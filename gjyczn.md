代发 wailian999

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gt2ycoaffyo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2elzjmxbq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.vqdsnc.cn/Article/details/gt2ncrqebnd.html

Go:   slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gt2runbkayu.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gt2nbtzhast.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.andypj.xyz/Article/details/gt2fwupfrrp.html

[N03] 快速排序（分治示例）
来源：http://dali.andypj.xyz/Article/details/gt2gbsjjpep.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oxdtamkt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.iojbl.cn/Article/details/gt2kypzeeur.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhixingplan.top/Article/details/gt2bcxumgoy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gt2blvnqbsb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gzhubu.top/Article/details/gt2dziccnwi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenjidiqi.icu/Article/details/gt2ujlxirms.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nanxinkj.top/Article/details/gt2btrxnpol.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenzaomai.com/Article/details/gt2gukgkuel.html

[N04] 斐波那契数列
来源：http://dali.ppjwa.cn/Article/details/gt2odljqduz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gt2imkzauue.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hmnqlkeb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gt2whzvnnuw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2mgcfilpj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmiafkmb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sxryk.cn/Article/details/gt2jfkzdpjx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gt2jvtblxvf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2npjkcseb.html

[N05] 最大公约数
来源：http://dali.gaohongyu789.top/Article/details/gt2osrvavwo.html

Py:   math.gcd(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gt2hghbxlhx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.birdmap.top/Article/details/gt2tjvazcyj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gt2pdpywpks.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gt2vnejwwie.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.vqdsnc.cn/Article/details/gt2izhldzwp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuanzx.com/Article/details/gt2sjowzmmm.html

Ruby: a.gcd(b)
来源：http://dali.316326.xyz/Article/details/gt2paltckzg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cdnleiting.top/Article/details/gt2jvvlmsnb.html

[N06] 判断回文字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2eodfoijy.html

Py:   s == s[::-1]
来源：http://dali.yuxming.cn/Article/details/gt2spvsamyx.html

PHP:  $s === strrev($s);
来源：http://dali.yj20258888.top/Article/details/gt2rclixrjz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gt2wjyubjst.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rcwrumhn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jiagoushi.top/Article/details/gt2hnfwuqfj.html

Go:   // 双指针从两端比较
来源：http://dali.xylfe.cn/Article/details/gt2udlgtwkg.html

Ruby: s == s.reverse
来源：http://dali.meibo888.top/Article/details/gt2qxtiwkun.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gt2rcmfbmhl.html

[N07] 两数之和（返回下标）
来源：http://dali.cdnleiting.top/Article/details/gt2eecamrdg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.birdmap.top/Article/details/gt2nnrcmoro.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxuanxn.top/Article/details/gt2htxbdffl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangdashe.top/Article/details/gt2tymkovht.html

TS:   // 手写 Map<string, number>
来源：http://dali.tianlin.xyz/Article/details/gt2bxkzeruj.html

Java: // 手写 HashMap
来源：http://dali.shzxlz.cn/Article/details/gt2bzojervm.html

Go:   // 手写 map[int]int
来源：http://dali.wangdashe.top/Article/details/gt2xhgzwbzd.html

Ruby: // 手写 Hash
来源：http://dali.yj20258.top/Article/details/gt2izmlwgpt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.haohaochexian.top/Article/details/gt2gpqpitpo.html

[N08] 生成全排列
来源：http://dali.nanxinkj.top/Article/details/gt2vzwvsmbi.html

Py:   itertools.permutations(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2onuacriw.html

PHP:  // 手写递归交换
来源：http://dali.daxiang520.top/Article/details/gt2pbzrydjf.html

JS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gt2mvjixysb.html

TS:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gt2hegzkcdy.html

Java: // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gt2tijhecht.html

Go:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gt2rzhwasng.html

Ruby: arr.permutation.to_a
来源：http://dali.daria6918.cn/Article/details/gt2ocoysftt.html

C#:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gt2nxjvopin.html

[N09] 栈与队列
来源：http://dali.daxiang520.top/Article/details/gt2vpnsosoe.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daxiang520.top/Article/details/gt2ojemgykw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sweek.top/Article/details/gt2mxgzrmzx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gt2bcmifvhj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.9152youxi.cn/Article/details/gt2iufgaulh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258888.top/Article/details/gt2yryzaepb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenlongwang.top/Article/details/gt2ykppevth.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gt2mgpwqcul.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cucudq.cn/Article/details/gt2mavuwqsa.html

[N10] 链表节点定义
来源：http://dali.cucudq.cn/Article/details/gt2jqdezqjx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.wangdashe.top/Article/details/gt2ywsyvhtw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dashuyun.cn/Article/details/gt2seemiwdk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hammf.cn/Article/details/gt2eptzqyfm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yuxming.cn/Article/details/gt2apwoeskm.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258.top/Article/details/gt2mfmpatwf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jqgfzy.top/Article/details/gt2xigniznk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hytytpkp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.redwolf501.top/Article/details/gt2yvtiyhvv.html

[N11] 二叉树中序遍历
来源：http://dali.xylfe.cn/Article/details/gt2yfetivsp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aibaodan.cn/Article/details/gt2dtaxgaiu.html

PHP:  // 手写递归函数
来源：http://dali.hysaishi.cn/Article/details/gt2zrhwweig.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gt2jyorxsbz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.havefunace.top/Article/details/gt2fnxwcnck.html

Java: // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gt2xaqrdmyw.html

Go:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gt2aaxgyxva.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yueranfly.top/Article/details/gt2opwmdmiq.html

C#:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gt2zsknbwfm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shuidangran.top/Article/details/gt2tbkxwqnr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenlongwang.top/Article/details/gt2muzlrrch.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xmdyoqcq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gt2oymbblpl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenlongwang.top/Article/details/gt2thsprgno.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zdqjudy.top/Article/details/gt2abdcvizy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.iojbl.cn/Article/details/gt2uqbbzuys.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gt2btvozdjt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gt2yvooaipc.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2rugxnkbc.html

O. 并发与异步
来源：http://dali.hywenlv.cn/Article/details/gt2nzonpkab.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2fevnqwro.html

[O01] 启动一个线程
来源：http://dali.sysykeji.top/Article/details/gt2ifxxvkqf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhoulong.xyz/Article/details/gt2hgoiiyxj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnqzz.top/Article/details/gt2dmepjjnb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gogol.net.cn/Article/details/gt2kzfhnbdl.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gt2yarndjul.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangshuangyany.cn/Article/details/gt2harfxvpo.html

Go:   go f()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mtvemgix.html

Ruby: Thread.new { f }
来源：http://dali.xylfe.cn/Article/details/gt2hfpeqwwe.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258888.top/Article/details/gt2qbtupvzs.html

[O02] 使用线程池
来源：http://dali.sxryk.cn/Article/details/gt2rhimaviw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jlsjyb.cn/Article/details/gt2zlnwjnmj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.smart0.xyz/Article/details/gt2caytdlyc.html

JS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gt2andnmwvs.html

TS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gt2vcgxgngt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mzkqxeel.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuanzhike.top/Article/details/gt2boybcwdt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tanke756.top/Article/details/gt2resgcwkk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.redwolf501.top/Article/details/gt2nggfqdwr.html

[O03] 加锁保护共享数据
来源：http://dali.sweek.top/Article/details/gt2jmzllojt.html

Py:   with lock: shared += 1
来源：http://dali.havefunace.top/Article/details/gt2lvrrarbq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shangyingyoupin.top/Article/details/gt2zhxkqlat.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hfpthk.cn/Article/details/gt2gzgcceom.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gt2whkclxvk.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gt2hehdbxlc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuxming.cn/Article/details/gt2ifcihtho.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tian-w.cn/Article/details/gt2srfjitxc.html

C#:   lock (gate) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gt2xgibhotc.html

[O04] 定义异步函数并等待
来源：http://dali.iojbl.cn/Article/details/gt2jqwbmhzz.html

Py:   async def f():⏎    await g()
来源：http://dali.ppjwa.cn/Article/details/gt2leuibhox.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sufxvd.cn/Article/details/gt2gcvzjzul.html

JS:   async function f() { await g(); }
来源：http://dali.tanke756.top/Article/details/gt2exqojram.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ivvv.top/Article/details/gt2jvwtowmj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangtech.top/Article/details/gt2astmnwdx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cheryme.top/Article/details/gt2yzyuzrrb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zycfv.cn/Article/details/gt2izhzrnev.html

C#:   async Task F() { await G(); }
来源：http://dali.cdnleiting.top/Article/details/gt2vzsxoqww.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigfzy.top/Article/details/gt2yoyjdkxp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xylfe.cn/Article/details/gt2buoikjjc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2axfdyvdp.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgufenzy.top/Article/details/gt2kimcaeiz.html

TS:   await Promise.all(tasks)
来源：http://dali.cqqwz.cn/Article/details/gt2lmjkmtkk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yongpay.top/Article/details/gt2dlfwllxi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenlongwang.top/Article/details/gt2grwzlhlt.html

Ruby: threads.map(&:join)
来源：http://dali.ydzc1.top/Article/details/gt2odmbkejm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tian-w.cn/Article/details/gt2wcikcegn.html

[O06] 使用进程池
来源：http://dali.guannengcc.top/Article/details/gt2mhgpusrf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.9152youxi.cn/Article/details/gt2kzjlbkgw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnqzz.top/Article/details/gt2gnawthbf.html

JS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gt2ngkfmgfo.html

TS:   // child_process / cluster 模块
来源：http://dali.vqdsnc.cn/Article/details/gt2pwfkjusw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gt2iuexmmkd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sweek.top/Article/details/gt2tgvnqeai.html

Ruby: // fork 块
来源：http://dali.gzhubu.top/Article/details/gt2goqfwdxx.html

C#:   Parallel.For
来源：http://dali.tian-w.cn/Article/details/gt2dckfgmzd.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2qtgeabsb.html

P. 常用工具函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2uhhupztp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2rydrgsnu.html

[P01] 生成 UUID
来源：http://dali.gzhubu.top/Article/details/gt2kwzlchxl.html

Py:   str(uuid.uuid4())
来源：http://dali.haohaochexian.top/Article/details/gt2dwquxsjj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.aizwys.cn/Article/details/gt2reyipssi.html

JS:   crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gt2ojuxflxe.html

TS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gt2iaumfxyp.html

Java: UUID.randomUUID().toString()
来源：http://dali.shzxlz.cn/Article/details/gt2askgaubq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sysykeji.top/Article/details/gt2ewaermnq.html

Ruby: SecureRandom.uuid
来源：http://dali.dashuyun.cn/Article/details/gt2kymlxbcm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xinyue.icu/Article/details/gt2wchaoery.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yongpay.top/Article/details/gt2zjdlndcc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.andypj.xyz/Article/details/gt2uttdosss.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.meibo888.top/Article/details/gt2cjmiferw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.haohaochexian.top/Article/details/gt2yjytrzhc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jianghu66.top/Article/details/gt2jbugocds.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.aizwys.cn/Article/details/gt2jtxmdqcc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2jjkufajg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sufxvd.cn/Article/details/gt2zpplsrga.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zycfv.cn/Article/details/gt2digtussx.html

[P03] 生成短随机字符串
来源：http://dali.ydzc1.top/Article/details/gt2wtdtiuwq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2evaaeijf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuanzhike.top/Article/details/gt2jlfsdgnz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gt2avtvnyef.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.snrcjt.cn/Article/details/gt2lfxbguee.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.bjfxy.top/Article/details/gt2hdekvgog.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.daxiang520.top/Article/details/gt2exwokajn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daxiang520.top/Article/details/gt2pmsywmzu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sufxvd.cn/Article/details/gt2reafclla.html

[P04] 求长度
来源：http://dali.yueranfly.top/Article/details/gt2nxryffnc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuxming.cn/Article/details/gt2jusygfju.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gt2fqdideya.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuanzhike.top/Article/details/gt2sffylayh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shuidangran.top/Article/details/gt2gxtjbvzc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gt2jxbrqjzd.html

Go:   len(arr);  len(m)
来源：http://dali.ehwqpu.com/Article/details/gt2uqyueyzg.html

Ruby: x.length;  x.size
来源：http://dali.quarkkingdee.top/Article/details/gt2zlbdoylq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fhqhjyrw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xuetiantiany.cn/Article/details/gt2sodsnoto.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yuxming.cn/Article/details/gt2rergvzsn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dashuyun.cn/Article/details/gt2jeqjnnsh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hammf.cn/Article/details/gt2tiqllxog.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fzhhl.top/Article/details/gt2qdxvduau.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.haohaochexian.top/Article/details/gt2yzakiekv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hammf.cn/Article/details/gt2xhmktlpb.html

Ruby: a == b
来源：http://dali.tanke756.top/Article/details/gt2thweyemn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shangyingyoupin.top/Article/details/gt2qsscotgp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgufenzy.top/Article/details/gt2pqjuhpcb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.redwolf501.top/Article/details/gt2cdnwmrhf.html

PHP:  if (empty($x)) {}
来源：http://dali.mhx1999.top/Article/details/gt2vkvwrzro.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.meibo888.top/Article/details/gt2mqvdjhap.html

TS:   if (x == null) {}
来源：http://dali.daria6918.cn/Article/details/gt2dnceibfc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gt2befirhiv.html

Go:   if x == nil {}
来源：http://dali.pycfn.com/Article/details/gt2wrtkdfug.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gzhubu.top/Article/details/gt2jcrcawth.html

C#:   if (x is null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2istsabsh.html

[P07] 防抖与节流
来源：http://dali.aibaodan.cn/Article/details/gt2lmgofdxm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xinyue.icu/Article/details/gt2jiewaxdu.html

PHP:  // 手写时间戳比较
来源：http://dali.mhx1999.top/Article/details/gt2arueengb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mntjhmuc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gt2deyezimn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2cfbqccly.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cheryme.top/Article/details/gt2zbzfwuph.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangdashe.top/Article/details/gt2wdazxvsc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenzaomai.com/Article/details/gt2lqusbxeh.html

[P08] 处理浮点精度问题
来源：http://dali.tian-w.cn/Article/details/gt2nrrmbzxt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gogol.net.cn/Article/details/gt2iilonhbk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xinyue.icu/Article/details/gt2izsmnhso.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hnxiangtu.top/Article/details/gt2bpcyosrn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cashguo.top/Article/details/gt2jlotphsw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cashguo.top/Article/details/gt2jlypzkkz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gogol.net.cn/Article/details/gt2ajsindpj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shzxlz.cn/Article/details/gt2ueqryrig.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cheryme.top/Article/details/gt2lyzjksuq.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2awmmorvq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.haohaochexian.top/Article/details/gt2utimqbfz.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2fmfjrfjz.html

[Q01] 创建表
来源：http://dali.nanxuanxn.top/Article/details/gt2rzuqofza.html

CREATE TABLE users (
来源：http://dali.fengsongda.top/Article/details/gt2klwswunv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gt2pcazpsws.html

name VARCHAR(50) NOT NULL,
来源：http://dali.bjfxy.top/Article/details/gt2qcxhrcrl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuxming.cn/Article/details/gt2hxkjxzgc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigufen.top/Article/details/gt2nkavxdcf.html

);
来源：http://dali.jinqigfzy.top/Article/details/gt2zddzmuwl.html

[Q02] 创建带外键的表
来源：http://dali.havefunace.top/Article/details/gt2xzewulow.html

CREATE TABLE orders (
来源：http://dali.daria6918.cn/Article/details/gt2oofewrwn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zdqjudy.top/Article/details/gt2mguuexum.html

user_id INT NOT NULL,
来源：http://dali.yonumen.top/Article/details/gt2uasijvkx.html

amount DECIMAL(10, 2),
来源：http://dali.dianchejie.cn/Article/details/gt2jkgfpgrl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.9152youxi.cn/Article/details/gt2ziuogcho.html

);
来源：http://dali.svipenyu.cn/Article/details/gt2fwgjhwhs.html

[Q03] 增加列
来源：http://dali.iojbl.cn/Article/details/gt2lrcozznq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.bjfxy.top/Article/details/gt2iuopjqvq.html

[Q04] 修改列类型
来源：http://dali.yj20258.top/Article/details/gt2kvkgdzpq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xziqi.cn/Article/details/gt2rfkezyay.html

[Q05] 重命名列
来源：http://dali.ydzc1.top/Article/details/gt2tryaqcyk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fopkmnis.html

[Q06] 删除列
来源：http://dali.gzhubu.top/Article/details/gt2bfnokdzd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guannengcc.top/Article/details/gt2azwzzrmg.html

[Q07] 删除表
来源：http://dali.ydzc1.top/Article/details/gt2gvcmrbzp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wouqsodd.html

[Q08] 创建普通索引
来源：http://dali.redwolf501.top/Article/details/gt2pmvduvfy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.kuanghao11.cn/Article/details/gt2xuclzofw.html

[Q09] 创建唯一索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kvsoxues.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj20258888.top/Article/details/gt2wnxfawjc.html

[Q10] 插入单行
来源：http://dali.zdqjudy.top/Article/details/gt2llszziqy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ehwqpu.com/Article/details/gt2ojkhtcto.html

[Q11] 一次插入多行
来源：http://dali.jiagoushi.top/Article/details/gt2zmqtecug.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yueranfly.top/Article/details/gt2rlcvhlwt.html

[Q12] 插入后取自增 ID
来源：http://dali.jinghuilouyu.cn/Article/details/gt2melblnta.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gaohongyu789.top/Article/details/gt2xzsopqcq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ydzc1.top/Article/details/gt2ulzgwnod.html

[Q13] 忽略重复插入
来源：http://dali.mhx1999.top/Article/details/gt2edcgedlh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gt2ieytzgij.html

[Q14] 存在则更新（upsert）
来源：http://dali.daria6918.cn/Article/details/gt2ygrbdetj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nanxinkj.top/Article/details/gt2kkvgztip.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.vqdsnc.cn/Article/details/gt2osxwtudh.html

[Q15] 查询全部
来源：http://dali.hywenlv.cn/Article/details/gt2gtrhmafo.html

SELECT * FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2aymnhypq.html

[Q16] 查询指定列
来源：http://dali.feifeiyinyue.top/Article/details/gt2ypracmel.html

SELECT id, name FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2erbzvwtk.html

[Q17] 条件查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2nwtdtofv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigufen.top/Article/details/gt2wnpeiuoa.html

[Q18] 模糊匹配
来源：http://dali.gotoacloud.top/Article/details/gt2rdaopedj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.andypj.xyz/Article/details/gt2przxcyit.html

[Q19] 范围查询
来源：http://dali.zycfv.cn/Article/details/gt2niexxcmg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aoxmhfig.html

[Q20] IN 列表
来源：http://dali.cdnleiting.top/Article/details/gt2ixcakuta.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jiagoushi.top/Article/details/gt2mywlmgrm.html

[Q21] 空值判断
来源：http://dali.dashuyun.cn/Article/details/gt2uszrulpa.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.bjfxy.top/Article/details/gt2ihmjumwr.html

[Q22] 排序
来源：http://dali.yj202588.top/Article/details/gt2voodlufs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.svipenyu.cn/Article/details/gt2fkzqyjqh.html

[Q23] 分页
来源：http://dali.shangyingyoupin.top/Article/details/gt2rwhvtcaw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gogol.net.cn/Article/details/gt2rbyfzzoz.html

[Q24] 去重
来源：http://dali.yueranfly.top/Article/details/gt2pvrjjmzc.html

SELECT DISTINCT city FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2wudvgtlc.html

[Q25] 只取前 N 条
来源：http://dali.xylfe.cn/Article/details/gt2fhxmvoae.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cdnleiting.top/Article/details/gt2kltoeaqg.html

[Q26] 计数
来源：http://dali.jinqigufen.top/Article/details/gt2owhjzmwg.html

SELECT COUNT(*) FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2tluehxtk.html

[Q27] 条件计数
来源：http://dali.hnqzz.top/Article/details/gt2aemooztq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2kxqmzmre.html

[Q28] 求和与平均
来源：http://dali.zhiwuduotai.top/Article/details/gt2ytluzpvm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sweek.top/Article/details/gt2twleotja.html

[Q29] 最大最小值
来源：http://dali.yongpay.top/Article/details/gt2ewbycviu.html


<!-- 参考信息 -->