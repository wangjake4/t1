代发 wailian999

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hysaishi.cn/Article/details/gtwmaftcmr.html

Ruby: warn "err"
来源：http://dali.fengsongda.top/Article/details/gtslokpgvh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfelmiijq.html

[M07] 判断是否为主入口
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtvnvmhg.html

Py:   if __name__ == "__main__":
来源：http://dali.fzhhl.top/Article/details/gtrzttshwj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xinyue.icu/Article/details/gtzqthuoff.html

JS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gtxomindjo.html

TS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gtotllornw.html

Java: public static void main(String[] args)
来源：http://dali.ydzc1.top/Article/details/gtrqpyjwlg.html

Go:   func main()
来源：http://dali.9152youxi.cn/Article/details/gtavpipovs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacgcnvrk.html

C#:   static void Main(string[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gtynuomvpt.html

[M08] 获取系统与运行时信息
来源：http://dali.dianchejie.cn/Article/details/gtuqtjhfjy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuanzhike.top/Article/details/gtfkpjnhec.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fzhhl.top/Article/details/gthezcacnm.html

JS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtbxomwgea.html

TS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gtmnacyqwv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cucudq.cn/Article/details/gtyqvxnbka.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hongshengwenyu.top/Article/details/gtmdozdznd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgufenzy.top/Article/details/gtojhgyopn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangshuangyany.cn/Article/details/gtspgctwfz.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtdedoyili.html

N. 数据结构与算法
来源：http://dali.shuidangran.top/Article/details/gthxqzehir.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtxvrkgovt.html

[N01] 二分查找（有序数组）
来源：http://dali.guannengcc.top/Article/details/gtusfyeapt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtxlafehtm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sufxvd.cn/Article/details/gtgdxbygww.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gtalotglpz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtsfnlrgzc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtxghdjmyl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ybcxt.top/Article/details/gttqbkdghm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ivvv.top/Article/details/gtuepgxetk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlkblwkp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aizwys.cn/Article/details/gtxsqbkmet.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tanke756.top/Article/details/gtqinrygpr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cheryme.top/Article/details/gtvqhnbyxq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtclirlzrh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gtknesnvrb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tian-w.cn/Article/details/gtljipjjjd.html

Go:   slices.Sort(arr)
来源：http://dali.guannengcc.top/Article/details/gtngvkiomr.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gtsvkaujmo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.birdmap.top/Article/details/gtdduhahdu.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhcolsei.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yangfankeji.com/Article/details/gtahnskoln.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jiagoushi.top/Article/details/gtmqfzkomh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gtzmueylxq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gtkozsnxyu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuanzhike.top/Article/details/gtttamikct.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gotoacloud.top/Article/details/gtbwazjyjt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daxiang520.top/Article/details/gtjgpbpwbx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nwbrower.top/Article/details/gtqvoeslyc.html

[N04] 斐波那契数列
来源：http://dali.bjfxy.top/Article/details/gtxyzefhqz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dianchejie.cn/Article/details/gtfjutrzuu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqwubiee.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gtgvmsevzy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gtvjoaerev.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gtjcbjieno.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gzhubu.top/Article/details/gtvuceaxph.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.iojbl.cn/Article/details/gtxpucgqsb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gtfxeedpsv.html

[N05] 最大公约数
来源：http://dali.c1oappe.top/Article/details/gtmatdihcv.html

Py:   math.gcd(a, b)
来源：http://dali.hnqzz.top/Article/details/gtemdvptni.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cheryme.top/Article/details/gtbikjtbqo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtkkyrdxul.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.quarkkingdee.top/Article/details/gtgzdixzso.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.9152youxi.cn/Article/details/gtxcfhytqc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xylfe.cn/Article/details/gthyqcjapa.html

Ruby: a.gcd(b)
来源：http://dali.jinqigufen.top/Article/details/gtblzxxbnl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.havefunace.top/Article/details/gtqbaqolag.html

[N06] 判断回文字符串
来源：http://dali.tianlin.xyz/Article/details/gtxifjzbtr.html

Py:   s == s[::-1]
来源：http://dali.gogol.net.cn/Article/details/gtphyrmhfu.html

PHP:  $s === strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtxupjjxje.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtcqdkghmc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtjitgfnmu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.meibo888.top/Article/details/gtyvjgaxua.html

Go:   // 双指针从两端比较
来源：http://dali.ehwqpu.com/Article/details/gtvwjhpnvu.html

Ruby: s == s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gtunellzqg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gtbaycrjrp.html

[N07] 两数之和（返回下标）
来源：http://dali.shangyingyoupin.top/Article/details/gtciaxbtmd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jqgufenzy.top/Article/details/gtuasdqthn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yongpay.top/Article/details/gtboysdbzn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dashuyun.cn/Article/details/gtgzyhsrtg.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpaaybmks.html

Java: // 手写 HashMap
来源：http://dali.guowangkeji.top/Article/details/gtnwlagxyi.html

Go:   // 手写 map[int]int
来源：http://dali.yanxiufei.cn/Article/details/gtshrlsero.html

Ruby: // 手写 Hash
来源：http://dali.wangshuangyany.cn/Article/details/gtoqutwffs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dashuyun.cn/Article/details/gtsjwrzien.html

[N08] 生成全排列
来源：http://dali.jianghu66.top/Article/details/gtszdbevpp.html

Py:   itertools.permutations(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtofbhzbuq.html

PHP:  // 手写递归交换
来源：http://dali.cqqwz.cn/Article/details/gtdpqeaxwn.html

JS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtnkclfyuj.html

TS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtyfskhysh.html

Java: // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjkhaoxjs.html

Go:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtezhmpnns.html

Ruby: arr.permutation.to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvjcrzpm.html

C#:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtmudpmudq.html

[N09] 栈与队列
来源：http://dali.kuanghao11.cn/Article/details/gtlzfcrnkl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.mhx1999.top/Article/details/gtysqromiw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyojgjjdh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuxming.cn/Article/details/gtjcjchfrb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gaohongyu789.top/Article/details/gtulyjatke.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxinkj.top/Article/details/gtwjbzjdvq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.redwolf501.top/Article/details/gtmpigkhgk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtevbeclkp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhengqikj.top/Article/details/gtrakwsfkv.html

[N10] 链表节点定义
来源：http://dali.sweek.top/Article/details/gttlbvjacq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xziqi.cn/Article/details/gtshzmdjjx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.andypj.xyz/Article/details/gtqdccrhvj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yongpay.top/Article/details/gtwoxnozbu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dianchejie.cn/Article/details/gtfxpxrijr.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258.top/Article/details/gtvmdsnhfz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.dianchejie.cn/Article/details/gthtfesyeb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgfzy.top/Article/details/gtubxacmya.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnqzz.top/Article/details/gtdqixbyzv.html

[N11] 二叉树中序遍历
来源：http://dali.yueranfly.top/Article/details/gtfsgodyyt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.iojbl.cn/Article/details/gtdgnfbsnh.html

PHP:  // 手写递归函数
来源：http://dali.nwbrower.top/Article/details/gtrbcamygh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gtykjysnrh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gtukvomrah.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gtvbukowqg.html

Go:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtosvdveak.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangdashe.top/Article/details/gtjeovswoy.html

C#:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtkpqxyajy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnxiangtu.top/Article/details/gtqzysgtyl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sysykeji.top/Article/details/gtmhwnuves.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yangfankeji.com/Article/details/gtqsdsgxhs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hfpthk.cn/Article/details/gtsmolnvyc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gthmzyyrqo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gtarpfnquf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sysykeji.top/Article/details/gtymnulkiu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jlsjyb.cn/Article/details/gtetzvgwco.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gtkuzxdnsb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtvoedgmak.html

O. 并发与异步
来源：http://dali.guannengcc.top/Article/details/gtmlrhwmpx.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtrqkmmxvz.html

[O01] 启动一个线程
来源：http://dali.jinghuilouyu.cn/Article/details/gthjtmuidp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ppjwa.cn/Article/details/gtswrcvjvf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nwbrower.top/Article/details/gtkxznmbdz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.vqdsnc.cn/Article/details/gtjaektpjj.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gtutpqcmtt.html

Java: new Thread(() -> f()).start()
来源：http://dali.iojbl.cn/Article/details/gthwypvvjf.html

Go:   go f()
来源：http://dali.hnqzz.top/Article/details/gtmlctkbfm.html

Ruby: Thread.new { f }
来源：http://dali.hfpthk.cn/Article/details/gtbbdlfwcd.html

C#:   Task.Run(() => F());
来源：http://dali.gotoacloud.top/Article/details/gtbwisfcim.html

[O02] 使用线程池
来源：http://dali.sweek.top/Article/details/gtigscscdq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yueranfly.top/Article/details/gtindxzqoy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigufen.top/Article/details/gtqgmiqqok.html

JS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gtoxzlkqrg.html

TS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gtnfpfmzbs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jianghu66.top/Article/details/gtantsqaqm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tianlin.xyz/Article/details/gtusrjeazl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.iojbl.cn/Article/details/gtgtfxajmx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tianlin.xyz/Article/details/gtthvnatxy.html

[O03] 加锁保护共享数据
来源：http://dali.jqgufenzy.top/Article/details/gtwplatrvs.html

Py:   with lock: shared += 1
来源：http://dali.aizwys.cn/Article/details/gtkgnpseoz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sweek.top/Article/details/gtguppgmuz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.bjfxy.top/Article/details/gtkywpftup.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gtwmaypyvv.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gtnblvitvy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.redwolf501.top/Article/details/gtcreorbpb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.birdmap.top/Article/details/gtuygxtoqt.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigfzy.top/Article/details/gtitlinwnh.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcxyfjst.html

Py:   async def f():⏎    await g()
来源：http://dali.hnqzz.top/Article/details/gtrovnbgxs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenjidiqi.icu/Article/details/gtahvhcjyk.html

JS:   async function f() { await g(); }
来源：http://dali.smart0.xyz/Article/details/gtxiujbdpq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yongpay.top/Article/details/gtofwayybv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yanxiufei.cn/Article/details/gtrowtvahm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ydzc1.top/Article/details/gtpfaawwmj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daxiang520.top/Article/details/gtjparuqxk.html

C#:   async Task F() { await G(); }
来源：http://dali.chenlongwang.top/Article/details/gtrzvwgjuc.html

[O05] 并发执行并等待全部完成
来源：http://dali.hywenlv.cn/Article/details/gtttriobdq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tanke756.top/Article/details/gtxafozemt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuetiantiany.cn/Article/details/gtpfqgnkel.html

JS:   await Promise.all(tasks)
来源：http://dali.shzxlz.cn/Article/details/gtlwthhldg.html

TS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gtcckkwvos.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cqqwz.cn/Article/details/gtnulklbjy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pycfn.com/Article/details/gtyseitlbt.html

Ruby: threads.map(&:join)
来源：http://dali.yuxming.cn/Article/details/gtiyhgakpb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xinyue.icu/Article/details/gtjaocrqmy.html

[O06] 使用进程池
来源：http://dali.fengsongda.top/Article/details/gtcasrmmtm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj202588.top/Article/details/gtkhmaqbys.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zdqjudy.top/Article/details/gtpbdduthe.html

JS:   // child_process / cluster 模块
来源：http://dali.meibo888.top/Article/details/gtqxpxocnr.html

TS:   // child_process / cluster 模块
来源：http://dali.guannengcc.top/Article/details/gtvxhajztq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hfpthk.cn/Article/details/gtxvzwzfkc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.kuanghao11.cn/Article/details/gtkocvhgnh.html

Ruby: // fork 块
来源：http://dali.wangshuangyany.cn/Article/details/gtrobcuoyt.html

C#:   Parallel.For
来源：http://dali.ppjwa.cn/Article/details/gtwvjfwmpo.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gturvfoccp.html

P. 常用工具函数
来源：http://dali.gogol.net.cn/Article/details/gtftlzzoew.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtrehtadjo.html

[P01] 生成 UUID
来源：http://dali.jyoumei.cn/Article/details/gtwnjqstni.html

Py:   str(uuid.uuid4())
来源：http://dali.ppjwa.cn/Article/details/gtuwuixjpy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxuanxn.top/Article/details/gtbasaebec.html

JS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gtqruvbcid.html

TS:   crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gtdhgylakl.html

Java: UUID.randomUUID().toString()
来源：http://dali.xylfe.cn/Article/details/gtgbiqxkyt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.pycfn.com/Article/details/gtnqdxewhc.html

Ruby: SecureRandom.uuid
来源：http://dali.daxiang520.top/Article/details/gtrsazmseg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tian-w.cn/Article/details/gtslxgiwll.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigufen.top/Article/details/gtogwuapib.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tian-w.cn/Article/details/gtzrpfscjp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.quarkkingdee.top/Article/details/gtyawlgwvw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.bjfxy.top/Article/details/gtgvxbbttg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.feifeiyinyue.top/Article/details/gtsjuoyhyy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxinkj.top/Article/details/gtaheynsdb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtksfsqbjj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hnxiangtu.top/Article/details/gtpjkotmxx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shangyingyoupin.top/Article/details/gtisdfygmi.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gtnqhluows.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.feifeiyinyue.top/Article/details/gtycvtezew.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ydzc1.top/Article/details/gtgfawkvac.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gotoacloud.top/Article/details/gtuazutebr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtieaozacm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.kuanghao11.cn/Article/details/gtdtoqplsa.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nwbrower.top/Article/details/gtcybuhwnv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhengqikj.top/Article/details/gtzmavbesx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.svipenyu.cn/Article/details/gtygbmpayh.html

[P04] 求长度
来源：http://dali.guowangkeji.top/Article/details/gticxhezkf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.kuanghao11.cn/Article/details/gtvamfnrgf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtugfbzmnn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shzxlz.cn/Article/details/gtjxuavsoj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fengsongda.top/Article/details/gtpfcnrqtk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnqzz.top/Article/details/gtgduiasrt.html

Go:   len(arr);  len(m)
来源：http://dali.zhixingplan.top/Article/details/gtfjbqhhxs.html

Ruby: x.length;  x.size
来源：http://dali.sufxvd.cn/Article/details/gtfdrpnvha.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hammf.cn/Article/details/gtioyoixig.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yangfankeji.com/Article/details/gtwneklaba.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.316326.xyz/Article/details/gtnhmngwzu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.fzhhl.top/Article/details/gttofgjfnx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.andypj.xyz/Article/details/gtpyvdqyjb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvcwssov.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yuanzhike.top/Article/details/gtyhpsblsh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.fengsongda.top/Article/details/gtnnaetgkz.html

Ruby: a == b
来源：http://dali.xuetiantiany.cn/Article/details/gtknbezixp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinghuilouyu.cn/Article/details/gtssufcrqp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xuanzx.com/Article/details/gteclxmpvy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ydzc1.top/Article/details/gtncqdsyow.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gtqwbropaa.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinqigufen.top/Article/details/gthvcmpjok.html

TS:   if (x == null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpfzbcfi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gtcmnwaole.html

Go:   if x == nil {}
来源：http://dali.hywenlv.cn/Article/details/gtuymyggrt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dashuyun.cn/Article/details/gtvrpuwecz.html

C#:   if (x is null) {}
来源：http://dali.316326.xyz/Article/details/gtnecydlyt.html

[P07] 防抖与节流
来源：http://dali.kuanghao11.cn/Article/details/gtoiquzgsv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gogol.net.cn/Article/details/gtthpnipjn.html

PHP:  // 手写时间戳比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqmgylhp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gtsrdyvkwv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtopiwpsyz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cqqwz.cn/Article/details/gtbszomplu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.wangdashe.top/Article/details/gtoifuwwms.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gaohongyu789.top/Article/details/gtuyorktgc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tanke756.top/Article/details/gtvieiatto.html

[P08] 处理浮点精度问题
来源：http://dali.jqgufenzy.top/Article/details/gtbhxlbaqd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cashguo.top/Article/details/gtxuhdargu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtxniyzfkj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.9152youxi.cn/Article/details/gtgufydozq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gtszzarafp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.vqdsnc.cn/Article/details/gtlzirmylx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenlongwang.top/Article/details/gtxongjekv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ehwqpu.com/Article/details/gtxykojxpu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangtech.top/Article/details/gtiitndzhk.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtqspemzca.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xuetiantiany.cn/Article/details/gtiipnqnoe.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtrkwcjxsx.html

[Q01] 创建表
来源：http://dali.feifeiyinyue.top/Article/details/gtxurwwsip.html

CREATE TABLE users (
来源：http://dali.gotoacloud.top/Article/details/gtybvldztm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258.top/Article/details/gtirrouwiu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gtpwtpiqaj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sxryk.cn/Article/details/gtacvhruyf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cdnleiting.top/Article/details/gtiheeucve.html

);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrldobde.html

[Q02] 创建带外键的表
来源：http://dali.shzxlz.cn/Article/details/gthrjsybxc.html

CREATE TABLE orders (
来源：http://dali.ydzc1.top/Article/details/gtkapjwqiy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gtuhxpgqaf.html

user_id INT NOT NULL,
来源：http://dali.316326.xyz/Article/details/gtxzxjvgox.html

amount DECIMAL(10, 2),
来源：http://dali.316326.xyz/Article/details/gthfxvmigy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gtekjsalaj.html

);
来源：http://dali.svipenyu.cn/Article/details/gtmmgmklcf.html

[Q03] 增加列
来源：http://dali.hnxiangtu.top/Article/details/gtbyxvmzsr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.feifeiyinyue.top/Article/details/gtlbhobaft.html

[Q04] 修改列类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbffcbrc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cashguo.top/Article/details/gtsedhkxhs.html

[Q05] 重命名列
来源：http://dali.yongpay.top/Article/details/gtwlsrkjpq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nwbrower.top/Article/details/gtjpoxtmpz.html

[Q06] 删除列
来源：http://dali.zhoulong.xyz/Article/details/gttjwsxjnh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenlongwang.top/Article/details/gtovblbiiy.html

[Q07] 删除表
来源：http://dali.jyoumei.cn/Article/details/gtjaqvaxub.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xinyue.icu/Article/details/gttdmchnmk.html

[Q08] 创建普通索引
来源：http://dali.aizwys.cn/Article/details/gtnetpwrpw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gtjwnrjxkv.html

[Q09] 创建唯一索引
来源：http://dali.nanxinkj.top/Article/details/gtphsfpnns.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gtrjdjomze.html

[Q10] 插入单行
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhzsrxfe.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtezzwqpkh.html

[Q11] 一次插入多行
来源：http://dali.xziqi.cn/Article/details/gtadevccwc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdinyape.html

[Q12] 插入后取自增 ID
来源：http://dali.hfpthk.cn/Article/details/gthmscablf.html


<!-- 参考信息 -->