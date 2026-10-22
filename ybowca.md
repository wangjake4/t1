代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2npcqpssc.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtgztxo.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnavvnu.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2acodmaai.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlolifl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwaiqat.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjvvcaa.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsrgnud.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrzdvcg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlcivhq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpiyvyc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcjvppc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwohfbn.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2kxksfuky.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tfquepvh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2wpuetsxb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2usworjzw.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2flhblfoh.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmctaltw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2otfnmdmj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxspzij.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfgyiaq.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpepfxk.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxokqbl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2gurksews.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqfaagl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhuczxgv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2mglwljvt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2igupaalc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ghimwuud.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnsulze.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2flkryfok.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vputlkji.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjinzsg.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmzydid.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkfhlgy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgznsvzj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuqwcja.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jigcfrfq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2phcpcbnv.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2henunlno.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbseiats.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkeyuug.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzcodvp.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wedkhayx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjuvesk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjyczkv.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ooufenkd.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkcbprm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjqocol.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbmvmpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vefjngsw.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2cddyyzin.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2hmeaudig.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvscrse.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzeseidt.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzqreqp.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvxnyuf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcxxxnq.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfyfvzw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtuqqbz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2kueuqbhy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjljawr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbdtoyv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2kerjcdte.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqqxhar.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqktjosr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2aaumqqnd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pucldwkd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2gijcwsjk.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdnudhp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2clrlxdkk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpuurmi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgoxkrp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyyzkba.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzaakoqj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmthquu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yihtdwzz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrvcwka.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcknddd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtvutdg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjhavam.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmnojbu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2gaitvbrd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkjwcyc.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpmfyji.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvcuvqi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2oymqwtuu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2uexipevn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqgvuis.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2eweaifhf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrtpkfl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkfaror.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2oibynpsk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyozljn.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlqdeoh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfucmdk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfomsloh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2xnblwovg.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2omwmadwt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2diafubsp.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2baaywoyp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oliaeopr.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhspwie.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqojtoek.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqocdfgj.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsuaswu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfddowd.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhjddgi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jlelkaom.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmvbyks.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2twkokrmw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwiynjt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sunmyalh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ocorumlf.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2iulojdaq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrucsul.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2skowsxwp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhalcac.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2njjwntsh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2syjzeaqw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2othrmdky.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2wehggbtr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsbxevu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2grcblgwi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2yczjpwpw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jjktqffo.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxunodx.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgzvfbt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbzkghk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvdptsp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwspvov.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2yyeqjwcg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgccwcjf.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2tarihbdp.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnhedso.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgpwhoh.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2heccmtuf.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnnrgqb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdzmiek.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpnwggx.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjjulkl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqksgmdu.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zjivfwtx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhrxqfg.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfkfrlf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjohdsdc.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2jrigaogg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2uljesgzp.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbvtdyi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyyksyuq.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2uormxyxt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2znhfrcrc.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ojakanta.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqqlplv.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwqwlvx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ymepkhky.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkkjxou.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2iktepwfu.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2sglxehye.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vdupohms.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2zywxwpie.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2heghcjds.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lkaccnrv.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyfiski.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsorelo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2pftbrzbk.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dndefycg.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqgrsmj.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2inhotsjo.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvzgcwt.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2balouvpo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkqvoxu.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnptaxj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2wqoptghf.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvgsyrp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfjkgxm.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vntohubo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnnuncy.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdnozbx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlexedsy.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oadvwutc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdsdyee.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2knqbyueo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjskigix.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kaounrtf.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgpuuoj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2uxraetxo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2sfksjxkv.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hthaikfi.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2buunnnhu.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kcakvlfr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fezmlhcw.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzbxwfi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jljwpthc.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxsdqqv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaxhgwj.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bckvccnu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsxmzhb.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtmklrw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2skizmdln.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2edzwuwjd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsthmabx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxyefph.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vsapptph.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2evyennrs.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjhpxkx.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqfsvln.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjgqqqz.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmllfgjv.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdxumsu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2typmxrui.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpupsew.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2flkgdoxh.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bswgsynn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqlhhad.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2inoaufbc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yleiwvlv.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hovdfpmi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2npcwswiz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoduovdz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2vykdxxop.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhclbsk.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjhopdp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxtpbym.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmmzkxb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2elvlyzdr.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqxnhlp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyomkwx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuiaizr.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iokhbxmx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwltioii.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwfomse.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2urzttygd.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fyatfokk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2esixfxli.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hakvymdi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrycxzp.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oezgvcbq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2svkkzajh.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rrflwsnm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2asfcnxgj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpckfbyo.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tkywyhkj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdylitss.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wamxzwqs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwggfii.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pphdtlrd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkcxhzd.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcyiwwb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxpgoxt.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tdidqdxc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwytprd.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2yydnsgbo.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrzemvv.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tynmnrke.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxtcvkl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2oknqmtro.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxbucjc.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzyquyv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2egyaycky.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xblelmcb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2peluldau.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2uikqcljt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fswccihj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdfbkio.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2shrxjaie.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqficcrh.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgewhwg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dprvjhyu.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2gywxkrmo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmshwip.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2szwwnnwq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2hroxjqbw.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpvhjuy.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbyqeyf.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuekxxh.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2einpxzcb.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xahynjgd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekydrwph.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2bewbzteu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmtkcog.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2sblihafb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhejcmly.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wefpidwe.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2nligruux.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2kglwmkvl.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrxonyx.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpebzre.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2djwdzjxn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrwedxo.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zckvtxcw.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xutxvbzj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtungur.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkajowb.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmedhtc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcpfelc.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrmcqqm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvdrkft.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmaahra.html


<!-- 参考信息 -->