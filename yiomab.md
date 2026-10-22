代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2jhafecwp.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbavvfaa.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgnwrpn.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2tsafoqnt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2oxffycqy.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpyygse.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2delscycf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrkkjwc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2pofaegwl.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkxoxfv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2unhfkuhm.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vmplztcj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2omjbyuih.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2phzzqeoj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqjfgud.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2xyatbtcr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikigxmps.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqgfqyp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vczznojy.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnpmqec.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mquscrbg.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qznreskm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvuojmgn.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnspsqy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzzapfc.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhfavrd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzbwjef.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2qnftehml.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2behlhmbs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2znzgyeqj.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcydrnt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rmumlmyv.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztudkslc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ztozxurd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvcclei.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2odnmwont.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2izmtcyup.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkufcfn.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydywrsts.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fegzdfkf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbumqkvm.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqwxjhh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfyihlr.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzsaikk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhosogjs.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xvexouds.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fklellpg.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcklioi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2txhyshde.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uyerwxtf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtrddoi.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2luokglta.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2xaicgiug.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuszwxz.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrgcjrt.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnuzaze.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfjlwqu.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyyyfom.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvbhbma.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2exibsbon.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uedmvlts.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmiravr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkzriqz.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2irjvmuoa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bypbavdc.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjuytsp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqxioco.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvszunq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cazfmjmi.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmrkzkj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfmfntq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlrmszj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnasnez.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkfrflw.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2oqaiqazh.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2sdclfgsx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2calssttu.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmikiopl.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqdcqcs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmnygzr.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyyperb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnoagphd.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjlzytn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vomohlcq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnedoqd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzupjww.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvoslltc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwfnjxs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yczkewnl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsgrauz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwetrah.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2txeqzsdl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwjnphl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjdslbm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yofwxnbi.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pfykosko.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqevfbh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgxduru.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rjiqbjbw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgaqeww.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbbwrzt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxnjjnw.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqungjl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2iurfspwu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2izllvore.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqctiql.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2irbzsrqk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2timfxfty.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2weunhdvk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlyjmkh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsegotx.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2jotwswmw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzcpuud.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kcejfoit.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2aoeexmjs.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wivoahbz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdzbsma.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2aubcxgil.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyrqfhz.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2frvgzurc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zxblhiia.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjxgbpl.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2dswhdkcp.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdhbdpm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgdhrmw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2esggbaqf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmspwbvg.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2trlxxjbi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwyesbc.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdbaued.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfgspwi.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnlwtxo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qabqhcto.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bejkttnc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrrsudz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wujscljk.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2higavomb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pujrnnja.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2bggmufqf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ribhzwfm.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eydewcmf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqogean.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhfbbuf.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnjhcti.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdcuogl.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhonkir.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gpergiwu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlivmmk.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjjvqfu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsergsek.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyyprgv.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhgapmv.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2icudyhzx.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2mssslmgo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsysvdd.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkklhgn.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yejbrvdy.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbviqei.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2olnlwxca.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfxguep.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsjxnxs.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ajderuir.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqzxmme.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmuqgwp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxkrzaa.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyujhpg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2snuafbnv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrfkzpj.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2moplpscz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcygcmig.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2omczmeim.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2umniypib.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vojiuilu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2lfoomkga.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2guylfexr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2atlqwxhd.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2plgbvzds.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2thcocwpn.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkyglts.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oepnfmue.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ralwzieo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgaoggqv.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbkudzd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgicybp.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxkrqci.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdzdnvo.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2sizkwpfx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2fowjzwpv.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tldxegen.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2iveojbmg.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qybnpiwt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkkorlv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvkrysb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvkpsgf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2umfsciac.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcmixug.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uinrrost.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2uzaxlofk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrqmxkc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdinybx.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ascqzsyl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ciaufklt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2dplqiups.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2oqntlrrr.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2hkknquid.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2dblajdvt.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2drxzndhm.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wytpyzqe.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2titfjefn.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhqiqpg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnwrowe.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2osehxhyw.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbpwwcb.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2odscwnka.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfptwzo.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbdiyzf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyfknrp.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fuebpxxq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uptwskrp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwymtbi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvxyqxp.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oowprbfj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvfpdyx.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ratpggrd.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmewupm.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvztpnb.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zermrvxa.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rogvucvv.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2odpuskli.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xkycwpgq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2frcsmxqn.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vgecaaci.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2exqjqvqg.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xpaxzxtv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqzsbbz.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2junshosp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qxojmuyv.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2psmacgfx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnygklr.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgndbod.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2feeftsld.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wffwhljv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wawuhdgi.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wosmiouv.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kebavdta.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnjktlp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrbotft.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jccmxlin.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vugjcijp.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ssreyfxl.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkgdfwq.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnjfrer.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2htunrnfl.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ceauxaes.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoxivcr.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pekgzypx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kwflyemb.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ryommpoy.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqltwmhk.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwhoquf.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcwxrxn.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2zaccjtpf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyqbpns.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kolspxqx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zthffeeq.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xozrbysk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfziwjdb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzxvllk.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzscmgem.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2swlforby.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrqiruo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nptehywe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2muteihbm.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2znprwvir.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ipktebhk.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvmlukt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2cshibnvr.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tqljwnpa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2gdiieevt.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zeohfzua.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkrzxyr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxqbtrl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsuqqny.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnmtagi.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tctynsvg.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdswanf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqesnwe.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tscdcwvj.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvhgszn.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjpygac.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpnhbqj.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ariylueg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrydhtc.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cxikomnd.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjpsdxk.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2apnirirp.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpbpwvt.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2uroiadcq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdyzmsy.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2awmrcycn.html


<!-- 参考信息 -->