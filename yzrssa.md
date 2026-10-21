代发 wailian999

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gtsndcxpjp.html

[N10] 链表节点定义
来源：http://dali.chenjidiqi.icu/Article/details/gtrfmyjrzq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fengsongda.top/Article/details/gtynmowglz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nwbrower.top/Article/details/gtejftuyjn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hammf.cn/Article/details/gtqcgfeaye.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuanzx.com/Article/details/gtntldfvfs.html

Java: class Node { int v; Node next; }
来源：http://dali.tianlin.xyz/Article/details/gtkdovdlud.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenzaomai.com/Article/details/gtmwwnjbxo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jianghu66.top/Article/details/gtvhhhtlyh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvjhyhapo.html

[N11] 二叉树中序遍历
来源：http://dali.pycfn.com/Article/details/gtgzcrzkjl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.svipenyu.cn/Article/details/gtlazyvjay.html

PHP:  // 手写递归函数
来源：http://dali.yongpay.top/Article/details/gtuuviuqxc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gtbcoqswoz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ehwqpu.com/Article/details/gtcycmykpd.html

Java: // 手写递归
来源：http://dali.yj202588.top/Article/details/gtffxmuect.html

Go:   // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtoiqyafkh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cucudq.cn/Article/details/gtuwiziwqt.html

C#:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gtpxyerslu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.haohaochexian.top/Article/details/gtmgjftkho.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sxryk.cn/Article/details/gtqowfbuiw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hammf.cn/Article/details/gtqgfzjdag.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sweek.top/Article/details/gtdleyeapo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gtanjtuxbn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gtpkxlqxgh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.havefunace.top/Article/details/gtiabmnwig.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgfzy.top/Article/details/gtawifefwk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.316326.xyz/Article/details/gtgvnkypeu.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtdsqqovru.html

O. 并发与异步
来源：http://dali.yvedp.cn/Article/details/gtcqamebhe.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtewjalhyg.html

[O01] 启动一个线程
来源：http://dali.ivvv.top/Article/details/gtdsexshci.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoepwphmv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyngjnbyg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvabytag.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gttkjwdfmf.html

Java: new Thread(() -> f()).start()
来源：http://dali.vqdsnc.cn/Article/details/gtnobnnrdl.html

Go:   go f()
来源：http://dali.sufxvd.cn/Article/details/gtdosjfcie.html

Ruby: Thread.new { f }
来源：http://dali.jqgfzy.top/Article/details/gtpikvrqrm.html

C#:   Task.Run(() => F());
来源：http://dali.zycfv.cn/Article/details/gtmmfhhlul.html

[O02] 使用线程池
来源：http://dali.chenlongwang.top/Article/details/gtwzhztble.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hammf.cn/Article/details/gtzadjqihi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuuitvcad.html

JS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gtxjcvuzek.html

TS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gtfqwzknfk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.bjfxy.top/Article/details/gtymswnano.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.guannengcc.top/Article/details/gtzzrnclsz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhiwuduotai.top/Article/details/gtnuloggkw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gzhubu.top/Article/details/gtpaojkqjr.html

[O03] 加锁保护共享数据
来源：http://dali.jqgfzy.top/Article/details/gtljdoxfem.html

Py:   with lock: shared += 1
来源：http://dali.kuanghao11.cn/Article/details/gtfvqztzrn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nanxinkj.top/Article/details/gtcqrgnwds.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tianlin.xyz/Article/details/gtmzazmxxc.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gtdfeafoel.html

Java: synchronized (this) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gtazwkordw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.316326.xyz/Article/details/gtnbnhssvo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthruobtzl.html

C#:   lock (gate) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gtbbisfbzs.html

[O04] 定义异步函数并等待
来源：http://dali.daria6918.cn/Article/details/gtygppozzb.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxinkj.top/Article/details/gtxemnyrvf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.aizwys.cn/Article/details/gthkcwqjau.html

JS:   async function f() { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gtbbgzeglu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtxvbjqjcu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yangfankeji.com/Article/details/gtjkgwgvqj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ivvv.top/Article/details/gthdpjqqvw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.snrcjt.cn/Article/details/gtzgsfmgbd.html

C#:   async Task F() { await G(); }
来源：http://dali.hywenlv.cn/Article/details/gtkcsthrkq.html

[O05] 并发执行并等待全部完成
来源：http://dali.sufxvd.cn/Article/details/gtgmuukejs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gtilawesop.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.meibo888.top/Article/details/gtmxxqxiss.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gtdfemrjlg.html

TS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gterelxltf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shangyingyoupin.top/Article/details/gtcictyprz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tanke756.top/Article/details/gtnkltzlbi.html

Ruby: threads.map(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gtlqfatkvd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jlsjyb.cn/Article/details/gtqzugboyc.html

[O06] 使用进程池
来源：http://dali.gzhubu.top/Article/details/gtsdiyzppi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gzhubu.top/Article/details/gtrvgirzmy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yueranfly.top/Article/details/gtqzxollcp.html

JS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gtsbqksrhf.html

TS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gtigmxtsmt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cqqwz.cn/Article/details/gtbardiljm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxcfgune.html

Ruby: // fork 块
来源：http://dali.andypj.xyz/Article/details/gthjzvpvdy.html

C#:   Parallel.For
来源：http://dali.hnxiangtu.top/Article/details/gtvvuyhjng.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtrialevfb.html

P. 常用工具函数
来源：http://dali.mhx1999.top/Article/details/gttofyvszb.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gttpczlxdz.html

[P01] 生成 UUID
来源：http://dali.0kj1m.cn/Article/details/gtntfqchyo.html

Py:   str(uuid.uuid4())
来源：http://dali.nanxinkj.top/Article/details/gtbpnubwsn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.pycfn.com/Article/details/gtxjddyzdr.html

JS:   crypto.randomUUID()
来源：http://dali.tianlin.xyz/Article/details/gtuefckzhs.html

TS:   crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gtmrbcpvpx.html

Java: UUID.randomUUID().toString()
来源：http://dali.jyoumei.cn/Article/details/gtupxvyfds.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zdqjudy.top/Article/details/gtcxawqkgg.html

Ruby: SecureRandom.uuid
来源：http://dali.havefunace.top/Article/details/gtjbljqjzt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xziqi.cn/Article/details/gtnmaeitei.html

[P02] MD5 / SHA256 摘要
来源：http://dali.kuanghao11.cn/Article/details/gtkqolwpei.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jianghu66.top/Article/details/gtqkkgochi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.svipenyu.cn/Article/details/gtabehurxw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenzaomai.com/Article/details/gtjftdbhzf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenjidiqi.icu/Article/details/gtwyxfkyoo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jyoumei.cn/Article/details/gtefegazqq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yanxiufei.cn/Article/details/gtuxjkywgx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj202588.top/Article/details/gtlttwlptq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hywenlv.cn/Article/details/gtbvfdaqec.html

[P03] 生成短随机字符串
来源：http://dali.yj20258.top/Article/details/gtbldyzrcl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fzhhl.top/Article/details/gtgdbtayne.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nwbrower.top/Article/details/gtzaiwoqxi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gzhubu.top/Article/details/gtbgsmsqqi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cqqwz.cn/Article/details/gtbewwrwki.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.vqdsnc.cn/Article/details/gtaviretmw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhongyouzk.top/Article/details/gthzsrrufj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.c1oappe.top/Article/details/gthmybdsgl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guannengcc.top/Article/details/gtuutkmhcz.html

[P04] 求长度
来源：http://dali.hnxiangtu.top/Article/details/gtwhttohni.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangdashe.top/Article/details/gtcxqvasgw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gturebgqvw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gtlgrducfd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yongpay.top/Article/details/gtcrjnoxim.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenzaomai.com/Article/details/gttozsalif.html

Go:   len(arr);  len(m)
来源：http://dali.sysykeji.top/Article/details/gtgeilnsjp.html

Ruby: x.length;  x.size
来源：http://dali.dashuyun.cn/Article/details/gtcgurmwdk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.9152youxi.cn/Article/details/gtlwlihwmz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.birdmap.top/Article/details/gtwoucxlsm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigufen.top/Article/details/gtempqoary.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jlsjyb.cn/Article/details/gtpdjunzyu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdnhwwhq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnltklxri.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dashuyun.cn/Article/details/gtbfzxaykq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtumblzxii.html

Ruby: a == b
来源：http://dali.ybcxt.top/Article/details/gtlgjbsocd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gaohongyu789.top/Article/details/gthsvbzoqv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fengsongda.top/Article/details/gtdfduupog.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhoulong.xyz/Article/details/gtihlrwima.html

PHP:  if (empty($x)) {}
来源：http://dali.cucudq.cn/Article/details/gtccilzvmj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.svipenyu.cn/Article/details/gtkpkgjdgr.html

TS:   if (x == null) {}
来源：http://dali.pycfn.com/Article/details/gtjovpfvuo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gtlwxbawbq.html

Go:   if x == nil {}
来源：http://dali.shuidangran.top/Article/details/gtloxogssm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xinyue.icu/Article/details/gtlevqthff.html

C#:   if (x is null) {}
来源：http://dali.hammf.cn/Article/details/gtftdccpdn.html

[P07] 防抖与节流
来源：http://dali.c1oappe.top/Article/details/gtqmpanxxd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zycfv.cn/Article/details/gtwwlwtcpv.html

PHP:  // 手写时间戳比较
来源：http://dali.chenzaomai.com/Article/details/gtctvqhgwd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gtbbgswhlk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gtyauzkpyr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxyhzfpnj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sweek.top/Article/details/gtaonxnuvv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.daxiang520.top/Article/details/gttevzjkqq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqrukckk.html

[P08] 处理浮点精度问题
来源：http://dali.cashguo.top/Article/details/gtioqsiuqo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhengqikj.top/Article/details/gtrzxlhfor.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj20258888.top/Article/details/gtrormccbp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.svipenyu.cn/Article/details/gtcvuynmdk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.quarkkingdee.top/Article/details/gttdagncot.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuetiantiany.cn/Article/details/gtxeljubrr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnxiangtu.top/Article/details/gtmtpmowev.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.feifeiyinyue.top/Article/details/gtfwgwuhha.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hfpthk.cn/Article/details/gtuehwdbrf.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtvihvohvx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yueranfly.top/Article/details/gtkvfbxwfh.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gttukewqtw.html

[Q01] 创建表
来源：http://dali.guannengcc.top/Article/details/gtlonuhafd.html

CREATE TABLE users (
来源：http://dali.hysaishi.cn/Article/details/gtxlvjvvnf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gtymwnzowo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cheryme.top/Article/details/gtzlxetpxy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmuwxeeh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yangfankeji.com/Article/details/gtqaipvdzo.html

);
来源：http://dali.zhongyouzk.top/Article/details/gtchhswdzn.html

[Q02] 创建带外键的表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqghgvnro.html

CREATE TABLE orders (
来源：http://dali.hfpthk.cn/Article/details/gtaonmyomn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.c1oappe.top/Article/details/gtjgboemqc.html

user_id INT NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gtdnghwqqf.html

amount DECIMAL(10, 2),
来源：http://dali.nanxinkj.top/Article/details/gteyqbjkbu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.vqdsnc.cn/Article/details/gtricayyjr.html

);
来源：http://dali.yongpay.top/Article/details/gtdjhgcizs.html

[Q03] 增加列
来源：http://dali.zhongyouzk.top/Article/details/gtxdvkhbwv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xuanzx.com/Article/details/gtdkrpebzh.html

[Q04] 修改列类型
来源：http://dali.yonumen.top/Article/details/gtbaplrxef.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.svipenyu.cn/Article/details/gtzqszfahz.html

[Q05] 重命名列
来源：http://dali.redwolf501.top/Article/details/gtsqblpglr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.guowangkeji.top/Article/details/gtgiyqekoo.html

[Q06] 删除列
来源：http://dali.pengpengdd.cyou/Article/details/gtrzitdani.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.havefunace.top/Article/details/gtxrhemrgm.html

[Q07] 删除表
来源：http://dali.zycfv.cn/Article/details/gtacjsfqge.html

DROP TABLE IF EXISTS orders;
来源：http://dali.andypj.xyz/Article/details/gtdivdtrje.html

[Q08] 创建普通索引
来源：http://dali.hfpthk.cn/Article/details/gtbslbvzyr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhoulong.xyz/Article/details/gtzobhgyck.html

[Q09] 创建唯一索引
来源：http://dali.nanxuanxn.top/Article/details/gtdecwyyjq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdkufyis.html

[Q10] 插入单行
来源：http://dali.yvedp.cn/Article/details/gtynauwfun.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.316326.xyz/Article/details/gtnzsmufqx.html

[Q11] 一次插入多行
来源：http://dali.aizwys.cn/Article/details/gtjknkjoui.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gtarmxtpqo.html

[Q12] 插入后取自增 ID
来源：http://dali.iojbl.cn/Article/details/gtjhbjyunf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xziqi.cn/Article/details/gtwltoujll.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hfpthk.cn/Article/details/gtbpytpbxx.html

[Q13] 忽略重复插入
来源：http://dali.zhongyouzk.top/Article/details/gtmrcrobnb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmlwirac.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj20258888.top/Article/details/gthfahdixd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuetiantiany.cn/Article/details/gttdgwldnb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenjidiqi.icu/Article/details/gtpogutdqc.html

[Q15] 查询全部
来源：http://dali.xuetiantiany.cn/Article/details/gtzfdzhppu.html

SELECT * FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtblknbfev.html

[Q16] 查询指定列
来源：http://dali.guannengcc.top/Article/details/gtjygfaihb.html

SELECT id, name FROM users;
来源：http://dali.zycfv.cn/Article/details/gtqkzyivfn.html

[Q17] 条件查询
来源：http://dali.gotoacloud.top/Article/details/gtmnyjerhk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtlunatmxi.html

[Q18] 模糊匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtmxzyybjj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinqigufen.top/Article/details/gtdyujuzkf.html

[Q19] 范围查询
来源：http://dali.ivvv.top/Article/details/gtsshhvkgy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.haohaochexian.top/Article/details/gtqjktnsar.html

[Q20] IN 列表
来源：http://dali.xylfe.cn/Article/details/gtkkypxwcq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shuidangran.top/Article/details/gtjfrzegql.html

[Q21] 空值判断
来源：http://dali.zdqjudy.top/Article/details/gtmbdouvwn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zdqjudy.top/Article/details/gtilhweaax.html

[Q22] 排序
来源：http://dali.ydzc1.top/Article/details/gtezncxkfp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jianghu66.top/Article/details/gtgdatoogz.html

[Q23] 分页
来源：http://dali.andypj.xyz/Article/details/gtxsqflklz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.feifeiyinyue.top/Article/details/gtdyajhpyh.html

[Q24] 去重
来源：http://dali.yueranfly.top/Article/details/gtijzsmbmu.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrefcoygg.html

[Q25] 只取前 N 条
来源：http://dali.jinghuilouyu.cn/Article/details/gtautvvgpz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.quarkkingdee.top/Article/details/gtlrqqdhaw.html

[Q26] 计数
来源：http://dali.hongshengwenyu.top/Article/details/gtmsoktjvy.html

SELECT COUNT(*) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtccbrrddx.html

[Q27] 条件计数
来源：http://dali.mhx1999.top/Article/details/gtmugdlvja.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtvvgtvbrn.html

[Q28] 求和与平均
来源：http://dali.jinqigufen.top/Article/details/gtnimbnpyx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtaopikenp.html

[Q29] 最大最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtltubld.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtutjhruuk.html

[Q30] 分组统计
来源：http://dali.xuetiantiany.cn/Article/details/gtwowprafb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gtrpbuirzj.html

[Q31] 分组后过滤
来源：http://dali.xylfe.cn/Article/details/gtryxcdmny.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nwbrower.top/Article/details/gtlpuwvzus.html

[Q32] 分组拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gtwdzzvdcb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gtenmerimu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sufxvd.cn/Article/details/gtijdjocgl.html

[Q33] 多列分组
来源：http://dali.gogol.net.cn/Article/details/gtehplbzzc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.vqdsnc.cn/Article/details/gtgjpwzamf.html

[Q34] 每组取第一条
来源：http://dali.tanke756.top/Article/details/gtnrwdjjhp.html

SELECT * FROM (
来源：http://dali.xylfe.cn/Article/details/gtxtbgpnna.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xuanzx.com/Article/details/gtwjekktjz.html

) t WHERE rn = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtuftohzag.html

[Q35] 内连接
来源：http://dali.c1oappe.top/Article/details/gtppgribna.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtdekhqgdp.html

[Q36] 左连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gttuolktsc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhengqikj.top/Article/details/gtvwfesqmv.html

[Q37] 右连接
来源：http://dali.hnqzz.top/Article/details/gtutvqycsi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.fzhhl.top/Article/details/gtaptjoqlg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.pengpengdd.cyou/Article/details/gttlbrxccr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgfzy.top/Article/details/gtvykfpvxa.html

[Q39] 自连接（查上下级）
来源：http://dali.jianghu66.top/Article/details/gtuzuttqki.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.9152youxi.cn/Article/details/gtuboshtyp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gogol.net.cn/Article/details/gtazxrdbav.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zdqjudy.top/Article/details/gtgpazqqyv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cucudq.cn/Article/details/gttpwybrsz.html

[Q41] 多表连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhkvrqcz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuanzhike.top/Article/details/gtleebhhpu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fengsongda.top/Article/details/gtcmwyaunj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jlsjyb.cn/Article/details/gtbueaxsui.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmiqricdv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenzaomai.com/Article/details/gtoovizftm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cucudq.cn/Article/details/gtpczphdsd.html

[Q43] 标量子查询
来源：http://dali.zycfv.cn/Article/details/gtxvdnawxu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cashguo.top/Article/details/gtbbpfxmmk.html

[Q44] IN 子查询
来源：http://dali.gotoacloud.top/Article/details/gteigsvrrv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sweek.top/Article/details/gtdjsvdmxn.html

[Q45] EXISTS 判断存在
来源：http://dali.redwolf501.top/Article/details/gtvbmaretb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpctsklev.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cqqwz.cn/Article/details/gtqwbtxkxs.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jiagoushi.top/Article/details/gtxdqgohzw.html

[Q47] 与平均值比较
来源：http://dali.chenlongwang.top/Article/details/gtzzdltnbl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.smart0.xyz/Article/details/gtkyphmhdo.html

[Q48] CTE 公用表表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtkwcvxzio.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.guowangkeji.top/Article/details/gtrixvexjv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuanzx.com/Article/details/gtiffmlkic.html

[Q49] 更新单行
来源：http://dali.zhongyouzk.top/Article/details/gtrzuibcin.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gtrtixzgjz.html

[Q50] 批量更新
来源：http://dali.chenjidiqi.icu/Article/details/gtgcuoontx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigufen.top/Article/details/gtxypustkf.html

[Q51] 用子查询更新
来源：http://dali.fengsongda.top/Article/details/gtstumhlmq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigufen.top/Article/details/gtzcteumee.html

[Q52] 删除指定行
来源：http://dali.hnqzz.top/Article/details/gthdvwefkn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gttcwxgtks.html

[Q53] 按条件删除
来源：http://dali.hammf.cn/Article/details/gtaxsntzth.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.fzhhl.top/Article/details/gtlkdbwysu.html

[Q54] 清空表
来源：http://dali.zhengqikj.top/Article/details/gtuwfwrmrt.html

TRUNCATE TABLE logs;
来源：http://dali.shuidangran.top/Article/details/gtisrtkapn.html

[Q55] 排名（并列占位）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlkuzrwd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dashuyun.cn/Article/details/gthztqhmua.html

[Q56] 密集排名（并列不占位）
来源：http://dali.0kj1m.cn/Article/details/gtvmsdoxcl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.daxiang520.top/Article/details/gtfjoksqem.html

[Q57] 行号
来源：http://dali.hfpthk.cn/Article/details/gtpsejmaoc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtofygolfy.html

[Q58] 累计求和
来源：http://dali.jqgfzy.top/Article/details/gtxrlrzvqa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ydzc1.top/Article/details/gthhiowdnl.html

[Q59] 分组内累计
来源：http://dali.hywenlv.cn/Article/details/gtdobuigtf.html


<!-- 参考信息 -->