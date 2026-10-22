代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmnvvul.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrtalkk.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2aiiwzrkg.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnmxtof.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwwqgra.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2qddeirmq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcgirec.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2amgqjjcl.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuheeenh.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2tnoseesf.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qpndygmc.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnwmyyd.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcjgjde.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qqisoihc.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2kqikcpee.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kzingiwk.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2drhmrexx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkvtiod.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwiysjw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzeipvq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcybzyw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2skgglgsw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhzyjkg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gqommaky.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2mswxryxy.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwszkhg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsimejt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blveinyp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2picxcoox.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2skybjvfd.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbizaww.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsbsapy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiiejepk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkncsrqr.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rljzgphg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2uyonesdv.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwzipqp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcgvqlh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqpfvuk.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ftziudsc.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2auhqinmq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2cskkcwod.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2loogvobq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlsfrbb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwxeauw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgxufuy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uiviehma.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jimojfrq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbggdpr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cegckhdd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hovxmctn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uypusaru.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jlarodqm.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2jqehslfa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsgwygq.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ossaqlpa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpsxtse.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2adflidnd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2eshtqxvz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bamwxjof.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbeapkdu.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2oinvhftz.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2udivgeda.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxkaspc.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzbselm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwukmmw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2opxuuiln.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2psqucrwq.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qjoxesgp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2srstfhlq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ihaxexxt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2feneznzd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2klenxtch.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2cktqemgh.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2snnbfmjm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2thxwdciv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcqpgcr.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyuisvn.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sragowpj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2slpktdel.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbjhscp.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqjhhhb.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbnvlwv.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdgmrzn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzboyba.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnievlqa.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbdxjhw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2buuofyzp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuqivul.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2funfqmrm.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzstkhh.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2aprlxyfd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xabhpkdk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2llomokbq.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqyuzby.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmotehkl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlalbgzu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpqkwkf.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2kytyofhn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcaghvoo.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jejjodyx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2dksqriyb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eopmnufz.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsbvfqv.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjylnyy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvtmmff.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2obhgtdcv.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbvpzqt.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqoppzv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hkoiuhgs.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hundtifr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2faabdonf.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2uoecoohg.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxtgcbv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsiasqw.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngutyqzj.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2voupjjwt.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2elbievjx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvtlhwb.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2umkjtblc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdybxcn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnfultv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2nksidect.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyzprug.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwttxhw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrntlet.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgieukuq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rjksqqha.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hotxgzhb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2asyhrtoo.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2waisppax.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2upxgzspl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2anidnwev.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuuuysk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dchpxgte.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2urbpcfzw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyhduho.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzpiwdd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2scdueiju.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2txfjkxcy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2sadndwvk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2cueyyllq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rronrdjc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqqmyur.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2enhykald.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbiguakf.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdasfbi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkzzvqg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzzbrpo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2uacyggwg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2qeygzdfu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2eggcmgwn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2doqkohpk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2kuetiylf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkcwude.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2kithejff.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2vnroveur.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdtmikv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2okthvigh.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rozqqobh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2qiasklub.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcblqeb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2foncnoju.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qejuyebg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvbnlam.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqrjliv.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2slxhgsvr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2widbkahs.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wehgasgn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wbexmgwv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2twezlhyk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjefbma.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2mvswpcuk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtqgood.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqnaymg.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcfwqdz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrmrxmr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdafwkr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuamoyn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2umgpudqs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtqqzae.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2buojloqo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgvkyug.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2poqyjqdk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2twqhsijo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcondgx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yddhapzz.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2duyircfo.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2spgoozis.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrpivhd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kaahmblh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmweocp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsmpiym.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2tiewnwah.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2iaeatiyn.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ytveleld.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2uanstjju.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2nobxykjy.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbraind.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2zytpcltr.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2poeefmlw.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhxafif.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kutulacs.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vykhcgkk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsnpkxc.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2alqzygxu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmontoo.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2qerhwjwt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2afgftdtw.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbhlefa.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mllogxpm.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfaqfbv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrzlvva.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxmykqe.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2znmunudo.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2iupzsahc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzooaur.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2lknpfqpp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ksidqfsm.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmalfmx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2qbuhybcu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2vxturoap.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2xcljdbzx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hxygkoyv.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgpgwcx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2dzztynsa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlzqgpr.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2epumgmzg.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkxcawh.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjzuxuy.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkefpnrb.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lffyfpsc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tngjplru.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrdwxad.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2jovfldey.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2deezwpap.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdiqveqd.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgwwhgy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2geuvjrmy.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hprnoxpk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cruozckh.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrdkbvo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsnhabn.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbudpiz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmpugnq.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjgvimo.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyyvfzr.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cepxoauy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2waobiivk.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ovuocwss.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfssknrd.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qawfnjgu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfdhbur.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xockegvb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzdpfpz.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2aozfhkzt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjawzrw.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2flswygwn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnqrhqp.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmqxcef.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsfxbxu.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2edgrdqer.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkktpice.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2evcbedbs.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxgdndf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2twkpxavm.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2edlgzokh.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2wvubuzor.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2qoptqmld.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgvevtx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tgploqpr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2niquvtpi.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdwqoze.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmycpam.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ertdzvmp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mratpdeq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfqyihu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijapfeld.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2btxmjlpm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwppowi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2acpyzozi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmftvmk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtvhofc.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dpowbnxf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2witwjlrl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2crspatpk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjvpdou.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjusjtt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2yjphhpcr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vctwywmz.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqhslqq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ompyzgta.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaeryfz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbetnnj.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fppqpilv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zngdkpqv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iaalhlvz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbgljci.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vqenfgjn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmohmou.html


<!-- 参考信息 -->