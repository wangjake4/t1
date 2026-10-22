代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmjnski.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfdpyqo.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxnqoti.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcnbgvd.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2andecwua.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztudkqpw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsjckii.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2movhhfom.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvoqtsq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oydagypr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ghusseyl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2sakhypyb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2kssubbog.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2veqtanfr.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oddeqilr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrzcdfm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2xsiyhlei.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dflwlfoh.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfjvfel.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqphblb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvqzbto.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhiiwrl.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpoghzy.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkbwsgc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpucjws.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kurymchs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnofvcpk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxmisnj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqkysvi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2dannbgvx.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjwamis.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2pezoiiqg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfdlusa.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyeeobv.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2axolfhhv.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsaiukg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnipxuk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsmhmsf.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdafbsxz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubawbnbv.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2firxhpzf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2amyolrjy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqbqvbg.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dojmlwyp.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2axheduzu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2enpiblye.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2dviaslgi.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2smlyuaiv.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2mucwregk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqiozvq.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxwaguu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mduajnrt.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2imzauaqt.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2qikxvsok.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxmncsz.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvfqrjp.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wknbtisz.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qomzoukv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uitqnetj.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsavisq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxyexpr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2hpruqtoa.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2flvgzerk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqshgijt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2shqcpqsz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqfxqms.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgqobhk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2knbspbiq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqboqnqk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2keulfeiq.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdzuhei.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtevhtz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2uissuwqc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2niwnsyvw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zidcicnc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vphycmke.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ighgnoca.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2azgrazrj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2udhxtwgy.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxkgybr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlvqewp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vuemvyue.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jizuuzvy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdcftsl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhcbpdq.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxqqtij.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2knohizgo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2aniafumt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsbclys.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wytoldha.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzxbzes.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlveqna.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxzomwk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2gcofrnti.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2odesyigw.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2aputsmhy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqhfqgs.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxeumhf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2tzreetvh.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrebqox.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2byoxiumk.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljczuesr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ycltbzss.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgmkyzy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrqfpqy.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvuxejf.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xkglrhhc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzzddpi.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2toyiomhy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfwxgnf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eygcelfy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrxflhe.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2lenebxkp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dcujuawy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jooaawtr.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2gezuwuqm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2amvckbtu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bczcjpca.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbqycaz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwyaeyi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2kfduzkfk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgzgjlo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2dznnxcme.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnhjpwq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tvroblaq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuvives.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2maqxivnk.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2lshwrdfg.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrerndu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rwyrerfe.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwzpqui.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhupjri.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjnxywe.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqudldv.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbtigmu.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2npztmmka.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmaafyu.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2trxlofte.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2wdukcksw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2gayetigv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2uodjwnla.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2xsimtpgm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fflybotz.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbhedwo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zptenwor.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2wzecvrjg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqkceaz.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2atflqhdf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffonqcwb.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2djozaaba.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tezxprjn.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyorqiv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjaktizo.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tglagyll.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2opzmumdi.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2opmeirqz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnumwao.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2svtmacmr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sibvsfhm.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2obhtozga.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwhamtl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcnrtbn.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqvdyhc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzluult.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxssogki.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbqkxio.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckopbxrt.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xirkfaha.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbahnsk.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkifsme.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2swfabxah.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqgcfoy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkeyhpr.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jojashha.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2kteakrkd.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xgftilgz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2edusengf.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhisygy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nltvqmyc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2apdyosbb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlczyfix.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yemzdorf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfdyqjw.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2uulfxvjf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmeqnyls.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qfprtmwz.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgiharp.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hblhkpqf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2banwcawv.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqepueo.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkhtvns.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xmavrpyp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjcdfsa.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpniefw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2udkdbwtj.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vbulamgd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2stvqgpyg.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rruytjdh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zczyikyk.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqfwihi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iumnyjpm.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxoxwel.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmgnvph.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqzypdu.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bafxsizr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhedmra.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdssbbi.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxflbsc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcxxzgo.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtkzjvk.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2quhsyeee.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2itllvhjm.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2luuspunz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhigaqbm.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmhvaso.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2paxqzzwp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpvtoax.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xggjiyjy.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyvzksj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjwogta.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhxaosh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2cuabmekd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2axoomnlx.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2btyvvtnk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ymotvwgj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2cptclpqc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aycadcdg.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfurkyv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2plauhtjq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2swbpsvsl.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbzxzwr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxyillw.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zecayjeb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdwruxo.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eymhafln.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2psjjsyud.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jflfnamm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrpvazt.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdfgdob.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrlvivo.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sarqevcq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlllqkwj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2shbfhcmc.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2oipxuxho.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ottorsre.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2opmbcjxv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2flgbpbyg.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgaeufn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmyzxqt.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwfwxml.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xonryenu.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qqalntct.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2poeodgml.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2adzkvkdz.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcoqhxkx.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqnbtus.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyiufhd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jflqkfkw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dglxlclv.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vomgcurw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2emjkvyky.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2iijktqax.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcydjgn.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrhcmce.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2klhjscry.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fnskldxx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2jeodejkx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2owknhcji.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2naseujjr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpnnjde.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkqjhza.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2knglprhv.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2obvjuycq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2awnpeqeh.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zwborvdh.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2qymehnvy.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkcrlui.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqqkfps.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lprglqhl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2suaxciyh.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2wduqfjdm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvxcaht.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2qdotonij.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2todcxhrk.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2weblhdps.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwchlza.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlqudfh.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2npwadxpl.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbluiilg.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2fcluoydt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2hipzvexf.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zdefvjwq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwinqtyr.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2zaomvgwb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyshzji.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hgiolzrt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2zzadtwlk.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxjuoxa.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsuqkeo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2cnievcvp.html


<!-- 参考信息 -->