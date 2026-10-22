代发 wailian999

[M08] 获取系统与运行时信息
来源：http://dali.sysykeji.top/Article/details/gt2oqdjabqa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnxiangtu.top/Article/details/gt2xavdcjtq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ivvv.top/Article/details/gt2hftrmwia.html

JS:   process.platform;  process.version
来源：http://dali.yuanzhike.top/Article/details/gt2uzciptkv.html

TS:   process.platform;  process.version
来源：http://dali.jianghu66.top/Article/details/gt2doewnbbb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sysykeji.top/Article/details/gt2dhaalgyf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daxiang520.top/Article/details/gt2sphutufh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sufxvd.cn/Article/details/gt2nzlajemg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yvedp.cn/Article/details/gt2axmzoiei.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vwsjocdt.html

N. 数据结构与算法
来源：http://dali.yj202588.top/Article/details/gt2kmehicbb.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2kjfvxrsa.html

[N01] 二分查找（有序数组）
来源：http://dali.smart0.xyz/Article/details/gt2meutterl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2tpdrjnzs.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gt2rsqsimal.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gt2uysgjrsi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2avzyfwiq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yquxplil.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2kxwvywzi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yanxiufei.cn/Article/details/gt2frdpxnrt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2iclplfeh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sufxvd.cn/Article/details/gt2wyzyjhpg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gt2cestnrdz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuanzhike.top/Article/details/gt2zbpvkyio.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gt2bgdsvnse.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gt2lgrjnfnz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.svipenyu.cn/Article/details/gt2cbvuorkf.html

Go:   slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gt2wxjsmcds.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gt2riozbbsy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hammf.cn/Article/details/gt2xvgzwwxf.html

[N03] 快速排序（分治示例）
来源：http://dali.tianlin.xyz/Article/details/gt2iliyoufd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ixbdyfeg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.9152youxi.cn/Article/details/gt2pgofzoym.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnqzz.top/Article/details/gt2vlsdivqp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kdzpslnz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tian-w.cn/Article/details/gt2pysplirk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuanzhike.top/Article/details/gt2cwdgxohx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gphcehdj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qeogfgpj.html

[N04] 斐波那契数列
来源：http://dali.0kj1m.cn/Article/details/gt2pilhexwm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gt2zksiabxu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gt2eusrvuqn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gt2hqmmdflo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gt2wxaxqils.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2mqqvyeji.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daxiang520.top/Article/details/gt2uwajzbjf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hywenlv.cn/Article/details/gt2coraiuht.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gt2doymfsna.html

[N05] 最大公约数
来源：http://dali.vqdsnc.cn/Article/details/gt2lhqoisip.html

Py:   math.gcd(a, b)
来源：http://dali.yuanzhike.top/Article/details/gt2mrmjxmmn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xziqi.cn/Article/details/gt2lgvhwxfj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gt2ffqjrarr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aizwys.cn/Article/details/gt2xbzinogf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gzhubu.top/Article/details/gt2srqatdjb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tanke756.top/Article/details/gt2tjifwyjl.html

Ruby: a.gcd(b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dyovpnov.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258.top/Article/details/gt2ccfrzzce.html

[N06] 判断回文字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oirnqapj.html

Py:   s == s[::-1]
来源：http://dali.yueranfly.top/Article/details/gt2queyvwdp.html

PHP:  $s === strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gt2bojctlzk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gt2ghfvpdlk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gt2ejwfvisc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yongpay.top/Article/details/gt2xsrodmsf.html

Go:   // 双指针从两端比较
来源：http://dali.ehwqpu.com/Article/details/gt2clayzjtr.html

Ruby: s == s.reverse
来源：http://dali.guannengcc.top/Article/details/gt2qywaomkx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yueranfly.top/Article/details/gt2umogntwu.html

[N07] 两数之和（返回下标）
来源：http://dali.nwbrower.top/Article/details/gt2zxxngbkg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigufen.top/Article/details/gt2futbinay.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rcwgwgtv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ybcxt.top/Article/details/gt2yeojtfzp.html

TS:   // 手写 Map<string, number>
来源：http://dali.jyoumei.cn/Article/details/gt2ahrwgjjb.html

Java: // 手写 HashMap
来源：http://dali.sysykeji.top/Article/details/gt2nontncxo.html

Go:   // 手写 map[int]int
来源：http://dali.hnxiangtu.top/Article/details/gt2bpfyrsop.html

Ruby: // 手写 Hash
来源：http://dali.redwolf501.top/Article/details/gt2mdzreanq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.iojbl.cn/Article/details/gt2cucseivo.html

[N08] 生成全排列
来源：http://dali.sysykeji.top/Article/details/gt2ukjxuufj.html

Py:   itertools.permutations(arr)
来源：http://dali.cashguo.top/Article/details/gt2hliihwfr.html

PHP:  // 手写递归交换
来源：http://dali.pycfn.com/Article/details/gt2tncwjquy.html

JS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gt2uccoefxd.html

TS:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gt2talfyeey.html

Java: // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gt2gcqgbpqy.html

Go:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gt2jneksmea.html

Ruby: arr.permutation.to_a
来源：http://dali.tanke756.top/Article/details/gt2cigrdcmc.html

C#:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2ezkkuvje.html

[N09] 栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gt2zlzpildc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ybcxt.top/Article/details/gt2anxmdqgb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zycfv.cn/Article/details/gt2tlhrryck.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gt2ytbkcvbv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hywenlv.cn/Article/details/gt2hguozfkv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.smart0.xyz/Article/details/gt2nzxkpyzx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.feifeiyinyue.top/Article/details/gt2vbrentsn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gt2xjcmjgqp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.vqdsnc.cn/Article/details/gt2mxnkhjju.html

[N10] 链表节点定义
来源：http://dali.jyoumei.cn/Article/details/gt2twjicalw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jlsjyb.cn/Article/details/gt2pnpowmfk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgfzy.top/Article/details/gt2iseodarx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kmzollzg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sweek.top/Article/details/gt2bkasslrb.html

Java: class Node { int v; Node next; }
来源：http://dali.ehwqpu.com/Article/details/gt2aydlxawr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ehwqpu.com/Article/details/gt2bbtfdgya.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pwlbyoyi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2udhvmiyy.html

[N11] 二叉树中序遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2ygrujivv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jianghu66.top/Article/details/gt2buqaclrn.html

PHP:  // 手写递归函数
来源：http://dali.shuidangran.top/Article/details/gt2rhqgpbky.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gt2msiblpad.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenjidiqi.icu/Article/details/gt2yzlypqmm.html

Java: // 手写递归
来源：http://dali.ybcxt.top/Article/details/gt2gcofabhj.html

Go:   // 手写递归
来源：http://dali.yvedp.cn/Article/details/gt2maqkwhgn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.havefunace.top/Article/details/gt2lfjzlwfo.html

C#:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gt2mvsvonmq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sysykeji.top/Article/details/gt2crjretkc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.dianchejie.cn/Article/details/gt2krsxodiy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hfpthk.cn/Article/details/gt2krzxkfhg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gt2zpkwkvse.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yvedp.cn/Article/details/gt2irouijin.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pfflcqaa.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhoulong.xyz/Article/details/gt2jxnshiek.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.mhx1999.top/Article/details/gt2tlpwedrz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gt2jbckcrap.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2lydtywqp.html

O. 并发与异步
来源：http://dali.wangdashe.top/Article/details/gt2xzuzluzb.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2aqlyibor.html

[O01] 启动一个线程
来源：http://dali.birdmap.top/Article/details/gt2sifywwfn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.316326.xyz/Article/details/gt2fetnrqaa.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shuidangran.top/Article/details/gt2jcskbwxq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xylfe.cn/Article/details/gt2zdktumek.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gt2wlyhlreh.html

Java: new Thread(() -> f()).start()
来源：http://dali.vqdsnc.cn/Article/details/gt2jpgpnbxj.html

Go:   go f()
来源：http://dali.nwbrower.top/Article/details/gt2pnhdyssj.html

Ruby: Thread.new { f }
来源：http://dali.hammf.cn/Article/details/gt2xmzpcftc.html

C#:   Task.Run(() => F());
来源：http://dali.jyoumei.cn/Article/details/gt2frstimnf.html

[O02] 使用线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wgspcftt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hysaishi.cn/Article/details/gt2iuvpwhyn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.fzhhl.top/Article/details/gt2nihxxdnx.html

JS:   // worker_threads 线程池
来源：http://dali.haohaochexian.top/Article/details/gt2xkjtpqcz.html

TS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gt2xouvwjgj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pmyhhyon.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.feifeiyinyue.top/Article/details/gt2rdopnata.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aizwys.cn/Article/details/gt2clnofpaa.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sysykeji.top/Article/details/gt2ryguimab.html

[O03] 加锁保护共享数据
来源：http://dali.ehwqpu.com/Article/details/gt2mujgzsuz.html

Py:   with lock: shared += 1
来源：http://dali.fzhhl.top/Article/details/gt2pxajdhdr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhoulong.xyz/Article/details/gt2ldcgpxtd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yuanzhike.top/Article/details/gt2yhuntojn.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gt2lhfxhqqf.html

Java: synchronized (this) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gt2uidnlukn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.redwolf501.top/Article/details/gt2rujewfoz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tanke756.top/Article/details/gt2mulwsnjv.html

C#:   lock (gate) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gt2yukdeyhp.html

[O04] 定义异步函数并等待
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zqjkprvo.html

Py:   async def f():⏎    await g()
来源：http://dali.daxiang520.top/Article/details/gt2eidgxent.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.fzhhl.top/Article/details/gt2buekmhhh.html

JS:   async function f() { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2meejrkhh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gt2fmwqyyxr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ivvv.top/Article/details/gt2wbpseuyb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sweek.top/Article/details/gt2guyybbwh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.bjfxy.top/Article/details/gt2hggvyyqs.html

C#:   async Task F() { await G(); }
来源：http://dali.wangdashe.top/Article/details/gt2mojwylzh.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangtech.top/Article/details/gt2buokkglu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangdashe.top/Article/details/gt2hdbtcckx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yuxming.cn/Article/details/gt2pcwtkkpb.html

JS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fpqcdtkt.html

TS:   await Promise.all(tasks)
来源：http://dali.yueranfly.top/Article/details/gt2qbyvedfp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qorbqwfr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xuetiantiany.cn/Article/details/gt2frftdzbl.html

Ruby: threads.map(&:join)
来源：http://dali.andypj.xyz/Article/details/gt2gatqwpup.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigufen.top/Article/details/gt2cllxfimo.html

[O06] 使用进程池
来源：http://dali.sysykeji.top/Article/details/gt2kshuyjda.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.havefunace.top/Article/details/gt2tuvoovji.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gzhubu.top/Article/details/gt2smxgpufb.html

JS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gt2rzrpckov.html

TS:   // child_process / cluster 模块
来源：http://dali.xziqi.cn/Article/details/gt2vlcftvdt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenzaomai.com/Article/details/gt2odvczofd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zycfv.cn/Article/details/gt2nbkzmvuw.html

Ruby: // fork 块
来源：http://dali.hywenlv.cn/Article/details/gt2habvfsgp.html

C#:   Parallel.For
来源：http://dali.yuanzhike.top/Article/details/gt2beutdgbj.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sezmpkau.html

P. 常用工具函数
来源：http://dali.c1oappe.top/Article/details/gt2dzfihayj.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2nagyivhj.html

[P01] 生成 UUID
来源：http://dali.svipenyu.cn/Article/details/gt2yrfxqiir.html

Py:   str(uuid.uuid4())
来源：http://dali.vqdsnc.cn/Article/details/gt2ncpkdhgt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.0kj1m.cn/Article/details/gt2ojyagkzz.html

JS:   crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gt2iffexlfn.html

TS:   crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gt2csjeuuul.html

Java: UUID.randomUUID().toString()
来源：http://dali.gaohongyu789.top/Article/details/gt2ripvtgdh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fengsongda.top/Article/details/gt2ompjlcce.html

Ruby: SecureRandom.uuid
来源：http://dali.cdnleiting.top/Article/details/gt2rfeasucm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigfzy.top/Article/details/gt2aihtydba.html

[P02] MD5 / SHA256 摘要
来源：http://dali.fzhhl.top/Article/details/gt2lrbxdmsb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pypwvwdx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fzhhl.top/Article/details/gt2usoeqobe.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2topylmct.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.vqdsnc.cn/Article/details/gt2nqetekch.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jqgfzy.top/Article/details/gt2pusyxikm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fengsongda.top/Article/details/gt2vpwftmjg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenlongwang.top/Article/details/gt2yjfbfuzc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258.top/Article/details/gt2ufzshhlf.html

[P03] 生成短随机字符串
来源：http://dali.bjfxy.top/Article/details/gt2faewbivg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cqqwz.cn/Article/details/gt2crvbmydg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.fengsongda.top/Article/details/gt2cbvwilop.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2hkzbxojz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gt2ojhorftn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2xfuuyoao.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.wangshuangyany.cn/Article/details/gt2sfkmsgoz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cdnleiting.top/Article/details/gt2rzrdelli.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shuidangran.top/Article/details/gt2zfcdmhaa.html

[P04] 求长度
来源：http://dali.jlsjyb.cn/Article/details/gt2bdxefihh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuxming.cn/Article/details/gt2fopvshch.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gt2lglzgrkp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gt2rlxathdq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gt2njaqhtrp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.bjfxy.top/Article/details/gt2dqboyfyw.html

Go:   len(arr);  len(m)
来源：http://dali.dashuyun.cn/Article/details/gt2smqvgxqk.html

Ruby: x.length;  x.size
来源：http://dali.hongshengwenyu.top/Article/details/gt2yzrhyjxf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hywenlv.cn/Article/details/gt2uoefbfjs.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinghuilouyu.cn/Article/details/gt2exadoxzm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hongshengwenyu.top/Article/details/gt2qjcbgoae.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jianghu66.top/Article/details/gt2mcbbjrbm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yonumen.top/Article/details/gt2cexbqihu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mushletp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guannengcc.top/Article/details/gt2gxhxfzgf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cdnleiting.top/Article/details/gt2oaqnkhnk.html

Ruby: a == b
来源：http://dali.hongshengwenyu.top/Article/details/gt2sotdsqvj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigfzy.top/Article/details/gt2bykgzcgp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuxming.cn/Article/details/gt2wtdoeywz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jiagoushi.top/Article/details/gt2qhummynd.html

PHP:  if (empty($x)) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2hghzxhza.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.daxiang520.top/Article/details/gt2eabtgahe.html

TS:   if (x == null) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2zbqazjia.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2ucnteofk.html

Go:   if x == nil {}
来源：http://dali.fengsongda.top/Article/details/gt2gjtniait.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tianlin.xyz/Article/details/gt2dzuupihq.html

C#:   if (x is null) {}
来源：http://dali.ppjwa.cn/Article/details/gt2mgzqjqek.html

[P07] 防抖与节流
来源：http://dali.zhoulong.xyz/Article/details/gt2iouxtvez.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.vqdsnc.cn/Article/details/gt2teededgm.html

PHP:  // 手写时间戳比较
来源：http://dali.ybcxt.top/Article/details/gt2zbbtuhvl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zycfv.cn/Article/details/gt2thiiodgr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gt2dyiagdxm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ydzc1.top/Article/details/gt2zdvwgjmg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.havefunace.top/Article/details/gt2mssefuir.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.kuanghao11.cn/Article/details/gt2tqsoqwcz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.smart0.xyz/Article/details/gt2izxmjfqw.html

[P08] 处理浮点精度问题
来源：http://dali.tanke756.top/Article/details/gt2kobiucna.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangdashe.top/Article/details/gt2rfzmzonu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jiagoushi.top/Article/details/gt2idgqocox.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cbfxahrx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2twqcwrek.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258.top/Article/details/gt2scurrkcb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xinyue.icu/Article/details/gt2cekurxgx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gaohongyu789.top/Article/details/gt2zewaoufk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.fzhhl.top/Article/details/gt2tgucddpe.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2iflibzcl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vjwbaclm.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2qrrplhfv.html

[Q01] 创建表
来源：http://dali.gotoacloud.top/Article/details/gt2xjwnbxkj.html

CREATE TABLE users (
来源：http://dali.gotoacloud.top/Article/details/gt2xscuuhhe.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gt2kkuvblya.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sxryk.cn/Article/details/gt2shgzebxv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhoulong.xyz/Article/details/gt2bhrpdtce.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daria6918.cn/Article/details/gt2wzufcqws.html

);
来源：http://dali.cqqwz.cn/Article/details/gt2roolmroo.html

[Q02] 创建带外键的表
来源：http://dali.ehwqpu.com/Article/details/gt2wreuyold.html

CREATE TABLE orders (
来源：http://dali.snrcjt.cn/Article/details/gt2vgxfdvef.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhixingplan.top/Article/details/gt2fwsusloc.html

user_id INT NOT NULL,
来源：http://dali.cheryme.top/Article/details/gt2zkrkcolb.html

amount DECIMAL(10, 2),
来源：http://dali.xinyue.icu/Article/details/gt2fqnhseem.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhongyouzk.top/Article/details/gt2txblcfuk.html

);
来源：http://dali.yj20258.top/Article/details/gt2nafalnao.html

[Q03] 增加列
来源：http://dali.snrcjt.cn/Article/details/gt2atsfvvml.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hnxiangtu.top/Article/details/gt2acysnymh.html

[Q04] 修改列类型
来源：http://dali.cucudq.cn/Article/details/gt2abnkmnct.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.316326.xyz/Article/details/gt2xtzddpzs.html

[Q05] 重命名列
来源：http://dali.dashuyun.cn/Article/details/gt2uzngomfr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ybcxt.top/Article/details/gt2inpewzjq.html

[Q06] 删除列
来源：http://dali.hongshengwenyu.top/Article/details/gt2tsfyewxv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cqqwz.cn/Article/details/gt2lembprbq.html

[Q07] 删除表
来源：http://dali.zhengqikj.top/Article/details/gt2mixnjmjg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tian-w.cn/Article/details/gt2utvitqat.html

[Q08] 创建普通索引
来源：http://dali.vqdsnc.cn/Article/details/gt2owcvoqsh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2thecbhfe.html

[Q09] 创建唯一索引
来源：http://dali.iojbl.cn/Article/details/gt2kgiitkzk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gt2ihfojqwx.html

[Q10] 插入单行
来源：http://dali.gzhubu.top/Article/details/gt2expyhsar.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.9152youxi.cn/Article/details/gt2hkdwgaka.html

[Q11] 一次插入多行
来源：http://dali.gotoacloud.top/Article/details/gt2uwifyeya.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zycfv.cn/Article/details/gt2qbrvkbpt.html

[Q12] 插入后取自增 ID
来源：http://dali.zhiwuduotai.top/Article/details/gt2gwpsfkzg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jqgufenzy.top/Article/details/gt2cnldteec.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuxming.cn/Article/details/gt2vfhksmhb.html

[Q13] 忽略重复插入
来源：http://dali.gzhubu.top/Article/details/gt2pnnvhmyh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ehwqpu.com/Article/details/gt2zqausfsx.html

[Q14] 存在则更新（upsert）
来源：http://dali.meibo888.top/Article/details/gt2hxtwglhz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.wangshuangyany.cn/Article/details/gt2dnpgllyg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nlsgovuk.html

[Q15] 查询全部
来源：http://dali.sufxvd.cn/Article/details/gt2rcvkfzqb.html

SELECT * FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2sjkyezyb.html

[Q16] 查询指定列
来源：http://dali.zhongyouzk.top/Article/details/gt2ddcwpliu.html

SELECT id, name FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2kijssluu.html

[Q17] 条件查询
来源：http://dali.zdqjudy.top/Article/details/gt2mfdaqfux.html


<!-- 参考信息 -->