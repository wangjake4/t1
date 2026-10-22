代发 wailian999

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhoulong.xyz/Article/details/gtxkbhbcka.html

Ruby: warn "err"
来源：http://dali.shuidangran.top/Article/details/gtinjpheki.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hfpthk.cn/Article/details/gtefuaqsef.html

[M07] 判断是否为主入口
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcwqming.html

Py:   if __name__ == "__main__":
来源：http://dali.wangdashe.top/Article/details/gtwadiiiyj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgfdoogb.html

JS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gtljhizqrl.html

TS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gtgghroygy.html

Java: public static void main(String[] args)
来源：http://dali.gogol.net.cn/Article/details/gtxhmqajhe.html

Go:   func main()
来源：http://dali.yonumen.top/Article/details/gtiohtrpqa.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhoulong.xyz/Article/details/gtwgflxbzj.html

C#:   static void Main(string[] args)
来源：http://dali.ehwqpu.com/Article/details/gtcrhlpefm.html

[M08] 获取系统与运行时信息
来源：http://dali.0kj1m.cn/Article/details/gtqtngcfpm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tian-w.cn/Article/details/gtlnlwafjs.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhengqikj.top/Article/details/gtgyytfkbb.html

JS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gtnphtqgcg.html

TS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivkfhijn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.svipenyu.cn/Article/details/gtfclsbnyb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhongyouzk.top/Article/details/gtnchgmxqv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yvedp.cn/Article/details/gtvulpjhdc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.vqdsnc.cn/Article/details/gtmmgpvers.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtdwqzetcw.html

N. 数据结构与算法
来源：http://dali.ybcxt.top/Article/details/gtrelemkfd.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtudkgewgh.html

[N01] 二分查找（有序数组）
来源：http://dali.tianlin.xyz/Article/details/gtznvoslfd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtikbdolfl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjkdnlsmi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtxtnzaxzi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gtoxkmnuam.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtsghcieuj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtmbsdqqif.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xziqi.cn/Article/details/gtxaevlton.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtewailbbi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cheryme.top/Article/details/gtvqtctjet.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhiwuduotai.top/Article/details/gtrychzizr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuxming.cn/Article/details/gttlcgqeid.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gtsyfkvihg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtrabnwuhm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aibaodan.cn/Article/details/gtnvqnrmgu.html

Go:   slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gttihewdqw.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gtzynwtxyq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuanzx.com/Article/details/gtlfexfndx.html

[N03] 快速排序（分治示例）
来源：http://dali.birdmap.top/Article/details/gtlnvszdhg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.mhx1999.top/Article/details/gtkoqarwgp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gtoxacovla.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gogol.net.cn/Article/details/gtibnhhstk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gtmrrihchu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guannengcc.top/Article/details/gtwpzqjhzz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangdashe.top/Article/details/gtqhohtjnh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xziqi.cn/Article/details/gtpdwxrnxf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhoulong.xyz/Article/details/gtnhyfhvms.html

[N04] 斐波那契数列
来源：http://dali.meibo888.top/Article/details/gthsylmodh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nwbrower.top/Article/details/gtxqrvjhyp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gtlssrsgkk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtozcaxktc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gtmwzrtdar.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.iojbl.cn/Article/details/gtacqhvecf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jiagoushi.top/Article/details/gtztqypbzn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtqeqcgqlo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gttdddoity.html

[N05] 最大公约数
来源：http://dali.hywenlv.cn/Article/details/gttpxckeyf.html

Py:   math.gcd(a, b)
来源：http://dali.gotoacloud.top/Article/details/gtpbtospno.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xylfe.cn/Article/details/gtvflbclbi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gtfmkvmmta.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gtyiixyojj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xinyue.icu/Article/details/gtpktjjpoh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigufen.top/Article/details/gtcsvdypct.html

Ruby: a.gcd(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwtabsqi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shangyingyoupin.top/Article/details/gtsrnyacir.html

[N06] 判断回文字符串
来源：http://dali.zhoulong.xyz/Article/details/gtzuwjfkgb.html

Py:   s == s[::-1]
来源：http://dali.iojbl.cn/Article/details/gtpwlmalwl.html

PHP:  $s === strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gtwnriuewo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytliapxo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtqdvxpnbz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.c1oappe.top/Article/details/gtzteiogvx.html

Go:   // 双指针从两端比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcglwifvo.html

Ruby: s == s.reverse
来源：http://dali.zycfv.cn/Article/details/gtryssllbc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gtopvnkfer.html

[N07] 两数之和（返回下标）
来源：http://dali.yongpay.top/Article/details/gtjlozoumj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvegwroq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dianchejie.cn/Article/details/gtukdinbes.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgufenzy.top/Article/details/gtcuzmtuta.html

TS:   // 手写 Map<string, number>
来源：http://dali.gotoacloud.top/Article/details/gtpxvnyzuf.html

Java: // 手写 HashMap
来源：http://dali.daxiang520.top/Article/details/gttexsbgph.html

Go:   // 手写 map[int]int
来源：http://dali.daxiang520.top/Article/details/gtehvkourb.html

Ruby: // 手写 Hash
来源：http://dali.gaohongyu789.top/Article/details/gtnbyzrhug.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ppjwa.cn/Article/details/gtjupvzmcw.html

[N08] 生成全排列
来源：http://dali.feifeiyinyue.top/Article/details/gtuqkgaetg.html

Py:   itertools.permutations(arr)
来源：http://dali.gotoacloud.top/Article/details/gtofkpycfb.html

PHP:  // 手写递归交换
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqgauiek.html

JS:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtprbxrrrj.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtiditqytn.html

Java: // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtjeuhxaoe.html

Go:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtlwefqzov.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258888.top/Article/details/gtqqscytun.html

C#:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtcjllmcpz.html

[N09] 栈与队列
来源：http://dali.gzhubu.top/Article/details/gtvluwvxsh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tianlin.xyz/Article/details/gtfyrngiia.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj20258.top/Article/details/gthjjfwrxe.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtwximiqzd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guowangkeji.top/Article/details/gtmtuqzqmq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.meibo888.top/Article/details/gtyhbeihxu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pengpengdd.cyou/Article/details/gtygnakivg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gtfykbkvlk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.birdmap.top/Article/details/gtugpotyqb.html

[N10] 链表节点定义
来源：http://dali.hammf.cn/Article/details/gtiwpyhswt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ydzc1.top/Article/details/gtqjtmvpqy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbylnwaql.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigufen.top/Article/details/gtnsaeaomo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gtdndwhkxi.html

Java: class Node { int v; Node next; }
来源：http://dali.chenlongwang.top/Article/details/gtvdjvthar.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhongyouzk.top/Article/details/gteazuhvtc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cqqwz.cn/Article/details/gtzzszfmbj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sufxvd.cn/Article/details/gtiqwmijsr.html

[N11] 二叉树中序遍历
来源：http://dali.shangyingyoupin.top/Article/details/gterajinid.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gotoacloud.top/Article/details/gtbilhvkkh.html

PHP:  // 手写递归函数
来源：http://dali.zhongyouzk.top/Article/details/gtswwjxvjp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegtcmbap.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gtugmieims.html

Java: // 手写递归
来源：http://dali.fengsongda.top/Article/details/gtvxosgsfa.html

Go:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtwcvyvxsl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hammf.cn/Article/details/gtzkfsnkqk.html

C#:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gtdslrpwdo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.kuanghao11.cn/Article/details/gtocvupdgk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibluwkuq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xylfe.cn/Article/details/gtnbvtwfvc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ppjwa.cn/Article/details/gtkjhsvdmu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gtewnpftaf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gtobsccifq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aizwys.cn/Article/details/gticxvuymt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258.top/Article/details/gthclkduaa.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuanzx.com/Article/details/gtnuhtzieg.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtarnhwksq.html

O. 并发与异步
来源：http://dali.cashguo.top/Article/details/gtloomhvhl.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtrwryshek.html

[O01] 启动一个线程
来源：http://dali.yueranfly.top/Article/details/gtbdvzyabo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sufxvd.cn/Article/details/gtrfjyzyxa.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sweek.top/Article/details/gttdhbbvpi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jiagoushi.top/Article/details/gthxhhkmzf.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gtqpdhkxav.html

Java: new Thread(() -> f()).start()
来源：http://dali.hywenlv.cn/Article/details/gtcbzrkzqm.html

Go:   go f()
来源：http://dali.sxryk.cn/Article/details/gthhztjjfe.html

Ruby: Thread.new { f }
来源：http://dali.hongshengwenyu.top/Article/details/gtxdkqovuf.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigfzy.top/Article/details/gtbecgnmnp.html

[O02] 使用线程池
来源：http://dali.cdnleiting.top/Article/details/gtdnnqhnzn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gogol.net.cn/Article/details/gtpuvzjxvt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guannengcc.top/Article/details/gtfyisnefg.html

JS:   // worker_threads 线程池
来源：http://dali.zdqjudy.top/Article/details/gtmzthmtci.html

TS:   // worker_threads 线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjndbkwqq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ydzc1.top/Article/details/gtndcfyqtp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.mhx1999.top/Article/details/gtgfnrbinz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenjidiqi.icu/Article/details/gtimgnrdks.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nanxinkj.top/Article/details/gtpmqoesty.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigufen.top/Article/details/gtcsbzptqc.html

Py:   with lock: shared += 1
来源：http://dali.xylfe.cn/Article/details/gtqnxdvjzo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ppjwa.cn/Article/details/gtzaizswik.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pycfn.com/Article/details/gtylzwnhkl.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gtqeldzurf.html

Java: synchronized (this) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gtcazblshk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhengqikj.top/Article/details/gtyoldoial.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgufenzy.top/Article/details/gtgifffubk.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigfzy.top/Article/details/gtkgntonjl.html

[O04] 定义异步函数并等待
来源：http://dali.nanxinkj.top/Article/details/gtzyzeevvq.html

Py:   async def f():⏎    await g()
来源：http://dali.gzhubu.top/Article/details/gtzjuzykro.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xylfe.cn/Article/details/gtxdtqsrbr.html

JS:   async function f() { await g(); }
来源：http://dali.jqgufenzy.top/Article/details/gtgwbtgjzx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnqzz.top/Article/details/gtdeyqwgbs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.havefunace.top/Article/details/gtueyiylce.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.birdmap.top/Article/details/gtjvthsrhj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.aizwys.cn/Article/details/gtbnyqeinh.html

C#:   async Task F() { await G(); }
来源：http://dali.hnxiangtu.top/Article/details/gttlngwngw.html

[O05] 并发执行并等待全部完成
来源：http://dali.sxryk.cn/Article/details/gttjkzryqn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cdnleiting.top/Article/details/gtfwhkxocd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinqigfzy.top/Article/details/gtoselkzjs.html

JS:   await Promise.all(tasks)
来源：http://dali.fzhhl.top/Article/details/gtlqdixqxm.html

TS:   await Promise.all(tasks)
来源：http://dali.yanxiufei.cn/Article/details/gtvivkbkxk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.fzhhl.top/Article/details/gtyakadkgf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dashuyun.cn/Article/details/gtrkpdkivs.html

Ruby: threads.map(&:join)
来源：http://dali.sysykeji.top/Article/details/gtsudgpeec.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhiwuduotai.top/Article/details/gtvfimdwrt.html

[O06] 使用进程池
来源：http://dali.wangdashe.top/Article/details/gtwltdriag.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigfzy.top/Article/details/gtlcdduzrj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sufxvd.cn/Article/details/gtrkkkncnw.html

JS:   // child_process / cluster 模块
来源：http://dali.havefunace.top/Article/details/gtkuvylbcv.html

TS:   // child_process / cluster 模块
来源：http://dali.wangshuangyany.cn/Article/details/gtxnnwllxt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258.top/Article/details/gtikutzqif.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xuanzx.com/Article/details/gtoshxnsgj.html

Ruby: // fork 块
来源：http://dali.shanyushiyangtech.top/Article/details/gtrebmyubw.html

C#:   Parallel.For
来源：http://dali.chenlongwang.top/Article/details/gtllvfczpb.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtnilfgixt.html

P. 常用工具函数
来源：http://dali.yonumen.top/Article/details/gtrkkukbkp.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtbfxdxxia.html

[P01] 生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gtsxmjwdne.html

Py:   str(uuid.uuid4())
来源：http://dali.aibaodan.cn/Article/details/gtksullslv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gzhubu.top/Article/details/gtdabwqfbh.html

JS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gttnhfllid.html

TS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gtkknfkryy.html

Java: UUID.randomUUID().toString()
来源：http://dali.fzhhl.top/Article/details/gtowqqqqjm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gogol.net.cn/Article/details/gtkbsumisn.html

Ruby: SecureRandom.uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqonfikna.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jlsjyb.cn/Article/details/gtmcbfocze.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangdashe.top/Article/details/gtvpcxivgh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenjidiqi.icu/Article/details/gtbslkjszx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.feifeiyinyue.top/Article/details/gttqgtvqnf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sufxvd.cn/Article/details/gtguoumjde.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.daxiang520.top/Article/details/gtbtebjxlb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.316326.xyz/Article/details/gttcrdpsav.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daria6918.cn/Article/details/gtdccqsfrb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sxryk.cn/Article/details/gtnfajkouy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xylfe.cn/Article/details/gtomyrwuys.html

[P03] 生成短随机字符串
来源：http://dali.zhengqikj.top/Article/details/gthgcyovih.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.quarkkingdee.top/Article/details/gthbrsthcz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yueranfly.top/Article/details/gtpbzgobkg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmurdmsua.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gthsaiixkf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.smart0.xyz/Article/details/gtlyfbuxwi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jianghu66.top/Article/details/gtfgufpubg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuanzx.com/Article/details/gtnceiqawx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nanxinkj.top/Article/details/gtdqdywylj.html

[P04] 求长度
来源：http://dali.jianghu66.top/Article/details/gthxlbbsqm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tian-w.cn/Article/details/gtrjcqqvxf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtbdisgaxl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.quarkkingdee.top/Article/details/gtkbjofvdm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gtnbuqweeq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hammf.cn/Article/details/gtjmvhywhg.html

Go:   len(arr);  len(m)
来源：http://dali.zhixingplan.top/Article/details/gtfhgyqntd.html

Ruby: x.length;  x.size
来源：http://dali.fengsongda.top/Article/details/gtpcwyxmon.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sweek.top/Article/details/gtodchdlqd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zdqjudy.top/Article/details/gtbrpwdutd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenzaomai.com/Article/details/gtjblqzhxc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dashuyun.cn/Article/details/gtloytwfwp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tanke756.top/Article/details/gtrbgoqads.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwnlsjxl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hammf.cn/Article/details/gtgtrpsgpe.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ppjwa.cn/Article/details/gtrcwjxugd.html

Ruby: a == b
来源：http://dali.guowangkeji.top/Article/details/gtrwgfewgq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cashguo.top/Article/details/gtvddgyhqm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cheryme.top/Article/details/gttubytdfd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jlsjyb.cn/Article/details/gtsgtkmxtk.html

PHP:  if (empty($x)) {}
来源：http://dali.gaohongyu789.top/Article/details/gteiylujlq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guannengcc.top/Article/details/gtuigqkbgr.html

TS:   if (x == null) {}
来源：http://dali.nanxuanxn.top/Article/details/gtcqmpzaum.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gtsgimiojx.html

Go:   if x == nil {}
来源：http://dali.fengsongda.top/Article/details/gtjzdtrson.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yonumen.top/Article/details/gtzyorvubi.html

C#:   if (x is null) {}
来源：http://dali.ybcxt.top/Article/details/gttjntdomm.html

[P07] 防抖与节流
来源：http://dali.yj202588.top/Article/details/gtcuitbdtm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ppjwa.cn/Article/details/gtpvrxkanu.html

PHP:  // 手写时间戳比较
来源：http://dali.chenjidiqi.icu/Article/details/gtkyssdzdo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtmuyygqfp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gtknirdxgu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.pengpengdd.cyou/Article/details/gthyesrgxj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.mhx1999.top/Article/details/gtinjtaxwx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gaohongyu789.top/Article/details/gtmgxlxtit.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.quarkkingdee.top/Article/details/gthpeuivva.html

[P08] 处理浮点精度问题
来源：http://dali.yuanzhike.top/Article/details/gtaplxltwh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fengsongda.top/Article/details/gtijghffzj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hnxiangtu.top/Article/details/gtwpmgllhu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.kuanghao11.cn/Article/details/gtyugguall.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenlongwang.top/Article/details/gtuzhenpeq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangshuangyany.cn/Article/details/gtyxypfpbs.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cashguo.top/Article/details/gtnaydtsvk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.pycfn.com/Article/details/gtxbujszeg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xinyue.icu/Article/details/gtcptbvyos.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtpxqxqxid.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.tanke756.top/Article/details/gtxdexjeni.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtllbcyuve.html

[Q01] 创建表
来源：http://dali.nwbrower.top/Article/details/gtmmkmjtar.html

CREATE TABLE users (
来源：http://dali.shuidangran.top/Article/details/gtbxlozgea.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pengpengdd.cyou/Article/details/gtgcuwiodl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpodvuzwq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.guowangkeji.top/Article/details/gtmqcsdkce.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ppjwa.cn/Article/details/gtlwkmgxss.html

);
来源：http://dali.yangfankeji.com/Article/details/gtonzkdtej.html

[Q02] 创建带外键的表
来源：http://dali.yonumen.top/Article/details/gtwcpykfem.html

CREATE TABLE orders (
来源：http://dali.hysaishi.cn/Article/details/gtzgtqmadp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gtqhmmxcyn.html

user_id INT NOT NULL,
来源：http://dali.nwbrower.top/Article/details/gtzuczmtks.html

amount DECIMAL(10, 2),
来源：http://dali.cdnleiting.top/Article/details/gttshqmycb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhoulong.xyz/Article/details/gtygjeqrkh.html

);
来源：http://dali.jiagoushi.top/Article/details/gticnteqso.html

[Q03] 增加列
来源：http://dali.yangfankeji.com/Article/details/gtdcnwtotc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.dianchejie.cn/Article/details/gtwidvdqod.html

[Q04] 修改列类型
来源：http://dali.bjfxy.top/Article/details/gtrngkzwml.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj202588.top/Article/details/gtindogvip.html

[Q05] 重命名列
来源：http://dali.jinyuanbaomall.cn/Article/details/gteysihqfp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigfzy.top/Article/details/gtnqybedlr.html

[Q06] 删除列
来源：http://dali.xziqi.cn/Article/details/gtwoboeakh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yvedp.cn/Article/details/gtfttphjyg.html

[Q07] 删除表
来源：http://dali.shangyingyoupin.top/Article/details/gtbfpfelyb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cashguo.top/Article/details/gtkghfjwnk.html

[Q08] 创建普通索引
来源：http://dali.wangshuangyany.cn/Article/details/gtczyzyuse.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfpukoxq.html

[Q09] 创建唯一索引
来源：http://dali.xuanzx.com/Article/details/gthzeysbmi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hnxiangtu.top/Article/details/gtfgmheyyx.html

[Q10] 插入单行
来源：http://dali.kuanghao11.cn/Article/details/gtisfrqxxm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jianghu66.top/Article/details/gtjocwoqkj.html

[Q11] 一次插入多行
来源：http://dali.redwolf501.top/Article/details/gtnefipucm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtppbxkslz.html

[Q12] 插入后取自增 ID
来源：http://dali.zhiwuduotai.top/Article/details/gtjnbqfyox.html


<!-- 参考信息 -->