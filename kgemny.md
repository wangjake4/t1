代发 wailian999

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhnffkz.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2sseuosqz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqyvedz.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bqixdlka.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmxwswp.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nshbummx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2emhpqoke.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2jhknssvq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuwgmfa.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2teyacqmw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2oqftmcru.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ykaquxry.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2dohivyei.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2bwldjzjk.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwqgfdf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkhzkrv.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2qonyhjzh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2sulwoaia.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbndhlpq.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2toftazci.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybaazhfd.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwjgdam.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzpcwsr.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ztegcgtf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2guzszaiv.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ijphjjwd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmrdzrr.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2plivnapw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2csuekqbq.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2igyoebwb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kehmyrrp.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gkncctxc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2icsmmlie.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjdmetb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsuenfg.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2qcubovrn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkqttgq.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ypaobrmg.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qecwlpkh.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cshxytrn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnivozk.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuqqaln.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2icogzwtn.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaymkuf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2prdfptjs.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2isfcqrvb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvxlpqr.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqwlzzf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dditygzq.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2itmwjhpa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwsltou.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvaurht.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouytkubu.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sfefsaxv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wanuadnu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2kahzbarg.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2axrszmjx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuggquk.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2siexxvzb.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2pljkjdpz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2wqegagjf.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdgzygp.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ghorkjop.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwyzkhc.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rnskpoir.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdazvisf.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2owlraixk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjszwai.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2htkagxut.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnefwbg.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsbwxlj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhxudiu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyniqapn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgkgpud.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfagfor.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnigprt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvynsow.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjxenrz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhyiueyq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2weejzjpf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkzeupr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzvjbcw.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hodpmjtb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjgwkjo.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jftnrsku.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbaumzi.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hogqdsex.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpephdlp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvnmokz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvhbpzn.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2auhiqqms.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgkxolt.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkyeosg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjkjynq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfltpmp.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2eprposxu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uakkyvcc.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2awvapkpr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdqrnje.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsiabjt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyjocxj.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcrekqv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgiffjj.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfdwzuw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2icbaccit.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxqpaxu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvyiyps.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcuwpsm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2agmhdifu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsbjuhq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzomvuq.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2omaehcsu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvdzuiw.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vuiqqfdi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkendnnc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2potkagkm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfifcbd.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjpwaqf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2maxsrgxu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xervofkz.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqkgmsd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbyqktz.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqnfuej.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwsranj.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2alqrhptp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlrxeae.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxudwxx.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxzmkqm.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvsfzcj.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfdscne.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2erehzhto.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhpgixj.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmfjncp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxjkuis.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2iltlmynf.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2anrihfkt.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2myulgshw.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2fulzhcnj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2mlucdzjd.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrrsqdi.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hexvxwjb.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2bltlpqgx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2pocnkpiq.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2codabknl.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ullmuxsr.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2sldzommi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mclkhpba.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ivuxhlsq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqaxhwq.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqpjcwc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmamtpbu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2nczzyvew.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcacpeh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwguwim.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ontqnjhh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2rwalpyez.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxzwivu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkekzol.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2magkvrbl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqreocf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2cibtyowh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjutctp.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2idhfcouw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qaibqvqy.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvjulse.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2utzenqmg.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2thznzgnh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqqpoya.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ehblojiw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cerdhcgx.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2yvknpkes.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztiowrih.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2lbiogutz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpufoax.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2unxfjkun.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2stlslklo.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcjcxrn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2caspibbx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoijqhjl.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbdwnaz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2critvwpc.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2tniprjru.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgeapbq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtzssjk.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwguznk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uigidevh.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyyxwuw.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2jflmetak.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2cdspyccw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlfsqcl.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnzsfbb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uopnqbqp.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhfnbnt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqbpssd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcspvsb.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2sqevzqsr.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kupmpryz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrlpcyn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhbxopn.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdgiztz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oombyqmt.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2krzedwzx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jdullasf.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pcokdpwh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wftpvmnh.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvvmswv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsmkwng.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2rlljoxxe.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlhgnyo.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2alnjkkko.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnezarra.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2icivklsr.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvgpokp.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yaigbxyu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsbngeu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2htarlgaa.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aufommxc.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hztmmapl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oinzlshb.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2svejoboa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zavymhkp.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ellyrxcv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iikyxsfv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2iawebhzc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2geulabyy.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dzeczpnv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iieoyqtv.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oeekatvm.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfompva.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2tahyippx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bsohcyop.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nevpfwyp.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2guukfelq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vngkutjg.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sfibqzbl.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpltity.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2idmavvtt.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvilfcz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfimphvk.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuarkah.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkdywrg.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jgeomzsz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpwxfci.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkbxyxq.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xutrvmnx.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsolzlw.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2soxdjdsy.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwyevsw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yybpirbu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zoubvlvn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhvmstp.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwmbmpf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsihtjl.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ptostcvf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lebcvytf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2noyemghe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gbydvzps.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ypguovbb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbyodxo.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gavjpucq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2quohngoj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfajoxz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2mbellort.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ncghcvgs.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrzgglf.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2esjxxbnj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2chrbcfex.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkzotwu.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2obwqkmqj.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdelveo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmurzbb.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lokbwpsz.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2znxjdmie.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2deitthsp.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gmncnxxm.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2waeanwln.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gzurjjlq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuiimcd.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfjkgbk.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yjuykxms.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2lygfkvou.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcmiltd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlpztho.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfdzogf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2spziqilr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vpurvamr.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvqerkt.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfvfyud.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wjigddrj.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yprzdxhz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpqdsqg.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnefbir.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnpjssh.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqnrwvm.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2epphkpdr.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vgedvkyo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmwmqwx.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eooqijuf.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwekbxt.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2evhwgknx.html


<!-- 参考信息 -->