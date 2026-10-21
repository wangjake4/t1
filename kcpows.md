代发 wailian999

Java: public static void main(String[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gthetgyrxr.html

Go:   func main()
来源：http://dali.shzxlz.cn/Article/details/gtvyqpddqn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gotoacloud.top/Article/details/gtxyhxjiiv.html

C#:   static void Main(string[] args)
来源：http://dali.gotoacloud.top/Article/details/gtxyeraaut.html

[M08] 获取系统与运行时信息
来源：http://dali.zhoulong.xyz/Article/details/gtgnjastro.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sweek.top/Article/details/gtygxnvvui.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daria6918.cn/Article/details/gtiptuppmc.html

JS:   process.platform;  process.version
来源：http://dali.svipenyu.cn/Article/details/gtkropqqxo.html

TS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gtbmbspqpj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tian-w.cn/Article/details/gthkjlhqhi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhongyouzk.top/Article/details/gtfargfbwm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shangyingyoupin.top/Article/details/gtfszwqjnf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.havefunace.top/Article/details/gtckjtqnwg.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvcphvufk.html

N. 数据结构与算法
来源：http://dali.9152youxi.cn/Article/details/gtxipzttkx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtweipxkqh.html

[N01] 二分查找（有序数组）
来源：http://dali.xuetiantiany.cn/Article/details/gtyxdmaiax.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtvppkqmie.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtkagoveop.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtlohfqfuo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sxryk.cn/Article/details/gthetsjwdb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtrthehbrl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtrpplgauc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmyowbdn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtbsiofngd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.bjfxy.top/Article/details/gtzcskqqjt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangdashe.top/Article/details/gtqguvmbne.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.haohaochexian.top/Article/details/gtpjnmgaqz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gtgyryucjm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gtckyhdddj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yvedp.cn/Article/details/gtbnkqybnq.html

Go:   slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gtdvzgnvhm.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtrgscmehx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.svipenyu.cn/Article/details/gtxxplbwwe.html

[N03] 快速排序（分治示例）
来源：http://dali.sxryk.cn/Article/details/gtdwqweafj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhpihgde.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhiwuduotai.top/Article/details/gtinvcpluz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmxrxwqs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gtubjhrixg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daria6918.cn/Article/details/gteaeyisln.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fzhhl.top/Article/details/gtxtvsmvot.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yvedp.cn/Article/details/gtkruhmrrm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxuanxn.top/Article/details/gtaxhtsrwu.html

[N04] 斐波那契数列
来源：http://dali.meibo888.top/Article/details/gtlnsmvfka.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gtdzglnqqb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tanke756.top/Article/details/gtklcrixbh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gtoynhiigr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gtxtugkxwe.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gtjtuhxgxy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuetiantiany.cn/Article/details/gtldqujftq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtegkujwjb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtsjrwipxf.html

[N05] 最大公约数
来源：http://dali.ivvv.top/Article/details/gtdgnldwjp.html

Py:   math.gcd(a, b)
来源：http://dali.xziqi.cn/Article/details/gtbvgvbexh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.vqdsnc.cn/Article/details/gtvasdffsl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gtgleailfv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtveoqlgqx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cdnleiting.top/Article/details/gtzyqajtaz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xziqi.cn/Article/details/gtcioxwuuz.html

Ruby: a.gcd(b)
来源：http://dali.iojbl.cn/Article/details/gtiqxezzfu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hammf.cn/Article/details/gtcvojshqg.html

[N06] 判断回文字符串
来源：http://dali.yj20258.top/Article/details/gtvfqtvbnr.html

Py:   s == s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gttudoeweu.html

PHP:  $s === strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gtqgrkvgpd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtvyxpzeuu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtkwlfoqhw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxshjznng.html

Go:   // 双指针从两端比较
来源：http://dali.yueranfly.top/Article/details/gtymowjxim.html

Ruby: s == s.reverse
来源：http://dali.ydzc1.top/Article/details/gthzwlpimp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gtfodgrcia.html

[N07] 两数之和（返回下标）
来源：http://dali.svipenyu.cn/Article/details/gtdhtfssaq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jianghu66.top/Article/details/gtgsvqrsjo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhengqikj.top/Article/details/gtqvooozhe.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.svipenyu.cn/Article/details/gtbtvjrosy.html

TS:   // 手写 Map<string, number>
来源：http://dali.yvedp.cn/Article/details/gtecljinhj.html

Java: // 手写 HashMap
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutyzswfk.html

Go:   // 手写 map[int]int
来源：http://dali.nwbrower.top/Article/details/gtxjiiepgh.html

Ruby: // 手写 Hash
来源：http://dali.shangyingyoupin.top/Article/details/gtubweqfrw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tanke756.top/Article/details/gtfxfwouka.html

[N08] 生成全排列
来源：http://dali.ehwqpu.com/Article/details/gtyhmjxgbd.html

Py:   itertools.permutations(arr)
来源：http://dali.pycfn.com/Article/details/gtcuxgdhvn.html

PHP:  // 手写递归交换
来源：http://dali.tianlin.xyz/Article/details/gtkwecgojw.html

JS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gthadkchhb.html

TS:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtduccxuiv.html

Java: // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtbenklgnd.html

Go:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtseufyhlm.html

Ruby: arr.permutation.to_a
来源：http://dali.yangfankeji.com/Article/details/gtskejreml.html

C#:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtpozrlilr.html

[N09] 栈与队列
来源：http://dali.aibaodan.cn/Article/details/gtrqhfcygd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gogol.net.cn/Article/details/gtdamfxjhp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozfvrtmg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtjuunrdbn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.kuanghao11.cn/Article/details/gtkropczuc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cdnleiting.top/Article/details/gtyxrxwbvh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yanxiufei.cn/Article/details/gtbhedvjsl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gtzezzrxuy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ivvv.top/Article/details/gtdoeacnts.html

[N10] 链表节点定义
来源：http://dali.sxryk.cn/Article/details/gtqgnxytgt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.wangdashe.top/Article/details/gtbtretxiv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gogol.net.cn/Article/details/gtdgfktafr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.andypj.xyz/Article/details/gtvxsccdqy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ehwqpu.com/Article/details/gtnpamhlqy.html

Java: class Node { int v; Node next; }
来源：http://dali.gotoacloud.top/Article/details/gtczzavofo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.havefunace.top/Article/details/gtoeuzcixb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.quarkkingdee.top/Article/details/gttrnwlmsj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ppjwa.cn/Article/details/gtovwvdwok.html

[N11] 二叉树中序遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpcvqofu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj20258888.top/Article/details/gtcyoruncj.html

PHP:  // 手写递归函数
来源：http://dali.xylfe.cn/Article/details/gtsihvabto.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gtstnzcbjc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sweek.top/Article/details/gtjbjigpuj.html

Java: // 手写递归
来源：http://dali.316326.xyz/Article/details/gtpegxydnm.html

Go:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtjkwvilxz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shuidangran.top/Article/details/gtcfcdrokw.html

C#:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtuvufgcvd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tianlin.xyz/Article/details/gtfkbqmlqq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.andypj.xyz/Article/details/gtkcyishvx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shzxlz.cn/Article/details/gtdfpwhqwx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gtvfvheboj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fengsongda.top/Article/details/gtcsmarjie.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gtinmvkhxn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhixingplan.top/Article/details/gtpmwezeor.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.mhx1999.top/Article/details/gtofohcipu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gtgujocdoq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtrxjbwxlq.html

O. 并发与异步
来源：http://dali.yanxiufei.cn/Article/details/gtfsborqhp.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtphzjxwxu.html

[O01] 启动一个线程
来源：http://dali.ivvv.top/Article/details/gtgoybzkrj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.meibo888.top/Article/details/gtcirculbe.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.pengpengdd.cyou/Article/details/gtsuwiecrj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigfzy.top/Article/details/gtaoxscdst.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gtikaubskt.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj202588.top/Article/details/gtfmbdvavk.html

Go:   go f()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcuzgmigk.html

Ruby: Thread.new { f }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjadzfogd.html

C#:   Task.Run(() => F());
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcpmrrrw.html

[O02] 使用线程池
来源：http://dali.pengpengdd.cyou/Article/details/gtuycicqup.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.316326.xyz/Article/details/gtrdzawctq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gogol.net.cn/Article/details/gtgzufhtcd.html

JS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gthyxwqduh.html

TS:   // worker_threads 线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqwcnhkq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dianchejie.cn/Article/details/gtrwrtqdqj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jiagoushi.top/Article/details/gtoeusgkgg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258888.top/Article/details/gtrmnfnmeo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.mhx1999.top/Article/details/gtyacdkfog.html

[O03] 加锁保护共享数据
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmtndcuw.html

Py:   with lock: shared += 1
来源：http://dali.shangyingyoupin.top/Article/details/gtqlfyoxql.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.dashuyun.cn/Article/details/gtucaumvty.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tian-w.cn/Article/details/gtunakfekc.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gtvicdjroz.html

Java: synchronized (this) { shared++; }
来源：http://dali.sufxvd.cn/Article/details/gtkuxlkhjo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmywyrvsb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangdashe.top/Article/details/gtgzxzgncy.html

C#:   lock (gate) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gtgevjwnlz.html

[O04] 定义异步函数并等待
来源：http://dali.yuxming.cn/Article/details/gtfzjpvvdl.html

Py:   async def f():⏎    await g()
来源：http://dali.havefunace.top/Article/details/gtiblrqdjj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tanke756.top/Article/details/gthzghcxga.html

JS:   async function f() { await g(); }
来源：http://dali.xziqi.cn/Article/details/gtpfhxceys.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.fengsongda.top/Article/details/gtkygklpwx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.guowangkeji.top/Article/details/gtoinbeuex.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.andypj.xyz/Article/details/gtiqmepcbf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnxiangtu.top/Article/details/gtfcvihzhn.html

C#:   async Task F() { await G(); }
来源：http://dali.yangfankeji.com/Article/details/gtmtmtsqga.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhiwuduotai.top/Article/details/gtmnezcdjf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.bjfxy.top/Article/details/gtwrcchthr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.snrcjt.cn/Article/details/gtnzfuuepa.html

JS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gttytjhhlo.html

TS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gtdvvyxsqr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pengpengdd.cyou/Article/details/gteuknxjwt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.iojbl.cn/Article/details/gtkozhoivj.html

Ruby: threads.map(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtezvnxqpt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenzaomai.com/Article/details/gtakkebrbz.html

[O06] 使用进程池
来源：http://dali.ybcxt.top/Article/details/gtiagykogx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cqqwz.cn/Article/details/gtmqvbujeb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jiagoushi.top/Article/details/gteanubpkt.html

JS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gtvdymfcyw.html

TS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gtgcfeqibp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sweek.top/Article/details/gtpytnmyot.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jiagoushi.top/Article/details/gtscqharih.html

Ruby: // fork 块
来源：http://dali.cheryme.top/Article/details/gtivnjztst.html

C#:   Parallel.For
来源：http://dali.vqdsnc.cn/Article/details/gtunnzbbke.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtkkkqslgj.html

P. 常用工具函数
来源：http://dali.fzhhl.top/Article/details/gtcrbuaytk.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtoszvizzd.html

[P01] 生成 UUID
来源：http://dali.shuidangran.top/Article/details/gtwdtarlxi.html

Py:   str(uuid.uuid4())
来源：http://dali.jiagoushi.top/Article/details/gtkqjxuzff.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.svipenyu.cn/Article/details/gtkgkjbkrb.html

JS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufdmlnld.html

TS:   crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gtryekwmhf.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258.top/Article/details/gtlgucmscw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cucudq.cn/Article/details/gtswesxulb.html

Ruby: SecureRandom.uuid
来源：http://dali.xuanzx.com/Article/details/gtzepsjmkk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.daria6918.cn/Article/details/gtxkxvhuuq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnqzz.top/Article/details/gtwpfjvaxo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.svipenyu.cn/Article/details/gtszgiddls.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fzhhl.top/Article/details/gtvtgtrgcd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.meibo888.top/Article/details/gtzikougpm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.haohaochexian.top/Article/details/gtvkbdcubp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xylfe.cn/Article/details/gtpzxnujml.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ppjwa.cn/Article/details/gttndfdsio.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sysykeji.top/Article/details/gtqekgocug.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuanzhike.top/Article/details/gtkqipjwao.html

[P03] 生成短随机字符串
来源：http://dali.hywenlv.cn/Article/details/gtjlnaggvd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yanxiufei.cn/Article/details/gtnnliaqns.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hywenlv.cn/Article/details/gtfgdprtim.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnxiangtu.top/Article/details/gtexfvnjum.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbpdegtp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuxming.cn/Article/details/gtotygiuve.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dashuyun.cn/Article/details/gtvwgykffd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jianghu66.top/Article/details/gtirfbkhlq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hfpthk.cn/Article/details/gtminfflgd.html

[P04] 求长度
来源：http://dali.nwbrower.top/Article/details/gtmdjvhule.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ydzc1.top/Article/details/gtksbdushz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtmbkgyagt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shuidangran.top/Article/details/gtjmizogrk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gtfjujqfnz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.birdmap.top/Article/details/gtafcutski.html

Go:   len(arr);  len(m)
来源：http://dali.havefunace.top/Article/details/gtmntvxjoc.html

Ruby: x.length;  x.size
来源：http://dali.yongpay.top/Article/details/gtveryasnk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gtrskhybjf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxinkj.top/Article/details/gtyqcqlfkg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.quarkkingdee.top/Article/details/gtgibziwdv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.guowangkeji.top/Article/details/gtjlycsoml.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.kuanghao11.cn/Article/details/gtlzbxpqqc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gtnudqbznr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ehwqpu.com/Article/details/gtegchkogw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtmhkcfstl.html

Ruby: a == b
来源：http://dali.tianlin.xyz/Article/details/gtkgqaawts.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnqzz.top/Article/details/gtqzxnwojv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jiagoushi.top/Article/details/gtlstiuwck.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.dashuyun.cn/Article/details/gtzmgefmqj.html

PHP:  if (empty($x)) {}
来源：http://dali.sysykeji.top/Article/details/gtocwougdh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shuidangran.top/Article/details/gtvvapcncm.html

TS:   if (x == null) {}
来源：http://dali.fengsongda.top/Article/details/gtivvtwhbf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sweek.top/Article/details/gtconuptis.html

Go:   if x == nil {}
来源：http://dali.dianchejie.cn/Article/details/gtkfswrvso.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tian-w.cn/Article/details/gtrkfyvdsv.html

C#:   if (x is null) {}
来源：http://dali.guowangkeji.top/Article/details/gtbuvsjias.html

[P07] 防抖与节流
来源：http://dali.smart0.xyz/Article/details/gtzostoxdl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aibaodan.cn/Article/details/gtgwwylhje.html

PHP:  // 手写时间戳比较
来源：http://dali.smart0.xyz/Article/details/gtfdulyifi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gtmywndeyp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gtppeizujy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hammf.cn/Article/details/gtyzsnuggg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sweek.top/Article/details/gtrsmccwwf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nwbrower.top/Article/details/gtryjgzynm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aibaodan.cn/Article/details/gtypwpqokr.html

[P08] 处理浮点精度问题
来源：http://dali.sweek.top/Article/details/gtsewdxehn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.snrcjt.cn/Article/details/gtpnvyiojv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtpdbndtbg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.haohaochexian.top/Article/details/gtrqxqhiik.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.fzhhl.top/Article/details/gtjmkicpua.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hnxiangtu.top/Article/details/gtwbcwtkuc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangshuangyany.cn/Article/details/gtsowxquey.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hysaishi.cn/Article/details/gtorhlkvvk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hysaishi.cn/Article/details/gtwjajpdax.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtphksbnet.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nanxinkj.top/Article/details/gtebfonfqv.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtyqakxiql.html

[Q01] 创建表
来源：http://dali.fzhhl.top/Article/details/gtahymyrpq.html

CREATE TABLE users (
来源：http://dali.hysaishi.cn/Article/details/gthdxnhxry.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigfzy.top/Article/details/gtoxcxkgqh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gtwkziphls.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xuanzx.com/Article/details/gtihsbqezk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jqgufenzy.top/Article/details/gtjyekzrhe.html

);
来源：http://dali.hysaishi.cn/Article/details/gtffjqolja.html

[Q02] 创建带外键的表
来源：http://dali.9152youxi.cn/Article/details/gtevfkruzv.html

CREATE TABLE orders (
来源：http://dali.xylfe.cn/Article/details/gtkqlaoihk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jianghu66.top/Article/details/gtshnbjqan.html

user_id INT NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gtdecptkrk.html

amount DECIMAL(10, 2),
来源：http://dali.yongpay.top/Article/details/gtvmiykvxi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guannengcc.top/Article/details/gtbjgzndso.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gtuftlcwrs.html

[Q03] 增加列
来源：http://dali.shuidangran.top/Article/details/gteialzzxy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.bjfxy.top/Article/details/gtbrxcaazm.html

[Q04] 修改列类型
来源：http://dali.yj202588.top/Article/details/gtqudwcjyb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenzaomai.com/Article/details/gtvvgmlfwu.html

[Q05] 重命名列
来源：http://dali.jinqigufen.top/Article/details/gtxdgnwonm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdszlubqn.html

[Q06] 删除列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtautolqjw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sysykeji.top/Article/details/gtjksmgwrl.html

[Q07] 删除表
来源：http://dali.hnxiangtu.top/Article/details/gtntpgywst.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tian-w.cn/Article/details/gtyuiztynb.html

[Q08] 创建普通索引
来源：http://dali.yongpay.top/Article/details/gtwfhlhweu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gtydnfcuml.html

[Q09] 创建唯一索引
来源：http://dali.mhx1999.top/Article/details/gthksxbobx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gtlnkmspmk.html

[Q10] 插入单行
来源：http://dali.bjfxy.top/Article/details/gtshshwcig.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrevniasc.html

[Q11] 一次插入多行
来源：http://dali.yvedp.cn/Article/details/gtpodivdia.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtxmpzrqbl.html

[Q12] 插入后取自增 ID
来源：http://dali.daria6918.cn/Article/details/gtxjjincax.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigfzy.top/Article/details/gtakmpnngu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvctrusv.html

[Q13] 忽略重复插入
来源：http://dali.zhengqikj.top/Article/details/gtgklxiidr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenzaomai.com/Article/details/gtlchtgzzv.html

[Q14] 存在则更新（upsert）
来源：http://dali.havefunace.top/Article/details/gtxaufcntb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sysykeji.top/Article/details/gtniirpwro.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhoulong.xyz/Article/details/gtlygqzfpg.html

[Q15] 查询全部
来源：http://dali.sysykeji.top/Article/details/gtccnkxtxm.html


<!-- 参考信息 -->