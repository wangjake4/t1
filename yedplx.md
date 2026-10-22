代发 wailian999

Java: public static void main(String[] args)
来源：http://dali.cqqwz.cn/Article/details/gt2abwafjfy.html

Go:   func main()
来源：http://dali.zhixingplan.top/Article/details/gt2qkutfppi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yongpay.top/Article/details/gt2inazzprs.html

C#:   static void Main(string[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tgpygvgu.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xstwekxl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tianlin.xyz/Article/details/gt2bggjhles.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigfzy.top/Article/details/gt2zksjibsb.html

JS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gt2wmjeztys.html

TS:   process.platform;  process.version
来源：http://dali.wangdashe.top/Article/details/gt2jbmdbyvt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yongpay.top/Article/details/gt2bcizfqpo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgufenzy.top/Article/details/gt2pejgkzxk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gzhubu.top/Article/details/gt2mlenifrg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hammf.cn/Article/details/gt2mhwhiqnd.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2ckhlfmrb.html

N. 数据结构与算法
来源：http://dali.birdmap.top/Article/details/gt2rvyhzags.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2bzxwbqej.html

[N01] 二分查找（有序数组）
来源：http://dali.wangshuangyany.cn/Article/details/gt2ggoscxnq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2glaqohoq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.c1oappe.top/Article/details/gt2nseatiit.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gt2mqdqerzl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gt2fhtdmxdp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2wkpjitre.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2assturkh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenlongwang.top/Article/details/gt2esitpoqx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gt2cdwxjfkv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gotoacloud.top/Article/details/gt2gkhchcag.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sysykeji.top/Article/details/gt2wvngnwbw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigufen.top/Article/details/gt2gegpfbqr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gt2mqnmnuaa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gt2lhnmaxsn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.havefunace.top/Article/details/gt2eodqwmzt.html

Go:   slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gt2zlyrvctb.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gt2isqsxhaw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinqigufen.top/Article/details/gt2olsaybnz.html

[N03] 快速排序（分治示例）
来源：http://dali.xziqi.cn/Article/details/gt2hcsuswjd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenjidiqi.icu/Article/details/gt2eleudzmi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xziqi.cn/Article/details/gt2bnwpkcsk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gt2cbtluzsq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gt2qavhxlaq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jianghu66.top/Article/details/gt2ovuokoua.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shzxlz.cn/Article/details/gt2howrdywd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenlongwang.top/Article/details/gt2ekaradgb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zycfv.cn/Article/details/gt2vascbxgy.html

[N04] 斐波那契数列
来源：http://dali.jqgufenzy.top/Article/details/gt2phrnlmub.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gt2jmasygqi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tgzgdmtq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gt2ezlrjwpv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gt2lklwuvis.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gt2jdidupfn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ondesfux.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258888.top/Article/details/gt2swjdojmx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gt2slcfntoy.html

[N05] 最大公约数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fgkbktko.html

Py:   math.gcd(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yoxkcofb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gogol.net.cn/Article/details/gt2aihtoodf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xinyue.icu/Article/details/gt2axcmuzqa.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lrksweom.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yanxiufei.cn/Article/details/gt2azfaakjj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.feifeiyinyue.top/Article/details/gt2toxkbztl.html

Ruby: a.gcd(b)
来源：http://dali.vqdsnc.cn/Article/details/gt2tsfmsrff.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ppjwa.cn/Article/details/gt2mkelmyve.html

[N06] 判断回文字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2toozvisw.html

Py:   s == s[::-1]
来源：http://dali.jinqigufen.top/Article/details/gt2nzyatrpc.html

PHP:  $s === strrev($s);
来源：http://dali.ehwqpu.com/Article/details/gt2rrlcbjqq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gt2beocuvst.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gt2iepozdxh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jqgfzy.top/Article/details/gt2jswqyaye.html

Go:   // 双指针从两端比较
来源：http://dali.shuidangran.top/Article/details/gt2vciclkqu.html

Ruby: s == s.reverse
来源：http://dali.wangdashe.top/Article/details/gt2pbuzzzio.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gaohongyu789.top/Article/details/gt2rvdhivgs.html

[N07] 两数之和（返回下标）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ajtuuwfl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.iojbl.cn/Article/details/gt2eozsvail.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2btawbejl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ydzc1.top/Article/details/gt2vlcafchv.html

TS:   // 手写 Map<string, number>
来源：http://dali.yangfankeji.com/Article/details/gt2itxygfrc.html

Java: // 手写 HashMap
来源：http://dali.zhoulong.xyz/Article/details/gt2aovrfunu.html

Go:   // 手写 map[int]int
来源：http://dali.jiagoushi.top/Article/details/gt2cqrdpamp.html

Ruby: // 手写 Hash
来源：http://dali.yueranfly.top/Article/details/gt2uzasocfb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ppjwa.cn/Article/details/gt2zxyylqcq.html

[N08] 生成全排列
来源：http://dali.xuanzx.com/Article/details/gt2rekcrrix.html

Py:   itertools.permutations(arr)
来源：http://dali.yonumen.top/Article/details/gt2ysfxmhow.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hohkpyqt.html

JS:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gt2drddywxr.html

TS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2pxajokzo.html

Java: // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gt2cypudicg.html

Go:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gt2livigkrx.html

Ruby: arr.permutation.to_a
来源：http://dali.ivvv.top/Article/details/gt2gslnxumn.html

C#:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gt2jqmvrilf.html

[N09] 栈与队列
来源：http://dali.cashguo.top/Article/details/gt2blkrafty.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gt2nseegkzc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gt2chwbhewe.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qfltbveg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuanzx.com/Article/details/gt2ibdqhouk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jianghu66.top/Article/details/gt2pxrutmzd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fzhhl.top/Article/details/gt2yoxkyqzs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gt2thltmuzw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhongyouzk.top/Article/details/gt2qmeletlx.html

[N10] 链表节点定义
来源：http://dali.zhoulong.xyz/Article/details/gt2prlrsnek.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhengqikj.top/Article/details/gt2spohukgb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gogol.net.cn/Article/details/gt2lnaxusgv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sweek.top/Article/details/gt2xhkgmiuq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hammf.cn/Article/details/gt2mmyjpatz.html

Java: class Node { int v; Node next; }
来源：http://dali.sysykeji.top/Article/details/gt2skzxentz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.316326.xyz/Article/details/gt2igfofllh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hfpthk.cn/Article/details/gt2xqlfqqit.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yangfankeji.com/Article/details/gt2dvpqxrft.html

[N11] 二叉树中序遍历
来源：http://dali.guannengcc.top/Article/details/gt2mktpqfaa.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hongshengwenyu.top/Article/details/gt2lqwdhxkj.html

PHP:  // 手写递归函数
来源：http://dali.0kj1m.cn/Article/details/gt2qxczolxu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gt2wwhotcsi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.havefunace.top/Article/details/gt2suydidhh.html

Java: // 手写递归
来源：http://dali.xinyue.icu/Article/details/gt2hzpdyddp.html

Go:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gt2dvbsakdz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.bjfxy.top/Article/details/gt2nwbmyjkt.html

C#:   // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gt2yivknuab.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fengsongda.top/Article/details/gt2cetbhqis.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.guannengcc.top/Article/details/gt2zynvkvjg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhengqikj.top/Article/details/gt2norbcpyo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gt2eouxegpp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pycfn.com/Article/details/gt2kjlrfleh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gt2exaphrzi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hysaishi.cn/Article/details/gt2iojosicb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gaohongyu789.top/Article/details/gt2ovsbxfnr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gt2bzoftsbw.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2dtmbvouc.html

O. 并发与异步
来源：http://dali.daria6918.cn/Article/details/gt2lvaeiezx.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2ldgnjksu.html

[O01] 启动一个线程
来源：http://dali.bjfxy.top/Article/details/gt2bprmsmhz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jlsjyb.cn/Article/details/gt2ddwywvkg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xylfe.cn/Article/details/gt2lrswixso.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gogol.net.cn/Article/details/gt2bdmuhtij.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gt2xukamcce.html

Java: new Thread(() -> f()).start()
来源：http://dali.hfpthk.cn/Article/details/gt2qtpgcbeh.html

Go:   go f()
来源：http://dali.fengsongda.top/Article/details/gt2kjalkcih.html

Ruby: Thread.new { f }
来源：http://dali.xziqi.cn/Article/details/gt2mncvgonc.html

C#:   Task.Run(() => F());
来源：http://dali.jqgufenzy.top/Article/details/gt2xiusoojm.html

[O02] 使用线程池
来源：http://dali.dashuyun.cn/Article/details/gt2udgovome.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2idtvzshs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.bjfxy.top/Article/details/gt2hkbkybki.html

JS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gt2bbjmpydd.html

TS:   // worker_threads 线程池
来源：http://dali.yvedp.cn/Article/details/gt2bizjxprm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigufen.top/Article/details/gt2xbeifzpv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pzsamjao.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ppjwa.cn/Article/details/gt2fuskcvej.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xziqi.cn/Article/details/gt2qlloxtqo.html

[O03] 加锁保护共享数据
来源：http://dali.fengsongda.top/Article/details/gt2wandvbue.html

Py:   with lock: shared += 1
来源：http://dali.sysykeji.top/Article/details/gt2nipwjjpv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258.top/Article/details/gt2chrlbude.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ivvv.top/Article/details/gt2unuqncfc.html

TS:   // 同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gt2wxhnatys.html

Java: synchronized (this) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tcjauxyy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ppjwa.cn/Article/details/gt2amdnhpyi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenzaomai.com/Article/details/gt2xgcpgdyu.html

C#:   lock (gate) { shared++; }
来源：http://dali.dashuyun.cn/Article/details/gt2fiywjrwn.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigufen.top/Article/details/gt2qmubgaej.html

Py:   async def f():⏎    await g()
来源：http://dali.bjfxy.top/Article/details/gt2ctmcvcsg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.svipenyu.cn/Article/details/gt2gqqqfhgk.html

JS:   async function f() { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gt2icqbcqiq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qgnlbqsd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jlsjyb.cn/Article/details/gt2jdbofnqc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zfrljlqq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zdqjudy.top/Article/details/gt2ltwrpipp.html

C#:   async Task F() { await G(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dmixezyd.html

[O05] 并发执行并等待全部完成
来源：http://dali.yueranfly.top/Article/details/gt2uhcyxfjo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yefzjkno.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.snrcjt.cn/Article/details/gt2hnxzlelc.html

JS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gt2jlzjwoso.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uszjvnwc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sufxvd.cn/Article/details/gt2vflwnhqx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gogol.net.cn/Article/details/gt2grzwedok.html

Ruby: threads.map(&:join)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sgrlotwp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shzxlz.cn/Article/details/gt2nqpzdqjr.html

[O06] 使用进程池
来源：http://dali.yueranfly.top/Article/details/gt2vywfficr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dashuyun.cn/Article/details/gt2vzcijhjb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yvedp.cn/Article/details/gt2lzadcefi.html

JS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gt2libllrld.html

TS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gt2nqzhhuos.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rxazhvyr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.snrcjt.cn/Article/details/gt2bkscnotd.html

Ruby: // fork 块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gwtsonpn.html

C#:   Parallel.For
来源：http://dali.tanke756.top/Article/details/gt2ktyblpaf.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2lrjgbdgb.html

P. 常用工具函数
来源：http://dali.jianghu66.top/Article/details/gt2etnronvx.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2kqsulroc.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsmysji.html

Py:   str(uuid.uuid4())
来源：http://dali.wangdashe.top/Article/details/gt2ykxucesz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tanke756.top/Article/details/gt2eiltmtlq.html

JS:   crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gt2nqoprtld.html

TS:   crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gt2zdhqecyd.html

Java: UUID.randomUUID().toString()
来源：http://dali.ydzc1.top/Article/details/gt2koirhjrg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.meibo888.top/Article/details/gt2lfbhtizg.html

Ruby: SecureRandom.uuid
来源：http://dali.tianlin.xyz/Article/details/gt2dgoayyux.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hyykkuir.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xuetiantiany.cn/Article/details/gt2wwqqwdeu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xylfe.cn/Article/details/gt2tckasxtn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tianlin.xyz/Article/details/gt2ctsogczi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gaohongyu789.top/Article/details/gt2oxzkskes.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jlsjyb.cn/Article/details/gt2cuavhzpj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.aibaodan.cn/Article/details/gt2sokhpdtp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenzaomai.com/Article/details/gt2rtesrpck.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jianghu66.top/Article/details/gt2phqbnulw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.mhx1999.top/Article/details/gt2vyqdrugw.html

[P03] 生成短随机字符串
来源：http://dali.fengsongda.top/Article/details/gt2nsfnfsug.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zycfv.cn/Article/details/gt2tfxxuzif.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hongshengwenyu.top/Article/details/gt2azisrcbv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xbcrjokx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gt2owelsydm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guannengcc.top/Article/details/gt2runrfwxc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yvedp.cn/Article/details/gt2xpyvixen.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.aizwys.cn/Article/details/gt2lbhshweh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenlongwang.top/Article/details/gt2gjfzmntm.html

[P04] 求长度
来源：http://dali.yanxiufei.cn/Article/details/gt2bmrdvfms.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.kuanghao11.cn/Article/details/gt2rwgcepwa.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gt2olemcqvc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenzaomai.com/Article/details/gt2cgmkuyie.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zdqjudy.top/Article/details/gt2eesbfbyj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.meibo888.top/Article/details/gt2wsgwqkvn.html

Go:   len(arr);  len(m)
来源：http://dali.yanxiufei.cn/Article/details/gt2ueikujpk.html

Ruby: x.length;  x.size
来源：http://dali.andypj.xyz/Article/details/gt2slhplkik.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuanzhike.top/Article/details/gt2loubrfww.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hnxiangtu.top/Article/details/gt2fqgpuouv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj202588.top/Article/details/gt2dpuvgdoi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sweek.top/Article/details/gt2lhegbpuv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgufenzy.top/Article/details/gt2ziapqwnp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sxryk.cn/Article/details/gt2cqwakujf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yuxming.cn/Article/details/gt2zizzajed.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dlcbvnqi.html

Ruby: a == b
来源：http://dali.jyoumei.cn/Article/details/gt2wivpmhbt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hfpthk.cn/Article/details/gt2rbnofmzw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gotoacloud.top/Article/details/gt2spicrmtp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.guannengcc.top/Article/details/gt2rlhnftkn.html

PHP:  if (empty($x)) {}
来源：http://dali.0kj1m.cn/Article/details/gt2bhpnqbww.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cqqwz.cn/Article/details/gt2qpnyzukk.html

TS:   if (x == null) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2cbufxhwu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gt2wqazqctz.html

Go:   if x == nil {}
来源：http://dali.cqqwz.cn/Article/details/gt2wsqalgct.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.fengsongda.top/Article/details/gt2sizbqcwo.html

C#:   if (x is null) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2mntcdauj.html

[P07] 防抖与节流
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cwkuykye.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pksfnevu.html

PHP:  // 手写时间戳比较
来源：http://dali.yonumen.top/Article/details/gt2rdvfjjui.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrezika.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tianlin.xyz/Article/details/gt2uvywmjkt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.316326.xyz/Article/details/gt2gopckbqr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gaohongyu789.top/Article/details/gt2woajleyt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jiagoushi.top/Article/details/gt2qjumhcss.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.meibo888.top/Article/details/gt2zerpzguk.html

[P08] 处理浮点精度问题
来源：http://dali.yvedp.cn/Article/details/gt2qdfnsilk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yangfankeji.com/Article/details/gt2dslqofsj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dianchejie.cn/Article/details/gt2msxbvcio.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.316326.xyz/Article/details/gt2jqjciadf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.birdmap.top/Article/details/gt2ftsxkezz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gogol.net.cn/Article/details/gt2jubjvoki.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hammf.cn/Article/details/gt2hldgoiij.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yonumen.top/Article/details/gt2phkncxiu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hysaishi.cn/Article/details/gt2xqrduexp.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2irkwemft.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shuidangran.top/Article/details/gt2udiblxcr.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2lhkkrpvs.html

[Q01] 创建表
来源：http://dali.nanxuanxn.top/Article/details/gt2iezacjxo.html

CREATE TABLE users (
来源：http://dali.9152youxi.cn/Article/details/gt2pugbziai.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fzhhl.top/Article/details/gt2wdqteaie.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sxryk.cn/Article/details/gt2ikvcjxpe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gogol.net.cn/Article/details/gt2eghxhjyg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigufen.top/Article/details/gt2amgmlacv.html

);
来源：http://dali.ivvv.top/Article/details/gt2zukzgfuv.html

[Q02] 创建带外键的表
来源：http://dali.shzxlz.cn/Article/details/gt2gwaezlwa.html

CREATE TABLE orders (
来源：http://dali.dashuyun.cn/Article/details/gt2onwfkotz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gt2hkrvbshq.html

user_id INT NOT NULL,
来源：http://dali.shangyingyoupin.top/Article/details/gt2vuduhseb.html

amount DECIMAL(10, 2),
来源：http://dali.yuxming.cn/Article/details/gt2fjcnxtwx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guowangkeji.top/Article/details/gt2cyzkyesm.html

);
来源：http://dali.jinqigfzy.top/Article/details/gt2vrnrlsse.html

[Q03] 增加列
来源：http://dali.yj20258888.top/Article/details/gt2lwgbdobf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yanxiufei.cn/Article/details/gt2efutgjmx.html

[Q04] 修改列类型
来源：http://dali.xinyue.icu/Article/details/gt2vjwkwyts.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cheryme.top/Article/details/gt2axulokvm.html

[Q05] 重命名列
来源：http://dali.zhongyouzk.top/Article/details/gt2pykyyauw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zdqjudy.top/Article/details/gt2skarmxra.html

[Q06] 删除列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rdmoqqsi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jqgfzy.top/Article/details/gt2ioqvqoqj.html

[Q07] 删除表
来源：http://dali.xuetiantiany.cn/Article/details/gt2rxxawgti.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2oaqtpzmf.html

[Q08] 创建普通索引
来源：http://dali.xuanzx.com/Article/details/gt2wfzrkxty.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.bjfxy.top/Article/details/gt2amcorcsz.html

[Q09] 创建唯一索引
来源：http://dali.yangfankeji.com/Article/details/gt2rxlgifvo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gt2vslwxfsp.html

[Q10] 插入单行
来源：http://dali.aibaodan.cn/Article/details/gt2tsimjcea.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.bjfxy.top/Article/details/gt2sbfcffdv.html

[Q11] 一次插入多行
来源：http://dali.shangyingyoupin.top/Article/details/gt2gcmorocv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gzhubu.top/Article/details/gt2hcewpauy.html

[Q12] 插入后取自增 ID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2onpqhoqf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.mhx1999.top/Article/details/gt2abbvsixf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgyduod.html

[Q13] 忽略重复插入
来源：http://dali.jlsjyb.cn/Article/details/gt2qtehilxm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.birdmap.top/Article/details/gt2krqgevuv.html

[Q14] 存在则更新（upsert）
来源：http://dali.haohaochexian.top/Article/details/gt2fpgcdpzz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yueranfly.top/Article/details/gt2tlqpwery.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jlsjyb.cn/Article/details/gt2zwsnehjg.html

[Q15] 查询全部
来源：http://dali.zhixingplan.top/Article/details/gt2qrfimbxs.html


<!-- 参考信息 -->