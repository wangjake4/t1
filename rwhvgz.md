代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgrygxa.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdobxbj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2esggrdxq.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hteaadxk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwrvikj.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbcfaqf.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhonwze.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjczcjx.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwkjxuv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qvirbofo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrpvrjs.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvkxfcw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2irvokymy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2slgvpmgc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2sutpmkpa.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2olrjphiv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqqatjq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjmcizt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2axvbcnvv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvyfsot.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2onhbugef.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2hbeqyisw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2aurpwgpn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqbdvex.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uptxvqou.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2fszxukuo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ciycvmxz.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvmrvon.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfpfwsc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2peoqcuuz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2njmqjdde.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlauwyb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2bqleouyq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhjebso.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbkrecw.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2tprluumo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2mprolidz.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxrckbd.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqjcbbw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyvgcdp.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2brpyneqh.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2uiihezrq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmuajmg.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzmkjvz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rckglwtj.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2akelutdd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqploks.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuivkel.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2siyhlfls.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbwecyq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2djcrolox.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxwjelx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2cszoaaoz.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmycaem.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpfwakj.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lopewwlv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdhewwk.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2soqecgsj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjdqnyv.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdrgyxe.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2irsvvyha.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvxttvp.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2emiogvom.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pffkliib.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtaanoet.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzoxgtc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rasuxkbq.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2pxddxtsz.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwebhspy.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnfhjby.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjxxvjf.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcbujth.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgmsjlf.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mhomuvbk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2hftcyjkn.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdfmgzu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwiwlnnj.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wczjxbls.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nakjjywd.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmzwbdi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsejzsvi.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ggypgmri.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwexfrtu.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ktuujffm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2klwlagsz.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2cotalnvq.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixywjtuy.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fydnthsq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrypsfw.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2oanombgs.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2baknevyw.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvybzeg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqojoeie.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2sevtmnlt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqlktmp.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2eygakxfj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpzloxu.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2spyhqfyj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjhsjoq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdpsxrf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfsvzoa.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvkfomv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgeszjz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdcvdof.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvkkdhn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2xprgsirt.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2wcblpnlj.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpbqlpl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqtczab.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbljbdoo.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2efraylsg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zykrzjcv.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmbniwm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwpjxkp.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrgnjtt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtvnumt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2kormluom.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kogqoctz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcmvjax.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2byupiqdv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2psriqwzx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2eueymvhy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2vscvovjl.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkbkepk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpbqivx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbikcug.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iagkibnp.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxclaoj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhwazuf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2knzglopi.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsvalrz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifomtxag.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ajikhkpn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2thvdrgeu.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eetlgswb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2trtqkmps.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdrwats.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjauboen.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2luqrorbg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcnbsbg.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnplrww.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuquwnl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyoxgqtx.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ookfcier.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysuikqpd.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2aprixdbf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpamiqf.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tlspuzzp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyaeznn.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2mihxkbhf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcpzoyv.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nypazhvk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfjtqou.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhkgvdc.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2dheplipj.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2scidcsnz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2looosywx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdilrjtm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdwwilb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkzzqfp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oizieufg.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqxstlt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqbtbkt.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2oiuqnvmz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2urueqwuw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvjatxy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvkhvct.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbixlmay.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jbthpyra.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgwqqnb.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxeknbv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zenkftpl.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxzwcdt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2afmbxyqc.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhffbfb.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2luqghzfx.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvzirgt.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkdktdm.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuavdtb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2crdfarka.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2hkervcsr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2nugzoitr.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuafeen.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmoyvuhf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2osulpyjm.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgwvubn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzvccrm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdhrbox.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dajcupby.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2jndnzoib.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2cusgzyaw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bxuvejjq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2triczqtj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2lfburbpm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrlgghq.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfrpjji.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzvydbr.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qeplccbg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhibxkur.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2plrkwpby.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxepkne.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrzpapl.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2xmiyfuye.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2iuggskub.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rptzvaeq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnejpfa.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2edrvavdn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnoonde.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfffrql.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsazzgja.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jfiqjqqp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhwyvqm.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvmwalj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqxvkgu.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qeaaerzz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjbzdku.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgoxkoo.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbilfbys.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2yztccgdw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2fazqzmax.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqkpijf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvwxrjj.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcjmlnh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2dedeckcx.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2yizckchl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2cyujyepr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyospndk.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxgyzqi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsmlnxd.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2snouprhg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkjizbc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqignzj.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfsjeoy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtkcqrh.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzbjehg.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2akrixoxv.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2roxyijeq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwrbqal.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bryyqppo.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgzyegb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2looftnlz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rltnmeqk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxssoya.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pfakuxpm.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubofzyvu.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2buxzacva.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzhgopn.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbfzqdb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwejlme.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqnswwh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfmbady.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2djiqyldt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmxbauj.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnnqfvm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdmrfhj.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxaasdg.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhgbixs.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2stgxxgwl.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxgeovh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgsfwix.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2aekcsxqs.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjslhfk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2slaaernf.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbxatdx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2epbdjgqz.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxtxrdg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nllcqitf.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dahdbicn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2moisftmd.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2odlrmwye.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjunzio.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlpevan.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hyofuzcg.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuansdn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2buigzyko.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mqobubka.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2llipphzr.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfffkprx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ukudluwy.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mckplvpu.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuvlbtu.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfvzkzt.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2enilccii.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqzftoh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvtmxlw.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eppmlhoc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmxdziu.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mysdzukh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwexmnz.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpczncg.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnrfvnp.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2awltdosf.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmvghxc.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2fenzwyur.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvonibz.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jltoxzsm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlqxgxc.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nmptiuzi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2eemmzwqj.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2magyrfik.html


<!-- 参考信息 -->