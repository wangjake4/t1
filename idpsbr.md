代发 wailian999

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2rirmemqg.html

Ruby: warn "err"
来源：http://dali.jinqigufen.top/Article/details/gt2ftrzovfp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.dianchejie.cn/Article/details/gt2zhpophzd.html

[M07] 判断是否为主入口
来源：http://dali.dianchejie.cn/Article/details/gt2pnhewaqq.html

Py:   if __name__ == "__main__":
来源：http://dali.redwolf501.top/Article/details/gt2ymvcrmuz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2jspunokk.html

JS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gt2hhvzhcll.html

TS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gt2ioqvzmfj.html

Java: public static void main(String[] args)
来源：http://dali.aizwys.cn/Article/details/gt2tvhttdiq.html

Go:   func main()
来源：http://dali.zdqjudy.top/Article/details/gt2vadvnxen.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hywenlv.cn/Article/details/gt2wawfqsxe.html

C#:   static void Main(string[] args)
来源：http://dali.quarkkingdee.top/Article/details/gt2rkhotwyu.html

[M08] 获取系统与运行时信息
来源：http://dali.jianghu66.top/Article/details/gt2zrmqwzah.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zdqjudy.top/Article/details/gt2smmzjaig.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangdashe.top/Article/details/gt2nenkxola.html

JS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gt2vqhzvdnw.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2pfllqiaw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shzxlz.cn/Article/details/gt2apcsofzt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuanzx.com/Article/details/gt2smhosxsb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ueoimcpv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnqzz.top/Article/details/gt2bledwiwf.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2osuxihtk.html

N. 数据结构与算法
来源：http://dali.haohaochexian.top/Article/details/gt2xfbyijtl.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2otbnkiwf.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigufen.top/Article/details/gt2yzvjnzqf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2krnxeeeg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangdashe.top/Article/details/gt2ncognnln.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnqzz.top/Article/details/gt2nexiurqg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gt2ueolhmvl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2qfxjfows.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2odgrtwck.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tianlin.xyz/Article/details/gt2hvqjaivj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2vhkzwlxt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gogol.net.cn/Article/details/gt2docaahbe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gt2zlfxgmlc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.0kj1m.cn/Article/details/gt2urndjryf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gt2elansbxj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gt2mrqbjosy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.bjfxy.top/Article/details/gt2jeqpnqss.html

Go:   slices.Sort(arr)
来源：http://dali.bjfxy.top/Article/details/gt2wajfmzlm.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gt2hcorhkna.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yvedp.cn/Article/details/gt2glgvokgq.html

[N03] 快速排序（分治示例）
来源：http://dali.hammf.cn/Article/details/gt2znodlkun.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nanxuanxn.top/Article/details/gt2mtbbqqox.html

PHP:  // 递归实现，或用 usort
来源：http://dali.dianchejie.cn/Article/details/gt2qrhmesfa.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gt2zhzjtcxb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gt2agpxchax.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hysaishi.cn/Article/details/gt2fdpwfeze.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aizwys.cn/Article/details/gt2cdxhagmi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gotoacloud.top/Article/details/gt2pwriwoae.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cheryme.top/Article/details/gt2oulooqkx.html

[N04] 斐波那契数列
来源：http://dali.zhongyouzk.top/Article/details/gt2yfrazagd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gt2cqbscipt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xinyue.icu/Article/details/gt2mqeztrvu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gt2dgeiefgz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gt2wbcftorx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yongpay.top/Article/details/gt2uaoibuqx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2bainrato.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gt2upxxyimk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gt2jhinroiv.html

[N05] 最大公约数
来源：http://dali.yongpay.top/Article/details/gt2tjiauhxs.html

Py:   math.gcd(a, b)
来源：http://dali.guannengcc.top/Article/details/gt2dlqfphwz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.andypj.xyz/Article/details/gt2fbiykqao.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gt2rmljyqff.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gt2gfiixdjd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxuanxn.top/Article/details/gt2zbdyjgxi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.quarkkingdee.top/Article/details/gt2wwqfljre.html

Ruby: a.gcd(b)
来源：http://dali.nwbrower.top/Article/details/gt2iemfpgjz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yangfankeji.com/Article/details/gt2konwbstv.html

[N06] 判断回文字符串
来源：http://dali.mhx1999.top/Article/details/gt2sjvtbhyx.html

Py:   s == s[::-1]
来源：http://dali.yj20258888.top/Article/details/gt2lyvwyzpp.html

PHP:  $s === strrev($s);
来源：http://dali.xziqi.cn/Article/details/gt2tztsvkkb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2mvrtyfuu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2oyyvgsah.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhengqikj.top/Article/details/gt2cvejedcg.html

Go:   // 双指针从两端比较
来源：http://dali.sufxvd.cn/Article/details/gt2tvijjdiw.html

Ruby: s == s.reverse
来源：http://dali.zhongyouzk.top/Article/details/gt2dmlbuykt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gt2mqgudqlp.html

[N07] 两数之和（返回下标）
来源：http://dali.guowangkeji.top/Article/details/gt2plxqlnvz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sufxvd.cn/Article/details/gt2jkmmyabv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jyoumei.cn/Article/details/gt2ehffcagb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.316326.xyz/Article/details/gt2mleoiowa.html

TS:   // 手写 Map<string, number>
来源：http://dali.kuanghao11.cn/Article/details/gt2avdsbgcd.html

Java: // 手写 HashMap
来源：http://dali.kuanghao11.cn/Article/details/gt2ewwoxfuv.html

Go:   // 手写 map[int]int
来源：http://dali.dianchejie.cn/Article/details/gt2dyibntyd.html

Ruby: // 手写 Hash
来源：http://dali.dashuyun.cn/Article/details/gt2xliajlcc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dvmagfcm.html

[N08] 生成全排列
来源：http://dali.mhx1999.top/Article/details/gt2jtsdivcw.html

Py:   itertools.permutations(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2krcyhgfy.html

PHP:  // 手写递归交换
来源：http://dali.svipenyu.cn/Article/details/gt2jxncqytz.html

JS:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gt2imogtyqw.html

TS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2eogzynfq.html

Java: // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gt2kyozrrpx.html

Go:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gt2kocagfjn.html

Ruby: arr.permutation.to_a
来源：http://dali.iojbl.cn/Article/details/gt2bqizrxbl.html

C#:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gt2vmhqvutg.html

[N09] 栈与队列
来源：http://dali.tian-w.cn/Article/details/gt2fnryxqvw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yanxiufei.cn/Article/details/gt2bgdfhkud.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gt2twkxhvaj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.aizwys.cn/Article/details/gt2bixdsbtt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xylfe.cn/Article/details/gt2rameshyr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gotoacloud.top/Article/details/gt2pxbyffyq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.feifeiyinyue.top/Article/details/gt2vrvzjlva.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gt2hluwpiva.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ybcxt.top/Article/details/gt2ceiezuwo.html

[N10] 链表节点定义
来源：http://dali.nwbrower.top/Article/details/gt2wpiluxxl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cheryme.top/Article/details/gt2utpesbmy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xylfe.cn/Article/details/gt2vykqplzh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tanke756.top/Article/details/gt2enaicotx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hongshengwenyu.top/Article/details/gt2icytboan.html

Java: class Node { int v; Node next; }
来源：http://dali.ydzc1.top/Article/details/gt2fglwdobc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.9152youxi.cn/Article/details/gt2troqaehk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.fengsongda.top/Article/details/gt2asxckjic.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gzhubu.top/Article/details/gt2biwxmrdv.html

[N11] 二叉树中序遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2xzzxxquy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.svipenyu.cn/Article/details/gt2hlaumyya.html

PHP:  // 手写递归函数
来源：http://dali.yonumen.top/Article/details/gt2waopjlzc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ehwqpu.com/Article/details/gt2mhapghxs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenlongwang.top/Article/details/gt2hdfykxtk.html

Java: // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fpfgrjsf.html

Go:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gt2hcxplety.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xziqi.cn/Article/details/gt2ixrvehyh.html

C#:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2xzgnvnyi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhixingplan.top/Article/details/gt2benscvla.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qmvzwswh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yueranfly.top/Article/details/gt2aoytqhkl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hysaishi.cn/Article/details/gt2dsojoovz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cucudq.cn/Article/details/gt2ksqgploe.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gt2rautjleh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zycfv.cn/Article/details/gt2glwhkgfd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2szfenpag.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.redwolf501.top/Article/details/gt2qdibqlig.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2dkjthfpk.html

O. 并发与异步
来源：http://dali.quarkkingdee.top/Article/details/gt2krfvdfnf.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2nvjnkkao.html

[O01] 启动一个线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2usmxskke.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhixingplan.top/Article/details/gt2krcwnjri.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2gatodftr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cashguo.top/Article/details/gt2wacjngno.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gt2hqdjifio.html

Java: new Thread(() -> f()).start()
来源：http://dali.zycfv.cn/Article/details/gt2yvjeowqc.html

Go:   go f()
来源：http://dali.nwbrower.top/Article/details/gt2eneynzvz.html

Ruby: Thread.new { f }
来源：http://dali.cqqwz.cn/Article/details/gt2puussvxn.html

C#:   Task.Run(() => F());
来源：http://dali.yongpay.top/Article/details/gt2sfucured.html

[O02] 使用线程池
来源：http://dali.fengsongda.top/Article/details/gt2fnigdmbi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lmoapibk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daria6918.cn/Article/details/gt2vagbwbiu.html

JS:   // worker_threads 线程池
来源：http://dali.zhiwuduotai.top/Article/details/gt2wrvudqoz.html

TS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gt2cjcyeqnh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ppjwa.cn/Article/details/gt2cyykhukr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ubpowuec.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2atqeepkp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.andypj.xyz/Article/details/gt2xbyvtdbg.html

[O03] 加锁保护共享数据
来源：http://dali.tanke756.top/Article/details/gt2buusxcsv.html

Py:   with lock: shared += 1
来源：http://dali.yj202588.top/Article/details/gt2sehcqpun.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhengqikj.top/Article/details/gt2gosxzrru.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hfpthk.cn/Article/details/gt2umaqnfbu.html

TS:   // 同 JS
来源：http://dali.meibo888.top/Article/details/gt2iyrvqphu.html

Java: synchronized (this) { shared++; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2crwdcghm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yongpay.top/Article/details/gt2cdqubffy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpluiktl.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gt2xdhfjeib.html

[O04] 定义异步函数并等待
来源：http://dali.yj202588.top/Article/details/gt2typvkspj.html

Py:   async def f():⏎    await g()
来源：http://dali.yvedp.cn/Article/details/gt2iyxprilo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258.top/Article/details/gt2ecqtacyj.html

JS:   async function f() { await g(); }
来源：http://dali.guannengcc.top/Article/details/gt2jowmhobr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xziqi.cn/Article/details/gt2prmhmbaz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nanxinkj.top/Article/details/gt2gbouuymu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigufen.top/Article/details/gt2zlrborby.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenlongwang.top/Article/details/gt2dkcoyduw.html

C#:   async Task F() { await G(); }
来源：http://dali.sxryk.cn/Article/details/gt2jbhuruej.html

[O05] 并发执行并等待全部完成
来源：http://dali.iojbl.cn/Article/details/gt2rwdycjhj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yonumen.top/Article/details/gt2nzdoiouc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jyoumei.cn/Article/details/gt2goyrsodb.html

JS:   await Promise.all(tasks)
来源：http://dali.yueranfly.top/Article/details/gt2spszciuu.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gt2gttgddgr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.aizwys.cn/Article/details/gt2fcfsuguu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daria6918.cn/Article/details/gt2necqokbz.html

Ruby: threads.map(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gt2gnynzitx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.316326.xyz/Article/details/gt2cnvzqnml.html

[O06] 使用进程池
来源：http://dali.yonumen.top/Article/details/gt2mzgqjpwc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daria6918.cn/Article/details/gt2mrqqpzsk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hfpthk.cn/Article/details/gt2hqczxnoc.html

JS:   // child_process / cluster 模块
来源：http://dali.nanxuanxn.top/Article/details/gt2pvhhfndc.html

TS:   // child_process / cluster 模块
来源：http://dali.tian-w.cn/Article/details/gt2mhiuhemm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258888.top/Article/details/gt2lhaibdef.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.havefunace.top/Article/details/gt2pnslvbqn.html

Ruby: // fork 块
来源：http://dali.cashguo.top/Article/details/gt2idobqlky.html

C#:   Parallel.For
来源：http://dali.gaohongyu789.top/Article/details/gt2liclvfdu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2bnoaifee.html

P. 常用工具函数
来源：http://dali.fzhhl.top/Article/details/gt2oyuzemaq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2xxrbyshs.html

[P01] 生成 UUID
来源：http://dali.mhx1999.top/Article/details/gt2qbqloefc.html

Py:   str(uuid.uuid4())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pkrcbbtu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.snrcjt.cn/Article/details/gt2lazynmky.html

JS:   crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gt2kyfhgdug.html

TS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gt2axmfkxme.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tdwvifos.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hywenlv.cn/Article/details/gt2qwovuhpr.html

Ruby: SecureRandom.uuid
来源：http://dali.andypj.xyz/Article/details/gt2kvlcadbo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shzxlz.cn/Article/details/gt2jitfkjvq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zycfv.cn/Article/details/gt2ytborhiq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sufxvd.cn/Article/details/gt2jwzsgdql.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.meibo888.top/Article/details/gt2flzxlttc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kfdirppj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jianghu66.top/Article/details/gt2zocwqkog.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258.top/Article/details/gt2udwjwecs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yueranfly.top/Article/details/gt2exoqawib.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.9152youxi.cn/Article/details/gt2lqxtllqd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenjidiqi.icu/Article/details/gt2cizpommj.html

[P03] 生成短随机字符串
来源：http://dali.gotoacloud.top/Article/details/gt2jrizmbsd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhixingplan.top/Article/details/gt2spuqjcgd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tanke756.top/Article/details/gt2olhjhnyq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenzaomai.com/Article/details/gt2zjqccfdy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lzkvudfd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cdnleiting.top/Article/details/gt2opgcbztf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hfpthk.cn/Article/details/gt2yaqgaewz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.andypj.xyz/Article/details/gt2ymalvoxa.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hscrgovc.html

[P04] 求长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qchnbuxs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shangyingyoupin.top/Article/details/gt2osfneymm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gt2obartniq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gt2owqcxsxs.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gt2kswomskj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ydzc1.top/Article/details/gt2wqbueayt.html

Go:   len(arr);  len(m)
来源：http://dali.gaohongyu789.top/Article/details/gt2uzjgbhdg.html

Ruby: x.length;  x.size
来源：http://dali.chenjidiqi.icu/Article/details/gt2sfctzbum.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cucudq.cn/Article/details/gt2psdlnavg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ybcxt.top/Article/details/gt2djgfssnx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhixingplan.top/Article/details/gt2ddisozae.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.kuanghao11.cn/Article/details/gt2fxzkhdbz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.iojbl.cn/Article/details/gt2jcebijmi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.andypj.xyz/Article/details/gt2lwuvsrei.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guannengcc.top/Article/details/gt2dqpokuvl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ehwqpu.com/Article/details/gt2ljuyqfmz.html

Ruby: a == b
来源：http://dali.yvedp.cn/Article/details/gt2xyhasals.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gzhubu.top/Article/details/gt2fksqrnsf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nwbrower.top/Article/details/gt2qusyaywk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hnxiangtu.top/Article/details/gt2wybmlswh.html

PHP:  if (empty($x)) {}
来源：http://dali.havefunace.top/Article/details/gt2giiibjxc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2upcdbhxl.html

TS:   if (x == null) {}
来源：http://dali.nanxinkj.top/Article/details/gt2zmjvdafj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gt2upofqlyi.html

Go:   if x == nil {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kagaucqw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhongyouzk.top/Article/details/gt2bfeuynfx.html

C#:   if (x is null) {}
来源：http://dali.birdmap.top/Article/details/gt2rvojidlk.html

[P07] 防抖与节流
来源：http://dali.xuetiantiany.cn/Article/details/gt2ozncslcn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hysaishi.cn/Article/details/gt2cdjcbyoa.html

PHP:  // 手写时间戳比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qvcnbkat.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gt2whmzyqop.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuvpxhg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qwouchpr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.aibaodan.cn/Article/details/gt2jyybiixd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.quarkkingdee.top/Article/details/gt2umcqdnmn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.316326.xyz/Article/details/gt2dkzannez.html

[P08] 处理浮点精度问题
来源：http://dali.daxiang520.top/Article/details/gt2mdoucvpr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ehwqpu.com/Article/details/gt2whezrqao.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tian-w.cn/Article/details/gt2jddhvtdo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhengqikj.top/Article/details/gt2gqjridch.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gt2epaqdtrl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fengsongda.top/Article/details/gt2xdlpuszp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cdnleiting.top/Article/details/gt2mfavecgp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.316326.xyz/Article/details/gt2dtwmfeko.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tianlin.xyz/Article/details/gt2vwkjvxhp.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2iosdtzlw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.tanke756.top/Article/details/gt2upppaxwr.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2ttltvplj.html

[Q01] 创建表
来源：http://dali.snrcjt.cn/Article/details/gt2krorpvdw.html

CREATE TABLE users (
来源：http://dali.xylfe.cn/Article/details/gt2hbhvtput.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wtelnmlz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gt2habwhcxo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yonumen.top/Article/details/gt2sjhsbche.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cheryme.top/Article/details/gt2orcsmzzl.html

);
来源：http://dali.iojbl.cn/Article/details/gt2tfadxhkz.html

[Q02] 创建带外键的表
来源：http://dali.shangyingyoupin.top/Article/details/gt2weuxgodn.html

CREATE TABLE orders (
来源：http://dali.jqgufenzy.top/Article/details/gt2lyfdlsqv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xylfe.cn/Article/details/gt2nsxsyafl.html

user_id INT NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gt2wdnrzeua.html

amount DECIMAL(10, 2),
来源：http://dali.redwolf501.top/Article/details/gt2kmlwsqpi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iqyhbutp.html

);
来源：http://dali.quarkkingdee.top/Article/details/gt2vsihedjz.html

[Q03] 增加列
来源：http://dali.cqqwz.cn/Article/details/gt2hftscfwp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.quarkkingdee.top/Article/details/gt2wkmidqcc.html

[Q04] 修改列类型
来源：http://dali.mhx1999.top/Article/details/gt2cjdebiax.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daria6918.cn/Article/details/gt2fppewsaf.html

[Q05] 重命名列
来源：http://dali.tianlin.xyz/Article/details/gt2blsxvgyl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ksjrsxqg.html

[Q06] 删除列
来源：http://dali.kuanghao11.cn/Article/details/gt2dyxcgetg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj20258888.top/Article/details/gt2rqaxflzs.html

[Q07] 删除表
来源：http://dali.redwolf501.top/Article/details/gt2uwveotmk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2hiilqrxq.html

[Q08] 创建普通索引
来源：http://dali.meibo888.top/Article/details/gt2prtnmegb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nwbrower.top/Article/details/gt2bxbeqtvl.html

[Q09] 创建唯一索引
来源：http://dali.hongshengwenyu.top/Article/details/gt2qpgftjsu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gt2lmycdtmm.html

[Q10] 插入单行
来源：http://dali.zhixingplan.top/Article/details/gt2skglzceo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zdmdskiu.html

[Q11] 一次插入多行
来源：http://dali.haohaochexian.top/Article/details/gt2usohbagq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jyoumei.cn/Article/details/gt2jntcemrp.html

[Q12] 插入后取自增 ID
来源：http://dali.wangdashe.top/Article/details/gt2mdkxwkgp.html


<!-- 参考信息 -->