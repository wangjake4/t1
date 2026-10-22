代发 wailian999

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.birdmap.top/Article/details/gtsezcdmgt.html

[N10] 链表节点定义
来源：http://dali.ehwqpu.com/Article/details/gtqnyuojih.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.wangshuangyany.cn/Article/details/gtnnxmthss.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.smart0.xyz/Article/details/gtkmtokpta.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gaohongyu789.top/Article/details/gtdlzurfvd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuetiantiany.cn/Article/details/gtuvuqujdg.html

Java: class Node { int v; Node next; }
来源：http://dali.jyoumei.cn/Article/details/gtivkjuquk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.feifeiyinyue.top/Article/details/gtgxdpoclc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tanke756.top/Article/details/gtevdnklva.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cdnleiting.top/Article/details/gtwsvaxalh.html

[N11] 二叉树中序遍历
来源：http://dali.chenlongwang.top/Article/details/gtcutlgbvg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgngqzpcc.html

PHP:  // 手写递归函数
来源：http://dali.jyoumei.cn/Article/details/gtegkkloln.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gtjrfwbnwe.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gtmrfinehh.html

Java: // 手写递归
来源：http://dali.tanke756.top/Article/details/gtlgccpohv.html

Go:   // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjyuhhjn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shzxlz.cn/Article/details/gtyphqssxj.html

C#:   // 手写递归
来源：http://dali.316326.xyz/Article/details/gtsauudmmx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tanke756.top/Article/details/gtkfihogfu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yanxiufei.cn/Article/details/gtcwdplzeq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.iojbl.cn/Article/details/gtffhawqht.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gtkvizeqam.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gtkwqhahwx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gtrvhycely.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxinkj.top/Article/details/gtnfdymsuf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gogol.net.cn/Article/details/gtuqjuhbya.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ppjwa.cn/Article/details/gtdoxgzsxn.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtqembzvzs.html

O. 并发与异步
来源：http://dali.0kj1m.cn/Article/details/gticyfiekk.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtuqxtskbz.html

[O01] 启动一个线程
来源：http://dali.hywenlv.cn/Article/details/gtrwdkcxaq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gogol.net.cn/Article/details/gtrflteing.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hywenlv.cn/Article/details/gtbzqcuqgo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xziqi.cn/Article/details/gtembwtrou.html

TS:   // 同 JS
来源：http://dali.wangshuangyany.cn/Article/details/gtxljurkzs.html

Java: new Thread(() -> f()).start()
来源：http://dali.zycfv.cn/Article/details/gtwfnfauso.html

Go:   go f()
来源：http://dali.zhoulong.xyz/Article/details/gttkqdozqt.html

Ruby: Thread.new { f }
来源：http://dali.mhx1999.top/Article/details/gtidrlbslt.html

C#:   Task.Run(() => F());
来源：http://dali.cdnleiting.top/Article/details/gtmunupiab.html

[O02] 使用线程池
来源：http://dali.hysaishi.cn/Article/details/gtpcyyqsue.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhongyouzk.top/Article/details/gtlptaavwq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.quarkkingdee.top/Article/details/gtxonnjose.html

JS:   // worker_threads 线程池
来源：http://dali.zdqjudy.top/Article/details/gtloseaxal.html

TS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gtajwfrbzh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ydzc1.top/Article/details/gtxpgqzfys.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hammf.cn/Article/details/gtnztvqxdd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jyoumei.cn/Article/details/gtqtvvtuab.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.c1oappe.top/Article/details/gtdcuoswyo.html

[O03] 加锁保护共享数据
来源：http://dali.xinyue.icu/Article/details/gtvwwdtiye.html

Py:   with lock: shared += 1
来源：http://dali.chenjidiqi.icu/Article/details/gtylqciwoc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.smart0.xyz/Article/details/gtvuamovdp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yuxming.cn/Article/details/gtxhhqdkfm.html

TS:   // 同 JS
来源：http://dali.yongpay.top/Article/details/gtxcyhvxcy.html

Java: synchronized (this) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gtvorwkomo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuanzhike.top/Article/details/gtbvepghls.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinqigufen.top/Article/details/gthjucvnzt.html

C#:   lock (gate) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gtvyhgukah.html

[O04] 定义异步函数并等待
来源：http://dali.yanxiufei.cn/Article/details/gtckqdzaex.html

Py:   async def f():⏎    await g()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwnnvzkx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cdnleiting.top/Article/details/gtanmiktbi.html

JS:   async function f() { await g(); }
来源：http://dali.fzhhl.top/Article/details/gtjrcgxesq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gzhubu.top/Article/details/gtyqargeey.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258.top/Article/details/gtfxxcjjhd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.vqdsnc.cn/Article/details/gtzttxxdxp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jianghu66.top/Article/details/gtpvubkgaz.html

C#:   async Task F() { await G(); }
来源：http://dali.zhoulong.xyz/Article/details/gtnmrxchqb.html

[O05] 并发执行并等待全部完成
来源：http://dali.redwolf501.top/Article/details/gtngxcwmsq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtnpnaceyk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ehwqpu.com/Article/details/gtiwchbroo.html

JS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gthuvhnviv.html

TS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfqjstwa.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shzxlz.cn/Article/details/gtasugbtwn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.birdmap.top/Article/details/gtsdfovlyu.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258.top/Article/details/gtzsanwbpd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhongyouzk.top/Article/details/gtzqjlfjwg.html

[O06] 使用进程池
来源：http://dali.yanxiufei.cn/Article/details/gtpuykzmjz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jlsjyb.cn/Article/details/gtfqgvlrxs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsihhszq.html

JS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gtqownlosz.html

TS:   // child_process / cluster 模块
来源：http://dali.fzhhl.top/Article/details/gtyujwefzf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.haohaochexian.top/Article/details/gtivbklndp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ehwqpu.com/Article/details/gtyqenzpat.html

Ruby: // fork 块
来源：http://dali.zhiwuduotai.top/Article/details/gtzxtakvho.html

C#:   Parallel.For
来源：http://dali.gogol.net.cn/Article/details/gtkiqatgvf.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtvqqtbzdm.html

P. 常用工具函数
来源：http://dali.daria6918.cn/Article/details/gtcjalpycg.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtiwaynsiq.html

[P01] 生成 UUID
来源：http://dali.hnqzz.top/Article/details/gthzcwbciv.html

Py:   str(uuid.uuid4())
来源：http://dali.zhiwuduotai.top/Article/details/gtdccwgeqf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.iojbl.cn/Article/details/gtrwrebnol.html

JS:   crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gtbpoadado.html

TS:   crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gtrzkenxnm.html

Java: UUID.randomUUID().toString()
来源：http://dali.fengsongda.top/Article/details/gtykwcaczw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tian-w.cn/Article/details/gtnrpmqjly.html

Ruby: SecureRandom.uuid
来源：http://dali.xuanzx.com/Article/details/gtuszpohti.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aizwys.cn/Article/details/gtwictkecf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.fzhhl.top/Article/details/gtpvkqedfc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gaohongyu789.top/Article/details/gtdpmvpllc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yuxming.cn/Article/details/gtfokgfpzl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cdnleiting.top/Article/details/gtxrsycqgv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sysykeji.top/Article/details/gtymdxohna.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthyvuqljs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.andypj.xyz/Article/details/gtexgazcnc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gogol.net.cn/Article/details/gtjaucjqgu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinghuilouyu.cn/Article/details/gtbuzuhetn.html

[P03] 生成短随机字符串
来源：http://dali.ivvv.top/Article/details/gtessbvmtz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sxryk.cn/Article/details/gtqfykdrtb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.316326.xyz/Article/details/gthofgkgei.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gotoacloud.top/Article/details/gtttjmunbt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tian-w.cn/Article/details/gtojbxrgpg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.svipenyu.cn/Article/details/gtiyfvound.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cashguo.top/Article/details/gtdvpeeozi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.mhx1999.top/Article/details/gtabtxitxe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuxming.cn/Article/details/gtohpxofaq.html

[P04] 求长度
来源：http://dali.aizwys.cn/Article/details/gtvjjgctas.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nanxuanxn.top/Article/details/gtayswtzwa.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtauwymuif.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.316326.xyz/Article/details/gtbvrugrhp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gtdthtdaks.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhoulong.xyz/Article/details/gtjvdzdxsp.html

Go:   len(arr);  len(m)
来源：http://dali.cheryme.top/Article/details/gtmpipvdmk.html

Ruby: x.length;  x.size
来源：http://dali.shzxlz.cn/Article/details/gtbpisbasq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuxming.cn/Article/details/gtrlszfmcy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hywenlv.cn/Article/details/gtwaezglts.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zdqjudy.top/Article/details/gtojqanyin.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nanxuanxn.top/Article/details/gtjiuobfvd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinghuilouyu.cn/Article/details/gtnheqtmvi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.vqdsnc.cn/Article/details/gtkbrnwuex.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xziqi.cn/Article/details/gtxxtrggjm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xinyue.icu/Article/details/gtdtykrfan.html

Ruby: a == b
来源：http://dali.daxiang520.top/Article/details/gtjofjiryd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gaohongyu789.top/Article/details/gtfwnngqas.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinqigfzy.top/Article/details/gtsljcpzde.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yueranfly.top/Article/details/gtdqciknmn.html

PHP:  if (empty($x)) {}
来源：http://dali.kuanghao11.cn/Article/details/gtxcprrqnf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dashuyun.cn/Article/details/gtdhwxmphp.html

TS:   if (x == null) {}
来源：http://dali.birdmap.top/Article/details/gtlalenktl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gtbmcszzly.html

Go:   if x == nil {}
来源：http://dali.hywenlv.cn/Article/details/gttvtatrsn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sysykeji.top/Article/details/gthkkizcae.html

C#:   if (x is null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvgsawcm.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangtech.top/Article/details/gtyuvxjfsi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yueranfly.top/Article/details/gtqkdzlwku.html

PHP:  // 手写时间戳比较
来源：http://dali.sufxvd.cn/Article/details/gtktdbtocq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gtdmvezzys.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gtsbzpvclh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkenctdh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.aizwys.cn/Article/details/gtambonefy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hongshengwenyu.top/Article/details/gtpboybswy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.c1oappe.top/Article/details/gttekudved.html

[P08] 处理浮点精度问题
来源：http://dali.aizwys.cn/Article/details/gtepvxfiri.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hammf.cn/Article/details/gtxuvnwhqt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jianghu66.top/Article/details/gtyipbizvv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.wangshuangyany.cn/Article/details/gtfzvtyrfg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gtesqjorgh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.guannengcc.top/Article/details/gtakydgawn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.smart0.xyz/Article/details/gtzsyicvur.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ybcxt.top/Article/details/gtkcewtweq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sufxvd.cn/Article/details/gtyvntqohd.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtdytcgsjv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.snrcjt.cn/Article/details/gttixnkcrk.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtwjbueyfq.html

[Q01] 创建表
来源：http://dali.smart0.xyz/Article/details/gtvojvxncl.html

CREATE TABLE users (
来源：http://dali.xziqi.cn/Article/details/gtfkwyjdcw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gtizrfljft.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yueranfly.top/Article/details/gtesuyxlbe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shanyushiyangtech.top/Article/details/gtpihidmwi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pycfn.com/Article/details/gtozcgkscx.html

);
来源：http://dali.iojbl.cn/Article/details/gtcykekpzp.html

[Q02] 创建带外键的表
来源：http://dali.sufxvd.cn/Article/details/gthfsagdyu.html

CREATE TABLE orders (
来源：http://dali.ehwqpu.com/Article/details/gtlfqdlmeg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pengpengdd.cyou/Article/details/gtmqmmnzsz.html

user_id INT NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gtqggxvihx.html

amount DECIMAL(10, 2),
来源：http://dali.hnqzz.top/Article/details/gtfqgluvqt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.feifeiyinyue.top/Article/details/gtpnzlrdhr.html

);
来源：http://dali.sxryk.cn/Article/details/gtbxksodwr.html

[Q03] 增加列
来源：http://dali.pengpengdd.cyou/Article/details/gtdejsxjhq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfalvmzd.html

[Q04] 修改列类型
来源：http://dali.xuetiantiany.cn/Article/details/gtybfknhmn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgfzy.top/Article/details/gtkicizgdz.html

[Q05] 重命名列
来源：http://dali.yonumen.top/Article/details/gtimxgxfkc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigufen.top/Article/details/gtbnharyrh.html

[Q06] 删除列
来源：http://dali.yongpay.top/Article/details/gtgswmhzoy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbvyjfpq.html

[Q07] 删除表
来源：http://dali.pycfn.com/Article/details/gttpklwbyr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtqqlkzbss.html

[Q08] 创建普通索引
来源：http://dali.yj202588.top/Article/details/gtrbkhjryr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gtiolltyqt.html

[Q09] 创建唯一索引
来源：http://dali.kuanghao11.cn/Article/details/gtkumkqscf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gtoafjvwxk.html

[Q10] 插入单行
来源：http://dali.havefunace.top/Article/details/gthcnytrvr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tanke756.top/Article/details/gtvpitcgkx.html

[Q11] 一次插入多行
来源：http://dali.quarkkingdee.top/Article/details/gtisdywchj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangdashe.top/Article/details/gtovgzybcs.html

[Q12] 插入后取自增 ID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqdnyywh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangtech.top/Article/details/gtefxseyik.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hysaishi.cn/Article/details/gtmdwykkso.html

[Q13] 忽略重复插入
来源：http://dali.shzxlz.cn/Article/details/gtovjuzbhn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yuxming.cn/Article/details/gtzvrtushh.html

[Q14] 存在则更新（upsert）
来源：http://dali.hongshengwenyu.top/Article/details/gtbnfaxtwi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj20258888.top/Article/details/gtamhhwtgj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nanxuanxn.top/Article/details/gtsjsuvlgc.html

[Q15] 查询全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpuxurlal.html

SELECT * FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtpfmldqex.html

[Q16] 查询指定列
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmyjtxbo.html

SELECT id, name FROM users;
来源：http://dali.mhx1999.top/Article/details/gtpcritbef.html

[Q17] 条件查询
来源：http://dali.guannengcc.top/Article/details/gtiwmmqvmb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pycfn.com/Article/details/gtnwtmprvi.html

[Q18] 模糊匹配
来源：http://dali.hfpthk.cn/Article/details/gtrzmxyerc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.aizwys.cn/Article/details/gtasbcyhmu.html

[Q19] 范围查询
来源：http://dali.hammf.cn/Article/details/gtvofnunrw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.0kj1m.cn/Article/details/gtdesckkxx.html

[Q20] IN 列表
来源：http://dali.chenzaomai.com/Article/details/gtxuhklase.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gtbgruupkn.html

[Q21] 空值判断
来源：http://dali.9152youxi.cn/Article/details/gtschubcvo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xuanzx.com/Article/details/gtvqfrslbb.html

[Q22] 排序
来源：http://dali.yj202588.top/Article/details/gtzrtmmykt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.dashuyun.cn/Article/details/gtnmlsbsft.html

[Q23] 分页
来源：http://dali.fengsongda.top/Article/details/gtffrrleay.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cqqwz.cn/Article/details/gtuasnlggw.html

[Q24] 去重
来源：http://dali.ehwqpu.com/Article/details/gtzbjugwco.html

SELECT DISTINCT city FROM users;
来源：http://dali.yvedp.cn/Article/details/gtbancycij.html

[Q25] 只取前 N 条
来源：http://dali.zhixingplan.top/Article/details/gtrlchfpbi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tian-w.cn/Article/details/gtwjxdyxtc.html

[Q26] 计数
来源：http://dali.hywenlv.cn/Article/details/gtfaujikdv.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj202588.top/Article/details/gteevzfbmq.html

[Q27] 条件计数
来源：http://dali.snrcjt.cn/Article/details/gthesankjm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtcaowddyx.html

[Q28] 求和与平均
来源：http://dali.zhongyouzk.top/Article/details/gtfpgocter.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.316326.xyz/Article/details/gtpbexnoji.html

[Q29] 最大最小值
来源：http://dali.316326.xyz/Article/details/gthdpjebst.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtqkwjxjit.html

[Q30] 分组统计
来源：http://dali.cucudq.cn/Article/details/gtigrjyufx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gtpyjraxjb.html

[Q31] 分组后过滤
来源：http://dali.jinqigufen.top/Article/details/gtryigofpj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shzxlz.cn/Article/details/gtruebvcqr.html

[Q32] 分组拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gtrkynvxfd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gtwkxtljgd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.316326.xyz/Article/details/gtyjqgnrcr.html

[Q33] 多列分组
来源：http://dali.ppjwa.cn/Article/details/gtvjzofihz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.dashuyun.cn/Article/details/gtzyieikqe.html

[Q34] 每组取第一条
来源：http://dali.cqqwz.cn/Article/details/gtqbpkgsmr.html

SELECT * FROM (
来源：http://dali.chenzaomai.com/Article/details/gtpttfaoxh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenzaomai.com/Article/details/gtgyintqfm.html

) t WHERE rn = 1;
来源：http://dali.jianghu66.top/Article/details/gtpslgwerv.html

[Q35] 内连接
来源：http://dali.smart0.xyz/Article/details/gtazogtngq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gtknzgdjao.html

[Q36] 左连接
来源：http://dali.shangyingyoupin.top/Article/details/gtsflvjhri.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gtoyrmpsbz.html

[Q37] 右连接
来源：http://dali.zhoulong.xyz/Article/details/gtbntlipln.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cqqwz.cn/Article/details/gtzdmdxeej.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenlongwang.top/Article/details/gttyipgxqi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj202588.top/Article/details/gtvkugogsy.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthghhjtl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnqzz.top/Article/details/gtmlbhvwxj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tianlin.xyz/Article/details/gtshfgvyra.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcxbqpak.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhixingplan.top/Article/details/gtlnsvvwvh.html

[Q41] 多表连接
来源：http://dali.hfpthk.cn/Article/details/gtegytjrfg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.svipenyu.cn/Article/details/gtyaktnomz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.snrcjt.cn/Article/details/gtkyosdpps.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jiagoushi.top/Article/details/gtsdetajqq.html

[Q42] 连接条件附加过滤
来源：http://dali.yj20258.top/Article/details/gtiduldacx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.aizwys.cn/Article/details/gtcjfwffnp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenjidiqi.icu/Article/details/gtmxagvurv.html

[Q43] 标量子查询
来源：http://dali.xylfe.cn/Article/details/gtqwtrnjzm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guannengcc.top/Article/details/gttakmafyz.html

[Q44] IN 子查询
来源：http://dali.nwbrower.top/Article/details/gtsvhqbuvr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.9152youxi.cn/Article/details/gtxsqjrqme.html

[Q45] EXISTS 判断存在
来源：http://dali.yvedp.cn/Article/details/gtonyalnyc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yonumen.top/Article/details/gtlvczumyn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hnqzz.top/Article/details/gtonfseynk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shangyingyoupin.top/Article/details/gtabkeemzt.html

[Q47] 与平均值比较
来源：http://dali.havefunace.top/Article/details/gtndxjpgon.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zdqjudy.top/Article/details/gtruchwifs.html

[Q48] CTE 公用表表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtgfjgrgpa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.birdmap.top/Article/details/gtjkbbtelc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.smart0.xyz/Article/details/gtyrzxrmhr.html

[Q49] 更新单行
来源：http://dali.ydzc1.top/Article/details/gtdokhmfyl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gtwjimstiu.html

[Q50] 批量更新
来源：http://dali.dianchejie.cn/Article/details/gtcpxjehvb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jianghu66.top/Article/details/gtlmriwesa.html

[Q51] 用子查询更新
来源：http://dali.fengsongda.top/Article/details/gtpsffkhyc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ybcxt.top/Article/details/gttgssaozt.html

[Q52] 删除指定行
来源：http://dali.bjfxy.top/Article/details/gtywzloaes.html

DELETE FROM users WHERE id = 10;
来源：http://dali.meibo888.top/Article/details/gtmkbhgxmb.html

[Q53] 按条件删除
来源：http://dali.shangyingyoupin.top/Article/details/gtetfnhsut.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tian-w.cn/Article/details/gtbpzpvxwu.html

[Q54] 清空表
来源：http://dali.wangshuangyany.cn/Article/details/gtcultbzia.html

TRUNCATE TABLE logs;
来源：http://dali.tian-w.cn/Article/details/gtucehsklx.html

[Q55] 排名（并列占位）
来源：http://dali.dianchejie.cn/Article/details/gtxypqtpor.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gtlbagssit.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yuanzhike.top/Article/details/gtmdrpqfyc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cheryme.top/Article/details/gtuhqmxxfd.html

[Q57] 行号
来源：http://dali.dianchejie.cn/Article/details/gtjnmwcpuy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhengqikj.top/Article/details/gttktuocox.html

[Q58] 累计求和
来源：http://dali.zhixingplan.top/Article/details/gtfcmrgsyl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtgrhiiwwq.html

[Q59] 分组内累计
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbtceavx.html


<!-- 参考信息 -->