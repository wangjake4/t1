代发 wailian999

Java: public static void main(String[] args)
来源：http://dali.chenzaomai.com/Article/details/gtajwyekax.html

Go:   func main()
来源：http://dali.shanyushiyangtech.top/Article/details/gteyvoavta.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ivvv.top/Article/details/gtyixdzjvz.html

C#:   static void Main(string[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmanerxsu.html

[M08] 获取系统与运行时信息
来源：http://dali.hnqzz.top/Article/details/gtdngukrat.html

Py:   platform.system();  platform.python_version()
来源：http://dali.kuanghao11.cn/Article/details/gtaezojbsw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sweek.top/Article/details/gtbxrwombb.html

JS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gtbutkxtig.html

TS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gtmunvojgm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxhvfhym.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvbcoadd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258.top/Article/details/gtgldldehw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.316326.xyz/Article/details/gtpnvylqoz.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtzvucwzyx.html

N. 数据结构与算法
来源：http://dali.gaohongyu789.top/Article/details/gtuftexuii.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtrrpiquxd.html

[N01] 二分查找（有序数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gtnsuvrsln.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yvedp.cn/Article/details/gttxloggxs.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtniqcuwlu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtdsnclybb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gtpnztddku.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtwvojxqrb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gteoqlqgzp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jiagoushi.top/Article/details/gtcxdirqip.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcswrdjr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yonumen.top/Article/details/gtfseusywn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gtjgrodpum.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zycfv.cn/Article/details/gtzwiqydjz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgjiqfzr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gtbogpxool.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.meibo888.top/Article/details/gtuorunfrj.html

Go:   slices.Sort(arr)
来源：http://dali.jqgfzy.top/Article/details/gtsrcggovc.html

Ruby: arr.sort
来源：http://dali.hysaishi.cn/Article/details/gtkokyuyhf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtgztmvaxe.html

[N03] 快速排序（分治示例）
来源：http://dali.zhongyouzk.top/Article/details/gtgbvocayp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guannengcc.top/Article/details/gttvddwhyh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ivvv.top/Article/details/gtyrpllruz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjucqqgyt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gtaaoostmf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sweek.top/Article/details/gtkcahcscq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guannengcc.top/Article/details/gtiamsytuz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gotoacloud.top/Article/details/gtuceofzzm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.smart0.xyz/Article/details/gtrvdlltpw.html

[N04] 斐波那契数列
来源：http://dali.fzhhl.top/Article/details/gtpprawemg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gtjqwnmcwe.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.c1oappe.top/Article/details/gtakgjbocq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gteeiwytxd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtuedrfxcq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtstuyfsyx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.iojbl.cn/Article/details/gtqxmbwnlr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtqzfgbsgl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gtukuoyupp.html

[N05] 最大公约数
来源：http://dali.guowangkeji.top/Article/details/gtlhmidrvj.html

Py:   math.gcd(a, b)
来源：http://dali.cheryme.top/Article/details/gtzolgvdnw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenzaomai.com/Article/details/gtxuqbglwc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gtvitrpdgi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gtnjkwyqmq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuxming.cn/Article/details/gtpfuvcjkq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuxming.cn/Article/details/gtboakikca.html

Ruby: a.gcd(b)
来源：http://dali.gogol.net.cn/Article/details/gtkugfuaft.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.0kj1m.cn/Article/details/gtpwndcwlh.html

[N06] 判断回文字符串
来源：http://dali.chenlongwang.top/Article/details/gtshufudmk.html

Py:   s == s[::-1]
来源：http://dali.iojbl.cn/Article/details/gtcyiecjav.html

PHP:  $s === strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gtrjvoisen.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtfzgxeszi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtoykmbskn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxuanxn.top/Article/details/gtgxgdmhuc.html

Go:   // 双指针从两端比较
来源：http://dali.hnxiangtu.top/Article/details/gtvaikudjm.html

Ruby: s == s.reverse
来源：http://dali.316326.xyz/Article/details/gtkeibnsbf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gtgncawqnc.html

[N07] 两数之和（返回下标）
来源：http://dali.mhx1999.top/Article/details/gtjeytdopg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenzaomai.com/Article/details/gtaoaxkstk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrftqnje.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jiagoushi.top/Article/details/gtncfnacpl.html

TS:   // 手写 Map<string, number>
来源：http://dali.yangfankeji.com/Article/details/gtdzabgowh.html

Java: // 手写 HashMap
来源：http://dali.yonumen.top/Article/details/gtpvdzscrh.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gtmhfdusqw.html

Ruby: // 手写 Hash
来源：http://dali.nanxinkj.top/Article/details/gtgfttukjt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yueranfly.top/Article/details/gtekzkqoxe.html

[N08] 生成全排列
来源：http://dali.gotoacloud.top/Article/details/gtihismotg.html

Py:   itertools.permutations(arr)
来源：http://dali.yvedp.cn/Article/details/gtdetykujs.html

PHP:  // 手写递归交换
来源：http://dali.zhiwuduotai.top/Article/details/gtxstefwje.html

JS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gteewtaxng.html

TS:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtyfclmmyb.html

Java: // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtgdedtohd.html

Go:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtlxihfgnq.html

Ruby: arr.permutation.to_a
来源：http://dali.ybcxt.top/Article/details/gtvcofznml.html

C#:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtsvimeekj.html

[N09] 栈与队列
来源：http://dali.wangshuangyany.cn/Article/details/gtxxwfouul.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.9152youxi.cn/Article/details/gtkzsptssx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.redwolf501.top/Article/details/gttxqxjkay.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gtqhqxlmvl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hysaishi.cn/Article/details/gtoxhvshgm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.wangdashe.top/Article/details/gtzjcowmol.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yongpay.top/Article/details/gtkvoqaitc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gteyyessrw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cashguo.top/Article/details/gtidwjpudp.html

[N10] 链表节点定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmmhdnca.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cheryme.top/Article/details/gtwrfvavdr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cheryme.top/Article/details/gtjeykomad.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.haohaochexian.top/Article/details/gtwxpztozh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.snrcjt.cn/Article/details/gtfiodjxqo.html

Java: class Node { int v; Node next; }
来源：http://dali.hnxiangtu.top/Article/details/gtjbchcqea.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sysykeji.top/Article/details/gtpllyrhqu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yongpay.top/Article/details/gtwhoibfat.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenzaomai.com/Article/details/gtqwvnfkib.html

[N11] 二叉树中序遍历
来源：http://dali.chenzaomai.com/Article/details/gtaicelucg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jqgfzy.top/Article/details/gthxomhupl.html

PHP:  // 手写递归函数
来源：http://dali.aizwys.cn/Article/details/gtyvzdnnnw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gtrtqzbvsn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.vqdsnc.cn/Article/details/gtfkiimcen.html

Java: // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtrpxnfdtc.html

Go:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gtumwllicy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sweek.top/Article/details/gtyoeuthxf.html

C#:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtkfpywvka.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.kuanghao11.cn/Article/details/gtkfnnuzon.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yueranfly.top/Article/details/gthrpbhcdm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hnqzz.top/Article/details/gtxydawmkx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gtlzhhskdd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hammf.cn/Article/details/gtpufxsjqd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gtaamoinez.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xuetiantiany.cn/Article/details/gtpydjrnpa.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.c1oappe.top/Article/details/gtoazwrjvy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gtshhttesq.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtivveouji.html

O. 并发与异步
来源：http://dali.hnqzz.top/Article/details/gtgwpxrezt.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtmayknikg.html

[O01] 启动一个线程
来源：http://dali.meibo888.top/Article/details/gtusgyontb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenjidiqi.icu/Article/details/gtwrdvngpc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cucudq.cn/Article/details/gtvojcqxvo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.mhx1999.top/Article/details/gtmvdyamfh.html

TS:   // 同 JS
来源：http://dali.kuanghao11.cn/Article/details/gtogersrds.html

Java: new Thread(() -> f()).start()
来源：http://dali.shuidangran.top/Article/details/gtsheqsify.html

Go:   go f()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibdpwuqz.html

Ruby: Thread.new { f }
来源：http://dali.chenlongwang.top/Article/details/gtjejmsanu.html

C#:   Task.Run(() => F());
来源：http://dali.hywenlv.cn/Article/details/gtigptttcs.html

[O02] 使用线程池
来源：http://dali.guowangkeji.top/Article/details/gtcexhpzgd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.iojbl.cn/Article/details/gtyaogjaun.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhongyouzk.top/Article/details/gtrkjiimay.html

JS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gtqspmeuhq.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gtrdzdyfjk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jlsjyb.cn/Article/details/gtegunmcsi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gzhubu.top/Article/details/gtfrzinfpg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aibaodan.cn/Article/details/gtrzkvchmm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnxiangtu.top/Article/details/gtxzjbfqbo.html

[O03] 加锁保护共享数据
来源：http://dali.shzxlz.cn/Article/details/gtbzrmwvir.html

Py:   with lock: shared += 1
来源：http://dali.sufxvd.cn/Article/details/gtnhhhloze.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zycfv.cn/Article/details/gtkpuzowix.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.9152youxi.cn/Article/details/gttxixqabc.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gtmzmvmmdj.html

Java: synchronized (this) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gtkakssjmx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgfzy.top/Article/details/gtfpimvcbg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj202588.top/Article/details/gtlxrfvvmg.html

C#:   lock (gate) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gtowmeixvg.html

[O04] 定义异步函数并等待
来源：http://dali.hysaishi.cn/Article/details/gtriisasov.html

Py:   async def f():⏎    await g()
来源：http://dali.hysaishi.cn/Article/details/gtorigrbvb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xziqi.cn/Article/details/gtorxgvebr.html

JS:   async function f() { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gtxcwzpoth.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gtobcyuuli.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.iojbl.cn/Article/details/gtctywrcfa.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuanzhike.top/Article/details/gtnjokgkrl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sufxvd.cn/Article/details/gtcuzfbrtg.html

C#:   async Task F() { await G(); }
来源：http://dali.yonumen.top/Article/details/gtbjftjfdx.html

[O05] 并发执行并等待全部完成
来源：http://dali.hammf.cn/Article/details/gtnzmnfdwe.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gotoacloud.top/Article/details/gtrqvjslww.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jiagoushi.top/Article/details/gtebpbeilv.html

JS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gtcfvdnwso.html

TS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gtwsreqhdu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnxiangtu.top/Article/details/gtsmmkduft.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tanke756.top/Article/details/gtbcrtckag.html

Ruby: threads.map(&:join)
来源：http://dali.mhx1999.top/Article/details/gtbnatuiri.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nwbrower.top/Article/details/gtpcavopob.html

[O06] 使用进程池
来源：http://dali.redwolf501.top/Article/details/gtzuxzdlqa.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.andypj.xyz/Article/details/gtngdxyrry.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tanke756.top/Article/details/gtzgukdroc.html

JS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gtpjybcbmi.html

TS:   // child_process / cluster 模块
来源：http://dali.fzhhl.top/Article/details/gtnrqcsjvy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.316326.xyz/Article/details/gtsrdktndt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.vqdsnc.cn/Article/details/gtweerourb.html

Ruby: // fork 块
来源：http://dali.vqdsnc.cn/Article/details/gtpxwaimwx.html

C#:   Parallel.For
来源：http://dali.nanxinkj.top/Article/details/gtzvfwxkdr.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtgljcxtkm.html

P. 常用工具函数
来源：http://dali.pycfn.com/Article/details/gtpivtijob.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtixbzzzhc.html

[P01] 生成 UUID
来源：http://dali.guannengcc.top/Article/details/gtjwxegqct.html

Py:   str(uuid.uuid4())
来源：http://dali.pengpengdd.cyou/Article/details/gtnumvowym.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangshuangyany.cn/Article/details/gtkbirrzof.html

JS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gtudqlndec.html

TS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gtcrmbelev.html

Java: UUID.randomUUID().toString()
来源：http://dali.jianghu66.top/Article/details/gtnggxivmi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gzhubu.top/Article/details/gtrzvekpwt.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigufen.top/Article/details/gtcemnqzzi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jyoumei.cn/Article/details/gtdyglkrrk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.haohaochexian.top/Article/details/gtqmoxetpu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenzaomai.com/Article/details/gtyoschvft.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.guowangkeji.top/Article/details/gtbpsjhdpc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gaohongyu789.top/Article/details/gttebughkw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.haohaochexian.top/Article/details/gtbdziaehu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hammf.cn/Article/details/gtehcohcbz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfnxpvvy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xziqi.cn/Article/details/gtritrtgtn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hammf.cn/Article/details/gtmmvycbrm.html

[P03] 生成短随机字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlbkjgyo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zycfv.cn/Article/details/gtzhfxjdrj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gogol.net.cn/Article/details/gtxrpppxkj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gtceslnwym.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gtextcojrb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guannengcc.top/Article/details/gteedvevss.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.birdmap.top/Article/details/gtpddxnstj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhengqikj.top/Article/details/gtdtbywixi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhongyouzk.top/Article/details/gtnxkzbtaj.html

[P04] 求长度
来源：http://dali.jqgufenzy.top/Article/details/gtuehjramm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shangyingyoupin.top/Article/details/gtumhcocsa.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtcrerfthh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dashuyun.cn/Article/details/gtiqnnxgja.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cdnleiting.top/Article/details/gtvydvawgn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgfzy.top/Article/details/gtjvhfbeuo.html

Go:   len(arr);  len(m)
来源：http://dali.c1oappe.top/Article/details/gtedqacoej.html

Ruby: x.length;  x.size
来源：http://dali.chenlongwang.top/Article/details/gtmhzmxpwj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sxryk.cn/Article/details/gtacmiufnh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnajitpda.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shanyushiyangtech.top/Article/details/gtalnwjbjf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hongshengwenyu.top/Article/details/gtpvmdpuso.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sufxvd.cn/Article/details/gtkzrmyfec.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jlsjyb.cn/Article/details/gtivveabnt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.9152youxi.cn/Article/details/gtcqtrdsoy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ybcxt.top/Article/details/gtaaafpqen.html

Ruby: a == b
来源：http://dali.hfpthk.cn/Article/details/gttfylpwtb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yvedp.cn/Article/details/gtncnaomfa.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gzhubu.top/Article/details/gtvwkdxskz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.quarkkingdee.top/Article/details/gtnqbmjjyr.html

PHP:  if (empty($x)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvuoujik.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hysaishi.cn/Article/details/gtmdfqjjnp.html

TS:   if (x == null) {}
来源：http://dali.jiagoushi.top/Article/details/gtawlewbmu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gtbsupmbjr.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gthqcjrbpq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jyoumei.cn/Article/details/gtjijvhnmh.html

C#:   if (x is null) {}
来源：http://dali.gogol.net.cn/Article/details/gtqoyiyevv.html

[P07] 防抖与节流
来源：http://dali.hysaishi.cn/Article/details/gtaqwziyqf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hammf.cn/Article/details/gtopsmmxbf.html

PHP:  // 手写时间戳比较
来源：http://dali.yuanzhike.top/Article/details/gtrkxkklrk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtbcnvmnlk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gtmolsxyjr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yonumen.top/Article/details/gtlzafupvk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gzhubu.top/Article/details/gthukazqus.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hongshengwenyu.top/Article/details/gtqqpbtvnj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ppjwa.cn/Article/details/gtghvhkztd.html

[P08] 处理浮点精度问题
来源：http://dali.quarkkingdee.top/Article/details/gtjnsuniet.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhengqikj.top/Article/details/gtcbqzvose.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtewederwp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxiazpsm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cqqwz.cn/Article/details/gtqbwtbfbm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ivvv.top/Article/details/gtxbalqjfh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhvibatw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhixingplan.top/Article/details/gtqkkcttgt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.feifeiyinyue.top/Article/details/gtlhuubylx.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtuogbvtby.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.haohaochexian.top/Article/details/gttrdoltwl.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gttntgrsgb.html

[Q01] 创建表
来源：http://dali.bjfxy.top/Article/details/gtcatzaqix.html

CREATE TABLE users (
来源：http://dali.daria6918.cn/Article/details/gtirehmauk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xinyue.icu/Article/details/gtqibevyzn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhongyouzk.top/Article/details/gtgtyxvsgx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sysykeji.top/Article/details/gtczzhssas.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hfpthk.cn/Article/details/gttjtmncuf.html

);
来源：http://dali.jqgfzy.top/Article/details/gtchiheiah.html

[Q02] 创建带外键的表
来源：http://dali.zhoulong.xyz/Article/details/gtronhxhnt.html

CREATE TABLE orders (
来源：http://dali.redwolf501.top/Article/details/gtrvbsjjri.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hywenlv.cn/Article/details/gtqcgnboip.html

user_id INT NOT NULL,
来源：http://dali.daxiang520.top/Article/details/gtrdbqfzye.html

amount DECIMAL(10, 2),
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimmhohaq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinghuilouyu.cn/Article/details/gtarsedvqc.html

);
来源：http://dali.yuanzhike.top/Article/details/gtpxsjmbjr.html

[Q03] 增加列
来源：http://dali.yangfankeji.com/Article/details/gtgncljlfk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodnjxxys.html

[Q04] 修改列类型
来源：http://dali.cdnleiting.top/Article/details/gttjdxhtdb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hongshengwenyu.top/Article/details/gtjuxaiuuu.html

[Q05] 重命名列
来源：http://dali.jinghuilouyu.cn/Article/details/gtkumbcmyy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.fzhhl.top/Article/details/gtaszluvcg.html

[Q06] 删除列
来源：http://dali.zycfv.cn/Article/details/gtehptjpdb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangshuangyany.cn/Article/details/gtxavafwph.html

[Q07] 删除表
来源：http://dali.chenzaomai.com/Article/details/gtzmxxqhih.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shzxlz.cn/Article/details/gtpjjkzngl.html

[Q08] 创建普通索引
来源：http://dali.tanke756.top/Article/details/gtcvvurstc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gtwdwtbkec.html

[Q09] 创建唯一索引
来源：http://dali.yj20258888.top/Article/details/gtmqojozpp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gtyojijdwn.html

[Q10] 插入单行
来源：http://dali.birdmap.top/Article/details/gtgyxrewwa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.fengsongda.top/Article/details/gtstufciup.html

[Q11] 一次插入多行
来源：http://dali.fengsongda.top/Article/details/gtzjwbvkgn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.pycfn.com/Article/details/gtgqknerik.html

[Q12] 插入后取自增 ID
来源：http://dali.gzhubu.top/Article/details/gtjyhkwhnq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shuidangran.top/Article/details/gtltpdzxkx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.bjfxy.top/Article/details/gtmipifqqs.html

[Q13] 忽略重复插入
来源：http://dali.cqqwz.cn/Article/details/gtcxcflmdu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrnapnhs.html

[Q14] 存在则更新（upsert）
来源：http://dali.hongshengwenyu.top/Article/details/gtkhmpwbow.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hysaishi.cn/Article/details/gtgqoklvje.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guannengcc.top/Article/details/gtfckasgoo.html

[Q15] 查询全部
来源：http://dali.nanxuanxn.top/Article/details/gtpzeiwqoz.html


<!-- 参考信息 -->