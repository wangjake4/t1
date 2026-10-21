代发 wailian999

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtujpuohjt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.guowangkeji.top/Article/details/gtylxzndmn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tianlin.xyz/Article/details/gtlszgbicd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cqqwz.cn/Article/details/gthbkdtzaj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gtoozowahl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjjesctl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxinkj.top/Article/details/gtnuhnxemi.html

Go:   slices.Sort(arr)
来源：http://dali.tanke756.top/Article/details/gtskosnmvo.html

Ruby: arr.sort
来源：http://dali.bjfxy.top/Article/details/gtxukofkmo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yvedp.cn/Article/details/gtrxciopdw.html

[N03] 快速排序（分治示例）
来源：http://dali.daria6918.cn/Article/details/gtkeuhxmen.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yangfankeji.com/Article/details/gtzbxcwhag.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yonumen.top/Article/details/gtermuvwzb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gtpbziboyy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gtlebphats.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenjidiqi.icu/Article/details/gtjdhsvmfe.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cdnleiting.top/Article/details/gtrleegybz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.birdmap.top/Article/details/gtuvryuzwa.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dianchejie.cn/Article/details/gtzacnpdag.html

[N04] 斐波那契数列
来源：http://dali.chenlongwang.top/Article/details/gtuutybcjz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gtvozmecyx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.bjfxy.top/Article/details/gtcqhharfu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gthmozbpnx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtxjlyqnor.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gtonskhaxw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxuanxn.top/Article/details/gtwtjvpexe.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtjfqfeues.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtbtknkwms.html

[N05] 最大公约数
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtsyyeon.html

Py:   math.gcd(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrlmdwks.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guowangkeji.top/Article/details/gtvlvbfbbx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gtyaxpzrxj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtngymudif.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangtech.top/Article/details/gtptjkxoer.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jlsjyb.cn/Article/details/gtuenkeyle.html

Ruby: a.gcd(b)
来源：http://dali.sufxvd.cn/Article/details/gtebfwqrfx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhixingplan.top/Article/details/gtmsixocuk.html

[N06] 判断回文字符串
来源：http://dali.hnxiangtu.top/Article/details/gtuzgijpuu.html

Py:   s == s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gtobqayagx.html

PHP:  $s === strrev($s);
来源：http://dali.yongpay.top/Article/details/gtgwcedaum.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtmhgsbsbk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtlziqtope.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.mhx1999.top/Article/details/gtvqkdvjbh.html

Go:   // 双指针从两端比较
来源：http://dali.9152youxi.cn/Article/details/gtuohrvasq.html

Ruby: s == s.reverse
来源：http://dali.ydzc1.top/Article/details/gtsfuzikmy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gtztdeztpf.html

[N07] 两数之和（返回下标）
来源：http://dali.sweek.top/Article/details/gtgikzbbom.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.havefunace.top/Article/details/gtufbmenhz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhongyouzk.top/Article/details/gtqtlutelu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yonumen.top/Article/details/gtztjhuwdg.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangshuangyany.cn/Article/details/gtqwyhzysl.html

Java: // 手写 HashMap
来源：http://dali.zhixingplan.top/Article/details/gtcorlzfva.html

Go:   // 手写 map[int]int
来源：http://dali.zhoulong.xyz/Article/details/gtxpnbxgav.html

Ruby: // 手写 Hash
来源：http://dali.xziqi.cn/Article/details/gtniavyvzl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dianchejie.cn/Article/details/gtrtebcwuo.html

[N08] 生成全排列
来源：http://dali.c1oappe.top/Article/details/gtdomhgoel.html

Py:   itertools.permutations(arr)
来源：http://dali.0kj1m.cn/Article/details/gtjxebzoeh.html

PHP:  // 手写递归交换
来源：http://dali.yuanzhike.top/Article/details/gtugzorpwa.html

JS:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gthagowlmw.html

TS:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtoyunzkhm.html

Java: // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtxvoowwjg.html

Go:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtdihfrowb.html

Ruby: arr.permutation.to_a
来源：http://dali.sysykeji.top/Article/details/gtzdoerymg.html

C#:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtqmhdhdqo.html

[N09] 栈与队列
来源：http://dali.ivvv.top/Article/details/gtzotqcfcj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldoylpyn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gtvuxpsmor.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gttcbrnwnm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.316326.xyz/Article/details/gtjpmddriy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.wangdashe.top/Article/details/gtihzomstd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdsegzig.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtfofljkab.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zycfv.cn/Article/details/gtsdbnyevt.html

[N10] 链表节点定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbhhiifi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jianghu66.top/Article/details/gttkarozgo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.smart0.xyz/Article/details/gtdncgoyja.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sweek.top/Article/details/gtaqjptogz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hysaishi.cn/Article/details/gttshywwya.html

Java: class Node { int v; Node next; }
来源：http://dali.zhiwuduotai.top/Article/details/gtngrzjfug.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.birdmap.top/Article/details/gtxsimftjb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xuetiantiany.cn/Article/details/gtyqcbrhha.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgfzy.top/Article/details/gtlxvsowbt.html

[N11] 二叉树中序遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtobgfbunv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ybcxt.top/Article/details/gtwvvmubmc.html

PHP:  // 手写递归函数
来源：http://dali.svipenyu.cn/Article/details/gtxzbasedf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gtrzetixmb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gtkgfezzrd.html

Java: // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcaahiqp.html

Go:   // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtttrzsndx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xziqi.cn/Article/details/gtiumcdrxa.html

C#:   // 手写递归
来源：http://dali.gzhubu.top/Article/details/gtjfmvsnkw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gtrgmyxlec.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gaohongyu789.top/Article/details/gtqrejzmqn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tian-w.cn/Article/details/gtcckpkeed.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtfwigopxv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gtikuttftu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gtaiizmyav.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.wangdashe.top/Article/details/gtloavsgui.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cdnleiting.top/Article/details/gtczlvpkze.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gtvgodlhex.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtmfqbaetp.html

O. 并发与异步
来源：http://dali.c1oappe.top/Article/details/gtegibdayq.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtafkixoco.html

[O01] 启动一个线程
来源：http://dali.tianlin.xyz/Article/details/gtturricop.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.316326.xyz/Article/details/gtesglgohy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jqgfzy.top/Article/details/gtxghhgfgd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuanzhike.top/Article/details/gtedqcsogx.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gtlzaodqll.html

Java: new Thread(() -> f()).start()
来源：http://dali.snrcjt.cn/Article/details/gtommkyacn.html

Go:   go f()
来源：http://dali.jinqigufen.top/Article/details/gtassrctmv.html

Ruby: Thread.new { f }
来源：http://dali.316326.xyz/Article/details/gtiiqvacop.html

C#:   Task.Run(() => F());
来源：http://dali.xziqi.cn/Article/details/gtqdcfimgc.html

[O02] 使用线程池
来源：http://dali.yuanzhike.top/Article/details/gthxnzguhl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hywenlv.cn/Article/details/gtwwblfiaq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gzhubu.top/Article/details/gtwmoiuepe.html

JS:   // worker_threads 线程池
来源：http://dali.ydzc1.top/Article/details/gtclwtmhwe.html

TS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gtmhrpchka.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.quarkkingdee.top/Article/details/gtymjngkiq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangshuangyany.cn/Article/details/gtzvmxchos.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.redwolf501.top/Article/details/gtrxqnklue.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.meibo888.top/Article/details/gtifwqhwsg.html

[O03] 加锁保护共享数据
来源：http://dali.ivvv.top/Article/details/gtrvebyrnq.html

Py:   with lock: shared += 1
来源：http://dali.guannengcc.top/Article/details/gtpvkpeshg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.0kj1m.cn/Article/details/gtvqddgahm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yangfankeji.com/Article/details/gtmbuveqeb.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gtfglrxlos.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gtuqoihjek.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.havefunace.top/Article/details/gtixifysat.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.birdmap.top/Article/details/gttkfwplpl.html

C#:   lock (gate) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gtjgqxziav.html

[O04] 定义异步函数并等待
来源：http://dali.andypj.xyz/Article/details/gtbrnfqsad.html

Py:   async def f():⏎    await g()
来源：http://dali.xuanzx.com/Article/details/gtiogdrdrv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gogol.net.cn/Article/details/gtacojxiey.html

JS:   async function f() { await g(); }
来源：http://dali.jlsjyb.cn/Article/details/gtbnxjcbfh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.birdmap.top/Article/details/gtjdedtglc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.pengpengdd.cyou/Article/details/gtutlxlvov.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tianlin.xyz/Article/details/gtukofntqz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yangfankeji.com/Article/details/gtldnejvlm.html

C#:   async Task F() { await G(); }
来源：http://dali.hammf.cn/Article/details/gtwudnrffq.html

[O05] 并发执行并等待全部完成
来源：http://dali.kuanghao11.cn/Article/details/gtjyxpcvfd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.iojbl.cn/Article/details/gtbwjpusyy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tianlin.xyz/Article/details/gtdxjnpfqq.html

JS:   await Promise.all(tasks)
来源：http://dali.zhongyouzk.top/Article/details/gtxnfcksyx.html

TS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwwjzaza.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.dianchejie.cn/Article/details/gthefxfbik.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ybcxt.top/Article/details/gtnplbuidr.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gtpmapodbu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxaihzqsb.html

[O06] 使用进程池
来源：http://dali.yanxiufei.cn/Article/details/gtzqnkyxgu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangdashe.top/Article/details/gtkucxfygu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.vqdsnc.cn/Article/details/gtftgarkbe.html

JS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gtasoqzscf.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gtplwajkfz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.c1oappe.top/Article/details/gtpqhtxeyz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcwyoarh.html

Ruby: // fork 块
来源：http://dali.hammf.cn/Article/details/gtkqchxpjb.html

C#:   Parallel.For
来源：http://dali.chenlongwang.top/Article/details/gtucwfwlzm.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtsnumdbnm.html

P. 常用工具函数
来源：http://dali.jiagoushi.top/Article/details/gtfyyxdhns.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtlovqeokp.html

[P01] 生成 UUID
来源：http://dali.c1oappe.top/Article/details/gtkodcilps.html

Py:   str(uuid.uuid4())
来源：http://dali.iojbl.cn/Article/details/gtkppgviga.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenjidiqi.icu/Article/details/gtcfjeqnfh.html

JS:   crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gtpuxhucva.html

TS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtmdioutpg.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgfzy.top/Article/details/gtyndpzwfk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.meibo888.top/Article/details/gtxjyatsko.html

Ruby: SecureRandom.uuid
来源：http://dali.zhengqikj.top/Article/details/gtknnhpauz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuanzx.com/Article/details/gthnvjzqzw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.bjfxy.top/Article/details/gtpyentqup.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zycfv.cn/Article/details/gtdiyralpr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.meibo888.top/Article/details/gtsehdywal.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ehwqpu.com/Article/details/gtedvlcfhf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cdnleiting.top/Article/details/gthctpeusf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtkgnzdbtw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.mhx1999.top/Article/details/gtvyfqibtv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhixingplan.top/Article/details/gtfjuxgvbo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.0kj1m.cn/Article/details/gtttpkgeop.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gtwobqveqq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.bjfxy.top/Article/details/gtcnoazmtu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ppjwa.cn/Article/details/gteuiizpur.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.feifeiyinyue.top/Article/details/gttdbnxrpo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gtymbejtgq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnqzz.top/Article/details/gtiurtpkuz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aizwys.cn/Article/details/gtsrrobnhe.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.c1oappe.top/Article/details/gttebgtcjy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ybcxt.top/Article/details/gtjmtrapts.html

[P04] 求长度
来源：http://dali.316326.xyz/Article/details/gtqlxotkhw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sxryk.cn/Article/details/gtfymogxku.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtjczqqitr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenzaomai.com/Article/details/gtndaekgae.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daxiang520.top/Article/details/gteiuyrdul.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guannengcc.top/Article/details/gtufuenbvj.html

Go:   len(arr);  len(m)
来源：http://dali.iojbl.cn/Article/details/gtebigvilf.html

Ruby: x.length;  x.size
来源：http://dali.hysaishi.cn/Article/details/gtunziufmb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.havefunace.top/Article/details/gtgujqcqel.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhengqikj.top/Article/details/gtmxwdrjid.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhiwuduotai.top/Article/details/gtdlbriayd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgufenzy.top/Article/details/gtewkkjekb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.feifeiyinyue.top/Article/details/gtlcpwfizh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tanke756.top/Article/details/gtxzdodwgk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shzxlz.cn/Article/details/gtduceywgd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtjirutdxr.html

Ruby: a == b
来源：http://dali.zhoulong.xyz/Article/details/gttjtevzfn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.0kj1m.cn/Article/details/gtivtjihxb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenzaomai.com/Article/details/gtqedowedl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.mhx1999.top/Article/details/gtycaamusn.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gtcgxtltyp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.aizwys.cn/Article/details/gtjfhjxqeu.html

TS:   if (x == null) {}
来源：http://dali.hywenlv.cn/Article/details/gteyvazlkq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpweaqytp.html

Go:   if x == nil {}
来源：http://dali.snrcjt.cn/Article/details/gtezewfdrd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbenxnop.html

C#:   if (x is null) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtnssusznk.html

[P07] 防抖与节流
来源：http://dali.yonumen.top/Article/details/gtzdxxbdsj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cashguo.top/Article/details/gtdpkwbyii.html

PHP:  // 手写时间戳比较
来源：http://dali.c1oappe.top/Article/details/gtanfzvulk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gtyyrhmamn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gtxncodjrh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.guowangkeji.top/Article/details/gtkiccicjh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yueranfly.top/Article/details/gtpnupuudx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gogol.net.cn/Article/details/gtddyjgrrm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tianlin.xyz/Article/details/gtixtrbhiy.html

[P08] 处理浮点精度问题
来源：http://dali.snrcjt.cn/Article/details/gthhroycwu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj202588.top/Article/details/gtaegdojrj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ppjwa.cn/Article/details/gtlzfukonx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tian-w.cn/Article/details/gtxvgkisyt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cashguo.top/Article/details/gtgpzmqeev.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yangfankeji.com/Article/details/gtbiylsxbm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinghuilouyu.cn/Article/details/gtlurmafqz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.guannengcc.top/Article/details/gtyfkpswgw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sxryk.cn/Article/details/gtejfugkdc.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtyixexklf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.aizwys.cn/Article/details/gtotvmblat.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtskhfrvls.html

[Q01] 创建表
来源：http://dali.andypj.xyz/Article/details/gtudyofmxt.html

CREATE TABLE users (
来源：http://dali.zhengqikj.top/Article/details/gtfxkaaayv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ehwqpu.com/Article/details/gtrefmbkdd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yueranfly.top/Article/details/gtkyfmjbka.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jlsjyb.cn/Article/details/gttudghiew.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nanxuanxn.top/Article/details/gtlmaxiosj.html

);
来源：http://dali.ppjwa.cn/Article/details/gtdbmcqwle.html

[Q02] 创建带外键的表
来源：http://dali.hongshengwenyu.top/Article/details/gtvquurhno.html

CREATE TABLE orders (
来源：http://dali.yueranfly.top/Article/details/gtavhxcflk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xylfe.cn/Article/details/gtoeiqwwjc.html

user_id INT NOT NULL,
来源：http://dali.sweek.top/Article/details/gtfqzmcvnw.html

amount DECIMAL(10, 2),
来源：http://dali.jiagoushi.top/Article/details/gtaawqcoxx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.9152youxi.cn/Article/details/gtmpqrutsh.html

);
来源：http://dali.vqdsnc.cn/Article/details/gtekrgxygy.html

[Q03] 增加列
来源：http://dali.9152youxi.cn/Article/details/gtcsgomyhn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.haohaochexian.top/Article/details/gtquqhwjnq.html

[Q04] 修改列类型
来源：http://dali.tianlin.xyz/Article/details/gtgjkboxeh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cashguo.top/Article/details/gtwlzdrpgs.html

[Q05] 重命名列
来源：http://dali.zhoulong.xyz/Article/details/gtvmgouewh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cheryme.top/Article/details/gtpnvwatmr.html

[Q06] 删除列
来源：http://dali.meibo888.top/Article/details/gtkuljecfl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hongshengwenyu.top/Article/details/gtqdkbmmfj.html

[Q07] 删除表
来源：http://dali.aizwys.cn/Article/details/gttvhgteui.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcvvmidp.html

[Q08] 创建普通索引
来源：http://dali.hfpthk.cn/Article/details/gtslwhvkgw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gtkwgjmeaj.html

[Q09] 创建唯一索引
来源：http://dali.tianlin.xyz/Article/details/gtcdgmbuxb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gtsiudagzu.html

[Q10] 插入单行
来源：http://dali.tianlin.xyz/Article/details/gtxdvmfdyp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.haohaochexian.top/Article/details/gtpvlcwnul.html

[Q11] 一次插入多行
来源：http://dali.xziqi.cn/Article/details/gtslwghlpd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggjjtzao.html

[Q12] 插入后取自增 ID
来源：http://dali.yonumen.top/Article/details/gthaarnxpw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hfpthk.cn/Article/details/gtgjnaaaad.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dianchejie.cn/Article/details/gttmzukfve.html

[Q13] 忽略重复插入
来源：http://dali.vqdsnc.cn/Article/details/gtblxsyaau.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yuanzhike.top/Article/details/gtynmxclzy.html

[Q14] 存在则更新（upsert）
来源：http://dali.ppjwa.cn/Article/details/gtwbtyjjvw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xziqi.cn/Article/details/gtdipnosmj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cheryme.top/Article/details/gtkazkvmwa.html

[Q15] 查询全部
来源：http://dali.yongpay.top/Article/details/gtcokffgbw.html

SELECT * FROM users;
来源：http://dali.shuidangran.top/Article/details/gtmfokgmar.html

[Q16] 查询指定列
来源：http://dali.ivvv.top/Article/details/gtfsuzeobb.html

SELECT id, name FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtrawxyrxf.html

[Q17] 条件查询
来源：http://dali.zhongyouzk.top/Article/details/gtaivdbctt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.dianchejie.cn/Article/details/gthbyrhdkz.html

[Q18] 模糊匹配
来源：http://dali.iojbl.cn/Article/details/gtshqemprn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yuanzhike.top/Article/details/gtlkaqjmtb.html

[Q19] 范围查询
来源：http://dali.shzxlz.cn/Article/details/gtlrveprgy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shuidangran.top/Article/details/gthhyrhfxy.html

[Q20] IN 列表
来源：http://dali.jinqigfzy.top/Article/details/gtnhbhayyg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.c1oappe.top/Article/details/gtholvfnwy.html

[Q21] 空值判断
来源：http://dali.nwbrower.top/Article/details/gtojkhntia.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hfpthk.cn/Article/details/gthshauksb.html

[Q22] 排序
来源：http://dali.sysykeji.top/Article/details/gtylxnnwnl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shzxlz.cn/Article/details/gtszeasdhc.html

[Q23] 分页
来源：http://dali.wangdashe.top/Article/details/gtxoxjrolf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yanxiufei.cn/Article/details/gtztgyvvsb.html

[Q24] 去重
来源：http://dali.yj20258888.top/Article/details/gtvffgqxfd.html

SELECT DISTINCT city FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtobqkzngi.html

[Q25] 只取前 N 条
来源：http://dali.hongshengwenyu.top/Article/details/gtnhxfjsmn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgufenzy.top/Article/details/gtiyafqkks.html

[Q26] 计数
来源：http://dali.daria6918.cn/Article/details/gtydfjjvzv.html

SELECT COUNT(*) FROM users;
来源：http://dali.316326.xyz/Article/details/gtgsbokqhh.html

[Q27] 条件计数
来源：http://dali.sweek.top/Article/details/gtangzvbqg.html


<!-- 参考信息 -->