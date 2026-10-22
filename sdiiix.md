代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2islwsunl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2iopletrj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvdeajr.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmqyeek.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2hslqpmsy.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2omtunsoh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqtsssr.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmduvzzz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2hakaaclk.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yultczbj.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzbvcbu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2lkoohhti.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhslekh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qunsudgk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2khgqvrny.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvbfhbw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2bqceseop.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nubwnxje.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2woysmdih.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2iewpzjfa.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmjqphb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2scnopowv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkbvahc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyydjue.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2clwzywvz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2djzgiqsr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwghzxju.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2jmepzvsm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pccsoymu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyucupg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpqpqvq.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2qskwhgmi.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2eykrzkoh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzkiknd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgnkaid.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2plbkpvpa.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2cbglxije.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2azfxgwoo.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmppiqm.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpoiejb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wyztpnke.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jisudvhi.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyvleir.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2xppjejys.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmkamvy.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2grpjukdl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zseqatrm.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eguyyplk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2oycjxkyd.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrttywq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sycwhhuj.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnpmmmp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdoyzww.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2kekvvvbt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xixdtfmp.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yawkirpg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2yujsgyhx.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cogibzsg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2iltsvngb.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbaeira.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2slwypatr.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrflyfi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rdulrcvf.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpduycy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2xcibnkma.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqhooco.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmhkjnv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2htrbjsdp.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2amnnrrpn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2agmjhzyx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuytfdam.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2euwvhbyn.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyhecod.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkurbbj.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyqebcc.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2egbsbkoc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpndwfp.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2foycwafb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2mdozvuek.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqgmtgh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2oodbiuuu.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjisnak.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzyviis.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qgarxnzb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2etfemktl.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ewewgixq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lahcehzd.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2uosotdey.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlkpfxp.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqscnfg.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rppccvqr.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2eahxrzld.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2jkilbdtf.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lyleoiqx.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqnsmea.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwesfqi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2osnnivql.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gbisopdu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkzvxzu.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rzeolhas.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eajqkycm.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhllwxu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2simmiukc.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xarceqme.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxpwrcc.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2octygcpy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cddzfnpu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2gdihfahf.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzyclqy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbabczkd.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdhqthv.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ugygxynq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2rvecxlxy.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppoppjqs.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xztzlvfa.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fizcljxt.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2blysndwl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcasdjw.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lsaefufk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrtwejd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2usqavrba.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftaffpwv.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hifaiqap.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2womvhnvo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyphkdyv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkpdwit.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezoddyvi.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2alzmsslo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2enufuzvr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2cdohbrcg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjaacxau.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkgtbwx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2hryonhnw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjkdqom.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsldrdy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaumqvzq.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfqnbgs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdizrki.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrqnsnk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ietstksh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cufxaiow.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2epdxvpmm.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2geckogpp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2gooalukk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wxemdper.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2glfzleft.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyzowok.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2iyekttda.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgbzeup.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sochlgtc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkdqbwq.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gulabplz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjydttyj.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2neoncnta.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsswyhz.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbsruxu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ninqirip.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyythdl.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ougqbudl.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2inzcvbso.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2iubwvtdk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpvabhx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fujdrykd.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmvwugl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2emiqqvmy.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cqewfndj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqbxmwz.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2clroouwz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqzlqcm.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzgzkcu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zrajnyne.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqiruzml.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jylibpwm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lifaklov.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2tljmqykj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xabgorop.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2viemmfoe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsamvof.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcxgnnd.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2htvkarvz.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxebnra.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdftyutm.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwjbizq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsyebvb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2alskqbtd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2givquvbc.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ibowvmyn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbdlztl.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjdupab.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2sawjpmog.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ceevmsyo.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2thlqnics.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iytnwzqb.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxytxzd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2eekclsrl.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwnddgm.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyiryjoo.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2piksyjey.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vvecavct.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlmyfga.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnvcwea.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfjduxh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfslqfff.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2pwchulvs.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gscxgznv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2djqpthew.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2awnnlmzj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcpbmcc.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xsaaapab.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhadoeu.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjwibij.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkcydmf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ozitkoxq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyuvdud.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2shbipymf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2acyxvfrb.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2slcwwyyx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmultrn.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrsvegj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkurnmgu.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjfhunb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxloqliq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2qbotxpjc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqiioijn.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2oveudzoj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2vxaqctkp.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aahstlmv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jleectdn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2adhxeflp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrmfubq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvtjdcr.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lvawnbmy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzqztbw.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2klbocnjv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tauwokma.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqulrnb.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ykylqxqv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnyvfjz.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qioyhpfl.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnkcpqk.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlfxtzh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvxzywh.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyxslfh.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nnalwubc.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2wckfpkll.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajksdpzk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2adfviaay.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fytflnds.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgivfiux.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jpowbdbh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2peoazcec.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sfoprmni.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbxzepk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tskpsuot.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyencnq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qseobkxq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tulokrwq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpdlgca.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjvkwbm.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgrsyrt.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkcdyde.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwimnpmd.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrumhypb.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdesyhs.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2nrovgiai.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mgeslcbt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzrhzcb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqwybfe.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xergwmoo.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2egbzwubu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aakevcun.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rimxfwzu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdgidyj.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2paaoqzgi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyduffb.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgowevz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfugxkf.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrsjgbo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2unhqtxcw.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzkhelw.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgoqfzsm.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqeuyeu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgeufhzt.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzjhled.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbttihee.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dweojvtg.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gemxmdyi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vivniwaw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuhtcgy.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rzupwfji.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlztzuig.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrxsybp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkpjsns.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpixeau.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2arjwdxbf.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjuhpdq.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2baaennnb.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuxjsjv.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2apasgeoy.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lojylssn.html


<!-- 参考信息 -->