代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gtxevedabh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtaehvgqcw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jiagoushi.top/Article/details/gtjcqttaab.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nwbrower.top/Article/details/gtkhotxbzw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.bjfxy.top/Article/details/gtdlmsppuy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.iojbl.cn/Article/details/gtkapndtxd.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtkipiwarb.html

M. 命令行 / 进程 / 环境
来源：http://dali.0kj1m.cn/Article/details/gtntiaixix.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtyhgtxycy.html

[M01] 读取命令行参数
来源：http://dali.daria6918.cn/Article/details/gtnoncwspt.html

Py:   sys.argv[1:]
来源：http://dali.yongpay.top/Article/details/gtdcmlklvp.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gtkzfqoked.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtdqsdnmib.html

TS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gtcbgsftlp.html

Java: args 数组（main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gtsgtnalkk.html

Go:   os.Args[1:]
来源：http://dali.shzxlz.cn/Article/details/gtojsaddij.html

Ruby: ARGV
来源：http://dali.hongshengwenyu.top/Article/details/gtqhutxewo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenjidiqi.icu/Article/details/gttkqxolic.html

[M02] 读取环境变量
来源：http://dali.nanxuanxn.top/Article/details/gtbrnqebya.html

Py:   os.environ.get("HOME")
来源：http://dali.mhx1999.top/Article/details/gtjilxpnna.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gogol.net.cn/Article/details/gtshiuneyx.html

JS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gtnpgrxafy.html

TS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gtdhmgzktn.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtjrasqfhw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtnwpdnnhl.html

Ruby: ENV["HOME"]
来源：http://dali.yuanzhike.top/Article/details/gtaaogiptu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangdashe.top/Article/details/gtohloizxe.html

[M03] 执行外部命令
来源：http://dali.svipenyu.cn/Article/details/gtmfqpnsvq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhoulong.xyz/Article/details/gtrmltlvdl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cqqwz.cn/Article/details/gtzevrcinn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gtwweqtfer.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtbsrkpxiw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gttlxangsb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cqqwz.cn/Article/details/gtgcjfdmab.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sxryk.cn/Article/details/gtxwwadaeq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.dashuyun.cn/Article/details/gtpbqtwbnj.html

[M04] 获取当前工作目录
来源：http://dali.xinyue.icu/Article/details/gtcpfymjel.html

Py:   os.getcwd()
来源：http://dali.gogol.net.cn/Article/details/gtbmrombix.html

PHP:  getcwd();
来源：http://dali.jyoumei.cn/Article/details/gtjnqdqtxl.html

JS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtuuavnbbb.html

TS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gtolcgdaph.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zdqjudy.top/Article/details/gtxaczpfxg.html

Go:   os.Getwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymqixogb.html

Ruby: Dir.pwd
来源：http://dali.jyoumei.cn/Article/details/gtvrvzwdnr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tanke756.top/Article/details/gtukkibeho.html

[M05] 设置退出码
来源：http://dali.birdmap.top/Article/details/gttmctjeyf.html

Py:   sys.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtgszaryre.html

PHP:  exit(1);
来源：http://dali.gaohongyu789.top/Article/details/gtwtnttcib.html

JS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gturdvnhwc.html

TS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gtazrmlupq.html

Java: System.exit(1)
来源：http://dali.andypj.xyz/Article/details/gttdwysnzf.html

Go:   os.Exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtsbrmitbe.html

Ruby: exit 1
来源：http://dali.guannengcc.top/Article/details/gtthgplnxm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gotoacloud.top/Article/details/gtwpgettwo.html

[M06] 向标准错误输出
来源：http://dali.chenjidiqi.icu/Article/details/gtyccrxuxu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.c1oappe.top/Article/details/gtnbewsklc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuetiantiany.cn/Article/details/gtbmzxxrag.html

JS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gtbyywqnpg.html

TS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gtteaegshv.html

Java: System.err.println("err")
来源：http://dali.svipenyu.cn/Article/details/gttezzbtng.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cheryme.top/Article/details/gtcwkgmqfe.html

Ruby: warn "err"
来源：http://dali.jinqigufen.top/Article/details/gtoiomentq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrfpgzay.html

[M07] 判断是否为主入口
来源：http://dali.9152youxi.cn/Article/details/gtyyrlhjtr.html

Py:   if __name__ == "__main__":
来源：http://dali.snrcjt.cn/Article/details/gtmgzalgtg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.316326.xyz/Article/details/gtwuzqexrd.html

JS:   require.main === module
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbepakfif.html

TS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gtoiqtdwhp.html

Java: public static void main(String[] args)
来源：http://dali.zhixingplan.top/Article/details/gtwjrmlyrb.html

Go:   func main()
来源：http://dali.jqgfzy.top/Article/details/gtptqttpbd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xinyue.icu/Article/details/gtqtebfxhd.html

C#:   static void Main(string[] args)
来源：http://dali.hnqzz.top/Article/details/gteuatpnsb.html

[M08] 获取系统与运行时信息
来源：http://dali.c1oappe.top/Article/details/gthnpyyevv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nanxuanxn.top/Article/details/gtjipkpvix.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.316326.xyz/Article/details/gtsribckbl.html

JS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gtscjjgnpc.html

TS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gtnbsbjtac.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dianchejie.cn/Article/details/gttzxnbwhu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgufenzy.top/Article/details/gtrvnremcx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pycfn.com/Article/details/gtxmddcntb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dashuyun.cn/Article/details/gtauiqnepw.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtecmgqlye.html

N. 数据结构与算法
来源：http://dali.zhengqikj.top/Article/details/gtbtswezlu.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtdznyglcu.html

[N01] 二分查找（有序数组）
来源：http://dali.cheryme.top/Article/details/gtfectnwly.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tanke756.top/Article/details/gtvsyquvwr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.316326.xyz/Article/details/gtoyuxypch.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gtryrdhvpc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gtnaqcwebu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtzwziqhud.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtpsrgfscz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cashguo.top/Article/details/gtyfyqhnry.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gthdfiidsg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jyoumei.cn/Article/details/gtuacepwco.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangshuangyany.cn/Article/details/gtsygrudij.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yonumen.top/Article/details/gtjilbqvgr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gtoycexlfj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gtskvcuqjo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.quarkkingdee.top/Article/details/gtcrwdaicb.html

Go:   slices.Sort(arr)
来源：http://dali.xinyue.icu/Article/details/gtbmcghpvl.html

Ruby: arr.sort
来源：http://dali.yueranfly.top/Article/details/gtmjjjxtin.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.havefunace.top/Article/details/gtkxpylcby.html

[N03] 快速排序（分治示例）
来源：http://dali.hongshengwenyu.top/Article/details/gtcepvnyqr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.bjfxy.top/Article/details/gtexgcwsku.html

PHP:  // 递归实现，或用 usort
来源：http://dali.0kj1m.cn/Article/details/gtpmryzzcz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gtqfpbfezo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gthzvwxery.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258.top/Article/details/gtdthpzlol.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xylfe.cn/Article/details/gtfmnulyxv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.iojbl.cn/Article/details/gtlbuioxnq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hywenlv.cn/Article/details/gthgldgdco.html

[N04] 斐波那契数列
来源：http://dali.meibo888.top/Article/details/gtpfrffcgc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gtijttkyry.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ybcxt.top/Article/details/gthwyvjnoo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbszjxbxs.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtegmebiim.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamwmeaip.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pycfn.com/Article/details/gtyetslrqf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtvfjircdk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtunjninzw.html

[N05] 最大公约数
来源：http://dali.9152youxi.cn/Article/details/gtiuhxtkni.html

Py:   math.gcd(a, b)
来源：http://dali.meibo888.top/Article/details/gtchhrzysm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtffruutla.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gtyzpjswyi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yueranfly.top/Article/details/gtxjhuafnw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sufxvd.cn/Article/details/gtqubsmcvd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.pengpengdd.cyou/Article/details/gtvhroahct.html

Ruby: a.gcd(b)
来源：http://dali.zhongyouzk.top/Article/details/gtbbekxtoz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cashguo.top/Article/details/gtwgzacpej.html

[N06] 判断回文字符串
来源：http://dali.yvedp.cn/Article/details/gtixdulvfg.html

Py:   s == s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gtsyenpfkg.html

PHP:  $s === strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gtqcrlschm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtyftmrola.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtspgikzto.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sufxvd.cn/Article/details/gtbmeosbrs.html

Go:   // 双指针从两端比较
来源：http://dali.ybcxt.top/Article/details/gtlheqwgvq.html

Ruby: s == s.reverse
来源：http://dali.wangdashe.top/Article/details/gthssfrqed.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ivvv.top/Article/details/gtohifklok.html

[N07] 两数之和（返回下标）
来源：http://dali.yangfankeji.com/Article/details/gtvjtsyjqo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shzxlz.cn/Article/details/gtipvlzptz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqjbbgej.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xuetiantiany.cn/Article/details/gtnrrhxbsl.html

TS:   // 手写 Map<string, number>
来源：http://dali.cqqwz.cn/Article/details/gtzzzkpwjh.html

Java: // 手写 HashMap
来源：http://dali.sufxvd.cn/Article/details/gtzqsffsrl.html

Go:   // 手写 map[int]int
来源：http://dali.cheryme.top/Article/details/gtgnbwktzn.html

Ruby: // 手写 Hash
来源：http://dali.cqqwz.cn/Article/details/gttmnklgpj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocqunqjp.html

[N08] 生成全排列
来源：http://dali.aizwys.cn/Article/details/gtpsznrwoi.html

Py:   itertools.permutations(arr)
来源：http://dali.guannengcc.top/Article/details/gtcmuaoxuq.html

PHP:  // 手写递归交换
来源：http://dali.mhx1999.top/Article/details/gtuyprhcda.html

JS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtegjacfxa.html

TS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtxnmtawrq.html

Java: // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtbhzacmpt.html

Go:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtovfgfcve.html

Ruby: arr.permutation.to_a
来源：http://dali.dianchejie.cn/Article/details/gtsnewtxpy.html

C#:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtunhjhreq.html

[N09] 栈与队列
来源：http://dali.dashuyun.cn/Article/details/gttddyjiqs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenzaomai.com/Article/details/gtrfvgcyxk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtjhdgvpvu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtejwyfnvb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dashuyun.cn/Article/details/gtytruhvxl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aibaodan.cn/Article/details/gtxpsfvhah.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.meibo888.top/Article/details/gtnidtznns.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gtujhfybnk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.kuanghao11.cn/Article/details/gtxqgesazt.html

[N10] 链表节点定义
来源：http://dali.xylfe.cn/Article/details/gtpirftakh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkuqeyyzy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.wangshuangyany.cn/Article/details/gtccjaojqi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.kuanghao11.cn/Article/details/gtvaobqvvd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jlsjyb.cn/Article/details/gtdnkgmvhp.html

Java: class Node { int v; Node next; }
来源：http://dali.zdqjudy.top/Article/details/gtymwqowiq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cqqwz.cn/Article/details/gtucesnncp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazoffgzw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daria6918.cn/Article/details/gtkmaizfax.html

[N11] 二叉树中序遍历
来源：http://dali.hnqzz.top/Article/details/gtbvgnromg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daria6918.cn/Article/details/gtikcnxtln.html

PHP:  // 手写递归函数
来源：http://dali.c1oappe.top/Article/details/gtbtvlqwoy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyctpclaz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cheryme.top/Article/details/gtcpvfjhbd.html

Java: // 手写递归
来源：http://dali.cucudq.cn/Article/details/gtckgmditf.html

Go:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gtxiagsuwx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ehwqpu.com/Article/details/gtzicfndkr.html

C#:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtslsadxar.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yueranfly.top/Article/details/gtnfsihoay.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixmidgum.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinghuilouyu.cn/Article/details/gtyznaneqc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cucudq.cn/Article/details/gtdpqdxtgp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gtlceilexq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gtcuqfdrfi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258.top/Article/details/gtmnoczanh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zdqjudy.top/Article/details/gtfbqmtbzi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gtehmmcciv.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtbekxzwwu.html

O. 并发与异步
来源：http://dali.c1oappe.top/Article/details/gtdtexqdna.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtmrvkpbbm.html

[O01] 启动一个线程
来源：http://dali.ppjwa.cn/Article/details/gtslzrcakv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.birdmap.top/Article/details/gtqkjjdvck.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xylfe.cn/Article/details/gtbgibomlr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258888.top/Article/details/gtcdaslizv.html

TS:   // 同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gtdzgrrxwh.html

Java: new Thread(() -> f()).start()
来源：http://dali.ehwqpu.com/Article/details/gtnisjtpdm.html

Go:   go f()
来源：http://dali.jinqigufen.top/Article/details/gturcppqfj.html

Ruby: Thread.new { f }
来源：http://dali.gaohongyu789.top/Article/details/gtfjeghaqv.html

C#:   Task.Run(() => F());
来源：http://dali.ybcxt.top/Article/details/gtlhkhfkki.html

[O02] 使用线程池
来源：http://dali.redwolf501.top/Article/details/gtcamalsnr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.bjfxy.top/Article/details/gtwjijuxek.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhongyouzk.top/Article/details/gticlgthdm.html

JS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtunwygcmu.html

TS:   // worker_threads 线程池
来源：http://dali.kuanghao11.cn/Article/details/gtvfyhvnfd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daria6918.cn/Article/details/gtkkqpeiav.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuanzhike.top/Article/details/gtvyxizpkw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhongyouzk.top/Article/details/gtfoijppvq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xuanzx.com/Article/details/gttjeygmzt.html

[O03] 加锁保护共享数据
来源：http://dali.tianlin.xyz/Article/details/gthshqswhm.html

Py:   with lock: shared += 1
来源：http://dali.cucudq.cn/Article/details/gtwirdssgd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aibaodan.cn/Article/details/gtxlmbelxf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj20258888.top/Article/details/gtrejivlyj.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gtnfgkotjs.html

Java: synchronized (this) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmfeynydb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nwbrower.top/Article/details/gtuljuwtec.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyckzjhoh.html

C#:   lock (gate) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gtxzudbptw.html

[O04] 定义异步函数并等待
来源：http://dali.yvedp.cn/Article/details/gtfwjpfkdo.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxuanxn.top/Article/details/gtltlimydp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.316326.xyz/Article/details/gtpowabhoh.html

JS:   async function f() { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gtgmfikqze.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gtrjxcxfik.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cheryme.top/Article/details/gtwccacbop.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gaohongyu789.top/Article/details/gttgxlregy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.quarkkingdee.top/Article/details/gtyzwnzmxl.html

C#:   async Task F() { await G(); }
来源：http://dali.ehwqpu.com/Article/details/gtfuzsrxaw.html

[O05] 并发执行并等待全部完成
来源：http://dali.svipenyu.cn/Article/details/gtgyngjepi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhongyouzk.top/Article/details/gtnpqdwlik.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gotoacloud.top/Article/details/gtcodytbjt.html

JS:   await Promise.all(tasks)
来源：http://dali.tianlin.xyz/Article/details/gtusrizjdn.html

TS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gtdwaskgxp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gogol.net.cn/Article/details/gthsplvqxj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yanxiufei.cn/Article/details/gtkdnrvasv.html

Ruby: threads.map(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gtwnzkrjjj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sysykeji.top/Article/details/gtvcwrnvjb.html

[O06] 使用进程池
来源：http://dali.fzhhl.top/Article/details/gtwpwcalba.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fzhhl.top/Article/details/gtakiofnlq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.vqdsnc.cn/Article/details/gtokprwevg.html

JS:   // child_process / cluster 模块
来源：http://dali.fzhhl.top/Article/details/gtuiekrkcr.html

TS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gthakmgnsz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cheryme.top/Article/details/gtbhokeoyc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.snrcjt.cn/Article/details/gtpuifflup.html

Ruby: // fork 块
来源：http://dali.guowangkeji.top/Article/details/gtgicvernc.html

C#:   Parallel.For
来源：http://dali.jinghuilouyu.cn/Article/details/gtaaciwqll.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtinsgmjbn.html

P. 常用工具函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdymsjzb.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtnnphdkit.html

[P01] 生成 UUID
来源：http://dali.aibaodan.cn/Article/details/gtpisswqpr.html

Py:   str(uuid.uuid4())
来源：http://dali.feifeiyinyue.top/Article/details/gtomjlugpd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guannengcc.top/Article/details/gtcxzfjydo.html

JS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gtlopziqtx.html

TS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtuqitejok.html

Java: UUID.randomUUID().toString()
来源：http://dali.ppjwa.cn/Article/details/gtggxxjexb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hfpthk.cn/Article/details/gtqhykkuwq.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgfzy.top/Article/details/gtvmcmomok.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tanke756.top/Article/details/gtgyfmqoin.html

[P02] MD5 / SHA256 摘要
来源：http://dali.fengsongda.top/Article/details/gtozdbbunf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hfpthk.cn/Article/details/gtqrwzqidk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nwbrower.top/Article/details/gthwzrnkym.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sweek.top/Article/details/gtgevcfskr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.haohaochexian.top/Article/details/gtbnwulukk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.316326.xyz/Article/details/gtlosfcqsf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daxiang520.top/Article/details/gtdbcqomyb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtbtoaqqvn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cheryme.top/Article/details/gtlzgmbsit.html

[P03] 生成短随机字符串
来源：http://dali.nwbrower.top/Article/details/gtmtflysqz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.birdmap.top/Article/details/gtflrtvfin.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cheryme.top/Article/details/gtzpmisnlz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gtoyicmxfe.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gotoacloud.top/Article/details/gtbjqcncuk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhixingplan.top/Article/details/gtncsxrogk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ppjwa.cn/Article/details/gtpnnhohpk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jianghu66.top/Article/details/gtxxmiaydd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.kuanghao11.cn/Article/details/gtlnzercbk.html

[P04] 求长度
来源：http://dali.wangshuangyany.cn/Article/details/gttvekzduw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.havefunace.top/Article/details/gtvjygduki.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtwvdscpju.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shzxlz.cn/Article/details/gtlklvheqi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fengsongda.top/Article/details/gtgahmdcgx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258.top/Article/details/gtvlntkgkd.html

Go:   len(arr);  len(m)
来源：http://dali.hnxiangtu.top/Article/details/gtclrqxxsj.html

Ruby: x.length;  x.size
来源：http://dali.xuetiantiany.cn/Article/details/gthkztiypi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hywenlv.cn/Article/details/gtylgtkuyk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.c1oappe.top/Article/details/gtirwhcizf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258888.top/Article/details/gtuuebjfwa.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgfzy.top/Article/details/gtxzavaski.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.dashuyun.cn/Article/details/gthddbqddy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hysaishi.cn/Article/details/gtnctqnsvb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.svipenyu.cn/Article/details/gtetvulipm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sysykeji.top/Article/details/gtwpravegq.html

Ruby: a == b
来源：http://dali.kuanghao11.cn/Article/details/gthmctsxdl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shangyingyoupin.top/Article/details/gtuwrczpsi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj202588.top/Article/details/gtudssiovv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yongpay.top/Article/details/gtlbrbratb.html

PHP:  if (empty($x)) {}
来源：http://dali.nanxuanxn.top/Article/details/gtnjvcqgpf.html


<!-- 参考信息 -->