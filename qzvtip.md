代发 wailian999

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hongshengwenyu.top/Article/details/gtdowzgnnn.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtbzvempbx.html

N. 数据结构与算法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaoetouve.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtzvocwqrg.html

[N01] 二分查找（有序数组）
来源：http://dali.wangdashe.top/Article/details/gtykdzsnqs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtfxwjugqd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuxming.cn/Article/details/gtoysinnnj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gtjdycudxw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gtqrntgvcx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtntdrrffs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuanzx.com/Article/details/gteobsmedh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenlongwang.top/Article/details/gtltdqngbw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gthlswwyxf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenzaomai.com/Article/details/gthrtccdkj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.smart0.xyz/Article/details/gtwmmisgfd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hammf.cn/Article/details/gtiuhfffsi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gtxqjrekqs.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyifkrsnr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yangfankeji.com/Article/details/gtxalgozup.html

Go:   slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gtxmvgdald.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gttxdfgzzj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gthkcyvxdb.html

[N03] 快速排序（分治示例）
来源：http://dali.shuidangran.top/Article/details/gtjulxmvdu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.dashuyun.cn/Article/details/gtfxesredf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jiagoushi.top/Article/details/gtdoraemgx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gtmnrwpwul.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gttevmrlvy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aibaodan.cn/Article/details/gtfqhvlwyx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.pycfn.com/Article/details/gtkjahbbch.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.aizwys.cn/Article/details/gtopbpbarl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dashuyun.cn/Article/details/gtmxbdruie.html

[N04] 斐波那契数列
来源：http://dali.aizwys.cn/Article/details/gtpgrdaysh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.vqdsnc.cn/Article/details/gtvxwnyhkn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daria6918.cn/Article/details/gtgmxdglxd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqztxfwr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gtzqciqidj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.bjfxy.top/Article/details/gtuzulxlww.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlrperbmp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gttnjalvoe.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtlyzdbjon.html

[N05] 最大公约数
来源：http://dali.jlsjyb.cn/Article/details/gtjbrkfqes.html

Py:   math.gcd(a, b)
来源：http://dali.jianghu66.top/Article/details/gtubpswwfg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xuanzx.com/Article/details/gtezcnbglx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aibaodan.cn/Article/details/gtyblyulfz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gtqopxptdu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shuidangran.top/Article/details/gtzmonokga.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhongyouzk.top/Article/details/gtojfrmivt.html

Ruby: a.gcd(b)
来源：http://dali.birdmap.top/Article/details/gtpxywlyct.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.snrcjt.cn/Article/details/gtirwufxsx.html

[N06] 判断回文字符串
来源：http://dali.hywenlv.cn/Article/details/gtjlrzkpmz.html

Py:   s == s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gtfuryafmg.html

PHP:  $s === strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyeubifwu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtvvnkwwzq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtkbwyccft.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hfpthk.cn/Article/details/gtjmareecz.html

Go:   // 双指针从两端比较
来源：http://dali.tianlin.xyz/Article/details/gtwbesybmz.html

Ruby: s == s.reverse
来源：http://dali.nanxinkj.top/Article/details/gtoapzobcz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gtzjsdgnom.html

[N07] 两数之和（返回下标）
来源：http://dali.hammf.cn/Article/details/gtmcyujjfl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cucudq.cn/Article/details/gtrordrnnd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jyoumei.cn/Article/details/gtozmxpfbk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdrulltv.html

TS:   // 手写 Map<string, number>
来源：http://dali.c1oappe.top/Article/details/gtiucvgzzu.html

Java: // 手写 HashMap
来源：http://dali.gaohongyu789.top/Article/details/gtdwaqjhmi.html

Go:   // 手写 map[int]int
来源：http://dali.mhx1999.top/Article/details/gtkymcumyc.html

Ruby: // 手写 Hash
来源：http://dali.haohaochexian.top/Article/details/gtytxmzvda.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yonumen.top/Article/details/gtywjyascq.html

[N08] 生成全排列
来源：http://dali.zhongyouzk.top/Article/details/gtsdyujkcs.html

Py:   itertools.permutations(arr)
来源：http://dali.quarkkingdee.top/Article/details/gttrcwdllz.html

PHP:  // 手写递归交换
来源：http://dali.yvedp.cn/Article/details/gtbbpwtxjv.html

JS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtgudvurxp.html

TS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtnoitisrq.html

Java: // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtefjhzbig.html

Go:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtykiiiizi.html

Ruby: arr.permutation.to_a
来源：http://dali.yj202588.top/Article/details/gtfkphcpph.html

C#:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtlbwkrsjq.html

[N09] 栈与队列
来源：http://dali.shzxlz.cn/Article/details/gtgakghxcu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtoajkjmsl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daxiang520.top/Article/details/gtezwxkjyj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gtlwhcagaq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258.top/Article/details/gtgktwhjtt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxinkj.top/Article/details/gtwdtimard.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ehwqpu.com/Article/details/gtvbyiqoth.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtxwvgcwgw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhoulong.xyz/Article/details/gtxonmhhpy.html

[N10] 链表节点定义
来源：http://dali.cashguo.top/Article/details/gtialqzsed.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yueranfly.top/Article/details/gtxlfqpwgg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.quarkkingdee.top/Article/details/gtobmuglfb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tian-w.cn/Article/details/gtkwlhxvhf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258.top/Article/details/gtospjabcq.html

Java: class Node { int v; Node next; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmgzfuwe.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yueranfly.top/Article/details/gtcwtnlore.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xuetiantiany.cn/Article/details/gtivrfmkme.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.9152youxi.cn/Article/details/gtxiluwrbh.html

[N11] 二叉树中序遍历
来源：http://dali.yonumen.top/Article/details/gtjqsruxsw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cashguo.top/Article/details/gtbmejvyoi.html

PHP:  // 手写递归函数
来源：http://dali.fengsongda.top/Article/details/gtonwpnayy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gtnslortdy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gttsftpixj.html

Java: // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtydelbsts.html

Go:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtcablxtlj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jiagoushi.top/Article/details/gteresalca.html

C#:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gtpezrhtfd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fengsongda.top/Article/details/gtjilwznmo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ydzc1.top/Article/details/gtxslfdkvv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigufen.top/Article/details/gtkoziaess.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenlongwang.top/Article/details/gtajwlofoz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gtlixrwolm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gtmlttsvue.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.snrcjt.cn/Article/details/gtrwfeoiew.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenlongwang.top/Article/details/gtcprsvajb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pycfn.com/Article/details/gtmpcjbmvt.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtlioiziqu.html

O. 并发与异步
来源：http://dali.tian-w.cn/Article/details/gtiqeehrva.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gthhpfhsex.html

[O01] 启动一个线程
来源：http://dali.yuxming.cn/Article/details/gthlgkhknt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.guannengcc.top/Article/details/gtrkqvrwjp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ehwqpu.com/Article/details/gtgxdlibvc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ehwqpu.com/Article/details/gtsunjvlbz.html

TS:   // 同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoskibhwx.html

Java: new Thread(() -> f()).start()
来源：http://dali.sufxvd.cn/Article/details/gtnhtawghg.html

Go:   go f()
来源：http://dali.shuidangran.top/Article/details/gtaqaioapr.html

Ruby: Thread.new { f }
来源：http://dali.ehwqpu.com/Article/details/gttkkoozjr.html

C#:   Task.Run(() => F());
来源：http://dali.ehwqpu.com/Article/details/gtgttgorfu.html

[O02] 使用线程池
来源：http://dali.yueranfly.top/Article/details/gtkrxmzubc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.feifeiyinyue.top/Article/details/gtyfbnzmka.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aizwys.cn/Article/details/gtahowqqvu.html

JS:   // worker_threads 线程池
来源：http://dali.hysaishi.cn/Article/details/gtaqijiwap.html

TS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gtppxjobza.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenzaomai.com/Article/details/gtoxgqqqoc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yongpay.top/Article/details/gtctcuufwf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.havefunace.top/Article/details/gtlxoxjlkr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jianghu66.top/Article/details/gttskhxnmh.html

[O03] 加锁保护共享数据
来源：http://dali.yuxming.cn/Article/details/gtmmupcfpl.html

Py:   with lock: shared += 1
来源：http://dali.jlsjyb.cn/Article/details/gtddwlagtk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jyoumei.cn/Article/details/gtpfimjivp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.bjfxy.top/Article/details/gtwqcxhmsi.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gtzrwqyyrv.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gteubnazwt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.haohaochexian.top/Article/details/gtueungdgl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cdnleiting.top/Article/details/gtvbbomzgz.html

C#:   lock (gate) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gtyjljzkwk.html

[O04] 定义异步函数并等待
来源：http://dali.jiagoushi.top/Article/details/gtkfdvgyky.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigfzy.top/Article/details/gtaoytbato.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkcjkmmfb.html

JS:   async function f() { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbcgkqnbe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sysykeji.top/Article/details/gtiuekcdie.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shuidangran.top/Article/details/gtovrdthqv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cashguo.top/Article/details/gtluoyxhaj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nanxuanxn.top/Article/details/gtrcfavqrp.html

C#:   async Task F() { await G(); }
来源：http://dali.yonumen.top/Article/details/gtuuojkgka.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gtvlqfwmzw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xinyue.icu/Article/details/gtssnhkeag.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ydzc1.top/Article/details/gtmbpgxcya.html

JS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gtgzwmslbi.html

TS:   await Promise.all(tasks)
来源：http://dali.sweek.top/Article/details/gtchubpqaa.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tianlin.xyz/Article/details/gtcwbboqdp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.aizwys.cn/Article/details/gtglbyxvrk.html

Ruby: threads.map(&:join)
来源：http://dali.cucudq.cn/Article/details/gthcuzbqyl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.aizwys.cn/Article/details/gtgorunyrv.html

[O06] 使用进程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwatoego.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daria6918.cn/Article/details/gtlqiatcqs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.kuanghao11.cn/Article/details/gtifofszrr.html

JS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gttemzmwiq.html

TS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gtyoryvusx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhixingplan.top/Article/details/gttpgtotod.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.birdmap.top/Article/details/gtxkdtuydl.html

Ruby: // fork 块
来源：http://dali.havefunace.top/Article/details/gtmqpkflms.html

C#:   Parallel.For
来源：http://dali.dianchejie.cn/Article/details/gtldkvpgbg.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtsvjssezg.html

P. 常用工具函数
来源：http://dali.daxiang520.top/Article/details/gtktairvyn.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtenclrelq.html

[P01] 生成 UUID
来源：http://dali.quarkkingdee.top/Article/details/gtfztabbap.html

Py:   str(uuid.uuid4())
来源：http://dali.havefunace.top/Article/details/gtgdygxwuc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhongyouzk.top/Article/details/gtpcbqjrnx.html

JS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gtworaujte.html

TS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gtqnsqjooy.html

Java: UUID.randomUUID().toString()
来源：http://dali.shzxlz.cn/Article/details/gtoyzucihc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hysaishi.cn/Article/details/gtammpykux.html

Ruby: SecureRandom.uuid
来源：http://dali.shuidangran.top/Article/details/gtanchevbu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.meibo888.top/Article/details/gtfzpivanm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yangfankeji.com/Article/details/gtdmxilqji.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.iojbl.cn/Article/details/gtqktnlnod.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nwbrower.top/Article/details/gtwdftnaak.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.fengsongda.top/Article/details/gtwrkqclca.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.pycfn.com/Article/details/gtzcfbvfzi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.meibo888.top/Article/details/gtiecvdwpz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.andypj.xyz/Article/details/gtowtrpjlj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gtmifjehah.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.quarkkingdee.top/Article/details/gtkheyrqaf.html

[P03] 生成短随机字符串
来源：http://dali.vqdsnc.cn/Article/details/gtvtbamjvv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sxryk.cn/Article/details/gtlsktyeac.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hysaishi.cn/Article/details/gtawgbvsas.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dianchejie.cn/Article/details/gtsvotebbz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gtasxxrrdl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.316326.xyz/Article/details/gtrylmmdjz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.0kj1m.cn/Article/details/gtsrbnpagz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.redwolf501.top/Article/details/gtiqqjjnph.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tianlin.xyz/Article/details/gtksrmjqnv.html

[P04] 求长度
来源：http://dali.dianchejie.cn/Article/details/gtbynjsjbs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shzxlz.cn/Article/details/gtlgxkitrp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtdnumiucs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zycfv.cn/Article/details/gtztspgefh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gtetqmjxhj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.9152youxi.cn/Article/details/gtzcrqhlcj.html

Go:   len(arr);  len(m)
来源：http://dali.yongpay.top/Article/details/gtxwvlksvw.html

Ruby: x.length;  x.size
来源：http://dali.jqgfzy.top/Article/details/gtiacowpmj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ybcxt.top/Article/details/gtpelxwnhl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sxryk.cn/Article/details/gtvwghnuos.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sxryk.cn/Article/details/gtpisgpqjk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shuidangran.top/Article/details/gtwhyqmwel.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.wangshuangyany.cn/Article/details/gtufqqkgos.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gtsoegxdtv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hysaishi.cn/Article/details/gtecbeantx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yonumen.top/Article/details/gtmuohbwcq.html

Ruby: a == b
来源：http://dali.tanke756.top/Article/details/gtiwdgpeyy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.dianchejie.cn/Article/details/gtrzaelxpe.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhiwuduotai.top/Article/details/gthllnagqt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.c1oappe.top/Article/details/gtncbokikq.html

PHP:  if (empty($x)) {}
来源：http://dali.jlsjyb.cn/Article/details/gthjdwjddf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gaohongyu789.top/Article/details/gthurbddcb.html

TS:   if (x == null) {}
来源：http://dali.aibaodan.cn/Article/details/gtkfiwduks.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtfvmybntv.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gtamvvtsde.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhixingplan.top/Article/details/gttevttynf.html

C#:   if (x is null) {}
来源：http://dali.smart0.xyz/Article/details/gtuccfteig.html

[P07] 防抖与节流
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbqiewhw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jiagoushi.top/Article/details/gtyhtxhjfg.html

PHP:  // 手写时间戳比较
来源：http://dali.zhoulong.xyz/Article/details/gtfgnoesjd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gtltjlgaui.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtondjdklq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.vqdsnc.cn/Article/details/gtpaufxxuf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.redwolf501.top/Article/details/gtxrqztdjn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.havefunace.top/Article/details/gtmetqcdxk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj202588.top/Article/details/gthlwehedm.html

[P08] 处理浮点精度问题
来源：http://dali.jiagoushi.top/Article/details/gtbuprkuos.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cqqwz.cn/Article/details/gtatyvwzui.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj202588.top/Article/details/gtqdjjwsrk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sxryk.cn/Article/details/gtistwvuym.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.iojbl.cn/Article/details/gtfvukjnib.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.haohaochexian.top/Article/details/gtjnbpljyp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cheryme.top/Article/details/gtzzyparnj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhiwuduotai.top/Article/details/gtxyidgppn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nwbrower.top/Article/details/gtqkdvvcyr.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtsgzhhuxq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.daxiang520.top/Article/details/gtdoewbyxi.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtnkoogblq.html

[Q01] 创建表
来源：http://dali.jyoumei.cn/Article/details/gtimmcekzm.html

CREATE TABLE users (
来源：http://dali.316326.xyz/Article/details/gtfvqdoopp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ppjwa.cn/Article/details/gtoyteqgae.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yangfankeji.com/Article/details/gteabcgobl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenzaomai.com/Article/details/gtzcojdivp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pengpengdd.cyou/Article/details/gtgyesdeuh.html

);
来源：http://dali.tian-w.cn/Article/details/gtledzjzre.html

[Q02] 创建带外键的表
来源：http://dali.hnxiangtu.top/Article/details/gtaongdxpf.html

CREATE TABLE orders (
来源：http://dali.redwolf501.top/Article/details/gtmdmmyapf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gtludazmyn.html

user_id INT NOT NULL,
来源：http://dali.ppjwa.cn/Article/details/gthjwtvitm.html

amount DECIMAL(10, 2),
来源：http://dali.jinqigufen.top/Article/details/gtgjxvgkwu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkkofhol.html

);
来源：http://dali.zhongyouzk.top/Article/details/gtuvyrslbp.html

[Q03] 增加列
来源：http://dali.jlsjyb.cn/Article/details/gtwktphegq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xziqi.cn/Article/details/gthdmdlazv.html

[Q04] 修改列类型
来源：http://dali.zdqjudy.top/Article/details/gtwgqpgwgv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daria6918.cn/Article/details/gttpxutxig.html

[Q05] 重命名列
来源：http://dali.yj20258888.top/Article/details/gttgdooqxa.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xuetiantiany.cn/Article/details/gtgpnivzcw.html

[Q06] 删除列
来源：http://dali.zhiwuduotai.top/Article/details/gtfethixup.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sufxvd.cn/Article/details/gtteudgozv.html

[Q07] 删除表
来源：http://dali.9152youxi.cn/Article/details/gtrezsvhpm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.dianchejie.cn/Article/details/gtbnktafaj.html

[Q08] 创建普通索引
来源：http://dali.yueranfly.top/Article/details/gthjwpjmen.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gtrgftgkfm.html

[Q09] 创建唯一索引
来源：http://dali.feifeiyinyue.top/Article/details/gtamfoalyq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.kuanghao11.cn/Article/details/gtbzvxpxht.html

[Q10] 插入单行
来源：http://dali.pycfn.com/Article/details/gtzbjqdkhl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gtakpfeiyr.html

[Q11] 一次插入多行
来源：http://dali.mhx1999.top/Article/details/gtoghoypgb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sxryk.cn/Article/details/gtedjjgxox.html

[Q12] 插入后取自增 ID
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitzmfogv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cdnleiting.top/Article/details/gtmjpjksfb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.0kj1m.cn/Article/details/gtzfciktzs.html

[Q13] 忽略重复插入
来源：http://dali.aibaodan.cn/Article/details/gtaipahwjp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj20258.top/Article/details/gtdkoqsjgu.html

[Q14] 存在则更新（upsert）
来源：http://dali.zdqjudy.top/Article/details/gthnwvgjqg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbimttgy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shzxlz.cn/Article/details/gtijhalfon.html

[Q15] 查询全部
来源：http://dali.vqdsnc.cn/Article/details/gtxybxyang.html

SELECT * FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsxbdcyx.html

[Q16] 查询指定列
来源：http://dali.zhixingplan.top/Article/details/gtsnwyjldo.html

SELECT id, name FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtrhzfphom.html

[Q17] 条件查询
来源：http://dali.gaohongyu789.top/Article/details/gtapaggrys.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.snrcjt.cn/Article/details/gtpzrvaypg.html

[Q18] 模糊匹配
来源：http://dali.meibo888.top/Article/details/gtmoacbqah.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hongshengwenyu.top/Article/details/gtwzygdfxz.html

[Q19] 范围查询
来源：http://dali.feifeiyinyue.top/Article/details/gtkjzourur.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnqzz.top/Article/details/gtqkvjqhqk.html

[Q20] IN 列表
来源：http://dali.zdqjudy.top/Article/details/gtvylccnrt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtfrbgriib.html

[Q21] 空值判断
来源：http://dali.mhx1999.top/Article/details/gtqwfdgolj.html


<!-- 参考信息 -->