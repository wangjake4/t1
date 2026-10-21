代发 wailian999

[N01] 二分查找（有序数组）
来源：http://dali.aibaodan.cn/Article/details/gtdflgwtql.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtuuokpiyh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.pycfn.com/Article/details/gtdtziwykj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrboxnonh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gtqmtnydhy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gttqigtppo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cashguo.top/Article/details/gtzcymmdgv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hongshengwenyu.top/Article/details/gtalkjakaa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtcawrunvv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcataeygq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gtnifjwmci.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tian-w.cn/Article/details/gtkvmchpit.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gtafajtiaa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gtydoubofh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ybcxt.top/Article/details/gtqofqpsaj.html

Go:   slices.Sort(arr)
来源：http://dali.yuxming.cn/Article/details/gtxhvtjtfw.html

Ruby: arr.sort
来源：http://dali.xuetiantiany.cn/Article/details/gtisajwsaa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gotoacloud.top/Article/details/gtftpxncym.html

[N03] 快速排序（分治示例）
来源：http://dali.chenzaomai.com/Article/details/gtifvthvqp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gaohongyu789.top/Article/details/gtopgufyyc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xylfe.cn/Article/details/gtfijcehbl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gtqccqqstg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gtgrwzbqke.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrginwvg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigufen.top/Article/details/gtktkhxdyz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xinyue.icu/Article/details/gtqjmpjhkz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tianlin.xyz/Article/details/gtobhbxxqr.html

[N04] 斐波那契数列
来源：http://dali.cdnleiting.top/Article/details/gtblyyeoka.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlgmuzirh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.birdmap.top/Article/details/gtqyzhlqsk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gtybhvbhqd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtjcwlkgbz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gttvtzpyqb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shangyingyoupin.top/Article/details/gtbnipscda.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gtllbzuavx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gtifefeyat.html

[N05] 最大公约数
来源：http://dali.zhiwuduotai.top/Article/details/gtbliaomut.html

Py:   math.gcd(a, b)
来源：http://dali.jiagoushi.top/Article/details/gtrzfitwpn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxinkj.top/Article/details/gtzevcocoq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gtmfuupukf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigufen.top/Article/details/gtnxejufws.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hongshengwenyu.top/Article/details/gtwukafqms.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jyoumei.cn/Article/details/gthlfhrahy.html

Ruby: a.gcd(b)
来源：http://dali.snrcjt.cn/Article/details/gtcarawjjm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258888.top/Article/details/gtqvkxhhlb.html

[N06] 判断回文字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtrqaukkxn.html

Py:   s == s[::-1]
来源：http://dali.ybcxt.top/Article/details/gtkrkhbdrh.html

PHP:  $s === strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gtynuygzce.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtonnoymzh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtkhgvlovj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jqgufenzy.top/Article/details/gtxqtglqzs.html

Go:   // 双指针从两端比较
来源：http://dali.yongpay.top/Article/details/gtrwgjkidz.html

Ruby: s == s.reverse
来源：http://dali.iojbl.cn/Article/details/gtqzrircyp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gtbceshijr.html

[N07] 两数之和（返回下标）
来源：http://dali.chenjidiqi.icu/Article/details/gtamkrykwc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yuxming.cn/Article/details/gtvhcztaod.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.wangshuangyany.cn/Article/details/gtbjzmzhbt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yvedp.cn/Article/details/gtspsokmpo.html

TS:   // 手写 Map<string, number>
来源：http://dali.hysaishi.cn/Article/details/gtlonbjyjh.html

Java: // 手写 HashMap
来源：http://dali.jinqigfzy.top/Article/details/gtsokgimny.html

Go:   // 手写 map[int]int
来源：http://dali.wangshuangyany.cn/Article/details/gtmcdhgivt.html

Ruby: // 手写 Hash
来源：http://dali.yanxiufei.cn/Article/details/gtqlhmobkj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ybcxt.top/Article/details/gtfvweayko.html

[N08] 生成全排列
来源：http://dali.fengsongda.top/Article/details/gtjrcpvydy.html

Py:   itertools.permutations(arr)
来源：http://dali.andypj.xyz/Article/details/gtnbomdpiu.html

PHP:  // 手写递归交换
来源：http://dali.yangfankeji.com/Article/details/gtgohadnbg.html

JS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtxamvvhhm.html

TS:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtxxgmjujf.html

Java: // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtletpcdwk.html

Go:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtfeaonfli.html

Ruby: arr.permutation.to_a
来源：http://dali.gaohongyu789.top/Article/details/gtzsiqzwbg.html

C#:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtliduufnj.html

[N09] 栈与队列
来源：http://dali.zdqjudy.top/Article/details/gtilkftesf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtzxmupiny.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtytomduzo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gtupshwxvs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtouqequax.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cashguo.top/Article/details/gteyssznrj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shuidangran.top/Article/details/gtkhppmwtc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gtwdddwayi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jianghu66.top/Article/details/gtwgtqtook.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gtokgpxojx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shuidangran.top/Article/details/gtmzvuvpmt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xylfe.cn/Article/details/gtrmgxutol.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sysykeji.top/Article/details/gtqrurjykd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangshuangyany.cn/Article/details/gtklkkukcn.html

Java: class Node { int v; Node next; }
来源：http://dali.gotoacloud.top/Article/details/gtqhwbhkqe.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ppjwa.cn/Article/details/gtmrttxybn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nanxuanxn.top/Article/details/gttxpqmipi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tianlin.xyz/Article/details/gtrfqapact.html

[N11] 二叉树中序遍历
来源：http://dali.hfpthk.cn/Article/details/gtwflqfyiv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zycfv.cn/Article/details/gtohykhnqn.html

PHP:  // 手写递归函数
来源：http://dali.yonumen.top/Article/details/gtkcvydfpl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gtrdpbfkox.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gtjfdnpcmg.html

Java: // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtcgjplbco.html

Go:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gtdnjksjlh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhixingplan.top/Article/details/gtqqpitakd.html

C#:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gttshcvbta.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhsktygf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.c1oappe.top/Article/details/gtbxjchart.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yuanzhike.top/Article/details/gtveticrth.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gtkacuxbll.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gthlwtzqit.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gtzcwvwahn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yueranfly.top/Article/details/gtuqtvhzuj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gzhubu.top/Article/details/gttmxuclbt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gtkbaosogy.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtiaurukpr.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gtgkjeyxgq.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtencneuxh.html

[O01] 启动一个线程
来源：http://dali.ivvv.top/Article/details/gtfxswsskr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dianchejie.cn/Article/details/gtbwocykji.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.pycfn.com/Article/details/gtficwxpzh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sxryk.cn/Article/details/gtipndzape.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gtjomzacmg.html

Java: new Thread(() -> f()).start()
来源：http://dali.ybcxt.top/Article/details/gtcnrnxhmu.html

Go:   go f()
来源：http://dali.daria6918.cn/Article/details/gtomwjkypb.html

Ruby: Thread.new { f }
来源：http://dali.c1oappe.top/Article/details/gtykauwikz.html

C#:   Task.Run(() => F());
来源：http://dali.ybcxt.top/Article/details/gtxybispnw.html

[O02] 使用线程池
来源：http://dali.hnqzz.top/Article/details/gtvgwkoqwg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jqgufenzy.top/Article/details/gtkpkprbub.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dianchejie.cn/Article/details/gtsrjfisqo.html

JS:   // worker_threads 线程池
来源：http://dali.kuanghao11.cn/Article/details/gtxsymbmgt.html

TS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gtdpkguwmk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cdnleiting.top/Article/details/gtcodwfqey.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.mhx1999.top/Article/details/gtbbwqdloc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cqqwz.cn/Article/details/gtutawonzp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.0kj1m.cn/Article/details/gthxqboepe.html

[O03] 加锁保护共享数据
来源：http://dali.cucudq.cn/Article/details/gtsjnksrfa.html

Py:   with lock: shared += 1
来源：http://dali.daxiang520.top/Article/details/gtvcjmvopw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pengpengdd.cyou/Article/details/gtrumcfitm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shzxlz.cn/Article/details/gtxllamgmo.html

TS:   // 同 JS
来源：http://dali.ppjwa.cn/Article/details/gtrjuyftun.html

Java: synchronized (this) { shared++; }
来源：http://dali.fzhhl.top/Article/details/gtdippipnt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dianchejie.cn/Article/details/gtzfzmqcxl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqftahwz.html

C#:   lock (gate) { shared++; }
来源：http://dali.meibo888.top/Article/details/gtxucpldxu.html

[O04] 定义异步函数并等待
来源：http://dali.yj202588.top/Article/details/gtgurvmkpw.html

Py:   async def f():⏎    await g()
来源：http://dali.jinghuilouyu.cn/Article/details/gtubvgxsod.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ivvv.top/Article/details/gtupsquikm.html

JS:   async function f() { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gteffojemm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cashguo.top/Article/details/gtoqfdfqxn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jyoumei.cn/Article/details/gtviqeutjv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xziqi.cn/Article/details/gtavzpsjrm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yongpay.top/Article/details/gtqucwkeva.html

C#:   async Task F() { await G(); }
来源：http://dali.birdmap.top/Article/details/gtuxiuxjdl.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuetiantiany.cn/Article/details/gtvebizanl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtihbthazw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.quarkkingdee.top/Article/details/gtwpbejvnj.html

JS:   await Promise.all(tasks)
来源：http://dali.yongpay.top/Article/details/gtdzpbsgts.html

TS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gtuqpqedvh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigfzy.top/Article/details/gtfeiscgew.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.aibaodan.cn/Article/details/gtoiusflco.html

Ruby: threads.map(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gtcwqlurmb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.dashuyun.cn/Article/details/gtksspaxno.html

[O06] 使用进程池
来源：http://dali.havefunace.top/Article/details/gtycgwhufg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sufxvd.cn/Article/details/gtbllscyfx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcrarmeg.html

JS:   // child_process / cluster 模块
来源：http://dali.nanxuanxn.top/Article/details/gtglhwbtwi.html

TS:   // child_process / cluster 模块
来源：http://dali.guowangkeji.top/Article/details/gttjfhzcqx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yonumen.top/Article/details/gtmvwobjrw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.dashuyun.cn/Article/details/gtnalfpnxs.html

Ruby: // fork 块
来源：http://dali.zhengqikj.top/Article/details/gtvssuxvkr.html

C#:   Parallel.For
来源：http://dali.hywenlv.cn/Article/details/gtmernkyey.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gttujwznuk.html

P. 常用工具函数
来源：http://dali.jiagoushi.top/Article/details/gtvzulvktq.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtwmhcxaei.html

[P01] 生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gtysdqdycv.html

Py:   str(uuid.uuid4())
来源：http://dali.hammf.cn/Article/details/gtrabwzoer.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jiagoushi.top/Article/details/gtcngmthkm.html

JS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gtqnzjlvmj.html

TS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gtllycwgav.html

Java: UUID.randomUUID().toString()
来源：http://dali.guannengcc.top/Article/details/gtgwpklnmm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hnxiangtu.top/Article/details/gtikfyalrv.html

Ruby: SecureRandom.uuid
来源：http://dali.tanke756.top/Article/details/gtzbgthnqv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jlsjyb.cn/Article/details/gtozcvnrwc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.fzhhl.top/Article/details/gtyzqaiawu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hysaishi.cn/Article/details/gtfxjhpesc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ybcxt.top/Article/details/gtbbmwaspm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.feifeiyinyue.top/Article/details/gthddprjdi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cucudq.cn/Article/details/gtymlxxsnz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtycreqmzf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymwimjny.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.andypj.xyz/Article/details/gtfugydlob.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yongpay.top/Article/details/gtfyithapt.html

[P03] 生成短随机字符串
来源：http://dali.jiagoushi.top/Article/details/gtjusfqoqh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.smart0.xyz/Article/details/gtabnucrlu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.meibo888.top/Article/details/gtbtyxbtel.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gtexzhaxsa.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gtqeiplfiw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cashguo.top/Article/details/gtrkvzzosc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnxiangtu.top/Article/details/gtowubchnu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cucudq.cn/Article/details/gtmydlkvcp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hywenlv.cn/Article/details/gtckerrcmr.html

[P04] 求长度
来源：http://dali.yvedp.cn/Article/details/gtjahmheuz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hnqzz.top/Article/details/gttmwoojiv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtobsmdgun.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nwbrower.top/Article/details/gtlkircaok.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmpgqnjp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shuidangran.top/Article/details/gtmeirfjjx.html

Go:   len(arr);  len(m)
来源：http://dali.hongshengwenyu.top/Article/details/gtglcfujes.html

Ruby: x.length;  x.size
来源：http://dali.gotoacloud.top/Article/details/gtgkpziegz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gtvtsdshpc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkypaqxr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shanyushiyangtech.top/Article/details/gthtgufssl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hnqzz.top/Article/details/gtszyasclx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.svipenyu.cn/Article/details/gtbjntrwqo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuanzhike.top/Article/details/gtlzxmbryn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tianlin.xyz/Article/details/gtuwejfpax.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtvgutpkjy.html

Ruby: a == b
来源：http://dali.andypj.xyz/Article/details/gtpckuepnq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.c1oappe.top/Article/details/gtjodikzmi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yueranfly.top/Article/details/gtnysdledk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sweek.top/Article/details/gtnxmghzpq.html

PHP:  if (empty($x)) {}
来源：http://dali.cucudq.cn/Article/details/gtkjnamclp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrxsnmko.html

TS:   if (x == null) {}
来源：http://dali.cdnleiting.top/Article/details/gtjsfimnrh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqcomyjsc.html

Go:   if x == nil {}
来源：http://dali.redwolf501.top/Article/details/gtmwknssbb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jiagoushi.top/Article/details/gtnhizdtin.html

C#:   if (x is null) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtpuunyeue.html

[P07] 防抖与节流
来源：http://dali.havefunace.top/Article/details/gtfcdcqxtl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yongpay.top/Article/details/gtfgyvpyhn.html

PHP:  // 手写时间戳比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdjxwbos.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gthzwbdgjt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtnyopymxf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jianghu66.top/Article/details/gttblxiuil.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hnxiangtu.top/Article/details/gtgnjtiodt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fzhhl.top/Article/details/gtvbfrtuoo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yueranfly.top/Article/details/gtzaaruyyq.html

[P08] 处理浮点精度问题
来源：http://dali.yongpay.top/Article/details/gtigmnepxt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gogol.net.cn/Article/details/gtzlsiklnp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.pycfn.com/Article/details/gthtzykcel.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.kuanghao11.cn/Article/details/gtsdpmcgij.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtdvimbiht.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyeevsjqd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhengqikj.top/Article/details/gtpqabqfmm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cheryme.top/Article/details/gtzpbuyllc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yonumen.top/Article/details/gtdakasqep.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtkrjyggri.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenlongwang.top/Article/details/gtlgukedhr.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtinxfhshs.html

[Q01] 创建表
来源：http://dali.gogol.net.cn/Article/details/gtecdyzgkw.html

CREATE TABLE users (
来源：http://dali.tanke756.top/Article/details/gthhsfzynq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwpuyhev.html

name VARCHAR(50) NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gtdohhjbxm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.wangdashe.top/Article/details/gtvrxcopwr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkkcxqry.html

);
来源：http://dali.dianchejie.cn/Article/details/gtpmbkanha.html

[Q02] 创建带外键的表
来源：http://dali.iojbl.cn/Article/details/gtwboenpsr.html

CREATE TABLE orders (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmzcbufs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gtowhcbiux.html

user_id INT NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gtjurlbqli.html

amount DECIMAL(10, 2),
来源：http://dali.yj20258.top/Article/details/gtfdpyjqlv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.fengsongda.top/Article/details/gtxrmmdyxo.html

);
来源：http://dali.nanxinkj.top/Article/details/gtnyyzybsx.html

[Q03] 增加列
来源：http://dali.hongshengwenyu.top/Article/details/gtczxtnzxg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhongyouzk.top/Article/details/gtxannndxg.html

[Q04] 修改列类型
来源：http://dali.ybcxt.top/Article/details/gteiwyssrc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.iojbl.cn/Article/details/gtxtouskkc.html

[Q05] 重命名列
来源：http://dali.iojbl.cn/Article/details/gthavhffbr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcyaxchh.html

[Q06] 删除列
来源：http://dali.zhiwuduotai.top/Article/details/gtlvlfpsga.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmnjezzjs.html

[Q07] 删除表
来源：http://dali.sxryk.cn/Article/details/gtaqmywddu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xziqi.cn/Article/details/gttprnlbkq.html

[Q08] 创建普通索引
来源：http://dali.sweek.top/Article/details/gtcrfgvsrs.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.dianchejie.cn/Article/details/gtybcszmgq.html

[Q09] 创建唯一索引
来源：http://dali.smart0.xyz/Article/details/gtnieqshgw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.haohaochexian.top/Article/details/gtihfvonqy.html

[Q10] 插入单行
来源：http://dali.hammf.cn/Article/details/gtwvjzylvb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtvnflxbqd.html

[Q11] 一次插入多行
来源：http://dali.zhoulong.xyz/Article/details/gtdtgmzhfw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtzrmqblmg.html

[Q12] 插入后取自增 ID
来源：http://dali.jqgufenzy.top/Article/details/gtozmigjze.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sysykeji.top/Article/details/gtxsktovyp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xuanzx.com/Article/details/gtwknshmkn.html

[Q13] 忽略重复插入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwpgxzjyx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tian-w.cn/Article/details/gtkkeddfjf.html

[Q14] 存在则更新（upsert）
来源：http://dali.svipenyu.cn/Article/details/gtbkocxvoi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gotoacloud.top/Article/details/gthogwoqxi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinghuilouyu.cn/Article/details/gtreqnwuqn.html

[Q15] 查询全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgebzmmua.html

SELECT * FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtzgadqpyc.html

[Q16] 查询指定列
来源：http://dali.jqgufenzy.top/Article/details/gthzoinmar.html

SELECT id, name FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtvobhyobr.html

[Q17] 条件查询
来源：http://dali.hongshengwenyu.top/Article/details/gtjhuyiyff.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhoulong.xyz/Article/details/gttzaaoyae.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gtmiuvpcbf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxszawci.html

[Q19] 范围查询
来源：http://dali.hammf.cn/Article/details/gtwyafzvsp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cdnleiting.top/Article/details/gtnxzcykty.html

[Q20] IN 列表
来源：http://dali.smart0.xyz/Article/details/gtnvhlvodm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yvedp.cn/Article/details/gtrsotfwyd.html

[Q21] 空值判断
来源：http://dali.dashuyun.cn/Article/details/gtbofnsquj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.iojbl.cn/Article/details/gtkydylpxw.html

[Q22] 排序
来源：http://dali.havefunace.top/Article/details/gtbibehwux.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.snrcjt.cn/Article/details/gtixegovxm.html

[Q23] 分页
来源：http://dali.cheryme.top/Article/details/gtunsjnbyh.html


<!-- 参考信息 -->