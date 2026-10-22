代发 wailian999

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmojzpxv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2fojchpik.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhynqvs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsxzjwx.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxgrzzq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmqpnij.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhcpqzi.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2etsuwggf.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrpbiwu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2axrndvje.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2kzztnbex.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2apfeizro.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2piwkujkw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2drnvstwx.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtacatf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2okmcyhrt.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hptmszsd.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsmegly.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrxvlzo.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ormqfint.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dacdlwkc.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqvdxsa.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqoibzg.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuqfcxr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpxoouo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpwzynf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzraayze.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tulcnvqu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhtyrzc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2scutmjqy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbmpshh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2almrclmq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sggryzze.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2tupcyeii.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2twyxgtgw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkwwaga.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2nliuzbem.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgyxdrr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jebleduq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsksallc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjhcann.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcobqejk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jogzskls.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ufduuztx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2wstsbekt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2tjifbnvd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2chcpbaux.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlyzxll.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2aicnzseb.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwpcqgm.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfrfxpc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpkfxyk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2kammzdet.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2clkdnirv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtwqxcf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbayqog.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxauzjs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2dktpxosc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlhzxxa.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsgtwdo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2gcabcbzl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdfqnni.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2furicjcc.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hheuunzp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2hdeujhfi.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2woiytwdm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eugnzokq.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzbpmcj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2luxhuyov.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkrppyr.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2bngpkhmt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2suzugstb.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2liydujks.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjeploa.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlotqaf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmtplnn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxsydfd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmowaoe.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqrqksl.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwhxgqp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhemqcl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2daddfoim.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdgymnk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsiyrbl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2bxiklspf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2outujzlu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnlxchr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2wkeqkupn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aculemir.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2icrumhiv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jupxuicc.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwyzuqs.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqcqhqb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsccwfu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwdxsrm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2lxajchmo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrdyqeo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2eacybhod.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgcdwib.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2rukgabxk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfewjdo.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfevhqs.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2egtjogaf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpitlhaz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2agrayvgq.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2rkprtbyz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kndxpfqp.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bodyliob.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wojkuhsb.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2knsxvvtr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrjogmj.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2krqqrgie.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlecmbi.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2dytxmwta.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2igcyibdo.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bctmeztk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdeealra.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2frwkutbd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdvrjon.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxzftda.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jwiwqvyg.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbvzdfu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pyoifcoj.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2nzunicje.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2phiripdz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2skxynvqv.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2aevezjal.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzgxgqt.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfqmjvc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2niswxugc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2brsuledw.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hltvchxb.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2axhmbjbs.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqznxxo.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsoozfs.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwygdwa.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwxewvr.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvrvcxu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2uucoxvzb.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdmtjgw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsavvpyz.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkzjfdc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2izuvjugc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqnnvqv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqyotci.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nkauxxeb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2rukaueuj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2gnivnnva.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2meikvlyg.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdxmfgz.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jejwkuyt.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vadmysbq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwojynr.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfjpjkk.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhgkyvb.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpnfhgg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdxqeil.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzojocr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfifbih.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ualmhkgy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsolwdy.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vphgcgbq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnrdaqh.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2likiauew.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qijthqit.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uxiypfxc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2msmyrmpj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2snpeetup.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdyufed.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyznweq.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2umoardpr.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2iywfirod.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvfkizc.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrnbewf.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uronpaju.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxijrqla.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kozbaeif.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iueftrjw.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrcvdvu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqqemln.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwhsffi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uinwvejc.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrxhnio.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vtycgpvy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyritiw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtzslvf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtoopcyk.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aaucnkwo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2elatxwzd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2suchitoy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2peipuiuu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vbchooqm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2wivhcjxq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqssdons.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbujrpc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzymnucw.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rpppbqij.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2yinntgin.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrhyllc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2etoacvpk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ecprawgp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksukeevi.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwkhmgl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlrokar.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrevwfz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmgnpiz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdeqphy.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nxiqkbqi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrptjkoh.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfgybsh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnykfnl.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fvylpvxz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2meyuhazq.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2oyepfpst.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nexrgecv.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dthwefnj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcrhjbm.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2sukitpsy.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2uammfbqe.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2htgxcuhr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkulndx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkiqbxfs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkieikmn.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtqjoqh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2obcrhxfa.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yjetahmo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbtpvtl.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqmvzuc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsemxfkz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2omlsgaqn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zctrnbjz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbbwjni.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbyjskm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pznbqvhg.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2iumzhxlw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lblyxtay.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgsjqnd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnoxgzq.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzxdnbc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2yalloujv.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tllneylq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqlmoat.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsyolkf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhklwye.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2dywdbnlg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2dysascmb.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2chtndcps.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2quwixlpk.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtgngyb.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rezawolg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2zccbrzhk.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfmgylm.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgoqazmp.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2kuesirhw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxyrikb.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ziobpphd.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bytncgco.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2xblumsow.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zimzacte.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjbgets.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbanwju.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxqiagj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuthgkc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2dximxhin.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2eupeatms.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2esloukeo.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtvqhxo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2dijmftlt.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2iztgxbgu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfkgbfz.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2koupwhmg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2mfojzhtk.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqsnvut.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjijjxjr.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wloveroi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzupxtcy.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uswgcazr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmklihkd.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpphrnd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpyzble.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2sijpghae.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjnmshs.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2fodnkgwh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzwppqr.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2haqgcpkr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2tpndlxlf.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2giuqnhjg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2defdwhze.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbbsvjr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbdawdg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdnwweq.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2towmtyrf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nyliekna.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmkwiiq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lggkdpjv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2duqxnoio.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qforgmpa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrsnsth.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyqjuhl.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2zxajgqrt.html


<!-- 参考信息 -->