代发 wailian999

TS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gtpvazjrau.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cqqwz.cn/Article/details/gtmbnaaoof.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxinkj.top/Article/details/gtlxbbpipm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.snrcjt.cn/Article/details/gtjrtillof.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuetiantiany.cn/Article/details/gttzigmqhu.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtxlkuhdbj.html

N. 数据结构与算法
来源：http://dali.xziqi.cn/Article/details/gtjdzpmuja.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtgyzdbavg.html

[N01] 二分查找（有序数组）
来源：http://dali.zhongyouzk.top/Article/details/gtdkixatbs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shuidangran.top/Article/details/gteptlpgpl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtigiuojtu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fengsongda.top/Article/details/gtchfiqzrb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjncynqrm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuanzx.com/Article/details/gthzqnygth.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtxrhkygiq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ivvv.top/Article/details/gtlqaidjjt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtcyjqyvph.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zdqjudy.top/Article/details/gtpcjwxbno.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.0kj1m.cn/Article/details/gtaytirrmp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hywenlv.cn/Article/details/gtdvcrxwbh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gtqygimkdr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzewmzywx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gotoacloud.top/Article/details/gttugsajse.html

Go:   slices.Sort(arr)
来源：http://dali.jiagoushi.top/Article/details/gtexcgseno.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gtjhjbmbmu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gttabbcttf.html

[N03] 快速排序（分治示例）
来源：http://dali.svipenyu.cn/Article/details/gtwadjfbzb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.feifeiyinyue.top/Article/details/gtxazencmn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jqgfzy.top/Article/details/gtnckqpmbk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gogol.net.cn/Article/details/gtylmikigu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gtqijckimz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgufenzy.top/Article/details/gtiblbfkwv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cdnleiting.top/Article/details/gtwvzaqxvt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yongpay.top/Article/details/gtplgouflu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258.top/Article/details/gtvjzzyoyc.html

[N04] 斐波那契数列
来源：http://dali.redwolf501.top/Article/details/gtladhggll.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gtynbsbiut.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gtncggpvzy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gtwreldbku.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtzcqafcdx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gtdhwqqixb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcniiggof.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shzxlz.cn/Article/details/gthhiagdkp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtxqqfzaqt.html

[N05] 最大公约数
来源：http://dali.yj20258888.top/Article/details/gtqgyycwse.html

Py:   math.gcd(a, b)
来源：http://dali.guannengcc.top/Article/details/gtcngkclix.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gzhubu.top/Article/details/gtyztadtvj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtiisdqkhc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gtjrjjvdsc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.mhx1999.top/Article/details/gtqzdeiqys.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhoulong.xyz/Article/details/gtsebezcgq.html

Ruby: a.gcd(b)
来源：http://dali.xuanzx.com/Article/details/gtmssiglsp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.haohaochexian.top/Article/details/gtzpqldqdm.html

[N06] 判断回文字符串
来源：http://dali.zhongyouzk.top/Article/details/gttrsxydys.html

Py:   s == s[::-1]
来源：http://dali.meibo888.top/Article/details/gtinkrfwoi.html

PHP:  $s === strrev($s);
来源：http://dali.yvedp.cn/Article/details/gtzxreleih.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtwcqvegol.html

TS:   s === [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtikorroni.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxinkj.top/Article/details/gtamlqoozn.html

Go:   // 双指针从两端比较
来源：http://dali.shuidangran.top/Article/details/gtmryckblg.html

Ruby: s == s.reverse
来源：http://dali.yj20258.top/Article/details/gtfeulfcpk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gtnflvmmoj.html

[N07] 两数之和（返回下标）
来源：http://dali.shzxlz.cn/Article/details/gtwzcgsaoc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sufxvd.cn/Article/details/gtpcucmbko.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.kuanghao11.cn/Article/details/gtwckvtvru.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dianchejie.cn/Article/details/gtkmqdxhqh.html

TS:   // 手写 Map<string, number>
来源：http://dali.jyoumei.cn/Article/details/gtxklmkpfq.html

Java: // 手写 HashMap
来源：http://dali.havefunace.top/Article/details/gtzytduorm.html

Go:   // 手写 map[int]int
来源：http://dali.ppjwa.cn/Article/details/gtlapyrkee.html

Ruby: // 手写 Hash
来源：http://dali.tianlin.xyz/Article/details/gtmwihoknx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xinyue.icu/Article/details/gtfynchbsl.html

[N08] 生成全排列
来源：http://dali.chenzaomai.com/Article/details/gtilmewmdd.html

Py:   itertools.permutations(arr)
来源：http://dali.cdnleiting.top/Article/details/gtaimhwovf.html

PHP:  // 手写递归交换
来源：http://dali.zycfv.cn/Article/details/gtcahqkcns.html

JS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnkmksob.html

TS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtietzmhak.html

Java: // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtmpogeenv.html

Go:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gteopssgqe.html

Ruby: arr.permutation.to_a
来源：http://dali.chenzaomai.com/Article/details/gtimjjvjtn.html

C#:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtevksnhnf.html

[N09] 栈与队列
来源：http://dali.yuanzhike.top/Article/details/gtrqlgefwy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tanke756.top/Article/details/gtcjqgvohn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gtcnvgdenm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gtjuacxjwu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fzhhl.top/Article/details/gtaoxnvqiw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guowangkeji.top/Article/details/gtqkxontvs.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nwbrower.top/Article/details/gtxliousnj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gtzsrjmeak.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hywenlv.cn/Article/details/gtmcgqnmhc.html

[N10] 链表节点定义
来源：http://dali.ybcxt.top/Article/details/gtdrdoksph.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvvbjest.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cheryme.top/Article/details/gtcclfpagz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yonumen.top/Article/details/gtpbxbkmtf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhixingplan.top/Article/details/gtowhzmqeh.html

Java: class Node { int v; Node next; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvddiawri.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hysaishi.cn/Article/details/gtsnxyeriz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guowangkeji.top/Article/details/gtsdozzhgo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cqqwz.cn/Article/details/gtjiklaonr.html

[N11] 二叉树中序遍历
来源：http://dali.hnxiangtu.top/Article/details/gtltrdgazj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangtech.top/Article/details/gtobjujpbu.html

PHP:  // 手写递归函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsotjqbi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gtwpqncfgc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvuokekk.html

Java: // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtvfevytop.html

Go:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gttinxzezj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sxryk.cn/Article/details/gtmnnvdwiu.html

C#:   // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gtaqdajjeg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgufenzy.top/Article/details/gtlcqqbiuz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.redwolf501.top/Article/details/gtkazqmcah.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.316326.xyz/Article/details/gtcltzpbre.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.mhx1999.top/Article/details/gthwxrxpxs.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gtooimntzt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gtsofdhqjw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxinkj.top/Article/details/gtjkjdnwht.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gtkfsxkrwz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhiwuduotai.top/Article/details/gtxbwgpcgr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtfcevrasc.html

O. 并发与异步
来源：http://dali.ppjwa.cn/Article/details/gtlpxtumye.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtpypoeqgh.html

[O01] 启动一个线程
来源：http://dali.cheryme.top/Article/details/gtpybcvmsh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gaohongyu789.top/Article/details/gtrffzyibz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj202588.top/Article/details/gtrylwkbuz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskeklxds.html

TS:   // 同 JS
来源：http://dali.ehwqpu.com/Article/details/gtcpeqsxwn.html

Java: new Thread(() -> f()).start()
来源：http://dali.tanke756.top/Article/details/gtchgycxcy.html

Go:   go f()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoojvegko.html

Ruby: Thread.new { f }
来源：http://dali.redwolf501.top/Article/details/gtzlgpetnu.html

C#:   Task.Run(() => F());
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdielaef.html

[O02] 使用线程池
来源：http://dali.hnxiangtu.top/Article/details/gtxrgotrbj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.iojbl.cn/Article/details/gtgeyxonsx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tanke756.top/Article/details/gtthzmoail.html

JS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gtrqqaiuhv.html

TS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gtapyqvocn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tian-w.cn/Article/details/gtxhlwctbh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cdnleiting.top/Article/details/gtyoipjwev.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fengsongda.top/Article/details/gtpheqrpla.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yueranfly.top/Article/details/gtemfqyqza.html

[O03] 加锁保护共享数据
来源：http://dali.tanke756.top/Article/details/gtaavopebs.html

Py:   with lock: shared += 1
来源：http://dali.kuanghao11.cn/Article/details/gtativhozs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yangfankeji.com/Article/details/gtpxarfwxk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gtxrwbeacu.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gtblhpiiiy.html

Java: synchronized (this) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gtxvdfhusa.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.aibaodan.cn/Article/details/gtzjiilgfj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gaohongyu789.top/Article/details/gtcpzdwybq.html

C#:   lock (gate) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gtyhfhuevy.html

[O04] 定义异步函数并等待
来源：http://dali.hfpthk.cn/Article/details/gtiyibrikr.html

Py:   async def f():⏎    await g()
来源：http://dali.gogol.net.cn/Article/details/gtpodykzqb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhongyouzk.top/Article/details/gtigdjdgdj.html

JS:   async function f() { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gttyfintan.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258.top/Article/details/gtfnkxmynv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.snrcjt.cn/Article/details/gtogajfjtd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.pengpengdd.cyou/Article/details/gtipojckrs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.0kj1m.cn/Article/details/gtddbiqcho.html

C#:   async Task F() { await G(); }
来源：http://dali.jianghu66.top/Article/details/gtqpeipizc.html

[O05] 并发执行并等待全部完成
来源：http://dali.cucudq.cn/Article/details/gtqlnvihpb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sysykeji.top/Article/details/gtvsxwhkjl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhongyouzk.top/Article/details/gtzrnnzvjb.html

JS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtzsrkfd.html

TS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gteyumntwe.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.mhx1999.top/Article/details/gtqfpommcn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tianlin.xyz/Article/details/gtoqtqeaap.html

Ruby: threads.map(&:join)
来源：http://dali.iojbl.cn/Article/details/gtgyxcnmzk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gotoacloud.top/Article/details/gtvujsqsip.html

[O06] 使用进程池
来源：http://dali.shangyingyoupin.top/Article/details/gthrvgtqos.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fengsongda.top/Article/details/gtmmtcjfsq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yangfankeji.com/Article/details/gtfnbtzwwb.html

JS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gtimevbdpt.html

TS:   // child_process / cluster 模块
来源：http://dali.redwolf501.top/Article/details/gtzdlntnnd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.c1oappe.top/Article/details/gtqojywvim.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yvedp.cn/Article/details/gtnlzjptom.html

Ruby: // fork 块
来源：http://dali.meibo888.top/Article/details/gtxmidawmw.html

C#:   Parallel.For
来源：http://dali.xylfe.cn/Article/details/gtaciwzryf.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtqntoashz.html

P. 常用工具函数
来源：http://dali.yangfankeji.com/Article/details/gtcyrvegfb.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtyvalgxxs.html

[P01] 生成 UUID
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkszmhfzx.html

Py:   str(uuid.uuid4())
来源：http://dali.shzxlz.cn/Article/details/gtfzujfgit.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.snrcjt.cn/Article/details/gtejrscrdn.html

JS:   crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gttvenwokw.html

TS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtfeojwwab.html

Java: UUID.randomUUID().toString()
来源：http://dali.ydzc1.top/Article/details/gtdcohuhoa.html

Go:   // 用 github.com/google/uuid
来源：http://dali.aizwys.cn/Article/details/gtgeqbddxt.html

Ruby: SecureRandom.uuid
来源：http://dali.dashuyun.cn/Article/details/gtemgjmryp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.fengsongda.top/Article/details/gtknrdkxdg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gotoacloud.top/Article/details/gteziotydw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shzxlz.cn/Article/details/gtxjbxbgei.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cashguo.top/Article/details/gtlglakrtx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.kuanghao11.cn/Article/details/gtldqjyftw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yvedp.cn/Article/details/gtpzpofesc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gtlwlovbxv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.quarkkingdee.top/Article/details/gtceepboaw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hfpthk.cn/Article/details/gtifcoqwzu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuxming.cn/Article/details/gtglswlvjz.html

[P03] 生成短随机字符串
来源：http://dali.yvedp.cn/Article/details/gtykkwrjep.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jlsjyb.cn/Article/details/gtnfpkrzwj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqyiyuvs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgfzy.top/Article/details/gtfqfamdsx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtminlrzhk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jqgufenzy.top/Article/details/gtcpriggzn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yanxiufei.cn/Article/details/gtmoisdinh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.meibo888.top/Article/details/gtdmxoqnzy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258.top/Article/details/gtunxmxzyq.html

[P04] 求长度
来源：http://dali.sysykeji.top/Article/details/gtzzapwyfs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tianlin.xyz/Article/details/gtvhoansly.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtrkdivbht.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gtkrsrezox.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pengpengdd.cyou/Article/details/gtjiilohec.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gogol.net.cn/Article/details/gtwgrwqcpw.html

Go:   len(arr);  len(m)
来源：http://dali.gzhubu.top/Article/details/gtcgmscogk.html

Ruby: x.length;  x.size
来源：http://dali.hnxiangtu.top/Article/details/gtuylxdbqt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gthnggckcc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dashuyun.cn/Article/details/gtjksvodqn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenlongwang.top/Article/details/gtkadpljpd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hammf.cn/Article/details/gtzanjumdy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ehwqpu.com/Article/details/gtznfgvxgp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gtptzbovna.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.c1oappe.top/Article/details/gtqmhfqmdu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gogol.net.cn/Article/details/gtabmwsivq.html

Ruby: a == b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvktbpiuo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxinkj.top/Article/details/gtnmzplagx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zycfv.cn/Article/details/gtgmgdurix.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pengpengdd.cyou/Article/details/gtsyhlblcs.html

PHP:  if (empty($x)) {}
来源：http://dali.hammf.cn/Article/details/gtsdweyttf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgfzy.top/Article/details/gtrrdxtoip.html

TS:   if (x == null) {}
来源：http://dali.nanxuanxn.top/Article/details/gtrdomjctv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gtimjqejtj.html

Go:   if x == nil {}
来源：http://dali.andypj.xyz/Article/details/gtcqmagqaj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cqqwz.cn/Article/details/gtnhawkvzh.html

C#:   if (x is null) {}
来源：http://dali.hammf.cn/Article/details/gtdnswjqgc.html

[P07] 防抖与节流
来源：http://dali.shangyingyoupin.top/Article/details/gtozvgicyi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhixingplan.top/Article/details/gtxvidmlll.html

PHP:  // 手写时间戳比较
来源：http://dali.cheryme.top/Article/details/gtkmlbkeat.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gthrwmesre.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gtzonwvbmm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tianlin.xyz/Article/details/gtkqxdrkiy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.bjfxy.top/Article/details/gtknigemzz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.9152youxi.cn/Article/details/gtkxphlhaf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ppjwa.cn/Article/details/gtlywbjcep.html

[P08] 处理浮点精度问题
来源：http://dali.316326.xyz/Article/details/gtgbujzufd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gtziktzthb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.redwolf501.top/Article/details/gtezspxtgs.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daxiang520.top/Article/details/gthzcparee.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.andypj.xyz/Article/details/gtofvyvwbu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jlsjyb.cn/Article/details/gtxilcrmkw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvdijxxw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gotoacloud.top/Article/details/gtopiswyfg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xinyue.icu/Article/details/gtuulrvndv.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtrjtpriha.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jiagoushi.top/Article/details/gtjfjrivym.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtodiyuaat.html

[Q01] 创建表
来源：http://dali.hammf.cn/Article/details/gtoodzxyah.html

CREATE TABLE users (
来源：http://dali.0kj1m.cn/Article/details/gteplvvfnt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tian-w.cn/Article/details/gtkxsumrky.html

name VARCHAR(50) NOT NULL,
来源：http://dali.pycfn.com/Article/details/gtnxgclyyr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cdnleiting.top/Article/details/gtitbkgiez.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenlongwang.top/Article/details/gtzcxfvhmz.html

);
来源：http://dali.cashguo.top/Article/details/gttjpvoxqn.html

[Q02] 创建带外键的表
来源：http://dali.zhixingplan.top/Article/details/gtjiikfclp.html

CREATE TABLE orders (
来源：http://dali.feifeiyinyue.top/Article/details/gthlnraane.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuanzx.com/Article/details/gtgddtrclt.html

user_id INT NOT NULL,
来源：http://dali.havefunace.top/Article/details/gtxwopcozk.html

amount DECIMAL(10, 2),
来源：http://dali.hfpthk.cn/Article/details/gtbxtizeib.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sysykeji.top/Article/details/gtjeoolgri.html

);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgnkvypk.html

[Q03] 增加列
来源：http://dali.svipenyu.cn/Article/details/gtvgccofnp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pengpengdd.cyou/Article/details/gtadmvcdrb.html

[Q04] 修改列类型
来源：http://dali.316326.xyz/Article/details/gtknugtsak.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhoulong.xyz/Article/details/gttfxfrhyf.html

[Q05] 重命名列
来源：http://dali.ywan-chungtsiang.top/Article/details/gttuipnrzx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zdqjudy.top/Article/details/gtqvbmtgst.html

[Q06] 删除列
来源：http://dali.tanke756.top/Article/details/gtrntwdpnb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gzhubu.top/Article/details/gtyhryevwy.html

[Q07] 删除表
来源：http://dali.dianchejie.cn/Article/details/gtdqrdvekm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.havefunace.top/Article/details/gtoofbpgnw.html

[Q08] 创建普通索引
来源：http://dali.haohaochexian.top/Article/details/gtuweyfwoo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jqgufenzy.top/Article/details/gtzvebwvek.html

[Q09] 创建唯一索引
来源：http://dali.cdnleiting.top/Article/details/gtuningmis.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sweek.top/Article/details/gtmjlhziwf.html

[Q10] 插入单行
来源：http://dali.ehwqpu.com/Article/details/gtczsozohv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guowangkeji.top/Article/details/gtpmiwfgxi.html

[Q11] 一次插入多行
来源：http://dali.chenlongwang.top/Article/details/gtcpfozxir.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangdashe.top/Article/details/gtxxviqpdk.html

[Q12] 插入后取自增 ID
来源：http://dali.cheryme.top/Article/details/gtaenvcurb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shzxlz.cn/Article/details/gtxukspvts.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hywenlv.cn/Article/details/gtvhphobms.html

[Q13] 忽略重复插入
来源：http://dali.jinqigufen.top/Article/details/gtkcztomiv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj20258.top/Article/details/gtahdsqybv.html

[Q14] 存在则更新（upsert）
来源：http://dali.jqgufenzy.top/Article/details/gtpcoidxfk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gaohongyu789.top/Article/details/gtkwxztpvn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gtjkzjkgah.html

[Q15] 查询全部
来源：http://dali.svipenyu.cn/Article/details/gtrvxjkfbe.html

SELECT * FROM users;
来源：http://dali.yj202588.top/Article/details/gtscvgrzsf.html

[Q16] 查询指定列
来源：http://dali.gaohongyu789.top/Article/details/gtetftvgiy.html

SELECT id, name FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtxjhwwpoi.html

[Q17] 条件查询
来源：http://dali.chenjidiqi.icu/Article/details/gtsnsmduje.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daxiang520.top/Article/details/gtdxreodrb.html

[Q18] 模糊匹配
来源：http://dali.mhx1999.top/Article/details/gteypczbqh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.9152youxi.cn/Article/details/gtsgujhycc.html

[Q19] 范围查询
来源：http://dali.iojbl.cn/Article/details/gtcuyzexcc.html


<!-- 参考信息 -->