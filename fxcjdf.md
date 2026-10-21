代发 wailian999

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtwaukdzdu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pengpengdd.cyou/Article/details/gttyksmfrt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xylfe.cn/Article/details/gtcialifom.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywslfnpq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gtributrwg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gtobfkfzhj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzadznqo.html

Go:   slices.Sort(arr)
来源：http://dali.chenlongwang.top/Article/details/gtvnmbpcij.html

Ruby: arr.sort
来源：http://dali.chenzaomai.com/Article/details/gtzifnijhf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yangfankeji.com/Article/details/gtthltnvso.html

[N03] 快速排序（分治示例）
来源：http://dali.yuanzhike.top/Article/details/gtnphsqnsg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jianghu66.top/Article/details/gtfsucurvm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj202588.top/Article/details/gtpasgjylm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gttbbfcenm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gtlbplqrbr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangdashe.top/Article/details/gthsyisvse.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuanzx.com/Article/details/gtkwjgripi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhiwuduotai.top/Article/details/gtwkpwqcqn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yongpay.top/Article/details/gtmciyqdtx.html

[N04] 斐波那契数列
来源：http://dali.dashuyun.cn/Article/details/gtdyyfwptc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gtekuesnnw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gtlmwlrzuo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtseqmuyua.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gtsjcltpfe.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gtyusirdoi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenlongwang.top/Article/details/gtahfepokt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gtyxgxksfb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtlwysqeap.html

[N05] 最大公约数
来源：http://dali.nanxuanxn.top/Article/details/gttahztkzp.html

Py:   math.gcd(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtveyanaka.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zdqjudy.top/Article/details/gttmtribpd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjkzigjuy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gtxkolcizj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258888.top/Article/details/gtaiiqdgew.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aizwys.cn/Article/details/gtvoysohag.html

Ruby: a.gcd(b)
来源：http://dali.xuanzx.com/Article/details/gtwwfyfdnz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hnqzz.top/Article/details/gtwuecqmmg.html

[N06] 判断回文字符串
来源：http://dali.yuanzhike.top/Article/details/gtsjnjwece.html

Py:   s == s[::-1]
来源：http://dali.havefunace.top/Article/details/gtvfvkekoa.html

PHP:  $s === strrev($s);
来源：http://dali.sweek.top/Article/details/gtkgczfunx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtjyvnkdcx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtwtkzhcxh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gotoacloud.top/Article/details/gtbxcncnsl.html

Go:   // 双指针从两端比较
来源：http://dali.yvedp.cn/Article/details/gtygzdsmwd.html

Ruby: s == s.reverse
来源：http://dali.havefunace.top/Article/details/gtwdwaqqch.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gtvmxnrbgh.html

[N07] 两数之和（返回下标）
来源：http://dali.nanxuanxn.top/Article/details/gtsgclfghl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pengpengdd.cyou/Article/details/gtmkrzdvbv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.daria6918.cn/Article/details/gtxteswayu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.birdmap.top/Article/details/gtwvmbyamo.html

TS:   // 手写 Map<string, number>
来源：http://dali.cqqwz.cn/Article/details/gtidobdqmd.html

Java: // 手写 HashMap
来源：http://dali.pycfn.com/Article/details/gtppgzpoxx.html

Go:   // 手写 map[int]int
来源：http://dali.aibaodan.cn/Article/details/gtemkigung.html

Ruby: // 手写 Hash
来源：http://dali.316326.xyz/Article/details/gtpbubrqim.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cheryme.top/Article/details/gtacztlvik.html

[N08] 生成全排列
来源：http://dali.gotoacloud.top/Article/details/gtqdvautlt.html

Py:   itertools.permutations(arr)
来源：http://dali.daxiang520.top/Article/details/gtxsukayeu.html

PHP:  // 手写递归交换
来源：http://dali.jiagoushi.top/Article/details/gtjceziqnv.html

JS:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfhcqhnq.html

TS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtkzokxnxp.html

Java: // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtcdhofbxn.html

Go:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtxjcqfpmx.html

Ruby: arr.permutation.to_a
来源：http://dali.fzhhl.top/Article/details/gtsuhmrbuk.html

C#:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtcnofladv.html

[N09] 栈与队列
来源：http://dali.fzhhl.top/Article/details/gtwqwiikzk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhixingplan.top/Article/details/gttvnjtdhm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj202588.top/Article/details/gtqgeoeqhi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gteccmxnvt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.birdmap.top/Article/details/gthmuqgndr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhengqikj.top/Article/details/gtspnzhrsp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hongshengwenyu.top/Article/details/gtfdhynkrc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gtqhkpwyxo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dashuyun.cn/Article/details/gtctwpjbal.html

[N10] 链表节点定义
来源：http://dali.jinqigufen.top/Article/details/gtvknswsrm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sxryk.cn/Article/details/gtwwgnweja.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aizwys.cn/Article/details/gtwfudpduu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jyoumei.cn/Article/details/gtdumdulck.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.haohaochexian.top/Article/details/gtqoyqesfa.html

Java: class Node { int v; Node next; }
来源：http://dali.zhiwuduotai.top/Article/details/gtywquwzgx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sweek.top/Article/details/gtooxawxhm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jlsjyb.cn/Article/details/gtomoonbxd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zdqjudy.top/Article/details/gtymlxpugh.html

[N11] 二叉树中序遍历
来源：http://dali.dashuyun.cn/Article/details/gtekvovyao.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dianchejie.cn/Article/details/gtjpguhjtq.html

PHP:  // 手写递归函数
来源：http://dali.zhoulong.xyz/Article/details/gtsazqnmth.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenjidiqi.icu/Article/details/gthqxmbfnp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacppvgwr.html

Java: // 手写递归
来源：http://dali.tanke756.top/Article/details/gtadtavzcb.html

Go:   // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gtyjpellxi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.redwolf501.top/Article/details/gtsddykqmi.html

C#:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtodxwzsss.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhixingplan.top/Article/details/gtpscugfzn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hammf.cn/Article/details/gtzbznwvju.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.pycfn.com/Article/details/gtvusimsgl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gtjhtrzbdh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gtpubkjncl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gtavpyniqa.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ppjwa.cn/Article/details/gtziyujeaq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtdetjhsyt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigufen.top/Article/details/gtevgxvaxh.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtlhtvpfev.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gtujekdpno.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtkhesarbu.html

[O01] 启动一个线程
来源：http://dali.fzhhl.top/Article/details/gtncbhsnbs.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gotoacloud.top/Article/details/gtrrjibayn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jianghu66.top/Article/details/gtxufsvkqu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.9152youxi.cn/Article/details/gtsrijtwks.html

TS:   // 同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywxrwlrg.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthydendlv.html

Go:   go f()
来源：http://dali.yueranfly.top/Article/details/gttgubppdi.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrznifmo.html

C#:   Task.Run(() => F());
来源：http://dali.316326.xyz/Article/details/gtsywcqsto.html

[O02] 使用线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtxeopmkcu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aizwys.cn/Article/details/gtyujeudyb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yueranfly.top/Article/details/gtrrcyrnup.html

JS:   // worker_threads 线程池
来源：http://dali.cashguo.top/Article/details/gtgypdgrte.html

TS:   // worker_threads 线程池
来源：http://dali.zdqjudy.top/Article/details/gtjgljmoju.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.feifeiyinyue.top/Article/details/gtzwtdoctb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.kuanghao11.cn/Article/details/gtxhybcziy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yangfankeji.com/Article/details/gtwaizwtss.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenlongwang.top/Article/details/gtrvbdtbbk.html

[O03] 加锁保护共享数据
来源：http://dali.sysykeji.top/Article/details/gtnyspntse.html

Py:   with lock: shared += 1
来源：http://dali.nwbrower.top/Article/details/gthtexnbnf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sweek.top/Article/details/gtccthbabj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjrfzsog.html

TS:   // 同 JS
来源：http://dali.wangshuangyany.cn/Article/details/gtcxnymxjy.html

Java: synchronized (this) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gtgecevqcu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgfzy.top/Article/details/gtaojgwszx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.fengsongda.top/Article/details/gtfdzrincf.html

C#:   lock (gate) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gtjrtuptpr.html

[O04] 定义异步函数并等待
来源：http://dali.sweek.top/Article/details/gtoxnyjxsi.html

Py:   async def f():⏎    await g()
来源：http://dali.chenzaomai.com/Article/details/gtxrsbgdyz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tanke756.top/Article/details/gtrnkbtaky.html

JS:   async function f() { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gtljkwazue.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258.top/Article/details/gteczbuwlx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ybcxt.top/Article/details/gtcdvcjthq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cheryme.top/Article/details/gtnfmdeuug.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daxiang520.top/Article/details/gtlthkfscg.html

C#:   async Task F() { await G(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocxwgjgp.html

[O05] 并发执行并等待全部完成
来源：http://dali.9152youxi.cn/Article/details/gtwrbejgzl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvumbhbnw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hfpthk.cn/Article/details/gtwfjeccbn.html

JS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gtfrbajzed.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gtkdxoqxzb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuxming.cn/Article/details/gtobytnopx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cucudq.cn/Article/details/gtscuqlyht.html

Ruby: threads.map(&:join)
来源：http://dali.hysaishi.cn/Article/details/gtgrkxscnr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jiagoushi.top/Article/details/gtmkodmyrv.html

[O06] 使用进程池
来源：http://dali.jiagoushi.top/Article/details/gtekcxknxi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigfzy.top/Article/details/gtmzjhbabn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cucudq.cn/Article/details/gttehjvfta.html

JS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gtwmfxuddn.html

TS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gtttfrnmly.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gtnbnqtpod.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zycfv.cn/Article/details/gtfbrcbbqe.html

Ruby: // fork 块
来源：http://dali.bjfxy.top/Article/details/gtkmepryiv.html

C#:   Parallel.For
来源：http://dali.hysaishi.cn/Article/details/gtxkfivspc.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtonkbxvxo.html

P. 常用工具函数
来源：http://dali.ppjwa.cn/Article/details/gtjlsvlmpv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtklpgiury.html

[P01] 生成 UUID
来源：http://dali.birdmap.top/Article/details/gtdubybhkv.html

Py:   str(uuid.uuid4())
来源：http://dali.hongshengwenyu.top/Article/details/gtkoymipbv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.birdmap.top/Article/details/gtusmlsjzc.html

JS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gtnezclhbv.html

TS:   crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gtzelgfjax.html

Java: UUID.randomUUID().toString()
来源：http://dali.316326.xyz/Article/details/gtnpzxpzfu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xziqi.cn/Article/details/gtbmqbqwdr.html

Ruby: SecureRandom.uuid
来源：http://dali.hysaishi.cn/Article/details/gtnlhqagjs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cucudq.cn/Article/details/gtvaylkuir.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hongshengwenyu.top/Article/details/gtvutivuov.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daria6918.cn/Article/details/gtrwaeesrt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenzaomai.com/Article/details/gtndxjjqru.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yanxiufei.cn/Article/details/gtxjgnceli.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwndlayhu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.redwolf501.top/Article/details/gtqkfrlhxu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.svipenyu.cn/Article/details/gtaqvicmxu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shuidangran.top/Article/details/gtvazpexwk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.birdmap.top/Article/details/gtyybhoabh.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gtjfxvrozv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gogol.net.cn/Article/details/gtyzxssklq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gogol.net.cn/Article/details/gtkicdyxse.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ppjwa.cn/Article/details/gtaouertio.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sufxvd.cn/Article/details/gtycqrxrlk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.snrcjt.cn/Article/details/gtkihtjirr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nanxuanxn.top/Article/details/gtlghxuosj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.c1oappe.top/Article/details/gtymalwprr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fzhhl.top/Article/details/gtcltgbsnv.html

[P04] 求长度
来源：http://dali.jinghuilouyu.cn/Article/details/gthljuyrqp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqrokwcy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtclllcsxl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybeupmty.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gtacpzoilf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgufenzy.top/Article/details/gteeocbttw.html

Go:   len(arr);  len(m)
来源：http://dali.tian-w.cn/Article/details/gtusjhnxlx.html

Ruby: x.length;  x.size
来源：http://dali.jiagoushi.top/Article/details/gtdkkaxtfv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gogol.net.cn/Article/details/gtvsdweuuk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guannengcc.top/Article/details/gtjunsjbwb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdiohcfyf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nanxinkj.top/Article/details/gtjxsfgdhd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.redwolf501.top/Article/details/gtwuwiyfqb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.c1oappe.top/Article/details/gtabzigukr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hnxiangtu.top/Article/details/gtlaybtmlw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.smart0.xyz/Article/details/gtkozepvtv.html

Ruby: a == b
来源：http://dali.chenzaomai.com/Article/details/gtnzrqzjmo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cucudq.cn/Article/details/gtfipydbuc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinghuilouyu.cn/Article/details/gtvekcbnqx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenjidiqi.icu/Article/details/gtlwswfeln.html

PHP:  if (empty($x)) {}
来源：http://dali.gogol.net.cn/Article/details/gtfajyuazt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.9152youxi.cn/Article/details/gtntvlbejo.html

TS:   if (x == null) {}
来源：http://dali.yj202588.top/Article/details/gtueozykyy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gttggfmqlw.html

Go:   if x == nil {}
来源：http://dali.gzhubu.top/Article/details/gtvhlshijz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinqigfzy.top/Article/details/gtkcmykgvx.html

C#:   if (x is null) {}
来源：http://dali.nanxuanxn.top/Article/details/gttozlmeox.html

[P07] 防抖与节流
来源：http://dali.kuanghao11.cn/Article/details/gtanqkejon.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gotoacloud.top/Article/details/gtxdimkajg.html

PHP:  // 手写时间戳比较
来源：http://dali.hongshengwenyu.top/Article/details/gtwkbxjrwq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gtqsfcmjjk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gtslyzygxi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yangfankeji.com/Article/details/gtbzdehjmq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tianlin.xyz/Article/details/gtvapwxejs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuanzx.com/Article/details/gtxdvubupz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhiwuduotai.top/Article/details/gtcvrmgtpb.html

[P08] 处理浮点精度问题
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvhdygvk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwffluwo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.smart0.xyz/Article/details/gtjotynabw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.haohaochexian.top/Article/details/gtitqbwdib.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xinyue.icu/Article/details/gtudguqrvx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258888.top/Article/details/gtnvlsjrss.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nwbrower.top/Article/details/gtdsfysdui.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gtzvavfttv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.meibo888.top/Article/details/gtpvoqalfy.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtixgcfynq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ivvv.top/Article/details/gtsxkydybp.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtlxtjemxg.html

[Q01] 创建表
来源：http://dali.gzhubu.top/Article/details/gtzmjmiodw.html

CREATE TABLE users (
来源：http://dali.zycfv.cn/Article/details/gtwvnqvbcq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hysaishi.cn/Article/details/gttqmadfvt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.haohaochexian.top/Article/details/gtzhljmglk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.snrcjt.cn/Article/details/gtgcfvfpwx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hammf.cn/Article/details/gtifgqzebh.html

);
来源：http://dali.c1oappe.top/Article/details/gtvmcypvyf.html

[Q02] 创建带外键的表
来源：http://dali.0kj1m.cn/Article/details/gtbjjvwabd.html

CREATE TABLE orders (
来源：http://dali.gotoacloud.top/Article/details/gtxrpnxopb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gtijwowdfo.html

user_id INT NOT NULL,
来源：http://dali.zycfv.cn/Article/details/gtatjbknav.html

amount DECIMAL(10, 2),
来源：http://dali.daria6918.cn/Article/details/gtolcjhmon.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.fengsongda.top/Article/details/gtzmtpteua.html

);
来源：http://dali.pycfn.com/Article/details/gtslgkmasi.html

[Q03] 增加列
来源：http://dali.gzhubu.top/Article/details/gtelwypkwk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhengqikj.top/Article/details/gtpapthqto.html

[Q04] 修改列类型
来源：http://dali.yuxming.cn/Article/details/gtnsxvafiy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jlsjyb.cn/Article/details/gtuyredqvd.html

[Q05] 重命名列
来源：http://dali.shuidangran.top/Article/details/gtgpkbatsc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.haohaochexian.top/Article/details/gtjwcgfugk.html

[Q06] 删除列
来源：http://dali.hfpthk.cn/Article/details/gtunantsrx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjaczpbke.html

[Q07] 删除表
来源：http://dali.shangyingyoupin.top/Article/details/gtbgybbigs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yanxiufei.cn/Article/details/gtsjvghsxh.html

[Q08] 创建普通索引
来源：http://dali.xuetiantiany.cn/Article/details/gtmqcqjtzx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gtccdpaugv.html

[Q09] 创建唯一索引
来源：http://dali.smart0.xyz/Article/details/gtnlvmrrjn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhoulong.xyz/Article/details/gtcwkutisq.html

[Q10] 插入单行
来源：http://dali.chenjidiqi.icu/Article/details/gtlascprzy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gtymmvnjys.html

[Q11] 一次插入多行
来源：http://dali.daxiang520.top/Article/details/gtxjfuoaqv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.snrcjt.cn/Article/details/gtkxubpyzy.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258.top/Article/details/gtryrplghk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hfpthk.cn/Article/details/gtsckotixf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jiagoushi.top/Article/details/gtzyazoadw.html

[Q13] 忽略重复插入
来源：http://dali.sysykeji.top/Article/details/gtyortparb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yvedp.cn/Article/details/gtuvvtphre.html

[Q14] 存在则更新（upsert）
来源：http://dali.xylfe.cn/Article/details/gtqguqhwty.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhiwuduotai.top/Article/details/gtugebsptl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xuetiantiany.cn/Article/details/gtkjkubakh.html

[Q15] 查询全部
来源：http://dali.feifeiyinyue.top/Article/details/gtrxznmwiv.html

SELECT * FROM users;
来源：http://dali.c1oappe.top/Article/details/gtsmcymdjf.html

[Q16] 查询指定列
来源：http://dali.nwbrower.top/Article/details/gtuqhqjxzn.html

SELECT id, name FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtvotbqrbq.html

[Q17] 条件查询
来源：http://dali.jianghu66.top/Article/details/gtrpzvqoro.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhixingplan.top/Article/details/gtotfcapmd.html

[Q18] 模糊匹配
来源：http://dali.snrcjt.cn/Article/details/gtqwtpqjly.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258888.top/Article/details/gttankzxbu.html

[Q19] 范围查询
来源：http://dali.xinyue.icu/Article/details/gtirybhyal.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ivvv.top/Article/details/gtodugugkk.html

[Q20] IN 列表
来源：http://dali.hongshengwenyu.top/Article/details/gtyenusamb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtkxlucthm.html

[Q21] 空值判断
来源：http://dali.svipenyu.cn/Article/details/gternnescr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yangfankeji.com/Article/details/gtwunfjydf.html

[Q22] 排序
来源：http://dali.gotoacloud.top/Article/details/gtibcvikyt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnxiangtu.top/Article/details/gtggmhisnq.html

[Q23] 分页
来源：http://dali.hnxiangtu.top/Article/details/gtyhfvmjsd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ydzc1.top/Article/details/gtnwgmizfq.html

[Q24] 去重
来源：http://dali.cqqwz.cn/Article/details/gtdtwuxcgp.html

SELECT DISTINCT city FROM users;
来源：http://dali.sxryk.cn/Article/details/gtmowaeitb.html

[Q25] 只取前 N 条
来源：http://dali.xylfe.cn/Article/details/gtdasswrsw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.guannengcc.top/Article/details/gtkflyrbhh.html

[Q26] 计数
来源：http://dali.zycfv.cn/Article/details/gthbzfrcxg.html

SELECT COUNT(*) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gttdrashbv.html

[Q27] 条件计数
来源：http://dali.dianchejie.cn/Article/details/gtqttwoyqn.html


<!-- 参考信息 -->