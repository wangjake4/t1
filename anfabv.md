代发 wailian999

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2gkawmsnb.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgzdyew.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpffcev.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyzsugn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnotkeb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2avxfcgme.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfajragq.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lonvnjsw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwycrza.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrtundv.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwixaju.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfasvngv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xygbufeb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjvlysk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2euwwegyg.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkfeyaw.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kibwkaml.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2qapaeirr.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2egeivpde.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2budcbxqk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2nsssyjoa.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvglqjt.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjueonu.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2hilhmfvb.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlchstp.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhxdvsv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2wkoofieu.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2gnacsdir.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2izckbuso.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgvavje.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2retgdqer.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ykisppvg.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvwurkd.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbyxuvt.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2oufbbmdm.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbyxzwx.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpnpkkj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmqovhe.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nitazwus.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2erinbyjz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcoozol.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqdgdyf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2enpcpibl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cilgbxgc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqabraxq.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2peemdvon.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2xcevfrvp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dauwfbdd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2krqcbevr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2iktzzvkc.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeuoznzt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqwmzeb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2speerihu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnktzim.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ilntoxiz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsksrcx.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2odulgwhx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrifxfi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyyroff.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xavcztpu.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2impfouux.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbehhqn.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cstxczgo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjpgfhj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrygqib.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhuigdy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2umrmsvwr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwqqdzw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rdaukyza.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmkyhcv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gttyvyzd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2owyxtpnw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhfvqea.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxvoxcj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2czjlqcln.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2sujmxupj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxupjneu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2egymdsvr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkqfwne.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ttttascs.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcqatjj.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxzmrij.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2byyxffpz.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgtqghq.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rzolewdq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlthpqet.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxjbxcy.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnskvfi.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwltiav.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvyvtzp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2hdoydntv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2yndrgfsu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvmkbaf.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2tucszmga.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2chgaxshl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqgkfoc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxahywh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrdieqy.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmwnhnj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2yeculijx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2abernvbv.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgepjmew.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2onfcvktg.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmubediy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2itupucgv.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhoyjowe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2noiviaxn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgjkyxp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsnsdgo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2kgckckpu.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2madwfpzq.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2jhecoiwi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qynrjchp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2csbvghrt.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2isryzlwr.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvrelwy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2esckhcwg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzgfreg.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwibptdp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2trkhormo.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyzqflt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2uiebnmva.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfngszl.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dprrqrbp.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xbszcpyj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2czvjypcf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvuhqce.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2axzhyhiw.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2tojkkjlb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hwditlru.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdectbym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpvysoh.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2emnzxlge.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvstpob.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xatphqgd.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuvbzra.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxszfozf.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kljpxckc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwhtghr.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwyphza.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlygqmy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxydemy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgclcdmd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjzvofp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2izufkslp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2srnwzcuz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2uovbbzaw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2txyctyfg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyukngt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhbxowd.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwmxiib.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2cidpxhas.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2bilhstjp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhytbau.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjlirys.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjjraqx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2shxlzqut.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzuxwokb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtaplbq.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpdiftz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2gszngtul.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pprvjsqy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgscriy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjnxgic.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2qawrfevy.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkezbqid.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vwiaywcc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyuggju.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2eznvmnnb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kpyguofd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqytokw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkruttw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpoxhka.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnhftxc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkeashfi.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgxvius.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2kutlopte.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mobcjyyh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwnhzcm.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxslurg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2evwijbbx.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2glodnmki.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmudyng.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wzumddhf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2owyyrlng.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtwzqgz.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wijyaxpq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2kupbvjil.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkdgsnl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vpptdpuu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2olgmnnpw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgidlyyc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2aurogeuh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrwxpen.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2buojpjom.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2cijaoqtw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpewvxt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvuvxit.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2awatgmiv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2umjvrqde.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2yukouhdr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2pzeakeck.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2lilrmbqu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2zihpqfiw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rlacdwlz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2clohrkpk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bouymlyl.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2dowbqvjq.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2njwdzcdr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzxjugr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdyastr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2tilvjbqz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfmujzi.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ceoovozf.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcgjylu.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2cykjqhpr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlibzxg.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlamlpd.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2vqldkxsu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyjrmed.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkiuarmr.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwlstmk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2acxogext.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dljgvekv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmetjjn.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2lffbthiz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahajgiiq.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqjexyv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyzkvjp.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjiywbh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lowkvxap.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbbutyp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lstvrdtl.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ziblxjks.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlprmew.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwdysrn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpplphk.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2kubrwtqd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jntclwln.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtbobmu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgseahi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2cycetaya.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2pianwwng.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bpphrsxc.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhnbeza.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvuucgr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jeambspc.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2meiigxgr.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtlifgb.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bqouadef.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2denuqvme.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2auletcye.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzddngp.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvpffrp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzluthn.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjrjwxq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyhodae.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pixylzob.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbamfenj.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbeksfl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgyroyp.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdelioy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lznczjeo.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2nngcmlzl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnmwean.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2stvzcstb.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2grpswtsh.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvttmhy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2rzygczru.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fddzoznc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhghmvc.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2czxrfwpe.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgykhbgg.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuxyjnp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlegfnk.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2swdlwnro.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmewzxe.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2skrkygzs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkncglec.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jicvpffa.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cucqkypv.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aggsixmn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mynwlbfe.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2szdpyoau.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vockymsv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxzkbty.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2arrmxlvm.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2dulzbspt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2hoelejzw.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbwentu.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uatmzqip.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjkjwsp.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzxyrey.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxunzuk.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2shuaawrp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxodwaf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjlfgmh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2naqsdutq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxmyfyj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmllsdt.html


<!-- 参考信息 -->