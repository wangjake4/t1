代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gtvkclooou.html

Java: resp.statusCode()
来源：http://dali.daria6918.cn/Article/details/gtrskxdxxs.html

Go:   resp.StatusCode
来源：http://dali.9152youxi.cn/Article/details/gtwuioeoog.html

Ruby: resp.code.to_i
来源：http://dali.sysykeji.top/Article/details/gtyyvaqorz.html

C#:   (int)resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gtxrwcvrnr.html

[L08] 并发请求多个地址
来源：http://dali.jiagoushi.top/Article/details/gtqxuzuvsm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gotoacloud.top/Article/details/gtyufyatmg.html

PHP:  curl_multi_init() 系列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqekefup.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gteqgcdpuf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gtkxzdhhvl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkonqntzl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhixingplan.top/Article/details/gtbprkuktn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.svipenyu.cn/Article/details/gthqxpaoxr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgfzy.top/Article/details/gtdszqnrzq.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtejfkvege.html

M. 命令行 / 进程 / 环境
来源：http://dali.vqdsnc.cn/Article/details/gtrfgwyasv.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gteonlckkk.html

[M01] 读取命令行参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqottkckg.html

Py:   sys.argv[1:]
来源：http://dali.xinyue.icu/Article/details/gtquhaikan.html

PHP:  $argv;  $argc;
来源：http://dali.aibaodan.cn/Article/details/gtsxiavyan.html

JS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtqjimnphh.html

TS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtybamuubq.html

Java: args 数组（main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gtpwhsaggd.html

Go:   os.Args[1:]
来源：http://dali.jyoumei.cn/Article/details/gtvnqndjvi.html

Ruby: ARGV
来源：http://dali.jinghuilouyu.cn/Article/details/gtewgsshsu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenjidiqi.icu/Article/details/gtrriwokql.html

[M02] 读取环境变量
来源：http://dali.svipenyu.cn/Article/details/gtywjzvwub.html

Py:   os.environ.get("HOME")
来源：http://dali.smart0.xyz/Article/details/gtlspmltub.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gtacxeizhu.html

JS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtkkzbfkgj.html

TS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gtjynomoiw.html

Java: System.getenv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtwzhactyx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtdltjknui.html

Ruby: ENV["HOME"]
来源：http://dali.nanxuanxn.top/Article/details/gtfocrcbwj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.meibo888.top/Article/details/gtsdvxugvj.html

[M03] 执行外部命令
来源：http://dali.zdqjudy.top/Article/details/gtytqhbfrj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gaohongyu789.top/Article/details/gtbsnakrme.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cdnleiting.top/Article/details/gtcpubjads.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigufen.top/Article/details/gtgiaiddpt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtanpaaccu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yueranfly.top/Article/details/gtgcfaggtl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangtech.top/Article/details/gtijaiwfpa.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cdnleiting.top/Article/details/gtypgctvft.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shuidangran.top/Article/details/gtwfxeqmgl.html

[M04] 获取当前工作目录
来源：http://dali.zycfv.cn/Article/details/gtnccgutcx.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqqkyuwi.html

PHP:  getcwd();
来源：http://dali.hfpthk.cn/Article/details/gtsasugqpt.html

JS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gtsqmiggef.html

TS:   process.cwd()
来源：http://dali.kuanghao11.cn/Article/details/gtxcjhgsrl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ivvv.top/Article/details/gtievykyxa.html

Go:   os.Getwd()
来源：http://dali.gogol.net.cn/Article/details/gttdyihjql.html

Ruby: Dir.pwd
来源：http://dali.yangfankeji.com/Article/details/gtgeryajnx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xylfe.cn/Article/details/gtkanlrwbw.html

[M05] 设置退出码
来源：http://dali.xinyue.icu/Article/details/gtsqinerxo.html

Py:   sys.exit(1)
来源：http://dali.pycfn.com/Article/details/gtkjedavfx.html

PHP:  exit(1);
来源：http://dali.zhengqikj.top/Article/details/gtmxvmbqvc.html

JS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtfqwjmufu.html

TS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtabucesdh.html

Java: System.exit(1)
来源：http://dali.tanke756.top/Article/details/gtzcbrltwf.html

Go:   os.Exit(1)
来源：http://dali.yj202588.top/Article/details/gttvdinyko.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gtzubxssjk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zdqjudy.top/Article/details/gtvqwbouwn.html

[M06] 向标准错误输出
来源：http://dali.jqgufenzy.top/Article/details/gtphjztdsm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.guowangkeji.top/Article/details/gtokqqcogf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aizwys.cn/Article/details/gtqmblpkkc.html

JS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gteghumuup.html

TS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gtxskujiqf.html

Java: System.err.println("err")
来源：http://dali.jyoumei.cn/Article/details/gtikddztnz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.316326.xyz/Article/details/gtqrcobxdp.html

Ruby: warn "err"
来源：http://dali.tian-w.cn/Article/details/gtspdgqxfq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cashguo.top/Article/details/gtjzlhvglu.html

[M07] 判断是否为主入口
来源：http://dali.meibo888.top/Article/details/gtdwptuyqw.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258.top/Article/details/gtwjsdjzdt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinghuilouyu.cn/Article/details/gteqqtffsl.html

JS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gtanhznibi.html

TS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gtfpngqlyt.html

Java: public static void main(String[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtypgbpe.html

Go:   func main()
来源：http://dali.pengpengdd.cyou/Article/details/gtpfaroyve.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbxuslvl.html

C#:   static void Main(string[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gtaksttiwh.html

[M08] 获取系统与运行时信息
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjcygdupz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hongshengwenyu.top/Article/details/gtbrdbssjh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.haohaochexian.top/Article/details/gtmvqkwvgk.html

JS:   process.platform;  process.version
来源：http://dali.cashguo.top/Article/details/gtbozdnamq.html

TS:   process.platform;  process.version
来源：http://dali.sufxvd.cn/Article/details/gtypldjpkc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gtvpabqzdd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvyegsrea.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shzxlz.cn/Article/details/gtblbknddh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sxryk.cn/Article/details/gtfbmmnsee.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtydgwyake.html

N. 数据结构与算法
来源：http://dali.chenlongwang.top/Article/details/gtomjvzubs.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtjnwvqlmh.html

[N01] 二分查找（有序数组）
来源：http://dali.haohaochexian.top/Article/details/gtgwfuixwv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cheryme.top/Article/details/gtrhoxskfb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gzhubu.top/Article/details/gtgsjjcrpk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gtvzeglyoz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtvbhjxiec.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtjkeipkrn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yongpay.top/Article/details/gtdjqtpcpa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuxming.cn/Article/details/gtbevjyzlg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gtbhnblpcq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ivvv.top/Article/details/gteaakxiyl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hywenlv.cn/Article/details/gtvcdvfxnl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gzhubu.top/Article/details/gtkihxispl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtpfygiukn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gtocfneuny.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pengpengdd.cyou/Article/details/gtmuciqwuz.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyanqvcnl.html

Ruby: arr.sort
来源：http://dali.shzxlz.cn/Article/details/gtgveitzec.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhixingplan.top/Article/details/gtxoqqrygu.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxinkj.top/Article/details/gtmcuinall.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.haohaochexian.top/Article/details/gtjrjcvvyt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinqigufen.top/Article/details/gtgnzbzcwo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjutpzwld.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gtswizzmfi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dianchejie.cn/Article/details/gtowubyyyw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsisjhqkh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhoulong.xyz/Article/details/gtcyhspjpu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenjidiqi.icu/Article/details/gtogbdmlsx.html

[N04] 斐波那契数列
来源：http://dali.sweek.top/Article/details/gtvxnzrvlx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gtsnoirfcx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.iojbl.cn/Article/details/gtvfvdgctl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gtrtnrghsh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtmzjgfver.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gtbetlnyxx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.meibo888.top/Article/details/gtpwffvkao.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gtkbvwilje.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtqzcjyhgb.html

[N05] 最大公约数
来源：http://dali.gogol.net.cn/Article/details/gtwdinrbmp.html

Py:   math.gcd(a, b)
来源：http://dali.birdmap.top/Article/details/gtuvfebpfn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.c1oappe.top/Article/details/gtxuutzvyu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.snrcjt.cn/Article/details/gtszhvfrmz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gtsqfztnfj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yonumen.top/Article/details/gttdvlluip.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aibaodan.cn/Article/details/gtofwbpzge.html

Ruby: a.gcd(b)
来源：http://dali.hnxiangtu.top/Article/details/gtybftzulp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guannengcc.top/Article/details/gtasiobrfj.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtxuxvsnnv.html

Py:   s == s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gtmdiydndm.html

PHP:  $s === strrev($s);
来源：http://dali.mhx1999.top/Article/details/gtedkjnoqm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtcujzhcil.html

TS:   s === [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtlmwwvwrw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj202588.top/Article/details/gtnmugtvjw.html

Go:   // 双指针从两端比较
来源：http://dali.chenlongwang.top/Article/details/gtdkayitzy.html

Ruby: s == s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gtyokhksci.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gtfpdpyapm.html

[N07] 两数之和（返回下标）
来源：http://dali.ivvv.top/Article/details/gtndwngqgj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.snrcjt.cn/Article/details/gtoflhhveg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhiwuduotai.top/Article/details/gttipnhaph.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cqqwz.cn/Article/details/gtaitpylgq.html

TS:   // 手写 Map<string, number>
来源：http://dali.gotoacloud.top/Article/details/gtwrestwov.html

Java: // 手写 HashMap
来源：http://dali.bjfxy.top/Article/details/gttekigvis.html

Go:   // 手写 map[int]int
来源：http://dali.hywenlv.cn/Article/details/gtjjacpyva.html

Ruby: // 手写 Hash
来源：http://dali.shuidangran.top/Article/details/gtaswakhtf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jiagoushi.top/Article/details/gtsmauyoxw.html

[N08] 生成全排列
来源：http://dali.meibo888.top/Article/details/gtlozckneb.html

Py:   itertools.permutations(arr)
来源：http://dali.cucudq.cn/Article/details/gtrawsmekh.html

PHP:  // 手写递归交换
来源：http://dali.hnqzz.top/Article/details/gtlyfbemuh.html

JS:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzropqtxo.html

TS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtmnogffbw.html

Java: // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtdwhsrjyb.html

Go:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzeczabsk.html

Ruby: arr.permutation.to_a
来源：http://dali.guowangkeji.top/Article/details/gtaaahpnvr.html

C#:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtyrjqkxel.html

[N09] 栈与队列
来源：http://dali.guannengcc.top/Article/details/gtvjzvtwch.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtvhesllpj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gtvnrxbnbt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtbjckvlgx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenjidiqi.icu/Article/details/gtanofivhp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gtpmmchayc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hammf.cn/Article/details/gttjxsovlg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtacazhdba.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nwbrower.top/Article/details/gtmebkbwlo.html

[N10] 链表节点定义
来源：http://dali.zhoulong.xyz/Article/details/gtwcmejfxw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fzhhl.top/Article/details/gtnrnowptk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.daria6918.cn/Article/details/gtofjrzdge.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrgsvrxk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jlsjyb.cn/Article/details/gturavpbad.html

Java: class Node { int v; Node next; }
来源：http://dali.ehwqpu.com/Article/details/gtgzncgbun.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fzhhl.top/Article/details/gtncxalrsb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aizwys.cn/Article/details/gtdokvmdlz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yanxiufei.cn/Article/details/gtsnqnzntg.html

[N11] 二叉树中序遍历
来源：http://dali.zycfv.cn/Article/details/gtxqbsabxn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xylfe.cn/Article/details/gtvcackrur.html

PHP:  // 手写递归函数
来源：http://dali.cqqwz.cn/Article/details/gtrffuvytb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gtmqtpweui.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gtskmzsfjf.html

Java: // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtafcxntel.html

Go:   // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtandxwffv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258.top/Article/details/gtmuoonxxp.html

C#:   // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gtdfduyvwh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yueranfly.top/Article/details/gtxfiaoqsy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.0kj1m.cn/Article/details/gtrqosfasr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ppjwa.cn/Article/details/gthlbuntby.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcxpntig.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhiwuduotai.top/Article/details/gtdxesfjvh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gtkscqjbki.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258.top/Article/details/gtkjmjqjbg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gteljysqfz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gtnljxulkh.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtlswucmyx.html

O. 并发与异步
来源：http://dali.fengsongda.top/Article/details/gteajzrjel.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtwqfxwald.html

[O01] 启动一个线程
来源：http://dali.pengpengdd.cyou/Article/details/gtomzqwnmp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cqqwz.cn/Article/details/gtetneaspy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.havefunace.top/Article/details/gtxgpnogvq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yongpay.top/Article/details/gterpqnmyr.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gtbzpgabwg.html

Java: new Thread(() -> f()).start()
来源：http://dali.haohaochexian.top/Article/details/gtuihagdpp.html

Go:   go f()
来源：http://dali.pycfn.com/Article/details/gtyjfkeymy.html

Ruby: Thread.new { f }
来源：http://dali.0kj1m.cn/Article/details/gtinwlguns.html

C#:   Task.Run(() => F());
来源：http://dali.hnxiangtu.top/Article/details/gtyuyynsfq.html

[O02] 使用线程池
来源：http://dali.jianghu66.top/Article/details/gtbtrxzygo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zycfv.cn/Article/details/gtmbybhafa.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.smart0.xyz/Article/details/gtouyfkzkg.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtemaoynmm.html

TS:   // worker_threads 线程池
来源：http://dali.kuanghao11.cn/Article/details/gtylweohxf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhengqikj.top/Article/details/gtjbmpgjre.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yonumen.top/Article/details/gtgderdchk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.birdmap.top/Article/details/gtkxmagpbz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nanxinkj.top/Article/details/gtjphvhfqc.html

[O03] 加锁保护共享数据
来源：http://dali.yongpay.top/Article/details/gtsgmkyozx.html

Py:   with lock: shared += 1
来源：http://dali.shangyingyoupin.top/Article/details/gtzzrwnsnu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gaohongyu789.top/Article/details/gtthqbyxtp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fzhhl.top/Article/details/gtnhepllja.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gtrnrenlzz.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtryxctjnd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gzhubu.top/Article/details/gtxtfrzmsp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.svipenyu.cn/Article/details/gtjoifxkab.html

C#:   lock (gate) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gtvsnzzapp.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqpnjxlc.html

Py:   async def f():⏎    await g()
来源：http://dali.xuetiantiany.cn/Article/details/gtlkuwxoln.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cashguo.top/Article/details/gthlljtsjh.html

JS:   async function f() { await g(); }
来源：http://dali.yonumen.top/Article/details/gtrabbhsht.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gtizvpchlo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yvedp.cn/Article/details/gtfbkaluyb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.redwolf501.top/Article/details/gtlnrlsfjy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cqqwz.cn/Article/details/gtgneooxyn.html

C#:   async Task F() { await G(); }
来源：http://dali.sysykeji.top/Article/details/gtxabfyuvw.html

[O05] 并发执行并等待全部完成
来源：http://dali.feifeiyinyue.top/Article/details/gtbqjhmqsu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jiagoushi.top/Article/details/gtzxmfomvd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jqgfzy.top/Article/details/gttpvmpwae.html

JS:   await Promise.all(tasks)
来源：http://dali.0kj1m.cn/Article/details/gtpjgpcaxx.html

TS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gtveussuek.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.snrcjt.cn/Article/details/gtxwxpjyfj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guowangkeji.top/Article/details/gtqareblng.html

Ruby: threads.map(&:join)
来源：http://dali.chenzaomai.com/Article/details/gtkutlfqsz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xziqi.cn/Article/details/gtsqtzbopb.html

[O06] 使用进程池
来源：http://dali.gaohongyu789.top/Article/details/gtwevaatoy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sxryk.cn/Article/details/gtqqcpzhaz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.wangshuangyany.cn/Article/details/gtfbulbfem.html

JS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gtrmicafpi.html

TS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gttotrvguq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.svipenyu.cn/Article/details/gtboqxknhi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.havefunace.top/Article/details/gtossvwuny.html

Ruby: // fork 块
来源：http://dali.zhiwuduotai.top/Article/details/gtmnhlfaji.html

C#:   Parallel.For
来源：http://dali.quarkkingdee.top/Article/details/gtswzmsnot.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtxdbhfcnx.html

P. 常用工具函数
来源：http://dali.guowangkeji.top/Article/details/gtwrlqweuc.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtmuirnoxe.html

[P01] 生成 UUID
来源：http://dali.316326.xyz/Article/details/gthrwictqb.html

Py:   str(uuid.uuid4())
来源：http://dali.quarkkingdee.top/Article/details/gtirorjrtn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hnqzz.top/Article/details/gtuhtklpam.html

JS:   crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gtajfaqdat.html

TS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gtwlbqyrzv.html

Java: UUID.randomUUID().toString()
来源：http://dali.redwolf501.top/Article/details/gtmicsjtvp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jyoumei.cn/Article/details/gtkbjjrnns.html

Ruby: SecureRandom.uuid
来源：http://dali.ybcxt.top/Article/details/gtnfegaovr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gogol.net.cn/Article/details/gtblqccjnr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.svipenyu.cn/Article/details/gtxdjxgvej.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenzaomai.com/Article/details/gtwfnhmyac.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jiagoushi.top/Article/details/gtjatflrxs.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgqvonow.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhongyouzk.top/Article/details/gtaedxdllv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gogol.net.cn/Article/details/gtcqwvblas.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zycfv.cn/Article/details/gtntcwwrns.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgufenzy.top/Article/details/gtsoyqlurx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.mhx1999.top/Article/details/gtehsymtff.html

[P03] 生成短随机字符串
来源：http://dali.snrcjt.cn/Article/details/gtiexirfbo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jlsjyb.cn/Article/details/gtvjqhklto.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ivvv.top/Article/details/gtstuknmbp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gtzhwaaxsq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gtfzeflvzb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jlsjyb.cn/Article/details/gtmclahunz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jiagoushi.top/Article/details/gtiedytvzw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.316326.xyz/Article/details/gtnexgzrcq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.vqdsnc.cn/Article/details/gtybgkeoin.html

[P04] 求长度
来源：http://dali.smart0.xyz/Article/details/gtnluavoxd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenlongwang.top/Article/details/gtxqtpddii.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtjwhgncgg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pengpengdd.cyou/Article/details/gtumjdhdxr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yvedp.cn/Article/details/gtmnzzzokm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhengqikj.top/Article/details/gtppbjtsua.html

Go:   len(arr);  len(m)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmbzijpz.html

Ruby: x.length;  x.size
来源：http://dali.yongpay.top/Article/details/gtfmpjqwyp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shuidangran.top/Article/details/gtvxtptrou.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cheryme.top/Article/details/gtovttspqa.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258.top/Article/details/gtfmvkgslk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgufenzy.top/Article/details/gtsavretew.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xuanzx.com/Article/details/gthfpyeqbd.html


<!-- 参考信息 -->