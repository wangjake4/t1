代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzeimpw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2heqkbmge.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2crqvbtec.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2awojhbdl.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxqmnzb.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzkncbx.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyprmtjb.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyklpjb.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhxanuc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrwmnmh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvonjxt.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rtoqcogn.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jragdkne.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxcfrjk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ajldfylt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2muimuzwk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhbyzpq.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwrvywr.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xaernuuf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2mqoxgifz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjvzhls.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vefmpsmr.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxetuqg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfphdew.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gddekuci.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aibckuse.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kgskjxkb.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2stzgkicm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2stdpagty.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2spmdakyo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkbwbpz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rdndkphl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ituudnfz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2njgmzqwt.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2umjpkyco.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2cdeocvuu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2affccnqo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfqzolp.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hitltsyj.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvylwxlh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsybmwh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttehgvgw.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbsgcrn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkfptqg.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwsdcmt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrkcbyy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmmcnzt.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrzmped.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2asqdvbij.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2srubkroj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgpaopu.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2virywhol.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrcwgzd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2spgeeqwp.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ydypamtr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxpnaeb.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlamgxq.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqoqjgf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbwphsx.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2yneooplt.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bslgkzgw.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mihblshp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxjegxz.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2nutqrudz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjabjwp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2sesbydco.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2rilgxxgm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzivdqd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuxhqaw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpookobj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2cznmtjfe.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlrkacn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrxdoap.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcpkqvl.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bziyoujp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzgxrcd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjclbri.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2igcfycxt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dddwkgea.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkjmnjn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrjsfny.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrwybug.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxavjyf.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2njiwjequ.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2xancydha.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hnazbfsu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2itntigpb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgimvzs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjzopaj.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2szuepoht.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2shdgcdig.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfzxzpi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2jylxzswo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpienfd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ljasmyvv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2emuzqqeb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjqkjwj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2orvmaqua.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwculqg.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcqkpkg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2yktjpfva.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnpnjlt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2czrrqyau.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdndsrwp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbrzqmz.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lszegfja.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwrsmeq.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhubacrg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwutnxy.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2barvvhbr.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2swpgsyyn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2pztwdtsr.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lbemmtvc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrdbnwy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kabusgpf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsuptbaf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzdmrdn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcxhqjh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkitgve.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2vjihyleu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxlaokb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjeihagx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2akwvoprx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvuysmn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyjrxph.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvrmrfd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2prydbfyn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdysmtv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2agrkswmb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2sobkqtxg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qihglwjk.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2uczegpfx.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlonzwg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2epqqqmms.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ojixwcwm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjmmmss.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2gepvlbkv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2txbldyey.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2oizagtju.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2bhozyeiq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnibslm.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwloknw.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlgnkod.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2eykyfczd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2znxllxdk.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcklikm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2muhsrldz.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dtonigxw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlnuwwu.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2hvoflfmk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgtmgsb.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2jttxyaih.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjemftg.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ghubjeij.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iygqtwis.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2altxaiad.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzpysku.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpzhycg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2kedkbeiy.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cklsfetq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgvwohp.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrymdaq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbgytky.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2jyevwrvs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2zwndcoyq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xodheqya.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2bukgzqbu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2oqucvjmt.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfodwgww.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2awynzihw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkgfcrp.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2iogvgloc.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxayhffj.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmegjey.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkeokvxe.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfpgpgt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdzdgmu.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2erdyskvg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2btkfktoq.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xbofjpnt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2yusuccnz.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxracpd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2icphlpta.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2goulnqin.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvrsayr.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxdwrjc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfrrxge.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2otzfmckc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkzhaml.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gpygnjqu.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nucyhibg.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cllixgdu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ropiohjo.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlvadze.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfokncdv.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2sggoxkea.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzxkaoe.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2uisvqfiu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfanoctu.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxblsnw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oigyiijh.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxqjmnd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzovqadz.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqchlnf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtuyqth.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwvdmwl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fojhtiaq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyabgks.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pnuuyaux.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcdyvru.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2szvhaegf.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2envvpjir.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2txlygxsz.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqltluzn.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtrkuva.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdhppyr.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tivptezg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zitujvzr.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2asxpkscn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmsprdw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntllojjm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2abtcjpal.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlabgzn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxewyif.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zitmavjt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhkhatu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tirlskuf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eakewjql.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2imzociin.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxevvdf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbwjduu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2baplpptq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fhieyowj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlhkawh.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcqtlwv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwntxkqp.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2drkagjkk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhismmq.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iahmhblr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxrtlzv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vyarytrf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrpoyku.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwwjizf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwexyhb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jateuvhr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2omgootcp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rznigbeh.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxsctwo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqlusie.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hagwqiab.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nljvkgpp.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxavgqw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrxxawy.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2jcukkeke.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qglbpbdj.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2whtwihpc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjchdcl.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwkhoea.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgozhthp.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nscypsjx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kngtybsj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzdxyjn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfypxpr.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2knkomcyu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2twmxbywg.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2asbwbziy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fptiijsn.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaezwjp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gksnmybk.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2afhsntfo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2jqofpayd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2adluhacx.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vglkgrzg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwkfunv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2osbqijlc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgezmfo.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqtiqio.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2flgvmltv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dacplcvu.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2texrykhb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjexdkv.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2zznrsidb.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fuchmrqh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkolwhb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgelcri.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2qorcvplf.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdxuara.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyxrllm.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xanhxppw.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzyxkdr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgpawmj.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkufxcx.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kckyqhfh.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xromgzpi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgylkuu.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tydkzacm.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvynzzf.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2uxazrkds.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wndthswm.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwexvhx.html


<!-- 参考信息 -->