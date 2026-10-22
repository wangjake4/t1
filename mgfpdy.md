代发 wailian999

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrqlxmm.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2magmnggf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2evqqjwlg.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rqitrqzz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfgxege.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2imeeifco.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwcgoor.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2shahjxgv.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2duldcxza.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2iymbnosh.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ruknozjr.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2qwydzdod.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvppevq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjkpaky.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2thinobzx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2atpcpvxe.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkoixny.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kaolxall.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2okwqpagw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lckihmag.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnruwbbi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vigzrtmv.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2aojokcgo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhdqyki.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqeygsn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrvjiss.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvijali.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eiaocylq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2iocykxzn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2fmchyenk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zagmyiiu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oswmkgrp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhzykvb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqgqqut.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2orptaqdp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2oguggpqx.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2upayzlnp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2bblwdybc.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjyzsky.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjugiuf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgfipfs.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkfnzes.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbxdlmx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2elmiplmp.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpexmal.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgirsieo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyrwrzf.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2anfzpmvm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdackvne.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqvrgkr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmcvkuc.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mibvvvgd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdrhgnk.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjrctcc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2inhcwapx.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjtpkhn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2dynqbvtk.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2tekbknrd.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlykqkfs.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfkvsou.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2iezpaqcc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqhkeja.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xasrruxj.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwsnckh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvypzjoa.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlqpwrz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjticps.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2mlikmevy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qymtyahj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmjhikd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2cveiesyz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqsfyjv.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlryfai.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2boqxzsqn.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2zirpttor.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2syfgcasd.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxjzfzb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2esgjxjmd.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgafauv.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2otgvqofu.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdopeqk.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xesikqmh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2deawspvc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsbpjqx.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ymoafxqa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhnxygb.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2prranwen.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2esxxzgcw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmoyqkg.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzerpvg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2tljmrelf.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvbzrxh.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjxvxko.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqyhleu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2oucpcopv.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zbldtcit.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tssabcpu.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ougtfvrq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyyzqab.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2uspbvukj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kevmwtrh.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfkcfbg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfrmoww.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxzeifb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtwdmhk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbhfjtb.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2fgybzbta.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2xmajiyzr.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hbipcwbr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmjtlmy.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cjazmbcg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2yebmgwjj.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2iufuglvv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2malmpmgt.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2arficekg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfqpjcy.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2euodixqn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjuwojc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2occwyrof.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fchqwlmf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkmzpki.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyiwynrf.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2giwowlqn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2indldzva.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jofpfbfw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgfwqzw.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tiamkgmp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyaodjtl.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlhkyik.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2qwopheoi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2exwnttgs.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlhccgy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vrihcccs.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2mikppncp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2guhsfpai.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2prvdyxec.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tazywwqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yibxdwga.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjoxjfr.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2janlmuyx.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2faqselwq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqwfybr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqumwiic.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2foovpyss.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxwlmth.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtdvlyy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdkvaao.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjamumo.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iejrtroo.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yfylbxbl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkffvkyi.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkmhsbm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fqndihza.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eliuwioj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dohlqjrc.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkbbzar.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqjpfzv.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xasdpdhd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2shbcajzj.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzhehyw.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmrdiqr.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2witmusap.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nygorjno.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwwbdom.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnyowdl.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfdvgwd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gjoyggae.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2preuqcko.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqstdmv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgxfuxa.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kibsvvrr.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjunmtm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hxklwfvm.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dtplhknr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mzeuzhpo.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlxtfge.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cglxfzss.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtwtwvz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlqxxfl.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iizpsvqy.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnftgraa.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdxhjly.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bsoajdvx.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqffohk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sufcexcy.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ehaewklk.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpoeohm.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2saysaqud.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2whwmdguv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yisbrdpj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvtkmlp.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvcqpvx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mntnybns.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwrybxc.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhuuvnoj.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmrzsby.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2yraemadi.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2zimsopxb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxjiqvn.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrzuyfr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uwylkdlu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2geenkzux.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzfocen.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhfvygo.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shqpdfjd.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2utglevcq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjceodr.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2junfpbzc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgerflm.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2rhggjeon.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fgchuelt.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2dttpfvly.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqjrjdd.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xpttsrke.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrxvukq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2meyljxhc.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2suossmch.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmraxka.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2moeffklh.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnwkdpw.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cacshygc.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbenatl.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2axndehsg.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjedche.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtqnqyv.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsvhqfu.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyoavrx.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrqxwkq.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xatozlfp.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2isavsvdj.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcrnabx.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzxkmoj.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2thlqcpjd.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqxrnoz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfseozy.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qgumbqke.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfklgbw.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qlokhwfa.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpvbqjp.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2znsgegvc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyqgizj.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyjlfoy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2byfxykuh.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkakihl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2wnotpeev.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjgllwb.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmxeyvs.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvzuqzo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwcqqvb.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2utqycuaa.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iefdrpvw.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2fraenbjo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpcqqhl.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fuynckzs.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdlyvfp.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmfmqlv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2eceajhbi.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kexssrzq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2euobrjkm.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuufidz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kepszuzg.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2utzsmywc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmxwmhk.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxrboau.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2okgfyrjk.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpsidav.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2vqffzrzb.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tybthicu.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyrcopp.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsclgmq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfnrszw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmhuehx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2kdafpjwt.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2skdtdvqz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkbwipd.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvssgva.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwbdqlv.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgjyiqf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2blywvutl.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpbubhj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgduiuy.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyftbdy.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrkfopw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nptezrbk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2peyqvufh.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvdcerl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjorjfd.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdpsvte.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2vwahcrpj.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2modoldvt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnhnqhe.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqwrtno.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnrwvus.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2letrnrdr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkxdaeu.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbjnsjf.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2iafvlcsg.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpiudaj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sebizltc.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxwabxi.html


<!-- 参考信息 -->