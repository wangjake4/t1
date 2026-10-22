代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gt2ttpcofda.html

Java: resp.statusCode()
来源：http://dali.zdqjudy.top/Article/details/gt2ytxnwhzp.html

Go:   resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gt2dduohfaf.html

Ruby: resp.code.to_i
来源：http://dali.birdmap.top/Article/details/gt2elksamew.html

C#:   (int)resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gt2loqncdqi.html

[L08] 并发请求多个地址
来源：http://dali.sufxvd.cn/Article/details/gt2qjidnbhf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuetiantiany.cn/Article/details/gt2gcndxqhq.html

PHP:  curl_multi_init() 系列
来源：http://dali.aibaodan.cn/Article/details/gt2xvggwcnp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gt2clnwarbw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gt2ddezlhgu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yueranfly.top/Article/details/gt2mjejxyfx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guowangkeji.top/Article/details/gt2dotzrtkd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigufen.top/Article/details/gt2pgxycebe.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.9152youxi.cn/Article/details/gt2fvtaydhd.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2qjrbfftj.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinghuilouyu.cn/Article/details/gt2owtcfter.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2eugtvioq.html

[M01] 读取命令行参数
来源：http://dali.svipenyu.cn/Article/details/gt2qlznxqdg.html

Py:   sys.argv[1:]
来源：http://dali.quarkkingdee.top/Article/details/gt2syvveoiq.html

PHP:  $argv;  $argc;
来源：http://dali.316326.xyz/Article/details/gt2gcfrucvn.html

JS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gt2zxrypzqr.html

TS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gt2fizqyqna.html

Java: args 数组（main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gt2dlmwixxb.html

Go:   os.Args[1:]
来源：http://dali.aibaodan.cn/Article/details/gt2lchbpuoa.html

Ruby: ARGV
来源：http://dali.hnxiangtu.top/Article/details/gt2nfxkqrwv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gt2nkqlinmj.html

[M02] 读取环境变量
来源：http://dali.hammf.cn/Article/details/gt2llhwriyi.html

Py:   os.environ.get("HOME")
来源：http://dali.316326.xyz/Article/details/gt2haenanrw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gt2maxejzni.html

JS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gt2watvspxr.html

TS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gt2sthnenlo.html

Java: System.getenv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gt2zysysahu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gt2oarspzjt.html

Ruby: ENV["HOME"]
来源：http://dali.zdqjudy.top/Article/details/gt2msgbhdkg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tanke756.top/Article/details/gt2gvwvebpi.html

[M03] 执行外部命令
来源：http://dali.tian-w.cn/Article/details/gt2wthmzksx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fycvcgmj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xylfe.cn/Article/details/gt2lykzsikx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gt2gthhwqhh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gt2rmfnftbc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2chmoojyy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.svipenyu.cn/Article/details/gt2bzyhbxxb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuanzx.com/Article/details/gt2qfmsirvk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.316326.xyz/Article/details/gt2cbblncdu.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gt2btvhpbin.html

Py:   os.getcwd()
来源：http://dali.jlsjyb.cn/Article/details/gt2egydcsxt.html

PHP:  getcwd();
来源：http://dali.pengpengdd.cyou/Article/details/gt2jbowbopz.html

JS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gt2liflgyig.html

TS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wyancqsw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2chyzupzf.html

Go:   os.Getwd()
来源：http://dali.0kj1m.cn/Article/details/gt2gqlzgopf.html

Ruby: Dir.pwd
来源：http://dali.hammf.cn/Article/details/gt2sadsdtgj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cucudq.cn/Article/details/gt2zwigqmut.html

[M05] 设置退出码
来源：http://dali.pycfn.com/Article/details/gt2vddzpsec.html

Py:   sys.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2ebjajsgm.html

PHP:  exit(1);
来源：http://dali.tanke756.top/Article/details/gt2bclqkjkc.html

JS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2ldzzxyqs.html

TS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gt2hvngefeb.html

Java: System.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2hirwtzpg.html

Go:   os.Exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2xxaesmxp.html

Ruby: exit 1
来源：http://dali.xinyue.icu/Article/details/gt2tdipqubx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fengsongda.top/Article/details/gt2eqbrwkuf.html

[M06] 向标准错误输出
来源：http://dali.sysykeji.top/Article/details/gt2rjhajsus.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2seijmiqd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yongpay.top/Article/details/gt2wjfnkujy.html

JS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qyqroebq.html

TS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gt2rlyiajwx.html

Java: System.err.println("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2bkistrlh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cashguo.top/Article/details/gt2svkpsswe.html

Ruby: warn "err"
来源：http://dali.haohaochexian.top/Article/details/gt2bfooeslk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2bzipyohj.html

[M07] 判断是否为主入口
来源：http://dali.zhengqikj.top/Article/details/gt2htbupote.html

Py:   if __name__ == "__main__":
来源：http://dali.yonumen.top/Article/details/gt2ezbeedfx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cdnleiting.top/Article/details/gt2wdnkifsu.html

JS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gt2xqxqzarg.html

TS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gt2yhctzdud.html

Java: public static void main(String[] args)
来源：http://dali.sysykeji.top/Article/details/gt2whusncqh.html

Go:   func main()
来源：http://dali.yuanzhike.top/Article/details/gt2uzpgtdui.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2skxflbnr.html

C#:   static void Main(string[] args)
来源：http://dali.xziqi.cn/Article/details/gt2bueurfgr.html

[M08] 获取系统与运行时信息
来源：http://dali.ybcxt.top/Article/details/gt2gdcwhrjx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.kuanghao11.cn/Article/details/gt2jvxdtpmm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yrfadutl.html

JS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gt2dpyxmcqy.html

TS:   process.platform;  process.version
来源：http://dali.jianghu66.top/Article/details/gt2qviolixv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jianghu66.top/Article/details/gt2syfyxcsh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhixingplan.top/Article/details/gt2zspsgzqb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.mhx1999.top/Article/details/gt2gqtrvloc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgfzy.top/Article/details/gt2jtzkmhlw.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2hxmemhdb.html

N. 数据结构与算法
来源：http://dali.bjfxy.top/Article/details/gt2zbosdeer.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2vanxnqfm.html

[N01] 二分查找（有序数组）
来源：http://dali.ivvv.top/Article/details/gt2wyupkyns.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hbbwbuyy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vvylmboa.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gt2dxubvsnh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gt2fdqrrxrk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gt2ofkeohmy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rmbwixmx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yueranfly.top/Article/details/gt2eakbsfxm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2qiyrugzi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shangyingyoupin.top/Article/details/gt2nipelhjk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gt2qwwbovlx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daxiang520.top/Article/details/gt2ckqmugvk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gt2djqpcsav.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gt2muhvoiaq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.0kj1m.cn/Article/details/gt2pdbpmhyo.html

Go:   slices.Sort(arr)
来源：http://dali.daria6918.cn/Article/details/gt2ysyeicql.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gt2zvzzpspm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bqfaaobd.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ojwhvxup.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fzhhl.top/Article/details/gt2jwsfdfqj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cucudq.cn/Article/details/gt2udurtrvt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gt2lafczjqi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guowangkeji.top/Article/details/gt2uepdtemt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigufen.top/Article/details/gt2datgmvyt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sufxvd.cn/Article/details/gt2ztbdmnge.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guowangkeji.top/Article/details/gt2ncfgfaas.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhoulong.xyz/Article/details/gt2ndwizazg.html

[N04] 斐波那契数列
来源：http://dali.gogol.net.cn/Article/details/gt2ftbgxhav.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gt2xtmnoyka.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2soyishyt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gt2zszbicmt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gt2ysavklwa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gt2vszasaqp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wscqkofa.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gt2fgxhrkbo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gt2enwenxfk.html

[N05] 最大公约数
来源：http://dali.0kj1m.cn/Article/details/gt2snpevxgw.html

Py:   math.gcd(a, b)
来源：http://dali.cheryme.top/Article/details/gt2lnyckmqt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258.top/Article/details/gt2utstfryt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gt2wzszomho.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.smart0.xyz/Article/details/gt2xsbmciro.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.quarkkingdee.top/Article/details/gt2clmpfjjs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuxming.cn/Article/details/gt2nwwbysln.html

Ruby: a.gcd(b)
来源：http://dali.smart0.xyz/Article/details/gt2byualcad.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sysykeji.top/Article/details/gt2vexmalog.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yrjivgre.html

Py:   s == s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gt2cukfckja.html

PHP:  $s === strrev($s);
来源：http://dali.yj20258888.top/Article/details/gt2sbpnetpf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gt2zzrkbgtm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gt2ftperqkt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.vqdsnc.cn/Article/details/gt2vrxkdvjy.html

Go:   // 双指针从两端比较
来源：http://dali.svipenyu.cn/Article/details/gt2nyctgnhm.html

Ruby: s == s.reverse
来源：http://dali.gotoacloud.top/Article/details/gt2eigtnmkv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gt2tancehnj.html

[N07] 两数之和（返回下标）
来源：http://dali.sxryk.cn/Article/details/gt2wqmmlitm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ybcxt.top/Article/details/gt2etlljrbb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.daxiang520.top/Article/details/gt2mvncuxiu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hfpthk.cn/Article/details/gt2edsfqoyh.html

TS:   // 手写 Map<string, number>
来源：http://dali.yangfankeji.com/Article/details/gt2frhtanui.html

Java: // 手写 HashMap
来源：http://dali.0kj1m.cn/Article/details/gt2emnljtkc.html

Go:   // 手写 map[int]int
来源：http://dali.xinyue.icu/Article/details/gt2luvewnka.html

Ruby: // 手写 Hash
来源：http://dali.aizwys.cn/Article/details/gt2synpwqua.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pengpengdd.cyou/Article/details/gt2nzvmxrav.html

[N08] 生成全排列
来源：http://dali.cdnleiting.top/Article/details/gt2wknkcpcv.html

Py:   itertools.permutations(arr)
来源：http://dali.daxiang520.top/Article/details/gt2zjsyyqhb.html

PHP:  // 手写递归交换
来源：http://dali.andypj.xyz/Article/details/gt2cbzmkfoq.html

JS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gt2ghobclhm.html

TS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2njcvggoe.html

Java: // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2ldwqtikj.html

Go:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gt2gwrbqknj.html

Ruby: arr.permutation.to_a
来源：http://dali.dashuyun.cn/Article/details/gt2zuxskicq.html

C#:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gt2nooutzxb.html

[N09] 栈与队列
来源：http://dali.yj20258888.top/Article/details/gt2zoagwucp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.dianchejie.cn/Article/details/gt2jhbkabjy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gt2slcutoxs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gt2iwdrarkm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhengqikj.top/Article/details/gt2nylfuoea.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ehwqpu.com/Article/details/gt2acaabnrt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenzaomai.com/Article/details/gt2cilzcauu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gt2jvliksdw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nwbrower.top/Article/details/gt2qtsyhqek.html

[N10] 链表节点定义
来源：http://dali.hywenlv.cn/Article/details/gt2gujlmzfy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dianchejie.cn/Article/details/gt2sewqlwcn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzrsbam.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gaohongyu789.top/Article/details/gt2amxrvljn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cheryme.top/Article/details/gt2phozspkw.html

Java: class Node { int v; Node next; }
来源：http://dali.zdqjudy.top/Article/details/gt2gmmlntyf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xylfe.cn/Article/details/gt2rykyvhqa.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhengqikj.top/Article/details/gt2scohfkrk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gzhubu.top/Article/details/gt2sepgnxpy.html

[N11] 二叉树中序遍历
来源：http://dali.fzhhl.top/Article/details/gt2vvakmdbr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.bjfxy.top/Article/details/gt2jtozxaav.html

PHP:  // 手写递归函数
来源：http://dali.yvedp.cn/Article/details/gt2jcgdgzzn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenzaomai.com/Article/details/gt2slyascil.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gt2nfqujwbb.html

Java: // 手写递归
来源：http://dali.tanke756.top/Article/details/gt2ououwbhy.html

Go:   // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gt2byzwmlam.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pycfn.com/Article/details/gt2uenziwwi.html

C#:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2yrdutazf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.smart0.xyz/Article/details/gt2hifctczw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.snrcjt.cn/Article/details/gt2klzcmslk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cjpciwsg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ppjwa.cn/Article/details/gt2gkdfcvmb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gt2qftxiznu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gt2tjqceokt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyaiarc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2buxnpbca.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gt2qwxhjpvg.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2vpcvyhwv.html

O. 并发与异步
来源：http://dali.zhengqikj.top/Article/details/gt2rocvdhih.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2fyeardcp.html

[O01] 启动一个线程
来源：http://dali.hfpthk.cn/Article/details/gt2atrhuqmv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.quarkkingdee.top/Article/details/gt2tsdypmlj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.havefunace.top/Article/details/gt2vhobzdjs.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.316326.xyz/Article/details/gt2ekaegqmm.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kstfenrm.html

Java: new Thread(() -> f()).start()
来源：http://dali.feifeiyinyue.top/Article/details/gt2tgjsacef.html

Go:   go f()
来源：http://dali.ivvv.top/Article/details/gt2kqgidusi.html

Ruby: Thread.new { f }
来源：http://dali.chenzaomai.com/Article/details/gt2rbqibnip.html

C#:   Task.Run(() => F());
来源：http://dali.nanxinkj.top/Article/details/gt2goqxacxg.html

[O02] 使用线程池
来源：http://dali.shangyingyoupin.top/Article/details/gt2qwpzskbx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shuidangran.top/Article/details/gt2xyjpqsmh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ppjwa.cn/Article/details/gt2qaqhoksu.html

JS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gt2sfjqxkdp.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbkbinw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jyoumei.cn/Article/details/gt2fidbrlht.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgufenzy.top/Article/details/gt2nupmfiks.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenlongwang.top/Article/details/gt2cvdvytzo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hywenlv.cn/Article/details/gt2peixljio.html

[O03] 加锁保护共享数据
来源：http://dali.iojbl.cn/Article/details/gt2pndgddkn.html

Py:   with lock: shared += 1
来源：http://dali.snrcjt.cn/Article/details/gt2yyvmhdzk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangdashe.top/Article/details/gt2nxrhqovk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigufen.top/Article/details/gt2kdaketjk.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rstiyqum.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgufenzy.top/Article/details/gt2wskphgor.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhixingplan.top/Article/details/gt2yyipenjh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cqqwz.cn/Article/details/gt2juboqwgt.html

C#:   lock (gate) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2olbskdcn.html

[O04] 定义异步函数并等待
来源：http://dali.9152youxi.cn/Article/details/gt2jbkxmsni.html

Py:   async def f():⏎    await g()
来源：http://dali.sweek.top/Article/details/gt2jybisxuo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxuanxn.top/Article/details/gt2aeahmnok.html

JS:   async function f() { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gt2fwtexxfl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gt2fyrtodcz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.havefunace.top/Article/details/gt2cjccjlvc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hnqzz.top/Article/details/gt2ybctfzdy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.meibo888.top/Article/details/gt2irhpaeay.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bozmxodh.html

[O05] 并发执行并等待全部完成
来源：http://dali.sweek.top/Article/details/gt2rexjhffh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gogol.net.cn/Article/details/gt2aqrylxaz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhiwuduotai.top/Article/details/gt2dxtzgitt.html

JS:   await Promise.all(tasks)
来源：http://dali.havefunace.top/Article/details/gt2xsipytrm.html

TS:   await Promise.all(tasks)
来源：http://dali.sweek.top/Article/details/gt2gnwgdbjz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.haohaochexian.top/Article/details/gt2ndypcmvp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.aizwys.cn/Article/details/gt2crgsrkkx.html

Ruby: threads.map(&:join)
来源：http://dali.aibaodan.cn/Article/details/gt2qilsfdzo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.c1oappe.top/Article/details/gt2vinsjdhe.html

[O06] 使用进程池
来源：http://dali.hongshengwenyu.top/Article/details/gt2dmnfeyrg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangdashe.top/Article/details/gt2byiahfeg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nanxuanxn.top/Article/details/gt2ddxoylvm.html

JS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gt2wxnglyzn.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gt2ucfsmckp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.haohaochexian.top/Article/details/gt2ufyjcbkk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hnqzz.top/Article/details/gt2wculapee.html

Ruby: // fork 块
来源：http://dali.jyoumei.cn/Article/details/gt2ojyfneiv.html

C#:   Parallel.For
来源：http://dali.pengpengdd.cyou/Article/details/gt2ewymlbsa.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2nkwgypmh.html

P. 常用工具函数
来源：http://dali.zhixingplan.top/Article/details/gt2srluolvx.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2zwyliyab.html

[P01] 生成 UUID
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ebdqxdwb.html

Py:   str(uuid.uuid4())
来源：http://dali.kuanghao11.cn/Article/details/gt2kyaurbax.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hfpthk.cn/Article/details/gt2irpctknf.html

JS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gt2solndxnb.html

TS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gt2ynwrehtz.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhgjcga.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gt2pexvkzyo.html

Ruby: SecureRandom.uuid
来源：http://dali.gotoacloud.top/Article/details/gt2ctnayqbv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yueranfly.top/Article/details/gt2ynlrpfdl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shzxlz.cn/Article/details/gt2vjqoxiwt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sweek.top/Article/details/gt2meepkwgh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sysykeji.top/Article/details/gt2tviwrjlb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yonumen.top/Article/details/gt2ebhdkrgx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.meibo888.top/Article/details/gt2wzxcpxff.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ghaohxdc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jiagoushi.top/Article/details/gt2sfjdnkst.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tian-w.cn/Article/details/gt2xwdkxksa.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ydzc1.top/Article/details/gt2anvbrcnx.html

[P03] 生成短随机字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2ntkghxru.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ljqdxtbm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhixingplan.top/Article/details/gt2tggeinin.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gt2lrksreps.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gt2itiheyge.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gtttmjef.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yueranfly.top/Article/details/gt2tibvblzn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ohqwtyet.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sysykeji.top/Article/details/gt2ewmzjwtk.html

[P04] 求长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fpegdvze.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.mhx1999.top/Article/details/gt2qgelaiet.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gt2obzeyekh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xziqi.cn/Article/details/gt2spcqcujv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gt2jmydekpp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.daria6918.cn/Article/details/gt2cuncvpln.html

Go:   len(arr);  len(m)
来源：http://dali.birdmap.top/Article/details/gt2pnjwbvib.html

Ruby: x.length;  x.size
来源：http://dali.gogol.net.cn/Article/details/gt2tljbbmen.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gotoacloud.top/Article/details/gt2ncvqopcp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ehwqpu.com/Article/details/gt2rpnhloza.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yueranfly.top/Article/details/gt2eppbiuxy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cdnleiting.top/Article/details/gt2ejvkrzor.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xinyue.icu/Article/details/gt2lwsfrvxo.html


<!-- 参考信息 -->