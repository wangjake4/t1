代发 wailian999

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yvedp.cn/Article/details/gt2rrpgeins.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zycfv.cn/Article/details/gt2xtbrvrrb.html

Java: class Node { int v; Node next; }
来源：http://dali.ybcxt.top/Article/details/gt2lvhqpyhs.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.svipenyu.cn/Article/details/gt2wjnwypjw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aibaodan.cn/Article/details/gt2gpoovrbh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.c1oappe.top/Article/details/gt2rlqukaxm.html

[N11] 二叉树中序遍历
来源：http://dali.9152youxi.cn/Article/details/gt2guawxvaa.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cheryme.top/Article/details/gt2rwpkuckk.html

PHP:  // 手写递归函数
来源：http://dali.yangfankeji.com/Article/details/gt2pqizkkms.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.smart0.xyz/Article/details/gt2mgqeznnf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj202588.top/Article/details/gt2bnsflqon.html

Java: // 手写递归
来源：http://dali.tian-w.cn/Article/details/gt2sjbvqayh.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bksdqwct.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.mhx1999.top/Article/details/gt2mmbcrieh.html

C#:   // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aayhxzra.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shuidangran.top/Article/details/gt2zceildhw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shuidangran.top/Article/details/gt2rbfiwriy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2akijveik.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gt2sqngvmor.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hysaishi.cn/Article/details/gt2njtfgfmq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gt2fppwwdex.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.quarkkingdee.top/Article/details/gt2pwjxbkge.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258888.top/Article/details/gt2qitorrbm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gt2nnivdzib.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2ktgysswq.html

O. 并发与异步
来源：http://dali.yangfankeji.com/Article/details/gt2xkdcmjme.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2uezjwxvb.html

[O01] 启动一个线程
来源：http://dali.316326.xyz/Article/details/gt2mczcwnko.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shangyingyoupin.top/Article/details/gt2gnmkbrvq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jianghu66.top/Article/details/gt2xulhpmns.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wpklmglm.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gt2cbypdqnr.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhiwuduotai.top/Article/details/gt2qkphcxmx.html

Go:   go f()
来源：http://dali.shangyingyoupin.top/Article/details/gt2zudyolpj.html

Ruby: Thread.new { f }
来源：http://dali.aizwys.cn/Article/details/gt2kdaspnts.html

C#:   Task.Run(() => F());
来源：http://dali.zhiwuduotai.top/Article/details/gt2pptvwmhb.html

[O02] 使用线程池
来源：http://dali.wangshuangyany.cn/Article/details/gt2yolpbxja.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gt2oaygwqnx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ppjwa.cn/Article/details/gt2hrohoonj.html

JS:   // worker_threads 线程池
来源：http://dali.pycfn.com/Article/details/gt2xtbhiuft.html

TS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gt2ecyxutek.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sysykeji.top/Article/details/gt2wwwuledl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangdashe.top/Article/details/gt2soyidthw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qnnlvwbe.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.9152youxi.cn/Article/details/gt2hbjcdwpx.html

[O03] 加锁保护共享数据
来源：http://dali.ehwqpu.com/Article/details/gt2nlkslhhp.html

Py:   with lock: shared += 1
来源：http://dali.wangdashe.top/Article/details/gt2ynpfjjes.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pengpengdd.cyou/Article/details/gt2rupqicrt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sweek.top/Article/details/gt2bglisowy.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gt2mmotkqig.html

Java: synchronized (this) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gt2fbwzynia.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yueranfly.top/Article/details/gt2hicyektq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xoneeove.html

C#:   lock (gate) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gt2zgsdzdrx.html

[O04] 定义异步函数并等待
来源：http://dali.aibaodan.cn/Article/details/gt2slckccjp.html

Py:   async def f():⏎    await g()
来源：http://dali.wangdashe.top/Article/details/gt2lvshrcpo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhengqikj.top/Article/details/gt2vwnbprve.html

JS:   async function f() { await g(); }
来源：http://dali.yj202588.top/Article/details/gt2prheqhzx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jyoumei.cn/Article/details/gt2vdrvdwjc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangshuangyany.cn/Article/details/gt2qjrfelwq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shangyingyoupin.top/Article/details/gt2jpzoxhpt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.c1oappe.top/Article/details/gt2dhndqhtx.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2ftpnmefb.html

[O05] 并发执行并等待全部完成
来源：http://dali.daria6918.cn/Article/details/gt2dljopjag.html

Py:   asyncio.gather(*tasks)
来源：http://dali.meibo888.top/Article/details/gt2bhodthvr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxinkj.top/Article/details/gt2hrxnmtmc.html

JS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gt2niaxhlql.html

TS:   await Promise.all(tasks)
来源：http://dali.gogol.net.cn/Article/details/gt2hrcksawh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.birdmap.top/Article/details/gt2kungyjig.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cashguo.top/Article/details/gt2twezjjrq.html

Ruby: threads.map(&:join)
来源：http://dali.daxiang520.top/Article/details/gt2zslrqemz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cheryme.top/Article/details/gt2xvwcdnqb.html

[O06] 使用进程池
来源：http://dali.ybcxt.top/Article/details/gt2uavwgswv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hnqzz.top/Article/details/gt2fpgisfef.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.0kj1m.cn/Article/details/gt2ifuhzvii.html

JS:   // child_process / cluster 模块
来源：http://dali.yonumen.top/Article/details/gt2apvwmixi.html

TS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gt2gunqgkjq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258888.top/Article/details/gt2iqsbtygk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ehwqpu.com/Article/details/gt2iavbhhys.html

Ruby: // fork 块
来源：http://dali.hnxiangtu.top/Article/details/gt2emhcqfci.html

C#:   Parallel.For
来源：http://dali.wangdashe.top/Article/details/gt2mnfhnsoa.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2oetaisce.html

P. 常用工具函数
来源：http://dali.xuanzx.com/Article/details/gt2gniyrdvf.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2djikbnug.html

[P01] 生成 UUID
来源：http://dali.jlsjyb.cn/Article/details/gt2bcauljsu.html

Py:   str(uuid.uuid4())
来源：http://dali.ehwqpu.com/Article/details/gt2mlfqpmjm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhongyouzk.top/Article/details/gt2pctdbusu.html

JS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gt2rnssbyeh.html

TS:   crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gt2swenpvdt.html

Java: UUID.randomUUID().toString()
来源：http://dali.c1oappe.top/Article/details/gt2squjptbh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hammf.cn/Article/details/gt2gijfjzrt.html

Ruby: SecureRandom.uuid
来源：http://dali.chenzaomai.com/Article/details/gt2ztpekzrp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.c1oappe.top/Article/details/gt2jwrrjnoc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shuidangran.top/Article/details/gt2lsvjbugi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.fzhhl.top/Article/details/gt2dlhmuywp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yonumen.top/Article/details/gt2ptfjsrpp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jyoumei.cn/Article/details/gt2ofwewmvo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tian-w.cn/Article/details/gt2cmiqptgn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sufxvd.cn/Article/details/gt2gcvnxcdv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.smart0.xyz/Article/details/gt2kjxaqqkj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zycfv.cn/Article/details/gt2lwrzhdwu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2camqqlme.html

[P03] 生成短随机字符串
来源：http://dali.tianlin.xyz/Article/details/gt2gbwklgke.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shangyingyoupin.top/Article/details/gt2lpdzzrxd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.haohaochexian.top/Article/details/gt2tswyedfa.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gt2hdarkhfb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gt2kqgowiyz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wwtpmbzw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.0kj1m.cn/Article/details/gt2qtipzaob.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shuidangran.top/Article/details/gt2tpeaebms.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zdqjudy.top/Article/details/gt2krzjzdzq.html

[P04] 求长度
来源：http://dali.yangfankeji.com/Article/details/gt2ukuyfoms.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuxming.cn/Article/details/gt2vfeczpus.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gt2fjvwfags.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xinyue.icu/Article/details/gt2eghyzgmb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gt2vhjtzlmz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cqqwz.cn/Article/details/gt2xbljpcxb.html

Go:   len(arr);  len(m)
来源：http://dali.meibo888.top/Article/details/gt2zedhnowv.html

Ruby: x.length;  x.size
来源：http://dali.shuidangran.top/Article/details/gt2rirrbwdf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ivvv.top/Article/details/gt2noibpkhh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.snrcjt.cn/Article/details/gt2rjplscii.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pengpengdd.cyou/Article/details/gt2fxtcvwvj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.kuanghao11.cn/Article/details/gt2owzlfexn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yangfankeji.com/Article/details/gt2bbikcrta.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2migyfuit.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gzhubu.top/Article/details/gt2ojojnjym.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.guowangkeji.top/Article/details/gt2kqmqizgj.html

Ruby: a == b
来源：http://dali.dashuyun.cn/Article/details/gt2wcxmpzaw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenzaomai.com/Article/details/gt2lfkugcsj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hongshengwenyu.top/Article/details/gt2bdtgzvor.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.quarkkingdee.top/Article/details/gt2oemdxicc.html

PHP:  if (empty($x)) {}
来源：http://dali.fzhhl.top/Article/details/gt2akerckab.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.vqdsnc.cn/Article/details/gt2uqldwmbv.html

TS:   if (x == null) {}
来源：http://dali.jqgfzy.top/Article/details/gt2xhlqilly.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yonumen.top/Article/details/gt2gjrnycpr.html

Go:   if x == nil {}
来源：http://dali.redwolf501.top/Article/details/gt2ocpaeqgh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gotoacloud.top/Article/details/gt2vehxbecs.html

C#:   if (x is null) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2lyktovcw.html

[P07] 防抖与节流
来源：http://dali.0kj1m.cn/Article/details/gt2cjnmkhhh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yongpay.top/Article/details/gt2rigluvqt.html

PHP:  // 手写时间戳比较
来源：http://dali.haohaochexian.top/Article/details/gt2hkhtxozc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sbthebyb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gt2xojzfagr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aibaodan.cn/Article/details/gt2qctnymgr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hnqzz.top/Article/details/gt2txswnjhk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.guowangkeji.top/Article/details/gt2blgysmih.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nwbrower.top/Article/details/gt2xygbbqcr.html

[P08] 处理浮点精度问题
来源：http://dali.tianlin.xyz/Article/details/gt2qgmphoxq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenzaomai.com/Article/details/gt2kqtbcpnp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ffaocmac.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pycfn.com/Article/details/gt2upqanwii.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hysaishi.cn/Article/details/gt2qbkhpeyw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhengqikj.top/Article/details/gt2zlsczefo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cashguo.top/Article/details/gt2dvefznen.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sufxvd.cn/Article/details/gt2yvtadalj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2inwgmeci.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2wpzemwmh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhixingplan.top/Article/details/gt2cxyhxwpy.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2qmxnvmlz.html

[Q01] 创建表
来源：http://dali.yuanzhike.top/Article/details/gt2zmigpbmp.html

CREATE TABLE users (
来源：http://dali.cheryme.top/Article/details/gt2yvwurkwh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guannengcc.top/Article/details/gt2balzfotk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ehwqpu.com/Article/details/gt2gtwynhdb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nwbrower.top/Article/details/gt2tinstyqt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tian-w.cn/Article/details/gt2vjqkywct.html

);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fznbzfsf.html

[Q02] 创建带外键的表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yofeewru.html

CREATE TABLE orders (
来源：http://dali.redwolf501.top/Article/details/gt2mhykwfpe.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gt2dldrokhv.html

user_id INT NOT NULL,
来源：http://dali.yangfankeji.com/Article/details/gt2fasejidy.html

amount DECIMAL(10, 2),
来源：http://dali.gaohongyu789.top/Article/details/gt2ydyliguj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ppjwa.cn/Article/details/gt2ikoojnnv.html

);
来源：http://dali.c1oappe.top/Article/details/gt2xfulblxb.html

[Q03] 增加列
来源：http://dali.fengsongda.top/Article/details/gt2qhoemiyj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxuanxn.top/Article/details/gt2zuwikjjt.html

[Q04] 修改列类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2wmtmdjjm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.bjfxy.top/Article/details/gt2fazildqp.html

[Q05] 重命名列
来源：http://dali.hongshengwenyu.top/Article/details/gt2nfjrneir.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nanxuanxn.top/Article/details/gt2aecuqzfv.html

[Q06] 删除列
来源：http://dali.gogol.net.cn/Article/details/gt2mgehkhus.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zycfv.cn/Article/details/gt2mnmupaov.html

[Q07] 删除表
来源：http://dali.snrcjt.cn/Article/details/gt2cjwhcuwt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sysykeji.top/Article/details/gt2wkaeieta.html

[Q08] 创建普通索引
来源：http://dali.cheryme.top/Article/details/gt2lkoofcrm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tian-w.cn/Article/details/gt2qbktzvzv.html

[Q09] 创建唯一索引
来源：http://dali.haohaochexian.top/Article/details/gt2hecbitsa.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gt2oejpayaj.html

[Q10] 插入单行
来源：http://dali.bjfxy.top/Article/details/gt2iiypioab.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.fzhhl.top/Article/details/gt2jiphivtm.html

[Q11] 一次插入多行
来源：http://dali.zhongyouzk.top/Article/details/gt2dqbahhbz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.316326.xyz/Article/details/gt2ynvbtdeu.html

[Q12] 插入后取自增 ID
来源：http://dali.sweek.top/Article/details/gt2bpwhqmxi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jlsjyb.cn/Article/details/gt2vvhulefy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ppjwa.cn/Article/details/gt2zkkxudte.html

[Q13] 忽略重复插入
来源：http://dali.havefunace.top/Article/details/gt2hxbgyecy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cucudq.cn/Article/details/gt2taxcojor.html

[Q14] 存在则更新（upsert）
来源：http://dali.jlsjyb.cn/Article/details/gt2seorqgbh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.daria6918.cn/Article/details/gt2nioudovt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tanke756.top/Article/details/gt2irkduvnu.html

[Q15] 查询全部
来源：http://dali.yj20258.top/Article/details/gt2oyxnraib.html

SELECT * FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2ifkzyxlb.html

[Q16] 查询指定列
来源：http://dali.jinqigufen.top/Article/details/gt2sgzqsrfw.html

SELECT id, name FROM users;
来源：http://dali.tanke756.top/Article/details/gt2kgleepwa.html

[Q17] 条件查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2qiwlojzj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2kbszrmbl.html

[Q18] 模糊匹配
来源：http://dali.cheryme.top/Article/details/gt2aoxykbej.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.redwolf501.top/Article/details/gt2zmnzutqi.html

[Q19] 范围查询
来源：http://dali.hywenlv.cn/Article/details/gt2rblejsep.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pengpengdd.cyou/Article/details/gt2qzgzvogh.html

[Q20] IN 列表
来源：http://dali.tian-w.cn/Article/details/gt2aklbmfrh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zycfv.cn/Article/details/gt2znsqpfsf.html

[Q21] 空值判断
来源：http://dali.yangfankeji.com/Article/details/gt2wvobqgpw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinqigufen.top/Article/details/gt2bvsyrmlz.html

[Q22] 排序
来源：http://dali.havefunace.top/Article/details/gt2walnidir.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.vqdsnc.cn/Article/details/gt2jegsswap.html

[Q23] 分页
来源：http://dali.gzhubu.top/Article/details/gt2clvhuosg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nwbrower.top/Article/details/gt2sewgyaob.html

[Q24] 去重
来源：http://dali.zhongyouzk.top/Article/details/gt2xkgjtmdr.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2luywnuaj.html

[Q25] 只取前 N 条
来源：http://dali.xylfe.cn/Article/details/gt2xdkazaza.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fzhhl.top/Article/details/gt2xmihtvxp.html

[Q26] 计数
来源：http://dali.guowangkeji.top/Article/details/gt2kljhoqcp.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2jasjewcd.html

[Q27] 条件计数
来源：http://dali.aizwys.cn/Article/details/gt2tkqhquab.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2hjfzrmdw.html

[Q28] 求和与平均
来源：http://dali.redwolf501.top/Article/details/gt2nonwpxpc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2ouqdaywb.html

[Q29] 最大最小值
来源：http://dali.jinqigfzy.top/Article/details/gt2ykosryfj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2omrurqfo.html

[Q30] 分组统计
来源：http://dali.zhengqikj.top/Article/details/gt2ykdgmyhs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gt2dghdobcb.html

[Q31] 分组后过滤
来源：http://dali.yj20258.top/Article/details/gt2atlrcikt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hongshengwenyu.top/Article/details/gt2lybitkdo.html

[Q32] 分组拼接字符串
来源：http://dali.tian-w.cn/Article/details/gt2ewyzovvs.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gt2ejycsqxc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tianlin.xyz/Article/details/gt2girhxwzi.html

[Q33] 多列分组
来源：http://dali.guannengcc.top/Article/details/gt2swemblai.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hfpthk.cn/Article/details/gt2oaopypez.html

[Q34] 每组取第一条
来源：http://dali.cdnleiting.top/Article/details/gt2yjjlluai.html

SELECT * FROM (
来源：http://dali.xuetiantiany.cn/Article/details/gt2lvzbpwbe.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yanxiufei.cn/Article/details/gt2xrfmqqnk.html

) t WHERE rn = 1;
来源：http://dali.redwolf501.top/Article/details/gt2jwhvgghj.html

[Q35] 内连接
来源：http://dali.guowangkeji.top/Article/details/gt2qoanwcsx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.havefunace.top/Article/details/gt2bifzlyav.html

[Q36] 左连接
来源：http://dali.jyoumei.cn/Article/details/gt2litshwko.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.9152youxi.cn/Article/details/gt2lcidypsu.html

[Q37] 右连接
来源：http://dali.yongpay.top/Article/details/gt2lcjcqhiq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhengqikj.top/Article/details/gt2kmaxiujq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xziqi.cn/Article/details/gt2vrirctrk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daria6918.cn/Article/details/gt2owshmgbz.html

[Q39] 自连接（查上下级）
来源：http://dali.fzhhl.top/Article/details/gt2dvnlbmtq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.aizwys.cn/Article/details/gt2acgkavhk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ybcxt.top/Article/details/gt2immycrrb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangshuangyany.cn/Article/details/gt2agvlqykv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.mhx1999.top/Article/details/gt2yprugrem.html

[Q41] 多表连接
来源：http://dali.shuidangran.top/Article/details/gt2yhgxgwja.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daxiang520.top/Article/details/gt2fhwutodx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.redwolf501.top/Article/details/gt2eexbgjtu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gzhubu.top/Article/details/gt2uhzgbrjj.html

[Q42] 连接条件附加过滤
来源：http://dali.guowangkeji.top/Article/details/gt2hvgxaojf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuanzx.com/Article/details/gt2pznxmjah.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.c1oappe.top/Article/details/gt2vorqqphb.html

[Q43] 标量子查询
来源：http://dali.9152youxi.cn/Article/details/gt2lozhbszx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yanxiufei.cn/Article/details/gt2lyxlkrse.html

[Q44] IN 子查询
来源：http://dali.jianghu66.top/Article/details/gt2xivgkehv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sysykeji.top/Article/details/gt2rryeepih.html

[Q45] EXISTS 判断存在
来源：http://dali.daria6918.cn/Article/details/gt2ioworrov.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgufenzy.top/Article/details/gt2vobdhdfs.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.haohaochexian.top/Article/details/gt2goioeviq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gt2nlloqeis.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uplcmxew.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yanxiufei.cn/Article/details/gt2lyucdoao.html

[Q48] CTE 公用表表达式
来源：http://dali.zdqjudy.top/Article/details/gt2yykocfty.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nwbrower.top/Article/details/gt2udvgizlx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jiagoushi.top/Article/details/gt2weatyjlf.html

[Q49] 更新单行
来源：http://dali.ivvv.top/Article/details/gt2gomobism.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gt2mmitisst.html

[Q50] 批量更新
来源：http://dali.svipenyu.cn/Article/details/gt2wzgtazcl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shuidangran.top/Article/details/gt2yflvdocx.html

[Q51] 用子查询更新
来源：http://dali.andypj.xyz/Article/details/gt2bchefyad.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.birdmap.top/Article/details/gt2lwxmhzpq.html

[Q52] 删除指定行
来源：http://dali.kuanghao11.cn/Article/details/gt2ddhhjrrj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nwbrower.top/Article/details/gt2uoubetsa.html

[Q53] 按条件删除
来源：http://dali.tanke756.top/Article/details/gt2xlezafqw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gt2ufewfjyp.html

[Q54] 清空表
来源：http://dali.nanxinkj.top/Article/details/gt2tumitocg.html

TRUNCATE TABLE logs;
来源：http://dali.nwbrower.top/Article/details/gt2lklhwxfc.html

[Q55] 排名（并列占位）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2czkyritg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gt2loiubacn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zycfv.cn/Article/details/gt2yannrucl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.316326.xyz/Article/details/gt2mhlxnzmv.html

[Q57] 行号
来源：http://dali.andypj.xyz/Article/details/gt2hmvbehsv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2bwabumxk.html

[Q58] 累计求和
来源：http://dali.ehwqpu.com/Article/details/gt2vwangvek.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kugaiibd.html

[Q59] 分组内累计
来源：http://dali.hywenlv.cn/Article/details/gt2vzjkfpnf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gt2xmkmzebr.html

[Q60] 取上一行 / 下一行
来源：http://dali.yongpay.top/Article/details/gt2oqwmulii.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cheryme.top/Article/details/gt2scggjwlm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2ojccyfbb.html


<!-- 参考信息 -->