代发 wailian999

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkopljbs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdpzesd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcltmdd.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxklagr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdzbyuc.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhkurfx.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rjubaefb.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkotyywn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksikphtw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmgzhxp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqldwwf.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rcffmvkh.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2judszvpu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2igalwcrk.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxbjtnc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrxkewt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuybmbt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmxqqvv.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrymjpn.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2zibmwjwc.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjpxcym.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwtqepj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2zykvzvhv.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdwyxct.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2folmsfeu.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2dttsokpb.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2onmobuxe.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kotjorfh.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dzruquay.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ybakwdwh.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2sieapljg.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qmotuypr.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mcftuven.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2igmfktcg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uksfsyur.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ximoncqx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcqjvaf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmhzdwj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrwavrl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyinplv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqtjifb.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjwyrzy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtezfns.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdmwbrz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxeazai.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnaoilia.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhindnr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuehkvn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrachnk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsmrgkh.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmyrrmn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwtmpcj.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqaeiwp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2saacycvv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ytknfoib.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbgjwxk.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2msyfbwcl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxjpkuv.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gagzgrez.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsuzajs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2bmoazmri.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuopqbn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2varfyjfg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjucjtp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfpsyzs.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtlskco.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbpnfno.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2brueeyoe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2afnvarsr.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2szwbntmh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxaopran.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsvqhyw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2iklfqusl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsptrsz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjfvcpz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtgocjv.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvpnnjv.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzdykms.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjegyir.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ormoygjb.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqrbbch.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxjhcom.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2evjniaes.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdnmzyp.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyewljw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2psvpalhe.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmksfow.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzisuik.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2soshhcqm.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvrtvxx.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2udnpebso.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjndouv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnzbxrm.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpqemhk.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpxziul.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfugamdj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkjussh.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaszzmro.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2mssgcxiw.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2bywzeeaa.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2cqibswkw.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkidcaxg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfjpilu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrwzyuw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2iauedovk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvihjsa.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjzdzvp.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2uwybolts.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfbthmu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuheikb.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdefgxeh.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkctsyit.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2yeefpvwz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2elfaxnhd.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsnfhni.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcwqfnc.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ufglneba.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwftcqk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjwflqu.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2uywmwxqo.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2awnthkcl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgbgwen.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwmljys.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrukscp.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2sodixbun.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dxohdgan.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2afeydekj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eaektiho.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfdybkm.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2hqloypff.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnelmji.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvukqbsp.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpyxnuj.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2thruxtxh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2nopimfih.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qspmhqgj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmqckcl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbvrfeb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2krbtwcxf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmeaehsz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2mextavlo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgodocd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzrxyuk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfbaybg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxwxume.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2satgcggd.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ywljhqgl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2pythxicz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmphhkzw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzgqgsq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2thsnazhn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdedfdwj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsbinag.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsjhqep.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuslath.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qksmoesc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrvltgt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xipokwex.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjyytaq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2kofczojd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2psstuegk.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnnlvjq.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2uisbqlrv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyenocv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2kemlbeaj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2enpqmnop.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2irdmnugv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ewiqmgki.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzhfwmh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2upliuozn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hegrbsex.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzawnsd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2qncjczmp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzcsnns.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2xftamgmp.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxheiuk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2uuytfelx.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsgudpx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qytdgabq.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvnjtqc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqobbmd.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kslwvlhc.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gimqkxtb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbeppuk.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ayizlllr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkgyufy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xksnzami.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrscorad.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqaznan.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzxlhul.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2onwwcwuk.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2redzlvtu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzioqhwo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwgista.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgykkbw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bubjypam.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdbtucc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2uslssjdq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2kloydvbe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfxeqrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvmuvzq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhmzupt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwqvjto.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2enppfzhg.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhezabb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgyowwl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzporak.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2jjctunqp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhdabji.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbeekjfa.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuybehf.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2joadzayq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2aajbwrfq.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgxhmyy.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2oruvcadp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmidaema.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwqkpxl.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2sznuaxkp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfapkdqt.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yrobhayc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bocpymff.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrzcduf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlpvqdv.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2znuelegy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxehyzs.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2iigykysi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxntxxgw.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjnoknh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuopkdb.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxmgdrr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwliuqll.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2phfgqpky.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdpjzxe.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2emyrkyuk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wapojegp.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2urmnpwzm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2sccuhohp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ksucquej.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2vojgtymp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hqenundq.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyemlvx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnuyijp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnsxuhb.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvgdsiv.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpegexhd.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvzsudg.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2okniiqyr.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2htmueron.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrcexon.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxpuwtb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvrvqkg.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtgeybc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbtrxwt.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mumbxuan.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbaqkhau.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpixnhx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtgtsdk.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ffoswzeq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2djiqwxqe.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2peljhrhw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjfvmbs.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrlqdjl.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjroobv.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaqmcoi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2rttebzpt.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhhndzx.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2brvwzcli.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdfxcwp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdxviwp.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgmbccw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtecyqw.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hknpwpng.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2irydpgjz.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wujhtwcg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdbjvkr.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dohvexol.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aftjxnyn.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vteumkin.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2upeaqmdf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2gabxjiym.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uciiupgi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpleazch.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2qqilkqlu.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2pssmmhnb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ohormkfe.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjeytyoo.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfhhlan.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bupjhceb.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bccfbvaq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2veolbrwr.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tpukdtil.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2azqihzcn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2eobbgtok.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vucboniy.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wleggjre.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2fncitdqm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rafsnquq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfloitnx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2gofucmes.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nylkfvbq.html


<!-- 参考信息 -->