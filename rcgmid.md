代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvwcueo.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvzasrq.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwtycyt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyvdrxp.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nieyegst.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkcrnxv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2apiwnbod.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xekpkaeb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2owurnzuj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmyfegy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjwjygn.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2irrbsvvo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mutybjki.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cixmyxoe.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqkfcmr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvndsxnv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2iugnnccl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkihdet.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxguuznn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2mdplmchw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sbofkjgv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2hepnxlpk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dobvqwvb.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfdyfby.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwrbqdz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2avwbqogl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mwexuyzv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2oabnfwiu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2eszqoufj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrrqjfy.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2gypvqabr.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfdnhar.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2clvhphix.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmmojat.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2rvemcxhy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2qynbxgtw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mocieich.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjjeeuh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2yujsjium.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzenhiv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpaebgg.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ngonzknl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfccqmc.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjxqrak.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzaxwrw.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2judptprl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vusdslvh.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wqciwgtv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2odtyeock.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpynmce.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2omibaohv.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2atlsljqd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrrkfmv.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2cyoyspgz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2abjwijjw.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2knqybvqv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2suqvhefq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2nepjaxzo.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2egwdhdkg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2luuhtbqo.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2yubtrlmk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlbywuv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaysiltj.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bajfibnx.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eddutpqg.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zaglmabg.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtlnqpa.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzzpqky.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhtqprk.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxbyrvk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmpeeos.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dyftozpv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyletvf.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjpalvn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcaadudu.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2krixpxvo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vridtfhi.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dxclycbc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyukkgi.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlfbgmj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2dexkxqsn.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmzbazx.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2phwsymxy.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiibjoz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqswpbj.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hkaakdhd.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvovvxe.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2nolhbyjg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jykpywxm.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2pqahsqep.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zamsceyn.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wajotgir.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqipjxre.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jegevqef.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqecurzv.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zrydasoq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2unjtxdrk.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlavtun.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2asduhemb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2guezlmbb.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2swisosmo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2udhevuny.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2adnuxwjz.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2hauilqkt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzxmoqg.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2znszcqxw.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gbffkfqv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgaiawh.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rituaqjc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oemawvrk.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qsijxacd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fivfuikf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2byhrvrxi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2psqluold.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zosmadep.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ouidelhn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqewrhm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2exvzzgsg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2riegxcwo.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkinebc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2gryzlihx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtbieaj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oytdpppi.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sznpesvb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcdbufu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqknwddi.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbifouh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqwofpv.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnusdfl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzpmikv.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvdmhyu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qihljvro.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jujymxrx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yaavmcst.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqqlfdc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2naqcgksw.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqsrtyj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkgokly.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2picltqyg.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kblncncp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbcyvbf.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlnzssf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbythiz.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xespymlv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lolakdqz.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2xabxdeuf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2czxvnurj.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjskdqr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vouukwdn.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2blxnvgid.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfglrgb.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvujiqu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqhmylc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmwfjrd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjttcsg.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjzgppd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2irirboxw.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xughapsc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjirhhct.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtbirsk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuhwdbl.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hqatzwte.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkixgsw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqulwaoz.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qvevvwtv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwdebdz.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwegkso.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaatrcyp.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrazrjt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2mehiekrb.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bswunnqa.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2upleioeb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fwekeguj.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2syawvcrp.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvmicga.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkofqaa.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvcjdgf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzynxdwc.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2armqzgxl.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xotyryrt.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2coumqwnv.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgzpynm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2aydeasle.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyllnma.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2odsrgpmc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2etraqchs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2dvduocxz.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzegdwr.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2citflbea.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2uqaamtmh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2shzwipsv.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jstyxens.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2qagplekz.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2txtodwtb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iplsrhpt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvpjhvb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2snxywiuc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnsvmwd.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhqyjaz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2wfesgoul.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hujggdpg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2icmpzunf.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdmhwub.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2grfpjldi.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pngtlxzi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwscprsn.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2szmfrper.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bffiiikx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyjsseg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wayemfpv.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfhjffh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzvshaz.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2mslfwhbt.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqllluzd.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2loqgcsif.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdekopi.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2boecpfmf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2vljvydeb.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qprwxoud.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsttjvo.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkjgatv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2yacvicgg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jweosrhr.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqvxsto.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kwajuakl.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2isooxlxl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2owlyczho.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmwwswh.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yecbtqou.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hsobqywo.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2avievlsg.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2auuweymn.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2blbtqskf.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2bebmxkfd.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2llezlwhw.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzdeovf.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2fftzblqs.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cibeavxb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2msbfrqle.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzsigti.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2slvtfgnf.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjlfmrw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avixidaf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmpxrqw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lljpvcba.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sggwlvwk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nayxpulz.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwluhuj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2apinixaf.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rteooeok.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2admkjdbd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqvimxr.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2tlyeixzc.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcktgijh.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsalytz.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkucgcwd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtuxulo.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfxytzd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdxfpxy.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cerpseas.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aeiwtldw.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmtauak.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqmakcj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpdqfhd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ubldnrff.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wbksflzs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lhklzlmn.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsgeshw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gftzjcqp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kvineqdv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgnjbyo.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlscewl.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghedhsjs.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnpoiva.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hulfkrdj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfbtmmb.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bsioelfg.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzondbe.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdffnzf.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2unijgaxl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vojusnaq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuvfucq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sblncnyc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwjaslg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlejkay.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pocpdapb.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2jluldvyz.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2clommyfx.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fuimvkow.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2tegbiimh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2bgysqroe.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gicyrulz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iumqqmti.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwjriza.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2kixqgcoo.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjcsyzb.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikykuaaj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdewled.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yficqtgd.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zhaocmgo.html


<!-- 参考信息 -->