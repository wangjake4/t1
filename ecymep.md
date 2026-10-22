代发 wailian999

TS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtrfbumnbv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangdashe.top/Article/details/gtsueeywxd.html

Go:   os.Getwd()
来源：http://dali.guannengcc.top/Article/details/gtfdnnbwft.html

Ruby: Dir.pwd
来源：http://dali.haohaochexian.top/Article/details/gtmsoabkiy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxinkj.top/Article/details/gtepawsdvd.html

[M05] 设置退出码
来源：http://dali.hysaishi.cn/Article/details/gttjedesbo.html

Py:   sys.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtvwcyzqjj.html

PHP:  exit(1);
来源：http://dali.hnqzz.top/Article/details/gtbkxuaqqg.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtkvrmwfgk.html

TS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtnodhcnuu.html

Java: System.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtquvebghn.html

Go:   os.Exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtapcmvckv.html

Ruby: exit 1
来源：http://dali.nanxuanxn.top/Article/details/gttmpjbkks.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigfzy.top/Article/details/gtpifqwkxs.html

[M06] 向标准错误输出
来源：http://dali.daria6918.cn/Article/details/gtcyyohkzd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hammf.cn/Article/details/gtgbtkbvlg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.316326.xyz/Article/details/gttsvnddse.html

JS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gtmisycdcn.html

TS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gtixrapirn.html

Java: System.err.println("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtgiiahcgm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aizwys.cn/Article/details/gtfrbtyrkw.html

Ruby: warn "err"
来源：http://dali.nwbrower.top/Article/details/gtqkaigpgk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258888.top/Article/details/gtdbssqtfr.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gteqnjzhta.html

Py:   if __name__ == "__main__":
来源：http://dali.fzhhl.top/Article/details/gtkbxshqgy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hammf.cn/Article/details/gtvtruswmp.html

JS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gtatplcexd.html

TS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gtrhjpohyv.html

Java: public static void main(String[] args)
来源：http://dali.tianlin.xyz/Article/details/gtljaihhcq.html

Go:   func main()
来源：http://dali.birdmap.top/Article/details/gtuikpnniu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aibaodan.cn/Article/details/gtlvttihzt.html

C#:   static void Main(string[] args)
来源：http://dali.tianlin.xyz/Article/details/gtozfcmypk.html

[M08] 获取系统与运行时信息
来源：http://dali.meibo888.top/Article/details/gtcmfcjrzg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.mhx1999.top/Article/details/gtobqfmkje.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgufenzy.top/Article/details/gtoqatdemw.html

JS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gtqapxsdpy.html

TS:   process.platform;  process.version
来源：http://dali.svipenyu.cn/Article/details/gtwkfjuryp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.svipenyu.cn/Article/details/gtrpnncpck.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gzhubu.top/Article/details/gtmgtfkimf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yongpay.top/Article/details/gtueksotjt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ivvv.top/Article/details/gtsyxtkats.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtqlakrnex.html

N. 数据结构与算法
来源：http://dali.jlsjyb.cn/Article/details/gtsjrwvolc.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gthrvwxukf.html

[N01] 二分查找（有序数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gtubjysrhg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtnmhncssj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtsucbdvgi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gtgdffxmnr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gtbcfzhyli.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gtiqkqhlsq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtpwkqbuoz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhongyouzk.top/Article/details/gtvupaovrn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtnjyczdis.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.quarkkingdee.top/Article/details/gtfaehlfwr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gtydvgnjyv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtthfwrlit.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtcssmjitg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gttiziwyia.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aibaodan.cn/Article/details/gtgugjcidc.html

Go:   slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqfctyme.html

Ruby: arr.sort
来源：http://dali.guannengcc.top/Article/details/gtuyogknlq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cucudq.cn/Article/details/gtyauqrhau.html

[N03] 快速排序（分治示例）
来源：http://dali.nwbrower.top/Article/details/gtbecosgxg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.smart0.xyz/Article/details/gtavcafgqy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.bjfxy.top/Article/details/gtjvtlapok.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gtlnzuwzix.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuirgfjht.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258.top/Article/details/gtofihtsut.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nanxuanxn.top/Article/details/gtkzaumqkx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.andypj.xyz/Article/details/gtfymjcrji.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yvedp.cn/Article/details/gtcrbzdidj.html

[N04] 斐波那契数列
来源：http://dali.zhengqikj.top/Article/details/gtojzvmtst.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtyvegksxs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gtjtfaiaqn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gtuetyxqal.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtgxtbygfn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.c1oappe.top/Article/details/gtwxknkywd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hammf.cn/Article/details/gtppeilequ.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.mhx1999.top/Article/details/gtwbawmyut.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrevzplcl.html

[N05] 最大公约数
来源：http://dali.gzhubu.top/Article/details/gtzcrbugif.html

Py:   math.gcd(a, b)
来源：http://dali.andypj.xyz/Article/details/gtnrlabkhl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehhvqkqe.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gtmkgadmct.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gtgqleuyhi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.mhx1999.top/Article/details/gtzlrnedry.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nwbrower.top/Article/details/gtzpvpgxqy.html

Ruby: a.gcd(b)
来源：http://dali.guowangkeji.top/Article/details/gtkmuqlxym.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgsuosvnf.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgigwsway.html

Py:   s == s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gtvhcaauys.html

PHP:  $s === strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gtlnhwapbu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gtpmgsjkxm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtsxflwilp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.kuanghao11.cn/Article/details/gtacqtwetq.html

Go:   // 双指针从两端比较
来源：http://dali.xuanzx.com/Article/details/gtprgzcbyu.html

Ruby: s == s.reverse
来源：http://dali.yuxming.cn/Article/details/gtuclrqrxt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gttimopdwv.html

[N07] 两数之和（返回下标）
来源：http://dali.chenzaomai.com/Article/details/gtffslhgsa.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zycfv.cn/Article/details/gtxapuhcgn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhixingplan.top/Article/details/gtvtnnzifd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aizwys.cn/Article/details/gtlghgzmck.html

TS:   // 手写 Map<string, number>
来源：http://dali.0kj1m.cn/Article/details/gtthzfdtme.html

Java: // 手写 HashMap
来源：http://dali.shzxlz.cn/Article/details/gtwadqznlt.html

Go:   // 手写 map[int]int
来源：http://dali.yonumen.top/Article/details/gtgwqfwxsh.html

Ruby: // 手写 Hash
来源：http://dali.sxryk.cn/Article/details/gtyuqagjch.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hysaishi.cn/Article/details/gtsxlrhyjh.html

[N08] 生成全排列
来源：http://dali.aibaodan.cn/Article/details/gtdfnpmmcp.html

Py:   itertools.permutations(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtrcrsxzyx.html

PHP:  // 手写递归交换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstehdsbo.html

JS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtvegjfiwo.html

TS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtaoffysfh.html

Java: // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtnxxbctlv.html

Go:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gthuqahqiv.html

Ruby: arr.permutation.to_a
来源：http://dali.cashguo.top/Article/details/gtppnqixhq.html

C#:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtfxvzlaoc.html

[N09] 栈与队列
来源：http://dali.c1oappe.top/Article/details/gtsvcbnyul.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jianghu66.top/Article/details/gttfbsvbal.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gtrwlduyve.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtmndpqigk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ehwqpu.com/Article/details/gtzmkyzkok.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shzxlz.cn/Article/details/gtcnwvshbs.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xylfe.cn/Article/details/gtisbzadsp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gtrlxvsvkl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ydzc1.top/Article/details/gtfzgemiaz.html

[N10] 链表节点定义
来源：http://dali.jqgfzy.top/Article/details/gtwseaxlry.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.kuanghao11.cn/Article/details/gtlnydmejd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jiagoushi.top/Article/details/gtalhzakdx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhengqikj.top/Article/details/gtkjxhjvnw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgfzy.top/Article/details/gtkzpwbqrk.html

Java: class Node { int v; Node next; }
来源：http://dali.dianchejie.cn/Article/details/gtzvygcsin.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.havefunace.top/Article/details/gtrwzrolow.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xuanzx.com/Article/details/gtneafxnez.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sxryk.cn/Article/details/gtwdpecikv.html

[N11] 二叉树中序遍历
来源：http://dali.yvedp.cn/Article/details/gtblougrxv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sweek.top/Article/details/gtwrnhdusv.html

PHP:  // 手写递归函数
来源：http://dali.iojbl.cn/Article/details/gtqexjvyyq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gtpxiylcvb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gtablgeurc.html

Java: // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtgvyrfurm.html

Go:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtxumwmjjl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pycfn.com/Article/details/gtowcfjqou.html

C#:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtwyluwmrl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.guowangkeji.top/Article/details/gtamczvxxo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hywenlv.cn/Article/details/gtngkcztlf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yonumen.top/Article/details/gtukpwoxpr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gtezzsuusc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.snrcjt.cn/Article/details/gtdidkofyw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gtkvmncagr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cheryme.top/Article/details/gtpnidlzof.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.andypj.xyz/Article/details/gtacyqlppv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gtzjwvbjez.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gttivpbkwp.html

O. 并发与异步
来源：http://dali.cqqwz.cn/Article/details/gtkxiirarp.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtyjfmvzkb.html

[O01] 启动一个线程
来源：http://dali.jyoumei.cn/Article/details/gtxgyrysnw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryaewyub.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tianlin.xyz/Article/details/gtyohlgfgz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hywenlv.cn/Article/details/gtjzkwdelx.html

TS:   // 同 JS
来源：http://dali.wangshuangyany.cn/Article/details/gttotjmtqd.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtwzyreo.html

Go:   go f()
来源：http://dali.zdqjudy.top/Article/details/gtclaoktmv.html

Ruby: Thread.new { f }
来源：http://dali.chenjidiqi.icu/Article/details/gttkwoyiys.html

C#:   Task.Run(() => F());
来源：http://dali.guannengcc.top/Article/details/gthhewwgwt.html

[O02] 使用线程池
来源：http://dali.ydzc1.top/Article/details/gtgrucwaru.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangdashe.top/Article/details/gtgldctugt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yanxiufei.cn/Article/details/gtrpdiatar.html

JS:   // worker_threads 线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlypgitxf.html

TS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtfaqynbqm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jyoumei.cn/Article/details/gtnbfazbqq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.birdmap.top/Article/details/gtqpxigwga.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangtech.top/Article/details/gtslhltgym.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.quarkkingdee.top/Article/details/gtrdypbseo.html

[O03] 加锁保护共享数据
来源：http://dali.fengsongda.top/Article/details/gtakdmdunf.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gtarbyhzjn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shanyushiyangtech.top/Article/details/gtoidlwlxb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hysaishi.cn/Article/details/gtipgxvtjq.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gtqclpmigr.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxuanxn.top/Article/details/gtkfanmgns.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xinyue.icu/Article/details/gtsydfxsbh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuetiantiany.cn/Article/details/gtrmumdynv.html

C#:   lock (gate) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gtjxbksooo.html

[O04] 定义异步函数并等待
来源：http://dali.gotoacloud.top/Article/details/gtjufoxnrj.html

Py:   async def f():⏎    await g()
来源：http://dali.ppjwa.cn/Article/details/gtfcdoxkcw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gtfngfsbca.html

JS:   async function f() { await g(); }
来源：http://dali.tian-w.cn/Article/details/gtwyvlngcb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhrirlzy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.meibo888.top/Article/details/gtbtmssjqu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.0kj1m.cn/Article/details/gtedebxevl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.iojbl.cn/Article/details/gtxsywxoyu.html

C#:   async Task F() { await G(); }
来源：http://dali.nanxuanxn.top/Article/details/gtaofwupip.html

[O05] 并发执行并等待全部完成
来源：http://dali.fengsongda.top/Article/details/gtftnapdvx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xinyue.icu/Article/details/gtnjjgmjti.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.kuanghao11.cn/Article/details/gttzroztvp.html

JS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gttplouiwd.html

TS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gtpudoxegu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gotoacloud.top/Article/details/gtuzxmcvqw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gzhubu.top/Article/details/gtjbcboimy.html

Ruby: threads.map(&:join)
来源：http://dali.chenzaomai.com/Article/details/gtryskkwze.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigfzy.top/Article/details/gtefvicyuy.html

[O06] 使用进程池
来源：http://dali.yonumen.top/Article/details/gtfythczto.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yonumen.top/Article/details/gtifhnodcp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nwbrower.top/Article/details/gtjnileyvl.html

JS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gtchfxdrec.html

TS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gtjjlbwyhe.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinqigfzy.top/Article/details/gtnvhyzufx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xinyue.icu/Article/details/gtwguhbypq.html

Ruby: // fork 块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiafwkfxf.html

C#:   Parallel.For
来源：http://dali.tian-w.cn/Article/details/gtjwrghbhq.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtzsurvbsa.html

P. 常用工具函数
来源：http://dali.chenjidiqi.icu/Article/details/gtolgufmhh.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtaoslxvsz.html

[P01] 生成 UUID
来源：http://dali.jianghu66.top/Article/details/gtmfxzazrh.html

Py:   str(uuid.uuid4())
来源：http://dali.cdnleiting.top/Article/details/gtclxzsifc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yuanzhike.top/Article/details/gtmcxobugu.html

JS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtwstznrek.html

TS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gtkytspfau.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgfzy.top/Article/details/gtemklkfet.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yanxiufei.cn/Article/details/gtdmspnoes.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgufenzy.top/Article/details/gtwkupufpv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpuovywg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.havefunace.top/Article/details/gtnfpooqha.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.meibo888.top/Article/details/gtlyelprke.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hywenlv.cn/Article/details/gtuiwazrmf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guannengcc.top/Article/details/gtqvgdfchb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.daria6918.cn/Article/details/gtssklcvkc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkozrtoa.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yongpay.top/Article/details/gtspsjuovv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258.top/Article/details/gtwvzvgoao.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zdqjudy.top/Article/details/gtmiefacqi.html

[P03] 生成短随机字符串
来源：http://dali.shuidangran.top/Article/details/gtrcrgyhwo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuetiantiany.cn/Article/details/gtqtijehzl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aizwys.cn/Article/details/gtpwnudfup.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gtkqczqecm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yueranfly.top/Article/details/gtqoqfezzi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzutmreur.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ivvv.top/Article/details/gtkdenlxkt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.redwolf501.top/Article/details/gtnpkujbga.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yongpay.top/Article/details/gtgcykaisp.html

[P04] 求长度
来源：http://dali.fengsongda.top/Article/details/gtptuzeipv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.feifeiyinyue.top/Article/details/gtujyuooek.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtucmjafov.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gtejyfbvjx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gtkafhdxxm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.fzhhl.top/Article/details/gtcwjzhwfk.html

Go:   len(arr);  len(m)
来源：http://dali.aibaodan.cn/Article/details/gtlnhpwiqk.html

Ruby: x.length;  x.size
来源：http://dali.mhx1999.top/Article/details/gtchgxutvf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shuidangran.top/Article/details/gtnzjbcapt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuanzhike.top/Article/details/gtiiiylbgv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sweek.top/Article/details/gtefaizyyd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinqigfzy.top/Article/details/gtndvgfazz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.havefunace.top/Article/details/gtrpsiayqy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gtodktnpve.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hnqzz.top/Article/details/gtwtxhiygb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gtuzwqnfqx.html

Ruby: a == b
来源：http://dali.jyoumei.cn/Article/details/gtygmruouc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ehwqpu.com/Article/details/gtpbjriuzs.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gogol.net.cn/Article/details/gtaubwvoxq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jlsjyb.cn/Article/details/gtcdzigeam.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258.top/Article/details/gtqslecwnv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpcnfazx.html

TS:   if (x == null) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtomdrulpw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gtoehysgcl.html

Go:   if x == nil {}
来源：http://dali.cdnleiting.top/Article/details/gtirxtpfub.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyqioglu.html

C#:   if (x is null) {}
来源：http://dali.cheryme.top/Article/details/gtknmmwhot.html

[P07] 防抖与节流
来源：http://dali.tanke756.top/Article/details/gtyojcpkrs.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.mhx1999.top/Article/details/gtanqwshgl.html

PHP:  // 手写时间戳比较
来源：http://dali.aizwys.cn/Article/details/gtsxgoaleu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gtkguirefy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gtuloaxmwi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shzxlz.cn/Article/details/gtfldpfjxc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj202588.top/Article/details/gtzyvexmkv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sweek.top/Article/details/gthzduwsei.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.dashuyun.cn/Article/details/gtwjhlliqc.html

[P08] 处理浮点精度问题
来源：http://dali.xuanzx.com/Article/details/gtlrmnxxhx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jyoumei.cn/Article/details/gtbybybjbc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gthaquhzqi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtqvoqpu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dianchejie.cn/Article/details/gtevcnieno.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258888.top/Article/details/gtbwdwcvje.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shzxlz.cn/Article/details/gtzswqsvbc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dashuyun.cn/Article/details/gtlivxnlvy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tianlin.xyz/Article/details/gtzcmtkkhg.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohkezeyn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hysaishi.cn/Article/details/gtjnbaroun.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtxzhgjurv.html

[Q01] 创建表
来源：http://dali.cashguo.top/Article/details/gtsmbweigi.html

CREATE TABLE users (
来源：http://dali.ppjwa.cn/Article/details/gtfcwrzlww.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.feifeiyinyue.top/Article/details/gtrksrozpm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gtztyntzgi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.9152youxi.cn/Article/details/gtktlqkcqd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhixingplan.top/Article/details/gttqkdgjvn.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxelkmabc.html

[Q02] 创建带外键的表
来源：http://dali.dashuyun.cn/Article/details/gtclbnpybw.html

CREATE TABLE orders (
来源：http://dali.xuetiantiany.cn/Article/details/gthymqoohu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gtfqzydjlc.html

user_id INT NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gtlmhfhgbf.html

amount DECIMAL(10, 2),
来源：http://dali.snrcjt.cn/Article/details/gtagktjyih.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jiagoushi.top/Article/details/gtbkpabmgk.html


<!-- 参考信息 -->