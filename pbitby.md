代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gtvtxzbzor.html

[L08] 并发请求多个地址
来源：http://dali.daxiang520.top/Article/details/gtlbqmsgwo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.kuanghao11.cn/Article/details/gtuhhduyyx.html

PHP:  curl_multi_init() 系列
来源：http://dali.andypj.xyz/Article/details/gtpzewoeji.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtnlscaihf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtrxnxifcd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.bjfxy.top/Article/details/gtrebyxtgo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.andypj.xyz/Article/details/gtvyzgoepp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ppjwa.cn/Article/details/gtnainyzyf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guowangkeji.top/Article/details/gtqfhqrdcc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtntrsvzqn.html

M. 命令行 / 进程 / 环境
来源：http://dali.9152youxi.cn/Article/details/gtjkznbexz.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtpcjdbyuo.html

[M01] 读取命令行参数
来源：http://dali.wangshuangyany.cn/Article/details/gtiarfmklm.html

Py:   sys.argv[1:]
来源：http://dali.dashuyun.cn/Article/details/gtagbrmkgk.html

PHP:  $argv;  $argc;
来源：http://dali.sufxvd.cn/Article/details/gtzgrvrjug.html

JS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtclwnjkxp.html

TS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gtrvttdnpg.html

Java: args 数组（main 方法参数）
来源：http://dali.xuanzx.com/Article/details/gtfgppkdct.html

Go:   os.Args[1:]
来源：http://dali.daria6918.cn/Article/details/gtlrghpsge.html

Ruby: ARGV
来源：http://dali.zhoulong.xyz/Article/details/gtjknguykc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gtcqsbpkvo.html

[M02] 读取环境变量
来源：http://dali.gzhubu.top/Article/details/gtvjftzfhs.html

Py:   os.environ.get("HOME")
来源：http://dali.birdmap.top/Article/details/gtgejvzmyu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yuxming.cn/Article/details/gtncsabqke.html

JS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gttepypiqw.html

TS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gtsrzzoqcu.html

Java: System.getenv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtrzjseqrd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.meibo888.top/Article/details/gtngzohqbo.html

Ruby: ENV["HOME"]
来源：http://dali.hnxiangtu.top/Article/details/gtqwghsagc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tanke756.top/Article/details/gtndakuwio.html

[M03] 执行外部命令
来源：http://dali.sysykeji.top/Article/details/gtnbrthyiz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cqqwz.cn/Article/details/gtqzsrhfvb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenjidiqi.icu/Article/details/gtduccaqbu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhengqikj.top/Article/details/gtlwblyqtu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gtrzgdkhpr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.iojbl.cn/Article/details/gtajszzxsx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgfzy.top/Article/details/gtfaggkskl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jyoumei.cn/Article/details/gtdqvpbtaf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daxiang520.top/Article/details/gtkwemvtfa.html

[M04] 获取当前工作目录
来源：http://dali.dashuyun.cn/Article/details/gtmfrioerj.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxfdpjja.html

PHP:  getcwd();
来源：http://dali.yongpay.top/Article/details/gtcqslhuny.html

JS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgzoydvi.html

TS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gtjdkksmrd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.fzhhl.top/Article/details/gtektspmct.html

Go:   os.Getwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtumjifqak.html

Ruby: Dir.pwd
来源：http://dali.guannengcc.top/Article/details/gtscbrxiue.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.andypj.xyz/Article/details/gtuywicnsg.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gtmwwxzqul.html

Py:   sys.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphbblwsi.html

PHP:  exit(1);
来源：http://dali.xziqi.cn/Article/details/gtdhnthskn.html

JS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtlzfivopx.html

TS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gtblbkocen.html

Java: System.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtuznyhqqn.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gttijujcqs.html

Ruby: exit 1
来源：http://dali.aibaodan.cn/Article/details/gtytphnbkc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dianchejie.cn/Article/details/gttznheqzu.html

[M06] 向标准错误输出
来源：http://dali.yuanzhike.top/Article/details/gtvfggjxgo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aizwys.cn/Article/details/gtuvoarjxu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guannengcc.top/Article/details/gtdfkkeoqr.html

JS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gtbhnmiecz.html

TS:   console.error("err")
来源：http://dali.hnxiangtu.top/Article/details/gtqndtlqpu.html

Java: System.err.println("err")
来源：http://dali.wangdashe.top/Article/details/gttfcwfaes.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ppjwa.cn/Article/details/gtyoxlsiql.html

Ruby: warn "err"
来源：http://dali.sxryk.cn/Article/details/gtoqnftils.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yanxiufei.cn/Article/details/gtelrvhvdc.html

[M07] 判断是否为主入口
来源：http://dali.316326.xyz/Article/details/gtdhvnykzx.html

Py:   if __name__ == "__main__":
来源：http://dali.zhoulong.xyz/Article/details/gtchpgaenj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shzxlz.cn/Article/details/gtmjdplcqm.html

JS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gtdxtkuskn.html

TS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gtlerxhnif.html

Java: public static void main(String[] args)
来源：http://dali.fzhhl.top/Article/details/gtycswbfyc.html

Go:   func main()
来源：http://dali.hnqzz.top/Article/details/gtoazetugn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhixingplan.top/Article/details/gtdedgbuju.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdptckyy.html

[M08] 获取系统与运行时信息
来源：http://dali.fzhhl.top/Article/details/gtpnyizghc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ehwqpu.com/Article/details/gtxmhkoofy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyovkdqw.html

JS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gtyczpuzho.html

TS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gtsxlfdmcd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.c1oappe.top/Article/details/gtzwhncthh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aizwys.cn/Article/details/gtoaeerhue.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yonumen.top/Article/details/gtbcrfglvc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjwjpyer.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtddeohzsz.html

N. 数据结构与算法
来源：http://dali.jianghu66.top/Article/details/gttxtkfyps.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gteragelte.html

[N01] 二分查找（有序数组）
来源：http://dali.fzhhl.top/Article/details/gtotgoqdoa.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj202588.top/Article/details/gtnduvqjtl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ehwqpu.com/Article/details/gttvdygupa.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsdwaznl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucloxikn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtkfxdvxoe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtxgdwrqug.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenjidiqi.icu/Article/details/gtoyoodtef.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtzxiuljvg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuanzhike.top/Article/details/gttqtwptdv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuanzhike.top/Article/details/gtvwwmenda.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.mhx1999.top/Article/details/gtpygliqfc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gtrcakqqgu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdiwdboz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpykxrebs.html

Go:   slices.Sort(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtvhlaxpfe.html

Ruby: arr.sort
来源：http://dali.hnxiangtu.top/Article/details/gtlsuskpjt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlbeokjt.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxinkj.top/Article/details/gtgburfmkn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guowangkeji.top/Article/details/gthzuykmph.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gtulwnxiji.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gtsaonxdft.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gtvbhpuvwd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nwbrower.top/Article/details/gtujzunjqj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.316326.xyz/Article/details/gttkuvlmmz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.birdmap.top/Article/details/gtnatfshrf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.kuanghao11.cn/Article/details/gtzgudixhs.html

[N04] 斐波那契数列
来源：http://dali.zhoulong.xyz/Article/details/gtubchazko.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.havefunace.top/Article/details/gtcwisaoqn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.andypj.xyz/Article/details/gtpkirfmjl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtsgntacbt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtxnpcsyyf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yuxming.cn/Article/details/gtpqshthdn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jiagoushi.top/Article/details/gtbmetgyno.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gtletlnqzw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtimrqatnu.html

[N05] 最大公约数
来源：http://dali.wangdashe.top/Article/details/gtcpcogiqs.html

Py:   math.gcd(a, b)
来源：http://dali.yvedp.cn/Article/details/gtjbbzfxtv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtymicjtbl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aibaodan.cn/Article/details/gtycmekiih.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gtxzidrcur.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yueranfly.top/Article/details/gtgttzanpm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gzhubu.top/Article/details/gtzpewhdlp.html

Ruby: a.gcd(b)
来源：http://dali.fzhhl.top/Article/details/gthokrnjwy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.mhx1999.top/Article/details/gtmhwonjbs.html

[N06] 判断回文字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtyfshhepn.html

Py:   s == s[::-1]
来源：http://dali.xuanzx.com/Article/details/gtfkjxsaks.html

PHP:  $s === strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gtcjxpegjv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtpnaagzqj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtekbijfuu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnqzz.top/Article/details/gthggbvrjo.html

Go:   // 双指针从两端比较
来源：http://dali.fengsongda.top/Article/details/gthqjbxhpl.html

Ruby: s == s.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujmljiym.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gtgnodilgi.html

[N07] 两数之和（返回下标）
来源：http://dali.nanxinkj.top/Article/details/gthvffbstd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daria6918.cn/Article/details/gtehtigcvf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuetiantiany.cn/Article/details/gtcdtbsgeo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.havefunace.top/Article/details/gtwmqsuiek.html

TS:   // 手写 Map<string, number>
来源：http://dali.shangyingyoupin.top/Article/details/gtgxzcvojk.html

Java: // 手写 HashMap
来源：http://dali.hfpthk.cn/Article/details/gtyogwdedb.html

Go:   // 手写 map[int]int
来源：http://dali.yonumen.top/Article/details/gtudwifsyq.html

Ruby: // 手写 Hash
来源：http://dali.bjfxy.top/Article/details/gtiozpnunx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinqigfzy.top/Article/details/gtgxgvgksl.html

[N08] 生成全排列
来源：http://dali.zycfv.cn/Article/details/gtdxfibqhl.html

Py:   itertools.permutations(arr)
来源：http://dali.redwolf501.top/Article/details/gtwafzzmqx.html

PHP:  // 手写递归交换
来源：http://dali.dashuyun.cn/Article/details/gtnnntlwth.html

JS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gttaioqcvg.html

TS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtupczknxu.html

Java: // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gthksrlpuf.html

Go:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtkgffjvmq.html

Ruby: arr.permutation.to_a
来源：http://dali.pycfn.com/Article/details/gtjtmhnqxb.html

C#:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtuzpjiipu.html

[N09] 栈与队列
来源：http://dali.ydzc1.top/Article/details/gtjkskypxz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daxiang520.top/Article/details/gtxcfbfwgl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yonumen.top/Article/details/gteqenlhwy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gtwkgsyrea.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.quarkkingdee.top/Article/details/gtfcuioick.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shangyingyoupin.top/Article/details/gtuoavbqzh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdbkpepp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtnszoywzj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cheryme.top/Article/details/gtrlwcjquv.html

[N10] 链表节点定义
来源：http://dali.9152youxi.cn/Article/details/gtlwhjibqj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hongshengwenyu.top/Article/details/gtnvtcpzqp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhongyouzk.top/Article/details/gtaoueazba.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhoulong.xyz/Article/details/gtjeoqhndu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nwbrower.top/Article/details/gtenomymoc.html

Java: class Node { int v; Node next; }
来源：http://dali.ivvv.top/Article/details/gtwledrpjx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ybcxt.top/Article/details/gtmsidnguc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj202588.top/Article/details/gtsmqhjbwl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ybcxt.top/Article/details/gttkpqtwny.html

[N11] 二叉树中序遍历
来源：http://dali.yuxming.cn/Article/details/gtzxvtgwzc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sxryk.cn/Article/details/gtynhpzeua.html

PHP:  // 手写递归函数
来源：http://dali.ydzc1.top/Article/details/gttgikvosy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhwdmiyh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gtdbsneoms.html

Java: // 手写递归
来源：http://dali.guannengcc.top/Article/details/gtsqoelqlc.html

Go:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtahonnwfh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhiwuduotai.top/Article/details/gtmvjbejlt.html

C#:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtssujvnep.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.andypj.xyz/Article/details/gteveefsez.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnqzz.top/Article/details/gtrnwlzrdp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.birdmap.top/Article/details/gtjrnhauny.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gtfvciyiib.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gtwwdhjcqn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gtspkytpkm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cdnleiting.top/Article/details/gtisttoqmj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sufxvd.cn/Article/details/gtkrozamdp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gtdrztyiac.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhjbsrqs.html

O. 并发与异步
来源：http://dali.ybcxt.top/Article/details/gteqbwllxp.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpdnqmcq.html

[O01] 启动一个线程
来源：http://dali.fzhhl.top/Article/details/gtfewrmaje.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jianghu66.top/Article/details/gttatdluhq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dianchejie.cn/Article/details/gtmzczjqkk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ybcxt.top/Article/details/gteamqkclh.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gtehtvuxbo.html

Java: new Thread(() -> f()).start()
来源：http://dali.sysykeji.top/Article/details/gttnwwlvjk.html

Go:   go f()
来源：http://dali.yvedp.cn/Article/details/gtyatfereh.html

Ruby: Thread.new { f }
来源：http://dali.snrcjt.cn/Article/details/gtfgqtsjrg.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigfzy.top/Article/details/gttoiierws.html

[O02] 使用线程池
来源：http://dali.shuidangran.top/Article/details/gtxbkizahf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jqgfzy.top/Article/details/gtyhoejieu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hnqzz.top/Article/details/gtcjvyvmpi.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcyfmpfy.html

TS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gttzaptrdf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.9152youxi.cn/Article/details/gtbjdukugk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.316326.xyz/Article/details/gtplhzilhl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yuanzhike.top/Article/details/gtpreoxhjs.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ybcxt.top/Article/details/gtdsauldyf.html

[O03] 加锁保护共享数据
来源：http://dali.meibo888.top/Article/details/gttsfergve.html

Py:   with lock: shared += 1
来源：http://dali.cashguo.top/Article/details/gtljwsimqt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.svipenyu.cn/Article/details/gtrsnzwpxo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pengpengdd.cyou/Article/details/gtapmetlxu.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtldfleran.html

Java: synchronized (this) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gtthdnipux.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.smart0.xyz/Article/details/gtehblerib.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.9152youxi.cn/Article/details/gtlbifejsm.html

C#:   lock (gate) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gtajoxpnfu.html

[O04] 定义异步函数并等待
来源：http://dali.zhengqikj.top/Article/details/gtchtvzdtv.html

Py:   async def f():⏎    await g()
来源：http://dali.cucudq.cn/Article/details/gtkqbbkjke.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shanyushiyangtech.top/Article/details/gtywplmoyv.html

JS:   async function f() { await g(); }
来源：http://dali.jianghu66.top/Article/details/gttrpevqyj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yangfankeji.com/Article/details/gtwfvkjoiz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nwbrower.top/Article/details/gtqvurezit.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jianghu66.top/Article/details/gtvsguazcq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hfpthk.cn/Article/details/gtfveewoea.html

C#:   async Task F() { await G(); }
来源：http://dali.vqdsnc.cn/Article/details/gthvhwdrdx.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhiwuduotai.top/Article/details/gtqdujvjbz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tian-w.cn/Article/details/gteegijzeh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.vqdsnc.cn/Article/details/gtqmfaubkj.html

JS:   await Promise.all(tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gtidytfsdd.html

TS:   await Promise.all(tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnmnafuw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.snrcjt.cn/Article/details/gtoxfugvzx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shangyingyoupin.top/Article/details/gtqjcigczg.html

Ruby: threads.map(&:join)
来源：http://dali.andypj.xyz/Article/details/gtzgjwdlhd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenjidiqi.icu/Article/details/gtzufdiviy.html

[O06] 使用进程池
来源：http://dali.daria6918.cn/Article/details/gtitutiylp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.birdmap.top/Article/details/gtacfpeyqy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gaohongyu789.top/Article/details/gtptepicsd.html

JS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gtqwnturuz.html

TS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gtgkquwrmd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hywenlv.cn/Article/details/gtpyvfupqj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cucudq.cn/Article/details/gtlnnbruep.html

Ruby: // fork 块
来源：http://dali.hammf.cn/Article/details/gtnrqvzlty.html

C#:   Parallel.For
来源：http://dali.yj20258888.top/Article/details/gtwprpvxqo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtupncmpbz.html

P. 常用工具函数
来源：http://dali.hfpthk.cn/Article/details/gtceabymcv.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtmsjngpnl.html

[P01] 生成 UUID
来源：http://dali.birdmap.top/Article/details/gtzmjftqxa.html

Py:   str(uuid.uuid4())
来源：http://dali.bjfxy.top/Article/details/gtojylmfvi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shangyingyoupin.top/Article/details/gtrdtkgfqw.html

JS:   crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gtlnnaagjg.html

TS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtyoygwuxc.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnxiangtu.top/Article/details/gtspfwzvxi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.pengpengdd.cyou/Article/details/gtriqjiffa.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxinkj.top/Article/details/gtkfsqkckl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.quarkkingdee.top/Article/details/gtkzrzpnma.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daxiang520.top/Article/details/gtwumhnmbv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ybcxt.top/Article/details/gtzjmewbku.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhongyouzk.top/Article/details/gtnalidovd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aibaodan.cn/Article/details/gtlxtfmcth.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yueranfly.top/Article/details/gtjnyhqoky.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtloyadqxe.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.haohaochexian.top/Article/details/gtkibegycb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.haohaochexian.top/Article/details/gtpztxueue.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pengpengdd.cyou/Article/details/gtembophgd.html

[P03] 生成短随机字符串
来源：http://dali.fengsongda.top/Article/details/gtjakzlsdx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhoulong.xyz/Article/details/gtsgchooyx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zycfv.cn/Article/details/gtjyprvcsq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xinyue.icu/Article/details/gtcelahynl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gtvagqhatp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cashguo.top/Article/details/gtykdtcphk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.birdmap.top/Article/details/gtyqkrekgv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.pycfn.com/Article/details/gtorvixxfp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xuetiantiany.cn/Article/details/gtrvtoonkt.html

[P04] 求长度
来源：http://dali.shuidangran.top/Article/details/gtihqewzhx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ehwqpu.com/Article/details/gtnbbvqega.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtkwsighjo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daria6918.cn/Article/details/gtnhepysqr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gtfhkgewjn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.haohaochexian.top/Article/details/gtcvujpacl.html

Go:   len(arr);  len(m)
来源：http://dali.fengsongda.top/Article/details/gtjnwhwvvb.html

Ruby: x.length;  x.size
来源：http://dali.svipenyu.cn/Article/details/gttdpehjts.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shzxlz.cn/Article/details/gtdpdhxrwd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jqgufenzy.top/Article/details/gtapnvulnx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj202588.top/Article/details/gtcznyfxny.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkfbusqc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shzxlz.cn/Article/details/gtnwkndajj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj202588.top/Article/details/gtofwmitsj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jiagoushi.top/Article/details/gtnzpklnvz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yongpay.top/Article/details/gtnlnflces.html

Ruby: a == b
来源：http://dali.hammf.cn/Article/details/gtcuhokmjj.html


<!-- 参考信息 -->