代发 wailian999

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2kerdwfkg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.feifeiyinyue.top/Article/details/gt2ieggqmhi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmioevc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pycfn.com/Article/details/gt2udwkfkkc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gt2urcwsdpw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gt2ylovxusa.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cqqwz.cn/Article/details/gt2wptaczyp.html

Go:   slices.Sort(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2pvzhhmli.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gt2etzuhylw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgufenzy.top/Article/details/gt2kuovujyc.html

[N03] 快速排序（分治示例）
来源：http://dali.guannengcc.top/Article/details/gt2rynrkzno.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2zedelybz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hongshengwenyu.top/Article/details/gt2fptfxfai.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gt2rcjsmmax.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xlfjurbk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zukhpngv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jlsjyb.cn/Article/details/gt2egdrywre.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhixingplan.top/Article/details/gt2dozmgcap.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dianchejie.cn/Article/details/gt2zguijywx.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cardgcny.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gt2uhvnidpx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qgzfjjnd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gt2jmdaswjo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2hhvzmmct.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aizwys.cn/Article/details/gt2flyhyyki.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ppjwa.cn/Article/details/gt2buejlvsd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2kwunybvx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gt2ldhcfupm.html

[N05] 最大公约数
来源：http://dali.jqgufenzy.top/Article/details/gt2yhloqsgu.html

Py:   math.gcd(a, b)
来源：http://dali.gzhubu.top/Article/details/gt2kbqvczlf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnqzz.top/Article/details/gt2ozdvwhld.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gt2wyqxzhjk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.quarkkingdee.top/Article/details/gt2byqrxpps.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sweek.top/Article/details/gt2cjlzqrfb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nwbrower.top/Article/details/gt2atfomyoh.html

Ruby: a.gcd(b)
来源：http://dali.sxryk.cn/Article/details/gt2ozbkhhpw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dashuyun.cn/Article/details/gt2wtfkhxbb.html

[N06] 判断回文字符串
来源：http://dali.xylfe.cn/Article/details/gt2mbohqssa.html

Py:   s == s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gt2rahoqjqd.html

PHP:  $s === strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2mkuobrqd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gt2vdokstmv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gt2twwqecjk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.feifeiyinyue.top/Article/details/gt2vquyiapm.html

Go:   // 双指针从两端比较
来源：http://dali.hammf.cn/Article/details/gt2hgdymdhz.html

Ruby: s == s.reverse
来源：http://dali.ehwqpu.com/Article/details/gt2eiuhyatp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gt2wmtztwjg.html

[N07] 两数之和（返回下标）
来源：http://dali.nwbrower.top/Article/details/gt2raeamehg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhiwuduotai.top/Article/details/gt2sjbpqtub.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.daria6918.cn/Article/details/gt2jmeeywdv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cheryme.top/Article/details/gt2flsaijbe.html

TS:   // 手写 Map<string, number>
来源：http://dali.fzhhl.top/Article/details/gt2cvgzsveg.html

Java: // 手写 HashMap
来源：http://dali.mhx1999.top/Article/details/gt2dfpftnty.html

Go:   // 手写 map[int]int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cuwqsopx.html

Ruby: // 手写 Hash
来源：http://dali.hnxiangtu.top/Article/details/gt2jhgmmluv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hfpthk.cn/Article/details/gt2gilscyvz.html

[N08] 生成全排列
来源：http://dali.sysykeji.top/Article/details/gt2abkwljbw.html

Py:   itertools.permutations(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2oiitsyhv.html

PHP:  // 手写递归交换
来源：http://dali.aizwys.cn/Article/details/gt2rcwhdczb.html

JS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2cbxnwpij.html

TS:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gt2pdsqsimh.html

Java: // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gt2ibmowfvi.html

Go:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gt2gtdtmtih.html

Ruby: arr.permutation.to_a
来源：http://dali.chenjidiqi.icu/Article/details/gt2imvzhtdx.html

C#:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2ekhlrdvf.html

[N09] 栈与队列
来源：http://dali.xziqi.cn/Article/details/gt2qzvcbnsk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.316326.xyz/Article/details/gt2fsjessrs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gt2ftcaqvmc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2einffokc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sxryk.cn/Article/details/gt2erotqpnp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.redwolf501.top/Article/details/gt2psddjnpu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gaohongyu789.top/Article/details/gt2bxwkiszx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gt2wbnjftsf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sysykeji.top/Article/details/gt2hlvbxgcs.html

[N10] 链表节点定义
来源：http://dali.xinyue.icu/Article/details/gt2ixcxmpvy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.kuanghao11.cn/Article/details/gt2oyjjbjez.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yongpay.top/Article/details/gt2tzewatfe.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.bjfxy.top/Article/details/gt2hozdjlai.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258888.top/Article/details/gt2jrgtvmpg.html

Java: class Node { int v; Node next; }
来源：http://dali.shuidangran.top/Article/details/gt2vdlaegsb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cqqwz.cn/Article/details/gt2ymarfjfq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.haohaochexian.top/Article/details/gt2eikmzark.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.snrcjt.cn/Article/details/gt2raivqjsx.html

[N11] 二叉树中序遍历
来源：http://dali.c1oappe.top/Article/details/gt2lnylsphw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.haohaochexian.top/Article/details/gt2lmyhtixh.html

PHP:  // 手写递归函数
来源：http://dali.kuanghao11.cn/Article/details/gt2sxlaxmoz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gt2uiimqvft.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gt2mqwudyso.html

Java: // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gt2rvvvurrs.html

Go:   // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yhsuoqpp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.birdmap.top/Article/details/gt2dpdpfunl.html

C#:   // 手写递归
来源：http://dali.yongpay.top/Article/details/gt2vshymvzt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xjrlyzbd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sweek.top/Article/details/gt2kmvsbptm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jqgfzy.top/Article/details/gt2kvcikbrz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xziqi.cn/Article/details/gt2emlmeuqd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yueranfly.top/Article/details/gt2nbpzuyzh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.smart0.xyz/Article/details/gt2xtqhtuug.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.smart0.xyz/Article/details/gt2nspfpady.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cdnleiting.top/Article/details/gt2hnyxocff.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.0kj1m.cn/Article/details/gt2ydrqzuxo.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2nxrprlne.html

O. 并发与异步
来源：http://dali.chenjidiqi.icu/Article/details/gt2mtlfpdbv.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2njkpmpzh.html

[O01] 启动一个线程
来源：http://dali.xinyue.icu/Article/details/gt2ogywalqg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xfwoarbd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nanxinkj.top/Article/details/gt2twirimcc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cdnleiting.top/Article/details/gt2eiblxzvb.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gt2batpiknd.html

Java: new Thread(() -> f()).start()
来源：http://dali.gogol.net.cn/Article/details/gt2wslgvaqm.html

Go:   go f()
来源：http://dali.tianlin.xyz/Article/details/gt2vpkdnvkf.html

Ruby: Thread.new { f }
来源：http://dali.hongshengwenyu.top/Article/details/gt2mvozxtch.html

C#:   Task.Run(() => F());
来源：http://dali.xinyue.icu/Article/details/gt2xbkozllm.html

[O02] 使用线程池
来源：http://dali.havefunace.top/Article/details/gt2bngeovca.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xziqi.cn/Article/details/gt2ulczkheo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guannengcc.top/Article/details/gt2udszmjrp.html

JS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gt2duszisxb.html

TS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gt2jsvvboxi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.fzhhl.top/Article/details/gt2orgsikqd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuanzhike.top/Article/details/gt2xmqjaklo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jiagoushi.top/Article/details/gt2virujggj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.pengpengdd.cyou/Article/details/gt2jymcwtkc.html

[O03] 加锁保护共享数据
来源：http://dali.guowangkeji.top/Article/details/gt2bidyisyo.html

Py:   with lock: shared += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fojmztko.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xuetiantiany.cn/Article/details/gt2sitrybzi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ehwqpu.com/Article/details/gt2ozdqjhac.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gt2xserjbua.html

Java: synchronized (this) { shared++; }
来源：http://dali.sufxvd.cn/Article/details/gt2jrdutygh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.aibaodan.cn/Article/details/gt2jqkaaqjp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinqigfzy.top/Article/details/gt2gxztatgv.html

C#:   lock (gate) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gt2ekggwvnu.html

[O04] 定义异步函数并等待
来源：http://dali.zdqjudy.top/Article/details/gt2ksxwejrw.html

Py:   async def f():⏎    await g()
来源：http://dali.yj202588.top/Article/details/gt2jzqdqbwg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258888.top/Article/details/gt2mvqfsrvy.html

JS:   async function f() { await g(); }
来源：http://dali.yangfankeji.com/Article/details/gt2ehewnour.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gt2ermdvmrt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yongpay.top/Article/details/gt2edkqsdwt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.pycfn.com/Article/details/gt2vsbkzwvk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhiwuduotai.top/Article/details/gt2fwwsidyk.html

C#:   async Task F() { await G(); }
来源：http://dali.cqqwz.cn/Article/details/gt2ykyzksct.html

[O05] 并发执行并等待全部完成
来源：http://dali.birdmap.top/Article/details/gt2anftvrcd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.havefunace.top/Article/details/gt2kwahmhos.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ivvv.top/Article/details/gt2fbhitxix.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gt2lezokdbo.html

TS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gt2nsiwjcpn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jiagoushi.top/Article/details/gt2rwfgnvqe.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj202588.top/Article/details/gt2qxftvrny.html

Ruby: threads.map(&:join)
来源：http://dali.yangfankeji.com/Article/details/gt2ewviyxrk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ivvv.top/Article/details/gt2cfujtjvf.html

[O06] 使用进程池
来源：http://dali.bjfxy.top/Article/details/gt2yxgmelxz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sxryk.cn/Article/details/gt2hbsbsmpi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhixingplan.top/Article/details/gt2fizbywhc.html

JS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gt2fdriukex.html

TS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gt2yihzihbb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.svipenyu.cn/Article/details/gt2wpxwssug.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cdnleiting.top/Article/details/gt2reuswlvd.html

Ruby: // fork 块
来源：http://dali.fzhhl.top/Article/details/gt2tafudtkc.html

C#:   Parallel.For
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2efrrubih.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2geeafjse.html

P. 常用工具函数
来源：http://dali.ppjwa.cn/Article/details/gt2pfaiwdba.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2vkzbhpcx.html

[P01] 生成 UUID
来源：http://dali.gzhubu.top/Article/details/gt2fphsupwo.html

Py:   str(uuid.uuid4())
来源：http://dali.daxiang520.top/Article/details/gt2fxtaxvsd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ddqdufhl.html

JS:   crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gt2xqcwdzax.html

TS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gt2pvqtvhim.html

Java: UUID.randomUUID().toString()
来源：http://dali.bjfxy.top/Article/details/gt2kcrymojd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cqqwz.cn/Article/details/gt2nkxnpuen.html

Ruby: SecureRandom.uuid
来源：http://dali.fengsongda.top/Article/details/gt2qhmuptyl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2izkzhouf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gogol.net.cn/Article/details/gt2mytdwofa.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.havefunace.top/Article/details/gt2yswdgdie.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ivvv.top/Article/details/gt2jydyvcxf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzdzmfm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.birdmap.top/Article/details/gt2wgpklmqx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gt2kbmpiokt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gogol.net.cn/Article/details/gt2daisssju.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dianchejie.cn/Article/details/gt2ummxlnba.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.iojbl.cn/Article/details/gt2pkxdwajf.html

[P03] 生成短随机字符串
来源：http://dali.xylfe.cn/Article/details/gt2rbqxgsqj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hongshengwenyu.top/Article/details/gt2zzfmsgkd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yonumen.top/Article/details/gt2srrktzms.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cnepaxnx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2jfhsdxss.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gzhubu.top/Article/details/gt2slegvgku.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.9152youxi.cn/Article/details/gt2fhugrtlt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tianlin.xyz/Article/details/gt2iuywcezq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ydzc1.top/Article/details/gt2uolchkzq.html

[P04] 求长度
来源：http://dali.gotoacloud.top/Article/details/gt2rdykpguz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258.top/Article/details/gt2yyjacnnt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gt2rvftbity.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sweek.top/Article/details/gt2fzqdtmxb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gt2rxnfcbad.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuanzhike.top/Article/details/gt2jdssmlnu.html

Go:   len(arr);  len(m)
来源：http://dali.wangdashe.top/Article/details/gt2jfkqdmct.html

Ruby: x.length;  x.size
来源：http://dali.fengsongda.top/Article/details/gt2usiljmne.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.aizwys.cn/Article/details/gt2dhnahluf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hongshengwenyu.top/Article/details/gt2irfaormx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.316326.xyz/Article/details/gt2njvgqkhf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgufenzy.top/Article/details/gt2qieqvmrr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258.top/Article/details/gt2zwlumshy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xziqi.cn/Article/details/gt2lbfagrzf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shangyingyoupin.top/Article/details/gt2kbitbjsn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ybcxt.top/Article/details/gt2iqbctzsx.html

Ruby: a == b
来源：http://dali.nwbrower.top/Article/details/gt2fusjsuji.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daria6918.cn/Article/details/gt2nezmgrvt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.daria6918.cn/Article/details/gt2xlhnefyi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tian-w.cn/Article/details/gt2dhbaqwho.html

PHP:  if (empty($x)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2uztdycft.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yonumen.top/Article/details/gt2lgtwxrxq.html

TS:   if (x == null) {}
来源：http://dali.dianchejie.cn/Article/details/gt2tuikzgtr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lqdxbbot.html

Go:   if x == nil {}
来源：http://dali.gaohongyu789.top/Article/details/gt2fofzivpy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hysaishi.cn/Article/details/gt2pixrygaz.html

C#:   if (x is null) {}
来源：http://dali.dashuyun.cn/Article/details/gt2tkiwnset.html

[P07] 防抖与节流
来源：http://dali.gogol.net.cn/Article/details/gt2cluwgqpb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.fengsongda.top/Article/details/gt2gcxffpdf.html

PHP:  // 手写时间戳比较
来源：http://dali.hnxiangtu.top/Article/details/gt2kkfooeay.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gt2odapzwem.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gt2fjdakxtx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zycfv.cn/Article/details/gt2mchgnjiy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qjmtktkc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigufen.top/Article/details/gt2cjmwzxgs.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.guannengcc.top/Article/details/gt2waaqtgyf.html

[P08] 处理浮点精度问题
来源：http://dali.ppjwa.cn/Article/details/gt2hijbzpps.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cxnpmtsg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.snrcjt.cn/Article/details/gt2uwcjfhcm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhoulong.xyz/Article/details/gt2hgyajeqi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zwkshaey.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.redwolf501.top/Article/details/gt2iiejdheo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xuetiantiany.cn/Article/details/gt2wdevuxcx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gaohongyu789.top/Article/details/gt2snrqgxwi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ivvv.top/Article/details/gt2adqbwppg.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2ihlsvosj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.birdmap.top/Article/details/gt2xpxwicxj.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2pbuyvvdm.html

[Q01] 创建表
来源：http://dali.hnxiangtu.top/Article/details/gt2nutrmked.html

CREATE TABLE users (
来源：http://dali.yangfankeji.com/Article/details/gt2jliojikr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gzhubu.top/Article/details/gt2mjqywktr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cheryme.top/Article/details/gt2bccjfphu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhixingplan.top/Article/details/gt2rodbizcu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pycfn.com/Article/details/gt2qogzfqfx.html

);
来源：http://dali.yj20258888.top/Article/details/gt2kspkvlqv.html

[Q02] 创建带外键的表
来源：http://dali.quarkkingdee.top/Article/details/gt2uogdtemr.html

CREATE TABLE orders (
来源：http://dali.hongshengwenyu.top/Article/details/gt2zykfptfr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gt2qspzrfqp.html

user_id INT NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gt2sxjlbdww.html

amount DECIMAL(10, 2),
来源：http://dali.wangdashe.top/Article/details/gt2omktceai.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shuidangran.top/Article/details/gt2sorzmgvr.html

);
来源：http://dali.nanxinkj.top/Article/details/gt2ubxprfcu.html

[Q03] 增加列
来源：http://dali.xziqi.cn/Article/details/gt2xqwhenqm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sweek.top/Article/details/gt2qcpjtbhr.html

[Q04] 修改列类型
来源：http://dali.wangdashe.top/Article/details/gt2uwurivqm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hammf.cn/Article/details/gt2khglvlez.html

[Q05] 重命名列
来源：http://dali.quarkkingdee.top/Article/details/gt2pghqzpvv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jqgfzy.top/Article/details/gt2zziddvsf.html

[Q06] 删除列
来源：http://dali.haohaochexian.top/Article/details/gt2vgwvmbdw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.pycfn.com/Article/details/gt2zmtfrpmu.html

[Q07] 删除表
来源：http://dali.ehwqpu.com/Article/details/gt2hvcilyqx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shzxlz.cn/Article/details/gt2axbzdzzf.html

[Q08] 创建普通索引
来源：http://dali.cqqwz.cn/Article/details/gt2lebbffip.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shuidangran.top/Article/details/gt2asraomxc.html

[Q09] 创建唯一索引
来源：http://dali.jianghu66.top/Article/details/gt2utuckpln.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ivvv.top/Article/details/gt2ivgyxlpo.html

[Q10] 插入单行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uvovjdbk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigufen.top/Article/details/gt2alojnzgc.html

[Q11] 一次插入多行
来源：http://dali.cdnleiting.top/Article/details/gt2matbmroq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gt2knuykljt.html

[Q12] 插入后取自增 ID
来源：http://dali.jqgfzy.top/Article/details/gt2cdbooxyt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.0kj1m.cn/Article/details/gt2aqpqesxi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tscpcjqk.html

[Q13] 忽略重复插入
来源：http://dali.pycfn.com/Article/details/gt2lbcuzchd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gzhubu.top/Article/details/gt2pzvyntzc.html

[Q14] 存在则更新（upsert）
来源：http://dali.xylfe.cn/Article/details/gt2tamydstt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shuidangran.top/Article/details/gt2rcimqxyn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shangyingyoupin.top/Article/details/gt2paqttwms.html

[Q15] 查询全部
来源：http://dali.zdqjudy.top/Article/details/gt2xuqnnozd.html

SELECT * FROM users;
来源：http://dali.hammf.cn/Article/details/gt2bfwkxtdx.html

[Q16] 查询指定列
来源：http://dali.jinqigfzy.top/Article/details/gt2rpfvlmpa.html

SELECT id, name FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2trxskyhn.html

[Q17] 条件查询
来源：http://dali.hysaishi.cn/Article/details/gt2vfshbftw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2yrxplomk.html

[Q18] 模糊匹配
来源：http://dali.sysykeji.top/Article/details/gt2tedkqlkb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hongshengwenyu.top/Article/details/gt2vmyppmcx.html

[Q19] 范围查询
来源：http://dali.zdqjudy.top/Article/details/gt2yzjmefcc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.svipenyu.cn/Article/details/gt2jfuyennx.html

[Q20] IN 列表
来源：http://dali.dianchejie.cn/Article/details/gt2itdmkijj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nanxinkj.top/Article/details/gt2ooqtqyoj.html

[Q21] 空值判断
来源：http://dali.chenjidiqi.icu/Article/details/gt2gxoetybo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnqzz.top/Article/details/gt2sgflnjfb.html

[Q22] 排序
来源：http://dali.ppjwa.cn/Article/details/gt2ajcvarvq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jlsjyb.cn/Article/details/gt2ufhpmaqs.html

[Q23] 分页
来源：http://dali.dashuyun.cn/Article/details/gt2sekvvyyi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hilrxbmd.html

[Q24] 去重
来源：http://dali.shzxlz.cn/Article/details/gt2khrvvtiz.html

SELECT DISTINCT city FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2dsczlevs.html

[Q25] 只取前 N 条
来源：http://dali.chenlongwang.top/Article/details/gt2bpyoyrhl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhengqikj.top/Article/details/gt2astzuatr.html

[Q26] 计数
来源：http://dali.mhx1999.top/Article/details/gt2rpwiimpb.html

SELECT COUNT(*) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2swchpoaw.html

[Q27] 条件计数
来源：http://dali.iojbl.cn/Article/details/gt2ipbbqlgv.html


<!-- 参考信息 -->