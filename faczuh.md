代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtozcmil.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2lthoqesg.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbaqdke.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfqxjzw.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwzyqmk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmgrmsj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhjtwux.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyfzasx.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2itdwjyay.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2srmjlkjn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2jazhazhs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2inmdtozb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2dngxkdgh.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlggdnt.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjwyqrw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnecyan.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2spdssesf.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2glejhxor.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2deautrnn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgwdwod.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvsedbb.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyhorbp.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fujggzli.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzeripv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2xscpxqiv.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzmbmot.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kedbaqer.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zkafjaxv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmqkcmz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpgsysg.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2inztqadt.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2acxfxfyf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvncauy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjmfagv.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyskink.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpecqhkj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgegvise.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxaaurez.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygaanozt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eskoaztg.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbicnwe.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2typbuuvh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eiypajdk.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjczumo.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxnvfsz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpcajvx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzecchv.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnhngzk.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2dtumubuy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ypybiajv.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2splwnhep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2quffqzbm.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fociijko.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ybksjdbc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqkdlxk.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lccwucyv.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgnntke.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnemgyug.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2niozzoam.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xntxmlsx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uycxndce.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdxqscy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2stpcijjh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyzhgkj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhyegiq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlprfzr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zygrflha.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ynelkckw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2samgizdr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2wcomoqrz.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrqxryw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2roulpqok.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsssftwx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2naixsfgz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjazamn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vekbpohp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2gaiyysdh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjjjptx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ncehrfsh.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kpysjgkc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2idisptda.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhewsiy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkefxmu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfmtxfs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2cktxtsbt.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvhfsvy.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2psbkdjjl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxgyylw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbqafig.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lujlxwfx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2tqacxdnr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2xltjorfr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bazxhzyv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2damivfar.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpkbpdl.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2kycuvbon.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2xugnsumb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsarcqp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgtsylw.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytecllkj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2odynkgxa.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2telzvpxp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlfetff.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpljoavq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwhhpnc.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvlvtnz.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcaatii.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrbyani.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eszgoyls.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ktypzwep.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dltrggcu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyczkui.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2eamtvnmz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxjwhrb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpdgfik.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrrouaf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yctzxmgj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqnfwhp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2plfdcyvz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwbphzd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2hriehgtt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2idjrmdyz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2adslekud.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2jddltkcl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eoorvean.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjszhhd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2foqyonvk.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwodsvq.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbszpkq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmhbstm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2raysmiwo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzwuoum.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcwnxty.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsbmeqe.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkrbjzv.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrutxog.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvdxqti.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rkeydudf.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbljgbs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2gikedjey.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkcfmrp.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmaktun.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2shrmeiju.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yveozlgv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqtxvmy.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2pbaypuaw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwbemmb.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqjnxip.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvqbnzp.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrsxgfm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwvvena.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ihesuoff.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxqvvrw.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtqhnis.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2epmilyao.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hzujswpw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsmfyoy.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2mheoogex.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2uobjzots.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnwnksi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmvfsjt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcnaalk.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2utffgboi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2owoqkupd.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2grwfnnad.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2zevvufie.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnwaiwz.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2olkyegcj.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsscngyc.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2msvvaklf.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uruvvvnr.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tizpzfiu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtonopr.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iegtyvbs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ceoywwaf.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvttihx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjipdjy.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdjbhmp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcnrxny.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2brdkkozd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bulpdrll.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2afxwkugd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmowbjr.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzwlxss.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtyhpna.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gcusljbs.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2odujqolm.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vftncyca.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdwouzh.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuzdjbm.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjpeovm.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdtnnvt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpjnepa.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2odnaapjr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbivtlv.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2blvgirww.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2phiylgxd.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgbupdk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrgjlzd.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oskicniu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2prbebtem.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2goesbqqp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfufhtf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgrqkmd.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhvnqoa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2grcspwnv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2enpkcybk.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2fbklhuns.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzjllly.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhqctjs.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pncnnxsp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2obforlyh.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rcldetbm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmxekbn.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnaspwz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwazjmhz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwcohhr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhiiftyi.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdevsst.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlholrq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcghhytf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2vlecxkty.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyjwsai.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrpvnjc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ghimyuyn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrjaiay.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqpmfzi.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fcysuwom.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2skykocrd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugptfemn.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyaobrc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2srpirtsd.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnjvrol.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxowjggl.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjnypia.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruynexxi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgqgatx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvzndgg.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzmvtlo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzagylpl.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fccanyka.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmibvfm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyycfii.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdccnwe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltogewyb.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqyrggq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqcrjxg.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxnwjdh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mctfnixr.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2akkaomqd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2weglpvgc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cabbnipc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rccolxkt.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2njjhcwua.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2odgpmcou.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmlvtkt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzgxyno.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2urmwdogi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcphovvn.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2oqiciprp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsumnqy.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xabncklu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpgalef.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmykilt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaogidxk.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjonilb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2anviiqum.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2naksoynu.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wapbcbqn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuovezi.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnrvtkk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cedakgvd.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yofcnpsc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgdfdjj.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dncktvwq.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2waifzcxj.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtrzhtq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrwlfyj.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfipvdd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdxewes.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmofdnt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjtaqel.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdhigjt.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yedeirsq.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sycnwmnd.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2tuupmvxd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2zomasghg.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnabbeu.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eltdzxgb.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjvdpxw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdalzft.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxcvtpk.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhgdwbk.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2rmoujrma.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2olxwyfpb.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hxftbyud.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2pibrutat.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zpeuvurz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pspllruf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2efilixxf.html


<!-- 参考信息 -->