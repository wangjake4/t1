代发 wailian999

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2uychfael.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vmumvvul.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2etgojxqu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnnfrik.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsakhii.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjmvflw.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlalhdzf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbullml.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwymsdfv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opvyhkba.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uzstyggc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2iymezgla.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfcbnui.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dzotyhtk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kaoieyua.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmunktf.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzwwtda.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhrbjvc.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fhekhiim.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhpccmx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvexrfp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbdsslc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzmxrjb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxbwhdw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2janmafxm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2btmcmttr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2saienlbs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxrtdhn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfjruod.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkufrii.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuutwrs.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2brboicgo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2phwbrzyf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lantkaxu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbeevhd.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bwetnjav.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwobipwq.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqucqxu.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2wriimzut.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2shbbvjfi.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcebugx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oauhdgjo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qttyhuad.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbgcqvv.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2flereriq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqduflhb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2bberoiua.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2icrzeogc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2oqoedsaq.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2gelvcvhs.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2swdknehi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2adkwwsdr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdjvida.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwxpzbj.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsfefqv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpezbsey.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fumcgttv.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxxaygf.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qamjclwq.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhwvqni.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2njxugdno.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2arsbtrkr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ughahyil.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2aafodyze.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jpiafvgz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2hpogzxaw.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2slxexzhn.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvootkq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqedsen.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2xiehsxxd.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnkvklj.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzewkkl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcyefbj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpvnyyw.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsvzqku.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyxvojn.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnlofdn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2wiybtuix.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rtreaocz.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqmjhde.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzkwxrx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjvmrso.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2eqttwklh.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2jvskadgg.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxzzgxx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzvhukx.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgnlcij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fhflrixg.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hzahzvtw.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2chqxxrxj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuevxhv.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhwbbfn.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2susphjaw.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2skeaoobq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2swsxdafp.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvzantr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhipxsr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2xovnjteq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjefyfd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggamwvtd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2enlaiwjj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2juyzibdv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcolfmfc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrlfzcy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiztiotg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2awzivzeb.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iznjkzdq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgibiwq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2eefrehym.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2atouyser.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjitjnuf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpryqcnb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlhlmdb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzquewa.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wamhgcfw.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mbypzvwp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2wbywcvgg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfmofnd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjiflqc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2kxiwcasv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfxyail.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqelnbl.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqyzcmp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqhwpwh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2wurbcoub.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfpgjzi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2kmegtnmx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2gwigcvoi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bigfkjwv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmfikao.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxekawsj.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfbglof.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdvcihv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdyuoun.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2dsftkcob.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjxtzli.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2qiynbvex.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuzvdhz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtcpdlh.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkhfgns.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjdbhwu.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ettyviys.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxqtcap.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2jgllellp.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsadibu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnrhsse.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcuxdsy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2emscakhm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2smdxflan.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxfseky.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnptfsr.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjssete.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2sckvmwdc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbgikvt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2nycwhpyv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjzgbqp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbzlwvx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2yvygsmvu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ponuvnvw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjwhhgu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hasavpdb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnkxdpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjwewmj.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlwjwbt.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2lciocjto.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhoijnm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2psxlhlcy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2obwjlwic.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyexbiz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtzvtag.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsynygi.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjnqkum.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2erxukayd.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjaryoh.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtozzsm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2mevckmuq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvbjrwt.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2kawdaigg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nckgrioi.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jpupdzzt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdiurtlp.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2zqamfdiw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuiyjdiu.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqqwrta.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkmginm.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2lthbshjr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxomaypx.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2oifqqvrd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfobmefn.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpbbgaq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpivhne.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwuegof.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2utxwrlen.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvnwtbv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxxpiti.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2liixbbii.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmxjqff.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfojtih.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuenbke.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfbjeem.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlrwopa.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjwmhve.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttokjbva.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2otragxxi.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlltrql.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgsknkj.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmlnvqv.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aoklixkn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsclytbo.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnrbiks.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmkupnl.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfrzabc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcnicdp.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wtausoyz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxgljfy.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gwduyumw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2doeeryoy.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2idqhjauz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2gngbolct.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcyvoes.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjxxqvu.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdllllu.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecawnmpb.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2azuiyrtp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyonici.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2yokqlvxi.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpaxdef.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tytkiitm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdpjsmi.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ydaupkdj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyqompg.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kzobbxka.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2owdmtbtd.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dtydyala.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2psynquwe.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyfevrc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vavfyrqv.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrebqsl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcgnker.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2dexgtyzm.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkhiiwx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhegtho.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2vewgozvb.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrdzwfg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2vyonyjzq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdhgvqf.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjrftlv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygenvwjo.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vonhyhyd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqqpzom.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ekihfzfm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgelksu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkrduhg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eiscoani.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpuivufq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfxdzku.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhmshdh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjaioksq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppukukuw.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2giunmlqe.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ceatitzf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2dvakseep.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qedrjdqe.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lqybdmwz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2hmoousdr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdowoyg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2atowlhxo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezoqdwae.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2asqdadqi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyyxalv.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rntmipkd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfphfrh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pngqnmby.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfvxznb.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xylcvkkd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsuofem.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbkccda.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2uswietjt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsokoiey.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qvoqgzpn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2euvootsp.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2krtnwmer.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdrjifh.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkqaeqw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmuknzk.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2jezavifv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxpotvl.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvvyoom.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2eekfbxwk.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2leaorfmz.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2msihxxel.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqpubga.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuidhao.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2aemwgwah.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbzwghl.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yduiyjsu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2snaqaipd.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfzaqzi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnubovdz.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjccxot.html


<!-- 参考信息 -->