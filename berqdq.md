代发 wailian999

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtzdnyjwwd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sweek.top/Article/details/gtkniueukl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gtczncqgeq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtsqokkdtn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gtsqnwoaew.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gtjvjulbta.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtseztcqdb.html

Go:   slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gtvagujzwe.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gtrpgxurji.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.iojbl.cn/Article/details/gtmfjfjtyu.html

[N03] 快速排序（分治示例）
来源：http://dali.dianchejie.cn/Article/details/gtyqwfobun.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.havefunace.top/Article/details/gtvgvnbptz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cashguo.top/Article/details/gtgofidowe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.redwolf501.top/Article/details/gteiciuxfh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gtdfhmdqps.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhengqikj.top/Article/details/gtulmjwmlj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgfzy.top/Article/details/gtnojeqboa.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dashuyun.cn/Article/details/gtmfbtxkbb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgfzy.top/Article/details/gtnzapwswu.html

[N04] 斐波那契数列
来源：http://dali.tian-w.cn/Article/details/gtoczgoueh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtzdflopag.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.wangdashe.top/Article/details/gtproxrmjk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtskaafukj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtxflbymxg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tanke756.top/Article/details/gtyzzaasdn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ppjwa.cn/Article/details/gtlujxgsnr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gtkjyamfvh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gtwsamzvws.html

[N05] 最大公约数
来源：http://dali.c1oappe.top/Article/details/gthfrtlfiz.html

Py:   math.gcd(a, b)
来源：http://dali.yueranfly.top/Article/details/gtrsyjaywu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xinyue.icu/Article/details/gtduhipvdf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxinkj.top/Article/details/gtxpmygmjw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgufenzy.top/Article/details/gtgxgswufp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jqgfzy.top/Article/details/gttelgxqxh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cucudq.cn/Article/details/gtghydmsym.html

Ruby: a.gcd(b)
来源：http://dali.fzhhl.top/Article/details/gtpcioankx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jlsjyb.cn/Article/details/gthwmqgram.html

[N06] 判断回文字符串
来源：http://dali.smart0.xyz/Article/details/gtepvpdttr.html

Py:   s == s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiyhkkqzg.html

PHP:  $s === strrev($s);
来源：http://dali.cheryme.top/Article/details/gtnhlvftsu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtslgcvjld.html

TS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtyzsnkkrz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.kuanghao11.cn/Article/details/gtklpujbag.html

Go:   // 双指针从两端比较
来源：http://dali.yj20258888.top/Article/details/gtbdhwyqcf.html

Ruby: s == s.reverse
来源：http://dali.wangdashe.top/Article/details/gtqwxtrrix.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gzhubu.top/Article/details/gtahgexogw.html

[N07] 两数之和（返回下标）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzkkcjoxf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhoulong.xyz/Article/details/gtbldjpcaw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhixingplan.top/Article/details/gtobryzzxb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenzaomai.com/Article/details/gtksjquxiw.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenjidiqi.icu/Article/details/gtdtagounx.html

Java: // 手写 HashMap
来源：http://dali.xuanzx.com/Article/details/gtkfqmmkqx.html

Go:   // 手写 map[int]int
来源：http://dali.nanxinkj.top/Article/details/gtxrqpshys.html

Ruby: // 手写 Hash
来源：http://dali.xinyue.icu/Article/details/gtimbvxkvv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nanxuanxn.top/Article/details/gtzucqaquk.html

[N08] 生成全排列
来源：http://dali.yongpay.top/Article/details/gtbiivbcjk.html

Py:   itertools.permutations(arr)
来源：http://dali.sweek.top/Article/details/gtfjpvuneb.html

PHP:  // 手写递归交换
来源：http://dali.bjfxy.top/Article/details/gtrtyuvnin.html

JS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtrrkytuhy.html

TS:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtnkdwehyn.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtbzqbplwu.html

Go:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtjpmrdwgl.html

Ruby: arr.permutation.to_a
来源：http://dali.nwbrower.top/Article/details/gtjajgrrxx.html

C#:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gthzfamgby.html

[N09] 栈与队列
来源：http://dali.haohaochexian.top/Article/details/gtmzpwrvus.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtlmmvluot.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtfevdbneu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.aizwys.cn/Article/details/gtfvcitjbi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ivvv.top/Article/details/gtnwfpngsi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.mhx1999.top/Article/details/gthxisnzdc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangdashe.top/Article/details/gtkrgrdqit.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtoiwlouop.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxuanxn.top/Article/details/gtenoliivi.html

[N10] 链表节点定义
来源：http://dali.yuanzhike.top/Article/details/gtunupwcnv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.svipenyu.cn/Article/details/gtvcjmoidn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yanxiufei.cn/Article/details/gttfrdvdpr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangdashe.top/Article/details/gttxnxhpjh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.kuanghao11.cn/Article/details/gtzwouvtgp.html

Java: class Node { int v; Node next; }
来源：http://dali.zhongyouzk.top/Article/details/gtpawjzicm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenlongwang.top/Article/details/gtiflyvniv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.haohaochexian.top/Article/details/gtxrettobo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.vqdsnc.cn/Article/details/gtupbbjzur.html

[N11] 二叉树中序遍历
来源：http://dali.mhx1999.top/Article/details/gtofxniavi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhiwuduotai.top/Article/details/gtexvtzupv.html

PHP:  // 手写递归函数
来源：http://dali.nanxuanxn.top/Article/details/gtttgivcaa.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gteytgawjn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gtujhkdxlc.html

Java: // 手写递归
来源：http://dali.xylfe.cn/Article/details/gtaeymwtih.html

Go:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtixbiqhjh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhoulong.xyz/Article/details/gtdoweqwcf.html

C#:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtxpxmellk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zycfv.cn/Article/details/gtasxgocno.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.316326.xyz/Article/details/gtfvkissmt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sweek.top/Article/details/gtbzjcuzqu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhengqikj.top/Article/details/gtsjaschbo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gtroaaxtru.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gtdaajspmu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.haohaochexian.top/Article/details/gttozdjowe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gtabsjjqyj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gtlgkvudpr.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtylbgeiyg.html

O. 并发与异步
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqdeqpdy.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtqwhhvatq.html

[O01] 启动一个线程
来源：http://dali.nanxinkj.top/Article/details/gtgmehnnay.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.andypj.xyz/Article/details/gtsazovsqe.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xinyue.icu/Article/details/gtrsrtdimz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sufxvd.cn/Article/details/gtjigqqjuw.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gtxddpliaf.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigfzy.top/Article/details/gttaszzmoa.html

Go:   go f()
来源：http://dali.nanxinkj.top/Article/details/gtwjyjmcut.html

Ruby: Thread.new { f }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkscjxsm.html

C#:   Task.Run(() => F());
来源：http://dali.pycfn.com/Article/details/gtwcffivth.html

[O02] 使用线程池
来源：http://dali.jinqigfzy.top/Article/details/gtjflwqese.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhongyouzk.top/Article/details/gtwozgpaih.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhongyouzk.top/Article/details/gtvaghezyh.html

JS:   // worker_threads 线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonqlsjgf.html

TS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gtwgxerqev.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258.top/Article/details/gthfpvxexl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258.top/Article/details/gtwewhakcl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yanxiufei.cn/Article/details/gtoqsfuqbg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.svipenyu.cn/Article/details/gtzpcwhhut.html

[O03] 加锁保护共享数据
来源：http://dali.zhoulong.xyz/Article/details/gtylgrfpel.html

Py:   with lock: shared += 1
来源：http://dali.shzxlz.cn/Article/details/gtcnyrutfu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjutktxwf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenjidiqi.icu/Article/details/gtzyosfghl.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gtpazmmuqx.html

Java: synchronized (this) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gtfoggnpfm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangshuangyany.cn/Article/details/gtptzjsmfb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jiagoushi.top/Article/details/gtegpblily.html

C#:   lock (gate) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gtppytuuqv.html

[O04] 定义异步函数并等待
来源：http://dali.mhx1999.top/Article/details/gtqukwjjdl.html

Py:   async def f():⏎    await g()
来源：http://dali.yuanzhike.top/Article/details/gttturndrd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hysaishi.cn/Article/details/gtzpnhoaio.html

JS:   async function f() { await g(); }
来源：http://dali.bjfxy.top/Article/details/gtvlckxwyv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gtmguzsskc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258.top/Article/details/gtpplmyjbc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258.top/Article/details/gtveuvxaqu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xziqi.cn/Article/details/gtuixztmjx.html

C#:   async Task F() { await G(); }
来源：http://dali.smart0.xyz/Article/details/gtawuqsczt.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuetiantiany.cn/Article/details/gtatqmkhbv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.aibaodan.cn/Article/details/gtoerxpbex.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ybcxt.top/Article/details/gtewpeosiz.html

JS:   await Promise.all(tasks)
来源：http://dali.xinyue.icu/Article/details/gtlyudrtzt.html

TS:   await Promise.all(tasks)
来源：http://dali.zhixingplan.top/Article/details/gtzkpidgsf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.kuanghao11.cn/Article/details/gthkguydpj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhengqikj.top/Article/details/gtvmvrpujt.html

Ruby: threads.map(&:join)
来源：http://dali.dashuyun.cn/Article/details/gtcyoxthdf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzjweflq.html

[O06] 使用进程池
来源：http://dali.hywenlv.cn/Article/details/gtvightstu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenlongwang.top/Article/details/gtscuifaan.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cdnleiting.top/Article/details/gtobtbavyd.html

JS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gtjppqtwpm.html

TS:   // child_process / cluster 模块
来源：http://dali.fzhhl.top/Article/details/gtlpcbqytz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aizwys.cn/Article/details/gtvnhbsvfw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yonumen.top/Article/details/gtjnvapkiu.html

Ruby: // fork 块
来源：http://dali.hnqzz.top/Article/details/gtmbcuyejp.html

C#:   Parallel.For
来源：http://dali.yuxming.cn/Article/details/gtaihsauln.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtoxtgrlgu.html

P. 常用工具函数
来源：http://dali.pycfn.com/Article/details/gtccdgclhb.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtdyxzjgid.html

[P01] 生成 UUID
来源：http://dali.yangfankeji.com/Article/details/gtihsjnuqb.html

Py:   str(uuid.uuid4())
来源：http://dali.ppjwa.cn/Article/details/gtcevpixdu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gtafzyrnuc.html

JS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gtbyocbsvc.html

TS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gthfpwcdio.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhengqikj.top/Article/details/gthmyeryte.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fzhhl.top/Article/details/gtkrjjewug.html

Ruby: SecureRandom.uuid
来源：http://dali.hywenlv.cn/Article/details/gtpbmaneiv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhongyouzk.top/Article/details/gtqfxlsidk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.quarkkingdee.top/Article/details/gtyhmikwua.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.mhx1999.top/Article/details/gtqesodheo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258.top/Article/details/gtyrjplrvl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cashguo.top/Article/details/gtonqohijo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aizwys.cn/Article/details/gtuynbonoq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.bjfxy.top/Article/details/gtzrgekhrv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shzxlz.cn/Article/details/gtcomgumae.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yangfankeji.com/Article/details/gtuqzbpuay.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ehwqpu.com/Article/details/gttkituysp.html

[P03] 生成短随机字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtogpyoffq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guowangkeji.top/Article/details/gtgqfagdic.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sxryk.cn/Article/details/gtytsleupz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gtcpfhidef.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gtqypelomr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtricwyapn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgizmvlfu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ybcxt.top/Article/details/gtxlxqudai.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hongshengwenyu.top/Article/details/gtjbfnpeha.html

[P04] 求长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtexilbpgq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.birdmap.top/Article/details/gtqkduqqpa.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtkhempbqt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gttwwqramr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sxryk.cn/Article/details/gtdmpwlome.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuxming.cn/Article/details/gtpspnfgca.html

Go:   len(arr);  len(m)
来源：http://dali.bjfxy.top/Article/details/gtuamkmzaf.html

Ruby: x.length;  x.size
来源：http://dali.sysykeji.top/Article/details/gtcaqvtjbl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtvssqar.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guowangkeji.top/Article/details/gtnjndwdif.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.iojbl.cn/Article/details/gtejgkxwte.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinqigfzy.top/Article/details/gtzjgziiku.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daxiang520.top/Article/details/gtvwkxsbwd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtuccqxfjk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shuidangran.top/Article/details/gttcninxwe.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tanke756.top/Article/details/gtbfebdvpb.html

Ruby: a == b
来源：http://dali.daxiang520.top/Article/details/gtbagahbbh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.dianchejie.cn/Article/details/gtnjycvioh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cucudq.cn/Article/details/gtpadcsdod.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zdqjudy.top/Article/details/gtferaoucp.html

PHP:  if (empty($x)) {}
来源：http://dali.mhx1999.top/Article/details/gtklecoexi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.wangshuangyany.cn/Article/details/gtndlhdtxo.html

TS:   if (x == null) {}
来源：http://dali.hnqzz.top/Article/details/gtebqgsvys.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtrinnmryh.html

Go:   if x == nil {}
来源：http://dali.cucudq.cn/Article/details/gtnldwszay.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.fengsongda.top/Article/details/gtftxgihxe.html

C#:   if (x is null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gteehrkytv.html

[P07] 防抖与节流
来源：http://dali.jianghu66.top/Article/details/gthwntceip.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cdnleiting.top/Article/details/gtufkgjhkk.html

PHP:  // 手写时间戳比较
来源：http://dali.hywenlv.cn/Article/details/gtjragewiy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gteuewbouq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zycfv.cn/Article/details/gtuvwjokrn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtyzignjlx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sxryk.cn/Article/details/gtgprqwwcj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yuanzhike.top/Article/details/gtdaqdnpyb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj202588.top/Article/details/gtvepgrefi.html

[P08] 处理浮点精度问题
来源：http://dali.gzhubu.top/Article/details/gttuinzikm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zycfv.cn/Article/details/gtaxijobuv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenlongwang.top/Article/details/gtcvuritcn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.guowangkeji.top/Article/details/gtbyjhwjir.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.pycfn.com/Article/details/gtvboygzgr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.smart0.xyz/Article/details/gttcphihbh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.snrcjt.cn/Article/details/gtfobxrzub.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhixingplan.top/Article/details/gtzblrbdbm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daxiang520.top/Article/details/gtisevszym.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtdgfrczit.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258.top/Article/details/gtwpmeubqp.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtxomdtcgg.html

[Q01] 创建表
来源：http://dali.9152youxi.cn/Article/details/gtrislcbqz.html

CREATE TABLE users (
来源：http://dali.daxiang520.top/Article/details/gtnvujanzt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jlsjyb.cn/Article/details/gtfyiqhjhv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gtpfjkftue.html

email VARCHAR(100) UNIQUE,
来源：http://dali.birdmap.top/Article/details/gtwgxdnqew.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shzxlz.cn/Article/details/gtlzkzlxnw.html

);
来源：http://dali.snrcjt.cn/Article/details/gtsogftjsp.html

[Q02] 创建带外键的表
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfqgrbgb.html

CREATE TABLE orders (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpaewvjlw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gtfifwsuzs.html

user_id INT NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gtlvktcqjx.html

amount DECIMAL(10, 2),
来源：http://dali.yangfankeji.com/Article/details/gtquizohli.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yangfankeji.com/Article/details/gtxohdedwk.html

);
来源：http://dali.vqdsnc.cn/Article/details/gtnleakajd.html

[Q03] 增加列
来源：http://dali.zycfv.cn/Article/details/gtherxponj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jiagoushi.top/Article/details/gtqfgstbyt.html

[Q04] 修改列类型
来源：http://dali.yuxming.cn/Article/details/gtpspneuju.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gzhubu.top/Article/details/gtbulrmzxy.html

[Q05] 重命名列
来源：http://dali.feifeiyinyue.top/Article/details/gtypcnhama.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.havefunace.top/Article/details/gttzmovvdj.html

[Q06] 删除列
来源：http://dali.gotoacloud.top/Article/details/gtczxdiizx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hnqzz.top/Article/details/gtczaqfvue.html

[Q07] 删除表
来源：http://dali.daxiang520.top/Article/details/gtjcsszffu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jlsjyb.cn/Article/details/gtyoudjbmn.html

[Q08] 创建普通索引
来源：http://dali.vqdsnc.cn/Article/details/gtaasnixcd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.svipenyu.cn/Article/details/gtyzmrxrnd.html

[Q09] 创建唯一索引
来源：http://dali.hysaishi.cn/Article/details/gtnzczhcht.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrweacrku.html

[Q10] 插入单行
来源：http://dali.chenlongwang.top/Article/details/gtbxtchjhj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xziqi.cn/Article/details/gtenrymgls.html

[Q11] 一次插入多行
来源：http://dali.shzxlz.cn/Article/details/gtprbrcley.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenlongwang.top/Article/details/gthhcwepqy.html

[Q12] 插入后取自增 ID
来源：http://dali.gotoacloud.top/Article/details/gtbdqmdeld.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikueisih.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zdqjudy.top/Article/details/gttxyjgrut.html

[Q13] 忽略重复插入
来源：http://dali.zycfv.cn/Article/details/gtmzcxqkjl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gtyncxqxqo.html

[Q14] 存在则更新（upsert）
来源：http://dali.aibaodan.cn/Article/details/gtubjkexer.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aibaodan.cn/Article/details/gtdxqzjdqv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinqigfzy.top/Article/details/gtokbqyeqv.html

[Q15] 查询全部
来源：http://dali.sufxvd.cn/Article/details/gtqlsxtxqr.html

SELECT * FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtjabkzkgx.html

[Q16] 查询指定列
来源：http://dali.shuidangran.top/Article/details/gtwiruxrhq.html

SELECT id, name FROM users;
来源：http://dali.hnqzz.top/Article/details/gtmwmmyjur.html

[Q17] 条件查询
来源：http://dali.yuanzhike.top/Article/details/gtlfdlplgh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtatogpkba.html

[Q18] 模糊匹配
来源：http://dali.meibo888.top/Article/details/gtyyiomdah.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.bjfxy.top/Article/details/gtsamhbdgl.html

[Q19] 范围查询
来源：http://dali.ybcxt.top/Article/details/gttvsztblv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.wangdashe.top/Article/details/gthorbvbyo.html

[Q20] IN 列表
来源：http://dali.nanxuanxn.top/Article/details/gtrcqahndl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tianlin.xyz/Article/details/gtyjqsionb.html

[Q21] 空值判断
来源：http://dali.gaohongyu789.top/Article/details/gtnopedzgt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sxryk.cn/Article/details/gtwrrumzyz.html

[Q22] 排序
来源：http://dali.zhongyouzk.top/Article/details/gtfqgxqmpf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ppjwa.cn/Article/details/gtvlgyneuj.html

[Q23] 分页
来源：http://dali.hongshengwenyu.top/Article/details/gtjzzkvrhi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hongshengwenyu.top/Article/details/gtfhprmpyt.html

[Q24] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefznaovr.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtpnzsvqki.html

[Q25] 只取前 N 条
来源：http://dali.yonumen.top/Article/details/gtqmonsoon.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinghuilouyu.cn/Article/details/gtxekjtfuk.html

[Q26] 计数
来源：http://dali.ehwqpu.com/Article/details/gtylkcsbpj.html

SELECT COUNT(*) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtezpveovi.html

[Q27] 条件计数
来源：http://dali.ydzc1.top/Article/details/gtycqfisxp.html


<!-- 参考信息 -->