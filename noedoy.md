代发 wailian999

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gtdeubiobh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gthvwpavfh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zycfv.cn/Article/details/gticxtjcib.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangdashe.top/Article/details/gtndrvvpib.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtxixrzyzh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hysaishi.cn/Article/details/gtiflqlcrr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gtslnruyax.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ybcxt.top/Article/details/gtnnwjperb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gtoihkoxuv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gtkomnsmjq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.birdmap.top/Article/details/gtnkclzrie.html

Go:   slices.Sort(arr)
来源：http://dali.sufxvd.cn/Article/details/gtnunkbtgh.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gtcjpovnzd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuanzx.com/Article/details/gtvypiqrhy.html

[N03] 快速排序（分治示例）
来源：http://dali.haohaochexian.top/Article/details/gtfwfzdkhl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jyoumei.cn/Article/details/gtgxoyzegk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuxming.cn/Article/details/gtlurjwafg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gtwushbitl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.redwolf501.top/Article/details/gthgfgualy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sufxvd.cn/Article/details/gtwjmcrdft.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangshuangyany.cn/Article/details/gtbbrljgir.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hfpthk.cn/Article/details/gtielwipuk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenlongwang.top/Article/details/gtdvyiqxze.html

[N04] 斐波那契数列
来源：http://dali.wangshuangyany.cn/Article/details/gtptvjcrgi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtjkrciamn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xylfe.cn/Article/details/gtyzfwjhew.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtaftnvjkl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtnjzivkhk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gtzkwtxarw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ybcxt.top/Article/details/gtzlfzfpke.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gtisfzypgk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtoopofbkc.html

[N05] 最大公约数
来源：http://dali.yongpay.top/Article/details/gtxnvftpgp.html

Py:   math.gcd(a, b)
来源：http://dali.xuanzx.com/Article/details/gtuxgnxeqk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gotoacloud.top/Article/details/gtutiglzqh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqzcsyif.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gtmsysrxjg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenjidiqi.icu/Article/details/gtamgzcwki.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jianghu66.top/Article/details/gtcfdpxqri.html

Ruby: a.gcd(b)
来源：http://dali.gaohongyu789.top/Article/details/gtjkfrwfdt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yonumen.top/Article/details/gtblusfdqt.html

[N06] 判断回文字符串
来源：http://dali.yuxming.cn/Article/details/gtfsboutia.html

Py:   s == s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gtchllefha.html

PHP:  $s === strrev($s);
来源：http://dali.yongpay.top/Article/details/gtvcolaadw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtmtcwqwrv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtdapuinnq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.iojbl.cn/Article/details/gtamqnxzoo.html

Go:   // 双指针从两端比较
来源：http://dali.zycfv.cn/Article/details/gtxaredmuj.html

Ruby: s == s.reverse
来源：http://dali.jyoumei.cn/Article/details/gtascrlvto.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gtflvxylug.html

[N07] 两数之和（返回下标）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsifgpgcj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jiagoushi.top/Article/details/gticyreegu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuetiantiany.cn/Article/details/gtelvjepye.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aibaodan.cn/Article/details/gtbeedrbhx.html

TS:   // 手写 Map<string, number>
来源：http://dali.gotoacloud.top/Article/details/gtsyuidjpz.html

Java: // 手写 HashMap
来源：http://dali.kuanghao11.cn/Article/details/gtdwnwqgef.html

Go:   // 手写 map[int]int
来源：http://dali.redwolf501.top/Article/details/gtkhgeruqd.html

Ruby: // 手写 Hash
来源：http://dali.yj20258.top/Article/details/gtdfhcdcge.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hfpthk.cn/Article/details/gtsaonvlay.html

[N08] 生成全排列
来源：http://dali.zdqjudy.top/Article/details/gtscwqchkh.html

Py:   itertools.permutations(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxomkeqba.html

PHP:  // 手写递归交换
来源：http://dali.wangshuangyany.cn/Article/details/gtwcirhgnf.html

JS:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtfbokaukx.html

TS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtlpqtkmpe.html

Java: // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtuqzilitl.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazlovrgv.html

Ruby: arr.permutation.to_a
来源：http://dali.ybcxt.top/Article/details/gtyxicziej.html

C#:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwayontg.html

[N09] 栈与队列
来源：http://dali.fengsongda.top/Article/details/gtaxkargym.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gtezabgdng.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtaeoreglm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gtdyxlseep.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.iojbl.cn/Article/details/gtrefbhskt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gtigklzezy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigfzy.top/Article/details/gtfirqrqgk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtjkcjam.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.bjfxy.top/Article/details/gtmerwruhl.html

[N10] 链表节点定义
来源：http://dali.fzhhl.top/Article/details/gtqwsffpqg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xylfe.cn/Article/details/gtafsfnnjj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.kuanghao11.cn/Article/details/gtwoqtkinl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtutkyunqj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.smart0.xyz/Article/details/gtmlyuhzjd.html

Java: class Node { int v; Node next; }
来源：http://dali.hywenlv.cn/Article/details/gttqeaflan.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenzaomai.com/Article/details/gtqmjjjhin.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinqigufen.top/Article/details/gtxbiexatr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sysykeji.top/Article/details/gtkxpjtzgm.html

[N11] 二叉树中序遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtssciflqk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.mhx1999.top/Article/details/gtqpowxalc.html

PHP:  // 手写递归函数
来源：http://dali.jyoumei.cn/Article/details/gtjthwbjuw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnqzz.top/Article/details/gtzqzpwqvm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xziqi.cn/Article/details/gtcewemsyk.html

Java: // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfzaevlh.html

Go:   // 手写递归
来源：http://dali.aizwys.cn/Article/details/gtfwejbchx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tianlin.xyz/Article/details/gthoevbfyy.html

C#:   // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gtbrevjigx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhongyouzk.top/Article/details/gtcwvvbeyf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jyoumei.cn/Article/details/gtysxxtvuy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xuanzx.com/Article/details/gtsondyuga.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gtmtirifyi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hywenlv.cn/Article/details/gtnqelruyr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gaohongyu789.top/Article/details/gtprsqbieq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtoegulxpd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gtahgyzedd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gtzrmkozno.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtukwagalw.html

O. 并发与异步
来源：http://dali.tianlin.xyz/Article/details/gtkhjlanil.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtlkogazpa.html

[O01] 启动一个线程
来源：http://dali.hfpthk.cn/Article/details/gthmntndtf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sxryk.cn/Article/details/gtyxqbmqlh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cucudq.cn/Article/details/gttrzkkxmv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnxiangtu.top/Article/details/gtlsojmmwh.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gtfvarfqmp.html

Java: new Thread(() -> f()).start()
来源：http://dali.zdqjudy.top/Article/details/gtmuwzhcjs.html

Go:   go f()
来源：http://dali.yj202588.top/Article/details/gtqmwpvzce.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkcxrlsk.html

C#:   Task.Run(() => F());
来源：http://dali.zhiwuduotai.top/Article/details/gtnbsfivos.html

[O02] 使用线程池
来源：http://dali.yuxming.cn/Article/details/gtvdaskryi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xinyue.icu/Article/details/gtsxanicpo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hnxiangtu.top/Article/details/gtteiimwui.html

JS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gtiutuomza.html

TS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gtgewhmynk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.mhx1999.top/Article/details/gtydxjysuv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhaomingkeji.xyz/Article/details/gthcguegmj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhixingplan.top/Article/details/gttgyyhepn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jianghu66.top/Article/details/gtjfwdghzh.html

[O03] 加锁保护共享数据
来源：http://dali.bjfxy.top/Article/details/gtyfuvswns.html

Py:   with lock: shared += 1
来源：http://dali.ppjwa.cn/Article/details/gtfohrjsdh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gaohongyu789.top/Article/details/gtwqesrcgx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cucudq.cn/Article/details/gtlaphzxeu.html

TS:   // 同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsinptlgx.html

Java: synchronized (this) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhxitivf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgfzy.top/Article/details/gtcmgtdady.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.birdmap.top/Article/details/gtektfsvub.html

C#:   lock (gate) { shared++; }
来源：http://dali.redwolf501.top/Article/details/gtoydrvuvl.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gtipktcfje.html

Py:   async def f():⏎    await g()
来源：http://dali.kuanghao11.cn/Article/details/gtpzpyutnc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.iojbl.cn/Article/details/gtjljystav.html

JS:   async function f() { await g(); }
来源：http://dali.hnqzz.top/Article/details/gtftfneayp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.9152youxi.cn/Article/details/gtdlvrykbz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dashuyun.cn/Article/details/gttrahgehg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxinkj.top/Article/details/gtrciivhdr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sysykeji.top/Article/details/gtmdunrhhs.html

C#:   async Task F() { await G(); }
来源：http://dali.tian-w.cn/Article/details/gtusxpvpuf.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhiwuduotai.top/Article/details/gthnwaibjv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.9152youxi.cn/Article/details/gtdtwolsce.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cucudq.cn/Article/details/gtsisetpkp.html

JS:   await Promise.all(tasks)
来源：http://dali.cdnleiting.top/Article/details/gtollpxwue.html

TS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gtslxkyngx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttksqhvue.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhixingplan.top/Article/details/gtddqtewbn.html

Ruby: threads.map(&:join)
来源：http://dali.dashuyun.cn/Article/details/gtcibrelas.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gotoacloud.top/Article/details/gtuyfcpfok.html

[O06] 使用进程池
来源：http://dali.0kj1m.cn/Article/details/gthklslgox.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.kuanghao11.cn/Article/details/gtiwxhhvwv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ybcxt.top/Article/details/gtslnggeer.html

JS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gtrxrwqgxh.html

TS:   // child_process / cluster 模块
来源：http://dali.vqdsnc.cn/Article/details/gtuyaukskx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nwbrower.top/Article/details/gtpqoudtmg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hnxiangtu.top/Article/details/gtwtwkqvii.html

Ruby: // fork 块
来源：http://dali.jianghu66.top/Article/details/gtkrpxhery.html

C#:   Parallel.For
来源：http://dali.hysaishi.cn/Article/details/gtvaqumqgq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtzkxewzkm.html

P. 常用工具函数
来源：http://dali.chenzaomai.com/Article/details/gttqhtitzm.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtizrhdefo.html

[P01] 生成 UUID
来源：http://dali.gaohongyu789.top/Article/details/gtezxbmsuo.html

Py:   str(uuid.uuid4())
来源：http://dali.nanxuanxn.top/Article/details/gtooglbfir.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cheryme.top/Article/details/gtdijbauvb.html

JS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnidvcqlc.html

TS:   crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gtgrhsahri.html

Java: UUID.randomUUID().toString()
来源：http://dali.svipenyu.cn/Article/details/gthvjdawrl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ppjwa.cn/Article/details/gtzfmyemqr.html

Ruby: SecureRandom.uuid
来源：http://dali.tanke756.top/Article/details/gtpsvpiias.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yueranfly.top/Article/details/gtgpaasvow.html

[P02] MD5 / SHA256 摘要
来源：http://dali.havefunace.top/Article/details/gttzoytetg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.dianchejie.cn/Article/details/gtjmgjtkgs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daria6918.cn/Article/details/gtgazuxdma.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtwavjiihv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yongpay.top/Article/details/gtigvppvvp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtnxuyjvgi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxuanxn.top/Article/details/gtxvskljju.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigufen.top/Article/details/gtiwuffxvc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nwbrower.top/Article/details/gtnashcqae.html

[P03] 生成短随机字符串
来源：http://dali.hnxiangtu.top/Article/details/gtqueatvyv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhoulong.xyz/Article/details/gtggvouoya.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gaohongyu789.top/Article/details/gtqokfpqrc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtbfpnsnwe.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ehwqpu.com/Article/details/gtslxlpdds.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhengqikj.top/Article/details/gtwluntbhv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenlongwang.top/Article/details/gtdfpbvtfh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yuxming.cn/Article/details/gtjbypfzrj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.bjfxy.top/Article/details/gtvxkhinda.html

[P04] 求长度
来源：http://dali.chenzaomai.com/Article/details/gtgrhuoqqu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinqigufen.top/Article/details/gtzkzkftrm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtgquxozyq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gthdyjxspk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhongyouzk.top/Article/details/gtzatgwgio.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigfzy.top/Article/details/gtmubqlgsc.html

Go:   len(arr);  len(m)
来源：http://dali.tianlin.xyz/Article/details/gtiqkrzzjo.html

Ruby: x.length;  x.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gteeaofmwz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.daria6918.cn/Article/details/gtwylwntky.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tian-w.cn/Article/details/gtaavtjqbb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfaotqyvo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cdnleiting.top/Article/details/gtbfnfzker.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.mhx1999.top/Article/details/gtyassaxhw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfxlrobp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhixingplan.top/Article/details/gttcpkwkhy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtolzkcamh.html

Ruby: a == b
来源：http://dali.havefunace.top/Article/details/gtxmfifzni.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hongshengwenyu.top/Article/details/gtemnnuggj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.quarkkingdee.top/Article/details/gthpuhdceb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.bjfxy.top/Article/details/gtjkwdgdsp.html

PHP:  if (empty($x)) {}
来源：http://dali.bjfxy.top/Article/details/gtapolfgfo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.c1oappe.top/Article/details/gtsmkfosnv.html

TS:   if (x == null) {}
来源：http://dali.cdnleiting.top/Article/details/gtmsupmhuk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gtspbvnbsn.html

Go:   if x == nil {}
来源：http://dali.tian-w.cn/Article/details/gtletxtahg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dianchejie.cn/Article/details/gtzhnyjvwe.html

C#:   if (x is null) {}
来源：http://dali.fengsongda.top/Article/details/gtenrjnfjy.html

[P07] 防抖与节流
来源：http://dali.kuanghao11.cn/Article/details/gtobwldndr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jlsjyb.cn/Article/details/gtwukswtrb.html

PHP:  // 手写时间戳比较
来源：http://dali.bjfxy.top/Article/details/gtrdcpqiyb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gtekodybce.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gtpsiodgtt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hfpthk.cn/Article/details/gtubignnwp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xylfe.cn/Article/details/gtfimqeifo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jiagoushi.top/Article/details/gtoeempbar.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnqzz.top/Article/details/gtukbqavvs.html

[P08] 处理浮点精度问题
来源：http://dali.zhixingplan.top/Article/details/gtwzghsbef.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shzxlz.cn/Article/details/gtvvralvul.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ydzc1.top/Article/details/gtxoqvnpjm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.redwolf501.top/Article/details/gtddqylycv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gtsifcxqgl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.smart0.xyz/Article/details/gtknqlrtzo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tian-w.cn/Article/details/gtoetctlmf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yvedp.cn/Article/details/gtscetcesy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xylfe.cn/Article/details/gtntpjqrgl.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtgjoiseni.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.svipenyu.cn/Article/details/gtxwmlsxtk.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtstxcpmwn.html

[Q01] 创建表
来源：http://dali.sufxvd.cn/Article/details/gtdskwfapb.html

CREATE TABLE users (
来源：http://dali.andypj.xyz/Article/details/gtzomdadxk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aizwys.cn/Article/details/gtpkrxvzuh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shuidangran.top/Article/details/gtxfmkkwor.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nwbrower.top/Article/details/gtghvgauzp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.aizwys.cn/Article/details/gtloxyefjq.html

);
来源：http://dali.pycfn.com/Article/details/gtpgnzywnp.html

[Q02] 创建带外键的表
来源：http://dali.xinyue.icu/Article/details/gtfcsykkmr.html

CREATE TABLE orders (
来源：http://dali.cashguo.top/Article/details/gtdhghgldq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pengpengdd.cyou/Article/details/gtbwkquxzj.html

user_id INT NOT NULL,
来源：http://dali.haohaochexian.top/Article/details/gtyavehjcy.html

amount DECIMAL(10, 2),
来源：http://dali.nanxinkj.top/Article/details/gtxhlgyxie.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhengqikj.top/Article/details/gtmwyqnyxy.html

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgklbpsix.html

[Q03] 增加列
来源：http://dali.guannengcc.top/Article/details/gtarwwrhxv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yuxming.cn/Article/details/gtawqcsipa.html

[Q04] 修改列类型
来源：http://dali.havefunace.top/Article/details/gtfzabtuye.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sufxvd.cn/Article/details/gtksyhymka.html

[Q05] 重命名列
来源：http://dali.tanke756.top/Article/details/gtzaouujch.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jianghu66.top/Article/details/gtwllgxvek.html

[Q06] 删除列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtrahqvj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.9152youxi.cn/Article/details/gtdiualrkd.html

[Q07] 删除表
来源：http://dali.ivvv.top/Article/details/gtihqfxohu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fzhhl.top/Article/details/gtvntizmvp.html

[Q08] 创建普通索引
来源：http://dali.hammf.cn/Article/details/gtynkhahjy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gtwuzclwdi.html

[Q09] 创建唯一索引
来源：http://dali.xylfe.cn/Article/details/gtgakjnelo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.dianchejie.cn/Article/details/gtkfwpuhdl.html

[Q10] 插入单行
来源：http://dali.iojbl.cn/Article/details/gtnphbyrrn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gtivyswann.html

[Q11] 一次插入多行
来源：http://dali.birdmap.top/Article/details/gtgafkilmw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258.top/Article/details/gtmkocqvqq.html

[Q12] 插入后取自增 ID
来源：http://dali.svipenyu.cn/Article/details/gtmhwisfdm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cdnleiting.top/Article/details/gtduazybyk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xziqi.cn/Article/details/gtdhbmpwnd.html

[Q13] 忽略重复插入
来源：http://dali.jqgfzy.top/Article/details/gtnoqmzwbs.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.redwolf501.top/Article/details/gtgyenvgyg.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxuanxn.top/Article/details/gtdvmhvyme.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.c1oappe.top/Article/details/gtgrxskjsg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gotoacloud.top/Article/details/gttaxcxeqx.html

[Q15] 查询全部
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrelmxts.html

SELECT * FROM users;
来源：http://dali.yongpay.top/Article/details/gtkzgoebyu.html

[Q16] 查询指定列
来源：http://dali.hnxiangtu.top/Article/details/gtvqqnztcp.html

SELECT id, name FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtziufodgp.html

[Q17] 条件查询
来源：http://dali.hysaishi.cn/Article/details/gtxyhbtbrm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cucudq.cn/Article/details/gtafbrrlkl.html

[Q18] 模糊匹配
来源：http://dali.hfpthk.cn/Article/details/gtzyjdwgph.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenzaomai.com/Article/details/gtgobjakhx.html

[Q19] 范围查询
来源：http://dali.jinqigufen.top/Article/details/gtiecpihwm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hfpthk.cn/Article/details/gtrknpwifq.html

[Q20] IN 列表
来源：http://dali.yongpay.top/Article/details/gtuutbsxgj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfyrxoov.html

[Q21] 空值判断
来源：http://dali.0kj1m.cn/Article/details/gtqrfkhjyd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsexxfljj.html

[Q22] 排序
来源：http://dali.snrcjt.cn/Article/details/gtqgzquans.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnxiangtu.top/Article/details/gtdtutxuus.html

[Q23] 分页
来源：http://dali.daria6918.cn/Article/details/gttclrvgza.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xylfe.cn/Article/details/gtqzvrxugn.html

[Q24] 去重
来源：http://dali.svipenyu.cn/Article/details/gtdmuybizd.html

SELECT DISTINCT city FROM users;
来源：http://dali.pycfn.com/Article/details/gtzvhqncyv.html

[Q25] 只取前 N 条
来源：http://dali.fzhhl.top/Article/details/gtlslfvctc.html


<!-- 参考信息 -->