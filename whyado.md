代发 wailian999

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmslism.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgyfniz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lolfzxja.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsuznrr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwalocr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmihiuka.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhstbfn.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkottffa.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dupgwnlv.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cahylvld.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zyoebynp.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbxcqbc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvqjuqv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwsijmj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2nubrpmou.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zzatnydr.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2igqtdzdf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnyqmfj.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhagzeu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2jyecgtle.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgjfxed.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtrkhlp.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqigvfk.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2chgwqlgy.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2dasovmlc.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhbqohy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2jimqkzoy.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2nslfjggz.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiztnnsx.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2fojtntun.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2isqqkewi.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yaevblhu.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsargdj.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fqumwivn.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgasgan.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pobqrjwz.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zigwvcik.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yszraurc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dtborxyz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmcwlwl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2uettizxi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyvjtxo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2spfqhcoy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdtumda.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbbwhgd.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbjyyxw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvgnujt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whzsvwpx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2byjovgif.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqrtebp.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhswkqkg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqoffbk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2isolaqcw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ungvkkpm.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2glgyhnwu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqanssr.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xytpyjcu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2urgtsvmo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2aydizeot.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ifirehnu.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkmupzq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2buthgsut.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbjynou.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxjdymm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhpjfts.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqzhjnu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjqshfx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnmlizt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2woignslt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxmqzie.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sokcfhnb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vvldobnt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwklaia.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjikxfh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xrltlrtv.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzqvyfb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmfunii.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xysbokoi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyfiule.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rzywkfnj.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpgxsvh.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2usaftydt.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbrwnfz.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ukemoypg.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2odbvwfje.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2aerwgrds.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhmggsb.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2exizamrx.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ynolfjjn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmxhmry.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2zolxsnzo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2twwijtci.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrbfqtr.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2sddnsdhi.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjerzyv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnaxfyr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2xljaegbs.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdumfsa.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfacrpu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmodwtcz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhdhiwg.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsrxpds.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2owxmujuv.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2njxuybmn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2syiyxxzy.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsqbnjr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2npvvwxxw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyncczc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ibonntve.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnkdwzd.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhjdzld.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpyaylu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvvctpp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyszzxy.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkeowum.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdynxofd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2twkakngc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzpnrns.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdgipwr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpkbhks.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2amkkaqpp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhhpicx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nufwyopp.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhxodqp.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2afxejoin.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2hoijogcs.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2jppzvcrj.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2geudpmph.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkworzu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ipugomxi.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kesghreo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxmfhsk.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhewylg.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwkstds.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2icqmlfrp.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpmzuhe.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbehotin.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtojiay.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pmoczdon.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pntdknoi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmufosj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxwjltl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmoyhdlc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfocmkg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjpqyzr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2attpysei.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhkqfcu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2votgnmmd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2imohngcu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxgdlkm.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bojbygin.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwgidmy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdilxsg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqcosos.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyntrzyn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdqlszt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bondaxkg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbchxgw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2unzevapy.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxxflrw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbhtbjb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgeghtk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2iesdrvjk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2gdskcjcs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2wssmikcf.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqljtdgy.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtfjcpl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdiqnlx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsfmjdz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqgkiti.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxpdsuo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2dcskwrio.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdnvzbv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2cespatqg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iewmxbqc.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhnuujt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2epxaqsjw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfphoiel.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2tqekdhbp.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcaffkn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2zlikvndy.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2schynebx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jedlqbwp.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtduzkts.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdezvrrn.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgcmhut.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqtdjbf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2retjqluj.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2useqhhwm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtslqcz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2somjenwg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2idqvwjfx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqaopvu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqihwen.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xedkgcov.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2itaymwdz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtbirce.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtboxfwz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2purvvlfm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqvashb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2liiileep.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvhqudc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2zaptwjcf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2gprlwvtl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrcmbop.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2klicvajz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcgkchf.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzqjhet.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2btvadhpq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcdjljs.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2slvhgxlv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ottxooqk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2bdicagzh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmlgdlj.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2mjscetcf.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2egihfshf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2akborfks.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzrgthy.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjkxaup.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmolvlof.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwvvnnn.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ebylpxbj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hinzgrtu.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmaooor.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2heohfadw.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgxwlnr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsckjymc.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2rewylchu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2clmoiyfq.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2boonuqjl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2odbcoulf.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lqamjbio.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdvfino.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwcohrs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2biteuvcx.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwivgul.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2beazfxah.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmenhse.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwojssq.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2aoitbzrp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfuntgj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpdroln.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2zatejeld.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2weojqykh.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtawwdj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwkchee.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmyekif.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmtihrp.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eiznztsp.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2azwdzysw.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2axxpojtu.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jbriwhtd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uiibicix.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2unhdsrqu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfhdxrp.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qruuikqj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqkapkn.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rjipkqyv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqphwjms.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mumgzcdk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2pikyjzvm.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fintjqpq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtiamxll.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ammizvye.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2idsqlomj.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2llggvrdh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlabeylh.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhgykry.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2azxqrktm.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2uirqktkr.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vstzcegt.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2yutruqna.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxnidgq.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxpgnrp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kaicozgh.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kpacssed.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwrygvw.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bgemjtfa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzpkdcr.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcyaasi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wreceols.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvgcnjz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfmhnve.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2akhpbynt.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dqeremrn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrpteho.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzvmwyx.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2rnanpqww.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlcwxjm.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2crkppfis.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kiscodtl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrkhiac.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zookvjby.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iexuuqes.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2orwblsir.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnzqnpg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2apyfapyw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvxqvib.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2penfywoz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwqvvrd.html


<!-- 参考信息 -->