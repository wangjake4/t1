代发 wailian999

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fengsongda.top/Article/details/gtouearuwi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cdnleiting.top/Article/details/gteuqphirq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfpoqmoz.html

[N04] 斐波那契数列
来源：http://dali.xinyue.icu/Article/details/gtfbgqrzxv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gtebimfguo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258888.top/Article/details/gtcrksyarp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtsaglfsrk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gttfcynmur.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gtbzreenmb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.birdmap.top/Article/details/gtvofzpzwd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gtudjqpvxu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gtcnmgltum.html

[N05] 最大公约数
来源：http://dali.kuanghao11.cn/Article/details/gtzwdfmbpr.html

Py:   math.gcd(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtlzsqfyto.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yanxiufei.cn/Article/details/gtfxfoporo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gtyrlrnkwq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gtuqenvvqq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.bjfxy.top/Article/details/gtxghktrrk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ydzc1.top/Article/details/gtkuxrasqz.html

Ruby: a.gcd(b)
来源：http://dali.ppjwa.cn/Article/details/gtfzkhhgyd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fzhhl.top/Article/details/gtjxjuzpkn.html

[N06] 判断回文字符串
来源：http://dali.cdnleiting.top/Article/details/gthewbmcqd.html

Py:   s == s[::-1]
来源：http://dali.ybcxt.top/Article/details/gtsayowsny.html

PHP:  $s === strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gtstcjhxrk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtktuxxkqq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gteyiuevmj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xziqi.cn/Article/details/gtjqupbyom.html

Go:   // 双指针从两端比较
来源：http://dali.zhiwuduotai.top/Article/details/gtqmhknywk.html

Ruby: s == s.reverse
来源：http://dali.guowangkeji.top/Article/details/gtckpudyzh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gtiglfytek.html

[N07] 两数之和（返回下标）
来源：http://dali.haohaochexian.top/Article/details/gtlnlcmeiv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gzhubu.top/Article/details/gtgqymhyrf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhongyouzk.top/Article/details/gthsznwhpv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nwbrower.top/Article/details/gtthrxrbwv.html

TS:   // 手写 Map<string, number>
来源：http://dali.dashuyun.cn/Article/details/gtlwkelfux.html

Java: // 手写 HashMap
来源：http://dali.daxiang520.top/Article/details/gtqkilybon.html

Go:   // 手写 map[int]int
来源：http://dali.sysykeji.top/Article/details/gtmhbctnws.html

Ruby: // 手写 Hash
来源：http://dali.sxryk.cn/Article/details/gtedufuvmt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.meibo888.top/Article/details/gtcqhutblp.html

[N08] 生成全排列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnraglce.html

Py:   itertools.permutations(arr)
来源：http://dali.fengsongda.top/Article/details/gteotmpxor.html

PHP:  // 手写递归交换
来源：http://dali.316326.xyz/Article/details/gtfetvnzkl.html

JS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtxruvtpac.html

TS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtczhiyhtc.html

Java: // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gteodmcjsd.html

Go:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtonvhsext.html

Ruby: arr.permutation.to_a
来源：http://dali.xylfe.cn/Article/details/gtkkhygbqm.html

C#:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gteivnqitn.html

[N09] 栈与队列
来源：http://dali.shuidangran.top/Article/details/gtzkohkzcj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlncxnvzu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sysykeji.top/Article/details/gtfhelekxr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtxyvvbjnd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtauahkerq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxinkj.top/Article/details/gtivbbduwi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.redwolf501.top/Article/details/gtihabenpp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gtboqthsiw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sxryk.cn/Article/details/gtibzsdhqb.html

[N10] 链表节点定义
来源：http://dali.ppjwa.cn/Article/details/gtgoijequu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkoecxzg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.9152youxi.cn/Article/details/gtomrshvpt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhongyouzk.top/Article/details/gthqrsvngw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.pengpengdd.cyou/Article/details/gtppcglhmn.html

Java: class Node { int v; Node next; }
来源：http://dali.gaohongyu789.top/Article/details/gtwtbhpxce.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hnxiangtu.top/Article/details/gtbllztpip.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinqigfzy.top/Article/details/gtfovmwbtc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.smart0.xyz/Article/details/gtpsvnpcyy.html

[N11] 二叉树中序遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzeuiyssf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigufen.top/Article/details/gteixurpft.html

PHP:  // 手写递归函数
来源：http://dali.fengsongda.top/Article/details/gtgkkjtzyq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dianchejie.cn/Article/details/gtazkoqibi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gtazsiikgz.html

Java: // 手写递归
来源：http://dali.daria6918.cn/Article/details/gtebuonlox.html

Go:   // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gtodefrxse.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.dashuyun.cn/Article/details/gtvbywcvme.html

C#:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gtzxkhrbnf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jianghu66.top/Article/details/gtcscbajmk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yvedp.cn/Article/details/gtertejomi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenjidiqi.icu/Article/details/gtzblukjel.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fengsongda.top/Article/details/gthycflfbq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cucudq.cn/Article/details/gtmbokvogy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.0kj1m.cn/Article/details/gtllmszhye.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhixingplan.top/Article/details/gtxacmuhiz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hfpthk.cn/Article/details/gtalsrlfbn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gtrqooyuly.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtapzvmfbg.html

O. 并发与异步
来源：http://dali.nanxuanxn.top/Article/details/gtjvinukzj.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtelatkgde.html

[O01] 启动一个线程
来源：http://dali.xinyue.icu/Article/details/gtklubaluw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ehwqpu.com/Article/details/gteaihfazx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ehwqpu.com/Article/details/gtaoaasfmq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tanke756.top/Article/details/gtndwswotj.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gtwptyamvu.html

Java: new Thread(() -> f()).start()
来源：http://dali.gaohongyu789.top/Article/details/gtjuzndpph.html

Go:   go f()
来源：http://dali.xylfe.cn/Article/details/gtdsvijktw.html

Ruby: Thread.new { f }
来源：http://dali.jlsjyb.cn/Article/details/gtvzcgoclf.html

C#:   Task.Run(() => F());
来源：http://dali.bjfxy.top/Article/details/gtdjvwdpnw.html

[O02] 使用线程池
来源：http://dali.ehwqpu.com/Article/details/gthcvxtapi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.smart0.xyz/Article/details/gtcptosvga.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.svipenyu.cn/Article/details/gtkutvmpid.html

JS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gtjmbrcrsn.html

TS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gtzdivvytj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yongpay.top/Article/details/gtfmpbmwkq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ydzc1.top/Article/details/gtewzrqxwo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.wangshuangyany.cn/Article/details/gttqybkruf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.9152youxi.cn/Article/details/gtmtlqoaoy.html

[O03] 加锁保护共享数据
来源：http://dali.aibaodan.cn/Article/details/gtuxlskzyg.html

Py:   with lock: shared += 1
来源：http://dali.aizwys.cn/Article/details/gtecfepemw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.kuanghao11.cn/Article/details/gtqtmgbhyc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guannengcc.top/Article/details/gtlcbqznsv.html

TS:   // 同 JS
来源：http://dali.dashuyun.cn/Article/details/gtnlfiogra.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhengqikj.top/Article/details/gtvdhhrhno.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gaohongyu789.top/Article/details/gthfmigsex.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yonumen.top/Article/details/gtnfcylamu.html

C#:   lock (gate) { shared++; }
来源：http://dali.dianchejie.cn/Article/details/gtffaxqogx.html

[O04] 定义异步函数并等待
来源：http://dali.shangyingyoupin.top/Article/details/gtoycsdpqj.html

Py:   async def f():⏎    await g()
来源：http://dali.redwolf501.top/Article/details/gtydgftgts.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.redwolf501.top/Article/details/gtgnlarmzz.html

JS:   async function f() { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtolnxltfd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.havefunace.top/Article/details/gtgdokynbz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hammf.cn/Article/details/gtiiqsbknj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tanke756.top/Article/details/gtdlrahgnr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hywenlv.cn/Article/details/gtedozwjzn.html

C#:   async Task F() { await G(); }
来源：http://dali.birdmap.top/Article/details/gtjvfzfaop.html

[O05] 并发执行并等待全部完成
来源：http://dali.yuxming.cn/Article/details/gtbfquiwju.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tanke756.top/Article/details/gtdqvsssno.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yangfankeji.com/Article/details/gtwanqhdzn.html

JS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gtejziirff.html

TS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gtwatwhsyw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tanke756.top/Article/details/gtdkthugrs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.9152youxi.cn/Article/details/gtamckzoxu.html

Ruby: threads.map(&:join)
来源：http://dali.zycfv.cn/Article/details/gtfiybhnfl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgfzy.top/Article/details/gtmlwsuyct.html

[O06] 使用进程池
来源：http://dali.hammf.cn/Article/details/gtutrgbdgn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yongpay.top/Article/details/gtkmjpyqot.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.iojbl.cn/Article/details/gtqfcaaunj.html

JS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gtmbnjqqfi.html

TS:   // child_process / cluster 模块
来源：http://dali.xziqi.cn/Article/details/gthckpvudf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ivvv.top/Article/details/gtdduqlnyu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tanke756.top/Article/details/gtovfbbkna.html

Ruby: // fork 块
来源：http://dali.mhx1999.top/Article/details/gthtslwoet.html

C#:   Parallel.For
来源：http://dali.shuidangran.top/Article/details/gthpqmxpvv.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtfqaagdpu.html

P. 常用工具函数
来源：http://dali.daria6918.cn/Article/details/gtcxzmzphn.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtdqtfpgpj.html

[P01] 生成 UUID
来源：http://dali.hammf.cn/Article/details/gtwvhpzaig.html

Py:   str(uuid.uuid4())
来源：http://dali.tanke756.top/Article/details/gtoercmkrv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yuanzhike.top/Article/details/gtrsgxyrtb.html

JS:   crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgurskzbg.html

TS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gtjgwolldo.html

Java: UUID.randomUUID().toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtpfkbjupk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gaohongyu789.top/Article/details/gtcmsjvlvr.html

Ruby: SecureRandom.uuid
来源：http://dali.daxiang520.top/Article/details/gtxmjlkpss.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ppjwa.cn/Article/details/gtuxldfdah.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jianghu66.top/Article/details/gtempyptfr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sxryk.cn/Article/details/gtewnrcijv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daxiang520.top/Article/details/gttbrroejn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sufxvd.cn/Article/details/gtarzqfryy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.havefunace.top/Article/details/gtivzwtllt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpyoutofj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fzhhl.top/Article/details/gtqtadbyjy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttunejsfz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhengqikj.top/Article/details/gtuocecvqn.html

[P03] 生成短随机字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvobuqhw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinqigufen.top/Article/details/gtjviipfuu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tianlin.xyz/Article/details/gtnhwkjexb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gtwejdhgbd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gtyukhacwt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sysykeji.top/Article/details/gtdcrsfoqf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guannengcc.top/Article/details/gtjrnnqdcu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.smart0.xyz/Article/details/gtddiicbif.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ydzc1.top/Article/details/gtwkkhzula.html

[P04] 求长度
来源：http://dali.sweek.top/Article/details/gthmjabkbo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.fzhhl.top/Article/details/gtufaraezb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtykqwxlob.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuanzx.com/Article/details/gttqtsbtkt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gtikgliqii.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gttgojoctz.html

Go:   len(arr);  len(m)
来源：http://dali.jqgfzy.top/Article/details/gthxozqjcl.html

Ruby: x.length;  x.size
来源：http://dali.kuanghao11.cn/Article/details/gtxatjckxk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gtqzbgrjxh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guannengcc.top/Article/details/gtaoyvufia.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwouytue.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xylfe.cn/Article/details/gtmmkrrpsi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gtfnruyefl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guannengcc.top/Article/details/gtkggljhbx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hysaishi.cn/Article/details/gttqzwzulo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xylfe.cn/Article/details/gtxqviwrau.html

Ruby: a == b
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhbqnacl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ehwqpu.com/Article/details/gtcgqppfee.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xuanzx.com/Article/details/gtnlnknfee.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xinyue.icu/Article/details/gtwnoqgxli.html

PHP:  if (empty($x)) {}
来源：http://dali.guowangkeji.top/Article/details/gtdvndrnmt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tian-w.cn/Article/details/gtkswjcsfi.html

TS:   if (x == null) {}
来源：http://dali.cashguo.top/Article/details/gtolxmfjfj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gtpteahbhv.html

Go:   if x == nil {}
来源：http://dali.jiagoushi.top/Article/details/gtvdshzdua.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xylfe.cn/Article/details/gtgedxjjqo.html

C#:   if (x is null) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewpraazo.html

[P07] 防抖与节流
来源：http://dali.mhx1999.top/Article/details/gthdyawugn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsyplzhxf.html

PHP:  // 手写时间戳比较
来源：http://dali.xylfe.cn/Article/details/gtxirdybch.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gtubqnsqqn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gtvykmrevv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtvoqxfvxu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.redwolf501.top/Article/details/gtkgtrvmcc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcvegxzn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.havefunace.top/Article/details/gtbamfpxdb.html

[P08] 处理浮点精度问题
来源：http://dali.ehwqpu.com/Article/details/gtehpdgluc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jyoumei.cn/Article/details/gtdhehvxru.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nwbrower.top/Article/details/gtrrdtsyzd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.iojbl.cn/Article/details/gtissximfh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgufenzy.top/Article/details/gtuazfvymn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcoxzyod.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.smart0.xyz/Article/details/gtrpqgdfwv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.birdmap.top/Article/details/gtyzkbdxkz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.wangdashe.top/Article/details/gthfjrucrv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwliuawyo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guannengcc.top/Article/details/gtepkuavak.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtsfmasqsk.html

[Q01] 创建表
来源：http://dali.cdnleiting.top/Article/details/gtsejnhjhs.html

CREATE TABLE users (
来源：http://dali.yangfankeji.com/Article/details/gttukuzjiu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sweek.top/Article/details/gtkpckrabq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj202588.top/Article/details/gtixzzvbmu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zdqjudy.top/Article/details/gtzhvzcfrj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ppjwa.cn/Article/details/gtuakxktxo.html

);
来源：http://dali.gotoacloud.top/Article/details/gtzgohnjjb.html

[Q02] 创建带外键的表
来源：http://dali.hnxiangtu.top/Article/details/gtioncilyi.html

CREATE TABLE orders (
来源：http://dali.fengsongda.top/Article/details/gtbsitever.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gtsaryzzih.html

user_id INT NOT NULL,
来源：http://dali.yj20258888.top/Article/details/gtunorvtmt.html

amount DECIMAL(10, 2),
来源：http://dali.jqgfzy.top/Article/details/gtzmgyasbg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shzxlz.cn/Article/details/gttmxfzpnh.html

);
来源：http://dali.redwolf501.top/Article/details/gtvckkkell.html

[Q03] 增加列
来源：http://dali.meibo888.top/Article/details/gtppwkeusm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sufxvd.cn/Article/details/gthdubeyjn.html

[Q04] 修改列类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljgrdcpp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gaohongyu789.top/Article/details/gtubwqtfcf.html

[Q05] 重命名列
来源：http://dali.feifeiyinyue.top/Article/details/gtjbdteznn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrquvkjuj.html

[Q06] 删除列
来源：http://dali.gzhubu.top/Article/details/gtxstwwnzh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkgsngym.html

[Q07] 删除表
来源：http://dali.shuidangran.top/Article/details/gtvzlmidcq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gaohongyu789.top/Article/details/gtknjhehad.html

[Q08] 创建普通索引
来源：http://dali.zhixingplan.top/Article/details/gtvrztbeln.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinqigfzy.top/Article/details/gtanjwfjlu.html

[Q09] 创建唯一索引
来源：http://dali.daria6918.cn/Article/details/gtpnpfhrip.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gteauvqgxq.html

[Q10] 插入单行
来源：http://dali.sxryk.cn/Article/details/gtfpivroif.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gtchybugzj.html

[Q11] 一次插入多行
来源：http://dali.chenzaomai.com/Article/details/gtrxuyoecy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gzhubu.top/Article/details/gtzbxkmmuy.html

[Q12] 插入后取自增 ID
来源：http://dali.gaohongyu789.top/Article/details/gtlmxjbmzt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.dashuyun.cn/Article/details/gtquzpcfas.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hysaishi.cn/Article/details/gtkbjxnftz.html

[Q13] 忽略重复插入
来源：http://dali.xziqi.cn/Article/details/gtcszmjjgy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gtnhuiqyks.html

[Q14] 存在则更新（upsert）
来源：http://dali.aizwys.cn/Article/details/gtficgvehu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ydzc1.top/Article/details/gtszblmzll.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.316326.xyz/Article/details/gtpgsawecm.html

[Q15] 查询全部
来源：http://dali.svipenyu.cn/Article/details/gtgzhkxlfe.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtfvnlupxa.html

[Q16] 查询指定列
来源：http://dali.zhoulong.xyz/Article/details/gtwnyttkws.html

SELECT id, name FROM users;
来源：http://dali.havefunace.top/Article/details/gtjxcslxwh.html

[Q17] 条件查询
来源：http://dali.gzhubu.top/Article/details/gtpehtwhtw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guannengcc.top/Article/details/gtuwqggjtb.html

[Q18] 模糊匹配
来源：http://dali.nanxuanxn.top/Article/details/gtkkttghps.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pengpengdd.cyou/Article/details/gtbfwoifis.html

[Q19] 范围查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjyqufvgk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenzaomai.com/Article/details/gtrwjnsmtu.html

[Q20] IN 列表
来源：http://dali.shuidangran.top/Article/details/gtiwgyulry.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cqqwz.cn/Article/details/gtbxcncvzc.html

[Q21] 空值判断
来源：http://dali.xuanzx.com/Article/details/gtklkzwpbt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.daria6918.cn/Article/details/gtqpbvwjux.html

[Q22] 排序
来源：http://dali.ydzc1.top/Article/details/gthettcxml.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.dashuyun.cn/Article/details/gtjxdkxajx.html

[Q23] 分页
来源：http://dali.dianchejie.cn/Article/details/gturbcsylm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj20258888.top/Article/details/gtfnymebtd.html

[Q24] 去重
来源：http://dali.ppjwa.cn/Article/details/gthehiqgld.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtdefspqxq.html

[Q25] 只取前 N 条
来源：http://dali.xuetiantiany.cn/Article/details/gtvzmeekqg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tianlin.xyz/Article/details/gtxcqsxqte.html

[Q26] 计数
来源：http://dali.hammf.cn/Article/details/gtlbnmecxr.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258.top/Article/details/gtvdazkwel.html

[Q27] 条件计数
来源：http://dali.shanyushiyangtech.top/Article/details/gtqodemoda.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj202588.top/Article/details/gtngcyrhfe.html

[Q28] 求和与平均
来源：http://dali.sweek.top/Article/details/gtjhnqdfuq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtnkkdjick.html

[Q29] 最大最小值
来源：http://dali.quarkkingdee.top/Article/details/gtbefwqken.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtvbbtydkx.html

[Q30] 分组统计
来源：http://dali.hywenlv.cn/Article/details/gtoccxjyml.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtsxhmgxil.html

[Q31] 分组后过滤
来源：http://dali.yvedp.cn/Article/details/gtkoryxumj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sxryk.cn/Article/details/gtlhuawwra.html

[Q32] 分组拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gtmrhwjpqd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtavrtkvfm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xinyue.icu/Article/details/gtbfhaxkxa.html

[Q33] 多列分组
来源：http://dali.cashguo.top/Article/details/gtanoijgjm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hongshengwenyu.top/Article/details/gtgztduqxz.html

[Q34] 每组取第一条
来源：http://dali.yj20258888.top/Article/details/gtyhfdrxjw.html

SELECT * FROM (
来源：http://dali.nanxinkj.top/Article/details/gtcuhkhbhh.html


<!-- 参考信息 -->