代发 wailian999

TS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gtaxvnkftv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daria6918.cn/Article/details/gtghomvvxv.html

Go:   os.Getwd()
来源：http://dali.xylfe.cn/Article/details/gtiysfbeax.html

Ruby: Dir.pwd
来源：http://dali.hfpthk.cn/Article/details/gtgnhvbujg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuxming.cn/Article/details/gtbptytzfm.html

[M05] 设置退出码
来源：http://dali.gogol.net.cn/Article/details/gtznsfyray.html

Py:   sys.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtczksznka.html

PHP:  exit(1);
来源：http://dali.dianchejie.cn/Article/details/gtmcqkwadi.html

JS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtudhbqzum.html

TS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtngeikizm.html

Java: System.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtmdgbqryf.html

Go:   os.Exit(1)
来源：http://dali.yueranfly.top/Article/details/gtjgxxrymp.html

Ruby: exit 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzifttmr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daxiang520.top/Article/details/gtdrbccsez.html

[M06] 向标准错误输出
来源：http://dali.pengpengdd.cyou/Article/details/gtxyhopvjr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gtyyfwsuat.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yueranfly.top/Article/details/gtpfenxnup.html

JS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gtbmyykofv.html

TS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gtnkdlddnh.html

Java: System.err.println("err")
来源：http://dali.jyoumei.cn/Article/details/gtjhrdydkh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ivvv.top/Article/details/gttzirylei.html

Ruby: warn "err"
来源：http://dali.hfpthk.cn/Article/details/gtzcallkkc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sxryk.cn/Article/details/gtmvhyphvd.html

[M07] 判断是否为主入口
来源：http://dali.jinqigufen.top/Article/details/gtcfjaqnyy.html

Py:   if __name__ == "__main__":
来源：http://dali.sxryk.cn/Article/details/gtosbmrjnm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj202588.top/Article/details/gtfakpxprt.html

JS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gtoersewdo.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gtexxflybr.html

Java: public static void main(String[] args)
来源：http://dali.sxryk.cn/Article/details/gtjamkjtdi.html

Go:   func main()
来源：http://dali.haohaochexian.top/Article/details/gtbqbgfqpp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj20258888.top/Article/details/gtdtqhffoe.html

C#:   static void Main(string[] args)
来源：http://dali.zycfv.cn/Article/details/gtfcxaotbx.html

[M08] 获取系统与运行时信息
来源：http://dali.yangfankeji.com/Article/details/gtglqywgqw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ehwqpu.com/Article/details/gtqzijklsp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ppjwa.cn/Article/details/gtflaqosbs.html

JS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gtpmbswkhh.html

TS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gtabjdavpu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhiwuduotai.top/Article/details/gtmntdwkdq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shzxlz.cn/Article/details/gtzgesnnzl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xuetiantiany.cn/Article/details/gtftvlabbj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tian-w.cn/Article/details/gtoshwicly.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtwfmcduxi.html

N. 数据结构与算法
来源：http://dali.gogol.net.cn/Article/details/gthkqgoepw.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtwszydkyf.html

[N01] 二分查找（有序数组）
来源：http://dali.tianlin.xyz/Article/details/gtetfmquub.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtvhxhnqdp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtdshasznr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gtgngmsiif.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gtqsgkmocm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtwndbsczm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtsosghcoe.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yueranfly.top/Article/details/gttkrejedv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtfrfirjmn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhoulong.xyz/Article/details/gtpephyqof.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqbaxgee.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtzzasxnlb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gtdpmmuzhz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gtnhccvhjh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.redwolf501.top/Article/details/gthackocql.html

Go:   slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtzksgnlxq.html

Ruby: arr.sort
来源：http://dali.bjfxy.top/Article/details/gtijcoglnf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.0kj1m.cn/Article/details/gtoskzqtxa.html

[N03] 快速排序（分治示例）
来源：http://dali.hnxiangtu.top/Article/details/gtzzmqbjue.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258888.top/Article/details/gtuhdxdrqv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenzaomai.com/Article/details/gtzscoptsm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gtpjzpqdvs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gtchfylwen.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sysykeji.top/Article/details/gtckzvnish.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj202588.top/Article/details/gtfrwejroh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yanxiufei.cn/Article/details/gtpxkrvapj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigufen.top/Article/details/gtprnnoltj.html

[N04] 斐波那契数列
来源：http://dali.pengpengdd.cyou/Article/details/gtfvjmagvq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gtkztrnxmo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj202588.top/Article/details/gtlyqkaqii.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gtdqwwlqgr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtgnbmwelh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gttqsvkjre.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuetiantiany.cn/Article/details/gtpyetyxty.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gtrnkscbcr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gtbdhiiyai.html

[N05] 最大公约数
来源：http://dali.pengpengdd.cyou/Article/details/gtvmdtznjq.html

Py:   math.gcd(a, b)
来源：http://dali.cashguo.top/Article/details/gtrppdogjq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guowangkeji.top/Article/details/gtdgxkwzkw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gtwwidklgn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ppjwa.cn/Article/details/gtptmmbbnv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.snrcjt.cn/Article/details/gtelvghnpb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.mhx1999.top/Article/details/gtrwojsjbq.html

Ruby: a.gcd(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqncdnhva.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yonumen.top/Article/details/gtnsxqkdco.html

[N06] 判断回文字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwolpigfk.html

Py:   s == s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gtzdesljne.html

PHP:  $s === strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gtmdacgbwd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtzbdysytu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtcnmfvzod.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hysaishi.cn/Article/details/gtnyizwgsl.html

Go:   // 双指针从两端比较
来源：http://dali.xinyue.icu/Article/details/gtcampgphh.html

Ruby: s == s.reverse
来源：http://dali.nwbrower.top/Article/details/gtyppcrdlf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daria6918.cn/Article/details/gtmhnkdupl.html

[N07] 两数之和（返回下标）
来源：http://dali.hnqzz.top/Article/details/gtrzojagcj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gtkoqnefzs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ppjwa.cn/Article/details/gtuiaqdmyn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.316326.xyz/Article/details/gtebjopgca.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangshuangyany.cn/Article/details/gtfbagxtek.html

Java: // 手写 HashMap
来源：http://dali.316326.xyz/Article/details/gtjpapxufa.html

Go:   // 手写 map[int]int
来源：http://dali.yvedp.cn/Article/details/gtvnuwccso.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcciksgu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hysaishi.cn/Article/details/gtsgpvzsqg.html

[N08] 生成全排列
来源：http://dali.cdnleiting.top/Article/details/gtlzrqhmny.html

Py:   itertools.permutations(arr)
来源：http://dali.sxryk.cn/Article/details/gthmpbzolz.html

PHP:  // 手写递归交换
来源：http://dali.sxryk.cn/Article/details/gtqzgjysoo.html

JS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtuydzllhr.html

TS:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gthbevvghq.html

Java: // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gttnzfdzng.html

Go:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtrtrbxhef.html

Ruby: arr.permutation.to_a
来源：http://dali.dashuyun.cn/Article/details/gtlecghnlh.html

C#:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtztxptxpt.html

[N09] 栈与队列
来源：http://dali.shangyingyoupin.top/Article/details/gtoehwxhhx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gzhubu.top/Article/details/gtatanwnss.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtvfvjuyqk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gttyvibbqb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.andypj.xyz/Article/details/gthfwehxrf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gtshabjhdt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yangfankeji.com/Article/details/gteqkqyjky.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtqqldhval.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jlsjyb.cn/Article/details/gtpmfbkuwz.html

[N10] 链表节点定义
来源：http://dali.havefunace.top/Article/details/gtznhwdwic.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtjlvhtl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gotoacloud.top/Article/details/gtwtgnqchd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqqorqhy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xziqi.cn/Article/details/gtbrjhvefm.html

Java: class Node { int v; Node next; }
来源：http://dali.cucudq.cn/Article/details/gtwwzjcrtz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenjidiqi.icu/Article/details/gtqurvnoxa.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gaohongyu789.top/Article/details/gtvmllkknl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cheryme.top/Article/details/gtncbbxrgs.html

[N11] 二叉树中序遍历
来源：http://dali.9152youxi.cn/Article/details/gtnkyrbcjk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ehwqpu.com/Article/details/gtdljwlsye.html

PHP:  // 手写递归函数
来源：http://dali.birdmap.top/Article/details/gtddckgzny.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhoulong.xyz/Article/details/gtjzpsulxz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gtnyhiinwg.html

Java: // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gtvmtodfjf.html

Go:   // 手写递归
来源：http://dali.nwbrower.top/Article/details/gtifzfftue.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.birdmap.top/Article/details/gtmqlwsoix.html

C#:   // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtsaidexny.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.pengpengdd.cyou/Article/details/gtcqlifxdq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.redwolf501.top/Article/details/gtatmpldej.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cucudq.cn/Article/details/gthmtdyzrz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gtgdulsjvp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gtlrwbyzag.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gtlvaykdkq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.redwolf501.top/Article/details/gtfqkkjxje.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.havefunace.top/Article/details/gteajcnhkp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenzaomai.com/Article/details/gtpfpxixri.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtcrqhgtwn.html

O. 并发与异步
来源：http://dali.jianghu66.top/Article/details/gttuqvximt.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtywpzzyqi.html

[O01] 启动一个线程
来源：http://dali.nanxinkj.top/Article/details/gtykgudqun.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xziqi.cn/Article/details/gtnkpxgnvb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gaohongyu789.top/Article/details/gtnpxlbqaw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258.top/Article/details/gtafdizdhj.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gtuznaiuvt.html

Java: new Thread(() -> f()).start()
来源：http://dali.hywenlv.cn/Article/details/gtohahhppm.html

Go:   go f()
来源：http://dali.dianchejie.cn/Article/details/gtxtoxhbgu.html

Ruby: Thread.new { f }
来源：http://dali.zhengqikj.top/Article/details/gtqxgviwkr.html

C#:   Task.Run(() => F());
来源：http://dali.yj202588.top/Article/details/gtuavjwcfw.html

[O02] 使用线程池
来源：http://dali.yanxiufei.cn/Article/details/gtnxjjcfrx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sufxvd.cn/Article/details/gtzwkdwrex.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.mhx1999.top/Article/details/gtyadinbpy.html

JS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtdguomwsz.html

TS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gtrvouqnwr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jlsjyb.cn/Article/details/gtfdgzetsk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gogol.net.cn/Article/details/gthconvlsx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenlongwang.top/Article/details/gtaujbkcgw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkznirmq.html

[O03] 加锁保护共享数据
来源：http://dali.aibaodan.cn/Article/details/gtznnxwurc.html

Py:   with lock: shared += 1
来源：http://dali.yongpay.top/Article/details/gtyeqxxdmg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xziqi.cn/Article/details/gtfsdyxzqf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gogol.net.cn/Article/details/gtnlevzrub.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gtzocnzwxs.html

Java: synchronized (this) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gtlbvmllqx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cucudq.cn/Article/details/gtvevohugt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gtxxgoltaf.html

C#:   lock (gate) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjlsuuyku.html

[O04] 定义异步函数并等待
来源：http://dali.yueranfly.top/Article/details/gtewgcmuqs.html

Py:   async def f():⏎    await g()
来源：http://dali.aizwys.cn/Article/details/gtnewefcqb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.svipenyu.cn/Article/details/gtdlvirvyy.html

JS:   async function f() { await g(); }
来源：http://dali.yuxming.cn/Article/details/gtncwqhqwz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gttvaccpzc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ehwqpu.com/Article/details/gtrroctdmi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhixingplan.top/Article/details/gtzrjeclge.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigufen.top/Article/details/gtzmtmolsz.html

C#:   async Task F() { await G(); }
来源：http://dali.sysykeji.top/Article/details/gtblwgfmxt.html

[O05] 并发执行并等待全部完成
来源：http://dali.daria6918.cn/Article/details/gtzgsfedxs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.aibaodan.cn/Article/details/gtvcrgzmxq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fengsongda.top/Article/details/gthgscrtvw.html

JS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gtekdklkfr.html

TS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gtbtjoeoub.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cashguo.top/Article/details/gtgkrovews.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ivvv.top/Article/details/gtajeegaca.html

Ruby: threads.map(&:join)
来源：http://dali.mhx1999.top/Article/details/gtqogagpbs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zycfv.cn/Article/details/gtdhhexkyc.html

[O06] 使用进程池
来源：http://dali.sufxvd.cn/Article/details/gttsceeaii.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gaohongyu789.top/Article/details/gtjbcfkych.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhixingplan.top/Article/details/gtnindseaj.html

JS:   // child_process / cluster 模块
来源：http://dali.ydzc1.top/Article/details/gtnvpvqqso.html

TS:   // child_process / cluster 模块
来源：http://dali.birdmap.top/Article/details/gtsfytgmik.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.quarkkingdee.top/Article/details/gthbwflzok.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yueranfly.top/Article/details/gtniyilcay.html

Ruby: // fork 块
来源：http://dali.jqgufenzy.top/Article/details/gtuuokenci.html

C#:   Parallel.For
来源：http://dali.tanke756.top/Article/details/gtmpdwfmyd.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtgtqaugkm.html

P. 常用工具函数
来源：http://dali.andypj.xyz/Article/details/gtsozvjgzc.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxqwklnk.html

[P01] 生成 UUID
来源：http://dali.xylfe.cn/Article/details/gthshyjxah.html

Py:   str(uuid.uuid4())
来源：http://dali.hnqzz.top/Article/details/gtdiyatigi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yanxiufei.cn/Article/details/gtqohxfome.html

JS:   crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gtafjmbznm.html

TS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqmowdgy.html

Java: UUID.randomUUID().toString()
来源：http://dali.tianlin.xyz/Article/details/gthdhcyujw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj202588.top/Article/details/gtlqpxginn.html

Ruby: SecureRandom.uuid
来源：http://dali.shuidangran.top/Article/details/gtivzqkxov.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yanxiufei.cn/Article/details/gtyigzwyhp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xuetiantiany.cn/Article/details/gtxtrzfrey.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhoulong.xyz/Article/details/gtvyuoiuvt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cqqwz.cn/Article/details/gtrikrqvun.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yongpay.top/Article/details/gtfkszybru.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yvedp.cn/Article/details/gtbzpyuwnz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtslrsbzpt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigfzy.top/Article/details/gtnarjlyhj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yongpay.top/Article/details/gtrctmuylj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ppjwa.cn/Article/details/gthbyofiry.html

[P03] 生成短随机字符串
来源：http://dali.yangfankeji.com/Article/details/gtlemguqpw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.aizwys.cn/Article/details/gtvgrzdfvh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jianghu66.top/Article/details/gtcmfhftoz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yongpay.top/Article/details/gtjmpqcdco.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxuckzubu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xziqi.cn/Article/details/gtvualhyeu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258.top/Article/details/gtxfwgfilj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xinyue.icu/Article/details/gtsyzooicr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aizwys.cn/Article/details/gtpfpckzen.html

[P04] 求长度
来源：http://dali.yvedp.cn/Article/details/gtuhlzyfsc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sxryk.cn/Article/details/gtbnwfikuz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtmkfkpfvu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cashguo.top/Article/details/gttgdowqrm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gtoqzzftlp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.haohaochexian.top/Article/details/gtncyjtuvm.html

Go:   len(arr);  len(m)
来源：http://dali.jyoumei.cn/Article/details/gtvrzwbsix.html

Ruby: x.length;  x.size
来源：http://dali.yongpay.top/Article/details/gtphhemhpg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.snrcjt.cn/Article/details/gtgashdync.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dianchejie.cn/Article/details/gttmnyvjrr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hnqzz.top/Article/details/gtypzqhuix.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xuanzx.com/Article/details/gtzmaeoysy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fengsongda.top/Article/details/gtnqwzwvva.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.vqdsnc.cn/Article/details/gthrgbfrpv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zycfv.cn/Article/details/gtvvveorby.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtmgwvjyje.html

Ruby: a == b
来源：http://dali.yanxiufei.cn/Article/details/gtsfhnprpz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xylfe.cn/Article/details/gttxetyead.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tianlin.xyz/Article/details/gtwtvxqjkv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fengsongda.top/Article/details/gtlhvneiot.html

PHP:  if (empty($x)) {}
来源：http://dali.kuanghao11.cn/Article/details/gtycynepbu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ybcxt.top/Article/details/gtlxnruier.html

TS:   if (x == null) {}
来源：http://dali.jqgfzy.top/Article/details/gtgurmdmuv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gtuyxhbdmb.html

Go:   if x == nil {}
来源：http://dali.zdqjudy.top/Article/details/gtontqnwff.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenlongwang.top/Article/details/gtybjfajnn.html

C#:   if (x is null) {}
来源：http://dali.cucudq.cn/Article/details/gtsdadtzjn.html

[P07] 防抖与节流
来源：http://dali.hfpthk.cn/Article/details/gtqwyrpsie.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj202588.top/Article/details/gtpzmbzeva.html

PHP:  // 手写时间戳比较
来源：http://dali.xuanzx.com/Article/details/gtkuvvwagm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixpxhfxj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gtcktkxxjx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sxryk.cn/Article/details/gtjyjubvug.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.haohaochexian.top/Article/details/gtpvokituh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dianchejie.cn/Article/details/gthexcwhei.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jianghu66.top/Article/details/gtjpmleafy.html

[P08] 处理浮点精度问题
来源：http://dali.aizwys.cn/Article/details/gtplmnhggm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.9152youxi.cn/Article/details/gtnilbtgew.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.kuanghao11.cn/Article/details/gtocvfdxmv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ppjwa.cn/Article/details/gtkksyzevn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgufenzy.top/Article/details/gtsawhwvrv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhixingplan.top/Article/details/gtngxywgtm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigufen.top/Article/details/gtlnafzymz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ehwqpu.com/Article/details/gtspwyuhaj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.feifeiyinyue.top/Article/details/gtvvnrpwqv.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gthjnpeuqd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zdqjudy.top/Article/details/gtgzyrvxro.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtqhewynqe.html

[Q01] 创建表
来源：http://dali.yj202588.top/Article/details/gtwoamtasv.html

CREATE TABLE users (
来源：http://dali.redwolf501.top/Article/details/gtqouddeai.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ydzc1.top/Article/details/gtcwmygrda.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ppjwa.cn/Article/details/gtuvkplzcg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegutsbwn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nanxinkj.top/Article/details/gtbrgtlald.html

);
来源：http://dali.chenjidiqi.icu/Article/details/gtyngkdhpq.html

[Q02] 创建带外键的表
来源：http://dali.zhiwuduotai.top/Article/details/gtglvosgam.html

CREATE TABLE orders (
来源：http://dali.gogol.net.cn/Article/details/gtpgjnhiau.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gtgcaipvna.html

user_id INT NOT NULL,
来源：http://dali.nanxinkj.top/Article/details/gtaffrfigk.html

amount DECIMAL(10, 2),
来源：http://dali.chenzaomai.com/Article/details/gtzqvdsswr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezybzrtm.html


<!-- 参考信息 -->