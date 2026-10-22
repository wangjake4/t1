代发 wailian999

PHP:  // 递归实现，或用 usort
来源：http://dali.ivvv.top/Article/details/gtuzcxpqpj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fengsongda.top/Article/details/gtxwkjfzvl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ehwqpu.com/Article/details/gtlseskhnt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ydzc1.top/Article/details/gtibfwmxki.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zdqjudy.top/Article/details/gtgqgbkyew.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yonumen.top/Article/details/gtrcldoxwa.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xinyue.icu/Article/details/gtplljhuov.html

[N04] 斐波那契数列
来源：http://dali.dashuyun.cn/Article/details/gtacxwihhk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gtsiiiwemf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sysykeji.top/Article/details/gtkbjsgpwe.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gtggtnlgfg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtjgjozuuf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj202588.top/Article/details/gtiyopefag.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.havefunace.top/Article/details/gtbjmyqxjk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwstiytt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtqeixutji.html

[N05] 最大公约数
来源：http://dali.hongshengwenyu.top/Article/details/gtgawqkclz.html

Py:   math.gcd(a, b)
来源：http://dali.gotoacloud.top/Article/details/gthflagrwm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fzhhl.top/Article/details/gtghobgbgc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gttnzkfcqw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gtohsnpvpy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.vqdsnc.cn/Article/details/gtebcrobjm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gotoacloud.top/Article/details/gtqefvfqkd.html

Ruby: a.gcd(b)
来源：http://dali.gaohongyu789.top/Article/details/gtrpduvvut.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nwbrower.top/Article/details/gtkwugpkji.html

[N06] 判断回文字符串
来源：http://dali.tanke756.top/Article/details/gtvtqnqkks.html

Py:   s == s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gtlhkmbvmi.html

PHP:  $s === strrev($s);
来源：http://dali.yongpay.top/Article/details/gtnbkxhhgd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtzcsfcozd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtieigdhmc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tian-w.cn/Article/details/gtsodrmulx.html

Go:   // 双指针从两端比较
来源：http://dali.hywenlv.cn/Article/details/gtmnealrcl.html

Ruby: s == s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtxygmfmap.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gtectqozsd.html

[N07] 两数之和（返回下标）
来源：http://dali.xuanzx.com/Article/details/gthqhwjhep.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jqgfzy.top/Article/details/gtmjfqxitt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwfxfvww.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gzhubu.top/Article/details/gthurybksg.html

TS:   // 手写 Map<string, number>
来源：http://dali.birdmap.top/Article/details/gtnqextzda.html

Java: // 手写 HashMap
来源：http://dali.xziqi.cn/Article/details/gtjavmohxo.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258888.top/Article/details/gtrqkyuwot.html

Ruby: // 手写 Hash
来源：http://dali.jqgfzy.top/Article/details/gtvsgjqtop.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zycfv.cn/Article/details/gtoosuscos.html

[N08] 生成全排列
来源：http://dali.zhaomingkeji.xyz/Article/details/gthikgblfq.html

Py:   itertools.permutations(arr)
来源：http://dali.chenlongwang.top/Article/details/gtuonrcuct.html

PHP:  // 手写递归交换
来源：http://dali.jianghu66.top/Article/details/gtoizpxxpe.html

JS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtlocmykyt.html

TS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtclyubegs.html

Java: // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtwtgggdwh.html

Go:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtfiqxkdem.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigfzy.top/Article/details/gtsvwbherl.html

C#:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtzdinizjg.html

[N09] 栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gtnrlussxg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hammf.cn/Article/details/gtuahulbcw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtknaypcur.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtzywlzlwx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jiagoushi.top/Article/details/gthpyjaqtx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xziqi.cn/Article/details/gthvltxqwi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jianghu66.top/Article/details/gtbscbhqmp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtswbpthxs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ppjwa.cn/Article/details/gtziddghnn.html

[N10] 链表节点定义
来源：http://dali.haohaochexian.top/Article/details/gtoxvotksh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenzaomai.com/Article/details/gtncdaopxn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hammf.cn/Article/details/gtudryfrtv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.vqdsnc.cn/Article/details/gtvfaffyzz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.0kj1m.cn/Article/details/gtjqvazysw.html

Java: class Node { int v; Node next; }
来源：http://dali.yuanzhike.top/Article/details/gtlubdrfcv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xziqi.cn/Article/details/gtpasbrggt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.c1oappe.top/Article/details/gtftahdkbi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yvedp.cn/Article/details/gtohakegly.html

[N11] 二叉树中序遍历
来源：http://dali.yuanzhike.top/Article/details/gtuknbiazz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ppjwa.cn/Article/details/gtyoplhpot.html

PHP:  // 手写递归函数
来源：http://dali.dashuyun.cn/Article/details/gtotzvyqcd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gtndxkdyrh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gtgycwfknq.html

Java: // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gtxihmlmia.html

Go:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtcpwonxen.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nanxinkj.top/Article/details/gtmlnvazuh.html

C#:   // 手写递归
来源：http://dali.gzhubu.top/Article/details/gtimsvwvgc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangdashe.top/Article/details/gtjvcwluos.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aizwys.cn/Article/details/gtybyuboja.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gtmmbnwjkj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gttrqptjat.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fengsongda.top/Article/details/gtmomprnrb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gtctsdulof.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xinyue.icu/Article/details/gtfwshctrb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.c1oappe.top/Article/details/gtdcgzmybv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gtordaxaeq.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwvbufhm.html

O. 并发与异步
来源：http://dali.gogol.net.cn/Article/details/gtzjtidoyp.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtpbbkmzox.html

[O01] 启动一个线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxbbrdad.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yongpay.top/Article/details/gtuckimday.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtslkcffhu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shuidangran.top/Article/details/gtaxptkpiq.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gtqjrxmocb.html

Java: new Thread(() -> f()).start()
来源：http://dali.aizwys.cn/Article/details/gtydxwpjbl.html

Go:   go f()
来源：http://dali.iojbl.cn/Article/details/gtkpvkbdlh.html

Ruby: Thread.new { f }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebzlhbod.html

C#:   Task.Run(() => F());
来源：http://dali.smart0.xyz/Article/details/gtiqbfccko.html

[O02] 使用线程池
来源：http://dali.jyoumei.cn/Article/details/gtpbnmtspf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhongyouzk.top/Article/details/gtrzuzhxbr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangtech.top/Article/details/gthgqrkohq.html

JS:   // worker_threads 线程池
来源：http://dali.sxryk.cn/Article/details/gtadecohtp.html

TS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gtuqbkazhi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xuanzx.com/Article/details/gtqsteulio.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenzaomai.com/Article/details/gtqqzuwgtm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yueranfly.top/Article/details/gtpgtgqzyf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yueranfly.top/Article/details/gtlcvgfkwg.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigufen.top/Article/details/gtqvtzixbr.html

Py:   with lock: shared += 1
来源：http://dali.0kj1m.cn/Article/details/gtsqtbfhei.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.quarkkingdee.top/Article/details/gtuytdgbbt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhixingplan.top/Article/details/gtawifwyur.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gtsuwstrep.html

Java: synchronized (this) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gttzwtbhkz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.andypj.xyz/Article/details/gtdjgowzcd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuanzhike.top/Article/details/gtzissakmv.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gteldgeqqd.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258888.top/Article/details/gtftmkwnwn.html

Py:   async def f():⏎    await g()
来源：http://dali.jyoumei.cn/Article/details/gtdztyacaj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenzaomai.com/Article/details/gtixfdtidt.html

JS:   async function f() { await g(); }
来源：http://dali.havefunace.top/Article/details/gtizdqctai.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258888.top/Article/details/gtbyjydhkg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shangyingyoupin.top/Article/details/gtkjlhlyud.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuanzx.com/Article/details/gtrxxxqbqc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.snrcjt.cn/Article/details/gtlnlvvmvo.html

C#:   async Task F() { await G(); }
来源：http://dali.316326.xyz/Article/details/gtxjjeoxbh.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgufenzy.top/Article/details/gtlhvrrbcb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmprnpul.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinyuanbaomall.cn/Article/details/gtucjigtux.html

JS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtnlfiptcv.html

TS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gtsxmnqoup.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tanke756.top/Article/details/gtxegjgufs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gzhubu.top/Article/details/gtgwrxvnzz.html

Ruby: threads.map(&:join)
来源：http://dali.zdqjudy.top/Article/details/gtsltgeazv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gogol.net.cn/Article/details/gtdywkmikf.html

[O06] 使用进程池
来源：http://dali.meibo888.top/Article/details/gtgvcfchtp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shuidangran.top/Article/details/gtpdaziizf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.mhx1999.top/Article/details/gtqepysggw.html

JS:   // child_process / cluster 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrtoepkv.html

TS:   // child_process / cluster 模块
来源：http://dali.meibo888.top/Article/details/gtklswqjyb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.dianchejie.cn/Article/details/gtapgaiixi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jlsjyb.cn/Article/details/gtascbqzlz.html

Ruby: // fork 块
来源：http://dali.zhongyouzk.top/Article/details/gtbdmipswh.html

C#:   Parallel.For
来源：http://dali.quarkkingdee.top/Article/details/gtnoyoisax.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtggxsnuum.html

P. 常用工具函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdozxebh.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtggqybdjw.html

[P01] 生成 UUID
来源：http://dali.guannengcc.top/Article/details/gtlbmpuyfn.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgufenzy.top/Article/details/gtwxkstsqc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.9152youxi.cn/Article/details/gtteumbprl.html

JS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gtzcgwtgky.html

TS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gtqjvavgou.html

Java: UUID.randomUUID().toString()
来源：http://dali.pycfn.com/Article/details/gtsqjlbcbt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hnxiangtu.top/Article/details/gttrfexolk.html

Ruby: SecureRandom.uuid
来源：http://dali.meibo888.top/Article/details/gtdctaofpb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhengqikj.top/Article/details/gtpmbgsncy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgfzy.top/Article/details/gtarahzsyv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shangyingyoupin.top/Article/details/gtuhyldida.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.quarkkingdee.top/Article/details/gtuovynpca.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ppjwa.cn/Article/details/gtjxkaujcx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nanxinkj.top/Article/details/gtrpxakvjg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ydzc1.top/Article/details/gtajcqluvk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.pengpengdd.cyou/Article/details/gtaohlmevv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgfzy.top/Article/details/gtsinrtwwk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jyoumei.cn/Article/details/gtvcawzbns.html

[P03] 生成短随机字符串
来源：http://dali.cucudq.cn/Article/details/gtxtebynsf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tanke756.top/Article/details/gtmsrahqio.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yangfankeji.com/Article/details/gtxgcycvyb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj202588.top/Article/details/gtxdjeaycx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwryjyfpa.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.iojbl.cn/Article/details/gtwvsiszov.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhongyouzk.top/Article/details/gtjneccmwf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cucudq.cn/Article/details/gtdmsxvdag.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sxryk.cn/Article/details/gtybkhljmy.html

[P04] 求长度
来源：http://dali.gzhubu.top/Article/details/gtkxgikxtl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgfzy.top/Article/details/gtwmwbyrjx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gthotwamun.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.andypj.xyz/Article/details/gtydvvsjoq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sweek.top/Article/details/gtrnijweme.html

Java: list.size();  map.size();  s.length()
来源：http://dali.birdmap.top/Article/details/gtqbdnsauf.html

Go:   len(arr);  len(m)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgkkaxqr.html

Ruby: x.length;  x.size
来源：http://dali.xinyue.icu/Article/details/gtdhzbeuqc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jiagoushi.top/Article/details/gtbrfaiqzl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shangyingyoupin.top/Article/details/gtexvbzque.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.svipenyu.cn/Article/details/gtfbltajot.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cucudq.cn/Article/details/gtyrcerptz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.quarkkingdee.top/Article/details/gtzhohzlqv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258.top/Article/details/gtxcyotsxu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tian-w.cn/Article/details/gtjrqtucfr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cheryme.top/Article/details/gtnofguiwc.html

Ruby: a == b
来源：http://dali.jiagoushi.top/Article/details/gtmnsuneit.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sysykeji.top/Article/details/gtkyzxpofn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinghuilouyu.cn/Article/details/gtdnubfeti.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhongyouzk.top/Article/details/gtkoixnbog.html

PHP:  if (empty($x)) {}
来源：http://dali.nanxinkj.top/Article/details/gtpgiyfrge.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yangfankeji.com/Article/details/gtrxayqwld.html

TS:   if (x == null) {}
来源：http://dali.jinqigufen.top/Article/details/gtnpbuvxju.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtzoyejfjf.html

Go:   if x == nil {}
来源：http://dali.gotoacloud.top/Article/details/gtwrotgtai.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.havefunace.top/Article/details/gtbebsnpvv.html

C#:   if (x is null) {}
来源：http://dali.zhongyouzk.top/Article/details/gtfuaeddav.html

[P07] 防抖与节流
来源：http://dali.yj20258.top/Article/details/gtknvjndoi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxuanxn.top/Article/details/gtnpjvtyht.html

PHP:  // 手写时间戳比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrzndooc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtmlqzktnd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gthwadutej.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aibaodan.cn/Article/details/gtctkuapxy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sxryk.cn/Article/details/gtyscvhavl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sweek.top/Article/details/gthmdhagab.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxuanxn.top/Article/details/gttckiamwg.html

[P08] 处理浮点精度问题
来源：http://dali.iojbl.cn/Article/details/gtqkrvcvic.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xinyue.icu/Article/details/gtfsxkirgi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.mhx1999.top/Article/details/gtbhbacczh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xuetiantiany.cn/Article/details/gtcfvqmfnw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.havefunace.top/Article/details/gtmomdwuko.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigufen.top/Article/details/gtjvpftquf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.9152youxi.cn/Article/details/gtspsqnflp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yueranfly.top/Article/details/gtunbrqsby.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhengqikj.top/Article/details/gtabuylbge.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtzcdvkqrm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenjidiqi.icu/Article/details/gtkvpwsicg.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtblryuigo.html

[Q01] 创建表
来源：http://dali.guowangkeji.top/Article/details/gtcypzwuga.html

CREATE TABLE users (
来源：http://dali.xziqi.cn/Article/details/gtluljqmcl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhixingplan.top/Article/details/gtdbkoghqn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gttoatmeot.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnqzz.top/Article/details/gtfoswikjn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigfzy.top/Article/details/gtudguykvw.html

);
来源：http://dali.hfpthk.cn/Article/details/gtjreytkyg.html

[Q02] 创建带外键的表
来源：http://dali.redwolf501.top/Article/details/gtdyoanlpn.html

CREATE TABLE orders (
来源：http://dali.dashuyun.cn/Article/details/gtlovlfaer.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gzhubu.top/Article/details/gtemzskfth.html

user_id INT NOT NULL,
来源：http://dali.xuanzx.com/Article/details/gtqpysddja.html

amount DECIMAL(10, 2),
来源：http://dali.wangdashe.top/Article/details/gtoiedullh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xziqi.cn/Article/details/gtaqoeuwzy.html

);
来源：http://dali.yj20258.top/Article/details/gtgfyslkop.html

[Q03] 增加列
来源：http://dali.fengsongda.top/Article/details/gtoaowsqfb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.dianchejie.cn/Article/details/gtluwmgwce.html

[Q04] 修改列类型
来源：http://dali.chenlongwang.top/Article/details/gtolpsyhbi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shuidangran.top/Article/details/gtqmtyztyi.html

[Q05] 重命名列
来源：http://dali.sufxvd.cn/Article/details/gttjcayols.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ehwqpu.com/Article/details/gtioabyxfl.html

[Q06] 删除列
来源：http://dali.ehwqpu.com/Article/details/gtxxpvkpsz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sysykeji.top/Article/details/gtnmiydscn.html

[Q07] 删除表
来源：http://dali.316326.xyz/Article/details/gtomlkzolz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.guowangkeji.top/Article/details/gtbtrgtvds.html

[Q08] 创建普通索引
来源：http://dali.ydzc1.top/Article/details/gtekwqcphe.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhengqikj.top/Article/details/gtwfytexrb.html

[Q09] 创建唯一索引
来源：http://dali.fengsongda.top/Article/details/gtcowloyhs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gtvcruedzw.html

[Q10] 插入单行
来源：http://dali.xuetiantiany.cn/Article/details/gtioisbbwx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gtonzjjoit.html

[Q11] 一次插入多行
来源：http://dali.cashguo.top/Article/details/gtkiqqleda.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gtaiekamne.html

[Q12] 插入后取自增 ID
来源：http://dali.0kj1m.cn/Article/details/gtrgpylbzm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xuanzx.com/Article/details/gtlqdamqok.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.daria6918.cn/Article/details/gtdwouqrnj.html

[Q13] 忽略重复插入
来源：http://dali.feifeiyinyue.top/Article/details/gttkrmdywn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.meibo888.top/Article/details/gtmdakywaz.html

[Q14] 存在则更新（upsert）
来源：http://dali.redwolf501.top/Article/details/gtqlhtiolt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hywenlv.cn/Article/details/gtvtpjlyqj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tanke756.top/Article/details/gtjepyeuhl.html

[Q15] 查询全部
来源：http://dali.jyoumei.cn/Article/details/gtccspnmjn.html

SELECT * FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtlwtoigqh.html

[Q16] 查询指定列
来源：http://dali.ydzc1.top/Article/details/gtbqdbfdvf.html

SELECT id, name FROM users;
来源：http://dali.xylfe.cn/Article/details/gtizxcciuq.html

[Q17] 条件查询
来源：http://dali.fengsongda.top/Article/details/gtvxbkzomx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkylkowzx.html

[Q18] 模糊匹配
来源：http://dali.yj202588.top/Article/details/gtylfpnhpl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.quarkkingdee.top/Article/details/gtffwoccgu.html

[Q19] 范围查询
来源：http://dali.sxryk.cn/Article/details/gtawkqzzho.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuetiantiany.cn/Article/details/gtzoqcchgy.html

[Q20] IN 列表
来源：http://dali.birdmap.top/Article/details/gtmmdljotr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gtnfoctbzx.html

[Q21] 空值判断
来源：http://dali.svipenyu.cn/Article/details/gthspzppxl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxuanxn.top/Article/details/gtylcjnrbp.html

[Q22] 排序
来源：http://dali.chenzaomai.com/Article/details/gtzlcfkhll.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ybcxt.top/Article/details/gtqvedxslr.html

[Q23] 分页
来源：http://dali.hywenlv.cn/Article/details/gtgbxhqtqi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinqigfzy.top/Article/details/gtabgjqurb.html

[Q24] 去重
来源：http://dali.gaohongyu789.top/Article/details/gtmvxvqqnu.html

SELECT DISTINCT city FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtkgvolavz.html

[Q25] 只取前 N 条
来源：http://dali.havefunace.top/Article/details/gtrhtmmrqv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xinyue.icu/Article/details/gtabwfcmkp.html

[Q26] 计数
来源：http://dali.wangshuangyany.cn/Article/details/gthhxipded.html

SELECT COUNT(*) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtsvsjqmle.html

[Q27] 条件计数
来源：http://dali.meibo888.top/Article/details/gtxbecoirj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujpxqmyf.html

[Q28] 求和与平均
来源：http://dali.xuetiantiany.cn/Article/details/gtrwxqyoiq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtzksrdbmm.html

[Q29] 最大最小值
来源：http://dali.sxryk.cn/Article/details/gthjkhwfps.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtqrsfulqt.html

[Q30] 分组统计
来源：http://dali.sufxvd.cn/Article/details/gtjvpqjesa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gtyeyoqxbn.html

[Q31] 分组后过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtyuvutayw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtycfgztds.html

[Q32] 分组拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gtajtgtpym.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtxmyjqwle.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.kuanghao11.cn/Article/details/gtershngaz.html


<!-- 参考信息 -->