代发 wailian999

Py:   if __name__ == "__main__":
来源：http://dali.quarkkingdee.top/Article/details/gtbjsatnrs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gtpxzpgrvu.html

JS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gtzhmptkyr.html

TS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gttzxfbzoe.html

Java: public static void main(String[] args)
来源：http://dali.mhx1999.top/Article/details/gtetprzdrl.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gtlgjeauha.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.redwolf501.top/Article/details/gtgogwhoik.html

C#:   static void Main(string[] args)
来源：http://dali.hammf.cn/Article/details/gtnhveevsz.html

[M08] 获取系统与运行时信息
来源：http://dali.xuetiantiany.cn/Article/details/gtlhohkejj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.andypj.xyz/Article/details/gtcfslovxz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenzaomai.com/Article/details/gtaxzztkky.html

JS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gtjbyinjwc.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gtiagthkks.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttywacqnb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhengqikj.top/Article/details/gtcliehdqq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgufenzy.top/Article/details/gtecprsvds.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hywenlv.cn/Article/details/gtsvaobbbn.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gttsvtngqh.html

N. 数据结构与算法
来源：http://dali.gzhubu.top/Article/details/gterunltti.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtneflbdqh.html

[N01] 二分查找（有序数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwekfqzdl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtjaibpuvv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ydzc1.top/Article/details/gtnmfxmqcf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gtghzoovew.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gtucnmwljs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtrjpmnssf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtqfdnmscq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cdnleiting.top/Article/details/gtnepzmrmo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gtogysvbpb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dashuyun.cn/Article/details/gttvgyrdhe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gtebojofrq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yangfankeji.com/Article/details/gtvuqjmyry.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtuzfvrpoe.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gtkucuwuap.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhiwuduotai.top/Article/details/gtebkkpcmx.html

Go:   slices.Sort(arr)
来源：http://dali.tanke756.top/Article/details/gtaojgfbom.html

Ruby: arr.sort
来源：http://dali.jyoumei.cn/Article/details/gtpyagzyvp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfqaahyu.html

[N03] 快速排序（分治示例）
来源：http://dali.hywenlv.cn/Article/details/gtdzojuzih.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aibaodan.cn/Article/details/gtomstvvyy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyrigyvo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gthvcsqaxj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gtqwhoesxv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sysykeji.top/Article/details/gtcluyjspu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.meibo888.top/Article/details/gtgoqbnrkb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pycfn.com/Article/details/gtelwikqpk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tian-w.cn/Article/details/gtqjfiphva.html

[N04] 斐波那契数列
来源：http://dali.yonumen.top/Article/details/gtzlzfwplb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.iojbl.cn/Article/details/gtgmuhbdve.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gtesvfqlis.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtmarwbhio.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtrqswuruy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jyoumei.cn/Article/details/gtjjtdmpac.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.svipenyu.cn/Article/details/gtspwwxwbp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gtzigpdfso.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gtlwlnsynp.html

[N05] 最大公约数
来源：http://dali.cucudq.cn/Article/details/gtbpfnfdef.html

Py:   math.gcd(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtjumblicd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnqccnkre.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gtjxveahqx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gtnemnlqit.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jiagoushi.top/Article/details/gtcllfrjfo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujjihmao.html

Ruby: a.gcd(b)
来源：http://dali.nanxinkj.top/Article/details/gtciokfwtf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jyoumei.cn/Article/details/gtlbagfziz.html

[N06] 判断回文字符串
来源：http://dali.cucudq.cn/Article/details/gtwadrgkpe.html

Py:   s == s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gtffkvlsid.html

PHP:  $s === strrev($s);
来源：http://dali.meibo888.top/Article/details/gtruosoutv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtcivfmbpj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtlmehlnvy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhixingplan.top/Article/details/gtfzogjxcb.html

Go:   // 双指针从两端比较
来源：http://dali.hywenlv.cn/Article/details/gtacpuuorp.html

Ruby: s == s.reverse
来源：http://dali.shuidangran.top/Article/details/gtheoyqfzl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gttrqzhnma.html

[N07] 两数之和（返回下标）
来源：http://dali.yj202588.top/Article/details/gtfjsycztn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yangfankeji.com/Article/details/gtqhkbqqxx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hfpthk.cn/Article/details/gtrmxovvup.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hysaishi.cn/Article/details/gtaxgbcqqj.html

TS:   // 手写 Map<string, number>
来源：http://dali.tian-w.cn/Article/details/gtaazzbdze.html

Java: // 手写 HashMap
来源：http://dali.shuidangran.top/Article/details/gtegiojbgb.html

Go:   // 手写 map[int]int
来源：http://dali.hfpthk.cn/Article/details/gtbamdlpmz.html

Ruby: // 手写 Hash
来源：http://dali.zhoulong.xyz/Article/details/gtglamcnvt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.havefunace.top/Article/details/gtrrefhzxx.html

[N08] 生成全排列
来源：http://dali.meibo888.top/Article/details/gtnnejfrqf.html

Py:   itertools.permutations(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtgzldnfqi.html

PHP:  // 手写递归交换
来源：http://dali.jqgufenzy.top/Article/details/gtzueqdmum.html

JS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtycbuiyuj.html

TS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtzleafldk.html

Java: // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtvrpnames.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvcbxgmo.html

Ruby: arr.permutation.to_a
来源：http://dali.gogol.net.cn/Article/details/gtfmnbqrmz.html

C#:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtxjqaxpkw.html

[N09] 栈与队列
来源：http://dali.dashuyun.cn/Article/details/gtdqsiomcy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zycfv.cn/Article/details/gtdxnqlvja.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtrmkcurwt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtoearlfce.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tian-w.cn/Article/details/gthchkpdzh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.iojbl.cn/Article/details/gtkcxnvdgz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sysykeji.top/Article/details/gtdsqpnhfw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gtpvfcwrdz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dashuyun.cn/Article/details/gtaeohrnsu.html

[N10] 链表节点定义
来源：http://dali.hnxiangtu.top/Article/details/gtkmkdnmce.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenlongwang.top/Article/details/gtabgcxqra.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yangfankeji.com/Article/details/gtiakussqy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hfpthk.cn/Article/details/gtwemqbyop.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cdnleiting.top/Article/details/gtuwzfidnj.html

Java: class Node { int v; Node next; }
来源：http://dali.shangyingyoupin.top/Article/details/gtqlauqdxi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shzxlz.cn/Article/details/gtiqjffitk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sufxvd.cn/Article/details/gtffjlwwrp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fengsongda.top/Article/details/gtylzfpxrq.html

[N11] 二叉树中序遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gthnrxiqin.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aizwys.cn/Article/details/gtgvbkvtyr.html

PHP:  // 手写递归函数
来源：http://dali.tanke756.top/Article/details/gtsmwykbut.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gtygymexrs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gtshjbwhpb.html

Java: // 手写递归
来源：http://dali.yonumen.top/Article/details/gtoocqhvbh.html

Go:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtrrypwxjx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hnxiangtu.top/Article/details/gtwhidttqh.html

C#:   // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gtmioenalb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daxiang520.top/Article/details/gtlfpgclfd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.havefunace.top/Article/details/gtluadekkt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ivvv.top/Article/details/gtpdtubdzs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gtpdmmcual.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gtjqoqtxzr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ydzc1.top/Article/details/gtocpmcbol.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ydzc1.top/Article/details/gtzdyzeurx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ybcxt.top/Article/details/gtezzsqlgq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yongpay.top/Article/details/gtbrxsgznx.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtixvlrqta.html

O. 并发与异步
来源：http://dali.316326.xyz/Article/details/gtnodcokam.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtxsgzoejk.html

[O01] 启动一个线程
来源：http://dali.yj20258.top/Article/details/gtvjnrhmot.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.andypj.xyz/Article/details/gtdwhntiuv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.meibo888.top/Article/details/gtsgelpshm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhoulong.xyz/Article/details/gtrsxwinia.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gtmollokfr.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhoulong.xyz/Article/details/gtinhngqpe.html

Go:   go f()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhyqtbnz.html

Ruby: Thread.new { f }
来源：http://dali.gotoacloud.top/Article/details/gtipxfbqzk.html

C#:   Task.Run(() => F());
来源：http://dali.xylfe.cn/Article/details/gtthkhrlsr.html

[O02] 使用线程池
来源：http://dali.9152youxi.cn/Article/details/gtsedyajiu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhixingplan.top/Article/details/gtzvpckyil.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.9152youxi.cn/Article/details/gtdxsmxpmb.html

JS:   // worker_threads 线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtrcsrrkuk.html

TS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gtlnexsbir.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xziqi.cn/Article/details/gtkgzinbkc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yueranfly.top/Article/details/gtxhwxpwmo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinqigfzy.top/Article/details/gtuhkqfafl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.mhx1999.top/Article/details/gtfrfnpbbu.html

[O03] 加锁保护共享数据
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvqooxjs.html

Py:   with lock: shared += 1
来源：http://dali.kuanghao11.cn/Article/details/gtolsptcji.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.bjfxy.top/Article/details/gtdebfmpnz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zdqjudy.top/Article/details/gtiwznnumz.html

TS:   // 同 JS
来源：http://dali.316326.xyz/Article/details/gtooknebxr.html

Java: synchronized (this) { shared++; }
来源：http://dali.vqdsnc.cn/Article/details/gtzfuamjzb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jlsjyb.cn/Article/details/gtykpqseaf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuxming.cn/Article/details/gtrfbegufz.html

C#:   lock (gate) { shared++; }
来源：http://dali.cheryme.top/Article/details/gtfylxaczz.html

[O04] 定义异步函数并等待
来源：http://dali.xylfe.cn/Article/details/gtmsctsjyb.html

Py:   async def f():⏎    await g()
来源：http://dali.hysaishi.cn/Article/details/gtljkemvlg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikfpdtjn.html

JS:   async function f() { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gttnhtnbot.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yonumen.top/Article/details/gtchclkoil.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.feifeiyinyue.top/Article/details/gtinnxfzxz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xylfe.cn/Article/details/gtfggqckpg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jyoumei.cn/Article/details/gtjjtpalru.html

C#:   async Task F() { await G(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtvfgbcvxx.html

[O05] 并发执行并等待全部完成
来源：http://dali.guannengcc.top/Article/details/gtrpfrjuci.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gogol.net.cn/Article/details/gtteqkayij.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvrvkapz.html

JS:   await Promise.all(tasks)
来源：http://dali.9152youxi.cn/Article/details/gtdugvfzni.html

TS:   await Promise.all(tasks)
来源：http://dali.9152youxi.cn/Article/details/gtntlfvnqi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cucudq.cn/Article/details/gtwsxmfbxc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zycfv.cn/Article/details/gttbgpmpdn.html

Ruby: threads.map(&:join)
来源：http://dali.yuanzhike.top/Article/details/gtembqyhbk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jlsjyb.cn/Article/details/gtndpfceyv.html

[O06] 使用进程池
来源：http://dali.zhoulong.xyz/Article/details/gtlizttdsx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuxming.cn/Article/details/gtgjqhxbuh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zdqjudy.top/Article/details/gtbfjgaunm.html

JS:   // child_process / cluster 模块
来源：http://dali.xuetiantiany.cn/Article/details/gthbwkzwcf.html

TS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gtikvzffpg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ydzc1.top/Article/details/gthugcgyuf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.bjfxy.top/Article/details/gtmjwvrbck.html

Ruby: // fork 块
来源：http://dali.smart0.xyz/Article/details/gtnffmxhab.html

C#:   Parallel.For
来源：http://dali.yueranfly.top/Article/details/gturlbheay.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtwxwefbnx.html

P. 常用工具函数
来源：http://dali.xinyue.icu/Article/details/gtpngcqoec.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtmjzlsacp.html

[P01] 生成 UUID
来源：http://dali.hammf.cn/Article/details/gtvecdefji.html

Py:   str(uuid.uuid4())
来源：http://dali.jianghu66.top/Article/details/gthhmrnzys.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpuiwbyfz.html

JS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gthvcchkpn.html

TS:   crypto.randomUUID()
来源：http://dali.hongshengwenyu.top/Article/details/gtquiogjvw.html

Java: UUID.randomUUID().toString()
来源：http://dali.zycfv.cn/Article/details/gtqkxyxtgq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gogol.net.cn/Article/details/gtmtplpimj.html

Ruby: SecureRandom.uuid
来源：http://dali.bjfxy.top/Article/details/gtvgnegtek.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttgxvsxxm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xinyue.icu/Article/details/gtnwaefajr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.kuanghao11.cn/Article/details/gtahzwvafl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxinkj.top/Article/details/gtjeyyipqw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daria6918.cn/Article/details/gtrvkjmiwm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.vqdsnc.cn/Article/details/gtfyunzwtn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.birdmap.top/Article/details/gtktwltput.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuanzhike.top/Article/details/gtojemqkwv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sxryk.cn/Article/details/gtpewysoze.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhixingplan.top/Article/details/gtjbdtytru.html

[P03] 生成短随机字符串
来源：http://dali.xinyue.icu/Article/details/gtrnauyees.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gaohongyu789.top/Article/details/gtfsqvruof.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgufenzy.top/Article/details/gtlqxyrhrm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gthbrmwegg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgfzy.top/Article/details/gtfpvgxdns.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.meibo888.top/Article/details/gtmrhuvizr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.smart0.xyz/Article/details/gtbmtvrccw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zycfv.cn/Article/details/gtfsfetlon.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.redwolf501.top/Article/details/gtcidjglct.html

[P04] 求长度
来源：http://dali.zhengqikj.top/Article/details/gtqlanotjf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuanzhike.top/Article/details/gtnwqtzqnm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtvrzntxlf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gtfxoxwvob.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xinyue.icu/Article/details/gtosgdueoe.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zdqjudy.top/Article/details/gtugbushhw.html

Go:   len(arr);  len(m)
来源：http://dali.haohaochexian.top/Article/details/gtqiogefgm.html

Ruby: x.length;  x.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxxfblej.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hammf.cn/Article/details/gtlweuxqrc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yonumen.top/Article/details/gtkukycumz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pycfn.com/Article/details/gtzdrnomaf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinghuilouyu.cn/Article/details/gtohggitsn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yvedp.cn/Article/details/gtoqarmdan.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sweek.top/Article/details/gtcjavngri.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.svipenyu.cn/Article/details/gtubvfppxz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.snrcjt.cn/Article/details/gtwbplqomc.html

Ruby: a == b
来源：http://dali.ydzc1.top/Article/details/gtvvihlbby.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hammf.cn/Article/details/gtnnyloykp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.feifeiyinyue.top/Article/details/gtacyzdjtj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.316326.xyz/Article/details/gtddvlihfw.html

PHP:  if (empty($x)) {}
来源：http://dali.yj202588.top/Article/details/gtexvzjcaz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuanzx.com/Article/details/gthsbzukoj.html

TS:   if (x == null) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtkgqacy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinqigufen.top/Article/details/gtyvrhxwak.html

Go:   if x == nil {}
来源：http://dali.pengpengdd.cyou/Article/details/gtsqunpjva.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangshuangyany.cn/Article/details/gtjzbqugyo.html

C#:   if (x is null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovfefzjl.html

[P07] 防抖与节流
来源：http://dali.feifeiyinyue.top/Article/details/gtmltzxclk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yongpay.top/Article/details/gtemuggvlm.html

PHP:  // 手写时间戳比较
来源：http://dali.cucudq.cn/Article/details/gtdefcpire.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gtlcfmckoe.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gtomhkdwzm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gteevtkfkt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.smart0.xyz/Article/details/gtskdaosft.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yonumen.top/Article/details/gtxerfqwfy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gzhubu.top/Article/details/gtugxfocsk.html

[P08] 处理浮点精度问题
来源：http://dali.tianlin.xyz/Article/details/gtbfiynufr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.bjfxy.top/Article/details/gtuxzudvry.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yuanzhike.top/Article/details/gtefhceatp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenlongwang.top/Article/details/gtbtnvwcud.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gtifwimicd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jqgufenzy.top/Article/details/gtrzkcywum.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yvedp.cn/Article/details/gtetvphntd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.snrcjt.cn/Article/details/gtkoydnkpe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.aizwys.cn/Article/details/gtduktxdvo.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtjfwohhma.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ivvv.top/Article/details/gtppqxeegc.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtylbbxmiv.html

[Q01] 创建表
来源：http://dali.xylfe.cn/Article/details/gtvxjhzbwv.html

CREATE TABLE users (
来源：http://dali.guowangkeji.top/Article/details/gtjcfszqqk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gtgvshrrtd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gtchvvyzcd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.smart0.xyz/Article/details/gtwqzndgop.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhoulong.xyz/Article/details/gtbnrzegqu.html

);
来源：http://dali.tianlin.xyz/Article/details/gtmbbcwkbp.html

[Q02] 创建带外键的表
来源：http://dali.ybcxt.top/Article/details/gtngttfjiv.html

CREATE TABLE orders (
来源：http://dali.shzxlz.cn/Article/details/gtyjtvsjok.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gtdxlwlryy.html

user_id INT NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gthjnfyerv.html

amount DECIMAL(10, 2),
来源：http://dali.sxryk.cn/Article/details/gtbnthjrba.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guowangkeji.top/Article/details/gtoevrueer.html

);
来源：http://dali.sweek.top/Article/details/gtfokpptxh.html

[Q03] 增加列
来源：http://dali.gotoacloud.top/Article/details/gtaaazwepn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.redwolf501.top/Article/details/gtocsgsrul.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjyjixyv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tianlin.xyz/Article/details/gtkzfmbkau.html

[Q05] 重命名列
来源：http://dali.jyoumei.cn/Article/details/gtxzrljewz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.mhx1999.top/Article/details/gtdchtpekj.html

[Q06] 删除列
来源：http://dali.ehwqpu.com/Article/details/gtejqkhakt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xylfe.cn/Article/details/gtczokfrqn.html

[Q07] 删除表
来源：http://dali.sufxvd.cn/Article/details/gtsmendvwn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daria6918.cn/Article/details/gtbhuajfiz.html

[Q08] 创建普通索引
来源：http://dali.dashuyun.cn/Article/details/gtntujljfg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gttejsdurb.html

[Q09] 创建唯一索引
来源：http://dali.pengpengdd.cyou/Article/details/gtlngifomv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cqqwz.cn/Article/details/gtffspwwwv.html

[Q10] 插入单行
来源：http://dali.kuanghao11.cn/Article/details/gtvzutjjxe.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtiqiveqhx.html

[Q11] 一次插入多行
来源：http://dali.jinghuilouyu.cn/Article/details/gtnucjsfsn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zycfv.cn/Article/details/gtptbmhmib.html

[Q12] 插入后取自增 ID
来源：http://dali.xylfe.cn/Article/details/gtlepmhueb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.c1oappe.top/Article/details/gtdkukbnwe.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenjidiqi.icu/Article/details/gtpzekqwmf.html

[Q13] 忽略重复插入
来源：http://dali.ivvv.top/Article/details/gtqbgcewjg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sweek.top/Article/details/gtzdpxzlue.html


<!-- 参考信息 -->