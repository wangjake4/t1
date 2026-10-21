代发 wailian999

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfukbkvoz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhixingplan.top/Article/details/gtyrzqpslx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.birdmap.top/Article/details/gtapzacljj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gttqjqdvgu.html

[M04] 获取当前工作目录
来源：http://dali.yj202588.top/Article/details/gteikwejxr.html

Py:   os.getcwd()
来源：http://dali.guowangkeji.top/Article/details/gtvcltmnpm.html

PHP:  getcwd();
来源：http://dali.yj20258.top/Article/details/gtfrlgchaj.html

JS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gtyurtfwsy.html

TS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefsdtmwg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dashuyun.cn/Article/details/gtrwkxiyvh.html

Go:   os.Getwd()
来源：http://dali.xinyue.icu/Article/details/gthseycsid.html

Ruby: Dir.pwd
来源：http://dali.daxiang520.top/Article/details/gtoyfsheoq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yanxiufei.cn/Article/details/gtpdqzzqxk.html

[M05] 设置退出码
来源：http://dali.dashuyun.cn/Article/details/gtlblflwud.html

Py:   sys.exit(1)
来源：http://dali.sweek.top/Article/details/gtkkoyeubq.html

PHP:  exit(1);
来源：http://dali.hammf.cn/Article/details/gtfcxfiuaa.html

JS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gtlaqfxjrb.html

TS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtxdjndaau.html

Java: System.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtlkteikrb.html

Go:   os.Exit(1)
来源：http://dali.jyoumei.cn/Article/details/gttzonukyj.html

Ruby: exit 1
来源：http://dali.sweek.top/Article/details/gtfjmytiwc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aibaodan.cn/Article/details/gtmaxdavcs.html

[M06] 向标准错误输出
来源：http://dali.birdmap.top/Article/details/gtnplibxwt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenjidiqi.icu/Article/details/gtvvezindd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guowangkeji.top/Article/details/gtinkcsqgj.html

JS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gtoarkovii.html

TS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gtdxokztcs.html

Java: System.err.println("err")
来源：http://dali.kuanghao11.cn/Article/details/gtbdiossrp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hongshengwenyu.top/Article/details/gtpkyxpcpi.html

Ruby: warn "err"
来源：http://dali.yanxiufei.cn/Article/details/gtqiaqeqvt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hammf.cn/Article/details/gtkzsbpuaf.html

[M07] 判断是否为主入口
来源：http://dali.zhoulong.xyz/Article/details/gtqjpmncfd.html

Py:   if __name__ == "__main__":
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbugwvjap.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pycfn.com/Article/details/gtjfvqpsxf.html

JS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gtypjfkgbm.html

TS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gtjjnvjqtm.html

Java: public static void main(String[] args)
来源：http://dali.tanke756.top/Article/details/gtizjlokop.html

Go:   func main()
来源：http://dali.daxiang520.top/Article/details/gthygxvzpw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nwbrower.top/Article/details/gtyrmblxxz.html

C#:   static void Main(string[] args)
来源：http://dali.sysykeji.top/Article/details/gtiutoghpz.html

[M08] 获取系统与运行时信息
来源：http://dali.yvedp.cn/Article/details/gtnfxpffge.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuxming.cn/Article/details/gtbksarota.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangtech.top/Article/details/gtwldchiqa.html

JS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gtqguynahj.html

TS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gtkbhvyxku.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gtditxuwcp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigufen.top/Article/details/gtpejxbtfp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.svipenyu.cn/Article/details/gtmgzeeanj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.bjfxy.top/Article/details/gtpybfdqnt.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfkixawjf.html

N. 数据结构与算法
来源：http://dali.shuidangran.top/Article/details/gtrhhxywlb.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtfopbewxe.html

[N01] 二分查找（有序数组）
来源：http://dali.yuanzhike.top/Article/details/gtwurfhzlk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtefxxnrvl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtzbetzioc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwilheabn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gtsucqixtg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtnmovoqls.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtlvoslduk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncvunkyi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtastcsemw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.fengsongda.top/Article/details/gtedlgjmwz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gtjdmldtnm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zdqjudy.top/Article/details/gtqzcwvqay.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gtvdvdldkp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtatfixlyd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuetiantiany.cn/Article/details/gteiyjplgw.html

Go:   slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gtcorzprvy.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gtqqgcjiie.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinqigufen.top/Article/details/gtzkgjcukv.html

[N03] 快速排序（分治示例）
来源：http://dali.kuanghao11.cn/Article/details/gtjwgriezu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.dashuyun.cn/Article/details/gtmuvblflo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gzhubu.top/Article/details/gtsyicxszo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gttmcjkkcf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shzxlz.cn/Article/details/gtsevnojpp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xziqi.cn/Article/details/gturcvcqou.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ybcxt.top/Article/details/gttjdxejts.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenlongwang.top/Article/details/gteplgpkfj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.pycfn.com/Article/details/gtzymlwzfq.html

[N04] 斐波那契数列
来源：http://dali.sweek.top/Article/details/gtmywjiera.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtnqahgjzv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gtowlbfkye.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtfbchibkx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtixqqbeta.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.smart0.xyz/Article/details/gtsuabcoou.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jiagoushi.top/Article/details/gtyvhzefpw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jiagoushi.top/Article/details/gtjbnftxen.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtzcnklggd.html

[N05] 最大公约数
来源：http://dali.9152youxi.cn/Article/details/gthmchecsp.html

Py:   math.gcd(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtcufrgqgs.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aizwys.cn/Article/details/gtyotfzjcq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gtljqzpzlh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gtfnpydjdf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guowangkeji.top/Article/details/gtvyheilpk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.c1oappe.top/Article/details/gtbwqrxszv.html

Ruby: a.gcd(b)
来源：http://dali.nanxinkj.top/Article/details/gtojfewngy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.snrcjt.cn/Article/details/gtuckaqwre.html

[N06] 判断回文字符串
来源：http://dali.gzhubu.top/Article/details/gtksgkduci.html

Py:   s == s[::-1]
来源：http://dali.redwolf501.top/Article/details/gtonzicuvw.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gtraexnnvq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtlzztumyv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtcwprnshy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuxming.cn/Article/details/gtkoxqydkm.html

Go:   // 双指针从两端比较
来源：http://dali.sysykeji.top/Article/details/gtodqnmzsz.html

Ruby: s == s.reverse
来源：http://dali.xziqi.cn/Article/details/gtfkdtqesr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gttsapfpvy.html

[N07] 两数之和（返回下标）
来源：http://dali.shuidangran.top/Article/details/gtlgezyzar.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangdashe.top/Article/details/gtrvsgrhhv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuetiantiany.cn/Article/details/gtxcjdtwia.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgfzy.top/Article/details/gtupzgvthe.html

TS:   // 手写 Map<string, number>
来源：http://dali.fengsongda.top/Article/details/gtsvlgijzq.html

Java: // 手写 HashMap
来源：http://dali.yvedp.cn/Article/details/gtvippcvsr.html

Go:   // 手写 map[int]int
来源：http://dali.zhongyouzk.top/Article/details/gteyeuslqf.html

Ruby: // 手写 Hash
来源：http://dali.mhx1999.top/Article/details/gtxhjqczdv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shzxlz.cn/Article/details/gtqkwecxzz.html

[N08] 生成全排列
来源：http://dali.svipenyu.cn/Article/details/gtnywefymi.html

Py:   itertools.permutations(arr)
来源：http://dali.iojbl.cn/Article/details/gthvfyjudi.html

PHP:  // 手写递归交换
来源：http://dali.andypj.xyz/Article/details/gtwufwezfk.html

JS:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtmgdtatht.html

TS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtayaweoko.html

Java: // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtlxqkrune.html

Go:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtqmwglptf.html

Ruby: arr.permutation.to_a
来源：http://dali.iojbl.cn/Article/details/gtaucmwnws.html

C#:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtwnymurpl.html

[N09] 栈与队列
来源：http://dali.chenzaomai.com/Article/details/gtzmqdztgl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hfpthk.cn/Article/details/gtvkwjtnwg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtlyistcah.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gtkiiahxii.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guowangkeji.top/Article/details/gtcqmlykxu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fengsongda.top/Article/details/gtqiikazrr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fzhhl.top/Article/details/gttjzqpruq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gtatalglpq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yvedp.cn/Article/details/gtimkdrcmp.html

[N10] 链表节点定义
来源：http://dali.zhongyouzk.top/Article/details/gtyyxcaybs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ydzc1.top/Article/details/gtkvulmoig.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.redwolf501.top/Article/details/gthmmkpufj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nwbrower.top/Article/details/gtecudsdid.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shuidangran.top/Article/details/gtzowcaivw.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigfzy.top/Article/details/gtgcetqlpz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangtech.top/Article/details/gthvbrzlud.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnxiangtu.top/Article/details/gtytisxqyy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258.top/Article/details/gtmxufsowp.html

[N11] 二叉树中序遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgokqfqi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.quarkkingdee.top/Article/details/gtrpjzxftp.html

PHP:  // 手写递归函数
来源：http://dali.chenjidiqi.icu/Article/details/gtkuchvmdi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gtgmkbuvya.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yangfankeji.com/Article/details/gtkdgrdfkg.html

Java: // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gtecxngnop.html

Go:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gthilnoudd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fengsongda.top/Article/details/gtximiurel.html

C#:   // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gtjohpouky.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gttktacqty.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yuanzhike.top/Article/details/gtpwqjvskr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.mhx1999.top/Article/details/gtsjgujkgq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gzhubu.top/Article/details/gtkuvjecvq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gtirdkkzau.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gtgmavyhst.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daxiang520.top/Article/details/gtwwxehiff.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shzxlz.cn/Article/details/gtcweozcnu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gtcgrfwwvw.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtyygjbnck.html

O. 并发与异步
来源：http://dali.jianghu66.top/Article/details/gtoteglyjc.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtjlsphttl.html

[O01] 启动一个线程
来源：http://dali.yangfankeji.com/Article/details/gtxbjjwudv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.birdmap.top/Article/details/gtnqlyfaqe.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zdqjudy.top/Article/details/gtfqaevhik.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shangyingyoupin.top/Article/details/gtomrmxijf.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gtufjkskrq.html

Java: new Thread(() -> f()).start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchpaloka.html

Go:   go f()
来源：http://dali.wangshuangyany.cn/Article/details/gtoeyxxyva.html

Ruby: Thread.new { f }
来源：http://dali.redwolf501.top/Article/details/gttlskzgsb.html

C#:   Task.Run(() => F());
来源：http://dali.dashuyun.cn/Article/details/gtwblwakxh.html

[O02] 使用线程池
来源：http://dali.yj20258.top/Article/details/gtefvynnwo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangdashe.top/Article/details/gtjksssksd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.316326.xyz/Article/details/gtahwatpxd.html

JS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gtxmvosjfr.html

TS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gtgkipvdgn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hfpthk.cn/Article/details/gtenwiwrdy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxiwaapb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sysykeji.top/Article/details/gtrfqwscyd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.meibo888.top/Article/details/gtotbvjvkf.html

[O03] 加锁保护共享数据
来源：http://dali.hammf.cn/Article/details/gtgsdlvgot.html

Py:   with lock: shared += 1
来源：http://dali.zhiwuduotai.top/Article/details/gtxwzvwccj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hongshengwenyu.top/Article/details/gtjdyahepv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cdnleiting.top/Article/details/gtnrnjmhtx.html

TS:   // 同 JS
来源：http://dali.jlsjyb.cn/Article/details/gtdbgxeskw.html

Java: synchronized (this) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gtbxjswysi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.vqdsnc.cn/Article/details/gtlhgfvvau.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sufxvd.cn/Article/details/gtrwpvedwm.html

C#:   lock (gate) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdglwnjyb.html

[O04] 定义异步函数并等待
来源：http://dali.aibaodan.cn/Article/details/gthbdbtfye.html

Py:   async def f():⏎    await g()
来源：http://dali.fengsongda.top/Article/details/gtnidjusqu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.guowangkeji.top/Article/details/gtcvpofedj.html

JS:   async function f() { await g(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqxcvawc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gtwpbdrmmk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shuidangran.top/Article/details/gtpnqazliq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yanxiufei.cn/Article/details/gtaqhugolq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tian-w.cn/Article/details/gtbxfuqdan.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigfzy.top/Article/details/gtjjvygkjp.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangshuangyany.cn/Article/details/gtultegorj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.9152youxi.cn/Article/details/gtgagopxpi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqaoahit.html

JS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gtyeqdxztk.html

TS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtszregdtj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhixingplan.top/Article/details/gtobsvlkqw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cucudq.cn/Article/details/gtdfwwpfln.html

Ruby: threads.map(&:join)
来源：http://dali.hfpthk.cn/Article/details/gtzjelmwjq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ehwqpu.com/Article/details/gtvsixoqpa.html

[O06] 使用进程池
来源：http://dali.gogol.net.cn/Article/details/gtcrinlgdp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258888.top/Article/details/gtqpwzllhs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ivvv.top/Article/details/gtcoqosarr.html

JS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gthslpgbdt.html

TS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gtnbvjuxjn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.haohaochexian.top/Article/details/gtacvqvlkk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shanyushiyangtech.top/Article/details/gtpidkinvk.html

Ruby: // fork 块
来源：http://dali.zhengqikj.top/Article/details/gtqqygxbik.html

C#:   Parallel.For
来源：http://dali.snrcjt.cn/Article/details/gtgewetdxb.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtgjbaaids.html

P. 常用工具函数
来源：http://dali.c1oappe.top/Article/details/gtticokqme.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtugqhifxh.html

[P01] 生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gtqpmlcwew.html

Py:   str(uuid.uuid4())
来源：http://dali.jinqigfzy.top/Article/details/gtxtwddfsw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sysykeji.top/Article/details/gtqoheyywc.html

JS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gtrufkgxze.html

TS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gtvvprmmwq.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgfzy.top/Article/details/gtnfrrmwtb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.wangshuangyany.cn/Article/details/gtsrtqemet.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgufenzy.top/Article/details/gtzfvczgyk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jyoumei.cn/Article/details/gtcacuyvrc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.guowangkeji.top/Article/details/gtvienkjxv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tian-w.cn/Article/details/gthxrucvom.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinqigfzy.top/Article/details/gthflgrkmh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guannengcc.top/Article/details/gtajrnbxhb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnxiangtu.top/Article/details/gtdvoupocc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xziqi.cn/Article/details/gtumzcklvo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ydzc1.top/Article/details/gtmhdnptbc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cheryme.top/Article/details/gtqzhwwoha.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ybcxt.top/Article/details/gtrexfzzga.html

[P03] 生成短随机字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtlwxrjfhn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cqqwz.cn/Article/details/gtebvmmtdj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shzxlz.cn/Article/details/gtiekqzgrz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcijnducu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkstpnjx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sweek.top/Article/details/gtpnptagit.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pengpengdd.cyou/Article/details/gtbkinemhm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnxiangtu.top/Article/details/gtwchvmdcd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guannengcc.top/Article/details/gtkdwbnhjk.html

[P04] 求长度
来源：http://dali.nanxuanxn.top/Article/details/gtuzbvbjli.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.haohaochexian.top/Article/details/gtidozdubg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gtrhpuwkpi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gttxsdxbve.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gtstyrguqg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtgfazalzp.html

Go:   len(arr);  len(m)
来源：http://dali.meibo888.top/Article/details/gtyasnboez.html

Ruby: x.length;  x.size
来源：http://dali.zhengqikj.top/Article/details/gtfoviisac.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigufen.top/Article/details/gtjlyguzgy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cucudq.cn/Article/details/gtkdkiymxn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.mhx1999.top/Article/details/gtwpdrmrdz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.redwolf501.top/Article/details/gtzdfghwnu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yanxiufei.cn/Article/details/gtbdqswsla.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.iojbl.cn/Article/details/gtdghpiwkw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hnqzz.top/Article/details/gthxpcbngd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cheryme.top/Article/details/gtehhaxpye.html

Ruby: a == b
来源：http://dali.tanke756.top/Article/details/gtzsrkostk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuanzhike.top/Article/details/gtzxrwskei.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hongshengwenyu.top/Article/details/gtjwwotuef.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ivvv.top/Article/details/gtcxoduldg.html

PHP:  if (empty($x)) {}
来源：http://dali.andypj.xyz/Article/details/gtqzardgsd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ivvv.top/Article/details/gthijeqqlh.html

TS:   if (x == null) {}
来源：http://dali.tian-w.cn/Article/details/gtbwzjdsfb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gtpwlesmed.html

Go:   if x == nil {}
来源：http://dali.shuidangran.top/Article/details/gtqwbfcaev.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yvedp.cn/Article/details/gtafisipny.html

C#:   if (x is null) {}
来源：http://dali.jiagoushi.top/Article/details/gtmidrajde.html

[P07] 防抖与节流
来源：http://dali.gaohongyu789.top/Article/details/gtcryvyatj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shzxlz.cn/Article/details/gtwdtjbznf.html

PHP:  // 手写时间戳比较
来源：http://dali.havefunace.top/Article/details/gthmwerlbt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gtddsnsuol.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gtupyukuyx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cqqwz.cn/Article/details/gtpeofltqs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xziqi.cn/Article/details/gttcidwgcb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.0kj1m.cn/Article/details/gterbjhazb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zycfv.cn/Article/details/gttuvgnwfg.html

[P08] 处理浮点精度问题
来源：http://dali.cheryme.top/Article/details/gtjehocgej.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigufen.top/Article/details/gtcdjajibz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenlongwang.top/Article/details/gtgwxrvxjs.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jianghu66.top/Article/details/gtcuudpixm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.pycfn.com/Article/details/gtfvoymurd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.aizwys.cn/Article/details/gtoartyiuq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuxming.cn/Article/details/gtvrwbmxay.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zycfv.cn/Article/details/gtxrrsmmje.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gzhubu.top/Article/details/gtzrlxqggp.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtsertpaxv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cheryme.top/Article/details/gtmdrtacwq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtvrcqetse.html

[Q01] 创建表
来源：http://dali.shzxlz.cn/Article/details/gtlhmrxsbf.html

CREATE TABLE users (
来源：http://dali.hywenlv.cn/Article/details/gtgspswoaw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gotoacloud.top/Article/details/gttpbkyjfk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sysykeji.top/Article/details/gtyrwjcxcn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenlongwang.top/Article/details/gtmjiuorbn.html


<!-- 参考信息 -->