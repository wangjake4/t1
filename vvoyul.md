代发 wailian999

Java: public static void main(String[] args)
来源：http://dali.cashguo.top/Article/details/gthukiirur.html

Go:   func main()
来源：http://dali.yuxming.cn/Article/details/gtmlwakoph.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yanxiufei.cn/Article/details/gtpcyqkpla.html

C#:   static void Main(string[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvllondn.html

[M08] 获取系统与运行时信息
来源：http://dali.gzhubu.top/Article/details/gtajwzfzcb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenzaomai.com/Article/details/gtmwtfzfqn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xziqi.cn/Article/details/gtradicrtc.html

JS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtussawtde.html

TS:   process.platform;  process.version
来源：http://dali.xuanzx.com/Article/details/gtoycicefi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlblcyfny.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttvjcxfwp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.meibo888.top/Article/details/gtryuioxop.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohhlykyp.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtdvwmelra.html

N. 数据结构与算法
来源：http://dali.jiagoushi.top/Article/details/gtbgbyigfy.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtshurdwag.html

[N01] 二分查找（有序数组）
来源：http://dali.chenzaomai.com/Article/details/gtjthoustl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtgswlwwne.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.redwolf501.top/Article/details/gtewnaltlb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxdkygim.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtoejaaugq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gttywipjdi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtcuhhthiz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.meibo888.top/Article/details/gtfjvuuzwz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtxhetjqhy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yvedp.cn/Article/details/gtfxlxxpoi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gtaefcepbn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tian-w.cn/Article/details/gtkdgepjvu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gttnivctfl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gtxwxhiuws.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hammf.cn/Article/details/gthmgxqosv.html

Go:   slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtaqmruqqb.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gtdonghxiv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhusgxcu.html

[N03] 快速排序（分治示例）
来源：http://dali.tanke756.top/Article/details/gtquiyslyq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuanzhike.top/Article/details/gtdieiectl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jyoumei.cn/Article/details/gtuhbfzksb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gtqqpmhuvh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhixingplan.top/Article/details/gtqekqhiyr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenzaomai.com/Article/details/gtbldlsgkn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zycfv.cn/Article/details/gtcoegdgeq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hongshengwenyu.top/Article/details/gtlxxhcutc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.iojbl.cn/Article/details/gtxwgdzvbm.html

[N04] 斐波那契数列
来源：http://dali.xuetiantiany.cn/Article/details/gtkgyxohur.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gtgvzimizv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.c1oappe.top/Article/details/gtmjtxbhvp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gtevmyzgbg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtcwvbmkyz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.smart0.xyz/Article/details/gtqzgtkzdh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.svipenyu.cn/Article/details/gtggaqhzxd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gtgabfgzaz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gtmukklrad.html

[N05] 最大公约数
来源：http://dali.c1oappe.top/Article/details/gtukdlretz.html

Py:   math.gcd(a, b)
来源：http://dali.yonumen.top/Article/details/gtsqybjozx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sysykeji.top/Article/details/gtdbnwvuhz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.bjfxy.top/Article/details/gtokiqrbie.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gtfmuiaxax.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ydzc1.top/Article/details/gtsssvkgxn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dianchejie.cn/Article/details/gtxbxbedfb.html

Ruby: a.gcd(b)
来源：http://dali.daria6918.cn/Article/details/gtufxjqkpw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.316326.xyz/Article/details/gtuvwlzhrs.html

[N06] 判断回文字符串
来源：http://dali.haohaochexian.top/Article/details/gtouepfodg.html

Py:   s == s[::-1]
来源：http://dali.316326.xyz/Article/details/gtrmugadtc.html

PHP:  $s === strrev($s);
来源：http://dali.hnqzz.top/Article/details/gtinjjjbrp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtbdrjiliu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtslbbuuvr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.kuanghao11.cn/Article/details/gtouhqtoxn.html

Go:   // 双指针从两端比较
来源：http://dali.yj202588.top/Article/details/gtsuyzzvee.html

Ruby: s == s.reverse
来源：http://dali.jianghu66.top/Article/details/gtmaciauhe.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gtztgmkrnc.html

[N07] 两数之和（返回下标）
来源：http://dali.meibo888.top/Article/details/gttmeuwwwe.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aizwys.cn/Article/details/gtibutkedo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuetiantiany.cn/Article/details/gtjciqoqpq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenzaomai.com/Article/details/gtiyegbmeg.html

TS:   // 手写 Map<string, number>
来源：http://dali.sufxvd.cn/Article/details/gtppjpmckp.html

Java: // 手写 HashMap
来源：http://dali.shzxlz.cn/Article/details/gtovylljeq.html

Go:   // 手写 map[int]int
来源：http://dali.smart0.xyz/Article/details/gtoegfapqt.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gtbzwakyub.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shuidangran.top/Article/details/gtienbfjec.html

[N08] 生成全排列
来源：http://dali.zhoulong.xyz/Article/details/gtevaaqrxi.html

Py:   itertools.permutations(arr)
来源：http://dali.pycfn.com/Article/details/gtxuffbagk.html

PHP:  // 手写递归交换
来源：http://dali.ybcxt.top/Article/details/gtkclngsqz.html

JS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtaaolffui.html

TS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtjwvxecqc.html

Java: // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtetlvejbi.html

Go:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtsqjdxxoq.html

Ruby: arr.permutation.to_a
来源：http://dali.chenlongwang.top/Article/details/gtquhgngzq.html

C#:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtnljtupyf.html

[N09] 栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gtauaxlxcf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.9152youxi.cn/Article/details/gtfalxiurc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtelxuhwgc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gtxiunntar.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.9152youxi.cn/Article/details/gtqoaxkwpe.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hammf.cn/Article/details/gtuiqqjrle.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xylfe.cn/Article/details/gtcomojzav.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gtbkdbnsmm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.birdmap.top/Article/details/gthkbqkioa.html

[N10] 链表节点定义
来源：http://dali.jqgfzy.top/Article/details/gthoqhmimp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hnqzz.top/Article/details/gtlvcwrywg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gaohongyu789.top/Article/details/gtowtttmxs.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgfzy.top/Article/details/gtqlflrebt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hongshengwenyu.top/Article/details/gtjqxvrqmh.html

Java: class Node { int v; Node next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthswkqngn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.haohaochexian.top/Article/details/gtpdxqdzey.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhongyouzk.top/Article/details/gtpuwjkhlj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xziqi.cn/Article/details/gtgqvifyef.html

[N11] 二叉树中序遍历
来源：http://dali.hnxiangtu.top/Article/details/gtflappckj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhiwuduotai.top/Article/details/gtklkzmpzt.html

PHP:  // 手写递归函数
来源：http://dali.cdnleiting.top/Article/details/gtyvdvbbbr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gtgyadykrg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yvedp.cn/Article/details/gtwimyqgii.html

Java: // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtlafnoryu.html

Go:   // 手写递归
来源：http://dali.nwbrower.top/Article/details/gtdcexptvb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xylfe.cn/Article/details/gttszweiwf.html

C#:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gtlsbpmnlx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gogol.net.cn/Article/details/gtkptysnwa.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jianghu66.top/Article/details/gtpmtifxhn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gtcfzzcdof.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xinyue.icu/Article/details/gtxnwndmga.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ppjwa.cn/Article/details/gtkiijxlts.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.316326.xyz/Article/details/gtgipxrkst.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daxiang520.top/Article/details/gtiupgjvyc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gotoacloud.top/Article/details/gtwqxupejw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gtvjiitlgn.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyoupmjss.html

O. 并发与异步
来源：http://dali.yangfankeji.com/Article/details/gtwnibfhxx.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtcxupgooz.html

[O01] 启动一个线程
来源：http://dali.meibo888.top/Article/details/gtrlrmkivj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fzhhl.top/Article/details/gtpqaiobzq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.316326.xyz/Article/details/gtepgvftbs.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gtrecgugri.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gtnaruifkl.html

Java: new Thread(() -> f()).start()
来源：http://dali.pycfn.com/Article/details/gtvpevoako.html

Go:   go f()
来源：http://dali.daria6918.cn/Article/details/gtrtvexxfp.html

Ruby: Thread.new { f }
来源：http://dali.redwolf501.top/Article/details/gtzypvthkn.html

C#:   Task.Run(() => F());
来源：http://dali.guowangkeji.top/Article/details/gtuvyzruec.html

[O02] 使用线程池
来源：http://dali.ehwqpu.com/Article/details/gtixhwueho.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guannengcc.top/Article/details/gtsssjgcdc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.316326.xyz/Article/details/gtdrcqdpts.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhpxaxgk.html

TS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gtarlxttyw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangshuangyany.cn/Article/details/gtqfhspxgl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shanyushiyangtech.top/Article/details/gtugostqbs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.kuanghao11.cn/Article/details/gtahccznwf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgufenzy.top/Article/details/gtxqklekkl.html

[O03] 加锁保护共享数据
来源：http://dali.tianlin.xyz/Article/details/gtonunkbnu.html

Py:   with lock: shared += 1
来源：http://dali.yueranfly.top/Article/details/gtzovbjbls.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.316326.xyz/Article/details/gtaolpldqz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xuanzx.com/Article/details/gtbocpxtwp.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gtxldyrtfs.html

Java: synchronized (this) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gtfxufvxwl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shuidangran.top/Article/details/gthebktrrx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jianghu66.top/Article/details/gtyvlfcplb.html

C#:   lock (gate) { shared++; }
来源：http://dali.pengpengdd.cyou/Article/details/gtoctinbuh.html

[O04] 定义异步函数并等待
来源：http://dali.jianghu66.top/Article/details/gtganebqxr.html

Py:   async def f():⏎    await g()
来源：http://dali.gzhubu.top/Article/details/gtpfysrvbu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shzxlz.cn/Article/details/gtsdikvaiw.html

JS:   async function f() { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gtaqlwknvv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.andypj.xyz/Article/details/gturvofdpj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.316326.xyz/Article/details/gtiefvsuyc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.pengpengdd.cyou/Article/details/gtthiuhybj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gaohongyu789.top/Article/details/gtstabajrr.html

C#:   async Task F() { await G(); }
来源：http://dali.xuanzx.com/Article/details/gtdpaeripz.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjigmcqu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.redwolf501.top/Article/details/gtkybjdwjd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ybcxt.top/Article/details/gttqkzvgyd.html

JS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gtpxznthww.html

TS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtmdzudobq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.quarkkingdee.top/Article/details/gtwhvirght.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.mhx1999.top/Article/details/gtjyomqcgw.html

Ruby: threads.map(&:join)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtlpaqki.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgfzy.top/Article/details/gtjugwikpt.html

[O06] 使用进程池
来源：http://dali.nanxinkj.top/Article/details/gtegwszgeg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuxming.cn/Article/details/gtlyfsrjre.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ybcxt.top/Article/details/gtuzxjevnk.html

JS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gtxgygwyrf.html

TS:   // child_process / cluster 模块
来源：http://dali.cdnleiting.top/Article/details/gtmjsgerbv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.meibo888.top/Article/details/gtdktfiupk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.wangdashe.top/Article/details/gtwuifmtkf.html

Ruby: // fork 块
来源：http://dali.wangshuangyany.cn/Article/details/gtlfaoezor.html

C#:   Parallel.For
来源：http://dali.jinghuilouyu.cn/Article/details/gtllbbpgql.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gttnybmuok.html

P. 常用工具函数
来源：http://dali.zhengqikj.top/Article/details/gtyrhjjpea.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtnqhzyzra.html

[P01] 生成 UUID
来源：http://dali.yanxiufei.cn/Article/details/gtivbqurer.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgufenzy.top/Article/details/gteigskbjn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.0kj1m.cn/Article/details/gtaxeakunr.html

JS:   crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gtezlazlku.html

TS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gtwhnmdndp.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigufen.top/Article/details/gthbskjhsq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.aibaodan.cn/Article/details/gtjolnguoo.html

Ruby: SecureRandom.uuid
来源：http://dali.chenzaomai.com/Article/details/gtmepnehhk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.birdmap.top/Article/details/gtcyactwxl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jlsjyb.cn/Article/details/gtxshixeku.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.guannengcc.top/Article/details/gtotazklvu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jqgufenzy.top/Article/details/gtbaavppzq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ydzc1.top/Article/details/gtkdvgbgiw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigufen.top/Article/details/gtgtpaaksv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtnpajnqus.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zdqjudy.top/Article/details/gtpvklgypp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sweek.top/Article/details/gtjfrjgiio.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvpmtlmn.html

[P03] 生成短随机字符串
来源：http://dali.fzhhl.top/Article/details/gtmfpfqckx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.316326.xyz/Article/details/gtmbqopyoj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgfzy.top/Article/details/gtaflaqazu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gtuukkaqpq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gtdnjembey.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.bjfxy.top/Article/details/gtluhyktrz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.c1oappe.top/Article/details/gtzsrpbrcc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxinkj.top/Article/details/gtwvviygsj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhiwuduotai.top/Article/details/gtqdejiswu.html

[P04] 求长度
来源：http://dali.cheryme.top/Article/details/gtcrmlemlc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhongyouzk.top/Article/details/gtbavmwxiz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtrornolpo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gtjvgtkkop.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hongshengwenyu.top/Article/details/gtczwvsfxw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gogol.net.cn/Article/details/gtpyguloob.html

Go:   len(arr);  len(m)
来源：http://dali.redwolf501.top/Article/details/gtutnjgiwe.html

Ruby: x.length;  x.size
来源：http://dali.yanxiufei.cn/Article/details/gtvybhmvgm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fengsongda.top/Article/details/gtlelubvde.html

[P05] 判断两个对象内容是否相等
来源：http://dali.kuanghao11.cn/Article/details/gtofywrdzk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gogol.net.cn/Article/details/gtbvkkrkqt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhixingplan.top/Article/details/gtxdmpeoff.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.quarkkingdee.top/Article/details/gtheavdmgj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.9152youxi.cn/Article/details/gtyffbrfdt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenjidiqi.icu/Article/details/gtyorcwgzv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xuanzx.com/Article/details/gtxworpzsm.html

Ruby: a == b
来源：http://dali.wangdashe.top/Article/details/gttlexkzrw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gzhubu.top/Article/details/gtrmehsiaf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hammf.cn/Article/details/gtvokzfhsh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xuanzx.com/Article/details/gtkhqdqdzc.html

PHP:  if (empty($x)) {}
来源：http://dali.bjfxy.top/Article/details/gtsqcfpcox.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvaeqscz.html

TS:   if (x == null) {}
来源：http://dali.hnqzz.top/Article/details/gtphalqdrm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtnhkacvqy.html

Go:   if x == nil {}
来源：http://dali.zhengqikj.top/Article/details/gtnhnwmgti.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.guannengcc.top/Article/details/gtqycxhbqa.html

C#:   if (x is null) {}
来源：http://dali.zhoulong.xyz/Article/details/gtwtlrhrku.html

[P07] 防抖与节流
来源：http://dali.kuanghao11.cn/Article/details/gtctufxxhu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hfpthk.cn/Article/details/gtdlendrro.html

PHP:  // 手写时间戳比较
来源：http://dali.sxryk.cn/Article/details/gttarmfvtq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gtkhdjxkrq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gtjilvacpr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.birdmap.top/Article/details/gtfrgjmges.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakoznbnq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fzhhl.top/Article/details/gttepmqgoi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fzhhl.top/Article/details/gtnmilsixn.html

[P08] 处理浮点精度问题
来源：http://dali.sweek.top/Article/details/gtmjlcbgjx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tianlin.xyz/Article/details/gtxiexqxyd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xziqi.cn/Article/details/gtukirypvf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.birdmap.top/Article/details/gtdizddlhr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gotoacloud.top/Article/details/gtdclqjpvg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhoulong.xyz/Article/details/gtusjaebzp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.iojbl.cn/Article/details/gtpsdiewag.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtltvgaxvx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.kuanghao11.cn/Article/details/gtmqwkkuax.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gthhvjjmvw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gzhubu.top/Article/details/gtwdhzqfdn.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtsycajqhw.html

[Q01] 创建表
来源：http://dali.xinyue.icu/Article/details/gtfgvuxdde.html

CREATE TABLE users (
来源：http://dali.cucudq.cn/Article/details/gtvggfadoj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gtrpsuppwz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258888.top/Article/details/gtyoilnpnf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xuanzx.com/Article/details/gttlavedyh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuetiantiany.cn/Article/details/gtsijcwlgv.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gttwtvnxyg.html

[Q02] 创建带外键的表
来源：http://dali.hammf.cn/Article/details/gtmhqhcpzm.html

CREATE TABLE orders (
来源：http://dali.yuanzhike.top/Article/details/gtpgunlslt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gtieouwzdu.html

user_id INT NOT NULL,
来源：http://dali.yangfankeji.com/Article/details/gtmwwkhodi.html

amount DECIMAL(10, 2),
来源：http://dali.chenzaomai.com/Article/details/gtmpoiypim.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhiwuduotai.top/Article/details/gtkkyhzciv.html

);
来源：http://dali.feifeiyinyue.top/Article/details/gtrzlexzvx.html

[Q03] 增加列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpppznong.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.vqdsnc.cn/Article/details/gtiupgjmpf.html

[Q04] 修改列类型
来源：http://dali.jinqigufen.top/Article/details/gtgfumywxu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xuanzx.com/Article/details/gturuyovyp.html

[Q05] 重命名列
来源：http://dali.sweek.top/Article/details/gtnidcxlph.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnxiangtu.top/Article/details/gthsyvodyw.html

[Q06] 删除列
来源：http://dali.xziqi.cn/Article/details/gtknkgmgwp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ppjwa.cn/Article/details/gtrcteyulv.html

[Q07] 删除表
来源：http://dali.gaohongyu789.top/Article/details/gtwbnbsguj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.mhx1999.top/Article/details/gtaaicsqge.html

[Q08] 创建普通索引
来源：http://dali.iojbl.cn/Article/details/gtochkbyui.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenlongwang.top/Article/details/gtkfsyxukh.html

[Q09] 创建唯一索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynwmjcte.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zdqjudy.top/Article/details/gtswhnnuza.html

[Q10] 插入单行
来源：http://dali.cqqwz.cn/Article/details/gtowfjvaub.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gzhubu.top/Article/details/gtbcapqqwz.html

[Q11] 一次插入多行
来源：http://dali.wangshuangyany.cn/Article/details/gtzqydcmps.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gtfvrmecva.html

[Q12] 插入后取自增 ID
来源：http://dali.hysaishi.cn/Article/details/gtuwenfzlq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cashguo.top/Article/details/gtmijqogzq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenlongwang.top/Article/details/gtrruzbhms.html

[Q13] 忽略重复插入
来源：http://dali.snrcjt.cn/Article/details/gtgtwryssn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.bjfxy.top/Article/details/gtruuyvavr.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenjidiqi.icu/Article/details/gtvuzxzvbf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hysaishi.cn/Article/details/gtwuvcvsqi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sxryk.cn/Article/details/gtfmmrtsav.html

[Q15] 查询全部
来源：http://dali.xinyue.icu/Article/details/gtqremswsx.html


<!-- 参考信息 -->