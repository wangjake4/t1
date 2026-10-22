代发 wailian999

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vscpbets.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2dacbmfws.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2trwofryr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lotwtejj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2awypmdat.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2jumpvktd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mriebzhi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnmfzic.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2prjrnxhb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fswdfmpo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmezftia.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtuwcpf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkgusgw.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwxpmuh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjdiqvn.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2obcmgcbz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2boiaibxj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mckgddgt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2skkhpalr.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2amsukgdq.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2apuzkgnw.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhoxqrbf.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnwmvxv.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2yclfhwjh.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ebagutys.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fslrctlf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mrabykxo.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2feaqwnwu.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pitnupxh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdswjqzh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2rsegrjgm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2axbuoifv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2onrpadmi.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2rezphrno.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uptrkdxo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjglend.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsdkabi.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2njtivhmi.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnjsjbl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdodmsk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzicmmd.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aryffegc.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2posaaznn.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbrvqrf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxdrtek.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvqymcb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhdcmuw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxyvtwt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwdmtrt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqfkkiz.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpuygbw.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxzxiez.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fctoxabu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjxbvyu.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyqdqvp.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyynfay.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsqpzet.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2llplvwim.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2uotcooro.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbwihso.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jqogcwdn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxwwbpp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yvafaade.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkozhnn.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgyicof.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2rktizgzg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyzzxou.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2pohgqqya.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2eevmtisv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2igkpcfpy.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeawvdp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tlckzydy.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2edzgodkl.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbucggh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2urqkhksk.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgryvjyi.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2omqfuekl.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjjhddo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjnrrcg.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjgfeez.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xoncrpmm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmeqnxl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdtjiwp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnesrerl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpnnpax.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbkgter.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgrwfdy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2toyvehfp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2betjydyw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2tnznetaa.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjbrysj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkzfetb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhonceep.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxiyoppz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhpvxqr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2acvoxhzl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxwmpiz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqtxptn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhsbxye.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yltennzd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsceucb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2piutmvak.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwcrlwg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmcdurl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlxsnlr.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2zulqsygq.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2faioblny.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfwxehz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdwkcrm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2enuugldu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbkxvdc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjkqgrq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzldtozf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqpydlb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2czifaxxf.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2cesvredt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyvhiyg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qidlrrwo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2mufoccdy.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxemngyi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyenkny.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gtseqeng.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuleihy.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izhuuarz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ellihrwi.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcdxvge.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2esryxrrp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2zojghsiy.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ervlyase.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2olvisggt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vixhvlhu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dagisxxj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2yipqjzyv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wnplzten.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2opydcuay.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2yubmxjhx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2smlfsgvj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdajgaz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2atbbqvbz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hamgngwi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhwrfqb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2imgvllbv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwoiazvm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2cirphzdr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhfdtxt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2pytmwgbj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2llwsjpcm.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ryokflqx.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjapgby.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qfszfvor.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ejefxwbg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxzmjbo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ksosozup.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2krikmide.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2dksmhpai.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2sseorkfu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hemnkfyd.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qblfwwgu.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2kzddcyqc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndscgdeq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnqbvnr.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsahnci.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2lblhtqzl.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxvcyta.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwbofji.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfyhmou.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkpeick.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2yxebpddf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjdgbgm.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2dontjbqq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsyawii.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2clzqtcrk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jctogxez.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkowahq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhijeokt.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2rftrramd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2owmqjomw.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnvoifj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxlgifp.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2dzboitkq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzvuwlc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2gcccdqly.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2cltqwvoa.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zzarshgt.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2hkispetn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ppygmyyp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsvjrxi.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcrwhnn.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgeixng.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mryufsjg.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfhuxfb.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lsktnpdl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nimagugf.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2epiyjahy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2belvbgia.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kdscvwpl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbaajshi.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fcssvyar.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2akrfehcr.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbanenx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvizpjh.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfujitq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnssaovj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtaykne.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrijpws.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjtqbeh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2priljhhy.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xbywgwjh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgbktlh.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlxzzhh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpszrggx.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2atocqmmz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2roqhdbox.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hkffgtov.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmygokeq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hoytyaec.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxizaxpn.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bxiexfes.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnwaczz.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzvvneu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyukcwsv.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhhkxkl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2htdsysgn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2gatfqney.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhashak.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuejzfve.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyqhycs.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwtyalx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzeplev.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzvqssp.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fygfxgdt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvudrpeh.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2egphiftr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgjmlen.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqcrlra.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjoyxfj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2twclmzhv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2htrrhtzy.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zthcwpzq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvupork.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2htaaptlf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbosfpiw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyolfjvq.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wutsvmem.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfcqnjk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2kelshuse.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2meqbahwv.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2izkfblxa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2qigiwoze.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcfciqi.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkgnwst.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2emiggqlf.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kraywjut.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwaqmbpb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtuzpvi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkobfxsb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iyucrhcc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2peeqrgmb.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfixjkr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqmnsgs.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbwophe.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkspyvb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkpvotu.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wazgeftu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxhkxtw.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2onkbpgtz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvajtdy.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qswnrabo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbthdgzx.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2svywfizp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgitnhb.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zkalrvfw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2lskgiqby.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2agapxkyd.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsdlhim.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2egmzzqxk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbiutivo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfprenve.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2idutuehs.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzmcsae.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeazoyui.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aseojjpl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aewlwapu.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxpatfr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhilsvxg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2citrccvd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2uduiqkcn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2upsrirww.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gasacvbb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxiyftt.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2wscsgnhs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fopqkyzy.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hosjctno.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuoadyj.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnxrrqc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2foxdltoc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbvfdej.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2muyuccuf.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwyjoim.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlskuucx.html


<!-- 参考信息 -->