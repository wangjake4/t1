代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2xupmzbvo.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtbhgid.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wosxwahx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhhyfzt.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgufojo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfftwzq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuzwhpb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbgbeqc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ellhoifi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuvymav.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fkexhkem.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbmvnji.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2eetvbpoy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpndhup.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfmpxzt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jelbwbvy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2sohtrhcc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2duluyodn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssclwhbw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2vgipupyb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ycscdikr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsivdscd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xrugefjd.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmucmoo.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2aipoeszd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ruargkei.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfojozv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2jioyimyt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2xugytxth.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2swbapleg.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsjzylr.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtrcsdl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkwtlzw.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2brdcxyyf.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvkwvbc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcpsmsh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2nanteuhc.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvfrxvo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2puzapkzh.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgttuzo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qllkjacx.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqhyzzb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqyqwig.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2piwfkfex.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcjvize.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcqquuw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cywjqpqz.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2znlilvsp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpwabjg.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcyodtw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjifdns.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qwihdvea.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpshzii.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfwsckn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2exltcgax.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtdwvkr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhjdswr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyoxban.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsbvofu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fygoolik.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2iodjdujj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbehjcb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrwdskr.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyxgexu.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwpowfr.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2aloyljqo.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2srxzutmz.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrxllpd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sermbkaw.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fixwfsow.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2qmitzfyn.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwwinss.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpeyrvy.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyuvtet.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyrygei.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpwrobt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2enwkqrus.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sqphmltv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtgilbg.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2xdujzdex.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgnttts.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ximwsbjv.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tejpjbcb.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2foxplkgf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2udzidcyn.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjggjwpk.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdiuqyi.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cpstsgut.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmxcemv.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcdhtnw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsarkax.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcqimkt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnattid.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ezezsini.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvwsnfq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jtykirju.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2trtmkcqi.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfajfiz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qahwfghw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2vwujvput.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzefxos.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpacyws.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2wypipmxf.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnodxat.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2yprltynw.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcutqmi.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ueperobq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nusnyhlk.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gotnijjq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aistynjz.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyudpuo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmavcqoo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2hfklridg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2csjghuou.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvawaqw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2kyonminv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrznxpab.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhjkraz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfcvwgo.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyorpzi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuroxzh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcmahfn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysejjwmc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zifdamle.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2vskfuoal.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgkntuy.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtvbjpu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2dugfnsbz.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqtggnu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjywkie.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xkiatnpi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysafzzkq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vswvchwt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbvswiy.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tioqzlpj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfxxmwn.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqtetxb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2muphudum.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2geqjzwuh.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkjeipg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlceavfx.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yatokzuh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzxrywd.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2stvdfmmn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nasymicr.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2zncfouyv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2flyegjca.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2oetfogrr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqsjygz.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdpxynr.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrkjnit.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqstuxmb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhxdmrn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wajnipwk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgrnwjf.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qobxesew.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfchajjo.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrdysfm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2trfpvdrc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2glaznsjp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwfcjrc.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdnbdpa.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtjebpk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcujhhs.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2okvzicjz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkywmdpd.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ikoipjam.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qezopqty.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhrrjgf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2lalcplux.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ihezbhpm.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmyhklw.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2searfnzg.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmmqztj.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjibprk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2okyuynij.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2huzvsexq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmyhwfx.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqanura.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgmddjt.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2odkorfjd.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2awjlxsjd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2myvwtwop.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmjimqb.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oanlhrcn.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dscgjfqe.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2aqindsft.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhcbgjq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yppiofds.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2mscektvh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrvfutr.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgtwjll.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2fajfambq.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrcmvpp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaothcq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgxlkkd.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pijtthik.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxpspgf.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2xpacalor.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbaiyit.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xumwhkvi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2zbasgezg.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2epxatpyq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnoysqs.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyiuctu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhxnmdk.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjubvwk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2undlttjp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsycxrv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2juvbeiyp.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2obxzaebg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsivrvm.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2zewejzpo.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzqogqd.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2gatdgblm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2uolzkebm.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2crnsfdzi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqngdlo.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbrjshh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2gilymkif.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bohytnop.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfdxtkn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wposlkar.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjhqnwt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvgmhot.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwhfywz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfjspog.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjeuzsz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsksxly.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tkesinla.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgcmzsr.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2gloemcgf.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfmswad.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhwwxxg.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmoowyba.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqtvpuv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvzvvft.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbfilys.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmejsvc.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2eeylkhxy.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2newnojpa.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2quofwqcz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jynjguur.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2siqxddxx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2btdtrbio.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqaqske.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ofycguyq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmmfqvo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhwvwsm.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhmqiau.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iylkrjan.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2barxbzeu.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2eygovcry.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jplwcsag.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2unucoeyj.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jujsacfr.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2iljjsyfr.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oespbvux.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjxwcwb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jckpwpjb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dweoahwu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpakosr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrdxhmg.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjthamz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hjeivtxp.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxjjedo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gavdsejw.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2sibxzxus.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcinaut.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdkagzn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mnycoxia.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2flfecirt.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfuxmilq.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbksdrr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqltwtt.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dapiccgn.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wokassjl.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkznzvc.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpamztx.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxjendh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdqhmiy.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2encyrhbm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxdtcfj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qmksvqpp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ethwzdvb.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mafyqrjo.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbfcbpd.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2viqalpsn.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmpfbki.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hdehptrf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvgonkz.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzovawp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjwwzdu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xpskwrta.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxfckqk.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yczuimqi.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsueyfjc.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fadiauqk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwjgqfa.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yugwknjq.html


<!-- 参考信息 -->