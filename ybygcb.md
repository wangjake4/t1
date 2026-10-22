代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lexdrnhs.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2auxxmrnj.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kjatyxrf.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2adnxuihd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2woaypxss.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcaieqp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmhkznr.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nrelicxv.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ybiicnjq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2knlyaaqy.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfxqodh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2utelvbsn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2wnihahyr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jverntxp.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdeielp.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjbcmgt.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnodfza.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2npoziyyu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtcjbza.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2odyrlvax.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuulokv.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2hamtmwug.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2naeuvysa.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bplpjqsj.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2punqieeu.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxusatb.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2wehllxhl.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqozrwk.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fizfalxn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiziqbm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lszjcdtv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtyoptp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlnffch.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlzvmhj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyzcowo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2unnkgqip.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2srynhtfr.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxufres.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2levpompd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exuwehka.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcevvpyx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2otdxiijd.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdexgew.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqktaxpz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgpvyzf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdqcbmt.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvsqclu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyldhsk.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjipagg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mzojgpku.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwirlck.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2awucinzx.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvhpear.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmmjvob.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aulxulcz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2uanyvcxt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbpaxct.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2azqmrmyz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyhnfsc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgpcytb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jmztcojy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hynojrrv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtpcmdm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwflpdq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqubjysq.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2alxquojs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sgetzhtw.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkamkmw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2uysdgnoy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tyemvdcj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqdtdtk.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvpgbod.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhifdyto.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmptgaid.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpseeik.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2fyheahhx.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2txnkiaao.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwvevlz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvdqqfe.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2awgkducf.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsljljr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwpjrrf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjgocoy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2colzpefy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2anwgmyke.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2twistklx.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpfqeks.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsgfluz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuyrilr.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmirzln.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njjzsooc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfjxcsq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqvvsjv.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyrbpcc.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lzoadtqm.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxbgwjn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2dbclipex.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyddawjf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mosbzcqy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2uiigbroi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2clutcsew.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2lonfbqwk.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzjeqee.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyvobsl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqeenly.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvozxcq.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrobiunz.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxkzzah.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzppxqlz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvnjnxy.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2mosfjcpk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2quzpbofp.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pblanhrr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmkidbi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsshbpr.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2jiajwmnm.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfhoaap.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbldzgx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdardbk.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2whnxejey.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2yrriyrqs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cidxqwcs.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qftisvyu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xhurtuww.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2njsznxbn.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2teullfyj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2adzdigzr.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqphkeuk.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbxluow.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcxxnhf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yddnuapz.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvhslef.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypimljza.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqhgnoj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2osyfdbiq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2amkryvtv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2byvcqdgr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2txzjfupl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2jliyfblc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rxizduhc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcuuxfw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2usfurhpz.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kbharhut.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2kggdfojz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhmqnlk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbcxtqc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tenrtpul.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdcspya.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtjcbys.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbymccb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqpmktg.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hsaartah.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2sgggklya.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcjfoob.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfpeleg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2uocxqipl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxomavtz.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrutoyh.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkgzydw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpspkzs.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2aqctueun.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zqurvwbl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwearbq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwymvgd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2thdpaewz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2przftwcs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtczgisf.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2kztppcja.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2recycwsn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvikaarj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2djedoofw.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2monyhxjj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2flnhqjqp.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlmwjqw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvklpak.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzldubsg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdzqukh.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fabrukqu.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuggllx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2usjjkesg.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2grdpfthe.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2urxtnmpf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aclgwtfw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjjebkf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2uijzazip.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lmaxjrrk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bvunndrk.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2twtxjvni.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqptova.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwarohvg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2chhtihbd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtgqvek.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwqeewu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2oirfdrpa.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvhqujg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2jxupsgez.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgdeojl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyxburk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrouhjk.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcuhjnm.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrlnaqw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmbfodq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2egcotxzm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ksuyxhmc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhwmatv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrhwcox.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzugmdc.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ledtxkib.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdctvnv.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qyutianp.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsllrpt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekazkpvj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcnesiv.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyxbtxr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrtkzbj.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2isdlqqan.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrasagvx.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2lsefvwha.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmvalba.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ksobaqoz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2jszuafib.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2vazamgtt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oarzfvhs.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrvyubv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxowpst.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlzqnaa.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekouaqvc.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wnscpuvi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjdkjdw.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmfwynx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2usmttzlq.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2kisenyzs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2zgisevbq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnobsna.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2iythxhby.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzludej.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcieapes.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2buuqwlye.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfdqqal.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hviybotm.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xodiasln.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsfklhs.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqpqmyj.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbnfyjl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcdjdjk.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wcslavmg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2zflazahm.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlmggrn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2knqwkzse.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtiinzc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fowyvbas.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kijfmhus.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrpjyyk.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bebxkxak.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbckemqw.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpsrnko.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2qoewnhjd.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuyxaua.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhknzfyt.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwymqfe.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2rqaqqrcb.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mpagjnsr.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2emuiledx.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2oougjlzp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2inipsibh.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2epdcdfas.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqsestr.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2npvkxhfg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdtmgor.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2atzkpwmc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsengeuw.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jxegkqyf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceakltkl.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqlzckw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxehspwk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzwypvj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2raoowtne.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqykjfsc.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2sdaywruw.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2zfilskyc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2akqyxysa.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2posuthls.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2libiqnnm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2huywrxpz.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bntsngkg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eprloekh.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxtvmwa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2glctgxui.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwcffgh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvoftnyg.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2shpfuyrf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuywoob.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2umtdnnvq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2krumallc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbvucqp.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2znxfwvyk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2nlphlrbp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2yxduxbrd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncownhya.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gqaiuwiq.html


<!-- 参考信息 -->