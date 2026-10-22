代发 wailian999

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmknowwe.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqtxtjp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsgjcux.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2swfhfauj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2bycfzoiv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjjdgdw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsxjqgz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjtxfpc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsjsyts.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmcmfmn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcgpjnk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvlejil.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2afuhjdyx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdiatehk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtycclv.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lenyyoug.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjcexpr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2rccjmupu.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2yagrqrrx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2iupvvioj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyyewyl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkykjyf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbyeamd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcfyfzh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2diinvcql.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwdoucn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2acphhkpe.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2zcixcyfq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mafpofnw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyazyuw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zerhzzua.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2eczpauao.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fneruhlw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfdazpm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cghvnbyd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzriqfl.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjffpyup.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkjbwme.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owvrhfah.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhxoctg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dilnbjkr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ycimoavw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzokqolb.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyxsswj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lluzflwc.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfvbdlp.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2okmhornl.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzngqws.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjlqkpr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzallnh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwbigjs.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xgchjybd.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gswpnzsk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvkuilj.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2gamuqdwh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2erauknxa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbgncoo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2liuxlfau.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2gqarpphi.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfxjhgy.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpwnkjp.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2coyrevvt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2lekgiqyv.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2pudhhihj.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbzeyxb.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2gymbvhmv.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gsisoigy.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuoxmjs.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vetpoyac.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pbncqyvd.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2zztqxnvd.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwzaklj.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2todskyob.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zekwilpt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hrprwovk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdlgsep.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2duxeoclk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhqlelu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhrczwp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qupvgrif.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyxakqa.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jrapfugb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2cywmjsju.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idbbrkqn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pweademm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2osckfyhx.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esxaakiv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuefsbc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2twajdwry.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iggnohrc.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxmjxmy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2agsxeznr.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmldqrf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2srwkjzmm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2totoscmw.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mnthuyda.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhiodra.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqkrcjb.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyjhfnj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2avnxcnmk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdqfwpk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2vodighlk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjziufb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmvfmay.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2azxthhwl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeggjops.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmurnij.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lyazfvon.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtntmbm.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2tszgxade.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzxbetg.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2xizqcoau.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xuiqsdrz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrftxoa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrrxuom.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2onqshmkd.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2brxwsrmd.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2eeslwvdk.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjroppx.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2vmijneme.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbiqffq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmvodxq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dyccvice.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ttommgyu.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cqndqqye.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2aadmyolg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxowfpf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2cktdvyst.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcksovb.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2zavvyekc.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxcfzcz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxorheh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpcbipy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2uuajkvie.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikywxgva.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2pypiypxg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yijhercv.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbtkkrj.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlyjfog.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjnvizn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2bgddqvzy.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2adgsidlf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fobcxkjo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2mulrwmxt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmiqiig.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkhjmnt.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2obxhzjdi.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2vulcxyme.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdwxwph.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2mkidecsd.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwqupgv.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmtymwu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmkeani.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulchmlic.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2zltpdrjy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmlulyw.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2aafmomxs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdniruk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ffofqrsh.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xtktvzwl.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2oiikenfg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2esbxehqs.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbjharj.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2lfubwova.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2uiasxjfc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2omentsvz.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsuutoy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlipxvm.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhpyryq.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvpntax.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkrxuts.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kecafiop.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2msuhcshd.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwjxaxp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdciazq.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ppknkrqz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2donceimt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkxvppw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtirqqdd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsibgmh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvnapsy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ruuhjrsk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2cygvphgh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tppcwjsz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2agrhpzvu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2jgaklwwc.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lngcqbts.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2dssmpjvk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvsvlfd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyulxko.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gemxhiue.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxoorfl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxrlveu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqoctjch.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2htapizca.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxulrkx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrnkmej.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yznhlvtq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2pvohquzu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcjddpc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2osrdtigs.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvylakll.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdwwrpm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfcwjyd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2covosiqn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtmoxtp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2gjemvisy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ricmgbfq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hirfgglj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2shzjaabq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixywjmog.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2tndvnlyo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2gpurouib.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2yiutptsh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqyunqz.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tblajeyh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2uextutdy.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfveopl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpsmoac.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkavogi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzmarzm.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhojshkj.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpkqgzz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxwepmy.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zluohzzw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hctnjbla.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rzscpygd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpuqaqb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2nirblqvu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdrsyht.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2czddyhti.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2oswnlmhf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqwsbgc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpnziyc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2itpidfoc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwgnqin.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpzddyb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbruarh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvoafclv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2nhepihhh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ijninrvb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfcattl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmnvakx.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2swlqxeuy.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwatbil.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2issvomnz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2yddyvbyz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2fmedlear.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2lmeveqmv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kftdkaen.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjiojjr.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxjzlmy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2etvbnkck.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2uwruwdxq.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2qejximaf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2csgvbxlh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2nagqmbav.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2tykaerng.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkymlslj.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkwbcxx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxivxvi.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2wfublpdu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdyseqc.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyvcqxd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2urluufmj.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxozhxs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffchmjrg.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ihstjosj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hftcaauq.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzjvmrj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xypsvfyq.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2udsfsmbu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2otrthqti.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmlvjon.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sddthykp.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhhvirm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2xbupwiov.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ebptuuxo.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsoqjyf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pclwespj.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2etggzoex.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2auwvsjiz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsgvetz.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2npnbxbez.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrtvxlp.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vielhhfw.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcwphnl.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzsfazb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iywvspqf.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2faoxjkym.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2bramlilg.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrygtqu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2akkaktba.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmebfxu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbsjcbz.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgccnjh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfezrpt.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zaruiadm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhahidx.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2antflsae.html


<!-- 参考信息 -->