代发 wailian999

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2iedqopex.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpmlgeq.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lozqgpcq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkeetfor.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqaxyqhm.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2capztqhp.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qdosuhbz.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjywefv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2pybcfhpi.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsoqhoxe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdzdvuf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2bgigufoc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxkrrly.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2aidfavtm.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2teafjdwj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2nashpkxl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkafvtu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyeolpx.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhuagww.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdkeekt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlnjwwp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2agqpvtab.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpoioxa.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmiouts.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxvmggw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfyjdgc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eugnqbwo.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2bgygaiel.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2igkhulpo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlhhihg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2amzmmlir.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2kovetwqt.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2aetqopmq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jaflcvnr.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlohvyj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvwbywi.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2nqiisrzv.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxkvlok.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2okdskmcg.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ollzxxue.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dotxvolr.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwgdiim.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dayhpipn.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xintpmbw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mshrvtch.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvrqwem.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2verppbul.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdqgsyg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuyctjv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2teertylu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2riiqmlnu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpqyscy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2skdopgqd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2xfntzutr.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zozzogen.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgoltgm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2aoabmyql.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbieqwaa.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpfkuow.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2irqpfiny.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2yozprxgn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayebbcuj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfijtdf.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mxixulqo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdzqnqh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vispgjqt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjfvvud.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2xizgysxw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqlvqac.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2tykdpsmx.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2oebivuyp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wheqjeux.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2avtjhbfj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2iavxuqxt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2qyapocyt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2wapwgftx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfsortd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2hatwmoeo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsgwsok.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2wteyxnle.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2mxutfnru.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2umkqispq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgwazia.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpjxpax.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2aoaqwnyh.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2budkdxae.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cziweyxn.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mwscdssm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2regbmnqw.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2phgoztyq.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxwjaxc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtuulxp.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2egzolaza.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrzyclo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2foebacsr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2swwkygtm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2frshorhc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgqwevj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtogubg.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuftjxw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkvyuzt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2iormcgzn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxyglzj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpznonnj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2yorpymrd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqfinti.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2adzqxvlw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2btoneugd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhxhmcq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmimyrc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gizsqtjq.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2gfuqpysg.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwserem.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2utmzuugo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvvqunp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2mhskgqhh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmqbnmm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgesxtft.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2tefthtln.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2oketbsqo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2avxacolz.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2yvytuwua.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2spmhzphr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2arglfusz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpiedct.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2cgodjdqh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvwugzz.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvuckft.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjbdtpv.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ydiqmslc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2itnsnxrs.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtaqzzq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtfotvs.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpilsgg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfywojwy.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtxtpsf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2otuhznsb.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxkeuov.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxezaxmb.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2sjucwmnc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2aopgfvjp.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2yostihhr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dvowblli.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgmycfz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsgkwvb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2fvymsaey.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2fekwvwzz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjqsrho.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwazjum.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjcizpa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnrecvb.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdpocdf.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpxjibz.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbmxlot.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xugjhfku.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2maaieazw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwclhggy.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jugruoqf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2kpiuzhkh.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxetccq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqegzxfx.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpnwpcx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dghaacdv.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxzmcdl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcmwslp.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvopeqr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfbqmco.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlshpio.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqlmkcg.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ujiionfr.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmsomcl.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2swjuqgep.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpyabzo.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bpflfxxs.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkoexqnp.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2plkrwnyy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjvtqrr.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfkdvag.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2noqyhagl.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrrmqjy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2snjpifma.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmnmxab.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmlywpr.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpxdejw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xarfovzc.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2reclpibb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpkpuxr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlrjfof.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmqbcns.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmavmrs.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2qtylousf.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2xolsivma.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2hgehckvl.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsorkzf.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uutdthyi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2udoauxfz.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrhvaqd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2isihdevp.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nuaxtiec.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwthgzmz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2dctvrvnb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkheyuz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsaozsk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2cgywwzwt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwznwulb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2itpkbjbv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2peczraeo.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cknzgamb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2uazdskia.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuubgws.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2reqqdzoy.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nngjwcgy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2jokkkgma.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnshnzkk.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2idwflvqy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2trzwsqwx.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2epusmsqy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2kacnnwhu.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnggcpn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2abxuspte.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xizrmorm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdmndmk.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dinttvdv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucebeopb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfsmxrj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufntoigr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2udqmjfsl.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vcowexme.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqukpkpo.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tppggmei.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjrpiss.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wzietdpi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbyjvxi.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqocanf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kymyowsg.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2okqbtlrh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnbdmje.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2kiiaopwm.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2eloexyau.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnowqbp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejetuvyw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bidraaha.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2scourjoz.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vpptktjk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2buqkgqpu.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpsijdh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dasxypyn.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2adsnlopn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qruxhbsu.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfsjgkk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwnuudw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpiyrjw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2awnauwmu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkobcfep.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2vgiohrmk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2evqstxjq.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cebdffla.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbkemkm.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrkdwtg.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2btjrfncq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vskrkyto.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2fktqefpt.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fmuvlfud.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2enjkxszt.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsvpbjx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2mheurqyx.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxitkxq.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ighpzpzx.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvmbbkk.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcagout.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnhbtjd.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjscdqf.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgxramc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2napidtkw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2nouygmew.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsfqobq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjjrpgv.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2hezrrvox.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtlxzin.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwmbtqy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzruprb.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2csbjfvsq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2snsodphn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvfxrea.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qgccaucp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2uscvzlsl.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2muxymnuo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2jujezcvt.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2esbumumf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2oplasidk.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2etzllqzk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkvesub.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ivuuqduq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmuyfuq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2edqnwuic.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpqouxq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tllliqtq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2usocxyie.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsszjvb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2itekzyhz.html


<!-- 参考信息 -->