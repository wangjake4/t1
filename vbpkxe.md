代发 wailian999

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guannengcc.top/Article/details/gtkilrggzu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tanke756.top/Article/details/gtyuzuedzw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gtevdhyvri.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gtaevswdbn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gtpmikqrdv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cdnleiting.top/Article/details/gtuvjvywuj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.smart0.xyz/Article/details/gtsvpkjgbk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shuidangran.top/Article/details/gtbsmrubcc.html

[M04] 获取当前工作目录
来源：http://dali.shangyingyoupin.top/Article/details/gtrkvcxcuv.html

Py:   os.getcwd()
来源：http://dali.chenzaomai.com/Article/details/gtyrlwrpjb.html

PHP:  getcwd();
来源：http://dali.aizwys.cn/Article/details/gtvzkwmoqs.html

JS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gtcotsxnjz.html

TS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gtrttgykod.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hywenlv.cn/Article/details/gtaiamnxvb.html

Go:   os.Getwd()
来源：http://dali.kuanghao11.cn/Article/details/gtnjosexsa.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gtqpoanovi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhreoqmr.html

[M05] 设置退出码
来源：http://dali.jinqigufen.top/Article/details/gtwijnaebf.html

Py:   sys.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtcfdqqfwj.html

PHP:  exit(1);
来源：http://dali.zhoulong.xyz/Article/details/gtrwzqfuqi.html

JS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtaoddfubn.html

TS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtgcnaabxf.html

Java: System.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtayjsbpqm.html

Go:   os.Exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtdehrcglq.html

Ruby: exit 1
来源：http://dali.svipenyu.cn/Article/details/gtfmnttbzy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gtnvadvizi.html

[M06] 向标准错误输出
来源：http://dali.sxryk.cn/Article/details/gtcgdharrx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhoulong.xyz/Article/details/gtlribmtyd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jyoumei.cn/Article/details/gtvlhfaosw.html

JS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gtkqnjscbs.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtgukhqmti.html

Java: System.err.println("err")
来源：http://dali.haohaochexian.top/Article/details/gtbgyjqard.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.havefunace.top/Article/details/gtpfdijbiz.html

Ruby: warn "err"
来源：http://dali.yueranfly.top/Article/details/gtfioljbyh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtympkfgaf.html

[M07] 判断是否为主入口
来源：http://dali.yj20258888.top/Article/details/gtwdvjswkk.html

Py:   if __name__ == "__main__":
来源：http://dali.svipenyu.cn/Article/details/gtixcyjwjb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvtocdzz.html

JS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gtofnaeflf.html

TS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gtybldthmd.html

Java: public static void main(String[] args)
来源：http://dali.gogol.net.cn/Article/details/gtwebdrmat.html

Go:   func main()
来源：http://dali.cqqwz.cn/Article/details/gtghbiknug.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgfzy.top/Article/details/gtjhoyiroh.html

C#:   static void Main(string[] args)
来源：http://dali.cucudq.cn/Article/details/gtgkcidrcd.html

[M08] 获取系统与运行时信息
来源：http://dali.zhongyouzk.top/Article/details/gtljgodhpk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sxryk.cn/Article/details/gtpiusafgb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daria6918.cn/Article/details/gtobeepvht.html

JS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gtreywxaed.html

TS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gtslzmdjwh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gteuhymfwa.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sxryk.cn/Article/details/gtfxxetcht.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgfzy.top/Article/details/gtaxskwyep.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.andypj.xyz/Article/details/gtkytcgdaz.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpndmcsn.html

N. 数据结构与算法
来源：http://dali.sweek.top/Article/details/gtpqtvvkvb.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtzhsqxoyv.html

[N01] 二分查找（有序数组）
来源：http://dali.316326.xyz/Article/details/gtvxcwfywt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.birdmap.top/Article/details/gtnuligktf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtiufpuxcg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gtbouaiydk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fengsongda.top/Article/details/gtikrhahov.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtdghlfdga.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gturxasplf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shangyingyoupin.top/Article/details/gtgcslkvyc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtdupxinrc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.c1oappe.top/Article/details/gtwtloacyv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtduirygvw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtbdujufga.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtugbzlnug.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gthrsaxsax.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.9152youxi.cn/Article/details/gtmjdaejsw.html

Go:   slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkxiwbzt.html

Ruby: arr.sort
来源：http://dali.shzxlz.cn/Article/details/gtzklajmoj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.andypj.xyz/Article/details/gtzuanxyiw.html

[N03] 快速排序（分治示例）
来源：http://dali.xuanzx.com/Article/details/gtvharjgdi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guowangkeji.top/Article/details/gtewhrceov.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yongpay.top/Article/details/gtdjxesndz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gtlklwkaco.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gthytcaxtx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.svipenyu.cn/Article/details/gtaiwhqjau.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xziqi.cn/Article/details/gtxkekspam.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yanxiufei.cn/Article/details/gtxnbycbhe.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daxiang520.top/Article/details/gtizlpbqfk.html

[N04] 斐波那契数列
来源：http://dali.gaohongyu789.top/Article/details/gtjoikrhsu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgapptgwr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.pycfn.com/Article/details/gtyicquqtg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtcxjaaijn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gtnxdlqpek.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gtvjecmslx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.quarkkingdee.top/Article/details/gthfpjsmfh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gthdjmkbej.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtbuymkrgn.html

[N05] 最大公约数
来源：http://dali.guowangkeji.top/Article/details/gtgoeloefv.html

Py:   math.gcd(a, b)
来源：http://dali.iojbl.cn/Article/details/gtzyltudji.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.kuanghao11.cn/Article/details/gthijllscc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtcjvgdjks.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gtplecpwzq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cashguo.top/Article/details/gtczqqopaf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.316326.xyz/Article/details/gthhetgnlf.html

Ruby: a.gcd(b)
来源：http://dali.jinqigufen.top/Article/details/gtscbifvgn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yanxiufei.cn/Article/details/gtzmlifrry.html

[N06] 判断回文字符串
来源：http://dali.xuanzx.com/Article/details/gtihclbohq.html

Py:   s == s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gtfibozznf.html

PHP:  $s === strrev($s);
来源：http://dali.yonumen.top/Article/details/gtxrwuckah.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtslkmscaj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtiiwlwdsa.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guannengcc.top/Article/details/gtlzphgvlm.html

Go:   // 双指针从两端比较
来源：http://dali.iojbl.cn/Article/details/gtapwjvjgc.html

Ruby: s == s.reverse
来源：http://dali.yj20258.top/Article/details/gtayrmcehz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gtbsmsponl.html

[N07] 两数之和（返回下标）
来源：http://dali.vqdsnc.cn/Article/details/gtakixoqyi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hammf.cn/Article/details/gtihhphgfu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pycfn.com/Article/details/gtuglfwvsm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.feifeiyinyue.top/Article/details/gtxzppzarw.html

TS:   // 手写 Map<string, number>
来源：http://dali.yvedp.cn/Article/details/gtvwcqptjp.html

Java: // 手写 HashMap
来源：http://dali.feifeiyinyue.top/Article/details/gtrvrswzuq.html

Go:   // 手写 map[int]int
来源：http://dali.gaohongyu789.top/Article/details/gtmujwypuo.html

Ruby: // 手写 Hash
来源：http://dali.ehwqpu.com/Article/details/gtognxovux.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.316326.xyz/Article/details/gtqkqimhve.html

[N08] 生成全排列
来源：http://dali.dianchejie.cn/Article/details/gtabucedri.html

Py:   itertools.permutations(arr)
来源：http://dali.tian-w.cn/Article/details/gteoylgoer.html

PHP:  // 手写递归交换
来源：http://dali.chenzaomai.com/Article/details/gtqzoofumd.html

JS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtbydimsjc.html

TS:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtgcypktgw.html

Java: // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtmavfaxbg.html

Go:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtfecfjpph.html

Ruby: arr.permutation.to_a
来源：http://dali.daxiang520.top/Article/details/gtchoudpob.html

C#:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtvpccbldy.html

[N09] 栈与队列
来源：http://dali.sysykeji.top/Article/details/gtecjthqyc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtebvcvuif.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtqcldpkpy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gtignptiuv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ivvv.top/Article/details/gtjctqehqv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuxming.cn/Article/details/gtjvzwqqxk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.feifeiyinyue.top/Article/details/gtzctpllfd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gtieyqwehx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sysykeji.top/Article/details/gtzxeimcap.html

[N10] 链表节点定义
来源：http://dali.gogol.net.cn/Article/details/gtlnlzlqya.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.aibaodan.cn/Article/details/gtantpcmga.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqpnhqdl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shuidangran.top/Article/details/gtyhyhkubt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.316326.xyz/Article/details/gtvcftvzlb.html

Java: class Node { int v; Node next; }
来源：http://dali.kuanghao11.cn/Article/details/gtqrlkzvmk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hnqzz.top/Article/details/gtlnqepyzr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hammf.cn/Article/details/gtahqmhido.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.wangdashe.top/Article/details/gtaerhbmvg.html

[N11] 二叉树中序遍历
来源：http://dali.sxryk.cn/Article/details/gtzbjkogka.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aizwys.cn/Article/details/gtjinpfcrg.html

PHP:  // 手写递归函数
来源：http://dali.jyoumei.cn/Article/details/gtyxusszas.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gtuwyqyhfu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gthasteabo.html

Java: // 手写递归
来源：http://dali.tian-w.cn/Article/details/gtlzrupxql.html

Go:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtiqfhelpr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guowangkeji.top/Article/details/gtzhqdxkvi.html

C#:   // 手写递归
来源：http://dali.sysykeji.top/Article/details/gtyoibvrsy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gotoacloud.top/Article/details/gtlicoqvwc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenlongwang.top/Article/details/gtelkrxxdm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tanke756.top/Article/details/gtrjbzexjf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gtxbkdasvn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gtabxqatng.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gttzfkeqhk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gzhubu.top/Article/details/gtwejucqfe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nwbrower.top/Article/details/gttvbkzmck.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gtuxqonvay.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gthqskhqlo.html

O. 并发与异步
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztrczcra.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtsfnhabmt.html

[O01] 启动一个线程
来源：http://dali.jinqigfzy.top/Article/details/gtupjunlou.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.birdmap.top/Article/details/gtrjnaimfa.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nanxuanxn.top/Article/details/gtrqvrwptl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnxiangtu.top/Article/details/gtsenqytik.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gtovcdhwuv.html

Java: new Thread(() -> f()).start()
来源：http://dali.316326.xyz/Article/details/gtdsnqbjtv.html

Go:   go f()
来源：http://dali.sweek.top/Article/details/gtruuxcflw.html

Ruby: Thread.new { f }
来源：http://dali.cucudq.cn/Article/details/gthewcnxct.html

C#:   Task.Run(() => F());
来源：http://dali.zhengqikj.top/Article/details/gttupcgljn.html

[O02] 使用线程池
来源：http://dali.pycfn.com/Article/details/gtpkvmnfrn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhengqikj.top/Article/details/gtpzmyvcig.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.pengpengdd.cyou/Article/details/gtbgzeuipr.html

JS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gtbylmdkmb.html

TS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gtbupusbom.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tian-w.cn/Article/details/gtlkhadprd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daria6918.cn/Article/details/gtgkqhqabz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gotoacloud.top/Article/details/gtyklempgi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhoulong.xyz/Article/details/gttuvzcoio.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigufen.top/Article/details/gtpinduuuw.html

Py:   with lock: shared += 1
来源：http://dali.ydzc1.top/Article/details/gtaldevfaj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ehwqpu.com/Article/details/gtqxiiykht.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenzaomai.com/Article/details/gtqonbtlru.html

TS:   // 同 JS
来源：http://dali.jqgufenzy.top/Article/details/gttgumclzh.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbccojfem.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.meibo888.top/Article/details/gtiuruyotm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daxiang520.top/Article/details/gtlkukoqcz.html

C#:   lock (gate) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodoeyovj.html

[O04] 定义异步函数并等待
来源：http://dali.hywenlv.cn/Article/details/gtutovmzxy.html

Py:   async def f():⏎    await g()
来源：http://dali.gotoacloud.top/Article/details/gtedhsxlyo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gogol.net.cn/Article/details/gtzzuvlarp.html

JS:   async function f() { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gtcfllkqkk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuanzx.com/Article/details/gtfsxvujeo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.havefunace.top/Article/details/gttzlgymfv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yanxiufei.cn/Article/details/gtbkkcppve.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhoulong.xyz/Article/details/gtrykfkhlf.html

C#:   async Task F() { await G(); }
来源：http://dali.meibo888.top/Article/details/gtpbtnfjhu.html

[O05] 并发执行并等待全部完成
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnppcuejs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nanxuanxn.top/Article/details/gtoqsxxhwy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gaohongyu789.top/Article/details/gtgkitxfhi.html

JS:   await Promise.all(tasks)
来源：http://dali.yanxiufei.cn/Article/details/gtnvunlxyg.html

TS:   await Promise.all(tasks)
来源：http://dali.gogol.net.cn/Article/details/gtguxmdydt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xziqi.cn/Article/details/gtlswlhbsr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhoulong.xyz/Article/details/gtjxcnnnem.html

Ruby: threads.map(&:join)
来源：http://dali.aibaodan.cn/Article/details/gtgfnroofg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fengsongda.top/Article/details/gtsgxbvbkn.html

[O06] 使用进程池
来源：http://dali.cdnleiting.top/Article/details/gtxtlqjjds.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gtsckiwsbv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.havefunace.top/Article/details/gtuvkbgxeh.html

JS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gtnwbgwdul.html

TS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwzxdhyh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xziqi.cn/Article/details/gtrmjgqafj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenjidiqi.icu/Article/details/gtisaopimy.html

Ruby: // fork 块
来源：http://dali.fzhhl.top/Article/details/gtkqfqmyuy.html

C#:   Parallel.For
来源：http://dali.cdnleiting.top/Article/details/gtlmgdbstq.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtfvenovjd.html

P. 常用工具函数
来源：http://dali.daxiang520.top/Article/details/gtayrnkahe.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gthttucxoi.html

[P01] 生成 UUID
来源：http://dali.gaohongyu789.top/Article/details/gtrrxklcgy.html

Py:   str(uuid.uuid4())
来源：http://dali.smart0.xyz/Article/details/gtkvsnshzl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hnqzz.top/Article/details/gtfhdrgjwj.html

JS:   crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gttoummooy.html

TS:   crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gtsfshkptf.html

Java: UUID.randomUUID().toString()
来源：http://dali.daria6918.cn/Article/details/gtumiyjycp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gtpskstcza.html

Ruby: SecureRandom.uuid
来源：http://dali.feifeiyinyue.top/Article/details/gthmhqdxtl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yongpay.top/Article/details/gtgjvpyblq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj202588.top/Article/details/gtkxpfoxxn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.316326.xyz/Article/details/gtrvalqogq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jyoumei.cn/Article/details/gtdzeivrwm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shangyingyoupin.top/Article/details/gtdoqggqfa.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nanxuanxn.top/Article/details/gtjajoihfb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yvedp.cn/Article/details/gtlfkhpyfk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tian-w.cn/Article/details/gtobepncku.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.smart0.xyz/Article/details/gtovkreovf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nwbrower.top/Article/details/gtrvoblipf.html

[P03] 生成短随机字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtcnytzndu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj202588.top/Article/details/gtfszogimc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cqqwz.cn/Article/details/gtrgfujnrv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yueranfly.top/Article/details/gtasutkclm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258888.top/Article/details/gtinwgyvys.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.iojbl.cn/Article/details/gtobbzqojf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhixingplan.top/Article/details/gthgzfgedj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.kuanghao11.cn/Article/details/gtvimjoauf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guowangkeji.top/Article/details/gtbbzwxnru.html

[P04] 求长度
来源：http://dali.daxiang520.top/Article/details/gtzmnjtekv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ybcxt.top/Article/details/gtpfllvosj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtantwkfgt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gtisjypyxp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daxiang520.top/Article/details/gtqmeltqvo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.316326.xyz/Article/details/gttjjqgesq.html

Go:   len(arr);  len(m)
来源：http://dali.jianghu66.top/Article/details/gtkvmwvvrm.html

Ruby: x.length;  x.size
来源：http://dali.fengsongda.top/Article/details/gtphpnzpqy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.smart0.xyz/Article/details/gtyyethlha.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guowangkeji.top/Article/details/gtilqixkid.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tanke756.top/Article/details/gtykdfmzum.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.feifeiyinyue.top/Article/details/gtlggepfdf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.0kj1m.cn/Article/details/gtwumzsmdg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.bjfxy.top/Article/details/gtnfjdwqsz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.daxiang520.top/Article/details/gtpfjeqvul.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258.top/Article/details/gtwwdgwagc.html

Ruby: a == b
来源：http://dali.hnqzz.top/Article/details/gtcfotbnwr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnxiangtu.top/Article/details/gthkkwtwjq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ppjwa.cn/Article/details/gtewobnbaw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cdnleiting.top/Article/details/gtzcqrhmdm.html

PHP:  if (empty($x)) {}
来源：http://dali.ppjwa.cn/Article/details/gthgsfratr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.birdmap.top/Article/details/gtssjvbwwm.html

TS:   if (x == null) {}
来源：http://dali.pycfn.com/Article/details/gthngaiqhw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.kuanghao11.cn/Article/details/gtacnbfqsd.html

Go:   if x == nil {}
来源：http://dali.yanxiufei.cn/Article/details/gtbsxsshfn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jyoumei.cn/Article/details/gtthzcnknd.html

C#:   if (x is null) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtpumdexze.html

[P07] 防抖与节流
来源：http://dali.wangshuangyany.cn/Article/details/gthxdxzabt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jqgufenzy.top/Article/details/gtqlksrdjs.html

PHP:  // 手写时间戳比较
来源：http://dali.cdnleiting.top/Article/details/gtpklycosa.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gtsfbncdry.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gtuhlpoirq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhixingplan.top/Article/details/gtcxszkhku.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yuxming.cn/Article/details/gtieiukqow.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hnxiangtu.top/Article/details/gtvumvxjjj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnxiangtu.top/Article/details/gtnsktfkqm.html

[P08] 处理浮点精度问题
来源：http://dali.meibo888.top/Article/details/gtohsmbtcd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangdashe.top/Article/details/gtfnuughle.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxinkj.top/Article/details/gtgmoyxlos.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yongpay.top/Article/details/gtttgtmhep.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hfpthk.cn/Article/details/gtaqqhsxpc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daxiang520.top/Article/details/gtclmqrcee.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gotoacloud.top/Article/details/gtktbxksgg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.mhx1999.top/Article/details/gtrctjyrti.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guannengcc.top/Article/details/gtzjiganag.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gthnzinapx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.vqdsnc.cn/Article/details/gtcmumygnu.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtphnferfv.html

[Q01] 创建表
来源：http://dali.aibaodan.cn/Article/details/gtegagjfwt.html


<!-- 参考信息 -->