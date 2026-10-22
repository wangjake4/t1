代发 wailian999

Java: public static void main(String[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2khbmvwdv.html

Go:   func main()
来源：http://dali.yj20258.top/Article/details/gt2smwspsdy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ybcxt.top/Article/details/gt2tnybwmnw.html

C#:   static void Main(string[] args)
来源：http://dali.316326.xyz/Article/details/gt2ifkcvupb.html

[M08] 获取系统与运行时信息
来源：http://dali.hysaishi.cn/Article/details/gt2iejruvvh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dashuyun.cn/Article/details/gt2gnhuppbr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jlsjyb.cn/Article/details/gt2dypimdat.html

JS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gt2vjhoteim.html

TS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gt2cpyccdcv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxinkj.top/Article/details/gt2eyohsdul.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nydfultn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jianghu66.top/Article/details/gt2tayqryji.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.snrcjt.cn/Article/details/gt2wvmouimy.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2zwlwyujz.html

N. 数据结构与算法
来源：http://dali.ehwqpu.com/Article/details/gt2cvfuwcvl.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2aykqlrxv.html

[N01] 二分查找（有序数组）
来源：http://dali.wangdashe.top/Article/details/gt2vdqkatkx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2sbuiakbf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cxgwiokh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gt2xkwqvnxb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gt2nnxwyfuh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2eqzkihyo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ssafqcfn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jqgufenzy.top/Article/details/gt2rcoeuogf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2jcgwhquc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.316326.xyz/Article/details/gt2cutjrygf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yanxiufei.cn/Article/details/gt2jtcnvpsp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pycfn.com/Article/details/gt2hhdwjfid.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.redwolf501.top/Article/details/gt2tjlxfunk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gt2utlqrles.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hammf.cn/Article/details/gt2imeajkrd.html

Go:   slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2mlkknirr.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gt2oqaouyyb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jianghu66.top/Article/details/gt2gfvsvywv.html

[N03] 快速排序（分治示例）
来源：http://dali.yonumen.top/Article/details/gt2qqkewwfa.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenlongwang.top/Article/details/gt2xxbbouei.html

PHP:  // 递归实现，或用 usort
来源：http://dali.smart0.xyz/Article/details/gt2zxabphdy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gt2vefaoplq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gt2aqofswze.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.andypj.xyz/Article/details/gt2xesmgxdg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ivvv.top/Article/details/gt2nfxoatwf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258888.top/Article/details/gt2ctjxxvwx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yuanzhike.top/Article/details/gt2jwguccay.html

[N04] 斐波那契数列
来源：http://dali.meibo888.top/Article/details/gt2uexaiqgl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2xxycaykr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yueranfly.top/Article/details/gt2uctbyigq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gt2afkibkus.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uhcqhcnr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gt2vhslnxrd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ydzc1.top/Article/details/gt2cbzgihlq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gt2lvhvonmi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gt2jluoteqt.html

[N05] 最大公约数
来源：http://dali.hnqzz.top/Article/details/gt2jucvjogq.html

Py:   math.gcd(a, b)
来源：http://dali.dianchejie.cn/Article/details/gt2fgakbhcl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sufxvd.cn/Article/details/gt2exfvzgzd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2iuqlnfvi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gt2wvdvzsjn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.smart0.xyz/Article/details/gt2cojcsiph.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fzhhl.top/Article/details/gt2wmmysadc.html

Ruby: a.gcd(b)
来源：http://dali.cheryme.top/Article/details/gt2vfkctnju.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xylfe.cn/Article/details/gt2huuwyhvq.html

[N06] 判断回文字符串
来源：http://dali.nwbrower.top/Article/details/gt2fzjwqozx.html

Py:   s == s[::-1]
来源：http://dali.cashguo.top/Article/details/gt2rahiveks.html

PHP:  $s === strrev($s);
来源：http://dali.fengsongda.top/Article/details/gt2baylkmcd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gt2lnbslnna.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gt2nhnkhhnw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.birdmap.top/Article/details/gt2cpclzarf.html

Go:   // 双指针从两端比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2fnynkuer.html

Ruby: s == s.reverse
来源：http://dali.yongpay.top/Article/details/gt2nwvficcn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gt2zxyvgmtd.html

[N07] 两数之和（返回下标）
来源：http://dali.gogol.net.cn/Article/details/gt2uhetnylu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhixingplan.top/Article/details/gt2glomqcts.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cucudq.cn/Article/details/gt2lahpzrmf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cdnleiting.top/Article/details/gt2vutvvdvi.html

TS:   // 手写 Map<string, number>
来源：http://dali.pycfn.com/Article/details/gt2tdxdlkzg.html

Java: // 手写 HashMap
来源：http://dali.jqgfzy.top/Article/details/gt2atpeoint.html

Go:   // 手写 map[int]int
来源：http://dali.sufxvd.cn/Article/details/gt2ctrhxdbu.html

Ruby: // 手写 Hash
来源：http://dali.redwolf501.top/Article/details/gt2fnckvuud.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ppjwa.cn/Article/details/gt2yphjtemc.html

[N08] 生成全排列
来源：http://dali.zdqjudy.top/Article/details/gt2xbjnfraw.html

Py:   itertools.permutations(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2neprcvwx.html

PHP:  // 手写递归交换
来源：http://dali.mhx1999.top/Article/details/gt2vmzwhosv.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iwszmlzk.html

TS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nvvjgvbx.html

Java: // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2razpxirk.html

Go:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qcygffek.html

Ruby: arr.permutation.to_a
来源：http://dali.nwbrower.top/Article/details/gt2ahbjnyax.html

C#:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gt2ypsqofqe.html

[N09] 栈与队列
来源：http://dali.hammf.cn/Article/details/gt2xvavmqoc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnxiangtu.top/Article/details/gt2icbrnxgn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gt2fdxgtcpa.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2gzmapwmw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yangfankeji.com/Article/details/gt2tnnjeabu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tanke756.top/Article/details/gt2cewigyjq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.dianchejie.cn/Article/details/gt2cpogubqk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2jxfulwli.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.redwolf501.top/Article/details/gt2rjlvindh.html

[N10] 链表节点定义
来源：http://dali.gaohongyu789.top/Article/details/gt2fdcqaumh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ppjwa.cn/Article/details/gt2adtmkxaw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zdqjudy.top/Article/details/gt2wfaafras.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ehwqpu.com/Article/details/gt2knldlbev.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.pengpengdd.cyou/Article/details/gt2botivlhm.html

Java: class Node { int v; Node next; }
来源：http://dali.nwbrower.top/Article/details/gt2ijewfxxn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258.top/Article/details/gt2gvabnukr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zdqjudy.top/Article/details/gt2uwoiaivf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zdqjudy.top/Article/details/gt2wjtgrsrr.html

[N11] 二叉树中序遍历
来源：http://dali.mhx1999.top/Article/details/gt2awyhzowq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gotoacloud.top/Article/details/gt2wwnjbkcu.html

PHP:  // 手写递归函数
来源：http://dali.ydzc1.top/Article/details/gt2fyaustwc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.c1oappe.top/Article/details/gt2xzlhfndp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gt2smqswnfk.html

Java: // 手写递归
来源：http://dali.yueranfly.top/Article/details/gt2lbvewtnm.html

Go:   // 手写递归
来源：http://dali.aizwys.cn/Article/details/gt2eaaqojtn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zdqjudy.top/Article/details/gt2fodebvey.html

C#:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gt2haudiuqe.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenlongwang.top/Article/details/gt2qswkbilv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jlsjyb.cn/Article/details/gt2spblhclo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yonumen.top/Article/details/gt2lecowedq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gt2borljlgn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gt2vziukpry.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gt2lybousqj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgufenzy.top/Article/details/gt2keyqiwqz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yongpay.top/Article/details/gt2syfzyofq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gt2tjweptgu.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2mxgifkdn.html

O. 并发与异步
来源：http://dali.xziqi.cn/Article/details/gt2vxzgluwl.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2rljevpzk.html

[O01] 启动一个线程
来源：http://dali.fzhhl.top/Article/details/gt2rwnggixy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmwrpqq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dianchejie.cn/Article/details/gt2hfztrrmr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tianlin.xyz/Article/details/gt2bxuxhfim.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gt2bhubaxos.html

Java: new Thread(() -> f()).start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eieoikfl.html

Go:   go f()
来源：http://dali.xziqi.cn/Article/details/gt2yhtteiqb.html

Ruby: Thread.new { f }
来源：http://dali.yongpay.top/Article/details/gt2wvqsucjc.html

C#:   Task.Run(() => F());
来源：http://dali.cheryme.top/Article/details/gt2fprkuebq.html

[O02] 使用线程池
来源：http://dali.wangdashe.top/Article/details/gt2wuoayjqo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigfzy.top/Article/details/gt2wxejrjwp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yuxming.cn/Article/details/gt2damjobuf.html

JS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gt2uqilogjl.html

TS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gt2pkeulvkp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nigsqpjn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sxryk.cn/Article/details/gt2tjdzuadp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqmmibw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.daxiang520.top/Article/details/gt2nmevrtgi.html

[O03] 加锁保护共享数据
来源：http://dali.bjfxy.top/Article/details/gt2josbqevf.html

Py:   with lock: shared += 1
来源：http://dali.ehwqpu.com/Article/details/gt2zsgfjwad.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yangfankeji.com/Article/details/gt2sqpccbkr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hammf.cn/Article/details/gt2cpfwflfl.html

TS:   // 同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gt2qqovdelr.html

Java: synchronized (this) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gt2qkozvmzg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgufenzy.top/Article/details/gt2rbdxhxrb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yueranfly.top/Article/details/gt2nfqfgcch.html

C#:   lock (gate) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gt2jzdsvano.html

[O04] 定义异步函数并等待
来源：http://dali.svipenyu.cn/Article/details/gt2pzkgbgbr.html

Py:   async def f():⏎    await g()
来源：http://dali.jiagoushi.top/Article/details/gt2aeujyxem.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ydzc1.top/Article/details/gt2ulribtvy.html

JS:   async function f() { await g(); }
来源：http://dali.yonumen.top/Article/details/gt2kpattzfa.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2xkcexasz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xylfe.cn/Article/details/gt2qogbrjxd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.bjfxy.top/Article/details/gt2jhkqwwtk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xylfe.cn/Article/details/gt2kcmznmhj.html

C#:   async Task F() { await G(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2cgfdnvta.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuetiantiany.cn/Article/details/gt2ygsfjymj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zrghjcvs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.haohaochexian.top/Article/details/gt2brimkdiu.html

JS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gt2tjzyjlcr.html

TS:   await Promise.all(tasks)
来源：http://dali.gogol.net.cn/Article/details/gt2zkhrfcpc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.aibaodan.cn/Article/details/gt2dkvrelxi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nanxuanxn.top/Article/details/gt2twxlzoen.html

Ruby: threads.map(&:join)
来源：http://dali.zdqjudy.top/Article/details/gt2rzbnkxlr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.vqdsnc.cn/Article/details/gt2bwpdqrti.html

[O06] 使用进程池
来源：http://dali.gotoacloud.top/Article/details/gt2tahortvo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yongpay.top/Article/details/gt2knevfiwn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cucudq.cn/Article/details/gt2qxyxitdd.html

JS:   // child_process / cluster 模块
来源：http://dali.hysaishi.cn/Article/details/gt2rucsedii.html

TS:   // child_process / cluster 模块
来源：http://dali.xuanzx.com/Article/details/gt2dbplhreh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gotoacloud.top/Article/details/gt2sirywjtw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenzaomai.com/Article/details/gt2bixolvqt.html

Ruby: // fork 块
来源：http://dali.ppjwa.cn/Article/details/gt2qlmubkzh.html

C#:   Parallel.For
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jfkimsrt.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2eegpcmhm.html

P. 常用工具函数
来源：http://dali.cqqwz.cn/Article/details/gt2cgobfahu.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2iloyogqn.html

[P01] 生成 UUID
来源：http://dali.hnqzz.top/Article/details/gt2fuitxpxo.html

Py:   str(uuid.uuid4())
来源：http://dali.shuidangran.top/Article/details/gt2ithbjqaq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jyoumei.cn/Article/details/gt2kkitftcs.html

JS:   crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gt2eanopslc.html

TS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xnejvyfy.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgufenzy.top/Article/details/gt2deemdioy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.c1oappe.top/Article/details/gt2wbpfroqc.html

Ruby: SecureRandom.uuid
来源：http://dali.cashguo.top/Article/details/gt2eiocyjzo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cqqwz.cn/Article/details/gt2vkdjzvrg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.vqdsnc.cn/Article/details/gt2zcscvzpx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nanxuanxn.top/Article/details/gt2rdlhbrjo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenlongwang.top/Article/details/gt2szlzamns.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daria6918.cn/Article/details/gt2hzopiymx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenlongwang.top/Article/details/gt2ifskxyar.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yueranfly.top/Article/details/gt2zxyqrblw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.guannengcc.top/Article/details/gt2lvsgyrdd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tanke756.top/Article/details/gt2qbhhsvnf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ivvv.top/Article/details/gt2rpcvspbz.html

[P03] 生成短随机字符串
来源：http://dali.c1oappe.top/Article/details/gt2akvcnuuo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.mhx1999.top/Article/details/gt2dfdqifuv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.9152youxi.cn/Article/details/gt2aqolyquy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jianghu66.top/Article/details/gt2ddjhyknq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2shjehacs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.0kj1m.cn/Article/details/gt2jpzroaxz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bwnztexf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gzhubu.top/Article/details/gt2dasjbisf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daxiang520.top/Article/details/gt2hsbxcuhr.html

[P04] 求长度
来源：http://dali.zhoulong.xyz/Article/details/gt2kkgekmrr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xylfe.cn/Article/details/gt2pzgoacwu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gt2tupkvczl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gt2alzazpbz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daxiang520.top/Article/details/gt2tjndtdso.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hysaishi.cn/Article/details/gt2rfcijcto.html

Go:   len(arr);  len(m)
来源：http://dali.meibo888.top/Article/details/gt2umbuplkj.html

Ruby: x.length;  x.size
来源：http://dali.xinyue.icu/Article/details/gt2tmnsyyhs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj202588.top/Article/details/gt2jkvpqtjj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xuanzx.com/Article/details/gt2lvdeovfd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hongshengwenyu.top/Article/details/gt2cpghnizc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tian-w.cn/Article/details/gt2wluouizs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.mhx1999.top/Article/details/gt2edarjdtc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tanke756.top/Article/details/gt2cuelvivo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hywenlv.cn/Article/details/gt2brmrtfel.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aibaodan.cn/Article/details/gt2vsbntsmj.html

Ruby: a == b
来源：http://dali.yvedp.cn/Article/details/gt2ipcciwsu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.birdmap.top/Article/details/gt2tjvuspra.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfyglsx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj202588.top/Article/details/gt2dqmqqsve.html

PHP:  if (empty($x)) {}
来源：http://dali.hfpthk.cn/Article/details/gt2tatcrtnh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhongyouzk.top/Article/details/gt2xecrkpbj.html

TS:   if (x == null) {}
来源：http://dali.smart0.xyz/Article/details/gt2shxrpcgx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2rgvrjieh.html

Go:   if x == nil {}
来源：http://dali.zdqjudy.top/Article/details/gt2mwekarsx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nanprrzv.html

C#:   if (x is null) {}
来源：http://dali.xylfe.cn/Article/details/gt2iyvuayie.html

[P07] 防抖与节流
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ftjqzmrc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yonumen.top/Article/details/gt2tmtinius.html

PHP:  // 手写时间戳比较
来源：http://dali.nwbrower.top/Article/details/gt2piydumfy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gt2uyaasomu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gt2ptdkiwrb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2bhstiobs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yueranfly.top/Article/details/gt2bqafwgeu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dashuyun.cn/Article/details/gt2kyfdenhy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ehwqpu.com/Article/details/gt2iovfikny.html

[P08] 处理浮点精度问题
来源：http://dali.ivvv.top/Article/details/gt2hjovdajv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.snrcjt.cn/Article/details/gt2vvvtzpts.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj20258888.top/Article/details/gt2erswimvy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zycfv.cn/Article/details/gt2itkbzvkp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xuanzx.com/Article/details/gt2zylimayg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.dashuyun.cn/Article/details/gt2oqzptjew.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.iojbl.cn/Article/details/gt2fmkcjgbe.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuanzx.com/Article/details/gt2pzfziqkx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenzaomai.com/Article/details/gt2tkzbtojh.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2ypnnmjne.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nanxuanxn.top/Article/details/gt2nzmbqitc.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2vprtfqin.html

[Q01] 创建表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qlgjxzvt.html

CREATE TABLE users (
来源：http://dali.fzhhl.top/Article/details/gt2hsswrhdg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gt2khfujyot.html

name VARCHAR(50) NOT NULL,
来源：http://dali.mhx1999.top/Article/details/gt2tyaefvuy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkcfkvq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yueranfly.top/Article/details/gt2ughsayfc.html

);
来源：http://dali.ppjwa.cn/Article/details/gt2fjhjwgkd.html

[Q02] 创建带外键的表
来源：http://dali.fengsongda.top/Article/details/gt2ilgwkkqv.html

CREATE TABLE orders (
来源：http://dali.wangshuangyany.cn/Article/details/gt2hfoeuuov.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dianchejie.cn/Article/details/gt2ysefalmw.html

user_id INT NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gt2vkkcednp.html

amount DECIMAL(10, 2),
来源：http://dali.redwolf501.top/Article/details/gt2bfslcgwc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxuanxn.top/Article/details/gt2kyxgiyuo.html

);
来源：http://dali.hysaishi.cn/Article/details/gt2jmrxnsqo.html

[Q03] 增加列
来源：http://dali.aizwys.cn/Article/details/gt2ruanyupz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbyexpi.html

[Q04] 修改列类型
来源：http://dali.zhoulong.xyz/Article/details/gt2nrexvres.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.havefunace.top/Article/details/gt2zaybyjed.html

[Q05] 重命名列
来源：http://dali.zhengqikj.top/Article/details/gt2jsqbksoc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangdashe.top/Article/details/gt2kjoobjii.html

[Q06] 删除列
来源：http://dali.havefunace.top/Article/details/gt2rwlgacuz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fzhhl.top/Article/details/gt2ylrzwpgt.html

[Q07] 删除表
来源：http://dali.kuanghao11.cn/Article/details/gt2cvnuiajs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gotoacloud.top/Article/details/gt2caosdxds.html

[Q08] 创建普通索引
来源：http://dali.ydzc1.top/Article/details/gt2yzhiapjz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gt2aunsbmvo.html

[Q09] 创建唯一索引
来源：http://dali.yongpay.top/Article/details/gt2xrxzeszo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sufxvd.cn/Article/details/gt2jjbgxxdx.html

[Q10] 插入单行
来源：http://dali.tianlin.xyz/Article/details/gt2kiubjums.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mvraamig.html

[Q11] 一次插入多行
来源：http://dali.hammf.cn/Article/details/gt2flkfplby.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yvedp.cn/Article/details/gt2swylszid.html

[Q12] 插入后取自增 ID
来源：http://dali.zhixingplan.top/Article/details/gt2ohfauyhd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aibaodan.cn/Article/details/gt2hwmqddco.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xuanzx.com/Article/details/gt2sghkrcla.html

[Q13] 忽略重复插入
来源：http://dali.shuidangran.top/Article/details/gt2zdlvixup.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.9152youxi.cn/Article/details/gt2tfzvoczu.html

[Q14] 存在则更新（upsert）
来源：http://dali.cqqwz.cn/Article/details/gt2jvrjhfwb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gogol.net.cn/Article/details/gt2emwntvto.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fengsongda.top/Article/details/gt2zldtqsul.html

[Q15] 查询全部
来源：http://dali.yueranfly.top/Article/details/gt2zquyirsb.html


<!-- 参考信息 -->