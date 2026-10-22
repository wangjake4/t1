代发 wailian999

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cucudq.cn/Article/details/gtrajahxbw.html

[N10] 链表节点定义
来源：http://dali.cheryme.top/Article/details/gtibtuclji.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigufen.top/Article/details/gthbxqjwyf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xinyue.icu/Article/details/gtsnzpeobl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhoulong.xyz/Article/details/gtdeipeunw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgfzy.top/Article/details/gtmtkrtigv.html

Java: class Node { int v; Node next; }
来源：http://dali.vqdsnc.cn/Article/details/gtledgustu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhixingplan.top/Article/details/gtsecorcsb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgufenzy.top/Article/details/gtvjlpsevk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinjsbfnf.html

[N11] 二叉树中序遍历
来源：http://dali.redwolf501.top/Article/details/gtiswcmajy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj202588.top/Article/details/gtuxufwrei.html

PHP:  // 手写递归函数
来源：http://dali.yj202588.top/Article/details/gtwvcoeyye.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gtxapgjupn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gtvizquaxl.html

Java: // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gtiveskkxn.html

Go:   // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gtvsaevtwy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jyoumei.cn/Article/details/gthmnllmue.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gtjldytomo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.meibo888.top/Article/details/gtnfhsbczm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigfzy.top/Article/details/gtzsqaajbc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ybcxt.top/Article/details/gtpoaxoxnu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gtjupagrjp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258.top/Article/details/gtjiavdkbp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gtuwewnaea.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgufenzy.top/Article/details/gtidgblrgq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zycfv.cn/Article/details/gtsahnihpi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gtfovkpxcj.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtalraoiub.html

O. 并发与异步
来源：http://dali.gaohongyu789.top/Article/details/gtxlmikzdc.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtrznpubkz.html

[O01] 启动一个线程
来源：http://dali.pengpengdd.cyou/Article/details/gtceqwkqfd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jianghu66.top/Article/details/gtltacmger.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnxiangtu.top/Article/details/gtzadddise.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenlongwang.top/Article/details/gtwtoyqotq.html

TS:   // 同 JS
来源：http://dali.wangshuangyany.cn/Article/details/gtvfvamqaa.html

Java: new Thread(() -> f()).start()
来源：http://dali.haohaochexian.top/Article/details/gtwzyfilfx.html

Go:   go f()
来源：http://dali.cucudq.cn/Article/details/gtttacsaae.html

Ruby: Thread.new { f }
来源：http://dali.hywenlv.cn/Article/details/gtbkobxwwh.html

C#:   Task.Run(() => F());
来源：http://dali.yangfankeji.com/Article/details/gtdlwkxzos.html

[O02] 使用线程池
来源：http://dali.jinqigufen.top/Article/details/gtupzfdlci.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ydzc1.top/Article/details/gtysqszyik.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dashuyun.cn/Article/details/gtpiarbzuu.html

JS:   // worker_threads 线程池
来源：http://dali.kuanghao11.cn/Article/details/gtonrjmihl.html

TS:   // worker_threads 线程池
来源：http://dali.fzhhl.top/Article/details/gttabyigtp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.svipenyu.cn/Article/details/gtfvpxqmhp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuxming.cn/Article/details/gttftmdezv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gtryfzqrqt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shanyushiyangtech.top/Article/details/gtlmunekbe.html

[O03] 加锁保护共享数据
来源：http://dali.xziqi.cn/Article/details/gttefspfpk.html

Py:   with lock: shared += 1
来源：http://dali.hnxiangtu.top/Article/details/gtxvnvbskc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hysaishi.cn/Article/details/gtyujdoqov.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yanxiufei.cn/Article/details/gtsfqracrh.html

TS:   // 同 JS
来源：http://dali.ivvv.top/Article/details/gtltxnqtjd.html

Java: synchronized (this) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gtqkejclsv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258.top/Article/details/gtfyezrtue.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrmumhgw.html

C#:   lock (gate) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gtfaddetta.html

[O04] 定义异步函数并等待
来源：http://dali.yonumen.top/Article/details/gtcuifcvpq.html

Py:   async def f():⏎    await g()
来源：http://dali.xylfe.cn/Article/details/gtzispqiuo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hywenlv.cn/Article/details/gtqfbiwmpx.html

JS:   async function f() { await g(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgjivylv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gtmwpbvpwq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nanxinkj.top/Article/details/gtzzsqrfow.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.fzhhl.top/Article/details/gttlnavaxs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.0kj1m.cn/Article/details/gtodpnboqo.html

C#:   async Task F() { await G(); }
来源：http://dali.aizwys.cn/Article/details/gticfqozhk.html

[O05] 并发执行并等待全部完成
来源：http://dali.hnxiangtu.top/Article/details/gttatbrtzt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtodpqkmpb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenzaomai.com/Article/details/gtonaqztvh.html

JS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gtgtafmbnr.html

TS:   await Promise.all(tasks)
来源：http://dali.yvedp.cn/Article/details/gtcnludcsv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.andypj.xyz/Article/details/gtgfmcihuf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgufenzy.top/Article/details/gteotmyijk.html

Ruby: threads.map(&:join)
来源：http://dali.shangyingyoupin.top/Article/details/gtplhkkkwe.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj202588.top/Article/details/gtfepikwav.html

[O06] 使用进程池
来源：http://dali.nanxuanxn.top/Article/details/gtqvigkrvi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gthsvdurbb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sufxvd.cn/Article/details/gtshidkksa.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gtiibzfrdg.html

TS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gtmtynmumg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoafbsunq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinqigufen.top/Article/details/gtbwpnzdvr.html

Ruby: // fork 块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlyzrdxx.html

C#:   Parallel.For
来源：http://dali.iojbl.cn/Article/details/gthtdnfkys.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtmdsfbyaq.html

P. 常用工具函数
来源：http://dali.fengsongda.top/Article/details/gtukvenfrs.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gttafdgtxh.html

[P01] 生成 UUID
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhvbznkq.html

Py:   str(uuid.uuid4())
来源：http://dali.sysykeji.top/Article/details/gtnvrooxld.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cheryme.top/Article/details/gthalrqdyy.html

JS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gtimtdtqot.html

TS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gtrfwytwgp.html

Java: UUID.randomUUID().toString()
来源：http://dali.meibo888.top/Article/details/gtenyegeky.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yongpay.top/Article/details/gtfyxdhjnc.html

Ruby: SecureRandom.uuid
来源：http://dali.c1oappe.top/Article/details/gtmqamuens.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hongshengwenyu.top/Article/details/gtgbumbrvp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yvedp.cn/Article/details/gtvbtgryum.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tanke756.top/Article/details/gtdayuqndd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dianchejie.cn/Article/details/gteyvdlhcq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pycfn.com/Article/details/gtkfarhvwi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dashuyun.cn/Article/details/gtvyeozgaq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gtjwtcwpgq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hywenlv.cn/Article/details/gtzjsuecdg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.iojbl.cn/Article/details/gttjhokdbq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.birdmap.top/Article/details/gtrhgbewiy.html

[P03] 生成短随机字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtnptgxyln.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuanzx.com/Article/details/gtefofsfee.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.316326.xyz/Article/details/gttrmpxlhp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgufenzy.top/Article/details/gtnyyseaaz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ehwqpu.com/Article/details/gtdpgeqkbk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtvtpbqeuw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.havefunace.top/Article/details/gtbqsmfmoi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hywenlv.cn/Article/details/gtkiacwfzl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhoulong.xyz/Article/details/gtcnagpwjz.html

[P04] 求长度
来源：http://dali.sysykeji.top/Article/details/gtyfhnhpuc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.svipenyu.cn/Article/details/gtdgfidwpw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gttdzaytgr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gtvfoqmhbh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.vqdsnc.cn/Article/details/gtctbzwram.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxwtnqjz.html

Go:   len(arr);  len(m)
来源：http://dali.snrcjt.cn/Article/details/gtuphhelfg.html

Ruby: x.length;  x.size
来源：http://dali.hnqzz.top/Article/details/gtjxpxrrgk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tanke756.top/Article/details/gtzbfaurmo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ybcxt.top/Article/details/gtihxfgnux.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sweek.top/Article/details/gtiixldidg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yonumen.top/Article/details/gtayszggyp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfegdvdgp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.c1oappe.top/Article/details/gtxuakopgw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.havefunace.top/Article/details/gturybzpyk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtzsllblaa.html

Ruby: a == b
来源：http://dali.zhiwuduotai.top/Article/details/gttnybijyc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.dashuyun.cn/Article/details/gtckwmcqdg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.smart0.xyz/Article/details/gtzlykceff.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.svipenyu.cn/Article/details/gtwwmybwwr.html

PHP:  if (empty($x)) {}
来源：http://dali.zhoulong.xyz/Article/details/gtewyijytu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gzhubu.top/Article/details/gtfmavtkpz.html

TS:   if (x == null) {}
来源：http://dali.yuxming.cn/Article/details/gtasxfozus.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ydzc1.top/Article/details/gtqrmzgabh.html

Go:   if x == nil {}
来源：http://dali.zhengqikj.top/Article/details/gthfzzfuta.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinqigufen.top/Article/details/gtrtatkoci.html

C#:   if (x is null) {}
来源：http://dali.hammf.cn/Article/details/gtbkzuqejj.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangtech.top/Article/details/gtljdwhvhb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinqigufen.top/Article/details/gtcsfkimhv.html

PHP:  // 手写时间戳比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtarwupevs.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gtznrtnhep.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gtrltfxnyd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.andypj.xyz/Article/details/gtgclezxjj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.9152youxi.cn/Article/details/gtqfonxcxv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jianghu66.top/Article/details/gtllzodavl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gaohongyu789.top/Article/details/gtmxgcqguh.html

[P08] 处理浮点精度问题
来源：http://dali.zhiwuduotai.top/Article/details/gtnilezkzu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zycfv.cn/Article/details/gtgsdulppw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yuanzhike.top/Article/details/gtfojgjfzb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhixingplan.top/Article/details/gtunbttjtj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hfpthk.cn/Article/details/gtinnfiahy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.dianchejie.cn/Article/details/gthajnojam.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.fzhhl.top/Article/details/gtqoswipyu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.snrcjt.cn/Article/details/gtbplaqvrw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.iojbl.cn/Article/details/gthdmiijlf.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtohzwnqam.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sxryk.cn/Article/details/gtvfbfnzpu.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gthbpjwjry.html

[Q01] 创建表
来源：http://dali.ehwqpu.com/Article/details/gtgroueuia.html

CREATE TABLE users (
来源：http://dali.tian-w.cn/Article/details/gtslgywlna.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yongpay.top/Article/details/gtwfjczwth.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gtrfjolsww.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shzxlz.cn/Article/details/gtzezkinma.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangdashe.top/Article/details/gtlwpeyqpi.html

);
来源：http://dali.xylfe.cn/Article/details/gtatptdatm.html

[Q02] 创建带外键的表
来源：http://dali.svipenyu.cn/Article/details/gtkhimxron.html

CREATE TABLE orders (
来源：http://dali.jqgfzy.top/Article/details/gtclowofxq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gtkjrsykki.html

user_id INT NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gtlcisdwin.html

amount DECIMAL(10, 2),
来源：http://dali.chenjidiqi.icu/Article/details/gtwqsmbwxl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaknrqoug.html

);
来源：http://dali.ppjwa.cn/Article/details/gtleklgflg.html

[Q03] 增加列
来源：http://dali.aibaodan.cn/Article/details/gtnmwypwra.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ppjwa.cn/Article/details/gtcxzbnive.html

[Q04] 修改列类型
来源：http://dali.shuidangran.top/Article/details/gtzljmbeoy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.mhx1999.top/Article/details/gtyhqbqrka.html

[Q05] 重命名列
来源：http://dali.smart0.xyz/Article/details/gthakyewwf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gzhubu.top/Article/details/gtphijednm.html

[Q06] 删除列
来源：http://dali.jyoumei.cn/Article/details/gtzyajnyxi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj202588.top/Article/details/gtggwbvsrt.html

[Q07] 删除表
来源：http://dali.9152youxi.cn/Article/details/gtyylawole.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gaohongyu789.top/Article/details/gtmiytmtxk.html

[Q08] 创建普通索引
来源：http://dali.cqqwz.cn/Article/details/gtqyuccvpu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sxryk.cn/Article/details/gtmrexhjcq.html

[Q09] 创建唯一索引
来源：http://dali.yanxiufei.cn/Article/details/gtehjmcjqc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhongyouzk.top/Article/details/gtwxuarrqj.html

[Q10] 插入单行
来源：http://dali.ybcxt.top/Article/details/gtdqzokuau.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zycfv.cn/Article/details/gtpkwbrqzp.html

[Q11] 一次插入多行
来源：http://dali.zdqjudy.top/Article/details/gtluuoujjd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nanxinkj.top/Article/details/gtsesqzsbm.html

[Q12] 插入后取自增 ID
来源：http://dali.sufxvd.cn/Article/details/gtmtcvwfbf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj20258888.top/Article/details/gtrxshprju.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.birdmap.top/Article/details/gtphdutbtb.html

[Q13] 忽略重复插入
来源：http://dali.kuanghao11.cn/Article/details/gtshgoozlu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ybcxt.top/Article/details/gtraouvwet.html

[Q14] 存在则更新（upsert）
来源：http://dali.yueranfly.top/Article/details/gtcvzfsmhl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yangfankeji.com/Article/details/gttipguxct.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenzaomai.com/Article/details/gtovygtwdd.html

[Q15] 查询全部
来源：http://dali.yongpay.top/Article/details/gtwhllnvib.html

SELECT * FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gthpfgowhf.html

[Q16] 查询指定列
来源：http://dali.tanke756.top/Article/details/gtaqndlzog.html

SELECT id, name FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtaqaurxhj.html

[Q17] 条件查询
来源：http://dali.chenlongwang.top/Article/details/gtxlrmprku.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtmdskwizm.html

[Q18] 模糊匹配
来源：http://dali.hnqzz.top/Article/details/gtawpqbxli.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjsmkqwb.html

[Q19] 范围查询
来源：http://dali.yj20258.top/Article/details/gtygrpzgrk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.redwolf501.top/Article/details/gtezbfddzx.html

[Q20] IN 列表
来源：http://dali.fzhhl.top/Article/details/gtjfvymdta.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tanke756.top/Article/details/gthfhcimit.html

[Q21] 空值判断
来源：http://dali.iojbl.cn/Article/details/gtxieyxume.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnqzz.top/Article/details/gtadfabjhw.html

[Q22] 排序
来源：http://dali.xylfe.cn/Article/details/gtysohgrhh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hammf.cn/Article/details/gtokqgcddz.html

[Q23] 分页
来源：http://dali.shuidangran.top/Article/details/gtimdqowgp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dashuyun.cn/Article/details/gthjcrabmt.html

[Q24] 去重
来源：http://dali.birdmap.top/Article/details/gtlumxclii.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbednnykr.html

[Q25] 只取前 N 条
来源：http://dali.zhiwuduotai.top/Article/details/gtxedeecwx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pycfn.com/Article/details/gtuuovklgt.html

[Q26] 计数
来源：http://dali.cashguo.top/Article/details/gtvxjohimi.html

SELECT COUNT(*) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtoqtfpmcj.html

[Q27] 条件计数
来源：http://dali.pengpengdd.cyou/Article/details/gtfwolfvuy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtfhnwvfah.html

[Q28] 求和与平均
来源：http://dali.guannengcc.top/Article/details/gtotdssapi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtfmkithmh.html

[Q29] 最大最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtvolzax.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtfrvjho.html

[Q30] 分组统计
来源：http://dali.hywenlv.cn/Article/details/gtihxalglw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gtslivqpht.html

[Q31] 分组后过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtkqscedrb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jyoumei.cn/Article/details/gtkqxzjwcm.html

[Q32] 分组拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gtcfyfbpui.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtczkllwnz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yuxming.cn/Article/details/gtvedmcqsc.html

[Q33] 多列分组
来源：http://dali.nwbrower.top/Article/details/gtsjichmil.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hnqzz.top/Article/details/gtbmyleqcf.html

[Q34] 每组取第一条
来源：http://dali.ivvv.top/Article/details/gtentanmci.html

SELECT * FROM (
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpdlvrsj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jianghu66.top/Article/details/gtnssmmheh.html

) t WHERE rn = 1;
来源：http://dali.yj20258.top/Article/details/gtwlmylxgm.html

[Q35] 内连接
来源：http://dali.cdnleiting.top/Article/details/gtbflguzon.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aibaodan.cn/Article/details/gtsyaxxcke.html

[Q36] 左连接
来源：http://dali.hfpthk.cn/Article/details/gtabvdzure.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gtlwewothf.html

[Q37] 右连接
来源：http://dali.jqgufenzy.top/Article/details/gtvwbzqzup.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnxiangtu.top/Article/details/gttkrbviys.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinqigfzy.top/Article/details/gtacwyzcey.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cashguo.top/Article/details/gtajikhznp.html

[Q39] 自连接（查上下级）
来源：http://dali.xuetiantiany.cn/Article/details/gtvcdsldyi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xinyue.icu/Article/details/gtednewhlv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuxming.cn/Article/details/gtskpjgcvl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhoulong.xyz/Article/details/gtejljwarr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmkotxes.html

[Q41] 多表连接
来源：http://dali.cashguo.top/Article/details/gtqkofecny.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cqqwz.cn/Article/details/gtxwgqqcxh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijccdoyx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.pycfn.com/Article/details/gtlgpkojii.html

[Q42] 连接条件附加过滤
来源：http://dali.gzhubu.top/Article/details/gtgogrcypq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuetiantiany.cn/Article/details/gtwscnvxkw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxinkj.top/Article/details/gtxgsqcdkr.html

[Q43] 标量子查询
来源：http://dali.yangfankeji.com/Article/details/gthhhkbgcd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj20258888.top/Article/details/gtqsosbcvk.html

[Q44] IN 子查询
来源：http://dali.birdmap.top/Article/details/gtnjfizhlx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.9152youxi.cn/Article/details/gtdmpbgdgg.html

[Q45] EXISTS 判断存在
来源：http://dali.fzhhl.top/Article/details/gtjskyohai.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhongyouzk.top/Article/details/gtcajvppzj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dashuyun.cn/Article/details/gtpfhciuuy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenlongwang.top/Article/details/gtxdmmqpji.html

[Q47] 与平均值比较
来源：http://dali.birdmap.top/Article/details/gtdqewgtwc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hysaishi.cn/Article/details/gtyafqhlwi.html

[Q48] CTE 公用表表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtiszxompz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yvedp.cn/Article/details/gtkfrpcujl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zdqjudy.top/Article/details/gtfwtcrloh.html

[Q49] 更新单行
来源：http://dali.tian-w.cn/Article/details/gthpvqxbrp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvvtwbjw.html

[Q50] 批量更新
来源：http://dali.yueranfly.top/Article/details/gtrihfhpzn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhixingplan.top/Article/details/gtohdjyncf.html

[Q51] 用子查询更新
来源：http://dali.tanke756.top/Article/details/gtituvrmpt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhixingplan.top/Article/details/gtucmrpvtd.html

[Q52] 删除指定行
来源：http://dali.mhx1999.top/Article/details/gtqubhyueo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gtqwlmakmd.html

[Q53] 按条件删除
来源：http://dali.zhiwuduotai.top/Article/details/gtwqczxokn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cheryme.top/Article/details/gtzfehqhrd.html

[Q54] 清空表
来源：http://dali.yvedp.cn/Article/details/gtvaxxdhae.html

TRUNCATE TABLE logs;
来源：http://dali.cheryme.top/Article/details/gtlqssromh.html

[Q55] 排名（并列占位）
来源：http://dali.xinyue.icu/Article/details/gtxvvhmplo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cucudq.cn/Article/details/gtzvcsbajs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccvlkaqy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gtshyvvyyw.html

[Q57] 行号
来源：http://dali.hysaishi.cn/Article/details/gtqgocxelg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtygilfbds.html

[Q58] 累计求和
来源：http://dali.yj20258888.top/Article/details/gtopbiukmg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yonumen.top/Article/details/gtyazuyoia.html

[Q59] 分组内累计
来源：http://dali.xziqi.cn/Article/details/gtawxnvqdm.html


<!-- 参考信息 -->