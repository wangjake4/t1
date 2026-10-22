代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2eevbddmh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2phckbzeb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2drcjfemc.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfwqkfx.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2esnqunfd.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqletwes.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2fehqszta.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2dvczxcfn.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ftugnzse.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmsfrsk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzrlplz.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2prvwieef.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rcaodqfa.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qarlwwkt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzxrxig.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ghekrbch.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2beoxvznq.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2sjizrtlv.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qydmsvap.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2apkreekl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2alblnzcq.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbgvlte.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrhkydc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfsvqzm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdxjoqx.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmbbuox.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdojkbn.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2osrvrosh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ojusbkjl.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccawzihc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnjrozq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2htgbqfuo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2krahixgh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzfmpyt.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnvelta.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhxdygo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgjlfxw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2coameokv.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxgpnwa.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2itkbcdsn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2svwjfbrt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfnazko.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsszqblm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfiunds.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kevufgtz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubckezag.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hporgieo.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmqptif.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2stoetokt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2olqmvndj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnnuuhn.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2yvixwlkj.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2enpktczo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qtavyhfx.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkxbobd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwcdkay.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjgyekh.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2yphosazu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kijqbqzb.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ummrlptz.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pedwcihb.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhsuzvt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ybttesqa.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dndzmxcg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvoltpp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwldelc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofndkahh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvmjjhr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2msghozvx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuwbisv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkroilme.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2awudbfdj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2beruzyfn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpdnogg.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mgexiudl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2vidzadfp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhkotiq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovitqury.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqxuznm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyvihlb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfqkegb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2anqagpov.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dwswnlak.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgcmbdf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2tohxzouf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtqqczt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlzruwt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2lutlhgrd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2eabhnpjo.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2miagyhuc.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xcohdpjh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhdiiye.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2serjrqiv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjcbkvb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqfpjoz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2lpszioko.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hicakkba.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqplhqn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pifbzvii.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdzarxg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2zdswhgmo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqfkftr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgwqvse.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzbcudl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsseihd.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlptchii.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vuunfplc.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gioynfec.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2yubzbrsa.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpcbfmm.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xflzymhw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgygvba.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2grnvhboh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2siogszsq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2opubruwa.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2njcvoglw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvioxbu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2adphjsfa.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fyarwauy.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjntovl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2uclwwyvi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqolbwa.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ymimcbvf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhidgux.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkqtlzf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtaqisk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcswjzqd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvrejeu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvvsjfb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2hopaydbs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmvqawq.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2subqfuyu.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzjxkni.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2gewyyxna.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2relcrluj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2srzmzlsd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2plqcdwxv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhecbjma.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2pnajwuxv.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqbtjcd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jwffhyui.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2irwjoouv.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2xruuiicp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2fivnnith.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkaontpx.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjxtkou.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bttkixwy.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qhenujgx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjgapdp.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ljplinij.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2szldreaq.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2lwiqafyv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrztulte.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2oztcaqyb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kobeqfqf.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrpthlt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2koswbbva.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kenrjujn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mptiuxrb.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgwwxab.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2eruvbxgb.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvgovim.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jmccsgbn.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgfmalj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2zyeaepdr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrhucxb.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2kygjyotr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2byghwtsy.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2kevyvodf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2gfabbqlk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsiembiz.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2csrbstuu.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqvnads.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tkngwnic.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgowwcp.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxyepws.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnxouaj.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxhtehx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2jufldiqk.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmtumfs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqenwqgx.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrwrpfs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekljhlqx.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pweygmzh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvaothdw.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcpsesz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2jijephcz.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdchatg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgppvhrt.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gldmxodg.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjexomr.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yaehnipu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2gtimppwf.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwidjiaw.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ludsmyhq.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zetaadgg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uitpfcuz.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2txhyumzm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2psocshtq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfbxazd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yeetewpd.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzxrdnr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlskxxar.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bpisimdu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hspdamvx.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nqglmusb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmlkaew.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvjbdec.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ktslnbtn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwqhxrj.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpbspzy.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2riejcgmt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2eobcvove.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2utsbtdox.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bwssyjxr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrgkdou.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzsuffz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pixmbeet.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2luwtmngu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oclfbjtk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjsjbck.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aowqpvwb.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcizagd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfivkfr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aizxopsh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgugbzzb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhcqppk.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wxskzyyo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfvssev.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2weajwbae.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2agkualdn.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yflyuaxr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2htpfsyml.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2iykhkivj.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqqkzxn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjxiwug.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2trjyjyba.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzctoox.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2avrcovaj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2trsefbsc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fcswyzig.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pirmnctl.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2anspqoyi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2brybgpbg.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iralxvoo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2pumjarqd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqijgok.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjfkiih.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmufkof.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bauraswl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gfaohdfa.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2oopejfwx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eztvoxgp.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2bnharkue.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vinqxmst.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzmcfss.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhzjllt.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcazutb.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfmyxdm.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsmiulq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qajxpeko.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfqjmfz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cngphnra.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jdejwcpm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlfvlco.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvuvktn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2awifwaxj.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvxkgss.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yckixtvx.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcxhdou.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ditsabiu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhhjjlf.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjlkead.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwquubi.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjrspbj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjpjjmg.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsihtuq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2rzueeghw.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvkajwd.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpmexgd.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxaicoy.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlafsma.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqlsvgn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxavsxso.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2hsepamtk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2axbiqlnp.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcytbkm.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjiudqf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnigoxwp.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2swhpyqgt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnnldox.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2cljfzxpy.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkenlpwa.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzjxhye.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2oikqwsdx.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2enminsjp.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2icccvvfd.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcahujl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2njydabbz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ychbtlfy.html


<!-- 参考信息 -->