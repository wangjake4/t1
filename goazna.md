代发 wailian999

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gzhubu.top/Article/details/gt2hatwndig.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.316326.xyz/Article/details/gt2frgydbiu.html

Java: class Node { int v; Node next; }
来源：http://dali.9152youxi.cn/Article/details/gt2xylmawen.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sxryk.cn/Article/details/gt2bghovcrf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.haohaochexian.top/Article/details/gt2gscdvplq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.birdmap.top/Article/details/gt2jnbrfhyp.html

[N11] 二叉树中序遍历
来源：http://dali.sxryk.cn/Article/details/gt2bhustgfq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yuxming.cn/Article/details/gt2avypmtyg.html

PHP:  // 手写递归函数
来源：http://dali.xylfe.cn/Article/details/gt2icaiktwz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gt2xprwmkxc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gt2uneemkdj.html

Java: // 手写递归
来源：http://dali.yvedp.cn/Article/details/gt2acrzxrpu.html

Go:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gt2krxptsvr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xylfe.cn/Article/details/gt2wacfuvca.html

C#:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gt2ucelqytm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.haohaochexian.top/Article/details/gt2yphdmucc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ydzc1.top/Article/details/gt2hnqkhjmc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.guowangkeji.top/Article/details/gt2qvncgjng.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gt2dopqfikb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hysaishi.cn/Article/details/gt2tqqdbxnd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gt2urcrwjny.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nwbrower.top/Article/details/gt2skiwwdvb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.smart0.xyz/Article/details/gt2xlaqmwgu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gt2tskrolfa.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2fljdztdd.html

O. 并发与异步
来源：http://dali.snrcjt.cn/Article/details/gt2ahfsuuxt.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2rynxdoly.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gt2beadrkab.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zycfv.cn/Article/details/gt2spdtofsf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gaohongyu789.top/Article/details/gt2aczepdmc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gzhubu.top/Article/details/gt2huljdmld.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gt2zvvezaqx.html

Java: new Thread(() -> f()).start()
来源：http://dali.316326.xyz/Article/details/gt2fzkjaekv.html

Go:   go f()
来源：http://dali.guowangkeji.top/Article/details/gt2tcfiiqqa.html

Ruby: Thread.new { f }
来源：http://dali.haohaochexian.top/Article/details/gt2rmklwush.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigufen.top/Article/details/gt2nejjatae.html

[O02] 使用线程池
来源：http://dali.aibaodan.cn/Article/details/gt2euijzlbd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.redwolf501.top/Article/details/gt2qvtgztva.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cjxltzuv.html

JS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gt2xdzrvqwx.html

TS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gt2olilvlhw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cashguo.top/Article/details/gt2tepfobfz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.feifeiyinyue.top/Article/details/gt2wentznpl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hysaishi.cn/Article/details/gt2yaukhboh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258.top/Article/details/gt2snenfaui.html

[O03] 加锁保护共享数据
来源：http://dali.gaohongyu789.top/Article/details/gt2pqcgselz.html

Py:   with lock: shared += 1
来源：http://dali.hywenlv.cn/Article/details/gt2fupekrdr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zdqjudy.top/Article/details/gt2scpfcnyk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zdqjudy.top/Article/details/gt2kkallbzu.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gt2jkphdgxv.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj20258888.top/Article/details/gt2oxlxsuyc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xylfe.cn/Article/details/gt2zikogswa.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2szjylmyn.html

C#:   lock (gate) { shared++; }
来源：http://dali.zycfv.cn/Article/details/gt2mezvibeo.html

[O04] 定义异步函数并等待
来源：http://dali.tianlin.xyz/Article/details/gt2heckkkyt.html

Py:   async def f():⏎    await g()
来源：http://dali.gzhubu.top/Article/details/gt2rvvrmnnv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fwssnxdu.html

JS:   async function f() { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gt2cnjsklpy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gt2wdbdrnoo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.snrcjt.cn/Article/details/gt2zzmpzery.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jiagoushi.top/Article/details/gt2kivblxwz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.aibaodan.cn/Article/details/gt2gylitipm.html

C#:   async Task F() { await G(); }
来源：http://dali.chenzaomai.com/Article/details/gt2qefyseco.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhongyouzk.top/Article/details/gt2lvasjnzp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.fengsongda.top/Article/details/gt2jprpoxei.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.9152youxi.cn/Article/details/gt2quqziptv.html

JS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rlndhvzk.html

TS:   await Promise.all(tasks)
来源：http://dali.meibo888.top/Article/details/gt2sfkcqkwn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xylfe.cn/Article/details/gt2iulhlfbx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.bjfxy.top/Article/details/gt2ahqqvdve.html

Ruby: threads.map(&:join)
来源：http://dali.cheryme.top/Article/details/gt2tlgmfzoz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.316326.xyz/Article/details/gt2pmqwnxor.html

[O06] 使用进程池
来源：http://dali.mhx1999.top/Article/details/gt2shceiudb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gogol.net.cn/Article/details/gt2wuzolznk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jyoumei.cn/Article/details/gt2yldjndbx.html

JS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gt2oiykimtr.html

TS:   // child_process / cluster 模块
来源：http://dali.redwolf501.top/Article/details/gt2fiedclqj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yvedp.cn/Article/details/gt2ukzbhwul.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.aizwys.cn/Article/details/gt2uecmbojw.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxdprtj.html

C#:   Parallel.For
来源：http://dali.ivvv.top/Article/details/gt2agvcbdvr.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2mbxeswcg.html

P. 常用工具函数
来源：http://dali.sweek.top/Article/details/gt2gcnxklwc.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2mpvqpbat.html

[P01] 生成 UUID
来源：http://dali.yuxming.cn/Article/details/gt2gedjnnbq.html

Py:   str(uuid.uuid4())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jhoruduo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhengqikj.top/Article/details/gt2lhlakwvw.html

JS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gt2niqdvsnw.html

TS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gt2brotwlfh.html

Java: UUID.randomUUID().toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2nbyvqerk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ppjwa.cn/Article/details/gt2btgybpuc.html

Ruby: SecureRandom.uuid
来源：http://dali.birdmap.top/Article/details/gt2pauyfzmy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gogol.net.cn/Article/details/gt2gkveqqdc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.kuanghao11.cn/Article/details/gt2nyhbfjpn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.haohaochexian.top/Article/details/gt2qnclosyy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yvedp.cn/Article/details/gt2baiscpez.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jyoumei.cn/Article/details/gt2nbbfiarh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jyoumei.cn/Article/details/gt2wgrcbppc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pycfn.com/Article/details/gt2qyrzgani.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xylfe.cn/Article/details/gt2rmspxbbq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yongpay.top/Article/details/gt2xczizrup.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ivvv.top/Article/details/gt2kbgrabcd.html

[P03] 生成短随机字符串
来源：http://dali.haohaochexian.top/Article/details/gt2fqhwhhbv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2emfkmwvg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnqzz.top/Article/details/gt2apckldmp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnqzz.top/Article/details/gt2dvnlapkd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gzhubu.top/Article/details/gt2oxzjijzx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.fzhhl.top/Article/details/gt2dycnbfdm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hammf.cn/Article/details/gt2huygynzj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sweek.top/Article/details/gt2xkdnnjai.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.andypj.xyz/Article/details/gt2drwyfbwd.html

[P04] 求长度
来源：http://dali.zhoulong.xyz/Article/details/gt2ojllmrhw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nanxinkj.top/Article/details/gt2iokxyoay.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gt2ahnpcprv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gt2xpnxninp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gt2eejphlhr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tanke756.top/Article/details/gt2ggeonksq.html

Go:   len(arr);  len(m)
来源：http://dali.cucudq.cn/Article/details/gt2bumtrcib.html

Ruby: x.length;  x.size
来源：http://dali.pycfn.com/Article/details/gt2tdzuqvqg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuanzhike.top/Article/details/gt2qxdejodj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.pycfn.com/Article/details/gt2ppsoszrx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.aibaodan.cn/Article/details/gt2gdoxabmb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjjyypcs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cashguo.top/Article/details/gt2tqqontqz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sysykeji.top/Article/details/gt2jxziipwz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.daria6918.cn/Article/details/gt2bukvitae.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hnqzz.top/Article/details/gt2qvazeapt.html

Ruby: a == b
来源：http://dali.ydzc1.top/Article/details/gt2whgcqyhx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xinyue.icu/Article/details/gt2smggwewc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangshuangyany.cn/Article/details/gt2ccoqogzm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.redwolf501.top/Article/details/gt2wzavhiwk.html

PHP:  if (empty($x)) {}
来源：http://dali.ybcxt.top/Article/details/gt2gatijfsp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.quarkkingdee.top/Article/details/gt2rpqsefow.html

TS:   if (x == null) {}
来源：http://dali.cheryme.top/Article/details/gt2qnydpbgz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hammf.cn/Article/details/gt2hrxrjmgu.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lhkcfzyp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hysaishi.cn/Article/details/gt2tyfaaunl.html

C#:   if (x is null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dagzcwtv.html

[P07] 防抖与节流
来源：http://dali.cqqwz.cn/Article/details/gt2fvseyzgj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ppjwa.cn/Article/details/gt2xxdbwkpt.html

PHP:  // 手写时间戳比较
来源：http://dali.yongpay.top/Article/details/gt2uvasrija.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2chvcfpeh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gt2eulgpgnn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2dwppolnj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ydzc1.top/Article/details/gt2yflvyrxj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.haohaochexian.top/Article/details/gt2ddmerryy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xylfe.cn/Article/details/gt2uqlvdxcl.html

[P08] 处理浮点精度问题
来源：http://dali.guowangkeji.top/Article/details/gt2gwkjrlbz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tanke756.top/Article/details/gt2raxldsad.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.aibaodan.cn/Article/details/gt2hbvtsguj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nanxinkj.top/Article/details/gt2dlevchqz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xylfe.cn/Article/details/gt2sbsiyeoh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cdnleiting.top/Article/details/gt2vvcqousd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xziqi.cn/Article/details/gt2bclbzddx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.daxiang520.top/Article/details/gt2xasyxpif.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jiagoushi.top/Article/details/gt2ulyowsny.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2xhbgvzut.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rsohibpj.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2qiamreoe.html

[Q01] 创建表
来源：http://dali.chenlongwang.top/Article/details/gt2nzwolnar.html

CREATE TABLE users (
来源：http://dali.hysaishi.cn/Article/details/gt2mimuojxv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gt2rmsnyipi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.andypj.xyz/Article/details/gt2sudjdsqu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hammf.cn/Article/details/gt2efdvsvyn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jonkkjwl.html

);
来源：http://dali.aizwys.cn/Article/details/gt2ydosdecq.html

[Q02] 创建带外键的表
来源：http://dali.shangyingyoupin.top/Article/details/gt2xewxwjbs.html

CREATE TABLE orders (
来源：http://dali.ydzc1.top/Article/details/gt2gnusisyd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gt2zpcayity.html

user_id INT NOT NULL,
来源：http://dali.ybcxt.top/Article/details/gt2hzztulhn.html

amount DECIMAL(10, 2),
来源：http://dali.hammf.cn/Article/details/gt2waslckie.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.316326.xyz/Article/details/gt2sparuljx.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmbvlksz.html

[Q03] 增加列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hyrpvrge.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdohlqei.html

[Q04] 修改列类型
来源：http://dali.zdqjudy.top/Article/details/gt2iufihiyy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pycfn.com/Article/details/gt2hrcpsndd.html

[Q05] 重命名列
来源：http://dali.hysaishi.cn/Article/details/gt2ldlozaoy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zdqjudy.top/Article/details/gt2cossapdz.html

[Q06] 删除列
来源：http://dali.birdmap.top/Article/details/gt2sjpqbkxo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.0kj1m.cn/Article/details/gt2cyycsprg.html

[Q07] 删除表
来源：http://dali.jlsjyb.cn/Article/details/gt2ywcctyys.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shzxlz.cn/Article/details/gt2npmdpvac.html

[Q08] 创建普通索引
来源：http://dali.zhoulong.xyz/Article/details/gt2dfkhfxii.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gt2cegucxqh.html

[Q09] 创建唯一索引
来源：http://dali.mhx1999.top/Article/details/gt2xqdlbqvp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.dianchejie.cn/Article/details/gt2vofplahw.html

[Q10] 插入单行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mhdfdyet.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gt2uromzqhk.html

[Q11] 一次插入多行
来源：http://dali.tian-w.cn/Article/details/gt2ajcwrqdx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yvedp.cn/Article/details/gt2xhgkaklg.html

[Q12] 插入后取自增 ID
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rneauoxd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pycfn.com/Article/details/gt2lijvqdvf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dashuyun.cn/Article/details/gt2vcuwsunh.html

[Q13] 忽略重复插入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xwrpiioz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhengqikj.top/Article/details/gt2uhsldwar.html

[Q14] 存在则更新（upsert）
来源：http://dali.bjfxy.top/Article/details/gt2cryhpxyj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.0kj1m.cn/Article/details/gt2nvncsara.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nanxinkj.top/Article/details/gt2rktzdtyg.html

[Q15] 查询全部
来源：http://dali.0kj1m.cn/Article/details/gt2physkhgp.html

SELECT * FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2xyvjigyf.html

[Q16] 查询指定列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pcabdkly.html

SELECT id, name FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2fjmhaldy.html

[Q17] 条件查询
来源：http://dali.hysaishi.cn/Article/details/gt2zforrnov.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yvedp.cn/Article/details/gt2aqychdgs.html

[Q18] 模糊匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2poaugoes.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hammf.cn/Article/details/gt2qmevujxi.html

[Q19] 范围查询
来源：http://dali.hywenlv.cn/Article/details/gt2qkkwdjxd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuxming.cn/Article/details/gt2lwlpwsfz.html

[Q20] IN 列表
来源：http://dali.shzxlz.cn/Article/details/gt2zjlbfawa.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhixingplan.top/Article/details/gt2cfkuqubb.html

[Q21] 空值判断
来源：http://dali.jinqigfzy.top/Article/details/gt2rjuitido.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gotoacloud.top/Article/details/gt2obswqbrf.html

[Q22] 排序
来源：http://dali.jiagoushi.top/Article/details/gt2xdshvkhg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.9152youxi.cn/Article/details/gt2azfqtbal.html

[Q23] 分页
来源：http://dali.zhixingplan.top/Article/details/gt2lfdfxzxv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.feifeiyinyue.top/Article/details/gt2rbtihhot.html

[Q24] 去重
来源：http://dali.jianghu66.top/Article/details/gt2lsfvosry.html

SELECT DISTINCT city FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2fwdagnjg.html

[Q25] 只取前 N 条
来源：http://dali.andypj.xyz/Article/details/gt2qrvypvqd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sufxvd.cn/Article/details/gt2srjbrdsp.html

[Q26] 计数
来源：http://dali.shzxlz.cn/Article/details/gt2mmhlfnzb.html

SELECT COUNT(*) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2hyayshtx.html

[Q27] 条件计数
来源：http://dali.kuanghao11.cn/Article/details/gt2mxuetgki.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2ybagenkv.html

[Q28] 求和与平均
来源：http://dali.tian-w.cn/Article/details/gt2rnatorks.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2qcowlguw.html

[Q29] 最大最小值
来源：http://dali.andypj.xyz/Article/details/gt2mznbpnpb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2rlzygizl.html

[Q30] 分组统计
来源：http://dali.zhiwuduotai.top/Article/details/gt2fuvjmzid.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kmvkrltu.html

[Q31] 分组后过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ahnljhns.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zycfv.cn/Article/details/gt2yazwclut.html

[Q32] 分组拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rwccysoa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gt2ybivphqe.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shzxlz.cn/Article/details/gt2rwnvqswy.html

[Q33] 多列分组
来源：http://dali.yvedp.cn/Article/details/gt2sjjwyiay.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.quarkkingdee.top/Article/details/gt2mceplrci.html

[Q34] 每组取第一条
来源：http://dali.yangfankeji.com/Article/details/gt2pxofoejv.html

SELECT * FROM (
来源：http://dali.haohaochexian.top/Article/details/gt2erntgjtw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nwbrower.top/Article/details/gt2uiklubxb.html

) t WHERE rn = 1;
来源：http://dali.fengsongda.top/Article/details/gt2pvmwppkk.html

[Q35] 内连接
来源：http://dali.tianlin.xyz/Article/details/gt2uhdpqlrr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gt2stmvvfjf.html

[Q36] 左连接
来源：http://dali.hfpthk.cn/Article/details/gt2rdufwodh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hammf.cn/Article/details/gt2kupabgpw.html

[Q37] 右连接
来源：http://dali.ydzc1.top/Article/details/gt2xuptuemj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shzxlz.cn/Article/details/gt2uaayunfs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.svipenyu.cn/Article/details/gt2jejsoowu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuanzx.com/Article/details/gt2rvwhoduj.html

[Q39] 自连接（查上下级）
来源：http://dali.hongshengwenyu.top/Article/details/gt2iifdodcl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yanxiufei.cn/Article/details/gt2guvqnrbh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cheryme.top/Article/details/gt2xccreeso.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nwbrower.top/Article/details/gt2tiyfrdfs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.pengpengdd.cyou/Article/details/gt2cjeyrhvl.html

[Q41] 多表连接
来源：http://dali.tanke756.top/Article/details/gt2fkmkztht.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.havefunace.top/Article/details/gt2hbliegyi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xylfe.cn/Article/details/gt2jsjopahf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhengqikj.top/Article/details/gt2syhfzuyf.html

[Q42] 连接条件附加过滤
来源：http://dali.shangyingyoupin.top/Article/details/gt2emlglvqu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daria6918.cn/Article/details/gt2mlanruca.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.havefunace.top/Article/details/gt2ilmuwtxl.html

[Q43] 标量子查询
来源：http://dali.zycfv.cn/Article/details/gt2jfakuzqv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.wangdashe.top/Article/details/gt2ygihqchy.html

[Q44] IN 子查询
来源：http://dali.sufxvd.cn/Article/details/gt2wftpvncj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jyoumei.cn/Article/details/gt2pptrtvwd.html

[Q45] EXISTS 判断存在
来源：http://dali.haohaochexian.top/Article/details/gt2lgeoappi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gt2damyavzz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhoulong.xyz/Article/details/gt2qchgbagi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gt2hnxhlhfc.html

[Q47] 与平均值比较
来源：http://dali.hywenlv.cn/Article/details/gt2fkwlsnra.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qrjazhlg.html

[Q48] CTE 公用表表达式
来源：http://dali.jianghu66.top/Article/details/gt2gbreuntk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shangyingyoupin.top/Article/details/gt2otucaveq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.snrcjt.cn/Article/details/gt2wnkpskwi.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2axayehht.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.quarkkingdee.top/Article/details/gt2iyxpenup.html

[Q50] 批量更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gazeysqe.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj202588.top/Article/details/gt2yimqpknj.html

[Q51] 用子查询更新
来源：http://dali.yueranfly.top/Article/details/gt2zfbeemam.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2femgxcix.html

[Q52] 删除指定行
来源：http://dali.wangshuangyany.cn/Article/details/gt2fhsfeolz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.daxiang520.top/Article/details/gt2tcksznqf.html

[Q53] 按条件删除
来源：http://dali.chenjidiqi.icu/Article/details/gt2rvlmxwai.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gt2sbwvgrou.html

[Q54] 清空表
来源：http://dali.guowangkeji.top/Article/details/gt2adohisba.html

TRUNCATE TABLE logs;
来源：http://dali.c1oappe.top/Article/details/gt2gypyqtap.html

[Q55] 排名（并列占位）
来源：http://dali.jqgufenzy.top/Article/details/gt2lcfhdkwn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sysykeji.top/Article/details/gt2mbjtvytk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ydzc1.top/Article/details/gt2hrlkpjol.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gt2pxvsgqvw.html

[Q57] 行号
来源：http://dali.zycfv.cn/Article/details/gt2imkxtmxo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rdxmokag.html

[Q58] 累计求和
来源：http://dali.yj202588.top/Article/details/gt2tbnkkejb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shuidangran.top/Article/details/gt2ihhfrhhl.html

[Q59] 分组内累计
来源：http://dali.nanxuanxn.top/Article/details/gt2mneoimqk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gt2lawraycx.html

[Q60] 取上一行 / 下一行
来源：http://dali.aibaodan.cn/Article/details/gt2lojykbit.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnxiangtu.top/Article/details/gt2lpmppzge.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2rdtgxrnc.html


<!-- 参考信息 -->