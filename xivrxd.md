代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2xahkolhv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2skoyvxgr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtvjcct.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zaoaghdm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2spfvyosi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjyqsqw.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzgnxgu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqtzjqf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2epfuubsw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzintgcx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2urlquguv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2deiklchj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2sisqdtvj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zupdnbqq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2urigsxnn.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2chaaisud.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsszadc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ioariyoe.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ctknuxvg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2diyfglhz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmkvpjo.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2okptmgbn.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmkgeiw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2icmhycty.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2rgohwmeg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jesiiahl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2mnylgpbj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ermkkylj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2crbjreov.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2oyubgszu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrrqbjx.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2cstpvrwc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2aslogzmu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgofzdi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtfiyeh.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfqwnwr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2itjacehg.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nagdpvgy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ckafhkqa.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oarhataj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhunbdfo.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxuopbv.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2eyudtmvs.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrldnjy.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzletba.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2axjrqtiv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2etowojqa.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnyzbws.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2cluteskg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2csbvwxps.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxtwrdi.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2azfsybxo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zteuvzwg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2udefpdsi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2unbiktvt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfkcwsw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2eoojbvru.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2yljndhpa.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlpaasu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2rysbfylh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwgknyp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyahchl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2snavpndc.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2mzilzhlj.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvvizmh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ousvtstg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjoifvj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2hbumtqhz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwcalth.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2insxweww.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdieuqi.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2jilmyknz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qucjncxo.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2udlmbyri.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqvnzck.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppeuceto.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlluqtnd.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2myhlrbhy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqotawc.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxxcnve.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqngegpy.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpxtkge.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjgjgiu.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjoxmtl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhwxuhp.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhjzpsp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vckryciy.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kqusrqgv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2plxrvayi.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jcufoogf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkygvcb.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfnbloe.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpuppbu.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2grsaztii.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmximwn.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2hoylbvqr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqgecpa.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfjfabw.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnfaguz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2eklnpobg.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvlwkje.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxccqxt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqejnhlo.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbhyqys.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcavrmc.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nywfochs.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yeaotvyf.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2efmsyywp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2onjvaxls.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgdfyhc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrizaql.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mttovnns.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpvyzum.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hvupdqnq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfekjqc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcmjsel.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2njboahpt.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2izfpcnhl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2afywaukx.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ienysqli.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpcggxv.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vypgxrio.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkswmux.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdmxdhf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxpeuea.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ipydotmg.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfeugnla.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2midsibrr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgwvsgs.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bvroigfu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhepmveh.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpjuweo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2feaclfor.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvgojti.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkijmjnr.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlbqwya.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwuxtkin.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xzllyigc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pllsdfrr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzfhquf.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2oklahaqs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzfbvyw.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvbxwtw.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2oavuadma.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2svfiapyi.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwppvty.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkgxrhz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2loobaeli.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwvunfp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhvjqpy.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xadzvcak.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fglrsplx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkpmnpz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2abzsweni.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbxgnnt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2evdpabjn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrscmbk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ercxhvam.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2dycrhtpa.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sjysigtw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2moogiogb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2uijpjjdu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlctjyyx.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvgjcug.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsyhlgo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcibwslt.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmrhzxf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvexmzy.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bocvekot.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhkacap.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqxtzup.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvzfjuw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2umvvcmir.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkzctdp.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyhdepx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ighzbsyi.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2atsosscm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvuycuh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wotmqfjz.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2snqxbjim.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2myfyvgvv.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kivabznn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2acrupieo.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zyswvsxq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhnyrif.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2zigasedi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2igfpctzo.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbdytad.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nitebzhl.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvxgrcy.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfhsloh.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktobcnsj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcpwptb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtknejg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojstlhqw.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2idaajbrg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uydszodx.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfvdsel.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvkbloc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkldkyh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2knbxigfr.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmctmbf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2tkendryh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vghjzhxe.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xpufrehc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxjsbsf.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2olcsukqc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hehmpdhx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yljmmfqk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrcpneh.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgptnyk.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ultqfuxc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ujedevsa.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2cikljfxg.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkljrsk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeexageo.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2lfaghjif.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvsghgj.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqhbmos.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfghxidf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xigsllmf.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmhaffb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxthfvv.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqwewfb.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpzugwh.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2kestesse.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhneemi.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwlytrd.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ungchsnp.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2visloifm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsltqrw.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vgujclsk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2lenydawt.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyslqdx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpwldha.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2jryryuce.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdfqlmp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2seedmtja.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnwktmk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2zksqcvoc.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2oslmznxj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2rldgffyi.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2affgydop.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2lysaszqz.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2fildgxwm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnynlnw.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqzhpxt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2inaueaxq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhgqnaw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpokqirp.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkjzurn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2auvtcfyy.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrkafwe.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lehllffc.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2aigvmidn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bulrariv.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2cusjohbc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2hebyevog.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oysrdicb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxghqdyl.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsatcnp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2slmuhyty.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqxdvyp.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ucliaqer.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2djlrllde.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2iuempfjv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rczfpabv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwfviek.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxtgowu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qobykgsy.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2kidyeyom.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhqpbwy.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2kasohynb.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzxrlfb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2balobigg.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2urjsyvpt.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtlontt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmucglax.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjiouhm.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdgaaia.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2noujsrmc.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtiedvc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuefgkae.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjddkun.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cvirqryg.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwzgusr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgutssr.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2flzkrvbd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlyapnp.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qagqjphi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wkepfqmw.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2sposuoyb.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dksuuepd.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpcxqza.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lixopbqo.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dchalchs.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuhmwxu.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tobpklho.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxighwz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2szhfhvcr.html


<!-- 参考信息 -->