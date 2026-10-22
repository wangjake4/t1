代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2vifzwrfj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2xeypfceu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaoaarbz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yviacorw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzerqnq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2lisqttog.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hriqfyhx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhmyqlc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbzdgjd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ueteodhd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzxyogd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlvbvtr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzktpau.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpokrvw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jkokfhwv.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ythphyuw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2bemgruwp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjpfnxh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcvrjgx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvaywbo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2aunnxxrw.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrthrdb.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcoohur.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2srxihlzg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2kdaikbga.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkdixrm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbwhuhs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqcmkke.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2exzbsojo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ublrvgpg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsitepm.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2thcaxota.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjvdhxx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdgmeup.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2plidfgzf.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtmtvmf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhcmikz.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjzlglq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cctveosw.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2itethtxp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ciavcryk.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2syezezxh.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2shquhruv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpzzdll.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxmaawp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ftquaicf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqfzutx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjekwos.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2hhchjpwk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmncusn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rtczvxpd.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnpghjb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hexwlowf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkhtybh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2okrpvjpo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqghgvm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvinhcj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2xyludjrx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzoqsdro.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2csgnzfsq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ljprvhvb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2immvfsqz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkykzcau.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2sragumfk.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2knpxwvml.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2joalokgc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2yckanyxi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjuqngs.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkwfhcs.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2eswlyqpz.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfmeqmn.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlygyqx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxrqzxz.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2pzenjdtg.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2wonlcwcq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsexraw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcecgxr.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2guurnaoq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kitkodps.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuppnxj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtngdoba.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzyoafu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrefzsb.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2gmaoabag.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvvsggd.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2cuctpuwf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdptlsfk.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dyogtdbm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2uawtvxwp.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsscpgd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrqeauc.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyicuvu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vkehgout.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2alafbpzs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hmicwwzm.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2pezsecco.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2fgofcnht.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzgdskg.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzikspu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2aazhgylc.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2rowizfho.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2emjmuriz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkxlecf.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrbkpca.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vubrhvhx.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvbdojy.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzmogqj.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2velhgnjj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2brlwcgcc.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mtztdyeu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpvhnla.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmvggoc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbypcdq.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2plwkdzyc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcvxrif.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtpkexy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmwugwm.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2quhohydt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfhcteo.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbdzllw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2llkyvaee.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmsarzl.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aftrmcbi.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2alelddnb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2uygmjwzb.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2oeffjyzi.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2weayycjg.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xnadzbyg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oznfaxrb.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2exosywtr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yquedauy.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyipous.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnlxvvj.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2llxbdndj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbksezgg.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmivbgm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvgyiky.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2enghhbok.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwkedxy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2wujlbvae.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qtysyhix.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxtsxyy.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2wighpgtq.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbhrkil.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2zfatcvwp.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdglspc.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxuiocc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsgzhzs.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dorglbgo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwdigip.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgdvwjz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvztrvb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2anpprupm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkdwfxd.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2afvkjiqo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2bipxplfv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dksiblwn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2eydwsaww.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbkkppv.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuobzdj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2chpcwfnm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2dflocvrc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nubrevdu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yvubepbg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmndzxh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nimnbrkx.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cxiigigy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwbkbdh.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jpczvllk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvroqqxj.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwxwkln.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jntdrjdu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2spcdzqff.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxxygro.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kyadpkfk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfhjhgg.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nrciviyw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuuplxfq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2esxsfvoo.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2huqdhclz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhayioux.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cqttlzcg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jqiullrx.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2waxokjaw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkwnetu.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2xbauntej.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aocgwuly.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2corfkqst.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbhfowg.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2aoasmpdu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxytimoy.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ugofqbzv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gszvalyb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkyndts.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqyzesq.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zknwgqfz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtpnczd.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zxaxdywj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjffbdg.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2olwrxtup.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hflbpijo.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsqptlx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfdazue.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2odpgkucn.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kimewryo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xspmoxxg.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ztiozauq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpkoboo.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qqohymno.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2fszheasx.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tuipdhhd.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzarfvl.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvjtqbq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyjqagv.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lpppaetc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzaqzqof.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2illwfysv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2cainsyco.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfeepzh.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjkxmuq.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzpfruh.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2vadfnwje.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2amnjvypg.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhbujsg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2blmxrfss.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2szljehsn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2jfydagza.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2joikpikh.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcohvnd.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2yykfxekt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tjusibvy.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2debcytat.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2dzolrdih.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oscegoah.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvxvwgm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2blzzfkmg.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2guwwqsim.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzveaaj.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2avhzjrqa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2xclwedwp.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgvvoeu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvdisby.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsduiyx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbxmgwv.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsjgatu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgxwixu.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ephhkzvo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyrzguc.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tmswnzkk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2arsjnigm.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2antbjjfw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2njwnnmia.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqktoxp.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhoqukkz.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2rpirbtxv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dthppxov.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ekglwdls.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmfhiye.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fvprwbdh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2kijgqnlk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjawoebz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2onfcexiz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2demsmsly.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2idlekuis.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcyoleo.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2exrfjryz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yygefkfy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qaltgckx.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2odsohgnx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xfypypsc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuykkgk.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyynozm.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2dreyaoda.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwfrsvb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bibgjnwv.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrmwhew.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2iizqdqga.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrygtoo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkiyrmh.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2njhnrwbn.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2geshsapm.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2egrayzpy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbciqzwg.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vzejaejf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtocnjx.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nznpaiob.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mliiipto.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxurdyf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2malpnhjl.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbbcklf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qamrfgyn.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2syooxbel.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2trrrfpef.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwagnuqk.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwojehh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2duocofcu.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgtmsqk.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2igjzvhwn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vjodtvtu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2epqmewkq.html


<!-- 参考信息 -->