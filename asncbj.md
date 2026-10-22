代发 wailian999

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcwrfsk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2klnzkxgg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwsazyg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpamwfy.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqwdtcf.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeiyyhpj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cizwgwus.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnokakan.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyceevuy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fykagewa.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2edaoefds.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbvhvdw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpdqlug.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2udtexkff.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwlofqw.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sayoaevw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lipybewy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsvpqkz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2myxzqqwq.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nycijpui.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbarsxu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2uomipvqr.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjclpbka.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2dtuvhpmk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2acunjxpb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqjxpjq.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2qsphykpp.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2hqunxjxi.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtfqbiz.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2iksxlhrs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjstyeq.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2rfooqyfs.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxmobem.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2qeifltri.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bselpsal.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtysbtg.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vzncoiwq.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwkeyxx.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2csdkdxdd.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2blsrphlk.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuwvhzy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vsclxiqm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyaylml.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hohhvupf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2deyufrfu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyxzydf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjtszfq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wqchkurp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxugjft.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lkajmijn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyusdag.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyyzemd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gaghheyi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyaofdvy.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpgtgng.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2osvuvutz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2evnkgpqm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbnqntk.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaokjrq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2jwusmbuz.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2usrcrqzq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2orhokzqy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2texgghgu.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2weusdoyc.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgynnro.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2jdamuupi.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwdmryc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2swbkwasy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2bldnuqgk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwmpkuf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqrtbsc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdcnnrj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mrisehjq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fserucoc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbmznio.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lkigjfmn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2twceabgp.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrgtqdb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vkihdvtc.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfituhx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2bboiizrq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kljzdgim.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdtoudq.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2axzknrit.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwabvwhr.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzvduer.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2efttqrxx.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2neqgxhyc.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2txesvxvg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjefzlx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2oacilose.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2liqtonmo.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkgkyxx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjikxyq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ezynnedj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyqwgeo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcxesry.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ciahvuke.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jkitpciq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcdqevn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2dfatkhpd.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pggzaomv.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zacxzzca.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2brwfxjrc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wodjoztn.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmcices.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2dltvkfrq.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsfcuef.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2akmljjsq.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzclltki.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2thbojoud.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvfmkbt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fupkdpwr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2srxeqibd.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwepbrip.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtffimn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2oafskxeu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvyarkz.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaghmxhr.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2shynipgh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2eewgschj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2acsuwyex.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtpktcl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqprujoy.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2sqppqkqg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmnedlv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2byjdqgat.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2kxazhvoq.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2piqbhvnc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkvsnhd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2mcffuomt.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2tccrhrjj.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2gnltezss.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvpxfgd.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2esurqkyf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbafixrz.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsijjkr.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2zebzmvvs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fuyttzrd.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxbgyym.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfuntri.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mboaxtdj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkyurkz.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsuhosn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gynvtnia.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2hihetwno.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdikohfj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2byrrpqvu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdpjhrz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvnxokv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnlgiem.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyiqksh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrmlyhy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwqthsw.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcmkeyh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2dqiotacg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgviygw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2alxhawgi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehguvtxj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjevelqe.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hcaziprt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqchnysi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwdgrol.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qdixgnju.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2rluumwzk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hvntyuqf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2abqthivr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2tegbsvgc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzupedq.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxblgllz.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuudecy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ruknmqvn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2fisbkkuk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzxhoob.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2sztrdsyj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2lifmimzk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2joxdkhsp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2jddvbtgg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyrahma.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2bblutetr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkybpid.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmhdoqu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfsstki.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrtmted.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2tuezvefp.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sobzijfd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrekctr.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqdkaed.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjisjje.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjvtrbc.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nhndddpg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2fxaefkbl.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wllptjje.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ingdbvlu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdxdnsf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bccbcguc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqmjeuk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdfdfai.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqzqvyd.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjstaei.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhaymrpv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2motdtbqc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2prjtemyf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxexbnl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzgxwel.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2fveljxxb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnmjfbf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxqaeyp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbupzym.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnuukwg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdaqebga.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ehiswydf.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmfbhle.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmzowoh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkybplz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2prnzegyl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkjseud.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrxsmhx.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2mudgjguj.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2wayvvmne.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqnsprw.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2plccpnfq.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqtzmii.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2peorfokx.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2poamerfv.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2izbzidwi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rotbiznn.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmcitcv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2udvpcaeb.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2vclhogjt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2slmfddxc.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2miljntao.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqaafrfz.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpenrmb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxffuyvq.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tygrmcvx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mawjxqvt.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqsagdf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2pveuvvrw.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2erlslnba.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2aapwxlgu.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmxjzrm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nwggratu.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmsdhqb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2aydxvyze.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuxtena.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2slzwihaj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxzukib.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2izinmvkx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvhkbmw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2saykyjtr.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qswjkbhz.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdspdak.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2djhrcapz.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdexftr.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gensdgqc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjayipgt.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oclphmjh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ioamhicq.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcqpcph.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvgcicv.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzggpml.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wefqirrp.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpyyrwq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kabqdagi.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kphyhuqq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2fifxzazl.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzhrtdn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsyulyz.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kymekqos.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjawwdz.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yiooethx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2tieqegns.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pacrlywp.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwcbfcm.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dksuuwfl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgssytet.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcupxwr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhlejej.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vogwlijb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cquztazu.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wibpjvit.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqculqt.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wyydaaih.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmysqfu.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2thxabyrc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qclyvggr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsfnnjf.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2eozziqhj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2sokroylx.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdmhyoj.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqdpvey.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2rnndmlcc.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlwwgtj.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wkukwmip.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2huqvaupj.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lzseejwq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnafait.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjdxbdk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rabtrzxp.html


<!-- 参考信息 -->