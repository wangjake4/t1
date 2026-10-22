代发 wailian999

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258.top/Article/details/gtcodronke.html

Ruby: warn "err"
来源：http://dali.jiagoushi.top/Article/details/gtixpvxuzz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtgvusmrpe.html

[M07] 判断是否为主入口
来源：http://dali.ybcxt.top/Article/details/gtxwdxtokw.html

Py:   if __name__ == "__main__":
来源：http://dali.yuxming.cn/Article/details/gtnadciqgz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuanzhike.top/Article/details/gtnjpvnzpp.html

JS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gtotdvjocp.html

TS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gtxbuopmpr.html

Java: public static void main(String[] args)
来源：http://dali.vqdsnc.cn/Article/details/gtqxtaibkr.html

Go:   func main()
来源：http://dali.shangyingyoupin.top/Article/details/gtqjylivwb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gogol.net.cn/Article/details/gtlgrgsixt.html

C#:   static void Main(string[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcobyrogd.html

[M08] 获取系统与运行时信息
来源：http://dali.yangfankeji.com/Article/details/gtllmuohud.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangshuangyany.cn/Article/details/gtxdnogrtg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.vqdsnc.cn/Article/details/gtnlyhrqap.html

JS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gtxcsoskpv.html

TS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gtcmpugqcj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shanyushiyangtech.top/Article/details/gtiazfcloz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhiwuduotai.top/Article/details/gtxyhxhltb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyvkjgxy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nwbrower.top/Article/details/gtixgdbhoa.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtpcnlhxyk.html

N. 数据结构与算法
来源：http://dali.aizwys.cn/Article/details/gtyahgtcif.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gthmkzewek.html

[N01] 二分查找（有序数组）
来源：http://dali.ppjwa.cn/Article/details/gtyizutuqa.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtlsgztwrl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yueranfly.top/Article/details/gtffcdpgrt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gtktxkkjim.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtnbmopjie.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtaicwvhih.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmkyomyz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gaohongyu789.top/Article/details/gtjdwzwtvp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtygfudlaf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sxryk.cn/Article/details/gtktqjavby.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gtvrckleux.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmihajot.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtqlmygxav.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gthnxzoipu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shuidangran.top/Article/details/gtoxukjuwu.html

Go:   slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gtlnwgehbi.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gthwrblpeg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zdqjudy.top/Article/details/gtvqnaozaz.html

[N03] 快速排序（分治示例）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtisaccpku.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.feifeiyinyue.top/Article/details/gtyzvxscdi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhongyouzk.top/Article/details/gtcyynwzgu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gthvkoxsug.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gtfhhtcenb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuijrzkug.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hfpthk.cn/Article/details/gtqgdqcljf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmlesunc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nwbrower.top/Article/details/gtwasqtgsq.html

[N04] 斐波那契数列
来源：http://dali.ivvv.top/Article/details/gtjczclzqx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gtilxgqxct.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gtlqpugpbs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtijkyelnb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtflnimiai.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nwbrower.top/Article/details/gtvsqofgzf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.9152youxi.cn/Article/details/gtfjyvffna.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gtzqaqzkkb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtigmtdiiv.html

[N05] 最大公约数
来源：http://dali.daxiang520.top/Article/details/gtdfvintmf.html

Py:   math.gcd(a, b)
来源：http://dali.daxiang520.top/Article/details/gtsouosopf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zdqjudy.top/Article/details/gtpitwsntp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gtfcsskwxk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gtfodereuz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.quarkkingdee.top/Article/details/gtngcqyezt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.kuanghao11.cn/Article/details/gttmxgzguk.html

Ruby: a.gcd(b)
来源：http://dali.zdqjudy.top/Article/details/gtmdreaoep.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fzhhl.top/Article/details/gtgxjbkdgc.html

[N06] 判断回文字符串
来源：http://dali.jianghu66.top/Article/details/gtbawjuqwy.html

Py:   s == s[::-1]
来源：http://dali.wangdashe.top/Article/details/gtnkcoppif.html

PHP:  $s === strrev($s);
来源：http://dali.ydzc1.top/Article/details/gtakwvkjkr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtwikrcris.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtmhnzeqfk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tian-w.cn/Article/details/gtubwpmglm.html

Go:   // 双指针从两端比较
来源：http://dali.fzhhl.top/Article/details/gtnlpfmhvq.html

Ruby: s == s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gtfmwjdihc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gtfapwhowa.html

[N07] 两数之和（返回下标）
来源：http://dali.yueranfly.top/Article/details/gtvuzxqtvb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jyoumei.cn/Article/details/gtgrxhgcad.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.wangdashe.top/Article/details/gtcumcufun.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cashguo.top/Article/details/gtnjzwuhhf.html

TS:   // 手写 Map<string, number>
来源：http://dali.cashguo.top/Article/details/gtpcfimfzw.html

Java: // 手写 HashMap
来源：http://dali.zycfv.cn/Article/details/gttzbwrzwg.html

Go:   // 手写 map[int]int
来源：http://dali.daria6918.cn/Article/details/gtkmueisdt.html

Ruby: // 手写 Hash
来源：http://dali.vqdsnc.cn/Article/details/gtugwhxbzw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgufenzy.top/Article/details/gtvvmrgukp.html

[N08] 生成全排列
来源：http://dali.aizwys.cn/Article/details/gtpyhtrfsj.html

Py:   itertools.permutations(arr)
来源：http://dali.ppjwa.cn/Article/details/gtknnytsai.html

PHP:  // 手写递归交换
来源：http://dali.jiagoushi.top/Article/details/gtxuagktxe.html

JS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtsqiqbuuy.html

TS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtkugbnvmx.html

Java: // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtxkooemgp.html

Go:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtezlrumlt.html

Ruby: arr.permutation.to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjklpwjia.html

C#:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtazqmcwap.html

[N09] 栈与队列
来源：http://dali.yvedp.cn/Article/details/gtlmxdebqp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hywenlv.cn/Article/details/gteapgkaqk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gtlyiqypgs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtvgwmleat.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yuxming.cn/Article/details/gtugimbbvp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258.top/Article/details/gtrhkyhcur.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.kuanghao11.cn/Article/details/gtuawcdivj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtnzmgqobt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gtczkqjhma.html

[N10] 链表节点定义
来源：http://dali.yj20258888.top/Article/details/gtdbfpjpex.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yueranfly.top/Article/details/gtegbihzeq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.feifeiyinyue.top/Article/details/gtsecgbgth.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.pycfn.com/Article/details/gtkfsjkfrr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.feifeiyinyue.top/Article/details/gtcqrvjojq.html

Java: class Node { int v; Node next; }
来源：http://dali.tianlin.xyz/Article/details/gtgscdpbgo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhoulong.xyz/Article/details/gtyvgkuxil.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.birdmap.top/Article/details/gtgeyocdqq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xziqi.cn/Article/details/gtsatnpooc.html

[N11] 二叉树中序遍历
来源：http://dali.yj20258888.top/Article/details/gtkryoxdhj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.feifeiyinyue.top/Article/details/gtypwnncyb.html

PHP:  // 手写递归函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspcznyun.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jiagoushi.top/Article/details/gthcneweno.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hywenlv.cn/Article/details/gtivmgbgyi.html

Java: // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtkmndabfs.html

Go:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gtoixnrgmt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cdnleiting.top/Article/details/gtwetkvdfl.html

C#:   // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gtyezwmmgm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenzaomai.com/Article/details/gtqpgnpuvb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjoqjkbv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cdnleiting.top/Article/details/gtfndofwze.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gthcahhnqi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gtnommketp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gtzhgwbvao.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hfpthk.cn/Article/details/gtpobnvqbp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ivvv.top/Article/details/gtbarqjtfo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvmiyjcp.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtbbqsqojo.html

O. 并发与异步
来源：http://dali.havefunace.top/Article/details/gtjfwwielu.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtepftdsxc.html

[O01] 启动一个线程
来源：http://dali.aizwys.cn/Article/details/gtbikengif.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.svipenyu.cn/Article/details/gtpwlaqkai.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.kuanghao11.cn/Article/details/gtugkllvvb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zdqjudy.top/Article/details/gtytigrdic.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfplxfcw.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258888.top/Article/details/gtztzwdzbe.html

Go:   go f()
来源：http://dali.chenzaomai.com/Article/details/gtiuiquvsd.html

Ruby: Thread.new { f }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifnfneki.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigfzy.top/Article/details/gtuvlusumm.html

[O02] 使用线程池
来源：http://dali.xziqi.cn/Article/details/gtlkrxkoon.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aizwys.cn/Article/details/gtiiragmco.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yvedp.cn/Article/details/gtqcitoqiq.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258.top/Article/details/gtmxqwjdlf.html

TS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gtfjvvznkp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zdqjudy.top/Article/details/gtnqlmsrqh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxeflqwd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sweek.top/Article/details/gtrtmypnfa.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinghuilouyu.cn/Article/details/gtpefcxagw.html

[O03] 加锁保护共享数据
来源：http://dali.yanxiufei.cn/Article/details/gtgkuemswv.html

Py:   with lock: shared += 1
来源：http://dali.cucudq.cn/Article/details/gtquootzlx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shangyingyoupin.top/Article/details/gtyhapcnfc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinghuilouyu.cn/Article/details/gtukbdmceq.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gtmpyeltem.html

Java: synchronized (this) { shared++; }
来源：http://dali.cucudq.cn/Article/details/gtorbiubwd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuanzhike.top/Article/details/gtlaowetim.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daria6918.cn/Article/details/gteblgqtkw.html

C#:   lock (gate) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gteatzzkoe.html

[O04] 定义异步函数并等待
来源：http://dali.nwbrower.top/Article/details/gtyrkbepti.html

Py:   async def f():⏎    await g()
来源：http://dali.haohaochexian.top/Article/details/gtefoeytrh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cashguo.top/Article/details/gtuummbedw.html

JS:   async function f() { await g(); }
来源：http://dali.smart0.xyz/Article/details/gthedpexsp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sxryk.cn/Article/details/gtetyozrsb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.c1oappe.top/Article/details/gtdjswarxt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shuidangran.top/Article/details/gtxbtdizjl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuetiantiany.cn/Article/details/gtfjvkkkpe.html

C#:   async Task F() { await G(); }
来源：http://dali.zhengqikj.top/Article/details/gttmohlfxw.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhiwuduotai.top/Article/details/gtrphbbcul.html

Py:   asyncio.gather(*tasks)
来源：http://dali.9152youxi.cn/Article/details/gtqjlvlsyh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xinyue.icu/Article/details/gtvkiurxfj.html

JS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gturvzoygb.html

TS:   await Promise.all(tasks)
来源：http://dali.jiagoushi.top/Article/details/gtlujscjty.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zdqjudy.top/Article/details/gthjgkdcsm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.birdmap.top/Article/details/gtmjsoieze.html

Ruby: threads.map(&:join)
来源：http://dali.sufxvd.cn/Article/details/gtrskfaofq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgufenzy.top/Article/details/gtigmcuadg.html

[O06] 使用进程池
来源：http://dali.yj20258888.top/Article/details/gtwhlbbpcn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nwbrower.top/Article/details/gttbxscwmu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj20258888.top/Article/details/gtskusijsz.html

JS:   // child_process / cluster 模块
来源：http://dali.birdmap.top/Article/details/gtwljdiags.html

TS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gtpbezqlno.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fzhhl.top/Article/details/gttkkbcfgo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sysykeji.top/Article/details/gtndmzaloz.html

Ruby: // fork 块
来源：http://dali.shuidangran.top/Article/details/gtxhictdiy.html

C#:   Parallel.For
来源：http://dali.0kj1m.cn/Article/details/gthakmomos.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtfsigepxl.html

P. 常用工具函数
来源：http://dali.pengpengdd.cyou/Article/details/gtakejtvyu.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtgfnnbqup.html

[P01] 生成 UUID
来源：http://dali.nanxinkj.top/Article/details/gtscjrlekq.html

Py:   str(uuid.uuid4())
来源：http://dali.wangdashe.top/Article/details/gtysffnpgp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guowangkeji.top/Article/details/gttltxkgiv.html

JS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gtictoxyvv.html

TS:   crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gtiojiyosn.html

Java: UUID.randomUUID().toString()
来源：http://dali.havefunace.top/Article/details/gtxpayjdnx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj20258.top/Article/details/gtzhsptdeb.html

Ruby: SecureRandom.uuid
来源：http://dali.fengsongda.top/Article/details/gtauejjzme.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jyoumei.cn/Article/details/gthjjuczmr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yonumen.top/Article/details/gtepmmiulx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yanxiufei.cn/Article/details/gtcjksavvr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gotoacloud.top/Article/details/gtihetkuzr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cdnleiting.top/Article/details/gtakvkxeba.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ivvv.top/Article/details/gtyaymgusd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ppjwa.cn/Article/details/gtrvsxxrrm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aibaodan.cn/Article/details/gtezkjigbw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fzhhl.top/Article/details/gtrdinmelq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tian-w.cn/Article/details/gtketbkgxz.html

[P03] 生成短随机字符串
来源：http://dali.tanke756.top/Article/details/gtuirtmvpk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jqgufenzy.top/Article/details/gtbuvnalol.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenzaomai.com/Article/details/gtquzhhxwh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gtzbyruwrm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gtyajsazdi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hywenlv.cn/Article/details/gtzfxgpaqi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.bjfxy.top/Article/details/gtotwjsvdz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.316326.xyz/Article/details/gtzkjcykqs.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daxiang520.top/Article/details/gtgooesmar.html

[P04] 求长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gturgirfse.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.quarkkingdee.top/Article/details/gtylqzthdq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtjuclycrg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gtzvzmdjji.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gtfidhiejn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.daria6918.cn/Article/details/gtnytqbvgr.html

Go:   len(arr);  len(m)
来源：http://dali.gzhubu.top/Article/details/gtgfgiowdb.html

Ruby: x.length;  x.size
来源：http://dali.tian-w.cn/Article/details/gtfrkpnryb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nanxinkj.top/Article/details/gtfixqtxsx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.pengpengdd.cyou/Article/details/gtldhdvgjv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tian-w.cn/Article/details/gtvelvknms.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sufxvd.cn/Article/details/gtsifipgir.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xuetiantiany.cn/Article/details/gtwsleckmu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258888.top/Article/details/gtusiafccl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yanxiufei.cn/Article/details/gtodcpdwif.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cdnleiting.top/Article/details/gtkpczcvfz.html

Ruby: a == b
来源：http://dali.jlsjyb.cn/Article/details/gtuushhxds.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.0kj1m.cn/Article/details/gtftuscuip.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuxming.cn/Article/details/gtfttjwoxn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jyoumei.cn/Article/details/gtahchzknm.html

PHP:  if (empty($x)) {}
来源：http://dali.zdqjudy.top/Article/details/gtwzgsdkck.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yvedp.cn/Article/details/gtsnumwrfj.html

TS:   if (x == null) {}
来源：http://dali.zhoulong.xyz/Article/details/gtwvxalyan.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtqpvesdxw.html

Go:   if x == nil {}
来源：http://dali.hongshengwenyu.top/Article/details/gtfnyxtrpz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.kuanghao11.cn/Article/details/gtcgjmpcub.html

C#:   if (x is null) {}
来源：http://dali.andypj.xyz/Article/details/gtsslrmjhg.html

[P07] 防抖与节流
来源：http://dali.jqgfzy.top/Article/details/gtjnfmczmj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shuidangran.top/Article/details/gtgqijvamj.html

PHP:  // 手写时间戳比较
来源：http://dali.svipenyu.cn/Article/details/gtdlcpwlwi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuxming.cn/Article/details/gtzvmhrzli.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gtbnlgrbmj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cashguo.top/Article/details/gtwjdcqyrq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoinfwunc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.guowangkeji.top/Article/details/gtkwspgrqn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhbuqlbi.html

[P08] 处理浮点精度问题
来源：http://dali.hnqzz.top/Article/details/gtjraicblg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cdnleiting.top/Article/details/gtvjiputar.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.0kj1m.cn/Article/details/gtkaqumgco.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dashuyun.cn/Article/details/gtbshocnkr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gtlxrjsleg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.guowangkeji.top/Article/details/gtepkywwxf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nanxinkj.top/Article/details/gtsmwglurh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cashguo.top/Article/details/gtgegqwqur.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ehwqpu.com/Article/details/gthchbruic.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtyxstsrub.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ppjwa.cn/Article/details/gtjcwymmce.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtfzllrgns.html

[Q01] 创建表
来源：http://dali.cucudq.cn/Article/details/gtkggtzmgd.html

CREATE TABLE users (
来源：http://dali.zhongyouzk.top/Article/details/gtlhgvlnkh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gtfewdopuk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gtyfnfcibg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuanzhike.top/Article/details/gtqehjemgz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dianchejie.cn/Article/details/gtdzvxogij.html

);
来源：http://dali.cqqwz.cn/Article/details/gtfppwbfbp.html

[Q02] 创建带外键的表
来源：http://dali.yuxming.cn/Article/details/gtpldhyuor.html

CREATE TABLE orders (
来源：http://dali.ppjwa.cn/Article/details/gtzzxrpbre.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gtvqktlmyr.html

user_id INT NOT NULL,
来源：http://dali.sxryk.cn/Article/details/gtqrupxwaq.html

amount DECIMAL(10, 2),
来源：http://dali.andypj.xyz/Article/details/gtjuoyupmb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenlongwang.top/Article/details/gtcfunmumc.html

);
来源：http://dali.ydzc1.top/Article/details/gtxupouvgj.html

[Q03] 增加列
来源：http://dali.tian-w.cn/Article/details/gtylvxmgos.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yvedp.cn/Article/details/gttrtsdzcw.html

[Q04] 修改列类型
来源：http://dali.jianghu66.top/Article/details/gtejbvgpus.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jlsjyb.cn/Article/details/gtpjexcjnx.html

[Q05] 重命名列
来源：http://dali.zhiwuduotai.top/Article/details/gttbjnbbpx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.meibo888.top/Article/details/gtziwdmyle.html

[Q06] 删除列
来源：http://dali.jianghu66.top/Article/details/gtpuxcdrpg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hammf.cn/Article/details/gtefpgvjja.html

[Q07] 删除表
来源：http://dali.hongshengwenyu.top/Article/details/gtzxunupfg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.pycfn.com/Article/details/gtnlnjromh.html

[Q08] 创建普通索引
来源：http://dali.zhiwuduotai.top/Article/details/gthiyonred.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gtldoahldw.html

[Q09] 创建唯一索引
来源：http://dali.wangdashe.top/Article/details/gtkdskwlmu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gotoacloud.top/Article/details/gtlmkudhrw.html

[Q10] 插入单行
来源：http://dali.feifeiyinyue.top/Article/details/gtgugtasul.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.c1oappe.top/Article/details/gtqrtozyqc.html

[Q11] 一次插入多行
来源：http://dali.jinqigfzy.top/Article/details/gtmajuhhla.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtbgcdqgnu.html

[Q12] 插入后取自增 ID
来源：http://dali.shuidangran.top/Article/details/gtixpftmvw.html


<!-- 参考信息 -->