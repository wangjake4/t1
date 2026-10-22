代发 wailian999

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hywenlv.cn/Article/details/gtmtfojawp.html

JS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gttqexarhz.html

TS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gtdlftsbus.html

Java: System.err.println("err")
来源：http://dali.chenzaomai.com/Article/details/gttwzhajrp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxuanxn.top/Article/details/gtbjtrvlcy.html

Ruby: warn "err"
来源：http://dali.daria6918.cn/Article/details/gtivmcxqed.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shuidangran.top/Article/details/gtcyhjbqke.html

[M07] 判断是否为主入口
来源：http://dali.zhoulong.xyz/Article/details/gtynjaumzw.html

Py:   if __name__ == "__main__":
来源：http://dali.shzxlz.cn/Article/details/gtfzeeibor.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.kuanghao11.cn/Article/details/gtdtwhnktt.html

JS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gtfqrrmkuj.html

TS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gtricwjrzb.html

Java: public static void main(String[] args)
来源：http://dali.jyoumei.cn/Article/details/gtgtfliarn.html

Go:   func main()
来源：http://dali.yangfankeji.com/Article/details/gtydjrzmsq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgfzy.top/Article/details/gtmtayvkkl.html

C#:   static void Main(string[] args)
来源：http://dali.zycfv.cn/Article/details/gtsffzcjtv.html

[M08] 获取系统与运行时信息
来源：http://dali.xziqi.cn/Article/details/gtuoywdegq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnxiangtu.top/Article/details/gtmcdvglyx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.svipenyu.cn/Article/details/gtqvtpbeup.html

JS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gtyxoizryh.html

TS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gthsacbrfh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.havefunace.top/Article/details/gtznkkzwvi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sufxvd.cn/Article/details/gtdxkmabdk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhixingplan.top/Article/details/gtualgawjk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhengqikj.top/Article/details/gtdmhwbsxz.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtjuurmlyd.html

N. 数据结构与算法
来源：http://dali.yj20258.top/Article/details/gtneofohsm.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gteyqtwiyb.html

[N01] 二分查找（有序数组）
来源：http://dali.chenzaomai.com/Article/details/gtiopibhwc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtrnghrnym.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtxrkngpha.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxcxbnej.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gtsmdittrq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtnnygenur.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtuczogfld.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuanzx.com/Article/details/gthvprdlgc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtinetcsoj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gogol.net.cn/Article/details/gtyytknzcw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmviyowue.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cdnleiting.top/Article/details/gtisempjok.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gthgwwhslg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gtxbstllbn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hongshengwenyu.top/Article/details/gtdwkptyse.html

Go:   slices.Sort(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtglzmjpoz.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gtgxnbqlcl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gaohongyu789.top/Article/details/gthnwunddb.html

[N03] 快速排序（分治示例）
来源：http://dali.gaohongyu789.top/Article/details/gtfjrnpowt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tian-w.cn/Article/details/gtgrtsfhwu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangdashe.top/Article/details/gtbeolollo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.0kj1m.cn/Article/details/gtzmrxmuir.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gtbmdgpgui.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtkjskuwhr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hammf.cn/Article/details/gthkcmepvz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tian-w.cn/Article/details/gtmeqrjnnm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yuanzhike.top/Article/details/gtwnbjaysm.html

[N04] 斐波那契数列
来源：http://dali.hfpthk.cn/Article/details/gtghhjilom.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gttjwrclqm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gtzatrnuln.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtkxznfesv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtebrcmnqx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gtsexkntto.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fengsongda.top/Article/details/gtkxkcpveb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gttlgccbtb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gtjxshvleb.html

[N05] 最大公约数
来源：http://dali.jlsjyb.cn/Article/details/gtabzofaru.html

Py:   math.gcd(a, b)
来源：http://dali.yongpay.top/Article/details/gtfrnaxsik.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hysaishi.cn/Article/details/gtzkbxwlgu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gtxmtptjns.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gtahviukjn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258888.top/Article/details/gtzkddvqef.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yanxiufei.cn/Article/details/gtpovisuig.html

Ruby: a.gcd(b)
来源：http://dali.gaohongyu789.top/Article/details/gtwtbvtxhc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daria6918.cn/Article/details/gtgsaoqnrh.html

[N06] 判断回文字符串
来源：http://dali.gogol.net.cn/Article/details/gtwytehlws.html

Py:   s == s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gtmdvduegi.html

PHP:  $s === strrev($s);
来源：http://dali.redwolf501.top/Article/details/gtxlvawepo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtabfhtsqe.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtogivwexk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.fzhhl.top/Article/details/gtjlmbxadz.html

Go:   // 双指针从两端比较
来源：http://dali.xinyue.icu/Article/details/gtkkzdaxbe.html

Ruby: s == s.reverse
来源：http://dali.sxryk.cn/Article/details/gtqkpovkrn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gtdtkcyuov.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gthlygzlsa.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xuetiantiany.cn/Article/details/gthpixzeob.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cqqwz.cn/Article/details/gtlisldodw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.9152youxi.cn/Article/details/gtpiqurbcz.html

TS:   // 手写 Map<string, number>
来源：http://dali.daxiang520.top/Article/details/gticzglitl.html

Java: // 手写 HashMap
来源：http://dali.nanxuanxn.top/Article/details/gtnuwhftel.html

Go:   // 手写 map[int]int
来源：http://dali.aibaodan.cn/Article/details/gtdgtsmzsw.html

Ruby: // 手写 Hash
来源：http://dali.cheryme.top/Article/details/gtbigrheiw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinqigfzy.top/Article/details/gtkpcuugjp.html

[N08] 生成全排列
来源：http://dali.zdqjudy.top/Article/details/gtgtjmkgdv.html

Py:   itertools.permutations(arr)
来源：http://dali.xinyue.icu/Article/details/gtfhfbvval.html

PHP:  // 手写递归交换
来源：http://dali.gzhubu.top/Article/details/gthbpujjbz.html

JS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtsekvtmoe.html

TS:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtwbbzkths.html

Java: // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gttspcljzy.html

Go:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtoecexglx.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigfzy.top/Article/details/gtdpibyxxk.html

C#:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtywavjfup.html

[N09] 栈与队列
来源：http://dali.guowangkeji.top/Article/details/gtpascijkl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258.top/Article/details/gtudfywelh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.meibo888.top/Article/details/gtykjwmmca.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gtzqtwezmo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.birdmap.top/Article/details/gtewjlwolt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yangfankeji.com/Article/details/gtapajqzot.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pycfn.com/Article/details/gtvaxuujsc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtrlolylcf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinqigfzy.top/Article/details/gtcxdullka.html

[N10] 链表节点定义
来源：http://dali.wangdashe.top/Article/details/gtiprankfi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gaohongyu789.top/Article/details/gtuobkoval.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwudkfzrf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cqqwz.cn/Article/details/gtrwxpfriy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258888.top/Article/details/gteorrzafy.html

Java: class Node { int v; Node next; }
来源：http://dali.ydzc1.top/Article/details/gtqahpshjf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yueranfly.top/Article/details/gtnlgcpmdn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ehwqpu.com/Article/details/gtglansbzj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.guowangkeji.top/Article/details/gtjbveyrmo.html

[N11] 二叉树中序遍历
来源：http://dali.gaohongyu789.top/Article/details/gttdrwjjev.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sweek.top/Article/details/gtmcbjjysk.html

PHP:  // 手写递归函数
来源：http://dali.feifeiyinyue.top/Article/details/gtitjmxtfr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gtivpfpisb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gtcvvjxpml.html

Java: // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtvlrwjdts.html

Go:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gtccuetxne.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tanke756.top/Article/details/gtdnlxgmwv.html

C#:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtjeuvjlqm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzbsiqajm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.vqdsnc.cn/Article/details/gtjrhltpek.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.0kj1m.cn/Article/details/gtdxkplenf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenjidiqi.icu/Article/details/gtbefitlbj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.mhx1999.top/Article/details/gtljcrdkkc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gtxjmseotx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ydzc1.top/Article/details/gtdmjacaka.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258888.top/Article/details/gtvxbajgnm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.kuanghao11.cn/Article/details/gtkhthqyrs.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtaymssptc.html

O. 并发与异步
来源：http://dali.hywenlv.cn/Article/details/gtweltahwq.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtiqwagmjy.html

[O01] 启动一个线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafbdzncu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jqgufenzy.top/Article/details/gttzlkezwv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.mhx1999.top/Article/details/gtnvtghnvn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.c1oappe.top/Article/details/gtdidfmneg.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktbkxcpd.html

Java: new Thread(() -> f()).start()
来源：http://dali.0kj1m.cn/Article/details/gtxotimyax.html

Go:   go f()
来源：http://dali.0kj1m.cn/Article/details/gtsnspgijk.html

Ruby: Thread.new { f }
来源：http://dali.jqgufenzy.top/Article/details/gtoddynuvv.html

C#:   Task.Run(() => F());
来源：http://dali.shangyingyoupin.top/Article/details/gtnrqxrbvt.html

[O02] 使用线程池
来源：http://dali.jyoumei.cn/Article/details/gtogjlhjjo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhengqikj.top/Article/details/gtijfsokny.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhengqikj.top/Article/details/gtmpzeogos.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gtfmmrcapy.html

TS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gtedpijbsq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xuetiantiany.cn/Article/details/gtwkulxoec.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.meibo888.top/Article/details/gtximlqpdk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yueranfly.top/Article/details/gtmqszikdz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gogol.net.cn/Article/details/gtshxgqxuj.html

[O03] 加锁保护共享数据
来源：http://dali.jyoumei.cn/Article/details/gtikxjyhbz.html

Py:   with lock: shared += 1
来源：http://dali.yvedp.cn/Article/details/gtnmqeeqit.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sweek.top/Article/details/gtywpnrndn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj202588.top/Article/details/gtzcpmavpb.html

TS:   // 同 JS
来源：http://dali.kuanghao11.cn/Article/details/gtkwnnqkkr.html

Java: synchronized (this) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gtvhgrtmuy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cheryme.top/Article/details/gtvspqydiz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hammf.cn/Article/details/gtxdwmysmd.html

C#:   lock (gate) { shared++; }
来源：http://dali.cqqwz.cn/Article/details/gtlxxmzurw.html

[O04] 定义异步函数并等待
来源：http://dali.kuanghao11.cn/Article/details/gttpznfjzn.html

Py:   async def f():⏎    await g()
来源：http://dali.fengsongda.top/Article/details/gtletexpsj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hammf.cn/Article/details/gtwidrrxvv.html

JS:   async function f() { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gtxaopkess.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gtcpuqctcw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yvedp.cn/Article/details/gtonrxzqpn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gzhubu.top/Article/details/gtnqhgpxnp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ivvv.top/Article/details/gtnoacuszp.html

C#:   async Task F() { await G(); }
来源：http://dali.9152youxi.cn/Article/details/gtmqjztzno.html

[O05] 并发执行并等待全部完成
来源：http://dali.svipenyu.cn/Article/details/gtpoqgdmms.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dianchejie.cn/Article/details/gtipjdtghm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shuidangran.top/Article/details/gtdfuddjrd.html

JS:   await Promise.all(tasks)
来源：http://dali.9152youxi.cn/Article/details/gtrucvjgml.html

TS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gtvsasyryt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.fzhhl.top/Article/details/gtpfwbeyuw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xziqi.cn/Article/details/gtnhhjxnki.html

Ruby: threads.map(&:join)
来源：http://dali.c1oappe.top/Article/details/gtrevbibkl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.dianchejie.cn/Article/details/gtcnwllsez.html

[O06] 使用进程池
来源：http://dali.sxryk.cn/Article/details/gtcmxcvvod.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.0kj1m.cn/Article/details/gtbangbmnf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhiwuduotai.top/Article/details/gtmtjvqlri.html

JS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gtchquzxgw.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258.top/Article/details/gtlprmjgrw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimacidka.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sweek.top/Article/details/gtfpiqwhqf.html

Ruby: // fork 块
来源：http://dali.ehwqpu.com/Article/details/gtyjuevazu.html

C#:   Parallel.For
来源：http://dali.sufxvd.cn/Article/details/gtblujiznd.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtsolglfgn.html

P. 常用工具函数
来源：http://dali.yuxming.cn/Article/details/gtukibeliu.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtrglsufuy.html

[P01] 生成 UUID
来源：http://dali.yanxiufei.cn/Article/details/gtroczdqvg.html

Py:   str(uuid.uuid4())
来源：http://dali.havefunace.top/Article/details/gtnltodjdu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigfzy.top/Article/details/gtlwuhmbiz.html

JS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gtcijmzjlm.html

TS:   crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gtcdtajpqn.html

Java: UUID.randomUUID().toString()
来源：http://dali.zdqjudy.top/Article/details/gtgijldbnl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.birdmap.top/Article/details/gtolizywcf.html

Ruby: SecureRandom.uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gtcsqdafkk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhoulong.xyz/Article/details/gtosnuqqpt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkqtrqwh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.bjfxy.top/Article/details/gtsnfhsgwp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dianchejie.cn/Article/details/gtdzqdkhey.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ivvv.top/Article/details/gtnsrrlvwq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzckhary.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenzaomai.com/Article/details/gtbxmufohq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hnqzz.top/Article/details/gtxsdolosw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yueranfly.top/Article/details/gtqflhqwjv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.bjfxy.top/Article/details/gtcezgbcev.html

[P03] 生成短随机字符串
来源：http://dali.tanke756.top/Article/details/gtunhhefhy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhoulong.xyz/Article/details/gtosohplfc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jyoumei.cn/Article/details/gtyrhlrcbn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xinyue.icu/Article/details/gtrixderpe.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gtiuisoqrc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ivvv.top/Article/details/gtydvpbdna.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.fzhhl.top/Article/details/gttfjclsxx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yongpay.top/Article/details/gtahigjbnz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aibaodan.cn/Article/details/gtqujszpya.html

[P04] 求长度
来源：http://dali.yvedp.cn/Article/details/gtemckeoau.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yangfankeji.com/Article/details/gtsikgptzr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosuziglf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xinyue.icu/Article/details/gtrhnmwhxl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fengsongda.top/Article/details/gtoltakcja.html

Java: list.size();  map.size();  s.length()
来源：http://dali.haohaochexian.top/Article/details/gtkybzopyj.html

Go:   len(arr);  len(m)
来源：http://dali.0kj1m.cn/Article/details/gtrprvdanv.html

Ruby: x.length;  x.size
来源：http://dali.wangdashe.top/Article/details/gttbiroydq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cashguo.top/Article/details/gtimieqalz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj202588.top/Article/details/gthqvaixvi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gotoacloud.top/Article/details/gtgtpxbrzv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.haohaochexian.top/Article/details/gtuivigtma.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hysaishi.cn/Article/details/gtbmstmmai.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tanke756.top/Article/details/gtwsyfxjgp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nwbrower.top/Article/details/gtpdldxhfq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jqgfzy.top/Article/details/gtderlaxhu.html

Ruby: a == b
来源：http://dali.wangdashe.top/Article/details/gthwmfphhv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpkvpkaod.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shuidangran.top/Article/details/gtgmfmmoqa.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.c1oappe.top/Article/details/gtzdntdfaf.html

PHP:  if (empty($x)) {}
来源：http://dali.cucudq.cn/Article/details/gtivzzfpdm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuanzx.com/Article/details/gtzbhmmwcv.html

TS:   if (x == null) {}
来源：http://dali.zycfv.cn/Article/details/gtqpvxshhc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gtaqvghsix.html

Go:   if x == nil {}
来源：http://dali.hnxiangtu.top/Article/details/gtqunnujqk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jqgfzy.top/Article/details/gtqdomftqh.html

C#:   if (x is null) {}
来源：http://dali.gotoacloud.top/Article/details/gtuxjcovjs.html

[P07] 防抖与节流
来源：http://dali.daria6918.cn/Article/details/gtdqacswod.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yueranfly.top/Article/details/gtvuoqjlpb.html

PHP:  // 手写时间戳比较
来源：http://dali.haohaochexian.top/Article/details/gtqhrzsxal.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gtqdulgiqh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gttexcqhmi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrhnunij.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jyoumei.cn/Article/details/gtftkswomk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nwbrower.top/Article/details/gtnxwplgye.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gtogbnrjin.html

[P08] 处理浮点精度问题
来源：http://dali.hfpthk.cn/Article/details/gtstmbqfwd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigfzy.top/Article/details/gthbnypcpk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtroxptzju.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gotoacloud.top/Article/details/gtjtvbxufn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgufenzy.top/Article/details/gtgxocbpxt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jlsjyb.cn/Article/details/gtvphyllus.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jyoumei.cn/Article/details/gtapqwhpgq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dashuyun.cn/Article/details/gtmohpycrb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.bjfxy.top/Article/details/gtpctnhgle.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtpfujvayv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.0kj1m.cn/Article/details/gtehwfhmcb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtfpvizvfd.html

[Q01] 创建表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtioewlefg.html

CREATE TABLE users (
来源：http://dali.cashguo.top/Article/details/gtgtpsiizm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gtafjrgdjv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xuanzx.com/Article/details/gttmvkdmgd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jianghu66.top/Article/details/gtycubssgb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.fzhhl.top/Article/details/gtmjyogpvx.html

);
来源：http://dali.9152youxi.cn/Article/details/gtkznxzoyt.html

[Q02] 创建带外键的表
来源：http://dali.cqqwz.cn/Article/details/gtofphushc.html

CREATE TABLE orders (
来源：http://dali.kuanghao11.cn/Article/details/gtzlfnwtuf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gtqclpwwvz.html

user_id INT NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gtsrotfhkq.html

amount DECIMAL(10, 2),
来源：http://dali.ehwqpu.com/Article/details/gtawpmoesn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj20258888.top/Article/details/gtdaijzazi.html

);
来源：http://dali.iojbl.cn/Article/details/gtfgadthjr.html

[Q03] 增加列
来源：http://dali.mhx1999.top/Article/details/gtceguryni.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxuanxn.top/Article/details/gtavnntjsw.html

[Q04] 修改列类型
来源：http://dali.daria6918.cn/Article/details/gtwsieqfua.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.redwolf501.top/Article/details/gtoxtafjxp.html

[Q05] 重命名列
来源：http://dali.iojbl.cn/Article/details/gtjswhqmwa.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hongshengwenyu.top/Article/details/gtbpcwgbrf.html

[Q06] 删除列
来源：http://dali.ivvv.top/Article/details/gtcxtufrln.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ppjwa.cn/Article/details/gtwbldzjve.html

[Q07] 删除表
来源：http://dali.andypj.xyz/Article/details/gttmqhqgwg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sweek.top/Article/details/gtsskhxrlq.html

[Q08] 创建普通索引
来源：http://dali.yonumen.top/Article/details/gtvjtpyjgj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gthswerggl.html

[Q09] 创建唯一索引
来源：http://dali.jinqigfzy.top/Article/details/gtimlibyvv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqbwmwdp.html

[Q10] 插入单行
来源：http://dali.cheryme.top/Article/details/gtvwelmynp.html


<!-- 参考信息 -->