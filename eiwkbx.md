代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2socuqfap.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnpwqnv.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ognehreq.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2hayeusii.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ektbkzxy.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vywaclph.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2bqigqmhh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2epnysmvh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2yokndzhh.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2qcixbgwu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhsnzae.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qnipslxt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2oddlnrju.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvwnfkc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tguetsyr.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2smnyufsi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2acyltvqu.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2oderwpad.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2spugbvcw.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbultyl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvwkffv.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyjxail.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqedckxp.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2iresawxa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zivgizla.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvcozqb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tajwjvkt.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxnamlb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrzllgi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbiprme.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2crnhhmvk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsgxloe.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2cngsifmi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2jaevfyaq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlfvlzd.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnkopsf.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2texkoebj.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2trrwndma.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfajkped.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aezvvedf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpscdss.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vpymathp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2hlokveki.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmkmrod.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfkpkmi.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrruehw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nznbqkty.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjsyzyk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnyjkck.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qoesnofq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjrqswv.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsuygcg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahoypkrp.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2flezrwyx.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2asmnljub.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnhxwqp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxbgjku.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdceainu.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ashgddxl.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtxkzov.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzfbkxa.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrzezxb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtjwtrs.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2feirhhji.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrotsin.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2upmdbopl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sykwnnhs.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mxittxlj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ielvmtol.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuekhld.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqndcizj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2stgrhllg.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nskskkjc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlefhkxh.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvgrfvt.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2tfiibull.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2rxccbblm.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcsjoeup.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfxgnfm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgdtxgh.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2enmejatc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2maczhjtt.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2grisgwrd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmiftdoo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2bytfaues.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbkqdwt.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxkddbx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2spyiszod.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2czdlyqxt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlaehrq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2fterkslm.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aehejyus.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2pujrraum.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2acmbtnla.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtsrbyu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2efkswdqb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgqvlji.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucymkfwm.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrhwiyi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpasxet.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkelpfh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmlzyeu.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2stklplmz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2uohhwbxp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfdkhbk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbjqjul.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhocrlb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2opldgapq.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqgwbsk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgabgwle.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzwejkk.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdrcids.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qopqcena.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ymaavgvo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mcczlppf.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnijgdd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzigzjsh.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2unkhqkvg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2eontddvp.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2oznkzsqh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hfeykbjx.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2viflfaiz.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqptorpo.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxoomni.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrhvrbp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xadoggqg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zncjontk.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjujoak.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yutlcfqq.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yloifuwg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhikdybr.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhaxmvf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpkozte.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbgimbn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjwtltu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2crrdizkt.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bolhgjhw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2guhixcqt.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2aryoxnsa.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvqpcyf.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvdzsjo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvivbxj.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jmaymopl.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmvghwq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcfcjcw.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2kitkwnjk.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqhqrur.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ensiqkuz.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2yjuwqwla.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnmnxvb.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbhhnmc.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhhlcps.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2minezosu.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpjiybq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2byyqquoy.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwqsujv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wstsjjjx.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpqukgy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzsmeha.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yavgwjwc.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqveouk.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2pfuhljjr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwzbykw.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mktsqyst.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2sulnwviu.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ermnenva.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2myctlsms.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2omuumofd.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2clzdiada.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbbfwpa.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2qdasqnva.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hczfynti.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pqiiifoh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2nmleynuz.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvfdfzo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2hammrbic.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2afmlzkmr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpbyvto.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nagmpbvb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlnhuai.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnfovqr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkzkvmz.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ammohvkc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjydfqto.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2pkavfbib.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbouapu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsihglu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2enpwtpvz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmjgsks.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzrfehb.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvkzroc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2dahilbzo.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vknupige.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2tovkudho.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xikilxpl.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gdluhvti.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ecckwsze.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2lvriqxcy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2anecyhgy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lufcmddj.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqkvrri.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fbutkiuh.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2shuylqjk.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbvmldt.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjccyri.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwzengy.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2oeoiweng.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxoggrg.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2cluagiji.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xuufbfdm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzrkspn.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfgoxsx.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcvqatq.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dctibeok.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgeiazf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cuupohng.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2khtnxkqq.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2obxqassj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2opqhcyqk.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2adxsihkj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lgntvpkc.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ezngsqvh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uebjzyvt.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyxgghj.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjtogar.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jicydyic.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2heuomily.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpriupp.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvtrtdt.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2blucxtse.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gaspkcyw.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxdmkhx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzohncu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvrcvxb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqgzskj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oznsjwll.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjcluug.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tddeggqk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnwjccb.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsgvhcb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsupymih.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ipczpouq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rvogscnr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2flffqqpu.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpgsvtz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2obbekkqu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxodghe.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zqztgmnd.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mozvftph.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmjargu.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2btkytemt.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rkeibemk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2codbwwdf.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ozljbezy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2afdkmdxf.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcsdshz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjxbzgb.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wllvyndy.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2szkvvxcz.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvdkysq.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwixius.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqzxhsp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwndpip.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfcpbbj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmqdwhs.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2entgjjgw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2chascykr.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aeegrhow.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsunpkii.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnfzvaj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxmppwg.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbfeemb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrddqxi.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbctuwg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zkiwfcjs.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlfqerl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2clhbbmgd.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dxretddg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ihchlpyp.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcylhjd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejskrdqj.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjmoagj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzhfzae.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nakmtomx.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsvptdx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcuzrdl.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pvievkns.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvwvnbh.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pirbecjh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfnbtky.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqmiiyb.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fdttymyq.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qxroxnem.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bepfmqjo.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwsvkmb.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qaiozmko.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ybaamjjk.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxptusx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2rnidmihf.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tilgmdbe.html


<!-- 参考信息 -->