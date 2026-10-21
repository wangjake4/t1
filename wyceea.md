代发 wailian999

Py:   if __name__ == "__main__":
来源：http://dali.nanxuanxn.top/Article/details/gtlhucrajx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.bjfxy.top/Article/details/gthmgolunh.html

JS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gtdvtcermq.html

TS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gtknonyrhu.html

Java: public static void main(String[] args)
来源：http://dali.hammf.cn/Article/details/gtwdlskolf.html

Go:   func main()
来源：http://dali.jianghu66.top/Article/details/gtlvmzxtmm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yongpay.top/Article/details/gtcepqbndt.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gtndlriszg.html

[M08] 获取系统与运行时信息
来源：http://dali.dashuyun.cn/Article/details/gtpivjwgni.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajvpogtr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cucudq.cn/Article/details/gtshcqijtd.html

JS:   process.platform;  process.version
来源：http://dali.c1oappe.top/Article/details/gtyougzptm.html

TS:   process.platform;  process.version
来源：http://dali.gogol.net.cn/Article/details/gtdzusumks.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cashguo.top/Article/details/gtqshvomrb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.mhx1999.top/Article/details/gtqgnsbqyr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tianlin.xyz/Article/details/gtwiihbigt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guannengcc.top/Article/details/gtnsylhpis.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjozlrif.html

N. 数据结构与算法
来源：http://dali.hongshengwenyu.top/Article/details/gtyjytqxlu.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtmpdxxvhs.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxinkj.top/Article/details/gtpeujjjxj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtyklwprjh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cheryme.top/Article/details/gtvetaeywm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gtqrzgtdwj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gtnbzoxhll.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtmtbfidpj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtemkqflpb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sweek.top/Article/details/gtkgbdjbtr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtdszecqhw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gzhubu.top/Article/details/gtniowaply.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yanxiufei.cn/Article/details/gtkzhrvzav.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jianghu66.top/Article/details/gtsopllvpx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gtsmtcanfp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtqchguwgo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daria6918.cn/Article/details/gtjvkpwncv.html

Go:   slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtltyekpdr.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gtinmacaia.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jiagoushi.top/Article/details/gtrhaisvbn.html

[N03] 快速排序（分治示例）
来源：http://dali.c1oappe.top/Article/details/gtgyzcxsqt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hnxiangtu.top/Article/details/gtgojbtclm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangshuangyany.cn/Article/details/gtsqlqqwlu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gtgoodtnjt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tian-w.cn/Article/details/gtyxqnrzwt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.haohaochexian.top/Article/details/gtgyggopyw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dashuyun.cn/Article/details/gtqbluglmb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgnocgrz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangshuangyany.cn/Article/details/gtmizbrbdm.html

[N04] 斐波那契数列
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdcjjcxc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cdnleiting.top/Article/details/gtgqjitath.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hammf.cn/Article/details/gtdqmbspbh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtidehvoya.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gtrzrcawuq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gtwttzlovq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnxiangtu.top/Article/details/gtmwyiepyq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtkpxwcgav.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtymtofhie.html

[N05] 最大公约数
来源：http://dali.jqgufenzy.top/Article/details/gtyabtvtfz.html

Py:   math.gcd(a, b)
来源：http://dali.tianlin.xyz/Article/details/gteutkjuqm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cqqwz.cn/Article/details/gtmumgjdbo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gtlfszotrg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gogol.net.cn/Article/details/gtzdiduuaf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258.top/Article/details/gtierxyajl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dashuyun.cn/Article/details/gtmblwjpka.html

Ruby: a.gcd(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbousyvnh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sufxvd.cn/Article/details/gtppvmcxeq.html

[N06] 判断回文字符串
来源：http://dali.jyoumei.cn/Article/details/gtucespbly.html

Py:   s == s[::-1]
来源：http://dali.sysykeji.top/Article/details/gtqmylqpoo.html

PHP:  $s === strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gtauhqlwqd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtdufqrysf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtlxylcchq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtheifjseg.html

Go:   // 双指针从两端比较
来源：http://dali.ybcxt.top/Article/details/gtlmoxnzpt.html

Ruby: s == s.reverse
来源：http://dali.redwolf501.top/Article/details/gtzupfunxk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gtunxjrcwx.html

[N07] 两数之和（返回下标）
来源：http://dali.sxryk.cn/Article/details/gtaftasbes.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xylfe.cn/Article/details/gtyqakzcnx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ivvv.top/Article/details/gtxoeerfyx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnxiangtu.top/Article/details/gtebkldhan.html

TS:   // 手写 Map<string, number>
来源：http://dali.yueranfly.top/Article/details/gtfgdnnujk.html

Java: // 手写 HashMap
来源：http://dali.xinyue.icu/Article/details/gtdqritarq.html

Go:   // 手写 map[int]int
来源：http://dali.hfpthk.cn/Article/details/gtjiqvebvk.html

Ruby: // 手写 Hash
来源：http://dali.andypj.xyz/Article/details/gtyxmygnwi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aibaodan.cn/Article/details/gthzpehjan.html

[N08] 生成全排列
来源：http://dali.yvedp.cn/Article/details/gtaevnwivl.html

Py:   itertools.permutations(arr)
来源：http://dali.hnqzz.top/Article/details/gtkjefztxk.html

PHP:  // 手写递归交换
来源：http://dali.jqgufenzy.top/Article/details/gtvmqjpnzc.html

JS:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtuqajacyr.html

TS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtuchhaolh.html

Java: // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gthuddoavm.html

Go:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtzhbqmqbm.html

Ruby: arr.permutation.to_a
来源：http://dali.c1oappe.top/Article/details/gtvwemfrzj.html

C#:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtmxdruquz.html

[N09] 栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gtlifnghjp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guannengcc.top/Article/details/gtihysqrvb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtagphtwct.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gtqopdacbs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sufxvd.cn/Article/details/gtwlhocfxr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj202588.top/Article/details/gtcluwaoim.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpowierhq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtmaokjcbl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gogol.net.cn/Article/details/gtutcrvfik.html

[N10] 链表节点定义
来源：http://dali.xuanzx.com/Article/details/gtolifrtnw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.svipenyu.cn/Article/details/gtfavgryku.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.iojbl.cn/Article/details/gtcvoqhnra.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.dianchejie.cn/Article/details/gtrszcxkvy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.redwolf501.top/Article/details/gtnhvbzlhe.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzunwdsd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258.top/Article/details/gtyotwrqtk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.bjfxy.top/Article/details/gtnxxxymgr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xziqi.cn/Article/details/gtltizcsrz.html

[N11] 二叉树中序遍历
来源：http://dali.jyoumei.cn/Article/details/gtiozfmhnn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guannengcc.top/Article/details/gtmlxnuqha.html

PHP:  // 手写递归函数
来源：http://dali.yongpay.top/Article/details/gtdcuwpjpw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gtuczblryw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cheryme.top/Article/details/gtrrjmpcbq.html

Java: // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtwejfaiqm.html

Go:   // 手写递归
来源：http://dali.gzhubu.top/Article/details/gtjainvpwb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenlongwang.top/Article/details/gtsvtnhipq.html

C#:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtkcvuftpx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gtpztrpica.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daria6918.cn/Article/details/gtjtfgnrfi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hywenlv.cn/Article/details/gtzyltxvtu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gtxjxqkagp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gtgumqqzly.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gtlqxitpcq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxuanxn.top/Article/details/gttywyomyh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yongpay.top/Article/details/gtjqradcxe.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gtzgigukns.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtswrltmrs.html

O. 并发与异步
来源：http://dali.yongpay.top/Article/details/gtbjfgehmt.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtfcsaucey.html

[O01] 启动一个线程
来源：http://dali.guannengcc.top/Article/details/gtztjysjda.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xziqi.cn/Article/details/gtsceuzhlj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gotoacloud.top/Article/details/gtpmveomby.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shangyingyoupin.top/Article/details/gtuxmjdmwr.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gtuggqmxvm.html

Java: new Thread(() -> f()).start()
来源：http://dali.cheryme.top/Article/details/gtkgyhnpoa.html

Go:   go f()
来源：http://dali.sysykeji.top/Article/details/gtsnrlypma.html

Ruby: Thread.new { f }
来源：http://dali.yj202588.top/Article/details/gtaabxstqa.html

C#:   Task.Run(() => F());
来源：http://dali.xziqi.cn/Article/details/gtkotchazm.html

[O02] 使用线程池
来源：http://dali.jlsjyb.cn/Article/details/gtlldtkdal.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yuxming.cn/Article/details/gtyrrfzctt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.c1oappe.top/Article/details/gthkwihcqu.html

JS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gtbmuxjepo.html

TS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtvrvznbre.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258.top/Article/details/gtoamujrbf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.quarkkingdee.top/Article/details/gttzweeshc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqohkxze.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.pengpengdd.cyou/Article/details/gtpeeotyxa.html

[O03] 加锁保护共享数据
来源：http://dali.meibo888.top/Article/details/gtdyaisbra.html

Py:   with lock: shared += 1
来源：http://dali.smart0.xyz/Article/details/gtqnjupbwg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhiwuduotai.top/Article/details/gtiekdiiyr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gtgnyjklmn.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gtxlxsghwu.html

Java: synchronized (this) { shared++; }
来源：http://dali.zdqjudy.top/Article/details/gtchxdsbrj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvyrujhq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ppjwa.cn/Article/details/gtfdgbaupk.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gtnmjmhtxm.html

[O04] 定义异步函数并等待
来源：http://dali.pengpengdd.cyou/Article/details/gtheupvmwx.html

Py:   async def f():⏎    await g()
来源：http://dali.gotoacloud.top/Article/details/gtlxgbtkss.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sweek.top/Article/details/gtomjetzez.html

JS:   async function f() { await g(); }
来源：http://dali.xylfe.cn/Article/details/gtnmzfnxra.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nanxuanxn.top/Article/details/gtlpirvoee.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hysaishi.cn/Article/details/gttiyjfrla.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.kuanghao11.cn/Article/details/gtzvyhbaqa.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cucudq.cn/Article/details/gtwqkppmhn.html

C#:   async Task F() { await G(); }
来源：http://dali.shuidangran.top/Article/details/gtwfcjqrvl.html

[O05] 并发执行并等待全部完成
来源：http://dali.ivvv.top/Article/details/gtynzppldn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hfpthk.cn/Article/details/gtjquwzawu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shzxlz.cn/Article/details/gtntvvjkwh.html

JS:   await Promise.all(tasks)
来源：http://dali.jiagoushi.top/Article/details/gtidnldwmp.html

TS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gthiyaaksy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.meibo888.top/Article/details/gtqprnuzjb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ivvv.top/Article/details/gtkluytekg.html

Ruby: threads.map(&:join)
来源：http://dali.yueranfly.top/Article/details/gtcdgscahb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guannengcc.top/Article/details/gtbzbogura.html

[O06] 使用进程池
来源：http://dali.hfpthk.cn/Article/details/gtuumtugcu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258888.top/Article/details/gtdxgspedz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhixingplan.top/Article/details/gtmwmbxvpe.html

JS:   // child_process / cluster 模块
来源：http://dali.nanxuanxn.top/Article/details/gtbuzsnyqn.html

TS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gtqfimuyme.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwwlnejse.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.redwolf501.top/Article/details/gtihhxawzl.html

Ruby: // fork 块
来源：http://dali.xuetiantiany.cn/Article/details/gtibzbgrqk.html

C#:   Parallel.For
来源：http://dali.zhengqikj.top/Article/details/gtbxrcysyn.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxdnlrlu.html

P. 常用工具函数
来源：http://dali.zhongyouzk.top/Article/details/gtncptpjyp.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtwfwnireb.html

[P01] 生成 UUID
来源：http://dali.mhx1999.top/Article/details/gtmtzjygaf.html

Py:   str(uuid.uuid4())
来源：http://dali.tian-w.cn/Article/details/gtjujztuye.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj20258.top/Article/details/gtmlekogva.html

JS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gtmgozwvgw.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gtccvvzmld.html

Java: UUID.randomUUID().toString()
来源：http://dali.ppjwa.cn/Article/details/gtpmzrbkqr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.mhx1999.top/Article/details/gtbmtcrsdp.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigfzy.top/Article/details/gtjlksjzzr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenjidiqi.icu/Article/details/gteokufdbu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppwrtomy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cheryme.top/Article/details/gtqmtjzwcj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aibaodan.cn/Article/details/gtinjmwyxm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yangfankeji.com/Article/details/gtmkxdtfxh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.daxiang520.top/Article/details/gthedjhqhn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtqghnwewn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yueranfly.top/Article/details/gtgvsyroke.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenzaomai.com/Article/details/gtuhpxtqiw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhixingplan.top/Article/details/gtkoamtqxq.html

[P03] 生成短随机字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdmbjrrj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.haohaochexian.top/Article/details/gtrnaykxgt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tanke756.top/Article/details/gteyifczrb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gthtsetnus.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gtfvebxrwl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj20258888.top/Article/details/gtiptvxhzl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cucudq.cn/Article/details/gtoxzzwnop.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.c1oappe.top/Article/details/gthhqhmjyj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywinhjpk.html

[P04] 求长度
来源：http://dali.dianchejie.cn/Article/details/gttxmntlvy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zycfv.cn/Article/details/gtparvnbfr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gttnomhjbu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.316326.xyz/Article/details/gtjjiywamc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gthtzanblj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shzxlz.cn/Article/details/gtfmsspjwl.html

Go:   len(arr);  len(m)
来源：http://dali.yangfankeji.com/Article/details/gtgovqngtx.html

Ruby: x.length;  x.size
来源：http://dali.xuetiantiany.cn/Article/details/gtfxlstscv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sysykeji.top/Article/details/gtlmyyaneg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hongshengwenyu.top/Article/details/gtmyawyigy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yueranfly.top/Article/details/gtyfikmlem.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yongpay.top/Article/details/gtnonrrswf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sxryk.cn/Article/details/gtjtgrjhts.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fzhhl.top/Article/details/gtsfftoacl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.kuanghao11.cn/Article/details/gtdlfzstzj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwoabrvy.html

Ruby: a == b
来源：http://dali.tian-w.cn/Article/details/gturnlsano.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tanke756.top/Article/details/gtzoncdwrg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cucudq.cn/Article/details/gtrskrodxh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.9152youxi.cn/Article/details/gtaxrldjdh.html

PHP:  if (empty($x)) {}
来源：http://dali.hnqzz.top/Article/details/gtxlycopgp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.pycfn.com/Article/details/gtuihdjmpc.html

TS:   if (x == null) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtfbaxqwot.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jlsjyb.cn/Article/details/gtmlldyqck.html

Go:   if x == nil {}
来源：http://dali.aibaodan.cn/Article/details/gtfumjwtry.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.birdmap.top/Article/details/gtzcqviurk.html

C#:   if (x is null) {}
来源：http://dali.jinqigufen.top/Article/details/gtpzlxfids.html

[P07] 防抖与节流
来源：http://dali.yj202588.top/Article/details/gtlhibxycy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj20258.top/Article/details/gtdatxgbcg.html

PHP:  // 手写时间戳比较
来源：http://dali.hnxiangtu.top/Article/details/gtfrayirqz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gtaczajdcc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gtpmxfmtoh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.9152youxi.cn/Article/details/gtcprrczlk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbdficgo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigfzy.top/Article/details/gtwvpzbdaj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenjidiqi.icu/Article/details/gtxpzfjykj.html

[P08] 处理浮点精度问题
来源：http://dali.xuetiantiany.cn/Article/details/gtybrtcdje.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.smart0.xyz/Article/details/gtyrdrqqsm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpsdyjlm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj20258.top/Article/details/gttfcguqkn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtsbyresss.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tianlin.xyz/Article/details/gtcskeocuh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuxming.cn/Article/details/gtbntsuwzn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jyoumei.cn/Article/details/gtvoepvocy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cucudq.cn/Article/details/gttokhxnug.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbiwimcot.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yueranfly.top/Article/details/gtxxbccmqi.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtdavowcix.html

[Q01] 创建表
来源：http://dali.tanke756.top/Article/details/gtnoeeugyv.html

CREATE TABLE users (
来源：http://dali.yanxiufei.cn/Article/details/gthduzpbgl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sxryk.cn/Article/details/gthlfrgkoq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yueranfly.top/Article/details/gtattrfntm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztbjrxxs.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hammf.cn/Article/details/gtwwsekyde.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gtufytnejj.html

[Q02] 创建带外键的表
来源：http://dali.cashguo.top/Article/details/gtphkltqhu.html

CREATE TABLE orders (
来源：http://dali.havefunace.top/Article/details/gtzqowwion.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gzhubu.top/Article/details/gtvygtbagk.html

user_id INT NOT NULL,
来源：http://dali.ppjwa.cn/Article/details/gtvozvflvs.html

amount DECIMAL(10, 2),
来源：http://dali.zhiwuduotai.top/Article/details/gtepktmcsw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cheryme.top/Article/details/gtztiicgrl.html

);
来源：http://dali.zhengqikj.top/Article/details/gtwvjmbtww.html

[Q03] 增加列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpywcfgh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cdnleiting.top/Article/details/gtsfsmuqxk.html

[Q04] 修改列类型
来源：http://dali.zdqjudy.top/Article/details/gtsryqalha.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhengqikj.top/Article/details/gtmkndtaza.html

[Q05] 重命名列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkpayard.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.andypj.xyz/Article/details/gtoayovikl.html

[Q06] 删除列
来源：http://dali.chenzaomai.com/Article/details/gtdxbikhwd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtukukaomd.html

[Q07] 删除表
来源：http://dali.tanke756.top/Article/details/gtfdmlatxm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jyoumei.cn/Article/details/gtmraabwgm.html

[Q08] 创建普通索引
来源：http://dali.yuxming.cn/Article/details/gtaligsweh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gtofhfxyyd.html

[Q09] 创建唯一索引
来源：http://dali.jiagoushi.top/Article/details/gtvmejjjir.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.quarkkingdee.top/Article/details/gtncjomtuo.html

[Q10] 插入单行
来源：http://dali.zycfv.cn/Article/details/gtdvsirvkm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubbfzext.html

[Q11] 一次插入多行
来源：http://dali.xuanzx.com/Article/details/gtqxhiavsw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tanke756.top/Article/details/gtvqbvfvlw.html

[Q12] 插入后取自增 ID
来源：http://dali.chenjidiqi.icu/Article/details/gtfnmikqer.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ehwqpu.com/Article/details/gtckjhxuxb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shuidangran.top/Article/details/gtxgekdfbs.html

[Q13] 忽略重复插入
来源：http://dali.xinyue.icu/Article/details/gtdbxitarr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gtmkdawgql.html


<!-- 参考信息 -->