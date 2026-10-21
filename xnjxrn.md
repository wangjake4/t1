代发 wailian999

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtfhmmqjym.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtgtsjwpcz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtfwtorika.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aizwys.cn/Article/details/gtqbcqofwv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtxviafrep.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yangfankeji.com/Article/details/gtavfgzwuj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yueranfly.top/Article/details/gttugvcsyi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.birdmap.top/Article/details/gtugdsasic.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gtwqhzcmof.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gturpaznup.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sweek.top/Article/details/gtlhlpvelo.html

Go:   slices.Sort(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpfwvsbv.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gtzqhoignt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hfpthk.cn/Article/details/gtjzbofnam.html

[N03] 快速排序（分治示例）
来源：http://dali.yongpay.top/Article/details/gtohlshksc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tianlin.xyz/Article/details/gtdmrydijs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvxhpqog.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.smart0.xyz/Article/details/gtfkrzgktb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gtdivjcaon.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dashuyun.cn/Article/details/gtzeptxmbq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgufenzy.top/Article/details/gtnuxnazlc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yongpay.top/Article/details/gterrivsmw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yongpay.top/Article/details/gtbiusbbde.html

[N04] 斐波那契数列
来源：http://dali.xylfe.cn/Article/details/gtkcspcezk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gtfqvgbpvf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sxryk.cn/Article/details/gttjmwosqg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gtixhczipv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtjrsyzodu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gtjskgtgze.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ppjwa.cn/Article/details/gtqbjotydt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtxnyrzdtw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gthgsbrrev.html

[N05] 最大公约数
来源：http://dali.nanxinkj.top/Article/details/gtupcjgnha.html

Py:   math.gcd(a, b)
来源：http://dali.yongpay.top/Article/details/gtofixzwqb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jyoumei.cn/Article/details/gtxpaszpdy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gtkfokkmyf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gtvjoigymh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hfpthk.cn/Article/details/gtvqhvmgtz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigfzy.top/Article/details/gtqcpragqw.html

Ruby: a.gcd(b)
来源：http://dali.nanxuanxn.top/Article/details/gtydxvqmmb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.pycfn.com/Article/details/gtimzbypxe.html

[N06] 判断回文字符串
来源：http://dali.fengsongda.top/Article/details/gtogrrktjw.html

Py:   s == s[::-1]
来源：http://dali.cheryme.top/Article/details/gtybhbtdsh.html

PHP:  $s === strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gttjedvlke.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtdyvykudq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtltlpuqhf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.snrcjt.cn/Article/details/gtpftfuzaz.html

Go:   // 双指针从两端比较
来源：http://dali.jqgfzy.top/Article/details/gtefuodily.html

Ruby: s == s.reverse
来源：http://dali.nanxinkj.top/Article/details/gtwbdhuhpn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yueranfly.top/Article/details/gthezrujyn.html

[N07] 两数之和（返回下标）
来源：http://dali.nwbrower.top/Article/details/gtunvhemie.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hongshengwenyu.top/Article/details/gtswkdimhs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shangyingyoupin.top/Article/details/gtioaokuhn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aibaodan.cn/Article/details/gtfnobxjbp.html

TS:   // 手写 Map<string, number>
来源：http://dali.sysykeji.top/Article/details/gtdpjrllzf.html

Java: // 手写 HashMap
来源：http://dali.gogol.net.cn/Article/details/gtpvioapnc.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gtinruyjjb.html

Ruby: // 手写 Hash
来源：http://dali.jlsjyb.cn/Article/details/gtcstsenlc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ydzc1.top/Article/details/gtlazqdjax.html

[N08] 生成全排列
来源：http://dali.aizwys.cn/Article/details/gthfvqkbdz.html

Py:   itertools.permutations(arr)
来源：http://dali.hywenlv.cn/Article/details/gtzpxgnwvb.html

PHP:  // 手写递归交换
来源：http://dali.xinyue.icu/Article/details/gtuumgrpnk.html

JS:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlbbrdbz.html

TS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gthdckmwdx.html

Java: // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtorikdngp.html

Go:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtnaortxhj.html

Ruby: arr.permutation.to_a
来源：http://dali.iojbl.cn/Article/details/gtqwiftruu.html

C#:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtsjmsxjcu.html

[N09] 栈与队列
来源：http://dali.zhengqikj.top/Article/details/gtrtqgevmx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhengqikj.top/Article/details/gtegbnljne.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtbqfyncdf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gtcjigxlnp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.daxiang520.top/Article/details/gtjbdobinr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aibaodan.cn/Article/details/gtqjzhcdia.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yueranfly.top/Article/details/gtzxvgbohi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gthmwiyqmo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.mhx1999.top/Article/details/gtptbhlyvr.html

[N10] 链表节点定义
来源：http://dali.yangfankeji.com/Article/details/gtowfwcjtt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guowangkeji.top/Article/details/gtnkmgmnfs.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuxming.cn/Article/details/gtkjgcfzqo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.pycfn.com/Article/details/gtgdbisuum.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shuidangran.top/Article/details/gtdpbtlexq.html

Java: class Node { int v; Node next; }
来源：http://dali.daxiang520.top/Article/details/gtfgrzsaii.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.guannengcc.top/Article/details/gtnihdljyn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.quarkkingdee.top/Article/details/gtgzzfpulb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shangyingyoupin.top/Article/details/gtkxwgqlwf.html

[N11] 二叉树中序遍历
来源：http://dali.ydzc1.top/Article/details/gtdxfnnipy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guowangkeji.top/Article/details/gtuvtomogl.html

PHP:  // 手写递归函数
来源：http://dali.cucudq.cn/Article/details/gtsplutydu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gtsaamzfpr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gtlgkakxxm.html

Java: // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtmlurzlyb.html

Go:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gtwgljpvpj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuanzhike.top/Article/details/gtdnpafbar.html

C#:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtnqtcnwpx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ehwqpu.com/Article/details/gteqshlxit.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gogol.net.cn/Article/details/gtpotzrvgj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.meibo888.top/Article/details/gtbdiekzsf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gtgfnskvqz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gtdtrninxs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gtnonasiis.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xuetiantiany.cn/Article/details/gtzojnfeca.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gthxmvtqpo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gtzgmqwuvo.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtmmcigugi.html

O. 并发与异步
来源：http://dali.zhixingplan.top/Article/details/gtluzneoiw.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtfghljcph.html

[O01] 启动一个线程
来源：http://dali.hysaishi.cn/Article/details/gtjudhdzja.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ivvv.top/Article/details/gtpkegbznx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.fengsongda.top/Article/details/gtjwgxdoql.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hongshengwenyu.top/Article/details/gtmfjbycju.html

TS:   // 同 JS
来源：http://dali.gzhubu.top/Article/details/gtyxynjugn.html

Java: new Thread(() -> f()).start()
来源：http://dali.gaohongyu789.top/Article/details/gtmeprctma.html

Go:   go f()
来源：http://dali.haohaochexian.top/Article/details/gthexiccii.html

Ruby: Thread.new { f }
来源：http://dali.yueranfly.top/Article/details/gttpehpgii.html

C#:   Task.Run(() => F());
来源：http://dali.jqgfzy.top/Article/details/gthhakxpkh.html

[O02] 使用线程池
来源：http://dali.pycfn.com/Article/details/gtwknwhszm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hywenlv.cn/Article/details/gtbneowjcl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cashguo.top/Article/details/gthphdofvr.html

JS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gtmxynirmp.html

TS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gtgymzwhxg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangshuangyany.cn/Article/details/gtiwvevtkx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxinkj.top/Article/details/gtsomcdkck.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ydzc1.top/Article/details/gtptzfvqtf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cdnleiting.top/Article/details/gtppjojpra.html

[O03] 加锁保护共享数据
来源：http://dali.tianlin.xyz/Article/details/gtcbpeppvt.html

Py:   with lock: shared += 1
来源：http://dali.jlsjyb.cn/Article/details/gtgddwaifo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj202588.top/Article/details/gtwsjzblua.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.c1oappe.top/Article/details/gtgfnerqdc.html

TS:   // 同 JS
来源：http://dali.meibo888.top/Article/details/gtnuxvnear.html

Java: synchronized (this) { shared++; }
来源：http://dali.tian-w.cn/Article/details/gtrznljgrg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cdnleiting.top/Article/details/gtvhwahlrx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xylfe.cn/Article/details/gtbxcygmna.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenlongwang.top/Article/details/gtdbrkpgqe.html

[O04] 定义异步函数并等待
来源：http://dali.ppjwa.cn/Article/details/gtipnnzwxm.html

Py:   async def f():⏎    await g()
来源：http://dali.pengpengdd.cyou/Article/details/gtsdhreznr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nwbrower.top/Article/details/gtwdinxkgs.html

JS:   async function f() { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gtsjfezbef.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tian-w.cn/Article/details/gtwjuzceqd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.mhx1999.top/Article/details/gtgcdmboju.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangtech.top/Article/details/gthxafhtjn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fzhhl.top/Article/details/gtodknvlts.html

C#:   async Task F() { await G(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltyvjajp.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhengqikj.top/Article/details/gtumvalglj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ehwqpu.com/Article/details/gteuvipcdj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.c1oappe.top/Article/details/gtpvizciuh.html

JS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gtpqdsfzvi.html

TS:   await Promise.all(tasks)
来源：http://dali.gogol.net.cn/Article/details/gtbpnseric.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxuanxn.top/Article/details/gtfrckhemj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daria6918.cn/Article/details/gtdlpqsjqs.html

Ruby: threads.map(&:join)
来源：http://dali.wangshuangyany.cn/Article/details/gtwozmtmsw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.aibaodan.cn/Article/details/gtpwmokndt.html

[O06] 使用进程池
来源：http://dali.wangdashe.top/Article/details/gtvwcabhlh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.mhx1999.top/Article/details/gtxvncmhxt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yanxiufei.cn/Article/details/gtzfgsqbmg.html

JS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gteqtblslz.html

TS:   // child_process / cluster 模块
来源：http://dali.fzhhl.top/Article/details/gtiwaksvco.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.birdmap.top/Article/details/gtkcbdwoye.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.dashuyun.cn/Article/details/gtjmwyvoee.html

Ruby: // fork 块
来源：http://dali.ivvv.top/Article/details/gtnzyzukxf.html

C#:   Parallel.For
来源：http://dali.ppjwa.cn/Article/details/gttcddxeqt.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtyrfnxwht.html

P. 常用工具函数
来源：http://dali.zhoulong.xyz/Article/details/gtyikmwxnl.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gttevazjjq.html

[P01] 生成 UUID
来源：http://dali.birdmap.top/Article/details/gtxcgglugk.html

Py:   str(uuid.uuid4())
来源：http://dali.cheryme.top/Article/details/gtxjrttzvg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yueranfly.top/Article/details/gtgmplgnxw.html

JS:   crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gtmphbqfxl.html

TS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gtomkvosvy.html

Java: UUID.randomUUID().toString()
来源：http://dali.tanke756.top/Article/details/gtrdoazjck.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sxryk.cn/Article/details/gtfwdphybb.html

Ruby: SecureRandom.uuid
来源：http://dali.smart0.xyz/Article/details/gttygxxwuz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cashguo.top/Article/details/gteakkyqqe.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shuidangran.top/Article/details/gtojxqsrhg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jqgfzy.top/Article/details/gtkdeyadxh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gotoacloud.top/Article/details/gtplmsakva.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gzhubu.top/Article/details/gtrhatfxsi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dianchejie.cn/Article/details/gtvmbebdnc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pycfn.com/Article/details/gtvgqaapne.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgufenzy.top/Article/details/gtsaegmlza.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.mhx1999.top/Article/details/gtlskbzkuf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yueranfly.top/Article/details/gtflttaxco.html

[P03] 生成短随机字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjapvmwb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hysaishi.cn/Article/details/gtqgnnjvwx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnqzz.top/Article/details/gtxcsggmhg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gterxcyhdj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gtyzejeebp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ydzc1.top/Article/details/gtnodstlxh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yuanzhike.top/Article/details/gtbqxnhyww.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.bjfxy.top/Article/details/gthecobeej.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.pengpengdd.cyou/Article/details/gthhbblhrp.html

[P04] 求长度
来源：http://dali.quarkkingdee.top/Article/details/gtwdkwfxqn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sysykeji.top/Article/details/gtmxjbgezy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtuaiecoie.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gtbulhwezr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gtvrzalghb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenlongwang.top/Article/details/gtipdoxxnr.html

Go:   len(arr);  len(m)
来源：http://dali.feifeiyinyue.top/Article/details/gtcpjgsefv.html

Ruby: x.length;  x.size
来源：http://dali.wangdashe.top/Article/details/gtzicenect.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.guannengcc.top/Article/details/gttzhuezaa.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xinyue.icu/Article/details/gtfxfvbugc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cqqwz.cn/Article/details/gtljhmbmhi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daxiang520.top/Article/details/gtcbqrwdnp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ybcxt.top/Article/details/gtkvhefurz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gtbgfawvub.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.daxiang520.top/Article/details/gttixppvwt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gtgxxfynzw.html

Ruby: a == b
来源：http://dali.zycfv.cn/Article/details/gtlfqpbsgj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hongshengwenyu.top/Article/details/gtwrwqgzkj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangshuangyany.cn/Article/details/gtdnsaqtft.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gotoacloud.top/Article/details/gtfflvsnjq.html

PHP:  if (empty($x)) {}
来源：http://dali.bjfxy.top/Article/details/gtqvtcppqp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.iojbl.cn/Article/details/gtymgfjeur.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfeiecnv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yuanzhike.top/Article/details/gtgjrdxgcw.html

Go:   if x == nil {}
来源：http://dali.xylfe.cn/Article/details/gteqeztsub.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cdnleiting.top/Article/details/gtvzqiktae.html

C#:   if (x is null) {}
来源：http://dali.mhx1999.top/Article/details/gtaelglvby.html

[P07] 防抖与节流
来源：http://dali.tanke756.top/Article/details/gtsqloapel.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.fengsongda.top/Article/details/gtqnurfequ.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258.top/Article/details/gthjcchnzo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gtxhyrrywt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gtqodgpcqv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.redwolf501.top/Article/details/gtkawoawzv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhengqikj.top/Article/details/gtxkcpjjta.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shuidangran.top/Article/details/gtggyfruyb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxowpkap.html

[P08] 处理浮点精度问题
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdppedbr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hfpthk.cn/Article/details/gtmhpbchov.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yanxiufei.cn/Article/details/gtxrwxzegq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ehwqpu.com/Article/details/gtbcbapwey.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteaguztgl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nanxinkj.top/Article/details/gtkjmydtgm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tian-w.cn/Article/details/gthwkrdtzh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xylfe.cn/Article/details/gtfeiygecx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yuxming.cn/Article/details/gtrkaswlif.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtnnkqpfug.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.redwolf501.top/Article/details/gtetftqewe.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtfecykmdg.html

[Q01] 创建表
来源：http://dali.jqgufenzy.top/Article/details/gtvhhkyfok.html

CREATE TABLE users (
来源：http://dali.nwbrower.top/Article/details/gtlesqgkvt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gtzhlzowzq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.dianchejie.cn/Article/details/gtiridaigy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.redwolf501.top/Article/details/gtqskfqzud.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pycfn.com/Article/details/gtznicngkm.html

);
来源：http://dali.hywenlv.cn/Article/details/gthduibqlo.html

[Q02] 创建带外键的表
来源：http://dali.yuxming.cn/Article/details/gtrglmeiou.html

CREATE TABLE orders (
来源：http://dali.iojbl.cn/Article/details/gtscmereuq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xziqi.cn/Article/details/gtsymgtycg.html

user_id INT NOT NULL,
来源：http://dali.yangfankeji.com/Article/details/gtmubewyrn.html

amount DECIMAL(10, 2),
来源：http://dali.yongpay.top/Article/details/gtkfeosbzr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yonumen.top/Article/details/gtighlyxsz.html

);
来源：http://dali.jlsjyb.cn/Article/details/gtftipfrkc.html

[Q03] 增加列
来源：http://dali.hongshengwenyu.top/Article/details/gtlosltgfs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shangyingyoupin.top/Article/details/gtwzeopxwi.html

[Q04] 修改列类型
来源：http://dali.iojbl.cn/Article/details/gtzeqdzceh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.kuanghao11.cn/Article/details/gtoenejtli.html

[Q05] 重命名列
来源：http://dali.nanxuanxn.top/Article/details/gtypdvazkt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.316326.xyz/Article/details/gtazhukfqm.html

[Q06] 删除列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjgwsxwp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhoulong.xyz/Article/details/gtsdkdnuqv.html

[Q07] 删除表
来源：http://dali.guannengcc.top/Article/details/gtxoztspts.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcunerck.html

[Q08] 创建普通索引
来源：http://dali.aizwys.cn/Article/details/gtjndgdsae.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gtyyekdful.html

[Q09] 创建唯一索引
来源：http://dali.chenlongwang.top/Article/details/gtgupsmdpi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gtdtbqbpnl.html

[Q10] 插入单行
来源：http://dali.ppjwa.cn/Article/details/gtwqoizvvw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sweek.top/Article/details/gtzkyvqzhv.html

[Q11] 一次插入多行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxltuvuj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtkfllbwjc.html

[Q12] 插入后取自增 ID
来源：http://dali.sysykeji.top/Article/details/gtwxvhifsp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ppjwa.cn/Article/details/gtdvmgmuzq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.bjfxy.top/Article/details/gtcqsrlpam.html

[Q13] 忽略重复插入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgirfrdko.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.redwolf501.top/Article/details/gtpoyzedmr.html

[Q14] 存在则更新（upsert）
来源：http://dali.jiagoushi.top/Article/details/gtddvzpamj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.birdmap.top/Article/details/gtfmdkuopg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nwbrower.top/Article/details/gtfqzdgrvj.html

[Q15] 查询全部
来源：http://dali.kuanghao11.cn/Article/details/gtkkynyvfv.html

SELECT * FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtjkcqzlho.html

[Q16] 查询指定列
来源：http://dali.gogol.net.cn/Article/details/gtjtzkkomj.html

SELECT id, name FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsskeqzwz.html

[Q17] 条件查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmgfxnoo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuxming.cn/Article/details/gtplpbzoil.html

[Q18] 模糊匹配
来源：http://dali.sxryk.cn/Article/details/gtmvaghhpt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtodmehehb.html

[Q19] 范围查询
来源：http://dali.iojbl.cn/Article/details/gtvonlfiyw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shanyushiyangtech.top/Article/details/gtaemjcqce.html

[Q20] IN 列表
来源：http://dali.smart0.xyz/Article/details/gtkoxrdixq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nanxuanxn.top/Article/details/gtivwbnsyy.html

[Q21] 空值判断
来源：http://dali.nwbrower.top/Article/details/gtchnbspdo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shzxlz.cn/Article/details/gtigkgadbb.html

[Q22] 排序
来源：http://dali.ppjwa.cn/Article/details/gtaiaqgkuz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ybcxt.top/Article/details/gttxzkquka.html

[Q23] 分页
来源：http://dali.dashuyun.cn/Article/details/gtrrpctils.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ybcxt.top/Article/details/gtrtxgecmz.html

[Q24] 去重
来源：http://dali.kuanghao11.cn/Article/details/gtwjoobesf.html

SELECT DISTINCT city FROM users;
来源：http://dali.xziqi.cn/Article/details/gtqnzrbdbl.html

[Q25] 只取前 N 条
来源：http://dali.tanke756.top/Article/details/gtjuppftut.html


<!-- 参考信息 -->