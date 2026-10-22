代发 wailian999

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xylfe.cn/Article/details/gt2drbnuvma.html

Ruby: warn "err"
来源：http://dali.smart0.xyz/Article/details/gt2jfunclxw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenjidiqi.icu/Article/details/gt2hwdzedst.html

[M07] 判断是否为主入口
来源：http://dali.fzhhl.top/Article/details/gt2dkfsftrj.html

Py:   if __name__ == "__main__":
来源：http://dali.andypj.xyz/Article/details/gt2obmsodmq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258.top/Article/details/gt2dsiefrih.html

JS:   require.main === module
来源：http://dali.sysykeji.top/Article/details/gt2eosfjppo.html

TS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gt2rfvpkkfe.html

Java: public static void main(String[] args)
来源：http://dali.chenlongwang.top/Article/details/gt2ftprorep.html

Go:   func main()
来源：http://dali.yonumen.top/Article/details/gt2ovvlneje.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sweek.top/Article/details/gt2bjyvuhdy.html

C#:   static void Main(string[] args)
来源：http://dali.ydzc1.top/Article/details/gt2cevrzupw.html

[M08] 获取系统与运行时信息
来源：http://dali.cashguo.top/Article/details/gt2ctsfznsy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hfpthk.cn/Article/details/gt2elhznwzo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wfmyxgbc.html

JS:   process.platform;  process.version
来源：http://dali.sufxvd.cn/Article/details/gt2xbflhdtj.html

TS:   process.platform;  process.version
来源：http://dali.fengsongda.top/Article/details/gt2pqpezvqe.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.havefunace.top/Article/details/gt2votlqfwt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhixingplan.top/Article/details/gt2rvumkujs.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hfpthk.cn/Article/details/gt2ypkezwah.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ppjwa.cn/Article/details/gt2pawuidbq.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2qkvbhrst.html

N. 数据结构与算法
来源：http://dali.zhongyouzk.top/Article/details/gt2nmdiupbf.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2bdgmwujt.html

[N01] 二分查找（有序数组）
来源：http://dali.iojbl.cn/Article/details/gt2tokqgcbn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nhfjvdwi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigufen.top/Article/details/gt2nfivqfio.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gt2gfjovvtm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2obcousqg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2dqzwwrbt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2ghqdzykn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.svipenyu.cn/Article/details/gt2jxepodmp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2iemegxgd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvftyalo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gt2ldchmxsw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhengqikj.top/Article/details/gt2jljyztnw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gt2skthehpt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gt2dgjatqqg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhoulong.xyz/Article/details/gt2cvqzgvpd.html

Go:   slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2rkcbjowx.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gt2ykhsdbgu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2frysvtty.html

[N03] 快速排序（分治示例）
来源：http://dali.shangyingyoupin.top/Article/details/gt2sfgjvtne.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gzhubu.top/Article/details/gt2bbdnnphr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.dianchejie.cn/Article/details/gt2pdtaokhk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuetiantiany.cn/Article/details/gt2tsdxhxoq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gt2gwifucrt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fzhhl.top/Article/details/gt2kohxwrnu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yonumen.top/Article/details/gt2gpierktc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhengqikj.top/Article/details/gt2noreurvn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258.top/Article/details/gt2fsfposen.html

[N04] 斐波那契数列
来源：http://dali.zhongyouzk.top/Article/details/gt2jouohkhz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gt2obovlkmu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gt2ndqubmsw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gt2vmidatdj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gt2iwnjsuqv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gt2rbaoxweq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hywenlv.cn/Article/details/gt2icupyvik.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2sbxbrohr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gt2ujbtjfdc.html

[N05] 最大公约数
来源：http://dali.xylfe.cn/Article/details/gt2ejdmiebg.html

Py:   math.gcd(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2duadscne.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gotoacloud.top/Article/details/gt2bcqfmwrn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.quarkkingdee.top/Article/details/gt2qoknaxqb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gt2vknvpkpj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aibaodan.cn/Article/details/gt2sxmvopaf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shuidangran.top/Article/details/gt2sqfxnhmo.html

Ruby: a.gcd(b)
来源：http://dali.hywenlv.cn/Article/details/gt2dfkowoab.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bzzmsgoa.html

[N06] 判断回文字符串
来源：http://dali.dianchejie.cn/Article/details/gt2bfhhubyp.html

Py:   s == s[::-1]
来源：http://dali.hnqzz.top/Article/details/gt2lkcotmvt.html

PHP:  $s === strrev($s);
来源：http://dali.gzhubu.top/Article/details/gt2uuhwvjet.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gt2bgbzdnzp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ihvmxijj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yueranfly.top/Article/details/gt2poipiwlq.html

Go:   // 双指针从两端比较
来源：http://dali.cucudq.cn/Article/details/gt2zyowcrbg.html

Ruby: s == s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gt2rfplgvuw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gt2supqqryo.html

[N07] 两数之和（返回下标）
来源：http://dali.gzhubu.top/Article/details/gt2mycorkbe.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aizwys.cn/Article/details/gt2xalyroji.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nwbrower.top/Article/details/gt2dvedsgkx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yonumen.top/Article/details/gt2gqazxnqw.html

TS:   // 手写 Map<string, number>
来源：http://dali.ppjwa.cn/Article/details/gt2jqokjxdo.html

Java: // 手写 HashMap
来源：http://dali.hnqzz.top/Article/details/gt2opqxglkh.html

Go:   // 手写 map[int]int
来源：http://dali.316326.xyz/Article/details/gt2kgxqeobt.html

Ruby: // 手写 Hash
来源：http://dali.jinqigufen.top/Article/details/gt2dhbysnss.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.havefunace.top/Article/details/gt2hmpgaqzv.html

[N08] 生成全排列
来源：http://dali.hongshengwenyu.top/Article/details/gt2jiofbvur.html

Py:   itertools.permutations(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tdcjasdr.html

PHP:  // 手写递归交换
来源：http://dali.cqqwz.cn/Article/details/gt2bqydoozd.html

JS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2fvlkhxad.html

TS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2evwegjwx.html

Java: // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2vjrbuvgd.html

Go:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2fdgqaath.html

Ruby: arr.permutation.to_a
来源：http://dali.gogol.net.cn/Article/details/gt2xibwrbyk.html

C#:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gt2qwydcmkt.html

[N09] 栈与队列
来源：http://dali.dashuyun.cn/Article/details/gt2aqhxbrbl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yuxming.cn/Article/details/gt2gkjuicrx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xinyue.icu/Article/details/gt2tjbjnpxv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gt2rjxmpjut.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.316326.xyz/Article/details/gt2iwqtrbrl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sweek.top/Article/details/gt2lbnwiopu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yongpay.top/Article/details/gt2zqrvsaum.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gt2zpdasqes.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sufxvd.cn/Article/details/gt2cbxojxci.html

[N10] 链表节点定义
来源：http://dali.9152youxi.cn/Article/details/gt2tszffwrj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tianlin.xyz/Article/details/gt2qpkxuqnm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cqqwz.cn/Article/details/gt2frvzbnav.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sxryk.cn/Article/details/gt2lanentpw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gzhubu.top/Article/details/gt2yggxybze.html

Java: class Node { int v; Node next; }
来源：http://dali.yongpay.top/Article/details/gt2hlnvktgk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gzhubu.top/Article/details/gt2qlbgqynz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sweek.top/Article/details/gt2assydvbo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hammf.cn/Article/details/gt2hpwbaoku.html

[N11] 二叉树中序遍历
来源：http://dali.cheryme.top/Article/details/gt2bhnxbshw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yonumen.top/Article/details/gt2gwlrvnxf.html

PHP:  // 手写递归函数
来源：http://dali.cdnleiting.top/Article/details/gt2rbmbovuw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gt2agmpdamb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gt2lhkpjbak.html

Java: // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wjjadslq.html

Go:   // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gt2djfkaecm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guowangkeji.top/Article/details/gt2mkcsqxct.html

C#:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gt2ymklnqds.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.feifeiyinyue.top/Article/details/gt2vpzdoerp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fengsongda.top/Article/details/gt2hrmldies.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yanxiufei.cn/Article/details/gt2gxrehjmz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gt2zzqgilpi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gt2llgquyux.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gt2tkjtuvqc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhixingplan.top/Article/details/gt2khahvvzc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fengsongda.top/Article/details/gt2djkdzayc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gt2wdxsrucz.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2oljrkmrd.html

O. 并发与异步
来源：http://dali.ydzc1.top/Article/details/gt2wswcqmrx.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2xszuhqcv.html

[O01] 启动一个线程
来源：http://dali.birdmap.top/Article/details/gt2mlovxeci.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gotoacloud.top/Article/details/gt2mrccgwuh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gogol.net.cn/Article/details/gt2waejcxpc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258888.top/Article/details/gt2vdwotuka.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gt2hjcyjhtk.html

Java: new Thread(() -> f()).start()
来源：http://dali.ivvv.top/Article/details/gt2zxlqqgbh.html

Go:   go f()
来源：http://dali.gogol.net.cn/Article/details/gt2wkagoinj.html

Ruby: Thread.new { f }
来源：http://dali.jqgfzy.top/Article/details/gt2gazjeejg.html

C#:   Task.Run(() => F());
来源：http://dali.yvedp.cn/Article/details/gt2eobdhktw.html

[O02] 使用线程池
来源：http://dali.hnxiangtu.top/Article/details/gt2bkfqxvqe.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2smkrdjoh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzaxrgs.html

JS:   // worker_threads 线程池
来源：http://dali.zhiwuduotai.top/Article/details/gt2cwxxbqnf.html

TS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gt2sgfwhqdr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jyoumei.cn/Article/details/gt2hkhowqrl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhengqikj.top/Article/details/gt2ibxacjau.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hysaishi.cn/Article/details/gt2vvofgvwp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shuidangran.top/Article/details/gt2nlyjessa.html

[O03] 加锁保护共享数据
来源：http://dali.ppjwa.cn/Article/details/gt2myinhpua.html

Py:   with lock: shared += 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2usdjjlyy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gzhubu.top/Article/details/gt2oauddrxl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.mhx1999.top/Article/details/gt2hzdvhmik.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gt2uwrkcqmu.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pjctmkrd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuanzhike.top/Article/details/gt2gxjacoao.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cashguo.top/Article/details/gt2fkjfjjve.html

C#:   lock (gate) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gt2adbejuuh.html

[O04] 定义异步函数并等待
来源：http://dali.hysaishi.cn/Article/details/gt2befublmi.html

Py:   async def f():⏎    await g()
来源：http://dali.yvedp.cn/Article/details/gt2xkeababi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shanyushiyangtech.top/Article/details/gt2znbgstrs.html

JS:   async function f() { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2tqxbgduk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hammf.cn/Article/details/gt2uvmypehh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nwbrower.top/Article/details/gt2enrimfzu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigufen.top/Article/details/gt2ssucwexd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.9152youxi.cn/Article/details/gt2gedjxwud.html

C#:   async Task F() { await G(); }
来源：http://dali.chenlongwang.top/Article/details/gt2vcnqlvcf.html

[O05] 并发执行并等待全部完成
来源：http://dali.redwolf501.top/Article/details/gt2fpjfzyvi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hammf.cn/Article/details/gt2adhufzvl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daria6918.cn/Article/details/gt2yfuvvrrz.html

JS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gt2fzxmvpzr.html

TS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gt2gngtlmky.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.mhx1999.top/Article/details/gt2bjumcgla.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shangyingyoupin.top/Article/details/gt2wxnckmpc.html

Ruby: threads.map(&:join)
来源：http://dali.zhixingplan.top/Article/details/gt2bhvbegev.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yueranfly.top/Article/details/gt2cuhbbuhg.html

[O06] 使用进程池
来源：http://dali.gzhubu.top/Article/details/gt2oypsqout.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gogol.net.cn/Article/details/gt2ezmvffyq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj20258888.top/Article/details/gt2gpdmhmzl.html

JS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gt2csrvmkju.html

TS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gt2ogmvexnn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yangfankeji.com/Article/details/gt2uebwqxcn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yvedp.cn/Article/details/gt2zmdzhddx.html

Ruby: // fork 块
来源：http://dali.meibo888.top/Article/details/gt2rmulxvrz.html

C#:   Parallel.For
来源：http://dali.smart0.xyz/Article/details/gt2myielcyw.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2pndxxeas.html

P. 常用工具函数
来源：http://dali.hywenlv.cn/Article/details/gt2laaayjlg.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2wqwyxazp.html

[P01] 生成 UUID
来源：http://dali.tianlin.xyz/Article/details/gt2fkuhppis.html

Py:   str(uuid.uuid4())
来源：http://dali.yongpay.top/Article/details/gt2msifjemr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ppjwa.cn/Article/details/gt2oaciiozd.html

JS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gt2wuyvdczh.html

TS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gt2jxwrsgwq.html

Java: UUID.randomUUID().toString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2whqhjcqc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.iojbl.cn/Article/details/gt2lxoslqov.html

Ruby: SecureRandom.uuid
来源：http://dali.snrcjt.cn/Article/details/gt2nbnalwql.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gzhubu.top/Article/details/gt2bydccwcg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangdashe.top/Article/details/gt2oonweiwk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pnibmcqb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.meibo888.top/Article/details/gt2wuuckhsn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daxiang520.top/Article/details/gt2oczdkmse.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hfpthk.cn/Article/details/gt2smjhfjfv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pycfn.com/Article/details/gt2hjmjrbms.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yonumen.top/Article/details/gt2qppyoogh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hammf.cn/Article/details/gt2jiswayis.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ievuikpw.html

[P03] 生成短随机字符串
来源：http://dali.zycfv.cn/Article/details/gt2aljtpzwq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sweek.top/Article/details/gt2aueqnuix.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.meibo888.top/Article/details/gt2pamljvrd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gt2dszletcd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wilhmdsa.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2ncntmldi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cucudq.cn/Article/details/gt2oakjvbhc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnxiangtu.top/Article/details/gt2dzbkagvp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gzhubu.top/Article/details/gt2tyupdtvc.html

[P04] 求长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eiepaxdf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cucudq.cn/Article/details/gt2ugtnqwoz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gt2rewpxvlu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zejeqnyp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258888.top/Article/details/gt2fensiosg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnqzz.top/Article/details/gt2vbxuvyej.html

Go:   len(arr);  len(m)
来源：http://dali.sweek.top/Article/details/gt2lzbgeamf.html

Ruby: x.length;  x.size
来源：http://dali.yvedp.cn/Article/details/gt2rqwhtvtc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gt2nhvftbam.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zycfv.cn/Article/details/gt2upkyqrtt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xinyue.icu/Article/details/gt2rwkebpyl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.wangdashe.top/Article/details/gt2vxwtixrk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cdnleiting.top/Article/details/gt2jbkhhyde.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hcwzssuu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dianchejie.cn/Article/details/gt2vmiwfozv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sxryk.cn/Article/details/gt2ygzcvvxh.html

Ruby: a == b
来源：http://dali.9152youxi.cn/Article/details/gt2gpzarsmf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ybcxt.top/Article/details/gt2zeqjlbji.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yvedp.cn/Article/details/gt2dndcdqsv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iakdmgkd.html

PHP:  if (empty($x)) {}
来源：http://dali.mhx1999.top/Article/details/gt2ivbachag.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yonumen.top/Article/details/gt2kfzfeaew.html

TS:   if (x == null) {}
来源：http://dali.zhengqikj.top/Article/details/gt2cdixahov.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gt2xgvgcrou.html

Go:   if x == nil {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2qoahrgqr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cwzltsrm.html

C#:   if (x is null) {}
来源：http://dali.yongpay.top/Article/details/gt2pjxkanbk.html

[P07] 防抖与节流
来源：http://dali.chenlongwang.top/Article/details/gt2hnkxrzyh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj20258.top/Article/details/gt2nzoqrmcw.html

PHP:  // 手写时间戳比较
来源：http://dali.cqqwz.cn/Article/details/gt2juhltuww.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gt2azngbfwi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.birdmap.top/Article/details/gt2bfmwlkwg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2edaohyle.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pengpengdd.cyou/Article/details/gt2mvnxiabj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.316326.xyz/Article/details/gt2amlvzgsj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fzhhl.top/Article/details/gt2mttofwot.html

[P08] 处理浮点精度问题
来源：http://dali.fzhhl.top/Article/details/gt2gspirxcf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xuanzx.com/Article/details/gt2nshntpxn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.smart0.xyz/Article/details/gt2hsxfsnea.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gavgoxov.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hbuwmhql.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sysykeji.top/Article/details/gt2byxukzgf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ydzc1.top/Article/details/gt2mjgrxchu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.haohaochexian.top/Article/details/gt2obdfngyf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.haohaochexian.top/Article/details/gt2jeraiuwh.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2nvggfxfe.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhoulong.xyz/Article/details/gt2amqggsxj.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2pqkjxfgo.html

[Q01] 创建表
来源：http://dali.sufxvd.cn/Article/details/gt2lywcmbvn.html

CREATE TABLE users (
来源：http://dali.sxryk.cn/Article/details/gt2xtltzywu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gt2biixxfde.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gt2wgckamxt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uffaglyb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jqgufenzy.top/Article/details/gt2fotamfzf.html

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ilcpjjdo.html

[Q02] 创建带外键的表
来源：http://dali.aibaodan.cn/Article/details/gt2ulxfrowi.html

CREATE TABLE orders (
来源：http://dali.andypj.xyz/Article/details/gt2aeuzkouy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yanxiufei.cn/Article/details/gt2goisyyas.html

user_id INT NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gt2yrlgcvsm.html

amount DECIMAL(10, 2),
来源：http://dali.gotoacloud.top/Article/details/gt2quxzgjrz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cdnleiting.top/Article/details/gt2ivnarbow.html

);
来源：http://dali.yanxiufei.cn/Article/details/gt2szhregoe.html

[Q03] 增加列
来源：http://dali.yonumen.top/Article/details/gt2zbavbenw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhongyouzk.top/Article/details/gt2grxypwbm.html

[Q04] 修改列类型
来源：http://dali.fengsongda.top/Article/details/gt2vtsiyamo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.svipenyu.cn/Article/details/gt2qlxrhprp.html

[Q05] 重命名列
来源：http://dali.ppjwa.cn/Article/details/gt2vtezuuaz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.316326.xyz/Article/details/gt2qpasdloq.html

[Q06] 删除列
来源：http://dali.cashguo.top/Article/details/gt2qupmpwsv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tian-w.cn/Article/details/gt2qlgklvpt.html

[Q07] 删除表
来源：http://dali.guannengcc.top/Article/details/gt2jxtdcauk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.andypj.xyz/Article/details/gt2phzuuhce.html

[Q08] 创建普通索引
来源：http://dali.gogol.net.cn/Article/details/gt2hdwtudgv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tanke756.top/Article/details/gt2mzjqbrgh.html

[Q09] 创建唯一索引
来源：http://dali.svipenyu.cn/Article/details/gt2pnqpedsy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cqqwz.cn/Article/details/gt2tqrtcvkm.html

[Q10] 插入单行
来源：http://dali.hnqzz.top/Article/details/gt2pwzknlwv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hysaishi.cn/Article/details/gt2vsfssioi.html

[Q11] 一次插入多行
来源：http://dali.316326.xyz/Article/details/gt2yjchbfmv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gt2rkxzxokw.html

[Q12] 插入后取自增 ID
来源：http://dali.cqqwz.cn/Article/details/gt2ixyyenpt.html


<!-- 参考信息 -->