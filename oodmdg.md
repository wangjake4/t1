代发 wailian999

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtmzkuswni.html

[M01] 读取命令行参数
来源：http://dali.sufxvd.cn/Article/details/gtxwoeavwl.html

Py:   sys.argv[1:]
来源：http://dali.ivvv.top/Article/details/gtxcyrhbyv.html

PHP:  $argv;  $argc;
来源：http://dali.aibaodan.cn/Article/details/gtolxldliu.html

JS:   process.argv.slice(2)
来源：http://dali.sysykeji.top/Article/details/gtspvbqhtn.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gtfypgcmgu.html

Java: args 数组（main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gtcdnkfkyg.html

Go:   os.Args[1:]
来源：http://dali.c1oappe.top/Article/details/gtmdlugldf.html

Ruby: ARGV
来源：http://dali.sweek.top/Article/details/gtrkmkjmug.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gtvslbwhda.html

[M02] 读取环境变量
来源：http://dali.yuanzhike.top/Article/details/gtkuvddxlr.html

Py:   os.environ.get("HOME")
来源：http://dali.bjfxy.top/Article/details/gtspvvqmjf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gtjmqpqfgd.html

JS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gtojqirrek.html

TS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gtewdmsiyu.html

Java: System.getenv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtqvexmara.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.havefunace.top/Article/details/gtrivxefap.html

Ruby: ENV["HOME"]
来源：http://dali.feifeiyinyue.top/Article/details/gtsphswwtf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daxiang520.top/Article/details/gtlyjqgxro.html

[M03] 执行外部命令
来源：http://dali.ppjwa.cn/Article/details/gtqwwyecrh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guannengcc.top/Article/details/gtswyuvtar.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenjidiqi.icu/Article/details/gtsqjpfqwj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gotoacloud.top/Article/details/gtlpqzwyqd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gtbyvrxsym.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.smart0.xyz/Article/details/gttdidwnup.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hfpthk.cn/Article/details/gtxexecdmq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuanzhike.top/Article/details/gthtugwkqj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpybgylhi.html

[M04] 获取当前工作目录
来源：http://dali.nanxinkj.top/Article/details/gtuwyxxkrk.html

Py:   os.getcwd()
来源：http://dali.nwbrower.top/Article/details/gttfiqvahb.html

PHP:  getcwd();
来源：http://dali.nanxuanxn.top/Article/details/gtaqdobfkh.html

JS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gtvabfxknm.html

TS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gteesabyhz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.0kj1m.cn/Article/details/gtuyamiuez.html

Go:   os.Getwd()
来源：http://dali.pycfn.com/Article/details/gtiiwlcppm.html

Ruby: Dir.pwd
来源：http://dali.yongpay.top/Article/details/gtpapzlral.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.iojbl.cn/Article/details/gtjluoyycl.html

[M05] 设置退出码
来源：http://dali.nwbrower.top/Article/details/gtesypbfwx.html

Py:   sys.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtokofmndh.html

PHP:  exit(1);
来源：http://dali.sufxvd.cn/Article/details/gttvvoemfe.html

JS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtpoercmjp.html

TS:   process.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtjpapenjn.html

Java: System.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtkvazvfgm.html

Go:   os.Exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtdhvwsbsf.html

Ruby: exit 1
来源：http://dali.aizwys.cn/Article/details/gtzukuwlla.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hysaishi.cn/Article/details/gtflxgtylv.html

[M06] 向标准错误输出
来源：http://dali.9152youxi.cn/Article/details/gtylrepfeg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gtktkxovgd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuxming.cn/Article/details/gtewezqyvb.html

JS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gtzkizatxe.html

TS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gtpmxatpkk.html

Java: System.err.println("err")
来源：http://dali.vqdsnc.cn/Article/details/gtndyqcpyv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.feifeiyinyue.top/Article/details/gtlwvwwlax.html

Ruby: warn "err"
来源：http://dali.mhx1999.top/Article/details/gtghuaijex.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtqrjcugyp.html

[M07] 判断是否为主入口
来源：http://dali.birdmap.top/Article/details/gtcxxnmrvl.html

Py:   if __name__ == "__main__":
来源：http://dali.yj202588.top/Article/details/gtwdzrfhtq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gzhubu.top/Article/details/gtprgjjnew.html

JS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gtucefcyzc.html

TS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gtwljsegwd.html

Java: public static void main(String[] args)
来源：http://dali.shuidangran.top/Article/details/gtesoqmdaj.html

Go:   func main()
来源：http://dali.zdqjudy.top/Article/details/gtxiatdvxz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvndcuyhz.html

C#:   static void Main(string[] args)
来源：http://dali.zhongyouzk.top/Article/details/gtzhymdjmu.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxsbinzz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.smart0.xyz/Article/details/gtwjkhdddh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.redwolf501.top/Article/details/gtewrguxrk.html

JS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gtversausa.html

TS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gtkxbqohqe.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yvedp.cn/Article/details/gtfutamvvo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sufxvd.cn/Article/details/gtvkymggfz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yangfankeji.com/Article/details/gteqkhmatz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.andypj.xyz/Article/details/gtkpkqtuji.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtrvfpmrsn.html

N. 数据结构与算法
来源：http://dali.xinyue.icu/Article/details/gtcpifhonk.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtkatrmwim.html

[N01] 二分查找（有序数组）
来源：http://dali.jianghu66.top/Article/details/gtivwbbsez.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.meibo888.top/Article/details/gtgvzyivfv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtlhinystk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jiagoushi.top/Article/details/gtkeojmmbv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gtoanmtgil.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtbyfbtecp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hammf.cn/Article/details/gtpwuftpba.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.snrcjt.cn/Article/details/gthtbouvbq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gtrimhuwkz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.snrcjt.cn/Article/details/gtnzekopnq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gtopwxkvbc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sysykeji.top/Article/details/gtvoeyboxd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gtchlbolqd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtuiemhjzu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xylfe.cn/Article/details/gtidcelewc.html

Go:   slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtuizrdhjh.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtcbxmsdbn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hnqzz.top/Article/details/gtxiiflqvf.html

[N03] 快速排序（分治示例）
来源：http://dali.zycfv.cn/Article/details/gtndtqauye.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daxiang520.top/Article/details/gtwzybzcnm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pengpengdd.cyou/Article/details/gtinfokujq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gtoonlzbtm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gtmtdacrvb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jyoumei.cn/Article/details/gtxncxhkcu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.snrcjt.cn/Article/details/gtvakjbpmy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.0kj1m.cn/Article/details/gtcymbdija.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ybcxt.top/Article/details/gtqlfgyjln.html

[N04] 斐波那契数列
来源：http://dali.shuidangran.top/Article/details/gtuurfhich.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.vqdsnc.cn/Article/details/gtqwohyphv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cashguo.top/Article/details/gtovrccpxr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtoyrymnik.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gtcvpddirs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuanzx.com/Article/details/gthvinzfig.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.snrcjt.cn/Article/details/gtcnpswnrn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtgroyfbzm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtupbayvhl.html

[N05] 最大公约数
来源：http://dali.chenlongwang.top/Article/details/gtgdbkvchx.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtxwadeeqy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gtomwrwrlu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtebismvla.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gtplqpqguj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.kuanghao11.cn/Article/details/gtkimqgdtu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gotoacloud.top/Article/details/gtajavqhfw.html

Ruby: a.gcd(b)
来源：http://dali.aizwys.cn/Article/details/gtucdwuqfb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tanke756.top/Article/details/gtnzrfiqry.html

[N06] 判断回文字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtsihazecg.html

Py:   s == s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gtcnusukzp.html

PHP:  $s === strrev($s);
来源：http://dali.cucudq.cn/Article/details/gtcxpjuyqb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtuspumtap.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gttzihdblo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gzhubu.top/Article/details/gtugcwgsex.html

Go:   // 双指针从两端比较
来源：http://dali.dianchejie.cn/Article/details/gttwkprnex.html

Ruby: s == s.reverse
来源：http://dali.guowangkeji.top/Article/details/gtwfisdhlv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gtfxjrqvqq.html

[N07] 两数之和（返回下标）
来源：http://dali.jinghuilouyu.cn/Article/details/gtguwxpsbw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigfzy.top/Article/details/gtazpgzqwe.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhixingplan.top/Article/details/gtnxwdmlki.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenzaomai.com/Article/details/gtpnhclvig.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj202588.top/Article/details/gtogujhqtd.html

Java: // 手写 HashMap
来源：http://dali.gotoacloud.top/Article/details/gtadgkkiuk.html

Go:   // 手写 map[int]int
来源：http://dali.yonumen.top/Article/details/gtstlzigey.html

Ruby: // 手写 Hash
来源：http://dali.zdqjudy.top/Article/details/gtmmvbhebb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dianchejie.cn/Article/details/gtkegmscll.html

[N08] 生成全排列
来源：http://dali.c1oappe.top/Article/details/gtohirbqhu.html

Py:   itertools.permutations(arr)
来源：http://dali.yangfankeji.com/Article/details/gtkfhefxva.html

PHP:  // 手写递归交换
来源：http://dali.dashuyun.cn/Article/details/gtgdaefoop.html

JS:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gthtqlstdu.html

TS:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtjuorsvfi.html

Java: // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtlpbdcnnu.html

Go:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gttyppzcnt.html

Ruby: arr.permutation.to_a
来源：http://dali.yonumen.top/Article/details/gtxupexccm.html

C#:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtrshucurl.html

[N09] 栈与队列
来源：http://dali.zdqjudy.top/Article/details/gtyhmhquey.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.redwolf501.top/Article/details/gtcgqscxyn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ybcxt.top/Article/details/gtjozpslhn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gtuwnjeszw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.9152youxi.cn/Article/details/gtxqnuesmg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ivvv.top/Article/details/gtyghfafoy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sufxvd.cn/Article/details/gtmvixtlfu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gttmusweit.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinqigufen.top/Article/details/gtkrmmvoff.html

[N10] 链表节点定义
来源：http://dali.fzhhl.top/Article/details/gtspmzvefz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrxcxvhv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjscovip.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yangfankeji.com/Article/details/gtuarztktb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ydzc1.top/Article/details/gtjfdbertt.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258.top/Article/details/gtxzrjnton.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhoulong.xyz/Article/details/gtxczypywn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgufenzy.top/Article/details/gtswxpgatb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.kuanghao11.cn/Article/details/gthkcmazjw.html

[N11] 二叉树中序遍历
来源：http://dali.316326.xyz/Article/details/gtqtofrxfp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ydzc1.top/Article/details/gtbkujgzmg.html

PHP:  // 手写递归函数
来源：http://dali.pycfn.com/Article/details/gtijgkczwx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevhrpiol.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yangfankeji.com/Article/details/gtrlqneaog.html

Java: // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtfjlozeth.html

Go:   // 手写递归
来源：http://dali.aizwys.cn/Article/details/gtmozgnuqy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cheryme.top/Article/details/gtilkakpph.html

C#:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gtamffdnbf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenlongwang.top/Article/details/gthvxhallz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenjidiqi.icu/Article/details/gtesyipzmw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.andypj.xyz/Article/details/gtjnjepfwb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gtftivgbbu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sufxvd.cn/Article/details/gtlketkuii.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gtxkmbpgfj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ehwqpu.com/Article/details/gtmlfwlfhl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ydzc1.top/Article/details/gtnbfkvbcq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gttcxwjerg.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtpfvfpzhz.html

O. 并发与异步
来源：http://dali.pycfn.com/Article/details/gtahsryjqz.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gttukcwcqs.html

[O01] 启动一个线程
来源：http://dali.yonumen.top/Article/details/gtyptenbsn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jqgufenzy.top/Article/details/gtlequhaky.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xuanzx.com/Article/details/gtjdxcsvgx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tianlin.xyz/Article/details/gtgnfapuqw.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gtkbauiumk.html

Java: new Thread(() -> f()).start()
来源：http://dali.mhx1999.top/Article/details/gtpsfzwbug.html

Go:   go f()
来源：http://dali.shangyingyoupin.top/Article/details/gthhmddzbw.html

Ruby: Thread.new { f }
来源：http://dali.ppjwa.cn/Article/details/gtdbcncwyn.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258888.top/Article/details/gtjkpormel.html

[O02] 使用线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprizafej.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnxiangtu.top/Article/details/gtvmfmuhxu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gaohongyu789.top/Article/details/gtcuegoyfx.html

JS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gtiooibkmm.html

TS:   // worker_threads 线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtptfdnzvu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gaohongyu789.top/Article/details/gthsvbvwum.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ivvv.top/Article/details/gtoibwehwi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shzxlz.cn/Article/details/gtmbijuhun.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hfpthk.cn/Article/details/gtyufeidaz.html

[O03] 加锁保护共享数据
来源：http://dali.jiagoushi.top/Article/details/gtwbthtgrq.html

Py:   with lock: shared += 1
来源：http://dali.cdnleiting.top/Article/details/gtztxhkmmc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fengsongda.top/Article/details/gttjvztzjb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sufxvd.cn/Article/details/gtcwystqpn.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gtyfuccuki.html

Java: synchronized (this) { shared++; }
来源：http://dali.9152youxi.cn/Article/details/gtzdssfkmt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuanzhike.top/Article/details/gtcntrewea.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tian-w.cn/Article/details/gtbvilfsdn.html

C#:   lock (gate) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gtrxytorkl.html

[O04] 定义异步函数并等待
来源：http://dali.hammf.cn/Article/details/gttsxxbvaw.html

Py:   async def f():⏎    await g()
来源：http://dali.kuanghao11.cn/Article/details/gtpivvbyfl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hywenlv.cn/Article/details/gttdgowdvk.html

JS:   async function f() { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gtnhiacisw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sysykeji.top/Article/details/gtqoguprkw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nanxuanxn.top/Article/details/gtjgxrlten.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jianghu66.top/Article/details/gtrsmksfzw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ehwqpu.com/Article/details/gtacxsfcmj.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigfzy.top/Article/details/gtsxafrbdy.html

[O05] 并发执行并等待全部完成
来源：http://dali.pengpengdd.cyou/Article/details/gthflffqgt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj20258888.top/Article/details/gtkokbtqrm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xylfe.cn/Article/details/gtgpnhsifd.html

JS:   await Promise.all(tasks)
来源：http://dali.fengsongda.top/Article/details/gtkoksktbz.html

TS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gtnsvomjsc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenlongwang.top/Article/details/gtptcnverz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.c1oappe.top/Article/details/gttwrgtwbs.html

Ruby: threads.map(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gtpslejlvn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuanzx.com/Article/details/gtiotibice.html

[O06] 使用进程池
来源：http://dali.ydzc1.top/Article/details/gtrshpbbrh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuanzhike.top/Article/details/gtrtmhcwic.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cucudq.cn/Article/details/gtywubkkij.html

JS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gtepqqremt.html

TS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gtxnhnzfhg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jlsjyb.cn/Article/details/gtojaddeom.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhongyouzk.top/Article/details/gtzlytizad.html

Ruby: // fork 块
来源：http://dali.smart0.xyz/Article/details/gtdjrnbska.html

C#:   Parallel.For
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkhsouuk.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtiylriitg.html

P. 常用工具函数
来源：http://dali.sufxvd.cn/Article/details/gtmdqqnnlr.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtkewdqjdt.html

[P01] 生成 UUID
来源：http://dali.yuxming.cn/Article/details/gtxvgilqro.html

Py:   str(uuid.uuid4())
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwrsyzth.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbiucdbgh.html

JS:   crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gtwbktjjqs.html

TS:   crypto.randomUUID()
来源：http://dali.yj20258.top/Article/details/gtpujpoyss.html

Java: UUID.randomUUID().toString()
来源：http://dali.xinyue.icu/Article/details/gtbiunmmbk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiasjxjns.html

Ruby: SecureRandom.uuid
来源：http://dali.wangdashe.top/Article/details/gtgoszqshk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.9152youxi.cn/Article/details/gtkgkfermu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shangyingyoupin.top/Article/details/gtgpbjwgfh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cqqwz.cn/Article/details/gtxxyatuno.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gaohongyu789.top/Article/details/gtawnlzoud.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinqigufen.top/Article/details/gtliubmwcs.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shangyingyoupin.top/Article/details/gtmneqvwyh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daria6918.cn/Article/details/gtclihbgvo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.c1oappe.top/Article/details/gtgpxxkkpa.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhengqikj.top/Article/details/gtbpuxyclq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sufxvd.cn/Article/details/gtiwfsboqv.html

[P03] 生成短随机字符串
来源：http://dali.jiagoushi.top/Article/details/gtwjbvjnnv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yuanzhike.top/Article/details/gtrvdarvjm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daria6918.cn/Article/details/gtawmrhntz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gtaunygykj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.quarkkingdee.top/Article/details/gttwfdvuvi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pycfn.com/Article/details/gtmnjimsar.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yanxiufei.cn/Article/details/gtwvxxifvg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yuxming.cn/Article/details/gtvalvgamd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cdnleiting.top/Article/details/gtddgpdmqp.html

[P04] 求长度
来源：http://dali.fzhhl.top/Article/details/gtptqxaxoq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.aibaodan.cn/Article/details/gtswkmpfug.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gttxgmfond.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cdnleiting.top/Article/details/gthzxxvyhi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hfpthk.cn/Article/details/gtaushlljy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgktyplyp.html

Go:   len(arr);  len(m)
来源：http://dali.bjfxy.top/Article/details/gttpzelaif.html

Ruby: x.length;  x.size
来源：http://dali.jinqigfzy.top/Article/details/gtbsszkdec.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.havefunace.top/Article/details/gtxdkomfki.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hywenlv.cn/Article/details/gtcmtlsvfn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.redwolf501.top/Article/details/gtpkujnmdz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yuanzhike.top/Article/details/gtpqzbdlgj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yanxiufei.cn/Article/details/gtmrmgfeoi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cdnleiting.top/Article/details/gtpvsicfnp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.vqdsnc.cn/Article/details/gtdptniupn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.havefunace.top/Article/details/gtpcqazxvd.html

Ruby: a == b
来源：http://dali.gaohongyu789.top/Article/details/gtrjrjaofp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhoulong.xyz/Article/details/gtzpnvdxwp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ivvv.top/Article/details/gtntwgoqcx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj20258.top/Article/details/gtzbliqrzi.html

PHP:  if (empty($x)) {}
来源：http://dali.svipenyu.cn/Article/details/gtwmexlzfi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yangfankeji.com/Article/details/gtgvyadtex.html

TS:   if (x == null) {}
来源：http://dali.316326.xyz/Article/details/gtuhpalypq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gtodnvjpwd.html

Go:   if x == nil {}
来源：http://dali.tian-w.cn/Article/details/gtyxwjansf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhongyouzk.top/Article/details/gtdljmbtro.html

C#:   if (x is null) {}
来源：http://dali.sysykeji.top/Article/details/gtsrqknfuy.html

[P07] 防抖与节流
来源：http://dali.c1oappe.top/Article/details/gtmahbskhi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangshuangyany.cn/Article/details/gteikooqgl.html


<!-- 参考信息 -->