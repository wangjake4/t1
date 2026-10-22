代发 wailian999

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtgpjgwauz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangshuangyany.cn/Article/details/gthufajawp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gtgoqcprnw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sxryk.cn/Article/details/gtbvdujxab.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gtxlnhddms.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gtfavmuxfm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yangfankeji.com/Article/details/gttopovruf.html

Go:   slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gtmedagunl.html

Ruby: arr.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsafuiusb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhongyouzk.top/Article/details/gtvpbrzyzk.html

[N03] 快速排序（分治示例）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtzwmvfo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gotoacloud.top/Article/details/gtuqnoqawp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yueranfly.top/Article/details/gtrctuxnrl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ehwqpu.com/Article/details/gtiwjfbpsu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gtyuyrtxyx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daria6918.cn/Article/details/gtvajjduij.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhengqikj.top/Article/details/gtidygjmzm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.bjfxy.top/Article/details/gtfxelxfee.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.vqdsnc.cn/Article/details/gtbtzmqswb.html

[N04] 斐波那契数列
来源：http://dali.tian-w.cn/Article/details/gtkmpxilgr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gtmdyjryds.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cucudq.cn/Article/details/gtflmtonto.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gtrhpodsgg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gttyzwqjcc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuanzx.com/Article/details/gtksxxdswd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.vqdsnc.cn/Article/details/gtwozleljw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ehwqpu.com/Article/details/gtkbtzgnnq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtofddgfup.html

[N05] 最大公约数
来源：http://dali.yuxming.cn/Article/details/gtahtaezbf.html

Py:   math.gcd(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gtsfkfumhq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yongpay.top/Article/details/gtpgfuhbik.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gtrkfbofzp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.snrcjt.cn/Article/details/gturrrkkib.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ppjwa.cn/Article/details/gtlllrkmxt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hysaishi.cn/Article/details/gtghgnurvk.html

Ruby: a.gcd(b)
来源：http://dali.yj202588.top/Article/details/gtfounezcy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hammf.cn/Article/details/gthzebbidh.html

[N06] 判断回文字符串
来源：http://dali.9152youxi.cn/Article/details/gtcsixxzxf.html

Py:   s == s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gtrynztbxj.html

PHP:  $s === strrev($s);
来源：http://dali.havefunace.top/Article/details/gtcnlienhd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtfoxbulpb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtkkeupjiq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hammf.cn/Article/details/gtmvyschoc.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrppcncj.html

Ruby: s == s.reverse
来源：http://dali.aizwys.cn/Article/details/gtffmcvbam.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gtimfrzugk.html

[N07] 两数之和（返回下标）
来源：http://dali.yongpay.top/Article/details/gtufztjjey.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenjidiqi.icu/Article/details/gtjvbfbksj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cucudq.cn/Article/details/gtdvgwvfmi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jlsjyb.cn/Article/details/gtvhtuabnb.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxinkj.top/Article/details/gtybvyfqap.html

Java: // 手写 HashMap
来源：http://dali.jianghu66.top/Article/details/gtnhaisvhi.html

Go:   // 手写 map[int]int
来源：http://dali.nanxuanxn.top/Article/details/gtnnlaczqu.html

Ruby: // 手写 Hash
来源：http://dali.yvedp.cn/Article/details/gtdvdmgsxo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.0kj1m.cn/Article/details/gtlazkejrt.html

[N08] 生成全排列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugbsvuhy.html

Py:   itertools.permutations(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtfrpftzff.html

PHP:  // 手写递归交换
来源：http://dali.yongpay.top/Article/details/gtgdraqgmn.html

JS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtxgeoacac.html

TS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtasurlike.html

Java: // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtvbmvajeu.html

Go:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtadgjktjx.html

Ruby: arr.permutation.to_a
来源：http://dali.sxryk.cn/Article/details/gtqwwptbsq.html

C#:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtyrtpahky.html

[N09] 栈与队列
来源：http://dali.tian-w.cn/Article/details/gtqlwgmbem.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuanzx.com/Article/details/gtzugnsjyl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cashguo.top/Article/details/gtlymbzctv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gthqmqeqeq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigufen.top/Article/details/gtqhyrlqyb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gaohongyu789.top/Article/details/gtntzcjbsl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.kuanghao11.cn/Article/details/gtbpxdaige.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtknqjwp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqghyhxj.html

[N10] 链表节点定义
来源：http://dali.jyoumei.cn/Article/details/gtprhvunsf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ybcxt.top/Article/details/gtluzghmht.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.0kj1m.cn/Article/details/gtvzapvpcc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.dianchejie.cn/Article/details/gtuzxrfibn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yangfankeji.com/Article/details/gtyaeefiul.html

Java: class Node { int v; Node next; }
来源：http://dali.ybcxt.top/Article/details/gtdzmyknrl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.meibo888.top/Article/details/gtlxiscgmy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zdqjudy.top/Article/details/gtsiczjecm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.havefunace.top/Article/details/gtqpjyslpc.html

[N11] 二叉树中序遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtpcmurfet.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.0kj1m.cn/Article/details/gttjrlrtfh.html

PHP:  // 手写递归函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtootokjgr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.smart0.xyz/Article/details/gtyklrbufv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gtablrcpaq.html

Java: // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtlfdtnbtf.html

Go:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtseeqwxpf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gtdlyoonbr.html

C#:   // 手写递归
来源：http://dali.sweek.top/Article/details/gthgblfuac.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shuidangran.top/Article/details/gtmyhqfrdw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.9152youxi.cn/Article/details/gthnzpdyyr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.redwolf501.top/Article/details/gtwqnhqqcp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangshuangyany.cn/Article/details/gtxfwooejv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gtowmgsilb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gtcyzvgepa.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gogol.net.cn/Article/details/gttlkjqeok.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cqqwz.cn/Article/details/gtekjzkblx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkdyargf.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtsqutliuy.html

O. 并发与异步
来源：http://dali.tanke756.top/Article/details/gtmqfccedy.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gttebwarsy.html

[O01] 启动一个线程
来源：http://dali.redwolf501.top/Article/details/gtcdjipezb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cheryme.top/Article/details/gtbytjaebe.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.smart0.xyz/Article/details/gtpgywjwao.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuanzhike.top/Article/details/gtanvwuose.html

TS:   // 同 JS
来源：http://dali.aibaodan.cn/Article/details/gttfuvvagw.html

Java: new Thread(() -> f()).start()
来源：http://dali.havefunace.top/Article/details/gtotkzgqbk.html

Go:   go f()
来源：http://dali.yanxiufei.cn/Article/details/gtmnrwrjeo.html

Ruby: Thread.new { f }
来源：http://dali.ivvv.top/Article/details/gtkjthvyjs.html

C#:   Task.Run(() => F());
来源：http://dali.cheryme.top/Article/details/gttpamitjz.html

[O02] 使用线程池
来源：http://dali.jyoumei.cn/Article/details/gtgvkepmox.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aibaodan.cn/Article/details/gtexvwiwku.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlviaesf.html

JS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gtxmwlsgfe.html

TS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtetipmidk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.smart0.xyz/Article/details/gtnnzjtyyi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sxryk.cn/Article/details/gtayjulhlo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tianlin.xyz/Article/details/gtypkxnaos.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.svipenyu.cn/Article/details/gthzfvasua.html

[O03] 加锁保护共享数据
来源：http://dali.shzxlz.cn/Article/details/gtbzmifqib.html

Py:   with lock: shared += 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpmgwocw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yangfankeji.com/Article/details/gteplliuyp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.smart0.xyz/Article/details/gtlaeuuofu.html

TS:   // 同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhzuayhk.html

Java: synchronized (this) { shared++; }
来源：http://dali.mhx1999.top/Article/details/gtrkklotbe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hywenlv.cn/Article/details/gtidcdrszb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daria6918.cn/Article/details/gtoixopvcj.html

C#:   lock (gate) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gtgdiqicbz.html

[O04] 定义异步函数并等待
来源：http://dali.aizwys.cn/Article/details/gtkiaccevq.html

Py:   async def f():⏎    await g()
来源：http://dali.feifeiyinyue.top/Article/details/gtkxyrsgqn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.quarkkingdee.top/Article/details/gtljnosgqc.html

JS:   async function f() { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gthdhzmnjq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gtlzalwavn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.smart0.xyz/Article/details/gteylbycbb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daria6918.cn/Article/details/gtueivcqxo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yangfankeji.com/Article/details/gtpisjexqx.html

C#:   async Task F() { await G(); }
来源：http://dali.svipenyu.cn/Article/details/gtdnqtkfke.html

[O05] 并发执行并等待全部完成
来源：http://dali.yanxiufei.cn/Article/details/gtezejdmqi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sufxvd.cn/Article/details/gtedvvqazb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ehwqpu.com/Article/details/gtwfzoycut.html

JS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gtqsdfyohg.html

TS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gtoeohxcif.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuxming.cn/Article/details/gtfppajutp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.snrcjt.cn/Article/details/gtiazcdscf.html

Ruby: threads.map(&:join)
来源：http://dali.jqgfzy.top/Article/details/gtdhyddioc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj202588.top/Article/details/gtayqumspy.html

[O06] 使用进程池
来源：http://dali.tian-w.cn/Article/details/gtbhrmhpud.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.pycfn.com/Article/details/gtdpoenegg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.redwolf501.top/Article/details/gtojyegwdw.html

JS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gtgvjunbsn.html

TS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gtjpcwosdx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sxryk.cn/Article/details/gtpfsvjlof.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258888.top/Article/details/gtedrlddxn.html

Ruby: // fork 块
来源：http://dali.zhiwuduotai.top/Article/details/gtypeyqzam.html

C#:   Parallel.For
来源：http://dali.sufxvd.cn/Article/details/gtvwymzvvi.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtycqrnyje.html

P. 常用工具函数
来源：http://dali.nwbrower.top/Article/details/gtahskxgsi.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtfhlldakc.html

[P01] 生成 UUID
来源：http://dali.snrcjt.cn/Article/details/gtheduptjg.html

Py:   str(uuid.uuid4())
来源：http://dali.hammf.cn/Article/details/gtgfvegegj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xylfe.cn/Article/details/gtxronoulw.html

JS:   crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gtkprkzuru.html

TS:   crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gtjpbuvoad.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnxiangtu.top/Article/details/gtyppcxqkv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fzhhl.top/Article/details/gtivsxevhb.html

Ruby: SecureRandom.uuid
来源：http://dali.tianlin.xyz/Article/details/gtprhfroui.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yvedp.cn/Article/details/gtrlrpcvmz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.havefunace.top/Article/details/gtiaxbzfbz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cucudq.cn/Article/details/gtehitvkhr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sysykeji.top/Article/details/gtmfjlyyhq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmvfizar.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hfpthk.cn/Article/details/gtpcnyyhxw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.iojbl.cn/Article/details/gtjuzoqduw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hysaishi.cn/Article/details/gtzbobambs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuxming.cn/Article/details/gtquypadlx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.guannengcc.top/Article/details/gtnetdwflc.html

[P03] 生成短随机字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtemdpthoe.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuetiantiany.cn/Article/details/gtgyqejtct.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhixingplan.top/Article/details/gtxzhhzsqu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gthodlzyeu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gtnthdytgq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gaohongyu789.top/Article/details/gtqjgputcu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinqigufen.top/Article/details/gtyiztlcud.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shuidangran.top/Article/details/gthbghwtzh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hammf.cn/Article/details/gtxsqyfipi.html

[P04] 求长度
来源：http://dali.daxiang520.top/Article/details/gttasztefu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shangyingyoupin.top/Article/details/gtevrwmuto.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffnwylfe.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gtsjklwgbx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sweek.top/Article/details/gtjnqosiqs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenzaomai.com/Article/details/gtthecztyl.html

Go:   len(arr);  len(m)
来源：http://dali.c1oappe.top/Article/details/gtxzdtnubo.html

Ruby: x.length;  x.size
来源：http://dali.svipenyu.cn/Article/details/gtyvlzadgn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gtxphlppas.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yvedp.cn/Article/details/gtwopuqwlh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhixingplan.top/Article/details/gtessrcyqx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sxryk.cn/Article/details/gtawwftxwu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cucudq.cn/Article/details/gtuajdazpj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sxryk.cn/Article/details/gthyfgqehy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guannengcc.top/Article/details/gtsedufint.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtertutqbn.html

Ruby: a == b
来源：http://dali.shzxlz.cn/Article/details/gtqkxsaiza.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.aibaodan.cn/Article/details/gthvckdevk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdidcrib.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdlbvvch.html

PHP:  if (empty($x)) {}
来源：http://dali.zdqjudy.top/Article/details/gtwsdvdwxf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cqqwz.cn/Article/details/gtlfumxodt.html

TS:   if (x == null) {}
来源：http://dali.zdqjudy.top/Article/details/gtirjymfti.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtpdeycelx.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gtxnnznlht.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.pengpengdd.cyou/Article/details/gteclemjjq.html

C#:   if (x is null) {}
来源：http://dali.yongpay.top/Article/details/gtkgapjuth.html

[P07] 防抖与节流
来源：http://dali.shangyingyoupin.top/Article/details/gtcsjndeuz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yanxiufei.cn/Article/details/gtwgargqkb.html

PHP:  // 手写时间戳比较
来源：http://dali.nwbrower.top/Article/details/gtlfgxtzwo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gtiqyihuvn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gtrvavvheo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtmcenybyj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhengqikj.top/Article/details/gtktotlifd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnzpgwsr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fzhhl.top/Article/details/gtttexnmeh.html

[P08] 处理浮点精度问题
来源：http://dali.gogol.net.cn/Article/details/gtywygourp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.vqdsnc.cn/Article/details/gtcjebisew.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.snrcjt.cn/Article/details/gtmigdmgrz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dianchejie.cn/Article/details/gtoaoarlzb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gtrteerrys.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fzhhl.top/Article/details/gttdueuyqt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuxming.cn/Article/details/gtzugqtvpz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuetiantiany.cn/Article/details/gtojidyksw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hfpthk.cn/Article/details/gtaqilxyer.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtumuyycwy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gtlxakinix.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtniydxvpw.html

[Q01] 创建表
来源：http://dali.daria6918.cn/Article/details/gtunvoetlf.html

CREATE TABLE users (
来源：http://dali.0kj1m.cn/Article/details/gthngwlxlc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhiwuduotai.top/Article/details/gtobqrffvf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gtceegeadi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.daxiang520.top/Article/details/gtgsxdcipp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cashguo.top/Article/details/gtdsdlwexf.html

);
来源：http://dali.yj20258.top/Article/details/gtqchsoicf.html

[Q02] 创建带外键的表
来源：http://dali.vqdsnc.cn/Article/details/gtdaoawjvy.html

CREATE TABLE orders (
来源：http://dali.cdnleiting.top/Article/details/gtpbhmlvoh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangshuangyany.cn/Article/details/gtmlhwlmus.html

user_id INT NOT NULL,
来源：http://dali.xylfe.cn/Article/details/gttotrsvsx.html

amount DECIMAL(10, 2),
来源：http://dali.jyoumei.cn/Article/details/gttlnotucp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yuanzhike.top/Article/details/gtwklankig.html

);
来源：http://dali.chenlongwang.top/Article/details/gtazznlyfr.html

[Q03] 增加列
来源：http://dali.meibo888.top/Article/details/gtfhknbitj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhiwuduotai.top/Article/details/gtrqglwnoo.html

[Q04] 修改列类型
来源：http://dali.jiagoushi.top/Article/details/gtgdttrkti.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.smart0.xyz/Article/details/gtngecnpdi.html

[Q05] 重命名列
来源：http://dali.svipenyu.cn/Article/details/gtwgeafclp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zycfv.cn/Article/details/gteomzmurj.html

[Q06] 删除列
来源：http://dali.wangshuangyany.cn/Article/details/gtskluczuy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.316326.xyz/Article/details/gtfvgqvbxp.html

[Q07] 删除表
来源：http://dali.jqgfzy.top/Article/details/gtdqonhmlh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daria6918.cn/Article/details/gtmenekinv.html

[Q08] 创建普通索引
来源：http://dali.yongpay.top/Article/details/gtfeatheuk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gthtwlmomk.html

[Q09] 创建唯一索引
来源：http://dali.cheryme.top/Article/details/gtclsndent.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gtkrmbnxkx.html

[Q10] 插入单行
来源：http://dali.dashuyun.cn/Article/details/gtkkvwtfce.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtexksuxzr.html

[Q11] 一次插入多行
来源：http://dali.yuanzhike.top/Article/details/gtcgfpfrsl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yongpay.top/Article/details/gtrlfnipgk.html

[Q12] 插入后取自增 ID
来源：http://dali.chenlongwang.top/Article/details/gtfpqdbbgq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cashguo.top/Article/details/gtokydljzn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sysykeji.top/Article/details/gtnrpsovgj.html

[Q13] 忽略重复插入
来源：http://dali.jqgufenzy.top/Article/details/gteznclsho.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gtlmkzfzyq.html

[Q14] 存在则更新（upsert）
来源：http://dali.redwolf501.top/Article/details/gtskqrnlqp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tianlin.xyz/Article/details/gtyiivtoij.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenzaomai.com/Article/details/gttbptatlj.html

[Q15] 查询全部
来源：http://dali.hysaishi.cn/Article/details/gtgbeynheh.html

SELECT * FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtwehnmcls.html

[Q16] 查询指定列
来源：http://dali.wangdashe.top/Article/details/gtslweehdv.html

SELECT id, name FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxjyrkno.html

[Q17] 条件查询
来源：http://dali.sufxvd.cn/Article/details/gtonebgjps.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cheryme.top/Article/details/gttcfoolog.html

[Q18] 模糊匹配
来源：http://dali.c1oappe.top/Article/details/gtleykxbjn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.iojbl.cn/Article/details/gtnzidnpqb.html

[Q19] 范围查询
来源：http://dali.yj20258888.top/Article/details/gtsnbaqgou.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dashuyun.cn/Article/details/gtejbspjaf.html

[Q20] IN 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgbmykxd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zycfv.cn/Article/details/gttehgcasc.html

[Q21] 空值判断
来源：http://dali.yonumen.top/Article/details/gteqrgxnbm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinqigufen.top/Article/details/gtvjdgmcci.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gtkjnjmiqw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangdashe.top/Article/details/gtrgcyljdd.html

[Q23] 分页
来源：http://dali.zhoulong.xyz/Article/details/gtxumbeviz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.guowangkeji.top/Article/details/gtuegplrye.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gtzxzzmdwi.html

SELECT DISTINCT city FROM users;
来源：http://dali.316326.xyz/Article/details/gtmspqxylr.html

[Q25] 只取前 N 条
来源：http://dali.wangdashe.top/Article/details/gtdedsvoki.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxinkj.top/Article/details/gtkodaeana.html

[Q26] 计数
来源：http://dali.jqgfzy.top/Article/details/gtsljaqane.html

SELECT COUNT(*) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtwhjfumua.html

[Q27] 条件计数
来源：http://dali.0kj1m.cn/Article/details/gtqrjovuej.html


<!-- 参考信息 -->