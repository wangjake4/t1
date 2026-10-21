代发 wailian999

JS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtvpfvvzkc.html

TS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gthgjutoyo.html

Java: args 数组（main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gtouquzqnh.html

Go:   os.Args[1:]
来源：http://dali.guowangkeji.top/Article/details/gtgqcddite.html

Ruby: ARGV
来源：http://dali.ehwqpu.com/Article/details/gtxluyqhcv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtfqoewnug.html

[M02] 读取环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gtaifnwkbi.html

Py:   os.environ.get("HOME")
来源：http://dali.zycfv.cn/Article/details/gtymskkbqc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sweek.top/Article/details/gtxdvfbeyz.html

JS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gtpdxpqiqm.html

TS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gtqrazmgmr.html

Java: System.getenv("HOME")
来源：http://dali.hnqzz.top/Article/details/gtglhclhdo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gthbswbsvr.html

Ruby: ENV["HOME"]
来源：http://dali.guowangkeji.top/Article/details/gtirylgzkq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtyozhcqns.html

[M03] 执行外部命令
来源：http://dali.ivvv.top/Article/details/gtkfgkgdxz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjchtzgss.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sufxvd.cn/Article/details/gtyfmkoijw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigufen.top/Article/details/gtuiwyfmji.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gttirnxpyy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.meibo888.top/Article/details/gtahnbhyvc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yueranfly.top/Article/details/gtzulfhyne.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yangfankeji.com/Article/details/gtkfjyzrou.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cucudq.cn/Article/details/gtfiawirqe.html

[M04] 获取当前工作目录
来源：http://dali.chenjidiqi.icu/Article/details/gtfzrdmuvc.html

Py:   os.getcwd()
来源：http://dali.tanke756.top/Article/details/gtsiwrhazc.html

PHP:  getcwd();
来源：http://dali.nanxinkj.top/Article/details/gtneqhvete.html

JS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gtlrunwvgv.html

TS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtydzxmcap.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.svipenyu.cn/Article/details/gtrbirmuyx.html

Go:   os.Getwd()
来源：http://dali.zhongyouzk.top/Article/details/gtxnsaqexi.html

Ruby: Dir.pwd
来源：http://dali.vqdsnc.cn/Article/details/gttkzgdsjc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jlsjyb.cn/Article/details/gtdzavidzh.html

[M05] 设置退出码
来源：http://dali.svipenyu.cn/Article/details/gthmbsdngm.html

Py:   sys.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtpkewxdpo.html

PHP:  exit(1);
来源：http://dali.jqgfzy.top/Article/details/gtjafninqt.html

JS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtsqnncryn.html

TS:   process.exit(1)
来源：http://dali.316326.xyz/Article/details/gtrgytawkh.html

Java: System.exit(1)
来源：http://dali.c1oappe.top/Article/details/gthwmfmmeo.html

Go:   os.Exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtenzhnklb.html

Ruby: exit 1
来源：http://dali.zhengqikj.top/Article/details/gtprucmnoz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenjidiqi.icu/Article/details/gtjddzsduo.html

[M06] 向标准错误输出
来源：http://dali.iojbl.cn/Article/details/gteevpdijs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hysaishi.cn/Article/details/gtwmztxqps.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xinyue.icu/Article/details/gthkcnhcie.html

JS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gthnomdaku.html

TS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gtjilrpxko.html

Java: System.err.println("err")
来源：http://dali.aibaodan.cn/Article/details/gtblfobnyu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnqzz.top/Article/details/gtuxdcpicx.html

Ruby: warn "err"
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgoftvif.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnqzz.top/Article/details/gtikepujxd.html

[M07] 判断是否为主入口
来源：http://dali.jianghu66.top/Article/details/gthjajwdkx.html

Py:   if __name__ == "__main__":
来源：http://dali.cheryme.top/Article/details/gtbmmromcg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmeubiybm.html

JS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gtwpnowuyy.html

TS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gtfiifllrg.html

Java: public static void main(String[] args)
来源：http://dali.quarkkingdee.top/Article/details/gtbddedpte.html

Go:   func main()
来源：http://dali.daxiang520.top/Article/details/gtoxqvoqnc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yongpay.top/Article/details/gtvpbxnpoy.html

C#:   static void Main(string[] args)
来源：http://dali.aibaodan.cn/Article/details/gtytuofsuq.html

[M08] 获取系统与运行时信息
来源：http://dali.zhoulong.xyz/Article/details/gtqqcszplm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.vqdsnc.cn/Article/details/gtopqjkcke.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zdqjudy.top/Article/details/gtjhuxmxij.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gtqmnvlxsw.html

TS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gtyzkxotmu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.haohaochexian.top/Article/details/gtmdqgkxat.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xziqi.cn/Article/details/gtirtxdvgb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.snrcjt.cn/Article/details/gtxlwpovie.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gotoacloud.top/Article/details/gtfgimcruo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtsayvneka.html

N. 数据结构与算法
来源：http://dali.yj20258888.top/Article/details/gtcrhatrrg.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtdzcwkyfa.html

[N01] 二分查找（有序数组）
来源：http://dali.cucudq.cn/Article/details/gtqnjualew.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtcnwekqqp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmhhunang.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gtpetowayv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xziqi.cn/Article/details/gtvpxdwwif.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gthikipeww.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtihdwkjoe.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ppjwa.cn/Article/details/gtkhvynvcp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtrgyocwsx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hammf.cn/Article/details/gtzlwuqgop.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuetiantiany.cn/Article/details/gtukjbswxe.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtysinszjx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gtzziqszoc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtlbwoipnk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yongpay.top/Article/details/gtybnyswrr.html

Go:   slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gtydtvqkpg.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gtxvlqmfcr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinqigfzy.top/Article/details/gtkbongyxn.html

[N03] 快速排序（分治示例）
来源：http://dali.xylfe.cn/Article/details/gtnkunocag.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ybcxt.top/Article/details/gtjrxuoqnh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jqgufenzy.top/Article/details/gtrhypfsvj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gtdfyawdfw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gttnhnoift.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.kuanghao11.cn/Article/details/gtcmlrmisx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.kuanghao11.cn/Article/details/gtoylefwue.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shuidangran.top/Article/details/gtchkexbcp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cheryme.top/Article/details/gtttaauadg.html

[N04] 斐波那契数列
来源：http://dali.nwbrower.top/Article/details/gtqbohamwc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hammf.cn/Article/details/gtouwflpes.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sxryk.cn/Article/details/gtppbiptzk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gtrdnohaox.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtmtavhdgx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tian-w.cn/Article/details/gtkwjstxit.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.316326.xyz/Article/details/gteblhuxpx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gttpslkmol.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gtrhwosbdw.html

[N05] 最大公约数
来源：http://dali.jinqigufen.top/Article/details/gtabnzrlki.html

Py:   math.gcd(a, b)
来源：http://dali.gzhubu.top/Article/details/gtfyjfsgpx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbtstwhc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gtyaeybdax.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gtcbndwkbj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.meibo888.top/Article/details/gtyxxlvdae.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxinkj.top/Article/details/gtixjcmcap.html

Ruby: a.gcd(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtdcfnkygk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jianghu66.top/Article/details/gtdkrgwuds.html

[N06] 判断回文字符串
来源：http://dali.havefunace.top/Article/details/gtlqvbavbr.html

Py:   s == s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gtzwmoxmkf.html

PHP:  $s === strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtgwskimfg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gteugwqsgr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtsghorzbo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.dashuyun.cn/Article/details/gtjyumgiyf.html

Go:   // 双指针从两端比较
来源：http://dali.hysaishi.cn/Article/details/gtjumzfthq.html

Ruby: s == s.reverse
来源：http://dali.guannengcc.top/Article/details/gtrhswghqt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gtmafetavg.html

[N07] 两数之和（返回下标）
来源：http://dali.cucudq.cn/Article/details/gtnmikbaaf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigufen.top/Article/details/gtlrrachjk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ivvv.top/Article/details/gtpinikwzx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuanzhike.top/Article/details/gtaceiwxcd.html

TS:   // 手写 Map<string, number>
来源：http://dali.ybcxt.top/Article/details/gtkqxznbzb.html

Java: // 手写 HashMap
来源：http://dali.hysaishi.cn/Article/details/gtwjmlbthm.html

Go:   // 手写 map[int]int
来源：http://dali.andypj.xyz/Article/details/gthbcuoofc.html

Ruby: // 手写 Hash
来源：http://dali.guowangkeji.top/Article/details/gtrhqshziv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj20258888.top/Article/details/gtmweqcwiw.html

[N08] 生成全排列
来源：http://dali.jqgufenzy.top/Article/details/gtnypkrvgg.html

Py:   itertools.permutations(arr)
来源：http://dali.sysykeji.top/Article/details/gtenpvykmi.html

PHP:  // 手写递归交换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjppundb.html

JS:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtbndqfjko.html

TS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtjxmqctui.html

Java: // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtdbufxbqq.html

Go:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtsuaevjgg.html

Ruby: arr.permutation.to_a
来源：http://dali.chenjidiqi.icu/Article/details/gtrpfpqjez.html

C#:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtxcmewbvk.html

[N09] 栈与队列
来源：http://dali.9152youxi.cn/Article/details/gtrxwhqxid.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtupjciswa.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tanke756.top/Article/details/gtpoknlzro.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gthvvcgvtw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258888.top/Article/details/gthxhbazmj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.wangdashe.top/Article/details/gtpkosroce.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cqqwz.cn/Article/details/gtdqeurhnu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sysykeji.top/Article/details/gtgrgczlfn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sweek.top/Article/details/gtvmzbwzhi.html

[N10] 链表节点定义
来源：http://dali.daria6918.cn/Article/details/gtsyxrkfzk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gogol.net.cn/Article/details/gtjauqksvl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj20258888.top/Article/details/gtnkbttaec.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sysykeji.top/Article/details/gtiergtdvs.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hysaishi.cn/Article/details/gtlauzoqnw.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgufenzy.top/Article/details/gtxuromuzh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzdxnjiv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258888.top/Article/details/gtjasopfei.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gzhubu.top/Article/details/gtlltzoxbm.html

[N11] 二叉树中序遍历
来源：http://dali.nanxinkj.top/Article/details/gtjtkibqrb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zycfv.cn/Article/details/gtjswfqllo.html

PHP:  // 手写递归函数
来源：http://dali.xuanzx.com/Article/details/gtamvkldwo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pengpengdd.cyou/Article/details/gthgungldj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gtztiehihh.html

Java: // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvnurwix.html

Go:   // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gtuazsjwxd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuiylwwxi.html

C#:   // 手写递归
来源：http://dali.yvedp.cn/Article/details/gtyhtpsydl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.feifeiyinyue.top/Article/details/gthvzvwisr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sxryk.cn/Article/details/gtwlweunwn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.316326.xyz/Article/details/gthtnnzqcu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gtgyrkaupr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gtgmowpbkm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgxgchxw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhoulong.xyz/Article/details/gtroiqmxph.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhixingplan.top/Article/details/gtuuukozux.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gtvmpgvwro.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnopwunr.html

O. 并发与异步
来源：http://dali.nwbrower.top/Article/details/gtrvxfprsn.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtkafbyskh.html

[O01] 启动一个线程
来源：http://dali.feifeiyinyue.top/Article/details/gtfzhivvkd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinqigfzy.top/Article/details/gtalopfxuu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aizwys.cn/Article/details/gtkueyhxru.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hysaishi.cn/Article/details/gthfjdygmu.html

TS:   // 同 JS
来源：http://dali.nanxinkj.top/Article/details/gtwcicwbdi.html

Java: new Thread(() -> f()).start()
来源：http://dali.dashuyun.cn/Article/details/gtbyfgzbbz.html

Go:   go f()
来源：http://dali.kuanghao11.cn/Article/details/gtxjqgfkmf.html

Ruby: Thread.new { f }
来源：http://dali.hfpthk.cn/Article/details/gtdbyzhrwk.html

C#:   Task.Run(() => F());
来源：http://dali.hywenlv.cn/Article/details/gtytosllty.html

[O02] 使用线程池
来源：http://dali.redwolf501.top/Article/details/gtlgsrsosx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.316326.xyz/Article/details/gtgallxquq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.316326.xyz/Article/details/gtjsrewgvg.html

JS:   // worker_threads 线程池
来源：http://dali.fzhhl.top/Article/details/gthfspofls.html

TS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gtjtuerhcn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cqqwz.cn/Article/details/gtsmjmbeuq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.snrcjt.cn/Article/details/gtxfukapju.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hfpthk.cn/Article/details/gtienimewd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.0kj1m.cn/Article/details/gtzyaykiym.html

[O03] 加锁保护共享数据
来源：http://dali.xuanzx.com/Article/details/gtonwfwuho.html

Py:   with lock: shared += 1
来源：http://dali.xuanzx.com/Article/details/gtndimthxj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhongyouzk.top/Article/details/gtqlcxcdln.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.0kj1m.cn/Article/details/gtfcupoeqz.html

TS:   // 同 JS
来源：http://dali.mhx1999.top/Article/details/gtbxmogkjv.html

Java: synchronized (this) { shared++; }
来源：http://dali.ppjwa.cn/Article/details/gtkfkdaopf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xuanzx.com/Article/details/gtlwrwbwgw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj20258888.top/Article/details/gtuqlkpfwo.html

C#:   lock (gate) { shared++; }
来源：http://dali.bjfxy.top/Article/details/gtikiowcnz.html

[O04] 定义异步函数并等待
来源：http://dali.guannengcc.top/Article/details/gtpxakztta.html

Py:   async def f():⏎    await g()
来源：http://dali.yuxming.cn/Article/details/gtrrfbscgk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.bjfxy.top/Article/details/gtwrqjpdou.html

JS:   async function f() { await g(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzlzxfmei.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.vqdsnc.cn/Article/details/gttrzhmvdc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuxming.cn/Article/details/gtyqopcisx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinghuilouyu.cn/Article/details/gtehszxxpy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhixingplan.top/Article/details/gtbxwunmmp.html

C#:   async Task F() { await G(); }
来源：http://dali.yuxming.cn/Article/details/gtgzxwbstf.html

[O05] 并发执行并等待全部完成
来源：http://dali.ivvv.top/Article/details/gtirhrwrnm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.316326.xyz/Article/details/gttbwxcpjz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zdqjudy.top/Article/details/gtuazmnkoz.html

JS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtthfllpvl.html

TS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gtkyyykpkm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jianghu66.top/Article/details/gtbgumwahz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenjidiqi.icu/Article/details/gtrdsirtql.html

Ruby: threads.map(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gtdotvhter.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuetiantiany.cn/Article/details/gtvvgnjbbf.html

[O06] 使用进程池
来源：http://dali.kuanghao11.cn/Article/details/gtfriccteq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.mhx1999.top/Article/details/gtapqkdgdb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pycfn.com/Article/details/gteijiiccr.html

JS:   // child_process / cluster 模块
来源：http://dali.birdmap.top/Article/details/gtjjspgyls.html

TS:   // child_process / cluster 模块
来源：http://dali.smart0.xyz/Article/details/gtkbksqpsv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ydzc1.top/Article/details/gtilrcsvfi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.smart0.xyz/Article/details/gtrmdouwxf.html

Ruby: // fork 块
来源：http://dali.xuetiantiany.cn/Article/details/gtsmwresue.html

C#:   Parallel.For
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytlzropa.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtlvoqigbt.html

P. 常用工具函数
来源：http://dali.zhoulong.xyz/Article/details/gtixrjywlm.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtnxwalpls.html

[P01] 生成 UUID
来源：http://dali.pycfn.com/Article/details/gtbxplntbl.html

Py:   str(uuid.uuid4())
来源：http://dali.chenzaomai.com/Article/details/gtdkywswjz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.iojbl.cn/Article/details/gtyjaratei.html

JS:   crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gthulnlfbr.html

TS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtnxexwufo.html

Java: UUID.randomUUID().toString()
来源：http://dali.c1oappe.top/Article/details/gtdbbwwlna.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gotoacloud.top/Article/details/gtbsmafnyu.html

Ruby: SecureRandom.uuid
来源：http://dali.zhongyouzk.top/Article/details/gtlbtmlkfn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yvedp.cn/Article/details/gtcupwpmoa.html

[P02] MD5 / SHA256 摘要
来源：http://dali.birdmap.top/Article/details/gtvacypgna.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttinzgfnq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xuanzx.com/Article/details/gtcgcwzxtm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cashguo.top/Article/details/gtxswwehad.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.daria6918.cn/Article/details/gteclmcuor.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cheryme.top/Article/details/gtvsciezpj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jyoumei.cn/Article/details/gtadakmtno.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.kuanghao11.cn/Article/details/gtjbpmpxdc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgfzy.top/Article/details/gtqltdottu.html

[P03] 生成短随机字符串
来源：http://dali.daxiang520.top/Article/details/gthhrkgwxv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.andypj.xyz/Article/details/gtmqirvdou.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gogol.net.cn/Article/details/gtyehzbkgx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yongpay.top/Article/details/gtlzhwvvlv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gttfjlcfbr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nanxuanxn.top/Article/details/gtgvblkisp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sufxvd.cn/Article/details/gtedglapgj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jyoumei.cn/Article/details/gtcyltqhrj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ybcxt.top/Article/details/gtuypiqvtj.html

[P04] 求长度
来源：http://dali.ppjwa.cn/Article/details/gthqtkwpuu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.haohaochexian.top/Article/details/gtnuzipzzg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtgbvczkgs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenzaomai.com/Article/details/gthobbpkjd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gtzckpngew.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gzhubu.top/Article/details/gtdxmsuebv.html

Go:   len(arr);  len(m)
来源：http://dali.ehwqpu.com/Article/details/gtsoothyrs.html

Ruby: x.length;  x.size
来源：http://dali.chenjidiqi.icu/Article/details/gtgzsjiaxo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gtokwaceak.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sufxvd.cn/Article/details/gtvhzjdbuj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yuxming.cn/Article/details/gtiubcdwfe.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.bjfxy.top/Article/details/gtzhpchyoh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xylfe.cn/Article/details/gtqdsglvre.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tanke756.top/Article/details/gtnxjlujje.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdwbriar.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.iojbl.cn/Article/details/gtatakbcul.html

Ruby: a == b
来源：http://dali.haohaochexian.top/Article/details/gtpgicwcqq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cdnleiting.top/Article/details/gtpakodukk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zdqjudy.top/Article/details/gteegfacmy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jlsjyb.cn/Article/details/gtumrjwygy.html

PHP:  if (empty($x)) {}
来源：http://dali.snrcjt.cn/Article/details/gtvxtbwatm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guowangkeji.top/Article/details/gtibztylwg.html

TS:   if (x == null) {}
来源：http://dali.ydzc1.top/Article/details/gtdydwnmfv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gtvjpnjdve.html

Go:   if x == nil {}
来源：http://dali.bjfxy.top/Article/details/gtbtqztlii.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.0kj1m.cn/Article/details/gtfsgibwen.html

C#:   if (x is null) {}
来源：http://dali.guowangkeji.top/Article/details/gtpauctfoe.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangtech.top/Article/details/gtxptexmop.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ehwqpu.com/Article/details/gtnlnnvjan.html

PHP:  // 手写时间戳比较
来源：http://dali.aibaodan.cn/Article/details/gtxkfngcrb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gthupvuywj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gtwemcgmnk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xylfe.cn/Article/details/gtswhblhsy.html


<!-- 参考信息 -->