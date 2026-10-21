代发 wailian999

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.9152youxi.cn/Article/details/gtyzsoumys.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gtpzciemki.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hysaishi.cn/Article/details/gtzugxqzxq.html

[M07] 判断是否为主入口
来源：http://dali.yuxming.cn/Article/details/gtbapkpqle.html

Py:   if __name__ == "__main__":
来源：http://dali.tianlin.xyz/Article/details/gtncffdkpw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yonumen.top/Article/details/gtbshacyjj.html

JS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gtcbdgmqkm.html

TS:   require.main === module
来源：http://dali.yvedp.cn/Article/details/gtzhhrdnko.html

Java: public static void main(String[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gtbqlqxnjh.html

Go:   func main()
来源：http://dali.pengpengdd.cyou/Article/details/gtevstuqgu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.pengpengdd.cyou/Article/details/gtazrgofyu.html

C#:   static void Main(string[] args)
来源：http://dali.zhongyouzk.top/Article/details/gtytubhjjj.html

[M08] 获取系统与运行时信息
来源：http://dali.birdmap.top/Article/details/gtesrjvzmw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ivvv.top/Article/details/gtjyplzbrz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenzaomai.com/Article/details/gtvncaehmg.html

JS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gtymljisdr.html

TS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtacexupzq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shangyingyoupin.top/Article/details/gtrwnkranv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ehwqpu.com/Article/details/gtsiuxecsu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daxiang520.top/Article/details/gtczsprsxn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258888.top/Article/details/gtcmzmlstz.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtieinjgcv.html

N. 数据结构与算法
来源：http://dali.fzhhl.top/Article/details/gtetajvape.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtgjefywbw.html

[N01] 二分查找（有序数组）
来源：http://dali.zhoulong.xyz/Article/details/gtdmryfuat.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtjtqlyyyr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.birdmap.top/Article/details/gtubukonnq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sxryk.cn/Article/details/gtfypivziz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gtpibjxjpq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlbegokc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtxjojvlws.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxuanxn.top/Article/details/gtzpyrlonk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtavcxvrvt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pengpengdd.cyou/Article/details/gtyaboigqt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gtihlpdmcm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xinyue.icu/Article/details/gtpcmqzotx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gtbipdezga.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gteaeaalhs.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pycfn.com/Article/details/gtnxwrjjwv.html

Go:   slices.Sort(arr)
来源：http://dali.svipenyu.cn/Article/details/gtvsmdldsg.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gtrfglscso.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.snrcjt.cn/Article/details/gtmkuztpwg.html

[N03] 快速排序（分治示例）
来源：http://dali.jqgufenzy.top/Article/details/gthkkekxag.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pengpengdd.cyou/Article/details/gtlnekabsj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fzhhl.top/Article/details/gtszqexyjn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gtwbykvglc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gtfprmspzx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ivvv.top/Article/details/gtitghuwqi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daxiang520.top/Article/details/gtdhzegymw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.mhx1999.top/Article/details/gtqijtaxkr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.svipenyu.cn/Article/details/gtwugbvyky.html

[N04] 斐波那契数列
来源：http://dali.hnqzz.top/Article/details/gtgbpebuwq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jiagoushi.top/Article/details/gttpjmqanh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gtyarwjdyg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gtbpmfbfbd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gtwpbqbkvh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangdashe.top/Article/details/gtalytmjsh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj202588.top/Article/details/gtgfciacur.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdyiftag.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyutgybzu.html

[N05] 最大公约数
来源：http://dali.hammf.cn/Article/details/gtfrkgfuti.html

Py:   math.gcd(a, b)
来源：http://dali.cucudq.cn/Article/details/gtvuraotot.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj202588.top/Article/details/gtficjjbhz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gtnrynixlk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gtxwlnodln.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nwbrower.top/Article/details/gtgyqxgmym.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hfpthk.cn/Article/details/gtvrywvgfb.html

Ruby: a.gcd(b)
来源：http://dali.yvedp.cn/Article/details/gtihzuumqd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ivvv.top/Article/details/gtpofftcsb.html

[N06] 判断回文字符串
来源：http://dali.yj20258.top/Article/details/gttzjzkscg.html

Py:   s == s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gtejhhvnzy.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtrledoynp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtkerqsvqt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtkpbydmcv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jiagoushi.top/Article/details/gtfujfzsyu.html

Go:   // 双指针从两端比较
来源：http://dali.zhongyouzk.top/Article/details/gtthyuiayb.html

Ruby: s == s.reverse
来源：http://dali.ehwqpu.com/Article/details/gtykfscywv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gtdjefibmd.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgfzy.top/Article/details/gtfstuywmb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhongyouzk.top/Article/details/gtjpadjklu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.snrcjt.cn/Article/details/gtgadcnjdv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aibaodan.cn/Article/details/gtajnspqxl.html

TS:   // 手写 Map<string, number>
来源：http://dali.aizwys.cn/Article/details/gtplwwphiw.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsdsjkax.html

Go:   // 手写 map[int]int
来源：http://dali.chenzaomai.com/Article/details/gtqjkrwtnh.html

Ruby: // 手写 Hash
来源：http://dali.hywenlv.cn/Article/details/gtwzuzcawv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenjidiqi.icu/Article/details/gtgbuxtlsd.html

[N08] 生成全排列
来源：http://dali.ehwqpu.com/Article/details/gtlgnsqxqy.html

Py:   itertools.permutations(arr)
来源：http://dali.cucudq.cn/Article/details/gtotkmvqyf.html

PHP:  // 手写递归交换
来源：http://dali.xuetiantiany.cn/Article/details/gtatmdkgvy.html

JS:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtjschedts.html

TS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtgyjxbjku.html

Java: // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtjfrytoid.html

Go:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtpqcjtndy.html

Ruby: arr.permutation.to_a
来源：http://dali.jianghu66.top/Article/details/gtqjbtcfxc.html

C#:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtihawsidi.html

[N09] 栈与队列
来源：http://dali.fzhhl.top/Article/details/gtuljftmjd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xziqi.cn/Article/details/gtbwvnjqyq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.pycfn.com/Article/details/gtwalvendb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtgetriwtx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hywenlv.cn/Article/details/gtancikvxv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dashuyun.cn/Article/details/gtxjethgid.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cdnleiting.top/Article/details/gttusvncrm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gtdrwmjlok.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenlongwang.top/Article/details/gttzzexiux.html

[N10] 链表节点定义
来源：http://dali.nwbrower.top/Article/details/gtsbwvwsqt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jianghu66.top/Article/details/gtfuwomrag.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.quarkkingdee.top/Article/details/gtxkrwuplk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtruzyqxkc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cqqwz.cn/Article/details/gtifkcaoiy.html

Java: class Node { int v; Node next; }
来源：http://dali.hywenlv.cn/Article/details/gthyjfqaeg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ehwqpu.com/Article/details/gtjdiritxv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zycfv.cn/Article/details/gtbjfamsyh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xinyue.icu/Article/details/gttdzyambf.html

[N11] 二叉树中序遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxcuhkxk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fengsongda.top/Article/details/gtflsdpzgi.html

PHP:  // 手写递归函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjxeathz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gtiskncvwo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gttauohzlu.html

Java: // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gtflamzvra.html

Go:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gtklufqmld.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aibaodan.cn/Article/details/gtawevlnsq.html

C#:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gtifclpwoh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdyuhvmiv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.snrcjt.cn/Article/details/gtvomxvlxl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gzhubu.top/Article/details/gtnmlbyrzm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gtbhbqolfq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gtesluseip.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzslkwht.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hongshengwenyu.top/Article/details/gtwvywkzro.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xinyue.icu/Article/details/gtfxdmckkz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.smart0.xyz/Article/details/gtbwqdchym.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtinenzdqm.html

O. 并发与异步
来源：http://dali.mhx1999.top/Article/details/gtneofgjgn.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtymqdyatj.html

[O01] 启动一个线程
来源：http://dali.sufxvd.cn/Article/details/gtqzxolyij.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.svipenyu.cn/Article/details/gtawityzxt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shzxlz.cn/Article/details/gtlevuahbz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nwbrower.top/Article/details/gtwujanftw.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtrlskklfu.html

Java: new Thread(() -> f()).start()
来源：http://dali.cucudq.cn/Article/details/gtbgfhwjzj.html

Go:   go f()
来源：http://dali.cheryme.top/Article/details/gtdkfbtuyb.html

Ruby: Thread.new { f }
来源：http://dali.daxiang520.top/Article/details/gtfryqikrb.html

C#:   Task.Run(() => F());
来源：http://dali.zhengqikj.top/Article/details/gtphjflroc.html

[O02] 使用线程池
来源：http://dali.yonumen.top/Article/details/gtzjrmclwm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqojlwxd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuitcoezn.html

JS:   // worker_threads 线程池
来源：http://dali.hammf.cn/Article/details/gtgoqobctn.html

TS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gtmzhogbgd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhixingplan.top/Article/details/gthxrzqugx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yangfankeji.com/Article/details/gtjjqoaibd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hongshengwenyu.top/Article/details/gtfekntmgk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.0kj1m.cn/Article/details/gtdwdvzlbu.html

[O03] 加锁保护共享数据
来源：http://dali.ybcxt.top/Article/details/gtyvrbnydl.html

Py:   with lock: shared += 1
来源：http://dali.vqdsnc.cn/Article/details/gtmhmhbkwm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ydzc1.top/Article/details/gtsmmwgxmw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.bjfxy.top/Article/details/gtkheobkwn.html

TS:   // 同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gtdnznpxkt.html

Java: synchronized (this) { shared++; }
来源：http://dali.zycfv.cn/Article/details/gthqzgwdsg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ppjwa.cn/Article/details/gtymhtptff.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnqzz.top/Article/details/gtstsuwznn.html

C#:   lock (gate) { shared++; }
来源：http://dali.daxiang520.top/Article/details/gtuzjzgkzl.html

[O04] 定义异步函数并等待
来源：http://dali.birdmap.top/Article/details/gtxhstfxhw.html

Py:   async def f():⏎    await g()
来源：http://dali.hysaishi.cn/Article/details/gtdygbewgm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ivvv.top/Article/details/gtgdsmrviq.html

JS:   async function f() { await g(); }
来源：http://dali.guannengcc.top/Article/details/gtzxffcywg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj202588.top/Article/details/gtkvgjrcfc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258.top/Article/details/gtjjmzykmc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yongpay.top/Article/details/gtfhuhwfti.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yueranfly.top/Article/details/gtzyzzvyrt.html

C#:   async Task F() { await G(); }
来源：http://dali.wangdashe.top/Article/details/gttxlrbbxd.html

[O05] 并发执行并等待全部完成
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpxmrvbo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daria6918.cn/Article/details/gtijlvdkds.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cheryme.top/Article/details/gtxrdpqrli.html

JS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gtipuszslb.html

TS:   await Promise.all(tasks)
来源：http://dali.zhongyouzk.top/Article/details/gtpmtfhpiz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pengpengdd.cyou/Article/details/gtufnlzmvm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.bjfxy.top/Article/details/gteshbwmvf.html

Ruby: threads.map(&:join)
来源：http://dali.9152youxi.cn/Article/details/gthydsagvb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yueranfly.top/Article/details/gtqkyfozfh.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gtnzglxeve.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shangyingyoupin.top/Article/details/gtsgzlrpys.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hongshengwenyu.top/Article/details/gtslflymke.html

JS:   // child_process / cluster 模块
来源：http://dali.andypj.xyz/Article/details/gtxbtckfcw.html

TS:   // child_process / cluster 模块
来源：http://dali.chenzaomai.com/Article/details/gtnpuggvta.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwqsxbgn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.havefunace.top/Article/details/gtoqvomzcf.html

Ruby: // fork 块
来源：http://dali.vqdsnc.cn/Article/details/gtqjeyjcyt.html

C#:   Parallel.For
来源：http://dali.hnqzz.top/Article/details/gtacnmckhy.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtehrzryfy.html

P. 常用工具函数
来源：http://dali.zhongyouzk.top/Article/details/gtgrkfxhez.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtjtrmbqie.html

[P01] 生成 UUID
来源：http://dali.daria6918.cn/Article/details/gtnoffenbf.html

Py:   str(uuid.uuid4())
来源：http://dali.jyoumei.cn/Article/details/gtlihrxbae.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangdashe.top/Article/details/gtfgflyzop.html

JS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gtjmrracgg.html

TS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxlmeibbd.html

Java: UUID.randomUUID().toString()
来源：http://dali.pycfn.com/Article/details/gtyxyjgbuo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.haohaochexian.top/Article/details/gtrvykgdph.html

Ruby: SecureRandom.uuid
来源：http://dali.tianlin.xyz/Article/details/gtsiuhusyu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcasbkrg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ybcxt.top/Article/details/gtjqalabxg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.mhx1999.top/Article/details/gtyanmjvix.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.andypj.xyz/Article/details/gtsntsrckd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jqgufenzy.top/Article/details/gteqhpwgsk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aizwys.cn/Article/details/gtdinmejkj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xinyue.icu/Article/details/gtvrcfjume.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.vqdsnc.cn/Article/details/gtlhuzujkc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtambytfmw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aibaodan.cn/Article/details/gtolpqpxrg.html

[P03] 生成短随机字符串
来源：http://dali.wangdashe.top/Article/details/gtoxpqqeeo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sysykeji.top/Article/details/gtmftbvybd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aizwys.cn/Article/details/gthjsvdfqx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gtdnvnjnxk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrjdgmyg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigfzy.top/Article/details/gtkbrjddwk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.havefunace.top/Article/details/gtmkercaur.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.aibaodan.cn/Article/details/gtnmomexpg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daxiang520.top/Article/details/gtdhixfmco.html

[P04] 求长度
来源：http://dali.yonumen.top/Article/details/gtzjsgjwzk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhongyouzk.top/Article/details/gtgkzxgsbw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtofsouckb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gtqmhysixm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.haohaochexian.top/Article/details/gtguiwcuun.html

Java: list.size();  map.size();  s.length()
来源：http://dali.pycfn.com/Article/details/gtmfswbxpj.html

Go:   len(arr);  len(m)
来源：http://dali.cqqwz.cn/Article/details/gtvlvpnmkg.html

Ruby: x.length;  x.size
来源：http://dali.sxryk.cn/Article/details/gtcknnjekc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.dianchejie.cn/Article/details/gtmfgqpsfd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.birdmap.top/Article/details/gtnazgbhsj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.quarkkingdee.top/Article/details/gtckyculzi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cdnleiting.top/Article/details/gttgyfxqxq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daxiang520.top/Article/details/gtncrlzxmx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zycfv.cn/Article/details/gtucmrierz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dashuyun.cn/Article/details/gtyargygvh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtssbscwfo.html

Ruby: a == b
来源：http://dali.nanxuanxn.top/Article/details/gtwgnuxamd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jyoumei.cn/Article/details/gtnfdenhvm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zycfv.cn/Article/details/gtgeuoejcm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sweek.top/Article/details/gtlhnsgcfa.html

PHP:  if (empty($x)) {}
来源：http://dali.gzhubu.top/Article/details/gtbyxbedok.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gotoacloud.top/Article/details/gtxkaevosv.html

TS:   if (x == null) {}
来源：http://dali.gotoacloud.top/Article/details/gtbtgrjblg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gtruuukxbg.html

Go:   if x == nil {}
来源：http://dali.zdqjudy.top/Article/details/gttymtljnp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.pengpengdd.cyou/Article/details/gtxoosoowv.html

C#:   if (x is null) {}
来源：http://dali.chenzaomai.com/Article/details/gthlnyurqq.html

[P07] 防抖与节流
来源：http://dali.yj20258888.top/Article/details/gteyfpavzu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sysykeji.top/Article/details/gtpghmvrdd.html

PHP:  // 手写时间戳比较
来源：http://dali.shuidangran.top/Article/details/gtrjlxaybp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gtbrdhbiqq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtmomqtpcv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtbdwxoqbs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jyoumei.cn/Article/details/gtwhgjymed.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.guannengcc.top/Article/details/gtllwtwxws.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.mhx1999.top/Article/details/gtumjzvyca.html

[P08] 处理浮点精度问题
来源：http://dali.yj20258888.top/Article/details/gtfiblvbtq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.feifeiyinyue.top/Article/details/gtdwefkavc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.smart0.xyz/Article/details/gtukxphzbu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yanxiufei.cn/Article/details/gtkiyrlwqh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenzaomai.com/Article/details/gtjtupwkyo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yanxiufei.cn/Article/details/gtxcgfwfqe.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nwbrower.top/Article/details/gtvwfohqkz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.daria6918.cn/Article/details/gtnrivohyl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258.top/Article/details/gtnwhpolgo.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtbfwhjctj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.316326.xyz/Article/details/gtiswyrqxm.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwthanto.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gtpfvluriy.html

CREATE TABLE users (
来源：http://dali.xinyue.icu/Article/details/gtsubwaehz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gtghpnexuf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ybcxt.top/Article/details/gttqsveweh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.iojbl.cn/Article/details/gtnlkajooj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.mhx1999.top/Article/details/gtxtggnwui.html

);
来源：http://dali.havefunace.top/Article/details/gtnkctvruu.html

[Q02] 创建带外键的表
来源：http://dali.gaohongyu789.top/Article/details/gtrawnxqrc.html

CREATE TABLE orders (
来源：http://dali.yuxming.cn/Article/details/gttgbganmo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gtgajkskac.html

user_id INT NOT NULL,
来源：http://dali.aibaodan.cn/Article/details/gtszptnpwk.html

amount DECIMAL(10, 2),
来源：http://dali.sysykeji.top/Article/details/gtvntaxowz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shangyingyoupin.top/Article/details/gtftdgwlht.html

);
来源：http://dali.gaohongyu789.top/Article/details/gtygrgyjzq.html

[Q03] 增加列
来源：http://dali.guannengcc.top/Article/details/gtwsrotoaw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.vqdsnc.cn/Article/details/gtywaupvbr.html

[Q04] 修改列类型
来源：http://dali.yonumen.top/Article/details/gtrnkituty.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xuetiantiany.cn/Article/details/gtkoualodp.html

[Q05] 重命名列
来源：http://dali.dashuyun.cn/Article/details/gtittpfxqb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.kuanghao11.cn/Article/details/gtiejlbmwv.html

[Q06] 删除列
来源：http://dali.shangyingyoupin.top/Article/details/gtqxtxczwq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sufxvd.cn/Article/details/gtwtytrbbj.html

[Q07] 删除表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbgsqbuz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.dashuyun.cn/Article/details/gthkpvwujr.html

[Q08] 创建普通索引
来源：http://dali.hywenlv.cn/Article/details/gtnqucnnha.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gtnlwbfelb.html

[Q09] 创建唯一索引
来源：http://dali.ybcxt.top/Article/details/gtvwwgpjzc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdllnuzjb.html

[Q10] 插入单行
来源：http://dali.daxiang520.top/Article/details/gtkwllzsbf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yvedp.cn/Article/details/gtpluxcrgm.html

[Q11] 一次插入多行
来源：http://dali.svipenyu.cn/Article/details/gtjuovfygo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.c1oappe.top/Article/details/gtbgtvlpdd.html

[Q12] 插入后取自增 ID
来源：http://dali.hywenlv.cn/Article/details/gtrghpximy.html


<!-- 参考信息 -->