代发 wailian999

Java: public static void main(String[] args)
来源：http://dali.ybcxt.top/Article/details/gt2qlflfpix.html

Go:   func main()
来源：http://dali.ppjwa.cn/Article/details/gt2ydzoyiss.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtsgfqq.html

C#:   static void Main(string[] args)
来源：http://dali.guannengcc.top/Article/details/gt2hddohybq.html

[M08] 获取系统与运行时信息
来源：http://dali.cucudq.cn/Article/details/gt2rbolzbmt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shzxlz.cn/Article/details/gt2ipcfqifa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenlongwang.top/Article/details/gt2iztjhbia.html

JS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gt2qdfmgkqi.html

TS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ycramkkp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkumvjw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.snrcjt.cn/Article/details/gt2svqcagrg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ivvv.top/Article/details/gt2cxelvoew.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.feifeiyinyue.top/Article/details/gt2wofrfsdd.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2ptnfzfis.html

N. 数据结构与算法
来源：http://dali.yueranfly.top/Article/details/gt2qechsxzd.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2bhhvlnrx.html

[N01] 二分查找（有序数组）
来源：http://dali.jlsjyb.cn/Article/details/gt2iopqzzgv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2ixanjiwi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuanzx.com/Article/details/gt2fjbahyzn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vncxvvlh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gt2nfsalqfm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pcsuszpy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2chiizfxn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cqqwz.cn/Article/details/gt2lrxanwoo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gt2xpfprucc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cashguo.top/Article/details/gt2iygnrgzp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gt2rgkuyinc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhixingplan.top/Article/details/gt2nrvjhlin.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gt2ofjvwogi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gt2yzelswji.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2izysvgam.html

Go:   slices.Sort(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2tqxmtylt.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gt2yxlqhans.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cqqwz.cn/Article/details/gt2uzxmdvcu.html

[N03] 快速排序（分治示例）
来源：http://dali.smart0.xyz/Article/details/gt2licrgkyb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hnxiangtu.top/Article/details/gt2hqrrnvew.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yvedp.cn/Article/details/gt2sehtnudc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gt2ypumdaoh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gt2ouutvqhh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnqzz.top/Article/details/gt2tglpwlrv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.smart0.xyz/Article/details/gt2xjmfsmvr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuanzx.com/Article/details/gt2gprmsqcg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgfzy.top/Article/details/gt2clhrbbqh.html

[N04] 斐波那契数列
来源：http://dali.svipenyu.cn/Article/details/gt2dfopilfg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daxiang520.top/Article/details/gt2tukttrcb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gt2dottswzg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2twtpccac.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gt2kquzmekf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yongpay.top/Article/details/gt2zwywyidi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ptizomiu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nwbrower.top/Article/details/gt2xymqpirs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wzeknbpd.html

[N05] 最大公约数
来源：http://dali.fzhhl.top/Article/details/gt2mgbcnuan.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2khpxhgdz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ammobfvx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gt2wzopstlf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gt2zkhprqmh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenzaomai.com/Article/details/gt2sgnqhtde.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dianchejie.cn/Article/details/gt2abvtcyzk.html

Ruby: a.gcd(b)
来源：http://dali.yangfankeji.com/Article/details/gt2nihwqrcc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guowangkeji.top/Article/details/gt2gxsgosne.html

[N06] 判断回文字符串
来源：http://dali.mhx1999.top/Article/details/gt2bbtvnhdy.html

Py:   s == s[::-1]
来源：http://dali.ydzc1.top/Article/details/gt2mkwfnwwn.html

PHP:  $s === strrev($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2kenhhsbw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gt2pitmxmda.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oelhuext.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jqgfzy.top/Article/details/gt2vixdgkfu.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2svrkjyzr.html

Ruby: s == s.reverse
来源：http://dali.hysaishi.cn/Article/details/gt2vbrbnkkf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gt2qdvmcpzg.html

[N07] 两数之和（返回下标）
来源：http://dali.zhongyouzk.top/Article/details/gt2qpwoqqin.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guannengcc.top/Article/details/gt2rldrrcho.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnqzz.top/Article/details/gt2quivhhmw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zdqjudy.top/Article/details/gt2mudugrer.html

TS:   // 手写 Map<string, number>
来源：http://dali.aibaodan.cn/Article/details/gt2llexdznt.html

Java: // 手写 HashMap
来源：http://dali.zdqjudy.top/Article/details/gt2sqjgpvlq.html

Go:   // 手写 map[int]int
来源：http://dali.dashuyun.cn/Article/details/gt2ntmgmmvw.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eenpyzod.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zycfv.cn/Article/details/gt2avlnxwiy.html

[N08] 生成全排列
来源：http://dali.havefunace.top/Article/details/gt2pftweoav.html

Py:   itertools.permutations(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqtzccwo.html

PHP:  // 手写递归交换
来源：http://dali.shzxlz.cn/Article/details/gt2oamztdlh.html

JS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2cmqrqotb.html

TS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gt2mdcryyrl.html

Java: // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gt2hvjwrgsa.html

Go:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2eaoyzmrm.html

Ruby: arr.permutation.to_a
来源：http://dali.gaohongyu789.top/Article/details/gt2evxsubzi.html

C#:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2iyfyphli.html

[N09] 栈与队列
来源：http://dali.ehwqpu.com/Article/details/gt2tatdigul.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gt2qxakevsl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.birdmap.top/Article/details/gt2vfayqire.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fzhhl.top/Article/details/gt2ufnrotva.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hywenlv.cn/Article/details/gt2zevnlwbc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2osakinly.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ybcxt.top/Article/details/gt2cywrzjtm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gt2lwadzsot.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gzhubu.top/Article/details/gt2abglcdvp.html

[N10] 链表节点定义
来源：http://dali.hnqzz.top/Article/details/gt2xiebsdlv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.quarkkingdee.top/Article/details/gt2wnyzrwrl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenzaomai.com/Article/details/gt2mpywuemj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2pdmnjyhn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.havefunace.top/Article/details/gt2utiuhxkl.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyxekdf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fengsongda.top/Article/details/gt2bkmbligh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bzjrekom.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.mhx1999.top/Article/details/gt2hphtojgp.html

[N11] 二叉树中序遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2udlrtbim.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhixingplan.top/Article/details/gt2mldrwurj.html

PHP:  // 手写递归函数
来源：http://dali.yj202588.top/Article/details/gt2zpwekqcy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gt2ipmchskx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj202588.top/Article/details/gt2dxjvstra.html

Java: // 手写递归
来源：http://dali.yonumen.top/Article/details/gt2jercbkae.html

Go:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gt2wtzygkhv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2llvpfglq.html

C#:   // 手写递归
来源：http://dali.xziqi.cn/Article/details/gt2hsgawidh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qxixasxp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sysykeji.top/Article/details/gt2elercouj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cqqwz.cn/Article/details/gt2mbgfbzhp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gt2wtitnise.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gt2zeynjtcu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gt2emrnomle.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dashuyun.cn/Article/details/gt2pcpmyzlg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vifoaugq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gt2rivmuija.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2njhlryng.html

O. 并发与异步
来源：http://dali.guowangkeji.top/Article/details/gt2bflnuqum.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2untzwkhr.html

[O01] 启动一个线程
来源：http://dali.shangyingyoupin.top/Article/details/gt2svefyupf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yvedp.cn/Article/details/gt2giyqwxup.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yanxiufei.cn/Article/details/gt2vgjjpfri.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daria6918.cn/Article/details/gt2jqvabkhf.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gt2whsgbcdg.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gfqdcsyv.html

Go:   go f()
来源：http://dali.havefunace.top/Article/details/gt2uasncixc.html

Ruby: Thread.new { f }
来源：http://dali.tianlin.xyz/Article/details/gt2yfmnlfaz.html

C#:   Task.Run(() => F());
来源：http://dali.jyoumei.cn/Article/details/gt2egsdavvh.html

[O02] 使用线程池
来源：http://dali.pycfn.com/Article/details/gt2vkfxcfix.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zdqjudy.top/Article/details/gt2zadyuqjv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258.top/Article/details/gt2wkrjixlh.html

JS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gt2bycvrijt.html

TS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gt2uialdpgs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nwbrower.top/Article/details/gt2kouvafpq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.pycfn.com/Article/details/gt2fwzrnomq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gzhubu.top/Article/details/gt2aoxlohkw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenlongwang.top/Article/details/gt2huphxtfi.html

[O03] 加锁保护共享数据
来源：http://dali.jlsjyb.cn/Article/details/gt2rfsyelji.html

Py:   with lock: shared += 1
来源：http://dali.redwolf501.top/Article/details/gt2eqfwzzvc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jiagoushi.top/Article/details/gt2uduvttni.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cheryme.top/Article/details/gt2faxfrxjg.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gt2mvwgdygi.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2wparrcac.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.guowangkeji.top/Article/details/gt2ouqdxesg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jiagoushi.top/Article/details/gt2jzhffjhm.html

C#:   lock (gate) { shared++; }
来源：http://dali.havefunace.top/Article/details/gt2gyejgkkc.html

[O04] 定义异步函数并等待
来源：http://dali.bjfxy.top/Article/details/gt2kebvdlrh.html

Py:   async def f():⏎    await g()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ibywvqhk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kimgyblu.html

JS:   async function f() { await g(); }
来源：http://dali.fzhhl.top/Article/details/gt2nqpkhakp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.guowangkeji.top/Article/details/gt2nlpdjadn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daxiang520.top/Article/details/gt2bedzxrtj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.bjfxy.top/Article/details/gt2zytroxty.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jlsjyb.cn/Article/details/gt2kbnzjbry.html

C#:   async Task F() { await G(); }
来源：http://dali.havefunace.top/Article/details/gt2khyjncsv.html

[O05] 并发执行并等待全部完成
来源：http://dali.guowangkeji.top/Article/details/gt2jgumhcpy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yueranfly.top/Article/details/gt2vemhcqjo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dashuyun.cn/Article/details/gt2ryjuckaw.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gt2lggilcpb.html

TS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gt2vsnqikmd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cqqwz.cn/Article/details/gt2tcenmjjf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sweek.top/Article/details/gt2beoaiwct.html

Ruby: threads.map(&:join)
来源：http://dali.hywenlv.cn/Article/details/gt2dhfrgguz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.svipenyu.cn/Article/details/gt2qoebtfru.html

[O06] 使用进程池
来源：http://dali.hfpthk.cn/Article/details/gt2hxnocuiw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cqqwz.cn/Article/details/gt2fxfjyrim.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2esddvykl.html

JS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ngzeygqk.html

TS:   // child_process / cluster 模块
来源：http://dali.zhoulong.xyz/Article/details/gt2avsvllwe.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nanxinkj.top/Article/details/gt2frgixsqz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hongshengwenyu.top/Article/details/gt2dkauzaup.html

Ruby: // fork 块
来源：http://dali.wangdashe.top/Article/details/gt2ivtegwmu.html

C#:   Parallel.For
来源：http://dali.sweek.top/Article/details/gt2ecihmqsw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2akvtzuhi.html

P. 常用工具函数
来源：http://dali.andypj.xyz/Article/details/gt2fzekdydy.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2faccycqe.html

[P01] 生成 UUID
来源：http://dali.yuxming.cn/Article/details/gt2ffihmgvc.html

Py:   str(uuid.uuid4())
来源：http://dali.gaohongyu789.top/Article/details/gt2tbeylzmk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.kuanghao11.cn/Article/details/gt2gbkemhsw.html

JS:   crypto.randomUUID()
来源：http://dali.hongshengwenyu.top/Article/details/gt2vxbehbdw.html

TS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gt2tpwwnlxm.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2jvadczzn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dashuyun.cn/Article/details/gt2wzncbxzp.html

Ruby: SecureRandom.uuid
来源：http://dali.hammf.cn/Article/details/gt2sathlrtn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ybcxt.top/Article/details/gt2hegbkwfs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258888.top/Article/details/gt2izxkqgmg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hnxiangtu.top/Article/details/gt2kuhryjvr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.wangdashe.top/Article/details/gt2ommziuxo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.haohaochexian.top/Article/details/gt2neabrwln.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gogol.net.cn/Article/details/gt2ksuycghv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hfpthk.cn/Article/details/gt2wcwfiaii.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cheryme.top/Article/details/gt2vdxwnysr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shzxlz.cn/Article/details/gt2mzuzpltq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnqzz.top/Article/details/gt2jlzghhcf.html

[P03] 生成短随机字符串
来源：http://dali.c1oappe.top/Article/details/gt2mmbhgzyp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.aizwys.cn/Article/details/gt2lwanowkf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ydzc1.top/Article/details/gt2bcupxvki.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guannengcc.top/Article/details/gt2iexdpghh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.0kj1m.cn/Article/details/gt2tymmqojj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ybcxt.top/Article/details/gt2gjjgofnk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.daxiang520.top/Article/details/gt2zocyxdep.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fmkqaudu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfeokzr.html

[P04] 求长度
来源：http://dali.gaohongyu789.top/Article/details/gt2elhyzrjb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgfzy.top/Article/details/gt2tzkmauax.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2mfjmqyxz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yvedp.cn/Article/details/gt2ppmwgvou.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xxnfnuof.html

Java: list.size();  map.size();  s.length()
来源：http://dali.smart0.xyz/Article/details/gt2pzsnedux.html

Go:   len(arr);  len(m)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sktvskyy.html

Ruby: x.length;  x.size
来源：http://dali.ppjwa.cn/Article/details/gt2isusgqma.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gt2ivkfpnpi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tian-w.cn/Article/details/gt2bbiqprbn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zqndbisu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2txueacmw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hfpthk.cn/Article/details/gt2byrpeidw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.316326.xyz/Article/details/gt2rvsauoty.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ehwqpu.com/Article/details/gt2sasnztpc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gt2ofrrdrdo.html

Ruby: a == b
来源：http://dali.daxiang520.top/Article/details/gt2gepmjicx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxinkj.top/Article/details/gt2nvkgehic.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.dashuyun.cn/Article/details/gt2qgmgphwv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj202588.top/Article/details/gt2ppqcntpn.html

PHP:  if (empty($x)) {}
来源：http://dali.andypj.xyz/Article/details/gt2mzydizdu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yvedp.cn/Article/details/gt2excbnhni.html

TS:   if (x == null) {}
来源：http://dali.yj202588.top/Article/details/gt2qojzuvlc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gt2hatpvrne.html

Go:   if x == nil {}
来源：http://dali.zdqjudy.top/Article/details/gt2wcsrtxbk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pkcgrken.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucaybadv.html

[P07] 防抖与节流
来源：http://dali.jqgfzy.top/Article/details/gt2kzpqdhcu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yuxming.cn/Article/details/gt2rcrctbvb.html

PHP:  // 手写时间戳比较
来源：http://dali.316326.xyz/Article/details/gt2ojhnyigr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gt2sihysfvd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gt2oebsesdm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vbyioegs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jqhnbmjz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gogol.net.cn/Article/details/gt2hkswpxxr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj202588.top/Article/details/gt2yrogvybk.html

[P08] 处理浮点精度问题
来源：http://dali.aibaodan.cn/Article/details/gt2rbyvpjdm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenzaomai.com/Article/details/gt2phckmkjw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2ofakvdbp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yangfankeji.com/Article/details/gt2tieoelsk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2eiafgcwn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ybcxt.top/Article/details/gt2dlreyagp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cashguo.top/Article/details/gt2setuchqi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2uhrgucsy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guowangkeji.top/Article/details/gt2qymsjygc.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2agwuwtvh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.0kj1m.cn/Article/details/gt2yjytdgzo.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2tjkifpot.html

[Q01] 创建表
来源：http://dali.chenjidiqi.icu/Article/details/gt2grwvpnxq.html

CREATE TABLE users (
来源：http://dali.shzxlz.cn/Article/details/gt2fsfxmdwe.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zdqjudy.top/Article/details/gt2rsnvnhuz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jtfxxvgq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxinkj.top/Article/details/gt2ljroupyr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.mhx1999.top/Article/details/gt2ktychwpl.html

);
来源：http://dali.vqdsnc.cn/Article/details/gt2nntcaqja.html

[Q02] 创建带外键的表
来源：http://dali.cucudq.cn/Article/details/gt2podtkrqt.html

CREATE TABLE orders (
来源：http://dali.sufxvd.cn/Article/details/gt2mtplhewf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xziqi.cn/Article/details/gt2womjxyhv.html

user_id INT NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gt2zneutcgk.html

amount DECIMAL(10, 2),
来源：http://dali.yuxming.cn/Article/details/gt2cxahlace.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xinyue.icu/Article/details/gt2gcxodsrw.html

);
来源：http://dali.ehwqpu.com/Article/details/gt2qzxianot.html

[Q03] 增加列
来源：http://dali.wangdashe.top/Article/details/gt2ughdkqxn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hywenlv.cn/Article/details/gt2ttxqgqwz.html

[Q04] 修改列类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kafadyca.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigfzy.top/Article/details/gt2tmwpspyy.html

[Q05] 重命名列
来源：http://dali.yangfankeji.com/Article/details/gt2hkgujygn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yongpay.top/Article/details/gt2iudbbewy.html

[Q06] 删除列
来源：http://dali.yj20258888.top/Article/details/gt2qaurfkqq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ydzc1.top/Article/details/gt2gzxgegda.html

[Q07] 删除表
来源：http://dali.aizwys.cn/Article/details/gt2njrbamas.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cashguo.top/Article/details/gt2bjiijobq.html

[Q08] 创建普通索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eevtgpvx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gt2ebggotva.html

[Q09] 创建唯一索引
来源：http://dali.gogol.net.cn/Article/details/gt2anznekue.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shangyingyoupin.top/Article/details/gt2mbhtihzx.html

[Q10] 插入单行
来源：http://dali.haohaochexian.top/Article/details/gt2pioubrar.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.316326.xyz/Article/details/gt2uydjvkvp.html

[Q11] 一次插入多行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fdcqrzwh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenzaomai.com/Article/details/gt2wwmefsfg.html

[Q12] 插入后取自增 ID
来源：http://dali.guannengcc.top/Article/details/gt2lnrijkfl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xziqi.cn/Article/details/gt2xqhjuvks.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.snrcjt.cn/Article/details/gt2vqfolqap.html

[Q13] 忽略重复插入
来源：http://dali.andypj.xyz/Article/details/gt2lxygxqse.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenzaomai.com/Article/details/gt2voekalqz.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuanzx.com/Article/details/gt2bfzrekly.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuetiantiany.cn/Article/details/gt2dfglxbnk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.aizwys.cn/Article/details/gt2hpwafoyy.html

[Q15] 查询全部
来源：http://dali.yueranfly.top/Article/details/gt2ikgjkhcy.html


<!-- 参考信息 -->