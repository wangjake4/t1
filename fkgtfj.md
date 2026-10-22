代发 wailian999

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjvtycj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2scxzzgtz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlugfiq.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2mbicrqtb.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2odphfcpq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbmrkml.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2pspuvfyl.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2iwecziwm.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlppxtb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlgvpbo.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyykhkl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zeuuylda.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ggopmwua.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2nqguvxje.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pqebsdmv.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqtkdrt.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxnznuf.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsupiky.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxomcfj.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uufyplge.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2migapeiv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2srpgjzpz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2mckvkbpk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ineedhve.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrmzrgm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmpdozg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbnxbyw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sdugjujs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2elfomeph.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ojeszxcd.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hteqvhqg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwfecol.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrijsau.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjzzbbj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxtgjej.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnildlgz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ockcpbxo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbdnxiq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wakusgus.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aybiciwe.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2trhrwjpp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwolnbg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuqxkan.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2whsnawbx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjtmwgn.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxocamc.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hgooexln.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdvdwcf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2wxplwrfr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2phegpcdu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2womsplbn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvkxevm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kopmmiky.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2nvuyffdn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfowsno.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2bgscqjgm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2meooabnk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ognvicog.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2zefqxvly.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqwkgvz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2siaehumc.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjiudzwk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbawzkdt.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgllxtl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2hugnhzkf.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imspkpjt.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2kzexgxbm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyossbp.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qbntkhql.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlxuxrj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2llozfkbx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxwektc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2imxtzsid.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qopqtres.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zewlqtns.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2beyzoqye.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgiyxkpl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nstckfgc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjrbfwg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeoihfhx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrehrno.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2gseyjdva.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzvtvha.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2tdflrmqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrppjvt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmdpehd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwplxfs.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2bojcqbkp.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2bqogkeko.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqojsqt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2knkoroog.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtiolly.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2xihitjxg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2acblgnnr.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2eekwiqii.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjjtqyt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2cywahvpw.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyybdml.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2iovjbatz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2isovweva.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpreidmn.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2tdknekyf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2aianisqx.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqtrjhu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2yixyzivz.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2libpwdoz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdodogy.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmxtdor.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymynkshg.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvqpmyi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxpvsin.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tkerronb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mswtivfl.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2psldghlo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyxfkeh.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fpknbcgx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kkobkmhm.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2duabgzew.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvojaaj.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjtawkj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2eujoskix.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpdvokl.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2svxothbf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjpeasy.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2xariaqpn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdwiyyv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqkfvdo.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwlejtx.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqylmqz.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gfoaetaz.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpjaxbq.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2avmykdtq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgoemacx.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xrophdlt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2tljlmjav.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvklvga.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvmnqpl.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hugwyukk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgcucvy.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kqteifdp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjxvrer.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wydgrsir.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcxflrw.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2owrlmxyj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2atcfgzrv.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2emztppwc.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2astdtune.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hstssswz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2gncflqvc.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2injajcpq.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfnlrhu.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kzagwsne.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aglmyysb.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnboycu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgomnfen.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkqpfhu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qugpzpks.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jxudeyzc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgvjkok.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2teiwsgcz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2eymxiezg.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwftaro.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2umuhrrie.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrcyegh.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxzumve.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdmukka.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzctqdd.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjrrywy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2erkrxdqe.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlrtayh.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdtlhpf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxnrtfk.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcivjdr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzueycsv.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mnghergd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lndhfiae.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbumnqo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2otduoafs.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqgktic.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2usyzvzzi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbxcoch.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdzjqbu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsprstj.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpfagzv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2jujmdtur.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2siyosscu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2irmsoqsd.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbofeal.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ebicpriw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tptrfvhm.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uymymfce.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlqckka.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwfcmsc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbmftpd.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2akdtzgfd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkkbjkl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2magehbye.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuncfbf.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwbgecl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpwevpp.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xlszhfei.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2almjennf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfhntlf.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2curruufw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbbtwdd.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbaocbv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fuowkkuc.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2intujbji.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdygjuwi.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfknkvd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zotpwszf.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmsodpo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwqbuvo.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2mivnyboi.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2qoumqymu.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsuydwz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfrbqpi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lprcfvxa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2satecyvn.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmabmsq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukroyikt.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jufksnpc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffefpqls.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ukefykzp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2prnkafcu.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cybiwjuo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2osiufgbm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2picclxyu.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnolkex.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpbchsd.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2atcwjygp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tueklwiw.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zeyyajxm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpetvqw.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrdoetl.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2thripebn.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgqwpgo.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbvxroo.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bjuzantf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnygrczf.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2iblomaju.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnkavxm.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfcvhus.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgodcdvm.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2acicguhd.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhmrcfx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2wkamfwuq.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2cowuymdt.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxubsvta.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2uppxmzfq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkoygvo.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qftrpgup.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2olmhoeoe.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2incrpzva.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fykwypcu.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpmmufp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2meljuccl.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2htskuunp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqfhlfr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2uagrmdpg.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzdqopk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2esutusfw.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2vybdutiv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2bkoqvqfx.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sdimtvsn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhwrtlg.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nejgtbac.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qgacyavs.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqvawtk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vapgncmx.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwzjziw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pahxuzzj.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpnfzdf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2adjyylvc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgmajuh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfpbgik.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2azpsvgsq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmszfkzw.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrjyqvt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayibajnj.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vgoqwrgz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwxwrgo.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdldckvm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkviexh.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfoezjo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmprlrg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2anakvite.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuokaon.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvjsrvz.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vyarmssb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lanouego.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiaqdls.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdmwbzq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhxowfe.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2oztfwbxi.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbbxyij.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2udkkbauq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vpafapug.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzstgczc.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bkayxbzx.html


<!-- 参考信息 -->