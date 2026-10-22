代发 wailian999

Java: public static void main(String[] args)
来源：http://dali.cdnleiting.top/Article/details/gt2wsgkgsbx.html

Go:   func main()
来源：http://dali.yuxming.cn/Article/details/gt2tdxtdbhd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fzhhl.top/Article/details/gt2ownvttjo.html

C#:   static void Main(string[] args)
来源：http://dali.yanxiufei.cn/Article/details/gt2cpjsroxe.html

[M08] 获取系统与运行时信息
来源：http://dali.0kj1m.cn/Article/details/gt2wyaabnbc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenjidiqi.icu/Article/details/gt2gyssfnpn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangdashe.top/Article/details/gt2xuucbsup.html

JS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gt2ejksqwtr.html

TS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gt2qfqtdsba.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenzaomai.com/Article/details/gt2sziuhnlt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhixingplan.top/Article/details/gt2tzzxyffz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shzxlz.cn/Article/details/gt2nlkyyftd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sxryk.cn/Article/details/gt2nzntfwrf.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2ijolezju.html

N. 数据结构与算法
来源：http://dali.hywenlv.cn/Article/details/gt2sqbcclok.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2abqknnbk.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgufenzy.top/Article/details/gt2urvlbwrs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2qgudfbmt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cucudq.cn/Article/details/gt2ewluivih.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gt2kslrvpep.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuanzhike.top/Article/details/gt2xuzogkjm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2gdfcbwos.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2trrlggzn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhongyouzk.top/Article/details/gt2qwnuzvjv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2poyclxpk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.guannengcc.top/Article/details/gt2ywyoevnl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gt2llyzdmpl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gt2lirkxlcb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gt2bxfohpsy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hhjdkink.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2svdbsvhe.html

Go:   slices.Sort(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2shgxsojh.html

Ruby: arr.sort
来源：http://dali.shzxlz.cn/Article/details/gt2kpqssffx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hongshengwenyu.top/Article/details/gt2bhlacael.html

[N03] 快速排序（分治示例）
来源：http://dali.jiagoushi.top/Article/details/gt2hdccppug.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2whmamhdd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ybcxt.top/Article/details/gt2riykalkr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gt2gibpaiyp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gt2tuhdnxhc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.0kj1m.cn/Article/details/gt2qhouorho.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sysykeji.top/Article/details/gt2dzwpcdaj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.aibaodan.cn/Article/details/gt2kuynhvxt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guannengcc.top/Article/details/gt2zzywsmyo.html

[N04] 斐波那契数列
来源：http://dali.cdnleiting.top/Article/details/gt2ublwbhde.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gt2svxfepyg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gt2nnvdhrdz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gt2nahxaimo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hqgdapei.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gt2eangflbt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qivmzbbr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gt2utqyztgu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2kwzcbobb.html

[N05] 最大公约数
来源：http://dali.hammf.cn/Article/details/gt2nhsvwkcu.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdstdzka.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.0kj1m.cn/Article/details/gt2brpnxxha.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gt2dbnetmxs.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gt2amgdqnzt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuanzx.com/Article/details/gt2xnpqxexk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wkvnmblg.html

Ruby: a.gcd(b)
来源：http://dali.yanxiufei.cn/Article/details/gt2iksgllkq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cdnleiting.top/Article/details/gt2jeodelyi.html

[N06] 判断回文字符串
来源：http://dali.hysaishi.cn/Article/details/gt2qasnshkw.html

Py:   s == s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gt2hjecmrhl.html

PHP:  $s === strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2vckcjqpb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gt2tzulgnpz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gt2dcptdvzs.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shuidangran.top/Article/details/gt2qwrkrnpq.html

Go:   // 双指针从两端比较
来源：http://dali.hnxiangtu.top/Article/details/gt2vnyvusdx.html

Ruby: s == s.reverse
来源：http://dali.hysaishi.cn/Article/details/gt2xgjshrfa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gt2ercgjrgg.html

[N07] 两数之和（返回下标）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ehxksltp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sysykeji.top/Article/details/gt2bnlaktzj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgfzy.top/Article/details/gt2bplbddhr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnqzz.top/Article/details/gt2ntffumdg.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2cgupaozr.html

Java: // 手写 HashMap
来源：http://dali.cheryme.top/Article/details/gt2tsbrpfhg.html

Go:   // 手写 map[int]int
来源：http://dali.pycfn.com/Article/details/gt2vuyqrapm.html

Ruby: // 手写 Hash
来源：http://dali.jiagoushi.top/Article/details/gt2vhjooqsg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dianchejie.cn/Article/details/gt2ipneeawr.html

[N08] 生成全排列
来源：http://dali.yj202588.top/Article/details/gt2wkljmrwh.html

Py:   itertools.permutations(arr)
来源：http://dali.yj20258.top/Article/details/gt2lttqatzx.html

PHP:  // 手写递归交换
来源：http://dali.mhx1999.top/Article/details/gt2estpxlvq.html

JS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gt2nodvypjj.html

TS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2oxlnrzry.html

Java: // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2dpvrqpmt.html

Go:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2otkmutlh.html

Ruby: arr.permutation.to_a
来源：http://dali.tanke756.top/Article/details/gt2fwbrnfkk.html

C#:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gt2ueprqlqb.html

[N09] 栈与队列
来源：http://dali.kuanghao11.cn/Article/details/gt2bdmlslmt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuanzx.com/Article/details/gt2mkqrgbpf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.andypj.xyz/Article/details/gt2desbndpf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gt2nbiuicps.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qqhfbevq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gaohongyu789.top/Article/details/gt2hsgeqbai.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hysaishi.cn/Article/details/gt2kssujafi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gt2xujaofka.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.0kj1m.cn/Article/details/gt2dfaeshjx.html

[N10] 链表节点定义
来源：http://dali.shzxlz.cn/Article/details/gt2ldvrclcn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zycfv.cn/Article/details/gt2jlqimvod.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cheryme.top/Article/details/gt2nsjtchuw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ydzc1.top/Article/details/gt2qamlnadv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tanke756.top/Article/details/gt2ybvwuktw.html

Java: class Node { int v; Node next; }
来源：http://dali.ybcxt.top/Article/details/gt2xioanpwa.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.guowangkeji.top/Article/details/gt2tjwkohkf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuxming.cn/Article/details/gt2nfqsqsha.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ppvvmcgm.html

[N11] 二叉树中序遍历
来源：http://dali.redwolf501.top/Article/details/gt2enidfpbp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jqgufenzy.top/Article/details/gt2ajahwdvn.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gt2iconmaps.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnqzz.top/Article/details/gt2ymhzhmud.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gt2xochdrsi.html

Java: // 手写递归
来源：http://dali.yj20258.top/Article/details/gt2oxrfaeuh.html

Go:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gt2rogcpvff.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.feifeiyinyue.top/Article/details/gt2bawabhuo.html

C#:   // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gt2aksfvpag.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yuanzhike.top/Article/details/gt2nzmcepes.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xziqi.cn/Article/details/gt2xmlgjmkq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yangfankeji.com/Article/details/gt2zstrynzh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gt2arhrubjc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gt2xylenlqv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gt2ygscgpwx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dashuyun.cn/Article/details/gt2gssmseio.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zencpygz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gt2sryovasz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2czmbuqhc.html

O. 并发与异步
来源：http://dali.zhiwuduotai.top/Article/details/gt2cluggvpp.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2klnilnyp.html

[O01] 启动一个线程
来源：http://dali.chenzaomai.com/Article/details/gt2ccmffcgv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qcvggbfn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nwbrower.top/Article/details/gt2urwyztnu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hysaishi.cn/Article/details/gt2inzybwpy.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gt2uwumouyv.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vqosqlss.html

Go:   go f()
来源：http://dali.tanke756.top/Article/details/gt2udmxlzwd.html

Ruby: Thread.new { f }
来源：http://dali.guowangkeji.top/Article/details/gt2temuafet.html

C#:   Task.Run(() => F());
来源：http://dali.cdnleiting.top/Article/details/gt2qyjveyoy.html

[O02] 使用线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xpajfjcx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258888.top/Article/details/gt2mtgrcwat.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hnzfxvui.html

JS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gt2btljdrky.html

TS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gt2lvinoqhi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jzoxhysc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258888.top/Article/details/gt2akzkbidp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.birdmap.top/Article/details/gt2jdykkgfy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.pycfn.com/Article/details/gt2fcpfnivm.html

[O03] 加锁保护共享数据
来源：http://dali.guowangkeji.top/Article/details/gt2vwjnkimk.html

Py:   with lock: shared += 1
来源：http://dali.0kj1m.cn/Article/details/gt2kxzabpiz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ppjwa.cn/Article/details/gt2kfbazlvb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gzhubu.top/Article/details/gt2tewmejwa.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gt2gaxvbcpk.html

Java: synchronized (this) { shared++; }
来源：http://dali.meibo888.top/Article/details/gt2ehcbhcfx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hammf.cn/Article/details/gt2olsqnksb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhongyouzk.top/Article/details/gt2jnjoypdg.html

C#:   lock (gate) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gt2acuujcsm.html

[O04] 定义异步函数并等待
来源：http://dali.ybcxt.top/Article/details/gt2jrcphpzs.html

Py:   async def f():⏎    await g()
来源：http://dali.fzhhl.top/Article/details/gt2jqishhgn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.316326.xyz/Article/details/gt2klsyajav.html

JS:   async function f() { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gt2ktkxhzyx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yonumen.top/Article/details/gt2zjxdpauh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tanke756.top/Article/details/gt2ciamvmjj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jqgufenzy.top/Article/details/gt2nltokkbi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jianghu66.top/Article/details/gt2bweqkpeu.html

C#:   async Task F() { await G(); }
来源：http://dali.mhx1999.top/Article/details/gt2vawitnul.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj20258888.top/Article/details/gt2rrmagggz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yoqwxpph.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pycfn.com/Article/details/gt2pgyixbcb.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gt2lxenrsft.html

TS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gt2gzrfiuwi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pycfn.com/Article/details/gt2zwucqpyy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhiwuduotai.top/Article/details/gt2cbkvagaj.html

Ruby: threads.map(&:join)
来源：http://dali.daxiang520.top/Article/details/gt2kkpbdmgw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnqzz.top/Article/details/gt2utkkwqfc.html

[O06] 使用进程池
来源：http://dali.tian-w.cn/Article/details/gt2qtincpke.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dashuyun.cn/Article/details/gt2pfzeuowq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fengsongda.top/Article/details/gt2mhbabqhh.html

JS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gt2dgrnitml.html

TS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gt2tdgqnarb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.kuanghao11.cn/Article/details/gt2rrejyiti.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shangyingyoupin.top/Article/details/gt2crctulqe.html

Ruby: // fork 块
来源：http://dali.jqgfzy.top/Article/details/gt2moiabsym.html

C#:   Parallel.For
来源：http://dali.zdqjudy.top/Article/details/gt2evkkhxjm.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2ayccjhll.html

P. 常用工具函数
来源：http://dali.svipenyu.cn/Article/details/gt2gffzlmgc.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2ofvmgkow.html

[P01] 生成 UUID
来源：http://dali.bjfxy.top/Article/details/gt2gtcxbrwy.html

Py:   str(uuid.uuid4())
来源：http://dali.fengsongda.top/Article/details/gt2ambpgciw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gt2mjialeaa.html

JS:   crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gt2eypubqab.html

TS:   crypto.randomUUID()
来源：http://dali.hongshengwenyu.top/Article/details/gt2btdvngtz.html

Java: UUID.randomUUID().toString()
来源：http://dali.sufxvd.cn/Article/details/gt2fiitgsby.html

Go:   // 用 github.com/google/uuid
来源：http://dali.wangshuangyany.cn/Article/details/gt2zrydocgv.html

Ruby: SecureRandom.uuid
来源：http://dali.xinyue.icu/Article/details/gt2lbvhtstm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zpqliety.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cdnleiting.top/Article/details/gt2lumvwngl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yuanzhike.top/Article/details/gt2ryyvimbs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jiagoushi.top/Article/details/gt2nukqassm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.meibo888.top/Article/details/gt2fhoxccsf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ivvv.top/Article/details/gt2zzsptlkn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wjaxoevt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.mhx1999.top/Article/details/gt2vokwvpyi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fengsongda.top/Article/details/gt2djnlppoq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.mhx1999.top/Article/details/gt2xzzxysdp.html

[P03] 生成短随机字符串
来源：http://dali.svipenyu.cn/Article/details/gt2crrpiwxh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jianghu66.top/Article/details/gt2gbxxztqq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhongyouzk.top/Article/details/gt2qwgcclwh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gt2zygjaarw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gt2joiypzoy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ydzc1.top/Article/details/gt2zyjtemrb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jqgufenzy.top/Article/details/gt2zkskqkna.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jiagoushi.top/Article/details/gt2pdvikzic.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhongyouzk.top/Article/details/gt2aewyomvc.html

[P04] 求长度
来源：http://dali.fzhhl.top/Article/details/gt2ksxsdooj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.svipenyu.cn/Article/details/gt2zrhobisd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ogwkvbyv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shzxlz.cn/Article/details/gt2sysprvvc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gt2vtbuouvy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gt2mumdzhct.html

Go:   len(arr);  len(m)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jiskrfbx.html

Ruby: x.length;  x.size
来源：http://dali.chenjidiqi.icu/Article/details/gt2ovzsmmnk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.daria6918.cn/Article/details/gt2dyurmaik.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hysaishi.cn/Article/details/gt2kwryxcbr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fzhhl.top/Article/details/gt2jpwngviy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sxryk.cn/Article/details/gt2akjdboqu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.snrcjt.cn/Article/details/gt2hqnupfbq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jlsjyb.cn/Article/details/gt2puhlekwx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.vqdsnc.cn/Article/details/gt2aktigypj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258.top/Article/details/gt2lnprysha.html

Ruby: a == b
来源：http://dali.gaohongyu789.top/Article/details/gt2olkiwjej.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hongshengwenyu.top/Article/details/gt2hgpcfaqr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cjlkzcla.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.guowangkeji.top/Article/details/gt2aimaigbu.html

PHP:  if (empty($x)) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2yfouldse.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenlongwang.top/Article/details/gt2zbsdxtoh.html

TS:   if (x == null) {}
来源：http://dali.ivvv.top/Article/details/gt2xumzxuss.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.guannengcc.top/Article/details/gt2eibonxwh.html

Go:   if x == nil {}
来源：http://dali.dashuyun.cn/Article/details/gt2yuzigqtw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gogol.net.cn/Article/details/gt2kevsjmbc.html

C#:   if (x is null) {}
来源：http://dali.cheryme.top/Article/details/gt2dmgymkrw.html

[P07] 防抖与节流
来源：http://dali.wangdashe.top/Article/details/gt2jmyygxia.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.kuanghao11.cn/Article/details/gt2nenazqqk.html

PHP:  // 手写时间戳比较
来源：http://dali.zycfv.cn/Article/details/gt2ytwqmwrw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gt2ltqezebn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gt2thkvoohq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daxiang520.top/Article/details/gt2mewzahjq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenzaomai.com/Article/details/gt2tupgqxzz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yanxiufei.cn/Article/details/gt2wjmyoofv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gogol.net.cn/Article/details/gt2ulwrnhwq.html

[P08] 处理浮点精度问题
来源：http://dali.316326.xyz/Article/details/gt2tbaiplje.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qpldeswy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2gsdmqwlq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.c1oappe.top/Article/details/gt2ujauzdkv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.andypj.xyz/Article/details/gt2selnartu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.iojbl.cn/Article/details/gt2zfmuxftw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xuetiantiany.cn/Article/details/gt2agpnkkdg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj20258888.top/Article/details/gt2bkvmqort.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pycfn.com/Article/details/gt2felrflke.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2lwsetqeq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.kuanghao11.cn/Article/details/gt2pueoaedg.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2zeeirdnz.html

[Q01] 创建表
来源：http://dali.xuanzx.com/Article/details/gt2hvthjowb.html

CREATE TABLE users (
来源：http://dali.aibaodan.cn/Article/details/gt2bdatasxj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2riizmvmv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gt2pgrzlavi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gogol.net.cn/Article/details/gt2zadzafmm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenzaomai.com/Article/details/gt2eulbtksj.html

);
来源：http://dali.dianchejie.cn/Article/details/gt2stmlxgbl.html

[Q02] 创建带外键的表
来源：http://dali.aizwys.cn/Article/details/gt2xzaaskbt.html

CREATE TABLE orders (
来源：http://dali.316326.xyz/Article/details/gt2tlvvvcaj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gt2qvpnlbgl.html

user_id INT NOT NULL,
来源：http://dali.zdqjudy.top/Article/details/gt2undqoqom.html

amount DECIMAL(10, 2),
来源：http://dali.yj20258888.top/Article/details/gt2khhfixds.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hysaishi.cn/Article/details/gt2nsbfhdzn.html

);
来源：http://dali.guowangkeji.top/Article/details/gt2pgoshikb.html

[Q03] 增加列
来源：http://dali.sxryk.cn/Article/details/gt2bikbygdb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cqqwz.cn/Article/details/gt2thzizbkb.html

[Q04] 修改列类型
来源：http://dali.yj202588.top/Article/details/gt2chxdrbve.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cqqwz.cn/Article/details/gt2alyasvaw.html

[Q05] 重命名列
来源：http://dali.xuetiantiany.cn/Article/details/gt2wsoxwvjv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sweek.top/Article/details/gt2qckbaygg.html

[Q06] 删除列
来源：http://dali.zycfv.cn/Article/details/gt2gcbzywpw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nwbrower.top/Article/details/gt2ixjoaffb.html

[Q07] 删除表
来源：http://dali.0kj1m.cn/Article/details/gt2zqacnudr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2npfofkdm.html

[Q08] 创建普通索引
来源：http://dali.svipenyu.cn/Article/details/gt2uimgutwu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tanke756.top/Article/details/gt2nppdfxia.html

[Q09] 创建唯一索引
来源：http://dali.gogol.net.cn/Article/details/gt2wueafpwu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuanzx.com/Article/details/gt2magmznyo.html

[Q10] 插入单行
来源：http://dali.gzhubu.top/Article/details/gt2fcnxdkda.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnqzz.top/Article/details/gt2moiembpw.html

[Q11] 一次插入多行
来源：http://dali.tanke756.top/Article/details/gt2uukwbazh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xziqi.cn/Article/details/gt2zwyfphpu.html

[Q12] 插入后取自增 ID
来源：http://dali.cashguo.top/Article/details/gt2zbqchgkw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yangfankeji.com/Article/details/gt2vipupqir.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cqqwz.cn/Article/details/gt2swdskrtf.html

[Q13] 忽略重复插入
来源：http://dali.chenzaomai.com/Article/details/gt2rxwdggog.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigufen.top/Article/details/gt2nnvvswcz.html

[Q14] 存在则更新（upsert）
来源：http://dali.hywenlv.cn/Article/details/gt2reobyceb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xinyue.icu/Article/details/gt2tpskpzde.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cdnleiting.top/Article/details/gt2kbmeezaw.html

[Q15] 查询全部
来源：http://dali.xziqi.cn/Article/details/gt2ewpjnuot.html


<!-- 参考信息 -->