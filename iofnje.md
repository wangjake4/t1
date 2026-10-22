代发 wailian999

TS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gtuasxqtec.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxinkj.top/Article/details/gtxbsfgien.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cashguo.top/Article/details/gtkcotacxa.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gtkxkdmjja.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangdashe.top/Article/details/gtztkuqvpu.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtnhnuexlv.html

N. 数据结构与算法
来源：http://dali.chenzaomai.com/Article/details/gtzzrjtdit.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtskgjeywn.html

[N01] 二分查找（有序数组）
来源：http://dali.ybcxt.top/Article/details/gtdizhhutk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtydejwcbv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvekfvliy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gtqzbhefwy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtvjvzcrkt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtyxouqvkh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpxtluul.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tianlin.xyz/Article/details/gtbfqjqyqn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gttgeldzrb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zdqjudy.top/Article/details/gtpylktoxn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gtfnbjfffg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gteuwkymdo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtdrussfgp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gtupzkszzu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ydzc1.top/Article/details/gtarnkekgl.html

Go:   slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gtdlczdjeb.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gtqlqyvzpg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dashuyun.cn/Article/details/gtgzhgubpi.html

[N03] 快速排序（分治示例）
来源：http://dali.cashguo.top/Article/details/gtycazanzh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xziqi.cn/Article/details/gtoksswcjj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.iojbl.cn/Article/details/gtlfnhnvwe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gtyrykfyfn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gtcryjdqiv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hfpthk.cn/Article/details/gtuxbiarko.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zdqjudy.top/Article/details/gtlegyrypv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwqpghdb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daria6918.cn/Article/details/gtmgsoqsuz.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangtech.top/Article/details/gtgphdcvti.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gtzsbudoxe.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gtcshfhmow.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gtxkutkqwv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gtoawoyblb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pycfn.com/Article/details/gtxeasqpgz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnxiangtu.top/Article/details/gtddyhzntw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtlwmhtpll.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtvatazzfn.html

[N05] 最大公约数
来源：http://dali.ppjwa.cn/Article/details/gtieapvxfs.html

Py:   math.gcd(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtswqtdlpw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xziqi.cn/Article/details/gtcsvobijy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aizwys.cn/Article/details/gturyawquc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shuidangran.top/Article/details/gtpdawykgh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhengqikj.top/Article/details/gtrdshmtyb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shuidangran.top/Article/details/gtkgvmuvnv.html

Ruby: a.gcd(b)
来源：http://dali.snrcjt.cn/Article/details/gthaizpsau.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.meibo888.top/Article/details/gtxghyqjdw.html

[N06] 判断回文字符串
来源：http://dali.daxiang520.top/Article/details/gtqhfujpvm.html

Py:   s == s[::-1]
来源：http://dali.tian-w.cn/Article/details/gttmllsrds.html

PHP:  $s === strrev($s);
来源：http://dali.kuanghao11.cn/Article/details/gtealpmqvy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsofusaus.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtveroawzt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.snrcjt.cn/Article/details/gtbawzjdzl.html

Go:   // 双指针从两端比较
来源：http://dali.cucudq.cn/Article/details/gtlggagwkj.html

Ruby: s == s.reverse
来源：http://dali.quarkkingdee.top/Article/details/gtovjybetu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gtdxpxoquv.html

[N07] 两数之和（返回下标）
来源：http://dali.cdnleiting.top/Article/details/gtguybdxrr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hfpthk.cn/Article/details/gtznemrnwj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.meibo888.top/Article/details/gtgsbnbtvg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.9152youxi.cn/Article/details/gtwyvzzsll.html

TS:   // 手写 Map<string, number>
来源：http://dali.hywenlv.cn/Article/details/gtefupltap.html

Java: // 手写 HashMap
来源：http://dali.xuetiantiany.cn/Article/details/gtwygydlju.html

Go:   // 手写 map[int]int
来源：http://dali.cucudq.cn/Article/details/gtdxlxdmcc.html

Ruby: // 手写 Hash
来源：http://dali.tianlin.xyz/Article/details/gtoxguhjin.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yueranfly.top/Article/details/gtrvjogiwp.html

[N08] 生成全排列
来源：http://dali.shangyingyoupin.top/Article/details/gtqnpwmdge.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtuncrlvzp.html

PHP:  // 手写递归交换
来源：http://dali.cqqwz.cn/Article/details/gtxpdhgvwg.html

JS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtmpfiowvq.html

TS:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtnksnlafv.html

Java: // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtdjudnkmn.html

Go:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtfvzadpmg.html

Ruby: arr.permutation.to_a
来源：http://dali.zhoulong.xyz/Article/details/gtbysurhiu.html

C#:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtdggpslwk.html

[N09] 栈与队列
来源：http://dali.gaohongyu789.top/Article/details/gtfjlqljrb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtrnfshxkb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtzwdrncri.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtivaarjra.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.bjfxy.top/Article/details/gtvujsewoa.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cucudq.cn/Article/details/gtqdxxmllp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jqgfzy.top/Article/details/gttlmygtzw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtahwxdteg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yueranfly.top/Article/details/gtkmnrjijb.html

[N10] 链表节点定义
来源：http://dali.xinyue.icu/Article/details/gtauktapgn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yuxming.cn/Article/details/gtdgdftefd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ydzc1.top/Article/details/gtwvmghdib.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtixyymtqs.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvucvjrb.html

Java: class Node { int v; Node next; }
来源：http://dali.cqqwz.cn/Article/details/gtigqwtids.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jyoumei.cn/Article/details/gtfjlhgdql.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.andypj.xyz/Article/details/gtjcpfdjks.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnqzz.top/Article/details/gtchenavtl.html

[N11] 二叉树中序遍历
来源：http://dali.bjfxy.top/Article/details/gttbuuswjw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tianlin.xyz/Article/details/gtldfqzwes.html

PHP:  // 手写递归函数
来源：http://dali.birdmap.top/Article/details/gtscxrxugp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gtzekqyfpi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gtgjivbfmj.html

Java: // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gtdnsuhrbp.html

Go:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gthfoeckak.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258888.top/Article/details/gthcmyzfut.html

C#:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gtwhzzsnqh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jianghu66.top/Article/details/gtlxqfaaay.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.guannengcc.top/Article/details/gtdtrdenvu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.iojbl.cn/Article/details/gtlexmpeer.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gtblwkexrz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gtnmzprzel.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gtqigcncfp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhongyouzk.top/Article/details/gtzswjvfcl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtiuhouoow.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gthcnkhllf.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtbqxpfeqd.html

O. 并发与异步
来源：http://dali.zhaomingkeji.xyz/Article/details/gteurcocre.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gturliilyj.html

[O01] 启动一个线程
来源：http://dali.hywenlv.cn/Article/details/gtmnpdiqtx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tanke756.top/Article/details/gtsokkvxbf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gogol.net.cn/Article/details/gtzerenarl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ppjwa.cn/Article/details/gtcshfwsox.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gtqknpeitt.html

Java: new Thread(() -> f()).start()
来源：http://dali.aibaodan.cn/Article/details/gtsqtauyxx.html

Go:   go f()
来源：http://dali.aibaodan.cn/Article/details/gtticgnnbk.html

Ruby: Thread.new { f }
来源：http://dali.jianghu66.top/Article/details/gtdbyouwos.html

C#:   Task.Run(() => F());
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpgrviva.html

[O02] 使用线程池
来源：http://dali.zhixingplan.top/Article/details/gttjaleaax.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigfzy.top/Article/details/gtczuxmiks.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yonumen.top/Article/details/gtmzmuegbv.html

JS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gtdvsuhfed.html

TS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gtkaciaxfp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aibaodan.cn/Article/details/gtededqaqy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jiagoushi.top/Article/details/gtogsozgbi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpbwkrxd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.c1oappe.top/Article/details/gtgxqakdnq.html

[O03] 加锁保护共享数据
来源：http://dali.daria6918.cn/Article/details/gtqhwiqeuo.html

Py:   with lock: shared += 1
来源：http://dali.ydzc1.top/Article/details/gtpkrajhwu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shangyingyoupin.top/Article/details/gtnnlknoqv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fzhhl.top/Article/details/gtehspamfn.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gtelcamgxx.html

Java: synchronized (this) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gteljtulie.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xinyue.icu/Article/details/gtobhxoaxc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.bjfxy.top/Article/details/gtrerfkxbw.html

C#:   lock (gate) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gttciiffuo.html

[O04] 定义异步函数并等待
来源：http://dali.haohaochexian.top/Article/details/gtgcfgajnl.html

Py:   async def f():⏎    await g()
来源：http://dali.zdqjudy.top/Article/details/gtqunbukoa.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zdqjudy.top/Article/details/gtgyvxzbvd.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gtaovtkokj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj202588.top/Article/details/gtfgprlrib.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.birdmap.top/Article/details/gtodgtpayp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.feifeiyinyue.top/Article/details/gtvyvkxxku.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yonumen.top/Article/details/gtymdpecux.html

C#:   async Task F() { await G(); }
来源：http://dali.shuidangran.top/Article/details/gtkbhfkooy.html

[O05] 并发执行并等待全部完成
来源：http://dali.pycfn.com/Article/details/gtvjvmrtui.html

Py:   asyncio.gather(*tasks)
来源：http://dali.bjfxy.top/Article/details/gtyeocxcne.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhiaudtq.html

JS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvcvlami.html

TS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gtfcvdmweh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj20258888.top/Article/details/gtsdhoqbel.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj20258888.top/Article/details/gtbbgwabol.html

Ruby: threads.map(&:join)
来源：http://dali.yongpay.top/Article/details/gttcoafuyd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigufen.top/Article/details/gtyoihtbpc.html

[O06] 使用进程池
来源：http://dali.yonumen.top/Article/details/gtfvwhspxq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.0kj1m.cn/Article/details/gtlxlctvky.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jqgufenzy.top/Article/details/gtdlftzcrp.html

JS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydtttizr.html

TS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gtipgiiacp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gtoejeyzng.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinqigfzy.top/Article/details/gtoclhsxrk.html

Ruby: // fork 块
来源：http://dali.ydzc1.top/Article/details/gteccbaujw.html

C#:   Parallel.For
来源：http://dali.yongpay.top/Article/details/gtdfmlsglm.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtubiofdsk.html

P. 常用工具函数
来源：http://dali.zhoulong.xyz/Article/details/gtkzjhoioj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtejzvhtya.html

[P01] 生成 UUID
来源：http://dali.xziqi.cn/Article/details/gtgyuiecle.html

Py:   str(uuid.uuid4())
来源：http://dali.cheryme.top/Article/details/gtvkkjwuep.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.quarkkingdee.top/Article/details/gtpcsbenjq.html

JS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gtovibgmtr.html

TS:   crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gthcroycpv.html

Java: UUID.randomUUID().toString()
来源：http://dali.xuanzx.com/Article/details/gtxsxlusjr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ehwqpu.com/Article/details/gtgqysolfc.html

Ruby: SecureRandom.uuid
来源：http://dali.jyoumei.cn/Article/details/gtxjrzzlze.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.0kj1m.cn/Article/details/gtgnuwwhoy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jianghu66.top/Article/details/gterskhjnt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbciaurxp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtodnwishs.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbncvwnf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hysaishi.cn/Article/details/gtdstzpgjm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtudsolpcn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhixingplan.top/Article/details/gtdemqdjlq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgfzy.top/Article/details/gtdrieytdl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aibaodan.cn/Article/details/gtigaybbeq.html

[P03] 生成短随机字符串
来源：http://dali.daria6918.cn/Article/details/gtkyzpgzjb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenlongwang.top/Article/details/gtrbwtjroe.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjmtehtnk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yueranfly.top/Article/details/gtowuvaoui.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xylfe.cn/Article/details/gtcuunuyor.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtiqrfmitx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yuanzhike.top/Article/details/gtmsowlqyz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daria6918.cn/Article/details/gtnobmamnb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gaohongyu789.top/Article/details/gtwcwejnrr.html

[P04] 求长度
来源：http://dali.cashguo.top/Article/details/gtdfgbdgnp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.fzhhl.top/Article/details/gthfksiwal.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtyoafstyh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gtdaserdcf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gtixdzgnrq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gttyhbpqey.html

Go:   len(arr);  len(m)
来源：http://dali.yuxming.cn/Article/details/gtwbeczkwr.html

Ruby: x.length;  x.size
来源：http://dali.tanke756.top/Article/details/gtdbxqbqta.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ybcxt.top/Article/details/gtdzonstqg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ppjwa.cn/Article/details/gtslxdjmqh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhongyouzk.top/Article/details/gteepypbzp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinqigfzy.top/Article/details/gteyjrlabe.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jianghu66.top/Article/details/gtliwrcfil.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xziqi.cn/Article/details/gtauhcqzvr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgiwxwlp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gzhubu.top/Article/details/gtrdykfzwg.html

Ruby: a == b
来源：http://dali.shangyingyoupin.top/Article/details/gtfredpswd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yanxiufei.cn/Article/details/gtgxtxpnhx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj20258888.top/Article/details/gtkzydplpr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gtziuotdml.html

PHP:  if (empty($x)) {}
来源：http://dali.c1oappe.top/Article/details/gtfedcaaau.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xziqi.cn/Article/details/gtpnvujamn.html

TS:   if (x == null) {}
来源：http://dali.zdqjudy.top/Article/details/gtkgryuast.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hfpthk.cn/Article/details/gtxzpybqmc.html

Go:   if x == nil {}
来源：http://dali.chenlongwang.top/Article/details/gtxhxivtkb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yueranfly.top/Article/details/gtfdesataq.html

C#:   if (x is null) {}
来源：http://dali.ybcxt.top/Article/details/gtonokzuiw.html

[P07] 防抖与节流
来源：http://dali.hammf.cn/Article/details/gtsmlfgbcr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.havefunace.top/Article/details/gtxkaxgkos.html

PHP:  // 手写时间戳比较
来源：http://dali.wangdashe.top/Article/details/gtyphabffk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gtewdpfcxv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gtgcgzzpei.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhongyouzk.top/Article/details/gtjloxtdip.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sxryk.cn/Article/details/gtmjpcxkzt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.redwolf501.top/Article/details/gtobagxsxt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hammf.cn/Article/details/gtobofyrma.html

[P08] 处理浮点精度问题
来源：http://dali.guowangkeji.top/Article/details/gtfjqrahze.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.smart0.xyz/Article/details/gtdeqhojeg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gtxeifklsx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sysykeji.top/Article/details/gtssiuxhhd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtpztoxfaf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.andypj.xyz/Article/details/gthmefimio.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jyoumei.cn/Article/details/gtwajxeprl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xinyue.icu/Article/details/gtpsopxhui.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhiwuduotai.top/Article/details/gtrdptuylz.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtgsskhuhi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sweek.top/Article/details/gtyunxisno.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtnwwokpef.html

[Q01] 创建表
来源：http://dali.xinyue.icu/Article/details/gtxevqmyin.html

CREATE TABLE users (
来源：http://dali.ydzc1.top/Article/details/gtrtxxufgg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jianghu66.top/Article/details/gtzfopplqo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yongpay.top/Article/details/gtvghumxte.html

email VARCHAR(100) UNIQUE,
来源：http://dali.fzhhl.top/Article/details/gthkjqadod.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigfzy.top/Article/details/gtmxkdntjg.html

);
来源：http://dali.nwbrower.top/Article/details/gtvpgfuoiq.html

[Q02] 创建带外键的表
来源：http://dali.snrcjt.cn/Article/details/gtchgtmuyx.html

CREATE TABLE orders (
来源：http://dali.fzhhl.top/Article/details/gtkzzicmet.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gtjebumrkr.html

user_id INT NOT NULL,
来源：http://dali.jqgufenzy.top/Article/details/gtjhmfakdj.html

amount DECIMAL(10, 2),
来源：http://dali.yj20258888.top/Article/details/gtbpyrkzep.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tian-w.cn/Article/details/gtwnwcsdqa.html

);
来源：http://dali.mhx1999.top/Article/details/gtxzsolgpe.html

[Q03] 增加列
来源：http://dali.fzhhl.top/Article/details/gtdraqdfeu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jianghu66.top/Article/details/gtioprdxxe.html

[Q04] 修改列类型
来源：http://dali.yvedp.cn/Article/details/gtwhhxpdyq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.smart0.xyz/Article/details/gtmixvkeaa.html

[Q05] 重命名列
来源：http://dali.daxiang520.top/Article/details/gtflknebgj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.bjfxy.top/Article/details/gtwotrdrta.html

[Q06] 删除列
来源：http://dali.yanxiufei.cn/Article/details/gtdkwwmpps.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gotoacloud.top/Article/details/gtxvfjhvfv.html

[Q07] 删除表
来源：http://dali.zhoulong.xyz/Article/details/gtlkznkfnx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhengqikj.top/Article/details/gtbwcwsptc.html

[Q08] 创建普通索引
来源：http://dali.sufxvd.cn/Article/details/gtjmykzivj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gtxqwwnyks.html

[Q09] 创建唯一索引
来源：http://dali.aizwys.cn/Article/details/gtppswywuh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gtifikomkh.html

[Q10] 插入单行
来源：http://dali.nanxinkj.top/Article/details/gtaetlsodu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tanke756.top/Article/details/gtfdywhlxl.html

[Q11] 一次插入多行
来源：http://dali.dianchejie.cn/Article/details/gttbwrlqzw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.pycfn.com/Article/details/gtujqaanss.html

[Q12] 插入后取自增 ID
来源：http://dali.jinqigufen.top/Article/details/gtsaojsjov.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj20258.top/Article/details/gtqbbekscv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hongshengwenyu.top/Article/details/gtoxaluvcz.html

[Q13] 忽略重复插入
来源：http://dali.hongshengwenyu.top/Article/details/gtfrsczsjy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gtnmdsdsjj.html

[Q14] 存在则更新（upsert）
来源：http://dali.shanyushiyangtech.top/Article/details/gtewzspuaf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shzxlz.cn/Article/details/gtfonpgldf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmtlejan.html

[Q15] 查询全部
来源：http://dali.nanxinkj.top/Article/details/gtwfzogetk.html

SELECT * FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtnquxofmy.html

[Q16] 查询指定列
来源：http://dali.zhiwuduotai.top/Article/details/gtxiedgqzy.html

SELECT id, name FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtajenrryq.html

[Q17] 条件查询
来源：http://dali.cheryme.top/Article/details/gthrpyauww.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tanke756.top/Article/details/gtrvmgjtxp.html

[Q18] 模糊匹配
来源：http://dali.0kj1m.cn/Article/details/gtdodlleoc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shanyushiyangtech.top/Article/details/gtyslvcelr.html

[Q19] 范围查询
来源：http://dali.xuetiantiany.cn/Article/details/gtqhdiybvk.html


<!-- 参考信息 -->