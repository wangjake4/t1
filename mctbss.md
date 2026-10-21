代发 wailian999

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tian-w.cn/Article/details/gtzwnysout.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtiokyqgzs.html

N. 数据结构与算法
来源：http://dali.xuanzx.com/Article/details/gtrkobjakw.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtpmidcpmc.html

[N01] 二分查找（有序数组）
来源：http://dali.zhixingplan.top/Article/details/gtvhlhyqpv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtcrisnmqc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.birdmap.top/Article/details/gtrhmrhcpi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gtxsruerto.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtonrtlypq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtmlvnmgvy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gttiusgykt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuxming.cn/Article/details/gtwcoecnxz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtxzrvtyqm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenlongwang.top/Article/details/gtdvvobpsx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gtaqxwyfbn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ivvv.top/Article/details/gtmlseqjsa.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gtegiugopr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gtcajsmzcg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daria6918.cn/Article/details/gtzxharcdd.html

Go:   slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtanzyapau.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gtfdjqyivc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.havefunace.top/Article/details/gtibryhkbj.html

[N03] 快速排序（分治示例）
来源：http://dali.zhengqikj.top/Article/details/gtowootkot.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.havefunace.top/Article/details/gtpkftiekl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fengsongda.top/Article/details/gtuvlbkguj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gtuhanzfpq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gtecokzcto.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhixingplan.top/Article/details/gtaxafafxh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangshuangyany.cn/Article/details/gtujltumfv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinghuilouyu.cn/Article/details/gttplkuqwc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xuetiantiany.cn/Article/details/gthiifbmnc.html

[N04] 斐波那契数列
来源：http://dali.haohaochexian.top/Article/details/gtywipgmlg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gtfpfjzivt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sweek.top/Article/details/gtakjrpijr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtbgclfemi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtymzfwgqb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gtwfozqkvg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shuidangran.top/Article/details/gtiwilincb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ehwqpu.com/Article/details/gtakxybxjm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtsbgptbba.html

[N05] 最大公约数
来源：http://dali.yuanzhike.top/Article/details/gtrmzacwpt.html

Py:   math.gcd(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gthdmhhleu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shzxlz.cn/Article/details/gtsawimpps.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jlsjyb.cn/Article/details/gtssgwxnja.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtjhvcsjgt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ppjwa.cn/Article/details/gtmbwnldjy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sxryk.cn/Article/details/gtbxkjhjca.html

Ruby: a.gcd(b)
来源：http://dali.yueranfly.top/Article/details/gtnszpipkk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cheryme.top/Article/details/gtaheadlip.html

[N06] 判断回文字符串
来源：http://dali.zhongyouzk.top/Article/details/gtokylbuui.html

Py:   s == s[::-1]
来源：http://dali.sysykeji.top/Article/details/gtsclvexeg.html

PHP:  $s === strrev($s);
来源：http://dali.fzhhl.top/Article/details/gtplyestyw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtonrqsaff.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtopbyzvor.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenzaomai.com/Article/details/gtsmcrgmwc.html

Go:   // 双指针从两端比较
来源：http://dali.xuetiantiany.cn/Article/details/gtxdqiikfh.html

Ruby: s == s.reverse
来源：http://dali.haohaochexian.top/Article/details/gtcfpqxzrn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gtbvcqptak.html

[N07] 两数之和（返回下标）
来源：http://dali.ppjwa.cn/Article/details/gtrqthtflp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fzhhl.top/Article/details/gtgrfagzwd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cheryme.top/Article/details/gtoldxoxbg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yvedp.cn/Article/details/gtsqnxhsnz.html

TS:   // 手写 Map<string, number>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnuyclnw.html

Java: // 手写 HashMap
来源：http://dali.cqqwz.cn/Article/details/gtjkcphaqe.html

Go:   // 手写 map[int]int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvvvdhcm.html

Ruby: // 手写 Hash
来源：http://dali.shuidangran.top/Article/details/gtpugvnkkx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cucudq.cn/Article/details/gtxvfwakjc.html

[N08] 生成全排列
来源：http://dali.sysykeji.top/Article/details/gtxrmbzjvq.html

Py:   itertools.permutations(arr)
来源：http://dali.cqqwz.cn/Article/details/gtwdaypurk.html

PHP:  // 手写递归交换
来源：http://dali.hfpthk.cn/Article/details/gtnrkcplcb.html

JS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtlktkofwm.html

TS:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtncgxqbyd.html

Java: // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtvdczjopp.html

Go:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtdbetudft.html

Ruby: arr.permutation.to_a
来源：http://dali.hfpthk.cn/Article/details/gtgohuslzf.html

C#:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtobivinbk.html

[N09] 栈与队列
来源：http://dali.yangfankeji.com/Article/details/gtwivebdgh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangdashe.top/Article/details/gtklfrccpo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gtkrsvegfp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtbiquwzpl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hfpthk.cn/Article/details/gtwcdctoco.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jianghu66.top/Article/details/gtfawgiyez.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.meibo888.top/Article/details/gtbfthxjcy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtmfuyjgog.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinqigfzy.top/Article/details/gtfmoqqjtv.html

[N10] 链表节点定义
来源：http://dali.guowangkeji.top/Article/details/gthowugjyc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cashguo.top/Article/details/gtlhmohsyv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.snrcjt.cn/Article/details/gtclsjrhrz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipxnyvow.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daria6918.cn/Article/details/gtfjthqssu.html

Java: class Node { int v; Node next; }
来源：http://dali.gzhubu.top/Article/details/gtikgcyhvl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fzhhl.top/Article/details/gtfxtyhjsq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daria6918.cn/Article/details/gtoxzlzvlc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hywenlv.cn/Article/details/gtyjlgrvkd.html

[N11] 二叉树中序遍历
来源：http://dali.nanxinkj.top/Article/details/gtlgnvufuw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daxiang520.top/Article/details/gtgmdipomh.html

PHP:  // 手写递归函数
来源：http://dali.hnqzz.top/Article/details/gtmifljmdo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cheryme.top/Article/details/gtmvfsyarj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangshuangyany.cn/Article/details/gtidmcuaed.html

Java: // 手写递归
来源：http://dali.guannengcc.top/Article/details/gtfcpudxpp.html

Go:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtaujfhwlj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cqqwz.cn/Article/details/gtmgelzjxu.html

C#:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtucwfpcmu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinqigufen.top/Article/details/gtpkqttppj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yvedp.cn/Article/details/gthbzhspbt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.redwolf501.top/Article/details/gtqyrjrvfj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhiwuduotai.top/Article/details/gtpggwpvyi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gtyeecxkpr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gtgksjewbw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.iojbl.cn/Article/details/gtuqsaqwfl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ydzc1.top/Article/details/gtalctoleh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gthgotkoie.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtclhzxepz.html

O. 并发与异步
来源：http://dali.sysykeji.top/Article/details/gtmverxmjs.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtbogkqzra.html

[O01] 启动一个线程
来源：http://dali.ehwqpu.com/Article/details/gtcaovmluk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sweek.top/Article/details/gtcwipljuu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jqgfzy.top/Article/details/gtcbxnhgnq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.haohaochexian.top/Article/details/gtfchniobx.html

TS:   // 同 JS
来源：http://dali.xinyue.icu/Article/details/gtzfjlcpvy.html

Java: new Thread(() -> f()).start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgjywddx.html

Go:   go f()
来源：http://dali.gotoacloud.top/Article/details/gtlhnuhsay.html

Ruby: Thread.new { f }
来源：http://dali.hnxiangtu.top/Article/details/gtumhaqwas.html

C#:   Task.Run(() => F());
来源：http://dali.shangyingyoupin.top/Article/details/gtymwkxlil.html

[O02] 使用线程池
来源：http://dali.ybcxt.top/Article/details/gtfzkbcyxv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yvedp.cn/Article/details/gtmurhcjmv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.snrcjt.cn/Article/details/gtceskyndl.html

JS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gtrciykeem.html

TS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gtzanfsrgr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.meibo888.top/Article/details/gtbcyumtfr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258888.top/Article/details/gtlnjrnbgz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.guannengcc.top/Article/details/gtujedgpye.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cqqwz.cn/Article/details/gtgaxmkoul.html

[O03] 加锁保护共享数据
来源：http://dali.yj20258.top/Article/details/gtmfkddbyj.html

Py:   with lock: shared += 1
来源：http://dali.zhiwuduotai.top/Article/details/gtfzwjxxsn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ybcxt.top/Article/details/gtuksebktx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj202588.top/Article/details/gtggzncwec.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gtsanbnjfa.html

Java: synchronized (this) { shared++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfagxogad.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ehwqpu.com/Article/details/gtbmcikete.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhoulong.xyz/Article/details/gtqrnmgsih.html

C#:   lock (gate) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gtkokbmqda.html

[O04] 定义异步函数并等待
来源：http://dali.yj202588.top/Article/details/gtrhhbmrkv.html

Py:   async def f():⏎    await g()
来源：http://dali.hnxiangtu.top/Article/details/gtetutvege.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hysaishi.cn/Article/details/gtzxaibpup.html

JS:   async function f() { await g(); }
来源：http://dali.cucudq.cn/Article/details/gtzvzxskkj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.316326.xyz/Article/details/gtcqcygyvb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenzaomai.com/Article/details/gtdcneirwk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258888.top/Article/details/gtfpfrffkq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizrgqooy.html

C#:   async Task F() { await G(); }
来源：http://dali.aibaodan.cn/Article/details/gtzssyeera.html

[O05] 并发执行并等待全部完成
来源：http://dali.jianghu66.top/Article/details/gtkmtgycdi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xylfe.cn/Article/details/gttpjhfilz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sxryk.cn/Article/details/gtnvtcrval.html

JS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gtnngrmsbh.html

TS:   await Promise.all(tasks)
来源：http://dali.zhongyouzk.top/Article/details/gtizgudlks.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jiagoushi.top/Article/details/gtotwobhiz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nwbrower.top/Article/details/gtvonpbdua.html

Ruby: threads.map(&:join)
来源：http://dali.gogol.net.cn/Article/details/gtfgqspawm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdzdyemm.html

[O06] 使用进程池
来源：http://dali.ydzc1.top/Article/details/gttjcdlvnl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcxpuihq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hongshengwenyu.top/Article/details/gtyzsicnvb.html

JS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gtntqssbci.html

TS:   // child_process / cluster 模块
来源：http://dali.cheryme.top/Article/details/gtcdlkwdpt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gtmcxtfwok.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfevujot.html

Ruby: // fork 块
来源：http://dali.ydzc1.top/Article/details/gtzawokmit.html

C#:   Parallel.For
来源：http://dali.hysaishi.cn/Article/details/gtukwucnyp.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxpiakku.html

P. 常用工具函数
来源：http://dali.yongpay.top/Article/details/gtjpctdsxq.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfymaqxf.html

[P01] 生成 UUID
来源：http://dali.nanxinkj.top/Article/details/gtsknhaqyk.html

Py:   str(uuid.uuid4())
来源：http://dali.hammf.cn/Article/details/gtnwropwgt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tian-w.cn/Article/details/gtkdejwcgs.html

JS:   crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gthahyavqw.html

TS:   crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gtsomazsog.html

Java: UUID.randomUUID().toString()
来源：http://dali.hysaishi.cn/Article/details/gtxvnaajsx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.smart0.xyz/Article/details/gtrhewbwhx.html

Ruby: SecureRandom.uuid
来源：http://dali.ppjwa.cn/Article/details/gtzjhrxrzq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yuxming.cn/Article/details/gtimmcqjhf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangdashe.top/Article/details/gtgeymeuii.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hywenlv.cn/Article/details/gtwnqffryc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.9152youxi.cn/Article/details/gtetmahwiz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hfpthk.cn/Article/details/gtufvcsmcs.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.kuanghao11.cn/Article/details/gtobcvzqyf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtaplfpxbw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.vqdsnc.cn/Article/details/gtbnnwywci.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fzhhl.top/Article/details/gttyfngnnz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpvuvkkm.html

[P03] 生成短随机字符串
来源：http://dali.xziqi.cn/Article/details/gtqmxavtmz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.svipenyu.cn/Article/details/gtjpzijpoi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yonumen.top/Article/details/gthixeszbt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuanzhike.top/Article/details/gtrbdluvzi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.mhx1999.top/Article/details/gtipfttrlv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.andypj.xyz/Article/details/gtiuzakbqk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xziqi.cn/Article/details/gteqscqstn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jyoumei.cn/Article/details/gtjsjxecaf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tian-w.cn/Article/details/gtobhuopvf.html

[P04] 求长度
来源：http://dali.yangfankeji.com/Article/details/gtkuqkwbbi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.andypj.xyz/Article/details/gtqierzlhr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtewpjzuxu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gtgkphgcmv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtxynapogv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gogol.net.cn/Article/details/gtfgnidfkz.html

Go:   len(arr);  len(m)
来源：http://dali.kuanghao11.cn/Article/details/gtsntozoxg.html

Ruby: x.length;  x.size
来源：http://dali.yvedp.cn/Article/details/gtpyzlqygp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gtbyvrddub.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xuetiantiany.cn/Article/details/gtbmtxmlzb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pycfn.com/Article/details/gteceesrzy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jlsjyb.cn/Article/details/gtbllglhqq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jianghu66.top/Article/details/gtililzxvc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtubzqwnam.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.havefunace.top/Article/details/gtbkyijrnp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cucudq.cn/Article/details/gtvzzlipct.html

Ruby: a == b
来源：http://dali.guannengcc.top/Article/details/gtpdvbxzja.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shanyushiyangtech.top/Article/details/gtkybvwwop.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.quarkkingdee.top/Article/details/gtsauquwve.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jiagoushi.top/Article/details/gtbydzcjxt.html

PHP:  if (empty($x)) {}
来源：http://dali.smart0.xyz/Article/details/gtvvwseloa.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.316326.xyz/Article/details/gtrczvdfdn.html

TS:   if (x == null) {}
来源：http://dali.gotoacloud.top/Article/details/gtltjmbcst.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gtuakujqsv.html

Go:   if x == nil {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzilyeadx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xinyue.icu/Article/details/gtxrzychwp.html

C#:   if (x is null) {}
来源：http://dali.yangfankeji.com/Article/details/gtrjafxulp.html

[P07] 防抖与节流
来源：http://dali.dianchejie.cn/Article/details/gtgozlcmpm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yueranfly.top/Article/details/gtdvlkwrqw.html

PHP:  // 手写时间戳比较
来源：http://dali.yuanzhike.top/Article/details/gtusjrjlif.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gtaucogbgc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gtnveammad.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.meibo888.top/Article/details/gttrravmbw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gogol.net.cn/Article/details/gteokwtrka.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shzxlz.cn/Article/details/gtknazayav.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fzhhl.top/Article/details/gtoplbeodq.html

[P08] 处理浮点精度问题
来源：http://dali.cashguo.top/Article/details/gtzflepeny.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zycfv.cn/Article/details/gtsaoccjqa.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbokgkih.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tian-w.cn/Article/details/gtkktjemhs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.vqdsnc.cn/Article/details/gtyulpfewd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gotoacloud.top/Article/details/gtqwmzdlvn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jqgfzy.top/Article/details/gtoophsvzi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hammf.cn/Article/details/gtwqigvfum.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tanke756.top/Article/details/gtngwkqjhm.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtqjqfamsi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigfzy.top/Article/details/gtccusglni.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtkhcxvsbv.html

[Q01] 创建表
来源：http://dali.ivvv.top/Article/details/gtagbffppk.html

CREATE TABLE users (
来源：http://dali.zhongyouzk.top/Article/details/gtfbpolphg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ydzc1.top/Article/details/gtaggkiacx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gtoiecwmot.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pycfn.com/Article/details/gtregqfxlb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.9152youxi.cn/Article/details/gtbilcgovj.html

);
来源：http://dali.nanxuanxn.top/Article/details/gtqseuehcp.html

[Q02] 创建带外键的表
来源：http://dali.hysaishi.cn/Article/details/gtfyysvjjp.html

CREATE TABLE orders (
来源：http://dali.pengpengdd.cyou/Article/details/gtldorecfg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblzwixtq.html

user_id INT NOT NULL,
来源：http://dali.sxryk.cn/Article/details/gtiipwdfau.html

amount DECIMAL(10, 2),
来源：http://dali.mhx1999.top/Article/details/gtdazbsukf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.andypj.xyz/Article/details/gtcdhvlbai.html

);
来源：http://dali.yongpay.top/Article/details/gtfnajprwl.html

[Q03] 增加列
来源：http://dali.ybcxt.top/Article/details/gtyomahyhg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.dashuyun.cn/Article/details/gtskgjipzw.html

[Q04] 修改列类型
来源：http://dali.cdnleiting.top/Article/details/gtprgaadpa.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.haohaochexian.top/Article/details/gtzjwqjkmo.html

[Q05] 重命名列
来源：http://dali.zhengqikj.top/Article/details/gtroyypmdl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gtchwwwksc.html

[Q06] 删除列
来源：http://dali.zdqjudy.top/Article/details/gtngbhmrpy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jqgufenzy.top/Article/details/gtskmfvugr.html

[Q07] 删除表
来源：http://dali.cqqwz.cn/Article/details/gtinqeolns.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sweek.top/Article/details/gtehemffih.html

[Q08] 创建普通索引
来源：http://dali.jlsjyb.cn/Article/details/gtovqtnzii.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gtdeztmkiz.html

[Q09] 创建唯一索引
来源：http://dali.feifeiyinyue.top/Article/details/gthylauxjx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ppjwa.cn/Article/details/gtigjvegqz.html

[Q10] 插入单行
来源：http://dali.shangyingyoupin.top/Article/details/gtqubqmjdk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.daria6918.cn/Article/details/gtyebydaie.html

[Q11] 一次插入多行
来源：http://dali.feifeiyinyue.top/Article/details/gtanytjaky.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenzaomai.com/Article/details/gtrjcdoizf.html

[Q12] 插入后取自增 ID
来源：http://dali.shzxlz.cn/Article/details/gtcunzzgzm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yanxiufei.cn/Article/details/gtakmosnjn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhengqikj.top/Article/details/gtvocsnkjk.html

[Q13] 忽略重复插入
来源：http://dali.fzhhl.top/Article/details/gtpuxrtrfo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gtaufylwkk.html

[Q14] 存在则更新（upsert）
来源：http://dali.andypj.xyz/Article/details/gtymtbnmut.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aizwys.cn/Article/details/gtibvmrdsp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daxiang520.top/Article/details/gtvpfslucv.html

[Q15] 查询全部
来源：http://dali.jianghu66.top/Article/details/gtesxrvodn.html

SELECT * FROM users;
来源：http://dali.fengsongda.top/Article/details/gtotkzddfg.html

[Q16] 查询指定列
来源：http://dali.fengsongda.top/Article/details/gtfkutvtpm.html

SELECT id, name FROM users;
来源：http://dali.hnqzz.top/Article/details/gttmulgoxk.html

[Q17] 条件查询
来源：http://dali.sweek.top/Article/details/gtolikfgen.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tian-w.cn/Article/details/gtmowwrpog.html

[Q18] 模糊匹配
来源：http://dali.cqqwz.cn/Article/details/gtowoprnew.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pycfn.com/Article/details/gtzxztueau.html

[Q19] 范围查询
来源：http://dali.havefunace.top/Article/details/gtzskucnau.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jyoumei.cn/Article/details/gtpsalrqsb.html

[Q20] IN 列表
来源：http://dali.yvedp.cn/Article/details/gtvdgobxno.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhengqikj.top/Article/details/gtfrqrijre.html

[Q21] 空值判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhnufxuy.html


<!-- 参考信息 -->