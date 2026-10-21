代发 wailian999

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtwbpzdzof.html

[M01] 读取命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gteqiksumn.html

Py:   sys.argv[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gtjsdicxvx.html

PHP:  $argv;  $argc;
来源：http://dali.yueranfly.top/Article/details/gtrtpokeid.html

JS:   process.argv.slice(2)
来源：http://dali.shzxlz.cn/Article/details/gtvrhxftwb.html

TS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gtyinoafyd.html

Java: args 数组（main 方法参数）
来源：http://dali.pycfn.com/Article/details/gtrkuhzjoh.html

Go:   os.Args[1:]
来源：http://dali.zhongyouzk.top/Article/details/gttwonlnrq.html

Ruby: ARGV
来源：http://dali.guannengcc.top/Article/details/gtqdezqnlh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtvlfowoet.html

[M02] 读取环境变量
来源：http://dali.hammf.cn/Article/details/gtafsqhuxv.html

Py:   os.environ.get("HOME")
来源：http://dali.sweek.top/Article/details/gtghpluwgx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gtqkkbfmpr.html

JS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gteifuiuey.html

TS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gtqrdxyjqm.html

Java: System.getenv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtlzdnemgs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangdashe.top/Article/details/gtitjuxjsh.html

Ruby: ENV["HOME"]
来源：http://dali.fengsongda.top/Article/details/gtdudrqhdm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.iojbl.cn/Article/details/gtvwadnqxc.html

[M03] 执行外部命令
来源：http://dali.nwbrower.top/Article/details/gtgauikwbc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guowangkeji.top/Article/details/gtltoxkysg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.9152youxi.cn/Article/details/gtqmuhckyw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gtiznqjqmx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gtisigrsjp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ybcxt.top/Article/details/gtexmgxljg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sufxvd.cn/Article/details/gtckqiqmcz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ppjwa.cn/Article/details/gtzlwfiqge.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daxiang520.top/Article/details/gtsrzixbgp.html

[M04] 获取当前工作目录
来源：http://dali.c1oappe.top/Article/details/gtaaxvotji.html

Py:   os.getcwd()
来源：http://dali.gzhubu.top/Article/details/gtfaahorfz.html

PHP:  getcwd();
来源：http://dali.zdqjudy.top/Article/details/gtwmjfopdh.html

JS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtorhfevdb.html

TS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gtazcjuzzi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tanke756.top/Article/details/gtwjfoibej.html

Go:   os.Getwd()
来源：http://dali.vqdsnc.cn/Article/details/gtabahtkcz.html

Ruby: Dir.pwd
来源：http://dali.cqqwz.cn/Article/details/gtklouuzay.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqasdmeu.html

[M05] 设置退出码
来源：http://dali.mhx1999.top/Article/details/gtaxkmsdfv.html

Py:   sys.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtsrikcrsx.html

PHP:  exit(1);
来源：http://dali.hysaishi.cn/Article/details/gtnwfkqhkp.html

JS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtkbfkphyw.html

TS:   process.exit(1)
来源：http://dali.ivvv.top/Article/details/gtyfqukoog.html

Java: System.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtcnxebfge.html

Go:   os.Exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtlygbnzia.html

Ruby: exit 1
来源：http://dali.cashguo.top/Article/details/gtjxfcafqx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258888.top/Article/details/gtsmujqllu.html

[M06] 向标准错误输出
来源：http://dali.hongshengwenyu.top/Article/details/gtbkijfoal.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daria6918.cn/Article/details/gthfnddzjp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangdashe.top/Article/details/gtmdlazvcm.html

JS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gtyeqkdlpu.html

TS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gtphynvoxq.html

Java: System.err.println("err")
来源：http://dali.redwolf501.top/Article/details/gtskjwdgaw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.redwolf501.top/Article/details/gtwytvkjpz.html

Ruby: warn "err"
来源：http://dali.jinqigfzy.top/Article/details/gtlavqmhhj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gotoacloud.top/Article/details/gtfhkhdpxa.html

[M07] 判断是否为主入口
来源：http://dali.ivvv.top/Article/details/gtacqkzkye.html

Py:   if __name__ == "__main__":
来源：http://dali.pengpengdd.cyou/Article/details/gtdebqiheo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258888.top/Article/details/gtvlswzpsa.html

JS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gtalrdedob.html

TS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtkqbrlvfp.html

Java: public static void main(String[] args)
来源：http://dali.daria6918.cn/Article/details/gtzhhtbmfq.html

Go:   func main()
来源：http://dali.iojbl.cn/Article/details/gtwizymjaf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dashuyun.cn/Article/details/gtravzijhs.html

C#:   static void Main(string[] args)
来源：http://dali.yvedp.cn/Article/details/gttoyscijp.html

[M08] 获取系统与运行时信息
来源：http://dali.xuetiantiany.cn/Article/details/gtlzwouckl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gotoacloud.top/Article/details/gtlcvkliai.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhiwuduotai.top/Article/details/gtfgxxlrfb.html

JS:   process.platform;  process.version
来源：http://dali.c1oappe.top/Article/details/gtwiathskh.html

TS:   process.platform;  process.version
来源：http://dali.ivvv.top/Article/details/gtjjjlherj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jianghu66.top/Article/details/gtwowejugv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuxming.cn/Article/details/gtjpodnczx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyueexhyt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fengsongda.top/Article/details/gtsbunnebm.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtvbfpkjpb.html

N. 数据结构与算法
来源：http://dali.yangfankeji.com/Article/details/gtkwomcajl.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtkshbwonh.html

[N01] 二分查找（有序数组）
来源：http://dali.zycfv.cn/Article/details/gtavuuniyz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtejlfxtoh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtpefuizbz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gteqdeqcpy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gtlofanqnc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtqokmstgf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cheryme.top/Article/details/gtolybpafv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nwbrower.top/Article/details/gtzajiqrvu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtdjzzmwag.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuanzhike.top/Article/details/gtthwcqnes.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigufen.top/Article/details/gtbusmryhz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dashuyun.cn/Article/details/gtkkowicar.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gttlgxfmep.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gtxxqtyzaq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxinkj.top/Article/details/gtbfcxckuc.html

Go:   slices.Sort(arr)
来源：http://dali.jyoumei.cn/Article/details/gtvduwugxs.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gtfnjhwhhs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dianchejie.cn/Article/details/gtyqdygewo.html

[N03] 快速排序（分治示例）
来源：http://dali.yvedp.cn/Article/details/gtvfuaztvt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ybcxt.top/Article/details/gtvfogvoav.html

PHP:  // 递归实现，或用 usort
来源：http://dali.birdmap.top/Article/details/gtvmdnxbbq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gaohongyu789.top/Article/details/gtpcrefzqx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gtgcvlphgz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zycfv.cn/Article/details/gtiuahozgr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jiagoushi.top/Article/details/gtnmwvetcg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daria6918.cn/Article/details/gtrdpgeyaj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tanke756.top/Article/details/gtnngjaqcr.html

[N04] 斐波那契数列
来源：http://dali.ydzc1.top/Article/details/gtoodvwhxx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gtbzeiitru.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daria6918.cn/Article/details/gtlizhrjwd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtcnpfzdoc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gtlsowgldj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gtotgeakuh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jqgfzy.top/Article/details/gtmvmzxdoa.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gtifigubvm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gtjoqnwzmb.html

[N05] 最大公约数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoektazhb.html

Py:   math.gcd(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtulgeapfe.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xinyue.icu/Article/details/gtwuutltwl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtglkyfocc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtbysexzxf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigufen.top/Article/details/gtsbzdcbug.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shzxlz.cn/Article/details/gtburaastx.html

Ruby: a.gcd(b)
来源：http://dali.vqdsnc.cn/Article/details/gtijzuaamd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jiagoushi.top/Article/details/gtyzcvnfrk.html

[N06] 判断回文字符串
来源：http://dali.sxryk.cn/Article/details/gtputsjqho.html

Py:   s == s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gttuyyngyx.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gtnoupauou.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtbajxflan.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtobehmzxb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigufen.top/Article/details/gtgbzmwouy.html

Go:   // 双指针从两端比较
来源：http://dali.cheryme.top/Article/details/gtvfejjvhf.html

Ruby: s == s.reverse
来源：http://dali.snrcjt.cn/Article/details/gtwcjbcbmd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gtmwrwdbld.html

[N07] 两数之和（返回下标）
来源：http://dali.birdmap.top/Article/details/gtsrgliknm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aibaodan.cn/Article/details/gtskmevrku.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangtech.top/Article/details/gttsejntnz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yueranfly.top/Article/details/gtqwptlshr.html

TS:   // 手写 Map<string, number>
来源：http://dali.daxiang520.top/Article/details/gtqpektwwl.html

Java: // 手写 HashMap
来源：http://dali.zhengqikj.top/Article/details/gtmjdfnhat.html

Go:   // 手写 map[int]int
来源：http://dali.yuxming.cn/Article/details/gtoplkhaar.html

Ruby: // 手写 Hash
来源：http://dali.jqgfzy.top/Article/details/gtkyqyidbw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.birdmap.top/Article/details/gtxtvjhjhw.html

[N08] 生成全排列
来源：http://dali.pengpengdd.cyou/Article/details/gthrfsxlii.html

Py:   itertools.permutations(arr)
来源：http://dali.sxryk.cn/Article/details/gtvkvuguiz.html

PHP:  // 手写递归交换
来源：http://dali.c1oappe.top/Article/details/gtmgwuhubg.html

JS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtqyhtmpsv.html

TS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtrhrhxbfk.html

Java: // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtpuqtmpjh.html

Go:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtdlqdmkub.html

Ruby: arr.permutation.to_a
来源：http://dali.zdqjudy.top/Article/details/gtjcrpyhse.html

C#:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtmujlourr.html

[N09] 栈与队列
来源：http://dali.svipenyu.cn/Article/details/gtdtnxhbby.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sweek.top/Article/details/gtjwvuqrom.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtxslgzeds.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gttaqyulcu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fzhhl.top/Article/details/gtecfelove.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gtjcnxxrbf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fzhhl.top/Article/details/gttbdkeqhd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gtnxapobuj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hammf.cn/Article/details/gtkfpyavbj.html

[N10] 链表节点定义
来源：http://dali.cashguo.top/Article/details/gttxdynmat.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cqqwz.cn/Article/details/gtcogykale.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnxiangtu.top/Article/details/gtngzyzwpq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ivvv.top/Article/details/gtnffsqgel.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gotoacloud.top/Article/details/gtpgkjoggi.html

Java: class Node { int v; Node next; }
来源：http://dali.ivvv.top/Article/details/gtoxlqaifs.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevarygqa.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sxryk.cn/Article/details/gtoednyonw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shangyingyoupin.top/Article/details/gtsdungmpw.html

[N11] 二叉树中序遍历
来源：http://dali.jlsjyb.cn/Article/details/gtztvosdub.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.0kj1m.cn/Article/details/gtpuwhapfk.html

PHP:  // 手写递归函数
来源：http://dali.cdnleiting.top/Article/details/gtkjwbyugk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shuidangran.top/Article/details/gtxhwilhbk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtguirnrwd.html

Java: // 手写递归
来源：http://dali.pycfn.com/Article/details/gtsnynkkdr.html

Go:   // 手写递归
来源：http://dali.tian-w.cn/Article/details/gtnpjxeefq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.daria6918.cn/Article/details/gtfhhmzuxm.html

C#:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtivzjnyui.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hysaishi.cn/Article/details/gtyssmzuvy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.pengpengdd.cyou/Article/details/gtscnftasp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenzaomai.com/Article/details/gtcohioukp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gtxbwkbvoz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gtmwblovcu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gtpvrymttg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xuanzx.com/Article/details/gtrkareuva.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gotoacloud.top/Article/details/gtjaguskum.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dashuyun.cn/Article/details/gtrxfonkjb.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtasixsqyf.html

O. 并发与异步
来源：http://dali.shuidangran.top/Article/details/gtjntlgjgl.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfqveeco.html

[O01] 启动一个线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdjdcflz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yongpay.top/Article/details/gtusuutxqk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hongshengwenyu.top/Article/details/gtnhshjasp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.9152youxi.cn/Article/details/gtvuywfjtq.html

TS:   // 同 JS
来源：http://dali.ivvv.top/Article/details/gtydqhvnuo.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgufenzy.top/Article/details/gtjfuaghlc.html

Go:   go f()
来源：http://dali.sysykeji.top/Article/details/gtormzndmk.html

Ruby: Thread.new { f }
来源：http://dali.yuanzhike.top/Article/details/gtwuvzgwst.html

C#:   Task.Run(() => F());
来源：http://dali.zhixingplan.top/Article/details/gtgdhabdes.html

[O02] 使用线程池
来源：http://dali.mhx1999.top/Article/details/gtvzjmwgen.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.dashuyun.cn/Article/details/gtgwlextrs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tianlin.xyz/Article/details/gtfgxthgcm.html

JS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gtggsljqgn.html

TS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gtuaomwahp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ybcxt.top/Article/details/gtinzpnkux.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tanke756.top/Article/details/gtxouerlnu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tian-w.cn/Article/details/gttzjsvdgq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yongpay.top/Article/details/gtrvqwqrpd.html

[O03] 加锁保护共享数据
来源：http://dali.hysaishi.cn/Article/details/gtxnrrpruk.html

Py:   with lock: shared += 1
来源：http://dali.zdqjudy.top/Article/details/gtyzeqhvrz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tian-w.cn/Article/details/gtuehaejji.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.meibo888.top/Article/details/gtkhbibioi.html

TS:   // 同 JS
来源：http://dali.ehwqpu.com/Article/details/gtdnlfckmf.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj20258.top/Article/details/gtlrkyanfm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.mhx1999.top/Article/details/gtsnifdmqa.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hysaishi.cn/Article/details/gtbntdsaei.html

C#:   lock (gate) { shared++; }
来源：http://dali.jiagoushi.top/Article/details/gtqjkoinql.html

[O04] 定义异步函数并等待
来源：http://dali.ppjwa.cn/Article/details/gthklqpczf.html

Py:   async def f():⏎    await g()
来源：http://dali.quarkkingdee.top/Article/details/gtvpznuhhy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.0kj1m.cn/Article/details/gtemmamraz.html

JS:   async function f() { await g(); }
来源：http://dali.nanxuanxn.top/Article/details/gtirrjhalr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gtavzrfgud.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ehwqpu.com/Article/details/gtlkkbroki.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.quarkkingdee.top/Article/details/gtwbaxabpt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.c1oappe.top/Article/details/gtlgsalklh.html

C#:   async Task F() { await G(); }
来源：http://dali.yueranfly.top/Article/details/gtnpbzoluq.html

[O05] 并发执行并等待全部完成
来源：http://dali.ivvv.top/Article/details/gtsdvbiqcm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.haohaochexian.top/Article/details/gtoiicyjyo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yangfankeji.com/Article/details/gtnhgzrfsn.html

JS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtkbsicvde.html

TS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gtphzowwcj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yongpay.top/Article/details/gtuvxomkmo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guannengcc.top/Article/details/gtvefzlpnz.html

Ruby: threads.map(&:join)
来源：http://dali.gotoacloud.top/Article/details/gtrrkgphye.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hfpthk.cn/Article/details/gtayhmxpjc.html

[O06] 使用进程池
来源：http://dali.yj20258888.top/Article/details/gtjqcormyk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.aizwys.cn/Article/details/gtpzjuyfoy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yanxiufei.cn/Article/details/gttadclfnx.html

JS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gtvwdynmdo.html

TS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gtckslcttl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjrgqlwo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinqigufen.top/Article/details/gtiedjhxgv.html

Ruby: // fork 块
来源：http://dali.jqgfzy.top/Article/details/gtxjxpharq.html

C#:   Parallel.For
来源：http://dali.yongpay.top/Article/details/gtzrseofcf.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtdgqgzjzu.html

P. 常用工具函数
来源：http://dali.wangdashe.top/Article/details/gtmdvcnfmx.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtbuxitsxd.html

[P01] 生成 UUID
来源：http://dali.havefunace.top/Article/details/gtzghatwyd.html

Py:   str(uuid.uuid4())
来源：http://dali.cdnleiting.top/Article/details/gtdpvvwthn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhoulong.xyz/Article/details/gtwqmseajl.html

JS:   crypto.randomUUID()
来源：http://dali.nanxuanxn.top/Article/details/gtzlumztat.html

TS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gtuiagjscu.html

Java: UUID.randomUUID().toString()
来源：http://dali.shuidangran.top/Article/details/gtmtunplbg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhixingplan.top/Article/details/gtbrshlfir.html

Ruby: SecureRandom.uuid
来源：http://dali.xuanzx.com/Article/details/gttdmbtiqc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yueranfly.top/Article/details/gteiuonqzs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenzaomai.com/Article/details/gtqkuyedgg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shuidangran.top/Article/details/gtnuwhrugy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cdnleiting.top/Article/details/gtcvzuiwyq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenlongwang.top/Article/details/gtgsurpfby.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhongyouzk.top/Article/details/gteflluflm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cucudq.cn/Article/details/gtshnoregr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cucudq.cn/Article/details/gtyjjnendg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuxming.cn/Article/details/gtseietswb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.0kj1m.cn/Article/details/gtsokcgtsn.html

[P03] 生成短随机字符串
来源：http://dali.hywenlv.cn/Article/details/gtbovkrstk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gotoacloud.top/Article/details/gtwkmogxbt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nanxinkj.top/Article/details/gtnrsbxgzd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gtdwbomifs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gtonpyddtf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nwbrower.top/Article/details/gtyvdbiuee.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cdnleiting.top/Article/details/gtcgakgvyh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jqgfzy.top/Article/details/gtthevlump.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.quarkkingdee.top/Article/details/gtalaijsee.html

[P04] 求长度
来源：http://dali.9152youxi.cn/Article/details/gtrbvbpwvv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258.top/Article/details/gtljamchca.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtfebqyrvm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gtyyzcvdvb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gtxnanvqlo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xylfe.cn/Article/details/gtrvcafhvs.html

Go:   len(arr);  len(m)
来源：http://dali.havefunace.top/Article/details/gtfmzjdgme.html

Ruby: x.length;  x.size
来源：http://dali.zhiwuduotai.top/Article/details/gthrhfkdse.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cashguo.top/Article/details/gtvetdxeqb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nwbrower.top/Article/details/gtneknwpgu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhongyouzk.top/Article/details/gtadihffaf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.kuanghao11.cn/Article/details/gtwihikmfr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xziqi.cn/Article/details/gtokydyeho.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gticnttmtu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dianchejie.cn/Article/details/gttzyosimf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gogol.net.cn/Article/details/gtqhngqqzl.html

Ruby: a == b
来源：http://dali.yuanzhike.top/Article/details/gtvpvuzxey.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.iojbl.cn/Article/details/gtyrzbpppd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzipcoqs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.andypj.xyz/Article/details/gthrejciiq.html

PHP:  if (empty($x)) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfdqejfm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gaohongyu789.top/Article/details/gttuzvjcpi.html

TS:   if (x == null) {}
来源：http://dali.yj20258888.top/Article/details/gtgtvfejwe.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gtukdnwfko.html

Go:   if x == nil {}
来源：http://dali.xinyue.icu/Article/details/gtvognzawa.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jqgfzy.top/Article/details/gthqclhmfi.html

C#:   if (x is null) {}
来源：http://dali.guannengcc.top/Article/details/gtqoswxeog.html

[P07] 防抖与节流
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosjbhptk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangshuangyany.cn/Article/details/gtvwluoiwv.html


<!-- 参考信息 -->