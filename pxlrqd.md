代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkagftnd.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zctdunsn.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnveweb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2oedxsqgm.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qmamqpbo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxsulfp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgotcaa.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmqjpsz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2khvazwoj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gsukkehf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jzedsogz.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2orkmjxtd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2euzrdeim.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vokbllrp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2vdprktly.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2obfnvzib.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwtiwxz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2hoduyhht.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcghcir.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwuhefe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2msgqffjk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2idlousbn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxfvgbv.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2gycqcqtz.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2lumzundg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpypgol.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2akwqnweq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2aiakeidj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2pytstuks.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbnzypj.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpsuxti.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2xnamcnkn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2asjzocdx.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rngqokgr.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvvyteh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2eogpjoad.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2aylnwzny.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2dsklceom.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtyzwej.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjjhjha.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmpjqrh.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmuaohu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqmvbzz.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2orvqczdi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2taktdqip.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2llkgaexs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yacfkrnt.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgwjolw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqulhxmm.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2glrpvlva.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsuixwf.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpujzvo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuzvbth.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2unjgckpj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xeevbsmw.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2jerqgcgb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsbowsl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxadmbt.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2uarjyjwh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkkvfcu.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2axjioxgy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2scoymlxs.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jukhamdm.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmfthqb.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2erwrxjqw.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ccesynpp.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yixduvta.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcqvhpt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzyhevd.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wygvckqu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2duoiwucl.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2clnolkyo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrituxjs.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2itganczy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhcnnyc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2phdgfuvr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvytjswl.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ympoyntd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2quhrvnll.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2utxqxykh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2hevmyypw.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jycrskny.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkdkogl.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fyccfzgk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmilbda.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkrfpci.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcvjkmd.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxawhcm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuctlqbp.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rgasmcpk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhjablo.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvircvu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsaaidws.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kcupwfph.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pompddvi.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2znycaqrw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlfmavk.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrmliex.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmojklv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2khgsfgyg.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2otunxvzw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2xabyhccw.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2gyacizhj.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2jaujvppj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2hmckftzu.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcchtxn.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lruiylud.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2khubzhcd.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdevkkz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlacgvh.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zliirxon.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxototze.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxnxuoc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzukimlr.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2uinwyrft.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqdfilw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtxmppn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2edgsppkr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdrhukd.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uptcbqat.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2nqechqeh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2wkioggug.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxbynjt.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tunfdwlo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbwkuxh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdyhwsj.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkjztnz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2tspzvsjn.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyfcwmp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2uugtdasu.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvobrcq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhrufch.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyfyhkw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fibgpolt.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bmurpflb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2buinxgwo.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2keosnayx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnaeghi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxtvtks.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gygmvoev.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxozaug.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbefgra.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2syegsnow.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlowdrk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mawwedco.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2peixoatk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2suketqfc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjwhjmb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhaxinq.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2icxdslhw.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsncakdt.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2optfmize.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngduknij.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2javqmxvb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tflhrhpl.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyfffso.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxonhdg.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2anplozln.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxbhavv.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2clhtqgve.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqeyybk.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlbvzax.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2waswqrur.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2udxsnzoi.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyfrlkt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwzzmcw.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhefeyb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjztdtvq.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2edafllno.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2parqkjol.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmdhbqc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahadvubs.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfebinh.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqybfme.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbmlvvd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2vysmlyli.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2vixmoltb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhulsnmg.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2rakxrbgz.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xusmqpgm.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcohgrhx.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuacvvj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2apiqkixk.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgrarhs.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjxxbwo.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rciewspc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2huhsvtnp.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vvajjhsn.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtehklcm.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2booexgyn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkgzxbn.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwxanyw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2eivghwdx.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tetbhdcj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2stkmzobg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzawuap.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jfecrdlo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2mprxhsjg.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbaojqr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdwwdfc.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lpylcdnn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrsznmi.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlsmiml.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2kiiukeku.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhzhqdr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsndozkd.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zedssuzv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2exvwsigs.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zufuhrni.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqhqjmf.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2atebazch.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpajliph.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2akholsti.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wolbeohu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuzyypn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmjxxmn.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zyimczqr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2woodkbzl.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhmnlwg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2adyruspl.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwcujfm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2lidazfco.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfueqyzx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgmkyng.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2symubnta.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2loueseqi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2slbtxnuf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tyobswlt.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgruhuw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2umxfkqym.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqvhkjm.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2dksxlhcf.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2abfoveaq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqsivet.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrhkdlf.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrepmkp.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2qashsmrl.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwndxwre.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdzpcpa.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsdmpdy.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhqpdbl.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hxooldmg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzpppoz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zaoycpwu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhekbfm.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqqaxju.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2givfrpgt.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbqwetw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qocnjnue.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eikrsgtb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2acfegssw.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vhygrmbb.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkjcnny.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhoqagj.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmbeecs.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggawcwtg.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2eysirwbc.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2clpzluar.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnitjzl.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vicgapmt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nfagdktu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjzedff.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qrybdjac.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmelwrr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zirdfoeh.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrcooui.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpzgeoq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvpmcgo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2thzuohro.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpgztpi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpxoejr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtmtvps.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmbmzuf.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqhswwa.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wexxttlr.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbybjwg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnitfqd.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2phoubior.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2txwjnkiu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zpuqbmry.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuilwyu.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwnawen.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfnzxbj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvcypco.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2myxsdylk.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ulosewbp.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwihbdo.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhcygxj.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcsuqxs.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2owtxkkam.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2flhppbqf.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxkaiqv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xpavgduv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjxkyzy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbrlkgz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kzssbrrh.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czumwurs.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmanzgh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znmdctdu.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nembrkan.html


<!-- 参考信息 -->