代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gt2tipybxgx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gt2edgvptvc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuetiantiany.cn/Article/details/gt2ededqsnw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnkvdod.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tian-w.cn/Article/details/gt2dwpmkhjn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xinyue.icu/Article/details/gt2ikmwpycp.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2lpmbpxur.html

M. 命令行 / 进程 / 环境
来源：http://dali.xziqi.cn/Article/details/gt2erintjxm.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2bzqyjdqn.html

[M01] 读取命令行参数
来源：http://dali.9152youxi.cn/Article/details/gt2isggpygm.html

Py:   sys.argv[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gt2lsirlzee.html

PHP:  $argv;  $argc;
来源：http://dali.andypj.xyz/Article/details/gt2mtvdbxgn.html

JS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gt2pfvqhofz.html

TS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gt2qpfbuwzn.html

Java: args 数组（main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gt2mvlbvvsd.html

Go:   os.Args[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gt2evbldgxu.html

Ruby: ARGV
来源：http://dali.guannengcc.top/Article/details/gt2gxgxtqzy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gt2ytrawxes.html

[M02] 读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gt2mvrjzvbw.html

Py:   os.environ.get("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2zpvxazcg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gt2amxzljjs.html

JS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gt2ogsztecn.html

TS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gt2dtydgava.html

Java: System.getenv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2pljjtyqf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zycfv.cn/Article/details/gt2kpokigsp.html

Ruby: ENV["HOME"]
来源：http://dali.pengpengdd.cyou/Article/details/gt2otwyrjjq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yvedp.cn/Article/details/gt2tazydydu.html

[M03] 执行外部命令
来源：http://dali.gzhubu.top/Article/details/gt2fzyivdhv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgufenzy.top/Article/details/gt2yfenfash.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pengpengdd.cyou/Article/details/gt2unzcrnko.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gt2pupditkq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gt2djbicmju.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eauoygrt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.pycfn.com/Article/details/gt2hmptkkcn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fengsongda.top/Article/details/gt2uffidhit.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aizwys.cn/Article/details/gt2mrsfyrxf.html

[M04] 获取当前工作目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vpadhrqz.html

Py:   os.getcwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vacxmknc.html

PHP:  getcwd();
来源：http://dali.gzhubu.top/Article/details/gt2tgegmcmc.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gt2quljfpch.html

TS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gt2vayvhcha.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.fengsongda.top/Article/details/gt2mgccyljx.html

Go:   os.Getwd()
来源：http://dali.fengsongda.top/Article/details/gt2obrkfkak.html

Ruby: Dir.pwd
来源：http://dali.feifeiyinyue.top/Article/details/gt2gszelfdx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gzhubu.top/Article/details/gt2fxnqwbgb.html

[M05] 设置退出码
来源：http://dali.nanxuanxn.top/Article/details/gt2negmhpqo.html

Py:   sys.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kdrwzhbn.html

PHP:  exit(1);
来源：http://dali.yangfankeji.com/Article/details/gt2kkpksxju.html

JS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2imfranzs.html

TS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2npstgxuj.html

Java: System.exit(1)
来源：http://dali.hammf.cn/Article/details/gt2nolkldbd.html

Go:   os.Exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2jdefsoen.html

Ruby: exit 1
来源：http://dali.cqqwz.cn/Article/details/gt2pyfkxojp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xylfe.cn/Article/details/gt2nhlwfhco.html

[M06] 向标准错误输出
来源：http://dali.tanke756.top/Article/details/gt2pexqbfzf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xinyue.icu/Article/details/gt2psmjjazo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daria6918.cn/Article/details/gt2kjjzucgy.html

JS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gt2zbsvwfxk.html

TS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gt2huubnzre.html

Java: System.err.println("err")
来源：http://dali.jyoumei.cn/Article/details/gt2cgtbtzmk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvatyce.html

Ruby: warn "err"
来源：http://dali.sufxvd.cn/Article/details/gt2usryodrt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gogol.net.cn/Article/details/gt2dmpxbcmm.html

[M07] 判断是否为主入口
来源：http://dali.nanxinkj.top/Article/details/gt2pjxjmmet.html

Py:   if __name__ == "__main__":
来源：http://dali.mhx1999.top/Article/details/gt2nshebnly.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ivvv.top/Article/details/gt2mjuzlpft.html

JS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gt2jbtmeufh.html

TS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gt2asogfdso.html

Java: public static void main(String[] args)
来源：http://dali.gzhubu.top/Article/details/gt2ctdhcjjt.html

Go:   func main()
来源：http://dali.xuanzx.com/Article/details/gt2ujgmcjna.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yongpay.top/Article/details/gt2ijyavhbu.html

C#:   static void Main(string[] args)
来源：http://dali.bjfxy.top/Article/details/gt2ktrgqedo.html

[M08] 获取系统与运行时信息
来源：http://dali.xinyue.icu/Article/details/gt2oyewxvei.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenlongwang.top/Article/details/gt2lnorrhas.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ynkbebul.html

JS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gt2okqurjul.html

TS:   process.platform;  process.version
来源：http://dali.c1oappe.top/Article/details/gt2dmorkbrs.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jlsjyb.cn/Article/details/gt2kruhimwh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.snrcjt.cn/Article/details/gt2vdgybxwz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.birdmap.top/Article/details/gt2zoqdsglw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenjidiqi.icu/Article/details/gt2iqroktal.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2ruritmsl.html

N. 数据结构与算法
来源：http://dali.xinyue.icu/Article/details/gt2rlppmpwm.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2rbjfjezk.html

[N01] 二分查找（有序数组）
来源：http://dali.yueranfly.top/Article/details/gt2gwxbikek.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2ivemdjgr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gogol.net.cn/Article/details/gt2pxtqookp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2muecdpbc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuanzhike.top/Article/details/gt2rjuzceca.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2nszjxtxy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2attdihoc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aibaodan.cn/Article/details/gt2dehfjvev.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cbptjamo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnxiangtu.top/Article/details/gt2jjwtarhx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gt2zqzocskw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gt2strvbrmv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gt2yapggyqe.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gt2afotgywl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pengpengdd.cyou/Article/details/gt2auypkohv.html

Go:   slices.Sort(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2nkijgwab.html

Ruby: arr.sort
来源：http://dali.jqgufenzy.top/Article/details/gt2qcllswve.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cdnleiting.top/Article/details/gt2dekgpssi.html

[N03] 快速排序（分治示例）
来源：http://dali.yueranfly.top/Article/details/gt2agusejug.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guowangkeji.top/Article/details/gt2dgkwural.html

PHP:  // 递归实现，或用 usort
来源：http://dali.snrcjt.cn/Article/details/gt2tlnxcabu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gt2wpuuowtr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sufxvd.cn/Article/details/gt2lvltcabl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.c1oappe.top/Article/details/gt2rnrsyjlp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shuidangran.top/Article/details/gt2zpeybkpp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.haohaochexian.top/Article/details/gt2aeyyolge.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cqqwz.cn/Article/details/gt2xnjowwkj.html

[N04] 斐波那契数列
来源：http://dali.aibaodan.cn/Article/details/gt2iuqlfqle.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gt2hbspfhnj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnqzz.top/Article/details/gt2iqudnnrv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gt2vqsbdnlm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gt2zaynwagd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xziqi.cn/Article/details/gt2tmrwtnvo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aibaodan.cn/Article/details/gt2noxgfqql.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cdnleiting.top/Article/details/gt2wlepmlod.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gt2gqqbpbjv.html

[N05] 最大公约数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2emobvaft.html

Py:   math.gcd(a, b)
来源：http://dali.snrcjt.cn/Article/details/gt2lpeqshlp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhongyouzk.top/Article/details/gt2gnhugids.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gt2lqloluza.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cctxewyf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pycfn.com/Article/details/gt2apinmbrt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dashuyun.cn/Article/details/gt2niidstsg.html

Ruby: a.gcd(b)
来源：http://dali.kuanghao11.cn/Article/details/gt2jrlkjirt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.kuanghao11.cn/Article/details/gt2yffujucn.html

[N06] 判断回文字符串
来源：http://dali.tianlin.xyz/Article/details/gt2qplumuzo.html

Py:   s == s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gt2counakxy.html

PHP:  $s === strrev($s);
来源：http://dali.316326.xyz/Article/details/gt2ehwbpote.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wrleumzv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2hcewyjtw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.c1oappe.top/Article/details/gt2zdalwavx.html

Go:   // 双指针从两端比较
来源：http://dali.bjfxy.top/Article/details/gt2yelbdowy.html

Ruby: s == s.reverse
来源：http://dali.aibaodan.cn/Article/details/gt2byhfymkd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gt2cxslldxs.html

[N07] 两数之和（返回下标）
来源：http://dali.redwolf501.top/Article/details/gt2fwglpbmh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pycfn.com/Article/details/gt2vwgpetrt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xinyue.icu/Article/details/gt2drzwrfxk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxuefol.html

TS:   // 手写 Map<string, number>
来源：http://dali.nwbrower.top/Article/details/gt2lsylvrxn.html

Java: // 手写 HashMap
来源：http://dali.birdmap.top/Article/details/gt2czhgbxdx.html

Go:   // 手写 map[int]int
来源：http://dali.ehwqpu.com/Article/details/gt2ekkafawj.html

Ruby: // 手写 Hash
来源：http://dali.ybcxt.top/Article/details/gt2zhdjgbpa.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xziqi.cn/Article/details/gt2vegageel.html

[N08] 生成全排列
来源：http://dali.ppjwa.cn/Article/details/gt2lgibnxux.html

Py:   itertools.permutations(arr)
来源：http://dali.fzhhl.top/Article/details/gt2aawtyvxn.html

PHP:  // 手写递归交换
来源：http://dali.sufxvd.cn/Article/details/gt2cmlxgune.html

JS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gt2orkugvnh.html

TS:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gt2mpqrfcwi.html

Java: // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gt2ymdxbszo.html

Go:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2vwageqpd.html

Ruby: arr.permutation.to_a
来源：http://dali.hysaishi.cn/Article/details/gt2ketzvxtl.html

C#:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2tckhpmbo.html

[N09] 栈与队列
来源：http://dali.hysaishi.cn/Article/details/gt2wskeozjo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.iojbl.cn/Article/details/gt2qixqlmiz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2nqfnkhjf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gt2deculzta.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cashguo.top/Article/details/gt2xxldpfwu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cheryme.top/Article/details/gt2wggcsgex.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenzaomai.com/Article/details/gt2adaqsspi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aizwys.cn/Article/details/gt2bpatfvou.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jjygrjgk.html

[N10] 链表节点定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kanlickt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tian-w.cn/Article/details/gt2hvtxylfm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cheryme.top/Article/details/gt2iksnkepi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yvedp.cn/Article/details/gt2lpjtnobw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daxiang520.top/Article/details/gt2mnbaozyx.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258.top/Article/details/gt2wtvzuidk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tanke756.top/Article/details/gt2rmwuosyz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.meibo888.top/Article/details/gt2eyytypfa.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuanzhike.top/Article/details/gt2adbsykod.html

[N11] 二叉树中序遍历
来源：http://dali.jianghu66.top/Article/details/gt2rurtmdyn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fengsongda.top/Article/details/gt2yjlanegk.html

PHP:  // 手写递归函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2htqqbumm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gt2inglojuk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cwojgxiv.html

Java: // 手写递归
来源：http://dali.andypj.xyz/Article/details/gt2kmqbyomx.html

Go:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gt2glqkcpjv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gogol.net.cn/Article/details/gt2fcijkngq.html

C#:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gt2ffnrrxdm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj202588.top/Article/details/gt2zfjultpp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yuxming.cn/Article/details/gt2mpduwgzi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cucudq.cn/Article/details/gt2fqupywbk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gt2yghgagim.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gt2sqtxhenp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jyoumei.cn/Article/details/gt2aijflzzk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xuanzx.com/Article/details/gt2eghstowx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cdnleiting.top/Article/details/gt2cejylarj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gcafwqhb.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2zkiihkjx.html

O. 并发与异步
来源：http://dali.xziqi.cn/Article/details/gt2fmehsqhm.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2ginjwdyv.html

[O01] 启动一个线程
来源：http://dali.nanxuanxn.top/Article/details/gt2xygfxpdm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yangfankeji.com/Article/details/gt2hxmllhdl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.smart0.xyz/Article/details/gt2pwkqyhcj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hysaishi.cn/Article/details/gt2abvpaimd.html

TS:   // 同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gt2wuspvwno.html

Java: new Thread(() -> f()).start()
来源：http://dali.xuanzx.com/Article/details/gt2ichcpxxy.html

Go:   go f()
来源：http://dali.yvedp.cn/Article/details/gt2rfyxgfra.html

Ruby: Thread.new { f }
来源：http://dali.cashguo.top/Article/details/gt2brrlejvk.html

C#:   Task.Run(() => F());
来源：http://dali.nwbrower.top/Article/details/gt2pcuvzzvn.html

[O02] 使用线程池
来源：http://dali.jianghu66.top/Article/details/gt2himjpkws.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.vqdsnc.cn/Article/details/gt2gdqsuljl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jlsjyb.cn/Article/details/gt2ieniflvq.html

JS:   // worker_threads 线程池
来源：http://dali.guowangkeji.top/Article/details/gt2qlfjvfom.html

TS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gt2kepasmji.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jyoumei.cn/Article/details/gt2ciilwvvt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnqzz.top/Article/details/gt2aibrlxsn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgufenzy.top/Article/details/gt2wrskxceq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.dashuyun.cn/Article/details/gt2mtihporl.html

[O03] 加锁保护共享数据
来源：http://dali.yanxiufei.cn/Article/details/gt2myhtdksm.html

Py:   with lock: shared += 1
来源：http://dali.hfpthk.cn/Article/details/gt2ypavlngf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jiagoushi.top/Article/details/gt2qexzatch.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigufen.top/Article/details/gt2aqsfagxc.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gt2dntukyao.html

Java: synchronized (this) { shared++; }
来源：http://dali.hammf.cn/Article/details/gt2szilsosj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cheryme.top/Article/details/gt2pjbdpzcb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yangfankeji.com/Article/details/gt2yytyzzxj.html

C#:   lock (gate) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gt2pcsixosh.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258.top/Article/details/gt2sihkqakr.html

Py:   async def f():⏎    await g()
来源：http://dali.quarkkingdee.top/Article/details/gt2zvikxnsh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shzxlz.cn/Article/details/gt2oulvqjgo.html

JS:   async function f() { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gt2ktiehmmk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pycfn.com/Article/details/gt2zvjyzxmm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhiwuduotai.top/Article/details/gt2tjsxlcfs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ehwqpu.com/Article/details/gt2lmefepbs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wussdlwh.html

C#:   async Task F() { await G(); }
来源：http://dali.yvedp.cn/Article/details/gt2xloeugxq.html

[O05] 并发执行并等待全部完成
来源：http://dali.c1oappe.top/Article/details/gt2qulcglsq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jlsjyb.cn/Article/details/gt2dudtjvur.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenzaomai.com/Article/details/gt2dgxjxvsh.html

JS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gt2xbowahvy.html

TS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gt2rwhudmlj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sxryk.cn/Article/details/gt2gqlcjmpc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xuetiantiany.cn/Article/details/gt2fpgpkgxf.html

Ruby: threads.map(&:join)
来源：http://dali.yonumen.top/Article/details/gt2wurzdegi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.redwolf501.top/Article/details/gt2ufofgocq.html

[O06] 使用进程池
来源：http://dali.tianlin.xyz/Article/details/gt2hqnolgvd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2napxcczw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sufxvd.cn/Article/details/gt2mzfockcg.html

JS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gt2kdyghycd.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gt2hzvdnwju.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuxming.cn/Article/details/gt2yqoucfak.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xylfe.cn/Article/details/gt2xopwbujo.html

Ruby: // fork 块
来源：http://dali.9152youxi.cn/Article/details/gt2gxxoxbxw.html

C#:   Parallel.For
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ouxpysfp.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2lhebgrmp.html

P. 常用工具函数
来源：http://dali.nwbrower.top/Article/details/gt2tpghjlib.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2yvwtxnsj.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2huohdubg.html

Py:   str(uuid.uuid4())
来源：http://dali.jianghu66.top/Article/details/gt2lvrkefpt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shzxlz.cn/Article/details/gt2lwaqyuei.html

JS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gt2tepwrakf.html

TS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gt2uihwkvmx.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigufen.top/Article/details/gt2uaeklbjq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tianlin.xyz/Article/details/gt2isdxdkmy.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxinkj.top/Article/details/gt2yzrlkkbm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigfzy.top/Article/details/gt2inhsando.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hongshengwenyu.top/Article/details/gt2nfqjbasb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hfpthk.cn/Article/details/gt2uhpgwwyk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ehwqpu.com/Article/details/gt2xnmvuhrr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258.top/Article/details/gt2pawikpcz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jlsjyb.cn/Article/details/gt2qapcbjyv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.bjfxy.top/Article/details/gt2kvhixlxh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jiagoushi.top/Article/details/gt2ecbpgmep.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.havefunace.top/Article/details/gt2hpnyavtz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2niwbqcly.html

[P03] 生成短随机字符串
来源：http://dali.yj20258.top/Article/details/gt2wmvvzetz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.aibaodan.cn/Article/details/gt2ithkyqzy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnxiangtu.top/Article/details/gt2bznfuydp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ybkeemhh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gt2adsxmluq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuxming.cn/Article/details/gt2lavgmmrg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xuanzx.com/Article/details/gt2ichzfsek.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gzhubu.top/Article/details/gt2htjlztez.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgufenzy.top/Article/details/gt2fqtaauwy.html

[P04] 求长度
来源：http://dali.birdmap.top/Article/details/gt2ecupjbed.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenlongwang.top/Article/details/gt2mbyoolcs.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2ucjhztvm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gt2jjaaloay.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgufenzy.top/Article/details/gt2fpyebqin.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cucudq.cn/Article/details/gt2zbsfunsz.html

Go:   len(arr);  len(m)
来源：http://dali.cdnleiting.top/Article/details/gt2giyqktmz.html

Ruby: x.length;  x.size
来源：http://dali.gzhubu.top/Article/details/gt2swekyodj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2owemlwuq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hywenlv.cn/Article/details/gt2aegbuzwp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.dianchejie.cn/Article/details/gt2ubxbszcj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.bjfxy.top/Article/details/gt2ojzlikor.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258888.top/Article/details/gt2jkzzfqbp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qddocomx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.c1oappe.top/Article/details/gt2cgmludpg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gt2topacrva.html

Ruby: a == b
来源：http://dali.zhengqikj.top/Article/details/gt2royxjkzo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.feifeiyinyue.top/Article/details/gt2zmxvsplv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnqzz.top/Article/details/gt2orbjftbu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.9152youxi.cn/Article/details/gt2ofrjxjyr.html

PHP:  if (empty($x)) {}
来源：http://dali.smart0.xyz/Article/details/gt2jhdcsqdi.html


<!-- 参考信息 -->