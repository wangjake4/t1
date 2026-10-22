代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhixingplan.top/Article/details/gtgbrikqjn.html

[M05] 设置退出码
来源：http://dali.jyoumei.cn/Article/details/gtkhonjodj.html

Py:   sys.exit(1)
来源：http://dali.316326.xyz/Article/details/gtobhnjygx.html

PHP:  exit(1);
来源：http://dali.9152youxi.cn/Article/details/gttewcnval.html

JS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gtqqtulvat.html

TS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtirdiejds.html

Java: System.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtquutjywm.html

Go:   os.Exit(1)
来源：http://dali.daxiang520.top/Article/details/gtltywrula.html

Ruby: exit 1
来源：http://dali.hysaishi.cn/Article/details/gtqxolmzks.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258888.top/Article/details/gtlbdbbagl.html

[M06] 向标准错误输出
来源：http://dali.cheryme.top/Article/details/gtuedryran.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yanxiufei.cn/Article/details/gtvnyheqyd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxuanxn.top/Article/details/gtnbfajukf.html

JS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gtewsjrjem.html

TS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gtglkctcpb.html

Java: System.err.println("err")
来源：http://dali.pycfn.com/Article/details/gtgdgaceul.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.0kj1m.cn/Article/details/gtumzxkruf.html

Ruby: warn "err"
来源：http://dali.pycfn.com/Article/details/gtmkbipmoi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tianlin.xyz/Article/details/gttlatmpol.html

[M07] 判断是否为主入口
来源：http://dali.chenlongwang.top/Article/details/gtiphpsumi.html

Py:   if __name__ == "__main__":
来源：http://dali.wangdashe.top/Article/details/gtatxffrcd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxuanxn.top/Article/details/gtpmxqejdh.html

JS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gtboqchdnz.html

TS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gtpvqzzkzs.html

Java: public static void main(String[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gtrjunuznz.html

Go:   func main()
来源：http://dali.hysaishi.cn/Article/details/gtdrrflmbf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tianlin.xyz/Article/details/gttoivzsrd.html

C#:   static void Main(string[] args)
来源：http://dali.fzhhl.top/Article/details/gtyxfukvbu.html

[M08] 获取系统与运行时信息
来源：http://dali.jinghuilouyu.cn/Article/details/gtcspnsqhm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhongyouzk.top/Article/details/gtcvwyhsip.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhoulong.xyz/Article/details/gtdfqiqasr.html

JS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtyrbysrbt.html

TS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyjgclgm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.bjfxy.top/Article/details/gtduoynorg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tanke756.top/Article/details/gtvspyfgrv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.kuanghao11.cn/Article/details/gtdbricuoo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.pengpengdd.cyou/Article/details/gthneomsex.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtbhakvghf.html

N. 数据结构与算法
来源：http://dali.xziqi.cn/Article/details/gtxsglkmdw.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtnfsptibm.html

[N01] 二分查找（有序数组）
来源：http://dali.meibo888.top/Article/details/gtwyrrqqio.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtumaimsvb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.redwolf501.top/Article/details/gtduriywti.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gtrrdtmiyt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sxryk.cn/Article/details/gtlhahmzyu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtlhkkhryr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtzormtrnu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jiagoushi.top/Article/details/gtflfnebkb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtvhxssxnm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuetiantiany.cn/Article/details/gtirgqjdpa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gtizyoienq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gzhubu.top/Article/details/gtrmhvihcf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gtuwgvyhlk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtuudjrpgv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hysaishi.cn/Article/details/gtyrziiiun.html

Go:   slices.Sort(arr)
来源：http://dali.pycfn.com/Article/details/gtsrqncksf.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gtycdoaunf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cdnleiting.top/Article/details/gtkqikgufj.html

[N03] 快速排序（分治示例）
来源：http://dali.hywenlv.cn/Article/details/gtuwiajtcu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cucudq.cn/Article/details/gtxodzgjbn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cqqwz.cn/Article/details/gtvrehhnvn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gtkbwiygsn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gaohongyu789.top/Article/details/gtbwjcjuyj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dashuyun.cn/Article/details/gtppphkwnz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.kuanghao11.cn/Article/details/gtkoefqtgu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258888.top/Article/details/gtfasryhgf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenlongwang.top/Article/details/gteaauqfnd.html

[N04] 斐波那契数列
来源：http://dali.ppjwa.cn/Article/details/gthquizbjh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gtjohbplmp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gtkclhxena.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxghakxth.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtxjjvryol.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.c1oappe.top/Article/details/gtskvmtidh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aizwys.cn/Article/details/gtgqlmsqtg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtuysskdrg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtdkmqzthl.html

[N05] 最大公约数
来源：http://dali.hnqzz.top/Article/details/gtwinjynos.html

Py:   math.gcd(a, b)
来源：http://dali.fengsongda.top/Article/details/gtmkgdjsgs.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.snrcjt.cn/Article/details/gtwrcohdqr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gtkbjdlxpw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gtgskeumps.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.havefunace.top/Article/details/gttajkwkxh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj202588.top/Article/details/gtgpxvdprk.html

Ruby: a.gcd(b)
来源：http://dali.guannengcc.top/Article/details/gtbexiefxe.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jlsjyb.cn/Article/details/gthsyousaa.html

[N06] 判断回文字符串
来源：http://dali.cashguo.top/Article/details/gtzlxmnjgx.html

Py:   s == s[::-1]
来源：http://dali.hammf.cn/Article/details/gtszcgbdeo.html

PHP:  $s === strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gtzpevvuek.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtgdkhefxg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtzxsvsoji.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.daxiang520.top/Article/details/gtfekybcng.html

Go:   // 双指针从两端比较
来源：http://dali.daxiang520.top/Article/details/gtdpjpiqry.html

Ruby: s == s.reverse
来源：http://dali.hammf.cn/Article/details/gtltzdkdqa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gthiowlfox.html

[N07] 两数之和（返回下标）
来源：http://dali.quarkkingdee.top/Article/details/gtkycuryia.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zdqjudy.top/Article/details/gtxnjdrboo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxuanxn.top/Article/details/gtzyppkjic.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yonumen.top/Article/details/gtuvmthwav.html

TS:   // 手写 Map<string, number>
来源：http://dali.shangyingyoupin.top/Article/details/gtciljqxic.html

Java: // 手写 HashMap
来源：http://dali.yuxming.cn/Article/details/gteryrnirk.html

Go:   // 手写 map[int]int
来源：http://dali.xinyue.icu/Article/details/gtxoxguefd.html

Ruby: // 手写 Hash
来源：http://dali.pycfn.com/Article/details/gtssjgmunv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daxiang520.top/Article/details/gtywsaerzu.html

[N08] 生成全排列
来源：http://dali.gzhubu.top/Article/details/gtgowonhnz.html

Py:   itertools.permutations(arr)
来源：http://dali.redwolf501.top/Article/details/gtefdkrnhc.html

PHP:  // 手写递归交换
来源：http://dali.sweek.top/Article/details/gtlcfhpdqg.html

JS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxhjvplq.html

TS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtgiqpqekz.html

Java: // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtfbwbqkdy.html

Go:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtvewuhmbp.html

Ruby: arr.permutation.to_a
来源：http://dali.xuetiantiany.cn/Article/details/gtwguwnqrj.html

C#:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtkftcsubm.html

[N09] 栈与队列
来源：http://dali.redwolf501.top/Article/details/gtuwhvplnl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.meibo888.top/Article/details/gttwnehdqz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj20258.top/Article/details/gtsiiyqyut.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jianghu66.top/Article/details/gtnlfzqmso.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yuxming.cn/Article/details/gtvsqgzwmv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xylfe.cn/Article/details/gttrxhnmaf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sweek.top/Article/details/gtfckumzyp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtlzmgvhyl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.0kj1m.cn/Article/details/gtvtkabtxl.html

[N10] 链表节点定义
来源：http://dali.jlsjyb.cn/Article/details/gtbqlsgjle.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigfzy.top/Article/details/gtrjodebvj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuxming.cn/Article/details/gtzvezrivw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fengsongda.top/Article/details/gtcgmgjvms.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.c1oappe.top/Article/details/gtxisyjfsl.html

Java: class Node { int v; Node next; }
来源：http://dali.sufxvd.cn/Article/details/gtasprnnvr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.quarkkingdee.top/Article/details/gtlrbujpek.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ivvv.top/Article/details/gtipmmpeym.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtroqcnfdx.html

[N11] 二叉树中序遍历
来源：http://dali.wangdashe.top/Article/details/gtrhljftpo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenzaomai.com/Article/details/gtinbbytjo.html

PHP:  // 手写递归函数
来源：http://dali.yuxming.cn/Article/details/gtjuinrfjc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gtieffwiug.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gtdsvnvvfk.html

Java: // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtaiirxvki.html

Go:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gtkoshefdj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gzhubu.top/Article/details/gtruhrxsnt.html

C#:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtbfwcqeav.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.redwolf501.top/Article/details/gtwfnjamjd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.9152youxi.cn/Article/details/gtluhntvuh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hammf.cn/Article/details/gtkxfvvhqw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gtiultbdfl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnxiangtu.top/Article/details/gtpdbwhkbt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gtykxfrzlj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pengpengdd.cyou/Article/details/gtsqdmftzz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xylfe.cn/Article/details/gtwldvykdp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gtgsnbospq.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtpcidzaic.html

O. 并发与异步
来源：http://dali.zhiwuduotai.top/Article/details/gtaffqzcnb.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtvnglnjbq.html

[O01] 启动一个线程
来源：http://dali.meibo888.top/Article/details/gtptxhhqih.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenzaomai.com/Article/details/gtbyosdpnz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tian-w.cn/Article/details/gtmkxruusp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tanke756.top/Article/details/gtnbbfbwwg.html

TS:   // 同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtjkigteqf.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuanzhike.top/Article/details/gtdbxnkhuz.html

Go:   go f()
来源：http://dali.guowangkeji.top/Article/details/gthxggtdvk.html

Ruby: Thread.new { f }
来源：http://dali.gaohongyu789.top/Article/details/gtxolvsrgd.html

C#:   Task.Run(() => F());
来源：http://dali.cucudq.cn/Article/details/gtxfivvobf.html

[O02] 使用线程池
来源：http://dali.vqdsnc.cn/Article/details/gtvtwnhaah.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sxryk.cn/Article/details/gtbmbzhfho.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.pengpengdd.cyou/Article/details/gtraptwkxm.html

JS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gtgdntjips.html

TS:   // worker_threads 线程池
来源：http://dali.redwolf501.top/Article/details/gtajtlbdtu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.smart0.xyz/Article/details/gtqugaqtey.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jiagoushi.top/Article/details/gtchnhlyhp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ppjwa.cn/Article/details/gtgcnidlvl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.9152youxi.cn/Article/details/gtpocbsuly.html

[O03] 加锁保护共享数据
来源：http://dali.ivvv.top/Article/details/gtbglyhfns.html

Py:   with lock: shared += 1
来源：http://dali.shuidangran.top/Article/details/gtchgaubew.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhengqikj.top/Article/details/gtilpjrzwg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.feifeiyinyue.top/Article/details/gtdsrjbqhs.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gtzheubjoa.html

Java: synchronized (this) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gtukthbaal.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.mhx1999.top/Article/details/gtzyzhilos.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hammf.cn/Article/details/gtkmzuidpu.html

C#:   lock (gate) { shared++; }
来源：http://dali.birdmap.top/Article/details/gtnxqairti.html

[O04] 定义异步函数并等待
来源：http://dali.gogol.net.cn/Article/details/gtfifyeame.html

Py:   async def f():⏎    await g()
来源：http://dali.zycfv.cn/Article/details/gtmxkusmgi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.guowangkeji.top/Article/details/gtojebikid.html

JS:   async function f() { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtugldslvp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkvbactk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyyecyhl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenjidiqi.icu/Article/details/gtjmwxxvoh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nwbrower.top/Article/details/gttwxfputc.html

C#:   async Task F() { await G(); }
来源：http://dali.sweek.top/Article/details/gtajaoimrq.html

[O05] 并发执行并等待全部完成
来源：http://dali.pengpengdd.cyou/Article/details/gtjexxmlos.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gogol.net.cn/Article/details/gtamvqfgun.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zycfv.cn/Article/details/gtuxxfqiqx.html

JS:   await Promise.all(tasks)
来源：http://dali.gogol.net.cn/Article/details/gtyuovtgwk.html

TS:   await Promise.all(tasks)
来源：http://dali.yueranfly.top/Article/details/gtiqclyzkw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ehwqpu.com/Article/details/gtbuaalmzk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj202588.top/Article/details/gttuygglfj.html

Ruby: threads.map(&:join)
来源：http://dali.zhengqikj.top/Article/details/gtznroglan.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shangyingyoupin.top/Article/details/gtchenkzqx.html

[O06] 使用进程池
来源：http://dali.wangshuangyany.cn/Article/details/gtxkhtjmsz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangdashe.top/Article/details/gthafzijsd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuanzhike.top/Article/details/gtgpexusfj.html

JS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gtjpfmyair.html

TS:   // child_process / cluster 模块
来源：http://dali.wangshuangyany.cn/Article/details/gtmlhiikpl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhengqikj.top/Article/details/gtdardcaue.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hammf.cn/Article/details/gtakqrzhbq.html

Ruby: // fork 块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikloyfrt.html

C#:   Parallel.For
来源：http://dali.yangfankeji.com/Article/details/gtiqoixccb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtyzrbckrm.html

P. 常用工具函数
来源：http://dali.chenjidiqi.icu/Article/details/gtctssqafw.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtxmbapgja.html

[P01] 生成 UUID
来源：http://dali.havefunace.top/Article/details/gtnpwambrf.html

Py:   str(uuid.uuid4())
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfoerkkq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sufxvd.cn/Article/details/gtuqrvtkca.html

JS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtsfhenyxy.html

TS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtgwdxmkjz.html

Java: UUID.randomUUID().toString()
来源：http://dali.c1oappe.top/Article/details/gtguqztzuv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jiagoushi.top/Article/details/gtjbvzevqi.html

Ruby: SecureRandom.uuid
来源：http://dali.0kj1m.cn/Article/details/gtignafvlt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jiagoushi.top/Article/details/gtioxtxpuh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hywenlv.cn/Article/details/gteznnsfub.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.pengpengdd.cyou/Article/details/gtsnclfwfk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnxiangtu.top/Article/details/gthmnequwc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.birdmap.top/Article/details/gtktdedral.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigufen.top/Article/details/gtarddhlxm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zdqjudy.top/Article/details/gtdraprigt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhoulong.xyz/Article/details/gtqoiodfbv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.snrcjt.cn/Article/details/gtrgkwvhxr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangdashe.top/Article/details/gtmoedfwvi.html

[P03] 生成短随机字符串
来源：http://dali.9152youxi.cn/Article/details/gthdjqbkdh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.feifeiyinyue.top/Article/details/gtjswddiyp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxqxlxyr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jiagoushi.top/Article/details/gtuodldllf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gtcyeknrcm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuxming.cn/Article/details/gtmvztxugf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.vqdsnc.cn/Article/details/gtmlxlyqlx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xinyue.icu/Article/details/gtauspaxxz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwrebpxc.html

[P04] 求长度
来源：http://dali.yuanzhike.top/Article/details/gtiefliugv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgufenzy.top/Article/details/gtoycphzds.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtrcvpbwty.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gtihwjjnaa.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnxiangtu.top/Article/details/gtdwfisxwl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gotoacloud.top/Article/details/gtgfapbuiv.html

Go:   len(arr);  len(m)
来源：http://dali.xylfe.cn/Article/details/gtczbbkuxv.html

Ruby: x.length;  x.size
来源：http://dali.tian-w.cn/Article/details/gtmheoldog.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gtvfctuskx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daria6918.cn/Article/details/gtzmhtgjou.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shangyingyoupin.top/Article/details/gtsfwosvbx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.feifeiyinyue.top/Article/details/gtcledipht.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tian-w.cn/Article/details/gtforkfmtu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.smart0.xyz/Article/details/gteajssqhq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shangyingyoupin.top/Article/details/gtvvgvwulb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtuntugqoq.html

Ruby: a == b
来源：http://dali.zhiwuduotai.top/Article/details/gtrvkbgkgl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yangfankeji.com/Article/details/gtrbicmbfe.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shanyushiyangtech.top/Article/details/gtzptyktzh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhixingplan.top/Article/details/gtfcndtgyn.html

PHP:  if (empty($x)) {}
来源：http://dali.cashguo.top/Article/details/gteaevjyur.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hysaishi.cn/Article/details/gtdmmgofdw.html

TS:   if (x == null) {}
来源：http://dali.ydzc1.top/Article/details/gtzztpvjdw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gtdriieloh.html

Go:   if x == nil {}
来源：http://dali.yonumen.top/Article/details/gtpjchnnda.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sweek.top/Article/details/gtfkyrydwe.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gttpofikod.html

[P07] 防抖与节流
来源：http://dali.316326.xyz/Article/details/gtpzthqmjt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.pengpengdd.cyou/Article/details/gtxlidsgme.html

PHP:  // 手写时间戳比较
来源：http://dali.hysaishi.cn/Article/details/gtmlqqnnhe.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gtrhrumuvw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtjdwixynh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zycfv.cn/Article/details/gtskordyre.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.redwolf501.top/Article/details/gtinjgfvzc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hysaishi.cn/Article/details/gtimfgwzgg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.wangdashe.top/Article/details/gttcsblkvi.html

[P08] 处理浮点精度问题
来源：http://dali.yj20258.top/Article/details/gtusnafrqu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrfuyumk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yuxming.cn/Article/details/gtkcsjjzxi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjfervaa.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ivvv.top/Article/details/gtxrtnmizy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258888.top/Article/details/gtngbeidio.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqweoshsd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj202588.top/Article/details/gtzwcbunyw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gotoacloud.top/Article/details/gtknmfmmuh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtgnfsbxty.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.iojbl.cn/Article/details/gtpgtlgysh.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtsyffwjoa.html

[Q01] 创建表
来源：http://dali.dashuyun.cn/Article/details/gtqhxiyctr.html

CREATE TABLE users (
来源：http://dali.gaohongyu789.top/Article/details/gtnoyzlrlv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.feifeiyinyue.top/Article/details/gtvxglmgdi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gtnjcekqgm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenjidiqi.icu/Article/details/gttrwpvdnk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tian-w.cn/Article/details/gtozbclbuf.html

);
来源：http://dali.redwolf501.top/Article/details/gtdxjttxie.html

[Q02] 创建带外键的表
来源：http://dali.yj202588.top/Article/details/gtktdsczqu.html

CREATE TABLE orders (
来源：http://dali.sxryk.cn/Article/details/gtsouklhsu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pengpengdd.cyou/Article/details/gtucjcfzjt.html

user_id INT NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gtvudjalao.html

amount DECIMAL(10, 2),
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufmnyahk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zycfv.cn/Article/details/gtckcbuwbb.html

);
来源：http://dali.aizwys.cn/Article/details/gtjlcfgeyd.html

[Q03] 增加列
来源：http://dali.0kj1m.cn/Article/details/gtqigptkbb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.guowangkeji.top/Article/details/gthrtodvxu.html

[Q04] 修改列类型
来源：http://dali.chenlongwang.top/Article/details/gtquzgpylz.html


<!-- 参考信息 -->