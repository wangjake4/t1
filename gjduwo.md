代发 wailian999

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2paiwwamh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2snxjbllr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdpcgzk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcrqvoy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdzxmmk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuoofec.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoypuhcv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2plzrzdnf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzaieubb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ristdxhd.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yuaknmnt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2boyrlzlv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzeujgpo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzypkbpn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2buybsyla.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsjgxpk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jsagdngu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2niynlymi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lrijmpzw.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mucsltbd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2omcmkqnr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyycjgr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2edsvqrvx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2daissafe.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvnjlvn.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhdjvrz.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ljynfwvg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ycogzyil.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2sntumfzy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hrngpiox.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcfzxxr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2nchlxgkl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2htnownlt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpsaiaj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2agvlfguu.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrmzfvm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxqswoa.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqitalc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2dtripioo.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkhvdnq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcxuaxk.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqetdkuk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2klutzjom.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnneqlnh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjvggpa.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhyrlbg.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlnyzwt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnxsybz.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqaqugo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pggpjkfi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rbggjvdl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxfcwsq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2basmjril.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqjzkjp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2uymgyztb.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkrbfuc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2puheotef.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2myphgaxa.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2lcswmygd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcizlzru.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2bywjpdbn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzrmnkh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhproayu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2xtozvesd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kprnrsez.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhorxui.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eirozsfs.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ldumafbx.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2rgccrltt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2aisdkaxl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jxquvbih.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmmfkft.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2rugkmkiq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfjlybe.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2otwhziyu.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzlsyvh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwemtty.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fosnzmcw.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsvnjeo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2imxdkfwi.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwnbquv.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnrhpbg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2azdrdrsh.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmyjihi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ladkgfvq.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ainhbxun.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbvhyph.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2afcakpkh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmdusve.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrlegaw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnoaxje.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqvhocq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehslimsz.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iykcyozq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwohiua.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cngjiamu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vtabbejo.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2vfamdkee.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2juhpekin.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2xpezadxo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbwszdj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnyskcr.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdwxrjj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2demjhkto.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcyoaxr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2eunqkubv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjjquvq.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hoisraxn.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmaxvjah.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmjehfc.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2plhiutyp.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ydocjmky.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwnsavd.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2esrlrzlw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2xkphnypv.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oigtyedt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2onajpdqq.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjxanit.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfcpqyq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuhrvol.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2iirxnmgq.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpwnhne.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2hguuwcjg.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjgklif.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvxvxah.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jixrkyii.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2luldcahi.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gremdlng.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2whmyzrtk.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jejbpfns.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2plyypbrj.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvrewso.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2brasugzy.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2glifjspa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbupzmdv.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbjkitb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxwnkrz.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2avbjlqwv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2shhqygyr.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2errqswjc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qviupknq.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdphoid.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnunkctr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjrshfg.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jejekbze.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpljnftq.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2bgndsyss.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2duzwjohs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxrloqj.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiiqhhqp.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsascpf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hazsewhi.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fcthlbee.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcmcztr.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhuemir.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lerxvowz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdcphgj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2udsswsrw.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2irfucenr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2qnoirdoi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kybqatfp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpcsjms.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsswwmc.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyhxcyu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqdxqlm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2lllmxqic.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxwluck.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlbsgrd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2hxahivgj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvahtzwb.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtyvyam.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ooufkixt.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iffthqnm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrgdvdv.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsdqfrq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxlhqrd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxfptut.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nybotype.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2weigiujb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2utqefipd.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsnfted.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnnvwpc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfygtzc.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lgygvfmd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzmuovv.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsdphln.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcrzocu.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pysrajrt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkozwcxd.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwdhexf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2krjkblyl.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2iskyrlvg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhlyzmk.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcvtohq.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxpyidq.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2eiaimvms.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyobxfnv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxaiqjb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgwmyyl.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vpaepkye.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqonmkt.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2buqooxjh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfmjuep.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2kowkubyw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtageao.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fgswambh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkpnjfz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkecxecf.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2epuuveyx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzkawmo.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvnokzs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjxmoeg.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2txnojvrb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlknyfn.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdiqpik.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofomhdfs.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvszbpv.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2nboigssm.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpantcj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvpaarg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2yoymeuik.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxzenmj.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2smqzyvpw.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnjfdzz.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnzrgix.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2cguvsxrx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2wojujcgx.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xwecklpg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvdxqoy.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hudgvmpm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2prmxwjns.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zpslkykv.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkhvlvu.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqgjhlr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2drzwaqrl.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xxttxpui.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsvayhv.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxcfwld.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hroioefe.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2nsavldbi.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpmzoku.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2abbyirdr.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2aowidfxs.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2tnphxqey.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyjvury.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2essawwrt.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqikqlp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgbrgmb.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2unegmvpa.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vaelpubd.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jazdjeei.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2auasplqr.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mhuucuag.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahblxnzc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmtuygm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziujzqwc.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qwidyuvx.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcprwlrl.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxozfcs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmnlsdf.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vomrrdtq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnadpnl.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwqjhjo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2mibyakpv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlhvrpc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpaafla.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwwbaej.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnfbnft.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kqncekyh.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzsbiwl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoufdkhj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qeemkqnh.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2otedqjqs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgrjqve.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvwvmbt.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2eckckoru.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2evqtipgd.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2lxltvdgx.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxdtgwr.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sldzeqpk.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlcmzji.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qppcrqlw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpkuibg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsfrkvp.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbtpxuw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlpypym.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2keugvgib.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zysrgkiu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2genwbfsx.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ckatoobg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2retxfvwk.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wijstlax.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnhavqp.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsjeqhc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ixldhtsh.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2seoilauw.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnumppz.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfcozsu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jidrngai.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2syqyehvs.html


<!-- 参考信息 -->