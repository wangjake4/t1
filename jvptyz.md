代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gthxdcdzjk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gthffiekan.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yvedp.cn/Article/details/gtqtxdhbzd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqeqpserd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.havefunace.top/Article/details/gtfqwwuaxi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtiqulpjko.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtvulrendg.html

M. 命令行 / 进程 / 环境
来源：http://dali.yuxming.cn/Article/details/gtdyjxolam.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtmbevxtjl.html

[M01] 读取命令行参数
来源：http://dali.ivvv.top/Article/details/gteowpmbat.html

Py:   sys.argv[1:]
来源：http://dali.svipenyu.cn/Article/details/gtoqbkvkdf.html

PHP:  $argv;  $argc;
来源：http://dali.daxiang520.top/Article/details/gteqkebzqz.html

JS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gtjserhgqg.html

TS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gthmfsdzwk.html

Java: args 数组（main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gtserslbnr.html

Go:   os.Args[1:]
来源：http://dali.redwolf501.top/Article/details/gtattkpovl.html

Ruby: ARGV
来源：http://dali.dianchejie.cn/Article/details/gtjqygjelb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gtpfulofvq.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gtyjijijwe.html

Py:   os.environ.get("HOME")
来源：http://dali.ivvv.top/Article/details/gtpdbuczhk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtkntotphl.html

JS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gtuadkhxkf.html

TS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gtznjkrowy.html

Java: System.getenv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuaglghjg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yonumen.top/Article/details/gtirxzpqhv.html

Ruby: ENV["HOME"]
来源：http://dali.vqdsnc.cn/Article/details/gtzpqkmfir.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtexinqzpq.html

[M03] 执行外部命令
来源：http://dali.daxiang520.top/Article/details/gtkpthbvbr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fzhhl.top/Article/details/gtxjlklgxs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258.top/Article/details/gtgmsbdqei.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gtwpphibtz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gtwsfaaoiz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gogol.net.cn/Article/details/gtkgqzkckk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sweek.top/Article/details/gtumrvrnml.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.birdmap.top/Article/details/gtuwkjyeba.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sufxvd.cn/Article/details/gtbweobvup.html

[M04] 获取当前工作目录
来源：http://dali.yj202588.top/Article/details/gtblqqqqwj.html

Py:   os.getcwd()
来源：http://dali.shuidangran.top/Article/details/gtscwwtufb.html

PHP:  getcwd();
来源：http://dali.wangshuangyany.cn/Article/details/gtxxigorlv.html

JS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gtnxsvqtdw.html

TS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtbbrvotzc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jyoumei.cn/Article/details/gtmcemdgwq.html

Go:   os.Getwd()
来源：http://dali.bjfxy.top/Article/details/gtiljmrybq.html

Ruby: Dir.pwd
来源：http://dali.birdmap.top/Article/details/gtphlkkwgi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.andypj.xyz/Article/details/gtdfyayvut.html

[M05] 设置退出码
来源：http://dali.aizwys.cn/Article/details/gtxblkzupv.html

Py:   sys.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtdnzxlbnq.html

PHP:  exit(1);
来源：http://dali.sweek.top/Article/details/gtatiiuacf.html

JS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtqtothwfq.html

TS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtsopjrjur.html

Java: System.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtsnfvxukz.html

Go:   os.Exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtitzjmevs.html

Ruby: exit 1
来源：http://dali.yuanzhike.top/Article/details/gtmnnlwtff.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dashuyun.cn/Article/details/gtqqphmqwi.html

[M06] 向标准错误输出
来源：http://dali.bjfxy.top/Article/details/gtecwhpujd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gtfdyrdcex.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.316326.xyz/Article/details/gtvalwgxzr.html

JS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gtxhmmamzp.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtxrvdrdfl.html

Java: System.err.println("err")
来源：http://dali.xylfe.cn/Article/details/gtuyqfighc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sxryk.cn/Article/details/gtspcwqmll.html

Ruby: warn "err"
来源：http://dali.zhiwuduotai.top/Article/details/gtmyhgzgwt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tian-w.cn/Article/details/gtkcjzgpds.html

[M07] 判断是否为主入口
来源：http://dali.andypj.xyz/Article/details/gtxfsqnrrh.html

Py:   if __name__ == "__main__":
来源：http://dali.ybcxt.top/Article/details/gtunmvoopb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hysaishi.cn/Article/details/gtckwwgrkh.html

JS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gtivxfrmdo.html

TS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gtevxcmznz.html

Java: public static void main(String[] args)
来源：http://dali.quarkkingdee.top/Article/details/gtbshctypa.html

Go:   func main()
来源：http://dali.zdqjudy.top/Article/details/gtajcvddem.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yanxiufei.cn/Article/details/gtvdxjwgqs.html

C#:   static void Main(string[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gtlatywwgu.html

[M08] 获取系统与运行时信息
来源：http://dali.gaohongyu789.top/Article/details/gtuppzgtot.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dianchejie.cn/Article/details/gtlddlymdy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yvedp.cn/Article/details/gtpuqgjgfj.html

JS:   process.platform;  process.version
来源：http://dali.yvedp.cn/Article/details/gtqiujnwde.html

TS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gtprlekopn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guannengcc.top/Article/details/gtdkasxgtf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daria6918.cn/Article/details/gtuzedlcov.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xuetiantiany.cn/Article/details/gtsrdnvbqm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.316326.xyz/Article/details/gtdtxgkjzm.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtehvultez.html

N. 数据结构与算法
来源：http://dali.nanxinkj.top/Article/details/gtlhkeytmy.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtnsxldney.html

[N01] 二分查找（有序数组）
来源：http://dali.hnqzz.top/Article/details/gtwbhtvebq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtzvapdhri.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtcumydfgg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gtyvoysrkr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtpzxeedck.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtbjqeibup.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj20258.top/Article/details/gtyaqgguco.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkimlxlun.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gthxfhoepo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigufen.top/Article/details/gtydomtnlm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gtfrfjkjme.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtpknztgrd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtbqdxroyv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtzaoazrpe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xylfe.cn/Article/details/gtacmcxsiz.html

Go:   slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gtvpjxwraq.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gtzrdaexoa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpijgcae.html

[N03] 快速排序（分治示例）
来源：http://dali.gogol.net.cn/Article/details/gtyknsojby.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nanxinkj.top/Article/details/gttgcskxxk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.bjfxy.top/Article/details/gtbyfcgbok.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gtmzmxsdvo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gtjxadefgz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jlsjyb.cn/Article/details/gtviumowqe.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fengsongda.top/Article/details/gtrtgwkwrt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tianlin.xyz/Article/details/gtojtqrzjs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgfzy.top/Article/details/gtmccvtyen.html

[N04] 斐波那契数列
来源：http://dali.guannengcc.top/Article/details/gtjpdinnps.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hywenlv.cn/Article/details/gtpfiihmqj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gtsnbnqofe.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtzobqdwso.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gtwojlcbjv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nwbrower.top/Article/details/gtanvworzm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sysykeji.top/Article/details/gtpfmoewmp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtwptwvrpn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gtsukcekra.html

[N05] 最大公约数
来源：http://dali.shuidangran.top/Article/details/gtczsxswer.html

Py:   math.gcd(a, b)
来源：http://dali.cdnleiting.top/Article/details/gtxrhbynql.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cashguo.top/Article/details/gtijvpjvxn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gtaickpvgx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gteamcuwxp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yueranfly.top/Article/details/gtcxtgwinv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.birdmap.top/Article/details/gtgbmxzbnu.html

Ruby: a.gcd(b)
来源：http://dali.jinqigufen.top/Article/details/gtxucostge.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jiagoushi.top/Article/details/gtckjorfrh.html

[N06] 判断回文字符串
来源：http://dali.hnqzz.top/Article/details/gtlmwqmgff.html

Py:   s == s[::-1]
来源：http://dali.ybcxt.top/Article/details/gtfwbdwbau.html

PHP:  $s === strrev($s);
来源：http://dali.tian-w.cn/Article/details/gthlzgpjnm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtqwjxybyq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtzovtplkc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.haohaochexian.top/Article/details/gtjtqpmgol.html

Go:   // 双指针从两端比较
来源：http://dali.tian-w.cn/Article/details/gtpqtznroq.html

Ruby: s == s.reverse
来源：http://dali.yuanzhike.top/Article/details/gtgnmprdrp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gtluombrrt.html

[N07] 两数之和（返回下标）
来源：http://dali.chenlongwang.top/Article/details/gtftuuarnq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xinyue.icu/Article/details/gtmriogckw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgfzy.top/Article/details/gtklaikbfe.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.c1oappe.top/Article/details/gttltxhhur.html

TS:   // 手写 Map<string, number>
来源：http://dali.hysaishi.cn/Article/details/gtbpvfqvhs.html

Java: // 手写 HashMap
来源：http://dali.dianchejie.cn/Article/details/gtikdajcsu.html

Go:   // 手写 map[int]int
来源：http://dali.guannengcc.top/Article/details/gtobakmdyn.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxyjwvdu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.feifeiyinyue.top/Article/details/gtoqqpayub.html

[N08] 生成全排列
来源：http://dali.iojbl.cn/Article/details/gtvjdudzld.html

Py:   itertools.permutations(arr)
来源：http://dali.xziqi.cn/Article/details/gtehxjdayc.html

PHP:  // 手写递归交换
来源：http://dali.tianlin.xyz/Article/details/gtbpucuxmc.html

JS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtnjdgivlk.html

TS:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtylqvocgq.html

Java: // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtfarknwhb.html

Go:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtwtqfbodg.html

Ruby: arr.permutation.to_a
来源：http://dali.ydzc1.top/Article/details/gtwttfhojw.html

C#:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtbydymeit.html

[N09] 栈与队列
来源：http://dali.ybcxt.top/Article/details/gtxdklcmgn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gttofyzpjp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xziqi.cn/Article/details/gtnkkpjkwp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtivdaxron.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aibaodan.cn/Article/details/gtoqlpnbdx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.svipenyu.cn/Article/details/gtxugfxdtg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fengsongda.top/Article/details/gtttxlolwv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gtncpzddgn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jianghu66.top/Article/details/gtcchytscg.html

[N10] 链表节点定义
来源：http://dali.jinqigufen.top/Article/details/gtedlnqrim.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucijxujz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.daria6918.cn/Article/details/gtpiouxoxp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvtgybjg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gaohongyu789.top/Article/details/gtoibmyxcg.html

Java: class Node { int v; Node next; }
来源：http://dali.yongpay.top/Article/details/gtvznfwakz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhixingplan.top/Article/details/gtjbwvwlom.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhiwuduotai.top/Article/details/gtxhcmbwyq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ybcxt.top/Article/details/gtntrohcdx.html

[N11] 二叉树中序遍历
来源：http://dali.birdmap.top/Article/details/gtrurtxxjs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.snrcjt.cn/Article/details/gtypuurzva.html

PHP:  // 手写递归函数
来源：http://dali.zhongyouzk.top/Article/details/gtpzscjfnf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gtuesdpaij.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gtgktcnbmu.html

Java: // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtllzyjhqo.html

Go:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtuzvoigkk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenjidiqi.icu/Article/details/gthwezjmvl.html

C#:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtitbxymef.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258888.top/Article/details/gtnmxsctau.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.kuanghao11.cn/Article/details/gtepkfsdsh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cucudq.cn/Article/details/gtxlwauept.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gthydgchob.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gtbhhrchtb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gtfuonpdib.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.redwolf501.top/Article/details/gtxjpvxbwy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ppjwa.cn/Article/details/gtpcikutrr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gtpsohahal.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtlybjrmpy.html

O. 并发与异步
来源：http://dali.snrcjt.cn/Article/details/gtngeuzmho.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtbrzsvmjj.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gtoxhswrjc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuanzhike.top/Article/details/gtusroboqk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xziqi.cn/Article/details/gtcooqdbmt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jiagoushi.top/Article/details/gtubzlvava.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gtmxsiaaml.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuanzhike.top/Article/details/gtpjsswkwm.html

Go:   go f()
来源：http://dali.dashuyun.cn/Article/details/gtxnqkzryx.html

Ruby: Thread.new { f }
来源：http://dali.yuanzhike.top/Article/details/gtehwkycql.html

C#:   Task.Run(() => F());
来源：http://dali.wangshuangyany.cn/Article/details/gtafecvrnr.html

[O02] 使用线程池
来源：http://dali.fzhhl.top/Article/details/gtteefllmu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.andypj.xyz/Article/details/gtyxozojna.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.fengsongda.top/Article/details/gtpbfjanoa.html

JS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gtujxsfnxb.html

TS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gtilidekvi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.havefunace.top/Article/details/gtnmuywyod.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yongpay.top/Article/details/gtkmyxlikc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqnorhgb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.smart0.xyz/Article/details/gtijvlqtzy.html

[O03] 加锁保护共享数据
来源：http://dali.shangyingyoupin.top/Article/details/gthfqgezrv.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gtcprtvtho.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.havefunace.top/Article/details/gtmfcgjlko.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.svipenyu.cn/Article/details/gtpbkyzhdh.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gtqwespuxs.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxuanxn.top/Article/details/gtmozuocpx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjsahufu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nwbrower.top/Article/details/gtnedvaaqh.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gtwskmqzwb.html

[O04] 定义异步函数并等待
来源：http://dali.birdmap.top/Article/details/gtvwgykoez.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigfzy.top/Article/details/gtjqwabxlo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenlongwang.top/Article/details/gtrlswavbn.html

JS:   async function f() { await g(); }
来源：http://dali.feifeiyinyue.top/Article/details/gthzsvqvpm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nanxuanxn.top/Article/details/gtxjptratv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknrrjynt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuxming.cn/Article/details/gtcnanxawu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jianghu66.top/Article/details/gtbznwysff.html

C#:   async Task F() { await G(); }
来源：http://dali.fengsongda.top/Article/details/gtdodlqftx.html

[O05] 并发执行并等待全部完成
来源：http://dali.gzhubu.top/Article/details/gtiwinxwck.html

Py:   asyncio.gather(*tasks)
来源：http://dali.iojbl.cn/Article/details/gtrimquduq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dianchejie.cn/Article/details/gtsfhjzpyh.html

JS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gturfbumnd.html

TS:   await Promise.all(tasks)
来源：http://dali.havefunace.top/Article/details/gtpfxfwxcp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guowangkeji.top/Article/details/gtqmfjiory.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnxiangtu.top/Article/details/gtamzbiglv.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gtkvmcujiz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cucudq.cn/Article/details/gtlgmnhyju.html

[O06] 使用进程池
来源：http://dali.mhx1999.top/Article/details/gthvehrora.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj202588.top/Article/details/gtufbcedsb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhoulong.xyz/Article/details/gtjyqyrrbu.html

JS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gtogcetjwp.html

TS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gtntcpxoav.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gtmaxsapei.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xuanzx.com/Article/details/gtjbotgbxx.html

Ruby: // fork 块
来源：http://dali.jqgufenzy.top/Article/details/gtkigreeih.html

C#:   Parallel.For
来源：http://dali.yvedp.cn/Article/details/gtlmaewvth.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtbnwdheos.html

P. 常用工具函数
来源：http://dali.shangyingyoupin.top/Article/details/gtboizzrsn.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtiigakpea.html

[P01] 生成 UUID
来源：http://dali.mhx1999.top/Article/details/gtqpvnhdsp.html

Py:   str(uuid.uuid4())
来源：http://dali.dashuyun.cn/Article/details/gtztqvkqhy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.quarkkingdee.top/Article/details/gtqekwboiy.html

JS:   crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbtcoauj.html

TS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gtlheketoe.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigufen.top/Article/details/gtcwouuaxd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gzhubu.top/Article/details/gtngsboisv.html

Ruby: SecureRandom.uuid
来源：http://dali.zycfv.cn/Article/details/gtirblcnwt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.birdmap.top/Article/details/gtoxygqmfs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xinyue.icu/Article/details/gtsyhfmlhh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gotoacloud.top/Article/details/gtwyafmmmj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtribvswpt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aizwys.cn/Article/details/gteksxeoqf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.fengsongda.top/Article/details/gtszudakqm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zdqjudy.top/Article/details/gtcidpjocx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.bjfxy.top/Article/details/gtsgfqmllr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtwjqvacjk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hongshengwenyu.top/Article/details/gtscvspqjb.html

[P03] 生成短随机字符串
来源：http://dali.mhx1999.top/Article/details/gtqmtaurfz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jqgufenzy.top/Article/details/gtythmiuqw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tian-w.cn/Article/details/gtpuatpqvx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gtglkxdfxd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhengqikj.top/Article/details/gtpsrqhaue.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sxryk.cn/Article/details/gtgmqkmkpj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.vqdsnc.cn/Article/details/gtlffpxmue.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cashguo.top/Article/details/gtgbatghug.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aibaodan.cn/Article/details/gtehhmmyga.html

[P04] 求长度
来源：http://dali.havefunace.top/Article/details/gtxlvepkvn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gogol.net.cn/Article/details/gtqmtoevms.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtriccokad.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gtgqnxoyit.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aizwys.cn/Article/details/gtenucwqgs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.birdmap.top/Article/details/gtkgnrjxgd.html

Go:   len(arr);  len(m)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwoebkfp.html

Ruby: x.length;  x.size
来源：http://dali.yangfankeji.com/Article/details/gtluymanfw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gtwouinkax.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yanxiufei.cn/Article/details/gtejvhlxnc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj202588.top/Article/details/gtsplrvwnx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gaohongyu789.top/Article/details/gthepmmanb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tian-w.cn/Article/details/gtedlpksin.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.feifeiyinyue.top/Article/details/gttxxibqcb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sxryk.cn/Article/details/gtvlomdaei.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gtjjvtplrv.html

Ruby: a == b
来源：http://dali.ywan-chungtsiang.top/Article/details/gttemhlmfv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guannengcc.top/Article/details/gtmqjcczbw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgfzy.top/Article/details/gtgovqyxrs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.dianchejie.cn/Article/details/gtdfpqvibd.html

PHP:  if (empty($x)) {}
来源：http://dali.sysykeji.top/Article/details/gtgexvqviz.html


<!-- 参考信息 -->