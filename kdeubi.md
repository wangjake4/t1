代发 wailian999

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjwuvyi.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwcnwfu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrjroaa.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxghvars.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfeyxrl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndeepmeg.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnlgehi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdjukvd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuavyfp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihophwaj.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfsbtkk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2zanfattu.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ehuzdbsc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmxlypo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkuypxq.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xctisuof.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gkksxfkc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqsdyxk.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlyksyq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2degbxgte.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrrnjlg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2liscitax.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2natawsbv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlycbgm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvkdfyo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbudkrhh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmtxkau.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2obwrqnay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fippqihe.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2auippyig.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2utojukck.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjvubpt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqomkur.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbzhdlr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjhnbmv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2nsizvkzx.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmbakno.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzgcosy.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkqvkjw.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2srslfcag.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxjjjza.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujraovkq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2naswulkn.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpycsca.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtwggxj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jphagxvi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtljjes.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzjrpgi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdsynjh.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqznbpp.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcqkwbp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2hayeiens.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqinjtj.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjnfihj.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqaaxpvw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvxvqlm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmykncg.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bctyhrqx.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2eudzuimp.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2fojucwmg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2glopdjgo.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyltpzhh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnwqwsm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2wicimyds.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2caivyaww.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2sbncxmdj.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2njkcsmkd.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2fghuafhh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fecifvht.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2zyuogiam.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyvfrnd.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xueovqpc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2okoedjyq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhhxhpd.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2iraufzrt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yehawpvr.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvwnuex.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmynkwau.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjtrbdh.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjjlvpy.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvuuzdy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2yikoqkdi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmxxdoq.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2rqeuetmp.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlrfwpo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aacwqaxl.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgnjsig.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lokqrxvy.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlgqlwo.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2qellvrwk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqkfdul.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtqbboc.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qygpspgd.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkaapqnm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lndhiyyg.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2flofqzvf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnykhqaj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2isikiexl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2byfvrhji.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjwgmcm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2snncxyfq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdeoidpr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2kumqirnc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwfhcwv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckesjsor.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrbopnk.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnemdep.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ddveoubw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2stkyufve.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2digsaoxf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyitvtu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hioneafe.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvcnmkj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsnvdno.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ltisszgc.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxyzwjg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2qllglouy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xghvzmls.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnckkfa.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2etlpovsg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2oknvxcpv.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcrckrb.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zguhfekw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhybqjk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkpjyat.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2amuoksye.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrtqzbn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2gukswnil.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzilrjxq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2trwqtcrg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfniaqwc.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2xumsrnht.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2lynxxacy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfcwfbm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2otncwtle.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2epckwnnt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2eauvfgkk.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fovikdqg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpnjoxc.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2upnicfbd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2darerwra.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrgyrce.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlbkhug.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2axxahxdh.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhpswsd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2daqxwgof.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2obdwhphc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzpugwp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvlfjqd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxqpqfh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wriqfuuc.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhmayvt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2phkblhoj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2iueicoyk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvmyhbq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2afrqglgs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2urmzcpil.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2tetzlbxn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2geqywsio.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnlauxs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gplilego.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2dlskotav.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyyiwhj.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2dqoelpmg.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2vngundug.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2adqmquxz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfsbyie.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2abtllpbz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwqslqt.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqrhuto.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2rttpjivx.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxqluqr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsjoejq.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2eumwkqve.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzwiukn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2uippwrkv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkffuszc.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2zuoguqja.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhufslc.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lmiasfdb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbzuigx.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnimlbf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmoagvzi.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgwnzuj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmqdsft.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqogezf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqclsgu.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2teahycmo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2cutfchuv.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlrdcwg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2csdthhbh.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bphgmzom.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bloggdkc.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2qgugrqta.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pgknseek.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2pvezgvhd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2snnmwjxa.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpisfwy.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyboqpo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyiirhv.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbvwftm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2cphhecry.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2shderzju.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ccywafxe.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2isoiijjc.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qltkhqkc.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2snlltryd.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2apmeilsq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbyjfzaf.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmzkgfz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2fwktqxyj.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2noiegoox.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvwsbhd.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zckapihb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrtadud.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cchyrfqt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrbfojs.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmoepnk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyfhvjg.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2kvokdqlh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2idygaigv.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhiytru.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwleifi.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yptgtdry.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpnodhl.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2uidbsnjh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnowcnk.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwydrsjj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcymfopb.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnvezpo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbtcpms.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqeghmy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkmxexz.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wtodefkd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2trnmuubs.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2suybncrt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aughsmab.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhavsie.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgxdsdg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2cikgsyng.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqgzkit.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmtkano.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdqtawb.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmlrxra.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2waildcok.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lflwohib.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yogwkjbx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jprutfyf.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nuoxcugf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdwfqek.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxgevkf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbajvnml.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2znoycecz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbusyys.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pafirtow.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfaclrc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjprpyqj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrkfxwd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ityzldmf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2odarshlf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2cspkunut.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyyompq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qybrbiao.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hchetanx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2hyizieis.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxejikdt.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jizngams.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2asmeocem.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2laucscpv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbcgufb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2stdabkll.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dibwkefi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqmnkjj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2uofugzqv.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpsvach.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmusrnf.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzmwvfm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2utcfgfqr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmyjplc.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kfoghnap.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqowufl.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vhldvgrs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcuauhu.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2toqypwng.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjzlhcu.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2dniniaqk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlfrqgj.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2beapsrpu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfvscmm.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2guadvizn.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuchsabr.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdioeap.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jaoefvxj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpzufzp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvlgqgb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mnspniih.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sctllycf.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2awntqqql.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gneysfzs.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2jemxajvd.html


<!-- 参考信息 -->