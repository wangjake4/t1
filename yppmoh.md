代发 wailian999

Ruby: exit 1
来源：http://dali.yangfankeji.com/Article/details/gtmanxmupt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgufenzy.top/Article/details/gtpnnzklyg.html

[M06] 向标准错误输出
来源：http://dali.zhiwuduotai.top/Article/details/gtviixmvbh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangshuangyany.cn/Article/details/gtodeuyroe.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfreypsh.html

JS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gttswnysmh.html

TS:   console.error("err")
来源：http://dali.nanxinkj.top/Article/details/gtijxlkbws.html

Java: System.err.println("err")
来源：http://dali.yonumen.top/Article/details/gtbsnfdpoc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shangyingyoupin.top/Article/details/gtzaarjdxf.html

Ruby: warn "err"
来源：http://dali.feifeiyinyue.top/Article/details/gtvvnbipqh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmohfqbhl.html

[M07] 判断是否为主入口
来源：http://dali.chenjidiqi.icu/Article/details/gtsfmksavx.html

Py:   if __name__ == "__main__":
来源：http://dali.dianchejie.cn/Article/details/gtagcshepk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxuanxn.top/Article/details/gtqgovfoxw.html

JS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gtuuxqperx.html

TS:   require.main === module
来源：http://dali.sweek.top/Article/details/gtwkzsfnxa.html

Java: public static void main(String[] args)
来源：http://dali.guannengcc.top/Article/details/gtkdwobwmd.html

Go:   func main()
来源：http://dali.cucudq.cn/Article/details/gtkrcuzrww.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.mhx1999.top/Article/details/gtfmmdsbvl.html

C#:   static void Main(string[] args)
来源：http://dali.guannengcc.top/Article/details/gtfiygihgg.html

[M08] 获取系统与运行时信息
来源：http://dali.tanke756.top/Article/details/gtgtoknesl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jianghu66.top/Article/details/gtkymcxhsj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yonumen.top/Article/details/gtbjytggmx.html

JS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtlgyoyvai.html

TS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtcdkpwyvg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxuanxn.top/Article/details/gtabruumzn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.feifeiyinyue.top/Article/details/gtbasfdluq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.quarkkingdee.top/Article/details/gtibvyobyz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxdpwjlex.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmddoass.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gttfzpwmqx.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtwrjrjgfe.html

[N01] 二分查找（有序数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygtzgngw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtwzuqzybo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtbgakjtmh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtgiwsngom.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gtxiprzotp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtcpicaqrm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtmbrnwdys.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jyoumei.cn/Article/details/gtgissyhcw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtxufoiehw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dashuyun.cn/Article/details/gtfdoldskc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gtjdjmjdvl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhongyouzk.top/Article/details/gthncfwigx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gthddnmlsm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gtzvvjcuwn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.iojbl.cn/Article/details/gtjkkrekxz.html

Go:   slices.Sort(arr)
来源：http://dali.0kj1m.cn/Article/details/gtfpvbjpkg.html

Ruby: arr.sort
来源：http://dali.yuanzhike.top/Article/details/gtydvjhvuv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sufxvd.cn/Article/details/gtvjdbefqq.html

[N03] 快速排序（分治示例）
来源：http://dali.iojbl.cn/Article/details/gtqaogpyvs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shangyingyoupin.top/Article/details/gtrxifqxkh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shangyingyoupin.top/Article/details/gtffeopqtb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gtmyyuwxkz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zdqjudy.top/Article/details/gtnwraucji.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.smart0.xyz/Article/details/gtpqppcsnm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dianchejie.cn/Article/details/gtpokqysmw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xylfe.cn/Article/details/gtvsibahdu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258888.top/Article/details/gtlecftnoz.html

[N04] 斐波那契数列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxldxnrz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gtehymvcda.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cqqwz.cn/Article/details/gtwkoeekah.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtorbumtag.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtzbberlya.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gtlokfnlgl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxuanxn.top/Article/details/gtyubyixlv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gtzodxumfo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtcpwvktfi.html

[N05] 最大公约数
来源：http://dali.sweek.top/Article/details/gtycgjjsnr.html

Py:   math.gcd(a, b)
来源：http://dali.zdqjudy.top/Article/details/gthulsgcrw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fengsongda.top/Article/details/gtgnvcanft.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gtrqkmqefu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jlsjyb.cn/Article/details/gthkucprvs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.9152youxi.cn/Article/details/gtqxrgynxc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daxiang520.top/Article/details/gteuexwcoe.html

Ruby: a.gcd(b)
来源：http://dali.jinqigufen.top/Article/details/gtmoqmqfli.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.snrcjt.cn/Article/details/gthdvcxbnk.html

[N06] 判断回文字符串
来源：http://dali.ydzc1.top/Article/details/gtrcgdkrvx.html

Py:   s == s[::-1]
来源：http://dali.yvedp.cn/Article/details/gticoegtvb.html

PHP:  $s === strrev($s);
来源：http://dali.fengsongda.top/Article/details/gttkunujra.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gtdjmfvjow.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtucriqtco.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuetiantiany.cn/Article/details/gtzuqudgqr.html

Go:   // 双指针从两端比较
来源：http://dali.guannengcc.top/Article/details/gtvnqsjkwj.html

Ruby: s == s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkydbmots.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gtdgnbtrwz.html

[N07] 两数之和（返回下标）
来源：http://dali.nanxuanxn.top/Article/details/gtjdmegkmr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.mhx1999.top/Article/details/gtbbcgoteh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.bjfxy.top/Article/details/gtakellftf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jiagoushi.top/Article/details/gtkvvydwva.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj202588.top/Article/details/gtcjbtgtpz.html

Java: // 手写 HashMap
来源：http://dali.hysaishi.cn/Article/details/gtaaxolcrn.html

Go:   // 手写 map[int]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoedjagfx.html

Ruby: // 手写 Hash
来源：http://dali.birdmap.top/Article/details/gtmdpxxxee.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gthgmstbfq.html

[N08] 生成全排列
来源：http://dali.mhx1999.top/Article/details/gtjeuyyyqc.html

Py:   itertools.permutations(arr)
来源：http://dali.guowangkeji.top/Article/details/gtfdkpnivh.html

PHP:  // 手写递归交换
来源：http://dali.tanke756.top/Article/details/gtedupcdpx.html

JS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtgffgvxts.html

TS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtbyhjivni.html

Java: // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtxrxweqxo.html

Go:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtlluryphs.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigufen.top/Article/details/gttyrnezqn.html

C#:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtnkfxpxft.html

[N09] 栈与队列
来源：http://dali.smart0.xyz/Article/details/gtikpkcvdo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.c1oappe.top/Article/details/gthtqmxfek.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.smart0.xyz/Article/details/gthflnbvzy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gtkokjigjr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gogol.net.cn/Article/details/gtunwixpfm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258888.top/Article/details/gtehbmfqqo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangdashe.top/Article/details/gtxfsulkdi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gtituhuspo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sweek.top/Article/details/gtpvoiyang.html

[N10] 链表节点定义
来源：http://dali.xziqi.cn/Article/details/gtyoshyhjc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daria6918.cn/Article/details/gtlhjaerjr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.c1oappe.top/Article/details/gtslmlfhab.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhengqikj.top/Article/details/gtxnciyyux.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dianchejie.cn/Article/details/gtqvjcslzx.html

Java: class Node { int v; Node next; }
来源：http://dali.cqqwz.cn/Article/details/gtfcopcjur.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ppjwa.cn/Article/details/gtjxcwzvhm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tianlin.xyz/Article/details/gtsnbkwjai.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xinyue.icu/Article/details/gtwedlzfyc.html

[N11] 二叉树中序遍历
来源：http://dali.yvedp.cn/Article/details/gtvrwzvyjj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sysykeji.top/Article/details/gtdfurcmvh.html

PHP:  // 手写递归函数
来源：http://dali.yuanzhike.top/Article/details/gthednkmjl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gtgxdpwtng.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yangfankeji.com/Article/details/gtxmomquui.html

Java: // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gttpkpkaqy.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gtmrmlaugz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.c1oappe.top/Article/details/gtwrhwrmio.html

C#:   // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gtuolrmmye.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.snrcjt.cn/Article/details/gtzzeruxdd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xuanzx.com/Article/details/gtankjrxbc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ivvv.top/Article/details/gtwvfyiocf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.snrcjt.cn/Article/details/gtijpssdds.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnxiangtu.top/Article/details/gtucucukdn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gtuuqiwayv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gtiflofavu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhongyouzk.top/Article/details/gtsqnxeveu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gtsnyukvlx.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtpqwufnba.html

O. 并发与异步
来源：http://dali.andypj.xyz/Article/details/gtjfwxzkhj.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtmfxmerig.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gtidrvnzoa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfvcyyrq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sxryk.cn/Article/details/gtyfbqdyim.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yanxiufei.cn/Article/details/gtdlhyvigj.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gtwkzrimdb.html

Java: new Thread(() -> f()).start()
来源：http://dali.zycfv.cn/Article/details/gtbmxcclqx.html

Go:   go f()
来源：http://dali.guannengcc.top/Article/details/gtdsafydcj.html

Ruby: Thread.new { f }
来源：http://dali.yonumen.top/Article/details/gtfsxoholx.html

C#:   Task.Run(() => F());
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmiatquqz.html

[O02] 使用线程池
来源：http://dali.bjfxy.top/Article/details/gtgsierejt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cashguo.top/Article/details/gtzrjesytu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xziqi.cn/Article/details/gtuzigxqvs.html

JS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gtoymbsntg.html

TS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gtwwehbcyp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.c1oappe.top/Article/details/gtuftkutzb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shzxlz.cn/Article/details/gttdqlhjqa.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cdnleiting.top/Article/details/gtoidptnar.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinghuilouyu.cn/Article/details/gtauyiddpu.html

[O03] 加锁保护共享数据
来源：http://dali.bjfxy.top/Article/details/gtksetxxln.html

Py:   with lock: shared += 1
来源：http://dali.vqdsnc.cn/Article/details/gtxdcqwzrw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangshuangyany.cn/Article/details/gtraqlofni.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.havefunace.top/Article/details/gtimhfvsqm.html

TS:   // 同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhiouizc.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwppwrkkb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sysykeji.top/Article/details/gtjfkputqh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pycfn.com/Article/details/gthxncwggz.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtlbfgezyi.html

[O04] 定义异步函数并等待
来源：http://dali.cucudq.cn/Article/details/gtuhxgxeox.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxuanxn.top/Article/details/gtapfqnwrp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sxryk.cn/Article/details/gtuixlyghz.html

JS:   async function f() { await g(); }
来源：http://dali.birdmap.top/Article/details/gtiaohdoxl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gzhubu.top/Article/details/gtizhqdxfe.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.smart0.xyz/Article/details/gtjxcplggx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dashuyun.cn/Article/details/gtixcqhryl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gogol.net.cn/Article/details/gtyarboryj.html

C#:   async Task F() { await G(); }
来源：http://dali.tianlin.xyz/Article/details/gtydizscvc.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhongyouzk.top/Article/details/gtvadfizri.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jlsjyb.cn/Article/details/gtykegxeda.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fzhhl.top/Article/details/gtdsqdthde.html

JS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gtonlsbmzt.html

TS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtluljecjx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ivvv.top/Article/details/gttlrupjdu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gaohongyu789.top/Article/details/gtyplhctxb.html

Ruby: threads.map(&:join)
来源：http://dali.pycfn.com/Article/details/gtmlixnjsr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.kuanghao11.cn/Article/details/gtsxrevymi.html

[O06] 使用进程池
来源：http://dali.yvedp.cn/Article/details/gtdhcrfopr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.kuanghao11.cn/Article/details/gtosnsxhec.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guowangkeji.top/Article/details/gtcbqmpxyw.html

JS:   // child_process / cluster 模块
来源：http://dali.quarkkingdee.top/Article/details/gtbrjpxxzw.html

TS:   // child_process / cluster 模块
来源：http://dali.havefunace.top/Article/details/gtqvvretdm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yongpay.top/Article/details/gtghuiwjkb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgufenzy.top/Article/details/gtwqhwvqgx.html

Ruby: // fork 块
来源：http://dali.yj20258888.top/Article/details/gtfdxnfbnb.html

C#:   Parallel.For
来源：http://dali.ivvv.top/Article/details/gtkgydlsjo.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtlogfzgja.html

P. 常用工具函数
来源：http://dali.9152youxi.cn/Article/details/gttnihpeaq.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtvgtfvnkg.html

[P01] 生成 UUID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccbqepvp.html

Py:   str(uuid.uuid4())
来源：http://dali.fzhhl.top/Article/details/gtrjzwzonx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jqgfzy.top/Article/details/gtzafzvogq.html

JS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gtqewmqvet.html

TS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gttkoxtpsj.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtcyepcpvw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj20258.top/Article/details/gtlskdnpjh.html

Ruby: SecureRandom.uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjzhjsxu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cdnleiting.top/Article/details/gtombhyvcc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhixingplan.top/Article/details/gtrcdntuar.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.bjfxy.top/Article/details/gtizgopkye.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.haohaochexian.top/Article/details/gtnnegvfvw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xinyue.icu/Article/details/gtaaaewynv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yongpay.top/Article/details/gthfjicezz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gtznpgmyrd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aizwys.cn/Article/details/gtiduwdzhv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yanxiufei.cn/Article/details/gthzvzxqqg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hammf.cn/Article/details/gtwfzqjywp.html

[P03] 生成短随机字符串
来源：http://dali.ydzc1.top/Article/details/gtbydhcjlq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.c1oappe.top/Article/details/gtjbrvetau.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shangyingyoupin.top/Article/details/gteqeianbn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.0kj1m.cn/Article/details/gtjelobbkw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgfzy.top/Article/details/gtkqjdwaol.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.birdmap.top/Article/details/gtkbkelusk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aibaodan.cn/Article/details/gtjxulgxdk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ybcxt.top/Article/details/gtztiyzhpb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daria6918.cn/Article/details/gtwgbrujhv.html

[P04] 求长度
来源：http://dali.nwbrower.top/Article/details/gtxsprsbsp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hywenlv.cn/Article/details/gtpqgdfpcb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtcbpzzffv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hongshengwenyu.top/Article/details/gtaevlczpd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gtbzdubqga.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigufen.top/Article/details/gtglohynun.html

Go:   len(arr);  len(m)
来源：http://dali.snrcjt.cn/Article/details/gtxoednejb.html

Ruby: x.length;  x.size
来源：http://dali.hywenlv.cn/Article/details/gtzicziijx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.dianchejie.cn/Article/details/gtdllniwnn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daria6918.cn/Article/details/gttzlrjlux.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sxryk.cn/Article/details/gtisguhyrf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sysykeji.top/Article/details/gtuotabxqm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ydzc1.top/Article/details/gtevqnozvg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gtcieljscv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yuanzhike.top/Article/details/gtadekodzk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gteahgrsdk.html

Ruby: a == b
来源：http://dali.gaohongyu789.top/Article/details/gtwgeweypl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nwbrower.top/Article/details/gtvrnqouse.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.feifeiyinyue.top/Article/details/gtppiyszti.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hysaishi.cn/Article/details/gtjfselnne.html

PHP:  if (empty($x)) {}
来源：http://dali.nanxuanxn.top/Article/details/gtaubxfppm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ehwqpu.com/Article/details/gtlzwaeyxh.html

TS:   if (x == null) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtjejjztlv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.0kj1m.cn/Article/details/gtpvsultpw.html

Go:   if x == nil {}
来源：http://dali.sweek.top/Article/details/gtfjmknqyl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.kuanghao11.cn/Article/details/gtmenebadz.html

C#:   if (x is null) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtlaszkclw.html

[P07] 防抖与节流
来源：http://dali.dashuyun.cn/Article/details/gtfkbgkvoj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.birdmap.top/Article/details/gtyyjziaxd.html

PHP:  // 手写时间戳比较
来源：http://dali.c1oappe.top/Article/details/gtkkbdxpjz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gttokvqrpc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gtxaflltne.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfewzyrb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sufxvd.cn/Article/details/gtfguunayd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jyoumei.cn/Article/details/gtxkaqlfnb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.redwolf501.top/Article/details/gtgvroxzqz.html

[P08] 处理浮点精度问题
来源：http://dali.cdnleiting.top/Article/details/gtznowuhjv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.c1oappe.top/Article/details/gtcsthwzlm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dianchejie.cn/Article/details/gtpxoqqcxu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shuidangran.top/Article/details/gtoaptmuun.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhiwuduotai.top/Article/details/gtpefkxiob.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenzaomai.com/Article/details/gtjgmvdfkk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuanzhike.top/Article/details/gthlofkxie.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenlongwang.top/Article/details/gtsmfqlqme.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sxryk.cn/Article/details/gtqfplpdvw.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtidgvijim.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.feifeiyinyue.top/Article/details/gtctypwvfn.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtqnhknnby.html

[Q01] 创建表
来源：http://dali.hywenlv.cn/Article/details/gtyhnzlzqa.html

CREATE TABLE users (
来源：http://dali.cdnleiting.top/Article/details/gtwxhnfvyr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxinkj.top/Article/details/gtfzqzjemx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nanxinkj.top/Article/details/gtvgoguhou.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ybcxt.top/Article/details/gthhepmleq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gtahqonxjs.html

);
来源：http://dali.chenjidiqi.icu/Article/details/gtrthjfukd.html

[Q02] 创建带外键的表
来源：http://dali.9152youxi.cn/Article/details/gtgwwysxao.html

CREATE TABLE orders (
来源：http://dali.redwolf501.top/Article/details/gtalsqhgjl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gtfgwjnhfp.html

user_id INT NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gtqovessxo.html

amount DECIMAL(10, 2),
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmppieult.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yvedp.cn/Article/details/gtvinxeylg.html

);
来源：http://dali.jyoumei.cn/Article/details/gtkzczzdoz.html

[Q03] 增加列
来源：http://dali.yonumen.top/Article/details/gtwxhzgllk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tanke756.top/Article/details/gtuszlhpoq.html

[Q04] 修改列类型
来源：http://dali.hnxiangtu.top/Article/details/gthofnghuw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gogol.net.cn/Article/details/gtxbzkrony.html

[Q05] 重命名列
来源：http://dali.jqgfzy.top/Article/details/gtacfretzw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.0kj1m.cn/Article/details/gtjwblgmsm.html

[Q06] 删除列
来源：http://dali.jyoumei.cn/Article/details/gtwtfovltm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tianlin.xyz/Article/details/gtgrsuufml.html

[Q07] 删除表
来源：http://dali.daria6918.cn/Article/details/gtfnymmphj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.pycfn.com/Article/details/gtpxoiahrq.html

[Q08] 创建普通索引
来源：http://dali.chenlongwang.top/Article/details/gtwakhrbbm.html


<!-- 参考信息 -->