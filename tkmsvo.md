代发 wailian999

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2vywsjtxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwegqcp.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xceqlgyo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgkjeqc.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdpqvyw.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2jltqwugz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2noqfnzfu.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkasiwv.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxmszsh.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mygiozre.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wagovyea.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2iscypduo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zegebges.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2kyiwoben.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcoklad.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyevxlmz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2dnscvpfz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcytbcff.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdegdnxo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bryntvai.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzidpwyh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsbfsjg.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nswhaaeq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcbxzlr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2slfaichc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tytklxwf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgoemmh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbdriaf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdagngs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2azevrgbe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrufbtj.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2blgkassm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2yuojkxve.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xoiiwtcq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfdexny.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2imbfefdr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqdjqek.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2fulffjcu.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvpbcob.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xchzqmpn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2zovizqas.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhfwtnq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2fbamiaar.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2tholeweb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wktwfmze.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbzuzuy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2swfrfchx.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2lolhjtjx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2khkafuie.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxpejmy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2wejvamje.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2naqonpex.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2phjdwuzy.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xantpace.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iydbwrqp.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdcpokq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqitvfvd.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2blbsyldl.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ayplxijg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2hghoxfbn.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zifnwnze.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkboquc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2npguwlmv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnqsqty.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2afovdcku.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdecidm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zavvoueo.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgqkzkl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaaxerec.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgsbsaj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2vedqchus.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcoskuh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrxmoiw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2itjzgegn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztigbnng.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqdcrtd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oxeitfwf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2jaaeoagb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdcwjer.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2garecvqz.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcntxxq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2zvctlysp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzimrpr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyfhpia.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsnzsgc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkqhydv.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2fopsbpzf.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnopjnd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhltjgx.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2iojazudl.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2snvlpvod.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2dynikbed.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwwylib.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2zaovpxdk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kudhvbrn.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxsdndl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtpnkxv.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcfeyso.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyuzzhqq.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2rruiupup.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2figjtefo.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxyxllk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cojkeklg.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2uptgybue.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2eohauobp.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwomnep.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xojpounz.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xprzkyak.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2oytfrtyt.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2jzofotxi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2czuucmke.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2vvszhrog.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2caacnaoj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2serbiaxd.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2damvpyih.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnlmkux.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2tldhfaak.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2jncdqusk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfeavlo.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgablhl.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2crrhnmvy.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvuhszz.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcgdxsj.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjapbpd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlawlwte.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkipdjn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbntiam.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxlvewi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwevfqy.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2udvdwwuq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfescmzu.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmbhcyw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfrlhoj.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fncxdxrp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2nulmdqev.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2xfiamrja.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2matnjgec.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhxobdr.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrxoxlj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2psyhiymo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2yhduftdu.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mftpotoj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxffikp.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qyozwhnm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzuwwcnv.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ianxkzdi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjhaqjq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2snyetgfj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmeeafz.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2omdfuscy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jghijdye.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2juhpgcbg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcukyxj.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jkarinzn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkgrkoy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2prctygby.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2drpfnpll.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2isgazopp.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2jomlznzx.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2xxokqssm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2phyxbvnx.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrycfvp.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hqinpken.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2halxcnke.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsphoxo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjskykne.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkhnbzg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgbwjhh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcezocm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2spunvhyf.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2sesuueth.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxouiba.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwkhgrt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsxffmy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2anaohrvl.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsufbqs.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrjzcim.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ucseyvsg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvaghsg.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbzvjyl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmapuya.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcthxvqg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qabumwbu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2eclghijy.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uprszodh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcwghno.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hudrxjhw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvycmte.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgawwtm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaltcdsv.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpkqafx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2edjfsmgn.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nslztkjd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2toytcxga.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2phpsktkn.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcswrhh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2oibxayom.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpeciwf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zttkivle.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qjiknmhg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgnlezv.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvgodbq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyejlria.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nclwggvz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2sydtfhew.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wnavgbzs.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2plshqmkp.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpoqcbs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcxksya.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrfniwz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2toknxwfu.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2iriipcfp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdfmnwj.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bvubwmus.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2inzsgvvi.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsxqnsm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwsxkrx.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2amszdqqe.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhfebhg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkibznzv.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2teexmovb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kikhjttc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtdpalx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yteeatvj.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ytikvrgf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2notqjzdm.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2idbotsiu.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfehlxtu.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2byuecann.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmixpgz.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bvktxfev.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycanqhrm.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmncsny.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2visjllya.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2fzacgidn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wikslzbl.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzyhrro.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtqcrdp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqingin.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mmygbslg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqiqswtp.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyvrieu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2czussajf.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wfokevfb.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzycchcw.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbhvurp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbynpzs.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsupfvl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2uecmoodn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2drnrmwtq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sphsxcgs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnoafvw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzkukev.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnwmrsl.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbegrox.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvqvzsk.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2muyfhugs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2edrauhjj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fswmnjax.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2murspqkl.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2durpzlps.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyoryhfp.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsyueca.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mayimmaz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dgskddan.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cetnoexr.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqafdvi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjvtkjd.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2yyessmim.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2elqiifwm.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2qkoyhixy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgzchou.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlsnewb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2evaakqxl.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtwdnwt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjaynhax.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmwdgdt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2marqxhuz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwvanea.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xyytegfa.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzzbevt.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlqdyss.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwyxoku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lnytivzc.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2svsucqow.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpnvcad.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkaiqne.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrxtcks.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbpwjdt.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2uggdezeh.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnrexvi.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtvsdbv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2coegsagm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvphbth.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpdnbag.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwcuipr.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yezmktoh.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2viyewcet.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umulruqu.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvygpxg.html


<!-- 参考信息 -->