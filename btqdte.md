代发 wailian999

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2pehxnsfe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyabpjv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyyzlus.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2rezvsfny.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2faxrshcj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrwbaey.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkbqezz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkgpqof.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2okutpxwj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2fcraemvc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhfjexa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2siurvbtc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fkprmfpx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjasevfn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2admxzqup.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhzcbyc.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2umwgpmfv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vkenjydq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tvccklbo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2iajvljay.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfwmsns.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2djahgnch.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2pzeqvdqw.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2waaxtdnr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuuzhnj.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qecnspse.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvmsrfb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcaztaek.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgjsgfv.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2kedopvgl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlttmflu.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vpywixvd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bacfjucv.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2hnafmtge.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmbsejd.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2rouzattl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2xruggmqa.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbqklch.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2irvjqjrs.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhnkkyl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqptgcg.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbvjfwg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkgbcrs.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tsonasxf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2miclsncn.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwswhzm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2radliwfz.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2snymmqdz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vmubkrfi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxxdyao.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwdjkyq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bieptsje.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnbirju.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxmcdlk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ackrptgq.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nudygcku.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgcuztu.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wfihlerw.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwugirbd.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2doqdbtkk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpluviqb.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rofzjsdi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2exzrdshd.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuczexd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzbelel.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjvizus.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2svrkmsla.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wxclnnjo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtllznzy.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rolpntbg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2gopfadtz.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvsoigy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtoxtly.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyncazb.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zavuinyy.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2irykvqvp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2woldvkaw.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fapandfx.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsxisps.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2avwzwdwf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oowhetkg.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2axngdget.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2epoocfkg.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvjhsuv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnwwriu.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2limrbxwq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxbfczb.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmngyre.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfgbtrm.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvnafjj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkujiqc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2fcylituc.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxzbamy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqhicqh.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2fxaiogef.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtrdiae.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ceruhuqc.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyglkphl.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iaebjgux.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vendwdvl.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xfucqlfo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdwbjkt.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyqumby.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrwptcy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2spxtvife.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2znixtyql.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tytevnpr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdwxsrv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjntgmb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2kscnmpvd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhxdjte.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2izpbhqph.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvnbkuu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2kwljtrwc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kytjepux.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpqyawo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxxnjjo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfxxbxb.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2umynybwm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ditgnuwf.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wymdzrrj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zruajvya.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2exswbzwi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjjxbzf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqdqjgp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjypjdq.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cphirmrr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwqoczh.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xywegsdx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfanprkn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtmctkh.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kilfqrlw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tglchtxa.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fciiyhnq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2estuyhpw.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cyoufgnb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2riuxhjey.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2otphaomw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsnpgcn.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mniwtdis.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdmxble.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2eqeegpad.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgdsuwe.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhywkoz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgzewwa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2scbwoxfa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2acwmvktx.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2norvwqxs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdghcyak.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2idgtdhme.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiykzumz.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwzotey.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2avfmqhxw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rosjccoy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2fazqyicl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mketmsrr.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jfupzkxz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2axgqteot.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ximmwvnt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvqdxic.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbhcobn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2mfortjsh.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vamkxarp.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcaghgl.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lxntxsjc.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhcvbpz.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wzavhwhj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2klypqxrq.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxevyfb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2udstikfz.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2grlthdbi.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmhvqkq.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aozktbms.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2lhigtptt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnoodng.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbomcdm.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qflcvbhp.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2gipiufce.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ziluoqon.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2crgbpohw.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkxmspb.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyabldl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fifyjryo.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2audqsrhg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2klucrnsr.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2krbpqhrx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqowvcru.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2gggthrgw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kebbwawm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2itbjorod.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxqkkkx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvepubw.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvgiceu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ozohbupv.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmplytf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ooihlsjq.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2phvypkgs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fovgtkta.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfdsrys.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbecvko.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2atumzqzm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mirkwgxs.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ebttvcmi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxgcudk.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyjwyzx.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwqvmwm.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwolrgh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxkeuid.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gcitrcls.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmlmoaf.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oxufxdgk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbzaqwe.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2deyxxbgr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2knturqxr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nodmcscg.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnljvgo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsvefxz.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2otzsmxwa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwuxrta.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wfujqhap.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbgbqbf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhvxqbu.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoyhczw.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2logtuxqx.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqxbvmh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2svxdusmc.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjrligi.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwnnvxp.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfzyrwq.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2prpanqka.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2umplrusg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2umkcddgx.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2clklabkx.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ehiazvdv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kprebgoz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzwgrpv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhhjuqa.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hijbvlwg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2olgpgaui.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2btqdvjla.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gzroyesq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtgrlnn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmujaul.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gstuszkd.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgpsimt.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkbzucx.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxiagdmj.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xizmdidg.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxcmbis.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqlwvmk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxpjgvt.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rewttdpt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvfhbgo.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2lvendqro.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkkkmjh.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrnnekj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyydthd.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hubxqvzc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyigxgh.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzyjsfh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwaqmee.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqcqqxn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwtmnbj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eotlxfhe.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvmuxto.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdxxfjn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ymghukzv.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ahaugodo.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tongtdin.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfhjrui.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuekmvi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsbgowh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bapxhmvm.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2djwnualt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2umjilfat.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vtujsjnu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgixbkm.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzotryg.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsciirc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfnccly.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvzgaif.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcqslif.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrmhcrs.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpfyero.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dttgxaar.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmhgwrm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnexiydy.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hwczvqor.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtdhkkp.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzonhuk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svntdnuc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bxssnjok.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhcniij.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtfngok.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bxeliuhm.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjeyfdn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2hizyipui.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyfitiu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkydrqw.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dsogtbxv.html


<!-- 参考信息 -->