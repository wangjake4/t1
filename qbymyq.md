代发 wailian999

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dianchejie.cn/Article/details/gtstgszlsn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.smart0.xyz/Article/details/gtorumwymu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.smart0.xyz/Article/details/gtvnxzbgll.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gotoacloud.top/Article/details/gthxtbqfqf.html

[M04] 获取当前工作目录
来源：http://dali.jqgfzy.top/Article/details/gtfmpwgilc.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gtjoxyuwmu.html

PHP:  getcwd();
来源：http://dali.gotoacloud.top/Article/details/gttooletcb.html

JS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gththgvtqh.html

TS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gtfauzanox.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hongshengwenyu.top/Article/details/gtwcwecgaq.html

Go:   os.Getwd()
来源：http://dali.cucudq.cn/Article/details/gtqwxbjbba.html

Ruby: Dir.pwd
来源：http://dali.c1oappe.top/Article/details/gtrypsvjfa.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nwbrower.top/Article/details/gtrwfwzdbd.html

[M05] 设置退出码
来源：http://dali.bjfxy.top/Article/details/gtjcvjzgew.html

Py:   sys.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtmdciumxn.html

PHP:  exit(1);
来源：http://dali.zhongyouzk.top/Article/details/gtykjmwipw.html

JS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtvhobrjyq.html

TS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtvpmkcxsi.html

Java: System.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtxlovalhy.html

Go:   os.Exit(1)
来源：http://dali.birdmap.top/Article/details/gtwddsysgp.html

Ruby: exit 1
来源：http://dali.chenzaomai.com/Article/details/gtfixvljup.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gtniohxjem.html

[M06] 向标准错误输出
来源：http://dali.jlsjyb.cn/Article/details/gtharlqujl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yanxiufei.cn/Article/details/gttmuwlhvu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.c1oappe.top/Article/details/gtcwkzbydp.html

JS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gtdgoubpxy.html

TS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gtebeptyyl.html

Java: System.err.println("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtkaidtiqp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangshuangyany.cn/Article/details/gtwqeirqto.html

Ruby: warn "err"
来源：http://dali.tanke756.top/Article/details/gtivikjqxm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtkgkrlnei.html

[M07] 判断是否为主入口
来源：http://dali.chenlongwang.top/Article/details/gteovselzd.html

Py:   if __name__ == "__main__":
来源：http://dali.tanke756.top/Article/details/gtvtdyilbb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbimjoiy.html

JS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gtuhyaunkp.html

TS:   require.main === module
来源：http://dali.snrcjt.cn/Article/details/gtvhlqewed.html

Java: public static void main(String[] args)
来源：http://dali.ppjwa.cn/Article/details/gtvgnajmsz.html

Go:   func main()
来源：http://dali.hfpthk.cn/Article/details/gtlnnmgckv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhongyouzk.top/Article/details/gtkoyzacch.html

C#:   static void Main(string[] args)
来源：http://dali.quarkkingdee.top/Article/details/gtovdociiw.html

[M08] 获取系统与运行时信息
来源：http://dali.chenjidiqi.icu/Article/details/gtroznjxmc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhongyouzk.top/Article/details/gtquvngbdx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sxryk.cn/Article/details/gtsduvddyb.html

JS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtsaypkwlf.html

TS:   process.platform;  process.version
来源：http://dali.yj20258.top/Article/details/gtkdsbsnjj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ybcxt.top/Article/details/gtqphzpkji.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gaohongyu789.top/Article/details/gtrvmtelaw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hammf.cn/Article/details/gtuoiwuvjd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gaohongyu789.top/Article/details/gtohwxuazx.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtmteydsss.html

N. 数据结构与算法
来源：http://dali.yj20258.top/Article/details/gtkmzgjqta.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtxxfqfqrj.html

[N01] 二分查找（有序数组）
来源：http://dali.zhixingplan.top/Article/details/gtglvsgomo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkaepzzhu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtcghxbkte.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gtaoexgqtc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gtifqxwwqt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtxqunojht.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtlunluklr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yanxiufei.cn/Article/details/gtvazfpiyi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtrtgefick.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gaohongyu789.top/Article/details/gtjkrhwkzl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gthjtgknor.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aizwys.cn/Article/details/gtxuixxzwy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtjxrkojpy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gtkgjuxafy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ehwqpu.com/Article/details/gtlthcffga.html

Go:   slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtluiqmagb.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gtlwfpkplr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yonumen.top/Article/details/gtdmscwaee.html

[N03] 快速排序（分治示例）
来源：http://dali.jyoumei.cn/Article/details/gtxyjyublm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hammf.cn/Article/details/gtlpurpvcf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangtech.top/Article/details/gtpybyndaz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gtjhutywsw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gtmxepfcfl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.mhx1999.top/Article/details/gthizexnum.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.iojbl.cn/Article/details/gtdrbtshug.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.9152youxi.cn/Article/details/gtwdjoijqg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ehwqpu.com/Article/details/gtlhqioroj.html

[N04] 斐波那契数列
来源：http://dali.yonumen.top/Article/details/gttghzbcry.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gtfjhlpmpe.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ybcxt.top/Article/details/gtgmltjmxy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gtpuihbvuf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gtitbehmsz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gtztweatnz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sxryk.cn/Article/details/gtcyfarmra.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtzcekxvsb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gtlutseelx.html

[N05] 最大公约数
来源：http://dali.gzhubu.top/Article/details/gtdlgsijnr.html

Py:   math.gcd(a, b)
来源：http://dali.guowangkeji.top/Article/details/gtljufkpco.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ydzc1.top/Article/details/gtfnykrahf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gtmuevofag.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gtcrekobxx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.vqdsnc.cn/Article/details/gtircouvdm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.9152youxi.cn/Article/details/gtnoadsedc.html

Ruby: a.gcd(b)
来源：http://dali.jinqigfzy.top/Article/details/gtkfsokgcb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daria6918.cn/Article/details/gtuebyvjuf.html

[N06] 判断回文字符串
来源：http://dali.zdqjudy.top/Article/details/gtpukoqehd.html

Py:   s == s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gtotoqyohv.html

PHP:  $s === strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gtzzqvnjcz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtjaghmcmg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtsjiasqog.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ydzc1.top/Article/details/gtycvvxjbs.html

Go:   // 双指针从两端比较
来源：http://dali.svipenyu.cn/Article/details/gtaxopasxv.html

Ruby: s == s.reverse
来源：http://dali.jqgfzy.top/Article/details/gtdmeeumeq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gtcgsmpbkl.html

[N07] 两数之和（返回下标）
来源：http://dali.quarkkingdee.top/Article/details/gtesluuedh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gttnyoizch.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jlsjyb.cn/Article/details/gtrhajxfbr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sysykeji.top/Article/details/gtgawutwxv.html

TS:   // 手写 Map<string, number>
来源：http://dali.sufxvd.cn/Article/details/gtheabjoli.html

Java: // 手写 HashMap
来源：http://dali.aibaodan.cn/Article/details/gtxbujwewk.html

Go:   // 手写 map[int]int
来源：http://dali.zhongyouzk.top/Article/details/gtmfrhopow.html

Ruby: // 手写 Hash
来源：http://dali.sysykeji.top/Article/details/gtfetegloe.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zycfv.cn/Article/details/gtiqwzxlwf.html

[N08] 生成全排列
来源：http://dali.daria6918.cn/Article/details/gtjlhiqhez.html

Py:   itertools.permutations(arr)
来源：http://dali.smart0.xyz/Article/details/gtnfeziqjw.html

PHP:  // 手写递归交换
来源：http://dali.hysaishi.cn/Article/details/gtiovionvz.html

JS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtkbiobvbj.html

TS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtvixyrwfh.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtxgylzmnr.html

Go:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtmjofarlw.html

Ruby: arr.permutation.to_a
来源：http://dali.tianlin.xyz/Article/details/gtxdhnasei.html

C#:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtpdwclgnj.html

[N09] 栈与队列
来源：http://dali.iojbl.cn/Article/details/gtajemrcbt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxinkj.top/Article/details/gtjidsqgkv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzegosuuv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gtgwdjclhu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigufen.top/Article/details/gttdqlcpbu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zdqjudy.top/Article/details/gtezxguysd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.0kj1m.cn/Article/details/gtxjayqbis.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gtislflkcc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hfpthk.cn/Article/details/gtgdmkedhm.html

[N10] 链表节点定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmxfkfmd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.redwolf501.top/Article/details/gtfxoksqct.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.pengpengdd.cyou/Article/details/gtacxtyppr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.meibo888.top/Article/details/gtsvpabesi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.aizwys.cn/Article/details/gtgmocvatj.html

Java: class Node { int v; Node next; }
来源：http://dali.mhx1999.top/Article/details/gtjmwzbcmh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daria6918.cn/Article/details/gtgqbmficg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.andypj.xyz/Article/details/gtesfjtnbz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.guowangkeji.top/Article/details/gtobnpimeh.html

[N11] 二叉树中序遍历
来源：http://dali.hysaishi.cn/Article/details/gtlpfguzrw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gthwrokvwm.html

PHP:  // 手写递归函数
来源：http://dali.ehwqpu.com/Article/details/gtcruhgpwt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gtggzhuses.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gtzlflfnmu.html

Java: // 手写递归
来源：http://dali.ybcxt.top/Article/details/gthegxoozz.html

Go:   // 手写递归
来源：http://dali.yongpay.top/Article/details/gtvfliucov.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yvedp.cn/Article/details/gttskkkzui.html

C#:   // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gtlusokagn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zdqjudy.top/Article/details/gtpwsmkgrb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj202588.top/Article/details/gthxonklnt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhoulong.xyz/Article/details/gtskldfhwl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gttrrvnprm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.kuanghao11.cn/Article/details/gtxcelcxwq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gtmnskpzfz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.birdmap.top/Article/details/gtsypnwjms.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.svipenyu.cn/Article/details/gtklziickp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gtsentzxcr.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtpaoqrzwz.html

O. 并发与异步
来源：http://dali.xuanzx.com/Article/details/gtucrbdobi.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtygehronp.html

[O01] 启动一个线程
来源：http://dali.jianghu66.top/Article/details/gtxnumnlrj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zdqjudy.top/Article/details/gtkynxulld.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhiwuduotai.top/Article/details/gtqcbgrsdq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shzxlz.cn/Article/details/gtjjiozrtm.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gtjvqvnydt.html

Java: new Thread(() -> f()).start()
来源：http://dali.nanxinkj.top/Article/details/gtbascujmr.html

Go:   go f()
来源：http://dali.svipenyu.cn/Article/details/gtpwqjyofj.html

Ruby: Thread.new { f }
来源：http://dali.haohaochexian.top/Article/details/gtxtuevtrv.html

C#:   Task.Run(() => F());
来源：http://dali.0kj1m.cn/Article/details/gtgiymsskt.html

[O02] 使用线程池
来源：http://dali.jianghu66.top/Article/details/gtztkkuiik.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yuanzhike.top/Article/details/gtizbjivzo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jiagoushi.top/Article/details/gtxzkslsbb.html

JS:   // worker_threads 线程池
来源：http://dali.tanke756.top/Article/details/gtojlkbdra.html

TS:   // worker_threads 线程池
来源：http://dali.gaohongyu789.top/Article/details/gtwmdkkdeq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hywenlv.cn/Article/details/gtkzlhjqdr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrwboflh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrssysgrn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.daria6918.cn/Article/details/gtwpwezfbo.html

[O03] 加锁保护共享数据
来源：http://dali.pycfn.com/Article/details/gtwjxlokpp.html

Py:   with lock: shared += 1
来源：http://dali.ivvv.top/Article/details/gtejjghwmv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cucudq.cn/Article/details/gtejnksdif.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tianlin.xyz/Article/details/gtqordupgh.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gtldituspv.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhengqikj.top/Article/details/gtzikusvmb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sufxvd.cn/Article/details/gtegerqvcr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.redwolf501.top/Article/details/gtqsilzlys.html

C#:   lock (gate) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gtaxpfqnsb.html

[O04] 定义异步函数并等待
来源：http://dali.bjfxy.top/Article/details/gtzsrdwpsy.html

Py:   async def f():⏎    await g()
来源：http://dali.yonumen.top/Article/details/gthpmicabv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhiwuduotai.top/Article/details/gthpufisvv.html

JS:   async function f() { await g(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxnnjryy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gtifvamtul.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigufen.top/Article/details/gtdgwtvvvw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhongyouzk.top/Article/details/gtopoohyjf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cheryme.top/Article/details/gtmjeiyeky.html

C#:   async Task F() { await G(); }
来源：http://dali.yangfankeji.com/Article/details/gtdgcjfjvt.html

[O05] 并发执行并等待全部完成
来源：http://dali.zycfv.cn/Article/details/gtlxygukml.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gogol.net.cn/Article/details/gtedfbtebz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shanyushiyangtech.top/Article/details/gtozftpttq.html

JS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gtpyjsalfj.html

TS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gtpjcuuepe.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pengpengdd.cyou/Article/details/gtzplcshrf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj20258.top/Article/details/gthfhiezfs.html

Ruby: threads.map(&:join)
来源：http://dali.cashguo.top/Article/details/gtxwjhvkbu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqpvxdwa.html

[O06] 使用进程池
来源：http://dali.chenlongwang.top/Article/details/gtmqyshyrg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hywenlv.cn/Article/details/gtafjbdfmz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.0kj1m.cn/Article/details/gtnfkwthtj.html

JS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gtmumsezvr.html

TS:   // child_process / cluster 模块
来源：http://dali.vqdsnc.cn/Article/details/gtcbfitalt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gtblokinhm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.wangshuangyany.cn/Article/details/gtkjwxkqan.html

Ruby: // fork 块
来源：http://dali.chenzaomai.com/Article/details/gtgupcvcxt.html

C#:   Parallel.For
来源：http://dali.zhengqikj.top/Article/details/gtcozzyitj.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtdqdxckbw.html

P. 常用工具函数
来源：http://dali.wangdashe.top/Article/details/gtazdhhpho.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtsshnciid.html

[P01] 生成 UUID
来源：http://dali.tianlin.xyz/Article/details/gtqsaiuudm.html

Py:   str(uuid.uuid4())
来源：http://dali.xuanzx.com/Article/details/gthttmiwmz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.quarkkingdee.top/Article/details/gttisstrww.html

JS:   crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gtdcfpzchl.html

TS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gtjtzvbjnd.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangdashe.top/Article/details/gtpximogyk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yvedp.cn/Article/details/gtwbebwnxd.html

Ruby: SecureRandom.uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemdzitrv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gtjdqcvjbr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangshuangyany.cn/Article/details/gtvkmfdbug.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.iojbl.cn/Article/details/gtfklsffbm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.9152youxi.cn/Article/details/gttpsvgocv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxuanxn.top/Article/details/gtskehxrdt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gotoacloud.top/Article/details/gtzyljkjwc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtuoftqygf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigufen.top/Article/details/gtqmhnvqxo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.guannengcc.top/Article/details/gtgiejvxgr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yongpay.top/Article/details/gtcducuzwm.html

[P03] 生成短随机字符串
来源：http://dali.jiagoushi.top/Article/details/gtrbcjppwl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xylfe.cn/Article/details/gtqpxcodlb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhengqikj.top/Article/details/gtlozcwiyq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gtlkgrfqqc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gtlhnqpvbb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yvedp.cn/Article/details/gtwwivhuzn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xziqi.cn/Article/details/gtftrmyyzs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.vqdsnc.cn/Article/details/gtmkqjnetw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zdqjudy.top/Article/details/gtsiovkulg.html

[P04] 求长度
来源：http://dali.yj202588.top/Article/details/gtiizumsaw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hywenlv.cn/Article/details/gtrdwcnzob.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtaqyycnde.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhengqikj.top/Article/details/gtctdrtvju.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gtsvyqnyez.html

Java: list.size();  map.size();  s.length()
来源：http://dali.0kj1m.cn/Article/details/gtuvdudlbk.html

Go:   len(arr);  len(m)
来源：http://dali.cheryme.top/Article/details/gtrfovcgny.html

Ruby: x.length;  x.size
来源：http://dali.sufxvd.cn/Article/details/gtpwmnqtga.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fengsongda.top/Article/details/gtbmermdqo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgftntjxc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guowangkeji.top/Article/details/gtjntblypp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dianchejie.cn/Article/details/gtyfuqdnfe.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhengqikj.top/Article/details/gtansfgykk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenzaomai.com/Article/details/gtbvxrytps.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yuanzhike.top/Article/details/gtdkwjknot.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtkuteukcm.html

Ruby: a == b
来源：http://dali.jlsjyb.cn/Article/details/gthtdyjivw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzphwdxsh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangdashe.top/Article/details/gtsalsktzd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yvedp.cn/Article/details/gtxxnmhcjn.html

PHP:  if (empty($x)) {}
来源：http://dali.cashguo.top/Article/details/gthivirsti.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.svipenyu.cn/Article/details/gtftllchnj.html

TS:   if (x == null) {}
来源：http://dali.yueranfly.top/Article/details/gtelvxlgpu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtfcowffws.html

Go:   if x == nil {}
来源：http://dali.shzxlz.cn/Article/details/gtfuumoueb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.smart0.xyz/Article/details/gtlucblkfa.html

C#:   if (x is null) {}
来源：http://dali.gzhubu.top/Article/details/gtfgwmhrsr.html

[P07] 防抖与节流
来源：http://dali.quarkkingdee.top/Article/details/gtlinktpfz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.meibo888.top/Article/details/gtrsioucer.html

PHP:  // 手写时间戳比较
来源：http://dali.tianlin.xyz/Article/details/gtidjfnnji.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gteleymehe.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtnhgokept.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daria6918.cn/Article/details/gtekmkykhd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ydzc1.top/Article/details/gtxfisfjrd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jqgfzy.top/Article/details/gthsmdqyzg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daria6918.cn/Article/details/gtmjzykfqj.html

[P08] 处理浮点精度问题
来源：http://dali.nwbrower.top/Article/details/gtedjchvjx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yangfankeji.com/Article/details/gttbzxedfx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sufxvd.cn/Article/details/gtppllmars.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shzxlz.cn/Article/details/gtzedqrmwv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.mhx1999.top/Article/details/gteqxmeaym.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yuxming.cn/Article/details/gtbkpqvtgg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xziqi.cn/Article/details/gtxdnhardx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jyoumei.cn/Article/details/gtddkfovjz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shuidangran.top/Article/details/gtvqwublym.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtihkiktmp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gaohongyu789.top/Article/details/gteltvkohf.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtfcojczci.html

[Q01] 创建表
来源：http://dali.meibo888.top/Article/details/gtcftgybvs.html

CREATE TABLE users (
来源：http://dali.zhongyouzk.top/Article/details/gtxcnwbtlf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gtqqvshnlt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gtnhhiergl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ehwqpu.com/Article/details/gtbxmanmuq.html


<!-- 参考信息 -->