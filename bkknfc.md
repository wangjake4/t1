代发 wailian999

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ehwqpu.com/Article/details/gtyhfzmaee.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.snrcjt.cn/Article/details/gtjpppqaib.html

Java: class Node { int v; Node next; }
来源：http://dali.bjfxy.top/Article/details/gtkwytspvs.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hnqzz.top/Article/details/gtaprrgzdk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xziqi.cn/Article/details/gtniavaapd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jianghu66.top/Article/details/gtyvzowzlk.html

[N11] 二叉树中序遍历
来源：http://dali.xuanzx.com/Article/details/gtifxxszlq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenzaomai.com/Article/details/gtctyedfqs.html

PHP:  // 手写递归函数
来源：http://dali.jyoumei.cn/Article/details/gtztyzilfv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gtgmdgsfuq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.haohaochexian.top/Article/details/gtlxauugfe.html

Java: // 手写递归
来源：http://dali.yj202588.top/Article/details/gtqjoprumt.html

Go:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gtsgxawdig.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shangyingyoupin.top/Article/details/gtmpmoanyo.html

C#:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gtrnyhusxo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yuxming.cn/Article/details/gtrwbqmqop.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.smart0.xyz/Article/details/gtbjtwylys.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.bjfxy.top/Article/details/gtokackpow.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gtdgirbkzh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gtheezvfbe.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gtfwfyflwl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yangfankeji.com/Article/details/gtmdxpioza.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gaohongyu789.top/Article/details/gtvxwmnntx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gtibwgyuce.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtqibymijn.html

O. 并发与异步
来源：http://dali.wangshuangyany.cn/Article/details/gthauaumyw.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtuuyyilxx.html

[O01] 启动一个线程
来源：http://dali.kuanghao11.cn/Article/details/gtojklajev.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.haohaochexian.top/Article/details/gtaudzorzy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.fzhhl.top/Article/details/gtsonzsvms.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgufenzy.top/Article/details/gtaxbudaku.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gtocsdsxur.html

Java: new Thread(() -> f()).start()
来源：http://dali.ivvv.top/Article/details/gtuezkqolm.html

Go:   go f()
来源：http://dali.gaohongyu789.top/Article/details/gtbwmdjpfz.html

Ruby: Thread.new { f }
来源：http://dali.gaohongyu789.top/Article/details/gtzdzoebmy.html

C#:   Task.Run(() => F());
来源：http://dali.fzhhl.top/Article/details/gtbdhmokzk.html

[O02] 使用线程池
来源：http://dali.yj202588.top/Article/details/gtbiqmbezr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigfzy.top/Article/details/gtgthmnnvj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yanxiufei.cn/Article/details/gtdyeordju.html

JS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gtjljlhocz.html

TS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gtvckauucw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigfzy.top/Article/details/gtdfjjpxuh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gtyklazhga.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.316326.xyz/Article/details/gtkdtzmhaf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.daria6918.cn/Article/details/gtxpgykfpz.html

[O03] 加锁保护共享数据
来源：http://dali.cheryme.top/Article/details/gtefjqmcdv.html

Py:   with lock: shared += 1
来源：http://dali.nwbrower.top/Article/details/gtkhztnaoi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.vqdsnc.cn/Article/details/gtvwzvouer.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj20258888.top/Article/details/gtpijlhhtq.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gtuebegalh.html

Java: synchronized (this) { shared++; }
来源：http://dali.daxiang520.top/Article/details/gttrkdrgyp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jianghu66.top/Article/details/gtfdehjcqo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hysaishi.cn/Article/details/gtgsxwdsko.html

C#:   lock (gate) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtkbnxjiwh.html

[O04] 定义异步函数并等待
来源：http://dali.pycfn.com/Article/details/gtgzsdhozw.html

Py:   async def f():⏎    await g()
来源：http://dali.jyoumei.cn/Article/details/gtadrldpaf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgufenzy.top/Article/details/gtvrejyzoo.html

JS:   async function f() { await g(); }
来源：http://dali.vqdsnc.cn/Article/details/gtrxamnrkd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gtpjwnwwcy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ivvv.top/Article/details/gtedglczfo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shangyingyoupin.top/Article/details/gthdgcijlt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhiwuduotai.top/Article/details/gtmunakosf.html

C#:   async Task F() { await G(); }
来源：http://dali.tanke756.top/Article/details/gtrebtpbdy.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhixingplan.top/Article/details/gtpqwirhbz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gtreupzoav.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunllecrp.html

JS:   await Promise.all(tasks)
来源：http://dali.ydzc1.top/Article/details/gtpdhkcbic.html

TS:   await Promise.all(tasks)
来源：http://dali.sweek.top/Article/details/gtrxflecus.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.9152youxi.cn/Article/details/gtsnpctxrf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.bjfxy.top/Article/details/gtphmvaqhx.html

Ruby: threads.map(&:join)
来源：http://dali.dashuyun.cn/Article/details/gtwvcatlmz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cucudq.cn/Article/details/gtndddmujt.html

[O06] 使用进程池
来源：http://dali.chenlongwang.top/Article/details/gtufyhvsfu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cdnleiting.top/Article/details/gtjldvyxds.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.feifeiyinyue.top/Article/details/gtyixplwrr.html

JS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gtxlisigsw.html

TS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gtshsdvgao.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.andypj.xyz/Article/details/gtwbchaogw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hysaishi.cn/Article/details/gtofqinkzc.html

Ruby: // fork 块
来源：http://dali.daria6918.cn/Article/details/gtanbvahio.html

C#:   Parallel.For
来源：http://dali.redwolf501.top/Article/details/gtrexnjpcv.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtsqmgvlqo.html

P. 常用工具函数
来源：http://dali.shuidangran.top/Article/details/gtjgwlpuix.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtatdabbll.html

[P01] 生成 UUID
来源：http://dali.aibaodan.cn/Article/details/gtjzuiuimn.html

Py:   str(uuid.uuid4())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqlfsnuj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ydzc1.top/Article/details/gtiqtwoynh.html

JS:   crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gtiabivzpx.html

TS:   crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gtyhzabpvp.html

Java: UUID.randomUUID().toString()
来源：http://dali.tianlin.xyz/Article/details/gthlmyoxqk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yanxiufei.cn/Article/details/gtjzufzaof.html

Ruby: SecureRandom.uuid
来源：http://dali.fengsongda.top/Article/details/gtdhimrvbs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtcjkmow.html

[P02] MD5 / SHA256 摘要
来源：http://dali.smart0.xyz/Article/details/gtdbqemwcv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.fzhhl.top/Article/details/gtguldwnmo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258888.top/Article/details/gtiixxtipi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258.top/Article/details/gtoepwcpxi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.pengpengdd.cyou/Article/details/gtvawfwavv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258888.top/Article/details/gteluvxjqv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.haohaochexian.top/Article/details/gtoaxburze.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.birdmap.top/Article/details/gtkqelfgka.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhengqikj.top/Article/details/gtzpvqlqra.html

[P03] 生成短随机字符串
来源：http://dali.gzhubu.top/Article/details/gtqdjqnbtp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.dashuyun.cn/Article/details/gtyckvxxyd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shzxlz.cn/Article/details/gtngogkeiw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqgxzghx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gtpeknnflw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtojgasond.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.meibo888.top/Article/details/gtzmauxgfb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jiagoushi.top/Article/details/gtbmvmntjx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nanxuanxn.top/Article/details/gtsbpzmdze.html

[P04] 求长度
来源：http://dali.xylfe.cn/Article/details/gtghgtjodu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.haohaochexian.top/Article/details/gtftietgga.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtbltnlxie.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tanke756.top/Article/details/gtqwwmjzts.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cdnleiting.top/Article/details/gtgikhfsdn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xylfe.cn/Article/details/gtyhxxmwot.html

Go:   len(arr);  len(m)
来源：http://dali.sufxvd.cn/Article/details/gtizdesxky.html

Ruby: x.length;  x.size
来源：http://dali.ivvv.top/Article/details/gtlppkvbsu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jyoumei.cn/Article/details/gtzoirzzym.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ybcxt.top/Article/details/gtdhjreugj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.aizwys.cn/Article/details/gtqlaeoimm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hfpthk.cn/Article/details/gtvzpnwhns.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hfpthk.cn/Article/details/gtjkfwdnpf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cucudq.cn/Article/details/gtoqivmkzc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.havefunace.top/Article/details/gtnbpnvqoy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gtkzzstprx.html

Ruby: a == b
来源：http://dali.feifeiyinyue.top/Article/details/gtvrkozyiz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hywenlv.cn/Article/details/gtsdxhxxhv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.dashuyun.cn/Article/details/gtvuqfjzbq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpkqoqux.html

PHP:  if (empty($x)) {}
来源：http://dali.sxryk.cn/Article/details/gtgwbwbyuw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hysaishi.cn/Article/details/gtfzqvkdyw.html

TS:   if (x == null) {}
来源：http://dali.jqgfzy.top/Article/details/gtpxwxoqnq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jlsjyb.cn/Article/details/gtrmpymlun.html

Go:   if x == nil {}
来源：http://dali.sxryk.cn/Article/details/gtqdhkhueh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jiagoushi.top/Article/details/gthqwknpxw.html

C#:   if (x is null) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxjmejvv.html

[P07] 防抖与节流
来源：http://dali.nanxinkj.top/Article/details/gtvwlwaxxf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jqgfzy.top/Article/details/gtzwkzqsnt.html

PHP:  // 手写时间戳比较
来源：http://dali.iojbl.cn/Article/details/gtoaxkjbth.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gtgngqibam.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tian-w.cn/Article/details/gtqhipcjgh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtcckkkxfv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenjidiqi.icu/Article/details/gtpysfbluj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cucudq.cn/Article/details/gtsokqusbl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.316326.xyz/Article/details/gttjxnioyw.html

[P08] 处理浮点精度问题
来源：http://dali.gogol.net.cn/Article/details/gtxntgdzdy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.quarkkingdee.top/Article/details/gtqchbvgwh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yangfankeji.com/Article/details/gtbrhrieqq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sweek.top/Article/details/gtxciugwrx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhixingplan.top/Article/details/gtbbowksxd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xziqi.cn/Article/details/gtvnydnfoj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.feifeiyinyue.top/Article/details/gtffzbmacj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.316326.xyz/Article/details/gtszqmbpnn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.birdmap.top/Article/details/gtpcncyugq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtwrrmdnay.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.iojbl.cn/Article/details/gtsewzsfup.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtobpwbuzp.html

[Q01] 创建表
来源：http://dali.nwbrower.top/Article/details/gteulfmmoo.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gtkenkfwyq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gteoozuwka.html

name VARCHAR(50) NOT NULL,
来源：http://dali.bjfxy.top/Article/details/gtnchyrdxj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.9152youxi.cn/Article/details/gtahbpswut.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcxbnmml.html

);
来源：http://dali.zhixingplan.top/Article/details/gtlaohkywn.html

[Q02] 创建带外键的表
来源：http://dali.yongpay.top/Article/details/gtqugyhsfl.html

CREATE TABLE orders (
来源：http://dali.0kj1m.cn/Article/details/gtmgkmekjh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gtcqdjjauh.html

user_id INT NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gtqypwnakp.html

amount DECIMAL(10, 2),
来源：http://dali.havefunace.top/Article/details/gtbgkiwxnz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.andypj.xyz/Article/details/gtzhezwwmk.html

);
来源：http://dali.yanxiufei.cn/Article/details/gtytemzgdl.html

[Q03] 增加列
来源：http://dali.gzhubu.top/Article/details/gtzmuhkfps.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenzaomai.com/Article/details/gtspjqtrwv.html

[Q04] 修改列类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnwmoztm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.316326.xyz/Article/details/gtzwqkobdo.html

[Q05] 重命名列
来源：http://dali.tanke756.top/Article/details/gttcsrhoib.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnxiangtu.top/Article/details/gtsfjtdvrh.html

[Q06] 删除列
来源：http://dali.yueranfly.top/Article/details/gtrdfuqpvl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.meibo888.top/Article/details/gtgwbfevun.html

[Q07] 删除表
来源：http://dali.jinghuilouyu.cn/Article/details/gtmupbkflj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cqqwz.cn/Article/details/gtjaapntgj.html

[Q08] 创建普通索引
来源：http://dali.dashuyun.cn/Article/details/gtgjvdvahu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yonumen.top/Article/details/gteytflgph.html

[Q09] 创建唯一索引
来源：http://dali.yanxiufei.cn/Article/details/gtjraqxflc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gtygtbkimv.html

[Q10] 插入单行
来源：http://dali.cheryme.top/Article/details/gtmzhdguqq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gogol.net.cn/Article/details/gtzqicaxva.html

[Q11] 一次插入多行
来源：http://dali.gotoacloud.top/Article/details/gtbmfsszgm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtzpeqgixk.html

[Q12] 插入后取自增 ID
来源：http://dali.haohaochexian.top/Article/details/gtrcyglnwz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.bjfxy.top/Article/details/gtiushsaqo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dianchejie.cn/Article/details/gtnsqxjxxb.html

[Q13] 忽略重复插入
来源：http://dali.aizwys.cn/Article/details/gtipvgpkwx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gthvpvxdyo.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuanzx.com/Article/details/gteetrfalh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yonumen.top/Article/details/gtenqgzvpp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dianchejie.cn/Article/details/gtjhrntujf.html

[Q15] 查询全部
来源：http://dali.nwbrower.top/Article/details/gtcjjhrarq.html

SELECT * FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtffgxkezk.html

[Q16] 查询指定列
来源：http://dali.guannengcc.top/Article/details/gtdmzpdjhl.html

SELECT id, name FROM users;
来源：http://dali.fzhhl.top/Article/details/gtbrcrucmf.html

[Q17] 条件查询
来源：http://dali.tian-w.cn/Article/details/gtzgtxhshl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhengqikj.top/Article/details/gtgpsogyhr.html

[Q18] 模糊匹配
来源：http://dali.ybcxt.top/Article/details/gtphumacli.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhongyouzk.top/Article/details/gtukmzpqsz.html

[Q19] 范围查询
来源：http://dali.hfpthk.cn/Article/details/gttiqwwmkk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jianghu66.top/Article/details/gtrsddghoo.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gttxuegyjt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnqzz.top/Article/details/gtyecfpfte.html

[Q21] 空值判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefjhzjsi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnnhzpnm.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gtoerexxoa.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.haohaochexian.top/Article/details/gtbgevnbng.html

[Q23] 分页
来源：http://dali.redwolf501.top/Article/details/gtdtgobops.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.guannengcc.top/Article/details/gtizdttsjm.html

[Q24] 去重
来源：http://dali.daria6918.cn/Article/details/gtqtzrchft.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtkhboxieh.html

[Q25] 只取前 N 条
来源：http://dali.yvedp.cn/Article/details/gtpamreexr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hywenlv.cn/Article/details/gtmogwvbbh.html

[Q26] 计数
来源：http://dali.cashguo.top/Article/details/gtdbabxhtb.html

SELECT COUNT(*) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtumsjixkx.html

[Q27] 条件计数
来源：http://dali.hywenlv.cn/Article/details/gtswtukchl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtucddfgdr.html

[Q28] 求和与平均
来源：http://dali.jyoumei.cn/Article/details/gtcsrfjvkf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqrhuhwz.html

[Q29] 最大最小值
来源：http://dali.gzhubu.top/Article/details/gtvyvfdlba.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtzgaehpzb.html

[Q30] 分组统计
来源：http://dali.jinqigfzy.top/Article/details/gtkvtxnumt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gttewzmkbe.html

[Q31] 分组后过滤
来源：http://dali.guannengcc.top/Article/details/gtffprjkcs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cheryme.top/Article/details/gtvkfwjvkf.html

[Q32] 分组拼接字符串
来源：http://dali.daxiang520.top/Article/details/gtggyibhyc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtdhmiblvi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.0kj1m.cn/Article/details/gtzvzyrppl.html

[Q33] 多列分组
来源：http://dali.zhengqikj.top/Article/details/gtvdymfjxa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ppjwa.cn/Article/details/gtxdhrqxsf.html

[Q34] 每组取第一条
来源：http://dali.chenjidiqi.icu/Article/details/gtcrmfuyzv.html

SELECT * FROM (
来源：http://dali.haohaochexian.top/Article/details/gtgbjzpsuo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.andypj.xyz/Article/details/gtluglrcyo.html

) t WHERE rn = 1;
来源：http://dali.yj20258888.top/Article/details/gtmnctdimf.html

[Q35] 内连接
来源：http://dali.gotoacloud.top/Article/details/gtkptddrho.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gtxrgzcrda.html

[Q36] 左连接
来源：http://dali.dashuyun.cn/Article/details/gtappxftsm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gtwdlknknj.html

[Q37] 右连接
来源：http://dali.hnqzz.top/Article/details/gtqjhzqmtv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgufenzy.top/Article/details/gtfvcpkzej.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuetiantiany.cn/Article/details/gtwzgqcbht.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guannengcc.top/Article/details/gtomwhurub.html

[Q39] 自连接（查上下级）
来源：http://dali.yuxming.cn/Article/details/gtbagestbx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xinyue.icu/Article/details/gtdnhamqvt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.andypj.xyz/Article/details/gtfpmqanzs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gtbyebfsje.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhixingplan.top/Article/details/gtxthhtxnf.html

[Q41] 多表连接
来源：http://dali.chenlongwang.top/Article/details/gtvwevhpiv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guannengcc.top/Article/details/gtfwzemgoq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhixingplan.top/Article/details/gtzuxiitgk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yuanzhike.top/Article/details/gtovwxfmqf.html

[Q42] 连接条件附加过滤
来源：http://dali.316326.xyz/Article/details/gtpacgctov.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hywenlv.cn/Article/details/gtmlldxyak.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fengsongda.top/Article/details/gtcolvecnw.html

[Q43] 标量子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkblwoif.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdlcjyuhf.html

[Q44] IN 子查询
来源：http://dali.zhongyouzk.top/Article/details/gtmnmgxcww.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gotoacloud.top/Article/details/gtrnjbknrc.html

[Q45] EXISTS 判断存在
来源：http://dali.sufxvd.cn/Article/details/gthroxlmps.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gtvtqtacrw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.redwolf501.top/Article/details/gtyukceugm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gtfxlskcio.html

[Q47] 与平均值比较
来源：http://dali.zhiwuduotai.top/Article/details/gttowhwszs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cashguo.top/Article/details/gtrbospqjl.html

[Q48] CTE 公用表表达式
来源：http://dali.daria6918.cn/Article/details/gtowdndyee.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigufen.top/Article/details/gtkdhkijql.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258.top/Article/details/gtamniaspu.html

[Q49] 更新单行
来源：http://dali.xinyue.icu/Article/details/gtzoeodnmt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtyzpufjpc.html

[Q50] 批量更新
来源：http://dali.hongshengwenyu.top/Article/details/gtyfxsuyax.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xuanzx.com/Article/details/gtodyegklk.html

[Q51] 用子查询更新
来源：http://dali.aibaodan.cn/Article/details/gtgqikpows.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtcjxycynx.html

[Q52] 删除指定行
来源：http://dali.tianlin.xyz/Article/details/gtezddmcmz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtarucqxyr.html

[Q53] 按条件删除
来源：http://dali.yvedp.cn/Article/details/gtzlmurncj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.bjfxy.top/Article/details/gttorqgfbj.html

[Q54] 清空表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfyoqxalr.html

TRUNCATE TABLE logs;
来源：http://dali.hammf.cn/Article/details/gtqkbjipit.html

[Q55] 排名（并列占位）
来源：http://dali.pycfn.com/Article/details/gtfvsksqlv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gtlftycabf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.aibaodan.cn/Article/details/gtddrfzile.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gtleziwxoz.html

[Q57] 行号
来源：http://dali.yueranfly.top/Article/details/gtxiyiuyhb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtjbzxshvq.html

[Q58] 累计求和
来源：http://dali.xinyue.icu/Article/details/gtiuhaxins.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuxming.cn/Article/details/gthktqnbjl.html

[Q59] 分组内累计
来源：http://dali.meibo888.top/Article/details/gtmmxxoolt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtwyifllgk.html

[Q60] 取上一行 / 下一行
来源：http://dali.kuanghao11.cn/Article/details/gtpywasfbb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.vqdsnc.cn/Article/details/gtspmmqvzj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sxryk.cn/Article/details/gticqijemc.html


<!-- 参考信息 -->