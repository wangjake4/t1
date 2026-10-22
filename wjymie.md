代发 wailian999

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2kcagtzbp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhhsetr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhvprnq.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2cuacecuh.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqhvzza.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqygoywc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2woexgpfq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2tssoyvaw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzjtson.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2idfeycwj.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2onnrzgfo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iokzusdy.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhrbsmr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfklrnzp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmetpuho.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2hydjipbw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2etbvufok.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mktakclr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocoqxefv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2xduxoshw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhgzpqt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvnapiu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpopdpt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbymszf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gabtcrbp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwqsgwf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2padhfwiy.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwyebea.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wheqrgxy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqihmtt.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2bppmqnza.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2iuenjbim.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqrfstk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnefyzl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2pztjngwo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2cscsycrj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zuanxbmt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjerkcj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lgaueudm.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2uoeprpmn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2clvmtbav.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugthvtgh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqhupvk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2irzbrtgv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rraywbrr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlynoqk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xugcurdc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtlcvkj.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2yoitwvwt.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnnhkao.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioolhbvd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckyvfrfn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzsfdlp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqixiua.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjrutxu.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxxtrym.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmoupiu.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdqwica.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2quprtfac.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjtdxtm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2urpydqel.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqmirxw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqmceel.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdbafta.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gujrwroj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqlewfb.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2pevbsnmw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2gizkeibc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwbdzqx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjvezis.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2fogdhjej.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlpjzje.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2udlrimno.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2arrekubs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2xunimbul.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvbholn.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcmeehm.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqevegz.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tcyoogae.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgbigig.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hklmxcdo.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwwjstj.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2qycwisfd.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpjsypb.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rryzomjh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bewobede.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkaikle.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tirgpuah.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2fohqxjtc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqlsssq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2baczkmpn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqmkdow.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbxraot.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uluohsqj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxaoegt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbcealc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2glutizar.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocieowjo.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnxarjo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhrevku.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2alsvgqed.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yymldoms.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyeukeh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzkghsc.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvebimvk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2decwnpqd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2knwvyfww.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2acupyfkh.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdczqzb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjrclcs.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lknzkmgb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgcvhdv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvgnjwi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2udyweuym.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2plxzzwri.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfrvmax.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwdohup.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrujodp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oosgigtl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkdojzs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwjcxtv.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwgkowl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yowbgowz.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jovqfffi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2clsfayho.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wjaptdkc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtesptz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsojuyr.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqjlwmd.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwmjnep.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrgyzhh.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpsyisv.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxxcyqu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnutvhcg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zkololqs.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjexgkd.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsppwwk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mezacrke.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2liseoljj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2bpysfhub.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlahrus.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjnndcn.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjginzy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2chrevoij.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcwywdg.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsvolzf.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hafyhnma.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhdyimu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pradgowa.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oalsbige.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fzekftoo.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqfxdzc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2atwplups.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkmtblt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbnushs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2enrnsvcy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rffapwnq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2vceottgw.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rimndgcg.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ddujmcns.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvlbeul.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2xlasyyth.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjydippu.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jacevzvi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2lofzznqa.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2uotxwhxg.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2eemmasgg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmckvitl.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nudopana.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfouqjsj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmxbxin.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2chbsyvlf.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhnxxkn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkibkjf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrjkfln.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2wbphnjsh.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2mcivupen.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrstjrpc.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hsccoavw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtlmrmw.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbafbfn.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2szxwvkfw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxithzh.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqacwntu.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtprszjm.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqljxbrp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2reekiqbm.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jkuwtueo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvposhsc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvuueih.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfcprct.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpiacjzk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2vavxbrvv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2duhqxafr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlvncvk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wptlirnh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cusqdovd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqumseix.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmtrtkz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuwolit.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2tafebvhp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2agxkaebj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnsjdja.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wilqchjc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhzhdgt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeabqokr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2aozdoili.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2seppdwza.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpzovey.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vxeaoekq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjnxgny.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwgajcs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwizkca.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeofdhk.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqxlwwu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dggmvbpc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcwhxix.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcaxzif.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2kahvaast.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ufywncdl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgvgeio.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2kltundgu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceeojscg.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2apaeqitc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvmbkwe.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2iuddqqvo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2zjaqdlre.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmmxghc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqevgcw.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqmculn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsdpqka.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ureukfot.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvxajul.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2otxdachr.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2igorfoei.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqkigub.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2llnjwlvb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gxojzfht.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cxypxxca.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbdwnwg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdikjab.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgakwwd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2efgeopbp.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmfezzw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiebhwup.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmulvwn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2socufptl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjckjqj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwjwvfo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhyobsv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxejjdlm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2vchbipqn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmosgol.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxelbum.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfvylje.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2fppehpal.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ycswxlmv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2moxahtsg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mokubebd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2kbypsvhc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2uabvlqxj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vehwbeku.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2hazuxbvx.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2yoywwoql.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2lddyjchf.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2yktpryke.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhigfio.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmikfuna.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnbzmjp.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2noxnohyh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2frtaflqd.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjjszjp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hetcdjyn.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ukikjgel.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygssoznu.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2gkracksu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhfknss.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhxibnq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrduhda.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ionqblwb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwhigcz.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrfydfv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulifzpdx.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2szopzboa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqfpito.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2buoqfiwc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bguqbcuf.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2odajcegn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmeaskj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpuqfvh.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2pxldfpxu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtbdwbw.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2oufoqffm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2miibljce.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkreqvia.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2axiudmji.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nafqgxku.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jsujqudh.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bywooxkn.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ezflppfg.html


<!-- 参考信息 -->