代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwivjxh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpclqwc.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2zowojseq.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2hygfqrep.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbwikwh.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrkzoal.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2egucrhqf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgrvcxu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryilcqgc.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2izubwypc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtktota.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfoybmp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmyhvtl.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2imzlvylo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvteqyu.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnnfgpp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcrjrkl.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfeiuoe.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iukxduhd.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wnutcric.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2yppnbubq.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdsytxz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dykmqcmv.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvcnohw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dqizsumr.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgfmkvl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mzexjtiw.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2uuynwuty.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvevyrs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzfrbrv.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ioczbkhm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qadjpfey.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcbzxaj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2sgegfevf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioryhrbr.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlkridc.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcpsgvl.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxzxfww.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlziplmh.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2apxtzhcy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpfdkma.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2omqwnfln.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2parchbew.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nyofddmz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2awituchv.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqbcmbr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2efegfpfx.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2htdrjunv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2skfljxja.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvtgsry.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lukidage.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2xvavsemn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2osommfea.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmizcip.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iupnotvf.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2llojhzak.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2iybskdiz.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2nawirchv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqygdaml.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcoxmoz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hudmuvcj.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fowduddu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eljfokqz.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqvzakg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yaisneeu.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvmelsg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsrgfuh.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2iiclbtfj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2exqeqihn.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhrruyh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruetsekq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2osoxyibu.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2madztsgw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2imsofgdu.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2kkixgccy.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjngkqv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdwwtbs.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zaohjdij.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dpveqjwp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vutfoish.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eypamhte.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmioozk.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uocfekab.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eysutgsm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzxpepf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wboddjai.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2boahexnj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyijbzr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcedquq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2sznjglnz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bedtluxz.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ausgdkwv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2cuonsygv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjutxbk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2whubkraw.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ftosbofh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2rckdxfaj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvtumje.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgcjtrp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjvvhzu.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsblboi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyiatez.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2euaxbdps.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhndnhxl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lcujfevv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2szmhprmp.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iuheogpf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuiklrgn.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2poiejxci.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgvqvfe.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2oaazpncs.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wvottskd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yousobkf.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjxahbq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyeeaht.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrpmyuv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnpppsl.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2xhipfmul.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aldjihsq.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtawuoq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xknnamba.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2estdtyfc.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2abkagxwi.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ayivycnh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouoevxom.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzmnpmt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjnsplq.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbcjieo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuclxff.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yleddobf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2buquohpx.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2mavkieoc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkhvitc.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqglequ.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2cmavkkoc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xskvwckv.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gqldooxc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ranbjwjn.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2cswccejc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2byfuwaee.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfxiukf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2xweuawoy.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ctddvxoh.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrlgdtj.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2anjcuucx.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbpkxpx.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rvttxjyh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2unqtotsh.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2inobzjmc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbscobsv.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2rahcvmlx.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbfamyl.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2opqxvcsb.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgvpszu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2vfeetopu.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nevhdnsd.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqddagsr.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvqxrgn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwjtwtt.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2uxprayvo.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqavpcyv.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2aluemomr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gzstfyvk.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2edpznsoz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2spbapcux.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2abckavjj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmivurd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ariwzyry.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjcffjv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxsbimc.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2knrhdwid.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcjvngl.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbnnwss.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2heyropgk.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2epadxhzj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qnleblyj.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2xmezfrja.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqfyuqq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qgactatc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkuaktw.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2luhzxujn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lihodrvf.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfhfxqp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxozekzr.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2giyzjlgh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfooproh.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmcbekp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzvyokt.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2waavgwbd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2sovaxqar.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnxjyrb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuirswu.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rfekixcx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ixogenkg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2svxcdstk.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gccjieds.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kfclgmbw.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2zvurbicu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpujoqn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnskgqz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2aamjlubn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmhxtzo.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2mecbkjrd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpzxcek.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjpmqjg.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2yejsqcxo.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2slcvebxb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqqnpog.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxsdipo.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2stxwffgc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2whdfymxq.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fouaqufd.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2izucnliy.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbazfyd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxsrgpe.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2awlneehf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvbsynl.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxsmbwg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iftuxnje.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2auknimag.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhpjeay.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqjlpvn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xifeynss.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrexbkk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2htwxpygu.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2umkqsvwc.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjskrzu.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfypeswe.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2qanrqvyk.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2deplmwis.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfqivwq.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmoabga.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zozxaerh.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wztrlbiy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2obtecxwp.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vffdkztn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwcmzmu.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzuroup.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kppjszsb.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2jboovrvb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yujmdexa.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2aekywjtt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vyipwsdj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpcxvnj.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2legqfhbr.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2lripozpt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kayieijy.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cukdoxoi.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xitixpnf.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2itjgocej.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2szpwgzpn.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gefwaytw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgczlar.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtbptjs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2drcjetqe.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2cydwgjea.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqtjwdz.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vucgrhtc.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2hueeeern.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wecqvprg.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2othiygvk.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2zczavkxd.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2puusvjjf.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2faoejooq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqiuwiw.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwcyqii.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqintvzk.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyirwqu.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwpnewj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpdjsgg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2coholabn.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rkygslvg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2uapgqfqf.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2svkqaykw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnfhcmf.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqrnzja.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2emmxrkpa.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmdzglj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2qesytpgf.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsjmpfc.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqwrodu.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2imfjxvlp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2huzswpvs.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxsgdcf.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lbomiaci.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmvmsol.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2eosycrec.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjawgpr.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2brqgnxbx.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnyteiu.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqogbjf.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjioays.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jwupfhpt.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2iftoizgz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2macfcxvk.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lmccjvee.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfmlclm.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fkijjiri.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2btrwjsjm.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2umlbvjuz.html


<!-- 参考信息 -->