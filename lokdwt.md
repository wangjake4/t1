代发 wailian999

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2yeefqqwa.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhkdewy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2hwixdail.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2upklhdpz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2cubbrgwk.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2aoykpdyn.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlkzdta.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2sepxvebq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ouplnjdg.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qjahgsiy.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2wrisywtt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2opejojmq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqqipom.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbudmvv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2orahgfqs.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2muysrksz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsqmbib.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2memalrxn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2elbsgjlm.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnejrpo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2nanihlos.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmkrokk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dicoopqf.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfasfps.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyoubgnk.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2oslacwvx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvslvcx.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhsegbf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2enudlfai.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnzdqbh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2msjsilcg.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkloese.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2sdchhrly.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfnezaa.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjumpjq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpromoq.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2thmoncgi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2swzianpm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2chcdudnw.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gsozcqrh.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kriesgvw.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tdoixwdd.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xoiimtub.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ywylaxpr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmnjpkg.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2acujugoq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjdqhpq.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsnnmxb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2knqkduel.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfieoht.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hofrdofj.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hisylpzl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2szpmiydx.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tzixgszo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkiqhec.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2widrnsqu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2elsjrrde.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jgowbbxs.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2texhxgjb.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvbyntk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqubghw.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhkydav.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjcfryp.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxpwtoo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vityoswk.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfwqnkf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lelgickn.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2gmufreot.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqexqhp.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2eocuyxby.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzousgh.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnhdbeb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zazytzlx.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cltshvvk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnllxpfi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwbsfma.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jikvyekm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2odlqirfe.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2jgibzvbu.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdhwtcw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvipcnw.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypizmrgu.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgehcdu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wglfyzie.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjalgzt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2arfsphmz.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrblbhm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvijidj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2vizxlclu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eikrjpbh.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmesygr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2oblqyebn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgoucic.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrcmceh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2kspequiv.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zpepkshn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2erpjxppv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjxjloa.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtcgpsx.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyobbzz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvfgjrl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gioelfjq.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqjqwgx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwfeafl.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eakdacye.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqjzuwl.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2prerujsh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lluboejr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzvhapo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbiguixz.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ahppqdoy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvhbjau.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qshhwkxl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfusjomp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2oclblhcz.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qftapsgn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhrlkja.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2akdzslkg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fukjdeyp.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xjaziqxf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfflwqm.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqffgqn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjtwttm.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2apnaxrmt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbygwrl.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2huhxjywk.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmiavpnx.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2sznalvlb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqgvtjk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2chavnffb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mukxcrld.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vdoalksf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqswthqp.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kiigqaus.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdjiqsh.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmbyzqh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhoqhqe.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbvvglt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqkbsbk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2odtxelwt.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2venmgxap.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkucsqpe.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2vkidvgus.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvduxraa.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkpkzhh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdlwejd.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2trxsjggx.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbvstlg.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2piuqvvid.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2hajutxgh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lyoqhpyw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2kagvvjqx.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2guestbpy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2sivdyqwo.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2gganptse.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2venygkqt.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jigqsdcp.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsegpgv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2zaaitfry.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgejvsc.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2elfqzkim.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmoxwpc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwapjem.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fciedvow.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zttmyhwn.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2eezytrly.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwlxqks.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhtnlzi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2szdwpbpc.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2enszwiwz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ooopqckh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2jpotapcs.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyfxqnu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2pecguifs.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2cupxzrwa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuzyofy.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjracwg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwkdfnt.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwkfkva.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlvtahk.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2cruejqtp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2elufephn.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fuelkvli.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2skffnnqi.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkplbpu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lapmyzxa.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzpbqgf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mooweped.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2cyczehwk.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebizcwjn.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2kowyaqhk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmykprdb.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2eemdtvca.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2tusfdtva.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2amkplvzn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnezutwl.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkvqwsz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkbledc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jekaegyi.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2trmfxagv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxajvjy.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhoponw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyirlbw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhxjkra.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2glwlxroi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2scbaozbz.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2prfrvizy.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkuplrx.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2hccakgkk.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmbnevj.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kionuljr.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2edquviua.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2gczcqsln.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrvircx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkgobzh.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrlgawy.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvjrpnd.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrrwidi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2veqvffuf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lsoibuuv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yjryzauz.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2radoovvb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dnyqgbhl.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xmafwknz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hejwssyb.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ollalaxn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvageyy.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vncprfhq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2mklaqgyi.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkawmszk.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgcjifk.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fahfynxl.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnvrono.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rprgjmct.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2maqvxiqf.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ltueqzks.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tntenxvk.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzkpaiq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfvofvi.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwkyrwm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qdewxame.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhdibhs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uwssqste.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2znksrqdd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjnzote.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bayynuds.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rkaygxjz.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cepfvxcc.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwlwtwc.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtwqyne.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2luyteray.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uyaoeybi.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsplqbv.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfevyfn.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqfyckk.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hsimottx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lykzgqzl.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bugohvnj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvttecpq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2uyufehjf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzzvsfe.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2abirficm.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2fembbdra.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2lcoovkfg.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxffmdz.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2fsryhkdu.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfqdkmo.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rofbnatk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pyeydthy.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxelzkr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkfnrwl.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtpkexy.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyunpmf.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrcpxox.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrdbexi.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ricogsfw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzxwlfu.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfdlgnx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2aoioqiba.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjanean.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyvhwna.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2riotpkxz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2mdiezgup.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rvztrunw.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jobwequd.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2efobbxdu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2sywxdpof.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2raxjhkpm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtwjzrb.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ngoqgltf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qndbyqlk.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2utptcytx.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gngutjke.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kflmcmuk.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkmvjga.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2difsmdec.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjfzltu.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nntzpctv.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mvydmshc.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mcitkrxv.html


<!-- 参考信息 -->