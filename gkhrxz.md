代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gt2ixjvseit.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gt2zsqzradc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ppjwa.cn/Article/details/gt2gokasraw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xinyue.icu/Article/details/gt2eodndyel.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.9152youxi.cn/Article/details/gt2drcscoee.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sweek.top/Article/details/gt2jvbhllgg.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2shozygxw.html

M. 命令行 / 进程 / 环境
来源：http://dali.xinyue.icu/Article/details/gt2bzcbillp.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2fobsmboc.html

[M01] 读取命令行参数
来源：http://dali.xylfe.cn/Article/details/gt2bubdhysh.html

Py:   sys.argv[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2magcqruj.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sszegmal.html

JS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hhptwpyk.html

TS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gt2hncqhxpn.html

Java: args 数组（main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gt2prswdzoq.html

Go:   os.Args[1:]
来源：http://dali.redwolf501.top/Article/details/gt2mlytjdje.html

Ruby: ARGV
来源：http://dali.xziqi.cn/Article/details/gt2jnzsqtdn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gt2obdehppq.html

[M02] 读取环境变量
来源：http://dali.sxryk.cn/Article/details/gt2ffmpmefc.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2usdcjtra.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gt2wqgyxcib.html

JS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gt2toezbuqk.html

TS:   process.env.HOME
来源：http://dali.nwbrower.top/Article/details/gt2oorzryvw.html

Java: System.getenv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bsunqnvr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.meibo888.top/Article/details/gt2jhbzgvck.html

Ruby: ENV["HOME"]
来源：http://dali.hfpthk.cn/Article/details/gt2msoainob.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.birdmap.top/Article/details/gt2yzihhepj.html

[M03] 执行外部命令
来源：http://dali.mhx1999.top/Article/details/gt2laglsjhh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.meibo888.top/Article/details/gt2tutyuzgk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258.top/Article/details/gt2ttxvwylr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gt2zbzpnume.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gt2dtyclubq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.iojbl.cn/Article/details/gt2zphyrjwh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.haohaochexian.top/Article/details/gt2rhoyzsyv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xziqi.cn/Article/details/gt2lrqghmrf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sweek.top/Article/details/gt2ocbsqgpa.html

[M04] 获取当前工作目录
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lfpzrftl.html

Py:   os.getcwd()
来源：http://dali.yongpay.top/Article/details/gt2qkpwuyql.html

PHP:  getcwd();
来源：http://dali.hammf.cn/Article/details/gt2sotwvzfp.html

JS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gt2wgagvcus.html

TS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gt2yczszmvt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tianlin.xyz/Article/details/gt2qwatgxpm.html

Go:   os.Getwd()
来源：http://dali.zhengqikj.top/Article/details/gt2yvcgfaao.html

Ruby: Dir.pwd
来源：http://dali.iojbl.cn/Article/details/gt2shetviie.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.feifeiyinyue.top/Article/details/gt2bwrejxrz.html

[M05] 设置退出码
来源：http://dali.xylfe.cn/Article/details/gt2osqgnast.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqhhbtd.html

PHP:  exit(1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aelbodll.html

JS:   process.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ozuxlxio.html

TS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yztqctdo.html

Java: System.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2klvvdbfy.html

Go:   os.Exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2lawpxtwu.html

Ruby: exit 1
来源：http://dali.hammf.cn/Article/details/gt2hbpdpdfj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yangfankeji.com/Article/details/gt2uzcokugf.html

[M06] 向标准错误输出
来源：http://dali.jqgfzy.top/Article/details/gt2iuqmvflg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hywenlv.cn/Article/details/gt2ihrosbrl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuxming.cn/Article/details/gt2tcnoquff.html

JS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gt2jmylqiwe.html

TS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gt2ksatafgu.html

Java: System.err.println("err")
来源：http://dali.guowangkeji.top/Article/details/gt2ryvodruk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xziqi.cn/Article/details/gt2iqcyxpkm.html

Ruby: warn "err"
来源：http://dali.kuanghao11.cn/Article/details/gt2vemczoev.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sysykeji.top/Article/details/gt2fotygdhr.html

[M07] 判断是否为主入口
来源：http://dali.gogol.net.cn/Article/details/gt2myctlygg.html

Py:   if __name__ == "__main__":
来源：http://dali.svipenyu.cn/Article/details/gt2lryuyfoh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aibaodan.cn/Article/details/gt2kzfmpipy.html

JS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gt2ymhqrpzt.html

TS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gt2grztpaoe.html

Java: public static void main(String[] args)
来源：http://dali.cheryme.top/Article/details/gt2dengsgjs.html

Go:   func main()
来源：http://dali.xuanzx.com/Article/details/gt2uyfugzkp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ehwqpu.com/Article/details/gt2mxabajrm.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lrmhjlxq.html

[M08] 获取系统与运行时信息
来源：http://dali.feifeiyinyue.top/Article/details/gt2pivvlgkl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigfzy.top/Article/details/gt2tclkvvpp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shangyingyoupin.top/Article/details/gt2wrnpnufv.html

JS:   process.platform;  process.version
来源：http://dali.sufxvd.cn/Article/details/gt2xijirjqz.html

TS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gt2pjkpnsbk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yvedp.cn/Article/details/gt2jzkorfcl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj202588.top/Article/details/gt2mnqyolmd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tianlin.xyz/Article/details/gt2boqpohsf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dashuyun.cn/Article/details/gt2qvaqedud.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2xdwkqhfm.html

N. 数据结构与算法
来源：http://dali.zhoulong.xyz/Article/details/gt2ekagfxcd.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2izbkltvq.html

[N01] 二分查找（有序数组）
来源：http://dali.redwolf501.top/Article/details/gt2rhpjihjw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2ldtxvvdu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.guannengcc.top/Article/details/gt2upgjtcff.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gt2npckmtxz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gt2zzqpkxwk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2mrrvtegd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xvccvtqa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhengqikj.top/Article/details/gt2cgmvygww.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2zbqhqzbw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gotoacloud.top/Article/details/gt2rgzylzzh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gt2qhddaozx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yueranfly.top/Article/details/gt2cqbkfmdv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gt2pmuyamwc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gt2vlxwndaf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sweek.top/Article/details/gt2luvjyasr.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gt2pczxwswp.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aurqblxk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.pengpengdd.cyou/Article/details/gt2iodbdenj.html

[N03] 快速排序（分治示例）
来源：http://dali.yvedp.cn/Article/details/gt2fjpjweyx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ehwqpu.com/Article/details/gt2kkrwrjbc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhongyouzk.top/Article/details/gt2vbajwrlz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gogol.net.cn/Article/details/gt2djjbxdtp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gt2lwqtcywc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangshuangyany.cn/Article/details/gt2vatlcoyb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.kuanghao11.cn/Article/details/gt2sbhapjdl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yonumen.top/Article/details/gt2zmhydhvp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hnxiangtu.top/Article/details/gt2fbikufeo.html

[N04] 斐波那契数列
来源：http://dali.zhongyouzk.top/Article/details/gt2gemdgmrj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gt2cacdadwl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gt2zbgthzqi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gt2kldscovi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2qlpvlivz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tssqcltg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sweek.top/Article/details/gt2jhclyxcu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gt2vmijekgo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gt2cuvisrzy.html

[N05] 最大公约数
来源：http://dali.fengsongda.top/Article/details/gt2fbanolzp.html

Py:   math.gcd(a, b)
来源：http://dali.chenlongwang.top/Article/details/gt2kxabhhzv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258888.top/Article/details/gt2ewjmbsgb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pbhfexlp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gt2pgionpkx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhoulong.xyz/Article/details/gt2qwhgfukd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.9152youxi.cn/Article/details/gt2jymahvxu.html

Ruby: a.gcd(b)
来源：http://dali.shuidangran.top/Article/details/gt2lkgfjsgn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guannengcc.top/Article/details/gt2xfdowgsk.html

[N06] 判断回文字符串
来源：http://dali.tian-w.cn/Article/details/gt2apqksmcy.html

Py:   s == s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gt2gzapkvgi.html

PHP:  $s === strrev($s);
来源：http://dali.c1oappe.top/Article/details/gt2ozahaiff.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gt2iwlcllfh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gt2odqfvxox.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xziqi.cn/Article/details/gt2yvfkmljs.html

Go:   // 双指针从两端比较
来源：http://dali.yj202588.top/Article/details/gt2rnikekyn.html

Ruby: s == s.reverse
来源：http://dali.meibo888.top/Article/details/gt2uqlqgccx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gt2skzxxmkn.html

[N07] 两数之和（返回下标）
来源：http://dali.chenjidiqi.icu/Article/details/gt2vbqraugf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jqgfzy.top/Article/details/gt2swpgwueu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.daxiang520.top/Article/details/gt2hluldmzg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nwbrower.top/Article/details/gt2lppcryjx.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangshuangyany.cn/Article/details/gt2qwnfbwwg.html

Java: // 手写 HashMap
来源：http://dali.gaohongyu789.top/Article/details/gt2bayfmren.html

Go:   // 手写 map[int]int
来源：http://dali.svipenyu.cn/Article/details/gt2sdygaabv.html

Ruby: // 手写 Hash
来源：http://dali.vqdsnc.cn/Article/details/gt2mtomnipf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnqzz.top/Article/details/gt2atlkyhpi.html

[N08] 生成全排列
来源：http://dali.guannengcc.top/Article/details/gt2qqvuiwfh.html

Py:   itertools.permutations(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2sddszdie.html

PHP:  // 手写递归交换
来源：http://dali.zhiwuduotai.top/Article/details/gt2uxwevoar.html

JS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2rewetcnt.html

TS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jhsnghfb.html

Java: // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gt2bxpujzna.html

Go:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2svjfdugf.html

Ruby: arr.permutation.to_a
来源：http://dali.jiagoushi.top/Article/details/gt2qyqzkzpd.html

C#:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gt2fiidtmnc.html

[N09] 栈与队列
来源：http://dali.fzhhl.top/Article/details/gt2jscacvtv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hfpthk.cn/Article/details/gt2zyvnxwpc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jianghu66.top/Article/details/gt2ubxirvpo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tanke756.top/Article/details/gt2dzydfmua.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jqgfzy.top/Article/details/gt2zuqwlykg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhixingplan.top/Article/details/gt2qsdlwwrf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xziqi.cn/Article/details/gt2lzkzelcz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gt2sykoaidw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yanxiufei.cn/Article/details/gt2puexhpsx.html

[N10] 链表节点定义
来源：http://dali.shzxlz.cn/Article/details/gt2ldlijdrb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hfpthk.cn/Article/details/gt2ocxczjmm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sweek.top/Article/details/gt2dhdkltbs.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shuidangran.top/Article/details/gt2ulxxvant.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dianchejie.cn/Article/details/gt2xsrlebxh.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgufenzy.top/Article/details/gt2avsaoapp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.316326.xyz/Article/details/gt2lewgaoon.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.fengsongda.top/Article/details/gt2jfdgbyen.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.kuanghao11.cn/Article/details/gt2hnskcvhk.html

[N11] 二叉树中序遍历
来源：http://dali.tian-w.cn/Article/details/gt2lajftxqj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nanxinkj.top/Article/details/gt2docjcwpq.html

PHP:  // 手写递归函数
来源：http://dali.dashuyun.cn/Article/details/gt2dqhgcmmt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yangfankeji.com/Article/details/gt2pkxsitlc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gt2tvzrjywl.html

Java: // 手写递归
来源：http://dali.iojbl.cn/Article/details/gt2qgqeeuwl.html

Go:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gt2jaerpfxw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guannengcc.top/Article/details/gt2pblfthfh.html

C#:   // 手写递归
来源：http://dali.sweek.top/Article/details/gt2ttlgmlgm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shangyingyoupin.top/Article/details/gt2fxqakadm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zycfv.cn/Article/details/gt2pohibcgm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sxryk.cn/Article/details/gt2hofibtal.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ppjwa.cn/Article/details/gt2fphduzuw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gt2ddicjusg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gt2hnoammnj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.quarkkingdee.top/Article/details/gt2wfgrfolz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jyoumei.cn/Article/details/gt2lmnasuve.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258.top/Article/details/gt2aoqulwjd.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2ccfecmez.html

O. 并发与异步
来源：http://dali.redwolf501.top/Article/details/gt2xcqzmdrf.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2kbagmkgt.html

[O01] 启动一个线程
来源：http://dali.zycfv.cn/Article/details/gt2aeleajqd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.316326.xyz/Article/details/gt2vasnyxvf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.bjfxy.top/Article/details/gt2kwphmjet.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yongpay.top/Article/details/gt2fkmucuxy.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gt2zsqrnchv.html

Java: new Thread(() -> f()).start()
来源：http://dali.gzhubu.top/Article/details/gt2nclcrsjj.html

Go:   go f()
来源：http://dali.hnxiangtu.top/Article/details/gt2mzrwugrh.html

Ruby: Thread.new { f }
来源：http://dali.jinqigufen.top/Article/details/gt2mveitdfv.html

C#:   Task.Run(() => F());
来源：http://dali.tianlin.xyz/Article/details/gt2dyyrgqmx.html

[O02] 使用线程池
来源：http://dali.zhixingplan.top/Article/details/gt2ujphnpft.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shuidangran.top/Article/details/gt2hyikysen.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nanxuanxn.top/Article/details/gt2feflfjdl.html

JS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gt2mrlbjlbf.html

TS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gt2echypdqn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yonumen.top/Article/details/gt2xnlizsye.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.pycfn.com/Article/details/gt2bswmaubg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ehwqpu.com/Article/details/gt2mewubcqi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nwbrower.top/Article/details/gt2dhpkcdry.html

[O03] 加锁保护共享数据
来源：http://dali.xylfe.cn/Article/details/gt2bjjdrhwu.html

Py:   with lock: shared += 1
来源：http://dali.sysykeji.top/Article/details/gt2ghknszlf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangdashe.top/Article/details/gt2qzpudygq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hysaishi.cn/Article/details/gt2augphgbs.html

TS:   // 同 JS
来源：http://dali.mhx1999.top/Article/details/gt2uqbiwovi.html

Java: synchronized (this) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gt2kzdmzrhl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cashguo.top/Article/details/gt2vpryfbep.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jtncatcd.html

C#:   lock (gate) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gt2rlypvgws.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjaxogs.html

Py:   async def f():⏎    await g()
来源：http://dali.ydzc1.top/Article/details/gt2aqsnqhrt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.0kj1m.cn/Article/details/gt2aptrkync.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2bpsgcirn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vufenjuj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zwbeufcg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hysaishi.cn/Article/details/gt2agkztosw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.redwolf501.top/Article/details/gt2ebfqmzvb.html

C#:   async Task F() { await G(); }
来源：http://dali.guowangkeji.top/Article/details/gt2wojoaqua.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenzaomai.com/Article/details/gt2wsdtlcrp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenzaomai.com/Article/details/gt2nfvmstan.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.snrcjt.cn/Article/details/gt2xmdnpuuh.html

JS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gt2isppzzrw.html

TS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gt2iusqzxof.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.mhx1999.top/Article/details/gt2yrrflyhz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.haohaochexian.top/Article/details/gt2jichkzno.html

Ruby: threads.map(&:join)
来源：http://dali.0kj1m.cn/Article/details/gt2ozfajopn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2juontupy.html

[O06] 使用进程池
来源：http://dali.zdqjudy.top/Article/details/gt2tindksda.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.meibo888.top/Article/details/gt2bemqbefy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.smart0.xyz/Article/details/gt2psaqazmk.html

JS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gt2mjzmhdev.html

TS:   // child_process / cluster 模块
来源：http://dali.yj202588.top/Article/details/gt2xbjrycaw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shuidangran.top/Article/details/gt2eyawgwwg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hysaishi.cn/Article/details/gt2btxrigao.html

Ruby: // fork 块
来源：http://dali.smart0.xyz/Article/details/gt2etrrybqr.html

C#:   Parallel.For
来源：http://dali.zhoulong.xyz/Article/details/gt2abuwgcxt.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2ucoigznx.html

P. 常用工具函数
来源：http://dali.316326.xyz/Article/details/gt2pvdleqqo.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2urxbdppf.html

[P01] 生成 UUID
来源：http://dali.andypj.xyz/Article/details/gt2lsfuroun.html

Py:   str(uuid.uuid4())
来源：http://dali.daria6918.cn/Article/details/gt2whnoiyum.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.pengpengdd.cyou/Article/details/gt2qbvkvfzs.html

JS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gt2xkrjlksx.html

TS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gt2lfbyiykp.html

Java: UUID.randomUUID().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gt2nfzngayq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yonumen.top/Article/details/gt2bbhnqost.html

Ruby: SecureRandom.uuid
来源：http://dali.chenjidiqi.icu/Article/details/gt2yxoslxhe.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yangfankeji.com/Article/details/gt2rhnkksfr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pycfn.com/Article/details/gt2wdbwkogr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.0kj1m.cn/Article/details/gt2eyscfydn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tian-w.cn/Article/details/gt2tghzahkc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenjidiqi.icu/Article/details/gt2ivhbadyf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gogol.net.cn/Article/details/gt2atliqtsk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qhfwyacx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2luawkpcy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ppjwa.cn/Article/details/gt2jsfuojjm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jyoumei.cn/Article/details/gt2jznsdjak.html

[P03] 生成短随机字符串
来源：http://dali.yj202588.top/Article/details/gt2ycmcjlyo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxinkj.top/Article/details/gt2ethejged.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhixingplan.top/Article/details/gt2zbspdtwt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gt2empdvfns.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ppjwa.cn/Article/details/gt2crazruvq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.meibo888.top/Article/details/gt2tcdvzgvj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenjidiqi.icu/Article/details/gt2ququarco.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mdjbnsnl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nanxuanxn.top/Article/details/gt2awsuzhhs.html

[P04] 求长度
来源：http://dali.birdmap.top/Article/details/gt2khjyndpp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.fzhhl.top/Article/details/gt2ujfksswo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2qylmmajq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nwbrower.top/Article/details/gt2etfozgjv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.snrcjt.cn/Article/details/gt2kenvdfhx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yvedp.cn/Article/details/gt2urvekqpk.html

Go:   len(arr);  len(m)
来源：http://dali.zdqjudy.top/Article/details/gt2oynkdwch.html

Ruby: x.length;  x.size
来源：http://dali.gogol.net.cn/Article/details/gt2disxztsm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.bjfxy.top/Article/details/gt2rwszajwm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.smart0.xyz/Article/details/gt2nuempmjd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yangfankeji.com/Article/details/gt2zptcesoo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daria6918.cn/Article/details/gt2sbolgkch.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wuqopnbz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yongpay.top/Article/details/gt2tmrlutqf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cheryme.top/Article/details/gt2xnrgdlvq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2effohtxr.html

Ruby: a == b
来源：http://dali.sweek.top/Article/details/gt2cefrizdv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.c1oappe.top/Article/details/gt2uwsanayt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhiwuduotai.top/Article/details/gt2byvmsznd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbqnyhq.html

PHP:  if (empty($x)) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2tvhesauw.html


<!-- 参考信息 -->