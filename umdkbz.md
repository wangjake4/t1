代发 wailian999

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2eejrzbcq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfidrhtb.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2augoypqj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkfxjeh.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrjdvjc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkhebie.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlqabqt.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzkiytd.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2anyxfnnt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcjwswr.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cgckeccv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2setemqun.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2roupezkz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2blmychmg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlgnnav.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2awaxqjbf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cyduyfkg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bimuztbh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwlmgpw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxuoybv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbpudem.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbprkgy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2etopehgs.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgmnmxn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxebmlv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxmhjop.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2kugzeivy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2oxscfljn.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfiyjygj.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2iukbuexf.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhnmang.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2qynagkla.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pwujrqzp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqriiwc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuhjpqr.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxxnvuw.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jjikhpqb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhdspko.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2keijfdll.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2tmscwpug.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2cjupeijz.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgnauao.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbdhrlb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqxdtwo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbixbmq.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2cihqxgdy.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hplwzwjl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2tuchbdzl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mikbcxkt.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzlgazd.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsrilpg.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2iaswpzpx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfqeiwp.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrplgrby.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dloyvdyt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrcnedv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsvelqo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2lyexlbia.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlqmbld.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2osnbecou.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhjtpsz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2aauhvzin.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqswlsx.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yatzqdia.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2hsorwxye.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2svkryqab.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbcbcfl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtmzwji.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2naqjvkyy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqajpun.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nkeywerr.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjwhnmo.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuaqxrt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2dahaczcr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2vhejxtyf.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2bjupxoij.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvqozox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxsjsku.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrxpllj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cbuzucpn.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2abjgbwrn.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2kglqugjw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2casnxyph.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pinnvacw.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcmdygu.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2eoexaaja.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvghufn.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uedylalg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjuxpws.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnyrjzk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsorkgsc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjeqqdv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2elzlelcc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpepiqhw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2irnrnkvq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwpmhkq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvfozxw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzvrdto.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxkcdax.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2lypsdwno.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2gokmapzk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvjmjmk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2iiaylriu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwtbnas.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qytvoxay.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxwrypf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ebctroyf.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvscjrn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2cncjgyva.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcimkzh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2znevtzwm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlkotkh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2isnljjxm.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2xymwqekb.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrugamm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwaruzb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpswrfa.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vkeocczb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ncndiabw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrkmlld.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lquvdlnk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2kkljavki.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uldvifke.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2lqiskgrf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2klkgvfuy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wshepoav.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2muibikvq.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvrmkdv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxcbkqf.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzaxloh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvghftk.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlmswjb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbkitrz.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpgiazq.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxytxko.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2lakzxhqj.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wyutgqoo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmdmyuo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwkzycr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpxqyed.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnxyzoy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzkvfcb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mgekjwkr.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqbbpsc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2oubtetcr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuxssid.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2gvskvtqd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wflnzxls.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqjpizg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2uaysoszq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtvvygt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2lueyxysd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qskpfsbh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsjzxfp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnkscoy.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmeokzu.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2plyuyhmh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwvzwyh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ahndexot.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsebtul.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjvlliu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ommjqqdy.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhyiqer.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2yfunlaoe.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtcvtrd.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtzywto.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnbeclw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2egjcmxfu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdmhrhl.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyvupuy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdatzgu.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iindihhr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdtfxng.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2punmtpez.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2onirgtgn.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmadonk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhfknhr.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ooglzfrs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxaglfj.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2quzoirws.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgxinbf.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlnztmh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxnslux.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xjophpyj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfztfro.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlqvjqg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xazpvjrr.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2uojfpvfb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2spnenyjt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhjtriv.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2wjisgjrw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qiedyehm.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkyamxl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyfvzrs.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyopdtjt.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ltauxtwo.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmicmqmg.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmzeiow.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfyknnu.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dlizoncd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhiheiu.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vqikigve.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2esbvawiu.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyshzxv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2thzhepxb.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wiviuetn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2joodmhft.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dhazzoaz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxihorej.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hqimqgmp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2liscdqnv.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgbjyra.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvemvojj.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2utimobzy.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyoknacq.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lirgnjfc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2nszxgjep.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcytmzs.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzguhbwf.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuacgkb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2csosixdo.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2unzfqaeb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukexesrf.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvgvmap.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcslfzft.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzlbktc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyywnlx.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrlfljp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dosqrqer.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2befioiuz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2emajkvna.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmfpvkc.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgajwpr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfojytj.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzsveub.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ruujkktr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqmafuj.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrzcdxc.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dcghaits.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsplrwnq.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zyeakuir.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2icsnmuqs.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vabsjfyi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnlvbin.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhodjgl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwenxxp.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2haruvmxw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqfkdti.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnittul.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2hedrxtbm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvczjwb.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgjogxj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqwparo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnxbnzs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bksstpme.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqgcjpo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwhbimb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2oneznjcu.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ldoechef.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcfvipm.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtbjmwc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbomxqs.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tqaxhyzb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2trrbdfmd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsxjmeu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vombsmkr.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzjldil.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgnmzri.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyirqeg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmoozpcq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcktzxr.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2chvhgbpl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmtayhp.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhbapju.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2liwkexre.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uchsxomf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejowbyov.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2djnuadsx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2drgzggbt.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2msblkiae.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpyufaj.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyfupcb.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyvhlxh.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxmmmpo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnstffm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtnnsvo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmxtdcq.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fekcdxyu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjiaiib.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2isxktchb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfymctx.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxvcaeq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqrotzc.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcmigbk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmgveju.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmcmpyl.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlllcqp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjheezc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2pccqowex.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzezfswf.html


<!-- 参考信息 -->