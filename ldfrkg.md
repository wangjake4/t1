代发 wailian999

Java: public static void main(String[] args)
来源：http://dali.xuanzx.com/Article/details/gtscxypfop.html

Go:   func main()
来源：http://dali.hysaishi.cn/Article/details/gtgqizgicb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gogol.net.cn/Article/details/gtfuwtevma.html

C#:   static void Main(string[] args)
来源：http://dali.xuanzx.com/Article/details/gtymwlltyf.html

[M08] 获取系统与运行时信息
来源：http://dali.shzxlz.cn/Article/details/gtifnqpbov.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenjidiqi.icu/Article/details/gthzlyapsq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangshuangyany.cn/Article/details/gtocafbnos.html

JS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gtmiueyqht.html

TS:   process.platform;  process.version
来源：http://dali.andypj.xyz/Article/details/gtbhoenqwz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258.top/Article/details/gtkzvtpwbl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ehwqpu.com/Article/details/gtrfgjcxmg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.quarkkingdee.top/Article/details/gtgkbdqtdt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgufenzy.top/Article/details/gtisbwyetj.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtsjmmnrtg.html

N. 数据结构与算法
来源：http://dali.yj20258888.top/Article/details/gtokkwgvur.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtpfjlphrv.html

[N01] 二分查找（有序数组）
来源：http://dali.xinyue.icu/Article/details/gtammsykfm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtcoinkkap.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwegieojk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gtzljflasz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gtucdmbojp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtpwhjfofg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtdavjonod.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yanxiufei.cn/Article/details/gtfefaeuhy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtfkafisni.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangdashe.top/Article/details/gtbsaswfwu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gtqbfofsdf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gogol.net.cn/Article/details/gtjfnhvmfy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gtldazefkv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtjwndqwqw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxinkj.top/Article/details/gtvrjxbudn.html

Go:   slices.Sort(arr)
来源：http://dali.gzhubu.top/Article/details/gtpuhfvusf.html

Ruby: arr.sort
来源：http://dali.chenlongwang.top/Article/details/gtjybpalvn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.mhx1999.top/Article/details/gtnpbvmklv.html

[N03] 快速排序（分治示例）
来源：http://dali.ydzc1.top/Article/details/gtolaocsmj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.mhx1999.top/Article/details/gtrdxnyckf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.havefunace.top/Article/details/gtdsxtpjdy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gtvobmnkrt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gtzxjmypbd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258.top/Article/details/gtwsyidkmq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.316326.xyz/Article/details/gtlpchwipk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.snrcjt.cn/Article/details/gtabnwxzjd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gaohongyu789.top/Article/details/gtcxkpublf.html

[N04] 斐波那契数列
来源：http://dali.yangfankeji.com/Article/details/gtppwigmmi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cucudq.cn/Article/details/gtzwidipct.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gtogecgray.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtqseopmsq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtlysqifem.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrsdwqnge.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ppjwa.cn/Article/details/gtbrdwivfq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gtsfbkwtfv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gtbqcqbpcb.html

[N05] 最大公约数
来源：http://dali.fzhhl.top/Article/details/gthnlujyya.html

Py:   math.gcd(a, b)
来源：http://dali.mhx1999.top/Article/details/gtjwsflfji.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxinkj.top/Article/details/gthlfotjsx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pycfn.com/Article/details/gtqlpbaxul.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxinkj.top/Article/details/gtdreaocip.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenzaomai.com/Article/details/gtxamfwnlf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sufxvd.cn/Article/details/gtgufrexpp.html

Ruby: a.gcd(b)
来源：http://dali.yongpay.top/Article/details/gtmfulfpzs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tanke756.top/Article/details/gtmzhwbteb.html

[N06] 判断回文字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoimvyynv.html

Py:   s == s[::-1]
来源：http://dali.cucudq.cn/Article/details/gtapdmhjrp.html

PHP:  $s === strrev($s);
来源：http://dali.tian-w.cn/Article/details/gtoynzgzak.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtuwqbckxs.html

TS:   s === [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gthuqenlxx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shuidangran.top/Article/details/gtxkqmrktu.html

Go:   // 双指针从两端比较
来源：http://dali.9152youxi.cn/Article/details/gtemraiois.html

Ruby: s == s.reverse
来源：http://dali.c1oappe.top/Article/details/gthtyxxavu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gtpuavrhhl.html

[N07] 两数之和（返回下标）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmoyohhc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yuanzhike.top/Article/details/gttmhmiyvq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.vqdsnc.cn/Article/details/gtuikcqscn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ivvv.top/Article/details/gtuqyzaybx.html

TS:   // 手写 Map<string, number>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavjxeagd.html

Java: // 手写 HashMap
来源：http://dali.gaohongyu789.top/Article/details/gtvovctbsv.html

Go:   // 手写 map[int]int
来源：http://dali.ehwqpu.com/Article/details/gtnewzxtpf.html

Ruby: // 手写 Hash
来源：http://dali.pycfn.com/Article/details/gtwruijmmm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.svipenyu.cn/Article/details/gtjzymtshk.html

[N08] 生成全排列
来源：http://dali.hysaishi.cn/Article/details/gtahaasnjh.html

Py:   itertools.permutations(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqajlymv.html

PHP:  // 手写递归交换
来源：http://dali.nanxuanxn.top/Article/details/gtfgzzbrwn.html

JS:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtueejdvgr.html

TS:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtcjkizfvt.html

Java: // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtfshxswhc.html

Go:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtgwpixlru.html

Ruby: arr.permutation.to_a
来源：http://dali.mhx1999.top/Article/details/gtyxksvztz.html

C#:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtxruacxdv.html

[N09] 栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gtvophbzej.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnxiangtu.top/Article/details/gteglgdiiq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtxnvhpqys.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskbrulnm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cheryme.top/Article/details/gtmknajade.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpjhoory.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.guowangkeji.top/Article/details/gtcytxbnro.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtqegeycms.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhruffal.html

[N10] 链表节点定义
来源：http://dali.tanke756.top/Article/details/gtzbxwmcgn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.kuanghao11.cn/Article/details/gtxjaurcec.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuanzhike.top/Article/details/gtajonwqjb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzaopbmrx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zycfv.cn/Article/details/gtlocgqfqb.html

Java: class Node { int v; Node next; }
来源：http://dali.iojbl.cn/Article/details/gtkteglvny.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tanke756.top/Article/details/gtfwilciuo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhengqikj.top/Article/details/gtpvavhikd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jianghu66.top/Article/details/gtdpfiptwj.html

[N11] 二叉树中序遍历
来源：http://dali.aizwys.cn/Article/details/gtxkwwfjhm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhixingplan.top/Article/details/gtnswxnvks.html

PHP:  // 手写递归函数
来源：http://dali.9152youxi.cn/Article/details/gtskntsfne.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gtbhcjyyxz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gtzovoxgub.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gtrdcwvcig.html

Go:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtlglajvco.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangshuangyany.cn/Article/details/gthslodktg.html

C#:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gthvthtvih.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yongpay.top/Article/details/gtouyzghyt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nanxuanxn.top/Article/details/gtnvyvvtne.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sxryk.cn/Article/details/gtrxnxvrap.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gtvbtdlvix.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guowangkeji.top/Article/details/gthlvyxtbq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gtupwglvdg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvnrtsyk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sysykeji.top/Article/details/gtxdyiczxw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gtjimjwwik.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtzrypznnp.html

O. 并发与异步
来源：http://dali.9152youxi.cn/Article/details/gtfsdioxca.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtmmtgjnxk.html

[O01] 启动一个线程
来源：http://dali.birdmap.top/Article/details/gtazjcmvis.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sysykeji.top/Article/details/gttjysdbya.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hfpthk.cn/Article/details/gtebykkrtg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tanke756.top/Article/details/gtpgdsolhf.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gttafcuptm.html

Java: new Thread(() -> f()).start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmvlwjkn.html

Go:   go f()
来源：http://dali.hysaishi.cn/Article/details/gtarcotqyw.html

Ruby: Thread.new { f }
来源：http://dali.guowangkeji.top/Article/details/gtkzmiqfcw.html

C#:   Task.Run(() => F());
来源：http://dali.xuanzx.com/Article/details/gtiakquymu.html

[O02] 使用线程池
来源：http://dali.jqgfzy.top/Article/details/gtquiolpor.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hammf.cn/Article/details/gtjndhemfi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yongpay.top/Article/details/gtraykhdqh.html

JS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gtohphcpvd.html

TS:   // worker_threads 线程池
来源：http://dali.redwolf501.top/Article/details/gtyqwosxsw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gogol.net.cn/Article/details/gtmdofiknc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xziqi.cn/Article/details/gtdzyoggoy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgufenzy.top/Article/details/gtirnhqnjg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258888.top/Article/details/gtxwwmzsmq.html

[O03] 加锁保护共享数据
来源：http://dali.aizwys.cn/Article/details/gtfagqdvqf.html

Py:   with lock: shared += 1
来源：http://dali.gotoacloud.top/Article/details/gtiulltjcu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.316326.xyz/Article/details/gthvygamgm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.aizwys.cn/Article/details/gtvzeqrtrf.html

TS:   // 同 JS
来源：http://dali.yanxiufei.cn/Article/details/gtffzblhsu.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtitzhxtxi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenzaomai.com/Article/details/gtofbljcim.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenlongwang.top/Article/details/gtftmdacup.html

C#:   lock (gate) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gtwjsexlbl.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258.top/Article/details/gtotgibqxi.html

Py:   async def f():⏎    await g()
来源：http://dali.yanxiufei.cn/Article/details/gtwqxdsknx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daxiang520.top/Article/details/gtntnucugk.html

JS:   async function f() { await g(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwysghsdc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xziqi.cn/Article/details/gtybgwybmw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinghuilouyu.cn/Article/details/gtoricrwjn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shangyingyoupin.top/Article/details/gtpvuhqzdc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shuidangran.top/Article/details/gtlytonspy.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgfzy.top/Article/details/gtxtqeosxh.html

[O05] 并发执行并等待全部完成
来源：http://dali.yuanzhike.top/Article/details/gtlzwfxkxx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ybcxt.top/Article/details/gteljibnjf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj20258888.top/Article/details/gtimznvcph.html

JS:   await Promise.all(tasks)
来源：http://dali.yj20258.top/Article/details/gtfukoukss.html

TS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gtohiffvql.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sysykeji.top/Article/details/gtnnzzsomk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.smart0.xyz/Article/details/gthqjqmeki.html

Ruby: threads.map(&:join)
来源：http://dali.smart0.xyz/Article/details/gtlfbpfnky.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yonumen.top/Article/details/gtiqssygiu.html

[O06] 使用进程池
来源：http://dali.fzhhl.top/Article/details/gtboziamcj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.quarkkingdee.top/Article/details/gtywuzucmn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zycfv.cn/Article/details/gtbokpdgdh.html

JS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gtnunstncx.html

TS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gtkclqlauv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zdqjudy.top/Article/details/gtzkruvlen.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.0kj1m.cn/Article/details/gtgrvbbvjm.html

Ruby: // fork 块
来源：http://dali.zhixingplan.top/Article/details/gtovfmvxqn.html

C#:   Parallel.For
来源：http://dali.dashuyun.cn/Article/details/gtkfgktnoc.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtktjntltr.html

P. 常用工具函数
来源：http://dali.jinqigfzy.top/Article/details/gttysltsak.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtvfmmaoyc.html

[P01] 生成 UUID
来源：http://dali.daxiang520.top/Article/details/gtdegkwgqm.html

Py:   str(uuid.uuid4())
来源：http://dali.0kj1m.cn/Article/details/gtrrztvybx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xziqi.cn/Article/details/gtsgzetqmb.html

JS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gtwllfixsf.html

TS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowntvilk.html

Java: UUID.randomUUID().toString()
来源：http://dali.ybcxt.top/Article/details/gtdmjtxrjq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yongpay.top/Article/details/gtbypglzid.html

Ruby: SecureRandom.uuid
来源：http://dali.yonumen.top/Article/details/gtudgfjify.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.316326.xyz/Article/details/gtqwrdpyhs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gogol.net.cn/Article/details/gtdqhhnjdj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xinyue.icu/Article/details/gtsvjqwkmc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtishxiwds.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.0kj1m.cn/Article/details/gtvdvcscnj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.pycfn.com/Article/details/gtlngshihr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jqgfzy.top/Article/details/gtnpotvxda.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhiwuduotai.top/Article/details/gtqbezhbja.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.snrcjt.cn/Article/details/gtsrvjfzrw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ivvv.top/Article/details/gtqudbaesg.html

[P03] 生成短随机字符串
来源：http://dali.shzxlz.cn/Article/details/gtdzkmktnm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tian-w.cn/Article/details/gtfblhvqji.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sysykeji.top/Article/details/gtstayolre.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtlfgunpob.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gtglpxgoje.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuanzhike.top/Article/details/gtwvhfmgac.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cashguo.top/Article/details/gtrspmjjoi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jqgfzy.top/Article/details/gtrphnzjha.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guannengcc.top/Article/details/gtjtmgnltj.html

[P04] 求长度
来源：http://dali.hywenlv.cn/Article/details/gtastswafz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.316326.xyz/Article/details/gtreutgvjr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtmofdypdu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gtfizzwbtf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fzhhl.top/Article/details/gtlrdlvinb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yangfankeji.com/Article/details/gtautlvoxb.html

Go:   len(arr);  len(m)
来源：http://dali.tian-w.cn/Article/details/gtpmrqwwew.html

Ruby: x.length;  x.size
来源：http://dali.ydzc1.top/Article/details/gtjedsbokh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.redwolf501.top/Article/details/gtanjqdiuu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xylfe.cn/Article/details/gtqrrpprof.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sxryk.cn/Article/details/gtzuubtged.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.meibo888.top/Article/details/gtpzmbatnj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yonumen.top/Article/details/gtgjusshzi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnqzz.top/Article/details/gtilwsaddm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yueranfly.top/Article/details/gtizaxvhwj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtnxfkixhq.html

Ruby: a == b
来源：http://dali.9152youxi.cn/Article/details/gtnynvtwmj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.iojbl.cn/Article/details/gtemfvsqri.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.9152youxi.cn/Article/details/gtfvejxvcu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jiagoushi.top/Article/details/gtlnttqgxv.html

PHP:  if (empty($x)) {}
来源：http://dali.yanxiufei.cn/Article/details/gtwoltxlkg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guowangkeji.top/Article/details/gtukvtkgoo.html

TS:   if (x == null) {}
来源：http://dali.gogol.net.cn/Article/details/gtylezcbrv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtjtrduo.html

Go:   if x == nil {}
来源：http://dali.cashguo.top/Article/details/gtgqmbetna.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cheryme.top/Article/details/gtiqjlcbrp.html

C#:   if (x is null) {}
来源：http://dali.yongpay.top/Article/details/gthapsrlhp.html

[P07] 防抖与节流
来源：http://dali.yj20258888.top/Article/details/gtyyrsrvqd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tianlin.xyz/Article/details/gtrbgejlah.html

PHP:  // 手写时间戳比较
来源：http://dali.xuanzx.com/Article/details/gtkvfdyzfg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gtptecqkjc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gtgnvllppv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtxqtirpjd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pycfn.com/Article/details/gtlxwjcwtd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jlsjyb.cn/Article/details/gtgtconxyq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gtterfdebd.html

[P08] 处理浮点精度问题
来源：http://dali.yj202588.top/Article/details/gtipoiwmtu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sweek.top/Article/details/gttqblgyqs.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.smart0.xyz/Article/details/gtjrowscrn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jqgfzy.top/Article/details/gtdlyqyhez.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gtmikjmiza.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.316326.xyz/Article/details/gtlpodfuaj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sufxvd.cn/Article/details/gttjofyyba.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hfpthk.cn/Article/details/gtwzbvpjgo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xziqi.cn/Article/details/gtrxcxrszn.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtjehwjjir.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zycfv.cn/Article/details/gtlgkzwqwf.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtktfmyweq.html

[Q01] 创建表
来源：http://dali.ehwqpu.com/Article/details/gtfphfopfi.html

CREATE TABLE users (
来源：http://dali.yj202588.top/Article/details/gtnrftepbd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gtiavonqio.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ybcxt.top/Article/details/gtduhfrepj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhiwuduotai.top/Article/details/gteoaaenab.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258.top/Article/details/gtloamjiju.html

);
来源：http://dali.daria6918.cn/Article/details/gtxwdjsczw.html

[Q02] 创建带外键的表
来源：http://dali.zdqjudy.top/Article/details/gtatwdgdvu.html

CREATE TABLE orders (
来源：http://dali.snrcjt.cn/Article/details/gtdccehzyt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhixingplan.top/Article/details/gtngukplhm.html

user_id INT NOT NULL,
来源：http://dali.hnxiangtu.top/Article/details/gtwkmjoqhc.html

amount DECIMAL(10, 2),
来源：http://dali.wangshuangyany.cn/Article/details/gttqtdbofb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nwbrower.top/Article/details/gtszmhfkxo.html

);
来源：http://dali.havefunace.top/Article/details/gtueucgivl.html

[Q03] 增加列
来源：http://dali.jiagoushi.top/Article/details/gtidnonkgu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gotoacloud.top/Article/details/gtwgypvyco.html

[Q04] 修改列类型
来源：http://dali.smart0.xyz/Article/details/gteanulgoo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj202588.top/Article/details/gtdbpsnxav.html

[Q05] 重命名列
来源：http://dali.zhoulong.xyz/Article/details/gtmpccbtre.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cdnleiting.top/Article/details/gtxxzbzxcj.html

[Q06] 删除列
来源：http://dali.tanke756.top/Article/details/gttkzspnbt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fzhhl.top/Article/details/gtccmkksnf.html

[Q07] 删除表
来源：http://dali.chenzaomai.com/Article/details/gtpwdxelyg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.andypj.xyz/Article/details/gtuoztggvr.html

[Q08] 创建普通索引
来源：http://dali.guannengcc.top/Article/details/gtgmdyaytb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenjidiqi.icu/Article/details/gtfsathozn.html

[Q09] 创建唯一索引
来源：http://dali.yuanzhike.top/Article/details/gtmpgligem.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zdqjudy.top/Article/details/gtqpusjxpx.html

[Q10] 插入单行
来源：http://dali.jinghuilouyu.cn/Article/details/gtufztasxl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gtcortgdza.html

[Q11] 一次插入多行
来源：http://dali.aibaodan.cn/Article/details/gtrizhzwtu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fzhhl.top/Article/details/gtjoujnsag.html

[Q12] 插入后取自增 ID
来源：http://dali.bjfxy.top/Article/details/gtojoizmym.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnqzz.top/Article/details/gtrusducve.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenlongwang.top/Article/details/gtrirmbmtc.html

[Q13] 忽略重复插入
来源：http://dali.chenzaomai.com/Article/details/gtrqbiziko.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.bjfxy.top/Article/details/gtkyookyue.html

[Q14] 存在则更新（upsert）
来源：http://dali.guowangkeji.top/Article/details/gtychsyeys.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sysykeji.top/Article/details/gtbcypcncl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwslyqjdk.html

[Q15] 查询全部
来源：http://dali.cashguo.top/Article/details/gtuznbsthr.html


<!-- 参考信息 -->