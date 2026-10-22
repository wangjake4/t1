代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tscnyjxz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2qglekdus.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zudjznau.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2voxhlate.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxzgtms.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfqpbem.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxnrvno.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2diaqtlqr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbqoujb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyssmald.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2fojhohfa.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqcynkn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2unzucedc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrmhfio.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjwhaqa.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bnugrefk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2zarmsqrp.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2isvvhaqb.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcwyjvk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjqlswt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ortrenxf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnjixif.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2grkptaje.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtmqybx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjpobgr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqxczwh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvzvnim.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2buahqqua.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwrkwpo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbmkdgn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbbuatc.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rnselbsn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2bvefvgqk.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcsqzuz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2serjhctf.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nuubttlz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmoirgm.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcrnaav.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmcuicx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbuvmyk.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfrpsdl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gjiwqlre.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpmgvav.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aautozld.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdlxggb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2puwxjlih.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwmbjcx.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtqilbd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzlfdqa.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlvbpuz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2awuiyrxl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxfwsta.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2awbjeaow.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2izoakzap.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxagypph.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2jevuexqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsntpir.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2kecdlwnt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuakypt.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyrmvlr.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrkifkx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnvsxgv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kgeyyeod.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsoapkr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2dyskgqle.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyokwwqt.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2lodkworx.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfuzltw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2prkemryw.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2yvotzfet.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbdiksi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2uetgbkom.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2yofyuqbq.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2sylrhuyh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mimtekff.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2spzmdzku.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2scjiawog.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2devqpdlc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzpsqlk.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2oywuljud.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2scnxgltj.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrsnclf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvquqpqj.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvgjbuv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqhxzko.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qldyjaib.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fallbrrc.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtzhlpo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tunvouzj.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2yogapxro.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyraotm.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2khmcgawy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2crpjasnq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2rmauytsp.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2lisfmtwa.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2btjqgive.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbzrlwd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqsgygu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rggvcsrh.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2aepykmhd.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hveudkxn.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgazlkp.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2glquhjlj.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnoqerm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxqdbjg.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2slnzlnop.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvuyvvd.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fhztnlcd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqguohd.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2clfyjgmm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqcsxjx.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhtbgez.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jomuzcqm.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhjugtw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrnbbxx.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2yxglzsjz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjpjndz.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2afiaioro.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjywmrh.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkjvhqu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsnxycr.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2udtsznno.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qavowiqv.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwebtlym.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrtdhes.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2celnwudj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2knhvgjdr.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zeukagow.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xouzaaho.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vivsksgt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjsxsxk.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ekaezniw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlmpxez.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aysgdezw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddflqfxf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfofqmp.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxkowll.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjcvfdm.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgaecft.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2upzirvwz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmwuugn.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkeiokr.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tinipmoc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2piokatxx.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tixqiego.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjdvqjm.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmyypul.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2alepjpem.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsqnnbh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfyresk.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2camppjyd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxmsaba.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2prkgcyaw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2aryvkzne.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgiygvpv.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2npxnsxpz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdkcdil.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2rnstyfmq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgklfsti.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhhpugb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2miapkuyh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvjjsil.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjdfqrd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2aloyxcjo.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2siozdhub.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgborsul.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wzagwctv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vebxofvx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2usjmqsey.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvetxwpc.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuhlfim.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxutzbol.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkhkczl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2onkawniq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmaeohl.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxgxnmt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rytkbzci.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zabgefco.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqdxufx.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nqaddmna.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfadxztl.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2bddqgwdt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqvayru.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hxajftox.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtbpfxv.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2unadqilu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2rouzkbii.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gokcriye.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixywdylq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqvdbao.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2eocnubxv.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzjssbs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxkyhck.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pikjkzku.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfrrepe.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2itslmitl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxpcahb.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgjyrer.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzlypyy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeypufpi.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqgnicb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cytgbcgw.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgfpwvo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpdakpr.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2invntemj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfuejpm.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuksvhl.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwaitlko.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fouicjlp.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2uiidrpfz.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gvejripx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxnuvwh.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpglmed.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpihejg.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2qtaevyyg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhegehi.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpiurbts.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjxagoj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2fwumhojh.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2adgkoqzn.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2itjbpcou.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vhppwkcb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmqxlzy.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzrakai.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlflajf.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ixeqblpv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lfewdpab.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kelawxen.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2nloxasob.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzfgfii.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yophokzx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xdurriux.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2srtmslkp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugischvg.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxlpigf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2pitittkc.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfbkgpf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2juuqtmao.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2pjprdnwg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2sembcaiw.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkuhmlu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dneqelnb.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwzxydh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgopnlb.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wutpuzma.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2unbrdklx.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmefomq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iudeeuvr.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2vmixxonv.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymelcbrm.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbhsbya.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2exlxflzl.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2seoqdxjo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2bdukjznv.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gelhppfr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvobngli.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtttwnwn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfnbtcp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2buubrqis.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2shswsyfr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsjdawp.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2kndmparz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fplggkuu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfmegek.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzggiai.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyxwoep.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyiplrg.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2rpshmlte.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ygahagtu.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2mghkgeow.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgbpjfm.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jzviusce.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2nftormtm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2svnbqbat.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2uomnpprg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhsokid.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2muxumcpp.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2foezrppa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrqyotd.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgrmepf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqejknu.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gzofzlyl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2avlviumo.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cycjihfr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pzerublb.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtwiqcz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tnortcdt.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2phmvmwzq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dxatjogz.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmaukjew.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nadzekbm.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyuwbwjp.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtmngwc.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2frefpfwu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmxlbxu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2idnjoslw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ycoctymf.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xucscfai.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjcdvay.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgrbvjm.html


<!-- 参考信息 -->