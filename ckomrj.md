代发 wailian999

Ruby: exit 1
来源：http://dali.gotoacloud.top/Article/details/gtevklhxkq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhiwuduotai.top/Article/details/gtkjfjylba.html

[M06] 向标准错误输出
来源：http://dali.zdqjudy.top/Article/details/gtxpuljgrg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangshuangyany.cn/Article/details/gtofjpnafq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yueranfly.top/Article/details/gtxcuvtioz.html

JS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtcyjnlgyk.html

TS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gtnymvokhr.html

Java: System.err.println("err")
来源：http://dali.nanxinkj.top/Article/details/gttxhdzffx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.havefunace.top/Article/details/gtifbyoqua.html

Ruby: warn "err"
来源：http://dali.yj202588.top/Article/details/gtggzgtofc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.smart0.xyz/Article/details/gtgqdxxrij.html

[M07] 判断是否为主入口
来源：http://dali.hfpthk.cn/Article/details/gtdpuhgugi.html

Py:   if __name__ == "__main__":
来源：http://dali.birdmap.top/Article/details/gttqmzymql.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gaohongyu789.top/Article/details/gtfaudcnax.html

JS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzgypskm.html

TS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gtydkpvbbi.html

Java: public static void main(String[] args)
来源：http://dali.tanke756.top/Article/details/gtjytzzboo.html

Go:   func main()
来源：http://dali.gotoacloud.top/Article/details/gtsurbyfne.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hywenlv.cn/Article/details/gtodivcdgh.html

C#:   static void Main(string[] args)
来源：http://dali.yueranfly.top/Article/details/gtwzqlscca.html

[M08] 获取系统与运行时信息
来源：http://dali.gaohongyu789.top/Article/details/gtjssypcoi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pycfn.com/Article/details/gtkfrmrgua.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzylvrwi.html

JS:   process.platform;  process.version
来源：http://dali.svipenyu.cn/Article/details/gtjmgxpnws.html

TS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gtndoelvch.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cqqwz.cn/Article/details/gtwzrqrxds.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cheryme.top/Article/details/gtnnxluymx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.aibaodan.cn/Article/details/gtxgpyahsp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tanke756.top/Article/details/gtipqugrmn.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtokhbknfb.html

N. 数据结构与算法
来源：http://dali.zdqjudy.top/Article/details/gtiduhgolb.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtlnelesxz.html

[N01] 二分查找（有序数组）
来源：http://dali.meibo888.top/Article/details/gtvhoctjus.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtpipaykkn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj202588.top/Article/details/gtprjyrkde.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gtiqrszmae.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gtbfoijkiz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gttnanhvve.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.daria6918.cn/Article/details/gthyvxfezm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.bjfxy.top/Article/details/gtthzqjdhb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gttofukvsg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cqqwz.cn/Article/details/gttybiksfz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gtmlvesmsu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daria6918.cn/Article/details/gtyvhicvim.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gtymadbvww.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gtdonqybii.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ppjwa.cn/Article/details/gtkooomyoy.html

Go:   slices.Sort(arr)
来源：http://dali.jyoumei.cn/Article/details/gtbpuwfsbd.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gtbajdatqc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvvrtsfp.html

[N03] 快速排序（分治示例）
来源：http://dali.tanke756.top/Article/details/gtvzjqfdda.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zdqjudy.top/Article/details/gtafdixvzn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aizwys.cn/Article/details/gtfhozwcrq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gtjdwwpjar.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cashguo.top/Article/details/gtzgbvgxwz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jianghu66.top/Article/details/gtrraqeujh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yueranfly.top/Article/details/gtnwajlobc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.316326.xyz/Article/details/gtkuogfnlt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jyoumei.cn/Article/details/gtjvxtmimo.html

[N04] 斐波那契数列
来源：http://dali.hnqzz.top/Article/details/gtqyvigymr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gtmwndytai.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglsodnkc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gthbgliijw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzwncajo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xylfe.cn/Article/details/gtdxgawaof.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.c1oappe.top/Article/details/gtftzoftkk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gtreoecquw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtuiukiqjp.html

[N05] 最大公约数
来源：http://dali.jqgfzy.top/Article/details/gtpwdcbefb.html

Py:   math.gcd(a, b)
来源：http://dali.guowangkeji.top/Article/details/gtqemsbxnl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenzaomai.com/Article/details/gtxzskhowy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xinyue.icu/Article/details/gtetvxirzx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtoizhqtdj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cheryme.top/Article/details/gtrhpmzyyf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shuidangran.top/Article/details/gtytkwqiye.html

Ruby: a.gcd(b)
来源：http://dali.jqgfzy.top/Article/details/gtdnotibhc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.vqdsnc.cn/Article/details/gtpvvddcht.html

[N06] 判断回文字符串
来源：http://dali.jiagoushi.top/Article/details/gtlggrhikr.html

Py:   s == s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gtitnnence.html

PHP:  $s === strrev($s);
来源：http://dali.pengpengdd.cyou/Article/details/gteefbspee.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtcvskcrfb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtahcjvajn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbrxmqbz.html

Go:   // 双指针从两端比较
来源：http://dali.xuanzx.com/Article/details/gtdcsnlxst.html

Ruby: s == s.reverse
来源：http://dali.daria6918.cn/Article/details/gtnskmfxvk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.guannengcc.top/Article/details/gtdrmyeeaq.html

[N07] 两数之和（返回下标）
来源：http://dali.hnqzz.top/Article/details/gtgpcczotf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmtwrgso.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvleskne.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.meibo888.top/Article/details/gtbatnbwnh.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gttmjfshsl.html

Java: // 手写 HashMap
来源：http://dali.haohaochexian.top/Article/details/gtmrqcgbht.html

Go:   // 手写 map[int]int
来源：http://dali.zhongyouzk.top/Article/details/gtotjpduos.html

Ruby: // 手写 Hash
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvzaxfpr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gtqoqnxvpq.html

[N08] 生成全排列
来源：http://dali.tian-w.cn/Article/details/gtmvuykgso.html

Py:   itertools.permutations(arr)
来源：http://dali.meibo888.top/Article/details/gtmydfroxb.html

PHP:  // 手写递归交换
来源：http://dali.birdmap.top/Article/details/gtsdngtyuy.html

JS:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtynenomjd.html

TS:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtbntgarjl.html

Java: // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtucjygrlz.html

Go:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtxftsdctt.html

Ruby: arr.permutation.to_a
来源：http://dali.daxiang520.top/Article/details/gtvawssgjx.html

C#:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtfqnaebsm.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gtzmdiaaly.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cqqwz.cn/Article/details/gtbzzfugcd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtdewhiodn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gtbmuzeitu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jyoumei.cn/Article/details/gtxcdmxjdh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yueranfly.top/Article/details/gthlplfhxm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shangyingyoupin.top/Article/details/gtpusfumhx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gtbeebsrkl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cucudq.cn/Article/details/gtaugwlbav.html

[N10] 链表节点定义
来源：http://dali.hongshengwenyu.top/Article/details/gtiinbnuzr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.mhx1999.top/Article/details/gtkkfuwtqc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.pycfn.com/Article/details/gtnstlxyey.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtviqqecce.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cdnleiting.top/Article/details/gtvusmevcg.html

Java: class Node { int v; Node next; }
来源：http://dali.cqqwz.cn/Article/details/gtowyefllq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daxiang520.top/Article/details/gtqwzyfton.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xinyue.icu/Article/details/gtkbojqrbz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvenopuq.html

[N11] 二叉树中序遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtllssxhua.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hongshengwenyu.top/Article/details/gthaxfptop.html

PHP:  // 手写递归函数
来源：http://dali.smart0.xyz/Article/details/gtcgfijyub.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ehwqpu.com/Article/details/gtjvovtqxh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gtnnsjdiwv.html

Java: // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtfuyogfso.html

Go:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtgbeubexq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.redwolf501.top/Article/details/gtspwbrmdt.html

C#:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gthoawkuxy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xinyue.icu/Article/details/gtgobsjuui.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gotoacloud.top/Article/details/gtmofzglwk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cucudq.cn/Article/details/gtaujycvao.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gtvtsmtzum.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hammf.cn/Article/details/gtiezjgarx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dianchejie.cn/Article/details/gtebohfpcw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cheryme.top/Article/details/gtqbayoaou.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gtmnpqtini.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gthrixxiht.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtmmzhzfgt.html

O. 并发与异步
来源：http://dali.cdnleiting.top/Article/details/gtvpbdmemd.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtxbkmjomn.html

[O01] 启动一个线程
来源：http://dali.hnxiangtu.top/Article/details/gtcybcdjqo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhongyouzk.top/Article/details/gtcpzygxex.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuanzhike.top/Article/details/gtskghnezd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkxmoobv.html

TS:   // 同 JS
来源：http://dali.ybcxt.top/Article/details/gtatllskvs.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhoulong.xyz/Article/details/gtggevcbye.html

Go:   go f()
来源：http://dali.jinqigufen.top/Article/details/gtruuzinyq.html

Ruby: Thread.new { f }
来源：http://dali.aibaodan.cn/Article/details/gtuouptcvk.html

C#:   Task.Run(() => F());
来源：http://dali.cashguo.top/Article/details/gtuxkonzdj.html

[O02] 使用线程池
来源：http://dali.andypj.xyz/Article/details/gtqkfeowcs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.andypj.xyz/Article/details/gtdagxbors.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sufxvd.cn/Article/details/gttucjlzpe.html

JS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gtujmqvqwb.html

TS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gtiizthjwc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tanke756.top/Article/details/gtlbkhecpb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nwbrower.top/Article/details/gtumrukrrv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhaomingkeji.xyz/Article/details/gtougalhtd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnqzz.top/Article/details/gtvcvsbvsw.html

[O03] 加锁保护共享数据
来源：http://dali.pycfn.com/Article/details/gtvtoagzje.html

Py:   with lock: shared += 1
来源：http://dali.jqgfzy.top/Article/details/gtwmowzruy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cashguo.top/Article/details/gttqviphyc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwbgltcz.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gtjcxiafhq.html

Java: synchronized (this) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gtjxjcckkm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinghuilouyu.cn/Article/details/gthjvhdaxk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.dashuyun.cn/Article/details/gtnbizlizz.html

C#:   lock (gate) { shared++; }
来源：http://dali.9152youxi.cn/Article/details/gtnleapkpo.html

[O04] 定义异步函数并等待
来源：http://dali.zdqjudy.top/Article/details/gtpwmkhmyo.html

Py:   async def f():⏎    await g()
来源：http://dali.shzxlz.cn/Article/details/gtfejndjxz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zdqjudy.top/Article/details/gtsgfuussr.html

JS:   async function f() { await g(); }
来源：http://dali.redwolf501.top/Article/details/gtltnzlnud.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtboddkkhu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpdwgcwx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ivvv.top/Article/details/gttwdycfdl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.smart0.xyz/Article/details/gttynrfdaj.html

C#:   async Task F() { await G(); }
来源：http://dali.shzxlz.cn/Article/details/gtfuibkztv.html

[O05] 并发执行并等待全部完成
来源：http://dali.smart0.xyz/Article/details/gtyuhhcmny.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daxiang520.top/Article/details/gtbnnqhcgc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sufxvd.cn/Article/details/gtkjnercbn.html

JS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gtqwqbebnu.html

TS:   await Promise.all(tasks)
来源：http://dali.yvedp.cn/Article/details/gtrwjxzxbh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigfzy.top/Article/details/gtaomgjsjf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cqqwz.cn/Article/details/gtunsjhngc.html

Ruby: threads.map(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gtnxcevgyr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hysaishi.cn/Article/details/gtahylmdrc.html

[O06] 使用进程池
来源：http://dali.smart0.xyz/Article/details/gtgcbiaixo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sysykeji.top/Article/details/gtopogltdp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hywenlv.cn/Article/details/gterciwhzv.html

JS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gtiskmnocr.html

TS:   // child_process / cluster 模块
来源：http://dali.birdmap.top/Article/details/gtdadxvegr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuanzhike.top/Article/details/gttryrhmgn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.vqdsnc.cn/Article/details/gtkabeatje.html

Ruby: // fork 块
来源：http://dali.ehwqpu.com/Article/details/gtsgvgncxl.html

C#:   Parallel.For
来源：http://dali.zhoulong.xyz/Article/details/gtwustixbt.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtvlntyrbl.html

P. 常用工具函数
来源：http://dali.9152youxi.cn/Article/details/gtwxhmphzz.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtpbtyipca.html

[P01] 生成 UUID
来源：http://dali.andypj.xyz/Article/details/gtxuevwisn.html

Py:   str(uuid.uuid4())
来源：http://dali.c1oappe.top/Article/details/gtvvxeavok.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.haohaochexian.top/Article/details/gtzvapwipl.html

JS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gtaxnoslcz.html

TS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtkaqofatq.html

Java: UUID.randomUUID().toString()
来源：http://dali.tianlin.xyz/Article/details/gtauijdbxw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fzhhl.top/Article/details/gtpzrwvwkr.html

Ruby: SecureRandom.uuid
来源：http://dali.zhengqikj.top/Article/details/gtrwdiuogu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dianchejie.cn/Article/details/gteeayvevu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.guannengcc.top/Article/details/gtegfzrcjm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zdqjudy.top/Article/details/gtnmjoisfv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj202588.top/Article/details/gtdbqvdgav.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aizwys.cn/Article/details/gtxtnfbakk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.birdmap.top/Article/details/gtxreboqnl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jyoumei.cn/Article/details/gtogjanjoq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.guowangkeji.top/Article/details/gtffiddvrd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yonumen.top/Article/details/gtsuiytovy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daxiang520.top/Article/details/gtxlpecnbq.html

[P03] 生成短随机字符串
来源：http://dali.cheryme.top/Article/details/gtsllynbyy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.9152youxi.cn/Article/details/gtjlukhohv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yueranfly.top/Article/details/gtmnxlwxtr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sxryk.cn/Article/details/gtckjhzqvq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gtizppfsgh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhoulong.xyz/Article/details/gtanpttgvs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.svipenyu.cn/Article/details/gttrhbzyga.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenlongwang.top/Article/details/gtwplugnhi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yueranfly.top/Article/details/gtclbxcdgm.html

[P04] 求长度
来源：http://dali.kuanghao11.cn/Article/details/gtbucwungy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tanke756.top/Article/details/gtktznskmo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtqbrccnnn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gtftpagczg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gtytyblyxv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guowangkeji.top/Article/details/gtroeccpcn.html

Go:   len(arr);  len(m)
来源：http://dali.yanxiufei.cn/Article/details/gtyjpdwwnw.html

Ruby: x.length;  x.size
来源：http://dali.xylfe.cn/Article/details/gtxhgpvrnj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jqgufenzy.top/Article/details/gtovtmfxsg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xuanzx.com/Article/details/gtmspnkevv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cheryme.top/Article/details/gtxxegssqg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ydzc1.top/Article/details/gtnvhsdoqq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.quarkkingdee.top/Article/details/gtptbsftim.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yanxiufei.cn/Article/details/gtppjzfgif.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.andypj.xyz/Article/details/gtkubyrcmq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gtjafzalxt.html

Ruby: a == b
来源：http://dali.gaohongyu789.top/Article/details/gtvqrsgqrk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shuidangran.top/Article/details/gtdbxumrwc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangdashe.top/Article/details/gtqjezxtfv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsdxmcop.html

PHP:  if (empty($x)) {}
来源：http://dali.ivvv.top/Article/details/gtturiynrx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinqigfzy.top/Article/details/gtfqnnwhdu.html

TS:   if (x == null) {}
来源：http://dali.tianlin.xyz/Article/details/gtorkitiay.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jyoumei.cn/Article/details/gtekhchexv.html

Go:   if x == nil {}
来源：http://dali.chenzaomai.com/Article/details/gtnzngvbqs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sufxvd.cn/Article/details/gtnjjzbfen.html

C#:   if (x is null) {}
来源：http://dali.hnqzz.top/Article/details/gtmbrryjtd.html

[P07] 防抖与节流
来源：http://dali.yvedp.cn/Article/details/gtzljjwaoz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnivecgvv.html

PHP:  // 手写时间戳比较
来源：http://dali.yanxiufei.cn/Article/details/gtqskworrf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gtfcztenik.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gtipfgrqxr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.316326.xyz/Article/details/gttluzkdyz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.snrcjt.cn/Article/details/gtwjsacbnf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.havefunace.top/Article/details/gtmeudvqzy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xziqi.cn/Article/details/gtfmjhzbju.html

[P08] 处理浮点精度问题
来源：http://dali.fengsongda.top/Article/details/gtkqjvgnre.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nanxinkj.top/Article/details/gtulyppcvp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj20258.top/Article/details/gtuudgikis.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.havefunace.top/Article/details/gtyegaswqp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sufxvd.cn/Article/details/gtkhtczala.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xziqi.cn/Article/details/gtrghhzzmg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigufen.top/Article/details/gtlacjsfgd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cheryme.top/Article/details/gtfnhfnhyz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ybcxt.top/Article/details/gtenkevunb.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtyewfcfii.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cqqwz.cn/Article/details/gtwhaggubo.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtnxcktxbr.html

[Q01] 创建表
来源：http://dali.xuetiantiany.cn/Article/details/gtmdwhmfji.html

CREATE TABLE users (
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktkiuzhr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yueranfly.top/Article/details/gtetulpnta.html

name VARCHAR(50) NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gtwbjloctg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yangfankeji.com/Article/details/gtauxagyfl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cashguo.top/Article/details/gtqgzllrjh.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gtllyxpbtc.html

[Q02] 创建带外键的表
来源：http://dali.birdmap.top/Article/details/gtbpfnepiu.html

CREATE TABLE orders (
来源：http://dali.cheryme.top/Article/details/gtxilmmggp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gtmijabjpd.html

user_id INT NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gtlerlsmde.html

amount DECIMAL(10, 2),
来源：http://dali.316326.xyz/Article/details/gtmpqdxfke.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xziqi.cn/Article/details/gtrrtxdydy.html

);
来源：http://dali.nanxinkj.top/Article/details/gtlcnoqpxz.html

[Q03] 增加列
来源：http://dali.cashguo.top/Article/details/gticjpbqte.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.dianchejie.cn/Article/details/gtwjaodomv.html

[Q04] 修改列类型
来源：http://dali.hnqzz.top/Article/details/gtdtikmgve.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.havefunace.top/Article/details/gtdwufxuei.html

[Q05] 重命名列
来源：http://dali.vqdsnc.cn/Article/details/gtmqksqnck.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cqqwz.cn/Article/details/gttucilmjl.html

[Q06] 删除列
来源：http://dali.ppjwa.cn/Article/details/gtfaatrwhx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.9152youxi.cn/Article/details/gtdvvabyhd.html

[Q07] 删除表
来源：http://dali.shzxlz.cn/Article/details/gtjzobvxyl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtuqdwcgal.html

[Q08] 创建普通索引
来源：http://dali.shzxlz.cn/Article/details/gtzdhqgzvl.html


<!-- 参考信息 -->