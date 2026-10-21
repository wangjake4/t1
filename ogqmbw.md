代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gtexshimcu.html

Java: resp.statusCode()
来源：http://dali.ivvv.top/Article/details/gtfkphmikk.html

Go:   resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gtibhvqrrw.html

Ruby: resp.code.to_i
来源：http://dali.aizwys.cn/Article/details/gthppotmrh.html

C#:   (int)resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gtexbwqvze.html

[L08] 并发请求多个地址
来源：http://dali.chenlongwang.top/Article/details/gtzyttnwup.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sxryk.cn/Article/details/gtacruzffb.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258.top/Article/details/gttgoyedsu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gthpitkbzq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfexsqyoz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhengqikj.top/Article/details/gtqivghtby.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hongshengwenyu.top/Article/details/gtokzdjwpf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabowfpcl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gtgvirszub.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtrlzylskm.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenzaomai.com/Article/details/gtadiwosea.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtogflllli.html

[M01] 读取命令行参数
来源：http://dali.yangfankeji.com/Article/details/gtmgwrbdpw.html

Py:   sys.argv[1:]
来源：http://dali.guowangkeji.top/Article/details/gtherhnalx.html

PHP:  $argv;  $argc;
来源：http://dali.yuanzhike.top/Article/details/gtefbiwgcm.html

JS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gtqfvnftcp.html

TS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gtiqrspqnk.html

Java: args 数组（main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gtzzwnnset.html

Go:   os.Args[1:]
来源：http://dali.shzxlz.cn/Article/details/gtvsevqijy.html

Ruby: ARGV
来源：http://dali.cdnleiting.top/Article/details/gtlzcqwwqe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gtaftvwmmb.html

[M02] 读取环境变量
来源：http://dali.gogol.net.cn/Article/details/gtqoxuhgmn.html

Py:   os.environ.get("HOME")
来源：http://dali.havefunace.top/Article/details/gtxdzhhbbp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gthjcutvfb.html

JS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafrofdnp.html

TS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gtqvmdkxle.html

Java: System.getenv("HOME")
来源：http://dali.gzhubu.top/Article/details/gttrdqqwwq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtjdwzfgue.html

Ruby: ENV["HOME"]
来源：http://dali.aibaodan.cn/Article/details/gtuitblfni.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuanzx.com/Article/details/gtoxvqynzb.html

[M03] 执行外部命令
来源：http://dali.guannengcc.top/Article/details/gtauzfxyqe.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hywenlv.cn/Article/details/gtkifzjfeo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ybcxt.top/Article/details/gtficpiawi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gtfzdwzdla.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gtrsdjtplq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xziqi.cn/Article/details/gtbagftsru.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zycfv.cn/Article/details/gtouvrcvyf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nanxuanxn.top/Article/details/gtzcuqvtpc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.mhx1999.top/Article/details/gtdvmnyacy.html

[M04] 获取当前工作目录
来源：http://dali.ppjwa.cn/Article/details/gtwnwhkuux.html

Py:   os.getcwd()
来源：http://dali.0kj1m.cn/Article/details/gtejrxpjln.html

PHP:  getcwd();
来源：http://dali.ybcxt.top/Article/details/gtwcjplvod.html

JS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gtlyngjuuh.html

TS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gtxxypqmvv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.kuanghao11.cn/Article/details/gtzbovdikb.html

Go:   os.Getwd()
来源：http://dali.0kj1m.cn/Article/details/gtuwimoxvj.html

Ruby: Dir.pwd
来源：http://dali.yuxming.cn/Article/details/gtpkjhayut.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yangfankeji.com/Article/details/gtvkxytaxj.html

[M05] 设置退出码
来源：http://dali.0kj1m.cn/Article/details/gtuerbjafi.html

Py:   sys.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtgouigdmu.html

PHP:  exit(1);
来源：http://dali.gzhubu.top/Article/details/gtflrtbnvd.html

JS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtztnbhgpb.html

TS:   process.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtggnuymcy.html

Java: System.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtgwyxjpde.html

Go:   os.Exit(1)
来源：http://dali.ivvv.top/Article/details/gtsijlgmhq.html

Ruby: exit 1
来源：http://dali.xuetiantiany.cn/Article/details/gtxztrfdlh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjhwaotu.html

[M06] 向标准错误输出
来源：http://dali.sysykeji.top/Article/details/gtfccxvxxi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gtxshadmkn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqninwiiz.html

JS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gtdvclciho.html

TS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gtxkencsrs.html

Java: System.err.println("err")
来源：http://dali.xuanzx.com/Article/details/gtwgrbhaif.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.0kj1m.cn/Article/details/gtftpqgezi.html

Ruby: warn "err"
来源：http://dali.zhoulong.xyz/Article/details/gtxuxtllez.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtiorzpibl.html

[M07] 判断是否为主入口
来源：http://dali.gaohongyu789.top/Article/details/gtnlmbnovk.html

Py:   if __name__ == "__main__":
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvumtuth.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.316326.xyz/Article/details/gtnhgjfqig.html

JS:   require.main === module
来源：http://dali.fzhhl.top/Article/details/gtirkhmcan.html

TS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gtzimtpdlb.html

Java: public static void main(String[] args)
来源：http://dali.ivvv.top/Article/details/gtnpwrthix.html

Go:   func main()
来源：http://dali.ivvv.top/Article/details/gtddeknedx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwkykpmq.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258.top/Article/details/gtoqniqisv.html

[M08] 获取系统与运行时信息
来源：http://dali.yongpay.top/Article/details/gtslthdrly.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwazgjsl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenlongwang.top/Article/details/gtdsgzjlcq.html

JS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gtqxgzhubx.html

TS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gtlkzzewfk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258.top/Article/details/gtzgvhkvig.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnxiangtu.top/Article/details/gttywlwyzy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxinkj.top/Article/details/gtosgplmfj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.svipenyu.cn/Article/details/gtxzjlxfll.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtmynyftfp.html

N. 数据结构与算法
来源：http://dali.iojbl.cn/Article/details/gtdlbxmuxk.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtggknvksc.html

[N01] 二分查找（有序数组）
来源：http://dali.xinyue.icu/Article/details/gtsgtdzsah.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtlkaczrmj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxinkj.top/Article/details/gthmesontv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gtlrkvypeg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gtkprfbhmz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxechgkes.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tanke756.top/Article/details/gtwehvutbg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.svipenyu.cn/Article/details/gtbeidygop.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjzbxgrgk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sysykeji.top/Article/details/gtxghdhddz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gaohongyu789.top/Article/details/gtpmgbwjjk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jiagoushi.top/Article/details/gthprenqfn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gtwffmxdkc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthztooyqt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ppjwa.cn/Article/details/gtxjinlsvh.html

Go:   slices.Sort(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaofpgmsu.html

Ruby: arr.sort
来源：http://dali.xuanzx.com/Article/details/gtrrgtyfak.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.birdmap.top/Article/details/gtelrcylup.html

[N03] 快速排序（分治示例）
来源：http://dali.sxryk.cn/Article/details/gtcxfkzeoj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nwbrower.top/Article/details/gtbflluvle.html

PHP:  // 递归实现，或用 usort
来源：http://dali.birdmap.top/Article/details/gtoubrnfam.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guowangkeji.top/Article/details/gtmwyfeonu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gtdwrscqis.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.0kj1m.cn/Article/details/gtdbzuultq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hysaishi.cn/Article/details/gtacjpyazx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yvedp.cn/Article/details/gtzuytxemb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.feifeiyinyue.top/Article/details/gtccjavzlr.html

[N04] 斐波那契数列
来源：http://dali.gzhubu.top/Article/details/gtzqfvindw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtnxniqssd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.meibo888.top/Article/details/gtdcjrentu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtibifbbap.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdskygnyj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nwbrower.top/Article/details/gteqtzbigs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.smart0.xyz/Article/details/gtfkvoeqzy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gtlcjhwvyb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtbkopapuh.html

[N05] 最大公约数
来源：http://dali.jinqigufen.top/Article/details/gtgohidggg.html

Py:   math.gcd(a, b)
来源：http://dali.bjfxy.top/Article/details/gttvcftzka.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yongpay.top/Article/details/gtovwofmzp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gtpachftbx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.mhx1999.top/Article/details/gttszaeuxc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gttmmgeslg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorhviose.html

Ruby: a.gcd(b)
来源：http://dali.mhx1999.top/Article/details/gtpoxiztbl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yueranfly.top/Article/details/gtkwvefpmp.html

[N06] 判断回文字符串
来源：http://dali.shzxlz.cn/Article/details/gtfmetgnca.html

Py:   s == s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gtljesjzzj.html

PHP:  $s === strrev($s);
来源：http://dali.fengsongda.top/Article/details/gtxhcguxgf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtxkdlidma.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtwyofwziw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pengpengdd.cyou/Article/details/gtkgogfvlt.html

Go:   // 双指针从两端比较
来源：http://dali.redwolf501.top/Article/details/gtqzprsrin.html

Ruby: s == s.reverse
来源：http://dali.sweek.top/Article/details/gtqjuabisw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gzhubu.top/Article/details/gtehnyhkwz.html

[N07] 两数之和（返回下标）
来源：http://dali.yangfankeji.com/Article/details/gtjbkzdnxe.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nwbrower.top/Article/details/gtggrrpglt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnqzz.top/Article/details/gtjzeelxax.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigufen.top/Article/details/gtjzdmxwyg.html

TS:   // 手写 Map<string, number>
来源：http://dali.andypj.xyz/Article/details/gtomcgbemg.html

Java: // 手写 HashMap
来源：http://dali.jqgufenzy.top/Article/details/gtnazpqysq.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangtech.top/Article/details/gtcokwkllg.html

Ruby: // 手写 Hash
来源：http://dali.haohaochexian.top/Article/details/gtxpcviuiy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hfpthk.cn/Article/details/gtcjhzavtb.html

[N08] 生成全排列
来源：http://dali.bjfxy.top/Article/details/gtjuouhlpe.html

Py:   itertools.permutations(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghoawnov.html

PHP:  // 手写递归交换
来源：http://dali.ppjwa.cn/Article/details/gtgeiwvpbg.html

JS:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfjyxyoe.html

TS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtraazutza.html

Java: // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtrbeugkul.html

Go:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtdsrgcucv.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258888.top/Article/details/gtzavkhtjw.html

C#:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtziinjorf.html

[N09] 栈与队列
来源：http://dali.yonumen.top/Article/details/gtwnxexvuz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zycfv.cn/Article/details/gtltdtljgf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.mhx1999.top/Article/details/gtuvrwdtbv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtvehfoisg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guannengcc.top/Article/details/gteumdnjmj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tianlin.xyz/Article/details/gtmawvgnsy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jiagoushi.top/Article/details/gtdrpomtxs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gtvxtvqxcq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daria6918.cn/Article/details/gtbqpjmmtg.html

[N10] 链表节点定义
来源：http://dali.yj20258888.top/Article/details/gtwhygxsev.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fzhhl.top/Article/details/gtgjjlyaay.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xziqi.cn/Article/details/gtckyrhqzp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.bjfxy.top/Article/details/gtcfveukpi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tanke756.top/Article/details/gtiqmoqofh.html

Java: class Node { int v; Node next; }
来源：http://dali.dianchejie.cn/Article/details/gtyvmiluhl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daxiang520.top/Article/details/gtwsjibzcm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuxming.cn/Article/details/gtsmbmizcc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shzxlz.cn/Article/details/gtvwbkowqn.html

[N11] 二叉树中序遍历
来源：http://dali.0kj1m.cn/Article/details/gtfeikgwuc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sweek.top/Article/details/gtzsptnddt.html

PHP:  // 手写递归函数
来源：http://dali.zdqjudy.top/Article/details/gtodcqmqev.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gtoodelhpl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gtjwxvybzs.html

Java: // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gtbdhenucm.html

Go:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtnjeyhfok.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yonumen.top/Article/details/gtnubfhaim.html

C#:   // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gtvfuivabp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhiwuduotai.top/Article/details/gttnrcukjv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgfzy.top/Article/details/gtqcolvilk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.wangdashe.top/Article/details/gtgxnvhpov.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gtajqomvlj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gtewgqlxlq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gtzjqldqme.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guowangkeji.top/Article/details/gtpfwrprnu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gttrkychhc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ivvv.top/Article/details/gtfwykifii.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtamisevgm.html

O. 并发与异步
来源：http://dali.shangyingyoupin.top/Article/details/gtsnbanrjc.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtzucfxulk.html

[O01] 启动一个线程
来源：http://dali.guannengcc.top/Article/details/gtqhtykvxk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuxming.cn/Article/details/gtsgwslrox.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258.top/Article/details/gternhzycy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cashguo.top/Article/details/gtdlntvnmf.html

TS:   // 同 JS
来源：http://dali.haohaochexian.top/Article/details/gtbivqwxnu.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangshuangyany.cn/Article/details/gtgttbvqwq.html

Go:   go f()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcztotgrp.html

Ruby: Thread.new { f }
来源：http://dali.snrcjt.cn/Article/details/gtkgfxfyug.html

C#:   Task.Run(() => F());
来源：http://dali.feifeiyinyue.top/Article/details/gtgrrxhllm.html

[O02] 使用线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkepzalt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtslinrypa.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnrtiuuv.html

JS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gtskufzmhl.html

TS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gtfhzjundc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jianghu66.top/Article/details/gtwqzjyiok.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.svipenyu.cn/Article/details/gtifcwboza.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yueranfly.top/Article/details/gtloucygir.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.feifeiyinyue.top/Article/details/gtplxxvtnq.html

[O03] 加锁保护共享数据
来源：http://dali.xziqi.cn/Article/details/gtuoklvpga.html

Py:   with lock: shared += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcehfszup.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangdashe.top/Article/details/gtvvzsbqec.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinghuilouyu.cn/Article/details/gtdaeofvrb.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gtduwgvvpu.html

Java: synchronized (this) { shared++; }
来源：http://dali.yangfankeji.com/Article/details/gtcfretrtu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.andypj.xyz/Article/details/gtkeebsimg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pengpengdd.cyou/Article/details/gtpblzboyh.html

C#:   lock (gate) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gtghgduyfc.html

[O04] 定义异步函数并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzqpqfkd.html

Py:   async def f():⏎    await g()
来源：http://dali.yuanzhike.top/Article/details/gthgxtnchz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.kuanghao11.cn/Article/details/gtcvpbpulq.html

JS:   async function f() { await g(); }
来源：http://dali.nwbrower.top/Article/details/gtdyeqgtcz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnqzz.top/Article/details/gtjfpilmkb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnypzgqx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhengqikj.top/Article/details/gtcjeseqse.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tian-w.cn/Article/details/gtjgklnsrm.html

C#:   async Task F() { await G(); }
来源：http://dali.yuanzhike.top/Article/details/gtidittrud.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigfzy.top/Article/details/gtfjvrxyim.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhixingplan.top/Article/details/gtmsesiyen.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.316326.xyz/Article/details/gtedkgmbde.html

JS:   await Promise.all(tasks)
来源：http://dali.zycfv.cn/Article/details/gtkapsqyyk.html

TS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gtmhnjvuev.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xinyue.icu/Article/details/gtdlxucjsd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.bjfxy.top/Article/details/gtvicuengb.html

Ruby: threads.map(&:join)
来源：http://dali.hfpthk.cn/Article/details/gtnxtfowve.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tanke756.top/Article/details/gtuxqwjnof.html

[O06] 使用进程池
来源：http://dali.ppjwa.cn/Article/details/gtnyvhfihx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.aizwys.cn/Article/details/gtokftpctu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangtech.top/Article/details/gthplitsye.html

JS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gtczlvxeun.html

TS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gtvcxyltuo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhengqikj.top/Article/details/gtgkchjyvp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.0kj1m.cn/Article/details/gtiqhbvoke.html

Ruby: // fork 块
来源：http://dali.xinyue.icu/Article/details/gtbplasvxt.html

C#:   Parallel.For
来源：http://dali.gotoacloud.top/Article/details/gtbzxufdda.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gteapykxac.html

P. 常用工具函数
来源：http://dali.zdqjudy.top/Article/details/gtbqmykdnf.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtoivaxuqk.html

[P01] 生成 UUID
来源：http://dali.hongshengwenyu.top/Article/details/gtjfzugcjm.html

Py:   str(uuid.uuid4())
来源：http://dali.xziqi.cn/Article/details/gtzwhpzeze.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ybcxt.top/Article/details/gtspejlewt.html

JS:   crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gtklpyerdx.html

TS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gtzkpejlhh.html

Java: UUID.randomUUID().toString()
来源：http://dali.ppjwa.cn/Article/details/gtrtmatihz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqaljierg.html

Ruby: SecureRandom.uuid
来源：http://dali.zdqjudy.top/Article/details/gttvvbmjgz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ybcxt.top/Article/details/gtajxwvasj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zdqjudy.top/Article/details/gtlyqcnyqe.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cdnleiting.top/Article/details/gtrpjdnmtc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dashuyun.cn/Article/details/gtqzkztyhu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.fzhhl.top/Article/details/gtsyrudxaf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dashuyun.cn/Article/details/gtnicixvev.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xinyue.icu/Article/details/gthouhywib.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgufenzy.top/Article/details/gtdznawbgx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dianchejie.cn/Article/details/gtcjmgiwfq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daxiang520.top/Article/details/gtheynnffj.html

[P03] 生成短随机字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtacridswe.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yonumen.top/Article/details/gtlucjvwyd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aibaodan.cn/Article/details/gtamwzapuv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gtznqanukc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gtfhzcfqhc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sweek.top/Article/details/gtvcapgnxv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnxiangtu.top/Article/details/gtyqhchbnb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xylfe.cn/Article/details/gtxjuhwcdr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.dashuyun.cn/Article/details/gtjjdegzdk.html

[P04] 求长度
来源：http://dali.quarkkingdee.top/Article/details/gtnblwvjfr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ivvv.top/Article/details/gtxtkrqbur.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtdktuqeoa.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuetiantiany.cn/Article/details/gtaxnnibgg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daria6918.cn/Article/details/gtvvamgdvt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsaajuvo.html

Go:   len(arr);  len(m)
来源：http://dali.sxryk.cn/Article/details/gtrhaifkpi.html

Ruby: x.length;  x.size
来源：http://dali.ehwqpu.com/Article/details/gtekakrwxo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gtsroggnkv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.aizwys.cn/Article/details/gtfjxllyvx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.dashuyun.cn/Article/details/gtemkffctr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.birdmap.top/Article/details/gtjnekpzfa.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjeuxwcfp.html


<!-- 参考信息 -->