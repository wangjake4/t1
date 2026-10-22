代发 wailian999

Ruby: exit 1
来源：http://dali.dianchejie.cn/Article/details/gt2gthsfgwy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxinkj.top/Article/details/gt2skoovabx.html

[M06] 向标准错误输出
来源：http://dali.xziqi.cn/Article/details/gt2etpqrkgf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gt2ykvuyqtq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnqzz.top/Article/details/gt2lsdjkfyu.html

JS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gt2jafktyto.html

TS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gt2nxbjijmh.html

Java: System.err.println("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qrgbnepu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kxavdoxu.html

Ruby: warn "err"
来源：http://dali.hnxiangtu.top/Article/details/gt2viixbjwt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj202588.top/Article/details/gt2gvmvymaf.html

[M07] 判断是否为主入口
来源：http://dali.shuidangran.top/Article/details/gt2aqyzdnad.html

Py:   if __name__ == "__main__":
来源：http://dali.zhixingplan.top/Article/details/gt2loebcijp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tanke756.top/Article/details/gt2nikjmgdd.html

JS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbioulhd.html

TS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gt2keqcytfq.html

Java: public static void main(String[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ngukgkuh.html

Go:   func main()
来源：http://dali.xinyue.icu/Article/details/gt2fmgdgxlc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2syltomvk.html

C#:   static void Main(string[] args)
来源：http://dali.smart0.xyz/Article/details/gt2ltpclbuc.html

[M08] 获取系统与运行时信息
来源：http://dali.aibaodan.cn/Article/details/gt2xnapimzn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.birdmap.top/Article/details/gt2bruhohqp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ajalayyu.html

JS:   process.platform;  process.version
来源：http://dali.yuxming.cn/Article/details/gt2lxchndpp.html

TS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gt2buyhhnga.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hfpthk.cn/Article/details/gt2ctbapsbl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daxiang520.top/Article/details/gt2ztbslcmb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pycfn.com/Article/details/gt2vdhefann.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuanzhike.top/Article/details/gt2gszvgewy.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2uojpljjw.html

N. 数据结构与算法
来源：http://dali.ehwqpu.com/Article/details/gt2byyngbnf.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2yoldteot.html

[N01] 二分查找（有序数组）
来源：http://dali.kuanghao11.cn/Article/details/gt2qgclwveq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2mzfbyevx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj202588.top/Article/details/gt2zmcaifdx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gt2atcsaqkh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sxryk.cn/Article/details/gt2fqixougw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2uynkdogm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2jvscbuuy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yvedp.cn/Article/details/gt2zdqjaajx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gt2vbltrtix.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ybcxt.top/Article/details/gt2wchgezpp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gt2csaivewd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhoulong.xyz/Article/details/gt2jsrfpdse.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gt2vrewfirn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gt2bsqxtitb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jqgufenzy.top/Article/details/gt2udsptkmt.html

Go:   slices.Sort(arr)
来源：http://dali.bjfxy.top/Article/details/gt2mhegrzyw.html

Ruby: arr.sort
来源：http://dali.316326.xyz/Article/details/gt2rkfbsmtj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yueranfly.top/Article/details/gt2fulysedb.html

[N03] 快速排序（分治示例）
来源：http://dali.hywenlv.cn/Article/details/gt2lzrisxwt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuanzhike.top/Article/details/gt2zszsgljj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ppjwa.cn/Article/details/gt2pljaqvtt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gt2pipomonw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zycfv.cn/Article/details/gt2fgcyljsc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ybcxt.top/Article/details/gt2cdguaszs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhengqikj.top/Article/details/gt2tendyztk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj202588.top/Article/details/gt2yogeozlr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhiwuduotai.top/Article/details/gt2xfwwfdai.html

[N04] 斐波那契数列
来源：http://dali.cdnleiting.top/Article/details/gt2dpgnztho.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gt2vapsqdnx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gpwdkjyi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gt2ddhmlbyt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zauxbgsp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gt2grmgjucg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinqigufen.top/Article/details/gt2yibgvfpp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gt2vqbafozi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gt2hgwxrrjk.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2pupxlxyn.html

Py:   math.gcd(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gt2zafkjfpi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2wdydogig.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2lategozs.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yueranfly.top/Article/details/gt2peyrbtze.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ppjwa.cn/Article/details/gt2xpugycuy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ezcdwdoy.html

Ruby: a.gcd(b)
来源：http://dali.c1oappe.top/Article/details/gt2lzsqhzxh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sxryk.cn/Article/details/gt2ohqafrql.html

[N06] 判断回文字符串
来源：http://dali.xylfe.cn/Article/details/gt2jfhdxent.html

Py:   s == s[::-1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lllbqjyy.html

PHP:  $s === strrev($s);
来源：http://dali.jinqigufen.top/Article/details/gt2ydnsbxpn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gt2wiurzvpt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gt2dgqoxdah.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uoctcssh.html

Go:   // 双指针从两端比较
来源：http://dali.nanxinkj.top/Article/details/gt2xokekmgo.html

Ruby: s == s.reverse
来源：http://dali.xinyue.icu/Article/details/gt2puendaqo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.meibo888.top/Article/details/gt2jkugfztt.html

[N07] 两数之和（返回下标）
来源：http://dali.fengsongda.top/Article/details/gt2dkydpnoa.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.kuanghao11.cn/Article/details/gt2bvopgxur.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258.top/Article/details/gt2kqwnbytb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.bjfxy.top/Article/details/gt2omdbethg.html

TS:   // 手写 Map<string, number>
来源：http://dali.haohaochexian.top/Article/details/gt2qrfziqeg.html

Java: // 手写 HashMap
来源：http://dali.zhixingplan.top/Article/details/gt2hsurcaqz.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258888.top/Article/details/gt2ovzwhfas.html

Ruby: // 手写 Hash
来源：http://dali.9152youxi.cn/Article/details/gt2krybltur.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yuxming.cn/Article/details/gt2lnplatdd.html

[N08] 生成全排列
来源：http://dali.andypj.xyz/Article/details/gt2drqmgfzc.html

Py:   itertools.permutations(arr)
来源：http://dali.sysykeji.top/Article/details/gt2msaihwyp.html

PHP:  // 手写递归交换
来源：http://dali.smart0.xyz/Article/details/gt2wgjngsbk.html

JS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gt2dywyszie.html

TS:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gt2iijwhcop.html

Java: // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gt2bqcdtoqf.html

Go:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gt2aamyatnq.html

Ruby: arr.permutation.to_a
来源：http://dali.yangfankeji.com/Article/details/gt2ftokabha.html

C#:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gt2vcpmryhl.html

[N09] 栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvgvuogz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gt2jozjfryc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tmyapwwf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gt2fypjpspq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.kuanghao11.cn/Article/details/gt2ubvksewy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nsqwflrx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xylfe.cn/Article/details/gt2qtjcbwev.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gt2nrokason.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tianlin.xyz/Article/details/gt2xxzxcvgq.html

[N10] 链表节点定义
来源：http://dali.cucudq.cn/Article/details/gt2kvxtxoym.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.feifeiyinyue.top/Article/details/gt2foizfpcd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhengqikj.top/Article/details/gt2dnkuwrsz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hammf.cn/Article/details/gt2gweeneym.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jiagoushi.top/Article/details/gt2rqtqkfal.html

Java: class Node { int v; Node next; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2xlweesht.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.iojbl.cn/Article/details/gt2qblbptxp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sxryk.cn/Article/details/gt2tujkqvuy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cdnleiting.top/Article/details/gt2ovtjticv.html

[N11] 二叉树中序遍历
来源：http://dali.cheryme.top/Article/details/gt2boctfgsk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xziqi.cn/Article/details/gt2khacejqx.html

PHP:  // 手写递归函数
来源：http://dali.cucudq.cn/Article/details/gt2exgrrlbd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gt2tzxboktj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gt2ccsujziz.html

Java: // 手写递归
来源：http://dali.xylfe.cn/Article/details/gt2cnjdedav.html

Go:   // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mkfqesdl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sweek.top/Article/details/gt2jftjtvgo.html

C#:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gt2jkybtath.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.havefunace.top/Article/details/gt2oxdzompf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gzhubu.top/Article/details/gt2zobdqvia.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2muyhvdes.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gt2tygshgun.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gt2mjmojdti.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyklaak.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.haohaochexian.top/Article/details/gt2mipndtae.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hnxiangtu.top/Article/details/gt2gbqzobxu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gt2hjdqqzgl.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2ryrajrka.html

O. 并发与异步
来源：http://dali.quarkkingdee.top/Article/details/gt2zmgtncqs.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2dswbrnho.html

[O01] 启动一个线程
来源：http://dali.mhx1999.top/Article/details/gt2yikzqkov.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.birdmap.top/Article/details/gt2vafcaaeu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnxiangtu.top/Article/details/gt2xaradeug.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hammf.cn/Article/details/gt2jfsbuwqv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mdohhvkh.html

Java: new Thread(() -> f()).start()
来源：http://dali.pengpengdd.cyou/Article/details/gt2mydrzlgx.html

Go:   go f()
来源：http://dali.jinqigufen.top/Article/details/gt2oxrtkbqg.html

Ruby: Thread.new { f }
来源：http://dali.sufxvd.cn/Article/details/gt2bwvtzkyz.html

C#:   Task.Run(() => F());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jxgiyxwe.html

[O02] 使用线程池
来源：http://dali.svipenyu.cn/Article/details/gt2uxtgrtbh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gt2cicoclut.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.kuanghao11.cn/Article/details/gt2igxawcql.html

JS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gt2kuavpxng.html

TS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gt2bwxdlqhg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jiagoushi.top/Article/details/gt2tlffatqw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.snrcjt.cn/Article/details/gt2akybbpje.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenjidiqi.icu/Article/details/gt2bybypkcr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.fengsongda.top/Article/details/gt2pyhbyaxk.html

[O03] 加锁保护共享数据
来源：http://dali.tanke756.top/Article/details/gt2xdyhiaxe.html

Py:   with lock: shared += 1
来源：http://dali.guowangkeji.top/Article/details/gt2bfgwdwar.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hysaishi.cn/Article/details/gt2fidtoney.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shzxlz.cn/Article/details/gt2ydyknoja.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gt2balpqwgg.html

Java: synchronized (this) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gt2dljgrary.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yongpay.top/Article/details/gt2rcsmaaak.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gotoacloud.top/Article/details/gt2ghgyvrww.html

C#:   lock (gate) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gt2xkkfvoqm.html

[O04] 定义异步函数并等待
来源：http://dali.wangdashe.top/Article/details/gt2ucvnjaep.html

Py:   async def f():⏎    await g()
来源：http://dali.andypj.xyz/Article/details/gt2hdgpjqus.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.bjfxy.top/Article/details/gt2swynkgmx.html

JS:   async function f() { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gt2bfbaahvz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tian-w.cn/Article/details/gt2kqzfkowr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.guannengcc.top/Article/details/gt2vernxlai.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daria6918.cn/Article/details/gt2zunvwzxo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.0kj1m.cn/Article/details/gt2rzgjjxhe.html

C#:   async Task F() { await G(); }
来源：http://dali.cashguo.top/Article/details/gt2xuahoqvb.html

[O05] 并发执行并等待全部完成
来源：http://dali.bjfxy.top/Article/details/gt2rlcajktr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.mhx1999.top/Article/details/gt2gfyfihwo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fengsongda.top/Article/details/gt2vrnljfyo.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gt2tjvomopl.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gt2mijpudiu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gzhubu.top/Article/details/gt2ygsmtgpd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pengpengdd.cyou/Article/details/gt2pnpldrmd.html

Ruby: threads.map(&:join)
来源：http://dali.xinyue.icu/Article/details/gt2ywfcprhv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ehwqpu.com/Article/details/gt2orgbqttd.html

[O06] 使用进程池
来源：http://dali.quarkkingdee.top/Article/details/gt2nmzeqkxf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tanke756.top/Article/details/gt2slkxwvps.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xinyue.icu/Article/details/gt2ijuvhumg.html

JS:   // child_process / cluster 模块
来源：http://dali.zhoulong.xyz/Article/details/gt2hialreme.html

TS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gt2ugewwmol.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenlongwang.top/Article/details/gt2ncjmgbvd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinqigufen.top/Article/details/gt2rfjwcdqj.html

Ruby: // fork 块
来源：http://dali.xuetiantiany.cn/Article/details/gt2xhxydocj.html

C#:   Parallel.For
来源：http://dali.jlsjyb.cn/Article/details/gt2wmykexgl.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2llpqnzbo.html

P. 常用工具函数
来源：http://dali.tanke756.top/Article/details/gt2icokmbga.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2gmoihhhx.html

[P01] 生成 UUID
来源：http://dali.guannengcc.top/Article/details/gt2yjdyxywn.html

Py:   str(uuid.uuid4())
来源：http://dali.jiagoushi.top/Article/details/gt2kbtibhxu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.316326.xyz/Article/details/gt2ounusvyh.html

JS:   crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gt2cpmpqjay.html

TS:   crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gt2ihypksxb.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258.top/Article/details/gt2axbiyigv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yangfankeji.com/Article/details/gt2owajdply.html

Ruby: SecureRandom.uuid
来源：http://dali.tianlin.xyz/Article/details/gt2nalwzutr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gotoacloud.top/Article/details/gt2cfnrbnzk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hammf.cn/Article/details/gt2emfekllv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yangfankeji.com/Article/details/gt2vpbltruw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.iojbl.cn/Article/details/gt2claiclta.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gzhubu.top/Article/details/gt2fqquxkkq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yangfankeji.com/Article/details/gt2qikbqwtq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gogol.net.cn/Article/details/gt2ifukzpro.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.316326.xyz/Article/details/gt2plsjkpxh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xylfe.cn/Article/details/gt2zcaippme.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ybcxt.top/Article/details/gt2isbeaast.html

[P03] 生成短随机字符串
来源：http://dali.yj20258.top/Article/details/gt2javlktbx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ybcxt.top/Article/details/gt2bielzjez.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgufenzy.top/Article/details/gt2gqytlglv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gt2qbldxkei.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gt2fiudrqai.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.snrcjt.cn/Article/details/gt2mmfccbia.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhoulong.xyz/Article/details/gt2ykuswtph.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ydzc1.top/Article/details/gt2rtqprcqb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gzhubu.top/Article/details/gt2yeoagtfb.html

[P04] 求长度
来源：http://dali.nwbrower.top/Article/details/gt2zxgiappe.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ydzc1.top/Article/details/gt2wtkemiiu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gt2biywvcmh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shuidangran.top/Article/details/gt2apzqdlwl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cdnleiting.top/Article/details/gt2zdzhrmfs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gt2habgziiq.html

Go:   len(arr);  len(m)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nvcsasdv.html

Ruby: x.length;  x.size
来源：http://dali.jianghu66.top/Article/details/gt2fzbbjjuj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jiagoushi.top/Article/details/gt2ijjxapbl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gaohongyu789.top/Article/details/gt2bnpebamn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.snrcjt.cn/Article/details/gt2gbmxhjqr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vsgdybal.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rgwlchpk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gt2zhgnrkmw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sfmgsaic.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.mhx1999.top/Article/details/gt2ugkcwshw.html

Ruby: a == b
来源：http://dali.gzhubu.top/Article/details/gt2amehmtar.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cdnleiting.top/Article/details/gt2vfhgvdzp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yueranfly.top/Article/details/gt2yllgoelq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.svipenyu.cn/Article/details/gt2nxzbdcga.html

PHP:  if (empty($x)) {}
来源：http://dali.jyoumei.cn/Article/details/gt2mwjwmvns.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.redwolf501.top/Article/details/gt2qidmjiae.html

TS:   if (x == null) {}
来源：http://dali.yuxming.cn/Article/details/gt2vhfpyhnt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gt2samzbfky.html

Go:   if x == nil {}
来源：http://dali.yj20258888.top/Article/details/gt2agpxctxn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ivvv.top/Article/details/gt2tdameefm.html

C#:   if (x is null) {}
来源：http://dali.zhixingplan.top/Article/details/gt2pblmhsnq.html

[P07] 防抖与节流
来源：http://dali.nanxuanxn.top/Article/details/gt2gmclbena.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yanxiufei.cn/Article/details/gt2wmlctack.html

PHP:  // 手写时间戳比较
来源：http://dali.yj202588.top/Article/details/gt2ufbmaacf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gt2xmuztczi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gt2elfqbqez.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ypdvnrkc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ehwqpu.com/Article/details/gt2nqliikmf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhoulong.xyz/Article/details/gt2qtsgdbmw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenjidiqi.icu/Article/details/gt2rrydfzxa.html

[P08] 处理浮点精度问题
来源：http://dali.hysaishi.cn/Article/details/gt2bucfqwwy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ddyfpxwt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vyvmmthv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cdnleiting.top/Article/details/gt2fexcqjjn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yongpay.top/Article/details/gt2fdfdmusv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258.top/Article/details/gt2vurvmjqp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pbwwsmao.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ybcxt.top/Article/details/gt2lfaezkbd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jiagoushi.top/Article/details/gt2rkycfbzw.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2kywrcacl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.9152youxi.cn/Article/details/gt2nqziypsx.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2okpjbyrp.html

[Q01] 创建表
来源：http://dali.yj202588.top/Article/details/gt2mlzfohxt.html

CREATE TABLE users (
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vxkjggjv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yueranfly.top/Article/details/gt2mdtnbera.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhongyouzk.top/Article/details/gt2skiyjion.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuanzhike.top/Article/details/gt2rtubisld.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yueranfly.top/Article/details/gt2gpqrwyxv.html

);
来源：http://dali.yj202588.top/Article/details/gt2fvkeijre.html

[Q02] 创建带外键的表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2odkblbim.html

CREATE TABLE orders (
来源：http://dali.hnxiangtu.top/Article/details/gt2fmsgaefl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sxryk.cn/Article/details/gt2zavrftto.html

user_id INT NOT NULL,
来源：http://dali.zhiwuduotai.top/Article/details/gt2jmjgpruv.html

amount DECIMAL(10, 2),
来源：http://dali.zdqjudy.top/Article/details/gt2deihecdn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cucudq.cn/Article/details/gt2dhehfixi.html

);
来源：http://dali.yj20258888.top/Article/details/gt2edvbanxf.html

[Q03] 增加列
来源：http://dali.jinqigfzy.top/Article/details/gt2bvdrcsuf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.birdmap.top/Article/details/gt2haaoaclm.html

[Q04] 修改列类型
来源：http://dali.zycfv.cn/Article/details/gt2uhiedqne.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.havefunace.top/Article/details/gt2drtapokd.html

[Q05] 重命名列
来源：http://dali.ehwqpu.com/Article/details/gt2zozvyihs.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jianghu66.top/Article/details/gt2rchzliac.html

[Q06] 删除列
来源：http://dali.ppjwa.cn/Article/details/gt2bzduvnyp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.316326.xyz/Article/details/gt2bcalagrl.html

[Q07] 删除表
来源：http://dali.hongshengwenyu.top/Article/details/gt2nsdfdskt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.haohaochexian.top/Article/details/gt2slndouaa.html

[Q08] 创建普通索引
来源：http://dali.yj202588.top/Article/details/gt2tlelzhfu.html


<!-- 参考信息 -->