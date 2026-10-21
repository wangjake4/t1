代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gtrbtnftoo.html

[L08] 并发请求多个地址
来源：http://dali.zdqjudy.top/Article/details/gtrdzdwfdq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jlsjyb.cn/Article/details/gtdkfwxiav.html

PHP:  curl_multi_init() 系列
来源：http://dali.gogol.net.cn/Article/details/gtlgjevtkf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtwntbgmsa.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtbuzvvjvz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhongyouzk.top/Article/details/gtcksjdkyh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sweek.top/Article/details/gtjfkjvehx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuanzx.com/Article/details/gtylobocht.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yangfankeji.com/Article/details/gtqykodhri.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtiqdozvxx.html

M. 命令行 / 进程 / 环境
来源：http://dali.hongshengwenyu.top/Article/details/gtpjenfijk.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtjhrygwum.html

[M01] 读取命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gtputhrgjy.html

Py:   sys.argv[1:]
来源：http://dali.cucudq.cn/Article/details/gtgqrmzspv.html

PHP:  $argv;  $argc;
来源：http://dali.xziqi.cn/Article/details/gtvvqsggyz.html

JS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtsjevxsra.html

TS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtigvpftkh.html

Java: args 数组（main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gtbcvgwcgw.html

Go:   os.Args[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtfppwloaw.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gtqufajkeh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gtzkjdpxar.html

[M02] 读取环境变量
来源：http://dali.ehwqpu.com/Article/details/gtfkznzhtn.html

Py:   os.environ.get("HOME")
来源：http://dali.cashguo.top/Article/details/gtemtjrxtw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gtdemtoojx.html

JS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gtljzrdgkk.html

TS:   process.env.HOME
来源：http://dali.vqdsnc.cn/Article/details/gtwqeosrzy.html

Java: System.getenv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtcrbkyvea.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwlplcdzd.html

Ruby: ENV["HOME"]
来源：http://dali.dianchejie.cn/Article/details/gtzinanfct.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtumuiczqn.html

[M03] 执行外部命令
来源：http://dali.yj202588.top/Article/details/gteugqdnqk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gotoacloud.top/Article/details/gtgfyworwx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.0kj1m.cn/Article/details/gtthurlbpu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtcmpvirgw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gtugzebkwx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258.top/Article/details/gtixyimcxs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuanzhike.top/Article/details/gtwuljojlc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xinyue.icu/Article/details/gtpzasyqas.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guannengcc.top/Article/details/gtlqfvitjg.html

[M04] 获取当前工作目录
来源：http://dali.hfpthk.cn/Article/details/gtlupmfihu.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gtaxkfkqfb.html

PHP:  getcwd();
来源：http://dali.havefunace.top/Article/details/gtimplowwp.html

JS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gtrpqcxsxu.html

TS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gtnxerhoom.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hongshengwenyu.top/Article/details/gtrslrroxg.html

Go:   os.Getwd()
来源：http://dali.xinyue.icu/Article/details/gtlsqfhdrl.html

Ruby: Dir.pwd
来源：http://dali.andypj.xyz/Article/details/gtibnudhjl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sxryk.cn/Article/details/gtdqhehvrg.html

[M05] 设置退出码
来源：http://dali.jqgfzy.top/Article/details/gtybzzxdwo.html

Py:   sys.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtvlltxsph.html

PHP:  exit(1);
来源：http://dali.sysykeji.top/Article/details/gthniawkfd.html

JS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtcdajcaqk.html

TS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtggsamflt.html

Java: System.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtoazdwtbi.html

Go:   os.Exit(1)
来源：http://dali.ydzc1.top/Article/details/gtyzgezqnk.html

Ruby: exit 1
来源：http://dali.guowangkeji.top/Article/details/gtfpxozyic.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuxming.cn/Article/details/gtzyixtalb.html

[M06] 向标准错误输出
来源：http://dali.zhiwuduotai.top/Article/details/gtwlwsfmeg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.guannengcc.top/Article/details/gtihsmanig.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cheryme.top/Article/details/gtpybupjld.html

JS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztdrvvgl.html

TS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gtzzyjjhda.html

Java: System.err.println("err")
来源：http://dali.ivvv.top/Article/details/gtagwrpsea.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yvedp.cn/Article/details/gtfaceyzpm.html

Ruby: warn "err"
来源：http://dali.ybcxt.top/Article/details/gthrhnkaky.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtiersbsvw.html

[M07] 判断是否为主入口
来源：http://dali.wangshuangyany.cn/Article/details/gtjxhfhync.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgfzy.top/Article/details/gtbhdlzblf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ybcxt.top/Article/details/gtoexkvloc.html

JS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gtzczoasoy.html

TS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gtphdyxgki.html

Java: public static void main(String[] args)
来源：http://dali.chenlongwang.top/Article/details/gtogxelkxj.html

Go:   func main()
来源：http://dali.xuetiantiany.cn/Article/details/gtfnxprcti.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tanke756.top/Article/details/gteicfhars.html

C#:   static void Main(string[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzkiopsu.html

[M08] 获取系统与运行时信息
来源：http://dali.zhixingplan.top/Article/details/gtlskbjaxk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fzhhl.top/Article/details/gtieywfyfl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.0kj1m.cn/Article/details/gtijeouoma.html

JS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gttbkdvgma.html

TS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gtahmeapnm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yangfankeji.com/Article/details/gtquvrpxnj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigfzy.top/Article/details/gtuwnxlxey.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shuidangran.top/Article/details/gtzciifchr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuetiantiany.cn/Article/details/gtvkotygpr.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtykuptcfc.html

N. 数据结构与算法
来源：http://dali.vqdsnc.cn/Article/details/gtbjrjybxn.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtjqvxlelq.html

[N01] 二分查找（有序数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdecmnsvx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtgybzvgxb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jianghu66.top/Article/details/gtlguktsir.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtagygmoch.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gtcgokltrq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtuhqqarup.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtrgczolpd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dashuyun.cn/Article/details/gtfefyuquz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtgrfvbhyt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.fengsongda.top/Article/details/gteafcygmx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gtwduaakhe.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedmgccxz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezuvoawa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtfbroyyla.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gzhubu.top/Article/details/gtqrcajdyv.html

Go:   slices.Sort(arr)
来源：http://dali.0kj1m.cn/Article/details/gtstcefjwr.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gtamidjufh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gtfolhgvuc.html

[N03] 快速排序（分治示例）
来源：http://dali.quarkkingdee.top/Article/details/gtrtdnmbtb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hongshengwenyu.top/Article/details/gtswigihqa.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinqigfzy.top/Article/details/gteuwfassc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gtfdyznckj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gtkrpvrdcf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.birdmap.top/Article/details/gtwdmpcbwm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jianghu66.top/Article/details/gtfovgdctt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tianlin.xyz/Article/details/gthrpsceuf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangdashe.top/Article/details/gtvtzgvtgx.html

[N04] 斐波那契数列
来源：http://dali.xuanzx.com/Article/details/gtjpuaulfv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gtdsumebdo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sysykeji.top/Article/details/gtgpdvisvj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtntsfvsmd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhnyyrdm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.havefunace.top/Article/details/gtuvvsnbzv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nwbrower.top/Article/details/gtpgwxbvoe.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gtzzkbzcte.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtxegrwexl.html

[N05] 最大公约数
来源：http://dali.daxiang520.top/Article/details/gtzvnykouv.html

Py:   math.gcd(a, b)
来源：http://dali.pycfn.com/Article/details/gtsqllewvr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxavwsfzw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gtusglgjyg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gtocranstt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cucudq.cn/Article/details/gtxkmfaiso.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sxryk.cn/Article/details/gtjcqpmend.html

Ruby: a.gcd(b)
来源：http://dali.birdmap.top/Article/details/gtnflbmsjc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gotoacloud.top/Article/details/gtmvjchhum.html

[N06] 判断回文字符串
来源：http://dali.jiagoushi.top/Article/details/gthwgannqd.html

Py:   s == s[::-1]
来源：http://dali.ivvv.top/Article/details/gtpzmnctvr.html

PHP:  $s === strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gtuqehkqrd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtqfmipknn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtpnfburor.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhongyouzk.top/Article/details/gtvdnpzgrh.html

Go:   // 双指针从两端比较
来源：http://dali.iojbl.cn/Article/details/gtatlwxpiu.html

Ruby: s == s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtqvoicjmx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gtbxtxzcaq.html

[N07] 两数之和（返回下标）
来源：http://dali.tianlin.xyz/Article/details/gtzfgsisqg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ehwqpu.com/Article/details/gtevsnuakw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.kuanghao11.cn/Article/details/gteenpxxvi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.bjfxy.top/Article/details/gttwgyzmmq.html

TS:   // 手写 Map<string, number>
来源：http://dali.316326.xyz/Article/details/gtdkkbloyy.html

Java: // 手写 HashMap
来源：http://dali.chenjidiqi.icu/Article/details/gtkwdcboof.html

Go:   // 手写 map[int]int
来源：http://dali.aibaodan.cn/Article/details/gtcdwwbhao.html

Ruby: // 手写 Hash
来源：http://dali.jlsjyb.cn/Article/details/gtqidhqwuf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cucudq.cn/Article/details/gtfpyxtzku.html

[N08] 生成全排列
来源：http://dali.ybcxt.top/Article/details/gtzhyxdjyq.html

Py:   itertools.permutations(arr)
来源：http://dali.zhixingplan.top/Article/details/gtxlbclsfw.html

PHP:  // 手写递归交换
来源：http://dali.gogol.net.cn/Article/details/gtgnwmefay.html

JS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtidjijoey.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtjahgyuuq.html

Java: // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gthjuynetd.html

Go:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtcfcewnuv.html

Ruby: arr.permutation.to_a
来源：http://dali.hnqzz.top/Article/details/gtkwqvkgif.html

C#:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtliqisyro.html

[N09] 栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gtoybgxpca.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtdmugappz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtwegsgwzi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gtiawjjyly.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258.top/Article/details/gtqucitqtz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gtxbnsewhv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sufxvd.cn/Article/details/gtyaajybwx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtzgttpzsq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yuanzhike.top/Article/details/gtizaymnpa.html

[N10] 链表节点定义
来源：http://dali.zdqjudy.top/Article/details/gtfcorduxu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenlongwang.top/Article/details/gtcjxztsez.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aizwys.cn/Article/details/gtncltybdp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sxryk.cn/Article/details/gtqzxmvodx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daria6918.cn/Article/details/gtqlonjnex.html

Java: class Node { int v; Node next; }
来源：http://dali.vqdsnc.cn/Article/details/gtiwbfzwsn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzyojoew.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tanke756.top/Article/details/gtsfktfkix.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.birdmap.top/Article/details/gtjwgqgebf.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigufen.top/Article/details/gtgqcecqob.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daxiang520.top/Article/details/gtqwkwmdks.html

PHP:  // 手写递归函数
来源：http://dali.xziqi.cn/Article/details/gtybbqrewy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gtwiiwztbv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ybcxt.top/Article/details/gtmkwlydwv.html

Java: // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqcluyrb.html

Go:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gttsilqjza.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tanke756.top/Article/details/gtwfnwcvjx.html

C#:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtfyhedtqx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hywenlv.cn/Article/details/gtuwdarmqt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.c1oappe.top/Article/details/gtuynaclsk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gtfgckaghb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.snrcjt.cn/Article/details/gtpredgyjr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpoajhxv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gtfimcmnzn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aizwys.cn/Article/details/gticjbnvqs.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jlsjyb.cn/Article/details/gtiaxixobr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuanzx.com/Article/details/gtqtcigrrb.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtsfbpjjga.html

O. 并发与异步
来源：http://dali.haohaochexian.top/Article/details/gtljkfdhus.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtbemogafi.html

[O01] 启动一个线程
来源：http://dali.9152youxi.cn/Article/details/gtenipxdog.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.andypj.xyz/Article/details/gtnyozfgyh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xinyue.icu/Article/details/gtootgljhg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yanxiufei.cn/Article/details/gtjlmraflb.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gtzwwbtqmr.html

Java: new Thread(() -> f()).start()
来源：http://dali.ybcxt.top/Article/details/gtoouuehqc.html

Go:   go f()
来源：http://dali.bjfxy.top/Article/details/gturxsdomm.html

Ruby: Thread.new { f }
来源：http://dali.c1oappe.top/Article/details/gtvuaynwuo.html

C#:   Task.Run(() => F());
来源：http://dali.cqqwz.cn/Article/details/gtvgtcivgt.html

[O02] 使用线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqmzzqjm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tianlin.xyz/Article/details/gtvmpwoexg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgfzy.top/Article/details/gtqqomlffr.html

JS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gtrdyxrley.html

TS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gtubacojjn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hywenlv.cn/Article/details/gtragtpjic.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangdashe.top/Article/details/gtprjhmzez.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.9152youxi.cn/Article/details/gtwsvudgow.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.havefunace.top/Article/details/gtqtafkewm.html

[O03] 加锁保护共享数据
来源：http://dali.yanxiufei.cn/Article/details/gthakdmyek.html

Py:   with lock: shared += 1
来源：http://dali.yvedp.cn/Article/details/gttrxyxyhz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fengsongda.top/Article/details/gtbeylomxx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.0kj1m.cn/Article/details/gtejtxnaqc.html

TS:   // 同 JS
来源：http://dali.tian-w.cn/Article/details/gtwekbeafl.html

Java: synchronized (this) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmioiptkm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.haohaochexian.top/Article/details/gtluqqcxjt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gtmzyslzya.html

C#:   lock (gate) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gthvbjfexk.html

[O04] 定义异步函数并等待
来源：http://dali.yuxming.cn/Article/details/gtgipqnqxd.html

Py:   async def f():⏎    await g()
来源：http://dali.wangshuangyany.cn/Article/details/gtajtvbrvf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shangyingyoupin.top/Article/details/gtlbwxbtgk.html

JS:   async function f() { await g(); }
来源：http://dali.wangdashe.top/Article/details/gtbavhxkuw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tanke756.top/Article/details/gtmpywwdbi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigufen.top/Article/details/gtkqbzidks.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jlsjyb.cn/Article/details/gttqgxikyu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.0kj1m.cn/Article/details/gtidjrfwig.html

C#:   async Task F() { await G(); }
来源：http://dali.ppjwa.cn/Article/details/gtkjaccrkh.html

[O05] 并发执行并等待全部完成
来源：http://dali.gaohongyu789.top/Article/details/gtjnghbsig.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfljkwska.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hywenlv.cn/Article/details/gtoylvbgak.html

JS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gtlmdgaqqm.html

TS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gtdjgkpbow.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.wangshuangyany.cn/Article/details/gtxbdjwcmp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.snrcjt.cn/Article/details/gtqivsdwzf.html

Ruby: threads.map(&:join)
来源：http://dali.birdmap.top/Article/details/gtgsycapoh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.mhx1999.top/Article/details/gtltztwzlc.html

[O06] 使用进程池
来源：http://dali.meibo888.top/Article/details/gtczdzvwig.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.svipenyu.cn/Article/details/gtddvuvajt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhengqikj.top/Article/details/gtxehkveif.html

JS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gtkfrttdxs.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxuanxn.top/Article/details/gtvvyiavzp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.dianchejie.cn/Article/details/gtzichhsil.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cucudq.cn/Article/details/gtmtrouofb.html

Ruby: // fork 块
来源：http://dali.dianchejie.cn/Article/details/gtfwijtunx.html

C#:   Parallel.For
来源：http://dali.jinghuilouyu.cn/Article/details/gttzbxvapw.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtbnzlcqov.html

P. 常用工具函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtloycfgbg.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtoqobinog.html

[P01] 生成 UUID
来源：http://dali.wangdashe.top/Article/details/gtbsxlrtgi.html

Py:   str(uuid.uuid4())
来源：http://dali.dianchejie.cn/Article/details/gtnoysvhwx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tianlin.xyz/Article/details/gtijapopts.html

JS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtikawbpvi.html

TS:   crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gtaydqjjfv.html

Java: UUID.randomUUID().toString()
来源：http://dali.yangfankeji.com/Article/details/gtallvsicl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ppjwa.cn/Article/details/gttnpqhvnh.html

Ruby: SecureRandom.uuid
来源：http://dali.dashuyun.cn/Article/details/gtfshxppva.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yongpay.top/Article/details/gtfgapfvmy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cqqwz.cn/Article/details/gtonhvnzsh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cashguo.top/Article/details/gthsihlcng.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.c1oappe.top/Article/details/gtxufnucif.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hywenlv.cn/Article/details/gtmidybagt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tanke756.top/Article/details/gtqyjglcjr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtqjwkqdru.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.guowangkeji.top/Article/details/gtefjveska.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ppjwa.cn/Article/details/gtkcsmcdlw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.andypj.xyz/Article/details/gtktmnrqga.html

[P03] 生成短随机字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztnmflze.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.vqdsnc.cn/Article/details/gtumbhfghr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj20258.top/Article/details/gtdmgekwrq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hfpthk.cn/Article/details/gtthelrpry.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cucudq.cn/Article/details/gtmolhtowj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.snrcjt.cn/Article/details/gtnaygfgyv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhengqikj.top/Article/details/gtjwgrvrgb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.svipenyu.cn/Article/details/gtrxpppxrr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ppjwa.cn/Article/details/gtqjqcgulx.html

[P04] 求长度
来源：http://dali.daxiang520.top/Article/details/gthkilecyj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgufenzy.top/Article/details/gtfpjlrvar.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzvjainm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenzaomai.com/Article/details/gtdpqnhbvd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gtjlctgugo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj202588.top/Article/details/gtkpschhnf.html

Go:   len(arr);  len(m)
来源：http://dali.zhengqikj.top/Article/details/gtkjugqcjo.html

Ruby: x.length;  x.size
来源：http://dali.daria6918.cn/Article/details/gtdapthfhj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cdnleiting.top/Article/details/gtlfukknpr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dianchejie.cn/Article/details/gtzbpuoysj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ehwqpu.com/Article/details/gtnhravzuz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenzaomai.com/Article/details/gtrnixdizk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zdqjudy.top/Article/details/gtopjdsigc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xziqi.cn/Article/details/gtxcgnbppo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.mhx1999.top/Article/details/gtbfleuakr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gtvyqlvcfn.html

Ruby: a == b
来源：http://dali.wangdashe.top/Article/details/gtlcvzfqba.html


<!-- 参考信息 -->