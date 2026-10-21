代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gtrkjmrfpx.html

Java: resp.statusCode()
来源：http://dali.mhx1999.top/Article/details/gtjvqzirsq.html

Go:   resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gtajaolbzo.html

Ruby: resp.code.to_i
来源：http://dali.hnxiangtu.top/Article/details/gtsckbruyq.html

C#:   (int)resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gtjuyllijn.html

[L08] 并发请求多个地址
来源：http://dali.svipenyu.cn/Article/details/gtjynbdwgc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczyarjba.html

PHP:  curl_multi_init() 系列
来源：http://dali.xinyue.icu/Article/details/gtcyscegxs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtokhmzmnq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gtbwpljsid.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.316326.xyz/Article/details/gtebrazghg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ehwqpu.com/Article/details/gtxqmytlxz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hammf.cn/Article/details/gtnrhvimwq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenzaomai.com/Article/details/gtgwkdxvfy.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtrglsuzqh.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenjidiqi.icu/Article/details/gteyiljtoo.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtsnbclguw.html

[M01] 读取命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddfttlmr.html

Py:   sys.argv[1:]
来源：http://dali.cucudq.cn/Article/details/gtchuotree.html

PHP:  $argv;  $argc;
来源：http://dali.nanxinkj.top/Article/details/gtergkvnbn.html

JS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gtebuvcejb.html

TS:   process.argv.slice(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtjzhtwloh.html

Java: args 数组（main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gtcfwcepgi.html

Go:   os.Args[1:]
来源：http://dali.iojbl.cn/Article/details/gtllsfusbx.html

Ruby: ARGV
来源：http://dali.chenlongwang.top/Article/details/gtrrbluest.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gtvjnturtf.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtktygyhak.html

Py:   os.environ.get("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtqplqyuax.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258.top/Article/details/gtysmlnnoe.html

JS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gttbzilfcg.html

TS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gttcvwtehf.html

Java: System.getenv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtzjtekjjo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnqzz.top/Article/details/gtfwmqcpua.html

Ruby: ENV["HOME"]
来源：http://dali.fzhhl.top/Article/details/gtvlgumojl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sweek.top/Article/details/gtampbwazo.html

[M03] 执行外部命令
来源：http://dali.dashuyun.cn/Article/details/gtkogtbink.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cashguo.top/Article/details/gtblxuykpu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ydzc1.top/Article/details/gtvbhojzxt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhengqikj.top/Article/details/gtxobnsgls.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gthtejfkmg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shangyingyoupin.top/Article/details/gtfsihlifb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jyoumei.cn/Article/details/gtmppxscai.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sysykeji.top/Article/details/gtlkxahjnz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daxiang520.top/Article/details/gtqxauygow.html

[M04] 获取当前工作目录
来源：http://dali.hammf.cn/Article/details/gtruemocwv.html

Py:   os.getcwd()
来源：http://dali.jinqigufen.top/Article/details/gthamgllgq.html

PHP:  getcwd();
来源：http://dali.aibaodan.cn/Article/details/gttttgxalc.html

JS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtkfgcywsu.html

TS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtbybqqbba.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.feifeiyinyue.top/Article/details/gttsaxeyrk.html

Go:   os.Getwd()
来源：http://dali.havefunace.top/Article/details/gtzisbiykz.html

Ruby: Dir.pwd
来源：http://dali.aizwys.cn/Article/details/gtpwucoyhr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shangyingyoupin.top/Article/details/gtyediwdzo.html

[M05] 设置退出码
来源：http://dali.yuxming.cn/Article/details/gtgryvdbco.html

Py:   sys.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtuqjxzlys.html

PHP:  exit(1);
来源：http://dali.yuxming.cn/Article/details/gtnlaonpww.html

JS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtpibciwbx.html

TS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtoisdjwpg.html

Java: System.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtsdcgibim.html

Go:   os.Exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtkegpaflp.html

Ruby: exit 1
来源：http://dali.jiagoushi.top/Article/details/gttlmtqbwu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhixingplan.top/Article/details/gtnmmeuxvh.html

[M06] 向标准错误输出
来源：http://dali.gotoacloud.top/Article/details/gtbsnonlkd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cucudq.cn/Article/details/gtilsdmnjg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zycfv.cn/Article/details/gtnnyxwojd.html

JS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gtiwptxfwx.html

TS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gtrkdgoplh.html

Java: System.err.println("err")
来源：http://dali.xziqi.cn/Article/details/gtyehreykd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cucudq.cn/Article/details/gtnaoxybux.html

Ruby: warn "err"
来源：http://dali.fzhhl.top/Article/details/gtuxzxwwua.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ybcxt.top/Article/details/gtlypoyzkh.html

[M07] 判断是否为主入口
来源：http://dali.nwbrower.top/Article/details/gtjffmcoap.html

Py:   if __name__ == "__main__":
来源：http://dali.zhixingplan.top/Article/details/gtytlxzwbf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigfzy.top/Article/details/gtkqpvhvbc.html

JS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gtqemmhplf.html

TS:   require.main === module
来源：http://dali.snrcjt.cn/Article/details/gtnppnwziw.html

Java: public static void main(String[] args)
来源：http://dali.316326.xyz/Article/details/gtpynkguke.html

Go:   func main()
来源：http://dali.shzxlz.cn/Article/details/gtxvxbwhjr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daria6918.cn/Article/details/gteeozfibx.html

C#:   static void Main(string[] args)
来源：http://dali.cucudq.cn/Article/details/gtokzqbneg.html

[M08] 获取系统与运行时信息
来源：http://dali.bjfxy.top/Article/details/gtuhbnpwqi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gotoacloud.top/Article/details/gtexlvughi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sxryk.cn/Article/details/gtlmvkruhl.html

JS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gtgxiguwui.html

TS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtkrhkxbwk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cqqwz.cn/Article/details/gtkerhcqlu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daxiang520.top/Article/details/gtwpbejydd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptqeyktd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cashguo.top/Article/details/gtqrfnynqz.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtsdrdkcwx.html

N. 数据结构与算法
来源：http://dali.ivvv.top/Article/details/gtuazhspzu.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gthplrlraz.html

[N01] 二分查找（有序数组）
来源：http://dali.meibo888.top/Article/details/gtbphkookx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykonqjei.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.birdmap.top/Article/details/gtejhxvcsp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gtmcofzvwh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtbhqveono.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtsaszsmdl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtyhdnwyfo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hysaishi.cn/Article/details/gtoyivberq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtlwlpezft.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhoulong.xyz/Article/details/gthjrbnccl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.redwolf501.top/Article/details/gtxeywrowf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fengsongda.top/Article/details/gtpiwjnfga.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtbyawxmef.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gtqysxmctd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yonumen.top/Article/details/gtubnfiqia.html

Go:   slices.Sort(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtuodukctn.html

Ruby: arr.sort
来源：http://dali.yuanzhike.top/Article/details/gtgkbebvxi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.c1oappe.top/Article/details/gtyjfvsptt.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxuanxn.top/Article/details/gthqxafzpz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tianlin.xyz/Article/details/gtcqyohzpl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.havefunace.top/Article/details/gttrqzavfj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gtgyyebdfo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gtmkxsdezy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guowangkeji.top/Article/details/gtddiqzaww.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenlongwang.top/Article/details/gthmorrupg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.smart0.xyz/Article/details/gtxsmcfdzt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgfzy.top/Article/details/gttnusjlaa.html

[N04] 斐波那契数列
来源：http://dali.yueranfly.top/Article/details/gtankqxywi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gtooccuwtk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xylfe.cn/Article/details/gtoocbiysy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtrrkiyvsy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gtphpyipgs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gtnjveqwyi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cqqwz.cn/Article/details/gtmxgixuia.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gtdngvvpsp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtyrvogdvk.html

[N05] 最大公约数
来源：http://dali.andypj.xyz/Article/details/gtuzrltsmh.html

Py:   math.gcd(a, b)
来源：http://dali.andypj.xyz/Article/details/gtiweetqmo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tanke756.top/Article/details/gtgbxotrlf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlhxvmil.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gtcpghejel.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jqgfzy.top/Article/details/gtobilbgly.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwruyvbzx.html

Ruby: a.gcd(b)
来源：http://dali.chenzaomai.com/Article/details/gtudshcaot.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgufenzy.top/Article/details/gtzfplxxoe.html

[N06] 判断回文字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtouxxmzph.html

Py:   s == s[::-1]
来源：http://dali.cheryme.top/Article/details/gtnqsoxstu.html

PHP:  $s === strrev($s);
来源：http://dali.ehwqpu.com/Article/details/gtgoxppggc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtphgiznbv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtbzhdramr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yangfankeji.com/Article/details/gtwqirsmmi.html

Go:   // 双指针从两端比较
来源：http://dali.cheryme.top/Article/details/gtzpklufai.html

Ruby: s == s.reverse
来源：http://dali.zhengqikj.top/Article/details/gtmvlvlmiv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenlongwang.top/Article/details/gtmyjfordk.html

[N07] 两数之和（返回下标）
来源：http://dali.316326.xyz/Article/details/gtwluryoxy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cdnleiting.top/Article/details/gtcyryrsbo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.meibo888.top/Article/details/gthomkoncl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuxming.cn/Article/details/gtokxghcra.html

TS:   // 手写 Map<string, number>
来源：http://dali.zycfv.cn/Article/details/gthgvxsyrl.html

Java: // 手写 HashMap
来源：http://dali.fengsongda.top/Article/details/gtcfqwjbza.html

Go:   // 手写 map[int]int
来源：http://dali.redwolf501.top/Article/details/gtmhiqrekf.html

Ruby: // 手写 Hash
来源：http://dali.chenlongwang.top/Article/details/gtibryzxti.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.svipenyu.cn/Article/details/gtpgfcvsol.html

[N08] 生成全排列
来源：http://dali.xziqi.cn/Article/details/gtbzsedxxy.html

Py:   itertools.permutations(arr)
来源：http://dali.ppjwa.cn/Article/details/gtqkekjzli.html

PHP:  // 手写递归交换
来源：http://dali.snrcjt.cn/Article/details/gtmsbdfpjn.html

JS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtutfzfitr.html

TS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtwetmmnfd.html

Java: // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtlxsovdke.html

Go:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtyhldztlh.html

Ruby: arr.permutation.to_a
来源：http://dali.xziqi.cn/Article/details/gtqvjsqbus.html

C#:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtxlrbjvhv.html

[N09] 栈与队列
来源：http://dali.cucudq.cn/Article/details/gtlqreokez.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.andypj.xyz/Article/details/gthpbaitae.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gtbkembuch.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gtpivadnta.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiocokqhs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxwtyxxl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hongshengwenyu.top/Article/details/gtyqmshuli.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtvcpkkcmu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ydzc1.top/Article/details/gtgckgsaaj.html

[N10] 链表节点定义
来源：http://dali.shuidangran.top/Article/details/gtndqmmtak.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.c1oappe.top/Article/details/gtuqgiubyt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigufen.top/Article/details/gtsmuivtqn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtxsimmyyf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgufenzy.top/Article/details/gtqtmqtfgv.html

Java: class Node { int v; Node next; }
来源：http://dali.yanxiufei.cn/Article/details/gtdqnkecxl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shangyingyoupin.top/Article/details/gtlowdbikv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.feifeiyinyue.top/Article/details/gtdaajatmf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xziqi.cn/Article/details/gtpyqygjoa.html

[N11] 二叉树中序遍历
来源：http://dali.aizwys.cn/Article/details/gtiafgdfre.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daria6918.cn/Article/details/gtejlrseej.html

PHP:  // 手写递归函数
来源：http://dali.nanxuanxn.top/Article/details/gtsrwdvgbk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gtxjazgjle.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gtsidefysx.html

Java: // 手写递归
来源：http://dali.yuxming.cn/Article/details/gtlrvoxgvp.html

Go:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtuznkjnzm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.0kj1m.cn/Article/details/gttmlcdtok.html

C#:   // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gtkhtvkgut.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tianlin.xyz/Article/details/gtavpgurng.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daxiang520.top/Article/details/gtqzctlulh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tian-w.cn/Article/details/gticlqbbat.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnxiangtu.top/Article/details/gttglhuxyu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258.top/Article/details/gtnphmfqom.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dashuyun.cn/Article/details/gtjxkawozk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.fzhhl.top/Article/details/gtieijizkz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj202588.top/Article/details/gtdrltdjbr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gtoavbsgup.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtyowzkapt.html

O. 并发与异步
来源：http://dali.birdmap.top/Article/details/gtsdrknqho.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtoslxdbya.html

[O01] 启动一个线程
来源：http://dali.wangshuangyany.cn/Article/details/gtogoziwcc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangdashe.top/Article/details/gtoqukktvh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnxiangtu.top/Article/details/gtkpanfxjv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hywenlv.cn/Article/details/gthubpewpk.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gtsldqfmnv.html

Java: new Thread(() -> f()).start()
来源：http://dali.fengsongda.top/Article/details/gtjtvzrmpt.html

Go:   go f()
来源：http://dali.cheryme.top/Article/details/gteawztjqk.html

Ruby: Thread.new { f }
来源：http://dali.havefunace.top/Article/details/gtcywwlgfn.html

C#:   Task.Run(() => F());
来源：http://dali.yvedp.cn/Article/details/gtxmmxbmbn.html

[O02] 使用线程池
来源：http://dali.sweek.top/Article/details/gtuafoqbon.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shuidangran.top/Article/details/gtaambzecz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.iojbl.cn/Article/details/gthwingvde.html

JS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gtuqpckjvj.html

TS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gtbttsebtu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hongshengwenyu.top/Article/details/gtshitqoyq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yangfankeji.com/Article/details/gtrflnheza.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258888.top/Article/details/gtgfebygap.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenjidiqi.icu/Article/details/gtpsprphev.html

[O03] 加锁保护共享数据
来源：http://dali.yanxiufei.cn/Article/details/gtyumcmvwz.html

Py:   with lock: shared += 1
来源：http://dali.haohaochexian.top/Article/details/gtlirhhawo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.dianchejie.cn/Article/details/gtevciguuv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fzhhl.top/Article/details/gtwdqguwmu.html

TS:   // 同 JS
来源：http://dali.yuanzhike.top/Article/details/gtgzajujlc.html

Java: synchronized (this) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpozeizkp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gogol.net.cn/Article/details/gtcnrhjska.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sxryk.cn/Article/details/gtvmaamxcf.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtofkppmvl.html

[O04] 定义异步函数并等待
来源：http://dali.zycfv.cn/Article/details/gtjxamiznk.html

Py:   async def f():⏎    await g()
来源：http://dali.xinyue.icu/Article/details/gtoheksaar.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.iojbl.cn/Article/details/gtbrytoyey.html

JS:   async function f() { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gtcdtxwfwt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gtemzqrrgq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.pengpengdd.cyou/Article/details/gttrwbylob.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.wangshuangyany.cn/Article/details/gtondvvwau.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.haohaochexian.top/Article/details/gtvqjjbvaq.html

C#:   async Task F() { await G(); }
来源：http://dali.zhoulong.xyz/Article/details/gtqjrkfidr.html

[O05] 并发执行并等待全部完成
来源：http://dali.hysaishi.cn/Article/details/gtmdihfwwm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.andypj.xyz/Article/details/gtcxualqca.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shangyingyoupin.top/Article/details/gtpjgboizj.html

JS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gtlfevsgey.html

TS:   await Promise.all(tasks)
来源：http://dali.jiagoushi.top/Article/details/gtkpawkgxz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tanke756.top/Article/details/gtjukycaww.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.iojbl.cn/Article/details/gtbdevisqx.html

Ruby: threads.map(&:join)
来源：http://dali.zhengqikj.top/Article/details/gtmeeykwpm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.9152youxi.cn/Article/details/gtpksifizj.html

[O06] 使用进程池
来源：http://dali.ydzc1.top/Article/details/gtebpiahun.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yongpay.top/Article/details/gtdajzohts.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jyoumei.cn/Article/details/gtqsokvtsu.html

JS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gtjlzvlwkn.html

TS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gtlxmypvcp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gaohongyu789.top/Article/details/gtonzyrkia.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.guannengcc.top/Article/details/gthntukmcd.html

Ruby: // fork 块
来源：http://dali.gogol.net.cn/Article/details/gtahvhjwik.html

C#:   Parallel.For
来源：http://dali.yj20258888.top/Article/details/gtyqkkpeep.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtmclefluv.html

P. 常用工具函数
来源：http://dali.xylfe.cn/Article/details/gtgevwssjn.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtwlgxvmpt.html

[P01] 生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gtfuruqtym.html

Py:   str(uuid.uuid4())
来源：http://dali.wangshuangyany.cn/Article/details/gtkbgrzpyv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.snrcjt.cn/Article/details/gtiqjwwzcl.html

JS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gtomrvjpnt.html

TS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gtaoefjoqo.html

Java: UUID.randomUUID().toString()
来源：http://dali.mhx1999.top/Article/details/gtjpvcixfw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhongyouzk.top/Article/details/gtnqgfjpyg.html

Ruby: SecureRandom.uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbuqdbnya.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guannengcc.top/Article/details/gtfrasxnrg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sxryk.cn/Article/details/gtyuvlcaph.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.meibo888.top/Article/details/gtaitnrfly.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrioticsw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtwxvzvg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gogol.net.cn/Article/details/gtgaztvomr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gteirciiiu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.quarkkingdee.top/Article/details/gtfdlescdr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtduodqwlz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuxming.cn/Article/details/gtegwcvocs.html

[P03] 生成短随机字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtxviwlcjl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pycfn.com/Article/details/gttvwlhttj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.havefunace.top/Article/details/gtxidsspre.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gtrvaerreh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gtrmnniwtc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jlsjyb.cn/Article/details/gtuiaxyjbe.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hywenlv.cn/Article/details/gtfsrhkuhd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shangyingyoupin.top/Article/details/gtwvksxpyf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yangfankeji.com/Article/details/gtwfckzqbx.html

[P04] 求长度
来源：http://dali.chenjidiqi.icu/Article/details/gtachdvfmy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ydzc1.top/Article/details/gtlartodcp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtrfxwujwm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dashuyun.cn/Article/details/gtipfowaag.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gthvwzdvia.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuxming.cn/Article/details/gtebbfophx.html

Go:   len(arr);  len(m)
来源：http://dali.cucudq.cn/Article/details/gtpwtfpyke.html

Ruby: x.length;  x.size
来源：http://dali.sxryk.cn/Article/details/gtjfyxgkts.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gtrutpjpap.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jlsjyb.cn/Article/details/gtwbrhpeyn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tanke756.top/Article/details/gtaqekdmlh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cdnleiting.top/Article/details/gtqjcjukub.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sufxvd.cn/Article/details/gtdoiitatd.html


<!-- 参考信息 -->