代发 wailian999

Java: public static void main(String[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gtddkrfzut.html

Go:   func main()
来源：http://dali.aibaodan.cn/Article/details/gtnzspuvgl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.svipenyu.cn/Article/details/gtybhslxih.html

C#:   static void Main(string[] args)
来源：http://dali.c1oappe.top/Article/details/gtouyxodkp.html

[M08] 获取系统与运行时信息
来源：http://dali.sysykeji.top/Article/details/gtzekkawtb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yanxiufei.cn/Article/details/gtlulxgcng.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.svipenyu.cn/Article/details/gtoimrmvag.html

JS:   process.platform;  process.version
来源：http://dali.xuanzx.com/Article/details/gtrizvdqzw.html

TS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gtfmntuoen.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.havefunace.top/Article/details/gtyfauttnt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pycfn.com/Article/details/gtrspjqufl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.birdmap.top/Article/details/gtoufbkdcx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.kuanghao11.cn/Article/details/gtqmbgmpap.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtaflnwkys.html

N. 数据结构与算法
来源：http://dali.kuanghao11.cn/Article/details/gtidbxbwut.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtfnsbenlp.html

[N01] 二分查找（有序数组）
来源：http://dali.vqdsnc.cn/Article/details/gtbfqlykuk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtyklcysgd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tanke756.top/Article/details/gtjwnjvgpy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gtrpilzwjf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtindpyxpy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtztmpcypm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtfyjtelaq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.redwolf501.top/Article/details/gtjbhsrkdg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtlslorkfx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgufenzy.top/Article/details/gtvbskpesi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtjawzsnsw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtqhrkxwme.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gtfihvijey.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gtjdqagtmh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuetiantiany.cn/Article/details/gtrblkhssb.html

Go:   slices.Sort(arr)
来源：http://dali.tianlin.xyz/Article/details/gthdubbtcs.html

Ruby: arr.sort
来源：http://dali.nanxuanxn.top/Article/details/gtmolyejvu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gotoacloud.top/Article/details/gtluhkicos.html

[N03] 快速排序（分治示例）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoprxadah.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.feifeiyinyue.top/Article/details/gtwtbjigrz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuetiantiany.cn/Article/details/gtwvyvifaa.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gtelmumygr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuanzhike.top/Article/details/gtibroekyr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xylfe.cn/Article/details/gtiafitwsq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ppjwa.cn/Article/details/gtwimdfyyi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.havefunace.top/Article/details/gtwjbscaks.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.bjfxy.top/Article/details/gtnefwoptm.html

[N04] 斐波那契数列
来源：http://dali.zycfv.cn/Article/details/gtvqkqwdes.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gtvvwqmdmm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cashguo.top/Article/details/gtxbpjgspj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtklyoeayn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gtjofoeouw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gtvnbllgef.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xziqi.cn/Article/details/gtjrwtccqe.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtsqlbsthx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtrdxbjzzp.html

[N05] 最大公约数
来源：http://dali.shangyingyoupin.top/Article/details/gtlipogxhu.html

Py:   math.gcd(a, b)
来源：http://dali.daxiang520.top/Article/details/gtnmlgwgqj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ppjwa.cn/Article/details/gtakkjqfix.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtwtwcwbne.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gtmhgkczeb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.iojbl.cn/Article/details/gtllwdipfp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.birdmap.top/Article/details/gttvddpilg.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gtplzouwot.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sysykeji.top/Article/details/gtxwjzotgl.html

[N06] 判断回文字符串
来源：http://dali.jiagoushi.top/Article/details/gtcvbjdxgt.html

Py:   s == s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gtrffilpbv.html

PHP:  $s === strrev($s);
来源：http://dali.jinqigfzy.top/Article/details/gtsyfkwuui.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtunzyrkld.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgeutsrmp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipurgzks.html

Go:   // 双指针从两端比较
来源：http://dali.yj20258.top/Article/details/gtmgnowhnz.html

Ruby: s == s.reverse
来源：http://dali.ydzc1.top/Article/details/gtdmkshxph.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aibaodan.cn/Article/details/gtijpdaxmx.html

[N07] 两数之和（返回下标）
来源：http://dali.yuxming.cn/Article/details/gtzklqezkb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fzhhl.top/Article/details/gtlnzoxplt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinyuanbaomall.cn/Article/details/gterbeeybv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.meibo888.top/Article/details/gtvmpnzvon.html

TS:   // 手写 Map<string, number>
来源：http://dali.xylfe.cn/Article/details/gtxcofrkyd.html

Java: // 手写 HashMap
来源：http://dali.fengsongda.top/Article/details/gtulvsticp.html

Go:   // 手写 map[int]int
来源：http://dali.jianghu66.top/Article/details/gtgnqsmaki.html

Ruby: // 手写 Hash
来源：http://dali.ehwqpu.com/Article/details/gtguttenxj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cucudq.cn/Article/details/gtrtufqumh.html

[N08] 生成全排列
来源：http://dali.pengpengdd.cyou/Article/details/gtnrqenjts.html

Py:   itertools.permutations(arr)
来源：http://dali.zhengqikj.top/Article/details/gtyghlupkl.html

PHP:  // 手写递归交换
来源：http://dali.dianchejie.cn/Article/details/gtspxxnlcd.html

JS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtrpiuzkta.html

TS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfodusnuv.html

Java: // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtaqyjcegz.html

Go:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gttkgmempy.html

Ruby: arr.permutation.to_a
来源：http://dali.daxiang520.top/Article/details/gtishacpuz.html

C#:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtovkreqmj.html

[N09] 栈与队列
来源：http://dali.guowangkeji.top/Article/details/gtfbdcxrvv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xinyue.icu/Article/details/gtdbwwwccq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gtahabtpnr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtwrmrrxtl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.andypj.xyz/Article/details/gtdrddisja.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gtjpuhypjm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zdqjudy.top/Article/details/gtfdlkfhmj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gtdrdtmmvw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gotoacloud.top/Article/details/gtnbfltlqw.html

[N10] 链表节点定义
来源：http://dali.zycfv.cn/Article/details/gtjqbienkz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.wangdashe.top/Article/details/gtxxqgbyzj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.wangdashe.top/Article/details/gtgnhmeaci.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shuidangran.top/Article/details/gthpakzxba.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdygasadg.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigfzy.top/Article/details/gtrsqjzadk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hfpthk.cn/Article/details/gtuenhfrmi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgfzy.top/Article/details/gtqiuetgvr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sufxvd.cn/Article/details/gtfgkvnmmx.html

[N11] 二叉树中序遍历
来源：http://dali.iojbl.cn/Article/details/gtxwnwfxrk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yueranfly.top/Article/details/gtvuwgpxjn.html

PHP:  // 手写递归函数
来源：http://dali.sxryk.cn/Article/details/gtngitvbnw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gtsnydhbqs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pengpengdd.cyou/Article/details/gtgbxxawmp.html

Java: // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gtffqbotar.html

Go:   // 手写递归
来源：http://dali.gzhubu.top/Article/details/gtxqnauppm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.c1oappe.top/Article/details/gtbuxphzfh.html

C#:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gtfjoypjwb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.dashuyun.cn/Article/details/gtanaevceq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenlongwang.top/Article/details/gtzdqphbdv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj20258888.top/Article/details/gtvbckdkqy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gtljylxniz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pycfn.com/Article/details/gttqidgjwm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gtoovqofxw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hfpthk.cn/Article/details/gtduvuurvh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yanxiufei.cn/Article/details/gtuwdhibjo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gtyremeesg.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtmhxjdgpp.html

O. 并发与异步
来源：http://dali.feifeiyinyue.top/Article/details/gtuyecjgvw.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gttwyfsmwe.html

[O01] 启动一个线程
来源：http://dali.hnqzz.top/Article/details/gtidgjjexd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ybcxt.top/Article/details/gtpmbhmsub.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258888.top/Article/details/gtedfrmwrm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenjidiqi.icu/Article/details/gtszzkfuaz.html

TS:   // 同 JS
来源：http://dali.iojbl.cn/Article/details/gtgjuxumhh.html

Java: new Thread(() -> f()).start()
来源：http://dali.316326.xyz/Article/details/gtqnmsavuw.html

Go:   go f()
来源：http://dali.jinqigfzy.top/Article/details/gtvoqmtwmz.html

Ruby: Thread.new { f }
来源：http://dali.yangfankeji.com/Article/details/gtuclgftof.html

C#:   Task.Run(() => F());
来源：http://dali.fengsongda.top/Article/details/gtkiwjnpsi.html

[O02] 使用线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtlgeawxua.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hfpthk.cn/Article/details/gtjwgutcem.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangdashe.top/Article/details/gtyywikmjf.html

JS:   // worker_threads 线程池
来源：http://dali.cashguo.top/Article/details/gtprcbzdau.html

TS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gtsmmllxkp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xinyue.icu/Article/details/gtvxbkjjbc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shangyingyoupin.top/Article/details/gtrkutjuba.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fzhhl.top/Article/details/gteolvryph.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hammf.cn/Article/details/gtjvylrtbq.html

[O03] 加锁保护共享数据
来源：http://dali.chenlongwang.top/Article/details/gtwbuvqnoq.html

Py:   with lock: shared += 1
来源：http://dali.pengpengdd.cyou/Article/details/gtcxfziqgx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aibaodan.cn/Article/details/gtpkewskxk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xuanzx.com/Article/details/gtkaixajed.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssqznqxt.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj20258.top/Article/details/gtcxkkaheg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.havefunace.top/Article/details/gtwbskucmm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.fzhhl.top/Article/details/gtaekrlocw.html

C#:   lock (gate) { shared++; }
来源：http://dali.316326.xyz/Article/details/gtjkpesnnb.html

[O04] 定义异步函数并等待
来源：http://dali.zdqjudy.top/Article/details/gthtaylpxy.html

Py:   async def f():⏎    await g()
来源：http://dali.dashuyun.cn/Article/details/gthdpiwuvg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dashuyun.cn/Article/details/gtqnxqupmx.html

JS:   async function f() { await g(); }
来源：http://dali.daxiang520.top/Article/details/gtobvwyeeb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yueranfly.top/Article/details/gttaaeevvy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangshuangyany.cn/Article/details/gtdframtqg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.wangdashe.top/Article/details/gtpyhrbsfx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj202588.top/Article/details/gtouhrnfzr.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigfzy.top/Article/details/gtrrimevcz.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuetiantiany.cn/Article/details/gtfetvluiz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.haohaochexian.top/Article/details/gtgjzmvtti.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenjidiqi.icu/Article/details/gtybjwhxyk.html

JS:   await Promise.all(tasks)
来源：http://dali.ydzc1.top/Article/details/gtviygrueh.html

TS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtethmeehs.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.fengsongda.top/Article/details/gthnthnmwj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenjidiqi.icu/Article/details/gtrczhzrgj.html

Ruby: threads.map(&:join)
来源：http://dali.gotoacloud.top/Article/details/gtdyfplonz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigufen.top/Article/details/gtldzfqvxt.html

[O06] 使用进程池
来源：http://dali.shangyingyoupin.top/Article/details/gtykktohgr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhongyouzk.top/Article/details/gtynvkqdxi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtmalnakxf.html

JS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gtyprbajwp.html

TS:   // child_process / cluster 模块
来源：http://dali.zhongyouzk.top/Article/details/gtznxyeyiz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yangfankeji.com/Article/details/gtyhpmeiio.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xylfe.cn/Article/details/gtzzknlolu.html

Ruby: // fork 块
来源：http://dali.316326.xyz/Article/details/gtqgztkkoi.html

C#:   Parallel.For
来源：http://dali.sufxvd.cn/Article/details/gtfmjgnfag.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtxavauoji.html

P. 常用工具函数
来源：http://dali.hfpthk.cn/Article/details/gtmlqpwndy.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtezrcytyk.html

[P01] 生成 UUID
来源：http://dali.aibaodan.cn/Article/details/gthtpeodmf.html

Py:   str(uuid.uuid4())
来源：http://dali.xziqi.cn/Article/details/gtuqfqzkfm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.c1oappe.top/Article/details/gtmpmbdexz.html

JS:   crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gtyazlnoki.html

TS:   crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gtjbviwxbv.html

Java: UUID.randomUUID().toString()
来源：http://dali.yvedp.cn/Article/details/gtylnqscck.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shuidangran.top/Article/details/gthasihgeu.html

Ruby: SecureRandom.uuid
来源：http://dali.zhoulong.xyz/Article/details/gtelqiyymt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gaohongyu789.top/Article/details/gtcumtegnu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ehwqpu.com/Article/details/gttxdfnnjd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gaohongyu789.top/Article/details/gtvmxszsoi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzlhidcv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangshuangyany.cn/Article/details/gtqvzzlpsb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cheryme.top/Article/details/gtlotwewpz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.mhx1999.top/Article/details/gttlvoodow.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsipasojw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ybcxt.top/Article/details/gtlirvgius.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenjidiqi.icu/Article/details/gtswevcqao.html

[P03] 生成短随机字符串
来源：http://dali.havefunace.top/Article/details/gtnqwriopc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuetiantiany.cn/Article/details/gtlrucbsza.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sweek.top/Article/details/gtlppnvoaj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hfpthk.cn/Article/details/gtecbirywt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yvedp.cn/Article/details/gtydxlpeyb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.vqdsnc.cn/Article/details/gtxlfewedm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.havefunace.top/Article/details/gtniqibhqj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.mhx1999.top/Article/details/gtxylrnnoc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sufxvd.cn/Article/details/gtkbumpgkx.html

[P04] 求长度
来源：http://dali.hnxiangtu.top/Article/details/gtsdkaoxdy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nwbrower.top/Article/details/gttxvosyvf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtrkutmdgs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gtmajuuabo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tanke756.top/Article/details/gtirsdgdgf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.svipenyu.cn/Article/details/gtjcjbpcuq.html

Go:   len(arr);  len(m)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkmjsazh.html

Ruby: x.length;  x.size
来源：http://dali.gotoacloud.top/Article/details/gtcjawiero.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvlueufz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthvryeal.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258888.top/Article/details/gtmuawnkqg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj20258.top/Article/details/gtkokyvdco.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqaaeomvj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yvedp.cn/Article/details/gtpgrvcybc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pengpengdd.cyou/Article/details/gtspwgvhbs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyghxqaet.html

Ruby: a == b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfkompkrt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ydzc1.top/Article/details/gtbmeqcrwc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.daria6918.cn/Article/details/gtgpnoyoon.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jianghu66.top/Article/details/gtqdwhjzkc.html

PHP:  if (empty($x)) {}
来源：http://dali.snrcjt.cn/Article/details/gtadynnpyz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guowangkeji.top/Article/details/gtpelulkvk.html

TS:   if (x == null) {}
来源：http://dali.yanxiufei.cn/Article/details/gtpbhzaduj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajytgsir.html

Go:   if x == nil {}
来源：http://dali.xuetiantiany.cn/Article/details/gtivlfvbpm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.0kj1m.cn/Article/details/gtrpxhccfp.html

C#:   if (x is null) {}
来源：http://dali.hammf.cn/Article/details/gtyzvltiae.html

[P07] 防抖与节流
来源：http://dali.ybcxt.top/Article/details/gtpaaqfaid.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ybcxt.top/Article/details/gtpmzwmtpk.html

PHP:  // 手写时间戳比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorrybgft.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gthnqupocw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gtqtzkxbta.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.c1oappe.top/Article/details/gtsancnive.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yonumen.top/Article/details/gtncrhmuvs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sweek.top/Article/details/gtfwsensph.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinqigufen.top/Article/details/gtuxnghpqe.html

[P08] 处理浮点精度问题
来源：http://dali.quarkkingdee.top/Article/details/gtjdtpuovf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shangyingyoupin.top/Article/details/gtjojbqxls.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.redwolf501.top/Article/details/gtgjhabwhp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.iojbl.cn/Article/details/gtemfbmdus.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tanke756.top/Article/details/gtgpajkfhk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.birdmap.top/Article/details/gtfaeqzxha.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnxiangtu.top/Article/details/gtsjbjnuxr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jqgufenzy.top/Article/details/gtsofnhglo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenlongwang.top/Article/details/gtvutsuxcb.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtykahrbla.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258.top/Article/details/gtoeayqbgp.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtusuwaknj.html

[Q01] 创建表
来源：http://dali.zdqjudy.top/Article/details/gtycouzpkl.html

CREATE TABLE users (
来源：http://dali.jianghu66.top/Article/details/gtfdwqbrvq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.havefunace.top/Article/details/gtsngqtkpt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.9152youxi.cn/Article/details/gtasgrcqlw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cashguo.top/Article/details/gtajetqmfq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nanxinkj.top/Article/details/gtvdorlvnc.html

);
来源：http://dali.smart0.xyz/Article/details/gtgsnfliib.html

[Q02] 创建带外键的表
来源：http://dali.hywenlv.cn/Article/details/gthakgiljn.html

CREATE TABLE orders (
来源：http://dali.zycfv.cn/Article/details/gtqyigpckd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cucudq.cn/Article/details/gtpxzjfzbm.html

user_id INT NOT NULL,
来源：http://dali.meibo888.top/Article/details/gtnerpuvnx.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gtbzbpufky.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zycfv.cn/Article/details/gtklrjmgbs.html

);
来源：http://dali.shzxlz.cn/Article/details/gtszuvrsrl.html

[Q03] 增加列
来源：http://dali.daxiang520.top/Article/details/gtrzuunerm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xylfe.cn/Article/details/gtnghfuxka.html

[Q04] 修改列类型
来源：http://dali.xziqi.cn/Article/details/gtvvjwdvqb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.9152youxi.cn/Article/details/gthdtallyi.html

[Q05] 重命名列
来源：http://dali.guannengcc.top/Article/details/gtchljcwvo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.9152youxi.cn/Article/details/gtxralllia.html

[Q06] 删除列
来源：http://dali.fengsongda.top/Article/details/gtoahcdfni.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yvedp.cn/Article/details/gtpcjuosqy.html

[Q07] 删除表
来源：http://dali.tanke756.top/Article/details/gtwagpgpzc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jqgfzy.top/Article/details/gtwebnafyq.html

[Q08] 创建普通索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwskayms.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj20258.top/Article/details/gtpttsucos.html

[Q09] 创建唯一索引
来源：http://dali.pengpengdd.cyou/Article/details/gtelprxdit.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gtmrehqehq.html

[Q10] 插入单行
来源：http://dali.jlsjyb.cn/Article/details/gtisqtzsdu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenlongwang.top/Article/details/gtsffnrwih.html

[Q11] 一次插入多行
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwqrgpip.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gtngdasgfq.html

[Q12] 插入后取自增 ID
来源：http://dali.dashuyun.cn/Article/details/gtxoeqohqu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.316326.xyz/Article/details/gttxrdpprs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gtiqdasljz.html

[Q13] 忽略重复插入
来源：http://dali.aizwys.cn/Article/details/gtfdydhfre.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gtlhyijxrn.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinqigufen.top/Article/details/gtdqmmiulr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.daxiang520.top/Article/details/gtctxsqhko.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xuetiantiany.cn/Article/details/gtvkxvzgjr.html

[Q15] 查询全部
来源：http://dali.sxryk.cn/Article/details/gtpndyqlcv.html


<!-- 参考信息 -->