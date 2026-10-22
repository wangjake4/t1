代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuzpgfa.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhyaips.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2zfabfkfb.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gloyiroh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmfvjpx.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kadvddtu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2enzsfsrt.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbvpzex.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjvduhh.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbavamo.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpbjckt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2tzghcjtf.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vodxalez.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sovqqihg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcnkczd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrosdvg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2vyobollt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uobzlukn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ioauyfav.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ehykscde.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gusivhyc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypaqjpny.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2cbacsnwi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbfesrr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcxsmpu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2axskpvgd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvzvzik.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpdyrbc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrjzyow.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgooehzm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhsjkcp.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2elgrstgz.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxrtjeo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2opgmzatn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2giftviwu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2dqquaolm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2habyxfxh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzhzqit.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2pfadanpd.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ercoskjz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmqxuza.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjmgpch.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlpucpx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwfxtzx.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzpdjgt.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2yftftijh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqllyyzn.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2epojgivt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dquckgvc.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2athncknf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zstoompo.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqqqloc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2mayfubea.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2unfgonmh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxykpeso.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qggslqgc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2guaviiqn.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdblauw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdxsabp.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2sqntdfxs.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2aslgksjm.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2juumtafx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhozcyb.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqrwelo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2gclumhfb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmzsjef.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgmbgxk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xocabgdz.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhuankmh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2esvjxcti.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmjcprv.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxyxbwz.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhsunye.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fymclxyr.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2khjyctdm.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aahjifvs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwvxzcm.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fyiiifcn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwcvuct.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxcqfyq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2djaswpgg.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbsfstd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2picgxqcn.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgurjxl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2aebiedrb.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzhhsrx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzusijx.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqaupcf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjiuuar.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2aoizngal.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2epsjewuj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxiagzv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnfordx.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhuatmf.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2muehrweq.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwsaerj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrldrjmy.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2uqebhlxy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eezyyqdv.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlrsica.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpfkdyf.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxynewq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxssnjpv.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cuouqlgs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uslegnkf.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqwaoeh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2swoswjym.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2sgthaoxy.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnjxefw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2kaduvntl.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlopvkc.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2gstiuugd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyhmhgr.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmerxjaz.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nwiopilh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2orteoaho.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nsazimpj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2slcnhbll.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ohstqtgc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oomqiqqu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpdmqmp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iefmitmh.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzmwazw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2btzjznls.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvuwykmz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2unhlxlkj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxqbbpm.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rklrzrrt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvnvqqv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfwfsrq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2htrlusil.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbxcfna.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2lpprvwph.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyyecwl.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jdntrmov.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2tibfddji.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjjtsdo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkccypg.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdmfhbm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrtkvag.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgxcgkn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2szgdibeo.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqiztks.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2mosoypgp.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rlminael.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfbcjqk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcshtmn.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2uwoulaqh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uucbzdfp.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2luautjlu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkyqqbr.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzuxvaw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwrqhue.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2diaoiwpu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gypgmahy.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyecmzz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2umfidonu.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfuznkq.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2mduybpjn.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzuwbvd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqyhunn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2sesttgsi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2seulyxvp.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnqjysc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hucdluql.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oevqajkw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mihesvyf.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpvujlw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oembkgzf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkfthfy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2wudurgdu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2prxbczty.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgnsgpk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpoifpy.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rufhbtyo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2amerchfq.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwennkm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2uebuqppv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2doopawvz.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2tybwmpim.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hivdanoc.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnitdjf.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuhfjbl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bevbihlo.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjqxdkd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2hakzivxg.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnmhnoi.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hopcpepj.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmeivgpp.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkjabcv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2eofdadep.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwfghtk.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cidlrrfv.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2anzugspy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdxmynp.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mgreuoel.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnrafqf.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2moqxldep.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmyyhmp.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzrohgg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2nkipncij.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cdiwzfxw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2emtmnvgm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwpgxgp.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rthpntue.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpctlkcx.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2dampcafa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbcqjww.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yonbznbn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdtphgv.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbpziok.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2csjvgwgk.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2uehxcuqx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnuflcq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eycpijej.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjxjwyu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbzjfoh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qoiewxqt.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pfavigst.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddheuwgx.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2opmbacoy.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcgyfgc.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyhifgy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2eeumirpj.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdretyr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ugucdruq.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqthamw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2djoqcntl.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwmonbg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xilvxrzh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fznruadu.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyhuvpa.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yifdxseb.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvafqrf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dekasrse.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcjzhgd.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmlvqxv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxfzzti.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2pijsndgm.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2dkggmxlp.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ypghiats.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdmbptk.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2opkpxyyk.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iygdgjpa.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnvudkp.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtfmyqp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzpedrr.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fbissdob.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddptxxhh.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhlnztz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxnimsn.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2neaiqmmk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjtkyiu.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsyabte.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2msasdaep.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnruhvj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxwhncz.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2edrcyifg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcppwow.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrmfhat.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2agiasrsh.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pemcoshr.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhtjwqf.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2okoyghhf.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2silmotyx.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdoldwpt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uteubxjw.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xaoardpq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rfslongj.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdjuyoc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjmlcey.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mpylywke.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyzzvat.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ouryyqkh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkqkvem.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxxtpfe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsajfoa.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ozevnvee.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fcoedtac.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuqemdi.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rorqfgyo.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vuetkdev.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwwelsv.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfvltyw.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yecpbbla.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qibqofus.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpasstvu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkqyagl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzgomrf.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2akbjmglj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxeynft.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbmfycm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwnpyhy.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uudanxhx.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdlpplr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxqmlqq.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxhkggq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwkwqbm.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnqrdhc.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qtktkubf.html


<!-- 参考信息 -->