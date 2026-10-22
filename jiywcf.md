代发 wailian999

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsklmhl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2dilcezep.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjwinai.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ctklrnfs.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2gilinxws.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtpqwjw.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2likwltap.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2tlirwyxj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jjshglvi.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvyshel.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkpdecd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtbkjre.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpsjxim.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2sxscujnc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2debkxwbz.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxbeggd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxosxgwc.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcvmvmy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2thtwbxwa.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2czuralmx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2epuwrlpf.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbixjry.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgpbzze.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqiiomu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfytsaut.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpsixnw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zncwtgio.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2todfadfj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qlexgfxt.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2vdajjijj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bvckvuxx.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwfduic.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2wadmraov.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnypqjk.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkdlior.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsxpanw.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmgmlwu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdvqxkr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2banxfaed.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tyeeysch.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uedjruzh.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqcioik.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2btlmxolk.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2edbomgjf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvhbxwr.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgksocw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2zspugybn.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ordukjfy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlonico.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2smuxyqmx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zowcakfa.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lzketekc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfppzqg.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuzjwgf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxwqjyk.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdymknx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdkhvpm.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2etohrxwz.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbbfeyw.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kivuvqob.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpzobaq.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lbienlvj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2biffkuox.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcbgxpi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrerlwzt.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwtvayh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsgtwsp.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2krsvttnc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwrgshi.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcbkouc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kunsjxch.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmvwmba.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hadcmeav.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tenpbwpc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiaolzwq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkjdlnl.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrgvzze.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2egfppztf.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwmdqna.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2lowncqor.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2qojrxhvm.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzcgtvh.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wndiqhkd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyljxut.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2chxupxey.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2byldwauh.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eevtlpow.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkkslpa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvauzrlv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhunazo.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcthraa.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2tosygxxd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjuayoe.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwpsbaq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbndwhim.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eppyzkav.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnyrfpu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwmuiar.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvjszdm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwewmkt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsurcqa.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjcogpv.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qihqevim.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2blsqfjzc.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qafydkzl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyyruqn.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqqgjjz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdiqizs.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hhttwlid.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxpkvao.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2obdhrkwo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdrrsyc.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yowiiqmv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfvxbax.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvuckss.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqdgwaa.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqslkfov.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ubckvkti.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlxdjiv.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2isadatcm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjoitvjp.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2rcctmcfa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2swlyhvxl.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxxptkp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xhujknfo.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2srcdmrqo.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2knbfdpcy.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkokzrf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvbyjat.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zljvenvn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpaajxda.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2axoxfmmf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxrxbzc.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2txhfosls.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctedubcq.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nmeoilrc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbugbzgg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bgeiehld.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2djrtmuuf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrdgjxm.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwbibxz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bztyarvs.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2dhypiwbs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvbqtdb.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqyuhvz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcitmlp.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwqcbjn.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcmmdgo.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbgntcc.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2skrtrcpg.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2udtcovho.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyqjgrm.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsjkuxe.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwjlsfp.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2obqzcjze.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxokocvb.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcpytxx.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwyltqt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2hswzrxng.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfdmgxy.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkjaivq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxbrwji.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpiipnl.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cszmqvjn.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pibarvmv.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2eijurrnu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kehzuivn.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gyszqmwg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzgwxix.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dcoiizlz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbpafie.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvgcbfy.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2omkwcrgl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2lihbevol.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2auehdqoc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2nnygfufz.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwsqafy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjyoyoi.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2noyayzwh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbvrgjd.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2rbidgdwa.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kggzvjsc.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xizdnyvw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gssjdrwx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqjnunq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlgikqp.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmdqtwv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpcxnom.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2recrzwdh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpjcbsx.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2htnjqfft.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwlmvdb.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dgaipwji.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2toceovaa.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bztwyivj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxkglba.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqaumnzq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2tosqnzbf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lufqusku.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2plcoobtd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rvejvbvy.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2snoqqzjy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqbpdnq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hljrldor.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfcybdq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egqcfiet.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ekagmrpc.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2qonswsey.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnbjcgw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2gbolyjnm.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gscxledc.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2focjvagf.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hblzwpyi.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aavevlgm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2edmnznbr.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnxoguo.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmkzzll.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mszxuwrt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgckckf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzjtxvg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqepllw.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfiytzm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2odyofpqz.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpqiony.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2avjgjyqa.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aavgybdf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyiszya.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2uvheobyn.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2musgjsra.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjtcuvn.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlllhlda.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogewtoai.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2twcndgcq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2crwtkwaz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlrbryf.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsyqyst.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tofcgthh.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2qitmrvzr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2alfdoipi.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sqenwwly.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvfkadd.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2faziwjfm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsniqnv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwwwfaz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwnefoe.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjkxkyh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iekgqlmz.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2utudoixf.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ciiusdzy.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2scioyuzf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aenxahnb.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2saznamxn.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlofjyx.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rkesamiw.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oihmhoqp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sobrmglf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gheujigc.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2seziojfw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxrjwwy.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mkypbcho.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2krumhqvk.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmasjcg.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqxjata.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbifosx.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2udoqyhyj.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2yfexqeaw.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwnzsid.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uumwqjsw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vxntxxmz.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzfycfz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqxshlf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uvozekpm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxpplih.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtmclpf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ognjimft.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zoawwcnv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mixeyvvn.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgxjcxq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnkwrtf.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2aurfkvof.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcvernd.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dommftqr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2viazgcuc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xwghdwkn.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxleueuy.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvvuutn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lsuxfkwb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwvlwrd.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlsngrp.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hllpzewj.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2aixmrjgv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zlseacnu.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcfhtwv.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeortwd.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2icembnun.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mggivizu.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbzjurq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nzebqtmu.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2aflcfnpi.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yjblznxp.html


<!-- 参考信息 -->