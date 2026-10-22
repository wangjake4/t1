代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shuidangran.top/Article/details/gt2qxrxzuzl.html

[M05] 设置退出码
来源：http://dali.nanxinkj.top/Article/details/gt2ehktqidz.html

Py:   sys.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2uvsbofhg.html

PHP:  exit(1);
来源：http://dali.meibo888.top/Article/details/gt2iikkckwo.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2gicjqkiu.html

TS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2acdzsevh.html

Java: System.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2buvwytfu.html

Go:   os.Exit(1)
来源：http://dali.yonumen.top/Article/details/gt2ispntocp.html

Ruby: exit 1
来源：http://dali.aizwys.cn/Article/details/gt2aorbyzlt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jlsjyb.cn/Article/details/gt2czzzzpxs.html

[M06] 向标准错误输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2fyscescz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gt2chyzknxn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2obpzarih.html

JS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gt2ylcltyuw.html

TS:   console.error("err")
来源：http://dali.kuanghao11.cn/Article/details/gt2lpabcgzx.html

Java: System.err.println("err")
来源：http://dali.yuanzhike.top/Article/details/gt2nyuyiulg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.redwolf501.top/Article/details/gt2lcidskyy.html

Ruby: warn "err"
来源：http://dali.zhengqikj.top/Article/details/gt2txlxhuhw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.redwolf501.top/Article/details/gt2bjceyfun.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dvqcyanj.html

Py:   if __name__ == "__main__":
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ebhhddoh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.316326.xyz/Article/details/gt2luhqpkbp.html

JS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gt2yezudehn.html

TS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gt2cavbfyie.html

Java: public static void main(String[] args)
来源：http://dali.hnxiangtu.top/Article/details/gt2ubzfpdni.html

Go:   func main()
来源：http://dali.xinyue.icu/Article/details/gt2bfihxhhp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jyoumei.cn/Article/details/gt2ritauiae.html

C#:   static void Main(string[] args)
来源：http://dali.nanxinkj.top/Article/details/gt2cjrzwalo.html

[M08] 获取系统与运行时信息
来源：http://dali.nwbrower.top/Article/details/gt2wlcfhdcq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.aizwys.cn/Article/details/gt2fnqdauij.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dianchejie.cn/Article/details/gt2jgpyfbua.html

JS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bkvdstdo.html

TS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gt2guzwkaby.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jyoumei.cn/Article/details/gt2gtpzzsip.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yvedp.cn/Article/details/gt2nqounkac.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenlongwang.top/Article/details/gt2yyegfddn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sweek.top/Article/details/gt2ahsozijr.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2dbedbuva.html

N. 数据结构与算法
来源：http://dali.hnqzz.top/Article/details/gt2cljatzve.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2stieynjn.html

[N01] 二分查找（有序数组）
来源：http://dali.gaohongyu789.top/Article/details/gt2hzhstjil.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2qxnhhfju.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.aizwys.cn/Article/details/gt2bxydqizw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gt2nfiblxeb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cdnleiting.top/Article/details/gt2ddysqilq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kshuixeo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gt2qsszvoiy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zdqjudy.top/Article/details/gt2utjgekid.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gt2nwmjemaf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gotoacloud.top/Article/details/gt2ycuhhxgm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gt2cbkzgarr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sxryk.cn/Article/details/gt2shvbyans.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gt2zievahxs.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gt2nzahsmpt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gaohongyu789.top/Article/details/gt2jcgbcjao.html

Go:   slices.Sort(arr)
来源：http://dali.pycfn.com/Article/details/gt2ivfdrsgy.html

Ruby: arr.sort
来源：http://dali.yueranfly.top/Article/details/gt2xfmygers.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aizwys.cn/Article/details/gt2yjelgjrb.html

[N03] 快速排序（分治示例）
来源：http://dali.shzxlz.cn/Article/details/gt2adfdozec.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258.top/Article/details/gt2hrmoohwc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ezvcdvyv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gt2otlpzxgb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gt2xaxlkhqs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.andypj.xyz/Article/details/gt2zbplghep.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhengqikj.top/Article/details/gt2wowapkzp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuetiantiany.cn/Article/details/gt2pcxnkeyj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xylfe.cn/Article/details/gt2twmavgpx.html

[N04] 斐波那契数列
来源：http://dali.sufxvd.cn/Article/details/gt2okybvdit.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gt2dvzonbea.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.bjfxy.top/Article/details/gt2faxqfxla.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gt2lltyoetc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2fwfydkcc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gt2dyhgqyqh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yanxiufei.cn/Article/details/gt2bymbwwcr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gogol.net.cn/Article/details/gt2ltxmckqe.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gt2bmrnorug.html

[N05] 最大公约数
来源：http://dali.meibo888.top/Article/details/gt2nayihbdq.html

Py:   math.gcd(a, b)
来源：http://dali.hywenlv.cn/Article/details/gt2lfdyxjzg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zycfv.cn/Article/details/gt2jhklozhp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gt2divdaktx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gt2qwsamqgz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zdqjudy.top/Article/details/gt2lmtiuhcw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yangfankeji.com/Article/details/gt2fgchxdva.html

Ruby: a.gcd(b)
来源：http://dali.fzhhl.top/Article/details/gt2aflkizay.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yvedp.cn/Article/details/gt2cunedlae.html

[N06] 判断回文字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2luethxwf.html

Py:   s == s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gt2beqkswje.html

PHP:  $s === strrev($s);
来源：http://dali.sysykeji.top/Article/details/gt2ggxtvbsn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gt2zddkqcrg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gt2rmspcqqn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxinkj.top/Article/details/gt2zufrgoil.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mttrykod.html

Ruby: s == s.reverse
来源：http://dali.gogol.net.cn/Article/details/gt2ohsxuvgj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.guannengcc.top/Article/details/gt2icktvabk.html

[N07] 两数之和（返回下标）
来源：http://dali.pycfn.com/Article/details/gt2wxuamlza.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigfzy.top/Article/details/gt2gebrlutq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cashguo.top/Article/details/gt2tbjzuaaq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daxiang520.top/Article/details/gt2thzzysul.html

TS:   // 手写 Map<string, number>
来源：http://dali.sufxvd.cn/Article/details/gt2xdawyhkw.html

Java: // 手写 HashMap
来源：http://dali.316326.xyz/Article/details/gt2ylmxfkjp.html

Go:   // 手写 map[int]int
来源：http://dali.zhengqikj.top/Article/details/gt2udypoljb.html

Ruby: // 手写 Hash
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ntpaccgp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj20258888.top/Article/details/gt2cgsbntzt.html

[N08] 生成全排列
来源：http://dali.xziqi.cn/Article/details/gt2wohyxbgq.html

Py:   itertools.permutations(arr)
来源：http://dali.sxryk.cn/Article/details/gt2hfozzlzw.html

PHP:  // 手写递归交换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pehrkjwk.html

JS:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gt2niagvrjd.html

TS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gt2nsrnmvwo.html

Java: // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2iunckbdb.html

Go:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gt2shmmjfdh.html

Ruby: arr.permutation.to_a
来源：http://dali.gaohongyu789.top/Article/details/gt2kfykcpzj.html

C#:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2dksgvpqn.html

[N09] 栈与队列
来源：http://dali.sweek.top/Article/details/gt2hmpizmdg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ybcxt.top/Article/details/gt2xtxuautj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qfvqgzau.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gt2tfevvwrz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gogol.net.cn/Article/details/gt2smoyejxf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yueranfly.top/Article/details/gt2dgjbcyud.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxuanxn.top/Article/details/gt2dbsmridr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gt2kjqqzgew.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cucudq.cn/Article/details/gt2oywxjsxf.html

[N10] 链表节点定义
来源：http://dali.zdqjudy.top/Article/details/gt2exvgqzcg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhixingplan.top/Article/details/gt2mtnjxzgr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vkirmayg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.havefunace.top/Article/details/gt2pyxkabnp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgufenzy.top/Article/details/gt2tldvdgzh.html

Java: class Node { int v; Node next; }
来源：http://dali.aibaodan.cn/Article/details/gt2texnwgyd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pycfn.com/Article/details/gt2oooqppgi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sweek.top/Article/details/gt2shcoibek.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jlsjyb.cn/Article/details/gt2trmdxaen.html

[N11] 二叉树中序遍历
来源：http://dali.yangfankeji.com/Article/details/gt2ecbufqop.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gotoacloud.top/Article/details/gt2hnitcgzg.html

PHP:  // 手写递归函数
来源：http://dali.daria6918.cn/Article/details/gt2vzqfhmso.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dianchejie.cn/Article/details/gt2jmrulvzs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gt2khfgmzib.html

Java: // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2ksvhctwi.html

Go:   // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gt2xtoasbay.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cashguo.top/Article/details/gt2mmienabi.html

C#:   // 手写递归
来源：http://dali.smart0.xyz/Article/details/gt2sewlqctl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.pycfn.com/Article/details/gt2nfupwqzu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sutmmqui.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.vqdsnc.cn/Article/details/gt2cvikpnta.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2crpqtflq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gt2dumamxdd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuanzx.com/Article/details/gt2qdeeyqon.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.kuanghao11.cn/Article/details/gt2oqolkfsi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.quarkkingdee.top/Article/details/gt2likfpmyg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.0kj1m.cn/Article/details/gt2fbfikbps.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2uysxshvw.html

O. 并发与异步
来源：http://dali.jyoumei.cn/Article/details/gt2qpnlqgjd.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2jcxozvtq.html

[O01] 启动一个线程
来源：http://dali.chenzaomai.com/Article/details/gt2kgmtjxrf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tanke756.top/Article/details/gt2ppgoxqny.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cucudq.cn/Article/details/gt2jviezcrf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.fengsongda.top/Article/details/gt2ghsnwlea.html

TS:   // 同 JS
来源：http://dali.havefunace.top/Article/details/gt2kqbxvedw.html

Java: new Thread(() -> f()).start()
来源：http://dali.fzhhl.top/Article/details/gt2omfexqzu.html

Go:   go f()
来源：http://dali.yj202588.top/Article/details/gt2ehvsqdoi.html

Ruby: Thread.new { f }
来源：http://dali.pycfn.com/Article/details/gt2clngfdhm.html

C#:   Task.Run(() => F());
来源：http://dali.gogol.net.cn/Article/details/gt2pihutjxf.html

[O02] 使用线程池
来源：http://dali.gaohongyu789.top/Article/details/gt2aoagiwjh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jqgfzy.top/Article/details/gt2kbrvclor.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sufxvd.cn/Article/details/gt2wngktekl.html

JS:   // worker_threads 线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ljzpquyb.html

TS:   // worker_threads 线程池
来源：http://dali.gaohongyu789.top/Article/details/gt2pclracpp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cdvmkysn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj202588.top/Article/details/gt2uqrgztxa.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cucudq.cn/Article/details/gt2ubexwjtg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.wangdashe.top/Article/details/gt2fggmoxzc.html

[O03] 加锁保护共享数据
来源：http://dali.svipenyu.cn/Article/details/gt2jlrbfszs.html

Py:   with lock: shared += 1
来源：http://dali.jiagoushi.top/Article/details/gt2gnyjbaoh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.haohaochexian.top/Article/details/gt2yfqewugj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigufen.top/Article/details/gt2jzwwgvfr.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gt2ybhlthgo.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gt2hlfxnxkt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jatinfgo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ioeocduw.html

C#:   lock (gate) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gt2sqmrtzss.html

[O04] 定义异步函数并等待
来源：http://dali.gaohongyu789.top/Article/details/gt2orhifnhc.html

Py:   async def f():⏎    await g()
来源：http://dali.cucudq.cn/Article/details/gt2pcckywgv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.guannengcc.top/Article/details/gt2mamhvgfb.html

JS:   async function f() { await g(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zkotusvg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gt2mzldpwff.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigufen.top/Article/details/gt2btzzdtap.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.aizwys.cn/Article/details/gt2vjmxqpsf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yongpay.top/Article/details/gt2epyzjesw.html

C#:   async Task F() { await G(); }
来源：http://dali.dashuyun.cn/Article/details/gt2fqcluahi.html

[O05] 并发执行并等待全部完成
来源：http://dali.hfpthk.cn/Article/details/gt2tcakyxxj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgufenzy.top/Article/details/gt2uwcvbxzs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kastdagu.html

JS:   await Promise.all(tasks)
来源：http://dali.tian-w.cn/Article/details/gt2ayslzijo.html

TS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gt2lmdfmoib.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.aizwys.cn/Article/details/gt2bxmoavqu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2frszoulx.html

Ruby: threads.map(&:join)
来源：http://dali.dianchejie.cn/Article/details/gt2rgfdqeww.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xylfe.cn/Article/details/gt2kvhanbyv.html

[O06] 使用进程池
来源：http://dali.jianghu66.top/Article/details/gt2ihxewvrf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgufenzy.top/Article/details/gt2btaiymks.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuanzhike.top/Article/details/gt2ywjmpftu.html

JS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gt2eqxkaokv.html

TS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gt2tavkavsf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gt2atclnqco.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj202588.top/Article/details/gt2zvyzuibj.html

Ruby: // fork 块
来源：http://dali.chenzaomai.com/Article/details/gt2jhvpktjc.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2fojswlxs.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ydzlqyfy.html

P. 常用工具函数
来源：http://dali.havefunace.top/Article/details/gt2fzkviexv.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2ccguddla.html

[P01] 生成 UUID
来源：http://dali.jinghuilouyu.cn/Article/details/gt2txrcnfyw.html

Py:   str(uuid.uuid4())
来源：http://dali.tanke756.top/Article/details/gt2xpxdrquw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jqgfzy.top/Article/details/gt2cetoagkl.html

JS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gt2eyfkmjlx.html

TS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gt2hwlzwxvq.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuanzhike.top/Article/details/gt2mzokdscf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.9152youxi.cn/Article/details/gt2onafuhly.html

Ruby: SecureRandom.uuid
来源：http://dali.c1oappe.top/Article/details/gt2chioqoct.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jianghu66.top/Article/details/gt2ezjhkcud.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2oabrdjpd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.iojbl.cn/Article/details/gt2esqwqzdr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258888.top/Article/details/gt2jezasvnp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.mhx1999.top/Article/details/gt2ljqfeoxi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgufenzy.top/Article/details/gt2bebvcwcd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xtswcjme.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.andypj.xyz/Article/details/gt2jrvjfcvc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.haohaochexian.top/Article/details/gt2viifytdz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgufenzy.top/Article/details/gt2chkeoiex.html

[P03] 生成短随机字符串
来源：http://dali.ybcxt.top/Article/details/gt2xunokfcm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cucudq.cn/Article/details/gt2deqtuipt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xziqi.cn/Article/details/gt2wiwbfgbc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gt2tyoqoily.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tanke756.top/Article/details/gt2etdjydtf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.wangdashe.top/Article/details/gt2zlkjpnid.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tian-w.cn/Article/details/gt2hjvlgqww.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ehwqpu.com/Article/details/gt2rsswjvnn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tian-w.cn/Article/details/gt2xtanunqu.html

[P04] 求长度
来源：http://dali.mhx1999.top/Article/details/gt2lbnumagc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hfpthk.cn/Article/details/gt2sfggrntm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2mjgkpgnz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgufenzy.top/Article/details/gt2sphsexun.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pengpengdd.cyou/Article/details/gt2lqcjwdmt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.snrcjt.cn/Article/details/gt2nlgwgsdh.html

Go:   len(arr);  len(m)
来源：http://dali.tian-w.cn/Article/details/gt2bkdqlpis.html

Ruby: x.length;  x.size
来源：http://dali.fzhhl.top/Article/details/gt2xqqeills.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ivvv.top/Article/details/gt2myhkmgme.html

[P05] 判断两个对象内容是否相等
来源：http://dali.birdmap.top/Article/details/gt2mfyzlfry.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yueranfly.top/Article/details/gt2duxifnim.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhixingplan.top/Article/details/gt2eeogzfcg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hwgtmpxm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwoeadiv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xylfe.cn/Article/details/gt2udffumak.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.havefunace.top/Article/details/gt2xttxlxmt.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2auwflgyu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shuidangran.top/Article/details/gt2eruywfpr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jyoumei.cn/Article/details/gt2rpcxhhhe.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj20258888.top/Article/details/gt2pbhmdboj.html

PHP:  if (empty($x)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lolvncmn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yvedp.cn/Article/details/gt2ftjduqrg.html

TS:   if (x == null) {}
来源：http://dali.yuanzhike.top/Article/details/gt2rikflirl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gt2eoptruod.html

Go:   if x == nil {}
来源：http://dali.gaohongyu789.top/Article/details/gt2pmfveahm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jqgufenzy.top/Article/details/gt2rflxvdsy.html

C#:   if (x is null) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2dizmpluj.html

[P07] 防抖与节流
来源：http://dali.aibaodan.cn/Article/details/gt2qtsjzxbj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhengqikj.top/Article/details/gt2qjaqkdwg.html

PHP:  // 手写时间戳比较
来源：http://dali.hfpthk.cn/Article/details/gt2yildkxqm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gt2exlcjzpg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gt2vxhbjdsp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.wangdashe.top/Article/details/gt2ozkjdnkt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cheryme.top/Article/details/gt2eqlappvw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ppjwa.cn/Article/details/gt2bbrxgghj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.dianchejie.cn/Article/details/gt2uvozadzl.html

[P08] 处理浮点精度问题
来源：http://dali.yanxiufei.cn/Article/details/gt2xdpzjjoq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hongshengwenyu.top/Article/details/gt2txdwssrj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cqqwz.cn/Article/details/gt2egteehfg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sweek.top/Article/details/gt2ukisqfsy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shzxlz.cn/Article/details/gt2baipuezv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenzaomai.com/Article/details/gt2lwchrpnh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhoulong.xyz/Article/details/gt2moftcstf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.daria6918.cn/Article/details/gt2wcvjtxbs.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.c1oappe.top/Article/details/gt2jabkzeuz.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2dmnmxtlk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cheryme.top/Article/details/gt2tqtqtyrp.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2pxaghwpq.html

[Q01] 创建表
来源：http://dali.yanxiufei.cn/Article/details/gt2bloqdypa.html

CREATE TABLE users (
来源：http://dali.hnxiangtu.top/Article/details/gt2mubkxlgt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gt2rniuduwd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gt2yqoivsly.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuxming.cn/Article/details/gt2ciuwolxs.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuanzx.com/Article/details/gt2qqtzetpd.html

);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2peciedzl.html

[Q02] 创建带外键的表
来源：http://dali.wangshuangyany.cn/Article/details/gt2srtxznfz.html

CREATE TABLE orders (
来源：http://dali.daxiang520.top/Article/details/gt2qfcekveb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gt2zyigroiy.html

user_id INT NOT NULL,
来源：http://dali.xuanzx.com/Article/details/gt2ejyvwqdw.html

amount DECIMAL(10, 2),
来源：http://dali.ydzc1.top/Article/details/gt2rhxmkvwd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ovabbdds.html

);
来源：http://dali.ydzc1.top/Article/details/gt2pcuktqbr.html

[Q03] 增加列
来源：http://dali.andypj.xyz/Article/details/gt2xxefmhut.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2neybmrfc.html

[Q04] 修改列类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ivfmbupn.html


<!-- 参考信息 -->