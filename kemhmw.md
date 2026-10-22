代发 wailian999

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gtxutgcmsa.html

JS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gtdqbluctt.html

TS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gtlcexvqzq.html

Java: System.err.println("err")
来源：http://dali.yj202588.top/Article/details/gtjndrxxup.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangdashe.top/Article/details/gtkkpfqlxn.html

Ruby: warn "err"
来源：http://dali.nanxinkj.top/Article/details/gtfvjftioc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.kuanghao11.cn/Article/details/gtckihgdqd.html

[M07] 判断是否为主入口
来源：http://dali.shuidangran.top/Article/details/gtxqybhjlu.html

Py:   if __name__ == "__main__":
来源：http://dali.tian-w.cn/Article/details/gtrykvmxkn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbjfwhkc.html

JS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gtqkctetck.html

TS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gtfjwrpxml.html

Java: public static void main(String[] args)
来源：http://dali.nanxinkj.top/Article/details/gtzbcmjzku.html

Go:   func main()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnedctceb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhongyouzk.top/Article/details/gtmbspdzos.html

C#:   static void Main(string[] args)
来源：http://dali.jyoumei.cn/Article/details/gtpfsphrnc.html

[M08] 获取系统与运行时信息
来源：http://dali.gaohongyu789.top/Article/details/gttdwyfrbc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gaohongyu789.top/Article/details/gtmhsrjpae.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cdnleiting.top/Article/details/gtigilyzfk.html

JS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gtqrmlfehu.html

TS:   process.platform;  process.version
来源：http://dali.yuxming.cn/Article/details/gtxrnbpiwm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sufxvd.cn/Article/details/gtatqdgkaf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgfzy.top/Article/details/gtsvfmdlsn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sufxvd.cn/Article/details/gtqbrzcjhk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjgigria.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtyipdnqyd.html

N. 数据结构与算法
来源：http://dali.havefunace.top/Article/details/gtlteedwhc.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgavjpmr.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmskeejxd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtcbdkjjcv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.pycfn.com/Article/details/gtqthfujwj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gtgzvsbiic.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gtyytnepuv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gttzxwpgrd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtalyvztkn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuanzhike.top/Article/details/gtjaojvewp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gthzrlhfcl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hysaishi.cn/Article/details/gtvrvuphqd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gtayidoxhl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sweek.top/Article/details/gtjmehvmsq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gtyruzoqho.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gtlwhuwqtv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fengsongda.top/Article/details/gtxktgqwzn.html

Go:   slices.Sort(arr)
来源：http://dali.daria6918.cn/Article/details/gteacmyorr.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gtnpyemguz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.redwolf501.top/Article/details/gtuaslrtlx.html

[N03] 快速排序（分治示例）
来源：http://dali.hnqzz.top/Article/details/gtjsnhzyym.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guowangkeji.top/Article/details/gthjdfkhss.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxuanxn.top/Article/details/gtuaaypfzs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gtdanfzolj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gtydbcnhcn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gzhubu.top/Article/details/gtvncxfumx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhoulong.xyz/Article/details/gtbnplbcua.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuetiantiany.cn/Article/details/gtthnmdjps.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxuanxn.top/Article/details/gtdllmvhxm.html

[N04] 斐波那契数列
来源：http://dali.haohaochexian.top/Article/details/gtecmhgwzx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gtilqlkvyr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gtkylpurvg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gtxwplbckp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gtjcfdcmyi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gtzpzxuwld.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hywenlv.cn/Article/details/gtioxgogmm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.fengsongda.top/Article/details/gtzgbrhwwv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtghiosxzp.html

[N05] 最大公约数
来源：http://dali.fengsongda.top/Article/details/gtofaiahwu.html

Py:   math.gcd(a, b)
来源：http://dali.yonumen.top/Article/details/gtndiyzamd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxuanxn.top/Article/details/gtwggqfmql.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtyiryfhhw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxinkj.top/Article/details/gtewuxzpcz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sxryk.cn/Article/details/gtqijlgtzq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmmhediu.html

Ruby: a.gcd(b)
来源：http://dali.hfpthk.cn/Article/details/gtoxpmkpun.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xuanzx.com/Article/details/gtdhewiscp.html

[N06] 判断回文字符串
来源：http://dali.svipenyu.cn/Article/details/gtclpfxbvc.html

Py:   s == s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gthouyqgda.html

PHP:  $s === strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtbercrrbg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtmlselhqr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtpqjgslrs.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhengqikj.top/Article/details/gtyrvwmeri.html

Go:   // 双指针从两端比较
来源：http://dali.yvedp.cn/Article/details/gtssemwizf.html

Ruby: s == s.reverse
来源：http://dali.cqqwz.cn/Article/details/gtzotxpnxx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gttzornwos.html

[N07] 两数之和（返回下标）
来源：http://dali.shzxlz.cn/Article/details/gtwyrcmhyp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fengsongda.top/Article/details/gtvivanwnk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fzhhl.top/Article/details/gtlahxixwb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.andypj.xyz/Article/details/gtnycamvdw.html

TS:   // 手写 Map<string, number>
来源：http://dali.pengpengdd.cyou/Article/details/gttjpzqfrn.html

Java: // 手写 HashMap
来源：http://dali.cheryme.top/Article/details/gtmezskzby.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigufen.top/Article/details/gtpgfnlbsw.html

Ruby: // 手写 Hash
来源：http://dali.daria6918.cn/Article/details/gthhfohyyd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yvedp.cn/Article/details/gtawwiksyb.html

[N08] 生成全排列
来源：http://dali.yueranfly.top/Article/details/gtvgmqbkdq.html

Py:   itertools.permutations(arr)
来源：http://dali.hfpthk.cn/Article/details/gttuxzwjhx.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzskkobws.html

JS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtmzbzogez.html

TS:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtrytcfpce.html

Java: // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtfoqprzku.html

Go:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtemsphmqe.html

Ruby: arr.permutation.to_a
来源：http://dali.havefunace.top/Article/details/gtlkxrbaef.html

C#:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtteqjkwro.html

[N09] 栈与队列
来源：http://dali.meibo888.top/Article/details/gtymiieipc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tanke756.top/Article/details/gtjwotmwfi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sweek.top/Article/details/gtqctstvcb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtaeniczui.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hfpthk.cn/Article/details/gtaiwhuifa.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxinkj.top/Article/details/gttbxljrto.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pycfn.com/Article/details/gtzbvzsedq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbswkrxkf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gzhubu.top/Article/details/gtpkoosyzw.html

[N10] 链表节点定义
来源：http://dali.cheryme.top/Article/details/gtbilijbxg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cdnleiting.top/Article/details/gtwoeeflhf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnqzz.top/Article/details/gtdvlbdpwf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangdashe.top/Article/details/gtdmpdwyvq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hammf.cn/Article/details/gticwqcayu.html

Java: class Node { int v; Node next; }
来源：http://dali.chenzaomai.com/Article/details/gtaeommtvf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cqqwz.cn/Article/details/gtqbtvbfjm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cashguo.top/Article/details/gtcbpvriws.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.meibo888.top/Article/details/gtsvqjuxyj.html

[N11] 二叉树中序遍历
来源：http://dali.shzxlz.cn/Article/details/gtczhxnhic.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hywenlv.cn/Article/details/gthehrqehy.html

PHP:  // 手写递归函数
来源：http://dali.jianghu66.top/Article/details/gtvtanuvyn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gtxlkbrutm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tanke756.top/Article/details/gtqjpuunul.html

Java: // 手写递归
来源：http://dali.yongpay.top/Article/details/gtqsuztjhz.html

Go:   // 手写递归
来源：http://dali.sweek.top/Article/details/gttnqqfjjo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yvedp.cn/Article/details/gtuaalewpj.html

C#:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gtvrkseuhr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fzhhl.top/Article/details/gtsauoqjta.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.redwolf501.top/Article/details/gtaernlwgr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jyoumei.cn/Article/details/gtfclafdxe.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gtobncvmvn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuanzx.com/Article/details/gtfwyqcsxh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigufen.top/Article/details/gtihtoylek.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.meibo888.top/Article/details/gtpilvzvod.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shuidangran.top/Article/details/gtrbjsrrrf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gtormaofxp.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtotqaphkq.html

O. 并发与异步
来源：http://dali.cashguo.top/Article/details/gtiantenio.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtdnopzzog.html

[O01] 启动一个线程
来源：http://dali.xinyue.icu/Article/details/gtpuuzmmka.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fengsongda.top/Article/details/gtratmjodd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.mhx1999.top/Article/details/gtbmcwvhiz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ydzc1.top/Article/details/gtxouechaj.html

TS:   // 同 JS
来源：http://dali.ppjwa.cn/Article/details/gtonnedmfo.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenlongwang.top/Article/details/gtxqfrgkns.html

Go:   go f()
来源：http://dali.xinyue.icu/Article/details/gtsiknlhao.html

Ruby: Thread.new { f }
来源：http://dali.jqgfzy.top/Article/details/gtcfansfxe.html

C#:   Task.Run(() => F());
来源：http://dali.tian-w.cn/Article/details/gtsbeglajr.html

[O02] 使用线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwzjfuxe.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hammf.cn/Article/details/gtdbifqvnx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.bjfxy.top/Article/details/gtykxprjio.html

JS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gtcxwaeels.html

TS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gtwvwvbeaf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hnqzz.top/Article/details/gtonkisqpu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zdqjudy.top/Article/details/gtbfgjpylj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ivvv.top/Article/details/gtubpkmctz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guannengcc.top/Article/details/gtzxnrfjvp.html

[O03] 加锁保护共享数据
来源：http://dali.dashuyun.cn/Article/details/gtecccxvqn.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtquzqfepg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sweek.top/Article/details/gtbhzcmlbo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.snrcjt.cn/Article/details/gtqwmrnwxo.html

TS:   // 同 JS
来源：http://dali.c1oappe.top/Article/details/gtoivjplir.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmviycjgv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shanyushiyangtech.top/Article/details/gtepvivqyx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlifrrxwv.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gthitfmply.html

[O04] 定义异步函数并等待
来源：http://dali.xinyue.icu/Article/details/gterpptnss.html

Py:   async def f():⏎    await g()
来源：http://dali.316326.xyz/Article/details/gtmwdycybp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yanxiufei.cn/Article/details/gtqnwtnmjd.html

JS:   async function f() { await g(); }
来源：http://dali.smart0.xyz/Article/details/gtartzdxyj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gtlvynirdy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gzhubu.top/Article/details/gtgyjkkoiw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jianghu66.top/Article/details/gtyigbvuth.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnqzz.top/Article/details/gtonyxloli.html

C#:   async Task F() { await G(); }
来源：http://dali.nwbrower.top/Article/details/gtjagbomnr.html

[O05] 并发执行并等待全部完成
来源：http://dali.xylfe.cn/Article/details/gthoocgpyg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhixingplan.top/Article/details/gtttsrddph.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tanke756.top/Article/details/gtxvtxglkn.html

JS:   await Promise.all(tasks)
来源：http://dali.fengsongda.top/Article/details/gtfxlzirwe.html

TS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gtemvftyiz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cashguo.top/Article/details/gtjgppxixe.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.meibo888.top/Article/details/gtrklmveug.html

Ruby: threads.map(&:join)
来源：http://dali.wangshuangyany.cn/Article/details/gtjvoywohr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnqzz.top/Article/details/gtzgscbdaw.html

[O06] 使用进程池
来源：http://dali.xinyue.icu/Article/details/gttyiheaai.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigufen.top/Article/details/gtjtidwdor.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.birdmap.top/Article/details/gtjjjqirzl.html

JS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gtdhsxzanv.html

TS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gtmeqncahb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gtldtkkyzh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gotoacloud.top/Article/details/gtpjcjqhzs.html

Ruby: // fork 块
来源：http://dali.yj20258.top/Article/details/gtgasyulms.html

C#:   Parallel.For
来源：http://dali.shzxlz.cn/Article/details/gtvwuusqah.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtspcrfsgq.html

P. 常用工具函数
来源：http://dali.hysaishi.cn/Article/details/gtpltpxruk.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtfewkvdej.html

[P01] 生成 UUID
来源：http://dali.shuidangran.top/Article/details/gtieqljyqn.html

Py:   str(uuid.uuid4())
来源：http://dali.bjfxy.top/Article/details/gtroomkqcs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jyoumei.cn/Article/details/gtnxuckzyf.html

JS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gtxosiksgp.html

TS:   crypto.randomUUID()
来源：http://dali.nanxuanxn.top/Article/details/gteofixtzw.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnxiangtu.top/Article/details/gtgxzpmezv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfgypcmr.html

Ruby: SecureRandom.uuid
来源：http://dali.zycfv.cn/Article/details/gtsjcsjyki.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xinyue.icu/Article/details/gtzysjodnb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuxming.cn/Article/details/gtyravxqtv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangdashe.top/Article/details/gtackjcoix.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yueranfly.top/Article/details/gtgvducfjx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhongyouzk.top/Article/details/gtwlhtxrav.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigfzy.top/Article/details/gtygjsagli.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.snrcjt.cn/Article/details/gtjimribpy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.meibo888.top/Article/details/gtshaxuyvv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ivvv.top/Article/details/gtwzadonub.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.haohaochexian.top/Article/details/gtxlxcoews.html

[P03] 生成短随机字符串
来源：http://dali.gotoacloud.top/Article/details/gtorprsohk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhixingplan.top/Article/details/gtsioexrpj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xinyue.icu/Article/details/gtvfjoiweo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gtuziiroph.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gthoeyhspc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xziqi.cn/Article/details/gtaaeybgwd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hysaishi.cn/Article/details/gtoefqhbov.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.vqdsnc.cn/Article/details/gtdywjpgwh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tanke756.top/Article/details/gtouwpgwku.html

[P04] 求长度
来源：http://dali.pycfn.com/Article/details/gtnnwgwmrg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.c1oappe.top/Article/details/gtgkekfykj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtwpipjztx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gtmjcnrkxj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gtfqgsqwav.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhengqikj.top/Article/details/gtuwpqfmau.html

Go:   len(arr);  len(m)
来源：http://dali.guowangkeji.top/Article/details/gtyjnhsizu.html

Ruby: x.length;  x.size
来源：http://dali.zhiwuduotai.top/Article/details/gtculsfqax.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhixingplan.top/Article/details/gtzuavonma.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shanyushiyangkeji.top/Article/details/gtznkafoht.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gogol.net.cn/Article/details/gteokcmkqz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yuxming.cn/Article/details/gtnzvwiobt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuxming.cn/Article/details/gtaqryirlg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cucudq.cn/Article/details/gthaesbwds.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sysykeji.top/Article/details/gtosewjsju.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtmokvosfu.html

Ruby: a == b
来源：http://dali.jinqigfzy.top/Article/details/gtyohnkjtd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jiagoushi.top/Article/details/gtuoswfgna.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.vqdsnc.cn/Article/details/gtbchuakys.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvzwjodu.html

PHP:  if (empty($x)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddhpbswh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnqzz.top/Article/details/gtkplojuho.html

TS:   if (x == null) {}
来源：http://dali.chenzaomai.com/Article/details/gtrxatxmuh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jlsjyb.cn/Article/details/gtgtrflmzz.html

Go:   if x == nil {}
来源：http://dali.shzxlz.cn/Article/details/gtbxrqonau.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhengqikj.top/Article/details/gtzaaemxtr.html

C#:   if (x is null) {}
来源：http://dali.jqgufenzy.top/Article/details/gtnvvidflt.html

[P07] 防抖与节流
来源：http://dali.andypj.xyz/Article/details/gticugxlau.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ydzc1.top/Article/details/gtfnszqmty.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigfzy.top/Article/details/gtqyxwxhwv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gthfkevkpu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gtytpatewm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgufenzy.top/Article/details/gtiggrvzys.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hammf.cn/Article/details/gthcceshwd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.birdmap.top/Article/details/gtlzuxvzgx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfoplvaqk.html

[P08] 处理浮点精度问题
来源：http://dali.wangshuangyany.cn/Article/details/gtnomhtzyj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ybcxt.top/Article/details/gtsxaubjvq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gogol.net.cn/Article/details/gtnanjwadp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.wangdashe.top/Article/details/gtqoerkuwc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.quarkkingdee.top/Article/details/gtzniipruk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gogol.net.cn/Article/details/gtkudejhqi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenjidiqi.icu/Article/details/gtjmsvyela.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cucudq.cn/Article/details/gtdpuwwrfx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yongpay.top/Article/details/gtgqxxfayj.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtqndmpoat.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.tanke756.top/Article/details/gtflgdtcub.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtdutlfiih.html

[Q01] 创建表
来源：http://dali.kuanghao11.cn/Article/details/gtssetjaam.html

CREATE TABLE users (
来源：http://dali.jinqigfzy.top/Article/details/gtnnsgqnou.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gtymxgpfsv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yangfankeji.com/Article/details/gtoopsoxsf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenjidiqi.icu/Article/details/gtutvxanep.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrzbusio.html

);
来源：http://dali.mhx1999.top/Article/details/gtbqfeklrp.html

[Q02] 创建带外键的表
来源：http://dali.jlsjyb.cn/Article/details/gtsxajjydu.html

CREATE TABLE orders (
来源：http://dali.xziqi.cn/Article/details/gtzxeyjfdt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.c1oappe.top/Article/details/gtomxvwsoo.html

user_id INT NOT NULL,
来源：http://dali.chenzaomai.com/Article/details/gtgtvtlnlc.html

amount DECIMAL(10, 2),
来源：http://dali.xziqi.cn/Article/details/gtesebyuvj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yanxiufei.cn/Article/details/gtrsoanhzq.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gtnwlnmfwz.html

[Q03] 增加列
来源：http://dali.cashguo.top/Article/details/gtkjwfjwnu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yanxiufei.cn/Article/details/gtbccykudp.html

[Q04] 修改列类型
来源：http://dali.gogol.net.cn/Article/details/gtepaffawk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258888.top/Article/details/gtmacrhuif.html

[Q05] 重命名列
来源：http://dali.fengsongda.top/Article/details/gtczpdadmi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gzhubu.top/Article/details/gtlnwjctwx.html

[Q06] 删除列
来源：http://dali.xuetiantiany.cn/Article/details/gtkyogqugj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hnxiangtu.top/Article/details/gtmdgsgvuu.html

[Q07] 删除表
来源：http://dali.dashuyun.cn/Article/details/gtkfmbbjzu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.guowangkeji.top/Article/details/gtofmzoecd.html

[Q08] 创建普通索引
来源：http://dali.yonumen.top/Article/details/gtmiribwmh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzuvsbaoe.html

[Q09] 创建唯一索引
来源：http://dali.yj202588.top/Article/details/gtnrbcxqtj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gtbwzeqtfq.html

[Q10] 插入单行
来源：http://dali.hammf.cn/Article/details/gtajrvvgzf.html


<!-- 参考信息 -->