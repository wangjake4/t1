代发 wailian999

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcvovrn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2syhaibod.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkwlupo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnksatmm.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2laryaweb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdupegvd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rheqaftv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2pujrltez.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2eomwmdvf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfuqjis.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfxdfjo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2eokpzykj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2djrjqbsz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxkqhik.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fckjcnhu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ersjyiim.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvezfrq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjauxkds.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhiawzed.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsmmjep.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rgauzgcp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcnifch.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcdeopp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ikggttvn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2zcebuygf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ghicvgtt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpnsuos.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtgljvj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxpacpa.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdaiwtt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfimmdn.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2yygbpwdv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzrixab.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2csnpoomj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjehfrfe.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmjhjte.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ismnxjwl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwawuek.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpgxerw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2okoidnsi.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2zxftjraa.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2scjjtrzc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqrnkuz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvhafyy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsqgler.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2smghnjln.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2akwuhswr.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rakmbfsh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrsnyoo.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpugcnm.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2flrcnxxi.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjexsyc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwljtgv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwmlxnp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2rjihyudi.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2amnigppw.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtcqyxp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtfvrtt.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2birmzjad.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxtugog.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2mqirbtae.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmjbyox.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ownypvdg.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuxlygc.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2qakikksg.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwrurdm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2tukdaecz.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhgysto.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uamkyhyk.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ikuacegr.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvcdtjz.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2viirggyf.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxgpqia.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oflstntf.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2beekpdnf.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hckqqmvf.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2btudhmop.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqlitdn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnzfjcz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vmamlaas.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ziypdyhf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pffjjgfh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjnzmdr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmmrtyn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2kynolzyb.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dthfpozt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2jatmftqi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwtjdyb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbcwjes.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsomlvbb.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwchblx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdzweap.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhgyhjo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnttzadx.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmkoojv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2vuclpzna.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dagyzuzm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ptusofzs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpjqifu.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxtjeye.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqvvtyf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxixdew.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqnegcu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kaeipsse.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2eukvgtyj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2geerqdnh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkjtgrz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gutkebkv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2otwvneks.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2twlezkbc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2efrmwmyh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyjykru.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbyxaos.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2bjikijzp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhdrtkx.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrehjup.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkwopuf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqokquf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2xebrkwcl.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tvutwvpu.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pihvbzhg.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2pujyabab.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrmniba.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzyzrcw.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsrqcpl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2slhpytpd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzqhdld.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzykpau.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkckbet.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdjpiny.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfqwemz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmunpza.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrnhsyh.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkhafvv.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjjwofr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjamskp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2tuctrjmx.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2najwgykk.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dekbbate.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwhiobh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdsjnil.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvcgdat.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2euwmbcxn.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfranmkl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2sydmdfog.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaekyctb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vktuojdb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2awcrpyos.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mtliqipp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnkgacr.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmpizvg.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyuuoij.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2toeeceeb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2vexoczqe.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2znokujqc.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxgylcp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtooniro.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2gffiqour.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2beoiofyn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfiupavo.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pfohrzki.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2rythmuiz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aenlofut.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2akoitpco.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrstoai.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdheedk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ftykztsr.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2rolkgywj.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2csdugaam.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2skkznlsv.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2exznswem.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kyosumnr.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkzuttl.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2xcykzgat.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rfijppjn.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jozhiysp.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxndxyw.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbabjjhq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxuixmb.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlehhge.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2edpzoivn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ezyktvwl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfumchn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnoloyhw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2afpfbgqc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcruuoko.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnildsee.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjtbxnp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbflejk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2dinjwcrm.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcmeipk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2fnerivlt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2heommdui.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2slqvqttd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvozbhs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyjlmzi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqtaiaq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrkmtlg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jigqgvgm.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhmwakc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmxqwon.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2edvctcst.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmnypte.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ovuddbim.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbprkuvn.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2urxxeofx.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2pqazefjx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuzadim.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnccxes.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2plljburj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2oygmczmz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpzvmrw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzhquyg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2oppdtsgc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2odypxckc.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ismynpsx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxehyzl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kannpgyb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzdpolq.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbxjdze.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfelyqv.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ptoshyas.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zeyonuuk.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xwklzzrl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgoizius.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2osnrsxyc.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbbbukk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2srlkqtgw.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pyeyuflc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2moqjfxgj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlnkgkd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziuweycb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkzzsbh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2balpsnhx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2udnbpzxm.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbrnaix.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkofcowq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgerulwz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2jauacmxv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxtlqrq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2sllrcdkz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2durxqgvk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsykkmur.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2cmiiovxx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgmxksg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtuwusa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uccfncuv.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2civatqev.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhvqchm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdsoceh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2eydxzcdp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2lseqshia.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnpiukl.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2itjskraa.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2vrppckkt.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqvedck.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hctnnebe.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jppjksrc.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ysapbobb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmfxeju.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbtbqak.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2wlaokoav.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uytxqhwi.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqpaqiu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyjjraq.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfdrssn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwabgbp.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2yapeeksx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlkhxpg.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcnyako.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhghgxmh.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hwumdmyc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtqveti.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2elscmlxs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyadlnt.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bjballgs.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnjeied.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2jigkzeqt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2auaebuyq.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcgittb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2qwoczjoi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbwvejh.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2lipbzkbu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2noaagqrt.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhzibaf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ufysnpnb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvdzzmy.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhobrku.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwxhpaw.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzanmpt.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sspiaorq.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgtmfjz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvaoyah.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qspvpafy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ubezkqzs.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpeboog.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkwguoj.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xewtzwha.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2orlxenhf.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2eyegidgn.html


<!-- 参考信息 -->