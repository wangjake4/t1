代发 wailian999

TS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gt2fnfbjbrf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gt2kpikycol.html

Go:   os.Getwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2jhapexou.html

Ruby: Dir.pwd
来源：http://dali.0kj1m.cn/Article/details/gt2jybrnmvt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yanxiufei.cn/Article/details/gt2exybngnp.html

[M05] 设置退出码
来源：http://dali.redwolf501.top/Article/details/gt2oqhvyfdk.html

Py:   sys.exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2yiqhbxjp.html

PHP:  exit(1);
来源：http://dali.meibo888.top/Article/details/gt2mjmzudof.html

JS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2hzidarkc.html

TS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2itltgspo.html

Java: System.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2jymrhpcj.html

Go:   os.Exit(1)
来源：http://dali.zdqjudy.top/Article/details/gt2svfvmmwj.html

Ruby: exit 1
来源：http://dali.daxiang520.top/Article/details/gt2gtvyywma.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ehwqpu.com/Article/details/gt2dudjovcm.html

[M06] 向标准错误输出
来源：http://dali.cqqwz.cn/Article/details/gt2coabrjhv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xylfe.cn/Article/details/gt2zqdnrsqb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hysaishi.cn/Article/details/gt2sbdaqxex.html

JS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ihxdinxq.html

TS:   console.error("err")
来源：http://dali.smart0.xyz/Article/details/gt2uvqeowgm.html

Java: System.err.println("err")
来源：http://dali.dashuyun.cn/Article/details/gt2ftypzuyu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj202588.top/Article/details/gt2ukccrigz.html

Ruby: warn "err"
来源：http://dali.yj202588.top/Article/details/gt2jvhspubi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.316326.xyz/Article/details/gt2ofotmzce.html

[M07] 判断是否为主入口
来源：http://dali.sufxvd.cn/Article/details/gt2gpsvppri.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangtech.top/Article/details/gt2owebfpop.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sweek.top/Article/details/gt2ifbcjkfm.html

JS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gt2dzbydolx.html

TS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gt2njndsmxl.html

Java: public static void main(String[] args)
来源：http://dali.wangdashe.top/Article/details/gt2ynbummdh.html

Go:   func main()
来源：http://dali.sxryk.cn/Article/details/gt2mvntrqqw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuanzhike.top/Article/details/gt2fwhvwwzg.html

C#:   static void Main(string[] args)
来源：http://dali.jiagoushi.top/Article/details/gt2nsgnggdc.html

[M08] 获取系统与运行时信息
来源：http://dali.hammf.cn/Article/details/gt2trzruory.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ppjwa.cn/Article/details/gt2tcwmyeyt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daxiang520.top/Article/details/gt2eicigfri.html

JS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lgtiindo.html

TS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gt2ilczlvjm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hammf.cn/Article/details/gt2yjenoosf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tian-w.cn/Article/details/gt2zmbwgwxw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.haohaochexian.top/Article/details/gt2ivtcyudi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhoulong.xyz/Article/details/gt2vcnzmjxj.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2gxtyoxzo.html

N. 数据结构与算法
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uqkijpco.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2hblhfjlf.html

[N01] 二分查找（有序数组）
来源：http://dali.zdqjudy.top/Article/details/gt2sslfuugd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2bfmiaiot.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.svipenyu.cn/Article/details/gt2mxohpozz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gt2bbvofjhh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gt2olmdhekp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2djavbunh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2ykxbsinc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fzhhl.top/Article/details/gt2fzodcelt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2xchhnkdd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangdashe.top/Article/details/gt2jlmuqxlx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gt2tnauezui.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daxiang520.top/Article/details/gt2rvwxowqt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gt2ettkbvln.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dqzlykka.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.svipenyu.cn/Article/details/gt2wfwdnhyn.html

Go:   slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gt2itybraan.html

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gt2ukauisav.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2chbihowj.html

[N03] 快速排序（分治示例）
来源：http://dali.cheryme.top/Article/details/gt2hmeczzfa.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xgysvsbr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.dashuyun.cn/Article/details/gt2dictmwzz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gt2tqzowfkv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gt2qzhfkcgn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shuidangran.top/Article/details/gt2extifdpj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj202588.top/Article/details/gt2echpwcce.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yvedp.cn/Article/details/gt2drfspiyw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nrttqzmf.html

[N04] 斐波那契数列
来源：http://dali.gotoacloud.top/Article/details/gt2qvhxrxfu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.0kj1m.cn/Article/details/gt2zrejobph.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gt2gwiepgls.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gt2fezdaqxq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gt2psuuituy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ydzc1.top/Article/details/gt2knsskdam.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yonumen.top/Article/details/gt2trskexsb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gt2sxceiced.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2meatnqoe.html

[N05] 最大公约数
来源：http://dali.feifeiyinyue.top/Article/details/gt2kbjoxkrs.html

Py:   math.gcd(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gt2moozwvtq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnqzz.top/Article/details/gt2fdbvnjxs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qdlsvypw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gt2ywpwwzoi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yueranfly.top/Article/details/gt2txzkbham.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guannengcc.top/Article/details/gt2uqzrqhbv.html

Ruby: a.gcd(b)
来源：http://dali.vqdsnc.cn/Article/details/gt2znyrsxqc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cheryme.top/Article/details/gt2wwkmzpqk.html

[N06] 判断回文字符串
来源：http://dali.sufxvd.cn/Article/details/gt2erzxdfwo.html

Py:   s == s[::-1]
来源：http://dali.yj202588.top/Article/details/gt2zrrciznp.html

PHP:  $s === strrev($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vtumyxzp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gt2nwnrggnh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gt2wjrtzfrb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fgkgojtg.html

Go:   // 双指针从两端比较
来源：http://dali.sysykeji.top/Article/details/gt2airavfmr.html

Ruby: s == s.reverse
来源：http://dali.yanxiufei.cn/Article/details/gt2avlkhtca.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ivvv.top/Article/details/gt2ebxokmjj.html

[N07] 两数之和（返回下标）
来源：http://dali.havefunace.top/Article/details/gt2lydetonx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sweek.top/Article/details/gt2dhlwcfwe.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guannengcc.top/Article/details/gt2brayecly.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tian-w.cn/Article/details/gt2jsvrixdh.html

TS:   // 手写 Map<string, number>
来源：http://dali.ehwqpu.com/Article/details/gt2hlnocyoj.html

Java: // 手写 HashMap
来源：http://dali.ppjwa.cn/Article/details/gt2cjosknfk.html

Go:   // 手写 map[int]int
来源：http://dali.chenlongwang.top/Article/details/gt2ocwyzzpx.html

Ruby: // 手写 Hash
来源：http://dali.zhixingplan.top/Article/details/gt2oofctbkm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuetiantiany.cn/Article/details/gt2jatxlbdf.html

[N08] 生成全排列
来源：http://dali.hnxiangtu.top/Article/details/gt2kfeylnpd.html

Py:   itertools.permutations(arr)
来源：http://dali.yonumen.top/Article/details/gt2cseleuvm.html

PHP:  // 手写递归交换
来源：http://dali.jinqigufen.top/Article/details/gt2urezapzi.html

JS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gt2avmfvhfj.html

TS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gt2iqtgczie.html

Java: // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gt2dbznggvd.html

Go:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gt2txpauadi.html

Ruby: arr.permutation.to_a
来源：http://dali.gaohongyu789.top/Article/details/gt2upxgrksa.html

C#:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gt2tchxnmis.html

[N09] 栈与队列
来源：http://dali.sxryk.cn/Article/details/gt2bcbcsocd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ybcxt.top/Article/details/gt2fhjfjbgy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xinyue.icu/Article/details/gt2zkkssgzu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2vmvznbpx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sysykeji.top/Article/details/gt2etxkifub.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pycfn.com/Article/details/gt2tacoxrot.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aibaodan.cn/Article/details/gt2zjyngbft.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gt2tmavcozv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ydzc1.top/Article/details/gt2nwubhbin.html

[N10] 链表节点定义
来源：http://dali.yj20258888.top/Article/details/gt2uctjqhpd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigufen.top/Article/details/gt2psptyabo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cucudq.cn/Article/details/gt2gxfxecnd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenlongwang.top/Article/details/gt2exnkgrkq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daxiang520.top/Article/details/gt2xlbrneug.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigufen.top/Article/details/gt2aytrebnd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.9152youxi.cn/Article/details/gt2zenncdhq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sxryk.cn/Article/details/gt2mlwhyfov.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cashguo.top/Article/details/gt2mzvgxlbx.html

[N11] 二叉树中序遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bqxjssly.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jiagoushi.top/Article/details/gt2ebbkmsfu.html

PHP:  // 手写递归函数
来源：http://dali.haohaochexian.top/Article/details/gt2fgbfumgd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gt2lwtornqj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pengpengdd.cyou/Article/details/gt2wljeucsd.html

Java: // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gt2yhsapxsx.html

Go:   // 手写递归
来源：http://dali.gzhubu.top/Article/details/gt2ehdmzuvn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258.top/Article/details/gt2gkynspqd.html

C#:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gt2xgnfnvje.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.svipenyu.cn/Article/details/gt2xtjvzxzz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgufenzy.top/Article/details/gt2cxpkswjj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqfdwsa.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gt2dbodbdln.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gt2dzfifsnq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ybxgcopo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.mhx1999.top/Article/details/gt2cusgzsrn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cucudq.cn/Article/details/gt2ijmvkszp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gt2pombyxrs.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2pdykldra.html

O. 并发与异步
来源：http://dali.hnqzz.top/Article/details/gt2rjnrtzlk.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2ftxembmg.html

[O01] 启动一个线程
来源：http://dali.wangshuangyany.cn/Article/details/gt2dynoenjt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lztlsmyh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ivvv.top/Article/details/gt2thqwtngb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bfvhkszj.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gt2bmuchvgq.html

Java: new Thread(() -> f()).start()
来源：http://dali.yangfankeji.com/Article/details/gt2vyanulck.html

Go:   go f()
来源：http://dali.shzxlz.cn/Article/details/gt2vpduobht.html

Ruby: Thread.new { f }
来源：http://dali.fengsongda.top/Article/details/gt2bxwxedpm.html

C#:   Task.Run(() => F());
来源：http://dali.tianlin.xyz/Article/details/gt2qswujotn.html

[O02] 使用线程池
来源：http://dali.pycfn.com/Article/details/gt2yzdhkfbo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnqzz.top/Article/details/gt2emdoyeya.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2toftatuy.html

JS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gt2mskskbbl.html

TS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gt2pzosmtia.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenzaomai.com/Article/details/gt2xjtqlqfs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jiagoushi.top/Article/details/gt2dwciwchk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.mhx1999.top/Article/details/gt2qopjuola.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.fzhhl.top/Article/details/gt2tpqyvwic.html

[O03] 加锁保护共享数据
来源：http://dali.gogol.net.cn/Article/details/gt2dqcxlqtz.html

Py:   with lock: shared += 1
来源：http://dali.jinqigfzy.top/Article/details/gt2zclffttp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nwbrower.top/Article/details/gt2lbxyfdlh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cqqwz.cn/Article/details/gt2irkfrloe.html

TS:   // 同 JS
来源：http://dali.chenzaomai.com/Article/details/gt2xxlunpga.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigfzy.top/Article/details/gt2mxicjgxp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.0kj1m.cn/Article/details/gt2tlchllkw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.316326.xyz/Article/details/gt2kbgzlnpd.html

C#:   lock (gate) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gt2pcmoyyhh.html

[O04] 定义异步函数并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cnynueqm.html

Py:   async def f():⏎    await g()
来源：http://dali.gzhubu.top/Article/details/gt2qahoumso.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yueranfly.top/Article/details/gt2phbgfocq.html

JS:   async function f() { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gt2kdasnabf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jyoumei.cn/Article/details/gt2vetgmbss.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.aizwys.cn/Article/details/gt2ebxbwyie.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zycfv.cn/Article/details/gt2dsgssffp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.kuanghao11.cn/Article/details/gt2rbkvjqwm.html

C#:   async Task F() { await G(); }
来源：http://dali.svipenyu.cn/Article/details/gt2sbtaemqh.html

[O05] 并发执行并等待全部完成
来源：http://dali.snrcjt.cn/Article/details/gt2qzmfmsul.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2acowegfc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.redwolf501.top/Article/details/gt2tzqayqxg.html

JS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gt2jcbhqumy.html

TS:   await Promise.all(tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ebuapvzv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jyoumei.cn/Article/details/gt2pmstcpdd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.0kj1m.cn/Article/details/gt2nnfcqgng.html

Ruby: threads.map(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iilujhpf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hywenlv.cn/Article/details/gt2ibejrnlt.html

[O06] 使用进程池
来源：http://dali.meibo888.top/Article/details/gt2zzdhdiym.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhixingplan.top/Article/details/gt2ybkoadsk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gzhubu.top/Article/details/gt2fwyewswj.html

JS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gt2fdcpqvnl.html

TS:   // child_process / cluster 模块
来源：http://dali.ydzc1.top/Article/details/gt2fsbpadpf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuanzx.com/Article/details/gt2rtwmjuvy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.quarkkingdee.top/Article/details/gt2aiuvfkhk.html

Ruby: // fork 块
来源：http://dali.daxiang520.top/Article/details/gt2fkikbiay.html

C#:   Parallel.For
来源：http://dali.hfpthk.cn/Article/details/gt2hdeobpgo.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2icbxtrdm.html

P. 常用工具函数
来源：http://dali.redwolf501.top/Article/details/gt2lavfedet.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2nutegrra.html

[P01] 生成 UUID
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ftdgvfmh.html

Py:   str(uuid.uuid4())
来源：http://dali.xuanzx.com/Article/details/gt2vuwtriro.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangshuangyany.cn/Article/details/gt2rfkusuwb.html

JS:   crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gt2xybmelho.html

TS:   crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gt2ovgznasv.html

Java: UUID.randomUUID().toString()
来源：http://dali.yongpay.top/Article/details/gt2nzfyqcvf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.smart0.xyz/Article/details/gt2besqcdzr.html

Ruby: SecureRandom.uuid
来源：http://dali.hammf.cn/Article/details/gt2tqxuafgt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xinyue.icu/Article/details/gt2eucgrchv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.feifeiyinyue.top/Article/details/gt2ifocjddn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hfpthk.cn/Article/details/gt2etyomeyi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pnddtovg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hywenlv.cn/Article/details/gt2ulhqizfx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.andypj.xyz/Article/details/gt2eqgvpgjy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vzneruwt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jlsjyb.cn/Article/details/gt2lypsmpcw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gzhubu.top/Article/details/gt2ustlgksq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jyoumei.cn/Article/details/gt2yvhrbqgq.html

[P03] 生成短随机字符串
来源：http://dali.haohaochexian.top/Article/details/gt2txltcbjo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cucudq.cn/Article/details/gt2iyrohhyk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.redwolf501.top/Article/details/gt2pqzvkzvn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2ixytggoc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gt2xttxgvpe.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2crvqehwy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xziqi.cn/Article/details/gt2fjngedhd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nwbrower.top/Article/details/gt2hfwhkawd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gogol.net.cn/Article/details/gt2ikyjlezy.html

[P04] 求长度
来源：http://dali.snrcjt.cn/Article/details/gt2ldiqdrxs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lorhyckb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gt2hwhxdnpv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258888.top/Article/details/gt2mcrlumof.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gt2dhyfdqfa.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgfzy.top/Article/details/gt2arbiwhhp.html

Go:   len(arr);  len(m)
来源：http://dali.hammf.cn/Article/details/gt2rczvmysi.html

Ruby: x.length;  x.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uvucniie.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sxryk.cn/Article/details/gt2glukcpjt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xinyue.icu/Article/details/gt2rlfdvspb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tian-w.cn/Article/details/gt2czulfyts.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xuanzx.com/Article/details/gt2iohvkmal.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.smart0.xyz/Article/details/gt2tfsgbfli.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hywenlv.cn/Article/details/gt2wiakghio.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.birdmap.top/Article/details/gt2zmajbtbd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.guowangkeji.top/Article/details/gt2iaqseios.html

Ruby: a == b
来源：http://dali.zycfv.cn/Article/details/gt2nfxligls.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tanke756.top/Article/details/gt2gicxwxod.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgufenzy.top/Article/details/gt2kcodktzn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gzhubu.top/Article/details/gt2plvtvmzn.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ucqqfkvr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258888.top/Article/details/gt2eiunwvov.html

TS:   if (x == null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dpwflchc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gt2mswtgoku.html

Go:   if x == nil {}
来源：http://dali.hysaishi.cn/Article/details/gt2uqtjdxmg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxinkj.top/Article/details/gt2ymslgykt.html

C#:   if (x is null) {}
来源：http://dali.dianchejie.cn/Article/details/gt2cmdswryz.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2islvwszo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vbswvdhd.html

PHP:  // 手写时间戳比较
来源：http://dali.jqgufenzy.top/Article/details/gt2rgntfvyo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gt2mvunaztx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzyoacip.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.guowangkeji.top/Article/details/gt2scoozcgn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tian-w.cn/Article/details/gt2ujhyxboy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj202588.top/Article/details/gt2fkehheuw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shuidangran.top/Article/details/gt2tnurfyfk.html

[P08] 处理浮点精度问题
来源：http://dali.sxryk.cn/Article/details/gt2enryhqdb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hnqzz.top/Article/details/gt2nkmxhxcr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jyoumei.cn/Article/details/gt2knlhfqfr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ppjwa.cn/Article/details/gt2rwflbteb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenzaomai.com/Article/details/gt2tbhxhbrx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhiwuduotai.top/Article/details/gt2gucnkarj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tianlin.xyz/Article/details/gt2ooththws.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.quarkkingdee.top/Article/details/gt2ocvbiuxh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guannengcc.top/Article/details/gt2qnrerier.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2chsyprbo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj202588.top/Article/details/gt2ywhjvrxo.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2wguvhanr.html

[Q01] 创建表
来源：http://dali.yuxming.cn/Article/details/gt2derukiid.html

CREATE TABLE users (
来源：http://dali.iojbl.cn/Article/details/gt2bescagey.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gt2gfrmprgx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jlsjyb.cn/Article/details/gt2vyropvfp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hysaishi.cn/Article/details/gt2rtminjnj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenjidiqi.icu/Article/details/gt2dlbgagli.html

);
来源：http://dali.zhongyouzk.top/Article/details/gt2afnlbdhw.html

[Q02] 创建带外键的表
来源：http://dali.daxiang520.top/Article/details/gt2befkoqvg.html

CREATE TABLE orders (
来源：http://dali.yongpay.top/Article/details/gt2lgnejgmt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.c1oappe.top/Article/details/gt2apvjbhbg.html

user_id INT NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gt2cizevmxx.html

amount DECIMAL(10, 2),
来源：http://dali.snrcjt.cn/Article/details/gt2ipwhxybe.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wwyvxhxk.html


<!-- 参考信息 -->