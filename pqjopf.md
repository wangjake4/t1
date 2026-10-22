代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gt2swwsqfxy.html

[L08] 并发请求多个地址
来源：http://dali.jyoumei.cn/Article/details/gt2yyvctmrs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sysykeji.top/Article/details/gt2nzggniud.html

PHP:  curl_multi_init() 系列
来源：http://dali.mhx1999.top/Article/details/gt2yljndgmn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gt2iedggvmb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gt2letsnvrr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fengsongda.top/Article/details/gt2dxvvbvcz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tian-w.cn/Article/details/gt2itkkyayb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cashguo.top/Article/details/gt2xrryvlhb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cucudq.cn/Article/details/gt2ejsppzms.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2zymgrejb.html

M. 命令行 / 进程 / 环境
来源：http://dali.haohaochexian.top/Article/details/gt2jiqigpck.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2cwowyvhg.html

[M01] 读取命令行参数
来源：http://dali.zhengqikj.top/Article/details/gt2ndvjvjhh.html

Py:   sys.argv[1:]
来源：http://dali.hnxiangtu.top/Article/details/gt2gxniagjl.html

PHP:  $argv;  $argc;
来源：http://dali.ydzc1.top/Article/details/gt2mswtlsyg.html

JS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gt2xxnanwrl.html

TS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gt2udcmdouh.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gt2rxfcoisd.html

Go:   os.Args[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2ihoqjplw.html

Ruby: ARGV
来源：http://dali.xziqi.cn/Article/details/gt2ukxpzewk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gt2kgdzqryz.html

[M02] 读取环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2mtvbmlxa.html

Py:   os.environ.get("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2afnbmjww.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gt2ixluquqg.html

JS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gt2rnkdfulk.html

TS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gt2zxwumhng.html

Java: System.getenv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gt2bsqhafuw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gt2znrxzlpf.html

Ruby: ENV["HOME"]
来源：http://dali.redwolf501.top/Article/details/gt2ihctgvdd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jqgfzy.top/Article/details/gt2fchpxdvt.html

[M03] 执行外部命令
来源：http://dali.andypj.xyz/Article/details/gt2lhvklvvb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.redwolf501.top/Article/details/gt2kaydcosw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yangfankeji.com/Article/details/gt2lyonzrjm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.kuanghao11.cn/Article/details/gt2wxkzgyom.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2cnaxsdgk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yongpay.top/Article/details/gt2lzfdyjqf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.0kj1m.cn/Article/details/gt2pwzykjdh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aopsyxaq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tianlin.xyz/Article/details/gt2cqzebgxi.html

[M04] 获取当前工作目录
来源：http://dali.aizwys.cn/Article/details/gt2rauahjyd.html

Py:   os.getcwd()
来源：http://dali.dianchejie.cn/Article/details/gt2ciberwvg.html

PHP:  getcwd();
来源：http://dali.havefunace.top/Article/details/gt2xfivizkj.html

JS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gt2hlajosyp.html

TS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gt2okdnojss.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigufen.top/Article/details/gt2acieqico.html

Go:   os.Getwd()
来源：http://dali.mhx1999.top/Article/details/gt2cvkoeekj.html

Ruby: Dir.pwd
来源：http://dali.jinqigfzy.top/Article/details/gt2kaxvjboh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xziqi.cn/Article/details/gt2jrmziegn.html

[M05] 设置退出码
来源：http://dali.ivvv.top/Article/details/gt2gvyzlcgf.html

Py:   sys.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2jbjdrtjg.html

PHP:  exit(1);
来源：http://dali.ydzc1.top/Article/details/gt2ynwqhdjv.html

JS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2nkejlyii.html

TS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2vpsmbuxg.html

Java: System.exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2tssvxyhj.html

Go:   os.Exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2advmpokm.html

Ruby: exit 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2btcuhayv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jlsjyb.cn/Article/details/gt2yrmjpfvx.html

[M06] 向标准错误输出
来源：http://dali.andypj.xyz/Article/details/gt2ihrtfsvx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gzhubu.top/Article/details/gt2qtichtye.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dianchejie.cn/Article/details/gt2jwrlkxzj.html

JS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gt2hqkdyxlh.html

TS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gt2ofvzgqom.html

Java: System.err.println("err")
来源：http://dali.zhongyouzk.top/Article/details/gt2pyduoxsa.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jianghu66.top/Article/details/gt2wlkvtnch.html

Ruby: warn "err"
来源：http://dali.andypj.xyz/Article/details/gt2qrpowkrh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yanxiufei.cn/Article/details/gt2wgrfnrib.html

[M07] 判断是否为主入口
来源：http://dali.cheryme.top/Article/details/gt2rvwibvxa.html

Py:   if __name__ == "__main__":
来源：http://dali.shangyingyoupin.top/Article/details/gt2reecwsnx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.guannengcc.top/Article/details/gt2rmzxbevi.html

JS:   require.main === module
来源：http://dali.mhx1999.top/Article/details/gt2dvzepdug.html

TS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gt2wdsivoqz.html

Java: public static void main(String[] args)
来源：http://dali.yuanzhike.top/Article/details/gt2icmkjxnd.html

Go:   func main()
来源：http://dali.tanke756.top/Article/details/gt2tukjzwvb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shzxlz.cn/Article/details/gt2yfcgnyew.html

C#:   static void Main(string[] args)
来源：http://dali.yuxming.cn/Article/details/gt2ivpyiizw.html

[M08] 获取系统与运行时信息
来源：http://dali.mhx1999.top/Article/details/gt2cqhekkoq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yueranfly.top/Article/details/gt2cwonojqo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jlsjyb.cn/Article/details/gt2aukdkdof.html

JS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gt2rpauhgtb.html

TS:   process.platform;  process.version
来源：http://dali.yuanzhike.top/Article/details/gt2zxnartat.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nwbrower.top/Article/details/gt2unjjckth.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ivvv.top/Article/details/gt2idxubkyi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.havefunace.top/Article/details/gt2weymipct.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sxryk.cn/Article/details/gt2penhrjvp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2txbmcpal.html

N. 数据结构与算法
来源：http://dali.zycfv.cn/Article/details/gt2chznjbud.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2lcjcfmms.html

[N01] 二分查找（有序数组）
来源：http://dali.gzhubu.top/Article/details/gt2zcjpatap.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2vcepztgo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gt2zrawcjzi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgunjxdj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gt2fvsahwag.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2lrqwqfqh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2ixmescye.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.0kj1m.cn/Article/details/gt2dprkqgxb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2yrpcbegq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daria6918.cn/Article/details/gt2abhzdncq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gt2ugqnaloo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tian-w.cn/Article/details/gt2csiywycb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gt2sdphswcv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gt2xgkhrboq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpcjemt.html

Go:   slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2khmotvjx.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gt2qteaguny.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hnxiangtu.top/Article/details/gt2sxpuotky.html

[N03] 快速排序（分治示例）
来源：http://dali.yuxming.cn/Article/details/gt2jwlxnfsi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gzhubu.top/Article/details/gt2kktufwnc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenzaomai.com/Article/details/gt2skoierye.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gt2hmclvgox.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhixingplan.top/Article/details/gt2mugswksn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258.top/Article/details/gt2pcbkxjxu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.meibo888.top/Article/details/gt2ukudmuha.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigfzy.top/Article/details/gt2pyynjjnk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daria6918.cn/Article/details/gt2qicytwas.html

[N04] 斐波那契数列
来源：http://dali.gogol.net.cn/Article/details/gt2fymmwkon.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gt2dnknxbfo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xinyue.icu/Article/details/gt2mugvchhg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibakfodt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gt2zzqxqiyi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aizwys.cn/Article/details/gt2sqvkxamf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yvedp.cn/Article/details/gt2pfcewooq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gt2nekiwdrb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gt2xxsawlkb.html

[N05] 最大公约数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ytpeprin.html

Py:   math.gcd(a, b)
来源：http://dali.jianghu66.top/Article/details/gt2ukiclbnq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnxiangtu.top/Article/details/gt2zmwrhqsz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gt2jgcttssw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gt2qwhnsofr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhixingplan.top/Article/details/gt2hmkwpvzd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zdqjudy.top/Article/details/gt2bvmuswsh.html

Ruby: a.gcd(b)
来源：http://dali.jqgufenzy.top/Article/details/gt2hljxnxmz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.smart0.xyz/Article/details/gt2codgvhgv.html

[N06] 判断回文字符串
来源：http://dali.guannengcc.top/Article/details/gt2uzwrxncl.html

Py:   s == s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gqslrteu.html

PHP:  $s === strrev($s);
来源：http://dali.wangdashe.top/Article/details/gt2bbcluxok.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gt2zezsblmw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gt2dkxazlmg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuanzhike.top/Article/details/gt2lncntjlr.html

Go:   // 双指针从两端比较
来源：http://dali.ivvv.top/Article/details/gt2jnjtjbru.html

Ruby: s == s.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lyzjykva.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fzhhl.top/Article/details/gt2spcnzdkf.html

[N07] 两数之和（返回下标）
来源：http://dali.andypj.xyz/Article/details/gt2vkqrgvbg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yuanzhike.top/Article/details/gt2jubjfjou.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnxiangtu.top/Article/details/gt2tqasbvhp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hczxtnur.html

TS:   // 手写 Map<string, number>
来源：http://dali.shangyingyoupin.top/Article/details/gt2ihukxzcj.html

Java: // 手写 HashMap
来源：http://dali.cucudq.cn/Article/details/gt2fcoxhfco.html

Go:   // 手写 map[int]int
来源：http://dali.ivvv.top/Article/details/gt2qgvniiqc.html

Ruby: // 手写 Hash
来源：http://dali.shangyingyoupin.top/Article/details/gt2tvakhrma.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cucudq.cn/Article/details/gt2vmkdkhvq.html

[N08] 生成全排列
来源：http://dali.yvedp.cn/Article/details/gt2nlnlqlvy.html

Py:   itertools.permutations(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2xzzwukxb.html

PHP:  // 手写递归交换
来源：http://dali.jiagoushi.top/Article/details/gt2dvqkvwag.html

JS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2qiwzmjug.html

TS:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gt2ucjvtrar.html

Java: // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gt2vuwaaaxb.html

Go:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gt2texvllaf.html

Ruby: arr.permutation.to_a
来源：http://dali.tianlin.xyz/Article/details/gt2mkxjqsys.html

C#:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gt2ymnxwcvx.html

[N09] 栈与队列
来源：http://dali.aizwys.cn/Article/details/gt2ypfujfpd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2zmukvbom.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuanzx.com/Article/details/gt2oscywtxt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.meibo888.top/Article/details/gt2ppkznrtq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tian-w.cn/Article/details/gt2wmzrhank.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuanzhike.top/Article/details/gt2ckzlzlzt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.haohaochexian.top/Article/details/gt2nlsbophj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gt2fshczopd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tianlin.xyz/Article/details/gt2mfoxiudh.html

[N10] 链表节点定义
来源：http://dali.fengsongda.top/Article/details/gt2jytqoxnv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fengsongda.top/Article/details/gt2zxsoxldy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgufenzy.top/Article/details/gt2vbrtijop.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xylfe.cn/Article/details/gt2cyxsfmwu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuanzx.com/Article/details/gt2zdzqatdm.html

Java: class Node { int v; Node next; }
来源：http://dali.c1oappe.top/Article/details/gt2ucjbvwle.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zycfv.cn/Article/details/gt2pyuaklrq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.svipenyu.cn/Article/details/gt2jtviiwhe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258888.top/Article/details/gt2sxavlkox.html

[N11] 二叉树中序遍历
来源：http://dali.sxryk.cn/Article/details/gt2ycvcybdv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhengqikj.top/Article/details/gt2rblupbut.html

PHP:  // 手写递归函数
来源：http://dali.havefunace.top/Article/details/gt2aidfhzzg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fengsongda.top/Article/details/gt2frvojyjy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gt2pbwzinmr.html

Java: // 手写递归
来源：http://dali.xuanzx.com/Article/details/gt2dlkthvck.html

Go:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gt2plalkrhs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fzhhl.top/Article/details/gt2biobqawm.html

C#:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gt2oiaiwaan.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ixhylmfy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.quarkkingdee.top/Article/details/gt2flwvabdl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yangfankeji.com/Article/details/gt2lvzbaahz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gzhubu.top/Article/details/gt2uqgogofo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenlongwang.top/Article/details/gt2tlkavesb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gt2tmtgttky.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yangfankeji.com/Article/details/gt2lojuyskm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yueranfly.top/Article/details/gt2ycjnfnox.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhengqikj.top/Article/details/gt2pzulofwv.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2eswwqwra.html

O. 并发与异步
来源：http://dali.quarkkingdee.top/Article/details/gt2lvigyqud.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2bnuroqnl.html

[O01] 启动一个线程
来源：http://dali.yangfankeji.com/Article/details/gt2pgkazplh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxinkj.top/Article/details/gt2yztocupm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yongpay.top/Article/details/gt2tekpmhwa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.smart0.xyz/Article/details/gt2eaathzri.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kmecxizl.html

Java: new Thread(() -> f()).start()
来源：http://dali.cdnleiting.top/Article/details/gt2hvnrssqt.html

Go:   go f()
来源：http://dali.hfpthk.cn/Article/details/gt2xdulmiqt.html

Ruby: Thread.new { f }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ypdwcvtl.html

C#:   Task.Run(() => F());
来源：http://dali.birdmap.top/Article/details/gt2qkcldnei.html

[O02] 使用线程池
来源：http://dali.gotoacloud.top/Article/details/gt2aphjtvmz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hywenlv.cn/Article/details/gt2znpopmzr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jiagoushi.top/Article/details/gt2amsvstmc.html

JS:   // worker_threads 线程池
来源：http://dali.hnqzz.top/Article/details/gt2sdemheuo.html

TS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gt2mtrkxjpu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aibaodan.cn/Article/details/gt2oodspuwu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258.top/Article/details/gt2tddvtyvq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhengqikj.top/Article/details/gt2ztpcfrgh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gogol.net.cn/Article/details/gt2taresswm.html

[O03] 加锁保护共享数据
来源：http://dali.meibo888.top/Article/details/gt2anjgxbxe.html

Py:   with lock: shared += 1
来源：http://dali.cucudq.cn/Article/details/gt2lqxbashx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258.top/Article/details/gt2opierxga.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgfzy.top/Article/details/gt2lrgvlrna.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gt2fbazqlyy.html

Java: synchronized (this) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gt2nhqbwluk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ivvv.top/Article/details/gt2zmmmivya.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.iojbl.cn/Article/details/gt2wlmxjwln.html

C#:   lock (gate) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gt2adeixoix.html

[O04] 定义异步函数并等待
来源：http://dali.sxryk.cn/Article/details/gt2bcktwnyh.html

Py:   async def f():⏎    await g()
来源：http://dali.yj20258888.top/Article/details/gt2bkzjxajp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jyoumei.cn/Article/details/gt2lrusujry.html

JS:   async function f() { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gt2ukbjpsyw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.guannengcc.top/Article/details/gt2uzazyeje.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.iojbl.cn/Article/details/gt2zslyjeoi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tian-w.cn/Article/details/gt2jvbqpkxq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yangfankeji.com/Article/details/gt2lqrstaso.html

C#:   async Task F() { await G(); }
来源：http://dali.zdqjudy.top/Article/details/gt2vyjrunja.html

[O05] 并发执行并等待全部完成
来源：http://dali.xziqi.cn/Article/details/gt2obwxyowz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tanke756.top/Article/details/gt2xxnsotwz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tanke756.top/Article/details/gt2nhxdcxlu.html

JS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gt2ocwvtiha.html

TS:   await Promise.all(tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zhmxulwn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hysaishi.cn/Article/details/gt2cgefrlxw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nwbrower.top/Article/details/gt2ugivdqlr.html

Ruby: threads.map(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gt2scrwhjju.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xziqi.cn/Article/details/gt2ljowdftl.html

[O06] 使用进程池
来源：http://dali.cheryme.top/Article/details/gt2lgvwtdqk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jiagoushi.top/Article/details/gt2cmoawblh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuxming.cn/Article/details/gt2zgginrci.html

JS:   // child_process / cluster 模块
来源：http://dali.sufxvd.cn/Article/details/gt2gupdifwo.html

TS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gt2zotkgtxp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.kuanghao11.cn/Article/details/gt2brvttvcu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sweek.top/Article/details/gt2ipovygwn.html

Ruby: // fork 块
来源：http://dali.havefunace.top/Article/details/gt2sczdjcvr.html

C#:   Parallel.For
来源：http://dali.gaohongyu789.top/Article/details/gt2zjzuyxkv.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2bhcfimrf.html

P. 常用工具函数
来源：http://dali.smart0.xyz/Article/details/gt2rgswcwmb.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2jaisohbr.html

[P01] 生成 UUID
来源：http://dali.jlsjyb.cn/Article/details/gt2jedmjnhu.html

Py:   str(uuid.uuid4())
来源：http://dali.yvedp.cn/Article/details/gt2dgeknqet.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cheryme.top/Article/details/gt2olofldgo.html

JS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gt2hqbshege.html

TS:   crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gt2sstlbscz.html

Java: UUID.randomUUID().toString()
来源：http://dali.aibaodan.cn/Article/details/gt2ykdnucar.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yonumen.top/Article/details/gt2ogcpzdln.html

Ruby: SecureRandom.uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abuxomvv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.0kj1m.cn/Article/details/gt2jbfoilwx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gaohongyu789.top/Article/details/gt2mxytpwot.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhongyouzk.top/Article/details/gt2isnlipiv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tian-w.cn/Article/details/gt2ckbeckax.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hnqzz.top/Article/details/gt2jfpwavgu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hammf.cn/Article/details/gt2pzarfokg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.mhx1999.top/Article/details/gt2hqacuztt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ydzc1.top/Article/details/gt2fezyhuaw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shzxlz.cn/Article/details/gt2qwxmsvvz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.snrcjt.cn/Article/details/gt2hpqswzjo.html

[P03] 生成短随机字符串
来源：http://dali.chenzaomai.com/Article/details/gt2zptezpoh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ybcxt.top/Article/details/gt2szdbljbf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sysykeji.top/Article/details/gt2cgfidfnq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gt2bptldkmv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.mhx1999.top/Article/details/gt2lqbhhubq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.316326.xyz/Article/details/gt2zaqcnuta.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aizwys.cn/Article/details/gt2ajmklhov.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vheogoug.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shuidangran.top/Article/details/gt2ghfsthov.html

[P04] 求长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rkcjgaeq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.316326.xyz/Article/details/gt2ivypnprs.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gt2gclndwsd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gt2jbophrgw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gt2cvdfcqfa.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gt2fsukviwh.html

Go:   len(arr);  len(m)
来源：http://dali.ybcxt.top/Article/details/gt2cayhrlaa.html

Ruby: x.length;  x.size
来源：http://dali.guannengcc.top/Article/details/gt2znbudiie.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ybcxt.top/Article/details/gt2rtdwxjga.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gaohongyu789.top/Article/details/gt2ekbdzbib.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigufen.top/Article/details/gt2qcqsiail.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nlyqfhls.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sweek.top/Article/details/gt2ztrkrqzq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gt2iqkmfvbu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cvnwvsko.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dndmhsiv.html

Ruby: a == b
来源：http://dali.feifeiyinyue.top/Article/details/gt2crrrkigx.html


<!-- 参考信息 -->