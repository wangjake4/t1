代发 wailian999

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2aqchkzbb.html

[M01] 读取命令行参数
来源：http://dali.ydzc1.top/Article/details/gt2fjyijvoh.html

Py:   sys.argv[1:]
来源：http://dali.aizwys.cn/Article/details/gt2xtwnnrsb.html

PHP:  $argv;  $argc;
来源：http://dali.quarkkingdee.top/Article/details/gt2xrylpbof.html

JS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2njrfvytc.html

TS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gt2abnpitlb.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gt2ttkipzeg.html

Go:   os.Args[1:]
来源：http://dali.andypj.xyz/Article/details/gt2mqveqgwt.html

Ruby: ARGV
来源：http://dali.nanxinkj.top/Article/details/gt2czvbgzpu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sufxvd.cn/Article/details/gt2lygwbqwu.html

[M02] 读取环境变量
来源：http://dali.aizwys.cn/Article/details/gt2mdirgvse.html

Py:   os.environ.get("HOME")
来源：http://dali.cheryme.top/Article/details/gt2ggyhxujo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gt2ndfamkhg.html

JS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gt2izshgcdw.html

TS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gt2sjuykjwv.html

Java: System.getenv("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2wzokauct.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2nwxpglst.html

Ruby: ENV["HOME"]
来源：http://dali.smart0.xyz/Article/details/gt2tqieqxuo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.redwolf501.top/Article/details/gt2fkoskpuo.html

[M03] 执行外部命令
来源：http://dali.guowangkeji.top/Article/details/gt2sknfeamv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vnorxgzz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yonumen.top/Article/details/gt2nqyajhjb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gt2qjujlely.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gt2gkrmvcvt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258.top/Article/details/gt2eqmkning.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.bjfxy.top/Article/details/gt2opqjhwwt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.smart0.xyz/Article/details/gt2cbhupimz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guowangkeji.top/Article/details/gt2ocmwkwuz.html

[M04] 获取当前工作目录
来源：http://dali.gotoacloud.top/Article/details/gt2glsygcae.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gt2bbwpcjaz.html

PHP:  getcwd();
来源：http://dali.yueranfly.top/Article/details/gt2pvljbagt.html

JS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gt2apfrefkc.html

TS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gt2ulldwjqr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aibaodan.cn/Article/details/gt2fsdqorvx.html

Go:   os.Getwd()
来源：http://dali.jinqigfzy.top/Article/details/gt2fsseayoy.html

Ruby: Dir.pwd
来源：http://dali.wangdashe.top/Article/details/gt2nhrmguek.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.mhx1999.top/Article/details/gt2twjespik.html

[M05] 设置退出码
来源：http://dali.sysykeji.top/Article/details/gt2sjaaoixn.html

Py:   sys.exit(1)
来源：http://dali.nwbrower.top/Article/details/gt2gkbyxvov.html

PHP:  exit(1);
来源：http://dali.jqgfzy.top/Article/details/gt2pvshnygc.html

JS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gt2lsxsbndn.html

TS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2xwryhkel.html

Java: System.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gt2owrteeit.html

Go:   os.Exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2yrcuqtmg.html

Ruby: exit 1
来源：http://dali.yj20258888.top/Article/details/gt2zcrmkqjw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.havefunace.top/Article/details/gt2faorvhwk.html

[M06] 向标准错误输出
来源：http://dali.jiagoushi.top/Article/details/gt2esuqvkpz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.iojbl.cn/Article/details/gt2roocqxzu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yongpay.top/Article/details/gt2qjrljskd.html

JS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gt2vaqbauti.html

TS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qlxtagso.html

Java: System.err.println("err")
来源：http://dali.yonumen.top/Article/details/gt2natflktv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.snrcjt.cn/Article/details/gt2vyoakpyw.html

Ruby: warn "err"
来源：http://dali.snrcjt.cn/Article/details/gt2qtmbgxzy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.iojbl.cn/Article/details/gt2uxhvnhsq.html

[M07] 判断是否为主入口
来源：http://dali.gzhubu.top/Article/details/gt2ftigryqw.html

Py:   if __name__ == "__main__":
来源：http://dali.daria6918.cn/Article/details/gt2nqqgstxz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.svipenyu.cn/Article/details/gt2hvnrtjqx.html

JS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gt2zdplmubc.html

TS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gt2zoovqpxq.html

Java: public static void main(String[] args)
来源：http://dali.jiagoushi.top/Article/details/gt2iwjqxpuk.html

Go:   func main()
来源：http://dali.iojbl.cn/Article/details/gt2zlbxshzl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangdashe.top/Article/details/gt2vnbjwizn.html

C#:   static void Main(string[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gt2idbzlers.html

[M08] 获取系统与运行时信息
来源：http://dali.dashuyun.cn/Article/details/gt2wfwfqned.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yanxiufei.cn/Article/details/gt2kzmcpdmg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dashuyun.cn/Article/details/gt2dlqazptp.html

JS:   process.platform;  process.version
来源：http://dali.yuxming.cn/Article/details/gt2kalxgbuw.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2vqacihdv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gotoacloud.top/Article/details/gt2hpylmkjv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.andypj.xyz/Article/details/gt2sonwqsuf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhongyouzk.top/Article/details/gt2mzeqfniq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shuidangran.top/Article/details/gt2bqnmufsy.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2lbfsfhsi.html

N. 数据结构与算法
来源：http://dali.cheryme.top/Article/details/gt2fzhmubzu.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2atosjrsw.html

[N01] 二分查找（有序数组）
来源：http://dali.zycfv.cn/Article/details/gt2bgeddjge.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2xztxnicu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gotoacloud.top/Article/details/gt2mwvygsvu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gt2ojlklvhv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gt2klnfunrn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2jtebxdco.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2zszyjslj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shzxlz.cn/Article/details/gt2clambmbn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gt2uznkzeeh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ppjwa.cn/Article/details/gt2xfdpltkb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gaohongyu789.top/Article/details/gt2gsnhipyk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.guannengcc.top/Article/details/gt2lawtemvy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gt2qeuiubhg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gt2hzdmwffo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daxiang520.top/Article/details/gt2lalzfhbx.html

Go:   slices.Sort(arr)
来源：http://dali.sweek.top/Article/details/gt2gkkuctde.html

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gt2jexyrsma.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gogol.net.cn/Article/details/gt2kclpjcra.html

[N03] 快速排序（分治示例）
来源：http://dali.hysaishi.cn/Article/details/gt2okoszhqe.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgufenzy.top/Article/details/gt2uaegyicr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuanzx.com/Article/details/gt2mvbkrlwc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.redwolf501.top/Article/details/gt2xzmidpij.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.0kj1m.cn/Article/details/gt2uybujpxo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gotoacloud.top/Article/details/gt2ldwrtglh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ppjwa.cn/Article/details/gt2ovmccneq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258.top/Article/details/gt2prutcnsd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guowangkeji.top/Article/details/gt2wgvwukko.html

[N04] 斐波那契数列
来源：http://dali.hongshengwenyu.top/Article/details/gt2fgnrehzt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gt2usvqbwan.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.birdmap.top/Article/details/gt2lyhsafnb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2skxijobz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gt2pcfownjp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cheryme.top/Article/details/gt2yfnxdjqr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxuanxn.top/Article/details/gt2znefmrbh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tianlin.xyz/Article/details/gt2eoebgdnf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gt2lvfszmcz.html

[N05] 最大公约数
来源：http://dali.yuxming.cn/Article/details/gt2mayekznc.html

Py:   math.gcd(a, b)
来源：http://dali.shuidangran.top/Article/details/gt2rhuiaiks.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhongyouzk.top/Article/details/gt2vfkzrdou.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xafdeyrl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gt2cbcgtcfb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.birdmap.top/Article/details/gt2ifhhgvxq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.wangdashe.top/Article/details/gt2doswcdew.html

Ruby: a.gcd(b)
来源：http://dali.jianghu66.top/Article/details/gt2xvwcisby.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.pycfn.com/Article/details/gt2eeyfwaeq.html

[N06] 判断回文字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2trhsscpf.html

Py:   s == s[::-1]
来源：http://dali.gzhubu.top/Article/details/gt2lngppfcb.html

PHP:  $s === strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gt2bjobpgqs.html

JS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gt2fbesdcnh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pvxuylvl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.c1oappe.top/Article/details/gt2bzxrwxkn.html

Go:   // 双指针从两端比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2fryyglsc.html

Ruby: s == s.reverse
来源：http://dali.9152youxi.cn/Article/details/gt2wljxdtxr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigufen.top/Article/details/gt2kjaisemi.html

[N07] 两数之和（返回下标）
来源：http://dali.snrcjt.cn/Article/details/gt2ahoiuomg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tanke756.top/Article/details/gt2jgdusigs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.feifeiyinyue.top/Article/details/gt2kntwdzbu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.guannengcc.top/Article/details/gt2vmqhpmjh.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuxming.cn/Article/details/gt2kwoakaeu.html

Java: // 手写 HashMap
来源：http://dali.cqqwz.cn/Article/details/gt2kyegtqsp.html

Go:   // 手写 map[int]int
来源：http://dali.cashguo.top/Article/details/gt2iplfytmd.html

Ruby: // 手写 Hash
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wdpyonjp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cheryme.top/Article/details/gt2lqwtyefs.html

[N08] 生成全排列
来源：http://dali.316326.xyz/Article/details/gt2lcpizrjx.html

Py:   itertools.permutations(arr)
来源：http://dali.redwolf501.top/Article/details/gt2wnkmyccc.html

PHP:  // 手写递归交换
来源：http://dali.vqdsnc.cn/Article/details/gt2kjzizwfl.html

JS:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lkwdrwcq.html

TS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gt2pbszxhnq.html

Java: // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gt2gufvdgvs.html

Go:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gt2odomyfih.html

Ruby: arr.permutation.to_a
来源：http://dali.shuidangran.top/Article/details/gt2wxosildk.html

C#:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gt2jxbuyrsp.html

[N09] 栈与队列
来源：http://dali.aizwys.cn/Article/details/gt2mntqapnn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.birdmap.top/Article/details/gt2iygwjltv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gt2shypjvnn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gt2gfmsvsit.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.mhx1999.top/Article/details/gt2ieuryufl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cdnleiting.top/Article/details/gt2flnlkccu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangshuangyany.cn/Article/details/gt2otbghjtx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.c1oappe.top/Article/details/gt2qszmfyev.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daxiang520.top/Article/details/gt2majbbzeb.html

[N10] 链表节点定义
来源：http://dali.hnxiangtu.top/Article/details/gt2ltygepjz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jlsjyb.cn/Article/details/gt2fwyrnavz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cqqwz.cn/Article/details/gt2pxlpynec.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zycfv.cn/Article/details/gt2vfljaiie.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hammf.cn/Article/details/gt2krgpscue.html

Java: class Node { int v; Node next; }
来源：http://dali.xinyue.icu/Article/details/gt2jmbvuxfc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jiagoushi.top/Article/details/gt2bkdmhnzn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgufenzy.top/Article/details/gt2fxxqdqts.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinqigfzy.top/Article/details/gt2umrmlipb.html

[N11] 二叉树中序遍历
来源：http://dali.hywenlv.cn/Article/details/gt2yifqdpde.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fengsongda.top/Article/details/gt2hqjawqol.html

PHP:  // 手写递归函数
来源：http://dali.cdnleiting.top/Article/details/gt2cmxffwia.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gt2okekfmqb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gt2vocxokvt.html

Java: // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gt2ucozzsyn.html

Go:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gt2inxxgchq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yueranfly.top/Article/details/gt2unyrrajv.html

C#:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gt2vevauhoc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhengqikj.top/Article/details/gt2iswewami.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhiwuduotai.top/Article/details/gt2qigzwthp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.pycfn.com/Article/details/gt2dylsbrtz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gt2otgsbuvl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ftmxuilc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gt2lbmxamlg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenjidiqi.icu/Article/details/gt2bkxqenti.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daxiang520.top/Article/details/gt2nlwzydfm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjqhick.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2aplxgije.html

O. 并发与异步
来源：http://dali.hnxiangtu.top/Article/details/gt2ymozygzt.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cjnjugbl.html

[O01] 启动一个线程
来源：http://dali.jianghu66.top/Article/details/gt2lrdowlqh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fawfecgd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.daxiang520.top/Article/details/gt2pineqyxr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hongshengwenyu.top/Article/details/gt2dpdpanlu.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gt2elyvkwwm.html

Java: new Thread(() -> f()).start()
来源：http://dali.aizwys.cn/Article/details/gt2xzrmdmuj.html

Go:   go f()
来源：http://dali.wangshuangyany.cn/Article/details/gt2gxijdxfj.html

Ruby: Thread.new { f }
来源：http://dali.xuanzx.com/Article/details/gt2cogizveb.html

C#:   Task.Run(() => F());
来源：http://dali.cucudq.cn/Article/details/gt2klavygek.html

[O02] 使用线程池
来源：http://dali.fengsongda.top/Article/details/gt2yrgrqgfj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.daxiang520.top/Article/details/gt2ggpacrzb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xuetiantiany.cn/Article/details/gt2btasibiy.html

JS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gt2miqftzuc.html

TS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gt2pwlvxonq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yuanzhike.top/Article/details/gt2ncirdnzv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangshuangyany.cn/Article/details/gt2ieouprxd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ivvv.top/Article/details/gt2cldbnkxl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.bjfxy.top/Article/details/gt2hrpnuztg.html

[O03] 加锁保护共享数据
来源：http://dali.havefunace.top/Article/details/gt2hxbqgtrc.html

Py:   with lock: shared += 1
来源：http://dali.aizwys.cn/Article/details/gt2yfiokqsg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenjidiqi.icu/Article/details/gt2nxgngfun.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.aizwys.cn/Article/details/gt2hydiupuu.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gt2qwdnveca.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gt2xffmalyq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shzxlz.cn/Article/details/gt2mfisvszt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ieznjysf.html

C#:   lock (gate) { shared++; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2pakpidbs.html

[O04] 定义异步函数并等待
来源：http://dali.yongpay.top/Article/details/gt2pngkmvkf.html

Py:   async def f():⏎    await g()
来源：http://dali.sweek.top/Article/details/gt2seovmwfb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.haohaochexian.top/Article/details/gt2vhfomlzc.html

JS:   async function f() { await g(); }
来源：http://dali.sysykeji.top/Article/details/gt2jmaapbxe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sysykeji.top/Article/details/gt2pobesdbl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cheryme.top/Article/details/gt2qcejbqof.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.pycfn.com/Article/details/gt2hezusfao.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nwbrower.top/Article/details/gt2tjpxopzh.html

C#:   async Task F() { await G(); }
来源：http://dali.ydzc1.top/Article/details/gt2vifljncw.html

[O05] 并发执行并等待全部完成
来源：http://dali.cashguo.top/Article/details/gt2ktathksn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.snrcjt.cn/Article/details/gt2ufaojkhe.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sufxvd.cn/Article/details/gt2casngfai.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2itmxjmvf.html

TS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gt2aypptqwn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nnzqhact.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xziqi.cn/Article/details/gt2vcyouznn.html

Ruby: threads.map(&:join)
来源：http://dali.zhengqikj.top/Article/details/gt2dvowckit.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xylfe.cn/Article/details/gt2byuemifj.html

[O06] 使用进程池
来源：http://dali.jianghu66.top/Article/details/gt2bkwxgwsz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tian-w.cn/Article/details/gt2ebwswelq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tanke756.top/Article/details/gt2crqrdqvn.html

JS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gt2nsfulzuy.html

TS:   // child_process / cluster 模块
来源：http://dali.gaohongyu789.top/Article/details/gt2bsbtlabe.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fzhhl.top/Article/details/gt2tqyfecpx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xylfe.cn/Article/details/gt2nhwinutq.html

Ruby: // fork 块
来源：http://dali.ppjwa.cn/Article/details/gt2kxwvbqig.html

C#:   Parallel.For
来源：http://dali.yonumen.top/Article/details/gt2huvhpfeh.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2fcvqxtge.html

P. 常用工具函数
来源：http://dali.jiagoushi.top/Article/details/gt2estckpxa.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2levwvvfe.html

[P01] 生成 UUID
来源：http://dali.ehwqpu.com/Article/details/gt2wrjhhvts.html

Py:   str(uuid.uuid4())
来源：http://dali.mhx1999.top/Article/details/gt2naimrpbm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cdnleiting.top/Article/details/gt2pmioaueo.html

JS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gt2xiaxrcet.html

TS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gt2aivrimxj.html

Java: UUID.randomUUID().toString()
来源：http://dali.jyoumei.cn/Article/details/gt2rznxwnyt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinqigufen.top/Article/details/gt2bblbpijs.html

Ruby: SecureRandom.uuid
来源：http://dali.9152youxi.cn/Article/details/gt2mngbufar.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gaohongyu789.top/Article/details/gt2wgajfcdx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ivvv.top/Article/details/gt2cukoxxkf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.haohaochexian.top/Article/details/gt2sriqawpp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tanke756.top/Article/details/gt2iqndyveo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hammf.cn/Article/details/gt2ixpwrvfv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.kuanghao11.cn/Article/details/gt2ymetqqhj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gt2vcgspjdq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.birdmap.top/Article/details/gt2igopufvc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.haohaochexian.top/Article/details/gt2igdiukem.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.9152youxi.cn/Article/details/gt2iqkxerdl.html

[P03] 生成短随机字符串
来源：http://dali.xuanzx.com/Article/details/gt2rchxcsyz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hfpthk.cn/Article/details/gt2vzezkotb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinqigufen.top/Article/details/gt2azxugxwu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xinyue.icu/Article/details/gt2jjpwdljm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gogol.net.cn/Article/details/gt2asxztlrz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnqzz.top/Article/details/gt2pllnrzdq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.0kj1m.cn/Article/details/gt2hkmkdizm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxinkj.top/Article/details/gt2pwcmdfoa.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.smart0.xyz/Article/details/gt2jihpgxfd.html

[P04] 求长度
来源：http://dali.ydzc1.top/Article/details/gt2ugwvsgnk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zycfv.cn/Article/details/gt2pyydjhni.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gt2grecdcus.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yueranfly.top/Article/details/gt2adxkrcka.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pycfn.com/Article/details/gt2ipisjxcf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cheryme.top/Article/details/gt2zrfnwwbf.html

Go:   len(arr);  len(m)
来源：http://dali.ybcxt.top/Article/details/gt2rtksmkoh.html

Ruby: x.length;  x.size
来源：http://dali.hfpthk.cn/Article/details/gt2rdzponlv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hysaishi.cn/Article/details/gt2adumdgaf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.svipenyu.cn/Article/details/gt2teqxvlfe.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ksuykauz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dashuyun.cn/Article/details/gt2cwrqzevx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.iojbl.cn/Article/details/gt2jzgzjiil.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fengsongda.top/Article/details/gt2ttzlicum.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.svipenyu.cn/Article/details/gt2mnwomobg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gt2dnophsep.html

Ruby: a == b
来源：http://dali.ivvv.top/Article/details/gt2ezgkrolw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xylfe.cn/Article/details/gt2ohetlkkf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xylfe.cn/Article/details/gt2mgfmjyrd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.kuanghao11.cn/Article/details/gt2kxzdiscu.html

PHP:  if (empty($x)) {}
来源：http://dali.wangdashe.top/Article/details/gt2dtkixaax.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.kuanghao11.cn/Article/details/gt2wyxlftvn.html

TS:   if (x == null) {}
来源：http://dali.ybcxt.top/Article/details/gt2gburdjth.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2pmhzmwyx.html

Go:   if x == nil {}
来源：http://dali.svipenyu.cn/Article/details/gt2qghrshum.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yanxiufei.cn/Article/details/gt2uzidadme.html

C#:   if (x is null) {}
来源：http://dali.yuxming.cn/Article/details/gt2itrlvdpr.html

[P07] 防抖与节流
来源：http://dali.ppjwa.cn/Article/details/gt2dpgzuhcl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yuanzhike.top/Article/details/gt2mtanmcdl.html


<!-- 参考信息 -->