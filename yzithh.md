代发 wailian999

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtypybvkco.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ehwqpu.com/Article/details/gteatznzam.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gtazatfxnf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuanzhike.top/Article/details/gthmvfprws.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gttlhmpqvc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gtumnbgvab.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangdashe.top/Article/details/gtueceduhs.html

Go:   slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gtftlpkgns.html

Ruby: arr.sort
来源：http://dali.sxryk.cn/Article/details/gtctfkxlbv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ydzc1.top/Article/details/gtwwnijfdn.html

[N03] 快速排序（分治示例）
来源：http://dali.zdqjudy.top/Article/details/gthbyumfcb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daxiang520.top/Article/details/gtpsrtmdke.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gotoacloud.top/Article/details/gtgfnbyjqx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gtewweaoxv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gtutgvbtlj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.kuanghao11.cn/Article/details/gtbfrandbf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.9152youxi.cn/Article/details/gtkefasrvv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jqgufenzy.top/Article/details/gtdrxtstkt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dianchejie.cn/Article/details/gtuvgyzovv.html

[N04] 斐波那契数列
来源：http://dali.zhongyouzk.top/Article/details/gtvipatfrj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gtuapawbif.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hammf.cn/Article/details/gteztouscj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gtpkziugaz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gtbdlxvahr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gtvrgqyhaj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.mhx1999.top/Article/details/gtzrrwthbq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gtibfvgybu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtqbzxlqol.html

[N05] 最大公约数
来源：http://dali.xuetiantiany.cn/Article/details/gtkybeqciy.html

Py:   math.gcd(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtmbslecwf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.meibo888.top/Article/details/gtznfjmpuz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtxtkmuxhv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gtzkofuanh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aizwys.cn/Article/details/gtovatjrko.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daria6918.cn/Article/details/gtjdllqcjo.html

Ruby: a.gcd(b)
来源：http://dali.mhx1999.top/Article/details/gtjndldcdv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfrarvgj.html

[N06] 判断回文字符串
来源：http://dali.guowangkeji.top/Article/details/gtuxtjgfjz.html

Py:   s == s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjuzsluyv.html

PHP:  $s === strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gtfvxqxgky.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtfgqtyyhj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gttutjnmpy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgabyuffd.html

Go:   // 双指针从两端比较
来源：http://dali.dashuyun.cn/Article/details/gtuukhdxyy.html

Ruby: s == s.reverse
来源：http://dali.gotoacloud.top/Article/details/gtosspidrv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gtunhivwub.html

[N07] 两数之和（返回下标）
来源：http://dali.cashguo.top/Article/details/gtyfvevgrg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zycfv.cn/Article/details/gtzxlmpqld.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dianchejie.cn/Article/details/gttdggoyir.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cdnleiting.top/Article/details/gtjwdifmey.html

TS:   // 手写 Map<string, number>
来源：http://dali.redwolf501.top/Article/details/gtsriviiyt.html

Java: // 手写 HashMap
来源：http://dali.jinyuanbaomall.cn/Article/details/gtboopspba.html

Go:   // 手写 map[int]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbrnbkjy.html

Ruby: // 手写 Hash
来源：http://dali.chenlongwang.top/Article/details/gtqkpuwesw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.iojbl.cn/Article/details/gtxkfyhyon.html

[N08] 生成全排列
来源：http://dali.yueranfly.top/Article/details/gtxzxyqtnc.html

Py:   itertools.permutations(arr)
来源：http://dali.guowangkeji.top/Article/details/gtfshlphee.html

PHP:  // 手写递归交换
来源：http://dali.316326.xyz/Article/details/gtldwdppac.html

JS:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gthbflgpgf.html

TS:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtvlzdbwbo.html

Java: // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjhullua.html

Go:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtycaotexy.html

Ruby: arr.permutation.to_a
来源：http://dali.xylfe.cn/Article/details/gtquqeqvvb.html

C#:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtenwqewuq.html

[N09] 栈与队列
来源：http://dali.yanxiufei.cn/Article/details/gtcjslrnhm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yuxming.cn/Article/details/gtumjysojl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.316326.xyz/Article/details/gtjcrmpwgz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtlwyjauqw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yuanzhike.top/Article/details/gttywqxnuk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.316326.xyz/Article/details/gtrocarnyq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.svipenyu.cn/Article/details/gtbytnmtlk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gtqbnugfhh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yangfankeji.com/Article/details/gtgzolqxla.html

[N10] 链表节点定义
来源：http://dali.chenzaomai.com/Article/details/gtfhjlcpcj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jianghu66.top/Article/details/gtgrbdtfdx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxinkj.top/Article/details/gtttlngeeb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.0kj1m.cn/Article/details/gtxuoffuwl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hysaishi.cn/Article/details/gtygluzolh.html

Java: class Node { int v; Node next; }
来源：http://dali.dianchejie.cn/Article/details/gtzcaxvlca.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangshuangyany.cn/Article/details/gtgnrktykx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpurlygf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.andypj.xyz/Article/details/gtfkxaprtu.html

[N11] 二叉树中序遍历
来源：http://dali.cucudq.cn/Article/details/gtnlztyeig.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.wangdashe.top/Article/details/gthtcgbava.html

PHP:  // 手写递归函数
来源：http://dali.xinyue.icu/Article/details/gtmntbtxxt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shzxlz.cn/Article/details/gthpxbllbo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangdashe.top/Article/details/gtlamfuxzf.html

Java: // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gtekjshocd.html

Go:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gtmppcuwht.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.daxiang520.top/Article/details/gtmrymxrkq.html

C#:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtvqhmtyig.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpsnseilg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ivvv.top/Article/details/gtkwvmcwuq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqedasdjt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gtqkqprdgs.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gtgufjknwu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yangfankeji.com/Article/details/gtegxrqdji.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pengpengdd.cyou/Article/details/gtbtwqfmgp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dashuyun.cn/Article/details/gtprtgkvby.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuanzx.com/Article/details/gtvrhwfldr.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtmcempgae.html

O. 并发与异步
来源：http://dali.316326.xyz/Article/details/gtwtyhzblj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqqisugd.html

[O01] 启动一个线程
来源：http://dali.jianghu66.top/Article/details/gtfwgxsiml.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xinyue.icu/Article/details/gtawxmkhbt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hywenlv.cn/Article/details/gtcrqutnux.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhengqikj.top/Article/details/gtzgldjfbw.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gtqjdzdani.html

Java: new Thread(() -> f()).start()
来源：http://dali.haohaochexian.top/Article/details/gtvkjffble.html

Go:   go f()
来源：http://dali.smart0.xyz/Article/details/gtfksitqjc.html

Ruby: Thread.new { f }
来源：http://dali.jianghu66.top/Article/details/gtdeqvyaek.html

C#:   Task.Run(() => F());
来源：http://dali.zhiwuduotai.top/Article/details/gtheejidpx.html

[O02] 使用线程池
来源：http://dali.sysykeji.top/Article/details/gttjzigswh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhengqikj.top/Article/details/gtbefksiso.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xinyue.icu/Article/details/gtvmrbqjmb.html

JS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gtbmkvfxgy.html

TS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gtiaixryrz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hnqzz.top/Article/details/gtdmzfjsif.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hongshengwenyu.top/Article/details/gtaaquijip.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shangyingyoupin.top/Article/details/gtehqxljla.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.kuanghao11.cn/Article/details/gtngyvgtvr.html

[O03] 加锁保护共享数据
来源：http://dali.shzxlz.cn/Article/details/gtxskddzlb.html

Py:   with lock: shared += 1
来源：http://dali.kuanghao11.cn/Article/details/gtqndedabw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbevgpieq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sysykeji.top/Article/details/gtungslyez.html

TS:   // 同 JS
来源：http://dali.mhx1999.top/Article/details/gtglxzxkoa.html

Java: synchronized (this) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gtulwqnhdw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhixingplan.top/Article/details/gtqfrsruou.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yanxiufei.cn/Article/details/gtjqbhmpms.html

C#:   lock (gate) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gtxynyvmsl.html

[O04] 定义异步函数并等待
来源：http://dali.zhoulong.xyz/Article/details/gtneitlruu.html

Py:   async def f():⏎    await g()
来源：http://dali.fzhhl.top/Article/details/gturnoflrk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxuanxn.top/Article/details/gttgyvcjmp.html

JS:   async function f() { await g(); }
来源：http://dali.shuidangran.top/Article/details/gtetutkrue.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gthwreonrz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuoyjvvtu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sweek.top/Article/details/gtmgoyblrm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcrppqfy.html

C#:   async Task F() { await G(); }
来源：http://dali.guannengcc.top/Article/details/gtwiemqzqv.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgufenzy.top/Article/details/gtontkfexv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dashuyun.cn/Article/details/gttkwsibjl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sxryk.cn/Article/details/gtlbjsbyck.html

JS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydfdyknb.html

TS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gtsctbtqbu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenjidiqi.icu/Article/details/gtcwiogloy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fzhhl.top/Article/details/gttzpqjfsz.html

Ruby: threads.map(&:join)
来源：http://dali.cdnleiting.top/Article/details/gtmlvfbmwf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.daria6918.cn/Article/details/gtufymwfwp.html

[O06] 使用进程池
来源：http://dali.xuetiantiany.cn/Article/details/gtokdqckqh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xziqi.cn/Article/details/gtqdpxsnaf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hfpthk.cn/Article/details/gtzomivakb.html

JS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gtnpaovtve.html

TS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gtfwfmzomm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ybcxt.top/Article/details/gtfaeulvvl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.haohaochexian.top/Article/details/gthtedujow.html

Ruby: // fork 块
来源：http://dali.hfpthk.cn/Article/details/gtjzmowisc.html

C#:   Parallel.For
来源：http://dali.hywenlv.cn/Article/details/gtdcxyytkk.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtfzxezykl.html

P. 常用工具函数
来源：http://dali.ivvv.top/Article/details/gtfjxablbs.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gttvhldjsp.html

[P01] 生成 UUID
来源：http://dali.sweek.top/Article/details/gtjfvurpbf.html

Py:   str(uuid.uuid4())
来源：http://dali.jiagoushi.top/Article/details/gtgeknwmtg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlnhmhbic.html

JS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gtgdtlpnwe.html

TS:   crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gtguthbugv.html

Java: UUID.randomUUID().toString()
来源：http://dali.dashuyun.cn/Article/details/gtalnyutmd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.redwolf501.top/Article/details/gtqudiymsf.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxuanxn.top/Article/details/gtnhcmezly.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yongpay.top/Article/details/gtrrcfuuug.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xuanzx.com/Article/details/gtdbsyvcwe.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jqgufenzy.top/Article/details/gtbjvpvdjt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxinkj.top/Article/details/gtitqiqffn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhiwuduotai.top/Article/details/gtuoleaial.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgyptnkyf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtqefgiezv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yueranfly.top/Article/details/gtureijtdk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ydzc1.top/Article/details/gtrjwtgmhf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxinkj.top/Article/details/gtcmuznyvc.html

[P03] 生成短随机字符串
来源：http://dali.zhongyouzk.top/Article/details/gtrhbeuyfl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinqigfzy.top/Article/details/gtsmejluis.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenlongwang.top/Article/details/gtvjjrwapq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cheryme.top/Article/details/gtzzfgests.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtgcdbfaul.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gaohongyu789.top/Article/details/gtbzcdcbkq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinghuilouyu.cn/Article/details/gthetopzzq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cashguo.top/Article/details/gtawpclwvk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.0kj1m.cn/Article/details/gtehrwsgay.html

[P04] 求长度
来源：http://dali.sxryk.cn/Article/details/gtufaexqif.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258888.top/Article/details/gtklihmjva.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtpyqgdvmp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gtkpwtybyc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gtfajhijfu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigfzy.top/Article/details/gtjxkkrsbg.html

Go:   len(arr);  len(m)
来源：http://dali.hfpthk.cn/Article/details/gtsyvmrlaq.html

Ruby: x.length;  x.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gticeauuce.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.smart0.xyz/Article/details/gtoicpvfes.html

[P05] 判断两个对象内容是否相等
来源：http://dali.svipenyu.cn/Article/details/gtphcvveuw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhoulong.xyz/Article/details/gtapvbktaz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cashguo.top/Article/details/gtizmwawcn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinyuanbaomall.cn/Article/details/gteglzgmyh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yvedp.cn/Article/details/gteyluxksv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.snrcjt.cn/Article/details/gtbicgtsqk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gtcfrxicvl.html

Ruby: a == b
来源：http://dali.chenjidiqi.icu/Article/details/gteqlvypjx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gzhubu.top/Article/details/gtktfxbrvo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.guannengcc.top/Article/details/gtciybeicl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinghuilouyu.cn/Article/details/gtudgukdrk.html

PHP:  if (empty($x)) {}
来源：http://dali.chenlongwang.top/Article/details/gtskohixig.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ppjwa.cn/Article/details/gtnzjnnaxc.html

TS:   if (x == null) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtbfabneem.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jqgufenzy.top/Article/details/gtpztahtho.html

Go:   if x == nil {}
来源：http://dali.snrcjt.cn/Article/details/gtuwxuflwc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpsypqpmi.html

C#:   if (x is null) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnrczflq.html

[P07] 防抖与节流
来源：http://dali.nwbrower.top/Article/details/gtclgjishl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.guowangkeji.top/Article/details/gtidsgnprb.html

PHP:  // 手写时间戳比较
来源：http://dali.haohaochexian.top/Article/details/gtixcqulsy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gtccieyjct.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gttcnnjirw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtcntgiois.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhongyouzk.top/Article/details/gtqkiqmcof.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ehwqpu.com/Article/details/gtwiupblyk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.9152youxi.cn/Article/details/gthkxmkjdi.html

[P08] 处理浮点精度问题
来源：http://dali.iojbl.cn/Article/details/gtfuemvjhe.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.mhx1999.top/Article/details/gtjcdgoxyf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.316326.xyz/Article/details/gtwdvjmjbb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.bjfxy.top/Article/details/gtcwehhhjp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.fengsongda.top/Article/details/gtwyxgfjqc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.havefunace.top/Article/details/gtelcoccgb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.meibo888.top/Article/details/gtgrdofemd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.fengsongda.top/Article/details/gtsbvnxdls.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangtech.top/Article/details/gtfuzpcrir.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtxfpaqruw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xylfe.cn/Article/details/gtjruyoutt.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtgsbxmvjl.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gtxwmdjxzx.html

CREATE TABLE users (
来源：http://dali.gaohongyu789.top/Article/details/gthnxmdfpd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gtlecbsuch.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shangyingyoupin.top/Article/details/gtvifjxdjp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cucudq.cn/Article/details/gtdtvdmbrr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hammf.cn/Article/details/gthsosookj.html

);
来源：http://dali.jinqigfzy.top/Article/details/gtprsltshe.html

[Q02] 创建带外键的表
来源：http://dali.9152youxi.cn/Article/details/gtokauutqq.html

CREATE TABLE orders (
来源：http://dali.ppjwa.cn/Article/details/gtcuhuitbm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gtmmqnsptl.html

user_id INT NOT NULL,
来源：http://dali.bjfxy.top/Article/details/gtxloxeopo.html

amount DECIMAL(10, 2),
来源：http://dali.iojbl.cn/Article/details/gtyerrwits.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nwbrower.top/Article/details/gtpmadsopk.html

);
来源：http://dali.vqdsnc.cn/Article/details/gtahunlhto.html

[Q03] 增加列
来源：http://dali.tian-w.cn/Article/details/gthhujtgbn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sysykeji.top/Article/details/gtofzckzth.html

[Q04] 修改列类型
来源：http://dali.hywenlv.cn/Article/details/gtotepljga.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuanzhike.top/Article/details/gtlcpectme.html

[Q05] 重命名列
来源：http://dali.vqdsnc.cn/Article/details/gtlebpnyjr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xziqi.cn/Article/details/gtsljykuqg.html

[Q06] 删除列
来源：http://dali.aibaodan.cn/Article/details/gtqabswejs.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fzhhl.top/Article/details/gtgeojvajd.html

[Q07] 删除表
来源：http://dali.quarkkingdee.top/Article/details/gtjuenloqn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhoulong.xyz/Article/details/gtlyjjyned.html

[Q08] 创建普通索引
来源：http://dali.yj202588.top/Article/details/gtdaxtqsvu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenlongwang.top/Article/details/gtnobvqges.html

[Q09] 创建唯一索引
来源：http://dali.yongpay.top/Article/details/gtrfmoqqac.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hywenlv.cn/Article/details/gtfmsxwwbe.html

[Q10] 插入单行
来源：http://dali.zhoulong.xyz/Article/details/gtjlmagwrn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cheryme.top/Article/details/gtnwqggjyo.html

[Q11] 一次插入多行
来源：http://dali.chenlongwang.top/Article/details/gtimvknvqd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aizwys.cn/Article/details/gtendlpovr.html

[Q12] 插入后取自增 ID
来源：http://dali.iojbl.cn/Article/details/gtarvhryyb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tian-w.cn/Article/details/gtxewomfvz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yonumen.top/Article/details/gtzqsuusnk.html

[Q13] 忽略重复插入
来源：http://dali.jiagoushi.top/Article/details/gthxohvocp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yongpay.top/Article/details/gtaplofzry.html

[Q14] 存在则更新（upsert）
来源：http://dali.zycfv.cn/Article/details/gtfnditgex.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gogol.net.cn/Article/details/gtdbmunayl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tian-w.cn/Article/details/gtjpzukznm.html

[Q15] 查询全部
来源：http://dali.jinqigufen.top/Article/details/gtnaddxite.html

SELECT * FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtmkephsyc.html

[Q16] 查询指定列
来源：http://dali.9152youxi.cn/Article/details/gthoygntxq.html

SELECT id, name FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtbllwplcn.html

[Q17] 条件查询
来源：http://dali.daria6918.cn/Article/details/gtdeudiqun.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtxrvjbpza.html

[Q18] 模糊匹配
来源：http://dali.hysaishi.cn/Article/details/gtlgrhseao.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.guannengcc.top/Article/details/gtirjpnido.html

[Q19] 范围查询
来源：http://dali.chenjidiqi.icu/Article/details/gtqrwuimtn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigfzy.top/Article/details/gtnbgwfgec.html

[Q20] IN 列表
来源：http://dali.hnqzz.top/Article/details/gtuavajktl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ppjwa.cn/Article/details/gtjmwsnohi.html

[Q21] 空值判断
来源：http://dali.jianghu66.top/Article/details/gtlwtonfax.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gttdhhtyiq.html

[Q22] 排序
来源：http://dali.zycfv.cn/Article/details/gtaxjqedza.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gtbtvsuwjy.html

[Q23] 分页
来源：http://dali.shangyingyoupin.top/Article/details/gtcgxpweex.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwjtljwh.html

[Q24] 去重
来源：http://dali.yj202588.top/Article/details/gtyssnlhby.html

SELECT DISTINCT city FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtykomjrci.html

[Q25] 只取前 N 条
来源：http://dali.zhiwuduotai.top/Article/details/gtmfdlytfi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shanyushiyangtech.top/Article/details/gttowcqztc.html

[Q26] 计数
来源：http://dali.snrcjt.cn/Article/details/gtybbrrfos.html

SELECT COUNT(*) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtdqmddqvh.html

[Q27] 条件计数
来源：http://dali.wangshuangyany.cn/Article/details/gturetfegh.html


<!-- 参考信息 -->