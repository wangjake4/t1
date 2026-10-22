代发 wailian999

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtlamkqdbt.html

[M01] 读取命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtobpkylpa.html

Py:   sys.argv[1:]
来源：http://dali.0kj1m.cn/Article/details/gtcufdjkkq.html

PHP:  $argv;  $argc;
来源：http://dali.vqdsnc.cn/Article/details/gtkhrmpqsn.html

JS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtvfqschse.html

TS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gtqyxkqoqo.html

Java: args 数组（main 方法参数）
来源：http://dali.316326.xyz/Article/details/gtbysmerfk.html

Go:   os.Args[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtwxalvpgz.html

Ruby: ARGV
来源：http://dali.chenzaomai.com/Article/details/gtjkpmxawm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gtsvblaxcy.html

[M02] 读取环境变量
来源：http://dali.zycfv.cn/Article/details/gtwpyawnfp.html

Py:   os.environ.get("HOME")
来源：http://dali.gzhubu.top/Article/details/gtketgwsrh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gtyolbtxzl.html

JS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gtuobjgypa.html

TS:   process.env.HOME
来源：http://dali.snrcjt.cn/Article/details/gtsjsfdqll.html

Java: System.getenv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gthjxzbzae.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtdmidnsin.html

Ruby: ENV["HOME"]
来源：http://dali.zhoulong.xyz/Article/details/gtjrzinrki.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.c1oappe.top/Article/details/gtywojyeor.html

[M03] 执行外部命令
来源：http://dali.pycfn.com/Article/details/gttnvmqibx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pycfn.com/Article/details/gtacblvyqj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pycfn.com/Article/details/gtpmsgatxa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gtljtmtxpq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gtspitcyrw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shuidangran.top/Article/details/gtrahrqcks.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shuidangran.top/Article/details/gtugxbywtg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zycfv.cn/Article/details/gtljdgueab.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zycfv.cn/Article/details/gtibijalaw.html

[M04] 获取当前工作目录
来源：http://dali.chenlongwang.top/Article/details/gtwrsjijic.html

Py:   os.getcwd()
来源：http://dali.shuidangran.top/Article/details/gtedpxxfzb.html

PHP:  getcwd();
来源：http://dali.guowangkeji.top/Article/details/gtuxrfvfnp.html

JS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsvntbsg.html

TS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gthymktyyn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cucudq.cn/Article/details/gtrpbfmqgh.html

Go:   os.Getwd()
来源：http://dali.jqgufenzy.top/Article/details/gtqhudebjn.html

Ruby: Dir.pwd
来源：http://dali.yj20258888.top/Article/details/gtecxciyxk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuetiantiany.cn/Article/details/gtxplkjxmr.html

[M05] 设置退出码
来源：http://dali.feifeiyinyue.top/Article/details/gtbdocqovf.html

Py:   sys.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtvfqzrvpk.html

PHP:  exit(1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfornqrva.html

JS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtylmyblkl.html

TS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtnobcyqsl.html

Java: System.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtrdntbidt.html

Go:   os.Exit(1)
来源：http://dali.smart0.xyz/Article/details/gtyhdkwfhf.html

Ruby: exit 1
来源：http://dali.cucudq.cn/Article/details/gtvhbixqpq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.feifeiyinyue.top/Article/details/gtjafyfogp.html

[M06] 向标准错误输出
来源：http://dali.hfpthk.cn/Article/details/gtamyppmtp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnqzz.top/Article/details/gthhxmlrmf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.iojbl.cn/Article/details/gtmecfujhg.html

JS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gtlwykoyse.html

TS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gtnzfokejj.html

Java: System.err.println("err")
来源：http://dali.hfpthk.cn/Article/details/gtiogaotne.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjllxfxh.html

Ruby: warn "err"
来源：http://dali.jlsjyb.cn/Article/details/gtglnrqqss.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ehwqpu.com/Article/details/gtflvcaufs.html

[M07] 判断是否为主入口
来源：http://dali.yvedp.cn/Article/details/gtopytbrjw.html

Py:   if __name__ == "__main__":
来源：http://dali.hnxiangtu.top/Article/details/gttjowubhm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhixingplan.top/Article/details/gtvupukuoe.html

JS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtfivrbqcx.html

TS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gtyfxriiyl.html

Java: public static void main(String[] args)
来源：http://dali.shzxlz.cn/Article/details/gtedmxchze.html

Go:   func main()
来源：http://dali.snrcjt.cn/Article/details/gtetepchyh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ybcxt.top/Article/details/gtfrvjmncq.html

C#:   static void Main(string[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gtlcmxyqqi.html

[M08] 获取系统与运行时信息
来源：http://dali.nanxuanxn.top/Article/details/gtwbxdykmg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhiwuduotai.top/Article/details/gtvcsrsemf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guannengcc.top/Article/details/gtyvpmjayv.html

JS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gttrnqhgqa.html

TS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtohnawhvd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258.top/Article/details/gtllqlznxp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.wangdashe.top/Article/details/gtkoycbkkk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzscsbrm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhiwuduotai.top/Article/details/gtysazkrwq.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtdutgjmye.html

N. 数据结构与算法
来源：http://dali.nwbrower.top/Article/details/gtwvjbeodl.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtvbujhjni.html

[N01] 二分查找（有序数组）
来源：http://dali.zhixingplan.top/Article/details/gtcmybwfjw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtfritwung.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sysykeji.top/Article/details/gtgmoskohg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtqgoltziu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gtnqsubzji.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtbtufzzae.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtvymtwtzj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cashguo.top/Article/details/gtvjladvpi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtupgqlkmq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dashuyun.cn/Article/details/gtslypmkzz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gtavmibomk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.redwolf501.top/Article/details/gtpilcpmve.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.redwolf501.top/Article/details/gtqcexudln.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgejaqqsk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cdnleiting.top/Article/details/gttrltneex.html

Go:   slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gtgebxnxdl.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gtrqppuqwp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daxiang520.top/Article/details/gtgzoiwtdk.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxuanxn.top/Article/details/gtvjvijyig.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.dashuyun.cn/Article/details/gtvkiqhqfd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlvqroxu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gtzdrbrcob.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gtvnghlroc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sysykeji.top/Article/details/gtzerlhucs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gtomikomau.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwfcsfyp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtzckemrna.html

[N04] 斐波那契数列
来源：http://dali.zdqjudy.top/Article/details/gtagygchtj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gtsocelfgx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258888.top/Article/details/gtkyxlwqsq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtnyiajxth.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtparvulos.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gtebwplevx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuanzhike.top/Article/details/gtreqnpwib.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gtxhlpgugy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtwnemnegf.html

[N05] 最大公约数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyegeuxfi.html

Py:   math.gcd(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtctbxeohp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtuiulhhzm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtlxixjwsy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yueranfly.top/Article/details/gtksxzbhlp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hysaishi.cn/Article/details/gtyicilpoo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenzaomai.com/Article/details/gtjarbwwqi.html

Ruby: a.gcd(b)
来源：http://dali.hywenlv.cn/Article/details/gtwiajpleg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.aizwys.cn/Article/details/gtkopqvozb.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gthyxyptnz.html

Py:   s == s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcnmshom.html

PHP:  $s === strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gtftejrelq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtllwrhxsy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtvzsljrtr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aizwys.cn/Article/details/gtjmfirtmq.html

Go:   // 双指针从两端比较
来源：http://dali.yj202588.top/Article/details/gtyqrwslvy.html

Ruby: s == s.reverse
来源：http://dali.cashguo.top/Article/details/gtwolddwro.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gtvvfdodom.html

[N07] 两数之和（返回下标）
来源：http://dali.birdmap.top/Article/details/gtnmreuoqa.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yueranfly.top/Article/details/gtnphalxjl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.daxiang520.top/Article/details/gtpyrtphkd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.feifeiyinyue.top/Article/details/gtxrxzefzt.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxuanxn.top/Article/details/gthctnfnjd.html

Java: // 手写 HashMap
来源：http://dali.zycfv.cn/Article/details/gtbxibjsfc.html

Go:   // 手写 map[int]int
来源：http://dali.xziqi.cn/Article/details/gtstgrqhir.html

Ruby: // 手写 Hash
来源：http://dali.gogol.net.cn/Article/details/gtmzklksbg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenjidiqi.icu/Article/details/gtpxnedcut.html

[N08] 生成全排列
来源：http://dali.gaohongyu789.top/Article/details/gtjxveyovj.html

Py:   itertools.permutations(arr)
来源：http://dali.hfpthk.cn/Article/details/gtrjxzttjo.html

PHP:  // 手写递归交换
来源：http://dali.ppjwa.cn/Article/details/gtrjmnwkwg.html

JS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtyphpjfrh.html

TS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtdropugyi.html

Java: // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtuokwznlj.html

Go:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtcmyngfdi.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gtzydhpzqd.html

C#:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtdzbnrcyv.html

[N09] 栈与队列
来源：http://dali.ivvv.top/Article/details/gtkymewxsk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtoqxsvrar.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtsylcaapk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xylfe.cn/Article/details/gtsxuujgbk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.mhx1999.top/Article/details/gtoduectvt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.svipenyu.cn/Article/details/gtogcsxdem.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hysaishi.cn/Article/details/gtxjxvnfhg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258888.top/Article/details/gtruqvljfl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.vqdsnc.cn/Article/details/gtytztgnvz.html

[N10] 链表节点定义
来源：http://dali.guannengcc.top/Article/details/gtelgrljfa.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xziqi.cn/Article/details/gtexesicze.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sxryk.cn/Article/details/gtfumjdfux.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.meibo888.top/Article/details/gtbzrdxmrq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hnxiangtu.top/Article/details/gtykudwkin.html

Java: class Node { int v; Node next; }
来源：http://dali.jianghu66.top/Article/details/gtloplbcur.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nanxuanxn.top/Article/details/gtsgbujjhe.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgufenzy.top/Article/details/gtmlmsygjj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cqqwz.cn/Article/details/gtbmkycavd.html

[N11] 二叉树中序遍历
来源：http://dali.zhiwuduotai.top/Article/details/gttxqagjqg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.mhx1999.top/Article/details/gtialhxwmw.html

PHP:  // 手写递归函数
来源：http://dali.zycfv.cn/Article/details/gtofoknmwd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gthctyvamx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gtpmpsrhhb.html

Java: // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gtlrzqnqln.html

Go:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gtpsdydohj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinqigfzy.top/Article/details/gtlzfrklss.html

C#:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gtotfrfuwx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.vqdsnc.cn/Article/details/gtqgrdmdoy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cheryme.top/Article/details/gtrebupdtn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gtpvxawalh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gtibqzeqig.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangtech.top/Article/details/gthkhaicmk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gtdhmdhazf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtltxpzcar.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.birdmap.top/Article/details/gthngmrdyc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gtnxmzwjtm.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtsonvkknp.html

O. 并发与异步
来源：http://dali.jiagoushi.top/Article/details/gtumfwiqjp.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtkhanhnqp.html

[O01] 启动一个线程
来源：http://dali.smart0.xyz/Article/details/gtprlwpnkq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yongpay.top/Article/details/gtnhkokpuw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.svipenyu.cn/Article/details/gtblpxnvuc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cheryme.top/Article/details/gtvbzomjsg.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gtaejqlftz.html

Java: new Thread(() -> f()).start()
来源：http://dali.xuetiantiany.cn/Article/details/gtocavutei.html

Go:   go f()
来源：http://dali.jianghu66.top/Article/details/gtpkonphvr.html

Ruby: Thread.new { f }
来源：http://dali.zhongyouzk.top/Article/details/gtdeowkqki.html

C#:   Task.Run(() => F());
来源：http://dali.guannengcc.top/Article/details/gtwtyowgla.html

[O02] 使用线程池
来源：http://dali.yueranfly.top/Article/details/gtfyexszch.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jiagoushi.top/Article/details/gtigctazup.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgfzy.top/Article/details/gtcomginke.html

JS:   // worker_threads 线程池
来源：http://dali.jqgufenzy.top/Article/details/gtmgnydeoa.html

TS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gtsrcwwyby.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.9152youxi.cn/Article/details/gthwxxwxam.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxinkj.top/Article/details/gtlzscbtkr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cucudq.cn/Article/details/gtyojevymr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.quarkkingdee.top/Article/details/gtqqcauwjc.html

[O03] 加锁保护共享数据
来源：http://dali.daria6918.cn/Article/details/gtwykinwhb.html

Py:   with lock: shared += 1
来源：http://dali.gzhubu.top/Article/details/gtfhygvprb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ydzc1.top/Article/details/gtbcslssmi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.feifeiyinyue.top/Article/details/gtwrrevmni.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gtquzfrkoe.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtrlqivkuu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenzaomai.com/Article/details/gtwjpkgmew.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.fengsongda.top/Article/details/gtrdymfkor.html

C#:   lock (gate) { shared++; }
来源：http://dali.ivvv.top/Article/details/gtlcxilfqq.html

[O04] 定义异步函数并等待
来源：http://dali.dianchejie.cn/Article/details/gtivtsfgib.html

Py:   async def f():⏎    await g()
来源：http://dali.dashuyun.cn/Article/details/gtujigjtzy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.haohaochexian.top/Article/details/gtxafjlznz.html

JS:   async function f() { await g(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtawgcjogn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gtxtjbodpf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinghuilouyu.cn/Article/details/gtebcqzsky.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258.top/Article/details/gtgkcshnsj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yuxming.cn/Article/details/gtwwklvlnt.html

C#:   async Task F() { await G(); }
来源：http://dali.zycfv.cn/Article/details/gtzuiinbzb.html

[O05] 并发执行并等待全部完成
来源：http://dali.yueranfly.top/Article/details/gtuzwpgurg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnqzz.top/Article/details/gtinvuikve.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhiwuduotai.top/Article/details/gtmfsmmdks.html

JS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtmqaqgwac.html

TS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gtxkvedzph.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.havefunace.top/Article/details/gtjxlhdwcq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj20258.top/Article/details/gtsabddmpw.html

Ruby: threads.map(&:join)
来源：http://dali.cqqwz.cn/Article/details/gtzjueskcx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cashguo.top/Article/details/gtarbjkkmr.html

[O06] 使用进程池
来源：http://dali.sxryk.cn/Article/details/gtfkacpibd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zycfv.cn/Article/details/gttleaijpm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tanke756.top/Article/details/gtdfkuqzmz.html

JS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gtifzbmuyl.html

TS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gtcfdiuyuw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gogol.net.cn/Article/details/gtjefpcfni.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gtxeeecgyu.html

Ruby: // fork 块
来源：http://dali.cashguo.top/Article/details/gtmdwsrhax.html

C#:   Parallel.For
来源：http://dali.aizwys.cn/Article/details/gtzlkzwagi.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gturvvbqnm.html

P. 常用工具函数
来源：http://dali.birdmap.top/Article/details/gtrfztyopo.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtemetlpwa.html

[P01] 生成 UUID
来源：http://dali.vqdsnc.cn/Article/details/gtdkyryghq.html

Py:   str(uuid.uuid4())
来源：http://dali.zhixingplan.top/Article/details/gtsefztqqa.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxinkj.top/Article/details/gttglbefbb.html

JS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgyvdddtv.html

TS:   crypto.randomUUID()
来源：http://dali.yj20258.top/Article/details/gtdytjwhat.html

Java: UUID.randomUUID().toString()
来源：http://dali.zdqjudy.top/Article/details/gtowynzswh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.iojbl.cn/Article/details/gthhowbfzc.html

Ruby: SecureRandom.uuid
来源：http://dali.pengpengdd.cyou/Article/details/gtgfkotdyl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuanzx.com/Article/details/gtjygpvwzx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cheryme.top/Article/details/gtrzibylca.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cashguo.top/Article/details/gtmyesqwyn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dashuyun.cn/Article/details/gteqlxvkej.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sysykeji.top/Article/details/gtecdzahdv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.redwolf501.top/Article/details/gtemeajdrv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258888.top/Article/details/gtekerpkff.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.pengpengdd.cyou/Article/details/gtgznhmdhy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.mhx1999.top/Article/details/gtjfzkyjpn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gogol.net.cn/Article/details/gtjrthrgdo.html

[P03] 生成短随机字符串
来源：http://dali.quarkkingdee.top/Article/details/gtwtpjmago.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xylfe.cn/Article/details/gtmcdweldy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sweek.top/Article/details/gtxjhsaqjq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gtqzvfzppc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xziqi.cn/Article/details/gtjeuaihdt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxjakywu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cheryme.top/Article/details/gtcynjqtqh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnqzz.top/Article/details/gthgdyesvx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigufen.top/Article/details/gtlmdfvdtn.html

[P04] 求长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlagpqan.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yanxiufei.cn/Article/details/gtepjebjxd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtbihkuflq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqjihdif.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivaciziw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.birdmap.top/Article/details/gtvtvqrvpt.html

Go:   len(arr);  len(m)
来源：http://dali.yuanzhike.top/Article/details/gtwdfljcrs.html

Ruby: x.length;  x.size
来源：http://dali.hnxiangtu.top/Article/details/gteteshggp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.vqdsnc.cn/Article/details/gtcagtsjho.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ybcxt.top/Article/details/gtppmgcnln.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.redwolf501.top/Article/details/gtmipevysq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xuanzx.com/Article/details/gtcpuhasmj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tian-w.cn/Article/details/gtknlpqeao.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gtiozyslpx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hfpthk.cn/Article/details/gtrbljvptv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jianghu66.top/Article/details/gtvyhbumed.html

Ruby: a == b
来源：http://dali.ppjwa.cn/Article/details/gthshkfmpf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.316326.xyz/Article/details/gtbmkphhgn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjczrcop.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.feifeiyinyue.top/Article/details/gtxbbtxzry.html

PHP:  if (empty($x)) {}
来源：http://dali.cucudq.cn/Article/details/gtdpvimwqy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cheryme.top/Article/details/gtcszspgqj.html

TS:   if (x == null) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtiucrkdtd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gtynptnova.html

Go:   if x == nil {}
来源：http://dali.ehwqpu.com/Article/details/gtmkprtacx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhixingplan.top/Article/details/gtcdpqfygn.html

C#:   if (x is null) {}
来源：http://dali.mhx1999.top/Article/details/gtijurkjif.html

[P07] 防抖与节流
来源：http://dali.gotoacloud.top/Article/details/gtczkllsai.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.quarkkingdee.top/Article/details/gttvqhivhs.html


<!-- 参考信息 -->