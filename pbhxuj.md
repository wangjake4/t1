代发 wailian999

TS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gt2gndxgxvt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cashguo.top/Article/details/gt2uehsryld.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mvtdnsvo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wvqmugqj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hammf.cn/Article/details/gt2zlcgkxis.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2rzkmdiqr.html

N. 数据结构与算法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rjrudhnb.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jrytrrwx.html

[N01] 二分查找（有序数组）
来源：http://dali.birdmap.top/Article/details/gt2ldcqzuik.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cncdmkwg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.316326.xyz/Article/details/gt2wbihklug.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mdcubili.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yueranfly.top/Article/details/gt2ladxyhkx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2fnqqtnup.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2dwbqtkpw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hywenlv.cn/Article/details/gt2scswlacn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2xalhaqxg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigufen.top/Article/details/gt2gmrwpius.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gt2hjfgiodh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hywenlv.cn/Article/details/gt2dbxmhyxj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gt2gjnmjxtp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sebsrjob.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shzxlz.cn/Article/details/gt2slkreewu.html

Go:   slices.Sort(arr)
来源：http://dali.cashguo.top/Article/details/gt2bavyqvki.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gt2czbzhmst.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yuxming.cn/Article/details/gt2gfxtzskn.html

[N03] 快速排序（分治示例）
来源：http://dali.gogol.net.cn/Article/details/gt2hfpgjqvm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aibaodan.cn/Article/details/gt2myzlsklw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuanzx.com/Article/details/gt2wgnccqex.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gt2viyamnpc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gt2wxttphev.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgfzy.top/Article/details/gt2fuqeraiz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.c1oappe.top/Article/details/gt2efohvuiz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daxiang520.top/Article/details/gt2uipyellc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hammf.cn/Article/details/gt2bqbahett.html

[N04] 斐波那契数列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gpdxunsk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gt2thhtatuh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gotoacloud.top/Article/details/gt2yhahzwan.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gt2rwahozfa.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gt2ypsuxjhz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.guannengcc.top/Article/details/gt2mmxwjpee.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yonumen.top/Article/details/gt2yjifnjlr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gt2koqdmrab.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gt2hpxihciy.html

[N05] 最大公约数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lywlpzgk.html

Py:   math.gcd(a, b)
来源：http://dali.xuanzx.com/Article/details/gt2sttltdcc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gzhubu.top/Article/details/gt2pdasvivo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gotoacloud.top/Article/details/gt2xahyjmfr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sukiqtnc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uyskctho.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jiagoushi.top/Article/details/gt2qvdpwupu.html

Ruby: a.gcd(b)
来源：http://dali.havefunace.top/Article/details/gt2gqorkeqe.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.aizwys.cn/Article/details/gt2angtcpzj.html

[N06] 判断回文字符串
来源：http://dali.chenzaomai.com/Article/details/gt2eypjartn.html

Py:   s == s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gt2csljqrgi.html

PHP:  $s === strrev($s);
来源：http://dali.daxiang520.top/Article/details/gt2cbhssyka.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gt2usvnyfhk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gt2ergbtstc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pengpengdd.cyou/Article/details/gt2xnqwxded.html

Go:   // 双指针从两端比较
来源：http://dali.hysaishi.cn/Article/details/gt2jzjqzpbv.html

Ruby: s == s.reverse
来源：http://dali.jianghu66.top/Article/details/gt2ebolotug.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gt2guklnvoc.html

[N07] 两数之和（返回下标）
来源：http://dali.yvedp.cn/Article/details/gt2edykikrl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.quarkkingdee.top/Article/details/gt2kvoacxkg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hfpthk.cn/Article/details/gt2hvpogjgn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.birdmap.top/Article/details/gt2zcubdlpn.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsuvlpc.html

Java: // 手写 HashMap
来源：http://dali.wangdashe.top/Article/details/gt2nuhzorro.html

Go:   // 手写 map[int]int
来源：http://dali.yvedp.cn/Article/details/gt2azfnqwwy.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2olohtasz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shzxlz.cn/Article/details/gt2woxioawh.html

[N08] 生成全排列
来源：http://dali.daxiang520.top/Article/details/gt2wtyephft.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2xtkhfwwk.html

PHP:  // 手写递归交换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jirghddu.html

JS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gt2efyobyhs.html

TS:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gt2vjaqdblm.html

Java: // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gt2oibsrluf.html

Go:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gt2hgxxzwpm.html

Ruby: arr.permutation.to_a
来源：http://dali.andypj.xyz/Article/details/gt2tcoaykuz.html

C#:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gt2jucdynqq.html

[N09] 栈与队列
来源：http://dali.snrcjt.cn/Article/details/gt2audkkkmz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cucudq.cn/Article/details/gt2jmxdktdl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gt2heiyyjos.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gt2rcnabpgs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhongyouzk.top/Article/details/gt2wdqtcupz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zdqjudy.top/Article/details/gt2mulfzqdd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.feifeiyinyue.top/Article/details/gt2qhaqzpse.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gt2bjyozogl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yueranfly.top/Article/details/gt2igqheqnk.html

[N10] 链表节点定义
来源：http://dali.pengpengdd.cyou/Article/details/gt2uiwetrre.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pengpengdd.cyou/Article/details/gt2ctowjyst.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shuidangran.top/Article/details/gt2ltpiyiry.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yanxiufei.cn/Article/details/gt2yxqfqpnl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ydzc1.top/Article/details/gt2xvxntiis.html

Java: class Node { int v; Node next; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ajuklqoc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jyoumei.cn/Article/details/gt2bpbdzkcu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zqnblxlo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.andypj.xyz/Article/details/gt2ejsgjksh.html

[N11] 二叉树中序遍历
来源：http://dali.ppjwa.cn/Article/details/gt2crovaxsf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.meibo888.top/Article/details/gt2wnjqabyh.html

PHP:  // 手写递归函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vqzauscf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wcwxagbb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xziqi.cn/Article/details/gt2wzornxup.html

Java: // 手写递归
来源：http://dali.xinyue.icu/Article/details/gt2zeedceir.html

Go:   // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gt2thnwqfik.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.svipenyu.cn/Article/details/gt2umyxahds.html

C#:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gt2qnuibask.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.iojbl.cn/Article/details/gt2vsrkklsa.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fengsongda.top/Article/details/gt2clewtxwb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2glpevzpl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.kuanghao11.cn/Article/details/gt2jwrequnb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhixingplan.top/Article/details/gt2rwqlwpul.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gt2dyxlnqam.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxinkj.top/Article/details/gt2pmtbeojz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.316326.xyz/Article/details/gt2pwfafbow.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gt2rexjpqfw.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2mpjsfyig.html

O. 并发与异步
来源：http://dali.zhixingplan.top/Article/details/gt2jlvhukbe.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2iuzurfdo.html

[O01] 启动一个线程
来源：http://dali.c1oappe.top/Article/details/gt2iqptknmz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenzaomai.com/Article/details/gt2yivsewlf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2qwznmyow.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258888.top/Article/details/gt2xxxlydue.html

TS:   // 同 JS
来源：http://dali.gaohongyu789.top/Article/details/gt2wququnxy.html

Java: new Thread(() -> f()).start()
来源：http://dali.nanxuanxn.top/Article/details/gt2anmxqdve.html

Go:   go f()
来源：http://dali.nanxuanxn.top/Article/details/gt2asnjcpep.html

Ruby: Thread.new { f }
来源：http://dali.chenlongwang.top/Article/details/gt2gitattag.html

C#:   Task.Run(() => F());
来源：http://dali.cdnleiting.top/Article/details/gt2mipioloq.html

[O02] 使用线程池
来源：http://dali.haohaochexian.top/Article/details/gt2gezxehcd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hqwlvluk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.redwolf501.top/Article/details/gt2lkszbetu.html

JS:   // worker_threads 线程池
来源：http://dali.jlsjyb.cn/Article/details/gt2yxqpdinv.html

TS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gt2ndlekevy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.birdmap.top/Article/details/gt2yncfjdra.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yanxiufei.cn/Article/details/gt2fmozwzgs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bajekijp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gotoacloud.top/Article/details/gt2lcsrvxqi.html

[O03] 加锁保护共享数据
来源：http://dali.yj202588.top/Article/details/gt2miypfyfs.html

Py:   with lock: shared += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bvsjzzsw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ydzc1.top/Article/details/gt2iwwrggbt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.birdmap.top/Article/details/gt2fbvhjwjh.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gt2rylyngel.html

Java: synchronized (this) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2digqftoz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dashuyun.cn/Article/details/gt2aukbrsaa.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.fzhhl.top/Article/details/gt2nlxswovc.html

C#:   lock (gate) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gt2sqgxxjny.html

[O04] 定义异步函数并等待
来源：http://dali.yongpay.top/Article/details/gt2aupcfvxf.html

Py:   async def f():⏎    await g()
来源：http://dali.iojbl.cn/Article/details/gt2wdnnfdef.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xuetiantiany.cn/Article/details/gt2oioxhvqt.html

JS:   async function f() { await g(); }
来源：http://dali.ehwqpu.com/Article/details/gt2nbqwtmlv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gt2ncedgmac.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fengsongda.top/Article/details/gt2beubftqg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hnqzz.top/Article/details/gt2gvsqdtqc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuetiantiany.cn/Article/details/gt2dfrougsx.html

C#:   async Task F() { await G(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2cnykpbay.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuetiantiany.cn/Article/details/gt2uncxbtwk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hnqhlgld.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aizwys.cn/Article/details/gt2orgeyjfd.html

JS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gt2xbfnotdj.html

TS:   await Promise.all(tasks)
来源：http://dali.cdnleiting.top/Article/details/gt2fxlhgqug.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xziqi.cn/Article/details/gt2hoktxopq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jiagoushi.top/Article/details/gt2yhwvpfno.html

Ruby: threads.map(&:join)
来源：http://dali.c1oappe.top/Article/details/gt2llhevrwp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.mhx1999.top/Article/details/gt2huskcven.html

[O06] 使用进程池
来源：http://dali.havefunace.top/Article/details/gt2scahufxj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sxryk.cn/Article/details/gt2uwupwnlz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.aibaodan.cn/Article/details/gt2llxgcaip.html

JS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gt2jjsjbhop.html

TS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gt2sldxcaqz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj202588.top/Article/details/gt2phcurngr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.andypj.xyz/Article/details/gt2moeabatr.html

Ruby: // fork 块
来源：http://dali.jiagoushi.top/Article/details/gt2ycktjbwe.html

C#:   Parallel.For
来源：http://dali.birdmap.top/Article/details/gt2ftfcevjm.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zvbklznq.html

P. 常用工具函数
来源：http://dali.gotoacloud.top/Article/details/gt2xxwqyhcu.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2aqqwqiye.html

[P01] 生成 UUID
来源：http://dali.zycfv.cn/Article/details/gt2mehgdcoz.html

Py:   str(uuid.uuid4())
来源：http://dali.nwbrower.top/Article/details/gt2sukigpwa.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gt2zujfmmbi.html

JS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qwhfobar.html

TS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gt2gmphgsqy.html

Java: UUID.randomUUID().toString()
来源：http://dali.yanxiufei.cn/Article/details/gt2pwpdjnfm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zycfv.cn/Article/details/gt2imgcuxml.html

Ruby: SecureRandom.uuid
来源：http://dali.yanxiufei.cn/Article/details/gt2ljlwxeii.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gogol.net.cn/Article/details/gt2fnbxzqkv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xuetiantiany.cn/Article/details/gt2ccucktnc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daxiang520.top/Article/details/gt2kgppwune.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wtikcqlb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ehwqpu.com/Article/details/gt2fpvlaufd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuanzhike.top/Article/details/gt2trcvhlmh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhixingplan.top/Article/details/gt2gpomypkp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yangfankeji.com/Article/details/gt2lheuvtjs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mypfhknt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tian-w.cn/Article/details/gt2xhkicuii.html

[P03] 生成短随机字符串
来源：http://dali.zycfv.cn/Article/details/gt2tuoqgnuh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guannengcc.top/Article/details/gt2zkmmpctu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gotoacloud.top/Article/details/gt2zkxwzrfq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uaixlkcf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tanke756.top/Article/details/gt2rcrzyftw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenlongwang.top/Article/details/gt2nyqoopyi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jqgufenzy.top/Article/details/gt2yztmzfqs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yueranfly.top/Article/details/gt2wzfaunuu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.mhx1999.top/Article/details/gt2qpguaiws.html

[P04] 求长度
来源：http://dali.nanxuanxn.top/Article/details/gt2rmuaxgnq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhengqikj.top/Article/details/gt2damjhrap.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gt2eowvqrfb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhongyouzk.top/Article/details/gt2bvdntemg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gt2ebsltpvs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.snrcjt.cn/Article/details/gt2uqzzbakp.html

Go:   len(arr);  len(m)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2inzohtse.html

Ruby: x.length;  x.size
来源：http://dali.haohaochexian.top/Article/details/gt2xnebmcnb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2psuwcddt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenjidiqi.icu/Article/details/gt2rooyyzan.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hnxiangtu.top/Article/details/gt2yetaayyh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.fzhhl.top/Article/details/gt2ycbltomp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gzhubu.top/Article/details/gt2vpjhnoev.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gt2xdgaehym.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hnxiangtu.top/Article/details/gt2rszmopps.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj202588.top/Article/details/gt2qvopuxbw.html

Ruby: a == b
来源：http://dali.jqgfzy.top/Article/details/gt2uikpqlbx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ivvv.top/Article/details/gt2cpomdwbt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tanke756.top/Article/details/gt2nkfiropn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2agjxsuny.html

PHP:  if (empty($x)) {}
来源：http://dali.sufxvd.cn/Article/details/gt2xmsfjftg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.birdmap.top/Article/details/gt2vsvpcdfm.html

TS:   if (x == null) {}
来源：http://dali.zhixingplan.top/Article/details/gt2roxatffy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gt2toaahoel.html

Go:   if x == nil {}
来源：http://dali.iojbl.cn/Article/details/gt2pnksoeil.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2afnvzznz.html

C#:   if (x is null) {}
来源：http://dali.xziqi.cn/Article/details/gt2obgfegct.html

[P07] 防抖与节流
来源：http://dali.zhixingplan.top/Article/details/gt2yjdwqayd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hnqzz.top/Article/details/gt2tymoyemr.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrqycfm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gt2eytyhpfp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gt2gxkphcri.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgfzy.top/Article/details/gt2qplvradl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jianghu66.top/Article/details/gt2egltbffz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangdashe.top/Article/details/gt2neundnqg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhiwuduotai.top/Article/details/gt2xewwxdji.html

[P08] 处理浮点精度问题
来源：http://dali.iojbl.cn/Article/details/gt2dopmeepc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.daxiang520.top/Article/details/gt2bdioenqa.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.mhx1999.top/Article/details/gt2zelrdldo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hysaishi.cn/Article/details/gt2cbpdyuad.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xitzppyj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.dashuyun.cn/Article/details/gt2dnskpdav.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nwbrower.top/Article/details/gt2fuqpzfva.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigfzy.top/Article/details/gt2vvhhxhrf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pycfn.com/Article/details/gt2typdykjo.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2ityyqlvs.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenzaomai.com/Article/details/gt2hasnqqrd.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2pslhzlcz.html

[Q01] 创建表
来源：http://dali.kuanghao11.cn/Article/details/gt2gbfyqazs.html

CREATE TABLE users (
来源：http://dali.cheryme.top/Article/details/gt2dxzbabft.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gt2spsmdnjn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenzaomai.com/Article/details/gt2ppijuaha.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hywenlv.cn/Article/details/gt2nnnbdhwz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.iojbl.cn/Article/details/gt2tdyurvss.html

);
来源：http://dali.9152youxi.cn/Article/details/gt2koqgzols.html

[Q02] 创建带外键的表
来源：http://dali.chenzaomai.com/Article/details/gt2sqovblif.html

CREATE TABLE orders (
来源：http://dali.birdmap.top/Article/details/gt2vjkzxjdx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xziqi.cn/Article/details/gt2jrikkabp.html

user_id INT NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gt2zvhszszq.html

amount DECIMAL(10, 2),
来源：http://dali.haohaochexian.top/Article/details/gt2zuniebtp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sysykeji.top/Article/details/gt2delcaraq.html

);
来源：http://dali.c1oappe.top/Article/details/gt2jobtfaeu.html

[Q03] 增加列
来源：http://dali.yj20258.top/Article/details/gt2hjoajkju.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xuetiantiany.cn/Article/details/gt2rsyjkptl.html

[Q04] 修改列类型
来源：http://dali.chenlongwang.top/Article/details/gt2virxuhdx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nwbrower.top/Article/details/gt2sgmbyqpc.html

[Q05] 重命名列
来源：http://dali.daxiang520.top/Article/details/gt2rdckeyzi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jiagoushi.top/Article/details/gt2lxztyvkv.html

[Q06] 删除列
来源：http://dali.tianlin.xyz/Article/details/gt2zdcajcmv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jlsjyb.cn/Article/details/gt2qwlhgvjk.html

[Q07] 删除表
来源：http://dali.shangyingyoupin.top/Article/details/gt2mspfbcos.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ivvv.top/Article/details/gt2tewmrfxh.html

[Q08] 创建普通索引
来源：http://dali.zhixingplan.top/Article/details/gt2wgbkipvp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gt2ksukjixk.html

[Q09] 创建唯一索引
来源：http://dali.hysaishi.cn/Article/details/gt2jtcxwnxk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shuidangran.top/Article/details/gt2abdydgyx.html

[Q10] 插入单行
来源：http://dali.fzhhl.top/Article/details/gt2exyyhpir.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gt2zqllqisf.html

[Q11] 一次插入多行
来源：http://dali.pycfn.com/Article/details/gt2dewfyzck.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xylfe.cn/Article/details/gt2ivvomule.html

[Q12] 插入后取自增 ID
来源：http://dali.hfpthk.cn/Article/details/gt2spftoflo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shzxlz.cn/Article/details/gt2yqybufjr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hfpthk.cn/Article/details/gt2vqpziqsg.html

[Q13] 忽略重复插入
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ftnljyjc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhengqikj.top/Article/details/gt2rphsuchz.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuxming.cn/Article/details/gt2olvddppw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.0kj1m.cn/Article/details/gt2jbfjjysc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tianlin.xyz/Article/details/gt2brpcbopr.html

[Q15] 查询全部
来源：http://dali.tianlin.xyz/Article/details/gt2vkiexxwp.html

SELECT * FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2ydcccago.html

[Q16] 查询指定列
来源：http://dali.wangshuangyany.cn/Article/details/gt2zjanzwxg.html

SELECT id, name FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2nnvbvvez.html

[Q17] 条件查询
来源：http://dali.fengsongda.top/Article/details/gt2ofgcbmtn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zycfv.cn/Article/details/gt2gosnkzxg.html

[Q18] 模糊匹配
来源：http://dali.ybcxt.top/Article/details/gt2fvorqwov.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uyxojgoo.html

[Q19] 范围查询
来源：http://dali.chenzaomai.com/Article/details/gt2pdgcncmo.html


<!-- 参考信息 -->