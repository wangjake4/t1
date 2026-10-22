代发 wailian999

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2idvqziki.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqrdkhb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvgwfvr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2urnvwpwa.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nooxohpb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnskotw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2reifgrnt.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2slouxfxc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2odxjwiwu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxicqrf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2uabvceiu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vwecalfq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2mewhpzid.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2hazizzbd.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuftyja.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xlokpagg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2jaczfpkc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvyhsrl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxnpgio.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2swtxkkfh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhxgjhc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqjwnfl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhoxwvra.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjpjqzx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2bqndsmfk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgaejjn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwffttc.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2urmxnvsf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ernualft.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzilnceb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kyevftht.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2veofcyjt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhihmfz.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2juzokywz.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2udsbvsln.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2nlprliku.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ffattcls.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bnaijytv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2suotamym.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxvgcfv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2joowzonf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuqoyvo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xophenpv.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2kmurnahu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxfndfz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2affqpuis.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcmqfmv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2epczmeku.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrvixcv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzviplh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwszxymj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ojohxniu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvudjqy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2wlabnwqs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tanddpqo.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2xfculmvi.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2zobmxpcl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2pihycvgq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lbposljl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2oeivnfal.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2inoywdad.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmckwgo.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvkknma.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2qatzzqhr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2brhdkjkk.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2roktxxhe.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwctleo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqodmaxj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjudpwt.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2zilnbvvp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jehckfxm.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtqucpg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2czluowum.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2pucgytfe.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqcivoe.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2mdyhtzzn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2sexdqcos.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbmpnmq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uofiryze.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbaywzg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttimkdmg.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2piwgdbaw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyravhc.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzsddrv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwwzhla.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2kdeqrhkp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzsopqq.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ceppspxn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2nivwhodj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvipmxb.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmgcqqa.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tkeleraz.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2aojsopzk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ipctwvfl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2txcmqbid.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2yymknhsi.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeoqnyrs.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nlymrnrr.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxkthkd.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqoguvn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fipjydtz.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcunefj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2xhurikjf.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrvdbox.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrvvbte.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2khfppjql.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eaivkoqu.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bxazkpje.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2djqiugjg.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2htlhwchf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdplbluh.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvdyzus.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwrlhql.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ecapopjl.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmudlvry.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkgnjrc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2bblkbtgz.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2upepvkfb.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fchyhtwb.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pibqwspk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sycxofvj.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ergltfae.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vewhenww.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lvduhwjd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2shaflvxd.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2uryfucug.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2btyiitmp.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ptixojmd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkynmyed.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2neqrhkeb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwvkxkl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ennitbew.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2onyavwcv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2aoidowlo.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpzuyuu.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrgjpiz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhldcnk.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjjwytp.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2umzgyldj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uprutobv.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nhydbjsj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2omyvympn.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrnpknw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsudyvib.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrazjed.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuoqohe.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkbqmeu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2wlexihtw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pknrqzvd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwenbur.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieddlxhu.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsoxxzf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmigunk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbhvxwg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrmvehj.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2roegyksy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnomlmn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxzwoma.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2raxirflu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuyeualb.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tktyvtpf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2hoygovzl.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtsgtrg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvdsvak.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eokztyhh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ketloccf.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2geluwmel.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2anspvnvt.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ftoemgzb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2rerogopx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hehduxjr.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gouxmppy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzffudr.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rrexhsqv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hztnijff.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxwevss.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdhkmsl.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhinalo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqituxpj.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fehpyhhs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvezsty.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2iongzesh.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnkpjlu.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcqtgza.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2liqcbueb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2uutwuutc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2optbrfhk.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cldxrhjv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2isefeulr.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2alyckbhg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqodcre.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyxntaf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpxchui.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvirktm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwsjxux.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqmymgw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2obyjefbh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlkjbcb.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2emlnuvzz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2easjtxjc.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2znhoggch.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2eholbimo.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2phhbiidn.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbprbtth.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kwawanrb.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfsajhy.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzibsac.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyrqswe.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2spmiizue.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcobxmg.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsmqjmg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2insolkxk.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2axulfdqz.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rshwufhh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlltlzy.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrjfxgy.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwenhop.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwkhsep.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kycteyhk.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvuihjf.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2brgpgofa.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ekirmgxf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzzduvk.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjiayzi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wquoxypv.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnutfik.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2asnszgms.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2prqratmn.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqrmvqn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhaorrba.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfufnfr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hynwbrwn.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnjdrff.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cwasrohc.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2meyzahgc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2btmaiizu.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbeznnw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2taoldczy.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dpunmgga.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfmoupd.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmsnovg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bljomizc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdhkosy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jryydfif.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzhbbxl.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tofplxyk.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgelron.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwbpfmv.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbcxdqa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuudtej.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqvrymg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbbmguw.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhapkgpk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2eorxnmmj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwohxrn.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2otvryrvh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2afvoakgu.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtrqyca.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzklvcaw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pinejsst.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uutgunrm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzjegiq.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2renknhrw.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2juqkvivh.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2jlujdrln.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2tznedhrk.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfiycncu.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lnitfoqc.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2cokiywuu.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwqtqch.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2waexqkog.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlkcvwr.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2glyntxja.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ciftjkce.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzzvoyl.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qklcctup.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2auvldzbd.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2viioqgtn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrqlwuq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xodzspqi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjydkvs.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2opuylemk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2edkgcsgx.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2kskamlip.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwpgxhb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsgrhnv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2euafznql.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2medwurub.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2gevlxyzr.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwbmxxa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ltaqpojk.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnfujtl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmkkgdg.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vfezrzsu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbqtgzc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2epizcwdz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bhklyekx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xckuxygo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnkslhp.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzrbywq.html


<!-- 参考信息 -->