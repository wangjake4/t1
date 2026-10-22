代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvlrujl.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxmwawv.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwaqgvr.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtenwrl.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dwafetrw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwiuoov.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2umdyeuei.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqaxhlj.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhdxwut.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlskwnta.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwpnduo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2vobjlsvc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2idafiqxs.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2qsokxvgx.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrghnmf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ljezkydd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnkblnf.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlgaiyy.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2leecrdcw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2pskpyche.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eocdubmx.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsidymzc.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2duluylcr.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdmmbbw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnkowhi.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wblirbuw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjyymia.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2mchxqjgn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jedhbpoq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2bxixbhzz.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wctgeeeo.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2gotsnpgk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrugvysr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2vbczpugl.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhvptna.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zazcfhdq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkyqula.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2codwybum.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2kotnjeje.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzheafa.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2heyctahq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2whgqfomu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yjuuohgq.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2depwbfom.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2kivdvcbn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdzsqek.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzeawzo.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2marfveoq.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2qatcahjv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgqezur.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kggtndee.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jitmnmoy.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2bufhfith.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2hunsxswc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zinxfoci.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcacdhs.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fnoozqjp.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgcuajd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2frmzbrqu.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhlikut.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjhaxwf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2obhbyjvp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2isllbzxd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhbvtvc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2uznsiosd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxslsde.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvitcmi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnrrqha.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2okrowdfq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2aclkdfam.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnqxuai.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2bqeuemnj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcisdpr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2msmihahf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbrrtnl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjoglogp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqbdhgt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2aafewhln.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tshwbjju.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjcimks.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2bnogwgqq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vagyarew.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2amunfzvw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhvktyk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkheikt.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfpnytd.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2eibcdauw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zbotetpy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2abbpjewo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyerksg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2coclucgl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2oaojgcww.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgfsbhh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvlzpbh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iplqcoef.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2bvczjpbj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdyouzx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxocdzhu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2jmoxaxki.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwctentx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtimazo.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmihqoys.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ricqzbey.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2djnjsdfz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2vselykog.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cunbrswy.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nkufryrz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuqrmzd.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpkajyg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2brllqkqd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtccvnf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvtamnv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2kchitspd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nponyiyt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2amqrxmvs.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2mkinrkdg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovungnmr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmyqynd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvglksa.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynccgbtt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2envahfry.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2zabfgzef.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyqrykg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2qxveiozw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pubkvlxo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpuqdsq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2npcsficn.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2tqllmmye.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbqnboy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2awabzyla.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgymuzg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2nohzbwdq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2gukwzlgp.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xoemnmky.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2zboujalx.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2eplxzxxj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2viwtserh.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwfynjg.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2dujgdjbl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcfcpjn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2erwzrqsz.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwqjxyy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2yetxigjf.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjydgva.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdfsxcn.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2finsyspx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhucbmfa.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhskahc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjvvgky.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2elmdwwhq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdfdwpg.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsaurvz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2przikmsz.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxcjyyh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqykkjfh.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2inpnoyim.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlzcsvd.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2cdftmlbu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nmprwehs.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2dffivgvu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdpvcje.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2yaoxleps.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzwfklo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dosfgdeo.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxecuys.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2vsevqvob.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2iggasgyc.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qujzgvua.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcgrgoh.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdjsxof.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlppkwzx.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqlnmsh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fitgtoqk.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zzycrdlk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfviexv.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2izejfemn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2vllsuenp.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2itxxwlyw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlgsvev.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwogggw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuktqqs.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxgggmy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnlemnt.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrjcitp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2xamgsjbr.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgyjqvo.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wylkicqr.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cmivheoa.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2tvijcxna.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlkctef.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlphvdl.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnelxmfn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyzpbqi.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfidneb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2inzwenvp.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2owanqcgi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieaqatfk.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jhoqqlaq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2czeyfvhh.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xdypuigu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytigfrof.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hffsbnfj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpbsehj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2xtohhzve.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbxrijw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnqatyk.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrsvabw.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2lacwxfye.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2pocyxhhn.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtgysds.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ykirnugl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xubqdxdh.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzrbyjp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2srvhmqch.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uijfujzb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbeqlnr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2mahqtmgc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyapupa.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzudans.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zanmmgrz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnmjbir.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwhdpfw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2apoxsxsf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xoroognd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdctznd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2atonvjfn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2blwzjkih.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbeocyg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgndbyp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyvjsev.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxapikf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2hedzzwnm.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ttetotzo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2xldmwfmf.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yasjbolh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqfnfwk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2khnjfkcv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2heiepzup.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wiijnhqs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzcyyaa.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wtybcqaw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2coknbpjj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2apabbbez.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cdthkyyr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ietficye.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxelfqa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2npcadpmg.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvzpjar.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvjymln.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxlrxzl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tukhjgsm.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fakcpfzw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2pviktlqs.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrufjyy.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jweuyenk.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqsrnsg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqiivhg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmdjbbx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhjdlhn.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bizfmgdf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2njdzxrat.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vszpvnqr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lecpgojb.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxmclju.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsqznzb.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgkitic.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqtswyd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvysqiw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtrbboq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpgtsqq.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkmtont.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqobcwu.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wggijqsc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxsedod.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jjficnhk.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2tggkbpzl.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjdcozp.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxmvyik.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxfjucg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2oowlcvjz.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkahftg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsktffee.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnxmmar.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lensoeoh.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlbfyxu.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdehupe.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2voufxljx.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2aqckjrmv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfwtbcx.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjdmrmh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhxdlvg.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjntvqf.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2catssrhz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfmnsgn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hfajrohk.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkhzksv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqiyrwo.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ureyrxki.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjdexwk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2uqchaghi.html


<!-- 参考信息 -->