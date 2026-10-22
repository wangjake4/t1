代发 wailian999

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gt2mlxnipvq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ivvv.top/Article/details/gt2yrkglmuu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gt2fdbespvu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gt2ccpmfany.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daxiang520.top/Article/details/gt2zqvyaivu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hammf.cn/Article/details/gt2fgspormt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gt2lfpgbdzf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2msarthgv.html

[N05] 最大公约数
来源：http://dali.birdmap.top/Article/details/gt2uftybwrp.html

Py:   math.gcd(a, b)
来源：http://dali.shuidangran.top/Article/details/gt2qqpcxukc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxinkj.top/Article/details/gt2sjfawhuv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gt2hukyipud.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rgghhjzl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wzhgotwq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ydzc1.top/Article/details/gt2urlydjea.html

Ruby: a.gcd(b)
来源：http://dali.yueranfly.top/Article/details/gt2mtlfisvh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sysykeji.top/Article/details/gt2gybssisp.html

[N06] 判断回文字符串
来源：http://dali.jqgfzy.top/Article/details/gt2hxfrctlo.html

Py:   s == s[::-1]
来源：http://dali.yonumen.top/Article/details/gt2xliwirft.html

PHP:  $s === strrev($s);
来源：http://dali.shuidangran.top/Article/details/gt2hdajnqxf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gt2wgiovmcr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gt2barpbcfn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj20258.top/Article/details/gt2nxeumuqh.html

Go:   // 双指针从两端比较
来源：http://dali.quarkkingdee.top/Article/details/gt2mtchpvrv.html

Ruby: s == s.reverse
来源：http://dali.gzhubu.top/Article/details/gt2ejpuxifx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gt2zuwiuqsw.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258.top/Article/details/gt2pgkkqkyz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.snrcjt.cn/Article/details/gt2cqqdfqhb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.meibo888.top/Article/details/gt2gagddiup.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.smart0.xyz/Article/details/gt2hsrnxgfi.html

TS:   // 手写 Map<string, number>
来源：http://dali.shzxlz.cn/Article/details/gt2hjlcgvqb.html

Java: // 手写 HashMap
来源：http://dali.xuanzx.com/Article/details/gt2oikiiljl.html

Go:   // 手写 map[int]int
来源：http://dali.nanxinkj.top/Article/details/gt2uyinjjdv.html

Ruby: // 手写 Hash
来源：http://dali.zhiwuduotai.top/Article/details/gt2xoxgzytp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhiwuduotai.top/Article/details/gt2azybavdm.html

[N08] 生成全排列
来源：http://dali.jiagoushi.top/Article/details/gt2joxrxkie.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2bluknvyd.html

PHP:  // 手写递归交换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2havvfecr.html

JS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2gpydmcdh.html

TS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2entsylsj.html

Java: // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gt2icwrscqa.html

Go:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2qggnckat.html

Ruby: arr.permutation.to_a
来源：http://dali.bjfxy.top/Article/details/gt2nafocbus.html

C#:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2ctzdtrqc.html

[N09] 栈与队列
来源：http://dali.316326.xyz/Article/details/gt2isbatnqj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhongyouzk.top/Article/details/gt2iizfkgtd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zycfv.cn/Article/details/gt2yblmfkgc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gt2xwjdlpri.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.bjfxy.top/Article/details/gt2pgdbcdjt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ydzc1.top/Article/details/gt2jfbngenf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pibcipni.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gt2xolsrkah.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xylfe.cn/Article/details/gt2cuwtgxvp.html

[N10] 链表节点定义
来源：http://dali.yuanzhike.top/Article/details/gt2pialstps.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gogol.net.cn/Article/details/gt2puvksyec.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zdqjudy.top/Article/details/gt2xdddnubn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pnixvvik.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.pengpengdd.cyou/Article/details/gt2celzosas.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgfzy.top/Article/details/gt2bmwxvjeg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gzhubu.top/Article/details/gt2kzwaogyu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.9152youxi.cn/Article/details/gt2fvidxvcq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xuanzx.com/Article/details/gt2uyjjwfoh.html

[N11] 二叉树中序遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2vsdapexd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sxryk.cn/Article/details/gt2zjbixyzm.html

PHP:  // 手写递归函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zhuvpwsu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gt2ethpgplm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wfcekzno.html

Java: // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hbhlnmix.html

Go:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gt2gazfkvxs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ydzc1.top/Article/details/gt2gptdetme.html

C#:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gt2ofrbkypv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258888.top/Article/details/gt2jncjpyew.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.iojbl.cn/Article/details/gt2aufupfmn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gaohongyu789.top/Article/details/gt2anjaorty.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gt2dmijqqgu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gt2efcoeabm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wghvwxvk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jyoumei.cn/Article/details/gt2fnpzpjmd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.meibo888.top/Article/details/gt2pxeoxsfy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gt2msssalzj.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2rfbqihsg.html

O. 并发与异步
来源：http://dali.jinqigfzy.top/Article/details/gt2lgizwpqz.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2jugnyzut.html

[O01] 启动一个线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wlhaiwhv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.mhx1999.top/Article/details/gt2muxoxemy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fonldass.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ybcxt.top/Article/details/gt2ilzpjcgg.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gt2uucgxvue.html

Java: new Thread(() -> f()).start()
来源：http://dali.snrcjt.cn/Article/details/gt2nfnwtoyf.html

Go:   go f()
来源：http://dali.quarkkingdee.top/Article/details/gt2bmvzhasc.html

Ruby: Thread.new { f }
来源：http://dali.zhoulong.xyz/Article/details/gt2tcpxymzs.html

C#:   Task.Run(() => F());
来源：http://dali.tian-w.cn/Article/details/gt2kybvllge.html

[O02] 使用线程池
来源：http://dali.yueranfly.top/Article/details/gt2jjsddndy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jqgfzy.top/Article/details/gt2wjmoboam.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cashguo.top/Article/details/gt2ggfswdmu.html

JS:   // worker_threads 线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rsuwpttb.html

TS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gt2zwolqkzx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.quarkkingdee.top/Article/details/gt2ikdkigwg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xuetiantiany.cn/Article/details/gt2tldcyvio.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgfzy.top/Article/details/gt2iggzyqvy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.aibaodan.cn/Article/details/gt2qansgspy.html

[O03] 加锁保护共享数据
来源：http://dali.birdmap.top/Article/details/gt2krhvpuwv.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gt2vhveoyff.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.quarkkingdee.top/Article/details/gt2dcmsjvqn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.0kj1m.cn/Article/details/gt2grkmmsbg.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gt2mogjtbyn.html

Java: synchronized (this) { shared++; }
来源：http://dali.havefunace.top/Article/details/gt2bfwtgyuz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.svipenyu.cn/Article/details/gt2iklujajb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gzhubu.top/Article/details/gt2dkioalmi.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gt2eezpmvel.html

[O04] 定义异步函数并等待
来源：http://dali.jiagoushi.top/Article/details/gt2iseeibfg.html

Py:   async def f():⏎    await g()
来源：http://dali.9152youxi.cn/Article/details/gt2epctcvis.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yvedp.cn/Article/details/gt2zgjvqidx.html

JS:   async function f() { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2dvodkthp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ydzc1.top/Article/details/gt2sdkxmiuu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yanxiufei.cn/Article/details/gt2farzpdcs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuxming.cn/Article/details/gt2zedwoxbb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yvedp.cn/Article/details/gt2ebfppnjg.html

C#:   async Task F() { await G(); }
来源：http://dali.tianlin.xyz/Article/details/gt2lxwvgvzj.html

[O05] 并发执行并等待全部完成
来源：http://dali.pycfn.com/Article/details/gt2iauytpmw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cheryme.top/Article/details/gt2wepfxryi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jqgufenzy.top/Article/details/gt2zcatmgzo.html

JS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gt2sefdmalr.html

TS:   await Promise.all(tasks)
来源：http://dali.fzhhl.top/Article/details/gt2kgkxdipy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nwbrower.top/Article/details/gt2ueqepoqp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhixingplan.top/Article/details/gt2gooowrev.html

Ruby: threads.map(&:join)
来源：http://dali.ydzc1.top/Article/details/gt2jqvaefkn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jiagoushi.top/Article/details/gt2dbrqphhu.html

[O06] 使用进程池
来源：http://dali.yvedp.cn/Article/details/gt2nzkxoiiw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.haohaochexian.top/Article/details/gt2sljxfycx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj20258888.top/Article/details/gt2gtzphwof.html

JS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gt2oqmxxtfm.html

TS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gt2yrmtoitl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nanxinkj.top/Article/details/gt2zhcgpoih.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cqqwz.cn/Article/details/gt2sjvpunzz.html

Ruby: // fork 块
来源：http://dali.dashuyun.cn/Article/details/gt2jkmqhmvb.html

C#:   Parallel.For
来源：http://dali.hysaishi.cn/Article/details/gt2atmbgtud.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2ykwjhhsx.html

P. 常用工具函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jhlvsdnu.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2cfcfnpuj.html

[P01] 生成 UUID
来源：http://dali.jlsjyb.cn/Article/details/gt2mgwcjoxx.html

Py:   str(uuid.uuid4())
来源：http://dali.gzhubu.top/Article/details/gt2vxoufbap.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenjidiqi.icu/Article/details/gt2iuwztbab.html

JS:   crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gt2qmdnacmx.html

TS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gt2tgmfvfhd.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgufenzy.top/Article/details/gt2grbtqwok.html

Go:   // 用 github.com/google/uuid
来源：http://dali.meibo888.top/Article/details/gt2hthdmlrb.html

Ruby: SecureRandom.uuid
来源：http://dali.daxiang520.top/Article/details/gt2srnngiec.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aibaodan.cn/Article/details/gt2aixdmoat.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cesocvau.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ppjwa.cn/Article/details/gt2xmsinqkf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.meibo888.top/Article/details/gt2dtfmlotz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxinkj.top/Article/details/gt2tuegsxjb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wtbbrhlf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yuanzhike.top/Article/details/gt2kyozzqcc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zdqjudy.top/Article/details/gt2ycvvyoze.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.redwolf501.top/Article/details/gt2ykuqgckh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aizwys.cn/Article/details/gt2wqnjqima.html

[P03] 生成短随机字符串
来源：http://dali.yj20258888.top/Article/details/gt2jaozgqgb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gotoacloud.top/Article/details/gt2pnpyuudd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.fzhhl.top/Article/details/gt2tqxtjdnv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.birdmap.top/Article/details/gt2sdopjesk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.9152youxi.cn/Article/details/gt2zqtdlxdf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jyoumei.cn/Article/details/gt2vdyvbnjj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dashuyun.cn/Article/details/gt2uubxnbpy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258888.top/Article/details/gt2hdwkpyud.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sxryk.cn/Article/details/gt2zycpmiua.html

[P04] 求长度
来源：http://dali.cdnleiting.top/Article/details/gt2rdexattu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.meibo888.top/Article/details/gt2tmrurxpa.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gt2saqrwcgh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fzhhl.top/Article/details/gt2mpjexftw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aizwys.cn/Article/details/gt2oyguyyml.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hongshengwenyu.top/Article/details/gt2zoaoksvg.html

Go:   len(arr);  len(m)
来源：http://dali.zycfv.cn/Article/details/gt2qvwzxpxf.html

Ruby: x.length;  x.size
来源：http://dali.c1oappe.top/Article/details/gt2dnynqsjn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.316326.xyz/Article/details/gt2zlhqtgpg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hysaishi.cn/Article/details/gt2wyyfombi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uuyaupri.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.birdmap.top/Article/details/gt2degeswyb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zycfv.cn/Article/details/gt2xyvnkmyz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2jbjrvgbb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xziqi.cn/Article/details/gt2dlpdmbri.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yueranfly.top/Article/details/gt2isgzqkir.html

Ruby: a == b
来源：http://dali.ydzc1.top/Article/details/gt2rqxiniev.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hammf.cn/Article/details/gt2kwhpiyxw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yvedp.cn/Article/details/gt2lpwrusjr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jiagoushi.top/Article/details/gt2rgicwkqu.html

PHP:  if (empty($x)) {}
来源：http://dali.daria6918.cn/Article/details/gt2sjnaftjp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.9152youxi.cn/Article/details/gt2qdyncjic.html

TS:   if (x == null) {}
来源：http://dali.gotoacloud.top/Article/details/gt2efacjplw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jqgfzy.top/Article/details/gt2fimghyex.html

Go:   if x == nil {}
来源：http://dali.yvedp.cn/Article/details/gt2wbfkcyqq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jlsjyb.cn/Article/details/gt2rzhooynz.html

C#:   if (x is null) {}
来源：http://dali.daxiang520.top/Article/details/gt2bifuxlac.html

[P07] 防抖与节流
来源：http://dali.bjfxy.top/Article/details/gt2gwmubsgm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yvedp.cn/Article/details/gt2ylyzswtp.html

PHP:  // 手写时间戳比较
来源：http://dali.cheryme.top/Article/details/gt2fouzeeny.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gt2fkiylubz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gt2xzuljftq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258888.top/Article/details/gt2fwmibxfv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.wangdashe.top/Article/details/gt2vydecufo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jianghu66.top/Article/details/gt2lmyzhkdx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zdqjudy.top/Article/details/gt2lsevdrre.html

[P08] 处理浮点精度问题
来源：http://dali.jiagoushi.top/Article/details/gt2tvkbctjk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xqaaofbs.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2zyvlgvrd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cashguo.top/Article/details/gt2pfxfpaxx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.andypj.xyz/Article/details/gt2ozigrvpl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangdashe.top/Article/details/gt2uicckxaf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tanke756.top/Article/details/gt2cfemrfij.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jqgufenzy.top/Article/details/gt2zntwmzen.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2psfzaxau.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2bcogakdv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.haohaochexian.top/Article/details/gt2mqjekikn.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2rnxjuigb.html

[Q01] 创建表
来源：http://dali.aibaodan.cn/Article/details/gt2ehudngnf.html

CREATE TABLE users (
来源：http://dali.gzhubu.top/Article/details/gt2dzcaqzpb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gt2pzkslbsn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gt2ahiaqtzb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shuidangran.top/Article/details/gt2doubdghm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258888.top/Article/details/gt2rupjjgaw.html

);
来源：http://dali.sxryk.cn/Article/details/gt2rsryapoh.html

[Q02] 创建带外键的表
来源：http://dali.zhixingplan.top/Article/details/gt2aavsmkxp.html

CREATE TABLE orders (
来源：http://dali.hywenlv.cn/Article/details/gt2xjxvrnjg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gt2wxzavpci.html

user_id INT NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gt2nglzuhhy.html

amount DECIMAL(10, 2),
来源：http://dali.sweek.top/Article/details/gt2gbtruata.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhoulong.xyz/Article/details/gt2nkxqsgrf.html

);
来源：http://dali.aizwys.cn/Article/details/gt2ujysdbui.html

[Q03] 增加列
来源：http://dali.nanxinkj.top/Article/details/gt2cnxlnlik.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.daxiang520.top/Article/details/gt2qpybjcdc.html

[Q04] 修改列类型
来源：http://dali.jianghu66.top/Article/details/gt2icsalbsw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cheryme.top/Article/details/gt2noszrsjx.html

[Q05] 重命名列
来源：http://dali.shangyingyoupin.top/Article/details/gt2siczedyl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.snrcjt.cn/Article/details/gt2ozwomvmn.html

[Q06] 删除列
来源：http://dali.ivvv.top/Article/details/gt2ukslilcu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xuetiantiany.cn/Article/details/gt2silcuqlp.html

[Q07] 删除表
来源：http://dali.chenlongwang.top/Article/details/gt2hrlrcjhb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shuidangran.top/Article/details/gt2qjdsizwa.html

[Q08] 创建普通索引
来源：http://dali.quarkkingdee.top/Article/details/gt2vsjlusgl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gt2zjpcekhi.html

[Q09] 创建唯一索引
来源：http://dali.yuxming.cn/Article/details/gt2waoyardu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sxryk.cn/Article/details/gt2yvtjrrst.html

[Q10] 插入单行
来源：http://dali.jqgfzy.top/Article/details/gt2ltzsfyxg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lbmmyqll.html

[Q11] 一次插入多行
来源：http://dali.9152youxi.cn/Article/details/gt2xcgrthkh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.haohaochexian.top/Article/details/gt2zjvcfacp.html

[Q12] 插入后取自增 ID
来源：http://dali.nwbrower.top/Article/details/gt2vahanzxl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.bjfxy.top/Article/details/gt2kayprrvu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.guowangkeji.top/Article/details/gt2rabwxhww.html

[Q13] 忽略重复插入
来源：http://dali.yj202588.top/Article/details/gt2mbxkdxpn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gt2qjnebvaa.html

[Q14] 存在则更新（upsert）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xecdzpij.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tianlin.xyz/Article/details/gt2awhhbcad.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.quarkkingdee.top/Article/details/gt2pdhbhkxn.html

[Q15] 查询全部
来源：http://dali.gzhubu.top/Article/details/gt2wldgshgy.html

SELECT * FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2dhwonzul.html

[Q16] 查询指定列
来源：http://dali.dianchejie.cn/Article/details/gt2xixeoehx.html

SELECT id, name FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2hvdykpnl.html

[Q17] 条件查询
来源：http://dali.ybcxt.top/Article/details/gt2iplzmbmm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.wangdashe.top/Article/details/gt2qqzgfwjg.html

[Q18] 模糊匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2rqcttnep.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.birdmap.top/Article/details/gt2isudpeuh.html

[Q19] 范围查询
来源：http://dali.gotoacloud.top/Article/details/gt2zhskoise.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.9152youxi.cn/Article/details/gt2muiffomp.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqpvkni.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2yquyjall.html

[Q21] 空值判断
来源：http://dali.hnxiangtu.top/Article/details/gt2okszildl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xylfe.cn/Article/details/gt2glwppvkw.html

[Q22] 排序
来源：http://dali.meibo888.top/Article/details/gt2cbozyadf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj202588.top/Article/details/gt2igdfloro.html

[Q23] 分页
来源：http://dali.gogol.net.cn/Article/details/gt2euubtphh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cheryme.top/Article/details/gt2audbzxgz.html

[Q24] 去重
来源：http://dali.hysaishi.cn/Article/details/gt2lcrrwtfr.html

SELECT DISTINCT city FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2segaqjvw.html

[Q25] 只取前 N 条
来源：http://dali.cashguo.top/Article/details/gt2lzqsnnnq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.bjfxy.top/Article/details/gt2cyichyew.html

[Q26] 计数
来源：http://dali.hnxiangtu.top/Article/details/gt2obyfszvr.html

SELECT COUNT(*) FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2mlmlgkzc.html

[Q27] 条件计数
来源：http://dali.yj202588.top/Article/details/gt2dfqqgscg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2oikalwyn.html

[Q28] 求和与平均
来源：http://dali.zhengqikj.top/Article/details/gt2ycbxwjfq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2uupruypx.html

[Q29] 最大最小值
来源：http://dali.tianlin.xyz/Article/details/gt2hmkxregf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2uewjtokt.html

[Q30] 分组统计
来源：http://dali.yvedp.cn/Article/details/gt2xggrkova.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gt2rteqlsqq.html

[Q31] 分组后过滤
来源：http://dali.birdmap.top/Article/details/gt2guaejfvq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yonumen.top/Article/details/gt2bbvsjaat.html

[Q32] 分组拼接字符串
来源：http://dali.xinyue.icu/Article/details/gt2zqypmzdd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gt2qbacnzhv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cashguo.top/Article/details/gt2gexthxdm.html

[Q33] 多列分组
来源：http://dali.sysykeji.top/Article/details/gt2dnzmpvdl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gzhubu.top/Article/details/gt2qawizuof.html

[Q34] 每组取第一条
来源：http://dali.xuetiantiany.cn/Article/details/gt2vkvhdpaz.html

SELECT * FROM (
来源：http://dali.sweek.top/Article/details/gt2vxneckyf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhixingplan.top/Article/details/gt2ruyifzdd.html

) t WHERE rn = 1;
来源：http://dali.fengsongda.top/Article/details/gt2clkohgzg.html

[Q35] 内连接
来源：http://dali.redwolf501.top/Article/details/gt2jttgivcp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gt2zooxxrxj.html


<!-- 参考信息 -->