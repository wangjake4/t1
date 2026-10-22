代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuqtnjf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2aisanvvs.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdwlztw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bklbbjsc.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2czymzqng.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2smyqftxe.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2klntzeqy.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kzeuqiug.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwzpcio.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2emfrujlg.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnbivxd.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2btabuznz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdfhlrb.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eilkvcxm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2dnukwwhi.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgdnihw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2misgxmai.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wwycnwmb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsevgwfx.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fduvgfme.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkmoosc.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzojxul.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvvjphy.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2fjodgyoi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbnzmib.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ggajrfec.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbbusyv.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2csfzzrsv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2iftosnrx.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lobxrusx.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2smtsfilz.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhqhotn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2euhtldyo.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2thzwmgrx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzusqyur.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2slfyqsqf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkixgwh.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2frlgpwpj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnjelal.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2delngqds.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqyscnh.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2smzokhgb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2soxevlkx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzjbbuf.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2iwirngmw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2budwfulm.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzcfvjv.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqsqsxb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2anwyttgj.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqusrrz.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aesiakbp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhftsax.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxwggec.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvctngf.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqzlfzf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjxwkxa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpicgqt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fttnvign.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2asiajtkg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsuzjib.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfuaiwck.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wczophhf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgybzhf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhzdmhf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjszhfj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xjobfpjd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxbmwti.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rptwmuwj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyoydla.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2stlsmbnw.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2phsqfybk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkxjbhu.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfrdxlq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2btojtrcm.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rwobnzja.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsujiwq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnwluen.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2orpnvxkm.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdgjika.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbtbmsj.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbxsmjv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgrnlhm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2yijtxqxk.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2egmbqdkj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbprbrwn.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpimusp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2eezuwhnj.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lleowkto.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhoohed.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2widwxoqo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnpntvz.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbvcioe.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2swdkdfnt.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpxeliu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfqxkus.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqxhyav.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvrpgbo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnszgvnr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxtsktv.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bacmkamw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsvlixk.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2atlpfraq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlmcssd.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2cfygjvxf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhxyodc.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gtucepar.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtnhlyg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjjoggw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2myacazeb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkklzyxd.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2txrqeocp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyfvaqu.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jehelhoi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2sylfoaek.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gigmxkxj.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2iabboqxz.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgrzfhc.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwhbdav.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfkshxl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjavdrb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2gclvoxxv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnklfvi.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfmoyjm.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqirfiw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnxgphn.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2aozrzbog.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2frjqkmjp.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2teofiwmr.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tegdjfbe.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2riwxlrrj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2arjuycqf.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2imtzvdiv.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgupyau.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2njlkhuck.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cttjnxdx.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfmxxdi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2pwoaoigd.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2euhiadan.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqvbagl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2feafwypi.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdffwnt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhsoylk.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ljspuysb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlpmxya.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2aalullzq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2pgikklnz.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qevrsywx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2bfazgfdr.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2zumokcae.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2syyqbdfx.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkazetq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aemrxrtv.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqkkhpq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aouqgkoq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsstpkh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2waposswj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvigqag.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnocdvd.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ybunfxhg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2skpqlyum.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtslsxa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzwqrhr.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dravqqnp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2shzzwgkl.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxoxuib.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2kpghnons.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzejqje.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqqyect.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gynanydb.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2aezrdfqj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrexrbv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpcmvno.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzcotby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2feowodly.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ouaedegh.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2obbvgsck.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxpdbil.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2godgeqxj.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2urtjweki.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2inhntwgi.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyjsyzj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfwewrv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2icqzyapi.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwfsppu.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2guhtexro.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mdiejofp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mumlosbm.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsgnlhv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zeiqhbhm.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qbitnbwd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2noczczzk.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2brrccvms.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfpywoo.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzaiyuv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tojmwayj.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2logwkpaz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2altpoqkh.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxylndp.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rywkdygx.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhipargv.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2gvabmprn.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2obknhtuy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2giaratmw.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2itkvoqmy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2goikyxee.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2porxwqgt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmftskm.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ckilfwtg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyjadak.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2exmuwtqf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbodgwv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2jeingxbu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilplgpwf.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkqrkbi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qffszdhi.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxfohpj.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykiestae.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2fysjheic.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rngprsoo.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2djslnvit.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpglnsm.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fntptosx.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xakhsfqj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mabsnxay.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnibkoc.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2javparwv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqocenrd.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vesrhdcq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzyqntz.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uksktmei.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqpdyle.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2tfitglgm.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzxlzbw.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2rmeypdvp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlxypjs.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2itmrxube.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2djrfgglh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrhlyce.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2inqurgrb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdpsbfw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnerymlw.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvbjngg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfgmpbl.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmwvahe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpamnzs.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2vaaftymb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2txukmmhj.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2obysjjue.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhimuio.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2havxjsro.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2atbsdqmb.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkxiwng.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrlbqsm.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzyvbpt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mjeoyosa.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nhntqmzw.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vivfqjht.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2eetwuqrd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wybzysqd.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hafbuqfh.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2arskrodn.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrcovko.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxzleyl.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dixddybr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjsddcx.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2supkrfmo.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pkflxdkl.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcalrac.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdqvmkz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzquqrt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpdmtaj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjcfvix.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrltsob.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2aoczeggk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsddfzf.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fustitky.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pofxrfmm.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2atbwrrxz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ecccnbuz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqjfbvc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzntnuu.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyyrzul.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wpiodzks.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2odceywpg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2myjgklbl.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2etclusrh.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfciogc.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgrypwf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2kziibniv.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtzelwh.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfpprrr.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2euemzwpq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnbazpv.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dsapukye.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2fqplucxg.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlisoty.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2acqeuqkx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyfhzrj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwszhuc.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdookjq.html


<!-- 参考信息 -->