代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ofotvurq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2oejoabxd.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2sghcyruv.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwsablo.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2klgrvykn.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfeibtq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyflwbs.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2grtrpfqo.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhxhrxh.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2tddqqmat.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pphqqvel.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nywokxvy.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cxthirqp.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vcangczu.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxxyvfo.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qgugdtbv.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vholwlgz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxxnlgv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2avhvxsjr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgrbzdg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2aiukfmem.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkoeqsk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqbyrpt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqmehrd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2iavcvphv.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kjblcjnd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqoazfx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swgecqwy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsofltq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcroabrk.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twblkfhq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvjpkof.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2himwakzd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnxseav.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2magjsnfa.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjxkwjk.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnmkygb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2glylwuap.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2axutfmwh.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vopyejjv.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qvchisbm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyomgsj.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmwpzee.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2chfictxc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnnzumu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcmywvp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkfhyyu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2grozrvln.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtvwumb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jinaktue.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2shpeotju.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmpfgym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgnjvbp.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2isoodypf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2detcjbfn.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqixsgh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgocdhgg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2darudpdg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2oveaitbe.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hybgzgdq.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvuyqks.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcweqfr.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnzeqwa.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2avhvnjng.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2irexvdun.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyyjsft.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrsiqgm.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpqbycw.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zowdllpr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkhzvbp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2krosrqtw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhsdtdc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2aaiwuqii.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2lshexvls.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmrxnyn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2npfvqlow.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqlrqap.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtxsewr.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjdsumu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2wiudxvdy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tznpdrvu.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsybrlwq.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pewtbalc.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsedxizs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2airognhd.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2swhfiqfd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dljymsiq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnevzid.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzoondz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2lipyztbr.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2luobgxas.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxfzbwv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2skshmcll.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnmmfci.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrejttq.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmblavrv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2dteygwsz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzlwfog.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycibyxvx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfllgbza.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2amymlqhn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvclqgmo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsxyrfs.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmjmtnv.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xmultyzo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ppskuvdk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2mseulfry.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2mcilgadc.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2rmighhkm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrhaahh.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2taqjvspu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qufosjsq.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxaakwi.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2eeewusxb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqmlsaw.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2epdzqhos.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzjyudl.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pcghejwv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xghtpwoi.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dmefjfzw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2plxqbbxl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2dnamxwok.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfzmicj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvdlqer.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgnyevs.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2juzoofov.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvaxxzdp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tjuxihqq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2alzqphvl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwaegdh.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2trliqpic.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhndfyt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2atmzglnp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yymwxcpd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hawasdjb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvbfgng.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nycphuud.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2sifuxdtk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzmrsss.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2umulthml.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmflkel.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hexdhmin.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2pggczzxe.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxudbjo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhljdyg.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2unsbokey.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2oprnwrub.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtswonh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdwnpou.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuynhgq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbgqruj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2tamnwuut.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnngtkil.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2egktqvxs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnbmlaf.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2imuepoml.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2rigpgmcx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hstvmmdo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqphchm.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cesqhbks.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2xynceoko.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjedpoca.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbibwrnf.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gufishms.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2zokorvgp.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwasyko.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lgypfrod.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2oddqcred.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxvvcmt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sutpsqpk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ickmijiu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vatsqkma.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiiicbr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfvodib.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvhpeqb.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2avupgbhi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2elqvltpj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kodbnncu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2aimyuooa.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpjxuws.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2woohnpyk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2lapyuwtn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvcftnf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2dasfnrom.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gidgkcwg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlctjqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjrjhbl.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2txdrbdkn.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsmdmbn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvshlzr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkjamki.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2xmshdhxo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2olijezrf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2znaietrg.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2azwyypzr.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2deapamdt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tekjildc.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2brtgzmpi.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmcwwlt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2gocrgdrk.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2bprygicx.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2wszbnyzd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvphbmyg.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrrvqzw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2odmstbjf.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpcubrv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcdykfd.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2kezkkbal.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2crxkyabz.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjzimff.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2svqnfttr.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bgaachkd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrhseqx.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtxrqyh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksplxsxv.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpooqam.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2eawwpvtr.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwfcssd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqcximc.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2weflzkdb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2kbferhsi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2vahspwxm.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2fazaynml.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnwgjym.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2mecszpan.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2suxmdgqz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2csxldtfj.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ghslabml.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqerncop.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkjaiyu.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzovmnpw.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2djdtxsxo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyijdlt.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2muoaaoat.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzcoooe.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwhysrc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiebhxvm.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vpirbbvg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpattaw.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2whbdxdxm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwifmxo.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2audkltnr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjeuzgem.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2mnghtcib.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2tymviqvi.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnjotlv.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hapxromo.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2isrjaupf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2gluhctyk.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlzmcjg.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2daaphxuc.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2uocxocpm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzjwquj.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fiftzcwm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2twdvkgea.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcpkfah.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfgnhuw.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpnjszc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyrkvdg.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2igqqmnit.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgamrke.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsctran.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpufncx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2baeticjw.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkluumj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjobsvnx.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2aoealrzs.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2bujwukcd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2cadfltks.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxiwgzyx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pmptetmp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eltfuway.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlndvgd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxgdjxk.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zacfusrp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxdaoll.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzqvqll.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbjszbn.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzntrxts.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzcmewr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcdmqom.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2zpeicmjj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2sedzvuml.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vnaykeqd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkgmmxl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhukvhe.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrvquaf.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2aduocaxu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2djsiopdw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2spwbczid.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qgduqbnn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2jleowwdu.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbkrfna.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixipiipo.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jftstlez.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhiefkul.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyrdael.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhtdxxz.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jguqbfkn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykidghtf.html


<!-- 参考信息 -->