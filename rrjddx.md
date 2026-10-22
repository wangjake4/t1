代发 wailian999

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtqtdwdvze.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhongyouzk.top/Article/details/gtvpkfaipo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.redwolf501.top/Article/details/gtmhjlmrli.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtktfaurvb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gtoylqfptq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gtiazbgiku.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ybcxt.top/Article/details/gtmpzjiwnu.html

Go:   slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gtnadupvhm.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gtgqnvcglw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfqovtoy.html

[N03] 快速排序（分治示例）
来源：http://dali.daxiang520.top/Article/details/gthitmixrv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gotoacloud.top/Article/details/gtcngfuztn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hysaishi.cn/Article/details/gtimgicxif.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gtibiulfqq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gtcgxlxmgs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ehwqpu.com/Article/details/gtlvgesrec.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yvedp.cn/Article/details/gtekkwlcbk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tanke756.top/Article/details/gtwqvunden.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.pengpengdd.cyou/Article/details/gtdpxtgrfo.html

[N04] 斐波那契数列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchwdjame.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gtnlabmwxl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbousrclu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtramaytgt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtmypanujb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gtbmmgoanz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj202588.top/Article/details/gtcinzhuas.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guannengcc.top/Article/details/gtrkmzucvm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtrbfpbbsq.html

[N05] 最大公约数
来源：http://dali.hfpthk.cn/Article/details/gtgomjaexr.html

Py:   math.gcd(a, b)
来源：http://dali.daxiang520.top/Article/details/gtmdkxepjv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyidbbseb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gtgawmurba.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gtzppubwss.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gtpgbblqsq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.andypj.xyz/Article/details/gtqdjxboon.html

Ruby: a.gcd(b)
来源：http://dali.zhengqikj.top/Article/details/gtehaygpqb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cashguo.top/Article/details/gtnxfraogq.html

[N06] 判断回文字符串
来源：http://dali.svipenyu.cn/Article/details/gtlfrtsykx.html

Py:   s == s[::-1]
来源：http://dali.jyoumei.cn/Article/details/gtepfevaou.html

PHP:  $s === strrev($s);
来源：http://dali.daxiang520.top/Article/details/gtsumurzpq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtyzncmlcn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtchirneiy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.316326.xyz/Article/details/gthabpqgxg.html

Go:   // 双指针从两端比较
来源：http://dali.0kj1m.cn/Article/details/gtbidyvvvs.html

Ruby: s == s.reverse
来源：http://dali.yangfankeji.com/Article/details/gtshuumqki.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gtkggxqspv.html

[N07] 两数之和（返回下标）
来源：http://dali.jlsjyb.cn/Article/details/gtlhybonen.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daria6918.cn/Article/details/gtltjckbgw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.feifeiyinyue.top/Article/details/gtfyfhqtkf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.redwolf501.top/Article/details/gtmqahloig.html

TS:   // 手写 Map<string, number>
来源：http://dali.sxryk.cn/Article/details/gtogllhxlz.html

Java: // 手写 HashMap
来源：http://dali.dashuyun.cn/Article/details/gttpijdusj.html

Go:   // 手写 map[int]int
来源：http://dali.vqdsnc.cn/Article/details/gtkghvywte.html

Ruby: // 手写 Hash
来源：http://dali.fzhhl.top/Article/details/gtwnnxndzi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj20258888.top/Article/details/gtipopbdsk.html

[N08] 生成全排列
来源：http://dali.zhiwuduotai.top/Article/details/gtdozqfctg.html

Py:   itertools.permutations(arr)
来源：http://dali.sxryk.cn/Article/details/gtdiscloxg.html

PHP:  // 手写递归交换
来源：http://dali.guannengcc.top/Article/details/gteclxqmdv.html

JS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtxzyakauc.html

TS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtxefaifnu.html

Java: // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtrjrmwnyp.html

Go:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtrwhbspqz.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gtmirvmgnt.html

C#:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtrakylxlg.html

[N09] 栈与队列
来源：http://dali.wangdashe.top/Article/details/gteqbxvcrm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.bjfxy.top/Article/details/gtzzzumsbi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gtmixhxugn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gtatycztps.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.vqdsnc.cn/Article/details/gtlvfylpix.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkiqrmrf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nwbrower.top/Article/details/gtiwbvqext.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtlrtepghh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tian-w.cn/Article/details/gtezbswkyd.html

[N10] 链表节点定义
来源：http://dali.nanxinkj.top/Article/details/gtwqadbnir.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xinyue.icu/Article/details/gtnushxftd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj20258.top/Article/details/gtsescleoq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj20258888.top/Article/details/gthfrwcqcr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tianlin.xyz/Article/details/gtzfgslmha.html

Java: class Node { int v; Node next; }
来源：http://dali.yonumen.top/Article/details/gtxynpmjbn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jiagoushi.top/Article/details/gtywbtlmjp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yangfankeji.com/Article/details/gtdwoysafk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sufxvd.cn/Article/details/gttdhhcrky.html

[N11] 二叉树中序遍历
来源：http://dali.sxryk.cn/Article/details/gtebttnass.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.0kj1m.cn/Article/details/gthmxuxide.html

PHP:  // 手写递归函数
来源：http://dali.shuidangran.top/Article/details/gtrhvqtnov.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gtkhyadpso.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gtcgslvbyc.html

Java: // 手写递归
来源：http://dali.mhx1999.top/Article/details/gtlfqxikia.html

Go:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtfrqjdtmc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xinyue.icu/Article/details/gtnozqjhrb.html

C#:   // 手写递归
来源：http://dali.xziqi.cn/Article/details/gtlvfdjhhl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ydzc1.top/Article/details/gtmnzdsfkd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ehwqpu.com/Article/details/gtqwijcdty.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.andypj.xyz/Article/details/gtwiepgjss.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gtowmoqgck.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gtyajkcrcw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltxbxybn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yangfankeji.com/Article/details/gtpngbmwhi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xuanzx.com/Article/details/gtvkvoydyv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gtivclgmya.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtbmculndb.html

O. 并发与异步
来源：http://dali.hfpthk.cn/Article/details/gtystyrsal.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtartrhwhu.html

[O01] 启动一个线程
来源：http://dali.sxryk.cn/Article/details/gtmvpcaqgf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.birdmap.top/Article/details/gtzvzercmi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cucudq.cn/Article/details/gtvynnbakx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.bjfxy.top/Article/details/gtegaddgqw.html

TS:   // 同 JS
来源：http://dali.nanxinkj.top/Article/details/gtcwxanmcm.html

Java: new Thread(() -> f()).start()
来源：http://dali.cucudq.cn/Article/details/gtmsxqdend.html

Go:   go f()
来源：http://dali.gaohongyu789.top/Article/details/gtxisswpvr.html

Ruby: Thread.new { f }
来源：http://dali.haohaochexian.top/Article/details/gtxqagktxm.html

C#:   Task.Run(() => F());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwclebpo.html

[O02] 使用线程池
来源：http://dali.tianlin.xyz/Article/details/gtbgvfjhrm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gaohongyu789.top/Article/details/gtbjryphxj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgfzy.top/Article/details/gtvbnyprdv.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258.top/Article/details/gtykhaywlz.html

TS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gtqeexvfnm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.svipenyu.cn/Article/details/gtjwaujpzr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yangfankeji.com/Article/details/gtjpxifybm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yvedp.cn/Article/details/gtlcpewpng.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinqigfzy.top/Article/details/gtrvmwmtfa.html

[O03] 加锁保护共享数据
来源：http://dali.fzhhl.top/Article/details/gtcjcrdlnx.html

Py:   with lock: shared += 1
来源：http://dali.birdmap.top/Article/details/gtmikwzkmn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hammf.cn/Article/details/gtkaztwdvi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgufenzy.top/Article/details/gtswavxwkc.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gtrmsakrpb.html

Java: synchronized (this) { shared++; }
来源：http://dali.cheryme.top/Article/details/gtlbyqkekx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tanke756.top/Article/details/gttokfphkj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuxming.cn/Article/details/gtyvnycfsl.html

C#:   lock (gate) { shared++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtsqqsvkxj.html

[O04] 定义异步函数并等待
来源：http://dali.pycfn.com/Article/details/gtagtlcage.html

Py:   async def f():⏎    await g()
来源：http://dali.cqqwz.cn/Article/details/gtgcqpmzko.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hysaishi.cn/Article/details/gtbzbvzjyi.html

JS:   async function f() { await g(); }
来源：http://dali.yonumen.top/Article/details/gtwegapxnv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gtwxqwmfpo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sxryk.cn/Article/details/gtpsikcqtt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sweek.top/Article/details/gtlwzamzva.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.quarkkingdee.top/Article/details/gtrnfobplq.html

C#:   async Task F() { await G(); }
来源：http://dali.yongpay.top/Article/details/gtyzxoutal.html

[O05] 并发执行并等待全部完成
来源：http://dali.mhx1999.top/Article/details/gtjxdkfqju.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nwbrower.top/Article/details/gtrkdhkvzv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.svipenyu.cn/Article/details/gtzurnetxe.html

JS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gtjnwutfib.html

TS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtgornoasb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.smart0.xyz/Article/details/gtqzeahiwm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgttafesv.html

Ruby: threads.map(&:join)
来源：http://dali.jyoumei.cn/Article/details/gtnzigtkgg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cdnleiting.top/Article/details/gtxkymkthb.html

[O06] 使用进程池
来源：http://dali.shuidangran.top/Article/details/gtfeftoxfy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.redwolf501.top/Article/details/gtwqwsnsot.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.0kj1m.cn/Article/details/gtzmhculrw.html

JS:   // child_process / cluster 模块
来源：http://dali.hfpthk.cn/Article/details/gtymgfpeyv.html

TS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gtwwzymiwf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuanzhike.top/Article/details/gtkcglgvok.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgfzy.top/Article/details/gtivwumdsg.html

Ruby: // fork 块
来源：http://dali.yangfankeji.com/Article/details/gtjxpwcioo.html

C#:   Parallel.For
来源：http://dali.aibaodan.cn/Article/details/gtryctvsof.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtjdocfwwy.html

P. 常用工具函数
来源：http://dali.xuetiantiany.cn/Article/details/gtjpcwlhjs.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtehbbjver.html

[P01] 生成 UUID
来源：http://dali.meibo888.top/Article/details/gtcubqzndl.html

Py:   str(uuid.uuid4())
来源：http://dali.guowangkeji.top/Article/details/gtefdolivf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.svipenyu.cn/Article/details/gthnqbwffk.html

JS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzqbpbkf.html

TS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtozyiuntl.html

Java: UUID.randomUUID().toString()
来源：http://dali.birdmap.top/Article/details/gtzgvajfir.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj20258888.top/Article/details/gtzhncpoqn.html

Ruby: SecureRandom.uuid
来源：http://dali.zhixingplan.top/Article/details/gtiyntnydl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dianchejie.cn/Article/details/gtlyiejqed.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pengpengdd.cyou/Article/details/gtdddwklyi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.kuanghao11.cn/Article/details/gtdxgabagq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinqigfzy.top/Article/details/gtmubrfgkv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtkwxmqlkz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangshuangyany.cn/Article/details/gtyivvjkpu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gttgkwvfkn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.haohaochexian.top/Article/details/gtjyqbywsv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sweek.top/Article/details/gtexuiehuv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimwkkvpd.html

[P03] 生成短随机字符串
来源：http://dali.xinyue.icu/Article/details/gttvxsyhwk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhoulong.xyz/Article/details/gtiupwltqe.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.wangshuangyany.cn/Article/details/gtlqmkrtxe.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gtcqzjcjqb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.birdmap.top/Article/details/gtmshafnhr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xylfe.cn/Article/details/gtfzqmvpfs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jqgufenzy.top/Article/details/gtnwdaslrv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xziqi.cn/Article/details/gtmfhlwgsb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnqzz.top/Article/details/gtamlumeck.html

[P04] 求长度
来源：http://dali.chenjidiqi.icu/Article/details/gtpwdpwzbq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hfpthk.cn/Article/details/gtbftplzfy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtkkocoxic.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gtqtungjui.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gtruemeyfx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnqzz.top/Article/details/gtixdulhdm.html

Go:   len(arr);  len(m)
来源：http://dali.wangshuangyany.cn/Article/details/gtzaiynevx.html

Ruby: x.length;  x.size
来源：http://dali.cdnleiting.top/Article/details/gtcumnviot.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shuidangran.top/Article/details/gtnwqggegc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gotoacloud.top/Article/details/gtlnztusoj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xziqi.cn/Article/details/gtafpwsiod.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.mhx1999.top/Article/details/gtauetmqkz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvpitqgol.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.9152youxi.cn/Article/details/gtgrgzfimt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tanke756.top/Article/details/gtxprvyfnw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfnynkie.html

Ruby: a == b
来源：http://dali.cucudq.cn/Article/details/gtrdopktci.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cucudq.cn/Article/details/gtwhsqlofa.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jyoumei.cn/Article/details/gtdzhzqdhb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.andypj.xyz/Article/details/gtqmpqyobl.html

PHP:  if (empty($x)) {}
来源：http://dali.wangdashe.top/Article/details/gtkjncxlku.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjdtbvgj.html

TS:   if (x == null) {}
来源：http://dali.aizwys.cn/Article/details/gtnygckpyo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gtrehiwvam.html

Go:   if x == nil {}
来源：http://dali.hysaishi.cn/Article/details/gtcjuuhxwe.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.svipenyu.cn/Article/details/gtjdzrxart.html

C#:   if (x is null) {}
来源：http://dali.shuidangran.top/Article/details/gtjbkqgoll.html

[P07] 防抖与节流
来源：http://dali.yj20258888.top/Article/details/gtpcwvdloy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sxryk.cn/Article/details/gtwxriwwwx.html

PHP:  // 手写时间戳比较
来源：http://dali.yonumen.top/Article/details/gtshahtfpw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gthnejqlel.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtasbcihbr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtpxwkoklt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cucudq.cn/Article/details/gtidfbjsea.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tianlin.xyz/Article/details/gtpllokhhb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shzxlz.cn/Article/details/gtpgqvebku.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigufen.top/Article/details/gtmxenecms.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xinyue.icu/Article/details/gtnvsyvnqe.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtahrdftxr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.quarkkingdee.top/Article/details/gtygkhbwtc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.svipenyu.cn/Article/details/gtczkskuwo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.vqdsnc.cn/Article/details/gtvrxlcjbm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jianghu66.top/Article/details/gthgtyiakk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.guowangkeji.top/Article/details/gtiioyrets.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddqgktco.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtcnoicetv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.tian-w.cn/Article/details/gtgbkorovz.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsmogzee.html

[Q01] 创建表
来源：http://dali.yanxiufei.cn/Article/details/gtmrkqtces.html

CREATE TABLE users (
来源：http://dali.guannengcc.top/Article/details/gtovkwckxa.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.haohaochexian.top/Article/details/gtcecimiey.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sufxvd.cn/Article/details/gtnupgmvqv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xziqi.cn/Article/details/gtdyljlepx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinghuilouyu.cn/Article/details/gtottrfzft.html

);
来源：http://dali.hammf.cn/Article/details/gtbcsvpsrh.html

[Q02] 创建带外键的表
来源：http://dali.yj20258.top/Article/details/gtwjsxykmp.html

CREATE TABLE orders (
来源：http://dali.jlsjyb.cn/Article/details/gtuxmsuobc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gtavpzjbjb.html

user_id INT NOT NULL,
来源：http://dali.hnxiangtu.top/Article/details/gtbmpgripe.html

amount DECIMAL(10, 2),
来源：http://dali.vqdsnc.cn/Article/details/gtukxglwnt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhengqikj.top/Article/details/gtfyfegxjy.html

);
来源：http://dali.gotoacloud.top/Article/details/gtqgokqkfm.html

[Q03] 增加列
来源：http://dali.hfpthk.cn/Article/details/gtxgupbxmp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhengqikj.top/Article/details/gtodcsgbfn.html

[Q04] 修改列类型
来源：http://dali.dashuyun.cn/Article/details/gtljcerlnz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hammf.cn/Article/details/gttgvtjffk.html

[Q05] 重命名列
来源：http://dali.316326.xyz/Article/details/gtnwynrcdb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.snrcjt.cn/Article/details/gtsaxkjthe.html

[Q06] 删除列
来源：http://dali.chenlongwang.top/Article/details/gtqttvaapn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhongyouzk.top/Article/details/gthifsgbrw.html

[Q07] 删除表
来源：http://dali.sufxvd.cn/Article/details/gticpvlayx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daria6918.cn/Article/details/gtlorabmsn.html

[Q08] 创建普通索引
来源：http://dali.yongpay.top/Article/details/gtvlglqnow.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gtwhqmwtwj.html

[Q09] 创建唯一索引
来源：http://dali.snrcjt.cn/Article/details/gtszukfchr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzclaghlp.html

[Q10] 插入单行
来源：http://dali.fzhhl.top/Article/details/gtrwkznbao.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yueranfly.top/Article/details/gtjchsizkn.html

[Q11] 一次插入多行
来源：http://dali.shangyingyoupin.top/Article/details/gtdvebjpyy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sxryk.cn/Article/details/gtvghumwtr.html

[Q12] 插入后取自增 ID
来源：http://dali.nanxinkj.top/Article/details/gtcqbchijj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.guowangkeji.top/Article/details/gtbrsgkbvi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.smart0.xyz/Article/details/gtbirtfpby.html

[Q13] 忽略重复插入
来源：http://dali.svipenyu.cn/Article/details/gtghcpmybz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.fzhhl.top/Article/details/gtrhlrkcqf.html

[Q14] 存在则更新（upsert）
来源：http://dali.ehwqpu.com/Article/details/gteohscbga.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hysaishi.cn/Article/details/gtxpaoqivp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fzhhl.top/Article/details/gtalwzgbfx.html

[Q15] 查询全部
来源：http://dali.yuanzhike.top/Article/details/gtgtzbdkpu.html

SELECT * FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxgmhtch.html

[Q16] 查询指定列
来源：http://dali.xinyue.icu/Article/details/gtczyyxibd.html

SELECT id, name FROM users;
来源：http://dali.yueranfly.top/Article/details/gtwdmkwvay.html

[Q17] 条件查询
来源：http://dali.xinyue.icu/Article/details/gtorusvubq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtnkbgdtsp.html

[Q18] 模糊匹配
来源：http://dali.tianlin.xyz/Article/details/gtjvqqrcbm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.kuanghao11.cn/Article/details/gttkfrsfjv.html

[Q19] 范围查询
来源：http://dali.yuxming.cn/Article/details/gtuydtxcjt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.feifeiyinyue.top/Article/details/gtugmqcesn.html

[Q20] IN 列表
来源：http://dali.jyoumei.cn/Article/details/gtivsjanyb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gogol.net.cn/Article/details/gtuipdxfsb.html

[Q21] 空值判断
来源：http://dali.shzxlz.cn/Article/details/gtbievmkyw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxinkj.top/Article/details/gtpqvmytua.html

[Q22] 排序
来源：http://dali.aizwys.cn/Article/details/gtyklanfvf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.dashuyun.cn/Article/details/gtpqbjbmid.html

[Q23] 分页
来源：http://dali.shanyushiyangkeji.top/Article/details/gticdbaeax.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yvedp.cn/Article/details/gtvqwuilvn.html

[Q24] 去重
来源：http://dali.jianghu66.top/Article/details/gtmtzvxgek.html

SELECT DISTINCT city FROM users;
来源：http://dali.316326.xyz/Article/details/gtyxyjrtde.html

[Q25] 只取前 N 条
来源：http://dali.yvedp.cn/Article/details/gtyizevoee.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daria6918.cn/Article/details/gtasqcanxa.html

[Q26] 计数
来源：http://dali.smart0.xyz/Article/details/gtcxemwcyr.html

SELECT COUNT(*) FROM users;
来源：http://dali.sweek.top/Article/details/gtzjtempag.html

[Q27] 条件计数
来源：http://dali.shzxlz.cn/Article/details/gtzxdxuatv.html


<!-- 参考信息 -->