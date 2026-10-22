代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2scsydkui.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ncoqwvql.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxxerlz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpuaaba.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbodvbf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeiddpnm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhqladd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ffocpbbk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqmsuim.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2neaukevg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yqriymth.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnmwsum.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufchavnn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkascew.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2idubirdp.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2yjncwriv.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfjqxtd.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbprorn.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2fckacprk.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2olehpyon.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlqzcau.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsccryzk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrnjvct.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkucwbq.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbihawq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qigaetfw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2osssqjyi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2neljcmnb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ymikwxos.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2obkmsgls.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2anurhwph.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2jegrmqua.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ussvxriv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wasevase.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqclhgp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljunntpx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpintxgc.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbqphgd.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbxnjzh.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxiuapmi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxjwqjf.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkjleng.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxipjmr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2elacjfeu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrwtegi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdhvbva.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nihyrtaz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyevmpz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtxnigj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2casgfdpy.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtadbehc.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wescefxb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2qndkuebw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2feveqnod.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2onjcqmnz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwjyvek.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xwisnifz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2wghmpbdt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dezchwss.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqkptig.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ehncadbg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzydlpz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2oglfvzfp.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ldphugcs.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2iehpusor.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsejvef.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2twjswzie.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhiywzz.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyqzxhh.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2lpaayysi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpzmpef.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgbyhgh.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xsaqsxxq.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdksebxv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2oibkumwg.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfhgnwq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2evxjpzsa.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkpnwbw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyanyqr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgmxofl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzjjubt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzedafm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrfruwy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kytznqek.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2beaugwye.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2zucfxzug.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yavipzzl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhairyk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjnimwt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzhglor.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvzrooa.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyxymwd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bolcyqyt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsezuuw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnyfevb.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfemueb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjxcfqw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsomypr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jqooxxgc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsnbzsj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2meyvabqg.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtokfxoa.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2butgnfvv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zolqigkv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2cfehdihd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpcxypm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2azjdmdpz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2mruabtac.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykeprcup.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgpnioa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezicbcxc.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbwdket.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtcagdy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntaeydxv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrgauqc.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzakuhtc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2cmaauhjo.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpipmcd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vkagftsk.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkmwyit.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2mslxwpxt.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xselpzya.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2srbqtlxk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdkjbas.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcglczi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2trugzqfl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rnathvrg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2otshgtjp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2difssdcv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlimjqa.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqyzwiw.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtfahcn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiboknjc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zargkinq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2fduyjhsx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnelcdmi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxhhoif.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpdjgby.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvixdhxi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ridkvjhf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbcdugg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxfeqvi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwsmqqw.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2bjezthos.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2xntptzik.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvdzlkq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2chujtlht.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2mrskluoo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2rexvkotq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwohzhk.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwldafo.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwtldeo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzafmll.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsjgzyj.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2gkosckvn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2szyqdxfd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqnnwrx.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhaxwtn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhrjpgs.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxwgbzh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfupwcl.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2mhliqbgx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2poecyvol.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2wbahjbjk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfabtdkm.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrbecih.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvjucyj.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pobmsopi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2pofoajnf.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzvdjll.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhgvckn.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fwadcbjp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rusykaze.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2umlguksi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlcgyey.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkqmjpk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2srewxzox.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2mdiiopfg.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwsjgny.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2eklnfihm.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2poylbfrt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgapsmf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnezfkd.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlicgla.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eabcpaau.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2maxlxvum.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2opqfnrcv.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgwbgtm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmryrhoe.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyfbfer.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2rkaxgphq.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwowktk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzizgixq.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2waqvhemw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmpycrz.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yorihlwl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtaubtr.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jsseiwgx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfuazgzt.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2eueohffs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpecnhwx.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwgttia.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvfwkxj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jvspnnxq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcglsgp.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgyfisu.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2imxijlqg.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpviwsk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gchirsmq.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hryravjw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2luintsql.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xttxyjsr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkddxfyc.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqvgkog.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcanvex.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyftyum.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcqgynr.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2exhqtgqt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpqnuux.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2meqgcybg.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvqndsz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbwwwwy.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2hoznwenu.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2tgokhogn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2btdshmvj.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjszmmce.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2krsolozc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpappcqj.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkvnxjf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvfezsl.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfwxqre.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhxpimw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2geiyefkw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bihgobmc.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcsrwho.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ojncxqfq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2edqahpmi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvugjtp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsthwsqy.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pllcbecd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2tyntaegm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2paqpcwat.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sizmebuz.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdgbywx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvrhngk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmglrhdf.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2csnglpvc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vthgnoyd.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2djlfvreq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsysgju.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcywnxb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpvtdzg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgbxcqc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgdsxwv.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqvpktn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpevhqoe.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvklvrs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqerjxzs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2elpouess.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2moojzonl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpeyrob.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kjduudiw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzimcex.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tmevliov.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhcrbss.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2vftuknub.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqzrwhk.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcwstqo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qonrrkxp.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2irgzpnsn.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyrgyuj.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2soxnmnkq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtrntuf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpzrewc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrhusbo.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gixwciar.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fevamhsi.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xerycciv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2frpfdmkn.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2fvikuzyk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiviljql.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjuqrdb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfqmfdm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqujnlfx.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2escahoth.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcmjmnj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ektlvayn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2usrqtgez.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ziphgykf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnclpjy.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mogayuih.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrmdasi.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2awrzytqy.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxmozzq.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dycbizci.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdroyzr.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2sprkrncr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqngxgui.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2miztprqa.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyltnhba.html


<!-- 参考信息 -->