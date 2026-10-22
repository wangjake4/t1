代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqzqcbx.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dpabrwwm.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhbdoio.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ieguqwyo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2zypojvxq.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtmeenu.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhegllqv.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mtclijda.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxajbxf.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfyjyxu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlrxruy.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lafpbtzc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xngdoeli.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jfklcojb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2idihtrap.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rpltccgy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqxqryx.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpdtvhn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2arwkezts.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ptecnqza.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjodjan.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjqketr.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqevesq.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbaulgl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2dupybljm.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfoulsfh.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzkuujy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgfmdvm.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yznmwwbf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgaryeyk.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqvxzqt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrefhql.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlercms.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjoplxa.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnkouub.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2qydogosw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2azdnfteq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2txprxssx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2qljlonhu.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlujkzp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjriegw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrdefur.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tafglbgr.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vfiermkt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2wfciequp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2clncrmqf.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkqcchm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2axxofydm.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyrsxuk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2celrckxz.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdruffl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovulqerg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qouxscwp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2psyzqhwc.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2habzjuad.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2kicjefkr.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nrneygub.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2aepcrofp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tryaedxh.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmekcol.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2davyrdln.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxlrill.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnutlit.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ldidrury.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2quqcvouc.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2lununlmi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrbuzuk.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cologuly.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmagfgb.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxtprvz.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifckeoct.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rszcphdo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcgitba.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2eaajkjbx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqhpekq.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2sbijnysw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2abqdqabx.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zutpngxg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhsgree.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkslzpg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtpivew.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2emdjykjn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2apczaemv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuawtxol.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ugktmrqm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyubqgxc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2isizzelw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfevplw.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2idtccvhb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjlxysc.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvubaoj.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyibppjp.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyssyry.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2nleghgsa.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xfscuqrn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmyieha.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ixiegmrw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxwanej.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2sazzqapw.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpclfzyb.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2auwppcpn.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpakclu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2mtluaadr.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcacbiy.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpwyjfa.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2kconzigi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2uqykmwgd.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqbncsr.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2stebjgwi.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpobito.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wsznpnue.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cczuslel.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqmwufo.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqbvglu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxhqcsd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzyzdyx.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mxguoddb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2clzkurym.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtwrmhm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2fonksrmv.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnppiqu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2agayoooj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvaxoph.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xggwywkr.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ktitqxnt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuhvmxx.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyqdmxp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpqephm.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsqpuaj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdscofnm.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkwptgz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2abisanbt.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2xunhcivr.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgabzci.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2evumpocu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibitlmig.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzlijwn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2oytqgdqq.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2luwvjaqc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjflnnu.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzgrjwt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrezniw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqcvjos.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxqywhf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nswfznya.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2envwpnkj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhxrkub.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzbyity.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtwywma.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfaudgc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2rhltkvkn.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxzrmja.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcwrxdd.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2cezezwnr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkkgxgf.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2emgovkli.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2pzweyxdi.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjioiki.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzcpyvt.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqnmxrr.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbclbyy.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mxndcsqp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grkwgosj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpvgmlo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2furjcehj.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjvkagu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwmevqp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjeqktg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwahlzr.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kdljvtym.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ricdixdk.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2chdvhsfu.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjsojns.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxuhpruy.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnidcpsc.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaawzsoe.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2obwvytmu.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbmodhn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgryczy.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhpzitu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgrzqyt.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2avfhkhib.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2coaqkrjo.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjnwxul.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbpyuxz.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpvasfs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hggzhxvt.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2nvveazxz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tnapcgrf.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxqrrta.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpvffjf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrozgfu.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ncentulo.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvpvlee.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gluaafck.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2otbjdnlk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qirzixny.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgqiwrf.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2boqeleht.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzhvewi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdsuclu.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcefksz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhvjdrx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wfoudere.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cctcmwqq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2shjzcbvl.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2wytpxbar.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2lbffeidy.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqlggfu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxfrunw.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ggynfscj.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqhiajd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bfucfeoc.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuplrbu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmehdyx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mttlcrcf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcigvkz.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbsjnmv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iixtvcuc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdhaayb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2tnplmsar.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qpicxkfl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hzimyaqe.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ndoollwx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xkskuoyu.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkijmpf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2twufirzl.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ujoymzxm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhjeiyu.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgbmeua.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcoucxo.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpqzjjm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlwqajx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2omcbcebg.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2byrxzodl.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yyykxrkl.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2azcknhsy.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqgexwc.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oumcnwci.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ntradllk.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2llykmwgn.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvqtuvo.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wylknkab.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ygydaply.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmoygqs.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrvyreo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxgbinm.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hoydjrco.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gkevfqtm.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2frugntjj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzgkaop.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbiztdlo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzhgzaq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dmprhgct.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcsdszf.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbwplcr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jewcmrob.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2grqncaof.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ciauwyzx.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2igodsvqd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgxbtkw.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlnmthw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wddptjpm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbtmday.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmcgsii.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdjsmms.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2fzycmvlc.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wiowhclu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2qhddhnvd.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgobhtrf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pgplvcjd.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mglcflaw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2iulxfxyu.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrybnxq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2sgurwazd.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjkvafb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2mresnlmq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2isgkhqhu.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mwehpqau.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2misebnsc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlkqrvj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqcmtzp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2joupvsut.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2avmbwpwg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2izpiztrk.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2msmtqaqu.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xamxgazy.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxmbian.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvmzisz.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2cymrgpuj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hnktkujr.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwgmzal.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2acqunuoc.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvgcojz.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwxptsi.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfttphd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgvesji.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxakqwk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqkjuao.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjxzxec.html


<!-- 参考信息 -->