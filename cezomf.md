代发 wailian999

[M08] 获取系统与运行时信息
来源：http://dali.yueranfly.top/Article/details/gtvjnntnrt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.bjfxy.top/Article/details/gtlzjqsfxv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shzxlz.cn/Article/details/gthguyjgsi.html

JS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gttkbrkzxo.html

TS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gtcnfzkrbs.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cashguo.top/Article/details/gtcnsehjcu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258.top/Article/details/gtbqmjtbui.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yongpay.top/Article/details/gtpigskqjd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cqqwz.cn/Article/details/gttujeiwcz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbuajbkp.html

N. 数据结构与算法
来源：http://dali.hnqzz.top/Article/details/gtqqbykiog.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtryyzdgrn.html

[N01] 二分查找（有序数组）
来源：http://dali.xziqi.cn/Article/details/gtvbxertdh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtxsnnnxqi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cheryme.top/Article/details/gtacgzfycm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gtrntbjsij.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gtsddrkarw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtqbhbyytf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtapdjxogz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.pengpengdd.cyou/Article/details/gtdzkvuaei.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtuymmibod.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.feifeiyinyue.top/Article/details/gtmwafhwek.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gtihkdlzoj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.quarkkingdee.top/Article/details/gtgaanpffl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtexjvilyp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gtprdnlyzx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258.top/Article/details/gthqwavodk.html

Go:   slices.Sort(arr)
来源：http://dali.xinyue.icu/Article/details/gtgstoksvs.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gtqgojjrjp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxehvacir.html

[N03] 快速排序（分治示例）
来源：http://dali.gaohongyu789.top/Article/details/gtitaivjfq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuanzhike.top/Article/details/gtyyzkjsxk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hywenlv.cn/Article/details/gtirxplrun.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gtjceqpxlc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gtpywzfgey.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ivvv.top/Article/details/gtybmwnexg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yanxiufei.cn/Article/details/gtbiybpyrm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.kuanghao11.cn/Article/details/gtskqpltss.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenzaomai.com/Article/details/gtuthxrbzp.html

[N04] 斐波那契数列
来源：http://dali.jinqigfzy.top/Article/details/gtrnrppqxu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gticvspppp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gtzjjgixxi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gttlpzsdar.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtxjfmpqhc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.iojbl.cn/Article/details/gttvvbhwyi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.quarkkingdee.top/Article/details/gtzzkkxpus.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gtbxkunqfe.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gtxklinwax.html

[N05] 最大公约数
来源：http://dali.ehwqpu.com/Article/details/gtpvoyurqe.html

Py:   math.gcd(a, b)
来源：http://dali.andypj.xyz/Article/details/gtwjcvlnoo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsivpkndg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpomoyen.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gtbzcujemq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhongyouzk.top/Article/details/gtpqwyqmxd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhiwuduotai.top/Article/details/gttflomijw.html

Ruby: a.gcd(b)
来源：http://dali.mhx1999.top/Article/details/gtayyxddsx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.smart0.xyz/Article/details/gtgrombhhf.html

[N06] 判断回文字符串
来源：http://dali.aizwys.cn/Article/details/gtojwsqtjm.html

Py:   s == s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gtkrbtzehk.html

PHP:  $s === strrev($s);
来源：http://dali.smart0.xyz/Article/details/gteklusedo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtupjmrukx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtqfzpebrp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhixingplan.top/Article/details/gtzmdhkocj.html

Go:   // 双指针从两端比较
来源：http://dali.snrcjt.cn/Article/details/gtjpoktgnd.html

Ruby: s == s.reverse
来源：http://dali.chenlongwang.top/Article/details/gtooxnazfu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gtdcemfbhc.html

[N07] 两数之和（返回下标）
来源：http://dali.nwbrower.top/Article/details/gtepronljt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xinyue.icu/Article/details/gtfbvfalvd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.mhx1999.top/Article/details/gtrvvjbjhb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yonumen.top/Article/details/gtzqcxfjlc.html

TS:   // 手写 Map<string, number>
来源：http://dali.tianlin.xyz/Article/details/gtviwwtcnm.html

Java: // 手写 HashMap
来源：http://dali.hysaishi.cn/Article/details/gtfoyyctrt.html

Go:   // 手写 map[int]int
来源：http://dali.gogol.net.cn/Article/details/gtdvedfszw.html

Ruby: // 手写 Hash
来源：http://dali.nanxuanxn.top/Article/details/gtnvmkqxgd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.meibo888.top/Article/details/gtlgcrgfmq.html

[N08] 生成全排列
来源：http://dali.wangshuangyany.cn/Article/details/gtoauonjpq.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgfzy.top/Article/details/gtropkaqgn.html

PHP:  // 手写递归交换
来源：http://dali.zdqjudy.top/Article/details/gtnymjweut.html

JS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtwttcxsyt.html

TS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtjgdaapot.html

Java: // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtpknuohag.html

Go:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtlzgglfkf.html

Ruby: arr.permutation.to_a
来源：http://dali.zycfv.cn/Article/details/gtolyqvhad.html

C#:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtciwwerli.html

[N09] 栈与队列
来源：http://dali.cucudq.cn/Article/details/gthzircjud.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjluxkmfn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gtefprxrzn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tanke756.top/Article/details/gtfefmmkni.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cashguo.top/Article/details/gtxqkczljf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fengsongda.top/Article/details/gtznnrjxmg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.vqdsnc.cn/Article/details/gteoywdxxp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtlvejcecf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jlsjyb.cn/Article/details/gtsruqexjj.html

[N10] 链表节点定义
来源：http://dali.aibaodan.cn/Article/details/gtipqjapsi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.smart0.xyz/Article/details/gtnjmpwbkp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aibaodan.cn/Article/details/gtixrfdltl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tianlin.xyz/Article/details/gtpgdmppdy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gaohongyu789.top/Article/details/gtaidmfobi.html

Java: class Node { int v; Node next; }
来源：http://dali.daria6918.cn/Article/details/gtjawltxob.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cqqwz.cn/Article/details/gtcbepsahk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknpcjxwp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jyoumei.cn/Article/details/gtwushxgqm.html

[N11] 二叉树中序遍历
来源：http://dali.shangyingyoupin.top/Article/details/gthmmmwvbr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cqqwz.cn/Article/details/gtdukmphvc.html

PHP:  // 手写递归函数
来源：http://dali.9152youxi.cn/Article/details/gtkbtygkie.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhixingplan.top/Article/details/gtmjitqolh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gtradvdvni.html

Java: // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtjyudhjju.html

Go:   // 手写递归
来源：http://dali.aizwys.cn/Article/details/gtpqegamxv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guowangkeji.top/Article/details/gtozqavins.html

C#:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtyfviqiph.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sweek.top/Article/details/gtatiarzvr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.havefunace.top/Article/details/gtotmwtpil.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ydzc1.top/Article/details/gtwiowyeyh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gturtmsich.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gtddeqbxta.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqbhhnnh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yongpay.top/Article/details/gtitqkixzf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhixingplan.top/Article/details/gtavdqwwyn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ydzc1.top/Article/details/gtbeufpckx.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtrdsrykhy.html

O. 并发与异步
来源：http://dali.zdqjudy.top/Article/details/gtuugtkyrv.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gthtojqnad.html

[O01] 启动一个线程
来源：http://dali.sysykeji.top/Article/details/gtfspjhida.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenlongwang.top/Article/details/gtkvahzmez.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.wangshuangyany.cn/Article/details/gtkpjvsvcl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlyyfisz.html

TS:   // 同 JS
来源：http://dali.mhx1999.top/Article/details/gtmfjqfxeu.html

Java: new Thread(() -> f()).start()
来源：http://dali.9152youxi.cn/Article/details/gtxlywespa.html

Go:   go f()
来源：http://dali.haohaochexian.top/Article/details/gtonmlnsbg.html

Ruby: Thread.new { f }
来源：http://dali.quarkkingdee.top/Article/details/gtnpudyrjs.html

C#:   Task.Run(() => F());
来源：http://dali.cashguo.top/Article/details/gtmsyrngbi.html

[O02] 使用线程池
来源：http://dali.fengsongda.top/Article/details/gtuehislqs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gotoacloud.top/Article/details/gthyilqrap.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tian-w.cn/Article/details/gttixnrtdt.html

JS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gtsnmciyge.html

TS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gtjilquuvh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhixingplan.top/Article/details/gtvvbotfrd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cashguo.top/Article/details/gtjcgsvsfe.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fengsongda.top/Article/details/gtpnlympvq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xuetiantiany.cn/Article/details/gtkfniktkw.html

[O03] 加锁保护共享数据
来源：http://dali.gaohongyu789.top/Article/details/gtnkvsfdfx.html

Py:   with lock: shared += 1
来源：http://dali.daria6918.cn/Article/details/gtjonrpnjf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shzxlz.cn/Article/details/gtaaiidgcm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sweek.top/Article/details/gtrqxhmxxr.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gtowqubpay.html

Java: synchronized (this) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gtkiaivejt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenjidiqi.icu/Article/details/gtmrtvvtrr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cdnleiting.top/Article/details/gtzfagjcvj.html

C#:   lock (gate) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdhjjesw.html

[O04] 定义异步函数并等待
来源：http://dali.yongpay.top/Article/details/gtzafvjkcy.html

Py:   async def f():⏎    await g()
来源：http://dali.tian-w.cn/Article/details/gtlemfdurq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hysaishi.cn/Article/details/gtyndlxpkp.html

JS:   async function f() { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gtiuedlvzq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ybcxt.top/Article/details/gtaihtyzsv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhiwuduotai.top/Article/details/gtefpcnfzu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.pengpengdd.cyou/Article/details/gtrlijqbaa.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shangyingyoupin.top/Article/details/gtppmtjlwz.html

C#:   async Task F() { await G(); }
来源：http://dali.kuanghao11.cn/Article/details/gtvrniytzj.html

[O05] 并发执行并等待全部完成
来源：http://dali.jyoumei.cn/Article/details/gtjtddcbzi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtcqvmdfih.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shzxlz.cn/Article/details/gttccjnnzu.html

JS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gtndwigphp.html

TS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gthwcpmxfa.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sweek.top/Article/details/gtbtqzsckq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yongpay.top/Article/details/gtzlftwrzz.html

Ruby: threads.map(&:join)
来源：http://dali.xuanzx.com/Article/details/gtkiunqeiq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tianlin.xyz/Article/details/gtmptpctev.html

[O06] 使用进程池
来源：http://dali.yongpay.top/Article/details/gtfxclskqz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hfpthk.cn/Article/details/gtnvcfldog.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.birdmap.top/Article/details/gtqgjhdbtd.html

JS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gtebxxfyyd.html

TS:   // child_process / cluster 模块
来源：http://dali.havefunace.top/Article/details/gtherhdocj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhengqikj.top/Article/details/gthtwepfdj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shuidangran.top/Article/details/gtrhsidwab.html

Ruby: // fork 块
来源：http://dali.pengpengdd.cyou/Article/details/gtusnsrjgq.html

C#:   Parallel.For
来源：http://dali.zhengqikj.top/Article/details/gtyiqpzkxa.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtbwnjlrmf.html

P. 常用工具函数
来源：http://dali.aizwys.cn/Article/details/gtfnevvhbj.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtmtldenoj.html

[P01] 生成 UUID
来源：http://dali.dianchejie.cn/Article/details/gtpbzsxxmd.html

Py:   str(uuid.uuid4())
来源：http://dali.haohaochexian.top/Article/details/gtfawhluyk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhongyouzk.top/Article/details/gtiaxmnrul.html

JS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gtgssqfbrs.html

TS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gtpszktkho.html

Java: UUID.randomUUID().toString()
来源：http://dali.smart0.xyz/Article/details/gtzlcfbllz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.meibo888.top/Article/details/gtmvkxggja.html

Ruby: SecureRandom.uuid
来源：http://dali.chenzaomai.com/Article/details/gtiwatpoul.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.svipenyu.cn/Article/details/gtjsceibkm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yanxiufei.cn/Article/details/gtrwdisefq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.vqdsnc.cn/Article/details/gtnlmusywe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jyoumei.cn/Article/details/gtfpgbwhol.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ehwqpu.com/Article/details/gtaxpiwnoo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.andypj.xyz/Article/details/gtejqnamqo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sxryk.cn/Article/details/gttfmahmei.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj20258.top/Article/details/gtkrdlowrk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj202588.top/Article/details/gtmsrfpoqa.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daxiang520.top/Article/details/gtzgekkbfh.html

[P03] 生成短随机字符串
来源：http://dali.9152youxi.cn/Article/details/gtmicimslv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xziqi.cn/Article/details/gtadsqrjha.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gogol.net.cn/Article/details/gthotoigqq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gtjjnwpqnk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gtheeulufy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ehwqpu.com/Article/details/gtzgyxptsb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.haohaochexian.top/Article/details/gtpnxifzpu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yuanzhike.top/Article/details/gtqmacdifz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.c1oappe.top/Article/details/gttspeksvm.html

[P04] 求长度
来源：http://dali.ydzc1.top/Article/details/gtxgxmbrzp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgufenzy.top/Article/details/gtwuwifwmq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtmrmutsck.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtcsrbpnle.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gtybrfaxgw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gtokjxsdtb.html

Go:   len(arr);  len(m)
来源：http://dali.mhx1999.top/Article/details/gttynytsun.html

Ruby: x.length;  x.size
来源：http://dali.cashguo.top/Article/details/gtyvoppzuk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.0kj1m.cn/Article/details/gtqfvoxqsh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ppjwa.cn/Article/details/gtloiwrnvo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gogol.net.cn/Article/details/gtgcjctgmg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.fengsongda.top/Article/details/gtjohgdeiu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ppjwa.cn/Article/details/gtarlnmoaz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gtiwethcub.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.smart0.xyz/Article/details/gtvcmkmhjj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yonumen.top/Article/details/gtkolyludu.html

Ruby: a == b
来源：http://dali.tian-w.cn/Article/details/gtlscxswkh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinghuilouyu.cn/Article/details/gtganeruua.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.pycfn.com/Article/details/gtghswlzkp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.dianchejie.cn/Article/details/gtrtxqazww.html

PHP:  if (empty($x)) {}
来源：http://dali.daxiang520.top/Article/details/gtbctkckqe.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxuanxn.top/Article/details/gtjhjewaxl.html

TS:   if (x == null) {}
来源：http://dali.dashuyun.cn/Article/details/gtonckpkhs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gtlmwlxjww.html

Go:   if x == nil {}
来源：http://dali.xinyue.icu/Article/details/gttoquttnw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sysykeji.top/Article/details/gtijrdxfoj.html

C#:   if (x is null) {}
来源：http://dali.svipenyu.cn/Article/details/gtxzuvoxgz.html

[P07] 防抖与节流
来源：http://dali.yonumen.top/Article/details/gttxtzenpz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yuanzhike.top/Article/details/gtjvdmyqkb.html

PHP:  // 手写时间戳比较
来源：http://dali.xuetiantiany.cn/Article/details/gtomgmmyjx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtbazdglfe.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtluwjzrjj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtiszhbuep.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258.top/Article/details/gtcuupbucu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxppjwnwz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxinkj.top/Article/details/gtwippbenc.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigufen.top/Article/details/gtfddnulvk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tanke756.top/Article/details/gtkgccxeac.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sufxvd.cn/Article/details/gtluznpuaw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pengpengdd.cyou/Article/details/gtxvymlcuh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xylfe.cn/Article/details/gtxnffntmv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yanxiufei.cn/Article/details/gtlzmwooez.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tian-w.cn/Article/details/gtrjtatglv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jlsjyb.cn/Article/details/gtxmppqmcj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhixingplan.top/Article/details/gtlrkxcxmp.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtrtdogznr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xziqi.cn/Article/details/gtejmrzagk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtwmomabgq.html

[Q01] 创建表
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrxuxbzq.html

CREATE TABLE users (
来源：http://dali.zhiwuduotai.top/Article/details/gtpznhiyvy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ydzc1.top/Article/details/gtskqqkijo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhiwuduotai.top/Article/details/gtmjbjwkwj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.vqdsnc.cn/Article/details/gtbcazqfjf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.feifeiyinyue.top/Article/details/gtthdvfqpe.html

);
来源：http://dali.zycfv.cn/Article/details/gtnteofhcm.html

[Q02] 创建带外键的表
来源：http://dali.ivvv.top/Article/details/gtsejquscw.html

CREATE TABLE orders (
来源：http://dali.dashuyun.cn/Article/details/gtiyrjxdti.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gtfzadpcxd.html

user_id INT NOT NULL,
来源：http://dali.ivvv.top/Article/details/gtniuwdrbw.html

amount DECIMAL(10, 2),
来源：http://dali.nanxuanxn.top/Article/details/gtnyxkjbmc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ydzc1.top/Article/details/gtglbvbphi.html

);
来源：http://dali.nwbrower.top/Article/details/gtulfsydeh.html

[Q03] 增加列
来源：http://dali.yangfankeji.com/Article/details/gtiizmytve.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hywenlv.cn/Article/details/gtqnknkrgh.html

[Q04] 修改列类型
来源：http://dali.gzhubu.top/Article/details/gtxgimxref.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.havefunace.top/Article/details/gtxdrusxjh.html

[Q05] 重命名列
来源：http://dali.zhoulong.xyz/Article/details/gtdfkkcwar.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.haohaochexian.top/Article/details/gtykgkxpga.html

[Q06] 删除列
来源：http://dali.cdnleiting.top/Article/details/gtxvryaixi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.c1oappe.top/Article/details/gtiipmdbir.html

[Q07] 删除表
来源：http://dali.xziqi.cn/Article/details/gtjzmbjfmo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenlongwang.top/Article/details/gtnwjlpnds.html

[Q08] 创建普通索引
来源：http://dali.andypj.xyz/Article/details/gtorkstcdj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gtrergqclf.html

[Q09] 创建唯一索引
来源：http://dali.jinqigfzy.top/Article/details/gtsexejmwx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zdqjudy.top/Article/details/gtaoobgmdh.html

[Q10] 插入单行
来源：http://dali.ppjwa.cn/Article/details/gtxncamwtk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yangfankeji.com/Article/details/gttzbvczyf.html

[Q11] 一次插入多行
来源：http://dali.yvedp.cn/Article/details/gtqilxdhhw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ehwqpu.com/Article/details/gtvphydpri.html

[Q12] 插入后取自增 ID
来源：http://dali.sxryk.cn/Article/details/gtatxkymfq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yonumen.top/Article/details/gtldlwocld.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj202588.top/Article/details/gtiqsvqtme.html

[Q13] 忽略重复插入
来源：http://dali.cdnleiting.top/Article/details/gtnbmuouap.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtqgnknadk.html

[Q14] 存在则更新（upsert）
来源：http://dali.meibo888.top/Article/details/gtgayqiuez.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tian-w.cn/Article/details/gtvlpkgnkq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenzaomai.com/Article/details/gteqclnluw.html

[Q15] 查询全部
来源：http://dali.hysaishi.cn/Article/details/gtmvifxeee.html

SELECT * FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gturxtfckl.html

[Q16] 查询指定列
来源：http://dali.jlsjyb.cn/Article/details/gtrhgulxye.html

SELECT id, name FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gthauqjovx.html

[Q17] 条件查询
来源：http://dali.gzhubu.top/Article/details/gtqshrklqm.html


<!-- 参考信息 -->