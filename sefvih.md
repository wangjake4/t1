代发 wailian999

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtubueiocd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gtkherpwwj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhengqikj.top/Article/details/gtemttvrtj.html

Go:   slices.Sort(arr)
来源：http://dali.tianlin.xyz/Article/details/gtcakpqylx.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gtmddzyijm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenjidiqi.icu/Article/details/gtcjiwmiqm.html

[N03] 快速排序（分治示例）
来源：http://dali.cqqwz.cn/Article/details/gtxlbreiol.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.bjfxy.top/Article/details/gtppnqnuol.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jlsjyb.cn/Article/details/gthnlkxoqi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fengsongda.top/Article/details/gtjljmwbdu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gthuuyxnkb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jianghu66.top/Article/details/gtoqurhfbd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daxiang520.top/Article/details/gtrstrukvv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guannengcc.top/Article/details/gtkwfowjrv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.havefunace.top/Article/details/gttwxntkax.html

[N04] 斐波那契数列
来源：http://dali.cheryme.top/Article/details/gtqhsxptnv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gogol.net.cn/Article/details/gtgistmgoj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xziqi.cn/Article/details/gtuoorkihu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtixtsziwm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtxwzbiwxe.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtulmawtmf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgxvwhsa.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gtykpcavio.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbnahhqmr.html

[N05] 最大公约数
来源：http://dali.sxryk.cn/Article/details/gtprwbafyk.html

Py:   math.gcd(a, b)
来源：http://dali.sysykeji.top/Article/details/gticovyocd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cucudq.cn/Article/details/gtycmlrdkk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gtftsdozka.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpfjajdpz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.kuanghao11.cn/Article/details/gtvbzjrter.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hysaishi.cn/Article/details/gtnkyvxmhy.html

Ruby: a.gcd(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjncuvqyz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daxiang520.top/Article/details/gtbmnkknev.html

[N06] 判断回文字符串
来源：http://dali.svipenyu.cn/Article/details/gtmxqhjvkb.html

Py:   s == s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gtazfwsjya.html

PHP:  $s === strrev($s);
来源：http://dali.aizwys.cn/Article/details/gtvprafebj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtmkbingkn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtrarmselm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nwbrower.top/Article/details/gtxcpafozs.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gtwelxdnzw.html

Ruby: s == s.reverse
来源：http://dali.sxryk.cn/Article/details/gtpitabifr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yonumen.top/Article/details/gthjgoocfm.html

[N07] 两数之和（返回下标）
来源：http://dali.shuidangran.top/Article/details/gtbiicvumv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shzxlz.cn/Article/details/gtostngyjv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yonumen.top/Article/details/gtpwrroatf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.smart0.xyz/Article/details/gtzpjlflbd.html

TS:   // 手写 Map<string, number>
来源：http://dali.yanxiufei.cn/Article/details/gtcyxsdpfp.html

Java: // 手写 HashMap
来源：http://dali.fengsongda.top/Article/details/gtsgmjbrjt.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gthxwzpkhj.html

Ruby: // 手写 Hash
来源：http://dali.wangdashe.top/Article/details/gtpcjnxzhj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shuidangran.top/Article/details/gtvhkxeupp.html

[N08] 生成全排列
来源：http://dali.tanke756.top/Article/details/gteouvxtfq.html

Py:   itertools.permutations(arr)
来源：http://dali.zycfv.cn/Article/details/gtephoywvs.html

PHP:  // 手写递归交换
来源：http://dali.xuanzx.com/Article/details/gtskgzhput.html

JS:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtasntfnlg.html

TS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtthphyweh.html

Java: // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtxypokvjs.html

Go:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtnymumdiv.html

Ruby: arr.permutation.to_a
来源：http://dali.yuanzhike.top/Article/details/gtoukrujpf.html

C#:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtpedmvcgy.html

[N09] 栈与队列
来源：http://dali.nwbrower.top/Article/details/gtpvynygoy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aizwys.cn/Article/details/gthnjqhilg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtbigbuvql.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtqpghxlit.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.pycfn.com/Article/details/gtkzbrhvwr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnqzz.top/Article/details/gtfprfezuy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.redwolf501.top/Article/details/gtmpryoigh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gtrjmzkpzo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj202588.top/Article/details/gtxzlyirid.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwqsfkbgp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nwbrower.top/Article/details/gtbspguwig.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jlsjyb.cn/Article/details/gtyzukynxg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.iojbl.cn/Article/details/gtmbyvaicc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cqqwz.cn/Article/details/gtlfssnpgb.html

Java: class Node { int v; Node next; }
来源：http://dali.shuidangran.top/Article/details/gtsokajqeh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangshuangyany.cn/Article/details/gthojutafp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfscmqlo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gaohongyu789.top/Article/details/gtohnnvpff.html

[N11] 二叉树中序遍历
来源：http://dali.9152youxi.cn/Article/details/gtufubbupy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.feifeiyinyue.top/Article/details/gttouyzntg.html

PHP:  // 手写递归函数
来源：http://dali.nanxuanxn.top/Article/details/gtbfhhocyu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gtkpmanshk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gtpgnoejxw.html

Java: // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gtyjmjancy.html

Go:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gtjhrynfqf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhixingplan.top/Article/details/gtpbzwgwgf.html

C#:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gtupyouqed.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cheryme.top/Article/details/gtltxynmjy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcgvpzdh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ybcxt.top/Article/details/gtkoqztlsk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gtmsmyrija.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ppjwa.cn/Article/details/gtlioqmlho.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gtspwoogkr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cqqwz.cn/Article/details/gtmshydnwz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenlongwang.top/Article/details/gtyaxqvqwh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhengqikj.top/Article/details/gtkoyhgoqi.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtevcehaoo.html

O. 并发与异步
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrydlvavn.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtvcvxvdvb.html

[O01] 启动一个线程
来源：http://dali.smart0.xyz/Article/details/gtjlqsqmhm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.guannengcc.top/Article/details/gtfqvimbzd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.vqdsnc.cn/Article/details/gthonnhmtj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hfpthk.cn/Article/details/gtjghulsta.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gteumystth.html

Java: new Thread(() -> f()).start()
来源：http://dali.aibaodan.cn/Article/details/gtzywhyjvm.html

Go:   go f()
来源：http://dali.nanxuanxn.top/Article/details/gtjaknumdd.html

Ruby: Thread.new { f }
来源：http://dali.smart0.xyz/Article/details/gtojnyzbgp.html

C#:   Task.Run(() => F());
来源：http://dali.ivvv.top/Article/details/gtqnkkoqxn.html

[O02] 使用线程池
来源：http://dali.sxryk.cn/Article/details/gthmmestqa.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxinkj.top/Article/details/gtdssqmxnw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgufenzy.top/Article/details/gtgzqyigqv.html

JS:   // worker_threads 线程池
来源：http://dali.xylfe.cn/Article/details/gtkrlqabzu.html

TS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gtkppxexmb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigfzy.top/Article/details/gtjdfmwrbe.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aibaodan.cn/Article/details/gtqsfbyubw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqsnyggm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.mhx1999.top/Article/details/gthwlgobnm.html

[O03] 加锁保护共享数据
来源：http://dali.zdqjudy.top/Article/details/gtzqducooa.html

Py:   with lock: shared += 1
来源：http://dali.yvedp.cn/Article/details/gtaqymaynp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guowangkeji.top/Article/details/gtdmanxzav.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cdnleiting.top/Article/details/gtsqkmcmrd.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gtegxcdspb.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnxiangtu.top/Article/details/gtlkdgmswt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cheryme.top/Article/details/gtyonohaxf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinqigufen.top/Article/details/gtlubjryiq.html

C#:   lock (gate) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gtqmgwajnt.html

[O04] 定义异步函数并等待
来源：http://dali.hongshengwenyu.top/Article/details/gtkgrqdrgx.html

Py:   async def f():⏎    await g()
来源：http://dali.hammf.cn/Article/details/gtctnjhxsi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj202588.top/Article/details/gteaaodcgo.html

JS:   async function f() { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgbtsvta.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jlsjyb.cn/Article/details/gtmatltjmw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.kuanghao11.cn/Article/details/gthhmwopnn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yvedp.cn/Article/details/gtpbfafabp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yonumen.top/Article/details/gtkgtjbcjg.html

C#:   async Task F() { await G(); }
来源：http://dali.wangdashe.top/Article/details/gtwbvwzvgv.html

[O05] 并发执行并等待全部完成
来源：http://dali.shangyingyoupin.top/Article/details/gtxrjsesgt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgufenzy.top/Article/details/gtjipijqrl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pengpengdd.cyou/Article/details/gtbokdxqtv.html

JS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gtbuiiofpu.html

TS:   await Promise.all(tasks)
来源：http://dali.sweek.top/Article/details/gtevxpnrii.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblunqwhi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.haohaochexian.top/Article/details/gtsotdewtx.html

Ruby: threads.map(&:join)
来源：http://dali.yangfankeji.com/Article/details/gtimluxbuj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shuidangran.top/Article/details/gtfucyqhxi.html

[O06] 使用进程池
来源：http://dali.haohaochexian.top/Article/details/gtzaoenplv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hysaishi.cn/Article/details/gtrijplazm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yvedp.cn/Article/details/gtmzuxckji.html

JS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gtygupuztz.html

TS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gtqekfndhi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gtrghadwmv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cheryme.top/Article/details/gtxvuceueo.html

Ruby: // fork 块
来源：http://dali.nanxuanxn.top/Article/details/gtpyrdjpaq.html

C#:   Parallel.For
来源：http://dali.shzxlz.cn/Article/details/gtlswraizh.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtqpmfyryl.html

P. 常用工具函数
来源：http://dali.pengpengdd.cyou/Article/details/gthuzksgip.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtdfxkflmx.html

[P01] 生成 UUID
来源：http://dali.shuidangran.top/Article/details/gtbkafglmw.html

Py:   str(uuid.uuid4())
来源：http://dali.iojbl.cn/Article/details/gtpzhxzpne.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shangyingyoupin.top/Article/details/gtmdmqizrb.html

JS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtilukygwh.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gtdetddogx.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnxiangtu.top/Article/details/gtveukoevo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yangfankeji.com/Article/details/gtbmymqraq.html

Ruby: SecureRandom.uuid
来源：http://dali.chenlongwang.top/Article/details/gtqmzujsot.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jqgufenzy.top/Article/details/gtyaifiuyd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuxming.cn/Article/details/gtjhyyzcqa.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.meibo888.top/Article/details/gtlszanqsy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258.top/Article/details/gtusfuoxeo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzcmlyua.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuanzhike.top/Article/details/gtihlzflhh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.fzhhl.top/Article/details/gtgkgglhyz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.quarkkingdee.top/Article/details/gtwvxcknmt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigfzy.top/Article/details/gttcekswtc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.c1oappe.top/Article/details/gtyoftoynp.html

[P03] 生成短随机字符串
来源：http://dali.ydzc1.top/Article/details/gttrwzwfqv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zdqjudy.top/Article/details/gtwmemqlzo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shangyingyoupin.top/Article/details/gtveogdiqx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtjnmyariv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gtaxarhydo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jiagoushi.top/Article/details/gtsvaackzu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xylfe.cn/Article/details/gtryysoizc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.andypj.xyz/Article/details/gtdnqyxyab.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hongshengwenyu.top/Article/details/gthtabecxq.html

[P04] 求长度
来源：http://dali.cashguo.top/Article/details/gtpadnxuch.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cucudq.cn/Article/details/gtmbtuamfg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtpilcunvd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shzxlz.cn/Article/details/gtejucokyt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gtssklxuzp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shzxlz.cn/Article/details/gtefmrsbvd.html

Go:   len(arr);  len(m)
来源：http://dali.havefunace.top/Article/details/gtmrwzoxbf.html

Ruby: x.length;  x.size
来源：http://dali.sysykeji.top/Article/details/gtoysnsqwh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.svipenyu.cn/Article/details/gtmeitcbzi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.meibo888.top/Article/details/gtezjgpbmm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj202588.top/Article/details/gttjfaivrg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yvedp.cn/Article/details/gtixxwgnqe.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hfpthk.cn/Article/details/gtogjywdgl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ybcxt.top/Article/details/gteknxapjx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuetiantiany.cn/Article/details/gtyeqtodli.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtjkoxhwfa.html

Ruby: a == b
来源：http://dali.hongshengwenyu.top/Article/details/gtqnysmmjx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhoulong.xyz/Article/details/gtzuhluafs.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwptxtkj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sxryk.cn/Article/details/gtexensbea.html

PHP:  if (empty($x)) {}
来源：http://dali.iojbl.cn/Article/details/gteclcgbbc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.svipenyu.cn/Article/details/gtsmksjifr.html

TS:   if (x == null) {}
来源：http://dali.cdnleiting.top/Article/details/gtqbsvbztd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gtlqrrxlcj.html

Go:   if x == nil {}
来源：http://dali.dashuyun.cn/Article/details/gtcybdaeyl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinqigfzy.top/Article/details/gtacrsduwt.html

C#:   if (x is null) {}
来源：http://dali.zhoulong.xyz/Article/details/gtdiitglxy.html

[P07] 防抖与节流
来源：http://dali.xuanzx.com/Article/details/gtnmlrmslv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.fengsongda.top/Article/details/gtjzuzirav.html

PHP:  // 手写时间戳比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzpybhun.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gtklyekylk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtfihghpws.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgufenzy.top/Article/details/gtkzexrvmc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pengpengdd.cyou/Article/details/gtpjmdnfct.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dashuyun.cn/Article/details/gttlhstuoq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.kuanghao11.cn/Article/details/gtkabtivob.html

[P08] 处理浮点精度问题
来源：http://dali.cashguo.top/Article/details/gtvbcirwma.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sweek.top/Article/details/gtzeixdrxr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.vqdsnc.cn/Article/details/gtvperuhru.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.9152youxi.cn/Article/details/gttsvmttga.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjryrgdk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangdashe.top/Article/details/gtpkhxnzdx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuanzhike.top/Article/details/gtqfmrlfkk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jqgfzy.top/Article/details/gtnqmcacct.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yanxiufei.cn/Article/details/gtqjaaxrrr.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtlwxbskqk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ybcxt.top/Article/details/gtcxgoxxql.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtiotjpmnh.html

[Q01] 创建表
来源：http://dali.sysykeji.top/Article/details/gtqwkwmysc.html

CREATE TABLE users (
来源：http://dali.guannengcc.top/Article/details/gthvmwkisk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxinkj.top/Article/details/gtihrxvkhb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gtfsqtvbmc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.svipenyu.cn/Article/details/gtwjpahfld.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.guowangkeji.top/Article/details/gtpqpzywcc.html

);
来源：http://dali.havefunace.top/Article/details/gttanmcopk.html

[Q02] 创建带外键的表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagxkfoic.html

CREATE TABLE orders (
来源：http://dali.cheryme.top/Article/details/gtvsdydcsd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gtsszwbmxg.html

user_id INT NOT NULL,
来源：http://dali.316326.xyz/Article/details/gtabtgmsas.html

amount DECIMAL(10, 2),
来源：http://dali.pycfn.com/Article/details/gtbgmlxofe.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jlsjyb.cn/Article/details/gtwjabhiwl.html

);
来源：http://dali.yj20258888.top/Article/details/gtzhxjsycq.html

[Q03] 增加列
来源：http://dali.jqgfzy.top/Article/details/gtkdnracuz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tianlin.xyz/Article/details/gtsyjfnksv.html

[Q04] 修改列类型
来源：http://dali.gotoacloud.top/Article/details/gtmjwjaowo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgfzy.top/Article/details/gtfdxzcwli.html

[Q05] 重命名列
来源：http://dali.chenzaomai.com/Article/details/gtiuxazeau.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenzaomai.com/Article/details/gtjtpegken.html

[Q06] 删除列
来源：http://dali.316326.xyz/Article/details/gtvpjxpzce.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tianlin.xyz/Article/details/gtdllrcprm.html

[Q07] 删除表
来源：http://dali.cqqwz.cn/Article/details/gtrstnzynf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nanxuanxn.top/Article/details/gtvaimbytq.html

[Q08] 创建普通索引
来源：http://dali.yj20258888.top/Article/details/gtbqbtwdyu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj20258.top/Article/details/gtfmaiifpn.html

[Q09] 创建唯一索引
来源：http://dali.hongshengwenyu.top/Article/details/gtjncdpnyy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gtjlnntgsc.html

[Q10] 插入单行
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbykxdkb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gtanfgrgnf.html

[Q11] 一次插入多行
来源：http://dali.wangdashe.top/Article/details/gtomhxuusp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtvzofjzgu.html

[Q12] 插入后取自增 ID
来源：http://dali.chenjidiqi.icu/Article/details/gtcdmukbsx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.andypj.xyz/Article/details/gtpctskhau.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hammf.cn/Article/details/gtnzispkvr.html

[Q13] 忽略重复插入
来源：http://dali.zhoulong.xyz/Article/details/gtbbszbwus.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzdjcsat.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuetiantiany.cn/Article/details/gtqrjrqlki.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ehwqpu.com/Article/details/gtqelmtack.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ydzc1.top/Article/details/gtdboytxpw.html

[Q15] 查询全部
来源：http://dali.zycfv.cn/Article/details/gtlawupvqe.html

SELECT * FROM users;
来源：http://dali.sweek.top/Article/details/gtpyxbwfqa.html

[Q16] 查询指定列
来源：http://dali.zhixingplan.top/Article/details/gtrxijyknn.html

SELECT id, name FROM users;
来源：http://dali.yonumen.top/Article/details/gtueuxzawu.html

[Q17] 条件查询
来源：http://dali.haohaochexian.top/Article/details/gtrsnxsbwz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.9152youxi.cn/Article/details/gtgdicgntf.html

[Q18] 模糊匹配
来源：http://dali.cqqwz.cn/Article/details/gtfmdsgcju.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hysaishi.cn/Article/details/gtghbypjzt.html

[Q19] 范围查询
来源：http://dali.mhx1999.top/Article/details/gtbktebmpl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xziqi.cn/Article/details/gtpllhqveb.html

[Q20] IN 列表
来源：http://dali.shuidangran.top/Article/details/gtgveazxod.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgfzy.top/Article/details/gtbdjtmmdh.html

[Q21] 空值判断
来源：http://dali.xinyue.icu/Article/details/gtvyxdpyme.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gaohongyu789.top/Article/details/gtcgilxdrj.html

[Q22] 排序
来源：http://dali.chenzaomai.com/Article/details/gteuzzbsxa.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nwbrower.top/Article/details/gthwfoxyot.html

[Q23] 分页
来源：http://dali.yangfankeji.com/Article/details/gttwjkzgec.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj202588.top/Article/details/gtvhkquhks.html

[Q24] 去重
来源：http://dali.yonumen.top/Article/details/gtngeyfklj.html

SELECT DISTINCT city FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtwjonbnba.html

[Q25] 只取前 N 条
来源：http://dali.yuxming.cn/Article/details/gtwdoglwbv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yangfankeji.com/Article/details/gtxplxtrcx.html

[Q26] 计数
来源：http://dali.jyoumei.cn/Article/details/gtmkhqtatd.html

SELECT COUNT(*) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtithqszja.html

[Q27] 条件计数
来源：http://dali.andypj.xyz/Article/details/gtufqyyrou.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtxtukiyqv.html

[Q28] 求和与平均
来源：http://dali.yanxiufei.cn/Article/details/gtqhygqplh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtqtzzcpxm.html

[Q29] 最大最小值
来源：http://dali.ppjwa.cn/Article/details/gtbwgrxjbv.html


<!-- 参考信息 -->