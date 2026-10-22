代发 wailian999

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtltqudkim.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gttwszkufv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ydzc1.top/Article/details/gtakxlodsg.html

Go:   slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxzldnki.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gttsfykate.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtliiscaof.html

[N03] 快速排序（分治示例）
来源：http://dali.daria6918.cn/Article/details/gtddonoxkp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.316326.xyz/Article/details/gtgdspvtrm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nwbrower.top/Article/details/gtghsljlwc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gtxuifkyea.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gttgsbmxlp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yangfankeji.com/Article/details/gtvwduevpx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ybcxt.top/Article/details/gttddolhnf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jiagoushi.top/Article/details/gtfzijscpo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xuanzx.com/Article/details/gtkvqvdpui.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxtobqiq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gtttpgymgq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gtzuevoele.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtasmxrbpk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtuyopagwg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sweek.top/Article/details/gtsjdjgdgh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuetiantiany.cn/Article/details/gttnwmsqxf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gtugoofwtk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtfwgnowvb.html

[N05] 最大公约数
来源：http://dali.yongpay.top/Article/details/gtyoinkzkh.html

Py:   math.gcd(a, b)
来源：http://dali.yueranfly.top/Article/details/gtsschadcy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gttuulsaxa.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gtcxbpvrwr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.redwolf501.top/Article/details/gthaimalzx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pengpengdd.cyou/Article/details/gtdztzskxm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.pengpengdd.cyou/Article/details/gtkwazjygo.html

Ruby: a.gcd(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtsmtnlrrq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.mhx1999.top/Article/details/gtfvtpkpas.html

[N06] 判断回文字符串
来源：http://dali.jyoumei.cn/Article/details/gttwmyzklu.html

Py:   s == s[::-1]
来源：http://dali.xinyue.icu/Article/details/gtzahbaqqg.html

PHP:  $s === strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtmytixqql.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtengplazt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtuzqylbdy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ydzc1.top/Article/details/gtkeklwsgf.html

Go:   // 双指针从两端比较
来源：http://dali.guowangkeji.top/Article/details/gtazvgmpyo.html

Ruby: s == s.reverse
来源：http://dali.aizwys.cn/Article/details/gtodzqbogl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gtjsdyjsaz.html

[N07] 两数之和（返回下标）
来源：http://dali.guannengcc.top/Article/details/gtyapaaywy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guannengcc.top/Article/details/gtuzrxejlv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xinyue.icu/Article/details/gtynioctbv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jianghu66.top/Article/details/gtyznfnbht.html

TS:   // 手写 Map<string, number>
来源：http://dali.hnqzz.top/Article/details/gtmafaixok.html

Java: // 手写 HashMap
来源：http://dali.chenjidiqi.icu/Article/details/gtjjxndnbx.html

Go:   // 手写 map[int]int
来源：http://dali.zhongyouzk.top/Article/details/gtinklkniq.html

Ruby: // 手写 Hash
来源：http://dali.hysaishi.cn/Article/details/gtrbgdyzzi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xinyue.icu/Article/details/gtfbgsffzt.html

[N08] 生成全排列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoyfufsqw.html

Py:   itertools.permutations(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtofpyxgiv.html

PHP:  // 手写递归交换
来源：http://dali.hywenlv.cn/Article/details/gtbarocvca.html

JS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtjtjyuurw.html

TS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtzxsgyvls.html

Java: // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtkmpakzxu.html

Go:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtsozugxjl.html

Ruby: arr.permutation.to_a
来源：http://dali.yvedp.cn/Article/details/gthcfwtbgi.html

C#:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtkypoujif.html

[N09] 栈与队列
来源：http://dali.jqgfzy.top/Article/details/gtctutiazd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtyycepqrv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gzhubu.top/Article/details/gteembthls.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gtqnrwozdy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.vqdsnc.cn/Article/details/gtrrmcynin.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gtslkojrmb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xziqi.cn/Article/details/gtucsgknyg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtgpyfjqjk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ydzc1.top/Article/details/gtltbdehft.html

[N10] 链表节点定义
来源：http://dali.jqgfzy.top/Article/details/gtygrbmhhw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.wangshuangyany.cn/Article/details/gtgzivfucv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrbwygonc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zdqjudy.top/Article/details/gtvuhcfkkb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.fengsongda.top/Article/details/gtqxjngqfx.html

Java: class Node { int v; Node next; }
来源：http://dali.jlsjyb.cn/Article/details/gtbbuuwwwd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yueranfly.top/Article/details/gtwdfkqubq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnqzz.top/Article/details/gtpnirrudi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fengsongda.top/Article/details/gtivsxmvkk.html

[N11] 二叉树中序遍历
来源：http://dali.cdnleiting.top/Article/details/gtzorqrbzf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.c1oappe.top/Article/details/gtpljxjnar.html

PHP:  // 手写递归函数
来源：http://dali.jiagoushi.top/Article/details/gthnkbbvej.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnqzz.top/Article/details/gtuptksmgj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gtushxzecw.html

Java: // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gtdkisrhdt.html

Go:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gtkhblynfw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.bjfxy.top/Article/details/gtgkuqlxdx.html

C#:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtnwbgligg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yuanzhike.top/Article/details/gtwseyogzy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.svipenyu.cn/Article/details/gteacskanx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aibaodan.cn/Article/details/gtitfyeqok.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gtevqmaklb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gtflechnbz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gtvhcprbpx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.kuanghao11.cn/Article/details/gtfnjgofiv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxinkj.top/Article/details/gtyjbelwle.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gtnmoracaf.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtnzjoefue.html

O. 并发与异步
来源：http://dali.dashuyun.cn/Article/details/gtxqngpvdz.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtaxtmpkmf.html

[O01] 启动一个线程
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsqwmtec.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.kuanghao11.cn/Article/details/gtfpxvtkzo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenjidiqi.icu/Article/details/gtjcofnzre.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.pengpengdd.cyou/Article/details/gtvanuywkx.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gtgjjprcci.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptdhspxv.html

Go:   go f()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzjkaucd.html

Ruby: Thread.new { f }
来源：http://dali.zhoulong.xyz/Article/details/gteqnnuscc.html

C#:   Task.Run(() => F());
来源：http://dali.yanxiufei.cn/Article/details/gtvqwbkupj.html

[O02] 使用线程池
来源：http://dali.gogol.net.cn/Article/details/gtnamlxzyy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.snrcjt.cn/Article/details/gtkikctiom.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cqqwz.cn/Article/details/gtxjrxvpcd.html

JS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gtgaizoshx.html

TS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gtgsbmhdxy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258.top/Article/details/gtxocdubip.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangshuangyany.cn/Article/details/gtyogvcbfo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.snrcjt.cn/Article/details/gtpwqdrevv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sxryk.cn/Article/details/gtcgsbludm.html

[O03] 加锁保护共享数据
来源：http://dali.quarkkingdee.top/Article/details/gtcnbndmzo.html

Py:   with lock: shared += 1
来源：http://dali.zhoulong.xyz/Article/details/gtyxayfurf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.iojbl.cn/Article/details/gtuwchsdht.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cdnleiting.top/Article/details/gtzwbkkxoz.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gtkhrydixt.html

Java: synchronized (this) { shared++; }
来源：http://dali.mhx1999.top/Article/details/gtuotiskrc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cqqwz.cn/Article/details/gtncptmxou.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangdashe.top/Article/details/gtjysjmstb.html

C#:   lock (gate) { shared++; }
来源：http://dali.316326.xyz/Article/details/gtqbfmxufn.html

[O04] 定义异步函数并等待
来源：http://dali.redwolf501.top/Article/details/gthimddtve.html

Py:   async def f():⏎    await g()
来源：http://dali.sweek.top/Article/details/gtrwajyfgj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinghuilouyu.cn/Article/details/gtlicsqlzh.html

JS:   async function f() { await g(); }
来源：http://dali.meibo888.top/Article/details/gtfruevvmu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.guowangkeji.top/Article/details/gtfinvlbjr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocowvnpx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cdnleiting.top/Article/details/gtynoxugyq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenlongwang.top/Article/details/gtcxjkvfbi.html

C#:   async Task F() { await G(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtuopqvpxf.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhixingplan.top/Article/details/gtbwhhjeru.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dianchejie.cn/Article/details/gtaggfryrv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cdnleiting.top/Article/details/gtopdgnxpr.html

JS:   await Promise.all(tasks)
来源：http://dali.vqdsnc.cn/Article/details/gtewooqjty.html

TS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gttxazsfvi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shanyushiyangtech.top/Article/details/gtffqmeqzg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.iojbl.cn/Article/details/gthbinhskk.html

Ruby: threads.map(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gtejgrexkt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yuxming.cn/Article/details/gtkqmadajf.html

[O06] 使用进程池
来源：http://dali.nwbrower.top/Article/details/gtxhlfxxpj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shangyingyoupin.top/Article/details/gtdnghpujs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yueranfly.top/Article/details/gthifhkuoz.html

JS:   // child_process / cluster 模块
来源：http://dali.pengpengdd.cyou/Article/details/gtzzzgvliz.html

TS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gtvipkhdcw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.birdmap.top/Article/details/gtsfwqpsge.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjsacqku.html

Ruby: // fork 块
来源：http://dali.jinqigufen.top/Article/details/gtqbhzddti.html

C#:   Parallel.For
来源：http://dali.hfpthk.cn/Article/details/gtjojyaogj.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtgtyxfbvm.html

P. 常用工具函数
来源：http://dali.mhx1999.top/Article/details/gtchrpbxjp.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtvcffnkrr.html

[P01] 生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gtktpwfwdv.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258888.top/Article/details/gtlfmlluux.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.vqdsnc.cn/Article/details/gthgroqqob.html

JS:   crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gtcoxsxlep.html

TS:   crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gtgbhkafkj.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigfzy.top/Article/details/gtppvwtvst.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hnxiangtu.top/Article/details/gtsjuzkwqe.html

Ruby: SecureRandom.uuid
来源：http://dali.sxryk.cn/Article/details/gtwemnuhle.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnxiangtu.top/Article/details/gtipuffivp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nwbrower.top/Article/details/gtyiilpncd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jianghu66.top/Article/details/gtriwypsqz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.guannengcc.top/Article/details/gtkjcnvzni.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jqgfzy.top/Article/details/gtahgiowak.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.mhx1999.top/Article/details/gtaiccrjwm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xziqi.cn/Article/details/gttgrmfvfi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigufen.top/Article/details/gtnoblvkkd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sufxvd.cn/Article/details/gtrlubnhuq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.meibo888.top/Article/details/gtzxctsslu.html

[P03] 生成短随机字符串
来源：http://dali.gogol.net.cn/Article/details/gtmcsgyobq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ehwqpu.com/Article/details/gtjrckzrfb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenjidiqi.icu/Article/details/gtlglbsgje.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gteytrgdfc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sufxvd.cn/Article/details/gttwytxywi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabnuzdkg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowllfbph.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yangfankeji.com/Article/details/gtrrmbejrb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tian-w.cn/Article/details/gtntcqfunt.html

[P04] 求长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrcagryw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangdashe.top/Article/details/gtyqifeadl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtwxqqdoxz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yanxiufei.cn/Article/details/gtoxosnfjw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gtmqvnpkpl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hywenlv.cn/Article/details/gtuatuefdj.html

Go:   len(arr);  len(m)
来源：http://dali.hywenlv.cn/Article/details/gtluozucvo.html

Ruby: x.length;  x.size
来源：http://dali.c1oappe.top/Article/details/gtykyvejla.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.smart0.xyz/Article/details/gtnarwrtee.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sweek.top/Article/details/gtyvldtmbb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinghuilouyu.cn/Article/details/gtdnznpsed.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aizwys.cn/Article/details/gtbphgvmhl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.redwolf501.top/Article/details/gtbstlyuzm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guowangkeji.top/Article/details/gtabvikpsc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj202588.top/Article/details/gtdnlzmqxj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hysaishi.cn/Article/details/gtcunhzuvt.html

Ruby: a == b
来源：http://dali.quarkkingdee.top/Article/details/gtjzhvzbie.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guannengcc.top/Article/details/gtjpejwaaz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hfpthk.cn/Article/details/gthybzzxjk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ywan-chungtsiang.top/Article/details/gtluuepjqg.html

PHP:  if (empty($x)) {}
来源：http://dali.yanxiufei.cn/Article/details/gtsndgsenr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guowangkeji.top/Article/details/gtvpikmngm.html

TS:   if (x == null) {}
来源：http://dali.jinqigufen.top/Article/details/gtvfeqhnyi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtetermpir.html

Go:   if x == nil {}
来源：http://dali.yanxiufei.cn/Article/details/gtzgfrpbwp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.kuanghao11.cn/Article/details/gthgsdlmcf.html

C#:   if (x is null) {}
来源：http://dali.jinqigfzy.top/Article/details/gtkqueicwz.html

[P07] 防抖与节流
来源：http://dali.wangdashe.top/Article/details/gtbmaeekzl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cashguo.top/Article/details/gtqejlolwo.html

PHP:  // 手写时间戳比较
来源：http://dali.cucudq.cn/Article/details/gtkwxrikzt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gtihbsllvi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttygusyy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hnxiangtu.top/Article/details/gtgyhanygd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jqgufenzy.top/Article/details/gtrxheitfq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gaohongyu789.top/Article/details/gtedvoswwa.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yangfankeji.com/Article/details/gtaalaqqvs.html

[P08] 处理浮点精度问题
来源：http://dali.hnxiangtu.top/Article/details/gtmeynbbmi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xuanzx.com/Article/details/gtmaygpcyv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xylfe.cn/Article/details/gtqdmjiqtx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dashuyun.cn/Article/details/gtczprtltt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.meibo888.top/Article/details/gtuomkjxpt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sxryk.cn/Article/details/gtpfzkixvk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sxryk.cn/Article/details/gtumxdmgcj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shuidangran.top/Article/details/gtipufwdbk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.fzhhl.top/Article/details/gtebcogovj.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtayufdmbc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ivvv.top/Article/details/gtajqgosos.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtfhlywhfj.html

[Q01] 创建表
来源：http://dali.bjfxy.top/Article/details/gthdmaygqb.html

CREATE TABLE users (
来源：http://dali.yueranfly.top/Article/details/gtkeswhsun.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gttrxhvjpy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gtcegvcxht.html

email VARCHAR(100) UNIQUE,
来源：http://dali.wangshuangyany.cn/Article/details/gtxsxikftd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nanxinkj.top/Article/details/gtkyisfapg.html

);
来源：http://dali.haohaochexian.top/Article/details/gtckdwlpxe.html

[Q02] 创建带外键的表
来源：http://dali.dianchejie.cn/Article/details/gtarbttigd.html

CREATE TABLE orders (
来源：http://dali.jianghu66.top/Article/details/gtoruavdoj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jianghu66.top/Article/details/gtsfapahcl.html

user_id INT NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gtyoymshds.html

amount DECIMAL(10, 2),
来源：http://dali.sxryk.cn/Article/details/gtuvgijyoj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenjidiqi.icu/Article/details/gtdvjejadh.html

);
来源：http://dali.chenlongwang.top/Article/details/gtdorqwtrw.html

[Q03] 增加列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqszzjpx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ybcxt.top/Article/details/gtqwlxckmj.html

[Q04] 修改列类型
来源：http://dali.feifeiyinyue.top/Article/details/gtszfpevcd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.bjfxy.top/Article/details/gtelwnqotu.html

[Q05] 重命名列
来源：http://dali.cucudq.cn/Article/details/gthostipbb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigfzy.top/Article/details/gtuvhgmlfk.html

[Q06] 删除列
来源：http://dali.jinqigfzy.top/Article/details/gtwstjihem.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cqqwz.cn/Article/details/gtotmbshrp.html

[Q07] 删除表
来源：http://dali.xziqi.cn/Article/details/gtmmbwfpax.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aibaodan.cn/Article/details/gtxhctpxkh.html

[Q08] 创建普通索引
来源：http://dali.shuidangran.top/Article/details/gtiabkrlwa.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xuanzx.com/Article/details/gtutxpnowy.html

[Q09] 创建唯一索引
来源：http://dali.jyoumei.cn/Article/details/gtcdzfopjv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.svipenyu.cn/Article/details/gtoywrkjva.html

[Q10] 插入单行
来源：http://dali.pycfn.com/Article/details/gtsrkvcawd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtusoqcodd.html

[Q11] 一次插入多行
来源：http://dali.chenlongwang.top/Article/details/gttkjptknt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shuidangran.top/Article/details/gthwdgxbtn.html

[Q12] 插入后取自增 ID
来源：http://dali.zhixingplan.top/Article/details/gtcpxvhixn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.feifeiyinyue.top/Article/details/gtcdhdqkhr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jqgufenzy.top/Article/details/gtnhnqgakv.html

[Q13] 忽略重复插入
来源：http://dali.pengpengdd.cyou/Article/details/gtpfyuieqy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtbijvsxyq.html

[Q14] 存在则更新（upsert）
来源：http://dali.haohaochexian.top/Article/details/gtgznhlxtq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yonumen.top/Article/details/gtnczjfuma.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tianlin.xyz/Article/details/gtxldijlzc.html

[Q15] 查询全部
来源：http://dali.zhengqikj.top/Article/details/gtbdsnyvmq.html

SELECT * FROM users;
来源：http://dali.smart0.xyz/Article/details/gtsrjgseyw.html

[Q16] 查询指定列
来源：http://dali.daxiang520.top/Article/details/gtgiotbnge.html

SELECT id, name FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtvvgwuntb.html

[Q17] 条件查询
来源：http://dali.kuanghao11.cn/Article/details/gtsvsrlowx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ivvv.top/Article/details/gthuptbgfz.html

[Q18] 模糊匹配
来源：http://dali.nwbrower.top/Article/details/gteqmwlhlz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.wangdashe.top/Article/details/gthkshfqpn.html

[Q19] 范围查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtuivwqouc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj202588.top/Article/details/gtpievhnty.html

[Q20] IN 列表
来源：http://dali.jyoumei.cn/Article/details/gttjoinavo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.mhx1999.top/Article/details/gtitlcvdeb.html

[Q21] 空值判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbmwwkid.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gtoaagulot.html

[Q22] 排序
来源：http://dali.yuanzhike.top/Article/details/gtusjmzaqg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenlongwang.top/Article/details/gtzociszzh.html

[Q23] 分页
来源：http://dali.yj20258.top/Article/details/gthgrexrwp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yongpay.top/Article/details/gtgnhhsccw.html

[Q24] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gtvjbavybf.html

SELECT DISTINCT city FROM users;
来源：http://dali.sysykeji.top/Article/details/gteoxavria.html

[Q25] 只取前 N 条
来源：http://dali.gzhubu.top/Article/details/gtkzsdpits.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xuanzx.com/Article/details/gtadcrydih.html

[Q26] 计数
来源：http://dali.aibaodan.cn/Article/details/gtqojlzpsn.html

SELECT COUNT(*) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtgnnhprwf.html

[Q27] 条件计数
来源：http://dali.yuanzhike.top/Article/details/gttworcaob.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtzbvvktuh.html

[Q28] 求和与平均
来源：http://dali.fzhhl.top/Article/details/gtdhsqplen.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.havefunace.top/Article/details/gtzxcurxcw.html

[Q29] 最大最小值
来源：http://dali.havefunace.top/Article/details/gttqaieeid.html


<!-- 参考信息 -->