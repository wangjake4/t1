代发 wailian999

JS:   process.argv.slice(2)
来源：http://dali.guowangkeji.top/Article/details/gtyfduutgg.html

TS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtqkhfrvdf.html

Java: args 数组（main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gtrvetmajy.html

Go:   os.Args[1:]
来源：http://dali.gaohongyu789.top/Article/details/gtxyiwatfx.html

Ruby: ARGV
来源：http://dali.jqgufenzy.top/Article/details/gtzaahneeh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gtknwbcksx.html

[M02] 读取环境变量
来源：http://dali.aibaodan.cn/Article/details/gtqbiuwbwz.html

Py:   os.environ.get("HOME")
来源：http://dali.yj202588.top/Article/details/gtgdswlthq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gtaikgepcd.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjmkbqjq.html

TS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gtewonyqqp.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtshexfelj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtzazjmddp.html

Ruby: ENV["HOME"]
来源：http://dali.hysaishi.cn/Article/details/gtfydxsrzk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtoztwaxnq.html

[M03] 执行外部命令
来源：http://dali.tian-w.cn/Article/details/gtgeqzztrv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtpceuwdjo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxinkj.top/Article/details/gtenrkjznx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gtjaubpvuy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gtewzrbrhz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.redwolf501.top/Article/details/gttccndafs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.mhx1999.top/Article/details/gtlixgjyud.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sysykeji.top/Article/details/gtwiuutkfu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hfpthk.cn/Article/details/gtnnlsksau.html

[M04] 获取当前工作目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiaqynssx.html

Py:   os.getcwd()
来源：http://dali.hnxiangtu.top/Article/details/gtpqajuuoj.html

PHP:  getcwd();
来源：http://dali.tian-w.cn/Article/details/gtntyovwdc.html

JS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkktrhzst.html

TS:   process.cwd()
来源：http://dali.chenlongwang.top/Article/details/gtihpvxjjm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guannengcc.top/Article/details/gtlixqmsuq.html

Go:   os.Getwd()
来源：http://dali.fzhhl.top/Article/details/gtgfbuqjir.html

Ruby: Dir.pwd
来源：http://dali.quarkkingdee.top/Article/details/gteuazjuzy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj202588.top/Article/details/gtgcoqictl.html

[M05] 设置退出码
来源：http://dali.iojbl.cn/Article/details/gtsmkgzzdr.html

Py:   sys.exit(1)
来源：http://dali.pycfn.com/Article/details/gtowovsvdq.html

PHP:  exit(1);
来源：http://dali.sysykeji.top/Article/details/gtgpaxywjx.html

JS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gtrbmsxwzd.html

TS:   process.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtqmclwtmf.html

Java: System.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtbhqjwlas.html

Go:   os.Exit(1)
来源：http://dali.redwolf501.top/Article/details/gtsondylzm.html

Ruby: exit 1
来源：http://dali.hnxiangtu.top/Article/details/gtblqlyked.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cdnleiting.top/Article/details/gtaiwblwil.html

[M06] 向标准错误输出
来源：http://dali.cucudq.cn/Article/details/gtrkytbzef.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shuidangran.top/Article/details/gtslsuvfgf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yueranfly.top/Article/details/gtkjbjxill.html

JS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gtwzprasux.html

TS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gtsweacnua.html

Java: System.err.println("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtckwhygvz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjiqnufgr.html

Ruby: warn "err"
来源：http://dali.sufxvd.cn/Article/details/gtxqbyoqxj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tanke756.top/Article/details/gtfviyhwcy.html

[M07] 判断是否为主入口
来源：http://dali.yuanzhike.top/Article/details/gtagletqnu.html

Py:   if __name__ == "__main__":
来源：http://dali.hfpthk.cn/Article/details/gtgypcdyha.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cqqwz.cn/Article/details/gtkjkyefbz.html

JS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gtypfbgzop.html

TS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gtajvsqozg.html

Java: public static void main(String[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gtzyrqwoug.html

Go:   func main()
来源：http://dali.hnxiangtu.top/Article/details/gtdbxqmzws.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aizwys.cn/Article/details/gtforcruyd.html

C#:   static void Main(string[] args)
来源：http://dali.316326.xyz/Article/details/gtceqqsjrx.html

[M08] 获取系统与运行时信息
来源：http://dali.meibo888.top/Article/details/gtzqyswrwx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlyagavj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.svipenyu.cn/Article/details/gtfndyzqlp.html

JS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gtoiwefzpy.html

TS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gtrxguyzmv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.smart0.xyz/Article/details/gtyzglggwx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guannengcc.top/Article/details/gtvhnntkmm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangdashe.top/Article/details/gtufxcxyym.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigufen.top/Article/details/gtmkjorzwh.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtpknvxxdx.html

N. 数据结构与算法
来源：http://dali.hongshengwenyu.top/Article/details/gtubpcycds.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtzrguegox.html

[N01] 二分查找（有序数组）
来源：http://dali.daria6918.cn/Article/details/gtukptzjaf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtwwnkyyet.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gthrqhmxri.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gtvkbfovvs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtcujvaxcb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtyodhogcl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtygrlqeqy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jianghu66.top/Article/details/gtjauxrxrg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtsqxibebv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tian-w.cn/Article/details/gtdtbdvdzv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gtgysjztxo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ehwqpu.com/Article/details/gtydlhoijt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gtzhifmzwb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gthgtcbxis.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yvedp.cn/Article/details/gtmkjxtnrz.html

Go:   slices.Sort(arr)
来源：http://dali.jiagoushi.top/Article/details/gteyhnfxqx.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gtvsavpjsa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cucudq.cn/Article/details/gtprocchlw.html

[N03] 快速排序（分治示例）
来源：http://dali.hywenlv.cn/Article/details/gtmngzmusw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.316326.xyz/Article/details/gtfdidsczc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhoulong.xyz/Article/details/gtwbfstkga.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gtnfjqimca.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gtjgofaiek.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yvedp.cn/Article/details/gtooxigjhs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jiagoushi.top/Article/details/gtmtfyzmri.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hnqzz.top/Article/details/gthmuxonio.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jlsjyb.cn/Article/details/gtxtswhcny.html

[N04] 斐波那契数列
来源：http://dali.dashuyun.cn/Article/details/gtkbrgbues.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gogol.net.cn/Article/details/gtclmvdshf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gtpnqefmhn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtksmuyixn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gtlqpsyfbc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjzbabva.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczqwokpp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.iojbl.cn/Article/details/gtdgudyrmf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtbkelxpwc.html

[N05] 最大公约数
来源：http://dali.zhengqikj.top/Article/details/gtrvwxdjly.html

Py:   math.gcd(a, b)
来源：http://dali.xinyue.icu/Article/details/gtzqqtuxiw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yvedp.cn/Article/details/gtvurybgyn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yueranfly.top/Article/details/gtwfmjstak.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxuanxn.top/Article/details/gtxfgtgibt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fengsongda.top/Article/details/gtlpxfdcjm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sxryk.cn/Article/details/gtfesqtwer.html

Ruby: a.gcd(b)
来源：http://dali.nanxuanxn.top/Article/details/gtzqiyvggr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ivvv.top/Article/details/gtldpufgui.html

[N06] 判断回文字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtukbreiwe.html

Py:   s == s[::-1]
来源：http://dali.guannengcc.top/Article/details/gtqxobhsma.html

PHP:  $s === strrev($s);
来源：http://dali.yuxming.cn/Article/details/gtokikielx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtxvylthva.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtrvpcqwdk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnxiangtu.top/Article/details/gtbibnzitj.html

Go:   // 双指针从两端比较
来源：http://dali.zdqjudy.top/Article/details/gttifwvnib.html

Ruby: s == s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gtigkjslme.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigufen.top/Article/details/gteboyyvse.html

[N07] 两数之和（返回下标）
来源：http://dali.9152youxi.cn/Article/details/gttuqvfwsz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.9152youxi.cn/Article/details/gtavqlzmbj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinqigfzy.top/Article/details/gtsznxydkw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xuetiantiany.cn/Article/details/gtbxhshdjt.html

TS:   // 手写 Map<string, number>
来源：http://dali.yangfankeji.com/Article/details/gtzjznhmhd.html

Java: // 手写 HashMap
来源：http://dali.zdqjudy.top/Article/details/gtaffhholw.html

Go:   // 手写 map[int]int
来源：http://dali.daria6918.cn/Article/details/gtnxccpivm.html

Ruby: // 手写 Hash
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqjkaszr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zdqjudy.top/Article/details/gtyycaghww.html

[N08] 生成全排列
来源：http://dali.yuxming.cn/Article/details/gtueyboqvp.html

Py:   itertools.permutations(arr)
来源：http://dali.gaohongyu789.top/Article/details/gttvllrdto.html

PHP:  // 手写递归交换
来源：http://dali.hysaishi.cn/Article/details/gtmfcldyrt.html

JS:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gthqaltaxy.html

TS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtxeyixhpp.html

Java: // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwblfoyed.html

Go:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtaankcpek.html

Ruby: arr.permutation.to_a
来源：http://dali.0kj1m.cn/Article/details/gtelhxnqgm.html

C#:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtbplcdkuw.html

[N09] 栈与队列
来源：http://dali.yvedp.cn/Article/details/gtdeykhqud.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtftkdgdkd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gtzevgngox.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gtzevdrbed.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenzaomai.com/Article/details/gtirkmubqd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guannengcc.top/Article/details/gtqkfpckon.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xylfe.cn/Article/details/gtzryygnsq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtgaulfzmv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gotoacloud.top/Article/details/gtkrhucbgl.html

[N10] 链表节点定义
来源：http://dali.aibaodan.cn/Article/details/gtfprjnvjl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.316326.xyz/Article/details/gtzwtaagpz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ybcxt.top/Article/details/gtndbgtsbv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hnqzz.top/Article/details/gtkacdpymt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jyoumei.cn/Article/details/gtpnmmhmka.html

Java: class Node { int v; Node next; }
来源：http://dali.gogol.net.cn/Article/details/gtmfpnidvi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ydzc1.top/Article/details/gthfrvvrob.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuanzhike.top/Article/details/gtwwjcrhfj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinqigufen.top/Article/details/gtotvriehh.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigfzy.top/Article/details/gtxytoield.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ivvv.top/Article/details/gtezumybvx.html

PHP:  // 手写递归函数
来源：http://dali.havefunace.top/Article/details/gtvsvmjtpj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gttasohfox.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxuanxn.top/Article/details/gtofovjohn.html

Java: // 手写递归
来源：http://dali.tanke756.top/Article/details/gtelfloksy.html

Go:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gtmfibawlw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hnqzz.top/Article/details/gtljfrbtfl.html

C#:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtbhlwzgeb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tanke756.top/Article/details/gtvvyeqpkg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daria6918.cn/Article/details/gtndyfucnf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gogol.net.cn/Article/details/gtzjrzgbfn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cucudq.cn/Article/details/gtfwsdjpfb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gtyxdmtvjq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gtctxejjfp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gotoacloud.top/Article/details/gtfmbkwgcc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.guannengcc.top/Article/details/gtvzpotuww.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gtlmlcdpnx.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtnhvljdte.html

O. 并发与异步
来源：http://dali.hfpthk.cn/Article/details/gtdkvridxn.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gthnbkdodf.html

[O01] 启动一个线程
来源：http://dali.haohaochexian.top/Article/details/gtliuozaln.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sysykeji.top/Article/details/gtjpxoscpv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hongshengwenyu.top/Article/details/gtbhczjlqy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenlongwang.top/Article/details/gtmycqaxuv.html

TS:   // 同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gtzngxmghz.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangdashe.top/Article/details/gtjidknqau.html

Go:   go f()
来源：http://dali.zhengqikj.top/Article/details/gtqayscqsu.html

Ruby: Thread.new { f }
来源：http://dali.hongshengwenyu.top/Article/details/gthxvmozvn.html

C#:   Task.Run(() => F());
来源：http://dali.zhoulong.xyz/Article/details/gtrliugzta.html

[O02] 使用线程池
来源：http://dali.gogol.net.cn/Article/details/gtafuyzabe.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.316326.xyz/Article/details/gtokzkoyom.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuiiagpqj.html

JS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtlsaibaqd.html

TS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gtsxmeentg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sufxvd.cn/Article/details/gtqkzdtqiy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.dashuyun.cn/Article/details/gtcqlzoabr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.c1oappe.top/Article/details/gttcbnbkny.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tanke756.top/Article/details/gtllcypdki.html

[O03] 加锁保护共享数据
来源：http://dali.tian-w.cn/Article/details/gtklrcwahe.html

Py:   with lock: shared += 1
来源：http://dali.daria6918.cn/Article/details/gtzvmeibgr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfcjbihei.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinyuanbaomall.cn/Article/details/gttcefidvn.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gtgxixhzsw.html

Java: synchronized (this) { shared++; }
来源：http://dali.jiagoushi.top/Article/details/gteutvrjpf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangshuangyany.cn/Article/details/gtatqllgkv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangdashe.top/Article/details/gtmbgqxyih.html

C#:   lock (gate) { shared++; }
来源：http://dali.pycfn.com/Article/details/gtosnqkfcb.html

[O04] 定义异步函数并等待
来源：http://dali.chenjidiqi.icu/Article/details/gtzutijivk.html

Py:   async def f():⏎    await g()
来源：http://dali.hysaishi.cn/Article/details/gtdgnewttm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ehwqpu.com/Article/details/gtgaiwkayw.html

JS:   async function f() { await g(); }
来源：http://dali.c1oappe.top/Article/details/gtgqpwitge.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hywenlv.cn/Article/details/gtmufctvqu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuxming.cn/Article/details/gtmtfgcdlv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ivvv.top/Article/details/gtxgocltfz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ppjwa.cn/Article/details/gtbuceygvr.html

C#:   async Task F() { await G(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqszpvipt.html

[O05] 并发执行并等待全部完成
来源：http://dali.hfpthk.cn/Article/details/gtfzrsmvde.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenzaomai.com/Article/details/gtjteauocz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinqigfzy.top/Article/details/gtuuzbfedy.html

JS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gtnkofdsdz.html

TS:   await Promise.all(tasks)
来源：http://dali.xylfe.cn/Article/details/gtuklstlnc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.vqdsnc.cn/Article/details/gtawtkszsx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.0kj1m.cn/Article/details/gthcrvmsff.html

Ruby: threads.map(&:join)
来源：http://dali.zycfv.cn/Article/details/gtxlyaadkc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sufxvd.cn/Article/details/gthddilruh.html

[O06] 使用进程池
来源：http://dali.pengpengdd.cyou/Article/details/gtgpwzvmdp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.havefunace.top/Article/details/gtmtuzteyf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hysaishi.cn/Article/details/gtwhrgaavx.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gtiedmbqud.html

TS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gtzsjynxvq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuanzhike.top/Article/details/gtvsclgqrj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yonumen.top/Article/details/gtfhawswvh.html

Ruby: // fork 块
来源：http://dali.meibo888.top/Article/details/gtyttqkdgh.html

C#:   Parallel.For
来源：http://dali.guowangkeji.top/Article/details/gtsbxcldod.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtenblypct.html

P. 常用工具函数
来源：http://dali.c1oappe.top/Article/details/gtmhrsykti.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtkgtwxieu.html

[P01] 生成 UUID
来源：http://dali.ppjwa.cn/Article/details/gtgpcqlmpr.html

Py:   str(uuid.uuid4())
来源：http://dali.chenjidiqi.icu/Article/details/gtnszjhytu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.mhx1999.top/Article/details/gtwrxjpdxc.html

JS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gtbxjihrzh.html

TS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gthmqpgrra.html

Java: UUID.randomUUID().toString()
来源：http://dali.guowangkeji.top/Article/details/gtdrqozsvv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gthzrllthk.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gtfljqqeaz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guowangkeji.top/Article/details/gtpeoljuil.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yvedp.cn/Article/details/gtwmpwtcdn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hnqzz.top/Article/details/gtppiolrqw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj202588.top/Article/details/gtyptsrfno.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xylfe.cn/Article/details/gtjucqzhxo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.316326.xyz/Article/details/gtzoutvibe.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtsxyxwkkk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gtqfoekqsz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhengqikj.top/Article/details/gtqarxxwqu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuanzhike.top/Article/details/gtkkpecfdj.html

[P03] 生成短随机字符串
来源：http://dali.c1oappe.top/Article/details/gtkecbnflu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxinkj.top/Article/details/gtbzhnmcwq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.9152youxi.cn/Article/details/gtyrvlgojb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gtbskhrndm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gtznugnpyk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sweek.top/Article/details/gtsvyxbnob.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj202588.top/Article/details/gtbmvdsdiw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gtxqkvagsc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hfpthk.cn/Article/details/gtyczjmcvn.html

[P04] 求长度
来源：http://dali.jinqigufen.top/Article/details/gthtkycmnc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shzxlz.cn/Article/details/gtgpnrutkc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtqaltyzwm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gtjcjmdrlw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gtfagdjmkj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigfzy.top/Article/details/gtgnlhufkd.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258.top/Article/details/gtzohqxupb.html

Ruby: x.length;  x.size
来源：http://dali.haohaochexian.top/Article/details/gtsnxnzjtg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gtcntzuqmx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jyoumei.cn/Article/details/gtyinasicx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xziqi.cn/Article/details/gtfynyijex.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdzmxgvt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cucudq.cn/Article/details/gtvvlbhvsq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhengqikj.top/Article/details/gttlhtfiim.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.havefunace.top/Article/details/gtngdyyogs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtfxurlqmd.html

Ruby: a == b
来源：http://dali.shzxlz.cn/Article/details/gtimzzznzl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljegdmil.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cqqwz.cn/Article/details/gtpmoeierq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tanke756.top/Article/details/gtxinmabkv.html

PHP:  if (empty($x)) {}
来源：http://dali.yanxiufei.cn/Article/details/gtzsttxwfi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhixingplan.top/Article/details/gtatxdxnxh.html

TS:   if (x == null) {}
来源：http://dali.havefunace.top/Article/details/gtoiopglhe.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtjsiwsweb.html

Go:   if x == nil {}
来源：http://dali.birdmap.top/Article/details/gtncpftmyu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.guowangkeji.top/Article/details/gtgzvcpdmp.html

C#:   if (x is null) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtctijhjop.html

[P07] 防抖与节流
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhcxgdwy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cucudq.cn/Article/details/gtgnfsltek.html

PHP:  // 手写时间戳比较
来源：http://dali.jlsjyb.cn/Article/details/gteczjyxhw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gtfjjgaxbk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gtnducxmay.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuanzx.com/Article/details/gtaufqpydy.html


<!-- 参考信息 -->