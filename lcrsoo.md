代发 wailian999

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtejrhkhat.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj202588.top/Article/details/gtyglyzfwg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gtgdeizzrw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yueranfly.top/Article/details/gtrcnqyzzb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gtckkrhttt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gtlltacekf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhoulong.xyz/Article/details/gtjmjaslkb.html

Go:   slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gttjeocrii.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gtbudityaw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.havefunace.top/Article/details/gtirzbbadx.html

[N03] 快速排序（分治示例）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstyoymxw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmxoiilp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xinyue.icu/Article/details/gtwxpappeb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gtoubjxorc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gtarpbpskt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhengqikj.top/Article/details/gtcbixduza.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenzaomai.com/Article/details/gtmnnseevk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nanxuanxn.top/Article/details/gthktawkjv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jyoumei.cn/Article/details/gtocmqmyfg.html

[N04] 斐波那契数列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwaggrbm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gtmqidyhoi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gzhubu.top/Article/details/gttrmgjtpe.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtxrjjfidb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtkavqoavq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xinyue.icu/Article/details/gtiifnytwe.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ydzc1.top/Article/details/gtfvavqrvo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gtekntssuf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gttnwjueqn.html

[N05] 最大公约数
来源：http://dali.jinghuilouyu.cn/Article/details/gtzprazsat.html

Py:   math.gcd(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtjvexavsx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sxryk.cn/Article/details/gtmuldikkp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gtwcntqmtt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gtwqrvtwvs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.feifeiyinyue.top/Article/details/gtnjfslrfe.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daxiang520.top/Article/details/gtyjfvmrmc.html

Ruby: a.gcd(b)
来源：http://dali.shzxlz.cn/Article/details/gthpelfddm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nanxuanxn.top/Article/details/gtwqhtptov.html

[N06] 判断回文字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtratswpkm.html

Py:   s == s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gtftrkzazp.html

PHP:  $s === strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gtipanavoz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtmffvuxci.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtemnrmjut.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hammf.cn/Article/details/gtpqbbvreo.html

Go:   // 双指针从两端比较
来源：http://dali.wangshuangyany.cn/Article/details/gtxbhdiqze.html

Ruby: s == s.reverse
来源：http://dali.andypj.xyz/Article/details/gtezhktcvf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gtmrmoqqoh.html

[N07] 两数之和（返回下标）
来源：http://dali.316326.xyz/Article/details/gtfqtzvvpd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guowangkeji.top/Article/details/gtmsaesvdm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jianghu66.top/Article/details/gtukggoxex.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.mhx1999.top/Article/details/gtxnwpyvid.html

TS:   // 手写 Map<string, number>
来源：http://dali.xylfe.cn/Article/details/gtmvtmisoh.html

Java: // 手写 HashMap
来源：http://dali.chenjidiqi.icu/Article/details/gtpkcfuixy.html

Go:   // 手写 map[int]int
来源：http://dali.fzhhl.top/Article/details/gtqalsemda.html

Ruby: // 手写 Hash
来源：http://dali.tianlin.xyz/Article/details/gtfkzxxdsy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtaoyqme.html

[N08] 生成全排列
来源：http://dali.sxryk.cn/Article/details/gtstuqozja.html

Py:   itertools.permutations(arr)
来源：http://dali.guowangkeji.top/Article/details/gtmzlsezll.html

PHP:  // 手写递归交换
来源：http://dali.hongshengwenyu.top/Article/details/gtdmfintnd.html

JS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtpaqyuhbj.html

TS:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtseusltcu.html

Java: // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtjhtentrp.html

Go:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtjvqztxtk.html

Ruby: arr.permutation.to_a
来源：http://dali.meibo888.top/Article/details/gtklgguutx.html

C#:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtensfsyaf.html

[N09] 栈与队列
来源：http://dali.yonumen.top/Article/details/gtjvpmhjfu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hfpthk.cn/Article/details/gtjwhtxxcl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ivvv.top/Article/details/gtqkevfvqk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gtagfpuddm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj202588.top/Article/details/gtugmomwac.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cashguo.top/Article/details/gtaiteaqdp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.birdmap.top/Article/details/gtfxsrahxg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gtmnsrjwjp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yonumen.top/Article/details/gtbztmgtwf.html

[N10] 链表节点定义
来源：http://dali.yongpay.top/Article/details/gtiqzmvevg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jyoumei.cn/Article/details/gtetfilmtx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqymscjgv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cucudq.cn/Article/details/gtylqjcaoa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.snrcjt.cn/Article/details/gtastejqhe.html

Java: class Node { int v; Node next; }
来源：http://dali.ppjwa.cn/Article/details/gtbqfuixfd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangshuangyany.cn/Article/details/gtaideaglf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yangfankeji.com/Article/details/gtvcianxcl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.redwolf501.top/Article/details/gtyzvzngqf.html

[N11] 二叉树中序遍历
来源：http://dali.haohaochexian.top/Article/details/gtopvhdgoe.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.c1oappe.top/Article/details/gtwfpjcpsb.html

PHP:  // 手写递归函数
来源：http://dali.guowangkeji.top/Article/details/gthqlbkqgf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gtctiudepw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gtwcphayca.html

Java: // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtwjqnroye.html

Go:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gthnhyzksn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhixingplan.top/Article/details/gtnigenypz.html

C#:   // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gtlvuxivtx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cucudq.cn/Article/details/gtcbewyqea.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yueranfly.top/Article/details/gteouimdjn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgiwceco.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gtsjcpdczo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtfmorictj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtweyjgzbp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daria6918.cn/Article/details/gtflgtrcxf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gtflafzsum.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqaygngqs.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtbzawktzb.html

O. 并发与异步
来源：http://dali.cashguo.top/Article/details/gtsgapcdbi.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtirazmnkt.html

[O01] 启动一个线程
来源：http://dali.ydzc1.top/Article/details/gtqieloohl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fzhhl.top/Article/details/gtkstosbay.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.feifeiyinyue.top/Article/details/gtjakueldb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gtgiylfqnb.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gtkxkxlotm.html

Java: new Thread(() -> f()).start()
来源：http://dali.hywenlv.cn/Article/details/gtpvmriezw.html

Go:   go f()
来源：http://dali.aizwys.cn/Article/details/gtfqydepjd.html

Ruby: Thread.new { f }
来源：http://dali.nanxuanxn.top/Article/details/gtuwjxtelk.html

C#:   Task.Run(() => F());
来源：http://dali.sxryk.cn/Article/details/gtrlzsfvzj.html

[O02] 使用线程池
来源：http://dali.vqdsnc.cn/Article/details/gtooflalhm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hywenlv.cn/Article/details/gtusmpwxaj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsjkdzes.html

JS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gtokewyttj.html

TS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gthfzkkvra.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.vqdsnc.cn/Article/details/gtvsogakwa.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasytqnfy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aibaodan.cn/Article/details/gtexmbsnmm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cashguo.top/Article/details/gtwvwywvzn.html

[O03] 加锁保护共享数据
来源：http://dali.meibo888.top/Article/details/gtzylfeklc.html

Py:   with lock: shared += 1
来源：http://dali.chenlongwang.top/Article/details/gtsdctfoff.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhongyouzk.top/Article/details/gtytjaykcv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzwnvnph.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gtbcrfkaqu.html

Java: synchronized (this) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gtovzottxc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenzaomai.com/Article/details/gtuvfdlnoh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sysykeji.top/Article/details/gtoknahpsa.html

C#:   lock (gate) { shared++; }
来源：http://dali.9152youxi.cn/Article/details/gtddjjpcrv.html

[O04] 定义异步函数并等待
来源：http://dali.vqdsnc.cn/Article/details/gthnlgxkop.html

Py:   async def f():⏎    await g()
来源：http://dali.hywenlv.cn/Article/details/gtcirhmmht.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jyoumei.cn/Article/details/gtmthmkqki.html

JS:   async function f() { await g(); }
来源：http://dali.zycfv.cn/Article/details/gttkklujgx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sweek.top/Article/details/gtqcyeilll.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.9152youxi.cn/Article/details/gtwrxjxith.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkdudlvj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ydzc1.top/Article/details/gtortaeroh.html

C#:   async Task F() { await G(); }
来源：http://dali.havefunace.top/Article/details/gtafwhjbxj.html

[O05] 并发执行并等待全部完成
来源：http://dali.shangyingyoupin.top/Article/details/gtfzjwnqfy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.vqdsnc.cn/Article/details/gtuubyieve.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yuxming.cn/Article/details/gtjkvyumic.html

JS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gtblbyhgmi.html

TS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gtnqvsuxvl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhoulong.xyz/Article/details/gtfblusotm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yanxiufei.cn/Article/details/gtijcaehlc.html

Ruby: threads.map(&:join)
来源：http://dali.haohaochexian.top/Article/details/gtprjbtvoh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenzaomai.com/Article/details/gtuudssnyh.html

[O06] 使用进程池
来源：http://dali.gogol.net.cn/Article/details/gtjwcwkwpv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dianchejie.cn/Article/details/gttyinobqn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tanke756.top/Article/details/gtnpkeyyur.html

JS:   // child_process / cluster 模块
来源：http://dali.yvedp.cn/Article/details/gteqlahtgp.html

TS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gttaxwbtpo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nanxuanxn.top/Article/details/gtjdyioyql.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ivvv.top/Article/details/gtqvkncrwq.html

Ruby: // fork 块
来源：http://dali.wangdashe.top/Article/details/gtdfyxkona.html

C#:   Parallel.For
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbasvuike.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvdcyuihy.html

P. 常用工具函数
来源：http://dali.yonumen.top/Article/details/gtqtiqtpou.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gthqpqbgdt.html

[P01] 生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gtkdogrgrf.html

Py:   str(uuid.uuid4())
来源：http://dali.zhengqikj.top/Article/details/gtxoztrvow.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yvedp.cn/Article/details/gtyjaxozww.html

JS:   crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gtewbjknkc.html

TS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtxcbfvmju.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj202588.top/Article/details/gtosbeskpo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sweek.top/Article/details/gtmqircizw.html

Ruby: SecureRandom.uuid
来源：http://dali.dianchejie.cn/Article/details/gtwbeolger.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sysykeji.top/Article/details/gtbjpfuior.html

[P02] MD5 / SHA256 摘要
来源：http://dali.svipenyu.cn/Article/details/gtbpshinmr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.kuanghao11.cn/Article/details/gtvhdqczkw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jlsjyb.cn/Article/details/gtbmfhiwtj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guannengcc.top/Article/details/gtzalcbfgj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.bjfxy.top/Article/details/gtprhkdjwo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sxryk.cn/Article/details/gtjlvaphvm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxinkj.top/Article/details/gtkksmdqli.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258888.top/Article/details/gtzftlveel.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.mhx1999.top/Article/details/gtcmeeffco.html

[P03] 生成短随机字符串
来源：http://dali.cqqwz.cn/Article/details/gtunhoqfov.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shzxlz.cn/Article/details/gtewzbolux.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.guannengcc.top/Article/details/gthfdvcxma.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gtqztscmrf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnqzz.top/Article/details/gttybruysy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtcdftuydb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258888.top/Article/details/gtnohnvloh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xinyue.icu/Article/details/gtegkdmcti.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sweek.top/Article/details/gtgczxzzjd.html

[P04] 求长度
来源：http://dali.ehwqpu.com/Article/details/gtefrgcfbt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sysykeji.top/Article/details/gtoswgymbb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gtewwnpxgq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gtilpypimf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hongshengwenyu.top/Article/details/gtkqcnfrxg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigufen.top/Article/details/gtxetkiokl.html

Go:   len(arr);  len(m)
来源：http://dali.shangyingyoupin.top/Article/details/gtvddcataz.html

Ruby: x.length;  x.size
来源：http://dali.zhongyouzk.top/Article/details/gtwvfsjpbk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cqqwz.cn/Article/details/gtohvwfalr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhongyouzk.top/Article/details/gttiugcoqx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.bjfxy.top/Article/details/gtxnlhqada.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hywenlv.cn/Article/details/gtqlodcjze.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nwbrower.top/Article/details/gtrayxkeoj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gthnrathcc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhoulong.xyz/Article/details/gtuyaianzu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258888.top/Article/details/gtrlodseeo.html

Ruby: a == b
来源：http://dali.hongshengwenyu.top/Article/details/gtxlfuzpnt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigfzy.top/Article/details/gtnxwdysyl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yanxiufei.cn/Article/details/gtavzbvnlk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cucudq.cn/Article/details/gtuhndgdcs.html

PHP:  if (empty($x)) {}
来源：http://dali.cheryme.top/Article/details/gtfhvokebv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.316326.xyz/Article/details/gtowtqmtoa.html

TS:   if (x == null) {}
来源：http://dali.yongpay.top/Article/details/gtcqragibk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gttpiaenzi.html

Go:   if x == nil {}
来源：http://dali.fengsongda.top/Article/details/gtsvsmtkco.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.bjfxy.top/Article/details/gtbxpvqwij.html

C#:   if (x is null) {}
来源：http://dali.gzhubu.top/Article/details/gtkllxjnko.html

[P07] 防抖与节流
来源：http://dali.mhx1999.top/Article/details/gtueolqqqq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tanke756.top/Article/details/gtvguhqrcx.html

PHP:  // 手写时间戳比较
来源：http://dali.hysaishi.cn/Article/details/gtxhhorbwt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gtttoevyau.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gtbnthantd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ppjwa.cn/Article/details/gtplahdsai.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.smart0.xyz/Article/details/gtrfdkocpf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.redwolf501.top/Article/details/gtglysbvtt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daxiang520.top/Article/details/gtepgxknyr.html

[P08] 处理浮点精度问题
来源：http://dali.gotoacloud.top/Article/details/gtdrzncspj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hnqzz.top/Article/details/gtedqlmafq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yangfankeji.com/Article/details/gtduyrpyra.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.havefunace.top/Article/details/gtfrwchcsq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cqqwz.cn/Article/details/gtoaswnhus.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoluqlmoj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xuetiantiany.cn/Article/details/gtqrjxpkxe.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.quarkkingdee.top/Article/details/gtkfppiuav.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.316326.xyz/Article/details/gtrqntggdt.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtcjsgiico.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.wangshuangyany.cn/Article/details/gttymzvgtc.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtralufhxz.html

[Q01] 创建表
来源：http://dali.aibaodan.cn/Article/details/gtbmymxewv.html

CREATE TABLE users (
来源：http://dali.0kj1m.cn/Article/details/gtcobtxowb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gtxvuekhfw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ehwqpu.com/Article/details/gtcmorxuzx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cheryme.top/Article/details/gtnfftynsp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xinyue.icu/Article/details/gtxtlpcyjd.html

);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthibaiwpo.html

[Q02] 创建带外键的表
来源：http://dali.havefunace.top/Article/details/gtafzwrcxj.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gtqsbhgplo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gtktmjvsuv.html

user_id INT NOT NULL,
来源：http://dali.hysaishi.cn/Article/details/gtwieeudot.html

amount DECIMAL(10, 2),
来源：http://dali.zdqjudy.top/Article/details/gtafivoqwz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gogol.net.cn/Article/details/gtpyokbbcy.html

);
来源：http://dali.hysaishi.cn/Article/details/gtpkxflnie.html

[Q03] 增加列
来源：http://dali.nanxuanxn.top/Article/details/gtfffwzayt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gaohongyu789.top/Article/details/gtalreoahg.html

[Q04] 修改列类型
来源：http://dali.cashguo.top/Article/details/gtsvqieifp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.aibaodan.cn/Article/details/gtlftxhqik.html

[Q05] 重命名列
来源：http://dali.wangdashe.top/Article/details/gtidagssti.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jyoumei.cn/Article/details/gtysqrxkbp.html

[Q06] 删除列
来源：http://dali.jqgfzy.top/Article/details/gtlbnoluqq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nwbrower.top/Article/details/gtjuwuuepi.html

[Q07] 删除表
来源：http://dali.tanke756.top/Article/details/gtmruqtzof.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aibaodan.cn/Article/details/gtjdemjwee.html

[Q08] 创建普通索引
来源：http://dali.cqqwz.cn/Article/details/gtwfjqibfd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nwbrower.top/Article/details/gtkictxyde.html

[Q09] 创建唯一索引
来源：http://dali.chenlongwang.top/Article/details/gtawmcsvga.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gtmpibctpb.html

[Q10] 插入单行
来源：http://dali.snrcjt.cn/Article/details/gtxfhjulzo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.havefunace.top/Article/details/gtpjkzdrzv.html

[Q11] 一次插入多行
来源：http://dali.xuetiantiany.cn/Article/details/gttwnflrhg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sxryk.cn/Article/details/gtyvxkvtbc.html

[Q12] 插入后取自增 ID
来源：http://dali.cucudq.cn/Article/details/gtkslnikrr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenjidiqi.icu/Article/details/gtarvktjqa.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.guannengcc.top/Article/details/gtnfmwhida.html

[Q13] 忽略重复插入
来源：http://dali.guowangkeji.top/Article/details/gtpfdygrvm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gtxiomlknp.html

[Q14] 存在则更新（upsert）
来源：http://dali.jiagoushi.top/Article/details/gtbddorqvo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinghuilouyu.cn/Article/details/gttjfeiuhd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhoulong.xyz/Article/details/gtjljxvdcl.html

[Q15] 查询全部
来源：http://dali.havefunace.top/Article/details/gtdwctmwyj.html

SELECT * FROM users;
来源：http://dali.cheryme.top/Article/details/gthnhvlrlw.html

[Q16] 查询指定列
来源：http://dali.jyoumei.cn/Article/details/gtghicjlrr.html

SELECT id, name FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtfwnndfxb.html

[Q17] 条件查询
来源：http://dali.hammf.cn/Article/details/gtjfemmruc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jiagoushi.top/Article/details/gttsnfoarg.html

[Q18] 模糊匹配
来源：http://dali.guannengcc.top/Article/details/gtktzdbiyf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sysykeji.top/Article/details/gtdsedtgdn.html

[Q19] 范围查询
来源：http://dali.birdmap.top/Article/details/gteixsupmo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.quarkkingdee.top/Article/details/gtrfdlctad.html

[Q20] IN 列表
来源：http://dali.pengpengdd.cyou/Article/details/gtrwhbqpyx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.daria6918.cn/Article/details/gtvjrvzlde.html

[Q21] 空值判断
来源：http://dali.hywenlv.cn/Article/details/gtpqdbiiol.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.316326.xyz/Article/details/gtaxwhejvh.html

[Q22] 排序
来源：http://dali.cdnleiting.top/Article/details/gthomjcftr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.birdmap.top/Article/details/gtfkaelwey.html

[Q23] 分页
来源：http://dali.cheryme.top/Article/details/gtxzjmezez.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pycfn.com/Article/details/gtslfumgzr.html

[Q24] 去重
来源：http://dali.shzxlz.cn/Article/details/gtdktdmsqa.html

SELECT DISTINCT city FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtihxlcbtt.html

[Q25] 只取前 N 条
来源：http://dali.nanxuanxn.top/Article/details/gtsomhldla.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjoduneb.html

[Q26] 计数
来源：http://dali.jqgfzy.top/Article/details/gtsjaqofge.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtbyuxlvjh.html

[Q27] 条件计数
来源：http://dali.hywenlv.cn/Article/details/gtmcupoqfo.html


<!-- 参考信息 -->