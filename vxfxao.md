代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gt2gkwtcmeq.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ntjpuyff.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hysaishi.cn/Article/details/gt2fszujygf.html

PHP:  curl_multi_init() 系列
来源：http://dali.vqdsnc.cn/Article/details/gt2pwymxbqa.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gt2clboljxx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gt2yiqbgdae.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.iojbl.cn/Article/details/gt2twtitvqx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sxryk.cn/Article/details/gt2clfybmch.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.haohaochexian.top/Article/details/gt2kpvbvtry.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2glqmutxk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2jxslwxua.html

M. 命令行 / 进程 / 环境
来源：http://dali.hywenlv.cn/Article/details/gt2idwqsrcb.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2dmhecyap.html

[M01] 读取命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2vgwcysay.html

Py:   sys.argv[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gt2tnvwymen.html

PHP:  $argv;  $argc;
来源：http://dali.ehwqpu.com/Article/details/gt2torpnpix.html

JS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gt2qgipewvy.html

TS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gt2flpuoyui.html

Java: args 数组（main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gt2gccrcnjx.html

Go:   os.Args[1:]
来源：http://dali.fengsongda.top/Article/details/gt2zxjxippz.html

Ruby: ARGV
来源：http://dali.yuanzhike.top/Article/details/gt2zrcafgwc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gt2bbbadida.html

[M02] 读取环境变量
来源：http://dali.smart0.xyz/Article/details/gt2axfljguf.html

Py:   os.environ.get("HOME")
来源：http://dali.xuanzx.com/Article/details/gt2ecbsbokq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gt2jppscqmd.html

JS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gt2vldcqkrt.html

TS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gt2abacqgyk.html

Java: System.getenv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gt2udfkkiuw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2hjqkirov.html

Ruby: ENV["HOME"]
来源：http://dali.yonumen.top/Article/details/gt2ycyafnkt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gt2xajkdntl.html

[M03] 执行外部命令
来源：http://dali.yj20258.top/Article/details/gt2pqxejrqf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hongshengwenyu.top/Article/details/gt2juacixwp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hywenlv.cn/Article/details/gt2bvfngqab.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gt2uzamhebr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gt2vycwjuvf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhongyouzk.top/Article/details/gt2dvrptxln.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cheryme.top/Article/details/gt2pueuaumi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhiwuduotai.top/Article/details/gt2jeljyolm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cashguo.top/Article/details/gt2zqpjmvya.html

[M04] 获取当前工作目录
来源：http://dali.yj20258.top/Article/details/gt2jmrqjdlk.html

Py:   os.getcwd()
来源：http://dali.sufxvd.cn/Article/details/gt2euyuhvrb.html

PHP:  getcwd();
来源：http://dali.yvedp.cn/Article/details/gt2ozvawcxk.html

JS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gt2oekhskyq.html

TS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gt2dsdxgkcl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.0kj1m.cn/Article/details/gt2xlwboqtx.html

Go:   os.Getwd()
来源：http://dali.mhx1999.top/Article/details/gt2eztrvqrz.html

Ruby: Dir.pwd
来源：http://dali.gogol.net.cn/Article/details/gt2wgsjsxvd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yvedp.cn/Article/details/gt2eclaloov.html

[M05] 设置退出码
来源：http://dali.gaohongyu789.top/Article/details/gt2xeugibqf.html

Py:   sys.exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2cvanjfvn.html

PHP:  exit(1);
来源：http://dali.tanke756.top/Article/details/gt2gzmdfqhl.html

JS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gt2ydaygevz.html

TS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2xdonlmrx.html

Java: System.exit(1)
来源：http://dali.cheryme.top/Article/details/gt2gkjnszcp.html

Go:   os.Exit(1)
来源：http://dali.jianghu66.top/Article/details/gt2hgfcrpyy.html

Ruby: exit 1
来源：http://dali.aizwys.cn/Article/details/gt2aeigfnoo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxinkj.top/Article/details/gt2dwqlmalj.html

[M06] 向标准错误输出
来源：http://dali.yuanzhike.top/Article/details/gt2gkfdzqil.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tian-w.cn/Article/details/gt2njfpucyo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sysykeji.top/Article/details/gt2drvkumfx.html

JS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gt2cwhgtydv.html

TS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gt2tnmamyqt.html

Java: System.err.println("err")
来源：http://dali.0kj1m.cn/Article/details/gt2oausnusf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.kuanghao11.cn/Article/details/gt2drdofpbc.html

Ruby: warn "err"
来源：http://dali.xuetiantiany.cn/Article/details/gt2glrxiikr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jiagoushi.top/Article/details/gt2vhybktwu.html

[M07] 判断是否为主入口
来源：http://dali.chenzaomai.com/Article/details/gt2tiswkkyg.html

Py:   if __name__ == "__main__":
来源：http://dali.pengpengdd.cyou/Article/details/gt2ibwsijbv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.andypj.xyz/Article/details/gt2yrjaxuap.html

JS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gt2wevnukum.html

TS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gt2ljufcmob.html

Java: public static void main(String[] args)
来源：http://dali.snrcjt.cn/Article/details/gt2yqgoelqd.html

Go:   func main()
来源：http://dali.redwolf501.top/Article/details/gt2hsecjghr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuxming.cn/Article/details/gt2dkwupedi.html

C#:   static void Main(string[] args)
来源：http://dali.zycfv.cn/Article/details/gt2xyjxcldk.html

[M08] 获取系统与运行时信息
来源：http://dali.redwolf501.top/Article/details/gt2xhdkyxre.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gotoacloud.top/Article/details/gt2rhwlmsvn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sweek.top/Article/details/gt2zefbsqlt.html

JS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gt2cbrmwsox.html

TS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gt2zowendmw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.daria6918.cn/Article/details/gt2dbutzykc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uwdilhlf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.quarkkingdee.top/Article/details/gt2ibnawbjv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gogol.net.cn/Article/details/gt2ddwnbbwe.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2mnpanbpr.html

N. 数据结构与算法
来源：http://dali.shzxlz.cn/Article/details/gt2spkzrxip.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2dnisqxpq.html

[N01] 二分查找（有序数组）
来源：http://dali.svipenyu.cn/Article/details/gt2vpzspvhw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dvfzbtks.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj202588.top/Article/details/gt2khlmyqne.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gt2dvvhwgxb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gt2ayojwvkh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2vjlvrcvx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2kbyikcgp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.andypj.xyz/Article/details/gt2wopkgzfi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gt2xdrssloa.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xylfe.cn/Article/details/gt2iizwcsmy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gt2drshwfxu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnqzz.top/Article/details/gt2rlimwgpu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gt2giybabod.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gt2dnxcgwwn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dianchejie.cn/Article/details/gt2xynscold.html

Go:   slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2bbeojhml.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gt2jvbihfnk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.316326.xyz/Article/details/gt2uccpcgpu.html

[N03] 快速排序（分治示例）
来源：http://dali.birdmap.top/Article/details/gt2phhbzkso.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinqigfzy.top/Article/details/gt2rspgtgjt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.bjfxy.top/Article/details/gt2kmxobduc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gt2ugheqjvw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gt2havnecxi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sweek.top/Article/details/gt2kveadakq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigfzy.top/Article/details/gt2brqnjtxr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigfzy.top/Article/details/gt2rwrwoudv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shangyingyoupin.top/Article/details/gt2wwciukfe.html

[N04] 斐波那契数列
来源：http://dali.kuanghao11.cn/Article/details/gt2wiavblvk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tlqdbekp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cdnleiting.top/Article/details/gt2eleadjwa.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2nbfopabb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mtxkflmq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gt2gpxydake.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gotoacloud.top/Article/details/gt2nnywtmpa.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gt2carbhfjd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2mumpotfw.html

[N05] 最大公约数
来源：http://dali.sysykeji.top/Article/details/gt2imxxuzrf.html

Py:   math.gcd(a, b)
来源：http://dali.yuxming.cn/Article/details/gt2fhasdtne.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guowangkeji.top/Article/details/gt2lyxyjvkl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gt2slbwxous.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gogol.net.cn/Article/details/gt2fnqlmbru.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yongpay.top/Article/details/gt2gzwhzqkj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vdhgqnmy.html

Ruby: a.gcd(b)
来源：http://dali.daria6918.cn/Article/details/gt2zscbckqy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ydzc1.top/Article/details/gt2apuxzcjo.html

[N06] 判断回文字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2qevvqjiy.html

Py:   s == s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gt2rjkvcliq.html

PHP:  $s === strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gt2dfztnxpz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gt2bvicexii.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gt2zghjucvx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shangyingyoupin.top/Article/details/gt2qlaaqyja.html

Go:   // 双指针从两端比较
来源：http://dali.yuanzhike.top/Article/details/gt2bysoerkr.html

Ruby: s == s.reverse
来源：http://dali.bjfxy.top/Article/details/gt2nwwdhtuk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gt2adytvmxo.html

[N07] 两数之和（返回下标）
来源：http://dali.haohaochexian.top/Article/details/gt2xhrrmyjz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jyoumei.cn/Article/details/gt2hifyljli.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yuxming.cn/Article/details/gt2izypmhfz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhengqikj.top/Article/details/gt2axkskkmk.html

TS:   // 手写 Map<string, number>
来源：http://dali.tanke756.top/Article/details/gt2oghtehbc.html

Java: // 手写 HashMap
来源：http://dali.sufxvd.cn/Article/details/gt2caypqsvc.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258888.top/Article/details/gt2wpzkfrdk.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gt2nsugpcrk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2damsondm.html

[N08] 生成全排列
来源：http://dali.sweek.top/Article/details/gt2wjlbpvcu.html

Py:   itertools.permutations(arr)
来源：http://dali.havefunace.top/Article/details/gt2yrgjozyx.html

PHP:  // 手写递归交换
来源：http://dali.jinqigfzy.top/Article/details/gt2nesuszpe.html

JS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2vxkfgkdm.html

TS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gt2gvtpojpt.html

Java: // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gt2bqnuabet.html

Go:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gt2hsollklw.html

Ruby: arr.permutation.to_a
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iwwhmfuq.html

C#:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2erfokdex.html

[N09] 栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gt2jmrxzypx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangdashe.top/Article/details/gt2qxglvofk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jianghu66.top/Article/details/gt2ajiggexk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gt2tlmxrhzj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.andypj.xyz/Article/details/gt2flfgdofh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jianghu66.top/Article/details/gt2fdtqsngf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhixingplan.top/Article/details/gt2dkcxcyuo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gt2thkzftud.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gt2qjaerkid.html

[N10] 链表节点定义
来源：http://dali.birdmap.top/Article/details/gt2jwmaywmb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhongyouzk.top/Article/details/gt2loozhuqr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj20258888.top/Article/details/gt2hkysmtjg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nanxinkj.top/Article/details/gt2pqdqvpat.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.c1oappe.top/Article/details/gt2rirkkqdu.html

Java: class Node { int v; Node next; }
来源：http://dali.ppjwa.cn/Article/details/gt2robfpzje.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cucudq.cn/Article/details/gt2pdnuifrv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhongyouzk.top/Article/details/gt2sfgyercb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ehwqpu.com/Article/details/gt2idufcsox.html

[N11] 二叉树中序遍历
来源：http://dali.316326.xyz/Article/details/gt2ugfmulgi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.birdmap.top/Article/details/gt2krscldhu.html

PHP:  // 手写递归函数
来源：http://dali.gzhubu.top/Article/details/gt2htnglmnj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gt2eqliulpf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gt2gjidhfvi.html

Java: // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gt2zdxxqymu.html

Go:   // 手写递归
来源：http://dali.sysykeji.top/Article/details/gt2uipcdnun.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cqqwz.cn/Article/details/gt2bcniagpg.html

C#:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wiucuxoa.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cashguo.top/Article/details/gt2cpcqyigs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhongyouzk.top/Article/details/gt2rbfdevvn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ivvv.top/Article/details/gt2xmhkgmlr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gt2hgludcow.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.c1oappe.top/Article/details/gt2vewqpbhq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gt2ybcpbivu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sysykeji.top/Article/details/gt2xozcpjhw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yvedp.cn/Article/details/gt2ostqphvg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jyoumei.cn/Article/details/gt2ifiluqgt.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2lrxsvrgi.html

O. 并发与异步
来源：http://dali.yonumen.top/Article/details/gt2vldnyciu.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2tnsrddtu.html

[O01] 启动一个线程
来源：http://dali.yongpay.top/Article/details/gt2nkcqqgdg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hongshengwenyu.top/Article/details/gt2lkvykamw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yonumen.top/Article/details/gt2jvtdfkeb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cdnleiting.top/Article/details/gt2icpkhixl.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gt2qqgxbygj.html

Java: new Thread(() -> f()).start()
来源：http://dali.xuanzx.com/Article/details/gt2nxbaycqe.html

Go:   go f()
来源：http://dali.ppjwa.cn/Article/details/gt2enuanfcw.html

Ruby: Thread.new { f }
来源：http://dali.yj202588.top/Article/details/gt2xekxdtys.html

C#:   Task.Run(() => F());
来源：http://dali.birdmap.top/Article/details/gt2qchgygzr.html

[O02] 使用线程池
来源：http://dali.tianlin.xyz/Article/details/gt2umpkfktd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.havefunace.top/Article/details/gt2iefesebd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.snrcjt.cn/Article/details/gt2yoormiqp.html

JS:   // worker_threads 线程池
来源：http://dali.pycfn.com/Article/details/gt2mzkbhbcm.html

TS:   // worker_threads 线程池
来源：http://dali.gotoacloud.top/Article/details/gt2uviyzwht.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ivvv.top/Article/details/gt2fvyhcrzf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xziqi.cn/Article/details/gt2rlkksdch.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.mhx1999.top/Article/details/gt2juihbhut.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.bjfxy.top/Article/details/gt2runppjve.html

[O03] 加锁保护共享数据
来源：http://dali.tanke756.top/Article/details/gt2ecxqmtoy.html

Py:   with lock: shared += 1
来源：http://dali.nwbrower.top/Article/details/gt2tnmwmwye.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258888.top/Article/details/gt2bnefwmbu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenzaomai.com/Article/details/gt2wwtbxsak.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gt2ygiscpyy.html

Java: synchronized (this) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gt2tipxdjbl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenjidiqi.icu/Article/details/gt2kskkstyq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxinkj.top/Article/details/gt2zrayuhsk.html

C#:   lock (gate) { shared++; }
来源：http://dali.vqdsnc.cn/Article/details/gt2mgxtmwjh.html

[O04] 定义异步函数并等待
来源：http://dali.wangshuangyany.cn/Article/details/gt2bekzyjci.html

Py:   async def f():⏎    await g()
来源：http://dali.c1oappe.top/Article/details/gt2jxfmfazs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangdashe.top/Article/details/gt2dlomuolh.html

JS:   async function f() { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gt2chqtxtib.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gt2opcgnodx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fzhhl.top/Article/details/gt2epfnqjbp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jianghu66.top/Article/details/gt2uwnpuqdg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shzxlz.cn/Article/details/gt2ungzsiir.html

C#:   async Task F() { await G(); }
来源：http://dali.pycfn.com/Article/details/gt2owapaawd.html

[O05] 并发执行并等待全部完成
来源：http://dali.tian-w.cn/Article/details/gt2bhnlieqe.html

Py:   asyncio.gather(*tasks)
来源：http://dali.aizwys.cn/Article/details/gt2hnynbodq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.mhx1999.top/Article/details/gt2xbhqnbgy.html

JS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gt2unvejsap.html

TS:   await Promise.all(tasks)
来源：http://dali.xylfe.cn/Article/details/gt2gjapmsqa.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yueranfly.top/Article/details/gt2knozqfcd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zdqjudy.top/Article/details/gt2ypsixhbp.html

Ruby: threads.map(&:join)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bmepevus.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yongpay.top/Article/details/gt2sxnmjboy.html

[O06] 使用进程池
来源：http://dali.yuxming.cn/Article/details/gt2aqwaoosu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.snrcjt.cn/Article/details/gt2ueiovbbj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pycfn.com/Article/details/gt2wshfvsbw.html

JS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gt2qghvbrbg.html

TS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gt2pnkbjods.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2helowduj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hywenlv.cn/Article/details/gt2siigfzvk.html

Ruby: // fork 块
来源：http://dali.xinyue.icu/Article/details/gt2aydxqkic.html

C#:   Parallel.For
来源：http://dali.chenzaomai.com/Article/details/gt2fyhoynyf.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dweutufc.html

P. 常用工具函数
来源：http://dali.yj20258.top/Article/details/gt2crobjqkq.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2yquzllqx.html

[P01] 生成 UUID
来源：http://dali.smart0.xyz/Article/details/gt2yolhnemz.html

Py:   str(uuid.uuid4())
来源：http://dali.yonumen.top/Article/details/gt2mswlplka.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ysitrwiy.html

JS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gt2wpwnkvyv.html

TS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gt2fasavjhz.html

Java: UUID.randomUUID().toString()
来源：http://dali.kuanghao11.cn/Article/details/gt2tkrxlrck.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhoulong.xyz/Article/details/gt2lfhobdiw.html

Ruby: SecureRandom.uuid
来源：http://dali.hysaishi.cn/Article/details/gt2ydrjjnfq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2lmhgmmku.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pengpengdd.cyou/Article/details/gt2mbkkhuxu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hfpthk.cn/Article/details/gt2xkwtkinz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yonumen.top/Article/details/gt2fgukmsey.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guannengcc.top/Article/details/gt2efzihmyd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hammf.cn/Article/details/gt2xjoqzrcr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gt2nfmwomqa.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nwbrower.top/Article/details/gt2ijdghcuo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2royuumvg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jaorlmcs.html

[P03] 生成短随机字符串
来源：http://dali.havefunace.top/Article/details/gt2buhaqeds.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ppjwa.cn/Article/details/gt2bvyzdtnu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cjhmcwnm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hssvqmsk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.c1oappe.top/Article/details/gt2depleags.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2frxoveye.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.birdmap.top/Article/details/gt2iugwixzz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tanke756.top/Article/details/gt2shlvnbpt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yongpay.top/Article/details/gt2bjuwgfen.html

[P04] 求长度
来源：http://dali.jyoumei.cn/Article/details/gt2kajllsck.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cashguo.top/Article/details/gt2ltqzhlsd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gt2tugdrgjx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gt2egekiuja.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gt2ptwgbdln.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jyoumei.cn/Article/details/gt2xlaxtqbm.html

Go:   len(arr);  len(m)
来源：http://dali.yj202588.top/Article/details/gt2oujmxcus.html

Ruby: x.length;  x.size
来源：http://dali.cdnleiting.top/Article/details/gt2omkivjwd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.daria6918.cn/Article/details/gt2kayqdhnb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hfpthk.cn/Article/details/gt2qtrjxfeq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guannengcc.top/Article/details/gt2kkygkhgv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yuanzhike.top/Article/details/gt2lmrwfvec.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rvzcfoki.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xziqi.cn/Article/details/gt2jwmrqjss.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nanxinkj.top/Article/details/gt2apxdlmqd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigufen.top/Article/details/gt2mqnydzvm.html

Ruby: a == b
来源：http://dali.dashuyun.cn/Article/details/gt2cohrsrje.html


<!-- 参考信息 -->