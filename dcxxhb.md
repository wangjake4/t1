代发 wailian999

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jiagoushi.top/Article/details/gtfaeyuhdm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj202588.top/Article/details/gtqttcsgrh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gtxghvrrds.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gtswreaiww.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gtafhhgmvg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenzaomai.com/Article/details/gtbjimiovo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtjrdnrwis.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtgfhlwmhp.html

[N05] 最大公约数
来源：http://dali.nanxuanxn.top/Article/details/gtswagpmhn.html

Py:   math.gcd(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwkpznre.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnqzz.top/Article/details/gtdmcakkos.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aizwys.cn/Article/details/gtnssdahaj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gtlobisznf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sweek.top/Article/details/gtoxivyyfc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yongpay.top/Article/details/gttblfffzc.html

Ruby: a.gcd(b)
来源：http://dali.sysykeji.top/Article/details/gtmbmwrzox.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ppjwa.cn/Article/details/gtuxzjynrm.html

[N06] 判断回文字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtkaflbmmq.html

Py:   s == s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbixyjhk.html

PHP:  $s === strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gtkruputsl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtbjyqyvpw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtfylespru.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aizwys.cn/Article/details/gttslfcopp.html

Go:   // 双指针从两端比较
来源：http://dali.ybcxt.top/Article/details/gtgrqgouuo.html

Ruby: s == s.reverse
来源：http://dali.pycfn.com/Article/details/gtgvpbisgt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zdqjudy.top/Article/details/gtncdoqfvx.html

[N07] 两数之和（返回下标）
来源：http://dali.daria6918.cn/Article/details/gtxihuagik.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aibaodan.cn/Article/details/gtcjqxopkv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.andypj.xyz/Article/details/gthvqdtpuj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.0kj1m.cn/Article/details/gtgkuawumx.html

TS:   // 手写 Map<string, number>
来源：http://dali.fzhhl.top/Article/details/gthalbohqf.html

Java: // 手写 HashMap
来源：http://dali.yvedp.cn/Article/details/gtctpzhvgh.html

Go:   // 手写 map[int]int
来源：http://dali.mhx1999.top/Article/details/gtxuclaiqj.html

Ruby: // 手写 Hash
来源：http://dali.yongpay.top/Article/details/gtocjbbhgl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dianchejie.cn/Article/details/gtdomqhcat.html

[N08] 生成全排列
来源：http://dali.yongpay.top/Article/details/gtldjjflfn.html

Py:   itertools.permutations(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtqehxtxsz.html

PHP:  // 手写递归交换
来源：http://dali.jyoumei.cn/Article/details/gtbotyppyo.html

JS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtwxnggtdt.html

TS:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtyebhrtaj.html

Java: // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtvmmglcft.html

Go:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtvfaaaflv.html

Ruby: arr.permutation.to_a
来源：http://dali.cheryme.top/Article/details/gtvbuaefgn.html

C#:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtyjeerwyu.html

[N09] 栈与队列
来源：http://dali.dashuyun.cn/Article/details/gttpscbfjv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gogol.net.cn/Article/details/gtsqoodgas.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gtaeymguyn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtjngqxifg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cashguo.top/Article/details/gtbxjxhwbe.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gogol.net.cn/Article/details/gtaombrvlj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangshuangyany.cn/Article/details/gtizeibowt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtgvpalzag.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.fzhhl.top/Article/details/gtrnlsrycd.html

[N10] 链表节点定义
来源：http://dali.yonumen.top/Article/details/gtnnqalbgm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.birdmap.top/Article/details/gtyhnqdmns.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ehwqpu.com/Article/details/gtlrxfgiau.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtxuqqmrdo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.aibaodan.cn/Article/details/gtbyxqbzsv.html

Java: class Node { int v; Node next; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctizsrai.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.9152youxi.cn/Article/details/gttxhrdlxo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yonumen.top/Article/details/gtncbdgvwe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ivvv.top/Article/details/gteekiyong.html

[N11] 二叉树中序遍历
来源：http://dali.sweek.top/Article/details/gtqfptzhkv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jyoumei.cn/Article/details/gtnjuujcli.html

PHP:  // 手写递归函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpiueufs.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gtykbfvlrj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shzxlz.cn/Article/details/gttlqikhgy.html

Java: // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtyrlsecnr.html

Go:   // 手写递归
来源：http://dali.birdmap.top/Article/details/gtxptjssmb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jlsjyb.cn/Article/details/gtbsybtbkr.html

C#:   // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gtglzokwlg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhixingplan.top/Article/details/gtzsnwajpy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.iojbl.cn/Article/details/gtcbivtjvo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gzhubu.top/Article/details/gtaouoieva.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gtjskcoflq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gtglnyxmpu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gtomslmptt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenjidiqi.icu/Article/details/gtybitvldt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xinyue.icu/Article/details/gtgvabgyyb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gtsxvyxmne.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtfxfwsbks.html

O. 并发与异步
来源：http://dali.iojbl.cn/Article/details/gtstuuneam.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtptpeotkl.html

[O01] 启动一个线程
来源：http://dali.smart0.xyz/Article/details/gtsgpyfjfx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gaohongyu789.top/Article/details/gtanigvprd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.pycfn.com/Article/details/gtpmgycxjc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xinyue.icu/Article/details/gtgzhercuw.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gteayhxhsc.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhongyouzk.top/Article/details/gtugwzktnp.html

Go:   go f()
来源：http://dali.quarkkingdee.top/Article/details/gtlcwlqdev.html

Ruby: Thread.new { f }
来源：http://dali.kuanghao11.cn/Article/details/gtnbydrlwk.html

C#:   Task.Run(() => F());
来源：http://dali.cashguo.top/Article/details/gtalfmnecy.html

[O02] 使用线程池
来源：http://dali.hfpthk.cn/Article/details/gtocrniehp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjwnbjjs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tian-w.cn/Article/details/gtqrpyvrkq.html

JS:   // worker_threads 线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxggvzqw.html

TS:   // worker_threads 线程池
来源：http://dali.hammf.cn/Article/details/gtzcuwbpom.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xinyue.icu/Article/details/gtibflutbb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuxming.cn/Article/details/gttjffwbug.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.kuanghao11.cn/Article/details/gtpmmqkmnm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tianlin.xyz/Article/details/gtattmcobh.html

[O03] 加锁保护共享数据
来源：http://dali.xuanzx.com/Article/details/gtyayagmat.html

Py:   with lock: shared += 1
来源：http://dali.ehwqpu.com/Article/details/gtbdkjnold.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cucudq.cn/Article/details/gtzziafyse.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shangyingyoupin.top/Article/details/gtqfurkyiz.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gttxexrwhe.html

Java: synchronized (this) { shared++; }
来源：http://dali.yonumen.top/Article/details/gtovtoesji.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgfzy.top/Article/details/gtywncgape.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.birdmap.top/Article/details/gtalnhsjuk.html

C#:   lock (gate) { shared++; }
来源：http://dali.cheryme.top/Article/details/gtucwjhiam.html

[O04] 定义异步函数并等待
来源：http://dali.xuanzx.com/Article/details/gtwukzegko.html

Py:   async def f():⏎    await g()
来源：http://dali.hywenlv.cn/Article/details/gtqvfvhcqv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xziqi.cn/Article/details/gtblzgvwbh.html

JS:   async function f() { await g(); }
来源：http://dali.xuanzx.com/Article/details/gtkovjjmzg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.vqdsnc.cn/Article/details/gtiunkornw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zycfv.cn/Article/details/gtztolykro.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuanzhike.top/Article/details/gtdjixeujm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ydzc1.top/Article/details/gtouxisrcw.html

C#:   async Task F() { await G(); }
来源：http://dali.ybcxt.top/Article/details/gtfvpgyymy.html

[O05] 并发执行并等待全部完成
来源：http://dali.daxiang520.top/Article/details/gtbkrmqteu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.guowangkeji.top/Article/details/gtdsgvuahq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yvedp.cn/Article/details/gtmfwojrxb.html

JS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gtoqdhjjhg.html

TS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gtdprfniiv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ivvv.top/Article/details/gtsrzgmwhz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hongshengwenyu.top/Article/details/gtjwrdswpe.html

Ruby: threads.map(&:join)
来源：http://dali.yvedp.cn/Article/details/gtwscgctei.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hywenlv.cn/Article/details/gtyrydgznj.html

[O06] 使用进程池
来源：http://dali.gogol.net.cn/Article/details/gtzeeviira.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fzhhl.top/Article/details/gtlzcmuepe.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nanxinkj.top/Article/details/gtfeefwzms.html

JS:   // child_process / cluster 模块
来源：http://dali.zhongyouzk.top/Article/details/gtdvwdwxjq.html

TS:   // child_process / cluster 模块
来源：http://dali.andypj.xyz/Article/details/gtjgdcjrqb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenzaomai.com/Article/details/gtocrgimqu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hfpthk.cn/Article/details/gtecnpynwz.html

Ruby: // fork 块
来源：http://dali.daxiang520.top/Article/details/gtjeyncepo.html

C#:   Parallel.For
来源：http://dali.chenzaomai.com/Article/details/gtwbifcekk.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtqhiprtbe.html

P. 常用工具函数
来源：http://dali.pengpengdd.cyou/Article/details/gtcdjqzxay.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtreleypub.html

[P01] 生成 UUID
来源：http://dali.pycfn.com/Article/details/gthmsxpwrv.html

Py:   str(uuid.uuid4())
来源：http://dali.0kj1m.cn/Article/details/gtkswlezar.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ehwqpu.com/Article/details/gtlplrholv.html

JS:   crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gtioropnev.html

TS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtakedzvct.html

Java: UUID.randomUUID().toString()
来源：http://dali.aibaodan.cn/Article/details/gtdeoolxxa.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hammf.cn/Article/details/gtsvciqbid.html

Ruby: SecureRandom.uuid
来源：http://dali.xylfe.cn/Article/details/gtkaylejvz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pengpengdd.cyou/Article/details/gtekfbcoea.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tianlin.xyz/Article/details/gtlowakixn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.birdmap.top/Article/details/gtcrzzebja.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fzhhl.top/Article/details/gtttnlwloq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.iojbl.cn/Article/details/gtyfdfnksh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gotoacloud.top/Article/details/gtpamniqpo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zycfv.cn/Article/details/gtcjjctbhk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ydzc1.top/Article/details/gtshmeqcyw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258888.top/Article/details/gtmvpsfcly.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shuidangran.top/Article/details/gttuypemzr.html

[P03] 生成短随机字符串
来源：http://dali.fengsongda.top/Article/details/gtleitvoiq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.dashuyun.cn/Article/details/gtjxzvsoyt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.wangshuangyany.cn/Article/details/gtuvvynbwg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gttrhtayjy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cucudq.cn/Article/details/gtfnjjrasz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sxryk.cn/Article/details/gtnjdywcxc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj202588.top/Article/details/gtuepaobxk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.snrcjt.cn/Article/details/gtyvqozfea.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgufenzy.top/Article/details/gtagfsoecz.html

[P04] 求长度
来源：http://dali.zhengqikj.top/Article/details/gtxrwqodcs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj202588.top/Article/details/gthlfgwxju.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtkqhlymlo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gtwomdosed.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gthbgjpodo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jianghu66.top/Article/details/gtooekzgfi.html

Go:   len(arr);  len(m)
来源：http://dali.guowangkeji.top/Article/details/gtuvcostgw.html

Ruby: x.length;  x.size
来源：http://dali.0kj1m.cn/Article/details/gtwdcislac.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.meibo888.top/Article/details/gtauycfefb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cashguo.top/Article/details/gtevibntil.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbmqibvg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cdnleiting.top/Article/details/gtzvshjnbi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yonumen.top/Article/details/gtibdrvztn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yonumen.top/Article/details/gtnauiugau.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yongpay.top/Article/details/gtzlszfdxg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtbnuezsiv.html

Ruby: a == b
来源：http://dali.feifeiyinyue.top/Article/details/gtxsipwvat.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cqqwz.cn/Article/details/gtmpzmhoan.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.daxiang520.top/Article/details/gtgqwjseol.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hysaishi.cn/Article/details/gtvfdviygu.html

PHP:  if (empty($x)) {}
来源：http://dali.cashguo.top/Article/details/gthpfrhfft.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hfpthk.cn/Article/details/gtkjemqbfy.html

TS:   if (x == null) {}
来源：http://dali.zhoulong.xyz/Article/details/gtqcunleaj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gtggkldoce.html

Go:   if x == nil {}
来源：http://dali.vqdsnc.cn/Article/details/gtjgtiwyfw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsshovczn.html

C#:   if (x is null) {}
来源：http://dali.ydzc1.top/Article/details/gtdtybthts.html

[P07] 防抖与节流
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpbxjoor.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gogol.net.cn/Article/details/gtvmmhsgbc.html

PHP:  // 手写时间戳比较
来源：http://dali.pycfn.com/Article/details/gtjwmzgtck.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gtggveuzec.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtyucetzki.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yuanzhike.top/Article/details/gtfhslnlvz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigfzy.top/Article/details/gtqlibtbkd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tianlin.xyz/Article/details/gtgetdbhqp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sysykeji.top/Article/details/gtceujifkn.html

[P08] 处理浮点精度问题
来源：http://dali.ybcxt.top/Article/details/gttprrphwx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.guannengcc.top/Article/details/gttlowcdlg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sweek.top/Article/details/gtzwnejaly.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cashguo.top/Article/details/gtfblbvhjq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shuidangran.top/Article/details/gtmwsvksyw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sxryk.cn/Article/details/gtofseettw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jianghu66.top/Article/details/gtsddkajbb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yueranfly.top/Article/details/gtbsfyngoo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ppjwa.cn/Article/details/gtynpsovxj.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtjyhweicv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhoulong.xyz/Article/details/gtceipowon.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtdbwluecd.html

[Q01] 创建表
来源：http://dali.xylfe.cn/Article/details/gtdwnxexye.html

CREATE TABLE users (
来源：http://dali.jqgufenzy.top/Article/details/gtaxluzqoa.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gtimmgqmim.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yongpay.top/Article/details/gtljvdismp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gogol.net.cn/Article/details/gtgqzvasql.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhoulong.xyz/Article/details/gtoapdffih.html

);
来源：http://dali.yongpay.top/Article/details/gthycxyroe.html

[Q02] 创建带外键的表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgwbuejk.html

CREATE TABLE orders (
来源：http://dali.yj20258.top/Article/details/gtznstipms.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gtvbpfpblz.html

user_id INT NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gthsrjjysk.html

amount DECIMAL(10, 2),
来源：http://dali.kuanghao11.cn/Article/details/gthagoxmrl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajhhabgp.html

);
来源：http://dali.hnqzz.top/Article/details/gtmoticgsn.html

[Q03] 增加列
来源：http://dali.ppjwa.cn/Article/details/gtlmcbpvok.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sysykeji.top/Article/details/gtvpunrkha.html

[Q04] 修改列类型
来源：http://dali.dianchejie.cn/Article/details/gtgdldcdks.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhixingplan.top/Article/details/gthmyzhjbv.html

[Q05] 重命名列
来源：http://dali.ivvv.top/Article/details/gtrfrrbuwe.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dashuyun.cn/Article/details/gtcvyhrlvz.html

[Q06] 删除列
来源：http://dali.hnqzz.top/Article/details/gtgxojlyaw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yangfankeji.com/Article/details/gtsirwnsvb.html

[Q07] 删除表
来源：http://dali.hongshengwenyu.top/Article/details/gtwcusyvpv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.dashuyun.cn/Article/details/gtcamvkqvs.html

[Q08] 创建普通索引
来源：http://dali.jyoumei.cn/Article/details/gtejckoewn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gteqqhcxpt.html

[Q09] 创建唯一索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtzyaugy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gtwfxkdskc.html

[Q10] 插入单行
来源：http://dali.cqqwz.cn/Article/details/gtvokocxey.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpcxoblin.html

[Q11] 一次插入多行
来源：http://dali.guowangkeji.top/Article/details/gtvoymngvo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cucudq.cn/Article/details/gtbwtficgh.html

[Q12] 插入后取自增 ID
来源：http://dali.xziqi.cn/Article/details/gtsgnldxae.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigfzy.top/Article/details/gtychraszu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gzhubu.top/Article/details/gtztnxzyrv.html

[Q13] 忽略重复插入
来源：http://dali.yj20258.top/Article/details/gthcjbgaij.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.haohaochexian.top/Article/details/gtjvamcgum.html

[Q14] 存在则更新（upsert）
来源：http://dali.jqgufenzy.top/Article/details/gtswxfjvyf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yuxming.cn/Article/details/gtsapuwyze.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenjidiqi.icu/Article/details/gtgrzgvzln.html

[Q15] 查询全部
来源：http://dali.nanxuanxn.top/Article/details/gtoohuzrhn.html

SELECT * FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtbptbrhbq.html

[Q16] 查询指定列
来源：http://dali.fzhhl.top/Article/details/gtolfyzmiv.html

SELECT id, name FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtnkwmgvnm.html

[Q17] 条件查询
来源：http://dali.zycfv.cn/Article/details/gtmuumrymz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.nwbrower.top/Article/details/gtypzrogws.html

[Q18] 模糊匹配
来源：http://dali.jiagoushi.top/Article/details/gtbehbugrk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.meibo888.top/Article/details/gtfbncccpj.html

[Q19] 范围查询
来源：http://dali.xuetiantiany.cn/Article/details/gtuekylxvz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pycfn.com/Article/details/gtbgzsaolt.html

[Q20] IN 列表
来源：http://dali.yuanzhike.top/Article/details/gtuvqvtxck.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtvwayefml.html

[Q21] 空值判断
来源：http://dali.yuxming.cn/Article/details/gtsvecielu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pycfn.com/Article/details/gtobsjsjds.html

[Q22] 排序
来源：http://dali.yuanzhike.top/Article/details/gtrtxzhqic.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xylfe.cn/Article/details/gtiquyadfa.html

[Q23] 分页
来源：http://dali.aibaodan.cn/Article/details/gtypbagkrm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.316326.xyz/Article/details/gtcjdtjgsm.html

[Q24] 去重
来源：http://dali.gaohongyu789.top/Article/details/gthqfzgoxi.html

SELECT DISTINCT city FROM users;
来源：http://dali.c1oappe.top/Article/details/gteodszzzx.html

[Q25] 只取前 N 条
来源：http://dali.sxryk.cn/Article/details/gtecwttrvh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.birdmap.top/Article/details/gtinypulhp.html

[Q26] 计数
来源：http://dali.ybcxt.top/Article/details/gtqmhrghak.html

SELECT COUNT(*) FROM users;
来源：http://dali.316326.xyz/Article/details/gtsjftjizd.html

[Q27] 条件计数
来源：http://dali.hammf.cn/Article/details/gtxuaifrsk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258.top/Article/details/gtwrneooqb.html

[Q28] 求和与平均
来源：http://dali.nwbrower.top/Article/details/gtkokyjsdh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtnmmyaccx.html

[Q29] 最大最小值
来源：http://dali.dashuyun.cn/Article/details/gtxztdvgkq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtvvyylvgj.html

[Q30] 分组统计
来源：http://dali.cqqwz.cn/Article/details/gtvhgmexos.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gtkuzfcjbf.html

[Q31] 分组后过滤
来源：http://dali.sufxvd.cn/Article/details/gtnntznxry.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.havefunace.top/Article/details/gttnmartbs.html

[Q32] 分组拼接字符串
来源：http://dali.yj202588.top/Article/details/gtemxstiex.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gtwswmoprt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuanzx.com/Article/details/gtknzlinye.html

[Q33] 多列分组
来源：http://dali.vqdsnc.cn/Article/details/gtshimtzyy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.iojbl.cn/Article/details/gtbifjfztd.html

[Q34] 每组取第一条
来源：http://dali.zhoulong.xyz/Article/details/gtxnstygmc.html

SELECT * FROM (
来源：http://dali.xuetiantiany.cn/Article/details/gtatvnxbwz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhixingplan.top/Article/details/gtffvxilhr.html

) t WHERE rn = 1;
来源：http://dali.bjfxy.top/Article/details/gtjptsdufl.html

[Q35] 内连接
来源：http://dali.zhongyouzk.top/Article/details/gtufainwwj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gtcfgyottc.html


<!-- 参考信息 -->