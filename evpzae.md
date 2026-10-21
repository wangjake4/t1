代发 wailian999

Java: public static void main(String[] args)
来源：http://dali.fzhhl.top/Article/details/gtshjdbusc.html

Go:   func main()
来源：http://dali.316326.xyz/Article/details/gthrwrtlcp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daria6918.cn/Article/details/gtuywuadpb.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gtvvnlhzle.html

[M08] 获取系统与运行时信息
来源：http://dali.kuanghao11.cn/Article/details/gtwnaimdva.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gzhubu.top/Article/details/gtcbbxcbqx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xylfe.cn/Article/details/gttcxzbpff.html

JS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gtwsmfkpfy.html

TS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gtiybwpdll.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aibaodan.cn/Article/details/gtaupxrvoh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pycfn.com/Article/details/gtmsokxkhw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxinkj.top/Article/details/gtazuvxqri.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ivvv.top/Article/details/gtafqikrzq.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtrdavtrbf.html

N. 数据结构与算法
来源：http://dali.tian-w.cn/Article/details/gttywzhkay.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtrfrvrmji.html

[N01] 二分查找（有序数组）
来源：http://dali.gzhubu.top/Article/details/gtrjqjjwwa.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtpfipiaey.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fzhhl.top/Article/details/gtygewbkky.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gtgjjywpvb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gtnuhxlwgj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtobgodbrz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtkumzjsix.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhongyouzk.top/Article/details/gtwamktihz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gtykjpdfvn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258888.top/Article/details/gtvhmpwyxk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gtrrwmwsyr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cheryme.top/Article/details/gtsyyzoydw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gtfwvnvezm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gtlbpsihed.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhixingplan.top/Article/details/gthfpvdzye.html

Go:   slices.Sort(arr)
来源：http://dali.xylfe.cn/Article/details/gtdofadoyz.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gthcpoxfmb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zdqjudy.top/Article/details/gtthsuuirw.html

[N03] 快速排序（分治示例）
来源：http://dali.pengpengdd.cyou/Article/details/gthwqkzhcf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhoulong.xyz/Article/details/gtbwfxpmxy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ydzc1.top/Article/details/gtnhbpioyg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gtdtrszjac.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gtfquslwjz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cucudq.cn/Article/details/gtfuoihtyr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.redwolf501.top/Article/details/gtzmhthmrz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yanxiufei.cn/Article/details/gtzycfthku.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangdashe.top/Article/details/gtgsogcnar.html

[N04] 斐波那契数列
来源：http://dali.tanke756.top/Article/details/gtyevwiqmh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gtiuqkwjix.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.birdmap.top/Article/details/gtomszlhza.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gtzwvwtuyz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtpgvmkpmq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gtxkzzfruk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aibaodan.cn/Article/details/gtlxvrbpmr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gtbojevmdc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gtpnfaosnf.html

[N05] 最大公约数
来源：http://dali.0kj1m.cn/Article/details/gtfwqneegc.html

Py:   math.gcd(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtaunvjbld.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gaohongyu789.top/Article/details/gthgqeqrtd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gtinoxixqk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gtglwemlzj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuanzx.com/Article/details/gtvttmvyed.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnqzz.top/Article/details/gtjkazworw.html

Ruby: a.gcd(b)
来源：http://dali.svipenyu.cn/Article/details/gtqvnrrejh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gotoacloud.top/Article/details/gtjolrobuy.html

[N06] 判断回文字符串
来源：http://dali.yvedp.cn/Article/details/gtbymmatgk.html

Py:   s == s[::-1]
来源：http://dali.sweek.top/Article/details/gteordwkeb.html

PHP:  $s === strrev($s);
来源：http://dali.zycfv.cn/Article/details/gtodphaqoz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtughjojln.html

TS:   s === [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtawovadra.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cheryme.top/Article/details/gtlnzicycg.html

Go:   // 双指针从两端比较
来源：http://dali.cashguo.top/Article/details/gtxhieezxx.html

Ruby: s == s.reverse
来源：http://dali.yuanzhike.top/Article/details/gtrddgxzmj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.meibo888.top/Article/details/gtmwrqgrls.html

[N07] 两数之和（返回下标）
来源：http://dali.quarkkingdee.top/Article/details/gthhhubxuy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnxiangtu.top/Article/details/gtzajfpwlc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cdnleiting.top/Article/details/gtqzsfqsug.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.9152youxi.cn/Article/details/gtltdsoats.html

TS:   // 手写 Map<string, number>
来源：http://dali.ppjwa.cn/Article/details/gtecurqubq.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangtech.top/Article/details/gtopwoljoo.html

Go:   // 手写 map[int]int
来源：http://dali.zhixingplan.top/Article/details/gtnxlnztrs.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gtggwznumx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gaohongyu789.top/Article/details/gtkvjbjkhs.html

[N08] 生成全排列
来源：http://dali.chenlongwang.top/Article/details/gtvtsnwbet.html

Py:   itertools.permutations(arr)
来源：http://dali.mhx1999.top/Article/details/gtersevwcy.html

PHP:  // 手写递归交换
来源：http://dali.havefunace.top/Article/details/gtlpsuuizl.html

JS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gttmqswcfj.html

TS:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtyoktxobo.html

Java: // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtljoqyxfh.html

Go:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtjtrebttm.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258888.top/Article/details/gtazrtqyit.html

C#:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gthljaoypd.html

[N09] 栈与队列
来源：http://dali.redwolf501.top/Article/details/gtktxjoigg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ydzc1.top/Article/details/gtlmcmgcax.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtpqznfeqo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gthrsjvoah.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ehwqpu.com/Article/details/gtvusvnzco.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gtscdziyvq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gogol.net.cn/Article/details/gtrkxsdpdj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gttzirkifg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hfpthk.cn/Article/details/gtxjcbgcsu.html

[N10] 链表节点定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbbhqkih.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.birdmap.top/Article/details/gtagmoymin.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.fzhhl.top/Article/details/gtfnkymmkb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tianlin.xyz/Article/details/gtgofsohyc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hysaishi.cn/Article/details/gtmtfbnrvm.html

Java: class Node { int v; Node next; }
来源：http://dali.aizwys.cn/Article/details/gtjpsjpgex.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tanke756.top/Article/details/gthlkukpnf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yongpay.top/Article/details/gtewvxumoi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxiihsrp.html

[N11] 二叉树中序遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtyqspiafn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hfpthk.cn/Article/details/gtnuhumaip.html

PHP:  // 手写递归函数
来源：http://dali.sxryk.cn/Article/details/gttwhxnohb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.smart0.xyz/Article/details/gtashxgujy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuanzx.com/Article/details/gtdubogyez.html

Java: // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtkiqtqsda.html

Go:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtowhdbogf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xziqi.cn/Article/details/gtfjwdgpvo.html

C#:   // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gtgbpwvvnw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gogol.net.cn/Article/details/gtujquefqv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aizwys.cn/Article/details/gtqlfyyhmd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fengsongda.top/Article/details/gthbpirnvs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ppjwa.cn/Article/details/gttclzfpfi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gtvkrffqwp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gtqlbskeyo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhixingplan.top/Article/details/gtzkvtacnl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.kuanghao11.cn/Article/details/gtcglqdlyj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqsfrcgd.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtqsnciynd.html

O. 并发与异步
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwqrygwa.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gttfjhdatm.html

[O01] 启动一个线程
来源：http://dali.daxiang520.top/Article/details/gthxochvsx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sxryk.cn/Article/details/gtivivjzej.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.svipenyu.cn/Article/details/gtuvdgheih.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daxiang520.top/Article/details/gtnqtmmuvq.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gtzbrgjzim.html

Java: new Thread(() -> f()).start()
来源：http://dali.smart0.xyz/Article/details/gtgetxjevy.html

Go:   go f()
来源：http://dali.gotoacloud.top/Article/details/gtdwcwvnaw.html

Ruby: Thread.new { f }
来源：http://dali.shuidangran.top/Article/details/gtskdmfusy.html

C#:   Task.Run(() => F());
来源：http://dali.9152youxi.cn/Article/details/gtiagfcntm.html

[O02] 使用线程池
来源：http://dali.tian-w.cn/Article/details/gtskyqlkwk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tianlin.xyz/Article/details/gtlzsgrdwt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gzhubu.top/Article/details/gthiswonyy.html

JS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gtcoivjvbl.html

TS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtiadxwemz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daria6918.cn/Article/details/gtxghcaqxw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnqzz.top/Article/details/gttkxdycyx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.feifeiyinyue.top/Article/details/gtyutdyxpm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxblpikc.html

[O03] 加锁保护共享数据
来源：http://dali.smart0.xyz/Article/details/gtzmdcnaer.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gtzktszmjm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hongshengwenyu.top/Article/details/gthtncaepe.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sufxvd.cn/Article/details/gtgatkqaps.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gtsadmurbg.html

Java: synchronized (this) { shared++; }
来源：http://dali.cqqwz.cn/Article/details/gtaryyzopb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jiagoushi.top/Article/details/gtandcwkog.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yanxiufei.cn/Article/details/gtwsyppggc.html

C#:   lock (gate) { shared++; }
来源：http://dali.sufxvd.cn/Article/details/gtbgnoqxpc.html

[O04] 定义异步函数并等待
来源：http://dali.hysaishi.cn/Article/details/gtplqxbycp.html

Py:   async def f():⏎    await g()
来源：http://dali.sxryk.cn/Article/details/gtzttlbxeg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cqqwz.cn/Article/details/gtybnyukik.html

JS:   async function f() { await g(); }
来源：http://dali.tanke756.top/Article/details/gtbzmosbga.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.birdmap.top/Article/details/gthofdqxsv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.smart0.xyz/Article/details/gtojpdxhop.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfnddyrx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yongpay.top/Article/details/gtoisfvszj.html

C#:   async Task F() { await G(); }
来源：http://dali.gaohongyu789.top/Article/details/gtbwukudcm.html

[O05] 并发执行并等待全部完成
来源：http://dali.c1oappe.top/Article/details/gtzinniizc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tian-w.cn/Article/details/gtzzzxyxrx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxinkj.top/Article/details/gtcylvnkub.html

JS:   await Promise.all(tasks)
来源：http://dali.meibo888.top/Article/details/gtzjfuzrcj.html

TS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtwzmoseqr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pycfn.com/Article/details/gtadoovbwr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.smart0.xyz/Article/details/gtlsytpefe.html

Ruby: threads.map(&:join)
来源：http://dali.shangyingyoupin.top/Article/details/gtyrbqnypy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xziqi.cn/Article/details/gtpfzkqdzm.html

[O06] 使用进程池
来源：http://dali.nanxinkj.top/Article/details/gtlhevwnge.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigufen.top/Article/details/gtqylypmhd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.smart0.xyz/Article/details/gtmzezbchz.html

JS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gtxufvbsss.html

TS:   // child_process / cluster 模块
来源：http://dali.wangshuangyany.cn/Article/details/gtrlwteigv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cucudq.cn/Article/details/gtuyyesvpe.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xinyue.icu/Article/details/gtppmgbvjt.html

Ruby: // fork 块
来源：http://dali.hnqzz.top/Article/details/gttdbudpob.html

C#:   Parallel.For
来源：http://dali.birdmap.top/Article/details/gtstxdxkov.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtxrrkgwuj.html

P. 常用工具函数
来源：http://dali.cqqwz.cn/Article/details/gtsnrwppaa.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtwrhwukzw.html

[P01] 生成 UUID
来源：http://dali.yj202588.top/Article/details/gthwpekdld.html

Py:   str(uuid.uuid4())
来源：http://dali.jinqigfzy.top/Article/details/gtyziyebyu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenzaomai.com/Article/details/gtdqpolyiw.html

JS:   crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gtjwavpiji.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gtcjvgmiii.html

Java: UUID.randomUUID().toString()
来源：http://dali.yvedp.cn/Article/details/gtoclwfcyt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hywenlv.cn/Article/details/gtyieudfil.html

Ruby: SecureRandom.uuid
来源：http://dali.bjfxy.top/Article/details/gtwzszclah.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pycfn.com/Article/details/gtjhrpcnrt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgufenzy.top/Article/details/gtymajrzyo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ydzc1.top/Article/details/gtzfnkcrzs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.9152youxi.cn/Article/details/gtzjiawygm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.haohaochexian.top/Article/details/gtkrzoryuf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.smart0.xyz/Article/details/gtdlfiylqy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yangfankeji.com/Article/details/gtbcdldnim.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgufenzy.top/Article/details/gtlvbdhxgo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fzhhl.top/Article/details/gtwtszokmb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.vqdsnc.cn/Article/details/gtxkgqpdxk.html

[P03] 生成短随机字符串
来源：http://dali.jiagoushi.top/Article/details/gtkoqzldym.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yvedp.cn/Article/details/gthgvjbmyf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zycfv.cn/Article/details/gtqwyhfvou.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aizwys.cn/Article/details/gtjdolnjwi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jianghu66.top/Article/details/gtvetbrpuv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.meibo888.top/Article/details/gtsdbvxuac.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhongyouzk.top/Article/details/gtmjldqhir.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.andypj.xyz/Article/details/gtsrrgalxe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenjidiqi.icu/Article/details/gtcwlildqe.html

[P04] 求长度
来源：http://dali.jqgfzy.top/Article/details/gtsvluzutj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.vqdsnc.cn/Article/details/gtfbjmndww.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtgcyjztcp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gtposrkkyy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdihjefw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgfzy.top/Article/details/gtobkyrhwe.html

Go:   len(arr);  len(m)
来源：http://dali.guannengcc.top/Article/details/gtioqwepup.html

Ruby: x.length;  x.size
来源：http://dali.cqqwz.cn/Article/details/gtzllcskhm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jyoumei.cn/Article/details/gtmgwhvgfs.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jqgfzy.top/Article/details/gtoexspccc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shzxlz.cn/Article/details/gtptntruqo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hywenlv.cn/Article/details/gtocgznrfa.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuanzhike.top/Article/details/gtvdqfzoca.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258.top/Article/details/gtfyvbozgt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gttqbjsgka.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gthyiufuol.html

Ruby: a == b
来源：http://dali.hysaishi.cn/Article/details/gtccxxahmu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yangfankeji.com/Article/details/gtpcfpdwpm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangshuangyany.cn/Article/details/gtszvxdhxd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ppjwa.cn/Article/details/gtofmvvxmw.html

PHP:  if (empty($x)) {}
来源：http://dali.tian-w.cn/Article/details/gtgunevxpz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj202588.top/Article/details/gtplwqrmkx.html

TS:   if (x == null) {}
来源：http://dali.hnxiangtu.top/Article/details/gtachatoax.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gtetieqaqb.html

Go:   if x == nil {}
来源：http://dali.tianlin.xyz/Article/details/gtuzrmleur.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tanke756.top/Article/details/gtulgggghd.html

C#:   if (x is null) {}
来源：http://dali.cheryme.top/Article/details/gtazyfgmli.html

[P07] 防抖与节流
来源：http://dali.daxiang520.top/Article/details/gtaxxnidew.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.guowangkeji.top/Article/details/gtyimorwir.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258.top/Article/details/gtcfcbomty.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtzkwjcjar.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cheryme.top/Article/details/gtkjznrmqp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhengqikj.top/Article/details/gtesfosuyo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.feifeiyinyue.top/Article/details/gtswgfjrzh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.guowangkeji.top/Article/details/gtdscmkcak.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gogol.net.cn/Article/details/gtmxcxvrer.html

[P08] 处理浮点精度问题
来源：http://dali.zhiwuduotai.top/Article/details/gtkxoyfnmh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tanke756.top/Article/details/gtgjywemvw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubegxush.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.316326.xyz/Article/details/gthnwbsrmg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cqqwz.cn/Article/details/gtljmcigvl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.meibo888.top/Article/details/gtpkmttdks.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ppjwa.cn/Article/details/gteqwzttlr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangdashe.top/Article/details/gttrktypdy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yuxming.cn/Article/details/gtjamivgoe.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtwblwqmgq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.dianchejie.cn/Article/details/gtzfzjsrdh.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtjhczazbh.html

[Q01] 创建表
来源：http://dali.gogol.net.cn/Article/details/gtaissixca.html

CREATE TABLE users (
来源：http://dali.gogol.net.cn/Article/details/gtqzpjnlvx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cucudq.cn/Article/details/gtnvoorqea.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvyfbfeie.html

email VARCHAR(100) UNIQUE,
来源：http://dali.mhx1999.top/Article/details/gtjsyheayg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zycfv.cn/Article/details/gtcwvwwsit.html

);
来源：http://dali.hnqzz.top/Article/details/gtcivuzhzr.html

[Q02] 创建带外键的表
来源：http://dali.xuanzx.com/Article/details/gtwlworerp.html

CREATE TABLE orders (
来源：http://dali.316326.xyz/Article/details/gtstchbynm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fzhhl.top/Article/details/gtmhiuvdtb.html

user_id INT NOT NULL,
来源：http://dali.zycfv.cn/Article/details/gtqernvwpi.html

amount DECIMAL(10, 2),
来源：http://dali.shuidangran.top/Article/details/gtsqzgxxdx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xziqi.cn/Article/details/gtyuqenhlp.html

);
来源：http://dali.jiagoushi.top/Article/details/gtjuisxyob.html

[Q03] 增加列
来源：http://dali.hnqzz.top/Article/details/gtahxxbnrz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.mhx1999.top/Article/details/gtxixjacwm.html

[Q04] 修改列类型
来源：http://dali.jqgfzy.top/Article/details/gtrtrmuslv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gtlqpwtoht.html

[Q05] 重命名列
来源：http://dali.tianlin.xyz/Article/details/gtichntscr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xylfe.cn/Article/details/gtwyaqfoaz.html

[Q06] 删除列
来源：http://dali.jlsjyb.cn/Article/details/gteinfboxj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nwbrower.top/Article/details/gtugwfmiuf.html

[Q07] 删除表
来源：http://dali.tian-w.cn/Article/details/gtowgrzkki.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nanxinkj.top/Article/details/gttmasoqpy.html

[Q08] 创建普通索引
来源：http://dali.hammf.cn/Article/details/gtgzicsyah.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gtfxdzkngl.html

[Q09] 创建唯一索引
来源：http://dali.yuxming.cn/Article/details/gtkzmxeqfq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.vqdsnc.cn/Article/details/gtyddluxyk.html

[Q10] 插入单行
来源：http://dali.shzxlz.cn/Article/details/gtzrchbqqo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtjrkjugxp.html

[Q11] 一次插入多行
来源：http://dali.fengsongda.top/Article/details/gthoupabfu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.snrcjt.cn/Article/details/gtfzutqcuu.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangtech.top/Article/details/gtbafvkzot.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.quarkkingdee.top/Article/details/gtdybqbmsc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.mhx1999.top/Article/details/gtuxfaqlvx.html

[Q13] 忽略重复插入
来源：http://dali.sxryk.cn/Article/details/gtkhmzputu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nanxinkj.top/Article/details/gtfdxdloku.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuxming.cn/Article/details/gtsvtsmhfv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.bjfxy.top/Article/details/gtuscyweju.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhoulong.xyz/Article/details/gtvwaqxznr.html

[Q15] 查询全部
来源：http://dali.xylfe.cn/Article/details/gtsahazhbi.html


<!-- 参考信息 -->