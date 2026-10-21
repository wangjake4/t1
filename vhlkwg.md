代发 wailian999

[N01] 二分查找（有序数组）
来源：http://dali.jqgufenzy.top/Article/details/gtcbangudr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtweqticwq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fengsongda.top/Article/details/gtoidkwmvb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gtttbvarqp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuanzhike.top/Article/details/gtvofgkyxn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtkwdkccfk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtyfniuwbl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.pengpengdd.cyou/Article/details/gttucsbejp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gtbzxwjopn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ehwqpu.com/Article/details/gttgiwwbdh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.redwolf501.top/Article/details/gtcisoiloh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.smart0.xyz/Article/details/gtiabburib.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtfchwqmet.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gtpkuwohkn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cucudq.cn/Article/details/gtdsnigvbz.html

Go:   slices.Sort(arr)
来源：http://dali.jqgfzy.top/Article/details/gtjqbhdmha.html

Ruby: arr.sort
来源：http://dali.gzhubu.top/Article/details/gtsovdpgfz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yangfankeji.com/Article/details/gtnnpldzcm.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigfzy.top/Article/details/gttsvpmzwh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxpmxtzm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shangyingyoupin.top/Article/details/gtwqgfjfoc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.quarkkingdee.top/Article/details/gtojtzakkf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.quarkkingdee.top/Article/details/gtyhvuawjb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fzhhl.top/Article/details/gtiepmuaji.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhongyouzk.top/Article/details/gtgghxlxek.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj202588.top/Article/details/gthlbfbbli.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yonumen.top/Article/details/gtcmpzqjay.html

[N04] 斐波那契数列
来源：http://dali.nanxuanxn.top/Article/details/gtacqmsfkn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gttgkrcqqm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sysykeji.top/Article/details/gtfvbtlxey.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtkmgzgdxh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtxacsfari.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gtvppnzabf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.0kj1m.cn/Article/details/gtwokiwthy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gtokoipaue.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtculbsqzb.html

[N05] 最大公约数
来源：http://dali.guowangkeji.top/Article/details/gtghltzweh.html

Py:   math.gcd(a, b)
来源：http://dali.cdnleiting.top/Article/details/gttdxldoma.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xziqi.cn/Article/details/gtyvdjpmky.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gtlxrbhmcy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmgbyccwa.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.kuanghao11.cn/Article/details/gtapvlggpz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yanxiufei.cn/Article/details/gttagygzpn.html

Ruby: a.gcd(b)
来源：http://dali.cqqwz.cn/Article/details/gtgvuxljwf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fengsongda.top/Article/details/gtmkrwmzbe.html

[N06] 判断回文字符串
来源：http://dali.yangfankeji.com/Article/details/gtorbeceax.html

Py:   s == s[::-1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqwlocwg.html

PHP:  $s === strrev($s);
来源：http://dali.fengsongda.top/Article/details/gttxbkvwmp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtnxmmssnl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtqzdrujrh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cashguo.top/Article/details/gtwiuizgta.html

Go:   // 双指针从两端比较
来源：http://dali.redwolf501.top/Article/details/gtqwfvouxg.html

Ruby: s == s.reverse
来源：http://dali.svipenyu.cn/Article/details/gtghoxmcxz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gttvwvzlrh.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258888.top/Article/details/gtytvwlhta.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ppjwa.cn/Article/details/gtyhsimjfm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuetiantiany.cn/Article/details/gtqerjiujj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuanzhike.top/Article/details/gtlywwjwyr.html

TS:   // 手写 Map<string, number>
来源：http://dali.redwolf501.top/Article/details/gtbrlikfwd.html

Java: // 手写 HashMap
来源：http://dali.dianchejie.cn/Article/details/gtqscelhwg.html

Go:   // 手写 map[int]int
来源：http://dali.nanxinkj.top/Article/details/gttegwllmp.html

Ruby: // 手写 Hash
来源：http://dali.yuanzhike.top/Article/details/gttgoymmtz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shuidangran.top/Article/details/gtfripxltk.html

[N08] 生成全排列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqtxltwt.html

Py:   itertools.permutations(arr)
来源：http://dali.zycfv.cn/Article/details/gtgyzxbnyr.html

PHP:  // 手写递归交换
来源：http://dali.wangshuangyany.cn/Article/details/gtnbpnxlbn.html

JS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtrszvludh.html

TS:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtpvaxqgxt.html

Java: // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlzwjinn.html

Go:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtghtxplgb.html

Ruby: arr.permutation.to_a
来源：http://dali.gotoacloud.top/Article/details/gtnelbhrmz.html

C#:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtpuvtoyfk.html

[N09] 栈与队列
来源：http://dali.andypj.xyz/Article/details/gtlfkzooas.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nwbrower.top/Article/details/gtsnrpwrpq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gtigfwfxyw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gtizdbxpys.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hammf.cn/Article/details/gtchhgwwnr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtaprvdtbm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fzhhl.top/Article/details/gtrrazubuq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuanzx.com/Article/details/gtzlwltczz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ybcxt.top/Article/details/gtckmnvmwu.html

[N10] 链表节点定义
来源：http://dali.shangyingyoupin.top/Article/details/gtvketzyao.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jlsjyb.cn/Article/details/gtnsbguzgj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.svipenyu.cn/Article/details/gtfdsxtbaz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yangfankeji.com/Article/details/gtybqkkqqr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhixingplan.top/Article/details/gthiijcadz.html

Java: class Node { int v; Node next; }
来源：http://dali.tianlin.xyz/Article/details/gtggnwltoj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ppjwa.cn/Article/details/gtlkavvpyx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sxryk.cn/Article/details/gtkpmlcdcy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ehwqpu.com/Article/details/gtvpemuqgu.html

[N11] 二叉树中序遍历
来源：http://dali.jqgfzy.top/Article/details/gtypembvnx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tanke756.top/Article/details/gtjlmabqgj.html

PHP:  // 手写递归函数
来源：http://dali.zhongyouzk.top/Article/details/gtppxctzyi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dashuyun.cn/Article/details/gttmawnrxb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gtveollyaq.html

Java: // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gtdwrsldmy.html

Go:   // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gtqonnodpk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqyvjsjf.html

C#:   // 手写递归
来源：http://dali.gzhubu.top/Article/details/gtouvtlsuc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sweek.top/Article/details/gtnvpeednq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.c1oappe.top/Article/details/gtavamoftg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.pengpengdd.cyou/Article/details/gtxlkhvazc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gtsqqgyehe.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gtcotbonwj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gtfuihtygn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenjidiqi.icu/Article/details/gtjvejzzhm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhengqikj.top/Article/details/gtejzcqvpb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxusgfzkl.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gttluklabn.html

O. 并发与异步
来源：http://dali.yangfankeji.com/Article/details/gtyntuvrvl.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtvrkrobgv.html

[O01] 启动一个线程
来源：http://dali.dianchejie.cn/Article/details/gtoqjxphgk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.feifeiyinyue.top/Article/details/gtfzhzkkpz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zycfv.cn/Article/details/gtrpalujjc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuxming.cn/Article/details/gtybkioazg.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gtfpzunapy.html

Java: new Thread(() -> f()).start()
来源：http://dali.sweek.top/Article/details/gttmawpgpn.html

Go:   go f()
来源：http://dali.hfpthk.cn/Article/details/gtyuampljy.html

Ruby: Thread.new { f }
来源：http://dali.yuanzhike.top/Article/details/gtrxxqyavi.html

C#:   Task.Run(() => F());
来源：http://dali.fengsongda.top/Article/details/gtatrqwlum.html

[O02] 使用线程池
来源：http://dali.mhx1999.top/Article/details/gtzphanlao.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.smart0.xyz/Article/details/gtcjqyvjcb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.svipenyu.cn/Article/details/gtwzbnbvft.html

JS:   // worker_threads 线程池
来源：http://dali.hnqzz.top/Article/details/gtoiyghdrh.html

TS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gtonponzsr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.snrcjt.cn/Article/details/gtnvmwktny.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangdashe.top/Article/details/gtrekwvjdv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tian-w.cn/Article/details/gtyjfonqbw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guannengcc.top/Article/details/gtvbgoqvop.html

[O03] 加锁保护共享数据
来源：http://dali.shangyingyoupin.top/Article/details/gtnfimnuxh.html

Py:   with lock: shared += 1
来源：http://dali.havefunace.top/Article/details/gtrmrbjhec.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhoulong.xyz/Article/details/gtpfewrtpd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hywenlv.cn/Article/details/gtuzcdpxdt.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gtkyhbmtyb.html

Java: synchronized (this) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gtoiwbauul.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtriccxxmx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xylfe.cn/Article/details/gtjclbgdyc.html

C#:   lock (gate) { shared++; }
来源：http://dali.tanke756.top/Article/details/gtlljvkznb.html

[O04] 定义异步函数并等待
来源：http://dali.yonumen.top/Article/details/gtlywkozfi.html

Py:   async def f():⏎    await g()
来源：http://dali.aizwys.cn/Article/details/gtcvklfwtp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jianghu66.top/Article/details/gtsfugryzz.html

JS:   async function f() { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtqoamreoc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ydzc1.top/Article/details/gtdleuwbrs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ppjwa.cn/Article/details/gttubcqkbj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dianchejie.cn/Article/details/gtggetdzdp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhixingplan.top/Article/details/gtgwvdeqfb.html

C#:   async Task F() { await G(); }
来源：http://dali.zdqjudy.top/Article/details/gtqoazrpdk.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuanzx.com/Article/details/gtlkuxgpwe.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangdashe.top/Article/details/gtvjnegath.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cucudq.cn/Article/details/gttlvnnesa.html

JS:   await Promise.all(tasks)
来源：http://dali.jiagoushi.top/Article/details/gtwrcfxago.html

TS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gtiljpjhwx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jqgfzy.top/Article/details/gtbzbxytbd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cdnleiting.top/Article/details/gtzlchvsbh.html

Ruby: threads.map(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gtepquqabo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj202588.top/Article/details/gtjflhrqda.html

[O06] 使用进程池
来源：http://dali.gotoacloud.top/Article/details/gtjzmzihce.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fengsongda.top/Article/details/gtebvollap.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gotoacloud.top/Article/details/gtpwxogsmq.html

JS:   // child_process / cluster 模块
来源：http://dali.yonumen.top/Article/details/gtcpgoxeqy.html

TS:   // child_process / cluster 模块
来源：http://dali.smart0.xyz/Article/details/gtbxfcfxvw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyehgqvuu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yangfankeji.com/Article/details/gtudhvqwlt.html

Ruby: // fork 块
来源：http://dali.shanyushiyangtech.top/Article/details/gthytluvcu.html

C#:   Parallel.For
来源：http://dali.bjfxy.top/Article/details/gtejqlsqub.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtruydnbuj.html

P. 常用工具函数
来源：http://dali.iojbl.cn/Article/details/gtkbwnlkre.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtcattctwt.html

[P01] 生成 UUID
来源：http://dali.nwbrower.top/Article/details/gtwztpztta.html

Py:   str(uuid.uuid4())
来源：http://dali.yuxming.cn/Article/details/gtiktxxnmf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxinkj.top/Article/details/gtwdasduwq.html

JS:   crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gtfkqhgnty.html

TS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gtatlmgewt.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258888.top/Article/details/gtbipcedue.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtxnyphl.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxuanxn.top/Article/details/gtozjkgnun.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tianlin.xyz/Article/details/gtljwwevux.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sweek.top/Article/details/gtpqarbixx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jyoumei.cn/Article/details/gtcuennnsd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yvedp.cn/Article/details/gtnxgyetau.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jianghu66.top/Article/details/gtbptjdqdm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangshuangyany.cn/Article/details/gtyolubwpj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtsetaltip.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.vqdsnc.cn/Article/details/gteffezwes.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgfzy.top/Article/details/gtuuktgsae.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pengpengdd.cyou/Article/details/gtvohrvsrg.html

[P03] 生成短随机字符串
来源：http://dali.hnqzz.top/Article/details/gtthvpvlag.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuetiantiany.cn/Article/details/gtloomvpfi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nwbrower.top/Article/details/gtcdygkcvr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dianchejie.cn/Article/details/gtmpyqwgrg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ppjwa.cn/Article/details/gthwoebhhi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sufxvd.cn/Article/details/gtvbmtikws.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.9152youxi.cn/Article/details/gtxnxzfhqr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnxiangtu.top/Article/details/gtlruafcll.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnqzz.top/Article/details/gtbyobrmng.html

[P04] 求长度
来源：http://dali.jianghu66.top/Article/details/gtsnrcymha.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hfpthk.cn/Article/details/gtqntdgmjd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtdmmgiwzd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jlsjyb.cn/Article/details/gthpwkcthi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sweek.top/Article/details/gtcjeomfyo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258.top/Article/details/gtfnlxmyke.html

Go:   len(arr);  len(m)
来源：http://dali.yuanzhike.top/Article/details/gtlmysakbp.html

Ruby: x.length;  x.size
来源：http://dali.pycfn.com/Article/details/gtdfnqqzpc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gtqfukbfjo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.iojbl.cn/Article/details/gtoixjdbqu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yonumen.top/Article/details/gtbyderwum.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.guowangkeji.top/Article/details/gtxshjzczc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shzxlz.cn/Article/details/gtsvcckckv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258888.top/Article/details/gtoaegusdf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shanyushiyangtech.top/Article/details/gttsvqpbcv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jianghu66.top/Article/details/gtqbglbwyc.html

Ruby: a == b
来源：http://dali.iojbl.cn/Article/details/gtgbcbkutz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.aibaodan.cn/Article/details/gtaturrwwe.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.dashuyun.cn/Article/details/gtfmotfsul.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.redwolf501.top/Article/details/gtotjenlpr.html

PHP:  if (empty($x)) {}
来源：http://dali.yueranfly.top/Article/details/gtnyluychq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258.top/Article/details/gtkmtqhqxe.html

TS:   if (x == null) {}
来源：http://dali.yangfankeji.com/Article/details/gtkxtetydc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sweek.top/Article/details/gtzmefetaq.html

Go:   if x == nil {}
来源：http://dali.0kj1m.cn/Article/details/gtchxomseg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yanxiufei.cn/Article/details/gtaxmjjiju.html

C#:   if (x is null) {}
来源：http://dali.cdnleiting.top/Article/details/gtwzvtfrct.html

[P07] 防抖与节流
来源：http://dali.tanke756.top/Article/details/gtverocmpa.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gaohongyu789.top/Article/details/gtlldhkmkp.html

PHP:  // 手写时间戳比较
来源：http://dali.aizwys.cn/Article/details/gtznbbsbkm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gtylyptcbn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwpunlkl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenzaomai.com/Article/details/gtbqnrklwc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.iojbl.cn/Article/details/gtfshzjiqn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hfpthk.cn/Article/details/gtzccxuggc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.pengpengdd.cyou/Article/details/gtrbjhpxvu.html

[P08] 处理浮点精度问题
来源：http://dali.316326.xyz/Article/details/gtyxakzogm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gogol.net.cn/Article/details/gtxagagpev.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hammf.cn/Article/details/gttpzgcfok.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.andypj.xyz/Article/details/gtryrjfdus.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yj202588.top/Article/details/gtpgbezdgp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daxiang520.top/Article/details/gtpybbfyig.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigfzy.top/Article/details/gtyzmylyfb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.c1oappe.top/Article/details/gtcdbbllku.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hfpthk.cn/Article/details/gtrzexphcw.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtukhgvjko.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.svipenyu.cn/Article/details/gtawijubpf.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtkpajwxgd.html

[Q01] 创建表
来源：http://dali.sysykeji.top/Article/details/gtlchcnenj.html

CREATE TABLE users (
来源：http://dali.chenlongwang.top/Article/details/gthapehczo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuanzhike.top/Article/details/gtroiewctk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gtxtngjyda.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hysaishi.cn/Article/details/gtztctueep.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jqgufenzy.top/Article/details/gtvzaezzdo.html

);
来源：http://dali.andypj.xyz/Article/details/gtkiprbomc.html

[Q02] 创建带外键的表
来源：http://dali.guannengcc.top/Article/details/gtkfxpjkip.html

CREATE TABLE orders (
来源：http://dali.jqgfzy.top/Article/details/gtpvfyebjl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gtizuubvjv.html

user_id INT NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gtaoaawada.html

amount DECIMAL(10, 2),
来源：http://dali.haohaochexian.top/Article/details/gtmvvewqgs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.fzhhl.top/Article/details/gtoqhisrgb.html

);
来源：http://dali.sweek.top/Article/details/gtjrnmznjr.html

[Q03] 增加列
来源：http://dali.andypj.xyz/Article/details/gtvdgbdxea.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sysykeji.top/Article/details/gtdbczllsv.html

[Q04] 修改列类型
来源：http://dali.dashuyun.cn/Article/details/gtcvyybklc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yangfankeji.com/Article/details/gtlvcyyacb.html

[Q05] 重命名列
来源：http://dali.bjfxy.top/Article/details/gtcrrsdvyi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sxryk.cn/Article/details/gtvnbobepc.html

[Q06] 删除列
来源：http://dali.c1oappe.top/Article/details/gtpfnvwnnl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cashguo.top/Article/details/gtexqomffz.html

[Q07] 删除表
来源：http://dali.fzhhl.top/Article/details/gtantdxlns.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjuinjuf.html

[Q08] 创建普通索引
来源：http://dali.zhixingplan.top/Article/details/gtvxaktjay.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.redwolf501.top/Article/details/gtyhhtjfeq.html

[Q09] 创建唯一索引
来源：http://dali.xziqi.cn/Article/details/gtwcmwspbp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gtsrfgsmtp.html

[Q10] 插入单行
来源：http://dali.sweek.top/Article/details/gtlxffcchm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258.top/Article/details/gtlywafsce.html

[Q11] 一次插入多行
来源：http://dali.guannengcc.top/Article/details/gtviqpmigq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yonumen.top/Article/details/gtqacexqme.html

[Q12] 插入后取自增 ID
来源：http://dali.yuxming.cn/Article/details/gtnmijxrue.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cqqwz.cn/Article/details/gtnvvkkwun.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.quarkkingdee.top/Article/details/gttscyxiet.html

[Q13] 忽略重复插入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqorjoxq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sysykeji.top/Article/details/gtabvuhakn.html

[Q14] 存在则更新（upsert）
来源：http://dali.cucudq.cn/Article/details/gtfcnbezac.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj20258.top/Article/details/gtkwahexir.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zycfv.cn/Article/details/gtyplhnvnr.html

[Q15] 查询全部
来源：http://dali.chenzaomai.com/Article/details/gtpzqacioe.html

SELECT * FROM users;
来源：http://dali.xziqi.cn/Article/details/gtcedkmizh.html

[Q16] 查询指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gtyuyhxanz.html

SELECT id, name FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezzatbcl.html

[Q17] 条件查询
来源：http://dali.cashguo.top/Article/details/gtjxrwkpar.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.andypj.xyz/Article/details/gthanjnxhj.html

[Q18] 模糊匹配
来源：http://dali.shuidangran.top/Article/details/gtevaiiioz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sysykeji.top/Article/details/gtgoeyasgx.html

[Q19] 范围查询
来源：http://dali.dianchejie.cn/Article/details/gtqrvttycz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.kuanghao11.cn/Article/details/gtbuwiiqzu.html

[Q20] IN 列表
来源：http://dali.cucudq.cn/Article/details/gtpvnorbqu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.0kj1m.cn/Article/details/gthbrlkdmz.html

[Q21] 空值判断
来源：http://dali.redwolf501.top/Article/details/gttoiazfsn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj202588.top/Article/details/gtheqhqrji.html

[Q22] 排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaaevxryx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.kuanghao11.cn/Article/details/gtikuqyvin.html

[Q23] 分页
来源：http://dali.fzhhl.top/Article/details/gtjqnzhlmd.html


<!-- 参考信息 -->