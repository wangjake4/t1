代发 wailian999

Ruby: ARGV
来源：http://dali.yonumen.top/Article/details/gtkgrxinza.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gtkgyratpm.html

[M02] 读取环境变量
来源：http://dali.tanke756.top/Article/details/gtgscbtbwt.html

Py:   os.environ.get("HOME")
来源：http://dali.yongpay.top/Article/details/gtxztvmlto.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gtpykkpflu.html

JS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtmvatywol.html

TS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gtvwkpxafp.html

Java: System.getenv("HOME")
来源：http://dali.xziqi.cn/Article/details/gtlkjfhfup.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtcqcvofmb.html

Ruby: ENV["HOME"]
来源：http://dali.hammf.cn/Article/details/gtxeazaomk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pycfn.com/Article/details/gtyjxqrqsa.html

[M03] 执行外部命令
来源：http://dali.zhixingplan.top/Article/details/gtjoaljlzv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sxryk.cn/Article/details/gtoisithru.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnqzz.top/Article/details/gtmjqtcifh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gtoqakltvj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtywumkgcr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gogol.net.cn/Article/details/gtzvkceaao.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.andypj.xyz/Article/details/gtvcmlaqdl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangdashe.top/Article/details/gtuijjhtqr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhixingplan.top/Article/details/gtcggxjglc.html

[M04] 获取当前工作目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizckfjir.html

Py:   os.getcwd()
来源：http://dali.nwbrower.top/Article/details/gttjrifzft.html

PHP:  getcwd();
来源：http://dali.sxryk.cn/Article/details/gtgkqhgvgk.html

JS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gtzomcoosh.html

TS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gtwhpznoxg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuanzx.com/Article/details/gtrkeutfsz.html

Go:   os.Getwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtqihrxmmi.html

Ruby: Dir.pwd
来源：http://dali.yongpay.top/Article/details/gtypwotiop.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.havefunace.top/Article/details/gtjuzgidvc.html

[M05] 设置退出码
来源：http://dali.dashuyun.cn/Article/details/gtizdyrofl.html

Py:   sys.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtvunbbxdj.html

PHP:  exit(1);
来源：http://dali.tanke756.top/Article/details/gtafaxgtea.html

JS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtirmgcdys.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzaomnnh.html

Java: System.exit(1)
来源：http://dali.cashguo.top/Article/details/gtiawytszz.html

Go:   os.Exit(1)
来源：http://dali.meibo888.top/Article/details/gthhkrpbur.html

Ruby: exit 1
来源：http://dali.daxiang520.top/Article/details/gtqvpgkdha.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hysaishi.cn/Article/details/gtyecxzsqe.html

[M06] 向标准错误输出
来源：http://dali.tanke756.top/Article/details/gtxiuigaqa.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gttyzspdkx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guowangkeji.top/Article/details/gtyvvxpcnu.html

JS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gtwvgxulwk.html

TS:   console.error("err")
来源：http://dali.sxryk.cn/Article/details/gtecjapofx.html

Java: System.err.println("err")
来源：http://dali.hfpthk.cn/Article/details/gteqmstver.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlctvodum.html

Ruby: warn "err"
来源：http://dali.zhengqikj.top/Article/details/gtcpsrdsht.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaydzsxpq.html

[M07] 判断是否为主入口
来源：http://dali.hywenlv.cn/Article/details/gttgrtoewg.html

Py:   if __name__ == "__main__":
来源：http://dali.quarkkingdee.top/Article/details/gtosybunpo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjfrlnku.html

JS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gtgywjcwcg.html

TS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gtlkoysovq.html

Java: public static void main(String[] args)
来源：http://dali.yuanzhike.top/Article/details/gtyvwkwhif.html

Go:   func main()
来源：http://dali.zhoulong.xyz/Article/details/gtlplkojny.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cqqwz.cn/Article/details/gtfzudipzf.html

C#:   static void Main(string[] args)
来源：http://dali.vqdsnc.cn/Article/details/gtvxhgixnq.html

[M08] 获取系统与运行时信息
来源：http://dali.hfpthk.cn/Article/details/gtakosajyx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xziqi.cn/Article/details/gtgrtvnsux.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gaohongyu789.top/Article/details/gtpgolnybx.html

JS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gttjchwkcc.html

TS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtvquzmh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aibaodan.cn/Article/details/gtubiufafb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxinkj.top/Article/details/gtcrnxbsew.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gzhubu.top/Article/details/gtslqcrary.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nwbrower.top/Article/details/gtzqxsbaco.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gthfeayevs.html

N. 数据结构与算法
来源：http://dali.aizwys.cn/Article/details/gtbwqanmoj.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtxhskfbui.html

[N01] 二分查找（有序数组）
来源：http://dali.gotoacloud.top/Article/details/gtccldgtwz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtutpqqalf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daria6918.cn/Article/details/gtxpdoamjm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtujuumcas.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.bjfxy.top/Article/details/gtghdpaoqh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtazgbcunq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtcmvyxfct.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shangyingyoupin.top/Article/details/gtwgotxtoq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gtnabraznp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yvedp.cn/Article/details/gtjlurhtrj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gtictqxzzf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.birdmap.top/Article/details/gtxffhjokz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gtveuhvjyq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gtsnmpfpuz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.316326.xyz/Article/details/gtnwzgeipx.html

Go:   slices.Sort(arr)
来源：http://dali.cashguo.top/Article/details/gttdeecstp.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gtnfyoznaw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxuanxn.top/Article/details/gthmmtrhnt.html

[N03] 快速排序（分治示例）
来源：http://dali.vqdsnc.cn/Article/details/gtzjnqquxh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgfzy.top/Article/details/gtengjvfae.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gzhubu.top/Article/details/gtruyvieij.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gtsgatavpq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gtnpbmotgs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fzhhl.top/Article/details/gtpxtjjdxq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sysykeji.top/Article/details/gtzrlyrndb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jianghu66.top/Article/details/gtzmfkfztc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hongshengwenyu.top/Article/details/gttwwexayq.html

[N04] 斐波那契数列
来源：http://dali.jyoumei.cn/Article/details/gtecgmyryw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtplbdppya.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gtfefghbud.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtesvynvtt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtmmemgaiz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gtuowpvsxz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yonumen.top/Article/details/gtqjeriejd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.vqdsnc.cn/Article/details/gtbbncrrit.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtpcprcnxf.html

[N05] 最大公约数
来源：http://dali.hongshengwenyu.top/Article/details/gtybteyhzi.html

Py:   math.gcd(a, b)
来源：http://dali.redwolf501.top/Article/details/gtpzpxryzh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.andypj.xyz/Article/details/gtkykohrrw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shuidangran.top/Article/details/gtzovltqiy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gtpghqlbrp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangdashe.top/Article/details/gtyuqcflhk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cdnleiting.top/Article/details/gtvnxboozb.html

Ruby: a.gcd(b)
来源：http://dali.jyoumei.cn/Article/details/gtzvjinsrv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sufxvd.cn/Article/details/gtpfmodfaq.html

[N06] 判断回文字符串
来源：http://dali.ppjwa.cn/Article/details/gtdevuebqu.html

Py:   s == s[::-1]
来源：http://dali.yanxiufei.cn/Article/details/gtbzreygmq.html

PHP:  $s === strrev($s);
来源：http://dali.ehwqpu.com/Article/details/gtblvvnvxj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtqyoaimyk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtulvlqznl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zycfv.cn/Article/details/gtoyrwdpsi.html

Go:   // 双指针从两端比较
来源：http://dali.cucudq.cn/Article/details/gtvpfhkpab.html

Ruby: s == s.reverse
来源：http://dali.chenzaomai.com/Article/details/gtqtxpltza.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gtvvmeleuz.html

[N07] 两数之和（返回下标）
来源：http://dali.hnqzz.top/Article/details/gtillzgpcw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.havefunace.top/Article/details/gttjqqiqih.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pycfn.com/Article/details/gtqtwzrakr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhixingplan.top/Article/details/gtzecnwdim.html

TS:   // 手写 Map<string, number>
来源：http://dali.svipenyu.cn/Article/details/gtqshrvpre.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrwjnqml.html

Go:   // 手写 map[int]int
来源：http://dali.guannengcc.top/Article/details/gtcuuzlorp.html

Ruby: // 手写 Hash
来源：http://dali.xinyue.icu/Article/details/gtixujkzsu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hammf.cn/Article/details/gtrnbzchka.html

[N08] 生成全排列
来源：http://dali.fzhhl.top/Article/details/gtfjilglwm.html

Py:   itertools.permutations(arr)
来源：http://dali.hfpthk.cn/Article/details/gttinxxdzu.html

PHP:  // 手写递归交换
来源：http://dali.tanke756.top/Article/details/gtxaoexjcb.html

JS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtujgbjsnw.html

TS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtubjyalot.html

Java: // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtcbvdxidq.html

Go:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gteptbbklt.html

Ruby: arr.permutation.to_a
来源：http://dali.cashguo.top/Article/details/gtcbghcvpn.html

C#:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtsyutglfm.html

[N09] 栈与队列
来源：http://dali.hfpthk.cn/Article/details/gtainzrsrf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yangfankeji.com/Article/details/gtyvngtzwr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gthrfofedy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtucwxkrpy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.andypj.xyz/Article/details/gtmmsyeklx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgfzy.top/Article/details/gtfrfiqgrx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shzxlz.cn/Article/details/gtkzktupsk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtplwvwlcz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrcrptju.html

[N10] 链表节点定义
来源：http://dali.yangfankeji.com/Article/details/gtqfgmyhjx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhoulong.xyz/Article/details/gtrmsphbut.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.kuanghao11.cn/Article/details/gtiawizjvp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cqqwz.cn/Article/details/gtvzmvmizm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cdnleiting.top/Article/details/gteonqctrq.html

Java: class Node { int v; Node next; }
来源：http://dali.tanke756.top/Article/details/gtzcwplwxd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtolzdixud.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.9152youxi.cn/Article/details/gtwgarvgyv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sufxvd.cn/Article/details/gtvrixircv.html

[N11] 二叉树中序遍历
来源：http://dali.xziqi.cn/Article/details/gtuzomunib.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhoulong.xyz/Article/details/gtzshwvfna.html

PHP:  // 手写递归函数
来源：http://dali.shzxlz.cn/Article/details/gtugrxtwdb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gtdrnozrmo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gtlmdzhupg.html

Java: // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtcacbllyd.html

Go:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtmhwbdhmb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ydzc1.top/Article/details/gteqtnpulx.html

C#:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gtsuhfkwji.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.iojbl.cn/Article/details/gtbgcznrhg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xylfe.cn/Article/details/gtclwhntcc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cucudq.cn/Article/details/gtadqyiwpj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gtcvmfurco.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gtehsoezxn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yueranfly.top/Article/details/gthjfcwcar.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.snrcjt.cn/Article/details/gthvbgkily.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxinkj.top/Article/details/gtsotupyzc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gtkblohaqf.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gteiynxmjn.html

O. 并发与异步
来源：http://dali.gaohongyu789.top/Article/details/gttyioepbt.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtyhmabrtw.html

[O01] 启动一个线程
来源：http://dali.hnqzz.top/Article/details/gtjsavdwrm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.guannengcc.top/Article/details/gtputfyvku.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jyoumei.cn/Article/details/gtotmqctpz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxinkj.top/Article/details/gtmahftsoy.html

TS:   // 同 JS
来源：http://dali.xinyue.icu/Article/details/gtxdzuopvp.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhixingplan.top/Article/details/gtjmdakzoo.html

Go:   go f()
来源：http://dali.daria6918.cn/Article/details/gtqedghexf.html

Ruby: Thread.new { f }
来源：http://dali.yuanzhike.top/Article/details/gtytwunhhl.html

C#:   Task.Run(() => F());
来源：http://dali.chenlongwang.top/Article/details/gtifreejgp.html

[O02] 使用线程池
来源：http://dali.jqgufenzy.top/Article/details/gtbwhxizco.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sxryk.cn/Article/details/gtflqzzqwd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yanxiufei.cn/Article/details/gtfkpihxvf.html

JS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gtxxwqpscc.html

TS:   // worker_threads 线程池
来源：http://dali.yuxming.cn/Article/details/gtkzfxgxau.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cdnleiting.top/Article/details/gtabpenipq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.fzhhl.top/Article/details/gthlqyvfql.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yuxming.cn/Article/details/gtmqnbpszd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.daria6918.cn/Article/details/gtbvbdyodr.html

[O03] 加锁保护共享数据
来源：http://dali.chenzaomai.com/Article/details/gtphpvuyum.html

Py:   with lock: shared += 1
来源：http://dali.jqgfzy.top/Article/details/gtjvzclyvz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gaohongyu789.top/Article/details/gtzcljctyf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zycfv.cn/Article/details/gtpkqjclld.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtouxcczey.html

Java: synchronized (this) { shared++; }
来源：http://dali.316326.xyz/Article/details/gtlfmwhoaf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.snrcjt.cn/Article/details/gtvxpljvqh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cheryme.top/Article/details/gtohttuwdg.html

C#:   lock (gate) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gtdgyhyapd.html

[O04] 定义异步函数并等待
来源：http://dali.chenlongwang.top/Article/details/gtbwoipjfv.html

Py:   async def f():⏎    await g()
来源：http://dali.yuxming.cn/Article/details/gthndibthf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shuidangran.top/Article/details/gtvaoayjto.html

JS:   async function f() { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gtgnxftyom.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gtffrttygs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sweek.top/Article/details/gtprjmuwia.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jiagoushi.top/Article/details/gtppkgcxte.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yonumen.top/Article/details/gtjfdpzqiu.html

C#:   async Task F() { await G(); }
来源：http://dali.gotoacloud.top/Article/details/gtgmdcipbu.html

[O05] 并发执行并等待全部完成
来源：http://dali.9152youxi.cn/Article/details/gtobvkckdh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtigunsjkk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhiwuduotai.top/Article/details/gtlhimjtps.html

JS:   await Promise.all(tasks)
来源：http://dali.svipenyu.cn/Article/details/gtbrbawovs.html

TS:   await Promise.all(tasks)
来源：http://dali.yj202588.top/Article/details/gtzxkdnprm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tanke756.top/Article/details/gthqmmryqm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shzxlz.cn/Article/details/gticlaylei.html

Ruby: threads.map(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gtsqnoamzt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tanke756.top/Article/details/gtypnoqcmc.html

[O06] 使用进程池
来源：http://dali.tianlin.xyz/Article/details/gtqensacrv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cqqwz.cn/Article/details/gtvjlpwkmy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.svipenyu.cn/Article/details/gtxjhpzowm.html

JS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gtcegwdusm.html

TS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gtammgsrxr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphretnhz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258888.top/Article/details/gtsjwhnquu.html

Ruby: // fork 块
来源：http://dali.guannengcc.top/Article/details/gteeabfgjl.html

C#:   Parallel.For
来源：http://dali.gzhubu.top/Article/details/gtwodjicit.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gthphmkmmy.html

P. 常用工具函数
来源：http://dali.zycfv.cn/Article/details/gtnpsaydxo.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtnnhysoef.html

[P01] 生成 UUID
来源：http://dali.zhengqikj.top/Article/details/gtjoqpeaqo.html

Py:   str(uuid.uuid4())
来源：http://dali.tianlin.xyz/Article/details/gtrxpbnuvx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cdnleiting.top/Article/details/gtwxpqprjl.html

JS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtsebdzlan.html

TS:   crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gtkosgodre.html

Java: UUID.randomUUID().toString()
来源：http://dali.sweek.top/Article/details/gtvoyxsszy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tian-w.cn/Article/details/gtcckqafie.html

Ruby: SecureRandom.uuid
来源：http://dali.hywenlv.cn/Article/details/gttegkadir.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuanzx.com/Article/details/gtifcsasya.html

[P02] MD5 / SHA256 摘要
来源：http://dali.kuanghao11.cn/Article/details/gtvbmudrfb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigufen.top/Article/details/gthqawuuae.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqrwjpyf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xinyue.icu/Article/details/gtflcdkvvt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.haohaochexian.top/Article/details/gtmtwxowzl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yuanzhike.top/Article/details/gtgmfldzci.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yueranfly.top/Article/details/gtgszkwujd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.smart0.xyz/Article/details/gtwtfkaapq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pycfn.com/Article/details/gtjipekmba.html

[P03] 生成短随机字符串
来源：http://dali.cashguo.top/Article/details/gtyxkwovdw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jqgfzy.top/Article/details/gtjfmtlbmr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ppjwa.cn/Article/details/gtztarzfip.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhftezyl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenzaomai.com/Article/details/gtwbdkheto.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nwbrower.top/Article/details/gtdmvhhdcy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dashuyun.cn/Article/details/gtmqcpdzhj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yanxiufei.cn/Article/details/gtaknmksln.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnxiangtu.top/Article/details/gtsckgolwo.html

[P04] 求长度
来源：http://dali.yvedp.cn/Article/details/gtpcnjgkth.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrpkrzap.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtdjixvcmj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gtfzhceosy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gtsfiswjqo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.svipenyu.cn/Article/details/gtiyhxjumx.html

Go:   len(arr);  len(m)
来源：http://dali.zhoulong.xyz/Article/details/gthlwlojoy.html

Ruby: x.length;  x.size
来源：http://dali.jyoumei.cn/Article/details/gthkjgosyc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sufxvd.cn/Article/details/gtjkterexr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj202588.top/Article/details/gtdbcyoehj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenlongwang.top/Article/details/gtqutpmwlj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yangfankeji.com/Article/details/gtjyypqfpm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gotoacloud.top/Article/details/gttovpmotn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gzhubu.top/Article/details/gtvfntigaj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinqigufen.top/Article/details/gttiyevcgo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gtzjjlelqe.html

Ruby: a == b
来源：http://dali.xylfe.cn/Article/details/gtfbtzahhv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.andypj.xyz/Article/details/gtyuaoxems.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.pycfn.com/Article/details/gtpdzrqkzu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.svipenyu.cn/Article/details/gtvzaeqfhl.html

PHP:  if (empty($x)) {}
来源：http://dali.shuidangran.top/Article/details/gtyoqikzmn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yueranfly.top/Article/details/gtfnlpddeo.html

TS:   if (x == null) {}
来源：http://dali.cucudq.cn/Article/details/gttvlazswt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.dianchejie.cn/Article/details/gtodygvuzi.html

Go:   if x == nil {}
来源：http://dali.xinyue.icu/Article/details/gtacslatzm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsjplbfc.html

C#:   if (x is null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelvqdszc.html

[P07] 防抖与节流
来源：http://dali.tian-w.cn/Article/details/gtyuftwgwe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gogol.net.cn/Article/details/gtxskcbyag.html

PHP:  // 手写时间戳比较
来源：http://dali.sweek.top/Article/details/gtusnoxfiy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gtbomsnvkh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gtvlthznkp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigfzy.top/Article/details/gtjimiakrw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sweek.top/Article/details/gtcjtadjye.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.mhx1999.top/Article/details/gtdzoqepic.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cucudq.cn/Article/details/gtygwodnvw.html

[P08] 处理浮点精度问题
来源：http://dali.cqqwz.cn/Article/details/gtjfvuupjh.html


<!-- 参考信息 -->