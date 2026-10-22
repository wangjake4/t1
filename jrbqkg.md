代发 wailian999

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wymdmeaj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyaivakq.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2becfasqo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnodpxnj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjznqmvq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyedmmq.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgkxdwm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2lmascoyx.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpqyhfh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rtaprqbh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbnyaet.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2esflbrjv.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvtwfif.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaszfzg.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iavsejux.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2aaclrhde.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxvkgja.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2mehlfibb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqpyyom.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2yohpyxln.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2djsswham.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxsooqm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebazzxnt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnfcbua.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2louoaike.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxwnpcw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwszuvx.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2awnrjfym.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkpyrrc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zzeyffry.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ffewlptb.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpmkyry.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2egcpvnwt.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnyvbng.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwvhxek.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjojbdz.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2predxyyc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2asfdziyf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqddftf.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yzndsbof.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kqadcdhr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaauwvft.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2hksquomo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2bslaayeq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2cywzwjvh.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ommsjocf.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wpawsodv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2eaehuudw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2rgiapcrx.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dydbyamx.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyeysgqh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2xynkhydm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvytoru.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgwcqoc.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lodqbtet.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2oditocjo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpdnaob.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfbupxy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvojkmi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2analhpkg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuocbrx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2lixsjcnh.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfitonc.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkzloub.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqavzuh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2smbldoop.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uexsutsv.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2usgjubjd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnywzerr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxkopeh.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykaohlqj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjyljkn.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2eutaiknv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypoovjgi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ocierrno.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbgkifx.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2bszmento.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2phvolujy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdmgzod.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2iqinhhif.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2upzttjvs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwlihjs.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ryupgzhx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvtsnuj.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuwhaqi.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2fphvjpoq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2epixmrvw.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mymysmlx.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2donznytb.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtfwaia.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2svrogjeu.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zsejvbkh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzvxdfg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2hmexeaws.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2aauenofu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjcgoin.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhmmoho.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2lujeiral.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbtvmww.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzinrzi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2urkpuyeh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2vwagkgrx.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ezspbrxt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpdxfzg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2xybkmhge.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2topknkes.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbgxzsm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkehfsp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jnimzmpd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2icjkplgp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnmouwz.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ueswdaxx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2icivaxau.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2supzqzrb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkjpxcb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2siidzixk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2elqliryn.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2rigaovqz.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzkcqyx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2knacdeps.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2cumuqsim.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkehdes.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdonlsj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2bwaztppd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2avzaulpj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2cibkxlhg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvaizmh.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2zfixbytm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2obhhypzp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhjsuoc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2byiiwege.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhzywif.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2wgraakgm.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zgazzvtj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2doosnkty.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmbjgqj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsqqjsa.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nszhayds.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuigvsq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzxewiz.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ccobobmh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjqkofs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uszfmcyl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2libzpewb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2apjfglco.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2govaashz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfzluys.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2fexwgrhn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2aurhtagu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrkhkfe.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2rkutgqts.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wawohfjy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2jpygyord.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2wldzakvn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhlcwsy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsyrezx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2udspaztz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2fggjknfr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjeljnr.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2plqddoih.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxdlngp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuxpgrs.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jiecgwki.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2otvhivya.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ilomvkss.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhviprj.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2uulgnpjq.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqeghmk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jchjkeko.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmompak.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2lidjndwd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2pobymwcd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuuiardn.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2iikutakz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwwimha.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqzkvrl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2woxrpmlu.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2uywprsgp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbmsfta.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2loiqtomc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2eellwtpr.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2nroehgcf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghctghjs.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2opthlroy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmelteq.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjyokdk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsehynhk.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzjzzjm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2iuekshcy.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuguetg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xsojxsdv.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwieghj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2alokizlx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2pxscrbdm.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2leztbvmj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuwrnyw.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2cejmvtkd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2mihsmloo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2yflyokas.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nplwhloo.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgugmpex.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlqsqdi.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmohcicx.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlnbrca.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2appdriqs.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2isultbla.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrsajqo.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfqzkjn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2tecxluas.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxfhema.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzbdxrq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pubqqxsj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfxdaix.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zfskfcbv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmamcsn.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmuepmp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2okseaivl.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlqsfpi.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvfzaiz.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mooplbaf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqttrqx.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gaeufyxv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqvvdgk.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2twsoujfi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dniybxca.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ymizslsk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqqsjeg.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2twhwaubt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2scqjxzev.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2udofethe.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrbozey.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnwklfx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2owjhsqwf.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2twzpvdbu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvzylhq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsifvhy.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2eeiklyrf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgyqxlz.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2gqoevtzh.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2eebjnlnn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkuvcvp.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oknpegum.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfcqsae.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vaehfalr.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ryllokcs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2quiokfjq.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqsmgoh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbselgkq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmddxfh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzckaqc.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2keibnthe.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2lqslesrd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnosxdl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2nycbyuyt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgklhyu.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jgroslyw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhhblyn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbtzsmd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cohkttnl.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kxawugeq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fhunhnqn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxalloij.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2obknxcnn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2drbkcgvd.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2siprtnkx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkooudb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2snrlzsxa.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwpgjtu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfwwyll.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnawjeif.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnbddxo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2eawzapcv.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pekpfmvf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjtkewg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2esvrgqsb.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrnkrhv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yalogjgl.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pegbvauz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rbinrdlo.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyhdccn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrlkxbj.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2hyeoxgkt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqyhdvn.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qpustfkr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rhobawmk.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqcoxvs.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxacpaoc.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2risgfzeu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcrhfnu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2irogdkms.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpskkms.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rukrnqtl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwlgxvg.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2krxytfhf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhezoyh.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2dlaihyvd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wleiduga.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzbbfag.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2cpekfspe.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2idmwxwju.html


<!-- 参考信息 -->