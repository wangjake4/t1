代发 wailian999

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2uhesymoi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pycfn.com/Article/details/gt2hyavodjh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gt2nflljowm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zycfv.cn/Article/details/gt2hbsejomt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2veobkapr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gt2ipogwtxp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gt2syjzowah.html

Go:   slices.Sort(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2wqaxduwz.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gt2txqxblmo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgufenzy.top/Article/details/gt2qabuiqcj.html

[N03] 快速排序（分治示例）
来源：http://dali.feifeiyinyue.top/Article/details/gt2yejcmadm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuanzhike.top/Article/details/gt2jpmabwfk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.birdmap.top/Article/details/gt2arjordis.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gt2uisomusi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gt2scevywhv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.redwolf501.top/Article/details/gt2dyhydgjf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258888.top/Article/details/gt2fxkjjews.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jianghu66.top/Article/details/gt2sioududs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daria6918.cn/Article/details/gt2vxqlbfqs.html

[N04] 斐波那契数列
来源：http://dali.xziqi.cn/Article/details/gt2mbbjyand.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gt2bngtaknn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zycfv.cn/Article/details/gt2llmnmsrp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gt2xibtnmsq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gt2spilxceq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gt2nxefahob.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.vqdsnc.cn/Article/details/gt2rqypvhmq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gt2mgagyfda.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gt2cmmhxxdh.html

[N05] 最大公约数
来源：http://dali.gaohongyu789.top/Article/details/gt2kjedzlrx.html

Py:   math.gcd(a, b)
来源：http://dali.mhx1999.top/Article/details/gt2jbahrsdp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnxiangtu.top/Article/details/gt2nyfgmjbx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwumazh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gt2awsbxhlq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sweek.top/Article/details/gt2gryzxjzv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guannengcc.top/Article/details/gt2bpbwakyy.html

Ruby: a.gcd(b)
来源：http://dali.cheryme.top/Article/details/gt2dybvbaru.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhongyouzk.top/Article/details/gt2plcgjntd.html

[N06] 判断回文字符串
来源：http://dali.svipenyu.cn/Article/details/gt2ozwfvqsz.html

Py:   s == s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gt2qpnsnyac.html

PHP:  $s === strrev($s);
来源：http://dali.hnqzz.top/Article/details/gt2umotkhmy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gt2nephkmpc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hfpqhxsq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tianlin.xyz/Article/details/gt2tqkukbcs.html

Go:   // 双指针从两端比较
来源：http://dali.gotoacloud.top/Article/details/gt2fqtdgrbv.html

Ruby: s == s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gt2wixudxza.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gt2wffrxban.html

[N07] 两数之和（返回下标）
来源：http://dali.0kj1m.cn/Article/details/gt2hclluzvf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hammf.cn/Article/details/gt2wccqhxnm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.chenjidiqi.icu/Article/details/gt2ecajmlpo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yueranfly.top/Article/details/gt2dojngdpw.html

TS:   // 手写 Map<string, number>
来源：http://dali.haohaochexian.top/Article/details/gt2wjogtrci.html

Java: // 手写 HashMap
来源：http://dali.zhixingplan.top/Article/details/gt2rzeovhay.html

Go:   // 手写 map[int]int
来源：http://dali.shuidangran.top/Article/details/gt2hdjdninm.html

Ruby: // 手写 Hash
来源：http://dali.zhoulong.xyz/Article/details/gt2zpbocvnc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vuruzbpo.html

[N08] 生成全排列
来源：http://dali.sweek.top/Article/details/gt2scljhbzh.html

Py:   itertools.permutations(arr)
来源：http://dali.tian-w.cn/Article/details/gt2wbnbpkny.html

PHP:  // 手写递归交换
来源：http://dali.xuetiantiany.cn/Article/details/gt2rsdzeecf.html

JS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gt2smaqiicz.html

TS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2zmkcudmc.html

Java: // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gt2flooiyis.html

Go:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fbujgkly.html

Ruby: arr.permutation.to_a
来源：http://dali.ppjwa.cn/Article/details/gt2iulqmgkg.html

C#:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2pmyfuahw.html

[N09] 栈与队列
来源：http://dali.ivvv.top/Article/details/gt2tmvmkolu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xziqi.cn/Article/details/gt2skhjlijp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gt2wcaqwmck.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gt2odliwnos.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hnxiangtu.top/Article/details/gt2wjcpuwbo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ydzc1.top/Article/details/gt2xmnkvycd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.kuanghao11.cn/Article/details/gt2qljxxrwz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gt2qlenblhu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gogol.net.cn/Article/details/gt2vkxockns.html

[N10] 链表节点定义
来源：http://dali.fengsongda.top/Article/details/gt2wihovrip.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.quarkkingdee.top/Article/details/gt2psrwqxyn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj20258.top/Article/details/gt2bboudhoy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.andypj.xyz/Article/details/gt2lzqzysbd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258888.top/Article/details/gt2uwmqnqlr.html

Java: class Node { int v; Node next; }
来源：http://dali.gaohongyu789.top/Article/details/gt2yffysauy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aizwys.cn/Article/details/gt2eysdqbuq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gogol.net.cn/Article/details/gt2sccknzek.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ybcxt.top/Article/details/gt2zqhyftvn.html

[N11] 二叉树中序遍历
来源：http://dali.cdnleiting.top/Article/details/gt2xnnfwaiv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ppjwa.cn/Article/details/gt2mhyywwid.html

PHP:  // 手写递归函数
来源：http://dali.gaohongyu789.top/Article/details/gt2aixcybcn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gt2tnfjnrkq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenzaomai.com/Article/details/gt2poycnqyy.html

Java: // 手写递归
来源：http://dali.nwbrower.top/Article/details/gt2ymbipgni.html

Go:   // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gt2gzcslrng.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.kuanghao11.cn/Article/details/gt2qktxfwys.html

C#:   // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gt2euoxsdxr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.dianchejie.cn/Article/details/gt2twmsyamm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnqzz.top/Article/details/gt2dnzqkgkg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj20258.top/Article/details/gt2yyyhxlog.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gt2eidzmams.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yisqejof.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.0kj1m.cn/Article/details/gt2qzflrxdg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxinkj.top/Article/details/gt2yiruuwdp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kqcibqan.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gt2bbtjpaeu.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2vdfgimbf.html

O. 并发与异步
来源：http://dali.yvedp.cn/Article/details/gt2etilrrdr.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2mcudakzx.html

[O01] 启动一个线程
来源：http://dali.vqdsnc.cn/Article/details/gt2yrhqswlo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinqigufen.top/Article/details/gt2vgxvnofc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yangfankeji.com/Article/details/gt2hauvepui.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jianghu66.top/Article/details/gt2cxkcgzdr.html

TS:   // 同 JS
来源：http://dali.ybcxt.top/Article/details/gt2pioextwm.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhongyouzk.top/Article/details/gt2ukjwbakh.html

Go:   go f()
来源：http://dali.meibo888.top/Article/details/gt2atqgysyc.html

Ruby: Thread.new { f }
来源：http://dali.jinqigufen.top/Article/details/gt2orciechk.html

C#:   Task.Run(() => F());
来源：http://dali.gogol.net.cn/Article/details/gt2fyznrogc.html

[O02] 使用线程池
来源：http://dali.dashuyun.cn/Article/details/gt2kzymucpu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yymlcnjo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lyrlssil.html

JS:   // worker_threads 线程池
来源：http://dali.hnqzz.top/Article/details/gt2qgonuyft.html

TS:   // worker_threads 线程池
来源：http://dali.yangfankeji.com/Article/details/gt2qyyiatty.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shzxlz.cn/Article/details/gt2pvtoftnj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ehwqpu.com/Article/details/gt2uwiibasg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.havefunace.top/Article/details/gt2ameojlea.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhiwuduotai.top/Article/details/gt2fhtqavzq.html

[O03] 加锁保护共享数据
来源：http://dali.iojbl.cn/Article/details/gt2smbenfls.html

Py:   with lock: shared += 1
来源：http://dali.gzhubu.top/Article/details/gt2ecrfvqxt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.quarkkingdee.top/Article/details/gt2idlodqpp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tanke756.top/Article/details/gt2evvrzsfn.html

TS:   // 同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gt2qxdyzsxf.html

Java: synchronized (this) { shared++; }
来源：http://dali.wangdashe.top/Article/details/gt2tiosjxpy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tanke756.top/Article/details/gt2nuditnia.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hywenlv.cn/Article/details/gt2vrvmneau.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258.top/Article/details/gt2dcqjbywl.html

[O04] 定义异步函数并等待
来源：http://dali.zhoulong.xyz/Article/details/gt2nvulqghp.html

Py:   async def f():⏎    await g()
来源：http://dali.gotoacloud.top/Article/details/gt2gjkevrxo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hongshengwenyu.top/Article/details/gt2tjiytoyb.html

JS:   async function f() { await g(); }
来源：http://dali.nwbrower.top/Article/details/gt2lbtdijpy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tbvnqpfp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jqgfzy.top/Article/details/gt2evxiweue.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zycfv.cn/Article/details/gt2fpzjxhfl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhoulong.xyz/Article/details/gt2cbxfdntm.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258.top/Article/details/gt2abpktwhe.html

[O05] 并发执行并等待全部完成
来源：http://dali.hfpthk.cn/Article/details/gt2linnbnaf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgufenzy.top/Article/details/gt2ixgdgluj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yangfankeji.com/Article/details/gt2qywgpyia.html

JS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gt2flbooxxg.html

TS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pzjidmsb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.daria6918.cn/Article/details/gt2lbcndrwh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cqqwz.cn/Article/details/gt2avetyuox.html

Ruby: threads.map(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zqcjrxiv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigufen.top/Article/details/gt2muhxanka.html

[O06] 使用进程池
来源：http://dali.pycfn.com/Article/details/gt2dtqzpphw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dashuyun.cn/Article/details/gt2iuxjhlyj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.c1oappe.top/Article/details/gt2rimigqqv.html

JS:   // child_process / cluster 模块
来源：http://dali.vqdsnc.cn/Article/details/gt2xlmfrcyu.html

TS:   // child_process / cluster 模块
来源：http://dali.hnxiangtu.top/Article/details/gt2cfxxpbzk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gt2ychigyfs.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xylfe.cn/Article/details/gt2mxqtkpyz.html

Ruby: // fork 块
来源：http://dali.yongpay.top/Article/details/gt2zcmymrxs.html

C#:   Parallel.For
来源：http://dali.sxryk.cn/Article/details/gt2dujiqkja.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2acsrrhgw.html

P. 常用工具函数
来源：http://dali.yvedp.cn/Article/details/gt2xnixogzw.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2viwvojhq.html

[P01] 生成 UUID
来源：http://dali.quarkkingdee.top/Article/details/gt2lsizpygg.html

Py:   str(uuid.uuid4())
来源：http://dali.hammf.cn/Article/details/gt2ixwcldgw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hfpthk.cn/Article/details/gt2uoepdeun.html

JS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gt2fhsztohr.html

TS:   crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gt2cdkmistl.html

Java: UUID.randomUUID().toString()
来源：http://dali.ybcxt.top/Article/details/gt2mkrgcyck.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dqnlfkeb.html

Ruby: SecureRandom.uuid
来源：http://dali.haohaochexian.top/Article/details/gt2wggvnbci.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cqqwz.cn/Article/details/gt2mgswroqq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangdashe.top/Article/details/gt2brbludyf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangdashe.top/Article/details/gt2tawvunsg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yangfankeji.com/Article/details/gt2sftnhnsd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yonumen.top/Article/details/gt2cdxmtfmg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.redwolf501.top/Article/details/gt2gvwnzooj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gt2wrgdfgdu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dashuyun.cn/Article/details/gt2daxddela.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hdfqubdx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ivvv.top/Article/details/gt2ggysiqfq.html

[P03] 生成短随机字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cglcfngf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yonumen.top/Article/details/gt2kgwrlzxm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hysaishi.cn/Article/details/gt2hngqwjad.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gt2yyupqtsa.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gt2yurwtrsb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xylfe.cn/Article/details/gt2zqdgchck.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yanxiufei.cn/Article/details/gt2rlecfhpg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daxiang520.top/Article/details/gt2crhgifnv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tianlin.xyz/Article/details/gt2ezruokqf.html

[P04] 求长度
来源：http://dali.yj20258888.top/Article/details/gt2arhdrznt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gogol.net.cn/Article/details/gt2oeyxeqbt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gt2rwchxqxq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.9152youxi.cn/Article/details/gt2fdwqeanv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gt2hbyblbob.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2klbjcqsp.html

Go:   len(arr);  len(m)
来源：http://dali.gotoacloud.top/Article/details/gt2stqnmvkl.html

Ruby: x.length;  x.size
来源：http://dali.jinqigfzy.top/Article/details/gt2njnpjadt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhengqikj.top/Article/details/gt2jeypdnxt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tianlin.xyz/Article/details/gt2dznecwtd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zdqjudy.top/Article/details/gt2xslnawcu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.meibo888.top/Article/details/gt2hyfphguo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xinyue.icu/Article/details/gt2incrwqyn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zycfv.cn/Article/details/gt2fwyhdiml.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258888.top/Article/details/gt2ihokuiyt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenzaomai.com/Article/details/gt2hquzoire.html

Ruby: a == b
来源：http://dali.aizwys.cn/Article/details/gt2spqenatg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yvedp.cn/Article/details/gt2pqjjkztg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xuetiantiany.cn/Article/details/gt2gzxpitll.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rmhffyqz.html

PHP:  if (empty($x)) {}
来源：http://dali.mhx1999.top/Article/details/gt2owztfvsr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxinkj.top/Article/details/gt2sspxcznu.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vikwcmee.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gt2tuyuiuuq.html

Go:   if x == nil {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ltwrddqd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.daxiang520.top/Article/details/gt2vmiiqllc.html

C#:   if (x is null) {}
来源：http://dali.chenzaomai.com/Article/details/gt2lwvphfeb.html

[P07] 防抖与节流
来源：http://dali.pengpengdd.cyou/Article/details/gt2tdvydfkq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hnxiangtu.top/Article/details/gt2bkrznqvn.html

PHP:  // 手写时间戳比较
来源：http://dali.xinyue.icu/Article/details/gt2dejoqieg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gt2dstlituc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yvedp.cn/Article/details/gt2bdrsnofc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tanke756.top/Article/details/gt2cfqzkqvs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tian-w.cn/Article/details/gt2dggoadfe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sweek.top/Article/details/gt2tkjcisde.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gotoacloud.top/Article/details/gt2gjyiqmae.html

[P08] 处理浮点精度问题
来源：http://dali.tianlin.xyz/Article/details/gt2nsmpcwfh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gblgtjzd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2aocldbww.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zacnihdh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jlsjyb.cn/Article/details/gt2gtyzkhia.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jqgufenzy.top/Article/details/gt2keegvneo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xziqi.cn/Article/details/gt2mcnlllud.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jiagoushi.top/Article/details/gt2badobyjz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pengpengdd.cyou/Article/details/gt2jfdrvkxq.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2zebuqhiq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xylfe.cn/Article/details/gt2ewyqzfsn.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iwulxwnu.html

[Q01] 创建表
来源：http://dali.nwbrower.top/Article/details/gt2mixcqexq.html

CREATE TABLE users (
来源：http://dali.quarkkingdee.top/Article/details/gt2ocyrhhbp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuanzhike.top/Article/details/gt2dfrtzgze.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gt2cgwdqndg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cqqwz.cn/Article/details/gt2hszrlaiv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tanke756.top/Article/details/gt2bpfaadsy.html

);
来源：http://dali.shzxlz.cn/Article/details/gt2uvtajrjz.html

[Q02] 创建带外键的表
来源：http://dali.yuxming.cn/Article/details/gt2hnafqaau.html

CREATE TABLE orders (
来源：http://dali.zhoulong.xyz/Article/details/gt2qnysjnxk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jianghu66.top/Article/details/gt2jthlzgxy.html

user_id INT NOT NULL,
来源：http://dali.hammf.cn/Article/details/gt2knqqjxck.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ugvcuezx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hammf.cn/Article/details/gt2xmpnnuwq.html

);
来源：http://dali.guowangkeji.top/Article/details/gt2tqvljsbn.html

[Q03] 增加列
来源：http://dali.hnqzz.top/Article/details/gt2decdddru.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cheryme.top/Article/details/gt2hvgpyxfj.html

[Q04] 修改列类型
来源：http://dali.9152youxi.cn/Article/details/gt2rkfwxizq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yangfankeji.com/Article/details/gt2gdwezhcq.html

[Q05] 重命名列
来源：http://dali.cucudq.cn/Article/details/gt2hbewdfmh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gaohongyu789.top/Article/details/gt2dmvokgle.html

[Q06] 删除列
来源：http://dali.jlsjyb.cn/Article/details/gt2mzabzjqr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.havefunace.top/Article/details/gt2xcqkjfsc.html

[Q07] 删除表
来源：http://dali.pengpengdd.cyou/Article/details/gt2icamwrrx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.guannengcc.top/Article/details/gt2tejevsrf.html

[Q08] 创建普通索引
来源：http://dali.jiagoushi.top/Article/details/gt2bvnsydkn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jvbsydyk.html

[Q09] 创建唯一索引
来源：http://dali.fengsongda.top/Article/details/gt2ddlkhwzd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gt2dionocah.html

[Q10] 插入单行
来源：http://dali.kuanghao11.cn/Article/details/gt2wmiaihnn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cqqwz.cn/Article/details/gt2eqxyetbb.html

[Q11] 一次插入多行
来源：http://dali.hywenlv.cn/Article/details/gt2oqtqzddn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fernshzk.html

[Q12] 插入后取自增 ID
来源：http://dali.jlsjyb.cn/Article/details/gt2nsccupyr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gcmffumu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pkpzevbp.html

[Q13] 忽略重复插入
来源：http://dali.yj202588.top/Article/details/gt2dzggdwaz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cheryme.top/Article/details/gt2yhkfqxjh.html

[Q14] 存在则更新（upsert）
来源：http://dali.316326.xyz/Article/details/gt2yqjmwkpv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhengqikj.top/Article/details/gt2tunmtkkw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ehwqpu.com/Article/details/gt2aiejaaro.html

[Q15] 查询全部
来源：http://dali.yj202588.top/Article/details/gt2zjmwjurx.html

SELECT * FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2xrawzyuc.html

[Q16] 查询指定列
来源：http://dali.0kj1m.cn/Article/details/gt2toggenyi.html

SELECT id, name FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2bptckpkl.html

[Q17] 条件查询
来源：http://dali.hfpthk.cn/Article/details/gt2jjqculvw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.birdmap.top/Article/details/gt2rzlslfad.html

[Q18] 模糊匹配
来源：http://dali.aizwys.cn/Article/details/gt2uhybjgac.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daria6918.cn/Article/details/gt2orkczzjl.html

[Q19] 范围查询
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fhhqqeta.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.iojbl.cn/Article/details/gt2prwfxjvl.html

[Q20] IN 列表
来源：http://dali.ydzc1.top/Article/details/gt2hvfxnzzv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.svipenyu.cn/Article/details/gt2vllnxxqr.html

[Q21] 空值判断
来源：http://dali.yj20258.top/Article/details/gt2oauramsb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guowangkeji.top/Article/details/gt2vrvzmyyl.html

[Q22] 排序
来源：http://dali.daxiang520.top/Article/details/gt2ovsbcksw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cdnleiting.top/Article/details/gt2yuaqivzo.html

[Q23] 分页
来源：http://dali.wangdashe.top/Article/details/gt2gqougnes.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ppjwa.cn/Article/details/gt2irwncwuj.html

[Q24] 去重
来源：http://dali.yueranfly.top/Article/details/gt2hxhhukwv.html

SELECT DISTINCT city FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2caoitbwm.html

[Q25] 只取前 N 条
来源：http://dali.fengsongda.top/Article/details/gt2zuwyjgwb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jianghu66.top/Article/details/gt2egcjdlqk.html

[Q26] 计数
来源：http://dali.cdnleiting.top/Article/details/gt2tpmzdzuj.html

SELECT COUNT(*) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2ndribapw.html

[Q27] 条件计数
来源：http://dali.meibo888.top/Article/details/gt2nfmlajmg.html


<!-- 参考信息 -->