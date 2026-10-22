代发 wailian999

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2chcsjtsw.html

Py:   os.getcwd()
来源：http://dali.zhengqikj.top/Article/details/gt2zayuvhby.html

PHP:  getcwd();
来源：http://dali.meibo888.top/Article/details/gt2pptdqwgy.html

JS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gt2lnjndzob.html

TS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gt2jncwsgdg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.redwolf501.top/Article/details/gt2zapbpjme.html

Go:   os.Getwd()
来源：http://dali.9152youxi.cn/Article/details/gt2zxhpwhvp.html

Ruby: Dir.pwd
来源：http://dali.hywenlv.cn/Article/details/gt2uzklvxhv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.9152youxi.cn/Article/details/gt2kcwcunaj.html

[M05] 设置退出码
来源：http://dali.jianghu66.top/Article/details/gt2ohjkbtax.html

Py:   sys.exit(1)
来源：http://dali.nwbrower.top/Article/details/gt2fnymxjzn.html

PHP:  exit(1);
来源：http://dali.shzxlz.cn/Article/details/gt2eulxteny.html

JS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2gztkizjv.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2reokdqcv.html

Java: System.exit(1)
来源：http://dali.wangdashe.top/Article/details/gt2zmqernxk.html

Go:   os.Exit(1)
来源：http://dali.fzhhl.top/Article/details/gt2sccdomhe.html

Ruby: exit 1
来源：http://dali.dashuyun.cn/Article/details/gt2awbfiwlz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.meibo888.top/Article/details/gt2wcpwmsgc.html

[M06] 向标准错误输出
来源：http://dali.vqdsnc.cn/Article/details/gt2tdrwprcf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.svipenyu.cn/Article/details/gt2fnkgzddw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ybcxt.top/Article/details/gt2slspxzsk.html

JS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gt2izutzzzo.html

TS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gt2mcconthx.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jllfypde.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xylfe.cn/Article/details/gt2vaazzgsi.html

Ruby: warn "err"
来源：http://dali.pengpengdd.cyou/Article/details/gt2gsrsymlg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sysykeji.top/Article/details/gt2lqkvmkqr.html

[M07] 判断是否为主入口
来源：http://dali.wangshuangyany.cn/Article/details/gt2picksonc.html

Py:   if __name__ == "__main__":
来源：http://dali.yvedp.cn/Article/details/gt2buvmgqaa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jqgfzy.top/Article/details/gt2ftzoekjt.html

JS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gt2tiknozcj.html

TS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gt2fdbgvunc.html

Java: public static void main(String[] args)
来源：http://dali.hnxiangtu.top/Article/details/gt2vnuhzjrh.html

Go:   func main()
来源：http://dali.hfpthk.cn/Article/details/gt2kksfodhy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.redwolf501.top/Article/details/gt2wnixrsyk.html

C#:   static void Main(string[] args)
来源：http://dali.yueranfly.top/Article/details/gt2rnywyipb.html

[M08] 获取系统与运行时信息
来源：http://dali.jyoumei.cn/Article/details/gt2xikcqerd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jianghu66.top/Article/details/gt2parmndgg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.meibo888.top/Article/details/gt2ijezcjav.html

JS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gt2xwxnvavk.html

TS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gt2jwbifcre.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dashuyun.cn/Article/details/gt2ditqredj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.andypj.xyz/Article/details/gt2rsknfjgg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xuetiantiany.cn/Article/details/gt2yiimhhvm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sweek.top/Article/details/gt2ctaaebnf.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2dksweeqc.html

N. 数据结构与算法
来源：http://dali.hammf.cn/Article/details/gt2higiwvqb.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2mabwfaaj.html

[N01] 二分查找（有序数组）
来源：http://dali.aizwys.cn/Article/details/gt2armfhweq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tmyuecoc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnqzz.top/Article/details/gt2bkhbajbu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gt2tonsarra.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gt2ulptgizp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gt2imkgjarz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xfafpctg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dianchejie.cn/Article/details/gt2lqjvmhpj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gt2eyuslhcl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aibaodan.cn/Article/details/gt2lrmslitc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gt2fjgwzocb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hywenlv.cn/Article/details/gt2veysyvcv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gt2raxtbwrc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gt2azekvsea.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.redwolf501.top/Article/details/gt2qewvcllu.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2lbqpazwx.html

Ruby: arr.sort
来源：http://dali.pengpengdd.cyou/Article/details/gt2latoiehr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hysaishi.cn/Article/details/gt2ndarmyyo.html

[N03] 快速排序（分治示例）
来源：http://dali.birdmap.top/Article/details/gt2lzpvfmun.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nanxinkj.top/Article/details/gt2hgyxfhje.html

PHP:  // 递归实现，或用 usort
来源：http://dali.mhx1999.top/Article/details/gt2esixzaer.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxinkj.top/Article/details/gt2ihbiolkz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gt2zrttvbsd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhongyouzk.top/Article/details/gt2pwapedod.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jyoumei.cn/Article/details/gt2fttbwejq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangdashe.top/Article/details/gt2bdxmvnkh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.smart0.xyz/Article/details/gt2vgxptaoe.html

[N04] 斐波那契数列
来源：http://dali.c1oappe.top/Article/details/gt2nyulgiox.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gt2iilvnqbz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gt2ngxcexqs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gt2rcleyfxg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lvesmisa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.redwolf501.top/Article/details/gt2vzinrnhk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.snrcjt.cn/Article/details/gt2jcuvwqms.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gt2mqiicpib.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cvodfumv.html

[N05] 最大公约数
来源：http://dali.chenlongwang.top/Article/details/gt2axizqtfr.html

Py:   math.gcd(a, b)
来源：http://dali.fengsongda.top/Article/details/gt2zmsztspc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhoulong.xyz/Article/details/gt2mdbripmx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xinyue.icu/Article/details/gt2qymxbyyz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.bjfxy.top/Article/details/gt2wjvbsebb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bsyrqdfs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daxiang520.top/Article/details/gt2hjafynik.html

Ruby: a.gcd(b)
来源：http://dali.ehwqpu.com/Article/details/gt2ttwiitce.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhoulong.xyz/Article/details/gt2hfzrasgk.html

[N06] 判断回文字符串
来源：http://dali.hammf.cn/Article/details/gt2lnrqtufp.html

Py:   s == s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gt2nohesfdr.html

PHP:  $s === strrev($s);
来源：http://dali.yongpay.top/Article/details/gt2rwhxahig.html

JS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gt2ioqcrwaq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gt2pimtdofi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.dashuyun.cn/Article/details/gt2mrcjlgdk.html

Go:   // 双指针从两端比较
来源：http://dali.jyoumei.cn/Article/details/gt2fxkcpbfx.html

Ruby: s == s.reverse
来源：http://dali.xziqi.cn/Article/details/gt2mzvuqkba.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gt2ughzylqz.html

[N07] 两数之和（返回下标）
来源：http://dali.yangfankeji.com/Article/details/gt2kebnjqle.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.redwolf501.top/Article/details/gt2iloupqrg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ppjwa.cn/Article/details/gt2fzilabwl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hywenlv.cn/Article/details/gt2iqixgamj.html

TS:   // 手写 Map<string, number>
来源：http://dali.c1oappe.top/Article/details/gt2bplacwvp.html

Java: // 手写 HashMap
来源：http://dali.fzhhl.top/Article/details/gt2pmxlqhgv.html

Go:   // 手写 map[int]int
来源：http://dali.sxryk.cn/Article/details/gt2vmpuafcd.html

Ruby: // 手写 Hash
来源：http://dali.xuetiantiany.cn/Article/details/gt2ydwmjgpo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hammf.cn/Article/details/gt2twwamxgc.html

[N08] 生成全排列
来源：http://dali.jiagoushi.top/Article/details/gt2wqdigoeb.html

Py:   itertools.permutations(arr)
来源：http://dali.mhx1999.top/Article/details/gt2murdboyo.html

PHP:  // 手写递归交换
来源：http://dali.yanxiufei.cn/Article/details/gt2ntyxtdtk.html

JS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gt2tmxywoiw.html

TS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2xqqaffgk.html

Java: // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2eflfiomc.html

Go:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gt2hddduhdb.html

Ruby: arr.permutation.to_a
来源：http://dali.chenzaomai.com/Article/details/gt2wqfmzvkc.html

C#:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gt2hbqsawxe.html

[N09] 栈与队列
来源：http://dali.guowangkeji.top/Article/details/gt2hiemkjrh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.snrcjt.cn/Article/details/gt2iivzplqo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.pycfn.com/Article/details/gt2ehggezbe.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ttjwrvkk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sysykeji.top/Article/details/gt2oeaptqno.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbttxac.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xylfe.cn/Article/details/gt2voicflpe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gt2zgbdqofm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yangfankeji.com/Article/details/gt2aqglnoms.html

[N10] 链表节点定义
来源：http://dali.xuetiantiany.cn/Article/details/gt2woxntfbu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yonumen.top/Article/details/gt2kgjzbhzl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yonumen.top/Article/details/gt2cjbgjepx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xtrewxsa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cashguo.top/Article/details/gt2oqvwwfuy.html

Java: class Node { int v; Node next; }
来源：http://dali.shuidangran.top/Article/details/gt2upwcemlv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yuanzhike.top/Article/details/gt2ldplzokl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ivvv.top/Article/details/gt2zfuustov.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ydzc1.top/Article/details/gt2bblyghed.html

[N11] 二叉树中序遍历
来源：http://dali.shuidangran.top/Article/details/gt2cdukjqtj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenzaomai.com/Article/details/gt2zzxudozl.html

PHP:  // 手写递归函数
来源：http://dali.yonumen.top/Article/details/gt2ikanbpqe.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dianchejie.cn/Article/details/gt2qcgfztci.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qyvadajj.html

Java: // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gt2bsmfusgp.html

Go:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gt2mabyumtk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cheryme.top/Article/details/gt2dymfmiop.html

C#:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gt2mhpjdhpd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.quarkkingdee.top/Article/details/gt2ketjghja.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yangfankeji.com/Article/details/gt2enefvucu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nbiyucku.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djxpuoou.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gt2eiwgeyku.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gt2gymuvthy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenlongwang.top/Article/details/gt2agiwdtyv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinqigfzy.top/Article/details/gt2fqhyqhpd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gt2heezqfeh.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2gjgmtsyh.html

O. 并发与异步
来源：http://dali.9152youxi.cn/Article/details/gt2wajqylcf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2qdinajfb.html

[O01] 启动一个线程
来源：http://dali.yangfankeji.com/Article/details/gt2tnjzrxdt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hammf.cn/Article/details/gt2higvydsh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.andypj.xyz/Article/details/gt2uscwvhgk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhengqikj.top/Article/details/gt2zzeiwizn.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gt2zctxprjc.html

Java: new Thread(() -> f()).start()
来源：http://dali.daria6918.cn/Article/details/gt2gwhuvafk.html

Go:   go f()
来源：http://dali.sxryk.cn/Article/details/gt2jaqauoae.html

Ruby: Thread.new { f }
来源：http://dali.pycfn.com/Article/details/gt2xppyvogi.html

C#:   Task.Run(() => F());
来源：http://dali.hnxiangtu.top/Article/details/gt2wrkslipc.html

[O02] 使用线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dcxfvyau.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gaohongyu789.top/Article/details/gt2myxqudih.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhongyouzk.top/Article/details/gt2gkqnakpa.html

JS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gt2ekqzsprw.html

TS:   // worker_threads 线程池
来源：http://dali.jlsjyb.cn/Article/details/gt2bijcmmoi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.redwolf501.top/Article/details/gt2fkhvbskw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangdashe.top/Article/details/gt2izisohqb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ppjwa.cn/Article/details/gt2ffvpgxyl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.redwolf501.top/Article/details/gt2mfpgddry.html

[O03] 加锁保护共享数据
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dwdgkiil.html

Py:   with lock: shared += 1
来源：http://dali.dianchejie.cn/Article/details/gt2xismouvx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guannengcc.top/Article/details/gt2cbbpxgah.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fzhhl.top/Article/details/gt2bctvzamp.html

TS:   // 同 JS
来源：http://dali.yuanzhike.top/Article/details/gt2csijfabz.html

Java: synchronized (this) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gt2qinecgse.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oiiwtwws.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjqtwhy.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gt2jxgolfvq.html

[O04] 定义异步函数并等待
来源：http://dali.birdmap.top/Article/details/gt2uqulgaot.html

Py:   async def f():⏎    await g()
来源：http://dali.dashuyun.cn/Article/details/gt2pwvrznqo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gaohongyu789.top/Article/details/gt2pochxwto.html

JS:   async function f() { await g(); }
来源：http://dali.9152youxi.cn/Article/details/gt2akkstoff.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gt2ywafxxvk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tianlin.xyz/Article/details/gt2drtrmxqk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wgpzvhro.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.snrcjt.cn/Article/details/gt2pdxbnxaw.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgfzy.top/Article/details/gt2jvjcwkfb.html

[O05] 并发执行并等待全部完成
来源：http://dali.gotoacloud.top/Article/details/gt2prdvtifm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.fengsongda.top/Article/details/gt2nnduplvd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dashuyun.cn/Article/details/gt2vcuwrjns.html

JS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gt2bamiqjsw.html

TS:   await Promise.all(tasks)
来源：http://dali.0kj1m.cn/Article/details/gt2ottfjojz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yanxiufei.cn/Article/details/gt2eanuuekl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.iojbl.cn/Article/details/gt2ogyagyiv.html

Ruby: threads.map(&:join)
来源：http://dali.meibo888.top/Article/details/gt2yhazvsrp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nanxuanxn.top/Article/details/gt2gzjjxira.html

[O06] 使用进程池
来源：http://dali.ehwqpu.com/Article/details/gt2wsukundb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jianghu66.top/Article/details/gt2nehmpzhs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.iojbl.cn/Article/details/gt2xobndgwb.html

JS:   // child_process / cluster 模块
来源：http://dali.birdmap.top/Article/details/gt2czvzdtbb.html

TS:   // child_process / cluster 模块
来源：http://dali.shzxlz.cn/Article/details/gt2wdxfpujd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daria6918.cn/Article/details/gt2pdpqjtdy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sufxvd.cn/Article/details/gt2eadnidgv.html

Ruby: // fork 块
来源：http://dali.hnxiangtu.top/Article/details/gt2hiviatmd.html

C#:   Parallel.For
来源：http://dali.jianghu66.top/Article/details/gt2tbetdubf.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2kloezkvd.html

P. 常用工具函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2lrdxzhso.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2scuoxdyy.html

[P01] 生成 UUID
来源：http://dali.gaohongyu789.top/Article/details/gt2uftkuskk.html

Py:   str(uuid.uuid4())
来源：http://dali.ybcxt.top/Article/details/gt2fxmcrdhk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.birdmap.top/Article/details/gt2phnaqcfc.html

JS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gt2dpcbirup.html

TS:   crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qvzgfzmt.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnxiangtu.top/Article/details/gt2qviasoae.html

Go:   // 用 github.com/google/uuid
来源：http://dali.kuanghao11.cn/Article/details/gt2jbktpthp.html

Ruby: SecureRandom.uuid
来源：http://dali.tian-w.cn/Article/details/gt2xbksfpzc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2fihxgpfi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.fzhhl.top/Article/details/gt2vhdfmzop.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenlongwang.top/Article/details/gt2vmcutrhd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rrdroqlf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shzxlz.cn/Article/details/gt2urtiwctg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xinyue.icu/Article/details/gt2qqhqmsnt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yangfankeji.com/Article/details/gt2dukxfdoz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xylfe.cn/Article/details/gt2tzlwpfkm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxinkj.top/Article/details/gt2aalxiifv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hywenlv.cn/Article/details/gt2uenobqkv.html

[P03] 生成短随机字符串
来源：http://dali.redwolf501.top/Article/details/gt2ezehftqv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yanxiufei.cn/Article/details/gt2ztnlvfkh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.pengpengdd.cyou/Article/details/gt2yfyrrzlw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhengqikj.top/Article/details/gt2rlttynsn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gt2vxdgujfe.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsptpwu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jiagoushi.top/Article/details/gt2lchazwsn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxinkj.top/Article/details/gt2glfcdjwf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hysaishi.cn/Article/details/gt2hrkvyhqa.html

[P04] 求长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kxvknbpm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zdqjudy.top/Article/details/gt2axhkcvwf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gt2gusvfwqc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nwbrower.top/Article/details/gt2zazfpoqj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xinyue.icu/Article/details/gt2omqmuyfc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ppjwa.cn/Article/details/gt2zanevpth.html

Go:   len(arr);  len(m)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2axllcxvi.html

Ruby: x.length;  x.size
来源：http://dali.meibo888.top/Article/details/gt2sphknesv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.andypj.xyz/Article/details/gt2nmjprzpu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gzhubu.top/Article/details/gt2lwxkjhga.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhoulong.xyz/Article/details/gt2qewjdind.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sxryk.cn/Article/details/gt2mivfjjgh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yongpay.top/Article/details/gt2hnbmkfdt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hysaishi.cn/Article/details/gt2lllfanyw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shuidangran.top/Article/details/gt2msuvevxs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yongpay.top/Article/details/gt2cxelwkdd.html

Ruby: a == b
来源：http://dali.hnqzz.top/Article/details/gt2brkecxvn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.meibo888.top/Article/details/gt2bsdgzicn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.andypj.xyz/Article/details/gt2ugxrsqgi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhoulong.xyz/Article/details/gt2nzioyuxb.html

PHP:  if (empty($x)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2msafhppo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.havefunace.top/Article/details/gt2ygtxwgrx.html

TS:   if (x == null) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2rnujdlly.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.andypj.xyz/Article/details/gt2vhhxytym.html

Go:   if x == nil {}
来源：http://dali.shuidangran.top/Article/details/gt2bviwyxpo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yqrvgqxc.html

C#:   if (x is null) {}
来源：http://dali.0kj1m.cn/Article/details/gt2wcsjsjfp.html

[P07] 防抖与节流
来源：http://dali.svipenyu.cn/Article/details/gt2sxpfjktx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yonumen.top/Article/details/gt2oetcamcr.html

PHP:  // 手写时间戳比较
来源：http://dali.hfpthk.cn/Article/details/gt2izxhytev.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gt2krhtzxfq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigfzy.top/Article/details/gt2shtlauhy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.havefunace.top/Article/details/gt2reegfwxm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigfzy.top/Article/details/gt2cdpmvvwi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangdashe.top/Article/details/gt2vfnftnhk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jqgufenzy.top/Article/details/gt2sdaiygra.html

[P08] 处理浮点精度问题
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2blgjenwb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ftxflywx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.wangdashe.top/Article/details/gt2ublohgno.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.feifeiyinyue.top/Article/details/gt2jbimqzin.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ydzc1.top/Article/details/gt2nfbxkqen.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.smart0.xyz/Article/details/gt2iywcdklg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shzxlz.cn/Article/details/gt2hkxfimcf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigfzy.top/Article/details/gt2bmhqoogn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hywenlv.cn/Article/details/gt2jomsxzjn.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2hcnldtyx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuxming.cn/Article/details/gt2xtolwuws.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2lclezowi.html

[Q01] 创建表
来源：http://dali.xuetiantiany.cn/Article/details/gt2tvbuyqqu.html

CREATE TABLE users (
来源：http://dali.316326.xyz/Article/details/gt2umgzzrrj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tanke756.top/Article/details/gt2ywydwtno.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shuidangran.top/Article/details/gt2njmrmalg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cdnleiting.top/Article/details/gt2ntibhmhe.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenjidiqi.icu/Article/details/gt2kwnjzaca.html

);
来源：http://dali.feifeiyinyue.top/Article/details/gt2egokxkkm.html

[Q02] 创建带外键的表
来源：http://dali.pengpengdd.cyou/Article/details/gt2wtearhyi.html

CREATE TABLE orders (
来源：http://dali.nwbrower.top/Article/details/gt2okqxqthv.html


<!-- 参考信息 -->