代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzxjmph.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjelwvc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmarhub.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvwntpj.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmxnbyi.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfmgbob.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbijqbtl.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpvkeqa.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2epijizfs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2deupsghq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2heftaeea.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hltvbaaa.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pducjrih.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2trdqhlfw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtylxyk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2frtxpgxo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwwsrmg.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2gazftgnr.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfvhpul.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqedknz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgpimhr.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmrxlxw.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyfenll.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpdouhb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmaktfi.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dijgpgoa.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2dassifve.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2zaagjsqn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2xpggulmn.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqjwjyu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmwnumi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2gdymrciv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2oknaplkq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdczmml.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pztulckl.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnpjqoh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuycawa.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbxoalm.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkgmqet.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqjsoqz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcytwxv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2zovsrnnk.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuadwzbc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzejgck.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lycavimf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2omnrgljq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nyielfbj.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2upmhszxn.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2esxuoamf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ldladknp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2gouyzdyk.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2wtudtplj.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmkfwtx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzfnbjb.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gznzqvdd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzfgrae.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2szzfcoie.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2pifwgsro.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2urrslzfh.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lyocpkqr.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnwbrhw.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2prtjenek.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2klhxwibp.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbokwfe.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kldedycw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2bpofwixx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjounqty.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxenbxdh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2zxegqquu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifryjmmv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvikzckd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2iexxxxce.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sytcbsrd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqsqitq.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtwtqxd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwicoxjw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojftvnwt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qldtmdec.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2plwpftie.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsifdmw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2cejecobk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrgkvfa.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2osrngmvv.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwycbfk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvhruza.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ditylxsl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwhwkhu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2demoarjq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2juutjpzb.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2mejeyndi.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2puxjqpzl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdlzrga.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2guuwictp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgwzome.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyavygj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkxmklw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2efddrsna.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2lcutvfrt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuirldk.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmyzoou.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2druuupfc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtgrsmj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlhdnwt.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ukimsves.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2exgbqaim.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wsltfwdl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcnyokw.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zktomouv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkgiwyr.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2giwfptgk.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcmuwlj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2cxodpqnm.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2krmrwkck.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2okmhttpc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2atqwgmgh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgmrnnn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2hoklshqa.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2emvoepkm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lifuhlst.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2fgthsbeb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzdnhki.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfdozcl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2oebantxk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2svtslgto.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2crzljfmr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2hadivkpi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxkxhbd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2soakiqeq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2moqvrhwo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2vphmbspl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2btphewul.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqszqlv.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2pkolpomr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hakagzff.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zzssdhel.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2afbnjoro.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2gnukjrdv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmmxirr.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwpqkje.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2knomslim.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2abzeplgx.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jkuruouo.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ywckrjdp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcossuoy.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjzmzfs.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2uexxhoit.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2omqaofng.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfyxomg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hitpmjik.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2lnndzomq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uibzqddb.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2nymshmrp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2phgkzwdw.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2tobjaugr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbdfpat.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rjeqdjfk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbhbjkx.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnzhots.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsoetfkk.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2apnmrwpu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsxkasw.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2xjstbjvb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2muzlaccd.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvowycv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsbedzv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2llglamjx.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxngxrh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2isbpkfuh.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhecdgc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2sfryitgw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbimyhfl.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2juiqpawh.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnvaqky.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2uyukkrbf.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwvhyng.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpjmgvd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2umvukwol.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oftnkgpn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyzbugz.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nkevycfa.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfneldx.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwltowk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymybvdoq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2euocjyqr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpbgfry.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ishnxnuf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2znlxufsa.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2banpelqd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgcjtjt.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hspplwxm.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2avddvifj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxyyual.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmsyrvq.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2aladddii.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vumlrbts.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwphwyyx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxuwgxu.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxtqrsa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fufkqyba.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ijezolji.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsurdcik.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bigicrzx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwonmnxz.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hqprapxs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfgtdju.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2stqcgofq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fejucsnb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2guzhwttj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtgjudo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbtwwnd.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2niqrkqzz.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvqrmih.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2jeisbzxo.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2thatqaaf.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2evhlazxm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjzypjj.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aiefknyl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbvjhex.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iihmmflm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnezifm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2nlspmpjc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrzwukz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2osnbohqb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcscogc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pszzhgue.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2glpduyzl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2sougkgje.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2knylygpm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2rkooyysx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2nlemujnn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvmezkc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sqopycek.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2gaoyytyj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zybyxfnk.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvxtabn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtabymlu.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ndulgfcm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiiemcyv.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyiaydj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dltrsdru.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xatlkxgj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2peweskgl.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2snbfbgkd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2swgawllw.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yndirxir.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2eainrvkm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqhrsjg.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnkhjcp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ronaavfz.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tmumbfsv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmqpals.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzanxsi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2myywfjey.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2yethcwbt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulayrkrj.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsrqmbn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqmzqep.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgsqkov.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2udvxgizm.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2piwhtvdr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubakczzm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2otdrpkei.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zonikgww.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbrwcbu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmekzvrm.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfckiqy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwgadke.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkjedxv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzwpcrt.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkqhpxu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfuhdxb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhowicmz.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlqheac.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjxjjhb.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvbhnli.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cypovuiw.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jihbfpfn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqhxguq.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmmgkeu.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvihywft.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2okvpdqwj.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzmygfo.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwfkujz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2hacdmiby.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwifdci.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvobdmcs.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrtqffq.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjnnhtz.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdjdrdn.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2owclivnq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgsmojw.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mvisrlfa.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlljync.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2chwnwqmm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrytnnz.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqdznlb.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpzvywa.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ybplufhb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzdlmwf.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kaucazvh.html


<!-- 参考信息 -->