代发 wailian999

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2blhntptf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2daxkpcjy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrllzdw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbxsedb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbpvxkq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2hramxbcq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjehdnuw.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2oeujyyfv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrsdeua.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2epnnjvtf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbxdxmi.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pczxnvll.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2xsblqfst.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2djpcqznu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcbsmzm.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqyvfaf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjtaryr.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdaquncp.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcaehsm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqmyqdd.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrwkcsd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcdyxuy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lchhrqdl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nazvohdp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2qronwfhu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxnyyto.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2uaefijoh.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwgbhjj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkomlnec.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2stmoyxwu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2fiidjxew.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqldzzr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2zlteptmj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2slsbiynz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsiknkd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2yyviugzg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qroesxhy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmldzaa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gauvmgcc.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwhquej.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjzblvr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ramanaps.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2gkypsnnb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwhnthp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrtbttn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtunsquy.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfxcuil.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnljfih.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2djxvqyil.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrvubkp.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcyyksj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxifqueq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfgakai.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhitxnp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqxkovm.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hztxaarg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2psuepxkf.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvcfftj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfgytuw.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2avpzhnox.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjrzpvg.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2bqiyqbps.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkysqrhx.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2shhmhtag.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhnlyby.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2blmyiokz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdayjfu.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vjinpugu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnktkyu.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdaxorg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqidtud.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2avrrpguc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbfgpqu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnoulua.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2sblaqyoz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2eymtidug.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrapxvzr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwpobri.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqytnqy.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmermgi.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ioitokwi.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjwbqxd.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wparlxcz.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tybtzubw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdofonq.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zidlszrw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaxkode.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wccnilbh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjucnbtu.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jekugapw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fakwvsgs.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2voexbjbg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2btcevwqa.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjplafy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgjfmut.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfvdtwh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsxyfsw.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsnscdv.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxhtjdc.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvkrgcm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2rykgpxjg.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2isfhkkdu.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcltcyqu.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcbaeqc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2myvlpibk.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vcosygia.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwodjqfn.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcfkilu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbijjvz.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2encbhcnp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyjbfmg.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtemdby.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueliquex.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ybomfkdp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnkvrpe.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2facfwxoz.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsgtccf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnggqlid.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2llmnjzre.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlhsvlk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2cfarzipm.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqytdcnp.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jbafhmfv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwpxzrh.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqaujsv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdbrwcf.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnpllgy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2byurnsug.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozeatcgf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqtflii.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mezfkasx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vbszkqth.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocybnyzj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrsdryo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2erwljyeu.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwargte.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfpkgjm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2gpulrndz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhqtcht.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqeuqic.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ppajzguq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgdfxol.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fglzoupw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmiheicv.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgabuto.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkurcax.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpzsqma.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fabsmmwh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwtewfq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xygejdwx.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpqtsxb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlotpcpk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sigklbyj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2owyngcez.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbgvhdh.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2izhrynse.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2idqhudls.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbqnmho.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wptkkdxt.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjenpwa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhgygpw.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2etqhhriw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbiyyaqt.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwleeht.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ltszwfjx.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnplgma.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkzsygi.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqwrjwr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2onuzlelq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2opsksyoj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsvpyqt.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfzexob.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpjtjfw.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zvinecba.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqqurgu.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2txdavxej.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnrscjx.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hsghfgqy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhwbfnd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxwstyp.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xaffjpkx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhannxc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ketahakc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqrtapz.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wbejrlkt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhnkfls.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlbfpzy.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwsmgcl.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mehcyexq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjoiemd.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iexhrcir.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdorigz.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2oonciqbn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyskiyu.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2idjfmzqy.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwqegdf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rutjhshs.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdzivor.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2scfcpttj.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2gbshpvzp.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrxmeer.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rgugfwqh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqhamfu.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuiilow.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ettvwdfh.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2eorgzsad.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnsdcym.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2olhcwsxh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2tsukobrj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdyynpk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwrnamy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2zppfchno.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxkbhay.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2jepoftwq.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2bkalyike.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2opwqdtuj.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2acibimqr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpxugcq.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lkoeplet.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbabvvn.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhxxafw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2alfbhvux.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yidysyta.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsejcup.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvcqecy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwuuymv.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmufiup.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kihkfzub.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrcvadi.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtyxomj.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2seaabwij.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gawehgjv.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgehity.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2tmijdfqo.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rukdrqta.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2odidbaci.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzwgcju.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbuvydn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2osoxmhcm.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgthuse.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzhkaat.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2eivzjtum.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2crxytffc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tplwfrnh.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxrojij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqklcqt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwsstco.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgwwtko.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vmozwvfq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2orjzehmf.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2urfqkdhm.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtmvtij.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmiysqe.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpbusim.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2coznluoi.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2czwlzthz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyyzmjgk.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpllqtm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxndoko.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrzugfy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xjaysujz.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcwoltk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zueeyocz.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2umwjpbdw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2enskprzj.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjxksvm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2awfiujhc.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qoktylua.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcnddxq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yroxldco.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2avkozisa.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsavovxj.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrgidrf.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fyurlwhl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfrxtzj.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2apmmyfxd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2htllcdlz.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vatppmvm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvgvmwm.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmuswag.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkbvejj.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbfxcla.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2grgktupy.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ibslgmlo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qphcvuiw.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqptmdo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcattfw.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyefkby.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpezlwmc.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2gopwmgsu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmbxkru.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfzdrad.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnofpmt.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsbpkvy.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xoulgbxk.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyalsau.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zaopooge.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uklukqlc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tahukbbs.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2noqitksq.html


<!-- 参考信息 -->