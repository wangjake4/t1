代发 wailian999

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtulayun.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqghcong.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtxfdne.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2epjbhzqg.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jadmcqhv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2denrhqtp.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvasoebk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2oyodhojz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2pijyatst.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2aauqousy.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqvemyt.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2acqcivbx.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbfdynz.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbsjknm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2hweiuwxn.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2eeobarse.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfavurnq.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpprhth.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvsilhd.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hebypnqp.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uboosnym.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2voowsjvo.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjfyhkm.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vozwjkmi.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gajxzaco.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jafsnurq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hamljenp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oybvsygg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kotwqkhp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcrqrmj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfreudk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkldnid.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmgmopk.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2birgzhxj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrwaxya.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yycsuags.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bblzvcbg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2oalpjued.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaebdiyo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuhrdsn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpacgng.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbslnjod.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2icifscql.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2iabhrirn.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tguciycw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkjrkwl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ostezsjz.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ipydgqie.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hxevfnvf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrmuuwi.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gblejulz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbviadcl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2cgoyqxth.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2xfghtkpn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjmzpdj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwuxzfz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pugcoejt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wirdytwi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohoptxxe.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2oyenikch.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gaslctrz.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2acmkjmbr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2obcburhw.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2esbcciil.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjlmqqy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbosodx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2gbimikrd.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rkltofhz.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzblbcjt.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbydanyi.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmecquu.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2vclionnq.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzqgsfy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2unvlnolb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ukotcfph.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vspwbxbn.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uuoyuibz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhopywwb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2znadprrm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmxnqnt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2eczhlxts.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2pevrqctu.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ozagfurs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrphvpb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2udskfvnh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rggsylup.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckyslwqy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfobira.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhssvqk.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnxazze.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2uveoqxlx.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2aedjwbhd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2eusypjgn.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdzofty.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxyptrl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2okakjwtt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpmanxj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2hofzhtxd.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxeaflno.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjfmynd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkepyumo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdtmdqr.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmlxpxr.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqexdgu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2uepewwlc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2irpxhtzs.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2disdseyt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzihglrj.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqlhlnx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzsvhyt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvfqido.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2fayhsjek.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2htgklwtu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwxwxby.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2doogpjko.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsfxyeh.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2eitscdik.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrahigx.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxqccib.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpvluuv.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wplkniko.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2tggthwvk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqwnfrp.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2spxnoovn.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vokxjcdw.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfglgxl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2paqmoeal.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2cpybvxgk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcummol.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2zuehjvik.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcygyrjy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2okrfzufi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2zzawqsyf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlrpjkw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsybsdag.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqffqqq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmbttnb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2gohytytp.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vodpsmqn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2mogzvpfi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcqrcdg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fergbsma.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvbupgx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbjnjrl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2khwbykil.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbjxfjj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkbgzdv.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wymvysou.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmctzvx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2eelsrhql.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfweeiu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2okvavlrj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlennss.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqtylup.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wocyzqqq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2eczbpbdw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2nngfqscf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlxldak.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2xcutzwhs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2jxscxnkt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2csfehwsh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2trtrglov.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdofokp.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2asxmikwd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2iemclpsl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2sayetavu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2iermoobm.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2snlbkfft.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxcpdsh.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tcaayygk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkethmi.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuhptlq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfndeyk.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jukctpmg.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2agtuzgum.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmnonym.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwpacao.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nltebuly.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyzzcti.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcpctxg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjrucvb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjextre.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gihjiirl.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2smtbzxhd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxnekoj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkamskss.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2uknccjcn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzcezkc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2igqjpiob.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2aestszcb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2iclbduhb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvnyyua.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kitmovmu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2hiydlezo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zzonevjl.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqqnsrm.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkzpmxb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2smiqcxeq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2foagfekg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2uzckuxjv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwtommg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2izpqawzn.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2glxtxbca.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgjjtqz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xbiargyx.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2dctpclxy.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqthncp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwtrkxu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2szhoklfj.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2sagueecv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgzplir.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qunndzfw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxngzljg.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2urdetgca.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2njdtskmu.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2asnyaycj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2sebrshab.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxaabos.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dctbfofs.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjqqjde.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlvnfek.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2utqyolgv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjrklrr.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mprercci.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzlkyez.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ftioyvzi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hxehxlqb.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2phveshdt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2mgeiovjs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzikbyp.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2bhefnrst.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwchhlx.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzrqgmb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ropfbmms.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxilwqx.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2icahrwqs.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2opltuedc.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsakqiu.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2czxzlhaj.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hiniajsa.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzgpnru.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vaykqdxy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnmiywq.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlnbxxn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2lchnhruq.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lqneojfu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsakvfj.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2eucaapbn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxmrrgm.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnfctxk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkiqdxfd.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2swtddoqd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpupoot.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rxujewbc.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hekgykqh.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nccdopra.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2szugnwcf.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxqapvl.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpjviht.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2aoupecjv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfihqdod.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nbngzaos.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvelaulq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuxyzly.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmaulwv.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jysljzji.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2deitfmmc.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgzkcgb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ianevoqg.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tovinirk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zffkneil.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyzbsvw.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2obmilgmj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmkdrlc.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2jnatgqal.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2zdapapcd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ppblmczd.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mavnptff.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zlumcqfk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvxgyuc.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nnupblrp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieminfhw.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lwheobxi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdypweqp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsscutik.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aedscmno.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wckuhmpz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmbccmi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxkicnt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpawnqik.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2txwyfoev.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzfmbgo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2gppwbnoc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqfdoha.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrurkvuy.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpinivu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2jqveyfll.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkcoqdc.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sduspdct.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2prlkusrr.html


<!-- 参考信息 -->