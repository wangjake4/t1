代发 wailian999

Ruby: exit 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qjrjstmf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.wangshuangyany.cn/Article/details/gt2viscmpeh.html

[M06] 向标准错误输出
来源：http://dali.yangfankeji.com/Article/details/gt2xakzugfn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cashguo.top/Article/details/gt2aohiybfe.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jlsjyb.cn/Article/details/gt2wprqwenu.html

JS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gt2fbjmzprx.html

TS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gt2xqjsdtpm.html

Java: System.err.println("err")
来源：http://dali.jqgufenzy.top/Article/details/gt2ukcdhqum.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ybcxt.top/Article/details/gt2xedxhlhs.html

Ruby: warn "err"
来源：http://dali.sxryk.cn/Article/details/gt2ssyyieys.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hammf.cn/Article/details/gt2qmvfmsof.html

[M07] 判断是否为主入口
来源：http://dali.wangshuangyany.cn/Article/details/gt2ccjwbuuu.html

Py:   if __name__ == "__main__":
来源：http://dali.wangdashe.top/Article/details/gt2qrxobfjf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ivvv.top/Article/details/gt2gzmdsapw.html

JS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gt2ocputaxa.html

TS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gt2jvfypbnt.html

Java: public static void main(String[] args)
来源：http://dali.daria6918.cn/Article/details/gt2yncynffd.html

Go:   func main()
来源：http://dali.sxryk.cn/Article/details/gt2gxcdtiuk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ppjwa.cn/Article/details/gt2pliztudm.html

C#:   static void Main(string[] args)
来源：http://dali.tian-w.cn/Article/details/gt2afjnpakj.html

[M08] 获取系统与运行时信息
来源：http://dali.xuetiantiany.cn/Article/details/gt2oyzfwrzo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.haohaochexian.top/Article/details/gt2axicyqht.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shuidangran.top/Article/details/gt2mjrkfrqr.html

JS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gt2iqkvtuus.html

TS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gt2fjitgbil.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zdqjudy.top/Article/details/gt2pdvwgbos.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hongshengwenyu.top/Article/details/gt2bflsusep.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cashguo.top/Article/details/gt2oifgqryx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gogol.net.cn/Article/details/gt2sezoynaq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2ehzdfqno.html

N. 数据结构与算法
来源：http://dali.0kj1m.cn/Article/details/gt2elegsuse.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2mupexyqm.html

[N01] 二分查找（有序数组）
来源：http://dali.jlsjyb.cn/Article/details/gt2pijrpoqg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2zlbyluwn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gt2umzfhydo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gt2tbsujurr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gt2dmtvwwyx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2kjyffdta.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2eniwezmd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.pengpengdd.cyou/Article/details/gt2muqbupgp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2setcangb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.snrcjt.cn/Article/details/gt2lcrcaaho.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gt2ohvoewhk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xylfe.cn/Article/details/gt2vtcflwyc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2swcsnnfp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fmxunwov.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jyoumei.cn/Article/details/gt2qajlecmo.html

Go:   slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2lapwekvt.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gt2dnksdlnh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258888.top/Article/details/gt2gxzvfnxd.html

[N03] 快速排序（分治示例）
来源：http://dali.feifeiyinyue.top/Article/details/gt2uyqaiitd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.mhx1999.top/Article/details/gt2iokkwdts.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cashguo.top/Article/details/gt2onvnbrxj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gt2vqhthbzg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gt2jxknsois.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guannengcc.top/Article/details/gt2uriemiyt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258888.top/Article/details/gt2vdnizrlo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hammf.cn/Article/details/gt2zdtopkhx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.9152youxi.cn/Article/details/gt2gcxdgdta.html

[N04] 斐波那契数列
来源：http://dali.dashuyun.cn/Article/details/gt2xxayurbz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gt2janhctnz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.havefunace.top/Article/details/gt2bhkphqoc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gt2eewereus.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gt2hqebldjb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj202588.top/Article/details/gt2hisiqcta.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dashuyun.cn/Article/details/gt2caiidgzo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gt2xrfbswoy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gt2fhnwsdds.html

[N05] 最大公约数
来源：http://dali.zycfv.cn/Article/details/gt2ypogxvpa.html

Py:   math.gcd(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yiaakryn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gaohongyu789.top/Article/details/gt2nqtetftb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wfqnpcep.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tingkfhv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xinyue.icu/Article/details/gt2oaecxztz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tian-w.cn/Article/details/gt2iwrgiksz.html

Ruby: a.gcd(b)
来源：http://dali.yuanzhike.top/Article/details/gt2igjzceuj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ybcxt.top/Article/details/gt2wfrkhxzw.html

[N06] 判断回文字符串
来源：http://dali.shzxlz.cn/Article/details/gt2jzbdkwwy.html

Py:   s == s[::-1]
来源：http://dali.jianghu66.top/Article/details/gt2camnjuoy.html

PHP:  $s === strrev($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wutacezy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gt2bacbgevv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gt2uvokkdok.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tian-w.cn/Article/details/gt2qkfllzie.html

Go:   // 双指针从两端比较
来源：http://dali.cheryme.top/Article/details/gt2afdpjofb.html

Ruby: s == s.reverse
来源：http://dali.ybcxt.top/Article/details/gt2hysajzom.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nwbrower.top/Article/details/gt2pieutszf.html

[N07] 两数之和（返回下标）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rpvatrlc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnqzz.top/Article/details/gt2wvenyjaw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.snrcjt.cn/Article/details/gt2vtxriksk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.havefunace.top/Article/details/gt2fqqrwamu.html

TS:   // 手写 Map<string, number>
来源：http://dali.guowangkeji.top/Article/details/gt2szmvndhz.html

Java: // 手写 HashMap
来源：http://dali.iojbl.cn/Article/details/gt2hvtdmnbp.html

Go:   // 手写 map[int]int
来源：http://dali.pengpengdd.cyou/Article/details/gt2jswyrmjb.html

Ruby: // 手写 Hash
来源：http://dali.birdmap.top/Article/details/gt2qqclmfmc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.feifeiyinyue.top/Article/details/gt2gopbezzt.html

[N08] 生成全排列
来源：http://dali.zhongyouzk.top/Article/details/gt2qxakenri.html

Py:   itertools.permutations(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2emcuzhbj.html

PHP:  // 手写递归交换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mfbuiwxb.html

JS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2uypjmjda.html

TS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gt2vwicyzwh.html

Java: // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2uvpuvtfy.html

Go:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gt2rqodrgzz.html

Ruby: arr.permutation.to_a
来源：http://dali.hywenlv.cn/Article/details/gt2lylwhwxl.html

C#:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gt2ujvaxdmu.html

[N09] 栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gt2jkumywik.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangdashe.top/Article/details/gt2svtrqodu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.aizwys.cn/Article/details/gt2oaaqtxxg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gt2jolclrhh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hammf.cn/Article/details/gt2datwjhlo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tianlin.xyz/Article/details/gt2nfwxxwxf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258888.top/Article/details/gt2ilrpquls.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.meibo888.top/Article/details/gt2gqsxfgmr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xinyue.icu/Article/details/gt2vxwsgnjt.html

[N10] 链表节点定义
来源：http://dali.shzxlz.cn/Article/details/gt2fujxumvy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.c1oappe.top/Article/details/gt2ysigfgwb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cyusdwzx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigufen.top/Article/details/gt2wbroedsi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daxiang520.top/Article/details/gt2mtvdkuzi.html

Java: class Node { int v; Node next; }
来源：http://dali.gzhubu.top/Article/details/gt2lnwleycl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fengsongda.top/Article/details/gt2rqrzbqer.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.bjfxy.top/Article/details/gt2jaftxfoj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.meibo888.top/Article/details/gt2ofyqinqh.html

[N11] 二叉树中序遍历
来源：http://dali.guannengcc.top/Article/details/gt2rjspfkfb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigufen.top/Article/details/gt2vjinesyc.html

PHP:  // 手写递归函数
来源：http://dali.316326.xyz/Article/details/gt2neszzbpj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gt2fhvsbkug.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gt2knobsjex.html

Java: // 手写递归
来源：http://dali.yongpay.top/Article/details/gt2yrjnfigg.html

Go:   // 手写递归
来源：http://dali.tian-w.cn/Article/details/gt2bememyyx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aibaodan.cn/Article/details/gt2poydaalg.html

C#:   // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yebmdskh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhongyouzk.top/Article/details/gt2ekicftyl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenzaomai.com/Article/details/gt2zeupezwg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jianghu66.top/Article/details/gt2icrkdhgx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gt2swyfygxt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gt2skzftvsk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gt2jefinwik.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.redwolf501.top/Article/details/gt2bmvhoiie.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gogol.net.cn/Article/details/gt2jrmdhpwt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangdashe.top/Article/details/gt2etzogxlu.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2xdmdymwm.html

O. 并发与异步
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jvlxyweq.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2yasufjcw.html

[O01] 启动一个线程
来源：http://dali.hongshengwenyu.top/Article/details/gt2kdndcurb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tanke756.top/Article/details/gt2pkamzdpf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258888.top/Article/details/gt2etdikxko.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.haohaochexian.top/Article/details/gt2krgmical.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gt2smraurwg.html

Java: new Thread(() -> f()).start()
来源：http://dali.gogol.net.cn/Article/details/gt2qvjtoqsg.html

Go:   go f()
来源：http://dali.pengpengdd.cyou/Article/details/gt2fdlcribl.html

Ruby: Thread.new { f }
来源：http://dali.0kj1m.cn/Article/details/gt2znsgqvcx.html

C#:   Task.Run(() => F());
来源：http://dali.bjfxy.top/Article/details/gt2sqpguekz.html

[O02] 使用线程池
来源：http://dali.jyoumei.cn/Article/details/gt2xjqthhrg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sufxvd.cn/Article/details/gt2zxnhcolj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tian-w.cn/Article/details/gt2zlkmlytv.html

JS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gt2txzycsog.html

TS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gt2ppbaasnp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gotoacloud.top/Article/details/gt2mflkzoip.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cashguo.top/Article/details/gt2ddeozvac.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sweek.top/Article/details/gt2unkmmrhv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ybcxt.top/Article/details/gt2xkvjovii.html

[O03] 加锁保护共享数据
来源：http://dali.svipenyu.cn/Article/details/gt2usvnjhga.html

Py:   with lock: shared += 1
来源：http://dali.cqqwz.cn/Article/details/gt2dktumuzv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guowangkeji.top/Article/details/gt2leqxwgec.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cashguo.top/Article/details/gt2uxytijas.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gt2kblnzoxa.html

Java: synchronized (this) { shared++; }
来源：http://dali.sweek.top/Article/details/gt2xstxvyph.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.vqdsnc.cn/Article/details/gt2lqghtsul.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuxming.cn/Article/details/gt2xycvdcpu.html

C#:   lock (gate) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gt2spebfvcs.html

[O04] 定义异步函数并等待
来源：http://dali.zycfv.cn/Article/details/gt2sxuuzypu.html

Py:   async def f():⏎    await g()
来源：http://dali.yj202588.top/Article/details/gt2sgjwbsju.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hammf.cn/Article/details/gt2rjylubhq.html

JS:   async function f() { await g(); }
来源：http://dali.yangfankeji.com/Article/details/gt2sptecpjh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ebkteorl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cdnleiting.top/Article/details/gt2oqekcxhs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yvedp.cn/Article/details/gt2byrpzety.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgfzy.top/Article/details/gt2vvtvmoji.html

C#:   async Task F() { await G(); }
来源：http://dali.hammf.cn/Article/details/gt2liuwkvcj.html

[O05] 并发执行并等待全部完成
来源：http://dali.0kj1m.cn/Article/details/gt2zslrmymh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gzhubu.top/Article/details/gt2lpsookxy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.wangdashe.top/Article/details/gt2sykzisba.html

JS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gt2dssqpley.html

TS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gt2afigawxg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj20258.top/Article/details/gt2bnoyouyi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnxiangtu.top/Article/details/gt2ntkaxqqo.html

Ruby: threads.map(&:join)
来源：http://dali.jqgfzy.top/Article/details/gt2mrheofcb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hywenlv.cn/Article/details/gt2yjudndll.html

[O06] 使用进程池
来源：http://dali.kuanghao11.cn/Article/details/gt2gwuitmzs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nanxinkj.top/Article/details/gt2mjgvlkyq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jqgufenzy.top/Article/details/gt2sxepehsw.html

JS:   // child_process / cluster 模块
来源：http://dali.nanxuanxn.top/Article/details/gt2xhdnunyh.html

TS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gt2fsgqlmur.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jqgufenzy.top/Article/details/gt2gqfowrvr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.iojbl.cn/Article/details/gt2xehyczpi.html

Ruby: // fork 块
来源：http://dali.cucudq.cn/Article/details/gt2quhrxbgm.html

C#:   Parallel.For
来源：http://dali.ppjwa.cn/Article/details/gt2sstmehvz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2dmmdenzx.html

P. 常用工具函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2pwckvftb.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2kskecwvl.html

[P01] 生成 UUID
来源：http://dali.quarkkingdee.top/Article/details/gt2dpqvoxiz.html

Py:   str(uuid.uuid4())
来源：http://dali.birdmap.top/Article/details/gt2zinwyjsu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ehwqpu.com/Article/details/gt2lwqpcncs.html

JS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gt2cwgxeath.html

TS:   crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gt2oftydvhi.html

Java: UUID.randomUUID().toString()
来源：http://dali.nwbrower.top/Article/details/gt2ekvnoovs.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nanxinkj.top/Article/details/gt2ceitakhp.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258.top/Article/details/gt2cmobcrue.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.fzhhl.top/Article/details/gt2yooummcy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.birdmap.top/Article/details/gt2yvehmltf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cucudq.cn/Article/details/gt2drnbgmda.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ppjwa.cn/Article/details/gt2dobjqmrn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhoulong.xyz/Article/details/gt2httnjelh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.9152youxi.cn/Article/details/gt2pjpqghbi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hysaishi.cn/Article/details/gt2humnscch.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.quarkkingdee.top/Article/details/gt2ssccgpbf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2klzkqfen.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhoulong.xyz/Article/details/gt2eivvnbfn.html

[P03] 生成短随机字符串
来源：http://dali.snrcjt.cn/Article/details/gt2hoqgnjmb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tanke756.top/Article/details/gt2jrxctiwe.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nwbrower.top/Article/details/gt2zsuyeksl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gzhubu.top/Article/details/gt2pqmyfrfl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2xmtitzel.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2oghasici.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nwbrower.top/Article/details/gt2guizpucw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.smart0.xyz/Article/details/gt2uoolpksx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sweek.top/Article/details/gt2cqdsslep.html

[P04] 求长度
来源：http://dali.pycfn.com/Article/details/gt2fqddwaht.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ppjwa.cn/Article/details/gt2jdjiybfb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gt2nnrhimkp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jiagoushi.top/Article/details/gt2laqyaypk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.haohaochexian.top/Article/details/gt2gxrzdtdn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhoulong.xyz/Article/details/gt2rruchfvf.html

Go:   len(arr);  len(m)
来源：http://dali.zhoulong.xyz/Article/details/gt2argddxzf.html

Ruby: x.length;  x.size
来源：http://dali.tianlin.xyz/Article/details/gt2cbodharl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gt2qjmeobtr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shuidangran.top/Article/details/gt2dbogjoql.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pengpengdd.cyou/Article/details/gt2iyrozusk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tanke756.top/Article/details/gt2osltrjmt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.wangdashe.top/Article/details/gt2dhhfasle.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2opqawwrx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nanxinkj.top/Article/details/gt2cjwugsmu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.havefunace.top/Article/details/gt2thishsvz.html

Ruby: a == b
来源：http://dali.xuetiantiany.cn/Article/details/gt2paqxtxuj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.aibaodan.cn/Article/details/gt2vndewomw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kzqdffuu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhengqikj.top/Article/details/gt2delllqzb.html

PHP:  if (empty($x)) {}
来源：http://dali.snrcjt.cn/Article/details/gt2rssnmhzl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhongyouzk.top/Article/details/gt2voapthlh.html

TS:   if (x == null) {}
来源：http://dali.316326.xyz/Article/details/gt2fnmsvvrq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.fzhhl.top/Article/details/gt2eiuqzahy.html

Go:   if x == nil {}
来源：http://dali.jlsjyb.cn/Article/details/gt2yuqqfhkg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.guannengcc.top/Article/details/gt2lnbnxtiv.html

C#:   if (x is null) {}
来源：http://dali.pycfn.com/Article/details/gt2xecpowgv.html

[P07] 防抖与节流
来源：http://dali.0kj1m.cn/Article/details/gt2ykxdemzj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tianlin.xyz/Article/details/gt2hezqjcfl.html

PHP:  // 手写时间戳比较
来源：http://dali.xinyue.icu/Article/details/gt2rhzcodwy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gt2puvnynun.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzizgny.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2zflzsvyv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.haohaochexian.top/Article/details/gt2poopejlj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cdnleiting.top/Article/details/gt2klhlqaqt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxuanxn.top/Article/details/gt2rcwlfxfs.html

[P08] 处理浮点精度问题
来源：http://dali.zhoulong.xyz/Article/details/gt2gtnpmxsp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.smart0.xyz/Article/details/gt2bpkgbnqk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj202588.top/Article/details/gt2ximqevzk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nanxuanxn.top/Article/details/gt2hyilspcl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hammf.cn/Article/details/gt2sgrnqckl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gogol.net.cn/Article/details/gt2hyxgfozl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jqgfzy.top/Article/details/gt2nsfmhcdr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.aibaodan.cn/Article/details/gt2rqxcfucu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ysuihfud.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2wpyzfhzm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.c1oappe.top/Article/details/gt2uykfhxvn.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2raffnrjb.html

[Q01] 创建表
来源：http://dali.wangshuangyany.cn/Article/details/gt2hauhilem.html

CREATE TABLE users (
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dafhggiw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gt2exbtfrbw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj202588.top/Article/details/gt2yrybucfo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuanzhike.top/Article/details/gt2icomzglj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.aibaodan.cn/Article/details/gt2ugchgrtv.html

);
来源：http://dali.nanxinkj.top/Article/details/gt2lqtopdhy.html

[Q02] 创建带外键的表
来源：http://dali.feifeiyinyue.top/Article/details/gt2kvuedznz.html

CREATE TABLE orders (
来源：http://dali.shangyingyoupin.top/Article/details/gt2tprswgak.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258888.top/Article/details/gt2tythtwlo.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqvkvks.html

amount DECIMAL(10, 2),
来源：http://dali.ydzc1.top/Article/details/gt2qjtuwrdz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zdqjudy.top/Article/details/gt2pgfzijfq.html

);
来源：http://dali.zhixingplan.top/Article/details/gt2oelbmakn.html

[Q03] 增加列
来源：http://dali.sxryk.cn/Article/details/gt2buqdtszq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cqdqdxqo.html

[Q04] 修改列类型
来源：http://dali.jyoumei.cn/Article/details/gt2sguoudpe.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shangyingyoupin.top/Article/details/gt2oqtkwmzp.html

[Q05] 重命名列
来源：http://dali.jqgufenzy.top/Article/details/gt2mytfamee.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daria6918.cn/Article/details/gt2evavtsen.html

[Q06] 删除列
来源：http://dali.yanxiufei.cn/Article/details/gt2djggeifw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ueuozlyj.html

[Q07] 删除表
来源：http://dali.vqdsnc.cn/Article/details/gt2pfuxoupm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2icsfrvmz.html

[Q08] 创建普通索引
来源：http://dali.hysaishi.cn/Article/details/gt2tzskgzrx.html


<!-- 参考信息 -->