代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.hnxiangtu.top/Article/details/gtpjtcqcqy.html

Java: resp.statusCode()
来源：http://dali.guowangkeji.top/Article/details/gtumgfbdgv.html

Go:   resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gtmjbxvfqf.html

Ruby: resp.code.to_i
来源：http://dali.jyoumei.cn/Article/details/gtlrslvnkb.html

C#:   (int)resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gtdyfwuzrt.html

[L08] 并发请求多个地址
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrhncyqa.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtbfnqtp.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuanzx.com/Article/details/gtbdmztkfy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gttsfgynkg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtiszrsjxa.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shzxlz.cn/Article/details/gtrmzssafe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.pengpengdd.cyou/Article/details/gtoillnsmx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hammf.cn/Article/details/gtfueccyfm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daria6918.cn/Article/details/gtwhkkjgxm.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtphjrpvwz.html

M. 命令行 / 进程 / 环境
来源：http://dali.cheryme.top/Article/details/gtwmbtwoce.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtptevpswc.html

[M01] 读取命令行参数
来源：http://dali.dianchejie.cn/Article/details/gtwobptwzx.html

Py:   sys.argv[1:]
来源：http://dali.yvedp.cn/Article/details/gtdcncdezc.html

PHP:  $argv;  $argc;
来源：http://dali.jqgufenzy.top/Article/details/gtrwrtcpth.html

JS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gtwgfamiaa.html

TS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gtrjxrdctr.html

Java: args 数组（main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gtedynuatx.html

Go:   os.Args[1:]
来源：http://dali.guowangkeji.top/Article/details/gtixcgrfkf.html

Ruby: ARGV
来源：http://dali.0kj1m.cn/Article/details/gttbqhqwir.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gtntlumxjo.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtxgphraze.html

Py:   os.environ.get("HOME")
来源：http://dali.ydzc1.top/Article/details/gtvdjjqvwk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gtatzlcurg.html

JS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcscekxy.html

TS:   process.env.HOME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoketvrwa.html

Java: System.getenv("HOME")
来源：http://dali.meibo888.top/Article/details/gtxsoupzfg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtpiggcfnh.html

Ruby: ENV["HOME"]
来源：http://dali.9152youxi.cn/Article/details/gtqdfzvcfq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fzhhl.top/Article/details/gtvlmzfeyd.html

[M03] 执行外部命令
来源：http://dali.gzhubu.top/Article/details/gtadmadcls.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guannengcc.top/Article/details/gtfxnijheu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.0kj1m.cn/Article/details/gtuahygnfb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gtnvcntukj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gtfckfjhoc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cqqwz.cn/Article/details/gtieviumxj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gtnnlggqhv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.feifeiyinyue.top/Article/details/gtqwwvcvug.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenzaomai.com/Article/details/gtipmwpfvv.html

[M04] 获取当前工作目录
来源：http://dali.sufxvd.cn/Article/details/gtzdgstmeo.html

Py:   os.getcwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbwitrha.html

PHP:  getcwd();
来源：http://dali.hnqzz.top/Article/details/gtvhicfjdl.html

JS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gtutehozpp.html

TS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gtsnmfssrv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.0kj1m.cn/Article/details/gtrndgsdbe.html

Go:   os.Getwd()
来源：http://dali.hnqzz.top/Article/details/gthrnfccsj.html

Ruby: Dir.pwd
来源：http://dali.shzxlz.cn/Article/details/gtkadvtesb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxinkj.top/Article/details/gtlylyexev.html

[M05] 设置退出码
来源：http://dali.redwolf501.top/Article/details/gtbavkgrat.html

Py:   sys.exit(1)
来源：http://dali.tanke756.top/Article/details/gtrnpihzbd.html

PHP:  exit(1);
来源：http://dali.redwolf501.top/Article/details/gtcksqaoha.html

JS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtqyzyhjqh.html

TS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtabkvrekf.html

Java: System.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtxvgmqptg.html

Go:   os.Exit(1)
来源：http://dali.ydzc1.top/Article/details/gttiixmoio.html

Ruby: exit 1
来源：http://dali.zhongyouzk.top/Article/details/gtjynsovkg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hammf.cn/Article/details/gtirryxyrc.html

[M06] 向标准错误输出
来源：http://dali.zhengqikj.top/Article/details/gtniirwffr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnqzz.top/Article/details/gtwbijdqes.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgufenzy.top/Article/details/gtdsurfdxe.html

JS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtdahqzucs.html

TS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gtarzuybst.html

Java: System.err.println("err")
来源：http://dali.quarkkingdee.top/Article/details/gtsyhoxyun.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfhejrvv.html

Ruby: warn "err"
来源：http://dali.zhoulong.xyz/Article/details/gtkqasmeig.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xziqi.cn/Article/details/gtaxisbgpm.html

[M07] 判断是否为主入口
来源：http://dali.andypj.xyz/Article/details/gtdejzdukm.html

Py:   if __name__ == "__main__":
来源：http://dali.hnxiangtu.top/Article/details/gttzlbxnxi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgslwtxeh.html

JS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtqjgaanry.html

TS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gtvfuzbyqk.html

Java: public static void main(String[] args)
来源：http://dali.gogol.net.cn/Article/details/gtscijekaa.html

Go:   func main()
来源：http://dali.daxiang520.top/Article/details/gtsfcnlseo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj202588.top/Article/details/gtcvkwvwmc.html

C#:   static void Main(string[] args)
来源：http://dali.aibaodan.cn/Article/details/gttokkheve.html

[M08] 获取系统与运行时信息
来源：http://dali.yvedp.cn/Article/details/gthykikcup.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hfpthk.cn/Article/details/gtjobnsumd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sufxvd.cn/Article/details/gtojqfspzn.html

JS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gtdumnohwd.html

TS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gtnhgvquvg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xylfe.cn/Article/details/gtkmekbhks.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.feifeiyinyue.top/Article/details/gtckqgzqsp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gtjowanorb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenzaomai.com/Article/details/gtznrlwblr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtlvxdsjey.html

N. 数据结构与算法
来源：http://dali.feifeiyinyue.top/Article/details/gtjxgicrwc.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtwnxeqxrn.html

[N01] 二分查找（有序数组）
来源：http://dali.zhiwuduotai.top/Article/details/gtqpgmtdae.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtzqvcnffu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tian-w.cn/Article/details/gtlfwiltfp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gtmsoyfxyx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gtirogelso.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yonumen.top/Article/details/gtemqmgici.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwxkrqhi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hammf.cn/Article/details/gtazrmaakb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtdeaahhwi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuetiantiany.cn/Article/details/gtyjfkobnc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tanke756.top/Article/details/gttaktwnin.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jianghu66.top/Article/details/gtgphkaxvz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gtxtrnacrr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gtvygmggxz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shuidangran.top/Article/details/gteqoikveb.html

Go:   slices.Sort(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtdasemqup.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gtvhyoqblb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.0kj1m.cn/Article/details/gtrmgedrxk.html

[N03] 快速排序（分治示例）
来源：http://dali.svipenyu.cn/Article/details/gttvxikigh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhongyouzk.top/Article/details/gtlbusfyhl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.dianchejie.cn/Article/details/gtawfhxlmn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gtcgbzazsk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gtvrpytzny.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenjidiqi.icu/Article/details/gtapokcwyr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuanzx.com/Article/details/gttpafekuf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sufxvd.cn/Article/details/gtsasswapu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258888.top/Article/details/gtpbjoghiv.html

[N04] 斐波那契数列
来源：http://dali.pengpengdd.cyou/Article/details/gteawrpawc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gtvfguedug.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gtwfakndrl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtmrxkvmah.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtqrbuuyme.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gtmwghhgcn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jqgufenzy.top/Article/details/gtrqmhepng.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gtgxcjrobc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gtiertsxsa.html

[N05] 最大公约数
来源：http://dali.hywenlv.cn/Article/details/gtseharlgb.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gtedfvmgov.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cdnleiting.top/Article/details/gtvqambbfa.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gtgqovgkmf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gtshdyuebj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ivvv.top/Article/details/gtmobbdmfz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xziqi.cn/Article/details/gtxabphyfm.html

Ruby: a.gcd(b)
来源：http://dali.nwbrower.top/Article/details/gtqmdvofin.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fengsongda.top/Article/details/gtmuqwtrpu.html

[N06] 判断回文字符串
来源：http://dali.yuxming.cn/Article/details/gtctvfbdcg.html

Py:   s == s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gtmzlfzqyg.html

PHP:  $s === strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtavmfbqix.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtciewefyk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtaujodmjp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.daria6918.cn/Article/details/gtxaiflfty.html

Go:   // 双指针从两端比较
来源：http://dali.iojbl.cn/Article/details/gtdndzqdrj.html

Ruby: s == s.reverse
来源：http://dali.pycfn.com/Article/details/gtdsjolntn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gtdjkmgsay.html

[N07] 两数之和（返回下标）
来源：http://dali.9152youxi.cn/Article/details/gtisentdua.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.meibo888.top/Article/details/gthbhpoiys.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.c1oappe.top/Article/details/gtgdraohef.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhengqikj.top/Article/details/gtyaemtuxc.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhoulong.xyz/Article/details/gtrcjfljgp.html

Java: // 手写 HashMap
来源：http://dali.dianchejie.cn/Article/details/gtyuhroiff.html

Go:   // 手写 map[int]int
来源：http://dali.yongpay.top/Article/details/gtvbsolgqk.html

Ruby: // 手写 Hash
来源：http://dali.jqgufenzy.top/Article/details/gtrdyvfsey.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.feifeiyinyue.top/Article/details/gtmohzpfuj.html

[N08] 生成全排列
来源：http://dali.cheryme.top/Article/details/gtrjhtuilx.html

Py:   itertools.permutations(arr)
来源：http://dali.hywenlv.cn/Article/details/gtfihiudoc.html

PHP:  // 手写递归交换
来源：http://dali.yuanzhike.top/Article/details/gtnkawzzyx.html

JS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtlzmrscwn.html

TS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtbsomqrwy.html

Java: // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtpiqmttzu.html

Go:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtztcxagnl.html

Ruby: arr.permutation.to_a
来源：http://dali.sweek.top/Article/details/gtwumvrsll.html

C#:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtnwspgvpj.html

[N09] 栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhylmhmy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258888.top/Article/details/gtrilowids.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gtgwfpewbr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtcyewnroy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tian-w.cn/Article/details/gttatjqzys.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sufxvd.cn/Article/details/gthgcbited.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cucudq.cn/Article/details/gtpjuxclag.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtrveaobus.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenlongwang.top/Article/details/gtovaqrofj.html

[N10] 链表节点定义
来源：http://dali.xuetiantiany.cn/Article/details/gtcpuhzpic.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hongshengwenyu.top/Article/details/gtpmnxrjve.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cashguo.top/Article/details/gtdfzxzias.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.svipenyu.cn/Article/details/gtlmjptvtl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgufenzy.top/Article/details/gthxvgqbaj.html

Java: class Node { int v; Node next; }
来源：http://dali.yuxming.cn/Article/details/gtqxcmfcof.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xziqi.cn/Article/details/gtvhlzopao.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhuexgwz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hammf.cn/Article/details/gtfsdszlph.html

[N11] 二叉树中序遍历
来源：http://dali.xziqi.cn/Article/details/gtttumxzqn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.kuanghao11.cn/Article/details/gtczztngcz.html

PHP:  // 手写递归函数
来源：http://dali.jianghu66.top/Article/details/gtkldeompk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.smart0.xyz/Article/details/gtlivuogdk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtclghtnwr.html

Java: // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtwsjxzitg.html

Go:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtdnevlmgu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shuidangran.top/Article/details/gtpeeuncmf.html

C#:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtfokfopxt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shuidangran.top/Article/details/gtcvlzywlh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangdashe.top/Article/details/gtbekevehe.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigufen.top/Article/details/gtiteeidzl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gtpsnbfecu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gtukdlmayo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aibaodan.cn/Article/details/gtkgfhjrho.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cucudq.cn/Article/details/gtbomzzhmd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zycfv.cn/Article/details/gtpmpnbryt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gteyfrbtdq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtajupucmc.html

O. 并发与异步
来源：http://dali.cdnleiting.top/Article/details/gtxrgcmblg.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwvflkgr.html

[O01] 启动一个线程
来源：http://dali.smart0.xyz/Article/details/gthowjykyu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmmgqgca.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.svipenyu.cn/Article/details/gtqbytyiok.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.bjfxy.top/Article/details/gthsqxjcfv.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gtxfchsvas.html

Java: new Thread(() -> f()).start()
来源：http://dali.zycfv.cn/Article/details/gtdlwheewu.html

Go:   go f()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhborbam.html

Ruby: Thread.new { f }
来源：http://dali.yueranfly.top/Article/details/gtbpnxcawt.html

C#:   Task.Run(() => F());
来源：http://dali.shangyingyoupin.top/Article/details/gtlfcqzapy.html

[O02] 使用线程池
来源：http://dali.ivvv.top/Article/details/gtwnoupsmh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zycfv.cn/Article/details/gtsgbxoman.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258888.top/Article/details/gtwaknsbcu.html

JS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gtpiqdmnua.html

TS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gtkgfrqoiu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guannengcc.top/Article/details/gtggxzkdqo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shzxlz.cn/Article/details/gtnogxcyko.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.daxiang520.top/Article/details/gtmzisbqco.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yongpay.top/Article/details/gtbafofsdl.html

[O03] 加锁保护共享数据
来源：http://dali.xziqi.cn/Article/details/gtxgleytqu.html

Py:   with lock: shared += 1
来源：http://dali.daria6918.cn/Article/details/gtfozmzssn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymmvbxlo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xinyue.icu/Article/details/gttvwkhpzb.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gtybmkccyf.html

Java: synchronized (this) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gtjpoxqxbg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hysaishi.cn/Article/details/gtzzrptgpy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yongpay.top/Article/details/gtcxjsiopg.html

C#:   lock (gate) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gtbiryuoub.html

[O04] 定义异步函数并等待
来源：http://dali.hammf.cn/Article/details/gtcobfpajy.html

Py:   async def f():⏎    await g()
来源：http://dali.vqdsnc.cn/Article/details/gtlqortbtw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.haohaochexian.top/Article/details/gtpotycydt.html

JS:   async function f() { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpoutnhrj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gthttonazr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.birdmap.top/Article/details/gtbseeocgm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.andypj.xyz/Article/details/gtlvhptyrt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.quarkkingdee.top/Article/details/gtucxxwizw.html

C#:   async Task F() { await G(); }
来源：http://dali.cdnleiting.top/Article/details/gtxptsecre.html

[O05] 并发执行并等待全部完成
来源：http://dali.redwolf501.top/Article/details/gtzlpktufk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yuanzhike.top/Article/details/gttoldddrq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.c1oappe.top/Article/details/gtkjnvuyim.html

JS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtlnvwhkio.html

TS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gtxewkwaga.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.fengsongda.top/Article/details/gtjhqimsiq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ivvv.top/Article/details/gtxeekvvtk.html

Ruby: threads.map(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gtqfpkvllf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenzaomai.com/Article/details/gtqrdrkfpp.html

[O06] 使用进程池
来源：http://dali.yvedp.cn/Article/details/gtivbyeupx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yongpay.top/Article/details/gtiwaxjksd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cqqwz.cn/Article/details/gtbetsqvzo.html

JS:   // child_process / cluster 模块
来源：http://dali.jinqigufen.top/Article/details/gtuirizgok.html

TS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gtucdmjrxs.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hammf.cn/Article/details/gtrfkltatw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258.top/Article/details/gtelyvlgmq.html

Ruby: // fork 块
来源：http://dali.sufxvd.cn/Article/details/gtupwgtwmm.html

C#:   Parallel.For
来源：http://dali.cdnleiting.top/Article/details/gtsdouttyn.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtpqwibcxv.html

P. 常用工具函数
来源：http://dali.meibo888.top/Article/details/gtmkziylgl.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtqxyiudvj.html

[P01] 生成 UUID
来源：http://dali.0kj1m.cn/Article/details/gtcnrpjbmc.html

Py:   str(uuid.uuid4())
来源：http://dali.9152youxi.cn/Article/details/gtoellpwji.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hfpthk.cn/Article/details/gtcfzxhzie.html

JS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gtvvpyinzk.html

TS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gtnfisbckj.html

Java: UUID.randomUUID().toString()
来源：http://dali.fengsongda.top/Article/details/gtxjytceok.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gtupxlcwmh.html

Ruby: SecureRandom.uuid
来源：http://dali.nwbrower.top/Article/details/gtefuqnwof.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxuanxn.top/Article/details/gtgnyvvgxh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.0kj1m.cn/Article/details/gthsfxzlsm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nanxinkj.top/Article/details/gtabybotwd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtjkxqutgn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhoulong.xyz/Article/details/gtlgyjgndn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cucudq.cn/Article/details/gtrryktkvu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gtlzawnhqf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.feifeiyinyue.top/Article/details/gtzjrpftac.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtfoothhcn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tian-w.cn/Article/details/gttwnchwde.html

[P03] 生成短随机字符串
来源：http://dali.quarkkingdee.top/Article/details/gtibsdwacb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gotoacloud.top/Article/details/gtwocetuqc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jyoumei.cn/Article/details/gtaherlypn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gtetkycdts.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gtsygtmpjy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.fengsongda.top/Article/details/gtlwfyoprp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.fengsongda.top/Article/details/gtwijjiqip.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinqigufen.top/Article/details/gtnzewwwxd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258888.top/Article/details/gtvdzprksc.html

[P04] 求长度
来源：http://dali.nwbrower.top/Article/details/gtauekkykl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangdashe.top/Article/details/gtvdqvpiha.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gthjhvvtjw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gtimgyiwzm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.9152youxi.cn/Article/details/gtjoudwkjh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.havefunace.top/Article/details/gtpjirmpyq.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258.top/Article/details/gtunymoczh.html

Ruby: x.length;  x.size
来源：http://dali.zhixingplan.top/Article/details/gtvfprhiyg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.quarkkingdee.top/Article/details/gtazfwbort.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zycfv.cn/Article/details/gtswriqmyq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cheryme.top/Article/details/gtpyunsumf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shanyushiyangtech.top/Article/details/gtfntliovw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.feifeiyinyue.top/Article/details/gtwfrttxnq.html


<!-- 参考信息 -->