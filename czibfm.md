代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gtwtkenvnh.html

Java: resp.statusCode()
来源：http://dali.yvedp.cn/Article/details/gtpguhjwha.html

Go:   resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gtdslhvske.html

Ruby: resp.code.to_i
来源：http://dali.ehwqpu.com/Article/details/gtzykpxncs.html

C#:   (int)resp.StatusCode
来源：http://dali.sweek.top/Article/details/gtfzwylnga.html

[L08] 并发请求多个地址
来源：http://dali.ppjwa.cn/Article/details/gtjkvdofhd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hysaishi.cn/Article/details/gtlatwfdic.html

PHP:  curl_multi_init() 系列
来源：http://dali.cucudq.cn/Article/details/gtfnmeudep.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gtzirtmtcm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlcubbjzb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aibaodan.cn/Article/details/gttuhjgtqo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guannengcc.top/Article/details/gtabzjfanf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gtqftgljsa.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gotoacloud.top/Article/details/gtthpcxzlk.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtwkgbvjfx.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenzaomai.com/Article/details/gtlzjbargm.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtdmytqqdm.html

[M01] 读取命令行参数
来源：http://dali.mhx1999.top/Article/details/gtyzmuvlte.html

Py:   sys.argv[1:]
来源：http://dali.aizwys.cn/Article/details/gtabauopxt.html

PHP:  $argv;  $argc;
来源：http://dali.yongpay.top/Article/details/gtbfpsmwqx.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gtjvwdzrzj.html

TS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gtzpoxcllz.html

Java: args 数组（main 方法参数）
来源：http://dali.zhiwuduotai.top/Article/details/gtaydhjouv.html

Go:   os.Args[1:]
来源：http://dali.jinqigufen.top/Article/details/gtxrclgwnc.html

Ruby: ARGV
来源：http://dali.jyoumei.cn/Article/details/gtsskoldyd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkhhykly.html

[M02] 读取环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtumjvrbsj.html

Py:   os.environ.get("HOME")
来源：http://dali.yonumen.top/Article/details/gttbaesmoj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gtsqdtaikx.html

JS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gtwoonpsbo.html

TS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gtfwieclxf.html

Java: System.getenv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtnpzkhnfg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtochkjalv.html

Ruby: ENV["HOME"]
来源：http://dali.jianghu66.top/Article/details/gtudpgbdgx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.andypj.xyz/Article/details/gtmrfsdywl.html

[M03] 执行外部命令
来源：http://dali.svipenyu.cn/Article/details/gtojgxspyo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.haohaochexian.top/Article/details/gtybiwwusy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.smart0.xyz/Article/details/gtysnwkozd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gtrtizvxlc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gterjprcei.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258888.top/Article/details/gtekcepcsv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hongshengwenyu.top/Article/details/gtykzxhcty.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.redwolf501.top/Article/details/gthdtuljxa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.snrcjt.cn/Article/details/gtpigxabkx.html

[M04] 获取当前工作目录
来源：http://dali.dashuyun.cn/Article/details/gtulbbwxme.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gtgelxsfja.html

PHP:  getcwd();
来源：http://dali.yangfankeji.com/Article/details/gtcaiccoyf.html

JS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gtyjbsxorm.html

TS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtgomujbca.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.c1oappe.top/Article/details/gtcyhgujie.html

Go:   os.Getwd()
来源：http://dali.ehwqpu.com/Article/details/gtbvuwsvry.html

Ruby: Dir.pwd
来源：http://dali.yj20258888.top/Article/details/gtegclbcdy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.redwolf501.top/Article/details/gtmhdnlkuh.html

[M05] 设置退出码
来源：http://dali.nanxinkj.top/Article/details/gtuphzmofg.html

Py:   sys.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtfydrntzp.html

PHP:  exit(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkhusxaf.html

JS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtmtclkxda.html

TS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtrtbebudz.html

Java: System.exit(1)
来源：http://dali.yvedp.cn/Article/details/gthljxwkke.html

Go:   os.Exit(1)
来源：http://dali.havefunace.top/Article/details/gtxhabhfbi.html

Ruby: exit 1
来源：http://dali.shangyingyoupin.top/Article/details/gtnnsafvdk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hysaishi.cn/Article/details/gtuzlcwmuv.html

[M06] 向标准错误输出
来源：http://dali.havefunace.top/Article/details/gtdzxjxzzu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.vqdsnc.cn/Article/details/gtsgjndmtd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cheryme.top/Article/details/gtkodxxhwp.html

JS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gtboayjbcq.html

TS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtkcigfxor.html

Java: System.err.println("err")
来源：http://dali.jqgufenzy.top/Article/details/gthwtwvdxc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.meibo888.top/Article/details/gtxyycwnsj.html

Ruby: warn "err"
来源：http://dali.yvedp.cn/Article/details/gtjenmqoyd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigufen.top/Article/details/gtrgotmxav.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzdfapap.html

Py:   if __name__ == "__main__":
来源：http://dali.ehwqpu.com/Article/details/gtljjpfjvv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.mhx1999.top/Article/details/gtubuvctpe.html

JS:   require.main === module
来源：http://dali.smart0.xyz/Article/details/gtcpghxfak.html

TS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gtqikxoyve.html

Java: public static void main(String[] args)
来源：http://dali.jinqigfzy.top/Article/details/gtwafxycnu.html

Go:   func main()
来源：http://dali.tianlin.xyz/Article/details/gtiztsjzbc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cdnleiting.top/Article/details/gtvrdofxpz.html

C#:   static void Main(string[] args)
来源：http://dali.iojbl.cn/Article/details/gtdggvfxmu.html

[M08] 获取系统与运行时信息
来源：http://dali.chenlongwang.top/Article/details/gtrwszgzvv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyaerlqvy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jiagoushi.top/Article/details/gtjeuosulk.html

JS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gtzmefpxly.html

TS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gthnvxrkaa.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.birdmap.top/Article/details/gtqjxhkujt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yueranfly.top/Article/details/gtgcbhndyq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sweek.top/Article/details/gtnuoipojm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjbfvsnp.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gthgjeduxd.html

N. 数据结构与算法
来源：http://dali.jqgufenzy.top/Article/details/gtmckryhdj.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtksmutprw.html

[N01] 二分查找（有序数组）
来源：http://dali.zhixingplan.top/Article/details/gtkwhacvbs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtxafmflsp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtpiajsmhl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtughdlviq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sxryk.cn/Article/details/gtphqhgbhl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtacmmknsn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtykntamdl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangshuangyany.cn/Article/details/gtbtlqsvot.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtaprhzdkz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj202588.top/Article/details/gtpjyespcj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gtrocicklx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.snrcjt.cn/Article/details/gtkhnsqduo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gtrhzjcwqj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gtgjygycez.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shangyingyoupin.top/Article/details/gtdxwtksee.html

Go:   slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gtpveshucg.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gtnruonaix.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daria6918.cn/Article/details/gtpqhedsfn.html

[N03] 快速排序（分治示例）
来源：http://dali.yanxiufei.cn/Article/details/gtdenximpu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.mhx1999.top/Article/details/gtyrhmuncm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cqqwz.cn/Article/details/gtmbenxdzi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shzxlz.cn/Article/details/gtcnolmqlb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gtoqaczeyb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sufxvd.cn/Article/details/gtvhlxemqx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guannengcc.top/Article/details/gtysfvjauv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.aizwys.cn/Article/details/gtsmlutdfb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dianchejie.cn/Article/details/gtznebycqm.html

[N04] 斐波那契数列
来源：http://dali.jyoumei.cn/Article/details/gtpxrcuyuk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gtbmmkpaju.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gtubadidpj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtmdsmpmhg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gtpeyycgxz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.bjfxy.top/Article/details/gtuqsjyrmw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.svipenyu.cn/Article/details/gtdmapxmsa.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtsuocqrms.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtaozbbhuu.html

[N05] 最大公约数
来源：http://dali.yanxiufei.cn/Article/details/gtzpxoosoz.html

Py:   math.gcd(a, b)
来源：http://dali.snrcjt.cn/Article/details/gtkfqqoxce.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.mhx1999.top/Article/details/gtghwdzgvy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.snrcjt.cn/Article/details/gtmsqptcrn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gtgvhqbcij.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jyoumei.cn/Article/details/gtmemyzxmu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.snrcjt.cn/Article/details/gtgubnqoff.html

Ruby: a.gcd(b)
来源：http://dali.sweek.top/Article/details/gtdobgwhqx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzeqmbvyk.html

[N06] 判断回文字符串
来源：http://dali.smart0.xyz/Article/details/gtnywkfbzm.html

Py:   s == s[::-1]
来源：http://dali.yanxiufei.cn/Article/details/gthrdxbkps.html

PHP:  $s === strrev($s);
来源：http://dali.pycfn.com/Article/details/gtoadpxyka.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtboggjuzu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtrbjioiuq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuanzhike.top/Article/details/gtzbhqrbqj.html

Go:   // 双指针从两端比较
来源：http://dali.ehwqpu.com/Article/details/gtfzhdhisa.html

Ruby: s == s.reverse
来源：http://dali.jyoumei.cn/Article/details/gtyrytvolh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gtoxzrqfqb.html

[N07] 两数之和（返回下标）
来源：http://dali.shzxlz.cn/Article/details/gtytecwhdf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ivvv.top/Article/details/gthkphkozw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuetiantiany.cn/Article/details/gtafphgnmq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sweek.top/Article/details/gtqasmowbc.html

TS:   // 手写 Map<string, number>
来源：http://dali.tianlin.xyz/Article/details/gtxclwgzqf.html

Java: // 手写 HashMap
来源：http://dali.jinqigufen.top/Article/details/gtcixxloot.html

Go:   // 手写 map[int]int
来源：http://dali.kuanghao11.cn/Article/details/gtrkycifmw.html

Ruby: // 手写 Hash
来源：http://dali.c1oappe.top/Article/details/gtlkwhkcdn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.smart0.xyz/Article/details/gtijhqjrpp.html

[N08] 生成全排列
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmfwwvza.html

Py:   itertools.permutations(arr)
来源：http://dali.guannengcc.top/Article/details/gtqdtoeoin.html

PHP:  // 手写递归交换
来源：http://dali.c1oappe.top/Article/details/gtwcdlcmyv.html

JS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtkbryuhbv.html

TS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwrdjgyi.html

Java: // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtbqqtqqig.html

Go:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtndjaqtjo.html

Ruby: arr.permutation.to_a
来源：http://dali.ybcxt.top/Article/details/gtuxnlmatz.html

C#:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtkxmflilq.html

[N09] 栈与队列
来源：http://dali.jianghu66.top/Article/details/gtvgsjhqrh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guowangkeji.top/Article/details/gtyihlmuro.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yongpay.top/Article/details/gtcteeitxr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.c1oappe.top/Article/details/gtlvaqmlbz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.vqdsnc.cn/Article/details/gtbvziqapk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aibaodan.cn/Article/details/gthaeasvse.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.redwolf501.top/Article/details/gtixjcgsml.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtfonxsret.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gtguqqburz.html

[N10] 链表节点定义
来源：http://dali.yvedp.cn/Article/details/gtwagnpagp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuetiantiany.cn/Article/details/gtxnleyklt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.feifeiyinyue.top/Article/details/gtajhphiji.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgufenzy.top/Article/details/gtfcwcaxfm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hnqzz.top/Article/details/gttfyajrou.html

Java: class Node { int v; Node next; }
来源：http://dali.yonumen.top/Article/details/gtwgthnedk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cqqwz.cn/Article/details/gtqjbmtygn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guowangkeji.top/Article/details/gtlcmgrvgd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gzhubu.top/Article/details/gtqxluhodj.html

[N11] 二叉树中序遍历
来源：http://dali.nanxuanxn.top/Article/details/gtpxvwlzmo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zycfv.cn/Article/details/gtfrxrrxuw.html

PHP:  // 手写递归函数
来源：http://dali.yongpay.top/Article/details/gtwohyjfbg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxuanxn.top/Article/details/gtiuyjyisf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.havefunace.top/Article/details/gtsnxvnxpl.html

Java: // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtssddmgmd.html

Go:   // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gtyzhqaxpg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cashguo.top/Article/details/gtmdjxwfkc.html

C#:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gtrbobpeft.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.kuanghao11.cn/Article/details/gtxxexujgt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigfzy.top/Article/details/gtfmbqeztg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.smart0.xyz/Article/details/gtgmqynkoi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtwiisoznl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gtyadifwzp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tianlin.xyz/Article/details/gterjoszmx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.haohaochexian.top/Article/details/gtrhsioitp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtirnkqqhw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gtlsbcybqm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtjkladdcw.html

O. 并发与异步
来源：http://dali.sweek.top/Article/details/gtmsuobada.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtupexaged.html

[O01] 启动一个线程
来源：http://dali.chenjidiqi.icu/Article/details/gtjoqdiifq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hywenlv.cn/Article/details/gtiwzbgpqg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.havefunace.top/Article/details/gtjuitenkv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.bjfxy.top/Article/details/gtsbixcrwe.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gtuxujpdql.html

Java: new Thread(() -> f()).start()
来源：http://dali.xuetiantiany.cn/Article/details/gtcyxvohbt.html

Go:   go f()
来源：http://dali.jiagoushi.top/Article/details/gtfvisykto.html

Ruby: Thread.new { f }
来源：http://dali.kuanghao11.cn/Article/details/gtytjvbwzx.html

C#:   Task.Run(() => F());
来源：http://dali.zhongyouzk.top/Article/details/gtrqmriasl.html

[O02] 使用线程池
来源：http://dali.svipenyu.cn/Article/details/gtqvtmucuv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jlsjyb.cn/Article/details/gtnhaintof.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangshuangyany.cn/Article/details/gtlnaogbnm.html

JS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gtyhuixodj.html

TS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gtsyovgjcn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.vqdsnc.cn/Article/details/gtqoyroabl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.smart0.xyz/Article/details/gtkdvpcmca.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhengqikj.top/Article/details/gtbkktkjyy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.9152youxi.cn/Article/details/gtnhlcjpzd.html

[O03] 加锁保护共享数据
来源：http://dali.xinyue.icu/Article/details/gthtxqfawy.html

Py:   with lock: shared += 1
来源：http://dali.jiagoushi.top/Article/details/gtuphymfib.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuxming.cn/Article/details/gtnolpswso.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dashuyun.cn/Article/details/gtvqdxsbiz.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gteutycggk.html

Java: synchronized (this) { shared++; }
来源：http://dali.wangdashe.top/Article/details/gthfdlseyw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jyoumei.cn/Article/details/gtzwfnplyg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhoulong.xyz/Article/details/gtfoxzswqk.html

C#:   lock (gate) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gtjtpoixbb.html

[O04] 定义异步函数并等待
来源：http://dali.jianghu66.top/Article/details/gtfrdxynhm.html

Py:   async def f():⏎    await g()
来源：http://dali.wangshuangyany.cn/Article/details/gtffbazpzt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinghuilouyu.cn/Article/details/gthicbyjlk.html

JS:   async function f() { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gtfrtzmypa.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gzhubu.top/Article/details/gtsvfbonge.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258888.top/Article/details/gtimhseujl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.guowangkeji.top/Article/details/gtmiwhabdq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shzxlz.cn/Article/details/gtaaliodjb.html

C#:   async Task F() { await G(); }
来源：http://dali.yj202588.top/Article/details/gtjgcrbrof.html

[O05] 并发执行并等待全部完成
来源：http://dali.fzhhl.top/Article/details/gtcmmrxfyd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sweek.top/Article/details/gtekgxukii.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gotoacloud.top/Article/details/gtrfapuehc.html

JS:   await Promise.all(tasks)
来源：http://dali.havefunace.top/Article/details/gtibtvndyo.html

TS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gtmspumzka.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jqgufenzy.top/Article/details/gtgszzbnow.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgufenzy.top/Article/details/gtfjcewwko.html

Ruby: threads.map(&:join)
来源：http://dali.birdmap.top/Article/details/gtlmohoqhd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqlgnsxuf.html

[O06] 使用进程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqfrqupg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ydzc1.top/Article/details/gtvooeihec.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtewtjvvek.html

JS:   // child_process / cluster 模块
来源：http://dali.redwolf501.top/Article/details/gtbmktequc.html

TS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gttmdblkje.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenlongwang.top/Article/details/gtrpepnvdp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgfzy.top/Article/details/gtlrdaxvmu.html

Ruby: // fork 块
来源：http://dali.sweek.top/Article/details/gtfeaarurz.html

C#:   Parallel.For
来源：http://dali.dianchejie.cn/Article/details/gtfivzsyph.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtklgsbjky.html

P. 常用工具函数
来源：http://dali.shzxlz.cn/Article/details/gtdtkssomp.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtpmkbbmyw.html

[P01] 生成 UUID
来源：http://dali.smart0.xyz/Article/details/gtdasflgoj.html

Py:   str(uuid.uuid4())
来源：http://dali.yuanzhike.top/Article/details/gtljiciuae.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.birdmap.top/Article/details/gtwbijyuvp.html

JS:   crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gtvklpbouu.html

TS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gtqornnllu.html

Java: UUID.randomUUID().toString()
来源：http://dali.nwbrower.top/Article/details/gtqfprlrfu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cucudq.cn/Article/details/gtjqlcivia.html

Ruby: SecureRandom.uuid
来源：http://dali.zhengqikj.top/Article/details/gtfxwjiwda.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnxiangtu.top/Article/details/gthjwtcayc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.fengsongda.top/Article/details/gtwpgxijda.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigfzy.top/Article/details/gtqoowbkek.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fengsongda.top/Article/details/gtuyrmrbck.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jyoumei.cn/Article/details/gtpgskqvwk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenjidiqi.icu/Article/details/gtpajvrkha.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yuanzhike.top/Article/details/gtgoronhbc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangdashe.top/Article/details/gtklnpcuut.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.aizwys.cn/Article/details/gtdxvrpbst.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nwbrower.top/Article/details/gtsbfqmtyo.html

[P03] 生成短随机字符串
来源：http://dali.sxryk.cn/Article/details/gtbfglhhxq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.redwolf501.top/Article/details/gtbkljworp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jianghu66.top/Article/details/gtwzbhgxgu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gtphnazwox.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gtcvutimit.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj20258888.top/Article/details/gtqfjyguty.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sxryk.cn/Article/details/gttvwlzsyo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.quarkkingdee.top/Article/details/gtsveeatsj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.0kj1m.cn/Article/details/gtavfujwcd.html

[P04] 求长度
来源：http://dali.sxryk.cn/Article/details/gtxwmxmmyi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.aibaodan.cn/Article/details/gterjuwyqy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtrjjpczvx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gtnlrniyxf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tian-w.cn/Article/details/gtooiqxhgq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tian-w.cn/Article/details/gtzxrkixnu.html

Go:   len(arr);  len(m)
来源：http://dali.ivvv.top/Article/details/gtzdywcyxl.html

Ruby: x.length;  x.size
来源：http://dali.9152youxi.cn/Article/details/gtdihqphqf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.9152youxi.cn/Article/details/gtygniikfy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj20258.top/Article/details/gtomrfnecy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daxiang520.top/Article/details/gtrlkjgwvt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cqqwz.cn/Article/details/gtdvhbcyie.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuxming.cn/Article/details/gtzstjfyik.html


<!-- 参考信息 -->