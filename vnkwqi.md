代发 wailian999

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2evfkgvef.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdsbzwf.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2brskeubi.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yggcuoet.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdcwzow.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqjnssh.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2xfefuqye.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kgloqjzd.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2htxdsexo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xcunsurz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoxqjwi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2puevaxjy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2uvedvcst.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2onelwedg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxjhgeb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2obyhcogf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2knfxuuav.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcetfzo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpvfgbh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omxzbjux.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uabwcksj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqzinom.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgygkep.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2kevbqrhj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2slmhjqfy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oobceczr.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nltnsekj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2sknjadjl.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wguttxzx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjgsavz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbcpast.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjjfpbe.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjgdgvk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2aszsqisk.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zwesbtxr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvjnnqk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrstcsm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvohcbsh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2yqisnwzw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2adoxbvwj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwsjxbb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbheqyr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlegtxdf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2njvwxejw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgbeluq.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxgqgmm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmotomnh.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyatxge.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2uccygvqq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtzteow.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2kackashp.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2knwfgypz.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuetnmg.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbcxwdp.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmaqrju.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2emhraejq.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ynniuiwg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rijuclhh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwmbvjv.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjqtehq.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdjdqww.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2utrrdtvb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2phcjthot.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvslced.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2oijwtycw.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2xdctshlf.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhkqijm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgzyhly.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2vicuhwaw.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pbubziqu.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qopsliqq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkznhunz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2niohpvam.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkyxbby.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2uonrijqq.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxyodti.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrilgmo.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvjpizs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqwbilu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2atltwwcn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2suxcqeaq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2rinrpobe.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnhmueu.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgncdea.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dktmnohz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2xlquljsv.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxukxrmx.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2raueiomx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2mcajfuwy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2njbrvrod.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjhutqt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kddxerhm.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qibpqege.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2famqpjol.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2shygkpia.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2laiyvvgv.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkgukrz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbyevyq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxayrzc.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhuvodb.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2gptjmirg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2snnddewe.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lkujchgl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2puooxpkp.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2pwehpwwa.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvowapq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzwfaxg.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2clkmesvu.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pptqycmz.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wikkzmpf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqyozkf.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qveopwcs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sruqypga.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyzpvzu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfosqdp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2piboshfx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2lvuefhyy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmawwrie.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2nexqohgc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmxhwhg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxycpib.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2arcpzzby.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yutowdyk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfxsror.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2kljngobj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lupmuafv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mauqrjse.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwqbnpm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fabxqkga.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2njhtdzhx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ziutfguy.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2penmmshh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2eztyfsjo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yrouabaz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ycexmxtn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2foxuoqte.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2nopwnbua.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2roucvkbw.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2nuycusae.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hplframe.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2qelkuhca.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdqexox.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2etkunxgp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2pujbqvda.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftprnigl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2wffpcjqh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyhwxpw.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqgddpt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvfojot.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2byigstpt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdsudro.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2evnuiclu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2wummukhf.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuvmnes.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eoezgzpk.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqjhwwt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2npeyujfh.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2anffalfp.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzdpppe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqtfgap.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwkbpjz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrmahou.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmfhhtb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsebtyp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2zhffqjzr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qwepmoqn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jvoldkgy.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjmexpk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2aggohmyw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qalbjoor.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2bxajqmgi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgqnibo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2eipuuhbr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtxjyeq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2qiedadgl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfriyzf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvkmauk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2clldllls.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbtbopl.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2iscnaidw.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2xthzneqr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2igkjkerz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2btbfhsnw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2itnxzqbm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfspuzv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzctpfm.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2rkscxnvb.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2otshpxaf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjbvswp.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyowewt.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrwfbkr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsoouqqi.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfmoqkl.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqxnkiu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbefvap.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnvamru.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgqpaya.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkaemtm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwthoqxs.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsobtqs.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfbydep.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ybytpxnz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkyhecn.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bkeqehpd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpffmai.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpxtoxw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlmsiop.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2asdudcpb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuopmhf.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtodytg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkmjhbx.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ximupigd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwveraq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkknlhk.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2qytffmec.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2botsckfc.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzaacht.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjmlaru.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xegkluxe.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nahohjdr.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhakwrk.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcvhuob.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftodigee.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hycifmcw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gabdsbde.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nslxqmjj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2wyasivox.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fingfgnc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpuxlfp.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wgppbvcp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkxxyif.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hdumykxw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxybmoov.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwtgogo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttogaeee.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhobmcz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsrtegw.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2peueaqwh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwoyalwm.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjogldt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2blcbqnak.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhqgnkh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2naxuwsnu.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2poyrmzdu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwblaml.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhhtmsc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzexruw.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfcvkhc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yncugowt.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpzpthd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbftkoez.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cmffyahk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctembnsn.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nfatltqz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpoeuwkz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2xdiwrndj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2soxcuqaa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ookrdskr.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2wszbkoxb.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrkywen.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfailvo.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2koilpzrx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwrqwrx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2txthcihh.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dpeojlip.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pstvjnlk.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhievjr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zubhcdpd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqfkpki.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvqxwch.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmuktbu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2tqezjjkf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpprycjv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzdvcpe.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2udtjpclk.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hukvqcse.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtnhjyt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2pqditmde.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdqelbc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hmriihfo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2nthpqxtc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmhglom.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjiwura.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2oypggfsv.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oyeousis.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rauehrzw.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2faeijegp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nykbrkgo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqrxfxm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbmgwzq.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2daxwiqna.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2lobbtdhs.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdvztdy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxlkjcy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrihuwe.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrwiruz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxuuhsa.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmiktnk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyyzbvf.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfubngs.html


<!-- 参考信息 -->