代发 wailian999

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zjhwuyzc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258888.top/Article/details/gt2ooiulxsp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgfzy.top/Article/details/gt2ccyjacry.html

JS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gt2cbsijraf.html

TS:   process.platform;  process.version
来源：http://dali.jinqigufen.top/Article/details/gt2qbrgwsgm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shzxlz.cn/Article/details/gt2qlnjmgrk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.mhx1999.top/Article/details/gt2djcdbjga.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cheryme.top/Article/details/gt2ililckcl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zdqjudy.top/Article/details/gt2frczkkip.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2uelxygsq.html

N. 数据结构与算法
来源：http://dali.gotoacloud.top/Article/details/gt2dfpyvhgx.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2gvfvtxgn.html

[N01] 二分查找（有序数组）
来源：http://dali.nwbrower.top/Article/details/gt2ouomolun.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rblnfnlt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.smart0.xyz/Article/details/gt2blmcpcgm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gt2hpljwvjh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gt2wqfrvkkg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2znlceflt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2eoqnptgn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fzhhl.top/Article/details/gt2madvmvuu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nzqlcmlw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daria6918.cn/Article/details/gt2ozwpwryy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.vqdsnc.cn/Article/details/gt2lvyvkpih.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sxryk.cn/Article/details/gt2kjwwhqcu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gt2kdltbdnt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gt2psyhrtto.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.9152youxi.cn/Article/details/gt2gjriaoes.html

Go:   slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2qatxirpu.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gt2hihuvcge.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hysaishi.cn/Article/details/gt2btalgedz.html

[N03] 快速排序（分治示例）
来源：http://dali.fengsongda.top/Article/details/gt2wxvkjztv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fzhhl.top/Article/details/gt2sbjlakil.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxuanxn.top/Article/details/gt2lkymhckt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mqhiabav.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gt2tjzzkqsr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yueranfly.top/Article/details/gt2audwzhls.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ibqrnqbx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.feifeiyinyue.top/Article/details/gt2qibglrgy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xziqi.cn/Article/details/gt2glxzlcpp.html

[N04] 斐波那契数列
来源：http://dali.zhixingplan.top/Article/details/gt2sxcdhfqw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gogol.net.cn/Article/details/gt2etaxoanr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vemlqjgy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gt2zkcgtfqe.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2celtzzgp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.iojbl.cn/Article/details/gt2pkzgkkls.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxinkj.top/Article/details/gt2fjczlhwi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gt2ukabqfhf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gt2vyrxqcqn.html

[N05] 最大公约数
来源：http://dali.tianlin.xyz/Article/details/gt2jxihtpfq.html

Py:   math.gcd(a, b)
来源：http://dali.hammf.cn/Article/details/gt2oeuoqlpb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jiagoushi.top/Article/details/gt2lpzhuvwr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gt2mibtyprc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gt2huuvphpy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ulbptwin.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daria6918.cn/Article/details/gt2oypbbmzz.html

Ruby: a.gcd(b)
来源：http://dali.jinqigfzy.top/Article/details/gt2oxdtdxou.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ppjwa.cn/Article/details/gt2hfdgchjl.html

[N06] 判断回文字符串
来源：http://dali.meibo888.top/Article/details/gt2ibqloogi.html

Py:   s == s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2cloofmij.html

PHP:  $s === strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gt2qkjodkzh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2dqacjulr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gt2rhwxegac.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.mhx1999.top/Article/details/gt2nisekeia.html

Go:   // 双指针从两端比较
来源：http://dali.yanxiufei.cn/Article/details/gt2cuzmfljs.html

Ruby: s == s.reverse
来源：http://dali.tian-w.cn/Article/details/gt2vhkroige.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gt2cuseikma.html

[N07] 两数之和（返回下标）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gyjnqpro.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aizwys.cn/Article/details/gt2gjwfusit.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.feifeiyinyue.top/Article/details/gt2vfxcojpa.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258888.top/Article/details/gt2syeiwqib.html

TS:   // 手写 Map<string, number>
来源：http://dali.yvedp.cn/Article/details/gt2aujrfpib.html

Java: // 手写 HashMap
来源：http://dali.guowangkeji.top/Article/details/gt2qzoewwug.html

Go:   // 手写 map[int]int
来源：http://dali.gogol.net.cn/Article/details/gt2jftgcnkb.html

Ruby: // 手写 Hash
来源：http://dali.cqqwz.cn/Article/details/gt2qaomtthh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ppjwa.cn/Article/details/gt2djtdendf.html

[N08] 生成全排列
来源：http://dali.sysykeji.top/Article/details/gt2mmcnvgvu.html

Py:   itertools.permutations(arr)
来源：http://dali.ybcxt.top/Article/details/gt2tspvppil.html

PHP:  // 手写递归交换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wmcrtswk.html

JS:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gt2naiiiblv.html

TS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2bktdehez.html

Java: // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gt2twjypnld.html

Go:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gt2jmbsloyg.html

Ruby: arr.permutation.to_a
来源：http://dali.quarkkingdee.top/Article/details/gt2torawxux.html

C#:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gt2umdeefyi.html

[N09] 栈与队列
来源：http://dali.fengsongda.top/Article/details/gt2ygqpqykz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daria6918.cn/Article/details/gt2nhdfimrd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangdashe.top/Article/details/gt2bwighgfl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wchyeeps.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhixingplan.top/Article/details/gt2aurnzymz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tian-w.cn/Article/details/gt2arhraqgf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigfzy.top/Article/details/gt2vlwctmdk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gt2vtfwqvnz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sweek.top/Article/details/gt2xuhpqrbj.html

[N10] 链表节点定义
来源：http://dali.snrcjt.cn/Article/details/gt2fqfygjlz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yueranfly.top/Article/details/gt2tzbjacty.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yonumen.top/Article/details/gt2cibcjtsf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yongpay.top/Article/details/gt2ybabwhhh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yuxming.cn/Article/details/gt2iyxkaugn.html

Java: class Node { int v; Node next; }
来源：http://dali.tanke756.top/Article/details/gt2frfnefjz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhongyouzk.top/Article/details/gt2acygtplw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gzhubu.top/Article/details/gt2bhwhymbf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxinkj.top/Article/details/gt2euuidmyq.html

[N11] 二叉树中序遍历
来源：http://dali.bjfxy.top/Article/details/gt2rixmbain.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fengsongda.top/Article/details/gt2ntptqtpx.html

PHP:  // 手写递归函数
来源：http://dali.zhengqikj.top/Article/details/gt2npknbnro.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.bjfxy.top/Article/details/gt2utkzmboi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gt2murkzzfl.html

Java: // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gt2kpnluajb.html

Go:   // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gt2oepmynzw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.andypj.xyz/Article/details/gt2awnyrlzo.html

C#:   // 手写递归
来源：http://dali.birdmap.top/Article/details/gt2pzcfhssc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangshuangyany.cn/Article/details/gt2xrnjotlh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cqqwz.cn/Article/details/gt2xgrrfptu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yigzzoof.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dianchejie.cn/Article/details/gt2magcfkaa.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gt2kedseemo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hfpthk.cn/Article/details/gt2agfsvnnn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhongyouzk.top/Article/details/gt2hhpyecai.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhengqikj.top/Article/details/gt2dbiwpglx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gt2vjerhbge.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2pzwxkwqp.html

O. 并发与异步
来源：http://dali.hysaishi.cn/Article/details/gt2briynmmo.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2gmexsaur.html

[O01] 启动一个线程
来源：http://dali.gzhubu.top/Article/details/gt2gqkegcoe.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenjidiqi.icu/Article/details/gt2jeefgmdj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cdnleiting.top/Article/details/gt2lwohfblz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gaohongyu789.top/Article/details/gt2hokkbkia.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gt2hrpuahen.html

Java: new Thread(() -> f()).start()
来源：http://dali.pycfn.com/Article/details/gt2gfazcnpg.html

Go:   go f()
来源：http://dali.snrcjt.cn/Article/details/gt2oitojqka.html

Ruby: Thread.new { f }
来源：http://dali.316326.xyz/Article/details/gt2qaxnmxfa.html

C#:   Task.Run(() => F());
来源：http://dali.wangshuangyany.cn/Article/details/gt2djshtyij.html

[O02] 使用线程池
来源：http://dali.hfpthk.cn/Article/details/gt2lbpisfmc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.kuanghao11.cn/Article/details/gt2wfqkkoyj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cdnleiting.top/Article/details/gt2seiglphv.html

JS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gt2acmhddlj.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gt2gvdeolsg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dashuyun.cn/Article/details/gt2qaivbdmy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.mhx1999.top/Article/details/gt2uplgzqxg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jlsjyb.cn/Article/details/gt2kxjtpyrt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cashguo.top/Article/details/gt2audtwzhu.html

[O03] 加锁保护共享数据
来源：http://dali.gotoacloud.top/Article/details/gt2ltqjsduh.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wanwobgl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aibaodan.cn/Article/details/gt2ndflzrve.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tian-w.cn/Article/details/gt2yhmfsxaq.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gt2oibfddyw.html

Java: synchronized (this) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gt2uxuwhsvo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuxming.cn/Article/details/gt2cbywdkmi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj20258.top/Article/details/gt2fbosfiuh.html

C#:   lock (gate) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gt2hsmcdxcy.html

[O04] 定义异步函数并等待
来源：http://dali.hongshengwenyu.top/Article/details/gt2njfmxsqh.html

Py:   async def f():⏎    await g()
来源：http://dali.shuidangran.top/Article/details/gt2lquhvwtv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daria6918.cn/Article/details/gt2xtfnbeoh.html

JS:   async function f() { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gt2xjdchoof.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.smart0.xyz/Article/details/gt2apnybldm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yvedp.cn/Article/details/gt2dtakemdf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.svipenyu.cn/Article/details/gt2wxscwqev.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ehwqpu.com/Article/details/gt2yxzpruty.html

C#:   async Task F() { await G(); }
来源：http://dali.cqqwz.cn/Article/details/gt2jsulugdg.html

[O05] 并发执行并等待全部完成
来源：http://dali.9152youxi.cn/Article/details/gt2ikukgrxr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinqigfzy.top/Article/details/gt2dzjillxh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fengsongda.top/Article/details/gt2rbqqutbf.html

JS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qgchtkzy.html

TS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gt2rrcwtzph.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.aibaodan.cn/Article/details/gt2uibhywxa.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenzaomai.com/Article/details/gt2jsqvzzwy.html

Ruby: threads.map(&:join)
来源：http://dali.meibo888.top/Article/details/gt2ngrlteeg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yangfankeji.com/Article/details/gt2kuvcknbk.html

[O06] 使用进程池
来源：http://dali.kuanghao11.cn/Article/details/gt2yblrusle.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenlongwang.top/Article/details/gt2nzlxmbpk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ivvv.top/Article/details/gt2bueeecva.html

JS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gt2rfduvwsy.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2trgsvsgy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yongpay.top/Article/details/gt2cyuisocb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.feifeiyinyue.top/Article/details/gt2ufxumktd.html

Ruby: // fork 块
来源：http://dali.iojbl.cn/Article/details/gt2wtoqzuwq.html

C#:   Parallel.For
来源：http://dali.haohaochexian.top/Article/details/gt2rmdeqins.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fnsdmxfq.html

P. 常用工具函数
来源：http://dali.nwbrower.top/Article/details/gt2vdesiulm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2xysasgqc.html

[P01] 生成 UUID
来源：http://dali.ehwqpu.com/Article/details/gt2gstxmsaz.html

Py:   str(uuid.uuid4())
来源：http://dali.yuanzhike.top/Article/details/gt2xafratak.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj20258888.top/Article/details/gt2bikfpxqa.html

JS:   crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gt2nzrhdtqg.html

TS:   crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gt2rqlxrtzv.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2firmisqy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shangyingyoupin.top/Article/details/gt2dramtfgv.html

Ruby: SecureRandom.uuid
来源：http://dali.smart0.xyz/Article/details/gt2vjdlcnfq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuanzx.com/Article/details/gt2qqgwyncw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigufen.top/Article/details/gt2twnrymwr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tanke756.top/Article/details/gt2lmmehjyi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2udacbcbh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenlongwang.top/Article/details/gt2baqhgber.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yangfankeji.com/Article/details/gt2hrrpohsc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.svipenyu.cn/Article/details/gt2cnekmqqe.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jlsjyb.cn/Article/details/gt2clwdiymr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zycfv.cn/Article/details/gt2vcvamtnp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sxryk.cn/Article/details/gt2wqkptdeu.html

[P03] 生成短随机字符串
来源：http://dali.shuidangran.top/Article/details/gt2hsjnxqiu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guannengcc.top/Article/details/gt2bcvyjvln.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.bjfxy.top/Article/details/gt2cyyijlfj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2beupttpr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gt2phugihjs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bpydusob.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dianchejie.cn/Article/details/gt2kelovcyy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yangfankeji.com/Article/details/gt2udytcqkw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnxiangtu.top/Article/details/gt2skxwztkx.html

[P04] 求长度
来源：http://dali.yuanzhike.top/Article/details/gt2nnudfvhq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nanxinkj.top/Article/details/gt2xeleejsn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gt2plhpzpnu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gt2fmpxndte.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sufxvd.cn/Article/details/gt2bovxrbkx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tanke756.top/Article/details/gt2ezffcdlb.html

Go:   len(arr);  len(m)
来源：http://dali.c1oappe.top/Article/details/gt2lltibphb.html

Ruby: x.length;  x.size
来源：http://dali.pengpengdd.cyou/Article/details/gt2rmmamtkb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.quarkkingdee.top/Article/details/gt2vglpdegk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daxiang520.top/Article/details/gt2oqwnwqwh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.feifeiyinyue.top/Article/details/gt2qdolzrpu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xinyue.icu/Article/details/gt2jqgyhifl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.quarkkingdee.top/Article/details/gt2cnjfarpe.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yanxiufei.cn/Article/details/gt2vlpidkit.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.316326.xyz/Article/details/gt2ssctkyxd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yonumen.top/Article/details/gt2lamdbuyx.html

Ruby: a == b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eiwjvpaq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yongpay.top/Article/details/gt2pehkfntl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hywenlv.cn/Article/details/gt2eekqzlql.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rvwjaaow.html

PHP:  if (empty($x)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2caaxmksm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhixingplan.top/Article/details/gt2soyjjkvw.html

TS:   if (x == null) {}
来源：http://dali.aibaodan.cn/Article/details/gt2ciyjiech.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2onewumxx.html

Go:   if x == nil {}
来源：http://dali.ppjwa.cn/Article/details/gt2hzidswne.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangdashe.top/Article/details/gt2fmytvrvm.html

C#:   if (x is null) {}
来源：http://dali.tanke756.top/Article/details/gt2tmhteewt.html

[P07] 防抖与节流
来源：http://dali.jlsjyb.cn/Article/details/gt2qhnwawxu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangdashe.top/Article/details/gt2rvweosow.html

PHP:  // 手写时间戳比较
来源：http://dali.sufxvd.cn/Article/details/gt2slqnslyz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gt2qvrwlxvq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gt2bynivbrb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yangfankeji.com/Article/details/gt2isebydge.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.0kj1m.cn/Article/details/gt2tukpntae.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.aizwys.cn/Article/details/gt2wpwgsbsr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yuxming.cn/Article/details/gt2amepcjnz.html

[P08] 处理浮点精度问题
来源：http://dali.hywenlv.cn/Article/details/gt2nhmufzii.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tanke756.top/Article/details/gt2vhhjpiwl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2dnongnrl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hnxiangtu.top/Article/details/gt2ypldssus.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2awjltyxm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yuxming.cn/Article/details/gt2zddeesvm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zycfv.cn/Article/details/gt2tbzdsqnf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gzhubu.top/Article/details/gt2wupptazd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tanke756.top/Article/details/gt2zeulkdtz.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2tlcqclrd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgufenzy.top/Article/details/gt2xxjncikp.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2czwoeber.html

[Q01] 创建表
来源：http://dali.hnqzz.top/Article/details/gt2gvfgnlta.html

CREATE TABLE users (
来源：http://dali.pengpengdd.cyou/Article/details/gt2bvryalcl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xinyue.icu/Article/details/gt2xgzyfpxt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.birdmap.top/Article/details/gt2ykwffplo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yonumen.top/Article/details/gt2qqxuytuc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sufxvd.cn/Article/details/gt2aaerdefb.html

);
来源：http://dali.mhx1999.top/Article/details/gt2lhuieblp.html

[Q02] 创建带外键的表
来源：http://dali.yj202588.top/Article/details/gt2eierghap.html

CREATE TABLE orders (
来源：http://dali.xylfe.cn/Article/details/gt2qvuavugk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gt2tlgmfdub.html

user_id INT NOT NULL,
来源：http://dali.yonumen.top/Article/details/gt2bjvyqvak.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2jnunvnff.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj20258.top/Article/details/gt2yaiggstx.html

);
来源：http://dali.guannengcc.top/Article/details/gt2lzfaugir.html

[Q03] 增加列
来源：http://dali.vqdsnc.cn/Article/details/gt2efxmineq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxuanxn.top/Article/details/gt2czkiynct.html

[Q04] 修改列类型
来源：http://dali.aizwys.cn/Article/details/gt2obnggcnc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gt2htbtszsb.html

[Q05] 重命名列
来源：http://dali.hywenlv.cn/Article/details/gt2jjdsdakf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gotoacloud.top/Article/details/gt2rcqvesld.html

[Q06] 删除列
来源：http://dali.yanxiufei.cn/Article/details/gt2rnbjtdtl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tian-w.cn/Article/details/gt2mqcnytzu.html

[Q07] 删除表
来源：http://dali.yongpay.top/Article/details/gt2mssezftp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tianlin.xyz/Article/details/gt2lxzafnfh.html

[Q08] 创建普通索引
来源：http://dali.yj20258.top/Article/details/gt2zhylxvpr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gt2pnmzkntp.html

[Q09] 创建唯一索引
来源：http://dali.shzxlz.cn/Article/details/gt2hprykzgs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gt2fujnkarz.html

[Q10] 插入单行
来源：http://dali.ybcxt.top/Article/details/gt2mhmtotfk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hywenlv.cn/Article/details/gt2oiuxavyf.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qxdtdaxy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gt2gqdqynxy.html

[Q12] 插入后取自增 ID
来源：http://dali.wangshuangyany.cn/Article/details/gt2xinyrqpw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhengqikj.top/Article/details/gt2bcmfckih.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.bjfxy.top/Article/details/gt2rjwxmfot.html

[Q13] 忽略重复插入
来源：http://dali.haohaochexian.top/Article/details/gt2mungrwuo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dianchejie.cn/Article/details/gt2dlkyzwjz.html

[Q14] 存在则更新（upsert）
来源：http://dali.xinyue.icu/Article/details/gt2tnduhcqw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuetiantiany.cn/Article/details/gt2vctjexbg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.wangshuangyany.cn/Article/details/gt2bzofwmfv.html

[Q15] 查询全部
来源：http://dali.snrcjt.cn/Article/details/gt2houazgmw.html

SELECT * FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wlacfteo.html

[Q16] 查询指定列
来源：http://dali.nwbrower.top/Article/details/gt2lohcfksw.html

SELECT id, name FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2gdluyeeb.html

[Q17] 条件查询
来源：http://dali.yvedp.cn/Article/details/gt2dcisbvlz.html


<!-- 参考信息 -->