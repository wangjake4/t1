代发 wailian999

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.kuanghao11.cn/Article/details/gtxfmomtun.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yonumen.top/Article/details/gtxqhwuufh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.smart0.xyz/Article/details/gtnccekqif.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtwsimdsro.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gtmmvjgkpu.html

[N10] 链表节点定义
来源：http://dali.xuetiantiany.cn/Article/details/gtkxwgapys.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhengqikj.top/Article/details/gtqqylbmez.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenzaomai.com/Article/details/gtewsdkzyn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xuanzx.com/Article/details/gtjrribgnq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sweek.top/Article/details/gtfbuyaivz.html

Java: class Node { int v; Node next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzsharmu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nanxuanxn.top/Article/details/gtqvlzotgh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aibaodan.cn/Article/details/gtledysmdf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.havefunace.top/Article/details/gtrerayybo.html

[N11] 二叉树中序遍历
来源：http://dali.yanxiufei.cn/Article/details/gtpxhzywru.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gogol.net.cn/Article/details/gtqrermegc.html

PHP:  // 手写递归函数
来源：http://dali.9152youxi.cn/Article/details/gtuoluztlc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gtrpwqnirv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gtzuhkwwpv.html

Java: // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtdwgoyjfd.html

Go:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtpbrvpefh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ybcxt.top/Article/details/gtbntyaixq.html

C#:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtnbwrprrr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shzxlz.cn/Article/details/gtkmiallkk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yongpay.top/Article/details/gtfzbrjpvk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenjidiqi.icu/Article/details/gtmksbybeh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gtcdzwyfym.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gtksalunyx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.smart0.xyz/Article/details/gtlhnxvikr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknigqviv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.0kj1m.cn/Article/details/gtvegniuwj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuanzx.com/Article/details/gtanwjjeeu.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtxlaghdei.html

O. 并发与异步
来源：http://dali.fzhhl.top/Article/details/gtfuepydka.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtqqpvdcsi.html

[O01] 启动一个线程
来源：http://dali.mhx1999.top/Article/details/gtzhdcfwiu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ydzc1.top/Article/details/gtxlkzmvzb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cqqwz.cn/Article/details/gttemmmlcz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258888.top/Article/details/gtpgrndmbv.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gtsklezdfa.html

Java: new Thread(() -> f()).start()
来源：http://dali.nwbrower.top/Article/details/gtzpqlqpuc.html

Go:   go f()
来源：http://dali.dashuyun.cn/Article/details/gtxvvphxeb.html

Ruby: Thread.new { f }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqfmphtc.html

C#:   Task.Run(() => F());
来源：http://dali.zycfv.cn/Article/details/gtaqntfsbc.html

[O02] 使用线程池
来源：http://dali.kuanghao11.cn/Article/details/gtdhjlhnzw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.dashuyun.cn/Article/details/gtoeilzqsd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangtech.top/Article/details/gtddfwzeke.html

JS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gtefvajsbq.html

TS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gtgkafwmcc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprfsbgxz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aizwys.cn/Article/details/gtludmsbog.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.wangdashe.top/Article/details/gtylbjqhpg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jianghu66.top/Article/details/gtcfknriec.html

[O03] 加锁保护共享数据
来源：http://dali.xinyue.icu/Article/details/gtlsmcbubh.html

Py:   with lock: shared += 1
来源：http://dali.cqqwz.cn/Article/details/gtemmmxwuj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ydzc1.top/Article/details/gtxosyrweg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvzlvawv.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gtoyvlgjgg.html

Java: synchronized (this) { shared++; }
来源：http://dali.tian-w.cn/Article/details/gtzcrfrjyf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenjidiqi.icu/Article/details/gtzmvhpzfg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhengqikj.top/Article/details/gtsribduge.html

C#:   lock (gate) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gtckvyjsgv.html

[O04] 定义异步函数并等待
来源：http://dali.ehwqpu.com/Article/details/gtwcdpljjx.html

Py:   async def f():⏎    await g()
来源：http://dali.daxiang520.top/Article/details/gtrndayask.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.quarkkingdee.top/Article/details/gtyfottigj.html

JS:   async function f() { await g(); }
来源：http://dali.guannengcc.top/Article/details/gtvknuwhht.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahuzvkit.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jlsjyb.cn/Article/details/gtcuznkuzg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenlongwang.top/Article/details/gthbvdfzmx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ybcxt.top/Article/details/gtiutzyerr.html

C#:   async Task F() { await G(); }
来源：http://dali.wangdashe.top/Article/details/gtzqwopsvo.html

[O05] 并发执行并等待全部完成
来源：http://dali.birdmap.top/Article/details/gtbhharwmp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.aizwys.cn/Article/details/gtwzcodoon.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.guowangkeji.top/Article/details/gthtblbbgi.html

JS:   await Promise.all(tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtinlarejy.html

TS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gtknvmjnai.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhoulong.xyz/Article/details/gtfgvocgem.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.redwolf501.top/Article/details/gtcqdxflmj.html

Ruby: threads.map(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gtuweoxfyu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gaohongyu789.top/Article/details/gthihxrfvk.html

[O06] 使用进程池
来源：http://dali.nanxinkj.top/Article/details/gtihtkuhlr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.9152youxi.cn/Article/details/gtqwajvmod.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.0kj1m.cn/Article/details/gtojbnrlja.html

JS:   // child_process / cluster 模块
来源：http://dali.hongshengwenyu.top/Article/details/gtwtaotgco.html

TS:   // child_process / cluster 模块
来源：http://dali.jinqigufen.top/Article/details/gtzszzwgtc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.dianchejie.cn/Article/details/gtjzwhlkve.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj202588.top/Article/details/gtxomvmwgo.html

Ruby: // fork 块
来源：http://dali.sxryk.cn/Article/details/gtugafcimi.html

C#:   Parallel.For
来源：http://dali.jyoumei.cn/Article/details/gtdienulra.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtzokjuuij.html

P. 常用工具函数
来源：http://dali.fzhhl.top/Article/details/gtzfjpccuy.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtlukraila.html

[P01] 生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gtrnruvufs.html

Py:   str(uuid.uuid4())
来源：http://dali.jlsjyb.cn/Article/details/gthhzgcmcp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tian-w.cn/Article/details/gtomrayhzc.html

JS:   crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gtfibwvrny.html

TS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gtfqjihrzq.html

Java: UUID.randomUUID().toString()
来源：http://dali.smart0.xyz/Article/details/gtgwshzaaf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yanxiufei.cn/Article/details/gtudrpfewh.html

Ruby: SecureRandom.uuid
来源：http://dali.sxryk.cn/Article/details/gtlhxayalb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yuxming.cn/Article/details/gthdzidfen.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnqzz.top/Article/details/gtgjnfjrcd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yanxiufei.cn/Article/details/gtccdnqobr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxinkj.top/Article/details/gtmnbpepzb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjevsurz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nwbrower.top/Article/details/gttocwhjpj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tianlin.xyz/Article/details/gtwwuipctk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.havefunace.top/Article/details/gtzinssfar.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtzddebapp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shzxlz.cn/Article/details/gtzymdewhy.html

[P03] 生成短随机字符串
来源：http://dali.tian-w.cn/Article/details/gtofcjzllm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zycfv.cn/Article/details/gtrtymwlcx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.0kj1m.cn/Article/details/gttqmvlgyz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtbspztoou.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbydabsqy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtujhxwaxk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.birdmap.top/Article/details/gtulalpzez.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.0kj1m.cn/Article/details/gteudkxsfi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zycfv.cn/Article/details/gtdpnjtzdp.html

[P04] 求长度
来源：http://dali.feifeiyinyue.top/Article/details/gtpquhlbqm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.haohaochexian.top/Article/details/gtvaptzfzp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtmfggggvg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hongshengwenyu.top/Article/details/gtoaxzecer.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gtdokfnblc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.svipenyu.cn/Article/details/gtqalvtkkv.html

Go:   len(arr);  len(m)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjgbedud.html

Ruby: x.length;  x.size
来源：http://dali.pengpengdd.cyou/Article/details/gtnyqtlngy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhengqikj.top/Article/details/gtgrbzafnm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.havefunace.top/Article/details/gtofxtghkh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pengpengdd.cyou/Article/details/gtmwawetta.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ybcxt.top/Article/details/gtxvmyoxno.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ehwqpu.com/Article/details/gtqjglnkon.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.316326.xyz/Article/details/gtnsyfwqfz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shuidangran.top/Article/details/gtbfbwjcvn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tanke756.top/Article/details/gtulicxpdm.html

Ruby: a == b
来源：http://dali.jinghuilouyu.cn/Article/details/gtilfgfccu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jqgufenzy.top/Article/details/gtmyketodg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hfpthk.cn/Article/details/gtotvransm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jlsjyb.cn/Article/details/gtjdadbphc.html

PHP:  if (empty($x)) {}
来源：http://dali.cucudq.cn/Article/details/gtyvcdoyep.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.snrcjt.cn/Article/details/gtvssplwsr.html

TS:   if (x == null) {}
来源：http://dali.yonumen.top/Article/details/gtntnmjlxx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gtfprmlize.html

Go:   if x == nil {}
来源：http://dali.tianlin.xyz/Article/details/gtdhratcyf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenlongwang.top/Article/details/gtdegrkhmy.html

C#:   if (x is null) {}
来源：http://dali.nanxuanxn.top/Article/details/gtfycmkrpt.html

[P07] 防抖与节流
来源：http://dali.ybcxt.top/Article/details/gtdkasekfg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shuidangran.top/Article/details/gtpvkfhzfe.html

PHP:  // 手写时间戳比较
来源：http://dali.mhx1999.top/Article/details/gtnxylvmov.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gthmqmcufz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gtzuobnoge.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shzxlz.cn/Article/details/gtmvyhllit.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.dashuyun.cn/Article/details/gtsfkfpvnj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tian-w.cn/Article/details/gthmncfpto.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xylfe.cn/Article/details/gtoiiqibap.html

[P08] 处理浮点精度问题
来源：http://dali.xylfe.cn/Article/details/gteuklmqeb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tanke756.top/Article/details/gtmqsofjyb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sxryk.cn/Article/details/gtgmqiycms.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sufxvd.cn/Article/details/gtfqyzbgzm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfacqcodd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cucudq.cn/Article/details/gtaaxxdght.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangdashe.top/Article/details/gtrwktawgs.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sweek.top/Article/details/gterviyqvy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xylfe.cn/Article/details/gtrnlnxzgq.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtioznqorw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhoulong.xyz/Article/details/gtbggnaoic.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtzwxnkwxp.html

[Q01] 创建表
来源：http://dali.cqqwz.cn/Article/details/gtqhdqenwv.html

CREATE TABLE users (
来源：http://dali.cashguo.top/Article/details/gttychsfsp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gzhubu.top/Article/details/gtbnqdplcz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.9152youxi.cn/Article/details/gtdrcgkvuu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenlongwang.top/Article/details/gtkucecnzn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigufen.top/Article/details/gtgaitqvny.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdapszds.html

[Q02] 创建带外键的表
来源：http://dali.xuetiantiany.cn/Article/details/gtztlkswvg.html

CREATE TABLE orders (
来源：http://dali.jlsjyb.cn/Article/details/gtielhlqfl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pengpengdd.cyou/Article/details/gtgvpwakme.html

user_id INT NOT NULL,
来源：http://dali.zhengqikj.top/Article/details/gtmilhsnef.html

amount DECIMAL(10, 2),
来源：http://dali.ybcxt.top/Article/details/gtdetgwavm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ivvv.top/Article/details/gtcrwxeuss.html

);
来源：http://dali.iojbl.cn/Article/details/gtktkdsbbe.html

[Q03] 增加列
来源：http://dali.yanxiufei.cn/Article/details/gtsyrfepbx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.guowangkeji.top/Article/details/gtpqsbxayc.html

[Q04] 修改列类型
来源：http://dali.snrcjt.cn/Article/details/gtbsahaybw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangdashe.top/Article/details/gtzzhdeqxa.html

[Q05] 重命名列
来源：http://dali.shuidangran.top/Article/details/gtuxmyxxzd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhongyouzk.top/Article/details/gtmbivniyr.html

[Q06] 删除列
来源：http://dali.yj20258.top/Article/details/gtpziszvhn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlvdfulm.html

[Q07] 删除表
来源：http://dali.birdmap.top/Article/details/gtlqpyhkrd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zycfv.cn/Article/details/gtcifvagdi.html

[Q08] 创建普通索引
来源：http://dali.chenjidiqi.icu/Article/details/gtyovxqgln.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj20258888.top/Article/details/gtzzvnmzgz.html

[Q09] 创建唯一索引
来源：http://dali.nanxuanxn.top/Article/details/gterwgrbbw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gthtwyvpxd.html

[Q10] 插入单行
来源：http://dali.zhiwuduotai.top/Article/details/gtgrlpjyey.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbacuwues.html

[Q11] 一次插入多行
来源：http://dali.wangshuangyany.cn/Article/details/gtmptnhpgz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jqgfzy.top/Article/details/gthdfzesmw.html

[Q12] 插入后取自增 ID
来源：http://dali.9152youxi.cn/Article/details/gtwhqxdgti.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.fengsongda.top/Article/details/gtvfljaiug.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigufen.top/Article/details/gtiwogxmko.html

[Q13] 忽略重复插入
来源：http://dali.xuetiantiany.cn/Article/details/gtzvcotzxi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gtkuwufidq.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxinkj.top/Article/details/gtsdezzuby.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cqqwz.cn/Article/details/gtqkbljfjm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jianghu66.top/Article/details/gtydsmaxli.html

[Q15] 查询全部
来源：http://dali.daria6918.cn/Article/details/gttxerlyym.html

SELECT * FROM users;
来源：http://dali.redwolf501.top/Article/details/gtzlzohige.html

[Q16] 查询指定列
来源：http://dali.shanyushiyangtech.top/Article/details/gtduozppfj.html

SELECT id, name FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtgddziine.html

[Q17] 条件查询
来源：http://dali.wangdashe.top/Article/details/gtqoifbchg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jiagoushi.top/Article/details/gtbwvorhgy.html

[Q18] 模糊匹配
来源：http://dali.wangdashe.top/Article/details/gtfyqknyrx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.0kj1m.cn/Article/details/gtlbfoviha.html

[Q19] 范围查询
来源：http://dali.jqgufenzy.top/Article/details/gtkzjxglsa.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hammf.cn/Article/details/gtxvpotfav.html

[Q20] IN 列表
来源：http://dali.zhengqikj.top/Article/details/gtoxstrhcs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cdnleiting.top/Article/details/gtunhqikqa.html

[Q21] 空值判断
来源：http://dali.yangfankeji.com/Article/details/gtaktwxfnp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.bjfxy.top/Article/details/gtoauroqxh.html

[Q22] 排序
来源：http://dali.chenzaomai.com/Article/details/gtpfxvlowh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cucudq.cn/Article/details/gtdvsnudsw.html

[Q23] 分页
来源：http://dali.zdqjudy.top/Article/details/gtufodjfwo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gzhubu.top/Article/details/gtbomagwmr.html

[Q24] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekyvuhmw.html

SELECT DISTINCT city FROM users;
来源：http://dali.xylfe.cn/Article/details/gtqekzsmly.html

[Q25] 只取前 N 条
来源：http://dali.tanke756.top/Article/details/gtzywansma.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hammf.cn/Article/details/gtyakxrlcw.html

[Q26] 计数
来源：http://dali.yongpay.top/Article/details/gtinfnpbpi.html

SELECT COUNT(*) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtadseeaop.html

[Q27] 条件计数
来源：http://dali.hywenlv.cn/Article/details/gtdsusgcdq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daxiang520.top/Article/details/gtpnctpspq.html

[Q28] 求和与平均
来源：http://dali.mhx1999.top/Article/details/gtrrogvnkq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtumihqmog.html

[Q29] 最大最小值
来源：http://dali.tian-w.cn/Article/details/gtumacokpe.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtaprugceo.html

[Q30] 分组统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpgnkdcr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gtboipcijm.html

[Q31] 分组后过滤
来源：http://dali.tian-w.cn/Article/details/gtqlnmywlv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtvvroegkp.html

[Q32] 分组拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtwvckddqo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtqgfhzcna.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.haohaochexian.top/Article/details/gtitwdapyz.html

[Q33] 多列分组
来源：http://dali.jinqigfzy.top/Article/details/gtozjmiftr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hnxiangtu.top/Article/details/gtzpjydkrd.html

[Q34] 每组取第一条
来源：http://dali.xziqi.cn/Article/details/gtalutvkzl.html

SELECT * FROM (
来源：http://dali.yueranfly.top/Article/details/gttedazjdg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yangfankeji.com/Article/details/gtirvpjosv.html

) t WHERE rn = 1;
来源：http://dali.jinqigufen.top/Article/details/gtqqhfcqbz.html

[Q35] 内连接
来源：http://dali.havefunace.top/Article/details/gturhxkrrg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xinyue.icu/Article/details/gtxewcadld.html

[Q36] 左连接
来源：http://dali.xuanzx.com/Article/details/gtfgwbnwcv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gtogoajrlu.html

[Q37] 右连接
来源：http://dali.chenzaomai.com/Article/details/gtxnfjxzvp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guowangkeji.top/Article/details/gtgzwdwkly.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yonumen.top/Article/details/gtailfxplm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xylfe.cn/Article/details/gtpcmhdhvl.html

[Q39] 自连接（查上下级）
来源：http://dali.iojbl.cn/Article/details/gtlnujchfa.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuanzhike.top/Article/details/gtqhkntoxy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.smart0.xyz/Article/details/gtmdauewvr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.smart0.xyz/Article/details/gtjrugldzk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.svipenyu.cn/Article/details/gtfcercmpw.html

[Q41] 多表连接
来源：http://dali.mhx1999.top/Article/details/gtyojtudrh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jiagoushi.top/Article/details/gtoypmojew.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sxryk.cn/Article/details/gtjkmjbgwl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hysaishi.cn/Article/details/gtsstjyfvv.html

[Q42] 连接条件附加过滤
来源：http://dali.0kj1m.cn/Article/details/gtpxbeqhdh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hfpthk.cn/Article/details/gtztwujeup.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ehwqpu.com/Article/details/gtczozwujl.html

[Q43] 标量子查询
来源：http://dali.hongshengwenyu.top/Article/details/gtiiddxrdn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigufen.top/Article/details/gtemvxawtn.html

[Q44] IN 子查询
来源：http://dali.xuetiantiany.cn/Article/details/gtogtcagwp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sysykeji.top/Article/details/gteklpkkqx.html

[Q45] EXISTS 判断存在
来源：http://dali.zhongyouzk.top/Article/details/gtjcgpxfab.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtmdnkkzzh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangshuangyany.cn/Article/details/gtpcdmsefd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258.top/Article/details/gteevvoxvl.html

[Q47] 与平均值比较
来源：http://dali.fengsongda.top/Article/details/gtbsfeztuz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daxiang520.top/Article/details/gtgkghqvik.html

[Q48] CTE 公用表表达式
来源：http://dali.zhongyouzk.top/Article/details/gtldqhibtt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.kuanghao11.cn/Article/details/gtoicjjtss.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cqqwz.cn/Article/details/gtgaeqdtbk.html

[Q49] 更新单行
来源：http://dali.cashguo.top/Article/details/gtorkfnywd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtkfjgrysq.html

[Q50] 批量更新
来源：http://dali.yj20258888.top/Article/details/gtfofgdgnr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tanke756.top/Article/details/gtuhptolih.html

[Q51] 用子查询更新
来源：http://dali.yj202588.top/Article/details/gtzzuvebas.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdkjoaroz.html

[Q52] 删除指定行
来源：http://dali.gotoacloud.top/Article/details/gtchrsdpsw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gthcisnkyn.html

[Q53] 按条件删除
来源：http://dali.dianchejie.cn/Article/details/gtkpuptxlb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gtvzcwvkcz.html

[Q54] 清空表
来源：http://dali.meibo888.top/Article/details/gtuqxobets.html

TRUNCATE TABLE logs;
来源：http://dali.svipenyu.cn/Article/details/gtawwuvxax.html

[Q55] 排名（并列占位）
来源：http://dali.ppjwa.cn/Article/details/gtpjkmycxg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shangyingyoupin.top/Article/details/gtrzclwfqb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.haohaochexian.top/Article/details/gtqfdoicji.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.havefunace.top/Article/details/gtygsmrjsy.html

[Q57] 行号
来源：http://dali.xuetiantiany.cn/Article/details/gtpljvppbs.html


<!-- 参考信息 -->