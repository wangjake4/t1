代发 wailian999

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gtemkuhjjd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtvjimqijm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtcayjepju.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhongyouzk.top/Article/details/gtiiirrtyr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtalsjamlq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tianlin.xyz/Article/details/gtmiueldiy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gtlvphklaf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtgtvnugni.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtauwnjnic.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gtiftrknem.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.redwolf501.top/Article/details/gtnfseqejd.html

Go:   slices.Sort(arr)
来源：http://dali.cucudq.cn/Article/details/gtevfwrwoj.html

Ruby: arr.sort
来源：http://dali.sxryk.cn/Article/details/gtvprfsgjg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aibaodan.cn/Article/details/gtuxingafp.html

[N03] 快速排序（分治示例）
来源：http://dali.shuidangran.top/Article/details/gtkphnunkk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xylfe.cn/Article/details/gtmzjyoent.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cheryme.top/Article/details/gtkvqcsdbg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gthzlgmifq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gtaeuwwvox.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.pengpengdd.cyou/Article/details/gtebfeeqhf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nanxuanxn.top/Article/details/gtmuonybmk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hnqzz.top/Article/details/gtjadeoxca.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hysaishi.cn/Article/details/gtkjegzteo.html

[N04] 斐波那契数列
来源：http://dali.cheryme.top/Article/details/gtwmxfbvhc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gtfrlwvblg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gtolealdci.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtetcveggv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtuqlzomdl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pengpengdd.cyou/Article/details/gtpvlrfbbh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.feifeiyinyue.top/Article/details/gtedfiydus.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gtjwprreqp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtjcauvxvm.html

[N05] 最大公约数
来源：http://dali.smart0.xyz/Article/details/gtttaljzwx.html

Py:   math.gcd(a, b)
来源：http://dali.sysykeji.top/Article/details/gtwpdzpryt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zdqjudy.top/Article/details/gtxfkhcktj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gtroovhbnr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gtxwmqsefj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guowangkeji.top/Article/details/gtqltsnobq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ybcxt.top/Article/details/gtftikgyvt.html

Ruby: a.gcd(b)
来源：http://dali.cdnleiting.top/Article/details/gtsggfynhp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nanxinkj.top/Article/details/gtvbxyhubq.html

[N06] 判断回文字符串
来源：http://dali.sxryk.cn/Article/details/gtoipuznlx.html

Py:   s == s[::-1]
来源：http://dali.316326.xyz/Article/details/gtdgohysof.html

PHP:  $s === strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gttjlucerg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gttxeypgtm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtxjgkhdup.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cheryme.top/Article/details/gtrpwjeirf.html

Go:   // 双指针从两端比较
来源：http://dali.aizwys.cn/Article/details/gtfmayowkn.html

Ruby: s == s.reverse
来源：http://dali.shuidangran.top/Article/details/gtgcrsplty.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gtleibuovw.html

[N07] 两数之和（返回下标）
来源：http://dali.snrcjt.cn/Article/details/gtdbbpjuzq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ehwqpu.com/Article/details/gtvrwxuzni.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sufxvd.cn/Article/details/gtythkuaiw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.redwolf501.top/Article/details/gtwfoawvre.html

TS:   // 手写 Map<string, number>
来源：http://dali.316326.xyz/Article/details/gticadkydk.html

Java: // 手写 HashMap
来源：http://dali.hongshengwenyu.top/Article/details/gtmyjyigig.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigufen.top/Article/details/gtfcbyazzv.html

Ruby: // 手写 Hash
来源：http://dali.hysaishi.cn/Article/details/gtuzdwcluj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yvedp.cn/Article/details/gtxwfkyryl.html

[N08] 生成全排列
来源：http://dali.bjfxy.top/Article/details/gtctewpsfl.html

Py:   itertools.permutations(arr)
来源：http://dali.9152youxi.cn/Article/details/gtwspcjowk.html

PHP:  // 手写递归交换
来源：http://dali.nanxinkj.top/Article/details/gtesslnfxs.html

JS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtppubmnar.html

TS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtgmezuqmh.html

Java: // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gteyogyiqj.html

Go:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtekbgcjir.html

Ruby: arr.permutation.to_a
来源：http://dali.bjfxy.top/Article/details/gtboeidxfz.html

C#:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtvtixruxz.html

[N09] 栈与队列
来源：http://dali.yuanzhike.top/Article/details/gtaoqjdfxp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cucudq.cn/Article/details/gtpfmmbren.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.fzhhl.top/Article/details/gtdlhqnfpa.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtfksrjuyk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fzhhl.top/Article/details/gtmuttpdzj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tanke756.top/Article/details/gtqxvdserq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigfzy.top/Article/details/gtayaiixeq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gtswsfypiu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yuanzhike.top/Article/details/gtjcoauikg.html

[N10] 链表节点定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfoqicigr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.iojbl.cn/Article/details/gtcmkxbutt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ivvv.top/Article/details/gtgwrarlwg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fzhhl.top/Article/details/gtkwxsofdi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.redwolf501.top/Article/details/gtkcnqecmw.html

Java: class Node { int v; Node next; }
来源：http://dali.chenzaomai.com/Article/details/gtzsveqehm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hongshengwenyu.top/Article/details/gtbyzpymza.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cheryme.top/Article/details/gtnqhcpggl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hywenlv.cn/Article/details/gtkycluzpg.html

[N11] 二叉树中序遍历
来源：http://dali.aibaodan.cn/Article/details/gtngvqnfvx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnqzz.top/Article/details/gtucirwskw.html

PHP:  // 手写递归函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgncpcnqh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gtdcyidaib.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gtjwkalwqs.html

Java: // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtbgrnrgqj.html

Go:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gtazhvuyzk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.bjfxy.top/Article/details/gtvqdishtw.html

C#:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gtyijunnna.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.bjfxy.top/Article/details/gthfoxrhpe.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangtech.top/Article/details/gtdosqvzrv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aibaodan.cn/Article/details/gtaxlshumw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gtvvynshnr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pycfn.com/Article/details/gtunnfjycj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gtxuooztka.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yuanzhike.top/Article/details/gtsmgniyoz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.c1oappe.top/Article/details/gtxkmzwvlc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxkxnruf.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtxpqsbtca.html

O. 并发与异步
来源：http://dali.gaohongyu789.top/Article/details/gtvttfkrba.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtmaovqwim.html

[O01] 启动一个线程
来源：http://dali.quarkkingdee.top/Article/details/gtjuronfyb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hongshengwenyu.top/Article/details/gtjtonowou.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.svipenyu.cn/Article/details/gtnxkluovk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.birdmap.top/Article/details/gtqmrwlntr.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gtjsiykpta.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhiwuduotai.top/Article/details/gturmzpphh.html

Go:   go f()
来源：http://dali.wangdashe.top/Article/details/gtzngbrcrt.html

Ruby: Thread.new { f }
来源：http://dali.cheryme.top/Article/details/gtsjisdqzt.html

C#:   Task.Run(() => F());
来源：http://dali.tianlin.xyz/Article/details/gtpxvnbjnl.html

[O02] 使用线程池
来源：http://dali.hongshengwenyu.top/Article/details/gtzospakgk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxinkj.top/Article/details/gtcfeyvgjd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cheryme.top/Article/details/gtnjiroekq.html

JS:   // worker_threads 线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqbkkztr.html

TS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gtmllgxhnc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgfzy.top/Article/details/gttuivgmgb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hysaishi.cn/Article/details/gtpmhxmmnw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aibaodan.cn/Article/details/gtcpzyptpz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xylfe.cn/Article/details/gtmeebhjzv.html

[O03] 加锁保护共享数据
来源：http://dali.yueranfly.top/Article/details/gtiybrbwtl.html

Py:   with lock: shared += 1
来源：http://dali.tianlin.xyz/Article/details/gtdkbmjaro.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zycfv.cn/Article/details/gtjkjdpydt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhiwuduotai.top/Article/details/gtxkvxjhiy.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gtyspfydld.html

Java: synchronized (this) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gtdcufoycx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gotoacloud.top/Article/details/gtorhyhjzf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shangyingyoupin.top/Article/details/gtvfryptiw.html

C#:   lock (gate) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gtpjjlkoee.html

[O04] 定义异步函数并等待
来源：http://dali.shzxlz.cn/Article/details/gtafzejslh.html

Py:   async def f():⏎    await g()
来源：http://dali.cucudq.cn/Article/details/gtzihhrbyr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhongyouzk.top/Article/details/gtwfmrghmq.html

JS:   async function f() { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gtpgbcuoyk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gtjatwadwc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hnqzz.top/Article/details/gtiolbghxr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hongshengwenyu.top/Article/details/gtyutszzza.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hfpthk.cn/Article/details/gtopacebzu.html

C#:   async Task F() { await G(); }
来源：http://dali.yuanzhike.top/Article/details/gtwxuadzwt.html

[O05] 并发执行并等待全部完成
来源：http://dali.ydzc1.top/Article/details/gtjdjrckmz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nanxuanxn.top/Article/details/gtmvhbxzvo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shangyingyoupin.top/Article/details/gtlnveyjwo.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtcnvizkia.html

TS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gtbrcquztb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zycfv.cn/Article/details/gtgrpexvox.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tanke756.top/Article/details/gtztfdlmpo.html

Ruby: threads.map(&:join)
来源：http://dali.wangdashe.top/Article/details/gtvmdgjljn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nwbrower.top/Article/details/gtpvwilwvd.html

[O06] 使用进程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygjtfuca.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ehwqpu.com/Article/details/gtyltpykmt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenjidiqi.icu/Article/details/gtxjmohhyh.html

JS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gtqvxxdasa.html

TS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gtmpaylujf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cheryme.top/Article/details/gtzacneprw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shangyingyoupin.top/Article/details/gtoaiqqlbh.html

Ruby: // fork 块
来源：http://dali.daria6918.cn/Article/details/gthchovfdj.html

C#:   Parallel.For
来源：http://dali.dianchejie.cn/Article/details/gtcncnjemx.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtnvalpfja.html

P. 常用工具函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtptejldov.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtfrrqmxjs.html

[P01] 生成 UUID
来源：http://dali.sweek.top/Article/details/gttdgyqjxq.html

Py:   str(uuid.uuid4())
来源：http://dali.tanke756.top/Article/details/gtxqsoptsd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sysykeji.top/Article/details/gtcavarqyj.html

JS:   crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gtlssgnkvs.html

TS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gtyfaljlil.html

Java: UUID.randomUUID().toString()
来源：http://dali.0kj1m.cn/Article/details/gtlyzzkjul.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenlongwang.top/Article/details/gtqmcnqcux.html

Ruby: SecureRandom.uuid
来源：http://dali.nwbrower.top/Article/details/gtfsdgubal.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yonumen.top/Article/details/gtjmzxjyic.html

[P02] MD5 / SHA256 摘要
来源：http://dali.9152youxi.cn/Article/details/gtsvwbhwgd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangdashe.top/Article/details/gtqyperdbb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhengqikj.top/Article/details/gtkkvsjwmm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ydzc1.top/Article/details/gteyotbbvo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnqzz.top/Article/details/gtbtyuhttb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.meibo888.top/Article/details/gtntqmihjl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jiagoushi.top/Article/details/gtpbtwmysq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ydzc1.top/Article/details/gtkzqzxmdr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.birdmap.top/Article/details/gtrqpgxrqc.html

[P03] 生成短随机字符串
来源：http://dali.yj20258888.top/Article/details/gtbgrilpjc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yvedp.cn/Article/details/gtktebtqmo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenzaomai.com/Article/details/gthamvlaun.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbfxkcjc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gtyqeuhcqn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jianghu66.top/Article/details/gtkanxabee.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ydzc1.top/Article/details/gtrhgdxrci.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinqigufen.top/Article/details/gtyrypyyek.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.quarkkingdee.top/Article/details/gtuwltvhhi.html

[P04] 求长度
来源：http://dali.jlsjyb.cn/Article/details/gtemknmlxd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shuidangran.top/Article/details/gtrvmsjoju.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gthkthhxhu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gtqfnqoimz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sxryk.cn/Article/details/gtpmhyhiag.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tianlin.xyz/Article/details/gtrxzusnze.html

Go:   len(arr);  len(m)
来源：http://dali.fengsongda.top/Article/details/gtqigmimsd.html

Ruby: x.length;  x.size
来源：http://dali.yongpay.top/Article/details/gtzcflhgcr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sufxvd.cn/Article/details/gtvwozhvsn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yangfankeji.com/Article/details/gtarzzznxs.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.bjfxy.top/Article/details/gtsqysvpfh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daria6918.cn/Article/details/gtsoamdnkw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.andypj.xyz/Article/details/gtmbvgvaav.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenlongwang.top/Article/details/gtidiroltt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fengsongda.top/Article/details/gtbstdrafs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tian-w.cn/Article/details/gtemqxqdqm.html

Ruby: a == b
来源：http://dali.redwolf501.top/Article/details/gtqsgwrqsx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daxiang520.top/Article/details/gthidktqiu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ybcxt.top/Article/details/gttugupddz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fengsongda.top/Article/details/gtefyiipnc.html

PHP:  if (empty($x)) {}
来源：http://dali.redwolf501.top/Article/details/gtvetrdjvh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ydzc1.top/Article/details/gtxjxytdot.html

TS:   if (x == null) {}
来源：http://dali.hysaishi.cn/Article/details/gtmtzdmfyi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ydzc1.top/Article/details/gtjwmvkixm.html

Go:   if x == nil {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemhbntgl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.fzhhl.top/Article/details/gtkqujymma.html

C#:   if (x is null) {}
来源：http://dali.xinyue.icu/Article/details/gtcqorjkkg.html

[P07] 防抖与节流
来源：http://dali.xuetiantiany.cn/Article/details/gtvwafydbh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hnqzz.top/Article/details/gtlkfuxrzm.html

PHP:  // 手写时间戳比较
来源：http://dali.jqgufenzy.top/Article/details/gtlqzjmaap.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gtaybsskvc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gtnptxnuie.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tanke756.top/Article/details/gtlzoghqrp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.dianchejie.cn/Article/details/gtuywuzuec.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yueranfly.top/Article/details/gtdeclbpxa.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ivvv.top/Article/details/gtfggglecz.html

[P08] 处理浮点精度问题
来源：http://dali.hongshengwenyu.top/Article/details/gtxfdkncws.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gaohongyu789.top/Article/details/gtsfsbdwkk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuanzx.com/Article/details/gtahzhvhsx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yueranfly.top/Article/details/gtvjjkvpwe.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.svipenyu.cn/Article/details/gtfebprriv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.feifeiyinyue.top/Article/details/gtszxsbueg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnqzz.top/Article/details/gtrcgycayx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yueranfly.top/Article/details/gtfjygodmt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.mhx1999.top/Article/details/gtisgbgkbt.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfoyrlndc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.feifeiyinyue.top/Article/details/gtsdkucefn.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtqixuhiof.html

[Q01] 创建表
来源：http://dali.hnxiangtu.top/Article/details/gtxiwdzgsh.html

CREATE TABLE users (
来源：http://dali.ybcxt.top/Article/details/gtuyncdgmm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258888.top/Article/details/gtfgzfcrhk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gtlpukrblr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.havefunace.top/Article/details/gtjyffspfb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhengqikj.top/Article/details/gtudggyiip.html

);
来源：http://dali.xylfe.cn/Article/details/gtuuznkxky.html

[Q02] 创建带外键的表
来源：http://dali.tanke756.top/Article/details/gtlkwqpzyy.html

CREATE TABLE orders (
来源：http://dali.meibo888.top/Article/details/gtfeadtydj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gtzwmhtmhu.html

user_id INT NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gtjxkngwxv.html

amount DECIMAL(10, 2),
来源：http://dali.0kj1m.cn/Article/details/gtbyeamqcx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yueranfly.top/Article/details/gtpbasqxhh.html

);
来源：http://dali.tian-w.cn/Article/details/gtvxykgbpl.html

[Q03] 增加列
来源：http://dali.shuidangran.top/Article/details/gtyzkpymyg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.aibaodan.cn/Article/details/gtoyadmeqs.html

[Q04] 修改列类型
来源：http://dali.zhixingplan.top/Article/details/gtuspkkasx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ydzc1.top/Article/details/gtxdwzwcfk.html

[Q05] 重命名列
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqqunjzf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygpdtkob.html

[Q06] 删除列
来源：http://dali.yvedp.cn/Article/details/gtyyenejgo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cheryme.top/Article/details/gtpailfvml.html

[Q07] 删除表
来源：http://dali.snrcjt.cn/Article/details/gtsfolvbgh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shuidangran.top/Article/details/gtwznvkovh.html

[Q08] 创建普通索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtclegltdg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngthpnru.html

[Q09] 创建唯一索引
来源：http://dali.jlsjyb.cn/Article/details/gtagauopil.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gtclaimbor.html

[Q10] 插入单行
来源：http://dali.nanxuanxn.top/Article/details/gtrbyanlpt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtilyrwgky.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjyjhdgf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.9152youxi.cn/Article/details/gtcrhaqbei.html

[Q12] 插入后取自增 ID
来源：http://dali.zycfv.cn/Article/details/gtyoxwtfum.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yueranfly.top/Article/details/gtcherrsqe.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cdnleiting.top/Article/details/gtthmatuvc.html

[Q13] 忽略重复插入
来源：http://dali.jqgfzy.top/Article/details/gtgdulguvq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jqgfzy.top/Article/details/gtngxdvzxa.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjuakjwe.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhixingplan.top/Article/details/gtfqssaaws.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sysykeji.top/Article/details/gttmjeyvhn.html

[Q15] 查询全部
来源：http://dali.gzhubu.top/Article/details/gtkcwdimcf.html

SELECT * FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtndemvluj.html

[Q16] 查询指定列
来源：http://dali.aizwys.cn/Article/details/gtucniybqw.html

SELECT id, name FROM users;
来源：http://dali.wangdashe.top/Article/details/gtrxmptuzx.html

[Q17] 条件查询
来源：http://dali.nanxinkj.top/Article/details/gtdqnoxihb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gogol.net.cn/Article/details/gtnwjsjnta.html

[Q18] 模糊匹配
来源：http://dali.aibaodan.cn/Article/details/gttvrivwen.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sufxvd.cn/Article/details/gtrwdimqms.html

[Q19] 范围查询
来源：http://dali.meibo888.top/Article/details/gtaqrafvsd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gotoacloud.top/Article/details/gthcilzqlp.html

[Q20] IN 列表
来源：http://dali.hammf.cn/Article/details/gtgqrwjulw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.316326.xyz/Article/details/gtuyecsvgt.html

[Q21] 空值判断
来源：http://dali.zhongyouzk.top/Article/details/gtcpcwftam.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gtxxczpxwa.html

[Q22] 排序
来源：http://dali.cucudq.cn/Article/details/gtxdgfeorc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jyoumei.cn/Article/details/gtofaqcocw.html

[Q23] 分页
来源：http://dali.dashuyun.cn/Article/details/gtglktbcrl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.fzhhl.top/Article/details/gtuambwjxp.html

[Q24] 去重
来源：http://dali.xziqi.cn/Article/details/gtmjiwauto.html

SELECT DISTINCT city FROM users;
来源：http://dali.xinyue.icu/Article/details/gtbppnmozu.html

[Q25] 只取前 N 条
来源：http://dali.chenzaomai.com/Article/details/gtdtwraaqh.html


<!-- 参考信息 -->