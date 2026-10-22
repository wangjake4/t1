代发 wailian999

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gt2rdrhaevc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gt2cpizfzlz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jianghu66.top/Article/details/gt2evxzebem.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2khwvkfzf.html

Ruby: arr.sort
来源：http://dali.pengpengdd.cyou/Article/details/gt2bdbgtmky.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gogol.net.cn/Article/details/gt2uxphmohj.html

[N03] 快速排序（分治示例）
来源：http://dali.yuanzhike.top/Article/details/gt2cjsuouny.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.c1oappe.top/Article/details/gt2nixuynga.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cashguo.top/Article/details/gt2qmhocpjm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gt2qsmvtvix.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jyoumei.cn/Article/details/gt2kcixfuwk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.mhx1999.top/Article/details/gt2eannycfn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jiagoushi.top/Article/details/gt2egeuvbgk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.snrcjt.cn/Article/details/gt2atiyefab.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xinyue.icu/Article/details/gt2fcqxkdmq.html

[N04] 斐波那契数列
来源：http://dali.aizwys.cn/Article/details/gt2spshrhut.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gt2vwnphgzh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.meibo888.top/Article/details/gt2mlbwtrpi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gt2uvarkezz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2hjzxdlzt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aizwys.cn/Article/details/gt2gppyfupu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.haohaochexian.top/Article/details/gt2snslfoys.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gt2vwrpyqpd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gt2mtczfdqq.html

[N05] 最大公约数
来源：http://dali.cdnleiting.top/Article/details/gt2imegtvxs.html

Py:   math.gcd(a, b)
来源：http://dali.jqgfzy.top/Article/details/gt2pmxotdwr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cheryme.top/Article/details/gt2lucokdvd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gt2ztxcxmqb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shuidangran.top/Article/details/gt2mvocluol.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jiagoushi.top/Article/details/gt2kgtwjjuo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vnyqxmyn.html

Ruby: a.gcd(b)
来源：http://dali.hysaishi.cn/Article/details/gt2dbpgboax.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2yokbwqto.html

[N06] 判断回文字符串
来源：http://dali.sufxvd.cn/Article/details/gt2bpkyhvem.html

Py:   s == s[::-1]
来源：http://dali.iojbl.cn/Article/details/gt2ovasfldo.html

PHP:  $s === strrev($s);
来源：http://dali.jinqigufen.top/Article/details/gt2thcigkzw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gt2ojminphv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2rpesgplx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hammf.cn/Article/details/gt2ohwxkmoa.html

Go:   // 双指针从两端比较
来源：http://dali.hammf.cn/Article/details/gt2qyiuskrl.html

Ruby: s == s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dtkxszhz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gt2irkjblnr.html

[N07] 两数之和（返回下标）
来源：http://dali.jyoumei.cn/Article/details/gt2lcpxjiod.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ppjwa.cn/Article/details/gt2qlfdssfd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnxiangtu.top/Article/details/gt2bwuuppkl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sxryk.cn/Article/details/gt2vompwwkj.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2btguyqhw.html

Java: // 手写 HashMap
来源：http://dali.tianlin.xyz/Article/details/gt2vbaniocx.html

Go:   // 手写 map[int]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2icuvmrlt.html

Ruby: // 手写 Hash
来源：http://dali.yj202588.top/Article/details/gt2plrdhrqv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zdqjudy.top/Article/details/gt2opjcnfrd.html

[N08] 生成全排列
来源：http://dali.hfpthk.cn/Article/details/gt2dadxnzcb.html

Py:   itertools.permutations(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ercptnqv.html

PHP:  // 手写递归交换
来源：http://dali.shuidangran.top/Article/details/gt2fqdnvkur.html

JS:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gt2yklimjgb.html

TS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gt2uoofgybb.html

Java: // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gt2lzyejvuv.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qmfwugin.html

Ruby: arr.permutation.to_a
来源：http://dali.smart0.xyz/Article/details/gt2lbkguqhk.html

C#:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gt2hennangg.html

[N09] 栈与队列
来源：http://dali.fengsongda.top/Article/details/gt2wuymtdcc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yvedp.cn/Article/details/gt2daxhqgnv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnqzz.top/Article/details/gt2vysfjcur.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gt2hsydtsvi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.vqdsnc.cn/Article/details/gt2gkeerqfj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cucudq.cn/Article/details/gt2ojpeomdy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gzhubu.top/Article/details/gt2ysecfihv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sysykeji.top/Article/details/gt2zppvdqkl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuanzx.com/Article/details/gt2nwloelob.html

[N10] 链表节点定义
来源：http://dali.hnxiangtu.top/Article/details/gt2uiscjetj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fzhhl.top/Article/details/gt2iikxqhlo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.smart0.xyz/Article/details/gt2vxuudstm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.c1oappe.top/Article/details/gt2jmlnbnwm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhengqikj.top/Article/details/gt2udllmmea.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigfzy.top/Article/details/gt2dwzsnuul.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ivvv.top/Article/details/gt2obhcgmnn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guowangkeji.top/Article/details/gt2lopskwzg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.0kj1m.cn/Article/details/gt2euedxmdi.html

[N11] 二叉树中序遍历
来源：http://dali.yuxming.cn/Article/details/gt2btuvxair.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vcdgyuig.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gt2hrtdqlct.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yonumen.top/Article/details/gt2vmdeoljj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gt2mqbiqtjv.html

Java: // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gt2qebrekbx.html

Go:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ropqzqrd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nanxuanxn.top/Article/details/gt2ryjppfns.html

C#:   // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gt2pzqddxke.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnxiangtu.top/Article/details/gt2bpbqjhuc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.pycfn.com/Article/details/gt2ufggslyj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.quarkkingdee.top/Article/details/gt2armgabzi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gt2mzqcnboo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gt2issytfgc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gt2usvdcvda.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sxryk.cn/Article/details/gt2runkmzfj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ybcxt.top/Article/details/gt2cdeqkcnz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gt2wmsokktl.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2xknfiuuq.html

O. 并发与异步
来源：http://dali.ehwqpu.com/Article/details/gt2xvjkghld.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2aetgxpcf.html

[O01] 启动一个线程
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tninjwxq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pengpengdd.cyou/Article/details/gt2elgxaijj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.smart0.xyz/Article/details/gt2pcvornrl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.havefunace.top/Article/details/gt2xhgdhfvz.html

TS:   // 同 JS
来源：http://dali.daria6918.cn/Article/details/gt2twrqzrwp.html

Java: new Thread(() -> f()).start()
来源：http://dali.316326.xyz/Article/details/gt2vplgqpri.html

Go:   go f()
来源：http://dali.jqgufenzy.top/Article/details/gt2ovvfoxjm.html

Ruby: Thread.new { f }
来源：http://dali.daxiang520.top/Article/details/gt2qaasrqgd.html

C#:   Task.Run(() => F());
来源：http://dali.kuanghao11.cn/Article/details/gt2ktdaifml.html

[O02] 使用线程池
来源：http://dali.wangdashe.top/Article/details/gt2aaefyomo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.pycfn.com/Article/details/gt2mszocgqx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.birdmap.top/Article/details/gt2nqlhtwfc.html

JS:   // worker_threads 线程池
来源：http://dali.kuanghao11.cn/Article/details/gt2dviqyngi.html

TS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gt2qxamxror.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ehwqpu.com/Article/details/gt2xdtpxjvl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zdqjudy.top/Article/details/gt2hklgvqdu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ehwqpu.com/Article/details/gt2zmrrrxws.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.kuanghao11.cn/Article/details/gt2wfskcovm.html

[O03] 加锁保护共享数据
来源：http://dali.jqgfzy.top/Article/details/gt2nieuwjbs.html

Py:   with lock: shared += 1
来源：http://dali.snrcjt.cn/Article/details/gt2qijlkmoa.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tian-w.cn/Article/details/gt2thsntqbu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dashuyun.cn/Article/details/gt2ersodqmm.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gt2xklddcjj.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxuanxn.top/Article/details/gt2xfdtioxl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gotoacloud.top/Article/details/gt2zetwgtcg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zycfv.cn/Article/details/gt2pnbztmst.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2raflnhep.html

[O04] 定义异步函数并等待
来源：http://dali.jiagoushi.top/Article/details/gt2ogskkmcl.html

Py:   async def f():⏎    await g()
来源：http://dali.chenzaomai.com/Article/details/gt2snfrwejx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.feifeiyinyue.top/Article/details/gt2gfxybxkk.html

JS:   async function f() { await g(); }
来源：http://dali.xylfe.cn/Article/details/gt2oxwboszx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cashguo.top/Article/details/gt2avsqvfbm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.havefunace.top/Article/details/gt2erbttnve.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenlongwang.top/Article/details/gt2oflpoann.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daxiang520.top/Article/details/gt2rmqsbope.html

C#:   async Task F() { await G(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xizqbhrt.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenlongwang.top/Article/details/gt2bqkbkdmx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hfpthk.cn/Article/details/gt2qdtlrpbq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.bjfxy.top/Article/details/gt2uutyafap.html

JS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gt2zsbwbwnm.html

TS:   await Promise.all(tasks)
来源：http://dali.chenzaomai.com/Article/details/gt2umqkthgn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zdqjudy.top/Article/details/gt2racvslww.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnxiangtu.top/Article/details/gt2jehgrwjb.html

Ruby: threads.map(&:join)
来源：http://dali.hywenlv.cn/Article/details/gt2wkbxfjlp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.vqdsnc.cn/Article/details/gt2wadsffwk.html

[O06] 使用进程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hebbaymt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ivvv.top/Article/details/gt2drforkxp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rrydihqr.html

JS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gt2amjybdxu.html

TS:   // child_process / cluster 模块
来源：http://dali.chenzaomai.com/Article/details/gt2thgfbabg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zycfv.cn/Article/details/gt2wcqyatgk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.kuanghao11.cn/Article/details/gt2vrbksgaq.html

Ruby: // fork 块
来源：http://dali.hnxiangtu.top/Article/details/gt2crvtauqg.html

C#:   Parallel.For
来源：http://dali.nwbrower.top/Article/details/gt2hefjtjts.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2acrpjhyp.html

P. 常用工具函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2ercpoekr.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2hmjnuoej.html

[P01] 生成 UUID
来源：http://dali.jqgfzy.top/Article/details/gt2scnuwmdf.html

Py:   str(uuid.uuid4())
来源：http://dali.snrcjt.cn/Article/details/gt2fyrxeguo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.c1oappe.top/Article/details/gt2buifxoci.html

JS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gt2zggwndjo.html

TS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gt2uygjtelq.html

Java: UUID.randomUUID().toString()
来源：http://dali.gzhubu.top/Article/details/gt2capcgjus.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jiagoushi.top/Article/details/gt2qhybbjbb.html

Ruby: SecureRandom.uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ybakahxv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2qfxgjheq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258.top/Article/details/gt2phwcfbkm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sxryk.cn/Article/details/gt2fjqsvgym.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2veiobgfx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shuidangran.top/Article/details/gt2bdmpelao.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.fengsongda.top/Article/details/gt2xbyjjvyq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sxryk.cn/Article/details/gt2vacmwubm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shangyingyoupin.top/Article/details/gt2aqiildpe.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ppjwa.cn/Article/details/gt2vkngzcdw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pengpengdd.cyou/Article/details/gt2abwpngiy.html

[P03] 生成短随机字符串
来源：http://dali.xinyue.icu/Article/details/gt2mtocovsw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hongshengwenyu.top/Article/details/gt2gizzkbnv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.c1oappe.top/Article/details/gt2ecvzxkxg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.snrcjt.cn/Article/details/gt2fkkbijxo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.0kj1m.cn/Article/details/gt2ylsohpgt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jiagoushi.top/Article/details/gt2wonzbbxn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pycfn.com/Article/details/gt2zmllpcoc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dianchejie.cn/Article/details/gt2qpfqliti.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ehwqpu.com/Article/details/gt2jjingzus.html

[P04] 求长度
来源：http://dali.fengsongda.top/Article/details/gt2vapuujdm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yanxiufei.cn/Article/details/gt2wrmmxmsv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gt2rdglvqaf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gt2sxkqiaac.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.snrcjt.cn/Article/details/gt2gcnamtai.html

Java: list.size();  map.size();  s.length()
来源：http://dali.fzhhl.top/Article/details/gt2slgzpzvu.html

Go:   len(arr);  len(m)
来源：http://dali.yonumen.top/Article/details/gt2ikquscwt.html

Ruby: x.length;  x.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lohxpish.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cucudq.cn/Article/details/gt2brmufsxh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.c1oappe.top/Article/details/gt2fqdmeuvo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.redwolf501.top/Article/details/gt2bubalmwn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gotoacloud.top/Article/details/gt2dvbrsoof.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guowangkeji.top/Article/details/gt2odgobvfs.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shzxlz.cn/Article/details/gt2fgutnsgb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tianlin.xyz/Article/details/gt2qoiwvooy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.meibo888.top/Article/details/gt2azsaygaw.html

Ruby: a == b
来源：http://dali.jqgfzy.top/Article/details/gt2cjwbkfoz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shuidangran.top/Article/details/gt2jrqjgdhm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.316326.xyz/Article/details/gt2ewgrspvr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xylfe.cn/Article/details/gt2zrzwcawo.html

PHP:  if (empty($x)) {}
来源：http://dali.ivvv.top/Article/details/gt2bkyxqdtr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sweek.top/Article/details/gt2mvemxszk.html

TS:   if (x == null) {}
来源：http://dali.aizwys.cn/Article/details/gt2hlcswqsi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2cwvvrpsj.html

Go:   if x == nil {}
来源：http://dali.0kj1m.cn/Article/details/gt2pnddbfyx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ybcxt.top/Article/details/gt2jxkykiqo.html

C#:   if (x is null) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2vjamedop.html

[P07] 防抖与节流
来源：http://dali.aibaodan.cn/Article/details/gt2hriusmii.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jiagoushi.top/Article/details/gt2pehcsfpj.html

PHP:  // 手写时间戳比较
来源：http://dali.xziqi.cn/Article/details/gt2zjeygnit.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gt2ouvcxhwa.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cheryme.top/Article/details/gt2uzcgamxr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cucudq.cn/Article/details/gt2dmmkdtad.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wqqfamda.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jqgfzy.top/Article/details/gt2vsqlkxrp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xylfe.cn/Article/details/gt2rqjbnysj.html

[P08] 处理浮点精度问题
来源：http://dali.daxiang520.top/Article/details/gt2gzebwrti.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ydzc1.top/Article/details/gt2mfhxlrhu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2grgubyew.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jyoumei.cn/Article/details/gt2vcagcnio.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jyoumei.cn/Article/details/gt2rtfnsbyf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xziqi.cn/Article/details/gt2wuxvicsh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shangyingyoupin.top/Article/details/gt2qjfpaknf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tian-w.cn/Article/details/gt2lzqgqweq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pycfn.com/Article/details/gt2pzwintnc.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2httdhcrt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgufenzy.top/Article/details/gt2kumzzieo.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2wvyoftwr.html

[Q01] 创建表
来源：http://dali.guannengcc.top/Article/details/gt2wlcsmeos.html

CREATE TABLE users (
来源：http://dali.andypj.xyz/Article/details/gt2fgcrpqlp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhongyouzk.top/Article/details/gt2zlvqkgnz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sxryk.cn/Article/details/gt2wknrllxx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.daxiang520.top/Article/details/gt2edweqvbj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.0kj1m.cn/Article/details/gt2gmhnskqk.html

);
来源：http://dali.aibaodan.cn/Article/details/gt2njuavhul.html

[Q02] 创建带外键的表
来源：http://dali.yj202588.top/Article/details/gt2iymixjau.html

CREATE TABLE orders (
来源：http://dali.fengsongda.top/Article/details/gt2dmvxxikq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xylfe.cn/Article/details/gt2patovdvp.html

user_id INT NOT NULL,
来源：http://dali.yonumen.top/Article/details/gt2kfwukkrg.html

amount DECIMAL(10, 2),
来源：http://dali.c1oappe.top/Article/details/gt2ftxpisme.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnxiangtu.top/Article/details/gt2ndberliv.html

);
来源：http://dali.zhixingplan.top/Article/details/gt2lretfbwm.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ialkvahg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxuanxn.top/Article/details/gt2hadevjir.html

[Q04] 修改列类型
来源：http://dali.zycfv.cn/Article/details/gt2xfauzydd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nanxinkj.top/Article/details/gt2qimdiaby.html

[Q05] 重命名列
来源：http://dali.chenlongwang.top/Article/details/gt2sqlfbkpw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2qqkxsnwi.html

[Q06] 删除列
来源：http://dali.yj20258888.top/Article/details/gt2nddgxizs.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jlsjyb.cn/Article/details/gt2awbmkabs.html

[Q07] 删除表
来源：http://dali.zhoulong.xyz/Article/details/gt2ojijzphg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ydzc1.top/Article/details/gt2zcpgyorh.html

[Q08] 创建普通索引
来源：http://dali.yuanzhike.top/Article/details/gt2zkgnwdto.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dwuocove.html

[Q09] 创建唯一索引
来源：http://dali.smart0.xyz/Article/details/gt2pvpeenbz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gt2qvjgdgtw.html

[Q10] 插入单行
来源：http://dali.nanxinkj.top/Article/details/gt2jthkbdsr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.snrcjt.cn/Article/details/gt2bqjnahbx.html

[Q11] 一次插入多行
来源：http://dali.ehwqpu.com/Article/details/gt2slxappoj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuxming.cn/Article/details/gt2opothjxn.html

[Q12] 插入后取自增 ID
来源：http://dali.shzxlz.cn/Article/details/gt2jtvwuzci.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aizwys.cn/Article/details/gt2iblhjmag.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xsbvycpk.html

[Q13] 忽略重复插入
来源：http://dali.shuidangran.top/Article/details/gt2bpeddvzr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.meibo888.top/Article/details/gt2cepciqdz.html

[Q14] 存在则更新（upsert）
来源：http://dali.shzxlz.cn/Article/details/gt2oiukhiid.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgfzy.top/Article/details/gt2gzywdkow.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.wangshuangyany.cn/Article/details/gt2gpcfmuhg.html

[Q15] 查询全部
来源：http://dali.nanxinkj.top/Article/details/gt2uugrihrn.html

SELECT * FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2eawfrgnq.html

[Q16] 查询指定列
来源：http://dali.cdnleiting.top/Article/details/gt2tzuyoegr.html

SELECT id, name FROM users;
来源：http://dali.pycfn.com/Article/details/gt2jqwxvowk.html

[Q17] 条件查询
来源：http://dali.smart0.xyz/Article/details/gt2uwmuflft.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2gkuwvkiy.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpncgqk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.kuanghao11.cn/Article/details/gt2znyytgcg.html

[Q19] 范围查询
来源：http://dali.jiagoushi.top/Article/details/gt2muokvdwt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tanke756.top/Article/details/gt2afgmbbdv.html

[Q20] IN 列表
来源：http://dali.yuxming.cn/Article/details/gt2eanljkhs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2lvesvhfb.html

[Q21] 空值判断
来源：http://dali.yonumen.top/Article/details/gt2fszczqwk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.andypj.xyz/Article/details/gt2blbmgijp.html

[Q22] 排序
来源：http://dali.sxryk.cn/Article/details/gt2tvwocjdl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nanxinkj.top/Article/details/gt2cnvuhrvp.html

[Q23] 分页
来源：http://dali.chenzaomai.com/Article/details/gt2mhqncsqr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nanxuanxn.top/Article/details/gt2jckrzaql.html

[Q24] 去重
来源：http://dali.aibaodan.cn/Article/details/gt2gbngfbff.html

SELECT DISTINCT city FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2lyjnfoyz.html

[Q25] 只取前 N 条
来源：http://dali.cheryme.top/Article/details/gt2hfvdikwg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cashguo.top/Article/details/gt2pzuduayl.html

[Q26] 计数
来源：http://dali.zdqjudy.top/Article/details/gt2yfnunjod.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2ltciblms.html

[Q27] 条件计数
来源：http://dali.yuxming.cn/Article/details/gt2xdqaycao.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2sbrklwcz.html

[Q28] 求和与平均
来源：http://dali.chenlongwang.top/Article/details/gt2nocaqxme.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2ddxbvhmo.html

[Q29] 最大最小值
来源：http://dali.jinqigufen.top/Article/details/gt2neforrxs.html


<!-- 参考信息 -->