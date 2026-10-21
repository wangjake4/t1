代发 wailian999

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258888.top/Article/details/gtlkxzdfzz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gtbrmuuocq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.c1oappe.top/Article/details/gtbhwblnfi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinghuilouyu.cn/Article/details/gtmunpilwd.html

[M04] 获取当前工作目录
来源：http://dali.ppjwa.cn/Article/details/gtdzhrqwdg.html

Py:   os.getcwd()
来源：http://dali.ybcxt.top/Article/details/gtwaqhfons.html

PHP:  getcwd();
来源：http://dali.hywenlv.cn/Article/details/gtdxtucoho.html

JS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gtdfzfhvdw.html

TS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gthccxdmhb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwsrijlr.html

Go:   os.Getwd()
来源：http://dali.ybcxt.top/Article/details/gtvuyzpacn.html

Ruby: Dir.pwd
来源：http://dali.jianghu66.top/Article/details/gtxvcmfdkf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuetiantiany.cn/Article/details/gtvwasfjld.html

[M05] 设置退出码
来源：http://dali.chenlongwang.top/Article/details/gtdudmngfq.html

Py:   sys.exit(1)
来源：http://dali.yj202588.top/Article/details/gtghhqcvdd.html

PHP:  exit(1);
来源：http://dali.ehwqpu.com/Article/details/gtuzfddcjb.html

JS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtrxyejwxp.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtncdnqeaj.html

Java: System.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtujifvhjn.html

Go:   os.Exit(1)
来源：http://dali.yvedp.cn/Article/details/gttssifhfn.html

Ruby: exit 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbghgdhob.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xinyue.icu/Article/details/gtdxhhekbw.html

[M06] 向标准错误输出
来源：http://dali.jinqigfzy.top/Article/details/gthynqbrzz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gttihpwzof.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yvedp.cn/Article/details/gtdgpkbayb.html

JS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gtpsznsjwm.html

TS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gtuyniudro.html

Java: System.err.println("err")
来源：http://dali.ehwqpu.com/Article/details/gtgelhzixx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pycfn.com/Article/details/gtdxralkjs.html

Ruby: warn "err"
来源：http://dali.yuanzhike.top/Article/details/gtfheadwps.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ydzc1.top/Article/details/gtieltnhnn.html

[M07] 判断是否为主入口
来源：http://dali.jiagoushi.top/Article/details/gttqzodgjx.html

Py:   if __name__ == "__main__":
来源：http://dali.bjfxy.top/Article/details/gtjmzrjeyq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hammf.cn/Article/details/gtilwtwpwo.html

JS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gtkxicygex.html

TS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gthoudfazj.html

Java: public static void main(String[] args)
来源：http://dali.xziqi.cn/Article/details/gtygtmtzsz.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gtevjwnfsw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cashguo.top/Article/details/gtqscqxpdg.html

C#:   static void Main(string[] args)
来源：http://dali.gzhubu.top/Article/details/gtifgctwtr.html

[M08] 获取系统与运行时信息
来源：http://dali.tian-w.cn/Article/details/gtyyyhrsya.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jyoumei.cn/Article/details/gtxpsbuhxj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guowangkeji.top/Article/details/gtrtnmsiqp.html

JS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gtxkcmdfxn.html

TS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gtrlvhcdtp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aizwys.cn/Article/details/gtagnysdjj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gotoacloud.top/Article/details/gtxnhyrzts.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daxiang520.top/Article/details/gthsplvcnz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258888.top/Article/details/gtktaprvye.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtyzlyswct.html

N. 数据结构与算法
来源：http://dali.yj202588.top/Article/details/gtzsxcgtbv.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtrprqdncx.html

[N01] 二分查找（有序数组）
来源：http://dali.hnxiangtu.top/Article/details/gtmdlssiig.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtqwzpoxvx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nwbrower.top/Article/details/gtihewmmei.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gtyeuzibzp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gtrrtldhac.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtrxxmmcmq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtaizmfowy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.feifeiyinyue.top/Article/details/gtbzhqwjbk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtiokulmpx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinghuilouyu.cn/Article/details/gtamkxcwti.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gtueskpjjt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuxming.cn/Article/details/gtjodlngyf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gtseblkbsl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtauhfnwlf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daxiang520.top/Article/details/gtasodiumb.html

Go:   slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gtqohnplqt.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrukazfm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dashuyun.cn/Article/details/gtfnaxohht.html

[N03] 快速排序（分治示例）
来源：http://dali.gogol.net.cn/Article/details/gtyonylfnb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tanke756.top/Article/details/gtwwgwcejl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258.top/Article/details/gtjpcyquxm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.quarkkingdee.top/Article/details/gtuzgqedvx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cashguo.top/Article/details/gtkvtwkkhr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhixingplan.top/Article/details/gtnmuzrzgp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gthowhiddg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jqgufenzy.top/Article/details/gtnhdzaxrf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cdnleiting.top/Article/details/gtgjqivevq.html

[N04] 斐波那契数列
来源：http://dali.gzhubu.top/Article/details/gtekiqhoik.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccycphmj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gtvcgbvpwy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtcnaenhha.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtossaopuc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnqzz.top/Article/details/gtatqtesui.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sufxvd.cn/Article/details/gtpljlwsys.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtuybmkmab.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gtsztmrzwj.html

[N05] 最大公约数
来源：http://dali.shuidangran.top/Article/details/gtwsbxfhhk.html

Py:   math.gcd(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtbzmsiusr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhongyouzk.top/Article/details/gtzjozgiok.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtcaitsujx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gtjssiifrq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.9152youxi.cn/Article/details/gtgumbucsu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guannengcc.top/Article/details/gtbxpnzlyu.html

Ruby: a.gcd(b)
来源：http://dali.smart0.xyz/Article/details/gtwdhulmki.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhwwecok.html

[N06] 判断回文字符串
来源：http://dali.cucudq.cn/Article/details/gtxojwxmff.html

Py:   s == s[::-1]
来源：http://dali.wangdashe.top/Article/details/gtzzdnyqic.html

PHP:  $s === strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gtctmnyvgb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtufahigom.html

TS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtxtimjdhx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aibaodan.cn/Article/details/gtprgrmdcc.html

Go:   // 双指针从两端比较
来源：http://dali.hongshengwenyu.top/Article/details/gteqcpjjoa.html

Ruby: s == s.reverse
来源：http://dali.hywenlv.cn/Article/details/gtihtwgsbh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigufen.top/Article/details/gtzzhcxspc.html

[N07] 两数之和（返回下标）
来源：http://dali.hammf.cn/Article/details/gtshnddpkx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guowangkeji.top/Article/details/gtfrdthwvn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fzhhl.top/Article/details/gtcwluzcep.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.vqdsnc.cn/Article/details/gtxuixbzxk.html

TS:   // 手写 Map<string, number>
来源：http://dali.ydzc1.top/Article/details/gtuaksaoze.html

Java: // 手写 HashMap
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbblgwjt.html

Go:   // 手写 map[int]int
来源：http://dali.dashuyun.cn/Article/details/gtxedkocwy.html

Ruby: // 手写 Hash
来源：http://dali.jqgufenzy.top/Article/details/gtxagpqeln.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.birdmap.top/Article/details/gtwdqhkoaz.html

[N08] 生成全排列
来源：http://dali.316326.xyz/Article/details/gtmcuqvimb.html

Py:   itertools.permutations(arr)
来源：http://dali.gzhubu.top/Article/details/gtqhlkgcxj.html

PHP:  // 手写递归交换
来源：http://dali.sxryk.cn/Article/details/gtrykbgbku.html

JS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtmevttdmq.html

TS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtrtwwwzwe.html

Java: // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtyadxcjva.html

Go:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtcbsuvksl.html

Ruby: arr.permutation.to_a
来源：http://dali.0kj1m.cn/Article/details/gthvpbbejo.html

C#:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtrynjjjsc.html

[N09] 栈与队列
来源：http://dali.shzxlz.cn/Article/details/gtkejeylwj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daxiang520.top/Article/details/gtrnsybqzn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gtstqiigai.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gtasozkdlf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.c1oappe.top/Article/details/gtyijvyppr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cdnleiting.top/Article/details/gtotoaauxf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenzaomai.com/Article/details/gtsadfbbay.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gtmybvrkdt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yanxiufei.cn/Article/details/gtvuxrwmtd.html

[N10] 链表节点定义
来源：http://dali.vqdsnc.cn/Article/details/gthsuzqlfx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nanxinkj.top/Article/details/gthlwyxvze.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zycfv.cn/Article/details/gtqjlecypq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenzaomai.com/Article/details/gtlbrloxdh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gzhubu.top/Article/details/gtpohcnmmg.html

Java: class Node { int v; Node next; }
来源：http://dali.snrcjt.cn/Article/details/gtusnflhgt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yonumen.top/Article/details/gtsduwnwfo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guowangkeji.top/Article/details/gtxcwlxqce.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ppjwa.cn/Article/details/gtpmlerpct.html

[N11] 二叉树中序遍历
来源：http://dali.xinyue.icu/Article/details/gtuokdbzvd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hammf.cn/Article/details/gttjwrgjpz.html

PHP:  // 手写递归函数
来源：http://dali.jlsjyb.cn/Article/details/gtdqzzhghp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gtblneasix.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gtgnsvyruv.html

Java: // 手写递归
来源：http://dali.bjfxy.top/Article/details/gttogmvzbg.html

Go:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtblsryuzq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fzhhl.top/Article/details/gtavvyilqd.html

C#:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtjaifhpnk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgfzy.top/Article/details/gtwmrivqun.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yangfankeji.com/Article/details/gtqtucwgrg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ivvv.top/Article/details/gtmgzbeetl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gteyikaxcz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gtvsnkqzkr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gtuuuhookl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dashuyun.cn/Article/details/gtfxksmwfl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gtjechefjc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ydzc1.top/Article/details/gtjqakjfgl.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmxtlzgx.html

O. 并发与异步
来源：http://dali.fengsongda.top/Article/details/gtaatqbzij.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtpnngxztn.html

[O01] 启动一个线程
来源：http://dali.tanke756.top/Article/details/gtaqgycakh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ehwqpu.com/Article/details/gtjnoxkohp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.vqdsnc.cn/Article/details/gtmbirlvtt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.aibaodan.cn/Article/details/gtiesjynis.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gtgdyehmrr.html

Java: new Thread(() -> f()).start()
来源：http://dali.hysaishi.cn/Article/details/gtbnupespg.html

Go:   go f()
来源：http://dali.chenjidiqi.icu/Article/details/gtdylmtsuf.html

Ruby: Thread.new { f }
来源：http://dali.gotoacloud.top/Article/details/gtnatfydaw.html

C#:   Task.Run(() => F());
来源：http://dali.feifeiyinyue.top/Article/details/gtyatyrcdf.html

[O02] 使用线程池
来源：http://dali.daxiang520.top/Article/details/gtdcodxcri.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guowangkeji.top/Article/details/gtkzbvkwld.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.pycfn.com/Article/details/gtftosjofx.html

JS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gtqcdahpfn.html

TS:   // worker_threads 线程池
来源：http://dali.jianghu66.top/Article/details/gtmtuwijdt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ivvv.top/Article/details/gteifnpwds.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.iojbl.cn/Article/details/gtaddojske.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tian-w.cn/Article/details/gtcbkyudix.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ydzc1.top/Article/details/gtbemojwvm.html

[O03] 加锁保护共享数据
来源：http://dali.shuidangran.top/Article/details/gtfyxtofga.html

Py:   with lock: shared += 1
来源：http://dali.vqdsnc.cn/Article/details/gtnpvupgau.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jyoumei.cn/Article/details/gtcddmyhtv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.iojbl.cn/Article/details/gttegcllrr.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gtrqsrwmih.html

Java: synchronized (this) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gtsegkcaov.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cheryme.top/Article/details/gtnnaagsrp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gogol.net.cn/Article/details/gtueqvnfbt.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gtprhghpms.html

[O04] 定义异步函数并等待
来源：http://dali.feifeiyinyue.top/Article/details/gtyjkeqmbj.html

Py:   async def f():⏎    await g()
来源：http://dali.yvedp.cn/Article/details/gtolbczxjq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.mhx1999.top/Article/details/gtcfjoeqvb.html

JS:   async function f() { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtybzbnd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gtiegroeih.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hysaishi.cn/Article/details/gtpdzlwjwb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dashuyun.cn/Article/details/gtafdzorze.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgfzy.top/Article/details/gtrfmpqakn.html

C#:   async Task F() { await G(); }
来源：http://dali.iojbl.cn/Article/details/gtksgrmhbd.html

[O05] 并发执行并等待全部完成
来源：http://dali.pengpengdd.cyou/Article/details/gtmmvlecxv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xylfe.cn/Article/details/gtlxcillbd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sxryk.cn/Article/details/gtktafqrxg.html

JS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbcnwmuvc.html

TS:   await Promise.all(tasks)
来源：http://dali.redwolf501.top/Article/details/gtjririwxl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gtlapgnkhc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sufxvd.cn/Article/details/gtfpmcnuwt.html

Ruby: threads.map(&:join)
来源：http://dali.xylfe.cn/Article/details/gtuhgqywaj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nanxinkj.top/Article/details/gtngezedzd.html

[O06] 使用进程池
来源：http://dali.kuanghao11.cn/Article/details/gtqbchjrpo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tian-w.cn/Article/details/gtbpjqrlar.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuanzhike.top/Article/details/gtecjxsinj.html

JS:   // child_process / cluster 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfjjocab.html

TS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gtdbhyvxmb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yanxiufei.cn/Article/details/gtoboqpgui.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.guannengcc.top/Article/details/gtelviqsxt.html

Ruby: // fork 块
来源：http://dali.yuxming.cn/Article/details/gtftbqgaso.html

C#:   Parallel.For
来源：http://dali.shuidangran.top/Article/details/gtzqyevjxh.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtusttnusl.html

P. 常用工具函数
来源：http://dali.meibo888.top/Article/details/gtjugezejv.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtauzkhpur.html

[P01] 生成 UUID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnitmgyrv.html

Py:   str(uuid.uuid4())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinlixmdn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cucudq.cn/Article/details/gtfkueetmj.html

JS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gtwzeffurl.html

TS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtyhlehuqk.html

Java: UUID.randomUUID().toString()
来源：http://dali.cdnleiting.top/Article/details/gttxfprdva.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ydzc1.top/Article/details/gtlobfblcr.html

Ruby: SecureRandom.uuid
来源：http://dali.ivvv.top/Article/details/gtfpwjjlrn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yonumen.top/Article/details/gtqnpotauf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.havefunace.top/Article/details/gtxkopxjou.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.havefunace.top/Article/details/gturcrhwkj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtnrndkwzo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jqgufenzy.top/Article/details/gtgzdtkiav.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ppjwa.cn/Article/details/gtsdbzeapo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.mhx1999.top/Article/details/gtltydpgqd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.smart0.xyz/Article/details/gtbimvagub.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fengsongda.top/Article/details/gtvhqntops.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yongpay.top/Article/details/gtikugovuj.html

[P03] 生成短随机字符串
来源：http://dali.hammf.cn/Article/details/gtameiwgil.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gaohongyu789.top/Article/details/gtlzousxrt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ybcxt.top/Article/details/gtjuguxuey.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gtxvzohent.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ppjwa.cn/Article/details/gtayvnfshw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xziqi.cn/Article/details/gtevjnunqx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zycfv.cn/Article/details/gtgxzdeqdo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ydzc1.top/Article/details/gtzpwcajgj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sxryk.cn/Article/details/gtulsuivax.html

[P04] 求长度
来源：http://dali.jinqigfzy.top/Article/details/gteifbwztx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hnqzz.top/Article/details/gtvzwsvasw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtvwjwgdgp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zycfv.cn/Article/details/gtnmlrbsbw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sufxvd.cn/Article/details/gtcmoeqoix.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xziqi.cn/Article/details/gtdiuosbow.html

Go:   len(arr);  len(m)
来源：http://dali.jiagoushi.top/Article/details/gtsrpqfwyu.html

Ruby: x.length;  x.size
来源：http://dali.iojbl.cn/Article/details/gtdaxxabkr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ehwqpu.com/Article/details/gtdlsuhwne.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nwbrower.top/Article/details/gtttlfhfzg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.wangshuangyany.cn/Article/details/gtioppkpzi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shangyingyoupin.top/Article/details/gttsxpwpwr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.0kj1m.cn/Article/details/gttmtycshh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.9152youxi.cn/Article/details/gtvaaiezmi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fzhhl.top/Article/details/gtzzydfiql.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.daria6918.cn/Article/details/gttouqrdtv.html

Ruby: a == b
来源：http://dali.jqgfzy.top/Article/details/gtccdzcfcw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenjidiqi.icu/Article/details/gtsmauyexk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zdqjudy.top/Article/details/gtcibxybmr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.havefunace.top/Article/details/gtlmjnboru.html

PHP:  if (empty($x)) {}
来源：http://dali.xinyue.icu/Article/details/gtwocdbioo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinqigufen.top/Article/details/gtacbbsfug.html

TS:   if (x == null) {}
来源：http://dali.dashuyun.cn/Article/details/gtliuzeyrb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gthjhidngt.html

Go:   if x == nil {}
来源：http://dali.yuxming.cn/Article/details/gttxpssmcu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj202588.top/Article/details/gttdeyqcpv.html

C#:   if (x is null) {}
来源：http://dali.svipenyu.cn/Article/details/gtahjwpjvj.html

[P07] 防抖与节流
来源：http://dali.hongshengwenyu.top/Article/details/gtcfjwqfgv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.birdmap.top/Article/details/gtgvuimawu.html

PHP:  // 手写时间戳比较
来源：http://dali.smart0.xyz/Article/details/gtcfxznnse.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuxming.cn/Article/details/gtnwygzdku.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gtzjvoboxf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgufenzy.top/Article/details/gtqjfqhslw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.wangdashe.top/Article/details/gtbysnzzom.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.mhx1999.top/Article/details/gtpghyvctg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzsxuenx.html

[P08] 处理浮点精度问题
来源：http://dali.ybcxt.top/Article/details/gtrbultedl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jyoumei.cn/Article/details/gtwptcalmk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.quarkkingdee.top/Article/details/gttddgsapy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pengpengdd.cyou/Article/details/gtapczwasy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.vqdsnc.cn/Article/details/gtaxstbzjl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hywenlv.cn/Article/details/gtxaojvxju.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.guannengcc.top/Article/details/gtckbhymhd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.snrcjt.cn/Article/details/gtzeetfaqm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhiwuduotai.top/Article/details/gtuteizeca.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtftqdmdmc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.andypj.xyz/Article/details/gtgouiliue.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtxnnkaioi.html

[Q01] 创建表
来源：http://dali.xuanzx.com/Article/details/gtskpxrlvl.html

CREATE TABLE users (
来源：http://dali.havefunace.top/Article/details/gtaexnexqx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gtqwazobpq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gtzioaaaht.html

email VARCHAR(100) UNIQUE,
来源：http://dali.feifeiyinyue.top/Article/details/gtjcyzkiyw.html


<!-- 参考信息 -->