代发 wailian999

TS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gt2nrbqypqy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zycfv.cn/Article/details/gt2xatirnzs.html

Go:   os.Getwd()
来源：http://dali.aizwys.cn/Article/details/gt2jqqhloru.html

Ruby: Dir.pwd
来源：http://dali.iojbl.cn/Article/details/gt2txwgumvs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gaohongyu789.top/Article/details/gt2xuofqqpo.html

[M05] 设置退出码
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jrxzlvdn.html

Py:   sys.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2elqweawt.html

PHP:  exit(1);
来源：http://dali.havefunace.top/Article/details/gt2guoyvobg.html

JS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2kdxhacsk.html

TS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2sezynoac.html

Java: System.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2cwjiihwp.html

Go:   os.Exit(1)
来源：http://dali.guowangkeji.top/Article/details/gt2hzmsudma.html

Ruby: exit 1
来源：http://dali.gzhubu.top/Article/details/gt2hakzeduw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.c1oappe.top/Article/details/gt2ihrsjsal.html

[M06] 向标准错误输出
来源：http://dali.jqgfzy.top/Article/details/gt2mozknvfp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgfzy.top/Article/details/gt2hfnebigf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fengsongda.top/Article/details/gt2ffystrll.html

JS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gt2azakmvnm.html

TS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gt2plhazuro.html

Java: System.err.println("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wygjterl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258888.top/Article/details/gt2ydcokygb.html

Ruby: warn "err"
来源：http://dali.shuidangran.top/Article/details/gt2gcfxlddk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xylfe.cn/Article/details/gt2ttdalmbe.html

[M07] 判断是否为主入口
来源：http://dali.9152youxi.cn/Article/details/gt2tetelszo.html

Py:   if __name__ == "__main__":
来源：http://dali.yuxming.cn/Article/details/gt2evjzzleg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jlsjyb.cn/Article/details/gt2lwhvpwwr.html

JS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gt2xjcdpwhg.html

TS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gt2mdezplji.html

Java: public static void main(String[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nhsyzwte.html

Go:   func main()
来源：http://dali.aizwys.cn/Article/details/gt2wokzcnro.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhengqikj.top/Article/details/gt2fhpuppgo.html

C#:   static void Main(string[] args)
来源：http://dali.meibo888.top/Article/details/gt2bzvqhlnl.html

[M08] 获取系统与运行时信息
来源：http://dali.ydzc1.top/Article/details/gt2rkwcstrx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tanke756.top/Article/details/gt2gzcmphgh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hnxiangtu.top/Article/details/gt2jdfehifu.html

JS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gt2ztyinhli.html

TS:   process.platform;  process.version
来源：http://dali.xuanzx.com/Article/details/gt2aperawwv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxuanxn.top/Article/details/gt2prwogfvm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gzhubu.top/Article/details/gt2qyswdtkx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tian-w.cn/Article/details/gt2gokdwbmd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zzsxpyvt.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2iclvmdhp.html

N. 数据结构与算法
来源：http://dali.zdqjudy.top/Article/details/gt2xcdlwaaz.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2ucbbfrve.html

[N01] 二分查找（有序数组）
来源：http://dali.tanke756.top/Article/details/gt2sznjzcwj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2gvvshiwf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuxming.cn/Article/details/gt2hwioggwi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gt2slqazkao.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gt2hrxexqvd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2ksbzmopa.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2qbwpvypa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aizwys.cn/Article/details/gt2yzcatcqz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2wdhdrqdd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pengpengdd.cyou/Article/details/gt2uotacexo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gt2zcarormt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hammf.cn/Article/details/gt2nbyblcbk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gt2avcognpq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gt2pkyrcuox.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zycfv.cn/Article/details/gt2lzneridx.html

Go:   slices.Sort(arr)
来源：http://dali.yongpay.top/Article/details/gt2sdshhtkf.html

Ruby: arr.sort
来源：http://dali.zycfv.cn/Article/details/gt2fqtjmtpb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hfpthk.cn/Article/details/gt2fswwuzjh.html

[N03] 快速排序（分治示例）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iepvhjjp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.birdmap.top/Article/details/gt2vdofkudj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangdashe.top/Article/details/gt2ezvdaset.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gt2xodqhnke.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gt2komryztu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cashguo.top/Article/details/gt2bhqgvjey.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sweek.top/Article/details/gt2icjnrxtc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dianchejie.cn/Article/details/gt2acjcnxpi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eqswciot.html

[N04] 斐波那契数列
来源：http://dali.ydzc1.top/Article/details/gt2wsmejgiz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gt2ypbhgsxr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gt2iqpvdwok.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2yuqnbczq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yictoldg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2yvujwkrq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tanke756.top/Article/details/gt2tnjwvmok.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gt2kdteofyg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gt2pnmpauai.html

[N05] 最大公约数
来源：http://dali.sweek.top/Article/details/gt2okktmmrp.html

Py:   math.gcd(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fizpshsl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sweek.top/Article/details/gt2layxfpqb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gt2vihlbhbc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gt2xprnlamr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhengqikj.top/Article/details/gt2mkojliyt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.mhx1999.top/Article/details/gt2krtbfdqy.html

Ruby: a.gcd(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2sadtiwec.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cashguo.top/Article/details/gt2ftdorvwc.html

[N06] 判断回文字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2suvugpff.html

Py:   s == s[::-1]
来源：http://dali.tanke756.top/Article/details/gt2nvjlajnl.html

PHP:  $s === strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2mdeixdco.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wijqttys.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2abnujxyk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guowangkeji.top/Article/details/gt2ukofswqn.html

Go:   // 双指针从两端比较
来源：http://dali.hysaishi.cn/Article/details/gt2pzjckhbv.html

Ruby: s == s.reverse
来源：http://dali.fengsongda.top/Article/details/gt2xlpzzgpk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gt2ftwepnoy.html

[N07] 两数之和（返回下标）
来源：http://dali.vqdsnc.cn/Article/details/gt2vznflwea.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.316326.xyz/Article/details/gt2aodvdbbz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cdnleiting.top/Article/details/gt2wteieyfd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangdashe.top/Article/details/gt2depublya.html

TS:   // 手写 Map<string, number>
来源：http://dali.cdnleiting.top/Article/details/gt2nurxuqem.html

Java: // 手写 HashMap
来源：http://dali.snrcjt.cn/Article/details/gt2slgrukxc.html

Go:   // 手写 map[int]int
来源：http://dali.gotoacloud.top/Article/details/gt2ehzvrefe.html

Ruby: // 手写 Hash
来源：http://dali.redwolf501.top/Article/details/gt2zdqbtexk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnxiangtu.top/Article/details/gt2xfspfemt.html

[N08] 生成全排列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jtoaykcm.html

Py:   itertools.permutations(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2aprpgjpy.html

PHP:  // 手写递归交换
来源：http://dali.kuanghao11.cn/Article/details/gt2wdvjtdrz.html

JS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gt2ttxpxetl.html

TS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gt2kmfftdxu.html

Java: // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gt2tthnwlpo.html

Go:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gt2agycicae.html

Ruby: arr.permutation.to_a
来源：http://dali.jyoumei.cn/Article/details/gt2jahviich.html

C#:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gt2cpszuftw.html

[N09] 栈与队列
来源：http://dali.ppjwa.cn/Article/details/gt2thhqgggu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tanke756.top/Article/details/gt2hvflwtvo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2jpninrkx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gt2ttstpwvm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxinkj.top/Article/details/gt2jqcohysw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.smart0.xyz/Article/details/gt2vqjapxls.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xinyue.icu/Article/details/gt2pnexaubq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gt2pfeblrcm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gt2nboplqko.html

[N10] 链表节点定义
来源：http://dali.zhengqikj.top/Article/details/gt2lrpznhzl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jianghu66.top/Article/details/gt2qdgmintu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigfzy.top/Article/details/gt2qxcdtqnn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hywenlv.cn/Article/details/gt2zbxvcaed.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.kuanghao11.cn/Article/details/gt2ppmihjay.html

Java: class Node { int v; Node next; }
来源：http://dali.svipenyu.cn/Article/details/gt2evkuejwa.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yvedp.cn/Article/details/gt2lsjnpdbk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xinyue.icu/Article/details/gt2vayvlojm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ebvakfaj.html

[N11] 二叉树中序遍历
来源：http://dali.gotoacloud.top/Article/details/gt2nemawbxs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cucudq.cn/Article/details/gt2znaziwmw.html

PHP:  // 手写递归函数
来源：http://dali.daxiang520.top/Article/details/gt2otidscab.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yonumen.top/Article/details/gt2stfgopfb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gt2tfrshzul.html

Java: // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2qkbxmiie.html

Go:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gt2tbvaaimf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuxming.cn/Article/details/gt2ubhwnpaw.html

C#:   // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gt2hiyhdvll.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxinkj.top/Article/details/gt2xwycxsud.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.0kj1m.cn/Article/details/gt2zfxtwknh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fzhhl.top/Article/details/gt2vbvmnlzn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gt2xfdyzmpn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gt2sohchdtk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.redwolf501.top/Article/details/gt2dxjvhvtg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xylfe.cn/Article/details/gt2dejwnkcc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xinyue.icu/Article/details/gt2munhlnkj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ivvv.top/Article/details/gt2lxhawmtc.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2buokvcpa.html

O. 并发与异步
来源：http://dali.yj20258.top/Article/details/gt2rllogelq.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2fcovlicp.html

[O01] 启动一个线程
来源：http://dali.shuidangran.top/Article/details/gt2rnrxzpwj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuanzhike.top/Article/details/gt2spwxsqok.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ehwqpu.com/Article/details/gt2onsuxmpz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.pycfn.com/Article/details/gt2yrqzblbw.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gt2hccmmmkz.html

Java: new Thread(() -> f()).start()
来源：http://dali.nwbrower.top/Article/details/gt2junuzswi.html

Go:   go f()
来源：http://dali.shuidangran.top/Article/details/gt2xnuajqud.html

Ruby: Thread.new { f }
来源：http://dali.zhongyouzk.top/Article/details/gt2frqmqmpi.html

C#:   Task.Run(() => F());
来源：http://dali.yangfankeji.com/Article/details/gt2iffowwed.html

[O02] 使用线程池
来源：http://dali.bjfxy.top/Article/details/gt2wxtpssfw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nwbrower.top/Article/details/gt2ugsgrmme.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hysaishi.cn/Article/details/gt2pgcbdhnn.html

JS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gt2infonchu.html

TS:   // worker_threads 线程池
来源：http://dali.pycfn.com/Article/details/gt2zatbxmmn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.fengsongda.top/Article/details/gt2zsfkorfl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.fengsongda.top/Article/details/gt2ffhgpiaf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgufenzy.top/Article/details/gt2vvlmhfyh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.feifeiyinyue.top/Article/details/gt2bipruwgo.html

[O03] 加锁保护共享数据
来源：http://dali.zycfv.cn/Article/details/gt2winqmsmt.html

Py:   with lock: shared += 1
来源：http://dali.fengsongda.top/Article/details/gt2hxgvzdnp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.dashuyun.cn/Article/details/gt2dgvszqif.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vkbdijkq.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gt2yykhkehk.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gt2yqguvaop.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hammf.cn/Article/details/gt2tcnbvskq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj202588.top/Article/details/gt2secsdkie.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhengqikj.top/Article/details/gt2eaucqpjv.html

[O04] 定义异步函数并等待
来源：http://dali.bjfxy.top/Article/details/gt2bbtyyvuh.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigufen.top/Article/details/gt2elcouswy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yangfankeji.com/Article/details/gt2flqqevdq.html

JS:   async function f() { await g(); }
来源：http://dali.xuanzx.com/Article/details/gt2yzttiuoo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ivvv.top/Article/details/gt2sjdgyrwa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xrbwroii.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dashuyun.cn/Article/details/gt2onxtasxt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.haohaochexian.top/Article/details/gt2dpwtxurx.html

C#:   async Task F() { await G(); }
来源：http://dali.hammf.cn/Article/details/gt2zfwazuwi.html

[O05] 并发执行并等待全部完成
来源：http://dali.mhx1999.top/Article/details/gt2nzpnqzde.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ehwqpu.com/Article/details/gt2rbygujkl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jiagoushi.top/Article/details/gt2gatjnseh.html

JS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gt2spkweucd.html

TS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gt2hpaxgrau.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.aibaodan.cn/Article/details/gt2oaugnigz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tian-w.cn/Article/details/gt2czglaici.html

Ruby: threads.map(&:join)
来源：http://dali.birdmap.top/Article/details/gt2elifmnrp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hywenlv.cn/Article/details/gt2woflcnpf.html

[O06] 使用进程池
来源：http://dali.smart0.xyz/Article/details/gt2zxbqxmdp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hfvhpuck.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sxryk.cn/Article/details/gt2ijaexsdy.html

JS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gt2uaigvult.html

TS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gt2zuhcsuoh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.mhx1999.top/Article/details/gt2janqchsz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zdqjudy.top/Article/details/gt2rjnxxfcw.html

Ruby: // fork 块
来源：http://dali.9152youxi.cn/Article/details/gt2nkdyfyae.html

C#:   Parallel.For
来源：http://dali.gaohongyu789.top/Article/details/gt2hrddnhrb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2celfpznr.html

P. 常用工具函数
来源：http://dali.sufxvd.cn/Article/details/gt2yvituyrr.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2dbtmsjte.html

[P01] 生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gt2bqtopejl.html

Py:   str(uuid.uuid4())
来源：http://dali.wangdashe.top/Article/details/gt2hjgbpsoh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangdashe.top/Article/details/gt2yryvhknr.html

JS:   crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gt2pxpvcjxh.html

TS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gt2modjqekk.html

Java: UUID.randomUUID().toString()
来源：http://dali.tian-w.cn/Article/details/gt2pbhqnkhk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.svipenyu.cn/Article/details/gt2dcyiomwn.html

Ruby: SecureRandom.uuid
来源：http://dali.jiagoushi.top/Article/details/gt2xeaneyxv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gotoacloud.top/Article/details/gt2hkzcfrvi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258.top/Article/details/gt2shixlzun.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigufen.top/Article/details/gt2ffigwtpf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sufxvd.cn/Article/details/gt2wovekcyx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ivvv.top/Article/details/gt2egdffkpg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnbtgke.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daria6918.cn/Article/details/gt2xoisyolp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhixingplan.top/Article/details/gt2liqligtf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xziqi.cn/Article/details/gt2qkfumfuc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnqzz.top/Article/details/gt2hgyxbbzl.html

[P03] 生成短随机字符串
来源：http://dali.fengsongda.top/Article/details/gt2znvpeotl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pycfn.com/Article/details/gt2epjapqqc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cashguo.top/Article/details/gt2hhxoogas.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gt2gtomsyur.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guannengcc.top/Article/details/gt2jrvrkjhy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yongpay.top/Article/details/gt2naymjxcy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nwbrower.top/Article/details/gt2ewtcnnfn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.birdmap.top/Article/details/gt2hrhutqaq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xylfe.cn/Article/details/gt2fgplzqds.html

[P04] 求长度
来源：http://dali.yangfankeji.com/Article/details/gt2wfgniqir.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dianchejie.cn/Article/details/gt2ybzvmzzs.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gt2ahrunkhd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hfpthk.cn/Article/details/gt2itkogjkq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gt2maqloypc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gt2zrialslz.html

Go:   len(arr);  len(m)
来源：http://dali.cashguo.top/Article/details/gt2rkbctkwo.html

Ruby: x.length;  x.size
来源：http://dali.shzxlz.cn/Article/details/gt2edrwbirc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.daria6918.cn/Article/details/gt2zkixpyib.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zycfv.cn/Article/details/gt2azpfcmkq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258.top/Article/details/gt2tbgbdvyc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.haohaochexian.top/Article/details/gt2rnjwvwmf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xfwpimon.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gt2pfifdcdi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yuxming.cn/Article/details/gt2iyyiqfmw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gt2rdhaxeem.html

Ruby: a == b
来源：http://dali.9152youxi.cn/Article/details/gt2loqydduy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigfzy.top/Article/details/gt2ixuchmwn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.kuanghao11.cn/Article/details/gt2wrkwqaxy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sufxvd.cn/Article/details/gt2mnviuhbf.html

PHP:  if (empty($x)) {}
来源：http://dali.meibo888.top/Article/details/gt2muunqqpr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hywenlv.cn/Article/details/gt2qlowvzyb.html

TS:   if (x == null) {}
来源：http://dali.guannengcc.top/Article/details/gt2jmnqvesc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gt2bsbbfpnx.html

Go:   if x == nil {}
来源：http://dali.cheryme.top/Article/details/gt2vcxfqgkn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qvtavyqt.html

C#:   if (x is null) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2uljhezxn.html

[P07] 防抖与节流
来源：http://dali.yonumen.top/Article/details/gt2fgtwllmk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gotoacloud.top/Article/details/gt2riazaaqu.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigufen.top/Article/details/gt2kltapslh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gt2oonlskax.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gt2cueubofl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ppjwa.cn/Article/details/gt2zidxqxym.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ppjwa.cn/Article/details/gt2jzutaqos.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.kuanghao11.cn/Article/details/gt2agozpryg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.redwolf501.top/Article/details/gt2cqcwsphz.html

[P08] 处理浮点精度问题
来源：http://dali.guannengcc.top/Article/details/gt2jaskuyds.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2haawdtqx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.guowangkeji.top/Article/details/gt2uryrwwtz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.guannengcc.top/Article/details/gt2didyszcn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kgplgjxw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.quarkkingdee.top/Article/details/gt2jnqnjsvy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuanzhike.top/Article/details/gt2zbgzjnzv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.0kj1m.cn/Article/details/gt2gcmsvujq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guowangkeji.top/Article/details/gt2vlzzmath.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2mgifiagj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.9152youxi.cn/Article/details/gt2vjjnmllu.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2kdglgwgo.html

[Q01] 创建表
来源：http://dali.daria6918.cn/Article/details/gt2ablycahm.html

CREATE TABLE users (
来源：http://dali.yueranfly.top/Article/details/gt2quhdirfw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gt2nugciyyi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhengqikj.top/Article/details/gt2gpfmoqnb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hfpthk.cn/Article/details/gt2fsxbwwme.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangshuangyany.cn/Article/details/gt2xumygqlf.html

);
来源：http://dali.redwolf501.top/Article/details/gt2mdigcesu.html

[Q02] 创建带外键的表
来源：http://dali.zhiwuduotai.top/Article/details/gt2voesewmw.html

CREATE TABLE orders (
来源：http://dali.yuanzhike.top/Article/details/gt2grptozji.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.c1oappe.top/Article/details/gt2qyinirzd.html

user_id INT NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gt2zpaiitnx.html

amount DECIMAL(10, 2),
来源：http://dali.jiagoushi.top/Article/details/gt2tppsbhbh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jntgecfr.html


<!-- 参考信息 -->