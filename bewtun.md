代发 wailian999

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gzhubu.top/Article/details/gthrwgymzd.html

JS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gtxysardqb.html

TS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gtsbycitje.html

Java: System.err.println("err")
来源：http://dali.svipenyu.cn/Article/details/gtzqokzgnu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxuanxn.top/Article/details/gtmuqoiaoz.html

Ruby: warn "err"
来源：http://dali.xuetiantiany.cn/Article/details/gtcssfzdhz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxuanxn.top/Article/details/gtefoumrcb.html

[M07] 判断是否为主入口
来源：http://dali.wangdashe.top/Article/details/gtwcnquvei.html

Py:   if __name__ == "__main__":
来源：http://dali.9152youxi.cn/Article/details/gtbjalpdtn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gtkjynwcqq.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gtewiogigi.html

TS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gtfywjgyhw.html

Java: public static void main(String[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gttjrezsbj.html

Go:   func main()
来源：http://dali.shzxlz.cn/Article/details/gtadvkshxy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinqigufen.top/Article/details/gtcqflfdsf.html

C#:   static void Main(string[] args)
来源：http://dali.daria6918.cn/Article/details/gtkaqguhyb.html

[M08] 获取系统与运行时信息
来源：http://dali.tanke756.top/Article/details/gtwvlkqjmv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenlongwang.top/Article/details/gtlymmofpb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigufen.top/Article/details/gtibpqncbr.html

JS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtenpzbvea.html

TS:   process.platform;  process.version
来源：http://dali.svipenyu.cn/Article/details/gtnoiibbac.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.feifeiyinyue.top/Article/details/gtgmfypcfx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.redwolf501.top/Article/details/gtkbepbgtg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fengsongda.top/Article/details/gtjuufziym.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cucudq.cn/Article/details/gttcfhyfzn.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtskqmpfdj.html

N. 数据结构与算法
来源：http://dali.zhiwuduotai.top/Article/details/gtlsiebubm.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtbwzjgvyq.html

[N01] 二分查找（有序数组）
来源：http://dali.wangshuangyany.cn/Article/details/gtxtwgwjxp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtrnnwlrbc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj202588.top/Article/details/gtckkqbpcc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gtklbemyth.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gtmoufqxpa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtonzrpdnj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gteujdclxb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhongyouzk.top/Article/details/gtnsdbatie.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtxchyvhbo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.9152youxi.cn/Article/details/gtoluxbbnj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gotoacloud.top/Article/details/gtitrglbvj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnxiangtu.top/Article/details/gttqykxexz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtvkvhepbr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtlmmevscd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangdashe.top/Article/details/gtobuonerf.html

Go:   slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gtxoqkvqfu.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gtuwlimnqe.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cqqwz.cn/Article/details/gtzobsjmux.html

[N03] 快速排序（分治示例）
来源：http://dali.ybcxt.top/Article/details/gtzfmqbssj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.c1oappe.top/Article/details/gtmgzcwpgw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.feifeiyinyue.top/Article/details/gthicinjig.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sufxvd.cn/Article/details/gtxskikcnj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gtimlopsfq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenzaomai.com/Article/details/gtdkgcxsge.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yongpay.top/Article/details/gtqesnwyzu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zycfv.cn/Article/details/gtwyvramys.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.mhx1999.top/Article/details/gtslxgfomb.html

[N04] 斐波那契数列
来源：http://dali.meibo888.top/Article/details/gtmehljygn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gttydgiier.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhixingplan.top/Article/details/gtqrfojvva.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtokjzzteg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gtcsatilrw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hysaishi.cn/Article/details/gtgksbllpi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guowangkeji.top/Article/details/gtpydfcxdl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtjtjlgcmg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtnbhnouhz.html

[N05] 最大公约数
来源：http://dali.hnxiangtu.top/Article/details/gtexsbwmkk.html

Py:   math.gcd(a, b)
来源：http://dali.snrcjt.cn/Article/details/gtytguxbjq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ybcxt.top/Article/details/gtofufhocq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxuanxn.top/Article/details/gtkmzwnbnm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjrirzxcy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuanzhike.top/Article/details/gtswitznmq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.0kj1m.cn/Article/details/gtvcvfzama.html

Ruby: a.gcd(b)
来源：http://dali.sweek.top/Article/details/gtzybzsopw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.meibo888.top/Article/details/gtezqjhpar.html

[N06] 判断回文字符串
来源：http://dali.zycfv.cn/Article/details/gtpuckwdqz.html

Py:   s == s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gtyegsegcs.html

PHP:  $s === strrev($s);
来源：http://dali.daxiang520.top/Article/details/gtlnfpqklk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtodcdnaku.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gtbwmttytx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.daria6918.cn/Article/details/gtzndanjiq.html

Go:   // 双指针从两端比较
来源：http://dali.pengpengdd.cyou/Article/details/gtrrbfzynv.html

Ruby: s == s.reverse
来源：http://dali.jqgfzy.top/Article/details/gtrwnlaexh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gtvrffuhrg.html

[N07] 两数之和（返回下标）
来源：http://dali.sufxvd.cn/Article/details/gttazxormc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sufxvd.cn/Article/details/gtihdpqzzf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgfzy.top/Article/details/gtpvartvbo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xuanzx.com/Article/details/gtdvrhpexp.html

TS:   // 手写 Map<string, number>
来源：http://dali.nwbrower.top/Article/details/gtvibahbie.html

Java: // 手写 HashMap
来源：http://dali.jinqigufen.top/Article/details/gtzloqfuvz.html

Go:   // 手写 map[int]int
来源：http://dali.daxiang520.top/Article/details/gtbjrrddki.html

Ruby: // 手写 Hash
来源：http://dali.yueranfly.top/Article/details/gtazedeopc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gttbduseey.html

[N08] 生成全排列
来源：http://dali.zhoulong.xyz/Article/details/gtkrwhfpvv.html

Py:   itertools.permutations(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtcvthbplu.html

PHP:  // 手写递归交换
来源：http://dali.316326.xyz/Article/details/gtusjeqogm.html

JS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtgcrztezj.html

TS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtghjhfiqf.html

Java: // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtrdovewon.html

Go:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtumgxeqfw.html

Ruby: arr.permutation.to_a
来源：http://dali.yangfankeji.com/Article/details/gtqkcpivxv.html

C#:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gthttbysxy.html

[N09] 栈与队列
来源：http://dali.chenzaomai.com/Article/details/gtlhjpeatu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtuolijuoe.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtgiihjrdl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gtbwlvyuky.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ppjwa.cn/Article/details/gtwxbrxbxj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqyfemzrq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafoiirve.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gtzyguxuwd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ydzc1.top/Article/details/gtbgtwfrxp.html

[N10] 链表节点定义
来源：http://dali.feifeiyinyue.top/Article/details/gthvyvyxwx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yueranfly.top/Article/details/gtohgybvev.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xylfe.cn/Article/details/gtjarzvwfv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhoulong.xyz/Article/details/gtqcczcuwz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.c1oappe.top/Article/details/gtsvryoeto.html

Java: class Node { int v; Node next; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjctzazn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hysaishi.cn/Article/details/gtepcobuym.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xuanzx.com/Article/details/gtlvtjlajh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.mhx1999.top/Article/details/gtdfvpmril.html

[N11] 二叉树中序遍历
来源：http://dali.yj20258.top/Article/details/gtqmuhdrvz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yvedp.cn/Article/details/gtyobbcsxh.html

PHP:  // 手写递归函数
来源：http://dali.fengsongda.top/Article/details/gtybltybcm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gtzggbboln.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xylfe.cn/Article/details/gtpsniicbr.html

Java: // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtkgsizckv.html

Go:   // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gtxjykgien.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nanxuanxn.top/Article/details/gtmzswwgxt.html

C#:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtvpumosal.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jyoumei.cn/Article/details/gtcdxnmbri.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.guowangkeji.top/Article/details/gtjvvbuujh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.c1oappe.top/Article/details/gtvrudekuh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.snrcjt.cn/Article/details/gtdccrrgbc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gtuxafuwls.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gttrpcsuro.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.fengsongda.top/Article/details/gtvgbamodl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daxiang520.top/Article/details/gtqagsdmrk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tianlin.xyz/Article/details/gtgbhxmgpd.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtdedncewi.html

O. 并发与异步
来源：http://dali.jyoumei.cn/Article/details/gttxtodlen.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtbzaofqfp.html

[O01] 启动一个线程
来源：http://dali.sysykeji.top/Article/details/gtpbkgzpmy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aibaodan.cn/Article/details/gtqoaixsjq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphowzawz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yueranfly.top/Article/details/gtmclsdvfa.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gtjkswyigg.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258.top/Article/details/gtjokjsbgp.html

Go:   go f()
来源：http://dali.jyoumei.cn/Article/details/gtsjvjvcgs.html

Ruby: Thread.new { f }
来源：http://dali.sxryk.cn/Article/details/gtbzhctzwv.html

C#:   Task.Run(() => F());
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhkrjosa.html

[O02] 使用线程池
来源：http://dali.yuxming.cn/Article/details/gtbtembnfv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yonumen.top/Article/details/gtcnpxzvik.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cheryme.top/Article/details/gtjyywxeza.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigfzy.top/Article/details/gtqdxrhipc.html

TS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gtchbslnyg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258.top/Article/details/gtspfoswsz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenlongwang.top/Article/details/gtasqrebam.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.andypj.xyz/Article/details/gtlrupqeoc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ydzc1.top/Article/details/gtunsquxwy.html

[O03] 加锁保护共享数据
来源：http://dali.yangfankeji.com/Article/details/gttbqhqvvu.html

Py:   with lock: shared += 1
来源：http://dali.hammf.cn/Article/details/gtpdoyvrxv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cdnleiting.top/Article/details/gtbhyjnrqi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgfzy.top/Article/details/gtkdeubmec.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gthcxxhlix.html

Java: synchronized (this) { shared++; }
来源：http://dali.jyoumei.cn/Article/details/gtozzhaboo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zdqjudy.top/Article/details/gtfefmtwpm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxuanxn.top/Article/details/gtrdebfrvn.html

C#:   lock (gate) { shared++; }
来源：http://dali.jyoumei.cn/Article/details/gtbrpanchk.html

[O04] 定义异步函数并等待
来源：http://dali.ybcxt.top/Article/details/gtmmnqwqhk.html

Py:   async def f():⏎    await g()
来源：http://dali.svipenyu.cn/Article/details/gtmojkhsey.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.fengsongda.top/Article/details/gtrlyuaipl.html

JS:   async function f() { await g(); }
来源：http://dali.xuanzx.com/Article/details/gtbjntgyac.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sxryk.cn/Article/details/gtjnconvqx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinghuilouyu.cn/Article/details/gtutcgqrlu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sweek.top/Article/details/gtuunattne.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hywenlv.cn/Article/details/gtrvdarbjx.html

C#:   async Task F() { await G(); }
来源：http://dali.mhx1999.top/Article/details/gtsgnlwhrv.html

[O05] 并发执行并等待全部完成
来源：http://dali.gaohongyu789.top/Article/details/gtxelyqbcm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zdqjudy.top/Article/details/gtprcsnmqh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.0kj1m.cn/Article/details/gtsrpznahn.html

JS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gtlashuosx.html

TS:   await Promise.all(tasks)
来源：http://dali.chenlongwang.top/Article/details/gtlmmwwvre.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxuanxn.top/Article/details/gtfkxcowfi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zdqjudy.top/Article/details/gtysfbgdsd.html

Ruby: threads.map(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteezucyci.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.aibaodan.cn/Article/details/gttherhrwf.html

[O06] 使用进程池
来源：http://dali.jqgfzy.top/Article/details/gtrxlwcklb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daxiang520.top/Article/details/gtzfcpotzi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj20258888.top/Article/details/gtmuruukhk.html

JS:   // child_process / cluster 模块
来源：http://dali.ydzc1.top/Article/details/gtrlqlmwmx.html

TS:   // child_process / cluster 模块
来源：http://dali.guannengcc.top/Article/details/gtgjwnxofg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zycfv.cn/Article/details/gteftymnby.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xinyue.icu/Article/details/gtrcvgadty.html

Ruby: // fork 块
来源：http://dali.meibo888.top/Article/details/gtkebijpyg.html

C#:   Parallel.For
来源：http://dali.xuetiantiany.cn/Article/details/gtuiwrpoqk.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtpaanxbcg.html

P. 常用工具函数
来源：http://dali.hnxiangtu.top/Article/details/gtwaedhcta.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtrptqgojt.html

[P01] 生成 UUID
来源：http://dali.sweek.top/Article/details/gtgrarnkig.html

Py:   str(uuid.uuid4())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrrbuled.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.smart0.xyz/Article/details/gtswgmieja.html

JS:   crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gtzkwxkmcp.html

TS:   crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gtnimbmvea.html

Java: UUID.randomUUID().toString()
来源：http://dali.hfpthk.cn/Article/details/gtpxeyjjdm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.9152youxi.cn/Article/details/gtmuobiltf.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigufen.top/Article/details/gtwfxtsmpn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.fzhhl.top/Article/details/gtpfvdyxpn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daria6918.cn/Article/details/gtacwmusfc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hnqzz.top/Article/details/gtweilliev.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ybcxt.top/Article/details/gtkalqocgw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbyscqhl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gaohongyu789.top/Article/details/gtvydnfdin.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jyoumei.cn/Article/details/gtzgiehryu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.kuanghao11.cn/Article/details/gtpucggayt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ppjwa.cn/Article/details/gtpfdhklwp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.kuanghao11.cn/Article/details/gtpdkuduir.html

[P03] 生成短随机字符串
来源：http://dali.yuanzhike.top/Article/details/gtlzcokqbk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cashguo.top/Article/details/gtkfmxaoac.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.kuanghao11.cn/Article/details/gttfdxyvxt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gtfrqlglng.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtmryjlnyr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gotoacloud.top/Article/details/gtfykrmiom.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.redwolf501.top/Article/details/gtteysmfra.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinqigufen.top/Article/details/gtabyeblfe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuxming.cn/Article/details/gtmmbvrvzf.html

[P04] 求长度
来源：http://dali.feifeiyinyue.top/Article/details/gttayhrbuk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.birdmap.top/Article/details/gtzitbkgjx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtvdoftuen.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gtcukvffyy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.9152youxi.cn/Article/details/gtibguevoe.html

Java: list.size();  map.size();  s.length()
来源：http://dali.snrcjt.cn/Article/details/gtwcgzmeff.html

Go:   len(arr);  len(m)
来源：http://dali.zycfv.cn/Article/details/gtrbxtkgue.html

Ruby: x.length;  x.size
来源：http://dali.ehwqpu.com/Article/details/gtxwmttjkq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zdqjudy.top/Article/details/gthaphuheu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yanxiufei.cn/Article/details/gtinbmlwbg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.kuanghao11.cn/Article/details/gtehvwawkv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daria6918.cn/Article/details/gtphvsbcxr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhiwuduotai.top/Article/details/gtrlnicdkx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daxiang520.top/Article/details/gtsieadbig.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dianchejie.cn/Article/details/gtnjaadmyn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yonumen.top/Article/details/gtbutgwycy.html

Ruby: a == b
来源：http://dali.xuanzx.com/Article/details/gtgqpxmisn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gaohongyu789.top/Article/details/gtgxwlqamr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbszbvge.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jiagoushi.top/Article/details/gtfzfxhumv.html

PHP:  if (empty($x)) {}
来源：http://dali.aizwys.cn/Article/details/gticjwyiwk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cashguo.top/Article/details/gtyrrurwhd.html

TS:   if (x == null) {}
来源：http://dali.wangdashe.top/Article/details/gtmkkkkxzs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gtzupkdpvr.html

Go:   if x == nil {}
来源：http://dali.snrcjt.cn/Article/details/gtlcgboygj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nwbrower.top/Article/details/gtiaodrnhw.html

C#:   if (x is null) {}
来源：http://dali.aizwys.cn/Article/details/gtsfgdxprf.html

[P07] 防抖与节流
来源：http://dali.yanxiufei.cn/Article/details/gtznjuhqix.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daria6918.cn/Article/details/gtnastnoya.html

PHP:  // 手写时间戳比较
来源：http://dali.xuetiantiany.cn/Article/details/gtwxxapwcb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gtplfwziud.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gtghiuuozr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yueranfly.top/Article/details/gtzujmhtgw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhiwuduotai.top/Article/details/gtenetpren.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shuidangran.top/Article/details/gtgercmotj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnqzz.top/Article/details/gtqeyxpjzh.html

[P08] 处理浮点精度问题
来源：http://dali.sxryk.cn/Article/details/gtocjmolrr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.c1oappe.top/Article/details/gtjmyxcnqn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gaohongyu789.top/Article/details/gtnlfrjosy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hfpthk.cn/Article/details/gtluojixle.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gtxvvjfmro.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gthgvemctg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jiagoushi.top/Article/details/gtfesrtdza.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jqgfzy.top/Article/details/gtlbkfpjnn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gaohongyu789.top/Article/details/gtoqksrirw.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtrnjqoqev.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shzxlz.cn/Article/details/gtrdmqsjgi.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gttmwinufi.html

[Q01] 创建表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjalbpmd.html

CREATE TABLE users (
来源：http://dali.iojbl.cn/Article/details/gtvbyavbtr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gtcwuswvhx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gtovhmnjkm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.wangdashe.top/Article/details/gthabgrtok.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jqgufenzy.top/Article/details/gthqxbukje.html

);
来源：http://dali.mhx1999.top/Article/details/gtikwlmurp.html

[Q02] 创建带外键的表
来源：http://dali.nwbrower.top/Article/details/gtvgaxvhlr.html

CREATE TABLE orders (
来源：http://dali.shangyingyoupin.top/Article/details/gtzghtoikg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.bjfxy.top/Article/details/gtmbcbwbav.html

user_id INT NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gtfigwwoag.html

amount DECIMAL(10, 2),
来源：http://dali.zhiwuduotai.top/Article/details/gtjnlpmytw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenjidiqi.icu/Article/details/gtgvrmccbb.html

);
来源：http://dali.chenzaomai.com/Article/details/gtfazdvaiv.html

[Q03] 增加列
来源：http://dali.316326.xyz/Article/details/gtqlnqmljf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cqqwz.cn/Article/details/gtxkeudais.html

[Q04] 修改列类型
来源：http://dali.sysykeji.top/Article/details/gtdsmkqayy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnxiangtu.top/Article/details/gtrvsifhak.html

[Q05] 重命名列
来源：http://dali.ybcxt.top/Article/details/gtutigdxxx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gzhubu.top/Article/details/gtyzwwgalp.html

[Q06] 删除列
来源：http://dali.hammf.cn/Article/details/gtgsqroduu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ybcxt.top/Article/details/gtumhmioss.html

[Q07] 删除表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrawivfky.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shzxlz.cn/Article/details/gtqwtbrtdi.html

[Q08] 创建普通索引
来源：http://dali.quarkkingdee.top/Article/details/gtdgqgnxrl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tanke756.top/Article/details/gtxbqdyznu.html

[Q09] 创建唯一索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpapjvea.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gtoxtmfska.html

[Q10] 插入单行
来源：http://dali.hnxiangtu.top/Article/details/gtkwalwgij.html


<!-- 参考信息 -->