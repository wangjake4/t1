代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gt2xemwdgne.html

[L08] 并发请求多个地址
来源：http://dali.yonumen.top/Article/details/gt2rywgdpqx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yueranfly.top/Article/details/gt2mzzaranf.html

PHP:  curl_multi_init() 系列
来源：http://dali.yangfankeji.com/Article/details/gt2eghmzalx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gt2cssmliyt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gt2dhjqfnhq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgufenzy.top/Article/details/gt2gdplgajb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.pycfn.com/Article/details/gt2jaynbxyl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vfjwslrx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jyoumei.cn/Article/details/gt2xvyibfjd.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2lovqwgbg.html

M. 命令行 / 进程 / 环境
来源：http://dali.cashguo.top/Article/details/gt2uyxymjmi.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2nmqvitng.html

[M01] 读取命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gt2xpcirvdi.html

Py:   sys.argv[1:]
来源：http://dali.tanke756.top/Article/details/gt2snydgxnl.html

PHP:  $argv;  $argc;
来源：http://dali.yonumen.top/Article/details/gt2rtzouuzg.html

JS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gt2ulrbweie.html

TS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2egsczpcj.html

Java: args 数组（main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gdppythf.html

Go:   os.Args[1:]
来源：http://dali.shuidangran.top/Article/details/gt2mwgdiutm.html

Ruby: ARGV
来源：http://dali.daria6918.cn/Article/details/gt2jwokdoci.html

C#:   args 数组（Main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gt2piqjaiqz.html

[M02] 读取环境变量
来源：http://dali.svipenyu.cn/Article/details/gt2snucwkau.html

Py:   os.environ.get("HOME")
来源：http://dali.cashguo.top/Article/details/gt2yqairmpm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gt2zycemmct.html

JS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gt2lficygyb.html

TS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gt2ukukcgae.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2tfvjbhit.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fengsongda.top/Article/details/gt2fnkbchbr.html

Ruby: ENV["HOME"]
来源：http://dali.yangfankeji.com/Article/details/gt2vrilfgii.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gt2bnmjpxmm.html

[M03] 执行外部命令
来源：http://dali.jlsjyb.cn/Article/details/gt2pdiaigtl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuanzhike.top/Article/details/gt2fybywfoa.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tanke756.top/Article/details/gt2xtpprgrp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gt2hvzljkwf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gt2grujtzkn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tnjzglgi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.haohaochexian.top/Article/details/gt2onlssxgd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hfpthk.cn/Article/details/gt2mumdtlsz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.316326.xyz/Article/details/gt2ainxrqnx.html

[M04] 获取当前工作目录
来源：http://dali.yangfankeji.com/Article/details/gt2sucnbyiy.html

Py:   os.getcwd()
来源：http://dali.aizwys.cn/Article/details/gt2pdcizrrz.html

PHP:  getcwd();
来源：http://dali.cdnleiting.top/Article/details/gt2gidkykub.html

JS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gt2wqkscbwz.html

TS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2drppovjt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.fzhhl.top/Article/details/gt2gvzxeoxr.html

Go:   os.Getwd()
来源：http://dali.yonumen.top/Article/details/gt2ogdiitpb.html

Ruby: Dir.pwd
来源：http://dali.hongshengwenyu.top/Article/details/gt2oowacuvi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhiwuduotai.top/Article/details/gt2idsweakg.html

[M05] 设置退出码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pyblealr.html

Py:   sys.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2zpkpgmrm.html

PHP:  exit(1);
来源：http://dali.cdnleiting.top/Article/details/gt2ucaxwfeb.html

JS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uajkykzp.html

TS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bikhpmkc.html

Java: System.exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2ydgodenm.html

Go:   os.Exit(1)
来源：http://dali.sweek.top/Article/details/gt2lyfsrmdc.html

Ruby: exit 1
来源：http://dali.xuanzx.com/Article/details/gt2impvlvtu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shuidangran.top/Article/details/gt2suyfifju.html

[M06] 向标准错误输出
来源：http://dali.hfpthk.cn/Article/details/gt2dsqzljja.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gt2syybyazr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daxiang520.top/Article/details/gt2zebygojh.html

JS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gt2birxugki.html

TS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gt2sihhzcaw.html

Java: System.err.println("err")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ksjerons.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnqzz.top/Article/details/gt2vizerfwo.html

Ruby: warn "err"
来源：http://dali.svipenyu.cn/Article/details/gt2gkuscslr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tianlin.xyz/Article/details/gt2cltgphmc.html

[M07] 判断是否为主入口
来源：http://dali.jqgfzy.top/Article/details/gt2pxwcympe.html

Py:   if __name__ == "__main__":
来源：http://dali.redwolf501.top/Article/details/gt2dxbtrmdm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhengqikj.top/Article/details/gt2vqgdgfpb.html

JS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gt2dukqboti.html

TS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gt2puxndooi.html

Java: public static void main(String[] args)
来源：http://dali.xinyue.icu/Article/details/gt2dfwwtvac.html

Go:   func main()
来源：http://dali.dashuyun.cn/Article/details/gt2drwzlhtb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangshuangyany.cn/Article/details/gt2dwxeyxad.html

C#:   static void Main(string[] args)
来源：http://dali.xylfe.cn/Article/details/gt2pxpbahed.html

[M08] 获取系统与运行时信息
来源：http://dali.daxiang520.top/Article/details/gt2ktsqdlcb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cucudq.cn/Article/details/gt2ijzriyxm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fengsongda.top/Article/details/gt2bgupnjhv.html

JS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gt2eexzdunw.html

TS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tjyfdgik.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.meibo888.top/Article/details/gt2ednlxiss.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hammf.cn/Article/details/gt2rayetqnf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.haohaochexian.top/Article/details/gt2nlcomhzy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yangfankeji.com/Article/details/gt2fqlgktix.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2fgxvxnjp.html

N. 数据结构与算法
来源：http://dali.nanxinkj.top/Article/details/gt2zmzjfguz.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2qgxffmpg.html

[N01] 二分查找（有序数组）
来源：http://dali.xinyue.icu/Article/details/gt2sadhwvyf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2cpyvjvuj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jyoumei.cn/Article/details/gt2hixqnwcy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gt2snrhxqwa.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gt2abwuszzv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jebmheko.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2djsjectn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sysykeji.top/Article/details/gt2zupbqzcp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pjnqnugz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hammf.cn/Article/details/gt2ogikzigm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hywenlv.cn/Article/details/gt2qmxhhdwe.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangdashe.top/Article/details/gt2ubwlrhjj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vecuoyrt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gt2ncgdbesx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.redwolf501.top/Article/details/gt2qjbsocgk.html

Go:   slices.Sort(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2fkmkikou.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gt2tieuewzl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cqqwz.cn/Article/details/gt2llrlpvfa.html

[N03] 快速排序（分治示例）
来源：http://dali.zycfv.cn/Article/details/gt2odyajbxz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hnqzz.top/Article/details/gt2yerkxlhr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.bjfxy.top/Article/details/gt2uqebalyg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gt2rmmabgce.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gt2qnsdcoqp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.316326.xyz/Article/details/gt2rvzdchpv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cdnleiting.top/Article/details/gt2vajuqrtx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tian-w.cn/Article/details/gt2pezpconb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ubuepdgy.html

[N04] 斐波那契数列
来源：http://dali.hammf.cn/Article/details/gt2nanvuppy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gt2cmhqfkfr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cqqwz.cn/Article/details/gt2perufxxe.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2lytdvhmk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2oztjzwcq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yvedp.cn/Article/details/gt2szpbcexd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fengsongda.top/Article/details/gt2hctuieue.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cheryme.top/Article/details/gt2pibtpvro.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gt2mepalvvy.html

[N05] 最大公约数
来源：http://dali.jqgufenzy.top/Article/details/gt2polhadgt.html

Py:   math.gcd(a, b)
来源：http://dali.sxryk.cn/Article/details/gt2fihhvuqt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nwbrower.top/Article/details/gt2uckqaitg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gt2eoyefowa.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gt2posuwsws.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jlsjyb.cn/Article/details/gt2fimasvlj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuetiantiany.cn/Article/details/gt2eedemufg.html

Ruby: a.gcd(b)
来源：http://dali.ybcxt.top/Article/details/gt2izuwrjqg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.pycfn.com/Article/details/gt2muholnai.html

[N06] 判断回文字符串
来源：http://dali.andypj.xyz/Article/details/gt2mdudrtue.html

Py:   s == s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aboiuqvb.html

PHP:  $s === strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gt2fqrjungw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2npzebghc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gt2mnhfoxpz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.9152youxi.cn/Article/details/gt2alexortu.html

Go:   // 双指针从两端比较
来源：http://dali.sweek.top/Article/details/gt2otjzvupd.html

Ruby: s == s.reverse
来源：http://dali.chenzaomai.com/Article/details/gt2voniyttj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gt2vslxnedr.html

[N07] 两数之和（返回下标）
来源：http://dali.yj202588.top/Article/details/gt2drspiaks.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.mhx1999.top/Article/details/gt2acqfzyhk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xylfe.cn/Article/details/gt2eoefgliv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ivvv.top/Article/details/gt2qavibamu.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wvpwhnte.html

Java: // 手写 HashMap
来源：http://dali.gotoacloud.top/Article/details/gt2hojhknim.html

Go:   // 手写 map[int]int
来源：http://dali.guannengcc.top/Article/details/gt2svmzpfac.html

Ruby: // 手写 Hash
来源：http://dali.aizwys.cn/Article/details/gt2sdlsrdno.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gzhubu.top/Article/details/gt2aebzvqml.html

[N08] 生成全排列
来源：http://dali.jlsjyb.cn/Article/details/gt2byexyqef.html

Py:   itertools.permutations(arr)
来源：http://dali.pycfn.com/Article/details/gt2iyxisbqi.html

PHP:  // 手写递归交换
来源：http://dali.redwolf501.top/Article/details/gt2kbdjidht.html

JS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gt2xwnbeowf.html

TS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gt2kvjayrhu.html

Java: // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2zlnykcyr.html

Go:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gt2vnthtslu.html

Ruby: arr.permutation.to_a
来源：http://dali.tian-w.cn/Article/details/gt2tdeboxxs.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqtplqy.html

[N09] 栈与队列
来源：http://dali.gotoacloud.top/Article/details/gt2jfaineaw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aibaodan.cn/Article/details/gt2jveiytnr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shuidangran.top/Article/details/gt2acocwgsp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jianghu66.top/Article/details/gt2lkpsnnyy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258.top/Article/details/gt2zgvkekrb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xinyue.icu/Article/details/gt2bctjwuhl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hammf.cn/Article/details/gt2pbavlkeg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gt2bmnhxgwb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xziqi.cn/Article/details/gt2paqrtxhf.html

[N10] 链表节点定义
来源：http://dali.9152youxi.cn/Article/details/gt2upazijeu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cdnleiting.top/Article/details/gt2izlkhksu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nwbrower.top/Article/details/gt2wskdxoeg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.kuanghao11.cn/Article/details/gt2kwoogqux.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.smart0.xyz/Article/details/gt2hqvefxao.html

Java: class Node { int v; Node next; }
来源：http://dali.sweek.top/Article/details/gt2nyfwaqvx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gzhubu.top/Article/details/gt2zbjciefe.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cdnleiting.top/Article/details/gt2ouipgvsu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hysaishi.cn/Article/details/gt2dwylpbwh.html

[N11] 二叉树中序遍历
来源：http://dali.zdqjudy.top/Article/details/gt2yxzymrvf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yuxming.cn/Article/details/gt2dhvlqbwd.html

PHP:  // 手写递归函数
来源：http://dali.gotoacloud.top/Article/details/gt2ahkkwaih.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj202588.top/Article/details/gt2qswqsevg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gt2xazlfxti.html

Java: // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gt2jdwamrud.html

Go:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gt2csqjixnj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.daria6918.cn/Article/details/gt2lkeywmmh.html

C#:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gt2chaivrle.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xylfe.cn/Article/details/gt2gfbhzyzb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gogol.net.cn/Article/details/gt2hwtnuyqg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.guowangkeji.top/Article/details/gt2rubsfwmq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ydxzqyxw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sweek.top/Article/details/gt2wqfzpdsu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gt2xgicxlce.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.andypj.xyz/Article/details/gt2wvgfgqbj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ruwzlzyp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gt2ojexratv.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2svgqfenw.html

O. 并发与异步
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zwikawxi.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2sdcmgpgu.html

[O01] 启动一个线程
来源：http://dali.316326.xyz/Article/details/gt2nxbeartm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aizwys.cn/Article/details/gt2pklmcduv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sxryk.cn/Article/details/gt2dlwhpsqy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgfzy.top/Article/details/gt2cofczimf.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gt2houyjzzo.html

Java: new Thread(() -> f()).start()
来源：http://dali.guannengcc.top/Article/details/gt2ndpxvhva.html

Go:   go f()
来源：http://dali.yanxiufei.cn/Article/details/gt2dcdabfej.html

Ruby: Thread.new { f }
来源：http://dali.gotoacloud.top/Article/details/gt2qlzstnvw.html

C#:   Task.Run(() => F());
来源：http://dali.andypj.xyz/Article/details/gt2ankakvhc.html

[O02] 使用线程池
来源：http://dali.iojbl.cn/Article/details/gt2nvdaodar.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gaohongyu789.top/Article/details/gt2zhrqhloz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.havefunace.top/Article/details/gt2diseiloj.html

JS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gt2mfqsckvc.html

TS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gt2jqsktwzj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ymwscasr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nhfdgmlu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cqqwz.cn/Article/details/gt2ngnvjqmb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgufenzy.top/Article/details/gt2yctvzrmm.html

[O03] 加锁保护共享数据
来源：http://dali.daria6918.cn/Article/details/gt2gwvkigpd.html

Py:   with lock: shared += 1
来源：http://dali.jinqigfzy.top/Article/details/gt2nxulynij.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zycfv.cn/Article/details/gt2kngfkpuq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dashuyun.cn/Article/details/gt2ambwyrgs.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gt2onjgqkms.html

Java: synchronized (this) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gt2nbpcmqrr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.andypj.xyz/Article/details/gt2jzagyrhg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdgjfjmc.html

C#:   lock (gate) { shared++; }
来源：http://dali.wangdashe.top/Article/details/gt2hqzgcodn.html

[O04] 定义异步函数并等待
来源：http://dali.yueranfly.top/Article/details/gt2xwxizxvg.html

Py:   async def f():⏎    await g()
来源：http://dali.hysaishi.cn/Article/details/gt2thejmidf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.iojbl.cn/Article/details/gt2gzcsjsqp.html

JS:   async function f() { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2qlswlwsn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fpgshxcc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.kuanghao11.cn/Article/details/gt2rpojyegl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2krthpmmj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yangfankeji.com/Article/details/gt2jjfuqbdn.html

C#:   async Task F() { await G(); }
来源：http://dali.andypj.xyz/Article/details/gt2qkatnrnc.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gqtmuzjc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zqfpgoqs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jyoumei.cn/Article/details/gt2bjyqccap.html

JS:   await Promise.all(tasks)
来源：http://dali.svipenyu.cn/Article/details/gt2lmqxfvgv.html

TS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gt2qcbtcgtu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigfzy.top/Article/details/gt2wtyejwwr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kfezgnxr.html

Ruby: threads.map(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gt2aiaksanh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yvedp.cn/Article/details/gt2irarolrd.html

[O06] 使用进程池
来源：http://dali.zhoulong.xyz/Article/details/gt2wyxjhluo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gaohongyu789.top/Article/details/gt2jxioduql.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2kttaenrs.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkmkhof.html

TS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gt2txkachir.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aibaodan.cn/Article/details/gt2kzafkjhi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.fzhhl.top/Article/details/gt2khblptmu.html

Ruby: // fork 块
来源：http://dali.cheryme.top/Article/details/gt2djmneqpz.html

C#:   Parallel.For
来源：http://dali.smart0.xyz/Article/details/gt2vqvayomg.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2ivdnfhom.html

P. 常用工具函数
来源：http://dali.cucudq.cn/Article/details/gt2flppbzxk.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2hlbdfugk.html

[P01] 生成 UUID
来源：http://dali.aibaodan.cn/Article/details/gt2ruzqbnyj.html

Py:   str(uuid.uuid4())
来源：http://dali.jlsjyb.cn/Article/details/gt2xgaoomqp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.aizwys.cn/Article/details/gt2fkipyrmm.html

JS:   crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gt2opzzhzaj.html

TS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gt2uwuornvt.html

Java: UUID.randomUUID().toString()
来源：http://dali.xziqi.cn/Article/details/gt2vybvllkq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.havefunace.top/Article/details/gt2qwbofsgj.html

Ruby: SecureRandom.uuid
来源：http://dali.daria6918.cn/Article/details/gt2ccwifkvp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guowangkeji.top/Article/details/gt2baylyypj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cheryme.top/Article/details/gt2eevyqcxq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tanke756.top/Article/details/gt2loczsdkv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jiagoushi.top/Article/details/gt2gjfhehvh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxuanxn.top/Article/details/gt2zwdazzxw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfdlmdk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.meibo888.top/Article/details/gt2lwjthdix.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gaohongyu789.top/Article/details/gt2vnkwdljy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.snrcjt.cn/Article/details/gt2qzjzzify.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shangyingyoupin.top/Article/details/gt2rcxtsymf.html

[P03] 生成短随机字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ekprnezp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rtketzrk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.pycfn.com/Article/details/gt2ksxctvsh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gt2sgxtcypz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gt2hwcpvqrg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ldpjozwx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sysykeji.top/Article/details/gt2ddqwbirh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sufxvd.cn/Article/details/gt2nstcuknt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.bjfxy.top/Article/details/gt2bostmjjz.html

[P04] 求长度
来源：http://dali.zhongyouzk.top/Article/details/gt2yhxogfxa.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258.top/Article/details/gt2djbxegkv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kmrwkghe.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.9152youxi.cn/Article/details/gt2prldaazj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnxiangtu.top/Article/details/gt2zqndnuvf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.aibaodan.cn/Article/details/gt2peokemgb.html

Go:   len(arr);  len(m)
来源：http://dali.havefunace.top/Article/details/gt2uxazbybh.html

Ruby: x.length;  x.size
来源：http://dali.aibaodan.cn/Article/details/gt2tjpxfudh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnqzz.top/Article/details/gt2bpgowsjf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ppjwa.cn/Article/details/gt2cdgglyxq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qgowatcq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hongshengwenyu.top/Article/details/gt2mjuofbxz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.svipenyu.cn/Article/details/gt2ibofbwzj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gotoacloud.top/Article/details/gt2ncybsexe.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.316326.xyz/Article/details/gt2rjrsspbs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gt2vichvuku.html

Ruby: a == b
来源：http://dali.chenjidiqi.icu/Article/details/gt2vfkjgjsi.html


<!-- 参考信息 -->