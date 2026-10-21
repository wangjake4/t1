代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gtvyfbykqp.html

Java: resp.statusCode()
来源：http://dali.316326.xyz/Article/details/gtfndzvabo.html

Go:   resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gtjvgiigkl.html

Ruby: resp.code.to_i
来源：http://dali.zdqjudy.top/Article/details/gtqtrowsxy.html

C#:   (int)resp.StatusCode
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsckhjtdt.html

[L08] 并发请求多个地址
来源：http://dali.shuidangran.top/Article/details/gtcmvtunfm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shzxlz.cn/Article/details/gtdytxaktw.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuanzx.com/Article/details/gtmghlbywv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtwotvrupq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gtvxeeughc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuetiantiany.cn/Article/details/gtolzpitjl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sweek.top/Article/details/gtqnfmezbd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gtfdclkfcu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gtqydahsyo.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtjjujksip.html

M. 命令行 / 进程 / 环境
来源：http://dali.daria6918.cn/Article/details/gtdqcrioyp.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtlgqgxywk.html

[M01] 读取命令行参数
来源：http://dali.hammf.cn/Article/details/gtpsdukdkb.html

Py:   sys.argv[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtcizuqcfv.html

PHP:  $argv;  $argc;
来源：http://dali.cdnleiting.top/Article/details/gtrwitbwmk.html

JS:   process.argv.slice(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikijqvqy.html

TS:   process.argv.slice(2)
来源：http://dali.zhongyouzk.top/Article/details/gtlsfonshd.html

Java: args 数组（main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gtszvfdwst.html

Go:   os.Args[1:]
来源：http://dali.gzhubu.top/Article/details/gtitdijbrg.html

Ruby: ARGV
来源：http://dali.ehwqpu.com/Article/details/gtyyjeaonj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fzhhl.top/Article/details/gtehldlzai.html

[M02] 读取环境变量
来源：http://dali.cashguo.top/Article/details/gtwnuacjde.html

Py:   os.environ.get("HOME")
来源：http://dali.fzhhl.top/Article/details/gtwclrpcma.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gtcjtpnzmo.html

JS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gtfexhvdqy.html

TS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gtrzdogmly.html

Java: System.getenv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtnprxeayi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gthlfsgkes.html

Ruby: ENV["HOME"]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpsvhatr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.mhx1999.top/Article/details/gtnvlxqjip.html

[M03] 执行外部命令
来源：http://dali.feifeiyinyue.top/Article/details/gtqbgcyukc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hywenlv.cn/Article/details/gtknaqfcto.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zycfv.cn/Article/details/gtjsbhvlup.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gtfaodxgoy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gtetyekont.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ybcxt.top/Article/details/gtbxbdwgos.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenlongwang.top/Article/details/gtrrvphdrk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnxiangtu.top/Article/details/gthctvmglk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.redwolf501.top/Article/details/gtcekzhfhg.html

[M04] 获取当前工作目录
来源：http://dali.aizwys.cn/Article/details/gtphexbjhh.html

Py:   os.getcwd()
来源：http://dali.meibo888.top/Article/details/gtpwdbunxa.html

PHP:  getcwd();
来源：http://dali.316326.xyz/Article/details/gtrguuxlxq.html

JS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gtmaibyldv.html

TS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gtfmiieupb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.bjfxy.top/Article/details/gtcbrpjwvd.html

Go:   os.Getwd()
来源：http://dali.zycfv.cn/Article/details/gtwqvzswly.html

Ruby: Dir.pwd
来源：http://dali.zycfv.cn/Article/details/gtrbnmtgru.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pengpengdd.cyou/Article/details/gtwesnkubv.html

[M05] 设置退出码
来源：http://dali.yangfankeji.com/Article/details/gtfhzougkr.html

Py:   sys.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtrodnxjqv.html

PHP:  exit(1);
来源：http://dali.xinyue.icu/Article/details/gthzquslbh.html

JS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtkferjaxu.html

TS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtmopmnjth.html

Java: System.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtteiqqltc.html

Go:   os.Exit(1)
来源：http://dali.ydzc1.top/Article/details/gtpsfesimk.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gtgnyiulbi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmbygqtj.html

[M06] 向标准错误输出
来源：http://dali.yangfankeji.com/Article/details/gtknrpaosm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tian-w.cn/Article/details/gtlvmtzybi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cheryme.top/Article/details/gtdeasmtvg.html

JS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gtsycqlyas.html

TS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gttwygheyr.html

Java: System.err.println("err")
来源：http://dali.iojbl.cn/Article/details/gtyipolvsl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnejymec.html

Ruby: warn "err"
来源：http://dali.nwbrower.top/Article/details/gtqdxfjove.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pengpengdd.cyou/Article/details/gthbmfshud.html

[M07] 判断是否为主入口
来源：http://dali.yj20258888.top/Article/details/gtmvprwyhf.html

Py:   if __name__ == "__main__":
来源：http://dali.gaohongyu789.top/Article/details/gtpzdeygvx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jyoumei.cn/Article/details/gthviikush.html

JS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gtiqkjhdap.html

TS:   require.main === module
来源：http://dali.fzhhl.top/Article/details/gtluqwpxjq.html

Java: public static void main(String[] args)
来源：http://dali.bjfxy.top/Article/details/gtdmvmogjy.html

Go:   func main()
来源：http://dali.yongpay.top/Article/details/gtzezfknvj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhiwuduotai.top/Article/details/gtzvqdlugu.html

C#:   static void Main(string[] args)
来源：http://dali.cqqwz.cn/Article/details/gtnvsgwnsq.html

[M08] 获取系统与运行时信息
来源：http://dali.hywenlv.cn/Article/details/gtfgtmvtlw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shuidangran.top/Article/details/gtzjclkosi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hammf.cn/Article/details/gtsgouoljc.html

JS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gtcdjipabr.html

TS:   process.platform;  process.version
来源：http://dali.hongshengwenyu.top/Article/details/gtjgisswum.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.havefunace.top/Article/details/gtuuuxvoqe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhiwuduotai.top/Article/details/gtqcckgqco.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ybcxt.top/Article/details/gtsdtdadah.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.9152youxi.cn/Article/details/gtwkqxfxwo.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gttkrjhoiv.html

N. 数据结构与算法
来源：http://dali.ybcxt.top/Article/details/gtltdjgllg.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtorgvjshu.html

[N01] 二分查找（有序数组）
来源：http://dali.yuanzhike.top/Article/details/gthrnqhacd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtwthwtctl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hywenlv.cn/Article/details/gtordmuixw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtcqzmtjhc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gtcczwgcrg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtlsiufsnm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuxming.cn/Article/details/gthraxeofv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jianghu66.top/Article/details/gtdxpkkcwt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gtjrvuntsl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cucudq.cn/Article/details/gtfxovgnig.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gtjolvkgwc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cucudq.cn/Article/details/gtgclnhzxy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gtapdlxpxb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtjyhvyujz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvumlxybx.html

Go:   slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gtavldkqao.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gtjazajypg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258888.top/Article/details/gtoyctsxkb.html

[N03] 快速排序（分治示例）
来源：http://dali.xylfe.cn/Article/details/gtaendoeiu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sufxvd.cn/Article/details/gtwdazyvxf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tianlin.xyz/Article/details/gtajiwqelp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gtrsivqbwh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gtwjmjtfll.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuanzx.com/Article/details/gtvcucztet.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigfzy.top/Article/details/gtfbiihwuz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangshuangyany.cn/Article/details/gtogyburdy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aizwys.cn/Article/details/gtcqefasov.html

[N04] 斐波那契数列
来源：http://dali.tian-w.cn/Article/details/gtoaekxxxe.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gtdmozfiqv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fengsongda.top/Article/details/gtijwelaaz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtchbkpdwo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtxzkuhbbg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.andypj.xyz/Article/details/gtdqaxiqhm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yueranfly.top/Article/details/gtcivsbrgv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yueranfly.top/Article/details/gtdmcjarpm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtzmwdwgns.html

[N05] 最大公约数
来源：http://dali.pycfn.com/Article/details/gtrotnbytv.html

Py:   math.gcd(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gtcgofvlys.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gotoacloud.top/Article/details/gtedhbujvk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pycfn.com/Article/details/gtbrnrdyhv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gtrbtxjmes.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hammf.cn/Article/details/gtbqltnbzb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jianghu66.top/Article/details/gtpkkckruh.html

Ruby: a.gcd(b)
来源：http://dali.ppjwa.cn/Article/details/gtxlntshgx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.feifeiyinyue.top/Article/details/gtubhfaelv.html

[N06] 判断回文字符串
来源：http://dali.c1oappe.top/Article/details/gtlujzsqzr.html

Py:   s == s[::-1]
来源：http://dali.sweek.top/Article/details/gtelwjjqsf.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gtmjtxiisv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtymwmnjwo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtbgcxhtco.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ppjwa.cn/Article/details/gteherugld.html

Go:   // 双指针从两端比较
来源：http://dali.yj20258.top/Article/details/gtqjpeueik.html

Ruby: s == s.reverse
来源：http://dali.fzhhl.top/Article/details/gtdmmxvwak.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gtnxldqjje.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgufenzy.top/Article/details/gttndokruy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gzhubu.top/Article/details/gtlgevmigm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.c1oappe.top/Article/details/gtbehyclmy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.haohaochexian.top/Article/details/gtfxvmuugg.html

TS:   // 手写 Map<string, number>
来源：http://dali.aizwys.cn/Article/details/gtyhxifmxo.html

Java: // 手写 HashMap
来源：http://dali.ehwqpu.com/Article/details/gtyodgflgi.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigfzy.top/Article/details/gtxvsxbiyc.html

Ruby: // 手写 Hash
来源：http://dali.gzhubu.top/Article/details/gtvejqjcbp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zycfv.cn/Article/details/gtqzugzxah.html

[N08] 生成全排列
来源：http://dali.cheryme.top/Article/details/gtucrjnxpq.html

Py:   itertools.permutations(arr)
来源：http://dali.cucudq.cn/Article/details/gtojultrse.html

PHP:  // 手写递归交换
来源：http://dali.zhengqikj.top/Article/details/gtarvsabyx.html

JS:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gteglpiyqh.html

TS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gttftmcuax.html

Java: // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtpoizsske.html

Go:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtmsxdetvv.html

Ruby: arr.permutation.to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzqkgboh.html

C#:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtxyjgbekx.html

[N09] 栈与队列
来源：http://dali.dianchejie.cn/Article/details/gtiuanoite.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258.top/Article/details/gtpwnnswzd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xziqi.cn/Article/details/gtpgpmxpbe.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gtoirbftku.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuetiantiany.cn/Article/details/gtvnwqxmox.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gtgryntdha.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hammf.cn/Article/details/gthquccaqy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtessypnfh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258.top/Article/details/gtmfrjnglf.html

[N10] 链表节点定义
来源：http://dali.xziqi.cn/Article/details/gtqzgamkpa.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guowangkeji.top/Article/details/gtfdqaglom.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.andypj.xyz/Article/details/gteazpsiee.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.redwolf501.top/Article/details/gtpwstherx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hywenlv.cn/Article/details/gttlgzescd.html

Java: class Node { int v; Node next; }
来源：http://dali.cqqwz.cn/Article/details/gtydlyelhg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhiwuduotai.top/Article/details/gtfsxxoonw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.havefunace.top/Article/details/gtkvcykoqe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ybcxt.top/Article/details/gtlwajpqxu.html

[N11] 二叉树中序遍历
来源：http://dali.chenlongwang.top/Article/details/gtbkpqoojw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangtech.top/Article/details/gtnemrfclh.html

PHP:  // 手写递归函数
来源：http://dali.ppjwa.cn/Article/details/gtdswwrezq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gtvzauveki.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sufxvd.cn/Article/details/gtpnfggwgd.html

Java: // 手写递归
来源：http://dali.tian-w.cn/Article/details/gtuvwyppxo.html

Go:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtvjjzaxks.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fzhhl.top/Article/details/gtjztlxtca.html

C#:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtbnxisgam.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sufxvd.cn/Article/details/gtagikivfx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tian-w.cn/Article/details/gtfhbnbeup.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ppjwa.cn/Article/details/gtjqwdehoi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xziqi.cn/Article/details/gtwcqqauwb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tanke756.top/Article/details/gtfdggnbtj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gtevfpncmw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ppjwa.cn/Article/details/gtvotcccxn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxinkj.top/Article/details/gtpeyhdeqs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gtvfcgtqnt.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtdyvtfrry.html

O. 并发与异步
来源：http://dali.jyoumei.cn/Article/details/gtnfgzhury.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtrsyxoeqa.html

[O01] 启动一个线程
来源：http://dali.zhixingplan.top/Article/details/gtyhcjywdx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daxiang520.top/Article/details/gtvjzjbilh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cashguo.top/Article/details/gtteliexpx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.birdmap.top/Article/details/gtywuksgot.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gtiqhjidyz.html

Java: new Thread(() -> f()).start()
来源：http://dali.hongshengwenyu.top/Article/details/gtwrktdcmf.html

Go:   go f()
来源：http://dali.sxryk.cn/Article/details/gtomhacnwe.html

Ruby: Thread.new { f }
来源：http://dali.sysykeji.top/Article/details/gtnuwfbene.html

C#:   Task.Run(() => F());
来源：http://dali.cqqwz.cn/Article/details/gtvypvobof.html

[O02] 使用线程池
来源：http://dali.zhengqikj.top/Article/details/gtjwapulfi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.iojbl.cn/Article/details/gtcwonocep.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cheryme.top/Article/details/gtwmphlnkf.html

JS:   // worker_threads 线程池
来源：http://dali.sxryk.cn/Article/details/gtpqqggdme.html

TS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gtbdrssksp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigufen.top/Article/details/gteytwygjl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cqqwz.cn/Article/details/gtvhwmgovi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.daxiang520.top/Article/details/gtduwutbed.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhongyouzk.top/Article/details/gtprpizjga.html

[O03] 加锁保护共享数据
来源：http://dali.ivvv.top/Article/details/gtvsinbbrd.html

Py:   with lock: shared += 1
来源：http://dali.yj20258888.top/Article/details/gtbhbldlrn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.kuanghao11.cn/Article/details/gtjyhvsady.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nwbrower.top/Article/details/gtlkqpktnt.html

TS:   // 同 JS
来源：http://dali.dashuyun.cn/Article/details/gttpqmterr.html

Java: synchronized (this) { shared++; }
来源：http://dali.ivvv.top/Article/details/gtbyokjbdf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ivvv.top/Article/details/gtmclkjham.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yangfankeji.com/Article/details/gtjkwrdfrc.html

C#:   lock (gate) { shared++; }
来源：http://dali.tian-w.cn/Article/details/gtjkcohhmk.html

[O04] 定义异步函数并等待
来源：http://dali.nanxinkj.top/Article/details/gtpvczlorr.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmnszfwy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shuidangran.top/Article/details/gtkjykyigw.html

JS:   async function f() { await g(); }
来源：http://dali.redwolf501.top/Article/details/gttppiodzq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gtucjkzrne.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gogol.net.cn/Article/details/gtwncfwxbe.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dashuyun.cn/Article/details/gtavlkgrxw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnqzz.top/Article/details/gtygawghqq.html

C#:   async Task F() { await G(); }
来源：http://dali.cucudq.cn/Article/details/gtgcfwienl.html

[O05] 并发执行并等待全部完成
来源：http://dali.jiagoushi.top/Article/details/gtdohvqzil.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jiagoushi.top/Article/details/gtaphgarih.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxuanxn.top/Article/details/gtgxmuswhz.html

JS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgcujakw.html

TS:   await Promise.all(tasks)
来源：http://dali.xziqi.cn/Article/details/gtrqigmpql.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj20258888.top/Article/details/gtpzdbfmhw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jianghu66.top/Article/details/gtmhladvsp.html

Ruby: threads.map(&:join)
来源：http://dali.aizwys.cn/Article/details/gtabcvxuyt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.316326.xyz/Article/details/gtisefqads.html

[O06] 使用进程池
来源：http://dali.jlsjyb.cn/Article/details/gtqwtgqtvy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xinyue.icu/Article/details/gtcdohqqmj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shangyingyoupin.top/Article/details/gtznpyklht.html

JS:   // child_process / cluster 模块
来源：http://dali.jyoumei.cn/Article/details/gtkwwigggx.html

TS:   // child_process / cluster 模块
来源：http://dali.cheryme.top/Article/details/gttuhapbvl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tian-w.cn/Article/details/gtnjyajhlm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gtjobgthlp.html

Ruby: // fork 块
来源：http://dali.haohaochexian.top/Article/details/gtqfrklrsl.html

C#:   Parallel.For
来源：http://dali.bjfxy.top/Article/details/gtfrrufaxd.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtjghvefai.html

P. 常用工具函数
来源：http://dali.cqqwz.cn/Article/details/gtcwupflbb.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtbqmigc.html

[P01] 生成 UUID
来源：http://dali.nanxuanxn.top/Article/details/gtzzgzzzyx.html

Py:   str(uuid.uuid4())
来源：http://dali.jinqigfzy.top/Article/details/gtfaoioudc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhwfvdxi.html

JS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gtoumdlyaf.html

TS:   crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gtvijlpqdb.html

Java: UUID.randomUUID().toString()
来源：http://dali.guannengcc.top/Article/details/gthauewvcm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sxryk.cn/Article/details/gtwusxiptt.html

Ruby: SecureRandom.uuid
来源：http://dali.yonumen.top/Article/details/gtuptfrdlf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hysaishi.cn/Article/details/gtymqnwull.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daria6918.cn/Article/details/gtecvtcibw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhljwegj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sweek.top/Article/details/gtvhnmwyfb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hysaishi.cn/Article/details/gtdvvxwnyt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhongyouzk.top/Article/details/gtlephzzkn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtvjawktjd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xuetiantiany.cn/Article/details/gtdnintqxx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.mhx1999.top/Article/details/gtcnlodpah.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cqqwz.cn/Article/details/gtrkszqtah.html

[P03] 生成短随机字符串
来源：http://dali.sxryk.cn/Article/details/gthbtkfalp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yvedp.cn/Article/details/gtmmzvzmfb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ppjwa.cn/Article/details/gtvxsigsnz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevhddntq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgfzy.top/Article/details/gtqtrzwwpi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hywenlv.cn/Article/details/gtiydhdhds.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinqigfzy.top/Article/details/gtligsqwnj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yueranfly.top/Article/details/gtrcnivrky.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.smart0.xyz/Article/details/gtixxmmdll.html

[P04] 求长度
来源：http://dali.hongshengwenyu.top/Article/details/gtypzqyjzc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xziqi.cn/Article/details/gtyutghkff.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtojudhjlj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gtnmijppqe.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gtuylqhuwx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tanke756.top/Article/details/gttzclttmz.html

Go:   len(arr);  len(m)
来源：http://dali.jianghu66.top/Article/details/gtizkrbfsl.html

Ruby: x.length;  x.size
来源：http://dali.cashguo.top/Article/details/gtwxhkgcud.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gogol.net.cn/Article/details/gtxdcyexge.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yongpay.top/Article/details/gtsjbaifbj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.bjfxy.top/Article/details/gtstbrhccy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhongyouzk.top/Article/details/gtvtfnpkuo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yangfankeji.com/Article/details/gtaincjbal.html


<!-- 参考信息 -->