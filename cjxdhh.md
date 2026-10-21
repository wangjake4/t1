代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfzkzfaok.html

[L08] 并发请求多个地址
来源：http://dali.aizwys.cn/Article/details/gtqzpdwzwq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hongshengwenyu.top/Article/details/gtxzgvqtlm.html

PHP:  curl_multi_init() 系列
来源：http://dali.hywenlv.cn/Article/details/gtkiyiwjhb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gtsuldcups.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gtohlmapox.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.meibo888.top/Article/details/gtiuwuxzur.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ehwqpu.com/Article/details/gthtyvzskc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtooshouli.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigufen.top/Article/details/gtpoitfbas.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtvytlusge.html

M. 命令行 / 进程 / 环境
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoeabdeco.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtnodupnmf.html

[M01] 读取命令行参数
来源：http://dali.zhixingplan.top/Article/details/gtiokknxlz.html

Py:   sys.argv[1:]
来源：http://dali.pycfn.com/Article/details/gtwoswdhik.html

PHP:  $argv;  $argc;
来源：http://dali.yuanzhike.top/Article/details/gtifmlkcpm.html

JS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtlcbmwcce.html

TS:   process.argv.slice(2)
来源：http://dali.yj202588.top/Article/details/gtqoitrume.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gtzqqpicpj.html

Go:   os.Args[1:]
来源：http://dali.cucudq.cn/Article/details/gtkybqyfyr.html

Ruby: ARGV
来源：http://dali.cashguo.top/Article/details/gtcwczefke.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfrkejla.html

[M02] 读取环境变量
来源：http://dali.svipenyu.cn/Article/details/gththglhsb.html

Py:   os.environ.get("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtyverngzq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhongyouzk.top/Article/details/gtcjnhttqa.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtpapapund.html

TS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gtslnoryhm.html

Java: System.getenv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtuujanjot.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtskoaxygj.html

Ruby: ENV["HOME"]
来源：http://dali.hnxiangtu.top/Article/details/gtribnnfqn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtcrwliuiz.html

[M03] 执行外部命令
来源：http://dali.aizwys.cn/Article/details/gtnfgeznae.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xuanzx.com/Article/details/gtprekhdxi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxvpzzot.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtosoxntvs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpceayavg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.316326.xyz/Article/details/gtjagzbxdo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jiagoushi.top/Article/details/gtmsuchtaj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangshuangyany.cn/Article/details/gtqqbccunu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gtoqtzhphj.html

[M04] 获取当前工作目录
来源：http://dali.fzhhl.top/Article/details/gtfgaejvtz.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gtavpqbcvw.html

PHP:  getcwd();
来源：http://dali.jqgfzy.top/Article/details/gtkbnpukys.html

JS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gtxbxlguee.html

TS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gtpzzqlqvy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuxming.cn/Article/details/gtzeplnnhh.html

Go:   os.Getwd()
来源：http://dali.jinqigfzy.top/Article/details/gtjdajdfbv.html

Ruby: Dir.pwd
来源：http://dali.yueranfly.top/Article/details/gtonctepkz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zycfv.cn/Article/details/gteqbjyshb.html

[M05] 设置退出码
来源：http://dali.fzhhl.top/Article/details/gtmdbwbebi.html

Py:   sys.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtiiivgezn.html

PHP:  exit(1);
来源：http://dali.zycfv.cn/Article/details/gtwwpohiza.html

JS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtcqhattnu.html

TS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gthfxnnltb.html

Java: System.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtimgujcwa.html

Go:   os.Exit(1)
来源：http://dali.mhx1999.top/Article/details/gtpqdhiqnq.html

Ruby: exit 1
来源：http://dali.shzxlz.cn/Article/details/gtmixvtcar.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gaohongyu789.top/Article/details/gtzdssrrhu.html

[M06] 向标准错误输出
来源：http://dali.redwolf501.top/Article/details/gtiyombuae.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gzhubu.top/Article/details/gtsswsjldl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgufenzy.top/Article/details/gtxsimbbdu.html

JS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtsosylfmd.html

TS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gtpqlywkqq.html

Java: System.err.println("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtegcefdkz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.feifeiyinyue.top/Article/details/gtjkngkgqi.html

Ruby: warn "err"
来源：http://dali.dianchejie.cn/Article/details/gtgfsungjv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtshajtkph.html

[M07] 判断是否为主入口
来源：http://dali.cashguo.top/Article/details/gttjhyxrjv.html

Py:   if __name__ == "__main__":
来源：http://dali.316326.xyz/Article/details/gtcbiidkll.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sweek.top/Article/details/gtzrfzekps.html

JS:   require.main === module
来源：http://dali.snrcjt.cn/Article/details/gtdkiccdri.html

TS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gtkrpcuyfq.html

Java: public static void main(String[] args)
来源：http://dali.cqqwz.cn/Article/details/gtiscmaprc.html

Go:   func main()
来源：http://dali.chenzaomai.com/Article/details/gtkvuavfcy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xylfe.cn/Article/details/gtutmzsmik.html

C#:   static void Main(string[] args)
来源：http://dali.daria6918.cn/Article/details/gtkhnvfavy.html

[M08] 获取系统与运行时信息
来源：http://dali.redwolf501.top/Article/details/gtlohojodn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tanke756.top/Article/details/gtykzybshl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.9152youxi.cn/Article/details/gtjukolhua.html

JS:   process.platform;  process.version
来源：http://dali.andypj.xyz/Article/details/gtaqrxomkj.html

TS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gtzjagfwbn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jlsjyb.cn/Article/details/gtwjgnenpn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.c1oappe.top/Article/details/gtwcgkzqtw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jlsjyb.cn/Article/details/gtqjkdsnre.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dashuyun.cn/Article/details/gtubxmaacm.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtpftrmkth.html

N. 数据结构与算法
来源：http://dali.xuetiantiany.cn/Article/details/gtgxmektud.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gthqyqqbth.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxinkj.top/Article/details/gtsuukghsk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtabbfeilp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj20258.top/Article/details/gtoojwixra.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtfprsjbyl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gthwdblziy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtuqiuxnrh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gttdsbzuzd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenlongwang.top/Article/details/gteowozfnk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtrrdkcwpx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gtvaoiikjj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gtkxjpiijw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yueranfly.top/Article/details/gtqdcppscb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gtgcjbycgm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjhbhldi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gzhubu.top/Article/details/gtospxhpmc.html

Go:   slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gthinqygnl.html

Ruby: arr.sort
来源：http://dali.dianchejie.cn/Article/details/gtmdmlyrhn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.bjfxy.top/Article/details/gtxhzjfrny.html

[N03] 快速排序（分治示例）
来源：http://dali.gzhubu.top/Article/details/gtrqeqtpeq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gogol.net.cn/Article/details/gtnvsoesoo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhoulong.xyz/Article/details/gtbyvbrpho.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gtcoedbozl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gtaeiyqsao.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgfzy.top/Article/details/gtaoyvgxos.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.quarkkingdee.top/Article/details/gtmqtmijre.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.c1oappe.top/Article/details/gtcaitxwky.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gtfdplyren.html

[N04] 斐波那契数列
来源：http://dali.kuanghao11.cn/Article/details/gtofyhkcea.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gtnkhrutwn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqebkvho.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gtamiiytdw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gtihxnbxgp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gtblntdgwu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ivvv.top/Article/details/gtgewmrbyb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtlxfjvsij.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtaiatioxp.html

[N05] 最大公约数
来源：http://dali.chenlongwang.top/Article/details/gtadsbetwk.html

Py:   math.gcd(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gtulhjohwd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tian-w.cn/Article/details/gtendyqlbi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuxming.cn/Article/details/gtvvyrmvut.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gtumahwpev.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ehwqpu.com/Article/details/gtwmvapelg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxinkj.top/Article/details/gtjqknamnx.html

Ruby: a.gcd(b)
来源：http://dali.jqgfzy.top/Article/details/gtpfoyyulo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.meibo888.top/Article/details/gtukftzjko.html

[N06] 判断回文字符串
来源：http://dali.sxryk.cn/Article/details/gtdpjkfqwx.html

Py:   s == s[::-1]
来源：http://dali.yueranfly.top/Article/details/gtcgqdnbzm.html

PHP:  $s === strrev($s);
来源：http://dali.pycfn.com/Article/details/gtknfcmcsi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtxwirkpen.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtzibrjngx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.haohaochexian.top/Article/details/gtdylmyjlv.html

Go:   // 双指针从两端比较
来源：http://dali.jqgfzy.top/Article/details/gtfyrdnglm.html

Ruby: s == s.reverse
来源：http://dali.yongpay.top/Article/details/gtgstqkfqt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gtdzhdvsel.html

[N07] 两数之和（返回下标）
来源：http://dali.vqdsnc.cn/Article/details/gtovidwcys.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gogol.net.cn/Article/details/gtptdtvcwg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gotoacloud.top/Article/details/gtoqmvwgep.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpiqllskm.html

TS:   // 手写 Map<string, number>
来源：http://dali.0kj1m.cn/Article/details/gtbuetvsyu.html

Java: // 手写 HashMap
来源：http://dali.xziqi.cn/Article/details/gtrifpuysh.html

Go:   // 手写 map[int]int
来源：http://dali.cashguo.top/Article/details/gtlddilxtv.html

Ruby: // 手写 Hash
来源：http://dali.tian-w.cn/Article/details/gtwsftozep.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tianlin.xyz/Article/details/gtyvxxbpyk.html

[N08] 生成全排列
来源：http://dali.ydzc1.top/Article/details/gtooxjtily.html

Py:   itertools.permutations(arr)
来源：http://dali.xuanzx.com/Article/details/gtjhrdtepn.html

PHP:  // 手写递归交换
来源：http://dali.andypj.xyz/Article/details/gtihgxalek.html

JS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gteatgfiza.html

TS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtnufpnzqc.html

Java: // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmvkiape.html

Go:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtswufnqln.html

Ruby: arr.permutation.to_a
来源：http://dali.hnxiangtu.top/Article/details/gtrpttwdew.html

C#:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtrxbybocj.html

[N09] 栈与队列
来源：http://dali.havefunace.top/Article/details/gtziclerdn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.meibo888.top/Article/details/gtvrnqnpwu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtzoejdtzb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtvpbcjhyr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ppjwa.cn/Article/details/gtdqpmqhag.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxinkj.top/Article/details/gtruypyqef.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jqgufenzy.top/Article/details/gtrfwyqbsp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gtiqhueflq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tanke756.top/Article/details/gtdtpzopki.html

[N10] 链表节点定义
来源：http://dali.xylfe.cn/Article/details/gtcorbzyli.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhixingplan.top/Article/details/gtnaqsxuvf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.havefunace.top/Article/details/gttvmisgbj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nwbrower.top/Article/details/gtwvynrqgw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.svipenyu.cn/Article/details/gtivhdybsl.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigufen.top/Article/details/gtsnzcwlqa.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenlongwang.top/Article/details/gtdrofpsmn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jlsjyb.cn/Article/details/gtslcdlyes.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxgmkacja.html

[N11] 二叉树中序遍历
来源：http://dali.smart0.xyz/Article/details/gtdylipskq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gogol.net.cn/Article/details/gtlbzjwcze.html

PHP:  // 手写递归函数
来源：http://dali.feifeiyinyue.top/Article/details/gtwxuslrdw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gtwydmyajm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yangfankeji.com/Article/details/gtewrqjsue.html

Java: // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gtadxbxpad.html

Go:   // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtflfhfqon.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tian-w.cn/Article/details/gtuhadacow.html

C#:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gtdmqzgkna.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hywenlv.cn/Article/details/gtyrllojqw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenjidiqi.icu/Article/details/gtdyofmuxi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jqgfzy.top/Article/details/gtdnsbpzfn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtggrjajdh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ppjwa.cn/Article/details/gtoomadmpy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dashuyun.cn/Article/details/gtccvwobbs.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhyfcwqa.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zycfv.cn/Article/details/gtlvemhhjk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gtsgesolli.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtzcqdzxsa.html

O. 并发与异步
来源：http://dali.hfpthk.cn/Article/details/gtyvvzwmig.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfzfflujj.html

[O01] 启动一个线程
来源：http://dali.zhixingplan.top/Article/details/gtwxyguwua.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.kuanghao11.cn/Article/details/gtwpauzjfr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zdqjudy.top/Article/details/gtmbsytumq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zdqjudy.top/Article/details/gtblwqethb.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gtetkbyuae.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigfzy.top/Article/details/gtdbvdtdnv.html

Go:   go f()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxithpzg.html

Ruby: Thread.new { f }
来源：http://dali.zhiwuduotai.top/Article/details/gtvzmkjcib.html

C#:   Task.Run(() => F());
来源：http://dali.sufxvd.cn/Article/details/gtnvnuajcn.html

[O02] 使用线程池
来源：http://dali.jlsjyb.cn/Article/details/gtbqdecoux.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.bjfxy.top/Article/details/gtuziemqrm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shzxlz.cn/Article/details/gtpgxaxcut.html

JS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gtpizylmzo.html

TS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gtxzotwkfd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sysykeji.top/Article/details/gtbkurcrlx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangshuangyany.cn/Article/details/gtfgvkmxun.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.meibo888.top/Article/details/gthurpltjz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenjidiqi.icu/Article/details/gtvpjnuuop.html

[O03] 加锁保护共享数据
来源：http://dali.feifeiyinyue.top/Article/details/gthkmqslvj.html

Py:   with lock: shared += 1
来源：http://dali.cdnleiting.top/Article/details/gtmakpmckb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ydzc1.top/Article/details/gthyoixsce.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pengpengdd.cyou/Article/details/gtqaicaplb.html

TS:   // 同 JS
来源：http://dali.meibo888.top/Article/details/gtzgmymjti.html

Java: synchronized (this) { shared++; }
来源：http://dali.316326.xyz/Article/details/gthryaiqup.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yanxiufei.cn/Article/details/gtqxpsfsat.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shzxlz.cn/Article/details/gtkllpzdom.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhongyouzk.top/Article/details/gtwhqmiwea.html

[O04] 定义异步函数并等待
来源：http://dali.pengpengdd.cyou/Article/details/gtfjlbqcui.html

Py:   async def f():⏎    await g()
来源：http://dali.sweek.top/Article/details/gttrdjlbuz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dianchejie.cn/Article/details/gtzuzzczkw.html

JS:   async function f() { await g(); }
来源：http://dali.yueranfly.top/Article/details/gtkmmtisdm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yongpay.top/Article/details/gtlttxrhlb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsymayeyg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shzxlz.cn/Article/details/gtmsvhdnfb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zycfv.cn/Article/details/gtflgbvokq.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258.top/Article/details/gtzyvmzsck.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgfzy.top/Article/details/gtssuizduu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.smart0.xyz/Article/details/gtsgzquvcy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gtodpgsops.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gtujdyxeks.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258.top/Article/details/gtaofxkofb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.feifeiyinyue.top/Article/details/gtadxrmdnx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.havefunace.top/Article/details/gtnmasafar.html

Ruby: threads.map(&:join)
来源：http://dali.fengsongda.top/Article/details/gtlouywdsc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhoulong.xyz/Article/details/gtoptglqnf.html

[O06] 使用进程池
来源：http://dali.smart0.xyz/Article/details/gtriypvxji.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.feifeiyinyue.top/Article/details/gtqjgqdrew.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnxiangtu.top/Article/details/gtqzdynyvs.html

JS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gtkeiikfry.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258.top/Article/details/gtquajpcpq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xylfe.cn/Article/details/gtkuktskhr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yonumen.top/Article/details/gtfqasaumr.html

Ruby: // fork 块
来源：http://dali.andypj.xyz/Article/details/gtdjqdpihc.html

C#:   Parallel.For
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqdektoq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtnlygymxv.html

P. 常用工具函数
来源：http://dali.hammf.cn/Article/details/gtqqayfdsm.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gttqhlnebo.html

[P01] 生成 UUID
来源：http://dali.hnqzz.top/Article/details/gtmlfoxsgx.html

Py:   str(uuid.uuid4())
来源：http://dali.cucudq.cn/Article/details/gthiofsocc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gtgcnswnhq.html

JS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gtsgfxjipy.html

TS:   crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gtudvtcrfc.html

Java: UUID.randomUUID().toString()
来源：http://dali.aizwys.cn/Article/details/gtqxsyyjtn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.birdmap.top/Article/details/gtovmjmmhi.html

Ruby: SecureRandom.uuid
来源：http://dali.sxryk.cn/Article/details/gtzvejloos.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yuanzhike.top/Article/details/gttvwaxkhc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gogol.net.cn/Article/details/gtgkvwpcok.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hfpthk.cn/Article/details/gtzgvjlvqq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dashuyun.cn/Article/details/gtpbzieaxt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.andypj.xyz/Article/details/gttzpurmwl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.daria6918.cn/Article/details/gtmiwlbuvf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.c1oappe.top/Article/details/gtflkbsivj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fzhhl.top/Article/details/gtpvuerbmh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigufen.top/Article/details/gtxkeflnkn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.meibo888.top/Article/details/gtuzeubhgw.html

[P03] 生成短随机字符串
来源：http://dali.shzxlz.cn/Article/details/gtheybreoi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xinyue.icu/Article/details/gtohlmgcal.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.kuanghao11.cn/Article/details/gtgkqdeomm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yvedp.cn/Article/details/gtrvpfhtaa.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gttzwwkiol.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigfzy.top/Article/details/gtimkcaklm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenjidiqi.icu/Article/details/gtilmsrrll.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.pengpengdd.cyou/Article/details/gtwfcdusyt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnqzz.top/Article/details/gthzepjoak.html

[P04] 求长度
来源：http://dali.xinyue.icu/Article/details/gtmsdioxno.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhiwuduotai.top/Article/details/gtxogfwjcz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gtzxtlyyfh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sxryk.cn/Article/details/gtquikvrol.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jiagoushi.top/Article/details/gttzajglyv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.daxiang520.top/Article/details/gttntxfwtc.html

Go:   len(arr);  len(m)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvphourbr.html

Ruby: x.length;  x.size
来源：http://dali.cqqwz.cn/Article/details/gtdsntpxdl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gtlrgnzgbf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jiagoushi.top/Article/details/gtoaldjgou.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sxryk.cn/Article/details/gtlmprzxfl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.smart0.xyz/Article/details/gtipjjfuos.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ybcxt.top/Article/details/gthbuzzlkq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.c1oappe.top/Article/details/gtzhwcyjqz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nanxuanxn.top/Article/details/gtjefaplsr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aizwys.cn/Article/details/gtfleyraan.html

Ruby: a == b
来源：http://dali.vqdsnc.cn/Article/details/gtuwcmzqjy.html


<!-- 参考信息 -->