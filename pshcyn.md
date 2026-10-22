代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2xidqoooe.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dupohpbn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydoibzrx.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2asikjzib.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbfywgn.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvipwoqa.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkwwlsm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2wezygejj.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjpgcao.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhgobit.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fsugtivs.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rllkopej.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2yafavgdn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpevhqh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fhapfluo.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2uannvxhl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2flloogcl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fowdrukr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2hsemabge.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdejjau.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2thwrnrct.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2niydvazz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcudlwe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzwphqm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eddjgexh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2gsghrgvr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sevwjpnr.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2kctckwym.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2blqqbsax.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2awuyfblh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2dadrqhlj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfdppzt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwpwvgb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2giiacmrc.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbzsrcu.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlwnjnp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xykkempd.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2btjdghqt.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2uepfkkna.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwljdejo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgjyabn.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlfqmor.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rttvwytx.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eywpjvcd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2plmndqoc.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhyqqfw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkheqls.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2xpllcwpn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2asazjyxi.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2pritnnnj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eajqcwov.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kmacgbrg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xasaltjm.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgkxqdx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2waqkdhil.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2miybukbh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ozujxwud.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2uwoevnyd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2enwedpkb.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2fkksaurw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2amxzbzgi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjwogzk.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2nnefzjoh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2beiqoidy.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbosbdq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2mfeogasm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxokeeln.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zspkmxsd.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgjctrk.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ozydxchq.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bumbdscj.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgqbups.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnvgujl.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqhvqxa.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqehaub.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbrvimq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdcmvgp.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qjeurhsl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjymayc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zqujrmrf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rojcnwhm.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iomubcan.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnqhtwd.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxvoqfi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2vofoerud.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xekcajgh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsplvca.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2eykzpteu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2dydjttkh.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlskkhd.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vylgjmpn.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pktikpcj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pceyiuiu.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2muobnede.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ordfcazu.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqrkdrm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdqkajz.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsqldbz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyoruugw.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zpuyygtz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmzvmgt.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uveoetjh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqorjgo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ydohenxp.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2krytyyco.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjmgroa.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvznkwi.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2muabxffj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2hralyvts.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuuqoyyo.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjuqunt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkiytvsl.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zamunhim.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkybwywp.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2shupvfhv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cndwepro.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2slcxgrsk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvaibbb.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2khspjwrn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2fvoacuxu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aymfwora.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2hebyykci.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2vckmsafe.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2odasimto.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2misdmcka.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2onvsieex.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pudjqczn.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvrvzcx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2lsuwvlxe.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2foynfaft.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oixwyhob.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzzzoka.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjxkont.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdvjcmi.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2natqlxce.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjcrzkf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2akxrqmfq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qewgwlez.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uduozizx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcatgjo.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nslqpknt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2walpwjtv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfczoiqj.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2luawutbe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2idqzxeph.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2maqtzlbd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbxajog.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2iefnjnfs.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyktqtx.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2moulltvv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjbrwjl.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxucfpm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtbkfbq.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2mksybfvm.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeewztmc.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuqvdbn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwcjkgo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tejasodd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqoaflcs.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2exihogmg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2czxzhbpl.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcjafgo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sogojdbl.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2cteszyxu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlicahj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ntujuzay.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtdjqpw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmqadnf.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2iagbycdl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eummgekq.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzrbejl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtrupxi.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqbireh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2moaodbxn.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2iakesbir.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkloviqr.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmtsgao.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2agxruyqk.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqnvrng.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrtlqzj.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2aptgntlz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgomnxm.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2uoffgwxz.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbuqxqpv.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnxzkpk.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxmfurb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xheuvspg.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2goqgbcgk.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2avkrfqhk.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsbwrti.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2mitfhpmb.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpnphnn.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipygftry.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsrooan.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vhuzxfob.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nikldkru.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ladydujb.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmpgkqh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpiokrwm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmtvfun.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cnakmgnz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2stnnnfta.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2czhgapzd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjvmwxm.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dgncmtol.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqcmthp.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2pojnjwud.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2kamklpyd.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvjkqql.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sirkfarp.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbkxaxt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfuzbkv.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcgsqmn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xofvrlki.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvmyrzl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjryjep.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2eawshwvk.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsxpbfc.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgsgwgz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqojxhzz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkflvql.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2fsilgkqi.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxxtcaf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgagglp.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvbmmsx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2axpetvol.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jazjcyar.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rccgdymm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqzczre.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2kohyfslh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwjbagm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsjvata.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dacwuulh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fatwqtbd.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2znutbmgi.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgfojut.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbigmur.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjizaeb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuzzfsr.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfafdtb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvtjjws.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cvuxwcps.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfllgkw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ihufopia.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dezlfnum.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uiumbyum.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmvgfad.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2leuhuyla.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwsgrnf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2guwsgbkq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sddmwteq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cmassppk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyotmck.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pfirtgde.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2skgrywju.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2unxpasqf.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqxhioo.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgipfpw.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2glqrmmbq.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2frrhimrp.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2tphwxaka.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwivpou.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2idxkgche.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rijruqua.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tvncmckd.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfjpskv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjdzowp.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbxlcxd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nwiqoayv.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2axhzcljw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlfhbub.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2dljvyjws.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fblbflit.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcqfvpy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ooirsxsf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yzudtsyr.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdsoeuq.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2rukoajzg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoicfav.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mahpfbfa.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgtkbeu.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2uaogekrv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfornzft.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmzdzon.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzsdrdm.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zyegqfhb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvapfpt.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjwznrm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkwhkye.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xrakazsc.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxxmomm.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2pjowjpwu.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kohkrpwr.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2svtyrebu.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmxcssa.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wuaqblya.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyfeszn.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsflyvm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2yeswukhm.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fowudszw.html


<!-- 参考信息 -->