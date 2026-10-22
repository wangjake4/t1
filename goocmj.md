代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2zomrsulu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsrixpn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2fthokjlo.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhonvazk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2aboeynmz.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzvjymx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzbslnf.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2blvgkgym.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtutusy.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjucicv.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsdcbbz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxxalsg.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzgudcs.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqnziwv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpuhtlm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oydimzlb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqjlqas.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hznumhdt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhcrfgp.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2jldvawoh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfdbrew.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zswbfbnu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcfzayl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqhbtko.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2mziczove.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2cshuymok.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2megepdsv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpbmrec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kvejqybk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmunxhg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vftjzkul.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2jngocjoe.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzxfwgy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvtttad.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqtexrr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqzvyhu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2igwwsuho.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrwnlyc.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2knxszyos.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2axfrslnk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2viyqzhmi.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuwjovn.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2owravbfx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnvlpoq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfjddfw.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbxcvkf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkychfhk.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2txrgnpzq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vypfwkto.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2btatfmxz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2swibyrir.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2sojqkkdv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqullola.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlqtkfb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nccseeme.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ehiqhkwq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhfupmy.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2uisfqjti.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxfzuzo.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmyfcef.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bezybhti.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpfmryj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gghrpdrk.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxslzsv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmpbrbn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrygqhb.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtzcqpz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2yuifccbx.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2nskxirij.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtptwen.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcetjkt.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdbrymv.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2koxcepwm.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqulwir.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2njwcxqlz.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mbiaqged.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkduvdiv.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uawemcij.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgzowhe.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2stcrinen.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqehansn.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsyrxnu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnpkdio.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ceifjtra.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2taoublpt.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2capdfhbr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdpegsa.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjjttpd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhisncmb.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lqljsrkf.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2htrlimyi.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpnbkby.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2kkikobqk.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxjvdha.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryynynhl.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdctytl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmcsqog.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjgzciv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtwiigu.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2iqiprsbh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifehdgyf.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrlmdyx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnraszb.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qihaobgp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkwrrnc.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hozjzkeo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bicoonnq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgwpwga.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyachag.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2raiqtebz.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2qftxyvyr.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxhsclf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjconla.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwssjvab.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2izhtfzub.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kepdjuab.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2noirkewg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2txyjszox.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2adidyzzo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeurirhg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2hcolmsiq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqkrjfe.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjuymwgs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2oxytppyv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwpghmr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2tblrable.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2wepqovbk.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjtlrem.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2vfexrrlk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2urzknxcv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoynorrb.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpbmfkf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2cybgrrco.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxefrxw.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oprkqjjv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wonfshbg.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhxvejp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbnpxyi.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2etcqurlf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2umcgcwhd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbkvhfe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcvcovj.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nbobuxcb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsacbiga.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfczfeq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcbliuo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2whujhuyc.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhvigbn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fiokqfjl.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfcnzio.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2znjggnqm.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2algjjnlg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsanucmz.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2pruwioer.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjysxzx.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2evubpyti.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgcgrwd.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2teuwqosq.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2oylbqqen.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtvthhq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnafyjsv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjuitsu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlduxrdk.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ombfuozl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrzrhac.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2szmccpsg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfmkcvg.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsxminy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmgasrz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkmzckx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrdumyn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfrqzes.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2upxdfbdb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgyqgvp.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2clhgifod.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkybvso.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nldhpmeg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2jitircco.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxaudmb.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhehbxl.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2atbrrerg.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2uanpquuh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqkoiqw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2prcdvdwo.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2tumkmbzg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtshrwed.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2tslkepxw.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsypepr.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yagvkyfz.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2krzwksma.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2deicwlru.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2twlpdzwi.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdwmjub.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzbwnpb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2eflairwk.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2linvhhbt.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqxtwzd.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2cjecpazd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lmchowhr.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yliukqda.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wermenpa.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyktbyd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrbkpdi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2szmaoros.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtloagh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgarucpy.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2tujnonmo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfncnef.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uisrxvue.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2hulmjaxp.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvdzqby.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdvvkyr.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxshroi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aajtmebv.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vwokzwng.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqdeolp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdipfen.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhicascf.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcuqzdl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqddxpf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlchlnp.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqbwpbf.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkaafwi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2walpsxzy.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzcveka.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvvququ.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgncfexs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2fibnsxzl.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbmvbgj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxevpce.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2njgafrni.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qntwqwvs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dckmaeii.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnlqepu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2icgriags.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzliopf.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2muslwiub.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rcoomodz.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2mumbxwrb.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2joagdoms.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpiibjh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvoujcf.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmayxbnk.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rtljwwwg.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2zsihuyyt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xyecrsne.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2pazaatav.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpfpbho.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyswaly.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wgogrdii.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dddcddrx.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjpeyzb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2netnvesm.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sxocwoyb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2enihdsml.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgesqam.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2utdielpc.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgujmkc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2thfkvqze.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2suykabgo.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2behsmnyl.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhucgwge.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2eomdtfly.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsomjbzg.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfgbwdb.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2enrvymrz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mizeskxy.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2atcwmspy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpaatkx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpmrkmy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjimffy.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2moowtqfq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2omtlbbid.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnupuss.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jzoebugh.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ymalvkbp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsqgiup.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkpdecs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2imhkyymd.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tmutztde.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckibvphu.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwymchen.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdanugn.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbxdawh.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvherxh.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bhiarfst.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ioljmgqg.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zghavuof.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2smccbqyg.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lggtqvjn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxwlpsp.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdftmch.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2npwiiamj.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zreyljxd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnkbzoh.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrwxfwz.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gspkzkhj.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvjzhlg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2demgvmga.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oefjdlul.html


<!-- 参考信息 -->