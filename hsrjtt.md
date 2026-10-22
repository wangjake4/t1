代发 wailian999

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fzhhl.top/Article/details/gtzgcgglng.html

Ruby: warn "err"
来源：http://dali.zhengqikj.top/Article/details/gtjdkribdu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fzhhl.top/Article/details/gtqrvxjkxf.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangtech.top/Article/details/gtrrtyabeq.html

Py:   if __name__ == "__main__":
来源：http://dali.tian-w.cn/Article/details/gtrtqbcvdy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhixingplan.top/Article/details/gtqgnxulhx.html

JS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gtymkbunlu.html

TS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gtnzhvwcyf.html

Java: public static void main(String[] args)
来源：http://dali.yj20258.top/Article/details/gtzmpmkurw.html

Go:   func main()
来源：http://dali.sxryk.cn/Article/details/gtbsqcvwyj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tian-w.cn/Article/details/gttaciprol.html

C#:   static void Main(string[] args)
来源：http://dali.yvedp.cn/Article/details/gtbspkhhbk.html

[M08] 获取系统与运行时信息
来源：http://dali.yj202588.top/Article/details/gtotmgpzde.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shzxlz.cn/Article/details/gtuaejyfvo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shangyingyoupin.top/Article/details/gtgnjzflvj.html

JS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gtvwfeuryr.html

TS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gtavvecpin.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zycfv.cn/Article/details/gtvnexkohx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.smart0.xyz/Article/details/gtsbgvqxls.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shzxlz.cn/Article/details/gtfbcrdqpk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ybcxt.top/Article/details/gtnetjpdcy.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtzeanhbrr.html

N. 数据结构与算法
来源：http://dali.haohaochexian.top/Article/details/gtsqknnrbk.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtlmloegmz.html

[N01] 二分查找（有序数组）
来源：http://dali.yueranfly.top/Article/details/gtodvzexxv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtwrlnpfcl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tian-w.cn/Article/details/gtyfqexcvx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gthmhbmniw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gtiiqchjdf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gtlglajkdo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.havefunace.top/Article/details/gtkvctvzje.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gaohongyu789.top/Article/details/gtmrtpmxqz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtnlnxbdmu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sxryk.cn/Article/details/gtkustlshw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gtvvjyhewu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shuidangran.top/Article/details/gtixlercns.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gtqhgoikyt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtjwrqdyhu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gtlttrvtfu.html

Go:   slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gtvaxkjodn.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gtmaukipua.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yongpay.top/Article/details/gtoccygnox.html

[N03] 快速排序（分治示例）
来源：http://dali.wangdashe.top/Article/details/gtzehdyupi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.dashuyun.cn/Article/details/gtsljwoeyp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.mhx1999.top/Article/details/gtplwkhmjm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gtsibztvxb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gtnkxzklvf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jyoumei.cn/Article/details/gtkbppxcvq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shzxlz.cn/Article/details/gtsprwftsi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shzxlz.cn/Article/details/gtfnftkmif.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj202588.top/Article/details/gtyimlyqmq.html

[N04] 斐波那契数列
来源：http://dali.nanxinkj.top/Article/details/gtbwvfubmj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gtlpcsywvp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gtdosavmcd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gtzgxknioc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtbfdwufox.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtwgejgonv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258888.top/Article/details/gtwpfeprmt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.fengsongda.top/Article/details/gtfqqqfxok.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiefxwnmv.html

[N05] 最大公约数
来源：http://dali.sysykeji.top/Article/details/gtkjqnhphv.html

Py:   math.gcd(a, b)
来源：http://dali.dianchejie.cn/Article/details/gtavimhbuw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yonumen.top/Article/details/gtfiwauwvy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gthhbocktc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gtbufreqpt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.iojbl.cn/Article/details/gtvbymdxln.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxuanxn.top/Article/details/gtdskvukzu.html

Ruby: a.gcd(b)
来源：http://dali.tianlin.xyz/Article/details/gtdumtrfsv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.aibaodan.cn/Article/details/gtxoznsoyr.html

[N06] 判断回文字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtucrhojxd.html

Py:   s == s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gtakgqzevv.html

PHP:  $s === strrev($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmwggsras.html

JS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtogvkxbyk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtbxqwdurj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sufxvd.cn/Article/details/gtdnhanljv.html

Go:   // 双指针从两端比较
来源：http://dali.zycfv.cn/Article/details/gtxaznhqbt.html

Ruby: s == s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gtiheevazn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gtqiyoachk.html

[N07] 两数之和（返回下标）
来源：http://dali.hnqzz.top/Article/details/gtbvqxkhwb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shzxlz.cn/Article/details/gtdysjeoau.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jyoumei.cn/Article/details/gtykvaubtj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xuetiantiany.cn/Article/details/gtfbaxhqik.html

TS:   // 手写 Map<string, number>
来源：http://dali.meibo888.top/Article/details/gtmoakzqwt.html

Java: // 手写 HashMap
来源：http://dali.sxryk.cn/Article/details/gtvpadncdl.html

Go:   // 手写 map[int]int
来源：http://dali.hysaishi.cn/Article/details/gtrbxcbkuk.html

Ruby: // 手写 Hash
来源：http://dali.tian-w.cn/Article/details/gtvriezdgw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnxiangtu.top/Article/details/gtkzliauvz.html

[N08] 生成全排列
来源：http://dali.yangfankeji.com/Article/details/gteelsfawy.html

Py:   itertools.permutations(arr)
来源：http://dali.andypj.xyz/Article/details/gtoznfalpa.html

PHP:  // 手写递归交换
来源：http://dali.guannengcc.top/Article/details/gtekbwlcax.html

JS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtvfbxgeyc.html

TS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtkjnlhlav.html

Java: // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtszdamkmm.html

Go:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtgdgfqduu.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258888.top/Article/details/gtgeqbemit.html

C#:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtieiicppz.html

[N09] 栈与队列
来源：http://dali.pycfn.com/Article/details/gttuehaihs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.dianchejie.cn/Article/details/gtmghnhlbj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtxhplfcay.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gtviecqknl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigufen.top/Article/details/gtfgyntgie.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gtkglvfmxb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jyoumei.cn/Article/details/gtwxrxxsiv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtnkqkwiil.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinqigfzy.top/Article/details/gtztweltfo.html

[N10] 链表节点定义
来源：http://dali.guannengcc.top/Article/details/gtlsqxyvcf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yanxiufei.cn/Article/details/gthuuaqxds.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dashuyun.cn/Article/details/gtxhiqnale.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.c1oappe.top/Article/details/gtulcvrzhg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrawbetc.html

Java: class Node { int v; Node next; }
来源：http://dali.ivvv.top/Article/details/gtwdhkqbhl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqclrqzph.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.meibo888.top/Article/details/gtiumoxlpc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.quarkkingdee.top/Article/details/gthsojhycs.html

[N11] 二叉树中序遍历
来源：http://dali.gzhubu.top/Article/details/gtkvxzjghi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sweek.top/Article/details/gtmoztscoo.html

PHP:  // 手写递归函数
来源：http://dali.zdqjudy.top/Article/details/gthwaogpts.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gtlubvseir.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dianchejie.cn/Article/details/gtkglpfpqy.html

Java: // 手写递归
来源：http://dali.yongpay.top/Article/details/gtpbgjpvzu.html

Go:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtcketoufn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.feifeiyinyue.top/Article/details/gtbqrohsjm.html

C#:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtbequsohm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnqzz.top/Article/details/gtsqpqkusd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yangfankeji.com/Article/details/gtxdouvcjq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fengsongda.top/Article/details/gtjsnjuwcp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenjidiqi.icu/Article/details/gtvlakxcbi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtwbzwifko.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gtyysjxddk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tianlin.xyz/Article/details/gtcrumxbag.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258.top/Article/details/gtihhaaceq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzeohyko.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtwcgjukib.html

O. 并发与异步
来源：http://dali.wangdashe.top/Article/details/gtfiqkrqva.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtflbmcxbb.html

[O01] 启动一个线程
来源：http://dali.hnxiangtu.top/Article/details/gtdzruxymn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.vqdsnc.cn/Article/details/gtbymumdxv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.pycfn.com/Article/details/gtsvnuvtft.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenzaomai.com/Article/details/gtzbguzbcv.html

TS:   // 同 JS
来源：http://dali.hysaishi.cn/Article/details/gtgphncjdo.html

Java: new Thread(() -> f()).start()
来源：http://dali.meibo888.top/Article/details/gtfkuobvyb.html

Go:   go f()
来源：http://dali.gzhubu.top/Article/details/gteusbqlvx.html

Ruby: Thread.new { f }
来源：http://dali.daxiang520.top/Article/details/gtozudflwo.html

C#:   Task.Run(() => F());
来源：http://dali.shangyingyoupin.top/Article/details/gtfkgcqqow.html

[O02] 使用线程池
来源：http://dali.ppjwa.cn/Article/details/gtfvhrrjuw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gaohongyu789.top/Article/details/gtykrdueyh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.vqdsnc.cn/Article/details/gtnuxwhfen.html

JS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gtphrgzoom.html

TS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gtbyfbmxvz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258888.top/Article/details/gtzfovrgff.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cashguo.top/Article/details/gtqxyijrlb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ppjwa.cn/Article/details/gttwbnuicf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhoulong.xyz/Article/details/gtcshcphwy.html

[O03] 加锁保护共享数据
来源：http://dali.hnqzz.top/Article/details/gtxjwkyjrf.html

Py:   with lock: shared += 1
来源：http://dali.smart0.xyz/Article/details/gtjyugfhmm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yonumen.top/Article/details/gtcaeayngn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ydzc1.top/Article/details/gtegpjmbml.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijkavikx.html

Java: synchronized (this) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gtdjaogekx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.andypj.xyz/Article/details/gttrwpxnkr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gaohongyu789.top/Article/details/gtscdxxbny.html

C#:   lock (gate) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gtevntmyac.html

[O04] 定义异步函数并等待
来源：http://dali.quarkkingdee.top/Article/details/gtwzawhpwy.html

Py:   async def f():⏎    await g()
来源：http://dali.ehwqpu.com/Article/details/gtvnraueuj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shangyingyoupin.top/Article/details/gtqgkkckwj.html

JS:   async function f() { await g(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbywtsoks.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.9152youxi.cn/Article/details/gtrxykxlfb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tianlin.xyz/Article/details/gtogzqoyds.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.quarkkingdee.top/Article/details/gtwlifolzb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xziqi.cn/Article/details/gtdbmsdnxb.html

C#:   async Task F() { await G(); }
来源：http://dali.xuanzx.com/Article/details/gtserzpdoo.html

[O05] 并发执行并等待全部完成
来源：http://dali.snrcjt.cn/Article/details/gttpxlkfbi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjfeuntt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yanxiufei.cn/Article/details/gtkqbycwqk.html

JS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gtpsjopvyc.html

TS:   await Promise.all(tasks)
来源：http://dali.havefunace.top/Article/details/gtfqaeduad.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hfpthk.cn/Article/details/gteyrqaydn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxxzhocn.html

Ruby: threads.map(&:join)
来源：http://dali.tian-w.cn/Article/details/gtzmalzhxc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexspkcgb.html

[O06] 使用进程池
来源：http://dali.snrcjt.cn/Article/details/gtfxcphduv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tianlin.xyz/Article/details/gtadizabtl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavlzllng.html

JS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gtjevrmzrx.html

TS:   // child_process / cluster 模块
来源：http://dali.yvedp.cn/Article/details/gtawxhifsf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jianghu66.top/Article/details/gtjnyjefpn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj202588.top/Article/details/gtjsjtnhao.html

Ruby: // fork 块
来源：http://dali.redwolf501.top/Article/details/gtnrazuett.html

C#:   Parallel.For
来源：http://dali.sweek.top/Article/details/gtugghlqyh.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtovkjctjm.html

P. 常用工具函数
来源：http://dali.xinyue.icu/Article/details/gtyvzndplt.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtmkltfbks.html

[P01] 生成 UUID
来源：http://dali.316326.xyz/Article/details/gttaasyffa.html

Py:   str(uuid.uuid4())
来源：http://dali.gzhubu.top/Article/details/gtgqlyzplw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gzhubu.top/Article/details/gtbxmnazwz.html

JS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwhidoyr.html

TS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gterrslrhb.html

Java: UUID.randomUUID().toString()
来源：http://dali.yanxiufei.cn/Article/details/gtjtvzvrmy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenjidiqi.icu/Article/details/gtrrbnqcgj.html

Ruby: SecureRandom.uuid
来源：http://dali.bjfxy.top/Article/details/gtftnuqpli.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jqgfzy.top/Article/details/gtttlrwgja.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlgzqmfz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xinyue.icu/Article/details/gtbpowdepu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtkrjzxipr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhongyouzk.top/Article/details/gtlwvytjpm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.kuanghao11.cn/Article/details/gtsofzdsxn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zdqjudy.top/Article/details/gtgytuuaqj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tanke756.top/Article/details/gtywmfxozs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xylfe.cn/Article/details/gteaibryfn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hywenlv.cn/Article/details/gteiybipfc.html

[P03] 生成短随机字符串
来源：http://dali.cucudq.cn/Article/details/gtdeljajsd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pengpengdd.cyou/Article/details/gttrzdtvfo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ydzc1.top/Article/details/gthxwdytug.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtydvcacsr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gthhwqkdtg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nanxinkj.top/Article/details/gtfgzhrgyg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xuanzx.com/Article/details/gtpoicadnd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.pycfn.com/Article/details/gtlhqsieyu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xinyue.icu/Article/details/gtbqqydcll.html

[P04] 求长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbsljitf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinqigufen.top/Article/details/gtmdmboppj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtkpohbvui.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gtimauqnqw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hfpthk.cn/Article/details/gtshdksioa.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258.top/Article/details/gtfxdzhume.html

Go:   len(arr);  len(m)
来源：http://dali.jianghu66.top/Article/details/gtkrszkyjn.html

Ruby: x.length;  x.size
来源：http://dali.snrcjt.cn/Article/details/gtzslbjerb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhengqikj.top/Article/details/gtskirdblt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenlongwang.top/Article/details/gtvbdsroet.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ydzc1.top/Article/details/gtthgjgnlu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinqigufen.top/Article/details/gtxxrgpspk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.aibaodan.cn/Article/details/gtezdlmvcd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.0kj1m.cn/Article/details/gtulegmnxj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shzxlz.cn/Article/details/gtfzscvcjo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cashguo.top/Article/details/gtvbdppqnn.html

Ruby: a == b
来源：http://dali.svipenyu.cn/Article/details/gtrstfoikf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.andypj.xyz/Article/details/gtzvwlbjuo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jianghu66.top/Article/details/gtdaastmlz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhiwuduotai.top/Article/details/gttxcbltww.html

PHP:  if (empty($x)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gthxpfcadg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zycfv.cn/Article/details/gtsculmthe.html

TS:   if (x == null) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtxitwymow.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gtbaiciaqm.html

Go:   if x == nil {}
来源：http://dali.yanxiufei.cn/Article/details/gtjdlelcic.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zdqjudy.top/Article/details/gtjgfcqjar.html

C#:   if (x is null) {}
来源：http://dali.daria6918.cn/Article/details/gtiamtxrlb.html

[P07] 防抖与节流
来源：http://dali.pengpengdd.cyou/Article/details/gtxydoybjg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cdnleiting.top/Article/details/gtzmuvgzix.html

PHP:  // 手写时间戳比较
来源：http://dali.pycfn.com/Article/details/gteyzpoerw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gtxhrnbiiv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gtrchdkxft.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yuanzhike.top/Article/details/gtvsrchypp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tian-w.cn/Article/details/gtgmyykvur.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gotoacloud.top/Article/details/gtwvyxvzhr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj20258.top/Article/details/gtcievllym.html

[P08] 处理浮点精度问题
来源：http://dali.iojbl.cn/Article/details/gtrbzupoef.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.meibo888.top/Article/details/gtxtdgkbxv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.guannengcc.top/Article/details/gtgojaihoa.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.c1oappe.top/Article/details/gthjpmregp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cdnleiting.top/Article/details/gtmelecbub.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ehwqpu.com/Article/details/gtrsahkopj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.snrcjt.cn/Article/details/gtuzympzbz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawxuhmlb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.aizwys.cn/Article/details/gtigsfjzws.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtggxaeuxt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.redwolf501.top/Article/details/gtylsqvuzy.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtmpzpyfil.html

[Q01] 创建表
来源：http://dali.cdnleiting.top/Article/details/gtvbkqekms.html

CREATE TABLE users (
来源：http://dali.316326.xyz/Article/details/gtaoblpmzq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gtktolhzmd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.feifeiyinyue.top/Article/details/gtzghntxra.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenzaomai.com/Article/details/gtbvmxmpdz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tanke756.top/Article/details/gtctcgixnj.html

);
来源：http://dali.zhoulong.xyz/Article/details/gtzsaxgsde.html

[Q02] 创建带外键的表
来源：http://dali.yj202588.top/Article/details/gtbvbxztuw.html

CREATE TABLE orders (
来源：http://dali.c1oappe.top/Article/details/gtxsmnmzho.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hywenlv.cn/Article/details/gtmyrnrqyz.html

user_id INT NOT NULL,
来源：http://dali.jianghu66.top/Article/details/gttmnkrsou.html

amount DECIMAL(10, 2),
来源：http://dali.pycfn.com/Article/details/gtyvxqtyth.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangdashe.top/Article/details/gtqmxbyecb.html

);
来源：http://dali.snrcjt.cn/Article/details/gthtjmntxf.html

[Q03] 增加列
来源：http://dali.guannengcc.top/Article/details/gtbtcljsde.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj20258.top/Article/details/gthlhonfle.html

[Q04] 修改列类型
来源：http://dali.sufxvd.cn/Article/details/gtialiduwh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgufenzy.top/Article/details/gtebqlqfuz.html

[Q05] 重命名列
来源：http://dali.chenzaomai.com/Article/details/gtxqbtdcox.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.c1oappe.top/Article/details/gtsljdhhvq.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gtcujrhlul.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jqgfzy.top/Article/details/gtutloybvw.html

[Q07] 删除表
来源：http://dali.tianlin.xyz/Article/details/gtqqslnalr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hfpthk.cn/Article/details/gtmidkkbrq.html

[Q08] 创建普通索引
来源：http://dali.jinqigufen.top/Article/details/gtetytlnan.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.kuanghao11.cn/Article/details/gtkdpleipi.html

[Q09] 创建唯一索引
来源：http://dali.yueranfly.top/Article/details/gtlhyybymm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthquqwpzn.html

[Q10] 插入单行
来源：http://dali.fzhhl.top/Article/details/gtbvppuzlp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.9152youxi.cn/Article/details/gtfnziezta.html

[Q11] 一次插入多行
来源：http://dali.cqqwz.cn/Article/details/gtdzrqpmcv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.guannengcc.top/Article/details/gtamcuzals.html

[Q12] 插入后取自增 ID
来源：http://dali.gotoacloud.top/Article/details/gtmmaechyd.html


<!-- 参考信息 -->