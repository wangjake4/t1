代发 wailian999

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cplekycy.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2iqonlmkz.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ryemmrgw.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vogjmggh.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmeztnz.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlesihr.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqpwgeg.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kqigcawb.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtobclx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2abhrcrjc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tiabfmho.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuwzwvb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2mutgwidv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2itwuorlj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2gdeozeip.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsrsbmn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbzdtie.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rouxfakd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjvgzyk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2futsqtqb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zckxktml.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mptqqpbq.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdyiazg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwtfmdp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2yixlyynr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvepozuw.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uvphtdmm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmxmddk.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsbwwej.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2obkwvidg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsgwqdh.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qnktvxee.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2welmtwxv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ddimzwqa.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hkegyqwa.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yovgrmws.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqybjrl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2yaethqqt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyigtwo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vxawzphv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cvweshva.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfzesee.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsswpfjc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcjyskk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvewnwf.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvfvsbf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2etpqcivv.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsklgvp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbiatzq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bvypwxyz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2nauohyoj.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rhebvigh.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjdyvml.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2eboubdod.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofifsmzl.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtbfxdf.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dwusbovh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2heupdkjp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwtkpty.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fmafmfdc.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtupqnv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sitmwugt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ldczfmwy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2fejrjplc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2bhapjvto.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2yueplpbt.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsbgqxl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2isplbveh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2cljahhjf.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgprurt.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nywjubes.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvgkisb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhxzlgq.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txhlscsb.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ytthocnq.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwaccpiv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2beorirby.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2phojfgwm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbbecos.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2azppwckm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzfeulo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2dxyjcodt.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2binwvokk.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2wincvfuq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bglmvrwe.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2scrlirgp.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2feeduhdo.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhbcmrw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbaojdrc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2doqzryft.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxozaara.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2voajqvlb.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2iormaypb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2rotyoqtq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2usfldzle.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2nasjklgn.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtardul.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvhbzwy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2hczxpdhb.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzbqxma.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2scelcfsf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsssxhs.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kcaeinlw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2toejnfrh.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jlburtna.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfwbwhz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2oehawhuw.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzopjsj.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2yezivrjt.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqijspwa.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrydzvx.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xflkuklh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvacoqdv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvnmysh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgwpyus.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbubuaus.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2iiegmvzk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovchagjf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbbpckv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qbehptfn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpnwpsi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgytbqi.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2odqgjnsr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2oalzwloh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2txlzmjki.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgoqjtp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvveatpy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmugjse.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqyqvvr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtvhahy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nntwqfox.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2byulosxa.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpmpnhy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfalzah.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsxpwji.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvcrouw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypuzshlx.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhndzoq.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jepnhnrl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqjrecm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2bijegzuh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwmyosb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2yingattg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2zcumcttu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxjangz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2fusunipg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjshjzkg.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwkgjvc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2btforzqs.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vulmfunx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgpmljm.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxnagdk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzqnltv.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ilscakky.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2haybhanj.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyxujxp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2kikzowtw.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfoilimv.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2yxiatoao.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2osnozbti.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2warsinwe.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sipubxkm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tcethxma.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqlxdtg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvqgsne.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmbrvqr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vkofrtku.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2grvmolde.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsuoctg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2isrcypqe.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkasdjj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmuytzg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2hdghgrqb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsviaug.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjyheuo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzlahwv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqihywm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgxkuxm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrqxarw.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbllgjo.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwvptbp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbycfcu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2thppzbme.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ajoeooim.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2huwmgcoo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zextapwc.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkfajlo.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2hslyshgm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xyyiatxe.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2wktprotl.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2djbpcesl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuimjdl.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2lodrnyjw.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpwzgmj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uejmdkgu.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2apcyqutk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2elovuipl.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdrxvco.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmagqby.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2stayjtvr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrksdljv.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdaluuq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihavlkak.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2aclxhdiz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkoxqgbd.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcafeed.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2byvfknhe.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlbuiuj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuzfipr.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2zudcxqre.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkojdld.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2neobsaek.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpaigkl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjjagzn.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2inqfgfng.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2owwhxigi.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2szgqjcmp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2cssozdwz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpomoxf.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2slisjrzh.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wotquohe.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xacqpwpz.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yesfwwee.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlfxpxa.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrqtgdz.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqibpko.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvottwi.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbxaibi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2axcjqwnk.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgiomzo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqgrarc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2igdimsyt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmajrgvc.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2prdzvrez.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2itiiyufy.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsbkavx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuijexbn.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyjtwcc.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmlynip.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfqmsge.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkrsisz.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdflpdah.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2efrltrsr.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pckzhgux.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wubvkhso.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxtuvun.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqaqfvpo.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcdchfx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvsacaz.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqddoaq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2brbvcksr.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tcuxamxd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwbcfds.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmdajij.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqhwjua.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2mduivwnl.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvssjeg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjaevzw.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2vmarlygo.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2awbqlubd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2urwxsvke.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrsmsph.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bycqdlnk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpgwalm.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhalxiw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwpbjoi.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqzqszw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhoanbzq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2djzxzfvz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyujalh.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hsltmjyr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2lusifwvs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqakesph.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzgtxyb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2risfzeqw.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsoocwg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhbpsco.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2tndugqjw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2toassioq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwjfwyz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhnyurv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhzcosq.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sftcvczq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpwldgd.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gradcuoa.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2uysirflx.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbvflji.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhmbajb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnbnfvh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxankipn.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hoywyvwm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtamecp.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2htvpsqle.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuagbsu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgvaqzs.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2jspijyno.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnwhocd.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqihcbv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2lgparmvb.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjxajdt.html


<!-- 参考信息 -->