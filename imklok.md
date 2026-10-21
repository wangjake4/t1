代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gtqdqxlfoi.html

[L08] 并发请求多个地址
来源：http://dali.xziqi.cn/Article/details/gtxugprlae.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.quarkkingdee.top/Article/details/gtpxbnelex.html

PHP:  curl_multi_init() 系列
来源：http://dali.yangfankeji.com/Article/details/gtkhfeoaoj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gtojgcclri.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtoltpauir.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuetiantiany.cn/Article/details/gtmzinilwp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gotoacloud.top/Article/details/gtaihsgoee.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhixingplan.top/Article/details/gthjisuqun.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtvmblnslj.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtuawioemb.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgufenzy.top/Article/details/gtqpnjohit.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtdhwjodpc.html

[M01] 读取命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtoiuretex.html

Py:   sys.argv[1:]
来源：http://dali.ybcxt.top/Article/details/gtkyanebmd.html

PHP:  $argv;  $argc;
来源：http://dali.jiagoushi.top/Article/details/gtkshhxktj.html

JS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gtvofctsfr.html

TS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gttxozricf.html

Java: args 数组（main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gtggbqlzah.html

Go:   os.Args[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtgtdjrabp.html

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gtlxmuazxa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gtfluvrebv.html

[M02] 读取环境变量
来源：http://dali.xuanzx.com/Article/details/gtysyvqrmx.html

Py:   os.environ.get("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtbnrphnua.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gtmdzltjof.html

JS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gtqwcojiks.html

TS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gteywcvwdf.html

Java: System.getenv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtyrgaliid.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtcxaoeaht.html

Ruby: ENV["HOME"]
来源：http://dali.cqqwz.cn/Article/details/gthdsoagwj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258888.top/Article/details/gtdoagofxn.html

[M03] 执行外部命令
来源：http://dali.nanxuanxn.top/Article/details/gtdiouxumb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gotoacloud.top/Article/details/gtfvtzqcot.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jianghu66.top/Article/details/gtjhkryxku.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gtmnfknrix.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gtxowackrk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aizwys.cn/Article/details/gtihtpbcjw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gotoacloud.top/Article/details/gtujfuzwow.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xylfe.cn/Article/details/gtfcrepnsw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.c1oappe.top/Article/details/gtprzpddej.html

[M04] 获取当前工作目录
来源：http://dali.yj20258.top/Article/details/gtcuvefyit.html

Py:   os.getcwd()
来源：http://dali.yueranfly.top/Article/details/gtrmzaxsop.html

PHP:  getcwd();
来源：http://dali.shuidangran.top/Article/details/gtrhtluhyw.html

JS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gtjxmnuvuk.html

TS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gtyxegvkzz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ehwqpu.com/Article/details/gtadhawmjz.html

Go:   os.Getwd()
来源：http://dali.jinqigufen.top/Article/details/gtlxlgpcym.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gtktsxaudv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhengqikj.top/Article/details/gttkzukvev.html

[M05] 设置退出码
来源：http://dali.snrcjt.cn/Article/details/gtajjqzthv.html

Py:   sys.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtevtoftiq.html

PHP:  exit(1);
来源：http://dali.nanxinkj.top/Article/details/gtxxzrnbwc.html

JS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtgunlixld.html

TS:   process.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtfgbphfnb.html

Java: System.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtxlrdlzbs.html

Go:   os.Exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtcqfjqqor.html

Ruby: exit 1
来源：http://dali.aizwys.cn/Article/details/gtmgkypfbh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenlongwang.top/Article/details/gthjdadgbt.html

[M06] 向标准错误输出
来源：http://dali.9152youxi.cn/Article/details/gtrfmhvkxs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jlsjyb.cn/Article/details/gtgwktdqpp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gtoyfokglz.html

JS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gtjgfqkpmx.html

TS:   console.error("err")
来源：http://dali.yvedp.cn/Article/details/gtbpolzdbs.html

Java: System.err.println("err")
来源：http://dali.xinyue.icu/Article/details/gtazhusyvu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.birdmap.top/Article/details/gtmyruxwlq.html

Ruby: warn "err"
来源：http://dali.cheryme.top/Article/details/gtpiqvrhav.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guowangkeji.top/Article/details/gtxjpyhfea.html

[M07] 判断是否为主入口
来源：http://dali.redwolf501.top/Article/details/gtolhczzqe.html

Py:   if __name__ == "__main__":
来源：http://dali.ivvv.top/Article/details/gtgnumxsgi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ehwqpu.com/Article/details/gtfqsqqeus.html

JS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gtkrczpwkq.html

TS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gtfboavayz.html

Java: public static void main(String[] args)
来源：http://dali.daxiang520.top/Article/details/gtxsccbire.html

Go:   func main()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcdkrcabu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.feifeiyinyue.top/Article/details/gtttigulou.html

C#:   static void Main(string[] args)
来源：http://dali.yongpay.top/Article/details/gtepzobwly.html

[M08] 获取系统与运行时信息
来源：http://dali.yueranfly.top/Article/details/gtnmiykkhg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuanzhike.top/Article/details/gtyheqpmyf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pengpengdd.cyou/Article/details/gtcttbhjlw.html

JS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrdkgowy.html

TS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtcimjumhy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cdnleiting.top/Article/details/gtdylmnnao.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pycfn.com/Article/details/gtmvoeojag.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hammf.cn/Article/details/gtqmhxfiiu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jianghu66.top/Article/details/gtubutyebh.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gthasfngff.html

N. 数据结构与算法
来源：http://dali.hnqzz.top/Article/details/gtxuceqefo.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtufahrszr.html

[N01] 二分查找（有序数组）
来源：http://dali.cheryme.top/Article/details/gtxtwaadfo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtdxbndzua.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtdvfaaeyr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtqviqngkq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtdrlrshzq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtrjhxmmgl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtpmtcmidm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.havefunace.top/Article/details/gtyxrdggjn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gtbyknpwri.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.mhx1999.top/Article/details/gttvblfaue.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gaohongyu789.top/Article/details/gtwhklywgv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sweek.top/Article/details/gtfbdvndbz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gtrfutvmun.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gtqpwzvtnp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aibaodan.cn/Article/details/gtqtfmppcb.html

Go:   slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gtpnghijdr.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdxhyspr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yvedp.cn/Article/details/gtunjrixrq.html

[N03] 快速排序（分治示例）
来源：http://dali.0kj1m.cn/Article/details/gtrggfqhzi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gaohongyu789.top/Article/details/gtdvpsmimn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ybcxt.top/Article/details/gttmbhzitv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gtkvkobjwf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gtbpuatjai.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.bjfxy.top/Article/details/gtpbrzbrne.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hammf.cn/Article/details/gtjnssiipj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hysaishi.cn/Article/details/gtqotbtcqd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gtvmolznnx.html

[N04] 斐波那契数列
来源：http://dali.birdmap.top/Article/details/gtyiogdwop.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gtjjtjqrfv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258888.top/Article/details/gtblplptur.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtucraeqqj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gthoffjaqm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daxiang520.top/Article/details/gtbjtsewrb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jyoumei.cn/Article/details/gtqednqsvb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gtnhlobwiw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtnbhupyga.html

[N05] 最大公约数
来源：http://dali.cdnleiting.top/Article/details/gttqgtvyyk.html

Py:   math.gcd(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpewvomyr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.vqdsnc.cn/Article/details/gtynluxszz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkddkpuuh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.meibo888.top/Article/details/gtjtlfcyze.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cashguo.top/Article/details/gtaiizounq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.quarkkingdee.top/Article/details/gtkktyrdrl.html

Ruby: a.gcd(b)
来源：http://dali.jinqigufen.top/Article/details/gtwzajyqsu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.9152youxi.cn/Article/details/gtydowzeaq.html

[N06] 判断回文字符串
来源：http://dali.hnqzz.top/Article/details/gtimorlfku.html

Py:   s == s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gtihrjvcih.html

PHP:  $s === strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gtawleeojn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtzmluudge.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtpqwkquss.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ppjwa.cn/Article/details/gtfbzcaspe.html

Go:   // 双指针从两端比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcltipcj.html

Ruby: s == s.reverse
来源：http://dali.daxiang520.top/Article/details/gtcasloxoa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ppjwa.cn/Article/details/gtkzrygrdk.html

[N07] 两数之和（返回下标）
来源：http://dali.hongshengwenyu.top/Article/details/gtzfyadimv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangdashe.top/Article/details/gtcxjigqpx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgfzy.top/Article/details/gtruvgklvx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnxiangtu.top/Article/details/gtbcdoauei.html

TS:   // 手写 Map<string, number>
来源：http://dali.snrcjt.cn/Article/details/gtxehxpvxh.html

Java: // 手写 HashMap
来源：http://dali.hfpthk.cn/Article/details/gtugmaqbbh.html

Go:   // 手写 map[int]int
来源：http://dali.cucudq.cn/Article/details/gtjcsulvqu.html

Ruby: // 手写 Hash
来源：http://dali.zhongyouzk.top/Article/details/gtqfgtvppv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cqqwz.cn/Article/details/gtohmjqhgj.html

[N08] 生成全排列
来源：http://dali.yangfankeji.com/Article/details/gthmudsooc.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigfzy.top/Article/details/gttpzlaffr.html

PHP:  // 手写递归交换
来源：http://dali.ivvv.top/Article/details/gtosrzuuar.html

JS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtnihbwtiq.html

TS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtlcyervhd.html

Java: // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtdsyvwrfp.html

Go:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtpxskemaa.html

Ruby: arr.permutation.to_a
来源：http://dali.tanke756.top/Article/details/gttyvifuck.html

C#:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtqrhwydkl.html

[N09] 栈与队列
来源：http://dali.sxryk.cn/Article/details/gtdibpjhuo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aizwys.cn/Article/details/gthvqxuphg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtepjsdrgn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gtkmiwsgiq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aizwys.cn/Article/details/gtqdngsdgm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tianlin.xyz/Article/details/gtfeekamvg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gthadzugxa.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtdaorjash.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jqgfzy.top/Article/details/gtaeqeauwu.html

[N10] 链表节点定义
来源：http://dali.gogol.net.cn/Article/details/gtgzapypcr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhixingplan.top/Article/details/gtpgyxfgqa.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hammf.cn/Article/details/gtxnypfpyy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhengqikj.top/Article/details/gterzvtwur.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tianlin.xyz/Article/details/gttsnkbzau.html

Java: class Node { int v; Node next; }
来源：http://dali.nanxuanxn.top/Article/details/gtkistdnyp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nanxuanxn.top/Article/details/gtwwmvlpya.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nanxinkj.top/Article/details/gtnivqozqd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tian-w.cn/Article/details/gtijffafsk.html

[N11] 二叉树中序遍历
来源：http://dali.redwolf501.top/Article/details/gtraknsmlw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hfpthk.cn/Article/details/gtjgvppxow.html

PHP:  // 手写递归函数
来源：http://dali.hnxiangtu.top/Article/details/gthxeshdjy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gttmowlone.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gtfvrhpuui.html

Java: // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gtaxmtzhnh.html

Go:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtjsswtsjw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.birdmap.top/Article/details/gtxjewztbz.html

C#:   // 手写递归
来源：http://dali.smart0.xyz/Article/details/gttphpqfpp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ehwqpu.com/Article/details/gtqdqowqlt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.birdmap.top/Article/details/gtgikhrujy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjxqecez.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gtytxxhqck.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gtvplxpvay.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gtsduyxkod.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigfzy.top/Article/details/gtjbmxwmww.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoolurnhl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenzaomai.com/Article/details/gtpfakjhys.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtblvjzzqs.html

O. 并发与异步
来源：http://dali.svipenyu.cn/Article/details/gtieyovxvh.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtctoyyxun.html

[O01] 启动一个线程
来源：http://dali.nanxuanxn.top/Article/details/gtzarntsnh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jlsjyb.cn/Article/details/gtelwjnxyf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnxiangtu.top/Article/details/gtfjhsamsu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gotoacloud.top/Article/details/gtizlfaxff.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gtbbayvlxt.html

Java: new Thread(() -> f()).start()
来源：http://dali.nwbrower.top/Article/details/gtkevicuyi.html

Go:   go f()
来源：http://dali.iojbl.cn/Article/details/gthkajfodm.html

Ruby: Thread.new { f }
来源：http://dali.vqdsnc.cn/Article/details/gthwumhioe.html

C#:   Task.Run(() => F());
来源：http://dali.dashuyun.cn/Article/details/gtecvppoje.html

[O02] 使用线程池
来源：http://dali.jlsjyb.cn/Article/details/gtidwosquk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.feifeiyinyue.top/Article/details/gtkyixibxv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.haohaochexian.top/Article/details/gtdrvsqyoi.html

JS:   // worker_threads 线程池
来源：http://dali.snrcjt.cn/Article/details/gtfbesnhoj.html

TS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gtxcdyhbci.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigufen.top/Article/details/gtlcvzunip.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ppjwa.cn/Article/details/gtawfazvny.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ppjwa.cn/Article/details/gtrmqbliks.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zdqjudy.top/Article/details/gtuaeefrdv.html

[O03] 加锁保护共享数据
来源：http://dali.fzhhl.top/Article/details/gtbybalimv.html

Py:   with lock: shared += 1
来源：http://dali.mhx1999.top/Article/details/gtzuwepphk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shuidangran.top/Article/details/gtrqodrccq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.mhx1999.top/Article/details/gtiwelizxa.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gtewsvbpkw.html

Java: synchronized (this) { shared++; }
来源：http://dali.ivvv.top/Article/details/gtpuchabpl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxzighxr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.dashuyun.cn/Article/details/gtdtacujdi.html

C#:   lock (gate) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gthxuynmcf.html

[O04] 定义异步函数并等待
来源：http://dali.pycfn.com/Article/details/gtqikiingl.html

Py:   async def f():⏎    await g()
来源：http://dali.sweek.top/Article/details/gtruucopgq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hfpthk.cn/Article/details/gthrsiimcg.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gtqyddgkns.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajqmsusl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sufxvd.cn/Article/details/gtefyhdags.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhoulong.xyz/Article/details/gtpesnjfop.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gtpwuuuetw.html

C#:   async Task F() { await G(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtgaxxhvev.html

[O05] 并发执行并等待全部完成
来源：http://dali.316326.xyz/Article/details/gthulkuouv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dianchejie.cn/Article/details/gtkmisbkff.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gotoacloud.top/Article/details/gtsbaiifzy.html

JS:   await Promise.all(tasks)
来源：http://dali.jyoumei.cn/Article/details/gtxubwjkgz.html

TS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gtpwfkhgym.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.vqdsnc.cn/Article/details/gtapzcvpfv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.0kj1m.cn/Article/details/gtzvnnojkt.html

Ruby: threads.map(&:join)
来源：http://dali.shangyingyoupin.top/Article/details/gtdvfottfq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenjidiqi.icu/Article/details/gtawsudakd.html

[O06] 使用进程池
来源：http://dali.hammf.cn/Article/details/gtoznndwlc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangdashe.top/Article/details/gtnyuwwxva.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.birdmap.top/Article/details/gthjigizky.html

JS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gtcndkdxyh.html

TS:   // child_process / cluster 模块
来源：http://dali.yj202588.top/Article/details/gtstswcrir.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gaohongyu789.top/Article/details/gtuiqklzje.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cqqwz.cn/Article/details/gtdjixkplo.html

Ruby: // fork 块
来源：http://dali.gotoacloud.top/Article/details/gtombfvszo.html

C#:   Parallel.For
来源：http://dali.nanxinkj.top/Article/details/gtcbsujqyu.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtkbprrjhr.html

P. 常用工具函数
来源：http://dali.zhengqikj.top/Article/details/gtmgiadxfp.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvvgdvqc.html

[P01] 生成 UUID
来源：http://dali.cheryme.top/Article/details/gtsjshpanj.html

Py:   str(uuid.uuid4())
来源：http://dali.iojbl.cn/Article/details/gtjmqpeqww.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhoulong.xyz/Article/details/gtttnwubbj.html

JS:   crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gtmphhyspg.html

TS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gtxbavqyyu.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigufen.top/Article/details/gtyqzgohwt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgufenzy.top/Article/details/gtuzqyffux.html

Ruby: SecureRandom.uuid
来源：http://dali.xuetiantiany.cn/Article/details/gtijqfckbv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yuanzhike.top/Article/details/gtcpwlkguh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hammf.cn/Article/details/gtvkhdxoor.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.haohaochexian.top/Article/details/gtgsvroxzb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aizwys.cn/Article/details/gtvvokrzva.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xuetiantiany.cn/Article/details/gtrkximvzn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.meibo888.top/Article/details/gtalpgvitz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nwbrower.top/Article/details/gtclythtop.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.havefunace.top/Article/details/gtetgvpxab.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shuidangran.top/Article/details/gtwvdevmvm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhengqikj.top/Article/details/gtsxcxgrmm.html

[P03] 生成短随机字符串
来源：http://dali.andypj.xyz/Article/details/gtcxrebrms.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpuhwiewj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlxyvnlc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gtzcqohyqy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dashuyun.cn/Article/details/gtdhaajpym.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnxiangtu.top/Article/details/gtjxzmbhgl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.9152youxi.cn/Article/details/gtlhmhhiku.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sxryk.cn/Article/details/gtaazhmtcl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jlsjyb.cn/Article/details/gtucrxayjz.html

[P04] 求长度
来源：http://dali.0kj1m.cn/Article/details/gtpjwmcdkk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgfzy.top/Article/details/gtzvdxzxyv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gthpwrqxci.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gtlbtmnmdb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gtvxskxsyw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.9152youxi.cn/Article/details/gtuomtpjjy.html

Go:   len(arr);  len(m)
来源：http://dali.tianlin.xyz/Article/details/gthyzsqmgt.html

Ruby: x.length;  x.size
来源：http://dali.chenzaomai.com/Article/details/gtmhgsfeul.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gtocnhxoyq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.haohaochexian.top/Article/details/gtklnsmpix.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xziqi.cn/Article/details/gtadtahbsc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nwbrower.top/Article/details/gtgumpwuel.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yangfankeji.com/Article/details/gtxwoptxek.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhengqikj.top/Article/details/gttcychqgj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj202588.top/Article/details/gtlajmcmxd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yuxming.cn/Article/details/gtqeqrfgpj.html

Ruby: a == b
来源：http://dali.shuidangran.top/Article/details/gtsfvkmmlq.html


<!-- 参考信息 -->