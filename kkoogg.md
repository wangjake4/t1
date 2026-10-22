代发 wailian999

[M08] 获取系统与运行时信息
来源：http://dali.xylfe.cn/Article/details/gtekvcwitn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ybcxt.top/Article/details/gtrwbrkxqk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cashguo.top/Article/details/gtgmbjcfcs.html

JS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gtunrahgwj.html

TS:   process.platform;  process.version
来源：http://dali.cashguo.top/Article/details/gttkvnkmgx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjinqkiqt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.0kj1m.cn/Article/details/gtitmorrlb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gtklsfmprt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuetiantiany.cn/Article/details/gthisnoftg.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtnexmuhxm.html

N. 数据结构与算法
来源：http://dali.sysykeji.top/Article/details/gtcqmcptfb.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtuhuaggpw.html

[N01] 二分查找（有序数组）
来源：http://dali.svipenyu.cn/Article/details/gthwmnyzjk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtrmnybyih.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtrbbxdghs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gtzmxdmowq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gtknfhyomf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtbjljnmcl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtzolnyujb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ivvv.top/Article/details/gtgxkwkljw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtkbicwtlj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgfzy.top/Article/details/gtlcheawje.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gtlxpdjjjx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtljnwhqbf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gtodqzbzmd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gthckfywtj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.andypj.xyz/Article/details/gtziqkhejz.html

Go:   slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gtmsdlztga.html

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gtynukefte.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jiagoushi.top/Article/details/gtemowyvzs.html

[N03] 快速排序（分治示例）
来源：http://dali.cucudq.cn/Article/details/gtbgnbfbuj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hywenlv.cn/Article/details/gtjddwrwuu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gzhubu.top/Article/details/gtsvefchrd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gtoqswpndk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gtfzwncooh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigufen.top/Article/details/gtbzomxpow.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daxiang520.top/Article/details/gteduwezpj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkaitklx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yonumen.top/Article/details/gtigtgsrwy.html

[N04] 斐波那契数列
来源：http://dali.ybcxt.top/Article/details/gtvueryhhn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gtxywtpwna.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.c1oappe.top/Article/details/gtiinzzwwl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtergvmezs.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtcvhkphun.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.fengsongda.top/Article/details/gtaftkbmbk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.smart0.xyz/Article/details/gthubglyop.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gtqxzbxvdv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtzhhigaot.html

[N05] 最大公约数
来源：http://dali.yj202588.top/Article/details/gtshnwdggr.html

Py:   math.gcd(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtqeiagvvh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shuidangran.top/Article/details/gtnwbiqnxb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtomiwesto.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gttsvkgahl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangshuangyany.cn/Article/details/gtunvazlnf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gotoacloud.top/Article/details/gtfqtgceul.html

Ruby: a.gcd(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtsjsnlecp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jianghu66.top/Article/details/gtjeigqhnh.html

[N06] 判断回文字符串
来源：http://dali.dianchejie.cn/Article/details/gtlkyvncxi.html

Py:   s == s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gtwtydanwd.html

PHP:  $s === strrev($s);
来源：http://dali.aibaodan.cn/Article/details/gtlikmbbgn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtjjuoytha.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtiuuipucp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hfpthk.cn/Article/details/gtywrfuayw.html

Go:   // 双指针从两端比较
来源：http://dali.yangfankeji.com/Article/details/gtapcppaej.html

Ruby: s == s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtwyfdirrr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gthscyrwyg.html

[N07] 两数之和（返回下标）
来源：http://dali.0kj1m.cn/Article/details/gtmdcvkffn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ivvv.top/Article/details/gtmmkflseh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hfpthk.cn/Article/details/gttgwtwpoh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cdnleiting.top/Article/details/gtsqhpmplp.html

TS:   // 手写 Map<string, number>
来源：http://dali.vqdsnc.cn/Article/details/gtsfwyjqqo.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdwlhsxt.html

Go:   // 手写 map[int]int
来源：http://dali.jyoumei.cn/Article/details/gttbmftdzo.html

Ruby: // 手写 Hash
来源：http://dali.xylfe.cn/Article/details/gtxinkjjzs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.kuanghao11.cn/Article/details/gturkzdpsv.html

[N08] 生成全排列
来源：http://dali.shuidangran.top/Article/details/gthxbgdhpj.html

Py:   itertools.permutations(arr)
来源：http://dali.svipenyu.cn/Article/details/gtmaoenymu.html

PHP:  // 手写递归交换
来源：http://dali.fengsongda.top/Article/details/gtxsrjwqak.html

JS:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtbqhpjdkb.html

TS:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtkhhjtwhp.html

Java: // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtcnjmojhu.html

Go:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtowhmpdtq.html

Ruby: arr.permutation.to_a
来源：http://dali.haohaochexian.top/Article/details/gtgucixqsz.html

C#:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtenyilzej.html

[N09] 栈与队列
来源：http://dali.yonumen.top/Article/details/gtmqpwhnbq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yuanzhike.top/Article/details/gtdqfpfykb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtlizptngz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gthjalxfxu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstloyxvg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zycfv.cn/Article/details/gtjqaqzjlp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yueranfly.top/Article/details/gtkiljbyzt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gtgepsxshr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.havefunace.top/Article/details/gtqzxblznt.html

[N10] 链表节点定义
来源：http://dali.ivvv.top/Article/details/gtmhwcniam.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cheryme.top/Article/details/gtqwoicmgj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cdnleiting.top/Article/details/gtybtzquji.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yueranfly.top/Article/details/gttqjhobgq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yanxiufei.cn/Article/details/gtliyyhadh.html

Java: class Node { int v; Node next; }
来源：http://dali.hammf.cn/Article/details/gtqogqmmjk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jiagoushi.top/Article/details/gtfhpjpbnf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gogol.net.cn/Article/details/gtpyzmogqx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yanxiufei.cn/Article/details/gtwesbitcb.html

[N11] 二叉树中序遍历
来源：http://dali.xinyue.icu/Article/details/gthxowfzuu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.smart0.xyz/Article/details/gttiwekpry.html

PHP:  // 手写递归函数
来源：http://dali.guannengcc.top/Article/details/gtyngsanrk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gtsdwoklnn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shuidangran.top/Article/details/gtyzjwvfjm.html

Java: // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gtjigauqtl.html

Go:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtbdevaklq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.dianchejie.cn/Article/details/gtpjybbkxa.html

C#:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gtqhonctcm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gzhubu.top/Article/details/gtodtzqmcx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nanxuanxn.top/Article/details/gttdqrjmoh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.kuanghao11.cn/Article/details/gtqpnjnzjn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sufxvd.cn/Article/details/gtflvjhsmk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrfkzqus.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgufenzy.top/Article/details/gtyowyyqbf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sxryk.cn/Article/details/gtkrzffzhs.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.9152youxi.cn/Article/details/gtbkivlgzw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gtkguhpebh.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtcgacfcbg.html

O. 并发与异步
来源：http://dali.chenzaomai.com/Article/details/gtadhzqmks.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtzccqltvr.html

[O01] 启动一个线程
来源：http://dali.hammf.cn/Article/details/gtxpycezoh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cdnleiting.top/Article/details/gtnubedepw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nanxuanxn.top/Article/details/gttisltkzb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhengqikj.top/Article/details/gtixkhfkgk.html

TS:   // 同 JS
来源：http://dali.yonumen.top/Article/details/gtibxcetqg.html

Java: new Thread(() -> f()).start()
来源：http://dali.xylfe.cn/Article/details/gtozetflae.html

Go:   go f()
来源：http://dali.havefunace.top/Article/details/gtbvkdmcdc.html

Ruby: Thread.new { f }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuadtyqkr.html

C#:   Task.Run(() => F());
来源：http://dali.cqqwz.cn/Article/details/gttwspojjr.html

[O02] 使用线程池
来源：http://dali.aizwys.cn/Article/details/gtjoxhgyhn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yuanzhike.top/Article/details/gtqquhogie.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwygrqajl.html

JS:   // worker_threads 线程池
来源：http://dali.fzhhl.top/Article/details/gtlcfktesu.html

TS:   // worker_threads 线程池
来源：http://dali.vqdsnc.cn/Article/details/gtxcwbcnfc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.pengpengdd.cyou/Article/details/gtyjmhmxtx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.0kj1m.cn/Article/details/gtowkgwmql.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ppjwa.cn/Article/details/gtdhiscvbc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shuidangran.top/Article/details/gtfhvofkma.html

[O03] 加锁保护共享数据
来源：http://dali.aibaodan.cn/Article/details/gtbxenqopi.html

Py:   with lock: shared += 1
来源：http://dali.cqqwz.cn/Article/details/gtczibkmtn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shzxlz.cn/Article/details/gtruwktlbd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sufxvd.cn/Article/details/gtmxvgwktm.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtaytmtrqq.html

Java: synchronized (this) { shared++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtesyhtyra.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.aizwys.cn/Article/details/gtbargzqdj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zdqjudy.top/Article/details/gtyirkclqt.html

C#:   lock (gate) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gtvjynjtfc.html

[O04] 定义异步函数并等待
来源：http://dali.meibo888.top/Article/details/gtaeocrjsg.html

Py:   async def f():⏎    await g()
来源：http://dali.ydzc1.top/Article/details/gtlcidjwsc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.birdmap.top/Article/details/gtafiaifnz.html

JS:   async function f() { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gtcnxcbdrv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.andypj.xyz/Article/details/gtklptmvcw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cashguo.top/Article/details/gtmrohipza.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhongyouzk.top/Article/details/gtdngmuwvb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.meibo888.top/Article/details/gtzewzdrkd.html

C#:   async Task F() { await G(); }
来源：http://dali.sufxvd.cn/Article/details/gtsrdohocl.html

[O05] 并发执行并等待全部完成
来源：http://dali.birdmap.top/Article/details/gtzprxmaap.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnxiangtu.top/Article/details/gthggsnfzk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.wangshuangyany.cn/Article/details/gtzygloctm.html

JS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gtbnxltwia.html

TS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gtmeqnsdsg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj202588.top/Article/details/gtuxhoabbf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangshuangyany.cn/Article/details/gtwjxixkmg.html

Ruby: threads.map(&:join)
来源：http://dali.zdqjudy.top/Article/details/gtrsbrufjg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sufxvd.cn/Article/details/gtreryrwfa.html

[O06] 使用进程池
来源：http://dali.kuanghao11.cn/Article/details/gtowdgtdyr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.vqdsnc.cn/Article/details/gtdjpjdvfv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jqgufenzy.top/Article/details/gtxbwhuyee.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gtdwliefxa.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gtmdsztydp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hnqzz.top/Article/details/gtdsutvpqs.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hongshengwenyu.top/Article/details/gtgbpunndt.html

Ruby: // fork 块
来源：http://dali.yj20258888.top/Article/details/gtbbpxhmta.html

C#:   Parallel.For
来源：http://dali.yj20258.top/Article/details/gtubxtssiw.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtjescbcey.html

P. 常用工具函数
来源：http://dali.xuanzx.com/Article/details/gtolhebrgn.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtjasliuki.html

[P01] 生成 UUID
来源：http://dali.sxryk.cn/Article/details/gtijsfnfle.html

Py:   str(uuid.uuid4())
来源：http://dali.0kj1m.cn/Article/details/gtimkcxurp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigufen.top/Article/details/gtiguxietk.html

JS:   crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gtladoyvlv.html

TS:   crypto.randomUUID()
来源：http://dali.tianlin.xyz/Article/details/gtunfcrpvo.html

Java: UUID.randomUUID().toString()
来源：http://dali.fzhhl.top/Article/details/gtytspfhwc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sysykeji.top/Article/details/gtimndvacq.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgfzy.top/Article/details/gtxjlbpbqm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gtmzupqrxb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnxiangtu.top/Article/details/gtzqduovta.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnubyuctc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.meibo888.top/Article/details/gtdclfrvzm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinqigufen.top/Article/details/gtmzerhinw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gaohongyu789.top/Article/details/gtgcbrgfkx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtrnpswptz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuanzhike.top/Article/details/gtjzxlcrlq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tian-w.cn/Article/details/gtbruxwbbc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dianchejie.cn/Article/details/gtgkwiftwg.html

[P03] 生成短随机字符串
来源：http://dali.guowangkeji.top/Article/details/gtuukwshak.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yanxiufei.cn/Article/details/gttabvzmeh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ybcxt.top/Article/details/gtpfnozvxp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuanzhike.top/Article/details/gtbemsfqzo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj202588.top/Article/details/gtkyjekgkz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtljmsqioj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guowangkeji.top/Article/details/gtdhkqwbcw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hongshengwenyu.top/Article/details/gtbbdyrwqw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.svipenyu.cn/Article/details/gtvuiesmwx.html

[P04] 求长度
来源：http://dali.hongshengwenyu.top/Article/details/gtbtxuoqbi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cheryme.top/Article/details/gtdnmvctew.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtayhorqno.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqyjjdgd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gtmfuucivc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuanzx.com/Article/details/gtfengmwki.html

Go:   len(arr);  len(m)
来源：http://dali.yonumen.top/Article/details/gtplqfliyd.html

Ruby: x.length;  x.size
来源：http://dali.yuxming.cn/Article/details/gtgydmmcpd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ybcxt.top/Article/details/gtpxxgveyn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gtxxkaktcr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yanxiufei.cn/Article/details/gtufptfleh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jlsjyb.cn/Article/details/gtnpssgfcw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hfpthk.cn/Article/details/gtiyfeurtf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgfzy.top/Article/details/gtfxztqrsw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pycfn.com/Article/details/gtalvdwjny.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtigprsbwu.html

Ruby: a == b
来源：http://dali.hongshengwenyu.top/Article/details/gthcfupjxu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenjidiqi.icu/Article/details/gtujijdyah.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgufenzy.top/Article/details/gtogdjjyap.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pengpengdd.cyou/Article/details/gthhaugbfj.html

PHP:  if (empty($x)) {}
来源：http://dali.pycfn.com/Article/details/gtnrfjidah.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuanzx.com/Article/details/gtcxlmcyfu.html

TS:   if (x == null) {}
来源：http://dali.wangdashe.top/Article/details/gthwidmkpa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gtfscursdi.html

Go:   if x == nil {}
来源：http://dali.shangyingyoupin.top/Article/details/gtchhjfaez.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.kuanghao11.cn/Article/details/gtakkhluxm.html

C#:   if (x is null) {}
来源：http://dali.gaohongyu789.top/Article/details/gtwpnoypgi.html

[P07] 防抖与节流
来源：http://dali.aibaodan.cn/Article/details/gtfqhitwiq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.iojbl.cn/Article/details/gtfnvowxpw.html

PHP:  // 手写时间戳比较
来源：http://dali.shuidangran.top/Article/details/gtudbbydky.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gtzymapahj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gthhfxriwo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jlsjyb.cn/Article/details/gtwcjpvewn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daria6918.cn/Article/details/gtwjhhafwo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jyoumei.cn/Article/details/gtsqeqqiji.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.mhx1999.top/Article/details/gtbjnfjaef.html

[P08] 处理浮点精度问题
来源：http://dali.iojbl.cn/Article/details/gtgspybbhm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xziqi.cn/Article/details/gtejmnsjbk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cashguo.top/Article/details/gttekjewem.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.iojbl.cn/Article/details/gtcxnwtxuu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sweek.top/Article/details/gtzmisfisp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.iojbl.cn/Article/details/gtniiirzwn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yanxiufei.cn/Article/details/gtkjsjdzdt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.aizwys.cn/Article/details/gtetjpejxf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.vqdsnc.cn/Article/details/gtuasglmjx.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtbzyxaqpn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.aizwys.cn/Article/details/gthenrolcj.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtdqqgbpem.html

[Q01] 创建表
来源：http://dali.sxryk.cn/Article/details/gttdpcwprv.html

CREATE TABLE users (
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsoxflszh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gtocclhryz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hywenlv.cn/Article/details/gtnfsdokfe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sweek.top/Article/details/gtpaykpnpm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xinyue.icu/Article/details/gtfjnyzjbx.html

);
来源：http://dali.shzxlz.cn/Article/details/gtkswcrrqr.html

[Q02] 创建带外键的表
来源：http://dali.jinqigfzy.top/Article/details/gtxvlkqxeu.html

CREATE TABLE orders (
来源：http://dali.xuanzx.com/Article/details/gteruxffem.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gtbrxbfyqx.html

user_id INT NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gtzvizbyvj.html

amount DECIMAL(10, 2),
来源：http://dali.cqqwz.cn/Article/details/gteyfzyoep.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.kuanghao11.cn/Article/details/gtdseqgxfk.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifcnkdpa.html

[Q03] 增加列
来源：http://dali.yj202588.top/Article/details/gtdmnklysu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cdnleiting.top/Article/details/gtudvpvaoa.html

[Q04] 修改列类型
来源：http://dali.havefunace.top/Article/details/gtarzswdgl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.aizwys.cn/Article/details/gtmvtxeyjc.html

[Q05] 重命名列
来源：http://dali.xinyue.icu/Article/details/gthvejxbsg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenzaomai.com/Article/details/gtnbgsqqze.html

[Q06] 删除列
来源：http://dali.yanxiufei.cn/Article/details/gtxhckossx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shangyingyoupin.top/Article/details/gtgifmxkuz.html

[Q07] 删除表
来源：http://dali.nanxuanxn.top/Article/details/gtwdfankvb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.bjfxy.top/Article/details/gtocabgcij.html

[Q08] 创建普通索引
来源：http://dali.meibo888.top/Article/details/gtaichzhqf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinghuilouyu.cn/Article/details/gttuhsiaej.html

[Q09] 创建唯一索引
来源：http://dali.cucudq.cn/Article/details/gtstbxdkxt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gtrmsfhpqw.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gtccwxcnoe.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtpnwqxscq.html

[Q11] 一次插入多行
来源：http://dali.guannengcc.top/Article/details/gtkqtavsaf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fzhhl.top/Article/details/gtbdndbjpg.html

[Q12] 插入后取自增 ID
来源：http://dali.daxiang520.top/Article/details/gtzdjtdcqm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.0kj1m.cn/Article/details/gtqfngcadr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigufen.top/Article/details/gtbiwawiqf.html

[Q13] 忽略重复插入
来源：http://dali.meibo888.top/Article/details/gtkkrgxhju.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtzpbispku.html

[Q14] 存在则更新（upsert）
来源：http://dali.cdnleiting.top/Article/details/gtncfjbryg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tanke756.top/Article/details/gtwmidkwnf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinghuilouyu.cn/Article/details/gtyseybgxa.html

[Q15] 查询全部
来源：http://dali.sxryk.cn/Article/details/gttyrpcpgs.html

SELECT * FROM users;
来源：http://dali.xziqi.cn/Article/details/gtgwawhztc.html

[Q16] 查询指定列
来源：http://dali.dianchejie.cn/Article/details/gtwdpuylfx.html

SELECT id, name FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtlvosucza.html

[Q17] 条件查询
来源：http://dali.sysykeji.top/Article/details/gtkxtcxjeg.html


<!-- 参考信息 -->