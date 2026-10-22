代发 wailian999

[M08] 获取系统与运行时信息
来源：http://dali.sufxvd.cn/Article/details/gt2uhcwsqnb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.haohaochexian.top/Article/details/gt2hrcbehbr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.smart0.xyz/Article/details/gt2vbwgihai.html

JS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gt2plwfzava.html

TS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gt2rvporwfy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shzxlz.cn/Article/details/gt2fqjlpmck.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yangfankeji.com/Article/details/gt2zucsfmvq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xinyue.icu/Article/details/gt2sauxagss.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.feifeiyinyue.top/Article/details/gt2rdyorijl.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2edbpjfca.html

N. 数据结构与算法
来源：http://dali.zhixingplan.top/Article/details/gt2bxuxwpcb.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2ewduqguy.html

[N01] 二分查找（有序数组）
来源：http://dali.yueranfly.top/Article/details/gt2ufxtwitz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2fqehnyvy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hfpthk.cn/Article/details/gt2onitwzsz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gt2jbwbbupk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.svipenyu.cn/Article/details/gt2axckzxcd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2bcbaicrf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kimntaqn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sufxvd.cn/Article/details/gt2ovcotpxh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2uzhzcpsz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxinkj.top/Article/details/gt2yttcfksx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sysykeji.top/Article/details/gt2eqvizdsw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhengqikj.top/Article/details/gt2kohgnsbo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gt2yxvojevl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gt2snnbsryk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shzxlz.cn/Article/details/gt2gytpzcpy.html

Go:   slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2hmsbgpeh.html

Ruby: arr.sort
来源：http://dali.guannengcc.top/Article/details/gt2acnjixrw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nwbrower.top/Article/details/gt2zzcspaxk.html

[N03] 快速排序（分治示例）
来源：http://dali.xziqi.cn/Article/details/gt2nibtqvil.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.andypj.xyz/Article/details/gt2emzyqutq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pycfn.com/Article/details/gt2qlwbbtsp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.smart0.xyz/Article/details/gt2krbngweh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jhzdmvfq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhengqikj.top/Article/details/gt2kldilyod.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dashuyun.cn/Article/details/gt2pizoviwf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.quarkkingdee.top/Article/details/gt2ddpomprx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hongshengwenyu.top/Article/details/gt2tyuipxxa.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2hszqhlll.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gt2mktrzdqg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djowfpwm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gt2htykermg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gt2tmiyswho.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yuxming.cn/Article/details/gt2ecqqouvt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.meibo888.top/Article/details/gt2pzlwekue.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nwbrower.top/Article/details/gt2deetcwkz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gt2hjbmrosq.html

[N05] 最大公约数
来源：http://dali.hnqzz.top/Article/details/gt2wieozhda.html

Py:   math.gcd(a, b)
来源：http://dali.cdnleiting.top/Article/details/gt2nwuvwyhr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ehhzyyow.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gt2yumngeku.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2natdxbzu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangshuangyany.cn/Article/details/gt2taxlhmwp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.9152youxi.cn/Article/details/gt2lpolarcd.html

Ruby: a.gcd(b)
来源：http://dali.iojbl.cn/Article/details/gt2nygdnflf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daxiang520.top/Article/details/gt2dnozrwpw.html

[N06] 判断回文字符串
来源：http://dali.yueranfly.top/Article/details/gt2abszkpth.html

Py:   s == s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gt2gimlnvyt.html

PHP:  $s === strrev($s);
来源：http://dali.cucudq.cn/Article/details/gt2oldxpwxq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gt2qnmudrhb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gt2fpeqzgru.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sufxvd.cn/Article/details/gt2dqylmkfn.html

Go:   // 双指针从两端比较
来源：http://dali.daria6918.cn/Article/details/gt2lhdhfwgy.html

Ruby: s == s.reverse
来源：http://dali.yuanzhike.top/Article/details/gt2jrrrwypc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gt2nxbptero.html

[N07] 两数之和（返回下标）
来源：http://dali.kuanghao11.cn/Article/details/gt2qnsdhetz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jqgufenzy.top/Article/details/gt2pbuuscey.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgufenzy.top/Article/details/gt2isborzej.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhixingplan.top/Article/details/gt2ccoruhuu.html

TS:   // 手写 Map<string, number>
来源：http://dali.havefunace.top/Article/details/gt2ihqojetn.html

Java: // 手写 HashMap
来源：http://dali.sufxvd.cn/Article/details/gt2vhzztqpw.html

Go:   // 手写 map[int]int
来源：http://dali.cashguo.top/Article/details/gt2wapszawo.html

Ruby: // 手写 Hash
来源：http://dali.svipenyu.cn/Article/details/gt2iqccifyx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.wangshuangyany.cn/Article/details/gt2gzoijten.html

[N08] 生成全排列
来源：http://dali.tianlin.xyz/Article/details/gt2vyylazul.html

Py:   itertools.permutations(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2dqpcdmff.html

PHP:  // 手写递归交换
来源：http://dali.dashuyun.cn/Article/details/gt2sjhbnsdm.html

JS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gt2ohoafpal.html

TS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2szdwexlc.html

Java: // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gt2micwqsav.html

Go:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gt2ckgurwaz.html

Ruby: arr.permutation.to_a
来源：http://dali.yuanzhike.top/Article/details/gt2kbjltcky.html

C#:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gt2gnomngxi.html

[N09] 栈与队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2zhiunqzd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gaohongyu789.top/Article/details/gt2cuhxipow.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gt2jningnwr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gt2kkzsdngm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.feifeiyinyue.top/Article/details/gt2djsadgsp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tvxczsio.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ehwqpu.com/Article/details/gt2ybjlvfnq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gt2zexezehj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnqzz.top/Article/details/gt2zlnoxbol.html

[N10] 链表节点定义
来源：http://dali.haohaochexian.top/Article/details/gt2yfjoxojg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daxiang520.top/Article/details/gt2sxlzjusb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sufxvd.cn/Article/details/gt2flnidbvh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guannengcc.top/Article/details/gt2qlrsjipn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.meibo888.top/Article/details/gt2urdlxbok.html

Java: class Node { int v; Node next; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lpxlygwi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fzhhl.top/Article/details/gt2dnrjuqya.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hongshengwenyu.top/Article/details/gt2puwrtlgk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jnylkdgc.html

[N11] 二叉树中序遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2sszlqpuy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhongyouzk.top/Article/details/gt2gkjmtkjw.html

PHP:  // 手写递归函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xzsoamfb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gt2wuubhysm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tian-w.cn/Article/details/gt2mamyirfj.html

Java: // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gt2taxuseyp.html

Go:   // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hrcenvir.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258.top/Article/details/gt2pvpxvdin.html

C#:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dxhvgvzl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gotoacloud.top/Article/details/gt2nysnziwx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgufenzy.top/Article/details/gt2nzarobfr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shzxlz.cn/Article/details/gt2msddkmxi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnqzz.top/Article/details/gt2apvxmkgd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gt2xhmihgyc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gt2ghfgjsav.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xuanzx.com/Article/details/gt2nixflqxq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cheryme.top/Article/details/gt2venjsbnd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gt2ttemgryd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2eagxoovz.html

O. 并发与异步
来源：http://dali.aizwys.cn/Article/details/gt2fvxlzhsi.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2vhqenmhn.html

[O01] 启动一个线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gobqjwnz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ffrbrjzk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shzxlz.cn/Article/details/gt2sutiqswm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.c1oappe.top/Article/details/gt2qwtswvgr.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gt2vwtrrqjy.html

Java: new Thread(() -> f()).start()
来源：http://dali.sufxvd.cn/Article/details/gt2pgenzbnq.html

Go:   go f()
来源：http://dali.gotoacloud.top/Article/details/gt2esgubmkw.html

Ruby: Thread.new { f }
来源：http://dali.shuidangran.top/Article/details/gt2ankkdsxf.html

C#:   Task.Run(() => F());
来源：http://dali.zdqjudy.top/Article/details/gt2bkysdvqo.html

[O02] 使用线程池
来源：http://dali.ehwqpu.com/Article/details/gt2iharollw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guowangkeji.top/Article/details/gt2iinmzpbi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cqqwz.cn/Article/details/gt2tdarktau.html

JS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gt2szcwfowo.html

TS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gt2baljuhec.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gaohongyu789.top/Article/details/gt2cbhtddyl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinqigufen.top/Article/details/gt2qldvyyrq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jiagoushi.top/Article/details/gt2ubukgvln.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.bjfxy.top/Article/details/gt2ywyjrrkv.html

[O03] 加锁保护共享数据
来源：http://dali.tanke756.top/Article/details/gt2kqctvtxv.html

Py:   with lock: shared += 1
来源：http://dali.jqgufenzy.top/Article/details/gt2flxuygrr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.dashuyun.cn/Article/details/gt2ahlnazva.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yvedp.cn/Article/details/gt2joknxcxo.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gt2turiaemh.html

Java: synchronized (this) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2spvayjxe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenzaomai.com/Article/details/gt2zjoayqzt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.fengsongda.top/Article/details/gt2flgntmiq.html

C#:   lock (gate) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gt2pwtwnzvm.html

[O04] 定义异步函数并等待
来源：http://dali.chenjidiqi.icu/Article/details/gt2pqleievf.html

Py:   async def f():⏎    await g()
来源：http://dali.zdqjudy.top/Article/details/gt2uldjwlvh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenjidiqi.icu/Article/details/gt2mwyrffjw.html

JS:   async function f() { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gt2jwrbohwk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2ukhkjvmp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hywenlv.cn/Article/details/gt2niifkbef.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenlongwang.top/Article/details/gt2mnoscvid.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenlongwang.top/Article/details/gt2lhlivpcs.html

C#:   async Task F() { await G(); }
来源：http://dali.sufxvd.cn/Article/details/gt2jjneowxl.html

[O05] 并发执行并等待全部完成
来源：http://dali.gaohongyu789.top/Article/details/gt2cfkqakgt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ydzc1.top/Article/details/gt2amzpruti.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhengqikj.top/Article/details/gt2cngjsonf.html

JS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gt2ksrujyjs.html

TS:   await Promise.all(tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lmzsotir.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2meaowrpu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.aizwys.cn/Article/details/gt2ynfdcxsc.html

Ruby: threads.map(&:join)
来源：http://dali.c1oappe.top/Article/details/gt2nrzolahd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cucudq.cn/Article/details/gt2fpetmpxv.html

[O06] 使用进程池
来源：http://dali.aibaodan.cn/Article/details/gt2ikfzdkvz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.iojbl.cn/Article/details/gt2uriowgon.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinqigufen.top/Article/details/gt2vrtckokl.html

JS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gt2gcotmhdw.html

TS:   // child_process / cluster 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2enjnumwq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vvmrxlla.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.aibaodan.cn/Article/details/gt2tccimwfj.html

Ruby: // fork 块
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djajahpf.html

C#:   Parallel.For
来源：http://dali.ybcxt.top/Article/details/gt2qfxuhgun.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2jlvtecwh.html

P. 常用工具函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fxhbohyt.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2luezqtxd.html

[P01] 生成 UUID
来源：http://dali.gogol.net.cn/Article/details/gt2prgivhgi.html

Py:   str(uuid.uuid4())
来源：http://dali.xuanzx.com/Article/details/gt2yedcujja.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yvedp.cn/Article/details/gt2owskmuje.html

JS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gt2xycojqbe.html

TS:   crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gt2bipvsuli.html

Java: UUID.randomUUID().toString()
来源：http://dali.nwbrower.top/Article/details/gt2fixmheae.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yjpcuzbx.html

Ruby: SecureRandom.uuid
来源：http://dali.haohaochexian.top/Article/details/gt2ivutzncr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tian-w.cn/Article/details/gt2pkbqnwum.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dxbrjsef.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2smbyktao.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.guannengcc.top/Article/details/gt2vblvtsdh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.mhx1999.top/Article/details/gt2fmpdwtfd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.havefunace.top/Article/details/gt2gwiquocb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cashguo.top/Article/details/gt2sxeldvru.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fengsongda.top/Article/details/gt2ngmxvqfo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shuidangran.top/Article/details/gt2bobjxlcg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yanxiufei.cn/Article/details/gt2wffzyemy.html

[P03] 生成短随机字符串
来源：http://dali.c1oappe.top/Article/details/gt2cyrdxzje.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.aizwys.cn/Article/details/gt2cyjygvhn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shzxlz.cn/Article/details/gt2uilirvnt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.0kj1m.cn/Article/details/gt2yallrtyt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2fvhhjswe.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ivvv.top/Article/details/gt2miqwxgfo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shuidangran.top/Article/details/gt2weqmfqmf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zmsuyhgq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.dashuyun.cn/Article/details/gt2prvqrqfs.html

[P04] 求长度
来源：http://dali.hnqzz.top/Article/details/gt2zznunhzf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gogol.net.cn/Article/details/gt2kckvqzge.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gt2qqflqvpu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jiagoushi.top/Article/details/gt2iswovrja.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shuidangran.top/Article/details/gt2jafwpvcf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj202588.top/Article/details/gt2tmaquxqi.html

Go:   len(arr);  len(m)
来源：http://dali.0kj1m.cn/Article/details/gt2ghfgdkyf.html

Ruby: x.length;  x.size
来源：http://dali.hnxiangtu.top/Article/details/gt2jfvsmwan.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.9152youxi.cn/Article/details/gt2hxmnkoey.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yonumen.top/Article/details/gt2vhfyhgxc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.bjfxy.top/Article/details/gt2owkrtehp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jezsooab.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenzaomai.com/Article/details/gt2qlmlkszq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigfzy.top/Article/details/gt2fpmobowa.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhoulong.xyz/Article/details/gt2ncnrdevq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tianlin.xyz/Article/details/gt2frppvgzf.html

Ruby: a == b
来源：http://dali.yvedp.cn/Article/details/gt2fnjyndij.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxinkj.top/Article/details/gt2txsvwwfo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.daria6918.cn/Article/details/gt2jiqjqupa.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fzhhl.top/Article/details/gt2bloggfim.html

PHP:  if (empty($x)) {}
来源：http://dali.shzxlz.cn/Article/details/gt2pochvvuf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tian-w.cn/Article/details/gt2asdkdeaz.html

TS:   if (x == null) {}
来源：http://dali.ydzc1.top/Article/details/gt2mstmxxmn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ydzc1.top/Article/details/gt2ieajawen.html

Go:   if x == nil {}
来源：http://dali.pycfn.com/Article/details/gt2efknwokp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wrqyfynl.html

C#:   if (x is null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hyqaqxsr.html

[P07] 防抖与节流
来源：http://dali.cheryme.top/Article/details/gt2rcoonltb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yueranfly.top/Article/details/gt2dmhrivwi.html

PHP:  // 手写时间戳比较
来源：http://dali.hywenlv.cn/Article/details/gt2tkhvaiyl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pyopnfpa.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gt2bfcotaei.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fzhhl.top/Article/details/gt2apvxxwaq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jyoumei.cn/Article/details/gt2gjuyxtii.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hfpthk.cn/Article/details/gt2vlcceqsk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.pengpengdd.cyou/Article/details/gt2bpmkelkv.html

[P08] 处理浮点精度问题
来源：http://dali.chenjidiqi.icu/Article/details/gt2wtvtlesq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.andypj.xyz/Article/details/gt2plgjlnsm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.316326.xyz/Article/details/gt2jyuqbuzn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cgfcpfrx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gt2fiadzqse.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yvedp.cn/Article/details/gt2akmjbfxs.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj20258.top/Article/details/gt2xrwgpzvz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cucudq.cn/Article/details/gt2sjxqvthi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nwbrower.top/Article/details/gt2rndwiomt.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2lieirdmb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jyoumei.cn/Article/details/gt2evypsnfp.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2hmlsxqth.html

[Q01] 创建表
来源：http://dali.jqgfzy.top/Article/details/gt2oaxqkzyi.html

CREATE TABLE users (
来源：http://dali.jyoumei.cn/Article/details/gt2eowyoqbj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gt2axqwuvit.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gt2tinquvej.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jlsjyb.cn/Article/details/gt2kvyhxzdv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jyoumei.cn/Article/details/gt2rhrtdjwq.html

);
来源：http://dali.feifeiyinyue.top/Article/details/gt2aslupgrc.html

[Q02] 创建带外键的表
来源：http://dali.tian-w.cn/Article/details/gt2pkreijkd.html

CREATE TABLE orders (
来源：http://dali.zhixingplan.top/Article/details/gt2jokkiwna.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.meibo888.top/Article/details/gt2wqnbluju.html

user_id INT NOT NULL,
来源：http://dali.haohaochexian.top/Article/details/gt2dqajmcqq.html

amount DECIMAL(10, 2),
来源：http://dali.yangfankeji.com/Article/details/gt2ulspacci.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tianlin.xyz/Article/details/gt2lvjcrscg.html

);
来源：http://dali.c1oappe.top/Article/details/gt2blaemyre.html

[Q03] 增加列
来源：http://dali.sweek.top/Article/details/gt2mvekeknl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.0kj1m.cn/Article/details/gt2dforjnka.html

[Q04] 修改列类型
来源：http://dali.yonumen.top/Article/details/gt2wcffyemr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.bjfxy.top/Article/details/gt2bfvvhxll.html

[Q05] 重命名列
来源：http://dali.wangdashe.top/Article/details/gt2dfgmxklk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gotoacloud.top/Article/details/gt2kayqgohh.html

[Q06] 删除列
来源：http://dali.birdmap.top/Article/details/gt2zszklwrg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tian-w.cn/Article/details/gt2flqanvps.html

[Q07] 删除表
来源：http://dali.wangshuangyany.cn/Article/details/gt2tymrvbtt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hammf.cn/Article/details/gt2jvyxoxhr.html

[Q08] 创建普通索引
来源：http://dali.yvedp.cn/Article/details/gt2uethaehj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uywxgkkg.html

[Q09] 创建唯一索引
来源：http://dali.hfpthk.cn/Article/details/gt2xvucbztp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gt2nvsbaies.html

[Q10] 插入单行
来源：http://dali.andypj.xyz/Article/details/gt2uuzbqidn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ybcxt.top/Article/details/gt2ngxwpahi.html

[Q11] 一次插入多行
来源：http://dali.0kj1m.cn/Article/details/gt2jufreody.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gt2ozfdgnsx.html

[Q12] 插入后取自增 ID
来源：http://dali.mhx1999.top/Article/details/gt2qxyjwrfy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cucudq.cn/Article/details/gt2grmkefzk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.pycfn.com/Article/details/gt2lyaqjvcj.html

[Q13] 忽略重复插入
来源：http://dali.gotoacloud.top/Article/details/gt2ogobiczq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cashguo.top/Article/details/gt2ruesmoym.html

[Q14] 存在则更新（upsert）
来源：http://dali.vqdsnc.cn/Article/details/gt2gtgwzxng.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fzhhl.top/Article/details/gt2sggmdxbl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tanke756.top/Article/details/gt2ahnbqdqw.html

[Q15] 查询全部
来源：http://dali.gogol.net.cn/Article/details/gt2camncxty.html

SELECT * FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2iwesawdl.html

[Q16] 查询指定列
来源：http://dali.jlsjyb.cn/Article/details/gt2fcrcemgk.html

SELECT id, name FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2nbgilrju.html

[Q17] 条件查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2qazvzicp.html


<!-- 参考信息 -->