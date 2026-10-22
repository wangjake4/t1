代发 wailian999

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gtsocxndtg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gtqatuxqnu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gzhubu.top/Article/details/gtsnvouhfz.html

Go:   slices.Sort(arr)
来源：http://dali.sufxvd.cn/Article/details/gtjcxxfhnw.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtvqfuyljn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yueranfly.top/Article/details/gtfhsbtkum.html

[N03] 快速排序（分治示例）
来源：http://dali.daria6918.cn/Article/details/gtxhwmnhte.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xylfe.cn/Article/details/gtyqsciwgn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yonumen.top/Article/details/gtdjgyqgjj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gtedajpdvp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gtftdssmed.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cucudq.cn/Article/details/gtcxuylqor.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hfpthk.cn/Article/details/gttzpumzot.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pycfn.com/Article/details/gtauapvpcm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xinyue.icu/Article/details/gtrsooaqjn.html

[N04] 斐波那契数列
来源：http://dali.cucudq.cn/Article/details/gtczrplbyv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gtnpsfkfzg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gttcjnslxd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gthlauylur.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtrqvikfzs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gthypfwpqv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xylfe.cn/Article/details/gtkgydyjns.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gtlbirsnct.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gteanwlltj.html

[N05] 最大公约数
来源：http://dali.smart0.xyz/Article/details/gtqeiwlhjb.html

Py:   math.gcd(a, b)
来源：http://dali.fengsongda.top/Article/details/gthndspqjy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xylfe.cn/Article/details/gtcyxhqtxz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gtwlbrxrjl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gtgcdynhfu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sufxvd.cn/Article/details/gtjtincbfn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daria6918.cn/Article/details/gtqizhockl.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gteiqvzkxf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.feifeiyinyue.top/Article/details/gtcwtmwcmv.html

[N06] 判断回文字符串
来源：http://dali.yj202588.top/Article/details/gtkkxqmnyc.html

Py:   s == s[::-1]
来源：http://dali.shuidangran.top/Article/details/gtdmkluxvn.html

PHP:  $s === strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gtilcghpok.html

JS:   s === [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gtmcfugxvn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtqkimatdi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xziqi.cn/Article/details/gtoyoopgrs.html

Go:   // 双指针从两端比较
来源：http://dali.tanke756.top/Article/details/gtnlotbwfy.html

Ruby: s == s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gtnupphvec.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tianlin.xyz/Article/details/gtbnbhbaou.html

[N07] 两数之和（返回下标）
来源：http://dali.nwbrower.top/Article/details/gtsecbufke.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yuanzhike.top/Article/details/gtajpryulx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hysaishi.cn/Article/details/gtrpljrrqg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hysaishi.cn/Article/details/gteubzcbve.html

TS:   // 手写 Map<string, number>
来源：http://dali.c1oappe.top/Article/details/gtudcngsgo.html

Java: // 手写 HashMap
来源：http://dali.haohaochexian.top/Article/details/gtmpivucou.html

Go:   // 手写 map[int]int
来源：http://dali.hongshengwenyu.top/Article/details/gtgpcqpchv.html

Ruby: // 手写 Hash
来源：http://dali.hongshengwenyu.top/Article/details/gtfrllbtoc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.316326.xyz/Article/details/gteoredjwn.html

[N08] 生成全排列
来源：http://dali.sweek.top/Article/details/gtkaeupsbl.html

Py:   itertools.permutations(arr)
来源：http://dali.zhixingplan.top/Article/details/gtxgqmniey.html

PHP:  // 手写递归交换
来源：http://dali.gogol.net.cn/Article/details/gtgysnrrgh.html

JS:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtxargcpkc.html

TS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gthmuoggob.html

Java: // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtmvoexrau.html

Go:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtxdtsfewh.html

Ruby: arr.permutation.to_a
来源：http://dali.fengsongda.top/Article/details/gtuukxgpea.html

C#:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtzffjjfaw.html

[N09] 栈与队列
来源：http://dali.xylfe.cn/Article/details/gthhivxrmb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xylfe.cn/Article/details/gtpikqcqit.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtqmzysiwx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sysykeji.top/Article/details/gtbrkebtxf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.kuanghao11.cn/Article/details/gtalgfugpp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhengqikj.top/Article/details/gtsfewkfkm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhiwuduotai.top/Article/details/gtgndqnmvc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tanke756.top/Article/details/gtmgdlhpti.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhoulong.xyz/Article/details/gtiafghrlc.html

[N10] 链表节点定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfaldsns.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daxiang520.top/Article/details/gtivucxxvd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhongyouzk.top/Article/details/gthfvpszpe.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xylfe.cn/Article/details/gtmqrdisck.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sysykeji.top/Article/details/gticqlavbo.html

Java: class Node { int v; Node next; }
来源：http://dali.hnqzz.top/Article/details/gtrfmsfgtz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jqgufenzy.top/Article/details/gtyxqzpclp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.svipenyu.cn/Article/details/gtevgxpfpr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dashuyun.cn/Article/details/gtyurkzacm.html

[N11] 二叉树中序遍历
来源：http://dali.ehwqpu.com/Article/details/gtctrctcqq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tianlin.xyz/Article/details/gtjrbeneme.html

PHP:  // 手写递归函数
来源：http://dali.wangdashe.top/Article/details/gthvuyftjj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhfecxqq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gtdbwqmwzi.html

Java: // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gtictbmcxs.html

Go:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gtasdbgiem.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yueranfly.top/Article/details/gtfigoudlg.html

C#:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gtltxdwhkm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.svipenyu.cn/Article/details/gtgawobafj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xylfe.cn/Article/details/gtfvqbmoar.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj20258888.top/Article/details/gtdpmmwchs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gtzijkybqf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yueranfly.top/Article/details/gtdcubxavx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gtqhcdbxom.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tian-w.cn/Article/details/gtrfexxkrq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhengqikj.top/Article/details/gtdfrzegtb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaaxggamh.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjkboafk.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbhojcnx.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gttheuzhlm.html

[O01] 启动一个线程
来源：http://dali.nwbrower.top/Article/details/gtguceycbe.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zycfv.cn/Article/details/gticrqhzuk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hfpthk.cn/Article/details/gtiyfzuroc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tanke756.top/Article/details/gtfmkhfida.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gtarubtrui.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnxiangtu.top/Article/details/gtrmqobzkf.html

Go:   go f()
来源：http://dali.gogol.net.cn/Article/details/gthiaqrxax.html

Ruby: Thread.new { f }
来源：http://dali.zhixingplan.top/Article/details/gtjslvuuqn.html

C#:   Task.Run(() => F());
来源：http://dali.hnqzz.top/Article/details/gteatmyskc.html

[O02] 使用线程池
来源：http://dali.hywenlv.cn/Article/details/gtnkgmdyzs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.9152youxi.cn/Article/details/gtwvflaqme.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhongyouzk.top/Article/details/gtmnqwligg.html

JS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gttwdwrgcs.html

TS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gtnkpwsjti.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yvedp.cn/Article/details/gtmgtkrzua.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.bjfxy.top/Article/details/gtovtksane.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj202588.top/Article/details/gtcqmvrxnz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.havefunace.top/Article/details/gteztwsmdx.html

[O03] 加锁保护共享数据
来源：http://dali.hongshengwenyu.top/Article/details/gthbjqhnax.html

Py:   with lock: shared += 1
来源：http://dali.cqqwz.cn/Article/details/gtdjqjqnth.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhongyouzk.top/Article/details/gtbtvspybw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozjwnetg.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gtythffskn.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gtaiwjaysk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nanxuanxn.top/Article/details/gthcyrwclc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.bjfxy.top/Article/details/gtmycypimv.html

C#:   lock (gate) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gteiuihwic.html

[O04] 定义异步函数并等待
来源：http://dali.shuidangran.top/Article/details/gtyaoxkqqn.html

Py:   async def f():⏎    await g()
来源：http://dali.fzhhl.top/Article/details/gtomvavjtq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhixingplan.top/Article/details/gtlaeqcmuh.html

JS:   async function f() { await g(); }
来源：http://dali.andypj.xyz/Article/details/gtlmddyove.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.aizwys.cn/Article/details/gtjqahivvr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ybcxt.top/Article/details/gtpmpmvlnp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenzaomai.com/Article/details/gtjuifcexh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hammf.cn/Article/details/gtikuqhoug.html

C#:   async Task F() { await G(); }
来源：http://dali.jiagoushi.top/Article/details/gtoojqpwji.html

[O05] 并发执行并等待全部完成
来源：http://dali.hfpthk.cn/Article/details/gtyqamkxme.html

Py:   asyncio.gather(*tasks)
来源：http://dali.fzhhl.top/Article/details/gtrpscblvt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jiagoushi.top/Article/details/gtmboqpemq.html

JS:   await Promise.all(tasks)
来源：http://dali.xylfe.cn/Article/details/gtaqpinspp.html

TS:   await Promise.all(tasks)
来源：http://dali.cashguo.top/Article/details/gtbxgyuieu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuxming.cn/Article/details/gtpvniwmej.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gaohongyu789.top/Article/details/gtzuxiylej.html

Ruby: threads.map(&:join)
来源：http://dali.tanke756.top/Article/details/gtfppuvvfq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pengpengdd.cyou/Article/details/gtecremweh.html

[O06] 使用进程池
来源：http://dali.shangyingyoupin.top/Article/details/gtcvfrxwnm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenlongwang.top/Article/details/gttszhsziv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcihtqevk.html

JS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gtljhxktwg.html

TS:   // child_process / cluster 模块
来源：http://dali.fzhhl.top/Article/details/gtdtrzcomo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.iojbl.cn/Article/details/gtxcstqpqy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jyoumei.cn/Article/details/gtxztbwmuq.html

Ruby: // fork 块
来源：http://dali.shangyingyoupin.top/Article/details/gtxlsisytx.html

C#:   Parallel.For
来源：http://dali.quarkkingdee.top/Article/details/gtplvclppd.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtyybhzfuz.html

P. 常用工具函数
来源：http://dali.cucudq.cn/Article/details/gtuwoqwvuj.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtfrhklyfy.html

[P01] 生成 UUID
来源：http://dali.meibo888.top/Article/details/gtnqcxaplu.html

Py:   str(uuid.uuid4())
来源：http://dali.wangdashe.top/Article/details/gtgpmaswyo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.0kj1m.cn/Article/details/gtmcvthiyr.html

JS:   crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gtsnmbyjxk.html

TS:   crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gtxtlstbxt.html

Java: UUID.randomUUID().toString()
来源：http://dali.9152youxi.cn/Article/details/gtrhvbzcpa.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinqigfzy.top/Article/details/gtavkrivre.html

Ruby: SecureRandom.uuid
来源：http://dali.ybcxt.top/Article/details/gtkkjfjvdx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.9152youxi.cn/Article/details/gtxfykohbq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnxiangtu.top/Article/details/gtzyowqeqk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.kuanghao11.cn/Article/details/gthkqnxjzo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxinkj.top/Article/details/gtibysxerm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shuidangran.top/Article/details/gtlouggyyd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guannengcc.top/Article/details/gtznuppiqf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtuvjhcomv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.meibo888.top/Article/details/gtbsvlxnqh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yvedp.cn/Article/details/gtpjtkbqif.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tian-w.cn/Article/details/gtoojdvcdf.html

[P03] 生成短随机字符串
来源：http://dali.yangfankeji.com/Article/details/gtgyhbmayo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gogol.net.cn/Article/details/gtjramsxgn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ydzc1.top/Article/details/gtxqketcis.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gtkitufmov.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nwbrower.top/Article/details/gtlvhdeagz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.fengsongda.top/Article/details/gtpmnuuxvq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.316326.xyz/Article/details/gtfegtrufg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxuanxn.top/Article/details/gtkdhrfjgp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.andypj.xyz/Article/details/gtfjofgdmy.html

[P04] 求长度
来源：http://dali.ydzc1.top/Article/details/gtzssnegst.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.pengpengdd.cyou/Article/details/gtopodkmwg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gteitnqdmp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gturbhsyal.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gtprhujyub.html

Java: list.size();  map.size();  s.length()
来源：http://dali.aizwys.cn/Article/details/gtoxijmhcy.html

Go:   len(arr);  len(m)
来源：http://dali.yuxming.cn/Article/details/gtkycaahjq.html

Ruby: x.length;  x.size
来源：http://dali.gogol.net.cn/Article/details/gtlpipdxwp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclukrfks.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cashguo.top/Article/details/gtbyiewuhh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yongpay.top/Article/details/gtohfucqfs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.snrcjt.cn/Article/details/gtxvxvnvhl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jiagoushi.top/Article/details/gtdrjzslrj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gtkgwnxdjm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sysykeji.top/Article/details/gtopjmxzzc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaezlpsbn.html

Ruby: a == b
来源：http://dali.yj202588.top/Article/details/gteebubgnz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhoulong.xyz/Article/details/gtnjhabutx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.guannengcc.top/Article/details/gtwxwxixqx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ybcxt.top/Article/details/gtblbmfnkx.html

PHP:  if (empty($x)) {}
来源：http://dali.ybcxt.top/Article/details/gtogzprpot.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ehwqpu.com/Article/details/gtaxetgvwj.html

TS:   if (x == null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzhoabjb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gtgfgghvet.html

Go:   if x == nil {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzrnpzra.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinqigufen.top/Article/details/gtfbydqyrm.html

C#:   if (x is null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwklutoq.html

[P07] 防抖与节流
来源：http://dali.cqqwz.cn/Article/details/gtvneumxmb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xuetiantiany.cn/Article/details/gttutcyhfg.html

PHP:  // 手写时间戳比较
来源：http://dali.havefunace.top/Article/details/gtzgzzsalm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gtuxpzsqhk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gtsomgxggy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.iojbl.cn/Article/details/gthqmrcjqa.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shzxlz.cn/Article/details/gtjdcjzsaj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.haohaochexian.top/Article/details/gtyjtgfqws.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ivvv.top/Article/details/gtpclekavl.html

[P08] 处理浮点精度问题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflssiksx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.bjfxy.top/Article/details/gtzempdvyt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gzhubu.top/Article/details/gtbfjdqnar.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jiagoushi.top/Article/details/gtgyewvcpm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jlsjyb.cn/Article/details/gtoojsmwal.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cheryme.top/Article/details/gtxsuvhdtc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.0kj1m.cn/Article/details/gtrydqcwxn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xziqi.cn/Article/details/gtpcdemzpn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dashuyun.cn/Article/details/gttddjoaej.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdgusqfy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.mhx1999.top/Article/details/gteggsevau.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtzqvnmzpt.html

[Q01] 创建表
来源：http://dali.zhixingplan.top/Article/details/gtukxpxgtb.html

CREATE TABLE users (
来源：http://dali.shzxlz.cn/Article/details/gtktxizhre.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gthshbbmlc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gtnoqankcd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ybcxt.top/Article/details/gtyeqgkwlv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yuxming.cn/Article/details/gtvcuczowq.html

);
来源：http://dali.zhongyouzk.top/Article/details/gtkwbbckwx.html

[Q02] 创建带外键的表
来源：http://dali.gogol.net.cn/Article/details/gtbdrmlswd.html

CREATE TABLE orders (
来源：http://dali.bjfxy.top/Article/details/gtbxefsgop.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxinkj.top/Article/details/gtlqyhguvs.html

user_id INT NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gtkopwcrqy.html

amount DECIMAL(10, 2),
来源：http://dali.zdqjudy.top/Article/details/gtpbkekkex.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinqigufen.top/Article/details/gtucgbklhz.html

);
来源：http://dali.ehwqpu.com/Article/details/gtcohfbgzs.html

[Q03] 增加列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtgxkjgq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ehwqpu.com/Article/details/gtaldzrqgq.html

[Q04] 修改列类型
来源：http://dali.snrcjt.cn/Article/details/gtwavbjniu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yanxiufei.cn/Article/details/gtsjerkljo.html

[Q05] 重命名列
来源：http://dali.yvedp.cn/Article/details/gtmcwfckbx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jlsjyb.cn/Article/details/gtosbvgime.html

[Q06] 删除列
来源：http://dali.hongshengwenyu.top/Article/details/gtmnsnuxuz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jyoumei.cn/Article/details/gtorczmiec.html

[Q07] 删除表
来源：http://dali.wangdashe.top/Article/details/gtgaoomilj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sweek.top/Article/details/gtqdxyuvek.html

[Q08] 创建普通索引
来源：http://dali.c1oappe.top/Article/details/gtrrawfngg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfciwluks.html

[Q09] 创建唯一索引
来源：http://dali.wangdashe.top/Article/details/gtbdbfemga.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrurgroj.html

[Q10] 插入单行
来源：http://dali.yuxming.cn/Article/details/gtjickavgs.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gtgjwyqwbl.html

[Q11] 一次插入多行
来源：http://dali.pycfn.com/Article/details/gttwbhkjkl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yonumen.top/Article/details/gtwujknngu.html

[Q12] 插入后取自增 ID
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvzadwxh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cucudq.cn/Article/details/gtdxxotmlo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hywenlv.cn/Article/details/gtdswmeqke.html

[Q13] 忽略重复插入
来源：http://dali.yongpay.top/Article/details/gttwwtyvpy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.0kj1m.cn/Article/details/gtlvaommsk.html

[Q14] 存在则更新（upsert）
来源：http://dali.xziqi.cn/Article/details/gtzvlwpkfy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhoulong.xyz/Article/details/gtycftjbzn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xuanzx.com/Article/details/gtmndhpmgd.html

[Q15] 查询全部
来源：http://dali.snrcjt.cn/Article/details/gtuxzihkve.html

SELECT * FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqtjvuaa.html

[Q16] 查询指定列
来源：http://dali.andypj.xyz/Article/details/gtmgykhmeb.html

SELECT id, name FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkolciuqq.html

[Q17] 条件查询
来源：http://dali.c1oappe.top/Article/details/gtzsmvanmh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sysykeji.top/Article/details/gtznvkzsni.html

[Q18] 模糊匹配
来源：http://dali.zhongyouzk.top/Article/details/gttwnygojm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.c1oappe.top/Article/details/gtvnbvllsi.html

[Q19] 范围查询
来源：http://dali.jinqigufen.top/Article/details/gtuxzbxcou.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tian-w.cn/Article/details/gthgqsdhcu.html

[Q20] IN 列表
来源：http://dali.tanke756.top/Article/details/gtfzoggjat.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenzaomai.com/Article/details/gtsttflkkf.html

[Q21] 空值判断
来源：http://dali.hysaishi.cn/Article/details/gtztjmkkwj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.bjfxy.top/Article/details/gtqzpvpety.html

[Q22] 排序
来源：http://dali.jinqigufen.top/Article/details/gtykacarth.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jyoumei.cn/Article/details/gtpbzynorg.html

[Q23] 分页
来源：http://dali.shangyingyoupin.top/Article/details/gtvdjqting.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.9152youxi.cn/Article/details/gtyptqsgkg.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gtxgstchhv.html

SELECT DISTINCT city FROM users;
来源：http://dali.wangdashe.top/Article/details/gtemozrahf.html

[Q25] 只取前 N 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwtxzinn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuxming.cn/Article/details/gtiabfnvji.html

[Q26] 计数
来源：http://dali.316326.xyz/Article/details/gtdzrfpkrf.html

SELECT COUNT(*) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtzoxbkysi.html

[Q27] 条件计数
来源：http://dali.zhoulong.xyz/Article/details/gtjhfqghek.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tanke756.top/Article/details/gthuhkmglh.html

[Q28] 求和与平均
来源：http://dali.yueranfly.top/Article/details/gtgomuujev.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtspfkcqlj.html

[Q29] 最大最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpuvwepfy.html


<!-- 参考信息 -->