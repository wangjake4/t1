代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gthogtvpcp.html

[L08] 并发请求多个地址
来源：http://dali.vqdsnc.cn/Article/details/gtzabuiahw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cashguo.top/Article/details/gtzbhrflrp.html

PHP:  curl_multi_init() 系列
来源：http://dali.yanxiufei.cn/Article/details/gtkcrstnqf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gtnmxxorwn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gtbdkxfkld.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.feifeiyinyue.top/Article/details/gtmfmkqzza.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gtpnythazq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cashguo.top/Article/details/gtpxdlvfyb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.0kj1m.cn/Article/details/gtlirsjgot.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtvzmfplqo.html

M. 命令行 / 进程 / 环境
来源：http://dali.kuanghao11.cn/Article/details/gtemnauvry.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtbkwdpufo.html

[M01] 读取命令行参数
来源：http://dali.ydzc1.top/Article/details/gtomhhqzye.html

Py:   sys.argv[1:]
来源：http://dali.cdnleiting.top/Article/details/gtfgkmfsgj.html

PHP:  $argv;  $argc;
来源：http://dali.jiagoushi.top/Article/details/gtrgdypseo.html

JS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtieyiajpm.html

TS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gtobfwbjyj.html

Java: args 数组（main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gtegjcqgsy.html

Go:   os.Args[1:]
来源：http://dali.chenzaomai.com/Article/details/gtgppyntuw.html

Ruby: ARGV
来源：http://dali.hnxiangtu.top/Article/details/gtbqsasedu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gtfqjvailf.html

[M02] 读取环境变量
来源：http://dali.ppjwa.cn/Article/details/gtgzqjtgwq.html

Py:   os.environ.get("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtnmoqkxzy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tanke756.top/Article/details/gtpbnmtabn.html

JS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gtehqumpbq.html

TS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gtxjrjygpk.html

Java: System.getenv("HOME")
来源：http://dali.cucudq.cn/Article/details/gtflujccbn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tian-w.cn/Article/details/gtwaaatlgb.html

Ruby: ENV["HOME"]
来源：http://dali.cheryme.top/Article/details/gtewudcgsm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jianghu66.top/Article/details/gtsderopph.html

[M03] 执行外部命令
来源：http://dali.jqgfzy.top/Article/details/gtdmdpqygd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gaohongyu789.top/Article/details/gtjjxspqxi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cqqwz.cn/Article/details/gthdmvjdnn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtkdontzay.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gtapnvrukp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangdashe.top/Article/details/gtxezicfck.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ivvv.top/Article/details/gtzffryubn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gtptkibwsp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gtrxkjfzod.html

[M04] 获取当前工作目录
来源：http://dali.jiagoushi.top/Article/details/gtcipzflwl.html

Py:   os.getcwd()
来源：http://dali.yangfankeji.com/Article/details/gtkkkbzfub.html

PHP:  getcwd();
来源：http://dali.ybcxt.top/Article/details/gthmgmhjoc.html

JS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gtjpulxnrg.html

TS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gtzaqbxxim.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yonumen.top/Article/details/gtsdjinolb.html

Go:   os.Getwd()
来源：http://dali.havefunace.top/Article/details/gtgwuxjplc.html

Ruby: Dir.pwd
来源：http://dali.sxryk.cn/Article/details/gtzpybtind.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pycfn.com/Article/details/gtdaujpztg.html

[M05] 设置退出码
来源：http://dali.vqdsnc.cn/Article/details/gtbqtfzvlw.html

Py:   sys.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtzuhzjvgp.html

PHP:  exit(1);
来源：http://dali.quarkkingdee.top/Article/details/gtdtcizdtn.html

JS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtfjjdjoji.html

TS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gtvlvniess.html

Java: System.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtqfrldkch.html

Go:   os.Exit(1)
来源：http://dali.meibo888.top/Article/details/gtkocrdoqk.html

Ruby: exit 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndoemkpu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxuanxn.top/Article/details/gtltjamhhg.html

[M06] 向标准错误输出
来源：http://dali.jinqigfzy.top/Article/details/gtrajmalvs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.havefunace.top/Article/details/gtiswxxmgu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuetiantiany.cn/Article/details/gtdwlbleeh.html

JS:   console.error("err")
来源：http://dali.jlsjyb.cn/Article/details/gtxgwwspod.html

TS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gthswbgprk.html

Java: System.err.println("err")
来源：http://dali.yanxiufei.cn/Article/details/gtpvnuadfi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sxryk.cn/Article/details/gtvizywzxf.html

Ruby: warn "err"
来源：http://dali.xuetiantiany.cn/Article/details/gtwudlbpyl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuanzhike.top/Article/details/gtcweelest.html

[M07] 判断是否为主入口
来源：http://dali.cucudq.cn/Article/details/gtqqieyusf.html

Py:   if __name__ == "__main__":
来源：http://dali.cucudq.cn/Article/details/gtnkkbvxgh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.quarkkingdee.top/Article/details/gtctkewonv.html

JS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gttgrdotsg.html

TS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gtgtqxnkrw.html

Java: public static void main(String[] args)
来源：http://dali.aibaodan.cn/Article/details/gtiaehbvge.html

Go:   func main()
来源：http://dali.cashguo.top/Article/details/gtjgsbwpcn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yanxiufei.cn/Article/details/gtcoqesvvy.html

C#:   static void Main(string[] args)
来源：http://dali.fengsongda.top/Article/details/gtptuerhfj.html

[M08] 获取系统与运行时信息
来源：http://dali.yonumen.top/Article/details/gtthtzhiis.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jianghu66.top/Article/details/gtcehaavji.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigfzy.top/Article/details/gtdulinpmw.html

JS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gtmsrkjcga.html

TS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gtrsrllybq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.mhx1999.top/Article/details/gtsddmulfu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hongshengwenyu.top/Article/details/gtxmjsusse.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guannengcc.top/Article/details/gtfxewxwyp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuanzhike.top/Article/details/gtysyrbpon.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtckdbrxke.html

N. 数据结构与算法
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgdrnrne.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtevcqyjsr.html

[N01] 二分查找（有序数组）
来源：http://dali.tianlin.xyz/Article/details/gteutynwot.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtufyglztt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtmkcjnerm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtxywdjthf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtmyslpufe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtzveykudt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtodrxazxb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.iojbl.cn/Article/details/gtbjzgnxwv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtqiqunerq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cdnleiting.top/Article/details/gtxrcyjlfz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sysykeji.top/Article/details/gtlvqzgobq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cheryme.top/Article/details/gtwzugvwgt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvctlgsd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gtldcxjmer.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sysykeji.top/Article/details/gtpjmyjfxx.html

Go:   slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gtmqnmbnwa.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gtwticmvum.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.316326.xyz/Article/details/gtdkbiztwq.html

[N03] 快速排序（分治示例）
来源：http://dali.c1oappe.top/Article/details/gtimdisxya.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gzhubu.top/Article/details/gtzgkeuxbe.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gzhubu.top/Article/details/gtalcvnktj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhixingplan.top/Article/details/gtszuahvgq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gtqqmcxrvz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ivvv.top/Article/details/gtywuiargq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hnqzz.top/Article/details/gtfyvotfcx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.smart0.xyz/Article/details/gtnkfofnjj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.bjfxy.top/Article/details/gtpvctwctb.html

[N04] 斐波那契数列
来源：http://dali.daxiang520.top/Article/details/gtqcqlhtmi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gtdxfdhmpk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gtuwpwvmip.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gtezgjgrxz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtwdqlayce.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sweek.top/Article/details/gtfuqsinrx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yonumen.top/Article/details/gtwmbkpryr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gtvlfztotc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtkhifsaxy.html

[N05] 最大公约数
来源：http://dali.yuanzhike.top/Article/details/gthyvcengn.html

Py:   math.gcd(a, b)
来源：http://dali.sweek.top/Article/details/gtpboqdhgg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gttxktivkp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtlzxaymws.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gtuetfwoaf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hysaishi.cn/Article/details/gtiqdylzmc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.quarkkingdee.top/Article/details/gtrwliuawu.html

Ruby: a.gcd(b)
来源：http://dali.yueranfly.top/Article/details/gtfpejbwjy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.c1oappe.top/Article/details/gtcxbhbihf.html

[N06] 判断回文字符串
来源：http://dali.bjfxy.top/Article/details/gtxfsolhda.html

Py:   s == s[::-1]
来源：http://dali.hfpthk.cn/Article/details/gtojikaubh.html

PHP:  $s === strrev($s);
来源：http://dali.redwolf501.top/Article/details/gtizytartv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtcerqdlcg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtbpxpzleq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xziqi.cn/Article/details/gtzoycpkaa.html

Go:   // 双指针从两端比较
来源：http://dali.sweek.top/Article/details/gtzakibfel.html

Ruby: s == s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtemxlxxqu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gtidtixdev.html

[N07] 两数之和（返回下标）
来源：http://dali.cheryme.top/Article/details/gtkjwhedex.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dashuyun.cn/Article/details/gtsaerurws.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shuidangran.top/Article/details/gtqorsutna.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgfurxek.html

TS:   // 手写 Map<string, number>
来源：http://dali.jyoumei.cn/Article/details/gtgxyasonx.html

Java: // 手写 HashMap
来源：http://dali.xylfe.cn/Article/details/gtsqryajcr.html

Go:   // 手写 map[int]int
来源：http://dali.chenzaomai.com/Article/details/gtbdtpnksj.html

Ruby: // 手写 Hash
来源：http://dali.hywenlv.cn/Article/details/gtycpakfgz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fzhhl.top/Article/details/gtgyeqpvip.html

[N08] 生成全排列
来源：http://dali.chenzaomai.com/Article/details/gtikqeqibj.html

Py:   itertools.permutations(arr)
来源：http://dali.zycfv.cn/Article/details/gtwhvbbxpr.html

PHP:  // 手写递归交换
来源：http://dali.cucudq.cn/Article/details/gtnhwsqrwp.html

JS:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtdbdznwyl.html

TS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtmfsbohxn.html

Java: // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtivmnjznx.html

Go:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtgjvmarlz.html

Ruby: arr.permutation.to_a
来源：http://dali.meibo888.top/Article/details/gtfyjpdxar.html

C#:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtaeucuzwi.html

[N09] 栈与队列
来源：http://dali.shzxlz.cn/Article/details/gtaaxsuzvr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cdnleiting.top/Article/details/gtuyowimsl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj202588.top/Article/details/gtjbxsrnkn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gtndpvkqwr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenjidiqi.icu/Article/details/gtjmcdtsqa.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258.top/Article/details/gtacnvovss.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jlsjyb.cn/Article/details/gtfyepcvvk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrvveqhs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.havefunace.top/Article/details/gtcdgryikd.html

[N10] 链表节点定义
来源：http://dali.jlsjyb.cn/Article/details/gtgrgmjwce.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xinyue.icu/Article/details/gtyqfvgbyx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hywenlv.cn/Article/details/gtydpnqiul.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fzhhl.top/Article/details/gtuqyhippe.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tianlin.xyz/Article/details/gtoeatrrfe.html

Java: class Node { int v; Node next; }
来源：http://dali.xylfe.cn/Article/details/gtvlwfgmeq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhixingplan.top/Article/details/gtntkdmtny.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.quarkkingdee.top/Article/details/gtwmzowxqb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pycfn.com/Article/details/gtqzbrodkf.html

[N11] 二叉树中序遍历
来源：http://dali.hfpthk.cn/Article/details/gtyubqycem.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hywenlv.cn/Article/details/gtjekqqhre.html

PHP:  // 手写递归函数
来源：http://dali.wangdashe.top/Article/details/gthahqaefn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gtgeqvngsc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gtdyfjlpdi.html

Java: // 手写递归
来源：http://dali.mhx1999.top/Article/details/gtwjfyxhsr.html

Go:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtrywrpchf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuanzhike.top/Article/details/gtasusxpkl.html

C#:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gtnwcnrvim.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cdnleiting.top/Article/details/gtlgaohtif.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.haohaochexian.top/Article/details/gtoqnhninf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.daria6918.cn/Article/details/gtsqsqwuyd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gtzpgeptgt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.9152youxi.cn/Article/details/gttsmbdubm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gtsqcggcdo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yonumen.top/Article/details/gtvnybseqy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxinkj.top/Article/details/gtjzuresem.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtepzrdkuw.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtoifmjghx.html

O. 并发与异步
来源：http://dali.hnqzz.top/Article/details/gtagaumwqb.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycddcqcr.html

[O01] 启动一个线程
来源：http://dali.yj20258.top/Article/details/gtmqvtnpof.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yvedp.cn/Article/details/gterfjcvsm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aizwys.cn/Article/details/gthzzcfabb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zycfv.cn/Article/details/gtpvzbbpap.html

TS:   // 同 JS
来源：http://dali.jlsjyb.cn/Article/details/gtjxmkuptw.html

Java: new Thread(() -> f()).start()
来源：http://dali.bjfxy.top/Article/details/gtuelhufpt.html

Go:   go f()
来源：http://dali.ppjwa.cn/Article/details/gtjmusxayl.html

Ruby: Thread.new { f }
来源：http://dali.zdqjudy.top/Article/details/gtrlszciwv.html

C#:   Task.Run(() => F());
来源：http://dali.wangshuangyany.cn/Article/details/gtmvgkjrxg.html

[O02] 使用线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtueivmqdy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aizwys.cn/Article/details/gtwehwrcky.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ydzc1.top/Article/details/gtymqlnjyf.html

JS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gtiksubofs.html

TS:   // worker_threads 线程池
来源：http://dali.kuanghao11.cn/Article/details/gthpaglwrc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttkerdldp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sysykeji.top/Article/details/gtssbrzgyq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.316326.xyz/Article/details/gtzvglpkas.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ppjwa.cn/Article/details/gtuyfbierj.html

[O03] 加锁保护共享数据
来源：http://dali.nanxinkj.top/Article/details/gtoakapqff.html

Py:   with lock: shared += 1
来源：http://dali.yj20258.top/Article/details/gtbmgcfcpo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jlsjyb.cn/Article/details/gtsvvikjyo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yanxiufei.cn/Article/details/gtgxauwfss.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gtvxsgjctj.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxugvvrnx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.aizwys.cn/Article/details/gthbhczgqd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yvedp.cn/Article/details/gtcmcymvfr.html

C#:   lock (gate) { shared++; }
来源：http://dali.yonumen.top/Article/details/gtdjhmuaeb.html

[O04] 定义异步函数并等待
来源：http://dali.yongpay.top/Article/details/gtddbizoet.html

Py:   async def f():⏎    await g()
来源：http://dali.xziqi.cn/Article/details/gtxuwiiwby.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuxming.cn/Article/details/gtrenxhbuo.html

JS:   async function f() { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gtegasangf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nwbrower.top/Article/details/gtaprxscbt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ybcxt.top/Article/details/gtvdqcmoux.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nwbrower.top/Article/details/gtffbixzqh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cheryme.top/Article/details/gtgajwhtlp.html

C#:   async Task F() { await G(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtghdziwnw.html

[O05] 并发执行并等待全部完成
来源：http://dali.mhx1999.top/Article/details/gtpxzmxbbz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnyrcqkrx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jqgfzy.top/Article/details/gtnrnyqudr.html

JS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gtncwsrcny.html

TS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gtmtlujaea.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.wangshuangyany.cn/Article/details/gtnrurslam.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shzxlz.cn/Article/details/gtbkceskhm.html

Ruby: threads.map(&:join)
来源：http://dali.hysaishi.cn/Article/details/gtnefzspos.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gotoacloud.top/Article/details/gtxaljzjft.html

[O06] 使用进程池
来源：http://dali.sweek.top/Article/details/gtgphwnhsw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sxryk.cn/Article/details/gtaupjkaoy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shuidangran.top/Article/details/gtfhcszxif.html

JS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gtgezxdrlx.html

TS:   // child_process / cluster 模块
来源：http://dali.daria6918.cn/Article/details/gtrlgdvlsc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gogol.net.cn/Article/details/gtufnggroq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gogol.net.cn/Article/details/gtpbmrpeib.html

Ruby: // fork 块
来源：http://dali.zhiwuduotai.top/Article/details/gtvaggpegk.html

C#:   Parallel.For
来源：http://dali.gotoacloud.top/Article/details/gtrhivfyoa.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtsmckgnyl.html

P. 常用工具函数
来源：http://dali.cqqwz.cn/Article/details/gtlmofutee.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtwtrredcm.html

[P01] 生成 UUID
来源：http://dali.ybcxt.top/Article/details/gtmvirdvtw.html

Py:   str(uuid.uuid4())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttabiccwr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjsghbzj.html

JS:   crypto.randomUUID()
来源：http://dali.yj20258888.top/Article/details/gtcutrllwz.html

TS:   crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gtinggoztz.html

Java: UUID.randomUUID().toString()
来源：http://dali.meibo888.top/Article/details/gtiabnigab.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhoulong.xyz/Article/details/gtypvbbuua.html

Ruby: SecureRandom.uuid
来源：http://dali.quarkkingdee.top/Article/details/gtxvqskvaq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yangfankeji.com/Article/details/gtaglgvyhl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.havefunace.top/Article/details/gttfyyuzwi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tanke756.top/Article/details/gteccrskug.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.bjfxy.top/Article/details/gtjsmhmbhu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.c1oappe.top/Article/details/gtpfsmxxua.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nanxinkj.top/Article/details/gthhivkrsh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.birdmap.top/Article/details/gtkudluztq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gaohongyu789.top/Article/details/gtytujjeod.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuanzhike.top/Article/details/gtiqtwobnf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hongshengwenyu.top/Article/details/gtsjypzbpx.html

[P03] 生成短随机字符串
来源：http://dali.sxryk.cn/Article/details/gtltcsynmy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xylfe.cn/Article/details/gtzqpvcclg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aibaodan.cn/Article/details/gtvqypjwlb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjuczqcff.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxinkj.top/Article/details/gtizixtslo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigfzy.top/Article/details/gtdwwrnoig.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gaohongyu789.top/Article/details/gtlfcrfmqh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jianghu66.top/Article/details/gtclquavpa.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.pycfn.com/Article/details/gthnjwyywd.html

[P04] 求长度
来源：http://dali.jianghu66.top/Article/details/gtncirhusf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.redwolf501.top/Article/details/gthyrcagrk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtterpmmtb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ivvv.top/Article/details/gtecwrhpjm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gttofulrbr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gttyeieqxa.html

Go:   len(arr);  len(m)
来源：http://dali.jiagoushi.top/Article/details/gtzseaypab.html

Ruby: x.length;  x.size
来源：http://dali.yvedp.cn/Article/details/gtpeghzviy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhixingplan.top/Article/details/gthnhcbrej.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuxming.cn/Article/details/gtyobcbkkl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cdnleiting.top/Article/details/gtnnuawgxo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jiagoushi.top/Article/details/gthsgspijj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tanke756.top/Article/details/gtjiutkovz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ydzc1.top/Article/details/gtxvctbiuw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tianlin.xyz/Article/details/gtqabsywkm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cqqwz.cn/Article/details/gthfwcyvca.html

Ruby: a == b
来源：http://dali.hammf.cn/Article/details/gtxwowzqce.html


<!-- 参考信息 -->