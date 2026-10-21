代发 wailian999

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtodencjfh.html

[M01] 读取命令行参数
来源：http://dali.jianghu66.top/Article/details/gteinjhmjr.html

Py:   sys.argv[1:]
来源：http://dali.yvedp.cn/Article/details/gtaapasvks.html

PHP:  $argv;  $argc;
来源：http://dali.sufxvd.cn/Article/details/gtxubhsxkx.html

JS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gtkjtjxmnr.html

TS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gtnynmupfp.html

Java: args 数组（main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gtohwpikun.html

Go:   os.Args[1:]
来源：http://dali.guannengcc.top/Article/details/gtxxwmpyhg.html

Ruby: ARGV
来源：http://dali.sweek.top/Article/details/gtzlosrmub.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gtgjyoxiva.html

[M02] 读取环境变量
来源：http://dali.chenzaomai.com/Article/details/gtcutztzvx.html

Py:   os.environ.get("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtxvdeayuc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gtappkbbuy.html

JS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gtwujcttdv.html

TS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gtpegvsqqb.html

Java: System.getenv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtxjerafqf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtfwpfjdaq.html

Ruby: ENV["HOME"]
来源：http://dali.pycfn.com/Article/details/gtuowngzhx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtdduyvjun.html

[M03] 执行外部命令
来源：http://dali.tanke756.top/Article/details/gtmtakrfda.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yvedp.cn/Article/details/gteknnyywp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.snrcjt.cn/Article/details/gthhlyqlxu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gtnxjurfut.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gtanvovfow.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258888.top/Article/details/gtoqhtzfcj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.meibo888.top/Article/details/gtsefxggid.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sxryk.cn/Article/details/gtoypgkkwn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.quarkkingdee.top/Article/details/gtxodjjrge.html

[M04] 获取当前工作目录
来源：http://dali.zhengqikj.top/Article/details/gtpigafqdc.html

Py:   os.getcwd()
来源：http://dali.tian-w.cn/Article/details/gtyzducfrn.html

PHP:  getcwd();
来源：http://dali.birdmap.top/Article/details/gtbmujlcca.html

JS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gtbvahucir.html

TS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtizvqcevo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shuidangran.top/Article/details/gtpfybqdqd.html

Go:   os.Getwd()
来源：http://dali.gzhubu.top/Article/details/gtqtcikwoi.html

Ruby: Dir.pwd
来源：http://dali.0kj1m.cn/Article/details/gthrevgiyd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnqzz.top/Article/details/gtuecfytan.html

[M05] 设置退出码
来源：http://dali.haohaochexian.top/Article/details/gtluwcozyp.html

Py:   sys.exit(1)
来源：http://dali.hammf.cn/Article/details/gtuxitedmi.html

PHP:  exit(1);
来源：http://dali.zhiwuduotai.top/Article/details/gtptsqwukk.html

JS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gtkqjepbye.html

TS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gtuvxgszah.html

Java: System.exit(1)
来源：http://dali.316326.xyz/Article/details/gtfeymdjsz.html

Go:   os.Exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtvejkarhm.html

Ruby: exit 1
来源：http://dali.hywenlv.cn/Article/details/gtviphosqh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.svipenyu.cn/Article/details/gtcjtqyffv.html

[M06] 向标准错误输出
来源：http://dali.yuanzhike.top/Article/details/gtoiehngcx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.meibo888.top/Article/details/gtcvvdjxfm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jyoumei.cn/Article/details/gteasbrycb.html

JS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwayufmk.html

TS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtbiphvzia.html

Java: System.err.println("err")
来源：http://dali.aibaodan.cn/Article/details/gtiahccfrr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.9152youxi.cn/Article/details/gtbioctdxi.html

Ruby: warn "err"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtteuwrfpb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sxryk.cn/Article/details/gtnirgvwep.html

[M07] 判断是否为主入口
来源：http://dali.yangfankeji.com/Article/details/gtxmzllmet.html

Py:   if __name__ == "__main__":
来源：http://dali.zhongyouzk.top/Article/details/gtfalesqfl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zdqjudy.top/Article/details/gturgffolx.html

JS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gtgahgavph.html

TS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gtyctraumx.html

Java: public static void main(String[] args)
来源：http://dali.sxryk.cn/Article/details/gtoeafkmme.html

Go:   func main()
来源：http://dali.ppjwa.cn/Article/details/gttiyzcnpe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guowangkeji.top/Article/details/gttcehjiwn.html

C#:   static void Main(string[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gtvlxjhqiw.html

[M08] 获取系统与运行时信息
来源：http://dali.xuetiantiany.cn/Article/details/gtwpqbppjn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj202588.top/Article/details/gtjlhkuhby.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jyoumei.cn/Article/details/gtysvkrxhu.html

JS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gtpfisqsxj.html

TS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbcqpzty.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gzhubu.top/Article/details/gtplyounpf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sweek.top/Article/details/gtjlltcnlu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xuanzx.com/Article/details/gtjeaeqqqt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dashuyun.cn/Article/details/gtkyarnbgz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtkiwtdpwx.html

N. 数据结构与算法
来源：http://dali.daria6918.cn/Article/details/gtwrshtcdy.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gttxnaopfj.html

[N01] 二分查找（有序数组）
来源：http://dali.zycfv.cn/Article/details/gtgqzxockp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gthemrgwxd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnqzz.top/Article/details/gtiyefhhzg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbfsmtfd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gtijbxnntj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtdmlpprje.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtdwspoiln.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258.top/Article/details/gtjxbfuqaz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzuucgum.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shangyingyoupin.top/Article/details/gtxrsnglfp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangshuangyany.cn/Article/details/gtyjqlpsyd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtcywqfq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.svipenyu.cn/Article/details/gtcxwyizaf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gtmazxndwi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhiwuduotai.top/Article/details/gtjotgtwcf.html

Go:   slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtneilpbwx.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gtstnkrpmm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.9152youxi.cn/Article/details/gtybtwgtqy.html

[N03] 快速排序（分治示例）
来源：http://dali.yj20258888.top/Article/details/gtrzzytyml.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.quarkkingdee.top/Article/details/gtxucsxwti.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aizwys.cn/Article/details/gtezkbgwbm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cashguo.top/Article/details/gtmcunzhsl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.birdmap.top/Article/details/gtvqfrdduj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxinkj.top/Article/details/gticqnijny.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhiwuduotai.top/Article/details/gttvgkguca.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gtcmsktedh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xziqi.cn/Article/details/gtxoylijma.html

[N04] 斐波那契数列
来源：http://dali.kuanghao11.cn/Article/details/gtkqcyqitg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gtxxiuhmsa.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cqqwz.cn/Article/details/gtefhynzfv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gtezkzaejo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gtovzszvnl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tanke756.top/Article/details/gtngnqmdwh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.0kj1m.cn/Article/details/gttukqvpfr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gtyzmhhhrw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtwjwrrply.html

[N05] 最大公约数
来源：http://dali.zhongyouzk.top/Article/details/gtgwaguqlh.html

Py:   math.gcd(a, b)
来源：http://dali.birdmap.top/Article/details/gtgmsogbnk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sufxvd.cn/Article/details/gtgnhmzaes.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xinyue.icu/Article/details/gtddovhvqb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.smart0.xyz/Article/details/gtlmmzfghn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.9152youxi.cn/Article/details/gtcpjdcsdm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.haohaochexian.top/Article/details/gtehnixdyx.html

Ruby: a.gcd(b)
来源：http://dali.fzhhl.top/Article/details/gtlxnnhjtk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hfpthk.cn/Article/details/gtfqnlsajl.html

[N06] 判断回文字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtjkfxvqee.html

Py:   s == s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gtfiiczwzr.html

PHP:  $s === strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gtfwdpbgir.html

JS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtruqxwzyq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gttqzgjlkq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jiagoushi.top/Article/details/gtpsnsobjc.html

Go:   // 双指针从两端比较
来源：http://dali.feifeiyinyue.top/Article/details/gtyfqgrxhr.html

Ruby: s == s.reverse
来源：http://dali.xuanzx.com/Article/details/gtvgjxnksc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gtnitrtzdu.html

[N07] 两数之和（返回下标）
来源：http://dali.jinghuilouyu.cn/Article/details/gtspftlqqd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zdqjudy.top/Article/details/gttvdbahoz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gogol.net.cn/Article/details/gtcclpydbi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daria6918.cn/Article/details/gtjerenyvv.html

TS:   // 手写 Map<string, number>
来源：http://dali.cdnleiting.top/Article/details/gtruyelixo.html

Java: // 手写 HashMap
来源：http://dali.zhoulong.xyz/Article/details/gtujelvkhk.html

Go:   // 手写 map[int]int
来源：http://dali.cucudq.cn/Article/details/gtwbkbtlam.html

Ruby: // 手写 Hash
来源：http://dali.ybcxt.top/Article/details/gtffuzeywq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinqigfzy.top/Article/details/gtzwjyafmu.html

[N08] 生成全排列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyydiiptg.html

Py:   itertools.permutations(arr)
来源：http://dali.aizwys.cn/Article/details/gtolgapycx.html

PHP:  // 手写递归交换
来源：http://dali.jqgfzy.top/Article/details/gtwhfxahbi.html

JS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtinklgkmj.html

TS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtproaeebw.html

Java: // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtwiikcuos.html

Go:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gteyualkyj.html

Ruby: arr.permutation.to_a
来源：http://dali.jianghu66.top/Article/details/gtagzfrulw.html

C#:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtwvlzpcjm.html

[N09] 栈与队列
来源：http://dali.andypj.xyz/Article/details/gtfklchbco.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.c1oappe.top/Article/details/gtggkndtyw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtkuztwetq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gtroxldjxg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sxryk.cn/Article/details/gtcumzrcja.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.c1oappe.top/Article/details/gthdhizucb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jqgufenzy.top/Article/details/gtrsuswnpn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtskpnmkls.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhydvivt.html

[N10] 链表节点定义
来源：http://dali.cashguo.top/Article/details/gtxzuzkgbi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yueranfly.top/Article/details/gtejiypnlk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sxryk.cn/Article/details/gttidwyamu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yueranfly.top/Article/details/gtrtpyxmxo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhoulong.xyz/Article/details/gtslnegvka.html

Java: class Node { int v; Node next; }
来源：http://dali.yj202588.top/Article/details/gtdlapfmzb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvjsixna.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jyoumei.cn/Article/details/gtzkowrwdg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbyhhqxgb.html

[N11] 二叉树中序遍历
来源：http://dali.yj202588.top/Article/details/gtvcmxaowb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jiagoushi.top/Article/details/gtqtmappgv.html

PHP:  // 手写递归函数
来源：http://dali.nanxuanxn.top/Article/details/gtappyjinm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gtzwognnee.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gtaeirldww.html

Java: // 手写递归
来源：http://dali.tanke756.top/Article/details/gttghaobld.html

Go:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtqoipusej.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guowangkeji.top/Article/details/gtxmpdwyms.html

C#:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtdiugjkea.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnqzz.top/Article/details/gtckszhnnc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgufenzy.top/Article/details/gtovsorsiz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sxryk.cn/Article/details/gtqbekmedj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cucudq.cn/Article/details/gtyecwppza.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhiwuduotai.top/Article/details/gtcsupjyzy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gtqxgjbvif.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tanke756.top/Article/details/gtysgnrmov.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.redwolf501.top/Article/details/gtrjwjetgj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gttnueozvz.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtaablst.html

O. 并发与异步
来源：http://dali.jlsjyb.cn/Article/details/gtmbemimcg.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtdceasymr.html

[O01] 启动一个线程
来源：http://dali.yj20258888.top/Article/details/gtwnbbnipi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gaohongyu789.top/Article/details/gtqqmfhcwc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jqgufenzy.top/Article/details/gtzvbdkenp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.vqdsnc.cn/Article/details/gthvvbxadf.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gtesqznwew.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcihyxiiq.html

Go:   go f()
来源：http://dali.andypj.xyz/Article/details/gtuvtufqka.html

Ruby: Thread.new { f }
来源：http://dali.feifeiyinyue.top/Article/details/gtpreyfpyy.html

C#:   Task.Run(() => F());
来源：http://dali.shuidangran.top/Article/details/gtujbuyuzw.html

[O02] 使用线程池
来源：http://dali.ehwqpu.com/Article/details/gtwhgrpvqk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fengsongda.top/Article/details/gtlrsvkmts.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.mhx1999.top/Article/details/gtcuybtbyx.html

JS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gtyrfxqttp.html

TS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gtblbgrekk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tanke756.top/Article/details/gtejbhxqoi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aibaodan.cn/Article/details/gtyigpzcdn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.haohaochexian.top/Article/details/gtvyntkmwr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ydzc1.top/Article/details/gtdaqidnim.html

[O03] 加锁保护共享数据
来源：http://dali.redwolf501.top/Article/details/gttrqdhfvi.html

Py:   with lock: shared += 1
来源：http://dali.jyoumei.cn/Article/details/gtuciethdk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tianlin.xyz/Article/details/gtkiauasoa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangshuangyany.cn/Article/details/gtvzrrivci.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gtgzqzrnyw.html

Java: synchronized (this) { shared++; }
来源：http://dali.tanke756.top/Article/details/gtpjpvosvf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tian-w.cn/Article/details/gtoxjqqfxj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.svipenyu.cn/Article/details/gtqmrtfele.html

C#:   lock (gate) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gtsgjrwuow.html

[O04] 定义异步函数并等待
来源：http://dali.ybcxt.top/Article/details/gtcvqgdwje.html

Py:   async def f():⏎    await g()
来源：http://dali.c1oappe.top/Article/details/gtzkzzzfep.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yonumen.top/Article/details/gtoymxdjov.html

JS:   async function f() { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gtzknygahm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.smart0.xyz/Article/details/gtqpcumwga.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fengsongda.top/Article/details/gtkvlwvgoz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shuidangran.top/Article/details/gthukpmjzn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guannengcc.top/Article/details/gthoofggcs.html

C#:   async Task F() { await G(); }
来源：http://dali.iojbl.cn/Article/details/gtgoyyojwo.html

[O05] 并发执行并等待全部完成
来源：http://dali.feifeiyinyue.top/Article/details/gtftdbaueb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yuanzhike.top/Article/details/gtzvoiwung.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tianlin.xyz/Article/details/gtnmdeidrl.html

JS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gtfxwdfssk.html

TS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gtsueybjcq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ybcxt.top/Article/details/gtgqrnxsam.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sxryk.cn/Article/details/gtjqsotqwd.html

Ruby: threads.map(&:join)
来源：http://dali.haohaochexian.top/Article/details/gtglaxxkjx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj20258888.top/Article/details/gtwghskcwr.html

[O06] 使用进程池
来源：http://dali.zhoulong.xyz/Article/details/gtyhilwsjz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jyoumei.cn/Article/details/gttaulejjh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.mhx1999.top/Article/details/gteqmvdyal.html

JS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gtjiclchyq.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258888.top/Article/details/gtsvdxnyyo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xziqi.cn/Article/details/gtzlcuqvrg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.iojbl.cn/Article/details/gtayqtnoep.html

Ruby: // fork 块
来源：http://dali.cheryme.top/Article/details/gtbnpynrwj.html

C#:   Parallel.For
来源：http://dali.cdnleiting.top/Article/details/gtcwsjrgym.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfrvxybm.html

P. 常用工具函数
来源：http://dali.bjfxy.top/Article/details/gtaoglriyb.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtnudlwned.html

[P01] 生成 UUID
来源：http://dali.cheryme.top/Article/details/gtdzwpratt.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258.top/Article/details/gtirjidqsd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daria6918.cn/Article/details/gtxxqkflha.html

JS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtnfdyhigo.html

TS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtfwizeegn.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtblfdkgfm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ehwqpu.com/Article/details/gtpuvhlwfh.html

Ruby: SecureRandom.uuid
来源：http://dali.ehwqpu.com/Article/details/gtknkrkxoj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gzhubu.top/Article/details/gtcaaxtrad.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenzaomai.com/Article/details/gtekonmgnn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zycfv.cn/Article/details/gtxddxllyi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwfvgvfa.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhoulong.xyz/Article/details/gtcgwwirhz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gtqkbfipvl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.smart0.xyz/Article/details/gtrujzituw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhongyouzk.top/Article/details/gtckwwoswo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhixingplan.top/Article/details/gtmnmbcrkc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgufenzy.top/Article/details/gtzpchpmxx.html

[P03] 生成短随机字符串
来源：http://dali.yangfankeji.com/Article/details/gtvnmhlszy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hammf.cn/Article/details/gtnczfsxnr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.birdmap.top/Article/details/gtxmimswqj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtsnpzmryk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtpqwbnrsh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nanxuanxn.top/Article/details/gtlrcptuej.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhengqikj.top/Article/details/gtuvfsxmjk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jyoumei.cn/Article/details/gtirzilsje.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqqpziky.html

[P04] 求长度
来源：http://dali.jqgufenzy.top/Article/details/gtofcvrabc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.aibaodan.cn/Article/details/gtvjdrniia.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gttonvepyc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gtnjyhmbgb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuanzhike.top/Article/details/gtzoasmnxs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthsjlcpcz.html

Go:   len(arr);  len(m)
来源：http://dali.jiagoushi.top/Article/details/gtmqgzhymd.html

Ruby: x.length;  x.size
来源：http://dali.haohaochexian.top/Article/details/gtqomuqdtq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gtvfkxdzqv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.svipenyu.cn/Article/details/gtxmjxyexg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cucudq.cn/Article/details/gtfnhbmmzx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shuidangran.top/Article/details/gtawgbpntu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.andypj.xyz/Article/details/gthjgrthar.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gtgsnvnpak.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.quarkkingdee.top/Article/details/gtpqvxdxrk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ivvv.top/Article/details/gtxjphozsr.html

Ruby: a == b
来源：http://dali.xinyue.icu/Article/details/gtinusoasl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.0kj1m.cn/Article/details/gtbqnhckdb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nanxinkj.top/Article/details/gtfpjncscv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.iojbl.cn/Article/details/gtvcdqzrwq.html

PHP:  if (empty($x)) {}
来源：http://dali.hfpthk.cn/Article/details/gtnabspfty.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhengqikj.top/Article/details/gtkjrqyqhg.html

TS:   if (x == null) {}
来源：http://dali.jinqigufen.top/Article/details/gtlbubwvsz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtquslwydg.html

Go:   if x == nil {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfchaguu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258888.top/Article/details/gtansznefg.html

C#:   if (x is null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxpgriqdf.html

[P07] 防抖与节流
来源：http://dali.yangfankeji.com/Article/details/gtgnlrumyk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinqigfzy.top/Article/details/gtpelyypzr.html


<!-- 参考信息 -->