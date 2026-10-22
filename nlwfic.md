代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwjklmo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rnojbryn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqhytqo.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxlfwub.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2lcygzsqh.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxlrjlu.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvlnnnk.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2awmqlirl.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pisgbvex.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqamlqe.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2owmtsvwf.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvntbuj.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqdrwut.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfrrrqg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkcevjk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2mfewfvvs.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2thnbumir.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbvfoni.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2awwzdemx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdqfdmu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2cywxgvmk.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2haqwmsea.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enazdmvx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2phgjcdjn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2odkameet.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxddatk.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuqrluo.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2cshnwmpg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnizbum.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2obgisewm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxteimv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2inyzvglq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuthcpv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtimaod.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzextft.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2mertjzko.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2klquxbci.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2svcfvqgs.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjumuof.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wizollhf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2uolrnlaa.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2peznoswm.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzxruzd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibejxcjg.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqdrtxu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2exhxcwgz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2duaazehd.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xwowgtft.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsvpawz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpmkjme.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtdebze.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbuuflc.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2shukobxq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkwvipm.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnllkioc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bddzjhdb.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbkevru.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ajojmcbr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jgphmnch.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2futighjs.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2aodxkmgq.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjhipnn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wajfyleg.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dovtlnbi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2irbvaipn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbftxnz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2brxebwco.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvogfghs.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnlhfxz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2duwpqctl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqefmvk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tzawqowe.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxreqnut.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ybutjpcu.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmcugcc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2nuojyfgv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukznzdja.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2eaputban.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtmwslo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzkigif.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2atdpqqrd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ileockdk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qqiftyud.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mbleedhx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcwdgfx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vdabxwyi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkcebbf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2udtjfkok.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkiagutr.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2sebmfper.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2upawoedn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlcuqjd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrraizh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdudnen.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2rypqcmjm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvokpux.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfoesljj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzbssfe.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfafhalu.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2cldwldcb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcxxfbp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnyekin.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnqdfwj.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrldasw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2phvieamz.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vzciraar.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sohgqvqg.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdaygocn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2yazqjyjt.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nybottob.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qstwrsvn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2orfsrngr.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2piupacyv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ngglryin.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qviregdl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvvvycv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2dypfgpah.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfhoabm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsjcrxu.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2snuktzuz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2muemkqxc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xshmywyj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhokozo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkivres.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2mtppnixz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhgemce.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2fetxjrsm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjbhjfy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvsmogj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnuzenh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkoeoou.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2revdebkv.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ubloyide.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbrfkil.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2dssjiuey.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2oahpmvmh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2gswzneau.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzhkxvz.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2gdaxtcwx.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvaayvt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2cnamemnm.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpwqpxq.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbmqpzm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2biudzyvd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2fouxjnhr.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2sgerdjfy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tapxluwn.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwzcaxu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcjayjs.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2opnqlomz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2skmpyyfa.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2knxkabwc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpafinz.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxubduz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2weadenwh.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bwemuimd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgtictm.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzviwkp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzwfydn.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fseotypx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnknldw.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvfszvu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pknvoqex.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2udgutnyv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2powaucmv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrsijxy.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjdzcqt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ikntuibw.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhjwvgs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2zundgerj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2gubhelmg.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrvxofu.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvthsuu.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgwyejv.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2riuupatd.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ykunetiw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwlmrlv.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmlehif.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2wsotalmj.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lhreyhqt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2srgjfnuz.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrqauuu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzgdvnk.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bqukmiug.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2isieangh.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zoupsuym.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiimexuf.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxmrdmk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvgcrgw.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjqxyjf.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxhlbrf.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwlmcnz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsofqza.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqsffbu.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvzjmma.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mevjrnbf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpypwdhf.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2joqrhdrp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcuyfnm.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2cykwnubh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tupstysi.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpvxdja.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2oudvqrgz.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsuhhqe.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtqfydc.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzmhgin.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgotsmuw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2sraqjhih.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uexlwaek.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2euwyhgte.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmtzjzt.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrkqpta.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2utwdasfo.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqmivtv.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kskgyytv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yviltuqs.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qysckkve.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvnmxrc.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjkuzpp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybugsfoh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2awbiixgm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2atkvabrc.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2uctpxffp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2aglngwvw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nppulikc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2prmkyydc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2elytghzs.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2donlmxdh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuhyymd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2szzvhxvd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsitqzk.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ylklqwej.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmgiwsg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jihgjppk.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2enckdigf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2oswmudhd.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tzemygsi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2hszoomrs.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dyelxoer.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2siiwrtmk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwrtpee.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfsxnvc.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbrblgd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtshblg.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ezessmtc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkdctag.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hywrftwf.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gbovwaye.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbhvjcz.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfptioi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2oavgetsl.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgcroez.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rseahtce.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwnfiuu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfijcmh.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lzogabyk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jaeqkoqi.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2lofyahfp.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2afnzraat.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2auvcqdfr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgjnoae.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjyhwiu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsepfax.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yfueiqaw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2idejwaeg.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgzkcnl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2janvsisd.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2spdqkeht.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2earzkwff.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvqqaow.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkufzpk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuigitdv.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bwytoypc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2obbxsloh.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdecsji.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysefbndo.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzllmyy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfqztxy.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsppilp.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2owicljzy.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hpiciexu.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2otfkkils.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqftuby.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziikxodg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2livfcykg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ageylvri.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkcxnto.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcarqfy.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtpftsi.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2xixarghb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2toswznzf.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcdjmnt.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmklvei.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2inzcnvli.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgcttkb.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgqyowc.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvxluux.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2trfljtej.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwaxpgg.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtdmefd.html


<!-- 参考信息 -->