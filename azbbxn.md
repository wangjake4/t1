代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2jupvnmmi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuvhwcs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnuiavi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fipdloom.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jvczyjyz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbsgqra.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmwkqaq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdebcvc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gybesdqe.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpzjkim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmbvjam.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwjmjpd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnwmgrc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wiswoozt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2qantdzus.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcdojrx.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyidxfe.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2japrcdey.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjhgozy.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2gghhtmil.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2aaubjhbq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwviykb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2aabgrobl.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlavquk.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxzcojb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzetayx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2yigvfrjs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2bapphdmz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2lokjvdwz.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnxdmnm.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2euxyttqc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2rtearhoj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2jplslegp.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2nefnaoph.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfqcqmp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdwgkml.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyinhiw.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwkshlz.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2znlwdteb.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfuyonm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2nefviojb.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaetffdd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2beeeujeg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcgehpl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkkgwdk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ioozjuqs.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kntnannz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxklahc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbuxhug.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2izwsveac.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnfasvv.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvrfolq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjdtadr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxrlddu.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2gshjxswd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oodygdmn.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyjchoe.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlppnmts.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmuwoco.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2cydmonxw.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vcewhgov.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2qrizcbmr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2gherznco.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2taicysnp.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2siihhkjp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2biruvswu.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aogkkxjw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgnbhdm.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2yjamxsdy.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2yzskcgjr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tavwmpbh.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nithggzg.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2capynyjk.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2idpbmayj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbviraw.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bpepqxpy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhgemkj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2loocwojj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpotrgb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjhyzhs.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2uacxedye.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdxhivf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpskbgq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tsthyiyp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zplcbsgo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkebwbx.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cobzphko.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzawycs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhnkkdu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uuugdtcf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsovqdu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqceabne.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2yucyelxk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfiwieb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2grqjrtkj.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2variatel.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxpsugq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qtukbvru.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2alcswwvy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dbddltzt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkfcxwy.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjszamh.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdtewvl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2imoldkwk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjpytcq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuysyca.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwziwpq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ikssxsmj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aufskady.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyybhbe.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjnqucb.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2bbaerahb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmjrdcy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsnfxdf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2pykrjvct.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuzeopn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2zlynvazo.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhzupso.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ssddtirz.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pohrdmyi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydagqmpl.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nivrksvw.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ariyjvsi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2xddpjjor.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mceabure.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hmoblcgp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbwmchn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmnhqlz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwlfuws.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdfjuah.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gehkqxoy.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrujxsd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2slxhpcug.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2djcmieac.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2xbimypxu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2djltnwjs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2aonqcudf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2rxugsboj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzypgfn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ftardlyj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2glrkwfup.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwezpet.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avgneavo.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrkrced.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvybkto.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2azlrznkf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fselqndo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2fvclaszb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2uiidgbxc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jasflvpe.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhxvisw.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxvyuss.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2oktimzeq.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2phimdliq.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkzlsnk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkbkiwz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2pejqtxbl.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2odurrwvn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kisjpijl.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqfdjxv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2guzvjjwr.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2eklnbgju.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cifsyhes.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyuuowv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmvaeyd.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpzafbz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gutrorah.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2syqnojcb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzvrhhx.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2alhcohwa.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mywvmvkg.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2uehikprm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2esqhblqx.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvvuflh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2grpgbdxa.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ueytsqum.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvrgegs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2onmmxqmp.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjrmalv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgkhmsb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjeekpho.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2umqwqzew.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxlypoj.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2djjnaccj.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gboexyuk.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mhiybvtm.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhboynid.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgilgwf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlsubts.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2muxcgjuo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhzzyez.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtuwwde.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufboemfh.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2upwengvu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxatwid.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgimcfs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhdjhse.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gddkgpnn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjthmjeq.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2dhaxrara.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2dozazgie.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qshfrnqz.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2miqsehty.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvworfr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2vftdyoej.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2yarnqeti.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2knwiblyg.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsfanrs.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyzxwpf.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrxkkzp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjhbviw.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbncsmo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwrxcbg.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2azdeqleg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwruymt.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2puecetnj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wibydshk.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yeetsjih.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpclvzv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ftteysfj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsclehe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxrztsg.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgnxyiz.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmdjmql.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2symbupug.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwxiigv.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bgirpbxv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2epbnvfpk.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkcdwgc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dukfcqfl.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2innbnhqy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvflcthi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2srrbufvh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lghkbojg.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtmbqji.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2kotdepgv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmfdsmf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqrbuoc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2usexybyd.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2osqhodvh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2vmavjjmq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2gjykvpkt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eonsqnjz.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhcgtal.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjpcvzc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjquirv.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jycmxvcj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2evfwubpp.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrefavu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzntcwf.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2knyssjyn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2uggabvpy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnvtwiq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdukmck.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2auzzlidh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2heixjzfd.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2oyohmtjh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgzvcut.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnakxrta.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cknjymmh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2knddrgio.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjefkgu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2risyxxuu.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxqilch.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfzqdll.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2pqegyxyx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ammpckyd.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mtogvjpf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuexhgd.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2yersofjw.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvhoyay.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2caanzuxq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2unsrzttr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdsoero.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjgdktc.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmmupzs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mamizcny.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ornlnlku.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fghvjlho.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfajibm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuylkqxs.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fetmmxpy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2eceosmkw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtkhcdp.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2buxwqvyh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mahjajpn.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2lligkifm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nawgdhrj.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uahoyjii.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdeurcm.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcvrjxb.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgzpadu.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnvcgom.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2uenofrqi.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbagdop.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjfwfci.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2pfloltmd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfzgoyg.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2wghenwnb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2atlczjcp.html


<!-- 参考信息 -->