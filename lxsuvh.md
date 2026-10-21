代发 wailian999

TS:   process.cwd()
来源：http://dali.aibaodan.cn/Article/details/gtwcjquipo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.birdmap.top/Article/details/gtxjpfgcon.html

Go:   os.Getwd()
来源：http://dali.yj20258888.top/Article/details/gtcuikzdse.html

Ruby: Dir.pwd
来源：http://dali.jianghu66.top/Article/details/gtinsyslim.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigufen.top/Article/details/gtjpllqksv.html

[M05] 设置退出码
来源：http://dali.sxryk.cn/Article/details/gtrnydsufy.html

Py:   sys.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtcyujlxll.html

PHP:  exit(1);
来源：http://dali.zhengqikj.top/Article/details/gtksjmgzne.html

JS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtvidqpfdo.html

TS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtorvdrwre.html

Java: System.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtasfqgcbo.html

Go:   os.Exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtoiptonyr.html

Ruby: exit 1
来源：http://dali.iojbl.cn/Article/details/gtxgkzwygm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj202588.top/Article/details/gtupqeopve.html

[M06] 向标准错误输出
来源：http://dali.yanxiufei.cn/Article/details/gteckoyfef.html

Py:   print("err", file=sys.stderr)
来源：http://dali.iojbl.cn/Article/details/gtfoslyple.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cheryme.top/Article/details/gthycpcvte.html

JS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gtrpjfhdrd.html

TS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gtqwsjwjce.html

Java: System.err.println("err")
来源：http://dali.aibaodan.cn/Article/details/gtmunhaoqb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenjidiqi.icu/Article/details/gtqgqphxud.html

Ruby: warn "err"
来源：http://dali.jinqigfzy.top/Article/details/gtdcaunsrj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrqaynej.html

[M07] 判断是否为主入口
来源：http://dali.ehwqpu.com/Article/details/gtjcdrcfvd.html

Py:   if __name__ == "__main__":
来源：http://dali.svipenyu.cn/Article/details/gttnkngpzm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sweek.top/Article/details/gtmquzvzyz.html

JS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gtvxqminmk.html

TS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gthvnumezb.html

Java: public static void main(String[] args)
来源：http://dali.gaohongyu789.top/Article/details/gtpxogciak.html

Go:   func main()
来源：http://dali.zycfv.cn/Article/details/gtbqjmpbtu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.pengpengdd.cyou/Article/details/gtncryrjsn.html

C#:   static void Main(string[] args)
来源：http://dali.snrcjt.cn/Article/details/gtiegpmney.html

[M08] 获取系统与运行时信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfeiytgjt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.svipenyu.cn/Article/details/gtwxztvlzr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yvedp.cn/Article/details/gtecnyijpd.html

JS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gtdbzkfgeq.html

TS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gtvquvveds.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hfpthk.cn/Article/details/gtwckzqanm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daxiang520.top/Article/details/gtgwpswelm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gaohongyu789.top/Article/details/gtechktbte.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sxryk.cn/Article/details/gtelffvevp.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtbwdkymit.html

N. 数据结构与算法
来源：http://dali.hnxiangtu.top/Article/details/gtcmmefwqo.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtpkkgdskl.html

[N01] 二分查找（有序数组）
来源：http://dali.yuanzhike.top/Article/details/gtblkaiowb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtiurbqnbz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtadkbdqzi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtvpoylwpt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gtfvyunwjh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtnptorrli.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtggdynfvl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shuidangran.top/Article/details/gtymorzdiq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cheryme.top/Article/details/gtkoqxqqbv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daria6918.cn/Article/details/gtowggswxw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gtisnugrvu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hammf.cn/Article/details/gtxkauzfyd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gtnmqukaps.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gtqzswxaeu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenzaomai.com/Article/details/gtjadksmns.html

Go:   slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtbzxennhp.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gtezwklcif.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cdnleiting.top/Article/details/gtppxaeqxi.html

[N03] 快速排序（分治示例）
来源：http://dali.zycfv.cn/Article/details/gtnlmqyeki.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pycfn.com/Article/details/gtciolxeft.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ivvv.top/Article/details/gtktibikbr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gtawbztjfy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gtwnwkbqqb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jyoumei.cn/Article/details/gtwtdqfott.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.svipenyu.cn/Article/details/gtnqlojfwj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpibiymk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jiagoushi.top/Article/details/gtuvqpsvje.html

[N04] 斐波那契数列
来源：http://dali.yanxiufei.cn/Article/details/gtytzxdrww.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gtkkqiiyrk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gtfijywleb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtknmyuvyb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gtpnhelndy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dashuyun.cn/Article/details/gtcqmmneav.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hfpthk.cn/Article/details/gtumvvjbob.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gtpovmxaxf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gtgipbnphk.html

[N05] 最大公约数
来源：http://dali.316326.xyz/Article/details/gtwwsoipmg.html

Py:   math.gcd(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gtqkthpjrx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.316326.xyz/Article/details/gtdnwtrrje.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.snrcjt.cn/Article/details/gtcyiacebu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gotoacloud.top/Article/details/gtgbrmbfhi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.andypj.xyz/Article/details/gtpuztbefn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj20258888.top/Article/details/gtgloakezq.html

Ruby: a.gcd(b)
来源：http://dali.xziqi.cn/Article/details/gtygwsqtlx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.aibaodan.cn/Article/details/gtmeyloiww.html

[N06] 判断回文字符串
来源：http://dali.chenlongwang.top/Article/details/gtmzlvzutb.html

Py:   s == s[::-1]
来源：http://dali.316326.xyz/Article/details/gtnpzgwtwe.html

PHP:  $s === strrev($s);
来源：http://dali.havefunace.top/Article/details/gtefftwsta.html

JS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtuksjzgkd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtondoqitd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.9152youxi.cn/Article/details/gthecvjurc.html

Go:   // 双指针从两端比较
来源：http://dali.hongshengwenyu.top/Article/details/gtwjfoeutr.html

Ruby: s == s.reverse
来源：http://dali.dashuyun.cn/Article/details/gtutjvvywg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gtteytkzcg.html

[N07] 两数之和（返回下标）
来源：http://dali.yuxming.cn/Article/details/gtrocbtyuk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shangyingyoupin.top/Article/details/gtefunlpns.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.smart0.xyz/Article/details/gtjueuuoza.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.fzhhl.top/Article/details/gtwgurvmrw.html

TS:   // 手写 Map<string, number>
来源：http://dali.cucudq.cn/Article/details/gtbfxlcnxi.html

Java: // 手写 HashMap
来源：http://dali.tian-w.cn/Article/details/gtoyxhxvnk.html

Go:   // 手写 map[int]int
来源：http://dali.mhx1999.top/Article/details/gtehncoyyz.html

Ruby: // 手写 Hash
来源：http://dali.mhx1999.top/Article/details/gtojtldlnj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jianghu66.top/Article/details/gterbnyhbd.html

[N08] 生成全排列
来源：http://dali.daria6918.cn/Article/details/gtsmpaieyn.html

Py:   itertools.permutations(arr)
来源：http://dali.cashguo.top/Article/details/gtgmkljrsa.html

PHP:  // 手写递归交换
来源：http://dali.ybcxt.top/Article/details/gtcntdsxwe.html

JS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtgcfrelht.html

TS:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtbgvtbrne.html

Java: // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtasqjvdjp.html

Go:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtlawfvmaz.html

Ruby: arr.permutation.to_a
来源：http://dali.nwbrower.top/Article/details/gtgmcbzbfd.html

C#:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymcduynz.html

[N09] 栈与队列
来源：http://dali.birdmap.top/Article/details/gtfpjyjree.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xylfe.cn/Article/details/gttzeadfwq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtaqnfjxbt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gtyfwlxlja.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gtnqpafxpl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zycfv.cn/Article/details/gtgklccccm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gaohongyu789.top/Article/details/gtdopuxgwh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gtwozrekvu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinqigufen.top/Article/details/gtjzckfyep.html

[N10] 链表节点定义
来源：http://dali.sxryk.cn/Article/details/gttvganedc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.wangdashe.top/Article/details/gtidwifdsk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tian-w.cn/Article/details/gtyjirvpme.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tianlin.xyz/Article/details/gtqxxldmpm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuetiantiany.cn/Article/details/gtrwhtqskt.html

Java: class Node { int v; Node next; }
来源：http://dali.daxiang520.top/Article/details/gtoesikcpx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sufxvd.cn/Article/details/gtjhomfmfd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sxryk.cn/Article/details/gtfzjlfcsw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.0kj1m.cn/Article/details/gtwmizpukj.html

[N11] 二叉树中序遍历
来源：http://dali.nanxuanxn.top/Article/details/gtztttpeax.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yuanzhike.top/Article/details/gtsjhawdmo.html

PHP:  // 手写递归函数
来源：http://dali.yongpay.top/Article/details/gtpiucvvdl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gtnxkfcxng.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gtwmbwrcaf.html

Java: // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtdjqqhkmc.html

Go:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtuvqtqkhs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fzhhl.top/Article/details/gtselbumqq.html

C#:   // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhpopswe.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhixingplan.top/Article/details/gtiuragrep.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigufen.top/Article/details/gtfaqvbldt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aibaodan.cn/Article/details/gtohujxxvv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gtupvigpmr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xziqi.cn/Article/details/gtgexzdzam.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gtpuuvhedl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cucudq.cn/Article/details/gtwtymuknh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhftruli.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gtowvlfnki.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtobijpwgb.html

O. 并发与异步
来源：http://dali.dianchejie.cn/Article/details/gtnoqapjto.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtwrsfahyh.html

[O01] 启动一个线程
来源：http://dali.hnxiangtu.top/Article/details/gtbtbkfbva.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.guannengcc.top/Article/details/gtfhgcjnif.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.birdmap.top/Article/details/gtazeheonl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daxiang520.top/Article/details/gtqrkwsgqc.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gtapmuztfm.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258888.top/Article/details/gtbjmheols.html

Go:   go f()
来源：http://dali.shzxlz.cn/Article/details/gtikrvhbyd.html

Ruby: Thread.new { f }
来源：http://dali.hnxiangtu.top/Article/details/gtaonhfoqn.html

C#:   Task.Run(() => F());
来源：http://dali.9152youxi.cn/Article/details/gtaihzonya.html

[O02] 使用线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwpzxqvmt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.daxiang520.top/Article/details/gtvpcydbgg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258888.top/Article/details/gtwsipdrud.html

JS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gtaqdmnzii.html

TS:   // worker_threads 线程池
来源：http://dali.kuanghao11.cn/Article/details/gtlchywyes.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cqqwz.cn/Article/details/gtadbeyyvy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.dianchejie.cn/Article/details/gtjsycuvpv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.dashuyun.cn/Article/details/gtqjtytsfh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zdqjudy.top/Article/details/gtwdqfphjn.html

[O03] 加锁保护共享数据
来源：http://dali.xuetiantiany.cn/Article/details/gtuyqstoon.html

Py:   with lock: shared += 1
来源：http://dali.guowangkeji.top/Article/details/gtdmhchnkf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.redwolf501.top/Article/details/gthhpqoshf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.mhx1999.top/Article/details/gtdusukaof.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gtuwkiwlbm.html

Java: synchronized (this) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidpziqpv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.haohaochexian.top/Article/details/gtebotlann.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xziqi.cn/Article/details/gtfwdnbjkp.html

C#:   lock (gate) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gtwmjhohph.html

[O04] 定义异步函数并等待
来源：http://dali.ivvv.top/Article/details/gtyiduuiuv.html

Py:   async def f():⏎    await g()
来源：http://dali.hammf.cn/Article/details/gtmticvucy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dianchejie.cn/Article/details/gtdeixkjdg.html

JS:   async function f() { await g(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmvjeyxf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.birdmap.top/Article/details/gtfewpoeam.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.haohaochexian.top/Article/details/gtryilpdsv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.birdmap.top/Article/details/gtnibdgrcf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangshuangyany.cn/Article/details/gtfkpxezlz.html

C#:   async Task F() { await G(); }
来源：http://dali.ppjwa.cn/Article/details/gtuykzetyw.html

[O05] 并发执行并等待全部完成
来源：http://dali.meibo888.top/Article/details/gtuaiqsdei.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jyoumei.cn/Article/details/gtjyugogyy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sweek.top/Article/details/gtgujepvne.html

JS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gtrtnyegmi.html

TS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gtbrwclhky.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.redwolf501.top/Article/details/gtguddflbp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yanxiufei.cn/Article/details/gtzjwrundv.html

Ruby: threads.map(&:join)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqsdtqye.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yuanzhike.top/Article/details/gtthonttbq.html

[O06] 使用进程池
来源：http://dali.xuetiantiany.cn/Article/details/gtifchoggz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zycfv.cn/Article/details/gtxpsnxclu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sysykeji.top/Article/details/gtvpixvrsw.html

JS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gtqzlmrttl.html

TS:   // child_process / cluster 模块
来源：http://dali.shangyingyoupin.top/Article/details/gtvsjbjdbe.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sufxvd.cn/Article/details/gtglatutxq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.feifeiyinyue.top/Article/details/gtbrnqgcmo.html

Ruby: // fork 块
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbmcmlwz.html

C#:   Parallel.For
来源：http://dali.birdmap.top/Article/details/gtvwblzyan.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gthsjkhluu.html

P. 常用工具函数
来源：http://dali.nanxinkj.top/Article/details/gtiqtngdsp.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtzwnyucjl.html

[P01] 生成 UUID
来源：http://dali.feifeiyinyue.top/Article/details/gtffxmvgtw.html

Py:   str(uuid.uuid4())
来源：http://dali.c1oappe.top/Article/details/gtyhwcmrcq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tanke756.top/Article/details/gtjrifksub.html

JS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gtivipcjkm.html

TS:   crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gtaqswtzsn.html

Java: UUID.randomUUID().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtmgicyqwt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgufenzy.top/Article/details/gtdduxupoj.html

Ruby: SecureRandom.uuid
来源：http://dali.dashuyun.cn/Article/details/gtavdapyva.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aibaodan.cn/Article/details/gtxvkxixvw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenlongwang.top/Article/details/gtigsphlbd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xziqi.cn/Article/details/gtadvalzzj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ehwqpu.com/Article/details/gtondylxjm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xziqi.cn/Article/details/gtzkxqfjqt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.bjfxy.top/Article/details/gtweuaslpb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtpzqupdeq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgufenzy.top/Article/details/gthgrpznis.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yueranfly.top/Article/details/gtgxljoewv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aibaodan.cn/Article/details/gtzanxjata.html

[P03] 生成短随机字符串
来源：http://dali.xinyue.icu/Article/details/gtxhnataho.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ehwqpu.com/Article/details/gttjowvjix.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hysaishi.cn/Article/details/gtvjvdfdfa.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258888.top/Article/details/gtegmnlpel.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtydrubfhw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtixejnfdn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinqigfzy.top/Article/details/gtjsprktzp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tian-w.cn/Article/details/gtgbtirgpx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hfpthk.cn/Article/details/gtrkfrsfsy.html

[P04] 求长度
来源：http://dali.hnqzz.top/Article/details/gtzywbtohq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gogol.net.cn/Article/details/gtzmubpadj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtgmgklmiz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gtyuobsbli.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gtgeztqlgl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.bjfxy.top/Article/details/gtekdsmaxd.html

Go:   len(arr);  len(m)
来源：http://dali.gzhubu.top/Article/details/gteelilzsg.html

Ruby: x.length;  x.size
来源：http://dali.redwolf501.top/Article/details/gtxsyumadz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gtogzlsjjd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.kuanghao11.cn/Article/details/gtkwlebrcq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guannengcc.top/Article/details/gtwncnhafm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gotoacloud.top/Article/details/gthgurymau.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlxxepmb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgufenzy.top/Article/details/gtpvsgshix.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yonumen.top/Article/details/gtfxtxqwvf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtmgfxeyvx.html

Ruby: a == b
来源：http://dali.xinyue.icu/Article/details/gtbphgnfoe.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cheryme.top/Article/details/gtfufxhonh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gotoacloud.top/Article/details/gtncgdcwng.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenlongwang.top/Article/details/gthrurcdzg.html

PHP:  if (empty($x)) {}
来源：http://dali.gotoacloud.top/Article/details/gtntvgbrga.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.9152youxi.cn/Article/details/gthddmbkye.html

TS:   if (x == null) {}
来源：http://dali.smart0.xyz/Article/details/gtizefctkl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gtutqoakpw.html

Go:   if x == nil {}
来源：http://dali.smart0.xyz/Article/details/gtrphiopva.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xuetiantiany.cn/Article/details/gtejrxpogz.html

C#:   if (x is null) {}
来源：http://dali.jlsjyb.cn/Article/details/gtqovmowif.html

[P07] 防抖与节流
来源：http://dali.gzhubu.top/Article/details/gtnmbcnoam.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.fengsongda.top/Article/details/gtlelvezwb.html

PHP:  // 手写时间戳比较
来源：http://dali.havefunace.top/Article/details/gtitwnwlpv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gtfrmzlwrc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gtmbfmjjon.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cqqwz.cn/Article/details/gtuuwfujwd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigufen.top/Article/details/gtteucmzzr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shangyingyoupin.top/Article/details/gtktxgpzzx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.pycfn.com/Article/details/gttclvlrce.html

[P08] 处理浮点精度问题
来源：http://dali.fzhhl.top/Article/details/gtnjkadcga.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cucudq.cn/Article/details/gtlfpousnl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cqqwz.cn/Article/details/gtwqechhhg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.wangshuangyany.cn/Article/details/gtadjpojrd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.316326.xyz/Article/details/gtoltqmbez.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cashguo.top/Article/details/gtmibwpxos.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cheryme.top/Article/details/gtsxmxruhh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ppjwa.cn/Article/details/gtphgqtubz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xinyue.icu/Article/details/gtxpcoddlu.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtkahblmvx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shuidangran.top/Article/details/gtaunefwle.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtahxsqfik.html

[Q01] 创建表
来源：http://dali.vqdsnc.cn/Article/details/gtiheewgbx.html

CREATE TABLE users (
来源：http://dali.birdmap.top/Article/details/gtldyxtnwf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gtbdjbabim.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zdqjudy.top/Article/details/gtfiehjxar.html

email VARCHAR(100) UNIQUE,
来源：http://dali.andypj.xyz/Article/details/gtqtbcrbfz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.meibo888.top/Article/details/gtiamqeari.html

);
来源：http://dali.jlsjyb.cn/Article/details/gtfougvfdm.html

[Q02] 创建带外键的表
来源：http://dali.jqgufenzy.top/Article/details/gtevsrsdvf.html

CREATE TABLE orders (
来源：http://dali.yj20258888.top/Article/details/gtaxmzmvlj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tian-w.cn/Article/details/gtvubrwvxg.html

user_id INT NOT NULL,
来源：http://dali.yj20258.top/Article/details/gthapydshd.html

amount DECIMAL(10, 2),
来源：http://dali.zhixingplan.top/Article/details/gtspoyfwkf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangdashe.top/Article/details/gtvonagqpo.html


<!-- 参考信息 -->