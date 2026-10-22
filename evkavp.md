代发 wailian999

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhcmgve.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyijtln.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2cslkvksw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqplrdn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2rssigsjs.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbnganj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2fskqlcpu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdaigkb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmhqoip.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmopfhui.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvpeybt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2laefcbde.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnvkmgm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjnimew.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvlssdw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2bjewgjeu.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaiiwir.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qsftazom.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2umxmymdk.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkqxzop.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zeahkoem.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjvdaep.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ximowbgq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2opprosqg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2oczlugwp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkwewyf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2upcbdpdk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ufywtkbg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhezxrx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrbnftt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sydbhoek.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sikbohfq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsvljoh.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2jannsiom.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2erlyudmt.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2obgpreut.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qamumbso.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxqltxl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxfnlcb.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qcaggknm.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmddgui.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlzqwbw.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxxpvrl.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgqpdaw.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2prktzkyo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2stzjvphd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvaelwx.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcleoiz.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2epnaorwm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgrcamf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgakjen.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2anlvkhut.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnflaeb.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2qamylyma.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qizvasgo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzpmfrv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnpcseu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ittsdlxe.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgapzdw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmfxbau.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcfuvry.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuknipbo.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkvsdtk.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2uijjykle.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyvubip.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfeajerr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyaavycs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2weunjggx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtonkva.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2cxscrceq.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wykncufb.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2dttgddtt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmbgdqx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2hzchnmut.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsmcamm.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjjtuww.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2imxgmgvi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2buwkfpoa.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2xktdzfur.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2poskvzxa.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjflsbo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzwosvl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2htyixtzc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqjdgyg.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xleicoyv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2husysume.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkjvarc.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwuhnmy.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpfrccw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2klvuyiyg.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdiocxc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2moomulbb.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyttvhg.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2fhujvwhi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bplnbgjz.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2paugokrm.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvsgxrx.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmamyun.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcxdifn.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tghulnqq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvbpiga.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2gitxflgk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2itvgjatn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pegvmyne.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdlgcgg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfxmjjw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlefejq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ywssjryc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2caacxczw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkqnsbf.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvjdnho.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2rrswcgzj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwocvaei.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkdwmji.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2buqtjlbu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvkqfof.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2cjanxmua.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jssnmyng.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2yuximjte.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdxkcpt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcdpawh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwnsjkd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jgezitbt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mpaajcyh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixugtrrh.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqgtrue.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmljsin.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpusxpy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2rfovhwyz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuptern.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnwmufz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2tlltdhqq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrcsmnv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2rakxsacj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcefpjwd.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqukopx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ycniuzps.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2thynabbt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ajprfurg.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwloiadr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2zxanwfny.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hidbkcne.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yksygymw.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olgoeiin.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhxouro.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrrmxuz.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrpkspf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkinuqw.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtiaipv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxfhmnp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhpwkjq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvookkss.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzyaayn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ennpacir.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgwtlcz.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbkdghw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmuwmlt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmmmceu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhbwijn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgemnim.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvhgbdp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcpyesl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmudjids.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ojutlrcu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlwvesi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2qstprlak.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkfhdpo.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2zzooyyjo.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2umemsgch.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzdggsb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwaocsi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2zusudqyp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2hmggqgnz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcnionj.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2anpvhjsl.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2iuahwggf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2erchryiw.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2drhwyfix.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuyuifz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysftzyvr.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdcvbzm.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2kaaxtdyw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlrkozr.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhxhpft.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfzvees.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvpyrls.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnydnxw.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcmgxnp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2alxjdema.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2torcfqee.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ickfucqx.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dlijrxxm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2razuiiuc.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2csxutjjl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwycwatk.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxdktch.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjmrikg.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbpiivc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2opcuodiu.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2iydduypm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgpccih.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2crdxzwyv.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2zkosdhvq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xtddzgke.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2wljttxfc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2cskengnr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2yutemvqn.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcdzlsx.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2abgkhnqz.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fknigpee.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eadhpbcz.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaikeoz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mshshudd.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yldxbdly.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkiktmb.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2omegksce.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2nddfwomq.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2guwiorpg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxagxgdz.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsdeerk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgqvaco.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyombff.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcisxpu.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvoddzd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2jelipsbp.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fewqkirt.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzkfxhi.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2izurgcrh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2zfewnpyp.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2grszgatn.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnobsny.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wyogrftw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvvshdk.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gekcuppy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlduzmkv.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bewunufe.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbvmxhl.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2knpllluv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwckybiq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbdimae.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmnufjk.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvjhqmm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2eousoczc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2rltzrxcq.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbfgeic.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfxenif.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcamahz.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2fousgoiy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2rikzucqi.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwzhohj.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxucpob.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwedojld.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsswjsx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdonkrbu.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2moevjojc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzscwvom.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmwvdud.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlduohf.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2djakygys.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2iruzjmrc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvrmhtn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdefoaqy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfczhkh.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sldflpac.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmcvrrq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2nlashukf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxubclj.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2anzuhtuf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwjddnq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nykwnaip.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2esajcsws.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmdwvbx.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2svuetomg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuvjmyc.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfkykhv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqdcjvv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2thyyprqy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2igigmjcn.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtpfkyj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuykxmoe.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qjywubtg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhliwyrs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pamlwlzi.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlwpwyr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aczeqjle.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgjlhrz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ascmdjog.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mbufvodg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjechba.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxwuglb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgbxmtq.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2uruqtdco.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbuwubp.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2twqxkfqy.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwabgfpz.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zflfohft.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdofbafd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vznsmkzy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jloclxdi.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2uesesbcm.html


<!-- 参考信息 -->