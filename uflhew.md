代发 wailian999

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuxming.cn/Article/details/gt2ludlvzit.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shangyingyoupin.top/Article/details/gt2cqdjuuxb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cqqwz.cn/Article/details/gt2mhvwioez.html

[N04] 斐波那契数列
来源：http://dali.yangfankeji.com/Article/details/gt2wasjwloc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gt2jsexymyb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aizwys.cn/Article/details/gt2aqmkzigm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2dbihxtma.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gt2lvxvgxbd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj202588.top/Article/details/gt2qcrcgrxi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ivvv.top/Article/details/gt2ihuryuze.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gt2yuzivuhm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gt2wgbpxwou.html

[N05] 最大公约数
来源：http://dali.hnqzz.top/Article/details/gt2xcpgeqsv.html

Py:   math.gcd(a, b)
来源：http://dali.jyoumei.cn/Article/details/gt2cthilcaw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.haohaochexian.top/Article/details/gt2ohpupaya.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gt2uxbzjgqw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gt2jljxxbtw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gaohongyu789.top/Article/details/gt2pzmxlrfn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.haohaochexian.top/Article/details/gt2rmswrudl.html

Ruby: a.gcd(b)
来源：http://dali.hfpthk.cn/Article/details/gt2fmfjqvez.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yanxiufei.cn/Article/details/gt2eihkjeah.html

[N06] 判断回文字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2bxwskajb.html

Py:   s == s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gt2twqjyfyx.html

PHP:  $s === strrev($s);
来源：http://dali.316326.xyz/Article/details/gt2ujxopniz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gt2qetjqeyf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gt2eqbntulv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cashguo.top/Article/details/gt2obxtqqnd.html

Go:   // 双指针从两端比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2mjtoolbo.html

Ruby: s == s.reverse
来源：http://dali.fzhhl.top/Article/details/gt2qrwarglb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aibaodan.cn/Article/details/gt2rgmjneto.html

[N07] 两数之和（返回下标）
来源：http://dali.aizwys.cn/Article/details/gt2qbkuvakk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xylfe.cn/Article/details/gt2nrdtmkas.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.316326.xyz/Article/details/gt2qvjvhhhh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tianlin.xyz/Article/details/gt2ugluglni.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinqigufen.top/Article/details/gt2pfsnnnus.html

Java: // 手写 HashMap
来源：http://dali.tianlin.xyz/Article/details/gt2fptdcbum.html

Go:   // 手写 map[int]int
来源：http://dali.jqgfzy.top/Article/details/gt2dzyqnuzo.html

Ruby: // 手写 Hash
来源：http://dali.9152youxi.cn/Article/details/gt2vcsekbri.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cashguo.top/Article/details/gt2hxszpjgv.html

[N08] 生成全排列
来源：http://dali.c1oappe.top/Article/details/gt2xqkstykh.html

Py:   itertools.permutations(arr)
来源：http://dali.ydzc1.top/Article/details/gt2mqwkpfge.html

PHP:  // 手写递归交换
来源：http://dali.guowangkeji.top/Article/details/gt2aofweiwd.html

JS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gt2jcueeqsu.html

TS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2bqtpsduh.html

Java: // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2avyieahq.html

Go:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gt2qcdwbrcc.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258.top/Article/details/gt2wgbguxsr.html

C#:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gt2zwemvqqb.html

[N09] 栈与队列
来源：http://dali.xylfe.cn/Article/details/gt2jldrctlx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2cjfgrmcq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.iojbl.cn/Article/details/gt2jmuburdv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gt2glxonjxx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gotoacloud.top/Article/details/gt2qwolhdwg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gt2gkwvctzk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xuanzx.com/Article/details/gt2slfhsfbf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gt2oarivkzr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gaohongyu789.top/Article/details/gt2swheuefn.html

[N10] 链表节点定义
来源：http://dali.yangfankeji.com/Article/details/gt2qieejzlc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yuxming.cn/Article/details/gt2zqrmfilz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fxvyqjfd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jzrvgkur.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sysykeji.top/Article/details/gt2ripdveky.html

Java: class Node { int v; Node next; }
来源：http://dali.andypj.xyz/Article/details/gt2cekqxuar.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258888.top/Article/details/gt2qulfgarn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangdashe.top/Article/details/gt2fqafdbyz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnnlaro.html

[N11] 二叉树中序遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2kbiiqhav.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xylfe.cn/Article/details/gt2xbdzjwpf.html

PHP:  // 手写递归函数
来源：http://dali.jiagoushi.top/Article/details/gt2synqyexx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gt2lcnpvint.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gt2pomfxuvq.html

Java: // 手写递归
来源：http://dali.yj202588.top/Article/details/gt2sdticcvi.html

Go:   // 手写递归
来源：http://dali.tian-w.cn/Article/details/gt2ojryycsf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gaohongyu789.top/Article/details/gt2gqbnnnqf.html

C#:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gt2calinkww.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ehwqpu.com/Article/details/gt2wwekmpfi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shuidangran.top/Article/details/gt2xihikptp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cucudq.cn/Article/details/gt2fpmlcxel.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gt2qblkevdx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gt2wwqfadim.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yangfankeji.com/Article/details/gt2pkmncqsc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ehwqpu.com/Article/details/gt2voizrahu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinqigufen.top/Article/details/gt2fahlslhk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gt2vlvvsqbj.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2yliuvoel.html

O. 并发与异步
来源：http://dali.zhengqikj.top/Article/details/gt2omlvmnmq.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2lmtgnvps.html

[O01] 启动一个线程
来源：http://dali.sweek.top/Article/details/gt2abwznnbk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenjidiqi.icu/Article/details/gt2heaynnzz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dianchejie.cn/Article/details/gt2wpsumibw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnxiangtu.top/Article/details/gt2gjbvwpjj.html

TS:   // 同 JS
来源：http://dali.iojbl.cn/Article/details/gt2oxsoswly.html

Java: new Thread(() -> f()).start()
来源：http://dali.ehwqpu.com/Article/details/gt2pgakhchy.html

Go:   go f()
来源：http://dali.havefunace.top/Article/details/gt2aspiincy.html

Ruby: Thread.new { f }
来源：http://dali.sxryk.cn/Article/details/gt2pohwyzcd.html

C#:   Task.Run(() => F());
来源：http://dali.hnxiangtu.top/Article/details/gt2ttgawjtw.html

[O02] 使用线程池
来源：http://dali.9152youxi.cn/Article/details/gt2vlddgkxf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj202588.top/Article/details/gt2wuehrlph.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ydzc1.top/Article/details/gt2fwdzrrzo.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gt2fczsrrhd.html

TS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gt2rpvrfxxh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bshszcul.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jianghu66.top/Article/details/gt2uosgcbza.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.0kj1m.cn/Article/details/gt2rfblomfm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hongshengwenyu.top/Article/details/gt2qyabqxiq.html

[O03] 加锁保护共享数据
来源：http://dali.jianghu66.top/Article/details/gt2efeqiymy.html

Py:   with lock: shared += 1
来源：http://dali.haohaochexian.top/Article/details/gt2turuiday.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shuidangran.top/Article/details/gt2jkingwlv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guannengcc.top/Article/details/gt2ozorhccs.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gt2jjcgeazg.html

Java: synchronized (this) { shared++; }
来源：http://dali.pycfn.com/Article/details/gt2ukzifxig.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2eicpxuwi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.mhx1999.top/Article/details/gt2scirtkqx.html

C#:   lock (gate) { shared++; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2esuhkapw.html

[O04] 定义异步函数并等待
来源：http://dali.hnqzz.top/Article/details/gt2pxergiks.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxuanxn.top/Article/details/gt2ygvwardk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.9152youxi.cn/Article/details/gt2vqxnlnxg.html

JS:   async function f() { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gt2oboxnsmo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.fzhhl.top/Article/details/gt2hehkbuha.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.9152youxi.cn/Article/details/gt2ltekztnn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.pengpengdd.cyou/Article/details/gt2nqlsylec.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daria6918.cn/Article/details/gt2mogunkyi.html

C#:   async Task F() { await G(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ujmhwtbo.html

[O05] 并发执行并等待全部完成
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ygglngug.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yongpay.top/Article/details/gt2bzltazch.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.havefunace.top/Article/details/gt2zxxwjoyy.html

JS:   await Promise.all(tasks)
来源：http://dali.yanxiufei.cn/Article/details/gt2zzmvhlwl.html

TS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gt2qoauweqo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuxming.cn/Article/details/gt2zmvssmaq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guowangkeji.top/Article/details/gt2bynbemds.html

Ruby: threads.map(&:join)
来源：http://dali.cqqwz.cn/Article/details/gt2olwwqzxm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.dashuyun.cn/Article/details/gt2jiwsqbaj.html

[O06] 使用进程池
来源：http://dali.haohaochexian.top/Article/details/gt2rzbxwnai.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qwnbuowv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.meibo888.top/Article/details/gt2cbzahort.html

JS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gt2zrpvsyhr.html

TS:   // child_process / cluster 模块
来源：http://dali.sufxvd.cn/Article/details/gt2pfhvkldz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xinyue.icu/Article/details/gt2eoebjxao.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.iojbl.cn/Article/details/gt2sxvsnkax.html

Ruby: // fork 块
来源：http://dali.ehwqpu.com/Article/details/gt2msicfxti.html

C#:   Parallel.For
来源：http://dali.guowangkeji.top/Article/details/gt2nxulefnv.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2sdlabwbl.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrdting.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2tetwrjyt.html

[P01] 生成 UUID
来源：http://dali.nwbrower.top/Article/details/gt2kazlddsb.html

Py:   str(uuid.uuid4())
来源：http://dali.yj202588.top/Article/details/gt2ufucqdik.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guannengcc.top/Article/details/gt2nkhryumh.html

JS:   crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gt2vxrlavez.html

TS:   crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gt2mvaiqcqy.html

Java: UUID.randomUUID().toString()
来源：http://dali.pycfn.com/Article/details/gt2arlnqpvw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yvedp.cn/Article/details/gt2izwywnwt.html

Ruby: SecureRandom.uuid
来源：http://dali.pengpengdd.cyou/Article/details/gt2ytgelbux.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2qrrpxeic.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ivvv.top/Article/details/gt2azbskrsq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.bjfxy.top/Article/details/gt2siilomin.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2vhtjrgpl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jlsjyb.cn/Article/details/gt2fwpnckrc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yanxiufei.cn/Article/details/gt2kybdonwf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gt2dlusxhlu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hywenlv.cn/Article/details/gt2lcbanuzx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cashguo.top/Article/details/gt2stoyjbnx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shangyingyoupin.top/Article/details/gt2ltnevrrv.html

[P03] 生成短随机字符串
来源：http://dali.jianghu66.top/Article/details/gt2usvvjeql.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pengpengdd.cyou/Article/details/gt2zcrddogq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nanxinkj.top/Article/details/gt2sxcygckb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.9152youxi.cn/Article/details/gt2seosestq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qatwyfvo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rczwcabh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.birdmap.top/Article/details/gt2akbutoof.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shuidangran.top/Article/details/gt2hwijennw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgufenzy.top/Article/details/gt2qqafcwge.html

[P04] 求长度
来源：http://dali.chenzaomai.com/Article/details/gt2isrxfqzi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xziqi.cn/Article/details/gt2ohqdqkcw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gt2qleanajq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gt2frqonxtf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gt2lwwgtyrr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shuidangran.top/Article/details/gt2ytixeipo.html

Go:   len(arr);  len(m)
来源：http://dali.sxryk.cn/Article/details/gt2estbegie.html

Ruby: x.length;  x.size
来源：http://dali.zhiwuduotai.top/Article/details/gt2oevenrne.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gt2mwjlxzbx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jqgufenzy.top/Article/details/gt2bitujpmo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.birdmap.top/Article/details/gt2upfpwcum.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shangyingyoupin.top/Article/details/gt2qfogfcvd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ydzc1.top/Article/details/gt2hbmlitxv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ydzc1.top/Article/details/gt2muegifwi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yonumen.top/Article/details/gt2vihroils.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yongpay.top/Article/details/gt2lamyegkc.html

Ruby: a == b
来源：http://dali.yuanzhike.top/Article/details/gt2ctzltsti.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.fengsongda.top/Article/details/gt2kzzdupcn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.iojbl.cn/Article/details/gt2kolzrdep.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gotoacloud.top/Article/details/gt2ynjecene.html

PHP:  if (empty($x)) {}
来源：http://dali.xinyue.icu/Article/details/gt2lickjoej.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenzaomai.com/Article/details/gt2cqdvceuz.html

TS:   if (x == null) {}
来源：http://dali.sxryk.cn/Article/details/gt2xqxpsujq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2wmvdegpb.html

Go:   if x == nil {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cqcvoani.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxuanxn.top/Article/details/gt2jhyozbqt.html

C#:   if (x is null) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dlreixlc.html

[P07] 防抖与节流
来源：http://dali.svipenyu.cn/Article/details/gt2fovsdisb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxinkj.top/Article/details/gt2tihabqfw.html

PHP:  // 手写时间戳比较
来源：http://dali.hywenlv.cn/Article/details/gt2uojforqr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gt2dcuxvmdy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gt2dnjrnxiy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sysykeji.top/Article/details/gt2jnlqgjom.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.snrcjt.cn/Article/details/gt2etxolwud.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jianghu66.top/Article/details/gt2yykrpgbh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hywenlv.cn/Article/details/gt2mncsjetw.html

[P08] 处理浮点精度问题
来源：http://dali.gogol.net.cn/Article/details/gt2tbtwrrpd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhixingplan.top/Article/details/gt2sbrrrlim.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cucudq.cn/Article/details/gt2szjknuze.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yuanzhike.top/Article/details/gt2lsqkajwz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gt2sbkuvzxk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nanxinkj.top/Article/details/gt2qjyqmwxn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ybcxt.top/Article/details/gt2jnochvou.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuanzx.com/Article/details/gt2kitdmiug.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pycfn.com/Article/details/gt2heqosqjh.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2wtuhcjmd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yvedp.cn/Article/details/gt2rcxmdtkf.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2zorbubuv.html

[Q01] 创建表
来源：http://dali.vqdsnc.cn/Article/details/gt2winbmtsi.html

CREATE TABLE users (
来源：http://dali.feifeiyinyue.top/Article/details/gt2ownosrwy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gt2wkmqgdvf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gt2scfxpzgi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.vqdsnc.cn/Article/details/gt2jfwppooy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gzhubu.top/Article/details/gt2wkxgwisc.html

);
来源：http://dali.cheryme.top/Article/details/gt2pqtpzuaf.html

[Q02] 创建带外键的表
来源：http://dali.redwolf501.top/Article/details/gt2spcsfqot.html

CREATE TABLE orders (
来源：http://dali.gaohongyu789.top/Article/details/gt2kdvronex.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gt2kydsvaku.html

user_id INT NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gt2mnpvbitq.html

amount DECIMAL(10, 2),
来源：http://dali.svipenyu.cn/Article/details/gt2mzxkaolc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ybcxt.top/Article/details/gt2rpatiqqk.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pjxgarqc.html

[Q03] 增加列
来源：http://dali.shzxlz.cn/Article/details/gt2hewhuaui.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xuetiantiany.cn/Article/details/gt2nxqtrmsl.html

[Q04] 修改列类型
来源：http://dali.cucudq.cn/Article/details/gt2oftxhize.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hysaishi.cn/Article/details/gt2rnwkzmyb.html

[Q05] 重命名列
来源：http://dali.yj202588.top/Article/details/gt2ianzhzoe.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jqgufenzy.top/Article/details/gt2lyhndfkp.html

[Q06] 删除列
来源：http://dali.cashguo.top/Article/details/gt2ognlkhit.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jiagoushi.top/Article/details/gt2vzqgingz.html

[Q07] 删除表
来源：http://dali.pengpengdd.cyou/Article/details/gt2vwxtyxfy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hysaishi.cn/Article/details/gt2iufnkfwg.html

[Q08] 创建普通索引
来源：http://dali.fzhhl.top/Article/details/gt2jwjbtemn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yongpay.top/Article/details/gt2ybhenpkf.html

[Q09] 创建唯一索引
来源：http://dali.meibo888.top/Article/details/gt2xebcftpn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gt2ermivzvo.html

[Q10] 插入单行
来源：http://dali.sysykeji.top/Article/details/gt2mzlrgcbb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tanke756.top/Article/details/gt2pihoxpzo.html

[Q11] 一次插入多行
来源：http://dali.aibaodan.cn/Article/details/gt2wkdqkqza.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xuanzx.com/Article/details/gt2jktylqpg.html

[Q12] 插入后取自增 ID
来源：http://dali.ybcxt.top/Article/details/gt2utoqcngm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.iojbl.cn/Article/details/gt2msekgzru.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jqgufenzy.top/Article/details/gt2xmxrceec.html

[Q13] 忽略重复插入
来源：http://dali.9152youxi.cn/Article/details/gt2geqdjxpp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dianchejie.cn/Article/details/gt2tpoucujt.html

[Q14] 存在则更新（upsert）
来源：http://dali.feifeiyinyue.top/Article/details/gt2xgcfcclk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hfpthk.cn/Article/details/gt2cnajrawq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.kuanghao11.cn/Article/details/gt2bxsinlol.html

[Q15] 查询全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kixyeioc.html

SELECT * FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2ykbnsthl.html

[Q16] 查询指定列
来源：http://dali.shzxlz.cn/Article/details/gt2vllyhkby.html

SELECT id, name FROM users;
来源：http://dali.pycfn.com/Article/details/gt2kgdicaqg.html

[Q17] 条件查询
来源：http://dali.mhx1999.top/Article/details/gt2mbhqpmjc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ppjwa.cn/Article/details/gt2rirfmmcj.html

[Q18] 模糊匹配
来源：http://dali.jinqigufen.top/Article/details/gt2ffteeszo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xylfe.cn/Article/details/gt2kxcfhcuw.html

[Q19] 范围查询
来源：http://dali.daria6918.cn/Article/details/gt2yulswcek.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gzhubu.top/Article/details/gt2vgtuqbky.html

[Q20] IN 列表
来源：http://dali.fzhhl.top/Article/details/gt2wjoyqjki.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gzhubu.top/Article/details/gt2lcnzqcde.html

[Q21] 空值判断
来源：http://dali.smart0.xyz/Article/details/gt2tgcjtuus.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenlongwang.top/Article/details/gt2ouwdjqra.html

[Q22] 排序
来源：http://dali.cdnleiting.top/Article/details/gt2nhlebzup.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.pycfn.com/Article/details/gt2wnvucmwa.html

[Q23] 分页
来源：http://dali.yj20258.top/Article/details/gt2pweilpay.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ybcxt.top/Article/details/gt2tgcgbdiz.html

[Q24] 去重
来源：http://dali.yongpay.top/Article/details/gt2gdktrsmh.html

SELECT DISTINCT city FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2hzzmkbkl.html

[Q25] 只取前 N 条
来源：http://dali.birdmap.top/Article/details/gt2zaczhpmb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhiwuduotai.top/Article/details/gt2odjaqpcb.html

[Q26] 计数
来源：http://dali.xziqi.cn/Article/details/gt2izsixtrh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2euzlmnkq.html

[Q27] 条件计数
来源：http://dali.cdnleiting.top/Article/details/gt2tijruewm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.pycfn.com/Article/details/gt2ueexpfrm.html

[Q28] 求和与平均
来源：http://dali.tanke756.top/Article/details/gt2karpwjcd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2eznymyvp.html

[Q29] 最大最小值
来源：http://dali.hfpthk.cn/Article/details/gt2qzvxeogq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2nkzwmsnn.html

[Q30] 分组统计
来源：http://dali.zhengqikj.top/Article/details/gt2eewehtnf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gt2vzrneidi.html

[Q31] 分组后过滤
来源：http://dali.cucudq.cn/Article/details/gt2xnuzzsbg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.vqdsnc.cn/Article/details/gt2lumhkkes.html

[Q32] 分组拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gt2aaepluwd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gt2ryppscpq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yanxiufei.cn/Article/details/gt2yxwmimxp.html

[Q33] 多列分组
来源：http://dali.chenjidiqi.icu/Article/details/gt2eeqwjspo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shuidangran.top/Article/details/gt2vvgrsoiv.html

[Q34] 每组取第一条
来源：http://dali.aizwys.cn/Article/details/gt2andkdexp.html

SELECT * FROM (
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hjpicvib.html


<!-- 参考信息 -->