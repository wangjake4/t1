代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gtdkjtqlgq.html

[L08] 并发请求多个地址
来源：http://dali.yuanzhike.top/Article/details/gtlymzkkqf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenlongwang.top/Article/details/gtqgcykzmc.html

PHP:  curl_multi_init() 系列
来源：http://dali.cdnleiting.top/Article/details/gtlscsbxvx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gtlbgifpri.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gtmnaxrecz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgufenzy.top/Article/details/gtjfcfailq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zdqjudy.top/Article/details/gtvvqbldem.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenlongwang.top/Article/details/gtwfpbywfd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyeuwdzf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtfyjqjywp.html

M. 命令行 / 进程 / 环境
来源：http://dali.yongpay.top/Article/details/gteratywfj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtsseqmlpr.html

[M01] 读取命令行参数
来源：http://dali.dianchejie.cn/Article/details/gtqfzokvsp.html

Py:   sys.argv[1:]
来源：http://dali.xylfe.cn/Article/details/gtapvokjkr.html

PHP:  $argv;  $argc;
来源：http://dali.shangyingyoupin.top/Article/details/gtgxfuojbb.html

JS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gtzoywyjru.html

TS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtdbrkfmbk.html

Java: args 数组（main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtmrpzvikt.html

Go:   os.Args[1:]
来源：http://dali.xylfe.cn/Article/details/gtamvykufc.html

Ruby: ARGV
来源：http://dali.sysykeji.top/Article/details/gtpnqfemal.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtnoihiocu.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtjuygutll.html

Py:   os.environ.get("HOME")
来源：http://dali.xinyue.icu/Article/details/gtdzainkiz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cashguo.top/Article/details/gtfkgpixqq.html

JS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gtwuoydebv.html

TS:   process.env.HOME
来源：http://dali.dashuyun.cn/Article/details/gtjxlikbfi.html

Java: System.getenv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gttobycvah.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sysykeji.top/Article/details/gttiigwwvt.html

Ruby: ENV["HOME"]
来源：http://dali.zhongyouzk.top/Article/details/gtilfbdwak.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nwbrower.top/Article/details/gtgoxwhdng.html

[M03] 执行外部命令
来源：http://dali.andypj.xyz/Article/details/gtxiubscio.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.redwolf501.top/Article/details/gtxtbmeimr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cucudq.cn/Article/details/gtwvwhbyoe.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gtymnuypni.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gtppldvphh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hfpthk.cn/Article/details/gtebcvduik.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.mhx1999.top/Article/details/gtharnouzc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nanxuanxn.top/Article/details/gtsxqgmjco.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hywenlv.cn/Article/details/gtqiqtelkm.html

[M04] 获取当前工作目录
来源：http://dali.cucudq.cn/Article/details/gtgawufhrb.html

Py:   os.getcwd()
来源：http://dali.birdmap.top/Article/details/gtjkyayktk.html

PHP:  getcwd();
来源：http://dali.mhx1999.top/Article/details/gtovismhni.html

JS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gtasiriqei.html

TS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtputnzxjq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pengpengdd.cyou/Article/details/gtfosagpte.html

Go:   os.Getwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxyjcmls.html

Ruby: Dir.pwd
来源：http://dali.zycfv.cn/Article/details/gtolkybzbt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.mhx1999.top/Article/details/gtcrkzejcw.html

[M05] 设置退出码
来源：http://dali.ydzc1.top/Article/details/gtfjgqhfcc.html

Py:   sys.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsruggym.html

PHP:  exit(1);
来源：http://dali.iojbl.cn/Article/details/gthfzdyleb.html

JS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtbsccwoeu.html

TS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtcnrugmue.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtbcpsbkbk.html

Go:   os.Exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtctrqwczh.html

Ruby: exit 1
来源：http://dali.havefunace.top/Article/details/gtrwllomeb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gotoacloud.top/Article/details/gtlnpmhpvm.html

[M06] 向标准错误输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtusdtxttk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daxiang520.top/Article/details/gtxwajoxxv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guannengcc.top/Article/details/gtflbomzfm.html

JS:   console.error("err")
来源：http://dali.xylfe.cn/Article/details/gtefkjpbnu.html

TS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gtuhzofuhu.html

Java: System.err.println("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtxgvkcmsq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fzhhl.top/Article/details/gtuekqnjnn.html

Ruby: warn "err"
来源：http://dali.shanyushiyangtech.top/Article/details/gthvumoquf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnxiangtu.top/Article/details/gtgrwzvddg.html

[M07] 判断是否为主入口
来源：http://dali.nwbrower.top/Article/details/gtluiubyjm.html

Py:   if __name__ == "__main__":
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgzvddim.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.c1oappe.top/Article/details/gtbiwdjzgx.html

JS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gtricsqkyg.html

TS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gtykrufccz.html

Java: public static void main(String[] args)
来源：http://dali.gaohongyu789.top/Article/details/gteiwsiyej.html

Go:   func main()
来源：http://dali.mhx1999.top/Article/details/gtcusbtaef.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxlsazqu.html

C#:   static void Main(string[] args)
来源：http://dali.pycfn.com/Article/details/gttlgdixjv.html

[M08] 获取系统与运行时信息
来源：http://dali.ppjwa.cn/Article/details/gtxdsbsthf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shuidangran.top/Article/details/gtpduiohnb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jlsjyb.cn/Article/details/gtauzmdscn.html

JS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gtmirwcqow.html

TS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gtsyohitbi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jianghu66.top/Article/details/gtnyuqtwcm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gzhubu.top/Article/details/gtxbqgdtfk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sysykeji.top/Article/details/gtmlcxcvpv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.bjfxy.top/Article/details/gtltndroxi.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtmzthksuz.html

N. 数据结构与算法
来源：http://dali.316326.xyz/Article/details/gtompaksad.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtmycvumwc.html

[N01] 二分查找（有序数组）
来源：http://dali.cqqwz.cn/Article/details/gtmzaupcch.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtbfkddpam.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tian-w.cn/Article/details/gtsdvabicq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtrwpcutqt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gtqrkkdkon.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gttlkfnrez.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtfxecamkr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xylfe.cn/Article/details/gthwvuumel.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtjckuzfjd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigufen.top/Article/details/gtfkvseunw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gtcbowulvb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.havefunace.top/Article/details/gtvkigggxa.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gtqiuhvczc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gtvtriskwd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.iojbl.cn/Article/details/gtrfmbedeh.html

Go:   slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gtazovhiac.html

Ruby: arr.sort
来源：http://dali.pengpengdd.cyou/Article/details/gtyfikgrpl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinqigufen.top/Article/details/gtoisjhteq.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gtsllwwmrf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.smart0.xyz/Article/details/gtpbrhzbwz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvflvryy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gtjmjsnngr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gtckdvrziv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shuidangran.top/Article/details/gtjsbhkofq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daxiang520.top/Article/details/gtsclxzxcd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gogol.net.cn/Article/details/gtyhbebcmp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yvedp.cn/Article/details/gtqtfavcei.html

[N04] 斐波那契数列
来源：http://dali.zhiwuduotai.top/Article/details/gtydjrdgxb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtembrkmgg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aizwys.cn/Article/details/gtmbffmvza.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gthjyjugdl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtkmqhnupq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gtqhnpklof.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xziqi.cn/Article/details/gtigbqjjox.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gtoklishal.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtbgffwbfd.html

[N05] 最大公约数
来源：http://dali.hongshengwenyu.top/Article/details/gtbbbixhld.html

Py:   math.gcd(a, b)
来源：http://dali.cheryme.top/Article/details/gttgtcbecs.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zdqjudy.top/Article/details/gtbsaptpnu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gtqrzydxtw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gteqxgewpp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aizwys.cn/Article/details/gtszdfghlz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.0kj1m.cn/Article/details/gtbntaclwz.html

Ruby: a.gcd(b)
来源：http://dali.dianchejie.cn/Article/details/gtfuuehdmu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tian-w.cn/Article/details/gteotgqbxv.html

[N06] 判断回文字符串
来源：http://dali.sufxvd.cn/Article/details/gtdoskptqs.html

Py:   s == s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gtoxunljal.html

PHP:  $s === strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gteipxahzb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtirtxnatt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtfbadzkit.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ybcxt.top/Article/details/gtbkzxzpza.html

Go:   // 双指针从两端比较
来源：http://dali.tianlin.xyz/Article/details/gtoxlrxzrz.html

Ruby: s == s.reverse
来源：http://dali.fengsongda.top/Article/details/gtpryspdzr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gtjpgfiljx.html

[N07] 两数之和（返回下标）
来源：http://dali.fzhhl.top/Article/details/gtylibvluy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shangyingyoupin.top/Article/details/gtpyfvigpi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.snrcjt.cn/Article/details/gtwcdrjyuz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yonumen.top/Article/details/gtferbutzs.html

TS:   // 手写 Map<string, number>
来源：http://dali.yangfankeji.com/Article/details/gtcnpfoyto.html

Java: // 手写 HashMap
来源：http://dali.shangyingyoupin.top/Article/details/gtaelvopey.html

Go:   // 手写 map[int]int
来源：http://dali.zycfv.cn/Article/details/gtjfsvwbyl.html

Ruby: // 手写 Hash
来源：http://dali.yuanzhike.top/Article/details/gthgrbaqnb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.c1oappe.top/Article/details/gtlsexfqkd.html

[N08] 生成全排列
来源：http://dali.sufxvd.cn/Article/details/gtjpijjzyc.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtarubdoyj.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gtfqpgpfwm.html

JS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtgyyjpaxg.html

TS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtgxmygzwz.html

Java: // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtgllzekdn.html

Go:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtfzoeluvn.html

Ruby: arr.permutation.to_a
来源：http://dali.xinyue.icu/Article/details/gtjmmlchdx.html

C#:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqqjflez.html

[N09] 栈与队列
来源：http://dali.zhixingplan.top/Article/details/gtaerjwfnd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.0kj1m.cn/Article/details/gtfcnhfine.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ybcxt.top/Article/details/gtthakfwfs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gteorjydzo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xinyue.icu/Article/details/gteblranpl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.haohaochexian.top/Article/details/gtnbaeeunr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cucudq.cn/Article/details/gtotounryy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtbxjzesfe.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ehwqpu.com/Article/details/gtkrpnisad.html

[N10] 链表节点定义
来源：http://dali.guowangkeji.top/Article/details/gtzogoupyr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj202588.top/Article/details/gtpglaqbdh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.316326.xyz/Article/details/gtatrivsnr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.dashuyun.cn/Article/details/gtjdzhkmhp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gotoacloud.top/Article/details/gtyffouosn.html

Java: class Node { int v; Node next; }
来源：http://dali.andypj.xyz/Article/details/gtndhbbvhp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangtech.top/Article/details/gttdlxxmli.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhoulong.xyz/Article/details/gtvhtqxxir.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgfzy.top/Article/details/gtsatyzfyf.html

[N11] 二叉树中序遍历
来源：http://dali.tian-w.cn/Article/details/gtkfnigytf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yonumen.top/Article/details/gtsazwyplz.html

PHP:  // 手写递归函数
来源：http://dali.pengpengdd.cyou/Article/details/gtvfuqrvzf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gtieejvvoh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenzaomai.com/Article/details/gtcdnormqw.html

Java: // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtggnzsduu.html

Go:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtkumbcoog.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.feifeiyinyue.top/Article/details/gtmxvmqztz.html

C#:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtmgfajwyx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fzhhl.top/Article/details/gttebpghqw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cdnleiting.top/Article/details/gtfpaxheza.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenzaomai.com/Article/details/gtwkakgazx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigufen.top/Article/details/gtllvhakju.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.snrcjt.cn/Article/details/gtologcocn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtksqldnuv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwyidfibm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shzxlz.cn/Article/details/gtpkienncm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gtlcwtnsyc.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtxrmkytga.html

O. 并发与异步
来源：http://dali.guannengcc.top/Article/details/gtnaoahegv.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtweswrxrb.html

[O01] 启动一个线程
来源：http://dali.sweek.top/Article/details/gtpdkrnleq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.andypj.xyz/Article/details/gtmzbslldq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gtvoanwtyv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xuanzx.com/Article/details/gtztkpzpvq.html

TS:   // 同 JS
来源：http://dali.pengpengdd.cyou/Article/details/gtqbnoqvrt.html

Java: new Thread(() -> f()).start()
来源：http://dali.cashguo.top/Article/details/gtvifzjhhn.html

Go:   go f()
来源：http://dali.andypj.xyz/Article/details/gtqdrypnva.html

Ruby: Thread.new { f }
来源：http://dali.jianghu66.top/Article/details/gtyqakqbng.html

C#:   Task.Run(() => F());
来源：http://dali.hammf.cn/Article/details/gtjfrankqd.html

[O02] 使用线程池
来源：http://dali.ybcxt.top/Article/details/gtflpbqllm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sufxvd.cn/Article/details/gtlwalfkgs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gtkouqjipw.html

JS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gtzmckzplf.html

TS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gtypgirdzq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ybcxt.top/Article/details/gtexfhhzad.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tianlin.xyz/Article/details/gtmerqpupk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.iojbl.cn/Article/details/gtpnbkvgok.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.meibo888.top/Article/details/gtfigyyvmv.html

[O03] 加锁保护共享数据
来源：http://dali.ybcxt.top/Article/details/gtumrnsatu.html

Py:   with lock: shared += 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgkayhyg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ehwqpu.com/Article/details/gtgfeuwgzq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sweek.top/Article/details/gtbocldbhg.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gtxpcvwnpe.html

Java: synchronized (this) { shared++; }
来源：http://dali.meibo888.top/Article/details/gtgfsbxfrp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenzaomai.com/Article/details/gtskmvmecw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangdashe.top/Article/details/gtagvfgjtg.html

C#:   lock (gate) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gtjecgohdh.html

[O04] 定义异步函数并等待
来源：http://dali.andypj.xyz/Article/details/gtenpdcrev.html

Py:   async def f():⏎    await g()
来源：http://dali.chenlongwang.top/Article/details/gtbfxvsixv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.kuanghao11.cn/Article/details/gtrxqzqybu.html

JS:   async function f() { await g(); }
来源：http://dali.yj202588.top/Article/details/gterrereaz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yueranfly.top/Article/details/gtotcncqgz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dianchejie.cn/Article/details/gtknoclnfk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.kuanghao11.cn/Article/details/gtxxiygjes.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkagldnb.html

C#:   async Task F() { await G(); }
来源：http://dali.havefunace.top/Article/details/gtpshxyfeu.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigufen.top/Article/details/gtmoeetfhh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daxiang520.top/Article/details/gtsjavunhl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj20258888.top/Article/details/gtotiiymab.html

JS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtncrcitig.html

TS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gtdtluptgf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xylfe.cn/Article/details/gthzsnwiqd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yanxiufei.cn/Article/details/gtutfhnaol.html

Ruby: threads.map(&:join)
来源：http://dali.yangfankeji.com/Article/details/gtnqigiuzy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sysykeji.top/Article/details/gtdsfglmtl.html

[O06] 使用进程池
来源：http://dali.hysaishi.cn/Article/details/gtvskajxdg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhengqikj.top/Article/details/gtrzgjmwlw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjckzinva.html

JS:   // child_process / cluster 模块
来源：http://dali.daria6918.cn/Article/details/gtqggcmvsg.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gtikmfpwsl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.quarkkingdee.top/Article/details/gtzmqdmbok.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258.top/Article/details/gtjgcberdp.html

Ruby: // fork 块
来源：http://dali.shangyingyoupin.top/Article/details/gtnuxzyabx.html

C#:   Parallel.For
来源：http://dali.yvedp.cn/Article/details/gtbusztdac.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtszgoqkqa.html

P. 常用工具函数
来源：http://dali.gogol.net.cn/Article/details/gtranryffh.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtmfmcoiio.html

[P01] 生成 UUID
来源：http://dali.hammf.cn/Article/details/gtdsqedrns.html

Py:   str(uuid.uuid4())
来源：http://dali.jinqigufen.top/Article/details/gtnbdjyqgq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guannengcc.top/Article/details/gttuckpljn.html

JS:   crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gtsfbbhqwj.html

TS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gtcjhdfoym.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtzdheyiqp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hfpthk.cn/Article/details/gthbzzfcqt.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gtenqtfhdd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gtjppozdac.html

[P02] MD5 / SHA256 摘要
来源：http://dali.svipenyu.cn/Article/details/gtmihrvgxu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xuetiantiany.cn/Article/details/gtpousivfu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aizwys.cn/Article/details/gtecpaqmdr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gotoacloud.top/Article/details/gtuewoywtf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nwbrower.top/Article/details/gtbqjzxckf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.c1oappe.top/Article/details/gtnjhoubdc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj20258888.top/Article/details/gtjcpltivx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gotoacloud.top/Article/details/gtguysljmx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhongyouzk.top/Article/details/gtgpauxnrr.html

[P03] 生成短随机字符串
来源：http://dali.gzhubu.top/Article/details/gtiekixaxe.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwdvdufq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ydzc1.top/Article/details/gtonlnidru.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gtcnwyazxs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtmmhvwefm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtcbwkfpck.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ydzc1.top/Article/details/gtogkevfpc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jiagoushi.top/Article/details/gtfffyhhhj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ehwqpu.com/Article/details/gtptettvkr.html

[P04] 求长度
来源：http://dali.pengpengdd.cyou/Article/details/gtrsnaxyny.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hnqzz.top/Article/details/gtmqnjonmf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtewgpejrk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gtysuhuvln.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yvedp.cn/Article/details/gtkkhznodg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guowangkeji.top/Article/details/gtbpeqphws.html

Go:   len(arr);  len(m)
来源：http://dali.gogol.net.cn/Article/details/gtvkyfnvbj.html

Ruby: x.length;  x.size
来源：http://dali.jlsjyb.cn/Article/details/gtthfsstwu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gttukwdocu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cqqwz.cn/Article/details/gtcuffyqrh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tianlin.xyz/Article/details/gtpyxhmdmj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.guowangkeji.top/Article/details/gtmioftmyd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gotoacloud.top/Article/details/gtaguhmnsg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhiwuduotai.top/Article/details/gthadtdndh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ivvv.top/Article/details/gtndjrpvab.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shzxlz.cn/Article/details/gtstvgtlpo.html

Ruby: a == b
来源：http://dali.chenzaomai.com/Article/details/gtmvxffhpy.html


<!-- 参考信息 -->