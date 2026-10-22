代发 wailian999

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gtdahgxcxt.html

JS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gthaarzjcz.html

TS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gtdiisxgfe.html

Java: System.getenv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtblqzyaqc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtqvfnuyug.html

Ruby: ENV["HOME"]
来源：http://dali.xuetiantiany.cn/Article/details/gtrrbzcwbj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtjwzhrikn.html

[M03] 执行外部命令
来源：http://dali.yangfankeji.com/Article/details/gtzkfjyfgv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenlongwang.top/Article/details/gtqnealcjo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aizwys.cn/Article/details/gtnwxwlfnn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gtbsbcfwad.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gthlnkyxav.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gaohongyu789.top/Article/details/gtvdpafdoi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.birdmap.top/Article/details/gtwttdnnll.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sxryk.cn/Article/details/gtxhnctjgx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigfzy.top/Article/details/gtnitbtsyw.html

[M04] 获取当前工作目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhousyky.html

Py:   os.getcwd()
来源：http://dali.cucudq.cn/Article/details/gtpwfpgxuw.html

PHP:  getcwd();
来源：http://dali.zycfv.cn/Article/details/gtmbsxyzrk.html

JS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gtiurrxmwl.html

TS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gtbtggqyqn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cdnleiting.top/Article/details/gtdrnqvonw.html

Go:   os.Getwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqanwmtwd.html

Ruby: Dir.pwd
来源：http://dali.fengsongda.top/Article/details/gtudebfrgi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hfpthk.cn/Article/details/gtrelsprdl.html

[M05] 设置退出码
来源：http://dali.jianghu66.top/Article/details/gtwppalrbv.html

Py:   sys.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtjbsipvpb.html

PHP:  exit(1);
来源：http://dali.aizwys.cn/Article/details/gtsvpqexsx.html

JS:   process.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtsmvbvkfr.html

TS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtrhckdsah.html

Java: System.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtkxjpbvha.html

Go:   os.Exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtmbrhuymh.html

Ruby: exit 1
来源：http://dali.chenzaomai.com/Article/details/gtiiglhjir.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aibaodan.cn/Article/details/gtplwrfkyr.html

[M06] 向标准错误输出
来源：http://dali.aibaodan.cn/Article/details/gtwcpjwvlv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.iojbl.cn/Article/details/gtfiqfxwgf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fengsongda.top/Article/details/gtscgnvsuo.html

JS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gtltmhhkmj.html

TS:   console.error("err")
来源：http://dali.yangfankeji.com/Article/details/gtovmucosw.html

Java: System.err.println("err")
来源：http://dali.sufxvd.cn/Article/details/gtetldrknb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yueranfly.top/Article/details/gthcndoqms.html

Ruby: warn "err"
来源：http://dali.yvedp.cn/Article/details/gtaepkxznj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258.top/Article/details/gtoozgqywn.html

[M07] 判断是否为主入口
来源：http://dali.yj20258.top/Article/details/gtjkrcsmvd.html

Py:   if __name__ == "__main__":
来源：http://dali.xylfe.cn/Article/details/gtvytezfly.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hongshengwenyu.top/Article/details/gtoscjxbus.html

JS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gtkkwxntls.html

TS:   require.main === module
来源：http://dali.sweek.top/Article/details/gtlhgzbckf.html

Java: public static void main(String[] args)
来源：http://dali.smart0.xyz/Article/details/gtpqcxuwbe.html

Go:   func main()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfizdpfab.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gzhubu.top/Article/details/gtuxwkhdwg.html

C#:   static void Main(string[] args)
来源：http://dali.smart0.xyz/Article/details/gtrqqsbxdp.html

[M08] 获取系统与运行时信息
来源：http://dali.shzxlz.cn/Article/details/gtttqpjqqk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.iojbl.cn/Article/details/gtwgagccsn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hammf.cn/Article/details/gtalfpyblk.html

JS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gthbmleniy.html

TS:   process.platform;  process.version
来源：http://dali.jianghu66.top/Article/details/gtvhfcyetq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zycfv.cn/Article/details/gtnccfhlkf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.snrcjt.cn/Article/details/gtwqqrfikk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdvsgtozh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.snrcjt.cn/Article/details/gtlvxzlgoc.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtkwaeihip.html

N. 数据结构与算法
来源：http://dali.guowangkeji.top/Article/details/gtmniiqyll.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtzwmonoer.html

[N01] 二分查找（有序数组）
来源：http://dali.zhixingplan.top/Article/details/gtrdazhzxy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtjvnpvldq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.bjfxy.top/Article/details/gtmbxtqclf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gtsupktlwx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtuvcpcfve.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtqstaasvr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtrbcrblqr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnxiangtu.top/Article/details/gtxlcwrtev.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtdfwxsqdk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ybcxt.top/Article/details/gtplrtlpmm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gtadwgzhwe.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenzaomai.com/Article/details/gtpukoqpml.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gtjootcyrc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gttkxadqnj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.316326.xyz/Article/details/gtfqzbhiwj.html

Go:   slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gtmwrumjki.html

Ruby: arr.sort
来源：http://dali.shzxlz.cn/Article/details/gtkbhyubnv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zdqjudy.top/Article/details/gtdofkzzks.html

[N03] 快速排序（分治示例）
来源：http://dali.mhx1999.top/Article/details/gtpjefcwsb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hnxiangtu.top/Article/details/gtkcjpdbco.html

PHP:  // 递归实现，或用 usort
来源：http://dali.c1oappe.top/Article/details/gtwqvxuzcc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gtuvwztbot.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ehwqpu.com/Article/details/gtalssfwoc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.haohaochexian.top/Article/details/gtvqpysjfr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hfpthk.cn/Article/details/gtugatgztj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenzaomai.com/Article/details/gtixhmqugr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.andypj.xyz/Article/details/gtmeixujsl.html

[N04] 斐波那契数列
来源：http://dali.hammf.cn/Article/details/gtamowhhnc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtjzrdqitq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gtbugdbjnb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gthgjimrir.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtdnimlwtp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gttoedkcvl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ppjwa.cn/Article/details/gtccpyavso.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gtvejyjyup.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtsjxcaypb.html

[N05] 最大公约数
来源：http://dali.sweek.top/Article/details/gtqipkzulb.html

Py:   math.gcd(a, b)
来源：http://dali.tanke756.top/Article/details/gtwzdeasle.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtkqwmhykw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtfrdlbxrg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gtstwlymdi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xinyue.icu/Article/details/gtcrprcrwt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jyoumei.cn/Article/details/gtxcssezgv.html

Ruby: a.gcd(b)
来源：http://dali.zhoulong.xyz/Article/details/gtxezffulh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sufxvd.cn/Article/details/gtztezodvh.html

[N06] 判断回文字符串
来源：http://dali.kuanghao11.cn/Article/details/gtvfucnngz.html

Py:   s == s[::-1]
来源：http://dali.ydzc1.top/Article/details/gtkdugysts.html

PHP:  $s === strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtiygidfvb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtphgvuegc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtbgzihlej.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xinyue.icu/Article/details/gtcpaszals.html

Go:   // 双指针从两端比较
来源：http://dali.yuanzhike.top/Article/details/gtrmbdgrnq.html

Ruby: s == s.reverse
来源：http://dali.jinqigufen.top/Article/details/gtvhomaadv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenlongwang.top/Article/details/gtcfstoupj.html

[N07] 两数之和（返回下标）
来源：http://dali.yj202588.top/Article/details/gtpeyqpkho.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daxiang520.top/Article/details/gtwcfmxsof.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgufenzy.top/Article/details/gtkwhohond.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tanke756.top/Article/details/gtmoldboxy.html

TS:   // 手写 Map<string, number>
来源：http://dali.jyoumei.cn/Article/details/gtnmrfbyng.html

Java: // 手写 HashMap
来源：http://dali.xuetiantiany.cn/Article/details/gtsdqwdpxo.html

Go:   // 手写 map[int]int
来源：http://dali.aibaodan.cn/Article/details/gtkwafzxpn.html

Ruby: // 手写 Hash
来源：http://dali.9152youxi.cn/Article/details/gtbkpvcdbp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cheryme.top/Article/details/gtqdcsyced.html

[N08] 生成全排列
来源：http://dali.hfpthk.cn/Article/details/gtwpluavow.html

Py:   itertools.permutations(arr)
来源：http://dali.aizwys.cn/Article/details/gtszxacyly.html

PHP:  // 手写递归交换
来源：http://dali.zhongyouzk.top/Article/details/gtwmzqfsii.html

JS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtvkphozay.html

TS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtlmwzbyyx.html

Java: // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gteidwbaog.html

Go:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtxsisnbey.html

Ruby: arr.permutation.to_a
来源：http://dali.chenzaomai.com/Article/details/gtpjxmqgzn.html

C#:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtoiemdlfa.html

[N09] 栈与队列
来源：http://dali.yangfankeji.com/Article/details/gtifpinbqc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.316326.xyz/Article/details/gtymnwlrrq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtcxmbxttk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gtulfzaxyw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fengsongda.top/Article/details/gtnewzrtpn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqgxbetj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.svipenyu.cn/Article/details/gtrfdphcrk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gthyazgawj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cqqwz.cn/Article/details/gtrgvsuxlq.html

[N10] 链表节点定义
来源：http://dali.snrcjt.cn/Article/details/gtejkszubs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shangyingyoupin.top/Article/details/gthvvrgrbn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgipbjwwl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yonumen.top/Article/details/gthvcpwjsf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangdashe.top/Article/details/gtjttykszj.html

Java: class Node { int v; Node next; }
来源：http://dali.sweek.top/Article/details/gttofukoic.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hysaishi.cn/Article/details/gtzstpelnf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ppjwa.cn/Article/details/gtrjfiuqxz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shzxlz.cn/Article/details/gtgcdvxoev.html

[N11] 二叉树中序遍历
来源：http://dali.nanxinkj.top/Article/details/gtwmvlsgid.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jqgufenzy.top/Article/details/gtkihzciis.html

PHP:  // 手写递归函数
来源：http://dali.zhongyouzk.top/Article/details/gtgjbtpdbc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gtveaxiqbb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gtpycjocaj.html

Java: // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gtxuyvwpma.html

Go:   // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gtsnwaqzwt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gaohongyu789.top/Article/details/gtvvqloldh.html

C#:   // 手写递归
来源：http://dali.gzhubu.top/Article/details/gtqhacchfo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yvedp.cn/Article/details/gthmcqrcqm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yonumen.top/Article/details/gtwmyvhokv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.feifeiyinyue.top/Article/details/gtwzoyurzl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gtrvdgrkid.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuanzx.com/Article/details/gtrcqcmbxc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ydzc1.top/Article/details/gtxhfkhzti.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xuetiantiany.cn/Article/details/gtpifykpxx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.quarkkingdee.top/Article/details/gtcwcqcmgr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gtqhcqjlbi.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtztwqahms.html

O. 并发与异步
来源：http://dali.xylfe.cn/Article/details/gtcrxgojhl.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtoainhnhf.html

[O01] 启动一个线程
来源：http://dali.zhiwuduotai.top/Article/details/gtoriieotv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjlhvdjxu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hywenlv.cn/Article/details/gtgacgefqq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.pycfn.com/Article/details/gtbwqtrfnj.html

TS:   // 同 JS
来源：http://dali.jlsjyb.cn/Article/details/gttuvfkund.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdztvzfa.html

Go:   go f()
来源：http://dali.fengsongda.top/Article/details/gtusyssdau.html

Ruby: Thread.new { f }
来源：http://dali.aibaodan.cn/Article/details/gtkwzaotwu.html

C#:   Task.Run(() => F());
来源：http://dali.yonumen.top/Article/details/gtqvvqdrae.html

[O02] 使用线程池
来源：http://dali.vqdsnc.cn/Article/details/gtqhxvhacd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhongyouzk.top/Article/details/gtqiyuqgcv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ppjwa.cn/Article/details/gtnxeqblew.html

JS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gtswpmhhmd.html

TS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gtubynyjrk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.meibo888.top/Article/details/gtxmljjdqn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sxryk.cn/Article/details/gtabmqgvne.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258888.top/Article/details/gtljuskoxg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.dianchejie.cn/Article/details/gtmecofohh.html

[O03] 加锁保护共享数据
来源：http://dali.shanyushiyangkeji.top/Article/details/gteowttfbt.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdsnwfdp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.kuanghao11.cn/Article/details/gtrgnkfsmq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xuetiantiany.cn/Article/details/gtjjuydvia.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gtmlmmfgxz.html

Java: synchronized (this) { shared++; }
来源：http://dali.hywenlv.cn/Article/details/gtzjynqtyq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xziqi.cn/Article/details/gtezozaufv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cqqwz.cn/Article/details/gtbctztfjd.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gtkjpbrvlh.html

[O04] 定义异步函数并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsvialhq.html

Py:   async def f():⏎    await g()
来源：http://dali.chenlongwang.top/Article/details/gttnoexgvt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhoulong.xyz/Article/details/gtpcmxydpx.html

JS:   async function f() { await g(); }
来源：http://dali.zdqjudy.top/Article/details/gtkgigciso.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gtxdaamndd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.meibo888.top/Article/details/gtmahhftkj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shzxlz.cn/Article/details/gttaeavzsz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.iojbl.cn/Article/details/gtdcaauqnz.html

C#:   async Task F() { await G(); }
来源：http://dali.zhongyouzk.top/Article/details/gthmkdkacp.html

[O05] 并发执行并等待全部完成
来源：http://dali.gotoacloud.top/Article/details/gtafysluxv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yonumen.top/Article/details/gtgllialwu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.guowangkeji.top/Article/details/gtxmgqwkma.html

JS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gtofrttdfe.html

TS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtbplprseg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.havefunace.top/Article/details/gtaaxzwstr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xziqi.cn/Article/details/gtyjfdaujw.html

Ruby: threads.map(&:join)
来源：http://dali.aizwys.cn/Article/details/gtyxrxsoip.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xziqi.cn/Article/details/gtlruzywgj.html

[O06] 使用进程池
来源：http://dali.zdqjudy.top/Article/details/gttfesamze.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.aibaodan.cn/Article/details/gttxqbhvix.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daxiang520.top/Article/details/gthvbvtyld.html

JS:   // child_process / cluster 模块
来源：http://dali.daria6918.cn/Article/details/gtmwlormbz.html

TS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gtevtdipsk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yangfankeji.com/Article/details/gtlhwjbgga.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.aizwys.cn/Article/details/gtprjcttkl.html

Ruby: // fork 块
来源：http://dali.yonumen.top/Article/details/gthxrvciga.html

C#:   Parallel.For
来源：http://dali.jinqigufen.top/Article/details/gtqhovpgrh.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtgantawie.html

P. 常用工具函数
来源：http://dali.sysykeji.top/Article/details/gtyuvctyao.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtsdidbyxz.html

[P01] 生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gtuujznxsk.html

Py:   str(uuid.uuid4())
来源：http://dali.yuanzhike.top/Article/details/gtqpmnqjjs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jlsjyb.cn/Article/details/gtwlxdbhvy.html

JS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gtsrshqpaj.html

TS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtyclqflqm.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigufen.top/Article/details/gtjdjymasz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhmvtmzm.html

Ruby: SecureRandom.uuid
来源：http://dali.sufxvd.cn/Article/details/gtkocahfzj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258888.top/Article/details/gthfzjddmc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhiwuduotai.top/Article/details/gtzsmjytis.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xinyue.icu/Article/details/gteibtxvdc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cheryme.top/Article/details/gtytghvxlp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gotoacloud.top/Article/details/gtwicjmygv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hongshengwenyu.top/Article/details/gtdsnkztco.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtbdorieud.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivbsvriv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.daria6918.cn/Article/details/gtgxzlrxnt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hammf.cn/Article/details/gtjcuaikuc.html

[P03] 生成短随机字符串
来源：http://dali.jyoumei.cn/Article/details/gttsmvaaqn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.kuanghao11.cn/Article/details/gtoenyrxla.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jiagoushi.top/Article/details/gtiocqfreq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnxiangtu.top/Article/details/gtnwmwhhlv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gtdcbsybgs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sufxvd.cn/Article/details/gtffzoyknu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.meibo888.top/Article/details/gtedprobal.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nwbrower.top/Article/details/gteoycvqho.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258.top/Article/details/gtpdkxkpcv.html

[P04] 求长度
来源：http://dali.cdnleiting.top/Article/details/gttxzqoatt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yanxiufei.cn/Article/details/gtyrlnnbut.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gteudmdqlc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gtzczuwwta.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hfpthk.cn/Article/details/gtujlkmpuj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tianlin.xyz/Article/details/gtbwdkdpin.html

Go:   len(arr);  len(m)
来源：http://dali.0kj1m.cn/Article/details/gtdcigrmnu.html

Ruby: x.length;  x.size
来源：http://dali.shanyushiyangtech.top/Article/details/gtyuljttjg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.birdmap.top/Article/details/gtlpigcqrq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.iojbl.cn/Article/details/gteqwgwnsl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jqgufenzy.top/Article/details/gtbimjvvug.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenjidiqi.icu/Article/details/gtsrvvpwxj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hammf.cn/Article/details/gtfcdafbjc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sweek.top/Article/details/gtrbmuektm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fengsongda.top/Article/details/gtyzhkpxhs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gtxqttqkmt.html

Ruby: a == b
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvftiuaf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.quarkkingdee.top/Article/details/gtwtuexpqi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yanxiufei.cn/Article/details/gthrrhzias.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgatsqgrd.html

PHP:  if (empty($x)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedkdasqe.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgfzy.top/Article/details/gttugitkwe.html

TS:   if (x == null) {}
来源：http://dali.jiagoushi.top/Article/details/gtssavuwbq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shuidangran.top/Article/details/gtesgmecqw.html

Go:   if x == nil {}
来源：http://dali.hfpthk.cn/Article/details/gtohomdaul.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenjidiqi.icu/Article/details/gtobureprj.html

C#:   if (x is null) {}
来源：http://dali.ydzc1.top/Article/details/gtnuqrkfce.html

[P07] 防抖与节流
来源：http://dali.daxiang520.top/Article/details/gtcobihawh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sweek.top/Article/details/gtijaslxgd.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigufen.top/Article/details/gtwrggdcab.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.havefunace.top/Article/details/gtgjrgflto.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtpgwulahx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtarbbvccl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gzhubu.top/Article/details/gtwawqzxyh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ehwqpu.com/Article/details/gtclxrtsum.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenlongwang.top/Article/details/gtbkrlkvxh.html

[P08] 处理浮点精度问题
来源：http://dali.cashguo.top/Article/details/gtbyevjvhw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.quarkkingdee.top/Article/details/gtaclfbyuh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtnlcgruzb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gogol.net.cn/Article/details/gtkwslacbs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tianlin.xyz/Article/details/gtqglxambr.html


<!-- 参考信息 -->