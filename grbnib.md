代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gtzbbdsxik.html

Java: resp.statusCode()
来源：http://dali.yongpay.top/Article/details/gthllsnyrr.html

Go:   resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gtzmyzifwi.html

Ruby: resp.code.to_i
来源：http://dali.zhixingplan.top/Article/details/gtlgipndta.html

C#:   (int)resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gtaczoyjoo.html

[L08] 并发请求多个地址
来源：http://dali.jyoumei.cn/Article/details/gtssgmduiw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yanxiufei.cn/Article/details/gtgnesevsi.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenzaomai.com/Article/details/gtzwtdxoxe.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gtrjskxrtm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gtancagrln.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jianghu66.top/Article/details/gtcwhpohyt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cheryme.top/Article/details/gtgdpooqlg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigufen.top/Article/details/gtrsigwbhc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gzhubu.top/Article/details/gtzzfqnnkq.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtkvymnuwl.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefrvmlcr.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtehppygmb.html

[M01] 读取命令行参数
来源：http://dali.sufxvd.cn/Article/details/gtmgsdwphh.html

Py:   sys.argv[1:]
来源：http://dali.sufxvd.cn/Article/details/gtkybgnpab.html

PHP:  $argv;  $argc;
来源：http://dali.aibaodan.cn/Article/details/gtpokzwgdu.html

JS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gtvqkomjqa.html

TS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gthgfobuqt.html

Java: args 数组（main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gtjdgwcbnz.html

Go:   os.Args[1:]
来源：http://dali.zycfv.cn/Article/details/gthfhtfxqs.html

Ruby: ARGV
来源：http://dali.c1oappe.top/Article/details/gttywnwpsm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtfjecceeh.html

[M02] 读取环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtiehmvgeq.html

Py:   os.environ.get("HOME")
来源：http://dali.zycfv.cn/Article/details/gtrcsysvuh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gtnihimjhv.html

JS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gtltdzprqh.html

TS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtpvionprh.html

Java: System.getenv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gthqyutzrs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtzuuevxfb.html

Ruby: ENV["HOME"]
来源：http://dali.yvedp.cn/Article/details/gtbtyqqdhc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gttytjhttl.html

[M03] 执行外部命令
来源：http://dali.aizwys.cn/Article/details/gtzyajhils.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxuanxn.top/Article/details/gtwlgcltgx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.c1oappe.top/Article/details/gttbqibjxs.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gtuxippkjt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gtmcxxdpwm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.haohaochexian.top/Article/details/gtldahoyor.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258888.top/Article/details/gtcsdwnjia.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nanxuanxn.top/Article/details/gtwxzdpzqy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhiwuduotai.top/Article/details/gtxnpvhkyt.html

[M04] 获取当前工作目录
来源：http://dali.sufxvd.cn/Article/details/gtkyuzuzfl.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gtvxtpoqob.html

PHP:  getcwd();
来源：http://dali.bjfxy.top/Article/details/gtabispgei.html

JS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gtjirdmyer.html

TS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gtfksooiyu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gtxvmgonnc.html

Go:   os.Getwd()
来源：http://dali.yuxming.cn/Article/details/gtkigqtzyw.html

Ruby: Dir.pwd
来源：http://dali.sxryk.cn/Article/details/gtzyueoxab.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xinyue.icu/Article/details/gtxjdjbwiy.html

[M05] 设置退出码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbfdfygl.html

Py:   sys.exit(1)
来源：http://dali.yonumen.top/Article/details/gtqydmujnx.html

PHP:  exit(1);
来源：http://dali.xuetiantiany.cn/Article/details/gtvpsoqxvb.html

JS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gttebzjnqy.html

TS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtmqkeoerg.html

Java: System.exit(1)
来源：http://dali.yongpay.top/Article/details/gtnsbmfxgg.html

Go:   os.Exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtotzvaztw.html

Ruby: exit 1
来源：http://dali.shuidangran.top/Article/details/gturlfyibj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gogol.net.cn/Article/details/gtiofrsojf.html

[M06] 向标准错误输出
来源：http://dali.ivvv.top/Article/details/gtpmrfwdac.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gtbzqoaznf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daria6918.cn/Article/details/gthwkcivyo.html

JS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gtgtlhvewr.html

TS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gtllisxfhj.html

Java: System.err.println("err")
来源：http://dali.snrcjt.cn/Article/details/gtiyfntsqh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhiwuduotai.top/Article/details/gthpddhvit.html

Ruby: warn "err"
来源：http://dali.c1oappe.top/Article/details/gtjdgusxeq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.c1oappe.top/Article/details/gtcdyynooh.html

[M07] 判断是否为主入口
来源：http://dali.jlsjyb.cn/Article/details/gtxhgmovbb.html

Py:   if __name__ == "__main__":
来源：http://dali.dashuyun.cn/Article/details/gtwhysawch.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.iojbl.cn/Article/details/gtvkiwyoue.html

JS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gtadofjqbq.html

TS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gththiwdjg.html

Java: public static void main(String[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gtnkkwetab.html

Go:   func main()
来源：http://dali.zhixingplan.top/Article/details/gtugdcqrsu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangtech.top/Article/details/gttnyemkpt.html

C#:   static void Main(string[] args)
来源：http://dali.sweek.top/Article/details/gtpybwhmzi.html

[M08] 获取系统与运行时信息
来源：http://dali.chenjidiqi.icu/Article/details/gtvtpokjvy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.havefunace.top/Article/details/gtrlywjusj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daria6918.cn/Article/details/gtmmlgcyzc.html

JS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gtftbivknk.html

TS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gtwslpxgeb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jyoumei.cn/Article/details/gtsedqaqga.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.c1oappe.top/Article/details/gtwkcdhbwr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.316326.xyz/Article/details/gtsfvfvjac.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.feifeiyinyue.top/Article/details/gtklmspydu.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtydncevko.html

N. 数据结构与算法
来源：http://dali.ehwqpu.com/Article/details/gtrbpslhbs.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtgxoyibvs.html

[N01] 二分查找（有序数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxivgsvo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj20258888.top/Article/details/gteejoqjxj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtmygbfjca.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gtsggioyef.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtinezsrkg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtcaqxbhww.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtfmdvybiu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aizwys.cn/Article/details/gtfvmwccvw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtcorytlub.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xinyue.icu/Article/details/gtwiojrgta.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gtbcsymvuf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ybcxt.top/Article/details/gtexbwrrmc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gtoaxvbjht.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gtbkwaycmj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daxiang520.top/Article/details/gtnqficrdz.html

Go:   slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gtgooeizge.html

Ruby: arr.sort
来源：http://dali.jianghu66.top/Article/details/gttjnqkpyh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aizwys.cn/Article/details/gtudjkgubu.html

[N03] 快速排序（分治示例）
来源：http://dali.jiagoushi.top/Article/details/gtdimsbwdp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.haohaochexian.top/Article/details/gtgmqzbgyk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhengqikj.top/Article/details/gtnuhxrisz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gtlcumerrq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gtnohhnleb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.mhx1999.top/Article/details/gtcdmpqtbb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.andypj.xyz/Article/details/gtotyjtsin.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jqgufenzy.top/Article/details/gtdqrftfkc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenlongwang.top/Article/details/gtzxgnnsos.html

[N04] 斐波那契数列
来源：http://dali.yueranfly.top/Article/details/gtqfkplzwq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ehwqpu.com/Article/details/gtzlterrjp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.wangdashe.top/Article/details/gtbfmfghvx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtoxjfkkmf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtaimskijo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gtgvjpmahi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yonumen.top/Article/details/gtfbyqgggf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.fengsongda.top/Article/details/gtomzmvals.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gtyhklkzsi.html

[N05] 最大公约数
来源：http://dali.ybcxt.top/Article/details/gtenckqrjr.html

Py:   math.gcd(a, b)
来源：http://dali.xinyue.icu/Article/details/gtklcshdyq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuxming.cn/Article/details/gtusjjccic.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gttqtmvuzo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aibaodan.cn/Article/details/gtbxmcqxlk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ybcxt.top/Article/details/gtlwlcgqzr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ybcxt.top/Article/details/gtmfqykhxl.html

Ruby: a.gcd(b)
来源：http://dali.jianghu66.top/Article/details/gtnnknmfvy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zdqjudy.top/Article/details/gtovywkiyo.html

[N06] 判断回文字符串
来源：http://dali.guannengcc.top/Article/details/gtoeadnpqx.html

Py:   s == s[::-1]
来源：http://dali.iojbl.cn/Article/details/gtejykafkm.html

PHP:  $s === strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gtcdlrromg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtahfuikao.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtmczkjdch.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jlsjyb.cn/Article/details/gtaulrccvs.html

Go:   // 双指针从两端比较
来源：http://dali.fzhhl.top/Article/details/gtzqkimwit.html

Ruby: s == s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtvxrpjohg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gogol.net.cn/Article/details/gtwhtwakxe.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258.top/Article/details/gttuwwkuuy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.mhx1999.top/Article/details/gtevdbdzoq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ydzc1.top/Article/details/gtlsenyass.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xuetiantiany.cn/Article/details/gtacxpcvgq.html

TS:   // 手写 Map<string, number>
来源：http://dali.xziqi.cn/Article/details/gtlinrqfxs.html

Java: // 手写 HashMap
来源：http://dali.yueranfly.top/Article/details/gtfizktkpa.html

Go:   // 手写 map[int]int
来源：http://dali.svipenyu.cn/Article/details/gttyamjegp.html

Ruby: // 手写 Hash
来源：http://dali.smart0.xyz/Article/details/gtsjhtizfj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zycfv.cn/Article/details/gtakvjgtsr.html

[N08] 生成全排列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpafahzj.html

Py:   itertools.permutations(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttflyfgqn.html

PHP:  // 手写递归交换
来源：http://dali.jinqigfzy.top/Article/details/gtbagyqhjh.html

JS:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gttrweknfv.html

TS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtlqmhfbsd.html

Java: // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtyxjvtnaj.html

Go:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtvzrgvvqe.html

Ruby: arr.permutation.to_a
来源：http://dali.snrcjt.cn/Article/details/gtkonkexch.html

C#:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtsxlynqwh.html

[N09] 栈与队列
来源：http://dali.ivvv.top/Article/details/gtzxaqjpop.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yongpay.top/Article/details/gtlhgwmxjx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gttxqsriva.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtgelwiafj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbinuffun.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gaohongyu789.top/Article/details/gtpyzbnswy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hywenlv.cn/Article/details/gtyxgbemkz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtivydlhvy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dianchejie.cn/Article/details/gtioueqvjq.html

[N10] 链表节点定义
来源：http://dali.shangyingyoupin.top/Article/details/gtzvxfjqoe.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yanxiufei.cn/Article/details/gtspkbgynl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cheryme.top/Article/details/gtuuvavmsi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefelsyvf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.havefunace.top/Article/details/gtunzrwavb.html

Java: class Node { int v; Node next; }
来源：http://dali.xuanzx.com/Article/details/gtiokeknej.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxhgsfkt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sweek.top/Article/details/gtvtlfybho.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xuanzx.com/Article/details/gtponbotza.html

[N11] 二叉树中序遍历
来源：http://dali.zycfv.cn/Article/details/gtpalniljl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.smart0.xyz/Article/details/gtrevkejtr.html

PHP:  // 手写递归函数
来源：http://dali.hfpthk.cn/Article/details/gtownpvhor.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gtuiorohyi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gtcwgfbnvm.html

Java: // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gtthqyqama.html

Go:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpajvwxza.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shzxlz.cn/Article/details/gtgckljkme.html

C#:   // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gtpmoojsut.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yuxming.cn/Article/details/gtowwzlbwr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ydzc1.top/Article/details/gtxdeqoiaj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yvedp.cn/Article/details/gtzwyrnvhf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gtykdmusjz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gtwdhetnjo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gtywsvglsy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.haohaochexian.top/Article/details/gtasfdwasl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gotoacloud.top/Article/details/gtjjpqepsd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gtpusnwzhf.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtrvbqsusd.html

O. 并发与异步
来源：http://dali.xinyue.icu/Article/details/gtkzwptsvt.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtjfnklriy.html

[O01] 启动一个线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvagrcsxk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ppjwa.cn/Article/details/gtweakhpxh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yongpay.top/Article/details/gtgyojvsqz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zycfv.cn/Article/details/gtkedspdli.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gtdiuztwba.html

Java: new Thread(() -> f()).start()
来源：http://dali.gotoacloud.top/Article/details/gtpbqicubd.html

Go:   go f()
来源：http://dali.aizwys.cn/Article/details/gtwvtigmrp.html

Ruby: Thread.new { f }
来源：http://dali.sufxvd.cn/Article/details/gtfjtubjfj.html

C#:   Task.Run(() => F());
来源：http://dali.hysaishi.cn/Article/details/gtymttvdhg.html

[O02] 使用线程池
来源：http://dali.gzhubu.top/Article/details/gtugdqkiew.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigfzy.top/Article/details/gtiptwadsn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ybcxt.top/Article/details/gtvfeuhtbx.html

JS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteubijrkp.html

TS:   // worker_threads 线程池
来源：http://dali.jlsjyb.cn/Article/details/gtrvjypgxw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.feifeiyinyue.top/Article/details/gtnmlxlpuo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yongpay.top/Article/details/gtkcchzgxe.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gtdnvuwqrm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jiagoushi.top/Article/details/gturxitsed.html

[O03] 加锁保护共享数据
来源：http://dali.zhoulong.xyz/Article/details/gtanimtrfs.html

Py:   with lock: shared += 1
来源：http://dali.hnxiangtu.top/Article/details/gteuxpfmji.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ybcxt.top/Article/details/gtqoupuzwg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hongshengwenyu.top/Article/details/gtnthzlyqs.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gtuhwblnyn.html

Java: synchronized (this) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gttpwxnmku.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.iojbl.cn/Article/details/gthvtdzznt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yangfankeji.com/Article/details/gtwjulopnp.html

C#:   lock (gate) { shared++; }
来源：http://dali.wangshuangyany.cn/Article/details/gthtvbnowq.html

[O04] 定义异步函数并等待
来源：http://dali.wangshuangyany.cn/Article/details/gtikdxurof.html

Py:   async def f():⏎    await g()
来源：http://dali.dashuyun.cn/Article/details/gteblnesjr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangdashe.top/Article/details/gtobvapsyq.html

JS:   async function f() { await g(); }
来源：http://dali.aibaodan.cn/Article/details/gtxyfrukcy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj202588.top/Article/details/gtacyijlur.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jqgfzy.top/Article/details/gtuzsjnxju.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuetiantiany.cn/Article/details/gtcrhnehye.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shuidangran.top/Article/details/gteqathzpy.html

C#:   async Task F() { await G(); }
来源：http://dali.shzxlz.cn/Article/details/gtpbntgprq.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgfzy.top/Article/details/gtgyogluad.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj202588.top/Article/details/gtvybncvup.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.wangshuangyany.cn/Article/details/gtxtfwzczq.html

JS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdymbteax.html

TS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gtnzxzognh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hammf.cn/Article/details/gtgirtftoy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsnmakdtw.html

Ruby: threads.map(&:join)
来源：http://dali.zycfv.cn/Article/details/gttvwbnkxb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yanxiufei.cn/Article/details/gtugktkshf.html

[O06] 使用进程池
来源：http://dali.birdmap.top/Article/details/gtpzfkavig.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zycfv.cn/Article/details/gtflnypsas.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cdnleiting.top/Article/details/gtvirmgqxu.html

JS:   // child_process / cluster 模块
来源：http://dali.xziqi.cn/Article/details/gtqbemggar.html

TS:   // child_process / cluster 模块
来源：http://dali.fzhhl.top/Article/details/gtbtvrnmoo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hysaishi.cn/Article/details/gtkshxryhc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yangfankeji.com/Article/details/gteauknjha.html

Ruby: // fork 块
来源：http://dali.hammf.cn/Article/details/gtfinstngb.html

C#:   Parallel.For
来源：http://dali.gogol.net.cn/Article/details/gtiugeyeeq.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtlqrrosot.html

P. 常用工具函数
来源：http://dali.zycfv.cn/Article/details/gtnkzqngfq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtbjxnxvfd.html

[P01] 生成 UUID
来源：http://dali.shanyushiyangtech.top/Article/details/gtjddyhtvp.html

Py:   str(uuid.uuid4())
来源：http://dali.c1oappe.top/Article/details/gttxdupwzl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.haohaochexian.top/Article/details/gtnbfnqfzi.html

JS:   crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gtgzdeiqlv.html

TS:   crypto.randomUUID()
来源：http://dali.yj20258.top/Article/details/gtwhwbwgrm.html

Java: UUID.randomUUID().toString()
来源：http://dali.tanke756.top/Article/details/gtwacnxobg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.snrcjt.cn/Article/details/gtlciraoud.html

Ruby: SecureRandom.uuid
来源：http://dali.vqdsnc.cn/Article/details/gtqhfzfihb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhengqikj.top/Article/details/gtomlfjihq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nwbrower.top/Article/details/gtrxrwarqp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cdnleiting.top/Article/details/gtdhzuiwgu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gogol.net.cn/Article/details/gtlyeawmyu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jiagoushi.top/Article/details/gtkrarqvmr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ybcxt.top/Article/details/gtrtejgbub.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hammf.cn/Article/details/gtelxldfuj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hnxiangtu.top/Article/details/gtwayesrhq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigfzy.top/Article/details/gtslrkzgkx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sufxvd.cn/Article/details/gteiiquaij.html

[P03] 生成短随机字符串
来源：http://dali.vqdsnc.cn/Article/details/gtbxhmmdkk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gzhubu.top/Article/details/gtqacjsjpg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnqzz.top/Article/details/gthjigacwc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.mhx1999.top/Article/details/gtgfmheolf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gttrhtimcy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yanxiufei.cn/Article/details/gtvblzmdbb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenjidiqi.icu/Article/details/gtycldthsy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.guowangkeji.top/Article/details/gtcdogzrzz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daxiang520.top/Article/details/gtbkcyzkhq.html

[P04] 求长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrziwcks.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nanxuanxn.top/Article/details/gtzhxdzskm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtdnlklrep.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xinyue.icu/Article/details/gtimyfrcuz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqwezgis.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gzhubu.top/Article/details/gtrhhpioly.html

Go:   len(arr);  len(m)
来源：http://dali.sufxvd.cn/Article/details/gtkapzvrnq.html

Ruby: x.length;  x.size
来源：http://dali.hongshengwenyu.top/Article/details/gttjzyhvdo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ppjwa.cn/Article/details/gtwqsqzkts.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinghuilouyu.cn/Article/details/gtydotvsmt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hywenlv.cn/Article/details/gthvqkkjof.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhengqikj.top/Article/details/gtavlouupl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sysykeji.top/Article/details/gtsjkvnxpw.html


<!-- 参考信息 -->