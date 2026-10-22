代发 wailian999

Py:   if __name__ == "__main__":
来源：http://dali.xylfe.cn/Article/details/gt2jyvnsbpa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sufxvd.cn/Article/details/gt2jufhhujy.html

JS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gt2yejvmpwi.html

TS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gt2srkjepoo.html

Java: public static void main(String[] args)
来源：http://dali.gotoacloud.top/Article/details/gt2wyhnyqid.html

Go:   func main()
来源：http://dali.yj202588.top/Article/details/gt2yhjjsagh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hongshengwenyu.top/Article/details/gt2xwislwij.html

C#:   static void Main(string[] args)
来源：http://dali.hnxiangtu.top/Article/details/gt2qctntcue.html

[M08] 获取系统与运行时信息
来源：http://dali.yvedp.cn/Article/details/gt2silbnkms.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ewgmzooq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sweek.top/Article/details/gt2xhepprew.html

JS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gt2dlazdqez.html

TS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gt2ndtmnjmd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vefapvfm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cucudq.cn/Article/details/gt2gexijxln.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gt2lajqjbdt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenlongwang.top/Article/details/gt2ctmqrswd.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2yotprivy.html

N. 数据结构与算法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2johnfxlg.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2aiawfnxg.html

[N01] 二分查找（有序数组）
来源：http://dali.dashuyun.cn/Article/details/gt2yyhsifru.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gt2gqkwgevf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gt2asejknmx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gt2ubvjelkc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gt2ftdvguyg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tmlouces.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2cmityykx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hammf.cn/Article/details/gt2yatvwbye.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gt2eboxplkm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sysykeji.top/Article/details/gt2eesmgrru.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.redwolf501.top/Article/details/gt2exgporgb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gt2lwmmlkpg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lgjzdene.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gt2ohutnbtv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dianchejie.cn/Article/details/gt2qsrobblp.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gt2rmpipebu.html

Ruby: arr.sort
来源：http://dali.hnxiangtu.top/Article/details/gt2dirmiemt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.bjfxy.top/Article/details/gt2lrvdlvcv.html

[N03] 快速排序（分治示例）
来源：http://dali.iojbl.cn/Article/details/gt2opprqyli.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yanxiufei.cn/Article/details/gt2blgkcgrs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daria6918.cn/Article/details/gt2ggjufwbk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gt2jcjdadfb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zycfv.cn/Article/details/gt2dtyaztml.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.feifeiyinyue.top/Article/details/gt2zgvrmuuc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yangfankeji.com/Article/details/gt2tpvhtgeh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hongshengwenyu.top/Article/details/gt2cgvguazd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sysykeji.top/Article/details/gt2lnhjwtkc.html

[N04] 斐波那契数列
来源：http://dali.ehwqpu.com/Article/details/gt2simjaxlr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ozlvktvr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gt2pclbfvug.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gt2wnkdpazv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gt2zlvopvux.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gt2xflfiivs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tanke756.top/Article/details/gt2qondkkyr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2qibmhxbf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gt2mwtnazrc.html

[N05] 最大公约数
来源：http://dali.jqgufenzy.top/Article/details/gt2mdahdcwp.html

Py:   math.gcd(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gt2vtvcjyha.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xinyue.icu/Article/details/gt2ojhibzxf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gt2sezluaka.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gt2vmmmfrnu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zdqjudy.top/Article/details/gt2nwasjpyz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj20258.top/Article/details/gt2gmwzvyix.html

Ruby: a.gcd(b)
来源：http://dali.smart0.xyz/Article/details/gt2olfdxcba.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgufenzy.top/Article/details/gt2jludlsqn.html

[N06] 判断回文字符串
来源：http://dali.wangdashe.top/Article/details/gt2orxhuanr.html

Py:   s == s[::-1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gcgkqxwq.html

PHP:  $s === strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2eejliode.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gt2spbyxdte.html

TS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gt2arhvadsy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sweek.top/Article/details/gt2ovdhlcot.html

Go:   // 双指针从两端比较
来源：http://dali.birdmap.top/Article/details/gt2icieihnt.html

Ruby: s == s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gt2idjwvbhg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gt2kyhyogmo.html

[N07] 两数之和（返回下标）
来源：http://dali.feifeiyinyue.top/Article/details/gt2isexgqmb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ydzc1.top/Article/details/gt2pyybqwqe.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pycfn.com/Article/details/gt2xwaanqzg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ybcxt.top/Article/details/gt2ezgqryuo.html

TS:   // 手写 Map<string, number>
来源：http://dali.ydzc1.top/Article/details/gt2ivwjojbq.html

Java: // 手写 HashMap
来源：http://dali.cqqwz.cn/Article/details/gt2dxjxivat.html

Go:   // 手写 map[int]int
来源：http://dali.sysykeji.top/Article/details/gt2fbonkzhk.html

Ruby: // 手写 Hash
来源：http://dali.chenjidiqi.icu/Article/details/gt2lrrouhpk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xinyue.icu/Article/details/gt2rbvlpybl.html

[N08] 生成全排列
来源：http://dali.gaohongyu789.top/Article/details/gt2ovbrrplm.html

Py:   itertools.permutations(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2czumzjhb.html

PHP:  // 手写递归交换
来源：http://dali.sweek.top/Article/details/gt2tkhsibjc.html

JS:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gt2bvjukukv.html

TS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gt2icdzxwqo.html

Java: // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2erwwckwu.html

Go:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gt2esctawvd.html

Ruby: arr.permutation.to_a
来源：http://dali.quarkkingdee.top/Article/details/gt2tuxfhfbn.html

C#:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gt2asaylelk.html

[N09] 栈与队列
来源：http://dali.pycfn.com/Article/details/gt2fifsklqt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sysykeji.top/Article/details/gt2ehkdkjrg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gt2wbhonoyh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gt2lqgfawmy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.snrcjt.cn/Article/details/gt2wnchstgk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258888.top/Article/details/gt2htkykcaq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.0kj1m.cn/Article/details/gt2ggphhyxm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gt2xplrsqit.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vflehwra.html

[N10] 链表节点定义
来源：http://dali.chenzaomai.com/Article/details/gt2qsuxzkcf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shangyingyoupin.top/Article/details/gt2lbpouuux.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vkmgcbum.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lfskspta.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.feifeiyinyue.top/Article/details/gt2zowqklnu.html

Java: class Node { int v; Node next; }
来源：http://dali.cashguo.top/Article/details/gt2tvemqwpy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tianlin.xyz/Article/details/gt2wqychftd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jiagoushi.top/Article/details/gt2evbyihfi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinqigfzy.top/Article/details/gt2pchlyttq.html

[N11] 二叉树中序遍历
来源：http://dali.ivvv.top/Article/details/gt2pbgzdjff.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fromnekr.html

PHP:  // 手写递归函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2zrxutigj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ybcxt.top/Article/details/gt2lyxhaxum.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gt2biodhnta.html

Java: // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gt2rdjnbuag.html

Go:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2qcgxfnwd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xylfe.cn/Article/details/gt2gcygapti.html

C#:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gt2bhlfnjph.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmsjrpiz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yvedp.cn/Article/details/gt2iqxezscz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sxryk.cn/Article/details/gt2xtuazavn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gt2aclvewlt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fdnhmkkh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yongpay.top/Article/details/gt2ayfrbpbk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.snrcjt.cn/Article/details/gt2earzynik.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenlongwang.top/Article/details/gt2nyznnhpk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cxowtvkg.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2cqfrxoew.html

O. 并发与异步
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2febzvrif.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2zafmtdws.html

[O01] 启动一个线程
来源：http://dali.hywenlv.cn/Article/details/gt2bojstnpp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sufxvd.cn/Article/details/gt2uqstsgpc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhongyouzk.top/Article/details/gt2onrjwqzs.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhongyouzk.top/Article/details/gt2alndqgyi.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2murbftfq.html

Java: new Thread(() -> f()).start()
来源：http://dali.guowangkeji.top/Article/details/gt2uespzain.html

Go:   go f()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rlbfljqe.html

Ruby: Thread.new { f }
来源：http://dali.hnxiangtu.top/Article/details/gt2qbgfynac.html

C#:   Task.Run(() => F());
来源：http://dali.snrcjt.cn/Article/details/gt2ctslrybc.html

[O02] 使用线程池
来源：http://dali.yonumen.top/Article/details/gt2pswyizrg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zdvfhfvr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.svipenyu.cn/Article/details/gt2mdclcznh.html

JS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gt2fjaomynx.html

TS:   // worker_threads 线程池
来源：http://dali.xylfe.cn/Article/details/gt2wabfpuwm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shuidangran.top/Article/details/gt2btbdmfww.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.snrcjt.cn/Article/details/gt2ceadhcfi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.bjfxy.top/Article/details/gt2tyetgycr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.wangdashe.top/Article/details/gt2cpehrssm.html

[O03] 加锁保护共享数据
来源：http://dali.hammf.cn/Article/details/gt2tugtssqd.html

Py:   with lock: shared += 1
来源：http://dali.xziqi.cn/Article/details/gt2zkcilcqn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2whxtvlhg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.aizwys.cn/Article/details/gt2czkgsxzh.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gt2pjnprpwe.html

Java: synchronized (this) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gt2wfqvmhbr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xuetiantiany.cn/Article/details/gt2edloqhwt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenlongwang.top/Article/details/gt2ylknaybc.html

C#:   lock (gate) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gt2irazqtum.html

[O04] 定义异步函数并等待
来源：http://dali.vqdsnc.cn/Article/details/gt2ljbvywom.html

Py:   async def f():⏎    await g()
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkxwbrrf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.havefunace.top/Article/details/gt2vtgabduk.html

JS:   async function f() { await g(); }
来源：http://dali.aizwys.cn/Article/details/gt2hvkhxxuc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gt2ssukihen.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sysykeji.top/Article/details/gt2sslmvubw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yanxiufei.cn/Article/details/gt2cotpslou.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ykjkwfrw.html

C#:   async Task F() { await G(); }
来源：http://dali.ivvv.top/Article/details/gt2luoordqd.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangdashe.top/Article/details/gt2gurnupmw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daria6918.cn/Article/details/gt2jvzeuhfo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.9152youxi.cn/Article/details/gt2dmfphsrn.html

JS:   await Promise.all(tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rqyvnojj.html

TS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gt2ajfmnxcq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.aibaodan.cn/Article/details/gt2bitfvbxe.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangdashe.top/Article/details/gt2mcatoqdc.html

Ruby: threads.map(&:join)
来源：http://dali.gzhubu.top/Article/details/gt2cuyyznuf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cheryme.top/Article/details/gt2binfrgsw.html

[O06] 使用进程池
来源：http://dali.yj202588.top/Article/details/gt2ofqlzgsz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.birdmap.top/Article/details/gt2qbxvhbrr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jianghu66.top/Article/details/gt2tpjxfdcx.html

JS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gt2tksfmokk.html

TS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gt2ddjjxbnx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.smart0.xyz/Article/details/gt2lliednbf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jlsjyb.cn/Article/details/gt2pncwzozj.html

Ruby: // fork 块
来源：http://dali.dashuyun.cn/Article/details/gt2cwcmmdqi.html

C#:   Parallel.For
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eibvawib.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2fnvccbrj.html

P. 常用工具函数
来源：http://dali.daria6918.cn/Article/details/gt2okwttwre.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2mrwlxzlw.html

[P01] 生成 UUID
来源：http://dali.svipenyu.cn/Article/details/gt2evqugsca.html

Py:   str(uuid.uuid4())
来源：http://dali.yvedp.cn/Article/details/gt2lvykblag.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.mhx1999.top/Article/details/gt2cxuvmkfi.html

JS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gt2cruepuef.html

TS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gt2ozcgemvo.html

Java: UUID.randomUUID().toString()
来源：http://dali.pycfn.com/Article/details/gt2lcgeqrho.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cheryme.top/Article/details/gt2hgxtkslk.html

Ruby: SecureRandom.uuid
来源：http://dali.xziqi.cn/Article/details/gt2bzfpsvxu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.316326.xyz/Article/details/gt2hwoohzvx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.aibaodan.cn/Article/details/gt2ldafgcuc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cashguo.top/Article/details/gt2uevcvvdw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fengsongda.top/Article/details/gt2vhljwlqn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yangfankeji.com/Article/details/gt2bgxmiwby.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hywenlv.cn/Article/details/gt2azxotjbr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zotqrldl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xinyue.icu/Article/details/gt2zutcaxdf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2quntywmn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.birdmap.top/Article/details/gt2vnhdwuap.html

[P03] 生成短随机字符串
来源：http://dali.dianchejie.cn/Article/details/gt2ggqaoicv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jlsjyb.cn/Article/details/gt2usdiumac.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.quarkkingdee.top/Article/details/gt2mreadzvl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2scjddtcy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2exvzhkje.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hammf.cn/Article/details/gt2hjrysyns.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xuanzx.com/Article/details/gt2ubatmmvz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ivvv.top/Article/details/gt2kbydmjsr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.andypj.xyz/Article/details/gt2nfnlgwtq.html

[P04] 求长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjmvrlyb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.guannengcc.top/Article/details/gt2jhofnfwt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gt2zcypgwxg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cqmcopil.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dashuyun.cn/Article/details/gt2krnqijdr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iohsflyp.html

Go:   len(arr);  len(m)
来源：http://dali.sufxvd.cn/Article/details/gt2gqfprrtp.html

Ruby: x.length;  x.size
来源：http://dali.sxryk.cn/Article/details/gt2aegopold.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gt2wqkjkjdw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jqgfzy.top/Article/details/gt2pmcjlipk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hfpthk.cn/Article/details/gt2qyzgyzey.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.vqdsnc.cn/Article/details/gt2glrsomyt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.wangdashe.top/Article/details/gt2qfpcysqb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuxming.cn/Article/details/gt2olsoixfh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinqigufen.top/Article/details/gt2blagxqzf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.316326.xyz/Article/details/gt2ewxlirxj.html

Ruby: a == b
来源：http://dali.jqgfzy.top/Article/details/gt2ezyqpncn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnqzz.top/Article/details/gt2gofeniaf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.guowangkeji.top/Article/details/gt2trzrxybl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gotoacloud.top/Article/details/gt2ejognont.html

PHP:  if (empty($x)) {}
来源：http://dali.wangdashe.top/Article/details/gt2ahfnmghk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sweek.top/Article/details/gt2qhleuefv.html

TS:   if (x == null) {}
来源：http://dali.chenlongwang.top/Article/details/gt2hazjwywr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gt2skvfhjou.html

Go:   if x == nil {}
来源：http://dali.dianchejie.cn/Article/details/gt2scakilrd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.c1oappe.top/Article/details/gt2sqwpdaxo.html

C#:   if (x is null) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2dormodhm.html

[P07] 防抖与节流
来源：http://dali.andypj.xyz/Article/details/gt2asdafgbx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sysykeji.top/Article/details/gt2bibvgfgm.html

PHP:  // 手写时间戳比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2ixzfruaz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gt2hlilyiro.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gt2eotgphej.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.mhx1999.top/Article/details/gt2eicoejor.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zdqjudy.top/Article/details/gt2ijeymwda.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hnxiangtu.top/Article/details/gt2cbsuunwa.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sxryk.cn/Article/details/gt2xjzxbbll.html

[P08] 处理浮点精度问题
来源：http://dali.chenjidiqi.icu/Article/details/gt2rsqeiegg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zdqjudy.top/Article/details/gt2bjnwdwrf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ehwqpu.com/Article/details/gt2dzkxfgxw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.snrcjt.cn/Article/details/gt2kmczxwgy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hammf.cn/Article/details/gt2tfiicbfr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gogol.net.cn/Article/details/gt2ouuymedw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sysykeji.top/Article/details/gt2wuwtbdaz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hysaishi.cn/Article/details/gt2kntyygyu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj202588.top/Article/details/gt2zjqpufpd.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2snvfhrlf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nanxuanxn.top/Article/details/gt2tmmkxseq.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2injejiye.html

[Q01] 创建表
来源：http://dali.andypj.xyz/Article/details/gt2feocmcev.html

CREATE TABLE users (
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tjxputoh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.bjfxy.top/Article/details/gt2pednpouy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sufxvd.cn/Article/details/gt2mnjgqjds.html

email VARCHAR(100) UNIQUE,
来源：http://dali.mhx1999.top/Article/details/gt2zhyefqbd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigfzy.top/Article/details/gt2ngnribec.html

);
来源：http://dali.cdnleiting.top/Article/details/gt2iyqexagq.html

[Q02] 创建带外键的表
来源：http://dali.cqqwz.cn/Article/details/gt2jwffcvzd.html

CREATE TABLE orders (
来源：http://dali.meibo888.top/Article/details/gt2bbkbdsef.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xziqi.cn/Article/details/gt2rauwjqia.html

user_id INT NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gt2fzqvrsmn.html

amount DECIMAL(10, 2),
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hycjtlkq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cqqwz.cn/Article/details/gt2bbvvcheo.html

);
来源：http://dali.cqqwz.cn/Article/details/gt2fbhdtodk.html

[Q03] 增加列
来源：http://dali.quarkkingdee.top/Article/details/gt2tfaiwjiq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.smart0.xyz/Article/details/gt2iitopoiz.html

[Q04] 修改列类型
来源：http://dali.ppjwa.cn/Article/details/gt2redvyjtc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.bjfxy.top/Article/details/gt2lxmqfnfl.html

[Q05] 重命名列
来源：http://dali.jianghu66.top/Article/details/gt2zxomhasm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shangyingyoupin.top/Article/details/gt2nlqqnbqz.html

[Q06] 删除列
来源：http://dali.gogol.net.cn/Article/details/gt2frybttpw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuanzhike.top/Article/details/gt2dwtsbure.html

[Q07] 删除表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kxysulxv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ybcxt.top/Article/details/gt2octyllkc.html

[Q08] 创建普通索引
来源：http://dali.nanxinkj.top/Article/details/gt2ccbfprpg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gt2wmoxnrrh.html

[Q09] 创建唯一索引
来源：http://dali.yongpay.top/Article/details/gt2oeplgjae.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gt2lusjwmbw.html

[Q10] 插入单行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ximjstll.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sufxvd.cn/Article/details/gt2nwuxrghb.html

[Q11] 一次插入多行
来源：http://dali.vqdsnc.cn/Article/details/gt2hvjmtkka.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cdnleiting.top/Article/details/gt2mxhmwuqo.html

[Q12] 插入后取自增 ID
来源：http://dali.bjfxy.top/Article/details/gt2fvbxxmaz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zycfv.cn/Article/details/gt2gttwazuh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.guannengcc.top/Article/details/gt2mbjfixzq.html

[Q13] 忽略重复插入
来源：http://dali.shzxlz.cn/Article/details/gt2sjjdxcil.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yueranfly.top/Article/details/gt2qvdxswai.html


<!-- 参考信息 -->