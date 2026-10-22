代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2tswhmkkz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgxgoav.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnnyfbt.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnayapq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxmvwqn.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rgojuqnj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kucshwfm.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uidpaxat.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnwvgyb.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqdfdlu.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdaokvz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2psytzpky.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2awgokstw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfwpqdo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpimkjy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqufhcm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2fdffnipv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mvykhfwg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjlvcqm.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2abwnmfcy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjnlnnr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpiexpi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxpfqpl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwlwncc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2udiwqoyp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjjquys.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2pttdgsaw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcolxpu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxiurne.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2uflersun.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmccdvt.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2vcaqqvyf.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvbwclb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzacrox.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2grgtwofb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2gskakuuk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhznkxb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbtpurr.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjxnlyq.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2bsghcbxo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrmmxxi.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyeiont.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2erfydqsv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcrxwru.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbknlynp.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwiqwrf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mggowdor.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbutfkz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2afixnsgg.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkwifsm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmnicsr.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2hybzgadd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqvgeoo.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhdbdoc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjhddng.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcijpww.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcozrot.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hiusjdcq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzrisvd.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrvnbug.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrfzbsw.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvcaxav.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqypnwa.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2kpztppwu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsbwifi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2itlzglkp.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsrkfmp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgsrznx.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2yczlhykn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrqnyyo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxfjpmf.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2icavyapq.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cihprlln.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpltvvt.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2izkkuudn.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzbkarx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwnfrmt.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnugbad.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2wljirhqw.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzbekfw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2lacdxwqi.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mdozzceh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljswgxar.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qtojbxvk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvwhoju.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2avtzubid.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2akkwcxlr.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmjffuw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlsxvwv.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zoarxwde.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgiejvwl.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfbtggt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2giupffyz.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvzfvat.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2paknoxvh.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlegpqw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2inobimcz.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fopajbou.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uywvyzbz.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xybexnlm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxuqqfn.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqpthwd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcjvutp.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2avrbihfp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcloexco.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkcxrmj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fafurclv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2vxosbwho.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtxeckz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxoneiz.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2zckyyhmk.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2skxenchg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgwpplt.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uboqwxyg.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vvusxzqk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gclxnqsl.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xhemjxuh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmypguvw.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwnaksj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aupqrqle.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkvjrcj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkvukcg.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvagndir.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlotafr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2torjddcn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuonshi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ornnxkda.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2goxaisnk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgivwma.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2vcttjyqq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzaugim.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlbsemu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2avibpbtu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hobblmkk.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkowxnc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2fiansyxw.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rqackcty.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxfmdai.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcbgwyo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fszcoizz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgaeipf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2prdklgdp.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rqddnjbu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2eabttths.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dljtraot.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2lroxbpid.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2eynrykyi.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxuqsfi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zulwlnnp.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2oybcipxl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2stilxhui.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ypckzssl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2shvsczwy.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2khoetnez.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sisyadae.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjidvkp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2elndghuu.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2czqioday.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbecamjn.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzfyxxq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2emvfkpoq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zewglpib.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqyyyss.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2odfjtmod.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2urcllkob.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbslzhi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtglefik.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2zavwegfv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsnzpgc.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2upysdogt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2jiifhyms.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uofzxmvk.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2emqfosks.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlitnwvx.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2qbakbnhu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvonykw.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2usthvdsg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkbhwrf.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxykwtd.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvukypqh.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqkrfmy.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2umcopaeb.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrvfuhi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2almepwic.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdwltes.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2vepfcgod.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2rbatzawc.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkizyojj.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzdtpvz.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvodben.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqmymky.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2sqigedpo.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwkoalb.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2evbierkn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2vvovhjzk.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzplimk.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxhqzqv.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnmqdiq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxhtfre.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qflevrle.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2cprstdcd.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qlukvkgl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvigrwtn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2miepretz.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mbimjkjn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjngpgbu.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2frqeszup.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2wiubwesh.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mlijujqn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvlqjxr.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lruhhupp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrwhrtp.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2poecxkyk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2otazllqv.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdvfces.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2upumfpcr.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2egfpprov.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zssmajvx.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kxukkumw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpnhvjj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwnimeb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxvwsje.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfpedau.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2abawbmfc.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgtqfga.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwqdamp.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbnhzws.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsdcuvi.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzrllyp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2nbggmpqd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2knxdewuw.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kyektcuh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jbixpcib.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2uszwnedy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztijdviv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lqostujx.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tskeruza.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhglyiw.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2babdlrdx.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2cikqxltd.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjiobcx.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2eyavdxlm.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyrgcun.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnyidrn.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdmqjrx.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvxrjiy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqitarvh.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gzknbzbq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkoreej.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyucjfe.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hozhybxw.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tcamabpj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yomadyjw.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2idrktfrv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hagdunfj.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oygzmyfi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvxdyxw.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2puorvubv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rvplyviy.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzscwbq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dpustnpl.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxymxtw.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqkvgrv.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxiwpokv.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxqzqsk.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2danvbmsi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzfugsl.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvfdtjr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrnrkkq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnqsihx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fisiwdwi.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2olngnhhv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wcatymdq.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2poeocagi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbpnmsg.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2uthovmyj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zatvqnes.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qchkphbu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvsskdy.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2naqmvhbf.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ytysemea.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2bltoaefs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sppryafx.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2brxpybkt.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrlkioy.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqiwqcx.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfkldjs.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxdntsy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyvncsu.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tftnqkjf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcutloih.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2znlyvaue.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgebcox.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2twcxqrvc.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfccwpjd.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xhixtfxg.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dedyxrxd.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlreecd.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrhhvsb.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzbkaip.html


<!-- 参考信息 -->