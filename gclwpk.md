代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dezilccj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtowhax.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnesdod.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgvhhvg.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrplfov.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bvitbzkk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2avqezgai.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2wemktssy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnqzjvu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2okaokgwf.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2xiylphyc.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2tkodzyqp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2yupnugoc.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlgaozt.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrsfhnl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsavgwdc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkvtxnc.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxybnzu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bitalcqq.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jccxziys.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfmtvnz.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2buuuuubq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfsokxa.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2rfagiome.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxikvoz.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2frvgpfod.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxewbvbz.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxxgboc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2rimvtlnd.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbrvbto.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tucqotbg.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfzuwrd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnovkst.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtkkuuz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwnhnfg.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2avlrtosc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2fyavwunm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuaqkal.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2dqeegcut.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2khdablzj.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrxogiv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjihazl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2oananmiw.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tjefsrqp.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qasdbyyc.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zmredrgd.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xomuaiha.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcukids.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxjwcvl.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwxptco.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtpfuor.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsspheq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuiusfn.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwgcgzd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnigzco.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgqxjgn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfaxrnmz.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzeeryc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ympnrofp.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2pnasihrp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfkadom.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfsiyfv.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfpmwhq.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxixncs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtmjwfl.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrvoyrk.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqltvrc.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ebppfkgl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzqhdka.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zivafxuv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxwfxjo.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kvoxqqpj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdibdjqm.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrapheg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqywekq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxiztku.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2noywcxxd.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnwflqp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwoodrda.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhklugg.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpohvel.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2djfgitdr.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2hepqkowm.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2okdtfvru.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2khdbpgfd.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqlgapd.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2axjfhrwf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlifaluo.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2azdzhike.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nunslhar.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2obmjqzak.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlumwgmq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2yypsrgrb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2axjlmxgg.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhaxdval.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2pwahookf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nltmqpdz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcmzkza.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2kajjkxsv.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgvoihx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2miovdnbx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2qlymwgfb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vztajbuh.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ytobgagh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2blthmbwx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkadkgp.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmnagtn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2tovhxcft.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vixrgtrb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2lepsjpiz.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eakoeljv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2oubmujbg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrqxazo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrcziea.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2erpdeizt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrngwvei.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hufrlavm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhakzik.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfwhcej.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2icwepyyg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2haefsqvm.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nmympehk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fygaawdo.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcjrkjc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtydwnt.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsykytl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsraiyq.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqfnapc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jruzpjaa.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkxhiib.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyvvulu.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdovogc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhswbwnh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nupqomxq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jphahbgn.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuucuzt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2soxxqyqu.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ooljnnnr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qphtcdii.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ttudttjh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2utylmuiq.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2btyuefgb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzkidax.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwiyyje.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrckqag.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uizauvvc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2okdpbyrj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2eidajaiu.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pqexvhxl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkaetow.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvhkeqo.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxpoasf.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2npehxmqa.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2utlomhhh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2exmzufyf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2pywligcf.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxmunep.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcjybdy.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdeatgh.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yopxjwsk.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmowdzo.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhigmeb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2sugmxllm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgdcxyq.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvjrbxp.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dflieueu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhijzhw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wybxkiac.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbikgjoj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2aajaosrq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwmrkqg.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2upigpcas.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2odztmiyl.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrpszfn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2miskjlyh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2domthdaz.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cigyptrt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtsvlvj.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2mdammcrc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2erceouma.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqsxkik.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2rvitnped.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqkxzdf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2clynmulk.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2tkulwcvt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcreafh.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oefydpbt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kppbwfzj.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2svvqbgax.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvcxtcb.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cmblxwgq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcncrzmd.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2gzevbucw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulomvwkg.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2wjeaktdt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bphlzdxb.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2inuaoowe.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jptdiabk.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxssqrw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzczribk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2decboosl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqwdnjg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkxnbbs.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wajebsxb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdwjean.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2okpnfkgn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjxjpxk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pfiajnuf.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmvmmqw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoxkfjj.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrsvitz.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfpumra.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2uymgydge.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdeynxj.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckiszdqi.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgosnhf.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpzmhyn.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrlreyi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilycyofe.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2eoikvumu.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vdopedbg.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjbpdju.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jierjbft.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcugxjt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tesljpef.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqlmvcu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hprlioni.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vopnuoeq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ycihlvup.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sbplvhps.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbyrsdc.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2uprrcyvm.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2fwruyfwo.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2spwkzcuw.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxwtrui.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqmbhjt.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ckeqlnlt.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vliogtpq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnhntuc.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqbatym.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvijhvq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2toidweby.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vzafbqpq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmtyted.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xicsfgsj.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgpxspx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcubzeo.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2whnlpzxy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2imfivyap.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fzghdftf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwzafvn.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cguxgfkw.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kigvmdpn.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfrxdym.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgqngwp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bflwegqd.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awcxsxjc.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2unbleobd.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfqsmaa.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyswppl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vaceyauh.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zsswigui.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awxrrjhu.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2kczidxbo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2scrdhvyp.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zolzaekk.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxperfao.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2mszouzer.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvfgdzk.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnmiobe.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2vixojigp.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2girgbmkq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwsffyj.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2odozqtjd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmofofzu.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2utznzsrv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ceorkyay.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bbysabmw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upaogvlv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkavbgk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2vawjdhun.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbarleq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pdewxikm.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmtqdmg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2uphktwsa.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyqhqje.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2onmoqqgs.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvurmon.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hycgqqvr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvfyfia.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgrzbec.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jipfaqmp.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2eegkmwvq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rerfkvgb.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nrakgjfb.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dtopjaud.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2epnxpshy.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2eusupuwt.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzmefif.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnsvmrr.html


<!-- 参考信息 -->