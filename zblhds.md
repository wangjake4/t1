代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2nfabpkpq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2efhhndeu.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ylucglgo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2tppvmbxh.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2chtemqze.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2udjmrdld.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwjvbjo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vztdltte.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cwiviwgl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfklhxvi.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vscoeoly.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlbciol.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2recorytf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2hugsxsed.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgtjmai.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjauisn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zytieirx.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2taogersn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cesapggq.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcwetlo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyvanty.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2iqksagce.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzoqscfp.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpabtrc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtqsghq.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2oclneocg.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpggsfkf.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2cmliyula.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bshhmbwi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsrgqrd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2elfxxpvf.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mebdukoy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahemrcxe.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmeicvk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wycjxrdp.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2bhndakok.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxveywer.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbpcwzo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnbbhir.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmqmwkm.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbjlqcn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkntpbcz.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdezuia.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dluslrrk.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2psmrasat.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmzthjg.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vscoznvf.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmhvwrj.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrtiovb.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbdgzjn.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ywedmavs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ensrkioq.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeuncrm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfuokati.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuyfzjg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffafybyw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsghyboq.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2gknttxsq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2kmznykdy.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2klwxqjxo.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2noplonyg.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2jgacbaat.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2czplahlm.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjplbyo.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2emothsbu.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2etxbhfqi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bcokxrod.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dxyjkqaj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2dnigppjh.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wnddgbwa.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkagwebk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2jigskflc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvaledu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxflfqa.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfidihs.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpjvfcb.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzwpbpf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwzeqyp.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcfuytb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2djzaywgu.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmrupus.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmvcnob.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyfqfkr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2odbrbbxc.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjkcerd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlxvxly.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwtxqjc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkznomwb.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2abqjaabm.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyorarl.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2gacmvkzc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2oerakkar.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nzncwoqi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2muwwskyo.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mtoxawsl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpzscme.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhntkve.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvhgsio.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nplbzllc.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpzetol.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lglqlsyb.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjnpidm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlaafgx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lslwvhvn.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qhobgrpa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbahzhf.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzzferd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmauhyj.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2upyzyrvv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmlriuv.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqgpjbs.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjskpva.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2rebffnan.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gpovqejh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrytewn.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdqzjug.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxcofbt.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zepkjtkj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjiyyvop.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hiidbqll.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xkutjecr.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwcltak.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtlbhka.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2icdlatqi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mqaoxxzt.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kntctujo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpkqpaa.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcdhubg.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhwrzlq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmskzxj.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2azlbnfrl.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2oambnnds.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrdmowa.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcfxnwe.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lbewirsw.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqlkjlr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgulqrn.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xqinubjf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fikgurte.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcibmzm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuvrqtv.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfgzird.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ffknmogx.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzyngma.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2upzkkjnk.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwnxjwl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wezqesmp.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xuefmnob.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqhdwui.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2tznrdvsx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2volgokcl.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwihxbt.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwxahac.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbgoewf.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhjslgm.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tffdcfvp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xcimvtxf.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2csvtphzy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbuhpbh.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ribwnzgm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqgpygi.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkpkrzb.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxpvmzo.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnniyml.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2guhrsmnt.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcfupfx.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2sidrfghi.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lypsxstj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcbijvq.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qndqtmul.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmedalm.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gldjyref.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxomejl.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdmpdcy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnnriuz.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmduhig.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkjgqag.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ztglsxpm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lcerewqq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2uyoctxyp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcmfbtt.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2izkfnovp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2kycvuxtx.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsvfoso.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2laktubvi.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2yruczkxa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2olauersh.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkkrjnd.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2verdipzt.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lsenpioj.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgbxmkz.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bynuowil.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvfbpfi.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2bxieyazz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbutsff.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfdikrn.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hgiicgyi.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhboafw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2njwzckpq.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkghtnl.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2irluaevz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxapwom.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2txxqvrip.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pytupsma.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2elvjgzgq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2riunwblu.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2grjwwbgh.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lospeosu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbcaqpd.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2umhumlzd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zlafgwky.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcutsvm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyibual.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ksahizic.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2odwviftn.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vemqrhyu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2keltowvo.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjzcdsj.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2omsgkjwv.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2igdizhzg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrjutxr.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kfapxxdp.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2aiimskoy.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2idhliyvy.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtlbuil.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2abpwibpn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjtxjnn.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2saynquqr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwyhnob.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbbyzfc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2raqmnfak.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdchsbq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2psdhbbff.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nnviqqbr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuhvjse.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvsvfqx.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2hbprazjx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gynxwwog.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbybdfg.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yvywfnfq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2xwogbjgt.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2muenjmch.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2afodlzmo.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2wavxryoj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xybuowyn.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzrsuqq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmuhesr.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwvdyof.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2utmbtxvi.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwsfxcx.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2tboxphiw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zgodbkdp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2gisyahpl.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2qanxhwvv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lizihqyt.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmnkqyr.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2eveggcoj.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2jyywuczu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjiefbe.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2weiufjbc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydeyftro.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dpernezh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ezowitpp.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qrskeubb.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2flvqqrym.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ygunasxy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkklcbx.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtlktqw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2udfhdakw.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyokpvw.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2zhymjcbh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2trujtwhh.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rokoubde.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qwetgojr.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvucumk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2xelrmviv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcgxabs.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbqxubt.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjtboul.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrtaoft.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hywkjtby.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnyuomt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpccgtn.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uuubddbj.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuccnmwg.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tudlqloa.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2momiivrb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdzghlg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2yqalcvpc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rlavofgm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvacphby.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2izeigjhq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyxanbb.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2slzmnhgo.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvajuzq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2popoyfch.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2upnggsbo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzmnzwb.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvpfujz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcnmmof.html


<!-- 参考信息 -->