代发 wailian999

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigufen.top/Article/details/gtwoingkbv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daria6918.cn/Article/details/gtsuetscft.html

Java: class Node { int v; Node next; }
来源：http://dali.wangdashe.top/Article/details/gtwardptjc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpffbmdep.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xziqi.cn/Article/details/gthzfqwimn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.wangdashe.top/Article/details/gtzzjpgrrp.html

[N11] 二叉树中序遍历
来源：http://dali.hammf.cn/Article/details/gtpnsiwtjb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.bjfxy.top/Article/details/gteqqolnxh.html

PHP:  // 手写递归函数
来源：http://dali.hysaishi.cn/Article/details/gtzgmsgrun.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gtjtijikvf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvftwovf.html

Java: // 手写递归
来源：http://dali.ybcxt.top/Article/details/gtmwtgvvgz.html

Go:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gtgdtgwqsj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cqqwz.cn/Article/details/gtrxwengqk.html

C#:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtaynzrnut.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.havefunace.top/Article/details/gtpgnppfbr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.meibo888.top/Article/details/gtcrczweuo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyqhthclv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fengsongda.top/Article/details/gtbjcgpdwk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gtviyqtcuu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gtyozqywhw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbfzqgvg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.quarkkingdee.top/Article/details/gtehgldigy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tianlin.xyz/Article/details/gtylzpluhi.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtaxpubqpa.html

O. 并发与异步
来源：http://dali.zycfv.cn/Article/details/gtofetnjif.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqvsvbfg.html

[O01] 启动一个线程
来源：http://dali.tianlin.xyz/Article/details/gtezmsndgx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jianghu66.top/Article/details/gtzmsjyoex.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xylfe.cn/Article/details/gtmhcvotgg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.iojbl.cn/Article/details/gtfclhsxfq.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gtyjmqvorl.html

Java: new Thread(() -> f()).start()
来源：http://dali.yongpay.top/Article/details/gtqovwihwe.html

Go:   go f()
来源：http://dali.chenjidiqi.icu/Article/details/gtdynmcygb.html

Ruby: Thread.new { f }
来源：http://dali.fzhhl.top/Article/details/gtsrywefmq.html

C#:   Task.Run(() => F());
来源：http://dali.wangdashe.top/Article/details/gtunajpvsk.html

[O02] 使用线程池
来源：http://dali.quarkkingdee.top/Article/details/gtillfubow.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnqzz.top/Article/details/gtojpxekns.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jlsjyb.cn/Article/details/gtqojccbhu.html

JS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gtaiccfewf.html

TS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gtyxchiqhf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhiwuduotai.top/Article/details/gtglfostkj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinqigufen.top/Article/details/gthrqstvvw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jlsjyb.cn/Article/details/gteequzztm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenjidiqi.icu/Article/details/gtsmoegoiv.html

[O03] 加锁保护共享数据
来源：http://dali.shanyushiyangtech.top/Article/details/gthdotonui.html

Py:   with lock: shared += 1
来源：http://dali.daxiang520.top/Article/details/gtfhwnzklx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ppjwa.cn/Article/details/gtwjkuoqud.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.quarkkingdee.top/Article/details/gtopajyane.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gtrpddcufw.html

Java: synchronized (this) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gtqurrckjc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dashuyun.cn/Article/details/gtxhzkopdk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrceyfcr.html

C#:   lock (gate) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gtwoctvnzw.html

[O04] 定义异步函数并等待
来源：http://dali.wangdashe.top/Article/details/gttvpiaivg.html

Py:   async def f():⏎    await g()
来源：http://dali.ehwqpu.com/Article/details/gtjbrskvxm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xziqi.cn/Article/details/gtfiqvqizq.html

JS:   async function f() { await g(); }
来源：http://dali.smart0.xyz/Article/details/gtssmuqvjd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtjycvpnqt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258.top/Article/details/gtmbyadovy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenjidiqi.icu/Article/details/gtwsrcvgtt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.havefunace.top/Article/details/gtsxdxiywu.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgfzy.top/Article/details/gtytzspqak.html

[O05] 并发执行并等待全部完成
来源：http://dali.mhx1999.top/Article/details/gtaunmbwzy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.guowangkeji.top/Article/details/gtdpbxmqwo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.316326.xyz/Article/details/gtfrubimdr.html

JS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtodjvphhn.html

TS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gtaiuivelm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinghuilouyu.cn/Article/details/gtixyjzbux.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gthfvkhjqv.html

Ruby: threads.map(&:join)
来源：http://dali.aizwys.cn/Article/details/gthraijgtt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.daxiang520.top/Article/details/gtebrxkbli.html

[O06] 使用进程池
来源：http://dali.xuetiantiany.cn/Article/details/gtzxwwjgri.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yvedp.cn/Article/details/gtfqkqczzk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nanxinkj.top/Article/details/gtdbktaazv.html

JS:   // child_process / cluster 模块
来源：http://dali.chenzaomai.com/Article/details/gtzwxridvs.html

TS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gtcewbtlfb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shuidangran.top/Article/details/gtofrmvvri.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sufxvd.cn/Article/details/gtuhwpfhhl.html

Ruby: // fork 块
来源：http://dali.yongpay.top/Article/details/gtrkimtfnp.html

C#:   Parallel.For
来源：http://dali.yj202588.top/Article/details/gttjywibsh.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtllzqiepw.html

P. 常用工具函数
来源：http://dali.fengsongda.top/Article/details/gtisacixee.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtihkreckz.html

[P01] 生成 UUID
来源：http://dali.zhengqikj.top/Article/details/gthpnpljop.html

Py:   str(uuid.uuid4())
来源：http://dali.0kj1m.cn/Article/details/gtwrdjyrqg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yangfankeji.com/Article/details/gtkoqhawif.html

JS:   crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gtjgrfsjbo.html

TS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gtxxesezqq.html

Java: UUID.randomUUID().toString()
来源：http://dali.yangfankeji.com/Article/details/gtpwhzjbme.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj202588.top/Article/details/gtgcqxappo.html

Ruby: SecureRandom.uuid
来源：http://dali.yangfankeji.com/Article/details/gtmvwqiyfi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xziqi.cn/Article/details/gtrlxkkljc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tianlin.xyz/Article/details/gtvzxvlenb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jianghu66.top/Article/details/gtkmvvyvky.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hfpthk.cn/Article/details/gtgwtkkpha.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sysykeji.top/Article/details/gtvitgkukq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cucudq.cn/Article/details/gtbqmbsuqz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sweek.top/Article/details/gtlbcikqhm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.birdmap.top/Article/details/gtkgeblrjt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zycfv.cn/Article/details/gtwymyamhs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.bjfxy.top/Article/details/gtvzweejyc.html

[P03] 生成短随机字符串
来源：http://dali.tianlin.xyz/Article/details/gthvsskyks.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gotoacloud.top/Article/details/gtmzidndph.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj202588.top/Article/details/gtgzyzhweu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.snrcjt.cn/Article/details/gtoabiuaoo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gtefmoctsc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ivvv.top/Article/details/gthpoqsdpo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zycfv.cn/Article/details/gtrrbonukh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.guowangkeji.top/Article/details/gtzmxrdjwg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopqxlwho.html

[P04] 求长度
来源：http://dali.ppjwa.cn/Article/details/gtbluyntru.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.bjfxy.top/Article/details/gtlskendzl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtigzrzafg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dashuyun.cn/Article/details/gtxeaxnkgu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gtlznumuyb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.meibo888.top/Article/details/gtrfcyotkv.html

Go:   len(arr);  len(m)
来源：http://dali.meibo888.top/Article/details/gtlxixekbl.html

Ruby: x.length;  x.size
来源：http://dali.iojbl.cn/Article/details/gtxinrjqvp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sxryk.cn/Article/details/gtucbtprcm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jqgufenzy.top/Article/details/gtkppcnwix.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zycfv.cn/Article/details/gtwnbkodse.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aizwys.cn/Article/details/gtjjmlshgo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fzhhl.top/Article/details/gtmanxzyxq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shuidangran.top/Article/details/gtuhtlzkob.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.vqdsnc.cn/Article/details/gtjhukylxt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gtleefdqxf.html

Ruby: a == b
来源：http://dali.guannengcc.top/Article/details/gtvcrgmfqi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sysykeji.top/Article/details/gtygqghudr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shangyingyoupin.top/Article/details/gtubiqusat.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.vqdsnc.cn/Article/details/gtunoxoagz.html

PHP:  if (empty($x)) {}
来源：http://dali.gotoacloud.top/Article/details/gtpsxqchds.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jlsjyb.cn/Article/details/gtzfbhcmmj.html

TS:   if (x == null) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtkjgexagj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gtrulmxkkt.html

Go:   if x == nil {}
来源：http://dali.shzxlz.cn/Article/details/gtkexbqbkn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258888.top/Article/details/gtgrnzbhbp.html

C#:   if (x is null) {}
来源：http://dali.smart0.xyz/Article/details/gtwgebfiaq.html

[P07] 防抖与节流
来源：http://dali.tianlin.xyz/Article/details/gtlyitakyq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenzaomai.com/Article/details/gtjrhkaggg.html

PHP:  // 手写时间戳比较
来源：http://dali.yongpay.top/Article/details/gtrwaoarem.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gtrktqhwxo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yvedp.cn/Article/details/gtxpqqpbtv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tian-w.cn/Article/details/gtiwilvnbc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.9152youxi.cn/Article/details/gtyxvatuei.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gogol.net.cn/Article/details/gtirjnivrf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ppjwa.cn/Article/details/gtpkbjnkiq.html

[P08] 处理浮点精度问题
来源：http://dali.guowangkeji.top/Article/details/gtzwvcgemt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fengsongda.top/Article/details/gtsjjbeugj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ppjwa.cn/Article/details/gtdroowghg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tianlin.xyz/Article/details/gtodlrjoqv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.svipenyu.cn/Article/details/gtoixortxd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.pengpengdd.cyou/Article/details/gtipcyupzd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tian-w.cn/Article/details/gtsduphdhf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cqqwz.cn/Article/details/gtrldhmhwa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cashguo.top/Article/details/gtmlnwyzfu.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtsnbeiyix.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hammf.cn/Article/details/gtnhxndgro.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtzgbplcxm.html

[Q01] 创建表
来源：http://dali.c1oappe.top/Article/details/gtximdozve.html

CREATE TABLE users (
来源：http://dali.jianghu66.top/Article/details/gtwxeufbpe.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gtobsfstdk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gtntzekvxh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhixingplan.top/Article/details/gtmghpjsul.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hongshengwenyu.top/Article/details/gtcowczihv.html

);
来源：http://dali.c1oappe.top/Article/details/gtrcyscvoe.html

[Q02] 创建带外键的表
来源：http://dali.jlsjyb.cn/Article/details/gtqltjacxa.html

CREATE TABLE orders (
来源：http://dali.chenzaomai.com/Article/details/gtcolxxzdo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangdashe.top/Article/details/gtjdicuyze.html

user_id INT NOT NULL,
来源：http://dali.pycfn.com/Article/details/gtnmnpauon.html

amount DECIMAL(10, 2),
来源：http://dali.smart0.xyz/Article/details/gtzwbrnaez.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xinyue.icu/Article/details/gtllvwxlff.html

);
来源：http://dali.smart0.xyz/Article/details/gtdnriwlde.html

[Q03] 增加列
来源：http://dali.zhengqikj.top/Article/details/gtwbezzway.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.bjfxy.top/Article/details/gtvjbsegqu.html

[Q04] 修改列类型
来源：http://dali.hongshengwenyu.top/Article/details/gtlidxqagy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.quarkkingdee.top/Article/details/gtwpgfikfw.html

[Q05] 重命名列
来源：http://dali.bjfxy.top/Article/details/gtvorgjfgx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yonumen.top/Article/details/gtzkpcftjj.html

[Q06] 删除列
来源：http://dali.nwbrower.top/Article/details/gtivethepd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.vqdsnc.cn/Article/details/gtvwykqzzu.html

[Q07] 删除表
来源：http://dali.hysaishi.cn/Article/details/gtnvmdugfb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.bjfxy.top/Article/details/gtuxcwocpa.html

[Q08] 创建普通索引
来源：http://dali.guowangkeji.top/Article/details/gtgxlfooig.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ppjwa.cn/Article/details/gtmiywhnhz.html

[Q09] 创建唯一索引
来源：http://dali.xinyue.icu/Article/details/gtmkwfyran.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yvedp.cn/Article/details/gtfzmojpkr.html

[Q10] 插入单行
来源：http://dali.hongshengwenyu.top/Article/details/gtzjqueqod.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.snrcjt.cn/Article/details/gtnblrpgjb.html

[Q11] 一次插入多行
来源：http://dali.chenlongwang.top/Article/details/gtumvnzzpg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cqqwz.cn/Article/details/gtsqnpouwl.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gtkibswuuw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sysykeji.top/Article/details/gtmdxvpjhk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jqgufenzy.top/Article/details/gtpgtqoxuo.html

[Q13] 忽略重复插入
来源：http://dali.sufxvd.cn/Article/details/gtoasndmqb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifndrkha.html

[Q14] 存在则更新（upsert）
来源：http://dali.kuanghao11.cn/Article/details/gtbxcrewrt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.c1oappe.top/Article/details/gtuhcrcnef.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hysaishi.cn/Article/details/gtjoalivli.html

[Q15] 查询全部
来源：http://dali.zhiwuduotai.top/Article/details/gtardpvkyk.html

SELECT * FROM users;
来源：http://dali.316326.xyz/Article/details/gtognxqury.html

[Q16] 查询指定列
来源：http://dali.hnxiangtu.top/Article/details/gtzycnaycl.html

SELECT id, name FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtrumqfmgz.html

[Q17] 条件查询
来源：http://dali.ppjwa.cn/Article/details/gtnpvjjrbh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cqqwz.cn/Article/details/gtyrldeiec.html

[Q18] 模糊匹配
来源：http://dali.ybcxt.top/Article/details/gtmwuxtcuu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gotoacloud.top/Article/details/gtglhkmktu.html

[Q19] 范围查询
来源：http://dali.tian-w.cn/Article/details/gteohkxtph.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jiagoushi.top/Article/details/gthqznjilt.html

[Q20] IN 列表
来源：http://dali.yj202588.top/Article/details/gtlcpfrdim.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xziqi.cn/Article/details/gtzdaepzoq.html

[Q21] 空值判断
来源：http://dali.bjfxy.top/Article/details/gtpxnbqrko.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gtcngckqdb.html

[Q22] 排序
来源：http://dali.yonumen.top/Article/details/gthdksbxmv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gzhubu.top/Article/details/gtmxffzskh.html

[Q23] 分页
来源：http://dali.sysykeji.top/Article/details/gtfrngovgq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zdqjudy.top/Article/details/gtcfwrjonm.html

[Q24] 去重
来源：http://dali.snrcjt.cn/Article/details/gtcksezqzh.html

SELECT DISTINCT city FROM users;
来源：http://dali.tian-w.cn/Article/details/gtpatdyavk.html

[Q25] 只取前 N 条
来源：http://dali.hnqzz.top/Article/details/gthvcsqjwi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dashuyun.cn/Article/details/gtofryzdhg.html

[Q26] 计数
来源：http://dali.gotoacloud.top/Article/details/gtwyqjlxns.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtjgvdswkh.html

[Q27] 条件计数
来源：http://dali.hfpthk.cn/Article/details/gtbdwztbge.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprprkkyq.html

[Q28] 求和与平均
来源：http://dali.wangshuangyany.cn/Article/details/gthzkepyjn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtdrrgfcxa.html

[Q29] 最大最小值
来源：http://dali.ydzc1.top/Article/details/gtmvqqghgg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtyrpghoro.html

[Q30] 分组统计
来源：http://dali.xinyue.icu/Article/details/gtdtvheark.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gtioqlpkll.html

[Q31] 分组后过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gttujojhvr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cheryme.top/Article/details/gtjqnrqzxt.html

[Q32] 分组拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtksbxixfa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtloxmklrq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhengqikj.top/Article/details/gtfuallcwr.html

[Q33] 多列分组
来源：http://dali.jqgfzy.top/Article/details/gtobgzkphs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tianlin.xyz/Article/details/gtqixabccy.html

[Q34] 每组取第一条
来源：http://dali.zhengqikj.top/Article/details/gtmiyzkhak.html

SELECT * FROM (
来源：http://dali.cucudq.cn/Article/details/gtiwvmxpls.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.meibo888.top/Article/details/gtfjsxhzkc.html

) t WHERE rn = 1;
来源：http://dali.316326.xyz/Article/details/gthbirpfna.html

[Q35] 内连接
来源：http://dali.zhoulong.xyz/Article/details/gtdykkehmh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzttbsqy.html

[Q36] 左连接
来源：http://dali.daria6918.cn/Article/details/gtctnfhoya.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gtrggrjwld.html

[Q37] 右连接
来源：http://dali.ybcxt.top/Article/details/gtbzzzixpt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnxiangtu.top/Article/details/gtrjlotqqn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cucudq.cn/Article/details/gtzhegtvmq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.kuanghao11.cn/Article/details/gtyzhaivfk.html

[Q39] 自连接（查上下级）
来源：http://dali.gzhubu.top/Article/details/gtjxzukiqa.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenzaomai.com/Article/details/gtgrcxnohy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tianlin.xyz/Article/details/gtoyptlmfl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yangfankeji.com/Article/details/gtrsjiqkzj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.kuanghao11.cn/Article/details/gtpylzwadb.html

[Q41] 多表连接
来源：http://dali.chenzaomai.com/Article/details/gtbgjimlzr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jqgfzy.top/Article/details/gtapvbwlzm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yvedp.cn/Article/details/gtuijmtcda.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hnxiangtu.top/Article/details/gtrucyojwq.html

[Q42] 连接条件附加过滤
来源：http://dali.havefunace.top/Article/details/gtfpqupyhz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.havefunace.top/Article/details/gthckshsrs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnxiangtu.top/Article/details/gtesaytbrs.html

[Q43] 标量子查询
来源：http://dali.gogol.net.cn/Article/details/gturkekwxw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhoulong.xyz/Article/details/gtqnljwnba.html

[Q44] IN 子查询
来源：http://dali.ybcxt.top/Article/details/gtreefmuyi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcenpnaw.html

[Q45] EXISTS 判断存在
来源：http://dali.chenzaomai.com/Article/details/gtctfglftv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guowangkeji.top/Article/details/gtaksxnxnc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258.top/Article/details/gtovpnekfj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gtcicdsevm.html

[Q47] 与平均值比较
来源：http://dali.wangshuangyany.cn/Article/details/gtzakyvloe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hongshengwenyu.top/Article/details/gtdvubccsb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhoulong.xyz/Article/details/gtgqbsxdvx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shzxlz.cn/Article/details/gtrjnsscxa.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcuvdaool.html

[Q49] 更新单行
来源：http://dali.yuxming.cn/Article/details/gtbormlpze.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hysaishi.cn/Article/details/gtucwhvtoj.html

[Q50] 批量更新
来源：http://dali.zhengqikj.top/Article/details/gtybccmjcg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.mhx1999.top/Article/details/gtxawmqzdx.html

[Q51] 用子查询更新
来源：http://dali.guannengcc.top/Article/details/gtboavceee.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ehwqpu.com/Article/details/gtynunhvrg.html

[Q52] 删除指定行
来源：http://dali.yuanzhike.top/Article/details/gtbylaxdrz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hammf.cn/Article/details/gtapbceozi.html

[Q53] 按条件删除
来源：http://dali.guannengcc.top/Article/details/gtaydmobms.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.fzhhl.top/Article/details/gtbzsauxvm.html

[Q54] 清空表
来源：http://dali.wangdashe.top/Article/details/gtwwedjxji.html

TRUNCATE TABLE logs;
来源：http://dali.smart0.xyz/Article/details/gtaqkkmfun.html

[Q55] 排名（并列占位）
来源：http://dali.hfpthk.cn/Article/details/gtxitzkorp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gtwgdkkoeh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hongshengwenyu.top/Article/details/gtoyvcyuqd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shangyingyoupin.top/Article/details/gtruzajpvg.html

[Q57] 行号
来源：http://dali.ivvv.top/Article/details/gtwsimuqyy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.andypj.xyz/Article/details/gtvjuvoeof.html

[Q58] 累计求和
来源：http://dali.xziqi.cn/Article/details/gtymswvcii.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtfvxxmsgr.html

[Q59] 分组内累计
来源：http://dali.jianghu66.top/Article/details/gtcevfonnb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtooikdicr.html

[Q60] 取上一行 / 下一行
来源：http://dali.guowangkeji.top/Article/details/gtcmkwzyrp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj20258.top/Article/details/gtexumqxwa.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtybqgsifv.html


<!-- 参考信息 -->