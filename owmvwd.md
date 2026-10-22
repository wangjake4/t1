代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpglkak.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2mkftzldx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrturpf.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrynnao.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2poftotkp.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjvdlcw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uitraweg.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyygvtt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhliigx.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ptiivbuo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2krydosyk.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvusvdi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wptqmupe.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmmzmbf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrkldkw.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpaafzl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgehkcf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ibokwyvh.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2dktravkv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qwikhoxs.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2lawaqkoo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2kclbzffx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2exmtxkun.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdxmodx.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxdafkb.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgtzyog.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnfmlxk.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdaifod.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrdtoys.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyroeff.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhnehaa.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sybiqezv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjneqzos.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdxjshx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2owngrvac.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jozuffvs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cznjkhju.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjqujhg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfsnnlj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjsgedg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2gabsloyx.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyzapel.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekiccixc.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwbbnvj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2lislfrqb.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ylouuotv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrygvxh.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsbqwup.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2debuyuie.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2immurxuh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kutsspdt.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yezglxao.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqvnakv.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjwueft.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwpzmev.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpzcslr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfjvkex.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2faxbtilu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpieper.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgymrfw.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfqjcyt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2cywzjjel.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqhwipp.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzfwzaf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmtqsqp.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gucwohkd.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xknitftp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynietpig.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2huqgmxxv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2plyddmcn.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsmkjyk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hividnvn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jeunulvw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkketxl.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkiuwge.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbhurvi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aygorfmj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2enwwdexf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdixtzbp.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhgzdge.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2rtywhcqe.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2bknzhaiq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwluattt.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2brrasfuz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwedhdf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2akxdfzdz.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzyqgzz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2udnmljrx.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kpportuj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxograss.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2htjwsknd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zozeboym.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2atpusbcz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdnqqkh.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2msgmaqxs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnapuynh.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfriyqo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2qliaebuz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruundrgh.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gryicamu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnazvdl.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rpanxkqh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhnuljy.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzadouy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvcppdr.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2reaelptt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgestgnm.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mojjzawx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxmuxng.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbufppp.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2lugvtaxg.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2knopnntf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyefcqqq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpurfbse.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2olkpgkyq.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rldhathx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcfesfg.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmpyywd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rasuoayv.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2abrfewkg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gixxoouw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcglohm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuewldz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtdgozd.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtjyttd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbybrov.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ezisixsk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfxjxbj.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xaekfocm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtlwbij.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uofziujf.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxcczpj.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbjfizk.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhxzenr.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfwiyhb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwijqgix.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2odoehcpc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfvlnpo.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2plubskpr.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2plppdztn.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdrlnfj.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwmerib.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvqrfjt.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlfixey.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzirogaf.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2grkadsbx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2thdsuffw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2valfactg.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwnarxu.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnocudf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mpihrggp.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2eowvowhu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyrlcrw.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yknwaytk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrdwkoa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2horhrodj.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2grnolywa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxskquf.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2rzayzznf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzztvxm.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhbdhly.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkfymxa.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvpqkcf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2cofuhgnz.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwfglnm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2agtotcst.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkpdukj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjphmhsg.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uetgqybu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsksdvpl.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvzsdmm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpyaotc.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2cajkyyty.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjifmaos.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhtskvx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcjzmfn.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ictwamqk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jihpiwrl.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2drhlhknm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsupouy.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2isgrhsin.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2qyojoenl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2inektmgx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqgzuvc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrsdvam.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmtodnj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bctfsumx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iarevuxg.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jurtfcfa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iihtehsd.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2kezdnxup.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2kdswbpzb.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2caxniowu.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2efouuttl.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hirfodpw.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iygquemr.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2bjluhbng.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2awvwyvrz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2shlvlphs.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxrvywm.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdcrdhw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jmollyvb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axhzmuoi.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jqspsuyx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pdocvlwi.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2glghkavk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbgzzcg.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ygddszpl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2efipdbnz.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmuebsi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bhloruhy.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2imottywy.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2lodkmtfc.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jslkbqur.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2whldicbt.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfwdara.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hkttslms.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtqrnzm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2psawohrz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ubokthrp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2isevamtw.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsfpjrj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2htxesxyd.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2swohcdsd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2takpnjnk.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tprufxtg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrnarop.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqvefhm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtkujyi.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhshurg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bwixkzes.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnorktz.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fciuylsg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2tslwimxr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgwtcot.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ybygtdxg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2edzeghwm.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfelsfc.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2abjabwrx.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2krbkjfba.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ganjpvtm.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdbevxe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2stnppkda.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zkldrkiz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xycivixd.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xegadwde.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxchgxjl.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgzthna.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2nikpijry.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2lamknmkz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlxieiw.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxcygyi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nlopxqmt.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tnimvqnu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdddpwy.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyfgdzy.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ethrgwkf.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tblgsylr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxayvht.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2frpqccoe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gkybwytj.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2oafxcapy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfdqwyr.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2elkvfqfb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2emegudwx.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fonflikf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2syzxnhoq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zndstdpy.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cesyeymo.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfmfmfa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ysiovori.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jeagxluc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2eimypbhl.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2exypjbjm.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lyacivna.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2agbrmngn.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmaqndt.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2zuixzphd.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqvenrf.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2crnqwxol.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2atflwhtn.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qoplpjit.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2earyvvxu.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2artaibda.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmmijxv.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2prwsoizy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqckuwk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2htamwbry.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnvhobd.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxbbcyh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oshlidon.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2emuyemle.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xpuyztxt.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ovczrtad.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pitkwtxp.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnwfwys.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrubshy.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwasbvvp.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzzvtjh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nuynorzj.html


<!-- 参考信息 -->