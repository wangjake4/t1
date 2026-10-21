代发 wailian999

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.feifeiyinyue.top/Article/details/gtzdsdurib.html

Ruby: warn "err"
来源：http://dali.gogol.net.cn/Article/details/gtwsqsgfmz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.9152youxi.cn/Article/details/gtupzedgoc.html

[M07] 判断是否为主入口
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfkstmqlz.html

Py:   if __name__ == "__main__":
来源：http://dali.gogol.net.cn/Article/details/gtqlblcfiz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenjidiqi.icu/Article/details/gtqcmimgrc.html

JS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gtklkxifpf.html

TS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gtjesgwfcs.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiuisjvbh.html

Go:   func main()
来源：http://dali.hnqzz.top/Article/details/gtumdzamkg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shzxlz.cn/Article/details/gtrlikhjja.html

C#:   static void Main(string[] args)
来源：http://dali.nanxinkj.top/Article/details/gtryqnhrzr.html

[M08] 获取系统与运行时信息
来源：http://dali.sufxvd.cn/Article/details/gtkdtuvrae.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenjidiqi.icu/Article/details/gtuxgbscth.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiktpftuj.html

JS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gtdnwbmnfl.html

TS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gtfihvmrhj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sxryk.cn/Article/details/gtldjqkbhw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zdqjudy.top/Article/details/gtfgzcgkyx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fzhhl.top/Article/details/gtfpkvxeul.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.kuanghao11.cn/Article/details/gtyfkihjmp.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtxyoyjttq.html

N. 数据结构与算法
来源：http://dali.yj20258888.top/Article/details/gtdkxtebla.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtvuwjhzoh.html

[N01] 二分查找（有序数组）
来源：http://dali.daxiang520.top/Article/details/gtfadomidq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtcfgjtylj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gtasswajwz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gttyruolpr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtrsngpbzx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtqifqyymv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtdbwhflhq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.quarkkingdee.top/Article/details/gtyzqwobbc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gtaiksbwqq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgufenzy.top/Article/details/gteclcmfyn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.redwolf501.top/Article/details/gttbqhqsue.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtnpnvpaie.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gtjcfwrthk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gtokaanfzt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sweek.top/Article/details/gtttjwesgt.html

Go:   slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtpfmjorge.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gtsjrgxzha.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinqigufen.top/Article/details/gtiyfbzgfm.html

[N03] 快速排序（分治示例）
来源：http://dali.feifeiyinyue.top/Article/details/gtpjftcdnl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nanxuanxn.top/Article/details/gtpiuzhsts.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xylfe.cn/Article/details/gtxgiofvrr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gtacyrvblz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gtbvlzpiqs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nwbrower.top/Article/details/gthngdxowa.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhongyouzk.top/Article/details/gtijwrrfjv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhengqikj.top/Article/details/gtnyhozffs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.redwolf501.top/Article/details/gtcplfvbtf.html

[N04] 斐波那契数列
来源：http://dali.gaohongyu789.top/Article/details/gtxqlbkvtj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gtkdjdvhrs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nwbrower.top/Article/details/gtfffrbrfn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtjylcbeyk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtaretvyov.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gtqgyiwbuo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxinkj.top/Article/details/gtewkesmyr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gtbqfalwjq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtilsktbkq.html

[N05] 最大公约数
来源：http://dali.jyoumei.cn/Article/details/gttnerlnkf.html

Py:   math.gcd(a, b)
来源：http://dali.ybcxt.top/Article/details/gtbumykhto.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fzhhl.top/Article/details/gtfjqqlcsc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gtlpivuwom.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtencyzlra.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnxiangtu.top/Article/details/gtbpeuedvq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cucudq.cn/Article/details/gtdaihcack.html

Ruby: a.gcd(b)
来源：http://dali.yueranfly.top/Article/details/gtaebnxmno.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guowangkeji.top/Article/details/gteuecmwxk.html

[N06] 判断回文字符串
来源：http://dali.jlsjyb.cn/Article/details/gtklfrpqma.html

Py:   s == s[::-1]
来源：http://dali.jinqigufen.top/Article/details/gtdbgnfiib.html

PHP:  $s === strrev($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqdxrtka.html

JS:   s === [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtzhgoenbv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtsckrzcgn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.andypj.xyz/Article/details/gtymsivskb.html

Go:   // 双指针从两端比较
来源：http://dali.hongshengwenyu.top/Article/details/gtdswvasrn.html

Ruby: s == s.reverse
来源：http://dali.aibaodan.cn/Article/details/gtsseqpuqw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yonumen.top/Article/details/gtrzewpzpl.html

[N07] 两数之和（返回下标）
来源：http://dali.9152youxi.cn/Article/details/gteqwavhyq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhixingplan.top/Article/details/gtptbzdcti.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.mhx1999.top/Article/details/gtxvegwljg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daxiang520.top/Article/details/gtanxnuags.html

TS:   // 手写 Map<string, number>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpyqjdrdn.html

Java: // 手写 HashMap
来源：http://dali.snrcjt.cn/Article/details/gtxgqemprt.html

Go:   // 手写 map[int]int
来源：http://dali.haohaochexian.top/Article/details/gtqaysopeq.html

Ruby: // 手写 Hash
来源：http://dali.c1oappe.top/Article/details/gttdmoqfxy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shuidangran.top/Article/details/gtczuxbwvr.html

[N08] 生成全排列
来源：http://dali.gzhubu.top/Article/details/gtxjwdcjtq.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtebdxjugb.html

PHP:  // 手写递归交换
来源：http://dali.yuanzhike.top/Article/details/gtppldrqaa.html

JS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtjkkcmqtz.html

TS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gthgpfzxlf.html

Java: // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdbufzvr.html

Go:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gttecexnpz.html

Ruby: arr.permutation.to_a
来源：http://dali.guannengcc.top/Article/details/gtpzqjturr.html

C#:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtsgmmidzd.html

[N09] 栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gttcuputoz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tian-w.cn/Article/details/gtstdmlayc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtzjlhxtlp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtsuvgiggu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangdashe.top/Article/details/gtllbawlrq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yanxiufei.cn/Article/details/gtxkotcaic.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yanxiufei.cn/Article/details/gtnarwmxwx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gtmnehmemc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.c1oappe.top/Article/details/gtjtcrqsht.html

[N10] 链表节点定义
来源：http://dali.feifeiyinyue.top/Article/details/gtwaegdtpd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.meibo888.top/Article/details/gtdrbczstj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.c1oappe.top/Article/details/gtdarfyfol.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.iojbl.cn/Article/details/gtkfiluvlo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhoulong.xyz/Article/details/gtrrsfeudm.html

Java: class Node { int v; Node next; }
来源：http://dali.c1oappe.top/Article/details/gtgjzhhbiw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yvedp.cn/Article/details/gtshharpyw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ybcxt.top/Article/details/gttfkdwnlz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.snrcjt.cn/Article/details/gtkxotoquz.html

[N11] 二叉树中序遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgexqzpcu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigfzy.top/Article/details/gtkfkginav.html

PHP:  // 手写递归函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyicssiui.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gttvmdnmyv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gtdzhojaap.html

Java: // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtnxahqfkf.html

Go:   // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gthldcgnwo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cdnleiting.top/Article/details/gtfysywvxh.html

C#:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gttijuffpc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gotoacloud.top/Article/details/gtswwrupju.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ydzc1.top/Article/details/gtxgtvzdlx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigfzy.top/Article/details/gtibwcbwtk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnqzz.top/Article/details/gtvibxxmyz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenzaomai.com/Article/details/gtpxyvuucr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.9152youxi.cn/Article/details/gtzlowfylj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yonumen.top/Article/details/gtvbapacfe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258888.top/Article/details/gtrvsjvaup.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gtjxdmdybv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtxgwlwakg.html

O. 并发与异步
来源：http://dali.zhiwuduotai.top/Article/details/gtdwrhwevo.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtjoksgsqd.html

[O01] 启动一个线程
来源：http://dali.jianghu66.top/Article/details/gtszbyxmdp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangdashe.top/Article/details/gtbblnwgkq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.meibo888.top/Article/details/gtzqftcrva.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangdashe.top/Article/details/gtucfpqvzk.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gtklkigzxd.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgyrvamxk.html

Go:   go f()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgywhpskg.html

Ruby: Thread.new { f }
来源：http://dali.jiagoushi.top/Article/details/gtpudqnjvr.html

C#:   Task.Run(() => F());
来源：http://dali.sweek.top/Article/details/gthyaqcela.html

[O02] 使用线程池
来源：http://dali.chenjidiqi.icu/Article/details/gttaqgnazc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shuidangran.top/Article/details/gtikytsbri.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangshuangyany.cn/Article/details/gtmbnhyccl.html

JS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gtukhonrkh.html

TS:   // worker_threads 线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzltcfhct.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sysykeji.top/Article/details/gtzoxyzmed.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cucudq.cn/Article/details/gtyqjeckmh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jlsjyb.cn/Article/details/gtptisrmlx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yangfankeji.com/Article/details/gtawtjenuw.html

[O03] 加锁保护共享数据
来源：http://dali.sweek.top/Article/details/gtggdcotav.html

Py:   with lock: shared += 1
来源：http://dali.hfpthk.cn/Article/details/gtxvjfisdu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnqzz.top/Article/details/gtwocoioxc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fzhhl.top/Article/details/gtrwpqlctn.html

TS:   // 同 JS
来源：http://dali.daria6918.cn/Article/details/gtkrmokyks.html

Java: synchronized (this) { shared++; }
来源：http://dali.sweek.top/Article/details/gtmfsmntvp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jianghu66.top/Article/details/gtgsmkqclc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.aibaodan.cn/Article/details/gtdbdfdkku.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gtkslvhyee.html

[O04] 定义异步函数并等待
来源：http://dali.quarkkingdee.top/Article/details/gtnaotrnro.html

Py:   async def f():⏎    await g()
来源：http://dali.c1oappe.top/Article/details/gtlqsosnqy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.mhx1999.top/Article/details/gtzhchrxfb.html

JS:   async function f() { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gtkitfmwam.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gtchteyrlf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangshuangyany.cn/Article/details/gtrwrzsbaj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.smart0.xyz/Article/details/gtnyzuumus.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zdqjudy.top/Article/details/gteziqhjbq.html

C#:   async Task F() { await G(); }
来源：http://dali.jyoumei.cn/Article/details/gtpebvxpij.html

[O05] 并发执行并等待全部完成
来源：http://dali.daxiang520.top/Article/details/gtvrshsvmm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sxryk.cn/Article/details/gtlgbirrmq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tianlin.xyz/Article/details/gtafhmyfxq.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gtpjcydkkm.html

TS:   await Promise.all(tasks)
来源：http://dali.shzxlz.cn/Article/details/gtknltooxa.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuetiantiany.cn/Article/details/gtyyxrmvks.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nanxinkj.top/Article/details/gtjyhzrhns.html

Ruby: threads.map(&:join)
来源：http://dali.zdqjudy.top/Article/details/gtspezztvl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.redwolf501.top/Article/details/gtllithdiq.html

[O06] 使用进程池
来源：http://dali.bjfxy.top/Article/details/gtguzjroym.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shuidangran.top/Article/details/gtwigajqyw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sxryk.cn/Article/details/gtrqrsikkl.html

JS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gtuuhyfatm.html

TS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gtcycnnqlp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jyoumei.cn/Article/details/gtodcsknfg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yongpay.top/Article/details/gtninqgbma.html

Ruby: // fork 块
来源：http://dali.nwbrower.top/Article/details/gtycnchpyt.html

C#:   Parallel.For
来源：http://dali.sysykeji.top/Article/details/gtnwrsqbys.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtgrpiqqih.html

P. 常用工具函数
来源：http://dali.guannengcc.top/Article/details/gtpjarplsp.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtbypwywaw.html

[P01] 生成 UUID
来源：http://dali.shanyushiyangkeji.top/Article/details/gtekvytigs.html

Py:   str(uuid.uuid4())
来源：http://dali.cqqwz.cn/Article/details/gtycwecsdn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.havefunace.top/Article/details/gtgvtrrliy.html

JS:   crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gtaljhadlf.html

TS:   crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gtvzbekqwy.html

Java: UUID.randomUUID().toString()
来源：http://dali.0kj1m.cn/Article/details/gtgfwpmdks.html

Go:   // 用 github.com/google/uuid
来源：http://dali.wangshuangyany.cn/Article/details/gtmuafkbxs.html

Ruby: SecureRandom.uuid
来源：http://dali.kuanghao11.cn/Article/details/gtojoubfbj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.0kj1m.cn/Article/details/gttxwfjvwm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258888.top/Article/details/gtxeikpxnu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xuetiantiany.cn/Article/details/gtwsirbvnv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xylfe.cn/Article/details/gtmuaszmmg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tian-w.cn/Article/details/gtpkazdhtg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhongyouzk.top/Article/details/gtewswajug.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuanzx.com/Article/details/gtbiaxocaw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daxiang520.top/Article/details/gtxbaerorc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.svipenyu.cn/Article/details/gtzfzojtkl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuanzx.com/Article/details/gtqpylsdxf.html

[P03] 生成短随机字符串
来源：http://dali.0kj1m.cn/Article/details/gtoosjvnub.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.316326.xyz/Article/details/gtmckmjstb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hysaishi.cn/Article/details/gtehxcfwuy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gtoioxmect.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gtlkebxyox.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dashuyun.cn/Article/details/gtumtwqrpw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cqqwz.cn/Article/details/gtiskmwczl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jianghu66.top/Article/details/gtmmxdjcbe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sufxvd.cn/Article/details/gtdfogyrli.html

[P04] 求长度
来源：http://dali.guannengcc.top/Article/details/gtxgrbybyl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xuanzx.com/Article/details/gtsrdltled.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtcydohlya.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gtfyxwhecd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyizvngqy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cqqwz.cn/Article/details/gtudjulwgv.html

Go:   len(arr);  len(m)
来源：http://dali.gotoacloud.top/Article/details/gtohlgtgqx.html

Ruby: x.length;  x.size
来源：http://dali.sufxvd.cn/Article/details/gtghlxyeku.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xylfe.cn/Article/details/gthwyoefye.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daria6918.cn/Article/details/gtsnkxywwm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.quarkkingdee.top/Article/details/gtavnhxfsu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aibaodan.cn/Article/details/gtpguodsxb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258.top/Article/details/gtvnpgftxr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zycfv.cn/Article/details/gtzwsclmzp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258.top/Article/details/gtmtlcdonz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cheryme.top/Article/details/gtvsotrmdc.html

Ruby: a == b
来源：http://dali.jianghu66.top/Article/details/gtpqzpsmll.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcwaslyn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.aizwys.cn/Article/details/gtlljupccw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xinyue.icu/Article/details/gthqqqzoet.html

PHP:  if (empty($x)) {}
来源：http://dali.cheryme.top/Article/details/gtkxiqktyp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yuanzhike.top/Article/details/gtmdewyees.html

TS:   if (x == null) {}
来源：http://dali.birdmap.top/Article/details/gtvxlptcas.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gtdcylowyb.html

Go:   if x == nil {}
来源：http://dali.fengsongda.top/Article/details/gtaxsmqwtj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuanzhike.top/Article/details/gtckihqjvb.html

C#:   if (x is null) {}
来源：http://dali.daria6918.cn/Article/details/gtblugrkwd.html

[P07] 防抖与节流
来源：http://dali.nwbrower.top/Article/details/gtkufnlbqt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jqgfzy.top/Article/details/gtyjnuynok.html

PHP:  // 手写时间戳比较
来源：http://dali.zycfv.cn/Article/details/gtxwgvftqv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gtdgymotyp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtlhvzylgt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yueranfly.top/Article/details/gtgtrjivbo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ivvv.top/Article/details/gtqhahqdnd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jiagoushi.top/Article/details/gtxpjovkka.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jqgfzy.top/Article/details/gthtjfarru.html

[P08] 处理浮点精度问题
来源：http://dali.jyoumei.cn/Article/details/gtztusyjcr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jqgufenzy.top/Article/details/gtjpvmvftz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dashuyun.cn/Article/details/gtfcrbnlao.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.guannengcc.top/Article/details/gtuqfaeuow.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.9152youxi.cn/Article/details/gtlqerxwpp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xinyue.icu/Article/details/gtxfezhxcr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrzqxzbz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.havefunace.top/Article/details/gttndlmfvg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jiagoushi.top/Article/details/gtvjjxpmob.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtqvzugxot.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xuanzx.com/Article/details/gtnkvxdaah.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtzawjawdc.html

[Q01] 创建表
来源：http://dali.316326.xyz/Article/details/gtwedlcxlm.html

CREATE TABLE users (
来源：http://dali.yanxiufei.cn/Article/details/gttnxrvpzd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.haohaochexian.top/Article/details/gtelibiali.html

name VARCHAR(50) NOT NULL,
来源：http://dali.pycfn.com/Article/details/gtbiuhhsvd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hongshengwenyu.top/Article/details/gtjjlfhiie.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.meibo888.top/Article/details/gtwezmqvzu.html

);
来源：http://dali.aibaodan.cn/Article/details/gtxqoewsca.html

[Q02] 创建带外键的表
来源：http://dali.jinqigufen.top/Article/details/gtycbqojni.html

CREATE TABLE orders (
来源：http://dali.fengsongda.top/Article/details/gtbhgdcvah.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xinyue.icu/Article/details/gtapbhabiv.html

user_id INT NOT NULL,
来源：http://dali.sweek.top/Article/details/gtvngzvemv.html

amount DECIMAL(10, 2),
来源：http://dali.tianlin.xyz/Article/details/gtqokcploo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj20258.top/Article/details/gttkgcifog.html

);
来源：http://dali.vqdsnc.cn/Article/details/gtmqfuztzy.html

[Q03] 增加列
来源：http://dali.yj202588.top/Article/details/gtfemneanw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzzgbsme.html

[Q04] 修改列类型
来源：http://dali.feifeiyinyue.top/Article/details/gtcsxfunvu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.vqdsnc.cn/Article/details/gthdhpzabi.html

[Q05] 重命名列
来源：http://dali.tanke756.top/Article/details/gttsuuaynq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigfzy.top/Article/details/gtaccwofyy.html

[Q06] 删除列
来源：http://dali.hongshengwenyu.top/Article/details/gtatuatpnn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guowangkeji.top/Article/details/gtkpcodhip.html

[Q07] 删除表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdsbpcuwm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xinyue.icu/Article/details/gtojbsaaak.html

[Q08] 创建普通索引
来源：http://dali.ppjwa.cn/Article/details/gtnhjwwnsm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnxiangtu.top/Article/details/gtzrqdwupa.html

[Q09] 创建唯一索引
来源：http://dali.zdqjudy.top/Article/details/gtakpaafnr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gtvrzbmpcj.html

[Q10] 插入单行
来源：http://dali.zdqjudy.top/Article/details/gtvhjoztcr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtiufcktcq.html

[Q11] 一次插入多行
来源：http://dali.xuanzx.com/Article/details/gtfidebuhy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gzhubu.top/Article/details/gtmkwxqapb.html

[Q12] 插入后取自增 ID
来源：http://dali.jianghu66.top/Article/details/gtohxznzes.html


<!-- 参考信息 -->