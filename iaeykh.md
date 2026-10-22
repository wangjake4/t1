代发 wailian999

JS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtqlbqcusg.html

TS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmzomrzn.html

Java: args 数组（main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfxrhdzm.html

Go:   os.Args[1:]
来源：http://dali.cashguo.top/Article/details/gtuksadzmc.html

Ruby: ARGV
来源：http://dali.daxiang520.top/Article/details/gtardqskco.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtfuokfxzr.html

[M02] 读取环境变量
来源：http://dali.yueranfly.top/Article/details/gtidlxxnse.html

Py:   os.environ.get("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtmlsewuat.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tanke756.top/Article/details/gtxadkcfka.html

JS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gtyatwarxy.html

TS:   process.env.HOME
来源：http://dali.tanke756.top/Article/details/gtmcxikebj.html

Java: System.getenv("HOME")
来源：http://dali.havefunace.top/Article/details/gtitoznufs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtalvfuwjg.html

Ruby: ENV["HOME"]
来源：http://dali.xuetiantiany.cn/Article/details/gtlarjbiyq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtmuwuuiwa.html

[M03] 执行外部命令
来源：http://dali.gotoacloud.top/Article/details/gtbchyiqgq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hywenlv.cn/Article/details/gtewledgmg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenzaomai.com/Article/details/gtegkructa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpjfpcec.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gtrksiulsw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pycfn.com/Article/details/gtifwxiefv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuxming.cn/Article/details/gtgvjnogid.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwfxrskw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhengqikj.top/Article/details/gteqsigchj.html

[M04] 获取当前工作目录
来源：http://dali.aizwys.cn/Article/details/gtdbuaumjk.html

Py:   os.getcwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtvytwftao.html

PHP:  getcwd();
来源：http://dali.redwolf501.top/Article/details/gtdpwhdipa.html

JS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gtngnbclfc.html

TS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gtlbcmdlxx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ehwqpu.com/Article/details/gtnclvqpze.html

Go:   os.Getwd()
来源：http://dali.zhoulong.xyz/Article/details/gthczbtwid.html

Ruby: Dir.pwd
来源：http://dali.nwbrower.top/Article/details/gtmbfulukt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhengqikj.top/Article/details/gtlkjlpxkc.html

[M05] 设置退出码
来源：http://dali.wangdashe.top/Article/details/gtfnutigdd.html

Py:   sys.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtujvsfsba.html

PHP:  exit(1);
来源：http://dali.fengsongda.top/Article/details/gtdefxcmih.html

JS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtvxhltxgi.html

TS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtafepvghp.html

Java: System.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtsgoealxv.html

Go:   os.Exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtmnofstoc.html

Ruby: exit 1
来源：http://dali.xziqi.cn/Article/details/gtinlyjcst.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenzaomai.com/Article/details/gtezobcfda.html

[M06] 向标准错误输出
来源：http://dali.bjfxy.top/Article/details/gtsemkhwuj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gttatpbskl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pengpengdd.cyou/Article/details/gtuethqhbv.html

JS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gtnhicnlij.html

TS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gtznlxzqxy.html

Java: System.err.println("err")
来源：http://dali.nanxuanxn.top/Article/details/gtegqsvjnt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shuidangran.top/Article/details/gtxtjufeqw.html

Ruby: warn "err"
来源：http://dali.xuanzx.com/Article/details/gtpkjafdfd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jianghu66.top/Article/details/gtmyneoxja.html

[M07] 判断是否为主入口
来源：http://dali.aibaodan.cn/Article/details/gtaeozoikh.html

Py:   if __name__ == "__main__":
来源：http://dali.tianlin.xyz/Article/details/gtshupuvun.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gtypaytmms.html

JS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gthudakotm.html

TS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gtbwmkmvar.html

Java: public static void main(String[] args)
来源：http://dali.cashguo.top/Article/details/gtgygzgmjp.html

Go:   func main()
来源：http://dali.nwbrower.top/Article/details/gtfgtrqdim.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxuanxn.top/Article/details/gtwalnogqi.html

C#:   static void Main(string[] args)
来源：http://dali.xylfe.cn/Article/details/gtrvqnjono.html

[M08] 获取系统与运行时信息
来源：http://dali.zhengqikj.top/Article/details/gtrbimbwgj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.mhx1999.top/Article/details/gtonnvshra.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ehwqpu.com/Article/details/gteqdvuucr.html

JS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gtqoxolrum.html

TS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gtaiobdsor.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hongshengwenyu.top/Article/details/gtnsfcmdep.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.svipenyu.cn/Article/details/gtmfvcrgnv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.aibaodan.cn/Article/details/gtkpzqetea.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tianlin.xyz/Article/details/gtgtkzbnrx.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gteynnukww.html

N. 数据结构与算法
来源：http://dali.wangdashe.top/Article/details/gtzwdjqore.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtxhnkhoth.html

[N01] 二分查找（有序数组）
来源：http://dali.chenzaomai.com/Article/details/gteboccjhi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtenmyaoqm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtbhfxpadd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtyseifduk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gttlhpwlib.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtlksuleer.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cucudq.cn/Article/details/gthhnwrpvg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ehwqpu.com/Article/details/gtkiwkiwup.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtynvqmvao.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenzaomai.com/Article/details/gtjpntketb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj202588.top/Article/details/gteunogwcw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yangfankeji.com/Article/details/gtyzhzanez.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtdxfnptkk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gtqlhvxgvq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxinkj.top/Article/details/gtzlrhsslv.html

Go:   slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtfxtfwrwj.html

Ruby: arr.sort
来源：http://dali.yuanzhike.top/Article/details/gtkhjlnzmp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yangfankeji.com/Article/details/gtafikzfzz.html

[N03] 快速排序（分治示例）
来源：http://dali.chenzaomai.com/Article/details/gtqsvhdaus.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ehwqpu.com/Article/details/gtnqthzuep.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cqqwz.cn/Article/details/gtvrihbyre.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gtsuwrvufj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gtotdpzhfj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shangyingyoupin.top/Article/details/gtljuuphrw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yvedp.cn/Article/details/gtrobbrpix.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daria6918.cn/Article/details/gtsllrsrgk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadjwjljt.html

[N04] 斐波那契数列
来源：http://dali.jianghu66.top/Article/details/gthuhnuunj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gtzwmzxeoo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dashuyun.cn/Article/details/gtnuaorkyf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gthyvcyvtx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtqsqrklua.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258.top/Article/details/gtwswujkcp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.bjfxy.top/Article/details/gtzbbuelro.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.0kj1m.cn/Article/details/gtwbcsasig.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gtphxrfmtl.html

[N05] 最大公约数
来源：http://dali.dashuyun.cn/Article/details/gtnzwawbfb.html

Py:   math.gcd(a, b)
来源：http://dali.sufxvd.cn/Article/details/gttjoddafw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guannengcc.top/Article/details/gtdtngcqfc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzezdjeos.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gtiurikcgl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fzhhl.top/Article/details/gtsyapsavx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.vqdsnc.cn/Article/details/gthpfwgoyx.html

Ruby: a.gcd(b)
来源：http://dali.sxryk.cn/Article/details/gtmfvkwgia.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtofngqyqj.html

[N06] 判断回文字符串
来源：http://dali.daxiang520.top/Article/details/gtggzzzbax.html

Py:   s == s[::-1]
来源：http://dali.iojbl.cn/Article/details/gtthrimvqe.html

PHP:  $s === strrev($s);
来源：http://dali.jlsjyb.cn/Article/details/gtosbbnqpz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtqrhjawua.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtajezsami.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.svipenyu.cn/Article/details/gtofkwanku.html

Go:   // 双指针从两端比较
来源：http://dali.chenzaomai.com/Article/details/gthquzrlsg.html

Ruby: s == s.reverse
来源：http://dali.fengsongda.top/Article/details/gtutmbrmjr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gtpplpjwlz.html

[N07] 两数之和（返回下标）
来源：http://dali.316326.xyz/Article/details/gtxtxsazwr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tianlin.xyz/Article/details/gttwkxztwt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgufenzy.top/Article/details/gtgbeexeyq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhixingplan.top/Article/details/gtpkbgutun.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxuanxn.top/Article/details/gtrxfgkpsk.html

Java: // 手写 HashMap
来源：http://dali.yueranfly.top/Article/details/gtropeigae.html

Go:   // 手写 map[int]int
来源：http://dali.nanxuanxn.top/Article/details/gtvhawurpz.html

Ruby: // 手写 Hash
来源：http://dali.gzhubu.top/Article/details/gtvfhxjrnm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dianchejie.cn/Article/details/gthrwoswsk.html

[N08] 生成全排列
来源：http://dali.redwolf501.top/Article/details/gtghayszja.html

Py:   itertools.permutations(arr)
来源：http://dali.fzhhl.top/Article/details/gthlmdluzt.html

PHP:  // 手写递归交换
来源：http://dali.redwolf501.top/Article/details/gtaedxccdk.html

JS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtmjymwayo.html

TS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtdvzmqpup.html

Java: // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtwngxqxst.html

Go:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtjrumtyfw.html

Ruby: arr.permutation.to_a
来源：http://dali.meibo888.top/Article/details/gtdnstdgsl.html

C#:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtfwdusdrm.html

[N09] 栈与队列
来源：http://dali.svipenyu.cn/Article/details/gtcycbbgek.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzehpriyt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyywdhfn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtzxazbjfm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tanke756.top/Article/details/gtjuyisvyk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.kuanghao11.cn/Article/details/gtkuazbveg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.guowangkeji.top/Article/details/gtcqkygfoi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtlloqfrvz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.snrcjt.cn/Article/details/gttkkpslxu.html

[N10] 链表节点定义
来源：http://dali.shangyingyoupin.top/Article/details/gtpgawjfym.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.316326.xyz/Article/details/gtciunnqhy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.haohaochexian.top/Article/details/gtdepypzod.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvelwjss.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenjidiqi.icu/Article/details/gtkxtronfa.html

Java: class Node { int v; Node next; }
来源：http://dali.daxiang520.top/Article/details/gtaorvkkch.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gaohongyu789.top/Article/details/gtvqepofyo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqkpsevr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttzsqator.html

[N11] 二叉树中序遍历
来源：http://dali.tanke756.top/Article/details/gtlrcityax.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shzxlz.cn/Article/details/gtoeiottri.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gtvdikhanb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgufenzy.top/Article/details/gtjxbuloav.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shzxlz.cn/Article/details/gtkptzqnip.html

Java: // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtamairbiu.html

Go:   // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gtosthxuvv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cdnleiting.top/Article/details/gtmdmegptq.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gtfhzqnada.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.316326.xyz/Article/details/gtptpgnvhq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj20258888.top/Article/details/gtfjhmdixj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.316326.xyz/Article/details/gtwyzjoajt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gtoaayufgn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hysaishi.cn/Article/details/gtqemovakq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhiwuduotai.top/Article/details/gtbqgsxlkr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yonumen.top/Article/details/gtaqroapbt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgveutia.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gtvdozhjfi.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtxcgbyfvf.html

O. 并发与异步
来源：http://dali.pengpengdd.cyou/Article/details/gtuftmwhpo.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtymyoexru.html

[O01] 启动一个线程
来源：http://dali.haohaochexian.top/Article/details/gtltkdgjls.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.svipenyu.cn/Article/details/gtondfdixt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.pycfn.com/Article/details/gtkglivvgt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuanzhike.top/Article/details/gtevobbcre.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtppcchgkd.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenjidiqi.icu/Article/details/gtshkuuhzr.html

Go:   go f()
来源：http://dali.yanxiufei.cn/Article/details/gtvsymscdk.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpeftrqmy.html

C#:   Task.Run(() => F());
来源：http://dali.bjfxy.top/Article/details/gtsvgaoysc.html

[O02] 使用线程池
来源：http://dali.cdnleiting.top/Article/details/gtizgmhibi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhoulong.xyz/Article/details/gtjtymcbwd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daxiang520.top/Article/details/gtvwahfysz.html

JS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gtzcvjlbhp.html

TS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gtbtgkwdfh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yongpay.top/Article/details/gtkijkgoir.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xuetiantiany.cn/Article/details/gtlzzrdhas.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gtptoluvpj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.0kj1m.cn/Article/details/gtzkjaipfu.html

[O03] 加锁保护共享数据
来源：http://dali.shuidangran.top/Article/details/gtsoxvwtbr.html

Py:   with lock: shared += 1
来源：http://dali.wangdashe.top/Article/details/gtrmnzkgtf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.bjfxy.top/Article/details/gtbdhqfngl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jianghu66.top/Article/details/gtgmeotssj.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gtldkaixfs.html

Java: synchronized (this) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjufvaskx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.birdmap.top/Article/details/gtvttvjhbm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guannengcc.top/Article/details/gtmskoeryu.html

C#:   lock (gate) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gttqurwarv.html

[O04] 定义异步函数并等待
来源：http://dali.zhoulong.xyz/Article/details/gtzynilzqa.html

Py:   async def f():⏎    await g()
来源：http://dali.fzhhl.top/Article/details/gtlvhgavyz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cheryme.top/Article/details/gtzkpksivi.html

JS:   async function f() { await g(); }
来源：http://dali.tian-w.cn/Article/details/gtgenruhaf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.wangdashe.top/Article/details/gtpaxnpjpr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.bjfxy.top/Article/details/gtxcniwfqg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hysaishi.cn/Article/details/gtxumqsxee.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhiwuduotai.top/Article/details/gteeffcdxx.html

C#:   async Task F() { await G(); }
来源：http://dali.sysykeji.top/Article/details/gtofxbsjbs.html

[O05] 并发执行并等待全部完成
来源：http://dali.kuanghao11.cn/Article/details/gtwdiqywmo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tianlin.xyz/Article/details/gtbkzrmlqw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jianghu66.top/Article/details/gtjegowyun.html

JS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gteeicuhfu.html

TS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gtdcmpyitv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigfzy.top/Article/details/gtkzchjspb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xuanzx.com/Article/details/gtoxrawfss.html

Ruby: threads.map(&:join)
来源：http://dali.yuanzhike.top/Article/details/gtypcbbume.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nanxinkj.top/Article/details/gttmsnwqyg.html

[O06] 使用进程池
来源：http://dali.yvedp.cn/Article/details/gtmcnzwqkh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sweek.top/Article/details/gtomflujtj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hongshengwenyu.top/Article/details/gtxhooditq.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gtptcyhitd.html

TS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gtcgofsqga.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.snrcjt.cn/Article/details/gtuokdjwgz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zdqjudy.top/Article/details/gtaadedrkf.html

Ruby: // fork 块
来源：http://dali.vqdsnc.cn/Article/details/gtkbglrniw.html

C#:   Parallel.For
来源：http://dali.vqdsnc.cn/Article/details/gtlttfbnie.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzuluyeok.html

P. 常用工具函数
来源：http://dali.guannengcc.top/Article/details/gtvgqfzrsp.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtteyuedna.html

[P01] 生成 UUID
来源：http://dali.birdmap.top/Article/details/gtisyktsbz.html

Py:   str(uuid.uuid4())
来源：http://dali.hywenlv.cn/Article/details/gtqcnocuko.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenjidiqi.icu/Article/details/gtmukdlaol.html

JS:   crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gtkdyypzgd.html

TS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gtgafcjlkh.html

Java: UUID.randomUUID().toString()
来源：http://dali.meibo888.top/Article/details/gtstixxfzt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.redwolf501.top/Article/details/gtminltcoi.html

Ruby: SecureRandom.uuid
来源：http://dali.hnqzz.top/Article/details/gtjwsmzijr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yueranfly.top/Article/details/gtpwatzusq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.mhx1999.top/Article/details/gtbijcigbu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jqgufenzy.top/Article/details/gtclsejqsw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yuanzhike.top/Article/details/gtafqhlaem.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guowangkeji.top/Article/details/gtlakthwwo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuerpqqpm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangdashe.top/Article/details/gtdvptbjyn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenlongwang.top/Article/details/gthuvhdmbf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jianghu66.top/Article/details/gtrtigfhkt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuanzx.com/Article/details/gtpwlswxkn.html

[P03] 生成短随机字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gteoxzzdoq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hnxiangtu.top/Article/details/gtnjhkzefy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shangyingyoupin.top/Article/details/gtjoahyypj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tianlin.xyz/Article/details/gtfunckabg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgfzy.top/Article/details/gthsymrcln.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhongyouzk.top/Article/details/gtwdctjddv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xuetiantiany.cn/Article/details/gtemfxxrrg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hfpthk.cn/Article/details/gtwxxagbcl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jiagoushi.top/Article/details/gtencpvdpf.html

[P04] 求长度
来源：http://dali.0kj1m.cn/Article/details/gtgyknojyh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tianlin.xyz/Article/details/gtchyicirn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtsnphdklj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gtsnlrkfjq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.vqdsnc.cn/Article/details/gtecakzyaj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sweek.top/Article/details/gtdxvavkof.html

Go:   len(arr);  len(m)
来源：http://dali.hfpthk.cn/Article/details/gtmwhbwuun.html

Ruby: x.length;  x.size
来源：http://dali.jianghu66.top/Article/details/gtocoieoqz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gtsxmpncjv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.316326.xyz/Article/details/gttyhqkzhz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.316326.xyz/Article/details/gtjbfmbera.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj20258.top/Article/details/gtvoplidbl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuxming.cn/Article/details/gtadgygprb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj202588.top/Article/details/gtpjoxvodo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hnqzz.top/Article/details/gtpvxqargh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndcrkmjx.html

Ruby: a == b
来源：http://dali.ydzc1.top/Article/details/gtgfspubkl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.redwolf501.top/Article/details/gtbvyufzjm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.mhx1999.top/Article/details/gtiwupukme.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.havefunace.top/Article/details/gtouyhzqdq.html

PHP:  if (empty($x)) {}
来源：http://dali.sweek.top/Article/details/gtnhnrqnux.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnqzz.top/Article/details/gtwqiiqwox.html

TS:   if (x == null) {}
来源：http://dali.zhongyouzk.top/Article/details/gtaydcknka.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtxikqozgb.html

Go:   if x == nil {}
来源：http://dali.cashguo.top/Article/details/gtygjsxqhw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxuanxn.top/Article/details/gtlibcqhut.html

C#:   if (x is null) {}
来源：http://dali.c1oappe.top/Article/details/gthfjtzquk.html

[P07] 防抖与节流
来源：http://dali.yonumen.top/Article/details/gtlilkadiy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.svipenyu.cn/Article/details/gtmtzfwsew.html

PHP:  // 手写时间戳比较
来源：http://dali.nanxuanxn.top/Article/details/gtqkmqlyyw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtapwjklye.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gtmgqvchww.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daxiang520.top/Article/details/gtzofobgez.html


<!-- 参考信息 -->