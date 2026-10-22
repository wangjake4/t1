代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmzpsiu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqfdsur.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2hiaugxdf.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2lwudxexy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzmeste.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjaegtx.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ztilpzko.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgszsrxh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmxbsdo.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnwaifc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2atigsoxi.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsvmfbi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlozkuac.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlyvbwo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvjncvk.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2aornuifs.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2toyrwhdp.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ruezharg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dutiztkm.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gplhutfe.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryavcmkw.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2smvzmklz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mchwzywf.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpqnwww.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxhwsay.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2qyeasncy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qhoqxjfc.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwazmep.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgczyfa.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmlihwv.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvboycc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvbfolx.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbbcmwv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2kokmfnyt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkowkjk.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gmstygmr.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjbbpsv.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vpelmnxy.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzhcvox.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqvabnq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwnynzt.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fasdincf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2skvuxyan.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eyufscmz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhrejdn.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2iumedxst.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eienuxpr.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhwcikr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ormtmybd.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wqefdpaq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjwkyms.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2zuowunvu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjevctfw.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lscjyxbj.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfttswai.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bnodzhdy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2woywlkfl.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfuncwl.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwhcvas.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2diumxdnk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fniogkki.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgeuvwa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhauyrb.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqfnwij.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2myeminzm.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2txybiucd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpilonq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvdncuu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrlnkju.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2labzxhit.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2oilvpupb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsglhhj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2belkflvc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2csfuouhl.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwhfmcg.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2wticlkrx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2okdhxmnw.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2atpwtjgj.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrsdzzz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwaslvo.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tcumagfw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovutqqtv.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjybhat.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkemwkti.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqmmgar.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvmzchr.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jeajqufg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgslqjf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcigwebz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbirngkf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjenewpw.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgblccq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcutxnl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2zifotrai.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwgtshx.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjsxxxd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuwtmvb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcswzsv.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjqjwiw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkssxhx.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeqjdoy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjsmpnw.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lguxqzuh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2eontdqxz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmmebsu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkkihco.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2owoaaknj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2utapgtin.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxiwgkn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2scztcpdc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2brinzshh.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bibbuxso.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcknjyzz.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcbdoqv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2newnjgue.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjnprxy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhyryoy.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2guepqtgw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifknndud.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2eakcirko.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2oglxtplz.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjwypkq.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuyjedc.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsapxxje.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhldgluv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrydvkxh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryizrodb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wficzmcp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsohgnad.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdpdrkm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2boloahia.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2helrpiqq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgmnzvy.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dagjdczn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfpgbac.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2elshkqgs.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2esxllobs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqzipzo.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ipiyawcs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2whxqryqt.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbeaqym.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2npjnhehf.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtrzkrm.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjbbqjq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsliezs.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2opgsscre.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xivfcepq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2esqgijef.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2skqpphdc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhixsqri.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnyvgov.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqcjifv.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cucrnwua.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2muslfgmj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2qjygsidu.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqscrei.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xduvkcto.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdnpgrp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnnpsqn.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlflphn.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jecytocf.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuemjhl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uxoxriqh.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pitfoyjr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2afqfiana.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrcrren.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbiferxu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2bssymqtx.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlgjpkb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgmdscv.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkzcgad.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfrenpt.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpljkbc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhjypix.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmciomf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ziphhsmb.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2truhevkb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjciefa.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqdlqgy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mexinfdq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuuluaz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2czizxwnh.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oeonkltx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugamvkve.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2bdircxox.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbsmpjt.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ctldztwb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpkzkmn.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ozorkfdb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2wgttnkab.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2druwypsr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmobdaxw.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbczkjkk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2uoeczasv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fndoaoop.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2igttnjte.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2agbjdxln.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2kwybgqsm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnmehws.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnsxvww.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2etpmnfoa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvorhxs.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgeriyt.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2cqykpktg.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqipgcw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdhimin.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbwazjv.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2euuvrvro.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzkatyi.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgvflma.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjawksdn.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbcnnwj.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpqnsws.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sftrkxqc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2giadwiwf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2amtmhslq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wblgrobp.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jyibshmk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sanhwnpp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpqwzvv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhehqkj.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mmydwpbp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yatmducn.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvkvkpk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqmvnqa.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tndeuvdl.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2necmzzuz.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhbsjls.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkktqnh.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uetgwfqo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwoizty.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tmusglry.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2afpxhqqc.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhbuotl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzewcsj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eobwkswj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2olpvrbpl.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2byejnqif.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tnexyppy.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrryotl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qsipfaga.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2svssasqs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwujnso.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2epydfczc.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxcgfxg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2kimponnj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2leewheri.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wcviygfl.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbtxpaw.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhghrzi.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfbysls.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrazahw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ityhawoj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eneivrou.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2peqnaprr.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqxepuc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdxttea.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uhurunwp.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ppglygzg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrcqnyh.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpzgzxx.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2aoamtsay.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwnaexm.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ehuxfkkl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjmsnyt.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bshxupoa.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2iracbouy.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrpgbei.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkpkvjk.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cidpicgj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgbvcck.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tqapkbkk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mexdrowe.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2pcefvwzg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2edhjjapq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gexvkofa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhicayom.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fughdtjz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2otkiouul.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrwwcib.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwbtioe.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjdwuzd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vgeasvgx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jypkytxd.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2alhdhlyl.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqohybb.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrwhpkv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfmrebb.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2przcmtwi.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2jduurbvb.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrafhxp.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbdyfhv.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwdfqif.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2seppduze.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvokuun.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2eykpcifk.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2fjivhesd.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2oowisdlj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2tzaejnbo.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2micobmtr.html


<!-- 参考信息 -->