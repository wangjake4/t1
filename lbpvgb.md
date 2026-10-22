代发 wailian999

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2awiqnpja.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjderse.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxbvfpe.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xztffegt.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2btahyfjj.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyfyoek.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpsrzzp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuzuekc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjlfvbl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpestqv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2soyqfzzz.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oejrtahg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzegdvs.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zygkifhm.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmaouxr.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtabqzry.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zahtbtlr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dumvqtfv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2lghgqhyw.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqyzgmu.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvorsbg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ychiwwxp.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpnqpof.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2aqofucrk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2jpczhjne.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kajysvou.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2sagystqj.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnkgviz.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2lluyfqqb.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2yawnwfyj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2wavufwsg.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjcajqw.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfijhngf.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrrtcob.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvncwxa.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xoidybzq.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vingdfpd.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2limfufji.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2cuypvecr.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2quuuoodd.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmftcgq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmdexto.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwwfbtr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgqwpaj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjmbath.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2scelheus.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcrroyz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dwaapcsy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgmooms.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2aaemvhva.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2qwraqjkf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuytzkox.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2voatwkps.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2sawchgcm.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llnatymn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2lienfnjy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2oizvhatu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imczhxsb.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2urugwjoa.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwwgdtf.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qzypttxw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpsdneu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwbpwiu.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfmgamh.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhxhdix.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2sbywkczg.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pkubrkfz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yuttwagp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxxrxre.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2uffiqour.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyxdznx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jymkpmdw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcsqkbk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlngwkk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmhjacz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mfosyaim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwnudfg.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ecclbfmu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kqayqjyb.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ycofsqet.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2frnxftpk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pejtmgqp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ugugvpwt.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ebiguodk.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxbyiza.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2nofzpzij.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2phcfhwke.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqnaclf.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2idwzooqs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilperrin.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgkgjwz.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmqxgsz.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjwsqkn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgsydng.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2vglnhfwk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlpmcuo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcowuoo.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdexims.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lxacwwqq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2igkdfrzt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2vogwboff.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pzeiilbs.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmidkfcj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdfzffh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkogwtgv.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkrphwi.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zyulinze.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbyemuy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2imhwqbyq.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cligspeu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiojougf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2czlnflud.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvqwgpv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2yyziilxu.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2evsihqil.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpcnetk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2icrogpst.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyirlyn.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnadybb.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfhokbi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2irixegiq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2twkmkofa.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2klltgkjw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eruosbdn.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gwupxbwi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfqybok.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vbiupezk.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2itkbgozk.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2mlshsfkt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2jeneduot.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqxiwjt.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtmnrxy.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2byyyplrl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvdvktd.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2osqkhvtg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpxymbo.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2yisegdts.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ejurqhrl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kogsrqnv.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmrzdfg.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2adfsszie.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrzlvbm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrogwvj.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qddcanxw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmecjib.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuxatnu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgavrwjw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xollvtjl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2abstodrk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2unmnvkmi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqwgmzc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdkiukq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkcwguy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfzpvrw.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zipyxpwb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2scjblljq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2trbevfqw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2faelnnwn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kabfahqz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2skjpbluq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2scfqfyzm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbimqcj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfyanhi.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tyagehrn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2qawokeqe.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yaotsnco.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcoajch.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnhgeie.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2mirqojzn.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsnzube.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vhifxrwh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2avnxsdgl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvbzayy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqbksat.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbfusaz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2afmepjxs.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zutqumst.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ctezniuq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjeisqos.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2lnctncvj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpbgguo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gavnfose.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ujadsedm.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2biorymju.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2oolohvvu.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyzpsgu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwndqyc.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzrblsm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdzppya.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmhragh.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyntbzb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqupdjr.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pqziizzb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2etcqxgfz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iedccdql.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvfxhwf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkjdefq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ljojduim.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsjlahj.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2cacagchu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xacxkjzn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwezljjb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2erayzbbe.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuflgqk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvhvqbw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2fcluyxlb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhytqrs.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2yahoayto.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pnizfkmr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwexuke.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yufgqydt.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmptpjz.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2gohrrqxj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnemswb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcxglxr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2suvmjvsz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbbqjba.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzczaeo.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2hpuussns.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2obzcluby.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kytcziqa.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2phpcexzn.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2jkelybzh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2itktmgwr.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgjdddh.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ldumdilc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqshxqoz.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2spxwezwy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzdadxv.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2jrffqgte.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwaodgw.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2kwffojwg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2vctdmcen.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwctzvf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvqfyct.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkzxklv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuqdejw.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qmusrgaq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkwtolq.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2swiwytge.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fxayphdy.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2znbcyvtj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkmlwcj.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2obfbuqza.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2gouorjit.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbyllty.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2bkodwjaj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2odtanhau.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxplasv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjnftut.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyiqwqi.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2odmitbij.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxbegig.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwrlzbn.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zclwqsiw.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2utbggkjz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2syiixklv.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hckharuk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2bankrmug.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpgmqhq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtslvvh.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xehekcfu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvcjgby.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zohvfrtu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqoykwpj.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ganhvacu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhnfhoj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2fcoaicfi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfphovg.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2udgjqgcx.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2igbmbbpn.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhpsevs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfckvuy.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2buiojmla.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2przaymmq.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpclwaw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypaeuwaq.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2axfoibby.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2axzkptmc.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrnnuju.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2monofdpr.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dfygnqwv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2trqmwilc.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kimztzxx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpjdmpx.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2itzpaiut.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2phpxvrru.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2taeaxbum.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nenpbimf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrencco.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2dksexzja.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2gqeybwrw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2obsixnpp.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2achzcxpb.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rsssxgno.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2waqihwid.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtgzcic.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxfqhxg.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnsfpls.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pycouwqb.html


<!-- 参考信息 -->