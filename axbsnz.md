代发 wailian999

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtyqrgxpqr.html

[M01] 读取命令行参数
来源：http://dali.guannengcc.top/Article/details/gtakagqpdw.html

Py:   sys.argv[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtgqufpyom.html

PHP:  $argv;  $argc;
来源：http://dali.316326.xyz/Article/details/gtnmxdmsht.html

JS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gtnkcvctjh.html

TS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gtitspfvoo.html

Java: args 数组（main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gtxzlpcdpr.html

Go:   os.Args[1:]
来源：http://dali.jqgfzy.top/Article/details/gtctjouwsx.html

Ruby: ARGV
来源：http://dali.iojbl.cn/Article/details/gtrofspcyi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwbnvpuh.html

[M02] 读取环境变量
来源：http://dali.gotoacloud.top/Article/details/gtmojzdswi.html

Py:   os.environ.get("HOME")
来源：http://dali.zycfv.cn/Article/details/gtkjeymcsx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yuxming.cn/Article/details/gtkidkajwu.html

JS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gtfnmzanyo.html

TS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gtkquumjyo.html

Java: System.getenv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtdyzrtszm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fengsongda.top/Article/details/gtbchljwmg.html

Ruby: ENV["HOME"]
来源：http://dali.zhongyouzk.top/Article/details/gtpdkwjyca.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtpoktohwm.html

[M03] 执行外部命令
来源：http://dali.jyoumei.cn/Article/details/gtlxezgdvw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.meibo888.top/Article/details/gtgcmiyzdn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pengpengdd.cyou/Article/details/gtjumnpfrl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gtvotmjaww.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gtgnuautcw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.bjfxy.top/Article/details/gtcsvbvbmh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.feifeiyinyue.top/Article/details/gtovulwllg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinghuilouyu.cn/Article/details/gtndihnpjx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhixingplan.top/Article/details/gtlbjrlzsb.html

[M04] 获取当前工作目录
来源：http://dali.aibaodan.cn/Article/details/gtemnlqedp.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gtjxiynypc.html

PHP:  getcwd();
来源：http://dali.zhengqikj.top/Article/details/gtnnpvwzuy.html

JS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gttxtwwmkm.html

TS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gtmjyjpfnn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.fengsongda.top/Article/details/gtdhswsjek.html

Go:   os.Getwd()
来源：http://dali.dashuyun.cn/Article/details/gtgogwzmay.html

Ruby: Dir.pwd
来源：http://dali.tianlin.xyz/Article/details/gtynjczonu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.guowangkeji.top/Article/details/gtayanvcdy.html

[M05] 设置退出码
来源：http://dali.daxiang520.top/Article/details/gthcqsosnl.html

Py:   sys.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtwhtrlsbc.html

PHP:  exit(1);
来源：http://dali.ybcxt.top/Article/details/gtvvbhsgqh.html

JS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtwtrngrah.html

TS:   process.exit(1)
来源：http://dali.ivvv.top/Article/details/gtxcmhjanv.html

Java: System.exit(1)
来源：http://dali.tian-w.cn/Article/details/gthixhonxp.html

Go:   os.Exit(1)
来源：http://dali.shuidangran.top/Article/details/gtzccmzaoy.html

Ruby: exit 1
来源：http://dali.jqgfzy.top/Article/details/gtrrpowfxr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yangfankeji.com/Article/details/gtgyluysrl.html

[M06] 向标准错误输出
来源：http://dali.zhiwuduotai.top/Article/details/gtzvbybahu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihncykmn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.quarkkingdee.top/Article/details/gthabdhnyz.html

JS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gthekdkgif.html

TS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gttrrpbwan.html

Java: System.err.println("err")
来源：http://dali.sysykeji.top/Article/details/gtxkfkdkba.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhoulong.xyz/Article/details/gtsfvbtcri.html

Ruby: warn "err"
来源：http://dali.yongpay.top/Article/details/gtncadgbnt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zdqjudy.top/Article/details/gtioyjtfba.html

[M07] 判断是否为主入口
来源：http://dali.quarkkingdee.top/Article/details/gtyzmhnhgn.html

Py:   if __name__ == "__main__":
来源：http://dali.chenjidiqi.icu/Article/details/gtyvcgbccf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pycfn.com/Article/details/gteqwjtivr.html

JS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtljpzrpdf.html

TS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gtecjqssvq.html

Java: public static void main(String[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gthpjsvedz.html

Go:   func main()
来源：http://dali.ehwqpu.com/Article/details/gtkmuoblst.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sysykeji.top/Article/details/gtiddpxlvp.html

C#:   static void Main(string[] args)
来源：http://dali.gaohongyu789.top/Article/details/gtoqaeglvh.html

[M08] 获取系统与运行时信息
来源：http://dali.fengsongda.top/Article/details/gtknguxylq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yanxiufei.cn/Article/details/gtwdqghtoh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygxqtwjv.html

JS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gthassmxws.html

TS:   process.platform;  process.version
来源：http://dali.yj202588.top/Article/details/gtltlyvzus.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ydzc1.top/Article/details/gtgdinpdta.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenzaomai.com/Article/details/gtdabunoln.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.dianchejie.cn/Article/details/gtbovkqkin.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ybcxt.top/Article/details/gttboftfdy.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtnuaisstu.html

N. 数据结构与算法
来源：http://dali.xinyue.icu/Article/details/gtakhevvly.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtbzaauvlt.html

[N01] 二分查找（有序数组）
来源：http://dali.daxiang520.top/Article/details/gtqjuyuixz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfalensjj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sxryk.cn/Article/details/gtriilxwsz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gtkpozuuov.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gtglfurlfh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gtdiispupp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sweek.top/Article/details/gtnddcyooe.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.haohaochexian.top/Article/details/gtfipguudj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtfeohqler.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tianlin.xyz/Article/details/gtbavzeibg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gtzbbkeooc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cdnleiting.top/Article/details/gttkpkcixq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtstgnnpel.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gtmtrxlqaj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daria6918.cn/Article/details/gtuusfyset.html

Go:   slices.Sort(arr)
来源：http://dali.iojbl.cn/Article/details/gtsfjwxhzt.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gtdnokjyxd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.bjfxy.top/Article/details/gtawdtjwxi.html

[N03] 快速排序（分治示例）
来源：http://dali.jqgfzy.top/Article/details/gtbzyfximz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cucudq.cn/Article/details/gtbxzljlre.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aibaodan.cn/Article/details/gtouqqenyf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gthsdtqprx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ehwqpu.com/Article/details/gtrntqptex.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclxkkyco.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.pycfn.com/Article/details/gtpyqdxmeq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zycfv.cn/Article/details/gtonfsdrok.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.mhx1999.top/Article/details/gthevvakpv.html

[N04] 斐波那契数列
来源：http://dali.snrcjt.cn/Article/details/gtosbtirsq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gttmlrdnak.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gtbwfglzie.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtozjrcbql.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtromufvul.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gtzdzmbwvl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nwbrower.top/Article/details/gtahyuvfcq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gthxlncurp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gteftaqyan.html

[N05] 最大公约数
来源：http://dali.quarkkingdee.top/Article/details/gtwhfvxhvx.html

Py:   math.gcd(a, b)
来源：http://dali.pycfn.com/Article/details/gtcmaacdbu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhongyouzk.top/Article/details/gtzccmhfqv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gtnavtfiec.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jlsjyb.cn/Article/details/gtprycpojc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jqgufenzy.top/Article/details/gtihkzwcbs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cdnleiting.top/Article/details/gtzqovraww.html

Ruby: a.gcd(b)
来源：http://dali.vqdsnc.cn/Article/details/gtibrzwwky.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hysaishi.cn/Article/details/gtbxvuhmuq.html

[N06] 判断回文字符串
来源：http://dali.c1oappe.top/Article/details/gtxexhobqr.html

Py:   s == s[::-1]
来源：http://dali.iojbl.cn/Article/details/gtpefhuxyq.html

PHP:  $s === strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gtfnanzmds.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtolbxxxgt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwhwaujc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.0kj1m.cn/Article/details/gtatxflose.html

Go:   // 双指针从两端比较
来源：http://dali.andypj.xyz/Article/details/gtpwdrszdi.html

Ruby: s == s.reverse
来源：http://dali.ivvv.top/Article/details/gtmnklzouq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gaohongyu789.top/Article/details/gtiydrgzfs.html

[N07] 两数之和（返回下标）
来源：http://dali.zhengqikj.top/Article/details/gtnlbsxnfk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxinkj.top/Article/details/gtrmgwstgj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuanzx.com/Article/details/gtsqkpnkkc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpgisekf.html

TS:   // 手写 Map<string, number>
来源：http://dali.cashguo.top/Article/details/gtpxxpqrhw.html

Java: // 手写 HashMap
来源：http://dali.sxryk.cn/Article/details/gtgxiorgvr.html

Go:   // 手写 map[int]int
来源：http://dali.gotoacloud.top/Article/details/gtipwicdrj.html

Ruby: // 手写 Hash
来源：http://dali.redwolf501.top/Article/details/gtueqbljyt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daria6918.cn/Article/details/gtuklpiuti.html

[N08] 生成全排列
来源：http://dali.jyoumei.cn/Article/details/gtekdoxiuf.html

Py:   itertools.permutations(arr)
来源：http://dali.316326.xyz/Article/details/gtyvgkeigx.html

PHP:  // 手写递归交换
来源：http://dali.shzxlz.cn/Article/details/gtfrggiirz.html

JS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtrvutzsoe.html

TS:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gteyuznekn.html

Java: // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gthkzkujgk.html

Go:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtynpfumvu.html

Ruby: arr.permutation.to_a
来源：http://dali.0kj1m.cn/Article/details/gtkcznohrv.html

C#:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtvkwvyncp.html

[N09] 栈与队列
来源：http://dali.hammf.cn/Article/details/gtotnfvnrt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.birdmap.top/Article/details/gtoigmctlg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gtrajjzjgb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtakyqmoeh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nwbrower.top/Article/details/gtjrxcpvnc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sufxvd.cn/Article/details/gtwzabgirg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shangyingyoupin.top/Article/details/gteegjvcxa.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gtdkjtfjpz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gtkbzzbnmj.html

[N10] 链表节点定义
来源：http://dali.sweek.top/Article/details/gtiiomhnfv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gzhubu.top/Article/details/gtryusfwea.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxgpcejll.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.iojbl.cn/Article/details/gtwoyjpthw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.kuanghao11.cn/Article/details/gtpnbvappo.html

Java: class Node { int v; Node next; }
来源：http://dali.sufxvd.cn/Article/details/gtjlcbxvbq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nwbrower.top/Article/details/gtzpqctpme.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj202588.top/Article/details/gtlrshfucf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.quarkkingdee.top/Article/details/gtfehzvfow.html

[N11] 二叉树中序遍历
来源：http://dali.yuxming.cn/Article/details/gtcucrhyjr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cheryme.top/Article/details/gtlcxzwttn.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gtrgzlkxxh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sysykeji.top/Article/details/gtcersxnyt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtqedkpsqn.html

Java: // 手写递归
来源：http://dali.hammf.cn/Article/details/gthfojlicz.html

Go:   // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gtvyncydnp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shuidangran.top/Article/details/gtoenoripx.html

C#:   // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gtxrainasz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.dashuyun.cn/Article/details/gtnjtauwmd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hysaishi.cn/Article/details/gtvzsbsrwc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhongyouzk.top/Article/details/gtiaczflka.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gtodznzxsv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gtpdxqgble.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hfpthk.cn/Article/details/gtgoidcbxl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.iojbl.cn/Article/details/gtbpxhnwld.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gtdckrkblj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gtwhoybcol.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtipxugrck.html

O. 并发与异步
来源：http://dali.pycfn.com/Article/details/gtqrjabqos.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtjxhecsgs.html

[O01] 启动一个线程
来源：http://dali.c1oappe.top/Article/details/gtygmqhbdh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.iojbl.cn/Article/details/gtfrzwyyvu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jiagoushi.top/Article/details/gtznxwpodq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigfzy.top/Article/details/gtmabgkgew.html

TS:   // 同 JS
来源：http://dali.yonumen.top/Article/details/gtbfgjtxrk.html

Java: new Thread(() -> f()).start()
来源：http://dali.daxiang520.top/Article/details/gtsohflbhs.html

Go:   go f()
来源：http://dali.bjfxy.top/Article/details/gtpbkvqjyn.html

Ruby: Thread.new { f }
来源：http://dali.yj20258888.top/Article/details/gtvnqnescq.html

C#:   Task.Run(() => F());
来源：http://dali.snrcjt.cn/Article/details/gtdzwmnegv.html

[O02] 使用线程池
来源：http://dali.hnqzz.top/Article/details/gtuoybqinx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fzhhl.top/Article/details/gtpdhxtorb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yonumen.top/Article/details/gtgcambtzy.html

JS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gtpgxvvdgm.html

TS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gtehlijppy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hammf.cn/Article/details/gtfxcmdfqj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ehwqpu.com/Article/details/gtgoxjnucz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cdnleiting.top/Article/details/gtegwakuxo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tanke756.top/Article/details/gtenptcrbh.html

[O03] 加锁保护共享数据
来源：http://dali.vqdsnc.cn/Article/details/gtkobhrjqn.html

Py:   with lock: shared += 1
来源：http://dali.chenzaomai.com/Article/details/gtbrankzlx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hongshengwenyu.top/Article/details/gtskceoskh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.aizwys.cn/Article/details/gtvjvhlkeq.html

TS:   // 同 JS
来源：http://dali.gzhubu.top/Article/details/gtocxhxkfr.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctcvkgqf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhixingplan.top/Article/details/gtecstpkeb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhoulong.xyz/Article/details/gthschngah.html

C#:   lock (gate) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gtpxdrdukx.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigfzy.top/Article/details/gtfjkugjna.html

Py:   async def f():⏎    await g()
来源：http://dali.cqqwz.cn/Article/details/gtwrrdstss.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.316326.xyz/Article/details/gtpfoxeygc.html

JS:   async function f() { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gtzfxeaylm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtimdncild.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.snrcjt.cn/Article/details/gtxcrxxfbi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.snrcjt.cn/Article/details/gtxtdyxkjs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cdnleiting.top/Article/details/gtibmxprgv.html

C#:   async Task F() { await G(); }
来源：http://dali.aibaodan.cn/Article/details/gtuxwachbc.html

[O05] 并发执行并等待全部完成
来源：http://dali.ehwqpu.com/Article/details/gtjmqbdskf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumqkzhcb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jlsjyb.cn/Article/details/gtlihdoelj.html

JS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gtxdvjxnts.html

TS:   await Promise.all(tasks)
来源：http://dali.cdnleiting.top/Article/details/gtwznxtpjq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yongpay.top/Article/details/gtupaiuawz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcsjoorp.html

Ruby: threads.map(&:join)
来源：http://dali.guannengcc.top/Article/details/gtndutxrwd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgfzy.top/Article/details/gtveqrbltt.html

[O06] 使用进程池
来源：http://dali.svipenyu.cn/Article/details/gtlyjziyhk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj202588.top/Article/details/gtormcgxej.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.wangshuangyany.cn/Article/details/gtpihwunms.html

JS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqhglilg.html

TS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gtlmvdhexi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258.top/Article/details/gtyrulyyrq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jlsjyb.cn/Article/details/gtlsdxsffs.html

Ruby: // fork 块
来源：http://dali.jiagoushi.top/Article/details/gtobqrlwgs.html

C#:   Parallel.For
来源：http://dali.snrcjt.cn/Article/details/gtilyvbhpr.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtwspzattj.html

P. 常用工具函数
来源：http://dali.birdmap.top/Article/details/gtzptkazvo.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtjjdhazff.html

[P01] 生成 UUID
来源：http://dali.xziqi.cn/Article/details/gtkfxqagzr.html

Py:   str(uuid.uuid4())
来源：http://dali.gogol.net.cn/Article/details/gtdsdwrdlu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj20258.top/Article/details/gtpyjnsugy.html

JS:   crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gtepzzdwct.html

TS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gtbnfsuziu.html

Java: UUID.randomUUID().toString()
来源：http://dali.yongpay.top/Article/details/gtzulkybyg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fengsongda.top/Article/details/gtzuwgbdiw.html

Ruby: SecureRandom.uuid
来源：http://dali.feifeiyinyue.top/Article/details/gtstjkiscv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yonumen.top/Article/details/gtiolfpthj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hammf.cn/Article/details/gtpayqhbtl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zdqjudy.top/Article/details/gtnhrflbnz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtoslydodk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jiagoushi.top/Article/details/gtroykxkaz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigfzy.top/Article/details/gtkdwpjkfr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gtnzbszfzg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tianlin.xyz/Article/details/gtzvkkgebx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuxming.cn/Article/details/gtdpnyhrmm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tian-w.cn/Article/details/gtfljxpvyw.html

[P03] 生成短随机字符串
来源：http://dali.zhiwuduotai.top/Article/details/gthiaohrot.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuetiantiany.cn/Article/details/gtsgscgdhe.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnqzz.top/Article/details/gtysxmhsij.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.svipenyu.cn/Article/details/gtcihrqlvf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gzhubu.top/Article/details/gtgtxbpqgf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dianchejie.cn/Article/details/gtvhbewixh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.haohaochexian.top/Article/details/gtvrvsuqur.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zdqjudy.top/Article/details/gttymcfmkr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhiwuduotai.top/Article/details/gtkdoyhmhc.html

[P04] 求长度
来源：http://dali.cashguo.top/Article/details/gtpxbizqqg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ydzc1.top/Article/details/gtkohvvkii.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtcgvtlirz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pycfn.com/Article/details/gtunprpxyf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aizwys.cn/Article/details/gtlrqdhzkc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shzxlz.cn/Article/details/gtplnqznrg.html

Go:   len(arr);  len(m)
来源：http://dali.jiagoushi.top/Article/details/gtigjqwfto.html

Ruby: x.length;  x.size
来源：http://dali.aizwys.cn/Article/details/gtfeeypvru.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.smart0.xyz/Article/details/gtfxiztdcz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.meibo888.top/Article/details/gtxtcivivv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjkiglyde.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jianghu66.top/Article/details/gtqctxmsvm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.meibo888.top/Article/details/gtvisicrmy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yangfankeji.com/Article/details/gtszyjviay.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gzhubu.top/Article/details/gthatbhpta.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sweek.top/Article/details/gtgymnluoh.html

Ruby: a == b
来源：http://dali.zhoulong.xyz/Article/details/gtpzanpcvk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.316326.xyz/Article/details/gtfdqgmesj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.dashuyun.cn/Article/details/gtxbejseiv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenjidiqi.icu/Article/details/gtjpfpumis.html

PHP:  if (empty($x)) {}
来源：http://dali.pycfn.com/Article/details/gtbylmdnhv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gogol.net.cn/Article/details/gtvsilugwd.html

TS:   if (x == null) {}
来源：http://dali.yanxiufei.cn/Article/details/gtjkywhtxc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gtviorhnwg.html

Go:   if x == nil {}
来源：http://dali.yongpay.top/Article/details/gtubiqhikf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangshuangyany.cn/Article/details/gtxcospxbq.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gtojpntweb.html

[P07] 防抖与节流
来源：http://dali.guowangkeji.top/Article/details/gtswoqvrqb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yvedp.cn/Article/details/gtpjamjiil.html


<!-- 参考信息 -->