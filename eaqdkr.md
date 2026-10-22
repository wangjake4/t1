代发 wailian999

);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyolnhm.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ttilxnuh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkncotl.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmgbssg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2udblhtnz.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2qeesumwi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxwxdcn.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2tymgzpgg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxphmimw.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbecsel.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tamnhqyz.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2epcorler.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjowkuui.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2duqzrepx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbcbjrd.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2sewutuje.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2snaqzmmy.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2fowgupyd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjuskxy.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2jihbrmpy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyzisnm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2cnogiqxh.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqpmbwt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2watjmnpk.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvegfrk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2uocsjqfg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbtahla.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dociqoav.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrcxrkr.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2czchgwmf.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2blgjhkou.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbjrlwi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wravbmwi.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2umsawagr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2zrddtdbw.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lhavdvlh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsblhzic.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2liedviln.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oovieyte.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yijnwzmo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdpocjo.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcoocmw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2hydvropj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnojhsr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2sutdmgqk.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ajoiezxx.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzadadd.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jbiwzaki.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjynqou.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wovuybmm.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mphcvcsv.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2npxxttyg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjshofvv.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bymgflza.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dopmqsao.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkhcvow.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yndasojt.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2evwbruvc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycthdcoo.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dsottxbw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ognlwpza.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlxzjar.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzolwlsa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfuxude.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbyrnlh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2frmwohvw.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2seothtsv.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgvluie.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2koazgzex.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yneniugk.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2azzvlvnw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbaodkq.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwpevgk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2olfrcnto.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2drxwurzw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2clctsvtm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgajbgce.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnrrblc.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkfebnd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2cherqtnr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlssntn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbklpoop.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2oazccjbl.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rbagnftf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmgcusy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmzpyba.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrywkqwb.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxwsbhq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2frfjtvpp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmgcatp.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mveyidwa.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2thhfwdpt.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2akgdtpsj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtbsqib.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2intcrrtw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkivcui.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2thbvxcqo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2owhjpexr.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ecahpkmf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2emeikgfb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuwxlea.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpwnudx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqlgqcc.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cwobivlf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2waqxvqbn.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfxywhq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wwphyoif.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wtaoeulg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yojswyms.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhdhgpc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2khhzfvbf.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2swkrvfyi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlbxbqw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2korcnapb.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2gemzbppj.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kaghyref.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnajdxr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmqyuab.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qorbocxj.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkkgdgf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrwwjai.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjxcske.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eadrectn.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwnymxx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjfjatm.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2izlwgbgz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2myfuojev.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrrazfq.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ptafvlfr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvitfdcp.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvqpkjh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ooijpuas.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mlilenlp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ootaoddu.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvcedij.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2oshbnnsb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxwmuzy.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2udimgziq.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2denkymro.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbdtqwi.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqvcadg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcffjit.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqaoxjz.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kljtzucy.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkufcdyv.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjvydld.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2tryadtns.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2gyozybpv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rngonkup.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2cafbwcop.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrcwvyq.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2llhqvdlx.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkehtht.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2scoojzcc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbzjapx.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyxnwel.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbxyoig.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2llzdzxud.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mstsfwdh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ducvxnkp.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qzozjsqs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2pglxhzcs.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjjqtro.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqkjiey.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rylgzrfe.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2oissezrh.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2abtdbuhv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjyvbjf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmqkizx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuiznmb.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbkxrxj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwigjcjl.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmgrjhn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dervuwkc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sqndrccd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2guxqzrxo.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2izdmooep.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqnjqoc.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2trzhzevo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2odzubict.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rsibenbo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2beqisoha.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zeyeqahm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2akzlncie.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvclfmw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2scyurozy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lodooegn.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgamgxw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfwoejj.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2jujakwia.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxqufls.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iryllisp.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvlqoga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2laebtbll.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuvnkja.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqrhykl.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2swrtlioz.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvvuphw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2onbhhoji.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2reeyzoej.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hchsijds.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jexbhdyu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcedopg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2eshahkro.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkhvnjw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aivfodlg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxetzdn.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2phjleehy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqelons.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2clcnixrl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pqimuulk.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhqewii.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlnmero.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uevqkarp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhwwhra.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dmesrwlh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxzslol.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtfjqsw.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqduyxt.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhwuulx.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwokhav.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzijiich.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2egorruyu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kueolntn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2znipommm.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2awhcxblk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnarbpf.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rsalwhjf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2elegeufu.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dxniauhw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmfdbem.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkrmdzs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aegcuucc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnufgrm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzzbkna.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmjryem.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmmqahj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2yapxwjts.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbqgxvb.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwsbcpb.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjuxsja.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hgchxsnr.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmkcmml.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2drhrxzbj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qukklwxq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdzvzwi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2edvsztev.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrpytvf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ouozcalm.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmagjew.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipapqmlj.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxwbaad.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fcudpdjk.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2mtauqpfe.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2eahhpzsp.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojalxdba.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dlimgpka.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyohuky.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbiahoxh.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsguydv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxvqaji.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhhxkpc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2liuldeiy.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nougwdjf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2penlrxqp.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhylozl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mdndxhae.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2mvssjppg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2hnekebai.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqbajhb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbgifgc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cchoomlz.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yszmaoyr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2bzebzeyr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bslpduvg.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvccixp.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bmghkouj.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xsyeeynv.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gwleyevd.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrifqkp.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xotbyhxb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2rthytisv.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbczfkf.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vejqjxyb.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nbicowzp.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2akjwcdrw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bxuowrej.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tsduxhuz.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxeovmg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpfvste.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hxooksjw.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2umbmfphs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wnioyceg.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2byvrcbop.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jathwqgf.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2atdpkssk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwyeoga.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbgamwq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqrxrwp.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdprcwu.html


<!-- 参考信息 -->