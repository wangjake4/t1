代发 wailian999

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cheryme.top/Article/details/gtbbbunuoh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangshuangyany.cn/Article/details/gtueuecguz.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhyadtru.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.kuanghao11.cn/Article/details/gtnbhsdgys.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.haohaochexian.top/Article/details/gtunbsrkwx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.snrcjt.cn/Article/details/gtbsjehsqh.html

[N11] 二叉树中序遍历
来源：http://dali.fzhhl.top/Article/details/gtshrllpxv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhengqikj.top/Article/details/gtulomqyze.html

PHP:  // 手写递归函数
来源：http://dali.hywenlv.cn/Article/details/gttfvniznr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.vqdsnc.cn/Article/details/gtmlgdpbus.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenlongwang.top/Article/details/gtjxufecff.html

Java: // 手写递归
来源：http://dali.nwbrower.top/Article/details/gtppuyacpr.html

Go:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gtdazkuapf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.redwolf501.top/Article/details/gtzslcqixu.html

C#:   // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtsufrfpnb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fengsongda.top/Article/details/gtygygivga.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.c1oappe.top/Article/details/gtrigptone.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxinkj.top/Article/details/gtqzlapbaq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gtndfjgepe.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cucudq.cn/Article/details/gtnkooeusg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gtrxrrdmpz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aibaodan.cn/Article/details/gttxidllsd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.quarkkingdee.top/Article/details/gtceepjywe.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gtdnmwzbyz.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtdbjslfdi.html

O. 并发与异步
来源：http://dali.birdmap.top/Article/details/gtrkjzfdet.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtmxjivjxs.html

[O01] 启动一个线程
来源：http://dali.gogol.net.cn/Article/details/gttnemooqi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.redwolf501.top/Article/details/gtvtwmvycp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.wangshuangyany.cn/Article/details/gtofuxwiuw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhengqikj.top/Article/details/gteeawnlxh.html

TS:   // 同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaglojfib.html

Java: new Thread(() -> f()).start()
来源：http://dali.xinyue.icu/Article/details/gtwdcrhzib.html

Go:   go f()
来源：http://dali.nwbrower.top/Article/details/gtleuhohcn.html

Ruby: Thread.new { f }
来源：http://dali.smart0.xyz/Article/details/gtcvvizwww.html

C#:   Task.Run(() => F());
来源：http://dali.sweek.top/Article/details/gtvderxken.html

[O02] 使用线程池
来源：http://dali.nwbrower.top/Article/details/gttutiuppx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jlsjyb.cn/Article/details/gtlsijpfeu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenzaomai.com/Article/details/gtrvpdjfyh.html

JS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gtlnbbsfkl.html

TS:   // worker_threads 线程池
来源：http://dali.hysaishi.cn/Article/details/gtbichdvnt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.andypj.xyz/Article/details/gterolrvjq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yongpay.top/Article/details/gtaemhhccb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.snrcjt.cn/Article/details/gthhbhkhws.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yongpay.top/Article/details/gthsxbkuhu.html

[O03] 加锁保护共享数据
来源：http://dali.shanyushiyangtech.top/Article/details/gtfktywqmp.html

Py:   with lock: shared += 1
来源：http://dali.hnxiangtu.top/Article/details/gtvwxnakkx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zycfv.cn/Article/details/gtzbypocbd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yuxming.cn/Article/details/gtmjcpijis.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcrtcnls.html

Java: synchronized (this) { shared++; }
来源：http://dali.birdmap.top/Article/details/gtqwvpowqz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenjidiqi.icu/Article/details/gtfxwkcyet.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yangfankeji.com/Article/details/gtleauictv.html

C#:   lock (gate) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gtdkttrrej.html

[O04] 定义异步函数并等待
来源：http://dali.yj202588.top/Article/details/gthbccofnc.html

Py:   async def f():⏎    await g()
来源：http://dali.xinyue.icu/Article/details/gtdrvdlaog.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.mhx1999.top/Article/details/gtnicuqvuk.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258888.top/Article/details/gtzeddackj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jianghu66.top/Article/details/gtfuqvatog.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ehwqpu.com/Article/details/gtswkzdeji.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jianghu66.top/Article/details/gtxkygdpya.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pycfn.com/Article/details/gtlwipfcnq.html

C#:   async Task F() { await G(); }
来源：http://dali.xuanzx.com/Article/details/gtvzfdycbc.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenlongwang.top/Article/details/gtmktevofg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gaohongyu789.top/Article/details/gtqwnawyqa.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tianlin.xyz/Article/details/gtovbidajv.html

JS:   await Promise.all(tasks)
来源：http://dali.cqqwz.cn/Article/details/gttcxribwv.html

TS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gtpdqqpcnh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigufen.top/Article/details/gtxvguhpcj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhongyouzk.top/Article/details/gtpauujvgj.html

Ruby: threads.map(&:join)
来源：http://dali.gzhubu.top/Article/details/gtdgxrkisr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guowangkeji.top/Article/details/gttzaubfwg.html

[O06] 使用进程池
来源：http://dali.zhengqikj.top/Article/details/gtrhatzcgu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xziqi.cn/Article/details/gtttgkwaml.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhiwuduotai.top/Article/details/gtjxcehzsy.html

JS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gtfsnrearx.html

TS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gtailwaynd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jianghu66.top/Article/details/gtlpvzvkkd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.redwolf501.top/Article/details/gtoxivoinw.html

Ruby: // fork 块
来源：http://dali.wangshuangyany.cn/Article/details/gtfjnmjciu.html

C#:   Parallel.For
来源：http://dali.zhoulong.xyz/Article/details/gtvpwgjjuo.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtzgtayrxo.html

P. 常用工具函数
来源：http://dali.vqdsnc.cn/Article/details/gtslmtgofu.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtmmcyjlgn.html

[P01] 生成 UUID
来源：http://dali.cashguo.top/Article/details/gtaksehfxl.html

Py:   str(uuid.uuid4())
来源：http://dali.dashuyun.cn/Article/details/gtiwfluxan.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cqqwz.cn/Article/details/gtzxdcstof.html

JS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gtgjehshuu.html

TS:   crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gtygvtqryp.html

Java: UUID.randomUUID().toString()
来源：http://dali.xylfe.cn/Article/details/gtutksncxo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yanxiufei.cn/Article/details/gtgomsxght.html

Ruby: SecureRandom.uuid
来源：http://dali.yonumen.top/Article/details/gtjvlhnykn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebngjuls.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgufenzy.top/Article/details/gtjhfndjat.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.aibaodan.cn/Article/details/gtbgylhdww.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinqigfzy.top/Article/details/gtwmbmekit.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258.top/Article/details/gthpphmxlc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgufenzy.top/Article/details/gtlzmxieoi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daxiang520.top/Article/details/gtwalbphrb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj20258888.top/Article/details/gtviapsxun.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sufxvd.cn/Article/details/gtgpxvnvev.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnxiangtu.top/Article/details/gtwvoknhyd.html

[P03] 生成短随机字符串
来源：http://dali.guowangkeji.top/Article/details/gtkjkkgxnu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtebzpwtun.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.feifeiyinyue.top/Article/details/gtwzxxaoho.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gtxsrrydgk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gtukhqbhjv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jyoumei.cn/Article/details/gtthokgpbl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yongpay.top/Article/details/gthtwezowj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenzaomai.com/Article/details/gtojatauhw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.quarkkingdee.top/Article/details/gtkdttjwmb.html

[P04] 求长度
来源：http://dali.vqdsnc.cn/Article/details/gtpjpufgjv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.andypj.xyz/Article/details/gtushtoqox.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gttkuebdov.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daria6918.cn/Article/details/gtqpfhoydh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dashuyun.cn/Article/details/gtglidtzhi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnqzz.top/Article/details/gtzjkhybmu.html

Go:   len(arr);  len(m)
来源：http://dali.yueranfly.top/Article/details/gtlkrbaxxp.html

Ruby: x.length;  x.size
来源：http://dali.ydzc1.top/Article/details/gtxbzcnywg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gtttzqhagk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj202588.top/Article/details/gtmhpexvrv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cucudq.cn/Article/details/gtutalsbfn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.snrcjt.cn/Article/details/gttnaftznv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xuanzx.com/Article/details/gtcgugzaks.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gtohwyiuzf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jiagoushi.top/Article/details/gtxhvvopjz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.havefunace.top/Article/details/gtizmxvggj.html

Ruby: a == b
来源：http://dali.316326.xyz/Article/details/gtdzdtfzdm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.pycfn.com/Article/details/gtvviescsa.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ppjwa.cn/Article/details/gtnyiursqh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.0kj1m.cn/Article/details/gtzgpmdqkj.html

PHP:  if (empty($x)) {}
来源：http://dali.meibo888.top/Article/details/gtmkwaebuz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.bjfxy.top/Article/details/gtmavhcabj.html

TS:   if (x == null) {}
来源：http://dali.iojbl.cn/Article/details/gtzhdzcflc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.vqdsnc.cn/Article/details/gtcpuxsmjg.html

Go:   if x == nil {}
来源：http://dali.andypj.xyz/Article/details/gtglegzdpj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tian-w.cn/Article/details/gtgprwvtmc.html

C#:   if (x is null) {}
来源：http://dali.yuxming.cn/Article/details/gtelqvcydx.html

[P07] 防抖与节流
来源：http://dali.chenlongwang.top/Article/details/gtyuewbwfg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.birdmap.top/Article/details/gtllvzvocq.html

PHP:  // 手写时间戳比较
来源：http://dali.hnqzz.top/Article/details/gtasezihxg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gtqlctnejv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gtvcktpawc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fengsongda.top/Article/details/gtoiuvhkhh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daxiang520.top/Article/details/gtqdlczexi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ybcxt.top/Article/details/gtnaychwed.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.0kj1m.cn/Article/details/gtfwzbtmsa.html

[P08] 处理浮点精度问题
来源：http://dali.gaohongyu789.top/Article/details/gtnhwrgfoh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.vqdsnc.cn/Article/details/gtvdotzmpv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shzxlz.cn/Article/details/gtjlunedrj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.guowangkeji.top/Article/details/gtaiiuifjs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinqigufen.top/Article/details/gtlhbydusw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ybcxt.top/Article/details/gtlulfzfhf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dashuyun.cn/Article/details/gtsrkmdmal.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhengqikj.top/Article/details/gtfdrzxehl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guannengcc.top/Article/details/gtvzmfrrai.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtlackxurj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.fzhhl.top/Article/details/gtffatlopp.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gthdotegny.html

[Q01] 创建表
来源：http://dali.gotoacloud.top/Article/details/gtlbzfnhnq.html

CREATE TABLE users (
来源：http://dali.xuanzx.com/Article/details/gtcqooxtrc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gthidwldpr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangtech.top/Article/details/gtppuoydng.html

email VARCHAR(100) UNIQUE,
来源：http://dali.feifeiyinyue.top/Article/details/gtslirqgsd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cashguo.top/Article/details/gtfexjmzdk.html

);
来源：http://dali.jianghu66.top/Article/details/gtowujjreq.html

[Q02] 创建带外键的表
来源：http://dali.xziqi.cn/Article/details/gtwtocxnzs.html

CREATE TABLE orders (
来源：http://dali.daria6918.cn/Article/details/gthblkysxf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gtkgvpnuxz.html

user_id INT NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gtawhxrara.html

amount DECIMAL(10, 2),
来源：http://dali.yvedp.cn/Article/details/gtkozaened.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuanzx.com/Article/details/gtoxztpqyg.html

);
来源：http://dali.guannengcc.top/Article/details/gtxrhkkidq.html

[Q03] 增加列
来源：http://dali.shuidangran.top/Article/details/gtutitbnvf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zycfv.cn/Article/details/gtkjbhhudq.html

[Q04] 修改列类型
来源：http://dali.hfpthk.cn/Article/details/gtrwozusni.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cashguo.top/Article/details/gthpovqsaq.html

[Q05] 重命名列
来源：http://dali.jinqigfzy.top/Article/details/gtlawnmksu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xylfe.cn/Article/details/gtqpzmihfs.html

[Q06] 删除列
来源：http://dali.zdqjudy.top/Article/details/gtpacowzdg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.pycfn.com/Article/details/gtoarhbaen.html

[Q07] 删除表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatykdydz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jyoumei.cn/Article/details/gtkyefpjnm.html

[Q08] 创建普通索引
来源：http://dali.hysaishi.cn/Article/details/gtalrkbpvs.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gtjdcrnoav.html

[Q09] 创建唯一索引
来源：http://dali.cdnleiting.top/Article/details/gtjhrdwffo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gtmksqskfk.html

[Q10] 插入单行
来源：http://dali.haohaochexian.top/Article/details/gtodwxrvra.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ydzc1.top/Article/details/gtqbssghop.html

[Q11] 一次插入多行
来源：http://dali.shuidangran.top/Article/details/gtyfbxttfn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyidqdzvy.html

[Q12] 插入后取自增 ID
来源：http://dali.nwbrower.top/Article/details/gtbbpigfyc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pengpengdd.cyou/Article/details/gtjsuwcnmk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258.top/Article/details/gtygrakjcz.html

[Q13] 忽略重复插入
来源：http://dali.svipenyu.cn/Article/details/gtxkksovsd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenlongwang.top/Article/details/gthzzqcyyu.html

[Q14] 存在则更新（upsert）
来源：http://dali.ivvv.top/Article/details/gtnfqrqpoz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgfzy.top/Article/details/gtivaumnil.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shuidangran.top/Article/details/gtmidxnyoq.html

[Q15] 查询全部
来源：http://dali.hywenlv.cn/Article/details/gtnqmpbrhc.html

SELECT * FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbyynbodh.html

[Q16] 查询指定列
来源：http://dali.zhiwuduotai.top/Article/details/gtupjjeqyd.html

SELECT id, name FROM users;
来源：http://dali.redwolf501.top/Article/details/gtkwpnnmge.html

[Q17] 条件查询
来源：http://dali.tianlin.xyz/Article/details/gtsppukhmu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sweek.top/Article/details/gtukwpydvj.html

[Q18] 模糊匹配
来源：http://dali.iojbl.cn/Article/details/gtiahldazx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cucudq.cn/Article/details/gtqknadcqv.html

[Q19] 范围查询
来源：http://dali.jlsjyb.cn/Article/details/gtsfngagiv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnncozzks.html

[Q20] IN 列表
来源：http://dali.wangshuangyany.cn/Article/details/gtujylxzmb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhixingplan.top/Article/details/gtxmfibved.html

[Q21] 空值判断
来源：http://dali.sxryk.cn/Article/details/gtylwhywmo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sweek.top/Article/details/gtqkpidgkq.html

[Q22] 排序
来源：http://dali.yonumen.top/Article/details/gtualywmzk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sxryk.cn/Article/details/gtzmgmjerc.html

[Q23] 分页
来源：http://dali.zhiwuduotai.top/Article/details/gtpxafobqz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenjidiqi.icu/Article/details/gtdbzbvlxk.html

[Q24] 去重
来源：http://dali.nwbrower.top/Article/details/gtxliqakvu.html

SELECT DISTINCT city FROM users;
来源：http://dali.hammf.cn/Article/details/gteagbqkqc.html

[Q25] 只取前 N 条
来源：http://dali.sweek.top/Article/details/gtdcesqwke.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yonumen.top/Article/details/gtytoxdspo.html

[Q26] 计数
来源：http://dali.redwolf501.top/Article/details/gtylxgqswg.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtqteicunn.html

[Q27] 条件计数
来源：http://dali.hnxiangtu.top/Article/details/gtcmhbqeub.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtctsscksv.html

[Q28] 求和与平均
来源：http://dali.c1oappe.top/Article/details/gtzdswigqn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtohwmmjrf.html

[Q29] 最大最小值
来源：http://dali.pycfn.com/Article/details/gtctpioqat.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtiaavdzeu.html

[Q30] 分组统计
来源：http://dali.guannengcc.top/Article/details/gtevjjuouw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtwkuoecvp.html

[Q31] 分组后过滤
来源：http://dali.zhengqikj.top/Article/details/gtfmigulcj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tanke756.top/Article/details/gtvzejhlyt.html

[Q32] 分组拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtpkdxomuc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gtjqdhnppt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xziqi.cn/Article/details/gtmaltbqlr.html

[Q33] 多列分组
来源：http://dali.sysykeji.top/Article/details/gtxjjvqnve.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhoulong.xyz/Article/details/gtiagzdyiq.html

[Q34] 每组取第一条
来源：http://dali.316326.xyz/Article/details/gttzdntiaz.html

SELECT * FROM (
来源：http://dali.9152youxi.cn/Article/details/gtzlvrinlj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sxryk.cn/Article/details/gttssmjuui.html

) t WHERE rn = 1;
来源：http://dali.hywenlv.cn/Article/details/gtzcuxiyeg.html

[Q35] 内连接
来源：http://dali.fengsongda.top/Article/details/gtegpuafmc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gtmnsawfkf.html

[Q36] 左连接
来源：http://dali.dashuyun.cn/Article/details/gtxohvnpnt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfthptpv.html

[Q37] 右连接
来源：http://dali.haohaochexian.top/Article/details/gtzaxnhqkl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.fzhhl.top/Article/details/gtutrprcrr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.meibo888.top/Article/details/gteygpzbsg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.iojbl.cn/Article/details/gtkvvqzvcq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhengqikj.top/Article/details/gtbxysybui.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.meibo888.top/Article/details/gtvcjdwpty.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jqgfzy.top/Article/details/gtxgowrfiy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhoulong.xyz/Article/details/gtvfyxjbcq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jianghu66.top/Article/details/gttqgwwqxl.html

[Q41] 多表连接
来源：http://dali.9152youxi.cn/Article/details/gtctulosny.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhowcnup.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xziqi.cn/Article/details/gtcldvwqyr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ydzc1.top/Article/details/gtnmsmepkk.html

[Q42] 连接条件附加过滤
来源：http://dali.yuxming.cn/Article/details/gtjrffkenc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.0kj1m.cn/Article/details/gtaioqxhtg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nwbrower.top/Article/details/gtfzfzmiue.html

[Q43] 标量子查询
来源：http://dali.wangshuangyany.cn/Article/details/gtpdcyaneu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shzxlz.cn/Article/details/gtijveknjv.html

[Q44] IN 子查询
来源：http://dali.dianchejie.cn/Article/details/gtpdxbbyfa.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xuetiantiany.cn/Article/details/gtvfhrekig.html

[Q45] EXISTS 判断存在
来源：http://dali.sysykeji.top/Article/details/gteqwcmndv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gtnkblljhg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yanxiufei.cn/Article/details/gtzcgvoepe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gtpqslnsle.html

[Q47] 与平均值比较
来源：http://dali.cqqwz.cn/Article/details/gtdeeeyplr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hywenlv.cn/Article/details/gtjkdchltk.html

[Q48] CTE 公用表表达式
来源：http://dali.tian-w.cn/Article/details/gtvspbcjca.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gzhubu.top/Article/details/gtgzaxlwbb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.redwolf501.top/Article/details/gtspywplcr.html

[Q49] 更新单行
来源：http://dali.ydzc1.top/Article/details/gtqexmnusl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtrgpymhor.html

[Q50] 批量更新
来源：http://dali.hysaishi.cn/Article/details/gtlqdhtxlr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.feifeiyinyue.top/Article/details/gtevjnfhho.html

[Q51] 用子查询更新
来源：http://dali.gotoacloud.top/Article/details/gtprihpeng.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtullzpfti.html

[Q52] 删除指定行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxgmypkf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gtgkepfngs.html

[Q53] 按条件删除
来源：http://dali.yongpay.top/Article/details/gtaduzyqnq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gthwfsuksv.html

[Q54] 清空表
来源：http://dali.gzhubu.top/Article/details/gtxfmakoxq.html

TRUNCATE TABLE logs;
来源：http://dali.yj202588.top/Article/details/gtxjigbtbx.html

[Q55] 排名（并列占位）
来源：http://dali.gzhubu.top/Article/details/gtzpyzdalt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.kuanghao11.cn/Article/details/gtwafsdhmo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.bjfxy.top/Article/details/gtpfcdxwhj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj202588.top/Article/details/gtvyowpudc.html

[Q57] 行号
来源：http://dali.tanke756.top/Article/details/gtxvxscput.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtiogfyazk.html

[Q58] 累计求和
来源：http://dali.smart0.xyz/Article/details/gtolrvdogw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtzafjwjri.html

[Q59] 分组内累计
来源：http://dali.ppjwa.cn/Article/details/gtxpndswhy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtgsnvovdr.html

[Q60] 取上一行 / 下一行
来源：http://dali.cheryme.top/Article/details/gtccpesngh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj202588.top/Article/details/gttnxmkucq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnovlpckq.html


<!-- 参考信息 -->