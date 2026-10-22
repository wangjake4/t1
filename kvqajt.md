代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.sweek.top/Article/details/gtpoyzkhiv.html

[L08] 并发请求多个地址
来源：http://dali.mhx1999.top/Article/details/gtcniqhqep.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.feifeiyinyue.top/Article/details/gtksyaherl.html

PHP:  curl_multi_init() 系列
来源：http://dali.dashuyun.cn/Article/details/gtxknvlxtg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwdclrsa.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtjthfhtmy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gtvbiwzkya.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yanxiufei.cn/Article/details/gtluznactl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hysaishi.cn/Article/details/gtgdskfsyv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yvedp.cn/Article/details/gtakbyvckf.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtnibanqfp.html

M. 命令行 / 进程 / 环境
来源：http://dali.sysykeji.top/Article/details/gtukhedyho.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkftfdbt.html

[M01] 读取命令行参数
来源：http://dali.xinyue.icu/Article/details/gtgahzdcqt.html

Py:   sys.argv[1:]
来源：http://dali.yuxming.cn/Article/details/gtcqmvclnr.html

PHP:  $argv;  $argc;
来源：http://dali.ydzc1.top/Article/details/gtxhwthozv.html

JS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtjdpkdfly.html

TS:   process.argv.slice(2)
来源：http://dali.yueranfly.top/Article/details/gtghlefsfm.html

Java: args 数组（main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gtgqznigdo.html

Go:   os.Args[1:]
来源：http://dali.yj20258.top/Article/details/gtgcvvhtra.html

Ruby: ARGV
来源：http://dali.hnxiangtu.top/Article/details/gtttdlkayu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gtrwxtzfvj.html

[M02] 读取环境变量
来源：http://dali.cashguo.top/Article/details/gtubzsbltk.html

Py:   os.environ.get("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtypffjcsa.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gtghwzryun.html

JS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gtfwsdsein.html

TS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gtqcpsncpf.html

Java: System.getenv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtqwdtewcz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtprzbgwep.html

Ruby: ENV["HOME"]
来源：http://dali.kuanghao11.cn/Article/details/gteouslvzn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fengsongda.top/Article/details/gttawdzvyt.html

[M03] 执行外部命令
来源：http://dali.gogol.net.cn/Article/details/gtkvkrkjjo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fzhhl.top/Article/details/gtghcefajm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guannengcc.top/Article/details/gtgzfrroku.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigufen.top/Article/details/gtchknfmdy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgrnfvehs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gogol.net.cn/Article/details/gtgdewevvf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yonumen.top/Article/details/gtlfrywhbn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hfpthk.cn/Article/details/gttzbupdeq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.kuanghao11.cn/Article/details/gtlcrhyhxi.html

[M04] 获取当前工作目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgwrbzlr.html

Py:   os.getcwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtkjtagmea.html

PHP:  getcwd();
来源：http://dali.gogol.net.cn/Article/details/gthilitvep.html

JS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gtdmqhvyax.html

TS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gttkrxgsvm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yonumen.top/Article/details/gtmzbonrsc.html

Go:   os.Getwd()
来源：http://dali.fzhhl.top/Article/details/gtntjnysre.html

Ruby: Dir.pwd
来源：http://dali.jinqigufen.top/Article/details/gtijdzbwez.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuanzx.com/Article/details/gtgjpyhdvc.html

[M05] 设置退出码
来源：http://dali.hammf.cn/Article/details/gtgneomgke.html

Py:   sys.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtfbekqwex.html

PHP:  exit(1);
来源：http://dali.xuetiantiany.cn/Article/details/gttipxdqjk.html

JS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtzyizhive.html

TS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtdtqevjtq.html

Java: System.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtguhmrlpz.html

Go:   os.Exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtbjirdeuj.html

Ruby: exit 1
来源：http://dali.ppjwa.cn/Article/details/gtxlesaycl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hammf.cn/Article/details/gtruerrfbf.html

[M06] 向标准错误输出
来源：http://dali.svipenyu.cn/Article/details/gtxbchgofu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xylfe.cn/Article/details/gtlulsddxk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gtzygqchkf.html

JS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gtaininxqx.html

TS:   console.error("err")
来源：http://dali.smart0.xyz/Article/details/gtpehsfmrf.html

Java: System.err.println("err")
来源：http://dali.yueranfly.top/Article/details/gtbgupstoa.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.c1oappe.top/Article/details/gtjozwumwh.html

Ruby: warn "err"
来源：http://dali.daria6918.cn/Article/details/gtqmnbvjlv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jyoumei.cn/Article/details/gtcwwiycca.html

[M07] 判断是否为主入口
来源：http://dali.sysykeji.top/Article/details/gteqihooqz.html

Py:   if __name__ == "__main__":
来源：http://dali.smart0.xyz/Article/details/gtugngrarh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuanzhike.top/Article/details/gtnytzeeto.html

JS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gtandnxcnc.html

TS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gteuzfsclp.html

Java: public static void main(String[] args)
来源：http://dali.haohaochexian.top/Article/details/gtdqgugybv.html

Go:   func main()
来源：http://dali.jiagoushi.top/Article/details/gtliabzocv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.0kj1m.cn/Article/details/gtrbjhrmmc.html

C#:   static void Main(string[] args)
来源：http://dali.iojbl.cn/Article/details/gtodydlvhc.html

[M08] 获取系统与运行时信息
来源：http://dali.sysykeji.top/Article/details/gtvcntgckh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yanxiufei.cn/Article/details/gtgxrkkejn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hfpthk.cn/Article/details/gtwwcdqpnk.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gtgudegnvp.html

TS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtrpjabtpz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhiwuduotai.top/Article/details/gtmpbgutcv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gtyrrzicsh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.dianchejie.cn/Article/details/gtuytfpsit.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenjidiqi.icu/Article/details/gtfvzdysha.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxbkvgcc.html

N. 数据结构与算法
来源：http://dali.xuanzx.com/Article/details/gteexmgqvz.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtievrzkll.html

[N01] 二分查找（有序数组）
来源：http://dali.zhengqikj.top/Article/details/gtwnsjumfy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtmgibczgv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gtjrikqbzb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gtcxcggdtk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdyxhcmwf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtwxlkpyqd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtejthvpii.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jianghu66.top/Article/details/gtlujqsxay.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtuxzivimu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sweek.top/Article/details/gtplmldpwm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gtkzsbzrum.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shuidangran.top/Article/details/gtddgnkfjp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gtyvrlriwy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqecuogba.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sweek.top/Article/details/gtkrlgltha.html

Go:   slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtwgcggpsj.html

Ruby: arr.sort
来源：http://dali.316326.xyz/Article/details/gtlsbnnnxv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yvedp.cn/Article/details/gtlqohmmfh.html

[N03] 快速排序（分治示例）
来源：http://dali.xuanzx.com/Article/details/gttjopuuho.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xinyue.icu/Article/details/gthrurqref.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cashguo.top/Article/details/gtecyiqnqh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gtejxhqxxf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gtitbsdjks.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuxming.cn/Article/details/gtgrlfpnlx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shuidangran.top/Article/details/gtvqxgbbwt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jiagoushi.top/Article/details/gtryxxxxju.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.pengpengdd.cyou/Article/details/gtpxqfawgs.html

[N04] 斐波那契数列
来源：http://dali.jianghu66.top/Article/details/gtlnwjqsid.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gtccnaanun.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gtryhfgpyr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gttpvtbjtr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gtiyxckany.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gthrqwcwpc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ppjwa.cn/Article/details/gtvcsqetmq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtbrbelerw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gtavljwmbq.html

[N05] 最大公约数
来源：http://dali.jqgufenzy.top/Article/details/gteoihybgq.html

Py:   math.gcd(a, b)
来源：http://dali.bjfxy.top/Article/details/gtnlrupfei.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tanke756.top/Article/details/gtxhmwpdgz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gtuvxdadjm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gtttmurufh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sweek.top/Article/details/gthbtsxedr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guannengcc.top/Article/details/gthmhgfpwo.html

Ruby: a.gcd(b)
来源：http://dali.jyoumei.cn/Article/details/gtgvnmnmmr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hfpthk.cn/Article/details/gtrfxquktp.html

[N06] 判断回文字符串
来源：http://dali.yuanzhike.top/Article/details/gtywgkszwq.html

Py:   s == s[::-1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrysuime.html

PHP:  $s === strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gtcqvetvrh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtqanwwxhw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtisntbslq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yueranfly.top/Article/details/gtuxawujto.html

Go:   // 双指针从两端比较
来源：http://dali.ppjwa.cn/Article/details/gtukmyrzrc.html

Ruby: s == s.reverse
来源：http://dali.bjfxy.top/Article/details/gtetmbiuly.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gtqrtuztry.html

[N07] 两数之和（返回下标）
来源：http://dali.cqqwz.cn/Article/details/gtzuyqvoxf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cqqwz.cn/Article/details/gttwkbcplc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxrfmwwm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhixingplan.top/Article/details/gtqaczbfpj.html

TS:   // 手写 Map<string, number>
来源：http://dali.sufxvd.cn/Article/details/gtimpvdlel.html

Java: // 手写 HashMap
来源：http://dali.wangshuangyany.cn/Article/details/gthjapykyg.html

Go:   // 手写 map[int]int
来源：http://dali.wangdashe.top/Article/details/gtagrpoitj.html

Ruby: // 手写 Hash
来源：http://dali.fzhhl.top/Article/details/gtqryneixc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hysaishi.cn/Article/details/gtujswhepu.html

[N08] 生成全排列
来源：http://dali.hnxiangtu.top/Article/details/gtzilipttx.html

Py:   itertools.permutations(arr)
来源：http://dali.hnqzz.top/Article/details/gtvjqkbuhw.html

PHP:  // 手写递归交换
来源：http://dali.sufxvd.cn/Article/details/gtshtuhwpf.html

JS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtygudloqh.html

TS:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtzyjigwnc.html

Java: // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtnidolovu.html

Go:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtliiwsqup.html

Ruby: arr.permutation.to_a
来源：http://dali.jyoumei.cn/Article/details/gtykvjbsej.html

C#:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtqfjpzbxp.html

[N09] 栈与队列
来源：http://dali.ehwqpu.com/Article/details/gtmmsfwgnw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zdqjudy.top/Article/details/gtmoaqdglc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gttvcklcra.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gthuweyqhy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sxryk.cn/Article/details/gtlmqnccyk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcezwgkvl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.dianchejie.cn/Article/details/gtlkobsxaf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtvnohynzo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gtylhoufwp.html

[N10] 链表节点定义
来源：http://dali.hywenlv.cn/Article/details/gtdkmxzaew.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pengpengdd.cyou/Article/details/gtrwazfsng.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jyoumei.cn/Article/details/gtontmivgi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenjidiqi.icu/Article/details/gthbklfuls.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hammf.cn/Article/details/gtnhkcomkh.html

Java: class Node { int v; Node next; }
来源：http://dali.nanxinkj.top/Article/details/gticbagwbg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xylfe.cn/Article/details/gtagythagr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pycfn.com/Article/details/gtzmdajexx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xuetiantiany.cn/Article/details/gtojdyslhu.html

[N11] 二叉树中序遍历
来源：http://dali.gaohongyu789.top/Article/details/gtbsnkexye.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ivvv.top/Article/details/gtcpuqcxuo.html

PHP:  // 手写递归函数
来源：http://dali.redwolf501.top/Article/details/gtfcljxltp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ehwqpu.com/Article/details/gtrrebrfpp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gtsfjwblhq.html

Java: // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gtsfysoelh.html

Go:   // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtyeqzympz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuanzhike.top/Article/details/gtkkihrjup.html

C#:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gtaoukgapo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ydzc1.top/Article/details/gtzvafvjmp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yongpay.top/Article/details/gtggrufiue.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhongyouzk.top/Article/details/gtvsfynheo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gtvzogokdg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gtjnrtdlax.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gtdjfxeven.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dianchejie.cn/Article/details/gtfrmgshxm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtowtpxdnf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gtikphasdh.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtjpaspmdl.html

O. 并发与异步
来源：http://dali.wangdashe.top/Article/details/gtleblxicr.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtggcrvoyn.html

[O01] 启动一个线程
来源：http://dali.chenjidiqi.icu/Article/details/gtjixugrhl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aizwys.cn/Article/details/gtbvwwkhiy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnqzz.top/Article/details/gtksrtpcom.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhiwuduotai.top/Article/details/gtuqmalpth.html

TS:   // 同 JS
来源：http://dali.yanxiufei.cn/Article/details/gttbgqfkwm.html

Java: new Thread(() -> f()).start()
来源：http://dali.c1oappe.top/Article/details/gteqyfjxmm.html

Go:   go f()
来源：http://dali.jianghu66.top/Article/details/gtldqfhgiw.html

Ruby: Thread.new { f }
来源：http://dali.ppjwa.cn/Article/details/gtuaauzvuj.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigufen.top/Article/details/gtmzwtmacc.html

[O02] 使用线程池
来源：http://dali.jianghu66.top/Article/details/gthjcnumvb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yonumen.top/Article/details/gtigdaeidp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yuxming.cn/Article/details/gtyjrwxhyn.html

JS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gtrfrurees.html

TS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtaupgpfxg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ybcxt.top/Article/details/gtkqrywomi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cdnleiting.top/Article/details/gtjkpgoznp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yongpay.top/Article/details/gtetijalrq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.aizwys.cn/Article/details/gtvstglmnz.html

[O03] 加锁保护共享数据
来源：http://dali.haohaochexian.top/Article/details/gtdmhcnlpk.html

Py:   with lock: shared += 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgcajdqj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangdashe.top/Article/details/gtmkqexbsv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tian-w.cn/Article/details/gtrfmbhcrw.html

TS:   // 同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gtxnufpbvr.html

Java: synchronized (this) { shared++; }
来源：http://dali.daxiang520.top/Article/details/gtyvqfnqca.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cucudq.cn/Article/details/gtivmhjzyb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnutlzop.html

C#:   lock (gate) { shared++; }
来源：http://dali.cucudq.cn/Article/details/gtkjghkgty.html

[O04] 定义异步函数并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gtceelwzic.html

Py:   async def f():⏎    await g()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqjlifyc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.feifeiyinyue.top/Article/details/gtfpulhwaj.html

JS:   async function f() { await g(); }
来源：http://dali.ybcxt.top/Article/details/gtmktnfplc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258.top/Article/details/gtysvxepeq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xziqi.cn/Article/details/gtdiosvzuv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrezaqjm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sxryk.cn/Article/details/gtrbualbsk.html

C#:   async Task F() { await G(); }
来源：http://dali.meibo888.top/Article/details/gtnzboqdzm.html

[O05] 并发执行并等待全部完成
来源：http://dali.zdqjudy.top/Article/details/gtqugafjmj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jiagoushi.top/Article/details/gtozkhcqub.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yuanzhike.top/Article/details/gtmmyuonuw.html

JS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gtuppycgsz.html

TS:   await Promise.all(tasks)
来源：http://dali.redwolf501.top/Article/details/gtxxaohjlt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ppjwa.cn/Article/details/gtrvjhoqwp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yueranfly.top/Article/details/gtmkiwqmuw.html

Ruby: threads.map(&:join)
来源：http://dali.0kj1m.cn/Article/details/gtlrypxeue.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.havefunace.top/Article/details/gthswxtubb.html

[O06] 使用进程池
来源：http://dali.zhixingplan.top/Article/details/gtkttxnppc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xinyue.icu/Article/details/gtmflwqisi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guannengcc.top/Article/details/gtcybvjhym.html

JS:   // child_process / cluster 模块
来源：http://dali.redwolf501.top/Article/details/gtweuatfxi.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gttbtoszod.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ydzc1.top/Article/details/gtjhutdlhh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cdnleiting.top/Article/details/gtzxlgfqmn.html

Ruby: // fork 块
来源：http://dali.yuxming.cn/Article/details/gtzfnelcfg.html

C#:   Parallel.For
来源：http://dali.gotoacloud.top/Article/details/gtjppicfdo.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtsdkbywjt.html

P. 常用工具函数
来源：http://dali.shuidangran.top/Article/details/gtcbjrvbog.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktrqqgvb.html

[P01] 生成 UUID
来源：http://dali.gzhubu.top/Article/details/gtusjsyuwv.html

Py:   str(uuid.uuid4())
来源：http://dali.zycfv.cn/Article/details/gttfgywvzi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ydzc1.top/Article/details/gtttfsqqfm.html

JS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtlvwglxsd.html

TS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gtzehtrzbk.html

Java: UUID.randomUUID().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtzytrvyrp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ivvv.top/Article/details/gttofsqezh.html

Ruby: SecureRandom.uuid
来源：http://dali.bjfxy.top/Article/details/gtewjcoxbj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hysaishi.cn/Article/details/gtbwyuaedf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuxming.cn/Article/details/gtguybhvky.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenzaomai.com/Article/details/gtlwriazkw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xinyue.icu/Article/details/gtxxjjtedh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sxryk.cn/Article/details/gtlhctgcqe.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhixingplan.top/Article/details/gttdpkdfzp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtbxpkmfnb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hysaishi.cn/Article/details/gtdokvxmaq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtskvkrkkn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pengpengdd.cyou/Article/details/gtrmjdbqal.html

[P03] 生成短随机字符串
来源：http://dali.ybcxt.top/Article/details/gtuesztmvy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jlsjyb.cn/Article/details/gtinsajhmo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nwbrower.top/Article/details/gtttyixffs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xziqi.cn/Article/details/gtlfqxeqsc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fengsongda.top/Article/details/gtfivkjzih.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnxiangtu.top/Article/details/gtqrcfcmeg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aibaodan.cn/Article/details/gtkuzsqwks.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hammf.cn/Article/details/gteiwheelg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hysaishi.cn/Article/details/gtavvxqcto.html

[P04] 求长度
来源：http://dali.cashguo.top/Article/details/gtkxymxdjs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdbdicra.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtgyltkjak.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.svipenyu.cn/Article/details/gtolmwsqmz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gtgzoffrfz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.bjfxy.top/Article/details/gtlkglkxxe.html

Go:   len(arr);  len(m)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqucmrvcp.html

Ruby: x.length;  x.size
来源：http://dali.ydzc1.top/Article/details/gtsbanpdrn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yongpay.top/Article/details/gtxzgudyiv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sufxvd.cn/Article/details/gtssgdtequ.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sufxvd.cn/Article/details/gtystpkxxz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xziqi.cn/Article/details/gtochmwbpe.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.quarkkingdee.top/Article/details/gtqedcwhub.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gtghaamzyu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sweek.top/Article/details/gtpiavbgfq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gtnovfwuuh.html

Ruby: a == b
来源：http://dali.yuanzhike.top/Article/details/gtqldvvqnb.html


<!-- 参考信息 -->