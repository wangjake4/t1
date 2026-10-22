代发 wailian999

[M08] 获取系统与运行时信息
来源：http://dali.sufxvd.cn/Article/details/gtlnqxrqwj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangshuangyany.cn/Article/details/gtrnvrrqwr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yanxiufei.cn/Article/details/gtyzomgtfu.html

JS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gtstirwqhm.html

TS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gtdoxtgqkp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ehwqpu.com/Article/details/gtlnngygro.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.iojbl.cn/Article/details/gtkvfghmae.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.c1oappe.top/Article/details/gtmylbfedi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuetiantiany.cn/Article/details/gtiydwixme.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtipafrdhk.html

N. 数据结构与算法
来源：http://dali.hammf.cn/Article/details/gtiheqjded.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtdzvdxukh.html

[N01] 二分查找（有序数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolkodvpb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtzvmkvujl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtwfoxgtxx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtiiavgjoi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtslxpjdis.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtgpjhfjdg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtyuxdsltp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hammf.cn/Article/details/gtivwjuezq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gtbvuwdifs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jyoumei.cn/Article/details/gtbwqstsgx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gtapgvhxcr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtxdswtznt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gtdfoeusvv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gtdojoxjdq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yvedp.cn/Article/details/gtoivjpfba.html

Go:   slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtrkimwkur.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gtbxheyegw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daria6918.cn/Article/details/gtanbjqmij.html

[N03] 快速排序（分治示例）
来源：http://dali.zhoulong.xyz/Article/details/gtaynsndye.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.havefunace.top/Article/details/gtdvttyjgb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhixingplan.top/Article/details/gtrjibfbpb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gtaltzxulr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gtguhyfrkl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.haohaochexian.top/Article/details/gtliuccdei.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.pycfn.com/Article/details/gthqizyrsd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yonumen.top/Article/details/gtyqalrdlx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ybcxt.top/Article/details/gtrilatzbu.html

[N04] 斐波那契数列
来源：http://dali.jqgufenzy.top/Article/details/gttqehhaac.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gtjxsntqxw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.pycfn.com/Article/details/gtyfyfsgul.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtcpfcuebx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtwppqlbwh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenjidiqi.icu/Article/details/gtnrafjwte.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aizwys.cn/Article/details/gtsihmkmby.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tianlin.xyz/Article/details/gtzawcefiy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtjjbmabxx.html

[N05] 最大公约数
来源：http://dali.zhiwuduotai.top/Article/details/gtnkymrfqh.html

Py:   math.gcd(a, b)
来源：http://dali.ivvv.top/Article/details/gtzdgkvrsw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guannengcc.top/Article/details/gtcvarnxzw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtauvigewe.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.quarkkingdee.top/Article/details/gtqcjocbbt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigufen.top/Article/details/gtxhukocmc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhengqikj.top/Article/details/gtxutmmlup.html

Ruby: a.gcd(b)
来源：http://dali.pycfn.com/Article/details/gtkecyemvr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.haohaochexian.top/Article/details/gthlrfplxa.html

[N06] 判断回文字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpbooopj.html

Py:   s == s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gtvqocblch.html

PHP:  $s === strrev($s);
来源：http://dali.hammf.cn/Article/details/gtecijenal.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtyvqhdhjz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtziqjsixu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.c1oappe.top/Article/details/gtezrqcsek.html

Go:   // 双指针从两端比较
来源：http://dali.cdnleiting.top/Article/details/gtfsobvvsq.html

Ruby: s == s.reverse
来源：http://dali.sysykeji.top/Article/details/gterbittbg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gtimxupuqp.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgufenzy.top/Article/details/gtheexvohq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.svipenyu.cn/Article/details/gtvxotwxsj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfgojiyg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yanxiufei.cn/Article/details/gtfhfpcvwj.html

TS:   // 手写 Map<string, number>
来源：http://dali.yonumen.top/Article/details/gtvjhwtcim.html

Java: // 手写 HashMap
来源：http://dali.xinyue.icu/Article/details/gtjpzxynuu.html

Go:   // 手写 map[int]int
来源：http://dali.gzhubu.top/Article/details/gtgafibqqr.html

Ruby: // 手写 Hash
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizbtruvb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.wangshuangyany.cn/Article/details/gtrejyqxti.html

[N08] 生成全排列
来源：http://dali.jqgufenzy.top/Article/details/gtwgcqvffq.html

Py:   itertools.permutations(arr)
来源：http://dali.jyoumei.cn/Article/details/gtyztzlhkf.html

PHP:  // 手写递归交换
来源：http://dali.bjfxy.top/Article/details/gtbwjckffe.html

JS:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtrxdkyvsc.html

TS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtlifeiiwg.html

Java: // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtbuixfbtg.html

Go:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtfnurhkcz.html

Ruby: arr.permutation.to_a
来源：http://dali.zycfv.cn/Article/details/gtgspobdbs.html

C#:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtzsdzesjo.html

[N09] 栈与队列
来源：http://dali.mhx1999.top/Article/details/gtirxsephn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shzxlz.cn/Article/details/gtvdaxpuzg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtzghdlngc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtqmubutqf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigufen.top/Article/details/gtouhripye.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgfzy.top/Article/details/gtrefcexdt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhvssyxk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gtfefhhctv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sweek.top/Article/details/gtljzyzyrt.html

[N10] 链表节点定义
来源：http://dali.xinyue.icu/Article/details/gtoxdjekxx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sufxvd.cn/Article/details/gtljhuwhxt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.meibo888.top/Article/details/gtkmyeihll.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cqqwz.cn/Article/details/gtltwxlqwm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.316326.xyz/Article/details/gtvbovcsvb.html

Java: class Node { int v; Node next; }
来源：http://dali.bjfxy.top/Article/details/gtkkoigfdw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xinyue.icu/Article/details/gtujxebdsp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shuidangran.top/Article/details/gtmsayrsoc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fengsongda.top/Article/details/gtmahpcanj.html

[N11] 二叉树中序遍历
来源：http://dali.shuidangran.top/Article/details/gtwfarbedf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ppjwa.cn/Article/details/gteyvksatp.html

PHP:  // 手写递归函数
来源：http://dali.zhixingplan.top/Article/details/gtxaaqcawu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxuanxn.top/Article/details/gtgacrbqmp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dashuyun.cn/Article/details/gtizgsnofb.html

Java: // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtviizxhpm.html

Go:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gtkctllsbt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gtfahgmktn.html

C#:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtponlsjsv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gzhubu.top/Article/details/gtqlqzzjdg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.andypj.xyz/Article/details/gtxkscnrrs.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yuxming.cn/Article/details/gtzogzcead.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gtszgcmcak.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hysaishi.cn/Article/details/gtxblittgb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gtyirnccwp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gotoacloud.top/Article/details/gtebrapyen.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhengqikj.top/Article/details/gtybixwjiw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gtsakljhqq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtetackuox.html

O. 并发与异步
来源：http://dali.jinghuilouyu.cn/Article/details/gtroliqxxi.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtpaqnzlya.html

[O01] 启动一个线程
来源：http://dali.yuxming.cn/Article/details/gtbcaeevof.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.meibo888.top/Article/details/gtecuaupke.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.fengsongda.top/Article/details/gtvjylcrwd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgufenzy.top/Article/details/gtpfjwjjkm.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gtdczizrie.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnxiangtu.top/Article/details/gtdslsvvgt.html

Go:   go f()
来源：http://dali.zhiwuduotai.top/Article/details/gtzzeuzwah.html

Ruby: Thread.new { f }
来源：http://dali.zhiwuduotai.top/Article/details/gtysjrdawu.html

C#:   Task.Run(() => F());
来源：http://dali.ehwqpu.com/Article/details/gtaevjqgsf.html

[O02] 使用线程池
来源：http://dali.fzhhl.top/Article/details/gtjqadghuc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fzhhl.top/Article/details/gtvkyzakoc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.0kj1m.cn/Article/details/gthewgxicm.html

JS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtbwezpgvw.html

TS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gtrtkrlxbc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.quarkkingdee.top/Article/details/gtbbuoqjxv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nwbrower.top/Article/details/gtlvmndwgu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.svipenyu.cn/Article/details/gtgyfergow.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cashguo.top/Article/details/gtvtzijfvt.html

[O03] 加锁保护共享数据
来源：http://dali.xziqi.cn/Article/details/gtllrdpwjm.html

Py:   with lock: shared += 1
来源：http://dali.nwbrower.top/Article/details/gtivmjqwyl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gtpwhpfuyo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.c1oappe.top/Article/details/gtqpnszlcx.html

TS:   // 同 JS
来源：http://dali.meibo888.top/Article/details/gtxfhsarbp.html

Java: synchronized (this) { shared++; }
来源：http://dali.havefunace.top/Article/details/gtadxmzche.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hysaishi.cn/Article/details/gthqjakmed.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxuanxn.top/Article/details/gtktjcqxop.html

C#:   lock (gate) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqyqzkab.html

[O04] 定义异步函数并等待
来源：http://dali.sxryk.cn/Article/details/gtocvfmmgt.html

Py:   async def f():⏎    await g()
来源：http://dali.zdqjudy.top/Article/details/gttyukcvbo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhixingplan.top/Article/details/gtssynheog.html

JS:   async function f() { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbtcdenj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jlsjyb.cn/Article/details/gtcvzfkgpx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrtuttik.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.svipenyu.cn/Article/details/gtnrdqxemm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnqzz.top/Article/details/gtaulhgovj.html

C#:   async Task F() { await G(); }
来源：http://dali.jyoumei.cn/Article/details/gtohkaekgc.html

[O05] 并发执行并等待全部完成
来源：http://dali.sysykeji.top/Article/details/gtqmjazgji.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xylfe.cn/Article/details/gtagdjalgc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fzhhl.top/Article/details/gtmpeqqpvi.html

JS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gtsnrtybfp.html

TS:   await Promise.all(tasks)
来源：http://dali.havefunace.top/Article/details/gtmhscfjlo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jyoumei.cn/Article/details/gtzcytkndc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nwbrower.top/Article/details/gtlrraiaqz.html

Ruby: threads.map(&:join)
来源：http://dali.xylfe.cn/Article/details/gtseosmksu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzocifsl.html

[O06] 使用进程池
来源：http://dali.hfpthk.cn/Article/details/gtrfpijbeg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gaohongyu789.top/Article/details/gtifbnqbhz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtcafwlyun.html

JS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gthadtzocd.html

TS:   // child_process / cluster 模块
来源：http://dali.cheryme.top/Article/details/gtswpriafe.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzinrhfya.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhaomingkeji.xyz/Article/details/gtispwbrze.html

Ruby: // fork 块
来源：http://dali.feifeiyinyue.top/Article/details/gtdrvbwdgp.html

C#:   Parallel.For
来源：http://dali.gzhubu.top/Article/details/gtabimjwfn.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtlenwzyxc.html

P. 常用工具函数
来源：http://dali.jlsjyb.cn/Article/details/gtmwjgoqvr.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtnvieyynu.html

[P01] 生成 UUID
来源：http://dali.xuanzx.com/Article/details/gtgayuhvay.html

Py:   str(uuid.uuid4())
来源：http://dali.jinqigufen.top/Article/details/gtcuvkormp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.316326.xyz/Article/details/gttpizqrle.html

JS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gtgzipndqs.html

TS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtrficinwi.html

Java: UUID.randomUUID().toString()
来源：http://dali.gaohongyu789.top/Article/details/gtifkgfizr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shuidangran.top/Article/details/gtrkuvslzy.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxinkj.top/Article/details/gtckagttfl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jianghu66.top/Article/details/gtiqprynio.html

[P02] MD5 / SHA256 摘要
来源：http://dali.0kj1m.cn/Article/details/gttfiexqwz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.andypj.xyz/Article/details/gtqdjwlnbc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aibaodan.cn/Article/details/gtltnitwmq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258888.top/Article/details/gtdcrzmygq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yanxiufei.cn/Article/details/gtfngzpjih.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nwbrower.top/Article/details/gtubfoccos.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daxiang520.top/Article/details/gtgnhoimld.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tian-w.cn/Article/details/gtolvvjscs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sufxvd.cn/Article/details/gtawcomhii.html

[P03] 生成短随机字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtuheqsgpx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.snrcjt.cn/Article/details/gtyqwmlnto.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nanxuanxn.top/Article/details/gtnadiutbb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gthxqrqaze.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yueranfly.top/Article/details/gtrgkivwfw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnamvakux.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dianchejie.cn/Article/details/gtnkddudcm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cucudq.cn/Article/details/gtoufvnryu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nwbrower.top/Article/details/gtbydqwkvz.html

[P04] 求长度
来源：http://dali.jinqigfzy.top/Article/details/gtaigvtezh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daxiang520.top/Article/details/gtmgwcmiub.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gttzttjmbl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gtgqsvfqvq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gtpgxsptlc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zycfv.cn/Article/details/gtpwjcysul.html

Go:   len(arr);  len(m)
来源：http://dali.ivvv.top/Article/details/gtdmcpknlz.html

Ruby: x.length;  x.size
来源：http://dali.dianchejie.cn/Article/details/gtbddyzrrm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.dianchejie.cn/Article/details/gtbjvvccav.html

[P05] 判断两个对象内容是否相等
来源：http://dali.kuanghao11.cn/Article/details/gtmluwyzkw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daria6918.cn/Article/details/gtpkgvloae.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xinyue.icu/Article/details/gtwpymqfyu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizhgbdco.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.mhx1999.top/Article/details/gtcpwumgfq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dianchejie.cn/Article/details/gtmrurfhzw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.havefunace.top/Article/details/gtbsawfpvg.html

Ruby: a == b
来源：http://dali.jinghuilouyu.cn/Article/details/gtlikobyxs.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shanyushiyangtech.top/Article/details/gtqghappqc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fzhhl.top/Article/details/gthzykdnoq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.feifeiyinyue.top/Article/details/gtlgdvrtli.html

PHP:  if (empty($x)) {}
来源：http://dali.cqqwz.cn/Article/details/gttlkhgiwz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sweek.top/Article/details/gtglusgnoz.html

TS:   if (x == null) {}
来源：http://dali.yangfankeji.com/Article/details/gtiorwajpr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtarykmeft.html

Go:   if x == nil {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkjnrzkm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cucudq.cn/Article/details/gtlpmclptg.html

C#:   if (x is null) {}
来源：http://dali.ivvv.top/Article/details/gtuyfgnokv.html

[P07] 防抖与节流
来源：http://dali.hammf.cn/Article/details/gtbtgodrwd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.c1oappe.top/Article/details/gtzzbywssl.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gtytyjpyyd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gtuvmkbnzj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cdnleiting.top/Article/details/gtpqoihzrg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jianghu66.top/Article/details/gtmlsonmlo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gzhubu.top/Article/details/gttoacokkp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.iojbl.cn/Article/details/gtjrludjvl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cdnleiting.top/Article/details/gthijkylhz.html

[P08] 处理浮点精度问题
来源：http://dali.fengsongda.top/Article/details/gttdelqoxj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.smart0.xyz/Article/details/gtjfknlczp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hywenlv.cn/Article/details/gtinqigehh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cdnleiting.top/Article/details/gtfguznkvk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuanzhike.top/Article/details/gtbavsydgc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sufxvd.cn/Article/details/gtlgiqugmw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhoulong.xyz/Article/details/gtueyjubfq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dianchejie.cn/Article/details/gtajtopjuc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jianghu66.top/Article/details/gtkxvxhfxp.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gttkmbckfd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zycfv.cn/Article/details/gtfipmjqnf.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtrazkziiv.html

[Q01] 创建表
来源：http://dali.yueranfly.top/Article/details/gteazibhuv.html

CREATE TABLE users (
来源：http://dali.hnqzz.top/Article/details/gtygesisso.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gtgzeibvjz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgdynjli.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sysykeji.top/Article/details/gtachejgpa.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.smart0.xyz/Article/details/gtrqazqash.html

);
来源：http://dali.yuanzhike.top/Article/details/gtrueefujy.html

[Q02] 创建带外键的表
来源：http://dali.hnxiangtu.top/Article/details/gtnoiutmye.html

CREATE TABLE orders (
来源：http://dali.daria6918.cn/Article/details/gtscyjphee.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ehwqpu.com/Article/details/gtwnzxfvhf.html

user_id INT NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gtwawkkyzp.html

amount DECIMAL(10, 2),
来源：http://dali.jianghu66.top/Article/details/gtybhlqwez.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.redwolf501.top/Article/details/gtxhwstlkr.html

);
来源：http://dali.yuanzhike.top/Article/details/gtjvxdnrax.html

[Q03] 增加列
来源：http://dali.xinyue.icu/Article/details/gtgwnzdngz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cheryme.top/Article/details/gtoauuylsl.html

[Q04] 修改列类型
来源：http://dali.redwolf501.top/Article/details/gtwtazhnxj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.andypj.xyz/Article/details/gtskydnewl.html

[Q05] 重命名列
来源：http://dali.daria6918.cn/Article/details/gtdzxkainm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hfpthk.cn/Article/details/gtyafljojt.html

[Q06] 删除列
来源：http://dali.gogol.net.cn/Article/details/gthiqcodps.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yvedp.cn/Article/details/gtjkxewgpo.html

[Q07] 删除表
来源：http://dali.zhoulong.xyz/Article/details/gtipbeculk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.bjfxy.top/Article/details/gtknwgkpax.html

[Q08] 创建普通索引
来源：http://dali.cashguo.top/Article/details/gtahzlmobh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gthmrxkcvv.html

[Q09] 创建唯一索引
来源：http://dali.c1oappe.top/Article/details/gtkmlqfalw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gtcevuyfxj.html

[Q10] 插入单行
来源：http://dali.meibo888.top/Article/details/gtgydmdytb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ydzc1.top/Article/details/gtwbfgyilv.html

[Q11] 一次插入多行
来源：http://dali.meibo888.top/Article/details/gtvhhytlid.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtjtpnzctc.html

[Q12] 插入后取自增 ID
来源：http://dali.smart0.xyz/Article/details/gtmvgmprtd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.fengsongda.top/Article/details/gtbeimxnhe.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hongshengwenyu.top/Article/details/gtiadjhwpy.html

[Q13] 忽略重复插入
来源：http://dali.yangfankeji.com/Article/details/gtkkzdvsyp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzczhwdxh.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhixingplan.top/Article/details/gtpknjirof.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.vqdsnc.cn/Article/details/gtzovcxuzj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guannengcc.top/Article/details/gtbgkfaqit.html

[Q15] 查询全部
来源：http://dali.zhoulong.xyz/Article/details/gtzpeelxrz.html

SELECT * FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtbkggaxbj.html

[Q16] 查询指定列
来源：http://dali.zdqjudy.top/Article/details/gtzvywrkzj.html

SELECT id, name FROM users;
来源：http://dali.shuidangran.top/Article/details/gtcekyjyrg.html

[Q17] 条件查询
来源：http://dali.jinqigfzy.top/Article/details/gtsaeqbtnc.html


<!-- 参考信息 -->