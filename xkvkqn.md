代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2txfkodzo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzhsdqb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyjeihw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uoscvneh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcozyds.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2wareipot.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cmaspeoj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ealofzjl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2qakcnxyo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewknyacc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmiobyvt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqutwyze.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vogbufbw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jepjhguv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaciirm.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpvjfzg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2bppaufuu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwrvsjw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2sirscrlk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjxvzyr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2urmysaij.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndspkcln.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2veqthelv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkbubtg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnqumcd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ijuzsdml.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwjkbnq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2siasfjgm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2myzfhscb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2evhxhnac.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxniyvhl.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjyyghh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgfzfai.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmjkarm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbhvqbb.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2soujjtbm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfkmhxh.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jprbwhod.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrhknfp.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfebavrr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnerumy.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyxlnta.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2tukfkvmw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxrrrol.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjehkjd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2usgfnkul.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxasvns.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuktmirk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqjjmpl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kjoreieh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2krzggzjv.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkqzmym.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2awqsjgzv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgurpfyd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfkophv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdumrtz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpsdqla.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2cepnakpm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxyyrzx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2sewyqzvd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjllneq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfuqkyh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lctktjoa.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2jndbpxhw.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2bqathjpp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2otfmattr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhzhyjl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzperhx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2cywumrfx.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtlzdfq.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2mciztpdg.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqtyyav.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfrmdzq.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqdqwls.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnnnsiw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyohaii.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgrpbds.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcobcbk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzysbvbe.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjbjjuz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypawyiiz.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtanpbc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsubxalw.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfelqsz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2llhdzvhs.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsfjqvy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nppnvozl.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ezaynsvc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfsftod.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gptwjmlq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaqiqlc.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2oybvtsoi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ibakrytr.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxtomiw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2arodsxxe.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxfroyj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhfrirh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwmyxbb.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwxxofa.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxlgolc.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2sahqyekl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmwvihh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcgnwne.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2cysroipk.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2apgzoeiv.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwesbdw.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebljhjhw.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnuzeno.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqpomck.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfgbtmo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2dliesfnd.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zygddzpn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpshfswa.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dwygjscr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbafbam.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjdynkc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2moijatgr.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rykvhiha.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2utdfinwa.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkjdkhb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwswtapy.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhloxvd.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwjylgs.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcphass.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2dquxpzjv.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwheqhl.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhzrhrd.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdleplt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsvhhfs.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bacuebow.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmmzfie.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbxuzha.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmoucqn.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzegwmp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2whdpivol.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mduxgifk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vglysceb.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2awrsbftg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsnstvx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2cybvbmve.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2shggrlab.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2kollpauq.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2mukliyyl.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhtwjwq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqeyqci.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqryvxbk.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2horgfwla.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2srhptgui.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iztynvew.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcagpjci.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpyobfv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aivvremi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2oysgmdjs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nttnimwq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgvobtp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmljiem.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdluidav.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2eulqfzqf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcnnqnv.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sztxiopr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2whphvngx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfunqlz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2grtlvfkh.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2woydehsy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2opbvxtyq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzcxekz.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nifbeyhd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeumgmhv.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqsokfb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdovmmyo.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkjjnwi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfysfgp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnbmajp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbfwkqt.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlzqxtq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkodmkmt.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hsaclylj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtjpdov.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcllrkot.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjzlufm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrlqzun.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqtdsxd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2puuzjxjy.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnkkxfn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzmxefl.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2yghkdgrr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwoaaow.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2matqorth.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2exgtupwf.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsgluyw.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnwawpc.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsxeonq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlxdgdh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2awiymalt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqtqsfg.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mijsawkw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sptgjlfa.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbigkek.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dshxinku.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyhlrrx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsvicqs.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnuljhl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2xsarrqod.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwsfrck.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2arzuodpy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhkebxo.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqlurjw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxegushf.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrjgdts.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2fknfuxsd.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lnifejvs.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2odwacvlu.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhbkwma.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjpbzkk.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bwogxzjw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkfxkgr.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2adzgurmu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhyqhmxi.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ingepjvs.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyiehiy.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aghwtvof.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2elqgddfg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2kondnlym.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tefwrrsr.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgszfloz.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpicspr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgzsjmv.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhyizzu.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxtiwgd.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmmoopy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nproopmy.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdjunfk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrnhthc.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuiduvl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrjejgm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkmekmz.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2atsrwoda.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2udmcrqvp.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2wfprgnls.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2usrkhsln.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fybveqmv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2siaoibix.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2phgixrnd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrbdskn.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2dxflsnhe.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rabfqpqn.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsmjymd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkneuuua.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aejqujuz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cquqlbhz.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gymqgdhg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwjulsp.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2epmpmbzt.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrkcrvr.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2orycchoy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgczcql.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2djyreqwb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnjzrzi.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2onsytkrj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfrszql.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uysnpuqn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2uugupvsc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wztvpbbb.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dytkmdho.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cxngmuxm.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgowlvg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2obpqjqrd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhonxdga.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuxkpog.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyegwyg.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyaxjyn.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxyjtle.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vctfrjyg.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbtxstb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2glwcfqxl.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uaksdkxg.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2bgplenea.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eztujgwd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzyubye.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tulniocb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hthkrywa.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnkvdcc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unrkcehw.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqejcei.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nbaygqxf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxaughx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhcxtiz.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzifwhz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2smkvdtmc.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gzccxoel.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vofpszbf.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hcznxarn.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2cxaofujk.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtrcadg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dejzjhnm.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nctdoxom.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcffkec.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nsiuwhfn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxmhjtl.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tndnzhdo.html


<!-- 参考信息 -->