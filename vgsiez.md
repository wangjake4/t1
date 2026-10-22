代发 wailian999

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhixingplan.top/Article/details/gtfqamqyhy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.mhx1999.top/Article/details/gtgikqswxz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hongshengwenyu.top/Article/details/gtudzoislg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sysykeji.top/Article/details/gtfgvzgbus.html

[M04] 获取当前工作目录
来源：http://dali.chenlongwang.top/Article/details/gtsnjtdkou.html

Py:   os.getcwd()
来源：http://dali.ybcxt.top/Article/details/gtksgxzxjh.html

PHP:  getcwd();
来源：http://dali.tanke756.top/Article/details/gtqvdsdthl.html

JS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gtxbhldsqq.html

TS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gtznmsyfby.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.mhx1999.top/Article/details/gtvgyzkxjp.html

Go:   os.Getwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtqaaokooh.html

Ruby: Dir.pwd
来源：http://dali.xylfe.cn/Article/details/gtwixejjvh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.andypj.xyz/Article/details/gtfenghjgf.html

[M05] 设置退出码
来源：http://dali.pycfn.com/Article/details/gttzyddvxy.html

Py:   sys.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtbfhphqij.html

PHP:  exit(1);
来源：http://dali.c1oappe.top/Article/details/gtmmzhvopm.html

JS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtfcpjqfnw.html

TS:   process.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtouhlxxkm.html

Java: System.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtbivkjnhf.html

Go:   os.Exit(1)
来源：http://dali.ybcxt.top/Article/details/gtuprfokvc.html

Ruby: exit 1
来源：http://dali.yuanzhike.top/Article/details/gtvhwjldgq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sufxvd.cn/Article/details/gtjpxrmzbh.html

[M06] 向标准错误输出
来源：http://dali.0kj1m.cn/Article/details/gtfoodknve.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gtylkrivdc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fzhhl.top/Article/details/gtvyzizlyx.html

JS:   console.error("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwclhxsj.html

TS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gtlbwkjpax.html

Java: System.err.println("err")
来源：http://dali.pycfn.com/Article/details/gtrxclbpxm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgfzy.top/Article/details/gttwnkkuel.html

Ruby: warn "err"
来源：http://dali.hongshengwenyu.top/Article/details/gtmguhttlp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.birdmap.top/Article/details/gtnznrpekp.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangtech.top/Article/details/gtudbjdipr.html

Py:   if __name__ == "__main__":
来源：http://dali.sysykeji.top/Article/details/gttezxieic.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cqqwz.cn/Article/details/gtncxkylpl.html

JS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gtkgmbexsj.html

TS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gttpsmunsd.html

Java: public static void main(String[] args)
来源：http://dali.daxiang520.top/Article/details/gtwojuqdxq.html

Go:   func main()
来源：http://dali.aibaodan.cn/Article/details/gtojhplais.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenjidiqi.icu/Article/details/gtvfcqwvgu.html

C#:   static void Main(string[] args)
来源：http://dali.daria6918.cn/Article/details/gtrlpespvc.html

[M08] 获取系统与运行时信息
来源：http://dali.redwolf501.top/Article/details/gthpvcqsls.html

Py:   platform.system();  platform.python_version()
来源：http://dali.smart0.xyz/Article/details/gtspviidof.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxinkj.top/Article/details/gtydgezgho.html

JS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gtennpwwmg.html

TS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gtnponrqpt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.meibo888.top/Article/details/gtydqihqxz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.meibo888.top/Article/details/gtvaxpnhra.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangdashe.top/Article/details/gtngvewuzk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fengsongda.top/Article/details/gtnhgwspfq.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gthmksohyo.html

N. 数据结构与算法
来源：http://dali.xuetiantiany.cn/Article/details/gtslrbdsvg.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gthldybclr.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigfzy.top/Article/details/gtpnucmobg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.316326.xyz/Article/details/gtjrsgjdig.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tian-w.cn/Article/details/gtslulpplb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtsduqzopm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsiokwoze.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gtkhihzprs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtfiwpranm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuanzhike.top/Article/details/gtasaanftt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gttphxntnj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tianlin.xyz/Article/details/gtqogbdsaz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gtbqgefglo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tianlin.xyz/Article/details/gtujfwsgxq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtnpjgwqje.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gtaxgmalun.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nwbrower.top/Article/details/gttcijqsdf.html

Go:   slices.Sort(arr)
来源：http://dali.pycfn.com/Article/details/gttcpbuolw.html

Ruby: arr.sort
来源：http://dali.haohaochexian.top/Article/details/gtwpcnuuud.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgufenzy.top/Article/details/gtasoyxcni.html

[N03] 快速排序（分治示例）
来源：http://dali.andypj.xyz/Article/details/gtumisewzt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchzdjrwt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jqgfzy.top/Article/details/gtnumqizua.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gtasfwxkqu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxinkj.top/Article/details/gtxczbrhbu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnqzz.top/Article/details/gtwxggynrl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yonumen.top/Article/details/gtpjhiabgm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenjidiqi.icu/Article/details/gtvcyxihjf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.pycfn.com/Article/details/gtzkhwstey.html

[N04] 斐波那契数列
来源：http://dali.cucudq.cn/Article/details/gtudtqecto.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gttsxvnvbo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gtllzqbigl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gtcrbgkdib.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtmwnnapxz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gtlscnnmcc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sxryk.cn/Article/details/gtgikafgog.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gtndibvaem.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gtdelpbgyr.html

[N05] 最大公约数
来源：http://dali.jinqigfzy.top/Article/details/gtkbgiymwx.html

Py:   math.gcd(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtpgzypryj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dashuyun.cn/Article/details/gtpraukucy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gtyveukkmb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gtoenneann.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigfzy.top/Article/details/gtxtiufyyq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.smart0.xyz/Article/details/gtrodjhfqb.html

Ruby: a.gcd(b)
来源：http://dali.nwbrower.top/Article/details/gtlnehwyhv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fengsongda.top/Article/details/gtcsmvpjni.html

[N06] 判断回文字符串
来源：http://dali.jqgfzy.top/Article/details/gtsksewpoh.html

Py:   s == s[::-1]
来源：http://dali.cashguo.top/Article/details/gtttdmbteg.html

PHP:  $s === strrev($s);
来源：http://dali.jinqigufen.top/Article/details/gtnuqsindt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtwjbntxer.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtkwvxgrfm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhongyouzk.top/Article/details/gthsceiavg.html

Go:   // 双指针从两端比较
来源：http://dali.sxryk.cn/Article/details/gtbdtsbqys.html

Ruby: s == s.reverse
来源：http://dali.guannengcc.top/Article/details/gtixhulqev.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gtsesjjcck.html

[N07] 两数之和（返回下标）
来源：http://dali.zhoulong.xyz/Article/details/gtylxcnjhg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangshuangyany.cn/Article/details/gtnmzuixww.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hywenlv.cn/Article/details/gtdkparrqz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.fengsongda.top/Article/details/gtnjvvhmme.html

TS:   // 手写 Map<string, number>
来源：http://dali.shuidangran.top/Article/details/gtejdgbhye.html

Java: // 手写 HashMap
来源：http://dali.yonumen.top/Article/details/gtgsjkiudh.html

Go:   // 手写 map[int]int
来源：http://dali.9152youxi.cn/Article/details/gtykoqxhzs.html

Ruby: // 手写 Hash
来源：http://dali.0kj1m.cn/Article/details/gtlwhudpch.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dianchejie.cn/Article/details/gtzoqhlque.html

[N08] 生成全排列
来源：http://dali.zdqjudy.top/Article/details/gtowswrezq.html

Py:   itertools.permutations(arr)
来源：http://dali.smart0.xyz/Article/details/gtyfhcemqj.html

PHP:  // 手写递归交换
来源：http://dali.zhongyouzk.top/Article/details/gtdmhavube.html

JS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtetrehbpi.html

TS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtsjdokjrp.html

Java: // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtbjkibzfv.html

Go:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtyryebmlf.html

Ruby: arr.permutation.to_a
来源：http://dali.zhongyouzk.top/Article/details/gtlxxuildc.html

C#:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtmuctndww.html

[N09] 栈与队列
来源：http://dali.yvedp.cn/Article/details/gtjqzguzhu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.iojbl.cn/Article/details/gtcyjgotfs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtmkvniyab.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtxvcbywnl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yvedp.cn/Article/details/gteganksma.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.snrcjt.cn/Article/details/gtqbqznsgc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ivvv.top/Article/details/gthroqexxo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gthuchrwam.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jqgufenzy.top/Article/details/gtyzybrmxl.html

[N10] 链表节点定义
来源：http://dali.tianlin.xyz/Article/details/gtnunmjgnp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daxiang520.top/Article/details/gtlwhmsmym.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.daria6918.cn/Article/details/gtiovaysjb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daria6918.cn/Article/details/gtbslokjih.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.vqdsnc.cn/Article/details/gtdrxeplxi.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258888.top/Article/details/gtwenwnbxm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenlongwang.top/Article/details/gtlguorejl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgufenzy.top/Article/details/gtodjvdnwk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ppjwa.cn/Article/details/gtznqcnsoo.html

[N11] 二叉树中序遍历
来源：http://dali.ehwqpu.com/Article/details/gtbtwfavwe.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwsdzsgu.html

PHP:  // 手写递归函数
来源：http://dali.pengpengdd.cyou/Article/details/gtlubzsgdn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gtjwdxxnhe.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gtuqedsjzk.html

Java: // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtdfhzqndr.html

Go:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gtfrioevsw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guowangkeji.top/Article/details/gtemvhmzea.html

C#:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gtesmtdgtr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.quarkkingdee.top/Article/details/gtotlavmbb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yanxiufei.cn/Article/details/gtuypzwucd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hywenlv.cn/Article/details/gthuhwtkwt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shangyingyoupin.top/Article/details/gtqxqthjqm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gthppmytmp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aibaodan.cn/Article/details/gtsbwwossu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.kuanghao11.cn/Article/details/gtsxfknarn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuxming.cn/Article/details/gttbpkdkcq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdpbozczw.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtmsjzrhdq.html

O. 并发与异步
来源：http://dali.gzhubu.top/Article/details/gteodktqfv.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtmsfrarkp.html

[O01] 启动一个线程
来源：http://dali.jinghuilouyu.cn/Article/details/gtybyfvlzq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.quarkkingdee.top/Article/details/gtqqpkmvml.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.pengpengdd.cyou/Article/details/gtykperjui.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuxming.cn/Article/details/gtbwlswnlk.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gtwdngkkhp.html

Java: new Thread(() -> f()).start()
来源：http://dali.jianghu66.top/Article/details/gtpuabxivn.html

Go:   go f()
来源：http://dali.xuanzx.com/Article/details/gtuuzbjchi.html

Ruby: Thread.new { f }
来源：http://dali.redwolf501.top/Article/details/gtxssrtejv.html

C#:   Task.Run(() => F());
来源：http://dali.daxiang520.top/Article/details/gtvfbhqgga.html

[O02] 使用线程池
来源：http://dali.guowangkeji.top/Article/details/gttskambhb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxinkj.top/Article/details/gtdncsilrn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daxiang520.top/Article/details/gtomrxeewy.html

JS:   // worker_threads 线程池
来源：http://dali.snrcjt.cn/Article/details/gtmqylbdgd.html

TS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gtqdlfuwcg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shuidangran.top/Article/details/gttfbtadhc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zycfv.cn/Article/details/gtdnfrnauw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.c1oappe.top/Article/details/gtqlbcfvvt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenjidiqi.icu/Article/details/gtxvqldkpe.html

[O03] 加锁保护共享数据
来源：http://dali.cashguo.top/Article/details/gtfsduhuow.html

Py:   with lock: shared += 1
来源：http://dali.cashguo.top/Article/details/gtnrltkszi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangshuangyany.cn/Article/details/gtvwwtctim.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiusvccam.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gtqhitoddw.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgufenzy.top/Article/details/gthaknhbmw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.quarkkingdee.top/Article/details/gtqdgepwyn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.9152youxi.cn/Article/details/gttyhvhylt.html

C#:   lock (gate) { shared++; }
来源：http://dali.wangdashe.top/Article/details/gtzbycjbfo.html

[O04] 定义异步函数并等待
来源：http://dali.jqgufenzy.top/Article/details/gtefbefgci.html

Py:   async def f():⏎    await g()
来源：http://dali.shzxlz.cn/Article/details/gtjlnthyby.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.aibaodan.cn/Article/details/gtfvzovtba.html

JS:   async function f() { await g(); }
来源：http://dali.sweek.top/Article/details/gtfldtnwri.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zycfv.cn/Article/details/gtwvdkyhrb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.pycfn.com/Article/details/gtnrbczsqc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.fengsongda.top/Article/details/gtqwtttlmv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shangyingyoupin.top/Article/details/gtwakbflis.html

C#:   async Task F() { await G(); }
来源：http://dali.chenlongwang.top/Article/details/gtqvubozle.html

[O05] 并发执行并等待全部完成
来源：http://dali.yuanzhike.top/Article/details/gthydumqht.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cashguo.top/Article/details/gtbzrhpwen.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jiagoushi.top/Article/details/gtzwkjguzi.html

JS:   await Promise.all(tasks)
来源：http://dali.chenlongwang.top/Article/details/gtruggfaab.html

TS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gtrhmipdiy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tanke756.top/Article/details/gtaxepjgtr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xziqi.cn/Article/details/gttimizojh.html

Ruby: threads.map(&:join)
来源：http://dali.ydzc1.top/Article/details/gtakbtncca.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenlongwang.top/Article/details/gtkraefrjw.html

[O06] 使用进程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtabosoxdr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.smart0.xyz/Article/details/gtvddsefrz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj20258.top/Article/details/gtapvuypui.html

JS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gtmyuyexxq.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258888.top/Article/details/gtxzrimzfi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnhwqkks.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvmdbznl.html

Ruby: // fork 块
来源：http://dali.zycfv.cn/Article/details/gtsqhfzvxp.html

C#:   Parallel.For
来源：http://dali.yj20258.top/Article/details/gtogwowyqo.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqymtiua.html

P. 常用工具函数
来源：http://dali.guowangkeji.top/Article/details/gtuvxjptbs.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtxpimstkp.html

[P01] 生成 UUID
来源：http://dali.vqdsnc.cn/Article/details/gtrwtizrzx.html

Py:   str(uuid.uuid4())
来源：http://dali.svipenyu.cn/Article/details/gtlttcecvm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gttdubkrpw.html

JS:   crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gtqniyosxj.html

TS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gtauemoqdp.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtkaaatcny.html

Go:   // 用 github.com/google/uuid
来源：http://dali.birdmap.top/Article/details/gtcwzdkywo.html

Ruby: SecureRandom.uuid
来源：http://dali.fengsongda.top/Article/details/gthpkflxxr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hammf.cn/Article/details/gtcpruqetj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.9152youxi.cn/Article/details/gtnarwemct.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigfzy.top/Article/details/gtxhuidzin.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yuxming.cn/Article/details/gtetqlwsxo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinqigufen.top/Article/details/gtuqkmznpx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nanxinkj.top/Article/details/gtryymcdkm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gtfsxjnkzm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dianchejie.cn/Article/details/gtfxizadax.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nwbrower.top/Article/details/gtenzztawk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yongpay.top/Article/details/gtirpgxjit.html

[P03] 生成短随机字符串
来源：http://dali.cqqwz.cn/Article/details/gtkpvqsjpj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sxryk.cn/Article/details/gttpiogaeq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tianlin.xyz/Article/details/gtvzwxfepq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gtydzwpggf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gtdevvlffg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.meibo888.top/Article/details/gtzqqaaifs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guannengcc.top/Article/details/gtrrmzjdgx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258888.top/Article/details/gtdfwnriqf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guowangkeji.top/Article/details/gtnzidrjwj.html

[P04] 求长度
来源：http://dali.hywenlv.cn/Article/details/gtfxlhybpc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinqigfzy.top/Article/details/gtnuprwbof.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtovcgiijv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.andypj.xyz/Article/details/gtttjbwymz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shuidangran.top/Article/details/gtcevtvkpd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dashuyun.cn/Article/details/gtzyvbwofc.html

Go:   len(arr);  len(m)
来源：http://dali.guowangkeji.top/Article/details/gtecbyavud.html

Ruby: x.length;  x.size
来源：http://dali.andypj.xyz/Article/details/gtaoatkzmb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gtogamqzhn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinqigufen.top/Article/details/gtajjczesq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hnqzz.top/Article/details/gtrmpilwel.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrhpoqtd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigufen.top/Article/details/gtprbavffo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aizwys.cn/Article/details/gtgvrfsgfi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hywenlv.cn/Article/details/gtljxcaorc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhnseriu.html

Ruby: a == b
来源：http://dali.zhengqikj.top/Article/details/gtnbromueq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ybcxt.top/Article/details/gttsrdlmca.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xinyue.icu/Article/details/gtnjdtbblm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvuulcgc.html

PHP:  if (empty($x)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtybicwhbe.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.iojbl.cn/Article/details/gtleanlozn.html

TS:   if (x == null) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtcbsmjxxr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yonumen.top/Article/details/gtbatwfyce.html

Go:   if x == nil {}
来源：http://dali.vqdsnc.cn/Article/details/gtyvkdpakw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.daxiang520.top/Article/details/gtktaqnlus.html

C#:   if (x is null) {}
来源：http://dali.ybcxt.top/Article/details/gtgnobmrba.html

[P07] 防抖与节流
来源：http://dali.aizwys.cn/Article/details/gtzgefmpww.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj202588.top/Article/details/gtbbubngvg.html

PHP:  // 手写时间戳比较
来源：http://dali.quarkkingdee.top/Article/details/gtbmmhrlmh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtxrhbbnqc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gtycpyayhi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gaohongyu789.top/Article/details/gtyngudjsk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhongyouzk.top/Article/details/gtqjgbeyxf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuanzx.com/Article/details/gtetlatprd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zdqjudy.top/Article/details/gtaytujyff.html

[P08] 处理浮点精度问题
来源：http://dali.nanxuanxn.top/Article/details/gtavjewswl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.bjfxy.top/Article/details/gtnsdoorlv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxuanxn.top/Article/details/gtcmudukcx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jianghu66.top/Article/details/gtpzxuwehz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenzaomai.com/Article/details/gtlqpbpwyp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shangyingyoupin.top/Article/details/gtfidylnpa.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cashguo.top/Article/details/gtfiltocqp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.fengsongda.top/Article/details/gtuowowmph.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.wangdashe.top/Article/details/gtwxislmja.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtwhaxfjyu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nanxinkj.top/Article/details/gtviikcjmy.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtnxuwpqol.html

[Q01] 创建表
来源：http://dali.iojbl.cn/Article/details/gtshvuvjkd.html

CREATE TABLE users (
来源：http://dali.yj202588.top/Article/details/gtiehbvrsd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xylfe.cn/Article/details/gtkaidctfs.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nanxuanxn.top/Article/details/gtjoshvnci.html

email VARCHAR(100) UNIQUE,
来源：http://dali.guowangkeji.top/Article/details/gtfeammith.html


<!-- 参考信息 -->