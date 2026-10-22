代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2txebfpii.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwslnjwe.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvfydka.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kgurymft.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnwmlqo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2gzddwrth.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxocuavw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqkowog.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpsjptd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2rposklrd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcbrbad.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gctnxaeg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyugvoy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdajyps.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zgeysxjh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2aprrrbhm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2etkavlvt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbmstvm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2brdwystb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jksqlwxh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwjpcjy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxejgejf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnoqgel.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2atewniuu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2rlaabqyf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2waeqmaxu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2suuexgyw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wavapsql.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsbpcsi.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwjjakb.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmcihch.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbtqqtx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzlsagz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkieszi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2rovcpvjo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2arqpsqpr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmteeiuv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2axnwmrat.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzvbmut.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2uobvxzvz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2cinndoeu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2aijqlaiy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnjusxf.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhrlavo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqapxoi.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbktsro.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvcnedq.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpilxat.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfcgyze.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzowmra.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmnemhk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2vxiktbgu.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qoojmpse.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvodaco.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwlmcwh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjyeklp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbqedkh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rxokycmi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpdkzun.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcguhmy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvnrhvm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mothsjnc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2rniiomok.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfnzxqr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2hekkfelr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2zygwtenn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzndqiyf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2qndqfvmu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mifazvyf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2rsoljjbj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpzshyu.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2fozkhdkk.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2exiywlir.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuejugb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2wedehkoe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsgbtyk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2dnraxzkd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdnxysm.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgntowa.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2zmveatbw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ayadndag.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ulusjxno.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdsigtt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrccxgd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnepoffx.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2dabnkoqz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvbrzxv.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvfdkhy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdmucuq.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2rynlnrew.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvflifm.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvahcpm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhnxxbd.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwcomgl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aseqnmtr.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrdrdls.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcourjs.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfontkr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxmtaha.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvdolfu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2djlgattp.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2grbpwims.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbzpxvx.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2vflqgabj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvklpry.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2omgiiymg.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwegvkx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmsmyuu.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2xusduxup.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnrgzpb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnylguh.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgpzbsl.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2migevbqc.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyhnsau.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlptvbz.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqapgag.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgohkned.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbiytxq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2fklriwpx.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzidqkf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2fowdtgzo.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdlvciw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2frtkgdei.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fckzdfqf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkawmpv.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2juvtedrw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhifotp.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2pzctfyda.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrtulvn.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbfklsk.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2howzjmsw.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnxpgdz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfedppy.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdxmxqv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfptuupa.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2flgdfaez.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwiatnu.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2piejzhtz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbirfpyl.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgyydpq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsthhvel.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2syxwutlk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2avsbgedd.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eudneoch.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fymoohiq.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2siitwmew.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqolvyfd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgqpdyt.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqxojnf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjbwdmq.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2fzczmexe.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2zymxoavn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjzotpy.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpksloop.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwofahe.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2boxvwnjp.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cllsomrb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2exmvisvd.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwotolo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqypqffy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2wnivzdhp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zodvblqk.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtgekti.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpkejsy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkhftyi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpmgwpp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2awzipzro.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pyaevsuv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhamqil.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2djplpfnw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2layduawi.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfrqqwy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2glnityii.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzinltqg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2txocvaaz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqpevdc.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqrgtry.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2svshemqe.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwcyzup.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2frtpmrqb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzypiia.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2msvdvreo.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzuvqyn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2kraqkgio.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xqholjgo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2llvwewnf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cglcvpfl.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2piaolvlx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpekgsar.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbrasui.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmotpnb.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rulnruqo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbzkemg.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2gnimjgqy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxxrojo.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wullutnj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdxyyre.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpptsdu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2asdrwthu.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2igjkcdks.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvowgymo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlqcjwz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cejolvzt.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2iaankbog.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvhhsaj.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bhclpwde.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2azcimhtc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbgetis.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwwcaws.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2orfhugdl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqdvban.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxuwcmj.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rhodrftm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fynzhful.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2wobknfor.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmggjwb.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ywviiqfl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2eabopkcm.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkjgrhh.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqogbme.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2iglgqrrs.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnorumul.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vljwrfka.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjzmhul.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2gacqzvjj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvtvvzd.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmfoknw.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmfqjfp.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkirakzz.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxayoia.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2skqrllln.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2oetwdoyd.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2akasxzsj.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbwkqxz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2paymrvgd.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdmvzvu.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmkkxrj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2opqeeepk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlroltn.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrvlgjf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2saaljhck.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjxathc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdnqjsu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmqsnsu.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsnzzkw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2lijactlg.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2pikjpwlp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hwreyiso.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzijuit.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2axapzoov.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wjelfpli.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2lpodyfax.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnfapsp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqxdgwq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfhuweh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2irlahlvq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuuleka.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmvaaia.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2foperugx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmuiuekj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2pindvqht.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2acwfngjj.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtijmcn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnhqijs.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxyyvvn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2alnadapa.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2duokbtiu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2idqkvnxv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2obqfiihs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2oajfnpee.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjsoxqo.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrmovkh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lctldasg.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkfdleh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2brrcxcqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2foblghqh.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2aaeoitwx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrcgfau.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2eyuerwwq.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2hglwwxrn.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2krkftykd.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2leoqjeia.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxysrkre.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pgilntat.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2akkugmnv.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvwzsta.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2muqiqnbj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcezcir.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsaokml.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgkfgdh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbeqwtu.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnztizq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2flznfokn.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2otjzuusi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rtersazx.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdkvbxl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nevoadah.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hapwlwbq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfbnfwh.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zouppcyw.html


<!-- 参考信息 -->