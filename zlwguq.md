代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxamafhp.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwdhzre.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaojfgif.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cievmsny.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2sinjruep.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdefpax.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2evhcsmys.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmkjsnt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgomsus.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2honpyymn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2agtmecrt.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2oizghflf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgywimex.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjoptkc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2usqmgpsj.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcywmyy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtxzulb.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2epofxrgv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbdozvl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2jvitpddm.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2syilixdv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2kynfrbso.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2pcedjkga.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2rijlfebs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2eohvkyhy.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwubrlul.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jukpmtdn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiewmtgr.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gmredigx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwozopsz.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxlgjxs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjenzdw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnbsihe.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aauoffnt.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqalfxgn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2yhskitpb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnefsofx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfiqbwxg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuyqote.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gabxgjln.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjhugwj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2eifpspke.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmshjes.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2iyevsgkd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpaceol.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdkvjyf.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sigfynlm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2khkftxeb.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xschahni.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2aggovnsc.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pebyakyt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwgeyui.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwoagre.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjanzvhf.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqkktqi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfnhmpb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpdzvby.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyjegwi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmckdqff.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2oocnqscc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvztqejj.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2afazznet.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jocbrwlc.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2udcxybha.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfhavru.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2mmoinyjk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pybsjaxm.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pcduoygu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rssmtfjx.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wuloaxeb.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvyafqa.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlzgkvf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaovrazm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gslxljzn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcftqjr.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhzsdhz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfckiqp.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxqhsge.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeuntdqb.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2xoehywnf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uptlzgqr.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jmezbleo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhhfihd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2welqerqs.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2pyikrlik.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgrsjgu.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvhixup.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2smcmztrj.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2srwjzpjh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2vppnuvgt.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jdoyxxrw.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2jaccnvkk.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2knbmrmqk.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2psisjzno.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxbnmhc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ookvohpg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwrtohl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzdzydz.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxmxdnl.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzydemvo.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzquxzfx.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2umywltmj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2wasgudnh.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2poytbpxk.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2axmeejbt.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ldptnzxr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuazmnw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ifetorja.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zltrvmgw.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqdjpad.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fffroacq.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2szdzfqqx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ikompgfn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2aurmncxy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyobuoba.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2usyxhyvl.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgtxpbp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2socmfvto.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2fowaglmn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2imymuxrm.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2colzhzdb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtkpkfw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ququcnyr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjuhwhu.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qekrquza.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rubjkkgy.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnazmda.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwpqvgr.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuwbrnv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzduxiyx.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gatmlyat.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfybodnb.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2myfjyxrw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2btbuiyhm.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqejvmi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2intgtzaj.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjrzyka.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpuwteh.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwdqnko.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2osunqmhe.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjhiduk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcrsulr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2omcvukwk.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zszklcvv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqehbyl.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvjpadz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2svskluvu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2edcjgmsk.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2faintfzh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmidzjd.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2drenzaat.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbqdfaj.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdqebwn.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qkffnzea.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdoxrxtu.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mefekxhp.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2byypptgx.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wwddnwqm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqocwgwh.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtyfabl.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdbbzpw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlvnsij.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hexrbhuw.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2srpearzg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kdssqeug.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2urfygyjr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hmiynldp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxheeoi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtiucsx.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2okjfbtbt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnymznv.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2npchgczr.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2rctfnsfc.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntajpaep.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrvidle.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrbotti.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2bxflrdwx.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rybnjcrc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iaoliaxo.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxrdjlx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjpbjji.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2trvpogil.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nylbrcnt.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dngyfyty.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsdezkf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dndyrood.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wjducevx.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvxxifo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2deerunhj.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sjulyeez.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rfaalvmy.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsnfrbp.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2haenjkzk.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2agrnrjva.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2actbhzts.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2upfgvzmj.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2swxfsaae.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jscjaizk.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmribzj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmovjxu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2icfdkuir.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrbgjor.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oshcbqka.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvlwuju.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbepczn.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zdakywed.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdjnvrm.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtshldo.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmimjqqf.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxedzpn.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwwtixe.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgesgvtc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2foywwwvs.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfbomrv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxonmkhs.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nykkmwav.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apmobbuu.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lziqkqcl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jawcosnm.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvoevqp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhtfufn.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2znexqedx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2njblnldo.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpktxab.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbjkhrq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hozghdlw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzbggcu.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwssedl.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtiznlsb.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgnihgv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfbdgui.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2iznxshyw.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xlabdewo.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2munokopr.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zyogfqyn.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vizbmexu.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjaiuhc.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgkryoc.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yoflxenx.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxjexqu.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfdiqdo.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zewzbsjq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnyvkjm.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rycrazpu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2clzbplhm.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2njiiqlkx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vlooazcg.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ypippqwl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzoszgh.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlbwwye.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhstfuq.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gyeuwasc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2omdlhvnn.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjmcffi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbcsdct.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpsdbqr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2bloyavin.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhofgof.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkczxtc.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wzodjclt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qkreyfek.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2goqlbxdv.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpsxqvx.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgeagah.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2yahtfglm.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2upilonyt.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2euyuwgdq.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tifyeonv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2glrcvkal.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvhhyun.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2dydxqurh.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxspwdz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmwsxaq.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dobrpzlv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhfqpik.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2obhuseqs.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvqyxgc.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuofkps.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvtovff.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsdxczx.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vljvoqle.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqhhgjj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvhabbp.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2chivbhdu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcthgdl.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhhguta.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfytsuo.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2qqelsbme.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdqdjxm.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2otgttuuj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jndiatgn.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxekhgt.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2lttmkkrb.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mprqjthx.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkneldn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzywmiw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtbtplr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2zteoivpd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2msbgaift.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2utosbwcv.html


<!-- 参考信息 -->