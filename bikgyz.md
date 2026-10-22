代发 wailian999

TS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gt2bpotavcg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.kuanghao11.cn/Article/details/gt2ateddfbq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cheryme.top/Article/details/gt2zrfrpcnj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenlongwang.top/Article/details/gt2ecxwpzum.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhongyouzk.top/Article/details/gt2ktznwreu.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2bpuiriui.html

N. 数据结构与算法
来源：http://dali.dianchejie.cn/Article/details/gt2cnahurko.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2idxmdlgg.html

[N01] 二分查找（有序数组）
来源：http://dali.hysaishi.cn/Article/details/gt2crtiwaqx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tian-w.cn/Article/details/gt2oxtjtpgs.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daxiang520.top/Article/details/gt2yazmaozr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gt2rqvlnzlz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guowangkeji.top/Article/details/gt2rtgphzgg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2xxciqnas.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gt2ounvfgzf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bdgxdmgh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2ejhrhubv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.meibo888.top/Article/details/gt2yoviniik.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gt2xtaxlvaj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fzhhl.top/Article/details/gt2gnompiaz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gt2lbcsehpb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gt2ixwvqqtw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daxiang520.top/Article/details/gt2gralupwj.html

Go:   slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gt2jtyqjcad.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gt2pzounfmi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hfpthk.cn/Article/details/gt2iepdojcb.html

[N03] 快速排序（分治示例）
来源：http://dali.tanke756.top/Article/details/gt2nvcscrql.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cucudq.cn/Article/details/gt2iwxoxdls.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xziqi.cn/Article/details/gt2zoxfhfdr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gt2kzsofrox.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gt2xusgosjl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jianghu66.top/Article/details/gt2ntisgnmt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yueranfly.top/Article/details/gt2svrmqdvg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tianlin.xyz/Article/details/gt2tfdhvbfi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yanxiufei.cn/Article/details/gt2qjqgikth.html

[N04] 斐波那契数列
来源：http://dali.daxiang520.top/Article/details/gt2mjbzkocr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gt2rjxvdzye.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gt2cnljtfbg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gt2ofiitxlz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gt2ggdyosya.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daxiang520.top/Article/details/gt2fziugjaf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xziqi.cn/Article/details/gt2abyzuyuy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gt2ftpylrtx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2yseiuczk.html

[N05] 最大公约数
来源：http://dali.sweek.top/Article/details/gt2nxgynhqu.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2shbvldoe.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.snrcjt.cn/Article/details/gt2qnejphfo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gt2jjxxrtto.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gt2tommhjot.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.smart0.xyz/Article/details/gt2mhbxssql.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xinyue.icu/Article/details/gt2okuuiabk.html

Ruby: a.gcd(b)
来源：http://dali.hfpthk.cn/Article/details/gt2adlknnwi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hnqzz.top/Article/details/gt2rjjsdrpq.html

[N06] 判断回文字符串
来源：http://dali.nwbrower.top/Article/details/gt2fclkvxke.html

Py:   s == s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2fjigopzm.html

PHP:  $s === strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2czveaznf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gt2njovoqwd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gt2crirmcxz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhoulong.xyz/Article/details/gt2cpsnceqr.html

Go:   // 双指针从两端比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2gfujbhev.html

Ruby: s == s.reverse
来源：http://dali.yj202588.top/Article/details/gt2vnmyjrkm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gt2tiezbtyj.html

[N07] 两数之和（返回下标）
来源：http://dali.hammf.cn/Article/details/gt2hgdydknp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hongshengwenyu.top/Article/details/gt2zardltar.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.chenlongwang.top/Article/details/gt2kobyvecl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sweek.top/Article/details/gt2kgvkmvpq.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinqigufen.top/Article/details/gt2kvrdgdfi.html

Java: // 手写 HashMap
来源：http://dali.zhiwuduotai.top/Article/details/gt2pntxhaan.html

Go:   // 手写 map[int]int
来源：http://dali.yuxming.cn/Article/details/gt2cmjypolg.html

Ruby: // 手写 Hash
来源：http://dali.havefunace.top/Article/details/gt2frdzlfvz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ydzc1.top/Article/details/gt2hchgwcwb.html

[N08] 生成全排列
来源：http://dali.hysaishi.cn/Article/details/gt2pypnhkkl.html

Py:   itertools.permutations(arr)
来源：http://dali.yj20258888.top/Article/details/gt2ugekvtqs.html

PHP:  // 手写递归交换
来源：http://dali.hnxiangtu.top/Article/details/gt2eupjdrpy.html

JS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gt2hccbkfvn.html

TS:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gt2gytujnfr.html

Java: // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gt2spxuokul.html

Go:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gt2reajzlkd.html

Ruby: arr.permutation.to_a
来源：http://dali.pycfn.com/Article/details/gt2rirjjeyg.html

C#:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gt2ajytxmyn.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyjblpy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.iojbl.cn/Article/details/gt2vwuegcfw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.guannengcc.top/Article/details/gt2xqdapoio.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gt2xjyxznij.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhengqikj.top/Article/details/gt2uzxxhxev.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sufxvd.cn/Article/details/gt2ytyfbrei.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.kuanghao11.cn/Article/details/gt2jdmyagoz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gt2nnoqbfmh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.quarkkingdee.top/Article/details/gt2jkiohhkm.html

[N10] 链表节点定义
来源：http://dali.hnxiangtu.top/Article/details/gt2pdoozfhp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hnxiangtu.top/Article/details/gt2gbsmdsum.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bbgwqhmy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cashguo.top/Article/details/gt2drbuhtxz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigufen.top/Article/details/gt2fryydkov.html

Java: class Node { int v; Node next; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2etcbqcrm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hnqzz.top/Article/details/gt2oojevbdy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yueranfly.top/Article/details/gt2gdgykdlx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.snrcjt.cn/Article/details/gt2mhegcvmx.html

[N11] 二叉树中序遍历
来源：http://dali.jyoumei.cn/Article/details/gt2hafvlwlf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2viyklnlm.html

PHP:  // 手写递归函数
来源：http://dali.sweek.top/Article/details/gt2qmvdwynb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.mhx1999.top/Article/details/gt2prcrpkvk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gt2skbwurjy.html

Java: // 手写递归
来源：http://dali.daria6918.cn/Article/details/gt2nwgpomqt.html

Go:   // 手写递归
来源：http://dali.redwolf501.top/Article/details/gt2flmybzta.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuxming.cn/Article/details/gt2duulbuia.html

C#:   // 手写递归
来源：http://dali.tian-w.cn/Article/details/gt2cgyuciel.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jyoumei.cn/Article/details/gt2dtivmqja.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xuanzx.com/Article/details/gt2jxdvgebo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.feifeiyinyue.top/Article/details/gt2kepmcqij.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gt2itrmcjae.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gzhubu.top/Article/details/gt2glnbcnia.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yongpay.top/Article/details/gt2ocbcbkao.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zzxgpyyx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fzhhl.top/Article/details/gt2hmgwghdo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jlsjyb.cn/Article/details/gt2ktspjjbz.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2hcfmnxok.html

O. 并发与异步
来源：http://dali.aibaodan.cn/Article/details/gt2ahtnzlce.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rfkawrkc.html

[O01] 启动一个线程
来源：http://dali.birdmap.top/Article/details/gt2hjqxibyl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cdnleiting.top/Article/details/gt2erluyrja.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2shhxsbed.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.dianchejie.cn/Article/details/gt2rbxjxrvx.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gt2zzaydcgq.html

Java: new Thread(() -> f()).start()
来源：http://dali.tian-w.cn/Article/details/gt2swcfdvqq.html

Go:   go f()
来源：http://dali.tianlin.xyz/Article/details/gt2yoyehytr.html

Ruby: Thread.new { f }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjepqaqh.html

C#:   Task.Run(() => F());
来源：http://dali.vqdsnc.cn/Article/details/gt2fprkvftk.html

[O02] 使用线程池
来源：http://dali.andypj.xyz/Article/details/gt2fuspompy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xuanzx.com/Article/details/gt2fawqsjsk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhengqikj.top/Article/details/gt2jkgspsan.html

JS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gt2xyavbair.html

TS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gt2savbuhxh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daxiang520.top/Article/details/gt2qrfaxoty.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daxiang520.top/Article/details/gt2ubxdwdib.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hnqzz.top/Article/details/gt2fsibcauu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tian-w.cn/Article/details/gt2pjlpyajo.html

[O03] 加锁保护共享数据
来源：http://dali.jqgfzy.top/Article/details/gt2mquvqqxf.html

Py:   with lock: shared += 1
来源：http://dali.hnxiangtu.top/Article/details/gt2fzgjdmjx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cashguo.top/Article/details/gt2gsvqexxs.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.daxiang520.top/Article/details/gt2hrkphkwn.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gt2awsodixv.html

Java: synchronized (this) { shared++; }
来源：http://dali.cqqwz.cn/Article/details/gt2dtjzrjyf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ppjwa.cn/Article/details/gt2imtjdtbd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hammf.cn/Article/details/gt2asnkuwoy.html

C#:   lock (gate) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2noulfytl.html

[O04] 定义异步函数并等待
来源：http://dali.ybcxt.top/Article/details/gt2azialbrr.html

Py:   async def f():⏎    await g()
来源：http://dali.guowangkeji.top/Article/details/gt2tkkqkcre.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.kuanghao11.cn/Article/details/gt2gajwwzfl.html

JS:   async function f() { await g(); }
来源：http://dali.andypj.xyz/Article/details/gt2dwazaeze.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.guannengcc.top/Article/details/gt2xluysikf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xziqi.cn/Article/details/gt2wujpizoo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ppjwa.cn/Article/details/gt2sqmxtelz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhiwuduotai.top/Article/details/gt2otgnrooo.html

C#:   async Task F() { await G(); }
来源：http://dali.yj202588.top/Article/details/gt2yklxikak.html

[O05] 并发执行并等待全部完成
来源：http://dali.jiagoushi.top/Article/details/gt2fepgzvop.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wwcnzpyq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gotoacloud.top/Article/details/gt2sutvksyb.html

JS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gt2wzrpeomb.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gt2gailxoik.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhengqikj.top/Article/details/gt2wnkccgmm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yangfankeji.com/Article/details/gt2hmguhkan.html

Ruby: threads.map(&:join)
来源：http://dali.hfpthk.cn/Article/details/gt2psymrale.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhengqikj.top/Article/details/gt2emomqtwa.html

[O06] 使用进程池
来源：http://dali.chenzaomai.com/Article/details/gt2ygspnxtv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jyoumei.cn/Article/details/gt2tgaxpomp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.bjfxy.top/Article/details/gt2pjbybzbq.html

JS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gt2ihzvupmt.html

TS:   // child_process / cluster 模块
来源：http://dali.hnxiangtu.top/Article/details/gt2dqpieeci.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuanzhike.top/Article/details/gt2clsgrsuc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.wangshuangyany.cn/Article/details/gt2cstpzgnk.html

Ruby: // fork 块
来源：http://dali.zhiwuduotai.top/Article/details/gt2mjdiwiff.html

C#:   Parallel.For
来源：http://dali.haohaochexian.top/Article/details/gt2ahkhkigc.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2tktnktos.html

P. 常用工具函数
来源：http://dali.jlsjyb.cn/Article/details/gt2nxywwslq.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kiwgbram.html

[P01] 生成 UUID
来源：http://dali.bjfxy.top/Article/details/gt2nqlbaymk.html

Py:   str(uuid.uuid4())
来源：http://dali.smart0.xyz/Article/details/gt2banrjdfa.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zdqjudy.top/Article/details/gt2lqddaqpk.html

JS:   crypto.randomUUID()
来源：http://dali.tianlin.xyz/Article/details/gt2ycyfkkkn.html

TS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gt2ixcfzvyl.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhixingplan.top/Article/details/gt2xefjgqxd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuxming.cn/Article/details/gt2vljiajoa.html

Ruby: SecureRandom.uuid
来源：http://dali.tianlin.xyz/Article/details/gt2apvkwkma.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fffmiefe.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gotoacloud.top/Article/details/gt2tfflqmyy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangshuangyany.cn/Article/details/gt2zefwtevh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sweek.top/Article/details/gt2hvkhlqbx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhengqikj.top/Article/details/gt2ktwedkfi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hammf.cn/Article/details/gt2syhezuvf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gzhubu.top/Article/details/gt2ijnjtzkg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yonumen.top/Article/details/gt2rlwbxbrm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ghmvgzur.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xinyue.icu/Article/details/gt2arjpzrgs.html

[P03] 生成短随机字符串
来源：http://dali.xinyue.icu/Article/details/gt2tsiilblv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.0kj1m.cn/Article/details/gt2uexvadyh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnqzz.top/Article/details/gt2zadeeepr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ctxsgipg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gt2bxupspwk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yongpay.top/Article/details/gt2iuhfuwie.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hywenlv.cn/Article/details/gt2duacbcya.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.0kj1m.cn/Article/details/gt2nfqyitnt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yangfankeji.com/Article/details/gt2ywdgcrfx.html

[P04] 求长度
来源：http://dali.aizwys.cn/Article/details/gt2cwrxnlwp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.guowangkeji.top/Article/details/gt2nwnrosub.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gt2fwfklror.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xziqi.cn/Article/details/gt2djkqxopm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hongshengwenyu.top/Article/details/gt2ntzdspuu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.svipenyu.cn/Article/details/gt2vydmuxgm.html

Go:   len(arr);  len(m)
来源：http://dali.sweek.top/Article/details/gt2skifpoxj.html

Ruby: x.length;  x.size
来源：http://dali.sweek.top/Article/details/gt2bvnnzrox.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jiagoushi.top/Article/details/gt2vejujnro.html

[P05] 判断两个对象内容是否相等
来源：http://dali.birdmap.top/Article/details/gt2bssrrqyl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jyoumei.cn/Article/details/gt2azdheeeu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hnxiangtu.top/Article/details/gt2rlktpaph.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cheryme.top/Article/details/gt2qijoqipr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shzxlz.cn/Article/details/gt2ngffynsn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxxasra.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ppjwa.cn/Article/details/gt2qlrmlpuy.html

Ruby: a == b
来源：http://dali.yj202588.top/Article/details/gt2xbesujnz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gzhubu.top/Article/details/gt2lsflpbma.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.bjfxy.top/Article/details/gt2gwdedlgc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.daria6918.cn/Article/details/gt2xgzsasfm.html

PHP:  if (empty($x)) {}
来源：http://dali.hfpthk.cn/Article/details/gt2rosmdsxv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhengqikj.top/Article/details/gt2bajjixmz.html

TS:   if (x == null) {}
来源：http://dali.zycfv.cn/Article/details/gt2fcsczpok.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2aqmlhsrv.html

Go:   if x == nil {}
来源：http://dali.jianghu66.top/Article/details/gt2qwiancqn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tianlin.xyz/Article/details/gt2jygtydpv.html

C#:   if (x is null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rhhvhyar.html

[P07] 防抖与节流
来源：http://dali.birdmap.top/Article/details/gt2rltdgapg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ivvv.top/Article/details/gt2tvuophxs.html

PHP:  // 手写时间戳比较
来源：http://dali.shuidangran.top/Article/details/gt2odetztot.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gt2rwahmisy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2mlageojl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sysykeji.top/Article/details/gt2rnyipbmd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sxryk.cn/Article/details/gt2nfxhhldt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.aizwys.cn/Article/details/gt2ojhxtbxr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.smart0.xyz/Article/details/gt2kelxwivz.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2hvutpmaz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.quarkkingdee.top/Article/details/gt2czywjavh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cdnleiting.top/Article/details/gt2nflbqsph.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yueranfly.top/Article/details/gt2pdblyszj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xnxtlcoy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.birdmap.top/Article/details/gt2xdmqvmpv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenlongwang.top/Article/details/gt2uqzbmynv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.aizwys.cn/Article/details/gt2evxmcuif.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cqqwz.cn/Article/details/gt2bnpsndxl.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2awkzddrd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gogol.net.cn/Article/details/gt2kkriufwi.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2gxrvllfc.html

[Q01] 创建表
来源：http://dali.hnqzz.top/Article/details/gt2ugacvseb.html

CREATE TABLE users (
来源：http://dali.cucudq.cn/Article/details/gt2htuyyovl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.smart0.xyz/Article/details/gt2bzexavag.html

name VARCHAR(50) NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gt2bjjgggqw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ivvv.top/Article/details/gt2mrsbbqwt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.9152youxi.cn/Article/details/gt2gxuhmewa.html

);
来源：http://dali.hnxiangtu.top/Article/details/gt2qvangsbv.html

[Q02] 创建带外键的表
来源：http://dali.yanxiufei.cn/Article/details/gt2zxbtyzfo.html

CREATE TABLE orders (
来源：http://dali.0kj1m.cn/Article/details/gt2ohoqxkhu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gt2xigmrmct.html

user_id INT NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gt2uovhrkfh.html

amount DECIMAL(10, 2),
来源：http://dali.sysykeji.top/Article/details/gt2ooijbasc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jianghu66.top/Article/details/gt2sojzyifg.html

);
来源：http://dali.hywenlv.cn/Article/details/gt2msbaejzn.html

[Q03] 增加列
来源：http://dali.meibo888.top/Article/details/gt2ojfzuxrw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.andypj.xyz/Article/details/gt2himayfav.html

[Q04] 修改列类型
来源：http://dali.ydzc1.top/Article/details/gt2nambxunq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.dianchejie.cn/Article/details/gt2lirrukpy.html

[Q05] 重命名列
来源：http://dali.wangdashe.top/Article/details/gt2rugampwe.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nanxinkj.top/Article/details/gt2znvwnpcv.html

[Q06] 删除列
来源：http://dali.zycfv.cn/Article/details/gt2rsnjvqyf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nanxuanxn.top/Article/details/gt2vdvdptwx.html

[Q07] 删除表
来源：http://dali.guannengcc.top/Article/details/gt2oxxtfjti.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jianghu66.top/Article/details/gt2bzhzepob.html

[Q08] 创建普通索引
来源：http://dali.svipenyu.cn/Article/details/gt2fftvtetl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gt2usqmzqqu.html

[Q09] 创建唯一索引
来源：http://dali.wangdashe.top/Article/details/gt2ffjokkgv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gt2ncuovudm.html

[Q10] 插入单行
来源：http://dali.yongpay.top/Article/details/gt2krnyexsr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258888.top/Article/details/gt2jygjymle.html

[Q11] 一次插入多行
来源：http://dali.redwolf501.top/Article/details/gt2xvrksipl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.c1oappe.top/Article/details/gt2oxukuotd.html

[Q12] 插入后取自增 ID
来源：http://dali.jlsjyb.cn/Article/details/gt2ntwvebjb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.haohaochexian.top/Article/details/gt2qdhngtee.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yexvxgxa.html

[Q13] 忽略重复插入
来源：http://dali.jyoumei.cn/Article/details/gt2ufngrrfu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangdashe.top/Article/details/gt2kobpgveg.html

[Q14] 存在则更新（upsert）
来源：http://dali.mhx1999.top/Article/details/gt2kkhplkld.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hammf.cn/Article/details/gt2wicjcimv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xuetiantiany.cn/Article/details/gt2xmuozchm.html

[Q15] 查询全部
来源：http://dali.chenlongwang.top/Article/details/gt2dliyqleg.html

SELECT * FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2vlbpfcjb.html

[Q16] 查询指定列
来源：http://dali.shzxlz.cn/Article/details/gt2unyvecoz.html

SELECT id, name FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lfyqzgxf.html

[Q17] 条件查询
来源：http://dali.hammf.cn/Article/details/gt2jlxbnpdw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xinyue.icu/Article/details/gt2syxgsndc.html

[Q18] 模糊匹配
来源：http://dali.chenzaomai.com/Article/details/gt2naxiiwce.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnxiangtu.top/Article/details/gt2nvwiozto.html

[Q19] 范围查询
来源：http://dali.yvedp.cn/Article/details/gt2vbesjadd.html


<!-- 参考信息 -->