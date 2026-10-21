代发 wailian999

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.havefunace.top/Article/details/gtkrsaqkqx.html

JS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gtvwlcnipp.html

TS:   process.env.HOME
来源：http://dali.dashuyun.cn/Article/details/gtckqfftxs.html

Java: System.getenv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtxqkgmadj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuanzx.com/Article/details/gtjiiitwbz.html

Ruby: ENV["HOME"]
来源：http://dali.hywenlv.cn/Article/details/gtgqjrvdsh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtypkyvtrb.html

[M03] 执行外部命令
来源：http://dali.shuidangran.top/Article/details/gtfrzsoudb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ydzc1.top/Article/details/gtckkvaafz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhongyouzk.top/Article/details/gtnaggolok.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gtaezmwjzw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gttnxcxejx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shuidangran.top/Article/details/gtxhrwfkrn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuetiantiany.cn/Article/details/gtqzrgexpj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hammf.cn/Article/details/gtebqvevsp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gaohongyu789.top/Article/details/gtbvlbvwdg.html

[M04] 获取当前工作目录
来源：http://dali.iojbl.cn/Article/details/gtvfwnjptr.html

Py:   os.getcwd()
来源：http://dali.cheryme.top/Article/details/gtklxorcsn.html

PHP:  getcwd();
来源：http://dali.haohaochexian.top/Article/details/gtxzidohia.html

JS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtkfvmcopu.html

TS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtgetwohec.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ivvv.top/Article/details/gtbsjnsrgm.html

Go:   os.Getwd()
来源：http://dali.shzxlz.cn/Article/details/gtdgtxqhwk.html

Ruby: Dir.pwd
来源：http://dali.aibaodan.cn/Article/details/gtzipoxoer.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gaohongyu789.top/Article/details/gtdcmhfima.html

[M05] 设置退出码
来源：http://dali.yj20258.top/Article/details/gtqwnulgaw.html

Py:   sys.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtgbuprzqa.html

PHP:  exit(1);
来源：http://dali.hnxiangtu.top/Article/details/gtaofznuin.html

JS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtsojwvfsi.html

TS:   process.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtcjitzbsk.html

Java: System.exit(1)
来源：http://dali.xziqi.cn/Article/details/gttzysofaf.html

Go:   os.Exit(1)
来源：http://dali.pycfn.com/Article/details/gtaqmqwzxl.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gtxaoogpxa.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.iojbl.cn/Article/details/gtmkcvkrlm.html

[M06] 向标准错误输出
来源：http://dali.9152youxi.cn/Article/details/gtnxgpanzc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnxiangtu.top/Article/details/gtivtrdxku.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shangyingyoupin.top/Article/details/gthblfpric.html

JS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gtdkumblyv.html

TS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gtuejhxkje.html

Java: System.err.println("err")
来源：http://dali.fzhhl.top/Article/details/gtokimemhz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkwawkvx.html

Ruby: warn "err"
来源：http://dali.hfpthk.cn/Article/details/gtfapyumlo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtrvlhbrxv.html

[M07] 判断是否为主入口
来源：http://dali.yuanzhike.top/Article/details/gtepgowcbq.html

Py:   if __name__ == "__main__":
来源：http://dali.ivvv.top/Article/details/gthskmdoju.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fengsongda.top/Article/details/gtxdgrltcq.html

JS:   require.main === module
来源：http://dali.xuanzx.com/Article/details/gtalcetssr.html

TS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gtfjcwdsie.html

Java: public static void main(String[] args)
来源：http://dali.sysykeji.top/Article/details/gtwmofshbt.html

Go:   func main()
来源：http://dali.xylfe.cn/Article/details/gtmemctbva.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tian-w.cn/Article/details/gtxagjaedn.html

C#:   static void Main(string[] args)
来源：http://dali.svipenyu.cn/Article/details/gtohbleeqs.html

[M08] 获取系统与运行时信息
来源：http://dali.cheryme.top/Article/details/gtczmvduec.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnqzz.top/Article/details/gtsccqpngm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guannengcc.top/Article/details/gtojgrjofp.html

JS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gteovhoufg.html

TS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvkqyjwf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guannengcc.top/Article/details/gtevxbdlep.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.wangshuangyany.cn/Article/details/gtrkgztbhw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hongshengwenyu.top/Article/details/gthezfijhi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhoulong.xyz/Article/details/gtdidotrhl.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtqzfmqoil.html

N. 数据结构与算法
来源：http://dali.gotoacloud.top/Article/details/gtlnzklpul.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtlpgawnfe.html

[N01] 二分查找（有序数组）
来源：http://dali.hongshengwenyu.top/Article/details/gtlfgaudzz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ivvv.top/Article/details/gtealfomoq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gtrwkvuird.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jiagoushi.top/Article/details/gtfccqaqct.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwuyjlky.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtsbwtcgmd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.316326.xyz/Article/details/gtajpuxicu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.quarkkingdee.top/Article/details/gtccrnxpsj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtibsyigcy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cdnleiting.top/Article/details/gtwzsjkoxw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jlsjyb.cn/Article/details/gtwklutygw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yonumen.top/Article/details/gtkdphhtgd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gtpfrxlznv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gtcafkjcut.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuanzx.com/Article/details/gtbixedvzb.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gtkwgdlilh.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gtpfozzekq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinqigfzy.top/Article/details/gtakqzgiiw.html

[N03] 快速排序（分治示例）
来源：http://dali.quarkkingdee.top/Article/details/gtneczilwf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tanke756.top/Article/details/gtwupbsthk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.redwolf501.top/Article/details/gtytvtzmnw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jianghu66.top/Article/details/gtznsouhui.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ehwqpu.com/Article/details/gtebvloahm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxuanxn.top/Article/details/gtjgstbhnx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xylfe.cn/Article/details/gtcilmitfh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.bjfxy.top/Article/details/gtbejcwcyt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigfzy.top/Article/details/gtmnkfgibb.html

[N04] 斐波那契数列
来源：http://dali.zhoulong.xyz/Article/details/gteudcyuvf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gtpnqrybii.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gtaiaatokc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtuddrbeeh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gtyocuwxnq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gtgkcnberu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqknnoxv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gtkfwrpbnm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtbfcmncti.html

[N05] 最大公约数
来源：http://dali.xuanzx.com/Article/details/gtlzjtagfh.html

Py:   math.gcd(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gtranfstbh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtxmuckkff.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gtinabxhmy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gtaftzkzrt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenjidiqi.icu/Article/details/gthbsczegn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guowangkeji.top/Article/details/gtaltrzamv.html

Ruby: a.gcd(b)
来源：http://dali.hfpthk.cn/Article/details/gtsjwommcw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xziqi.cn/Article/details/gtelvujlfx.html

[N06] 判断回文字符串
来源：http://dali.ydzc1.top/Article/details/gtamaargst.html

Py:   s == s[::-1]
来源：http://dali.jyoumei.cn/Article/details/gtivaiplwh.html

PHP:  $s === strrev($s);
来源：http://dali.sxryk.cn/Article/details/gtcsvneopg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtvsmbeorg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtbwlihits.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnxiangtu.top/Article/details/gtxvacoasj.html

Go:   // 双指针从两端比较
来源：http://dali.jianghu66.top/Article/details/gtqfvmgxpm.html

Ruby: s == s.reverse
来源：http://dali.mhx1999.top/Article/details/gtrcwtnxjy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gtlzlpfhew.html

[N07] 两数之和（返回下标）
来源：http://dali.hfpthk.cn/Article/details/gtingbcxzo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yvedp.cn/Article/details/gtprsxfnhl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ybcxt.top/Article/details/gtdekzifri.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.0kj1m.cn/Article/details/gtsxjrvwau.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenlongwang.top/Article/details/gtzcocxxzg.html

Java: // 手写 HashMap
来源：http://dali.hammf.cn/Article/details/gtkppnyqwg.html

Go:   // 手写 map[int]int
来源：http://dali.ehwqpu.com/Article/details/gtolfbehfa.html

Ruby: // 手写 Hash
来源：http://dali.sxryk.cn/Article/details/gtgrmzcgrq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgciuxwp.html

[N08] 生成全排列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupfcheyx.html

Py:   itertools.permutations(arr)
来源：http://dali.zdqjudy.top/Article/details/gtnbshtpmy.html

PHP:  // 手写递归交换
来源：http://dali.zycfv.cn/Article/details/gtuxtylomy.html

JS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtlfxzrctm.html

TS:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtxmhlvuwn.html

Java: // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtnscbkgys.html

Go:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtdktuiksv.html

Ruby: arr.permutation.to_a
来源：http://dali.hongshengwenyu.top/Article/details/gteixbqmmn.html

C#:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtbwurmrho.html

[N09] 栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gtumlwuhzn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xylfe.cn/Article/details/gtuquyovrq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtvhlcjhbk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtbwibueyd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuanzx.com/Article/details/gtqmeoulgt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dashuyun.cn/Article/details/gtvbyyhyrt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenzaomai.com/Article/details/gtbdgzslko.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtolgjpxch.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.316326.xyz/Article/details/gtpuncskmv.html

[N10] 链表节点定义
来源：http://dali.yuxming.cn/Article/details/gtxuofptrk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yvedp.cn/Article/details/gttxjigsgn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.daxiang520.top/Article/details/gtgwztscdm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jyoumei.cn/Article/details/gttqqyxuad.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shangyingyoupin.top/Article/details/gtoyaifdei.html

Java: class Node { int v; Node next; }
来源：http://dali.ydzc1.top/Article/details/gtxouptdlh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jlsjyb.cn/Article/details/gtfzauptsx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuxming.cn/Article/details/gtxvcxrrea.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daria6918.cn/Article/details/gtitidhuqj.html

[N11] 二叉树中序遍历
来源：http://dali.guowangkeji.top/Article/details/gtagpuppqy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gtmifwrfzs.html

PHP:  // 手写递归函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtulrvgjfs.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yueranfly.top/Article/details/gtjvydmvov.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.havefunace.top/Article/details/gtgnannyck.html

Java: // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gtpwmeoiez.html

Go:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtuodkrmni.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenzaomai.com/Article/details/gtbwvnizuv.html

C#:   // 手写递归
来源：http://dali.yongpay.top/Article/details/gtzieigxlq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jiagoushi.top/Article/details/gtbmwregmj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hammf.cn/Article/details/gtmieuppoa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.dianchejie.cn/Article/details/gtldfyqrce.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangshuangyany.cn/Article/details/gtyletdvvp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hammf.cn/Article/details/gtqlypvxxs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hfpthk.cn/Article/details/gtnhbqppvy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenjidiqi.icu/Article/details/gtoyzmszab.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nwbrower.top/Article/details/gtorcqvitv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gtbxretybv.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtvnowqdap.html

O. 并发与异步
来源：http://dali.quarkkingdee.top/Article/details/gtolrkybns.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtlshsldrs.html

[O01] 启动一个线程
来源：http://dali.yj202588.top/Article/details/gtzkzdaluo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gteyttdmkr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jlsjyb.cn/Article/details/gtkcgadwtk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.pycfn.com/Article/details/gtjucvlsnz.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gtdevlrcxg.html

Java: new Thread(() -> f()).start()
来源：http://dali.hammf.cn/Article/details/gtyizsxlnv.html

Go:   go f()
来源：http://dali.nanxinkj.top/Article/details/gtaqfuypqb.html

Ruby: Thread.new { f }
来源：http://dali.hnxiangtu.top/Article/details/gttuswxkhp.html

C#:   Task.Run(() => F());
来源：http://dali.gotoacloud.top/Article/details/gtowvqvmyq.html

[O02] 使用线程池
来源：http://dali.gotoacloud.top/Article/details/gtmcomdjqb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.dianchejie.cn/Article/details/gtkrtikzxz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cashguo.top/Article/details/gtoqrimwaw.html

JS:   // worker_threads 线程池
来源：http://dali.snrcjt.cn/Article/details/gtvmqxikwv.html

TS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gtrjevpawh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.316326.xyz/Article/details/gtlyfkxipw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gaohongyu789.top/Article/details/gtmfsaglru.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.bjfxy.top/Article/details/gtqletcplr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbnsvofr.html

[O03] 加锁保护共享数据
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgfhvhmvu.html

Py:   with lock: shared += 1
来源：http://dali.havefunace.top/Article/details/gtlgldbkgv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinqigufen.top/Article/details/gtnvxforso.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.smart0.xyz/Article/details/gtxhdgciew.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gtmxlsapds.html

Java: synchronized (this) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gtagbxykxs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsucyikiz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.aizwys.cn/Article/details/gtsvjohgwl.html

C#:   lock (gate) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gtwfyunquh.html

[O04] 定义异步函数并等待
来源：http://dali.zycfv.cn/Article/details/gtilxhchdr.html

Py:   async def f():⏎    await g()
来源：http://dali.jqgfzy.top/Article/details/gtfruodzka.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhoulong.xyz/Article/details/gtxlrkvqvl.html

JS:   async function f() { await g(); }
来源：http://dali.meibo888.top/Article/details/gtalktyojn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xylfe.cn/Article/details/gteemicrnh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbmdxbcs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yanxiufei.cn/Article/details/gteexmgufi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cheryme.top/Article/details/gtgbdohtjp.html

C#:   async Task F() { await G(); }
来源：http://dali.tianlin.xyz/Article/details/gtzhomsogu.html

[O05] 并发执行并等待全部完成
来源：http://dali.zdqjudy.top/Article/details/gtwhchcmim.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenzaomai.com/Article/details/gtfjgatzfd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jianghu66.top/Article/details/gtkmrnwffl.html

JS:   await Promise.all(tasks)
来源：http://dali.zhixingplan.top/Article/details/gtvkmtmlup.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtvqyoxobg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.birdmap.top/Article/details/gtpnrzlxmr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ivvv.top/Article/details/gtfggnvune.html

Ruby: threads.map(&:join)
来源：http://dali.birdmap.top/Article/details/gtznuhlrjf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zycfv.cn/Article/details/gtfxfxrjnt.html

[O06] 使用进程池
来源：http://dali.dianchejie.cn/Article/details/gtngyosnet.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nanxinkj.top/Article/details/gtaofgwqou.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shuidangran.top/Article/details/gtplrhtlih.html

JS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gtpemqxglv.html

TS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gtivfdrvkx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258888.top/Article/details/gtdfhkhhhr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.pengpengdd.cyou/Article/details/gtgzjouhwp.html

Ruby: // fork 块
来源：http://dali.guannengcc.top/Article/details/gtdkjfroil.html

C#:   Parallel.For
来源：http://dali.yongpay.top/Article/details/gtebfocnye.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtxyrbxveu.html

P. 常用工具函数
来源：http://dali.gzhubu.top/Article/details/gttgyykdeu.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtrsosyevb.html

[P01] 生成 UUID
来源：http://dali.pengpengdd.cyou/Article/details/gtzphxrixr.html

Py:   str(uuid.uuid4())
来源：http://dali.gotoacloud.top/Article/details/gtbmznoqyj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yangfankeji.com/Article/details/gtsetriujl.html

JS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtfhdsbasr.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gtdwlivyiz.html

Java: UUID.randomUUID().toString()
来源：http://dali.birdmap.top/Article/details/gtzajsknta.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tanke756.top/Article/details/gtchvqkkoz.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gtoxazmjrg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.bjfxy.top/Article/details/gtvfwsyvrk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jlsjyb.cn/Article/details/gtjegjeezz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yangfankeji.com/Article/details/gtolwjhdzq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtsfpyqsoa.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.svipenyu.cn/Article/details/gtggavnbqp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guowangkeji.top/Article/details/gtvschwdwu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.smart0.xyz/Article/details/gtrqzbubez.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cqqwz.cn/Article/details/gtcfnspvcb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gaohongyu789.top/Article/details/gtxzfxqrgg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuanzhike.top/Article/details/gtcqqrasnx.html

[P03] 生成短随机字符串
来源：http://dali.chenzaomai.com/Article/details/gtojcdqvot.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pengpengdd.cyou/Article/details/gtnbftcmue.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.fengsongda.top/Article/details/gtscazaivt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgfzy.top/Article/details/gtiffwvjxf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gteebxazug.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xinyue.icu/Article/details/gtgelestac.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.c1oappe.top/Article/details/gtqnvclmzg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hywenlv.cn/Article/details/gtlmqbtnvl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.havefunace.top/Article/details/gtcxwaggko.html

[P04] 求长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvmzdscy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zycfv.cn/Article/details/gtsmzchjfm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtiiegndfn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gtwfkqyvnp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gtddfbsdue.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenlongwang.top/Article/details/gtjvbdeuud.html

Go:   len(arr);  len(m)
来源：http://dali.guannengcc.top/Article/details/gtqscezlrm.html

Ruby: x.length;  x.size
来源：http://dali.tian-w.cn/Article/details/gtptngnngx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tianlin.xyz/Article/details/gtfidujoqa.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shuidangran.top/Article/details/gtrcadqsbi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigufen.top/Article/details/gtjsyphyns.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aizwys.cn/Article/details/gtstmgkkdp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xuanzx.com/Article/details/gtxwlcpnec.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gtvcfolhrv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.0kj1m.cn/Article/details/gthjtvrcuz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtuuubofqs.html

Ruby: a == b
来源：http://dali.yj20258888.top/Article/details/gtuhsvvjzi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhengqikj.top/Article/details/gtkxacfbse.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinghuilouyu.cn/Article/details/gthhssfyhv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenlongwang.top/Article/details/gtemmgltyu.html

PHP:  if (empty($x)) {}
来源：http://dali.tian-w.cn/Article/details/gtezvwjwhz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuanzx.com/Article/details/gtlwpspebv.html

TS:   if (x == null) {}
来源：http://dali.zdqjudy.top/Article/details/gtbwzltckm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jyoumei.cn/Article/details/gtxcdlioii.html

Go:   if x == nil {}
来源：http://dali.xinyue.icu/Article/details/gtujztwosy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yanxiufei.cn/Article/details/gtcxkajhpi.html

C#:   if (x is null) {}
来源：http://dali.andypj.xyz/Article/details/gtgqgjjgmd.html

[P07] 防抖与节流
来源：http://dali.hywenlv.cn/Article/details/gtrpxsqugn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hywenlv.cn/Article/details/gtmngwcxcx.html

PHP:  // 手写时间戳比较
来源：http://dali.aibaodan.cn/Article/details/gtvfoqibjz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gtambrlvam.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtttqbrdyd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258888.top/Article/details/gtcvozlqmp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.kuanghao11.cn/Article/details/gtocluwwro.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fzhhl.top/Article/details/gtpabzidmj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jlsjyb.cn/Article/details/gtchmpocci.html

[P08] 处理浮点精度问题
来源：http://dali.gzhubu.top/Article/details/gtykcnnuye.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomnkjdqw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhoulong.xyz/Article/details/gtwcsphicy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhongyouzk.top/Article/details/gtleesuudp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tanke756.top/Article/details/gttuxhvrrc.html


<!-- 参考信息 -->