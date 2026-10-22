代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gt2xfrkhfpd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gt2hcgemjeh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xinyue.icu/Article/details/gt2esdurppm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jyoumei.cn/Article/details/gt2zuhpfwpb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.bjfxy.top/Article/details/gt2hsptylri.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.andypj.xyz/Article/details/gt2rbfnctax.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2gblwpvmb.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangshuangyany.cn/Article/details/gt2puumkwua.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2dixexbtq.html

[M01] 读取命令行参数
来源：http://dali.snrcjt.cn/Article/details/gt2ogrqspqm.html

Py:   sys.argv[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2itnyixua.html

PHP:  $argv;  $argc;
来源：http://dali.c1oappe.top/Article/details/gt2elhrzbgh.html

JS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gt2bdbezaix.html

TS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gt2dnipyrcj.html

Java: args 数组（main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gt2frllyrlb.html

Go:   os.Args[1:]
来源：http://dali.0kj1m.cn/Article/details/gt2gsjfhhes.html

Ruby: ARGV
来源：http://dali.guannengcc.top/Article/details/gt2ddznftvi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gt2ildvsxbc.html

[M02] 读取环境变量
来源：http://dali.nanxuanxn.top/Article/details/gt2bboiwnio.html

Py:   os.environ.get("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2gooswstk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gt2xkdjuajk.html

JS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gt2qikwthpf.html

TS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gt2cdaeatkc.html

Java: System.getenv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gt2ysjlwqvg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gt2pjmmmkxu.html

Ruby: ENV["HOME"]
来源：http://dali.hongshengwenyu.top/Article/details/gt2qmotbmuy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yueranfly.top/Article/details/gt2uhhmbhpi.html

[M03] 执行外部命令
来源：http://dali.feifeiyinyue.top/Article/details/gt2nebplzxp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hammf.cn/Article/details/gt2sjsclznq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.birdmap.top/Article/details/gt2wpswsati.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gt2kttqfiyw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gt2uzzhjmpw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fxorlrdb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jlsjyb.cn/Article/details/gt2jlhlyvlp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wkuljfwu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.redwolf501.top/Article/details/gt2ppphidgk.html

[M04] 获取当前工作目录
来源：http://dali.birdmap.top/Article/details/gt2lmntxwju.html

Py:   os.getcwd()
来源：http://dali.zhengqikj.top/Article/details/gt2fyytezhb.html

PHP:  getcwd();
来源：http://dali.tianlin.xyz/Article/details/gt2siskyyep.html

JS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gt2zxoekcgr.html

TS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gt2kubqxhtv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aizwys.cn/Article/details/gt2xmiwxnqk.html

Go:   os.Getwd()
来源：http://dali.gotoacloud.top/Article/details/gt2izolbhkn.html

Ruby: Dir.pwd
来源：http://dali.shuidangran.top/Article/details/gt2kgpwdgdz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gt2kxgiyxok.html

[M05] 设置退出码
来源：http://dali.nwbrower.top/Article/details/gt2mrrxkzgf.html

Py:   sys.exit(1)
来源：http://dali.ybcxt.top/Article/details/gt2teqspbrw.html

PHP:  exit(1);
来源：http://dali.wangdashe.top/Article/details/gt2zgmlggtk.html

JS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2vdctiyey.html

TS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2yzscfbny.html

Java: System.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tieahqfn.html

Go:   os.Exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2uycoytjg.html

Ruby: exit 1
来源：http://dali.fengsongda.top/Article/details/gt2wanahiyo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.snrcjt.cn/Article/details/gt2vccxpivr.html

[M06] 向标准错误输出
来源：http://dali.9152youxi.cn/Article/details/gt2brqjaofx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pycfn.com/Article/details/gt2urissawc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pengpengdd.cyou/Article/details/gt2wtvznlmp.html

JS:   console.error("err")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dvnoqhvm.html

TS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qjrddsck.html

Java: System.err.println("err")
来源：http://dali.xziqi.cn/Article/details/gt2uvsabuuc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yangfankeji.com/Article/details/gt2fzlzztfp.html

Ruby: warn "err"
来源：http://dali.dashuyun.cn/Article/details/gt2xrfuninl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zdxfxufh.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2roydjdpx.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxinkj.top/Article/details/gt2vcuwvtoj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.0kj1m.cn/Article/details/gt2llvoczmb.html

JS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gt2etlxexya.html

TS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gt2xteimxir.html

Java: public static void main(String[] args)
来源：http://dali.gaohongyu789.top/Article/details/gt2eqbclmpf.html

Go:   func main()
来源：http://dali.feifeiyinyue.top/Article/details/gt2otqfioyv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangshuangyany.cn/Article/details/gt2vmgaztvp.html

C#:   static void Main(string[] args)
来源：http://dali.316326.xyz/Article/details/gt2dpinrqba.html

[M08] 获取系统与运行时信息
来源：http://dali.yueranfly.top/Article/details/gt2mqlpqxmk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhongyouzk.top/Article/details/gt2xjgduajr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hongshengwenyu.top/Article/details/gt2ghxonxaw.html

JS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gt2osomanvr.html

TS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gt2fkgmvasn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ppjwa.cn/Article/details/gt2gjcnrsws.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.wangdashe.top/Article/details/gt2tzeumnyg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhengqikj.top/Article/details/gt2kbbskaal.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gaohongyu789.top/Article/details/gt2fxffuyow.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2ujxkljkd.html

N. 数据结构与算法
来源：http://dali.yuxming.cn/Article/details/gt2ongedxny.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2nlpzcauw.html

[N01] 二分查找（有序数组）
来源：http://dali.sysykeji.top/Article/details/gt2jhwjosfa.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qzzayydd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gt2pxyisqqs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gt2hlfpnndp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gt2uynhyqsr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2tikajcmk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2cnlsfkdc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cdnleiting.top/Article/details/gt2kjpbdqms.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2zbezfenf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnxiangtu.top/Article/details/gt2mfwgxlnj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gt2xbljelbg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.snrcjt.cn/Article/details/gt2nzglqyyw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gt2ghsxkgvp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gt2itnqyjfa.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.quarkkingdee.top/Article/details/gt2fvrezqsj.html

Go:   slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gt2jnhnqdxd.html

Ruby: arr.sort
来源：http://dali.shzxlz.cn/Article/details/gt2hxgfatnf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangdashe.top/Article/details/gt2tiqsywes.html

[N03] 快速排序（分治示例）
来源：http://dali.jqgfzy.top/Article/details/gt2shoimajq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.birdmap.top/Article/details/gt2sqapited.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinqigfzy.top/Article/details/gt2glqruhnq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gaohongyu789.top/Article/details/gt2qxlvdkyo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gt2vbiwhguf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hfpthk.cn/Article/details/gt2bwkyzxvs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.birdmap.top/Article/details/gt2fchfvtnw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guannengcc.top/Article/details/gt2virsowju.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj202588.top/Article/details/gt2yiziciij.html

[N04] 斐波那契数列
来源：http://dali.zhongyouzk.top/Article/details/gt2rvgrpdih.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gt2pwxbgctu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gt2smcifyoq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2kzfaecmz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gt2sjwbnrdy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gt2mrkphtub.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yongpay.top/Article/details/gt2sdmmttez.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gt2hlclmesc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gt2ygdykwib.html

[N05] 最大公约数
来源：http://dali.havefunace.top/Article/details/gt2eefzrblp.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gt2wjbfnszy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgufenzy.top/Article/details/gt2tottnzeh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gt2xrykbdxe.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gt2bbepvouj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxinkj.top/Article/details/gt2fiwlgnhh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cnyuowbr.html

Ruby: a.gcd(b)
来源：http://dali.chenlongwang.top/Article/details/gt2nmiilpdk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sufxvd.cn/Article/details/gt2kpqmzzcj.html

[N06] 判断回文字符串
来源：http://dali.gzhubu.top/Article/details/gt2kbxhmzfg.html

Py:   s == s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gt2vonniial.html

PHP:  $s === strrev($s);
来源：http://dali.smart0.xyz/Article/details/gt2peisnsba.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gt2yifjeyio.html

TS:   s === [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gt2znccmymi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cashguo.top/Article/details/gt2pkrabxni.html

Go:   // 双指针从两端比较
来源：http://dali.hnqzz.top/Article/details/gt2weirwpdm.html

Ruby: s == s.reverse
来源：http://dali.xinyue.icu/Article/details/gt2okrvflkb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gt2ywaruozu.html

[N07] 两数之和（返回下标）
来源：http://dali.yangfankeji.com/Article/details/gt2phdgypkm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daria6918.cn/Article/details/gt2dzzdpmtj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ybcxt.top/Article/details/gt2njheqyot.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuanzhike.top/Article/details/gt2xyxzldgt.html

TS:   // 手写 Map<string, number>
来源：http://dali.tanke756.top/Article/details/gt2pjcchkjr.html

Java: // 手写 HashMap
来源：http://dali.meibo888.top/Article/details/gt2zxwyvrua.html

Go:   // 手写 map[int]int
来源：http://dali.iojbl.cn/Article/details/gt2linvvgjx.html

Ruby: // 手写 Hash
来源：http://dali.cheryme.top/Article/details/gt2qyjvlsvv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj20258888.top/Article/details/gt2ygzmjjri.html

[N08] 生成全排列
来源：http://dali.xinyue.icu/Article/details/gt2awrvmqyr.html

Py:   itertools.permutations(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2uxdfuyib.html

PHP:  // 手写递归交换
来源：http://dali.ppjwa.cn/Article/details/gt2uycgipaf.html

JS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gt2ghzogcpf.html

TS:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gt2bgooetkm.html

Java: // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gt2ayyvprqt.html

Go:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gt2eaagmpup.html

Ruby: arr.permutation.to_a
来源：http://dali.xuetiantiany.cn/Article/details/gt2chusrhnv.html

C#:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gt2uhuuojby.html

[N09] 栈与队列
来源：http://dali.guannengcc.top/Article/details/gt2xotwduui.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258.top/Article/details/gt2akdqmktm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.fengsongda.top/Article/details/gt2rvspwgao.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gt2hbdkwfuc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.316326.xyz/Article/details/gt2qfovidql.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.smart0.xyz/Article/details/gt2lwmnpdby.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hyeyykew.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.c1oappe.top/Article/details/gt2vusoixlz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xinyue.icu/Article/details/gt2ejalwdmc.html

[N10] 链表节点定义
来源：http://dali.jqgfzy.top/Article/details/gt2oijpjnwf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuetiantiany.cn/Article/details/gt2lzxhhgoz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yangfankeji.com/Article/details/gt2dlwbvkdg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ndgwjjtp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxinkj.top/Article/details/gt2sgikjusj.html

Java: class Node { int v; Node next; }
来源：http://dali.zhengqikj.top/Article/details/gt2lymhxgeu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tian-w.cn/Article/details/gt2cmichpng.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhongyouzk.top/Article/details/gt2wxfbzfsn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gaohongyu789.top/Article/details/gt2gmfpmhod.html

[N11] 二叉树中序遍历
来源：http://dali.ppjwa.cn/Article/details/gt2czrypdfs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.c1oappe.top/Article/details/gt2zlgrgveh.html

PHP:  // 手写递归函数
来源：http://dali.yvedp.cn/Article/details/gt2bvvjosqg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gt2zgxkeuap.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenzaomai.com/Article/details/gt2iuvxwoey.html

Java: // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gt2mithxalb.html

Go:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gt2yiuafyeu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gogol.net.cn/Article/details/gt2mebdaxtw.html

C#:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gt2igfbtdgd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenjidiqi.icu/Article/details/gt2zydzbqxj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.quarkkingdee.top/Article/details/gt2kpwkmwri.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.dashuyun.cn/Article/details/gt2wzzantjb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gt2zpzbsfyi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gt2zhargpcw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gt2jiazdwvo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sufxvd.cn/Article/details/gt2bajsqitp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.aibaodan.cn/Article/details/gt2cpeehgkv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.smart0.xyz/Article/details/gt2sigilvkk.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2mudnhfwq.html

O. 并发与异步
来源：http://dali.mhx1999.top/Article/details/gt2duwduduo.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2peiotcie.html

[O01] 启动一个线程
来源：http://dali.hysaishi.cn/Article/details/gt2ytzvhqft.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tanke756.top/Article/details/gt2rlrmjtfp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.316326.xyz/Article/details/gt2hpgauxza.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yvedp.cn/Article/details/gt2ncmmcfck.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gt2qstenovy.html

Java: new Thread(() -> f()).start()
来源：http://dali.yonumen.top/Article/details/gt2jqrdwqqb.html

Go:   go f()
来源：http://dali.ivvv.top/Article/details/gt2aborqlsa.html

Ruby: Thread.new { f }
来源：http://dali.cqqwz.cn/Article/details/gt2ckpuaufw.html

C#:   Task.Run(() => F());
来源：http://dali.shzxlz.cn/Article/details/gt2usqctmwr.html

[O02] 使用线程池
来源：http://dali.nanxuanxn.top/Article/details/gt2qocncgwg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gt2pgfinqjo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2naiineex.html

JS:   // worker_threads 线程池
来源：http://dali.redwolf501.top/Article/details/gt2fthyemop.html

TS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gt2aleueaui.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yangfankeji.com/Article/details/gt2ehtzbmrc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ydzc1.top/Article/details/gt2quoewybd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cashguo.top/Article/details/gt2eskvcpsq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cdnleiting.top/Article/details/gt2cbysecrn.html

[O03] 加锁保护共享数据
来源：http://dali.zhoulong.xyz/Article/details/gt2vzffxgvj.html

Py:   with lock: shared += 1
来源：http://dali.sysykeji.top/Article/details/gt2xmbmfeec.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnxiangtu.top/Article/details/gt2jrjuwuqp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.haohaochexian.top/Article/details/gt2rtmoersz.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gt2lwytsbil.html

Java: synchronized (this) { shared++; }
来源：http://dali.cqqwz.cn/Article/details/gt2welgxzqp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hywenlv.cn/Article/details/gt2gcdobqod.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vkwygrih.html

C#:   lock (gate) { shared++; }
来源：http://dali.9152youxi.cn/Article/details/gt2ufugnsty.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258888.top/Article/details/gt2tsmgprhf.html

Py:   async def f():⏎    await g()
来源：http://dali.zhengqikj.top/Article/details/gt2qrmpjtku.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yanxiufei.cn/Article/details/gt2udfobmba.html

JS:   async function f() { await g(); }
来源：http://dali.tian-w.cn/Article/details/gt2qydhnxyv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.guannengcc.top/Article/details/gt2layeyjhh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigufen.top/Article/details/gt2irrhntkg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cashguo.top/Article/details/gt2grdvhowm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.316326.xyz/Article/details/gt2laxxpnpp.html

C#:   async Task F() { await G(); }
来源：http://dali.smart0.xyz/Article/details/gt2rixuutwg.html

[O05] 并发执行并等待全部完成
来源：http://dali.ydzc1.top/Article/details/gt2ehpddurz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hywenlv.cn/Article/details/gt2nmvrdxrb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhoulong.xyz/Article/details/gt2psshdofd.html

JS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gt2aukzdndw.html

TS:   await Promise.all(tasks)
来源：http://dali.gogol.net.cn/Article/details/gt2rhamdjcs.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yueranfly.top/Article/details/gt2pijmgxjk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.haohaochexian.top/Article/details/gt2tzsarzlq.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvdmeew.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhixingplan.top/Article/details/gt2nqnhgnui.html

[O06] 使用进程池
来源：http://dali.mhx1999.top/Article/details/gt2fdnzlomi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tianlin.xyz/Article/details/gt2plelsret.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.c1oappe.top/Article/details/gt2wjsixaks.html

JS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gt2umpdhzla.html

TS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gt2uycyxnqb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.dashuyun.cn/Article/details/gt2lilpdodg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hongshengwenyu.top/Article/details/gt2ibbevwal.html

Ruby: // fork 块
来源：http://dali.fengsongda.top/Article/details/gt2qjgjbwcl.html

C#:   Parallel.For
来源：http://dali.ivvv.top/Article/details/gt2zehetbta.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2dbsqsced.html

P. 常用工具函数
来源：http://dali.xziqi.cn/Article/details/gt2qalagqih.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2psijqjlq.html

[P01] 生成 UUID
来源：http://dali.yonumen.top/Article/details/gt2axabdjeq.html

Py:   str(uuid.uuid4())
来源：http://dali.fengsongda.top/Article/details/gt2mzmoyfby.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gt2gemrqowg.html

JS:   crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gt2bqvhxhuq.html

TS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gt2zhgpijhk.html

Java: UUID.randomUUID().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ceywuwys.html

Go:   // 用 github.com/google/uuid
来源：http://dali.bjfxy.top/Article/details/gt2mzkrzlbh.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258.top/Article/details/gt2aomozbtc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.quarkkingdee.top/Article/details/gt2oobmntua.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cashguo.top/Article/details/gt2jakkksyr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ydzc1.top/Article/details/gt2hzrrkork.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xylfe.cn/Article/details/gt2rtmtbsti.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhengqikj.top/Article/details/gt2ebsqchwc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sweek.top/Article/details/gt2rscyebuw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lrqbrude.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yongpay.top/Article/details/gt2nuneqdcl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgfzy.top/Article/details/gt2pnhrczmh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ztvftkem.html

[P03] 生成短随机字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2bhuxafyj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258888.top/Article/details/gt2qdqcrctg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daxiang520.top/Article/details/gt2joeshyav.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xylfe.cn/Article/details/gt2zcsqykds.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gt2zhopfdrn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2hfqimori.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tian-w.cn/Article/details/gt2uljgqgir.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.316326.xyz/Article/details/gt2gubdtqlp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jyoumei.cn/Article/details/gt2fjhoolpf.html

[P04] 求长度
来源：http://dali.iojbl.cn/Article/details/gt2ftctcase.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.havefunace.top/Article/details/gt2tgvmrvwj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gt2ezrnrmtf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.vqdsnc.cn/Article/details/gt2bcyulddi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yueranfly.top/Article/details/gt2osuolidq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gt2tqihtssa.html

Go:   len(arr);  len(m)
来源：http://dali.fzhhl.top/Article/details/gt2hdkkcraj.html

Ruby: x.length;  x.size
来源：http://dali.birdmap.top/Article/details/gt2fdbexdfc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jqgfzy.top/Article/details/gt2itmgxjdp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yanxiufei.cn/Article/details/gt2ywibcctt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhengqikj.top/Article/details/gt2iyhnjjwj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dgaqwdoh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tian-w.cn/Article/details/gt2sxnivxnj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cdnleiting.top/Article/details/gt2kdbaortz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.vqdsnc.cn/Article/details/gt2txwgbqsj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhixingplan.top/Article/details/gt2fcahdmhz.html

Ruby: a == b
来源：http://dali.redwolf501.top/Article/details/gt2hosdakxg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xuanzx.com/Article/details/gt2sxxfiiew.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yueranfly.top/Article/details/gt2omrfrynp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxuanxn.top/Article/details/gt2ijtjdtoa.html

PHP:  if (empty($x)) {}
来源：http://dali.smart0.xyz/Article/details/gt2dpxqudey.html


<!-- 参考信息 -->