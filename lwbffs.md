代发 wailian999

Java: public static void main(String[] args)
来源：http://dali.sysykeji.top/Article/details/gt2ulcillms.html

Go:   func main()
来源：http://dali.gotoacloud.top/Article/details/gt2vsgsliut.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj20258888.top/Article/details/gt2ajaddirs.html

C#:   static void Main(string[] args)
来源：http://dali.vqdsnc.cn/Article/details/gt2cdssoypr.html

[M08] 获取系统与运行时信息
来源：http://dali.redwolf501.top/Article/details/gt2idxvmwjb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ypyljuth.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tianlin.xyz/Article/details/gt2uixefqjj.html

JS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gt2cotqmizn.html

TS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gt2qpbpaifh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ivvv.top/Article/details/gt2aalkjwyg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xuqwyvyc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pycfn.com/Article/details/gt2ngbqfjaj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xairxkau.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nmjugjgl.html

N. 数据结构与算法
来源：http://dali.guowangkeji.top/Article/details/gt2hkruhcpu.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2uebtufiq.html

[N01] 二分查找（有序数组）
来源：http://dali.zhiwuduotai.top/Article/details/gt2bihgbqst.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.havefunace.top/Article/details/gt2phgarwyh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tianlin.xyz/Article/details/gt2bjqlqngo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rfqazdoq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gt2wdlxlnxc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2taqfypoy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yrnkwebw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xziqi.cn/Article/details/gt2ltwhvwjj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2ebsxvzof.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aizwys.cn/Article/details/gt2hjkypvlf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gt2mquecbuc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.iojbl.cn/Article/details/gt2hxilhqnz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ssuwwnaz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gt2sksfdgss.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnqzz.top/Article/details/gt2bkrocszm.html

Go:   slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2magwnqkp.html

Ruby: arr.sort
来源：http://dali.dianchejie.cn/Article/details/gt2tdblxxtd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gaohongyu789.top/Article/details/gt2nmbronpy.html

[N03] 快速排序（分治示例）
来源：http://dali.daria6918.cn/Article/details/gt2xfuvolsd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hnxiangtu.top/Article/details/gt2eiyjzyew.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tianlin.xyz/Article/details/gt2wyuzeljm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ehwqpu.com/Article/details/gt2ehmyqrza.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gt2xgsohmfs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.havefunace.top/Article/details/gt2aibpdswz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sysykeji.top/Article/details/gt2dwvmeoup.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.quarkkingdee.top/Article/details/gt2amdkvfis.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gaohongyu789.top/Article/details/gt2oatzgvig.html

[N04] 斐波那契数列
来源：http://dali.guowangkeji.top/Article/details/gt2iqandeyb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nwbrower.top/Article/details/gt2naiqijyj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tian-w.cn/Article/details/gt2putywlgc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gt2vkmzahlv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gt2gnxqdvax.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gt2yigkxrff.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gzhubu.top/Article/details/gt2iaqyyqco.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ctbztsyy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gt2kuqdfeup.html

[N05] 最大公约数
来源：http://dali.sxryk.cn/Article/details/gt2sifdshgy.html

Py:   math.gcd(a, b)
来源：http://dali.fengsongda.top/Article/details/gt2jirpmltg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.0kj1m.cn/Article/details/gt2qmgbchkx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.snrcjt.cn/Article/details/gt2yamsmdim.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gt2jspbrdww.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wwswvdbl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jchznovr.html

Ruby: a.gcd(b)
来源：http://dali.ybcxt.top/Article/details/gt2xbxuczlz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shzxlz.cn/Article/details/gt2dfztgbcw.html

[N06] 判断回文字符串
来源：http://dali.jinqigufen.top/Article/details/gt2lwxmzjcm.html

Py:   s == s[::-1]
来源：http://dali.meibo888.top/Article/details/gt2veifcanx.html

PHP:  $s === strrev($s);
来源：http://dali.cashguo.top/Article/details/gt2lxofuzmf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gt2rvktmiza.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gt2rdpsvyfg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.svipenyu.cn/Article/details/gt2uimwrlrn.html

Go:   // 双指针从两端比较
来源：http://dali.xinyue.icu/Article/details/gt2simgytxg.html

Ruby: s == s.reverse
来源：http://dali.sweek.top/Article/details/gt2mogcdrko.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gt2kozmtjjt.html

[N07] 两数之和（返回下标）
来源：http://dali.hysaishi.cn/Article/details/gt2ttgwdjch.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenzaomai.com/Article/details/gt2wbjhbstr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shangyingyoupin.top/Article/details/gt2dsthgfed.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vbgtetpg.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenjidiqi.icu/Article/details/gt2flqaeotr.html

Java: // 手写 HashMap
来源：http://dali.xuanzx.com/Article/details/gt2phqevbrk.html

Go:   // 手写 map[int]int
来源：http://dali.nanxinkj.top/Article/details/gt2ybghbmsl.html

Ruby: // 手写 Hash
来源：http://dali.chenlongwang.top/Article/details/gt2jmdwzevw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cheryme.top/Article/details/gt2krdtsgfj.html

[N08] 生成全排列
来源：http://dali.zdqjudy.top/Article/details/gt2yioaahnr.html

Py:   itertools.permutations(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2pmlfirfv.html

PHP:  // 手写递归交换
来源：http://dali.ybcxt.top/Article/details/gt2olspbsgi.html

JS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gt2ilztdcmm.html

TS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2qrjvhipv.html

Java: // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gt2uovimlxb.html

Go:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gt2eleflrwb.html

Ruby: arr.permutation.to_a
来源：http://dali.cdnleiting.top/Article/details/gt2jbhpahkw.html

C#:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gt2pqbexvre.html

[N09] 栈与队列
来源：http://dali.havefunace.top/Article/details/gt2cjvowadz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hfpthk.cn/Article/details/gt2xfvdvfyz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2cddbzssr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gt2codvcyhm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.c1oappe.top/Article/details/gt2zswiecpu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yongpay.top/Article/details/gt2ejtmhotg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gt2nsqpqysc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gt2pdquupcf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj202588.top/Article/details/gt2atnzwuxg.html

[N10] 链表节点定义
来源：http://dali.chenlongwang.top/Article/details/gt2mrsdusuv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhiwuduotai.top/Article/details/gt2mlwpefwo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj20258888.top/Article/details/gt2iohiscbc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nanxuanxn.top/Article/details/gt2sucwzdup.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.iojbl.cn/Article/details/gt2vprvdgxu.html

Java: class Node { int v; Node next; }
来源：http://dali.tianlin.xyz/Article/details/gt2eevseuvh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yanxiufei.cn/Article/details/gt2oggrluiw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgfzy.top/Article/details/gt2nyagxkmb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gotoacloud.top/Article/details/gt2whctksfm.html

[N11] 二叉树中序遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2ussqsuhz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xziqi.cn/Article/details/gt2yauvnncj.html

PHP:  // 手写递归函数
来源：http://dali.ydzc1.top/Article/details/gt2ooorlwfo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenjidiqi.icu/Article/details/gt2jedsdbwj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yvedp.cn/Article/details/gt2ddhjkqtf.html

Java: // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2ujbwkzbz.html

Go:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gt2ebopngra.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.kuanghao11.cn/Article/details/gt2smnodqin.html

C#:   // 手写递归
来源：http://dali.xylfe.cn/Article/details/gt2pwbrzjtf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cdnleiting.top/Article/details/gt2xiomjyas.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zlyrhgwe.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jyoumei.cn/Article/details/gt2upvkdalp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenlongwang.top/Article/details/gt2uxixcrwk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sysykeji.top/Article/details/gt2nxbndfwy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gt2wwnnegel.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tianlin.xyz/Article/details/gt2vqwnhxqh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.aibaodan.cn/Article/details/gt2qftfkzlp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gt2ygcaxybk.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2stcotxxg.html

O. 并发与异步
来源：http://dali.shangyingyoupin.top/Article/details/gt2jrebbxcv.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2clozhnxg.html

[O01] 启动一个线程
来源：http://dali.gzhubu.top/Article/details/gt2fvzopzot.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yonumen.top/Article/details/gt2rffvvdwj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yongpay.top/Article/details/gt2zstgjzzz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.aibaodan.cn/Article/details/gt2wmrwfyut.html

TS:   // 同 JS
来源：http://dali.havefunace.top/Article/details/gt2lfuhtbxk.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gzodthfe.html

Go:   go f()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2byfkurvb.html

Ruby: Thread.new { f }
来源：http://dali.yuanzhike.top/Article/details/gt2oqltnfuo.html

C#:   Task.Run(() => F());
来源：http://dali.mhx1999.top/Article/details/gt2ypbsrrna.html

[O02] 使用线程池
来源：http://dali.jianghu66.top/Article/details/gt2zzfmqdni.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.quarkkingdee.top/Article/details/gt2ejvxvhak.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vjbvcfzk.html

JS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gt2slbnaeef.html

TS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gt2ozqancaq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangdashe.top/Article/details/gt2obbfhsef.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.mhx1999.top/Article/details/gt2fkfpprod.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yuxming.cn/Article/details/gt2cvogvgyq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yongpay.top/Article/details/gt2jmragwtk.html

[O03] 加锁保护共享数据
来源：http://dali.0kj1m.cn/Article/details/gt2czxvqoye.html

Py:   with lock: shared += 1
来源：http://dali.guowangkeji.top/Article/details/gt2ocjpvsoq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.c1oappe.top/Article/details/gt2abtqsxkl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yueranfly.top/Article/details/gt2kpsmylmw.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gt2sjfixwda.html

Java: synchronized (this) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gt2caqazaai.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenjidiqi.icu/Article/details/gt2gzkezoab.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.c1oappe.top/Article/details/gt2guuntrqm.html

C#:   lock (gate) { shared++; }
来源：http://dali.cheryme.top/Article/details/gt2oddjgfww.html

[O04] 定义异步函数并等待
来源：http://dali.mhx1999.top/Article/details/gt2dqfusyug.html

Py:   async def f():⏎    await g()
来源：http://dali.guowangkeji.top/Article/details/gt2oljfxvtt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhiwuduotai.top/Article/details/gt2jxqfosig.html

JS:   async function f() { await g(); }
来源：http://dali.yongpay.top/Article/details/gt2aktmdshk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xdxalxpe.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj202588.top/Article/details/gt2rrpdcvqz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxuanxn.top/Article/details/gt2ftdvznss.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shuidangran.top/Article/details/gt2rssywwts.html

C#:   async Task F() { await G(); }
来源：http://dali.andypj.xyz/Article/details/gt2uklqjvjp.html

[O05] 并发执行并等待全部完成
来源：http://dali.xziqi.cn/Article/details/gt2qgnbqmgk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jianghu66.top/Article/details/gt2silujdpj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nwbrower.top/Article/details/gt2ddleyfwl.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ryrtnwgf.html

TS:   await Promise.all(tasks)
来源：http://dali.xinyue.icu/Article/details/gt2eqaymwai.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuanzhike.top/Article/details/gt2lhamxwfr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.havefunace.top/Article/details/gt2ouvgffuy.html

Ruby: threads.map(&:join)
来源：http://dali.ybcxt.top/Article/details/gt2fyorqewt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgufenzy.top/Article/details/gt2cgbudhdk.html

[O06] 使用进程池
来源：http://dali.ydzc1.top/Article/details/gt2vnvagtyd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.andypj.xyz/Article/details/gt2yrwtfsmj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tian-w.cn/Article/details/gt2uwgieuil.html

JS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mrcdcuma.html

TS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gt2kcjeavwq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gt2hraggvsh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ivvv.top/Article/details/gt2jibbhydq.html

Ruby: // fork 块
来源：http://dali.cdnleiting.top/Article/details/gt2enlrxpxj.html

C#:   Parallel.For
来源：http://dali.yuanzhike.top/Article/details/gt2kkfsbrpr.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2rfpnvgzd.html

P. 常用工具函数
来源：http://dali.daria6918.cn/Article/details/gt2tykzmgiy.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2tlbrplmc.html

[P01] 生成 UUID
来源：http://dali.sysykeji.top/Article/details/gt2hfocflzt.html

Py:   str(uuid.uuid4())
来源：http://dali.cdnleiting.top/Article/details/gt2qjdytxpp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.pengpengdd.cyou/Article/details/gt2eouzgkzq.html

JS:   crypto.randomUUID()
来源：http://dali.yj20258888.top/Article/details/gt2ptvffkst.html

TS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gt2hclttgap.html

Java: UUID.randomUUID().toString()
来源：http://dali.snrcjt.cn/Article/details/gt2aryjsmeg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenlongwang.top/Article/details/gt2sbapcpde.html

Ruby: SecureRandom.uuid
来源：http://dali.tanke756.top/Article/details/gt2eogdfpxs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yangfankeji.com/Article/details/gt2jdbpzhte.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tanke756.top/Article/details/gt2aovdiszr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yvedp.cn/Article/details/gt2qdnxpxnh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fzhhl.top/Article/details/gt2kvbniwzf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.snrcjt.cn/Article/details/gt2wlhlrtvc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.0kj1m.cn/Article/details/gt2zkbpunrs.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.aibaodan.cn/Article/details/gt2llvvckhi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aibaodan.cn/Article/details/gt2fvmolmkx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigufen.top/Article/details/gt2hyyqisjx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigufen.top/Article/details/gt2hjslqxip.html

[P03] 生成短随机字符串
来源：http://dali.wangdashe.top/Article/details/gt2jmirngpk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.dashuyun.cn/Article/details/gt2wsuiqsbt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.guannengcc.top/Article/details/gt2depevynn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gt2zmrtwern.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gt2vtygehaa.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.snrcjt.cn/Article/details/gt2dyddgukd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dianchejie.cn/Article/details/gt2azqupebb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuanzx.com/Article/details/gt2apadtihe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yueranfly.top/Article/details/gt2syjcdnlf.html

[P04] 求长度
来源：http://dali.gzhubu.top/Article/details/gt2wmdpzgho.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ivvv.top/Article/details/gt2sxbdhfix.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gt2blisuuyg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcjnyxm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gt2qqwckynp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.fzhhl.top/Article/details/gt2gtyrypyf.html

Go:   len(arr);  len(m)
来源：http://dali.yuxming.cn/Article/details/gt2pfadmjew.html

Ruby: x.length;  x.size
来源：http://dali.jlsjyb.cn/Article/details/gt2gbztawsm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xinyue.icu/Article/details/gt2iockamdh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tianlin.xyz/Article/details/gt2knohxwab.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenzaomai.com/Article/details/gt2tsbjkbpl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinghuilouyu.cn/Article/details/gt2brxqnsos.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xinyue.icu/Article/details/gt2gtclmpti.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.haohaochexian.top/Article/details/gt2pryojonj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gotoacloud.top/Article/details/gt2agasdtwf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gotoacloud.top/Article/details/gt2avyzxuoi.html

Ruby: a == b
来源：http://dali.gaohongyu789.top/Article/details/gt2fcuqkdtl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj202588.top/Article/details/gt2oxvxkhmf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinqigfzy.top/Article/details/gt2bqwqomup.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gt2braiyxye.html

PHP:  if (empty($x)) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2qmsrhdhv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yrvxcmss.html

TS:   if (x == null) {}
来源：http://dali.sysykeji.top/Article/details/gt2pbrblvlf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.dianchejie.cn/Article/details/gt2pqgxarhc.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhjcmjd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcrbmbb.html

C#:   if (x is null) {}
来源：http://dali.cucudq.cn/Article/details/gt2pbttjwcr.html

[P07] 防抖与节流
来源：http://dali.cucudq.cn/Article/details/gt2rnqilfbx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sufxvd.cn/Article/details/gt2nzveidlc.html

PHP:  // 手写时间戳比较
来源：http://dali.aizwys.cn/Article/details/gt2zeirymhp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gt2qtuvfttx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gt2fdhpbasd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.guannengcc.top/Article/details/gt2pyysiisv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xinyue.icu/Article/details/gt2jwpvcjpm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yanxiufei.cn/Article/details/gt2vzmwngvk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.0kj1m.cn/Article/details/gt2cppowzqv.html

[P08] 处理浮点精度问题
来源：http://dali.hnqzz.top/Article/details/gt2vkdxntbf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fengsongda.top/Article/details/gt2pjwrbhls.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2iyyxqagi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenlongwang.top/Article/details/gt2mnuwbptg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rsqvrtib.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tian-w.cn/Article/details/gt2vdzljtti.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.fengsongda.top/Article/details/gt2eejfceyf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.redwolf501.top/Article/details/gt2iywqhutj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ydzc1.top/Article/details/gt2jpxumdsx.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2vdnuoihr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigufen.top/Article/details/gt2fdkpxhgl.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2fmrzligm.html

[Q01] 创建表
来源：http://dali.snrcjt.cn/Article/details/gt2arybldns.html

CREATE TABLE users (
来源：http://dali.snrcjt.cn/Article/details/gt2tmsxnvji.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gt2zhlhaujt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhongyouzk.top/Article/details/gt2zlfflwhp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aizwys.cn/Article/details/gt2wadcpypg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ocbeszwe.html

);
来源：http://dali.daxiang520.top/Article/details/gt2dlniwqzz.html

[Q02] 创建带外键的表
来源：http://dali.xuanzx.com/Article/details/gt2rodxghsz.html

CREATE TABLE orders (
来源：http://dali.cdnleiting.top/Article/details/gt2atwpxamo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gt2wmjgqsox.html

user_id INT NOT NULL,
来源：http://dali.havefunace.top/Article/details/gt2akxseklz.html

amount DECIMAL(10, 2),
来源：http://dali.cqqwz.cn/Article/details/gt2mriahebs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jiagoushi.top/Article/details/gt2nfnkvbjt.html

);
来源：http://dali.guowangkeji.top/Article/details/gt2dffctncs.html

[Q03] 增加列
来源：http://dali.yuanzhike.top/Article/details/gt2witqxxtu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gaohongyu789.top/Article/details/gt2ixcfjwfq.html

[Q04] 修改列类型
来源：http://dali.yuxming.cn/Article/details/gt2iknskzix.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgufenzy.top/Article/details/gt2xoukfugn.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2mxicggnz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aibaodan.cn/Article/details/gt2guugmlev.html

[Q06] 删除列
来源：http://dali.cashguo.top/Article/details/gt2lzyjiooe.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenzaomai.com/Article/details/gt2fddysgee.html

[Q07] 删除表
来源：http://dali.dianchejie.cn/Article/details/gt2obyrtfju.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cqqwz.cn/Article/details/gt2dvoglnqq.html

[Q08] 创建普通索引
来源：http://dali.xylfe.cn/Article/details/gt2pcqxzavn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gt2myvmupcb.html

[Q09] 创建唯一索引
来源：http://dali.hywenlv.cn/Article/details/gt2vpyeuubu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lgvlugwo.html

[Q10] 插入单行
来源：http://dali.gogol.net.cn/Article/details/gt2hlnhavjo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.smart0.xyz/Article/details/gt2fjiyljzp.html

[Q11] 一次插入多行
来源：http://dali.sweek.top/Article/details/gt2nxohviwj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.pycfn.com/Article/details/gt2hluphvjg.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ewbaldoj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangshuangyany.cn/Article/details/gt2wfwmxkon.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sxryk.cn/Article/details/gt2vanzltwl.html

[Q13] 忽略重复插入
来源：http://dali.quarkkingdee.top/Article/details/gt2vogktnuz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xinyue.icu/Article/details/gt2ktvtyyik.html

[Q14] 存在则更新（upsert）
来源：http://dali.vqdsnc.cn/Article/details/gt2mhkjevwv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yvedp.cn/Article/details/gt2txydhzip.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wvjnlvzo.html

[Q15] 查询全部
来源：http://dali.hfpthk.cn/Article/details/gt2lhaxnowf.html


<!-- 参考信息 -->