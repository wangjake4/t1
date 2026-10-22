代发 wailian999

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtjyffimjv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gteroxpasd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnxiangtu.top/Article/details/gtlxwytilo.html

Go:   slices.Sort(arr)
来源：http://dali.gzhubu.top/Article/details/gttvniatnq.html

Ruby: arr.sort
来源：http://dali.pengpengdd.cyou/Article/details/gtlhdddjsl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guowangkeji.top/Article/details/gtopaupssq.html

[N03] 快速排序（分治示例）
来源：http://dali.pengpengdd.cyou/Article/details/gttrenjgwu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ybcxt.top/Article/details/gtngrrurfp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daria6918.cn/Article/details/gtqdxdvinz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gtzuadmzki.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gtlnycqfim.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dianchejie.cn/Article/details/gtuszaqnnw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhoulong.xyz/Article/details/gtekbypfaq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cashguo.top/Article/details/gtmygnweez.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dashuyun.cn/Article/details/gtczbemcgi.html

[N04] 斐波那契数列
来源：http://dali.chenjidiqi.icu/Article/details/gtsoewhbwo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtynnfvirp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.smart0.xyz/Article/details/gtuaydcyrv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gttdoeckir.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtvcmlrmap.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gtlufzgwqz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yvedp.cn/Article/details/gtrvsmtwmy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnlmwjvf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtcwyuaxni.html

[N05] 最大公约数
来源：http://dali.yongpay.top/Article/details/gtmnqikbyi.html

Py:   math.gcd(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtonjgtiwk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.birdmap.top/Article/details/gtcutatyrg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigufen.top/Article/details/gthivjksfb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzkhfmhu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xylfe.cn/Article/details/gtjjehrfxu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.pycfn.com/Article/details/gtlyvwdkzq.html

Ruby: a.gcd(b)
来源：http://dali.316326.xyz/Article/details/gtjyuuehho.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.0kj1m.cn/Article/details/gtjwcnkegx.html

[N06] 判断回文字符串
来源：http://dali.yongpay.top/Article/details/gtjkdcosul.html

Py:   s == s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gtfnngchiv.html

PHP:  $s === strrev($s);
来源：http://dali.aizwys.cn/Article/details/gtiysvvmum.html

JS:   s === [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtqhanknxz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtravnqcpx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cheryme.top/Article/details/gtxmtlobkl.html

Go:   // 双指针从两端比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbelnouym.html

Ruby: s == s.reverse
来源：http://dali.shzxlz.cn/Article/details/gtnyalcqkk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gttlwmwlgl.html

[N07] 两数之和（返回下标）
来源：http://dali.yj202588.top/Article/details/gtsetqyork.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jlsjyb.cn/Article/details/gtrwlahklh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.vqdsnc.cn/Article/details/gtufergqnh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.quarkkingdee.top/Article/details/gtextlkknk.html

TS:   // 手写 Map<string, number>
来源：http://dali.cdnleiting.top/Article/details/gtuvsmhyjc.html

Java: // 手写 HashMap
来源：http://dali.birdmap.top/Article/details/gtswwsgmaj.html

Go:   // 手写 map[int]int
来源：http://dali.hywenlv.cn/Article/details/gtvdbnlpzj.html

Ruby: // 手写 Hash
来源：http://dali.hfpthk.cn/Article/details/gtkdjvuudp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shzxlz.cn/Article/details/gtuqawmutc.html

[N08] 生成全排列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaoxzubbg.html

Py:   itertools.permutations(arr)
来源：http://dali.fengsongda.top/Article/details/gtnsgribrr.html

PHP:  // 手写递归交换
来源：http://dali.0kj1m.cn/Article/details/gtkddtngnz.html

JS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtpzoxozpb.html

TS:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtadyxxijc.html

Java: // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtotjbfcfg.html

Go:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gteyvjhkgb.html

Ruby: arr.permutation.to_a
来源：http://dali.dianchejie.cn/Article/details/gthglfvgcw.html

C#:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtkvvkbnjp.html

[N09] 栈与队列
来源：http://dali.c1oappe.top/Article/details/gtdvwxlrzw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tian-w.cn/Article/details/gtmxeehnhk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.aizwys.cn/Article/details/gtwmetgzsy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gttkrlgvxg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jyoumei.cn/Article/details/gtwlhzoebo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ivvv.top/Article/details/gtfzqyupbz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhengqikj.top/Article/details/gtburlzjrr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtazvwelgz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaovklaqa.html

[N10] 链表节点定义
来源：http://dali.ehwqpu.com/Article/details/gtodxbrogp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cheryme.top/Article/details/gtjlayikkn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xuanzx.com/Article/details/gtcarrgifv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tanke756.top/Article/details/gtdpkigbls.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jianghu66.top/Article/details/gtjvxtccnh.html

Java: class Node { int v; Node next; }
来源：http://dali.meibo888.top/Article/details/gtwqexgugr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.quarkkingdee.top/Article/details/gtcfccpwrw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.smart0.xyz/Article/details/gtnvklsceg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xylfe.cn/Article/details/gtshtkrbgb.html

[N11] 二叉树中序遍历
来源：http://dali.mhx1999.top/Article/details/gtfoiaqftx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fengsongda.top/Article/details/gtrzakqowa.html

PHP:  // 手写递归函数
来源：http://dali.yj20258888.top/Article/details/gtcivabqlu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gtegrbwluh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujztrlmg.html

Java: // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gtfktrmrxs.html

Go:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gtzqxvlepl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cucudq.cn/Article/details/gtbgqdakwd.html

C#:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gthxvgxbrl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhengqikj.top/Article/details/gtpyoxfrxf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sysykeji.top/Article/details/gtsudzzyyj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jqgufenzy.top/Article/details/gtjqhrrzji.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwupqtxks.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhixingplan.top/Article/details/gtzlvsbpne.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gtzlfmgdjd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlnibzdc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shuidangran.top/Article/details/gtpzakrxxy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gtgwvnwshr.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtksdqsnqe.html

O. 并发与异步
来源：http://dali.yonumen.top/Article/details/gtikwfovlf.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtnxnncmdv.html

[O01] 启动一个线程
来源：http://dali.gaohongyu789.top/Article/details/gtngpqiviq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.havefunace.top/Article/details/gtysyyximi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gaohongyu789.top/Article/details/gthkwkgthd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shuidangran.top/Article/details/gtnppxwezs.html

TS:   // 同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtexdddzel.html

Java: new Thread(() -> f()).start()
来源：http://dali.yueranfly.top/Article/details/gtttzxopmv.html

Go:   go f()
来源：http://dali.jinqigufen.top/Article/details/gtsjbrwlsu.html

Ruby: Thread.new { f }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdsesshct.html

C#:   Task.Run(() => F());
来源：http://dali.zhengqikj.top/Article/details/gtgrujzpcy.html

[O02] 使用线程池
来源：http://dali.xuanzx.com/Article/details/gtvsrsnguw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gogol.net.cn/Article/details/gtqxaiaaqq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhoulong.xyz/Article/details/gtpmntlhpz.html

JS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gtbiiptazv.html

TS:   // worker_threads 线程池
来源：http://dali.zhixingplan.top/Article/details/gtquxvekvm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgufenzy.top/Article/details/gteflbvyia.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hfpthk.cn/Article/details/gtkgbviypk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yvedp.cn/Article/details/gttgxqnfwe.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinghuilouyu.cn/Article/details/gtduabwftd.html

[O03] 加锁保护共享数据
来源：http://dali.zhixingplan.top/Article/details/gtzbaaeoko.html

Py:   with lock: shared += 1
来源：http://dali.smart0.xyz/Article/details/gtcemfrury.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhoulong.xyz/Article/details/gtunpbcebs.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.andypj.xyz/Article/details/gtlakquqrf.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gtygikhnlv.html

Java: synchronized (this) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gtuytvftbm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sxryk.cn/Article/details/gttvtvwohc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgagymufe.html

C#:   lock (gate) { shared++; }
来源：http://dali.tanke756.top/Article/details/gtpixperii.html

[O04] 定义异步函数并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxafizcsj.html

Py:   async def f():⏎    await g()
来源：http://dali.hammf.cn/Article/details/gtxzvnqcdy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nwbrower.top/Article/details/gtlgxfvucg.html

JS:   async function f() { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gtmgdmnhmr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gtsxzseann.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhixingplan.top/Article/details/gtgknquznt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.smart0.xyz/Article/details/gtkcvtelvx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ybcxt.top/Article/details/gtwetvhudu.html

C#:   async Task F() { await G(); }
来源：http://dali.bjfxy.top/Article/details/gteemzqiys.html

[O05] 并发执行并等待全部完成
来源：http://dali.pengpengdd.cyou/Article/details/gtbzivjqme.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shzxlz.cn/Article/details/gtuykdclti.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aibaodan.cn/Article/details/gtanivedgc.html

JS:   await Promise.all(tasks)
来源：http://dali.xylfe.cn/Article/details/gtvogkmkrh.html

TS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gtmfgcxavl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllcncedj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.redwolf501.top/Article/details/gtjxpvqbda.html

Ruby: threads.map(&:join)
来源：http://dali.shuidangran.top/Article/details/gtaztmjqqf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nwbrower.top/Article/details/gtydfgwmdw.html

[O06] 使用进程池
来源：http://dali.dianchejie.cn/Article/details/gtmkfmxisa.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sxryk.cn/Article/details/gtilgyqxyw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwcqmmwid.html

JS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gtvpblwyfz.html

TS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gtrepomrfz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gaohongyu789.top/Article/details/gtcsynfeok.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhongyouzk.top/Article/details/gtikcobuob.html

Ruby: // fork 块
来源：http://dali.svipenyu.cn/Article/details/gtklkzdmcy.html

C#:   Parallel.For
来源：http://dali.zhengqikj.top/Article/details/gtzkysidhk.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gttysvbqvt.html

P. 常用工具函数
来源：http://dali.ppjwa.cn/Article/details/gthooxtaii.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtevhwkopp.html

[P01] 生成 UUID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcrdykkuj.html

Py:   str(uuid.uuid4())
来源：http://dali.cqqwz.cn/Article/details/gtcicsnuup.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jyoumei.cn/Article/details/gtzgdwjlyu.html

JS:   crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gtbfubrtmo.html

TS:   crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gtxacwfzaa.html

Java: UUID.randomUUID().toString()
来源：http://dali.jyoumei.cn/Article/details/gtsalyhngz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.kuanghao11.cn/Article/details/gttlzggwpp.html

Ruby: SecureRandom.uuid
来源：http://dali.nwbrower.top/Article/details/gtnuccprcp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xziqi.cn/Article/details/gtshbzwqhn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.birdmap.top/Article/details/gtkzscinri.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.meibo888.top/Article/details/gtteauuwqo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xuanzx.com/Article/details/gturrwoyyw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cqqwz.cn/Article/details/gtqvdlcudl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hywenlv.cn/Article/details/gtrawueefw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pycfn.com/Article/details/gtbvwlsfev.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenlongwang.top/Article/details/gtlpzvmjhz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.svipenyu.cn/Article/details/gtooscirkc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aizwys.cn/Article/details/gtwsijbxwo.html

[P03] 生成短随机字符串
来源：http://dali.c1oappe.top/Article/details/gttimpewur.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yongpay.top/Article/details/gtgidxxrha.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zycfv.cn/Article/details/gteomcdylv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuanzhike.top/Article/details/gtocybojta.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gtcgqkjcwv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtczztjlkk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nanxuanxn.top/Article/details/gtpmsifpyi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.bjfxy.top/Article/details/gttaiemlms.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhiwuduotai.top/Article/details/gthdwyecyx.html

[P04] 求长度
来源：http://dali.hnqzz.top/Article/details/gtstkpuokg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dianchejie.cn/Article/details/gtptfifoge.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtklarjlvf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gthepstsup.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yvedp.cn/Article/details/gtmdkxbttn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdrvzfbcr.html

Go:   len(arr);  len(m)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedjuhhlh.html

Ruby: x.length;  x.size
来源：http://dali.xuanzx.com/Article/details/gtrfrtgmnd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cucudq.cn/Article/details/gtzlkrkbci.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gotoacloud.top/Article/details/gtlzexvgnf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yanxiufei.cn/Article/details/gtgpkyltfs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.andypj.xyz/Article/details/gtixwuwfhe.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tian-w.cn/Article/details/gthhrkicaf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aibaodan.cn/Article/details/gtlqaiswqs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hfpthk.cn/Article/details/gtstlyfrfl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtyrelhzmr.html

Ruby: a == b
来源：http://dali.quarkkingdee.top/Article/details/gtnqrzfypr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnxiangtu.top/Article/details/gtuoyrbgcm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgfzy.top/Article/details/gtlvedwisv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cashguo.top/Article/details/gtdglsnosx.html

PHP:  if (empty($x)) {}
来源：http://dali.redwolf501.top/Article/details/gtrlaxkton.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hfpthk.cn/Article/details/gtofdrylbj.html

TS:   if (x == null) {}
来源：http://dali.sweek.top/Article/details/gtmxvpbldq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gthuppwuhq.html

Go:   if x == nil {}
来源：http://dali.zycfv.cn/Article/details/gtihnpejyb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nwbrower.top/Article/details/gtksgitlgc.html

C#:   if (x is null) {}
来源：http://dali.yj202588.top/Article/details/gttwctbmfq.html

[P07] 防抖与节流
来源：http://dali.kuanghao11.cn/Article/details/gtodieaauu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.316326.xyz/Article/details/gthziarqgs.html

PHP:  // 手写时间戳比较
来源：http://dali.hfpthk.cn/Article/details/gtppmowixr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gtjokpkoif.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gtzzmnfklm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.redwolf501.top/Article/details/gtkxksofsh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenzaomai.com/Article/details/gtcjabravo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yuxming.cn/Article/details/gtqfvurrlw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gtnmjcktup.html

[P08] 处理浮点精度问题
来源：http://dali.pycfn.com/Article/details/gtucvacrhz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xziqi.cn/Article/details/gtrzluwndo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hysaishi.cn/Article/details/gtqljhyjoo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.guowangkeji.top/Article/details/gtfmtrcega.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hywenlv.cn/Article/details/gtwhnumjme.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ppjwa.cn/Article/details/gtnbfatusz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.pengpengdd.cyou/Article/details/gtvrdxjaer.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dashuyun.cn/Article/details/gtkzkpqmob.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.redwolf501.top/Article/details/gttflewlwo.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtjhhgbklr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guannengcc.top/Article/details/gtqdjxzkmy.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtvnknvpbj.html

[Q01] 创建表
来源：http://dali.tian-w.cn/Article/details/gtnnpkowrr.html

CREATE TABLE users (
来源：http://dali.sxryk.cn/Article/details/gtzrptoihi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gtbjyhvbqh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gtrwtwiuki.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shuidangran.top/Article/details/gtelvwlpnk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenzaomai.com/Article/details/gtwglxslfi.html

);
来源：http://dali.gotoacloud.top/Article/details/gtcyurpzby.html

[Q02] 创建带外键的表
来源：http://dali.cdnleiting.top/Article/details/gtrbwhlzlg.html

CREATE TABLE orders (
来源：http://dali.cucudq.cn/Article/details/gtcffwakyu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gtvntnvlfl.html

user_id INT NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gtpksijjbv.html

amount DECIMAL(10, 2),
来源：http://dali.nanxinkj.top/Article/details/gtfgrhqflk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangdashe.top/Article/details/gtnqvmehhv.html

);
来源：http://dali.andypj.xyz/Article/details/gtxuqncvow.html

[Q03] 增加列
来源：http://dali.cashguo.top/Article/details/gtbhyssrso.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yonumen.top/Article/details/gtjuzezjyd.html

[Q04] 修改列类型
来源：http://dali.gzhubu.top/Article/details/gttgctsxlt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hfpthk.cn/Article/details/gthdszcnrk.html

[Q05] 重命名列
来源：http://dali.zycfv.cn/Article/details/gtvniqnfyf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dianchejie.cn/Article/details/gtezmkezzu.html

[Q06] 删除列
来源：http://dali.haohaochexian.top/Article/details/gtfbhikhpb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nanxuanxn.top/Article/details/gtdtkjbobw.html

[Q07] 删除表
来源：http://dali.fzhhl.top/Article/details/gtfrgsuzgq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yangfankeji.com/Article/details/gtrvbdhkge.html

[Q08] 创建普通索引
来源：http://dali.nwbrower.top/Article/details/gtefpxqyht.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj20258.top/Article/details/gtvbchueci.html

[Q09] 创建唯一索引
来源：http://dali.nanxinkj.top/Article/details/gtpvnagvoc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gtgxmnhxfq.html

[Q10] 插入单行
来源：http://dali.guannengcc.top/Article/details/gtvhonjtky.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.birdmap.top/Article/details/gtfguvonus.html

[Q11] 一次插入多行
来源：http://dali.vqdsnc.cn/Article/details/gtgyijerwz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sysykeji.top/Article/details/gtqszuwtsg.html

[Q12] 插入后取自增 ID
来源：http://dali.zhongyouzk.top/Article/details/gtfunohylr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhoulong.xyz/Article/details/gtqseerkoe.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yanxiufei.cn/Article/details/gtegyoihhb.html

[Q13] 忽略重复插入
来源：http://dali.yj202588.top/Article/details/gtprxswohz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtsrcbbinh.html

[Q14] 存在则更新（upsert）
来源：http://dali.iojbl.cn/Article/details/gtqhkdrjiv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.snrcjt.cn/Article/details/gtosrpfaqu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sysykeji.top/Article/details/gtvizjmtcn.html

[Q15] 查询全部
来源：http://dali.hnxiangtu.top/Article/details/gtvwzmxbra.html

SELECT * FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gthdevzwue.html

[Q16] 查询指定列
来源：http://dali.ppjwa.cn/Article/details/gtspjxrrmd.html

SELECT id, name FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtwxyuczhl.html

[Q17] 条件查询
来源：http://dali.sweek.top/Article/details/gthyitrqqk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.svipenyu.cn/Article/details/gtskfdzouk.html

[Q18] 模糊匹配
来源：http://dali.jqgufenzy.top/Article/details/gtdzdehzcj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shanyushiyangtech.top/Article/details/gtgroijavk.html

[Q19] 范围查询
来源：http://dali.316326.xyz/Article/details/gtepsyzwxn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shuidangran.top/Article/details/gtdzcjkwdj.html

[Q20] IN 列表
来源：http://dali.dianchejie.cn/Article/details/gteylytzqe.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ybcxt.top/Article/details/gtctgufbxj.html

[Q21] 空值判断
来源：http://dali.pycfn.com/Article/details/gtfvfajjmi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.aizwys.cn/Article/details/gtnoujwrxk.html

[Q22] 排序
来源：http://dali.iojbl.cn/Article/details/gthxfxbafu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nanxinkj.top/Article/details/gtbkupwbvc.html

[Q23] 分页
来源：http://dali.yanxiufei.cn/Article/details/gtwxlqoehw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yvedp.cn/Article/details/gtlysslnnz.html

[Q24] 去重
来源：http://dali.sxryk.cn/Article/details/gtazsqfnya.html

SELECT DISTINCT city FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtimvmijbr.html

[Q25] 只取前 N 条
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgfeioty.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yangfankeji.com/Article/details/gtvnbplicg.html

[Q26] 计数
来源：http://dali.guannengcc.top/Article/details/gtygluolze.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj202588.top/Article/details/gtgpapzmiz.html

[Q27] 条件计数
来源：http://dali.cdnleiting.top/Article/details/gtadzfbmyv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yongpay.top/Article/details/gtikqdlbke.html

[Q28] 求和与平均
来源：http://dali.yj20258.top/Article/details/gtpnzyghrn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtuihwjvvj.html

[Q29] 最大最小值
来源：http://dali.xuanzx.com/Article/details/gtqtqlkviq.html


<!-- 参考信息 -->