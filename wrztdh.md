代发 wailian999

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2adrivmux.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwmbvln.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aytahkil.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvgutds.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2acmmjluf.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwbqlaz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgwhinb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfdxmfr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2heiyvwnx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bflbezir.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwafimxt.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2arqljzbe.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsnnjjc.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxbblpw.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvqxszu.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxsacvt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2phbgpqql.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bflqperb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2amrcqzvx.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2udfblvyh.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbqqbhw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2softeurb.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ylasekxo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwgpbna.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgszcrm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdokrfro.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2fuicjzbg.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2oigsjyjv.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2gavvyquh.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2qtosvrmp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2nligcfhu.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2xvaufhzo.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcegrgbq.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2rewqutec.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qiznamcz.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxznfre.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkonugg.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oicntvbb.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2kiihojij.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uuuacezt.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbpcxkf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kmszbgog.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhmlphj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2suomhwqe.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2joxdoeyn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcvkfjz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkglfvo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrveofe.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyfkgof.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pryqbigp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2oydufqbc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuasmegg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtldgrnu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2uczfqkvo.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyodbtnx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfheoukn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnbwrrr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxlxmub.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmzhqno.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2znhkmubg.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hspdilwc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbyjmcz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bjaihrdm.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2leiwkeiu.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwtgphh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpmrklo.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2prlnlqyi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjidwtxn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2rktpmggy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxsipjg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jofsdkdb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2raqaeigi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qekrfrwc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrwhlwa.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcszlquy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbadwmy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfprxxmr.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2irrvrium.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2htcvdgmc.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnslywl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2aolskvmm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnmnfij.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlqpobz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2cughgajr.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjrslsg.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnywpts.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyylvcl.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjknoyr.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ymilkufc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvecxvn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhbwsca.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2urzgmsay.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfnzlts.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2edjjtcyo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2cznolciw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2iobfyvpi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2vlinkxkh.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvnwpnv.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkujegz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2okhmxsht.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2fufehhpl.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuxpccb.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whuukbdo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbtfdrl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vznxczmm.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkexgyk.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hpchtqll.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2qawtwasz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjctrgw.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjldvfat.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtdzoms.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2miplgvjn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dcprdztu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjnhoza.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2foosnkuw.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2nypxipyv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzbvlte.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ztubxotp.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cahmdfyd.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuwmwam.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2hubgtrlj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2lplomxkp.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxdqhxa.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwwrowj.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2anetltnk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2jisrlixd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yoonhfrp.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqbphkg.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkvgmnk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ipeavuzr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrndqoz.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqctudz.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgapryj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrvoxhe.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdrxziz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fpehcooz.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2uktsqtqd.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2frfiuvwp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyheqtj.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2aysldmml.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcdqsyt.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2svqudvqi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kowojgng.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fudjizem.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zsatoyno.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqgjpol.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2majyqpvt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfjswff.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2eqoxjtnf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2xulovwue.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2redxupil.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdsnwsk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cidhynnt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxatjka.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kdinktjh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnuxyes.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2odyygxjw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkwamjk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcfkoij.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2twusboyx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qnoeyzhz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnuobll.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2evsdstru.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjgyhna.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2iozbvozs.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2uewjbyld.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2erjwvmqr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzgieti.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2peobrghh.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2iydclpec.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2pluprtpc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwfmvmw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpenfse.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cyaquxja.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2buofvgaw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2rjaezxmg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdywwzfk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwetgwj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2shuotefv.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyneyis.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyssvbn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbkpiqo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2vboabwhl.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpvbphc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkxalsb.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqicnqrg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqskddmd.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cimwkurl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqzhzhh.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjttlvn.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2apxoewiv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2icrmdgmm.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tyckcers.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnqzjpp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdtupvw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcndbuq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkhwejz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oljezahc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxecxex.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjhokzc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gweomvgq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mghcmjii.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtpzzjb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuelbutm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqbbbkw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2klacbvdh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2skzlpwss.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2xibxirco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2drrltgmb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2qingbbmt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlfytdx.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ykipdgld.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2owkwwqcg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rspivfap.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrapnvy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2rjffwjfs.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2cvoyxdey.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmqdvmi.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqvkcca.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2nsujkowe.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2efltotsd.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2czptvmku.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsspzjg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqipwhcw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdhxzoq.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfjbajg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptylnqci.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtcladq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2uydhpxhw.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpdndkr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxhwxrl.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdzzptp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2onxxfbwh.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2lizgrrns.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmswjeoy.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bliqspsg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2olgcbvoj.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnsuvbx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fowaqpkq.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bphwmqdn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2exuqlmxd.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfryjdo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2eokfxudm.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhgicrn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdoodzh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2kyobliga.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2vzaytqgk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpwzrvr.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmnpywl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2zaftimtm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjkrkbh.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nxugmyvl.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrzzpvj.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtvflsw.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjwmjtl.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lgymciqt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2llpfapgn.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsckwdf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2smeosusl.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iiblurkv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2crfyeyjr.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kfflliac.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2giqohyck.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhvegkl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kndaputs.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbqjzfm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2nviczzeo.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2dwypjcdw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmrfjjc.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tplrwmai.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdsnhyg.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxsogvw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmaljlv.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2thibdzqs.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qewjnalt.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbpwzog.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgasgeo.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xtenffyg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdzeqat.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbkzadw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzvffwx.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rceirglg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2iggkplbr.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2immkcogl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyqcuac.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjbsevj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nncdxxmn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2koaogver.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2iaveuopw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhivbqvl.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrgtefz.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdtxfhs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2btotbhki.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzknwrt.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2slggurnx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsxccev.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vusumxbi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtzhlte.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2htovyndq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dexzmrza.html


<!-- 参考信息 -->