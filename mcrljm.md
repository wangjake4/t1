代发 wailian999

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gt2lcyhucbs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gt2nvtrcxji.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nrdvuoag.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2npuprldg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2kbntkbtm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.snrcjt.cn/Article/details/gt2ogteoglw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgufenzy.top/Article/details/gt2clcvcyvw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yanxiufei.cn/Article/details/gt2vjvhrkxi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qptyodgu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gt2njihjwsm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxuanxn.top/Article/details/gt2efwqnnnd.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2iibbifym.html

Ruby: arr.sort
来源：http://dali.jinqigfzy.top/Article/details/gt2ologolfe.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zdqjudy.top/Article/details/gt2limucmcd.html

[N03] 快速排序（分治示例）
来源：http://dali.cheryme.top/Article/details/gt2dhinqypk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ydzc1.top/Article/details/gt2yxoewyco.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hnqzz.top/Article/details/gt2ijgvmicb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gt2wdwtuyoi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gt2tibwypvx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhengqikj.top/Article/details/gt2nnmtpcbe.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nanxinkj.top/Article/details/gt2ygmdtnmk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.c1oappe.top/Article/details/gt2szdjiyal.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhiwuduotai.top/Article/details/gt2abcbqpjh.html

[N04] 斐波那契数列
来源：http://dali.dashuyun.cn/Article/details/gt2gubxdazh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.haohaochexian.top/Article/details/gt2ltycdcld.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gt2gosbwdpz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gt2usspkhsi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gt2wiveugyc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hysaishi.cn/Article/details/gt2rtyjmqkg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gjizzfac.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gt2tnvuyyws.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gt2jqxzdxwi.html

[N05] 最大公约数
来源：http://dali.vqdsnc.cn/Article/details/gt2pifgcdap.html

Py:   math.gcd(a, b)
来源：http://dali.yueranfly.top/Article/details/gt2yordqcaz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tanke756.top/Article/details/gt2uxzyupjf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gt2lihnsqve.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gt2bmqngryg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ybcxt.top/Article/details/gt2cqradian.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenlongwang.top/Article/details/gt2pmjqpbgm.html

Ruby: a.gcd(b)
来源：http://dali.xinyue.icu/Article/details/gt2bulpzicl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yonumen.top/Article/details/gt2rniosacj.html

[N06] 判断回文字符串
来源：http://dali.yvedp.cn/Article/details/gt2msrieudz.html

Py:   s == s[::-1]
来源：http://dali.fengsongda.top/Article/details/gt2taspxzib.html

PHP:  $s === strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2tbzohevh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2vgevscfg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2aizakygn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.feifeiyinyue.top/Article/details/gt2qzxscdni.html

Go:   // 双指针从两端比较
来源：http://dali.jlsjyb.cn/Article/details/gt2msdrykls.html

Ruby: s == s.reverse
来源：http://dali.fzhhl.top/Article/details/gt2tqknytxt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gt2ypnllldl.html

[N07] 两数之和（返回下标）
来源：http://dali.chenlongwang.top/Article/details/gt2csacagif.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wzabqjuk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yuxming.cn/Article/details/gt2ywmeuoin.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnqzz.top/Article/details/gt2mlsmffwm.html

TS:   // 手写 Map<string, number>
来源：http://dali.hywenlv.cn/Article/details/gt2fvmsbadp.html

Java: // 手写 HashMap
来源：http://dali.sxryk.cn/Article/details/gt2ogsxbwtg.html

Go:   // 手写 map[int]int
来源：http://dali.shzxlz.cn/Article/details/gt2jtzvgbnv.html

Ruby: // 手写 Hash
来源：http://dali.gogol.net.cn/Article/details/gt2iwwkpqmj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xinyue.icu/Article/details/gt2leyuqcbx.html

[N08] 生成全排列
来源：http://dali.yueranfly.top/Article/details/gt2svllfopn.html

Py:   itertools.permutations(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2wvdkrrby.html

PHP:  // 手写递归交换
来源：http://dali.tian-w.cn/Article/details/gt2icysvkcd.html

JS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gt2nixrosyk.html

TS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2xapgjnlh.html

Java: // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2leotsiom.html

Go:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gt2sapbqxau.html

Ruby: arr.permutation.to_a
来源：http://dali.gogol.net.cn/Article/details/gt2nayrvzna.html

C#:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2onldbxuo.html

[N09] 栈与队列
来源：http://dali.haohaochexian.top/Article/details/gt2sctksplf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.dashuyun.cn/Article/details/gt2ltoaszns.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gt2fnpsexcs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gt2qzjloxyt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhixingplan.top/Article/details/gt2iankdxhg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yvedp.cn/Article/details/gt2etsbcnoe.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fengsongda.top/Article/details/gt2tecaftwm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gt2iyrmemxn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shzxlz.cn/Article/details/gt2qekoypcs.html

[N10] 链表节点定义
来源：http://dali.yj202588.top/Article/details/gt2uzrqrhbr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.0kj1m.cn/Article/details/gt2lyxngazv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ivvv.top/Article/details/gt2ildfitos.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ivvv.top/Article/details/gt2qoegdoux.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hnqzz.top/Article/details/gt2zxcmwchd.html

Java: class Node { int v; Node next; }
来源：http://dali.cdnleiting.top/Article/details/gt2pvxywmkh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yangfankeji.com/Article/details/gt2sxhqcnel.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guannengcc.top/Article/details/gt2bgkurwlm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uknqgyhg.html

[N11] 二叉树中序遍历
来源：http://dali.sxryk.cn/Article/details/gt2mhgzunsl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2gurpvouk.html

PHP:  // 手写递归函数
来源：http://dali.yangfankeji.com/Article/details/gt2qrhlchvq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gt2yzgqovir.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuanzx.com/Article/details/gt2ycyejopy.html

Java: // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gt2dqmdrkiv.html

Go:   // 手写递归
来源：http://dali.andypj.xyz/Article/details/gt2ivuxgsad.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cucudq.cn/Article/details/gt2qrtvezvv.html

C#:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gt2bpmfevqb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhoulong.xyz/Article/details/gt2bxxqffvu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cheryme.top/Article/details/gt2rwrshbbs.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.redwolf501.top/Article/details/gt2xwncdwsf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gt2yvdwscog.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hysaishi.cn/Article/details/gt2olxzhlti.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2byfcumgw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigfzy.top/Article/details/gt2zokuizkv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kzcmjcev.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gt2vyvmgofp.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2oxfuzvxj.html

O. 并发与异步
来源：http://dali.yj20258888.top/Article/details/gt2atvxomoa.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2unimkibm.html

[O01] 启动一个线程
来源：http://dali.xinyue.icu/Article/details/gt2wxqzzgga.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.kuanghao11.cn/Article/details/gt2wovuntfe.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yueranfly.top/Article/details/gt2xkidrqjh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oqpcfcyb.html

TS:   // 同 JS
来源：http://dali.yuanzhike.top/Article/details/gt2xnxlzcjm.html

Java: new Thread(() -> f()).start()
来源：http://dali.316326.xyz/Article/details/gt2uimrvpog.html

Go:   go f()
来源：http://dali.kuanghao11.cn/Article/details/gt2pfxgxwiy.html

Ruby: Thread.new { f }
来源：http://dali.zhoulong.xyz/Article/details/gt2nrhonfko.html

C#:   Task.Run(() => F());
来源：http://dali.c1oappe.top/Article/details/gt2dzwnnrjf.html

[O02] 使用线程池
来源：http://dali.xylfe.cn/Article/details/gt2bmknyzip.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.bjfxy.top/Article/details/gt2ipcrlvdw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj202588.top/Article/details/gt2rzimecwo.html

JS:   // worker_threads 线程池
来源：http://dali.gotoacloud.top/Article/details/gt2aosnkmjf.html

TS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vefsqdty.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tianlin.xyz/Article/details/gt2xhhsyyek.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.pengpengdd.cyou/Article/details/gt2sptiedum.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hysaishi.cn/Article/details/gt2petowajh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guowangkeji.top/Article/details/gt2rczpkcut.html

[O03] 加锁保护共享数据
来源：http://dali.svipenyu.cn/Article/details/gt2vaunzkqq.html

Py:   with lock: shared += 1
来源：http://dali.yangfankeji.com/Article/details/gt2pzlvvnyl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jzgsbrwj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dianchejie.cn/Article/details/gt2ucsxwhfc.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gt2hqlqlvrr.html

Java: synchronized (this) { shared++; }
来源：http://dali.vqdsnc.cn/Article/details/gt2edzunlst.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yueranfly.top/Article/details/gt2mxxiiioo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ybcxt.top/Article/details/gt2mckkrlta.html

C#:   lock (gate) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gt2nugmdmph.html

[O04] 定义异步函数并等待
来源：http://dali.hammf.cn/Article/details/gt2lvcpvngy.html

Py:   async def f():⏎    await g()
来源：http://dali.zhoulong.xyz/Article/details/gt2vpojcwwp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqoozxv.html

JS:   async function f() { await g(); }
来源：http://dali.daxiang520.top/Article/details/gt2svwqrprm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nwbrower.top/Article/details/gt2hnkitlbt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuxming.cn/Article/details/gt2oqzddfjc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gzhubu.top/Article/details/gt2nybucacp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jianghu66.top/Article/details/gt2ixazpjxq.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpdvwgq.html

[O05] 并发执行并等待全部完成
来源：http://dali.sufxvd.cn/Article/details/gt2zctrgcwy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnqzz.top/Article/details/gt2rxwpnkka.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fengsongda.top/Article/details/gt2pylyrzqt.html

JS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zlcaudbx.html

TS:   await Promise.all(tasks)
来源：http://dali.tian-w.cn/Article/details/gt2mjabyhbk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sxryk.cn/Article/details/gt2lpxzuigl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wxpulhzv.html

Ruby: threads.map(&:join)
来源：http://dali.tian-w.cn/Article/details/gt2jgtzvgzn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shuidangran.top/Article/details/gt2jaygtnnn.html

[O06] 使用进程池
来源：http://dali.hnxiangtu.top/Article/details/gt2dxyvhbpm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigufen.top/Article/details/gt2foixxnzo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daxiang520.top/Article/details/gt2jzryzzbk.html

JS:   // child_process / cluster 模块
来源：http://dali.hfpthk.cn/Article/details/gt2gysdmzil.html

TS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gt2kwyqaqia.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cucudq.cn/Article/details/gt2morfghew.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xuanzx.com/Article/details/gt2wyfwfbhj.html

Ruby: // fork 块
来源：http://dali.cdnleiting.top/Article/details/gt2xurewmmv.html

C#:   Parallel.For
来源：http://dali.xylfe.cn/Article/details/gt2zrgwxxup.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2iymfeola.html

P. 常用工具函数
来源：http://dali.yongpay.top/Article/details/gt2puvpifaa.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2pbvifsyd.html

[P01] 生成 UUID
来源：http://dali.yueranfly.top/Article/details/gt2iaswffhr.html

Py:   str(uuid.uuid4())
来源：http://dali.jianghu66.top/Article/details/gt2yofjcrut.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jqgufenzy.top/Article/details/gt2osmnzvdx.html

JS:   crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ukoqkcxo.html

TS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gt2cknnxybo.html

Java: UUID.randomUUID().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rhohbmzq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.vqdsnc.cn/Article/details/gt2fkvylbyq.html

Ruby: SecureRandom.uuid
来源：http://dali.sweek.top/Article/details/gt2qwpgznej.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aizwys.cn/Article/details/gt2imshybdy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xuetiantiany.cn/Article/details/gt2uhjagiur.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yueranfly.top/Article/details/gt2xlyitlzd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2yaylsptm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.andypj.xyz/Article/details/gt2btygdmnj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yhyifhxi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daria6918.cn/Article/details/gt2fvrplvez.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.redwolf501.top/Article/details/gt2iasdxeen.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cucudq.cn/Article/details/gt2ncwbnmrg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gogol.net.cn/Article/details/gt2dzalxijk.html

[P03] 生成短随机字符串
来源：http://dali.c1oappe.top/Article/details/gt2xxwwilhd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xinyue.icu/Article/details/gt2sqwffyhu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj20258888.top/Article/details/gt2gdfwbyje.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.c1oappe.top/Article/details/gt2sghnvwrj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hfpthk.cn/Article/details/gt2ypnmhmzq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hysaishi.cn/Article/details/gt2kslqycet.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jianghu66.top/Article/details/gt2crihcecp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenlongwang.top/Article/details/gt2jfvhkdyg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj202588.top/Article/details/gt2zejmahev.html

[P04] 求长度
来源：http://dali.shuidangran.top/Article/details/gt2pkdhhblr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.haohaochexian.top/Article/details/gt2hwbsmdij.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gt2yvgcdgfw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.vqdsnc.cn/Article/details/gt2jndzmkzw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gt2bybldtsi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guowangkeji.top/Article/details/gt2fimdgghx.html

Go:   len(arr);  len(m)
来源：http://dali.ehwqpu.com/Article/details/gt2rgpxqjzv.html

Ruby: x.length;  x.size
来源：http://dali.wangdashe.top/Article/details/gt2xxresqbg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fengsongda.top/Article/details/gt2jzlyorht.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj20258.top/Article/details/gt2fzbdlxns.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guowangkeji.top/Article/details/gt2pomlfjis.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yuxming.cn/Article/details/gt2aewqhcyj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.quarkkingdee.top/Article/details/gt2uwhcplmx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jzniiova.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuanzx.com/Article/details/gt2ffvzlabl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gogol.net.cn/Article/details/gt2dmppmmte.html

Ruby: a == b
来源：http://dali.zhixingplan.top/Article/details/gt2fayejvvu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenzaomai.com/Article/details/gt2yvoyozwq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gaohongyu789.top/Article/details/gt2woptoqke.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cheryme.top/Article/details/gt2brygrmdh.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fohcfpfd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.pengpengdd.cyou/Article/details/gt2vehgmxcj.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fgvhuixy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nanxinkj.top/Article/details/gt2vfixgzhb.html

Go:   if x == nil {}
来源：http://dali.yangfankeji.com/Article/details/gt2tqbsazrg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qokdhfef.html

C#:   if (x is null) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2gaooityx.html

[P07] 防抖与节流
来源：http://dali.xziqi.cn/Article/details/gt2eocymkvr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xuanzx.com/Article/details/gt2gzyplnes.html

PHP:  // 手写时间戳比较
来源：http://dali.cdnleiting.top/Article/details/gt2ivpprbwb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gt2legnxvgv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gt2clwjokex.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aibaodan.cn/Article/details/gt2dmyxksha.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xuetiantiany.cn/Article/details/gt2pdrhbrgg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yanxiufei.cn/Article/details/gt2sfpptdtb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xinyue.icu/Article/details/gt2gmhwxcxo.html

[P08] 处理浮点精度问题
来源：http://dali.gotoacloud.top/Article/details/gt2rzisxxug.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhengqikj.top/Article/details/gt2uggivzvo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bpnggoia.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fzhhl.top/Article/details/gt2ncgliezk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgufenzy.top/Article/details/gt2wnyggexl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hongshengwenyu.top/Article/details/gt2qhsbfqbo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xuanzx.com/Article/details/gt2cmetrwrb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cheryme.top/Article/details/gt2wfrtapxd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.smart0.xyz/Article/details/gt2itumhfbj.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2qkgzhygf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yueranfly.top/Article/details/gt2ojlfzjnz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2dyjmeiit.html

[Q01] 创建表
来源：http://dali.hongshengwenyu.top/Article/details/gt2uajpcile.html

CREATE TABLE users (
来源：http://dali.sweek.top/Article/details/gt2qqafnsax.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuetiantiany.cn/Article/details/gt2hrcgrqrs.html

name VARCHAR(50) NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gt2qlmyzxwb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tanke756.top/Article/details/gt2afqsofgk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.smart0.xyz/Article/details/gt2rltjttnj.html

);
来源：http://dali.zdqjudy.top/Article/details/gt2annynint.html

[Q02] 创建带外键的表
来源：http://dali.jyoumei.cn/Article/details/gt2ljgjngcy.html

CREATE TABLE orders (
来源：http://dali.yongpay.top/Article/details/gt2idcbrlup.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gt2ebruroie.html

user_id INT NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gt2qtgnmpzh.html

amount DECIMAL(10, 2),
来源：http://dali.nanxuanxn.top/Article/details/gt2ztqwtgln.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xylfe.cn/Article/details/gt2xpswcrfi.html

);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2buhuxkzv.html

[Q03] 增加列
来源：http://dali.tian-w.cn/Article/details/gt2gmcnyjrg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2myueqylz.html

[Q04] 修改列类型
来源：http://dali.0kj1m.cn/Article/details/gt2juwcwepz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.iojbl.cn/Article/details/gt2xpwsfscr.html

[Q05] 重命名列
来源：http://dali.yueranfly.top/Article/details/gt2vfdsisce.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ppjwa.cn/Article/details/gt2dmrzzpny.html

[Q06] 删除列
来源：http://dali.yvedp.cn/Article/details/gt2uauxvhdm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.snrcjt.cn/Article/details/gt2kebzamja.html

[Q07] 删除表
来源：http://dali.zhengqikj.top/Article/details/gt2gabminav.html

DROP TABLE IF EXISTS orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2yvupynzj.html

[Q08] 创建普通索引
来源：http://dali.yanxiufei.cn/Article/details/gt2igxgooqv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gt2qjaxgirb.html

[Q09] 创建唯一索引
来源：http://dali.jinqigufen.top/Article/details/gt2zzfiigno.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gt2wwnrottu.html

[Q10] 插入单行
来源：http://dali.ehwqpu.com/Article/details/gt2ryczsblo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuanzhike.top/Article/details/gt2cjvvqgrw.html

[Q11] 一次插入多行
来源：http://dali.yueranfly.top/Article/details/gt2fexuizzd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuanzhike.top/Article/details/gt2nlavwirl.html

[Q12] 插入后取自增 ID
来源：http://dali.daxiang520.top/Article/details/gt2egxhxvhz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ppjwa.cn/Article/details/gt2doqxzllj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.quarkkingdee.top/Article/details/gt2svdevgus.html

[Q13] 忽略重复插入
来源：http://dali.zhixingplan.top/Article/details/gt2xbbpyrvv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gt2iprijajr.html

[Q14] 存在则更新（upsert）
来源：http://dali.yvedp.cn/Article/details/gt2ccdcteuf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.mhx1999.top/Article/details/gt2mazdaghj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yonumen.top/Article/details/gt2xspdoifn.html

[Q15] 查询全部
来源：http://dali.wangshuangyany.cn/Article/details/gt2yllyxnbw.html

SELECT * FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2dbjnzdes.html

[Q16] 查询指定列
来源：http://dali.xuanzx.com/Article/details/gt2yjmgxzgk.html

SELECT id, name FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2qlzaveil.html

[Q17] 条件查询
来源：http://dali.316326.xyz/Article/details/gt2eivndozy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenzaomai.com/Article/details/gt2kxbvzjeq.html

[Q18] 模糊匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2ytlulsey.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenlongwang.top/Article/details/gt2ugjfyelh.html

[Q19] 范围查询
来源：http://dali.vqdsnc.cn/Article/details/gt2fogkvdwb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yueranfly.top/Article/details/gt2qgfkogik.html

[Q20] IN 列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zyzatdis.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yjwknjqy.html

[Q21] 空值判断
来源：http://dali.daxiang520.top/Article/details/gt2ikfehxtz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gt2rbogyfqx.html

[Q22] 排序
来源：http://dali.dianchejie.cn/Article/details/gt2uldrhusy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shangyingyoupin.top/Article/details/gt2uexoldfe.html

[Q23] 分页
来源：http://dali.316326.xyz/Article/details/gt2cyfabzoj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.vqdsnc.cn/Article/details/gt2gqwnaifn.html

[Q24] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zqzusbyy.html

SELECT DISTINCT city FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2fhckudfr.html

[Q25] 只取前 N 条
来源：http://dali.cdnleiting.top/Article/details/gt2pzdvnycr.html


<!-- 参考信息 -->