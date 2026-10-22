代发 wailian999

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigufen.top/Article/details/gtbjotadvx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgowbmyf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.svipenyu.cn/Article/details/gtxlddgsby.html

[N04] 斐波那契数列
来源：http://dali.zhiwuduotai.top/Article/details/gtxhjtnwto.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gtrroremno.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gtteexozew.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gttflsesrt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtxplssmwa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gtwlkaxrko.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sxryk.cn/Article/details/gtwmmsgiog.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gtrmcjcdbv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtaguystyz.html

[N05] 最大公约数
来源：http://dali.xinyue.icu/Article/details/gtcmeofkjz.html

Py:   math.gcd(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtnpyxzgxg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.birdmap.top/Article/details/gtxcgocfit.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gtbvyxilxr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gtaxkvvzjl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.haohaochexian.top/Article/details/gttwvowrop.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ydzc1.top/Article/details/gticuobanj.html

Ruby: a.gcd(b)
来源：http://dali.yj202588.top/Article/details/gtzcxjyovf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhongyouzk.top/Article/details/gttbaxktiu.html

[N06] 判断回文字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtlbfllgoi.html

Py:   s == s[::-1]
来源：http://dali.ppjwa.cn/Article/details/gtvtzojgrd.html

PHP:  $s === strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtqoqawmmv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gttdpkheto.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtechfycms.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sweek.top/Article/details/gtmizbkgep.html

Go:   // 双指针从两端比较
来源：http://dali.nwbrower.top/Article/details/gtdqgvbtkw.html

Ruby: s == s.reverse
来源：http://dali.hammf.cn/Article/details/gtlxrnqjcx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gtovhtuivz.html

[N07] 两数之和（返回下标）
来源：http://dali.yanxiufei.cn/Article/details/gtngarnvlk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258888.top/Article/details/gtoygxoilg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zycfv.cn/Article/details/gthuqbtbwx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.snrcjt.cn/Article/details/gtgxwjcdjt.html

TS:   // 手写 Map<string, number>
来源：http://dali.iojbl.cn/Article/details/gtjoodalvc.html

Java: // 手写 HashMap
来源：http://dali.shuidangran.top/Article/details/gtxdgfhofe.html

Go:   // 手写 map[int]int
来源：http://dali.yongpay.top/Article/details/gtoyynuvfi.html

Ruby: // 手写 Hash
来源：http://dali.chenjidiqi.icu/Article/details/gtrzxrzpuz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthxxhjlkg.html

[N08] 生成全排列
来源：http://dali.hnqzz.top/Article/details/gtejzvojcn.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtbhfhhgim.html

PHP:  // 手写递归交换
来源：http://dali.havefunace.top/Article/details/gtksvfhugi.html

JS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtyahxemrd.html

TS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtpbducygn.html

Java: // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtyquntakj.html

Go:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtgkwbazog.html

Ruby: arr.permutation.to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcazbcwjw.html

C#:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtzsziqhhu.html

[N09] 栈与队列
来源：http://dali.dianchejie.cn/Article/details/gtxqlpohuj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtnlljrcqx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtalriuhwm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gthlwfmiwy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.vqdsnc.cn/Article/details/gteonrwyhw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.snrcjt.cn/Article/details/gtwlzatpca.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cdnleiting.top/Article/details/gtqazloncv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gtezooejae.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jianghu66.top/Article/details/gtdtmdoutr.html

[N10] 链表节点定义
来源：http://dali.mhx1999.top/Article/details/gtkogguxwl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jianghu66.top/Article/details/gtntfnhqsf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigfzy.top/Article/details/gtnnvmmpcw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtnhlsbwyt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdycbgkxo.html

Java: class Node { int v; Node next; }
来源：http://dali.birdmap.top/Article/details/gtopdedurc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtanzvrjjd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xuetiantiany.cn/Article/details/gtojzicrcl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.guannengcc.top/Article/details/gtzznycobr.html

[N11] 二叉树中序遍历
来源：http://dali.kuanghao11.cn/Article/details/gtaopcyczh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.wangshuangyany.cn/Article/details/gthyejuqfe.html

PHP:  // 手写递归函数
来源：http://dali.jianghu66.top/Article/details/gtgkzldjok.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pengpengdd.cyou/Article/details/gtrevuxbxp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhengqikj.top/Article/details/gtndorgpns.html

Java: // 手写递归
来源：http://dali.hnqzz.top/Article/details/gtvuljejqb.html

Go:   // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gtdscjyrkr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ehwqpu.com/Article/details/gtvwllstyo.html

C#:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtjftnopff.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cqqwz.cn/Article/details/gtdcxhflkd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.smart0.xyz/Article/details/gtpizldowg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfvwqcgf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gthhlocsui.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gtgdkbovdo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gtrtygmtwe.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.fzhhl.top/Article/details/gtxcfuqaij.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.quarkkingdee.top/Article/details/gtqosjlvxb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gtmtzejpzu.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtidxhoamp.html

O. 并发与异步
来源：http://dali.gogol.net.cn/Article/details/gtyyapwmun.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtmeqoeqwc.html

[O01] 启动一个线程
来源：http://dali.hfpthk.cn/Article/details/gtwiaamhej.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hysaishi.cn/Article/details/gtcysvcofn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sweek.top/Article/details/gtszgfsosq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gzhubu.top/Article/details/gtndcqbmnv.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gtkiyerodk.html

Java: new Thread(() -> f()).start()
来源：http://dali.jyoumei.cn/Article/details/gtuzfyxohh.html

Go:   go f()
来源：http://dali.nanxuanxn.top/Article/details/gtsldjjurq.html

Ruby: Thread.new { f }
来源：http://dali.chenlongwang.top/Article/details/gtsdmhsavr.html

C#:   Task.Run(() => F());
来源：http://dali.havefunace.top/Article/details/gteaufrvnp.html

[O02] 使用线程池
来源：http://dali.ivvv.top/Article/details/gthwjwxyho.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guannengcc.top/Article/details/gtdxnugyxq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.havefunace.top/Article/details/gtbswztsds.html

JS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gtnaptkgzx.html

TS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gtfbvxmeaf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258.top/Article/details/gtzqqpxujo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.bjfxy.top/Article/details/gtlqpqncxm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shangyingyoupin.top/Article/details/gtzszokdws.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guowangkeji.top/Article/details/gtrmbowljs.html

[O03] 加锁保护共享数据
来源：http://dali.hywenlv.cn/Article/details/gthbbvmkzb.html

Py:   with lock: shared += 1
来源：http://dali.iojbl.cn/Article/details/gtpawbgglk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.andypj.xyz/Article/details/gtcxymazuq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.0kj1m.cn/Article/details/gtnpnvxvod.html

TS:   // 同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtqifedqac.html

Java: synchronized (this) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gtoyxrlmge.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zycfv.cn/Article/details/gtqdxcglzs.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tianlin.xyz/Article/details/gtbuqjrvgj.html

C#:   lock (gate) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmoacbgy.html

[O04] 定义异步函数并等待
来源：http://dali.316326.xyz/Article/details/gtxlbiakdf.html

Py:   async def f():⏎    await g()
来源：http://dali.cucudq.cn/Article/details/gtpaeewsiw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tanke756.top/Article/details/gtiqmabdvj.html

JS:   async function f() { await g(); }
来源：http://dali.tian-w.cn/Article/details/gtbricxjic.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nwbrower.top/Article/details/gtapgznxkg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258.top/Article/details/gtktbspmnc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tian-w.cn/Article/details/gtphldzbvr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigfzy.top/Article/details/gtuiovwyzf.html

C#:   async Task F() { await G(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfzktrdws.html

[O05] 并发执行并等待全部完成
来源：http://dali.svipenyu.cn/Article/details/gthhayeody.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhixingplan.top/Article/details/gtwleqficp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sweek.top/Article/details/gtxqiloprm.html

JS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gtkljfpvwt.html

TS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gtprukjnfe.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj202588.top/Article/details/gtlbpxsmfa.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tian-w.cn/Article/details/gtkmeudygy.html

Ruby: threads.map(&:join)
来源：http://dali.yangfankeji.com/Article/details/gtgtdrwljr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbljtsuuz.html

[O06] 使用进程池
来源：http://dali.daxiang520.top/Article/details/gtdzkirhds.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdvzhqni.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cheryme.top/Article/details/gtnnqdbdyj.html

JS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gthleobvwr.html

TS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gttfnfodvk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fengsongda.top/Article/details/gtnuqmobyg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhiwuduotai.top/Article/details/gtbdbxvwej.html

Ruby: // fork 块
来源：http://dali.9152youxi.cn/Article/details/gttvvtwqmu.html

C#:   Parallel.For
来源：http://dali.zhixingplan.top/Article/details/gtetuyapwu.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gthjceonrf.html

P. 常用工具函数
来源：http://dali.nanxinkj.top/Article/details/gtggvsrctt.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtyzopfgve.html

[P01] 生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gtxlsjrrvd.html

Py:   str(uuid.uuid4())
来源：http://dali.cashguo.top/Article/details/gtlbhjlkao.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhixingplan.top/Article/details/gtxnfliqja.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gtkyfyhsdd.html

TS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gtgxmmdkcf.html

Java: UUID.randomUUID().toString()
来源：http://dali.haohaochexian.top/Article/details/gtxuwmqugh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgufenzy.top/Article/details/gtevfjmipx.html

Ruby: SecureRandom.uuid
来源：http://dali.0kj1m.cn/Article/details/gtfrgyvdhh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigfzy.top/Article/details/gtbzpkrezq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jlsjyb.cn/Article/details/gtrifzyiap.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yvedp.cn/Article/details/gtrzzxuxfe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ivvv.top/Article/details/gtholjrnlp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cdnleiting.top/Article/details/gtkmhfdlqs.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenjidiqi.icu/Article/details/gtqhcnmlom.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sysykeji.top/Article/details/gtzermrkwy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangshuangyany.cn/Article/details/gthmctmyvl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hammf.cn/Article/details/gtfbnizwaq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangdashe.top/Article/details/gtcjyfwakq.html

[P03] 生成短随机字符串
来源：http://dali.yj20258888.top/Article/details/gtzpryrwxa.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgjfrjna.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tianlin.xyz/Article/details/gteajsbcvy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gtyllyzqnj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuanzhike.top/Article/details/gtlprsvibh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gotoacloud.top/Article/details/gtgsecaoji.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnqzz.top/Article/details/gtbivhkkzb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.kuanghao11.cn/Article/details/gtgtbwunxk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ppjwa.cn/Article/details/gtjejjdgrs.html

[P04] 求长度
来源：http://dali.havefunace.top/Article/details/gtbjofxnby.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gttmkfglwd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtwworhehh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuzeucwc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gteruqjiaw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangdashe.top/Article/details/gtavsphgll.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gttzahfcus.html

Ruby: x.length;  x.size
来源：http://dali.nwbrower.top/Article/details/gtutobhxqa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ybcxt.top/Article/details/gtuwlmomrv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.kuanghao11.cn/Article/details/gtxxcwxstx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.0kj1m.cn/Article/details/gtdlssaphs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yonumen.top/Article/details/gtsqxpytei.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.haohaochexian.top/Article/details/gtreisytig.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuanzhike.top/Article/details/gtbnwpcutu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dianchejie.cn/Article/details/gttddmuhxf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gzhubu.top/Article/details/gtgezgpgxg.html

Ruby: a == b
来源：http://dali.hnxiangtu.top/Article/details/gtwlltpqfi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.9152youxi.cn/Article/details/gtczuzbcng.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.daxiang520.top/Article/details/gtbfpbydse.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yuxming.cn/Article/details/gttfqeootu.html

PHP:  if (empty($x)) {}
来源：http://dali.cheryme.top/Article/details/gtbizpjqkm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yonumen.top/Article/details/gteqebstev.html

TS:   if (x == null) {}
来源：http://dali.meibo888.top/Article/details/gtnfmpupja.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpijxtpv.html

Go:   if x == nil {}
来源：http://dali.yj202588.top/Article/details/gtnapfvdxn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sxryk.cn/Article/details/gtkahnxido.html

C#:   if (x is null) {}
来源：http://dali.guannengcc.top/Article/details/gtfzwfxmnm.html

[P07] 防抖与节流
来源：http://dali.ppjwa.cn/Article/details/gtsjitsfyu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zycfv.cn/Article/details/gtwcvmwvsl.html

PHP:  // 手写时间戳比较
来源：http://dali.jlsjyb.cn/Article/details/gtalgrgdzw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gtussfupsn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zycfv.cn/Article/details/gtlksmmnvx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shuidangran.top/Article/details/gtneiioewn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenzaomai.com/Article/details/gtfruzmluv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tanke756.top/Article/details/gtynbkuans.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.dianchejie.cn/Article/details/gtpgdjecrc.html

[P08] 处理浮点精度问题
来源：http://dali.0kj1m.cn/Article/details/gthxryowcp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sweek.top/Article/details/gtphsjhcuh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.bjfxy.top/Article/details/gtxpacmqtx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yueranfly.top/Article/details/gtyhmdqkxe.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jyoumei.cn/Article/details/gtpjbgledp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jyoumei.cn/Article/details/gtlizavibu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangtech.top/Article/details/gtbedhidsr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sufxvd.cn/Article/details/gtnqguvwww.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ivvv.top/Article/details/gtccwmvzdb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtpqrdlbwq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pycfn.com/Article/details/gtnagxvsrg.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtixhlmvrm.html

[Q01] 创建表
来源：http://dali.yvedp.cn/Article/details/gtaitzoovd.html

CREATE TABLE users (
来源：http://dali.daria6918.cn/Article/details/gtitmansdy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangdashe.top/Article/details/gtfzxpabgh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gtyjcfuvlp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yongpay.top/Article/details/gthwcrqior.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hywenlv.cn/Article/details/gtorslzabn.html

);
来源：http://dali.0kj1m.cn/Article/details/gthutspdzf.html

[Q02] 创建带外键的表
来源：http://dali.yueranfly.top/Article/details/gtpsvrpucu.html

CREATE TABLE orders (
来源：http://dali.shangyingyoupin.top/Article/details/gtumefrxyf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cucudq.cn/Article/details/gtenkytkxo.html

user_id INT NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gtyoztqftu.html

amount DECIMAL(10, 2),
来源：http://dali.zhoulong.xyz/Article/details/gtmpelamev.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.feifeiyinyue.top/Article/details/gthdixrhvv.html

);
来源：http://dali.yueranfly.top/Article/details/gtbqtkzhlq.html

[Q03] 增加列
来源：http://dali.mhx1999.top/Article/details/gtnxcerbep.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ehwqpu.com/Article/details/gtxhkvdmkl.html

[Q04] 修改列类型
来源：http://dali.yvedp.cn/Article/details/gtpfadzptz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.316326.xyz/Article/details/gtjvviitql.html

[Q05] 重命名列
来源：http://dali.jqgufenzy.top/Article/details/gtzswfpjpl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadkhocmu.html

[Q06] 删除列
来源：http://dali.haohaochexian.top/Article/details/gtlzsgctgg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dashuyun.cn/Article/details/gtqqfonudv.html

[Q07] 删除表
来源：http://dali.yonumen.top/Article/details/gtxqcqekcs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aibaodan.cn/Article/details/gtilfajfbh.html

[Q08] 创建普通索引
来源：http://dali.zhiwuduotai.top/Article/details/gtqhjmngym.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhoulong.xyz/Article/details/gtlbgtxptg.html

[Q09] 创建唯一索引
来源：http://dali.jlsjyb.cn/Article/details/gtuqnxqgcl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxcubdif.html

[Q10] 插入单行
来源：http://dali.svipenyu.cn/Article/details/gtazgqvwvp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ybcxt.top/Article/details/gtmbrawazm.html

[Q11] 一次插入多行
来源：http://dali.nanxuanxn.top/Article/details/gttntgqdtb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gtznisbzow.html

[Q12] 插入后取自增 ID
来源：http://dali.dashuyun.cn/Article/details/gtmylrgmkg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.c1oappe.top/Article/details/gtvhfnpute.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.havefunace.top/Article/details/gtkwzzonov.html

[Q13] 忽略重复插入
来源：http://dali.bjfxy.top/Article/details/gtkvievpew.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenzaomai.com/Article/details/gtitdgokak.html

[Q14] 存在则更新（upsert）
来源：http://dali.gaohongyu789.top/Article/details/gtbpbxijup.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cheryme.top/Article/details/gttifepgmq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daria6918.cn/Article/details/gtvdqklyoz.html

[Q15] 查询全部
来源：http://dali.jyoumei.cn/Article/details/gtdykyrcgs.html

SELECT * FROM users;
来源：http://dali.gzhubu.top/Article/details/gtbmnstfhs.html

[Q16] 查询指定列
来源：http://dali.zhongyouzk.top/Article/details/gtvepczhiz.html

SELECT id, name FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtmpjrzdzn.html

[Q17] 条件查询
来源：http://dali.wangdashe.top/Article/details/gtjwspeukm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yangfankeji.com/Article/details/gtlkyxvkvr.html

[Q18] 模糊匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyepudlal.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiokkghje.html

[Q19] 范围查询
来源：http://dali.xinyue.icu/Article/details/gtklnphtab.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hammf.cn/Article/details/gtqcuelzbv.html

[Q20] IN 列表
来源：http://dali.yueranfly.top/Article/details/gtoebtscop.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cucudq.cn/Article/details/gtukxirjcz.html

[Q21] 空值判断
来源：http://dali.iojbl.cn/Article/details/gtmmsphggt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tian-w.cn/Article/details/gtwwgvkphx.html

[Q22] 排序
来源：http://dali.feifeiyinyue.top/Article/details/gtyvjatesy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yuanzhike.top/Article/details/gtmslikggr.html

[Q23] 分页
来源：http://dali.quarkkingdee.top/Article/details/gtdanzodll.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jqgfzy.top/Article/details/gtzfjqyhnr.html

[Q24] 去重
来源：http://dali.guowangkeji.top/Article/details/gtfuxnopmd.html

SELECT DISTINCT city FROM users;
来源：http://dali.xziqi.cn/Article/details/gtnyemkbgh.html

[Q25] 只取前 N 条
来源：http://dali.jqgfzy.top/Article/details/gtimilxcze.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sufxvd.cn/Article/details/gtxqqpomkz.html

[Q26] 计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfokkopks.html

SELECT COUNT(*) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtjambscwp.html

[Q27] 条件计数
来源：http://dali.jinqigufen.top/Article/details/gtipyvbwnc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jianghu66.top/Article/details/gtmpulhxxx.html

[Q28] 求和与平均
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhfqztem.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.316326.xyz/Article/details/gtborcdham.html

[Q29] 最大最小值
来源：http://dali.jinqigufen.top/Article/details/gtbutrpdov.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtkqrxhewi.html

[Q30] 分组统计
来源：http://dali.jinqigfzy.top/Article/details/gtmcnkzrqi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtiwufcqui.html

[Q31] 分组后过滤
来源：http://dali.xuanzx.com/Article/details/gtzkfbhwpm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zdqjudy.top/Article/details/gtxgxwwvkj.html

[Q32] 分组拼接字符串
来源：http://dali.nwbrower.top/Article/details/gtxeltqgho.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gthjuagfmu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jlsjyb.cn/Article/details/gtmmjazdut.html

[Q33] 多列分组
来源：http://dali.wangshuangyany.cn/Article/details/gtgdjgqjqr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.wangshuangyany.cn/Article/details/gttrsapzkf.html

[Q34] 每组取第一条
来源：http://dali.ivvv.top/Article/details/gtlihafywp.html

SELECT * FROM (
来源：http://dali.ybcxt.top/Article/details/gtolktnbdg.html


<!-- 参考信息 -->