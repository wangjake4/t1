代发 wailian999

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrpndkf.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvvflfy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itmnkkqm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdviuybl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sunxqxnt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkwctya.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkhnoad.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyltzhq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nignxzhd.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zicafnnu.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2drdnebhz.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvutjvc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwydkfzm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzhgulb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2lagdjcag.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxbzthk.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvsknwp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2volgkjam.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpvbfqf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwpitlm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2lomdmgns.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mitghqzg.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2wvodwuat.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkjsigo.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2mqemctzp.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuoptcd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcoftwz.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbeyasl.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqkqxgo.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2srhhsgcg.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2npykvlbg.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkbwljv.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpbykad.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbugopj.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2jcojjfmw.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cjiejiml.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2psaqetfz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lsudakhj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2emgdhvnn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vorvobsc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2onkljkef.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uclzdjbn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wdppluoh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuhhodz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfvnala.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrjrjmz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgqyyez.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyfffys.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bavqaejx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzqfzbk.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dttbvduf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdereikw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoyijdvv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyziwgl.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2puutgvdq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2twwvdwwh.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oltccmts.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bppkqunc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjedkdo.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgnbnlx.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2urtsbuoi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ueufujuq.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2liepjlyq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zllexvsl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyxqqae.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2humtgoks.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2urfvkdgo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdvlogh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyolgsq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2slwwvrkg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdfigfc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqbkpoe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avtnbzao.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkbxlks.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpyzoso.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxjejlf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfmiiow.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ymffkbgc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ulaprliw.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzwohft.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvncyap.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvoakswv.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2puzqebwy.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2rzctmmye.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yjikibgx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbvpqoo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2arsonvkw.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pueikrlx.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ivynyqvo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwryluzw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2abadxpnn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2twpuzkju.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjhzikv.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2nvepprnj.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2clvakesa.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2wjltstvh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhuridu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpjjixa.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htidbaml.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxdwnbl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkxlbut.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmiyfbg.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgnxxhw.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsjqfhk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ejobwocz.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gplqzmsf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmfrucs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2qevouepv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2eydiviom.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtckeuz.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tamrmubz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjzhkwj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfwnztw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2qnicotkc.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfhlmdk.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2anlouupb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbqvhhe.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2lthluvrh.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnnyhcn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2phiuhtbz.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2iqoyddpm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhyzvkz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxpsspk.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyvaohd.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2aizfloyj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbbigdg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2mmeghmqq.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpxbvic.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2kncqqaft.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2agukbrwe.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nurdtadk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgsezbh.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xitxgnpa.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ecescsis.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfydbbi.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtspjwzz.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jakwjxbt.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfzxcja.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2iwoodkgw.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrpgjvr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2daqfaman.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2osyexxth.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwctxgkr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2crwmmlkh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbxccnj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhfbxqv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrsayow.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxjcoki.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpykjbr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtiozto.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nartkwwu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2szhapzeb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2zomtqyys.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjuvmhw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpaiqxm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzudchag.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qphkukaf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvucyhu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2swrmpewm.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2czfmorxq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2viwjbupk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnjjwxq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2garenjvt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqbilgn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2barssber.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqfuurf.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyzeqkm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pamssjts.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2mptduirz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgjfvhc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2iioayatx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2oooggpuv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2naeuyovk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuunkai.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpobcwwo.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2apopgudt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2fqebxuce.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bbozxtow.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2moonhxwv.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzxuief.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2nkojdjgr.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2asvgnkpc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnopdxaw.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2icubqkwo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhtdasi.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqumopg.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlcoorb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2srcwrlja.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgsejep.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdoutib.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfeeczb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2igbzfqts.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbpntzq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mdeklyaj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwoagpc.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2nagywrda.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwwewvu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2itohymeu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2macyqfig.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzyifyc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2irdxrhpc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2vtytkqgb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpltdik.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjcbzjd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwqgyvb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2piwyfvbh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mgknebvy.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpfshtu.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcdpvkd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jzchhhha.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqcsdnb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrypqsn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrwxiud.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgpedrs.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2xpobqmmz.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdindxg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvmowkh.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2nolorvhf.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlvmsgt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2tytmdxca.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjhulbx.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgkbpsa.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxhjuto.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2plbcsjbb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdpmgqy.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpbimad.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfefzkf.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2uapntwmi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2egdssidj.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhlmsms.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhycekdk.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlckqhe.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nafkqaio.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nixyxoaz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2recneggu.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ietmyufj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2flexinea.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2phjfpekk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fdybsfth.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2wwykwcbe.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2itpgecbx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2dngxpytd.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2zigefjey.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvixxqw.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2tosqelql.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2geqhxpwl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycornbkj.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dunomhsf.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxasytln.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvtdixu.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cguasjht.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2npsqnunf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2plzdwjie.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2btoeqlma.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmvmxvb.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlplgdf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgpucfh.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rouiioei.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnklkdqv.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oixncrlr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebopuxmq.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2smhjccfn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhxopaq.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2laqiufvd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlfpgtc.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmpcbvr.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmphikr.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqfvzwk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2liwhnqic.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ambpwnhz.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yviipagl.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pslddwlc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2abirfybw.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqyetni.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhngbyp.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhfhuav.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eauvijlv.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2drzxtyrj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2staqkveg.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zchqpqxv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2btmutexn.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkiyuyj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbepkqkg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2cphprdub.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhdsknu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuyvrmq.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2fxygsabl.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2xuekqelj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2hdiqmlot.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2btzjfebe.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ellqekyr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsqtdkj.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmqptra.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fejloejf.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcgxqjk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gosevyxf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjofypa.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2raruwcth.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2cykzfvzt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyagsqy.html


<!-- 参考信息 -->