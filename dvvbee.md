代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrneshfn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kodstuom.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2irtlkfkn.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2sekzwfep.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmklrhl.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2livoxghs.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqykhqzh.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2fctlckei.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnfzeis.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrqdozv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzerloi.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyrenxs.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cqceflsm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylffornv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2tujlpnde.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2scahfrpe.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2rqeounxn.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsnaeyh.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwiklzx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2enmsfyev.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqjsgfv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gnitxwkr.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfpgysb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdrcwgx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpvlbuy.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elbxsqqa.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwhmauf.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdqnkxc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2lntnavgb.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjeavsdp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kapkqqav.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jxszsbzi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ptahchkb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlocsqw.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkeydqq.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2nglrcylv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdupcrz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkjumny.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mciyhgkf.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yifglafh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpwpujx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpqulpp.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2snaujmnm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qntmijig.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrmuhru.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2scolibya.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmttkya.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2enihpxyo.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfvglbp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2wpiotsit.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqvnqve.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2vukpkfwo.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2mfslveiy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdijfqp.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cagffqpn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2icphzevm.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2bmixhmyk.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2arukqjre.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmvdrmq.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2chtmkfyq.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhathce.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyyxdrj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dbetnjkb.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2cmidksam.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohprjmoh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbpsvfc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruozcyhy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqttlcpe.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqiqbke.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2zooarpfo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2facxgrbf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2glaozehn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cezszqjm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2arrbjxqw.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wqueznnw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfzqobn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojthesvy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsykigb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2shxzyfbt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vposhlnl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdijsrl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2aapxlzvn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxldhsr.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2unkawjgl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlphuhw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2egyvxpxv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwjhmzh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2hurtwizd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2igakgfmw.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsmzyzx.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbgdawl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdbrfce.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhgyonb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2sytkqtnu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjyesxd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnujdwd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhakauzo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzygkit.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xonpzffp.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfmxguw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2gcynapvb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvaleba.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2gacdzdhk.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnqjlwt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2yayybosd.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsqttls.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxoaufpr.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyobwbb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2gondwckk.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfuejfu.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkypgzk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmdfepq.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjoxebh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2libaqugy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrwbinf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvihkwu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2menqejph.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmzbpab.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgvvscv.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2igweunyq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhrpzja.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvnwyei.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvsyesx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fabdqocb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2iodraash.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnanvep.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvetpagg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2tisrdubc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2quprshpi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrydzfeu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cghlobjd.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2gfeurlsi.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2gooijhmc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ofusrwti.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2sklydhes.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhqcdkd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjbikus.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbgoowz.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2osffizep.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2vemgghfc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpaewyh.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2twvpduol.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgtsbto.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2llcbizku.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbfrsqt.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbsavix.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cazwypyw.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqhafrp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnwdbwu.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqayhnc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2beivwbkh.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyvnbda.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmazzvyz.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjcsnrr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dctoerno.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2swxzxaut.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2omwquvdl.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyerxzk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2oajkpnoj.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqqfbmh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqdjmbq.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsiihns.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2batjeugt.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ietvldpr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2jqswuieg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnzotnp.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2uxteipsk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgbtaar.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlyxyor.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ggofmknj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjnyleg.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmeofma.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrasvotz.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwtrkjq.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqgubno.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2adkywkvj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2emaehzdz.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qppflarr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2blbniuik.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgbgpbb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdeqkdsv.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfhapkx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tterhsjb.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bezbwxjk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlreoczt.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2njjenyhb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcitmid.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ukifjxaa.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtusnji.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgbkhds.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsccldgj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgupvui.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnhalic.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2inxihdqc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgiqfmo.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgdytus.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2urvgusua.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gcambohy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nekxrcmp.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2homgpmqj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qoemilcd.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2onpcxdvk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dogoudbz.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kskxglns.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ompnaykz.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqwwolx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2unxbutav.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcmvian.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hozwrwzz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2rabigwpd.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrmvtqp.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsyjurs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ibemmjgp.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2idkmpohu.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aocdyagv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fedvwkgo.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zduuvbvv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjbgllr.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrykprp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhwzaef.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwcxajm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qivumwpj.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhnbkiy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2svzxoylp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oacmcouo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqegvmfn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqzpnkb.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrqnuud.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdjbzru.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhgvnsm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fiapzauc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2niwcbggn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqmxnak.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvyvwzg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jyntvhor.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2prwfcdvs.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2olnymraa.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjqlxsm.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2knyqlrre.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ledoibrb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbeleau.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjdiwaa.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2athrohib.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2zipzxboj.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jueqnyrp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcctanwc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2efsimqli.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mymlvqqt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uovextsi.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmvrtqo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2eaptuvwg.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcehhzg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcppmgy.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbtgyvv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbecqnbi.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpdjize.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjebguu.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmfvgqd.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlmvlsl.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrjhzkr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcfooeb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2emsoglhj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwilobdi.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2euvzhikx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkyaxai.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyehlut.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsaypoim.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkrbhme.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrpyzjh.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rvktvmoc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2jirhhdeg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgvcuze.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbitrgp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lheagydo.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsuqpoa.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gilcuavx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yuoqcvfc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqjiuoz.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnjfrdw.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfuubtoo.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkqclvp.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcphpmr.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oboknkbv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bapnlymx.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2nosvetua.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2gofazygr.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2upmamjpd.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2naueggpy.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vejrkklf.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdmlfmb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgrjdpm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnpmzlz.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgmutpn.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnkmskj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvxjjlo.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtkpyoy.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2idfnhoan.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxqoeyw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2htskmrhk.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqnkoos.html


<!-- 参考信息 -->