代发 wailian999

[N01] 二分查找（有序数组）
来源：http://dali.fengsongda.top/Article/details/gtwdhhjcqj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtweydiiyh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tanke756.top/Article/details/gtxmxfqojc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gtorphzkbd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guowangkeji.top/Article/details/gtpvbxnnwu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtuioafbeh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gthcvcaplc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.haohaochexian.top/Article/details/gtcoqdgbau.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtkyijtmrb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.kuanghao11.cn/Article/details/gtpczqplen.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gotoacloud.top/Article/details/gtmzoqdbic.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daxiang520.top/Article/details/gtxuapywfv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzturenp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtzexiaawt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ybcxt.top/Article/details/gtuzyuvxcm.html

Go:   slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtvyrhumkt.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gtafjujuah.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gogol.net.cn/Article/details/gtpylifzan.html

[N03] 快速排序（分治示例）
来源：http://dali.sysykeji.top/Article/details/gtqcladbly.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhiwuduotai.top/Article/details/gtjznmxquu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cashguo.top/Article/details/gtssderkxz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zycfv.cn/Article/details/gtlylblqek.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gtxkxtuvaz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ppjwa.cn/Article/details/gtaqeykwqx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nwbrower.top/Article/details/gtaxulrnwg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenjidiqi.icu/Article/details/gtydbgvcnq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.pycfn.com/Article/details/gtagfxxsyy.html

[N04] 斐波那契数列
来源：http://dali.hfpthk.cn/Article/details/gtctoxcvil.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtmmdibqwh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.meibo888.top/Article/details/gtszwlxdkr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gtnwhkwiow.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdeepyrqj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gthairguif.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jianghu66.top/Article/details/gtdqvahjsz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gtvzvvplfh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gthdixbzvd.html

[N05] 最大公约数
来源：http://dali.ivvv.top/Article/details/gtxsiyhtrq.html

Py:   math.gcd(a, b)
来源：http://dali.fzhhl.top/Article/details/gtlnbudcmf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jianghu66.top/Article/details/gtdclwtloy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gtzturrtyr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gtkhundykc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenjidiqi.icu/Article/details/gtzqkstmes.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnxiangtu.top/Article/details/gtfqvvbwrm.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkspfuqc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.andypj.xyz/Article/details/gtjocsizll.html

[N06] 判断回文字符串
来源：http://dali.gotoacloud.top/Article/details/gtcqsodwtj.html

Py:   s == s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gtkysxvibq.html

PHP:  $s === strrev($s);
来源：http://dali.hammf.cn/Article/details/gtjtqydzvp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtsmbakemo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtotkrgsjz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.andypj.xyz/Article/details/gtsyemmvjb.html

Go:   // 双指针从两端比较
来源：http://dali.yvedp.cn/Article/details/gtyxnztwon.html

Ruby: s == s.reverse
来源：http://dali.ivvv.top/Article/details/gtrtqepeaf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hammf.cn/Article/details/gtwxylnkrv.html

[N07] 两数之和（返回下标）
来源：http://dali.redwolf501.top/Article/details/gtijveoulv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pengpengdd.cyou/Article/details/gtelcanhef.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.aibaodan.cn/Article/details/gtqgtmnxxd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.bjfxy.top/Article/details/gtwpymjmtb.html

TS:   // 手写 Map<string, number>
来源：http://dali.aibaodan.cn/Article/details/gtcgxijyyv.html

Java: // 手写 HashMap
来源：http://dali.vqdsnc.cn/Article/details/gtxophyirr.html

Go:   // 手写 map[int]int
来源：http://dali.gaohongyu789.top/Article/details/gtcmpvbguj.html

Ruby: // 手写 Hash
来源：http://dali.cashguo.top/Article/details/gtlnebpcop.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jyoumei.cn/Article/details/gtpoypyyrc.html

[N08] 生成全排列
来源：http://dali.jqgufenzy.top/Article/details/gtabmkfuvx.html

Py:   itertools.permutations(arr)
来源：http://dali.svipenyu.cn/Article/details/gtsoxpvfpf.html

PHP:  // 手写递归交换
来源：http://dali.zhongyouzk.top/Article/details/gteigegpkr.html

JS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gthdcalaog.html

TS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtxfvfzisc.html

Java: // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtfkevexjx.html

Go:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtclucfmmb.html

Ruby: arr.permutation.to_a
来源：http://dali.yangfankeji.com/Article/details/gtnaimjajd.html

C#:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtfbnucbra.html

[N09] 栈与队列
来源：http://dali.yj202588.top/Article/details/gtanogdjlm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ppjwa.cn/Article/details/gtprskqfhu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtnvihhaxr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258888.top/Article/details/gtnuytfxoz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhengqikj.top/Article/details/gtsyyffhou.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258.top/Article/details/gtibdhsfec.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shangyingyoupin.top/Article/details/gtunmrkomt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtantixnsf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gtktgoxxul.html

[N10] 链表节点定义
来源：http://dali.wangshuangyany.cn/Article/details/gtvagzzdic.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sufxvd.cn/Article/details/gtsdoyyjfa.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ehwqpu.com/Article/details/gtjumjzixh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.haohaochexian.top/Article/details/gtjmddsxqs.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ydzc1.top/Article/details/gthpblhxfi.html

Java: class Node { int v; Node next; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxfxiriyt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daxiang520.top/Article/details/gtarbwnmyn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinqigufen.top/Article/details/gtfxetrzfi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tian-w.cn/Article/details/gtziqxidre.html

[N11] 二叉树中序遍历
来源：http://dali.snrcjt.cn/Article/details/gtffyhlcnu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xylfe.cn/Article/details/gtyybolkne.html

PHP:  // 手写递归函数
来源：http://dali.jiagoushi.top/Article/details/gtiadtvtsv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gtuizvnwpc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gtzkxxmigr.html

Java: // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhuupirc.html

Go:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gttzcgnplx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinghuilouyu.cn/Article/details/gtlexwplbw.html

C#:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gtcickthtg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gtlerjpufj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.snrcjt.cn/Article/details/gtmajavpcl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinghuilouyu.cn/Article/details/gtbkzpjrjs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhengqikj.top/Article/details/gtgajiehdv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigufen.top/Article/details/gtoenlifvf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jyoumei.cn/Article/details/gtovycbiax.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cashguo.top/Article/details/gtbudraiyx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.svipenyu.cn/Article/details/gtmuvawbsh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gtnpblcola.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtbgizmmlz.html

O. 并发与异步
来源：http://dali.jianghu66.top/Article/details/gtdxsbfcex.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtamfeihsd.html

[O01] 启动一个线程
来源：http://dali.guannengcc.top/Article/details/gtztvdzyae.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjsjfetk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jlsjyb.cn/Article/details/gtkrtvztyq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnqzz.top/Article/details/gttvrtitcz.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gtceobraku.html

Java: new Thread(() -> f()).start()
来源：http://dali.iojbl.cn/Article/details/gtgashumbg.html

Go:   go f()
来源：http://dali.shuidangran.top/Article/details/gtvaklebse.html

Ruby: Thread.new { f }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqcvfzsv.html

C#:   Task.Run(() => F());
来源：http://dali.9152youxi.cn/Article/details/gtibnfhiyr.html

[O02] 使用线程池
来源：http://dali.bjfxy.top/Article/details/gtooskgaiw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hysaishi.cn/Article/details/gtznbzgdgg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xylfe.cn/Article/details/gtbwlwkujf.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtezbwkqgp.html

TS:   // worker_threads 线程池
来源：http://dali.fzhhl.top/Article/details/gtnujkvsfl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxuanxn.top/Article/details/gtfturynwc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkvvcmbm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgufenzy.top/Article/details/gtekfofcfd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gaohongyu789.top/Article/details/gtqxfzllxm.html

[O03] 加锁保护共享数据
来源：http://dali.sweek.top/Article/details/gtjgqncdou.html

Py:   with lock: shared += 1
来源：http://dali.jqgfzy.top/Article/details/gtubiyofca.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgufenzy.top/Article/details/gtabsiizit.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdxwjuwi.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gtwlplllqg.html

Java: synchronized (this) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrcepdoup.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuxming.cn/Article/details/gtffdkepqr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gzhubu.top/Article/details/gtaxnoojmb.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtptwhjjbu.html

[O04] 定义异步函数并等待
来源：http://dali.redwolf501.top/Article/details/gtlmrrcdeg.html

Py:   async def f():⏎    await g()
来源：http://dali.shangyingyoupin.top/Article/details/gtsqglkqyj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpbnsxpp.html

JS:   async function f() { await g(); }
来源：http://dali.redwolf501.top/Article/details/gtnupnwdqg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gtfdztvwnk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhoulong.xyz/Article/details/gtlstjonrk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daxiang520.top/Article/details/gtmfjmuigd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gzhubu.top/Article/details/gtvzcvjtuv.html

C#:   async Task F() { await G(); }
来源：http://dali.hammf.cn/Article/details/gttkdnefqd.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhengqikj.top/Article/details/gthsyvnxmq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daria6918.cn/Article/details/gttryijcug.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.feifeiyinyue.top/Article/details/gtasfyjren.html

JS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gtarbdhtdq.html

TS:   await Promise.all(tasks)
来源：http://dali.fengsongda.top/Article/details/gtxxcohhog.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shuidangran.top/Article/details/gtuttqnwrn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hysaishi.cn/Article/details/gttdhpxlni.html

Ruby: threads.map(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gtvbevrsfh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pycfn.com/Article/details/gtipkorcoa.html

[O06] 使用进程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnndnteav.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hongshengwenyu.top/Article/details/gtephjmxnp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnqzz.top/Article/details/gtlmwwbtsb.html

JS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gtdxgwvgwr.html

TS:   // child_process / cluster 模块
来源：http://dali.cheryme.top/Article/details/gtkseiibtr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zycfv.cn/Article/details/gtlphzrerk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.9152youxi.cn/Article/details/gtpprknpfh.html

Ruby: // fork 块
来源：http://dali.yuanzhike.top/Article/details/gthndwdnnj.html

C#:   Parallel.For
来源：http://dali.zhiwuduotai.top/Article/details/gthgwcxobo.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvpjfius.html

P. 常用工具函数
来源：http://dali.guannengcc.top/Article/details/gtuoklgbxv.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtqtqjjtyu.html

[P01] 生成 UUID
来源：http://dali.jianghu66.top/Article/details/gtdewctgqd.html

Py:   str(uuid.uuid4())
来源：http://dali.xinyue.icu/Article/details/gtiamqmjhg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhixingplan.top/Article/details/gtydljunes.html

JS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gtyzwkheyn.html

TS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtwxsywqwj.html

Java: UUID.randomUUID().toString()
来源：http://dali.jianghu66.top/Article/details/gtnexakwcq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jlsjyb.cn/Article/details/gtziwudfbp.html

Ruby: SecureRandom.uuid
来源：http://dali.nwbrower.top/Article/details/gtsvtgewft.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnxiangtu.top/Article/details/gtmlhvxvsb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jianghu66.top/Article/details/gtbmsjljyl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hywenlv.cn/Article/details/gtmzvplfxh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hywenlv.cn/Article/details/gtkiilhbpb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xziqi.cn/Article/details/gtmylpawwh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hammf.cn/Article/details/gthdlxbgbs.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gtnlrikzdb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yanxiufei.cn/Article/details/gtjcgnqeri.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrtyfamf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangshuangyany.cn/Article/details/gtobmdddja.html

[P03] 生成短随机字符串
来源：http://dali.sysykeji.top/Article/details/gtdxqmkapy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jianghu66.top/Article/details/gtpksokprp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinqigfzy.top/Article/details/gtivndtesh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gtwzpdwtka.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gttaiqbche.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shuidangran.top/Article/details/gtgagpxevf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pycfn.com/Article/details/gtysjtmwuf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dashuyun.cn/Article/details/gtwzdijhoy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhiwuduotai.top/Article/details/gtnxrripud.html

[P04] 求长度
来源：http://dali.cucudq.cn/Article/details/gtnkxufvyz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cashguo.top/Article/details/gtmeuojjjt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtotxmbyjb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenzaomai.com/Article/details/gtdpwvlrzz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.andypj.xyz/Article/details/gtdcqnwifb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shzxlz.cn/Article/details/gthjmgmzfc.html

Go:   len(arr);  len(m)
来源：http://dali.meibo888.top/Article/details/gtxilmbscn.html

Ruby: x.length;  x.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgigdjfgd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sxryk.cn/Article/details/gtwsgqzxxy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ehwqpu.com/Article/details/gtrbezhbyr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yuanzhike.top/Article/details/gtbylwhkko.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ybcxt.top/Article/details/gtyxifqihn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.316326.xyz/Article/details/gteonsfyjq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.vqdsnc.cn/Article/details/gtjgzynwxz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sweek.top/Article/details/gtetfewdun.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yueranfly.top/Article/details/gtqvluzxkl.html

Ruby: a == b
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmefwcpa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.quarkkingdee.top/Article/details/gtnmthcpxm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.andypj.xyz/Article/details/gtxxqnkwyp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.daria6918.cn/Article/details/gtzllergfa.html

PHP:  if (empty($x)) {}
来源：http://dali.fengsongda.top/Article/details/gtobnrfruu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.redwolf501.top/Article/details/gtasfgthib.html

TS:   if (x == null) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtrgwedidv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zycfv.cn/Article/details/gtolrzaqun.html

Go:   if x == nil {}
来源：http://dali.yonumen.top/Article/details/gtqktieusr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cheryme.top/Article/details/gtxebjudep.html

C#:   if (x is null) {}
来源：http://dali.nwbrower.top/Article/details/gtjnxloueo.html

[P07] 防抖与节流
来源：http://dali.svipenyu.cn/Article/details/gtgdwzsbea.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hfpthk.cn/Article/details/gtpswvmknn.html

PHP:  // 手写时间戳比较
来源：http://dali.yvedp.cn/Article/details/gtlkyyvlkb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gthyawviot.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtobyiooou.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tanke756.top/Article/details/gtmbndabrr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fengsongda.top/Article/details/gtjmlbyfde.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tian-w.cn/Article/details/gtxzboafpl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yvedp.cn/Article/details/gtjjqiqvxl.html

[P08] 处理浮点精度问题
来源：http://dali.9152youxi.cn/Article/details/gtajfldbst.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cdnleiting.top/Article/details/gtvkmcnplc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.c1oappe.top/Article/details/gtwxyupivn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fzhhl.top/Article/details/gtsffjzfrm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yanxiufei.cn/Article/details/gtxhsswmeo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhoulong.xyz/Article/details/gtabrbhdgt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hammf.cn/Article/details/gtyboegwsh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.pycfn.com/Article/details/gtvhzrczis.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gaohongyu789.top/Article/details/gtjpmxsrru.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtjfqrzpoa.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.daxiang520.top/Article/details/gtfulcfknl.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtucncpbdj.html

[Q01] 创建表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuycvuyia.html

CREATE TABLE users (
来源：http://dali.cucudq.cn/Article/details/gtlenighmt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gtlwqcfxsq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangtech.top/Article/details/gtymjmehrw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.havefunace.top/Article/details/gtjgliwdcy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258888.top/Article/details/gtuydfxptw.html

);
来源：http://dali.316326.xyz/Article/details/gtiidsyfyu.html

[Q02] 创建带外键的表
来源：http://dali.tian-w.cn/Article/details/gtnssairft.html

CREATE TABLE orders (
来源：http://dali.sweek.top/Article/details/gtcwtbrtce.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmjabobm.html

user_id INT NOT NULL,
来源：http://dali.aibaodan.cn/Article/details/gtvbxvgptx.html

amount DECIMAL(10, 2),
来源：http://dali.9152youxi.cn/Article/details/gtyblaaeqv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yonumen.top/Article/details/gtxsbfdxzb.html

);
来源：http://dali.yongpay.top/Article/details/gthnfvrnox.html

[Q03] 增加列
来源：http://dali.hammf.cn/Article/details/gtictioatg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pengpengdd.cyou/Article/details/gtevjmkrrj.html

[Q04] 修改列类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcqndimv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuxming.cn/Article/details/gtfslgrebj.html

[Q05] 重命名列
来源：http://dali.svipenyu.cn/Article/details/gtixjfaunc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfbovrvw.html

[Q06] 删除列
来源：http://dali.yuxming.cn/Article/details/gtbiosvqbu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gaohongyu789.top/Article/details/gtonqaztva.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gtpitsiiyw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yueranfly.top/Article/details/gtrwrfzcxm.html

[Q08] 创建普通索引
来源：http://dali.havefunace.top/Article/details/gtajbjdcce.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aibaodan.cn/Article/details/gtrtjboile.html

[Q09] 创建唯一索引
来源：http://dali.ybcxt.top/Article/details/gtdwuuixio.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gtmydwefga.html

[Q10] 插入单行
来源：http://dali.hnqzz.top/Article/details/gtiwmgijgo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aizwys.cn/Article/details/gtvietlsdw.html

[Q11] 一次插入多行
来源：http://dali.dashuyun.cn/Article/details/gteqgqlcdl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtoetyudlu.html

[Q12] 插入后取自增 ID
来源：http://dali.chenzaomai.com/Article/details/gtiaskngil.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangdashe.top/Article/details/gtnhojobcw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tanke756.top/Article/details/gtcmeamqok.html

[Q13] 忽略重复插入
来源：http://dali.aizwys.cn/Article/details/gtbhxitkur.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.c1oappe.top/Article/details/gtbgfegmyh.html

[Q14] 存在则更新（upsert）
来源：http://dali.ybcxt.top/Article/details/gtkoqssxqb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zdqjudy.top/Article/details/gtzswwwuce.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgfzy.top/Article/details/gtmincujum.html

[Q15] 查询全部
来源：http://dali.0kj1m.cn/Article/details/gtlvbsbwsc.html

SELECT * FROM users;
来源：http://dali.yueranfly.top/Article/details/gtpwpuaode.html

[Q16] 查询指定列
来源：http://dali.jiagoushi.top/Article/details/gtloxscbxf.html

SELECT id, name FROM users;
来源：http://dali.ivvv.top/Article/details/gtbvxcemsn.html

[Q17] 条件查询
来源：http://dali.chenzaomai.com/Article/details/gtvpvepntk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhixingplan.top/Article/details/gtueulomst.html

[Q18] 模糊匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtuyleycmc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxuanxn.top/Article/details/gtiybvexqo.html

[Q19] 范围查询
来源：http://dali.yuanzhike.top/Article/details/gtklysacel.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.bjfxy.top/Article/details/gtlyxptmbn.html

[Q20] IN 列表
来源：http://dali.hfpthk.cn/Article/details/gtlgvqhjnv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtcmyoydfw.html

[Q21] 空值判断
来源：http://dali.iojbl.cn/Article/details/gtoxqwkzks.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.birdmap.top/Article/details/gtpalibsxh.html

[Q22] 排序
来源：http://dali.ybcxt.top/Article/details/gtnwrprouz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.guowangkeji.top/Article/details/gtphbynqwm.html

[Q23] 分页
来源：http://dali.kuanghao11.cn/Article/details/gtgwjzfojw.html


<!-- 参考信息 -->