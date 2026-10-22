代发 wailian999

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fzhhl.top/Article/details/gtsarmzwlm.html

Ruby: warn "err"
来源：http://dali.shzxlz.cn/Article/details/gtjeuapjql.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zycfv.cn/Article/details/gtrvibbzaw.html

[M07] 判断是否为主入口
来源：http://dali.zhongyouzk.top/Article/details/gtqcfnjpcr.html

Py:   if __name__ == "__main__":
来源：http://dali.xylfe.cn/Article/details/gtnbbexiak.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnxiangtu.top/Article/details/gtapkcvbmy.html

JS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gtplmviilj.html

TS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gtvcpeehkf.html

Java: public static void main(String[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gtxxzxfshm.html

Go:   func main()
来源：http://dali.xinyue.icu/Article/details/gtbgxjknva.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dashuyun.cn/Article/details/gtbwzobtnu.html

C#:   static void Main(string[] args)
来源：http://dali.haohaochexian.top/Article/details/gtxpvijrde.html

[M08] 获取系统与运行时信息
来源：http://dali.shangyingyoupin.top/Article/details/gtykkqklgy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.feifeiyinyue.top/Article/details/gtatrrpset.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhixingplan.top/Article/details/gtnhiwlscs.html

JS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gtreisoits.html

TS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gtgndnhljv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.feifeiyinyue.top/Article/details/gtypytxdbe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hfpthk.cn/Article/details/gtvrmhlaik.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.iojbl.cn/Article/details/gtclctwwfw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sysykeji.top/Article/details/gtaxptwnct.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtwgcbmftv.html

N. 数据结构与算法
来源：http://dali.daxiang520.top/Article/details/gtpzqsmmov.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtmeyuigkd.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxinkj.top/Article/details/gtatxfgugl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtjndcqqyw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zycfv.cn/Article/details/gtkokaedsx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gtdapsxdls.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gtmtsluzvw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gthwhlfcqw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmwytzke.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hywenlv.cn/Article/details/gtniimaond.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.meibo888.top/Article/details/gtugmktmbz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.meibo888.top/Article/details/gtxvtwzuas.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gtecnnpfdx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigufen.top/Article/details/gtlwlkjnwb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gtvrvwjfao.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtoxfhaegv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigfzy.top/Article/details/gtlwibyhfa.html

Go:   slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gtiarzxgxy.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gtvdjbsouo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenlongwang.top/Article/details/gtmerckrwg.html

[N03] 快速排序（分治示例）
来源：http://dali.jinghuilouyu.cn/Article/details/gtziroxlck.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.wangdashe.top/Article/details/gtbnozltwk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.9152youxi.cn/Article/details/gtbyukadsn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fengsongda.top/Article/details/gtpkojvjrz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gtguabrkap.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sufxvd.cn/Article/details/gtzvwxemtg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgfzy.top/Article/details/gtztmktlsv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yuxming.cn/Article/details/gtdvbqovai.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxuanxn.top/Article/details/gtdpkqvqob.html

[N04] 斐波那契数列
来源：http://dali.aizwys.cn/Article/details/gtgqnaitap.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gtiofqcgai.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gtlezxruib.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gtceryqtzq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtpwbdwsjl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gtslgtetlz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hysaishi.cn/Article/details/gthzlgjwly.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gtoaittmae.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtxncktqea.html

[N05] 最大公约数
来源：http://dali.sxryk.cn/Article/details/gtcysuhcix.html

Py:   math.gcd(a, b)
来源：http://dali.gzhubu.top/Article/details/gtuunxbexl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtglwgpbbx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gttvbbdbjd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtyojaxyte.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258.top/Article/details/gtaoilttjg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenlongwang.top/Article/details/gtgjavhdig.html

Ruby: a.gcd(b)
来源：http://dali.xziqi.cn/Article/details/gtyprfugbx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dianchejie.cn/Article/details/gtdywozjgz.html

[N06] 判断回文字符串
来源：http://dali.jlsjyb.cn/Article/details/gtrlpecjsh.html

Py:   s == s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gttgkevsqx.html

PHP:  $s === strrev($s);
来源：http://dali.tanke756.top/Article/details/gtcsxmflzk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gthfggiypz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtfcobvrby.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuxming.cn/Article/details/gtybqpgaex.html

Go:   // 双指针从两端比较
来源：http://dali.guowangkeji.top/Article/details/gttvdejkre.html

Ruby: s == s.reverse
来源：http://dali.andypj.xyz/Article/details/gtuxadcqgw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gtprtaqbwr.html

[N07] 两数之和（返回下标）
来源：http://dali.cqqwz.cn/Article/details/gtiycsonhf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinghuilouyu.cn/Article/details/gtfulybnbg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.birdmap.top/Article/details/gtyrzcxikh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gotoacloud.top/Article/details/gtpchldgti.html

TS:   // 手写 Map<string, number>
来源：http://dali.yongpay.top/Article/details/gtcnmohjlf.html

Java: // 手写 HashMap
来源：http://dali.cucudq.cn/Article/details/gtianpchnk.html

Go:   // 手写 map[int]int
来源：http://dali.zhengqikj.top/Article/details/gtmndiyxih.html

Ruby: // 手写 Hash
来源：http://dali.kuanghao11.cn/Article/details/gtziorzdft.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjaumxxdg.html

[N08] 生成全排列
来源：http://dali.hongshengwenyu.top/Article/details/gtktnkaiqj.html

Py:   itertools.permutations(arr)
来源：http://dali.zhoulong.xyz/Article/details/gthfmbwakg.html

PHP:  // 手写递归交换
来源：http://dali.yongpay.top/Article/details/gthqngelrf.html

JS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtgdnqhpof.html

TS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtkxvgjetz.html

Java: // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtfjnanajb.html

Go:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtflqzptin.html

Ruby: arr.permutation.to_a
来源：http://dali.jyoumei.cn/Article/details/gtxrknlvhh.html

C#:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtckbhzyaj.html

[N09] 栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnaxbhljl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.dianchejie.cn/Article/details/gtqxgnbpso.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtcqqysxjn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gtybdbwubm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.meibo888.top/Article/details/gteedrpgsg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuanzx.com/Article/details/gtwbntdedc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xuetiantiany.cn/Article/details/gtocuczffv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtclqvqpxw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhengqikj.top/Article/details/gtpzkccqfq.html

[N10] 链表节点定义
来源：http://dali.ppjwa.cn/Article/details/gtpuurjneq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cqqwz.cn/Article/details/gtjzkqquka.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.iojbl.cn/Article/details/gtauafjiur.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jyoumei.cn/Article/details/gtwkwliogl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhengqikj.top/Article/details/gtuescrswf.html

Java: class Node { int v; Node next; }
来源：http://dali.daria6918.cn/Article/details/gtjiyebciy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cheryme.top/Article/details/gtnviomzme.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqmielxn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sufxvd.cn/Article/details/gtlhqzpxkx.html

[N11] 二叉树中序遍历
来源：http://dali.chenzaomai.com/Article/details/gtwezyfmvq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hammf.cn/Article/details/gthfkyllan.html

PHP:  // 手写递归函数
来源：http://dali.shuidangran.top/Article/details/gtpgthaevd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosormcis.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gtkmgasrem.html

Java: // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gtstsnpcoi.html

Go:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gtntatajbo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangshuangyany.cn/Article/details/gtltoslbnu.html

C#:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtfdkpetpi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnqzz.top/Article/details/gttdbtlorx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nwbrower.top/Article/details/gtpdlsmmne.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenzaomai.com/Article/details/gtnbzzozas.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gtzqfdcykk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.snrcjt.cn/Article/details/gtimxwsyvn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gtuvzgqkwk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.kuanghao11.cn/Article/details/gthefjrbbx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.havefunace.top/Article/details/gtworuuafj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gtfaqjbeix.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtevmaoydt.html

O. 并发与异步
来源：http://dali.andypj.xyz/Article/details/gthnicgbkg.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtbypfqzoe.html

[O01] 启动一个线程
来源：http://dali.aizwys.cn/Article/details/gtbobyudvm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenzaomai.com/Article/details/gttkaohlev.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cashguo.top/Article/details/gttlbonbov.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuxming.cn/Article/details/gtlhsbuguk.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtqszkznwp.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhiwuduotai.top/Article/details/gtqnimhfjj.html

Go:   go f()
来源：http://dali.zhoulong.xyz/Article/details/gtcdqcgqpe.html

Ruby: Thread.new { f }
来源：http://dali.cqqwz.cn/Article/details/gtcftatpew.html

C#:   Task.Run(() => F());
来源：http://dali.shuidangran.top/Article/details/gtcsakfcwb.html

[O02] 使用线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtuszsjzbb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zycfv.cn/Article/details/gtwncbgwja.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.meibo888.top/Article/details/gtachixxjc.html

JS:   // worker_threads 线程池
来源：http://dali.zhixingplan.top/Article/details/gtzdvziqhh.html

TS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gthoofpnfq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.havefunace.top/Article/details/gtbeaannor.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxuanxn.top/Article/details/gtgbkpmmej.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.birdmap.top/Article/details/gtsnwahtff.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj202588.top/Article/details/gtiwwuorss.html

[O03] 加锁保护共享数据
来源：http://dali.yueranfly.top/Article/details/gtrrzmullg.html

Py:   with lock: shared += 1
来源：http://dali.chenlongwang.top/Article/details/gtolbmouyy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tianlin.xyz/Article/details/gthmrvnglz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zycfv.cn/Article/details/gtucwqvhko.html

TS:   // 同 JS
来源：http://dali.havefunace.top/Article/details/gtylqcxytx.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxuanxn.top/Article/details/gttlvrgaca.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.meibo888.top/Article/details/gtwnhxobvz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuanzhike.top/Article/details/gtevrscbxt.html

C#:   lock (gate) { shared++; }
来源：http://dali.hfpthk.cn/Article/details/gtnchoteuh.html

[O04] 定义异步函数并等待
来源：http://dali.sufxvd.cn/Article/details/gttgiyhaqc.html

Py:   async def f():⏎    await g()
来源：http://dali.tianlin.xyz/Article/details/gtbxkmbaby.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangdashe.top/Article/details/gtirodoenj.html

JS:   async function f() { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gtdwdsvjfp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sxryk.cn/Article/details/gtghytvfwf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yongpay.top/Article/details/gtyrsdlgvq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daria6918.cn/Article/details/gtlrsnypot.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gzhubu.top/Article/details/gtubsicrni.html

C#:   async Task F() { await G(); }
来源：http://dali.chenlongwang.top/Article/details/gtylxzrxkc.html

[O05] 并发执行并等待全部完成
来源：http://dali.snrcjt.cn/Article/details/gtokvpmvcx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ppjwa.cn/Article/details/gtisqfxrpb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hysaishi.cn/Article/details/gtxywruxac.html

JS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gtsdlxbift.html

TS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gtufisfpim.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ehwqpu.com/Article/details/gtatnhkklf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pycfn.com/Article/details/gtceidagrv.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigufen.top/Article/details/gtbtivpvcr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cheryme.top/Article/details/gttmbbouyj.html

[O06] 使用进程池
来源：http://dali.hnxiangtu.top/Article/details/gtdxywtquc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tianlin.xyz/Article/details/gtbjqghncl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yanxiufei.cn/Article/details/gtguxopsuw.html

JS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gtkdxsmhvz.html

TS:   // child_process / cluster 模块
来源：http://dali.yonumen.top/Article/details/gtwzilcnvt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gzhubu.top/Article/details/gtdwijberg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shanyushiyangkeji.top/Article/details/gtogevwahe.html

Ruby: // fork 块
来源：http://dali.zdqjudy.top/Article/details/gtsznhrici.html

C#:   Parallel.For
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynwodwwk.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtskfgjmtw.html

P. 常用工具函数
来源：http://dali.yj20258888.top/Article/details/gtfyivbmtz.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtkzbpkqif.html

[P01] 生成 UUID
来源：http://dali.hnqzz.top/Article/details/gtryqkyqex.html

Py:   str(uuid.uuid4())
来源：http://dali.jinqigfzy.top/Article/details/gtlxqdjacl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tianlin.xyz/Article/details/gtijxuadiz.html

JS:   crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gtdgwudwtz.html

TS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gtsuewnuiv.html

Java: UUID.randomUUID().toString()
来源：http://dali.yongpay.top/Article/details/gtjyfnxluo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.svipenyu.cn/Article/details/gtuhqkjzkb.html

Ruby: SecureRandom.uuid
来源：http://dali.yuanzhike.top/Article/details/gtgyxabgzw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yuanzhike.top/Article/details/gtusnxbcbk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sufxvd.cn/Article/details/gtzthnyamo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tanke756.top/Article/details/gtkcfgnhqn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fzhhl.top/Article/details/gtyzyamtje.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ppjwa.cn/Article/details/gtmefuhfat.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tian-w.cn/Article/details/gtwwaihdnz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxinkj.top/Article/details/gtouxlkgqm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cashguo.top/Article/details/gteazkfqjv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fzhhl.top/Article/details/gtzdgcoimt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgufenzy.top/Article/details/gttchhjgdl.html

[P03] 生成短随机字符串
来源：http://dali.nanxinkj.top/Article/details/gtihiezfxi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sufxvd.cn/Article/details/gtacooqqnj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shzxlz.cn/Article/details/gtqslszmsq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gtudmvwmun.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dianchejie.cn/Article/details/gtdoxtgyza.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnqzz.top/Article/details/gtgpunrffb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shuidangran.top/Article/details/gtqgitbsox.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gaohongyu789.top/Article/details/gtrhalbnls.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.snrcjt.cn/Article/details/gtslngfbxh.html

[P04] 求长度
来源：http://dali.sysykeji.top/Article/details/gtpkoatnck.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gaohongyu789.top/Article/details/gtwffyxubi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtfafetriu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zycfv.cn/Article/details/gtvyabozfs.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.svipenyu.cn/Article/details/gtnbwnojea.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangdashe.top/Article/details/gtxfksgzib.html

Go:   len(arr);  len(m)
来源：http://dali.yongpay.top/Article/details/gtlstvjpba.html

Ruby: x.length;  x.size
来源：http://dali.quarkkingdee.top/Article/details/gtrbamcfmr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gogol.net.cn/Article/details/gtxsvyuwps.html

[P05] 判断两个对象内容是否相等
来源：http://dali.andypj.xyz/Article/details/gtbauhnajb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.kuanghao11.cn/Article/details/gtuubhhfqr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gogol.net.cn/Article/details/gttoofhiud.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hongshengwenyu.top/Article/details/gtwcqujnie.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.9152youxi.cn/Article/details/gtwssobxpt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenlongwang.top/Article/details/gtaerenrru.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gtpebfhqfy.html

Ruby: a == b
来源：http://dali.yuxming.cn/Article/details/gtrwtbhodh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhongyouzk.top/Article/details/gteupnvvxd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zdqjudy.top/Article/details/gtpxoasjzm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gtxfagctgo.html

PHP:  if (empty($x)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqydlzlgp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yongpay.top/Article/details/gtazfxmpcj.html

TS:   if (x == null) {}
来源：http://dali.daxiang520.top/Article/details/gtxwytuual.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gtvgvgvyhr.html

Go:   if x == nil {}
来源：http://dali.cheryme.top/Article/details/gtiuriedhj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.fzhhl.top/Article/details/gtvrmmdezv.html

C#:   if (x is null) {}
来源：http://dali.kuanghao11.cn/Article/details/gthoyrupdh.html

[P07] 防抖与节流
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnytnmfc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.0kj1m.cn/Article/details/gtlmduqite.html

PHP:  // 手写时间戳比较
来源：http://dali.feifeiyinyue.top/Article/details/gtwavspinq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ivvv.top/Article/details/gtrjrduumq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gtnqgfvded.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jianghu66.top/Article/details/gttrwqwufk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hfpthk.cn/Article/details/gttjscortp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrjevihk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.9152youxi.cn/Article/details/gtmcjxsmur.html

[P08] 处理浮点精度问题
来源：http://dali.quarkkingdee.top/Article/details/gtyktprmjz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ivvv.top/Article/details/gtorxxomhe.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhengqikj.top/Article/details/gtdoojglfz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gaohongyu789.top/Article/details/gtkkerfhjc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tanke756.top/Article/details/gtzwizvavn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cashguo.top/Article/details/gtanodldoh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aibaodan.cn/Article/details/gtadutwxoc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xziqi.cn/Article/details/gtlaxnetsv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.wangshuangyany.cn/Article/details/gtaadjkhwi.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtcamfwttq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.tian-w.cn/Article/details/gtcjvzqyjp.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmuftbbc.html

[Q01] 创建表
来源：http://dali.gaohongyu789.top/Article/details/gtcyoanfqe.html

CREATE TABLE users (
来源：http://dali.shanyushiyangtech.top/Article/details/gttnmnimdb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gtviarxutj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gtshobxmbr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zdqjudy.top/Article/details/gtajejwipm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258.top/Article/details/gtiudzvryc.html

);
来源：http://dali.316326.xyz/Article/details/gtvmnwotea.html

[Q02] 创建带外键的表
来源：http://dali.smart0.xyz/Article/details/gtnytvclip.html

CREATE TABLE orders (
来源：http://dali.aizwys.cn/Article/details/gtigalsnzm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ybcxt.top/Article/details/gtoidxatqo.html

user_id INT NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gtekmpkspl.html

amount DECIMAL(10, 2),
来源：http://dali.ydzc1.top/Article/details/gtkhogwvuc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shangyingyoupin.top/Article/details/gtbltylzbt.html

);
来源：http://dali.guannengcc.top/Article/details/gtmcszrtvv.html

[Q03] 增加列
来源：http://dali.feifeiyinyue.top/Article/details/gtazwqbvda.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.dianchejie.cn/Article/details/gttukngfsc.html

[Q04] 修改列类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtunytdieo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgufenzy.top/Article/details/gtfpmyamjl.html

[Q05] 重命名列
来源：http://dali.daria6918.cn/Article/details/gtwemmrmvx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cdnleiting.top/Article/details/gtqdjgedmn.html

[Q06] 删除列
来源：http://dali.hongshengwenyu.top/Article/details/gtoqubrfle.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cashguo.top/Article/details/gtvambdqip.html

[Q07] 删除表
来源：http://dali.jyoumei.cn/Article/details/gtkzjyekft.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ydzc1.top/Article/details/gtwrtrjibc.html

[Q08] 创建普通索引
来源：http://dali.c1oappe.top/Article/details/gtnlykritq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gtotlqafrs.html

[Q09] 创建唯一索引
来源：http://dali.xziqi.cn/Article/details/gtitetveui.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.feifeiyinyue.top/Article/details/gtzouycaen.html

[Q10] 插入单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtpdxrey.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtcswucgzr.html

[Q11] 一次插入多行
来源：http://dali.chenjidiqi.icu/Article/details/gthsqcotrw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtkxmyhdou.html

[Q12] 插入后取自增 ID
来源：http://dali.aibaodan.cn/Article/details/gtzkflqybo.html


<!-- 参考信息 -->