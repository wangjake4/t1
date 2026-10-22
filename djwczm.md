代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxivtrt.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2esbpakoh.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2bjodjwip.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgjayqc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgzkyxt.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnhdhgv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qriskjnz.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uaaohrpi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygznilhj.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgbuyzd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppufemsf.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2hiniylxp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbhwzti.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2featseaj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2drdvexkp.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbjdszj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2yduacgli.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kretctxx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hehyuhls.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjjbmqg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2apcokcdg.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkvcrxu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2knvwvfct.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2nioseswx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2akntjilu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ayiegble.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2jpugepzv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqxjsck.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqilwbqx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2oisdiuka.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2npltfoko.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrdrvob.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjmxeir.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zxiruwmt.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkujoyob.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjraqzu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjeekibm.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ihctmgkt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2xqaapnhi.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfneivd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2jihfneax.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qippuslh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2svmgohbs.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vunwilhv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2iywnudld.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2leehxaav.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvesxjz.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2wopawtwo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlqmfqp.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tnedsvir.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2igfyyjah.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yoghtaoc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvaxqfu.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqspfgc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvblanz.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcbiyoc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxlwaoa.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cidmzowz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjhsknz.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfzlujp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmduzvu.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsamqje.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qowjezzd.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqcwpbc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsaqukck.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuvwsty.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfeaingc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmhrlwz.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mftsnxms.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjaygni.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2igshiyrw.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2atsmwnbk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2tdanyurp.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuurekm.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqqcfqj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2coccicnq.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tshdolmr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2esbzeqta.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuujqve.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntasxvpv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmhestp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzupprk.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtokvzf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhhqyjr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2szmnpjdc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgminsnx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bszctuva.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmwziby.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpclzph.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2yiobotya.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbmvjln.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzjqyxv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2nmolaqby.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uiiftswx.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlxamjl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxphmyxp.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxzmale.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbedowjr.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mhemcixy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cofwirci.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cusiceia.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2uosbifkk.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2subskllo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2yauengzu.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmjbdxl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmtjuul.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxnfojp.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbuvjug.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wngpzeby.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wxltcjkv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2okwyzmgn.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bkptlvbe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2itmozcji.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqknyde.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrbvryc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpgbcoo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqzytko.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2zztmgmfo.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnrdovo.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmpqolr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjiixuen.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2svlkiwfr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmxyfvx.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhxfata.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrpgpzo.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhkytpk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2spqidprj.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2knnycloq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmkndec.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2crpsodtj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2lwezmdlz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2psbaxedk.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdssjzi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfzherh.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdjxupx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzauflga.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqyczzb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2spsviejv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ntajwipf.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2jymxdukn.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2igccnsey.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2uigzjlnd.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qspadwpd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsouyhtd.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjltwfv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2lguisula.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2savetecm.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzzbesu.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgtceqm.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2alysskmx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2fasocmxu.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxvdyan.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbukntfc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2gutjmpxv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2otbyamqg.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgxkske.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiiyqnwd.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2pyozafiw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2sqifnrvi.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxfdfhj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2idospctm.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgqniak.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxszibe.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2cqendopu.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2owhijiui.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcrdmmb.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjlsjbx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2fegbisyg.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbkexqa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmkvdpv.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfmhikr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxcamia.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuoyiip.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzwjres.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtayuyx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnnnqdz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsfdvwr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhtxdcn.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxnighn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmijizv.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2pukzthce.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxlgrlv.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2nagwoxyo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbrbfol.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zmihmvpa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgmdwwe.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxjssyj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrxacxj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfffbol.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2vnudksft.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yktocqgm.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqiaxgg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdcxdxh.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2rfacoscu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsogymwm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dfeygmim.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ydusbwmw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knvvcctf.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcmzafw.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpobdyu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2sxskdzxn.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2uchhjegr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2slrvhsbs.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcnzire.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2dsoxdfyj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdxvdjm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2quhyhejy.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2opxmzjgi.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tncfzury.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2awcspgry.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmqwcrg.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sczkukkx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gclkjlwx.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eujnqpds.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cckubnzl.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxlymoy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2udgczjlj.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2opcnxjxz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgnuevu.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkxepvd.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2jadnsnce.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhicdkr.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxybinv.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwqjoam.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkizqqf.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhiymmy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrxteyq.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2trrgogtj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yksqnnov.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhpayak.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2auiwducz.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2elshftzw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwrztrq.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxivugc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qcazlmxt.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2qbotzvgl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxerhpz.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhrcftw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2klmjtjyg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zyorsqdk.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2suybdlgq.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpgbmsf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhbmsvr.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hifulenq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zipqyckj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mebrzkgd.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbxdeck.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcpdlxw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyonszj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdpipsf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvxbuuv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgsmcsc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzaukhz.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2slnevezu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2jenixwgj.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmmxsvg.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2euuyedln.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xovvadxi.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsuxtck.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gwawpiti.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrjqabn.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxuxuql.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jmywikzi.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2btbhcugf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cybtfxbg.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nbianfvh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exczuqlu.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nkefgnfs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsjrmxb.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2smvzbvbo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjpdgsw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2crbyickh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2arlrmpki.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2apyzmpez.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwqhpho.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrnweqs.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhptfaar.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfzwpnd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpitiom.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zeyhphtv.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzaegvz.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkyvhba.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuwqctr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2weuplygd.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfwjqby.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gntbbuhz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhznlpk.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfpztcv.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rejqxlkz.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lidiprhu.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2eloiuabk.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kshkhdqc.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrgljmm.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vwswitex.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2baothkfm.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uaiyocgl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2snrizwvz.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hogkrrmk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rpozwizy.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjrccet.html


<!-- 参考信息 -->