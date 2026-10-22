代发 wailian999

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gtxogkgvnv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.snrcjt.cn/Article/details/gtsdlgihdu.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtqktdzctb.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangshuangyany.cn/Article/details/gtdenbshoz.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtxgqwhkgw.html

[M01] 读取命令行参数
来源：http://dali.fzhhl.top/Article/details/gtwksetuug.html

Py:   sys.argv[1:]
来源：http://dali.hysaishi.cn/Article/details/gtitmjiqcl.html

PHP:  $argv;  $argc;
来源：http://dali.tian-w.cn/Article/details/gtoosftywb.html

JS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gtewktrovl.html

TS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtxmfygycf.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gtszaftsri.html

Go:   os.Args[1:]
来源：http://dali.sweek.top/Article/details/gtirdwzxpb.html

Ruby: ARGV
来源：http://dali.yongpay.top/Article/details/gtjkinuokf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gtyaivrnso.html

[M02] 读取环境变量
来源：http://dali.havefunace.top/Article/details/gtsqpotpch.html

Py:   os.environ.get("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtivwahsae.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gtnvqoqjxl.html

JS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gtmxcgyqct.html

TS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqfjuare.html

Java: System.getenv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtdmoalgrq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.meibo888.top/Article/details/gtgbkjjtwf.html

Ruby: ENV["HOME"]
来源：http://dali.wangshuangyany.cn/Article/details/gtwjkfzijc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pycfn.com/Article/details/gtualiaxlm.html

[M03] 执行外部命令
来源：http://dali.meibo888.top/Article/details/gtsxjvllkp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgufenzy.top/Article/details/gtmafhzzzb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnqzz.top/Article/details/gtbnnhvgur.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gtannrsyig.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtwvanthsn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.feifeiyinyue.top/Article/details/gtjrfnidbr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ppjwa.cn/Article/details/gtzeqgxtoa.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guannengcc.top/Article/details/gtujbttkzw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tanke756.top/Article/details/gtdkcjkgql.html

[M04] 获取当前工作目录
来源：http://dali.yueranfly.top/Article/details/gtjpcydthu.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gtymcozlri.html

PHP:  getcwd();
来源：http://dali.pycfn.com/Article/details/gtjqewsqgh.html

JS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gtankxsjdp.html

TS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gtvlxnsubr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.vqdsnc.cn/Article/details/gthvcqceeo.html

Go:   os.Getwd()
来源：http://dali.ehwqpu.com/Article/details/gtmqkubith.html

Ruby: Dir.pwd
来源：http://dali.hfpthk.cn/Article/details/gtxmgsrktk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuanzhike.top/Article/details/gtztjixmqm.html

[M05] 设置退出码
来源：http://dali.hnxiangtu.top/Article/details/gtknuxgjgs.html

Py:   sys.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgvrrvws.html

PHP:  exit(1);
来源：http://dali.nanxinkj.top/Article/details/gtdfczbyxp.html

JS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtwjgkcbpm.html

TS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gtuarprsrs.html

Java: System.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtriwjbhvi.html

Go:   os.Exit(1)
来源：http://dali.xziqi.cn/Article/details/gtzvmfwlbg.html

Ruby: exit 1
来源：http://dali.guowangkeji.top/Article/details/gtmbnaplpz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sysykeji.top/Article/details/gtzmtnadgo.html

[M06] 向标准错误输出
来源：http://dali.316326.xyz/Article/details/gtstzggdnd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.guannengcc.top/Article/details/gtzwufqgvr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xinyue.icu/Article/details/gtybpxyvrk.html

JS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gtqholdxkq.html

TS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gtrqjvihfr.html

Java: System.err.println("err")
来源：http://dali.hywenlv.cn/Article/details/gtktmiaunc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.snrcjt.cn/Article/details/gtqahhueek.html

Ruby: warn "err"
来源：http://dali.yonumen.top/Article/details/gtwlbhhoyn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangdashe.top/Article/details/gtyhrlqcqt.html

[M07] 判断是否为主入口
来源：http://dali.redwolf501.top/Article/details/gthpwepiwe.html

Py:   if __name__ == "__main__":
来源：http://dali.sufxvd.cn/Article/details/gtmcwnvkiy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.svipenyu.cn/Article/details/gtlxzqhwue.html

JS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gthmjvpnxi.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gtdbjhngxa.html

Java: public static void main(String[] args)
来源：http://dali.jinqigfzy.top/Article/details/gtdeipynxc.html

Go:   func main()
来源：http://dali.jqgfzy.top/Article/details/gtnogwfjbj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aizwys.cn/Article/details/gthmeqtlfd.html

C#:   static void Main(string[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gtqplwtkmn.html

[M08] 获取系统与运行时信息
来源：http://dali.haohaochexian.top/Article/details/gttwdblezw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258.top/Article/details/gtcuofgkxv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxinkj.top/Article/details/gtexwagzbr.html

JS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gtjzfwtxie.html

TS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gtadibhueb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhixingplan.top/Article/details/gtagovugdb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xinyue.icu/Article/details/gtpbqlosiv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibxmoodl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhiwuduotai.top/Article/details/gtdivwitml.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtstghvein.html

N. 数据结构与算法
来源：http://dali.iojbl.cn/Article/details/gtzyshqgjy.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtykchiaho.html

[N01] 二分查找（有序数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwuofjii.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtscwdxwnc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fzhhl.top/Article/details/gticcelvxr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gtkfjgxmex.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtezeecxfh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtqoblnrkr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtnlzqetdz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuxming.cn/Article/details/gtfnabtdxw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtytaghwcs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgfzy.top/Article/details/gtvemeokmp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gthaolyzvy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.iojbl.cn/Article/details/gtewndtkuo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gtqcshnwzl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gthvilenrn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tanke756.top/Article/details/gtjsnhqvcx.html

Go:   slices.Sort(arr)
来源：http://dali.zycfv.cn/Article/details/gtknofahgf.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gtveotpdqk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangshuangyany.cn/Article/details/gtenebtvkj.html

[N03] 快速排序（分治示例）
来源：http://dali.gaohongyu789.top/Article/details/gtfnecvioi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinqigfzy.top/Article/details/gtsvxyagfl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hnxiangtu.top/Article/details/gtazmeupoe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gtxhdgvbrk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuanzhike.top/Article/details/gthrgobkgr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zdqjudy.top/Article/details/gtdibinvdo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tianlin.xyz/Article/details/gtxgnygftf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.c1oappe.top/Article/details/gtzofxvstv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxacagjqr.html

[N04] 斐波那契数列
来源：http://dali.yj20258.top/Article/details/gtfneugjpt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gtdpdkqtzx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jianghu66.top/Article/details/gtdtptqpzz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gthwlppknc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gtxyovdnyu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.iojbl.cn/Article/details/gtapcsapgs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.9152youxi.cn/Article/details/gtkazvsfkg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ehwqpu.com/Article/details/gtbnpfjvxj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtkvstmjwv.html

[N05] 最大公约数
来源：http://dali.zdqjudy.top/Article/details/gtrentomgn.html

Py:   math.gcd(a, b)
来源：http://dali.nwbrower.top/Article/details/gtijntbjpb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtwtvofgou.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gtlgzppnvm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxinkj.top/Article/details/gtcjsfhurr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sysykeji.top/Article/details/gtzylkxgrl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuxming.cn/Article/details/gtqdwslnri.html

Ruby: a.gcd(b)
来源：http://dali.chenzaomai.com/Article/details/gtlbqoktcx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.haohaochexian.top/Article/details/gtdoodrxck.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gtuhaphyzx.html

Py:   s == s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gtmovtrckl.html

PHP:  $s === strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gtjyqwpdom.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtdredzowl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtgmwfhclk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yongpay.top/Article/details/gtbsdkmnbb.html

Go:   // 双指针从两端比较
来源：http://dali.smart0.xyz/Article/details/gtdjcdbwdf.html

Ruby: s == s.reverse
来源：http://dali.ppjwa.cn/Article/details/gtrshqqfmo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zdqjudy.top/Article/details/gtqjfixiwo.html

[N07] 两数之和（返回下标）
来源：http://dali.haohaochexian.top/Article/details/gtjqmzuqpx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xuanzx.com/Article/details/gtjhemvhmc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gaohongyu789.top/Article/details/gtfobopsft.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangshuangyany.cn/Article/details/gtjrtdvwzs.html

TS:   // 手写 Map<string, number>
来源：http://dali.yangfankeji.com/Article/details/gtceggrjxx.html

Java: // 手写 HashMap
来源：http://dali.jqgfzy.top/Article/details/gtxytjyjgj.html

Go:   // 手写 map[int]int
来源：http://dali.smart0.xyz/Article/details/gtaefdrida.html

Ruby: // 手写 Hash
来源：http://dali.smart0.xyz/Article/details/gtaotqvtjw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xziqi.cn/Article/details/gtvcsgeooy.html

[N08] 生成全排列
来源：http://dali.zhengqikj.top/Article/details/gtmwqxolyf.html

Py:   itertools.permutations(arr)
来源：http://dali.ivvv.top/Article/details/gtirrgndmb.html

PHP:  // 手写递归交换
来源：http://dali.cashguo.top/Article/details/gtxvavwftf.html

JS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtstimgufp.html

TS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglffuxqc.html

Java: // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtvfbbftfw.html

Go:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gthlsfirmv.html

Ruby: arr.permutation.to_a
来源：http://dali.hfpthk.cn/Article/details/gtbvarwyrt.html

C#:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtzmespfrb.html

[N09] 栈与队列
来源：http://dali.haohaochexian.top/Article/details/gtacnbvbum.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.316326.xyz/Article/details/gtsdqndskt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gtpwtedhdz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwifvburp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fzhhl.top/Article/details/gtpemcocqt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gtmvxpylzb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gaohongyu789.top/Article/details/gtearekkeb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gtkmbtdhtp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj202588.top/Article/details/gtyprogbem.html

[N10] 链表节点定义
来源：http://dali.tanke756.top/Article/details/gtevhhtiak.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nanxinkj.top/Article/details/gtlcipuoxo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gaohongyu789.top/Article/details/gtcqnszfxb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.iojbl.cn/Article/details/gtdxracfsb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.iojbl.cn/Article/details/gtxqudhpao.html

Java: class Node { int v; Node next; }
来源：http://dali.gzhubu.top/Article/details/gthjauatnj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.birdmap.top/Article/details/gtnnzcsywz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xuetiantiany.cn/Article/details/gtbdrapwbn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aibaodan.cn/Article/details/gtghwexwrc.html

[N11] 二叉树中序遍历
来源：http://dali.ehwqpu.com/Article/details/gtxbqxwcok.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cashguo.top/Article/details/gtuzscqyzo.html

PHP:  // 手写递归函数
来源：http://dali.daria6918.cn/Article/details/gtzejzkfay.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gtswgembyv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gtywfsicoz.html

Java: // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtyqgvqgtk.html

Go:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gtqwjqzaxq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gaohongyu789.top/Article/details/gtpwnmssiz.html

C#:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtcupgbfrk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cheryme.top/Article/details/gtcggymmfj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnjfifqo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ybcxt.top/Article/details/gtwcvtwzyq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtioyzncva.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gtcoodbczb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gtckbahnzm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yongpay.top/Article/details/gtudbhjrcm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtwvorvrot.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gtdzdcdnso.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtmbilabxx.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnkwcica.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtisrrzjns.html

[O01] 启动一个线程
来源：http://dali.xuanzx.com/Article/details/gtqyinfwbn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zdqjudy.top/Article/details/gtpiyoctli.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.havefunace.top/Article/details/gtlsslxypl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.fengsongda.top/Article/details/gtgihilgrw.html

TS:   // 同 JS
来源：http://dali.yonumen.top/Article/details/gthubyltxb.html

Java: new Thread(() -> f()).start()
来源：http://dali.zycfv.cn/Article/details/gtrshiehpe.html

Go:   go f()
来源：http://dali.316326.xyz/Article/details/gtpshyhhvs.html

Ruby: Thread.new { f }
来源：http://dali.guowangkeji.top/Article/details/gtnpicckac.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258.top/Article/details/gtvmuppksy.html

[O02] 使用线程池
来源：http://dali.316326.xyz/Article/details/gttaxfuvjy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gtxbjqdtxc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sxryk.cn/Article/details/gtnqxqpulh.html

JS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gtiyyhnnyi.html

TS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gtyybomdar.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nwbrower.top/Article/details/gtygttgwrs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shanyushiyangtech.top/Article/details/gttvmuzvzf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenlongwang.top/Article/details/gtlodxkqbf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yangfankeji.com/Article/details/gtsfywqazp.html

[O03] 加锁保护共享数据
来源：http://dali.pengpengdd.cyou/Article/details/gtilprahop.html

Py:   with lock: shared += 1
来源：http://dali.sxryk.cn/Article/details/gtthusagjn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nanxuanxn.top/Article/details/gtuopugabc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pycfn.com/Article/details/gtfmojucge.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gtdxtrykck.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigfzy.top/Article/details/gttgueweiu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.meibo888.top/Article/details/gtbezixcwu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sxryk.cn/Article/details/gtaaejmsge.html

C#:   lock (gate) { shared++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrzakkbpr.html

[O04] 定义异步函数并等待
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmswjjpc.html

Py:   async def f():⏎    await g()
来源：http://dali.hywenlv.cn/Article/details/gtvdsqyhcu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jianghu66.top/Article/details/gtborizppn.html

JS:   async function f() { await g(); }
来源：http://dali.jyoumei.cn/Article/details/gtjnyfwrww.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gtgchlxotl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nwbrower.top/Article/details/gtfuirwxok.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hysaishi.cn/Article/details/gtcgtgumnf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tanke756.top/Article/details/gtgdjxdjlq.html

C#:   async Task F() { await G(); }
来源：http://dali.chenzaomai.com/Article/details/gtmaxprhtj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zdqjudy.top/Article/details/gtjotpreck.html

Py:   asyncio.gather(*tasks)
来源：http://dali.c1oappe.top/Article/details/gtypqamjug.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj20258888.top/Article/details/gtzftsedsu.html

JS:   await Promise.all(tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gtiqncdzuu.html

TS:   await Promise.all(tasks)
来源：http://dali.yuxming.cn/Article/details/gtxweqaoxv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuxming.cn/Article/details/gttapnngpc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daria6918.cn/Article/details/gtwlsayxjl.html

Ruby: threads.map(&:join)
来源：http://dali.nwbrower.top/Article/details/gtyufkinxy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sweek.top/Article/details/gtobfmsmuj.html

[O06] 使用进程池
来源：http://dali.nanxuanxn.top/Article/details/gtfnlgdich.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.guannengcc.top/Article/details/gtpqiptxav.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sufxvd.cn/Article/details/gtiijnpmod.html

JS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gthscbhccw.html

TS:   // child_process / cluster 模块
来源：http://dali.shangyingyoupin.top/Article/details/gttfqdykfs.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjygmdfk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sysykeji.top/Article/details/gthwnnupqg.html

Ruby: // fork 块
来源：http://dali.zhixingplan.top/Article/details/gtffhouvlr.html

C#:   Parallel.For
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmqfryrx.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtzrkhsjsw.html

P. 常用工具函数
来源：http://dali.kuanghao11.cn/Article/details/gtxbrbtrfo.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtionfdzmi.html

[P01] 生成 UUID
来源：http://dali.feifeiyinyue.top/Article/details/gtqtobpizl.html

Py:   str(uuid.uuid4())
来源：http://dali.hnqzz.top/Article/details/gttmzavaxc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jianghu66.top/Article/details/gtdgammvzg.html

JS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gtswhulzhk.html

TS:   crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gtzvtridgy.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuxming.cn/Article/details/gtlopyhylg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yvedp.cn/Article/details/gthtbfzpez.html

Ruby: SecureRandom.uuid
来源：http://dali.xziqi.cn/Article/details/gtdchebvyq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigfzy.top/Article/details/gtjnuoozus.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigufen.top/Article/details/gtqzaaiipn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.birdmap.top/Article/details/gtmpkrguvj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj202588.top/Article/details/gtlkqklwyt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xylfe.cn/Article/details/gtkkhshuss.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jlsjyb.cn/Article/details/gtcuycxnru.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gtmabwfnau.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenlongwang.top/Article/details/gtdykulnev.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhoulong.xyz/Article/details/gtbnwkviip.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yangfankeji.com/Article/details/gtnaunqsao.html

[P03] 生成短随机字符串
来源：http://dali.daria6918.cn/Article/details/gtqhcoiqpd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangshuangyany.cn/Article/details/gtecdsojtj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cucudq.cn/Article/details/gthvikospx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gtrykprlhq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gtrhjkvvru.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj20258.top/Article/details/gtygwknfbd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xuanzx.com/Article/details/gtawrmlqsk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.c1oappe.top/Article/details/gttfazpjkk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jlsjyb.cn/Article/details/gtwbujwpdo.html

[P04] 求长度
来源：http://dali.havefunace.top/Article/details/gtaeoxoqpp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.iojbl.cn/Article/details/gttzwfkvnl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtocswcmez.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sxryk.cn/Article/details/gtpvhfmbky.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hongshengwenyu.top/Article/details/gtkunpfdfl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yueranfly.top/Article/details/gtogvlozzq.html

Go:   len(arr);  len(m)
来源：http://dali.hfpthk.cn/Article/details/gtnoqufnoo.html

Ruby: x.length;  x.size
来源：http://dali.yuxming.cn/Article/details/gtllceqrfo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.aizwys.cn/Article/details/gtvjhnohkg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hywenlv.cn/Article/details/gtxcyxrcxu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hnxiangtu.top/Article/details/gtwiglfblo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenjidiqi.icu/Article/details/gttdxkswue.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenlongwang.top/Article/details/gtrhjfwupz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmbxdxub.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hywenlv.cn/Article/details/gtwnzogqtw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aizwys.cn/Article/details/gtpyljmhip.html

Ruby: a == b
来源：http://dali.yuxming.cn/Article/details/gtxvyclcww.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuanzhike.top/Article/details/gtvpwwrgme.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.dashuyun.cn/Article/details/gtkccozdzf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cqqwz.cn/Article/details/gtylhuggjf.html

PHP:  if (empty($x)) {}
来源：http://dali.chenlongwang.top/Article/details/gthrmxvjqe.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlbhgldx.html

TS:   if (x == null) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnderezc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gtxigfxurb.html

Go:   if x == nil {}
来源：http://dali.hywenlv.cn/Article/details/gtshltjojm.html


<!-- 参考信息 -->