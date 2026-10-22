代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnnekuu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqxizuz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lcithvez.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjbpimg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2hckcsekh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2axwosbzt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2lifhtjli.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmbuipd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmmbnhn.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckafmqyu.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hduafyin.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjymykl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhvkfqg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2etzyekpk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxlrpdz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2fygsvnxz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyxujjv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxxvxjz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnoqftcx.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2mupbhhdd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2kooezzsn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2clcugxxv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2awtnpywt.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyxjsfh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2sjadujdd.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2njirwbrz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2phnzllhy.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytarqifz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2uggcpela.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrfjiax.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxvlwwy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpikiku.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxdniff.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyzljat.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2otygdqeb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpywfyrz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsbyfge.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dxagjomt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2klziswir.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrqxnnw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvoaozsv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyndqgur.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2eczqldae.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnidixxn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2kvuxjtzz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2yymjjons.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2zspqzptt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2vgoeqecb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iruuauqv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2znwanbkt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkgwhtm.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rciwmaiz.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2abnwzstp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2numoemqs.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdrkvmx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2xftwhtjf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmqxkwv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktaoniem.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ghclpwoo.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrtkkqx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2navhwdcb.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmbmcaz.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2asevcigu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpitwott.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2shlrgaby.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlsscyt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjujbkn.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2knkhocdo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2uioablqy.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzrcgvv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pliftavb.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2xudkhjic.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpxpppm.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2rllqcgdm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhjfrco.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mzeqyrik.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2usugupeb.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbnaqmx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjyncug.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzthioj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjkcyhw.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2znuapsao.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsrzhhg.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2gajbctny.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2talwojuc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjophqq.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcsnyni.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrqqfsd.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2yysstytg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2gelydrcj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjnxybu.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjdltam.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2slckkubs.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zjltnatt.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnakodc.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgczxnn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kizsdjuj.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqdhsvg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkcqqnd.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqlmcze.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2baskzbyn.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwvzxcz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovumfqbc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bufzwpys.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2syvhphqv.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuhflks.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2neyelbik.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2byfxoags.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmiedsu.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ztodlkgr.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcnxzrx.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxqzles.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2dijcemdf.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxlvjjj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgfyqaf.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2yedkcwfr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2asvjzhoi.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gwoynibz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbsgscj.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2szlezuwq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwlgjmp.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tivzppmk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2oowjcztq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2itfrwafy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qryyapug.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mrteioub.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxncywsw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwxlugj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqecxcc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqwpzzx.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdpthtq.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2wymzsvnh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyvaizm.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2naifenca.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2njcypcml.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2esshbkus.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dcytrwyy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlizrylk.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hegwspgb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfjikvf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfiqzsk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2udnhoefr.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2cakbewrw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2wstwrgku.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wifejrxc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnlbzoj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2inlddtrj.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2javmbrip.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2tajpjuhh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2noueqdlk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jluhhojs.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpobios.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyvpgzb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzilkyt.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnsrldv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2idevvgpb.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nchwctnt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqwwpjp.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2msnxjxfd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqskpiwb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgrmjry.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsmeuzb.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgbydhc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2cambudts.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2euwraxlh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxisfgsi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrvthgw.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fcundoln.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxwucut.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hjavzrsc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzlkoqt.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lflnbpno.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2canyxozk.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrextuj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfgrrbx.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yfelqaua.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nnozijrk.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwunsle.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2uinhiutn.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpgmfbt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdyrtub.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vguzachd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyxlqyq.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lutdiqhh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2phmhmmtv.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fcokeiwx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2msibkadp.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2kdknxmph.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrurzdqw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bdywgdiu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2vlapkbab.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmogauff.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dtynuqtu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kikqixcf.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmhfzrr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vonhtyav.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gnatttyb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2rbapziqp.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2oyspprdv.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvurmvoe.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tbanwbyq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgiycfi.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2esmpvaqe.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoewpcmf.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbqdhrs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyihfifk.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2fsepmloc.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2clxyhmve.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2igzaalfo.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxmnjto.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2gbskmtkg.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vurusepd.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iciczque.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpegibx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2vnitqtke.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxoucmi.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yudgnkdg.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2avjajcom.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbuqmpu.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lukiwzsc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2tsauzlph.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qklhwtgp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxvjmyk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmwpwft.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsgrfvm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvjrzjp.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwcabcd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2etnxiteu.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lafegvld.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2suojlnrd.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwayfrz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2zuozkrbc.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2zpznkunb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2deeivqdt.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zgflqdxy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzfwpnl.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqygzlh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2klrbjowg.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ppazprzm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvuqkos.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2igtzbwgc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiomzdrm.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2bowszicr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2tktbyuct.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnsgnzq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvzfetg.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwdylyl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2apvkcidg.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwpkimu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2elrwbtde.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnhukur.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfiflzh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzhndch.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2glxziizj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqjbrgz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgrblvp.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vekulsrx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fewsqzjq.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuenyzv.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2cmftuoyu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2nehakyts.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2hhosbdmp.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvroryi.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyrhghq.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmfdgsv.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kaphuudf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2aalhhauk.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2nibvaujh.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbzjune.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eunqgesv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzckobrf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gaiapybr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhudebc.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fayqzfez.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ekotpvju.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxcyhwb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kejsiqhf.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ezirgyoc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2loijbgtd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2eepxgrka.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkyxyib.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjnfnyu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqehoff.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2chqbncea.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2itieyfme.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mekwhbqa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ciamsztk.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eteenlcx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2itmdoiur.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2eiaqgtre.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbinrgc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ubehaoss.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhtunry.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvwarsb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dmchxwcp.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwmuqcg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xngkejgn.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tnagrgep.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2exgfsdjs.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrzizcm.html


<!-- 参考信息 -->