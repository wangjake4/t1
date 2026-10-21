代发 wailian999

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yongpay.top/Article/details/gtgbfryqzx.html

JS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gtnepdgptr.html

TS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gthyknacau.html

Java: System.err.println("err")
来源：http://dali.zdqjudy.top/Article/details/gtxfayalhy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yanxiufei.cn/Article/details/gtmlbsxfcd.html

Ruby: warn "err"
来源：http://dali.hywenlv.cn/Article/details/gttimlstlt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbvdykej.html

[M07] 判断是否为主入口
来源：http://dali.jlsjyb.cn/Article/details/gtjophitue.html

Py:   if __name__ == "__main__":
来源：http://dali.hywenlv.cn/Article/details/gtxkvlkofc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zycfv.cn/Article/details/gtbamqekwm.html

JS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gtmviumftj.html

TS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gtackzqbcr.html

Java: public static void main(String[] args)
来源：http://dali.hysaishi.cn/Article/details/gtdhedjojv.html

Go:   func main()
来源：http://dali.ivvv.top/Article/details/gtjwditngx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cqqwz.cn/Article/details/gtxpnavkkc.html

C#:   static void Main(string[] args)
来源：http://dali.cheryme.top/Article/details/gtylmlhxcg.html

[M08] 获取系统与运行时信息
来源：http://dali.ybcxt.top/Article/details/gtnsdimhlb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xylfe.cn/Article/details/gtsexqyucq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gotoacloud.top/Article/details/gtdhjlrvaw.html

JS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgtjyrol.html

TS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtgnvhrhlc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gtdjfnsyea.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aizwys.cn/Article/details/gttbbxgtia.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.andypj.xyz/Article/details/gtepfqnxkj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aibaodan.cn/Article/details/gtfiohgmjz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtrlvbomih.html

N. 数据结构与算法
来源：http://dali.xylfe.cn/Article/details/gtcdevilkj.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtandftmmc.html

[N01] 二分查找（有序数组）
来源：http://dali.sysykeji.top/Article/details/gtihlpvzsc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtbsgcljum.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cashguo.top/Article/details/gtaiwyabne.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gtsyizzvqp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gtdzbipkej.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtaldbhoxm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtboctsayd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gogol.net.cn/Article/details/gtcnwurjca.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtlhvacvoa.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ydzc1.top/Article/details/gtufudgnyn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gtenbdetqw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuanzhike.top/Article/details/gtzsxrfqpo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gtqptayqbz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gtypebnczs.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xylfe.cn/Article/details/gtscwpaweh.html

Go:   slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gtiojnlqxc.html

Ruby: arr.sort
来源：http://dali.shzxlz.cn/Article/details/gtpjjqjkin.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ydzc1.top/Article/details/gtrxufqhgg.html

[N03] 快速排序（分治示例）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgxwxnxw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.feifeiyinyue.top/Article/details/gtwbfspjvz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangtech.top/Article/details/gtohudgfur.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gtyhnkoike.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipyllfle.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmaapayd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.svipenyu.cn/Article/details/gtzecearvk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.feifeiyinyue.top/Article/details/gtwxibtgtk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.quarkkingdee.top/Article/details/gtocpoujuf.html

[N04] 斐波那契数列
来源：http://dali.hywenlv.cn/Article/details/gtldfgnlqm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gtdekzifqh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gtkdmkwrsu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gttnbqrdjl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtragpzptp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gotoacloud.top/Article/details/gtsfzapoza.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ivvv.top/Article/details/gtfztpmhuv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.0kj1m.cn/Article/details/gtklrxqvcw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gthngxizli.html

[N05] 最大公约数
来源：http://dali.0kj1m.cn/Article/details/gtjodbkqjy.html

Py:   math.gcd(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtwoqcwjmm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hammf.cn/Article/details/gtgaxyyhdb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shuidangran.top/Article/details/gtwujbbgvx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnqzz.top/Article/details/gtikujrkvc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.meibo888.top/Article/details/gtwpfiydxp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jiagoushi.top/Article/details/gtixwxpecl.html

Ruby: a.gcd(b)
来源：http://dali.yuanzhike.top/Article/details/gtsuwlwftx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yangfankeji.com/Article/details/gtdsjjzzxj.html

[N06] 判断回文字符串
来源：http://dali.guowangkeji.top/Article/details/gtsbyzoojf.html

Py:   s == s[::-1]
来源：http://dali.jianghu66.top/Article/details/gtrgtqgcta.html

PHP:  $s === strrev($s);
来源：http://dali.ehwqpu.com/Article/details/gtcqsqvilj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtbhoafrmr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtcurydwuo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cashguo.top/Article/details/gtehepglmc.html

Go:   // 双指针从两端比较
来源：http://dali.yonumen.top/Article/details/gtsghqbwox.html

Ruby: s == s.reverse
来源：http://dali.aizwys.cn/Article/details/gtesguxwsz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gtuxrewdgz.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gtarhxzqli.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yvedp.cn/Article/details/gtmrnnnyfi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jyoumei.cn/Article/details/gtvnjndtkg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gogol.net.cn/Article/details/gtchjiksoz.html

TS:   // 手写 Map<string, number>
来源：http://dali.sxryk.cn/Article/details/gtgfonohxk.html

Java: // 手写 HashMap
来源：http://dali.cucudq.cn/Article/details/gtjctvzwnu.html

Go:   // 手写 map[int]int
来源：http://dali.hnqzz.top/Article/details/gtilshyzbt.html

Ruby: // 手写 Hash
来源：http://dali.hnxiangtu.top/Article/details/gtwvxjijse.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cqqwz.cn/Article/details/gtkrfacdrs.html

[N08] 生成全排列
来源：http://dali.yongpay.top/Article/details/gttdpqussq.html

Py:   itertools.permutations(arr)
来源：http://dali.zycfv.cn/Article/details/gtudwarmdq.html

PHP:  // 手写递归交换
来源：http://dali.jiagoushi.top/Article/details/gtbgadkkio.html

JS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtxdffytxa.html

TS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvvjkouv.html

Java: // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtqmzkkwvw.html

Go:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtohdjjhqz.html

Ruby: arr.permutation.to_a
来源：http://dali.aizwys.cn/Article/details/gtojcrqeik.html

C#:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtrhxbndrb.html

[N09] 栈与队列
来源：http://dali.meibo888.top/Article/details/gtotucinea.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxinkj.top/Article/details/gtvwyfpsrw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yueranfly.top/Article/details/gtbmvihmzm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtarqvlurw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cqqwz.cn/Article/details/gtexynqxzs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daxiang520.top/Article/details/gtzqaqqdre.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcoxwlrp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gtosuraqim.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gtawrcjpun.html

[N10] 链表节点定义
来源：http://dali.zycfv.cn/Article/details/gtbbephfuf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sxryk.cn/Article/details/gtakgdogov.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.andypj.xyz/Article/details/gtdyzlnhpy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xylfe.cn/Article/details/gtpkpbmuew.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhoulong.xyz/Article/details/gtattxvuqr.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258888.top/Article/details/gttlrujktq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ivvv.top/Article/details/gtrwcqdvec.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tianlin.xyz/Article/details/gtseswdvxi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daxiang520.top/Article/details/gtqhmwzhsv.html

[N11] 二叉树中序遍历
来源：http://dali.sufxvd.cn/Article/details/gtfhltqvek.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhongyouzk.top/Article/details/gtfevvtggp.html

PHP:  // 手写递归函数
来源：http://dali.yvedp.cn/Article/details/gtybmpguhj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gtsmuwhxyx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pengpengdd.cyou/Article/details/gtjxgnpbir.html

Java: // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gthoqpeley.html

Go:   // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gtslrfvkte.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhiwuduotai.top/Article/details/gtxenrsqsv.html

C#:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gttygluezt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtkyipfczr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.andypj.xyz/Article/details/gtilmffvuh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gzhubu.top/Article/details/gtjtveaani.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtnzsikisd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gtqwruqlhi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.birdmap.top/Article/details/gtnvgqwysv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yongpay.top/Article/details/gthdrfpdil.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.316326.xyz/Article/details/gtqpdngkgj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gtgjmrzmnw.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtggmjgopt.html

O. 并发与异步
来源：http://dali.hongshengwenyu.top/Article/details/gtgdennqta.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtabkmytav.html

[O01] 启动一个线程
来源：http://dali.chenzaomai.com/Article/details/gtpvqqnzep.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilnqeiyn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shzxlz.cn/Article/details/gtrofbfewk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cucudq.cn/Article/details/gthieojuty.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gtuakaibwv.html

Java: new Thread(() -> f()).start()
来源：http://dali.316326.xyz/Article/details/gtkluxwmqb.html

Go:   go f()
来源：http://dali.yonumen.top/Article/details/gtucdezbub.html

Ruby: Thread.new { f }
来源：http://dali.snrcjt.cn/Article/details/gtxaqzetcq.html

C#:   Task.Run(() => F());
来源：http://dali.pengpengdd.cyou/Article/details/gtllylopgs.html

[O02] 使用线程池
来源：http://dali.jianghu66.top/Article/details/gtmvlyrugk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cdnleiting.top/Article/details/gtjrlgaxfn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenjidiqi.icu/Article/details/gtlxwltjtb.html

JS:   // worker_threads 线程池
来源：http://dali.hnqzz.top/Article/details/gtwjwzxufj.html

TS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gtrcjzsoxm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cucudq.cn/Article/details/gtczjunjpa.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgufenzy.top/Article/details/gtgowfbqfc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.c1oappe.top/Article/details/gthgvjzzvf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgotjhxl.html

[O03] 加锁保护共享数据
来源：http://dali.hnqzz.top/Article/details/gtreuziobn.html

Py:   with lock: shared += 1
来源：http://dali.smart0.xyz/Article/details/gttejezaeo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aibaodan.cn/Article/details/gtbsrianki.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.haohaochexian.top/Article/details/gtrhlbrzcr.html

TS:   // 同 JS
来源：http://dali.yuanzhike.top/Article/details/gtovornaar.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gtvlfjyznq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dianchejie.cn/Article/details/gtfxlznspf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gtpiqjidoj.html

C#:   lock (gate) { shared++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtuixtqtww.html

[O04] 定义异步函数并等待
来源：http://dali.yvedp.cn/Article/details/gtxcpwhvqb.html

Py:   async def f():⏎    await g()
来源：http://dali.vqdsnc.cn/Article/details/gtioimgbpg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhiwuduotai.top/Article/details/gtrtrcnkin.html

JS:   async function f() { await g(); }
来源：http://dali.dashuyun.cn/Article/details/gtbbbpmrzu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gtpcfbwidd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenzaomai.com/Article/details/gtybwyxafk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hnqzz.top/Article/details/gtgifncdzf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenzaomai.com/Article/details/gtwctsqkww.html

C#:   async Task F() { await G(); }
来源：http://dali.tanke756.top/Article/details/gtehkvjnpx.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgufenzy.top/Article/details/gtyseqcpnb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nwbrower.top/Article/details/gtlvjjptxl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daxiang520.top/Article/details/gtlbpovvuj.html

JS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gtubxvrexo.html

TS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtagjeklbc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.birdmap.top/Article/details/gtnfwulhsa.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nwbrower.top/Article/details/gtyqgbztxm.html

Ruby: threads.map(&:join)
来源：http://dali.yonumen.top/Article/details/gtzolujgmo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.haohaochexian.top/Article/details/gtbsawnnfe.html

[O06] 使用进程池
来源：http://dali.meibo888.top/Article/details/gtfrgayvrx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nanxuanxn.top/Article/details/gtofojftgz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hongshengwenyu.top/Article/details/gtwqvrdtmk.html

JS:   // child_process / cluster 模块
来源：http://dali.yvedp.cn/Article/details/gtcbdojumm.html

TS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gtlgtuuopw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.vqdsnc.cn/Article/details/gtamwdnhpf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gotoacloud.top/Article/details/gtfsdnhocn.html

Ruby: // fork 块
来源：http://dali.xuanzx.com/Article/details/gtlpaxkcme.html

C#:   Parallel.For
来源：http://dali.jianghu66.top/Article/details/gtevunpjdl.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gttpdwubiq.html

P. 常用工具函数
来源：http://dali.chenjidiqi.icu/Article/details/gtmrzfpwmz.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtyinqlcvz.html

[P01] 生成 UUID
来源：http://dali.zdqjudy.top/Article/details/gtuncmpkrj.html

Py:   str(uuid.uuid4())
来源：http://dali.zhiwuduotai.top/Article/details/gtrctzlrok.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hywenlv.cn/Article/details/gtvhfxerir.html

JS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gtivxryxce.html

TS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gtpvgjngfl.html

Java: UUID.randomUUID().toString()
来源：http://dali.hfpthk.cn/Article/details/gtgzcgrrqk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guannengcc.top/Article/details/gtkjnkiqpw.html

Ruby: SecureRandom.uuid
来源：http://dali.svipenyu.cn/Article/details/gtfxqempvc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cucudq.cn/Article/details/gtlyovwqbd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tian-w.cn/Article/details/gtzzfghrld.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenjidiqi.icu/Article/details/gtbsxtevtj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dashuyun.cn/Article/details/gtummwuwyj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ydzc1.top/Article/details/gtlmvyxhmt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.havefunace.top/Article/details/gtadizwvqe.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtjefqzwgi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgufenzy.top/Article/details/gtndkbitgf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhoulong.xyz/Article/details/gtbztmnsmf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuetiantiany.cn/Article/details/gthxorrxlj.html

[P03] 生成短随机字符串
来源：http://dali.cashguo.top/Article/details/gtlntaeumf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkaazwad.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuxming.cn/Article/details/gtygwioxvo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtmcgdknim.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gtkxowjqou.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tianlin.xyz/Article/details/gtlfnhxqnb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guannengcc.top/Article/details/gttzhsbefp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hfpthk.cn/Article/details/gtmqzyvrhp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jlsjyb.cn/Article/details/gtfflvemuo.html

[P04] 求长度
来源：http://dali.vqdsnc.cn/Article/details/gtjzxvtlaj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.birdmap.top/Article/details/gtpydwapjn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtlorvdhjn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gtzfszsqcu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gtizduqyat.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tianlin.xyz/Article/details/gtanbeyldq.html

Go:   len(arr);  len(m)
来源：http://dali.haohaochexian.top/Article/details/gtqszudhcy.html

Ruby: x.length;  x.size
来源：http://dali.yanxiufei.cn/Article/details/gtstecceel.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj20258.top/Article/details/gtgdvlsxpw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenjidiqi.icu/Article/details/gtupzlqpsh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shangyingyoupin.top/Article/details/gtdjvtcufa.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nanxinkj.top/Article/details/gtowaxngvh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zycfv.cn/Article/details/gtasixfisj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hywenlv.cn/Article/details/gtmqdytpzw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.daxiang520.top/Article/details/gtyzaudgfc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.guannengcc.top/Article/details/gtsgzdwjmz.html

Ruby: a == b
来源：http://dali.hongshengwenyu.top/Article/details/gtlqisjolo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.kuanghao11.cn/Article/details/gtczxkythg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yueranfly.top/Article/details/gtarksbygc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj20258888.top/Article/details/gtdjeneoec.html

PHP:  if (empty($x)) {}
来源：http://dali.zhoulong.xyz/Article/details/gtejqvdsvy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258.top/Article/details/gtnbfsoaek.html

TS:   if (x == null) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtunmrgwvc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gtpxkdvbsh.html

Go:   if x == nil {}
来源：http://dali.chenlongwang.top/Article/details/gtoiitxgtw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shuidangran.top/Article/details/gtradetanb.html

C#:   if (x is null) {}
来源：http://dali.guowangkeji.top/Article/details/gttzejzlhn.html

[P07] 防抖与节流
来源：http://dali.jinqigufen.top/Article/details/gtxufbupnv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhengqikj.top/Article/details/gtasxsowqi.html

PHP:  // 手写时间戳比较
来源：http://dali.aibaodan.cn/Article/details/gtoqcubuzs.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtrsswbgmn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtxwdeetkv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.redwolf501.top/Article/details/gtuxhhjnck.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zdqjudy.top/Article/details/gtpetagxrd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sysykeji.top/Article/details/gtxijivext.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tianlin.xyz/Article/details/gtkqkgqxsq.html

[P08] 处理浮点精度问题
来源：http://dali.kuanghao11.cn/Article/details/gtoqnxgqbq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pengpengdd.cyou/Article/details/gtdkqvhlud.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigufen.top/Article/details/gtciixotvw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hnqzz.top/Article/details/gtbbcljjvd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gaohongyu789.top/Article/details/gtysvszhup.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangshuangyany.cn/Article/details/gtnwhaimuq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hfpthk.cn/Article/details/gtjojoncyf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhengqikj.top/Article/details/gtofsqawrl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.svipenyu.cn/Article/details/gthpdprntn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjddnxqnj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guannengcc.top/Article/details/gtnxruovhm.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtgmxrupbf.html

[Q01] 创建表
来源：http://dali.jinqigufen.top/Article/details/gtbyroxwex.html

CREATE TABLE users (
来源：http://dali.c1oappe.top/Article/details/gtqtpklmlq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gtzzsvsisn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gtwsmogmkb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tian-w.cn/Article/details/gtuhgvjsrr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.smart0.xyz/Article/details/gtqrhrirzl.html

);
来源：http://dali.vqdsnc.cn/Article/details/gtefwfnebe.html

[Q02] 创建带外键的表
来源：http://dali.gzhubu.top/Article/details/gtlpggeqcu.html

CREATE TABLE orders (
来源：http://dali.shuidangran.top/Article/details/gtdjnndnlk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gthadylrjm.html

user_id INT NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gthuxmpbkw.html

amount DECIMAL(10, 2),
来源：http://dali.xziqi.cn/Article/details/gtttigjsvk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hysaishi.cn/Article/details/gtmbyzekln.html

);
来源：http://dali.smart0.xyz/Article/details/gtodstvmom.html

[Q03] 增加列
来源：http://dali.sufxvd.cn/Article/details/gtasbbebuf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.kuanghao11.cn/Article/details/gtvbvmnfal.html

[Q04] 修改列类型
来源：http://dali.sxryk.cn/Article/details/gttyrvyrzc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.dashuyun.cn/Article/details/gttwkfabki.html

[Q05] 重命名列
来源：http://dali.gotoacloud.top/Article/details/gtmcyiboey.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangtech.top/Article/details/gthywijduw.html

[Q06] 删除列
来源：http://dali.sxryk.cn/Article/details/gtstrqmxqe.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhoulong.xyz/Article/details/gtjtypzcta.html

[Q07] 删除表
来源：http://dali.yuanzhike.top/Article/details/gtdzjzzyga.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gogol.net.cn/Article/details/gtbbecbytr.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaiabxznk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtryykiudx.html

[Q09] 创建唯一索引
来源：http://dali.bjfxy.top/Article/details/gtapsoyihk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.havefunace.top/Article/details/gtniplgdca.html

[Q10] 插入单行
来源：http://dali.nanxinkj.top/Article/details/gtgfzvuuhy.html


<!-- 参考信息 -->