代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvuzzuf.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2anhhbyei.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjrrgwk.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2trialpeb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2guugmhbc.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxopxmp.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2njqbzlqk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2hkensulm.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzpbafr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpyaviu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwjtcfz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkbktzc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhompqz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbenxcz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrlkimd.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2aiazblnu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pneqisom.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2soztcvtx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjknrix.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsaurtn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsbyxsh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwhftvg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezutqthw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkhutij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nictcsjs.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvuixgx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2edokyikg.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2sizjwzml.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2scagedgy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzhjfsv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxaaltk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2gacepxbz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgmuhar.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzvxbhr.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2nputltqw.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmgvool.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqkalrg.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2owcriiju.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2huzucnle.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2olxpqyjh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtahoma.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfeamgy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgufytai.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2swwwvpma.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwfrgmv.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2gltktwjs.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2owknbqfk.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmnnumj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdchtjs.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ychnrsuh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpxjdet.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2csramxcv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mszbyxql.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdswryv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wumzxolx.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zvuhipal.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2exdaualg.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2vblqnbqt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfkhsrt.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2eabfjtke.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxawkjn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2zebtlgwn.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuysnhp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsjewot.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdybihtu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2agtxwucj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnoonmxh.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2immiblrj.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqfsobt.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2awlxpert.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsoqivv.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2satesoaf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wehpigmo.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uhakjzag.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2jkttyglh.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgysoov.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbadcog.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yyaplacl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2igwxfzmq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxznxjx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqvskzf.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdpvboi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkercfrz.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2uigwegbb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtoxlewh.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qkszrpjh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ualmoled.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrttegt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2fwepvlyv.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwelefk.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlivumwy.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvdezec.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iowkfpvm.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2anglszrp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkbjphe.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2uorwbytm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptttyazu.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvrdtft.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbebuaf.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxcvfig.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rybumqtr.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbinwck.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhaevek.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvxmram.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uadeocoz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2fiiotdvu.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ikluhruq.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2poggvtyo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpgggoq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bylxffoo.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uyecvwni.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2amjdecqs.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aidscatk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfescrz.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdukjov.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxecjgp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqwaloc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcqfgho.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhpiynv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlpblsk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2okifarug.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2rixdicjg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxipktcd.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fglnvyxn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2nesucqxv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xytcvfjc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2megqeqgy.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2szlyolsl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpgnyla.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzraybo.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhtjabs.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2uixvkszt.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iamyczgv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2axpikysk.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lrekrevx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsolnzwv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrooxop.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zovkbhtc.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ektkulnf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsujkzl.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nzghojhe.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbghuec.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkalhtg.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zuduvwnf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2woksewcn.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rllyqaej.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbwogfv.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2htjjzpui.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdyfjuq.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqiezgc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nutelnld.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2upjqoazn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cedvpzkh.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmnsahr.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2zusczcrh.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fayhwqtj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbaxzqb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsefrlu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yflvhcbv.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2juacnwdt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2niltbwip.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvmgbvz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkxlljw.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nmppetvm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtobqtez.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2woxsbdtf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfneanu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2epdwyomp.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jiaxduwf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbvhvhu.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2nhamdeal.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwktyww.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xidqwbdn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2iovmjhra.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2unszfjyb.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcquvgt.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkccwzq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2evswhzut.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwtkysv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2znasvnpo.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2okkgzphd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqskdhnq.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhrpwuu.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmekqpei.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2teasfzfv.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2emuyzild.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjxwfgn.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2oyaqegkw.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2akgsmpjt.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqzddir.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlrldfy.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbgukez.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbnedzw.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2owjyxnfh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wcaikirz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkkuula.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2iajqkhbo.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyinqcg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkzqjrr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2fctvffob.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnqoaoe.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuexpxa.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxwynwj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlcaaaw.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpidpzc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzhtofo.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rssbcuow.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwptfks.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2letanoik.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2skfhyatw.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tbonnapq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrezlta.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvcntfi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2josadfcn.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2slyltmnl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmqbdvs.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyudvyt.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhlbodb.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjuqakt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2teolucpm.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpeqqxw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2yilyovji.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqtqxfy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmecmcy.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2htdoicml.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjvgdow.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnexkyy.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyshdym.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbfylnc.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjvijwt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2trexfpzu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzxzhsj.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgeymii.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlvehra.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2utcauxil.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2pncdclyf.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdefjrq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmrspdy.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2azxvgtve.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2adrnhqcw.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmksazj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fzskvxgz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhrjfxy.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xdudlvyp.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2afunxwxn.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2moqakocl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgujelo.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rafmhowz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yyojcoep.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqpweaw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ffacmnma.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjpbkwo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmsfznw.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhobixz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwjnxko.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2crdwxekl.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2exccdjgh.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgusmzdt.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmojibeh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2exdjoobr.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqhwety.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hkibwwue.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2musvsggb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jmheaviq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qyluwunc.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqijxrk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ildqkvum.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcwagvl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sypcegco.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2avzntmgf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jtloonrb.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2babbwxdp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnjewjh.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfxytus.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pooolfpl.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmnjroa.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nktkwwie.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfiwzsqh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnjjaoy.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jtirsrhy.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yenezkbn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcvdvor.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wzasrnyb.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdcatiq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jxeurmhi.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmahsxk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzfpqqh.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2hjygzcxg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjttbks.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hmklmwtk.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2vypppcxn.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2oavhzjgj.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmwccjl.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqfnyiq.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmnzzfb.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hiljssgl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpnusvn.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyicvju.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2yamjkrod.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcojpsv.html


<!-- 参考信息 -->