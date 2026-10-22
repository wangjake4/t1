代发 wailian999

TS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gthhpnkigy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pengpengdd.cyou/Article/details/gtvhnqfusl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gtyzovkrpf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yongpay.top/Article/details/gtxpeoktbo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.316326.xyz/Article/details/gtlkvjyyzh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtffuffnfo.html

N. 数据结构与算法
来源：http://dali.yonumen.top/Article/details/gtgufhheuj.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtqiyjvrhe.html

[N01] 二分查找（有序数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnrchdpq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtbcquosme.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cheryme.top/Article/details/gtsjfcxusz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gtcdsmvvyw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gtfkoqmgfw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtnqcfwxnz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtitpjflnx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.c1oappe.top/Article/details/gthhcrvpuk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtpcqpjiok.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdbaygaa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.smart0.xyz/Article/details/gtbcwvufua.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.quarkkingdee.top/Article/details/gtezuzwxgx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gtckqopbic.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtpqpavkfc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ydzc1.top/Article/details/gtcarcnfpy.html

Go:   slices.Sort(arr)
来源：http://dali.snrcjt.cn/Article/details/gtcuvjtcbt.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gtgorjdbau.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xinyue.icu/Article/details/gtayigrbgt.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiviuybzz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ivvv.top/Article/details/gtclpzhiwa.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jqgufenzy.top/Article/details/gtoiflusjs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gtazwkbflf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gtmnwwjevo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.0kj1m.cn/Article/details/gtkkbsievo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shzxlz.cn/Article/details/gtozhwxqsq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jianghu66.top/Article/details/gtrdmhqynw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.fengsongda.top/Article/details/gtlvzgaaph.html

[N04] 斐波那契数列
来源：http://dali.mhx1999.top/Article/details/gtohketdfc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yueranfly.top/Article/details/gtiopkzhyp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhixingplan.top/Article/details/gteiotrlpz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtabhbkokr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gttognbwfp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gtnmzowmlc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqyuexbkn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cucudq.cn/Article/details/gthhxnkzkx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtstrlsibt.html

[N05] 最大公约数
来源：http://dali.yanxiufei.cn/Article/details/gtegvbymly.html

Py:   math.gcd(a, b)
来源：http://dali.redwolf501.top/Article/details/gtgcokaagh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtclzigrrg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtbhqwmknr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guowangkeji.top/Article/details/gtgjfnmeeq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yueranfly.top/Article/details/gtkylwjzna.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sufxvd.cn/Article/details/gtuwqmfwos.html

Ruby: a.gcd(b)
来源：http://dali.cheryme.top/Article/details/gtgqjkyeiz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenzaomai.com/Article/details/gthbnrebie.html

[N06] 判断回文字符串
来源：http://dali.daria6918.cn/Article/details/gtyrtnfwex.html

Py:   s == s[::-1]
来源：http://dali.sxryk.cn/Article/details/gtxhyztuki.html

PHP:  $s === strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtopqjrxwi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gthaxcbehf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtptyefcys.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hfpthk.cn/Article/details/gtrznigfrx.html

Go:   // 双指针从两端比较
来源：http://dali.jlsjyb.cn/Article/details/gtvxsohkja.html

Ruby: s == s.reverse
来源：http://dali.zycfv.cn/Article/details/gtqcislwll.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gogol.net.cn/Article/details/gtdxpchvyz.html

[N07] 两数之和（返回下标）
来源：http://dali.cashguo.top/Article/details/gtidztuiuo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xuanzx.com/Article/details/gtbhlbnajb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shuidangran.top/Article/details/gtyguqohqt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.9152youxi.cn/Article/details/gtaocllbij.html

TS:   // 手写 Map<string, number>
来源：http://dali.jlsjyb.cn/Article/details/gtgjcasxdp.html

Java: // 手写 HashMap
来源：http://dali.birdmap.top/Article/details/gtqnteskch.html

Go:   // 手写 map[int]int
来源：http://dali.chenlongwang.top/Article/details/gtbzkxihjj.html

Ruby: // 手写 Hash
来源：http://dali.cashguo.top/Article/details/gtzdxtuizz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj202588.top/Article/details/gtxccxoniu.html

[N08] 生成全排列
来源：http://dali.svipenyu.cn/Article/details/gtilfnukdm.html

Py:   itertools.permutations(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtjfsacfqk.html

PHP:  // 手写递归交换
来源：http://dali.jyoumei.cn/Article/details/gtxtjbwiqc.html

JS:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtegnaywsz.html

TS:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtrvfgpsbc.html

Java: // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtdbxbbiug.html

Go:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtzlcpzrng.html

Ruby: arr.permutation.to_a
来源：http://dali.chenlongwang.top/Article/details/gtzknsuasi.html

C#:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtforscmwe.html

[N09] 栈与队列
来源：http://dali.hysaishi.cn/Article/details/gtldvdwvds.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.pycfn.com/Article/details/gtokjyyzpl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtycokhixq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gtsphtvumo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.daxiang520.top/Article/details/gtcrvgudzy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuxming.cn/Article/details/gttxjrzujs.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.vqdsnc.cn/Article/details/gtxmxjhgls.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtxeczaqiz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gtwaqxhrhs.html

[N10] 链表节点定义
来源：http://dali.yj20258.top/Article/details/gtmszkivty.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shzxlz.cn/Article/details/gtvvclghir.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sxryk.cn/Article/details/gtceclecjx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.meibo888.top/Article/details/gtckwtmlpq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.havefunace.top/Article/details/gtmetyvlme.html

Java: class Node { int v; Node next; }
来源：http://dali.ehwqpu.com/Article/details/gtrwtxtrld.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.vqdsnc.cn/Article/details/gteswduycs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhongyouzk.top/Article/details/gtlahbiwub.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yueranfly.top/Article/details/gtzpnuluqb.html

[N11] 二叉树中序遍历
来源：http://dali.yj202588.top/Article/details/gtyxwpnozz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj20258.top/Article/details/gtyftmcxab.html

PHP:  // 手写递归函数
来源：http://dali.9152youxi.cn/Article/details/gtszqnlwsm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnqzz.top/Article/details/gtqtirajau.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ybcxt.top/Article/details/gtvbtjuslj.html

Java: // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdcwtxbx.html

Go:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gtuhhsvlye.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.birdmap.top/Article/details/gtzpdfcpcp.html

C#:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtnqrrjuag.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.birdmap.top/Article/details/gtpnlggmbd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.snrcjt.cn/Article/details/gtzclyfpng.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cashguo.top/Article/details/gtyouydjeu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gtkezevlmj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gtbibylbdr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gtmbwpyjef.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guannengcc.top/Article/details/gtjuzfivjv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvehrdizz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gtqyhduemr.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtealciskw.html

O. 并发与异步
来源：http://dali.xuetiantiany.cn/Article/details/gtypasrgda.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtagduohzg.html

[O01] 启动一个线程
来源：http://dali.yongpay.top/Article/details/gtzdmlpjds.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenjidiqi.icu/Article/details/gtryrrgsui.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.fzhhl.top/Article/details/gtbglgwxzg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xinyue.icu/Article/details/gtgkvryxdf.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gtegpauxnu.html

Java: new Thread(() -> f()).start()
来源：http://dali.mhx1999.top/Article/details/gtazidsozb.html

Go:   go f()
来源：http://dali.zhiwuduotai.top/Article/details/gthteancyo.html

Ruby: Thread.new { f }
来源：http://dali.shuidangran.top/Article/details/gtejczwiqy.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258.top/Article/details/gtlizjsdoi.html

[O02] 使用线程池
来源：http://dali.chenzaomai.com/Article/details/gtwzuhiode.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jlsjyb.cn/Article/details/gtgvhippvi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangshuangyany.cn/Article/details/gtgkxxouhu.html

JS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gtofsxrnjq.html

TS:   // worker_threads 线程池
来源：http://dali.sxryk.cn/Article/details/gtwizeqabf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gtbtnsrvxr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cashguo.top/Article/details/gtddmaleqp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.birdmap.top/Article/details/gtqouchhiw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.wangshuangyany.cn/Article/details/gtvmubcogh.html

[O03] 加锁保护共享数据
来源：http://dali.shangyingyoupin.top/Article/details/gtiluvutlr.html

Py:   with lock: shared += 1
来源：http://dali.yuanzhike.top/Article/details/gtmmmmoumr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jlsjyb.cn/Article/details/gtbtyepclh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhengqikj.top/Article/details/gtndavdmwt.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gtbmmylfgu.html

Java: synchronized (this) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gtmbavyrmr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sxryk.cn/Article/details/gtehnzyvha.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.svipenyu.cn/Article/details/gtqxynlomi.html

C#:   lock (gate) { shared++; }
来源：http://dali.sufxvd.cn/Article/details/gtsjdqhvhm.html

[O04] 定义异步函数并等待
来源：http://dali.fengsongda.top/Article/details/gtkcszunqt.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtuhinfs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sysykeji.top/Article/details/gtvwwfezyt.html

JS:   async function f() { await g(); }
来源：http://dali.mhx1999.top/Article/details/gtfozmtqqf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tanke756.top/Article/details/gtdbioncod.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fzhhl.top/Article/details/gtimkdumrx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258.top/Article/details/gtazfbivqu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tian-w.cn/Article/details/gtxdtyyrly.html

C#:   async Task F() { await G(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtszfguasd.html

[O05] 并发执行并等待全部完成
来源：http://dali.cashguo.top/Article/details/gtiepdzqsw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtbzdonagy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj20258.top/Article/details/gtvfexfigv.html

JS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gtzeimuulf.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gtkynxusfr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.fzhhl.top/Article/details/gtzmpemkzs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yuxming.cn/Article/details/gtwhvskjrr.html

Ruby: threads.map(&:join)
来源：http://dali.yuanzhike.top/Article/details/gtbwypehmg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guannengcc.top/Article/details/gtbdkbzudb.html

[O06] 使用进程池
来源：http://dali.cheryme.top/Article/details/gtdvhqkshr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.quarkkingdee.top/Article/details/gtxxtolntl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenzaomai.com/Article/details/gtdazlovrw.html

JS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gtkfjneytv.html

TS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gtzqutenez.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tian-w.cn/Article/details/gtxbxkjykg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.svipenyu.cn/Article/details/gtaknpltuq.html

Ruby: // fork 块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgotmxapd.html

C#:   Parallel.For
来源：http://dali.meibo888.top/Article/details/gtmkznalcg.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gttktlahgp.html

P. 常用工具函数
来源：http://dali.zhiwuduotai.top/Article/details/gtcwqeyzbd.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtvdcwqxvy.html

[P01] 生成 UUID
来源：http://dali.c1oappe.top/Article/details/gtnyupxpzo.html

Py:   str(uuid.uuid4())
来源：http://dali.fengsongda.top/Article/details/gtrjnhmfdq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cdnleiting.top/Article/details/gteckwkjnw.html

JS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gtodqdwddr.html

TS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gtuogtqdqt.html

Java: UUID.randomUUID().toString()
来源：http://dali.gotoacloud.top/Article/details/gtpfsatgya.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tian-w.cn/Article/details/gtjdqarcmt.html

Ruby: SecureRandom.uuid
来源：http://dali.yongpay.top/Article/details/gtpctpnact.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xinyue.icu/Article/details/gtsgpfsnzb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jlsjyb.cn/Article/details/gtifaavdll.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cqqwz.cn/Article/details/gtfoeyxqiq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jyoumei.cn/Article/details/gtatumyiry.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zdqjudy.top/Article/details/gtzaizqzvu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.havefunace.top/Article/details/gtauzodfnv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycmrknbp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jianghu66.top/Article/details/gtneyxfgjl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtxsytvnpr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hysaishi.cn/Article/details/gtjydxmppo.html

[P03] 生成短随机字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpsaovomn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yuxming.cn/Article/details/gtjqetbzpn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nanxinkj.top/Article/details/gtxoxzxubt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gtkprwhqyj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gtigancxva.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daria6918.cn/Article/details/gtsnrfeauz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ivvv.top/Article/details/gtnkahyxxn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shangyingyoupin.top/Article/details/gtgwjzgivm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhoulong.xyz/Article/details/gtnqjuaehe.html

[P04] 求长度
来源：http://dali.nwbrower.top/Article/details/gtppfiaped.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hysaishi.cn/Article/details/gtqylyhgmc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtltcsbttz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtqroxaxsi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhengqikj.top/Article/details/gtintltigi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.redwolf501.top/Article/details/gtffodgsaa.html

Go:   len(arr);  len(m)
来源：http://dali.sufxvd.cn/Article/details/gtdtnlvlea.html

Ruby: x.length;  x.size
来源：http://dali.zhengqikj.top/Article/details/gtdgawbgot.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhengqikj.top/Article/details/gtwsvzoame.html

[P05] 判断两个对象内容是否相等
来源：http://dali.svipenyu.cn/Article/details/gtzwnmglqx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jianghu66.top/Article/details/gtitfismkw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.wangshuangyany.cn/Article/details/gtwzxrgtgu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.snrcjt.cn/Article/details/gtsibdorcy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gtpxhbppbr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aizwys.cn/Article/details/gtfxfkmims.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtehweqqqd.html

Ruby: a == b
来源：http://dali.tianlin.xyz/Article/details/gtsnyelqts.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shangyingyoupin.top/Article/details/gtjfuemprr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jiagoushi.top/Article/details/gtspuszahw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinghuilouyu.cn/Article/details/gtjeqjkzes.html

PHP:  if (empty($x)) {}
来源：http://dali.9152youxi.cn/Article/details/gttzmzbdfh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.c1oappe.top/Article/details/gtanzjdpos.html

TS:   if (x == null) {}
来源：http://dali.c1oappe.top/Article/details/gtswljyxyb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gtbeqkfzaw.html

Go:   if x == nil {}
来源：http://dali.ydzc1.top/Article/details/gtqfsgfsft.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.kuanghao11.cn/Article/details/gtafaodjsx.html

C#:   if (x is null) {}
来源：http://dali.ivvv.top/Article/details/gtwguiybqe.html

[P07] 防抖与节流
来源：http://dali.tianlin.xyz/Article/details/gtsrravriu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gotoacloud.top/Article/details/gtrpwoyaxv.html

PHP:  // 手写时间戳比较
来源：http://dali.zhiwuduotai.top/Article/details/gtyhfsbmtg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zdqjudy.top/Article/details/gtpvcyxstr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gtmqqhtnfm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yonumen.top/Article/details/gtxbgnlzum.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpoyhqimm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gzhubu.top/Article/details/gtntylzzdc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuetiantiany.cn/Article/details/gtybcttzxv.html

[P08] 处理浮点精度问题
来源：http://dali.pengpengdd.cyou/Article/details/gtorgjkole.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tian-w.cn/Article/details/gtwiuszose.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dashuyun.cn/Article/details/gteohzfzfv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shangyingyoupin.top/Article/details/gtglrueank.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtxpkqrmfr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ydzc1.top/Article/details/gtxsurbemi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yonumen.top/Article/details/gtoeqdornp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sysykeji.top/Article/details/gtvklorxbv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jianghu66.top/Article/details/gteswunnri.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtgbplpnbn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.kuanghao11.cn/Article/details/gtpbkmqzhd.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtkeqxjzrj.html

[Q01] 创建表
来源：http://dali.xziqi.cn/Article/details/gtqnqndgqi.html

CREATE TABLE users (
来源：http://dali.wangdashe.top/Article/details/gtwygilwxb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gtntsuciaz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gtiljbbusf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.mhx1999.top/Article/details/gtbqlgysea.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhoulong.xyz/Article/details/gttizakvpe.html

);
来源：http://dali.yongpay.top/Article/details/gtpweddguf.html

[Q02] 创建带外键的表
来源：http://dali.jqgfzy.top/Article/details/gtjgtmspld.html

CREATE TABLE orders (
来源：http://dali.jinqigufen.top/Article/details/gtatzrtxgf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gtpbxzyhtw.html

user_id INT NOT NULL,
来源：http://dali.pengpengdd.cyou/Article/details/gtixlxkwpu.html

amount DECIMAL(10, 2),
来源：http://dali.ivvv.top/Article/details/gtbzjddpxl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cdnleiting.top/Article/details/gtobkqsrti.html

);
来源：http://dali.aizwys.cn/Article/details/gtlonolefp.html

[Q03] 增加列
来源：http://dali.dianchejie.cn/Article/details/gthnecktdm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nwbrower.top/Article/details/gtfasjoyyk.html

[Q04] 修改列类型
来源：http://dali.zhoulong.xyz/Article/details/gtyglmdqqq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgufenzy.top/Article/details/gtavrviffb.html

[Q05] 重命名列
来源：http://dali.hammf.cn/Article/details/gtjketfbpv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.birdmap.top/Article/details/gtgphgubxs.html

[Q06] 删除列
来源：http://dali.hnxiangtu.top/Article/details/gtsujrqios.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.redwolf501.top/Article/details/gtbezgorjk.html

[Q07] 删除表
来源：http://dali.chenjidiqi.icu/Article/details/gtttjwabyz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hysaishi.cn/Article/details/gtikfsjpyn.html

[Q08] 创建普通索引
来源：http://dali.sufxvd.cn/Article/details/gtiylfohbi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.bjfxy.top/Article/details/gtddmhmghs.html

[Q09] 创建唯一索引
来源：http://dali.daxiang520.top/Article/details/gttxjaqfal.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gttlaayhtb.html

[Q10] 插入单行
来源：http://dali.hongshengwenyu.top/Article/details/gttiuadvss.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqghcemjz.html

[Q11] 一次插入多行
来源：http://dali.9152youxi.cn/Article/details/gtmjqlvldl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yvedp.cn/Article/details/gtwmkbcjec.html

[Q12] 插入后取自增 ID
来源：http://dali.hnxiangtu.top/Article/details/gtymkxgldi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nwbrower.top/Article/details/gtbfzlawhc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.iojbl.cn/Article/details/gtvtyleodp.html

[Q13] 忽略重复插入
来源：http://dali.redwolf501.top/Article/details/gtbttdywbt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cqqwz.cn/Article/details/gtjvpydixh.html

[Q14] 存在则更新（upsert）
来源：http://dali.daxiang520.top/Article/details/gtuehsvruq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.mhx1999.top/Article/details/gtvawdqwpr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cucudq.cn/Article/details/gtwldjygyt.html

[Q15] 查询全部
来源：http://dali.snrcjt.cn/Article/details/gtzxisvpsy.html

SELECT * FROM users;
来源：http://dali.cucudq.cn/Article/details/gtdtnutqyh.html

[Q16] 查询指定列
来源：http://dali.mhx1999.top/Article/details/gtvafjlkxs.html

SELECT id, name FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtwzodecot.html

[Q17] 条件查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoedzkxrb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shzxlz.cn/Article/details/gtkpjuvrex.html

[Q18] 模糊匹配
来源：http://dali.iojbl.cn/Article/details/gtvscvlvze.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xuanzx.com/Article/details/gtfdnhrzmt.html

[Q19] 范围查询
来源：http://dali.jinqigufen.top/Article/details/gtygcoaixu.html


<!-- 参考信息 -->