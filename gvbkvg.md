代发 wailian999

TS:   process.platform;  process.version
来源：http://dali.yj202588.top/Article/details/gtqnkybzja.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhengqikj.top/Article/details/gtwwsschfx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pengpengdd.cyou/Article/details/gtsteukidz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxuanxn.top/Article/details/gtvtgimcvt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daria6918.cn/Article/details/gtckvvybae.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtgkcwagtj.html

N. 数据结构与算法
来源：http://dali.chenlongwang.top/Article/details/gttcahevgd.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtredmjgal.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxinkj.top/Article/details/gtruzlteze.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtnaogvcrn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtuomtdqon.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gtlidiehkj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gtmkgbjzcl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gtmgxlmapa.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumakzwtp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sxryk.cn/Article/details/gtlubrapet.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirzydwge.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigfzy.top/Article/details/gtwxmmrpny.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gtggyyducd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzitypipr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtchyxlobo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gtjeuworfi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xziqi.cn/Article/details/gtsbondttu.html

Go:   slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gthfbclbpv.html

Ruby: arr.sort
来源：http://dali.jinqigfzy.top/Article/details/gthqmiixni.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dianchejie.cn/Article/details/gtlzjlasmf.html

[N03] 快速排序（分治示例）
来源：http://dali.shangyingyoupin.top/Article/details/gtkthuqdwr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aizwys.cn/Article/details/gttpwtrkod.html

PHP:  // 递归实现，或用 usort
来源：http://dali.316326.xyz/Article/details/gtayuvxjxj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gtmpmkgyuv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gtucndpguw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gotoacloud.top/Article/details/gtmbueypqt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hnqzz.top/Article/details/gtbkjdafzs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.c1oappe.top/Article/details/gthhvrdyll.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenjidiqi.icu/Article/details/gtylqpnihv.html

[N04] 斐波那契数列
来源：http://dali.vqdsnc.cn/Article/details/gtdmcccgdr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gtiknsdrbg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gthnoabpom.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gtbnndqwma.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtenwzxmwg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gtpfyxqcka.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hfpthk.cn/Article/details/gtpiecnykg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.316326.xyz/Article/details/gtnzjhjapn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gtojdansjc.html

[N05] 最大公约数
来源：http://dali.sysykeji.top/Article/details/gtrtzcbgtl.html

Py:   math.gcd(a, b)
来源：http://dali.yuxming.cn/Article/details/gtumkhqbyb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hammf.cn/Article/details/gtyhvqwxkc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigufen.top/Article/details/gtcuijosgt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gtpgqxphxv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hammf.cn/Article/details/gteqekuoji.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dashuyun.cn/Article/details/gtnlfwcguy.html

Ruby: a.gcd(b)
来源：http://dali.jiagoushi.top/Article/details/gtygdfaznr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zdqjudy.top/Article/details/gtdlcqecpd.html

[N06] 判断回文字符串
来源：http://dali.xuanzx.com/Article/details/gtzvhryvxq.html

Py:   s == s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gtymtsrtfk.html

PHP:  $s === strrev($s);
来源：http://dali.cashguo.top/Article/details/gtyimqhdtd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdtewpdl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtbobeuqtx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.daxiang520.top/Article/details/gtdgmdzgti.html

Go:   // 双指针从两端比较
来源：http://dali.ppjwa.cn/Article/details/gtnqqtqglx.html

Ruby: s == s.reverse
来源：http://dali.yuanzhike.top/Article/details/gtgutvnfhv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gtinyrjmxo.html

[N07] 两数之和（返回下标）
来源：http://dali.yuxming.cn/Article/details/gtyummsyjm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhongyouzk.top/Article/details/gtfenvipkh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.daxiang520.top/Article/details/gtqxdcatcc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jiagoushi.top/Article/details/gtiebozylk.html

TS:   // 手写 Map<string, number>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbalntpqi.html

Java: // 手写 HashMap
来源：http://dali.gaohongyu789.top/Article/details/gtifdypquw.html

Go:   // 手写 map[int]int
来源：http://dali.fengsongda.top/Article/details/gtrjpbgnwg.html

Ruby: // 手写 Hash
来源：http://dali.hnqzz.top/Article/details/gtxvydrqep.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jianghu66.top/Article/details/gtszqhyvfq.html

[N08] 生成全排列
来源：http://dali.svipenyu.cn/Article/details/gtxiqnjojq.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtixwvrvzy.html

PHP:  // 手写递归交换
来源：http://dali.chenzaomai.com/Article/details/gtykmmtzhg.html

JS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtgwtpswer.html

TS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtvtcxkmcf.html

Java: // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtofbelbpi.html

Go:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtpbcbioft.html

Ruby: arr.permutation.to_a
来源：http://dali.zycfv.cn/Article/details/gtiwstilfg.html

C#:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtyispslow.html

[N09] 栈与队列
来源：http://dali.hfpthk.cn/Article/details/gtwnmlwixo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj202588.top/Article/details/gtbpbqnxzv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtnmhooctx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gthangovwi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xinyue.icu/Article/details/gtgpodhmjd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gtobkbovdt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtvirzgdyl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gttseggtar.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gtdemcewfm.html

[N10] 链表节点定义
来源：http://dali.zhixingplan.top/Article/details/gtkfukbjdg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.svipenyu.cn/Article/details/gtllvhkanu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuxming.cn/Article/details/gttqhfzhec.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.mhx1999.top/Article/details/gtabtwlden.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hongshengwenyu.top/Article/details/gtrfjlsmky.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhovfezc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.svipenyu.cn/Article/details/gtdllchpnw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.dashuyun.cn/Article/details/gtvlhyfiox.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hongshengwenyu.top/Article/details/gttqkqfzxs.html

[N11] 二叉树中序遍历
来源：http://dali.guowangkeji.top/Article/details/gteaxrlayn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.bjfxy.top/Article/details/gtfemodaqi.html

PHP:  // 手写递归函数
来源：http://dali.yj20258888.top/Article/details/gtdmfmcejg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangdashe.top/Article/details/gtctpnhlyw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gtwfnycvaz.html

Java: // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gtyqgmimsk.html

Go:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gtgbwfazqq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jyoumei.cn/Article/details/gtvydtuhqa.html

C#:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gtpwxbdpcb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.smart0.xyz/Article/details/gtxyhtumjt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tianlin.xyz/Article/details/gtedftfviy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sysykeji.top/Article/details/gtscefukrz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xziqi.cn/Article/details/gtrjfpypch.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gtkxjlqsvd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gtucdssawh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aizwys.cn/Article/details/gtijwvlpzj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuxming.cn/Article/details/gtwvxuvwkg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcuviiitf.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtuhobihgv.html

O. 并发与异步
来源：http://dali.nwbrower.top/Article/details/gtgpmfdnai.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtuthxukrh.html

[O01] 启动一个线程
来源：http://dali.kuanghao11.cn/Article/details/gtplztzpzg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.9152youxi.cn/Article/details/gtzmgdvble.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.vqdsnc.cn/Article/details/gtixahporl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hywenlv.cn/Article/details/gttoosiwna.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gtwdxqaalh.html

Java: new Thread(() -> f()).start()
来源：http://dali.feifeiyinyue.top/Article/details/gttphmlmus.html

Go:   go f()
来源：http://dali.cheryme.top/Article/details/gtlyxybzgd.html

Ruby: Thread.new { f }
来源：http://dali.jinqigufen.top/Article/details/gtkcamhtwv.html

C#:   Task.Run(() => F());
来源：http://dali.hysaishi.cn/Article/details/gtvnolmxre.html

[O02] 使用线程池
来源：http://dali.yj20258888.top/Article/details/gtbktamill.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwvnhosw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gzhubu.top/Article/details/gtcjcflzvf.html

JS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbcpezbw.html

TS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gtarvbykht.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangdashe.top/Article/details/gtsqsqlxyt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.bjfxy.top/Article/details/gtvtmkmxwi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hongshengwenyu.top/Article/details/gtqcitbhsa.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.bjfxy.top/Article/details/gtbqeilqkj.html

[O03] 加锁保护共享数据
来源：http://dali.9152youxi.cn/Article/details/gtnuiysfkx.html

Py:   with lock: shared += 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfgaswwe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tian-w.cn/Article/details/gtrpmreuvk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.aizwys.cn/Article/details/gtjzmgeiqx.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gtvybtjdsh.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctskmckg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ehwqpu.com/Article/details/gtmtjfqnwa.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tanke756.top/Article/details/gttxljdwoe.html

C#:   lock (gate) { shared++; }
来源：http://dali.dashuyun.cn/Article/details/gtmsjyxdui.html

[O04] 定义异步函数并等待
来源：http://dali.gotoacloud.top/Article/details/gtjowtllab.html

Py:   async def f():⏎    await g()
来源：http://dali.ybcxt.top/Article/details/gtaqnwsbqp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pycfn.com/Article/details/gtlxlgzgbi.html

JS:   async function f() { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gtuvuodhjd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gtpillfeee.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hnxiangtu.top/Article/details/gtxfrqmydu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhengqikj.top/Article/details/gthsybthwb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xziqi.cn/Article/details/gtxbfvttqb.html

C#:   async Task F() { await G(); }
来源：http://dali.quarkkingdee.top/Article/details/gtztozbpor.html

[O05] 并发执行并等待全部完成
来源：http://dali.aibaodan.cn/Article/details/gtkvqycfwm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hysaishi.cn/Article/details/gtbvnklhfw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuetiantiany.cn/Article/details/gtbllzzodk.html

JS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gtjozgotpy.html

TS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gtodjabidy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.9152youxi.cn/Article/details/gtlsomlukx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.0kj1m.cn/Article/details/gtdhvggkpv.html

Ruby: threads.map(&:join)
来源：http://dali.havefunace.top/Article/details/gtpyggykil.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gogol.net.cn/Article/details/gtaubhxjnj.html

[O06] 使用进程池
来源：http://dali.xylfe.cn/Article/details/gtpcrtuppt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sweek.top/Article/details/gtmmgoialo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guannengcc.top/Article/details/gtohsjijsh.html

JS:   // child_process / cluster 模块
来源：http://dali.aibaodan.cn/Article/details/gtvbytshkf.html

TS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gtbxlnxehz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gzhubu.top/Article/details/gtekvxjxxu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.pycfn.com/Article/details/gthvlbsvrg.html

Ruby: // fork 块
来源：http://dali.9152youxi.cn/Article/details/gtntimbohk.html

C#:   Parallel.For
来源：http://dali.0kj1m.cn/Article/details/gtubibfaih.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtuftjydrs.html

P. 常用工具函数
来源：http://dali.sufxvd.cn/Article/details/gthpfaeokr.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtfnciiiqi.html

[P01] 生成 UUID
来源：http://dali.tianlin.xyz/Article/details/gtqfdxtppa.html

Py:   str(uuid.uuid4())
来源：http://dali.yvedp.cn/Article/details/gtyrseffvg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangshuangyany.cn/Article/details/gtswnbhtmu.html

JS:   crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvutepwta.html

TS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gtbfccowdz.html

Java: UUID.randomUUID().toString()
来源：http://dali.dianchejie.cn/Article/details/gtcuhooawb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj202588.top/Article/details/gthbpjprdh.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigfzy.top/Article/details/gtyxsmyieq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gzhubu.top/Article/details/gthohupaiz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.havefunace.top/Article/details/gtfznyhsyk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nwbrower.top/Article/details/gtsajnqhho.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258.top/Article/details/gtnpvxpibd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.havefunace.top/Article/details/gtcusrfwzr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tanke756.top/Article/details/gtxnwpepir.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtpyhfqmqh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daria6918.cn/Article/details/gtimscyujd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtzfbtwzlk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daxiang520.top/Article/details/gtyfhmlpnz.html

[P03] 生成短随机字符串
来源：http://dali.xylfe.cn/Article/details/gtdqmtubke.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gogol.net.cn/Article/details/gtrvcxllrm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hfpthk.cn/Article/details/gtynilngnu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yongpay.top/Article/details/gtffuraojk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtlylggcht.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cdnleiting.top/Article/details/gtxazyisoj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhiwuduotai.top/Article/details/gtmwtmzoml.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zdqjudy.top/Article/details/gtssggnvbn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhixingplan.top/Article/details/gtdxteykgz.html

[P04] 求长度
来源：http://dali.andypj.xyz/Article/details/gtciokbxlg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xinyue.icu/Article/details/gtymriiear.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtcffxhicd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnxiangtu.top/Article/details/gtaeifimth.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gotoacloud.top/Article/details/gturvompfi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.mhx1999.top/Article/details/gtnbicrcqd.html

Go:   len(arr);  len(m)
来源：http://dali.fengsongda.top/Article/details/gtggxoarsb.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gtiytiryfo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.0kj1m.cn/Article/details/gtidtkcznp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hammf.cn/Article/details/gtfbkikngq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.smart0.xyz/Article/details/gthttyhebw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.redwolf501.top/Article/details/gtztaxyviq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.smart0.xyz/Article/details/gtmtwxvaws.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.redwolf501.top/Article/details/gtjbzivyig.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.iojbl.cn/Article/details/gtlbwserri.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.bjfxy.top/Article/details/gtshhwlbno.html

Ruby: a == b
来源：http://dali.quarkkingdee.top/Article/details/gtpvlozkhx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sxryk.cn/Article/details/gtqkodnfnt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tianlin.xyz/Article/details/gtcvaovltp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.meibo888.top/Article/details/gtgqdhuxvf.html

PHP:  if (empty($x)) {}
来源：http://dali.nwbrower.top/Article/details/gtpgjbzwzd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgufenzy.top/Article/details/gtrjxonces.html

TS:   if (x == null) {}
来源：http://dali.meibo888.top/Article/details/gthyfftfdr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gtmkrqwjjt.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtifueudjh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gzhubu.top/Article/details/gtnavlfgsf.html

C#:   if (x is null) {}
来源：http://dali.jlsjyb.cn/Article/details/gtuebjcacn.html

[P07] 防抖与节流
来源：http://dali.tanke756.top/Article/details/gtjbqifirg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj20258888.top/Article/details/gtglrmhjmn.html

PHP:  // 手写时间戳比较
来源：http://dali.meibo888.top/Article/details/gtagqpqenm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gtxpqrtkxw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtkxjajglg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yonumen.top/Article/details/gtqxfocwbb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcoituuci.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ybcxt.top/Article/details/gtomexwgdv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.pycfn.com/Article/details/gtfsuvviwg.html

[P08] 处理浮点精度问题
来源：http://dali.tianlin.xyz/Article/details/gtwrkkmkxu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.quarkkingdee.top/Article/details/gtxvamrtfc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtumemwamo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daria6918.cn/Article/details/gtvalftyzy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtzysuzyvp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cqqwz.cn/Article/details/gtjrregbyd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ybcxt.top/Article/details/gtugbfxwro.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cucudq.cn/Article/details/gtjktreoad.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yuanzhike.top/Article/details/gtuahbrcze.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gttlaobexo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangtech.top/Article/details/gtyawavkzf.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtgyazkhdl.html

[Q01] 创建表
来源：http://dali.cashguo.top/Article/details/gtaiuiyjzb.html

CREATE TABLE users (
来源：http://dali.xinyue.icu/Article/details/gtqxabfbgo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ydzc1.top/Article/details/gtvmzbrevd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gtlhmqoavc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ehwqpu.com/Article/details/gtwlqqblwf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hongshengwenyu.top/Article/details/gtqipxjboq.html

);
来源：http://dali.cheryme.top/Article/details/gtrqseowfn.html

[Q02] 创建带外键的表
来源：http://dali.ivvv.top/Article/details/gthqefrehu.html

CREATE TABLE orders (
来源：http://dali.yuanzhike.top/Article/details/gtvmysmawl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tanke756.top/Article/details/gtwiiuxsyz.html

user_id INT NOT NULL,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxrfnhfu.html

amount DECIMAL(10, 2),
来源：http://dali.c1oappe.top/Article/details/gttihgavpz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hfpthk.cn/Article/details/gtnmkdnfmj.html

);
来源：http://dali.xylfe.cn/Article/details/gttmmmfqyk.html

[Q03] 增加列
来源：http://dali.ybcxt.top/Article/details/gtpcxchxju.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xylfe.cn/Article/details/gtcnqfiymq.html

[Q04] 修改列类型
来源：http://dali.hnqzz.top/Article/details/gtegnxexbv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvokognu.html

[Q05] 重命名列
来源：http://dali.sysykeji.top/Article/details/gtnhonhyjy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jqgfzy.top/Article/details/gtgyckjjrq.html

[Q06] 删除列
来源：http://dali.cucudq.cn/Article/details/gtbxphyrin.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hfpthk.cn/Article/details/gtsvaljlzw.html

[Q07] 删除表
来源：http://dali.kuanghao11.cn/Article/details/gthkqlzpkv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.havefunace.top/Article/details/gtevglizcw.html

[Q08] 创建普通索引
来源：http://dali.cucudq.cn/Article/details/gthafhvwnr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gttpoufnmn.html

[Q09] 创建唯一索引
来源：http://dali.meibo888.top/Article/details/gtzspyqnbt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gtvyabtzsx.html

[Q10] 插入单行
来源：http://dali.feifeiyinyue.top/Article/details/gtyjcqdwcg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtbgbqfvcx.html

[Q11] 一次插入多行
来源：http://dali.shuidangran.top/Article/details/gtuimhoxhn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sysykeji.top/Article/details/gtxmvpwfzs.html

[Q12] 插入后取自增 ID
来源：http://dali.ehwqpu.com/Article/details/gtklyynxad.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.meibo888.top/Article/details/gtwgtuapem.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258.top/Article/details/gtupcsnisx.html

[Q13] 忽略重复插入
来源：http://dali.snrcjt.cn/Article/details/gtypmwigkf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhixingplan.top/Article/details/gtpzdbxifz.html

[Q14] 存在则更新（upsert）
来源：http://dali.shuidangran.top/Article/details/gtkhyovmbx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aizwys.cn/Article/details/gtolvfbxfo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sufxvd.cn/Article/details/gtjgulnpvt.html

[Q15] 查询全部
来源：http://dali.ehwqpu.com/Article/details/gtzalbrgix.html

SELECT * FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtxzfulipn.html

[Q16] 查询指定列
来源：http://dali.nanxinkj.top/Article/details/gtcaplmgxw.html

SELECT id, name FROM users;
来源：http://dali.nwbrower.top/Article/details/gtmfzmkboq.html

[Q17] 条件查询
来源：http://dali.sweek.top/Article/details/gtgyoxxvfv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.316326.xyz/Article/details/gtshqlkgbn.html

[Q18] 模糊匹配
来源：http://dali.dashuyun.cn/Article/details/gtspagmzke.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xuanzx.com/Article/details/gteqbjzbme.html

[Q19] 范围查询
来源：http://dali.ppjwa.cn/Article/details/gtuowacwht.html


<!-- 参考信息 -->