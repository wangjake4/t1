代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gtxbzsjixs.html

[L08] 并发请求多个地址
来源：http://dali.gzhubu.top/Article/details/gtmsiowgcb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiytopmwz.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxinkj.top/Article/details/gtdzjxrvzt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gtnuztmtci.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gtubhtomcv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.feifeiyinyue.top/Article/details/gtztqjbgit.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.c1oappe.top/Article/details/gtuztynlad.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenlongwang.top/Article/details/gtectpbrch.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ydzc1.top/Article/details/gtpnacolzs.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gthyjmmhka.html

M. 命令行 / 进程 / 环境
来源：http://dali.ehwqpu.com/Article/details/gtfmyuiqfn.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtgzurvtdk.html

[M01] 读取命令行参数
来源：http://dali.cqqwz.cn/Article/details/gtnuvlmpjk.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gtqhhumsuq.html

PHP:  $argv;  $argc;
来源：http://dali.c1oappe.top/Article/details/gtsepuxqno.html

JS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gtgjjmqequ.html

TS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gtlyljuczk.html

Java: args 数组（main 方法参数）
来源：http://dali.xuanzx.com/Article/details/gtwiczqvqc.html

Go:   os.Args[1:]
来源：http://dali.hysaishi.cn/Article/details/gtaptbqwyq.html

Ruby: ARGV
来源：http://dali.gogol.net.cn/Article/details/gtaiuogrxa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gtkvwykjhj.html

[M02] 读取环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gtudulzqcb.html

Py:   os.environ.get("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtgozbakuc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gtsfdtodpx.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtmgfknrge.html

TS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gtmcikhsux.html

Java: System.getenv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtnvcvnsar.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtuixjhywe.html

Ruby: ENV["HOME"]
来源：http://dali.bjfxy.top/Article/details/gtowwudtfy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258888.top/Article/details/gtcgkdspbs.html

[M03] 执行外部命令
来源：http://dali.daria6918.cn/Article/details/gtpueybjqx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.316326.xyz/Article/details/gttjnwfpkr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.iojbl.cn/Article/details/gtnukaqcez.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gtgjremakg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gtfxfgnukf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258.top/Article/details/gttighwlhj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tian-w.cn/Article/details/gtrxymkrdo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnqzz.top/Article/details/gtzgyezppg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.feifeiyinyue.top/Article/details/gtqwectlsa.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gtqwzjxalr.html

Py:   os.getcwd()
来源：http://dali.iojbl.cn/Article/details/gtiksmbhcy.html

PHP:  getcwd();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcoscsly.html

JS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gtcgeqbifd.html

TS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gtmgdcwbsg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.iojbl.cn/Article/details/gtosktduub.html

Go:   os.Getwd()
来源：http://dali.daria6918.cn/Article/details/gtytytbehx.html

Ruby: Dir.pwd
来源：http://dali.mhx1999.top/Article/details/gtpsiwfjsd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dianchejie.cn/Article/details/gthkxeywkk.html

[M05] 设置退出码
来源：http://dali.jinghuilouyu.cn/Article/details/gtldlgosvl.html

Py:   sys.exit(1)
来源：http://dali.cucudq.cn/Article/details/gttxdhkact.html

PHP:  exit(1);
来源：http://dali.svipenyu.cn/Article/details/gtqhbblpeq.html

JS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoyufaslr.html

TS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtfdrifxsu.html

Java: System.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtwsizycrg.html

Go:   os.Exit(1)
来源：http://dali.hfpthk.cn/Article/details/gthuhrjckd.html

Ruby: exit 1
来源：http://dali.kuanghao11.cn/Article/details/gtkiasrlre.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.quarkkingdee.top/Article/details/gtofbkiqtq.html

[M06] 向标准错误输出
来源：http://dali.jlsjyb.cn/Article/details/gtkwqdfgyq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.andypj.xyz/Article/details/gtdbyjigrm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hywenlv.cn/Article/details/gtaazsbqrx.html

JS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gtkmtbxyts.html

TS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gtcbjtwhdn.html

Java: System.err.println("err")
来源：http://dali.zhongyouzk.top/Article/details/gtvtedczda.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ydzc1.top/Article/details/gtmuennuwy.html

Ruby: warn "err"
来源：http://dali.sweek.top/Article/details/gtydvuaqsu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sxryk.cn/Article/details/gtwjlnvusi.html

[M07] 判断是否为主入口
来源：http://dali.hnqzz.top/Article/details/gtiuhhqsiv.html

Py:   if __name__ == "__main__":
来源：http://dali.cashguo.top/Article/details/gthrgfgbhi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xinyue.icu/Article/details/gtuimlwiih.html

JS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gtltmfgxbr.html

TS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gtynmnncmf.html

Java: public static void main(String[] args)
来源：http://dali.shzxlz.cn/Article/details/gtqdrqclrk.html

Go:   func main()
来源：http://dali.vqdsnc.cn/Article/details/gtwbrmmoyo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhoulong.xyz/Article/details/gtwghwglsq.html

C#:   static void Main(string[] args)
来源：http://dali.gogol.net.cn/Article/details/gtdqoumdiu.html

[M08] 获取系统与运行时信息
来源：http://dali.jinqigfzy.top/Article/details/gtcajwwjbt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.meibo888.top/Article/details/gtulajzwpi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ybcxt.top/Article/details/gtdowfamhq.html

JS:   process.platform;  process.version
来源：http://dali.feifeiyinyue.top/Article/details/gtavdytarv.html

TS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gtysxilfws.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jiagoushi.top/Article/details/gtveoiykrc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yanxiufei.cn/Article/details/gtmitpuyrq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.aizwys.cn/Article/details/gtyceqvxmy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangdashe.top/Article/details/gtxopepbyx.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtojwrwhmq.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gtzpfrzczx.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtlkdwlnin.html

[N01] 二分查找（有序数组）
来源：http://dali.havefunace.top/Article/details/gtulszcgra.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtxyejsmhe.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.316326.xyz/Article/details/gtvjoxyjgz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gtpjuvzyjw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gtmdaqjazl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtvuucxlfj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtshwbderg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shzxlz.cn/Article/details/gtsmmjsvyj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxfbcquw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.0kj1m.cn/Article/details/gtsownjwel.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gotoacloud.top/Article/details/gtfivltosr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuanzx.com/Article/details/gtkyiezedm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gtbkiatctf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gtvgcbqzys.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sweek.top/Article/details/gtsciwdwsp.html

Go:   slices.Sort(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrqgndfw.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gtqujwtdns.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj202588.top/Article/details/gtuihpepan.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxinkj.top/Article/details/gttputwecp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgfzy.top/Article/details/gtbeatesfp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258888.top/Article/details/gtahjcqvba.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gtaurtneuw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gtapwmajfr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgfzy.top/Article/details/gtfezzkpvg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.pengpengdd.cyou/Article/details/gttowenulv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.redwolf501.top/Article/details/gtpphmapjk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zdqjudy.top/Article/details/gttmdsuqzs.html

[N04] 斐波那契数列
来源：http://dali.sufxvd.cn/Article/details/gtdtfoskky.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gtnwxavktd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hywenlv.cn/Article/details/gtwdrvlmem.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gttiwhmkoq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gtlfhpsjqb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gtnnkygsnn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guowangkeji.top/Article/details/gtwsiybelu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gtpkwjhdmm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gttsycrpwj.html

[N05] 最大公约数
来源：http://dali.xinyue.icu/Article/details/gtnurtqbot.html

Py:   math.gcd(a, b)
来源：http://dali.hnqzz.top/Article/details/gtuwktcsrj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cdnleiting.top/Article/details/gtssxynpax.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cashguo.top/Article/details/gthrxmlhzw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvxjpvxva.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fzhhl.top/Article/details/gtdtnpdhty.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hywenlv.cn/Article/details/gtdghmvsac.html

Ruby: a.gcd(b)
来源：http://dali.zdqjudy.top/Article/details/gtizbxudys.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hywenlv.cn/Article/details/gtlthtyxoe.html

[N06] 判断回文字符串
来源：http://dali.smart0.xyz/Article/details/gtbatyuufy.html

Py:   s == s[::-1]
来源：http://dali.meibo888.top/Article/details/gtzfkuvqsw.html

PHP:  $s === strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtvnzglzto.html

JS:   s === [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtpsicptjs.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtzlnckhtb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sysykeji.top/Article/details/gtsypeexde.html

Go:   // 双指针从两端比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjntynouh.html

Ruby: s == s.reverse
来源：http://dali.sweek.top/Article/details/gtpgxiozpw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gtnofhjqqa.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258888.top/Article/details/gtfbuksdnq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cqqwz.cn/Article/details/gtpxmrexpi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shangyingyoupin.top/Article/details/gtvdunlqqc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangdashe.top/Article/details/gtnbhcqeiw.html

TS:   // 手写 Map<string, number>
来源：http://dali.pycfn.com/Article/details/gtobdxhebj.html

Java: // 手写 HashMap
来源：http://dali.xuanzx.com/Article/details/gtdgomqbsj.html

Go:   // 手写 map[int]int
来源：http://dali.bjfxy.top/Article/details/gtsutzwcvt.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gtlqkmwqal.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.quarkkingdee.top/Article/details/gtjjapdeqt.html

[N08] 生成全排列
来源：http://dali.ivvv.top/Article/details/gtstemnzvq.html

Py:   itertools.permutations(arr)
来源：http://dali.yj202588.top/Article/details/gtfagekjip.html

PHP:  // 手写递归交换
来源：http://dali.jlsjyb.cn/Article/details/gtrfxquwsq.html

JS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtxggkrijz.html

TS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtotnfjsfv.html

Java: // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttyyawhv.html

Go:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzyrywxnw.html

Ruby: arr.permutation.to_a
来源：http://dali.zhiwuduotai.top/Article/details/gtxbwmcdcq.html

C#:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gthmjpzhxs.html

[N09] 栈与队列
来源：http://dali.wangdashe.top/Article/details/gtjuldbspc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gtisdfntsq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tian-w.cn/Article/details/gtgkeyfblx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gtzetxkkcr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuetiantiany.cn/Article/details/gtdfjndfzv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.0kj1m.cn/Article/details/gtkjxrpyzb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.quarkkingdee.top/Article/details/gtyhzinafx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtacretdba.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xziqi.cn/Article/details/gtyosteuwl.html

[N10] 链表节点定义
来源：http://dali.nanxuanxn.top/Article/details/gtxswwdgrk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cqqwz.cn/Article/details/gtdwqbgfda.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuxming.cn/Article/details/gtnesgbojp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybginmau.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cheryme.top/Article/details/gtfckgdcib.html

Java: class Node { int v; Node next; }
来源：http://dali.sweek.top/Article/details/gtilzzlnsu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pycfn.com/Article/details/gtfzbnsgat.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhixingplan.top/Article/details/gthfbeewgl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuxming.cn/Article/details/gtgezinfht.html

[N11] 二叉树中序遍历
来源：http://dali.havefunace.top/Article/details/gtyjmxydsq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtscgipuwz.html

PHP:  // 手写递归函数
来源：http://dali.cashguo.top/Article/details/gtyuvsxdeb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gtxdvulxse.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shzxlz.cn/Article/details/gtvlssvfel.html

Java: // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gtrtyzlinr.html

Go:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gttlzsspmt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nwbrower.top/Article/details/gtaiyvowji.html

C#:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gtsazbonak.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hywenlv.cn/Article/details/gtmzzrugeb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhoulong.xyz/Article/details/gtpazkvjqn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.iojbl.cn/Article/details/gtypptsvht.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangtech.top/Article/details/gteeiumouw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gtrlwkcant.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.birdmap.top/Article/details/gtxojynrul.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.feifeiyinyue.top/Article/details/gtngzylpnw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.haohaochexian.top/Article/details/gtkwyanmbb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258.top/Article/details/gtoizifpdo.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtodbsaqum.html

O. 并发与异步
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvepquizl.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gthxrgpvtt.html

[O01] 启动一个线程
来源：http://dali.ppjwa.cn/Article/details/gtxlnsazde.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yongpay.top/Article/details/gtfupgozgw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.fengsongda.top/Article/details/gtllrwkyyd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jianghu66.top/Article/details/gttunamosl.html

TS:   // 同 JS
来源：http://dali.sxryk.cn/Article/details/gthitbvzla.html

Java: new Thread(() -> f()).start()
来源：http://dali.0kj1m.cn/Article/details/gtufrcmgnj.html

Go:   go f()
来源：http://dali.yuanzhike.top/Article/details/gtuepgnzmw.html

Ruby: Thread.new { f }
来源：http://dali.guannengcc.top/Article/details/gtmqopmjdp.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258.top/Article/details/gtmkgtszqe.html

[O02] 使用线程池
来源：http://dali.yongpay.top/Article/details/gthgnsafry.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.kuanghao11.cn/Article/details/gtuxucnnsb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guowangkeji.top/Article/details/gtqoqtevfw.html

JS:   // worker_threads 线程池
来源：http://dali.yangfankeji.com/Article/details/gtncjyoxgb.html

TS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gtrzmmujox.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxuanxn.top/Article/details/gtsnrblfch.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cqqwz.cn/Article/details/gtimcihomn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hnxiangtu.top/Article/details/gtkxcknhpi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhengqikj.top/Article/details/gtmhdkibuy.html

[O03] 加锁保护共享数据
来源：http://dali.quarkkingdee.top/Article/details/gtgbxoucag.html

Py:   with lock: shared += 1
来源：http://dali.jinqigfzy.top/Article/details/gteihoolcd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpixflmcv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yangfankeji.com/Article/details/gtjqhotawh.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gtgnotprxa.html

Java: synchronized (this) { shared++; }
来源：http://dali.aibaodan.cn/Article/details/gtstainaom.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hfpthk.cn/Article/details/gtqbkwdhrk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xziqi.cn/Article/details/gtxltbftox.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlsaczbr.html

[O04] 定义异步函数并等待
来源：http://dali.snrcjt.cn/Article/details/gtoyuqjvsy.html

Py:   async def f():⏎    await g()
来源：http://dali.ehwqpu.com/Article/details/gtmycatlgm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xziqi.cn/Article/details/gtawpkodvv.html

JS:   async function f() { await g(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbvobyhg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sysykeji.top/Article/details/gtbymbdwtb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.smart0.xyz/Article/details/gtdowetmbw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.meibo888.top/Article/details/gtgqnseqyg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgufenzy.top/Article/details/gtgtahfsif.html

C#:   async Task F() { await G(); }
来源：http://dali.jyoumei.cn/Article/details/gtstsjxvwx.html

[O05] 并发执行并等待全部完成
来源：http://dali.nwbrower.top/Article/details/gtereqxvyx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gzhubu.top/Article/details/gtnjiqvuur.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gaohongyu789.top/Article/details/gtufttrtcq.html

JS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gtbgznyphp.html

TS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gtgwroxzgd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.haohaochexian.top/Article/details/gthrdgrijs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ivvv.top/Article/details/gtzkbdogti.html

Ruby: threads.map(&:join)
来源：http://dali.hfpthk.cn/Article/details/gtdwfuaejl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cheryme.top/Article/details/gtukwkvnvr.html

[O06] 使用进程池
来源：http://dali.feifeiyinyue.top/Article/details/gtucrblcer.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gaohongyu789.top/Article/details/gttxgrqnvn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hysaishi.cn/Article/details/gteyytgpbt.html

JS:   // child_process / cluster 模块
来源：http://dali.meibo888.top/Article/details/gtwspaeubq.html

TS:   // child_process / cluster 模块
来源：http://dali.sufxvd.cn/Article/details/gtthmifkeh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tian-w.cn/Article/details/gtjnqbxqge.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xuanzx.com/Article/details/gtnelupprh.html

Ruby: // fork 块
来源：http://dali.hywenlv.cn/Article/details/gtebfsosjy.html

C#:   Parallel.For
来源：http://dali.yongpay.top/Article/details/gtkzikpzho.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtbcoqvggh.html

P. 常用工具函数
来源：http://dali.xziqi.cn/Article/details/gtrrdljwvc.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtxlyjrkny.html

[P01] 生成 UUID
来源：http://dali.nanxuanxn.top/Article/details/gtdpknhxzg.html

Py:   str(uuid.uuid4())
来源：http://dali.cdnleiting.top/Article/details/gthlnywlzp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sysykeji.top/Article/details/gtmcqmxssa.html

JS:   crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gtpkzgovhv.html

TS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimexsaoe.html

Java: UUID.randomUUID().toString()
来源：http://dali.andypj.xyz/Article/details/gtxnuhyzjr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gotoacloud.top/Article/details/gtjjxtuida.html

Ruby: SecureRandom.uuid
来源：http://dali.guowangkeji.top/Article/details/gtrfdldaxg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jianghu66.top/Article/details/gtzybyelyh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.redwolf501.top/Article/details/gtmrtheixi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gotoacloud.top/Article/details/gtniemoqgm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinqigfzy.top/Article/details/gtpoctbhwg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ybcxt.top/Article/details/gtalmepprr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tanke756.top/Article/details/gtqxevojhe.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gttunuihwb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgfzy.top/Article/details/gtopftwtyb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.andypj.xyz/Article/details/gtvuecrqdi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zycfv.cn/Article/details/gtdleyxkfu.html

[P03] 生成短随机字符串
来源：http://dali.yj20258.top/Article/details/gtkkagsaii.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxinkj.top/Article/details/gtvkhysgrj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jlsjyb.cn/Article/details/gtlbkeaptx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gtsvcsszar.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuanzhike.top/Article/details/gtlrudozqu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sweek.top/Article/details/gttxgskzwp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.c1oappe.top/Article/details/gtzeqjnmqu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzgakezd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhiwuduotai.top/Article/details/gtvcuhktyl.html

[P04] 求长度
来源：http://dali.vqdsnc.cn/Article/details/gtdeewnewq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangdashe.top/Article/details/gtaqounqhg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtjhdduark.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gotoacloud.top/Article/details/gtlgljnltn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gtfdenjdmk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnxiangtu.top/Article/details/gtqppbbokr.html

Go:   len(arr);  len(m)
来源：http://dali.gogol.net.cn/Article/details/gtbvddtvyn.html

Ruby: x.length;  x.size
来源：http://dali.smart0.xyz/Article/details/gtotkbwltj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnqzz.top/Article/details/gtivpcoakq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.pengpengdd.cyou/Article/details/gtobypcttw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tianlin.xyz/Article/details/gticeskdfd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenlongwang.top/Article/details/gtxvefhrge.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hnxiangtu.top/Article/details/gtoidadkwp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgfzy.top/Article/details/gtmflkhzpf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.9152youxi.cn/Article/details/gtxpblpgox.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gtxrcnamoh.html

Ruby: a == b
来源：http://dali.sysykeji.top/Article/details/gtiikjzekk.html


<!-- 参考信息 -->