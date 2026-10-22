代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rsudhnsh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoahdkca.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhdwzho.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gmebqcwg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpxyvax.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2tvawqrns.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yhctgvqp.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2izyubheu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kyciutdz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2abfxmkew.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2zopmuymu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfgiucw.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqonhbfl.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2sovszoyn.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuaifxzn.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbzruan.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvzlbiz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2soguotbx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpnoqvy.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxlphfm.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnqdoqb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvovwbw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzeevyw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2cmydbpqk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2paxuxlxt.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2cierveck.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2drcydjxn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2vdghpyfb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwnmznu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgnohpk.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gectfgsd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxscwey.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpddkfo.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gojzfclr.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hascsquy.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcwpkjt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgkjhlq.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkcddug.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgprlprs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxdaymx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcsfsvp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwzvxel.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2clgxewig.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2djkebvyv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzoonbik.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ekholbrd.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pczndpgz.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2njwofjcg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgclvoso.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhnzyws.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2crqjjgrs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnthqjuo.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlxgrgr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdcunec.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdgqssz.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgjwwif.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2prvvhzzy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2demzkrmp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2omdpkvqu.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrjygky.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwplgtg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfupdgg.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtwwyrw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2viafodnr.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhkgfrz.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2rggxjqsi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfijgcu.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2obclpmtq.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2yynmebio.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwfiwgd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bsehrbwb.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fcljgryt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtytzxmr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2oybqexnl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2bogenmvb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2opkgrxvx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnebkpi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqhsbts.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaiittyx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsftyrx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugiqidjg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2gbaeqici.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzjgkth.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmzobcd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2eoojscmf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2auvkpcxl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpbryjc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2paovzajw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2azrroxon.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtlymwc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbmdroq.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uiewvoxu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ahozfhpw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2nnygmikh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2hnywwuoq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fseavutt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgedvrz.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2utjctvye.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxuchhr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mulutcvb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcucpla.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2abfycptl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsihyhy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmsfthr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqnytnz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxjienm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdxwdpf.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2izhenxbf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2anbdgghr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jatuejnh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2csxppgmm.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqfewth.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ggebedkv.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqsnlzo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rckfneqv.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2etmjxegl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrlzugn.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awqqghjt.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2svixrqwk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2vgygwmfa.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2obnimcqu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmukdvy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsrfyvj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2itiyzvny.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2wbubfimv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2chgapxie.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvbowqz.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfqfvvm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mivsxzbo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfuqmqb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhgdubf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnoetsc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwhglae.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrrsfbs.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2trinodpu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2jehtgcwb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdlcipq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpuihku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yjblupiq.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ugazkvan.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2qyuulrwg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyztfjn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2goatfdxa.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwuksej.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2zljpmhlh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2whlmkquq.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmlclkh.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2hbepqvje.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ekablvlm.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lodbkkcp.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2sbddstcr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2eivcdsut.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dglvxurq.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2yqaerxbq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggabuhtj.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zjytqmhs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2eifhfnyl.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2tlldjcnj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvtdswa.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2aixqnopu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2arbwplqe.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkjlfwa.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qivxtbxs.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyhuqsf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzrcpxo.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2afrlkeqz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhxscyw.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bfksqyuq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2shqhrvbz.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2xggiwegu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfpypbk.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhcuswj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzwpmmy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2srfrvynn.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbgxyao.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ergidter.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfklndyc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2slsxngsf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2zehfkvbo.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zamenjsu.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2psbkpsfk.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ellexeot.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2olhizraz.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ywaztrad.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kepvynus.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ncveoxqr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2cqoeyunj.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xfubyakj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2laccwzmu.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmtenqa.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbrlblo.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2subqwnfs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2twpjolmv.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qycbdyhp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnftzbbt.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqsztcu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2zncnutsx.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2itfgsvxh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtihlga.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxborkg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuxjkbz.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgzhnfj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oolszvyy.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2slxzrmqv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxosjzn.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmkutrt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvvpcvy.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rydyxpyy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkjyvdh.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2izmwzcdz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lawrdchs.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkhgszo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcfmnsj.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xafmyzuh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yajncrap.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2xpozicxr.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2aiaciamt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2lreqmwrf.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2astabbyz.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2amwycuoo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2gabkdyrd.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcmwupf.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2voywariy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oebohhwp.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgyfxrt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rubezuxa.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrdtklx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2abqkssvx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2gagigofe.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwghkij.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2otpmkveh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxgtmou.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmemeajm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2nirlttxr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcvnjvf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2buebafwi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2zsawlvtj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2nsertous.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbuicmg.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxstoum.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdroydi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uofmwujq.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2banhrohh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2peonaaqj.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnivrns.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfvbvnd.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvpivmo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebquorev.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xmeqvyiq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2njrgpfhd.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gzeplhtw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2xipuibaw.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ouolrzdx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozguoskt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlgprdf.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nemvtdci.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnayuito.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2scrxbnwf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwdpeeu.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kwohxyjo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2chknyfcp.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ttggxyhh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuvfmam.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbilmjz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvmszfw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtcjagd.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzepikp.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wiosindz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmacwdiq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvrisnt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2amyyxjho.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjalaay.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjqkobd.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gelsbdkv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2joblmhmz.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2vcirljci.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrctqtib.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgtvsmj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2gsorhrgs.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivroihft.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2eycjjxnq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwppxsn.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2efegcodv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsafodg.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uecbekoy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2bzldlpng.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kqagoehf.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwvcyyb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kehnugsy.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2dygxqezx.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zywcjppj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjmewli.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvhqtez.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2peihavsg.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnthryj.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbumnepr.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvmdjdy.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2lptxnsod.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2szibssma.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rufsvhud.html


<!-- 参考信息 -->