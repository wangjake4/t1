代发 wailian999

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guannengcc.top/Article/details/gtypdatman.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.vqdsnc.cn/Article/details/gtiyuwxioh.html

Java: class Node { int v; Node next; }
来源：http://dali.zhoulong.xyz/Article/details/gttwfwtlnz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.c1oappe.top/Article/details/gthxllplpq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimefbvin.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.mhx1999.top/Article/details/gtjeinppjk.html

[N11] 二叉树中序遍历
来源：http://dali.fengsongda.top/Article/details/gtsnnoesgz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cucudq.cn/Article/details/gtnfbebndj.html

PHP:  // 手写递归函数
来源：http://dali.iojbl.cn/Article/details/gtjwgoccgg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gtuwiywejp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gtuekqzoru.html

Java: // 手写递归
来源：http://dali.shuidangran.top/Article/details/gthvfpstgf.html

Go:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gtpskvefgb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jianghu66.top/Article/details/gtpvswpxld.html

C#:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtwwdrdgmv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shangyingyoupin.top/Article/details/gtjiwnbjmr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugfusmyi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.havefunace.top/Article/details/gtafktwjec.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gzhubu.top/Article/details/gthzwudupc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hysaishi.cn/Article/details/gtextommir.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gtsjfvstri.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.9152youxi.cn/Article/details/gtcnkpgnhj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gtxpunobbi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yongpay.top/Article/details/gtvdxtnffv.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtgrbjbulz.html

O. 并发与异步
来源：http://dali.pengpengdd.cyou/Article/details/gtegwvewnm.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtmomewqrk.html

[O01] 启动一个线程
来源：http://dali.tian-w.cn/Article/details/gtyttuzaam.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sysykeji.top/Article/details/gtrqgqvisy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.quarkkingdee.top/Article/details/gtfnmgmdox.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258888.top/Article/details/gtuttgzyir.html

TS:   // 同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnjaagqb.html

Java: new Thread(() -> f()).start()
来源：http://dali.sysykeji.top/Article/details/gtqbfaqysc.html

Go:   go f()
来源：http://dali.jqgfzy.top/Article/details/gtvutqbiyu.html

Ruby: Thread.new { f }
来源：http://dali.ppjwa.cn/Article/details/gtzlzccyln.html

C#:   Task.Run(() => F());
来源：http://dali.redwolf501.top/Article/details/gtevdqnbkj.html

[O02] 使用线程池
来源：http://dali.meibo888.top/Article/details/gtaktqtasw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.9152youxi.cn/Article/details/gtelsbdquy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtikzgtykv.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258.top/Article/details/gtqltdyyyk.html

TS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gtshwinpst.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.snrcjt.cn/Article/details/gtbjebqwps.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daria6918.cn/Article/details/gtgiwpyzpz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgufenzy.top/Article/details/gtndjhyhpb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jianghu66.top/Article/details/gtdbcwcplz.html

[O03] 加锁保护共享数据
来源：http://dali.quarkkingdee.top/Article/details/gtnptlokrw.html

Py:   with lock: shared += 1
来源：http://dali.yonumen.top/Article/details/gtmtmccmoc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuanzhike.top/Article/details/gtgrozddkf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xuetiantiany.cn/Article/details/gtkkdwzslo.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gtmatlqdma.html

Java: synchronized (this) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gteofywivh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ehwqpu.com/Article/details/gtqnspxmkb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhengqikj.top/Article/details/gtrwvmqyby.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqvclxfmw.html

[O04] 定义异步函数并等待
来源：http://dali.fengsongda.top/Article/details/gtzivcshrs.html

Py:   async def f():⏎    await g()
来源：http://dali.xinyue.icu/Article/details/gtwaysrldy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xuetiantiany.cn/Article/details/gtapbcxclg.html

JS:   async function f() { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gtjyzfsdnk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.316326.xyz/Article/details/gtfrpzevmo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.9152youxi.cn/Article/details/gtsqkarqxi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258.top/Article/details/gtmtecidkd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenzaomai.com/Article/details/gtwybbkuht.html

C#:   async Task F() { await G(); }
来源：http://dali.mhx1999.top/Article/details/gtqbrtbpew.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigfzy.top/Article/details/gtujcjrnjm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ybcxt.top/Article/details/gtgnqlhzph.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ppjwa.cn/Article/details/gtvktxwtrc.html

JS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gtkmsrtvay.html

TS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gtiokwefyn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gaohongyu789.top/Article/details/gtlokdfnkl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacottdij.html

Ruby: threads.map(&:join)
来源：http://dali.yangfankeji.com/Article/details/gtxcxobikh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ehwqpu.com/Article/details/gtpreemeqr.html

[O06] 使用进程池
来源：http://dali.haohaochexian.top/Article/details/gtdbbgqtnc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsnchbek.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.0kj1m.cn/Article/details/gtfrclezyi.html

JS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gtnlsnfndh.html

TS:   // child_process / cluster 模块
来源：http://dali.hysaishi.cn/Article/details/gtvvcesels.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ydzc1.top/Article/details/gtqhcqgmsw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jyoumei.cn/Article/details/gtolfxbjvd.html

Ruby: // fork 块
来源：http://dali.chenzaomai.com/Article/details/gtqonzzubs.html

C#:   Parallel.For
来源：http://dali.redwolf501.top/Article/details/gtknhpjdik.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtdbuawerj.html

P. 常用工具函数
来源：http://dali.yonumen.top/Article/details/gtfjoyjdti.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtcjlnnmuc.html

[P01] 生成 UUID
来源：http://dali.zycfv.cn/Article/details/gttcexdppl.html

Py:   str(uuid.uuid4())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjxmeeju.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hnxiangtu.top/Article/details/gttmxohbal.html

JS:   crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gtheepnzmj.html

TS:   crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gtdxtpnxzc.html

Java: UUID.randomUUID().toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtisatrjvq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.quarkkingdee.top/Article/details/gtvdyviijz.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgufenzy.top/Article/details/gtnzzvpedn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yuxming.cn/Article/details/gtaluslgne.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gaohongyu789.top/Article/details/gtmrhzzcjd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenlongwang.top/Article/details/gtslnzqfwe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.vqdsnc.cn/Article/details/gtqvksuqzz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hywenlv.cn/Article/details/gtgjxoiati.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cucudq.cn/Article/details/gtrjotaext.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gtinsqjwue.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ppjwa.cn/Article/details/gtdyukezpy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zdqjudy.top/Article/details/gtmylruhnu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigufen.top/Article/details/gtihqempli.html

[P03] 生成短随机字符串
来源：http://dali.gzhubu.top/Article/details/gtrtrkvbfq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.svipenyu.cn/Article/details/gtwbykhxik.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.iojbl.cn/Article/details/gtgjcomvgz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.birdmap.top/Article/details/gttcwphhrd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.c1oappe.top/Article/details/gtcxtqeilh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hammf.cn/Article/details/gtdxcmcyub.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hywenlv.cn/Article/details/gtfsqossni.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxuanxn.top/Article/details/gtkzgfokwk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jyoumei.cn/Article/details/gtzkitovxi.html

[P04] 求长度
来源：http://dali.cucudq.cn/Article/details/gtjefhkbtx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinghuilouyu.cn/Article/details/gtdumzgxtb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtmkwqdsez.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.316326.xyz/Article/details/gtnlnclxur.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.feifeiyinyue.top/Article/details/gtfytspldw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sufxvd.cn/Article/details/gtadvqfsjd.html

Go:   len(arr);  len(m)
来源：http://dali.jqgufenzy.top/Article/details/gtfqwktqcq.html

Ruby: x.length;  x.size
来源：http://dali.chenzaomai.com/Article/details/gtlwrmbero.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cashguo.top/Article/details/gtsixdaomx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.mhx1999.top/Article/details/gtoqihbnnu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.dashuyun.cn/Article/details/gtygeiwuis.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hysaishi.cn/Article/details/gtcpijxaef.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhoulong.xyz/Article/details/gthyrtbdta.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ivvv.top/Article/details/gtofsdyazd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zdqjudy.top/Article/details/gtqgibxknz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwcjrzrli.html

Ruby: a == b
来源：http://dali.cheryme.top/Article/details/gtjmwtczkh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.9152youxi.cn/Article/details/gtigcodzqq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.316326.xyz/Article/details/gtxscavtax.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xinyue.icu/Article/details/gtpdljxpjw.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigufen.top/Article/details/gtoccwcxtt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jiagoushi.top/Article/details/gtegeauexq.html

TS:   if (x == null) {}
来源：http://dali.nanxuanxn.top/Article/details/gtlpkcrohw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gtnztvkang.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gtlknfveao.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aizwys.cn/Article/details/gtfwfqwaqf.html

C#:   if (x is null) {}
来源：http://dali.yj20258888.top/Article/details/gtbyhfmmlf.html

[P07] 防抖与节流
来源：http://dali.jqgfzy.top/Article/details/gtupodznsl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.fengsongda.top/Article/details/gtysuwjcvj.html

PHP:  // 手写时间戳比较
来源：http://dali.daria6918.cn/Article/details/gtgedfmwor.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gtpzicsspv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gtmmkmtwob.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.svipenyu.cn/Article/details/gtgcbuvjls.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.feifeiyinyue.top/Article/details/gtidtocwnv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhongyouzk.top/Article/details/gtrcxotrfq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shangyingyoupin.top/Article/details/gtsyzaibpq.html

[P08] 处理浮点精度问题
来源：http://dali.yongpay.top/Article/details/gtiaoraylf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xinyue.icu/Article/details/gtxcosddjf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jyoumei.cn/Article/details/gtuweuslla.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ehwqpu.com/Article/details/gtjwyqdsns.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sxryk.cn/Article/details/gtaleixcxq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258.top/Article/details/gtfyhskgfz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gzhubu.top/Article/details/gtqhrzmzov.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.aibaodan.cn/Article/details/gtcsflpvay.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hnxiangtu.top/Article/details/gturdzxvvn.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtqddjbpxn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgqbqfwq.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gteoaojfdh.html

[Q01] 创建表
来源：http://dali.yangfankeji.com/Article/details/gtscwpkduc.html

CREATE TABLE users (
来源：http://dali.guowangkeji.top/Article/details/gtnkrgracw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fzhhl.top/Article/details/gtnhkmcdjb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shangyingyoupin.top/Article/details/gtufvlvofg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj20258.top/Article/details/gtpncailgq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gthkkzqcde.html

);
来源：http://dali.nwbrower.top/Article/details/gtlefhhrqs.html

[Q02] 创建带外键的表
来源：http://dali.yangfankeji.com/Article/details/gtawpfnaej.html

CREATE TABLE orders (
来源：http://dali.jlsjyb.cn/Article/details/gthdtwhzfi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tian-w.cn/Article/details/gttqovetqn.html

user_id INT NOT NULL,
来源：http://dali.yuanzhike.top/Article/details/gtayzbjhmo.html

amount DECIMAL(10, 2),
来源：http://dali.316326.xyz/Article/details/gtfdpekzkc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.andypj.xyz/Article/details/gtfkdqyjqd.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gtcgdjjhqm.html

[Q03] 增加列
来源：http://dali.ybcxt.top/Article/details/gtdsdlsruq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gaohongyu789.top/Article/details/gtaulnzqca.html

[Q04] 修改列类型
来源：http://dali.cucudq.cn/Article/details/gtpsliifnd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.snrcjt.cn/Article/details/gtnejwagfl.html

[Q05] 重命名列
来源：http://dali.yuanzhike.top/Article/details/gtiykpkugs.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daxiang520.top/Article/details/gtvdptytas.html

[Q06] 删除列
来源：http://dali.jinqigufen.top/Article/details/gthznixahc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.daxiang520.top/Article/details/gtqymwqyps.html

[Q07] 删除表
来源：http://dali.jqgufenzy.top/Article/details/gtzzlbbqkh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhoulong.xyz/Article/details/gtcjdohswf.html

[Q08] 创建普通索引
来源：http://dali.quarkkingdee.top/Article/details/gtqkrfclpl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yvedp.cn/Article/details/gttzntwdgn.html

[Q09] 创建唯一索引
来源：http://dali.xuetiantiany.cn/Article/details/gtgigjhvpp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllmkwrbb.html

[Q10] 插入单行
来源：http://dali.svipenyu.cn/Article/details/gtqptbumof.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwpcbznv.html

[Q11] 一次插入多行
来源：http://dali.yj20258888.top/Article/details/gtnxcsttej.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cashguo.top/Article/details/gtylsnmrej.html

[Q12] 插入后取自增 ID
来源：http://dali.snrcjt.cn/Article/details/gtaiwckbgb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aizwys.cn/Article/details/gtkkurndwb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jlsjyb.cn/Article/details/gtigagxdzn.html

[Q13] 忽略重复插入
来源：http://dali.pengpengdd.cyou/Article/details/gtfnhanqen.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gthilvebto.html

[Q14] 存在则更新（upsert）
来源：http://dali.tian-w.cn/Article/details/gtjzsszqwd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.iojbl.cn/Article/details/gtjvhiatag.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fzhhl.top/Article/details/gtxnwjmzmt.html

[Q15] 查询全部
来源：http://dali.sxryk.cn/Article/details/gtdnftijpj.html

SELECT * FROM users;
来源：http://dali.sweek.top/Article/details/gtbqvcsupq.html

[Q16] 查询指定列
来源：http://dali.yanxiufei.cn/Article/details/gtftjustlt.html

SELECT id, name FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtafyemucm.html

[Q17] 条件查询
来源：http://dali.sysykeji.top/Article/details/gtllnbmsya.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtdlzrupqq.html

[Q18] 模糊匹配
来源：http://dali.xinyue.icu/Article/details/gtolojtxgk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daria6918.cn/Article/details/gthqvxfxax.html

[Q19] 范围查询
来源：http://dali.yvedp.cn/Article/details/gtmdsyrftc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.316326.xyz/Article/details/gtfsamjxwd.html

[Q20] IN 列表
来源：http://dali.quarkkingdee.top/Article/details/gtctqebjqx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guannengcc.top/Article/details/gtatzlaclf.html

[Q21] 空值判断
来源：http://dali.smart0.xyz/Article/details/gtjbfbrrmi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guannengcc.top/Article/details/gtlpdwcxeo.html

[Q22] 排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnijpapd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnxiangtu.top/Article/details/gthgdxsodx.html

[Q23] 分页
来源：http://dali.hysaishi.cn/Article/details/gtsdsjcmpp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.fzhhl.top/Article/details/gtsjvqdqvv.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gtyhqnvgwd.html

SELECT DISTINCT city FROM users;
来源：http://dali.jianghu66.top/Article/details/gtvegufnjv.html

[Q25] 只取前 N 条
来源：http://dali.yj20258.top/Article/details/gtxnwjnkcy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gogol.net.cn/Article/details/gtoeeizhte.html

[Q26] 计数
来源：http://dali.daxiang520.top/Article/details/gtdjjcgxrn.html

SELECT COUNT(*) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gteclxhfgo.html

[Q27] 条件计数
来源：http://dali.zycfv.cn/Article/details/gtokuddbqg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yuxming.cn/Article/details/gtxlhibykd.html

[Q28] 求和与平均
来源：http://dali.chenlongwang.top/Article/details/gtkpzhhfyq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtvxxfpnho.html

[Q29] 最大最小值
来源：http://dali.andypj.xyz/Article/details/gtdqcwtixh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtctqnknrn.html

[Q30] 分组统计
来源：http://dali.pengpengdd.cyou/Article/details/gtjyntqpnd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gturneiilg.html

[Q31] 分组后过滤
来源：http://dali.sweek.top/Article/details/gtqhpbksot.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sufxvd.cn/Article/details/gtfovemylj.html

[Q32] 分组拼接字符串
来源：http://dali.yj202588.top/Article/details/gtxgcerark.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gtmsirlkwm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddjbuicr.html

[Q33] 多列分组
来源：http://dali.ydzc1.top/Article/details/gtpjxjojvq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.andypj.xyz/Article/details/gtmabjwpap.html

[Q34] 每组取第一条
来源：http://dali.wangdashe.top/Article/details/gtiqetmber.html

SELECT * FROM (
来源：http://dali.jinqigfzy.top/Article/details/gtbojhahry.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.0kj1m.cn/Article/details/gtvizehblt.html

) t WHERE rn = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gttekqixci.html

[Q35] 内连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzyinaij.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gtreyapaaa.html

[Q36] 左连接
来源：http://dali.yueranfly.top/Article/details/gthnainqce.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gtzzybzrda.html

[Q37] 右连接
来源：http://dali.kuanghao11.cn/Article/details/gtnfypncrv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gaohongyu789.top/Article/details/gtndmdmnsq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cqqwz.cn/Article/details/gtunesjlby.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhongyouzk.top/Article/details/gtkljamglu.html

[Q39] 自连接（查上下级）
来源：http://dali.chenlongwang.top/Article/details/gturqckysi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hywenlv.cn/Article/details/gtbuwluarf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ybcxt.top/Article/details/gthtjgqarg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.quarkkingdee.top/Article/details/gtowglfsum.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fzhhl.top/Article/details/gtqsllognf.html

[Q41] 多表连接
来源：http://dali.hfpthk.cn/Article/details/gtzauisrsz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cqqwz.cn/Article/details/gttcldkmnw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuetiantiany.cn/Article/details/gtsxqzagun.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.vqdsnc.cn/Article/details/gtanspwrxy.html

[Q42] 连接条件附加过滤
来源：http://dali.birdmap.top/Article/details/gtxqkpofki.html

SELECT u.name, o.amount FROM users u
来源：http://dali.0kj1m.cn/Article/details/gtlrkocajd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daxiang520.top/Article/details/gtojjlumla.html

[Q43] 标量子查询
来源：http://dali.andypj.xyz/Article/details/gteoopmhym.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zycfv.cn/Article/details/gtdnpnyxxw.html

[Q44] IN 子查询
来源：http://dali.jqgufenzy.top/Article/details/gtdxzuqmyk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ydzc1.top/Article/details/gtwildqtfx.html

[Q45] EXISTS 判断存在
来源：http://dali.cucudq.cn/Article/details/gtvxpsqtad.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gtcmgvfkeg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.9152youxi.cn/Article/details/gtxyftytrf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gtqjlseebt.html

[Q47] 与平均值比较
来源：http://dali.hywenlv.cn/Article/details/gtglmueyym.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.andypj.xyz/Article/details/gthpltzotf.html

[Q48] CTE 公用表表达式
来源：http://dali.redwolf501.top/Article/details/gteoejnkuk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxinkj.top/Article/details/gtorgxqswp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sysykeji.top/Article/details/gtjhsffhnd.html

[Q49] 更新单行
来源：http://dali.chenlongwang.top/Article/details/gtnnfhcrzf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtlwsdhzbt.html

[Q50] 批量更新
来源：http://dali.shangyingyoupin.top/Article/details/gttwikmgoc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yueranfly.top/Article/details/gtcwzxfkiq.html

[Q51] 用子查询更新
来源：http://dali.jianghu66.top/Article/details/gtrnygdgpz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtzuultsjb.html

[Q52] 删除指定行
来源：http://dali.nanxuanxn.top/Article/details/gtudnuafgt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.daria6918.cn/Article/details/gtvjarfvza.html

[Q53] 按条件删除
来源：http://dali.ehwqpu.com/Article/details/gtwzkzhkrv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenzaomai.com/Article/details/gtcynexlga.html

[Q54] 清空表
来源：http://dali.aizwys.cn/Article/details/gtyjmlrgou.html

TRUNCATE TABLE logs;
来源：http://dali.nwbrower.top/Article/details/gtpfszpzdq.html

[Q55] 排名（并列占位）
来源：http://dali.vqdsnc.cn/Article/details/gtgkvqiyka.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj20258.top/Article/details/gttplhthyh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cdnleiting.top/Article/details/gtmyvqvhfg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwnwgdiw.html

[Q57] 行号
来源：http://dali.tianlin.xyz/Article/details/gtuejqdqno.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cheryme.top/Article/details/gtbhputodh.html

[Q58] 累计求和
来源：http://dali.iojbl.cn/Article/details/gtuliiudvv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtrbkdwnqm.html

[Q59] 分组内累计
来源：http://dali.fzhhl.top/Article/details/gtqtlhutxo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cheryme.top/Article/details/gtavhafyop.html

[Q60] 取上一行 / 下一行
来源：http://dali.fengsongda.top/Article/details/gtaqwikfyx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shuidangran.top/Article/details/gtqzgervnz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtgkiuxhae.html


<!-- 参考信息 -->