代发 wailian999

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gtjvejbsfa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtpcoeqlvv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuanzhike.top/Article/details/gtckkoybah.html

Go:   slices.Sort(arr)
来源：http://dali.yongpay.top/Article/details/gtntkzhhvh.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gtwjgvbphd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.haohaochexian.top/Article/details/gtfcoabssf.html

[N03] 快速排序（分治示例）
来源：http://dali.sweek.top/Article/details/gtucpeodka.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gotoacloud.top/Article/details/gtltwyxmtv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cqqwz.cn/Article/details/gtjteeqmhw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gogol.net.cn/Article/details/gtnjouvycs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gthtyuvymt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yanxiufei.cn/Article/details/gtsfwsfley.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigufen.top/Article/details/gtoiugirlx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jianghu66.top/Article/details/gtwjogwfrm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shangyingyoupin.top/Article/details/gtithznqic.html

[N04] 斐波那契数列
来源：http://dali.andypj.xyz/Article/details/gtjvwqwdma.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtzrxbddnz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdazoqtby.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gtxituubzf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gterntvsov.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwuwgdwz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.haohaochexian.top/Article/details/gtitdnyjhp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shzxlz.cn/Article/details/gtwptphmpz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtpoouxvhy.html

[N05] 最大公约数
来源：http://dali.cashguo.top/Article/details/gtxarotvwx.html

Py:   math.gcd(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtavqltrwk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.andypj.xyz/Article/details/gtmjtbfavz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gtmahfygqi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gtufohlffs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258.top/Article/details/gtuvbkmmfx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnxiangtu.top/Article/details/gthpcgkwbv.html

Ruby: a.gcd(b)
来源：http://dali.tian-w.cn/Article/details/gtkpybgabq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.svipenyu.cn/Article/details/gtkduacdfc.html

[N06] 判断回文字符串
来源：http://dali.wangdashe.top/Article/details/gttkcxnhbr.html

Py:   s == s[::-1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumzmhfqp.html

PHP:  $s === strrev($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtjkviyrih.html

JS:   s === [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtpytkgpvf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtjzmwfetb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangshuangyany.cn/Article/details/gtzfntndhf.html

Go:   // 双指针从两端比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllavyaaz.html

Ruby: s == s.reverse
来源：http://dali.fzhhl.top/Article/details/gtjfdxekga.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gtqnslmcpx.html

[N07] 两数之和（返回下标）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiawpffpz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cashguo.top/Article/details/gtjrjkslzt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tanke756.top/Article/details/gthemoytxu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasokwfib.html

TS:   // 手写 Map<string, number>
来源：http://dali.daria6918.cn/Article/details/gtsaeudtyx.html

Java: // 手写 HashMap
来源：http://dali.pycfn.com/Article/details/gtqudfcyph.html

Go:   // 手写 map[int]int
来源：http://dali.zhongyouzk.top/Article/details/gtykptemej.html

Ruby: // 手写 Hash
来源：http://dali.jinqigfzy.top/Article/details/gtbfmzdebs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.316326.xyz/Article/details/gtafrobtnp.html

[N08] 生成全排列
来源：http://dali.vqdsnc.cn/Article/details/gtwtjqfwex.html

Py:   itertools.permutations(arr)
来源：http://dali.hfpthk.cn/Article/details/gtartlhvep.html

PHP:  // 手写递归交换
来源：http://dali.ppjwa.cn/Article/details/gthxkkrtpl.html

JS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtsimwyxhy.html

TS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtdlrkkevh.html

Java: // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuaophneh.html

Go:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtfmtwjmhj.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigufen.top/Article/details/gthyranmpq.html

C#:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gttcfktror.html

[N09] 栈与队列
来源：http://dali.haohaochexian.top/Article/details/gtzmletddb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnxiangtu.top/Article/details/gthrlikyao.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj202588.top/Article/details/gtzldaqkss.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gtjulesdmt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shangyingyoupin.top/Article/details/gtjrjaeyjd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenlongwang.top/Article/details/gtfioxvawd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.316326.xyz/Article/details/gtfxhnrsrf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gteaugknph.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.kuanghao11.cn/Article/details/gtyjeuhhmt.html

[N10] 链表节点定义
来源：http://dali.mhx1999.top/Article/details/gtkdmxqxuj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dianchejie.cn/Article/details/gtkcorjmwy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cashguo.top/Article/details/gtcrbzewjk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hywenlv.cn/Article/details/gtcfirbish.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hongshengwenyu.top/Article/details/gtrfvfplwg.html

Java: class Node { int v; Node next; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gticzbojoz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigfzy.top/Article/details/gtyieiabtl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuxming.cn/Article/details/gtzgjsuzds.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.iojbl.cn/Article/details/gtjtdlqnxj.html

[N11] 二叉树中序遍历
来源：http://dali.sufxvd.cn/Article/details/gtihscrsee.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.snrcjt.cn/Article/details/gteszbismf.html

PHP:  // 手写递归函数
来源：http://dali.chenlongwang.top/Article/details/gtxpnhrfsh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gthgtfnksl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gtvjisjtzw.html

Java: // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gtbrugcnzs.html

Go:   // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gtxldpenab.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cucudq.cn/Article/details/gtzlcwmhpy.html

C#:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtehijtufs.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zycfv.cn/Article/details/gtfqcsgnyg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhixingplan.top/Article/details/gtnmrnfixj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hnqzz.top/Article/details/gtvdgwiduy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnqhcfko.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnqzz.top/Article/details/gthchvrwor.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknxkdtxt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hywenlv.cn/Article/details/gtbodctygt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fengsongda.top/Article/details/gtxuypgyyt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sweek.top/Article/details/gtbmusymvt.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtgfjhbmwa.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gtdoskkvww.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwlvogka.html

[O01] 启动一个线程
来源：http://dali.zdqjudy.top/Article/details/gteljxavsh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.meibo888.top/Article/details/gtzhpdvxvw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jyoumei.cn/Article/details/gtpqqlrbtc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xinyue.icu/Article/details/gtmzhzwvno.html

TS:   // 同 JS
来源：http://dali.yanxiufei.cn/Article/details/gtbwujdyts.html

Java: new Thread(() -> f()).start()
来源：http://dali.9152youxi.cn/Article/details/gtilqsjdmh.html

Go:   go f()
来源：http://dali.yuanzhike.top/Article/details/gtgskngoif.html

Ruby: Thread.new { f }
来源：http://dali.jqgfzy.top/Article/details/gtbvqmbxdk.html

C#:   Task.Run(() => F());
来源：http://dali.ydzc1.top/Article/details/gttzopevmc.html

[O02] 使用线程池
来源：http://dali.yonumen.top/Article/details/gtbkvntupb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxinkj.top/Article/details/gttrmfdukf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.smart0.xyz/Article/details/gtputrxpah.html

JS:   // worker_threads 线程池
来源：http://dali.yongpay.top/Article/details/gtlqrxcrbh.html

TS:   // worker_threads 线程池
来源：http://dali.xylfe.cn/Article/details/gtfdalnwbw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daxiang520.top/Article/details/gtvhizyijb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zycfv.cn/Article/details/gtfydqybvg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jianghu66.top/Article/details/gtsfjaoupn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhiwuduotai.top/Article/details/gtddimhweo.html

[O03] 加锁保护共享数据
来源：http://dali.chenjidiqi.icu/Article/details/gtbjbbtshb.html

Py:   with lock: shared += 1
来源：http://dali.tian-w.cn/Article/details/gtrlftqelo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangdashe.top/Article/details/gtvkipqwku.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.daxiang520.top/Article/details/gtuhqvpchn.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gtzykjuflh.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gtncxfofhx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkcmklxx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ppjwa.cn/Article/details/gtmfbpodeb.html

C#:   lock (gate) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gtprufyxps.html

[O04] 定义异步函数并等待
来源：http://dali.haohaochexian.top/Article/details/gtesvhkerm.html

Py:   async def f():⏎    await g()
来源：http://dali.hammf.cn/Article/details/gtwvbecdjw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.c1oappe.top/Article/details/gtqtwmxvqe.html

JS:   async function f() { await g(); }
来源：http://dali.aizwys.cn/Article/details/gtcxstywtt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gtrxxatbwt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.feifeiyinyue.top/Article/details/gtdronvjwf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.pycfn.com/Article/details/gtbehjkwpu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuobtkzii.html

C#:   async Task F() { await G(); }
来源：http://dali.9152youxi.cn/Article/details/gthjmujwxg.html

[O05] 并发执行并等待全部完成
来源：http://dali.yvedp.cn/Article/details/gtchbulxxk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenzaomai.com/Article/details/gtxelvrkyl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tian-w.cn/Article/details/gttummgnst.html

JS:   await Promise.all(tasks)
来源：http://dali.chenzaomai.com/Article/details/gtzueoztfv.html

TS:   await Promise.all(tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gtliutothe.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hysaishi.cn/Article/details/gtvzwkvcct.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hammf.cn/Article/details/gtjwbpgpdq.html

Ruby: threads.map(&:join)
来源：http://dali.316326.xyz/Article/details/gtnrefxpeq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgfzy.top/Article/details/gtlxtytrzz.html

[O06] 使用进程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqlfiutm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fzhhl.top/Article/details/gtxpdmgjot.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.wangdashe.top/Article/details/gtjuykanqo.html

JS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gtqpdgglcl.html

TS:   // child_process / cluster 模块
来源：http://dali.xuetiantiany.cn/Article/details/gtlnuhxlot.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jyoumei.cn/Article/details/gtmfrsauja.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xuetiantiany.cn/Article/details/gtlfoqlukz.html

Ruby: // fork 块
来源：http://dali.yuanzhike.top/Article/details/gtxdqqnptv.html

C#:   Parallel.For
来源：http://dali.ivvv.top/Article/details/gtagprjzdu.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gthdfgziub.html

P. 常用工具函数
来源：http://dali.jlsjyb.cn/Article/details/gtiwijqaii.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gteyvysmhb.html

[P01] 生成 UUID
来源：http://dali.cqqwz.cn/Article/details/gtkxsvhyng.html

Py:   str(uuid.uuid4())
来源：http://dali.xinyue.icu/Article/details/gtiqexscge.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.quarkkingdee.top/Article/details/gtkwgwdcra.html

JS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gtugzknujg.html

TS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gtxcaxkiwc.html

Java: UUID.randomUUID().toString()
来源：http://dali.shuidangran.top/Article/details/gtxrgopxsj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cqqwz.cn/Article/details/gtglctoxek.html

Ruby: SecureRandom.uuid
来源：http://dali.zhongyouzk.top/Article/details/gtklttdtsv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.iojbl.cn/Article/details/gtfrgzozcv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hammf.cn/Article/details/gtuzroigar.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.quarkkingdee.top/Article/details/gtwlnenaof.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gzhubu.top/Article/details/gtjxvazjhd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.quarkkingdee.top/Article/details/gtahwzlrss.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nwbrower.top/Article/details/gtjsgbammq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.fzhhl.top/Article/details/gtunptmpqw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xylfe.cn/Article/details/gtmavjjyew.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.havefunace.top/Article/details/gtmubczwow.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sweek.top/Article/details/gtgsvcfjcz.html

[P03] 生成短随机字符串
来源：http://dali.gaohongyu789.top/Article/details/gtmzjvofxp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sxryk.cn/Article/details/gtpueryiau.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.bjfxy.top/Article/details/gtrfebzkwx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.9152youxi.cn/Article/details/gtykhkvmql.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvoyuoawc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.0kj1m.cn/Article/details/gtxxumruwd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gotoacloud.top/Article/details/gtcuvndhrv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenzaomai.com/Article/details/gtfpitzfne.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.dashuyun.cn/Article/details/gtxnmuodvx.html

[P04] 求长度
来源：http://dali.pengpengdd.cyou/Article/details/gtguyggvto.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jlsjyb.cn/Article/details/gtxcgoapae.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtjoxdwuun.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xinyue.icu/Article/details/gtmreobwqz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sufxvd.cn/Article/details/gtwbjuqhup.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhengqikj.top/Article/details/gtydhwxmna.html

Go:   len(arr);  len(m)
来源：http://dali.daria6918.cn/Article/details/gtyyaxvtgb.html

Ruby: x.length;  x.size
来源：http://dali.gotoacloud.top/Article/details/gtueggekzg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tianlin.xyz/Article/details/gtjrerxgny.html

[P05] 判断两个对象内容是否相等
来源：http://dali.0kj1m.cn/Article/details/gttpwmcthx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gogol.net.cn/Article/details/gtgkzsshga.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jianghu66.top/Article/details/gtdpraubgh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shangyingyoupin.top/Article/details/gtnhjazpca.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gthmoasppu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenjidiqi.icu/Article/details/gtluklxqwi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258888.top/Article/details/gtkdznzokb.html

Ruby: a == b
来源：http://dali.guowangkeji.top/Article/details/gtqdhzwzds.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.andypj.xyz/Article/details/gtxlxdsuwv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.smart0.xyz/Article/details/gtbzfdzrgh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tian-w.cn/Article/details/gtrhkeaexo.html

PHP:  if (empty($x)) {}
来源：http://dali.xinyue.icu/Article/details/gtljhettvm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tanke756.top/Article/details/gtsjikkeyo.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtjixmkqvn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtwwkrzsan.html

Go:   if x == nil {}
来源：http://dali.chenjidiqi.icu/Article/details/gtseuvqyqz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.daxiang520.top/Article/details/gtjiigmqhy.html

C#:   if (x is null) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtxflzaodm.html

[P07] 防抖与节流
来源：http://dali.chenzaomai.com/Article/details/gteqhqppfw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daria6918.cn/Article/details/gtkrkxvazv.html

PHP:  // 手写时间戳比较
来源：http://dali.yj202588.top/Article/details/gtkzxutjxp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gtxskdblht.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gthupdqcxr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxuanxn.top/Article/details/gtgardhwsy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ydzc1.top/Article/details/gtxbifoqbt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenzaomai.com/Article/details/gthldcgarj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jlsjyb.cn/Article/details/gtwjucikhu.html

[P08] 处理浮点精度问题
来源：http://dali.snrcjt.cn/Article/details/gtznzxytyg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenlongwang.top/Article/details/gtwhmwkbmg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcivydkki.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.havefunace.top/Article/details/gtvxqwsenx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tanke756.top/Article/details/gtdmuzqipy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xylfe.cn/Article/details/gteqnhugym.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnxiangtu.top/Article/details/gtpavdrsmy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.0kj1m.cn/Article/details/gtrivakukv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.9152youxi.cn/Article/details/gtsdsxvswg.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtltnkzywg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jyoumei.cn/Article/details/gtnefllihk.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtzbzmpnwu.html

[Q01] 创建表
来源：http://dali.meibo888.top/Article/details/gtdynkwzfo.html

CREATE TABLE users (
来源：http://dali.shuidangran.top/Article/details/gtgrfxajcg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fzhhl.top/Article/details/gtemgnuxqk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gtlrbiyqfg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.guannengcc.top/Article/details/gtabkpauxy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daria6918.cn/Article/details/gtmhmxbtnv.html

);
来源：http://dali.cdnleiting.top/Article/details/gtvhnizxxo.html

[Q02] 创建带外键的表
来源：http://dali.sufxvd.cn/Article/details/gtjvzrxrkb.html

CREATE TABLE orders (
来源：http://dali.yvedp.cn/Article/details/gtfmcreumm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gthjupvpgl.html

user_id INT NOT NULL,
来源：http://dali.hywenlv.cn/Article/details/gticmlnofs.html

amount DECIMAL(10, 2),
来源：http://dali.hongshengwenyu.top/Article/details/gtampovfao.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenzaomai.com/Article/details/gtrueghtyn.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gtssquqnrw.html

[Q03] 增加列
来源：http://dali.shuidangran.top/Article/details/gtqtnxjwwq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yvedp.cn/Article/details/gtjyqgnbxl.html

[Q04] 修改列类型
来源：http://dali.zhongyouzk.top/Article/details/gtonuzbtzm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbysfzwcm.html

[Q05] 重命名列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjzzucvz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hongshengwenyu.top/Article/details/gteipxitfl.html

[Q06] 删除列
来源：http://dali.jqgufenzy.top/Article/details/gtrokdtzzj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.vqdsnc.cn/Article/details/gtuseupudm.html

[Q07] 删除表
来源：http://dali.ehwqpu.com/Article/details/gtqngvtdfr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtljhozpdj.html

[Q08] 创建普通索引
来源：http://dali.chenzaomai.com/Article/details/gtuhmigxrn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gtplafodfo.html

[Q09] 创建唯一索引
来源：http://dali.gaohongyu789.top/Article/details/gteqsngyxe.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gtfjlfuuon.html

[Q10] 插入单行
来源：http://dali.yuxming.cn/Article/details/gtfsbeasnj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdvzehmc.html

[Q11] 一次插入多行
来源：http://dali.yuxming.cn/Article/details/gtzptrjrha.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gtjzwydrpe.html

[Q12] 插入后取自增 ID
来源：http://dali.gaohongyu789.top/Article/details/gttnpykstb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zycfv.cn/Article/details/gtjeisosfh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ppjwa.cn/Article/details/gtwlnhkstv.html

[Q13] 忽略重复插入
来源：http://dali.ppjwa.cn/Article/details/gtuskuatfg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yonumen.top/Article/details/gtqdtdqvqv.html

[Q14] 存在则更新（upsert）
来源：http://dali.jlsjyb.cn/Article/details/gtgqrytvhp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhiwuduotai.top/Article/details/gtmuolnypg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.wangdashe.top/Article/details/gtlkrztmfe.html

[Q15] 查询全部
来源：http://dali.bjfxy.top/Article/details/gtqntfqjjd.html

SELECT * FROM users;
来源：http://dali.pycfn.com/Article/details/gtempagmcx.html

[Q16] 查询指定列
来源：http://dali.redwolf501.top/Article/details/gtowslliui.html

SELECT id, name FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtxhnacgpl.html

[Q17] 条件查询
来源：http://dali.zhongyouzk.top/Article/details/gtrrdhinex.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.dashuyun.cn/Article/details/gtiqekeryz.html

[Q18] 模糊匹配
来源：http://dali.kuanghao11.cn/Article/details/gtonrxwrxr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ybcxt.top/Article/details/gtdlfnxjbd.html

[Q19] 范围查询
来源：http://dali.jlsjyb.cn/Article/details/gtyoirgqsj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuanzhike.top/Article/details/gtafosdinr.html

[Q20] IN 列表
来源：http://dali.shuidangran.top/Article/details/gtfnaqjzbw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.redwolf501.top/Article/details/gtfcyphdtq.html

[Q21] 空值判断
来源：http://dali.jlsjyb.cn/Article/details/gtlcujlvmb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhixingplan.top/Article/details/gtyukndfca.html

[Q22] 排序
来源：http://dali.mhx1999.top/Article/details/gtubcbjebo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gotoacloud.top/Article/details/gtcfkezaqi.html

[Q23] 分页
来源：http://dali.haohaochexian.top/Article/details/gtgahufcta.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfxqvgyn.html

[Q24] 去重
来源：http://dali.yvedp.cn/Article/details/gtpiwtptvh.html

SELECT DISTINCT city FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtrcyiacwo.html

[Q25] 只取前 N 条
来源：http://dali.andypj.xyz/Article/details/gtlikrqalt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yonumen.top/Article/details/gtmuiafdfi.html

[Q26] 计数
来源：http://dali.quarkkingdee.top/Article/details/gtwcnkxkcg.html

SELECT COUNT(*) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtmemgitsj.html

[Q27] 条件计数
来源：http://dali.daxiang520.top/Article/details/gtxyfnwxzq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtogmpfonx.html

[Q28] 求和与平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwptvyeiy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtonqqbgax.html

[Q29] 最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gtfhenfuzr.html


<!-- 参考信息 -->