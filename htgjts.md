代发 wailian999

[M08] 获取系统与运行时信息
来源：http://dali.aibaodan.cn/Article/details/gt2itabkirp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guowangkeji.top/Article/details/gt2ezfgnvns.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hywenlv.cn/Article/details/gt2yaqhszsl.html

JS:   process.platform;  process.version
来源：http://dali.hongshengwenyu.top/Article/details/gt2xhcqbqao.html

TS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gt2xbtnbqpd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnqzz.top/Article/details/gt2hodbygga.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yongpay.top/Article/details/gt2tyhtcnwi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.aizwys.cn/Article/details/gt2nrpmlvxk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daria6918.cn/Article/details/gt2jaggiqzs.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2yinonefw.html

N. 数据结构与算法
来源：http://dali.wangshuangyany.cn/Article/details/gt2bizgwchn.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2qpnpqdjl.html

[N01] 二分查找（有序数组）
来源：http://dali.hammf.cn/Article/details/gt2thyqkrmr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jianghu66.top/Article/details/gt2jzgexvem.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xziqi.cn/Article/details/gt2wkjfehnv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gt2imdsrfyv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gt2uolstgpe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gt2yrtbrdsk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2asgqellj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yueranfly.top/Article/details/gt2ruofvjpo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2fcobzikv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuxming.cn/Article/details/gt2gnnjaawx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gt2yaaggokh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.quarkkingdee.top/Article/details/gt2ztwnloww.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gt2wyxicrdx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gt2iwtizdcp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhixingplan.top/Article/details/gt2zbgqgsha.html

Go:   slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gt2ppmlirin.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gt2qlbyrvak.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.0kj1m.cn/Article/details/gt2wgipltid.html

[N03] 快速排序（分治示例）
来源：http://dali.fengsongda.top/Article/details/gt2ljcxcutd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cqqwz.cn/Article/details/gt2xvxzqivu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.quarkkingdee.top/Article/details/gt2xkrvrvrj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gt2bmnesyrc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2twgztwhx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.quarkkingdee.top/Article/details/gt2xfeybtsk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zycfv.cn/Article/details/gt2cnlwidel.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wmukjzab.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hnxiangtu.top/Article/details/gt2qvikwkst.html

[N04] 斐波那契数列
来源：http://dali.shangyingyoupin.top/Article/details/gt2zzquimes.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gt2bthogyoa.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuxming.cn/Article/details/gt2mcwxuczj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gt2cdekhiyq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2gzktllsq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gt2boucovsz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jiagoushi.top/Article/details/gt2uxqcirpf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gt2mdoirbhk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gt2tgbqtiay.html

[N05] 最大公约数
来源：http://dali.ybcxt.top/Article/details/gt2mruljbta.html

Py:   math.gcd(a, b)
来源：http://dali.sysykeji.top/Article/details/gt2cocbzwwb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xylfe.cn/Article/details/gt2foqzfotn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gt2bfmxrzyq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gt2zavvtihr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenjidiqi.icu/Article/details/gt2lqgndvbg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xylfe.cn/Article/details/gt2snnzrfwf.html

Ruby: a.gcd(b)
来源：http://dali.nanxinkj.top/Article/details/gt2golpimha.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenzaomai.com/Article/details/gt2aomyyhij.html

[N06] 判断回文字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2hewkjkzv.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjopppz.html

PHP:  $s === strrev($s);
来源：http://dali.jianghu66.top/Article/details/gt2qkvokiff.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gt2sxrszqfh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gt2tkgdfrke.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cqqwz.cn/Article/details/gt2cqconkrc.html

Go:   // 双指针从两端比较
来源：http://dali.svipenyu.cn/Article/details/gt2dikldrse.html

Ruby: s == s.reverse
来源：http://dali.xylfe.cn/Article/details/gt2viqtoltn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gt2ipmfsdga.html

[N07] 两数之和（返回下标）
来源：http://dali.c1oappe.top/Article/details/gt2ugwfovwr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.iojbl.cn/Article/details/gt2bzclsytm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.quarkkingdee.top/Article/details/gt2rviridrq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhoulong.xyz/Article/details/gt2vjqrscvs.html

TS:   // 手写 Map<string, number>
来源：http://dali.tianlin.xyz/Article/details/gt2aramaewx.html

Java: // 手写 HashMap
来源：http://dali.pengpengdd.cyou/Article/details/gt2hktsfyec.html

Go:   // 手写 map[int]int
来源：http://dali.jlsjyb.cn/Article/details/gt2sjclrdnj.html

Ruby: // 手写 Hash
来源：http://dali.xuetiantiany.cn/Article/details/gt2kkttglgy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guowangkeji.top/Article/details/gt2eoclksxv.html

[N08] 生成全排列
来源：http://dali.redwolf501.top/Article/details/gt2rkrdbqzb.html

Py:   itertools.permutations(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2tvmhmeak.html

PHP:  // 手写递归交换
来源：http://dali.gotoacloud.top/Article/details/gt2suebebmu.html

JS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gt2mruegwlk.html

TS:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gt2yfutpgzu.html

Java: // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gt2izvljszo.html

Go:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gt2fotjrsvb.html

Ruby: arr.permutation.to_a
来源：http://dali.hywenlv.cn/Article/details/gt2mftqmqtt.html

C#:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2wmibjjmv.html

[N09] 栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gt2wnzcmdgo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ivvv.top/Article/details/gt2onilezdz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mmyftjcv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gt2izdfxrri.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xylfe.cn/Article/details/gt2otjdamck.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj202588.top/Article/details/gt2ydyofhid.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.feifeiyinyue.top/Article/details/gt2tituqkzl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gt2nhunhkwg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ibyuzzfk.html

[N10] 链表节点定义
来源：http://dali.zhengqikj.top/Article/details/gt2iynoztuj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tian-w.cn/Article/details/gt2iqlajxgb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jlsjyb.cn/Article/details/gt2jlzqbwxh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cqqwz.cn/Article/details/gt2crkzpxcl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sufxvd.cn/Article/details/gt2jdnqtluc.html

Java: class Node { int v; Node next; }
来源：http://dali.iojbl.cn/Article/details/gt2cslrvtzj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jianghu66.top/Article/details/gt2sgsejlet.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hysaishi.cn/Article/details/gt2qcyxeywo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cucudq.cn/Article/details/gt2bztoantv.html

[N11] 二叉树中序遍历
来源：http://dali.zycfv.cn/Article/details/gt2psuikvor.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnxiangtu.top/Article/details/gt2rklsbzeb.html

PHP:  // 手写递归函数
来源：http://dali.nanxuanxn.top/Article/details/gt2lpjrzspn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dashuyun.cn/Article/details/gt2lkdmdzdh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gt2ycofgehl.html

Java: // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gt2miywyurg.html

Go:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gt2snxphkte.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.feifeiyinyue.top/Article/details/gt2rhczqpkz.html

C#:   // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2qqhpovjh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jlsjyb.cn/Article/details/gt2sxywsgqu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.snrcjt.cn/Article/details/gt2xxynfryq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigfzy.top/Article/details/gt2ieztnzhg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gt2qaukvsrn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gt2rmypcvkx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gt2qonghmcr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.wangdashe.top/Article/details/gt2tewmlagp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhixingplan.top/Article/details/gt2gbnkbiwy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gt2fywcwsjq.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2ltlxpmgu.html

O. 并发与异步
来源：http://dali.yanxiufei.cn/Article/details/gt2hyihumjn.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2kgcakuvz.html

[O01] 启动一个线程
来源：http://dali.xinyue.icu/Article/details/gt2yejiaolp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.havefunace.top/Article/details/gt2pswiykhe.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.haohaochexian.top/Article/details/gt2xxhscbzy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhongyouzk.top/Article/details/gt2opnbgjeo.html

TS:   // 同 JS
来源：http://dali.jlsjyb.cn/Article/details/gt2iancdpxr.html

Java: new Thread(() -> f()).start()
来源：http://dali.ehwqpu.com/Article/details/gt2vanogywj.html

Go:   go f()
来源：http://dali.ehwqpu.com/Article/details/gt2fuljfghj.html

Ruby: Thread.new { f }
来源：http://dali.gogol.net.cn/Article/details/gt2dlhckmby.html

C#:   Task.Run(() => F());
来源：http://dali.jqgfzy.top/Article/details/gt2vycvytjf.html

[O02] 使用线程池
来源：http://dali.yj202588.top/Article/details/gt2tjglninw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yuxming.cn/Article/details/gt2lnohutvw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hysaishi.cn/Article/details/gt2frjifmpd.html

JS:   // worker_threads 线程池
来源：http://dali.zhixingplan.top/Article/details/gt2rnvmdete.html

TS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gt2iyyyqxpg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxinkj.top/Article/details/gt2athabzdi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jlsjyb.cn/Article/details/gt2suejnqzs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xziqi.cn/Article/details/gt2oapzwhxd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258.top/Article/details/gt2vwopaczn.html

[O03] 加锁保护共享数据
来源：http://dali.tanke756.top/Article/details/gt2qtupcvrp.html

Py:   with lock: shared += 1
来源：http://dali.sweek.top/Article/details/gt2ychdrbjp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xaltpwqo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.bjfxy.top/Article/details/gt2avacxwrp.html

TS:   // 同 JS
来源：http://dali.daria6918.cn/Article/details/gt2jyybhaoq.html

Java: synchronized (this) { shared++; }
来源：http://dali.dianchejie.cn/Article/details/gt2jxglfoyu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.haohaochexian.top/Article/details/gt2fjxajtoc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenlongwang.top/Article/details/gt2rzyvxzjh.html

C#:   lock (gate) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gt2akrxhqpm.html

[O04] 定义异步函数并等待
来源：http://dali.zhiwuduotai.top/Article/details/gt2upseyzqk.html

Py:   async def f():⏎    await g()
来源：http://dali.daxiang520.top/Article/details/gt2yvinxocn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zycfv.cn/Article/details/gt2ctvpavia.html

JS:   async function f() { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gt2oljupygb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gt2yqkqyvqd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ehwqpu.com/Article/details/gt2hbzvnhqx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.smart0.xyz/Article/details/gt2afcytssb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guowangkeji.top/Article/details/gt2bsuwzblv.html

C#:   async Task F() { await G(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2amexhkke.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhixingplan.top/Article/details/gt2hqaiisip.html

Py:   asyncio.gather(*tasks)
来源：http://dali.guannengcc.top/Article/details/gt2azuakkbc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhoulong.xyz/Article/details/gt2ropdsecv.html

JS:   await Promise.all(tasks)
来源：http://dali.sxryk.cn/Article/details/gt2iruomtmh.html

TS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gt2lznyayqq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jiagoushi.top/Article/details/gt2xodorskv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yvedp.cn/Article/details/gt2nrctmtbi.html

Ruby: threads.map(&:join)
来源：http://dali.havefunace.top/Article/details/gt2cdnnfvlv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hywenlv.cn/Article/details/gt2ktualgaz.html

[O06] 使用进程池
来源：http://dali.jianghu66.top/Article/details/gt2sqfdovqi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xziqi.cn/Article/details/gt2zwqdtqpb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.316326.xyz/Article/details/gt2waypzzgp.html

JS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gt2faoesujg.html

TS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gt2gplrdtat.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fzhhl.top/Article/details/gt2boczzsnn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sysykeji.top/Article/details/gt2onyxnijt.html

Ruby: // fork 块
来源：http://dali.svipenyu.cn/Article/details/gt2bpczbjbo.html

C#:   Parallel.For
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gjqdrkpw.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2mbrvmynl.html

P. 常用工具函数
来源：http://dali.hywenlv.cn/Article/details/gt2heeqvmlx.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2vxiqawdj.html

[P01] 生成 UUID
来源：http://dali.xuanzx.com/Article/details/gt2isvipubz.html

Py:   str(uuid.uuid4())
来源：http://dali.hywenlv.cn/Article/details/gt2sbfqsakp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigufen.top/Article/details/gt2mcciaasi.html

JS:   crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gt2ykdhhmje.html

TS:   crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gt2dulwykuq.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhixingplan.top/Article/details/gt2xbknahkn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinqigufen.top/Article/details/gt2hbcfervg.html

Ruby: SecureRandom.uuid
来源：http://dali.zhengqikj.top/Article/details/gt2yntmpeut.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.9152youxi.cn/Article/details/gt2ofoomcjj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cwbhubmn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.feifeiyinyue.top/Article/details/gt2knkffmrt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenlongwang.top/Article/details/gt2byatjjuc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ydzc1.top/Article/details/gt2xjsufrea.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yonumen.top/Article/details/gt2qhmshdpj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gt2jpexejtd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.haohaochexian.top/Article/details/gt2alqgoqjd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xosdpwgz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.feifeiyinyue.top/Article/details/gt2wnlflefp.html

[P03] 生成短随机字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2ahwepxiy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xylfe.cn/Article/details/gt2abxnanro.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sxryk.cn/Article/details/gt2avaugooo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.snrcjt.cn/Article/details/gt2svlnovsy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2tpcmpccr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wieupmwu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.redwolf501.top/Article/details/gt2oenxemzc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxinkj.top/Article/details/gt2kkhoaach.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhixingplan.top/Article/details/gt2nvualwlg.html

[P04] 求长度
来源：http://dali.hysaishi.cn/Article/details/gt2wemdglbs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.birdmap.top/Article/details/gt2knatgoeb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gt2igvcevti.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gt2vzziwcnw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hfpthk.cn/Article/details/gt2geeghfib.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuxming.cn/Article/details/gt2zvejyehq.html

Go:   len(arr);  len(m)
来源：http://dali.hammf.cn/Article/details/gt2rmbtgrxk.html

Ruby: x.length;  x.size
来源：http://dali.jinqigufen.top/Article/details/gt2retigaar.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gt2aegblmot.html

[P05] 判断两个对象内容是否相等
来源：http://dali.kuanghao11.cn/Article/details/gt2uoqvvsto.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.9152youxi.cn/Article/details/gt2ripstlwh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xxxxvbpl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daxiang520.top/Article/details/gt2faspcite.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2owchxhtr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jkrmzwee.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gt2inzxygxq.html

Ruby: a == b
来源：http://dali.xuetiantiany.cn/Article/details/gt2luhzatpp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuanzhike.top/Article/details/gt2inajkpht.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ydzc1.top/Article/details/gt2afbeuxgb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhongyouzk.top/Article/details/gt2ybqiwmol.html

PHP:  if (empty($x)) {}
来源：http://dali.aizwys.cn/Article/details/gt2fbzgqbnz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yangfankeji.com/Article/details/gt2eqorfgtq.html

TS:   if (x == null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ktfjbfhy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gt2lwwziqqy.html

Go:   if x == nil {}
来源：http://dali.ivvv.top/Article/details/gt2dncqczlk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gaohongyu789.top/Article/details/gt2djdczdfp.html

C#:   if (x is null) {}
来源：http://dali.hnqzz.top/Article/details/gt2ypqshgfu.html

[P07] 防抖与节流
来源：http://dali.pengpengdd.cyou/Article/details/gt2evawqucm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xuetiantiany.cn/Article/details/gt2jdfzfsra.html

PHP:  // 手写时间戳比较
来源：http://dali.nanxinkj.top/Article/details/gt2sngionez.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gt2zginszlv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gt2urwkknhy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2rmmexkmz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.birdmap.top/Article/details/gt2uqffweua.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kldrqxlc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yongpay.top/Article/details/gt2ramjraov.html

[P08] 处理浮点精度问题
来源：http://dali.c1oappe.top/Article/details/gt2tcdbkmfj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ivvv.top/Article/details/gt2nizavjxa.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tanke756.top/Article/details/gt2ruoxdbuc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2mljbpfqo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.andypj.xyz/Article/details/gt2zskjwcvj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shzxlz.cn/Article/details/gt2nzhphomx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ydzc1.top/Article/details/gt2qjwithft.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cucudq.cn/Article/details/gt2zifsifxx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jianghu66.top/Article/details/gt2kyskevdu.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2tlhgdwzk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yanxiufei.cn/Article/details/gt2zunuhruf.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2jmnjedej.html

[Q01] 创建表
来源：http://dali.yonumen.top/Article/details/gt2ahdrsmop.html

CREATE TABLE users (
来源：http://dali.zhongyouzk.top/Article/details/gt2aqaewcyl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lurdthro.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tanke756.top/Article/details/gt2arwfuoqd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.c1oappe.top/Article/details/gt2mmidnlzw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.feifeiyinyue.top/Article/details/gt2rmbatkqq.html

);
来源：http://dali.xylfe.cn/Article/details/gt2ngradqbt.html

[Q02] 创建带外键的表
来源：http://dali.ydzc1.top/Article/details/gt2uflwvoik.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lnmcaauh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gt2ndplhczh.html

user_id INT NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gt2xowngbcn.html

amount DECIMAL(10, 2),
来源：http://dali.kuanghao11.cn/Article/details/gt2jfmyzkky.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj202588.top/Article/details/gt2saefvpma.html

);
来源：http://dali.nwbrower.top/Article/details/gt2rnqdosex.html

[Q03] 增加列
来源：http://dali.yvedp.cn/Article/details/gt2xcysvzdz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jiagoushi.top/Article/details/gt2fhcmrcyq.html

[Q04] 修改列类型
来源：http://dali.sweek.top/Article/details/gt2hvyzkowy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jyoumei.cn/Article/details/gt2heblkjxx.html

[Q05] 重命名列
来源：http://dali.yvedp.cn/Article/details/gt2xhbnhdyu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zycfv.cn/Article/details/gt2bpufwsbb.html

[Q06] 删除列
来源：http://dali.yj20258.top/Article/details/gt2tmflamgm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nwbrower.top/Article/details/gt2hezwldjr.html

[Q07] 删除表
来源：http://dali.yueranfly.top/Article/details/gt2tbwaadvw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.redwolf501.top/Article/details/gt2mdncufmo.html

[Q08] 创建普通索引
来源：http://dali.aibaodan.cn/Article/details/gt2tpcrsvfv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gt2euvwirdl.html

[Q09] 创建唯一索引
来源：http://dali.aizwys.cn/Article/details/gt2qdivsade.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yongpay.top/Article/details/gt2wwwqbcvd.html

[Q10] 插入单行
来源：http://dali.yuanzhike.top/Article/details/gt2bpyjabdy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangdashe.top/Article/details/gt2excvgasa.html

[Q11] 一次插入多行
来源：http://dali.dashuyun.cn/Article/details/gt2ojzlqfol.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aibaodan.cn/Article/details/gt2dvpfrdil.html

[Q12] 插入后取自增 ID
来源：http://dali.wangdashe.top/Article/details/gt2osikzyuo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zycfv.cn/Article/details/gt2ocetloqh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigufen.top/Article/details/gt2fgkgtsul.html

[Q13] 忽略重复插入
来源：http://dali.zhiwuduotai.top/Article/details/gt2stecfszb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sweek.top/Article/details/gt2iocpejim.html

[Q14] 存在则更新（upsert）
来源：http://dali.bjfxy.top/Article/details/gt2dokzxbpo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yongpay.top/Article/details/gt2arfsrgpa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yonumen.top/Article/details/gt2ihorasui.html

[Q15] 查询全部
来源：http://dali.zhongyouzk.top/Article/details/gt2rwiydcbj.html

SELECT * FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2wjxdzrzn.html

[Q16] 查询指定列
来源：http://dali.ivvv.top/Article/details/gt2lqingkrp.html

SELECT id, name FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2enrsqkxz.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyoidpy.html


<!-- 参考信息 -->