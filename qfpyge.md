代发 wailian999

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwujfckp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfupgpu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2eapbbyrq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2leubadcb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhcxpwx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgfwsmq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfsytje.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbrnvmp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2htspsxkj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2nvajhmyc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dphhwxoj.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2cxumayme.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdxrizx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzbzgoi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ntslqxyy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvmfkhn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzxztdw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2yavrsitv.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2qadlarnh.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuxyswz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vlycculm.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2nbueseho.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvmssrb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2knknstxs.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlmowam.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ibaqgcal.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hitcnxaj.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pribcujq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhtdqfq.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2vnducdps.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxplmwvd.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2umactgkq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyopdchr.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2tchzbdoh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iosujcwd.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbglqzh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qealqqcx.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xwenlipn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdepssu.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2psxjcnhr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ewidcqfn.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2lbixtkui.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqoogfg.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnvceit.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2dizjifhw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2oevjrflc.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2swtqbkjl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkttxyj.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwqtmkc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdgcsrs.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjryzydj.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfnufxn.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmejcqpf.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2navdmfzh.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcpnlbc.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2voyagczq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgutukj.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tfatkbvv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2jtirqhli.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdabrih.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwitztcv.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ejntekvp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2andfwwga.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbzsdhj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbubavtc.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvggcvw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2azynnhfk.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2oinbknbp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2pstffdkn.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2iahzikpe.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvfzjqh.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgcnoae.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxbrmgq.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxxhofj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdwmepq.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ztemwwck.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aglewupu.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvynutq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjsbsfa.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxjhhue.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsdkcem.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcloegj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmakyjgn.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2iflnzmha.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfrijfk.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2amolgbgl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2obavptcn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2juqcishi.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2suclvrue.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtotqeiv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvtbqfh.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvgrvtn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyjhvtq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2akzsliqr.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnulvqw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaltake.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2acbltlzz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxgrfpp.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmdbeqj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2segyzluw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2oovnvezb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zczidsao.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpgfdhm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2mjapaicu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhwehrc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkdekyh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxenggt.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvrcfcx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzbegpe.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgvgdge.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgyxtxm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2quvhoyax.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfqdhhg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsjspmj.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qktjbkag.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2bimlyryw.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cklbjcon.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqswvjjy.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lksjzimy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhqoyjc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mahxwmgy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbeuadkq.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlrjvuv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnxshae.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2itnijjqn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjugcay.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2aidwbkdl.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qpctjvok.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwefbbwz.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2oprnmdix.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2sbaqrxtg.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bdepbriz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2agdzfqqk.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfipxrw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2etfzjfoi.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2frnwjuxo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cxexryeg.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2njjykufu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2acojylav.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2oznpypku.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2byqzcgnh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2znwamxap.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2macmaiwu.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmjnpdf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aovciqnf.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2suqvrbwb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhpdgxx.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ebytzlkk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnguqiy.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2sffvaivo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2mcitzgeg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nczmgflt.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mhakaarl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pswllkmn.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2kqacrwbc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpswvfl.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnekyjc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsnejqq.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2srjswjxn.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhauqbyc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjtpich.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrvliea.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2riritpvo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlyirum.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtsrexs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2srvmikji.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2jetpuuvn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqishrxq.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbzhmvw.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rfciqylo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkuzixj.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2brdhwnoe.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubagejyb.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhfjjvk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqasxtj.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ounruabj.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vohzspvi.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2zfavbqhv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dfndkwjq.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqszusl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2lflpuqgj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vlznxvsw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2udjvmsst.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2vyovwptq.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ooojymty.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjzsynl.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2khyohntc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfuhddk.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gseyaoek.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2pukzcyzf.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ygaadabm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2pxiysmip.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfrsezl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjirnkc.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jaiuwwfr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxkcbeo.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvhdbfh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntoonbwo.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ziytrhqi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kutkqjtz.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2oxoblbbz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksaksnlu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrlyleg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuiuokl.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqmfzxe.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvrwwex.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2smtejmhi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvutwsh.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjoxfazd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2jkaofebb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxffsemg.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vhiunbkr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mjorzkxy.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2gsczdpwq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnvbdvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqwissi.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxxnifc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ablzcqio.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2oyklulxc.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2odipubcd.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zflnxqhe.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2znijomcl.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptydgxdi.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kesmiyyj.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqttrrx.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqmlmgx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzrsrwy.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2aedqanyl.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2txchfiqq.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fhuprnmx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pogtgsuk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdovdgkz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmhatfl.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2feiuscma.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmsvvgr.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xezicnpf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jymqrjhw.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkxlsen.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhjalxm.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lcswgdes.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvtssii.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xaevkcpu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2upthrosz.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2eydofyxo.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2unedgbvq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uisuzruw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mblysnsf.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpqkued.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhdwppn.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2zerlqevc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpwdjwr.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lphgppae.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqeezjb.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbjsniw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhnlvag.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgsyorj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgrcolc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2apiruuur.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2syrujtbf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hybgirzj.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mewrtgsz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2efucnvoc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlneazoo.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcstqyy.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tavuvyos.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fejelckz.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjufetlf.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gvafxocq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wejisupc.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wauygthh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxapvomz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtphwnh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jggbmfac.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2akozvcho.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2awxyveha.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xfahslhj.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2oezwevfw.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhcjgvl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwrnpwq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eutwwfrb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kaonjgyf.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtiidhk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjddxfz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsixuyv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnymgge.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwuiuxd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdpzkvi.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2opttwbyo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkwrqxp.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2rqaekcoh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uskbaiju.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqaqkkq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2raaralku.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvgpquc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ojajmdxi.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uojzsylp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhrkblk.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2gerliuxw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2coctivny.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqgwbes.html


<!-- 参考信息 -->