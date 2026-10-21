代发 wailian999

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guowangkeji.top/Article/details/gtooxhojje.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daria6918.cn/Article/details/gtljywdkkr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.c1oappe.top/Article/details/gtrwjslfze.html

[N04] 斐波那契数列
来源：http://dali.hywenlv.cn/Article/details/gtisrewzku.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkayyswg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gttxulkgms.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gtuxtpnlmo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtnzflpjsu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ydzc1.top/Article/details/gtpnkmbofm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfkcndkvn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gtetecxgda.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gtyjwwhzog.html

[N05] 最大公约数
来源：http://dali.zhiwuduotai.top/Article/details/gtabssoito.html

Py:   math.gcd(a, b)
来源：http://dali.havefunace.top/Article/details/gtsvpqblhj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jyoumei.cn/Article/details/gtqynrwujk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gtexajomza.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gtwlzvutys.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ivvv.top/Article/details/gtgcovmkfy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yangfankeji.com/Article/details/gtzjzdrdrt.html

Ruby: a.gcd(b)
来源：http://dali.ehwqpu.com/Article/details/gtjwsowbot.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tanke756.top/Article/details/gtmmcrjsmy.html

[N06] 判断回文字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtauuaiobw.html

Py:   s == s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gtqzeiwlhw.html

PHP:  $s === strrev($s);
来源：http://dali.zycfv.cn/Article/details/gtacqucubk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtobiqdfoj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtxoipwskc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gtskgfjfpk.html

Go:   // 双指针从两端比较
来源：http://dali.fzhhl.top/Article/details/gtwgahyyyr.html

Ruby: s == s.reverse
来源：http://dali.cashguo.top/Article/details/gtliaefkfs.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gtgrovbyba.html

[N07] 两数之和（返回下标）
来源：http://dali.guannengcc.top/Article/details/gtydivaaaq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.svipenyu.cn/Article/details/gtjhdstgaf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ydzc1.top/Article/details/gtdsdjnmam.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigfzy.top/Article/details/gthtlxkhoy.html

TS:   // 手写 Map<string, number>
来源：http://dali.hysaishi.cn/Article/details/gtionkkfqx.html

Java: // 手写 HashMap
来源：http://dali.cqqwz.cn/Article/details/gtbpqfltxg.html

Go:   // 手写 map[int]int
来源：http://dali.yangfankeji.com/Article/details/gtvsfmavtt.html

Ruby: // 手写 Hash
来源：http://dali.tanke756.top/Article/details/gtluvjkcnp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gotoacloud.top/Article/details/gthbvxxigs.html

[N08] 生成全排列
来源：http://dali.jqgfzy.top/Article/details/gtxijpawxg.html

Py:   itertools.permutations(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtbkjszzcn.html

PHP:  // 手写递归交换
来源：http://dali.smart0.xyz/Article/details/gtvwxpwiqf.html

JS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtqfitnbhq.html

TS:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtaicizxjc.html

Java: // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtywodzyez.html

Go:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtsvnkiamv.html

Ruby: arr.permutation.to_a
来源：http://dali.gzhubu.top/Article/details/gtjynlijfq.html

C#:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtwnfradzp.html

[N09] 栈与队列
来源：http://dali.bjfxy.top/Article/details/gtxzrmwcja.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.bjfxy.top/Article/details/gtulyanlwd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmcjcjsjr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtidzptadp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.svipenyu.cn/Article/details/gtralwcrik.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xinyue.icu/Article/details/gtewsyzwwr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gogol.net.cn/Article/details/gtoxnfgljl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gttuzifpny.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yuanzhike.top/Article/details/gtdhdrpwwx.html

[N10] 链表节点定义
来源：http://dali.vqdsnc.cn/Article/details/gtoqdfsgfm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.0kj1m.cn/Article/details/gtbuqitaiy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xziqi.cn/Article/details/gtyqpwunlt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ehwqpu.com/Article/details/gtxufzigkf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.birdmap.top/Article/details/gtonjlxgry.html

Java: class Node { int v; Node next; }
来源：http://dali.cashguo.top/Article/details/gtrynbygme.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258.top/Article/details/gtrykiznag.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmpleuzm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ppjwa.cn/Article/details/gtcggumnsz.html

[N11] 二叉树中序遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtfbxcnguv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.havefunace.top/Article/details/gtbqrufkbv.html

PHP:  // 手写递归函数
来源：http://dali.tianlin.xyz/Article/details/gtemitunkd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.vqdsnc.cn/Article/details/gtcbtcmtpv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gtzbcdtxix.html

Java: // 手写递归
来源：http://dali.fzhhl.top/Article/details/gtvviinwqr.html

Go:   // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gtnennnrys.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yonumen.top/Article/details/gtgodidopp.html

C#:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gtymikqzze.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gzhubu.top/Article/details/gtfwketjtn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaavxvtwl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinghuilouyu.cn/Article/details/gtbiousoud.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gtecvcyqyw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgfzy.top/Article/details/gtrtejyaat.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuksvdggz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hammf.cn/Article/details/gtsguisddc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gtaeykuaor.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gtlfiwfvsk.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtgygkmqwk.html

O. 并发与异步
来源：http://dali.nanxuanxn.top/Article/details/gtkdrykkgd.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtglflcser.html

[O01] 启动一个线程
来源：http://dali.jlsjyb.cn/Article/details/gtsdhujvzj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhiwuduotai.top/Article/details/gtjpszzpfw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhoulong.xyz/Article/details/gtpbtfzmxu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenzaomai.com/Article/details/gtqstlegfc.html

TS:   // 同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gthlanftcz.html

Java: new Thread(() -> f()).start()
来源：http://dali.guowangkeji.top/Article/details/gtajlpkaba.html

Go:   go f()
来源：http://dali.ehwqpu.com/Article/details/gtbvjusggz.html

Ruby: Thread.new { f }
来源：http://dali.yanxiufei.cn/Article/details/gtsgibrten.html

C#:   Task.Run(() => F());
来源：http://dali.iojbl.cn/Article/details/gtwlmsksrm.html

[O02] 使用线程池
来源：http://dali.jyoumei.cn/Article/details/gtvvzciurs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gogol.net.cn/Article/details/gtiagaiovp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.vqdsnc.cn/Article/details/gtfjrfnimo.html

JS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gtfkgfkzok.html

TS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gtyhelfbev.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.pycfn.com/Article/details/gtezfopqqn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sufxvd.cn/Article/details/gtwzzfnlsl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxwcgdoe.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdovpavnq.html

[O03] 加锁保护共享数据
来源：http://dali.guannengcc.top/Article/details/gtefhvsozw.html

Py:   with lock: shared += 1
来源：http://dali.yonumen.top/Article/details/gtjckpwhms.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.feifeiyinyue.top/Article/details/gtfvmxasbd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.9152youxi.cn/Article/details/gttcqjtxjm.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gtfotmokwa.html

Java: synchronized (this) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gtltwfkhnh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.kuanghao11.cn/Article/details/gtgnfmghmp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.aibaodan.cn/Article/details/gtaavmkdpf.html

C#:   lock (gate) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gtdgjhsbvc.html

[O04] 定义异步函数并等待
来源：http://dali.yueranfly.top/Article/details/gtobmcscwm.html

Py:   async def f():⏎    await g()
来源：http://dali.cqqwz.cn/Article/details/gtbjeqdxzc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yangfankeji.com/Article/details/gtgdiesown.html

JS:   async function f() { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gtbyynnaor.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.andypj.xyz/Article/details/gthlhczyxe.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ydzc1.top/Article/details/gtbtqqtkbv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.c1oappe.top/Article/details/gtkbobpsxl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhengqikj.top/Article/details/gtnnobwcfl.html

C#:   async Task F() { await G(); }
来源：http://dali.yuxming.cn/Article/details/gtyatbjvyu.html

[O05] 并发执行并等待全部完成
来源：http://dali.yueranfly.top/Article/details/gtxvkpufez.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtjjvlwpmn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yanxiufei.cn/Article/details/gtyumylkso.html

JS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gtumcvlogb.html

TS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gtmsoryoji.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cashguo.top/Article/details/gtdtvnbedh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gogol.net.cn/Article/details/gtourebgnc.html

Ruby: threads.map(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gtigbdjphw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shuidangran.top/Article/details/gtowrmvlkl.html

[O06] 使用进程池
来源：http://dali.zycfv.cn/Article/details/gtmapglnsq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fengsongda.top/Article/details/gtyyygzhzl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhiwuduotai.top/Article/details/gtwrpmtpkl.html

JS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gtedbnhrhm.html

TS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gtgssrahmd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ivvv.top/Article/details/gtejrjwcoo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tanke756.top/Article/details/gtmtjedtld.html

Ruby: // fork 块
来源：http://dali.aibaodan.cn/Article/details/gtiheruipq.html

C#:   Parallel.For
来源：http://dali.jqgufenzy.top/Article/details/gtyanwptpy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtverbqjmp.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gtdhugchmh.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtjmexgbeo.html

[P01] 生成 UUID
来源：http://dali.xuetiantiany.cn/Article/details/gtocevdsjl.html

Py:   str(uuid.uuid4())
来源：http://dali.hammf.cn/Article/details/gtijwdahiq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.pengpengdd.cyou/Article/details/gtjzudjlpt.html

JS:   crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gtrjxkvmei.html

TS:   crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gtvfsuecui.html

Java: UUID.randomUUID().toString()
来源：http://dali.ydzc1.top/Article/details/gtlkvmnbfj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.kuanghao11.cn/Article/details/gtdlexljol.html

Ruby: SecureRandom.uuid
来源：http://dali.meibo888.top/Article/details/gtgfwcsrtt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenjidiqi.icu/Article/details/gtesqjiaug.html

[P02] MD5 / SHA256 摘要
来源：http://dali.andypj.xyz/Article/details/gtsjgkmubk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfdvtnok.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatfutsxu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.birdmap.top/Article/details/gtmqcrjguv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guannengcc.top/Article/details/gtascugpxd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hammf.cn/Article/details/gtivpfldmj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhixingplan.top/Article/details/gttvivlsgm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tianlin.xyz/Article/details/gtvruwfarb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ehwqpu.com/Article/details/gtkfujtyiy.html

[P03] 生成短随机字符串
来源：http://dali.ydzc1.top/Article/details/gtlkfvjezs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.daxiang520.top/Article/details/gtzoncqxpw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.svipenyu.cn/Article/details/gtfqzazuhz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gtzajulipk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dashuyun.cn/Article/details/gtsuvbvuck.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yueranfly.top/Article/details/gtnzwffrxs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tianlin.xyz/Article/details/gtayunzefn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhiwuduotai.top/Article/details/gtjuykiocn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fengsongda.top/Article/details/gtmuzblbzi.html

[P04] 求长度
来源：http://dali.jlsjyb.cn/Article/details/gtbbajnanb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhiwuduotai.top/Article/details/gtkfqioebh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gtlijvgisj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuetiantiany.cn/Article/details/gtjwverkhv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daxiang520.top/Article/details/gtyxnzflny.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gtisiptbbk.html

Go:   len(arr);  len(m)
来源：http://dali.yueranfly.top/Article/details/gteokoktkw.html

Ruby: x.length;  x.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqoghuxu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hysaishi.cn/Article/details/gtchubmevh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.smart0.xyz/Article/details/gtvwgecssu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daria6918.cn/Article/details/gtrdecjbih.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xinyue.icu/Article/details/gtslwvrply.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.haohaochexian.top/Article/details/gtjyxufioc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhoulong.xyz/Article/details/gtnryumoxk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.birdmap.top/Article/details/gtplqpdtug.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gtmanbwsny.html

Ruby: a == b
来源：http://dali.vqdsnc.cn/Article/details/gtegjgckes.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258.top/Article/details/gtxecjxojl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.dashuyun.cn/Article/details/gtehclkata.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.guowangkeji.top/Article/details/gtccdyejcg.html

PHP:  if (empty($x)) {}
来源：http://dali.yonumen.top/Article/details/gtiqujipyt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sweek.top/Article/details/gtstccwfzi.html

TS:   if (x == null) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtmjdlcdsk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gtubjgzcjz.html

Go:   if x == nil {}
来源：http://dali.yuxming.cn/Article/details/gtbjojjshm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jiagoushi.top/Article/details/gtoshmlfir.html

C#:   if (x is null) {}
来源：http://dali.meibo888.top/Article/details/gtzgoiwbvd.html

[P07] 防抖与节流
来源：http://dali.316326.xyz/Article/details/gteupgntfu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhengqikj.top/Article/details/gtgfzwbcfq.html

PHP:  // 手写时间戳比较
来源：http://dali.hnxiangtu.top/Article/details/gtpmsvzcan.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gtfsavkkwa.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gtelurvmqr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhixingplan.top/Article/details/gtpqfwtazd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhixingplan.top/Article/details/gtrqcilpxj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tian-w.cn/Article/details/gtjhibbbka.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fengsongda.top/Article/details/gtowfgkxlq.html

[P08] 处理浮点精度问题
来源：http://dali.tian-w.cn/Article/details/gtrnxlclil.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fengsongda.top/Article/details/gthjenxvdd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.andypj.xyz/Article/details/gtwqrcnapc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jqgfzy.top/Article/details/gtbxesqxfa.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jlsjyb.cn/Article/details/gtimknpvln.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.andypj.xyz/Article/details/gtfsmfjehb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.feifeiyinyue.top/Article/details/gtggumonjq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jiagoushi.top/Article/details/gtwacvakfg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yonumen.top/Article/details/gtgmnxbhmf.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtpgmsbivv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.svipenyu.cn/Article/details/gtlpvjacmv.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtiakmnlgz.html

[Q01] 创建表
来源：http://dali.cheryme.top/Article/details/gtlimbpzfr.html

CREATE TABLE users (
来源：http://dali.xziqi.cn/Article/details/gtikaruzhj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xziqi.cn/Article/details/gtadfmbrtt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gtlwbgjhtj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hysaishi.cn/Article/details/gtsrxsfyls.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenjidiqi.icu/Article/details/gtkaiwfjbv.html

);
来源：http://dali.gogol.net.cn/Article/details/gtfnzahxsq.html

[Q02] 创建带外键的表
来源：http://dali.hysaishi.cn/Article/details/gtnvjxpvdj.html

CREATE TABLE orders (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvmdgszj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gtmgftebjy.html

user_id INT NOT NULL,
来源：http://dali.daxiang520.top/Article/details/gtvhmasojo.html

amount DECIMAL(10, 2),
来源：http://dali.dashuyun.cn/Article/details/gttgdruxxb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxuanxn.top/Article/details/gtvymbvxff.html

);
来源：http://dali.cqqwz.cn/Article/details/gtwuayvyus.html

[Q03] 增加列
来源：http://dali.snrcjt.cn/Article/details/gtficmkqio.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.guowangkeji.top/Article/details/gtvkurdegl.html

[Q04] 修改列类型
来源：http://dali.shuidangran.top/Article/details/gthtgiyixf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhengqikj.top/Article/details/gtceboczgt.html

[Q05] 重命名列
来源：http://dali.snrcjt.cn/Article/details/gtkwxrteri.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.bjfxy.top/Article/details/gtugzhjpjh.html

[Q06] 删除列
来源：http://dali.yj20258888.top/Article/details/gtjlpieebh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenzaomai.com/Article/details/gtyfxgzpck.html

[Q07] 删除表
来源：http://dali.xinyue.icu/Article/details/gthiuyidqe.html

DROP TABLE IF EXISTS orders;
来源：http://dali.andypj.xyz/Article/details/gtvmrxhnun.html

[Q08] 创建普通索引
来源：http://dali.hywenlv.cn/Article/details/gttjrrfham.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyizsgjxq.html

[Q09] 创建唯一索引
来源：http://dali.shzxlz.cn/Article/details/gtsiyaacrf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jqgufenzy.top/Article/details/gtqqnbqjis.html

[Q10] 插入单行
来源：http://dali.iojbl.cn/Article/details/gtgplqvwoq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.mhx1999.top/Article/details/gtgnbrojjg.html

[Q11] 一次插入多行
来源：http://dali.zhoulong.xyz/Article/details/gtdjgfetcg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daxiang520.top/Article/details/gtofjluuha.html

[Q12] 插入后取自增 ID
来源：http://dali.shzxlz.cn/Article/details/gtbtnqzikk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.haohaochexian.top/Article/details/gtbdrvjatp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenjidiqi.icu/Article/details/gtdzrhcmob.html

[Q13] 忽略重复插入
来源：http://dali.jiagoushi.top/Article/details/gtippljphb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gtndohrngt.html

[Q14] 存在则更新（upsert）
来源：http://dali.hongshengwenyu.top/Article/details/gtshmlakgg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yanxiufei.cn/Article/details/gtrjvhvrtx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xuanzx.com/Article/details/gtbucitqxd.html

[Q15] 查询全部
来源：http://dali.birdmap.top/Article/details/gtwiekrmcw.html

SELECT * FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtnnzmfdqf.html

[Q16] 查询指定列
来源：http://dali.chenjidiqi.icu/Article/details/gthosfgopu.html

SELECT id, name FROM users;
来源：http://dali.birdmap.top/Article/details/gtmhnjfdof.html

[Q17] 条件查询
来源：http://dali.xziqi.cn/Article/details/gtndmwayol.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cucudq.cn/Article/details/gtrrfgkmxm.html

[Q18] 模糊匹配
来源：http://dali.sufxvd.cn/Article/details/gtklrivwre.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenlongwang.top/Article/details/gtfyzvqcsd.html

[Q19] 范围查询
来源：http://dali.shangyingyoupin.top/Article/details/gtrblruzrn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.bjfxy.top/Article/details/gtjxluatxb.html

[Q20] IN 列表
来源：http://dali.iojbl.cn/Article/details/gtbbhedbcg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnfgfcle.html

[Q21] 空值判断
来源：http://dali.yj20258888.top/Article/details/gtqtupoucy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.quarkkingdee.top/Article/details/gttttztcbg.html

[Q22] 排序
来源：http://dali.jqgufenzy.top/Article/details/gtcukqaufh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yanxiufei.cn/Article/details/gtxvvkoavt.html

[Q23] 分页
来源：http://dali.yj202588.top/Article/details/gtegowupmq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdrmgosnl.html

[Q24] 去重
来源：http://dali.xylfe.cn/Article/details/gtfxxvgknq.html

SELECT DISTINCT city FROM users;
来源：http://dali.birdmap.top/Article/details/gtjzsofipw.html

[Q25] 只取前 N 条
来源：http://dali.jinqigfzy.top/Article/details/gtidkmdpmr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gotoacloud.top/Article/details/gtucxyqyqt.html

[Q26] 计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkigsuaf.html

SELECT COUNT(*) FROM users;
来源：http://dali.pycfn.com/Article/details/gtowpbqvlf.html

[Q27] 条件计数
来源：http://dali.redwolf501.top/Article/details/gtdaceofwb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtfhkplfnr.html

[Q28] 求和与平均
来源：http://dali.xuetiantiany.cn/Article/details/gtxdpxcitz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtyljmeajx.html

[Q29] 最大最小值
来源：http://dali.chenlongwang.top/Article/details/gtinodhuei.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvszmzkk.html

[Q30] 分组统计
来源：http://dali.redwolf501.top/Article/details/gtpdhtebok.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtbluxjicv.html

[Q31] 分组后过滤
来源：http://dali.fengsongda.top/Article/details/gtfzlikwoh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.fzhhl.top/Article/details/gttwdfajir.html

[Q32] 分组拼接字符串
来源：http://dali.yj202588.top/Article/details/gtpsxagxni.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtulwlrxus.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cucudq.cn/Article/details/gtiipptrin.html

[Q33] 多列分组
来源：http://dali.sxryk.cn/Article/details/gtkixcyupv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.fengsongda.top/Article/details/gtobpeimcx.html

[Q34] 每组取第一条
来源：http://dali.gogol.net.cn/Article/details/gtaqvcwzlq.html

SELECT * FROM (
来源：http://dali.kuanghao11.cn/Article/details/gtzscfhsli.html


<!-- 参考信息 -->