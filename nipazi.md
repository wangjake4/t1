代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qinlusws.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrhvkst.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kciqgftn.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2tytdtntj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2jecpyhkh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zytzoxzr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2spvqvefk.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2preypnwi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2yymhxasb.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcuijrz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtvmzse.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkzqlfo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2qetzamfz.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oukqzwfq.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvidsve.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2myawczyi.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsnfxfo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bupsactj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2znqomoap.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpdprrx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2fyixwokx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2poxrsdvx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuhntif.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2msxezmde.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhxovsy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2snhbahtk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlxnpij.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjwpahr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2neqqxlle.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgonmog.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsonyfjv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzayvqe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stbisnid.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxkifbl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcnwpha.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2xaghwrar.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2elfclygg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2fdonlslp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbbunof.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpmxgkp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2xggnklrc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcnnnjt.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlfbyrf.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2araxfnjh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2udlvasub.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcsmfrj.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnregvl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlueiecu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqegoub.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjaenec.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2knefvssh.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2svqjwbyu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2usnrngeb.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2sojeonvp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fenddwdp.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2byjhlsra.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgroupaw.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmgwzny.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2othwkqaw.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpnxkih.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlrvtys.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2npviihlu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2romqsfxv.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjifwfz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2khiyccxb.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjfnmip.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mbauhnec.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdfxhoy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2snqalelj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbhszgz.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2thxtakzn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tukfybrj.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrujcokr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2tocgmckt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcitosmj.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgvswnd.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhnqgnu.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlutdqj.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgoouly.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sktjmtfa.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmzkouj.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpwpkry.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2bihhkhek.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vofyavjp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2aezcuvyo.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuplgqz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vebbwlxd.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2amgzzeyg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2iojhohju.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2skqvmlhz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2penvxupa.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmglbtw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2opyvfvfk.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqfzfoo.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rogefyks.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbfqrhj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2qxveeeou.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjaokco.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwstqcm.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqgatfv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbyhgqm.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlmrglj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgvjnqq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnosnah.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2moqtmnkk.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyketgp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyylnxd.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxcihei.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2niaowsos.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yjajfldq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2foifrsue.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfwvybh.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hknbyiwm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjytwwx.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxvbzmd.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnvrmng.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgdfhyg.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvcimzm.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tucrkdqc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpccbong.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zpaheflk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlogytv.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpggwrb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vplgapmy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2orcdubim.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iymgxguu.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2planwldh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ietjaimk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcnqrcc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdlskkx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2hskgshki.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmuthfd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2emayzgex.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqlteex.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsihlbc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrvstrj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdbzspa.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgklmnj.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzktmdy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2atuuyeoc.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpmuowc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvmkuxo.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgcefqy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yddvmxhn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vzptgjav.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjrhpph.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2msspimpy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqycgllx.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cqezuame.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2brhhylcq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2smdqfzxu.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2dfeaoxtb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnaazqxh.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qaokfihb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2uszdofsq.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jlklbqzq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxymnai.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2icbshdfc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnapnjsl.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cksqutnd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2argeisux.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2shnciump.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2toaphxal.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2imekjwbg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugztbhrf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2sfaafrvz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzipsps.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qalqykun.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmnygfu.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mizqipqa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hffgjtvd.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2newnzhcz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxbzfod.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hdinaomr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdeixzb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tluaeirb.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjcehcj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrvuier.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2expzubhv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2assfslgw.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxjsgww.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2efmanqhb.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eobwjrbc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcljmdwq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2slutowqr.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2swsbnxdt.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bpixrztp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2twlzyfgd.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2pobcusnv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2uophcpkn.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2wohcists.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fonymhcn.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkfuwen.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhyvnfm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzzvpsi.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhwtdqp.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2owlmymnq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lczcmdsy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnvkuvv.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbgnhtw.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqhskzk.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwedyzn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwlabwj.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jykjusgl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrawnmd.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfyqccx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zourctup.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2vdibwmmr.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwmsmuq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfukybt.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2qxemnxdb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrgwnjr.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrrvhzm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwzevvm.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2idaddizc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qfybsyqs.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrafmdd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxurymtf.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rckjbwat.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lamtwvft.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuiczkc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmncxkm.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2olmkztmj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nywlprdr.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2uodwccph.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lftywuml.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zafcvssc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2lceggapj.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2egkwucel.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfwosff.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdtrcdn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxrsjfx.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2igumlcwe.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvrmbqd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yriynapz.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jiiazdqq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2idsicmkq.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2pqytqafb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwvigxf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nygitfjq.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2drnmfkwr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nritvmnf.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsndhay.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrfobcn.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2jizmwgln.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qbaezdze.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnuihcka.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vegjxqyi.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2czfxqiut.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2towgntmj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaicyod.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fnteplqm.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjbycjx.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2blppjmrk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2riwqfdsb.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzgydzt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cxumwdic.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmnaion.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfkrfla.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yoapahfg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xyyjabjy.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lynmzbpf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2suamgung.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2twairdpa.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2catmnzeh.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2abdypsrr.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjuvfuc.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2swqentnh.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsbmeph.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nbymitvk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2annzqqor.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gnchmmyq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmcpkdr.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtfeyij.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjuopxn.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yborbdpd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pvywklwn.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnbumik.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2weshknyk.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2tihjszaf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ahezazxc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrupyyn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwyvurl.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pyupkgic.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqezrrsf.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2glqydfun.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2laqmqqld.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwbrpzn.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlaozfc.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jmizosqn.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkesaay.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yiknwehx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2argnwfaf.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rvojlahe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwpcsxv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2sabrbyoc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aggxpebo.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fibyifxw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxeqnbax.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2jecpxxeg.html


<!-- 参考信息 -->