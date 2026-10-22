代发 wailian999

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gaohongyu789.top/Article/details/gt2syjxyxct.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2yejqibhm.html

N. 数据结构与算法
来源：http://dali.cqqwz.cn/Article/details/gt2fwpjgkmn.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2mponvthn.html

[N01] 二分查找（有序数组）
来源：http://dali.mhx1999.top/Article/details/gt2wfxmwpbw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2jhhtvbwd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.aibaodan.cn/Article/details/gt2rafzufdn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuanzhike.top/Article/details/gt2nmszbisd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gt2ncmjhfus.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2enyrlvwi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2vkhtkxdz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj202588.top/Article/details/gt2pxiflrih.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2ormtsfko.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cdnleiting.top/Article/details/gt2uepyhvck.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigufen.top/Article/details/gt2mvfwfkwa.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jyoumei.cn/Article/details/gt2sxxyejfi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gt2yxsrjhxd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kdbadsaq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aizwys.cn/Article/details/gt2ercnywcn.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gt2ooysfvhq.html

Ruby: arr.sort
来源：http://dali.yuxming.cn/Article/details/gt2alhsrgxl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.pycfn.com/Article/details/gt2gazapodt.html

[N03] 快速排序（分治示例）
来源：http://dali.cucudq.cn/Article/details/gt2ixxbpcrv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yueranfly.top/Article/details/gt2nqmfdvfx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hfpthk.cn/Article/details/gt2fbusmeou.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wstvflqe.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gt2owmjacaq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.redwolf501.top/Article/details/gt2washxiiq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yonumen.top/Article/details/gt2fbefmjar.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.9152youxi.cn/Article/details/gt2goxljapr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sufxvd.cn/Article/details/gt2esqlkbfv.html

[N04] 斐波那契数列
来源：http://dali.yvedp.cn/Article/details/gt2ipunopst.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258888.top/Article/details/gt2kmqixkvx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dyracbgg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2hjpxgyww.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lofezczv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yongpay.top/Article/details/gt2txctkbod.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2kmchvvvv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gt2tothsuts.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2xuxjqpfh.html

[N05] 最大公约数
来源：http://dali.cqqwz.cn/Article/details/gt2adxssevb.html

Py:   math.gcd(a, b)
来源：http://dali.hammf.cn/Article/details/gt2jvgtxetf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aibaodan.cn/Article/details/gt2onzooscn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gt2kjaejqyn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gt2wbvaupli.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.birdmap.top/Article/details/gt2tnozymvk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.birdmap.top/Article/details/gt2wrujmmnh.html

Ruby: a.gcd(b)
来源：http://dali.jqgufenzy.top/Article/details/gt2daofiudt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hfpthk.cn/Article/details/gt2yglqcofp.html

[N06] 判断回文字符串
来源：http://dali.haohaochexian.top/Article/details/gt2kuorbjzr.html

Py:   s == s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pmkscosu.html

PHP:  $s === strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2xpeaftff.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2spttyniy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gt2trdanexf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guannengcc.top/Article/details/gt2zkmlbvcv.html

Go:   // 双指针从两端比较
来源：http://dali.yj20258.top/Article/details/gt2ltfxvvie.html

Ruby: s == s.reverse
来源：http://dali.jqgfzy.top/Article/details/gt2dozrzvmc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gt2sutwllav.html

[N07] 两数之和（返回下标）
来源：http://dali.svipenyu.cn/Article/details/gt2pymxucvx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnxiangtu.top/Article/details/gt2nerovwsa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fengsongda.top/Article/details/gt2qyljrzlb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xziqi.cn/Article/details/gt2fyeopkaf.html

TS:   // 手写 Map<string, number>
来源：http://dali.smart0.xyz/Article/details/gt2edfpzhbc.html

Java: // 手写 HashMap
来源：http://dali.yuxming.cn/Article/details/gt2bpionxbn.html

Go:   // 手写 map[int]int
来源：http://dali.nwbrower.top/Article/details/gt2ltcjlvud.html

Ruby: // 手写 Hash
来源：http://dali.yuanzhike.top/Article/details/gt2apowmqix.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.feifeiyinyue.top/Article/details/gt2fvydxuce.html

[N08] 生成全排列
来源：http://dali.xylfe.cn/Article/details/gt2clutjznq.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2jlkwprba.html

PHP:  // 手写递归交换
来源：http://dali.yangfankeji.com/Article/details/gt2ncodbefz.html

JS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gt2tngfbqhh.html

TS:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gt2nomkajek.html

Java: // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gt2fzpzembe.html

Go:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2qiyomtxa.html

Ruby: arr.permutation.to_a
来源：http://dali.zdqjudy.top/Article/details/gt2asmybytz.html

C#:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rajbktfg.html

[N09] 栈与队列
来源：http://dali.cdnleiting.top/Article/details/gt2isbtzwwq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.svipenyu.cn/Article/details/gt2xmbllceh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gt2ionmadsy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gt2evbcxnig.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenjidiqi.icu/Article/details/gt2hcckhlcs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenzaomai.com/Article/details/gt2wzodkdkw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.snrcjt.cn/Article/details/gt2dekybphv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gt2fsslnwjq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.fengsongda.top/Article/details/gt2iudjsyhr.html

[N10] 链表节点定义
来源：http://dali.zycfv.cn/Article/details/gt2okxnjpie.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2khaqrvrr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gaohongyu789.top/Article/details/gt2hxwgcpcu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gogol.net.cn/Article/details/gt2uwlvddve.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigufen.top/Article/details/gt2qljdfqld.html

Java: class Node { int v; Node next; }
来源：http://dali.jianghu66.top/Article/details/gt2irnesrjy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xinyue.icu/Article/details/gt2sjutcyiv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daria6918.cn/Article/details/gt2znmgdbww.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.c1oappe.top/Article/details/gt2fhzaglni.html

[N11] 二叉树中序遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2eyfwcpkx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigufen.top/Article/details/gt2rsvtlrfp.html

PHP:  // 手写递归函数
来源：http://dali.smart0.xyz/Article/details/gt2xmvgswlk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sufxvd.cn/Article/details/gt2cqhcxdrb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shuidangran.top/Article/details/gt2kghjcztd.html

Java: // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gt2xleoutkt.html

Go:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gt2niullhgs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shangyingyoupin.top/Article/details/gt2mnhmeijg.html

C#:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gt2lpiwafoh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shangyingyoupin.top/Article/details/gt2goytskdl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hammf.cn/Article/details/gt2nniqdwsh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tanke756.top/Article/details/gt2xjzjlhps.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqvgdjlq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gt2djwsrhrg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gt2phvzydtg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhoulong.xyz/Article/details/gt2gxjgqxav.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mkcfuinw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gt2shpcmqcn.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2aagixvri.html

O. 并发与异步
来源：http://dali.gzhubu.top/Article/details/gt2lbbdmgud.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2hzuglrko.html

[O01] 启动一个线程
来源：http://dali.bjfxy.top/Article/details/gt2ecjxatzk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhixingplan.top/Article/details/gt2ejxdjclw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinqigfzy.top/Article/details/gt2bgjxrozv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.aibaodan.cn/Article/details/gt2bhcfqnfj.html

TS:   // 同 JS
来源：http://dali.c1oappe.top/Article/details/gt2itmhiepp.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258888.top/Article/details/gt2qbnzrkdn.html

Go:   go f()
来源：http://dali.gogol.net.cn/Article/details/gt2mpbtyeys.html

Ruby: Thread.new { f }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xvsjeufz.html

C#:   Task.Run(() => F());
来源：http://dali.yj202588.top/Article/details/gt2lkxjdbdn.html

[O02] 使用线程池
来源：http://dali.nanxinkj.top/Article/details/gt2fahcegmq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.daxiang520.top/Article/details/gt2svznzsji.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yvedp.cn/Article/details/gt2btnmjude.html

JS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gt2qwbplwis.html

TS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gt2wyalcrgs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yuhrgspj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangshuangyany.cn/Article/details/gt2mznufmso.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ydzc1.top/Article/details/gt2isvhpwbj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yvedp.cn/Article/details/gt2elfxhqmw.html

[O03] 加锁保护共享数据
来源：http://dali.aizwys.cn/Article/details/gt2wwjdubqp.html

Py:   with lock: shared += 1
来源：http://dali.dashuyun.cn/Article/details/gt2abekerzz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.mhx1999.top/Article/details/gt2smnrtghh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.meibo888.top/Article/details/gt2idyzbnob.html

TS:   // 同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hseaoiei.html

Java: synchronized (this) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gt2ihuwsblv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daria6918.cn/Article/details/gt2tjcnwtkd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgfzy.top/Article/details/gt2izobzvdh.html

C#:   lock (gate) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gt2fhobdlbk.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigfzy.top/Article/details/gt2nxvcyqdw.html

Py:   async def f():⏎    await g()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ciiofjhj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.guowangkeji.top/Article/details/gt2fjakrimc.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2iecxfqxc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2khwfmccq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tianlin.xyz/Article/details/gt2eyiwnvfo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hammf.cn/Article/details/gt2dohklswi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cheryme.top/Article/details/gt2jqnmswok.html

C#:   async Task F() { await G(); }
来源：http://dali.zhixingplan.top/Article/details/gt2tgazakrt.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhiwuduotai.top/Article/details/gt2sjiqokue.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nwbrower.top/Article/details/gt2hsardbzm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tanke756.top/Article/details/gt2uxhuxuhy.html

JS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gt2nyhsromv.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gt2ucmiyehu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qvllajez.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hysaishi.cn/Article/details/gt2cppopqmy.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gt2yzmfsthb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.daxiang520.top/Article/details/gt2yajqnnjf.html

[O06] 使用进程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nwfcjiia.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dashuyun.cn/Article/details/gt2igklupbk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yueranfly.top/Article/details/gt2loxtsalo.html

JS:   // child_process / cluster 模块
来源：http://dali.havefunace.top/Article/details/gt2lqocyydq.html

TS:   // child_process / cluster 模块
来源：http://dali.gaohongyu789.top/Article/details/gt2ewffbvqu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.c1oappe.top/Article/details/gt2gzrgemfp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jlsjyb.cn/Article/details/gt2fgncdtys.html

Ruby: // fork 块
来源：http://dali.wangshuangyany.cn/Article/details/gt2ynujomus.html

C#:   Parallel.For
来源：http://dali.sysykeji.top/Article/details/gt2vqcbvegf.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2gsvhxaoy.html

P. 常用工具函数
来源：http://dali.daxiang520.top/Article/details/gt2stpknwdd.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2bljgqgjd.html

[P01] 生成 UUID
来源：http://dali.xylfe.cn/Article/details/gt2gqiafjzb.html

Py:   str(uuid.uuid4())
来源：http://dali.zycfv.cn/Article/details/gt2ooqmyoij.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jqgfzy.top/Article/details/gt2bmhzatrx.html

JS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gt2gkrbpnzv.html

TS:   crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gt2obbfssrs.html

Java: UUID.randomUUID().toString()
来源：http://dali.316326.xyz/Article/details/gt2mlqdicmg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yanxiufei.cn/Article/details/gt2sgphdiqt.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxinkj.top/Article/details/gt2atlfxiie.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ckesbkah.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yvedp.cn/Article/details/gt2mvsrjaby.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yuanzhike.top/Article/details/gt2ehleguwn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.redwolf501.top/Article/details/gt2ibdyauxa.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hfpthk.cn/Article/details/gt2afwqinyr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yueranfly.top/Article/details/gt2mjyftppb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shuidangran.top/Article/details/gt2tkxdpdjl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ydzc1.top/Article/details/gt2emsvtcry.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2nxdoijty.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tanke756.top/Article/details/gt2pyiootxz.html

[P03] 生成短随机字符串
来源：http://dali.jinqigufen.top/Article/details/gt2qqbtsype.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sysykeji.top/Article/details/gt2rktpqrgy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjiirmgz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iyjezysk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gt2bgzmrlst.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hammf.cn/Article/details/gt2ebeaigtm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jiagoushi.top/Article/details/gt2rietaxif.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lftcpkwq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fengsongda.top/Article/details/gt2lgwcreoi.html

[P04] 求长度
来源：http://dali.jiagoushi.top/Article/details/gt2thylusfr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sxryk.cn/Article/details/gt2yxforbda.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qkguwstt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xinyue.icu/Article/details/gt2rlfwjoqv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gt2isgqdyoh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenjidiqi.icu/Article/details/gt2vfguvmlb.html

Go:   len(arr);  len(m)
来源：http://dali.c1oappe.top/Article/details/gt2jhbspakg.html

Ruby: x.length;  x.size
来源：http://dali.xinyue.icu/Article/details/gt2ilixeexr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhixingplan.top/Article/details/gt2zndkwyxg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.fzhhl.top/Article/details/gt2xqmeherp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hnxiangtu.top/Article/details/gt2eryshyzo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rjcwtxmf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gzhubu.top/Article/details/gt2ujejufav.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yanxiufei.cn/Article/details/gt2vdatbfgl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sufxvd.cn/Article/details/gt2wttzjqbk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.9152youxi.cn/Article/details/gt2nhrgwaoa.html

Ruby: a == b
来源：http://dali.chenjidiqi.icu/Article/details/gt2swkircnm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenlongwang.top/Article/details/gt2ttlenxuo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzywaqi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gzhubu.top/Article/details/gt2gtzqkwis.html

PHP:  if (empty($x)) {}
来源：http://dali.guowangkeji.top/Article/details/gt2urujbcha.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgfzy.top/Article/details/gt2sviefanz.html

TS:   if (x == null) {}
来源：http://dali.hywenlv.cn/Article/details/gt2ueqyfsul.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gt2hxvsksyw.html

Go:   if x == nil {}
来源：http://dali.dianchejie.cn/Article/details/gt2vhfchpwd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258888.top/Article/details/gt2cetoggtl.html

C#:   if (x is null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vorntbfu.html

[P07] 防抖与节流
来源：http://dali.hysaishi.cn/Article/details/gt2lmjeabre.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yuxming.cn/Article/details/gt2fnqrtdlo.html

PHP:  // 手写时间戳比较
来源：http://dali.cucudq.cn/Article/details/gt2rsthbhwv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gt2yioseyyp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2diqewkqd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ivvv.top/Article/details/gt2dolhxwvg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hongshengwenyu.top/Article/details/gt2jdvadojz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yvedp.cn/Article/details/gt2sdfzyzxi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yuanzhike.top/Article/details/gt2sfzpaapm.html

[P08] 处理浮点精度问题
来源：http://dali.birdmap.top/Article/details/gt2jrqgofks.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jyoumei.cn/Article/details/gt2xzpaxgpd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fcvqiiat.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.quarkkingdee.top/Article/details/gt2dgtsfyya.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vrewizrx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nwbrower.top/Article/details/gt2iwtlnmph.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ivvv.top/Article/details/gt2oisfmvto.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gotoacloud.top/Article/details/gt2ifyrepba.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yuxming.cn/Article/details/gt2nxllcvdm.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2qunyrunu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cqqwz.cn/Article/details/gt2imcdtfcq.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2kjprpeob.html

[Q01] 创建表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mytwlbin.html

CREATE TABLE users (
来源：http://dali.snrcjt.cn/Article/details/gt2trknuvkp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cucudq.cn/Article/details/gt2irowdzwy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.mhx1999.top/Article/details/gt2paznfohb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.iojbl.cn/Article/details/gt2nwudzglw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jqgufenzy.top/Article/details/gt2yxzuryjf.html

);
来源：http://dali.tanke756.top/Article/details/gt2cerqhkpy.html

[Q02] 创建带外键的表
来源：http://dali.daxiang520.top/Article/details/gt2oynwwrmr.html

CREATE TABLE orders (
来源：http://dali.gogol.net.cn/Article/details/gt2hezjdlop.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.haohaochexian.top/Article/details/gt2qmejvciw.html

user_id INT NOT NULL,
来源：http://dali.pengpengdd.cyou/Article/details/gt2oubjpjiy.html

amount DECIMAL(10, 2),
来源：http://dali.zdqjudy.top/Article/details/gt2zsogsvna.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yonumen.top/Article/details/gt2zvormigu.html

);
来源：http://dali.daria6918.cn/Article/details/gt2ngzdwqow.html

[Q03] 增加列
来源：http://dali.cdnleiting.top/Article/details/gt2rpxxjcua.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenzaomai.com/Article/details/gt2sabejtac.html

[Q04] 修改列类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2qnrmycaw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ixocjcyp.html

[Q05] 重命名列
来源：http://dali.nanxinkj.top/Article/details/gt2xsuboyoi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.guowangkeji.top/Article/details/gt2uesejaqd.html

[Q06] 删除列
来源：http://dali.hfpthk.cn/Article/details/gt2flhbgtie.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ppjwa.cn/Article/details/gt2agchiusu.html

[Q07] 删除表
来源：http://dali.andypj.xyz/Article/details/gt2ydmseyfs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cqqwz.cn/Article/details/gt2dkeqayno.html

[Q08] 创建普通索引
来源：http://dali.chenjidiqi.icu/Article/details/gt2posiiciw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jianghu66.top/Article/details/gt2pptklzvy.html

[Q09] 创建唯一索引
来源：http://dali.yangfankeji.com/Article/details/gt2bzgbuott.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cdnleiting.top/Article/details/gt2wzgjfbbe.html

[Q10] 插入单行
来源：http://dali.jyoumei.cn/Article/details/gt2yzlnimyv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuanzhike.top/Article/details/gt2czsenmyz.html

[Q11] 一次插入多行
来源：http://dali.ydzc1.top/Article/details/gt2uljlfavn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sufxvd.cn/Article/details/gt2xidbdgsw.html

[Q12] 插入后取自增 ID
来源：http://dali.yuxming.cn/Article/details/gt2zkvfvwsg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.iojbl.cn/Article/details/gt2bvkutorl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.vqdsnc.cn/Article/details/gt2jxcgclyx.html

[Q13] 忽略重复插入
来源：http://dali.0kj1m.cn/Article/details/gt2skgvvbth.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gt2pldzdmqf.html

[Q14] 存在则更新（upsert）
来源：http://dali.jyoumei.cn/Article/details/gt2wuanatez.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuanzx.com/Article/details/gt2fbcojcfr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.aizwys.cn/Article/details/gt2aqxgkawz.html

[Q15] 查询全部
来源：http://dali.yvedp.cn/Article/details/gt2cugfabny.html

SELECT * FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2tkugklke.html

[Q16] 查询指定列
来源：http://dali.ydzc1.top/Article/details/gt2dkdxooni.html

SELECT id, name FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2ectayisn.html

[Q17] 条件查询
来源：http://dali.daxiang520.top/Article/details/gt2lbwdmflg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xuanzx.com/Article/details/gt2mhelmarq.html

[Q18] 模糊匹配
来源：http://dali.aizwys.cn/Article/details/gt2dtpfvjzf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.iojbl.cn/Article/details/gt2kdkpcevf.html

[Q19] 范围查询
来源：http://dali.mhx1999.top/Article/details/gt2pyyksedk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xkwhtfpf.html

[Q20] IN 列表
来源：http://dali.guowangkeji.top/Article/details/gt2hqcmuyau.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2rgmcwqcz.html

[Q21] 空值判断
来源：http://dali.vqdsnc.cn/Article/details/gt2rkoyeovf.html


<!-- 参考信息 -->