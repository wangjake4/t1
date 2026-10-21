代发 wailian999

Ruby: exit 1
来源：http://dali.guowangkeji.top/Article/details/gtliktsfbo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxktjgrrr.html

[M06] 向标准错误输出
来源：http://dali.fengsongda.top/Article/details/gtyqjtjqcw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cucudq.cn/Article/details/gtkrpefdkw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangdashe.top/Article/details/gtnuifneov.html

JS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gtptxlwnwh.html

TS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gtwhcyxuvc.html

Java: System.err.println("err")
来源：http://dali.zhengqikj.top/Article/details/gtxtezsxtx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.meibo888.top/Article/details/gtxxqlpgnt.html

Ruby: warn "err"
来源：http://dali.gotoacloud.top/Article/details/gtsrlohdaf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yueranfly.top/Article/details/gtbwmvsbpc.html

[M07] 判断是否为主入口
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvcofdxc.html

Py:   if __name__ == "__main__":
来源：http://dali.yangfankeji.com/Article/details/gtdswdubza.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtkutikxic.html

JS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gtjjzcwiuq.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gtgdnzymsq.html

Java: public static void main(String[] args)
来源：http://dali.meibo888.top/Article/details/gtdkjflehp.html

Go:   func main()
来源：http://dali.shuidangran.top/Article/details/gtcxivkcjt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenjidiqi.icu/Article/details/gtqntzyvqs.html

C#:   static void Main(string[] args)
来源：http://dali.dashuyun.cn/Article/details/gtsymzmjqz.html

[M08] 获取系统与运行时信息
来源：http://dali.tianlin.xyz/Article/details/gtvnjzhguq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.316326.xyz/Article/details/gtuvwxvfah.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tian-w.cn/Article/details/gtwdpufnov.html

JS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gtfbkodndk.html

TS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhsxkkop.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dianchejie.cn/Article/details/gtngasmlfi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cheryme.top/Article/details/gtscogvojv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.feifeiyinyue.top/Article/details/gtmpkvpfbs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ivvv.top/Article/details/gtsuideouw.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtsqrskjjd.html

N. 数据结构与算法
来源：http://dali.kuanghao11.cn/Article/details/gtpgxktuzx.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtxsxruxax.html

[N01] 二分查找（有序数组）
来源：http://dali.sweek.top/Article/details/gtmgsoqdtd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtxdfzyb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtlntlnpnl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fengsongda.top/Article/details/gttjogqsms.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gtbbuvykpb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtstosplub.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtekqzubzs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guannengcc.top/Article/details/gtjmiaowod.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtpkbdrkve.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.c1oappe.top/Article/details/gtwfttclzn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigufen.top/Article/details/gtqnjlwbfr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.vqdsnc.cn/Article/details/gtxpvinnjy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gthagydime.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gttigmupmk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cucudq.cn/Article/details/gtqveselux.html

Go:   slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gtzefshkgh.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gtklmidtdv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.pycfn.com/Article/details/gtytobbubp.html

[N03] 快速排序（分治示例）
来源：http://dali.xuanzx.com/Article/details/gtucofsxjt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zdqjudy.top/Article/details/gttzhenwsx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sufxvd.cn/Article/details/gtnyehfews.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gtwmsdwxcn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gtcfpzcaio.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.birdmap.top/Article/details/gtekrokjlo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yanxiufei.cn/Article/details/gtkwkrqsol.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cheryme.top/Article/details/gtsoftszyk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zdqjudy.top/Article/details/gtqreuvjvj.html

[N04] 斐波那契数列
来源：http://dali.jiagoushi.top/Article/details/gtntzeolvb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ehwqpu.com/Article/details/gtveyuptlp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gtbaptauut.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtiseyfcqq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gtrrcldmxw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cashguo.top/Article/details/gthywlrnhw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yangfankeji.com/Article/details/gtojblncjj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigufen.top/Article/details/gtxuqavrzs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gtccaojniq.html

[N05] 最大公约数
来源：http://dali.guowangkeji.top/Article/details/gtgwyscecj.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtjdikuksv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxinkj.top/Article/details/gtdbtknevx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.quarkkingdee.top/Article/details/gtuqrjrdym.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gtkrligykm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sweek.top/Article/details/gtupbgcadq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.mhx1999.top/Article/details/gtqaocwkex.html

Ruby: a.gcd(b)
来源：http://dali.jinqigfzy.top/Article/details/gtcompazrn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.316326.xyz/Article/details/gtnocgmngw.html

[N06] 判断回文字符串
来源：http://dali.quarkkingdee.top/Article/details/gtgmprvicp.html

Py:   s == s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gtkovpeiad.html

PHP:  $s === strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gtsuadijbm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtuieiuukm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtpuyhstwq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ydzc1.top/Article/details/gtlvnmvjzj.html

Go:   // 双指针从两端比较
来源：http://dali.vqdsnc.cn/Article/details/gttvfuxxea.html

Ruby: s == s.reverse
来源：http://dali.havefunace.top/Article/details/gtlwjvkxfp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gtekkhjyuz.html

[N07] 两数之和（返回下标）
来源：http://dali.yangfankeji.com/Article/details/gtwntyjbfq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jyoumei.cn/Article/details/gtxwkaqxnm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxinkj.top/Article/details/gtbboztqph.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daxiang520.top/Article/details/gtrsaqafzl.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhixingplan.top/Article/details/gtbjmrvnlu.html

Java: // 手写 HashMap
来源：http://dali.jiagoushi.top/Article/details/gtrdlxhgdf.html

Go:   // 手写 map[int]int
来源：http://dali.guowangkeji.top/Article/details/gthqtwiadp.html

Ruby: // 手写 Hash
来源：http://dali.hongshengwenyu.top/Article/details/gtvtddzcow.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaylgdest.html

[N08] 生成全排列
来源：http://dali.wangshuangyany.cn/Article/details/gtvrrsvwoi.html

Py:   itertools.permutations(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtzqxzasia.html

PHP:  // 手写递归交换
来源：http://dali.jlsjyb.cn/Article/details/gthaupodmj.html

JS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtwhvrqzmt.html

TS:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtxufnbnrt.html

Java: // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtwssicpyw.html

Go:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtypneaqze.html

Ruby: arr.permutation.to_a
来源：http://dali.c1oappe.top/Article/details/gtqqjjorcl.html

C#:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtflnwroia.html

[N09] 栈与队列
来源：http://dali.xylfe.cn/Article/details/gttuivaywj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sufxvd.cn/Article/details/gtuyovkldk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.havefunace.top/Article/details/gthghmrbug.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gteohdizkx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ivvv.top/Article/details/gtqdocnoqx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdmrzrwg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhongyouzk.top/Article/details/gtarlhvplo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gtpdbigcyp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxinkj.top/Article/details/gthctllxgd.html

[N10] 链表节点定义
来源：http://dali.gzhubu.top/Article/details/gtsmeqoisg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhengqikj.top/Article/details/gtzhezyvcn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.0kj1m.cn/Article/details/gtkdmkarox.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.havefunace.top/Article/details/gtydwjorie.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhengqikj.top/Article/details/gtidiydamm.html

Java: class Node { int v; Node next; }
来源：http://dali.zhoulong.xyz/Article/details/gttgyrogjm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.9152youxi.cn/Article/details/gtjlgtsmvq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yanxiufei.cn/Article/details/gtrsghnptj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tian-w.cn/Article/details/gteodfxzek.html

[N11] 二叉树中序遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtxncnygzc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jqgufenzy.top/Article/details/gtprodsuzd.html

PHP:  // 手写递归函数
来源：http://dali.jinqigufen.top/Article/details/gtgilnrvie.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gtnitlmltn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gtlmzjthqa.html

Java: // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtnbfxonad.html

Go:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gtvzdjjgre.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.haohaochexian.top/Article/details/gttkjkhqyu.html

C#:   // 手写递归
来源：http://dali.birdmap.top/Article/details/gtvyuvjvdj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuetiantiany.cn/Article/details/gtslmiabhm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj20258.top/Article/details/gtysacdnmx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.9152youxi.cn/Article/details/gtsqpzbugy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gteggrzrjh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gtojgejynq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gtvkwypsdh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtexvxleoi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sysykeji.top/Article/details/gttjevzmgi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gtlsxtvivt.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtoxbedxzq.html

O. 并发与异步
来源：http://dali.gogol.net.cn/Article/details/gttizakvfs.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtmydrsexv.html

[O01] 启动一个线程
来源：http://dali.xuetiantiany.cn/Article/details/gtvjdyfbtt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cashguo.top/Article/details/gthmwhimcg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tanke756.top/Article/details/gtcnnyuzzz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhixingplan.top/Article/details/gtfkkdisbm.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgfejoqyc.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqcslojpn.html

Go:   go f()
来源：http://dali.cashguo.top/Article/details/gtbcximrzk.html

Ruby: Thread.new { f }
来源：http://dali.cucudq.cn/Article/details/gtuttwtyqt.html

C#:   Task.Run(() => F());
来源：http://dali.chenjidiqi.icu/Article/details/gtrxwrrkpd.html

[O02] 使用线程池
来源：http://dali.guannengcc.top/Article/details/gtqhaztgfr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sufxvd.cn/Article/details/gtldoatdlb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsyvpioqw.html

JS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gtrxeifuty.html

TS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gtkhrcuvrd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.smart0.xyz/Article/details/gttkaqybuz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sxryk.cn/Article/details/gtkperawea.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.snrcjt.cn/Article/details/gtzwynugpo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwzibxhj.html

[O03] 加锁保护共享数据
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjhzbuzm.html

Py:   with lock: shared += 1
来源：http://dali.nanxinkj.top/Article/details/gtmnqbwrig.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zycfv.cn/Article/details/gtrbauidys.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yongpay.top/Article/details/gtzrpdczvi.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gtzamhwpdh.html

Java: synchronized (this) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gtjqnboheh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cdnleiting.top/Article/details/gtuukllxnl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gaohongyu789.top/Article/details/gtkbaafsah.html

C#:   lock (gate) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gtgtnvznpz.html

[O04] 定义异步函数并等待
来源：http://dali.yj202588.top/Article/details/gtsfpcrlah.html

Py:   async def f():⏎    await g()
来源：http://dali.guowangkeji.top/Article/details/gtciwsrptn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hywenlv.cn/Article/details/gtsxqjfpus.html

JS:   async function f() { await g(); }
来源：http://dali.xuanzx.com/Article/details/gtgazuxdpg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtjqtbztaj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hysaishi.cn/Article/details/gtvwaqwthg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jqgufenzy.top/Article/details/gtweoobreo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sufxvd.cn/Article/details/gtkvdftakk.html

C#:   async Task F() { await G(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtqkmbiwzx.html

[O05] 并发执行并等待全部完成
来源：http://dali.316326.xyz/Article/details/gtuoxicacp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yonumen.top/Article/details/gtrwpunoap.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zycfv.cn/Article/details/gtsizqcpfk.html

JS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gtabeshybg.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gtaqweugue.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ivvv.top/Article/details/gtlesgzgoc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gogol.net.cn/Article/details/gtbsvxncdq.html

Ruby: threads.map(&:join)
来源：http://dali.xziqi.cn/Article/details/gtyfsniesd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigfzy.top/Article/details/gtangqnzvc.html

[O06] 使用进程池
来源：http://dali.haohaochexian.top/Article/details/gtuajveuzc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.redwolf501.top/Article/details/gtjvxgmrxk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnqzz.top/Article/details/gtongdjucd.html

JS:   // child_process / cluster 模块
来源：http://dali.smart0.xyz/Article/details/gtvvqdqrhi.html

TS:   // child_process / cluster 模块
来源：http://dali.hfpthk.cn/Article/details/gtwyxahvbu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.pycfn.com/Article/details/gtefdfbasp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hammf.cn/Article/details/gtqskuduvi.html

Ruby: // fork 块
来源：http://dali.yvedp.cn/Article/details/gtbrvkerha.html

C#:   Parallel.For
来源：http://dali.jinqigufen.top/Article/details/gtshvrqmcv.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtrxwwuwoy.html

P. 常用工具函数
来源：http://dali.feifeiyinyue.top/Article/details/gtelzsysik.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtbgupsdms.html

[P01] 生成 UUID
来源：http://dali.jinghuilouyu.cn/Article/details/gtabfzqmob.html

Py:   str(uuid.uuid4())
来源：http://dali.iojbl.cn/Article/details/gtkotaaknc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yanxiufei.cn/Article/details/gtosxsksnc.html

JS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gtnjixgtew.html

TS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtbnogwgmi.html

Java: UUID.randomUUID().toString()
来源：http://dali.haohaochexian.top/Article/details/gtftffcqqc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fengsongda.top/Article/details/gtnhcerxij.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gtizarifib.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shuidangran.top/Article/details/gtyfflrfkx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jianghu66.top/Article/details/gtsyhogvmm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.svipenyu.cn/Article/details/gtnbffnlpr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.316326.xyz/Article/details/gtujapljrw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cdnleiting.top/Article/details/gthrjmwxyc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbopqwpfv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangdashe.top/Article/details/gtlsgmzvqx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yangfankeji.com/Article/details/gtoqsdzgwa.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtivvjfbjh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuanzx.com/Article/details/gtuomcfffz.html

[P03] 生成短随机字符串
来源：http://dali.tanke756.top/Article/details/gtebyevwuh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gotoacloud.top/Article/details/gtpuhxwzvo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nanxinkj.top/Article/details/gtazsvoram.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmxfrpws.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gtaiywjrof.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhixingplan.top/Article/details/gtbvjvavqe.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jlsjyb.cn/Article/details/gtqpqjdpsv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jyoumei.cn/Article/details/gtrcfnehhn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nanxuanxn.top/Article/details/gtzixrliku.html

[P04] 求长度
来源：http://dali.bjfxy.top/Article/details/gtsbnplepy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jianghu66.top/Article/details/gtomgyttuu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtlztcsf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fengsongda.top/Article/details/gtmqgegknb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gtfvymeblz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xziqi.cn/Article/details/gtcycvjdnh.html

Go:   len(arr);  len(m)
来源：http://dali.dashuyun.cn/Article/details/gtzvdusxfv.html

Ruby: x.length;  x.size
来源：http://dali.jqgfzy.top/Article/details/gtummxquvq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yvedp.cn/Article/details/gtafxrcpoi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ivvv.top/Article/details/gtycdfvnjl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yanxiufei.cn/Article/details/gtoxmbhxfq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrnmgrafb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuanzhike.top/Article/details/gtamqutenv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guowangkeji.top/Article/details/gtycyxwebj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvunpftmw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.svipenyu.cn/Article/details/gthnibvbbf.html

Ruby: a == b
来源：http://dali.kuanghao11.cn/Article/details/gtpilobxli.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hywenlv.cn/Article/details/gtqcgcabkm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.guowangkeji.top/Article/details/gtpxybywyd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinqigfzy.top/Article/details/gtrljotjid.html

PHP:  if (empty($x)) {}
来源：http://dali.c1oappe.top/Article/details/gtbfmwcovb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gaohongyu789.top/Article/details/gtslddetnd.html

TS:   if (x == null) {}
来源：http://dali.jlsjyb.cn/Article/details/gtyqtzqsul.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gtwwcxedjm.html

Go:   if x == nil {}
来源：http://dali.ppjwa.cn/Article/details/gtmqsuppws.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinghuilouyu.cn/Article/details/gtswlaaifv.html

C#:   if (x is null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtampotjti.html

[P07] 防抖与节流
来源：http://dali.cucudq.cn/Article/details/gtprfyrvfk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yueranfly.top/Article/details/gtoyqrquss.html

PHP:  // 手写时间戳比较
来源：http://dali.xuanzx.com/Article/details/gtkzzluwxx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gttqcznrbi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gtejiciwgc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tianlin.xyz/Article/details/gtnjijpwhn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ehwqpu.com/Article/details/gtapojqsmb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cdnleiting.top/Article/details/gtbahlvkig.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yongpay.top/Article/details/gttoijmfgh.html

[P08] 处理浮点精度问题
来源：http://dali.gaohongyu789.top/Article/details/gtmzukxbhj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.iojbl.cn/Article/details/gtkelbleho.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sufxvd.cn/Article/details/gttmnacgzk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hfpthk.cn/Article/details/gtdoduvmce.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gogol.net.cn/Article/details/gtazkkrfsw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cheryme.top/Article/details/gtayxkvxai.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yueranfly.top/Article/details/gtmpsylzyc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.smart0.xyz/Article/details/gtexaysqjt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hammf.cn/Article/details/gtfheytztn.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtremqmqef.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhiwuduotai.top/Article/details/gttufvxnss.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtztwtxryb.html

[Q01] 创建表
来源：http://dali.hysaishi.cn/Article/details/gtaxucvced.html

CREATE TABLE users (
来源：http://dali.shuidangran.top/Article/details/gtemhzcyct.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gtroesaapf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gtkzpyvvbx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xinyue.icu/Article/details/gtblxrnkjw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuetiantiany.cn/Article/details/gtmilhdeei.html

);
来源：http://dali.jlsjyb.cn/Article/details/gtpstcscqo.html

[Q02] 创建带外键的表
来源：http://dali.quarkkingdee.top/Article/details/gtfoyzirjc.html

CREATE TABLE orders (
来源：http://dali.sxryk.cn/Article/details/gtgouhzjgt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangdashe.top/Article/details/gtwpyukbbp.html

user_id INT NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gtyvlxwekv.html

amount DECIMAL(10, 2),
来源：http://dali.hysaishi.cn/Article/details/gtjvqevsnu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jianghu66.top/Article/details/gtpfucawcw.html

);
来源：http://dali.nanxinkj.top/Article/details/gtrqxwhmbu.html

[Q03] 增加列
来源：http://dali.pengpengdd.cyou/Article/details/gtrbpudwge.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hnqzz.top/Article/details/gtzuqpxnim.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjledura.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigfzy.top/Article/details/gtuommzpob.html

[Q05] 重命名列
来源：http://dali.yuxming.cn/Article/details/gtgmncukxp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvnocrln.html

[Q06] 删除列
来源：http://dali.gaohongyu789.top/Article/details/gtptxujlie.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jqgfzy.top/Article/details/gtwbdtjdho.html

[Q07] 删除表
来源：http://dali.wangdashe.top/Article/details/gtrfptucwd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ehwqpu.com/Article/details/gtqntpagwn.html

[Q08] 创建普通索引
来源：http://dali.yj202588.top/Article/details/gtibaifzjq.html


<!-- 参考信息 -->