代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfkvlgr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbmrumb.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qmeswhyx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2infinjnb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyniwgj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjpqxpo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzefdvr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnxdavv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqkirzz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpijqrj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlgggzm.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2exxelmyv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzscpkc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2inqfqmqr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjcdjlr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxzulbr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmonvho.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzuvohs.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bupefumg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzkabex.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2zvddrtiq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jljcoveg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyekzcc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlyaqrr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwmidwb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjmxrvw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhaplisq.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlkiixi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbbnrqr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtlfkqp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2gptdpqyu.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xngvyvlk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2deevgiyz.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfksntet.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhskqmx.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvdwwit.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpioxqir.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqzqbve.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqwwhwd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2oxurqjkf.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsnfgly.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xudvxlua.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcrkpcz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuabvswj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2seevgzsy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyjvyqa.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqalydh.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2xhemevij.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xftaqyqk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2alpvxows.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnikxce.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2upmcqnme.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpwroho.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2yjllelmk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfutudzq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2oonbgkjm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2edmxtmje.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ayahgcvz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aukkpzku.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2gmiupply.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2bxichmsh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgkeuqg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vhovpiky.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmwisnp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2hboylrbg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvzyjiw.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwremka.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuqcjhc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2onzanlby.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzunzxx.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjnmheu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2evlccfpc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuaovxg.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2axtkvzds.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqoxewbe.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xasegfrn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdabamu.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwcdlod.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yomtyvnl.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2miuwcybp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2heirhmoh.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqfrxff.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uperxvqb.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmyjaeh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2abcyqugb.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyzkwuh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhinrny.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zhiugeug.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2udwyvgpw.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjlayey.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lewxkubx.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2gotvexxv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfcikjl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ouoqeyzk.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2bmekndfi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgoupea.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2etzmfjni.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2wadyphpe.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmdtooe.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bdezebny.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvfrqjn.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2humkzrdn.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwepmml.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2azkieffg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtekigg.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2splnlhvb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgiijuz.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnplzfz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuhuiog.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2djwisaoh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxobune.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bsraxgtm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsjkdgs.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnoaarc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuzsdog.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2nrecmceg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcqatbx.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ornlboug.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdtamlz.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2imrktsui.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2dadkdxnu.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vikzclgw.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tayzyvog.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lbepuapy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yeenqczm.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmfgsco.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnmlrne.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2aundlagy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoekhkdv.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wplvajlf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyehavk.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2goeproxr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2efbtponi.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfeqgev.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2voemdarj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwujofn.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnbtspi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2trmrrnqr.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ranirbou.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdcmvpp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2sitaooqi.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2liqygilt.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnhntld.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkybxkxx.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyxiczy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygorilox.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfxcjid.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jthqtkyz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfyffzg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzpaypi.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lueaydpv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2fwocxtsi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2glssqrwh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2efjddoyf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvdrjrn.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxogafl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2phvmxvzb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2alqpfofq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvlrqcu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbknvxh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2uemvqkkr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cybttgma.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2riqtonqy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2spwxocqc.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtwozet.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2amxgbvhi.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdhlozz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsovzmx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2khhdtsqx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2uunwwblv.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qokmtuaa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2xddvcelp.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nzycrcuu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnnclmi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2oozxjqgd.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vapqheed.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnehripr.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2frjuahtq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2eufunkrw.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdsxvdy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzyufxzb.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2oxndoxtf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfiyksnh.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfzgqhx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qufpgese.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2geurrjbb.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqyhldy.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2cliaufml.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpqhdwe.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fldtbmlr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuuvfyh.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jztsjgme.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mutoddpr.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzjqcqj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbixlvz.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgzmokr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfombnsm.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhpiwwa.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbufflw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oicijikr.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hatpcjcl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrumujy.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2wfetzqcp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ousojjma.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xgybkhsg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2sodxdagd.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eztfnfuq.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngaibjna.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqitbve.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2yelhpxzs.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrhftrg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2yikheaov.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2llysqplw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpyijnn.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlszxaa.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqcsnpu.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlirrle.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2arbawlpo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2oyapuztw.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzcucou.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2isgpaqqc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qylmerfo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2uihmlbow.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfhbake.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2phiqryvh.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2irfzjmjz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uagoivwf.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fyezsufm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfsuchf.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwjxsxg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2klxlabfz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2kabhjqsx.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rqiikqdt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2whxqfsmv.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxnjpba.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvmogzd.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uaaogwgt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2iubxqhzs.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kmituamf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ayulgmvs.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ypldpvyy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdshzav.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsafccb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpywlls.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2muziuwlj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbunfuxs.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqncfkt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dckuipqq.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ljblugpn.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zppugiwj.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwkmigc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2yozywvks.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmcpyee.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2xohmaxpg.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2azqcoorw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2iktdumfd.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qizxamtk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqvqhaa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2njwjnvio.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2flkerykk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gpswzovn.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2erurpfgy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqurcpd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qsahkcie.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dljeynml.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnrwcct.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2hoixmyfd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfncnka.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2daywxosr.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qgehpdlp.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpedvzw.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2waaekcau.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2bqigscdm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ceiufetb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2cybpedzs.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vasdpxje.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwrtxmm.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lusfzkks.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkcldmc.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bshyozno.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2deqtqtxf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2czeidxzo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfzmopy.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdlfghz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2woekidhj.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2udjvojmi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzeozih.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2uqffyztp.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwohfvq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tharnxbr.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngerosrt.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfecumx.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ughxutwk.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2khyfzzqg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2trikcnwe.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2euotojrp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbamgxm.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmglfgk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zltunrxj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fupiwoha.html


<!-- 参考信息 -->