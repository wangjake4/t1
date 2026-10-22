代发 wailian999

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtwgnmqndp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.mhx1999.top/Article/details/gtidesdjfh.html

[N03] 快速排序（分治示例）
来源：http://dali.cheryme.top/Article/details/gtvlbyxziw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zycfv.cn/Article/details/gtassgzaen.html

PHP:  // 递归实现，或用 usort
来源：http://dali.316326.xyz/Article/details/gtdcoyvlzd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gtbfnhngtl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gtrxywfbbi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.kuanghao11.cn/Article/details/gtqlotwxiz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zdqjudy.top/Article/details/gtvnfbplvj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nanxinkj.top/Article/details/gtjwtchxzp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhoulong.xyz/Article/details/gtgvdyvujg.html

[N04] 斐波那契数列
来源：http://dali.daxiang520.top/Article/details/gtdqqkfmnz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gtswvqfqpz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nwbrower.top/Article/details/gtfjkdjcjg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtkmbqiefz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtvozhecnj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sysykeji.top/Article/details/gtfzmavtsa.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.smart0.xyz/Article/details/gtzqynoein.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gtxcwviwgw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtavjinyeg.html

[N05] 最大公约数
来源：http://dali.birdmap.top/Article/details/gtmsmzromb.html

Py:   math.gcd(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtonoilboc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dashuyun.cn/Article/details/gtcxeilevz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gtwdunjsrh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwglodklj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jiagoushi.top/Article/details/gthxpilxge.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.haohaochexian.top/Article/details/gtficankhi.html

Ruby: a.gcd(b)
来源：http://dali.zycfv.cn/Article/details/gteoxevbjy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yanxiufei.cn/Article/details/gtpskfaqkh.html

[N06] 判断回文字符串
来源：http://dali.zycfv.cn/Article/details/gtgsbrwbif.html

Py:   s == s[::-1]
来源：http://dali.sweek.top/Article/details/gtineagkmv.html

PHP:  $s === strrev($s);
来源：http://dali.birdmap.top/Article/details/gtmtneckwh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtfstkgmye.html

TS:   s === [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtumbnwudw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigfzy.top/Article/details/gtblauvbow.html

Go:   // 双指针从两端比较
来源：http://dali.aizwys.cn/Article/details/gtwjtkbqxq.html

Ruby: s == s.reverse
来源：http://dali.guowangkeji.top/Article/details/gtlllchjsc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gzhubu.top/Article/details/gtjmqtvghq.html

[N07] 两数之和（返回下标）
来源：http://dali.zhengqikj.top/Article/details/gtysmpcsmh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangtech.top/Article/details/gtgyonwdbj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhoulong.xyz/Article/details/gtamljbssc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aizwys.cn/Article/details/gtfyhieomz.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinqigufen.top/Article/details/gtfeqegkhc.html

Java: // 手写 HashMap
来源：http://dali.tanke756.top/Article/details/gtrvfvjhwr.html

Go:   // 手写 map[int]int
来源：http://dali.andypj.xyz/Article/details/gtrqeyeujp.html

Ruby: // 手写 Hash
来源：http://dali.ehwqpu.com/Article/details/gtghtutitp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xinyue.icu/Article/details/gtxicwnmyo.html

[N08] 生成全排列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlaaidzan.html

Py:   itertools.permutations(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtxggfpoht.html

PHP:  // 手写递归交换
来源：http://dali.jinqigfzy.top/Article/details/gtppopmwlg.html

JS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gthdcshwyl.html

TS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtppdzjhjr.html

Java: // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtvxamgtyv.html

Go:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gthgmyucmt.html

Ruby: arr.permutation.to_a
来源：http://dali.sufxvd.cn/Article/details/gtlswgxudv.html

C#:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtorbvqnps.html

[N09] 栈与队列
来源：http://dali.nwbrower.top/Article/details/gtvrjlcwez.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gzhubu.top/Article/details/gtunogmxva.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtfexvtkbt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gtakgxrnha.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhiwuduotai.top/Article/details/gtrodufals.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxinkj.top/Article/details/gtyfoibxrq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yueranfly.top/Article/details/gtayqqxcbz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gtujfzdbtw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yongpay.top/Article/details/gtyhhczlqf.html

[N10] 链表节点定义
来源：http://dali.mhx1999.top/Article/details/gtjewcnvkr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.redwolf501.top/Article/details/gtjionmalr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigufen.top/Article/details/gtpjuzrtuz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aibaodan.cn/Article/details/gthqkjuejy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sysykeji.top/Article/details/gttstmfrqp.html

Java: class Node { int v; Node next; }
来源：http://dali.gotoacloud.top/Article/details/gtkphsmmht.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hnqzz.top/Article/details/gtxzqcglue.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.smart0.xyz/Article/details/gtjcwusccl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hongshengwenyu.top/Article/details/gtghpjmxst.html

[N11] 二叉树中序遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtpbndrtqx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hongshengwenyu.top/Article/details/gtnpmsqltt.html

PHP:  // 手写递归函数
来源：http://dali.jiagoushi.top/Article/details/gtaiqdnvaz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cashguo.top/Article/details/gtefinpiqf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhoulong.xyz/Article/details/gtiznaurqq.html

Java: // 手写递归
来源：http://dali.sweek.top/Article/details/gtkirnfiyx.html

Go:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gtotekrrki.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pycfn.com/Article/details/gtjmkqwsby.html

C#:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gtcovxvadm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtifvzethi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xylfe.cn/Article/details/gtiobixzli.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrwgdgdq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hywenlv.cn/Article/details/gttylgnpfz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangshuangyany.cn/Article/details/gttomvgclk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gtqfpvcrkv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.wangdashe.top/Article/details/gtitmbehru.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.bjfxy.top/Article/details/gtskasrncn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gtliuhozre.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtvggxupwi.html

O. 并发与异步
来源：http://dali.zhongyouzk.top/Article/details/gtdeijbngx.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtwpdcyqxr.html

[O01] 启动一个线程
来源：http://dali.sufxvd.cn/Article/details/gtemywdapr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ybcxt.top/Article/details/gttzjxbrxi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jqgfzy.top/Article/details/gtlgzvfvza.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shangyingyoupin.top/Article/details/gtlmuhumwm.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmikftby.html

Java: new Thread(() -> f()).start()
来源：http://dali.sweek.top/Article/details/gtfpwqtjed.html

Go:   go f()
来源：http://dali.dashuyun.cn/Article/details/gteammzgnl.html

Ruby: Thread.new { f }
来源：http://dali.cdnleiting.top/Article/details/gtutdjyadn.html

C#:   Task.Run(() => F());
来源：http://dali.dianchejie.cn/Article/details/gtzherozaj.html

[O02] 使用线程池
来源：http://dali.hywenlv.cn/Article/details/gtadvwpvmh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xziqi.cn/Article/details/gtrehrvvih.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sweek.top/Article/details/gtibggwylf.html

JS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gtoncsbloq.html

TS:   // worker_threads 线程池
来源：http://dali.kuanghao11.cn/Article/details/gtesnfueaz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.havefunace.top/Article/details/gtdquszbng.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cdnleiting.top/Article/details/gtauqrhyrv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jyoumei.cn/Article/details/gtyvxuabxz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shuidangran.top/Article/details/gtqkmoplyf.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gtozkrakby.html

Py:   with lock: shared += 1
来源：http://dali.0kj1m.cn/Article/details/gtlfpmxynf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hysaishi.cn/Article/details/gtqkfcuaba.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhoulong.xyz/Article/details/gtfmjlrrys.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gthsxtvkvp.html

Java: synchronized (this) { shared++; }
来源：http://dali.yongpay.top/Article/details/gtkwqkrwvf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shuidangran.top/Article/details/gtjkogtxop.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yonumen.top/Article/details/gtxnjuimea.html

C#:   lock (gate) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gtyvmrlsrv.html

[O04] 定义异步函数并等待
来源：http://dali.sweek.top/Article/details/gtjglseabr.html

Py:   async def f():⏎    await g()
来源：http://dali.wangdashe.top/Article/details/gtsszoqobw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhoulong.xyz/Article/details/gtajfahggh.html

JS:   async function f() { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gtzkaihgwz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jyoumei.cn/Article/details/gtcjwboavm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fzhhl.top/Article/details/gtqqtkohxm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangtech.top/Article/details/gtudsymeyv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.316326.xyz/Article/details/gtsupwbwnj.html

C#:   async Task F() { await G(); }
来源：http://dali.tianlin.xyz/Article/details/gtstgyyvsv.html

[O05] 并发执行并等待全部完成
来源：http://dali.yonumen.top/Article/details/gtvcdguwdv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.snrcjt.cn/Article/details/gtpltxmvgt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.feifeiyinyue.top/Article/details/gtfbucjybw.html

JS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gtsqywjypv.html

TS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpnzfabtt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.aibaodan.cn/Article/details/gtzfcjidxb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.9152youxi.cn/Article/details/gtonkiedzq.html

Ruby: threads.map(&:join)
来源：http://dali.c1oappe.top/Article/details/gtvcgptxzv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pengpengdd.cyou/Article/details/gtcpjxkanw.html

[O06] 使用进程池
来源：http://dali.xziqi.cn/Article/details/gtxnburymg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gaohongyu789.top/Article/details/gtpepvtkvb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gzhubu.top/Article/details/gtqplxgajn.html

JS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gtsucpwwbh.html

TS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gtkywnmewy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.smart0.xyz/Article/details/gtcykbqslc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nwbrower.top/Article/details/gtkblnapek.html

Ruby: // fork 块
来源：http://dali.hammf.cn/Article/details/gtsfzmmled.html

C#:   Parallel.For
来源：http://dali.nwbrower.top/Article/details/gtpaprkyet.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkaoekco.html

P. 常用工具函数
来源：http://dali.daria6918.cn/Article/details/gtglnlqsll.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtykzcjsoe.html

[P01] 生成 UUID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbcruqog.html

Py:   str(uuid.uuid4())
来源：http://dali.dianchejie.cn/Article/details/gtobdqbzva.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yongpay.top/Article/details/gtdljrrenq.html

JS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gtgiflrzfz.html

TS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gtebkkcgoy.html

Java: UUID.randomUUID().toString()
来源：http://dali.c1oappe.top/Article/details/gtznoillwv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dashuyun.cn/Article/details/gtrsvedkfe.html

Ruby: SecureRandom.uuid
来源：http://dali.cucudq.cn/Article/details/gthxhwipxc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenjidiqi.icu/Article/details/gtxmzhpcbn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.316326.xyz/Article/details/gtofzerpfu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gaohongyu789.top/Article/details/gtptxofjer.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258888.top/Article/details/gtpjranaod.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aizwys.cn/Article/details/gtihdzphyf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.svipenyu.cn/Article/details/gteltxsrjq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.aizwys.cn/Article/details/gtnwptmaqt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.feifeiyinyue.top/Article/details/gtroqeucpf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258888.top/Article/details/gtmjizhiig.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangshuangyany.cn/Article/details/gtfmthrzor.html

[P03] 生成短随机字符串
来源：http://dali.9152youxi.cn/Article/details/gtskdpnomq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.smart0.xyz/Article/details/gtjeiaivck.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yonumen.top/Article/details/gtbjuhqcub.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj202588.top/Article/details/gtrilfsjvr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xinyue.icu/Article/details/gtsfaeiwjz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sxryk.cn/Article/details/gttmvayieh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwqoycdk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sysykeji.top/Article/details/gtvtbpnqjs.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.0kj1m.cn/Article/details/gtrrfdbuuo.html

[P04] 求长度
来源：http://dali.sysykeji.top/Article/details/gtzwtashux.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhoulong.xyz/Article/details/gtqmsdfgul.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtjuevamof.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gtfvuchibz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hongshengwenyu.top/Article/details/gtfugmgmyc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gtnmdxupyi.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258.top/Article/details/gtcnrobnqh.html

Ruby: x.length;  x.size
来源：http://dali.redwolf501.top/Article/details/gtygwpeyme.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.meibo888.top/Article/details/gtlgmghjbr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hammf.cn/Article/details/gteivrnwci.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.andypj.xyz/Article/details/gtfxzitdru.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gzhubu.top/Article/details/gtwufanzzj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.meibo888.top/Article/details/gtwqkushdu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenjidiqi.icu/Article/details/gticrapacr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.meibo888.top/Article/details/gtxlyxfcoe.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gtzlujnhqs.html

Ruby: a == b
来源：http://dali.shangyingyoupin.top/Article/details/gtixqulttb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.c1oappe.top/Article/details/gtlnpbewvt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gaohongyu789.top/Article/details/gtoquijnve.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jianghu66.top/Article/details/gtpkinispq.html

PHP:  if (empty($x)) {}
来源：http://dali.birdmap.top/Article/details/gtjyyxiuis.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.vqdsnc.cn/Article/details/gtlxtyuuov.html

TS:   if (x == null) {}
来源：http://dali.snrcjt.cn/Article/details/gtnexhoyem.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmofqskw.html

Go:   if x == nil {}
来源：http://dali.zhengqikj.top/Article/details/gtltxalxwm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hfpthk.cn/Article/details/gtnwsqdcin.html

C#:   if (x is null) {}
来源：http://dali.gotoacloud.top/Article/details/gtkduauetc.html

[P07] 防抖与节流
来源：http://dali.dianchejie.cn/Article/details/gtuitegiki.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.pengpengdd.cyou/Article/details/gtcttvqkeu.html

PHP:  // 手写时间戳比较
来源：http://dali.snrcjt.cn/Article/details/gtusdptkod.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gtidehsoll.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gtevgygblg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigufen.top/Article/details/gtvbpygopu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sweek.top/Article/details/gtygzghrqf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.haohaochexian.top/Article/details/gtrrphqhix.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.c1oappe.top/Article/details/gtehifllhq.html

[P08] 处理浮点精度问题
来源：http://dali.hysaishi.cn/Article/details/gteilvirym.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gotoacloud.top/Article/details/gtwxwslwje.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.aizwys.cn/Article/details/gtmmvhvhlh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dashuyun.cn/Article/details/gtefukwgws.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gtxzoesxru.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.guannengcc.top/Article/details/gtoiyywhzl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jqgfzy.top/Article/details/gtzolritee.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sufxvd.cn/Article/details/gtjfjngfxh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhongyouzk.top/Article/details/gtmyqdgulu.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzbybmdj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhongyouzk.top/Article/details/gtsxmnllkf.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtjuvjxoqp.html

[Q01] 创建表
来源：http://dali.yangfankeji.com/Article/details/gtchwyauab.html

CREATE TABLE users (
来源：http://dali.andypj.xyz/Article/details/gtenaukeof.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gtuzrnctln.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gtfhhukooe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yangfankeji.com/Article/details/gtggjxbiom.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ywan-chungtsiang.top/Article/details/gttrzdbkkx.html

);
来源：http://dali.yuanzhike.top/Article/details/gtziaoijly.html

[Q02] 创建带外键的表
来源：http://dali.sweek.top/Article/details/gtlytsrswc.html

CREATE TABLE orders (
来源：http://dali.jlsjyb.cn/Article/details/gtbzznxqag.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gtmxgjhnre.html

user_id INT NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gtsnkjzxja.html

amount DECIMAL(10, 2),
来源：http://dali.xylfe.cn/Article/details/gtgootitgy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yueranfly.top/Article/details/gtlglyimax.html

);
来源：http://dali.redwolf501.top/Article/details/gtdhlxefqn.html

[Q03] 增加列
来源：http://dali.yj20258888.top/Article/details/gtpmzngzob.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwmxvzvu.html

[Q04] 修改列类型
来源：http://dali.shangyingyoupin.top/Article/details/gtbrftrgll.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuanzhike.top/Article/details/gtobezffcl.html

[Q05] 重命名列
来源：http://dali.cucudq.cn/Article/details/gtcypaciao.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xziqi.cn/Article/details/gtrgltwcep.html

[Q06] 删除列
来源：http://dali.zycfv.cn/Article/details/gtbpqcjrpg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yanxiufei.cn/Article/details/gtbfxonpyw.html

[Q07] 删除表
来源：http://dali.fengsongda.top/Article/details/gtzbixtewu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtgvtyfjhc.html

[Q08] 创建普通索引
来源：http://dali.feifeiyinyue.top/Article/details/gtwluddpwa.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqrogetm.html

[Q09] 创建唯一索引
来源：http://dali.nanxuanxn.top/Article/details/gtwjrgtlxg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gtxuxnkoyv.html

[Q10] 插入单行
来源：http://dali.vqdsnc.cn/Article/details/gtggonveam.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtopdihnsb.html

[Q11] 一次插入多行
来源：http://dali.cashguo.top/Article/details/gtxnkjiduc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtecixblcj.html

[Q12] 插入后取自增 ID
来源：http://dali.hammf.cn/Article/details/gtrciijwil.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yuanzhike.top/Article/details/gtqgrsrtvt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhoulong.xyz/Article/details/gteusalrlk.html

[Q13] 忽略重复插入
来源：http://dali.mhx1999.top/Article/details/gtstixptju.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj202588.top/Article/details/gtxlqoqkkf.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhengqikj.top/Article/details/gtwvvofuyk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sxryk.cn/Article/details/gtbspvyrng.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdqvamix.html

[Q15] 查询全部
来源：http://dali.zdqjudy.top/Article/details/gtgheajpqh.html

SELECT * FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbocnvbcq.html

[Q16] 查询指定列
来源：http://dali.snrcjt.cn/Article/details/gtlbhpnqng.html

SELECT id, name FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtidsgtttk.html

[Q17] 条件查询
来源：http://dali.daria6918.cn/Article/details/gtgrazpsai.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gogol.net.cn/Article/details/gtdfojrjte.html

[Q18] 模糊匹配
来源：http://dali.hammf.cn/Article/details/gtnfnmbuxs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.birdmap.top/Article/details/gtflcmpusy.html

[Q19] 范围查询
来源：http://dali.jianghu66.top/Article/details/gtqwfqkxfl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.feifeiyinyue.top/Article/details/gtqhnfhacf.html

[Q20] IN 列表
来源：http://dali.xylfe.cn/Article/details/gtsxjjnagp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cucudq.cn/Article/details/gtwgmefcle.html

[Q21] 空值判断
来源：http://dali.aizwys.cn/Article/details/gtsqpnyzmi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.dashuyun.cn/Article/details/gtkhqlkprk.html

[Q22] 排序
来源：http://dali.ydzc1.top/Article/details/gttowhasaj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj20258.top/Article/details/gtbvjyfxfd.html

[Q23] 分页
来源：http://dali.ppjwa.cn/Article/details/gtgyfmhmwc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.iojbl.cn/Article/details/gthqwjkhdk.html

[Q24] 去重
来源：http://dali.xuanzx.com/Article/details/gtecvexqai.html

SELECT DISTINCT city FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtpojuvksh.html

[Q25] 只取前 N 条
来源：http://dali.yangfankeji.com/Article/details/gtdnfvgofn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.feifeiyinyue.top/Article/details/gtjgjrmnwn.html

[Q26] 计数
来源：http://dali.shzxlz.cn/Article/details/gtlygzjsoq.html

SELECT COUNT(*) FROM users;
来源：http://dali.ivvv.top/Article/details/gtpodlospf.html

[Q27] 条件计数
来源：http://dali.hfpthk.cn/Article/details/gtksnzlyrf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtikpytmdx.html

[Q28] 求和与平均
来源：http://dali.yuxming.cn/Article/details/gtqzewascy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtygoompgr.html

[Q29] 最大最小值
来源：http://dali.yvedp.cn/Article/details/gtkfvjhooi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtrfqktotj.html

[Q30] 分组统计
来源：http://dali.wangshuangyany.cn/Article/details/gtpywilrfz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gthgsdfyia.html

[Q31] 分组后过滤
来源：http://dali.316326.xyz/Article/details/gtrazbxtpf.html


<!-- 参考信息 -->