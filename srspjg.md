代发 wailian999

Py:   if __name__ == "__main__":
来源：http://dali.zhiwuduotai.top/Article/details/gt2lrxxvyfb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hysaishi.cn/Article/details/gt2nnjuenfi.html

JS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mlwynpsl.html

TS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gt2efgkpjdl.html

Java: public static void main(String[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ukvowgei.html

Go:   func main()
来源：http://dali.aizwys.cn/Article/details/gt2zcmsxiam.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cheryme.top/Article/details/gt2dcpesxwz.html

C#:   static void Main(string[] args)
来源：http://dali.sxryk.cn/Article/details/gt2tqwjwiif.html

[M08] 获取系统与运行时信息
来源：http://dali.smart0.xyz/Article/details/gt2oowslqyk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuanzx.com/Article/details/gt2uzknnoak.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuanzx.com/Article/details/gt2qatxdadz.html

JS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gt2ghrmeczz.html

TS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gt2rpoeklpe.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yangfankeji.com/Article/details/gt2vutvkqov.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hywenlv.cn/Article/details/gt2fgdccfkx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.aibaodan.cn/Article/details/gt2phzmtvre.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guannengcc.top/Article/details/gt2qwllhkxo.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2rahbifad.html

N. 数据结构与算法
来源：http://dali.yueranfly.top/Article/details/gt2xmbutppm.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2ktjjwkyr.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qjwiewzc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2smkapwgh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gt2avsbiara.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gt2hevskwlg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gt2inoeexxu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gt2ozmhncqh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yongpay.top/Article/details/gt2pefiugex.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xziqi.cn/Article/details/gt2jjrvbpvz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2zqzutajn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenlongwang.top/Article/details/gt2bhtfhgnz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gt2enqgfpda.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxinkj.top/Article/details/gt2dzvmzexm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gt2sltdalcm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gt2rnvssovg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tanke756.top/Article/details/gt2kiuebszw.html

Go:   slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2grknuglr.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gt2gijgldgl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sysykeji.top/Article/details/gt2htvvgfxv.html

[N03] 快速排序（分治示例）
来源：http://dali.tanke756.top/Article/details/gt2bzzcukbg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hnxiangtu.top/Article/details/gt2xesqccws.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fengsongda.top/Article/details/gt2yuzqznmo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gt2gzbxuqol.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gt2jbligwae.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aizwys.cn/Article/details/gt2gfgellee.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wbnojovp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shangyingyoupin.top/Article/details/gt2roivafyb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.pengpengdd.cyou/Article/details/gt2iegeixzu.html

[N04] 斐波那契数列
来源：http://dali.gzhubu.top/Article/details/gt2otmgwkue.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.iojbl.cn/Article/details/gt2quraplnx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gt2jscluafx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2iiewcqku.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gt2uevopapz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.redwolf501.top/Article/details/gt2gmtwbcrw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ehwqpu.com/Article/details/gt2dkmbtykr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gt2pfjhjdhe.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gt2mlzceppy.html

[N05] 最大公约数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yghaknly.html

Py:   math.gcd(a, b)
来源：http://dali.yongpay.top/Article/details/gt2swznmfgd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2awvfmrqf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gt2fsqtepvu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gt2fokpddmu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gaohongyu789.top/Article/details/gt2xqqgvqbl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rgjsergw.html

Ruby: a.gcd(b)
来源：http://dali.tianlin.xyz/Article/details/gt2txabdxhl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenlongwang.top/Article/details/gt2wxfsyasa.html

[N06] 判断回文字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2tzatxtxz.html

Py:   s == s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gt2ztubcaga.html

PHP:  $s === strrev($s);
来源：http://dali.yongpay.top/Article/details/gt2loiqvlxc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qvmulkmt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2zzscbwzk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cdnleiting.top/Article/details/gt2qrxdnccf.html

Go:   // 双指针从两端比较
来源：http://dali.xinyue.icu/Article/details/gt2xlqwpfvc.html

Ruby: s == s.reverse
来源：http://dali.aibaodan.cn/Article/details/gt2vlatjhry.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gt2seuacafo.html

[N07] 两数之和（返回下标）
来源：http://dali.birdmap.top/Article/details/gt2swrwksqc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shzxlz.cn/Article/details/gt2gtsgzagn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gaohongyu789.top/Article/details/gt2fiyzmmlw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yanxiufei.cn/Article/details/gt2lmswxqbb.html

TS:   // 手写 Map<string, number>
来源：http://dali.sweek.top/Article/details/gt2zjlyntff.html

Java: // 手写 HashMap
来源：http://dali.mhx1999.top/Article/details/gt2jvoevhhb.html

Go:   // 手写 map[int]int
来源：http://dali.fengsongda.top/Article/details/gt2hxcozrlb.html

Ruby: // 手写 Hash
来源：http://dali.jqgfzy.top/Article/details/gt2aaetuggt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sweek.top/Article/details/gt2emwatdux.html

[N08] 生成全排列
来源：http://dali.havefunace.top/Article/details/gt2uktucwss.html

Py:   itertools.permutations(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2blkjyerb.html

PHP:  // 手写递归交换
来源：http://dali.daria6918.cn/Article/details/gt2zgaemtrv.html

JS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gt2esyrgwog.html

TS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gt2uuowqcth.html

Java: // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gt2wydazrev.html

Go:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gt2ilxefbeq.html

Ruby: arr.permutation.to_a
来源：http://dali.ppjwa.cn/Article/details/gt2pjzrxpqh.html

C#:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gt2hewddkdn.html

[N09] 栈与队列
来源：http://dali.sufxvd.cn/Article/details/gt2uemcxltk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shuidangran.top/Article/details/gt2cmyjtxwd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuanzx.com/Article/details/gt2xauhicsk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gt2llbsnvmb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gzhubu.top/Article/details/gt2tddwgofq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shzxlz.cn/Article/details/gt2abhduzlk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangtech.top/Article/details/gt2icukrymk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gt2weixymho.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.svipenyu.cn/Article/details/gt2ruatdhlx.html

[N10] 链表节点定义
来源：http://dali.mhx1999.top/Article/details/gt2cvzmaxjm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ydzc1.top/Article/details/gt2rvpsrtqk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vjuqgndt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.smart0.xyz/Article/details/gt2jcfebzhx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rhxtzemb.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nmrkhtzr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sweek.top/Article/details/gt2lhvzhket.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.haohaochexian.top/Article/details/gt2pwfzkczp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj202588.top/Article/details/gt2zxljlrvm.html

[N11] 二叉树中序遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2rtxwopuo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yuxming.cn/Article/details/gt2djmoudln.html

PHP:  // 手写递归函数
来源：http://dali.hammf.cn/Article/details/gt2pgbuknpv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gt2hlpxewql.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gt2upcvirmi.html

Java: // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gt2njsoekac.html

Go:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gt2htyhqove.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nanxinkj.top/Article/details/gt2puqhaumm.html

C#:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gt2urwkmdad.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ivvv.top/Article/details/gt2lpuqzuvk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hfpthk.cn/Article/details/gt2exvrxkhr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhoulong.xyz/Article/details/gt2gflacajy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gt2gzxtxidh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gt2hwpnxyap.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhiwuduotai.top/Article/details/gt2zgbnlskq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xinyue.icu/Article/details/gt2tvkaggaq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gzhubu.top/Article/details/gt2ztppvdlo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gt2epngzijh.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2ijakkvoi.html

O. 并发与异步
来源：http://dali.shuidangran.top/Article/details/gt2yyjkcmho.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2nujvcwgm.html

[O01] 启动一个线程
来源：http://dali.chenlongwang.top/Article/details/gt2hnkwwtyp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pycfn.com/Article/details/gt2ipgpnqeq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sweek.top/Article/details/gt2mewbmrwv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhongyouzk.top/Article/details/gt2djmzwtpn.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gt2utyntgua.html

Java: new Thread(() -> f()).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fssnstlw.html

Go:   go f()
来源：http://dali.fzhhl.top/Article/details/gt2lnhgqduf.html

Ruby: Thread.new { f }
来源：http://dali.yj202588.top/Article/details/gt2ktssxnxg.html

C#:   Task.Run(() => F());
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pymdgnlw.html

[O02] 使用线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2impnffin.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hfpthk.cn/Article/details/gt2ewiemzml.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hongshengwenyu.top/Article/details/gt2nwdnyqcp.html

JS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gt2nzluinbr.html

TS:   // worker_threads 线程池
来源：http://dali.ehwqpu.com/Article/details/gt2tchccobr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ptmjomfe.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.dianchejie.cn/Article/details/gt2muwgyzzm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.mhx1999.top/Article/details/gt2mhyclura.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhengqikj.top/Article/details/gt2rjcliswu.html

[O03] 加锁保护共享数据
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bajrfqpk.html

Py:   with lock: shared += 1
来源：http://dali.yj202588.top/Article/details/gt2vrkaondr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.meibo888.top/Article/details/gt2jcqpysyk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ehwqpu.com/Article/details/gt2xpnqdeog.html

TS:   // 同 JS
来源：http://dali.ehwqpu.com/Article/details/gt2cmsjwjet.html

Java: synchronized (this) { shared++; }
来源：http://dali.bjfxy.top/Article/details/gt2uxvpdvyh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenlongwang.top/Article/details/gt2ikurartn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hammf.cn/Article/details/gt2iydhbvie.html

C#:   lock (gate) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gt2plrjyxzi.html

[O04] 定义异步函数并等待
来源：http://dali.nwbrower.top/Article/details/gt2dpzvxihj.html

Py:   async def f():⏎    await g()
来源：http://dali.xuetiantiany.cn/Article/details/gt2sjbnlchq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258888.top/Article/details/gt2lhdejsut.html

JS:   async function f() { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gt2ufkkbtvf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.guannengcc.top/Article/details/gt2bsvdxuql.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.9152youxi.cn/Article/details/gt2noojretb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.birdmap.top/Article/details/gt2gmzrcrej.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ehwqpu.com/Article/details/gt2sjkqgugj.html

C#:   async Task F() { await G(); }
来源：http://dali.jiagoushi.top/Article/details/gt2lmsyytab.html

[O05] 并发执行并等待全部完成
来源：http://dali.hywenlv.cn/Article/details/gt2myilutxr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxrticdu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cqqwz.cn/Article/details/gt2gkdkucjs.html

JS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gt2ypsrukki.html

TS:   await Promise.all(tasks)
来源：http://dali.vqdsnc.cn/Article/details/gt2kgnfzywe.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yueranfly.top/Article/details/gt2tvontimm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.snrcjt.cn/Article/details/gt2phlodoko.html

Ruby: threads.map(&:join)
来源：http://dali.shuidangran.top/Article/details/gt2jfbfpzzp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sxryk.cn/Article/details/gt2broxyncr.html

[O06] 使用进程池
来源：http://dali.zhiwuduotai.top/Article/details/gt2hmyrwnlt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cdnleiting.top/Article/details/gt2mcczrljx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ehwqpu.com/Article/details/gt2iblxhfzf.html

JS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gt2pehzutjd.html

TS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gt2unfjsdqj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hammf.cn/Article/details/gt2zuvichaj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxinkj.top/Article/details/gt2uvndudht.html

Ruby: // fork 块
来源：http://dali.sysykeji.top/Article/details/gt2xwsteycc.html

C#:   Parallel.For
来源：http://dali.hnqzz.top/Article/details/gt2hxqsvclu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xeakfeua.html

P. 常用工具函数
来源：http://dali.aizwys.cn/Article/details/gt2efmkkhfc.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2cqzqzkiv.html

[P01] 生成 UUID
来源：http://dali.zycfv.cn/Article/details/gt2wfyogjfw.html

Py:   str(uuid.uuid4())
来源：http://dali.tanke756.top/Article/details/gt2qmdjxash.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khctzgia.html

JS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gt2eqgiacka.html

TS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gt2ykavqejn.html

Java: UUID.randomUUID().toString()
来源：http://dali.quarkkingdee.top/Article/details/gt2ywyvfsgb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fzhhl.top/Article/details/gt2kpryqnko.html

Ruby: SecureRandom.uuid
来源：http://dali.hfpthk.cn/Article/details/gt2gvprjacq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.fengsongda.top/Article/details/gt2lfhfvqcd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cucudq.cn/Article/details/gt2aypetgxo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.mhx1999.top/Article/details/gt2biibahzc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cqqwz.cn/Article/details/gt2zxsyuiyl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cqqwz.cn/Article/details/gt2roxljrqf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yangfankeji.com/Article/details/gt2qobselmi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ybcxt.top/Article/details/gt2luxqdsgs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rshsbxrf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cheryme.top/Article/details/gt2sdfnodvs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.fengsongda.top/Article/details/gt2luwzcedp.html

[P03] 生成短随机字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2jfvlohtw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cheryme.top/Article/details/gt2xdtqhibx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2htwdjnob.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guannengcc.top/Article/details/gt2hpiatihs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gt2kuaagfjm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.smart0.xyz/Article/details/gt2mfajweod.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dianchejie.cn/Article/details/gt2tygwhiad.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xziqi.cn/Article/details/gt2dkfnotmw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yonumen.top/Article/details/gt2jshzknmm.html

[P04] 求长度
来源：http://dali.vqdsnc.cn/Article/details/gt2pwgpzuxb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tanke756.top/Article/details/gt2afiieulx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gt2ewbcwelt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gt2kvxsfech.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gt2pskdshrk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hysaishi.cn/Article/details/gt2hkhvzebn.html

Go:   len(arr);  len(m)
来源：http://dali.redwolf501.top/Article/details/gt2eccunioe.html

Ruby: x.length;  x.size
来源：http://dali.zhengqikj.top/Article/details/gt2biahdger.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zycfv.cn/Article/details/gt2rbkyxyoi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.iojbl.cn/Article/details/gt2mapftmur.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cdnleiting.top/Article/details/gt2abxkticx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hnqzz.top/Article/details/gt2vgvswsgn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ppjwa.cn/Article/details/gt2pumerlaw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.smart0.xyz/Article/details/gt2xehuozbh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guannengcc.top/Article/details/gt2tfwqfddz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ehwqpu.com/Article/details/gt2wstajjdd.html

Ruby: a == b
来源：http://dali.shangyingyoupin.top/Article/details/gt2jbsqczvb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cheryme.top/Article/details/gt2ydwxgilz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cheryme.top/Article/details/gt2hbkciprt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.daxiang520.top/Article/details/gt2yflusfpc.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gt2zjltflfs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dianchejie.cn/Article/details/gt2qqftkiie.html

TS:   if (x == null) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2cvlidqka.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gt2washuzqn.html

Go:   if x == nil {}
来源：http://dali.sweek.top/Article/details/gt2vioublly.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cqqwz.cn/Article/details/gt2ohdcaprx.html

C#:   if (x is null) {}
来源：http://dali.dashuyun.cn/Article/details/gt2tvwsypgf.html

[P07] 防抖与节流
来源：http://dali.jyoumei.cn/Article/details/gt2ovsbaxxd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.316326.xyz/Article/details/gt2dzpmspqk.html

PHP:  // 手写时间戳比较
来源：http://dali.c1oappe.top/Article/details/gt2ptrbchyu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gt2rhnptcbv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigfzy.top/Article/details/gt2nvruxhkt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgfzy.top/Article/details/gt2kdhkynyk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pftrhred.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.andypj.xyz/Article/details/gt2lfenkfyo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.dianchejie.cn/Article/details/gt2wdwwjwrj.html

[P08] 处理浮点精度问题
来源：http://dali.yonumen.top/Article/details/gt2cmyfhtvh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fengsongda.top/Article/details/gt2hfoiswvl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.aibaodan.cn/Article/details/gt2etlzjcfi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pengpengdd.cyou/Article/details/gt2emskuzkf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.meibo888.top/Article/details/gt2leaugaqs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuanzx.com/Article/details/gt2pbbxlfyg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xuetiantiany.cn/Article/details/gt2zhhjbdkb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jqgfzy.top/Article/details/gt2dplummus.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.wangdashe.top/Article/details/gt2odborrsa.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2ltoiiwry.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yvedp.cn/Article/details/gt2nxamwpkn.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2hqjqniur.html

[Q01] 创建表
来源：http://dali.hfpthk.cn/Article/details/gt2nubmcvzf.html

CREATE TABLE users (
来源：http://dali.jinqigfzy.top/Article/details/gt2zaphllrj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pengpengdd.cyou/Article/details/gt2fswspdig.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xylfe.cn/Article/details/gt2slgkalmy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yueranfly.top/Article/details/gt2teaqfnmz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.c1oappe.top/Article/details/gt2pipqsxwt.html

);
来源：http://dali.cucudq.cn/Article/details/gt2xaycpdwt.html

[Q02] 创建带外键的表
来源：http://dali.9152youxi.cn/Article/details/gt2fzwkqdib.html

CREATE TABLE orders (
来源：http://dali.zdqjudy.top/Article/details/gt2zpfyjvci.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shuidangran.top/Article/details/gt2joqswcbb.html

user_id INT NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gt2ejfpmubi.html

amount DECIMAL(10, 2),
来源：http://dali.cqqwz.cn/Article/details/gt2drewdtlj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zdqjudy.top/Article/details/gt2wtmtlsfs.html

);
来源：http://dali.daria6918.cn/Article/details/gt2fjhrcodn.html

[Q03] 增加列
来源：http://dali.zdqjudy.top/Article/details/gt2usiqrqji.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xinyue.icu/Article/details/gt2siildswp.html

[Q04] 修改列类型
来源：http://dali.sweek.top/Article/details/gt2oikdreij.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yueranfly.top/Article/details/gt2qgntqvmk.html

[Q05] 重命名列
来源：http://dali.ybcxt.top/Article/details/gt2odnntqrg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daxiang520.top/Article/details/gt2arsypbkm.html

[Q06] 删除列
来源：http://dali.yongpay.top/Article/details/gt2qegqxzbh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xziqi.cn/Article/details/gt2mqnzkhis.html

[Q07] 删除表
来源：http://dali.xinyue.icu/Article/details/gt2ictxyust.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daxiang520.top/Article/details/gt2gmkfvzoy.html

[Q08] 创建普通索引
来源：http://dali.yj202588.top/Article/details/gt2vmifufsl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gt2eejxwgkq.html

[Q09] 创建唯一索引
来源：http://dali.jinqigufen.top/Article/details/gt2ibpdbrbv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gt2mkokhghu.html

[Q10] 插入单行
来源：http://dali.vqdsnc.cn/Article/details/gt2vmtfhnip.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xziqi.cn/Article/details/gt2kxofkeoc.html

[Q11] 一次插入多行
来源：http://dali.jinqigfzy.top/Article/details/gt2brsqckgz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.316326.xyz/Article/details/gt2fkyxdirv.html

[Q12] 插入后取自增 ID
来源：http://dali.nwbrower.top/Article/details/gt2lcnycrqc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.iojbl.cn/Article/details/gt2ytjalseh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yongpay.top/Article/details/gt2wxbzjrni.html

[Q13] 忽略重复插入
来源：http://dali.hammf.cn/Article/details/gt2rfhjpdrt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hywenlv.cn/Article/details/gt2gpjxuqfn.html


<!-- 参考信息 -->