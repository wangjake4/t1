代发 wailian999

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ddllfaju.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xboapjuh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrvtwdn.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2brrtesii.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmsnbcu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsulvkt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2sfonxbfi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgepokd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xajmgthg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2niemggxw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhjasbu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2nsggvfsv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjyutdi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqwrihz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cinkmgmr.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2wdiisbdd.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2qctavhjw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbvnadk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjkzlwj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqpyhxu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2nffqwkbj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjzicuo.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbewhac.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2okizcvje.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ospsfkot.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jyshbfdy.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqukbov.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjenzmn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2nehekzyy.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2wrefttyy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwauwqg.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkpqjzr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvynstdu.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxcxemt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yskcrnzh.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfurxln.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2khpvspox.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2auoxqbtb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjjdpny.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2htnwksml.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzekgux.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2flhrnewn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qklwfznk.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdjrrfj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvybgod.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2yeknbaib.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzoptfm.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbmlske.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2irprersq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzxhgay.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2yeysmwls.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wflzfdto.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjlhwim.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2zndzmyrj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2frtoxhke.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnazmum.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfiroeeq.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cnohumwr.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2girlytfq.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcurura.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pakagero.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hggyrjww.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2uueqfxpd.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcahxxx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgcloaz.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2eutfxxtl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpgkohp.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2etodolya.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2peatnkvf.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mycqkxna.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkfxzxh.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrfnpdc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsldyfte.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fsodwjpu.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqgnyer.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cskesbul.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2gpusjnhz.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mlonjrja.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfgnzsk.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2agzftgoq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnoufrey.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cjapeonc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sommchrg.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vcauftos.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwodrpnl.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2prgestmu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqhofrn.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsurqjs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2okcsffrr.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhstsvo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdyiatj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2gnosvtqg.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfklyvm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2gybqiifr.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfcjfet.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2naziaotk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2sjluaubj.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofslupcn.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ectjelat.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vawvldxs.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjztlky.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzemyfzy.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2txvaiwxw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcwvbsf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfoccfd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlvwdzg.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mewrjarw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzbvgpe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2asagmums.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2gysubptt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjptowjm.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxkskxp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyrhoyy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2swfdpqer.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxirnthx.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuofrum.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhwrpnt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxlwmdg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfuuhnh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2izrgmlsw.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvkgszf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2oujoggxm.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsgtbvs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjaxpmd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2thlkaemd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxpcxzb.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2artrqkzx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyujyxss.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnuerfa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2wywxqccz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryynzayp.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyeixoa.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2abgmwyew.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnfixtp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ltuoztjz.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwxmqcc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbagrth.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwfuoyo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wareigxh.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtonusd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhhclgr.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqdmjve.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfgsdvy.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdveqksn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxaexxjw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2esscneie.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tskneodi.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsdbcti.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyveyhoh.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kofslseh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbluxgx.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmmhbgt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlaatgq.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtyvuva.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2elatypbw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnjtptd.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2htlrfmpi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kseisheu.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2keoxihof.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsveuken.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvupena.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtdtuod.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2efakovof.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdqukze.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmloehk.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugilavlz.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gouinlnj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnkwulu.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsjjyhj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwwkqsg.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmtynku.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgypyjt.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qunyiyrb.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmovykz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2nisszgus.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2idgmiyym.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzcpsni.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmcaayz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2gufmidxu.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxbccjs.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvpksya.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqurazu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzodtpz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvhwviz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2axlnxrrp.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbyrmen.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oispchng.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2baekjhzm.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvltvbn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgovwymm.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ezurcrak.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2uavxnxgh.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2elmmplmt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtseisg.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2loxffjej.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2thufnjrk.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2azuuthkf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocipxiul.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bowocrdu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2covooexs.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpapnyo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnssqvqk.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zltbqjlm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrydqcw.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2jfarxkiw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gimabuvc.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2utpcrsis.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbaahiv.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsnpftz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlyvsok.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zjiazeru.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdxqecw.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2eehrwwnu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2lsipxhhu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwiewouv.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxnutxx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfamgjj.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2oisizwoo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzuskufy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqxpcuo.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2acflgyug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfqpfho.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ljooaxaf.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxowjgq.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2enwciuan.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2abpedtci.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdfxpdl.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jbaefsel.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgcfbla.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2omhzcpjg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgtygmy.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hoseyuoa.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgbbagi.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nomedtrt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycntwdmh.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbtifnh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnekyvf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lggcdvte.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zampufka.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgdjbis.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gibxiqjb.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2chsruvyh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sobisozv.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgfywjg.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2opgqeuqp.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnzkwub.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tevdnhbf.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2szactjrk.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2rvckqbwe.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2frjojrwj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hphopkgk.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhzfred.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vweuflpx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2dibrmfgq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxdadms.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzwcpsd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwiepbg.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iapolqoq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2khkujhfm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2holoeuwj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuxpelk.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ljupoawf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxmpqxy.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sifjkxwx.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2klcoljvj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkicvil.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvitdttz.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2loornoyt.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wyywuwrv.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbfeyjc.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2blvfphqa.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfhyded.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qsshgips.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnmbovj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcbdnwp.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2oysmsvkg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmvpvvz.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mevrxcwv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwlrctr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wuigakbk.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgjmgxh.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsoenfj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzyvpvw.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwlkawm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2frfjmsyd.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2trprgrix.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2satuprds.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbrvwuo.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qirifyfh.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2slbhbvsl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpndjgo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnbpuqj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgqjwmt.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnvtgwp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rpukzzjl.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuylbpk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzqceda.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrawjsv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2fwleebyu.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2updtrtam.html


<!-- 参考信息 -->