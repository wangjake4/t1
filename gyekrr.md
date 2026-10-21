代发 wailian999

JS:   process.argv.slice(2)
来源：http://dali.guowangkeji.top/Article/details/gtqzilfhqb.html

TS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtsjddamul.html

Java: args 数组（main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gtomrsrdlk.html

Go:   os.Args[1:]
来源：http://dali.haohaochexian.top/Article/details/gtzmxnmjgi.html

Ruby: ARGV
来源：http://dali.cqqwz.cn/Article/details/gtokjmrsxx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gtalouxcwl.html

[M02] 读取环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipxpqatg.html

Py:   os.environ.get("HOME")
来源：http://dali.sweek.top/Article/details/gtctbyebfc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gtfmxhryvo.html

JS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gtdvvagtep.html

TS:   process.env.HOME
来源：http://dali.redwolf501.top/Article/details/gtcjefusam.html

Java: System.getenv("HOME")
来源：http://dali.yueranfly.top/Article/details/gtxvqqmjwy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnqzz.top/Article/details/gtycizmkaz.html

Ruby: ENV["HOME"]
来源：http://dali.quarkkingdee.top/Article/details/gtwybsokmp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtbnnnzzmh.html

[M03] 执行外部命令
来源：http://dali.yangfankeji.com/Article/details/gtprahaipg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtshofosxg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmfbslzo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gtrxnbavqf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.c1oappe.top/Article/details/gtpzedjmxt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.316326.xyz/Article/details/gtgzuvxxiy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.smart0.xyz/Article/details/gtqjwluvyt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guowangkeji.top/Article/details/gtumpsocxo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jlsjyb.cn/Article/details/gtnlrnqhtc.html

[M04] 获取当前工作目录
来源：http://dali.yj20258.top/Article/details/gtltsuyges.html

Py:   os.getcwd()
来源：http://dali.hywenlv.cn/Article/details/gtcpgfpvpi.html

PHP:  getcwd();
来源：http://dali.sweek.top/Article/details/gtzlxmtyan.html

JS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gteayhjvzg.html

TS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gtuukhsoxz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jyoumei.cn/Article/details/gttkccyzhl.html

Go:   os.Getwd()
来源：http://dali.guannengcc.top/Article/details/gtoadyrygb.html

Ruby: Dir.pwd
来源：http://dali.cucudq.cn/Article/details/gtlongognj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.bjfxy.top/Article/details/gtqbuwurhn.html

[M05] 设置退出码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebqzqayy.html

Py:   sys.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gthlfnyljy.html

PHP:  exit(1);
来源：http://dali.gotoacloud.top/Article/details/gtaqrexqkc.html

JS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlzsuawq.html

TS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtnkdotogh.html

Java: System.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtycoxygba.html

Go:   os.Exit(1)
来源：http://dali.wangdashe.top/Article/details/gthfaslszp.html

Ruby: exit 1
来源：http://dali.cheryme.top/Article/details/gtxbpzkoan.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gzhubu.top/Article/details/gtdbzfbdri.html

[M06] 向标准错误输出
来源：http://dali.daxiang520.top/Article/details/gtxrnmrpux.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuanzhike.top/Article/details/gtcvjtgmvg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pycfn.com/Article/details/gtmqzdlnrd.html

JS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gtxmzmfirt.html

TS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gtierpfkuj.html

Java: System.err.println("err")
来源：http://dali.chenlongwang.top/Article/details/gtoncklsrv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.bjfxy.top/Article/details/gtopwfdqfa.html

Ruby: warn "err"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoeaistat.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tianlin.xyz/Article/details/gtgrmryraz.html

[M07] 判断是否为主入口
来源：http://dali.hnqzz.top/Article/details/gtxkhxchkx.html

Py:   if __name__ == "__main__":
来源：http://dali.haohaochexian.top/Article/details/gtdaziysok.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yangfankeji.com/Article/details/gtmtvbclsi.html

JS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gtngosawpq.html

TS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gtdgygvaif.html

Java: public static void main(String[] args)
来源：http://dali.tian-w.cn/Article/details/gtyjtlnpev.html

Go:   func main()
来源：http://dali.hywenlv.cn/Article/details/gtlhtxfaku.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shangyingyoupin.top/Article/details/gtkzhcklqi.html

C#:   static void Main(string[] args)
来源：http://dali.snrcjt.cn/Article/details/gtfpqafymn.html

[M08] 获取系统与运行时信息
来源：http://dali.jyoumei.cn/Article/details/gtppwbakqg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgfzy.top/Article/details/gtmisfkpvr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cqqwz.cn/Article/details/gtdzpahofa.html

JS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gtucranxxa.html

TS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gtjjiqbmom.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.quarkkingdee.top/Article/details/gtnuhlfrtq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhoulong.xyz/Article/details/gtvatvlsiq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangdashe.top/Article/details/gtvvqutbza.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ehwqpu.com/Article/details/gtrvlbvsqb.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtipzizjrj.html

N. 数据结构与算法
来源：http://dali.jiagoushi.top/Article/details/gtgsipcfpp.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtnhrzfmif.html

[N01] 二分查找（有序数组）
来源：http://dali.ehwqpu.com/Article/details/gtovjpivrb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtbfrrqfpe.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gtmkevhufo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gttlkudfmr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtcsqkegaz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtoqudxzeu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gttgohcrzu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cashguo.top/Article/details/gtrtrnosuo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gttbxdzcqy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuetiantiany.cn/Article/details/gtpmhyfpbe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtgpizvcxm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.svipenyu.cn/Article/details/gtastnpfep.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gtytwimjbc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gtkzbzlyrx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pycfn.com/Article/details/gtthsnmzak.html

Go:   slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gtwwblorqr.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gtqifqpolr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jyoumei.cn/Article/details/gtqedfeqeb.html

[N03] 快速排序（分治示例）
来源：http://dali.shzxlz.cn/Article/details/gtvrtshegx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.snrcjt.cn/Article/details/gtcztqfozy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fzhhl.top/Article/details/gtqwbnvkgv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gtgjawikgw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxinkj.top/Article/details/gtwqtrpjrn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aizwys.cn/Article/details/gtuzbpswur.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nanxinkj.top/Article/details/gtjojucaur.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hongshengwenyu.top/Article/details/gtivrjrwmm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhengqikj.top/Article/details/gtyaduamoc.html

[N04] 斐波那契数列
来源：http://dali.yanxiufei.cn/Article/details/gtamqfjemo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gtiwdizhak.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gtbzbaduog.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslyznhvp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtkaznhgbk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gttrembfgt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuanzhike.top/Article/details/gtdcekhzky.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sufxvd.cn/Article/details/gtuwicacfj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gttpasqupd.html

[N05] 最大公约数
来源：http://dali.zhengqikj.top/Article/details/gtdehrmsxn.html

Py:   math.gcd(a, b)
来源：http://dali.guowangkeji.top/Article/details/gtwlbsjhni.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuanzhike.top/Article/details/gtitlpusyj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gtwefkplqx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gtgxvsmsdm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gogol.net.cn/Article/details/gtwdmyvqxs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.mhx1999.top/Article/details/gttfryzrkr.html

Ruby: a.gcd(b)
来源：http://dali.yanxiufei.cn/Article/details/gtmapxrjzl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.wangdashe.top/Article/details/gtsqzfxacq.html

[N06] 判断回文字符串
来源：http://dali.jqgufenzy.top/Article/details/gtpjukphat.html

Py:   s == s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gtvyhqxkxf.html

PHP:  $s === strrev($s);
来源：http://dali.316326.xyz/Article/details/gthwexuijx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtuklqcaox.html

TS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtgksnwysg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangshuangyany.cn/Article/details/gtfeqdtiul.html

Go:   // 双指针从两端比较
来源：http://dali.sweek.top/Article/details/gtojhtltuf.html

Ruby: s == s.reverse
来源：http://dali.zdqjudy.top/Article/details/gtrsybqmil.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gtoqbvgohg.html

[N07] 两数之和（返回下标）
来源：http://dali.yuxming.cn/Article/details/gtnmakpecn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cqqwz.cn/Article/details/gtlvrxzgbo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ivvv.top/Article/details/gtgvdazpzs.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.meibo888.top/Article/details/gtinbgtsxy.html

TS:   // 手写 Map<string, number>
来源：http://dali.shangyingyoupin.top/Article/details/gtoxgemzwr.html

Java: // 手写 HashMap
来源：http://dali.hysaishi.cn/Article/details/gtxlijflho.html

Go:   // 手写 map[int]int
来源：http://dali.smart0.xyz/Article/details/gtoruemxvz.html

Ruby: // 手写 Hash
来源：http://dali.jiagoushi.top/Article/details/gttdzkcrjz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ivvv.top/Article/details/gtnizgasiq.html

[N08] 生成全排列
来源：http://dali.snrcjt.cn/Article/details/gtyoejifym.html

Py:   itertools.permutations(arr)
来源：http://dali.xuanzx.com/Article/details/gtbusswzsb.html

PHP:  // 手写递归交换
来源：http://dali.jqgufenzy.top/Article/details/gtmedswrvg.html

JS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtlekceprp.html

TS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtidnjqqrk.html

Java: // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtdrsczllz.html

Go:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtmzhbauly.html

Ruby: arr.permutation.to_a
来源：http://dali.iojbl.cn/Article/details/gtbczfukin.html

C#:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuivdenyl.html

[N09] 栈与队列
来源：http://dali.xinyue.icu/Article/details/gtctkqpjlg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shzxlz.cn/Article/details/gtjfbunavz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj202588.top/Article/details/gtviijhdme.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gtgqawfrfz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangshuangyany.cn/Article/details/gtrfrpqsjh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cashguo.top/Article/details/gtjloznczs.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pycfn.com/Article/details/gtgknsoexz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtcriyqzyz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.quarkkingdee.top/Article/details/gtdbuqpqpi.html

[N10] 链表节点定义
来源：http://dali.jqgfzy.top/Article/details/gtozcjvilh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj202588.top/Article/details/gtnrfiiiso.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.snrcjt.cn/Article/details/gtfvgxhoat.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.andypj.xyz/Article/details/gtswxhkohp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ivvv.top/Article/details/gtjlvxpwoa.html

Java: class Node { int v; Node next; }
来源：http://dali.fengsongda.top/Article/details/gtwaceeyep.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sxryk.cn/Article/details/gtzoetnvdc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuxming.cn/Article/details/gtkwffidtk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.iojbl.cn/Article/details/gtoibjzsjk.html

[N11] 二叉树中序遍历
来源：http://dali.yvedp.cn/Article/details/gtqrvsaxfi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yangfankeji.com/Article/details/gttvnfvwdg.html

PHP:  // 手写递归函数
来源：http://dali.zhengqikj.top/Article/details/gtnrhhzhme.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gtihadepfv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yvedp.cn/Article/details/gtopgmragi.html

Java: // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtjvpmezac.html

Go:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gtemdtuymo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zycfv.cn/Article/details/gtxcobivhc.html

C#:   // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzocqlblf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnxiangtu.top/Article/details/gtnuxsnotb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.iojbl.cn/Article/details/gtjizesqtw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.birdmap.top/Article/details/gtenlxdylv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gtazwqenqw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gtcfithwmh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gtdlolvvsq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yangfankeji.com/Article/details/gtdswhymhw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydlrbvml.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gtfvclsfbz.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtdwpagibb.html

O. 并发与异步
来源：http://dali.dianchejie.cn/Article/details/gttqpmzicq.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtveittilb.html

[O01] 启动一个线程
来源：http://dali.nwbrower.top/Article/details/gtrjzyfgrv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.snrcjt.cn/Article/details/gtgvlzpswn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.wangdashe.top/Article/details/gtigkwecie.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.fzhhl.top/Article/details/gtsysrpbbt.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gtzfzymyef.html

Java: new Thread(() -> f()).start()
来源：http://dali.birdmap.top/Article/details/gtfocqmwtf.html

Go:   go f()
来源：http://dali.meibo888.top/Article/details/gtemhhizpv.html

Ruby: Thread.new { f }
来源：http://dali.hongshengwenyu.top/Article/details/gtglgovjkd.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigufen.top/Article/details/gterklddfx.html

[O02] 使用线程池
来源：http://dali.kuanghao11.cn/Article/details/gtkikmqfgd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yonumen.top/Article/details/gtsqpfuihy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgfzy.top/Article/details/gtujisbcri.html

JS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gtqbzjfdqy.html

TS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gttoossadp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aibaodan.cn/Article/details/gtuwwziqjq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yangfankeji.com/Article/details/gtlhzjrnjk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cqqwz.cn/Article/details/gtbtaccivd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hysaishi.cn/Article/details/gtbuylbxlm.html

[O03] 加锁保护共享数据
来源：http://dali.quarkkingdee.top/Article/details/gtrxzsxegn.html

Py:   with lock: shared += 1
来源：http://dali.xziqi.cn/Article/details/gtewshxawe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yonumen.top/Article/details/gtxurtweud.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xinyue.icu/Article/details/gtqnidkvwp.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprirmgqd.html

Java: synchronized (this) { shared++; }
来源：http://dali.fzhhl.top/Article/details/gtqtytfgue.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cqqwz.cn/Article/details/gtyfbjdbwg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangdashe.top/Article/details/gtubqqvaff.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtecblwrzf.html

[O04] 定义异步函数并等待
来源：http://dali.yongpay.top/Article/details/gtfukwudva.html

Py:   async def f():⏎    await g()
来源：http://dali.yvedp.cn/Article/details/gtnntclkti.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nwbrower.top/Article/details/gtrzljhrzx.html

JS:   async function f() { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gtjdovjirh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gtpfjfscne.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.316326.xyz/Article/details/gtoyntishc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.wangdashe.top/Article/details/gtjuaesgrt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ivvv.top/Article/details/gtguwmsxvn.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258888.top/Article/details/gtekxvliyc.html

[O05] 并发执行并等待全部完成
来源：http://dali.gaohongyu789.top/Article/details/gtnahcwyma.html

Py:   asyncio.gather(*tasks)
来源：http://dali.redwolf501.top/Article/details/gtlulxhmum.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhengqikj.top/Article/details/gtpxogxpsm.html

JS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gtlpddvhgo.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gtvgdykgwg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.dashuyun.cn/Article/details/gtvfrfeyyc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yvedp.cn/Article/details/gtepupmuwl.html

Ruby: threads.map(&:join)
来源：http://dali.hfpthk.cn/Article/details/gtdgvadgqh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuanzx.com/Article/details/gtpvkologw.html

[O06] 使用进程池
来源：http://dali.dianchejie.cn/Article/details/gtjfiphahz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hfpthk.cn/Article/details/gtkxjnwftx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenjidiqi.icu/Article/details/gttjqzugaq.html

JS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gtnihpvswo.html

TS:   // child_process / cluster 模块
来源：http://dali.zhoulong.xyz/Article/details/gtyyujybpz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.havefunace.top/Article/details/gtpkkarsvn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.birdmap.top/Article/details/gtzgruxgqz.html

Ruby: // fork 块
来源：http://dali.zdqjudy.top/Article/details/gtxgxenetg.html

C#:   Parallel.For
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdymqpet.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gteospugmj.html

P. 常用工具函数
来源：http://dali.hnxiangtu.top/Article/details/gtqaavgizo.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtdruipyfx.html

[P01] 生成 UUID
来源：http://dali.zdqjudy.top/Article/details/gtqmkvhkdt.html

Py:   str(uuid.uuid4())
来源：http://dali.guannengcc.top/Article/details/gtwsqhzvyy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xylfe.cn/Article/details/gtwfldjlkz.html

JS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gtslkbldfz.html

TS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrolllct.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwisjenwq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hfpthk.cn/Article/details/gtefbcnftt.html

Ruby: SecureRandom.uuid
来源：http://dali.havefunace.top/Article/details/gtkjoknehw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sysykeji.top/Article/details/gtqapyldjs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.0kj1m.cn/Article/details/gtlppeauxs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigfzy.top/Article/details/gtadoxznwo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ydzc1.top/Article/details/gtvsbaukhl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sxryk.cn/Article/details/gtqylilegl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tanke756.top/Article/details/gtpghnqqer.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yangfankeji.com/Article/details/gtejdqmral.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gaohongyu789.top/Article/details/gtwhbziepc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqbvfgdw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenlongwang.top/Article/details/gtrrmyxsxs.html

[P03] 生成短随机字符串
来源：http://dali.cheryme.top/Article/details/gtobggkrsk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinghuilouyu.cn/Article/details/gtoohcqjzn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhengqikj.top/Article/details/gthfzivvwy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jiagoushi.top/Article/details/gtckwmuzau.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ppjwa.cn/Article/details/gtqqqmsbto.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shzxlz.cn/Article/details/gtmcpbzpyc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zdqjudy.top/Article/details/gtcmltrfub.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenzaomai.com/Article/details/gtnffojbsm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jlsjyb.cn/Article/details/gtdgbjcgxy.html

[P04] 求长度
来源：http://dali.c1oappe.top/Article/details/gtnuwawits.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cqqwz.cn/Article/details/gtdpmyjcdw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gttfkyrvab.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gtwpkiwvyn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cheryme.top/Article/details/gttknpxzva.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gogol.net.cn/Article/details/gtujvytlrh.html

Go:   len(arr);  len(m)
来源：http://dali.sweek.top/Article/details/gtraypoest.html

Ruby: x.length;  x.size
来源：http://dali.0kj1m.cn/Article/details/gtzebjkkaj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.dashuyun.cn/Article/details/gtseanmizu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yueranfly.top/Article/details/gtcnqyczlt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.wangshuangyany.cn/Article/details/gtornzevan.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zdqjudy.top/Article/details/gtxebrlcsp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.birdmap.top/Article/details/gtqvincsnu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gtlqgviwdi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.birdmap.top/Article/details/gtwdlvdazf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gtfmkrxahb.html

Ruby: a == b
来源：http://dali.hnxiangtu.top/Article/details/gtmihvzlzq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cucudq.cn/Article/details/gtddmxhhcl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfhbdclw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.vqdsnc.cn/Article/details/gtnsqpskex.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gthzynkwdf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tanke756.top/Article/details/gtvpzndjra.html

TS:   if (x == null) {}
来源：http://dali.snrcjt.cn/Article/details/gtvixgjeqz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtrobxtzya.html

Go:   if x == nil {}
来源：http://dali.yongpay.top/Article/details/gttiekafra.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxinkj.top/Article/details/gtbjfiakiz.html

C#:   if (x is null) {}
来源：http://dali.nanxuanxn.top/Article/details/gtawyapaci.html

[P07] 防抖与节流
来源：http://dali.jinghuilouyu.cn/Article/details/gtydrpnmrz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.quarkkingdee.top/Article/details/gtrskamjaj.html

PHP:  // 手写时间戳比较
来源：http://dali.gzhubu.top/Article/details/gtvsdfehfk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gtyipcnirg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gteagfaffw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.havefunace.top/Article/details/gtilkrzuwh.html


<!-- 参考信息 -->