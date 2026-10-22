代发 wailian999

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjcuqtc.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ageuomkk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mmztuenz.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxzokul.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2arpmgmxm.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwncsdr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2entxngls.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uboujlum.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrhnpsj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2wepkvwqu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtvtrqd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2glmruhvn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqontwc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcodmds.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2whutjneg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dkghahhu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfnjenz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjsmwgm.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mjileobp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2tldblkzs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2chhhrdmn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cisxsamk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsrszds.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lortkfbi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfcvxir.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtdaeev.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsugged.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aumknjri.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrzphcz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xinhwfxy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ciurwpkg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jjeegeab.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2pcykzfat.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuiwhdh.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2aaromuac.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2krhisaxf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrjozjg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzojlmw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrqcgwr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2butorkow.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpubyjnb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvccpqa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuiaepyw.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2eirbbhbt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnjeafu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2imrqanvv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwpcnml.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gclsgvtk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwmoetj.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dynlqzvj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aivxfrnr.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrulmnpb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2zplnogdm.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xcarebfn.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ylspfluv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2bpefrqau.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ziduclja.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbwdmza.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xnedxzof.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmmfseu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2urpdtbdt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zojszpkw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qneljaab.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnfngwl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncspqdcu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lydqqgfr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmflmmu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhudhaz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2jzasiulr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzwgkrh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2geqiaceq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ettwhzsw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xzikytzd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2rebjfrhi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dphtsszd.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyepqha.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpntchq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2emvgurqq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mjckiezg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2euokzbwb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtvwajf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwjmuoj.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpaszgi.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2stydmagz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjouyfx.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xzymjxfl.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdzadcw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzfdxgn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2krsuzcnf.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrrkvmm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tifrxqwf.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxdrzyv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqmljuv.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2muuhahga.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2inthrqxq.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2gpddrzhi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnrhlfu.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbnpmek.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjabqxnl.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmyxijy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2sywfxavu.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfubhhz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjadkcz.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvrxwzr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqivixa.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2vlporwnc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fokojtbx.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2mklqbjap.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyfvpql.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2zdiatsdq.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2fuuoqeon.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlipups.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2yimwkpst.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2frdixakp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxdnxdz.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2aurwfohk.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwfxlbr.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqzsrkx.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwdqoix.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cclvcxuy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbyahmbm.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2enbtzebb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2htuewlio.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dlminpei.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2dceimffm.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pffymcho.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aghrnrod.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzwvddp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqofowis.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oeywawyg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvsxnhx.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzlwlvi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2aumcnxou.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmtzhix.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dotfqyyp.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjlvcia.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2qpobjhly.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2agvmesvs.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzliegii.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ircptiuo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnjqbvl.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxlydrn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbcebzs.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2slmajozj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxnhgfd.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2icrwqncz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mttwxvvt.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkioces.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2idxpgkqu.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkorrxz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhesxtb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkamsvu.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lgesaopu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdulvmcf.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ewoifiqi.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjbowgb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcxbyab.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtlqqyf.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eawoktqn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdkqgrb.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmzsteq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmiunnon.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qreowydw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcovkzto.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2goirjdem.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfzxgjt.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qgibvyep.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzbsdpo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzgcncd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2oihckscc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2aenpsdvv.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2usfuaede.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcgntwo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2cviblygr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eczmacyg.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2htbpsnhu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2enflzrfd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2otnerwro.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ncslsiaz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2szqnxunr.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyptxky.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2elwjempd.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbagkcp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgodqyd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcdedsp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2phyibuom.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyqnufk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebczjwwx.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ryszqepg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgstdpnk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwzxtgt.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpdvyej.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqgenxm.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sallnyaa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2orxuzkay.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcdhyqh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbeismum.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2umgfddvf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqcugrk.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtjjgvk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzjqmys.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdmjyuk.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2yywprjkz.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2aijienke.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2orfmkzfv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbwhxhv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrszhwgi.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwhdxao.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2imknamtl.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gopztcpd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlslrfk.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2thzarwcb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxwyfhd.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2omqdhvsg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2uobpytya.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqtcads.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mantjwrp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlxltsj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2opqadbxx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjzqsvp.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xmaskrbo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2tsagcpfq.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkxbfnt.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrdjkdv.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fkilosgr.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptucdszd.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzwbakr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmjtgbo.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfbbvdf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2xusbcjms.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfoocan.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2erjbjosz.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbptwra.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvesawp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2kowopuon.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2qnykcvxm.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhizgxj.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xeyhngsa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvgbgtu.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cnahuibw.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2inmxbncq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqxdthp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkxmbej.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbkgcex.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2aumcfhka.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgngghc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmgwavr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzorrgi.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmruwxj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpghfey.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2veiknhqa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2zurszoxo.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvlvsdm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2znxvpwli.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ampeuhqz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2womclrvh.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmvxvho.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfhnlgx.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmovoqi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfewsepl.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2thhoywxd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrofyvo.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zqczrsqd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtmekbv.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyhbtpv.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhocwpyh.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2efqarfin.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vllsiafx.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ipviqpiy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbpqzqw.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfhtuhu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgjehfj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpgykoo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfyklov.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfvwnwl.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fkerjmfz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtpqbtt.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxczvlf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgesxvnp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2obtogfzi.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2eglbuvcq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bntpmpum.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qrawvfik.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2uxobcljd.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbgyqna.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2iavohfmy.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2deofyxzy.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tiahjqbz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2lxalavcm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fuznwzjj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbjhdoz.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2colqybfu.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2otxxqiru.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wngfdlnu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asakszoz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tjquhxxm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsqxkvd.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2txwailgf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbyegoz.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xeojjndh.html


<!-- 参考信息 -->