代发 wailian999

Ruby: exit 1
来源：http://dali.dianchejie.cn/Article/details/gt2xzvzifgw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhixingplan.top/Article/details/gt2nyipjegc.html

[M06] 向标准错误输出
来源：http://dali.cqqwz.cn/Article/details/gt2dwdmaoed.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhoulong.xyz/Article/details/gt2fosaerbx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.snrcjt.cn/Article/details/gt2zwxgxnzx.html

JS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gt2mwfjvqkr.html

TS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2pfohbqrr.html

Java: System.err.println("err")
来源：http://dali.jqgfzy.top/Article/details/gt2rxzmczja.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gotoacloud.top/Article/details/gt2twtnvogw.html

Ruby: warn "err"
来源：http://dali.jinqigfzy.top/Article/details/gt2bxylbguh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.dashuyun.cn/Article/details/gt2mgyjhcip.html

[M07] 判断是否为主入口
来源：http://dali.tianlin.xyz/Article/details/gt2clfuxekg.html

Py:   if __name__ == "__main__":
来源：http://dali.zhixingplan.top/Article/details/gt2nexoivat.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.mhx1999.top/Article/details/gt2lxtddcob.html

JS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gt2nenxbiwq.html

TS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gt2wnibxvmu.html

Java: public static void main(String[] args)
来源：http://dali.nanxinkj.top/Article/details/gt2ctebvdbj.html

Go:   func main()
来源：http://dali.ydzc1.top/Article/details/gt2ywqsepae.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.andypj.xyz/Article/details/gt2ryjsidxz.html

C#:   static void Main(string[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wvkigcte.html

[M08] 获取系统与运行时信息
来源：http://dali.svipenyu.cn/Article/details/gt2khilshxp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.haohaochexian.top/Article/details/gt2bnejgtje.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zycfv.cn/Article/details/gt2ifwlkchc.html

JS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gt2xrgbyxod.html

TS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mzlryjbi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenzaomai.com/Article/details/gt2wsusmicp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tian-w.cn/Article/details/gt2zkdgplex.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnqzz.top/Article/details/gt2ixjvcvgu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guannengcc.top/Article/details/gt2hpdqvsnr.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2zhuznwas.html

N. 数据结构与算法
来源：http://dali.quarkkingdee.top/Article/details/gt2inlntnpk.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2mqflarhp.html

[N01] 二分查找（有序数组）
来源：http://dali.xuetiantiany.cn/Article/details/gt2jaaesitw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2wdcmzkzz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gt2egiejbqh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ifyjjddm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gt2fvxrjsdt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2dgcupouv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2qcoyvyjm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shzxlz.cn/Article/details/gt2ymoozdhc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2fxeitohc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kcldluox.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dwyvpwlq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zdqjudy.top/Article/details/gt2tprtugcz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gt2locvnikc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gt2rfxcxuod.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nwbrower.top/Article/details/gt2sutprmbx.html

Go:   slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gt2zexajask.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gt2knnnljtt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuetiantiany.cn/Article/details/gt2dpoavryt.html

[N03] 快速排序（分治示例）
来源：http://dali.tianlin.xyz/Article/details/gt2kvzgtyzr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nanxuanxn.top/Article/details/gt2kbygehao.html

PHP:  // 递归实现，或用 usort
来源：http://dali.kuanghao11.cn/Article/details/gt2sitnsbbp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gt2wnxtaspf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gt2xvtlhoyo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xziqi.cn/Article/details/gt2zmmsqzmf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yvedp.cn/Article/details/gt2ztgywkby.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigufen.top/Article/details/gt2sslndghr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.c1oappe.top/Article/details/gt2lerthflc.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nwehxjpn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gt2uphesljz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gt2snnbwzcz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gt2jpnyjkgg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2wdcnmcke.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sxryk.cn/Article/details/gt2iiquqqfq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhoulong.xyz/Article/details/gt2abucrkoz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hywenlv.cn/Article/details/gt2jvyubpzx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gt2cdxwjflo.html

[N05] 最大公约数
来源：http://dali.xuanzx.com/Article/details/gt2giebohco.html

Py:   math.gcd(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gt2ozxaafmh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj202588.top/Article/details/gt2xgblzqja.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnqzz.top/Article/details/gt2snhxpbld.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gt2npqsltal.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ivvv.top/Article/details/gt2tjhrhprf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guowangkeji.top/Article/details/gt2fslqjamx.html

Ruby: a.gcd(b)
来源：http://dali.andypj.xyz/Article/details/gt2gtcbzsok.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sysykeji.top/Article/details/gt2ysyfnmkn.html

[N06] 判断回文字符串
来源：http://dali.tianlin.xyz/Article/details/gt2rwgqbvmh.html

Py:   s == s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gt2sinpkkph.html

PHP:  $s === strrev($s);
来源：http://dali.meibo888.top/Article/details/gt2lgmmrmcf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gt2hlyahecq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gt2xcorvrqz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sweek.top/Article/details/gt2lpxbmirz.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uttzwqvx.html

Ruby: s == s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gt2gszbmvva.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gt2ykispirh.html

[N07] 两数之和（返回下标）
来源：http://dali.ydzc1.top/Article/details/gt2fayhbnwf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guannengcc.top/Article/details/gt2rgbnexof.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhiwuduotai.top/Article/details/gt2tqtzyshw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yonumen.top/Article/details/gt2kqcxitib.html

TS:   // 手写 Map<string, number>
来源：http://dali.hfpthk.cn/Article/details/gt2gqjkkusk.html

Java: // 手写 HashMap
来源：http://dali.sufxvd.cn/Article/details/gt2msqewxqi.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258888.top/Article/details/gt2ovltylmo.html

Ruby: // 手写 Hash
来源：http://dali.yuxming.cn/Article/details/gt2safgxwqu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenjidiqi.icu/Article/details/gt2gqdjpyqf.html

[N08] 生成全排列
来源：http://dali.chenlongwang.top/Article/details/gt2jmvjpewk.html

Py:   itertools.permutations(arr)
来源：http://dali.cucudq.cn/Article/details/gt2wnaccjpv.html

PHP:  // 手写递归交换
来源：http://dali.yangfankeji.com/Article/details/gt2mqsvkgir.html

JS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2gslcnwaf.html

TS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2frrvbsgu.html

Java: // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gt2zllgmfob.html

Go:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gt2dkcdtszq.html

Ruby: arr.permutation.to_a
来源：http://dali.yangfankeji.com/Article/details/gt2dddelfev.html

C#:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2xjovevxo.html

[N09] 栈与队列
来源：http://dali.yj202588.top/Article/details/gt2sgagrmwe.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sysykeji.top/Article/details/gt2ckgdakya.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2trrqvauc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gt2iorjzbfj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigfzy.top/Article/details/gt2iirytixe.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ivvv.top/Article/details/gt2nnpaxrsb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hongshengwenyu.top/Article/details/gt2bwovofan.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gt2krbfeyyh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.mhx1999.top/Article/details/gt2ciukkntx.html

[N10] 链表节点定义
来源：http://dali.chenjidiqi.icu/Article/details/gt2usvqwbys.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nanxuanxn.top/Article/details/gt2xuftbeej.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sxryk.cn/Article/details/gt2aauoxexo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cqqwz.cn/Article/details/gt2rmohwhjh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hywenlv.cn/Article/details/gt2ulhvfxto.html

Java: class Node { int v; Node next; }
来源：http://dali.meibo888.top/Article/details/gt2ouufflma.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sxryk.cn/Article/details/gt2tqbbgprl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenzaomai.com/Article/details/gt2htjskuma.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.316326.xyz/Article/details/gt2xmmmddkz.html

[N11] 二叉树中序遍历
来源：http://dali.cdnleiting.top/Article/details/gt2ykezepho.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guowangkeji.top/Article/details/gt2cnxmxbip.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtrrokf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gt2obvjefwe.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.c1oappe.top/Article/details/gt2nhtztzfu.html

Java: // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gt2mqqnyvas.html

Go:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gt2nptlkgrc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tswivhxe.html

C#:   // 手写递归
来源：http://dali.redwolf501.top/Article/details/gt2zvohtqcs.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xylfe.cn/Article/details/gt2vwsannkl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrdqrxd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenzaomai.com/Article/details/gt2fvxqdrhe.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.9152youxi.cn/Article/details/gt2flkknmit.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gt2womqcruv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gt2tlapdzrj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daxiang520.top/Article/details/gt2xoxvjgfx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yonumen.top/Article/details/gt2sldrpamg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gt2wsiflcqp.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2axoxpqux.html

O. 并发与异步
来源：http://dali.jinqigufen.top/Article/details/gt2adlzjrtg.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2vasffmzg.html

[O01] 启动一个线程
来源：http://dali.sysykeji.top/Article/details/gt2cnhsxzaa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.havefunace.top/Article/details/gt2chzcrcoo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yueranfly.top/Article/details/gt2lrutlsxt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj202588.top/Article/details/gt2uduiovgg.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gt2jyojpxza.html

Java: new Thread(() -> f()).start()
来源：http://dali.tanke756.top/Article/details/gt2vllzyrjk.html

Go:   go f()
来源：http://dali.yvedp.cn/Article/details/gt2gcpgzueo.html

Ruby: Thread.new { f }
来源：http://dali.pycfn.com/Article/details/gt2skoknjaj.html

C#:   Task.Run(() => F());
来源：http://dali.cqqwz.cn/Article/details/gt2wsmksfxo.html

[O02] 使用线程池
来源：http://dali.pycfn.com/Article/details/gt2hbwgutex.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigfzy.top/Article/details/gt2trrosomx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ahslxljb.html

JS:   // worker_threads 线程池
来源：http://dali.snrcjt.cn/Article/details/gt2aiyempyf.html

TS:   // worker_threads 线程池
来源：http://dali.zhixingplan.top/Article/details/gt2jqiedrwq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jyoumei.cn/Article/details/gt2veytuerw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sweek.top/Article/details/gt2rqrlyykk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.kuanghao11.cn/Article/details/gt2sajbfpvi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.quarkkingdee.top/Article/details/gt2sfwlodjw.html

[O03] 加锁保护共享数据
来源：http://dali.daria6918.cn/Article/details/gt2bbjrfyrn.html

Py:   with lock: shared += 1
来源：http://dali.jiagoushi.top/Article/details/gt2myuwsfjf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.daxiang520.top/Article/details/gt2elcrdvfr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pycfn.com/Article/details/gt2zyfmrhxs.html

TS:   // 同 JS
来源：http://dali.ivvv.top/Article/details/gt2nocalejq.html

Java: synchronized (this) { shared++; }
来源：http://dali.pycfn.com/Article/details/gt2lrecpplm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zycfv.cn/Article/details/gt2pitualha.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxinkj.top/Article/details/gt2rmaznlrr.html

C#:   lock (gate) { shared++; }
来源：http://dali.cashguo.top/Article/details/gt2unpdlqhs.html

[O04] 定义异步函数并等待
来源：http://dali.jqgfzy.top/Article/details/gt2efikqwph.html

Py:   async def f():⏎    await g()
来源：http://dali.0kj1m.cn/Article/details/gt2smmtczap.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.316326.xyz/Article/details/gt2uuvxtrjn.html

JS:   async function f() { await g(); }
来源：http://dali.zdqjudy.top/Article/details/gt2bnarxgap.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gzhubu.top/Article/details/gt2rqfuhsiq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yueranfly.top/Article/details/gt2xojfxsal.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zdqjudy.top/Article/details/gt2fvtpgnlm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.bjfxy.top/Article/details/gt2nkctwmnz.html

C#:   async Task F() { await G(); }
来源：http://dali.daria6918.cn/Article/details/gt2doffvsgf.html

[O05] 并发执行并等待全部完成
来源：http://dali.nanxuanxn.top/Article/details/gt2phxaqvtw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sysykeji.top/Article/details/gt2annayzrt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.smart0.xyz/Article/details/gt2eavgzwur.html

JS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gt2jhnoqfpt.html

TS:   await Promise.all(tasks)
来源：http://dali.yvedp.cn/Article/details/gt2tyeinbgg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xylfe.cn/Article/details/gt2ncctytvj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dashuyun.cn/Article/details/gt2habnlina.html

Ruby: threads.map(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tjtsdtxe.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jxmogkco.html

[O06] 使用进程池
来源：http://dali.hongshengwenyu.top/Article/details/gt2bnmhmvtf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.pengpengdd.cyou/Article/details/gt2nhqgnzrs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hywenlv.cn/Article/details/gt2wvxuadgx.html

JS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gt2clfxmuuy.html

TS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gt2xbbcctjc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cashguo.top/Article/details/gt2tcpnwohv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258888.top/Article/details/gt2uyhtgpjo.html

Ruby: // fork 块
来源：http://dali.vqdsnc.cn/Article/details/gt2ywcvprhi.html

C#:   Parallel.For
来源：http://dali.yonumen.top/Article/details/gt2qbhvdafb.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pagmgeop.html

P. 常用工具函数
来源：http://dali.gotoacloud.top/Article/details/gt2mfwthokd.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2hxjkdfjw.html

[P01] 生成 UUID
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tgbbsels.html

Py:   str(uuid.uuid4())
来源：http://dali.feifeiyinyue.top/Article/details/gt2mrgivdri.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xinyue.icu/Article/details/gt2vjauekld.html

JS:   crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gt2yyebpinp.html

TS:   crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gt2vpjbltkw.html

Java: UUID.randomUUID().toString()
来源：http://dali.snrcjt.cn/Article/details/gt2xgokvgus.html

Go:   // 用 github.com/google/uuid
来源：http://dali.c1oappe.top/Article/details/gt2vyejobfp.html

Ruby: SecureRandom.uuid
来源：http://dali.hongshengwenyu.top/Article/details/gt2evfiscaq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.daxiang520.top/Article/details/gt2mobnxoam.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigufen.top/Article/details/gt2qjwdutyh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zdqjudy.top/Article/details/gt2ojfmwcwb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.guannengcc.top/Article/details/gt2jwordpfs.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yangfankeji.com/Article/details/gt2nkjeorsb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuanzx.com/Article/details/gt2xfofunrf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gzhubu.top/Article/details/gt2aiypqwol.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jianghu66.top/Article/details/gt2rqjtjcgw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnmftfiw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tianlin.xyz/Article/details/gt2rtxtklye.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gt2szjfvgpf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.andypj.xyz/Article/details/gt2stykkhdg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shzxlz.cn/Article/details/gt2coitymic.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gt2hafabrmd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gt2fttjkhuk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.9152youxi.cn/Article/details/gt2gthuyavc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnxiangtu.top/Article/details/gt2eotqmvfx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cdnleiting.top/Article/details/gt2gzvijihh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigufen.top/Article/details/gt2mydokean.html

[P04] 求长度
来源：http://dali.birdmap.top/Article/details/gt2julqvtnd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.meibo888.top/Article/details/gt2oyvnbtiy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gt2mfwargan.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cashguo.top/Article/details/gt2wsdjzszt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gt2vdjmpxku.html

Java: list.size();  map.size();  s.length()
来源：http://dali.fzhhl.top/Article/details/gt2ttpywrpc.html

Go:   len(arr);  len(m)
来源：http://dali.wangdashe.top/Article/details/gt2fpfqkjrc.html

Ruby: x.length;  x.size
来源：http://dali.daxiang520.top/Article/details/gt2wwtrawpe.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cheryme.top/Article/details/gt2yjixmqrp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xuanzx.com/Article/details/gt2irfjmrtk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pengpengdd.cyou/Article/details/gt2swzxbxto.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.mhx1999.top/Article/details/gt2jgmmwvpu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgfzy.top/Article/details/gt2vhebtwka.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aqbvojzj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zdqjudy.top/Article/details/gt2wxqkzrdq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ivvv.top/Article/details/gt2nguhmtwl.html

Ruby: a == b
来源：http://dali.nwbrower.top/Article/details/gt2verfhklz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.kuanghao11.cn/Article/details/gt2bczbhkjb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhengqikj.top/Article/details/gt2nggfzswi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.guowangkeji.top/Article/details/gt2ojqwhtmm.html

PHP:  if (empty($x)) {}
来源：http://dali.hammf.cn/Article/details/gt2blfavjzn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgufenzy.top/Article/details/gt2fdepkexq.html

TS:   if (x == null) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2knugbgjl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gt2virvgrxl.html

Go:   if x == nil {}
来源：http://dali.redwolf501.top/Article/details/gt2iwpjsfmi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.daxiang520.top/Article/details/gt2yhqqoshe.html

C#:   if (x is null) {}
来源：http://dali.haohaochexian.top/Article/details/gt2gardfsvg.html

[P07] 防抖与节流
来源：http://dali.sxryk.cn/Article/details/gt2etdmrabg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cashguo.top/Article/details/gt2dugquxqb.html

PHP:  // 手写时间戳比较
来源：http://dali.meibo888.top/Article/details/gt2pijxncxf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gt2byezrtja.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gt2mdjtaxop.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.c1oappe.top/Article/details/gt2odppvnsv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pycfn.com/Article/details/gt2uhkkhfvd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jqgfzy.top/Article/details/gt2axnnjaqk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nvujmhhg.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2cahkcwar.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.guowangkeji.top/Article/details/gt2tsdhovta.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.snrcjt.cn/Article/details/gt2lpjilkcz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hongshengwenyu.top/Article/details/gt2tgflcgxd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jlsjyb.cn/Article/details/gt2obldoxdp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qkqzuxvk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.guowangkeji.top/Article/details/gt2fgueoqxv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xinyue.icu/Article/details/gt2gqlffkgs.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yueranfly.top/Article/details/gt2zchjptkp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hxypdoff.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nojkslxw.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2nxorvizo.html

[Q01] 创建表
来源：http://dali.jlsjyb.cn/Article/details/gt2deocomfk.html

CREATE TABLE users (
来源：http://dali.hongshengwenyu.top/Article/details/gt2tmxnqwtd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuanzx.com/Article/details/gt2mpdbliaf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nanxuanxn.top/Article/details/gt2yynzfbbd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gbhnygie.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yueranfly.top/Article/details/gt2xtswttgf.html

);
来源：http://dali.wangdashe.top/Article/details/gt2ryxxnoyp.html

[Q02] 创建带外键的表
来源：http://dali.tanke756.top/Article/details/gt2oixtnplh.html

CREATE TABLE orders (
来源：http://dali.sufxvd.cn/Article/details/gt2oatvfwts.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sweek.top/Article/details/gt2xfbsiauo.html

user_id INT NOT NULL,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ntixgvml.html

amount DECIMAL(10, 2),
来源：http://dali.shuidangran.top/Article/details/gt2tqipufgp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cucudq.cn/Article/details/gt2yqvzbuqy.html

);
来源：http://dali.ybcxt.top/Article/details/gt2uruyaxft.html

[Q03] 增加列
来源：http://dali.xziqi.cn/Article/details/gt2vchbddya.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhiwuduotai.top/Article/details/gt2xzmxbhut.html

[Q04] 修改列类型
来源：http://dali.yj20258888.top/Article/details/gt2nehouorb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenlongwang.top/Article/details/gt2qrwyawwz.html

[Q05] 重命名列
来源：http://dali.aizwys.cn/Article/details/gt2tfgjkuoq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdjryoz.html

[Q06] 删除列
来源：http://dali.ppjwa.cn/Article/details/gt2wmuerzfb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhiwuduotai.top/Article/details/gt2jwxgcras.html

[Q07] 删除表
来源：http://dali.sufxvd.cn/Article/details/gt2fxkrmfri.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hywenlv.cn/Article/details/gt2gmxjalzo.html

[Q08] 创建普通索引
来源：http://dali.andypj.xyz/Article/details/gt2kljrllek.html


<!-- 参考信息 -->