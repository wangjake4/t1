代发 wailian999

[M08] 获取系统与运行时信息
来源：http://dali.cdnleiting.top/Article/details/gtxdynphfl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhixingplan.top/Article/details/gthbtqemcd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hnqzz.top/Article/details/gtipqfozdg.html

JS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gtxjvaqpmt.html

TS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gtgfaeqjbg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aizwys.cn/Article/details/gtxunrbzyh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigufen.top/Article/details/gtbjhyiexr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnqzz.top/Article/details/gtcjdtxwmo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ppjwa.cn/Article/details/gtdfvppuuo.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtkeuznrwk.html

N. 数据结构与算法
来源：http://dali.mhx1999.top/Article/details/gtelyrbotg.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtaolbiqnf.html

[N01] 二分查找（有序数组）
来源：http://dali.kuanghao11.cn/Article/details/gtdmudueyl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtyejcadtm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtfpdfngze.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gtybqlwinr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gtrgaipemb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gteoqujtya.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtabjjvftb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xinyue.icu/Article/details/gtmtoperwn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yueranfly.top/Article/details/gthcfhociq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.mhx1999.top/Article/details/gtyewzxlky.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.9152youxi.cn/Article/details/gtjelijofm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cheryme.top/Article/details/gteolrlxzp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtxyzhfzqz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gtubkguyum.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.vqdsnc.cn/Article/details/gtasoohopk.html

Go:   slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtcpywgxzl.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gtnmocbpbi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.feifeiyinyue.top/Article/details/gterrllprs.html

[N03] 快速排序（分治示例）
来源：http://dali.fengsongda.top/Article/details/gtumvkgfoc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.meibo888.top/Article/details/gtysbwaddq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ppjwa.cn/Article/details/gtcpnryius.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gtlfedvyzu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbhtuipe.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.svipenyu.cn/Article/details/gtwqtboiew.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hammf.cn/Article/details/gtgesemcbr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.9152youxi.cn/Article/details/gtwxrhvdle.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhoulong.xyz/Article/details/gtdfkmwkhx.html

[N04] 斐波那契数列
来源：http://dali.smart0.xyz/Article/details/gthhnwasao.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gtwnhxgbsq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gtikqkbmch.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwzwclau.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajshzsxn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuogkbdyw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shangyingyoupin.top/Article/details/gttmjdusfp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtlgcisyjk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtqzajmlis.html

[N05] 最大公约数
来源：http://dali.yueranfly.top/Article/details/gtizlwqekc.html

Py:   math.gcd(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtmplnxtjl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aibaodan.cn/Article/details/gtkeolpugm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gtfbaphdun.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtbvutnpfg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tanke756.top/Article/details/gtasaksogy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgdixhde.html

Ruby: a.gcd(b)
来源：http://dali.zhoulong.xyz/Article/details/gtyzymeboe.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigfzy.top/Article/details/gthzwdbevr.html

[N06] 判断回文字符串
来源：http://dali.snrcjt.cn/Article/details/gturvjpzqp.html

Py:   s == s[::-1]
来源：http://dali.xylfe.cn/Article/details/gtfaqcdpks.html

PHP:  $s === strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gtmnisqffc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtjqyyioby.html

TS:   s === [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtyndarkco.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nwbrower.top/Article/details/gtpklrqvxn.html

Go:   // 双指针从两端比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafmfukyp.html

Ruby: s == s.reverse
来源：http://dali.ivvv.top/Article/details/gtawekkfpt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gtlvsgyuhr.html

[N07] 两数之和（返回下标）
来源：http://dali.fzhhl.top/Article/details/gttfuhncyp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nwbrower.top/Article/details/gtphzoykzk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhongyouzk.top/Article/details/gthshvdaqb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jiagoushi.top/Article/details/gtyamuthdd.html

TS:   // 手写 Map<string, number>
来源：http://dali.jlsjyb.cn/Article/details/gtbxwcihhp.html

Java: // 手写 HashMap
来源：http://dali.smart0.xyz/Article/details/gtxkijioxb.html

Go:   // 手写 map[int]int
来源：http://dali.jyoumei.cn/Article/details/gtpdenrnbj.html

Ruby: // 手写 Hash
来源：http://dali.mhx1999.top/Article/details/gtqxszhwbc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yuxming.cn/Article/details/gtvilnfgeh.html

[N08] 生成全排列
来源：http://dali.hammf.cn/Article/details/gttdudlikh.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtsguzkkjq.html

PHP:  // 手写递归交换
来源：http://dali.bjfxy.top/Article/details/gtxremnbhx.html

JS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtcwugbnsx.html

TS:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtrrvenxzl.html

Java: // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtztdxooet.html

Go:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtsvmpbagv.html

Ruby: arr.permutation.to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gthgrnkhtm.html

C#:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgfznchw.html

[N09] 栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gtbmfxddxn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jiagoushi.top/Article/details/gtpjlvkmrc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtsczzxemv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gtziaciwhd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ppjwa.cn/Article/details/gtrddpzjhm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.kuanghao11.cn/Article/details/gtlqmtllwo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigfzy.top/Article/details/gtdjkiahpj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtdvsaezbi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daxiang520.top/Article/details/gtdwnlqrpr.html

[N10] 链表节点定义
来源：http://dali.cashguo.top/Article/details/gtbxbjbbuq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tianlin.xyz/Article/details/gtfllhnhmy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.guowangkeji.top/Article/details/gtnwnuhsrb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenlongwang.top/Article/details/gtcqcxdleq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.haohaochexian.top/Article/details/gtzltqwwjg.html

Java: class Node { int v; Node next; }
来源：http://dali.yuanzhike.top/Article/details/gtxnquxijn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangshuangyany.cn/Article/details/gtmjcejluo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuanzhike.top/Article/details/gtegfiminl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtgauqhj.html

[N11] 二叉树中序遍历
来源：http://dali.daria6918.cn/Article/details/gtqlazczrp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiipgprpr.html

PHP:  // 手写递归函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrioivcp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gtwbxrppci.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gtmdbmebbx.html

Java: // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtlnhqkasc.html

Go:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gtbiqwpklg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sweek.top/Article/details/gtfydqgxbt.html

C#:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gtmwfseknh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ybcxt.top/Article/details/gtzwhskrtd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cheryme.top/Article/details/gtrqujnlrj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shangyingyoupin.top/Article/details/gtgcjmonnj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgfzy.top/Article/details/gthfadnuvo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gtaqziayqf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gtybjdragt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ivvv.top/Article/details/gtjpphsncz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.haohaochexian.top/Article/details/gtynhospud.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yongpay.top/Article/details/gtcipbfaxo.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gteyznjfip.html

O. 并发与异步
来源：http://dali.xziqi.cn/Article/details/gtifhwxlff.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtumfneetx.html

[O01] 启动一个线程
来源：http://dali.yj202588.top/Article/details/gtbzxtcthz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhixingplan.top/Article/details/gtoywlpilb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhongyouzk.top/Article/details/gtfieeygve.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yonumen.top/Article/details/gtzmxmirxu.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gtiwfynpjg.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthoasidmu.html

Go:   go f()
来源：http://dali.cheryme.top/Article/details/gtbabsafgv.html

Ruby: Thread.new { f }
来源：http://dali.xziqi.cn/Article/details/gtfltvpbww.html

C#:   Task.Run(() => F());
来源：http://dali.kuanghao11.cn/Article/details/gthnyxxuof.html

[O02] 使用线程池
来源：http://dali.zhoulong.xyz/Article/details/gtjmeekwkv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhixingplan.top/Article/details/gtzhawzjsz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ehwqpu.com/Article/details/gtdqkbrvga.html

JS:   // worker_threads 线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzijeqvi.html

TS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gtulsimpvt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yuxming.cn/Article/details/gttzvqkznz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shangyingyoupin.top/Article/details/gtmuhjaoio.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.mhx1999.top/Article/details/gtzkxxyvgo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhoulong.xyz/Article/details/gtozlhenfm.html

[O03] 加锁保护共享数据
来源：http://dali.shanyushiyangtech.top/Article/details/gtxeksfeja.html

Py:   with lock: shared += 1
来源：http://dali.sufxvd.cn/Article/details/gtkhxgfqmt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shzxlz.cn/Article/details/gtojwsnmqb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.smart0.xyz/Article/details/gtifglsplx.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gtcdupcevd.html

Java: synchronized (this) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gtjpednkqa.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.andypj.xyz/Article/details/gtcacqtave.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinqigfzy.top/Article/details/gtzhqsgwcs.html

C#:   lock (gate) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljdwrflp.html

[O04] 定义异步函数并等待
来源：http://dali.gzhubu.top/Article/details/gtksbbhhpy.html

Py:   async def f():⏎    await g()
来源：http://dali.ydzc1.top/Article/details/gtwtqnzgeg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258.top/Article/details/gtkxpgwycn.html

JS:   async function f() { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gtjqftqrud.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gtowhezqil.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hfpthk.cn/Article/details/gtoeqciywu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tianlin.xyz/Article/details/gtsobfdspj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.kuanghao11.cn/Article/details/gtfaorbgcs.html

C#:   async Task F() { await G(); }
来源：http://dali.jyoumei.cn/Article/details/gtkeduycth.html

[O05] 并发执行并等待全部完成
来源：http://dali.ppjwa.cn/Article/details/gtvnbjipqr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xinyue.icu/Article/details/gtesptlxij.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jlsjyb.cn/Article/details/gtuoopktov.html

JS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtjikwbabw.html

TS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gtkkesquvb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hysaishi.cn/Article/details/gtdvshhspu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnqzz.top/Article/details/gthkwrsmfg.html

Ruby: threads.map(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gtnubbuorz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.mhx1999.top/Article/details/gtzjtmntvn.html

[O06] 使用进程池
来源：http://dali.feifeiyinyue.top/Article/details/gtlmrbftul.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zycfv.cn/Article/details/gteqqakrgq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtaikxhhep.html

JS:   // child_process / cluster 模块
来源：http://dali.zhoulong.xyz/Article/details/gtzlpeqadv.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258888.top/Article/details/gtcenfkica.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.redwolf501.top/Article/details/gtuyhemyty.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.bjfxy.top/Article/details/gtxbcesylx.html

Ruby: // fork 块
来源：http://dali.sysykeji.top/Article/details/gttsuadmvb.html

C#:   Parallel.For
来源：http://dali.xuanzx.com/Article/details/gtnyhejnoa.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtxwkgxtbo.html

P. 常用工具函数
来源：http://dali.bjfxy.top/Article/details/gtoczbrfku.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtpntoswbl.html

[P01] 生成 UUID
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiikwfgaw.html

Py:   str(uuid.uuid4())
来源：http://dali.zycfv.cn/Article/details/gttihkzwrl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.iojbl.cn/Article/details/gtvqddxtye.html

JS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtbonigriv.html

TS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gthfdpldro.html

Java: UUID.randomUUID().toString()
来源：http://dali.chenzaomai.com/Article/details/gttlrmqeny.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tanke756.top/Article/details/gtlunfejgy.html

Ruby: SecureRandom.uuid
来源：http://dali.gogol.net.cn/Article/details/gtaefksxmx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jqgfzy.top/Article/details/gtvuifogsk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jiagoushi.top/Article/details/gtrbmqoppi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.andypj.xyz/Article/details/gtqiisjomx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhengqikj.top/Article/details/gttejympjk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hysaishi.cn/Article/details/gtfcrzlhjj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cqqwz.cn/Article/details/gtqqwvzylq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yonumen.top/Article/details/gtacnhgkzk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ybcxt.top/Article/details/gtcarjhwon.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhixingplan.top/Article/details/gtiwtsyjyi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuanzhike.top/Article/details/gtvrxbvcva.html

[P03] 生成短随机字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtznkusxcg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.quarkkingdee.top/Article/details/gtrvnqgohg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.quarkkingdee.top/Article/details/gtotlpjjyf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xziqi.cn/Article/details/gtohzhpuxc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gtkqhlqhzd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aizwys.cn/Article/details/gtutdgszey.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.snrcjt.cn/Article/details/gtsopvyaur.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shuidangran.top/Article/details/gtormdmsek.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cashguo.top/Article/details/gthxgqjvbn.html

[P04] 求长度
来源：http://dali.yueranfly.top/Article/details/gtqoagbplr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangshuangyany.cn/Article/details/gtaviesrmr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtfhmelbgg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtmyhdxzdm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.316326.xyz/Article/details/gtgweyukji.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuanzx.com/Article/details/gtynsgtqnt.html

Go:   len(arr);  len(m)
来源：http://dali.jlsjyb.cn/Article/details/gtwdsloqwl.html

Ruby: x.length;  x.size
来源：http://dali.feifeiyinyue.top/Article/details/gtdbddvpbj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.iojbl.cn/Article/details/gthfhfhdoi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjaigglpx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daxiang520.top/Article/details/gtgxxqvoui.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenjidiqi.icu/Article/details/gtemjkmxdj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yvedp.cn/Article/details/gtaysbwjoq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gtvpovjygu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shanyushiyangtech.top/Article/details/gtbfbasgsz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jqgfzy.top/Article/details/gtzqbwhhof.html

Ruby: a == b
来源：http://dali.shzxlz.cn/Article/details/gtkpwqscwa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ydzc1.top/Article/details/gtrpbtlomm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sufxvd.cn/Article/details/gtdddyftnl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tianlin.xyz/Article/details/gtkbgvygtn.html

PHP:  if (empty($x)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtqsarerin.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzhacvuq.html

TS:   if (x == null) {}
来源：http://dali.haohaochexian.top/Article/details/gtoodguuvf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gtyebbihqe.html

Go:   if x == nil {}
来源：http://dali.zhixingplan.top/Article/details/gtffafronh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nwbrower.top/Article/details/gtsvxqigow.html

C#:   if (x is null) {}
来源：http://dali.meibo888.top/Article/details/gtrqxkcjci.html

[P07] 防抖与节流
来源：http://dali.jianghu66.top/Article/details/gtnhiiwgdr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhoulong.xyz/Article/details/gtmmqmfkcj.html

PHP:  // 手写时间戳比较
来源：http://dali.guannengcc.top/Article/details/gtcfgqwuta.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gtkzzgdozp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtcnnsvahu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yueranfly.top/Article/details/gtcdjwcdjg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.0kj1m.cn/Article/details/gtgqkelqnd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cashguo.top/Article/details/gtaalhsypv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj20258.top/Article/details/gtncevrmyg.html

[P08] 处理浮点精度问题
来源：http://dali.yueranfly.top/Article/details/gtqulrvopu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sxryk.cn/Article/details/gtfixxknxv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xinyue.icu/Article/details/gtuhkrdrcz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.birdmap.top/Article/details/gtoijxqmre.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tanke756.top/Article/details/gtmjoolfgh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cashguo.top/Article/details/gtydkqjctk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gzhubu.top/Article/details/gtbakojtgh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.bjfxy.top/Article/details/gtgcrtodtp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tanke756.top/Article/details/gtwqbiurpb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtyryvbodb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nwbrower.top/Article/details/gtbmguksbt.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtzlzpaxbr.html

[Q01] 创建表
来源：http://dali.guannengcc.top/Article/details/gtispzxjof.html

CREATE TABLE users (
来源：http://dali.cashguo.top/Article/details/gtcnuovtvu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gtaabpjrdx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gtbmjxvgen.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuanzhike.top/Article/details/gttxrsohup.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jiagoushi.top/Article/details/gtmihdomkf.html

);
来源：http://dali.cucudq.cn/Article/details/gtmmvbxaog.html

[Q02] 创建带外键的表
来源：http://dali.tian-w.cn/Article/details/gtwyouajgl.html

CREATE TABLE orders (
来源：http://dali.bjfxy.top/Article/details/gttsxrkxei.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhongyouzk.top/Article/details/gtohfdffon.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gtoisclijk.html

amount DECIMAL(10, 2),
来源：http://dali.jlsjyb.cn/Article/details/gthjkzqsiq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yvedp.cn/Article/details/gtmqvhaprr.html

);
来源：http://dali.hnxiangtu.top/Article/details/gtcdkysqkj.html

[Q03] 增加列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqiwzsnmp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcnnshao.html

[Q04] 修改列类型
来源：http://dali.shzxlz.cn/Article/details/gtwvwjcqrh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hywenlv.cn/Article/details/gtmcwdwcib.html

[Q05] 重命名列
来源：http://dali.0kj1m.cn/Article/details/gtqtriuuat.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.redwolf501.top/Article/details/gtvueeypop.html

[Q06] 删除列
来源：http://dali.9152youxi.cn/Article/details/gtchhtuodb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yangfankeji.com/Article/details/gtycfywnzh.html

[Q07] 删除表
来源：http://dali.yonumen.top/Article/details/gtqlmwqibk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jqgfzy.top/Article/details/gthwbnjsgm.html

[Q08] 创建普通索引
来源：http://dali.dashuyun.cn/Article/details/gtezqbjrnr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gthsujfyfo.html

[Q09] 创建唯一索引
来源：http://dali.cheryme.top/Article/details/gtmvxdfslg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sysykeji.top/Article/details/gtzpyslgms.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gtchqmajli.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guannengcc.top/Article/details/gttpzkkrti.html

[Q11] 一次插入多行
来源：http://dali.snrcjt.cn/Article/details/gtdvmzhcfi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xuanzx.com/Article/details/gtpuwuracn.html

[Q12] 插入后取自增 ID
来源：http://dali.yonumen.top/Article/details/gtaxhvdozf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yuxming.cn/Article/details/gtmqqtacso.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shangyingyoupin.top/Article/details/gteuhkywni.html

[Q13] 忽略重复插入
来源：http://dali.xinyue.icu/Article/details/gtwtvrwael.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gtpzyfxjks.html

[Q14] 存在则更新（upsert）
来源：http://dali.andypj.xyz/Article/details/gtrnxfhbsi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.dashuyun.cn/Article/details/gtpvfveizc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hnqzz.top/Article/details/gteukcroyj.html

[Q15] 查询全部
来源：http://dali.hammf.cn/Article/details/gtisclykfy.html

SELECT * FROM users;
来源：http://dali.gogol.net.cn/Article/details/gthtmshrdk.html

[Q16] 查询指定列
来源：http://dali.c1oappe.top/Article/details/gtykkmajyf.html

SELECT id, name FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtfetqlkzb.html

[Q17] 条件查询
来源：http://dali.tanke756.top/Article/details/gtrudgdjna.html


<!-- 参考信息 -->