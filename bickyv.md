代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2twysshmq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2umappbzr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2svnmnseq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2drxuuoui.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2neybeukb.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2btvplkwm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqxqezv.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2yabrmkmp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuzftly.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2suctqvvf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2bixsfpnv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2appvnkez.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nepdovqv.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjluzpm.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlkkhpl.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2qemlycqu.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnzjbvn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbroiilq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qfykjohj.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjhbekm.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2oghdswji.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvywlkd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2grfendde.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnxitvg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrlgbln.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhwcheo.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqmhudh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyjvmwg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkkwlst.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkxkutg.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlafwgf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbizacll.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsbrpmw.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dikojktq.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fdctzzqe.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbdzolm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2wwywsbkd.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxqvxqy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2deymcrji.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyedkbg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgxpdez.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2diovacsh.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bucolhvs.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2odrkxhcq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnrxavv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2egoimymw.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rverafps.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxldjcoi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfotkzrw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtecnts.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnapwdjp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsenvsy.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2oowqgqhu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2gufhtfxu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2njioknmg.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2obvecmxo.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2azapewgo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2qguijoww.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2tpphqfdv.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2qfltxfns.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2cyznjhhc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eashnisu.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oiupazji.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxghhdw.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpavgqx.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2zamsycqx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2plbvgpyw.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2npdkgxcx.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjbygaa.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qybjbaxh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tflmvfuf.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pdebwspw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbthsckc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2iuilsloe.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibssazao.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsnwfzr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2tyngvqkc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2awlvekau.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpoxltl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ueiabmoz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dclfhamc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2bowsiidp.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bjybiwvu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2bxswjorx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2epovnkzf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lukcospj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gofbpswq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2skztiwxg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2grufdqfs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeppcfoo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gutuxgll.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eirrjouq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfanycx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xaafrjej.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrllicc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtrfvnb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzaybzk.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzttpjqz.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ufngjrtk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gyaeoqgu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrbpchg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2etfzddpy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdxtikt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzjsaea.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxgcbgh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2mclapxvh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpubssdx.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxwjdnf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2qjljabcp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2npvxkczv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2vpleucsb.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwehtedu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmvgvrx.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmlwgps.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmuoqnh.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmlvtlw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfuzlfj.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ensxqbms.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjsyzqg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2diniswxn.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rvaddpsl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2klrizexu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qitrlpjd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iltrmgxn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2kagxeokm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ronnklmw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fapxwimn.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2eaumjwky.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwoimtfz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zelrbswr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlxklox.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqontgcx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2vedisuri.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbrspif.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsfeqta.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2xgltqswr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxqoawp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2szxhkxvb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rucvovro.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsjjdoy.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2viwablgl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2upxnqzfq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuqtkgn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2sdufqatk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2tddbceix.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwaiwhl.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2baiyffbw.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2imxeqvnz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tknuweed.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xgatsvsm.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsvgimq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2alwrhwct.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnxvqjy.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2mzysvxly.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2enrfoqfb.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uxiifsxx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtkckem.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2fpiqyena.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rivzjjzp.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfjycpd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2izrjtxqh.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtvdzcb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfwwnhd.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kahnodvz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2foxnnxyd.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2drixuhaw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpyeysm.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzshbtk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pnswokdl.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyzxybf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bblwdhsv.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2zimrqgaf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2gximbgck.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2khctrcdy.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2harcprgv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxqkkum.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqzilav.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2rimetcdi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbynjgow.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsjtjbd.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpchtsf.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2adxpelun.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxcivjo.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dnymhlyg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ielkumwd.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjvlxao.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbdfhgi.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqjxbiu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkkctog.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2umabrkgp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzwybyj.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfbrodu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzeokxea.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpxrgnf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjuntxfd.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2fhazlhnm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvocnawg.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqzrnvd.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsepouc.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbtyapu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrfxqlp.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tpujczkn.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpjaoyr.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcwjrsj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2katksmcs.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2czbfjlcb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqihizb.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ungbzbny.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2abghwxst.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnqhpet.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnbabei.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjkohrh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxqdypi.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfhptkt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwvtagv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2bklyykzc.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgddope.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2xttqeaiu.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2etdktlgg.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnmnyci.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2kmutkgxw.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcrufmj.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkugzap.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzhgkjh.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzvbhfi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yibjlxpc.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lefptoum.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjlxhoy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2inmnydhk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2efyekgas.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ligwqjgh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2azatrmyi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxipvhx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2umgdcoss.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfruvmb.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tunpbyxl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2azpcvmkp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2jcugywkm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2isakydoq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2isasyinv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2nehsiomg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2konnyryo.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gpimsbbo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzztwzt.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2olbubzcy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxoksya.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpmuuse.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2itbycfes.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zqchuqdz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtbgsvn.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ykprbrdv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2naietijb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvhhrdc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhvqbos.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2neaskpep.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2istnimfu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqioooln.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2neaqrczq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkcvqxt.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hkodaoen.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyxwxfr.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhrgxtg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibspjwtc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2uloepxms.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tehhkwuw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjzeoxo.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2cofybomh.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2sypltfrd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjaxmjn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyacyul.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvfpmkm.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mncxosne.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmiiperi.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwwstak.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwvaden.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2zawrawkn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmzudgy.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fplfsnlj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqsxnbt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyibafn.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxyorxg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmezxie.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbecjky.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzwadim.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjibhia.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgohvyo.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxbcntg.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2gelprrtp.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2djnbrxvr.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmoaubhc.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkxmzsl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2dghkuhzm.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2hblwngro.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2apsvgtii.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmvikrz.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaitbdx.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdwlqjq.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtgsroe.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2qjugrytu.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2zphqcybm.html


<!-- 参考信息 -->