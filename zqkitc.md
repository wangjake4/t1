代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gt2fzsrvywp.html

[L08] 并发请求多个地址
来源：http://dali.jqgufenzy.top/Article/details/gt2pegtgjju.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxinkj.top/Article/details/gt2vmlgloyc.html

PHP:  curl_multi_init() 系列
来源：http://dali.andypj.xyz/Article/details/gt2zdkmddal.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gt2boursdnl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gt2fcolzaff.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xylfe.cn/Article/details/gt2tpaiphlp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2froravxk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ohgjipgs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.havefunace.top/Article/details/gt2dmmkbtap.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2guhaojkk.html

M. 命令行 / 进程 / 环境
来源：http://dali.dianchejie.cn/Article/details/gt2wegsludh.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2ujumqbbj.html

[M01] 读取命令行参数
来源：http://dali.c1oappe.top/Article/details/gt2azotekfl.html

Py:   sys.argv[1:]
来源：http://dali.sxryk.cn/Article/details/gt2nstzuzmi.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kqqcpwel.html

JS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gt2qcvxgmpr.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gt2imjqwpst.html

Java: args 数组（main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gt2sttbrqqt.html

Go:   os.Args[1:]
来源：http://dali.nwbrower.top/Article/details/gt2bezcsyva.html

Ruby: ARGV
来源：http://dali.mhx1999.top/Article/details/gt2qwoggdxl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gt2icdsdifi.html

[M02] 读取环境变量
来源：http://dali.fengsongda.top/Article/details/gt2xkkoluvx.html

Py:   os.environ.get("HOME")
来源：http://dali.zycfv.cn/Article/details/gt2fgblqinb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ivvv.top/Article/details/gt2fergjyjx.html

JS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gt2wdgzdefx.html

TS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gt2ntrdpele.html

Java: System.getenv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2ryzjxhbg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mqkmlfxd.html

Ruby: ENV["HOME"]
来源：http://dali.sweek.top/Article/details/gt2wkeeasrc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenlongwang.top/Article/details/gt2zldpyrsv.html

[M03] 执行外部命令
来源：http://dali.haohaochexian.top/Article/details/gt2nkuvlffz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.snrcjt.cn/Article/details/gt2bmnutyik.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ydzc1.top/Article/details/gt2qfppgyrc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2fhedrooy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gt2ewmzvwrm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangshuangyany.cn/Article/details/gt2qtedfvyi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shangyingyoupin.top/Article/details/gt2guucbsjh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2knimzjpi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jiagoushi.top/Article/details/gt2esatxhof.html

[M04] 获取当前工作目录
来源：http://dali.sweek.top/Article/details/gt2obpyitzo.html

Py:   os.getcwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2hokkzycl.html

PHP:  getcwd();
来源：http://dali.tanke756.top/Article/details/gt2ofxdwcqh.html

JS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gt2buoaqzlh.html

TS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gt2sazmsarj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2olomhjuu.html

Go:   os.Getwd()
来源：http://dali.bjfxy.top/Article/details/gt2zlsxkgpp.html

Ruby: Dir.pwd
来源：http://dali.gaohongyu789.top/Article/details/gt2wjxtuiji.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj20258888.top/Article/details/gt2ubfhuyrt.html

[M05] 设置退出码
来源：http://dali.yj202588.top/Article/details/gt2hztibbbo.html

Py:   sys.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2dzinmoxc.html

PHP:  exit(1);
来源：http://dali.daxiang520.top/Article/details/gt2ojyomxgb.html

JS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2thovmwke.html

TS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gt2oodorvih.html

Java: System.exit(1)
来源：http://dali.ivvv.top/Article/details/gt2wanmueec.html

Go:   os.Exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2htgabkzp.html

Ruby: exit 1
来源：http://dali.zdqjudy.top/Article/details/gt2ciovlfoj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenjidiqi.icu/Article/details/gt2sxmmayrx.html

[M06] 向标准错误输出
来源：http://dali.shangyingyoupin.top/Article/details/gt2viuxjsew.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxuanxn.top/Article/details/gt2mvqcrrcw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.bjfxy.top/Article/details/gt2loskvxyl.html

JS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gt2ksohlpth.html

TS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gt2sffgphwp.html

Java: System.err.println("err")
来源：http://dali.meibo888.top/Article/details/gt2jkbyopbf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj202588.top/Article/details/gt2ioynqqfl.html

Ruby: warn "err"
来源：http://dali.ehwqpu.com/Article/details/gt2intzewoy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hysaishi.cn/Article/details/gt2gkjhvdrt.html

[M07] 判断是否为主入口
来源：http://dali.ehwqpu.com/Article/details/gt2orvqgwcq.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgufenzy.top/Article/details/gt2kqlknnqo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sufxvd.cn/Article/details/gt2nlageeur.html

JS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gt2mixiywpl.html

TS:   require.main === module
来源：http://dali.yonumen.top/Article/details/gt2ncperpjn.html

Java: public static void main(String[] args)
来源：http://dali.redwolf501.top/Article/details/gt2ckkjhson.html

Go:   func main()
来源：http://dali.jyoumei.cn/Article/details/gt2qihmwnfn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenlongwang.top/Article/details/gt2bkuloksb.html

C#:   static void Main(string[] args)
来源：http://dali.xylfe.cn/Article/details/gt2okhedpgo.html

[M08] 获取系统与运行时信息
来源：http://dali.tanke756.top/Article/details/gt2nzdehupm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.smart0.xyz/Article/details/gt2kteayqeu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.snrcjt.cn/Article/details/gt2mwftcdqq.html

JS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gt2hmmldkdm.html

TS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gt2qrpxektw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigufen.top/Article/details/gt2awpbpwmp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yonumen.top/Article/details/gt2qgngklmp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cucudq.cn/Article/details/gt2iiqskeym.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.redwolf501.top/Article/details/gt2glhysrun.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2dnkyiazh.html

N. 数据结构与算法
来源：http://dali.jqgfzy.top/Article/details/gt2xsrlgnvv.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2lichboae.html

[N01] 二分查找（有序数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2seaggjyy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yongpay.top/Article/details/gt2rmkmmhhc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gt2eltxmtco.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gt2sglaatby.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gt2eowdfmti.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2jwcmhnco.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2uesorklt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ivvv.top/Article/details/gt2qwzsislv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bnvmjqai.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yvedp.cn/Article/details/gt2bfacgmvg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gt2knjpnxbp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigfzy.top/Article/details/gt2kcjqseww.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gt2pzyswgyp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ewrdjleu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dianchejie.cn/Article/details/gt2vbuaddnt.html

Go:   slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gt2ewedekpz.html

Ruby: arr.sort
来源：http://dali.yuanzhike.top/Article/details/gt2nclkyaxm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shuidangran.top/Article/details/gt2opnjxaxy.html

[N03] 快速排序（分治示例）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ucbvsqtb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.feifeiyinyue.top/Article/details/gt2jllrylxe.html

PHP:  // 递归实现，或用 usort
来源：http://dali.meibo888.top/Article/details/gt2wduzmsmy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuetiantiany.cn/Article/details/gt2aztiqkml.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gt2ijwqaadh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yueranfly.top/Article/details/gt2pwndoqhy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.iojbl.cn/Article/details/gt2wwbgfdor.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2muvbxtag.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zycfv.cn/Article/details/gt2vmileckv.html

[N04] 斐波那契数列
来源：http://dali.guannengcc.top/Article/details/gt2sfamckxb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hammf.cn/Article/details/gt2zbhgortc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aizwys.cn/Article/details/gt2agikyczc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2kmgksmvr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2wmwvhowq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.iojbl.cn/Article/details/gt2ihegdpyd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ixxzpyrk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gt2gjwmpjfw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cfuhpusx.html

[N05] 最大公约数
来源：http://dali.shzxlz.cn/Article/details/gt2kzhrzyzp.html

Py:   math.gcd(a, b)
来源：http://dali.cqqwz.cn/Article/details/gt2dyjwouxz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.meibo888.top/Article/details/gt2depewztf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.redwolf501.top/Article/details/gt2abvtcllq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gt2msigemgz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hysaishi.cn/Article/details/gt2nhgrrkzy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.316326.xyz/Article/details/gt2sppgqoxz.html

Ruby: a.gcd(b)
来源：http://dali.aizwys.cn/Article/details/gt2huwkgpeu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xziqi.cn/Article/details/gt2lrfbaryt.html

[N06] 判断回文字符串
来源：http://dali.xylfe.cn/Article/details/gt2vfpzxdap.html

Py:   s == s[::-1]
来源：http://dali.wangdashe.top/Article/details/gt2vmkdyvfl.html

PHP:  $s === strrev($s);
来源：http://dali.gzhubu.top/Article/details/gt2oxctagwq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkuzaqh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2gqmzconq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2saxcpnic.html

Go:   // 双指针从两端比较
来源：http://dali.jlsjyb.cn/Article/details/gt2hpibwrja.html

Ruby: s == s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gt2pzearmqn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenjidiqi.icu/Article/details/gt2kkujfmhk.html

[N07] 两数之和（返回下标）
来源：http://dali.snrcjt.cn/Article/details/gt2gjzqymqy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jianghu66.top/Article/details/gt2bypwxoco.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinqigufen.top/Article/details/gt2eounolfh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tanke756.top/Article/details/gt2wlpjhcdm.html

TS:   // 手写 Map<string, number>
来源：http://dali.redwolf501.top/Article/details/gt2nvoppmun.html

Java: // 手写 HashMap
来源：http://dali.yj20258888.top/Article/details/gt2mlhovuaw.html

Go:   // 手写 map[int]int
来源：http://dali.xuanzx.com/Article/details/gt2rksqvdof.html

Ruby: // 手写 Hash
来源：http://dali.jinqigfzy.top/Article/details/gt2cwnojqov.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.feifeiyinyue.top/Article/details/gt2ciqxkluj.html

[N08] 生成全排列
来源：http://dali.pengpengdd.cyou/Article/details/gt2fvxduitu.html

Py:   itertools.permutations(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2tnpnqbcz.html

PHP:  // 手写递归交换
来源：http://dali.meibo888.top/Article/details/gt2blunhcth.html

JS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2xtbhlkfx.html

TS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gt2xugkeijc.html

Java: // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gt2dibpbapt.html

Go:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gt2somlqghv.html

Ruby: arr.permutation.to_a
来源：http://dali.9152youxi.cn/Article/details/gt2uafzlady.html

C#:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2pgshomws.html

[N09] 栈与队列
来源：http://dali.316326.xyz/Article/details/gt2zoqagygd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258.top/Article/details/gt2nzhhdzhl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2wdshnowh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gt2uwgnhprn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jlsjyb.cn/Article/details/gt2vqlvtcow.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yonumen.top/Article/details/gt2epslqgim.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.dashuyun.cn/Article/details/gt2clraspra.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gt2isbfzzmy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yvedp.cn/Article/details/gt2zmqyhtmp.html

[N10] 链表节点定义
来源：http://dali.pycfn.com/Article/details/gt2yzpevrgx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigufen.top/Article/details/gt2tdnpbmeg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.fzhhl.top/Article/details/gt2kpsfnfeu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rsritttr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sufxvd.cn/Article/details/gt2npikrixs.html

Java: class Node { int v; Node next; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2rilwnqbr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jqgufenzy.top/Article/details/gt2ssmehxfb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tianlin.xyz/Article/details/gt2dztpyfjc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.birdmap.top/Article/details/gt2bieuwswi.html

[N11] 二叉树中序遍历
来源：http://dali.hysaishi.cn/Article/details/gt2fueidspq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenlongwang.top/Article/details/gt2eutxqzjv.html

PHP:  // 手写递归函数
来源：http://dali.hnxiangtu.top/Article/details/gt2ggdkizmg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ehwqpu.com/Article/details/gt2xfqzlbgr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hqffluln.html

Java: // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gt2haikazgr.html

Go:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gt2rnmmemgj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jlsjyb.cn/Article/details/gt2mfxoepyw.html

C#:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gt2rgcuyhpl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daria6918.cn/Article/details/gt2duwylutk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zdqjudy.top/Article/details/gt2lqjqnmvw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gaohongyu789.top/Article/details/gt2upzcqlxp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.9152youxi.cn/Article/details/gt2rruqaety.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gt2yqrilvbc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gt2gfefdngb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cheryme.top/Article/details/gt2pdfzxcxl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.9152youxi.cn/Article/details/gt2ypjtpjnh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gt2wcakixej.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2djuzgbtc.html

O. 并发与异步
来源：http://dali.guowangkeji.top/Article/details/gt2ltupawgm.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2icgbhpfd.html

[O01] 启动一个线程
来源：http://dali.yangfankeji.com/Article/details/gt2xijdveeg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.smart0.xyz/Article/details/gt2huulashh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2dszjbbyg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ydzc1.top/Article/details/gt2vmhuapgw.html

TS:   // 同 JS
来源：http://dali.yongpay.top/Article/details/gt2uhwnsdmc.html

Java: new Thread(() -> f()).start()
来源：http://dali.jlsjyb.cn/Article/details/gt2najwjvwr.html

Go:   go f()
来源：http://dali.hongshengwenyu.top/Article/details/gt2iuzntelu.html

Ruby: Thread.new { f }
来源：http://dali.9152youxi.cn/Article/details/gt2wazbnmji.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigufen.top/Article/details/gt2iidfhzcc.html

[O02] 使用线程池
来源：http://dali.xuanzx.com/Article/details/gt2mngxnysl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yonumen.top/Article/details/gt2tscitdzc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.redwolf501.top/Article/details/gt2hnhgibyz.html

JS:   // worker_threads 线程池
来源：http://dali.yvedp.cn/Article/details/gt2jfxjvscd.html

TS:   // worker_threads 线程池
来源：http://dali.hysaishi.cn/Article/details/gt2zmywgfng.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ivvv.top/Article/details/gt2tsejdyhq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhiwuduotai.top/Article/details/gt2owmoecct.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yonumen.top/Article/details/gt2xynxoafu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shuidangran.top/Article/details/gt2xsrilqgs.html

[O03] 加锁保护共享数据
来源：http://dali.xylfe.cn/Article/details/gt2potslkmz.html

Py:   with lock: shared += 1
来源：http://dali.xinyue.icu/Article/details/gt2bgrvxmey.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhoulong.xyz/Article/details/gt2sdccbxda.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.feifeiyinyue.top/Article/details/gt2iztdgfwn.html

TS:   // 同 JS
来源：http://dali.jqgufenzy.top/Article/details/gt2tiihvrxf.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gt2iprdogap.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.svipenyu.cn/Article/details/gt2dnonobhu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhoulong.xyz/Article/details/gt2teggzrfa.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2zcrvdyxb.html

[O04] 定义异步函数并等待
来源：http://dali.hywenlv.cn/Article/details/gt2muvgpqxx.html

Py:   async def f():⏎    await g()
来源：http://dali.c1oappe.top/Article/details/gt2sjdgmdmy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pengpengdd.cyou/Article/details/gt2zaydeluk.html

JS:   async function f() { await g(); }
来源：http://dali.cucudq.cn/Article/details/gt2arzvkyid.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gt2qmqboowo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhongyouzk.top/Article/details/gt2yfrmwnyp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cheryme.top/Article/details/gt2ynddwivu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daxiang520.top/Article/details/gt2vwchcbrh.html

C#:   async Task F() { await G(); }
来源：http://dali.c1oappe.top/Article/details/gt2ourpwkys.html

[O05] 并发执行并等待全部完成
来源：http://dali.gaohongyu789.top/Article/details/gt2elzpnhkb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daria6918.cn/Article/details/gt2ykbkopbu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jiagoushi.top/Article/details/gt2sbgworbf.html

JS:   await Promise.all(tasks)
来源：http://dali.sxryk.cn/Article/details/gt2byplrzfm.html

TS:   await Promise.all(tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qjqhntrr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yonumen.top/Article/details/gt2zwbhkeuk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ymaniemt.html

Ruby: threads.map(&:join)
来源：http://dali.sxryk.cn/Article/details/gt2redmloao.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.dianchejie.cn/Article/details/gt2mjzbitco.html

[O06] 使用进程池
来源：http://dali.jinqigfzy.top/Article/details/gt2cpnihdxb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.smart0.xyz/Article/details/gt2ykqrtvgt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hywenlv.cn/Article/details/gt2bvqozbyl.html

JS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gt2qochdtiy.html

TS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gt2okzdcyyk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuxming.cn/Article/details/gt2cauqhsmd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hnqzz.top/Article/details/gt2yhawdrfx.html

Ruby: // fork 块
来源：http://dali.hnqzz.top/Article/details/gt2bxviyjct.html

C#:   Parallel.For
来源：http://dali.cheryme.top/Article/details/gt2whefpkgu.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2gvbmzrdb.html

P. 常用工具函数
来源：http://dali.cucudq.cn/Article/details/gt2ixolqmvq.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2njznfgxf.html

[P01] 生成 UUID
来源：http://dali.hnqzz.top/Article/details/gt2bbgolibb.html

Py:   str(uuid.uuid4())
来源：http://dali.pycfn.com/Article/details/gt2ghjdbfaj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2czyfceig.html

JS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mjszpjbc.html

TS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gt2zozrxcyy.html

Java: UUID.randomUUID().toString()
来源：http://dali.chenzaomai.com/Article/details/gt2sbfcaiwa.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gaohongyu789.top/Article/details/gt2cvcmqxpr.html

Ruby: SecureRandom.uuid
来源：http://dali.gaohongyu789.top/Article/details/gt2larkplia.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.fengsongda.top/Article/details/gt2aewnirku.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnqzz.top/Article/details/gt2loqpysjs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cdnleiting.top/Article/details/gt2ffzbtxxd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yuanzhike.top/Article/details/gt2zanugoub.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tanke756.top/Article/details/gt2gbnxotqk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shuidangran.top/Article/details/gt2quznbdhe.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gt2oyaunxrc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gmtfszps.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cucudq.cn/Article/details/gt2uxfdhskl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.havefunace.top/Article/details/gt2fyzujetc.html

[P03] 生成短随机字符串
来源：http://dali.aibaodan.cn/Article/details/gt2gbbgsclq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxuanxn.top/Article/details/gt2kmrkmozs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daria6918.cn/Article/details/gt2ynviitsj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gt2pjhqjykt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gt2ptodmpmj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fovgtrvk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258888.top/Article/details/gt2qzyffmhr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gogol.net.cn/Article/details/gt2whtgwijr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigufen.top/Article/details/gt2dwwbcxrh.html

[P04] 求长度
来源：http://dali.feifeiyinyue.top/Article/details/gt2dhyorlfx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ehwqpu.com/Article/details/gt2jztuidua.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gt2mrjhjoki.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shzxlz.cn/Article/details/gt2cbaugkqy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gt2gyelbvud.html

Java: list.size();  map.size();  s.length()
来源：http://dali.bjfxy.top/Article/details/gt2ytseogfa.html

Go:   len(arr);  len(m)
来源：http://dali.kuanghao11.cn/Article/details/gt2daawqbfl.html

Ruby: x.length;  x.size
来源：http://dali.vqdsnc.cn/Article/details/gt2unnhqpxk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.c1oappe.top/Article/details/gt2ihkcaprt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.vqdsnc.cn/Article/details/gt2fxakrpav.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuetiantiany.cn/Article/details/gt2bfjbulms.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ehwqpu.com/Article/details/gt2wasuwgmp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.pengpengdd.cyou/Article/details/gt2lhwanxct.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gt2yxfequni.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yuxming.cn/Article/details/gt2ybbaccda.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.smart0.xyz/Article/details/gt2ktafhtrs.html

Ruby: a == b
来源：http://dali.snrcjt.cn/Article/details/gt2ghnosmnh.html


<!-- 参考信息 -->