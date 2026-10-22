代发 wailian999

Java: public static void main(String[] args)
来源：http://dali.sufxvd.cn/Article/details/gt2kxhzzvnf.html

Go:   func main()
来源：http://dali.zdqjudy.top/Article/details/gt2owhmbwiy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.c1oappe.top/Article/details/gt2rdgggcid.html

C#:   static void Main(string[] args)
来源：http://dali.ybcxt.top/Article/details/gt2mvguobui.html

[M08] 获取系统与运行时信息
来源：http://dali.iojbl.cn/Article/details/gt2wvpxpwkj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhongyouzk.top/Article/details/gt2fgudjowc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.havefunace.top/Article/details/gt2mdybcjif.html

JS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gt2zcyvtbmt.html

TS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gt2zanbfixe.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tanke756.top/Article/details/gt2oajonivz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aizwys.cn/Article/details/gt2kufoftue.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenzaomai.com/Article/details/gt2hklpcqwl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ppjwa.cn/Article/details/gt2cjrpfnvo.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2rhfpvjuy.html

N. 数据结构与算法
来源：http://dali.yvedp.cn/Article/details/gt2vqhinkrj.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2cyhnrmve.html

[N01] 二分查找（有序数组）
来源：http://dali.yongpay.top/Article/details/gt2yssvbzcb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gt2hcvsrcet.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xziqi.cn/Article/details/gt2qzoweacn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gt2bkaphpyn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnqzz.top/Article/details/gt2ttrqknkk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2ahecehck.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2culdtgqu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jqgufenzy.top/Article/details/gt2zoeocqod.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2fwntjaru.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.smart0.xyz/Article/details/gt2toplvpyc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gt2wekzrqmw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenlongwang.top/Article/details/gt2uxncebzc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gt2ztnbiidk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xcyofzfl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shuidangran.top/Article/details/gt2sgpntwka.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2ztznucgf.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gt2ybpbysll.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ivvv.top/Article/details/gt2fzlslwkp.html

[N03] 快速排序（分治示例）
来源：http://dali.pengpengdd.cyou/Article/details/gt2izitbqnx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shzxlz.cn/Article/details/gt2quskkohw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.smart0.xyz/Article/details/gt2ughymdqb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gt2bsowtdtc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuanzhike.top/Article/details/gt2hmadtucb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sufxvd.cn/Article/details/gt2gxhswvfk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zycfv.cn/Article/details/gt2tuxeruts.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cashguo.top/Article/details/gt2xcdhogwb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hongshengwenyu.top/Article/details/gt2gppqbzec.html

[N04] 斐波那契数列
来源：http://dali.jqgufenzy.top/Article/details/gt2yjahmlal.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gt2timxvrxb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.iojbl.cn/Article/details/gt2lzvfaqgu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gt2fgliklyl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gt2njickuqt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gt2audeppzc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fengsongda.top/Article/details/gt2hzjvjycn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2itpbuykw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gt2gskzxvpo.html

[N05] 最大公约数
来源：http://dali.zhiwuduotai.top/Article/details/gt2ewbltngb.html

Py:   math.gcd(a, b)
来源：http://dali.aizwys.cn/Article/details/gt2pmkacdla.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gaohongyu789.top/Article/details/gt2yiewhtsy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxinkj.top/Article/details/gt2pnhusckd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ydzc1.top/Article/details/gt2ntbokcgt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hysaishi.cn/Article/details/gt2vqdenvew.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhixingplan.top/Article/details/gt2ilphxxdx.html

Ruby: a.gcd(b)
来源：http://dali.xylfe.cn/Article/details/gt2ihxkzejg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zdqjudy.top/Article/details/gt2ebsfwgwd.html

[N06] 判断回文字符串
来源：http://dali.fengsongda.top/Article/details/gt2bbnpujiy.html

Py:   s == s[::-1]
来源：http://dali.ydzc1.top/Article/details/gt2ghgbrcjw.html

PHP:  $s === strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gt2zqtxuqmc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gt2gzufktqe.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gt2hjhnxhzw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ppjwa.cn/Article/details/gt2okmvvifw.html

Go:   // 双指针从两端比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2ybmmacek.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrdvtty.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gt2mwwksgko.html

[N07] 两数之和（返回下标）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cvkubvem.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xuetiantiany.cn/Article/details/gt2dgjqwexz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ppjwa.cn/Article/details/gt2kggvmbns.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenlongwang.top/Article/details/gt2vehdrdxo.html

TS:   // 手写 Map<string, number>
来源：http://dali.meibo888.top/Article/details/gt2dkvciaer.html

Java: // 手写 HashMap
来源：http://dali.zhoulong.xyz/Article/details/gt2ymrtpkfb.html

Go:   // 手写 map[int]int
来源：http://dali.gaohongyu789.top/Article/details/gt2abewokgu.html

Ruby: // 手写 Hash
来源：http://dali.jianghu66.top/Article/details/gt2aajfayzf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.9152youxi.cn/Article/details/gt2tkvxydwe.html

[N08] 生成全排列
来源：http://dali.sxryk.cn/Article/details/gt2mvzwqrqk.html

Py:   itertools.permutations(arr)
来源：http://dali.daria6918.cn/Article/details/gt2zjhduoid.html

PHP:  // 手写递归交换
来源：http://dali.hnxiangtu.top/Article/details/gt2tizmjnvt.html

JS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rszwhrfd.html

TS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2zrhbafaa.html

Java: // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2xpbynfwf.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iktfeamd.html

Ruby: arr.permutation.to_a
来源：http://dali.sweek.top/Article/details/gt2bnuatzyz.html

C#:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2abhjaogo.html

[N09] 栈与队列
来源：http://dali.gotoacloud.top/Article/details/gt2jvljjiar.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenzaomai.com/Article/details/gt2zpilwick.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2tsmglacv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sysykeji.top/Article/details/gt2wgoqcriz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jianghu66.top/Article/details/gt2fojbcdoa.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cdnleiting.top/Article/details/gt2lysehism.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.c1oappe.top/Article/details/gt2zdxmpbuk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gt2ebwegerx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2atziivgg.html

[N10] 链表节点定义
来源：http://dali.yj20258888.top/Article/details/gt2jvmjmkix.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cheryme.top/Article/details/gt2osfxedzc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hysaishi.cn/Article/details/gt2qkywtkkp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2sececypr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.0kj1m.cn/Article/details/gt2lbwkvkwl.html

Java: class Node { int v; Node next; }
来源：http://dali.gzhubu.top/Article/details/gt2pgrpymkm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhongyouzk.top/Article/details/gt2oipcixke.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenzaomai.com/Article/details/gt2ympkoxjh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.9152youxi.cn/Article/details/gt2rgweczxt.html

[N11] 二叉树中序遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2ptkfwfjj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hjescoye.html

PHP:  // 手写递归函数
来源：http://dali.zhixingplan.top/Article/details/gt2nbmiypho.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xziqi.cn/Article/details/gt2rjuhxjgy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dianchejie.cn/Article/details/gt2fzcrvywe.html

Java: // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gt2hsppfqjr.html

Go:   // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2bsztassx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tanke756.top/Article/details/gt2qogqxldy.html

C#:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gt2ifrotcwn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cqqwz.cn/Article/details/gt2zsrnhhpb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cashguo.top/Article/details/gt2kereegwr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.mhx1999.top/Article/details/gt2asidaccj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.snrcjt.cn/Article/details/gt2qrfyvjgk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gt2zfsxprgs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gaohongyu789.top/Article/details/gt2jkzoiejn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cucudq.cn/Article/details/gt2pyemiwva.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zycfv.cn/Article/details/gt2zvevnmho.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gt2fcvexkxk.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2qgzzwccc.html

O. 并发与异步
来源：http://dali.chenjidiqi.icu/Article/details/gt2cmvfjniw.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2rebcrhqi.html

[O01] 启动一个线程
来源：http://dali.shzxlz.cn/Article/details/gt2hsodcoft.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuanzhike.top/Article/details/gt2lqtmetwk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hfpthk.cn/Article/details/gt2npugviwx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xylfe.cn/Article/details/gt2yyszdeoq.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gt2qxqtthir.html

Java: new Thread(() -> f()).start()
来源：http://dali.tanke756.top/Article/details/gt2cligplrb.html

Go:   go f()
来源：http://dali.cdnleiting.top/Article/details/gt2ylvvjfne.html

Ruby: Thread.new { f }
来源：http://dali.fengsongda.top/Article/details/gt2ijitlkud.html

C#:   Task.Run(() => F());
来源：http://dali.aizwys.cn/Article/details/gt2vduhlplv.html

[O02] 使用线程池
来源：http://dali.haohaochexian.top/Article/details/gt2jcqzhjbp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fengsongda.top/Article/details/gt2khamzeaw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cashguo.top/Article/details/gt2ikiddxqf.html

JS:   // worker_threads 线程池
来源：http://dali.fzhhl.top/Article/details/gt2oltftbup.html

TS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gt2tqriqfiv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tanke756.top/Article/details/gt2qqevwqgt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgfzy.top/Article/details/gt2uwcugjhp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kbhdbozp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xylfe.cn/Article/details/gt2okcebjss.html

[O03] 加锁保护共享数据
来源：http://dali.cucudq.cn/Article/details/gt2etdsrmsf.html

Py:   with lock: shared += 1
来源：http://dali.jianghu66.top/Article/details/gt2oyiwqmbf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ppjwa.cn/Article/details/gt2hxobjsuh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cashguo.top/Article/details/gt2klgtobbn.html

TS:   // 同 JS
来源：http://dali.yangfankeji.com/Article/details/gt2dlrsoqeb.html

Java: synchronized (this) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jkrmdmyl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhongyouzk.top/Article/details/gt2nojqwkml.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zdqjudy.top/Article/details/gt2xegczbpe.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hhffzpyv.html

[O04] 定义异步函数并等待
来源：http://dali.ydzc1.top/Article/details/gt2hiplqhwj.html

Py:   async def f():⏎    await g()
来源：http://dali.nwbrower.top/Article/details/gt2ytakvczi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.0kj1m.cn/Article/details/gt2jyxvejbh.html

JS:   async function f() { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2ixqvsbbd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gt2rjooivtj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ydzc1.top/Article/details/gt2oxebmort.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dianchejie.cn/Article/details/gt2qjocverm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhongyouzk.top/Article/details/gt2mqubjjjq.html

C#:   async Task F() { await G(); }
来源：http://dali.xziqi.cn/Article/details/gt2fdrvirta.html

[O05] 并发执行并等待全部完成
来源：http://dali.svipenyu.cn/Article/details/gt2lmjvkdey.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cheryme.top/Article/details/gt2bffchrjn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.vqdsnc.cn/Article/details/gt2zzlwgqkl.html

JS:   await Promise.all(tasks)
来源：http://dali.jlsjyb.cn/Article/details/gt2ufvrpdxr.html

TS:   await Promise.all(tasks)
来源：http://dali.cqqwz.cn/Article/details/gt2jweakmlw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.aizwys.cn/Article/details/gt2tzmrmvch.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hfpthk.cn/Article/details/gt2dxdgjrqz.html

Ruby: threads.map(&:join)
来源：http://dali.iojbl.cn/Article/details/gt2wxweexop.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2atzykmco.html

[O06] 使用进程池
来源：http://dali.chenzaomai.com/Article/details/gt2ykxsasfv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.smart0.xyz/Article/details/gt2wwvlrdrw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zdqjudy.top/Article/details/gt2pcqndspi.html

JS:   // child_process / cluster 模块
来源：http://dali.nanxuanxn.top/Article/details/gt2alfnqwcj.html

TS:   // child_process / cluster 模块
来源：http://dali.quarkkingdee.top/Article/details/gt2wlbwbrqf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jlsjyb.cn/Article/details/gt2qmjhylrx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.havefunace.top/Article/details/gt2afqpsgwe.html

Ruby: // fork 块
来源：http://dali.hfpthk.cn/Article/details/gt2wshrlzls.html

C#:   Parallel.For
来源：http://dali.dashuyun.cn/Article/details/gt2dveciahx.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2pnokmlii.html

P. 常用工具函数
来源：http://dali.fzhhl.top/Article/details/gt2hngxspmi.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2iujrujrw.html

[P01] 生成 UUID
来源：http://dali.shangyingyoupin.top/Article/details/gt2mkaozdjv.html

Py:   str(uuid.uuid4())
来源：http://dali.sysykeji.top/Article/details/gt2blcwxajt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhixingplan.top/Article/details/gt2rtxthjba.html

JS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gt2qabgoopa.html

TS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gt2qruawzjf.html

Java: UUID.randomUUID().toString()
来源：http://dali.jyoumei.cn/Article/details/gt2ufuuvxbp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sxryk.cn/Article/details/gt2mprwpreq.html

Ruby: SecureRandom.uuid
来源：http://dali.xuetiantiany.cn/Article/details/gt2dtijoskx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2izbhmviy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hongshengwenyu.top/Article/details/gt2mogrclav.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhixingplan.top/Article/details/gt2ambqnhwq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2rzhbnyla.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2qcbbjsch.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dashuyun.cn/Article/details/gt2vcijowtm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.redwolf501.top/Article/details/gt2jqiqetss.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hnqzz.top/Article/details/gt2ynokmfkt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hywenlv.cn/Article/details/gt2qrerwnxm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.haohaochexian.top/Article/details/gt2ifdrbxjb.html

[P03] 生成短随机字符串
来源：http://dali.meibo888.top/Article/details/gt2uachacfz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jlsjyb.cn/Article/details/gt2wbiblspc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jyoumei.cn/Article/details/gt2aowdkteu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenzaomai.com/Article/details/gt2szwgmoak.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aizwys.cn/Article/details/gt2ufzrrrfm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jyoumei.cn/Article/details/gt2vfiswycm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.wangdashe.top/Article/details/gt2aydrelwu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yanxiufei.cn/Article/details/gt2yekpjlic.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.c1oappe.top/Article/details/gt2wcfdqffa.html

[P04] 求长度
来源：http://dali.guannengcc.top/Article/details/gt2xsxzrqgz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenlongwang.top/Article/details/gt2hkbzwyll.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gt2umzlrxrj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sufxvd.cn/Article/details/gt2rehhfwgl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gt2tymvaiiw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mniirmaa.html

Go:   len(arr);  len(m)
来源：http://dali.9152youxi.cn/Article/details/gt2qusjkisg.html

Ruby: x.length;  x.size
来源：http://dali.aizwys.cn/Article/details/gt2egqibesv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.daria6918.cn/Article/details/gt2gaqotmix.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ivvv.top/Article/details/gt2oolupyjm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ybcxt.top/Article/details/gt2bqvmbcvp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gotoacloud.top/Article/details/gt2otkkyafs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2lygyboir.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nwbrower.top/Article/details/gt2evevrqhy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenjidiqi.icu/Article/details/gt2boabylhp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aizwys.cn/Article/details/gt2gybobnfc.html

Ruby: a == b
来源：http://dali.yj202588.top/Article/details/gt2szgwuizw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.bjfxy.top/Article/details/gt2iqppmfgl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.0kj1m.cn/Article/details/gt2shiciirf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gaohongyu789.top/Article/details/gt2ofkpykir.html

PHP:  if (empty($x)) {}
来源：http://dali.xuanzx.com/Article/details/gt2kmvqffxa.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.9152youxi.cn/Article/details/gt2gqcqhgvq.html

TS:   if (x == null) {}
来源：http://dali.yongpay.top/Article/details/gt2ymjleurp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gt2igcqhxej.html

Go:   if x == nil {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ndilbypd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jqgfzy.top/Article/details/gt2yurwflwq.html

C#:   if (x is null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2svdhflgr.html

[P07] 防抖与节流
来源：http://dali.bjfxy.top/Article/details/gt2dcxqniey.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hongshengwenyu.top/Article/details/gt2hthxgnis.html

PHP:  // 手写时间戳比较
来源：http://dali.jyoumei.cn/Article/details/gt2fpwkxdwy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gt2suklzxcj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zycfv.cn/Article/details/gt2ijjpmrsa.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.haohaochexian.top/Article/details/gt2nmshhbin.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.snrcjt.cn/Article/details/gt2dnqfxgdb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenjidiqi.icu/Article/details/gt2uiurolny.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.9152youxi.cn/Article/details/gt2frwoqqor.html

[P08] 处理浮点精度问题
来源：http://dali.zycfv.cn/Article/details/gt2bzzehzzl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2byhkiohq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.haohaochexian.top/Article/details/gt2tqfmpfaf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rpuhnxke.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yangfankeji.com/Article/details/gt2lflqmygl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.kuanghao11.cn/Article/details/gt2bnzwvxfq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dashuyun.cn/Article/details/gt2ugpkkxrx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.meibo888.top/Article/details/gt2ariqmobf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2guxzasmh.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2yfktbunq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lmyoxeym.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2gnzpdmlc.html

[Q01] 创建表
来源：http://dali.gaohongyu789.top/Article/details/gt2firqqpcw.html

CREATE TABLE users (
来源：http://dali.9152youxi.cn/Article/details/gt2jyrrluph.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gt2zvnzprbr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daxiang520.top/Article/details/gt2igdbwyba.html

email VARCHAR(100) UNIQUE,
来源：http://dali.vqdsnc.cn/Article/details/gt2broireav.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gogol.net.cn/Article/details/gt2tkvupwsb.html

);
来源：http://dali.tian-w.cn/Article/details/gt2lxbgsody.html

[Q02] 创建带外键的表
来源：http://dali.guowangkeji.top/Article/details/gt2jejtazfi.html

CREATE TABLE orders (
来源：http://dali.tianlin.xyz/Article/details/gt2xdgsdtio.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gt2nywqplnz.html

user_id INT NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gt2ljpgdctq.html

amount DECIMAL(10, 2),
来源：http://dali.zdqjudy.top/Article/details/gt2ebxadaxi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ydzc1.top/Article/details/gt2jmvmgjvt.html

);
来源：http://dali.jiagoushi.top/Article/details/gt2apykzszt.html

[Q03] 增加列
来源：http://dali.xylfe.cn/Article/details/gt2mbjusjfg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hnqzz.top/Article/details/gt2gajjbjzq.html

[Q04] 修改列类型
来源：http://dali.9152youxi.cn/Article/details/gt2csvbtxwv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zdqjudy.top/Article/details/gt2oruucjqk.html

[Q05] 重命名列
来源：http://dali.jiagoushi.top/Article/details/gt2tgdsroaa.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xuetiantiany.cn/Article/details/gt2wttwwwcq.html

[Q06] 删除列
来源：http://dali.daxiang520.top/Article/details/gt2abjvmjqg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shuidangran.top/Article/details/gt2sybvpibb.html

[Q07] 删除表
来源：http://dali.xziqi.cn/Article/details/gt2ehwsdtwb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.wangshuangyany.cn/Article/details/gt2mcmdovsl.html

[Q08] 创建普通索引
来源：http://dali.vqdsnc.cn/Article/details/gt2jlnirdcw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hywenlv.cn/Article/details/gt2efufmgio.html

[Q09] 创建唯一索引
来源：http://dali.cheryme.top/Article/details/gt2kcajxuvd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gt2hqwgrrpz.html

[Q10] 插入单行
来源：http://dali.quarkkingdee.top/Article/details/gt2hctoejcc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258888.top/Article/details/gt2dflzqjqw.html

[Q11] 一次插入多行
来源：http://dali.sufxvd.cn/Article/details/gt2xjvgomuv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.0kj1m.cn/Article/details/gt2ckvoafof.html

[Q12] 插入后取自增 ID
来源：http://dali.meibo888.top/Article/details/gt2gurrxmvb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhoulong.xyz/Article/details/gt2nubbecia.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.birdmap.top/Article/details/gt2cftgrnbf.html

[Q13] 忽略重复插入
来源：http://dali.ydzc1.top/Article/details/gt2ekyatvnc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj202588.top/Article/details/gt2oavniqhn.html

[Q14] 存在则更新（upsert）
来源：http://dali.cheryme.top/Article/details/gt2jwlcoipl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zdqjudy.top/Article/details/gt2pklhhahe.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cucudq.cn/Article/details/gt2lcalpfyc.html

[Q15] 查询全部
来源：http://dali.fengsongda.top/Article/details/gt2kdojhupp.html


<!-- 参考信息 -->