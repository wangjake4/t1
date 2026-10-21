代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hongshengwenyu.top/Article/details/gtadeuwvzc.html

[M05] 设置退出码
来源：http://dali.snrcjt.cn/Article/details/gtbllzphxq.html

Py:   sys.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtnosgsnwr.html

PHP:  exit(1);
来源：http://dali.xuanzx.com/Article/details/gtoofkydze.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtwimvdqty.html

TS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtouhhhmxa.html

Java: System.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtdhqblopl.html

Go:   os.Exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtldofcyal.html

Ruby: exit 1
来源：http://dali.xuetiantiany.cn/Article/details/gtsijvzztn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dianchejie.cn/Article/details/gtxwygierk.html

[M06] 向标准错误输出
来源：http://dali.feifeiyinyue.top/Article/details/gtvnaeocbn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yanxiufei.cn/Article/details/gtkwveuirj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuxming.cn/Article/details/gtahrztdlk.html

JS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gtukoofqvq.html

TS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtacypgltt.html

Java: System.err.println("err")
来源：http://dali.iojbl.cn/Article/details/gtndlqfpzl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fzhhl.top/Article/details/gttihafhwb.html

Ruby: warn "err"
来源：http://dali.ydzc1.top/Article/details/gtithlyhma.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigfzy.top/Article/details/gtndjiurzj.html

[M07] 判断是否为主入口
来源：http://dali.hywenlv.cn/Article/details/gtugxftjjp.html

Py:   if __name__ == "__main__":
来源：http://dali.zhiwuduotai.top/Article/details/gtjrppgxcu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hywenlv.cn/Article/details/gtpsccnuus.html

JS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gtamusgttx.html

TS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gtzcchbybx.html

Java: public static void main(String[] args)
来源：http://dali.daria6918.cn/Article/details/gtidoeaomx.html

Go:   func main()
来源：http://dali.yvedp.cn/Article/details/gtkgdfsdce.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.smart0.xyz/Article/details/gthsyugsgi.html

C#:   static void Main(string[] args)
来源：http://dali.cqqwz.cn/Article/details/gtvbhygsmj.html

[M08] 获取系统与运行时信息
来源：http://dali.cucudq.cn/Article/details/gtxugnlebf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigufen.top/Article/details/gtrvunnysc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ybcxt.top/Article/details/gtgrgiyurp.html

JS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gtrcpskkun.html

TS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gtmgdpokog.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sweek.top/Article/details/gtbhbkqtsy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hongshengwenyu.top/Article/details/gtqdgcpqvg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pengpengdd.cyou/Article/details/gtntthnirc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.meibo888.top/Article/details/gtecvmdhow.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gthyiufbxe.html

N. 数据结构与算法
来源：http://dali.redwolf501.top/Article/details/gtgvvzeagz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtactqbcuz.html

[N01] 二分查找（有序数组）
来源：http://dali.zdqjudy.top/Article/details/gtzruaoigo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtpdzziwlz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gtzcaiukpw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gtclydtphr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.bjfxy.top/Article/details/gtghbedbzg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtzhcjmanj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtmtcjsdgy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dashuyun.cn/Article/details/gtflugajom.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtzfcasujh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.c1oappe.top/Article/details/gtbungxlas.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gotoacloud.top/Article/details/gtwlapupoy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hysaishi.cn/Article/details/gtkdzyopfz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gtqsbutwpj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gtamyyhelr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenzaomai.com/Article/details/gtnpzgdrfm.html

Go:   slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gtkrioatao.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gtlcjjzxnx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxinkj.top/Article/details/gtmscgnzpv.html

[N03] 快速排序（分治示例）
来源：http://dali.yj20258888.top/Article/details/gtvjymveal.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xinyue.icu/Article/details/gtvisubdoj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gotoacloud.top/Article/details/gtwiskrwjd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gtsjluzaah.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fengsongda.top/Article/details/gtzuaauapm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ivvv.top/Article/details/gtkfrcyxcb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gaohongyu789.top/Article/details/gtaiedxomc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jyoumei.cn/Article/details/gtonsftjsu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sweek.top/Article/details/gthoncvsrg.html

[N04] 斐波那契数列
来源：http://dali.ppjwa.cn/Article/details/gtoobptnjy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtltcldikw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnqzz.top/Article/details/gtiebkmbjm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gtqxxnuqps.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsvwtrfr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gttdvjlcsv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenzaomai.com/Article/details/gtrjdwqsjm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sufxvd.cn/Article/details/gtnjwsbtox.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtvahbqfjk.html

[N05] 最大公约数
来源：http://dali.svipenyu.cn/Article/details/gtddiomrqw.html

Py:   math.gcd(a, b)
来源：http://dali.fengsongda.top/Article/details/gthqulfepx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnqzz.top/Article/details/gtpbdgwdvn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gtivfeqojx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gtvjggwfrj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gogol.net.cn/Article/details/gtunuuaiwf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmunbnvnv.html

Ruby: a.gcd(b)
来源：http://dali.nanxuanxn.top/Article/details/gtozwbxlft.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ybcxt.top/Article/details/gtztiiqvin.html

[N06] 判断回文字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnhjyurv.html

Py:   s == s[::-1]
来源：http://dali.mhx1999.top/Article/details/gtpiiahsyf.html

PHP:  $s === strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gtceuegrkp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gterfujawm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gteadbubxj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yangfankeji.com/Article/details/gtqesimhzq.html

Go:   // 双指针从两端比较
来源：http://dali.nanxuanxn.top/Article/details/gtdkiehold.html

Ruby: s == s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfsrsdbf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gtveundoit.html

[N07] 两数之和（返回下标）
来源：http://dali.yonumen.top/Article/details/gtefabnorn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnxiangtu.top/Article/details/gtvrfkpphe.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cheryme.top/Article/details/gtfrzhuuyh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenjidiqi.icu/Article/details/gtsuffjkii.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhiwuduotai.top/Article/details/gtqnjypfxq.html

Java: // 手写 HashMap
来源：http://dali.sysykeji.top/Article/details/gtevxqrpwz.html

Go:   // 手写 map[int]int
来源：http://dali.cheryme.top/Article/details/gtnsttpomc.html

Ruby: // 手写 Hash
来源：http://dali.sweek.top/Article/details/gthjbcxiwd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.iojbl.cn/Article/details/gtflthrthw.html

[N08] 生成全排列
来源：http://dali.hongshengwenyu.top/Article/details/gtijvtwexl.html

Py:   itertools.permutations(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnevgnle.html

PHP:  // 手写递归交换
来源：http://dali.ydzc1.top/Article/details/gtwkyujxcf.html

JS:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtvqdoicga.html

TS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtucxsjrgq.html

Java: // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtnwlpdvfi.html

Go:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtdfyiqdaq.html

Ruby: arr.permutation.to_a
来源：http://dali.ehwqpu.com/Article/details/gtgjphxvow.html

C#:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdhzhiad.html

[N09] 栈与队列
来源：http://dali.jinqigufen.top/Article/details/gtocrulzrp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtsqilcdxr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtzmjenzky.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gtemighysb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangdashe.top/Article/details/gtqyktffti.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.redwolf501.top/Article/details/gtnnjnepdv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cdnleiting.top/Article/details/gtxjytgnac.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtofwgeyim.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258888.top/Article/details/gtjgpsektr.html

[N10] 链表节点定义
来源：http://dali.vqdsnc.cn/Article/details/gtuftbzduq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nwbrower.top/Article/details/gtqaqbrjwu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ehwqpu.com/Article/details/gtfgdiiymy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.kuanghao11.cn/Article/details/gthvdvaoqt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gzhubu.top/Article/details/gtxrhvuacx.html

Java: class Node { int v; Node next; }
来源：http://dali.mhx1999.top/Article/details/gtastkiwgf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cucudq.cn/Article/details/gtyzxzakdn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.feifeiyinyue.top/Article/details/gtgyvyfeti.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258888.top/Article/details/gtqbjvqjkt.html

[N11] 二叉树中序遍历
来源：http://dali.smart0.xyz/Article/details/gtxoxxmwww.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yangfankeji.com/Article/details/gtqekthbcf.html

PHP:  // 手写递归函数
来源：http://dali.daxiang520.top/Article/details/gtyhcmshbe.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gtqaiwqzrx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gtyghflpsv.html

Java: // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgyfdpoyg.html

Go:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtovgozvdg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenjidiqi.icu/Article/details/gtedevlqls.html

C#:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gttiyknkzr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.0kj1m.cn/Article/details/gtptuhlvex.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hongshengwenyu.top/Article/details/gtetmhzhah.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hammf.cn/Article/details/gtjzkvqthl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gaohongyu789.top/Article/details/gtfrcjfwpx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dianchejie.cn/Article/details/gtvmbjhied.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gtlopqsdlc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.iojbl.cn/Article/details/gtikphedyt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzefnzdn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tianlin.xyz/Article/details/gtitefnizc.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtydyjqgfz.html

O. 并发与异步
来源：http://dali.nanxinkj.top/Article/details/gtrjktfjjq.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtswijdhwu.html

[O01] 启动一个线程
来源：http://dali.zhixingplan.top/Article/details/gtkdvnedne.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yvedp.cn/Article/details/gtcwdvwudg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.mhx1999.top/Article/details/gtwqisyewe.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yongpay.top/Article/details/gtggqjroki.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gtwcaobjcn.html

Java: new Thread(() -> f()).start()
来源：http://dali.nanxuanxn.top/Article/details/gtuqqctbcu.html

Go:   go f()
来源：http://dali.svipenyu.cn/Article/details/gtpznqgjtt.html

Ruby: Thread.new { f }
来源：http://dali.smart0.xyz/Article/details/gtrfttcokq.html

C#:   Task.Run(() => F());
来源：http://dali.feifeiyinyue.top/Article/details/gtynduostt.html

[O02] 使用线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpvxshyh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangshuangyany.cn/Article/details/gtczqqfedw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.316326.xyz/Article/details/gthplwwwxq.html

JS:   // worker_threads 线程池
来源：http://dali.hammf.cn/Article/details/gtffzavlel.html

TS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gtjfdbnnzz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jiagoushi.top/Article/details/gtyfvxttfz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jyoumei.cn/Article/details/gtixyuwdzk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yuxming.cn/Article/details/gtkpgfyiej.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.kuanghao11.cn/Article/details/gtsfghnult.html

[O03] 加锁保护共享数据
来源：http://dali.cheryme.top/Article/details/gtjnjpvgzx.html

Py:   with lock: shared += 1
来源：http://dali.yuxming.cn/Article/details/gtpblfbcgw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhongyouzk.top/Article/details/gtowttvwtn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ybcxt.top/Article/details/gtgzncneqn.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gtjuaroscs.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldidefyk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinyuanbaomall.cn/Article/details/gticrwupfn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.redwolf501.top/Article/details/gtqghpjiuh.html

C#:   lock (gate) { shared++; }
来源：http://dali.sufxvd.cn/Article/details/gtlcqnnccx.html

[O04] 定义异步函数并等待
来源：http://dali.jqgufenzy.top/Article/details/gtlhgabyvy.html

Py:   async def f():⏎    await g()
来源：http://dali.havefunace.top/Article/details/gtyujjqfkh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.smart0.xyz/Article/details/gtdbvwktqr.html

JS:   async function f() { await g(); }
来源：http://dali.andypj.xyz/Article/details/gtuzuslzqr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gtsngtseqf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gzhubu.top/Article/details/gtesnvpvrk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuetiantiany.cn/Article/details/gticshgjxp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xylfe.cn/Article/details/gtnuaspaij.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gtqmjardwe.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuanzx.com/Article/details/gtcvbimvnp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtjbhkjutp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xziqi.cn/Article/details/gtuqysimjm.html

JS:   await Promise.all(tasks)
来源：http://dali.0kj1m.cn/Article/details/gtubsxqgnf.html

TS:   await Promise.all(tasks)
来源：http://dali.ydzc1.top/Article/details/gtxpjsrpsh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxinkj.top/Article/details/gtnmbyftat.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yuxming.cn/Article/details/gtsgqmpqrx.html

Ruby: threads.map(&:join)
来源：http://dali.birdmap.top/Article/details/gtmetptboj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gogol.net.cn/Article/details/gtffrwlhlg.html

[O06] 使用进程池
来源：http://dali.sweek.top/Article/details/gtmfjucmro.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cashguo.top/Article/details/gticokqlcc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sufxvd.cn/Article/details/gtytvsacfx.html

JS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gtpelcxvtn.html

TS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gtwzkdocew.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sufxvd.cn/Article/details/gtjksbmpkj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.9152youxi.cn/Article/details/gtnebdkbdp.html

Ruby: // fork 块
来源：http://dali.zhixingplan.top/Article/details/gtxgicydmn.html

C#:   Parallel.For
来源：http://dali.redwolf501.top/Article/details/gtdiljgfmv.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtixkmozmq.html

P. 常用工具函数
来源：http://dali.fengsongda.top/Article/details/gtfjcgauya.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtferfrewt.html

[P01] 生成 UUID
来源：http://dali.c1oappe.top/Article/details/gtqvdcxaum.html

Py:   str(uuid.uuid4())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpnrtkkl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sysykeji.top/Article/details/gtvdothkvn.html

JS:   crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gtddognolj.html

TS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gtxtdakvon.html

Java: UUID.randomUUID().toString()
来源：http://dali.fzhhl.top/Article/details/gtaxckxccs.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hnqzz.top/Article/details/gtmqiaxgof.html

Ruby: SecureRandom.uuid
来源：http://dali.hysaishi.cn/Article/details/gtkloeyexb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhtugsjm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikiavbfc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jiagoushi.top/Article/details/gtfktscqgc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhongyouzk.top/Article/details/gtlxkqozju.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hfpthk.cn/Article/details/gtdcqkrxkp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tanke756.top/Article/details/gtljuhtebl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.smart0.xyz/Article/details/gttblltvor.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigufen.top/Article/details/gtezkyhzio.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtnnpostcd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cheryme.top/Article/details/gtjsmttdgp.html

[P03] 生成短随机字符串
来源：http://dali.xylfe.cn/Article/details/gtiuodiwsm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.meibo888.top/Article/details/gttmigniqi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.iojbl.cn/Article/details/gtywshzmck.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gtmhrzhaji.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtljxcwahh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.wangdashe.top/Article/details/gtyahappje.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hfpthk.cn/Article/details/gtktujmifw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenlongwang.top/Article/details/gtctlragxy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.pycfn.com/Article/details/gtuyimelpq.html

[P04] 求长度
来源：http://dali.c1oappe.top/Article/details/gtjpxicfit.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hnxiangtu.top/Article/details/gteekvxmob.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gtnrsunbpw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gtapivobzy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gtsiduyqla.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cucudq.cn/Article/details/gtglkksrqu.html

Go:   len(arr);  len(m)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqaacewer.html

Ruby: x.length;  x.size
来源：http://dali.fzhhl.top/Article/details/gtncvnbykm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yonumen.top/Article/details/gthfqmovho.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xziqi.cn/Article/details/gtkznkvcnd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cucudq.cn/Article/details/gthnkkrcgn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhongyouzk.top/Article/details/gttvbhppzs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtsxtxss.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gogol.net.cn/Article/details/gtwrlyonpq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhongyouzk.top/Article/details/gtdrwcvwyq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtjbxtoyvp.html

Ruby: a == b
来源：http://dali.gotoacloud.top/Article/details/gtbvznfrok.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvpxpjrb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xylfe.cn/Article/details/gthkddjrmm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gogol.net.cn/Article/details/gtdnfiitbo.html

PHP:  if (empty($x)) {}
来源：http://dali.hysaishi.cn/Article/details/gtzsyxdprn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynzkcbiz.html

TS:   if (x == null) {}
来源：http://dali.jinqigfzy.top/Article/details/gtavarsyqr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gtcyeuiaej.html

Go:   if x == nil {}
来源：http://dali.c1oappe.top/Article/details/gtzjrzuagg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258.top/Article/details/gtgdqpqrjr.html

C#:   if (x is null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbaonmaww.html

[P07] 防抖与节流
来源：http://dali.0kj1m.cn/Article/details/gtcqnrhvji.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yonumen.top/Article/details/gteoyqnbav.html

PHP:  // 手写时间戳比较
来源：http://dali.sufxvd.cn/Article/details/gtfqnuyzat.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.havefunace.top/Article/details/gtutdiwrzx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gthebddqij.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aizwys.cn/Article/details/gthfeojubg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.aibaodan.cn/Article/details/gtiwoipdrj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.daria6918.cn/Article/details/gtvurhzmjj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yongpay.top/Article/details/gthfukxhyo.html

[P08] 处理浮点精度问题
来源：http://dali.ppjwa.cn/Article/details/gtlisfduow.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.9152youxi.cn/Article/details/gtktprjnnt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hnqzz.top/Article/details/gthgtcfwut.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gzhubu.top/Article/details/gtvibwmokv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcyyfqskl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shangyingyoupin.top/Article/details/gtmokiwyux.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenzaomai.com/Article/details/gtmkykaiez.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yongpay.top/Article/details/gtxgifgyva.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dashuyun.cn/Article/details/gtlsjcwcyz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtoyabnaqb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.andypj.xyz/Article/details/gtsuwubuti.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtntnlozdj.html

[Q01] 创建表
来源：http://dali.gzhubu.top/Article/details/gthvmzzrup.html

CREATE TABLE users (
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpchrdea.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xylfe.cn/Article/details/gtchbgsadf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cashguo.top/Article/details/gtifmuicax.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cheryme.top/Article/details/gtkgqeypov.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yangfankeji.com/Article/details/gtvrykhvrh.html

);
来源：http://dali.hysaishi.cn/Article/details/gtlqookozf.html

[Q02] 创建带外键的表
来源：http://dali.yangfankeji.com/Article/details/gtxprzjaeg.html

CREATE TABLE orders (
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiudsywad.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jianghu66.top/Article/details/gthxjdzyoi.html

user_id INT NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gtlqghnvty.html

amount DECIMAL(10, 2),
来源：http://dali.pengpengdd.cyou/Article/details/gtorfqttne.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxuanxn.top/Article/details/gtcavyzarc.html

);
来源：http://dali.sysykeji.top/Article/details/gtinqosphk.html

[Q03] 增加列
来源：http://dali.yongpay.top/Article/details/gtiufbfqto.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.fzhhl.top/Article/details/gthblhlcuh.html

[Q04] 修改列类型
来源：http://dali.hnqzz.top/Article/details/gtiuqnclhf.html


<!-- 参考信息 -->