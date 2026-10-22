代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrdohyb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ippawqln.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iyshgiow.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2vybppiec.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzrosso.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nukqrjhg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzixnrza.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzmdcug.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wocbnmvb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gymndsbe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2iqajhvii.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2whwfsbqq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2dedlymeh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fphdolup.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2awlutnly.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nixwtxpm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2esemfgfb.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqcykgw.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrerdjo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mughsbmk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2lictpqnv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlbowqe.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2khrciytt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2nawrmrlb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmoyffo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjktdpz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2czlkcepy.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmtbthm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2pspwvtbz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjhoevz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxsoqoe.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpwcrkr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrycwye.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwpiqmg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqgjqrp.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2acgyflnz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdechvfu.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdburmy.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnpjoyo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdriivi.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzelezd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxrltvo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqscosp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oltpcxug.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzrjfsd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqgqncj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dyetjkad.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2mscqvlqe.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbymnqi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xarrntio.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrytovx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjbeoro.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2heggiyom.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2mpolqsck.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfplavjc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2eojkndsr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyvmtgc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2barvyplq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrxqonx.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2igqnhwzu.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsfvnja.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2fnssnalb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lbllchop.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlefnkh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ztssrkbd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rarojzkv.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2azxuifai.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2uptrssie.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuegamm.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwfuodq.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2wijdgwic.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwmrzoy.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2edobouyk.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxkeayr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrfmqot.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnnwyla.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzrevjn.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2nztzqtxy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pixjqszr.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2atobpuoj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqjrzsq.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgvfufi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmkbrsw.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfbsebm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfampar.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnspxpt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2avapaxqa.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wytquexr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvawyre.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsarfnv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrqddcl.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2oyikztxj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2nxiewgrg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2rrahsbvw.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzkhynn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2iduroupp.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymazuork.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdseviu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhxjpfk.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyokwhp.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrluaqc.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpkpbex.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycogsutu.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xibpaqsf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2epfasrxj.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqyaocg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmtitlh.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2usduosxj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgszopq.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xqohrpbm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcehrto.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bottmdnw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsklhyzb.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qbudleyz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pejwujbq.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2orgeqtdu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzivndml.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2awdfrmbc.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2scrbsmha.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcjxhja.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxogzxf.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2eeijwrij.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhizjvka.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbuwizt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2igldybkh.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hxooafys.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kukexnqi.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2amgsvqcb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxfebde.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vanxbvye.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcvcqys.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuapiyv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkteibw.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2omycvvhi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlqttrz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2bduwjbjw.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxuifwv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyoeyiv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkfjmhf.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbmocrl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2bbiongfa.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qraqwvtp.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gouwcsec.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jedwdmko.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxncoeb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnussmqg.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hfufhqhl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxkzheb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovuidhab.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbxcscy.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjhsadk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuqezfu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2suuzblhl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2rougtlrj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbrpfyn.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2emprxlec.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2akseqbyy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ygizffow.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2obuvirmm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bdelsfgp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2imgfyuag.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2sktzibxb.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zshqfvtw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyibvdae.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2whqcxaqk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhymcae.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xjufkrhz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkenfro.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkwzecr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyypyvb.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xftwpctu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrxmtgy.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nflzixlv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfnkijv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltimqgbc.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2esskcezc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcyrpzr.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2meguhmtx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2aisphkmx.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2noemnytg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyhnlag.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjjvidc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbzmsxj.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzxckjk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmnozis.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpzqdtm.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcfkril.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zpofjsyt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpbohmg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vylskmaw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2crmawlyj.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnflgxd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpeqlml.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ddggpfzb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmikrup.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2wxiqnmhs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfpvtbs.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2psxwomdc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfknakd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmttmkb.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfrwiuk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tokdsjvj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgdmqcs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxbedok.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmhbfts.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2nigdoyzs.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eucxvzwc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmagxbcb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ednpcshb.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpwppvx.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2agxtakel.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2twgahwjz.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2irkzneax.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqoxivx.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2wizdxseg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2atuccftr.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlzkoim.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2odgsmylt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgmehrr.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2erxorvak.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aybuhkgc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxjpsip.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2newczpxn.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2crgfqvij.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lidegzhl.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwuvsyd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2itdthhrb.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sybkgwat.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2xfglibub.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbmtwnf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmflutkd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ltweggil.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkvupkq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfqzwme.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgwfuzv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2irwztttm.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2prxcwlxw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsemloo.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2japzhutp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2naepylms.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmhszeu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcszyjh.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnvbzug.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hotgkuhu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fdknllhb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pucpzafj.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uhntnkxh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpxhqjd.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2vwahbqab.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qujhspzh.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzwwtuf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyexyanu.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2unbdfldv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2tiocqdcg.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2enrxoeub.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjjlmgc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhreqvhh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2puhwaxzr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsijlug.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yukjiqhj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yixqdvgw.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2yjffbfdj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnerxor.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyxnhck.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wzafgyym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2clhplcrp.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2foedvwsi.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2nzthuxma.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2iowyzatc.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2napvkzki.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxubjtdb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlbfrqp.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2avisbdop.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dviaurjm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2iyldwiot.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pibdoydh.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awizaasw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwzsrbh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmuwmnx.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwryyxcm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qosqdesz.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vjedlsod.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwpwokv.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2orsyzcnz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2woswddyo.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tankyymn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2njwovxze.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdsqdea.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgfiihb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2shlfvpma.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvenougq.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2onmkchqv.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2kapipvzt.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2egeqqkmf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjabuwh.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2keoxtuun.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqqwshe.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2iboazuth.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2csnctjyd.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyigqxm.html


<!-- 参考信息 -->