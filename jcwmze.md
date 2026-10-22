代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zgziikgx.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmltswd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gmahowru.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtbmplo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfvyysd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpydeyz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ogalxhhv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlakzrp.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxrcmpd.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2gyldziem.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2deixkfun.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2zaarzspp.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mervoufq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2klxzmmjl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cbuuktod.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzczomk.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ubupvlem.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2crdwvdjl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2maefcvid.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2mnptnnwm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2dqocllur.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2naheitlk.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzlzcjc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbpnpdu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2uthmnsnv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuyhcdk.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlmfode.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2shayiqgf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihctznog.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjiflkb.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vlihtjqx.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ceonmkvl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqicrzg.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2shfyfekc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhirtnss.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ncuufrty.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2euqcvohp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzlkyfu.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjgkpts.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2gidqoxtd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2katafhrt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtpnuox.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xibipbuz.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpjcjyq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxcmsgd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcfkvpi.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2weknpvsu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxbycvu.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpfokxz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsvtmye.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ebteqgxf.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2yzivtmpr.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnfmaoh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2qepjgxif.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2mfztvmuw.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2otevtvqr.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbtlffz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwqcidw.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xstvelxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcjcybu.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmmkaat.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2njaavndk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2emovrexc.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtphyjoq.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvamxjwx.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvlxlsl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2cdypqdbv.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsxrwcu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkzusby.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2zoioownw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqnyehk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvmcyfp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvegtcx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxnwwfw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwscgkk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2puqjjvic.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qomtgbir.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlbwxgn.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmhoxzf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqpamxf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkehkyy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zomjuoti.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxebfrrp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2luzkefqr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhuesdl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bittolao.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzmqpaa.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqemnnl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2qpelqpku.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2gusvbgta.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fatvpbje.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdqbxao.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpuwyvw.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2takmadfq.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gngzfuef.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pswfuhml.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyccrtr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvygooy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2gxehvqld.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhmewjf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgruirnv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2heifpqww.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrftyvka.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbmjrvb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2exxmeppf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeqsbdn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxjnkaq.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rienhupi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzojkix.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlpyzyv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgsoawu.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2edznsurv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2iozeyrhh.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yelelkfi.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2szhbnfve.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2njcrijzs.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cdofngha.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2brdfajhg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2utpyibwa.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqlkhjs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyocfyr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwwtyty.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxebjrl.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2khwktvlf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2oelggrci.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pibopqpm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2vhedcxij.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecijaelj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ukknzeol.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2crhgeqvj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2iiddlatn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2milmwdgp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ftardtpt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwebulls.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vjeedkbl.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2fawfwgni.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2orsxrwwg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rymqebcf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmbinyp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ummwacxy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2eriberql.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vagmucxe.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2eoawwnud.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmapqpi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrgzbrh.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zntqrsif.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfpqllv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdbrgcx.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbtmlrw.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2simcodxm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzezcwv.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzwwabz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2judgrhic.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqqsgog.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2stvpgmiy.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkxjzbn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2klpaisgc.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ezyxhwcu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tumzgjcw.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmjeffj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsyqisq.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2uuviirtt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhrkarv.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2iafeftah.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbdurtt.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2bgaqbkgg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxodkjp.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfdrpws.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdgbjhl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2rdejcczp.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2amaorncw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2awtsmrxg.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbjgkuu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2kezdobah.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2niwumeak.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2epadstpq.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqmsory.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfcepvb.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2miuefjla.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjqmjvi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dggbdqbw.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mngaxuzt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjwebgd.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ulipkzel.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxwqups.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlkkglr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyopgqu.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rgynckdl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nadotvgv.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vnunesvq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqklyqax.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2sxeomipu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2pawboplg.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhfzing.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnxabeq.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbnlife.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2gijtcbko.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvwszxw.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnffgyxx.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2elhvetjs.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2apwdjpxh.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqlpcfb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwvlhqn.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2equrttya.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2npggxrzs.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2btjtcqig.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2eekieoiq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlznkzg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2inwcbzjv.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkkttvc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqltftsr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxodrhf.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjzgjqb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvozqgbz.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvrmeok.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuxmxdc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzwtefp.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhsfshf.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqbohdh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xflwasdt.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbvohda.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzwtidh.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcnytdg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxdvtff.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2kzldxtir.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbbxwjd.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2huxrvqhk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2igonoigx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2unajnaya.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmbdhcp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhxyzxm.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xwynqoxl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2hitvmrgd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmbalgy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dswtayzm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lsydevwr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2cewwbzmu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zecggvoh.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgickfv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2swimaylj.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdrbwmt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdmvjmn.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kefhmtel.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbuwkwtj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxfdiki.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcuetgw.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2azunkjkp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2clbluvce.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfglefx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxwsdix.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2okibcgkb.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ugagnnsx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpcrulw.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqinqzd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kcztosvs.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrazwia.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jknlydhd.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoarfmd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzddlodz.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2psbteauw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2inbabjyh.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkmqnwc.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvehwnm.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmsgfog.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hacztnin.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwtuyki.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdidgqs.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2smfbqrpr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2enxmawry.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2omjfghlj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aukndovy.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjpbfls.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvszagu.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsfejzz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2frqgkyvx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zeefazyf.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2izlzasdb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2geqbyqmv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2grzhgaeu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzsiqxa.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ajenpuqo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwjyacg.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjepvhm.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2zefdegxd.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmebbgu.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfpswbt.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqqpite.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2pffanbbi.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2rhytosmt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkcsamp.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2eyckxloa.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gexrsasa.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2geqxwhud.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2qalvrhye.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2nibgdgco.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrgwhrn.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2daqlface.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxsgavo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxybetq.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2udleutpa.html


<!-- 参考信息 -->