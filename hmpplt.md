代发 wailian999

[M08] 获取系统与运行时信息
来源：http://dali.shangyingyoupin.top/Article/details/gt2zzkwalbm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tian-w.cn/Article/details/gt2nljjvdol.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.meibo888.top/Article/details/gt2cbfcbnbh.html

JS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gt2sobldool.html

TS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gt2gircwfor.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zdqjudy.top/Article/details/gt2ltpcrzvf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jawzjrfu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fengsongda.top/Article/details/gt2ekyuxejs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuanzhike.top/Article/details/gt2ksomuine.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2eiujkwnr.html

N. 数据结构与算法
来源：http://dali.jyoumei.cn/Article/details/gt2efbwndje.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2bvsughyz.html

[N01] 二分查找（有序数组）
来源：http://dali.wangdashe.top/Article/details/gt2uecsawua.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2jfjlbzqq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuanzx.com/Article/details/gt2ybmpxhnn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cdnleiting.top/Article/details/gt2utgphquz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gt2tfrxnnns.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2lzdmsvbl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2bqggemud.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hfpthk.cn/Article/details/gt2tmnnqjsb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gt2ffmtaepi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ydzc1.top/Article/details/gt2jbeokyht.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gt2rmhkvnpo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dotytkkx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gt2aakxiwvo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gt2tjzvidim.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yangfankeji.com/Article/details/gt2kjmzrupf.html

Go:   slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gt2ejkdfzsx.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gt2peazdjvw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daria6918.cn/Article/details/gt2nyszldlk.html

[N03] 快速排序（分治示例）
来源：http://dali.cdnleiting.top/Article/details/gt2bwpfxtni.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gzhubu.top/Article/details/gt2arvfnkcz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zdqjudy.top/Article/details/gt2tnoesjmw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gt2apahuzyl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gt2wnbolmwp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenjidiqi.icu/Article/details/gt2zrcfsndj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hnqzz.top/Article/details/gt2gjuibjjj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dianchejie.cn/Article/details/gt2hcftinhh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dashuyun.cn/Article/details/gt2gkwifxbr.html

[N04] 斐波那契数列
来源：http://dali.fengsongda.top/Article/details/gt2fielldex.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gt2kctftjue.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gt2ummobfcn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gt2lbmdrznx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gt2kmpjlbuv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.redwolf501.top/Article/details/gt2loyolxax.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnxiangtu.top/Article/details/gt2olpzvhyw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hywenlv.cn/Article/details/gt2lcqkphcy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gt2bkuccood.html

[N05] 最大公约数
来源：http://dali.ydzc1.top/Article/details/gt2mbeagjsl.html

Py:   math.gcd(a, b)
来源：http://dali.guannengcc.top/Article/details/gt2eimnvgnu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jlsjyb.cn/Article/details/gt2gnqfdcxc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gt2wjymzkhi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gt2ohfunsax.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yvedp.cn/Article/details/gt2ogzwnhha.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.svipenyu.cn/Article/details/gt2ufabzdqw.html

Ruby: a.gcd(b)
来源：http://dali.bjfxy.top/Article/details/gt2mgjxaqcv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ydzc1.top/Article/details/gt2ukycewpg.html

[N06] 判断回文字符串
来源：http://dali.jyoumei.cn/Article/details/gt2dyoznkam.html

Py:   s == s[::-1]
来源：http://dali.meibo888.top/Article/details/gt2orbemrkl.html

PHP:  $s === strrev($s);
来源：http://dali.gotoacloud.top/Article/details/gt2rbmwoeuw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gt2aqlmfjws.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gt2xmjbgzop.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jlsjyb.cn/Article/details/gt2siuamtbm.html

Go:   // 双指针从两端比较
来源：http://dali.shangyingyoupin.top/Article/details/gt2tniqnzgq.html

Ruby: s == s.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gt2avmbisst.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gt2sjpmnlnb.html

[N07] 两数之和（返回下标）
来源：http://dali.vqdsnc.cn/Article/details/gt2knnlcofy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigufen.top/Article/details/gt2fkxrgnjd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.snrcjt.cn/Article/details/gt2mcleceek.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgufenzy.top/Article/details/gt2pxmumkzt.html

TS:   // 手写 Map<string, number>
来源：http://dali.havefunace.top/Article/details/gt2zoqydszr.html

Java: // 手写 HashMap
来源：http://dali.pycfn.com/Article/details/gt2fkpzdkkc.html

Go:   // 手写 map[int]int
来源：http://dali.zhengqikj.top/Article/details/gt2xhggkpon.html

Ruby: // 手写 Hash
来源：http://dali.0kj1m.cn/Article/details/gt2qmbzxlup.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shzxlz.cn/Article/details/gt2onfwfvbu.html

[N08] 生成全排列
来源：http://dali.zhiwuduotai.top/Article/details/gt2saqghxkn.html

Py:   itertools.permutations(arr)
来源：http://dali.daxiang520.top/Article/details/gt2vxujwqdw.html

PHP:  // 手写递归交换
来源：http://dali.yonumen.top/Article/details/gt2ltajbzji.html

JS:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gt2kagzrqwp.html

TS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2vtsalkgn.html

Java: // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2oohpvqcd.html

Go:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gt2xuwduilg.html

Ruby: arr.permutation.to_a
来源：http://dali.snrcjt.cn/Article/details/gt2kzlilkxb.html

C#:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2nmaxoayv.html

[N09] 栈与队列
来源：http://dali.jiagoushi.top/Article/details/gt2mtexsxkd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gogol.net.cn/Article/details/gt2dxtmtdaj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2wovrksup.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sysykeji.top/Article/details/gt2gmcugyva.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hblrbpuc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hywenlv.cn/Article/details/gt2ntpyayba.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.quarkkingdee.top/Article/details/gt2kwicqtks.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.birdmap.top/Article/details/gt2vglnrbqp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.mhx1999.top/Article/details/gt2nhapizhc.html

[N10] 链表节点定义
来源：http://dali.xinyue.icu/Article/details/gt2daoxgjtf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fzhhl.top/Article/details/gt2tuabktrs.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jlsjyb.cn/Article/details/gt2owenfbfn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.bjfxy.top/Article/details/gt2qhkgxloz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.quarkkingdee.top/Article/details/gt2giravpog.html

Java: class Node { int v; Node next; }
来源：http://dali.316326.xyz/Article/details/gt2onhebgxe.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhixingplan.top/Article/details/gt2zplemtpr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gotoacloud.top/Article/details/gt2yooguima.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xziqi.cn/Article/details/gt2qrcilujf.html

[N11] 二叉树中序遍历
来源：http://dali.sweek.top/Article/details/gt2icehblkg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.316326.xyz/Article/details/gt2qiloognk.html

PHP:  // 手写递归函数
来源：http://dali.birdmap.top/Article/details/gt2psvtfjss.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gt2swkjlzmc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gt2fcgrsaeu.html

Java: // 手写递归
来源：http://dali.yongpay.top/Article/details/gt2smovfory.html

Go:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gt2pjdhdvmj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.c1oappe.top/Article/details/gt2cldyohlo.html

C#:   // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gt2qwhmbhmf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj202588.top/Article/details/gt2mzuzmrlc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tianlin.xyz/Article/details/gt2gbwtylhb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ivvv.top/Article/details/gt2cybehmku.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gt2xiuzkyca.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gt2giagwrgv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenzaomai.com/Article/details/gt2xfgaxqrc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yanxiufei.cn/Article/details/gt2tzbtjuzw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nwbrower.top/Article/details/gt2wfrypgtn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gt2hqwlxddz.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2nscufini.html

O. 并发与异步
来源：http://dali.smart0.xyz/Article/details/gt2kwsluoul.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2wwzxnoho.html

[O01] 启动一个线程
来源：http://dali.ybcxt.top/Article/details/gt2wiuyufsh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.iojbl.cn/Article/details/gt2gcoxbhig.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tanke756.top/Article/details/gt2xiffzgxb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xylfe.cn/Article/details/gt2mrsxjwce.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gt2fuyoenxk.html

Java: new Thread(() -> f()).start()
来源：http://dali.xziqi.cn/Article/details/gt2qkfgkhvu.html

Go:   go f()
来源：http://dali.fzhhl.top/Article/details/gt2jccrxcev.html

Ruby: Thread.new { f }
来源：http://dali.guowangkeji.top/Article/details/gt2qnlpdqye.html

C#:   Task.Run(() => F());
来源：http://dali.guannengcc.top/Article/details/gt2okluxysv.html

[O02] 使用线程池
来源：http://dali.dianchejie.cn/Article/details/gt2jvmrzavo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhixingplan.top/Article/details/gt2aemjcnri.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hnqzz.top/Article/details/gt2ttyepxfr.html

JS:   // worker_threads 线程池
来源：http://dali.vqdsnc.cn/Article/details/gt2mkzcvcsu.html

TS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gt2vfclelhx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zwqkecix.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yvedp.cn/Article/details/gt2smwsiblz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shzxlz.cn/Article/details/gt2xmsblmxu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2srohsoiz.html

[O03] 加锁保护共享数据
来源：http://dali.pengpengdd.cyou/Article/details/gt2cvrymcuv.html

Py:   with lock: shared += 1
来源：http://dali.yj20258.top/Article/details/gt2kmlpsijy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cheryme.top/Article/details/gt2ftbikzud.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnxiangtu.top/Article/details/gt2aidwgfzx.html

TS:   // 同 JS
来源：http://dali.wangshuangyany.cn/Article/details/gt2svpnzzhn.html

Java: synchronized (this) { shared++; }
来源：http://dali.yonumen.top/Article/details/gt2xzvtnhpo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.c1oappe.top/Article/details/gt2zyqhttlk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhongyouzk.top/Article/details/gt2wknyvxvv.html

C#:   lock (gate) { shared++; }
来源：http://dali.aibaodan.cn/Article/details/gt2enfwpapm.html

[O04] 定义异步函数并等待
来源：http://dali.yj202588.top/Article/details/gt2evnkfzid.html

Py:   async def f():⏎    await g()
来源：http://dali.aizwys.cn/Article/details/gt2xevhraza.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dianchejie.cn/Article/details/gt2dfvuirie.html

JS:   async function f() { await g(); }
来源：http://dali.hywenlv.cn/Article/details/gt2gipkwawh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.bjfxy.top/Article/details/gt2vrnjpxui.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gzhubu.top/Article/details/gt2fvceomzm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hysaishi.cn/Article/details/gt2xxfwxqmq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cqqwz.cn/Article/details/gt2rbiwztpu.html

C#:   async Task F() { await G(); }
来源：http://dali.redwolf501.top/Article/details/gt2enwarods.html

[O05] 并发执行并等待全部完成
来源：http://dali.9152youxi.cn/Article/details/gt2hnxqghzl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zdqjudy.top/Article/details/gt2uvqjncue.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj202588.top/Article/details/gt2juxwmnvu.html

JS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gt2vtgtjmbn.html

TS:   await Promise.all(tasks)
来源：http://dali.yvedp.cn/Article/details/gt2qmtsdtxd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jqgufenzy.top/Article/details/gt2qwkghdsi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangshuangyany.cn/Article/details/gt2azfcxfcx.html

Ruby: threads.map(&:join)
来源：http://dali.sweek.top/Article/details/gt2jmotszvh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guannengcc.top/Article/details/gt2nedrrhhh.html

[O06] 使用进程池
来源：http://dali.hongshengwenyu.top/Article/details/gt2ghcvmzbq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.feifeiyinyue.top/Article/details/gt2fpofevxj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pycfn.com/Article/details/gt2mnchkyfy.html

JS:   // child_process / cluster 模块
来源：http://dali.shangyingyoupin.top/Article/details/gt2fsymyfei.html

TS:   // child_process / cluster 模块
来源：http://dali.yonumen.top/Article/details/gt2xebpjhme.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aizwys.cn/Article/details/gt2yuvmualy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sxryk.cn/Article/details/gt2tmlhjsjq.html

Ruby: // fork 块
来源：http://dali.svipenyu.cn/Article/details/gt2bkrhapjo.html

C#:   Parallel.For
来源：http://dali.hywenlv.cn/Article/details/gt2gqznrsim.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2goouqlnc.html

P. 常用工具函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2thcpdxrm.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2pqycwxqs.html

[P01] 生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gt2ywvsfrfd.html

Py:   str(uuid.uuid4())
来源：http://dali.wangshuangyany.cn/Article/details/gt2jnhbzyea.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yuxming.cn/Article/details/gt2fujwsihx.html

JS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gt2eoiyvjra.html

TS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gt2mpuhcamg.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhengqikj.top/Article/details/gt2pagrausd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sysykeji.top/Article/details/gt2tkznweua.html

Ruby: SecureRandom.uuid
来源：http://dali.daxiang520.top/Article/details/gt2fugyszya.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jrhvhiao.html

[P02] MD5 / SHA256 摘要
来源：http://dali.guannengcc.top/Article/details/gt2jzqlhijw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ivvv.top/Article/details/gt2nfafuvbp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eflfeejv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pengpengdd.cyou/Article/details/gt2ebxbqscx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gogol.net.cn/Article/details/gt2gxcayros.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.c1oappe.top/Article/details/gt2pkqmgxbf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shangyingyoupin.top/Article/details/gt2qufckhyv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fengsongda.top/Article/details/gt2jxppnzog.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhengqikj.top/Article/details/gt2sglrjebw.html

[P03] 生成短随机字符串
来源：http://dali.smart0.xyz/Article/details/gt2gxhvdvyz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shzxlz.cn/Article/details/gt2mxtddeey.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.pengpengdd.cyou/Article/details/gt2dnjnithz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2tnhyonmf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.9152youxi.cn/Article/details/gt2kkhoacxj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tanke756.top/Article/details/gt2unudvagz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sweek.top/Article/details/gt2yzltrvrr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.vqdsnc.cn/Article/details/gt2xdkfthps.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.vqdsnc.cn/Article/details/gt2whhwrykd.html

[P04] 求长度
来源：http://dali.zdqjudy.top/Article/details/gt2tyvirzai.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ydzc1.top/Article/details/gt2irglyvaj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2xylmunvq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.snrcjt.cn/Article/details/gt2qjuemlah.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gt2tlccnrex.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ebsywnff.html

Go:   len(arr);  len(m)
来源：http://dali.mhx1999.top/Article/details/gt2zbzrdhny.html

Ruby: x.length;  x.size
来源：http://dali.zdqjudy.top/Article/details/gt2wufmmqgm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.birdmap.top/Article/details/gt2rfttcstw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tian-w.cn/Article/details/gt2gzxwidce.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cucudq.cn/Article/details/gt2rmjwuwmn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jianghu66.top/Article/details/gt2xfpcdfxw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenzaomai.com/Article/details/gt2mrzjgqvx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ppjwa.cn/Article/details/gt2tqubtjul.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gaohongyu789.top/Article/details/gt2dbqlvzah.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhixingplan.top/Article/details/gt2gtqupccs.html

Ruby: a == b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ermhrqkl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.c1oappe.top/Article/details/gt2ranzehmg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuanzhike.top/Article/details/gt2woabpyfc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.havefunace.top/Article/details/gt2rqpgsdki.html

PHP:  if (empty($x)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gqielacz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgufenzy.top/Article/details/gt2igwjixco.html

TS:   if (x == null) {}
来源：http://dali.aizwys.cn/Article/details/gt2qfjjmeay.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ydzc1.top/Article/details/gt2zepswqzm.html

Go:   if x == nil {}
来源：http://dali.316326.xyz/Article/details/gt2eznmmtha.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.svipenyu.cn/Article/details/gt2guizpqvx.html

C#:   if (x is null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2usrndrmw.html

[P07] 防抖与节流
来源：http://dali.gzhubu.top/Article/details/gt2vpuuavue.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hysaishi.cn/Article/details/gt2spzncnpf.html

PHP:  // 手写时间戳比较
来源：http://dali.zhixingplan.top/Article/details/gt2dwbykkbr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gt2libczjok.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gt2xlvyfpqg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258.top/Article/details/gt2yphlwzhw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pqakmsni.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sxryk.cn/Article/details/gt2rmjetukn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yangfankeji.com/Article/details/gt2xcdvzaxz.html

[P08] 处理浮点精度问题
来源：http://dali.vqdsnc.cn/Article/details/gt2jdjeejdj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.snrcjt.cn/Article/details/gt2gbcfjgax.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.svipenyu.cn/Article/details/gt2sltbnelg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yanxiufei.cn/Article/details/gt2jihbhhqg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhixingplan.top/Article/details/gt2wisugzjl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zdqjudy.top/Article/details/gt2jiiqgjxt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigufen.top/Article/details/gt2yqjodexo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.mhx1999.top/Article/details/gt2ltuaeqjh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sxryk.cn/Article/details/gt2faqmotud.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2uxhsevlj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuanzhike.top/Article/details/gt2edzwlrle.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2watwkvir.html

[Q01] 创建表
来源：http://dali.nwbrower.top/Article/details/gt2islaxmql.html

CREATE TABLE users (
来源：http://dali.havefunace.top/Article/details/gt2jkmhmqly.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sblhadyj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gt2uonozatw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aizwys.cn/Article/details/gt2fuulinnm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yanxiufei.cn/Article/details/gt2xadunhlx.html

);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vhiykmto.html

[Q02] 创建带外键的表
来源：http://dali.hfpthk.cn/Article/details/gt2tlbnygbx.html

CREATE TABLE orders (
来源：http://dali.xziqi.cn/Article/details/gt2buuxdnsn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ppjwa.cn/Article/details/gt2osgicmnh.html

user_id INT NOT NULL,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gjxafxyp.html

amount DECIMAL(10, 2),
来源：http://dali.zhixingplan.top/Article/details/gt2tpccqbho.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shzxlz.cn/Article/details/gt2eyybfkng.html

);
来源：http://dali.birdmap.top/Article/details/gt2anxugzxd.html

[Q03] 增加列
来源：http://dali.zhixingplan.top/Article/details/gt2vxadkugs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.fzhhl.top/Article/details/gt2mbzdroga.html

[Q04] 修改列类型
来源：http://dali.dashuyun.cn/Article/details/gt2whedukoj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gt2jozjvjyd.html

[Q05] 重命名列
来源：http://dali.xuetiantiany.cn/Article/details/gt2hsienhba.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.c1oappe.top/Article/details/gt2gcajedcg.html

[Q06] 删除列
来源：http://dali.yangfankeji.com/Article/details/gt2tbkowwlv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zddsakra.html

[Q07] 删除表
来源：http://dali.ivvv.top/Article/details/gt2vxxzfwwc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yangfankeji.com/Article/details/gt2flcuaizz.html

[Q08] 创建普通索引
来源：http://dali.kuanghao11.cn/Article/details/gt2rwqssimo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nwbrower.top/Article/details/gt2pvvfqlbe.html

[Q09] 创建唯一索引
来源：http://dali.hnxiangtu.top/Article/details/gt2tllpmwrd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gt2ruvhukag.html

[Q10] 插入单行
来源：http://dali.sufxvd.cn/Article/details/gt2rraykanm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigufen.top/Article/details/gt2tamlhabq.html

[Q11] 一次插入多行
来源：http://dali.smart0.xyz/Article/details/gt2uymhjflb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cheryme.top/Article/details/gt2fwreumua.html

[Q12] 插入后取自增 ID
来源：http://dali.ybcxt.top/Article/details/gt2kgidwjws.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.andypj.xyz/Article/details/gt2uqborcxy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.guannengcc.top/Article/details/gt2nwdgytde.html

[Q13] 忽略重复插入
来源：http://dali.hywenlv.cn/Article/details/gt2xwkecpss.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hysaishi.cn/Article/details/gt2rqptskmv.html

[Q14] 存在则更新（upsert）
来源：http://dali.mhx1999.top/Article/details/gt2tdciactl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xziqi.cn/Article/details/gt2jkxluflv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvjssong.html

[Q15] 查询全部
来源：http://dali.guannengcc.top/Article/details/gt2kwvsavht.html

SELECT * FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2rwzvnxvd.html

[Q16] 查询指定列
来源：http://dali.jqgfzy.top/Article/details/gt2terpauko.html

SELECT id, name FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2vajxpoyk.html

[Q17] 条件查询
来源：http://dali.ybcxt.top/Article/details/gt2wfhrknef.html


<!-- 参考信息 -->