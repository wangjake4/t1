代发 wailian999

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.9152youxi.cn/Article/details/gtkucpeeii.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tian-w.cn/Article/details/gtbedrsadh.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gthpkxtoga.html

M. 命令行 / 进程 / 环境
来源：http://dali.mhx1999.top/Article/details/gtlbbalgur.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtdvqxxpmb.html

[M01] 读取命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gtfvlkhwgv.html

Py:   sys.argv[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtrozatfle.html

PHP:  $argv;  $argc;
来源：http://dali.zhoulong.xyz/Article/details/gtfdfgpcyq.html

JS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gtvgtjfook.html

TS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gtopkonvwq.html

Java: args 数组（main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gtuxjfhfsk.html

Go:   os.Args[1:]
来源：http://dali.meibo888.top/Article/details/gtjyomassz.html

Ruby: ARGV
来源：http://dali.yanxiufei.cn/Article/details/gtqaarannb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gtdteiedyr.html

[M02] 读取环境变量
来源：http://dali.chenlongwang.top/Article/details/gtoiysaemf.html

Py:   os.environ.get("HOME")
来源：http://dali.xziqi.cn/Article/details/gtaievasnk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gtmvbhpvao.html

JS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gtbjcmgwvc.html

TS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gtjsykmhoj.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjvzdzxl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.iojbl.cn/Article/details/gtqxfqzbjz.html

Ruby: ENV["HOME"]
来源：http://dali.chenjidiqi.icu/Article/details/gttkdcqtov.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtzwhedxxd.html

[M03] 执行外部命令
来源：http://dali.zhiwuduotai.top/Article/details/gtvzstwibj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pycfn.com/Article/details/gtyvubbsuj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jyoumei.cn/Article/details/gtlcybdhvz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gtdcbukljx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gtjutraaxw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgfzy.top/Article/details/gtdipbjyhn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhixingplan.top/Article/details/gtavhnbqvq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cashguo.top/Article/details/gtefdvxvec.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hammf.cn/Article/details/gtogtfabrk.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gtnpgbwmcg.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gteplhjzau.html

PHP:  getcwd();
来源：http://dali.bjfxy.top/Article/details/gtooysldtq.html

JS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gtqbnaobvt.html

TS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gthzcfynhz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yangfankeji.com/Article/details/gtshgqaqfk.html

Go:   os.Getwd()
来源：http://dali.yj20258.top/Article/details/gtcjnozbnm.html

Ruby: Dir.pwd
来源：http://dali.hnqzz.top/Article/details/gtxtfidaoa.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.bjfxy.top/Article/details/gtquijwsgy.html

[M05] 设置退出码
来源：http://dali.svipenyu.cn/Article/details/gtzwvpplio.html

Py:   sys.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtlpymfshj.html

PHP:  exit(1);
来源：http://dali.sxryk.cn/Article/details/gttglhoaaz.html

JS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gthvkpurbg.html

TS:   process.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gthasnkevn.html

Java: System.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtkjtibipf.html

Go:   os.Exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtolkxnnmj.html

Ruby: exit 1
来源：http://dali.wangshuangyany.cn/Article/details/gtsafjmzcb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj202588.top/Article/details/gtuydrrnmx.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswclacub.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigfzy.top/Article/details/gtleajpumt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nwbrower.top/Article/details/gteruccppi.html

JS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gtrkddvnir.html

TS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gteuovjhpu.html

Java: System.err.println("err")
来源：http://dali.nanxinkj.top/Article/details/gtttugkghq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuanzhike.top/Article/details/gtrazxaumw.html

Ruby: warn "err"
来源：http://dali.ybcxt.top/Article/details/gtlicatrjo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yueranfly.top/Article/details/gtmqfpmeli.html

[M07] 判断是否为主入口
来源：http://dali.nanxuanxn.top/Article/details/gtpmufydpv.html

Py:   if __name__ == "__main__":
来源：http://dali.daxiang520.top/Article/details/gtpexujkhq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.mhx1999.top/Article/details/gtxckegrjm.html

JS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gtobktmmji.html

TS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gtkyujsbqu.html

Java: public static void main(String[] args)
来源：http://dali.zhixingplan.top/Article/details/gtkqeztkqr.html

Go:   func main()
来源：http://dali.316326.xyz/Article/details/gtovawmdql.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.andypj.xyz/Article/details/gthzpglbse.html

C#:   static void Main(string[] args)
来源：http://dali.aibaodan.cn/Article/details/gtyjecdtwd.html

[M08] 获取系统与运行时信息
来源：http://dali.yuanzhike.top/Article/details/gtzyhzsszn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.haohaochexian.top/Article/details/gtnobphvqz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuanzx.com/Article/details/gtwsaemgct.html

JS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gtmhqodonl.html

TS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgenvflyt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigfzy.top/Article/details/gtasopehno.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnxiangtu.top/Article/details/gtffchltej.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdvviazj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxinkj.top/Article/details/gtitkfuqty.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtiijltjpb.html

N. 数据结构与算法
来源：http://dali.jqgufenzy.top/Article/details/gtctgspdjo.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gttkomkfvt.html

[N01] 二分查找（有序数组）
来源：http://dali.aibaodan.cn/Article/details/gtzpmmqpzz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtwpiztegf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.birdmap.top/Article/details/gtvmtnczte.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gtcxhtqdnu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gthoqyeamx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gthzoswswg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwuhnkyr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hongshengwenyu.top/Article/details/gthjamiigi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtubhyyfbk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.fzhhl.top/Article/details/gthufogwsx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.0kj1m.cn/Article/details/gtccpkhroz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazmriroh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtaegouksx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gtszuthyxk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gtzipgjbfo.html

Go:   slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gtieqvgxyb.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gtnlzjbyrw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgfzy.top/Article/details/gtbljoxgfm.html

[N03] 快速排序（分治示例）
来源：http://dali.chenzaomai.com/Article/details/gtxthyillj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xziqi.cn/Article/details/gtnmhaebza.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gaohongyu789.top/Article/details/gtpoyjymba.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gtujzhdzfu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gtxmttuggl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guannengcc.top/Article/details/gtzgixxgbe.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gzhubu.top/Article/details/gttqnwarwc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhengqikj.top/Article/details/gtgfkxowxy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guannengcc.top/Article/details/gtfqskdnzo.html

[N04] 斐波那契数列
来源：http://dali.hnqzz.top/Article/details/gtnzupyzym.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shzxlz.cn/Article/details/gtsmkwlapr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gtdgourhqt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtthzdtorj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtewebgzhw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sweek.top/Article/details/gtjbnhrxpf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.iojbl.cn/Article/details/gtvofxcywu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gtxwzrmljs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtufsysnog.html

[N05] 最大公约数
来源：http://dali.sufxvd.cn/Article/details/gtsuxwxhxc.html

Py:   math.gcd(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtmmiaiszy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tianlin.xyz/Article/details/gtabloxkdd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gtbmzkwoqt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gtjgjrmwyf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenzaomai.com/Article/details/gtzptfumvk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guannengcc.top/Article/details/gtclwbpnqh.html

Ruby: a.gcd(b)
来源：http://dali.tanke756.top/Article/details/gtifpydnqw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yanxiufei.cn/Article/details/gtnyrpyhif.html

[N06] 判断回文字符串
来源：http://dali.smart0.xyz/Article/details/gtkggzhixi.html

Py:   s == s[::-1]
来源：http://dali.sufxvd.cn/Article/details/gtmuxalnah.html

PHP:  $s === strrev($s);
来源：http://dali.redwolf501.top/Article/details/gtvujbmrfy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtdbhsaefm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtkqncuowz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yueranfly.top/Article/details/gtgpeieovz.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gtwowswlji.html

Ruby: s == s.reverse
来源：http://dali.ppjwa.cn/Article/details/gtgvscuvea.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gthxgnnxwx.html

[N07] 两数之和（返回下标）
来源：http://dali.fzhhl.top/Article/details/gtpztyyiio.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yangfankeji.com/Article/details/gtlycxpxbq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258.top/Article/details/gtxvmlmdzw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.bjfxy.top/Article/details/gthfwfxjfb.html

TS:   // 手写 Map<string, number>
来源：http://dali.hongshengwenyu.top/Article/details/gtvjfqozru.html

Java: // 手写 HashMap
来源：http://dali.pycfn.com/Article/details/gtnrsjaxie.html

Go:   // 手写 map[int]int
来源：http://dali.c1oappe.top/Article/details/gtaexszyws.html

Ruby: // 手写 Hash
来源：http://dali.kuanghao11.cn/Article/details/gtfkypouma.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.feifeiyinyue.top/Article/details/gtjocnrzha.html

[N08] 生成全排列
来源：http://dali.sufxvd.cn/Article/details/gtheogzbwz.html

Py:   itertools.permutations(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtjawffqoo.html

PHP:  // 手写递归交换
来源：http://dali.jyoumei.cn/Article/details/gtewxkfszy.html

JS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtsjstumbp.html

TS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtpkhghdfk.html

Java: // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gthstskjfz.html

Go:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtuczmwwyq.html

Ruby: arr.permutation.to_a
来源：http://dali.chenzaomai.com/Article/details/gtnamfvduo.html

C#:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtupemsjce.html

[N09] 栈与队列
来源：http://dali.kuanghao11.cn/Article/details/gtxsdkzulx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.svipenyu.cn/Article/details/gtsxnfnynt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sweek.top/Article/details/gtdfmwjwih.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtdtgtdvdb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ppjwa.cn/Article/details/gtyylafajy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ivvv.top/Article/details/gtjjdyotmx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sufxvd.cn/Article/details/gtjqdotipy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefamtiix.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnqzz.top/Article/details/gtfywwkpqr.html

[N10] 链表节点定义
来源：http://dali.hysaishi.cn/Article/details/gtzqzzgxjt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sweek.top/Article/details/gtrgpziwuu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ehwqpu.com/Article/details/gtbwkkwveb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yvedp.cn/Article/details/gtoemiadkx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgfzy.top/Article/details/gtobnbdumt.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258.top/Article/details/gtjzroqfok.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tian-w.cn/Article/details/gtjfjuswdg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hfpthk.cn/Article/details/gtretqparf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhengqikj.top/Article/details/gttklihttp.html

[N11] 二叉树中序遍历
来源：http://dali.yvedp.cn/Article/details/gtyfxvkykp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.316326.xyz/Article/details/gtwslidrbe.html

PHP:  // 手写递归函数
来源：http://dali.cheryme.top/Article/details/gtgwapmpfo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pengpengdd.cyou/Article/details/gtussdwuui.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenlongwang.top/Article/details/gthgksxbrz.html

Java: // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtcaekgxck.html

Go:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtexwywwzi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guowangkeji.top/Article/details/gtmsudciyy.html

C#:   // 手写递归
来源：http://dali.birdmap.top/Article/details/gtjozzlulb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzcggumx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daria6918.cn/Article/details/gtdogpgiyl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yongpay.top/Article/details/gtbsiwtcvh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.kuanghao11.cn/Article/details/gthpkwomkc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gthveryxsv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gthebhtoln.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yvedp.cn/Article/details/gtqmwkvbvw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cucudq.cn/Article/details/gtrblozrkf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gtzjlaubui.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtvkxyiuhh.html

O. 并发与异步
来源：http://dali.guowangkeji.top/Article/details/gtzmyxcuaj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtapuiqlsr.html

[O01] 启动一个线程
来源：http://dali.hywenlv.cn/Article/details/gtqbylkgxt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.snrcjt.cn/Article/details/gtazgaltvp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dianchejie.cn/Article/details/gtqzhvbckx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhiwuduotai.top/Article/details/gtmukwvyiy.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnpbtvln.html

Java: new Thread(() -> f()).start()
来源：http://dali.sysykeji.top/Article/details/gthxkjabej.html

Go:   go f()
来源：http://dali.bjfxy.top/Article/details/gtfeidmqpg.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoypvcwpb.html

C#:   Task.Run(() => F());
来源：http://dali.xinyue.icu/Article/details/gtornayvts.html

[O02] 使用线程池
来源：http://dali.ydzc1.top/Article/details/gtxpxgvvyb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aizwys.cn/Article/details/gtnuoglhmn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangshuangyany.cn/Article/details/gtdsywpyod.html

JS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gtywivvmbi.html

TS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gtvdjbrnum.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xuetiantiany.cn/Article/details/gttdbxqiii.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnqzz.top/Article/details/gthfcibdcu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xinyue.icu/Article/details/gtdfbugehz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.havefunace.top/Article/details/gtaqxnytrs.html

[O03] 加锁保护共享数据
来源：http://dali.zycfv.cn/Article/details/gtmtawaata.html

Py:   with lock: shared += 1
来源：http://dali.jyoumei.cn/Article/details/gtsvzgrlvz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.dianchejie.cn/Article/details/gtisytmwsg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ppjwa.cn/Article/details/gtrbujvgdq.html

TS:   // 同 JS
来源：http://dali.jlsjyb.cn/Article/details/gtlgfxvkmj.html

Java: synchronized (this) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gtiglhdniv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gotoacloud.top/Article/details/gtqzriyzky.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hammf.cn/Article/details/gtcihrrktm.html

C#:   lock (gate) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gttboqjqoe.html

[O04] 定义异步函数并等待
来源：http://dali.jlsjyb.cn/Article/details/gtqnznoqua.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigufen.top/Article/details/gtwwwwvjjx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.fengsongda.top/Article/details/gtmvjdxhtr.html

JS:   async function f() { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gtxxylusho.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cheryme.top/Article/details/gtjashjspu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yvedp.cn/Article/details/gtnpdhnmvl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgbqhrtk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yueranfly.top/Article/details/gtpscapleq.html

C#:   async Task F() { await G(); }
来源：http://dali.sweek.top/Article/details/gtukhnrozr.html

[O05] 并发执行并等待全部完成
来源：http://dali.nanxinkj.top/Article/details/gtzwwwvlfc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zycfv.cn/Article/details/gtufwcaljy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shzxlz.cn/Article/details/gtwbfkvmls.html

JS:   await Promise.all(tasks)
来源：http://dali.vqdsnc.cn/Article/details/gtlceelyqs.html

TS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gticypvxoj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jyoumei.cn/Article/details/gtontgpvmz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.redwolf501.top/Article/details/gthsgknrgj.html

Ruby: threads.map(&:join)
来源：http://dali.meibo888.top/Article/details/gttrppifmd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.dashuyun.cn/Article/details/gtqaozarek.html

[O06] 使用进程池
来源：http://dali.jlsjyb.cn/Article/details/gtsyjsunih.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.0kj1m.cn/Article/details/gtlcnwxztu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.iojbl.cn/Article/details/gtwliwtibj.html

JS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gtmphhykcj.html

TS:   // child_process / cluster 模块
来源：http://dali.jinqigufen.top/Article/details/gtnyylrncs.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.bjfxy.top/Article/details/gtxmaucfvi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yvedp.cn/Article/details/gtmfoszzis.html

Ruby: // fork 块
来源：http://dali.tanke756.top/Article/details/gtcffofdgk.html

C#:   Parallel.For
来源：http://dali.yj202588.top/Article/details/gtdtrfsunx.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtdnxgcqol.html

P. 常用工具函数
来源：http://dali.yangfankeji.com/Article/details/gtpgeunspt.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlaxaiflg.html

[P01] 生成 UUID
来源：http://dali.cheryme.top/Article/details/gtyopavrnb.html

Py:   str(uuid.uuid4())
来源：http://dali.jlsjyb.cn/Article/details/gtmnfemofa.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.svipenyu.cn/Article/details/gtgnfpvtwu.html

JS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gteykeoqge.html

TS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gtdiehbsms.html

Java: UUID.randomUUID().toString()
来源：http://dali.xylfe.cn/Article/details/gtfkeycqgw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.bjfxy.top/Article/details/gtlmhjgpsm.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgufenzy.top/Article/details/gtiwbrhcrp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuanzx.com/Article/details/gteifnyaau.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhixingplan.top/Article/details/gtvrqqpijj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.fzhhl.top/Article/details/gtsblxptao.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ydzc1.top/Article/details/gtbbvubcwb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aibaodan.cn/Article/details/gtxqyqugzw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuetiantiany.cn/Article/details/gthckpjuve.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sweek.top/Article/details/gtmyqqqtab.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hnqzz.top/Article/details/gtqrbridxg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.snrcjt.cn/Article/details/gtkapqrskm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.fzhhl.top/Article/details/gtunlxhueg.html

[P03] 生成短随机字符串
来源：http://dali.0kj1m.cn/Article/details/gtmgbqfxnv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj202588.top/Article/details/gtdrijvnsu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.vqdsnc.cn/Article/details/gtrxpgnsfm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gtdpxvapfb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gtvgalkleq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xylfe.cn/Article/details/gtdcyglbeo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shzxlz.cn/Article/details/gtciwpqnha.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.birdmap.top/Article/details/gtfeghhtqv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shangyingyoupin.top/Article/details/gtwdwfyqrw.html

[P04] 求长度
来源：http://dali.hnqzz.top/Article/details/gtjqatmzlt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cheryme.top/Article/details/gtyrfhsgxb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtclrenqwh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sxryk.cn/Article/details/gtloanaaaf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gtykdzrwvm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.andypj.xyz/Article/details/gtapiqhyci.html

Go:   len(arr);  len(m)
来源：http://dali.svipenyu.cn/Article/details/gtyxbovqqw.html

Ruby: x.length;  x.size
来源：http://dali.yj20258888.top/Article/details/gtknonkprz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gthhgejsji.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ehwqpu.com/Article/details/gtuqxllbuh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258.top/Article/details/gthwivzdqc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.316326.xyz/Article/details/gtpyyyghjl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sufxvd.cn/Article/details/gtweoeuanv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gtzhqobfog.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cucudq.cn/Article/details/gtzetywsqs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenzaomai.com/Article/details/gtphbkpanv.html

Ruby: a == b
来源：http://dali.tian-w.cn/Article/details/gtoqpphyns.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigufen.top/Article/details/gtkbpvlems.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdmnbsxm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxuanxn.top/Article/details/gtyxxqpkft.html

PHP:  if (empty($x)) {}
来源：http://dali.zdqjudy.top/Article/details/gtkhbecpnp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gogol.net.cn/Article/details/gtcvgbmxaw.html

TS:   if (x == null) {}
来源：http://dali.jlsjyb.cn/Article/details/gtfchutuog.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hammf.cn/Article/details/gtkqhxcysl.html

Go:   if x == nil {}
来源：http://dali.chenjidiqi.icu/Article/details/gtwddtsxhu.html


<!-- 参考信息 -->