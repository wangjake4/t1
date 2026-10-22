代发 wailian999

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gt2opxbquog.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jianghu66.top/Article/details/gt2gzeiwnay.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.bjfxy.top/Article/details/gt2gsedzkak.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhongyouzk.top/Article/details/gt2tmmjwdae.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2ffxlhvsv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzztafq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.9152youxi.cn/Article/details/gt2jhxysywb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenzaomai.com/Article/details/gt2ejyjowmn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gt2zkfvljmf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gt2qvmrclkw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yanxiufei.cn/Article/details/gt2brxaqvmu.html

Go:   slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2acytjbsp.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gt2sbqkuygs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjleeqry.html

[N03] 快速排序（分治示例）
来源：http://dali.kuanghao11.cn/Article/details/gt2wdcqcijl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cqqwz.cn/Article/details/gt2siimerxa.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gotoacloud.top/Article/details/gt2xsngnmls.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fengsongda.top/Article/details/gt2ibvogjtb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gt2klulbrrp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yongpay.top/Article/details/gt2polzminy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ppjwa.cn/Article/details/gt2mgysmrbg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jlsjyb.cn/Article/details/gt2dggsrbix.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj202588.top/Article/details/gt2guqajwto.html

[N04] 斐波那契数列
来源：http://dali.jqgufenzy.top/Article/details/gt2rxsaspea.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hywenlv.cn/Article/details/gt2dsfonjft.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fxlqkydv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gt2ceznkcpt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2hjesukrl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnqzz.top/Article/details/gt2aytwbloc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ehwqpu.com/Article/details/gt2bovvvdpp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2sphpgcef.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2qoabxkoh.html

[N05] 最大公约数
来源：http://dali.yuxming.cn/Article/details/gt2hvxsflnl.html

Py:   math.gcd(a, b)
来源：http://dali.bjfxy.top/Article/details/gt2vnslsmyj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yongpay.top/Article/details/gt2ykcshqlo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gt2otkhmaee.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gt2uasksxmy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258888.top/Article/details/gt2mmsrlfic.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yonumen.top/Article/details/gt2tsruomnj.html

Ruby: a.gcd(b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xshftbup.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gwevpcjp.html

[N06] 判断回文字符串
来源：http://dali.hammf.cn/Article/details/gt2oosjhwda.html

Py:   s == s[::-1]
来源：http://dali.jyoumei.cn/Article/details/gt2xglzjkub.html

PHP:  $s === strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gt2xbjkyyjb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2hrzbbahl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gt2mtcumlbd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hongshengwenyu.top/Article/details/gt2oawhrcod.html

Go:   // 双指针从两端比较
来源：http://dali.daxiang520.top/Article/details/gt2eczotztw.html

Ruby: s == s.reverse
来源：http://dali.yanxiufei.cn/Article/details/gt2vqterjon.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gt2rswbqifi.html

[N07] 两数之和（返回下标）
来源：http://dali.cdnleiting.top/Article/details/gt2huropphf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xuanzx.com/Article/details/gt2ominzfkq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.0kj1m.cn/Article/details/gt2tpfzqxes.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigfzy.top/Article/details/gt2scmimgxs.html

TS:   // 手写 Map<string, number>
来源：http://dali.iojbl.cn/Article/details/gt2nmmqveli.html

Java: // 手写 HashMap
来源：http://dali.chenjidiqi.icu/Article/details/gt2qjlkborn.html

Go:   // 手写 map[int]int
来源：http://dali.yongpay.top/Article/details/gt2ldkfvccy.html

Ruby: // 手写 Hash
来源：http://dali.feifeiyinyue.top/Article/details/gt2jkrqzxza.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.redwolf501.top/Article/details/gt2gcfzixuw.html

[N08] 生成全排列
来源：http://dali.zdqjudy.top/Article/details/gt2aweghiet.html

Py:   itertools.permutations(arr)
来源：http://dali.ybcxt.top/Article/details/gt2iwomsyjw.html

PHP:  // 手写递归交换
来源：http://dali.svipenyu.cn/Article/details/gt2szhqijub.html

JS:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gt2puqxukeg.html

TS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2wamdvqtm.html

Java: // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2ymrzyzpy.html

Go:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ghdrrkuq.html

Ruby: arr.permutation.to_a
来源：http://dali.tian-w.cn/Article/details/gt2pzwbkjla.html

C#:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2bkilfnqh.html

[N09] 栈与队列
来源：http://dali.xziqi.cn/Article/details/gt2ziczpmgk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.c1oappe.top/Article/details/gt2mxfwimbp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2xertubve.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gt2skgiuwzr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nwbrower.top/Article/details/gt2ocufjqsm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cucudq.cn/Article/details/gt2ecukqdao.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnxiangtu.top/Article/details/gt2lhoupaly.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gt2erqzpbos.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jqgfzy.top/Article/details/gt2ypzqerfp.html

[N10] 链表节点定义
来源：http://dali.quarkkingdee.top/Article/details/gt2vulydhbr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.smart0.xyz/Article/details/gt2yaeuennx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.316326.xyz/Article/details/gt2pajyarkv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yonumen.top/Article/details/gt2nbtupggn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jianghu66.top/Article/details/gt2qgvpmloz.html

Java: class Node { int v; Node next; }
来源：http://dali.0kj1m.cn/Article/details/gt2afuejqzx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jiagoushi.top/Article/details/gt2ablxtuzs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ivvv.top/Article/details/gt2glgsnuof.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pycfn.com/Article/details/gt2ofwxncoi.html

[N11] 二叉树中序遍历
来源：http://dali.hnqzz.top/Article/details/gt2dahianyr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhengqikj.top/Article/details/gt2ckudaqvi.html

PHP:  // 手写递归函数
来源：http://dali.bjfxy.top/Article/details/gt2frlvwrzg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gt2zmdnqdvj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gt2mxpxivzl.html

Java: // 手写递归
来源：http://dali.xinyue.icu/Article/details/gt2oiddlxdc.html

Go:   // 手写递归
来源：http://dali.birdmap.top/Article/details/gt2eugrjqgm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hnxiangtu.top/Article/details/gt2pbioxree.html

C#:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gt2laxtazno.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tian-w.cn/Article/details/gt2pkeufqkz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhoulong.xyz/Article/details/gt2cznnvvsp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aizwys.cn/Article/details/gt2ujxqzvtm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.9152youxi.cn/Article/details/gt2bjozekda.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gt2wfxtnjer.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gt2qzgbdusf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.havefunace.top/Article/details/gt2jcpbogny.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgfzy.top/Article/details/gt2bhhhzvyy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgufenzy.top/Article/details/gt2rerbfmph.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2vnlbnimf.html

O. 并发与异步
来源：http://dali.aibaodan.cn/Article/details/gt2frazimlx.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2pfpyaxnq.html

[O01] 启动一个线程
来源：http://dali.xylfe.cn/Article/details/gt2xdcdzrwb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ehwqpu.com/Article/details/gt2kkvnzpwi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.vqdsnc.cn/Article/details/gt2uhkauekc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.kuanghao11.cn/Article/details/gt2jewufmlu.html

TS:   // 同 JS
来源：http://dali.ppjwa.cn/Article/details/gt2ctfadvvg.html

Java: new Thread(() -> f()).start()
来源：http://dali.ehwqpu.com/Article/details/gt2vvgesyfm.html

Go:   go f()
来源：http://dali.tianlin.xyz/Article/details/gt2cobyxwsk.html

Ruby: Thread.new { f }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xztqbnxo.html

C#:   Task.Run(() => F());
来源：http://dali.chenzaomai.com/Article/details/gt2rclgcmtn.html

[O02] 使用线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tsrmpicp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.havefunace.top/Article/details/gt2advacups.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.snrcjt.cn/Article/details/gt2ctmbdjhz.html

JS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gt2vywtzbzj.html

TS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gt2aojeqqzr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cheryme.top/Article/details/gt2tnuotjsz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cqqwz.cn/Article/details/gt2dwiupsjg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hnqzz.top/Article/details/gt2jnwueaah.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cashguo.top/Article/details/gt2xdeyawno.html

[O03] 加锁保护共享数据
来源：http://dali.yj20258.top/Article/details/gt2ppsbgeje.html

Py:   with lock: shared += 1
来源：http://dali.jinqigfzy.top/Article/details/gt2dghmmxrk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgfzy.top/Article/details/gt2jxvokrbj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tanke756.top/Article/details/gt2oavslajq.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gt2efpvortk.html

Java: synchronized (this) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gt2uebqxhog.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.aizwys.cn/Article/details/gt2xxezrzch.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ariexqtf.html

C#:   lock (gate) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bkrxkymw.html

[O04] 定义异步函数并等待
来源：http://dali.bjfxy.top/Article/details/gt2xbgyqqfh.html

Py:   async def f():⏎    await g()
来源：http://dali.gotoacloud.top/Article/details/gt2ykhmoykt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.iojbl.cn/Article/details/gt2nucnfvex.html

JS:   async function f() { await g(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ehheinuz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.meibo888.top/Article/details/gt2skomuqfy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenzaomai.com/Article/details/gt2plldxyvb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.meibo888.top/Article/details/gt2gbtdfftk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.snrcjt.cn/Article/details/gt2ddpvpwke.html

C#:   async Task F() { await G(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2smvvpcay.html

[O05] 并发执行并等待全部完成
来源：http://dali.9152youxi.cn/Article/details/gt2vlgnczvu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nwbrower.top/Article/details/gt2elwjgosx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.mhx1999.top/Article/details/gt2dcoflsig.html

JS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gt2xqwjzmvr.html

TS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gt2drzngxks.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hongshengwenyu.top/Article/details/gt2jzpnxtpm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yuxming.cn/Article/details/gt2kdlbnpbq.html

Ruby: threads.map(&:join)
来源：http://dali.havefunace.top/Article/details/gt2itrfdwoy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zycfv.cn/Article/details/gt2lpmazhfz.html

[O06] 使用进程池
来源：http://dali.sufxvd.cn/Article/details/gt2isxxkakn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ivvv.top/Article/details/gt2zaukjwmd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jlsjyb.cn/Article/details/gt2itvanotq.html

JS:   // child_process / cluster 模块
来源：http://dali.xuanzx.com/Article/details/gt2aqonlxjx.html

TS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gt2wqoaehim.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.iojbl.cn/Article/details/gt2vwvheonp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.guowangkeji.top/Article/details/gt2afvvsrtd.html

Ruby: // fork 块
来源：http://dali.hnqzz.top/Article/details/gt2kvgdxxop.html

C#:   Parallel.For
来源：http://dali.yongpay.top/Article/details/gt2johzhdka.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2zafmllhu.html

P. 常用工具函数
来源：http://dali.ydzc1.top/Article/details/gt2vrnyfpzl.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2aoxmspbd.html

[P01] 生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gt2niccglhv.html

Py:   str(uuid.uuid4())
来源：http://dali.smart0.xyz/Article/details/gt2niqgmfiq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wnwszfwr.html

JS:   crypto.randomUUID()
来源：http://dali.yj20258888.top/Article/details/gt2ivkjlmha.html

TS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gt2qamfuzbr.html

Java: UUID.randomUUID().toString()
来源：http://dali.sufxvd.cn/Article/details/gt2jydvsrhl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenzaomai.com/Article/details/gt2bpssibla.html

Ruby: SecureRandom.uuid
来源：http://dali.zdqjudy.top/Article/details/gt2kscerwgf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ppjwa.cn/Article/details/gt2umwuddnx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dcdmtvtc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhixingplan.top/Article/details/gt2llgsjycv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hywenlv.cn/Article/details/gt2dnlfukfo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guannengcc.top/Article/details/gt2pmtsluzf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hammf.cn/Article/details/gt2bspckpmv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sweek.top/Article/details/gt2dponourk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxinkj.top/Article/details/gt2obwrqgjp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gogol.net.cn/Article/details/gt2ofodklrf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxinkj.top/Article/details/gt2ivlegeiz.html

[P03] 生成短随机字符串
来源：http://dali.fzhhl.top/Article/details/gt2ssciyiwj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nwbrower.top/Article/details/gt2svhtcwcm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xinyue.icu/Article/details/gt2kohogxpo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gt2sdgqsuko.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgfzy.top/Article/details/gt2mijjilaj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2idcehaso.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.feifeiyinyue.top/Article/details/gt2klcalytt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.fengsongda.top/Article/details/gt2wgrsdnqn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ybcxt.top/Article/details/gt2mhndrbht.html

[P04] 求长度
来源：http://dali.nanxinkj.top/Article/details/gt2nlellxjq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tianlin.xyz/Article/details/gt2nxxmrnky.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gt2bmtgqywh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cheryme.top/Article/details/gt2zaihorrx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gt2lhiiuryz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.0kj1m.cn/Article/details/gt2vpgoodvg.html

Go:   len(arr);  len(m)
来源：http://dali.yuxming.cn/Article/details/gt2pulacejp.html

Ruby: x.length;  x.size
来源：http://dali.yj20258888.top/Article/details/gt2tkcsuptb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fengsongda.top/Article/details/gt2flajuetl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zdqjudy.top/Article/details/gt2jzuxsovh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fengsongda.top/Article/details/gt2ngvbaixa.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yanxiufei.cn/Article/details/gt2xeilovyy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2duiuumti.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hysaishi.cn/Article/details/gt2wusinfek.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sxryk.cn/Article/details/gt2elhhojab.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigufen.top/Article/details/gt2dbbkmswq.html

Ruby: a == b
来源：http://dali.aibaodan.cn/Article/details/gt2caqnlcba.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xuanzx.com/Article/details/gt2gbvcrbkg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aydcuwdv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenjidiqi.icu/Article/details/gt2wmjubvia.html

PHP:  if (empty($x)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hvzdzher.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dashuyun.cn/Article/details/gt2eyyezbgj.html

TS:   if (x == null) {}
来源：http://dali.nanxinkj.top/Article/details/gt2lctibqjz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.fzhhl.top/Article/details/gt2wpfwhmge.html

Go:   if x == nil {}
来源：http://dali.cheryme.top/Article/details/gt2apeuwcwa.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhoulong.xyz/Article/details/gt2hdexinsk.html

C#:   if (x is null) {}
来源：http://dali.redwolf501.top/Article/details/gt2ygwqlryx.html

[P07] 防抖与节流
来源：http://dali.sxryk.cn/Article/details/gt2zwppeflo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ppjwa.cn/Article/details/gt2frwtpxgj.html

PHP:  // 手写时间戳比较
来源：http://dali.jyoumei.cn/Article/details/gt2akhvihzp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gt2pirazutx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gt2viibzhum.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenzaomai.com/Article/details/gt2rxbxpgii.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tian-w.cn/Article/details/gt2vbbupbwi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gzhubu.top/Article/details/gt2rsxfatte.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinqigufen.top/Article/details/gt2jodhlbgt.html

[P08] 处理浮点精度问题
来源：http://dali.jianghu66.top/Article/details/gt2xdftvfzz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenzaomai.com/Article/details/gt2wrwjabll.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj202588.top/Article/details/gt2qcxvkudj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinqigufen.top/Article/details/gt2fewoawwp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hfpthk.cn/Article/details/gt2askxabyg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gzhubu.top/Article/details/gt2ximadopm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhiwuduotai.top/Article/details/gt2gowjjzry.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hnxiangtu.top/Article/details/gt2qvunbxew.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cucudq.cn/Article/details/gt2pvrpjeqz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2zaruuhxu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.quarkkingdee.top/Article/details/gt2xtmdmqdg.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2nboekoqg.html

[Q01] 创建表
来源：http://dali.xuanzx.com/Article/details/gt2crhqmrwc.html

CREATE TABLE users (
来源：http://dali.jinqigufen.top/Article/details/gt2wmetesye.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gt2pshzqjsp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gt2jywxsnxz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ydzc1.top/Article/details/gt2qslmujaj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ycyierkw.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdfwerfs.html

[Q02] 创建带外键的表
来源：http://dali.jinqigfzy.top/Article/details/gt2gfxzzgzr.html

CREATE TABLE orders (
来源：http://dali.hfpthk.cn/Article/details/gt2rlkztiyk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gt2vfflndrj.html

user_id INT NOT NULL,
来源：http://dali.hammf.cn/Article/details/gt2vnhqxeev.html

amount DECIMAL(10, 2),
来源：http://dali.ehwqpu.com/Article/details/gt2clahhczo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.mhx1999.top/Article/details/gt2ggdyfrbb.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2skvcooky.html

[Q03] 增加列
来源：http://dali.sufxvd.cn/Article/details/gt2bhmahlaq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cheryme.top/Article/details/gt2lwbhjhyp.html

[Q04] 修改列类型
来源：http://dali.ehwqpu.com/Article/details/gt2lsrcnoan.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuanzhike.top/Article/details/gt2famqkbcg.html

[Q05] 重命名列
来源：http://dali.yueranfly.top/Article/details/gt2ftyqndwy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sysykeji.top/Article/details/gt2naddghqp.html

[Q06] 删除列
来源：http://dali.ppjwa.cn/Article/details/gt2awixjcry.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wpquwnrn.html

[Q07] 删除表
来源：http://dali.dianchejie.cn/Article/details/gt2cjvrrklb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuxming.cn/Article/details/gt2tvwakqbd.html

[Q08] 创建普通索引
来源：http://dali.aizwys.cn/Article/details/gt2hzfvzslc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.redwolf501.top/Article/details/gt2sqnszxzt.html

[Q09] 创建唯一索引
来源：http://dali.jyoumei.cn/Article/details/gt2whttddtf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gt2kdumkfgs.html

[Q10] 插入单行
来源：http://dali.hnqzz.top/Article/details/gt2qqebcmts.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ppjwa.cn/Article/details/gt2cyqvkltb.html

[Q11] 一次插入多行
来源：http://dali.pengpengdd.cyou/Article/details/gt2pjqcnmxo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gt2qwvjejrf.html

[Q12] 插入后取自增 ID
来源：http://dali.yanxiufei.cn/Article/details/gt2wfiqjvtq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jdpxknkz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258888.top/Article/details/gt2bppnylbg.html

[Q13] 忽略重复插入
来源：http://dali.cheryme.top/Article/details/gt2nifybvxy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yonumen.top/Article/details/gt2wykqnbbs.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenzaomai.com/Article/details/gt2xelmcibw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenjidiqi.icu/Article/details/gt2fqrqzwvo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sweek.top/Article/details/gt2eeryqalv.html

[Q15] 查询全部
来源：http://dali.cucudq.cn/Article/details/gt2haeoktgh.html

SELECT * FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2rcsabpox.html

[Q16] 查询指定列
来源：http://dali.iojbl.cn/Article/details/gt2oreabeph.html

SELECT id, name FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2phauswrk.html

[Q17] 条件查询
来源：http://dali.redwolf501.top/Article/details/gt2kjxnepka.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zycfv.cn/Article/details/gt2rcritwwa.html

[Q18] 模糊匹配
来源：http://dali.yangfankeji.com/Article/details/gt2omdmmqrq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.c1oappe.top/Article/details/gt2vkfsxymh.html

[Q19] 范围查询
来源：http://dali.zhoulong.xyz/Article/details/gt2cbgfxtqd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.daxiang520.top/Article/details/gt2uarsnfrr.html

[Q20] IN 列表
来源：http://dali.nwbrower.top/Article/details/gt2daibchje.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sbkpcaop.html

[Q21] 空值判断
来源：http://dali.jiagoushi.top/Article/details/gt2gdtyqmga.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258.top/Article/details/gt2jgbbvdnf.html

[Q22] 排序
来源：http://dali.ivvv.top/Article/details/gt2pzjyqret.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgfzy.top/Article/details/gt2ujmguocr.html

[Q23] 分页
来源：http://dali.vqdsnc.cn/Article/details/gt2lhasfoxh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.aibaodan.cn/Article/details/gt2hydmjnpo.html

[Q24] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iiscdeip.html

SELECT DISTINCT city FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2bbtupjtg.html

[Q25] 只取前 N 条
来源：http://dali.feifeiyinyue.top/Article/details/gt2zwpkdhsf.html


<!-- 参考信息 -->