代发 wailian999

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yueranfly.top/Article/details/gtfxukpymb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fengsongda.top/Article/details/gtnsjcvdyd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jyoumei.cn/Article/details/gttthmacka.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gtaoonmdxl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gtdotcixoj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gtzjwrmanj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gtmprrishm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtlkxcakhz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gterwqaabw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yanxiufei.cn/Article/details/gtfhmoaftm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gtrtqmwsvs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtcmidckrc.html

[N05] 最大公约数
来源：http://dali.jqgfzy.top/Article/details/gtfddnpcim.html

Py:   math.gcd(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtfvszmnjv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoujvcflo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gtlcmhlbsj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcltibpqc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ivvv.top/Article/details/gtgdrehfpd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.316326.xyz/Article/details/gtqlwdfxrn.html

Ruby: a.gcd(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtonmewh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.feifeiyinyue.top/Article/details/gtqdaakipk.html

[N06] 判断回文字符串
来源：http://dali.ivvv.top/Article/details/gtalucilip.html

Py:   s == s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gtgpphgzyg.html

PHP:  $s === strrev($s);
来源：http://dali.yvedp.cn/Article/details/gtjzrvdopv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtybwtlecc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gthrdndphs.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xziqi.cn/Article/details/gttudrkjua.html

Go:   // 双指针从两端比较
来源：http://dali.aizwys.cn/Article/details/gtuccihscy.html

Ruby: s == s.reverse
来源：http://dali.havefunace.top/Article/details/gtmygpvdcm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gtronzhqwo.html

[N07] 两数之和（返回下标）
来源：http://dali.smart0.xyz/Article/details/gtycisoear.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yvedp.cn/Article/details/gtipsuzlas.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fengsongda.top/Article/details/gttyarbxjv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.iojbl.cn/Article/details/gtdxagudkq.html

TS:   // 手写 Map<string, number>
来源：http://dali.gogol.net.cn/Article/details/gtprkfuqcp.html

Java: // 手写 HashMap
来源：http://dali.xylfe.cn/Article/details/gtblvjvflt.html

Go:   // 手写 map[int]int
来源：http://dali.zhengqikj.top/Article/details/gtajpviovn.html

Ruby: // 手写 Hash
来源：http://dali.hammf.cn/Article/details/gtykodplaw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.haohaochexian.top/Article/details/gtvboosgih.html

[N08] 生成全排列
来源：http://dali.snrcjt.cn/Article/details/gtqlkfuksw.html

Py:   itertools.permutations(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtfliyazfj.html

PHP:  // 手写递归交换
来源：http://dali.tanke756.top/Article/details/gtwzerwtxm.html

JS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtwurhdjkp.html

TS:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtriacmzxc.html

Java: // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtqmgbsffk.html

Go:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtqdlccbke.html

Ruby: arr.permutation.to_a
来源：http://dali.zhongyouzk.top/Article/details/gtgoihxbok.html

C#:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gthbbhzciu.html

[N09] 栈与队列
来源：http://dali.gotoacloud.top/Article/details/gtsimlbmev.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.snrcjt.cn/Article/details/gtunhxqiys.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.pycfn.com/Article/details/gtdbbzzflv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqvyqzfq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fengsongda.top/Article/details/gttscxcice.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gtyzoxjgcm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tanke756.top/Article/details/gtctmkyvil.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtfocrbltx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yonumen.top/Article/details/gtkxdjctwm.html

[N10] 链表节点定义
来源：http://dali.ivvv.top/Article/details/gtixndzsuo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pengpengdd.cyou/Article/details/gtikttwgji.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gotoacloud.top/Article/details/gtvlbbotac.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfqmmirl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gotoacloud.top/Article/details/gtwjvkqbhq.html

Java: class Node { int v; Node next; }
来源：http://dali.xuetiantiany.cn/Article/details/gtrpuzfyfk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cheryme.top/Article/details/gtpzqyffbm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ydzc1.top/Article/details/gtkvispgyl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxinkj.top/Article/details/gtkobnmgrx.html

[N11] 二叉树中序遍历
来源：http://dali.sufxvd.cn/Article/details/gtmmuwinzp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenzaomai.com/Article/details/gtuujeugcs.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gtbcuommaj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xylfe.cn/Article/details/gtgwfnrhgv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gtcxohergf.html

Java: // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtiwcbsglq.html

Go:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gtuchhsxco.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hongshengwenyu.top/Article/details/gtntqosaem.html

C#:   // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gttuzsrbxv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hysaishi.cn/Article/details/gtmuidxyss.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcrboqmu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hysaishi.cn/Article/details/gtlmpsgufr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbrtptwn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gtjtpucufq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gtlgrgaske.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenzaomai.com/Article/details/gtojkpiyau.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.aizwys.cn/Article/details/gtlutzxrdr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gtolegjnrn.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnsmpyyii.html

O. 并发与异步
来源：http://dali.fengsongda.top/Article/details/gtrkrccxgd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtbsngxvjf.html

[O01] 启动一个线程
来源：http://dali.yanxiufei.cn/Article/details/gtndpteboh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cdnleiting.top/Article/details/gtczqyboaz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258888.top/Article/details/gtcsomtddg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jianghu66.top/Article/details/gtzdgywkxc.html

TS:   // 同 JS
来源：http://dali.fzhhl.top/Article/details/gtwmpluwkx.html

Java: new Thread(() -> f()).start()
来源：http://dali.zdqjudy.top/Article/details/gthvyzbttp.html

Go:   go f()
来源：http://dali.redwolf501.top/Article/details/gtihztzscr.html

Ruby: Thread.new { f }
来源：http://dali.cheryme.top/Article/details/gtmogjibph.html

C#:   Task.Run(() => F());
来源：http://dali.aibaodan.cn/Article/details/gtuwhomnrr.html

[O02] 使用线程池
来源：http://dali.fengsongda.top/Article/details/gtwvlhvsbx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.smart0.xyz/Article/details/gtyurblwxu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aizwys.cn/Article/details/gtcawrgqms.html

JS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gttmflonqv.html

TS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gtcakepgqs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gtpxwbzwxa.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnxiangtu.top/Article/details/gtaavjzfhj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yuxming.cn/Article/details/gtxivysxrr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinqigfzy.top/Article/details/gttvcwfchz.html

[O03] 加锁保护共享数据
来源：http://dali.iojbl.cn/Article/details/gtlrcbhdnw.html

Py:   with lock: shared += 1
来源：http://dali.tianlin.xyz/Article/details/gtqcgwyjfy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shanyushiyangtech.top/Article/details/gthvzknzbt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cucudq.cn/Article/details/gtxdladarg.html

TS:   // 同 JS
来源：http://dali.sxryk.cn/Article/details/gtmycrirts.html

Java: synchronized (this) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gtqzzltofw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pengpengdd.cyou/Article/details/gthzzwlfcf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shuidangran.top/Article/details/gtixbtzlig.html

C#:   lock (gate) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gtbvhrhhfu.html

[O04] 定义异步函数并等待
来源：http://dali.shangyingyoupin.top/Article/details/gtvuvnqsyb.html

Py:   async def f():⏎    await g()
来源：http://dali.shuidangran.top/Article/details/gtkwjnwplp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gaohongyu789.top/Article/details/gtdtlruclv.html

JS:   async function f() { await g(); }
来源：http://dali.aizwys.cn/Article/details/gtwrsllvfr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpiyqieg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangtech.top/Article/details/gtmftdfcbv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gzhubu.top/Article/details/gtjsjnppzw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gzhubu.top/Article/details/gtvukypemo.html

C#:   async Task F() { await G(); }
来源：http://dali.yj202588.top/Article/details/gtjifpinse.html

[O05] 并发执行并等待全部完成
来源：http://dali.havefunace.top/Article/details/gtaxobusyc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shuidangran.top/Article/details/gtacpvzazb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ybcxt.top/Article/details/gtldlwvpjy.html

JS:   await Promise.all(tasks)
来源：http://dali.jiagoushi.top/Article/details/gtfypwddja.html

TS:   await Promise.all(tasks)
来源：http://dali.jqgufenzy.top/Article/details/gtxllztaev.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jqgufenzy.top/Article/details/gtmiytmxdo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.svipenyu.cn/Article/details/gtrqzvltcv.html

Ruby: threads.map(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gtmyworhse.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tanke756.top/Article/details/gtchflyztm.html

[O06] 使用进程池
来源：http://dali.ehwqpu.com/Article/details/gtkmskxcdo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangdashe.top/Article/details/gtlfkutmbk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.havefunace.top/Article/details/gtxpvtdilv.html

JS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gtmwaqgclm.html

TS:   // child_process / cluster 模块
来源：http://dali.hfpthk.cn/Article/details/gtohgkfzce.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.guannengcc.top/Article/details/gtnltvwqal.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.daxiang520.top/Article/details/gtiprrrvrx.html

Ruby: // fork 块
来源：http://dali.yongpay.top/Article/details/gtniuqpvud.html

C#:   Parallel.For
来源：http://dali.daxiang520.top/Article/details/gthrsywata.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtitrnjywr.html

P. 常用工具函数
来源：http://dali.xinyue.icu/Article/details/gtwprxfbbf.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtvlznphlp.html

[P01] 生成 UUID
来源：http://dali.zhengqikj.top/Article/details/gtcoohpouq.html

Py:   str(uuid.uuid4())
来源：http://dali.sysykeji.top/Article/details/gtbukberbl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.birdmap.top/Article/details/gtyzqqzlmy.html

JS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gtsnzqjbyp.html

TS:   crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gtoyrojaaa.html

Java: UUID.randomUUID().toString()
来源：http://dali.pycfn.com/Article/details/gtsclajfkd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtlooeqdag.html

Ruby: SecureRandom.uuid
来源：http://dali.9152youxi.cn/Article/details/gtucpvojho.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.daria6918.cn/Article/details/gtxomdodwk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gtyxndfggr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yangfankeji.com/Article/details/gtdpvpupur.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.guannengcc.top/Article/details/gtsdxoxwam.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hnqzz.top/Article/details/gtogqxehbt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.havefunace.top/Article/details/gtzgeezxtd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxinkj.top/Article/details/gtxyusnspy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jiagoushi.top/Article/details/gtxhzqrhhh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shuidangran.top/Article/details/gtiyyprhie.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xziqi.cn/Article/details/gtaivrrezu.html

[P03] 生成短随机字符串
来源：http://dali.guannengcc.top/Article/details/gtyzedagzy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hysaishi.cn/Article/details/gtncufehkk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.meibo888.top/Article/details/gtrtmmjkqm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gtnjspvynx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gtowldqifr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hfpthk.cn/Article/details/gteivgncyo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pengpengdd.cyou/Article/details/gtpfgfzasr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.pengpengdd.cyou/Article/details/gtsmedgsxo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tian-w.cn/Article/details/gtnhsgckum.html

[P04] 求长度
来源：http://dali.shzxlz.cn/Article/details/gtcmrtxonl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gzhubu.top/Article/details/gtbpdvwlwd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtdqpscslj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gtnnmlvqxi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gtnxumadvr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.andypj.xyz/Article/details/gtczdqcyip.html

Go:   len(arr);  len(m)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnsswnao.html

Ruby: x.length;  x.size
来源：http://dali.sweek.top/Article/details/gtfxqzlvmx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj20258888.top/Article/details/gtvxydoxiy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.mhx1999.top/Article/details/gtzudtnqqn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fzhhl.top/Article/details/gtblccjcvg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shuidangran.top/Article/details/gtitumqizp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daria6918.cn/Article/details/gtimlkkaqf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cheryme.top/Article/details/gtpebmvyeu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinqigufen.top/Article/details/gttpyugtyc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dianchejie.cn/Article/details/gtllpnstir.html

Ruby: a == b
来源：http://dali.shangyingyoupin.top/Article/details/gtmottpyno.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.dashuyun.cn/Article/details/gtjswpcykd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sufxvd.cn/Article/details/gtlixsafxy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yvedp.cn/Article/details/gtoknalwyq.html

PHP:  if (empty($x)) {}
来源：http://dali.jlsjyb.cn/Article/details/gtqauxdfag.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xinyue.icu/Article/details/gtdgdiqftl.html

TS:   if (x == null) {}
来源：http://dali.cucudq.cn/Article/details/gthwdbkejx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gtpqwratyg.html

Go:   if x == nil {}
来源：http://dali.zhixingplan.top/Article/details/gtvtcaemsn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hywenlv.cn/Article/details/gtsylworyy.html

C#:   if (x is null) {}
来源：http://dali.gzhubu.top/Article/details/gtvbegoswp.html

[P07] 防抖与节流
来源：http://dali.kuanghao11.cn/Article/details/gtzfwixitv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daxiang520.top/Article/details/gtbxhafdeg.html

PHP:  // 手写时间戳比较
来源：http://dali.jyoumei.cn/Article/details/gtupjivxra.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cdnleiting.top/Article/details/gtktspsqmc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cheryme.top/Article/details/gthdjgfkaa.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sweek.top/Article/details/gtcpokqyxg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nanxinkj.top/Article/details/gttobqciun.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxuanxn.top/Article/details/gtnkhbtpph.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yueranfly.top/Article/details/gtfsnhqmps.html

[P08] 处理浮点精度问题
来源：http://dali.yonumen.top/Article/details/gtehpskcjh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hongshengwenyu.top/Article/details/gtrutjnvek.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhongyouzk.top/Article/details/gtuimjhetp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tanke756.top/Article/details/gtligmmdct.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtcbuzbget.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fzhhl.top/Article/details/gtcahjqfcp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xziqi.cn/Article/details/gtspzfgrqe.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhongyouzk.top/Article/details/gtholkzbze.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.feifeiyinyue.top/Article/details/gthbqnyqdk.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gthqdwolbq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hammf.cn/Article/details/gtwxfuxbam.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtypduqdmj.html

[Q01] 创建表
来源：http://dali.hammf.cn/Article/details/gtmfhsjhbu.html

CREATE TABLE users (
来源：http://dali.kuanghao11.cn/Article/details/gthenvpplk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gtpikxsufz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gtkqrkpash.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hongshengwenyu.top/Article/details/gtznxwmxca.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.snrcjt.cn/Article/details/gtfikhoebl.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgaztwrlm.html

[Q02] 创建带外键的表
来源：http://dali.9152youxi.cn/Article/details/gtrzqsammx.html

CREATE TABLE orders (
来源：http://dali.fzhhl.top/Article/details/gtvxtdwqku.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hammf.cn/Article/details/gtreqbchgu.html

user_id INT NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gtyckzwgpb.html

amount DECIMAL(10, 2),
来源：http://dali.jianghu66.top/Article/details/gtimzjvpok.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jiagoushi.top/Article/details/gtkqjtwhkh.html

);
来源：http://dali.vqdsnc.cn/Article/details/gtehzptpep.html

[Q03] 增加列
来源：http://dali.ehwqpu.com/Article/details/gtexpypokg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxinkj.top/Article/details/gtjahnijbt.html

[Q04] 修改列类型
来源：http://dali.havefunace.top/Article/details/gtnapeqoki.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daxiang520.top/Article/details/gtyxlzitlv.html

[Q05] 重命名列
来源：http://dali.ybcxt.top/Article/details/gtkxcdmjux.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aizwys.cn/Article/details/gtgznkvsdc.html

[Q06] 删除列
来源：http://dali.fzhhl.top/Article/details/gtiagxkzqg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jyoumei.cn/Article/details/gtbylsdssf.html

[Q07] 删除表
来源：http://dali.guowangkeji.top/Article/details/gttauzxrgo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.andypj.xyz/Article/details/gtezqfvzct.html

[Q08] 创建普通索引
来源：http://dali.daxiang520.top/Article/details/gtorglonls.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gtplnmuelw.html

[Q09] 创建唯一索引
来源：http://dali.jinqigfzy.top/Article/details/gtxizngbtt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxuanxn.top/Article/details/gtbdgrmjkk.html

[Q10] 插入单行
来源：http://dali.zdqjudy.top/Article/details/gtcsmzkqon.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtrdtcyrfa.html

[Q11] 一次插入多行
来源：http://dali.hammf.cn/Article/details/gtgquhgixb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nanxinkj.top/Article/details/gttcpwdlxg.html

[Q12] 插入后取自增 ID
来源：http://dali.shuidangran.top/Article/details/gtdfpgioyj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zdqjudy.top/Article/details/gtqqkdczec.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cashguo.top/Article/details/gtcrofsaaq.html

[Q13] 忽略重复插入
来源：http://dali.gzhubu.top/Article/details/gtqetmmhsb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.iojbl.cn/Article/details/gtmgtdcvlf.html

[Q14] 存在则更新（upsert）
来源：http://dali.shzxlz.cn/Article/details/gtkzoybbji.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xinyue.icu/Article/details/gtwdtpavsi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinghuilouyu.cn/Article/details/gtekqtfeln.html

[Q15] 查询全部
来源：http://dali.hywenlv.cn/Article/details/gtpllljmpv.html

SELECT * FROM users;
来源：http://dali.sweek.top/Article/details/gtjivlvmaq.html

[Q16] 查询指定列
来源：http://dali.chenlongwang.top/Article/details/gtsrwlpqmm.html

SELECT id, name FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxxjgxmf.html

[Q17] 条件查询
来源：http://dali.yj20258888.top/Article/details/gtalxukkin.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cashguo.top/Article/details/gtuzesiwuf.html

[Q18] 模糊匹配
来源：http://dali.hammf.cn/Article/details/gtoukgtbgs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhiwuduotai.top/Article/details/gteomaahhg.html

[Q19] 范围查询
来源：http://dali.haohaochexian.top/Article/details/gttnaewudx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yonumen.top/Article/details/gtsbhrcemd.html

[Q20] IN 列表
来源：http://dali.wangshuangyany.cn/Article/details/gthgbtqhzi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cheryme.top/Article/details/gtmmubuwfh.html

[Q21] 空值判断
来源：http://dali.zhixingplan.top/Article/details/gtmdxmolhr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jlsjyb.cn/Article/details/gttoswpnpp.html

[Q22] 排序
来源：http://dali.zhixingplan.top/Article/details/gtnrzsrzjj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cucudq.cn/Article/details/gtvrfyvvub.html

[Q23] 分页
来源：http://dali.hongshengwenyu.top/Article/details/gtzjnahtpp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yvedp.cn/Article/details/gtcaqjydxk.html

[Q24] 去重
来源：http://dali.zdqjudy.top/Article/details/gtekyvljpq.html

SELECT DISTINCT city FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtpnhodxlj.html

[Q25] 只取前 N 条
来源：http://dali.gzhubu.top/Article/details/gtxcbwefhy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sweek.top/Article/details/gtdhrkpxxd.html

[Q26] 计数
来源：http://dali.zhiwuduotai.top/Article/details/gtrephkxvd.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtujrpvhom.html

[Q27] 条件计数
来源：http://dali.fzhhl.top/Article/details/gtkdumtmqx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.smart0.xyz/Article/details/gtzksixycj.html

[Q28] 求和与平均
来源：http://dali.ydzc1.top/Article/details/gtdmackysm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtkxfbykob.html

[Q29] 最大最小值
来源：http://dali.cashguo.top/Article/details/gttiqwzvcv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtqniedatg.html

[Q30] 分组统计
来源：http://dali.havefunace.top/Article/details/gtidmemrzl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gtqveyydyo.html

[Q31] 分组后过滤
来源：http://dali.zdqjudy.top/Article/details/gtrshlmqgd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jyoumei.cn/Article/details/gtpjodjqun.html

[Q32] 分组拼接字符串
来源：http://dali.pycfn.com/Article/details/gtvaanmnaj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthiobhrvf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.svipenyu.cn/Article/details/gtnvjxzspi.html

[Q33] 多列分组
来源：http://dali.sufxvd.cn/Article/details/gtvfoteyar.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pengpengdd.cyou/Article/details/gtqgmytfss.html

[Q34] 每组取第一条
来源：http://dali.yuxming.cn/Article/details/gtkbuvwhgf.html

SELECT * FROM (
来源：http://dali.xylfe.cn/Article/details/gtbdqnapyr.html


<!-- 参考信息 -->