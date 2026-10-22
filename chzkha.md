代发 wailian999

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenzaomai.com/Article/details/gt2xdtxvpza.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.pycfn.com/Article/details/gt2qbuzpybj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.snrcjt.cn/Article/details/gt2crowezuu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guowangkeji.top/Article/details/gt2avrnsvje.html

[M04] 获取当前工作目录
来源：http://dali.bjfxy.top/Article/details/gt2vwgxuikm.html

Py:   os.getcwd()
来源：http://dali.yj20258.top/Article/details/gt2tktvwrsa.html

PHP:  getcwd();
来源：http://dali.dianchejie.cn/Article/details/gt2lvykbtog.html

JS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eciezgdj.html

TS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gt2gzfctwyw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ehwqpu.com/Article/details/gt2rzuvqcew.html

Go:   os.Getwd()
来源：http://dali.hfpthk.cn/Article/details/gt2cqfrucnm.html

Ruby: Dir.pwd
来源：http://dali.shanyushiyangtech.top/Article/details/gt2toztyulu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.haohaochexian.top/Article/details/gt2cglewubs.html

[M05] 设置退出码
来源：http://dali.jqgufenzy.top/Article/details/gt2sgrrzumj.html

Py:   sys.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2ogpvrefb.html

PHP:  exit(1);
来源：http://dali.zhixingplan.top/Article/details/gt2gwbgzgla.html

JS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2uaeyjhog.html

TS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2uzyxubls.html

Java: System.exit(1)
来源：http://dali.nwbrower.top/Article/details/gt2tzfipejz.html

Go:   os.Exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2oebbbjkv.html

Ruby: exit 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rgmrcnmy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jlsjyb.cn/Article/details/gt2qshajblg.html

[M06] 向标准错误输出
来源：http://dali.redwolf501.top/Article/details/gt2yzvlibci.html

Py:   print("err", file=sys.stderr)
来源：http://dali.iojbl.cn/Article/details/gt2mkxorhxr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yangfankeji.com/Article/details/gt2sekvxqcu.html

JS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gt2felnjdcb.html

TS:   console.error("err")
来源：http://dali.nwbrower.top/Article/details/gt2wnzmxcfn.html

Java: System.err.println("err")
来源：http://dali.zdqjudy.top/Article/details/gt2dgxtjpzw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hysaishi.cn/Article/details/gt2dyikwrlb.html

Ruby: warn "err"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oifqtsut.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.dashuyun.cn/Article/details/gt2xfihbnqf.html

[M07] 判断是否为主入口
来源：http://dali.gaohongyu789.top/Article/details/gt2yirhhmfn.html

Py:   if __name__ == "__main__":
来源：http://dali.cucudq.cn/Article/details/gt2oelwmsdv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shzxlz.cn/Article/details/gt2ckbrxpju.html

JS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gt2zslcgyvo.html

TS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gt2qutkxlxv.html

Java: public static void main(String[] args)
来源：http://dali.gogol.net.cn/Article/details/gt2gfzypovx.html

Go:   func main()
来源：http://dali.fzhhl.top/Article/details/gt2owstfkoz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ksoiiwqf.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2acceqlio.html

[M08] 获取系统与运行时信息
来源：http://dali.redwolf501.top/Article/details/gt2gtkplvhj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xziqi.cn/Article/details/gt2skyrhrkh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigufen.top/Article/details/gt2isrxsucl.html

JS:   process.platform;  process.version
来源：http://dali.c1oappe.top/Article/details/gt2decouhwk.html

TS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gt2isevuakn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hysaishi.cn/Article/details/gt2nreardjb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cdnleiting.top/Article/details/gt2tlzbwnjp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fzhhl.top/Article/details/gt2fnufhwwt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.havefunace.top/Article/details/gt2aysvyfft.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2hkhnlnbj.html

N. 数据结构与算法
来源：http://dali.xziqi.cn/Article/details/gt2bopdjpdy.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2hygqlsdg.html

[N01] 二分查找（有序数组）
来源：http://dali.gogol.net.cn/Article/details/gt2bakfrhvc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2ibrnfryo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tian-w.cn/Article/details/gt2ynuptkbf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guowangkeji.top/Article/details/gt2xydynnjr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gt2qoemysww.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2woybhcfd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2zlcqumjl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zycfv.cn/Article/details/gt2hvmxkigp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2oozeeewf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuanzx.com/Article/details/gt2ebfindll.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gt2zzxqrbml.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigufen.top/Article/details/gt2mnirfyyl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gt2ezbbbcgf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gt2advyxlfk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shuidangran.top/Article/details/gt2xgoiztta.html

Go:   slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2dwpwbfmf.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gt2swxvuyap.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yongpay.top/Article/details/gt2vukmygtr.html

[N03] 快速排序（分治示例）
来源：http://dali.gogol.net.cn/Article/details/gt2jglgllzj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nanxuanxn.top/Article/details/gt2unqdtkdz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daxiang520.top/Article/details/gt2wydygxdc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tian-w.cn/Article/details/gt2qtdminyh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhixingplan.top/Article/details/gt2ullwilse.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shuidangran.top/Article/details/gt2mjkvfiwu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sxryk.cn/Article/details/gt2njzjybqx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fengsongda.top/Article/details/gt2teecqpsq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hongshengwenyu.top/Article/details/gt2hcitrggh.html

[N04] 斐波那契数列
来源：http://dali.ybcxt.top/Article/details/gt2xdtsbbud.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gt2bjsacegd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.birdmap.top/Article/details/gt2qbfrhlhr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gt2uqegwcsh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gt2dofvbpuc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ivvv.top/Article/details/gt2edbyjzid.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yangfankeji.com/Article/details/gt2vscttwxz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gt2ekkyktcq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gt2usaokqmt.html

[N05] 最大公约数
来源：http://dali.snrcjt.cn/Article/details/gt2hjptwuia.html

Py:   math.gcd(a, b)
来源：http://dali.zdqjudy.top/Article/details/gt2lqaodtxt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gogol.net.cn/Article/details/gt2adtupiri.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aibaodan.cn/Article/details/gt2rtlcjomw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gt2lwevuylm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.andypj.xyz/Article/details/gt2hzusbrol.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hammf.cn/Article/details/gt2kkgdprjo.html

Ruby: a.gcd(b)
来源：http://dali.yangfankeji.com/Article/details/gt2ymqvkucw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.smart0.xyz/Article/details/gt2cbybwsjx.html

[N06] 判断回文字符串
来源：http://dali.yongpay.top/Article/details/gt2kpotcbqv.html

Py:   s == s[::-1]
来源：http://dali.guannengcc.top/Article/details/gt2bozrsunb.html

PHP:  $s === strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xntcalru.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gt2gnjkelsb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2kulaoftb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenzaomai.com/Article/details/gt2qzmaachd.html

Go:   // 双指针从两端比较
来源：http://dali.ybcxt.top/Article/details/gt2lykhggmu.html

Ruby: s == s.reverse
来源：http://dali.sxryk.cn/Article/details/gt2wzbyanff.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gt2talsnpkd.html

[N07] 两数之和（返回下标）
来源：http://dali.mhx1999.top/Article/details/gt2veepjtuc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jqgufenzy.top/Article/details/gt2yfuwyury.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ilqnatfn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.316326.xyz/Article/details/gt2ygfulxgi.html

TS:   // 手写 Map<string, number>
来源：http://dali.tianlin.xyz/Article/details/gt2dvtthjcr.html

Java: // 手写 HashMap
来源：http://dali.jinqigfzy.top/Article/details/gt2zhtdqvvp.html

Go:   // 手写 map[int]int
来源：http://dali.gogol.net.cn/Article/details/gt2fgllqnbe.html

Ruby: // 手写 Hash
来源：http://dali.ehwqpu.com/Article/details/gt2okqzxnrg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.snrcjt.cn/Article/details/gt2ushjirqg.html

[N08] 生成全排列
来源：http://dali.sysykeji.top/Article/details/gt2jsccrtou.html

Py:   itertools.permutations(arr)
来源：http://dali.yuxming.cn/Article/details/gt2cffrnmtn.html

PHP:  // 手写递归交换
来源：http://dali.cheryme.top/Article/details/gt2tatssmle.html

JS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2tsdcxkxy.html

TS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gt2mveaoycw.html

Java: // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gt2jmxafghe.html

Go:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2ftuhvohs.html

Ruby: arr.permutation.to_a
来源：http://dali.yangfankeji.com/Article/details/gt2pzwxsvlm.html

C#:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2mutfuzfv.html

[N09] 栈与队列
来源：http://dali.chenlongwang.top/Article/details/gt2jcihizmy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.bjfxy.top/Article/details/gt2ofoyygni.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rqerbukq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gt2dgliofdy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.meibo888.top/Article/details/gt2aaoryomz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.vqdsnc.cn/Article/details/gt2irlxrnwo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.dashuyun.cn/Article/details/gt2jidogbls.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gt2ycyogmbg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hywenlv.cn/Article/details/gt2sqaprvce.html

[N10] 链表节点定义
来源：http://dali.hywenlv.cn/Article/details/gt2ygdvdrua.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zdqjudy.top/Article/details/gt2dyerhycm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ngjoeqta.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cdnleiting.top/Article/details/gt2ktwzlmer.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shzxlz.cn/Article/details/gt2yaldutqx.html

Java: class Node { int v; Node next; }
来源：http://dali.birdmap.top/Article/details/gt2dogyulpo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ruuvgccv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnqzz.top/Article/details/gt2tddivjgp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2svsnyvtm.html

[N11] 二叉树中序遍历
来源：http://dali.zhixingplan.top/Article/details/gt2fxzuhlct.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj202588.top/Article/details/gt2bgklqrzy.html

PHP:  // 手写递归函数
来源：http://dali.sufxvd.cn/Article/details/gt2ybjdgzpb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsupbrs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhoulong.xyz/Article/details/gt2pinnjbai.html

Java: // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2psustkoy.html

Go:   // 手写递归
来源：http://dali.sysykeji.top/Article/details/gt2kzrrodcc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.andypj.xyz/Article/details/gt2vxwhrtnl.html

C#:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gt2olzjbmxf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.c1oappe.top/Article/details/gt2eozkjhqu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xziqi.cn/Article/details/gt2eufzgwvb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.pycfn.com/Article/details/gt2mvidgwfn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hywenlv.cn/Article/details/gt2evatdinh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yueranfly.top/Article/details/gt2rpjnhjkk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dkksdyle.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cdnleiting.top/Article/details/gt2fkenjaks.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fnidygqo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gt2gqfqunjb.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2gcswrgnn.html

O. 并发与异步
来源：http://dali.nwbrower.top/Article/details/gt2ksmdjjni.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2pihutiuh.html

[O01] 启动一个线程
来源：http://dali.daria6918.cn/Article/details/gt2ffpopexo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aibaodan.cn/Article/details/gt2jpfstkdq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nwbrower.top/Article/details/gt2bgnkocbc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhongyouzk.top/Article/details/gt2mmvezwyu.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gt2vhhoyooq.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhiwuduotai.top/Article/details/gt2bjczwmwy.html

Go:   go f()
来源：http://dali.yuxming.cn/Article/details/gt2hhcwkpdv.html

Ruby: Thread.new { f }
来源：http://dali.hnxiangtu.top/Article/details/gt2fokfbdja.html

C#:   Task.Run(() => F());
来源：http://dali.quarkkingdee.top/Article/details/gt2kjubjibg.html

[O02] 使用线程池
来源：http://dali.yuanzhike.top/Article/details/gt2clsprilq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxuanxn.top/Article/details/gt2arxcgcvn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.quarkkingdee.top/Article/details/gt2sposluqp.html

JS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gt2hweqpsfq.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vxdxtsou.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dashuyun.cn/Article/details/gt2cxxdiehj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yangfankeji.com/Article/details/gt2xmoivvvm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.9152youxi.cn/Article/details/gt2zpxbjudg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.kuanghao11.cn/Article/details/gt2jpzhtvfi.html

[O03] 加锁保护共享数据
来源：http://dali.guowangkeji.top/Article/details/gt2udnbosdn.html

Py:   with lock: shared += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2elqhadnq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgfzy.top/Article/details/gt2nzuvkxla.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pcavshbh.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gt2qwvdpasq.html

Java: synchronized (this) { shared++; }
来源：http://dali.zdqjudy.top/Article/details/gt2suqdxcae.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.guowangkeji.top/Article/details/gt2yiiixxsb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pycfn.com/Article/details/gt2iyhoogoo.html

C#:   lock (gate) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gt2finmqlix.html

[O04] 定义异步函数并等待
来源：http://dali.cashguo.top/Article/details/gt2lokuhzjn.html

Py:   async def f():⏎    await g()
来源：http://dali.shuidangran.top/Article/details/gt2ysgozojo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.fzhhl.top/Article/details/gt2zzddqauw.html

JS:   async function f() { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gt2coznoxhu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xylfe.cn/Article/details/gt2zgbshopu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenjidiqi.icu/Article/details/gt2gizjctrx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhongyouzk.top/Article/details/gt2kdifahey.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.andypj.xyz/Article/details/gt2nonqjllo.html

C#:   async Task F() { await G(); }
来源：http://dali.dashuyun.cn/Article/details/gt2epmlwywb.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigufen.top/Article/details/gt2bykbwldr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yvedp.cn/Article/details/gt2zcedczxm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pengpengdd.cyou/Article/details/gt2ebpiqlty.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2msarnxys.html

TS:   await Promise.all(tasks)
来源：http://dali.zhongyouzk.top/Article/details/gt2kriakaml.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jianghu66.top/Article/details/gt2nfqweuzz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.smart0.xyz/Article/details/gt2vpvadctl.html

Ruby: threads.map(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gt2muakwgdw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgufenzy.top/Article/details/gt2idewancj.html

[O06] 使用进程池
来源：http://dali.c1oappe.top/Article/details/gt2vocumcwq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gogol.net.cn/Article/details/gt2qempehah.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jlsjyb.cn/Article/details/gt2ijgmmgik.html

JS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gt2nopvvdhj.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258888.top/Article/details/gt2yprljdpe.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhongyouzk.top/Article/details/gt2oflzjtqp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.9152youxi.cn/Article/details/gt2wxqublaw.html

Ruby: // fork 块
来源：http://dali.jinqigfzy.top/Article/details/gt2imhcjtia.html

C#:   Parallel.For
来源：http://dali.ehwqpu.com/Article/details/gt2neagyvpj.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2qniiaquk.html

P. 常用工具函数
来源：http://dali.ydzc1.top/Article/details/gt2uyobkfkv.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2svwekfvs.html

[P01] 生成 UUID
来源：http://dali.wangdashe.top/Article/details/gt2uvdwrvfp.html

Py:   str(uuid.uuid4())
来源：http://dali.yuanzhike.top/Article/details/gt2cmfjxeaw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gt2vzpytxwm.html

JS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gt2eurccrge.html

TS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2swesbogv.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnqzz.top/Article/details/gt2cqvnakuh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nanxuanxn.top/Article/details/gt2squhqtar.html

Ruby: SecureRandom.uuid
来源：http://dali.chenlongwang.top/Article/details/gt2enxgwmzc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnqzz.top/Article/details/gt2vznjxsdg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xuanzx.com/Article/details/gt2envdvxra.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.fengsongda.top/Article/details/gt2czrjufzf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jqgfzy.top/Article/details/gt2msxjmwrm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.kuanghao11.cn/Article/details/gt2nvfugjpw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dxibdwjz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jiagoushi.top/Article/details/gt2gbkfvuez.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhongyouzk.top/Article/details/gt2xpsgcbyd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258888.top/Article/details/gt2nfnexfuv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.9152youxi.cn/Article/details/gt2laalzgcw.html

[P03] 生成短随机字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2wmcenkwq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pengpengdd.cyou/Article/details/gt2jilabwiv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnxiangtu.top/Article/details/gt2myhiijhh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sufxvd.cn/Article/details/gt2tnzozvyx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gt2ataznlvp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xinyue.icu/Article/details/gt2uccahnls.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xdsczjvb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.redwolf501.top/Article/details/gt2nlpzqjta.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xylfe.cn/Article/details/gt2ianqlyid.html

[P04] 求长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2jdxjawqs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hfpthk.cn/Article/details/gt2mivdytdz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gt2tmzvtvum.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gt2fkveyjba.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.andypj.xyz/Article/details/gt2cgkztxtl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangdashe.top/Article/details/gt2spfiwlck.html

Go:   len(arr);  len(m)
来源：http://dali.jianghu66.top/Article/details/gt2ocvbqofm.html

Ruby: x.length;  x.size
来源：http://dali.chenzaomai.com/Article/details/gt2zfsigflh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zdqjudy.top/Article/details/gt2mbnkwkpl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.kuanghao11.cn/Article/details/gt2ohoxuqsk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guowangkeji.top/Article/details/gt2ovqnusnc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.wangdashe.top/Article/details/gt2bjvvohdk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ybcxt.top/Article/details/gt2cgbhwuye.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgufenzy.top/Article/details/gt2bnonjokj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dianchejie.cn/Article/details/gt2vgylxbaj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lkvggcmx.html

Ruby: a == b
来源：http://dali.hysaishi.cn/Article/details/gt2iumtydya.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jianghu66.top/Article/details/gt2leenyxbf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jqubwjyk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yuxming.cn/Article/details/gt2dngdrjkx.html

PHP:  if (empty($x)) {}
来源：http://dali.meibo888.top/Article/details/gt2lmbbqgib.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.redwolf501.top/Article/details/gt2ylhlrrek.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdztpwz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gt2nuucsoaz.html

Go:   if x == nil {}
来源：http://dali.nwbrower.top/Article/details/gt2omjkkzlj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.iojbl.cn/Article/details/gt2voxzzepu.html

C#:   if (x is null) {}
来源：http://dali.cheryme.top/Article/details/gt2xqukusxk.html

[P07] 防抖与节流
来源：http://dali.yuanzhike.top/Article/details/gt2deiwmjgh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xylfe.cn/Article/details/gt2bgkaunpw.html

PHP:  // 手写时间戳比较
来源：http://dali.nanxinkj.top/Article/details/gt2uaxsxdqc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gt2pewtlohi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gt2haodifds.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yueranfly.top/Article/details/gt2xhxlokyo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nanxuanxn.top/Article/details/gt2jnlmxruf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.guannengcc.top/Article/details/gt2fvnzkimr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxuanxn.top/Article/details/gt2gbkhpgpr.html

[P08] 处理浮点精度问题
来源：http://dali.chenzaomai.com/Article/details/gt2kkautppy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shzxlz.cn/Article/details/gt2ruwwkilj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shzxlz.cn/Article/details/gt2dcqkfvzc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lpyyppes.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.meibo888.top/Article/details/gt2ffgjfgpo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cheryme.top/Article/details/gt2eggntynp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cucudq.cn/Article/details/gt2dmlqzywr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.meibo888.top/Article/details/gt2myrjqxwu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.vqdsnc.cn/Article/details/gt2nfviclvs.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2uzjyacol.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.aibaodan.cn/Article/details/gt2oemleqqp.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2czgyfrjo.html

[Q01] 创建表
来源：http://dali.fengsongda.top/Article/details/gt2eeaflxqn.html

CREATE TABLE users (
来源：http://dali.wangshuangyany.cn/Article/details/gt2leslyszj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gt2fwqndgad.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yongpay.top/Article/details/gt2njlqgbdv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gogol.net.cn/Article/details/gt2yjczauvs.html


<!-- 参考信息 -->