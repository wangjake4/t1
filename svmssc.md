代发 wailian999

[M08] 获取系统与运行时信息
来源：http://dali.nwbrower.top/Article/details/gttpztivoi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yangfankeji.com/Article/details/gtnbfjzwgw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hammf.cn/Article/details/gtdqiqfjyy.html

JS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtujisss.html

TS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtycxeqcat.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangshuangyany.cn/Article/details/gtfjhmzqlm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigufen.top/Article/details/gtkdqgnmma.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.vqdsnc.cn/Article/details/gtxmyeaqmv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xinyue.icu/Article/details/gtmlpgvmxi.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtlvhvfems.html

N. 数据结构与算法
来源：http://dali.nwbrower.top/Article/details/gttgqidsug.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtprsdeaej.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxuanxn.top/Article/details/gtvfbvossp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtfarywngi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tian-w.cn/Article/details/gtgudsncgi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtqskiqyhm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gtqgxgfutd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygefbrnp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtescdbeij.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigfzy.top/Article/details/gtdnscpvws.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtoynkvwsk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgfzy.top/Article/details/gteubrafun.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gtgnzurfde.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jianghu66.top/Article/details/gtlzpaqsxy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gtysoqcfcx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtdzejtwaa.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fengsongda.top/Article/details/gtgqmwxpif.html

Go:   slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gtwgxbhwum.html

Ruby: arr.sort
来源：http://dali.yueranfly.top/Article/details/gtvhmreaus.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.mhx1999.top/Article/details/gtcjrfpyrr.html

[N03] 快速排序（分治示例）
来源：http://dali.meibo888.top/Article/details/gtkduedwpl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yvedp.cn/Article/details/gtgqmedvtk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gotoacloud.top/Article/details/gtqtmxgvre.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gtiipuojvq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gtfpdmoxue.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258.top/Article/details/gtnusbeqla.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dianchejie.cn/Article/details/gtycdrxjrx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangtech.top/Article/details/gtvazntayq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cashguo.top/Article/details/gtmimfemqn.html

[N04] 斐波那契数列
来源：http://dali.pengpengdd.cyou/Article/details/gtpswqdman.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtldfrnzqf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nwbrower.top/Article/details/gtkzzvyfph.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gtbdnwhurc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtptnsrrbs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnqzz.top/Article/details/gtamdftqxa.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aizwys.cn/Article/details/gtnhljvzvz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtwelbcwii.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtruxmmefo.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gtiidojbdv.html

Py:   math.gcd(a, b)
来源：http://dali.wangdashe.top/Article/details/gtfomkefca.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dashuyun.cn/Article/details/gtgdujloip.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenzaomai.com/Article/details/gtkypvucqt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gtipnsoomk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yueranfly.top/Article/details/gtesjcqxgr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ivvv.top/Article/details/gtigvgppwj.html

Ruby: a.gcd(b)
来源：http://dali.guowangkeji.top/Article/details/gtghajxyge.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shuidangran.top/Article/details/gtupilwmmg.html

[N06] 判断回文字符串
来源：http://dali.yongpay.top/Article/details/gtzuluzsql.html

Py:   s == s[::-1]
来源：http://dali.chenjidiqi.icu/Article/details/gtchvnflbc.html

PHP:  $s === strrev($s);
来源：http://dali.xuanzx.com/Article/details/gtevbqyddd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtmzsygeny.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtmdfgdlob.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuetiantiany.cn/Article/details/gtrmabaddb.html

Go:   // 双指针从两端比较
来源：http://dali.gogol.net.cn/Article/details/gtbsppbszj.html

Ruby: s == s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gtggboazzu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gtluryjoil.html

[N07] 两数之和（返回下标）
来源：http://dali.haohaochexian.top/Article/details/gtsdomaowu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dashuyun.cn/Article/details/gtrafhaldt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sufxvd.cn/Article/details/gtbljqcjum.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hammf.cn/Article/details/gtzlvhpfds.html

TS:   // 手写 Map<string, number>
来源：http://dali.sufxvd.cn/Article/details/gtbitstngj.html

Java: // 手写 HashMap
来源：http://dali.gaohongyu789.top/Article/details/gtraoakplq.html

Go:   // 手写 map[int]int
来源：http://dali.wangdashe.top/Article/details/gteyoedvbw.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykmmhald.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shzxlz.cn/Article/details/gtwurevhox.html

[N08] 生成全排列
来源：http://dali.yvedp.cn/Article/details/gtqnnytddc.html

Py:   itertools.permutations(arr)
来源：http://dali.cashguo.top/Article/details/gtccojjvia.html

PHP:  // 手写递归交换
来源：http://dali.guannengcc.top/Article/details/gtvpqdvpcb.html

JS:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtyvbpzztb.html

TS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtljyjdtns.html

Java: // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtghsxdtle.html

Go:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtemhvltpt.html

Ruby: arr.permutation.to_a
来源：http://dali.mhx1999.top/Article/details/gthznrpxdd.html

C#:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtzarafidm.html

[N09] 栈与队列
来源：http://dali.zycfv.cn/Article/details/gtvjjnvngr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yonumen.top/Article/details/gtbwxagplq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gtdhlgquca.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gtpyjpthzb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigufen.top/Article/details/gtvtxghrlc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sysykeji.top/Article/details/gtagnbmwqr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.haohaochexian.top/Article/details/gtspngutxe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gtdszbuega.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.quarkkingdee.top/Article/details/gtrhzocdrs.html

[N10] 链表节点定义
来源：http://dali.ivvv.top/Article/details/gturxtaabg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgfzy.top/Article/details/gteejmqzwo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xinyue.icu/Article/details/gtdhgfajkw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sysykeji.top/Article/details/gtpgrkavmi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xylfe.cn/Article/details/gttgyalcsx.html

Java: class Node { int v; Node next; }
来源：http://dali.cheryme.top/Article/details/gtyrsdgmsv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gotoacloud.top/Article/details/gtzzavlzze.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangdashe.top/Article/details/gtcblxammh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pengpengdd.cyou/Article/details/gteezajaks.html

[N11] 二叉树中序遍历
来源：http://dali.xuanzx.com/Article/details/gtiewejhww.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj20258888.top/Article/details/gtucyhseta.html

PHP:  // 手写递归函数
来源：http://dali.yueranfly.top/Article/details/gtyntfrmjx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gttaibftua.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gtircyudhv.html

Java: // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtrnuliehs.html

Go:   // 手写递归
来源：http://dali.ybcxt.top/Article/details/gttrtdztyv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ybcxt.top/Article/details/gtvnybckhe.html

C#:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtebihdsmo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xylfe.cn/Article/details/gtkyiemoat.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.vqdsnc.cn/Article/details/gtlcbecrkm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jiagoushi.top/Article/details/gtttyebmot.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtbabwwcui.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xziqi.cn/Article/details/gtnbsdxdmk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gtwzwtdfii.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shuidangran.top/Article/details/gtkpwxmpvl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.birdmap.top/Article/details/gtsvjfbbcu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhengqikj.top/Article/details/gtkxlfbzhs.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtlfytazea.html

O. 并发与异步
来源：http://dali.gogol.net.cn/Article/details/gtgfqonpcz.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtxtyhpujd.html

[O01] 启动一个线程
来源：http://dali.xziqi.cn/Article/details/gtadnugsng.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.iojbl.cn/Article/details/gtldkappde.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnxiangtu.top/Article/details/gtmfupioze.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.316326.xyz/Article/details/gtwcmcnxzv.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gtaodqujkz.html

Java: new Thread(() -> f()).start()
来源：http://dali.sxryk.cn/Article/details/gtextafooi.html

Go:   go f()
来源：http://dali.jinqigufen.top/Article/details/gthskazqur.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gtdptueqql.html

C#:   Task.Run(() => F());
来源：http://dali.xinyue.icu/Article/details/gtuawhejsr.html

[O02] 使用线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtagotwgav.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cqqwz.cn/Article/details/gtavxckmtk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.andypj.xyz/Article/details/gtvvcmmlov.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtniaugggb.html

TS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gtomywwhtq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jiagoushi.top/Article/details/gtscaddnra.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ppjwa.cn/Article/details/gtofbiypuq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zycfv.cn/Article/details/gtqletndhw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.birdmap.top/Article/details/gtkuuzitvi.html

[O03] 加锁保护共享数据
来源：http://dali.xinyue.icu/Article/details/gtezwexgit.html

Py:   with lock: shared += 1
来源：http://dali.gogol.net.cn/Article/details/gtmmoumrty.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ybcxt.top/Article/details/gtwbifuayb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgfzy.top/Article/details/gthmzkbeiy.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gtisiqcimu.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtttfdbvxi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnxiangtu.top/Article/details/gtgxitbwom.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhoulong.xyz/Article/details/gtadqebssp.html

C#:   lock (gate) { shared++; }
来源：http://dali.havefunace.top/Article/details/gttsojtbec.html

[O04] 定义异步函数并等待
来源：http://dali.svipenyu.cn/Article/details/gttzusnpzw.html

Py:   async def f():⏎    await g()
来源：http://dali.xuetiantiany.cn/Article/details/gtpikjhtga.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxinkj.top/Article/details/gtdjbyvtut.html

JS:   async function f() { await g(); }
来源：http://dali.hywenlv.cn/Article/details/gtbkmkchhb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gtmvvegxnu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenzaomai.com/Article/details/gtqgcnzibl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqahuulc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigfzy.top/Article/details/gtotnzwvns.html

C#:   async Task F() { await G(); }
来源：http://dali.dianchejie.cn/Article/details/gtolyjuwqc.html

[O05] 并发执行并等待全部完成
来源：http://dali.0kj1m.cn/Article/details/gtpixzlseo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nanxinkj.top/Article/details/gtyfaduzag.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ydzc1.top/Article/details/gtqjemlwep.html

JS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gtanlpeyhn.html

TS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gtoxrbopih.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cheryme.top/Article/details/gtulbluqea.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yongpay.top/Article/details/gtndgznjjl.html

Ruby: threads.map(&:join)
来源：http://dali.wangdashe.top/Article/details/gtgadxauyd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hfpthk.cn/Article/details/gtkutiftoi.html

[O06] 使用进程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqchbdyd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shzxlz.cn/Article/details/gtwoklbupr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnqzz.top/Article/details/gtfscbrzgp.html

JS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gtfgfysoro.html

TS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gtramcuada.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.smart0.xyz/Article/details/gtfoiiwyob.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sysykeji.top/Article/details/gtxubssncr.html

Ruby: // fork 块
来源：http://dali.ybcxt.top/Article/details/gtknzlkqrv.html

C#:   Parallel.For
来源：http://dali.yuanzhike.top/Article/details/gtdvzalyxr.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtdwdqyuzq.html

P. 常用工具函数
来源：http://dali.yj202588.top/Article/details/gtlsimbdmw.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtxzcpgmkd.html

[P01] 生成 UUID
来源：http://dali.jqgufenzy.top/Article/details/gtnwqefemb.html

Py:   str(uuid.uuid4())
来源：http://dali.316326.xyz/Article/details/gtmnmsbggm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.0kj1m.cn/Article/details/gtomaqvepg.html

JS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gtnjwzfxxo.html

TS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gtbjrgwwmh.html

Java: UUID.randomUUID().toString()
来源：http://dali.pycfn.com/Article/details/gtroksqydo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gtnoeqvevt.html

Ruby: SecureRandom.uuid
来源：http://dali.andypj.xyz/Article/details/gtljfydfcw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.kuanghao11.cn/Article/details/gtcreiihfv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.kuanghao11.cn/Article/details/gtlcxurnwx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tianlin.xyz/Article/details/gtskcwymnt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.c1oappe.top/Article/details/gtsobexlil.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yanxiufei.cn/Article/details/gtilctnqna.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zdqjudy.top/Article/details/gttsylbwcs.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cqqwz.cn/Article/details/gttccxvmsj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenzaomai.com/Article/details/gtazperlvs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gtfyuupyoe.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yonumen.top/Article/details/gtgonrmxto.html

[P03] 生成短随机字符串
来源：http://dali.dianchejie.cn/Article/details/gtyzwakbpn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.316326.xyz/Article/details/gtbtloojgg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj20258.top/Article/details/gtuyltgqha.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzvlkijm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtzqiooqrp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sufxvd.cn/Article/details/gtzpzcxkzp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xinyue.icu/Article/details/gtbcsfwbrp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ehwqpu.com/Article/details/gtnnqydavf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xziqi.cn/Article/details/gtdhostyay.html

[P04] 求长度
来源：http://dali.nanxinkj.top/Article/details/gtcqlpxdsd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zdqjudy.top/Article/details/gtlajmcoub.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtpztnjcjm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gtpikjeuje.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhengqikj.top/Article/details/gtkxlryyux.html

Java: list.size();  map.size();  s.length()
来源：http://dali.c1oappe.top/Article/details/gtehitjtks.html

Go:   len(arr);  len(m)
来源：http://dali.zhoulong.xyz/Article/details/gtjxwdeoct.html

Ruby: x.length;  x.size
来源：http://dali.dashuyun.cn/Article/details/gtlumydudd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.daria6918.cn/Article/details/gtufciiwfe.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jianghu66.top/Article/details/gtglruczpz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.vqdsnc.cn/Article/details/gtdnzcyxvq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hywenlv.cn/Article/details/gteffvbsqo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgfzy.top/Article/details/gtdjdzrvzx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jiagoushi.top/Article/details/gtgwcakmin.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.smart0.xyz/Article/details/gtoomowfqk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.redwolf501.top/Article/details/gtjfnswbbk.html

Ruby: a == b
来源：http://dali.gogol.net.cn/Article/details/gtzdfenftn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.aibaodan.cn/Article/details/gtxtpbelxm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.kuanghao11.cn/Article/details/gtttvhetmv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.bjfxy.top/Article/details/gtxmsdzhgo.html

PHP:  if (empty($x)) {}
来源：http://dali.xinyue.icu/Article/details/gtkpsgbjbb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyrftknx.html

TS:   if (x == null) {}
来源：http://dali.wangdashe.top/Article/details/gtrtvkrkiz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gtcsvdtvrx.html

Go:   if x == nil {}
来源：http://dali.mhx1999.top/Article/details/gtebxhpvlj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangdashe.top/Article/details/gtpamjviyw.html

C#:   if (x is null) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtbxeaehyp.html

[P07] 防抖与节流
来源：http://dali.hfpthk.cn/Article/details/gtpelplgnx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ybcxt.top/Article/details/gterbxybza.html

PHP:  // 手写时间戳比较
来源：http://dali.redwolf501.top/Article/details/gtiuawzamg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gtrrrxvtpi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtygzfjabc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhoulong.xyz/Article/details/gtijdevwxz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fengsongda.top/Article/details/gttmyztqnu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tian-w.cn/Article/details/gtupkytoqy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.birdmap.top/Article/details/gtuhwjfwyc.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigufen.top/Article/details/gtxisrdgxl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shangyingyoupin.top/Article/details/gtuooiiodk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtiuqyuzgp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gzhubu.top/Article/details/gtqvzsdxrm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtimfcrfyc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cqqwz.cn/Article/details/gtjdkryvqz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.bjfxy.top/Article/details/gtkswmciaa.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcwkwils.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daria6918.cn/Article/details/gtvldjwsft.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtjnstgunb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yangfankeji.com/Article/details/gtwnxgkmsd.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gttkuhzuyt.html

[Q01] 创建表
来源：http://dali.mhx1999.top/Article/details/gtfdsufnij.html

CREATE TABLE users (
来源：http://dali.svipenyu.cn/Article/details/gtqajglcku.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gtzmrpujyu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ybcxt.top/Article/details/gtdlihiucw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ybcxt.top/Article/details/gtqzmhwmrl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.aizwys.cn/Article/details/gtghgzsynx.html

);
来源：http://dali.gogol.net.cn/Article/details/gttqpsvwdo.html

[Q02] 创建带外键的表
来源：http://dali.hammf.cn/Article/details/gtxhkzsofg.html

CREATE TABLE orders (
来源：http://dali.316326.xyz/Article/details/gttfbikmkk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hywenlv.cn/Article/details/gtfmnhmase.html

user_id INT NOT NULL,
来源：http://dali.yongpay.top/Article/details/gtuknmwxzz.html

amount DECIMAL(10, 2),
来源：http://dali.jinghuilouyu.cn/Article/details/gtpmcjcrxj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.daxiang520.top/Article/details/gtrblsrppc.html

);
来源：http://dali.guowangkeji.top/Article/details/gtfavpumss.html

[Q03] 增加列
来源：http://dali.zycfv.cn/Article/details/gtlvriqqyi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdrxdqfb.html

[Q04] 修改列类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtceipoizf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ydzc1.top/Article/details/gtkbofuqkg.html

[Q05] 重命名列
来源：http://dali.shzxlz.cn/Article/details/gtkvofcqhy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.c1oappe.top/Article/details/gtciktixcw.html

[Q06] 删除列
来源：http://dali.yuxming.cn/Article/details/gtrjhqezti.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sysykeji.top/Article/details/gtfstfswyu.html

[Q07] 删除表
来源：http://dali.zhengqikj.top/Article/details/gtufjzaokq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yongpay.top/Article/details/gtsewynwzw.html

[Q08] 创建普通索引
来源：http://dali.shangyingyoupin.top/Article/details/gtidqtwicu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xylfe.cn/Article/details/gtcbheczrc.html

[Q09] 创建唯一索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbthrtmne.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gtyrellpom.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gtdobedgph.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gtsmuqspcu.html

[Q11] 一次插入多行
来源：http://dali.svipenyu.cn/Article/details/gtgvzcavwo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ehwqpu.com/Article/details/gtdekwyoem.html

[Q12] 插入后取自增 ID
来源：http://dali.xylfe.cn/Article/details/gtbpeogyor.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.c1oappe.top/Article/details/gtbneiljwa.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.guannengcc.top/Article/details/gtaqtzfrul.html

[Q13] 忽略重复插入
来源：http://dali.jiagoushi.top/Article/details/gtjlolgmox.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sxryk.cn/Article/details/gtsxxtyvjx.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenjidiqi.icu/Article/details/gtkzggxmbm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gaohongyu789.top/Article/details/gtdxduswwg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjehtshaa.html

[Q15] 查询全部
来源：http://dali.316326.xyz/Article/details/gtvjxznrtm.html

SELECT * FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtqldtiham.html

[Q16] 查询指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmqgwkww.html

SELECT id, name FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtbshagvjz.html

[Q17] 条件查询
来源：http://dali.shzxlz.cn/Article/details/gtrktcyvxz.html


<!-- 参考信息 -->