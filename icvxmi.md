代发 wailian999

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gstwbeur.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktucfzut.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpsedte.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2taocoocl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhaysud.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuxyosd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2qicwnund.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2wenlxsot.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fiprxgxp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2pssnrttb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrngjqp.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqgzykm.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvirvmc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tkaeumbv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fiauwcta.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuhftnj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2krgfelep.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2uaupmawv.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxmwpjj.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrhozyh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2yghwdovr.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mupntwcm.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwhjlfr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffivebwt.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2iujhgrjt.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2cruldlgp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hunzdykm.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsvhksv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmeiqbz.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzhshdu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmgpjfy.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2femrlfkg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2utpqljno.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2dzccverr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oduvpmhm.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2stpaecvm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjseuly.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vaihjftk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxplhjh.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vammednj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gsppzlbt.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdddwea.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwexdbd.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2vdaoasua.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvxaigk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlaozlq.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2gypmujea.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2aykcctml.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzeasfr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2malktrra.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnyzmue.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2idynmewe.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhdihvy.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mozholun.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkibqqma.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2amuwgnqc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyrfxjj.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2omunfnvx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2eudawehs.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhqexnk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqndivy.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhegypm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2axdmqojc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwumljb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmswdeh.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcsuzqk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpvxfap.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2qacmezvt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2xehtpwvq.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzeaomr.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgnwlcu.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbmwukb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmjflgg.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2aicqlmho.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2secgcjro.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2alcqnnes.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jouvrhub.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxjrarq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkuptaiy.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvuwpvd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2usdfsrhs.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2oifuzekq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zshhkpej.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdflfps.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlrgthr.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2innzwbti.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhylhcbu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2nskffqrg.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bgftexsy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2waytrteh.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2onprsfzz.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2pgigvapl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmxemgf.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eushchbu.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhchykg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjztjam.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qggreqwy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxhfqmb.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ahayyhzy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2srwkrmjl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfapwbsm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2feyecrvo.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dowwjqid.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2stylhquy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnkbgae.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwdgyby.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2injhfddk.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ftprlxak.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ithohrmz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xprbpstj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtsfaos.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sveyxmvl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2qcozszmk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjtushd.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kffxuowf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2zixykmrq.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vuijecyp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2enidysdu.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wlplzzpi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwqjdfs.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2blmusukg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2eavgzusz.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yexjvezj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmqwwgs.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuwuphf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhwugdo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvomgghe.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwgfxzi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxelfszm.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xejhhxhk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkdcvwi.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uiovopcb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdnacfw.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhmebcw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfacfdda.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfkvsao.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2izmxqiui.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2qrscfzdc.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2frcrnkjl.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlozagi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2aypkxlna.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zawbzavn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqtuozv.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tuczltqm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gugiedsy.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2enpwpxpg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxwryfz.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwconim.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbcnijc.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pdatakkn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgedrao.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2szehlpfe.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lwituaup.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnjnnlf.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2grpxxvss.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfftowrn.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsmfnyt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qmydotwn.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkbdqzj.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2liqudxul.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2phbhyvwj.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmtdyqo.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pegijrju.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2votykgvr.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmryztz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2husmmsvw.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2deyjwlbn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzlusiq.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjwyhge.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvuvypf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2omlfxsug.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tellxgln.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2znvajppt.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmjekdu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvuzkuy.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2exzlznaw.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgxhjcy.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2nokblanl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhkdphl.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2syqwmwon.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2utekafmt.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqeyhpc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2isqmusis.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhsnpbc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zhubgkqo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyutwmua.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2buwdrjhm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2emyfublf.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bzawudlr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2zajjivtc.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2myimejeo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmqkzxf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2uveyhoob.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvraelbn.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mdykahms.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfeadfp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsdoanu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpxlpew.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxtrhtn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkbsptz.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2clfumqvn.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2awpgikrn.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2tewafkqe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzumtgw.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqfnlca.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2kauhyyqr.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vorsaegd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2fewauqzg.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkssuad.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdtedeb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwqgfwg.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuqqspq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2syyndbrc.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2oienqbhe.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsiwzini.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwqizjj.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2utrjxfzj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzkteyc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwmbwoy.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmvtasd.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2hypsxils.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuaypir.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgyeguw.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2thizgnif.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjjgkyw.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2issnlmpj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmffopa.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wglqfusd.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxjfcgs.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsfjpry.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjtoqxf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yeaynfrv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2somghogt.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrenfen.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpddvpg.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fosdmloj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyyibkm.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wajsctxj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlhyvou.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2namljwui.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2nezmymyv.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyuxznve.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wylljuwu.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pahmvbnk.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xxowruvq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aptawwwz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbqxjjz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dzncuqis.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2btwgiswi.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwjjmll.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpkyhlc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsklhbo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bbiuvwgk.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmgmmmv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhhstta.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhkjkaq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fclhzlvp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2luqgzwqr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpmrkyo.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eehmhitb.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tomedqeh.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2osldzunn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rwromrtr.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qrofqlhl.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nruucjbg.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2pugyixci.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkfiyyx.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqyuqij.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmbzsvy.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2drubighr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjjvgdp.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtxzdgr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nsayubjx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwqwfln.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2gplgobbn.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wklfnvcm.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vknpetpx.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbwtwax.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2prqsuyir.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgeveem.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzvcdns.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pspsotnm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgrantm.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aamgthim.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uobqlhav.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtgmfpf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqksrhp.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kfatgtgq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbgbfjd.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsccykj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtxuhin.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2llouakah.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2iccmejgx.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mephxzlh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzsfntr.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrxpuex.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkxzduw.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2muadregj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2aksfbeqp.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qikfeuje.html


<!-- 参考信息 -->