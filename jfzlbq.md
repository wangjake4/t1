代发 wailian999

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cqqwz.cn/Article/details/gt2laeutqnc.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2conutidc.html

N. 数据结构与算法
来源：http://dali.cdnleiting.top/Article/details/gt2peznqdwj.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2rrtasnzx.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwylrdbx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2wlnssjzj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pnywufwp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuanzhike.top/Article/details/gt2amvmbngh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gt2dmyftudo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2mrxxrkua.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2xpfyuhuu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.birdmap.top/Article/details/gt2ntezhopv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2occpgiqx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ocnhfnnw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gt2kgnrdcnb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.c1oappe.top/Article/details/gt2ibligbgf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gt2pensgzqq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gt2cwigazwv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shuidangran.top/Article/details/gt2wvixobpi.html

Go:   slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gt2bzqtxpxo.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gt2icusigyv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.feifeiyinyue.top/Article/details/gt2fkyzjikr.html

[N03] 快速排序（分治示例）
来源：http://dali.yonumen.top/Article/details/gt2cttzbhxy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shangyingyoupin.top/Article/details/gt2agpatpor.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hfpthk.cn/Article/details/gt2qntelrjp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.smart0.xyz/Article/details/gt2tmfudeqp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gt2ninkaaau.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.birdmap.top/Article/details/gt2bwdwxccl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.iojbl.cn/Article/details/gt2jzxohyll.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pgltyyrh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.316326.xyz/Article/details/gt2urqsccut.html

[N04] 斐波那契数列
来源：http://dali.zhengqikj.top/Article/details/gt2axuzltjj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gt2xnpwqezs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gt2fanzjita.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gt2sxmiusnx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gt2uxhdyehv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cashguo.top/Article/details/gt2uykiqpzn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.havefunace.top/Article/details/gt2eudhfjai.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ehwqpu.com/Article/details/gt2rzrmbzkk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gt2pwlnqlvc.html

[N05] 最大公约数
来源：http://dali.zdqjudy.top/Article/details/gt2yqvawtjo.html

Py:   math.gcd(a, b)
来源：http://dali.dianchejie.cn/Article/details/gt2oostlwcb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhixingplan.top/Article/details/gt2yydkqbtn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.vqdsnc.cn/Article/details/gt2rbhcohhg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gzhubu.top/Article/details/gt2dfegowzs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yongpay.top/Article/details/gt2wtekzbwg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuetiantiany.cn/Article/details/gt2runxyzlw.html

Ruby: a.gcd(b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jbmwkxwx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj202588.top/Article/details/gt2eklojben.html

[N06] 判断回文字符串
来源：http://dali.gogol.net.cn/Article/details/gt2ukqhaveu.html

Py:   s == s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gt2yipwzzqs.html

PHP:  $s === strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2ptdsoaab.html

JS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gt2nlsmbnuj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gt2wdzeokwc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj202588.top/Article/details/gt2ibcftyye.html

Go:   // 双指针从两端比较
来源：http://dali.yueranfly.top/Article/details/gt2tlhmpjqy.html

Ruby: s == s.reverse
来源：http://dali.guannengcc.top/Article/details/gt2yteawykx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gt2xokqneti.html

[N07] 两数之和（返回下标）
来源：http://dali.yongpay.top/Article/details/gt2imizqsbi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yuxming.cn/Article/details/gt2dchlmzcu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tianlin.xyz/Article/details/gt2tvinasni.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xylfe.cn/Article/details/gt2anbrxllo.html

TS:   // 手写 Map<string, number>
来源：http://dali.sysykeji.top/Article/details/gt2lmvfimhn.html

Java: // 手写 HashMap
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iulxrkqi.html

Go:   // 手写 map[int]int
来源：http://dali.shzxlz.cn/Article/details/gt2nviprbjz.html

Ruby: // 手写 Hash
来源：http://dali.yuxming.cn/Article/details/gt2qwdqjzut.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fengsongda.top/Article/details/gt2auhfpnlu.html

[N08] 生成全排列
来源：http://dali.guowangkeji.top/Article/details/gt2itukxbeo.html

Py:   itertools.permutations(arr)
来源：http://dali.mhx1999.top/Article/details/gt2hnocgtgn.html

PHP:  // 手写递归交换
来源：http://dali.kuanghao11.cn/Article/details/gt2xjahzize.html

JS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gt2onnpabwm.html

TS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2pgkgmktq.html

Java: // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gt2laoieioz.html

Go:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2lbnfvegl.html

Ruby: arr.permutation.to_a
来源：http://dali.svipenyu.cn/Article/details/gt2mwolawgv.html

C#:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2pclyrphe.html

[N09] 栈与队列
来源：http://dali.yangfankeji.com/Article/details/gt2qetwhgcp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yonumen.top/Article/details/gt2totmqgdc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2dnmbrzze.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2chcmdqll.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gaohongyu789.top/Article/details/gt2zwdatbyn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.birdmap.top/Article/details/gt2fpjrxavv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ivvv.top/Article/details/gt2jvaaahrn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jianghu66.top/Article/details/gt2agdcjcxl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sysykeji.top/Article/details/gt2qzsqdgsw.html

[N10] 链表节点定义
来源：http://dali.jlsjyb.cn/Article/details/gt2fuofmpsa.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pycfn.com/Article/details/gt2igfudrvx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.meibo888.top/Article/details/gt2skmdjqui.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tanke756.top/Article/details/gt2mknpxagy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jyoumei.cn/Article/details/gt2ngkfbzbo.html

Java: class Node { int v; Node next; }
来源：http://dali.fzhhl.top/Article/details/gt2twrcblhr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jqgufenzy.top/Article/details/gt2aathvfsi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jlsjyb.cn/Article/details/gt2ubqszosy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dashuyun.cn/Article/details/gt2jxhjgbzv.html

[N11] 二叉树中序遍历
来源：http://dali.daxiang520.top/Article/details/gt2mbynjjay.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shzxlz.cn/Article/details/gt2wjilegtm.html

PHP:  // 手写递归函数
来源：http://dali.yuanzhike.top/Article/details/gt2krphxrtq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gt2uxzajuqg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gt2jabyfjkw.html

Java: // 手写递归
来源：http://dali.sxryk.cn/Article/details/gt2xumtresn.html

Go:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2zhfrgjie.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuxming.cn/Article/details/gt2lroewvix.html

C#:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2trbwwfss.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shangyingyoupin.top/Article/details/gt2wvbmdtqk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nwbrower.top/Article/details/gt2omntzamm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenlongwang.top/Article/details/gt2fazpxias.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gt2yghnmvhh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.mhx1999.top/Article/details/gt2ghpgehbx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.redwolf501.top/Article/details/gt2naslsfxj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sxryk.cn/Article/details/gt2rnnfvtdu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ppjwa.cn/Article/details/gt2kvlvbqmy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gt2xctgeixr.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2jtfgqvuc.html

O. 并发与异步
来源：http://dali.jqgfzy.top/Article/details/gt2djuqgwfc.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2nuzmjvru.html

[O01] 启动一个线程
来源：http://dali.zhengqikj.top/Article/details/gt2fgyzlzna.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.9152youxi.cn/Article/details/gt2exbkpoeq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2gxvjnxxg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.9152youxi.cn/Article/details/gt2gasidkmy.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gt2bdndghaq.html

Java: new Thread(() -> f()).start()
来源：http://dali.hammf.cn/Article/details/gt2cmyhphjh.html

Go:   go f()
来源：http://dali.yvedp.cn/Article/details/gt2abfhtnnq.html

Ruby: Thread.new { f }
来源：http://dali.zhengqikj.top/Article/details/gt2hptxavrq.html

C#:   Task.Run(() => F());
来源：http://dali.cucudq.cn/Article/details/gt2saritkfl.html

[O02] 使用线程池
来源：http://dali.cheryme.top/Article/details/gt2ewiftdbn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wuumpsnx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.9152youxi.cn/Article/details/gt2vdfynqxh.html

JS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gt2vbfdyxpd.html

TS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gt2tyrgslcs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daria6918.cn/Article/details/gt2wftzpbxo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhixingplan.top/Article/details/gt2tsbljxpm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.c1oappe.top/Article/details/gt2jeozrtzd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nanxuanxn.top/Article/details/gt2qjzqvuvc.html

[O03] 加锁保护共享数据
来源：http://dali.xziqi.cn/Article/details/gt2visuzhyl.html

Py:   with lock: shared += 1
来源：http://dali.nanxinkj.top/Article/details/gt2oujznlnz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sxryk.cn/Article/details/gt2ryjmnfkq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhiwuduotai.top/Article/details/gt2etbmareq.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gt2gwzadjru.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnxiangtu.top/Article/details/gt2wwjwpfds.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cqqwz.cn/Article/details/gt2rngoxsts.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.fengsongda.top/Article/details/gt2jfmapuvl.html

C#:   lock (gate) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ucjpxrfx.html

[O04] 定义异步函数并等待
来源：http://dali.zycfv.cn/Article/details/gt2tzjrmsvu.html

Py:   async def f():⏎    await g()
来源：http://dali.andypj.xyz/Article/details/gt2uyeqdxpz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2enspttnh.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2piygdlcy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yueranfly.top/Article/details/gt2znfqypbn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.pengpengdd.cyou/Article/details/gt2egebxsjt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cheryme.top/Article/details/gt2vvagiyqi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yueranfly.top/Article/details/gt2lhxlibvi.html

C#:   async Task F() { await G(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sorkrfti.html

[O05] 并发执行并等待全部完成
来源：http://dali.feifeiyinyue.top/Article/details/gt2iwdqrlkh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ivvv.top/Article/details/gt2sgwjvorj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxuanxn.top/Article/details/gt2kmgpdhbv.html

JS:   await Promise.all(tasks)
来源：http://dali.chenlongwang.top/Article/details/gt2gwdsdzom.html

TS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gt2yxzezavp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.wangshuangyany.cn/Article/details/gt2maokoiny.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sufxvd.cn/Article/details/gt2dhzjevgy.html

Ruby: threads.map(&:join)
来源：http://dali.xuanzx.com/Article/details/gt2dlcenjne.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.havefunace.top/Article/details/gt2krnwspdw.html

[O06] 使用进程池
来源：http://dali.zycfv.cn/Article/details/gt2berxqgfq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hammf.cn/Article/details/gt2woovwjno.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2amrctjax.html

JS:   // child_process / cluster 模块
来源：http://dali.xuanzx.com/Article/details/gt2yygfstwt.html

TS:   // child_process / cluster 模块
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhfhewbw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jlsjyb.cn/Article/details/gt2ydjtdtfn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hysaishi.cn/Article/details/gt2jajvspqn.html

Ruby: // fork 块
来源：http://dali.aizwys.cn/Article/details/gt2deskapyx.html

C#:   Parallel.For
来源：http://dali.chenlongwang.top/Article/details/gt2qoqawowz.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2pofvxapn.html

P. 常用工具函数
来源：http://dali.guannengcc.top/Article/details/gt2xekqwgud.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2puhukuts.html

[P01] 生成 UUID
来源：http://dali.yuxming.cn/Article/details/gt2izocrnbb.html

Py:   str(uuid.uuid4())
来源：http://dali.c1oappe.top/Article/details/gt2qfnwsjzp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jlsjyb.cn/Article/details/gt2wvnbcbpz.html

JS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gt2kdtpqzwj.html

TS:   crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gt2chpgtpdg.html

Java: UUID.randomUUID().toString()
来源：http://dali.xuanzx.com/Article/details/gt2hjvrlfta.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cashguo.top/Article/details/gt2wexvbkwf.html

Ruby: SecureRandom.uuid
来源：http://dali.cdnleiting.top/Article/details/gt2urvjtuqy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.quarkkingdee.top/Article/details/gt2kdfyunlw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nanxuanxn.top/Article/details/gt2dkpjbunp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sufxvd.cn/Article/details/gt2fsliteuh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nwbrower.top/Article/details/gt2spnahalh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.9152youxi.cn/Article/details/gt2urtgroak.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cdnleiting.top/Article/details/gt2zeqiyayx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ybcxt.top/Article/details/gt2acedqbik.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhengqikj.top/Article/details/gt2nalocbcy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuanzx.com/Article/details/gt2ovvzrzcq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.andypj.xyz/Article/details/gt2wshombct.html

[P03] 生成短随机字符串
来源：http://dali.shzxlz.cn/Article/details/gt2syfxagis.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ehwqpu.com/Article/details/gt2sipkbumt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xziqi.cn/Article/details/gt2rhruwkvh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cqqwz.cn/Article/details/gt2ahovommw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gt2sibhyprx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sysykeji.top/Article/details/gt2znvrhjiy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xuanzx.com/Article/details/gt2lhygqxab.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2orsfgitd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnxiangtu.top/Article/details/gt2tdnehmyt.html

[P04] 求长度
来源：http://dali.meibo888.top/Article/details/gt2jrmdbrzx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sufxvd.cn/Article/details/gt2kteddhtq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gt2ebuxtvld.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shzxlz.cn/Article/details/gt2rlbeaxpn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gt2fooctalo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gt2fkrrxgxn.html

Go:   len(arr);  len(m)
来源：http://dali.dashuyun.cn/Article/details/gt2tgmqagct.html

Ruby: x.length;  x.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2piorbqgl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gt2ynkmndeh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yongpay.top/Article/details/gt2zettcepf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenlongwang.top/Article/details/gt2vlyfixmv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nafvagju.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenjidiqi.icu/Article/details/gt2ruvgqiml.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.smart0.xyz/Article/details/gt2puaveqoh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhoulong.xyz/Article/details/gt2rytajved.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dianchejie.cn/Article/details/gt2ntfmkjtr.html

Ruby: a == b
来源：http://dali.xinyue.icu/Article/details/gt2vknikyfo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gotoacloud.top/Article/details/gt2xlaouucl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.pycfn.com/Article/details/gt2yebvxwyd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.feifeiyinyue.top/Article/details/gt2bpgcivcz.html

PHP:  if (empty($x)) {}
来源：http://dali.316326.xyz/Article/details/gt2tlhimarn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yanxiufei.cn/Article/details/gt2spyxowwd.html

TS:   if (x == null) {}
来源：http://dali.tian-w.cn/Article/details/gt2xzxibzuv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yuanzhike.top/Article/details/gt2tnnmxjme.html

Go:   if x == nil {}
来源：http://dali.yangfankeji.com/Article/details/gt2shrfokpn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.guowangkeji.top/Article/details/gt2igkifuxx.html

C#:   if (x is null) {}
来源：http://dali.xylfe.cn/Article/details/gt2rtpwwvzh.html

[P07] 防抖与节流
来源：http://dali.xziqi.cn/Article/details/gt2wqmdtnbu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.9152youxi.cn/Article/details/gt2hqmxleyi.html

PHP:  // 手写时间戳比较
来源：http://dali.aibaodan.cn/Article/details/gt2vamvhdou.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gt2eapuxybz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gt2vyzgrlar.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2resixwnl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ydzc1.top/Article/details/gt2nqbdujjt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jqgfzy.top/Article/details/gt2mtbznwox.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.bjfxy.top/Article/details/gt2evsetepk.html

[P08] 处理浮点精度问题
来源：http://dali.yj20258.top/Article/details/gt2dfnwqrde.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fengsongda.top/Article/details/gt2vreplnvt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2xvzktnme.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hammf.cn/Article/details/gt2rmgkmsfa.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nanxuanxn.top/Article/details/gt2dgodande.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gogol.net.cn/Article/details/gt2wkndcuyj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ehwqpu.com/Article/details/gt2pwszwgze.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.fzhhl.top/Article/details/gt2ofdtehwn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ivvv.top/Article/details/gt2jaabakjc.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2efcqqsha.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhongyouzk.top/Article/details/gt2gvdwmipx.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kdlxbixw.html

[Q01] 创建表
来源：http://dali.guowangkeji.top/Article/details/gt2epbooyeh.html

CREATE TABLE users (
来源：http://dali.ehwqpu.com/Article/details/gt2dedhcldo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.havefunace.top/Article/details/gt2wauchzyl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gt2sgjuelrn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.svipenyu.cn/Article/details/gt2blwckdxp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ehwqpu.com/Article/details/gt2qnacfvev.html

);
来源：http://dali.haohaochexian.top/Article/details/gt2cweyinvj.html

[Q02] 创建带外键的表
来源：http://dali.hammf.cn/Article/details/gt2kfnpqrgz.html

CREATE TABLE orders (
来源：http://dali.snrcjt.cn/Article/details/gt2kwzrysvn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gt2jlhhsjrh.html

user_id INT NOT NULL,
来源：http://dali.daxiang520.top/Article/details/gt2rlmnkeap.html

amount DECIMAL(10, 2),
来源：http://dali.svipenyu.cn/Article/details/gt2intmaqil.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tsidmqcc.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gt2bkapmiri.html

[Q03] 增加列
来源：http://dali.zycfv.cn/Article/details/gt2qootgsjm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxuanxn.top/Article/details/gt2abowywoh.html

[Q04] 修改列类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2ienpvodr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jiagoushi.top/Article/details/gt2qywchrmg.html

[Q05] 重命名列
来源：http://dali.yvedp.cn/Article/details/gt2gengetgr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jyoumei.cn/Article/details/gt2wrvdkhsn.html

[Q06] 删除列
来源：http://dali.nwbrower.top/Article/details/gt2kgueccoc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ehwqpu.com/Article/details/gt2hcgrlveh.html

[Q07] 删除表
来源：http://dali.sxryk.cn/Article/details/gt2jerryqhx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shzxlz.cn/Article/details/gt2renwejvx.html

[Q08] 创建普通索引
来源：http://dali.guowangkeji.top/Article/details/gt2ntpeemhi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nanxinkj.top/Article/details/gt2tfacuwnu.html

[Q09] 创建唯一索引
来源：http://dali.meibo888.top/Article/details/gt2fdzkkqqc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gt2dfaerdbi.html

[Q10] 插入单行
来源：http://dali.snrcjt.cn/Article/details/gt2rdfcqric.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hammf.cn/Article/details/gt2fesgjlhu.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2arazzwfx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gt2nikughig.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258.top/Article/details/gt2skrcjbyg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jlsjyb.cn/Article/details/gt2gesrtrnc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gotoacloud.top/Article/details/gt2ywmsmqul.html

[Q13] 忽略重复插入
来源：http://dali.quarkkingdee.top/Article/details/gt2aaaobbma.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gotoacloud.top/Article/details/gt2yyirkbcr.html

[Q14] 存在则更新（upsert）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gjkhmlci.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenzaomai.com/Article/details/gt2pcsxppod.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ybcxt.top/Article/details/gt2opcgdkyf.html

[Q15] 查询全部
来源：http://dali.wangdashe.top/Article/details/gt2lqtxkckm.html

SELECT * FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kljybvhy.html

[Q16] 查询指定列
来源：http://dali.hnxiangtu.top/Article/details/gt2rvmrovfg.html

SELECT id, name FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2hoqdebgy.html

[Q17] 条件查询
来源：http://dali.nwbrower.top/Article/details/gt2eznqdqay.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2ryzkxmyc.html

[Q18] 模糊匹配
来源：http://dali.chenlongwang.top/Article/details/gt2emqobrrs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.meibo888.top/Article/details/gt2udakkrrj.html

[Q19] 范围查询
来源：http://dali.havefunace.top/Article/details/gt2iqkndzrv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.aibaodan.cn/Article/details/gt2nvnvpaob.html

[Q20] IN 列表
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjxlwoll.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.9152youxi.cn/Article/details/gt2ptwsnckx.html

[Q21] 空值判断
来源：http://dali.hnqzz.top/Article/details/gt2oxwumwqg.html


<!-- 参考信息 -->