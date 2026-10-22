代发 wailian999

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmcifuf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2iytanohe.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2obcgposh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyyzqmt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2phasrdpx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2avmpaqtx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdfftzw.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvmiceh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrofmtwf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuyzjky.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hajfuslz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sentfyan.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2udugpkka.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqszudpl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2htwtcitx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mldjxhgj.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxuscwe.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qijtufbj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiagqlu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfskjdyc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbevrfqn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2inapcvxq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2owjudvsf.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwutftt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqasnljj.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ofezqytc.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jguwxlhh.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uaepvycb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfkgliu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqzkotm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2peoqldfb.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2etnudcii.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwgflyh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxrjlyu.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzpyrft.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvnaulk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2dubcsvgz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugerihop.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrxvyjw.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2xbefvqcn.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ebogmxeo.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsfybjf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ektemjyc.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhdgnos.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgwfiir.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvdnbas.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfcvjcy.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oumcdepj.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuitrpi.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2obgebxmm.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2shiihxfl.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsmgbin.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oeiqguud.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsfuogj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcdayir.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pshyqwny.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmrxmrf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cjligzkp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xikjdelg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqeutfo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcabkuan.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcdxfpp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2tajtvwsj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dujlsoyr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmduroa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsdpqfe.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsoejkzn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfucawtg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpexxgrz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqofilhz.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hakwhrip.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ijruabba.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2phmvgapu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2frnrlhzl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tucjhbsj.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yesfhvdz.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxqipsx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvtrasq.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xolzkhye.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtijsaq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2yanerxwi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcbjhqa.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2botoaccm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ygankuey.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjvossp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvndrys.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkktkej.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kwidvphx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpjotuc.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2wjekcuod.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nkaaitun.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjsqzrx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2yodyuusu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdppfhl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpyjmml.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2naomizpu.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvgxwwy.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsuduux.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqboyah.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2cujgvfyv.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2juifodok.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxgqcdc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxxljki.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rwonubtn.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzilquw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxkslnm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2giqvxbjd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2sabzkkit.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrhmkek.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2xsecbcca.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ozltvtmw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqgsydr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2fniqrzar.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjrunsw.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeurbkwa.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2shofxihh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmhbano.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayspmeox.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jhutnkpt.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzlkjtt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2empfrqgr.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyhttfz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugedjlxy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2mcivryaq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvnonzw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2vsguinqe.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqoxhrf.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxmjmdq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2huircxvx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrxmusp.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqdgmyi.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2orexutsy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2pshoupub.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzkprkd.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygexmtov.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsrnzsa.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cowiokrz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzupekw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2umkgjggq.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2jipkjovl.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2fhekqcyl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2aglujucu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ecczqkib.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsudxxl.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2abvffkam.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgkukez.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tqiimrgb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2msbdabjo.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpeyjaf.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbvoqca.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdfzxbx.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmhxjhv.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvmamma.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbmbdle.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbnyofj.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yvncerrn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2irtkjdnb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwvcaua.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2hymvwpji.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwznkwof.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2wdesxctt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtmkyzf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohiwgsrl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjmhisa.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtfysfq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2cxoziwta.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sasbjziu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2irnuriwq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnpcetp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zymxksmp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbyiofj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnbsgqm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2sgroeocy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjpckan.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbwuzao.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2chkgpfpc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnuiwtd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrquuen.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2myhjyijc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2riqkhipj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttiiebuy.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2sujnsvnv.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcoenio.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wctmjmlm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrdkqfg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mixbhbsq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2uoznwhff.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbdorfd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzjmtan.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwyeyqb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2boejxjrc.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2pefmfsfd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbxmjag.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnzbmqa.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkgjqeo.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrkygqg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2yymzjfdk.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyaantk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvfkywo.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2llnkbbqj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzisybhv.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nnboldyz.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2soytzsap.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2akrxmwkl.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmyrxxa.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtcdfnw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zrluxbwe.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysylvnpk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2cpskuqbn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qdweyojc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxehwbt.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxgdger.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfkordg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2maqeykph.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2fllairwh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2onlvaxtx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2raytjmww.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2yirlpfdy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2xivijomx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfphnvh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsyzdog.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2azfjgyxb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bobrddwo.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2xuirmkea.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2cqiobeeg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxqqnbh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2uyysxeyy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2gekjygfv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvzodeu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2pclhyjnr.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2welcjdub.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ohevessi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgjhmib.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgbdzgy.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2oczmnmrz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiixyzfy.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2lizelfgr.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbqseen.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnclfenb.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzzloen.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjcnzqs.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2hbeiqvoz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbiiqsoo.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvqokjt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppstorvf.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2zhopyqbx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cviqwnic.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yaobmexp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqyavsqz.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sngqzxhe.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqdfwac.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kyagfgkn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkyfbtg.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvyxonq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlaehzo.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnfnyzq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqzwvyg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjfdtev.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2jthghkbp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmoingp.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzdkbof.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2wtllxovm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbxydmt.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhdbnlg.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2plcyciig.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjuaiui.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqlwvhz.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfstfnf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrffhygv.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqmmtwm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsiliqf.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwirxbr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrhbytl.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2aimsjemx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcywyje.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2adirnmvn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2orudknjc.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2amyhbeld.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmzkrau.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxjaqug.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2nivhguln.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2scpvdcet.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2diicukuu.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpqghwj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2czlqkpof.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qjedtivb.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2trmfoqac.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdfpdkf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyvieyq.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvtxvit.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzavnahp.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcdqeph.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkemwva.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhtjjhy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2myhfbzmu.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2itmuvgxh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqphzudq.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sctuvgqb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2icbilcde.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2gssyshkd.html


<!-- 参考信息 -->