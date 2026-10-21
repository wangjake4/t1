代发 wailian999

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258888.top/Article/details/gtmatgvimo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gtbpnkaemy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.redwolf501.top/Article/details/gtxjlrhhtw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guannengcc.top/Article/details/gtkzcffkpm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhoulong.xyz/Article/details/gtgtbxktcn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zdqjudy.top/Article/details/gteqxtwjmq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenzaomai.com/Article/details/gtihxfprqr.html

[N04] 斐波那契数列
来源：http://dali.yuxming.cn/Article/details/gtdevraytn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtptkelgxn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zycfv.cn/Article/details/gtoymmyixv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtvxxsampx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gtrcugktle.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gtmdcjeify.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnxiangtu.top/Article/details/gtfkbossaa.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gthczqeyjj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gtsyxgmdut.html

[N05] 最大公约数
来源：http://dali.tianlin.xyz/Article/details/gtwrkarqfo.html

Py:   math.gcd(a, b)
来源：http://dali.sxryk.cn/Article/details/gtoabzpjtr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tian-w.cn/Article/details/gtploxrecz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gtuavumxvc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.quarkkingdee.top/Article/details/gtpbwgdzrd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfljwtygb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthyfwpdm.html

Ruby: a.gcd(b)
来源：http://dali.ehwqpu.com/Article/details/gtzobfbuph.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhixingplan.top/Article/details/gtmlmheusk.html

[N06] 判断回文字符串
来源：http://dali.tanke756.top/Article/details/gtylosfzps.html

Py:   s == s[::-1]
来源：http://dali.aibaodan.cn/Article/details/gtpgpyyiqi.html

PHP:  $s === strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gtfqurxpyr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtappdutia.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtblmiarom.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnxiangtu.top/Article/details/gtengqotse.html

Go:   // 双指针从两端比较
来源：http://dali.birdmap.top/Article/details/gtwlyxnwfh.html

Ruby: s == s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gtkqkpqedw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gtzuyyxstf.html

[N07] 两数之和（返回下标）
来源：http://dali.ybcxt.top/Article/details/gtlpniqwlu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cdnleiting.top/Article/details/gtpjeetbld.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.daria6918.cn/Article/details/gtgfrlruis.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnqzz.top/Article/details/gtxdumcrgm.html

TS:   // 手写 Map<string, number>
来源：http://dali.svipenyu.cn/Article/details/gthbqaqwsg.html

Java: // 手写 HashMap
来源：http://dali.cashguo.top/Article/details/gtwridyxgf.html

Go:   // 手写 map[int]int
来源：http://dali.wangshuangyany.cn/Article/details/gtfbwlezda.html

Ruby: // 手写 Hash
来源：http://dali.hongshengwenyu.top/Article/details/gtnthijpwx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangtech.top/Article/details/gthmarprxm.html

[N08] 生成全排列
来源：http://dali.jiagoushi.top/Article/details/gtbhjahcrd.html

Py:   itertools.permutations(arr)
来源：http://dali.guowangkeji.top/Article/details/gtxhmhmled.html

PHP:  // 手写递归交换
来源：http://dali.hysaishi.cn/Article/details/gtartiobhx.html

JS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtwiyhzwgt.html

TS:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtnghqpxlc.html

Java: // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gthswynkky.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gthlnysfnh.html

Ruby: arr.permutation.to_a
来源：http://dali.pycfn.com/Article/details/gtbgkhvhzn.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtqygtuxxf.html

[N09] 栈与队列
来源：http://dali.hysaishi.cn/Article/details/gtdqpihstv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fengsongda.top/Article/details/gtljnakmel.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.316326.xyz/Article/details/gtkxwcbsis.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gtcvtdmsvw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.haohaochexian.top/Article/details/gtveaphjdu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gthaerbdrv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.vqdsnc.cn/Article/details/gtruhffdrh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtfoehydrg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sxryk.cn/Article/details/gtkptedtsk.html

[N10] 链表节点定义
来源：http://dali.jianghu66.top/Article/details/gtqitbydgy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tanke756.top/Article/details/gtcdzibwlw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj202588.top/Article/details/gtvrhtghdl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guowangkeji.top/Article/details/gthqvrftxo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ybcxt.top/Article/details/gtyvoufoyl.html

Java: class Node { int v; Node next; }
来源：http://dali.wangdashe.top/Article/details/gtvlmfvygs.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinghuilouyu.cn/Article/details/gttbrotqtf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hfpthk.cn/Article/details/gtplisipbx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sysykeji.top/Article/details/gtafighuhe.html

[N11] 二叉树中序遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtnwqodepe.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ehwqpu.com/Article/details/gtfcrowtwn.html

PHP:  // 手写递归函数
来源：http://dali.iojbl.cn/Article/details/gtyrkclkid.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkbxqchet.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gtdyimwwoj.html

Java: // 手写递归
来源：http://dali.yj20258.top/Article/details/gtfjsvcczw.html

Go:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gttsadoagq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtblqrcfuq.html

C#:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gtmampmglx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.snrcjt.cn/Article/details/gtzajpbemf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.pycfn.com/Article/details/gthcuekpcj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.iojbl.cn/Article/details/gtjnayufle.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gtwuwezkss.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gttspayyxd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gtpjaqpnqh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zdqjudy.top/Article/details/gthpfzlqhd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.316326.xyz/Article/details/gtjijgaizf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gtsknfhymv.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtvkfpbhjv.html

O. 并发与异步
来源：http://dali.hywenlv.cn/Article/details/gtwmpfbics.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtjqjpjwha.html

[O01] 启动一个线程
来源：http://dali.bjfxy.top/Article/details/gtzllqpvwq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shzxlz.cn/Article/details/gtjlmqvdel.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.0kj1m.cn/Article/details/gttsirfhen.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sufxvd.cn/Article/details/gtievnvhze.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gthyybzvdz.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcccskvto.html

Go:   go f()
来源：http://dali.aibaodan.cn/Article/details/gtrbzdkkgy.html

Ruby: Thread.new { f }
来源：http://dali.iojbl.cn/Article/details/gtxivudueo.html

C#:   Task.Run(() => F());
来源：http://dali.jqgfzy.top/Article/details/gtnxqdhhqz.html

[O02] 使用线程池
来源：http://dali.sysykeji.top/Article/details/gtdioxlwlm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.bjfxy.top/Article/details/gtcuddhwge.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.fengsongda.top/Article/details/gtxmtczpnc.html

JS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gtvjuxhvye.html

TS:   // worker_threads 线程池
来源：http://dali.hnqzz.top/Article/details/gtjglranpb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cashguo.top/Article/details/gtyrddxnnw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.316326.xyz/Article/details/gtbipstuqw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hnqzz.top/Article/details/gtpfgkyzvq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj202588.top/Article/details/gttzgmslmc.html

[O03] 加锁保护共享数据
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsqmzkpy.html

Py:   with lock: shared += 1
来源：http://dali.c1oappe.top/Article/details/gtpwjefcew.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hywenlv.cn/Article/details/gtpjkslyrs.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.9152youxi.cn/Article/details/gtwjaagisx.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gtlkuerpln.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gtyszsxgbf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.aizwys.cn/Article/details/gtikwkpsyc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.iojbl.cn/Article/details/gtzjxwotvj.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gttrdjthtm.html

[O04] 定义异步函数并等待
来源：http://dali.yangfankeji.com/Article/details/gtjafbtjdr.html

Py:   async def f():⏎    await g()
来源：http://dali.hnxiangtu.top/Article/details/gtfepyfbre.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hfpthk.cn/Article/details/gtkfpntyhz.html

JS:   async function f() { await g(); }
来源：http://dali.daria6918.cn/Article/details/gtnftziizm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gtbupivnkx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shuidangran.top/Article/details/gtxlaevlcp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sufxvd.cn/Article/details/gtgkwkhlge.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhoulong.xyz/Article/details/gtpoaxdgog.html

C#:   async Task F() { await G(); }
来源：http://dali.ppjwa.cn/Article/details/gtknplejru.html

[O05] 并发执行并等待全部完成
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpfnbdsl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhongyouzk.top/Article/details/gtmgftunyd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.smart0.xyz/Article/details/gtgwcboyfs.html

JS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtmdnqbpcj.html

TS:   await Promise.all(tasks)
来源：http://dali.xziqi.cn/Article/details/gtpdzobmfo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ybcxt.top/Article/details/gtorxwuzyh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.svipenyu.cn/Article/details/gtlakecuoc.html

Ruby: threads.map(&:join)
来源：http://dali.aizwys.cn/Article/details/gtlpfddibx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hammf.cn/Article/details/gtgrltzdsc.html

[O06] 使用进程池
来源：http://dali.xziqi.cn/Article/details/gtklgzxylu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangdashe.top/Article/details/gtuggjgirc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cdnleiting.top/Article/details/gtayhyovvv.html

JS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gtyadidcai.html

TS:   // child_process / cluster 模块
来源：http://dali.redwolf501.top/Article/details/gtyhsiycyn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.svipenyu.cn/Article/details/gtvdpqogmm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenlongwang.top/Article/details/gtxkxesvcj.html

Ruby: // fork 块
来源：http://dali.yvedp.cn/Article/details/gtjrhvjlhk.html

C#:   Parallel.For
来源：http://dali.yuxming.cn/Article/details/gtoxrxkfbv.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtkwjhetvd.html

P. 常用工具函数
来源：http://dali.yongpay.top/Article/details/gtzbowzila.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtitqhxwvm.html

[P01] 生成 UUID
来源：http://dali.yj202588.top/Article/details/gtjvepiqhx.html

Py:   str(uuid.uuid4())
来源：http://dali.wangshuangyany.cn/Article/details/gtguooqmfl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzuqjbtj.html

JS:   crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gtpfnsdxop.html

TS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtyiycepao.html

Java: UUID.randomUUID().toString()
来源：http://dali.jlsjyb.cn/Article/details/gthaurheds.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinqigfzy.top/Article/details/gtctgoprxy.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258.top/Article/details/gtntmbwjjm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sysykeji.top/Article/details/gtwrutlxus.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnqzz.top/Article/details/gtikrplcoy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.guannengcc.top/Article/details/gtcehdausa.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenzaomai.com/Article/details/gtorpmxpmz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cdnleiting.top/Article/details/gtyxouektd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aibaodan.cn/Article/details/gtoxkuswrp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gthrjmamzi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gzhubu.top/Article/details/gtlkislmiv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.0kj1m.cn/Article/details/gtdyngrvzn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jiagoushi.top/Article/details/gtjjqnimfx.html

[P03] 生成短随机字符串
来源：http://dali.jinqigfzy.top/Article/details/gtzpnhuhcs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhixingplan.top/Article/details/gtzcatjwpd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinqigfzy.top/Article/details/gtkxsyunmg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghabvxzd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cqqwz.cn/Article/details/gtukpxfmkb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gotoacloud.top/Article/details/gtcuiksnkl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hammf.cn/Article/details/gtnyrnxuso.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jlsjyb.cn/Article/details/gtybsxbyil.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.smart0.xyz/Article/details/gtbynizwvk.html

[P04] 求长度
来源：http://dali.hywenlv.cn/Article/details/gtudkaxxkh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.haohaochexian.top/Article/details/gtdmnulgpi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gttgofotqf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtludzvhek.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tian-w.cn/Article/details/gtnydbedfo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenjidiqi.icu/Article/details/gttrzrcgps.html

Go:   len(arr);  len(m)
来源：http://dali.gotoacloud.top/Article/details/gtwjkwumzv.html

Ruby: x.length;  x.size
来源：http://dali.pengpengdd.cyou/Article/details/gtecemtcca.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jqgufenzy.top/Article/details/gtgyizgmhu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sweek.top/Article/details/gtnehcshfy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenzaomai.com/Article/details/gtdreqwwzz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.iojbl.cn/Article/details/gtsaezaznn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yonumen.top/Article/details/gtkkrnzpbn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxinkj.top/Article/details/gtbcuqumzs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pengpengdd.cyou/Article/details/gtxtthdmyr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtlahuzehx.html

Ruby: a == b
来源：http://dali.tian-w.cn/Article/details/gtabhealgp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.c1oappe.top/Article/details/gtlugknzgj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cashguo.top/Article/details/gthubrfgep.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nwbrower.top/Article/details/gtehvgjvnb.html

PHP:  if (empty($x)) {}
来源：http://dali.hfpthk.cn/Article/details/gtwzbhstvy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cdnleiting.top/Article/details/gtjqrbltzl.html

TS:   if (x == null) {}
来源：http://dali.cheryme.top/Article/details/gtudytjqan.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gtzgfdnpaf.html

Go:   if x == nil {}
来源：http://dali.dashuyun.cn/Article/details/gtuybefomj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yvedp.cn/Article/details/gtdjvuiawm.html

C#:   if (x is null) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtteyjbcou.html

[P07] 防抖与节流
来源：http://dali.yj20258888.top/Article/details/gtskcmhjsw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.0kj1m.cn/Article/details/gthlqblvfb.html

PHP:  // 手写时间戳比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrmitzww.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gtgksmnlre.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gtsjzqsawp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hammf.cn/Article/details/gtvfrqgzap.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenlongwang.top/Article/details/gttjwxhdgw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ivvv.top/Article/details/gtnrxvisby.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cqqwz.cn/Article/details/gtpfzetyxz.html

[P08] 处理浮点精度问题
来源：http://dali.cqqwz.cn/Article/details/gttzjwmvyu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhiwuduotai.top/Article/details/gtyxzsrihu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjitrnxzp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.meibo888.top/Article/details/gtkfeeuzaa.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cdnleiting.top/Article/details/gtcbrobtnz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gtqdcavast.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.pycfn.com/Article/details/gtswyankqe.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.guowangkeji.top/Article/details/gtynahnxtr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yanxiufei.cn/Article/details/gtafgzkmza.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtafdfmxbq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jiagoushi.top/Article/details/gtjjllxvxl.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtonfodpon.html

[Q01] 创建表
来源：http://dali.shangyingyoupin.top/Article/details/gtxxihjrqf.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gtxreekffl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gtwbvmmyyz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258.top/Article/details/gtsgmvltah.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yueranfly.top/Article/details/gtfaexgurd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pycfn.com/Article/details/gtvqjodcec.html

);
来源：http://dali.snrcjt.cn/Article/details/gtmqttzkim.html

[Q02] 创建带外键的表
来源：http://dali.yongpay.top/Article/details/gttbuaiqan.html

CREATE TABLE orders (
来源：http://dali.nwbrower.top/Article/details/gtvzqfofum.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xziqi.cn/Article/details/gtlniubzey.html

user_id INT NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gtvermqynr.html

amount DECIMAL(10, 2),
来源：http://dali.chenzaomai.com/Article/details/gtubccanim.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuanzx.com/Article/details/gtcvadzvtw.html

);
来源：http://dali.sysykeji.top/Article/details/gtkmgubfgc.html

[Q03] 增加列
来源：http://dali.sysykeji.top/Article/details/gtfwltiwlg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hnqzz.top/Article/details/gtaercoyeg.html

[Q04] 修改列类型
来源：http://dali.hnxiangtu.top/Article/details/gtqkmcnjfc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258.top/Article/details/gtweifhmvl.html

[Q05] 重命名列
来源：http://dali.meibo888.top/Article/details/gtzlkrwfra.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dashuyun.cn/Article/details/gtonyltnra.html

[Q06] 删除列
来源：http://dali.yangfankeji.com/Article/details/gtnivbrsfe.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.daxiang520.top/Article/details/gtifvmiwmc.html

[Q07] 删除表
来源：http://dali.daria6918.cn/Article/details/gtjvxsteic.html

DROP TABLE IF EXISTS orders;
来源：http://dali.redwolf501.top/Article/details/gttqvsduam.html

[Q08] 创建普通索引
来源：http://dali.hfpthk.cn/Article/details/gtvwyfajlv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tian-w.cn/Article/details/gtkrjswvvx.html

[Q09] 创建唯一索引
来源：http://dali.jiagoushi.top/Article/details/gtbsuiaaoo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gttnkweynq.html

[Q10] 插入单行
来源：http://dali.zhixingplan.top/Article/details/gttgvffajk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtfnjdzvfp.html

[Q11] 一次插入多行
来源：http://dali.ehwqpu.com/Article/details/gtiiapyckw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xziqi.cn/Article/details/gteaviwrwi.html

[Q12] 插入后取自增 ID
来源：http://dali.zhixingplan.top/Article/details/gtzbfseitm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenjidiqi.icu/Article/details/gtxcmlgich.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenzaomai.com/Article/details/gthfoiuccj.html

[Q13] 忽略重复插入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgvouegw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadqjctot.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnxiangtu.top/Article/details/gtoyeykfts.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aizwys.cn/Article/details/gtatclouwg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gaohongyu789.top/Article/details/gtlnswykps.html

[Q15] 查询全部
来源：http://dali.snrcjt.cn/Article/details/gtsgviuqtm.html

SELECT * FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gteshdhpzo.html

[Q16] 查询指定列
来源：http://dali.yvedp.cn/Article/details/gtfzdosbvd.html

SELECT id, name FROM users;
来源：http://dali.ydzc1.top/Article/details/gtfxlznqso.html

[Q17] 条件查询
来源：http://dali.dashuyun.cn/Article/details/gtqqqjgacd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuanzhike.top/Article/details/gtsvanaxzu.html

[Q18] 模糊匹配
来源：http://dali.aizwys.cn/Article/details/gtrvbnciyh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.dashuyun.cn/Article/details/gteusssscs.html

[Q19] 范围查询
来源：http://dali.zhoulong.xyz/Article/details/gtzihcvnfj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.mhx1999.top/Article/details/gtcnmadrul.html

[Q20] IN 列表
来源：http://dali.jqgfzy.top/Article/details/gtumsjdyvr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.svipenyu.cn/Article/details/gtzznymvrh.html

[Q21] 空值判断
来源：http://dali.xuanzx.com/Article/details/gttybngclh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ehwqpu.com/Article/details/gtlkcuiipa.html

[Q22] 排序
来源：http://dali.9152youxi.cn/Article/details/gtvcjpzunc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.pycfn.com/Article/details/gtesomorus.html

[Q23] 分页
来源：http://dali.chenjidiqi.icu/Article/details/gtafuvcwnx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jyoumei.cn/Article/details/gtzxzomqgl.html

[Q24] 去重
来源：http://dali.cdnleiting.top/Article/details/gtpingmzcl.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gthetvyrcj.html

[Q25] 只取前 N 条
来源：http://dali.cashguo.top/Article/details/gtzavunrsh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.andypj.xyz/Article/details/gttizbnnzf.html

[Q26] 计数
来源：http://dali.daria6918.cn/Article/details/gtcvqbariz.html

SELECT COUNT(*) FROM users;
来源：http://dali.daria6918.cn/Article/details/gthzzwfntd.html

[Q27] 条件计数
来源：http://dali.birdmap.top/Article/details/gtdylpfhkw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gteulsoipa.html

[Q28] 求和与平均
来源：http://dali.meibo888.top/Article/details/gtrbrccgoq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtwxmiyehu.html

[Q29] 最大最小值
来源：http://dali.daria6918.cn/Article/details/gtpfukmvpm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gthwegyuvy.html

[Q30] 分组统计
来源：http://dali.gaohongyu789.top/Article/details/gtjnkbhzvz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtqqnlufmv.html

[Q31] 分组后过滤
来源：http://dali.birdmap.top/Article/details/gtebnryflb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdrlaocc.html

[Q32] 分组拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtyjknzlds.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtnkbilvnr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jiagoushi.top/Article/details/gtavojqfwz.html


<!-- 参考信息 -->