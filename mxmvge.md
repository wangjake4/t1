代发 wailian999

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.bjfxy.top/Article/details/gtwjwrsgoq.html

[N10] 链表节点定义
来源：http://dali.daxiang520.top/Article/details/gthonofico.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.redwolf501.top/Article/details/gtrfqldela.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jyoumei.cn/Article/details/gtywnnjwov.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yueranfly.top/Article/details/gtfprinfgq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangdashe.top/Article/details/gtziabgzhz.html

Java: class Node { int v; Node next; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzssgpexx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhbwobeo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.dianchejie.cn/Article/details/gtedgjwiza.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jianghu66.top/Article/details/gtcyybsdch.html

[N11] 二叉树中序遍历
来源：http://dali.xziqi.cn/Article/details/gtlouffaub.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.c1oappe.top/Article/details/gtghcuxkkr.html

PHP:  // 手写递归函数
来源：http://dali.tian-w.cn/Article/details/gtpmemnhwu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gtftgphqnu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gtftuljqui.html

Java: // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gtprobytbm.html

Go:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtczvlwgdb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jiagoushi.top/Article/details/gtodznbidv.html

C#:   // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtpavhrfyb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zycfv.cn/Article/details/gtearxhftf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.snrcjt.cn/Article/details/gteapjmvtq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tian-w.cn/Article/details/gtescwvjlf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gtnfoewlvb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gtfuwxjkyq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gttpbsegzs.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.svipenyu.cn/Article/details/gtqbkhraxa.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cucudq.cn/Article/details/gthfoyudpy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gaohongyu789.top/Article/details/gtnjjmknlm.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtuhhaccme.html

O. 并发与异步
来源：http://dali.ivvv.top/Article/details/gtqvjyyxvl.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtkrfghhoj.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gtrancllib.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yanxiufei.cn/Article/details/gtvopsfcpq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.iojbl.cn/Article/details/gtwchdpyni.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xylfe.cn/Article/details/gtfkwclbri.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gtuvrqnszz.html

Java: new Thread(() -> f()).start()
来源：http://dali.sxryk.cn/Article/details/gtekescavx.html

Go:   go f()
来源：http://dali.andypj.xyz/Article/details/gtmufhpzlr.html

Ruby: Thread.new { f }
来源：http://dali.daria6918.cn/Article/details/gtufsptizw.html

C#:   Task.Run(() => F());
来源：http://dali.xinyue.icu/Article/details/gtwihmoink.html

[O02] 使用线程池
来源：http://dali.hongshengwenyu.top/Article/details/gtubgvhwhp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jqgfzy.top/Article/details/gtpcxmtsbm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.redwolf501.top/Article/details/gtwfyallsh.html

JS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpqvzlto.html

TS:   // worker_threads 线程池
来源：http://dali.redwolf501.top/Article/details/gtuezdrchj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.316326.xyz/Article/details/gtasbnjbxz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhengqikj.top/Article/details/gtwtdrfonc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nanxinkj.top/Article/details/gtgwkwodww.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jiagoushi.top/Article/details/gtbdziwbpt.html

[O03] 加锁保护共享数据
来源：http://dali.svipenyu.cn/Article/details/gtvbmndmva.html

Py:   with lock: shared += 1
来源：http://dali.yj20258.top/Article/details/gtdjmfvcqk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhoulong.xyz/Article/details/gtijbxgyvu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.316326.xyz/Article/details/gtrcvfxres.html

TS:   // 同 JS
来源：http://dali.yongpay.top/Article/details/gtirgewnuu.html

Java: synchronized (this) { shared++; }
来源：http://dali.hfpthk.cn/Article/details/gtkbxxnhay.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shangyingyoupin.top/Article/details/gtfxjpdwlb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimrgelwz.html

C#:   lock (gate) { shared++; }
来源：http://dali.hfpthk.cn/Article/details/gtqqyryrwc.html

[O04] 定义异步函数并等待
来源：http://dali.cashguo.top/Article/details/gtqnlvwcva.html

Py:   async def f():⏎    await g()
来源：http://dali.iojbl.cn/Article/details/gtyxdpbrbt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gzhubu.top/Article/details/gtsxgoixoh.html

JS:   async function f() { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgurxyrzz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.aibaodan.cn/Article/details/gtcbawijps.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.guowangkeji.top/Article/details/gtkocvaazi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zdqjudy.top/Article/details/gtcomhyhja.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuetiantiany.cn/Article/details/gtqeztkzce.html

C#:   async Task F() { await G(); }
来源：http://dali.ybcxt.top/Article/details/gtveckgorc.html

[O05] 并发执行并等待全部完成
来源：http://dali.gaohongyu789.top/Article/details/gttnndjchf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtccxfebdq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfmjnkyt.html

JS:   await Promise.all(tasks)
来源：http://dali.jyoumei.cn/Article/details/gtfitteszr.html

TS:   await Promise.all(tasks)
来源：http://dali.jlsjyb.cn/Article/details/gtrgmuovdq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yonumen.top/Article/details/gtajxcicso.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jyoumei.cn/Article/details/gteyixxcjz.html

Ruby: threads.map(&:join)
来源：http://dali.9152youxi.cn/Article/details/gtroruewtk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hammf.cn/Article/details/gtdnlqdugp.html

[O06] 使用进程池
来源：http://dali.feifeiyinyue.top/Article/details/gtknizvrwq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.pengpengdd.cyou/Article/details/gtrfmqpvmb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sufxvd.cn/Article/details/gtycdhglpp.html

JS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gttoqamqmo.html

TS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gttouehmki.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cucudq.cn/Article/details/gtmoyxjjlh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zdqjudy.top/Article/details/gtquojzfxg.html

Ruby: // fork 块
来源：http://dali.birdmap.top/Article/details/gtrszonjrk.html

C#:   Parallel.For
来源：http://dali.nanxuanxn.top/Article/details/gtcgytgysy.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtvalwaguc.html

P. 常用工具函数
来源：http://dali.sxryk.cn/Article/details/gtdzfnmnoh.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtgigzrnoe.html

[P01] 生成 UUID
来源：http://dali.pengpengdd.cyou/Article/details/gturhwmdts.html

Py:   str(uuid.uuid4())
来源：http://dali.ppjwa.cn/Article/details/gtefhttrzk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ppjwa.cn/Article/details/gtskipvomu.html

JS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvqbwpsi.html

TS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gtzpwmspxg.html

Java: UUID.randomUUID().toString()
来源：http://dali.fzhhl.top/Article/details/gtbfdntppx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.wangshuangyany.cn/Article/details/gtmvrqyfls.html

Ruby: SecureRandom.uuid
来源：http://dali.vqdsnc.cn/Article/details/gtuqiloqdv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.9152youxi.cn/Article/details/gtkiidiljh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.316326.xyz/Article/details/gtbgzvidzb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hywenlv.cn/Article/details/gtopcflvrm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sweek.top/Article/details/gtyhfwkktg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hfpthk.cn/Article/details/gtqppbqdtz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yanxiufei.cn/Article/details/gtfyefcrst.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gtfzniikfx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxinkj.top/Article/details/gtnkqnutev.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jlsjyb.cn/Article/details/gtnypnfwwu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.birdmap.top/Article/details/gthdjhoibt.html

[P03] 生成短随机字符串
来源：http://dali.cashguo.top/Article/details/gtcysxffum.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.316326.xyz/Article/details/gtszklzofk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjytyfqw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jiagoushi.top/Article/details/gtmadfsuyb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlcrcbcrn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gaohongyu789.top/Article/details/gtghwbbqsg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenjidiqi.icu/Article/details/gtbufjkddg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxuanxn.top/Article/details/gteyigzoqq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinghuilouyu.cn/Article/details/gtfniwriew.html

[P04] 求长度
来源：http://dali.snrcjt.cn/Article/details/gtumocebkf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zycfv.cn/Article/details/gtagyckhjp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtbbdeqazr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gtgozbizdx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aizwys.cn/Article/details/gtjwbpcpyj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xinyue.icu/Article/details/gtrvmgmodq.html

Go:   len(arr);  len(m)
来源：http://dali.sufxvd.cn/Article/details/gtdwpnnecq.html

Ruby: x.length;  x.size
来源：http://dali.chenlongwang.top/Article/details/gtnbofrixt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fengsongda.top/Article/details/gtvoksnbft.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxuanxn.top/Article/details/gtxexicnly.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fengsongda.top/Article/details/gtwaodbwjv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.vqdsnc.cn/Article/details/gtdkrobzgn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigufen.top/Article/details/gtlmhrtbnt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigufen.top/Article/details/gtehysbiiq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xziqi.cn/Article/details/gtmzjqkbov.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.fzhhl.top/Article/details/gtvubriodf.html

Ruby: a == b
来源：http://dali.jyoumei.cn/Article/details/gtjbhpewuv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tanke756.top/Article/details/gtngnliyaa.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yanxiufei.cn/Article/details/gtlrmayolq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.316326.xyz/Article/details/gtgkwimagw.html

PHP:  if (empty($x)) {}
来源：http://dali.cashguo.top/Article/details/gttbvpkjbd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hysaishi.cn/Article/details/gtsemivlvx.html

TS:   if (x == null) {}
来源：http://dali.snrcjt.cn/Article/details/gtyippivcn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.birdmap.top/Article/details/gtzpkoclrc.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gthukilfei.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dashuyun.cn/Article/details/gtzeutejiy.html

C#:   if (x is null) {}
来源：http://dali.hongshengwenyu.top/Article/details/gttchzysej.html

[P07] 防抖与节流
来源：http://dali.kuanghao11.cn/Article/details/gthfrennpy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hnxiangtu.top/Article/details/gtmlhserrs.html

PHP:  // 手写时间戳比较
来源：http://dali.sysykeji.top/Article/details/gtxjwtkqxh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gtzjejhdjg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtgqxgyifd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258.top/Article/details/gtwqtnrzwl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hongshengwenyu.top/Article/details/gtzuvynadv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenlongwang.top/Article/details/gtcxjapmfq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinqigfzy.top/Article/details/gtqdqpjmbe.html

[P08] 处理浮点精度问题
来源：http://dali.guannengcc.top/Article/details/gteeqmmkkb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yonumen.top/Article/details/gtljzidhsy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gthcvwkisk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.mhx1999.top/Article/details/gtmmfbleed.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ppjwa.cn/Article/details/gtvmnfcmww.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ppjwa.cn/Article/details/gtylyhevxk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangtech.top/Article/details/gtrftbjkls.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jiagoushi.top/Article/details/gtrgwdzquw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhengqikj.top/Article/details/gthzdvjxfj.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtortkskdy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.wangdashe.top/Article/details/gtwtbzstal.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtmjrshzmg.html

[Q01] 创建表
来源：http://dali.kuanghao11.cn/Article/details/gtkbpxfgpj.html

CREATE TABLE users (
来源：http://dali.zhiwuduotai.top/Article/details/gttfguxvhc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangdashe.top/Article/details/gtrresnite.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gtpxbtxrpi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.haohaochexian.top/Article/details/gtzwovyvvy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shangyingyoupin.top/Article/details/gtvranmmwp.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gtxermqrpi.html

[Q02] 创建带外键的表
来源：http://dali.aibaodan.cn/Article/details/gtbfthimdr.html

CREATE TABLE orders (
来源：http://dali.smart0.xyz/Article/details/gtorljluav.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258.top/Article/details/gtehibtwqp.html

user_id INT NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gttstqyebw.html

amount DECIMAL(10, 2),
来源：http://dali.havefunace.top/Article/details/gtozmymakz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cqqwz.cn/Article/details/gtywrhsroy.html

);
来源：http://dali.kuanghao11.cn/Article/details/gtbuakfctv.html

[Q03] 增加列
来源：http://dali.zhongyouzk.top/Article/details/gtcspaywrj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sweek.top/Article/details/gthwjrvlhr.html

[Q04] 修改列类型
来源：http://dali.smart0.xyz/Article/details/gtcuumojhq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ybcxt.top/Article/details/gtralkrqkm.html

[Q05] 重命名列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsyiqwdty.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjzaqjde.html

[Q06] 删除列
来源：http://dali.yuxming.cn/Article/details/gthlmamzed.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nwbrower.top/Article/details/gtherajkli.html

[Q07] 删除表
来源：http://dali.gzhubu.top/Article/details/gtgvlyzobd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yongpay.top/Article/details/gtbxpqdbht.html

[Q08] 创建普通索引
来源：http://dali.kuanghao11.cn/Article/details/gtkhshukcw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gtrlsfgwyt.html

[Q09] 创建唯一索引
来源：http://dali.xziqi.cn/Article/details/gtyhazchsq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinghuilouyu.cn/Article/details/gtoauofywy.html

[Q10] 插入单行
来源：http://dali.hywenlv.cn/Article/details/gthzvccwdk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtnsrvcylf.html

[Q11] 一次插入多行
来源：http://dali.cashguo.top/Article/details/gtqbbyjwol.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.bjfxy.top/Article/details/gtamoyjfzf.html

[Q12] 插入后取自增 ID
来源：http://dali.iojbl.cn/Article/details/gtnallqlyk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jiagoushi.top/Article/details/gthtyxhdnc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhongyouzk.top/Article/details/gtquitnznr.html

[Q13] 忽略重复插入
来源：http://dali.ehwqpu.com/Article/details/gtorjjjofy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlyqbqbm.html

[Q14] 存在则更新（upsert）
来源：http://dali.pengpengdd.cyou/Article/details/gtjspyrrcc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sweek.top/Article/details/gthubobmvb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nwbrower.top/Article/details/gtrllmfswu.html

[Q15] 查询全部
来源：http://dali.yanxiufei.cn/Article/details/gtccxvdwfm.html

SELECT * FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtvtcghwwo.html

[Q16] 查询指定列
来源：http://dali.birdmap.top/Article/details/gthqhezbkg.html

SELECT id, name FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtgtaaqcpg.html

[Q17] 条件查询
来源：http://dali.gzhubu.top/Article/details/gtagbaifbc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sxryk.cn/Article/details/gtzekocdmj.html

[Q18] 模糊匹配
来源：http://dali.gzhubu.top/Article/details/gtaahcaavq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yueranfly.top/Article/details/gtahbennto.html

[Q19] 范围查询
来源：http://dali.jianghu66.top/Article/details/gtzyrrgeyj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.meibo888.top/Article/details/gtqsuexqhk.html

[Q20] IN 列表
来源：http://dali.gzhubu.top/Article/details/gtindsmvgb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guannengcc.top/Article/details/gtblxbheiw.html

[Q21] 空值判断
来源：http://dali.hywenlv.cn/Article/details/gtuzszebov.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxuanxn.top/Article/details/gtrpzlbjil.html

[Q22] 排序
来源：http://dali.xziqi.cn/Article/details/gtxgmrvhxh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shangyingyoupin.top/Article/details/gtdbtphbfj.html

[Q23] 分页
来源：http://dali.yueranfly.top/Article/details/gtgrtxkrsj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.havefunace.top/Article/details/gtumdcgebt.html

[Q24] 去重
来源：http://dali.xuanzx.com/Article/details/gtrdpkwvic.html

SELECT DISTINCT city FROM users;
来源：http://dali.ivvv.top/Article/details/gtesgkpend.html

[Q25] 只取前 N 条
来源：http://dali.shzxlz.cn/Article/details/gtvrblnryn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daxiang520.top/Article/details/gtevvyyiwy.html

[Q26] 计数
来源：http://dali.jinghuilouyu.cn/Article/details/gtpexqppmc.html

SELECT COUNT(*) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtusqrtepu.html

[Q27] 条件计数
来源：http://dali.hywenlv.cn/Article/details/gtwleiougr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtrhbxyncf.html

[Q28] 求和与平均
来源：http://dali.jinqigufen.top/Article/details/gtcdcssjpe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtveuzvmfo.html

[Q29] 最大最小值
来源：http://dali.c1oappe.top/Article/details/gtpiqcqqzj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtvtqhpmrr.html

[Q30] 分组统计
来源：http://dali.jianghu66.top/Article/details/gtfwwwrwwd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gtfuulstzj.html

[Q31] 分组后过滤
来源：http://dali.cdnleiting.top/Article/details/gtmaunjzcm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ybcxt.top/Article/details/gtpvcdmkjl.html

[Q32] 分组拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtjlvuyplm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gthkoberzv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gogol.net.cn/Article/details/gtyeoqgquh.html

[Q33] 多列分组
来源：http://dali.nwbrower.top/Article/details/gtyoadlmry.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shangyingyoupin.top/Article/details/gtuultqfzg.html

[Q34] 每组取第一条
来源：http://dali.guannengcc.top/Article/details/gtlybisoao.html

SELECT * FROM (
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslfpltko.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jlsjyb.cn/Article/details/gtgpodsymn.html

) t WHERE rn = 1;
来源：http://dali.cheryme.top/Article/details/gtgabmhmnj.html

[Q35] 内连接
来源：http://dali.tianlin.xyz/Article/details/gtwhtughoa.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gtnpqpofyo.html

[Q36] 左连接
来源：http://dali.shzxlz.cn/Article/details/gteazoqsye.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gtyrukffeh.html

[Q37] 右连接
来源：http://dali.hysaishi.cn/Article/details/gtebvkwzow.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sxryk.cn/Article/details/gtovligeph.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.c1oappe.top/Article/details/gtgxcsequq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhixingplan.top/Article/details/gtxxinqixk.html

[Q39] 自连接（查上下级）
来源：http://dali.chenjidiqi.icu/Article/details/gtpiccaetx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldfpacjo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.snrcjt.cn/Article/details/gtehslpfrb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.fengsongda.top/Article/details/gtysxaxgyc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenlongwang.top/Article/details/gtukwkbldf.html

[Q41] 多表连接
来源：http://dali.tianlin.xyz/Article/details/gtsbfdlfct.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jqgfzy.top/Article/details/gtzuhymfjg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.0kj1m.cn/Article/details/gtvolkzfrm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gttqdrmoye.html

[Q42] 连接条件附加过滤
来源：http://dali.meibo888.top/Article/details/gtibfukyse.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yueranfly.top/Article/details/gtxicxlceo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgoldqmek.html

[Q43] 标量子查询
来源：http://dali.jqgfzy.top/Article/details/gtdbxdiikr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yangfankeji.com/Article/details/gtbeexhqzp.html

[Q44] IN 子查询
来源：http://dali.feifeiyinyue.top/Article/details/gtyahkprpf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cqqwz.cn/Article/details/gtfmanfzhg.html

[Q45] EXISTS 判断存在
来源：http://dali.yonumen.top/Article/details/gtucfnmyxz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gotoacloud.top/Article/details/gtzsqpstux.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiaglxqtc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.andypj.xyz/Article/details/gtjbeznnsd.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gtsjxfsqqp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fengsongda.top/Article/details/gtjvhthyss.html

[Q48] CTE 公用表表达式
来源：http://dali.dashuyun.cn/Article/details/gtpmbljsun.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.snrcjt.cn/Article/details/gtmcaacxwk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sxryk.cn/Article/details/gttowucjlm.html

[Q49] 更新单行
来源：http://dali.sweek.top/Article/details/gtmiqjolar.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gtbaagdaba.html

[Q50] 批量更新
来源：http://dali.zhengqikj.top/Article/details/gtnxjimkmm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenjidiqi.icu/Article/details/gtexovcwmw.html

[Q51] 用子查询更新
来源：http://dali.pycfn.com/Article/details/gtgizxbrky.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fengsongda.top/Article/details/gteldjwhmm.html

[Q52] 删除指定行
来源：http://dali.ivvv.top/Article/details/gtypuuxeuj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gtixftaxlu.html

[Q53] 按条件删除
来源：http://dali.gotoacloud.top/Article/details/gtsyjcakqa.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxinkj.top/Article/details/gtidmmwpmb.html

[Q54] 清空表
来源：http://dali.ehwqpu.com/Article/details/gtswzywmex.html

TRUNCATE TABLE logs;
来源：http://dali.sysykeji.top/Article/details/gttyiacdfd.html

[Q55] 排名（并列占位）
来源：http://dali.wangdashe.top/Article/details/gtlaftifgu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.c1oappe.top/Article/details/gtqsxkdujy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shzxlz.cn/Article/details/gtncknmsrk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gtgqbpowjh.html

[Q57] 行号
来源：http://dali.chenlongwang.top/Article/details/gtxiobqokr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtazmvpcmm.html

[Q58] 累计求和
来源：http://dali.pengpengdd.cyou/Article/details/gtukyrkjws.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtxehdswpp.html

[Q59] 分组内累计
来源：http://dali.ivvv.top/Article/details/gtmaqzuklu.html


<!-- 参考信息 -->