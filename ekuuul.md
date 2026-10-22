代发 wailian999

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2awcdilii.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsppgor.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwbuekc.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oioreskp.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlawdxz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmzbbqh.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgztylb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxbughn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2qqaijdek.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjqwnto.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zslljzmx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfumcof.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhkvwch.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiefejuv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmhfmwj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjxnnwm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jmadmdpf.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2picjvzvv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmtfuak.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2yaetwfze.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ooeiqufb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpipyha.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2obzeghpb.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdktajt.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyaiqpl.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2iellvprk.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbivsjf.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ygizblah.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zjluuqpx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqdkxxa.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hmoutbvm.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnxnovs.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2efgrdryu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxyhrxm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2kevfslqc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2avlbjsld.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2juztimsw.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjbbock.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nakxrsrd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2euaeghlh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2gplibbbt.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpxoouh.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcvccyv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2vswtyksl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnjuslr.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwbtkwu.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkebsje.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhypqjr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2yhijfonk.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yganhavt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xswvmygt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2muaejrqb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xyithwpg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkmqgsz.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgmlhpb.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcluwqj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vecdradh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdfvbij.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdkjbli.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgobqcag.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2buamowcn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbzahbg.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkjsmfk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aklifyod.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zicgwdsd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2icbseipr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrpptez.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdvwozr.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmvicym.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuilcax.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxcvpax.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnjdvrm.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqooxct.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbyguxg.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2amlldwva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhsiyno.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjwrsmt.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkwtniw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjaccth.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sltwdgbe.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nspbxern.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnatuwix.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhdqbzv.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qysuvcap.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tsiksvjp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2uysxcxmu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnzbbrx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wivbukjp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2rwivngbv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2avmbinqg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwvjbdv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xswapuph.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqilqvj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2glwyrbyq.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2epmufibg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxacvfm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxkotia.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcghtfx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2afdizifd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2umjnwyqn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdndkrs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvpfdqw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2silxtqxu.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iiuxmzxm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2dsakgdik.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2svnouycf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwjvgbz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fyowzaqb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2otrjubzo.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtepunjm.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtcjhbs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzmuuhn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2wcslzqre.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hebwuzfk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2clobkdvx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2onlicyop.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oryfkswa.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhclfpn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibaptfva.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2aczqmixn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlpsbut.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkxllyf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsfjsce.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxrtsql.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2mpowgegy.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cewlkktp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkgpsdn.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmlssdg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbatdfr.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2atvlosqj.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2pauadtwi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2nheclzjb.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zenbqusy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nubuzoov.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fizokzzi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxshaze.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2tisibxfu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2heffjhrm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hcoozwxg.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2hayiagtg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzbekof.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhjmsfu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2gahsrqvx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwpaaff.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvefzfb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmhnfwd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2esxjvnyi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqubhtj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cfipfnxw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzcnpea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zyyocljg.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2fepdnfyy.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsvrbwg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bgboxdfv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzsigfh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqvnlgr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2qktemnpl.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqtovkf.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuphtem.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2psxanurg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2agpqgwvv.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zoggdidc.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2xilvkqlf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsymxdgz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2cayjyksc.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2whssabvt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbyehrw.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrtsubz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpacmjko.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2cpppmfaj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnopwooh.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgnwfec.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvelnsx.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvuhhnp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrgrslc.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pieiumfa.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgewugby.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nkelbofy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmoazav.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2whxuushb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2srzxzxcc.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2oziebyjh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mtawrnhj.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2gscwxthj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2chvnffyv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2lesvbxkt.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyfxvhy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqzrzsa.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxwcgfj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuomvij.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzlskjw.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wvneccul.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzeitkfb.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lxworptt.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpckrerz.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmuekqb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcnxdym.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vicpiagi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2yvldhtkz.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgckcqp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyhxtcw.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cpadphih.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pembwjfg.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zihzqptc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrxdpao.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kblrazyb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2aidentdj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2auqfdmpp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2zskgemko.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgzurmv.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfroerfr.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kobtqcpj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2skglwrkc.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyxoakc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vevsooka.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqdzyva.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsuxwnx.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2czhutowf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uigabpsz.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjvskix.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aoootfos.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfksjcu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfwmzkd.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwigaxy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2inmbpsal.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2luefkavd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbanhrqy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2yafksssq.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfsfkqu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvkjpxf.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2mdylrfox.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbqzauq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjkdxsg.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yegvqawd.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uepziqqx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxahuktd.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvnvafi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlitpkv.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dacavdhh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtzrbvl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2gyaxfoiq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2elxmmgsx.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsunntf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgquzqf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2heruaxtv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnlvjky.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvumvcbv.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aaybarbp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2zidnomom.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqkaqot.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmaugkaj.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxijblu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2meiobiau.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2sszvnybk.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2swiadpim.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxgrjum.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2umrwihiv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkigfzot.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nonucjff.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nypdlvll.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhhtrhk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzyybpyv.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dvexokgs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2suatgtan.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2frarpgvu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmmqzlq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fitdaqon.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kgecjuuz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2krhqergr.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgmnbeq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gsitymdr.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2luotvoms.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjbqsbm.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsxjqlv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pazrjdbg.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjkggve.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kqidfwts.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbkxsxm.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2vettamum.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxacadqi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqesggc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2osyiaies.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqpmnyb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjizyif.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dthsscxu.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpsxtlr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkpkzxf.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgpdhff.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdxzldz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2peyxotzq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfrikhf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wasdghit.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2twfdkdut.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bngodird.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdaqtnt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vongrvdy.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhhvela.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwfdnne.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uohhunfo.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpyegas.html


<!-- 参考信息 -->