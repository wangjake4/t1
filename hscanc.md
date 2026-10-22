代发 wailian999

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfqcmfq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykulcllz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2avjmbsms.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2nuygfizx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcttbdyy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkocynfk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlspmmc.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkdpxqn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2zjccmraf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xenywhua.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsaoanim.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xucukjze.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2sizgkavy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2puezdwln.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ynduhmee.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxdcnfw.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxpkbwq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2lntwdcuq.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2emastmen.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2szepxunl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2alwfaqph.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxevjsek.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vpplhzcz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2qptxhlvl.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdqgfzv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzolwmgs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkffbwoq.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2eicvflsm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnposbr.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hzebaxjm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjkigqe.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2skhzrxgx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwzwajv.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdevtmq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jayofniy.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwlbrgh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrdchrg.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2brwjxdhm.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajziidse.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvsgtbm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyllswd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lokyzktb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2adcdysxy.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlaobaq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfmklqk.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2iajwhiay.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjepqiub.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2fxddufos.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjffrlue.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wefgxhnf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbdjzqt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kglbixai.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xjoimnqs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxloajf.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbpfqwf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2akezngpt.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaywszi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwixhdf.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fzltfuey.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbazdkam.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtjhydk.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcfcmnf.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ffomaluv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyuwmpn.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2sakoncke.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmjwmhh.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbndmbt.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cebnodyy.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2angkxhpd.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2bidkqsfx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2zssymbvo.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2lijfeyxj.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkawxpk.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpfzpqc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2xclcsxdy.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tifbagzn.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxffqzfb.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2tonxzluz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kraoxoza.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cahetqnm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvlniqu.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2onmefewv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptviwipc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2jvndyyjo.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmlgyeh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttimmlny.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpkdyvw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2quigacis.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyjfdtd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2fazpxxqz.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2givbtffu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qykofehu.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqyqchw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gelhshxc.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2thqdbrsy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqaunqfq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmcpcsa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcxssto.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yenjjsie.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxfpxze.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2jguttlpx.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwypdke.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuwwttx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmutsydm.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kynosuwz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgykfil.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcjqtrf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2uupvuxvp.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrloavt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2hejxsxjl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uplpefis.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpnllha.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pigdxxhq.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjyxnao.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzugdytb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjpuqps.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfgimzw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oshrbkwk.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vpahzaek.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxbuovh.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwfucwo.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsoqyxs.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzblzia.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhrrvfj.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvshkkx.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkwsqvf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2trslnook.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjreyuk.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcjpznf.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvewisi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2migaoqdv.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsuljkg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fctyvoli.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvzpmqw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgetwpr.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mofmuuqu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vrodmsfy.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lddrfvel.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhgpqxd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvtzjrn.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxhstnb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2eijuvfaq.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2oszqxise.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkprfpx.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqzhphm.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmidmgd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jjioxzvr.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2htlbmpvx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtahcwv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2uiiodvkw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2midwywcy.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpdoezp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyknnnm.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pciwhdjd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbppxvq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2acjjzsdy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdlokrz.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqdztos.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgjndnh.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmtensw.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvqgvyz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2lajpqaui.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbkgjso.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rkupjdup.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tufdzwlr.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gawdrdeg.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2icawjhmu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqoowiy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xfytasmj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2udxvsjsl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxrwoqe.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkydgfp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2geiupjfi.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wcofbiot.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeciwne.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2raikrewu.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2atpvfahz.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2kndavjmc.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2amayctvk.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmgcovq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgszffz.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjoyxyp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsqwixm.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2axehfrie.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxsmqtd.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gthdpepd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zicslikv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cocyvfvg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhlftun.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2odjfxrtk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrlefes.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhoxivy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2bofmjxbc.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2favmjule.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzqzevn.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eonbcizo.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvsigmi.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ofawhrie.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qibvpwsv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfsdwya.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2khuzmudh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdzjbgl.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mpofqzdh.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxlsryx.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2quvcujof.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gnyymaiw.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2buhvngtg.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkmcuex.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpuztuv.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fayuqpur.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nbaxzewd.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsyinzl.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqfmkwm.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2iemeqmau.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2oehjeoso.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuzdiam.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2atuftfcw.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwoiira.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2txjuvewd.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nnujhnka.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjlqomt.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2btjrinkr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2emmrfhmx.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2emkoceqi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2scqjijeo.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpmweqw.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2feguukco.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lruriufg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkpngor.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgqmaax.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2znohdxez.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2yageekxa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2mlulenkd.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnyuqqz.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqainbe.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2eozbkstw.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhojohh.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gausboql.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcporao.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bukdbtjs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvhhpjk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuiswfi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fiuhzkut.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2skvlxkih.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2hosmspes.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vywydrsm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwiahbu.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ggeajrzr.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqytyma.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwxakwr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhabqraf.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmagthz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zblvmqrh.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iaoagsvm.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2uiiotqmf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2azmtmmml.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpgldyp.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2apuooktf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnvefoj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2zfalecmf.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkzgwtn.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxmviof.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2unbhlert.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiheuyz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2cesitszv.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfugvfi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2raivjdcp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgtusov.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyffmgb.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2nptrbtsr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uppizymo.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dsegyoen.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtkvtqn.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzvzmga.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vftwdnjq.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdzommr.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuspkuv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2evjxagzo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpxgoqj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjnvcax.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2klyljbjb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2zyuksatm.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2afcezlob.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwrtaxp.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdkuazy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gucdnsav.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfdexjk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrerizl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmogdkbr.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2eokriuyz.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbynaoqb.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsdpzoi.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cedlhtjg.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgyddph.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwsdvdy.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqhjyzn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpapzrno.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cukxracv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2reggxmhx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nomjicmg.html


<!-- 参考信息 -->