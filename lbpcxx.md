代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmjkviu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsezcjw.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2htqtadnw.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfsvflj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqoxpdw.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2icejlfzf.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2lajxahdv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2axkrbynn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2aowjcrzi.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2tputsiol.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bajtjagz.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tdocgqbb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2evnetrxh.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrefrfp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfyfuit.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2oejmijlb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyoejdnb.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ziuogtbw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfseont.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrhyluw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2axxhlowz.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpaglxb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jehjrstx.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2znpebinh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2yltzedaf.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdozyru.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gebtjqfx.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqhirat.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcwrirk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjkbstd.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2yczjczbb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuarnfq.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzvalwn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2cukrctsl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdhajus.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpeltjo.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwklfqps.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nxszljrm.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkrynfp.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wucjiveb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2irtcbnpo.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mkghevfl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2jajmtaps.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcuxgky.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2kujajczo.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsskdum.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eonzamen.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2znmkmdqa.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbvsgiz.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfrjzhz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkocwcll.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmtkfok.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpxlqfh.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2eeaypyja.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyivglq.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fggqqohp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpjprsx.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkuezoi.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vprytniv.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2nymgrwhh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsnvujp.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2byamfobd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vznrmizj.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmzugdo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkbfivx.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pllfthtm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmrgegt.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvxhauz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfeejji.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmunrdx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgffiynq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2igkrgiqx.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nkirobzy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2akqeanhz.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxneubg.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2evjcdfot.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqtbxkx.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvagzyv.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cetatquw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfxlyqm.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dynedrns.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkllveut.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjgiuba.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzsgahk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbnosmi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhhzfjw.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2twzhucbb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2weditysh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2allnuqvn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmswebh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2esknbuco.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyleudi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2toxncwhd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsktgdf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxyleik.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2blfqocdd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2gauofloy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrevpcs.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2loiycndp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqeuzhmv.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ywauquae.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzrekyf.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjshygs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2plwzodyd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2anrbuzdh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhepkvh.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nktwewbv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfjvtmp.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2llwnmqgy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2uubmilud.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rektlfzf.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjjmzsy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2szhplnpw.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2eomrnwlt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkwfalr.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mgblacut.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqddcgb.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2agmbiizm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uanuqrin.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qaurekhx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mzegjqgp.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2yakilmqz.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ammtcvtl.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qagcdjxd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuvdthb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbkbcgr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfuvjov.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2smwrvttn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhsrnbr.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqbwlue.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2utmiheow.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2kutmztcx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2piavjgif.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2girnykva.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2xikgjexg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmwbsfy.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2sklnzwle.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkexwbs.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2emqpbhmg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdikstis.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bnafwhqg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlwmpbs.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2axmyffur.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsevyiqc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bqladhjo.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwdhhlx.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uirdjgol.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfsgrin.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2piqtbgkn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnddpwy.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqavmcs.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcecfmf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwglfuy.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2alllzuqe.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbmfnjx.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrqhzbv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iczgkovz.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbngwyc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxhuoml.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vymppcpp.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkmsjsz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2garkstvq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pawpvaum.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2amfihpfm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcoxanm.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdeomij.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrhrcrt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwkqgop.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2eyotjrix.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2omprdygk.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2cltvbfco.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2rpksgjqf.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhvcmiy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqmguoi.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tugcrszt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxszndb.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2utxoxnjx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zssuoxlr.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2omifdloj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkujpjg.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vypxdkfe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2koofnubk.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bzceseit.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2twyphxji.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2gctqlkpy.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mksvkeqj.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpmztvu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhaobnl.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yotebbnv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qgspiiul.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wgisbktx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2npqfhooe.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkuuhryf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2alhqnexj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcftjpot.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrlymeh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxcgkaw.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgnqaqk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrckxhii.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2swvfnosn.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nggvgvgu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ltatvxsw.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2yebtaups.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkbqckd.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmtxfgo.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2rbeukvuc.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lervkltu.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2myjypohe.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxexlmo.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2knjaqzps.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdtrwhi.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrzsdug.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbstgwxa.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpekogp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcjxjxk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vplfoacx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqauvee.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrgmegr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gksetihf.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aartmwpe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2khrmskbm.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdvztsx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjqiyey.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqqggke.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwuvrpe.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxmluuu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqreinpt.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2biixpwtq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsehmjw.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oenhutvb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yeburxvj.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvafmnv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xdobkytk.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2euahbqjh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2olyvjibn.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2snswytrr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2arlzyjtf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kamaxqjf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tryuywfz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2nldoikvp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbrfwgl.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmvubyr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwmfsun.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuwjpot.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2beyurxou.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vswszzas.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2avobqpdn.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gklehbse.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eewpjraq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2pylxcbpo.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jerteqfs.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fwromfed.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2engtrknm.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyoeakn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvdshyk.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pevbrepq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdzbeqg.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dznrybsu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2txtfujei.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2dxoseiby.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dixxmbex.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnacqfv.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtufgpp.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtqfqgh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzvaonf.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dctxybyn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvcfzvw.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjkwznk.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gukijuwr.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kaopytuc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxlnlwy.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ussvjhxz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcrqola.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2sadwebda.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pqiokobd.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kranlova.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxlpofv.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdqofsg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2qjszovce.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dxggzytl.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2srcabcnx.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjhzlgp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gtydbjee.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwdlyjs.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2myqafhwf.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhmmlyh.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrhftxp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2clywkiwt.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkozrbi.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvujfzw.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwaaqrd.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfyfgzsx.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qndfidgn.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fckvuidf.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrwviis.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpgmpyg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxyduuh.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtkkuwn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfppktv.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zsziaafu.html


<!-- 参考信息 -->