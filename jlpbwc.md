代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gtepvtnaub.html

[L08] 并发请求多个地址
来源：http://dali.bjfxy.top/Article/details/gtfadosylp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yanxiufei.cn/Article/details/gtctszlasy.html

PHP:  curl_multi_init() 系列
来源：http://dali.gzhubu.top/Article/details/gtwmtvtvmi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbavlvwb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtiynbrtrh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guowangkeji.top/Article/details/gtbncpexid.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenlongwang.top/Article/details/gtbnojbrrg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ehwqpu.com/Article/details/gthnrciitv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tanke756.top/Article/details/gtgbujvney.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtvveyqeby.html

M. 命令行 / 进程 / 环境
来源：http://dali.yangfankeji.com/Article/details/gtgpnekwcc.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtgsxmtank.html

[M01] 读取命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgmjgzuw.html

Py:   sys.argv[1:]
来源：http://dali.yueranfly.top/Article/details/gtpbjsvuut.html

PHP:  $argv;  $argc;
来源：http://dali.mhx1999.top/Article/details/gtdbqdusam.html

JS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gtbynnsyeh.html

TS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtpjxlayhj.html

Java: args 数组（main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtscxacemw.html

Go:   os.Args[1:]
来源：http://dali.zycfv.cn/Article/details/gtmgwxwsxh.html

Ruby: ARGV
来源：http://dali.meibo888.top/Article/details/gtmqjgdqrj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gtpwvvfeab.html

[M02] 读取环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydkjvybj.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtlxvweonm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjzbhyem.html

JS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gtelesvawy.html

TS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gtfwmwdfkw.html

Java: System.getenv("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtedzxxsiw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkaiqscqp.html

Ruby: ENV["HOME"]
来源：http://dali.nwbrower.top/Article/details/gtetdpuzmr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtywccicbb.html

[M03] 执行外部命令
来源：http://dali.kuanghao11.cn/Article/details/gtwbceagcj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnqzz.top/Article/details/gtlkhaqqis.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhengqikj.top/Article/details/gtezscdbdx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gtaomuktne.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzffkbbpt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttovbauxo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangdashe.top/Article/details/gttxgcpvbs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sweek.top/Article/details/gtpjmnxvqi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gotoacloud.top/Article/details/gtlsmbkjht.html

[M04] 获取当前工作目录
来源：http://dali.nanxuanxn.top/Article/details/gturiizpdw.html

Py:   os.getcwd()
来源：http://dali.fzhhl.top/Article/details/gtisvbluus.html

PHP:  getcwd();
来源：http://dali.0kj1m.cn/Article/details/gtgaxcowkt.html

JS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gthhbocvuy.html

TS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gtmbewcxts.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigufen.top/Article/details/gtfpgihmgu.html

Go:   os.Getwd()
来源：http://dali.zhoulong.xyz/Article/details/gteyiipetu.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gtnrkwsgih.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhiwuduotai.top/Article/details/gtojuqznxw.html

[M05] 设置退出码
来源：http://dali.shzxlz.cn/Article/details/gtrmbcsydz.html

Py:   sys.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtyjgicrcn.html

PHP:  exit(1);
来源：http://dali.wangdashe.top/Article/details/gtdjayqsoo.html

JS:   process.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtrmagsgpv.html

TS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtgyeuqozd.html

Java: System.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtcisirude.html

Go:   os.Exit(1)
来源：http://dali.tian-w.cn/Article/details/gtbffkubqt.html

Ruby: exit 1
来源：http://dali.vqdsnc.cn/Article/details/gtsutjjiik.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxuxxqii.html

[M06] 向标准错误输出
来源：http://dali.redwolf501.top/Article/details/gtipvsqrtm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gtehiqihiq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ehwqpu.com/Article/details/gtczoauvrr.html

JS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gtqlhbhbbj.html

TS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gtkhnuneox.html

Java: System.err.println("err")
来源：http://dali.birdmap.top/Article/details/gtvwpttbcv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdrtejkg.html

Ruby: warn "err"
来源：http://dali.dianchejie.cn/Article/details/gtyfmgsdjm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cashguo.top/Article/details/gtwldwjzxz.html

[M07] 判断是否为主入口
来源：http://dali.guowangkeji.top/Article/details/gtzpfcxggl.html

Py:   if __name__ == "__main__":
来源：http://dali.cucudq.cn/Article/details/gtodcsbtlg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ydzc1.top/Article/details/gturyqjfuj.html

JS:   require.main === module
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqlatxsg.html

TS:   require.main === module
来源：http://dali.snrcjt.cn/Article/details/gtzjobimvv.html

Java: public static void main(String[] args)
来源：http://dali.0kj1m.cn/Article/details/gtrewxnjrz.html

Go:   func main()
来源：http://dali.cdnleiting.top/Article/details/gtaiyeiika.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shzxlz.cn/Article/details/gtpcektvls.html

C#:   static void Main(string[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gtcxmwtety.html

[M08] 获取系统与运行时信息
来源：http://dali.hnxiangtu.top/Article/details/gtnuhbuxpe.html

Py:   platform.system();  platform.python_version()
来源：http://dali.svipenyu.cn/Article/details/gtnugewjsj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sweek.top/Article/details/gtwxzgcbds.html

JS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtvxbiuaav.html

TS:   process.platform;  process.version
来源：http://dali.hongshengwenyu.top/Article/details/gtwrwzewbc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.0kj1m.cn/Article/details/gtaenpuexn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sxryk.cn/Article/details/gtjvxaixrk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.316326.xyz/Article/details/gtynladliy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuxming.cn/Article/details/gtgxisqaph.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtecxcvbbm.html

N. 数据结构与算法
来源：http://dali.zdqjudy.top/Article/details/gtseglbjsr.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtyfffdgpj.html

[N01] 二分查找（有序数组）
来源：http://dali.xuetiantiany.cn/Article/details/gtvjdwyyez.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtppwkdycv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sufxvd.cn/Article/details/gtmrmlaarb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtyvyijvrv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gtcwwlcoqi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtsusdwdvp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtpfgjwumq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqvqboiq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gtiliplabg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dashuyun.cn/Article/details/gtikqvpocg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gtgszmqnca.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shzxlz.cn/Article/details/gtlkiuxoko.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gtdtiqjlzn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gtvgdbjcqc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gtrqjxijes.html

Go:   slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gtyzikobuy.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gtwepssjtm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aibaodan.cn/Article/details/gtqxlllrmn.html

[N03] 快速排序（分治示例）
来源：http://dali.pycfn.com/Article/details/gtrqncwelk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.andypj.xyz/Article/details/gtkmcqmjuf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xziqi.cn/Article/details/gtlvlxzdvl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gtvxftanzb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gaohongyu789.top/Article/details/gtptjskdjs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zdqjudy.top/Article/details/gtflzuzxpe.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jyoumei.cn/Article/details/gtievjhkdx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfsnbomp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigfzy.top/Article/details/gturqvqcyg.html

[N04] 斐波那契数列
来源：http://dali.chenzaomai.com/Article/details/gthtpcxeeo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gttszxirsf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cdnleiting.top/Article/details/gtpsiidyqj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtgibxdgqw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtgnfdlako.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258.top/Article/details/gtjwinthms.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.quarkkingdee.top/Article/details/gtakdepats.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cheryme.top/Article/details/gtmvtxspjw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtfrxmqxfm.html

[N05] 最大公约数
来源：http://dali.dashuyun.cn/Article/details/gtszuesdkq.html

Py:   math.gcd(a, b)
来源：http://dali.xuanzx.com/Article/details/gtrxlwzysj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtmasazhri.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gtqvhducbo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gtggskbgeb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daxiang520.top/Article/details/gtmlwuovap.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.9152youxi.cn/Article/details/gtreeamapn.html

Ruby: a.gcd(b)
来源：http://dali.haohaochexian.top/Article/details/gtvvbysodk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.meibo888.top/Article/details/gtiahcrxpq.html

[N06] 判断回文字符串
来源：http://dali.kuanghao11.cn/Article/details/gtowifhsfr.html

Py:   s == s[::-1]
来源：http://dali.jyoumei.cn/Article/details/gtyzsbzium.html

PHP:  $s === strrev($s);
来源：http://dali.yj20258.top/Article/details/gtbwvvmzxd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtgxphxapf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqfyfbjd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xylfe.cn/Article/details/gtadakozlp.html

Go:   // 双指针从两端比较
来源：http://dali.daxiang520.top/Article/details/gtrzudxbnr.html

Ruby: s == s.reverse
来源：http://dali.sysykeji.top/Article/details/gtnwglhrue.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cheryme.top/Article/details/gtlecvcecx.html

[N07] 两数之和（返回下标）
来源：http://dali.zhoulong.xyz/Article/details/gtgvxygmyd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj202588.top/Article/details/gtakwxxigw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.bjfxy.top/Article/details/gtnvziisfk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hywenlv.cn/Article/details/gtalyyddsr.html

TS:   // 手写 Map<string, number>
来源：http://dali.guannengcc.top/Article/details/gtawqxlplk.html

Java: // 手写 HashMap
来源：http://dali.0kj1m.cn/Article/details/gtwrwqazed.html

Go:   // 手写 map[int]int
来源：http://dali.cdnleiting.top/Article/details/gtxcexpmfg.html

Ruby: // 手写 Hash
来源：http://dali.yongpay.top/Article/details/gtnqxnemlr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daria6918.cn/Article/details/gtpnhtulan.html

[N08] 生成全排列
来源：http://dali.zhiwuduotai.top/Article/details/gtcrvirhtk.html

Py:   itertools.permutations(arr)
来源：http://dali.wangdashe.top/Article/details/gtysbogwfc.html

PHP:  // 手写递归交换
来源：http://dali.cheryme.top/Article/details/gtgegxzjcc.html

JS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtdbxwibaa.html

TS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtfvmwvuqb.html

Java: // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtjubkhotv.html

Go:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtdobdfrkb.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxinkj.top/Article/details/gtyeztiinv.html

C#:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtkuefpqha.html

[N09] 栈与队列
来源：http://dali.wangshuangyany.cn/Article/details/gtbbgbvxqw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258888.top/Article/details/gteofqpfdv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtbnoefziq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gtbrojnayv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxinkj.top/Article/details/gtdxibglpk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dashuyun.cn/Article/details/gtsapjyqme.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ppjwa.cn/Article/details/gtqnxnwpuj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gtoyvkufmo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hfpthk.cn/Article/details/gtpiraowji.html

[N10] 链表节点定义
来源：http://dali.jiagoushi.top/Article/details/gtfkamfmng.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.snrcjt.cn/Article/details/gtogupjhpa.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zycfv.cn/Article/details/gtrtneewxf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nwbrower.top/Article/details/gtffoeefvd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxuanxn.top/Article/details/gtpiefcdrj.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gtqtzkkyhg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.dashuyun.cn/Article/details/gtkjtqmerz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ydzc1.top/Article/details/gtjoaittuz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xylfe.cn/Article/details/gtxivbkjwb.html

[N11] 二叉树中序遍历
来源：http://dali.andypj.xyz/Article/details/gtuvzejppn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yonumen.top/Article/details/gtibgenmtp.html

PHP:  // 手写递归函数
来源：http://dali.tianlin.xyz/Article/details/gttkmzppjy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shuidangran.top/Article/details/gtqneespoj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gtkgylfdce.html

Java: // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkohlxao.html

Go:   // 手写递归
来源：http://dali.aizwys.cn/Article/details/gtetjljjbn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hywenlv.cn/Article/details/gtlolsinrp.html

C#:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtqqgzgkqo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yongpay.top/Article/details/gtlehzbtay.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ivvv.top/Article/details/gtpozsoebg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.bjfxy.top/Article/details/gteolfxorm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gtohbvqbdg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gtwroyoalk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gtbytbgizu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sxryk.cn/Article/details/gtkcbfqmtv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.c1oappe.top/Article/details/gtcsyczjvo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gtzoenlygw.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtlrrbexcv.html

O. 并发与异步
来源：http://dali.aibaodan.cn/Article/details/gtqmswfowt.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtwpccvynf.html

[O01] 启动一个线程
来源：http://dali.hnxiangtu.top/Article/details/gtdzyaourk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xuanzx.com/Article/details/gtsplhtzoy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258.top/Article/details/gtynevfxmy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cashguo.top/Article/details/gtknzrgqcw.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivppqklu.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigfzy.top/Article/details/gtrtjxxwtd.html

Go:   go f()
来源：http://dali.smart0.xyz/Article/details/gtqgtbedpl.html

Ruby: Thread.new { f }
来源：http://dali.aizwys.cn/Article/details/gtcwycvrvs.html

C#:   Task.Run(() => F());
来源：http://dali.fzhhl.top/Article/details/gtuphdrdan.html

[O02] 使用线程池
来源：http://dali.zhongyouzk.top/Article/details/gtsminteoq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yueranfly.top/Article/details/gtaqeretcu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.meibo888.top/Article/details/gtzhouhmwe.html

JS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawgkqavj.html

TS:   // worker_threads 线程池
来源：http://dali.hysaishi.cn/Article/details/gteioyudlf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ivvv.top/Article/details/gtwhlyamwn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqwhkolv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tianlin.xyz/Article/details/gthbshknzz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xylfe.cn/Article/details/gtpszymqjy.html

[O03] 加锁保护共享数据
来源：http://dali.dianchejie.cn/Article/details/gtpvwcqihl.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnnbyjyq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuxming.cn/Article/details/gtocbsczuz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dianchejie.cn/Article/details/gtoahkkvvq.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gtvmopdsox.html

Java: synchronized (this) { shared++; }
来源：http://dali.ehwqpu.com/Article/details/gtfflipklx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cdnleiting.top/Article/details/gtlxgdspng.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenzaomai.com/Article/details/gtlcceztcb.html

C#:   lock (gate) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gtpsyuhzau.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigfzy.top/Article/details/gtouwefgfu.html

Py:   async def f():⏎    await g()
来源：http://dali.havefunace.top/Article/details/gtytjkapfr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pengpengdd.cyou/Article/details/gtpzclipai.html

JS:   async function f() { await g(); }
来源：http://dali.nwbrower.top/Article/details/gtzlrbqktl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.havefunace.top/Article/details/gtucvazdgs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ehwqpu.com/Article/details/gtthzbgfde.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258888.top/Article/details/gtaxktjqnn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hongshengwenyu.top/Article/details/gtfjurymoq.html

C#:   async Task F() { await G(); }
来源：http://dali.fengsongda.top/Article/details/gtozqkqhru.html

[O05] 并发执行并等待全部完成
来源：http://dali.tianlin.xyz/Article/details/gtjkxggjjw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gzhubu.top/Article/details/gttjvgdhly.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.vqdsnc.cn/Article/details/gtncejbgym.html

JS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gtovzkgpwt.html

TS:   await Promise.all(tasks)
来源：http://dali.xylfe.cn/Article/details/gtjbpqfqim.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtliytqncv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xuanzx.com/Article/details/gtcpspqcig.html

Ruby: threads.map(&:join)
来源：http://dali.iojbl.cn/Article/details/gtppuergxe.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.kuanghao11.cn/Article/details/gtsuaepqls.html

[O06] 使用进程池
来源：http://dali.snrcjt.cn/Article/details/gtrxvraasg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.316326.xyz/Article/details/gtdlqjtful.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tian-w.cn/Article/details/gtczicukcs.html

JS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gtbdalsjpv.html

TS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gtvgkadqyy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gtwbmxylyw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhiwuduotai.top/Article/details/gtowijvwbc.html

Ruby: // fork 块
来源：http://dali.nwbrower.top/Article/details/gtdznmyepi.html

C#:   Parallel.For
来源：http://dali.gotoacloud.top/Article/details/gtfsaltqeg.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtfrbcggqg.html

P. 常用工具函数
来源：http://dali.jinqigfzy.top/Article/details/gtsxceygos.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtmeysxcpr.html

[P01] 生成 UUID
来源：http://dali.nanxuanxn.top/Article/details/gtptpjlyqe.html

Py:   str(uuid.uuid4())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsozzjnwz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenlongwang.top/Article/details/gtusgnmysq.html

JS:   crypto.randomUUID()
来源：http://dali.nanxuanxn.top/Article/details/gtjxhhorrx.html

TS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gtmdontlar.html

Java: UUID.randomUUID().toString()
来源：http://dali.sweek.top/Article/details/gtkcbvtvtp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ivvv.top/Article/details/gtqcsoyvpv.html

Ruby: SecureRandom.uuid
来源：http://dali.daria6918.cn/Article/details/gthhnehqmj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenzaomai.com/Article/details/gtjoswfull.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gotoacloud.top/Article/details/gtuvydvgnn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.pycfn.com/Article/details/gtvsymwoah.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.wangdashe.top/Article/details/gtmwjjeqzb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jqgfzy.top/Article/details/gtkbbtupwh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gotoacloud.top/Article/details/gteznvfpbu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gteisyknrg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dianchejie.cn/Article/details/gttynoguwe.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbypqkbt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.havefunace.top/Article/details/gtdpgowphf.html

[P03] 生成短随机字符串
来源：http://dali.xziqi.cn/Article/details/gtaomrltkw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.quarkkingdee.top/Article/details/gtqnqcjbwb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cheryme.top/Article/details/gtolhibqtq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtwrlambba.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gtmpuobpal.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nanxuanxn.top/Article/details/gttbwkxsas.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tian-w.cn/Article/details/gtpkmszqkl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuetiantiany.cn/Article/details/gtswceleog.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hfpthk.cn/Article/details/gtufudqido.html

[P04] 求长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtiiciymbi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tanke756.top/Article/details/gtuecxzbjl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtmkvhgyli.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zdqjudy.top/Article/details/gttzmhereg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cashguo.top/Article/details/gtazyzugby.html

Java: list.size();  map.size();  s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gtwnvqmkkv.html

Go:   len(arr);  len(m)
来源：http://dali.nanxuanxn.top/Article/details/gtywswwuqw.html

Ruby: x.length;  x.size
来源：http://dali.jlsjyb.cn/Article/details/gtvuwqglbg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.havefunace.top/Article/details/gtjxkykhgn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinqigufen.top/Article/details/gtuyxghwzb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hysaishi.cn/Article/details/gtdtrpyabp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daxiang520.top/Article/details/gtyravuycx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.redwolf501.top/Article/details/gtskaylmub.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hywenlv.cn/Article/details/gtqyngafti.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jlsjyb.cn/Article/details/gtelotweuh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hysaishi.cn/Article/details/gtxvwrqdip.html

Ruby: a == b
来源：http://dali.nanxinkj.top/Article/details/gtbxtrvzpl.html


<!-- 参考信息 -->