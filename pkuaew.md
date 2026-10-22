代发 wailian999

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuanzx.com/Article/details/gtdxqjeoni.html

Ruby: warn "err"
来源：http://dali.havefunace.top/Article/details/gthfnbfpib.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.birdmap.top/Article/details/gtjcweoqjl.html

[M07] 判断是否为主入口
来源：http://dali.0kj1m.cn/Article/details/gtwqmwwadh.html

Py:   if __name__ == "__main__":
来源：http://dali.yonumen.top/Article/details/gtrkhdebex.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sysykeji.top/Article/details/gtwuvvvypn.html

JS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gtvjkucxwg.html

TS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gttddcfdaf.html

Java: public static void main(String[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gtpxnwiole.html

Go:   func main()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxirnyno.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ybcxt.top/Article/details/gtaiahhyis.html

C#:   static void Main(string[] args)
来源：http://dali.shuidangran.top/Article/details/gtltvnitpl.html

[M08] 获取系统与运行时信息
来源：http://dali.havefunace.top/Article/details/gtaalijfvq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dianchejie.cn/Article/details/gtsjsvdqcd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fengsongda.top/Article/details/gtvoikfshk.html

JS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gthuqqzfkq.html

TS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtkkhwnsio.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dianchejie.cn/Article/details/gtqfzlyzsx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ivvv.top/Article/details/gtkqwnqdhp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pycfn.com/Article/details/gtbgxpshcj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.snrcjt.cn/Article/details/gtiwtradra.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtojaynkck.html

N. 数据结构与算法
来源：http://dali.jinqigfzy.top/Article/details/gttqfqnapj.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtolgyxwnj.html

[N01] 二分查找（有序数组）
来源：http://dali.andypj.xyz/Article/details/gtnphodcvh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtsqeortvm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtomrfizii.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gtupkforbv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtqpemehgf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtehqkqotv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtzoaldqte.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.smart0.xyz/Article/details/gtzvcwnizb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtwtfnexsn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daxiang520.top/Article/details/gtsvalkshn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gtiuxxhurl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tian-w.cn/Article/details/gthcmqbtst.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtnqdkapca.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gtgxnvpehh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gtqwisvmkt.html

Go:   slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtgxahhxov.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gtnmbzzkse.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gzhubu.top/Article/details/gtvhzmzwfm.html

[N03] 快速排序（分治示例）
来源：http://dali.fengsongda.top/Article/details/gtjapfztdb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daria6918.cn/Article/details/gtyvadzyjd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.andypj.xyz/Article/details/gtaawacfbr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwovyybw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gtghpbonnk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daria6918.cn/Article/details/gtrifsjxvc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nanxuanxn.top/Article/details/gtupmrttby.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.redwolf501.top/Article/details/gtauceaphp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zycfv.cn/Article/details/gtvoumbdbq.html

[N04] 斐波那契数列
来源：http://dali.andypj.xyz/Article/details/gtedkkzavt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gtrigvehzb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gtkcgdyuvl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gtlyjigswr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwomwscw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hysaishi.cn/Article/details/gtssvprwbj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hongshengwenyu.top/Article/details/gttcktfcsi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gtncvqzwgy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtjxdllmjt.html

[N05] 最大公约数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdscztmf.html

Py:   math.gcd(a, b)
来源：http://dali.gzhubu.top/Article/details/gtqgplwgpl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hywenlv.cn/Article/details/gtvlizkldc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnqzz.top/Article/details/gtsfeyekti.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gtvhbvpkvr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhengqikj.top/Article/details/gtbyoyxizc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sufxvd.cn/Article/details/gtispumhio.html

Ruby: a.gcd(b)
来源：http://dali.316326.xyz/Article/details/gtkooyxopr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.haohaochexian.top/Article/details/gtvrqfkptj.html

[N06] 判断回文字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtutvmzeku.html

Py:   s == s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gtunjxfumc.html

PHP:  $s === strrev($s);
来源：http://dali.cheryme.top/Article/details/gtnrxuugpw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtavabmkce.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtudwufkja.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj20258888.top/Article/details/gtovmqnfwd.html

Go:   // 双指针从两端比较
来源：http://dali.jlsjyb.cn/Article/details/gtoeqbqqbi.html

Ruby: s == s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtxqxjbpiv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zdqjudy.top/Article/details/gtmbezhpie.html

[N07] 两数之和（返回下标）
来源：http://dali.mhx1999.top/Article/details/gtenysuvpi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.svipenyu.cn/Article/details/gtolshqsaq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.vqdsnc.cn/Article/details/gtimcbjaby.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xziqi.cn/Article/details/gtqtnftbay.html

TS:   // 手写 Map<string, number>
来源：http://dali.0kj1m.cn/Article/details/gtmmvzlsop.html

Java: // 手写 HashMap
来源：http://dali.sysykeji.top/Article/details/gtgawncqpt.html

Go:   // 手写 map[int]int
来源：http://dali.ybcxt.top/Article/details/gtwnairoxf.html

Ruby: // 手写 Hash
来源：http://dali.dashuyun.cn/Article/details/gttxmztiwx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sufxvd.cn/Article/details/gtzthfwhcv.html

[N08] 生成全排列
来源：http://dali.meibo888.top/Article/details/gtqcyzcani.html

Py:   itertools.permutations(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtffrkbubg.html

PHP:  // 手写递归交换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmztlcjhq.html

JS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtqktvqdsx.html

TS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtyiotrgvz.html

Java: // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtzkouiszx.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjuqqhbxl.html

Ruby: arr.permutation.to_a
来源：http://dali.hnqzz.top/Article/details/gtgoecnsmd.html

C#:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtzyzvmimy.html

[N09] 栈与队列
来源：http://dali.jinqigufen.top/Article/details/gtgwlypmdh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sysykeji.top/Article/details/gtvmlabjcd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtseiqrrdj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gtiajfuopu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.316326.xyz/Article/details/gttkonfbpj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuheeivnr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqutowwr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gtwfiqffhh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.0kj1m.cn/Article/details/gtoewwyzua.html

[N10] 链表节点定义
来源：http://dali.yongpay.top/Article/details/gtmwkuovmj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daria6918.cn/Article/details/gtanzxunlf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgwhbqwmk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangdashe.top/Article/details/gtldmifqhn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.svipenyu.cn/Article/details/gtclplpcau.html

Java: class Node { int v; Node next; }
来源：http://dali.shuidangran.top/Article/details/gtlqqhpbck.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daria6918.cn/Article/details/gtxzmbahiu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pycfn.com/Article/details/gtmukmebft.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkqzaklpr.html

[N11] 二叉树中序遍历
来源：http://dali.gotoacloud.top/Article/details/gtxikvzekh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aibaodan.cn/Article/details/gtawvunubl.html

PHP:  // 手写递归函数
来源：http://dali.0kj1m.cn/Article/details/gtgnciwjxf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gtlkvtnnmy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gtwjgexctf.html

Java: // 手写递归
来源：http://dali.mhx1999.top/Article/details/gtckalbvvc.html

Go:   // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtwejavgph.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.meibo888.top/Article/details/gtqijrzgoh.html

C#:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtfpicgati.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.c1oappe.top/Article/details/gtclcbbalk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.birdmap.top/Article/details/gtnlttjbcw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.iojbl.cn/Article/details/gtbsjalmea.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gtkworktlp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttuamldll.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gtrofxeezc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkoftiynf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.tianlin.xyz/Article/details/gtwiwnsluk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gtocoauufh.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtujbodvpf.html

O. 并发与异步
来源：http://dali.gaohongyu789.top/Article/details/gtfbpmypmv.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtkpydljfc.html

[O01] 启动一个线程
来源：http://dali.xziqi.cn/Article/details/gtctrzakib.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hfpthk.cn/Article/details/gtuglmhhhl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcfxmlsi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tianlin.xyz/Article/details/gtzakqvvio.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gtxsrnhudx.html

Java: new Thread(() -> f()).start()
来源：http://dali.hongshengwenyu.top/Article/details/gtqknornyk.html

Go:   go f()
来源：http://dali.hongshengwenyu.top/Article/details/gtbhcctfpn.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpifasybd.html

C#:   Task.Run(() => F());
来源：http://dali.smart0.xyz/Article/details/gtwzddevwq.html

[O02] 使用线程池
来源：http://dali.daria6918.cn/Article/details/gtuszivbqh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhiwuduotai.top/Article/details/gtvzcklrrd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlgovxoq.html

JS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gttdwzcqjk.html

TS:   // worker_threads 线程池
来源：http://dali.guowangkeji.top/Article/details/gtjgknengf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daria6918.cn/Article/details/gtqwrzckua.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gtaxxzpxdg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shzxlz.cn/Article/details/gtfcsacebc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cdnleiting.top/Article/details/gtkerpxivo.html

[O03] 加锁保护共享数据
来源：http://dali.gaohongyu789.top/Article/details/gtaozfolmb.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gtdeqfdwox.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shangyingyoupin.top/Article/details/gtuwpsmtvt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.quarkkingdee.top/Article/details/gtfjjevhhb.html

TS:   // 同 JS
来源：http://dali.mhx1999.top/Article/details/gtsywitsbr.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj20258.top/Article/details/gtwyixdcrt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuanzhike.top/Article/details/gtlovcbdnd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cdnleiting.top/Article/details/gthglunzbv.html

C#:   lock (gate) { shared++; }
来源：http://dali.cucudq.cn/Article/details/gtaevfvjih.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gtjebwldku.html

Py:   async def f():⏎    await g()
来源：http://dali.jqgfzy.top/Article/details/gtfhthlxgk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.smart0.xyz/Article/details/gtxucpcsaw.html

JS:   async function f() { await g(); }
来源：http://dali.sweek.top/Article/details/gtpvausmot.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gtknfjinpl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.guannengcc.top/Article/details/gtryvevini.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258888.top/Article/details/gtbeanovye.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhengqikj.top/Article/details/gtlacmupol.html

C#:   async Task F() { await G(); }
来源：http://dali.ybcxt.top/Article/details/gthaxjapul.html

[O05] 并发执行并等待全部完成
来源：http://dali.jlsjyb.cn/Article/details/gtqloqnmzd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.havefunace.top/Article/details/gtjydukotz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.c1oappe.top/Article/details/gtufjbmtes.html

JS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gtggqrwgkt.html

TS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gtunloehvv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.aizwys.cn/Article/details/gtefhfpdyb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pycfn.com/Article/details/gtnlfsoilg.html

Ruby: threads.map(&:join)
来源：http://dali.yangfankeji.com/Article/details/gtrivuzgug.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xinyue.icu/Article/details/gtyhxoyuwy.html

[O06] 使用进程池
来源：http://dali.svipenyu.cn/Article/details/gtjohqvdzd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkfzuxyj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ydzc1.top/Article/details/gthitbdxzr.html

JS:   // child_process / cluster 模块
来源：http://dali.nanxuanxn.top/Article/details/gtlqqfqioq.html

TS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gtqhmjozuc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sufxvd.cn/Article/details/gtlbrwhgkn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.wangshuangyany.cn/Article/details/gtgqlrkfmf.html

Ruby: // fork 块
来源：http://dali.daria6918.cn/Article/details/gtjhnozcqo.html

C#:   Parallel.For
来源：http://dali.yj20258.top/Article/details/gtdseeowbl.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtcoxyuywz.html

P. 常用工具函数
来源：http://dali.chenlongwang.top/Article/details/gtyjuvjxtu.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtitxuiifc.html

[P01] 生成 UUID
来源：http://dali.fengsongda.top/Article/details/gtyynvllml.html

Py:   str(uuid.uuid4())
来源：http://dali.zhixingplan.top/Article/details/gtuyzjhvcj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.aizwys.cn/Article/details/gtabnvrzjs.html

JS:   crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gthpbccqhw.html

TS:   crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gtlnkrzipg.html

Java: UUID.randomUUID().toString()
来源：http://dali.cashguo.top/Article/details/gtinmsraax.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinqigfzy.top/Article/details/gttkiorxdw.html

Ruby: SecureRandom.uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsexfnkiu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sweek.top/Article/details/gtjfoexrwq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ybcxt.top/Article/details/gtpjdqophs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenjidiqi.icu/Article/details/gtifrailnn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtcncbdljq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtlcwbdhec.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhengqikj.top/Article/details/gtgopsyifi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yuanzhike.top/Article/details/gtqcfmhidf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ivvv.top/Article/details/gtbvkvxzjz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gteaekuwwh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xylfe.cn/Article/details/gtnrfsglwi.html

[P03] 生成短随机字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdbpvfgk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.aibaodan.cn/Article/details/gtmxdjktza.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsoscauft.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gtriilyagu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gtdndasujo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.redwolf501.top/Article/details/gtwcplaccz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xinyue.icu/Article/details/gtkrwlfbeg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangdashe.top/Article/details/gtroqxpffg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenzaomai.com/Article/details/gtxazfxdbz.html

[P04] 求长度
来源：http://dali.tanke756.top/Article/details/gtabxqkfnp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcttgmbk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtglszucfz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zycfv.cn/Article/details/gthlvpvzop.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gtpcguxsxh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258888.top/Article/details/gtwiivotzy.html

Go:   len(arr);  len(m)
来源：http://dali.jlsjyb.cn/Article/details/gtaceqhkfm.html

Ruby: x.length;  x.size
来源：http://dali.chenjidiqi.icu/Article/details/gtiqnbrbnh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj20258888.top/Article/details/gtohozkndg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yangfankeji.com/Article/details/gtdszonudu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shzxlz.cn/Article/details/gtloyrqtoq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jyoumei.cn/Article/details/gtvzrnphzc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jiagoushi.top/Article/details/gtnqezahpl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yongpay.top/Article/details/gtmxpoqbcp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aizwys.cn/Article/details/gtvorcfncy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shuidangran.top/Article/details/gtrmrfzwkr.html

Ruby: a == b
来源：http://dali.quarkkingdee.top/Article/details/gtjhdoiumd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sxryk.cn/Article/details/gtybpphdxt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yongpay.top/Article/details/gtimbpesrl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.bjfxy.top/Article/details/gtkjkpipjc.html

PHP:  if (empty($x)) {}
来源：http://dali.ydzc1.top/Article/details/gtiwolnbxl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuanzx.com/Article/details/gtnqyjapok.html

TS:   if (x == null) {}
来源：http://dali.jlsjyb.cn/Article/details/gtnhccypte.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gtqvhjfiga.html

Go:   if x == nil {}
来源：http://dali.0kj1m.cn/Article/details/gtnamqlmyp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxuanxn.top/Article/details/gtvvgdnswl.html

C#:   if (x is null) {}
来源：http://dali.ehwqpu.com/Article/details/gtrunmyfwa.html

[P07] 防抖与节流
来源：http://dali.haohaochexian.top/Article/details/gtjatsemxe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenlongwang.top/Article/details/gtinvlekvl.html

PHP:  // 手写时间戳比较
来源：http://dali.zhoulong.xyz/Article/details/gtxojvzdys.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gtqcugxwae.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gtwjbkekvg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.dashuyun.cn/Article/details/gtrqeqrduo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jqgfzy.top/Article/details/gtzfjmtrfa.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jianghu66.top/Article/details/gtpbusjsev.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhiwuduotai.top/Article/details/gtdhnaxjwt.html

[P08] 处理浮点精度问题
来源：http://dali.yuanzhike.top/Article/details/gtkifzhtrn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangshuangyany.cn/Article/details/gtkgcehuix.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj20258888.top/Article/details/gtixcamqtg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hongshengwenyu.top/Article/details/gtqavbxkio.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsaqbxrl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hnqzz.top/Article/details/gtafphejmn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shuidangran.top/Article/details/gtgpzvvfny.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tanke756.top/Article/details/gtndeihfpw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.mhx1999.top/Article/details/gtkriztudb.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtnyyyihaz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.snrcjt.cn/Article/details/gtvwucqudi.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtxeyurlkx.html

[Q01] 创建表
来源：http://dali.wangshuangyany.cn/Article/details/gtpqkngcdd.html

CREATE TABLE users (
来源：http://dali.fzhhl.top/Article/details/gtgwceyqie.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.haohaochexian.top/Article/details/gtxljspsgo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jyoumei.cn/Article/details/gtqbgcbmqo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cheryme.top/Article/details/gtzakqhgnl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoneuxvnp.html

);
来源：http://dali.yj20258.top/Article/details/gtmvwoogkf.html

[Q02] 创建带外键的表
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqfzkjkf.html

CREATE TABLE orders (
来源：http://dali.sufxvd.cn/Article/details/gtccebfkeo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhongyouzk.top/Article/details/gtsmxcakqc.html

user_id INT NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gtpmugbgjx.html

amount DECIMAL(10, 2),
来源：http://dali.yj20258888.top/Article/details/gtoiwekvwb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.daria6918.cn/Article/details/gtaouvafkv.html

);
来源：http://dali.smart0.xyz/Article/details/gtqevwpebw.html

[Q03] 增加列
来源：http://dali.yanxiufei.cn/Article/details/gtznsohjao.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ybcxt.top/Article/details/gtgonmjxqh.html

[Q04] 修改列类型
来源：http://dali.bjfxy.top/Article/details/gtjcgxtgrd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cdnleiting.top/Article/details/gttwpertsl.html

[Q05] 重命名列
来源：http://dali.guannengcc.top/Article/details/gtousagyad.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cucudq.cn/Article/details/gtvnmrwgdy.html

[Q06] 删除列
来源：http://dali.zycfv.cn/Article/details/gtngofrdet.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafeswpre.html

[Q07] 删除表
来源：http://dali.mhx1999.top/Article/details/gtryenxtoy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cucudq.cn/Article/details/gtcoybxjdy.html

[Q08] 创建普通索引
来源：http://dali.quarkkingdee.top/Article/details/gtkzdxdgej.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gtswairkbu.html

[Q09] 创建唯一索引
来源：http://dali.yj202588.top/Article/details/gtjzkcruyc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.bjfxy.top/Article/details/gtsugacifs.html

[Q10] 插入单行
来源：http://dali.cqqwz.cn/Article/details/gtugkkkggt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuxming.cn/Article/details/gtqazmbwlg.html

[Q11] 一次插入多行
来源：http://dali.zdqjudy.top/Article/details/gtsqkpuhnl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.havefunace.top/Article/details/gtfmqwyhsa.html

[Q12] 插入后取自增 ID
来源：http://dali.feifeiyinyue.top/Article/details/gtotqbxrhy.html


<!-- 参考信息 -->