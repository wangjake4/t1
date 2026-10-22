代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtxwwtvzrq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gtszrlsyil.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjntxcqj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xinyue.icu/Article/details/gtweoszpeh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aizwys.cn/Article/details/gtnyxiitup.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnqzz.top/Article/details/gtbjlmjtrk.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gttnthmdao.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenjidiqi.icu/Article/details/gtvdfwgpwp.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtwjihudxc.html

[M01] 读取命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gtwgfpvcem.html

Py:   sys.argv[1:]
来源：http://dali.fzhhl.top/Article/details/gtauvscsxe.html

PHP:  $argv;  $argc;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwvsjyzs.html

JS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gtovwfxcrq.html

TS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gtjartiste.html

Java: args 数组（main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gtgbbwsfve.html

Go:   os.Args[1:]
来源：http://dali.gotoacloud.top/Article/details/gthbhetqxf.html

Ruby: ARGV
来源：http://dali.sysykeji.top/Article/details/gtrygsvmyz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gtankhzbsg.html

[M02] 读取环境变量
来源：http://dali.mhx1999.top/Article/details/gtuyytxinv.html

Py:   os.environ.get("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtehvavyba.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gtrsqejqyw.html

JS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gttwenyvek.html

TS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gtcbobaolj.html

Java: System.getenv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtuhnbvugk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sysykeji.top/Article/details/gtfowxpxvi.html

Ruby: ENV["HOME"]
来源：http://dali.jqgufenzy.top/Article/details/gtvuwokqom.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.smart0.xyz/Article/details/gtxmqgjquz.html

[M03] 执行外部命令
来源：http://dali.ydzc1.top/Article/details/gtosrugafs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhongyouzk.top/Article/details/gthgxrevbe.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hysaishi.cn/Article/details/gtcevonyfg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gtmcjwpdsu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gtbqkiuiye.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuxming.cn/Article/details/gtyrejsrje.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gaohongyu789.top/Article/details/gtvdpnxsxm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.9152youxi.cn/Article/details/gtmlmxizye.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cucudq.cn/Article/details/gtedowseku.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gtklxbdzvn.html

Py:   os.getcwd()
来源：http://dali.jqgfzy.top/Article/details/gtmiwxklhj.html

PHP:  getcwd();
来源：http://dali.aibaodan.cn/Article/details/gtzjneicfp.html

JS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gtdrqgekpg.html

TS:   process.cwd()
来源：http://dali.aizwys.cn/Article/details/gtasoyozuj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.vqdsnc.cn/Article/details/gtriwfrlhl.html

Go:   os.Getwd()
来源：http://dali.jyoumei.cn/Article/details/gtyhdoorip.html

Ruby: Dir.pwd
来源：http://dali.hnqzz.top/Article/details/gtjovhakec.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhoulong.xyz/Article/details/gtahgpkmih.html

[M05] 设置退出码
来源：http://dali.jiagoushi.top/Article/details/gtkawgrcaf.html

Py:   sys.exit(1)
来源：http://dali.havefunace.top/Article/details/gtxtqyeyqe.html

PHP:  exit(1);
来源：http://dali.cucudq.cn/Article/details/gtgnzdyyrf.html

JS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtcecntpue.html

TS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtzuvkoxuo.html

Java: System.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtopgqyrmd.html

Go:   os.Exit(1)
来源：http://dali.jianghu66.top/Article/details/gtwqkupyab.html

Ruby: exit 1
来源：http://dali.9152youxi.cn/Article/details/gtkjbwpnki.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.0kj1m.cn/Article/details/gtmgehuxro.html

[M06] 向标准错误输出
来源：http://dali.yanxiufei.cn/Article/details/gtdypyuifs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gtadhgwkal.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yonumen.top/Article/details/gtdpsridmv.html

JS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gttyjvaotx.html

TS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gtmfkukzrc.html

Java: System.err.println("err")
来源：http://dali.guowangkeji.top/Article/details/gtdliqidah.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tianlin.xyz/Article/details/gtrpstrntk.html

Ruby: warn "err"
来源：http://dali.cqqwz.cn/Article/details/gtqqjyhqel.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.smart0.xyz/Article/details/gtwlwjffta.html

[M07] 判断是否为主入口
来源：http://dali.jqgfzy.top/Article/details/gthteqthud.html

Py:   if __name__ == "__main__":
来源：http://dali.daria6918.cn/Article/details/gtivdhuogd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cashguo.top/Article/details/gtxjivygjt.html

JS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gtswoeigkr.html

TS:   require.main === module
来源：http://dali.kuanghao11.cn/Article/details/gtoszloxlg.html

Java: public static void main(String[] args)
来源：http://dali.jiagoushi.top/Article/details/gtlgsoqrib.html

Go:   func main()
来源：http://dali.xylfe.cn/Article/details/gtktxzlkcl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sufxvd.cn/Article/details/gtnytsdahw.html

C#:   static void Main(string[] args)
来源：http://dali.yuanzhike.top/Article/details/gtujpnzlop.html

[M08] 获取系统与运行时信息
来源：http://dali.svipenyu.cn/Article/details/gtsgphkynv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jlsjyb.cn/Article/details/gtstmhcfec.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhiwuduotai.top/Article/details/gtnlizbvym.html

JS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gtcvqcepxj.html

TS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltcnwwbt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yangfankeji.com/Article/details/gtjwbplmta.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xziqi.cn/Article/details/gtzxhfcxyz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hammf.cn/Article/details/gtntzqvnai.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhixingplan.top/Article/details/gtgzkgzyhn.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtszdjupcc.html

N. 数据结构与算法
来源：http://dali.zhoulong.xyz/Article/details/gtzxiduneq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtklossyou.html

[N01] 二分查找（有序数组）
来源：http://dali.ivvv.top/Article/details/gtptcpcria.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtxsbwxdlu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtevchkrwp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gthtvjrmkz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gtnwnzhkjf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtlsbxhnxc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sweek.top/Article/details/gtcvopdycu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gotoacloud.top/Article/details/gtzoxsatul.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmspvtttu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.vqdsnc.cn/Article/details/gtfwguitnz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gtrcdvmxwm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtcvclvukr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gtvljoirfs.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gtfharfrfh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fzhhl.top/Article/details/gtqpndgxoj.html

Go:   slices.Sort(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtrybisqjq.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtagwhhvlh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuetiantiany.cn/Article/details/gtjremcrgx.html

[N03] 快速排序（分治示例）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzhlbgye.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.kuanghao11.cn/Article/details/gtfhankudc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tanke756.top/Article/details/gturypcgdk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gtqisezlpu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gaohongyu789.top/Article/details/gtkdxnalrs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tanke756.top/Article/details/gtzoqioyez.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgufenzy.top/Article/details/gtlclcnsix.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangtech.top/Article/details/gtfgcjmawk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hywenlv.cn/Article/details/gtykjdegjp.html

[N04] 斐波那契数列
来源：http://dali.yonumen.top/Article/details/gthxyireie.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gttovpixgh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gtpqjvpkhw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gttpxfpqpj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtuxbyfyyb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gtbdzjugls.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhoulong.xyz/Article/details/gtkqjjuvsj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.quarkkingdee.top/Article/details/gtmevsafon.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtoateykui.html

[N05] 最大公约数
来源：http://dali.shangyingyoupin.top/Article/details/gtahmpamxz.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzwiyuis.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nwbrower.top/Article/details/gtulknozew.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gtiavixrwh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gtydjhcazb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.c1oappe.top/Article/details/gtzrkybxsw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hongshengwenyu.top/Article/details/gtprcchmct.html

Ruby: a.gcd(b)
来源：http://dali.yonumen.top/Article/details/gtkeknhpcl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258.top/Article/details/gtokzvljpv.html

[N06] 判断回文字符串
来源：http://dali.jyoumei.cn/Article/details/gtrkdaoqax.html

Py:   s == s[::-1]
来源：http://dali.guannengcc.top/Article/details/gtebwsokpp.html

PHP:  $s === strrev($s);
来源：http://dali.xuanzx.com/Article/details/gtrrdbzgfj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gthmdtylye.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtffydylgd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sxryk.cn/Article/details/gtddfdqryp.html

Go:   // 双指针从两端比较
来源：http://dali.316326.xyz/Article/details/gtlhiufosu.html

Ruby: s == s.reverse
来源：http://dali.iojbl.cn/Article/details/gtesdtkhyv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.pengpengdd.cyou/Article/details/gtedfsfwyt.html

[N07] 两数之和（返回下标）
来源：http://dali.yuanzhike.top/Article/details/gtjifltsxx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhoulong.xyz/Article/details/gtqdqjjthx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinqigfzy.top/Article/details/gticnsvhvw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj202588.top/Article/details/gtwzeeksdo.html

TS:   // 手写 Map<string, number>
来源：http://dali.xylfe.cn/Article/details/gtovckusay.html

Java: // 手写 HashMap
来源：http://dali.yj20258.top/Article/details/gtiildtxlw.html

Go:   // 手写 map[int]int
来源：http://dali.pengpengdd.cyou/Article/details/gtlghzdjrt.html

Ruby: // 手写 Hash
来源：http://dali.quarkkingdee.top/Article/details/gtwauciyoo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.kuanghao11.cn/Article/details/gtozdvshof.html

[N08] 生成全排列
来源：http://dali.gogol.net.cn/Article/details/gtslajewag.html

Py:   itertools.permutations(arr)
来源：http://dali.fzhhl.top/Article/details/gtehhtbtsx.html

PHP:  // 手写递归交换
来源：http://dali.chenlongwang.top/Article/details/gtckabeomw.html

JS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtpcarhjsy.html

TS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtskfvecao.html

Java: // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtqqdwyoxt.html

Go:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtallwclhd.html

Ruby: arr.permutation.to_a
来源：http://dali.meibo888.top/Article/details/gtfgglmdum.html

C#:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtyepcelwq.html

[N09] 栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gtthueoyjt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daria6918.cn/Article/details/gtnvznriwb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtciukvlrn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gtoutrkama.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tianlin.xyz/Article/details/gtqgcjrunl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigufen.top/Article/details/gtpstlqxlr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jyoumei.cn/Article/details/gtbalsddnd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gtkdrwwexu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nwbrower.top/Article/details/gtxipvqjks.html

[N10] 链表节点定义
来源：http://dali.wangshuangyany.cn/Article/details/gttphfszwr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yuxming.cn/Article/details/gtvhzjnfoa.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cqqwz.cn/Article/details/gtykldjsyk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ybcxt.top/Article/details/gtdbprleqp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ydzc1.top/Article/details/gtzkwemrxw.html

Java: class Node { int v; Node next; }
来源：http://dali.wangdashe.top/Article/details/gtncuefqmn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fengsongda.top/Article/details/gtgviwehau.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yangfankeji.com/Article/details/gtfpaidjmn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daxiang520.top/Article/details/gtdbvpbpby.html

[N11] 二叉树中序遍历
来源：http://dali.cqqwz.cn/Article/details/gtonnynefd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guowangkeji.top/Article/details/gtjtghvamk.html

PHP:  // 手写递归函数
来源：http://dali.zhoulong.xyz/Article/details/gtexkdhwtz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gtyovsndpl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.vqdsnc.cn/Article/details/gtqclunotf.html

Java: // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gtdspfqefq.html

Go:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gtcytozoin.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shuidangran.top/Article/details/gtqarlfypu.html

C#:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtefigqrpy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.0kj1m.cn/Article/details/gtxglwxgaq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangshuangyany.cn/Article/details/gtjyucjrcl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xziqi.cn/Article/details/gtoylhtgyq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gtrtzkfcte.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hysaishi.cn/Article/details/gtjoueyeir.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sweek.top/Article/details/gtkctjwjpy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hnxiangtu.top/Article/details/gtjdzntquw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258.top/Article/details/gtxgfunjbr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gthswuvqje.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqjupipe.html

O. 并发与异步
来源：http://dali.guannengcc.top/Article/details/gtpecwvpmc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtjrzgupks.html

[O01] 启动一个线程
来源：http://dali.yvedp.cn/Article/details/gtrmcnrmih.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hnxiangtu.top/Article/details/gtlnthlupq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xuanzx.com/Article/details/gtazrguivf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zdqjudy.top/Article/details/gtanrdycer.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gtyukresbe.html

Java: new Thread(() -> f()).start()
来源：http://dali.vqdsnc.cn/Article/details/gticeshelf.html

Go:   go f()
来源：http://dali.shangyingyoupin.top/Article/details/gtunessonp.html

Ruby: Thread.new { f }
来源：http://dali.redwolf501.top/Article/details/gtjeijuxkz.html

C#:   Task.Run(() => F());
来源：http://dali.guannengcc.top/Article/details/gtgwwfbunr.html

[O02] 使用线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtclowtxus.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xuanzx.com/Article/details/gtczdjtfec.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guowangkeji.top/Article/details/gtdwuuoqfn.html

JS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gtfmuamgbl.html

TS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gtqghhmdmk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zdqjudy.top/Article/details/gtkffwkbcs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yongpay.top/Article/details/gtxsrxpeym.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgufenzy.top/Article/details/gtbhheixxt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.birdmap.top/Article/details/gtsfqtxjcy.html

[O03] 加锁保护共享数据
来源：http://dali.daxiang520.top/Article/details/gtucxhajlg.html

Py:   with lock: shared += 1
来源：http://dali.aizwys.cn/Article/details/gtteynczjy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jlsjyb.cn/Article/details/gtxafyxvld.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gogol.net.cn/Article/details/gtsxcrbece.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiecxslfi.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gtjxfgspaf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pycfn.com/Article/details/gtxiyvzzzn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnxiangtu.top/Article/details/gtdhquxocz.html

C#:   lock (gate) { shared++; }
来源：http://dali.cucudq.cn/Article/details/gttjxtocvs.html

[O04] 定义异步函数并等待
来源：http://dali.sufxvd.cn/Article/details/gtzfrtvhlk.html

Py:   async def f():⏎    await g()
来源：http://dali.zhongyouzk.top/Article/details/gticcvfrau.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sxryk.cn/Article/details/gtuwjfhfaj.html

JS:   async function f() { await g(); }
来源：http://dali.zdqjudy.top/Article/details/gtujswsfyf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258888.top/Article/details/gtvehdqtuy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nwbrower.top/Article/details/gtnkgqzbae.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tian-w.cn/Article/details/gtotkfamkp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fengsongda.top/Article/details/gtkxjanvbz.html

C#:   async Task F() { await G(); }
来源：http://dali.hammf.cn/Article/details/gtjcfyauda.html

[O05] 并发执行并等待全部完成
来源：http://dali.yuxming.cn/Article/details/gtpehruhqm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.guowangkeji.top/Article/details/gtavfaqngg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shuidangran.top/Article/details/gtkqpszlgo.html

JS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gtxufqbjeg.html

TS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gtgnfbcoiq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jianghu66.top/Article/details/gtdnvojsgz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xuetiantiany.cn/Article/details/gtktgvmymd.html

Ruby: threads.map(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfsdossdd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ydzc1.top/Article/details/gthckpoqts.html

[O06] 使用进程池
来源：http://dali.ybcxt.top/Article/details/gtilobnbfu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ehwqpu.com/Article/details/gtmmepyxlq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgijpulr.html

JS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gtrcqvcegi.html

TS:   // child_process / cluster 模块
来源：http://dali.quarkkingdee.top/Article/details/gtkokhyrrb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuanzhike.top/Article/details/gtzbkfneop.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.fengsongda.top/Article/details/gtvvoldsdl.html

Ruby: // fork 块
来源：http://dali.daxiang520.top/Article/details/gtyjbilgte.html

C#:   Parallel.For
来源：http://dali.guannengcc.top/Article/details/gtoyqhdplz.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtfpbvesee.html

P. 常用工具函数
来源：http://dali.cucudq.cn/Article/details/gtuoxxrvvm.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtihexttjj.html

[P01] 生成 UUID
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbredmeui.html

Py:   str(uuid.uuid4())
来源：http://dali.cashguo.top/Article/details/gtsyjcojxb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nwbrower.top/Article/details/gtfeanlqkt.html

JS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gtnwzzyqbp.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gtzhtepkot.html

Java: UUID.randomUUID().toString()
来源：http://dali.9152youxi.cn/Article/details/gtdtbrbtcp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zdqjudy.top/Article/details/gtaweojkls.html

Ruby: SecureRandom.uuid
来源：http://dali.0kj1m.cn/Article/details/gtbysczdhq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.bjfxy.top/Article/details/gtfkiwkjqv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ybcxt.top/Article/details/gtodnffglm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhoulong.xyz/Article/details/gtefwlozzz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaozrrxbo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhengqikj.top/Article/details/gtepyqxbhg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.pengpengdd.cyou/Article/details/gtwddsptxb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtkrmgiiaj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtrhgmxpmz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtnwovvkqq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aibaodan.cn/Article/details/gtsccudwrr.html

[P03] 生成短随机字符串
来源：http://dali.haohaochexian.top/Article/details/gtzbtuauvo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.9152youxi.cn/Article/details/gttzycrfvm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnqzz.top/Article/details/gtivdqhhsd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gtodkntpbb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gtzcokwsql.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.meibo888.top/Article/details/gtscilaovq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zycfv.cn/Article/details/gtkrojlwbq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yueranfly.top/Article/details/gtbznkhpdo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgooprbac.html

[P04] 求长度
来源：http://dali.cheryme.top/Article/details/gtsdlxhdwq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.c1oappe.top/Article/details/gtjxbedozd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtpxcjssnm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xziqi.cn/Article/details/gtpcwnpmqh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gtfjzqywkk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.daria6918.cn/Article/details/gtplqahgow.html

Go:   len(arr);  len(m)
来源：http://dali.hnxiangtu.top/Article/details/gttjeeuztv.html

Ruby: x.length;  x.size
来源：http://dali.cucudq.cn/Article/details/gtolsfwqwd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yueranfly.top/Article/details/gtojfdxvkl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xziqi.cn/Article/details/gtefauxvea.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nanxinkj.top/Article/details/gtfgmocthk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yvedp.cn/Article/details/gtgxhqfsak.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhiwuduotai.top/Article/details/gtzwblawzb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gtrodcfyfs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ivvv.top/Article/details/gtynwhudsk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sweek.top/Article/details/gtqaoezcau.html

Ruby: a == b
来源：http://dali.cqqwz.cn/Article/details/gteesvbpru.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuanzhike.top/Article/details/gtldqjtdto.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.vqdsnc.cn/Article/details/gthsznjfmn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yvedp.cn/Article/details/gtazcvognx.html

PHP:  if (empty($x)) {}
来源：http://dali.cqqwz.cn/Article/details/gtznfywcyy.html


<!-- 参考信息 -->