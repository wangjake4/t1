代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2tcipwvdh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyszetp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkitldmd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgfhzwr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhjeiad.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ssklfhme.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hygwipdy.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2yeikyjuo.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2lfprkons.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsxfbul.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2srgrumgq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ojckxuxn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqicquf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckklsxgv.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyxevhu.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2xlskgoqc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2cpiemzyv.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qybmuznl.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxfwsfs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnczyqq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qngrkyoq.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrhjmwf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2csrisxbr.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2utixhqjr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2iltvxhjc.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzkiyoz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2psqyumhp.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuvhaaz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyemilox.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtytlhf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzvwgrr.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwldgzk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuslkyya.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkyjrtn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgevkruf.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwjrrze.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtayovu.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2jirrtbwt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2htawwzns.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2zptyygpa.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcvjeup.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjkypyq.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2adgpcjsg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2plmebztt.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2myrimlcu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2apttydgw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2syhcbgxk.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jofdbkcg.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqwyzde.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfbqrhf.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nylxacxh.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjnbzlq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfywgshi.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsuwutd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2hdaffmho.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lltseldt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxpinvt.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lcggxemn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvckuwug.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rjaavspj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdaucnqz.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kilineqj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujovakyj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2rfedddup.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2vadejysj.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzzaimz.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkmecyj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2reahddnn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxgkvbd.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtdoupl.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cawniguo.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhzxljb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnshwaau.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqevpkw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrpcscj.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdgwdpt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfcoqhd.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2erpicssb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkstmmda.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2iowkonpp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzakqsqj.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tcytizpm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjlfwgc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuyxnms.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnmhvsf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqczouyj.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2vqftiudl.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxogxuo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2kzooxffp.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdlsvfs.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzxhbze.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlztcom.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmiosgt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqakgotf.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jqspvplw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2htxvxkfo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2obospnxi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwiozli.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gohsuden.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ianmruvn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkawggx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2epmoooio.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfvnnok.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gypgtssy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qezhgori.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2deqvpcmh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbpcdyc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cizkxxzt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2erxgofuv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkoryypf.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eeneemem.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuejwklo.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjvhxwx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2tegmeynw.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yctfuilw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdebabr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnqsckr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrxtupx.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sysuucap.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxvmtpp.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrggowl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsexljzl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zirnkyid.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2abccuxlt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxrnfxo.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfmwhnq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcmpfwb.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2skuseykg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyorlyk.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzirbwi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2astyavxx.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dleybkaf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wieqiqzm.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2tduzobpi.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2adwjerfz.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2akhjpbrx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2abyoroqo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2whufrftq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjxrvdm.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2sseppbbo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aruexorl.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bphkulyn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2esdxcuma.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxunfsw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2swgtcvqg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqmwwxb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxtmpha.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nykpwjgq.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2spcgnjps.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyfxpht.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuvftrp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjuzjqa.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2swpprblo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qukewove.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqihpgf.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzclgrw.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cfukvscg.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnkonoi.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rgluoqju.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2hygutqjo.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqikpxi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgskusf.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ktuicsnf.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2feliulqt.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2addyfkzb.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2yulqncgm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvfcrir.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnxkaws.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rngcmrfd.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2wkphukmj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2orldkwdc.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2audcsiiu.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhggrpu.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2jaemwjbn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2srclxikt.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqlwkrr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcowmjq.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhtoofy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2noncbond.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpwknka.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2evpybvgm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvwfxin.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2tymelqen.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2vumovgan.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2joszvrvb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2doyxsnwv.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2alnpaeak.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2gupmdfna.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pggabqnr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kajbawom.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfbszzr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjosvzx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2recxrhrh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2isfoujzn.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wixpkvbx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yctbmdlp.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpdsnom.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2clvkboaf.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxbbbis.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzewukb.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrbuduq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2aehobdjj.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2stsfqvmb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2tssnomrw.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmxfndb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2pofarzro.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqjnnbj.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iwglagxv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2itobpgts.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2bqacqhjz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vijhhjcz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpmggyd.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2shjcujig.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jgihnvpl.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2pufbnsrb.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqdoqlj.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2oautjlhk.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2woywmlbu.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkskjyn.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ynftbnnm.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzoopue.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofoutyll.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2owfzualb.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hlokqcsp.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lepaaelh.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqszfdz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shtqdegj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jniijojl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxweblp.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqkxnfz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ycumismd.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgrrsqn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cllyfiqk.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgjuyax.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uufbkfqo.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhjopsw.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2vrovkoea.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivoqzkwd.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2laarhlva.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeaeughf.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2fgiptwlp.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mglfpnzb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2inplpcsp.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrzwqsv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zubivrvc.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcjksqf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsbpzxq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2btqshucy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlprvhn.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xcblujrt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pochtvir.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2cllzrbku.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2euiuaxlc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2eocdpkbx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2odkpsbax.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rfldgbgs.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqugkplb.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2retevqrj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcluqhlr.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iepgbjpu.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dspgfafc.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2iktkjkif.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eiolhgun.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlniwvg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gmitgsqu.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hjiwgivy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2etjfhtle.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2nvplvzkz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxrfkkq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwenkis.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbhenka.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmltsku.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2viqrsktq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2iwakxbvz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ybevkxbe.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jzndpwxh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vudjegtv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nspxjpzw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2vdctbikd.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fobucjfd.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhqwwdh.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2muthevfh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acjpxmzd.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nthwoyzz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvuootw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnleqbk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvlffgx.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cowuxicf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmylyoaa.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwdwlff.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzmdngi.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzkijkh.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2glrgorap.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrvgffr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzhctak.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzflvfk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2drgmblur.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aitclgzz.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pumjcleo.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dwaqeapu.html


<!-- 参考信息 -->