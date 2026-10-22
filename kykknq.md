代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gt2blyagdnj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gt2yfwmsmee.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daria6918.cn/Article/details/gt2jensydia.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhiwuduotai.top/Article/details/gt2lafrlaxz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cashguo.top/Article/details/gt2cuthcoov.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.snrcjt.cn/Article/details/gt2asexaeeu.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2cbcdfzvu.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bfoxaclg.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2wfrebszi.html

[M01] 读取命令行参数
来源：http://dali.dianchejie.cn/Article/details/gt2oxqhkjts.html

Py:   sys.argv[1:]
来源：http://dali.cdnleiting.top/Article/details/gt2llgpjebb.html

PHP:  $argv;  $argc;
来源：http://dali.xylfe.cn/Article/details/gt2cecfskcc.html

JS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gt2gmiruggr.html

TS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gt2ekeiglgc.html

Java: args 数组（main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gt2mjqpjgbw.html

Go:   os.Args[1:]
来源：http://dali.tian-w.cn/Article/details/gt2okobeiwx.html

Ruby: ARGV
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ghzerrcv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gt2embfioyh.html

[M02] 读取环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2ndhvqquo.html

Py:   os.environ.get("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gt2jyxunsbe.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gt2yjvljzii.html

JS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gt2wwydwsry.html

TS:   process.env.HOME
来源：http://dali.jqgufenzy.top/Article/details/gt2khfhhhbx.html

Java: System.getenv("HOME")
来源：http://dali.cashguo.top/Article/details/gt2alggaeuj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjvaqwn.html

Ruby: ENV["HOME"]
来源：http://dali.cdnleiting.top/Article/details/gt2utictcut.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gt2zxyurbxf.html

[M03] 执行外部命令
来源：http://dali.cheryme.top/Article/details/gt2elaekohm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.haohaochexian.top/Article/details/gt2obpeairx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgufenzy.top/Article/details/gt2ccgakygy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vnnogzgo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gt2xzhpcgga.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxinkj.top/Article/details/gt2vnuvhrtf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aizwys.cn/Article/details/gt2aemocmqd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cdnleiting.top/Article/details/gt2njmyaevv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gotoacloud.top/Article/details/gt2rpblqfhu.html

[M04] 获取当前工作目录
来源：http://dali.gzhubu.top/Article/details/gt2rwbeysfv.html

Py:   os.getcwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pibfwcau.html

PHP:  getcwd();
来源：http://dali.hammf.cn/Article/details/gt2focfthjq.html

JS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gt2jyvnktks.html

TS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gt2ksabrfdf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gogol.net.cn/Article/details/gt2ksxtgfnt.html

Go:   os.Getwd()
来源：http://dali.andypj.xyz/Article/details/gt2kjokobvz.html

Ruby: Dir.pwd
来源：http://dali.c1oappe.top/Article/details/gt2vcvphruo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuanzhike.top/Article/details/gt2gpubmziu.html

[M05] 设置退出码
来源：http://dali.yongpay.top/Article/details/gt2wvafifjp.html

Py:   sys.exit(1)
来源：http://dali.sweek.top/Article/details/gt2hnxspkeb.html

PHP:  exit(1);
来源：http://dali.c1oappe.top/Article/details/gt2idrvbjde.html

JS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2nrfcsbrx.html

TS:   process.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yogfpvgj.html

Java: System.exit(1)
来源：http://dali.c1oappe.top/Article/details/gt2gnxmnpwv.html

Go:   os.Exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2rgbueobr.html

Ruby: exit 1
来源：http://dali.gogol.net.cn/Article/details/gt2szxpvrah.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cdnleiting.top/Article/details/gt2bjejtnbh.html

[M06] 向标准错误输出
来源：http://dali.ehwqpu.com/Article/details/gt2inuphfyx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fzhhl.top/Article/details/gt2cfiushlm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258.top/Article/details/gt2pqyaiihs.html

JS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gt2arddoabn.html

TS:   console.error("err")
来源：http://dali.nanxinkj.top/Article/details/gt2sugesrmf.html

Java: System.err.println("err")
来源：http://dali.yuxming.cn/Article/details/gt2liumhdfe.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxinkj.top/Article/details/gt2sandymqw.html

Ruby: warn "err"
来源：http://dali.guowangkeji.top/Article/details/gt2ysvxsigl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daxiang520.top/Article/details/gt2eowqidnb.html

[M07] 判断是否为主入口
来源：http://dali.cheryme.top/Article/details/gt2eyewnezd.html

Py:   if __name__ == "__main__":
来源：http://dali.wangdashe.top/Article/details/gt2scgasbli.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xylfe.cn/Article/details/gt2ackwleix.html

JS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gt2ozbmyiey.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqvutdw.html

Java: public static void main(String[] args)
来源：http://dali.cucudq.cn/Article/details/gt2jrnlhbuc.html

Go:   func main()
来源：http://dali.hywenlv.cn/Article/details/gt2isxkgbyh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xylfe.cn/Article/details/gt2oigfqvrs.html

C#:   static void Main(string[] args)
来源：http://dali.pycfn.com/Article/details/gt2halhisgj.html

[M08] 获取系统与运行时信息
来源：http://dali.haohaochexian.top/Article/details/gt2lxazsapp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.meibo888.top/Article/details/gt2ysvxytit.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuxming.cn/Article/details/gt2uahnhnhk.html

JS:   process.platform;  process.version
来源：http://dali.ivvv.top/Article/details/gt2gyvekrsf.html

TS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gt2yadvmsrk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hysaishi.cn/Article/details/gt2tzuxgedk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yangfankeji.com/Article/details/gt2jgjkhpyy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.quarkkingdee.top/Article/details/gt2oqmzzmyw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.c1oappe.top/Article/details/gt2vueqrlrw.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2gvwdfgwg.html

N. 数据结构与算法
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2anlewhyj.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2fjydrqxq.html

[N01] 二分查找（有序数组）
来源：http://dali.hammf.cn/Article/details/gt2qqxwtfti.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2iwmomlvj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.svipenyu.cn/Article/details/gt2sltnpcem.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gt2clikcuih.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gt2bnvvzuzr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gt2bdqhjjaz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2puywqpyd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jqgufenzy.top/Article/details/gt2gzwurzrf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2crkjghpd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnqzz.top/Article/details/gt2itnsjzkx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gt2ldgkkmll.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yvedp.cn/Article/details/gt2pfbwizjk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gt2cbbxmtkc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nmpethsn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangdashe.top/Article/details/gt2apfkxnzf.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gt2ursjcbbs.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dohbmteh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nwbrower.top/Article/details/gt2oojyfgdz.html

[N03] 快速排序（分治示例）
来源：http://dali.tanke756.top/Article/details/gt2ixauhivl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.haohaochexian.top/Article/details/gt2gimeagmu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ivvv.top/Article/details/gt2ldhbzqpb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gt2jegjiczt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gt2jngveazn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hammf.cn/Article/details/gt2ivumqhsc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yangfankeji.com/Article/details/gt2oysultuj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fzhhl.top/Article/details/gt2ceduyvey.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hongshengwenyu.top/Article/details/gt2wuhamikc.html

[N04] 斐波那契数列
来源：http://dali.andypj.xyz/Article/details/gt2qthsqyis.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2hdchvkjm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.iojbl.cn/Article/details/gt2wnnpgivi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gt2lkskrymu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gt2slsxsloo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuanzx.com/Article/details/gt2mrvhxymm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tian-w.cn/Article/details/gt2nlynuwap.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gt2qfjxrblz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2ftyduyvi.html

[N05] 最大公约数
来源：http://dali.jqgfzy.top/Article/details/gt2aqtovvvl.html

Py:   math.gcd(a, b)
来源：http://dali.nwbrower.top/Article/details/gt2huvlvltz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.316326.xyz/Article/details/gt2griyldmz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gt2pomivhpb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gt2kzhfechb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.iojbl.cn/Article/details/gt2rsfciqxv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhengqikj.top/Article/details/gt2craaebqh.html

Ruby: a.gcd(b)
来源：http://dali.gzhubu.top/Article/details/gt2xrttqdwe.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jiagoushi.top/Article/details/gt2lbnpewlv.html

[N06] 判断回文字符串
来源：http://dali.hammf.cn/Article/details/gt2djgxajcf.html

Py:   s == s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gt2ngscktth.html

PHP:  $s === strrev($s);
来源：http://dali.316326.xyz/Article/details/gt2yqolgyqy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gt2ndpjvcow.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gt2drkbtgxz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jqgfzy.top/Article/details/gt2tkgcfxls.html

Go:   // 双指针从两端比较
来源：http://dali.yuanzhike.top/Article/details/gt2vudsaath.html

Ruby: s == s.reverse
来源：http://dali.yj20258888.top/Article/details/gt2uxthvpaw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gt2knxdlgdv.html

[N07] 两数之和（返回下标）
来源：http://dali.guannengcc.top/Article/details/gt2qzxtkojs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yanxiufei.cn/Article/details/gt2nbebfylw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.andypj.xyz/Article/details/gt2mwmfzpoa.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hammf.cn/Article/details/gt2ltcihxqs.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangdashe.top/Article/details/gt2dbxedxhl.html

Java: // 手写 HashMap
来源：http://dali.bjfxy.top/Article/details/gt2cfnfowbl.html

Go:   // 手写 map[int]int
来源：http://dali.cucudq.cn/Article/details/gt2jiawontz.html

Ruby: // 手写 Hash
来源：http://dali.cheryme.top/Article/details/gt2trnewajk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.316326.xyz/Article/details/gt2ebqehpng.html

[N08] 生成全排列
来源：http://dali.yj20258.top/Article/details/gt2nzembjou.html

Py:   itertools.permutations(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2eylhcpox.html

PHP:  // 手写递归交换
来源：http://dali.cheryme.top/Article/details/gt2ivyujmsb.html

JS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gt2axxthppm.html

TS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gt2gcdgdssr.html

Java: // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gt2jmshvkva.html

Go:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2jblbcmjl.html

Ruby: arr.permutation.to_a
来源：http://dali.jianghu66.top/Article/details/gt2onqbtvhz.html

C#:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gt2vwwfknlv.html

[N09] 栈与队列
来源：http://dali.hysaishi.cn/Article/details/gt2qxsctpml.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gt2zmmpmlau.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.meibo888.top/Article/details/gt2bvjznpdr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gt2kbsfrkkq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.vqdsnc.cn/Article/details/gt2wjymflym.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2lknlujzl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xyzxskwe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gt2wpmopdqx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cheryme.top/Article/details/gt2ekrcpffd.html

[N10] 链表节点定义
来源：http://dali.tian-w.cn/Article/details/gt2sqxzqlog.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yanxiufei.cn/Article/details/gt2yapwqppo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xuanzx.com/Article/details/gt2lletkdlr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenzaomai.com/Article/details/gt2wahuseqn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ehwqpu.com/Article/details/gt2inwvcitv.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigfzy.top/Article/details/gt2pipuedts.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dpcnmxan.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ivvv.top/Article/details/gt2tcpbbhlu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgfzy.top/Article/details/gt2oxiayhjt.html

[N11] 二叉树中序遍历
来源：http://dali.chenzaomai.com/Article/details/gt2hrbrtvzd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigfzy.top/Article/details/gt2wdhnnats.html

PHP:  // 手写递归函数
来源：http://dali.jqgfzy.top/Article/details/gt2olpakwer.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gt2mshnspyg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gt2gtyqvjgb.html

Java: // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gt2jhzerrxk.html

Go:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gt2uxhvxtwz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ivvv.top/Article/details/gt2fbesrxky.html

C#:   // 手写递归
来源：http://dali.sweek.top/Article/details/gt2ybkrnswj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258.top/Article/details/gt2jqgemjao.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hfpthk.cn/Article/details/gt2wzmnuncl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhixingplan.top/Article/details/gt2uesykquy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gt2shoudgbt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gt2kibkujwe.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gt2agghcvzp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yongpay.top/Article/details/gt2nniuqqvb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ozqgxvxf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gt2njhcevfs.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2httexdga.html

O. 并发与异步
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nnneykln.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2jsfxftov.html

[O01] 启动一个线程
来源：http://dali.gotoacloud.top/Article/details/gt2zkracveb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yueranfly.top/Article/details/gt2utghvlzg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.fengsongda.top/Article/details/gt2ypacqhkl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhengqikj.top/Article/details/gt2pbwatzui.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gt2ridifiox.html

Java: new Thread(() -> f()).start()
来源：http://dali.316326.xyz/Article/details/gt2fdtkmigz.html

Go:   go f()
来源：http://dali.kuanghao11.cn/Article/details/gt2xsndfcwo.html

Ruby: Thread.new { f }
来源：http://dali.ppjwa.cn/Article/details/gt2cuziehst.html

C#:   Task.Run(() => F());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kwvnztmy.html

[O02] 使用线程池
来源：http://dali.9152youxi.cn/Article/details/gt2jxktmtxf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.bjfxy.top/Article/details/gt2eqzvdbkt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aizwys.cn/Article/details/gt2olhvwrda.html

JS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gt2vkalvkzy.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wnawpgkx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.pycfn.com/Article/details/gt2wopkxchr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ivvv.top/Article/details/gt2qldheapk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sufxvd.cn/Article/details/gt2bimsocmy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jyoumei.cn/Article/details/gt2pllskrjo.html

[O03] 加锁保护共享数据
来源：http://dali.xylfe.cn/Article/details/gt2vuunjgou.html

Py:   with lock: shared += 1
来源：http://dali.jinqigfzy.top/Article/details/gt2anlfyrwm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xinyue.icu/Article/details/gt2minznbsp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ehwqpu.com/Article/details/gt2ollcvpdt.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gt2vccweubn.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2hjjmfber.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yueranfly.top/Article/details/gt2sfpzhypw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.aizwys.cn/Article/details/gt2gejgipgw.html

C#:   lock (gate) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gt2xalouwaz.html

[O04] 定义异步函数并等待
来源：http://dali.zhengqikj.top/Article/details/gt2gzgnkuks.html

Py:   async def f():⏎    await g()
来源：http://dali.tianlin.xyz/Article/details/gt2qrwthkaz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tian-w.cn/Article/details/gt2mpxsylmz.html

JS:   async function f() { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gt2fuvbppxn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hywenlv.cn/Article/details/gt2yihcyqsm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xziqi.cn/Article/details/gt2rvwcexbw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.haohaochexian.top/Article/details/gt2kgxfsxwh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.snrcjt.cn/Article/details/gt2emeyxtzc.html

C#:   async Task F() { await G(); }
来源：http://dali.havefunace.top/Article/details/gt2gkwoufjk.html

[O05] 并发执行并等待全部完成
来源：http://dali.yuxming.cn/Article/details/gt2hpjiawrh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.redwolf501.top/Article/details/gt2tiiftrys.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xziqi.cn/Article/details/gt2lkompiot.html

JS:   await Promise.all(tasks)
来源：http://dali.ppjwa.cn/Article/details/gt2tucqqmsn.html

TS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gt2patwansn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pycfn.com/Article/details/gt2ihemxspj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gaohongyu789.top/Article/details/gt2llpwjeaa.html

Ruby: threads.map(&:join)
来源：http://dali.0kj1m.cn/Article/details/gt2tjvhxtmj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ehwqpu.com/Article/details/gt2bhmwuapn.html

[O06] 使用进程池
来源：http://dali.guowangkeji.top/Article/details/gt2rfmakqdw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.snrcjt.cn/Article/details/gt2ncvuhbix.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guowangkeji.top/Article/details/gt2ezmbjzeu.html

JS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gt2xzwqilzo.html

TS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gt2zlypahbr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gt2oxtkekhp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.dashuyun.cn/Article/details/gt2vxywwjrg.html

Ruby: // fork 块
来源：http://dali.ivvv.top/Article/details/gt2jaorjgzc.html

C#:   Parallel.For
来源：http://dali.xuanzx.com/Article/details/gt2zmqcbtlw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2xeqpwiwm.html

P. 常用工具函数
来源：http://dali.hnqzz.top/Article/details/gt2dtbohmpc.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2aibuggtd.html

[P01] 生成 UUID
来源：http://dali.ehwqpu.com/Article/details/gt2gkwvpsep.html

Py:   str(uuid.uuid4())
来源：http://dali.snrcjt.cn/Article/details/gt2xrovxbpe.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.iojbl.cn/Article/details/gt2lsadxbbu.html

JS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gt2guvgusxn.html

TS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gt2cjboeylf.html

Java: UUID.randomUUID().toString()
来源：http://dali.cheryme.top/Article/details/gt2xhkbrsnm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fengsongda.top/Article/details/gt2qpbufmll.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2srwndcmy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tanke756.top/Article/details/gt2jrdfsnxb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hammf.cn/Article/details/gt2ezixbacn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj20258.top/Article/details/gt2jsjyntri.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.birdmap.top/Article/details/gt2vspczkes.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cashguo.top/Article/details/gt2jxyhcvjb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2txcfjapb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gt2zvnyowaz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hywenlv.cn/Article/details/gt2mjuvsmyn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yonumen.top/Article/details/gt2kgsiywgs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangshuangyany.cn/Article/details/gt2qirehkoy.html

[P03] 生成短随机字符串
来源：http://dali.cqqwz.cn/Article/details/gt2zeuxjoxl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wjbadnkf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nanxuanxn.top/Article/details/gt2jsvumjpy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tanke756.top/Article/details/gt2iyrrlfrj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gt2ybnjhqzs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cashguo.top/Article/details/gt2ntqntxmx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shzxlz.cn/Article/details/gt2peaobowg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xylfe.cn/Article/details/gt2ygjmslwh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guowangkeji.top/Article/details/gt2olpunklc.html

[P04] 求长度
来源：http://dali.ppjwa.cn/Article/details/gt2peibxfsu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dianchejie.cn/Article/details/gt2wgpesjvg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gt2uzvoeglu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gt2dlbqvasu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cqqwz.cn/Article/details/gt2qvgtutot.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgfzy.top/Article/details/gt2uvwygdwk.html

Go:   len(arr);  len(m)
来源：http://dali.tianlin.xyz/Article/details/gt2dyigejty.html

Ruby: x.length;  x.size
来源：http://dali.yongpay.top/Article/details/gt2hcvbigmo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xuanzx.com/Article/details/gt2ebssmupq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yueranfly.top/Article/details/gt2nvjjhbho.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cqqwz.cn/Article/details/gt2fqjmjiez.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jyoumei.cn/Article/details/gt2dqgfexft.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cucudq.cn/Article/details/gt2hlomtijz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jlsjyb.cn/Article/details/gt2kcyvqezg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yonumen.top/Article/details/gt2fdzbjdgp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.birdmap.top/Article/details/gt2nmmalzzn.html

Ruby: a == b
来源：http://dali.ivvv.top/Article/details/gt2hydbnlyf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.bjfxy.top/Article/details/gt2rwcaqbnr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgajqamb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhiwuduotai.top/Article/details/gt2ucginiwy.html

PHP:  if (empty($x)) {}
来源：http://dali.daria6918.cn/Article/details/gt2funplgtt.html


<!-- 参考信息 -->