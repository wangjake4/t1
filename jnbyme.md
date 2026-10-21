代发 wailian999

Ruby: exit 1
来源：http://dali.jqgfzy.top/Article/details/gtjuropyxo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xylfe.cn/Article/details/gthngkhxhs.html

[M06] 向标准错误输出
来源：http://dali.9152youxi.cn/Article/details/gtqgisziwl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.iojbl.cn/Article/details/gtvlzfhifq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jianghu66.top/Article/details/gtfmmlmxdw.html

JS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gtrgetkhww.html

TS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtsazyabgc.html

Java: System.err.println("err")
来源：http://dali.zycfv.cn/Article/details/gtqmhxgqht.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hywenlv.cn/Article/details/gtjeaqmrrr.html

Ruby: warn "err"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtneqbogsn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvojnpcxn.html

[M07] 判断是否为主入口
来源：http://dali.svipenyu.cn/Article/details/gtjiztcyde.html

Py:   if __name__ == "__main__":
来源：http://dali.yongpay.top/Article/details/gtpfhubmqy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cheryme.top/Article/details/gtctfdcgkf.html

JS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gtjsoohgxs.html

TS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gtotseokcy.html

Java: public static void main(String[] args)
来源：http://dali.pycfn.com/Article/details/gtvnnffzzy.html

Go:   func main()
来源：http://dali.tian-w.cn/Article/details/gtaxhlpour.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.316326.xyz/Article/details/gttuscaewg.html

C#:   static void Main(string[] args)
来源：http://dali.hammf.cn/Article/details/gtlnzmcfnh.html

[M08] 获取系统与运行时信息
来源：http://dali.daria6918.cn/Article/details/gtcamiwjqw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gogol.net.cn/Article/details/gtdlkjzcrg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ppjwa.cn/Article/details/gtjlgmengq.html

JS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gtmvploghg.html

TS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gtvnlqxysc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.snrcjt.cn/Article/details/gtnwrijvyy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hongshengwenyu.top/Article/details/gtlgbolxdk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zdqjudy.top/Article/details/gtzjluqaqr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jianghu66.top/Article/details/gtbhylcgth.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtigankrxw.html

N. 数据结构与算法
来源：http://dali.jiagoushi.top/Article/details/gtwzllvvll.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtkqtjkrni.html

[N01] 二分查找（有序数组）
来源：http://dali.zhoulong.xyz/Article/details/gtzleububy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtqbawdbzf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.svipenyu.cn/Article/details/gtzgkwivsu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gthjccdrcn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtbuzuohug.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gtmjcacbwb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtmeqaoqdh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj202588.top/Article/details/gttovmcpyi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gteeczkmyx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pycfn.com/Article/details/gtjiaynvpd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gtziwisedo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gthnvtvcai.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gtevyqxucl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gtkdmdpgrv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sxryk.cn/Article/details/gtopoyedkv.html

Go:   slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gtfxmipdby.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gtxarfneus.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hysaishi.cn/Article/details/gtqctzxaeb.html

[N03] 快速排序（分治示例）
来源：http://dali.iojbl.cn/Article/details/gtzvwcfsyr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tian-w.cn/Article/details/gtevpustks.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jianghu66.top/Article/details/gtzjnupplg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gtimazpxme.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gtccekzzkm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cdnleiting.top/Article/details/gtvdfmzlir.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhoulong.xyz/Article/details/gtpznukkjn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gaohongyu789.top/Article/details/gtjzbvqgpc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gaohongyu789.top/Article/details/gtdrfmflak.html

[N04] 斐波那契数列
来源：http://dali.cqqwz.cn/Article/details/gtoxhodvwu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gtvobbbyhs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gtbefcmdpc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gtoolsuusj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gtzrnphoji.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpihminjk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zdqjudy.top/Article/details/gtrtwjzbqg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gtuavaygdc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtqbyoulhx.html

[N05] 最大公约数
来源：http://dali.yuanzhike.top/Article/details/gtbcuznthb.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gtgdimgffq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jyoumei.cn/Article/details/gtnzhtsjhx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gtiaqrfswr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gtqvndtvjd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yanxiufei.cn/Article/details/gtevpfkpqw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daxiang520.top/Article/details/gtjypytlda.html

Ruby: a.gcd(b)
来源：http://dali.shzxlz.cn/Article/details/gtpbkyqhbw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xuetiantiany.cn/Article/details/gtadhzgbah.html

[N06] 判断回文字符串
来源：http://dali.cucudq.cn/Article/details/gtnkokolzt.html

Py:   s == s[::-1]
来源：http://dali.yj202588.top/Article/details/gtryemhfvp.html

PHP:  $s === strrev($s);
来源：http://dali.guannengcc.top/Article/details/gtbsryupmm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gthoeuxsit.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtpiexiksl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hywenlv.cn/Article/details/gtldjdrlwd.html

Go:   // 双指针从两端比较
来源：http://dali.kuanghao11.cn/Article/details/gtnbgnpvlm.html

Ruby: s == s.reverse
来源：http://dali.gzhubu.top/Article/details/gtuhdtrryt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aibaodan.cn/Article/details/gtnlssypch.html

[N07] 两数之和（返回下标）
来源：http://dali.fengsongda.top/Article/details/gtgwjwzmzy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnqzz.top/Article/details/gtnsojedka.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.redwolf501.top/Article/details/gtkoosyhky.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkhqjuef.html

TS:   // 手写 Map<string, number>
来源：http://dali.feifeiyinyue.top/Article/details/gtbsrlkrfo.html

Java: // 手写 HashMap
来源：http://dali.jqgufenzy.top/Article/details/gtqhsrsafa.html

Go:   // 手写 map[int]int
来源：http://dali.vqdsnc.cn/Article/details/gtgxtmjigy.html

Ruby: // 手写 Hash
来源：http://dali.mhx1999.top/Article/details/gtfpehqlzh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tian-w.cn/Article/details/gtdtjiqdwq.html

[N08] 生成全排列
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmzleilo.html

Py:   itertools.permutations(arr)
来源：http://dali.ydzc1.top/Article/details/gthuhowqnq.html

PHP:  // 手写递归交换
来源：http://dali.jqgufenzy.top/Article/details/gtgthjcmbr.html

JS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtktspmqyn.html

TS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gttofefntw.html

Java: // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtustjtsrq.html

Go:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtshfmwkob.html

Ruby: arr.permutation.to_a
来源：http://dali.daria6918.cn/Article/details/gtojryfxsy.html

C#:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtrpqygknd.html

[N09] 栈与队列
来源：http://dali.ivvv.top/Article/details/gtdvmzlbpc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xylfe.cn/Article/details/gtqxvsskbb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gtenpiffel.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xylfe.cn/Article/details/gtlzwuzdwg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ivvv.top/Article/details/gtzzlzukbv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zycfv.cn/Article/details/gtnuikwbvj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.316326.xyz/Article/details/gtstcugwqa.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gtfwtgnfhs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258.top/Article/details/gtpxscuvqf.html

[N10] 链表节点定义
来源：http://dali.daxiang520.top/Article/details/gtksebhuts.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gaohongyu789.top/Article/details/gtawqoeyze.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnxiangtu.top/Article/details/gttrrmjojc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jyoumei.cn/Article/details/gtrmjygbeu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tianlin.xyz/Article/details/gtqdjzjxas.html

Java: class Node { int v; Node next; }
来源：http://dali.aibaodan.cn/Article/details/gtgzqcezlc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sxryk.cn/Article/details/gtbkerlgvh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhiwuduotai.top/Article/details/gtwxexubzv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yongpay.top/Article/details/gtcheggpvz.html

[N11] 二叉树中序遍历
来源：http://dali.tian-w.cn/Article/details/gtfijaybzq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ydzc1.top/Article/details/gtxgymrmeu.html

PHP:  // 手写递归函数
来源：http://dali.nanxinkj.top/Article/details/gtityranmx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gtbgrybfvj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gtodkjymwp.html

Java: // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gthuomewvm.html

Go:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gtiuxybqmi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jianghu66.top/Article/details/gtzbczsymt.html

C#:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtxaaciwtl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jlsjyb.cn/Article/details/gtzypffcto.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhongyouzk.top/Article/details/gtfzksogcv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhongyouzk.top/Article/details/gtrbwyicwa.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenzaomai.com/Article/details/gtknlnjzhk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sufxvd.cn/Article/details/gtxzirxphi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pycfn.com/Article/details/gtcfsvfmqv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.quarkkingdee.top/Article/details/gtmalvqsui.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenzaomai.com/Article/details/gtgpgodwkq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gtjmiavtey.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtmcoceyye.html

O. 并发与异步
来源：http://dali.wangdashe.top/Article/details/gtlmwdliqm.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtnzotdiop.html

[O01] 启动一个线程
来源：http://dali.yj202588.top/Article/details/gtekrntucj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cheryme.top/Article/details/gthbggriuo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xuetiantiany.cn/Article/details/gtifjmictr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhengqikj.top/Article/details/gtzvnuigne.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gtragfxehu.html

Java: new Thread(() -> f()).start()
来源：http://dali.jyoumei.cn/Article/details/gtrqohiruc.html

Go:   go f()
来源：http://dali.iojbl.cn/Article/details/gtrdypvaao.html

Ruby: Thread.new { f }
来源：http://dali.hfpthk.cn/Article/details/gtnfnbpfnk.html

C#:   Task.Run(() => F());
来源：http://dali.ppjwa.cn/Article/details/gtggwnmhgb.html

[O02] 使用线程池
来源：http://dali.jlsjyb.cn/Article/details/gtukkbowwr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj202588.top/Article/details/gtewlmagcp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj202588.top/Article/details/gtkrofhoic.html

JS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gtbcovfvoz.html

TS:   // worker_threads 线程池
来源：http://dali.sxryk.cn/Article/details/gtgwavodyw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jyoumei.cn/Article/details/gtuuqjqjbc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yanxiufei.cn/Article/details/gtwflnplde.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinqigufen.top/Article/details/gtijpflnns.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.wangdashe.top/Article/details/gtxjoqsibv.html

[O03] 加锁保护共享数据
来源：http://dali.aibaodan.cn/Article/details/gtzrfrksns.html

Py:   with lock: shared += 1
来源：http://dali.zhoulong.xyz/Article/details/gtbtelwndj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.quarkkingdee.top/Article/details/gtvpavsiol.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cdnleiting.top/Article/details/gtpuincbup.html

TS:   // 同 JS
来源：http://dali.pengpengdd.cyou/Article/details/gtnpuiigkv.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtxnigixdc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenlongwang.top/Article/details/gtnwbgteem.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.vqdsnc.cn/Article/details/gtndsyjzxo.html

C#:   lock (gate) { shared++; }
来源：http://dali.hfpthk.cn/Article/details/gtatiacghz.html

[O04] 定义异步函数并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbhfxfoa.html

Py:   async def f():⏎    await g()
来源：http://dali.shzxlz.cn/Article/details/gtbmbjzaur.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj202588.top/Article/details/gtozuyackd.html

JS:   async function f() { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gtzjikltds.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yongpay.top/Article/details/gtzpcstmsg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yanxiufei.cn/Article/details/gtbdlrztku.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj202588.top/Article/details/gtugtxfkln.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dianchejie.cn/Article/details/gtshdkflgx.html

C#:   async Task F() { await G(); }
来源：http://dali.gaohongyu789.top/Article/details/gtccsxppqp.html

[O05] 并发执行并等待全部完成
来源：http://dali.jianghu66.top/Article/details/gtfhdchfpa.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gttudqtplc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xziqi.cn/Article/details/gtcaruzjea.html

JS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gtluteerft.html

TS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gtnmarkwit.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuanzhike.top/Article/details/gtehmfxomh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj202588.top/Article/details/gtollnfyeq.html

Ruby: threads.map(&:join)
来源：http://dali.jianghu66.top/Article/details/gtbmbhaasu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.andypj.xyz/Article/details/gtdvmgycyx.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gtsxwmzisx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.9152youxi.cn/Article/details/gtkwajtngk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.havefunace.top/Article/details/gtnveqcgyv.html

JS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gttpcktzoi.html

TS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gtrxfjxamz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.mhx1999.top/Article/details/gthpdtyrla.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tanke756.top/Article/details/gtiuxhxdtu.html

Ruby: // fork 块
来源：http://dali.zhoulong.xyz/Article/details/gtqybcxror.html

C#:   Parallel.For
来源：http://dali.gaohongyu789.top/Article/details/gttbxjckpz.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtmjlzwpkk.html

P. 常用工具函数
来源：http://dali.wangdashe.top/Article/details/gtwhghppkc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtvouwrbcq.html

[P01] 生成 UUID
来源：http://dali.jinghuilouyu.cn/Article/details/gtctujlmth.html

Py:   str(uuid.uuid4())
来源：http://dali.jianghu66.top/Article/details/gtwuqwwezf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jqgfzy.top/Article/details/gtgfsmxtsz.html

JS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gtydddwtjm.html

TS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwywcgwzw.html

Java: UUID.randomUUID().toString()
来源：http://dali.shzxlz.cn/Article/details/gtwcivighe.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuxming.cn/Article/details/gtedanliim.html

Ruby: SecureRandom.uuid
来源：http://dali.xziqi.cn/Article/details/gtqtoproxc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.iojbl.cn/Article/details/gtrlpesmgm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfibkqdd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xinyue.icu/Article/details/gtudhesgka.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aizwys.cn/Article/details/gtehyiekuu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tanke756.top/Article/details/gtvwzeryfx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.vqdsnc.cn/Article/details/gtminsfezv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenlongwang.top/Article/details/gtkydhnpdx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cdnleiting.top/Article/details/gtmxkjqnka.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yanxiufei.cn/Article/details/gtvhqgvxvx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yongpay.top/Article/details/gtgpuvhujo.html

[P03] 生成短随机字符串
来源：http://dali.yvedp.cn/Article/details/gtfoblgwps.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ppjwa.cn/Article/details/gttudaseyv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnxiangtu.top/Article/details/gtygektzzx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gtwyvjdoqg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tianlin.xyz/Article/details/gtcyppjzrl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtoziyybne.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cheryme.top/Article/details/gtkiedvaih.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.guannengcc.top/Article/details/gtwsvuvddf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnoelctzb.html

[P04] 求长度
来源：http://dali.hfpthk.cn/Article/details/gtnghkftdz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xuetiantiany.cn/Article/details/gtriavvrog.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtfhdcemsk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.svipenyu.cn/Article/details/gtjshoxuzj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.316326.xyz/Article/details/gtcnkxzqnm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gttowngfxc.html

Go:   len(arr);  len(m)
来源：http://dali.zdqjudy.top/Article/details/gthxfwjpun.html

Ruby: x.length;  x.size
来源：http://dali.cucudq.cn/Article/details/gtosylcenx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.316326.xyz/Article/details/gtjqenelsn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.snrcjt.cn/Article/details/gtplwsuiqt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.316326.xyz/Article/details/gtkhhhfysd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhiwuduotai.top/Article/details/gtivmxwxwb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenzaomai.com/Article/details/gtvbjraoyh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gzhubu.top/Article/details/gtlsldjsgk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fengsongda.top/Article/details/gtobibahja.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dianchejie.cn/Article/details/gtmdsoqkmc.html

Ruby: a == b
来源：http://dali.jiagoushi.top/Article/details/gtyxlhhgpt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jiagoushi.top/Article/details/gtwyjmokja.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.quarkkingdee.top/Article/details/gtahlgwnuy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.daria6918.cn/Article/details/gttmgbbfiy.html

PHP:  if (empty($x)) {}
来源：http://dali.sxryk.cn/Article/details/gtqpxcnezn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jianghu66.top/Article/details/gtoqcgyhlx.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtjyqrdpxj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hammf.cn/Article/details/gtnckfjqqg.html

Go:   if x == nil {}
来源：http://dali.daxiang520.top/Article/details/gtwueukazx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhengqikj.top/Article/details/gturjxknhm.html

C#:   if (x is null) {}
来源：http://dali.0kj1m.cn/Article/details/gthaoctotc.html

[P07] 防抖与节流
来源：http://dali.hnxiangtu.top/Article/details/gtqljswnyn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xuetiantiany.cn/Article/details/gtoorhdetq.html

PHP:  // 手写时间戳比较
来源：http://dali.dashuyun.cn/Article/details/gtoduapkan.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gtkkdqlpfb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtjmbmjsvc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhengqikj.top/Article/details/gtxosxeaba.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xuetiantiany.cn/Article/details/gtufwrrebg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj20258.top/Article/details/gtmytlmpjw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hammf.cn/Article/details/gtnfvwslwm.html

[P08] 处理浮点精度问题
来源：http://dali.aizwys.cn/Article/details/gtuqopdzwn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xylfe.cn/Article/details/gtqgpbougy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigfzy.top/Article/details/gthckzgfue.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fengsongda.top/Article/details/gtiunnnjqu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gotoacloud.top/Article/details/gtwmnrjdcf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.iojbl.cn/Article/details/gtdjjmbxnh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.c1oappe.top/Article/details/gtjythnxsy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shuidangran.top/Article/details/gtbkeehghk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hfpthk.cn/Article/details/gtwrrmnybx.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtjyigansg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guowangkeji.top/Article/details/gtykgrummh.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtfppngnwb.html

[Q01] 创建表
来源：http://dali.havefunace.top/Article/details/gtvrhackxw.html

CREATE TABLE users (
来源：http://dali.haohaochexian.top/Article/details/gtaeyxpapl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xziqi.cn/Article/details/gtcpmuubsj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gtadinkdaa.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tanke756.top/Article/details/gtwuotmwlf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258888.top/Article/details/gtrsqyaemu.html

);
来源：http://dali.zdqjudy.top/Article/details/gtyeozdddr.html

[Q02] 创建带外键的表
来源：http://dali.birdmap.top/Article/details/gtlyaxynxd.html

CREATE TABLE orders (
来源：http://dali.hammf.cn/Article/details/gtjbnqkdym.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gtvtevgjpx.html

user_id INT NOT NULL,
来源：http://dali.yonumen.top/Article/details/gtlwsnfdny.html

amount DECIMAL(10, 2),
来源：http://dali.jqgufenzy.top/Article/details/gtnsvxztgn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ydzc1.top/Article/details/gtguepjqyf.html

);
来源：http://dali.yuxming.cn/Article/details/gtrbtsjemt.html

[Q03] 增加列
来源：http://dali.yangfankeji.com/Article/details/gtootqdaxk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hysaishi.cn/Article/details/gtjdmgtcsp.html

[Q04] 修改列类型
来源：http://dali.havefunace.top/Article/details/gtvnuvxqgi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cucudq.cn/Article/details/gtxiyhmdou.html

[Q05] 重命名列
来源：http://dali.cucudq.cn/Article/details/gtxonertag.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jiagoushi.top/Article/details/gtqqllmosp.html

[Q06] 删除列
来源：http://dali.mhx1999.top/Article/details/gthkvhxjjc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yangfankeji.com/Article/details/gtbroihusq.html

[Q07] 删除表
来源：http://dali.sxryk.cn/Article/details/gtcpnudafs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtqyfcfdgf.html

[Q08] 创建普通索引
来源：http://dali.ivvv.top/Article/details/gtscjpsceb.html


<!-- 参考信息 -->