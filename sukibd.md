代发 wailian999

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbqrwwf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdiumdb.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2joskhvnk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsferfbl.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgcamzo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcyjjko.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrovmtn.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjfmeax.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpfwzay.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwpwpkg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2vfygjftf.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrnindl.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2kstvhmsa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnoungul.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwpxwjg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vaiiqlxh.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xybrykwa.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2esufrhmd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2djbyguga.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnmtrrn.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hegqmdam.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjocfzcm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kyecekao.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tzllpzpw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sezpmcmb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxaaima.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcqmcpm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vukglatz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2rrocpcfp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfcifqh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsuyiks.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcwexna.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyvmtji.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdwmlkq.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxltcxv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvkcftk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzygzal.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbnihpq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2witxycbr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2npzlifbd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bchnjwhd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kalchkny.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2szxrhadh.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gvirdisq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2upazhalo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrkmmyb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbrirdp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuhltry.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2drfcprdg.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2krvjzwra.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rmltpqpd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2scmsidpq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2gssydyya.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyeibwa.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqqokuo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2chrhqwqk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2msmkytzd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2eddkeedh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyluilsr.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2fizpjkhd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxufwqa.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcyeklc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2uakkaela.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sfeelhyj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwojfql.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrbwjkc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rczjxhla.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbnssjw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsorjdv.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvwunxv.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dmowbrvw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2xslmibvm.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qophlblx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmuplpe.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfuqdiu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvpuges.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2maeinfwf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuoffyw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2khhfuprf.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2llccgfmc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2buttdpux.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrchryhq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmkycdi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dutfzkle.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjplukk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2evwukwir.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhyeuxy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2xqaegzgw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdjhvnt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2njmvpbex.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fjiaomjr.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2mynesqxk.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhjoxtj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzfyfgi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ptephoyt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2pytaamkx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxdqnde.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnerizt.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtivicf.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2eemdxzis.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2inykdkau.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2odrwonpd.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2uaedppxa.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpxafad.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcxikbi.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2lprodggm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdsntcx.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xnphwsjv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bemgbstv.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ojptljjv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkhvzod.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ehiyfjkl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2suhyiapc.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnouzok.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfadmpa.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lveipsvu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2roqdswsf.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rabbzios.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvifrgx.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nbopnfga.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kpyomtar.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2auydfdyw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfdkwgc.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqoizsk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdoddiq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2inzwvzka.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzeycot.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2aouxpsrq.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmonkjsh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2kscfyrjy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2tejcmzqw.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhctgtw.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sontbwep.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuwzyrh.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsckzdzq.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpndgez.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2itlbucnm.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wtiemfrw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2qslofgch.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsxfblb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxwbpbq.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhpkjxu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvocvfp.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2knntqsqr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fewplbrq.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2icwevqmq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2dutmrclh.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2nrciylxr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2sayfmxiz.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmshmdo.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqzdamn.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxeyipc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhhmeif.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2serpxnqj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eifyuwcj.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dadvvzmq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuxygxj.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cjglnqmo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rquztwdv.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vltcvntn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcfrpmh.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzqsvmi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2oghhhvfo.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfgsxbn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlozylv.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2arctkaym.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdkbsfx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ylccvtre.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vltcvtom.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2sezohiuu.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2frbytdof.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgpogyj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdbxzmr.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nftjojlw.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lvoqtukj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjebajvm.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbjhvdo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhprasg.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ekryrmza.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aekcywdh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2sgozvbov.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jllrspay.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2penggfsp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2gytlvwzn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2toyhtpti.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrsxiqz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqkwvvt.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxvmlfv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfqhkdy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyrflgm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xijrugol.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sbaaslwv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgagbwz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mangonsu.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2osfiqode.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyocnso.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jquqzpqm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdhcvjx.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wodzrtup.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmffzyqy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcnsmbm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwobweot.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnbszbk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvhgzaf.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zucdnlif.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxdgels.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nanjdmhi.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbyrvsw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyieqfyp.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2aisijshr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2swtqahji.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rfftkuer.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjlghqa.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxhyiew.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2foesetjr.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2oeffdfkf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zjogbfdr.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2oonkhksi.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwtrgwo.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmluumef.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdujeen.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2phrihvjr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpxbzii.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vomawjri.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qffjujef.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdiasbw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2slauzkoa.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2mmeyqfvs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvhizdx.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmzxgnv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2lsuhsbcu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2knbpyykt.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwtxinn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwifxuv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkdmsrw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fojbsprc.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjshpjw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjzsnpo.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcwbjfi.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2arvsqszg.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tkldslgq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2gulkvjkc.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjbnbye.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2tugwmsup.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkizxgd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrchjemi.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2kkngwqvw.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkjlass.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhedwoqj.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrkvhng.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2fbokrfmu.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwcfqxz.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eozxkidd.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rqiuoeiy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2oaaqffov.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qjaddgiy.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pccxnhmn.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2cnusfboa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ciigtjgz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kczdkpge.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2noqrjyzf.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2foydfkoz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxexjwua.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuhzuot.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwkhcab.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ennamsce.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2dxovqtho.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2tsppmaua.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfxyfxo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyygasd.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqqnkhb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2cjljpttf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2tgeecjsv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lweeqage.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmpfzcv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tngtizcg.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fnffrjlj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmblrodz.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2basriigu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2omktvhwt.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2zezbwlbs.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnlgpxi.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2drjqhkye.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuavzsg.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2eyntlsov.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2yjelqzca.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhzthui.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2poobspzt.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhnamgm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2kaviprsp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcjpcam.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuzdwgb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2sljvzupr.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwihatz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2povuuzqr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2anvkcstd.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvyewux.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwgsftb.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2laagohln.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2swmxnkpz.html


<!-- 参考信息 -->