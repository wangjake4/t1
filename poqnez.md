代发 wailian999

TS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gt2evbvmeaf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ybcxt.top/Article/details/gt2ocrrgmza.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.0kj1m.cn/Article/details/gt2gdvphsau.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fengsongda.top/Article/details/gt2jtlhylaf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hysaishi.cn/Article/details/gt2dgtmyndx.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2vajehixt.html

N. 数据结构与算法
来源：http://dali.ivvv.top/Article/details/gt2lascelbb.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2qanxhwqm.html

[N01] 二分查找（有序数组）
来源：http://dali.zhengqikj.top/Article/details/gt2frqcsorr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2zkrtvkyi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.iojbl.cn/Article/details/gt2mbojcyvt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gt2olwqcpdv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gt2qpsjswwb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2jpuzflmb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2wweyczjy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jykcfwqv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gt2mxvmkdvl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigfzy.top/Article/details/gt2crnejxji.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gt2ubrbosnr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gt2oabyvbhw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gt2jmxyqmic.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gt2jgzocaza.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenlongwang.top/Article/details/gt2gzrzehnc.html

Go:   slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gt2xfzddhrc.html

Ruby: arr.sort
来源：http://dali.jqgfzy.top/Article/details/gt2tuxpwfjb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jlsjyb.cn/Article/details/gt2aveueang.html

[N03] 快速排序（分治示例）
来源：http://dali.c1oappe.top/Article/details/gt2ozztwafj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zzkradge.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pengpengdd.cyou/Article/details/gt2uazzgeuv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gt2yoegjrxi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gt2avfvtvai.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aizwys.cn/Article/details/gt2rlrfziah.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sxryk.cn/Article/details/gt2mjgabnul.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guowangkeji.top/Article/details/gt2wexcrlna.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.snrcjt.cn/Article/details/gt2gjhfqizy.html

[N04] 斐波那契数列
来源：http://dali.andypj.xyz/Article/details/gt2mrwqzyto.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gzjasiry.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.guowangkeji.top/Article/details/gt2xjoowtgq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gt2ttlgxrtx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gt2weibvimm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gt2dhiirhgv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.haohaochexian.top/Article/details/gt2anszazum.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpgsgnh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gt2cusjkscp.html

[N05] 最大公约数
来源：http://dali.gzhubu.top/Article/details/gt2jubjhgho.html

Py:   math.gcd(a, b)
来源：http://dali.sufxvd.cn/Article/details/gt2kfdscmle.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.haohaochexian.top/Article/details/gt2ipeqcamb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gt2qqnlnqxu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gt2oeetkwce.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhoulong.xyz/Article/details/gt2qpromevd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.wangdashe.top/Article/details/gt2aegjpdse.html

Ruby: a.gcd(b)
来源：http://dali.shzxlz.cn/Article/details/gt2rabtuvya.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sysykeji.top/Article/details/gt2braskbog.html

[N06] 判断回文字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uleufeqj.html

Py:   s == s[::-1]
来源：http://dali.pycfn.com/Article/details/gt2aafkuzqw.html

PHP:  $s === strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gt2dixfljqh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fvqavlqd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gt2hewfmcxp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ivvv.top/Article/details/gt2fvajdhol.html

Go:   // 双指针从两端比较
来源：http://dali.ybcxt.top/Article/details/gt2kctvyxjy.html

Ruby: s == s.reverse
来源：http://dali.jqgfzy.top/Article/details/gt2fjmhnspx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gt2srsdrwoj.html

[N07] 两数之和（返回下标）
来源：http://dali.kuanghao11.cn/Article/details/gt2tnnkzydg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangshuangyany.cn/Article/details/gt2zabsceel.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tian-w.cn/Article/details/gt2xkyacuud.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.svipenyu.cn/Article/details/gt2petnvgho.html

TS:   // 手写 Map<string, number>
来源：http://dali.jiagoushi.top/Article/details/gt2vdqidxrw.html

Java: // 手写 HashMap
来源：http://dali.hywenlv.cn/Article/details/gt2wrbooymt.html

Go:   // 手写 map[int]int
来源：http://dali.yj202588.top/Article/details/gt2xugtlojo.html

Ruby: // 手写 Hash
来源：http://dali.feifeiyinyue.top/Article/details/gt2ozijxmwj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cqqwz.cn/Article/details/gt2fwlvlcqy.html

[N08] 生成全排列
来源：http://dali.sweek.top/Article/details/gt2ozjossmh.html

Py:   itertools.permutations(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rbvfmblc.html

PHP:  // 手写递归交换
来源：http://dali.hysaishi.cn/Article/details/gt2mauupnse.html

JS:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gt2fevpxfmr.html

TS:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gt2fgcimgmq.html

Java: // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gt2kyhusqxx.html

Go:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2wcjtjqed.html

Ruby: arr.permutation.to_a
来源：http://dali.yongpay.top/Article/details/gt2eoavjrce.html

C#:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gt2ztokkmnq.html

[N09] 栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gt2aysgbcjp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cheryme.top/Article/details/gt2shqvgubt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gt2nehwvofh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gt2vitdcbnx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yanxiufei.cn/Article/details/gt2urdsxdgg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.snrcjt.cn/Article/details/gt2iegurzjn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.havefunace.top/Article/details/gt2chmaylwl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gt2agkvcglo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhixingplan.top/Article/details/gt2tftyhqbi.html

[N10] 链表节点定义
来源：http://dali.kuanghao11.cn/Article/details/gt2eqzylugt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cashguo.top/Article/details/gt2ipyadibt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.iojbl.cn/Article/details/gt2dmqmjwib.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xziqi.cn/Article/details/gt2johuuhaz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.havefunace.top/Article/details/gt2cjyaawfz.html

Java: class Node { int v; Node next; }
来源：http://dali.cqqwz.cn/Article/details/gt2wbqklnnb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenzaomai.com/Article/details/gt2mjpksowl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.9152youxi.cn/Article/details/gt2jazmpdom.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daria6918.cn/Article/details/gt2bdtwzeti.html

[N11] 二叉树中序遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2apozffmv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nanxinkj.top/Article/details/gt2ngyonzaf.html

PHP:  // 手写递归函数
来源：http://dali.daxiang520.top/Article/details/gt2emhdnlyh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sufxvd.cn/Article/details/gt2wtjbapgg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gt2twmtcpxb.html

Java: // 手写递归
来源：http://dali.fengsongda.top/Article/details/gt2wnacuhfj.html

Go:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gt2knbhzlqu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhixingplan.top/Article/details/gt2zskitiet.html

C#:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gt2yzpwxptf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hammf.cn/Article/details/gt2xdrbsfvl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hfpthk.cn/Article/details/gt2obngtnxv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aizwys.cn/Article/details/gt2pgowqylf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gt2mwoexyvo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenjidiqi.icu/Article/details/gt2vdawwuds.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gt2hitqysvj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jyoumei.cn/Article/details/gt2rvmlobnh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shzxlz.cn/Article/details/gt2zjlszjdq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gt2qozyeagd.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ybuhionh.html

O. 并发与异步
来源：http://dali.yangfankeji.com/Article/details/gt2twcmmnjt.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2ayimfdiy.html

[O01] 启动一个线程
来源：http://dali.shangyingyoupin.top/Article/details/gt2vwsckkro.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fengsongda.top/Article/details/gt2rrnbzlqe.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2devnkxiv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.meibo888.top/Article/details/gt2zmzfypna.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gt2adatfneb.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhongyouzk.top/Article/details/gt2iyonpkhd.html

Go:   go f()
来源：http://dali.jinqigfzy.top/Article/details/gt2agbtpjvw.html

Ruby: Thread.new { f }
来源：http://dali.mhx1999.top/Article/details/gt2tbqdrpqp.html

C#:   Task.Run(() => F());
来源：http://dali.fzhhl.top/Article/details/gt2askexrgc.html

[O02] 使用线程池
来源：http://dali.316326.xyz/Article/details/gt2glheeynp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cdgxvapt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ehwqpu.com/Article/details/gt2lqtqmonc.html

JS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gt2whlbyjcv.html

TS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gt2zzmyxvca.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gogol.net.cn/Article/details/gt2ftlktsjg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xinyue.icu/Article/details/gt2emvvphgu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgufenzy.top/Article/details/gt2jfsrdbmk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yangfankeji.com/Article/details/gt2bkekhchy.html

[O03] 加锁保护共享数据
来源：http://dali.nwbrower.top/Article/details/gt2lgblxlhv.html

Py:   with lock: shared += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hurmwlyj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenjidiqi.icu/Article/details/gt2puwdozzo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yuxming.cn/Article/details/gt2lfmdtcdm.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gt2ridwhlmo.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vvwcxcdu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nanxinkj.top/Article/details/gt2mdgohsmy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cucudq.cn/Article/details/gt2lexbzovm.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258888.top/Article/details/gt2kwwyufas.html

[O04] 定义异步函数并等待
来源：http://dali.chenlongwang.top/Article/details/gt2jygvcqmd.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wdbvzcnv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daria6918.cn/Article/details/gt2msosbosz.html

JS:   async function f() { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gt2otnetqsj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gogol.net.cn/Article/details/gt2fyewgfis.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.quarkkingdee.top/Article/details/gt2fufgsdof.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cheryme.top/Article/details/gt2hdxzczve.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenzaomai.com/Article/details/gt2ukzexqjg.html

C#:   async Task F() { await G(); }
来源：http://dali.hfpthk.cn/Article/details/gt2ifesgwdz.html

[O05] 并发执行并等待全部完成
来源：http://dali.gzhubu.top/Article/details/gt2vryywhgt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ckelnhoi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhengqikj.top/Article/details/gt2ztrojevv.html

JS:   await Promise.all(tasks)
来源：http://dali.yongpay.top/Article/details/gt2gnoonzrw.html

TS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gt2fkkiysnr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.birdmap.top/Article/details/gt2totjvmrg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenzaomai.com/Article/details/gt2orkcaugq.html

Ruby: threads.map(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gt2mwuhqfxz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.daria6918.cn/Article/details/gt2jrmnezzv.html

[O06] 使用进程池
来源：http://dali.cqqwz.cn/Article/details/gt2xwkjmabi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.9152youxi.cn/Article/details/gt2xarpayrx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhoulong.xyz/Article/details/gt2poyvkewl.html

JS:   // child_process / cluster 模块
来源：http://dali.redwolf501.top/Article/details/gt2abksjvik.html

TS:   // child_process / cluster 模块
来源：http://dali.xziqi.cn/Article/details/gt2bdctbkvd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.svipenyu.cn/Article/details/gt2nginflhb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zycfv.cn/Article/details/gt2lwxgzojp.html

Ruby: // fork 块
来源：http://dali.jlsjyb.cn/Article/details/gt2dwbexlpg.html

C#:   Parallel.For
来源：http://dali.dianchejie.cn/Article/details/gt2xatefzkd.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2kdnvwmpu.html

P. 常用工具函数
来源：http://dali.hysaishi.cn/Article/details/gt2nyabkzmi.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2thfokwqg.html

[P01] 生成 UUID
来源：http://dali.fengsongda.top/Article/details/gt2kuvuykfn.html

Py:   str(uuid.uuid4())
来源：http://dali.0kj1m.cn/Article/details/gt2zgrvyboj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ybcxt.top/Article/details/gt2yofwvyct.html

JS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gt2ktlyhiny.html

TS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gt2emhondfr.html

Java: UUID.randomUUID().toString()
来源：http://dali.jianghu66.top/Article/details/gt2ijgifwhy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.havefunace.top/Article/details/gt2ilrrvzhz.html

Ruby: SecureRandom.uuid
来源：http://dali.hywenlv.cn/Article/details/gt2xmnmuebw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxinkj.top/Article/details/gt2cbmekagl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yongpay.top/Article/details/gt2hxgmzkxu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tanke756.top/Article/details/gt2gldwwtwc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.wangdashe.top/Article/details/gt2yrzdbwbt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shzxlz.cn/Article/details/gt2hsmlyeib.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jyoumei.cn/Article/details/gt2rmhdpurp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yuxming.cn/Article/details/gt2kqwbhgfa.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xylfe.cn/Article/details/gt2fvvxvnoh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xziqi.cn/Article/details/gt2syegowrb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sxryk.cn/Article/details/gt2jssuqesu.html

[P03] 生成短随机字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2byreuwxf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shuidangran.top/Article/details/gt2ciklhruo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shzxlz.cn/Article/details/gt2hztfdtgt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2zgjnlbcl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sufxvd.cn/Article/details/gt2pmqmeklo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.mhx1999.top/Article/details/gt2rznoqibl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guowangkeji.top/Article/details/gt2tsmzzigc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jyoumei.cn/Article/details/gt2lhtlzqfu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258888.top/Article/details/gt2dxtmoygw.html

[P04] 求长度
来源：http://dali.svipenyu.cn/Article/details/gt2ukumtmjj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shzxlz.cn/Article/details/gt2hjeqlhtu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dymujsdn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hongshengwenyu.top/Article/details/gt2ixrtgiea.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ivvv.top/Article/details/gt2dkcrbixv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qzbstrzv.html

Go:   len(arr);  len(m)
来源：http://dali.quarkkingdee.top/Article/details/gt2ithfrmcj.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvnrisp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gt2ydarrfxm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.mhx1999.top/Article/details/gt2zinsdfxy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ydzc1.top/Article/details/gt2tjszzdhe.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gaohongyu789.top/Article/details/gt2cgifrsah.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258888.top/Article/details/gt2lgsbnxam.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tian-w.cn/Article/details/gt2damqisyq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sweek.top/Article/details/gt2hbkalmxw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gt2hqxaxmuj.html

Ruby: a == b
来源：http://dali.hongshengwenyu.top/Article/details/gt2wopsmwsg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xuetiantiany.cn/Article/details/gt2swkgytvt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnxiangtu.top/Article/details/gt2eqsjjdds.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.havefunace.top/Article/details/gt2wnshkpbn.html

PHP:  if (empty($x)) {}
来源：http://dali.snrcjt.cn/Article/details/gt2fpwropbb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ivvv.top/Article/details/gt2owxjrxrp.html

TS:   if (x == null) {}
来源：http://dali.birdmap.top/Article/details/gt2vwasrmsb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2dweurenr.html

Go:   if x == nil {}
来源：http://dali.chenlongwang.top/Article/details/gt2heygitxp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xxkatvpy.html

C#:   if (x is null) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2mzvicajw.html

[P07] 防抖与节流
来源：http://dali.hysaishi.cn/Article/details/gt2sausybdr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shuidangran.top/Article/details/gt2hvwlsvzk.html

PHP:  // 手写时间戳比较
来源：http://dali.zdqjudy.top/Article/details/gt2bfnrmpfb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gt2vtyrwkpl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gt2ugynjujg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yonumen.top/Article/details/gt2hgtnaids.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.andypj.xyz/Article/details/gt2osnsnzob.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cqqwz.cn/Article/details/gt2gvbxdmui.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.vqdsnc.cn/Article/details/gt2tbuiezxl.html

[P08] 处理浮点精度问题
来源：http://dali.snrcjt.cn/Article/details/gt2afxkhppc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.smart0.xyz/Article/details/gt2kmhuyxzi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cqqwz.cn/Article/details/gt2uafmpbtb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tanke756.top/Article/details/gt2wzvnklzu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wzboujdl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.snrcjt.cn/Article/details/gt2thjaymse.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenlongwang.top/Article/details/gt2xnczqjkm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yanxiufei.cn/Article/details/gt2rbzzvrrq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxuanxn.top/Article/details/gt2twhuhkgb.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2lugfbdwz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.svipenyu.cn/Article/details/gt2qulgpdod.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2oyrpobpn.html

[Q01] 创建表
来源：http://dali.feifeiyinyue.top/Article/details/gt2tyekmuvo.html

CREATE TABLE users (
来源：http://dali.chenlongwang.top/Article/details/gt2mlnzjmht.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenzaomai.com/Article/details/gt2nddvljjt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fzcygtgp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aizwys.cn/Article/details/gt2fvyjocub.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yuxming.cn/Article/details/gt2retndznx.html

);
来源：http://dali.tianlin.xyz/Article/details/gt2fdwufzzg.html

[Q02] 创建带外键的表
来源：http://dali.haohaochexian.top/Article/details/gt2qwkamvkd.html

CREATE TABLE orders (
来源：http://dali.kuanghao11.cn/Article/details/gt2wqiidykx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gt2mxketath.html

user_id INT NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gt2ljmtxsle.html

amount DECIMAL(10, 2),
来源：http://dali.aibaodan.cn/Article/details/gt2dwronsjb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cdnleiting.top/Article/details/gt2komysrdf.html

);
来源：http://dali.yj20258.top/Article/details/gt2lesbfpoh.html

[Q03] 增加列
来源：http://dali.quarkkingdee.top/Article/details/gt2gzrdfrkl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.c1oappe.top/Article/details/gt2wziacgla.html

[Q04] 修改列类型
来源：http://dali.yuanzhike.top/Article/details/gt2ocvtlgzx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jianghu66.top/Article/details/gt2hzwstnzv.html

[Q05] 重命名列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2elqbxzaa.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.birdmap.top/Article/details/gt2qnuzrdhh.html

[Q06] 删除列
来源：http://dali.nanxuanxn.top/Article/details/gt2nkuwhudw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gzhubu.top/Article/details/gt2bekvjghb.html

[Q07] 删除表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zdxoncbm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cashguo.top/Article/details/gt2rflfucrq.html

[Q08] 创建普通索引
来源：http://dali.jinqigufen.top/Article/details/gt2qnrtcwtw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sufxvd.cn/Article/details/gt2grwxvaiz.html

[Q09] 创建唯一索引
来源：http://dali.yj20258888.top/Article/details/gt2gbpzpdot.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shuidangran.top/Article/details/gt2axoiupvh.html

[Q10] 插入单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lmdgubgo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jqgfzy.top/Article/details/gt2lbwbimxh.html

[Q11] 一次插入多行
来源：http://dali.yueranfly.top/Article/details/gt2fhjomhiz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jiagoushi.top/Article/details/gt2nlwirbca.html

[Q12] 插入后取自增 ID
来源：http://dali.jqgufenzy.top/Article/details/gt2vvwuibqj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cqqwz.cn/Article/details/gt2cnvharam.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.mhx1999.top/Article/details/gt2trofwnif.html

[Q13] 忽略重复插入
来源：http://dali.zhongyouzk.top/Article/details/gt2xgkitoyq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yyxfsbkv.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj20258.top/Article/details/gt2tbdpjpeu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.316326.xyz/Article/details/gt2mocmodlz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yonumen.top/Article/details/gt2mrguodnp.html

[Q15] 查询全部
来源：http://dali.quarkkingdee.top/Article/details/gt2zflyithx.html

SELECT * FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2bujpoxec.html

[Q16] 查询指定列
来源：http://dali.shangyingyoupin.top/Article/details/gt2atjiekch.html

SELECT id, name FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2siigsbtq.html

[Q17] 条件查询
来源：http://dali.pycfn.com/Article/details/gt2ffsbsaev.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuxming.cn/Article/details/gt2sddqoray.html

[Q18] 模糊匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tbcitoyy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.meibo888.top/Article/details/gt2tnzkydmf.html

[Q19] 范围查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2xfaxvwyf.html


<!-- 参考信息 -->