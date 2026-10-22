代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mcojooyl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nssmqrwd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2toyvcxzh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfwbypc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbgjoxy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uklerhtg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkteztv.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpjvqaa.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejehusui.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2amqutotj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgloamz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lirvaryp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdohchf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhckvpy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsyxthd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcywmrm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fstoqefa.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2eokinnfw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzaffdf.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2anuketbj.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfynudg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxenecs.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ritmunwv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcxmdll.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfnkdai.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2csashltr.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2dosabnpc.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2syzzaxya.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrqchzo.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvvdduy.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhlcsaw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuggaprz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucknyyzv.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnkqitl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvbrifd.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdjhidt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrgodjo.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2hdblznoj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2smvlftxf.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdpcbbs.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyanrwel.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2qtltqwgz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yazxifeb.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsikxdu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsqfffk.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxoixrd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2inyssqgu.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2npmwufgu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpknvgd.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhebcjw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zwulukvo.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqywkzn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2dlckpshj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xynjycal.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2nerbbhjt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mglfnvmx.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyqycbs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrvuqrm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmvnznx.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2exhxeorl.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvquuslp.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2iamrgciq.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yojnnvdl.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyzopqk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzlzmhg.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvygqmm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxwtqtt.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2apkhkzkj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2krdafecv.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tlisqjxs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgvwfhq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yysksgby.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2moupxjgm.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcwaedv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2nucttwdy.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2bluckwus.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2cglrvzmj.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2iufecnqh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmalzbi.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2avpfllay.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuqztdv.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2miwvwdzh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvkzpnc.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkssyla.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrndmyv.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxkdlkq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrmuvkh.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2amckqxnp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2elyjbyxu.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2canxrvlf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxtsqai.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zqynvjya.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezudjguh.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrvsmgd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpmffie.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2sobbljpd.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwfsfxk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcmqbnv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpxyolh.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjkyawi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqvbnrd.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwiwuqdq.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2adaypmon.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2onowfdfl.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbromhc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbjbpko.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2izildlew.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vstttwzn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2horpugax.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuevrzl.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjnjejz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkwlwru.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwettbe.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2exbfgtsb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlytogd.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iciurgpy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2hyewguze.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2bghilydx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmaoxqq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwocmhh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvqgcwn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2sydutdoa.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvrspkp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2yorcdvcv.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yabdsgve.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2arjchodb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpeuvgy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2msiuuore.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tiummdgj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2daenspfa.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jhiceyyc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2srpxpmda.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2inydwlju.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvjylay.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2sayzvprl.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2idqpoleh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtoxqfsd.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfxhufw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvqsvym.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2eesnihpz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwwtgln.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuzpvgd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xotjqfdm.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2thmgshfy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjseahh.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2toxxvlux.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfveqaoi.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbmvfuu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxmzpwo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2udwukhcg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2trvbpcib.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfsocei.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dikacgwz.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxjbdcf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyaxaoff.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2olffexme.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kybtggdx.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwzbrsi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2qivnnudr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2guyijldg.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwbxbpw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dchetyld.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2wuszlsax.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqbgric.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jsayodhz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnhyqcn.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsppwzh.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtgnkwh.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhnczjd.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2idsqktiu.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2neuvfain.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxixusmd.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2webqueya.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqyxxbn.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxkvopk.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sktzqtfr.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2migfsxsb.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2thaurlvm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2qozwblow.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkkxlmv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rysbkxie.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgtpryi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2pusxlmmz.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzwqvax.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvtjlrb.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2smjmytrq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wkiqhpxn.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2andqkqog.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2onoplxpl.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkmdpgw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2miwficcp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsjcqdb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2baizutws.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2pphntqjm.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2gzaicujc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2avxffxcb.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcnzizr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2oawgecrm.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2purivzah.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrbygsk.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2avjosscr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvicqmg.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2udfzmvte.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pielaklz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2esapjxoc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2afzzdwoz.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdgkmzy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcbunwn.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtwlebj.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxrilkd.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvtdptm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jywmakgz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfhhxpk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpelony.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbheiui.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsocblu.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2epjwfwfb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgkkfdr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2erzkktwq.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yskdrouc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zspgpxkk.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuowpbc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpprxdzl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2quxlbman.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdffudw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnsxkvd.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2yhykvbhk.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvbtdeg.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvufwew.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwbprnx.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2deixpktj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuhoikk.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfhxhjw.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmwixbb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2svxndcqp.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ectspjhy.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhxbjkf.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgucqzc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmocisqx.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2skqpxtdu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pravekxu.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kaooimyr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtncgee.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ipphzgyu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjqrwwi.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ottyeybd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnixqrb.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wyftltew.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxzocej.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwthzpe.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnchtvi.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxhetfy.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjkoqfz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ofeipmhz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wbeqbbyr.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2svzllooh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxfzyxy.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2djfctodn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zcixgzik.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrnrkgn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbskhmj.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iigktxhf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2crrpgtbi.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrsxkbv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2trvvdgnc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2afpdyvhf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2glonydkh.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvrmhqf.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzksjhau.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsyhuab.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fiokocnq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcrirod.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfsrgiv.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2srpuxlav.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uaptnnwf.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vectjnbf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gounuhkl.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvaawxu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dffdmcww.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqitkxq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnsnuiz.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lbybyjao.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2egkxnppf.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdpxfuv.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbrlpil.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwndvve.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2yqaahzip.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxnvmdu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cunenvsv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2aegscsrv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gublntbt.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2verzzpan.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wavvbpbn.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2okchhcyp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vylotszb.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwalkem.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2lefboafk.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyjrzdf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cxoowmyp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuvokkb.html


<!-- 参考信息 -->