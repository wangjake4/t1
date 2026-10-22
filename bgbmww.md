代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjzuttj.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctoflmaa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrqlunu.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2coerwvpv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfegwru.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aiujsjbk.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2myzaazyl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvplfsn.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcojlbe.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvhfaah.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aylphfqv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsubqca.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2huxutlju.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xvodtwde.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fbozfeol.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvqlsat.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bslcnmtp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeblvpom.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2yifrrlon.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdyqtdp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2okoyeije.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwgmalx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgoflqr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlgrock.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gncwjlmi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnxvqov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2asaebkvu.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsrnswk.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2sziagpnv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2lqowhtub.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mzicqfvs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsrgnva.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2htghpdme.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfphhsbe.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2xsckcdav.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqtinzp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2inhfsygh.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxmdulv.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2mdettjxr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2riazvjye.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmdqyef.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ektdbjqd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcuswejb.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fedlflfh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2joxuzrzw.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2xbubqtxj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vujzvcug.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2exzdgoro.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgivlft.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2plfiwpks.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqpxkxy.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iynsphei.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2eictxhei.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jcewunck.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2kejidpia.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcpludb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxxxenr.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2cshesugf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2eluzdmtw.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2afxsvrsx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqdbegd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqpkgsb.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdopagg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkqkyml.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvrfugs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlsahxe.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2icxbplct.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdhjnmb.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsysqyiy.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ldisumoq.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfywowp.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qwarygnv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvslxdiw.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mineuhdp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2chatvyst.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mufuspxm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2aonyzkop.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2elulnfld.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcagcrxq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjgqsff.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpyswfy.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvqyepy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2obldbuiu.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyleuok.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2umlxlzub.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzaefvx.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbahdwt.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrylbol.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2appunctv.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2edhmbkrv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgutcotm.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pcknxkye.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pexxjvii.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjkkoew.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2glvclyef.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrbfstb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2woaaaynx.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxxbjap.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqswkvhc.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuxsqpe.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sudfyhtq.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jyllmmgg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrmavaw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2txtjkxww.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gamgxivi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyfwfkr.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxnvzej.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2qkitnycu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2fjymqfrj.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqxhkcx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2supsfexj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjiwuqos.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sjeqsymk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkafgwi.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvnutps.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfkkede.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2btztqkvi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpgkwqy.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xppahkrk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjtntbg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2txhyzdse.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2helzttjf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjemlrfy.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ysebdiga.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ldczijyr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2hitrucgf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2biyqffmo.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wldizefs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2atlsaiyc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lazwuggd.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tfictvnb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrzecko.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmekbgu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2yaooovsx.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ognvtkzl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpjrljj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tkytfoap.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhepehe.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qphvegui.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2wouazpcn.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aixfrazh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyymlmnz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hakbhwoa.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbitkdz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmgcuce.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rllyaove.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fdomifqt.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ieruuzie.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmgwxsq.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzjkgnw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgztequ.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnkwzrm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2alqyprmk.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2eotatjhk.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihffxqbn.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkinqhw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zliliyyo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2beiktqgh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hitjhyro.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zojcnqfz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqepedjd.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxxeicp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnfcgfa.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnvntxs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xoattfwr.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2krlloqnp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjakmcj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2thjjpwkt.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdvspwc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lowittbe.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ohujdvng.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmskujo.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sqypsxim.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2xedfskro.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhygfzc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrbvpwg.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxkekul.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbhsslp.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kvibwois.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwoiamwd.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2vriknbai.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2snzkrmlx.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2fsybzqir.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lujqvrsj.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2huexfkwf.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhsodes.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzrubzi.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgxusla.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrzdmtk.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2osztvsmi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2awgqpgnx.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vutolghe.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzlkary.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfknstq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vavglkqs.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2uoiqmaaj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2narofvxk.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2engasdjc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfcricw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvosmec.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2egeftalj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrtovdr.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2woyygilk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hnajhgbx.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrhttqm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsnlqiu.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ogazdpjq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrznskd.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2toaailnw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrlihcy.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zunbdotr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzqhzzk.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzxcsfq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2myugakts.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lxahrvrk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfecrnsq.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjubxyy.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhgtdkt.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyhucjb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhfhzxq.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrnhusa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zghsdutd.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxnzbru.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsayujn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsdwjtr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvxssyv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpirdeu.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkdcmym.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jprxpxkb.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzxihks.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfisggs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2srzwzxpj.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwtyzio.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2htxeetrx.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2gytbjjlf.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2svmaiipi.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgjuazg.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2btmaqyxn.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xczuscmg.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hldbtzuk.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vlclrhyb.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvgfkkx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxnzmlw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2sebcydkn.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2okyxhzxf.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvqpjmj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpfaxfh.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpodhva.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sheqyceh.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aknoqxfw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eobiivrw.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fcngqqvk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yrghokon.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tgopyrhn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmavuxs.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2onsiaxvg.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgbidln.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlqekue.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtknkcgh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2oybimvki.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxsoxif.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkvkoxh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2olfsvvff.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oikjztqn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2raeyzflq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2svyrsqah.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwoqgjs.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wxiyqunm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2udlgwnnx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhqhojt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wwszfucm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2faqgadyb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqeqjid.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zridphvb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kxojfhfu.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvahztr.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pidwdjax.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2cheukeij.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnslpgp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlswbeg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eriipwbc.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzqvkca.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sliyyctt.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlhbrkb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2afuvcwjq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdvqkbc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2audxigsv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzcdxoo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvbmrgk.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjptdrv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyloyfg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2acxntgib.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2edbjolgi.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqgsleq.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2yamtdfsw.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmtrnrb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqihadw.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2niwfhqvq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnsaeia.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uhuumrjh.html


<!-- 参考信息 -->