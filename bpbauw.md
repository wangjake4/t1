代发 wailian999

Py:   if __name__ == "__main__":
来源：http://dali.hongshengwenyu.top/Article/details/gtbheftmad.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tian-w.cn/Article/details/gtkjrbsciy.html

JS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gtygwtfkxa.html

TS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gtypxqducq.html

Java: public static void main(String[] args)
来源：http://dali.ydzc1.top/Article/details/gtzcfktglt.html

Go:   func main()
来源：http://dali.smart0.xyz/Article/details/gtketphbyo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shzxlz.cn/Article/details/gtsshroptv.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxdcczfb.html

[M08] 获取系统与运行时信息
来源：http://dali.yuxming.cn/Article/details/gtlfxypumq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ehwqpu.com/Article/details/gtmvbkmwlf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigfzy.top/Article/details/gtytkhjfxf.html

JS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gtipjrybrm.html

TS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gtpftcbppd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yongpay.top/Article/details/gthgrbusxn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sweek.top/Article/details/gtiuzhfwci.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tian-w.cn/Article/details/gtojwpgidp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.vqdsnc.cn/Article/details/gtgfawywne.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtaryrzlct.html

N. 数据结构与算法
来源：http://dali.jinghuilouyu.cn/Article/details/gteuncwrls.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrwzomii.html

[N01] 二分查找（有序数组）
来源：http://dali.xziqi.cn/Article/details/gtvngqlmrz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtfzkcfjvu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cheryme.top/Article/details/gtkagxfpzx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sxryk.cn/Article/details/gtcvzgxqzz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtoxmhfgzz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gtdeyetprw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tanke756.top/Article/details/gtfvbvmyvh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnxiangtu.top/Article/details/gtdxiaeojh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteeskpzoj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zycfv.cn/Article/details/gtsashjuit.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gtcnijjumt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.316326.xyz/Article/details/gtpfrcgzxg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gtghubxaig.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gtrvzgcbbn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shzxlz.cn/Article/details/gtaapuqpxu.html

Go:   slices.Sort(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtdvozmlfd.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gtoakvryyl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhiwuduotai.top/Article/details/gtxfrybauc.html

[N03] 快速排序（分治示例）
来源：http://dali.hnqzz.top/Article/details/gttyyucsbz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinqigfzy.top/Article/details/gtzjktdntu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.316326.xyz/Article/details/gtwpbccebj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gtpbxbmwmx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gtukpefqyr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnxiangtu.top/Article/details/gtmakvrozb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nanxinkj.top/Article/details/gtpvbleaof.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tanke756.top/Article/details/gtcnpjfzxk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwvinozo.html

[N04] 斐波那契数列
来源：http://dali.yuanzhike.top/Article/details/gtuijbomxo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gtcurexkgo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fengsongda.top/Article/details/gtpdpivkzj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtrssfsvcw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gtdnfsgkqd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pengpengdd.cyou/Article/details/gtmbgnkpqv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.feifeiyinyue.top/Article/details/gtfowlcqyn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gtxovnkprd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gtxtsjgzlc.html

[N05] 最大公约数
来源：http://dali.hammf.cn/Article/details/gthloncwfo.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258888.top/Article/details/gtaazazexr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sxryk.cn/Article/details/gtodvsarru.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gtjyfydncq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gtfpdglgml.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangdashe.top/Article/details/gtricaaipc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnqzz.top/Article/details/gtrmuadvgm.html

Ruby: a.gcd(b)
来源：http://dali.quarkkingdee.top/Article/details/gturhvrzyt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hnqzz.top/Article/details/gtbbjwjbgr.html

[N06] 判断回文字符串
来源：http://dali.yvedp.cn/Article/details/gtjekeuygf.html

Py:   s == s[::-1]
来源：http://dali.c1oappe.top/Article/details/gtiifsuaty.html

PHP:  $s === strrev($s);
来源：http://dali.yj20258888.top/Article/details/gtgcldleex.html

JS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtuconzpci.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gthurbuwtm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.dashuyun.cn/Article/details/gtyirvrkpf.html

Go:   // 双指针从两端比较
来源：http://dali.yvedp.cn/Article/details/gtnvwipjpz.html

Ruby: s == s.reverse
来源：http://dali.tian-w.cn/Article/details/gtmzdtnoag.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvcsvlbc.html

[N07] 两数之和（返回下标）
来源：http://dali.hongshengwenyu.top/Article/details/gtjsegjhne.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sufxvd.cn/Article/details/gtgbpbixjf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj202588.top/Article/details/gtpxozmovx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sweek.top/Article/details/gtiippceec.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangkeji.top/Article/details/gthezvimcq.html

Java: // 手写 HashMap
来源：http://dali.wangshuangyany.cn/Article/details/gtqgsanaec.html

Go:   // 手写 map[int]int
来源：http://dali.aibaodan.cn/Article/details/gtjyriomut.html

Ruby: // 手写 Hash
来源：http://dali.c1oappe.top/Article/details/gtcbhtendw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhongyouzk.top/Article/details/gtmrxnnywa.html

[N08] 生成全排列
来源：http://dali.nwbrower.top/Article/details/gtkstiaxmq.html

Py:   itertools.permutations(arr)
来源：http://dali.gogol.net.cn/Article/details/gttlowzgia.html

PHP:  // 手写递归交换
来源：http://dali.9152youxi.cn/Article/details/gthroadfab.html

JS:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtrkivcshq.html

TS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gthjahuovm.html

Java: // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtuwfizfvp.html

Go:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtebkycvqx.html

Ruby: arr.permutation.to_a
来源：http://dali.yvedp.cn/Article/details/gtoulrwiec.html

C#:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtthmzygkh.html

[N09] 栈与队列
来源：http://dali.ehwqpu.com/Article/details/gtmcpblkbn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gotoacloud.top/Article/details/gtkduikkia.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gtmvqmicsh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gtfbvmffli.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cqqwz.cn/Article/details/gtrayqlclm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tanke756.top/Article/details/gtylguhwbe.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hywenlv.cn/Article/details/gtegmtfpmr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtycuxtzty.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tianlin.xyz/Article/details/gtjnhrxqen.html

[N10] 链表节点定义
来源：http://dali.nanxuanxn.top/Article/details/gtapogvnvz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yonumen.top/Article/details/gtxkrjqyrr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ybcxt.top/Article/details/gtojstihzi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daxiang520.top/Article/details/gtzyapjjrv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gotoacloud.top/Article/details/gtulcldvql.html

Java: class Node { int v; Node next; }
来源：http://dali.hnxiangtu.top/Article/details/gtoitujvkn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hysaishi.cn/Article/details/gtjbnsrwnx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.0kj1m.cn/Article/details/gtwqeporsv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmnqpdcal.html

[N11] 二叉树中序遍历
来源：http://dali.yangfankeji.com/Article/details/gtmihgrcjr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aibaodan.cn/Article/details/gtfxozfgxj.html

PHP:  // 手写递归函数
来源：http://dali.daxiang520.top/Article/details/gtbzqdhdap.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gtnokhpjdu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gtfbokoeki.html

Java: // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtfbootgig.html

Go:   // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gtsjfauoch.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jlsjyb.cn/Article/details/gtvvzlgvcy.html

C#:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtvycrknba.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinqigfzy.top/Article/details/gtkqvwlnuz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gzhubu.top/Article/details/gtwifxqndq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xuanzx.com/Article/details/gtvhtefoor.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yueranfly.top/Article/details/gtcanphmhr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gtcyyiigsb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gtflwzwkrj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgunvever.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sxryk.cn/Article/details/gtkqxgppsh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gtmzsujfcq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtskcjascd.html

O. 并发与异步
来源：http://dali.mhx1999.top/Article/details/gtfrftksfs.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtphqtrbsz.html

[O01] 启动一个线程
来源：http://dali.fzhhl.top/Article/details/gtufjsrsow.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fengsongda.top/Article/details/gtptxlbnnw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shuidangran.top/Article/details/gtbugemcuk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.316326.xyz/Article/details/gtbytwlmqj.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gtthwolqrm.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigfzy.top/Article/details/gthpoeggmh.html

Go:   go f()
来源：http://dali.yongpay.top/Article/details/gtpbqkqndr.html

Ruby: Thread.new { f }
来源：http://dali.gaohongyu789.top/Article/details/gtqjmkijlx.html

C#:   Task.Run(() => F());
来源：http://dali.bjfxy.top/Article/details/gtabyjwmfl.html

[O02] 使用线程池
来源：http://dali.hysaishi.cn/Article/details/gtzpravtnu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.pycfn.com/Article/details/gtthhvqnct.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guowangkeji.top/Article/details/gtflnwvzbr.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gtrnhlsrkb.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258.top/Article/details/gtlzzzzuqa.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tianlin.xyz/Article/details/gtisddygfm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hammf.cn/Article/details/gtqscwynqf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cashguo.top/Article/details/gtvqdvagvp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hywenlv.cn/Article/details/gteiofniey.html

[O03] 加锁保护共享数据
来源：http://dali.zdqjudy.top/Article/details/gtutpecdxq.html

Py:   with lock: shared += 1
来源：http://dali.fengsongda.top/Article/details/gtsdxchkif.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.c1oappe.top/Article/details/gtdmclpupd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guannengcc.top/Article/details/gtnavvlpcp.html

TS:   // 同 JS
来源：http://dali.iojbl.cn/Article/details/gtfykcaqxh.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtpjayligs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmxgtdsz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gzhubu.top/Article/details/gtkbkdaeet.html

C#:   lock (gate) { shared++; }
来源：http://dali.wangshuangyany.cn/Article/details/gthhvxehni.html

[O04] 定义异步函数并等待
来源：http://dali.fengsongda.top/Article/details/gtepjthnnv.html

Py:   async def f():⏎    await g()
来源：http://dali.hammf.cn/Article/details/gttlrkdmao.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gogol.net.cn/Article/details/gtbxczcsjz.html

JS:   async function f() { await g(); }
来源：http://dali.9152youxi.cn/Article/details/gtjvresndd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gtmpjrtugg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258.top/Article/details/gtfvurxnny.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.fzhhl.top/Article/details/gtghcutpns.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.c1oappe.top/Article/details/gtljvcvmqu.html

C#:   async Task F() { await G(); }
来源：http://dali.daria6918.cn/Article/details/gtgdrekckl.html

[O05] 并发执行并等待全部完成
来源：http://dali.yvedp.cn/Article/details/gtoohuauuh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangdashe.top/Article/details/gtlhyfphmy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.birdmap.top/Article/details/gtpyvpszwt.html

JS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gtraubyczf.html

TS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gtyqxaifqm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj20258888.top/Article/details/gtzvwlhfms.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvbirvqt.html

Ruby: threads.map(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gtilxzbdnc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhongyouzk.top/Article/details/gthbrszzoc.html

[O06] 使用进程池
来源：http://dali.fzhhl.top/Article/details/gtvwiwpubn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.c1oappe.top/Article/details/gtcboekvcm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuecsvyxa.html

JS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gtjqvbogxy.html

TS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gtseiydpls.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aibaodan.cn/Article/details/gtbyvpwqdb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.aizwys.cn/Article/details/gtqnhuyumw.html

Ruby: // fork 块
来源：http://dali.feifeiyinyue.top/Article/details/gttcgcrpxg.html

C#:   Parallel.For
来源：http://dali.yvedp.cn/Article/details/gtvxszkczt.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcibscncd.html

P. 常用工具函数
来源：http://dali.cheryme.top/Article/details/gtdxmozgpv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtevibdixw.html

[P01] 生成 UUID
来源：http://dali.c1oappe.top/Article/details/gtzehgknns.html

Py:   str(uuid.uuid4())
来源：http://dali.hfpthk.cn/Article/details/gtuuhkwvfh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangshuangyany.cn/Article/details/gthaehhroq.html

JS:   crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gtpdfjoagg.html

TS:   crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gtupiljudv.html

Java: UUID.randomUUID().toString()
来源：http://dali.redwolf501.top/Article/details/gtphmxnekx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sufxvd.cn/Article/details/gtuxiofbmd.html

Ruby: SecureRandom.uuid
来源：http://dali.xylfe.cn/Article/details/gtjgtfwwnz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tian-w.cn/Article/details/gtfutixrpb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigufen.top/Article/details/gtxhiqpyax.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hysaishi.cn/Article/details/gtiflwosii.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.andypj.xyz/Article/details/gtoegmghbd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.fengsongda.top/Article/details/gtwleidfjh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytykyady.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gotoacloud.top/Article/details/gtkwbayptj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yongpay.top/Article/details/gtsnkyfhwo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sweek.top/Article/details/gtocrwbane.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shzxlz.cn/Article/details/gtjslrdkod.html

[P03] 生成短随机字符串
来源：http://dali.sysykeji.top/Article/details/gtwlbkwtch.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jiagoushi.top/Article/details/gtcrtvwpwa.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yonumen.top/Article/details/gteybwmizw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258888.top/Article/details/gtltfhjdyy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gaohongyu789.top/Article/details/gtnhfaqbwm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yanxiufei.cn/Article/details/gtfjmommmp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.daria6918.cn/Article/details/gtmcnatdpo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxinkj.top/Article/details/gtkkakikvo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jlsjyb.cn/Article/details/gtmbgatoma.html

[P04] 求长度
来源：http://dali.vqdsnc.cn/Article/details/gtkxwpdsmy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.snrcjt.cn/Article/details/gtwnayvupu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtkkeproii.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gtmemherra.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxvveftx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.smart0.xyz/Article/details/gtyhqwexzh.html

Go:   len(arr);  len(m)
来源：http://dali.yvedp.cn/Article/details/gtdxkfvrfz.html

Ruby: x.length;  x.size
来源：http://dali.ybcxt.top/Article/details/gtumtxnphs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zdqjudy.top/Article/details/gthnfrkbgx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tian-w.cn/Article/details/gtiagcmzmc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigufen.top/Article/details/gthuabdqfv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gogol.net.cn/Article/details/gtcfjlascq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrgrrhqw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.316326.xyz/Article/details/gtryyipoat.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nwbrower.top/Article/details/gtzpxrpxyq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtsjxarspa.html

Ruby: a == b
来源：http://dali.tian-w.cn/Article/details/gtyurfpmiz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cqqwz.cn/Article/details/gtxfsuduhw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yonumen.top/Article/details/gtfzbapsyp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cucudq.cn/Article/details/gtlwlrevwk.html

PHP:  if (empty($x)) {}
来源：http://dali.c1oappe.top/Article/details/gtbicmmkva.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sysykeji.top/Article/details/gtzvdayxvw.html

TS:   if (x == null) {}
来源：http://dali.cashguo.top/Article/details/gtmbgrhtjy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtfcorcwdh.html

Go:   if x == nil {}
来源：http://dali.cashguo.top/Article/details/gtqjnmfyso.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.fzhhl.top/Article/details/gtfqmwwvvb.html

C#:   if (x is null) {}
来源：http://dali.zycfv.cn/Article/details/gtfqlsisun.html

[P07] 防抖与节流
来源：http://dali.jiagoushi.top/Article/details/gtpxhfaith.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.guannengcc.top/Article/details/gtyndntoit.html

PHP:  // 手写时间戳比较
来源：http://dali.tian-w.cn/Article/details/gtocthwmgg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnydkcab.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gtvbpwqksp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.redwolf501.top/Article/details/gttouayudm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shanyushiyangtech.top/Article/details/gttmizgavf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fengsongda.top/Article/details/gtgtdpeiuu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gzhubu.top/Article/details/gtkuusyqbv.html

[P08] 处理浮点精度问题
来源：http://dali.redwolf501.top/Article/details/gtkwxgtdam.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.havefunace.top/Article/details/gtpnoshrot.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhoulong.xyz/Article/details/gtymzftqaq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yangfankeji.com/Article/details/gtucnhoogk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxaxvtls.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hnxiangtu.top/Article/details/gtlrovwkxi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hammf.cn/Article/details/gtkxddgznc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hnxiangtu.top/Article/details/gtccphxicq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.birdmap.top/Article/details/gtiqwnqwkj.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbknqdrz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jlsjyb.cn/Article/details/gtwdeecbcr.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtkodhzpfk.html

[Q01] 创建表
来源：http://dali.bjfxy.top/Article/details/gteqqdmqbz.html

CREATE TABLE users (
来源：http://dali.chenzaomai.com/Article/details/gtlzorksoi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.feifeiyinyue.top/Article/details/gtifwmxbnt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gtehmfrbeb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sysykeji.top/Article/details/gtnfjykjac.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jqgufenzy.top/Article/details/gtnqgbxsyd.html

);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitlrltti.html

[Q02] 创建带外键的表
来源：http://dali.tianlin.xyz/Article/details/gtnbhawhlq.html

CREATE TABLE orders (
来源：http://dali.nwbrower.top/Article/details/gtgfhnlcuv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ybcxt.top/Article/details/gtsjxqhorb.html

user_id INT NOT NULL,
来源：http://dali.redwolf501.top/Article/details/gtaetxvuhu.html

amount DECIMAL(10, 2),
来源：http://dali.xylfe.cn/Article/details/gthpcuhlvc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shuidangran.top/Article/details/gtnxkqgyul.html

);
来源：http://dali.cheryme.top/Article/details/gtgbdhctma.html

[Q03] 增加列
来源：http://dali.jianghu66.top/Article/details/gtpnpxgjel.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinqigfzy.top/Article/details/gthbpypqfv.html

[Q04] 修改列类型
来源：http://dali.fzhhl.top/Article/details/gtwdcbtpqj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gtoveoyucg.html

[Q05] 重命名列
来源：http://dali.cucudq.cn/Article/details/gtqguvmkzt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sysykeji.top/Article/details/gtvvsgjoov.html

[Q06] 删除列
来源：http://dali.ivvv.top/Article/details/gtimgqpjqr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.quarkkingdee.top/Article/details/gtfyltiylh.html

[Q07] 删除表
来源：http://dali.xziqi.cn/Article/details/gtmoxjzbgz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ivvv.top/Article/details/gtqtkukmfe.html

[Q08] 创建普通索引
来源：http://dali.shzxlz.cn/Article/details/gtycxxmavo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.dianchejie.cn/Article/details/gtikwssufr.html

[Q09] 创建唯一索引
来源：http://dali.chenlongwang.top/Article/details/gtdvbtfupw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tanke756.top/Article/details/gtjsdqeveo.html

[Q10] 插入单行
来源：http://dali.xylfe.cn/Article/details/gtbtevpghg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtzrnxifqz.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gtkvmqkkjg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sysykeji.top/Article/details/gtklzcluxe.html

[Q12] 插入后取自增 ID
来源：http://dali.sxryk.cn/Article/details/gtwtancifp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.guowangkeji.top/Article/details/gtlbffwljd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnugwxows.html

[Q13] 忽略重复插入
来源：http://dali.nanxinkj.top/Article/details/gtgfkvslsz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.andypj.xyz/Article/details/gtfpycmcnt.html


<!-- 参考信息 -->