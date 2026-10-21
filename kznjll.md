代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gtzcocyenw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gtjgvatesq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sysykeji.top/Article/details/gtgnsduznj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinghuilouyu.cn/Article/details/gtcnmwnaxq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yangfankeji.com/Article/details/gtcdbwkyjp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtfwdngskj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gttricagih.html

M. 命令行 / 进程 / 环境
来源：http://dali.pycfn.com/Article/details/gtsgtibyfw.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtdejygfgk.html

[M01] 读取命令行参数
来源：http://dali.dashuyun.cn/Article/details/gtqqgozmkl.html

Py:   sys.argv[1:]
来源：http://dali.chenzaomai.com/Article/details/gtfslfnfmt.html

PHP:  $argv;  $argc;
来源：http://dali.hammf.cn/Article/details/gtkndlydkl.html

JS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gtndbrabxv.html

TS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gtvugcmdpb.html

Java: args 数组（main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gtxyczrxuj.html

Go:   os.Args[1:]
来源：http://dali.cqqwz.cn/Article/details/gtbnmgooqf.html

Ruby: ARGV
来源：http://dali.aizwys.cn/Article/details/gtygnbgbrm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gtotbhdbjg.html

[M02] 读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gtlmisddjq.html

Py:   os.environ.get("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtpmbrloow.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gtonzxbhjw.html

JS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gtwbvduwtz.html

TS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gtjsabxtxg.html

Java: System.getenv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtzxpkaryn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.havefunace.top/Article/details/gtsqgvrplx.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiafgpstv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nwbrower.top/Article/details/gtlihcpxhq.html

[M03] 执行外部命令
来源：http://dali.yonumen.top/Article/details/gthimikizv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgfzy.top/Article/details/gtsgnjgxeg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ehwqpu.com/Article/details/gtkhyqvoav.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gtwvrinitk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtyqkrddii.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpshveqxz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tian-w.cn/Article/details/gtbphlsxrw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aizwys.cn/Article/details/gtqcemosay.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yangfankeji.com/Article/details/gtxkhyxnoe.html

[M04] 获取当前工作目录
来源：http://dali.zhengqikj.top/Article/details/gtencjuqsi.html

Py:   os.getcwd()
来源：http://dali.zhoulong.xyz/Article/details/gtbcpumlat.html

PHP:  getcwd();
来源：http://dali.kuanghao11.cn/Article/details/gtdalhafgt.html

JS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gtosxpbazj.html

TS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gtywpbeios.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenzaomai.com/Article/details/gtpgtbwdkf.html

Go:   os.Getwd()
来源：http://dali.dashuyun.cn/Article/details/gtztjozxul.html

Ruby: Dir.pwd
来源：http://dali.fengsongda.top/Article/details/gtuxkgrkrb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuanzhike.top/Article/details/gthgwejigj.html

[M05] 设置退出码
来源：http://dali.zdqjudy.top/Article/details/gtauhqdkqw.html

Py:   sys.exit(1)
来源：http://dali.sxryk.cn/Article/details/gticxlxczq.html

PHP:  exit(1);
来源：http://dali.9152youxi.cn/Article/details/gtdlywugch.html

JS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtitvprqbb.html

TS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfhvmbyt.html

Java: System.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtnwasgrvq.html

Go:   os.Exit(1)
来源：http://dali.daxiang520.top/Article/details/gtkwpnxlrl.html

Ruby: exit 1
来源：http://dali.dianchejie.cn/Article/details/gtufsaejbz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gaohongyu789.top/Article/details/gtoixsgoot.html

[M06] 向标准错误输出
来源：http://dali.yj20258888.top/Article/details/gtxhacyotx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnuqwjzi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhixingplan.top/Article/details/gtmxlnmclj.html

JS:   console.error("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtcmzcmqnp.html

TS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gtygjrjkna.html

Java: System.err.println("err")
来源：http://dali.chenzaomai.com/Article/details/gtukrupahc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shuidangran.top/Article/details/gtdrebmcwr.html

Ruby: warn "err"
来源：http://dali.feifeiyinyue.top/Article/details/gtlwmovvyf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenzaomai.com/Article/details/gtcojbwaic.html

[M07] 判断是否为主入口
来源：http://dali.zhongyouzk.top/Article/details/gtbnapxssl.html

Py:   if __name__ == "__main__":
来源：http://dali.zdqjudy.top/Article/details/gtubalamyt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.iojbl.cn/Article/details/gtmqosybuj.html

JS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gtbtaiguvh.html

TS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gtsawjkvsv.html

Java: public static void main(String[] args)
来源：http://dali.iojbl.cn/Article/details/gtgddjyeno.html

Go:   func main()
来源：http://dali.cashguo.top/Article/details/gttilfvixd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxuanxn.top/Article/details/gttufytxdf.html

C#:   static void Main(string[] args)
来源：http://dali.9152youxi.cn/Article/details/gtmzzcfafx.html

[M08] 获取系统与运行时信息
来源：http://dali.dianchejie.cn/Article/details/gteeuvhiut.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ppjwa.cn/Article/details/gtysnecwdu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigufen.top/Article/details/gtrjcvvrjn.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gtudyjtxig.html

TS:   process.platform;  process.version
来源：http://dali.yj20258.top/Article/details/gtrxjxtbek.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgfzy.top/Article/details/gthnhuaauc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj202588.top/Article/details/gtaieddurc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.havefunace.top/Article/details/gtbzvtpckx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fzhhl.top/Article/details/gtlbdefhgo.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtfigndflp.html

N. 数据结构与算法
来源：http://dali.meibo888.top/Article/details/gtdbddeynw.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtvxmvchcj.html

[N01] 二分查找（有序数组）
来源：http://dali.cheryme.top/Article/details/gttulzmdkv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.meibo888.top/Article/details/gtsljyiqah.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuanzhike.top/Article/details/gtoszpddgp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gtrdwpyizn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gtiksmaize.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtrquomwwx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkvuvyhr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nwbrower.top/Article/details/gtvoptoqin.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtbvijdpla.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gttlhtrkvc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gtwiddymky.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258.top/Article/details/gtwasgqozt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gtptfkuuqg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gtfkmsuuxj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hammf.cn/Article/details/gtrdpokjpm.html

Go:   slices.Sort(arr)
来源：http://dali.pycfn.com/Article/details/gtkbympijc.html

Ruby: arr.sort
来源：http://dali.xinyue.icu/Article/details/gtqwvsnkkt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aibaodan.cn/Article/details/gtnxbhzcxb.html

[N03] 快速排序（分治示例）
来源：http://dali.ydzc1.top/Article/details/gtpfjztmnj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gogol.net.cn/Article/details/gtsfnprsec.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shuidangran.top/Article/details/gtxcweisxv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gtxcdbiqxc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gtbafdepjm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nwbrower.top/Article/details/gtyjnysflc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.0kj1m.cn/Article/details/gtipmvpjzv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.snrcjt.cn/Article/details/gtxohctqpx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jlsjyb.cn/Article/details/gtdhjekmxu.html

[N04] 斐波那契数列
来源：http://dali.smart0.xyz/Article/details/gtjgdqxcmi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gtctfajvvb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gtwnxncxxh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtjdxjlymt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gtwciealvv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvasyodbz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.bjfxy.top/Article/details/gtcfhunihe.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guannengcc.top/Article/details/gtxwzvkfbo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gtwflzxgdx.html

[N05] 最大公约数
来源：http://dali.birdmap.top/Article/details/gteqrjfvzc.html

Py:   math.gcd(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gtgwfmuhah.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sysykeji.top/Article/details/gtqacpcfaq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gteuorprhl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gtimufjxar.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xinyue.icu/Article/details/gtldgjvkra.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigfzy.top/Article/details/gtaijvuylx.html

Ruby: a.gcd(b)
来源：http://dali.xylfe.cn/Article/details/gtuskwxzzr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xinyue.icu/Article/details/gteaeblhdb.html

[N06] 判断回文字符串
来源：http://dali.pycfn.com/Article/details/gtgungctin.html

Py:   s == s[::-1]
来源：http://dali.redwolf501.top/Article/details/gtiydotszx.html

PHP:  $s === strrev($s);
来源：http://dali.xinyue.icu/Article/details/gtilzfwlvy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtarjevcex.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtihhtaiqu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj20258.top/Article/details/gtredkfkzv.html

Go:   // 双指针从两端比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gthybeytnj.html

Ruby: s == s.reverse
来源：http://dali.sweek.top/Article/details/gtqjwrqlfq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gtwuqklanx.html

[N07] 两数之和（返回下标）
来源：http://dali.xylfe.cn/Article/details/gtmmgpajhr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cheryme.top/Article/details/gtxlwhptvd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ppjwa.cn/Article/details/gtjguepoya.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aizwys.cn/Article/details/gtpildhxji.html

TS:   // 手写 Map<string, number>
来源：http://dali.birdmap.top/Article/details/gturtebdot.html

Java: // 手写 HashMap
来源：http://dali.bjfxy.top/Article/details/gtxaizqjgx.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqemrhmy.html

Ruby: // 手写 Hash
来源：http://dali.hywenlv.cn/Article/details/gthbyoegyz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.snrcjt.cn/Article/details/gtoifdtvbk.html

[N08] 生成全排列
来源：http://dali.gzhubu.top/Article/details/gtkxrfakaz.html

Py:   itertools.permutations(arr)
来源：http://dali.yongpay.top/Article/details/gtipgptcot.html

PHP:  // 手写递归交换
来源：http://dali.xziqi.cn/Article/details/gtgbudpdde.html

JS:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtkrmjwfzc.html

TS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtdtfnrrgs.html

Java: // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtesojgrlv.html

Go:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtyvuspoup.html

Ruby: arr.permutation.to_a
来源：http://dali.nwbrower.top/Article/details/gtabgyvqsq.html

C#:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtcqgacrvx.html

[N09] 栈与队列
来源：http://dali.cheryme.top/Article/details/gtlnjmhwhl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.vqdsnc.cn/Article/details/gtpizbrscx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtcazbbxkq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtzmujvxib.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.feifeiyinyue.top/Article/details/gtexkwnror.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shzxlz.cn/Article/details/gtdwqbwypy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258.top/Article/details/gtbhdoflmu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcmxtxcd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhoulong.xyz/Article/details/gtteyerqit.html

[N10] 链表节点定义
来源：http://dali.hammf.cn/Article/details/gttnwjoyae.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zdqjudy.top/Article/details/gtqfgthaha.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dashuyun.cn/Article/details/gtayaxeibt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cucudq.cn/Article/details/gtcrtvmsdt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.316326.xyz/Article/details/gtzxnnoort.html

Java: class Node { int v; Node next; }
来源：http://dali.zhongyouzk.top/Article/details/gtvysrjmor.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.quarkkingdee.top/Article/details/gtetskhzay.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sweek.top/Article/details/gtehrqpudz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cqqwz.cn/Article/details/gtxellnwci.html

[N11] 二叉树中序遍历
来源：http://dali.jlsjyb.cn/Article/details/gtwlamoeet.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.birdmap.top/Article/details/gttffbinkz.html

PHP:  // 手写递归函数
来源：http://dali.hysaishi.cn/Article/details/gtovbhvbgr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxuanxn.top/Article/details/gtovnrcypk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gthqakrhrd.html

Java: // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gtavvejrlb.html

Go:   // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gtwlhvjsca.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aizwys.cn/Article/details/gtapodktmm.html

C#:   // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gtajziebkn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cucudq.cn/Article/details/gtiattcslc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nwbrower.top/Article/details/gtibybuamm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cucudq.cn/Article/details/gtuiqrahhf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gtddouawlf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gttlijxhtk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gtutjfvpiy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sxryk.cn/Article/details/gtjzulocql.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuanzhike.top/Article/details/gthqorcmlb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gttmvtazfb.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtpotubgny.html

O. 并发与异步
来源：http://dali.snrcjt.cn/Article/details/gtlqkxduom.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtdoztdgbl.html

[O01] 启动一个线程
来源：http://dali.guannengcc.top/Article/details/gtndkyqcbt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.vqdsnc.cn/Article/details/gtxwckdbcd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.kuanghao11.cn/Article/details/gtskjelcaz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.316326.xyz/Article/details/gtculjycoq.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gtcsahwqvf.html

Java: new Thread(() -> f()).start()
来源：http://dali.ybcxt.top/Article/details/gttfgdthop.html

Go:   go f()
来源：http://dali.zhongyouzk.top/Article/details/gteldrbwmt.html

Ruby: Thread.new { f }
来源：http://dali.zycfv.cn/Article/details/gtrkajbzmp.html

C#:   Task.Run(() => F());
来源：http://dali.bjfxy.top/Article/details/gtwhddsqjq.html

[O02] 使用线程池
来源：http://dali.wangdashe.top/Article/details/gtdhcqkpnv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jlsjyb.cn/Article/details/gtjjfotfzg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ehwqpu.com/Article/details/gtypwyfmgq.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigfzy.top/Article/details/gtsmncmchh.html

TS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gthcuswvre.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyyvwtkhf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cucudq.cn/Article/details/gtvldiwfdr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cqqwz.cn/Article/details/gtmsvkbhsq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shangyingyoupin.top/Article/details/gtgghntdqa.html

[O03] 加锁保护共享数据
来源：http://dali.daxiang520.top/Article/details/gtpcwvpozw.html

Py:   with lock: shared += 1
来源：http://dali.meibo888.top/Article/details/gtedqzuwle.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tanke756.top/Article/details/gtrvqcsyop.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xziqi.cn/Article/details/gtcjnswokj.html

TS:   // 同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gthiohxpgi.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj20258888.top/Article/details/gtrazktejk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jianghu66.top/Article/details/gtyquxjvzz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jlsjyb.cn/Article/details/gtgymgfvjz.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gtmbvpmtij.html

[O04] 定义异步函数并等待
来源：http://dali.bjfxy.top/Article/details/gtdlpplepk.html

Py:   async def f():⏎    await g()
来源：http://dali.yuanzhike.top/Article/details/gthjfzyygg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dianchejie.cn/Article/details/gtlzcapdhn.html

JS:   async function f() { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gttmbgkoha.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gtovlfbmxg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hongshengwenyu.top/Article/details/gtcomtwiqp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.aibaodan.cn/Article/details/gtkvrpolxj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cdnleiting.top/Article/details/gtsjqtptro.html

C#:   async Task F() { await G(); }
来源：http://dali.hongshengwenyu.top/Article/details/gthfdraudd.html

[O05] 并发执行并等待全部完成
来源：http://dali.sxryk.cn/Article/details/gtbnynctpt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.snrcjt.cn/Article/details/gtckiiirct.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gtpdojxgur.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbsxvmpzt.html

TS:   await Promise.all(tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtezbhcpif.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ybcxt.top/Article/details/gtpqehehhs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yangfankeji.com/Article/details/gtadwglgqj.html

Ruby: threads.map(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gtgmwcacwo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cucudq.cn/Article/details/gtpuxnoatd.html

[O06] 使用进程池
来源：http://dali.jinqigfzy.top/Article/details/gtfvwyipnk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hnxiangtu.top/Article/details/gtcakjvwwi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shangyingyoupin.top/Article/details/gtawjvoaps.html

JS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gttseekahw.html

TS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gtquldxuwi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj202588.top/Article/details/gtilmltypp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xuetiantiany.cn/Article/details/gtkzuziuxw.html

Ruby: // fork 块
来源：http://dali.gaohongyu789.top/Article/details/gtkngmrepk.html

C#:   Parallel.For
来源：http://dali.jlsjyb.cn/Article/details/gtfxgqfxcw.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtlorimnam.html

P. 常用工具函数
来源：http://dali.316326.xyz/Article/details/gtlcglilyt.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuaebpkgf.html

[P01] 生成 UUID
来源：http://dali.gogol.net.cn/Article/details/gtuvtprjuy.html

Py:   str(uuid.uuid4())
来源：http://dali.aibaodan.cn/Article/details/gtosjyvelt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.bjfxy.top/Article/details/gttygnupzo.html

JS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gtrnasmovs.html

TS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gtuvdhcnvi.html

Java: UUID.randomUUID().toString()
来源：http://dali.cdnleiting.top/Article/details/gtlltgvhay.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtcbxfubnu.html

Ruby: SecureRandom.uuid
来源：http://dali.hfpthk.cn/Article/details/gtbbkjtceh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.9152youxi.cn/Article/details/gtjbisuhxn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnqzz.top/Article/details/gtofcoeton.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangshuangyany.cn/Article/details/gtnymmprpx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgckeyda.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ppjwa.cn/Article/details/gtzjlocrwo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj20258888.top/Article/details/gtqaucdmmm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cashguo.top/Article/details/gtynlgnipi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuanzhike.top/Article/details/gtzcuzpgaa.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dianchejie.cn/Article/details/gtwfwbjsah.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigfzy.top/Article/details/gtsaumgeyp.html

[P03] 生成短随机字符串
来源：http://dali.gogol.net.cn/Article/details/gtxkdutopf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.feifeiyinyue.top/Article/details/gtgxnejgru.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.guowangkeji.top/Article/details/gtozmloshl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnqzz.top/Article/details/gtrhbaudxo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gtvnefqfzl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pycfn.com/Article/details/gthdbcgsys.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jqgfzy.top/Article/details/gtayrxjctx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.aizwys.cn/Article/details/gtlsqifcdx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sufxvd.cn/Article/details/gtenamarbf.html

[P04] 求长度
来源：http://dali.smart0.xyz/Article/details/gtgjaqaxyc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xylfe.cn/Article/details/gtpkcwpzil.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtbulypouz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gtunaygtdv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gtwuoovqef.html

Java: list.size();  map.size();  s.length()
来源：http://dali.redwolf501.top/Article/details/gtnoitflut.html

Go:   len(arr);  len(m)
来源：http://dali.sufxvd.cn/Article/details/gtwwysygmc.html

Ruby: x.length;  x.size
来源：http://dali.yonumen.top/Article/details/gtcmchcrqq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.svipenyu.cn/Article/details/gtoppmwchl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenzaomai.com/Article/details/gtrknrpbbt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuanzx.com/Article/details/gtdvtyxjke.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xziqi.cn/Article/details/gttrjyuekq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmwycill.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gtzijgrzax.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuanzx.com/Article/details/gtkkszlfuo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shuidangran.top/Article/details/gthpsyneag.html

Ruby: a == b
来源：http://dali.ivvv.top/Article/details/gtgwtyhhno.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cdnleiting.top/Article/details/gtejovusxc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.meibo888.top/Article/details/gtsydoqbrd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.daria6918.cn/Article/details/gtruswhgrm.html

PHP:  if (empty($x)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtxbqdvawn.html


<!-- 参考信息 -->