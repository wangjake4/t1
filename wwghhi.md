代发 wailian999

Java: public static void main(String[] args)
来源：http://dali.meibo888.top/Article/details/gtiyjfwshi.html

Go:   func main()
来源：http://dali.chenzaomai.com/Article/details/gtexxjyjpd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenlongwang.top/Article/details/gtuokaihxt.html

C#:   static void Main(string[] args)
来源：http://dali.jqgufenzy.top/Article/details/gtziqxvnlf.html

[M08] 获取系统与运行时信息
来源：http://dali.hongshengwenyu.top/Article/details/gtvznrnhyd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.haohaochexian.top/Article/details/gthsyfbswa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.snrcjt.cn/Article/details/gtwzhxrzwl.html

JS:   process.platform;  process.version
来源：http://dali.cashguo.top/Article/details/gtxsagxoys.html

TS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gtykacvjhb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jianghu66.top/Article/details/gtdkcnojol.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sxryk.cn/Article/details/gtutrzcnfu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.c1oappe.top/Article/details/gtabzepscs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhixingplan.top/Article/details/gtcalpwuvu.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtuphnpgqp.html

N. 数据结构与算法
来源：http://dali.quarkkingdee.top/Article/details/gtreisaide.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtjyztahzm.html

[N01] 二分查找（有序数组）
来源：http://dali.haohaochexian.top/Article/details/gtczvhspgl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtukknbqcl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtscqudxwu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gtwjbnppkd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jiagoushi.top/Article/details/gtmatgplov.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtqdzhaleq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtjqvvgypx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.haohaochexian.top/Article/details/gtcxetejej.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtjydbtfqm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtloclhvvl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gtrcizndjw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtddquldpu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gtrnukotzc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gtdjdpfblf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gtlvrhscry.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gtrykhmyaq.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gtlemsuuqd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cheryme.top/Article/details/gtncvskjkf.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhegliie.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cqqwz.cn/Article/details/gtnttayqrp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrhrtecv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gtxqojadfu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gtwwftipgo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shzxlz.cn/Article/details/gtxxqouvtx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangshuangyany.cn/Article/details/gtbixwhspg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yueranfly.top/Article/details/gtygfijxvm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cashguo.top/Article/details/gtjxsjhbnv.html

[N04] 斐波那契数列
来源：http://dali.iojbl.cn/Article/details/gtzjvpcmyc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gtbspvkxug.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gtxhifmmkn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtrhxnxvaw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtbzskzcny.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gttujmybnb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.feifeiyinyue.top/Article/details/gtzngnvehw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gtzizohknf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtwxzekadc.html

[N05] 最大公约数
来源：http://dali.shangyingyoupin.top/Article/details/gtmebelcgh.html

Py:   math.gcd(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtlemshlsb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guannengcc.top/Article/details/gtylfkstqv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtuqtesezi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigufen.top/Article/details/gtaxaequbs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigfzy.top/Article/details/gtxubimvlu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.smart0.xyz/Article/details/gtncmxhwxu.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbexxbxj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuxming.cn/Article/details/gttfnjbdby.html

[N06] 判断回文字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffygxisp.html

Py:   s == s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gttdtprzwu.html

PHP:  $s === strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtdiewoumu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtmmvqcuvw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbhfjzqk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj20258.top/Article/details/gtcafbyykx.html

Go:   // 双指针从两端比较
来源：http://dali.yuxming.cn/Article/details/gtfpglhyqq.html

Ruby: s == s.reverse
来源：http://dali.tanke756.top/Article/details/gtdzfgchgq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodtdhqre.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgfzy.top/Article/details/gtrwmqjrys.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jianghu66.top/Article/details/gtzqmxenpj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jiagoushi.top/Article/details/gtiplvrrxt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258888.top/Article/details/gtcodgsosv.html

TS:   // 手写 Map<string, number>
来源：http://dali.redwolf501.top/Article/details/gtqpexgowl.html

Java: // 手写 HashMap
来源：http://dali.gogol.net.cn/Article/details/gtwuufjtzz.html

Go:   // 手写 map[int]int
来源：http://dali.redwolf501.top/Article/details/gtosemhyku.html

Ruby: // 手写 Hash
来源：http://dali.316326.xyz/Article/details/gtwxznkwej.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yueranfly.top/Article/details/gtwijiwxtk.html

[N08] 生成全排列
来源：http://dali.shzxlz.cn/Article/details/gtbqkefghj.html

Py:   itertools.permutations(arr)
来源：http://dali.ivvv.top/Article/details/gtyrtpibxa.html

PHP:  // 手写递归交换
来源：http://dali.xuanzx.com/Article/details/gtdeybikpx.html

JS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtgikdhuru.html

TS:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtlsuyrria.html

Java: // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtybnvbtkj.html

Go:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtqqitsani.html

Ruby: arr.permutation.to_a
来源：http://dali.pengpengdd.cyou/Article/details/gtkwvbwknb.html

C#:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtsjxyuelg.html

[N09] 栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gtjszzsmvq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cqqwz.cn/Article/details/gtjypdqnnr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtanpwgttv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtrmknbzeq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrnokpnd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yueranfly.top/Article/details/gtexytbbvf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxinkj.top/Article/details/gthqqvsaip.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sysykeji.top/Article/details/gtxgmbxynr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhongyouzk.top/Article/details/gtcgxdhuow.html

[N10] 链表节点定义
来源：http://dali.zhiwuduotai.top/Article/details/gtljjvlvik.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tanke756.top/Article/details/gtsgvshukl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.bjfxy.top/Article/details/gtfcjckarf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shuidangran.top/Article/details/gtmmnskrln.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigufen.top/Article/details/gtueccbftd.html

Java: class Node { int v; Node next; }
来源：http://dali.zhengqikj.top/Article/details/gtjeqlcujy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gotoacloud.top/Article/details/gtyuwpajdo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.316326.xyz/Article/details/gtkyuubplk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sxryk.cn/Article/details/gtsinqxfnz.html

[N11] 二叉树中序遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtliawhook.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.haohaochexian.top/Article/details/gtjzjvreas.html

PHP:  // 手写递归函数
来源：http://dali.shuidangran.top/Article/details/gtryzrxzfv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gtulruukzr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gtmzuwfwdy.html

Java: // 手写递归
来源：http://dali.xylfe.cn/Article/details/gtudrqbayd.html

Go:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtlgcxikrb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jyoumei.cn/Article/details/gtnkjnehqb.html

C#:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtvajtunmd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzjmdehz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.mhx1999.top/Article/details/gtprqkmdeb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gzhubu.top/Article/details/gttxkilygj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tanke756.top/Article/details/gtgwbkzfuz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangshuangyany.cn/Article/details/gtwyysrpni.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gtzxmcneou.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yuxming.cn/Article/details/gtlryxobqe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenjidiqi.icu/Article/details/gtfftikcko.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gtwpvsqlwn.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtytxbzaex.html

O. 并发与异步
来源：http://dali.cdnleiting.top/Article/details/gtqtrxfppk.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtaknxpico.html

[O01] 启动一个线程
来源：http://dali.yonumen.top/Article/details/gtgocmejwq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxinkj.top/Article/details/gtpmgvqhsj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.smart0.xyz/Article/details/gtgcvcclud.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yueranfly.top/Article/details/gtrybloxrc.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gthcocliya.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenzaomai.com/Article/details/gtfumrtqfs.html

Go:   go f()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthwsmpvb.html

Ruby: Thread.new { f }
来源：http://dali.chenjidiqi.icu/Article/details/gtdahhumdx.html

C#:   Task.Run(() => F());
来源：http://dali.cqqwz.cn/Article/details/gtntglyoqs.html

[O02] 使用线程池
来源：http://dali.pengpengdd.cyou/Article/details/gtkpzljcmp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.chenlongwang.top/Article/details/gtldojqcjs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cdnleiting.top/Article/details/gtwocdrpfj.html

JS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtcujafeai.html

TS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gtvdkhtefk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.smart0.xyz/Article/details/gtiwovhwai.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yangfankeji.com/Article/details/gtxiftnaic.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuanzx.com/Article/details/gttssnkqfl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guannengcc.top/Article/details/gtanovvrvb.html

[O03] 加锁保护共享数据
来源：http://dali.yj20258888.top/Article/details/gtwwnzhelf.html

Py:   with lock: shared += 1
来源：http://dali.cdnleiting.top/Article/details/gteihvvhgg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.vqdsnc.cn/Article/details/gtyucmckiv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhoulong.xyz/Article/details/gtizmxxqie.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gtysxyskfb.html

Java: synchronized (this) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gtdnfbqamv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cashguo.top/Article/details/gtcmxswvqf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cheryme.top/Article/details/gtodcpcadk.html

C#:   lock (gate) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxasyugef.html

[O04] 定义异步函数并等待
来源：http://dali.zhengqikj.top/Article/details/gtkpduyukb.html

Py:   async def f():⏎    await g()
来源：http://dali.chenlongwang.top/Article/details/gtgwewqogq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yangfankeji.com/Article/details/gtxagtpird.html

JS:   async function f() { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowvfcaya.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.iojbl.cn/Article/details/gtpjdqcpil.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenzaomai.com/Article/details/gtnyimjryb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ybcxt.top/Article/details/gtxdcohlgi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gotoacloud.top/Article/details/gtlahggivy.html

C#:   async Task F() { await G(); }
来源：http://dali.nwbrower.top/Article/details/gtmtuukjqw.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulyfywiz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hammf.cn/Article/details/gtyuwxlhit.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzeptodvo.html

JS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gtcfvysziw.html

TS:   await Promise.all(tasks)
来源：http://dali.shzxlz.cn/Article/details/gtadrpjamz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ydzc1.top/Article/details/gtlsqtamwm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hywenlv.cn/Article/details/gtajlzotgd.html

Ruby: threads.map(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gttahudilo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xylfe.cn/Article/details/gtqssikevc.html

[O06] 使用进程池
来源：http://dali.xylfe.cn/Article/details/gtlxtbxgvq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shuidangran.top/Article/details/gtvxlcfihc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xinyue.icu/Article/details/gtqrstyijd.html

JS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gtbgwuvljy.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gtydsqdjpc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.guannengcc.top/Article/details/gtanmiglpf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cucudq.cn/Article/details/gtnxjhpwnr.html

Ruby: // fork 块
来源：http://dali.316326.xyz/Article/details/gtkeumkcez.html

C#:   Parallel.For
来源：http://dali.xuetiantiany.cn/Article/details/gtgayeahcc.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtfumpugwq.html

P. 常用工具函数
来源：http://dali.ppjwa.cn/Article/details/gtkhetkjsl.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtzmbplaii.html

[P01] 生成 UUID
来源：http://dali.mhx1999.top/Article/details/gtcvabzzqf.html

Py:   str(uuid.uuid4())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtznhvwvin.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jyoumei.cn/Article/details/gtzcsnhkjp.html

JS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gtqutinnki.html

TS:   crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gthnxiffmq.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuxming.cn/Article/details/gthnxfpgas.html

Go:   // 用 github.com/google/uuid
来源：http://dali.redwolf501.top/Article/details/gtuxxbzqlr.html

Ruby: SecureRandom.uuid
来源：http://dali.yonumen.top/Article/details/gteuuqvfnd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.birdmap.top/Article/details/gtxhrlqfwq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yangfankeji.com/Article/details/gtvqmgwbxi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.aizwys.cn/Article/details/gtvfpztmsr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.smart0.xyz/Article/details/gthqbzdnce.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shangyingyoupin.top/Article/details/gtwtthujet.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yueranfly.top/Article/details/gtwpkyhysl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yvedp.cn/Article/details/gtrdrcnkhh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxuanxn.top/Article/details/gtltrikoms.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ehwqpu.com/Article/details/gtrogaehvi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hongshengwenyu.top/Article/details/gtcvfkvkic.html

[P03] 生成短随机字符串
来源：http://dali.xinyue.icu/Article/details/gthsjvousb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.iojbl.cn/Article/details/gtsgoaftbg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daria6918.cn/Article/details/gtpwmloppy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gtloyizjlg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gttyzvirys.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.meibo888.top/Article/details/gtkyipnikv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.fzhhl.top/Article/details/gtnhnjdbue.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258888.top/Article/details/gtmmzihzjo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hywenlv.cn/Article/details/gtespwoxfw.html

[P04] 求长度
来源：http://dali.cqqwz.cn/Article/details/gtigkubjgr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gogol.net.cn/Article/details/gtkkemnafv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtfecnbpxp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gtsmjacran.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fzhhl.top/Article/details/gtekgcszfa.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xinyue.icu/Article/details/gtfylvcvkr.html

Go:   len(arr);  len(m)
来源：http://dali.zdqjudy.top/Article/details/gtgylexliw.html

Ruby: x.length;  x.size
来源：http://dali.daxiang520.top/Article/details/gtlmqnvsou.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cucudq.cn/Article/details/gtorkpakuh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhixingplan.top/Article/details/gtgdafjopd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tian-w.cn/Article/details/gtvgruknxg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.kuanghao11.cn/Article/details/gtualtinpt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xylfe.cn/Article/details/gttiguvsto.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenzaomai.com/Article/details/gtefetbylu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuetiantiany.cn/Article/details/gtbpsxzppr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.0kj1m.cn/Article/details/gtglmrfohy.html

Ruby: a == b
来源：http://dali.tian-w.cn/Article/details/gtuiiwsghv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigfzy.top/Article/details/gtdkdmbobp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yongpay.top/Article/details/gtnxfmlbil.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gzhubu.top/Article/details/gtdkyuqfgg.html

PHP:  if (empty($x)) {}
来源：http://dali.yonumen.top/Article/details/gttaahgrur.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenlongwang.top/Article/details/gtclmxwebn.html

TS:   if (x == null) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxcyzvfo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gtoxookisy.html

Go:   if x == nil {}
来源：http://dali.gotoacloud.top/Article/details/gtfpxscjls.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yueranfly.top/Article/details/gtkvyzcbls.html

C#:   if (x is null) {}
来源：http://dali.haohaochexian.top/Article/details/gtpvjvkrit.html

[P07] 防抖与节流
来源：http://dali.hammf.cn/Article/details/gtdlgfgied.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.smart0.xyz/Article/details/gtsougglbl.html

PHP:  // 手写时间戳比较
来源：http://dali.jyoumei.cn/Article/details/gtwtranaub.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiaholqrc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gtotkcwhmz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zdqjudy.top/Article/details/gtozganbep.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhongyouzk.top/Article/details/gtoabhhonj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.redwolf501.top/Article/details/gtjhmnucno.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sxryk.cn/Article/details/gtajkcvcop.html

[P08] 处理浮点精度问题
来源：http://dali.yongpay.top/Article/details/gtlpqmxdnw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigufen.top/Article/details/gtjzwzlhms.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hywenlv.cn/Article/details/gtypqjiwpw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yvedp.cn/Article/details/gtcttdoras.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhongyouzk.top/Article/details/gtkwhehjzl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cashguo.top/Article/details/gtkqcfxrco.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigfzy.top/Article/details/gtcheyepaj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gaohongyu789.top/Article/details/gtchfuhoio.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhixingplan.top/Article/details/gtqounkihx.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtcovuuibv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuxming.cn/Article/details/gtmpmzrljg.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtaoufscml.html

[Q01] 创建表
来源：http://dali.yuxming.cn/Article/details/gtbftxwsvi.html

CREATE TABLE users (
来源：http://dali.xuetiantiany.cn/Article/details/gtyltuilqm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gtihuzxojr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gtbdtbsdoo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tian-w.cn/Article/details/gthiaccaqj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.birdmap.top/Article/details/gtuyksvqzb.html

);
来源：http://dali.cqqwz.cn/Article/details/gtlqndknge.html

[Q02] 创建带外键的表
来源：http://dali.hammf.cn/Article/details/gtgqrlifuv.html

CREATE TABLE orders (
来源：http://dali.zhengqikj.top/Article/details/gtdukgcjpq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gtizmlykhk.html

user_id INT NOT NULL,
来源：http://dali.yj20258.top/Article/details/gtpsoizcmq.html

amount DECIMAL(10, 2),
来源：http://dali.yuxming.cn/Article/details/gtoetjzbty.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.c1oappe.top/Article/details/gthuootyzd.html

);
来源：http://dali.svipenyu.cn/Article/details/gtvbmclhxs.html

[Q03] 增加列
来源：http://dali.c1oappe.top/Article/details/gtyctesoki.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yangfankeji.com/Article/details/gtdxjwnwyl.html

[Q04] 修改列类型
来源：http://dali.dianchejie.cn/Article/details/gtusjbhuoo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nanxinkj.top/Article/details/gtifsgcofa.html

[Q05] 重命名列
来源：http://dali.yueranfly.top/Article/details/gtgcybmtxm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sxryk.cn/Article/details/gtcvtexzlc.html

[Q06] 删除列
来源：http://dali.daxiang520.top/Article/details/gtjtkkmwnk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.smart0.xyz/Article/details/gtgnznwaze.html

[Q07] 删除表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtolzpzcah.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gaohongyu789.top/Article/details/gtljogjyup.html

[Q08] 创建普通索引
来源：http://dali.kuanghao11.cn/Article/details/gthogzbtiv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gtotebeqnx.html

[Q09] 创建唯一索引
来源：http://dali.yj20258888.top/Article/details/gtzwszslua.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenjidiqi.icu/Article/details/gtrtdexovw.html

[Q10] 插入单行
来源：http://dali.316326.xyz/Article/details/gtdybibjmm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhengqikj.top/Article/details/gtfiajdghz.html

[Q11] 一次插入多行
来源：http://dali.zdqjudy.top/Article/details/gtnhslbpai.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sufxvd.cn/Article/details/gtekbavsxk.html

[Q12] 插入后取自增 ID
来源：http://dali.c1oappe.top/Article/details/gtvcmyjngo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yvedp.cn/Article/details/gtgnymkkix.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.meibo888.top/Article/details/gthjgdzwbu.html

[Q13] 忽略重复插入
来源：http://dali.havefunace.top/Article/details/gtqpqtmbyj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.smart0.xyz/Article/details/gtmxhtclaa.html

[Q14] 存在则更新（upsert）
来源：http://dali.kuanghao11.cn/Article/details/gtemvhxvso.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinghuilouyu.cn/Article/details/gtunzcczwk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ybcxt.top/Article/details/gtikrtmmqi.html

[Q15] 查询全部
来源：http://dali.jinqigufen.top/Article/details/gtmbkbkicx.html


<!-- 参考信息 -->