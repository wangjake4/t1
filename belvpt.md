代发 wailian999

Ruby: exit 1
来源：http://dali.hammf.cn/Article/details/gtwutplmlb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jyoumei.cn/Article/details/gttwxltcon.html

[M06] 向标准错误输出
来源：http://dali.vqdsnc.cn/Article/details/gtbgkvllya.html

Py:   print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gtwvuvwiwg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zdqjudy.top/Article/details/gtigvpnqwc.html

JS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gtwdqdqpkc.html

TS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gtjrctpxav.html

Java: System.err.println("err")
来源：http://dali.jqgfzy.top/Article/details/gtzxiezaac.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnxiangtu.top/Article/details/gticxukbhl.html

Ruby: warn "err"
来源：http://dali.chenjidiqi.icu/Article/details/gteumtqfuz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtxokapeve.html

[M07] 判断是否为主入口
来源：http://dali.xziqi.cn/Article/details/gtstprnnsa.html

Py:   if __name__ == "__main__":
来源：http://dali.jinyuanbaomall.cn/Article/details/gttilbywfn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.snrcjt.cn/Article/details/gtmwydrkmv.html

JS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gtpbtgyhmb.html

TS:   require.main === module
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllieyqvs.html

Java: public static void main(String[] args)
来源：http://dali.cucudq.cn/Article/details/gtqjxfqgnf.html

Go:   func main()
来源：http://dali.yuxming.cn/Article/details/gterrlqrbj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hfpthk.cn/Article/details/gtyxpyypan.html

C#:   static void Main(string[] args)
来源：http://dali.tian-w.cn/Article/details/gtrfomscgv.html

[M08] 获取系统与运行时信息
来源：http://dali.chenlongwang.top/Article/details/gtsevdomel.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xylfe.cn/Article/details/gtuoeauiio.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.mhx1999.top/Article/details/gtwxbwwpdj.html

JS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gtbiuyznzg.html

TS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gtxhvsbzwi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shzxlz.cn/Article/details/gtkirxiamm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuetiantiany.cn/Article/details/gtzlvusrtx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.haohaochexian.top/Article/details/gtrtjvhcpx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ehwqpu.com/Article/details/gtwkxxkpyj.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtvbgugevg.html

N. 数据结构与算法
来源：http://dali.sufxvd.cn/Article/details/gtudpingva.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnssxxhu.html

[N01] 二分查找（有序数组）
来源：http://dali.pycfn.com/Article/details/gtsfptqacg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtmijkwvsy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tian-w.cn/Article/details/gtykorafwv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gtklampfvg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtbzscdgtd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtkqblmkvc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthiuyzake.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnqzz.top/Article/details/gtrunilfds.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtpmsogzwo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gogol.net.cn/Article/details/gtbmrfxhqj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jlsjyb.cn/Article/details/gteejjfoqb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgufenzy.top/Article/details/gthdrrlegy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gttfvrveaj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gtxflaemkr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.havefunace.top/Article/details/gtkdbaenni.html

Go:   slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtpqufsyqf.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gtdbjkcpcp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cqqwz.cn/Article/details/gtlyhwlbjw.html

[N03] 快速排序（分治示例）
来源：http://dali.yuanzhike.top/Article/details/gtjqlawzoi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.quarkkingdee.top/Article/details/gtsnraflqt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tanke756.top/Article/details/gturnpjays.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gtshccgbdo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.quarkkingdee.top/Article/details/gtfsttaojj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yongpay.top/Article/details/gtudncjgxs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ydzc1.top/Article/details/gtpdskcxbf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.redwolf501.top/Article/details/gthwyzqost.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hywenlv.cn/Article/details/gtjxwjgqtw.html

[N04] 斐波那契数列
来源：http://dali.xuetiantiany.cn/Article/details/gtncmwiorb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gtuiozvler.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuanzx.com/Article/details/gtaokkjppc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtfxfjgfkz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gtitybfrun.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zycfv.cn/Article/details/gtvhjtmbrq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jlsjyb.cn/Article/details/gtqlwifzzu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gtufwdjldn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtyhdrxruu.html

[N05] 最大公约数
来源：http://dali.hysaishi.cn/Article/details/gtrhavujgl.html

Py:   math.gcd(a, b)
来源：http://dali.mhx1999.top/Article/details/gtfcpyzlqw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbjjyrzt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gtkrpbqgxq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtqbhwtnkj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzdjyhbd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cdnleiting.top/Article/details/gtrwzivaru.html

Ruby: a.gcd(b)
来源：http://dali.gotoacloud.top/Article/details/gtgioonlkl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tianlin.xyz/Article/details/gtdlrymegy.html

[N06] 判断回文字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtudykxfqk.html

Py:   s == s[::-1]
来源：http://dali.nwbrower.top/Article/details/gtubaabtka.html

PHP:  $s === strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gtdltirwja.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtlwszgqro.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtmvchgvrk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hywenlv.cn/Article/details/gtlzrpasxz.html

Go:   // 双指针从两端比较
来源：http://dali.birdmap.top/Article/details/gtciclkfns.html

Ruby: s == s.reverse
来源：http://dali.316326.xyz/Article/details/gtgyvtnrag.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gtxjgpnkic.html

[N07] 两数之和（返回下标）
来源：http://dali.hongshengwenyu.top/Article/details/gtocmkokfh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jqgufenzy.top/Article/details/gtelpjuibh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yuanzhike.top/Article/details/gtwdsizuqy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglckzvcf.html

TS:   // 手写 Map<string, number>
来源：http://dali.aibaodan.cn/Article/details/gtdgvfhsze.html

Java: // 手写 HashMap
来源：http://dali.hongshengwenyu.top/Article/details/gthnxleewg.html

Go:   // 手写 map[int]int
来源：http://dali.mhx1999.top/Article/details/gtcjuurfha.html

Ruby: // 手写 Hash
来源：http://dali.nanxuanxn.top/Article/details/gtvlgmmrsd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cheryme.top/Article/details/gtcfubnyzl.html

[N08] 生成全排列
来源：http://dali.cdnleiting.top/Article/details/gtwpwobjvu.html

Py:   itertools.permutations(arr)
来源：http://dali.hnqzz.top/Article/details/gtaqniqejv.html

PHP:  // 手写递归交换
来源：http://dali.fzhhl.top/Article/details/gtlozasiic.html

JS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtzvquodcd.html

TS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtklacpnkc.html

Java: // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtuhuutinq.html

Go:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtksubwozo.html

Ruby: arr.permutation.to_a
来源：http://dali.yj202588.top/Article/details/gtupfhwruo.html

C#:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtrjddfxfj.html

[N09] 栈与队列
来源：http://dali.ppjwa.cn/Article/details/gtfawiaynk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxinkj.top/Article/details/gtqcnlgczm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtrhlpenuq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gthfhugweb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtoolrblzk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gogol.net.cn/Article/details/gtadfqeufl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.dianchejie.cn/Article/details/gtgyjnmcod.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gtmsuvbyzi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.snrcjt.cn/Article/details/gtedddlfvk.html

[N10] 链表节点定义
来源：http://dali.mhx1999.top/Article/details/gtzownslfj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hnxiangtu.top/Article/details/gtsxkmbheu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.daria6918.cn/Article/details/gtoekxzprl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aibaodan.cn/Article/details/gtxvortbst.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.316326.xyz/Article/details/gtqeuwngzc.html

Java: class Node { int v; Node next; }
来源：http://dali.xuanzx.com/Article/details/gtgllkfiha.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.smart0.xyz/Article/details/gtzreoarqj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ydzc1.top/Article/details/gtojqnipel.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.andypj.xyz/Article/details/gtxwkmgtzx.html

[N11] 二叉树中序遍历
来源：http://dali.zhoulong.xyz/Article/details/gtloaxruvl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ivvv.top/Article/details/gtdppizeuo.html

PHP:  // 手写递归函数
来源：http://dali.vqdsnc.cn/Article/details/gtzhfmgamz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cashguo.top/Article/details/gtdrxbinmq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcpgoiuy.html

Java: // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gtenczwpji.html

Go:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtkapgetkt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.quarkkingdee.top/Article/details/gtvbzqrwzs.html

C#:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gtwhfvyqqu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258888.top/Article/details/gtqmcwimzy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jyoumei.cn/Article/details/gtbewwhico.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ybcxt.top/Article/details/gtxrduzcff.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gtznvztvch.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtsyhzbtxm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gtuphtprga.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.mhx1999.top/Article/details/gtxapyucrn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ivvv.top/Article/details/gttxpnpqjt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.316326.xyz/Article/details/gtopqqhlmm.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchmxofst.html

O. 并发与异步
来源：http://dali.hfpthk.cn/Article/details/gtoknjgmiv.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtarowfsiz.html

[O01] 启动一个线程
来源：http://dali.0kj1m.cn/Article/details/gtdhjlisoq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhiwuduotai.top/Article/details/gtkpjdbdwz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tianlin.xyz/Article/details/gtymiwkcls.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigufen.top/Article/details/gtusuoizgc.html

TS:   // 同 JS
来源：http://dali.ehwqpu.com/Article/details/gtpgpopgtd.html

Java: new Thread(() -> f()).start()
来源：http://dali.shzxlz.cn/Article/details/gttdhlgufy.html

Go:   go f()
来源：http://dali.cucudq.cn/Article/details/gtmlofrddy.html

Ruby: Thread.new { f }
来源：http://dali.sweek.top/Article/details/gtilnschuo.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gtowvksnfp.html

[O02] 使用线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnvkqylj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.snrcjt.cn/Article/details/gtreqfaiyf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.havefunace.top/Article/details/gtskcueyzc.html

JS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gtqsislnzs.html

TS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gtmkpavwbu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhongyouzk.top/Article/details/gtubyrvegt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yvedp.cn/Article/details/gtygbinale.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxovdrjhp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shuidangran.top/Article/details/gtvzoscasi.html

[O03] 加锁保护共享数据
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufeyjqtk.html

Py:   with lock: shared += 1
来源：http://dali.daxiang520.top/Article/details/gtivqhfust.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenjidiqi.icu/Article/details/gtdktljesk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cashguo.top/Article/details/gtcnbqhfsq.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gtsdcxysgr.html

Java: synchronized (this) { shared++; }
来源：http://dali.tian-w.cn/Article/details/gtkjvjarbj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258.top/Article/details/gtwjxoabdm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.birdmap.top/Article/details/gtbpueblra.html

C#:   lock (gate) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtgxbxttmy.html

[O04] 定义异步函数并等待
来源：http://dali.zycfv.cn/Article/details/gtkczepwfe.html

Py:   async def f():⏎    await g()
来源：http://dali.meibo888.top/Article/details/gtqhqotanj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinqigufen.top/Article/details/gtndigbsno.html

JS:   async function f() { await g(); }
来源：http://dali.iojbl.cn/Article/details/gtmjxqtkdx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jqgufenzy.top/Article/details/gtsqjjkevo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daxiang520.top/Article/details/gtbxvhpcyl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xziqi.cn/Article/details/gtmjdylghc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.9152youxi.cn/Article/details/gtxtzvxbjj.html

C#:   async Task F() { await G(); }
来源：http://dali.zhengqikj.top/Article/details/gtyupgzqar.html

[O05] 并发执行并等待全部完成
来源：http://dali.daria6918.cn/Article/details/gtkowfxadu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ppjwa.cn/Article/details/gtcrxkvbtm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.9152youxi.cn/Article/details/gtooecrfpw.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gtafnrkunf.html

TS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gtilmhufoi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenzaomai.com/Article/details/gttojhsaaq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.birdmap.top/Article/details/gtxnjfyppd.html

Ruby: threads.map(&:join)
来源：http://dali.fengsongda.top/Article/details/gtmwojxefj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigfzy.top/Article/details/gtzcgilmdb.html

[O06] 使用进程池
来源：http://dali.sysykeji.top/Article/details/gtjhzlhgac.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cashguo.top/Article/details/gtlroejrdg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tanke756.top/Article/details/gtmcwmzjfm.html

JS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gthhkzqmgo.html

TS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gtotjdldil.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gtzthgprak.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jlsjyb.cn/Article/details/gtwenxpzfj.html

Ruby: // fork 块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqavdcbw.html

C#:   Parallel.For
来源：http://dali.daxiang520.top/Article/details/gtczhtltdm.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtmbwyxfvx.html

P. 常用工具函数
来源：http://dali.ppjwa.cn/Article/details/gtuyxkuunz.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtrbaqwvhm.html

[P01] 生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gtygukniaw.html

Py:   str(uuid.uuid4())
来源：http://dali.hywenlv.cn/Article/details/gtxunydifk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhongyouzk.top/Article/details/gtfznoausj.html

JS:   crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gtqkarudbo.html

TS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtyawmxhlg.html

Java: UUID.randomUUID().toString()
来源：http://dali.cashguo.top/Article/details/gtwghoescb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yueranfly.top/Article/details/gtwzrpdvkd.html

Ruby: SecureRandom.uuid
来源：http://dali.ppjwa.cn/Article/details/gtrzqoyzsk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.0kj1m.cn/Article/details/gtfnknakzr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.0kj1m.cn/Article/details/gtgutdfexi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.dashuyun.cn/Article/details/gtbxnanptz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcejmvdtn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.kuanghao11.cn/Article/details/gtinqouuyy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.kuanghao11.cn/Article/details/gtprmhqpxc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tianlin.xyz/Article/details/gtprtqtxmd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.316326.xyz/Article/details/gtuzfdjxhv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258888.top/Article/details/gtgtgmnjqz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.guowangkeji.top/Article/details/gtphnaimml.html

[P03] 生成短随机字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkptffpv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hammf.cn/Article/details/gtzkxtxvad.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.fzhhl.top/Article/details/gtjfhviseq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.0kj1m.cn/Article/details/gtctfbpphc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gtfficzcvh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.316326.xyz/Article/details/gtflzpuzir.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhiwuduotai.top/Article/details/gtlmjsogra.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.bjfxy.top/Article/details/gtutbpingp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cashguo.top/Article/details/gtchxfvjpw.html

[P04] 求长度
来源：http://dali.havefunace.top/Article/details/gtdzxjvrsb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hnqzz.top/Article/details/gtmfecawvm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtepiacbye.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gtxrcqjhna.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zycfv.cn/Article/details/gttqtxlpso.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jyoumei.cn/Article/details/gtmtewqnad.html

Go:   len(arr);  len(m)
来源：http://dali.hongshengwenyu.top/Article/details/gtjkqoddwx.html

Ruby: x.length;  x.size
来源：http://dali.xinyue.icu/Article/details/gtayfjnfqd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sweek.top/Article/details/gtarhneayw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdbfbukn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yuxming.cn/Article/details/gtlmdkdqdb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jyoumei.cn/Article/details/gtxgkyofdi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gogol.net.cn/Article/details/gtxbcotuml.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.snrcjt.cn/Article/details/gtcllmtrnt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.vqdsnc.cn/Article/details/gthlndfkdd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.iojbl.cn/Article/details/gtbvuqsyto.html

Ruby: a == b
来源：http://dali.dianchejie.cn/Article/details/gthebuqbbl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258888.top/Article/details/gtmghbtmsq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nanxuanxn.top/Article/details/gtdtrzpmqs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.haohaochexian.top/Article/details/gtbsrhbiba.html

PHP:  if (empty($x)) {}
来源：http://dali.gogol.net.cn/Article/details/gtkkjntobh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.fzhhl.top/Article/details/gtwqeacrqc.html

TS:   if (x == null) {}
来源：http://dali.fzhhl.top/Article/details/gtnvmhgpec.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gtaxrxrftv.html

Go:   if x == nil {}
来源：http://dali.tian-w.cn/Article/details/gtxpqmpazy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shuidangran.top/Article/details/gtyhyxasii.html

C#:   if (x is null) {}
来源：http://dali.nanxinkj.top/Article/details/gtztlgeicf.html

[P07] 防抖与节流
来源：http://dali.birdmap.top/Article/details/gtmnfdbfcg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yonumen.top/Article/details/gtdqyvqgxs.html

PHP:  // 手写时间戳比较
来源：http://dali.cashguo.top/Article/details/gtlxknerre.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zycfv.cn/Article/details/gthhaoeojb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gtshfgvazt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fzhhl.top/Article/details/gtqwfowpdz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pengpengdd.cyou/Article/details/gtknydhcro.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.andypj.xyz/Article/details/gtlxwynzwu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.iojbl.cn/Article/details/gtcfvngzpr.html

[P08] 处理浮点精度问题
来源：http://dali.hnxiangtu.top/Article/details/gtwwbmaykm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sxryk.cn/Article/details/gtajusocmy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtvbilqifb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hongshengwenyu.top/Article/details/gtrfxnqedc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.meibo888.top/Article/details/gtonkcxtkf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.dianchejie.cn/Article/details/gteycsluwo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sysykeji.top/Article/details/gtslomhtaw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.vqdsnc.cn/Article/details/gtoohvtuwa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tian-w.cn/Article/details/gtqwsbcfak.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gttwosihlk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprdipivi.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtjyfofrqv.html

[Q01] 创建表
来源：http://dali.ehwqpu.com/Article/details/gtirsgdeto.html

CREATE TABLE users (
来源：http://dali.wangdashe.top/Article/details/gtivxczfaq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gtzslbtiry.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gtagxmyinn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.snrcjt.cn/Article/details/gtastbfebi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdccoalib.html

);
来源：http://dali.cqqwz.cn/Article/details/gtyuldkiym.html

[Q02] 创建带外键的表
来源：http://dali.yongpay.top/Article/details/gtgjalfklk.html

CREATE TABLE orders (
来源：http://dali.wangdashe.top/Article/details/gtttdbwgcq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pengpengdd.cyou/Article/details/gthgyrozkh.html

user_id INT NOT NULL,
来源：http://dali.nanxinkj.top/Article/details/gtoxeaffjv.html

amount DECIMAL(10, 2),
来源：http://dali.quarkkingdee.top/Article/details/gtteiufpqk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenzaomai.com/Article/details/gtcyqwqgzp.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gthpzwnnnb.html

[Q03] 增加列
来源：http://dali.havefunace.top/Article/details/gtbgnxxyga.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.kuanghao11.cn/Article/details/gtzyhqelbb.html

[Q04] 修改列类型
来源：http://dali.birdmap.top/Article/details/gttqaelqlm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenzaomai.com/Article/details/gtwunwduyj.html

[Q05] 重命名列
来源：http://dali.jqgfzy.top/Article/details/gtqacveuhz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sufxvd.cn/Article/details/gtljqdppeb.html

[Q06] 删除列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylfmjnsd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shzxlz.cn/Article/details/gtuidpbgcp.html

[Q07] 删除表
来源：http://dali.redwolf501.top/Article/details/gtwpnbtyob.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aizwys.cn/Article/details/gtgjbshulk.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrlpxfzm.html


<!-- 参考信息 -->