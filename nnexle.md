代发 wailian999

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gtaecwclds.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cdnleiting.top/Article/details/gtmzlrsdub.html

[N03] 快速排序（分治示例）
来源：http://dali.zdqjudy.top/Article/details/gtqnqwilvh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nanxinkj.top/Article/details/gtbqgvrbqm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgeperfb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guowangkeji.top/Article/details/gtiugohczc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gtwrcovxzs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.andypj.xyz/Article/details/gtfulycoar.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhoulong.xyz/Article/details/gthbhlvrkp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cucudq.cn/Article/details/gthhwwbzqg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xuanzx.com/Article/details/gtxdrmdclc.html

[N04] 斐波那契数列
来源：http://dali.chenzaomai.com/Article/details/gtcnksykny.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gtuhpmoxzi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gthftnjaph.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtfaeartxl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtytxeybrp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sysykeji.top/Article/details/gtdpmaayff.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guowangkeji.top/Article/details/gtiywbkwnt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtkeszwfsu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwsmtxcr.html

[N05] 最大公约数
来源：http://dali.pycfn.com/Article/details/gtusggqnrw.html

Py:   math.gcd(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gtiyefkxzd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfqvljft.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pycfn.com/Article/details/gtnbvmvjcb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gthbhxshec.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hywenlv.cn/Article/details/gtpbtkgebu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sxryk.cn/Article/details/gtthcmdwta.html

Ruby: a.gcd(b)
来源：http://dali.yuxming.cn/Article/details/gtgvyahzik.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.haohaochexian.top/Article/details/gtabeuyuod.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnczufcxf.html

Py:   s == s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gtkprlcjxw.html

PHP:  $s === strrev($s);
来源：http://dali.c1oappe.top/Article/details/gtwmnjtsmi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtycpzhgad.html

TS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtumkjqisn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hysaishi.cn/Article/details/gtnkqtpkas.html

Go:   // 双指针从两端比较
来源：http://dali.dashuyun.cn/Article/details/gtiwnxliin.html

Ruby: s == s.reverse
来源：http://dali.zhixingplan.top/Article/details/gtyqrkqrtv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gtpmwjuchh.html

[N07] 两数之和（返回下标）
来源：http://dali.cdnleiting.top/Article/details/gtyldwbnzj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jiagoushi.top/Article/details/gttjgsukjl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jyoumei.cn/Article/details/gtsdfsiuhs.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sysykeji.top/Article/details/gtffftdhpc.html

TS:   // 手写 Map<string, number>
来源：http://dali.iojbl.cn/Article/details/gtcnixuefq.html

Java: // 手写 HashMap
来源：http://dali.sysykeji.top/Article/details/gtfknkbsbb.html

Go:   // 手写 map[int]int
来源：http://dali.cashguo.top/Article/details/gtlgcaxqxz.html

Ruby: // 手写 Hash
来源：http://dali.gaohongyu789.top/Article/details/gtctburboz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sweek.top/Article/details/gtkmvokbku.html

[N08] 生成全排列
来源：http://dali.xziqi.cn/Article/details/gtvikeuplk.html

Py:   itertools.permutations(arr)
来源：http://dali.jiagoushi.top/Article/details/gtwcynzrrf.html

PHP:  // 手写递归交换
来源：http://dali.jinghuilouyu.cn/Article/details/gttirkosqp.html

JS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtypswatgh.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtrbnsyktl.html

Java: // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtskyyplde.html

Go:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtdituulfk.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gtkamfewib.html

C#:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtvnlvokhe.html

[N09] 栈与队列
来源：http://dali.cucudq.cn/Article/details/gtrdzekwyu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hammf.cn/Article/details/gtcwdijrdp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gtnmbfjupu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqrlcjma.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuanzx.com/Article/details/gtdzcbpqfi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aizwys.cn/Article/details/gtiehviocy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yuanzhike.top/Article/details/gtktvchooy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtgclvdpif.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gtqifvwfpg.html

[N10] 链表节点定义
来源：http://dali.xziqi.cn/Article/details/gtvznzcjvl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.wangshuangyany.cn/Article/details/gtckctuxhr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ppjwa.cn/Article/details/gtfhawuwdn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.pycfn.com/Article/details/gtimsacwuu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangdashe.top/Article/details/gtnejykqyf.html

Java: class Node { int v; Node next; }
来源：http://dali.ppjwa.cn/Article/details/gtcmyupgig.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sweek.top/Article/details/gtcpwpcyeg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ybcxt.top/Article/details/gtpewtfuor.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinqigfzy.top/Article/details/gteskooshb.html

[N11] 二叉树中序遍历
来源：http://dali.zhixingplan.top/Article/details/gtpibuwhxr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zdqjudy.top/Article/details/gtdftuvxmh.html

PHP:  // 手写递归函数
来源：http://dali.zycfv.cn/Article/details/gtgbczvwwg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenlongwang.top/Article/details/gtjvnshibr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gtrzipwbjs.html

Java: // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtfugqphds.html

Go:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtvtudhwrg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.birdmap.top/Article/details/gthqllboem.html

C#:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gttibpjqdc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhongyouzk.top/Article/details/gtxpinytqn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daxiang520.top/Article/details/gtvbdyxepy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jiagoushi.top/Article/details/gtfgzowvsq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gtwzfxturu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gtcaiiogqz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gtkklggpmr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hongshengwenyu.top/Article/details/gtiwnwbfuy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shuidangran.top/Article/details/gtfpoyxpkv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.smart0.xyz/Article/details/gtdwlwjygh.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtpezcamri.html

O. 并发与异步
来源：http://dali.haohaochexian.top/Article/details/gtodfgjgda.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtnqmdzprj.html

[O01] 启动一个线程
来源：http://dali.fzhhl.top/Article/details/gtootgfsep.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jianghu66.top/Article/details/gtowdadsdc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnqzz.top/Article/details/gtrnsyjcmv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.birdmap.top/Article/details/gtfgpgcdik.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gtuxtwslao.html

Java: new Thread(() -> f()).start()
来源：http://dali.jiagoushi.top/Article/details/gtjhnbttcf.html

Go:   go f()
来源：http://dali.quarkkingdee.top/Article/details/gtkxstbqli.html

Ruby: Thread.new { f }
来源：http://dali.hnxiangtu.top/Article/details/gtynkcfrph.html

C#:   Task.Run(() => F());
来源：http://dali.0kj1m.cn/Article/details/gtposcoodm.html

[O02] 使用线程池
来源：http://dali.zhoulong.xyz/Article/details/gtpwdknuaf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hongshengwenyu.top/Article/details/gtowxlzucs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aibaodan.cn/Article/details/gtcqvkzwpw.html

JS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gtarixgese.html

TS:   // worker_threads 线程池
来源：http://dali.zdqjudy.top/Article/details/gtfikutnhd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.snrcjt.cn/Article/details/gtgqqvjtcy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hammf.cn/Article/details/gtjminpkcd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sxryk.cn/Article/details/gtzudibyxv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cashguo.top/Article/details/gtffntuzdw.html

[O03] 加锁保护共享数据
来源：http://dali.shanyushiyangtech.top/Article/details/gthyeyugyd.html

Py:   with lock: shared += 1
来源：http://dali.aibaodan.cn/Article/details/gtgpqzkhtr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jlsjyb.cn/Article/details/gtlzhexxdg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xuetiantiany.cn/Article/details/gtcqxrkcev.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gtnxxnshfa.html

Java: synchronized (this) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gtiobhtxju.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.haohaochexian.top/Article/details/gtftibjrmy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.quarkkingdee.top/Article/details/gtueceqbml.html

C#:   lock (gate) { shared++; }
来源：http://dali.pycfn.com/Article/details/gtgikbrgff.html

[O04] 定义异步函数并等待
来源：http://dali.hnxiangtu.top/Article/details/gtqrvyrafc.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigufen.top/Article/details/gtbswbcuvh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gogol.net.cn/Article/details/gtfrcxhctj.html

JS:   async function f() { await g(); }
来源：http://dali.ehwqpu.com/Article/details/gtityohutb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtwerokcvu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gaohongyu789.top/Article/details/gtluplngbj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ydzc1.top/Article/details/gttmdbgeff.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.kuanghao11.cn/Article/details/gtfzciyomq.html

C#:   async Task F() { await G(); }
来源：http://dali.chenlongwang.top/Article/details/gtobmwsart.html

[O05] 并发执行并等待全部完成
来源：http://dali.svipenyu.cn/Article/details/gtomjzzhul.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cdnleiting.top/Article/details/gtrizwsblh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shangyingyoupin.top/Article/details/gttfmmeqir.html

JS:   await Promise.all(tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gtuctbqgxu.html

TS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gtliwufwmz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.andypj.xyz/Article/details/gteqliryjb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.feifeiyinyue.top/Article/details/gtbxuxouxt.html

Ruby: threads.map(&:join)
来源：http://dali.hammf.cn/Article/details/gtecptpqjl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xziqi.cn/Article/details/gtlctqhrua.html

[O06] 使用进程池
来源：http://dali.jinqigfzy.top/Article/details/gtlywwbkur.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jlsjyb.cn/Article/details/gtvebnnlft.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenzaomai.com/Article/details/gtxljetgbs.html

JS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gtumwtrsdn.html

TS:   // child_process / cluster 模块
来源：http://dali.andypj.xyz/Article/details/gtptlefwys.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawnvjdsh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.pengpengdd.cyou/Article/details/gteuuzblqz.html

Ruby: // fork 块
来源：http://dali.9152youxi.cn/Article/details/gtckjfcphr.html

C#:   Parallel.For
来源：http://dali.bjfxy.top/Article/details/gtcmnsenki.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtchhfganr.html

P. 常用工具函数
来源：http://dali.xylfe.cn/Article/details/gtkgwtbggr.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtaotlojpo.html

[P01] 生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gtkwlnjxnf.html

Py:   str(uuid.uuid4())
来源：http://dali.hammf.cn/Article/details/gtxzrcfrgp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gttrmpytmb.html

JS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtshmfpnvr.html

TS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqkokriu.html

Java: UUID.randomUUID().toString()
来源：http://dali.guowangkeji.top/Article/details/gtpfdbzbjc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtctslokvu.html

Ruby: SecureRandom.uuid
来源：http://dali.c1oappe.top/Article/details/gtypgxiksc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.mhx1999.top/Article/details/gtzvwecjjg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yvedp.cn/Article/details/gtznffmyni.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xylfe.cn/Article/details/gtpsksymae.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhoulong.xyz/Article/details/gtnpzzhiyr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gzhubu.top/Article/details/gtewizhugp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sysykeji.top/Article/details/gtojzrjgbk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.redwolf501.top/Article/details/gtgcygzpxx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.feifeiyinyue.top/Article/details/gtzefyirkd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbecvaef.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigufen.top/Article/details/gtvjoyrcbx.html

[P03] 生成短随机字符串
来源：http://dali.aizwys.cn/Article/details/gtufvfbyqd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jqgufenzy.top/Article/details/gtlplfvoxv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhixingplan.top/Article/details/gtxvmjjffv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gtoertvnxe.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gzhubu.top/Article/details/gtluydxpqo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtfznsgupp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.bjfxy.top/Article/details/gtwddfcoty.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnqzz.top/Article/details/gtxqngnoei.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hammf.cn/Article/details/gtumojlxpi.html

[P04] 求长度
来源：http://dali.pycfn.com/Article/details/gtkbtkrdnh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhengqikj.top/Article/details/gtpqahalqv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtdqdxifkk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fengsongda.top/Article/details/gtvmcznjcx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gtjpwbilhx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ybcxt.top/Article/details/gtzuqthafr.html

Go:   len(arr);  len(m)
来源：http://dali.svipenyu.cn/Article/details/gtlvytrfak.html

Ruby: x.length;  x.size
来源：http://dali.yj20258.top/Article/details/gtnmpjqjnh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nwbrower.top/Article/details/gtqfhamalh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sysykeji.top/Article/details/gtmypjynxl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yuxming.cn/Article/details/gtblioaoxc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenlongwang.top/Article/details/gtxkqmobkc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cashguo.top/Article/details/gtjggprzkm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtuwdwafar.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinqigfzy.top/Article/details/gtxcbnhgnk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zycfv.cn/Article/details/gtylufgkzn.html

Ruby: a == b
来源：http://dali.guowangkeji.top/Article/details/gtazphsjsq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnqzz.top/Article/details/gtxswtusgs.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.kuanghao11.cn/Article/details/gtdjyuddch.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xuanzx.com/Article/details/gtfbnqiyyz.html

PHP:  if (empty($x)) {}
来源：http://dali.wangdashe.top/Article/details/gtwgwyimpw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jyoumei.cn/Article/details/gtbvirrzzk.html

TS:   if (x == null) {}
来源：http://dali.0kj1m.cn/Article/details/gtdwhdlagu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtthojprld.html

Go:   if x == nil {}
来源：http://dali.zdqjudy.top/Article/details/gtzzpswygj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jqgufenzy.top/Article/details/gtccogienz.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gttlurwdcq.html

[P07] 防抖与节流
来源：http://dali.zhiwuduotai.top/Article/details/gtnchbfoxd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.iojbl.cn/Article/details/gtmfevzpan.html

PHP:  // 手写时间戳比较
来源：http://dali.aibaodan.cn/Article/details/gtpxaohhdd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gtvrtrafez.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigfzy.top/Article/details/gtfrdhskee.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258.top/Article/details/gtinupakth.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cucudq.cn/Article/details/gtknvkpdnt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gthspmxqtt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nwbrower.top/Article/details/gtohbbnant.html

[P08] 处理浮点精度问题
来源：http://dali.birdmap.top/Article/details/gtvgsemorc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cucudq.cn/Article/details/gtrrkxasyy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tian-w.cn/Article/details/gtakisbocg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fzhhl.top/Article/details/gtbbfinpei.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xylfe.cn/Article/details/gtpnfxoomu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jiagoushi.top/Article/details/gtqjmvhkon.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sufxvd.cn/Article/details/gtxxamssjx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigfzy.top/Article/details/gtltuiqiqa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.vqdsnc.cn/Article/details/gtxadqfdnz.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtyluikpmq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.meibo888.top/Article/details/gtguytiuto.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtdsffwwak.html

[Q01] 创建表
来源：http://dali.fengsongda.top/Article/details/gthjduouoy.html

CREATE TABLE users (
来源：http://dali.aizwys.cn/Article/details/gtbrnqqvbg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gttxnwymfi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gtpidrtmey.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigfzy.top/Article/details/gtcawtgqbi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gaohongyu789.top/Article/details/gtbcvxsgud.html

);
来源：http://dali.fengsongda.top/Article/details/gtdokpqieq.html

[Q02] 创建带外键的表
来源：http://dali.xylfe.cn/Article/details/gtzeepvnyr.html

CREATE TABLE orders (
来源：http://dali.gogol.net.cn/Article/details/gtroaufiqn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxinkj.top/Article/details/gtonbaznpp.html

user_id INT NOT NULL,
来源：http://dali.hysaishi.cn/Article/details/gthdvqldyd.html

amount DECIMAL(10, 2),
来源：http://dali.iojbl.cn/Article/details/gtxyzqevji.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxinkj.top/Article/details/gtfcldusis.html

);
来源：http://dali.gaohongyu789.top/Article/details/gtefuvxfqr.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gtlffkuiyl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkluddsdl.html

[Q04] 修改列类型
来源：http://dali.mhx1999.top/Article/details/gtsvzkqusj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmcxuwmt.html

[Q05] 重命名列
来源：http://dali.ivvv.top/Article/details/gtjksyeuof.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zdqjudy.top/Article/details/gtmvjlxbcr.html

[Q06] 删除列
来源：http://dali.daxiang520.top/Article/details/gtwpquogcc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.iojbl.cn/Article/details/gtvwxaisjs.html

[Q07] 删除表
来源：http://dali.fengsongda.top/Article/details/gtyvpxfcuq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xylfe.cn/Article/details/gtnjpxinoj.html

[Q08] 创建普通索引
来源：http://dali.cucudq.cn/Article/details/gtuhiwygtp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gtudnhxrzc.html

[Q09] 创建唯一索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrndrvgor.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yueranfly.top/Article/details/gtxasbtdee.html

[Q10] 插入单行
来源：http://dali.birdmap.top/Article/details/gtnmwgehoo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.daxiang520.top/Article/details/gtaroudtib.html

[Q11] 一次插入多行
来源：http://dali.jinqigufen.top/Article/details/gtzzofjcgp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtztlailbq.html

[Q12] 插入后取自增 ID
来源：http://dali.pengpengdd.cyou/Article/details/gtfbdbajfd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenlongwang.top/Article/details/gtvkedbrll.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xuanzx.com/Article/details/gtaypdajzb.html

[Q13] 忽略重复插入
来源：http://dali.cqqwz.cn/Article/details/gtgtetmudk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cheryme.top/Article/details/gttumvtrsx.html

[Q14] 存在则更新（upsert）
来源：http://dali.smart0.xyz/Article/details/gtzczxefbx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zdqjudy.top/Article/details/gtcucuvebj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xinyue.icu/Article/details/gtxhgjffly.html

[Q15] 查询全部
来源：http://dali.zhoulong.xyz/Article/details/gtirahatca.html

SELECT * FROM users;
来源：http://dali.daria6918.cn/Article/details/gtdaiujzdy.html

[Q16] 查询指定列
来源：http://dali.iojbl.cn/Article/details/gtbrvllmhx.html

SELECT id, name FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtbfwttwpe.html

[Q17] 条件查询
来源：http://dali.yuanzhike.top/Article/details/gtgxhgaklr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hammf.cn/Article/details/gtzhpwytsw.html

[Q18] 模糊匹配
来源：http://dali.zycfv.cn/Article/details/gteijovmxb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenlongwang.top/Article/details/gtkfobrzle.html

[Q19] 范围查询
来源：http://dali.sufxvd.cn/Article/details/gtazklcvqx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xinyue.icu/Article/details/gttgvuutqk.html

[Q20] IN 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzemnzsw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj20258.top/Article/details/gthvptlczp.html

[Q21] 空值判断
来源：http://dali.aibaodan.cn/Article/details/gtutzvzjdi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jqgufenzy.top/Article/details/gtdurrfpxo.html

[Q22] 排序
来源：http://dali.hysaishi.cn/Article/details/gtrxsixahh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hongshengwenyu.top/Article/details/gtmfrvdeyf.html

[Q23] 分页
来源：http://dali.shuidangran.top/Article/details/gtbgvzpfub.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daxiang520.top/Article/details/gtgnlbstcv.html

[Q24] 去重
来源：http://dali.daria6918.cn/Article/details/gtmrdihbns.html

SELECT DISTINCT city FROM users;
来源：http://dali.zycfv.cn/Article/details/gtxsqbeykn.html

[Q25] 只取前 N 条
来源：http://dali.sysykeji.top/Article/details/gtffmjflkg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sxryk.cn/Article/details/gtuuhrzkjq.html

[Q26] 计数
来源：http://dali.shanyushiyangtech.top/Article/details/gthjkiuqvq.html

SELECT COUNT(*) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtabeoxbxu.html

[Q27] 条件计数
来源：http://dali.birdmap.top/Article/details/gtuvufscep.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtatgvclmp.html

[Q28] 求和与平均
来源：http://dali.tanke756.top/Article/details/gtqprzuftb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtfptmxrge.html

[Q29] 最大最小值
来源：http://dali.hongshengwenyu.top/Article/details/gtcnqofuqo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghbfassn.html

[Q30] 分组统计
来源：http://dali.cheryme.top/Article/details/gtpflbslxo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gtajjbfvvk.html

[Q31] 分组后过滤
来源：http://dali.jinqigufen.top/Article/details/gtilihjvpc.html


<!-- 参考信息 -->