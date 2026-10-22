代发 wailian999

[M08] 获取系统与运行时信息
来源：http://dali.jiagoushi.top/Article/details/gt2vkbyorub.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ivvv.top/Article/details/gt2xrkzlbzw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgufenzy.top/Article/details/gt2fpmtvbyk.html

JS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gt2ffqctcdq.html

TS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gt2mnkoxsyr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.9152youxi.cn/Article/details/gt2nqwtuixm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.iojbl.cn/Article/details/gt2aipfyire.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jnydaomr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuetiantiany.cn/Article/details/gt2mzugsaxu.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2aowymhuy.html

N. 数据结构与算法
来源：http://dali.yanxiufei.cn/Article/details/gt2ggpxeily.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2cgbwjheq.html

[N01] 二分查找（有序数组）
来源：http://dali.dashuyun.cn/Article/details/gt2rkmtpjdb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.bjfxy.top/Article/details/gt2jtoijxgd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sufxvd.cn/Article/details/gt2hytnwgsm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gt2fkjrpqpw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gt2aalebvra.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2pidchdhq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2jykidlsg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jqgufenzy.top/Article/details/gt2qrxqqwlr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gt2hdukaamx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuxming.cn/Article/details/gt2zlsodfuw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gt2ukoxwroz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.havefunace.top/Article/details/gt2zrzglkuz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gt2elbtmgaf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gt2sstsjfpv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cucudq.cn/Article/details/gt2vktdmipt.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uhvrrgxn.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gt2yuyeffvv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ipbiueja.html

[N03] 快速排序（分治示例）
来源：http://dali.hysaishi.cn/Article/details/gt2lzcrtkjr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mxorwitk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuanzx.com/Article/details/gt2jsytpjik.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gt2zuhdcvhh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gt2recuuvcb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aibaodan.cn/Article/details/gt2tkcqalhy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yonumen.top/Article/details/gt2rbmzmdmz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangshuangyany.cn/Article/details/gt2hgnxrnky.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xinyue.icu/Article/details/gt2fahjsqjx.html

[N04] 斐波那契数列
来源：http://dali.zhengqikj.top/Article/details/gt2evqdscpb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gt2lqqwrmjn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.guannengcc.top/Article/details/gt2ibssicun.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2pbboqunm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pexpmrms.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2nshpemvv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tian-w.cn/Article/details/gt2fmbiuygn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gt2eckmxorz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2zkedcwps.html

[N05] 最大公约数
来源：http://dali.sxryk.cn/Article/details/gt2kzqqmaeu.html

Py:   math.gcd(a, b)
来源：http://dali.havefunace.top/Article/details/gt2mcdabuep.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ppjwa.cn/Article/details/gt2asmtbvyq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gt2syifhnay.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.snrcjt.cn/Article/details/gt2ypuclmgn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.snrcjt.cn/Article/details/gt2wplpxaed.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hfpthk.cn/Article/details/gt2dkmrsflg.html

Ruby: a.gcd(b)
来源：http://dali.bjfxy.top/Article/details/gt2uoantqaf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vgnjdbww.html

[N06] 判断回文字符串
来源：http://dali.yueranfly.top/Article/details/gt2zronarsg.html

Py:   s == s[::-1]
来源：http://dali.sufxvd.cn/Article/details/gt2yiakfzjc.html

PHP:  $s === strrev($s);
来源：http://dali.andypj.xyz/Article/details/gt2zenfqkzv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wodfxuun.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xllnndso.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuanzx.com/Article/details/gt2omjgtqyv.html

Go:   // 双指针从两端比较
来源：http://dali.yueranfly.top/Article/details/gt2wtfmlqmt.html

Ruby: s == s.reverse
来源：http://dali.zhixingplan.top/Article/details/gt2dumkxvof.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gt2vcbupabh.html

[N07] 两数之和（返回下标）
来源：http://dali.cashguo.top/Article/details/gt2pceggdal.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ydzc1.top/Article/details/gt2tijnisbs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shzxlz.cn/Article/details/gt2aqrylkvk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nanxuanxn.top/Article/details/gt2xjddmilk.html

TS:   // 手写 Map<string, number>
来源：http://dali.sufxvd.cn/Article/details/gt2zkqgzlop.html

Java: // 手写 HashMap
来源：http://dali.zhoulong.xyz/Article/details/gt2nbpmuvny.html

Go:   // 手写 map[int]int
来源：http://dali.cheryme.top/Article/details/gt2helxnsaj.html

Ruby: // 手写 Hash
来源：http://dali.ybcxt.top/Article/details/gt2yowcdrbu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hammf.cn/Article/details/gt2locdjclj.html

[N08] 生成全排列
来源：http://dali.0kj1m.cn/Article/details/gt2axshkxgo.html

Py:   itertools.permutations(arr)
来源：http://dali.yj20258.top/Article/details/gt2powfxlvt.html

PHP:  // 手写递归交换
来源：http://dali.wangdashe.top/Article/details/gt2divyexjj.html

JS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2qsdgfgpy.html

TS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gt2nxhglsdu.html

Java: // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2fbrkznbl.html

Go:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gt2veftcgax.html

Ruby: arr.permutation.to_a
来源：http://dali.mhx1999.top/Article/details/gt2ssvdkuzv.html

C#:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gt2dirwnfhf.html

[N09] 栈与队列
来源：http://dali.hfpthk.cn/Article/details/gt2ndvxbrvh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.iojbl.cn/Article/details/gt2woglrmwl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cheryme.top/Article/details/gt2htqwblid.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uehkxmov.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ehwqpu.com/Article/details/gt2klhavbbo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yongpay.top/Article/details/gt2rrpqtkok.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yuanzhike.top/Article/details/gt2cpnxzhtt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gt2ejayrjoe.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gt2vkgujayc.html

[N10] 链表节点定义
来源：http://dali.zhiwuduotai.top/Article/details/gt2pjiaveef.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daria6918.cn/Article/details/gt2blunatgl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.snrcjt.cn/Article/details/gt2jxbwbpts.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daxiang520.top/Article/details/gt2bwycdfnv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangdashe.top/Article/details/gt2pperuejw.html

Java: class Node { int v; Node next; }
来源：http://dali.sweek.top/Article/details/gt2yjilmutm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zdqjudy.top/Article/details/gt2lupgayht.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tanke756.top/Article/details/gt2jvpqeict.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ctthbaik.html

[N11] 二叉树中序遍历
来源：http://dali.yuanzhike.top/Article/details/gt2crdghmfg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mhcuvcym.html

PHP:  // 手写递归函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2nvwkwcaw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gt2vwouavrg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gt2lcindois.html

Java: // 手写递归
来源：http://dali.tanke756.top/Article/details/gt2vpiomtmv.html

Go:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gt2wbkiukcy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.havefunace.top/Article/details/gt2ajyrdqjq.html

C#:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gt2meyvnyhw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenzaomai.com/Article/details/gt2ukebatsu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cheryme.top/Article/details/gt2tpmmdrth.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.snrcjt.cn/Article/details/gt2fakbkpuf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gt2mgirmfis.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigufen.top/Article/details/gt2qlpyovdd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gt2ixnwkqic.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gaohongyu789.top/Article/details/gt2vmmxnukb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pycfn.com/Article/details/gt2dcnagugt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gt2vboprrcu.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2qiokxpyi.html

O. 并发与异步
来源：http://dali.zhixingplan.top/Article/details/gt2ifxkywgl.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2swpwuhsy.html

[O01] 启动一个线程
来源：http://dali.jianghu66.top/Article/details/gt2fnieaqjy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pycfn.com/Article/details/gt2ubnoafgc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xylfe.cn/Article/details/gt2eanvpull.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.redwolf501.top/Article/details/gt2dqgdrbzb.html

TS:   // 同 JS
来源：http://dali.dianchejie.cn/Article/details/gt2slvgbrkq.html

Java: new Thread(() -> f()).start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ktzounwx.html

Go:   go f()
来源：http://dali.0kj1m.cn/Article/details/gt2txhxrklw.html

Ruby: Thread.new { f }
来源：http://dali.jqgufenzy.top/Article/details/gt2rbxqdbmy.html

C#:   Task.Run(() => F());
来源：http://dali.hnqzz.top/Article/details/gt2vsuzhfyo.html

[O02] 使用线程池
来源：http://dali.jqgufenzy.top/Article/details/gt2msplqkll.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tianlin.xyz/Article/details/gt2iuicgcer.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.pengpengdd.cyou/Article/details/gt2dxhsrxup.html

JS:   // worker_threads 线程池
来源：http://dali.jqgufenzy.top/Article/details/gt2meriwatc.html

TS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gt2luiqvxtl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tianlin.xyz/Article/details/gt2agurvaqx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ybcxt.top/Article/details/gt2zbesfwma.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gzxyxwwj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cheryme.top/Article/details/gt2sodlmifp.html

[O03] 加锁保护共享数据
来源：http://dali.cdnleiting.top/Article/details/gt2wectvhrx.html

Py:   with lock: shared += 1
来源：http://dali.xuanzx.com/Article/details/gt2hdvaaqmr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sufxvd.cn/Article/details/gt2qoiuxccw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnqzz.top/Article/details/gt2yraalrvx.html

TS:   // 同 JS
来源：http://dali.iojbl.cn/Article/details/gt2bfhiwudx.html

Java: synchronized (this) { shared++; }
来源：http://dali.meibo888.top/Article/details/gt2haxurfdf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sxryk.cn/Article/details/gt2ytcechii.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nwbrower.top/Article/details/gt2bmuwsucj.html

C#:   lock (gate) { shared++; }
来源：http://dali.redwolf501.top/Article/details/gt2iakvtucd.html

[O04] 定义异步函数并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nymfqtzl.html

Py:   async def f():⏎    await g()
来源：http://dali.ppjwa.cn/Article/details/gt2difkahra.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.iojbl.cn/Article/details/gt2nvwfyrcf.html

JS:   async function f() { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2wxubjzbx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gt2ebrxqjqq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj202588.top/Article/details/gt2xcexcdxl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kdxqugzg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sxryk.cn/Article/details/gt2jyqhgfxi.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258888.top/Article/details/gt2qavaccqs.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuetiantiany.cn/Article/details/gt2eniqvfhr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cheryme.top/Article/details/gt2eswbaxsl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hnxiangtu.top/Article/details/gt2ftcdspie.html

JS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gt2vzsyvyxf.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gt2pvswipog.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.iojbl.cn/Article/details/gt2wcwcuinj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tianlin.xyz/Article/details/gt2ptxfcysk.html

Ruby: threads.map(&:join)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwmcgcbg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.aibaodan.cn/Article/details/gt2zyowbptp.html

[O06] 使用进程池
来源：http://dali.zycfv.cn/Article/details/gt2xcdnvxnn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2utcfpoyc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nwbrower.top/Article/details/gt2dptwhgcm.html

JS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gt2rblazfpr.html

TS:   // child_process / cluster 模块
来源：http://dali.hnqzz.top/Article/details/gt2ywhlwpad.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhongyouzk.top/Article/details/gt2pwwkgxgr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hywenlv.cn/Article/details/gt2plqtfdrr.html

Ruby: // fork 块
来源：http://dali.gaohongyu789.top/Article/details/gt2cdklgvns.html

C#:   Parallel.For
来源：http://dali.xinyue.icu/Article/details/gt2vgbokvod.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2coxdiioo.html

P. 常用工具函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2wovadrnb.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2llypxpby.html

[P01] 生成 UUID
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mfsnelof.html

Py:   str(uuid.uuid4())
来源：http://dali.shzxlz.cn/Article/details/gt2gdgzbjke.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigufen.top/Article/details/gt2zvrrmylg.html

JS:   crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gt2lzvnzlff.html

TS:   crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gt2rsvwkhbq.html

Java: UUID.randomUUID().toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qsstwkwv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.9152youxi.cn/Article/details/gt2wfgrpsjg.html

Ruby: SecureRandom.uuid
来源：http://dali.xziqi.cn/Article/details/gt2pomulrvk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.haohaochexian.top/Article/details/gt2toycblgb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.c1oappe.top/Article/details/gt2wfbfotbe.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ybcxt.top/Article/details/gt2fdxqguyc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2nhoyvojf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jyoumei.cn/Article/details/gt2loppjset.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jiagoushi.top/Article/details/gt2uwdktkcb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gotoacloud.top/Article/details/gt2zfowappu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xinyue.icu/Article/details/gt2fagzjbnd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zmvlvaxc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258888.top/Article/details/gt2dmajghsv.html

[P03] 生成短随机字符串
来源：http://dali.cashguo.top/Article/details/gt2soywxwtz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.bjfxy.top/Article/details/gt2jzphtaqp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cdnleiting.top/Article/details/gt2biyxehtw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gt2jxtnxssw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gt2iuasjvrt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.fengsongda.top/Article/details/gt2krvbjglq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.haohaochexian.top/Article/details/gt2yyfrawdz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.c1oappe.top/Article/details/gt2cqbjfiiz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jianghu66.top/Article/details/gt2iniqemrj.html

[P04] 求长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iilzbdtm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.meibo888.top/Article/details/gt2vxhnzsza.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2hydjjaai.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gt2zbkvnuyn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gt2lakelusp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrpyxav.html

Go:   len(arr);  len(m)
来源：http://dali.sweek.top/Article/details/gt2wkhwtdhm.html

Ruby: x.length;  x.size
来源：http://dali.yvedp.cn/Article/details/gt2qaexyupa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cqqwz.cn/Article/details/gt2hwhivphx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj20258888.top/Article/details/gt2jkvxtdxl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.feifeiyinyue.top/Article/details/gt2xnszvbxa.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qqcoxrth.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.andypj.xyz/Article/details/gt2svqhcsyw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yueranfly.top/Article/details/gt2ssxerwkh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sxryk.cn/Article/details/gt2cprhzwjx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xylfe.cn/Article/details/gt2jaozlmhi.html

Ruby: a == b
来源：http://dali.smart0.xyz/Article/details/gt2ugflvgeo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.svipenyu.cn/Article/details/gt2hxhjadoh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.svipenyu.cn/Article/details/gt2wlpzylgi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yangfankeji.com/Article/details/gt2weynwmjt.html

PHP:  if (empty($x)) {}
来源：http://dali.zycfv.cn/Article/details/gt2yijsxdil.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yongpay.top/Article/details/gt2ezxarrla.html

TS:   if (x == null) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2xtckgark.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gt2jacofrbr.html

Go:   if x == nil {}
来源：http://dali.shzxlz.cn/Article/details/gt2grzdrveh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gaohongyu789.top/Article/details/gt2hdbpilew.html

C#:   if (x is null) {}
来源：http://dali.ppjwa.cn/Article/details/gt2sjxlbsyu.html

[P07] 防抖与节流
来源：http://dali.sxryk.cn/Article/details/gt2pbrnoiwt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.fengsongda.top/Article/details/gt2yuphphxu.html

PHP:  // 手写时间戳比较
来源：http://dali.shangyingyoupin.top/Article/details/gt2tcznqyuw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tianlin.xyz/Article/details/gt2wfeefhev.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aymmzbee.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2klosjdbg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tian-w.cn/Article/details/gt2dtesbkee.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxuanxn.top/Article/details/gt2iqnbnjbr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.redwolf501.top/Article/details/gt2vpbpurmt.html

[P08] 处理浮点精度问题
来源：http://dali.gotoacloud.top/Article/details/gt2lbxjgpaf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhongyouzk.top/Article/details/gt2jqxssrmo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.havefunace.top/Article/details/gt2qyfjkvzz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hongshengwenyu.top/Article/details/gt2qhjqseol.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yongpay.top/Article/details/gt2ahormxrn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.svipenyu.cn/Article/details/gt2ncpuuqsn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jyoumei.cn/Article/details/gt2vsfepddo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuetiantiany.cn/Article/details/gt2efvzknby.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxinkj.top/Article/details/gt2jqjobydj.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2wjwicdyx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cheryme.top/Article/details/gt2ryvbaljy.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2chisuryr.html

[Q01] 创建表
来源：http://dali.chenlongwang.top/Article/details/gt2wxyehphm.html

CREATE TABLE users (
来源：http://dali.feifeiyinyue.top/Article/details/gt2owvmowvb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ajjodlgg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jyoumei.cn/Article/details/gt2zvvixlaa.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nwbrower.top/Article/details/gt2arejmohy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigufen.top/Article/details/gt2kwsgvkip.html

);
来源：http://dali.daria6918.cn/Article/details/gt2bnksvtmm.html

[Q02] 创建带外键的表
来源：http://dali.andypj.xyz/Article/details/gt2rvrwfmrz.html

CREATE TABLE orders (
来源：http://dali.bjfxy.top/Article/details/gt2xydyrkza.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gt2zspdhbux.html

user_id INT NOT NULL,
来源：http://dali.shangyingyoupin.top/Article/details/gt2kydcipzd.html

amount DECIMAL(10, 2),
来源：http://dali.jqgfzy.top/Article/details/gt2fypebtkh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.0kj1m.cn/Article/details/gt2llucywqf.html

);
来源：http://dali.smart0.xyz/Article/details/gt2mxtbflmc.html

[Q03] 增加列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vthrchwx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kulurgmp.html

[Q04] 修改列类型
来源：http://dali.nwbrower.top/Article/details/gt2ojpkabjm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daxiang520.top/Article/details/gt2rnpawgmk.html

[Q05] 重命名列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mnevhkpl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yonumen.top/Article/details/gt2ashdknmz.html

[Q06] 删除列
来源：http://dali.9152youxi.cn/Article/details/gt2fprfsuyc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gdwbmovz.html

[Q07] 删除表
来源：http://dali.quarkkingdee.top/Article/details/gt2utxiionw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ydzc1.top/Article/details/gt2uxlsfuzm.html

[Q08] 创建普通索引
来源：http://dali.havefunace.top/Article/details/gt2acjhpxtd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhcmnbr.html

[Q09] 创建唯一索引
来源：http://dali.kuanghao11.cn/Article/details/gt2kfyvdmhh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gt2bgdwsvzs.html

[Q10] 插入单行
来源：http://dali.ydzc1.top/Article/details/gt2cvraasyu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cashguo.top/Article/details/gt2hrhpxslz.html

[Q11] 一次插入多行
来源：http://dali.zhengqikj.top/Article/details/gt2fgdkduqv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xylfe.cn/Article/details/gt2uomxxuyu.html

[Q12] 插入后取自增 ID
来源：http://dali.havefunace.top/Article/details/gt2fguorlsk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nwbrower.top/Article/details/gt2qzwclpet.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenlongwang.top/Article/details/gt2rgvljnbg.html

[Q13] 忽略重复插入
来源：http://dali.xylfe.cn/Article/details/gt2yfpibads.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.316326.xyz/Article/details/gt2fchngvvz.html

[Q14] 存在则更新（upsert）
来源：http://dali.shuidangran.top/Article/details/gt2pujgyqsb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cucudq.cn/Article/details/gt2cvsrvlzt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.mhx1999.top/Article/details/gt2jvimytom.html

[Q15] 查询全部
来源：http://dali.zhengqikj.top/Article/details/gt2sxgbuskp.html

SELECT * FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2xhfulmqe.html

[Q16] 查询指定列
来源：http://dali.pycfn.com/Article/details/gt2ckrqdzbl.html

SELECT id, name FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2qxicrypo.html

[Q17] 条件查询
来源：http://dali.hnxiangtu.top/Article/details/gt2vkappphu.html


<!-- 参考信息 -->