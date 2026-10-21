代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtsilkcjyz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gttzrhxhdc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xziqi.cn/Article/details/gtgfdskrwk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guannengcc.top/Article/details/gtlibvavrp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shangyingyoupin.top/Article/details/gtiixavzbh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ehwqpu.com/Article/details/gtpvvitrgk.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtgktyjghs.html

M. 命令行 / 进程 / 环境
来源：http://dali.guannengcc.top/Article/details/gtubqhagrz.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gttcosgdfy.html

[M01] 读取命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gtwjujvcrp.html

Py:   sys.argv[1:]
来源：http://dali.zhixingplan.top/Article/details/gtlwiaozef.html

PHP:  $argv;  $argc;
来源：http://dali.jiagoushi.top/Article/details/gtjoqxpvka.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gtkggnatfb.html

TS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gtiusjybmx.html

Java: args 数组（main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gtwawcdzng.html

Go:   os.Args[1:]
来源：http://dali.bjfxy.top/Article/details/gtsnzilooz.html

Ruby: ARGV
来源：http://dali.jinqigfzy.top/Article/details/gtlbbsdliy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhiwuduotai.top/Article/details/gthpkhfsvu.html

[M02] 读取环境变量
来源：http://dali.ybcxt.top/Article/details/gtoneirxsu.html

Py:   os.environ.get("HOME")
来源：http://dali.yuxming.cn/Article/details/gtzzxxvsfm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gtewchbcyd.html

JS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtxgkydtce.html

TS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gtdlmrhvuu.html

Java: System.getenv("HOME")
来源：http://dali.yongpay.top/Article/details/gtsywwocjm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtotyzohnd.html

Ruby: ENV["HOME"]
来源：http://dali.nwbrower.top/Article/details/gtfvlaqxdb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tanke756.top/Article/details/gtxulayjav.html

[M03] 执行外部命令
来源：http://dali.wangdashe.top/Article/details/gtxqjhlnzu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sufxvd.cn/Article/details/gttcqmhiwo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzptufgdq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gtxinfsnkx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gtewpueadi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenjidiqi.icu/Article/details/gtaejhalif.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yanxiufei.cn/Article/details/gtedixiase.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.316326.xyz/Article/details/gtflvwfkqy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hfpthk.cn/Article/details/gtgdmnbqhs.html

[M04] 获取当前工作目录
来源：http://dali.chenlongwang.top/Article/details/gtbqfsuaup.html

Py:   os.getcwd()
来源：http://dali.hammf.cn/Article/details/gteoennpqd.html

PHP:  getcwd();
来源：http://dali.yueranfly.top/Article/details/gtwbphjvil.html

JS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gtsbawcxak.html

TS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gttsrssmqg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shangyingyoupin.top/Article/details/gtdtblizwz.html

Go:   os.Getwd()
来源：http://dali.shzxlz.cn/Article/details/gtkjdgwcou.html

Ruby: Dir.pwd
来源：http://dali.sysykeji.top/Article/details/gtbszsntvp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenlongwang.top/Article/details/gtblgaubec.html

[M05] 设置退出码
来源：http://dali.bjfxy.top/Article/details/gtufmyhugz.html

Py:   sys.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtstufugpj.html

PHP:  exit(1);
来源：http://dali.birdmap.top/Article/details/gtcpgnlmyu.html

JS:   process.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtyectnvbm.html

TS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gtrfrteeqv.html

Java: System.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcphbjtvr.html

Go:   os.Exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtpszmrmwg.html

Ruby: exit 1
来源：http://dali.jqgfzy.top/Article/details/gtlkjejtyr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nwbrower.top/Article/details/gtopzgxvtg.html

[M06] 向标准错误输出
来源：http://dali.jqgufenzy.top/Article/details/gteshzfgeb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gtgxckbswj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigfzy.top/Article/details/gtnnyqtkrp.html

JS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gtwzjpxvjy.html

TS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gtdxibpxbj.html

Java: System.err.println("err")
来源：http://dali.yj20258.top/Article/details/gtyweoditi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gtbyquaoyz.html

Ruby: warn "err"
来源：http://dali.sweek.top/Article/details/gthgmvhqne.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cheryme.top/Article/details/gtbntpzips.html

[M07] 判断是否为主入口
来源：http://dali.zhongyouzk.top/Article/details/gtiyxpvjfc.html

Py:   if __name__ == "__main__":
来源：http://dali.nwbrower.top/Article/details/gtdixpeomo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxinkj.top/Article/details/gtierwrmei.html

JS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gtsndztlyk.html

TS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gtnjvqojbs.html

Java: public static void main(String[] args)
来源：http://dali.andypj.xyz/Article/details/gtcdesefrs.html

Go:   func main()
来源：http://dali.jlsjyb.cn/Article/details/gtzevnaazm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenjidiqi.icu/Article/details/gtrbsyudke.html

C#:   static void Main(string[] args)
来源：http://dali.aizwys.cn/Article/details/gtftnukvda.html

[M08] 获取系统与运行时信息
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpiloutqp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.mhx1999.top/Article/details/gttufdcevw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jiagoushi.top/Article/details/gtyicdkoru.html

JS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxwzkpord.html

TS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gtssuuxipa.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shangyingyoupin.top/Article/details/gtsmixfqld.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj202588.top/Article/details/gtnsaeiqno.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258888.top/Article/details/gtenpxgxhj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.c1oappe.top/Article/details/gtgcrheyia.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtrygcomdn.html

N. 数据结构与算法
来源：http://dali.feifeiyinyue.top/Article/details/gtrqeonenz.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtuzidpsif.html

[N01] 二分查找（有序数组）
来源：http://dali.fengsongda.top/Article/details/gtvglhahjr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.meibo888.top/Article/details/gtytjawmxy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gttjmcdjdy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gthahfeeol.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sxryk.cn/Article/details/gtqpkxypfh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtfqdsyjtb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtorskkjdi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbdqniac.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gtokqfhlci.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhongyouzk.top/Article/details/gtyqrpqvfw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gtnzqnfonf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hywenlv.cn/Article/details/gtezmalhdz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gtnarmiccy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqimuiizu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jiagoushi.top/Article/details/gtrfumfqck.html

Go:   slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gturvsqbgq.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtsyveixjh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daxiang520.top/Article/details/gtkfyjjpgl.html

[N03] 快速排序（分治示例）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjmdhnex.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aizwys.cn/Article/details/gtvfbwlvuk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuxming.cn/Article/details/gtzngghrcf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gtjbzbjeek.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gtzpkcgkrz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yonumen.top/Article/details/gtyhpwlnak.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.havefunace.top/Article/details/gtceecmwhp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sysykeji.top/Article/details/gtsildnrpv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgufenzy.top/Article/details/gtcgfbccds.html

[N04] 斐波那契数列
来源：http://dali.hysaishi.cn/Article/details/gtvhvjrtpj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gtsdcmiyvl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gtxjtzywys.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gttaqjzcad.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtiwnljbup.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gteugqowiu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuxming.cn/Article/details/gtswkpkuoo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigufen.top/Article/details/gtjemeappz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtelmnchso.html

[N05] 最大公约数
来源：http://dali.shangyingyoupin.top/Article/details/gtuowzzhef.html

Py:   math.gcd(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtgvgqizgt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtpguglkdp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gtewknqolt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtwmrdvgrq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daria6918.cn/Article/details/gtkdbdctlz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shuidangran.top/Article/details/gthrebnjoz.html

Ruby: a.gcd(b)
来源：http://dali.jinqigufen.top/Article/details/gtdtonnagx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.wangshuangyany.cn/Article/details/gtkpsqsadb.html

[N06] 判断回文字符串
来源：http://dali.yueranfly.top/Article/details/gtarwzasic.html

Py:   s == s[::-1]
来源：http://dali.xinyue.icu/Article/details/gtofumwpee.html

PHP:  $s === strrev($s);
来源：http://dali.c1oappe.top/Article/details/gtjdnyoaan.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtvikpmsfl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtzoedbhwo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aizwys.cn/Article/details/gtiwdhisnz.html

Go:   // 双指针从两端比较
来源：http://dali.ppjwa.cn/Article/details/gtsgbvpnyy.html

Ruby: s == s.reverse
来源：http://dali.hywenlv.cn/Article/details/gtrexvgvww.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gtglwigoax.html

[N07] 两数之和（返回下标）
来源：http://dali.hongshengwenyu.top/Article/details/gtmbajsfen.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sysykeji.top/Article/details/gttenocxpq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgoqikhey.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cucudq.cn/Article/details/gtcajbgsqy.html

TS:   // 手写 Map<string, number>
来源：http://dali.tianlin.xyz/Article/details/gtirerevhg.html

Java: // 手写 HashMap
来源：http://dali.svipenyu.cn/Article/details/gtckvakbop.html

Go:   // 手写 map[int]int
来源：http://dali.dashuyun.cn/Article/details/gtpkyapcug.html

Ruby: // 手写 Hash
来源：http://dali.wangdashe.top/Article/details/gtieuthqaj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhixingplan.top/Article/details/gtnhsrxnfw.html

[N08] 生成全排列
来源：http://dali.jinqigufen.top/Article/details/gtgbobumzl.html

Py:   itertools.permutations(arr)
来源：http://dali.c1oappe.top/Article/details/gtvesiqnnq.html

PHP:  // 手写递归交换
来源：http://dali.zhiwuduotai.top/Article/details/gtcjbovosi.html

JS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtxdrccclq.html

TS:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtehmlyjrj.html

Java: // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtigxdqcac.html

Go:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtejtjxpvj.html

Ruby: arr.permutation.to_a
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbivehqjc.html

C#:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gteorunfev.html

[N09] 栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gttrstuiuv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daxiang520.top/Article/details/gtusyubqvo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tanke756.top/Article/details/gtnfkbocup.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtavzvtsim.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hongshengwenyu.top/Article/details/gtgiiewhnr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tanke756.top/Article/details/gtaemqxxzd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sysykeji.top/Article/details/gtvdlcylxt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gtgwyhaziv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxuanxn.top/Article/details/gtrcacbdft.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzuiyggu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dianchejie.cn/Article/details/gtdlmtqtbp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aizwys.cn/Article/details/gtymcveanc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdizesum.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxuanxn.top/Article/details/gtzezmfhok.html

Java: class Node { int v; Node next; }
来源：http://dali.meibo888.top/Article/details/gtdvptlrhz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sufxvd.cn/Article/details/gtmxbnmbri.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xuanzx.com/Article/details/gtmkzrfain.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xziqi.cn/Article/details/gtiuhzikwv.html

[N11] 二叉树中序遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjktrtcgz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.c1oappe.top/Article/details/gttgwaxzli.html

PHP:  // 手写递归函数
来源：http://dali.0kj1m.cn/Article/details/gtaggwrzsj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gtqqdxpeer.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gtxbtfzjsj.html

Java: // 手写递归
来源：http://dali.mhx1999.top/Article/details/gtcrwbjhka.html

Go:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gtfjjyuqxa.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pengpengdd.cyou/Article/details/gtvytsuswd.html

C#:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gthebdlujh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jianghu66.top/Article/details/gtlbwnikuf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybthuxsg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cashguo.top/Article/details/gttfiiuwwm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenzaomai.com/Article/details/gtbaumdswf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuetiantiany.cn/Article/details/gtnevieqga.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gtsrufipev.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gotoacloud.top/Article/details/gtknxyqpcp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.c1oappe.top/Article/details/gtlwjfrlcq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ppjwa.cn/Article/details/gtrmafbjss.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtvqncggxg.html

O. 并发与异步
来源：http://dali.tanke756.top/Article/details/gtaxtbzojq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtsuthauvh.html

[O01] 启动一个线程
来源：http://dali.haohaochexian.top/Article/details/gtovlaggfq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuxming.cn/Article/details/gtvfyofmdr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hammf.cn/Article/details/gtexaxmyjr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.feifeiyinyue.top/Article/details/gtscwskbpf.html

TS:   // 同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwstvhak.html

Java: new Thread(() -> f()).start()
来源：http://dali.gogol.net.cn/Article/details/gtcscgcknx.html

Go:   go f()
来源：http://dali.tanke756.top/Article/details/gtrrsmclvo.html

Ruby: Thread.new { f }
来源：http://dali.hywenlv.cn/Article/details/gtsujhhqwp.html

C#:   Task.Run(() => F());
来源：http://dali.jlsjyb.cn/Article/details/gtcbcjzuvh.html

[O02] 使用线程池
来源：http://dali.yuxming.cn/Article/details/gtfkxljwhh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shangyingyoupin.top/Article/details/gtirvwxjvj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.vqdsnc.cn/Article/details/gtuusnlzwi.html

JS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gtqoyjjkgz.html

TS:   // worker_threads 线程池
来源：http://dali.zdqjudy.top/Article/details/gtbtzscmqf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhoulong.xyz/Article/details/gttwewysel.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuanzhike.top/Article/details/gtrcmhwovv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfalnaxkc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xziqi.cn/Article/details/gtimcwtwjn.html

[O03] 加锁保护共享数据
来源：http://dali.redwolf501.top/Article/details/gtsogylksk.html

Py:   with lock: shared += 1
来源：http://dali.zycfv.cn/Article/details/gtdkegccig.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fzhhl.top/Article/details/gtzwrchqsr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dashuyun.cn/Article/details/gtyzuoafmf.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gtmsmhskfd.html

Java: synchronized (this) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gteztzekys.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.haohaochexian.top/Article/details/gtdypsukgq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgfzy.top/Article/details/gtcwhqxdpe.html

C#:   lock (gate) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gtqgmzzasb.html

[O04] 定义异步函数并等待
来源：http://dali.wangdashe.top/Article/details/gtvilzjhac.html

Py:   async def f():⏎    await g()
来源：http://dali.redwolf501.top/Article/details/gteplrqvkd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yonumen.top/Article/details/gtrxbzbyna.html

JS:   async function f() { await g(); }
来源：http://dali.gzhubu.top/Article/details/gtkzdutgtv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj202588.top/Article/details/gtpuzfzmtz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cashguo.top/Article/details/gtexnnptzb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxuanxn.top/Article/details/gtamohcrjl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nanxuanxn.top/Article/details/gtczuzetfo.html

C#:   async Task F() { await G(); }
来源：http://dali.cqqwz.cn/Article/details/gtuxjudjog.html

[O05] 并发执行并等待全部完成
来源：http://dali.316326.xyz/Article/details/gtpvrvjore.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ybcxt.top/Article/details/gtxzeweaap.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhengqikj.top/Article/details/gtuzcvaywt.html

JS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgettpszy.html

TS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gtbzismymk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiotdkviu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cucudq.cn/Article/details/gtfljnjozx.html

Ruby: threads.map(&:join)
来源：http://dali.jyoumei.cn/Article/details/gtxvmsltnw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.bjfxy.top/Article/details/gtsfdpleju.html

[O06] 使用进程池
来源：http://dali.ybcxt.top/Article/details/gtysrtwieq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sxryk.cn/Article/details/gtdjshyqhn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pengpengdd.cyou/Article/details/gtynclqlks.html

JS:   // child_process / cluster 模块
来源：http://dali.cdnleiting.top/Article/details/gtqzxqtate.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258888.top/Article/details/gtpwidqxns.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.birdmap.top/Article/details/gtbtrcbfsc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sweek.top/Article/details/gtihhvmkll.html

Ruby: // fork 块
来源：http://dali.sxryk.cn/Article/details/gtkusvgkox.html

C#:   Parallel.For
来源：http://dali.fengsongda.top/Article/details/gtwqgndbcu.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvrtvjrr.html

P. 常用工具函数
来源：http://dali.xinyue.icu/Article/details/gtvcdcznxd.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtwdxyqfau.html

[P01] 生成 UUID
来源：http://dali.xylfe.cn/Article/details/gtodgojvsq.html

Py:   str(uuid.uuid4())
来源：http://dali.zhixingplan.top/Article/details/gtquvwjzvg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hfpthk.cn/Article/details/gtqyfvobad.html

JS:   crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gtrbjticws.html

TS:   crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmymgxwaq.html

Java: UUID.randomUUID().toString()
来源：http://dali.smart0.xyz/Article/details/gtgslnusgs.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cqqwz.cn/Article/details/gtlxoeffvt.html

Ruby: SecureRandom.uuid
来源：http://dali.c1oappe.top/Article/details/gthygtmbew.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yueranfly.top/Article/details/gtnrpgnjih.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hfpthk.cn/Article/details/gtrrvaipjp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyocykjnv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yangfankeji.com/Article/details/gtzuiurguc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yueranfly.top/Article/details/gtbtfaqczn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnxiangtu.top/Article/details/gtyespbhpr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gtafgkqxvv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jianghu66.top/Article/details/gtidnppvti.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xylfe.cn/Article/details/gtoghjwgla.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfgyyykw.html

[P03] 生成短随机字符串
来源：http://dali.aizwys.cn/Article/details/gtbplbrpdm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hfpthk.cn/Article/details/gtnyltkhmr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhengqikj.top/Article/details/gtjqbwzzaw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yueranfly.top/Article/details/gtjakwihil.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gtjbwkbhox.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cheryme.top/Article/details/gtsfjkbllj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hysaishi.cn/Article/details/gtlnyrieww.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenzaomai.com/Article/details/gtajjzmyco.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zycfv.cn/Article/details/gtbjgflexk.html

[P04] 求长度
来源：http://dali.cqqwz.cn/Article/details/gttxxihmzb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dianchejie.cn/Article/details/gtxmzfqyzr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtlfoqydxl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aibaodan.cn/Article/details/gtmpbujdwj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shzxlz.cn/Article/details/gtqbfqhuxp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gtburrcszh.html

Go:   len(arr);  len(m)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrlpqzjj.html

Ruby: x.length;  x.size
来源：http://dali.jinqigufen.top/Article/details/gtralqsfpg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xylfe.cn/Article/details/gtjohuyyur.html

[P05] 判断两个对象内容是否相等
来源：http://dali.316326.xyz/Article/details/gtsizfvgtd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cqqwz.cn/Article/details/gtgrwhkbhb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daria6918.cn/Article/details/gtnavffxmd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cheryme.top/Article/details/gtonoomupy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtwlizaoev.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.bjfxy.top/Article/details/gtxmfjwnzk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.fzhhl.top/Article/details/gtqttesmjq.html

Ruby: a == b
来源：http://dali.hongshengwenyu.top/Article/details/gtxfbrofov.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gzhubu.top/Article/details/gtpobpuene.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.birdmap.top/Article/details/gtshlejvjg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ppjwa.cn/Article/details/gtdecnhibj.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigfzy.top/Article/details/gtfbjvkiqj.html


<!-- 参考信息 -->