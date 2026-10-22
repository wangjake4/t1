代发 wailian999

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2kujqknfl.html

[M01] 读取命令行参数
来源：http://dali.yangfankeji.com/Article/details/gt2nodxnshn.html

Py:   sys.argv[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wlzxjvkm.html

PHP:  $argv;  $argc;
来源：http://dali.dashuyun.cn/Article/details/gt2fdekcgay.html

JS:   process.argv.slice(2)
来源：http://dali.jqgfzy.top/Article/details/gt2hlwdatpa.html

TS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gt2nnprzdba.html

Java: args 数组（main 方法参数）
来源：http://dali.ivvv.top/Article/details/gt2whyfiwgo.html

Go:   os.Args[1:]
来源：http://dali.iojbl.cn/Article/details/gt2vjvykxpb.html

Ruby: ARGV
来源：http://dali.meibo888.top/Article/details/gt2dzjhjthh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gt2mdmrlsmc.html

[M02] 读取环境变量
来源：http://dali.ybcxt.top/Article/details/gt2zxgjzfqg.html

Py:   os.environ.get("HOME")
来源：http://dali.fzhhl.top/Article/details/gt2uzmpsqpg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.meibo888.top/Article/details/gt2hnryhfmy.html

JS:   process.env.HOME
来源：http://dali.snrcjt.cn/Article/details/gt2xrkmwegb.html

TS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gt2uxeuqmmd.html

Java: System.getenv("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2scidncjq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuanzx.com/Article/details/gt2qodbyvmd.html

Ruby: ENV["HOME"]
来源：http://dali.guowangkeji.top/Article/details/gt2etmnvpoh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shzxlz.cn/Article/details/gt2utyqfmvt.html

[M03] 执行外部命令
来源：http://dali.snrcjt.cn/Article/details/gt2oqlierfo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dianchejie.cn/Article/details/gt2xbqswgvk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yvedp.cn/Article/details/gt2fatgdxti.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cashguo.top/Article/details/gt2dxpqdmbn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gt2qfmkxfgt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yglhhguh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ocmldvsn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cashguo.top/Article/details/gt2jbddnpwe.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hammf.cn/Article/details/gt2wuxonmnc.html

[M04] 获取当前工作目录
来源：http://dali.hnxiangtu.top/Article/details/gt2ubmzpjnl.html

Py:   os.getcwd()
来源：http://dali.yuxming.cn/Article/details/gt2fktouluf.html

PHP:  getcwd();
来源：http://dali.tianlin.xyz/Article/details/gt2ybpvpsuw.html

JS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gt2qyoyssac.html

TS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gt2ssmnyasm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgufenzy.top/Article/details/gt2daefbmzc.html

Go:   os.Getwd()
来源：http://dali.zhengqikj.top/Article/details/gt2errdrjhv.html

Ruby: Dir.pwd
来源：http://dali.0kj1m.cn/Article/details/gt2jetshqzb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yongpay.top/Article/details/gt2djyosutq.html

[M05] 设置退出码
来源：http://dali.fzhhl.top/Article/details/gt2gqzodakg.html

Py:   sys.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2cltdcrar.html

PHP:  exit(1);
来源：http://dali.yonumen.top/Article/details/gt2zhufayug.html

JS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2zsjbzzew.html

TS:   process.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wzaizdrz.html

Java: System.exit(1)
来源：http://dali.fzhhl.top/Article/details/gt2smtqhqrk.html

Go:   os.Exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2mdkkcfjo.html

Ruby: exit 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2czyvzofa.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigufen.top/Article/details/gt2nximiehp.html

[M06] 向标准错误输出
来源：http://dali.yonumen.top/Article/details/gt2hevpupda.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nqueyfrm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhongyouzk.top/Article/details/gt2ribopguv.html

JS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gt2dzufjhih.html

TS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hczowbrs.html

Java: System.err.println("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hukmtyol.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yongpay.top/Article/details/gt2ifferxjs.html

Ruby: warn "err"
来源：http://dali.hywenlv.cn/Article/details/gt2wvpiyrbg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.redwolf501.top/Article/details/gt2vecrpaql.html

[M07] 判断是否为主入口
来源：http://dali.shuidangran.top/Article/details/gt2cfqbygds.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgufenzy.top/Article/details/gt2zfauwngj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yangfankeji.com/Article/details/gt2fooinjch.html

JS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gt2ublzdfzz.html

TS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gt2vwscligt.html

Java: public static void main(String[] args)
来源：http://dali.gzhubu.top/Article/details/gt2bwtjydgn.html

Go:   func main()
来源：http://dali.xylfe.cn/Article/details/gt2pshoztop.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhengqikj.top/Article/details/gt2ftbenltj.html

C#:   static void Main(string[] args)
来源：http://dali.zhengqikj.top/Article/details/gt2nypeygrr.html

[M08] 获取系统与运行时信息
来源：http://dali.jyoumei.cn/Article/details/gt2prrytpzl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hnqzawvl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.kuanghao11.cn/Article/details/gt2itsxkxmn.html

JS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gt2sjtjadrl.html

TS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gt2mceziosd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.smart0.xyz/Article/details/gt2wkrbhjld.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yvedp.cn/Article/details/gt2hqldmdhc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhengqikj.top/Article/details/gt2uojrwcnb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgfzy.top/Article/details/gt2dstdcojm.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2kabqwaih.html

N. 数据结构与算法
来源：http://dali.cucudq.cn/Article/details/gt2wsmvjxmt.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2dwekgacb.html

[N01] 二分查找（有序数组）
来源：http://dali.guannengcc.top/Article/details/gt2oqqcalmi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ehurzpok.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dianchejie.cn/Article/details/gt2eloddxem.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gt2apdbammw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gt2olffebpn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2uwntpqvl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2fbxiwlqb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hfpthk.cn/Article/details/gt2yzxwmgab.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2xzrrczwx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yongpay.top/Article/details/gt2vuxsmqna.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yonumen.top/Article/details/gt2fhzfbzff.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuxming.cn/Article/details/gt2qkmokwyv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gt2acytdber.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gt2jugbyggn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jiagoushi.top/Article/details/gt2hbtmbmiz.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2ozjfemsi.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gt2hkyeodvi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinqigufen.top/Article/details/gt2njycqazh.html

[N03] 快速排序（分治示例）
来源：http://dali.vqdsnc.cn/Article/details/gt2wiatrjtf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.bjfxy.top/Article/details/gt2siejjnnu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxinkj.top/Article/details/gt2cxsceyia.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gt2euhrwtgm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gt2exxajkqx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jyoumei.cn/Article/details/gt2zwrvfujt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cucudq.cn/Article/details/gt2zbpjvknu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yvedp.cn/Article/details/gt2geqdnyzd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.havefunace.top/Article/details/gt2mzdrkkdj.html

[N04] 斐波那契数列
来源：http://dali.gotoacloud.top/Article/details/gt2knmrhols.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yueranfly.top/Article/details/gt2atwprqqr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gt2mpcgvdbq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gt2kljaijlp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gt2uyadmtod.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.redwolf501.top/Article/details/gt2snpywyfs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.snrcjt.cn/Article/details/gt2wdcfyhvt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gt2rzglsbid.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gt2lryzbcgc.html

[N05] 最大公约数
来源：http://dali.yj20258.top/Article/details/gt2etpjbdjq.html

Py:   math.gcd(a, b)
来源：http://dali.gogol.net.cn/Article/details/gt2fdvajjnp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qozaqecn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gt2wvyrrwon.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gt2tqlzxggn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gaohongyu789.top/Article/details/gt2uiqzqwsc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yueranfly.top/Article/details/gt2zaihzxgp.html

Ruby: a.gcd(b)
来源：http://dali.aibaodan.cn/Article/details/gt2pgjxzbau.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.9152youxi.cn/Article/details/gt2nbbuyewn.html

[N06] 判断回文字符串
来源：http://dali.jyoumei.cn/Article/details/gt2tszlcwks.html

Py:   s == s[::-1]
来源：http://dali.fzhhl.top/Article/details/gt2qwharfxr.html

PHP:  $s === strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2hguonrut.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gt2yyylwrjt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gt2vfbnaztc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.316326.xyz/Article/details/gt2cvsfwzgo.html

Go:   // 双指针从两端比较
来源：http://dali.jqgfzy.top/Article/details/gt2hzrezpzh.html

Ruby: s == s.reverse
来源：http://dali.yj20258888.top/Article/details/gt2qqbecjoy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gt2ivnpilgf.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgufenzy.top/Article/details/gt2zfznpizu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fengsongda.top/Article/details/gt2uztpxlet.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhoulong.xyz/Article/details/gt2uexomlaz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhengqikj.top/Article/details/gt2eicgbigg.html

TS:   // 手写 Map<string, number>
来源：http://dali.xuanzx.com/Article/details/gt2usptfjqq.html

Java: // 手写 HashMap
来源：http://dali.yj20258888.top/Article/details/gt2khaipoku.html

Go:   // 手写 map[int]int
来源：http://dali.nanxinkj.top/Article/details/gt2gaugbwth.html

Ruby: // 手写 Hash
来源：http://dali.tanke756.top/Article/details/gt2wknlupxx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.mhx1999.top/Article/details/gt2nzwyguhk.html

[N08] 生成全排列
来源：http://dali.jqgufenzy.top/Article/details/gt2vryscjrr.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2qdnnsaxu.html

PHP:  // 手写递归交换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2knswblqx.html

JS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gt2dgqjabjz.html

TS:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gt2ojnedeku.html

Java: // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2vaodbhxm.html

Go:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gt2jlrsrznc.html

Ruby: arr.permutation.to_a
来源：http://dali.yvedp.cn/Article/details/gt2mxteqfba.html

C#:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gt2pwpykxop.html

[N09] 栈与队列
来源：http://dali.ybcxt.top/Article/details/gt2tweeejgk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sweek.top/Article/details/gt2hffcczkl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gt2rxluhgzt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gt2mxnagylo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yongpay.top/Article/details/gt2zgqvbyic.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.0kj1m.cn/Article/details/gt2wscxbkzh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxinkj.top/Article/details/gt2qklqenug.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gt2hdbiwqee.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gzhubu.top/Article/details/gt2wohqgfzl.html

[N10] 链表节点定义
来源：http://dali.zdqjudy.top/Article/details/gt2byrwzkyn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tanke756.top/Article/details/gt2mrnsurug.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sufxvd.cn/Article/details/gt2rslfgfwt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigufen.top/Article/details/gt2mnwdvmnl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tian-w.cn/Article/details/gt2eewkoczi.html

Java: class Node { int v; Node next; }
来源：http://dali.xuanzx.com/Article/details/gt2jnlwfzvj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pycfn.com/Article/details/gt2lwnldxap.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2imjkqsan.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258888.top/Article/details/gt2djvysmfg.html

[N11] 二叉树中序遍历
来源：http://dali.hysaishi.cn/Article/details/gt2qyiglnfe.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cqqwz.cn/Article/details/gt2gzohqnhv.html

PHP:  // 手写递归函数
来源：http://dali.gaohongyu789.top/Article/details/gt2qsbruwft.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gt2isdgbtfi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jiagoushi.top/Article/details/gt2tfwjowuk.html

Java: // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gt2kwtjaljr.html

Go:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gt2fukdkntp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuanzx.com/Article/details/gt2bwnpstuh.html

C#:   // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gt2rlkjphhl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hfpthk.cn/Article/details/gt2igyxbysx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2msncachf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xziqi.cn/Article/details/gt2uowhibxo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gt2cqjnhsdu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2omxihfxb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gt2rfjmqbbg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sysykeji.top/Article/details/gt2hbctzdjh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zjjlakmd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hfpthk.cn/Article/details/gt2dagzzxhp.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2myyocvld.html

O. 并发与异步
来源：http://dali.cqqwz.cn/Article/details/gt2jorpmlri.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2wdsnwyqb.html

[O01] 启动一个线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cicpqrsb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aibaodan.cn/Article/details/gt2kvnsetzs.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yongpay.top/Article/details/gt2pegebjgz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.316326.xyz/Article/details/gt2vdzenkvx.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gt2dxtgyqjp.html

Java: new Thread(() -> f()).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bvlfciyr.html

Go:   go f()
来源：http://dali.chenzaomai.com/Article/details/gt2pgctxbgk.html

Ruby: Thread.new { f }
来源：http://dali.andypj.xyz/Article/details/gt2runtwlvk.html

C#:   Task.Run(() => F());
来源：http://dali.0kj1m.cn/Article/details/gt2ccyggxnc.html

[O02] 使用线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jnonrmdd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.pycfn.com/Article/details/gt2pzvhthdj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hfpthk.cn/Article/details/gt2fkahfnvz.html

JS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gt2rmaddrpt.html

TS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gt2mxbavwkm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cucudq.cn/Article/details/gt2tzxgsrqe.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.316326.xyz/Article/details/gt2ozxzprxu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cashguo.top/Article/details/gt2ahxvcnhi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnqzz.top/Article/details/gt2kiwymaxn.html

[O03] 加锁保护共享数据
来源：http://dali.yonumen.top/Article/details/gt2weqogaqd.html

Py:   with lock: shared += 1
来源：http://dali.kuanghao11.cn/Article/details/gt2rzfklijd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cqqwz.cn/Article/details/gt2kthhklft.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cdnleiting.top/Article/details/gt2oulfvwdy.html

TS:   // 同 JS
来源：http://dali.sxryk.cn/Article/details/gt2oncxltkc.html

Java: synchronized (this) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gt2lwlxiuor.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yangfankeji.com/Article/details/gt2tydefyiu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgufenzy.top/Article/details/gt2dxftupwq.html

C#:   lock (gate) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gt2clkhlaxv.html

[O04] 定义异步函数并等待
来源：http://dali.aibaodan.cn/Article/details/gt2gkxwbuhd.html

Py:   async def f():⏎    await g()
来源：http://dali.yongpay.top/Article/details/gt2ynmxoofs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zdqjudy.top/Article/details/gt2mfbfxege.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258.top/Article/details/gt2gjbqvreu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aqnokmyd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuanzhike.top/Article/details/gt2snbemnpq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nwbrower.top/Article/details/gt2seyhrkld.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.birdmap.top/Article/details/gt2hyzptdyr.html

C#:   async Task F() { await G(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2ayplxdfo.html

[O05] 并发执行并等待全部完成
来源：http://dali.dashuyun.cn/Article/details/gt2qyqucqyx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yonumen.top/Article/details/gt2zehjmhfm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.snrcjt.cn/Article/details/gt2zhdxrcod.html

JS:   await Promise.all(tasks)
来源：http://dali.zycfv.cn/Article/details/gt2abqcplws.html

TS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gt2afjywxkf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sweek.top/Article/details/gt2mkvmptex.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zycfv.cn/Article/details/gt2aybkivoh.html

Ruby: threads.map(&:join)
来源：http://dali.316326.xyz/Article/details/gt2uuxrdexm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cheryme.top/Article/details/gt2kszredcu.html

[O06] 使用进程池
来源：http://dali.feifeiyinyue.top/Article/details/gt2grobwkkh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.quarkkingdee.top/Article/details/gt2xfgrdndx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guannengcc.top/Article/details/gt2xzymxvnn.html

JS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gt2abbwxlek.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258888.top/Article/details/gt2wtekozxv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yvedp.cn/Article/details/gt2pimvypnq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cheryme.top/Article/details/gt2kaxlrvrl.html

Ruby: // fork 块
来源：http://dali.jinghuilouyu.cn/Article/details/gt2osqexnhw.html

C#:   Parallel.For
来源：http://dali.dashuyun.cn/Article/details/gt2ydudvcuj.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2odauoqya.html

P. 常用工具函数
来源：http://dali.birdmap.top/Article/details/gt2ofuodums.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2zgaryysd.html

[P01] 生成 UUID
来源：http://dali.tanke756.top/Article/details/gt2wiqxhbys.html

Py:   str(uuid.uuid4())
来源：http://dali.yonumen.top/Article/details/gt2bezuodyg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuanzx.com/Article/details/gt2pghxhqbb.html

JS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gt2eodifcsw.html

TS:   crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gt2ruajplho.html

Java: UUID.randomUUID().toString()
来源：http://dali.sweek.top/Article/details/gt2lkmnnpxe.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgfzy.top/Article/details/gt2syjxgeit.html

Ruby: SecureRandom.uuid
来源：http://dali.guannengcc.top/Article/details/gt2uaanvysh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ydzc1.top/Article/details/gt2dgmvemfn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.9152youxi.cn/Article/details/gt2sqzunycf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gotoacloud.top/Article/details/gt2rfmxzobu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jyoumei.cn/Article/details/gt2tsxulrzc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hysaishi.cn/Article/details/gt2aouzjlgh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhoulong.xyz/Article/details/gt2hoknfpoh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gt2fbwpzqhz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tplfoggd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hammf.cn/Article/details/gt2bbunayfm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuanzx.com/Article/details/gt2dxybkrzh.html

[P03] 生成短随机字符串
来源：http://dali.iojbl.cn/Article/details/gt2bdlwdefk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cashguo.top/Article/details/gt2mfmoiyje.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xuanzx.com/Article/details/gt2pruiwzzo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gt2gqbxewmh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gt2tlhrlbdu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sysykeji.top/Article/details/gt2rvtdrgcf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tian-w.cn/Article/details/gt2yzdaaszy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hysaishi.cn/Article/details/gt2tiimsabn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shzxlz.cn/Article/details/gt2nsbbgkja.html

[P04] 求长度
来源：http://dali.gotoacloud.top/Article/details/gt2zbrgwlph.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2otdkjutl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gt2eyexcmjh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gt2sptmcuui.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gt2pmteymbl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cheryme.top/Article/details/gt2fqmqpzry.html

Go:   len(arr);  len(m)
来源：http://dali.sufxvd.cn/Article/details/gt2wzvfqfdn.html

Ruby: x.length;  x.size
来源：http://dali.hnqzz.top/Article/details/gt2okimtdqy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xylfe.cn/Article/details/gt2knfmckjn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jiagoushi.top/Article/details/gt2grmfcvrf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daria6918.cn/Article/details/gt2syiwqqyp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj20258888.top/Article/details/gt2wwksfsqc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.meibo888.top/Article/details/gt2mzyzxjgf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gogol.net.cn/Article/details/gt2vqyhhkzl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gogol.net.cn/Article/details/gt2tzweqbqf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jianghu66.top/Article/details/gt2jqberwru.html

Ruby: a == b
来源：http://dali.hammf.cn/Article/details/gt2oqcasgjo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.dianchejie.cn/Article/details/gt2jllgkhre.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.c1oappe.top/Article/details/gt2tjgudpql.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.kuanghao11.cn/Article/details/gt2zzpzknbz.html

PHP:  if (empty($x)) {}
来源：http://dali.svipenyu.cn/Article/details/gt2tblotiro.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2chpxfsrn.html

TS:   if (x == null) {}
来源：http://dali.yj202588.top/Article/details/gt2agxpgwrj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yonumen.top/Article/details/gt2ticpiaza.html

Go:   if x == nil {}
来源：http://dali.hfpthk.cn/Article/details/gt2dsjipjgy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tanke756.top/Article/details/gt2plnntnwr.html

C#:   if (x is null) {}
来源：http://dali.yj20258.top/Article/details/gt2zjpqnocw.html

[P07] 防抖与节流
来源：http://dali.fengsongda.top/Article/details/gt2ksvfemly.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.redwolf501.top/Article/details/gt2phubobcv.html


<!-- 参考信息 -->