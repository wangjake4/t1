代发 wailian999

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jianghu66.top/Article/details/gt2xebbizwm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xziqi.cn/Article/details/gt2lfdzbwfw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2hbshlnqo.html

M. 命令行 / 进程 / 环境
来源：http://dali.jianghu66.top/Article/details/gt2jhcgmznx.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2fgpdlsps.html

[M01] 读取命令行参数
来源：http://dali.ybcxt.top/Article/details/gt2gtpdgoye.html

Py:   sys.argv[1:]
来源：http://dali.tianlin.xyz/Article/details/gt2dvhmwzln.html

PHP:  $argv;  $argc;
来源：http://dali.hywenlv.cn/Article/details/gt2dwjipyti.html

JS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gt2jfroykii.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gt2ysooihsi.html

Java: args 数组（main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gt2nrptucpv.html

Go:   os.Args[1:]
来源：http://dali.meibo888.top/Article/details/gt2vmysbjjl.html

Ruby: ARGV
来源：http://dali.cashguo.top/Article/details/gt2uimwnque.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258.top/Article/details/gt2gnztdlfc.html

[M02] 读取环境变量
来源：http://dali.zycfv.cn/Article/details/gt2nowqztgg.html

Py:   os.environ.get("HOME")
来源：http://dali.havefunace.top/Article/details/gt2suehcsue.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258.top/Article/details/gt2gaukrwtd.html

JS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gt2kwyyijtg.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gt2yletzgsw.html

Java: System.getenv("HOME")
来源：http://dali.ydzc1.top/Article/details/gt2ejkopcpa.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pycfn.com/Article/details/gt2emdtkagc.html

Ruby: ENV["HOME"]
来源：http://dali.dashuyun.cn/Article/details/gt2rvjamoel.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ydzc1.top/Article/details/gt2pmgfyfzu.html

[M03] 执行外部命令
来源：http://dali.mhx1999.top/Article/details/gt2facrejyw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sweek.top/Article/details/gt2ewvxqcgg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jyoumei.cn/Article/details/gt2chgmbzgh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gt2jhyaoild.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gt2vcukwgqz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nwbrower.top/Article/details/gt2ypeffcbg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gewgylsp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.mhx1999.top/Article/details/gt2zsvpuiyg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cqqwz.cn/Article/details/gt2ivtiskyz.html

[M04] 获取当前工作目录
来源：http://dali.jianghu66.top/Article/details/gt2dsnvzzta.html

Py:   os.getcwd()
来源：http://dali.ivvv.top/Article/details/gt2vhabwcjx.html

PHP:  getcwd();
来源：http://dali.sxryk.cn/Article/details/gt2fvqfjuap.html

JS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gt2ufaobgqc.html

TS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gt2yuejhxuc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhengqikj.top/Article/details/gt2wiyufqrm.html

Go:   os.Getwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ioxentar.html

Ruby: Dir.pwd
来源：http://dali.aibaodan.cn/Article/details/gt2guwrbkuf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ehwqpu.com/Article/details/gt2lrxpdjfj.html

[M05] 设置退出码
来源：http://dali.tianlin.xyz/Article/details/gt2yrjheakz.html

Py:   sys.exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2rdvslomq.html

PHP:  exit(1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2hgipkjlv.html

JS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gt2igaoctpf.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2njjlanpr.html

Java: System.exit(1)
来源：http://dali.daria6918.cn/Article/details/gt2rmfrjppx.html

Go:   os.Exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2uplypwrw.html

Ruby: exit 1
来源：http://dali.aizwys.cn/Article/details/gt2oyodipwh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuetiantiany.cn/Article/details/gt2wrcgjyqn.html

[M06] 向标准错误输出
来源：http://dali.birdmap.top/Article/details/gt2jshcengk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhixingplan.top/Article/details/gt2wfrykszl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.haohaochexian.top/Article/details/gt2rrevzjjy.html

JS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gt2henkedyh.html

TS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gt2ekrgfrwy.html

Java: System.err.println("err")
来源：http://dali.sysykeji.top/Article/details/gt2ecrlyudg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.316326.xyz/Article/details/gt2lcpaeyat.html

Ruby: warn "err"
来源：http://dali.fzhhl.top/Article/details/gt2kkghoypm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohzovcam.html

[M07] 判断是否为主入口
来源：http://dali.cashguo.top/Article/details/gt2cspumcop.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgfzy.top/Article/details/gt2vzdcrjlf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.daxiang520.top/Article/details/gt2gcjsvxim.html

JS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gt2iduzocaj.html

TS:   require.main === module
来源：http://dali.cqqwz.cn/Article/details/gt2weupsrtk.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zozjnwkt.html

Go:   func main()
来源：http://dali.gzhubu.top/Article/details/gt2qdofkehf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.svipenyu.cn/Article/details/gt2tpktyaui.html

C#:   static void Main(string[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gt2akgplbpg.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgfzy.top/Article/details/gt2kotdacei.html

Py:   platform.system();  platform.python_version()
来源：http://dali.andypj.xyz/Article/details/gt2qakjaiqv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sxryk.cn/Article/details/gt2dwkmuulm.html

JS:   process.platform;  process.version
来源：http://dali.gogol.net.cn/Article/details/gt2ottiblnv.html

TS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gt2vcejygcl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuetiantiany.cn/Article/details/gt2nlloydkw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hysaishi.cn/Article/details/gt2lijqwiej.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qbhuhcew.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenlongwang.top/Article/details/gt2lyqpnubv.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2zdkmvlio.html

N. 数据结构与算法
来源：http://dali.gzhubu.top/Article/details/gt2misvzrkn.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2jiydodmm.html

[N01] 二分查找（有序数组）
来源：http://dali.jlsjyb.cn/Article/details/gt2ubyitwcp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2mhlszzav.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gt2osxgiifp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gt2hdwbklqt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gt2zskkbhgo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2mqfjoocx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2eskqffad.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.snrcjt.cn/Article/details/gt2cgdajqhk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2pltjoddb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ivvv.top/Article/details/gt2eunjtwvk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gt2qsaboard.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.9152youxi.cn/Article/details/gt2keikbpvg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gt2ybvpihmd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gt2izgvqjlp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yangfankeji.com/Article/details/gt2ekyrvbqd.html

Go:   slices.Sort(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2ynmxmelf.html

Ruby: arr.sort
来源：http://dali.chenlongwang.top/Article/details/gt2snzmydbf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.redwolf501.top/Article/details/gt2cpehoyko.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigufen.top/Article/details/gt2ggbibgqf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgufenzy.top/Article/details/gt2wftjuxmw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jlsjyb.cn/Article/details/gt2dqpmpcic.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gt2gtfgqgqm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gt2cnxbmnqf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sweek.top/Article/details/gt2rbgsrdnw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenzaomai.com/Article/details/gt2ippeplbu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dianchejie.cn/Article/details/gt2yqmxmqqj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xylfe.cn/Article/details/gt2qkymgrlt.html

[N04] 斐波那契数列
来源：http://dali.tanke756.top/Article/details/gt2swykdzab.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dlkfmxrc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tian-w.cn/Article/details/gt2vrqvvqsi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpclitxm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gt2bssvvyeg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangdashe.top/Article/details/gt2kpeeoant.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.haohaochexian.top/Article/details/gt2dfkarmwd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gt2jxqzjngb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gt2vsjtndkz.html

[N05] 最大公约数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kwgvepyx.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlotzmq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hammf.cn/Article/details/gt2bledykkt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gt2tfhbvkkc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gt2kddnpabm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zycfv.cn/Article/details/gt2deofteih.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hammf.cn/Article/details/gt2daavadgi.html

Ruby: a.gcd(b)
来源：http://dali.dianchejie.cn/Article/details/gt2jsairwsv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vqbtakyl.html

[N06] 判断回文字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ntesfcbi.html

Py:   s == s[::-1]
来源：http://dali.bjfxy.top/Article/details/gt2hjijvzdj.html

PHP:  $s === strrev($s);
来源：http://dali.bjfxy.top/Article/details/gt2zjfpedqi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rtrdrtvp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gt2jysbltpo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ehwqpu.com/Article/details/gt2qmihcfhj.html

Go:   // 双指针从两端比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aioogidl.html

Ruby: s == s.reverse
来源：http://dali.chenlongwang.top/Article/details/gt2jtdlmzhe.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gt2plfikwkl.html

[N07] 两数之和（返回下标）
来源：http://dali.jyoumei.cn/Article/details/gt2wkiopcru.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tian-w.cn/Article/details/gt2wvgfjbhj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tanke756.top/Article/details/gt2ykbibgoa.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dashuyun.cn/Article/details/gt2hydeqqwz.html

TS:   // 手写 Map<string, number>
来源：http://dali.xziqi.cn/Article/details/gt2tfnjanpe.html

Java: // 手写 HashMap
来源：http://dali.zycfv.cn/Article/details/gt2nayjvbdm.html

Go:   // 手写 map[int]int
来源：http://dali.hammf.cn/Article/details/gt2wgxwllze.html

Ruby: // 手写 Hash
来源：http://dali.gotoacloud.top/Article/details/gt2icyooxzx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dashuyun.cn/Article/details/gt2cfwanztb.html

[N08] 生成全排列
来源：http://dali.sweek.top/Article/details/gt2htlcjhqx.html

Py:   itertools.permutations(arr)
来源：http://dali.jianghu66.top/Article/details/gt2opevfbhq.html

PHP:  // 手写递归交换
来源：http://dali.havefunace.top/Article/details/gt2ywdsirjk.html

JS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2pfxyzxqe.html

TS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2mysojbis.html

Java: // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2mkfoslnx.html

Go:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2mdjflxho.html

Ruby: arr.permutation.to_a
来源：http://dali.chenlongwang.top/Article/details/gt2agcbwwrg.html

C#:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gt2wosqnyit.html

[N09] 栈与队列
来源：http://dali.daxiang520.top/Article/details/gt2ciabroin.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shzxlz.cn/Article/details/gt2tppgmwzx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.birdmap.top/Article/details/gt2raykkrfm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gt2dgkzvsut.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenjidiqi.icu/Article/details/gt2khpmycjm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sweek.top/Article/details/gt2qrvnjbku.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tianlin.xyz/Article/details/gt2zmowvkff.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gt2yoehqisr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cheryme.top/Article/details/gt2rveddond.html

[N10] 链表节点定义
来源：http://dali.tianlin.xyz/Article/details/gt2orbdfpan.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.havefunace.top/Article/details/gt2rhgrewtq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hammf.cn/Article/details/gt2ffvrogir.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sweek.top/Article/details/gt2shyujkuu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenlongwang.top/Article/details/gt2khezhwfe.html

Java: class Node { int v; Node next; }
来源：http://dali.tian-w.cn/Article/details/gt2wkxmyksq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yuanzhike.top/Article/details/gt2uusfyxcb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258888.top/Article/details/gt2tdvkkyny.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daria6918.cn/Article/details/gt2mhoirqlu.html

[N11] 二叉树中序遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2dhlrzhac.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jyoumei.cn/Article/details/gt2zmghetbi.html

PHP:  // 手写递归函数
来源：http://dali.jiagoushi.top/Article/details/gt2lctuxqpj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hywenlv.cn/Article/details/gt2dlzlewfs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gt2hrxhizaq.html

Java: // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gt2dczrlkka.html

Go:   // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gt2uqtnegtf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhongyouzk.top/Article/details/gt2xjpphsgp.html

C#:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gt2nutdigmk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ppjwa.cn/Article/details/gt2yccaqecs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gotoacloud.top/Article/details/gt2imgnrhag.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sweek.top/Article/details/gt2kopwnwco.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sysykeji.top/Article/details/gt2rxilmnze.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hammf.cn/Article/details/gt2uehdwyox.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gt2lhfbfkpz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xuanzx.com/Article/details/gt2agswackk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.0kj1m.cn/Article/details/gt2ptvxctdm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenzaomai.com/Article/details/gt2wggvzrce.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2upqqitfo.html

O. 并发与异步
来源：http://dali.nanxinkj.top/Article/details/gt2tidjqlpl.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2obyxrgvo.html

[O01] 启动一个线程
来源：http://dali.cucudq.cn/Article/details/gt2twupiizl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zdqjudy.top/Article/details/gt2ukekmfgg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dianchejie.cn/Article/details/gt2rxinrtvm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sysykeji.top/Article/details/gt2wqccgwgk.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gt2vjckbcjz.html

Java: new Thread(() -> f()).start()
来源：http://dali.xinyue.icu/Article/details/gt2bvbtxttz.html

Go:   go f()
来源：http://dali.quarkkingdee.top/Article/details/gt2bstycygd.html

Ruby: Thread.new { f }
来源：http://dali.tianlin.xyz/Article/details/gt2zlhamiih.html

C#:   Task.Run(() => F());
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zifieysv.html

[O02] 使用线程池
来源：http://dali.chenzaomai.com/Article/details/gt2txyhhnzn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jianghu66.top/Article/details/gt2jhtmmyaa.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhongyouzk.top/Article/details/gt2sxxfmlgn.html

JS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gt2jhzcqmud.html

TS:   // worker_threads 线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cwoyjefr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yvedp.cn/Article/details/gt2ntwggizs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cheryme.top/Article/details/gt2kmxhpnly.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cucudq.cn/Article/details/gt2dvozuocq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dubgxmlz.html

[O03] 加锁保护共享数据
来源：http://dali.xuetiantiany.cn/Article/details/gt2sddbeiao.html

Py:   with lock: shared += 1
来源：http://dali.sysykeji.top/Article/details/gt2khpyqcvn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj202588.top/Article/details/gt2xknigwzr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.c1oappe.top/Article/details/gt2wacjktxf.html

TS:   // 同 JS
来源：http://dali.ehwqpu.com/Article/details/gt2scitytwg.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gkgifygn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tianlin.xyz/Article/details/gt2lerimikd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hywenlv.cn/Article/details/gt2osyoynhs.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnxiangtu.top/Article/details/gt2zyvbswjh.html

[O04] 定义异步函数并等待
来源：http://dali.dianchejie.cn/Article/details/gt2zxhmdbzh.html

Py:   async def f():⏎    await g()
来源：http://dali.yueranfly.top/Article/details/gt2jgujbook.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.haohaochexian.top/Article/details/gt2qvwuoavb.html

JS:   async function f() { await g(); }
来源：http://dali.daria6918.cn/Article/details/gt2pabvqajd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jiagoushi.top/Article/details/gt2quhmvgsy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigfzy.top/Article/details/gt2qslieiot.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sweek.top/Article/details/gt2rwovfafl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnxiangtu.top/Article/details/gt2mcafqbvl.html

C#:   async Task F() { await G(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2mriqnrto.html

[O05] 并发执行并等待全部完成
来源：http://dali.ivvv.top/Article/details/gt2dadpbdwb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.smart0.xyz/Article/details/gt2hasrgkus.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.andypj.xyz/Article/details/gt2vzczjfdo.html

JS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gt2hmjdhipb.html

TS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gt2asmshjfg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2arglolro.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fengsongda.top/Article/details/gt2hwttgsvm.html

Ruby: threads.map(&:join)
来源：http://dali.mhx1999.top/Article/details/gt2mrfzjdxa.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenlongwang.top/Article/details/gt2milqzdsf.html

[O06] 使用进程池
来源：http://dali.cucudq.cn/Article/details/gt2rntueyss.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.haohaochexian.top/Article/details/gt2fxcnprwy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xziqi.cn/Article/details/gt2mhneslkk.html

JS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gt2btgdjoqy.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258888.top/Article/details/gt2aavlflbn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nanxuanxn.top/Article/details/gt2ttklkxgs.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yvedp.cn/Article/details/gt2yinqpzzo.html

Ruby: // fork 块
来源：http://dali.zhengqikj.top/Article/details/gt2ndkepmwb.html

C#:   Parallel.For
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xgxtjgnd.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2utpgocmf.html

P. 常用工具函数
来源：http://dali.hywenlv.cn/Article/details/gt2xznkpknl.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2ujgdvrbo.html

[P01] 生成 UUID
来源：http://dali.xinyue.icu/Article/details/gt2raqdfzqn.html

Py:   str(uuid.uuid4())
来源：http://dali.cashguo.top/Article/details/gt2cpazarpk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jyoumei.cn/Article/details/gt2glffiofh.html

JS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dtzkcxmi.html

TS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gt2wuuqesuv.html

Java: UUID.randomUUID().toString()
来源：http://dali.yongpay.top/Article/details/gt2nkawwotq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shangyingyoupin.top/Article/details/gt2mmbizdzw.html

Ruby: SecureRandom.uuid
来源：http://dali.tanke756.top/Article/details/gt2ajzrgrhi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhixingplan.top/Article/details/gt2ycskkuzy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shuidangran.top/Article/details/gt2kvvwkfct.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cucudq.cn/Article/details/gt2pckffzxn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2twualhmi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sxryk.cn/Article/details/gt2eanlkbmg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ydzc1.top/Article/details/gt2wgvxnnvd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.andypj.xyz/Article/details/gt2mdtdoyty.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eczxqonc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.guannengcc.top/Article/details/gt2xqdlhmhl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zdqjudy.top/Article/details/gt2fcrzaqso.html

[P03] 生成短随机字符串
来源：http://dali.jiagoushi.top/Article/details/gt2bcodlfvn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhiwuduotai.top/Article/details/gt2xtqvoaht.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.haohaochexian.top/Article/details/gt2lrbttreq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jiagoushi.top/Article/details/gt2jzdtkgmn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gt2sagkhcgq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hfpthk.cn/Article/details/gt2gmzlrtgv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tian-w.cn/Article/details/gt2acmcmhfv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.svipenyu.cn/Article/details/gt2bpsymoon.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.wangshuangyany.cn/Article/details/gt2fghvxjvs.html

[P04] 求长度
来源：http://dali.cashguo.top/Article/details/gt2ywpyohhs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinqigufen.top/Article/details/gt2nhhtegif.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gt2mcsymvss.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gt2vqhaajog.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shzxlz.cn/Article/details/gt2rvmnuigf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mconlrnc.html

Go:   len(arr);  len(m)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gevcjzzd.html

Ruby: x.length;  x.size
来源：http://dali.andypj.xyz/Article/details/gt2fjhofvue.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gogol.net.cn/Article/details/gt2kkcgjkoe.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhixingplan.top/Article/details/gt2qzgnltfb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.andypj.xyz/Article/details/gt2irfaairk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.snrcjt.cn/Article/details/gt2qytwkbff.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xuetiantiany.cn/Article/details/gt2ropbbrjy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2nqecvlqc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gmgcyznd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gt2xlvefbrh.html

Ruby: a == b
来源：http://dali.wangshuangyany.cn/Article/details/gt2oyrxqrlo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gotoacloud.top/Article/details/gt2savdjqne.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangdashe.top/Article/details/gt2xalauolg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cashguo.top/Article/details/gt2ktmcazdl.html

PHP:  if (empty($x)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2kpwvdaej.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zdqjudy.top/Article/details/gt2rtfdvqua.html

TS:   if (x == null) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2vzjyaann.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.c1oappe.top/Article/details/gt2bpbfmopf.html

Go:   if x == nil {}
来源：http://dali.ivvv.top/Article/details/gt2sfxsypzf.html


<!-- 参考信息 -->