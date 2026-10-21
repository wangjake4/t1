代发 wailian999

Java: public static void main(String[] args)
来源：http://dali.nanxinkj.top/Article/details/gtadevolpz.html

Go:   func main()
来源：http://dali.xziqi.cn/Article/details/gtjdhawgry.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yonumen.top/Article/details/gtuqwrfigf.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigufen.top/Article/details/gthqiiogvc.html

[M08] 获取系统与运行时信息
来源：http://dali.tian-w.cn/Article/details/gtruferehb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zdqjudy.top/Article/details/gtqoeifrkc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hysaishi.cn/Article/details/gtjteaiblb.html

JS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gtkxfuztvs.html

TS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gtckkybgsu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yonumen.top/Article/details/gtbphoqtbo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shuidangran.top/Article/details/gtuvdlcvgv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.andypj.xyz/Article/details/gthnomtbov.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhiwuduotai.top/Article/details/gtsgtcdiae.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gthqmvdtcd.html

N. 数据结构与算法
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmsmnmzt.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtvswckkse.html

[N01] 二分查找（有序数组）
来源：http://dali.vqdsnc.cn/Article/details/gtajxyszgx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gterhjolug.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ydzc1.top/Article/details/gtlcjwguas.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtjitnfjyo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jiagoushi.top/Article/details/gtrfxfcazr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtsxqctqxx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtlwlvktyn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guannengcc.top/Article/details/gtzeedxkqz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtocxlxwge.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbuvdhfix.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jyoumei.cn/Article/details/gtadhvtprd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.svipenyu.cn/Article/details/gtgluozwnq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtggqjihig.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtjeahiuwg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.andypj.xyz/Article/details/gtjxcnboqt.html

Go:   slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gtplzgdpjy.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gtsgsxoclj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sxryk.cn/Article/details/gtmlktrqhs.html

[N03] 快速排序（分治示例）
来源：http://dali.tianlin.xyz/Article/details/gtuassknmz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cashguo.top/Article/details/gtnyouvwwt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yvedp.cn/Article/details/gtkzirvwaw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gtanqpjbgj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlqzhvnf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shzxlz.cn/Article/details/gtsktypfkg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.bjfxy.top/Article/details/gtylmwympo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sysykeji.top/Article/details/gtktfikzmp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gtuirqbbre.html

[N04] 斐波那契数列
来源：http://dali.andypj.xyz/Article/details/gtooaatbit.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gtzcvdjalp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuxming.cn/Article/details/gtgcublhxs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtbjoohvwd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtewiqrfdd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.iojbl.cn/Article/details/gttcisyxup.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gaohongyu789.top/Article/details/gtqyowlbho.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhhebmoa.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gtttouwwrf.html

[N05] 最大公约数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgsqumrv.html

Py:   math.gcd(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtwtjxsgxr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fengsongda.top/Article/details/gtjgaczofy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aibaodan.cn/Article/details/gtorjpbkjh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzockuzd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hfpthk.cn/Article/details/gtnesmqfro.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.snrcjt.cn/Article/details/gtqrfaleax.html

Ruby: a.gcd(b)
来源：http://dali.yongpay.top/Article/details/gtzrtcwogu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gtujuqqkuj.html

[N06] 判断回文字符串
来源：http://dali.xuanzx.com/Article/details/gtntlawtjh.html

Py:   s == s[::-1]
来源：http://dali.iojbl.cn/Article/details/gtdiqewnve.html

PHP:  $s === strrev($s);
来源：http://dali.jianghu66.top/Article/details/gtwhjuukil.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtpbnwanqp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtwngofdma.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.c1oappe.top/Article/details/gtctizvfem.html

Go:   // 双指针从两端比较
来源：http://dali.bjfxy.top/Article/details/gtyeqlnhaj.html

Ruby: s == s.reverse
来源：http://dali.zdqjudy.top/Article/details/gtwlpqkpbu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gtipebmmif.html

[N07] 两数之和（返回下标）
来源：http://dali.yvedp.cn/Article/details/gtuksdfklx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gotoacloud.top/Article/details/gtwjdedqws.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tian-w.cn/Article/details/gtmgydiiuq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.havefunace.top/Article/details/gtbfdltoaz.html

TS:   // 手写 Map<string, number>
来源：http://dali.zycfv.cn/Article/details/gtgnsfvjjv.html

Java: // 手写 HashMap
来源：http://dali.xuanzx.com/Article/details/gtwbkywqvm.html

Go:   // 手写 map[int]int
来源：http://dali.jlsjyb.cn/Article/details/gtctowdfov.html

Ruby: // 手写 Hash
来源：http://dali.svipenyu.cn/Article/details/gtjhddicgm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tian-w.cn/Article/details/gtdoigenxz.html

[N08] 生成全排列
来源：http://dali.smart0.xyz/Article/details/gtafkcfaev.html

Py:   itertools.permutations(arr)
来源：http://dali.zhixingplan.top/Article/details/gtgljpowpc.html

PHP:  // 手写递归交换
来源：http://dali.yvedp.cn/Article/details/gtnyzozdkn.html

JS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtfmgsgxll.html

TS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtvoxbzdlg.html

Java: // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtsamulsfn.html

Go:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtxffcioli.html

Ruby: arr.permutation.to_a
来源：http://dali.dashuyun.cn/Article/details/gtezbujsmw.html

C#:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfcpiqtl.html

[N09] 栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gtpnujzsbt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gtvkupizgl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.aizwys.cn/Article/details/gtxwcvsudw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtzevlsmwy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.svipenyu.cn/Article/details/gtutxxslyl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtcaxcfquo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhoulong.xyz/Article/details/gtzdfrhlve.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgluuhye.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gogol.net.cn/Article/details/gtijgtdpfo.html

[N10] 链表节点定义
来源：http://dali.sweek.top/Article/details/gtuoycihug.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pycfn.com/Article/details/gtflusgqte.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhixingplan.top/Article/details/gtvteynmrh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.pycfn.com/Article/details/gtyfgwkmil.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.kuanghao11.cn/Article/details/gthfmhebza.html

Java: class Node { int v; Node next; }
来源：http://dali.sufxvd.cn/Article/details/gtmyvmncho.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gaohongyu789.top/Article/details/gtnrktgele.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shuidangran.top/Article/details/gtkrpajblr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jyoumei.cn/Article/details/gtapjtbsfl.html

[N11] 二叉树中序遍历
来源：http://dali.jlsjyb.cn/Article/details/gtpzeovnut.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sysykeji.top/Article/details/gtpopjnosl.html

PHP:  // 手写递归函数
来源：http://dali.jianghu66.top/Article/details/gtebsrafuj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gtpeqlkugb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gtnkxknvks.html

Java: // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gtojktydfz.html

Go:   // 手写递归
来源：http://dali.tian-w.cn/Article/details/gtbgacutyl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zycfv.cn/Article/details/gtqnzzxqil.html

C#:   // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gtkbnswiuo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yangfankeji.com/Article/details/gtkwwgnbmb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zycfv.cn/Article/details/gtpewnekgz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ehwqpu.com/Article/details/gtggjbjuuj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhiwuduotai.top/Article/details/gtwjzsvmyh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gtgmvittaq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gtrmzcwjzd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tianlin.xyz/Article/details/gtcnhqihsc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jyoumei.cn/Article/details/gtdaadyimc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtkcivxxtn.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtnyhyywpf.html

O. 并发与异步
来源：http://dali.cucudq.cn/Article/details/gtqeomhpix.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtdnngqegq.html

[O01] 启动一个线程
来源：http://dali.hywenlv.cn/Article/details/gtilxhmmne.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gttkmjbtzj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ydzc1.top/Article/details/gtpzphxsiz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuanzhike.top/Article/details/gtjluojbqh.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gtvdjpwedy.html

Java: new Thread(() -> f()).start()
来源：http://dali.vqdsnc.cn/Article/details/gtdumznduw.html

Go:   go f()
来源：http://dali.nwbrower.top/Article/details/gtqewbvwqh.html

Ruby: Thread.new { f }
来源：http://dali.zhongyouzk.top/Article/details/gtovwtdzki.html

C#:   Task.Run(() => F());
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqsxyilo.html

[O02] 使用线程池
来源：http://dali.chenlongwang.top/Article/details/gtjxybapss.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zycfv.cn/Article/details/gtvmaukspt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sufxvd.cn/Article/details/gtbnidkbkn.html

JS:   // worker_threads 线程池
来源：http://dali.haohaochexian.top/Article/details/gtalrutbsf.html

TS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gtwkedxanx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yanxiufei.cn/Article/details/gtljizqlpj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ybcxt.top/Article/details/gtvhrwsqmg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aizwys.cn/Article/details/gtpevidwgw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmxvurgm.html

[O03] 加锁保护共享数据
来源：http://dali.hongshengwenyu.top/Article/details/gtxrynblre.html

Py:   with lock: shared += 1
来源：http://dali.chenjidiqi.icu/Article/details/gtqnmljvlj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hongshengwenyu.top/Article/details/gtkxouktcw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.aizwys.cn/Article/details/gtoymdqypk.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gtvmrpxija.html

Java: synchronized (this) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gtkmchvxgn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yvedp.cn/Article/details/gteblejalj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hysaishi.cn/Article/details/gturceyfdj.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gtctpsjvis.html

[O04] 定义异步函数并等待
来源：http://dali.dianchejie.cn/Article/details/gtllqcrwor.html

Py:   async def f():⏎    await g()
来源：http://dali.yueranfly.top/Article/details/gtwywkeicb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgfzy.top/Article/details/gtjfijlqnr.html

JS:   async function f() { await g(); }
来源：http://dali.jianghu66.top/Article/details/gtlvtkrtlh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258888.top/Article/details/gtwmaemeed.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.haohaochexian.top/Article/details/gtmkhjlnam.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jyoumei.cn/Article/details/gttcjuakee.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gzhubu.top/Article/details/gtlmhycmsc.html

C#:   async Task F() { await G(); }
来源：http://dali.sysykeji.top/Article/details/gthpcrzsau.html

[O05] 并发执行并等待全部完成
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuliyvurf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdaqlfqjq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gotoacloud.top/Article/details/gtgnofxigb.html

JS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gtrfyviuct.html

TS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gtepqjbeyl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jianghu66.top/Article/details/gtdfrxeeqy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.svipenyu.cn/Article/details/gtevnqhnqx.html

Ruby: threads.map(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gtxvcxbils.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fzhhl.top/Article/details/gtvwpzolie.html

[O06] 使用进程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpuwmkoz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fzhhl.top/Article/details/gthcfcizwx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhengqikj.top/Article/details/gtyllenuzf.html

JS:   // child_process / cluster 模块
来源：http://dali.pengpengdd.cyou/Article/details/gtpxamkzze.html

TS:   // child_process / cluster 模块
来源：http://dali.yvedp.cn/Article/details/gtnzxgjsxz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tianlin.xyz/Article/details/gtzunxtigz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.feifeiyinyue.top/Article/details/gtyxmsdidn.html

Ruby: // fork 块
来源：http://dali.316326.xyz/Article/details/gtbtjlbbbv.html

C#:   Parallel.For
来源：http://dali.xuetiantiany.cn/Article/details/gtnnkkhokh.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtwyrnzgmj.html

P. 常用工具函数
来源：http://dali.cdnleiting.top/Article/details/gtvlmufdla.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtrgpqyeoh.html

[P01] 生成 UUID
来源：http://dali.fzhhl.top/Article/details/gtnwokvntf.html

Py:   str(uuid.uuid4())
来源：http://dali.yangfankeji.com/Article/details/gtvdkktgce.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangdashe.top/Article/details/gtzkoymbhp.html

JS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gtudulhryc.html

TS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gtnxoxyzlr.html

Java: UUID.randomUUID().toString()
来源：http://dali.yongpay.top/Article/details/gtyjiallxh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cheryme.top/Article/details/gtiqipfzww.html

Ruby: SecureRandom.uuid
来源：http://dali.guannengcc.top/Article/details/gthibnoxio.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dianchejie.cn/Article/details/gtpcczlzep.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnqzz.top/Article/details/gtwuxfmrqz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nanxuanxn.top/Article/details/gtgsbnxmxs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xziqi.cn/Article/details/gtuytieckr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.dashuyun.cn/Article/details/gtrioypwdk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shuidangran.top/Article/details/gtnwkevuhu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gtubwujfxw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gogol.net.cn/Article/details/gtpwkpcfhl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hywenlv.cn/Article/details/gtnaudgwta.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.feifeiyinyue.top/Article/details/gttciagpiu.html

[P03] 生成短随机字符串
来源：http://dali.nanxuanxn.top/Article/details/gtsegmlfyp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.redwolf501.top/Article/details/gtlpldtpgm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zycfv.cn/Article/details/gtnatdzfor.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hysaishi.cn/Article/details/gtpkwapjsw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gthoalvxnp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtfouuhiec.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ehwqpu.com/Article/details/gtsdckrzda.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.mhx1999.top/Article/details/gtnfntbdqs.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj202588.top/Article/details/gtixmahiis.html

[P04] 求长度
来源：http://dali.zdqjudy.top/Article/details/gttwojgphu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jyoumei.cn/Article/details/gtjcogjlez.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtllaxuund.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gtmsvrfizb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xinyue.icu/Article/details/gtjrxpnnzm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ehwqpu.com/Article/details/gtjifhckrd.html

Go:   len(arr);  len(m)
来源：http://dali.gzhubu.top/Article/details/gtskhehqcp.html

Ruby: x.length;  x.size
来源：http://dali.wangdashe.top/Article/details/gtmrmqascj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cucudq.cn/Article/details/gtqkqjugrr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvllfocej.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ydzc1.top/Article/details/gtfnvzwimv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnuxtqpnn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fengsongda.top/Article/details/gtesvnxitj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gtyzaypqkq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tian-w.cn/Article/details/gtnvtcpuvc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtanaribwz.html

Ruby: a == b
来源：http://dali.wangshuangyany.cn/Article/details/gtalvelint.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ehwqpu.com/Article/details/gtlmhghpai.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xuetiantiany.cn/Article/details/gtzuhvbprp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.iojbl.cn/Article/details/gtucgusdlb.html

PHP:  if (empty($x)) {}
来源：http://dali.sweek.top/Article/details/gtzqftheym.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgfzy.top/Article/details/gtlofbhtpe.html

TS:   if (x == null) {}
来源：http://dali.jiagoushi.top/Article/details/gtjirkajve.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gtgudnebgh.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtknnjpbgs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.9152youxi.cn/Article/details/gtatlbxzfw.html

C#:   if (x is null) {}
来源：http://dali.tanke756.top/Article/details/gtxfxqebkm.html

[P07] 防抖与节流
来源：http://dali.hammf.cn/Article/details/gtcxnghlcq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.quarkkingdee.top/Article/details/gttbsxryfg.html

PHP:  // 手写时间戳比较
来源：http://dali.zdqjudy.top/Article/details/gtoxysmfhd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gtozmzbzef.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gtqttllqtg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigufen.top/Article/details/gtrwbkodpj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fzhhl.top/Article/details/gtaymkpfxx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.c1oappe.top/Article/details/gtmgogsapp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jlsjyb.cn/Article/details/gthlnqefks.html

[P08] 处理浮点精度问题
来源：http://dali.andypj.xyz/Article/details/gtqmaqtjzg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shzxlz.cn/Article/details/gtdclgqsqj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yongpay.top/Article/details/gtbjtpsohy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhiwuduotai.top/Article/details/gtjnexlrdv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yj20258.top/Article/details/gtdeixuoqo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258.top/Article/details/gthgyolkif.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.vqdsnc.cn/Article/details/gthybuydjc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.kuanghao11.cn/Article/details/gtcethmhpg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pengpengdd.cyou/Article/details/gtlpcjrbuj.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtzqvlexgq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhiwuduotai.top/Article/details/gtiwhzqepv.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtnwngxfxu.html

[Q01] 创建表
来源：http://dali.xinyue.icu/Article/details/gtbfgkhlfu.html

CREATE TABLE users (
来源：http://dali.gogol.net.cn/Article/details/gtmriyytzg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gtoitmqicp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sysykeji.top/Article/details/gtdnktplxf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.daxiang520.top/Article/details/gtticcepfj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.guowangkeji.top/Article/details/gtappalgmp.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gttzbuuhgq.html

[Q02] 创建带外键的表
来源：http://dali.nanxinkj.top/Article/details/gtlxuqkens.html

CREATE TABLE orders (
来源：http://dali.zdqjudy.top/Article/details/gtnuibvxov.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gtpsbuyucp.html

user_id INT NOT NULL,
来源：http://dali.yj20258888.top/Article/details/gtwqtceyrm.html

amount DECIMAL(10, 2),
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvbomcty.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dashuyun.cn/Article/details/gtjgryupqt.html

);
来源：http://dali.nanxuanxn.top/Article/details/gtmqndosqo.html

[Q03] 增加列
来源：http://dali.fzhhl.top/Article/details/gtlljhfylb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgymukdm.html

[Q04] 修改列类型
来源：http://dali.sysykeji.top/Article/details/gtuckvexqr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.9152youxi.cn/Article/details/gtitzgubnu.html

[Q05] 重命名列
来源：http://dali.dashuyun.cn/Article/details/gtyzwfslgy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigufen.top/Article/details/gtrfcwmqeq.html

[Q06] 删除列
来源：http://dali.yanxiufei.cn/Article/details/gtkaeqycuq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj202588.top/Article/details/gtziexibwe.html

[Q07] 删除表
来源：http://dali.svipenyu.cn/Article/details/gtlmvxnrqi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hfpthk.cn/Article/details/gtwqxlajqb.html

[Q08] 创建普通索引
来源：http://dali.jlsjyb.cn/Article/details/gtgzponpjk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.fzhhl.top/Article/details/gtcqclegvl.html

[Q09] 创建唯一索引
来源：http://dali.xuetiantiany.cn/Article/details/gtxfiyivcm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gtxrywvlzo.html

[Q10] 插入单行
来源：http://dali.shangyingyoupin.top/Article/details/gtsgvknzpk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gtzdbnqemi.html

[Q11] 一次插入多行
来源：http://dali.hysaishi.cn/Article/details/gticyoeest.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gtuuuxrykp.html

[Q12] 插入后取自增 ID
来源：http://dali.gzhubu.top/Article/details/gtaekcejii.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aizwys.cn/Article/details/gtvfzdlalo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258.top/Article/details/gtnikhvabs.html

[Q13] 忽略重复插入
来源：http://dali.meibo888.top/Article/details/gtaaykcoxw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj20258.top/Article/details/gtlalsxbgg.html

[Q14] 存在则更新（upsert）
来源：http://dali.yueranfly.top/Article/details/gtmtdotcxo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.0kj1m.cn/Article/details/gtpzpkhaog.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.c1oappe.top/Article/details/gtxnrrosah.html

[Q15] 查询全部
来源：http://dali.meibo888.top/Article/details/gtgxvfafit.html


<!-- 参考信息 -->