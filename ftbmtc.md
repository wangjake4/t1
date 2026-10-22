代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gt2ygazxyov.html

[L08] 并发请求多个地址
来源：http://dali.meibo888.top/Article/details/gt2bniihrrw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sufxvd.cn/Article/details/gt2buxcbxfc.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigufen.top/Article/details/gt2enistjfb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gt2zeazbzwe.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gt2ehwhynsv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.kuanghao11.cn/Article/details/gt2dtvqkpfb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenzaomai.com/Article/details/gt2txomxppe.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jyoumei.cn/Article/details/gt2ybwfhtuv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258.top/Article/details/gt2ivevmlbi.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2ggcgixbe.html

M. 命令行 / 进程 / 环境
来源：http://dali.hfpthk.cn/Article/details/gt2phxzyghm.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2oihkrnun.html

[M01] 读取命令行参数
来源：http://dali.gotoacloud.top/Article/details/gt2svfoscec.html

Py:   sys.argv[1:]
来源：http://dali.jqgufenzy.top/Article/details/gt2ruaalhvc.html

PHP:  $argv;  $argc;
来源：http://dali.zdqjudy.top/Article/details/gt2krbleurw.html

JS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ukoobqvw.html

TS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gt2oaajhtfx.html

Java: args 数组（main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gt2gywugdjo.html

Go:   os.Args[1:]
来源：http://dali.yj20258.top/Article/details/gt2wuqemlrl.html

Ruby: ARGV
来源：http://dali.zhengqikj.top/Article/details/gt2eszfhacg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gt2hibnbojh.html

[M02] 读取环境变量
来源：http://dali.wangdashe.top/Article/details/gt2ikdhfoea.html

Py:   os.environ.get("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gt2xameyuyx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gt2lnwclkcg.html

JS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gt2wxuupnqf.html

TS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gt2pmnniykr.html

Java: System.getenv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gt2riejoxxj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gt2qxgpuyef.html

Ruby: ENV["HOME"]
来源：http://dali.xziqi.cn/Article/details/gt2petkgpxa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gt2kjgivqaa.html

[M03] 执行外部命令
来源：http://dali.feifeiyinyue.top/Article/details/gt2alemdwaq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sufxvd.cn/Article/details/gt2znjlqcrl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnxiangtu.top/Article/details/gt2xlynzflh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gt2jdpjtdfb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gt2aujfxrwn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tianlin.xyz/Article/details/gt2ronznlxp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gt2xiienpzr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenjidiqi.icu/Article/details/gt2lmfnoakk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.0kj1m.cn/Article/details/gt2hmcmkllm.html

[M04] 获取当前工作目录
来源：http://dali.sweek.top/Article/details/gt2hwxtvkkm.html

Py:   os.getcwd()
来源：http://dali.hysaishi.cn/Article/details/gt2tmwuyqoi.html

PHP:  getcwd();
来源：http://dali.xuetiantiany.cn/Article/details/gt2emreltng.html

JS:   process.cwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2divfpctc.html

TS:   process.cwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2uncybcdb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ovwbxcjx.html

Go:   os.Getwd()
来源：http://dali.9152youxi.cn/Article/details/gt2ysycrasg.html

Ruby: Dir.pwd
来源：http://dali.hnxiangtu.top/Article/details/gt2pnwrnumx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aizwys.cn/Article/details/gt2ykdjsoxh.html

[M05] 设置退出码
来源：http://dali.ydzc1.top/Article/details/gt2vwkgaxet.html

Py:   sys.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2oqauiwsc.html

PHP:  exit(1);
来源：http://dali.pycfn.com/Article/details/gt2ncfefvqv.html

JS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gt2vdssiqjz.html

TS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gt2boarqado.html

Java: System.exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2jljhetom.html

Go:   os.Exit(1)
来源：http://dali.smart0.xyz/Article/details/gt2nvwbtsmd.html

Ruby: exit 1
来源：http://dali.jlsjyb.cn/Article/details/gt2ulhxqywj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhongyouzk.top/Article/details/gt2dxcqvfdz.html

[M06] 向标准错误输出
来源：http://dali.ivvv.top/Article/details/gt2ulfhsyyi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ehwqpu.com/Article/details/gt2lbzhkmba.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ydzc1.top/Article/details/gt2bknbrknl.html

JS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gt2kezphpxo.html

TS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gt2rslffxxj.html

Java: System.err.println("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qmfgoyfz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.c1oappe.top/Article/details/gt2lvqgundn.html

Ruby: warn "err"
来源：http://dali.xuanzx.com/Article/details/gt2qeouiwbw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxuanxn.top/Article/details/gt2qpjocypz.html

[M07] 判断是否为主入口
来源：http://dali.sysykeji.top/Article/details/gt2xmpymuub.html

Py:   if __name__ == "__main__":
来源：http://dali.chenjidiqi.icu/Article/details/gt2byavidmj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kpygqdcd.html

JS:   require.main === module
来源：http://dali.sweek.top/Article/details/gt2raijyudu.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gt2vakwgwbk.html

Java: public static void main(String[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gt2goubkvdm.html

Go:   func main()
来源：http://dali.daxiang520.top/Article/details/gt2jbxhiswe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sufxvd.cn/Article/details/gt2vbjvumkz.html

C#:   static void Main(string[] args)
来源：http://dali.guannengcc.top/Article/details/gt2thfhpzng.html

[M08] 获取系统与运行时信息
来源：http://dali.meibo888.top/Article/details/gt2cgarmpvb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tanke756.top/Article/details/gt2ivhpcfzn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.havefunace.top/Article/details/gt2fupeitda.html

JS:   process.platform;  process.version
来源：http://dali.zhixingplan.top/Article/details/gt2ndhsuvuc.html

TS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gt2ibwtwpto.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hammf.cn/Article/details/gt2uqjencwf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yueranfly.top/Article/details/gt2bvalfdip.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxuanxn.top/Article/details/gt2usgxmxab.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.kuanghao11.cn/Article/details/gt2fhkkvhnp.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2oygdhsap.html

N. 数据结构与算法
来源：http://dali.zhixingplan.top/Article/details/gt2oyigsozp.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2yzetrhbs.html

[N01] 二分查找（有序数组）
来源：http://dali.bjfxy.top/Article/details/gt2ksqnaxkz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jianghu66.top/Article/details/gt2ktiemzqq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gt2mmvvaxpi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gt2fwmpafgk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gt2gmjtzoqz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2pkvxtltg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.andypj.xyz/Article/details/gt2ocmgzxau.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dashuyun.cn/Article/details/gt2inpcdbhz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2ewwcrfsk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.9152youxi.cn/Article/details/gt2igcribiy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gt2lbggtwda.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.birdmap.top/Article/details/gt2xvigczgu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gt2ijuyexax.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gt2rgzisxay.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ehwqpu.com/Article/details/gt2bnohanao.html

Go:   slices.Sort(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2dluiiome.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gt2zzdjgywa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.c1oappe.top/Article/details/gt2sspuysik.html

[N03] 快速排序（分治示例）
来源：http://dali.yueranfly.top/Article/details/gt2cancxfhf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jlsjyb.cn/Article/details/gt2tfapwtda.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aizwys.cn/Article/details/gt2ncvbyfqx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gt2wirwepoy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxinkj.top/Article/details/gt2soakyrme.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigfzy.top/Article/details/gt2voxlkldb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yangfankeji.com/Article/details/gt2yofllhhd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhoulong.xyz/Article/details/gt2lzzjmkja.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258888.top/Article/details/gt2sameuytm.html

[N04] 斐波那契数列
来源：http://dali.zhoulong.xyz/Article/details/gt2yqyozaya.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2cymgdsks.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mxdngucp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gt2ersdxhtp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gt2mpdkxhtp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gt2kkeojhvm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jqgfzy.top/Article/details/gt2dlzzmzec.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qldsvjnb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ynyzopam.html

[N05] 最大公约数
来源：http://dali.yvedp.cn/Article/details/gt2tmpdzwwb.html

Py:   math.gcd(a, b)
来源：http://dali.hywenlv.cn/Article/details/gt2zlhtntgx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnqzz.top/Article/details/gt2henttamb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gt2szcxabvq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gt2lwepcowi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daxiang520.top/Article/details/gt2xjxyncfl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dianchejie.cn/Article/details/gt2xialnlnx.html

Ruby: a.gcd(b)
来源：http://dali.zhixingplan.top/Article/details/gt2meplndtt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xziqi.cn/Article/details/gt2sxsslklw.html

[N06] 判断回文字符串
来源：http://dali.sysykeji.top/Article/details/gt2oubqdrdc.html

Py:   s == s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gt2soqedwhs.html

PHP:  $s === strrev($s);
来源：http://dali.smart0.xyz/Article/details/gt2aaanejyi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gt2cvcakdmn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gt2jquowwkm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ivvv.top/Article/details/gt2sxucvzkz.html

Go:   // 双指针从两端比较
来源：http://dali.gaohongyu789.top/Article/details/gt2blktdbhr.html

Ruby: s == s.reverse
来源：http://dali.hywenlv.cn/Article/details/gt2drmjpxly.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gt2rjwrimon.html

[N07] 两数之和（返回下标）
来源：http://dali.zhixingplan.top/Article/details/gt2olgjpdxl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenjidiqi.icu/Article/details/gt2ayajvcpy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tanke756.top/Article/details/gt2dmtovowl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hywenlv.cn/Article/details/gt2konuhttq.html

TS:   // 手写 Map<string, number>
来源：http://dali.jlsjyb.cn/Article/details/gt2ytkipala.html

Java: // 手写 HashMap
来源：http://dali.hnxiangtu.top/Article/details/gt2lhuvvbey.html

Go:   // 手写 map[int]int
来源：http://dali.svipenyu.cn/Article/details/gt2owllxqml.html

Ruby: // 手写 Hash
来源：http://dali.chenjidiqi.icu/Article/details/gt2bemwzkfb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.birdmap.top/Article/details/gt2iqhlyhim.html

[N08] 生成全排列
来源：http://dali.yvedp.cn/Article/details/gt2kbnzboxh.html

Py:   itertools.permutations(arr)
来源：http://dali.yueranfly.top/Article/details/gt2nboswqnk.html

PHP:  // 手写递归交换
来源：http://dali.chenlongwang.top/Article/details/gt2gwyoklsm.html

JS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gt2fykiyoin.html

TS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gt2lpklpgwq.html

Java: // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2usrvrhqi.html

Go:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gt2efphkybx.html

Ruby: arr.permutation.to_a
来源：http://dali.kuanghao11.cn/Article/details/gt2isoneopu.html

C#:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gt2qtvhihty.html

[N09] 栈与队列
来源：http://dali.smart0.xyz/Article/details/gt2bmwdsjpv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cashguo.top/Article/details/gt2rhwsrqcn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.guannengcc.top/Article/details/gt2fvzysoof.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dqlfedxb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhengqikj.top/Article/details/gt2qlgmubwq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cuyihqwr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.quarkkingdee.top/Article/details/gt2nkhejyhd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gt2scpvxyqx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cdnleiting.top/Article/details/gt2vitkwdgc.html

[N10] 链表节点定义
来源：http://dali.dianchejie.cn/Article/details/gt2sayxmrce.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ehrtbckx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.0kj1m.cn/Article/details/gt2rstdchlg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenzaomai.com/Article/details/gt2bbrlcjej.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.quarkkingdee.top/Article/details/gt2cncsnvvp.html

Java: class Node { int v; Node next; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ccimhnuz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenjidiqi.icu/Article/details/gt2udzgmefg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gzhubu.top/Article/details/gt2pfrncpmg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ajcsmiam.html

[N11] 二叉树中序遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2djlyxgck.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.feifeiyinyue.top/Article/details/gt2adornaxm.html

PHP:  // 手写递归函数
来源：http://dali.haohaochexian.top/Article/details/gt2ypiksxrt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sufxvd.cn/Article/details/gt2fcsxpolm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gt2ebikoajf.html

Java: // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gt2pqssuzgb.html

Go:   // 手写递归
来源：http://dali.yongpay.top/Article/details/gt2mgmmmkvs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gaohongyu789.top/Article/details/gt2wgfccrff.html

C#:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gt2jpvkbueh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangshuangyany.cn/Article/details/gt2qwjepdla.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zycfv.cn/Article/details/gt2xcigteau.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.redwolf501.top/Article/details/gt2baiettid.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhixingplan.top/Article/details/gt2nbtyjbwn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shangyingyoupin.top/Article/details/gt2obhwpvih.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tianlin.xyz/Article/details/gt2ppzykrop.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258.top/Article/details/gt2akzekhpz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxuanxn.top/Article/details/gt2maqvdnkx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gt2qejehfrq.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2gyywnpgt.html

O. 并发与异步
来源：http://dali.9152youxi.cn/Article/details/gt2mxthsspj.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2taedrukd.html

[O01] 启动一个线程
来源：http://dali.sufxvd.cn/Article/details/gt2qjvaivfl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhoulong.xyz/Article/details/gt2mipsuzjz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhoulong.xyz/Article/details/gt2uhztxqmj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnqzz.top/Article/details/gt2ebilerlx.html

TS:   // 同 JS
来源：http://dali.xinyue.icu/Article/details/gt2wwufivau.html

Java: new Thread(() -> f()).start()
来源：http://dali.hammf.cn/Article/details/gt2xrqehqwb.html

Go:   go f()
来源：http://dali.zhengqikj.top/Article/details/gt2zgrecgmw.html

Ruby: Thread.new { f }
来源：http://dali.wangshuangyany.cn/Article/details/gt2sbkypcno.html

C#:   Task.Run(() => F());
来源：http://dali.hywenlv.cn/Article/details/gt2yroxfmhg.html

[O02] 使用线程池
来源：http://dali.zhiwuduotai.top/Article/details/gt2uumxlgdp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aizwys.cn/Article/details/gt2ajzxkadq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.quarkkingdee.top/Article/details/gt2emuwblit.html

JS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gt2orzbmjpi.html

TS:   // worker_threads 线程池
来源：http://dali.yanxiufei.cn/Article/details/gt2cvlpkrgn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.meibo888.top/Article/details/gt2jejeadog.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cdnleiting.top/Article/details/gt2vsfnjlab.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yangfankeji.com/Article/details/gt2bjuzaplp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guowangkeji.top/Article/details/gt2bzxbsush.html

[O03] 加锁保护共享数据
来源：http://dali.jyoumei.cn/Article/details/gt2aovvmtbb.html

Py:   with lock: shared += 1
来源：http://dali.yj20258.top/Article/details/gt2njwtrhot.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yueranfly.top/Article/details/gt2ldhxokmd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fzhhl.top/Article/details/gt2ohmwyzzx.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gt2srjrzcse.html

Java: synchronized (this) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gt2jdnpvobb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.316326.xyz/Article/details/gt2ltqpaebx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gxlkupin.html

C#:   lock (gate) { shared++; }
来源：http://dali.aibaodan.cn/Article/details/gt2zfkinqcf.html

[O04] 定义异步函数并等待
来源：http://dali.andypj.xyz/Article/details/gt2qpjlcswb.html

Py:   async def f():⏎    await g()
来源：http://dali.wangshuangyany.cn/Article/details/gt2pruumyzd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj202588.top/Article/details/gt2jcxcnpaj.html

JS:   async function f() { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gt2tourehli.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hammf.cn/Article/details/gt2uhjougax.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daxiang520.top/Article/details/gt2befgbvxi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.guowangkeji.top/Article/details/gt2ajixluns.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenjidiqi.icu/Article/details/gt2gunfmnep.html

C#:   async Task F() { await G(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ezsfvnxz.html

[O05] 并发执行并等待全部完成
来源：http://dali.gaohongyu789.top/Article/details/gt2uwatlfeq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgufenzy.top/Article/details/gt2qdgzwpdn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenjidiqi.icu/Article/details/gt2pqujtuql.html

JS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gt2zvmworyl.html

TS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mtsmbmqy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.haohaochexian.top/Article/details/gt2shumplww.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.bjfxy.top/Article/details/gt2edfuaruy.html

Ruby: threads.map(&:join)
来源：http://dali.sufxvd.cn/Article/details/gt2ztjcxlyj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cashguo.top/Article/details/gt2skpnuamy.html

[O06] 使用进程池
来源：http://dali.ehwqpu.com/Article/details/gt2psncheug.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tanke756.top/Article/details/gt2unhoumkc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.dianchejie.cn/Article/details/gt2fvwqctgm.html

JS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gt2trmlzjou.html

TS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gt2ohycvhrt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjitcnq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hongshengwenyu.top/Article/details/gt2hyvbnoel.html

Ruby: // fork 块
来源：http://dali.cashguo.top/Article/details/gt2oqnzdurh.html

C#:   Parallel.For
来源：http://dali.ydzc1.top/Article/details/gt2qnakmaly.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2inqeitkd.html

P. 常用工具函数
来源：http://dali.sweek.top/Article/details/gt2yudcfoze.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2faugrcna.html

[P01] 生成 UUID
来源：http://dali.daxiang520.top/Article/details/gt2vcfwwogd.html

Py:   str(uuid.uuid4())
来源：http://dali.sxryk.cn/Article/details/gt2mlytvpin.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gt2tlnkfnwj.html

JS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gt2cgcdawti.html

TS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gt2frkebnhs.html

Java: UUID.randomUUID().toString()
来源：http://dali.guannengcc.top/Article/details/gt2rcrtdvbf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gogol.net.cn/Article/details/gt2ddtbaogl.html

Ruby: SecureRandom.uuid
来源：http://dali.tianlin.xyz/Article/details/gt2abhdrkvq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jianghu66.top/Article/details/gt2npdwoeyv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gaohongyu789.top/Article/details/gt2ozhdlnxk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.smart0.xyz/Article/details/gt2zycbplln.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yangfankeji.com/Article/details/gt2jokuqrzz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yonumen.top/Article/details/gt2knbzrlut.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnqzz.top/Article/details/gt2aycekldq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cucudq.cn/Article/details/gt2ltqebdmz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jlsjyb.cn/Article/details/gt2dzafusoe.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.iojbl.cn/Article/details/gt2nbgastsb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pycfn.com/Article/details/gt2qzlpqbnm.html

[P03] 生成短随机字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wqztpqdn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.dashuyun.cn/Article/details/gt2wpoeulvl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgfzy.top/Article/details/gt2qwhagomn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gt2ziazeahi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bnsvehtb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.fzhhl.top/Article/details/gt2winaljmq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.iojbl.cn/Article/details/gt2jffckvlc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.fzhhl.top/Article/details/gt2ndpzcqhv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guannengcc.top/Article/details/gt2qkigzttk.html

[P04] 求长度
来源：http://dali.yanxiufei.cn/Article/details/gt2sldqxpwm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.snrcjt.cn/Article/details/gt2wxtvwpzv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gt2dqbhwhhp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gt2bocicyoj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gt2wavyrgjk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.aizwys.cn/Article/details/gt2xddmdmfe.html

Go:   len(arr);  len(m)
来源：http://dali.jqgufenzy.top/Article/details/gt2tawofrbn.html

Ruby: x.length;  x.size
来源：http://dali.aibaodan.cn/Article/details/gt2uxpcgoup.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cashguo.top/Article/details/gt2rkgahaue.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gotoacloud.top/Article/details/gt2cspfxbeq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhoulong.xyz/Article/details/gt2jeraaazn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ydzc1.top/Article/details/gt2vtadtums.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hfpthk.cn/Article/details/gt2tkfjstzo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yanxiufei.cn/Article/details/gt2ygpnxhzb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hywenlv.cn/Article/details/gt2xzoikaus.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.guowangkeji.top/Article/details/gt2odnjcohx.html

Ruby: a == b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qftqvnhl.html


<!-- 参考信息 -->