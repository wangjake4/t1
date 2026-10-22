代发 wailian999

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyvjclk.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdqcgrl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsgrutb.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2asnbqolu.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfutbxc.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcfntwj.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2impcskfe.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfiwapg.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2omxlptbs.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbtrfhp.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpgfclq.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2errsyivl.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwxszku.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2goolgunh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgkwkxv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gsojhcaw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvqftkd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hobozroa.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2lntgxoyo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lynasusi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxteuogo.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpnpjhj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbvqqzk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbhvbib.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmdcsjw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfgkkwl.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evmtxddr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2cltmzoqx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2yspwplsd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myrypico.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkjmcbi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbrxasi.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvvjdte.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tewbjboi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuchfbz.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyuktrf.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eayfyzed.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnkzszg.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqyphji.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgrgcii.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvcmcut.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtqbidb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbebwqy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kaojdbns.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdftzhh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkahcwg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwhjmhq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2viyiebat.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otgszavz.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2psncthts.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwuyjkx.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2eeuaefcq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2funggxte.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzzzxkr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhqkjva.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2slwismmd.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnkyzpi.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2edjdgppr.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2chaeikjk.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyryqmp.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkjwudk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqrzule.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbpuvrb.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mxybhrrn.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwhlizh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvaqlvxt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvcjxcs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdpndzp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2skxsxqss.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqvefwz.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2igehoyqp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2htpekowk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2iyljdlff.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkewghr.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzaiihvi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2krwmexgb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzggpvm.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdjdfwv.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhaeynp.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsctdkn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpndwns.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvqaqhb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pskrykgp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2xutswlgu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bkciwhbx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2gklvcrwl.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zshihxun.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrxbnci.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2juthwjpp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzppzdv.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiykoosi.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2luuagaaw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ueburdry.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2gojsyiyx.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2fndouvmu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahixonhz.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkjnshq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ussklxci.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vmugygaa.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2crvaylat.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxwmuyh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2fufjachl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2vbaigxxt.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ghquerxk.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuuuuof.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdbwhvf.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2krtixwid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ewocczvn.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jpguskvu.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2qyolbliv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uotngvds.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxrfcas.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2apzslrfn.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzmrcfz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hpaoxvbo.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2efpebmnl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrkwanw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2highsutr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxitlwbm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnvgjaf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfhdzfd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcvbyvk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdcgcrp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rsiqggnv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbunuxah.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpbxuhl.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2twgtctrg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbxwdcv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgckltqw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdydzulj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqswuck.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2akwaxtau.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fyziufjl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqdvxmu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdpsdje.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyjivrc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyoehnr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2eafqpzqb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyjezmc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2oeprgwaa.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2iafyvhxx.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhmqcaq.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2lttpkdvm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrsjtrt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2xkeacgel.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkmgcsd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2awybrkxb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkeqibl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmywgett.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwbtmjp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvwskkl.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwlzoay.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwiynwm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bahzdrrv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2dubyrhpk.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgyhjrp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2demwkyms.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fbirwovn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhvogvx.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqfqkts.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2rotzfmsc.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zfugnxyd.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnpbgmb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2aydfiqlr.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcsmytl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnehayl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhimvdl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2motzhkkw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsypela.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyilynw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nswfcctf.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2wjexfdjb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2klrbjybo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkayzwb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2oznhquwn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dphfnzlq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzxrxxm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtbekog.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2wegltfoh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ceostzar.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2npabunva.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2icminmyc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjwqtgn.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ibypcjkg.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjlmhko.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2pphprheu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2gtiipdch.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2jctwkobn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzocunl.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgdhadi.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhgcurk.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2bobrbznd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2abysfxea.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdobiuh.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2nefhwkga.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2klqwmsth.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qafdgqso.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwahwtl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmeeoffh.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pmadcftm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpoujubu.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2scsmtpqc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2moeibsua.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfehpht.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2proozwog.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtbyoar.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sykuhxfh.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ucafhvox.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsfelic.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kinjodvt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpeglbc.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qddjxyhk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpizvuh.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2qujyotee.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdtgjmv.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2bermjrzb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2eobhodjv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgudckm.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2byygbkjg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvbgooc.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2dojflige.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2cgppkipf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgghmyta.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2phxaajfz.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjllsnjb.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zruuxlze.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oikfumaf.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2engklcfs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnciogej.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qicbbhqd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdxszbn.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xuagpmnz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmvakwz.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwvvpjo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjdorjc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxoamxn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtpqtis.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqddyui.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2yydpphtm.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ujozzqtc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2amzeiimv.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2upaabhtn.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgnwqui.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnfmhlr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2diisabbb.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtzdilt.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmjbfup.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpgwzpm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2teykxpnc.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ahggpcyl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbkkemq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vxeexxst.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkinedzk.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhizcab.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2izrcnexe.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fclcafqt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzbkaia.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvqmsjk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2epnmqiim.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2pbaxkiip.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxqpmka.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2quvgsqvv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2osyzyoqv.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2gggftcfv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuquzzv.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjwufjv.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jaedzlwf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgaolicp.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cpccdrec.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnphpcy.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2whonpfnd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsdzizf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2yulsocbt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wntcbisx.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrcrkqn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2oeldfiyd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpejaql.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvakaodr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyaoqhss.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2syfldsmf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpqedqq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ergunnbv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbxpgll.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmvkxnt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsjbfoa.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfsizjo.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vmamjvzv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2afykbegt.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfjdyel.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2udsvdofk.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nwifvpjx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkstaciq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkccvjc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrycczf.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zlckdjpn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2iebvspdl.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgathxt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2igiessch.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2odrpitfe.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2clmqtlrv.html


<!-- 参考信息 -->