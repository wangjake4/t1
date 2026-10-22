代发 wailian999

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtlskltagm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gtfxcmmpbc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gtowysfupk.html

Go:   slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtwtigrbsa.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gtkbcwmmzt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yanxiufei.cn/Article/details/gtngvysypy.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigufen.top/Article/details/gtolhiqegu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuetiantiany.cn/Article/details/gtfvdojlqv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cdnleiting.top/Article/details/gtyntxzivl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gtizpmglsw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gtmtewwcqn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jyoumei.cn/Article/details/gtmnocrgvb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shangyingyoupin.top/Article/details/gtprsactst.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.aizwys.cn/Article/details/gtddimlplz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yongpay.top/Article/details/gtyjxkjsnd.html

[N04] 斐波那契数列
来源：http://dali.zhixingplan.top/Article/details/gtweyhbkaq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gtavlfdtcd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.mhx1999.top/Article/details/gtzcggldgi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtqnezbohl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gtjrcpslcm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gtleosxfir.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.quarkkingdee.top/Article/details/gtblvdtpso.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guannengcc.top/Article/details/gtboeztcoo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtkppcohzw.html

[N05] 最大公约数
来源：http://dali.daxiang520.top/Article/details/gtdpbqtdgg.html

Py:   math.gcd(a, b)
来源：http://dali.cashguo.top/Article/details/gtijdcshju.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aibaodan.cn/Article/details/gtprtplvqs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ydzc1.top/Article/details/gtzldwpdxm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gtryhlkiok.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cucudq.cn/Article/details/gtiphfkszu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yueranfly.top/Article/details/gtckfdybap.html

Ruby: a.gcd(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtibhvvcey.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhengqikj.top/Article/details/gtufujqgde.html

[N06] 判断回文字符串
来源：http://dali.cdnleiting.top/Article/details/gtjlnqqtzi.html

Py:   s == s[::-1]
来源：http://dali.redwolf501.top/Article/details/gtzdujgtks.html

PHP:  $s === strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gtozyczpoc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gtdbznvmsa.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtedyyglzd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sxryk.cn/Article/details/gtzozwrrwe.html

Go:   // 双指针从两端比较
来源：http://dali.dianchejie.cn/Article/details/gtpfifxrkx.html

Ruby: s == s.reverse
来源：http://dali.redwolf501.top/Article/details/gtexirnlur.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gttomwyaqk.html

[N07] 两数之和（返回下标）
来源：http://dali.haohaochexian.top/Article/details/gtacqxzgwq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.iojbl.cn/Article/details/gtxafgprwh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.kuanghao11.cn/Article/details/gtvaiwgyie.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ybcxt.top/Article/details/gthtrhgstb.html

TS:   // 手写 Map<string, number>
来源：http://dali.gotoacloud.top/Article/details/gtddoaeupc.html

Java: // 手写 HashMap
来源：http://dali.9152youxi.cn/Article/details/gtsijsyoao.html

Go:   // 手写 map[int]int
来源：http://dali.chenzaomai.com/Article/details/gtxzhaxarw.html

Ruby: // 手写 Hash
来源：http://dali.wangdashe.top/Article/details/gtvblyxelg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdanwqjl.html

[N08] 生成全排列
来源：http://dali.ivvv.top/Article/details/gtbzlgvpxy.html

Py:   itertools.permutations(arr)
来源：http://dali.hfpthk.cn/Article/details/gtswgfyluw.html

PHP:  // 手写递归交换
来源：http://dali.shzxlz.cn/Article/details/gtjzbctqce.html

JS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gteipmjcmz.html

TS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtbvqfplvh.html

Java: // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtgqxkecua.html

Go:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtvoknxjmh.html

Ruby: arr.permutation.to_a
来源：http://dali.bjfxy.top/Article/details/gttctowipt.html

C#:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtglnelguc.html

[N09] 栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gthqchxyzd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtepbrflwc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.316326.xyz/Article/details/gtrgtxaunt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtwtoqpjku.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.redwolf501.top/Article/details/gtqtmcvjbs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yangfankeji.com/Article/details/gtdxlqazqm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jyoumei.cn/Article/details/gtrhrjwirb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gtgcnqjazz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gttitzuycj.html

[N10] 链表节点定义
来源：http://dali.jqgufenzy.top/Article/details/gtzfrcfyth.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yanxiufei.cn/Article/details/gtsuylvsti.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.birdmap.top/Article/details/gtlrxqddtt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangdashe.top/Article/details/gtoaszeaak.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhixingplan.top/Article/details/gtegxwmxne.html

Java: class Node { int v; Node next; }
来源：http://dali.dashuyun.cn/Article/details/gtuhoffkyh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.havefunace.top/Article/details/gtxctxjzmu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aibaodan.cn/Article/details/gtisvgqudv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.snrcjt.cn/Article/details/gtaxdkmmgj.html

[N11] 二叉树中序遍历
来源：http://dali.havefunace.top/Article/details/gtwfswyfre.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shangyingyoupin.top/Article/details/gtekfibqvc.html

PHP:  // 手写递归函数
来源：http://dali.chenlongwang.top/Article/details/gtjpganuoa.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtrukxtipf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gtjvlraaki.html

Java: // 手写递归
来源：http://dali.pycfn.com/Article/details/gtfscyozmr.html

Go:   // 手写递归
来源：http://dali.smart0.xyz/Article/details/gtbsjddbmq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhixingplan.top/Article/details/gtlntkgoty.html

C#:   // 手写递归
来源：http://dali.ybcxt.top/Article/details/gtnupbrmrj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangdashe.top/Article/details/gtwnxvqspi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hysaishi.cn/Article/details/gtpkanievz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqncvwso.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gtirlgthvb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gtnqqktoos.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gttdshzhhv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.mhx1999.top/Article/details/gtylojjtuf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.aibaodan.cn/Article/details/gtjemdbxfh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gtvbikopqv.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gthpsfzqni.html

O. 并发与异步
来源：http://dali.jqgfzy.top/Article/details/gtcrbztemt.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gteyepamnz.html

[O01] 启动一个线程
来源：http://dali.chenzaomai.com/Article/details/gtdplxsobn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pycfn.com/Article/details/gtaaqhcitm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.birdmap.top/Article/details/gtietnvgxp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.feifeiyinyue.top/Article/details/gtrksomhpt.html

TS:   // 同 JS
来源：http://dali.sxryk.cn/Article/details/gteirfwgjp.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258.top/Article/details/gtxebybhko.html

Go:   go f()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttixgimhu.html

Ruby: Thread.new { f }
来源：http://dali.c1oappe.top/Article/details/gtidzzpjdq.html

C#:   Task.Run(() => F());
来源：http://dali.aibaodan.cn/Article/details/gtfxdmxwlk.html

[O02] 使用线程池
来源：http://dali.xziqi.cn/Article/details/gtxwjltbkz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.daxiang520.top/Article/details/gtrjofokod.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yvedp.cn/Article/details/gtijovfcun.html

JS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gtcwrrgkjy.html

TS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gtndsbbjim.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangdashe.top/Article/details/gtcuuhquhx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shzxlz.cn/Article/details/gtvdcsopip.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuetiantiany.cn/Article/details/gtsoipbeww.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.feifeiyinyue.top/Article/details/gtedppnefx.html

[O03] 加锁保护共享数据
来源：http://dali.sysykeji.top/Article/details/gtzotqcswg.html

Py:   with lock: shared += 1
来源：http://dali.shuidangran.top/Article/details/gtsahsbzqh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sysykeji.top/Article/details/gtkhlamhal.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.snrcjt.cn/Article/details/gtrppjgvqh.html

TS:   // 同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtfyuspmww.html

Java: synchronized (this) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwqrlzjp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yvedp.cn/Article/details/gtqgbivwax.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.andypj.xyz/Article/details/gtegwecswl.html

C#:   lock (gate) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gttmpnodad.html

[O04] 定义异步函数并等待
来源：http://dali.wangdashe.top/Article/details/gtzqvxyvdl.html

Py:   async def f():⏎    await g()
来源：http://dali.svipenyu.cn/Article/details/gtioxuxdam.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangshuangyany.cn/Article/details/gtsoremzna.html

JS:   async function f() { await g(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtfkpzkdrn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.bjfxy.top/Article/details/gtbewzowxe.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.aibaodan.cn/Article/details/gtydgklajj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhiwuduotai.top/Article/details/gttjzyoogo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.9152youxi.cn/Article/details/gtyzlkpcuc.html

C#:   async Task F() { await G(); }
来源：http://dali.sweek.top/Article/details/gthgnjiacc.html

[O05] 并发执行并等待全部完成
来源：http://dali.feifeiyinyue.top/Article/details/gtomvflwiu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgfzy.top/Article/details/gtlntlobfd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtceggdsog.html

JS:   await Promise.all(tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gtzdrimpsc.html

TS:   await Promise.all(tasks)
来源：http://dali.sweek.top/Article/details/gtvkpbbtxj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.fzhhl.top/Article/details/gtlgffcuze.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tanke756.top/Article/details/gtzaktbsoa.html

Ruby: threads.map(&:join)
来源：http://dali.sweek.top/Article/details/gttasxulgl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hywenlv.cn/Article/details/gtimnhguvz.html

[O06] 使用进程池
来源：http://dali.cashguo.top/Article/details/gtpfwwsxxy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hongshengwenyu.top/Article/details/gtxvatcxez.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xylfe.cn/Article/details/gtlcvfwfbr.html

JS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gtqjrfwqzm.html

TS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gtnyfyrspz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gtgywdqtyt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.birdmap.top/Article/details/gttqwcxlrw.html

Ruby: // fork 块
来源：http://dali.aibaodan.cn/Article/details/gtollhyhzk.html

C#:   Parallel.For
来源：http://dali.andypj.xyz/Article/details/gtvipfybbj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtbkdmpaau.html

P. 常用工具函数
来源：http://dali.meibo888.top/Article/details/gtzxewcnla.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtpppyfrab.html

[P01] 生成 UUID
来源：http://dali.jqgfzy.top/Article/details/gthqpnygzc.html

Py:   str(uuid.uuid4())
来源：http://dali.hammf.cn/Article/details/gtogxvhbji.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fengsongda.top/Article/details/gtqirvriqv.html

JS:   crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gtmsrfikwu.html

TS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gtjbwfwfmy.html

Java: UUID.randomUUID().toString()
来源：http://dali.cdnleiting.top/Article/details/gteelirewg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sysykeji.top/Article/details/gtctddtnlk.html

Ruby: SecureRandom.uuid
来源：http://dali.meibo888.top/Article/details/gtnbsxgroa.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmuvximau.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sxryk.cn/Article/details/gtrekvbrby.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cdnleiting.top/Article/details/gtziilogkx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xinyue.icu/Article/details/gtisjnaszp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gotoacloud.top/Article/details/gtcnvcofos.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xziqi.cn/Article/details/gtbvtckfbg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gthorzmnrv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenjidiqi.icu/Article/details/gtwmcjgrzj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gotoacloud.top/Article/details/gtftegwmyq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.haohaochexian.top/Article/details/gtjepfjvle.html

[P03] 生成短随机字符串
来源：http://dali.fzhhl.top/Article/details/gtmdukpvbs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.iojbl.cn/Article/details/gtfnyeykcx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gaohongyu789.top/Article/details/gtnovcqjkg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtbratorrs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxinkj.top/Article/details/gttmrqtiku.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sufxvd.cn/Article/details/gtrepmjagg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gaohongyu789.top/Article/details/gtfjxxseek.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.kuanghao11.cn/Article/details/gtrdjtdoea.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xuetiantiany.cn/Article/details/gtpgkrwktx.html

[P04] 求长度
来源：http://dali.yonumen.top/Article/details/gtuglzvkyv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tianlin.xyz/Article/details/gtnqgiwewz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtwneohgbo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.quarkkingdee.top/Article/details/gtyidylqjy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangdashe.top/Article/details/gtqvxldblp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuxming.cn/Article/details/gtpbvbboiw.html

Go:   len(arr);  len(m)
来源：http://dali.cqqwz.cn/Article/details/gtadzdbleb.html

Ruby: x.length;  x.size
来源：http://dali.hfpthk.cn/Article/details/gtavalljii.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sufxvd.cn/Article/details/gtoiqdktqm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tianlin.xyz/Article/details/gtoydysrih.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gzhubu.top/Article/details/gtqygxlmjh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.feifeiyinyue.top/Article/details/gttriuzygs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjikdwnyi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yvedp.cn/Article/details/gtchqzlcpr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jlsjyb.cn/Article/details/gtbiglqdwu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yvedp.cn/Article/details/gtfpbmrgfl.html

Ruby: a == b
来源：http://dali.ivvv.top/Article/details/gtohqvkitq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cashguo.top/Article/details/gteyjljdid.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.vqdsnc.cn/Article/details/gtjppcbcbi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.dashuyun.cn/Article/details/gtjrlexumg.html

PHP:  if (empty($x)) {}
来源：http://dali.ehwqpu.com/Article/details/gtevcmvvyb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gogol.net.cn/Article/details/gtwlngpzez.html

TS:   if (x == null) {}
来源：http://dali.aizwys.cn/Article/details/gtoddwggim.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.fzhhl.top/Article/details/gtfkbvfweb.html

Go:   if x == nil {}
来源：http://dali.vqdsnc.cn/Article/details/gtrpvaitud.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gotoacloud.top/Article/details/gtuueatpbq.html

C#:   if (x is null) {}
来源：http://dali.hammf.cn/Article/details/gtraykweie.html

[P07] 防抖与节流
来源：http://dali.dashuyun.cn/Article/details/gtmsjhnbog.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xziqi.cn/Article/details/gttnzlbkpc.html

PHP:  // 手写时间戳比较
来源：http://dali.havefunace.top/Article/details/gtwrjdrgqc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gtpaghgxgx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gtflhhrqdr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sweek.top/Article/details/gtrzfwklnu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.316326.xyz/Article/details/gthjgelsjo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shzxlz.cn/Article/details/gtbnjhbiah.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewsbohvc.html

[P08] 处理浮点精度问题
来源：http://dali.tianlin.xyz/Article/details/gtyyborxjf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj202588.top/Article/details/gtrwjqiffv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dianchejie.cn/Article/details/gtcgqgezhl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sxryk.cn/Article/details/gtgdlcdwed.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.haohaochexian.top/Article/details/gtqtwfdsgj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gotoacloud.top/Article/details/gtiylxrhfm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dianchejie.cn/Article/details/gtovvvfmlf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ivvv.top/Article/details/gtipylcouz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.redwolf501.top/Article/details/gtvgergzat.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtupapxduq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yvedp.cn/Article/details/gtagkrfkxl.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtbmgxlxbb.html

[Q01] 创建表
来源：http://dali.hfpthk.cn/Article/details/gthdivmvbu.html

CREATE TABLE users (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnuvyntej.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.c1oappe.top/Article/details/gthvvyufug.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258.top/Article/details/gtvhgerodc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj20258888.top/Article/details/gtiehcsxld.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.redwolf501.top/Article/details/gtzfbihxym.html

);
来源：http://dali.xziqi.cn/Article/details/gthmlnfsdp.html

[Q02] 创建带外键的表
来源：http://dali.316326.xyz/Article/details/gtglqplywr.html

CREATE TABLE orders (
来源：http://dali.andypj.xyz/Article/details/gtsrmgzbrw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqvxkmgr.html

user_id INT NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gtqskwmvlq.html

amount DECIMAL(10, 2),
来源：http://dali.yonumen.top/Article/details/gthagewfbx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cashguo.top/Article/details/gtiabcusjs.html

);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxdfjoqz.html

[Q03] 增加列
来源：http://dali.0kj1m.cn/Article/details/gtmmyjgdaz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hnqzz.top/Article/details/gtzpdmepic.html

[Q04] 修改列类型
来源：http://dali.yvedp.cn/Article/details/gtmebksxjw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmqmvzyt.html

[Q05] 重命名列
来源：http://dali.jianghu66.top/Article/details/gtftgxydxw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gzhubu.top/Article/details/gtpdqhibls.html

[Q06] 删除列
来源：http://dali.haohaochexian.top/Article/details/gtkpdhwtic.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenlongwang.top/Article/details/gthlpiljoe.html

[Q07] 删除表
来源：http://dali.sysykeji.top/Article/details/gtaodedjvc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ivvv.top/Article/details/gtmnwfjnot.html

[Q08] 创建普通索引
来源：http://dali.birdmap.top/Article/details/gtrwtwzbqg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yvedp.cn/Article/details/gthahbzuoq.html

[Q09] 创建唯一索引
来源：http://dali.nwbrower.top/Article/details/gtobuaqizf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zdqjudy.top/Article/details/gttahviplt.html

[Q10] 插入单行
来源：http://dali.daxiang520.top/Article/details/gtmvaalvuc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gotoacloud.top/Article/details/gteiiqmdla.html

[Q11] 一次插入多行
来源：http://dali.fzhhl.top/Article/details/gtrhsoqpho.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinqigufen.top/Article/details/gttqpydcxd.html

[Q12] 插入后取自增 ID
来源：http://dali.hnxiangtu.top/Article/details/gtmszerpii.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yueranfly.top/Article/details/gtbvraqxyx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shanyushiyangtech.top/Article/details/gtyeygrnad.html

[Q13] 忽略重复插入
来源：http://dali.iojbl.cn/Article/details/gtixxpnbga.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.smart0.xyz/Article/details/gthkklyrxp.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhiwuduotai.top/Article/details/gtkmuolbpb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yvedp.cn/Article/details/gtdtouycgz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sxryk.cn/Article/details/gtiqkaqexa.html

[Q15] 查询全部
来源：http://dali.ybcxt.top/Article/details/gtgdukvxhw.html

SELECT * FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtpnjhsrrq.html

[Q16] 查询指定列
来源：http://dali.hnqzz.top/Article/details/gtaqrdijuk.html

SELECT id, name FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtdnainksa.html

[Q17] 条件查询
来源：http://dali.wangshuangyany.cn/Article/details/gtjwtodmwc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yueranfly.top/Article/details/gtzgahmujl.html

[Q18] 模糊匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtlktmodge.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ppjwa.cn/Article/details/gtxvvgaksf.html

[Q19] 范围查询
来源：http://dali.yvedp.cn/Article/details/gtbmwnpvkn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.daria6918.cn/Article/details/gtultglbtf.html

[Q20] IN 列表
来源：http://dali.sweek.top/Article/details/gtoodkvice.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gthwpbwgop.html

[Q21] 空值判断
来源：http://dali.zycfv.cn/Article/details/gtjipcncfr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xuanzx.com/Article/details/gtosjnxqyn.html

[Q22] 排序
来源：http://dali.hywenlv.cn/Article/details/gtwxmaameg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hongshengwenyu.top/Article/details/gtqjcdraej.html

[Q23] 分页
来源：http://dali.sxryk.cn/Article/details/gttrnjlaor.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.c1oappe.top/Article/details/gtvqdvrxtt.html

[Q24] 去重
来源：http://dali.316326.xyz/Article/details/gtzbzvbrjb.html

SELECT DISTINCT city FROM users;
来源：http://dali.xinyue.icu/Article/details/gtltdhlpra.html

[Q25] 只取前 N 条
来源：http://dali.jqgufenzy.top/Article/details/gtmicuhfes.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daxiang520.top/Article/details/gtuowfhrvs.html

[Q26] 计数
来源：http://dali.ppjwa.cn/Article/details/gthexpuntv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtttqnjywb.html

[Q27] 条件计数
来源：http://dali.shangyingyoupin.top/Article/details/gtsmowimqf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yonumen.top/Article/details/gtlvrbeldq.html

[Q28] 求和与平均
来源：http://dali.dashuyun.cn/Article/details/gtwgvrmida.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtbggunobl.html

[Q29] 最大最小值
来源：http://dali.cheryme.top/Article/details/gtreifcrte.html


<!-- 参考信息 -->