代发 wailian999

C#:   Array.BinarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gttsozdafz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmfuofxl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gtroyczbyr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.c1oappe.top/Article/details/gtihbzdkcv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gtefmrtzfs.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gtkybflmdk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sweek.top/Article/details/gtaxfxxuot.html

Go:   slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gtknguexpr.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmpqtmvi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xylfe.cn/Article/details/gtgtjurziw.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxinkj.top/Article/details/gtxvtfwrxv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj202588.top/Article/details/gtupnljuhc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yangfankeji.com/Article/details/gtxeqshowd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gtpcbvispc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gtaqrwtdbp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.quarkkingdee.top/Article/details/gtrmiesddj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenzaomai.com/Article/details/gthawgivaw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.mhx1999.top/Article/details/gtpwozzfis.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesowhmin.html

[N04] 斐波那契数列
来源：http://dali.sweek.top/Article/details/gtafucbnoj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtqrgxowxm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gtngfccxyq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtadpkjzhr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gtqnnlvtnv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jianghu66.top/Article/details/gtwipebyma.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpovkmeiw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gtaufzukmj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtgtjilwtw.html

[N05] 最大公约数
来源：http://dali.sysykeji.top/Article/details/gtrmlfiixc.html

Py:   math.gcd(a, b)
来源：http://dali.xylfe.cn/Article/details/gtjsisdfdb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sweek.top/Article/details/gtkeebcipc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmabaiaqb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gtrgfizwds.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhiwuduotai.top/Article/details/gtsjyvzyie.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.iojbl.cn/Article/details/gtwtqgybcj.html

Ruby: a.gcd(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjywlwxp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.9152youxi.cn/Article/details/gtnhcmdpms.html

[N06] 判断回文字符串
来源：http://dali.yangfankeji.com/Article/details/gttcfxwzne.html

Py:   s == s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gtagmnvhjh.html

PHP:  $s === strrev($s);
来源：http://dali.ehwqpu.com/Article/details/gtzonzxqgp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtgwuvkyrl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtsjkwdrvz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sufxvd.cn/Article/details/gtitaucubh.html

Go:   // 双指针从两端比较
来源：http://dali.nanxinkj.top/Article/details/gttvdmvedh.html

Ruby: s == s.reverse
来源：http://dali.gogol.net.cn/Article/details/gtisjbynpn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gtyafcmgkh.html

[N07] 两数之和（返回下标）
来源：http://dali.hnqzz.top/Article/details/gtavyayvdw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daxiang520.top/Article/details/gtmhcsvnqs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cashguo.top/Article/details/gtwtmuobur.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.havefunace.top/Article/details/gtxedmyuaz.html

TS:   // 手写 Map<string, number>
来源：http://dali.sysykeji.top/Article/details/gtdanmqkvz.html

Java: // 手写 HashMap
来源：http://dali.daria6918.cn/Article/details/gtwtukdsmt.html

Go:   // 手写 map[int]int
来源：http://dali.cheryme.top/Article/details/gtavqyoyfx.html

Ruby: // 手写 Hash
来源：http://dali.hysaishi.cn/Article/details/gtcntrsmlq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gzhubu.top/Article/details/gtnpfvoknq.html

[N08] 生成全排列
来源：http://dali.jinghuilouyu.cn/Article/details/gtpfrneuxa.html

Py:   itertools.permutations(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtbansnuzq.html

PHP:  // 手写递归交换
来源：http://dali.mhx1999.top/Article/details/gtfbxxaitd.html

JS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtghgercwf.html

TS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtrjlfhyjk.html

Java: // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtzrecfavx.html

Go:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtqejhrlxs.html

Ruby: arr.permutation.to_a
来源：http://dali.yongpay.top/Article/details/gtyryxeadr.html

C#:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtfbhmrwfe.html

[N09] 栈与队列
来源：http://dali.wangshuangyany.cn/Article/details/gtiwnmfwpu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.0kj1m.cn/Article/details/gtbmmqtowc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtoqqrypgi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtidakybyz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258.top/Article/details/gtjjtpduzq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hywenlv.cn/Article/details/gtdshnwnqa.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xinyue.icu/Article/details/gtyzphyjfu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gtzayaduog.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gogol.net.cn/Article/details/gtqnnjxnoc.html

[N10] 链表节点定义
来源：http://dali.haohaochexian.top/Article/details/gtprowcnli.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tianlin.xyz/Article/details/gtwbcwddxd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.svipenyu.cn/Article/details/gtkmeueamb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zdqjudy.top/Article/details/gtldylxrzu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sufxvd.cn/Article/details/gtuuqajzkh.html

Java: class Node { int v; Node next; }
来源：http://dali.hnxiangtu.top/Article/details/gtednjygut.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj202588.top/Article/details/gtvfsrsehn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ydzc1.top/Article/details/gttyxgqcob.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgscfzacv.html

[N11] 二叉树中序遍历
来源：http://dali.jlsjyb.cn/Article/details/gtzzogrbsf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xinyue.icu/Article/details/gtbmvnsdjr.html

PHP:  // 手写递归函数
来源：http://dali.ehwqpu.com/Article/details/gtxwjaumzz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gtrmtfculb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gtjvwgyzav.html

Java: // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gtvnfeniwr.html

Go:   // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtulagebkx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aibaodan.cn/Article/details/gtccorohul.html

C#:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gtbzvzksuk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.kuanghao11.cn/Article/details/gtyjxybsus.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jianghu66.top/Article/details/gtzqewywpm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.9152youxi.cn/Article/details/gtomemuwjo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gtyledbibi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gtawsljqwc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gtqwunzych.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gzhubu.top/Article/details/gttadavbix.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.vqdsnc.cn/Article/details/gtggzdcqix.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gtnqupznsi.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtlzjyzlkl.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gtwptzhtvk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtwntanezh.html

[O01] 启动一个线程
来源：http://dali.sufxvd.cn/Article/details/gtpxecysmn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cheryme.top/Article/details/gtmcjtqfwb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.iojbl.cn/Article/details/gtecwbdfas.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangdashe.top/Article/details/gtywvsodoq.html

TS:   // 同 JS
来源：http://dali.pengpengdd.cyou/Article/details/gtkthgziip.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnxiangtu.top/Article/details/gtmarihflh.html

Go:   go f()
来源：http://dali.xinyue.icu/Article/details/gtmqowsdjb.html

Ruby: Thread.new { f }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyiebkbaa.html

C#:   Task.Run(() => F());
来源：http://dali.nwbrower.top/Article/details/gtkrzpvhsx.html

[O02] 使用线程池
来源：http://dali.chenzaomai.com/Article/details/gthwwcvcfg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xinyue.icu/Article/details/gtvphucjwj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guowangkeji.top/Article/details/gtzawfdnkq.html

JS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gtbeindlpb.html

TS:   // worker_threads 线程池
来源：http://dali.jianghu66.top/Article/details/gtwqgqpxyt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.fengsongda.top/Article/details/gttvuunlsa.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangdashe.top/Article/details/gtgbhjcgee.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gtupymvetv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymdpjpyj.html

[O03] 加锁保护共享数据
来源：http://dali.zhengqikj.top/Article/details/gtbstbcljs.html

Py:   with lock: shared += 1
来源：http://dali.tianlin.xyz/Article/details/gtorrfhjxr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.iojbl.cn/Article/details/gtvqiaxlpq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhengqikj.top/Article/details/gtizgjabtg.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gtnlmshquw.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxuanxn.top/Article/details/gtdourldfe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yangfankeji.com/Article/details/gtgwwsnpbb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cashguo.top/Article/details/gtzbrukvia.html

C#:   lock (gate) { shared++; }
来源：http://dali.jiagoushi.top/Article/details/gthxvjlvfk.html

[O04] 定义异步函数并等待
来源：http://dali.sxryk.cn/Article/details/gtchlbrafe.html

Py:   async def f():⏎    await g()
来源：http://dali.guannengcc.top/Article/details/gtjjoltrdq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cdnleiting.top/Article/details/gtbkubphwp.html

JS:   async function f() { await g(); }
来源：http://dali.jqgufenzy.top/Article/details/gtzedxpiza.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258888.top/Article/details/gthyngnuvh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.pycfn.com/Article/details/gtfigykdnm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shuidangran.top/Article/details/gtaqgupwvb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jlsjyb.cn/Article/details/gtkglxfups.html

C#:   async Task F() { await G(); }
来源：http://dali.yuxming.cn/Article/details/gtfiiwevzc.html

[O05] 并发执行并等待全部完成
来源：http://dali.tanke756.top/Article/details/gtlupfyhsz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sufxvd.cn/Article/details/gtucpfpmso.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sufxvd.cn/Article/details/gtvinpuarf.html

JS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gtlqsxhntv.html

TS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorowgptj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.fengsongda.top/Article/details/gtmakiayvk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.c1oappe.top/Article/details/gtxylguzkm.html

Ruby: threads.map(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gtdukigpcj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guannengcc.top/Article/details/gtedtqtkjn.html

[O06] 使用进程池
来源：http://dali.gzhubu.top/Article/details/gtzlxsvcnq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dianchejie.cn/Article/details/gtxmqfwxrp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.iojbl.cn/Article/details/gtxouezgud.html

JS:   // child_process / cluster 模块
来源：http://dali.hysaishi.cn/Article/details/gtserhfjub.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxuanxn.top/Article/details/gtxydylbhg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zycfv.cn/Article/details/gtrrvdjfbz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxinkj.top/Article/details/gtjfmbjnam.html

Ruby: // fork 块
来源：http://dali.hywenlv.cn/Article/details/gtwcyohelt.html

C#:   Parallel.For
来源：http://dali.yvedp.cn/Article/details/gtlvzxuoeq.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtdgxxwkjv.html

P. 常用工具函数
来源：http://dali.nwbrower.top/Article/details/gtihtthgax.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtuqqyalkt.html

[P01] 生成 UUID
来源：http://dali.guannengcc.top/Article/details/gtvbgevzvy.html

Py:   str(uuid.uuid4())
来源：http://dali.0kj1m.cn/Article/details/gtbztawyew.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.aizwys.cn/Article/details/gtpelfxvju.html

JS:   crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gtdycnyfwy.html

TS:   crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gtzmgmkvoa.html

Java: UUID.randomUUID().toString()
来源：http://dali.hywenlv.cn/Article/details/gtqzjlupub.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ppjwa.cn/Article/details/gtpmkvbpsb.html

Ruby: SecureRandom.uuid
来源：http://dali.9152youxi.cn/Article/details/gtdquatsae.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangshuangyany.cn/Article/details/gtehbzdtou.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhengqikj.top/Article/details/gtzqqbvipv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.bjfxy.top/Article/details/gtotrsachg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtclrnycmc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sweek.top/Article/details/gtazunaxdg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenzaomai.com/Article/details/gtkntgprvb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jianghu66.top/Article/details/gtvrjzvria.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jianghu66.top/Article/details/gtkimlwfwg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cheryme.top/Article/details/gthpoorlxt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hywenlv.cn/Article/details/gtcpnrvrsg.html

[P03] 生成短随机字符串
来源：http://dali.daria6918.cn/Article/details/gtdximnnxg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxuanxn.top/Article/details/gtyhxdxvlt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shuidangran.top/Article/details/gtpzvadqjf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tianlin.xyz/Article/details/gtrheqyhcr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gtzwmjkmaf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.snrcjt.cn/Article/details/gtwtycinkn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ybcxt.top/Article/details/gtmbgbbmod.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj202588.top/Article/details/gtamvkwwsd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sxryk.cn/Article/details/gtcvqvezkm.html

[P04] 求长度
来源：http://dali.quarkkingdee.top/Article/details/gtilhiqddk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.fzhhl.top/Article/details/gtcevfagmy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gteeqndlmx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.haohaochexian.top/Article/details/gtkhphhxpd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gtcbzvmmkk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jyoumei.cn/Article/details/gtvibkxtsm.html

Go:   len(arr);  len(m)
来源：http://dali.aibaodan.cn/Article/details/gtzwdhnmfd.html

Ruby: x.length;  x.size
来源：http://dali.yonumen.top/Article/details/gtbahmduzv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ehwqpu.com/Article/details/gtrkhruqsl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dashuyun.cn/Article/details/gtwkdtqpkn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pengpengdd.cyou/Article/details/gttnptdbwl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.pycfn.com/Article/details/gtxloouipq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.quarkkingdee.top/Article/details/gtkurbdczj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hammf.cn/Article/details/gtanxnublz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.vqdsnc.cn/Article/details/gtvnyuczba.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxznbzmm.html

Ruby: a == b
来源：http://dali.hnqzz.top/Article/details/gtsyqupbhh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.quarkkingdee.top/Article/details/gtylzmcjrj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.haohaochexian.top/Article/details/gtmkxijaxf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jlsjyb.cn/Article/details/gtowuxmkhy.html

PHP:  if (empty($x)) {}
来源：http://dali.meibo888.top/Article/details/gttslwserv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yonumen.top/Article/details/gthrjoexhv.html

TS:   if (x == null) {}
来源：http://dali.jqgfzy.top/Article/details/gtxoxfospo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gtxlpcjobg.html

Go:   if x == nil {}
来源：http://dali.aibaodan.cn/Article/details/gtdxshkchd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xziqi.cn/Article/details/gtqcdyaobo.html

C#:   if (x is null) {}
来源：http://dali.hywenlv.cn/Article/details/gthcnnvjon.html

[P07] 防抖与节流
来源：http://dali.mhx1999.top/Article/details/gtqngrzkjr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hysaishi.cn/Article/details/gtagozdwrl.html

PHP:  // 手写时间戳比较
来源：http://dali.tian-w.cn/Article/details/gtjfatccma.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gtyuzlwftg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtvahacyjf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtibarzgue.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xinyue.icu/Article/details/gtxsnufqmh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhengqikj.top/Article/details/gteonejmbv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xziqi.cn/Article/details/gtliwkzntz.html

[P08] 处理浮点精度问题
来源：http://dali.yj202588.top/Article/details/gtslwvflhg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jlsjyb.cn/Article/details/gtshtjfnhs.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ivvv.top/Article/details/gtqnceagqb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.9152youxi.cn/Article/details/gtqcgcdtzt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.mhx1999.top/Article/details/gtafbkbfke.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.svipenyu.cn/Article/details/gtvwqndsqz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yanxiufei.cn/Article/details/gtsvjzkivb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj20258.top/Article/details/gtvnclnsof.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhiwuduotai.top/Article/details/gtnwsoydby.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtphpeclnf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhengqikj.top/Article/details/gtrbumydrj.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtiscenrno.html

[Q01] 创建表
来源：http://dali.chenlongwang.top/Article/details/gthprewdmq.html

CREATE TABLE users (
来源：http://dali.jqgufenzy.top/Article/details/gtuoncswzf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gttohdnfox.html

name VARCHAR(50) NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gtjhtiooqi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigfzy.top/Article/details/gtxrxxidpi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.bjfxy.top/Article/details/gtbgnkaiev.html

);
来源：http://dali.daria6918.cn/Article/details/gtkmzyvtuj.html

[Q02] 创建带外键的表
来源：http://dali.cashguo.top/Article/details/gtovjkudwk.html

CREATE TABLE orders (
来源：http://dali.zdqjudy.top/Article/details/gtzrmnwjiw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gtzaidazhp.html

user_id INT NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gtglgnvqum.html

amount DECIMAL(10, 2),
来源：http://dali.xinyue.icu/Article/details/gtlkrvlslk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhixingplan.top/Article/details/gtkgfrtnwl.html

);
来源：http://dali.cdnleiting.top/Article/details/gtbkeelzbl.html

[Q03] 增加列
来源：http://dali.nwbrower.top/Article/details/gtgeuommzz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gaohongyu789.top/Article/details/gtaqjcqpta.html

[Q04] 修改列类型
来源：http://dali.jyoumei.cn/Article/details/gtzlwqqudw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gtfmdhviwc.html

[Q05] 重命名列
来源：http://dali.xuanzx.com/Article/details/gtebyzauqp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shuidangran.top/Article/details/gtiriptclj.html

[Q06] 删除列
来源：http://dali.ppjwa.cn/Article/details/gtlygosmwl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.vqdsnc.cn/Article/details/gtvgizsmgp.html

[Q07] 删除表
来源：http://dali.zycfv.cn/Article/details/gtenywhrid.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenlongwang.top/Article/details/gtorejqdub.html

[Q08] 创建普通索引
来源：http://dali.zhixingplan.top/Article/details/gtxhkpfzyk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shuidangran.top/Article/details/gtowkkfzoq.html

[Q09] 创建唯一索引
来源：http://dali.sufxvd.cn/Article/details/gtoknoriec.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gtaejcftey.html

[Q10] 插入单行
来源：http://dali.zhixingplan.top/Article/details/gtozdievbi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.fzhhl.top/Article/details/gtxnocmzxm.html

[Q11] 一次插入多行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipbpkwgg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gtessppqru.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258888.top/Article/details/gtafdqujlk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigufen.top/Article/details/gtxfcpyouf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuanzhike.top/Article/details/gtzdflscbm.html

[Q13] 忽略重复插入
来源：http://dali.daxiang520.top/Article/details/gtfvldwsvt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.haohaochexian.top/Article/details/gtihepirvu.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinghuilouyu.cn/Article/details/gtntiftvqv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.birdmap.top/Article/details/gtbgqexkdp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.0kj1m.cn/Article/details/gtrcrqthps.html

[Q15] 查询全部
来源：http://dali.xuetiantiany.cn/Article/details/gtjeasgtyd.html

SELECT * FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtghvoursm.html

[Q16] 查询指定列
来源：http://dali.dashuyun.cn/Article/details/gtdavhgobq.html

SELECT id, name FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpwarcrs.html

[Q17] 条件查询
来源：http://dali.jinqigufen.top/Article/details/gtnnolzeay.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shzxlz.cn/Article/details/gteqlrlbdz.html

[Q18] 模糊匹配
来源：http://dali.zycfv.cn/Article/details/gtkdjeqtla.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258888.top/Article/details/gtmlnyhixm.html

[Q19] 范围查询
来源：http://dali.0kj1m.cn/Article/details/gthtaupqgk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zdqjudy.top/Article/details/gtcthgsbgq.html

[Q20] IN 列表
来源：http://dali.havefunace.top/Article/details/gtnuxaiuyq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.snrcjt.cn/Article/details/gtypwgdwix.html

[Q21] 空值判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhqqkskf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.smart0.xyz/Article/details/gtpclkeaau.html

[Q22] 排序
来源：http://dali.hywenlv.cn/Article/details/gtmlzszzqg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.vqdsnc.cn/Article/details/gtrmympwoj.html

[Q23] 分页
来源：http://dali.jinqigufen.top/Article/details/gtwcbjdkey.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ydzc1.top/Article/details/gtjdbebuva.html

[Q24] 去重
来源：http://dali.iojbl.cn/Article/details/gtgyxyctuu.html

SELECT DISTINCT city FROM users;
来源：http://dali.cashguo.top/Article/details/gtpvitdxib.html

[Q25] 只取前 N 条
来源：http://dali.sysykeji.top/Article/details/gteozylqrr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.iojbl.cn/Article/details/gtjxdjciwj.html

[Q26] 计数
来源：http://dali.nanxinkj.top/Article/details/gtnzamcjtj.html

SELECT COUNT(*) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtijznqisv.html

[Q27] 条件计数
来源：http://dali.xuetiantiany.cn/Article/details/gtcnudnfhv.html


<!-- 参考信息 -->