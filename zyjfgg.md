代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2itfzjbkf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2oskugpoi.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjzocdp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlcyehm.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2evrmywoe.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkhnsht.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkbussq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnrjrbf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsvuhxl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyreacb.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtcrmsk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2mohsuqfr.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2atbageqy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzgcydn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2twyletgs.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2btvydvpb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2feiigfhj.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bklowpdc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2usqobrvd.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zlexgicz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvijozik.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2jidlyqso.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nypbdyvt.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhkpxjm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gnevvqyb.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzkldus.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2krtehtwe.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqmjwjb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnsddmu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fruucwgp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrvmcsa.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2huhwlwoq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qshnegas.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cncavvlo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsgnnvi.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzlghvs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwjggdj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyeibdo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2yfihxhlz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwzzfwp.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2trnriwgr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tapayuwu.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyoidgn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkdgpye.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2odhcmgks.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzljdhc.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nqaogymq.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2uefueygo.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2goxafpke.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxbfqjh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2trlecxxp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbblgcq.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhtdxzk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrjdnuz.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvyxhqc.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tljahatt.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxebmwoz.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcrujnm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuixlmo.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2kucpwkzd.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcloeowt.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2roffltjr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2lkaouxpl.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xzamdzis.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkilmiq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ouazyeqp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pivyjofy.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqjrjaa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtkpxcs.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iefbyiwa.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xydmpyml.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2mvffawjt.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfflqpg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzauesrm.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2uefoshsd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2txuvzqqc.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2meqedqqo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2azsdgfwv.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nssgjbqn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2gawgmjya.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfheqef.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnckdxwj.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnhjtzg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwjzhyn.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2okfjbdhe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2etuygruf.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbvxntn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uclczmez.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2txnfzrtl.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwhkfex.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwigiyj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbwhrad.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2iboueltm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jayaaoru.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aydcqnkw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwxytri.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwswkhp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2vljkxiky.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbiseerl.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcbnwge.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hfioxuug.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyambhv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2whpfuvdd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmomybt.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2oqomvqmp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmpdoyz.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2yuugfgde.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmbexcy.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2wroypmuh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2dxobxdfb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwurgup.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdwkfvs.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2avxrpgyv.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2przvkymo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2umngbngf.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2skhlnfwl.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhlpzok.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxmhpoi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zofcpuxj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2epzuxyhh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2velzzfqi.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdpbifr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iducaivw.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlmmapn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sexxqfxi.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ewptpwuq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ojybjzet.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ebifanfp.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2bqenyfst.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fygnclih.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmogwsha.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2henvhmhb.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzkvpyz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvvszbq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxiybyr.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjqjtyd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtimurf.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2cjppetdp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrhofix.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vabsmdnw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tpltixrq.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wunbopzy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqybphd.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xhumnssm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2woeidvfm.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2utyzdxru.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnomjvm.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuvxafi.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjredyl.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2zirtgqup.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qajsljts.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mycultcy.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlihgktz.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jcouftqh.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbbicek.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qyolnggk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yjszmpee.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qowyopbt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oetwqbje.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2uledhman.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzptjvts.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qqksmxfg.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmzufga.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xruhmmqb.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xzntfnhj.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkxdlqg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2yprjjdek.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzumbry.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gcarppol.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcodtmq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmqrnaz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xnssqgyj.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdmnkid.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbcyhpg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umjwnymo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrwuzss.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ufumjkgn.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpenafw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmgjkbx.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxlasqt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2cryqlsri.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lscvqapc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpbwyhv.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrvfjxe.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxuptba.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsvungp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcdswwb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvsrnmu.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2otdajxkv.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbmxobc.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzkiltq.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2egcjpsyv.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rydjjjov.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqffwvf.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxyiznc.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgopfdj.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zchjtnno.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbtdoud.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2oijlffty.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xckmbqme.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2suzzlhcr.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkvjxqm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2nczalhet.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxaauyw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbjsxfb.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhxbdgh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwhwjak.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmznnxm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2diguxrso.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbwxuwu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwbrkdh.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtycurz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2waichjet.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqaddqk.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkuzgfn.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbpukyg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yveqhxui.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2axhdbpvo.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yzorvakf.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsttgkg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsapzlh.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2axhhrddi.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2iniuizka.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmlrgxd.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyachbx.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwmljiv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxnefgn.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bpoysmvx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfbwlon.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkjigaz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xcytsqls.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxvtrsh.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbbplhk.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uddvkttr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvgemyr.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2eopwcmwp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zglhihxx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkvqbxn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwqorcm.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bcaolbww.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2aumlvkco.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2siszpkwz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pizvvbhp.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2rllugkah.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwwzxwt.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2uzoasbha.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2saxmgdpb.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2crlnmiee.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyyfqcv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2yspzlakq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzaufgr.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqlsntr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2atwoxkzx.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2vsisiejd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbdsvby.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2femvckle.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2phhxbnls.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2aqorasdv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2peklkkko.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qszywpkg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihetjqgu.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnufvpo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xvoiahyo.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrsgvjq.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2uelbmmxl.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgcgimd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxarnow.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2obiscfhe.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2takcbsfu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2drlkotga.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2xidmdwcw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqrpxrk.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2joupqbvf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyjrnvd.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qfriojlq.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zavdlrji.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khynrkdn.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kcedrksr.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhwpikn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2oehsquso.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vltmlauz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2lnomwjvu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjygket.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfkhblc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxxnxhc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2busubfoh.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzceagb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsmwtse.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsjwyhu.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2tniwxqcm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsyrybm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ohykxxsh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzlptxy.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zemxxhpn.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqermki.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjcpcch.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwwnymo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdlgfod.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rklhzdqg.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvwhopr.html


<!-- 参考信息 -->