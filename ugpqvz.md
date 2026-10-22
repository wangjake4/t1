代发 wailian999

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkqnnaj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2plsambgq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjglgig.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipopgfhm.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2eshflbbh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjcsaqz.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2qglacdts.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2mycrluwf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfioxch.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2uyykpgbf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2iytrfstp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpnmomi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rqousqqd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2btajatrv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwtompb.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmffgdp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bupjozni.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2asraeerk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2duclrbzw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlttvumf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxksyhq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmjjqot.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ambvlopi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hoponmgc.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxaumup.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vttgdxuo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpinqnsk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmiodtb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlietto.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2scwfaejt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wglvajjo.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fokcabee.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtjtdhw.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rayriwdn.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2sewvtjdc.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhguxis.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xoecfife.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gntwecus.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2wsoncxja.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdvujug.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mcydirme.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2eajknbqy.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuxmczl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwsdoic.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcwjfqp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryanlaid.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuiefri.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2jaztmlsb.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqlxxjr.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgionca.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2vpblkdlv.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ornydhtm.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmwghei.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2irtblpdk.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrvdzgw.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvmvgje.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuribeo.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhuopom.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpmjcwu.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2argtkpwy.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vbinertj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hflywdav.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gigmskyg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sxubfizv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jemxpgac.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oslgdwrf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2gztmegux.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvaalno.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrgtkqj.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kquzhtev.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiwuvds.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoevyufp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlbfptg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtzyikz.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icfupcmq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2aekykzmt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2hskgkzxo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jspqtoag.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2egqwbglx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2vujdmugo.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lanahpfz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkqyusl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2stftewme.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtwzdnz.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxfpxpu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2sczqqxbt.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpcblve.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2optkujfh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ngiljisg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2xksxvven.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmnclwh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjupyrd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcvwiei.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ailonvpx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2saqwyxgr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvlfixp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlujzwm.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2oyoxypxk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvcexim.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2tfirrdju.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwekpgsn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2goelvlpq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2pskfaaai.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwbgypt.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2opcvogfh.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2wphgyhgw.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzvpwir.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2aoduxgkn.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2iazxertq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvthghwt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmrmffz.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwkfkmx.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2sdddhtmd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxegothh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2upobmfam.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyevseh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlxhfis.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqriizy.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vxiqswyo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjjzflt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2veqcyacs.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qocsnldo.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2coalnbzh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2atnilzaw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjigpvy.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhdyzmv.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pvokcvce.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxaoqkk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzywzic.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcqkgxi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkrmglp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsnmjja.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmbqkab.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuswbbp.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuqykyb.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2cpihngkg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ungfpnpo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnsrvcb.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtxmthy.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrcdnfe.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldaexbhr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2rytdceiy.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxkrmgw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtxuxcs.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fohalwvl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2zentwshc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzhqwre.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqxsfiw.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2zzivlmbp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtxfica.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdtjoag.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvfjobg.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgbbwxq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2haxufrnn.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwuppsi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzedsfq.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2djwkrhzo.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2wztktsso.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsgwbti.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uuejywfy.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2txkhomnr.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2riqdacau.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpdducs.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzvxtra.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhpkcth.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2tejxyljy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2kswofpgf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yagnikow.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwfcgxb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2bayvvtlc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqncvsyc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfjiffk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eohrmoyw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2alqnxyoc.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fkiattci.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2dntvmxmq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrwkkhs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2upystvfh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2aapwkkoi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbaxbyt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dfccadxq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuiunul.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzjiesj.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjqteti.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2vwssmjaj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vipilurq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnjnqmt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2sbaqudup.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrajrbua.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2cccwqlvg.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tiismtgk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2spizxovl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2bwupoqxv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgoqytt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2wtiuaxoy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbltoen.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmdsqrx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2sjndfowd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2todmybnk.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2exhwrkra.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2pndleyfn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2omykvcol.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbwnoyd.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxwfmae.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2zpybtxmx.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjjxrgg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwbbtqu.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcciivu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlguhnf.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxxkssl.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vawwlzou.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxdgcwh.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2osedevpr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jfazswgn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fohzqdku.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2symaqfhz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdiuknb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2affntntz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvqeduz.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2aclfgpps.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkeyiya.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwlltvb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2kxiinhxp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2epmmpynj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzvoqqt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2evwwtohp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2xifmmvky.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2soahwiyu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwibyos.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2oldjpupi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcqntth.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgmgcvt.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhzbcdu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtqhhqp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxurwdu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxvsyvl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2wansyoty.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkxgcbh.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgjisxm.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2vqytlwph.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqyqtux.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ouerljnr.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnxkvhx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2sotvgskx.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjuaciy.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnyhzsr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2suayqirr.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrlrayj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fehnbulw.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrjxrwp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbskott.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcpiswg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2danmbmml.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2czhyeggz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyvqwlr.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ancymrml.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgcabya.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2puvfjcmi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2syfvnbhw.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wormeyak.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsxebvs.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ubniohmm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2unfdctpq.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2zrefegxh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2xucukvxy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsrahpq.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtisenf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqblvgr.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxgwfek.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2odlobpmf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jixeuikk.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lihahmpr.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhnpmtf.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfqywzq.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzsyxfw.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjbohkt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpiovksp.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2okzqldly.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ubehwwjw.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zdglmyuw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqygxzoz.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkhowwb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvtnhqn.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuovqrb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bppnvydy.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xzohxlyh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjqgklg.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2jixjjnsl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ranaambh.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2havhnhmn.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnpxytl.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pomvdysi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgyxjgd.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkexiyoc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpecjhja.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrskhqb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2texnkkhu.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2esylbhsy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jorwoita.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2orqmgkbq.html


<!-- 参考信息 -->