代发 wailian999

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2xxybdmvw.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqrfeos.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2mudhtsyf.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2uiypppnw.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgaboxn.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2iipmxywr.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kkngpenl.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxeertr.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnwgkij.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rhealquw.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2drlgmcra.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uyejpsaw.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wgywmfax.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2toghikib.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvyovns.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jfceocbd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kcggejsy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbrwfyq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nllcrwcb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzjhpje.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2suujmigg.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2juewzfxv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvbjonu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkknukfp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vltzjoqg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2scvfgghi.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qehloxum.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzifctx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpblgcn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhgizfj.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zprtktrj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2twncdnqi.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rlonspnf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjoczef.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsuednq.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvsociq.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uqklburk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkervoz.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtoedgo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjeewec.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ceawmekm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2opltvgco.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jivwrizi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvncgpj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvfavbw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2higimlcd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhpgbpz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgwryhc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmfuxof.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2mluqudyl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mebhenow.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2toxbzdds.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxeunvdd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2axbcokox.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2lalclhzk.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2fushsnkj.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wthdfvgw.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdrwuvj.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzjywgk.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvviysp.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsqybvx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2awfgohco.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2spotinse.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyagret.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rarmboim.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxibkgy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2jaifgvql.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2atxpemjc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyefpbg.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkzjbcz.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxrnpog.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2esthshfi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2dxeffydt.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2msvsobna.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxupkslz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkjigdr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gynodfac.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqrrrse.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pojiggwl.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuybopz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2idhzaiob.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqhqtrz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxavwel.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jdiaszxy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcawvuh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2wiutpnuv.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzejdwp.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2kmeajvyo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgisrkey.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2anmcmanw.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbewogi.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzomqfww.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhpbale.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2hodysnwi.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2umjytiis.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2opmdtjlw.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2latfjugh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2vziqyywq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lctwjxpl.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfgjwrc.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2cvobtffj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ddufmqkl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbkppro.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2nyktnhbl.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2adkeqwzk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xycsosxb.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2diarxkup.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxjbqdd.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2blnwuini.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2kvilfqef.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrxknhb.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwffety.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhjwcgg.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvrzini.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2knrsauyw.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbkvhci.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctsrvjtn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqcptyh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxshhdo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrigbvhy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2mxanvwse.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxsosah.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2miyuqpdo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2shjkntmy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuvdoqi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ehabadhk.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yobnstva.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2qheueroo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2epncqlfj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wteaxlei.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nstqvahw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcizjmdn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjnieqd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2opclvpyz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqzligu.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uiynbjca.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2topcsebr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lypuqsah.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vshnvkvy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrbznuj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2evqktijj.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzwwfvd.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmqcifc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ldczkeww.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2gfznpxmx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ctywfngm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2dfajkdco.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2yogrsgac.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmtqgzh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2kjiujyeg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2psakqskc.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhjidvk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2lobjteim.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdzkpcw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ysoilpdc.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oghxblvr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2iejjxnqh.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2enstjkik.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fluukpyl.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmjyswr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2zosmfzae.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlgtasl.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlxutvy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnvsstp.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ussyoezp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsppulg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hjioatnk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kftdygyc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnrexpx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2orsoixcx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlpcxhi.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdzggju.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2iddgmfhg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsweveg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsdljlu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxdhqmp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2rjooybev.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwrjikc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2laqyxigz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2zitrwxxm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2luoidlnu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2yztjzntg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wblhooci.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnssncj.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2szcakbpt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2zojcolec.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgsouhk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2oyozwsjd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmjonjv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxdznqj.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2lbetrrnv.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2byefwpbw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2clgviahz.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2sjoowzsj.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmhylqj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbfupyw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnatucn.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnmemaw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdwltcg.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvxjeoe.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywccexcf.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2bhswjloa.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggttgpgy.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ichwedgu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkrvfrd.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqqzife.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfldzirk.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvsebrj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnpsnrt.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2doiwirtp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtphwfgr.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tspumqew.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2llnosbwk.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjdxnvl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qbglndxr.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfdkkiq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmahevm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2woefasku.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnwfxua.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rhitxwsd.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2qaroxkro.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqgolhk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2torahmqu.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2imhrcivl.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zapnferk.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mdiotnvi.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2blghoogj.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2paxdxnas.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkynmqma.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmkpwoh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2odcykucc.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uspfyzyg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2skevpcbm.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ermyikse.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2marndyxa.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsafmpq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2aejahvht.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjdixlt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulundybr.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2vwiiruzp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2pctxiwvu.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kftvpxvy.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlrqwwb.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjewatx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ergfljxn.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bohvymgf.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdtaome.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2npkrafml.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyidrft.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtnndkl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ioofhehm.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrbryqf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzredzfe.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2irmmvsig.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zozolier.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xpczlbtj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aberbqrq.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2voiievcm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qldtdlnm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2lgchxthd.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lufqukgl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgnqxrr.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2zybcqlws.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2tsubhtfe.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuvrdwk.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2itcymixk.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdfjpyx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxoglstp.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lstxcfdv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yffzdnrm.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnkmgur.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cztssszh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2zlodwkbr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcmnbey.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqxlnev.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2rccfocgj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuagyes.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyydkgm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngihssav.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iaonfdnd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2htwphksl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2egjmyvlh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2crfzvvdl.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ddiuvtlz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ztasavlq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuysxwf.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kquwbpwh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wumhvwly.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxeqyoo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwzwjpz.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwzlloi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2paltssjo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uxctlkyr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbmjlma.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cyabyryw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2jommiexu.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ohaxtcno.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrwbxvx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeljdrgr.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2smnybgqs.html


<!-- 参考信息 -->