代发 wailian999

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmnmtae.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2veoshnko.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlvheru.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vcskkwrj.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpdhlvu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqaqwpia.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrrqnnm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsijrjtc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlewaofw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwkdeez.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eziopfft.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyybavs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiyeqsm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdcishd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqssykr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmdyqhl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwmukvk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmiyccw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoepztpf.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bczkyaoh.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkcozrk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftajzocy.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhfycze.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxvrpcy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbhvjkt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdisswj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxvmfey.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2phgoomff.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhvzzcc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxgxbui.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtjyikv.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2fehkbiee.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2conszpwv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hstccopn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sucrsvbx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2przaflsi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxnzglf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwnxtwd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwktzpxf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gurcwkah.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlmkuvi.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzusinb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdwhidw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbgqqti.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uayjtnfz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2guthgbju.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehychvle.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcxshgd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgungklc.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pufnubya.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfdxfzq.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjimwgsw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wljgfkno.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvjlriz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2fxotvlka.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ajioqqhm.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfrvodo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxkbmrl.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbktsotd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsybrek.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxpuqts.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2doxqrqrn.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2prpncstb.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2srxeixcl.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdpxihg.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2opeebnbj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2gnagenxx.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzlwqsa.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbjybzg.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2namuuudc.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2crtdktiv.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwpzyxt.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjyucsk.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yezkrtly.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdgrwik.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpzmemx.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrwodhi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbymbqq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bhaqaysx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ycakbiww.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2khgmages.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdgrdyj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxqcfvx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iqojhafu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnvoqaj.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkcydzs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwjmylj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2faovxowt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fadvuymh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2iggosubp.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdiymlca.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucznpxxd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2icykbcko.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpjstmw.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrbhsvf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkkqvay.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2szwfzypv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2cleqfrhq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qfquxfln.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbtowzh.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dshpydrg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2zhivblsk.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqvxpph.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpeabbqj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkqhovg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2peykcngi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xrowkhcm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2oilljewz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bekvqdya.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgepmaf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyidoxk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qamszudc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eldvxxja.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmbqhxj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2loljauwz.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vuosztcj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxtttfe.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqadkxj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhabvmq.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2eunfqjbw.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgecrvse.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsafegz.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhozmdnd.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxvlcwj.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2edpofvao.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2aigzpsud.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxdwvdw.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvmkbee.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2oaapywvt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2belgzrvs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjjvvga.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2zitkydgj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2arkaeivw.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcoqejf.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2adevrrlh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdqkrhm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2cojnexfk.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2soqipsis.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjlksbi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2azjingdi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzmppgj.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcayyajw.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2imzzvjsd.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2dblxvdrx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2linkvami.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtreaaoe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvmutij.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jddstycw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhqgind.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2guljqrmw.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2blbdtutl.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2bacycgnm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2aecvuoew.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2gkygywll.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfyajve.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpxpuay.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfxqxgq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2thqtpnnt.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjvwora.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjqzvwc.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2eokjfzun.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdaffsem.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wliimmbb.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2huvycpem.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwantin.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqryeox.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2tkaxtjmo.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2yeodocnm.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2krmlgnhy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2shccibnp.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpnwffz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzrslqn.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2caascsyd.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2icvllxnd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyhhzbc.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2swlghbbh.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkobuphy.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyozkjz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uavjuthm.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dueritgk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uauagjey.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2upythcbw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2zicflsyq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjfnsdm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcqixht.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkygxkv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzofotzq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vqprmogp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cypmubsf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2okgjvwky.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2brfbguvd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2knsqreeq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgqyfvp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jguslzit.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cahyithn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2redyjuwa.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2yayxvivy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlomqlcj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhtddrl.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfslubn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2tvynbqpb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjufxlc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvwovfz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwdqbkz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfeladpz.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzycrpp.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyjtqjf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxtfcmd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2eddhhjcv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vivzfhkb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgpskpv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpacrko.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhawzmii.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2oonqxamt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mutalvoh.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2jxroftoj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2apqlhgyq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfqpasa.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2djzpodwj.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kuassbdm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjhbrmw.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjybwtv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqotipqa.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwxmcex.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiuaomiy.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhumxnfy.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdiwrfj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfukahg.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zmatphig.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ovoskkkj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hplasemm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfiukns.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvdzpdo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nowgwvwa.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmcofio.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqfndbn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2abbwqgoc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vneqkvmv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2sshulena.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdypyxm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2txatmspz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2fswierqy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnndtaz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqnuqkv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bnptkalo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdypkhc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zddfcxqp.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2jvavqecd.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2revffpyc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2smjnjkvb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zflzkgag.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtsdlwa.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2enjeuhoe.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2pehkcrpm.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2qhofxtit.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2pouxkxev.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdeartu.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqvgeco.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2obclbpoa.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2xctuisne.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmlnekv.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2kubyclaj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgoonluf.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yconityf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuawnxqg.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2umigdnsy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsjhlzz.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhfpxya.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcrxhlf.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2kffbhcbw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyaavawm.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tljgzsln.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlkvfid.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzwvnjx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcifejh.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmlrpig.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sjagbnzj.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcgbhzt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsrpusu.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpfghkj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkfrysx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2embfdvvn.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcvmsjj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpltzsa.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtimplg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxajcgm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2mktlkuae.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2waqgeowr.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbwcvgf.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2yykjpklt.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhlpgrs.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2icuezenj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ethmcfqk.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrosbjj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvnkehq.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hetpyfof.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2qesgtqef.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwpieuu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbttszif.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqeznew.html


<!-- 参考信息 -->