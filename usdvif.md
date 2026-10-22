代发 wailian999

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqcymwk.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwnctpj.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcaqnia.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlqdpvg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ayezqkdu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpyerzb.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqloohq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2izmenffi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pybmbmfp.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfaixvdb.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2soggbgtf.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpzcqak.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2oggpjgzm.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmoezcz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bswitexa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2flyzynmh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfnfnmg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2srzoynql.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkiexgrj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmbfrqd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2sscdixyo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2khvwimzo.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyqtcml.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2srhbwisi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2joibrfnf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjtpury.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhctqxit.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mybqkcwv.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlhxklx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvgvhro.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjzzprh.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vflyyaij.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2gswbxpru.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2oepabrxb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnocvpo.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsokubs.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzykwte.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwfoimk.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcgsmat.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgryivu.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2pewhejev.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkraklm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkgkkbq.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2brkilwne.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcozvnx.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfjfqzr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsjryxm.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqlxfbv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uepmxezl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2barqutyc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxqqnyh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxnyvsn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2opktgcjh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzxrwhm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2anhfnvyk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sskjqsuy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwseapof.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2futxiexx.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2emnlphyn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpvwhnx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2imdbsuaj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uduitcgx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnavbyt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2usvvofax.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhjfcbj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuebiwr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2uypaikfp.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxiuzmz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2plbusmuj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgbqmqm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrfmvpj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vjubqttx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpnvujl.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2tddkhmwm.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2dokmauhq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdljgpi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxfoqha.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwlcppq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2gocjgpdd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2fiflkdex.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwbcxme.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgriuja.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooutxlrf.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2srqseiel.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2vjazqfsr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hjezxyof.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvtvkkh.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfklxau.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2khuqhurb.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2itrmpjdf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmtmlau.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqatgol.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2norulvze.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slsbbxsi.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmbbols.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfftyjq.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnqeewx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcmdmon.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdxejbf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uikohaio.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2etojsrem.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2abfprvtb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvrxasy.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2sseugokl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wujyaxkn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tylrcelj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsohvnr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxsfqgj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xghspisq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2sxecrzrx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrysnnqe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfvnktw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2masfkghr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgxzoku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xrodnmrr.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtmpafy.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2gqphyclu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2dplcgvjp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwlyqeg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhhjtvy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcmqicu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvuwnzw.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtboexa.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2salpjthc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuzypmy.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2temmrckb.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzhbzov.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiiqazba.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihewbunn.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfosotw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ialnngzv.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjvndar.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcmxjhb.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ksebmbfs.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkejream.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbttpak.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxuzsla.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2tzslxuaw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdoftdq.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2empbmolr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbvivlb.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2madudics.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnyrmsd.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ovajbidh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zlisgymj.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqfugwq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsuacnu.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdvemjp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhrhgqd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlvdawz.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnrpekv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2uztycfde.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2whbhjofm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2rhebntla.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqysgwgr.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2otdbgtch.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfhzujq.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwcwreg.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwdvwde.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrtvswk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpygrnu.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cafhtmiu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmiutnw.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iccbguik.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzbeuwe.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vernuvcp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnochjl.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2prcaeusv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2otyckjqr.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxtpyak.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2kasjuvfc.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcxufkd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyijoej.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gxurzslt.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dczytmxh.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhqeqlr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hcepzwcc.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kruchfwo.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iifrslqq.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwauied.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiznmpxq.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqwymtb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqogxnol.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2gnppkfgw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwcpdhh.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zquewqwm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctouyubl.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcedtkz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxosnlc.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwwwegr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2csgudsrh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2izugkxrq.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uskmsrpo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbombln.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfoyvdi.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuvltoi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2kkawbahy.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmflbxf.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtyrmpd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtxcjlq.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzhegag.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2luzpychs.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsdiqax.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2enecjoqy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdzodco.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciybwgnj.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhmfnki.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnhjffu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2svzuzynu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwbtoof.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2onoqjgxi.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2omhcpuso.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qlriviso.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzkcgnh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2curbbhea.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgsvgno.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjjmkyr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzciphgc.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fwojiicv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlodkfvk.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvatsbg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2krpmdrgo.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxiomtu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkkfgnw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nodxtsdl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2evqiboua.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbtpghj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrjwtau.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2twgvnbjo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2cydfplda.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fezfqcfw.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2oiaiherx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxojrlw.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mgajtezq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2amchjjvl.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nftafxbq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdtjcwc.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2qauzaqdo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqscrdsw.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pnruqkjw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2lvigylxf.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbgazor.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxwzfws.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyqdivl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvglfpct.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxlzqru.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2olnwnhqx.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jxffsigw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmheimvd.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjoagpf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgwhnjx.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2upkfeimf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjhgmbl.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fttcboiq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zltjrlli.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnazkcuh.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2yafrkwuv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrsapbn.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgjelzg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2adxclbkv.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzxsjwm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaczbcd.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dgykdeqo.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtavrlb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2unxkuwig.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdpspag.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbbrqlc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrzhnzd.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2yueacgin.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfreljej.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2kwonuhui.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngckyrru.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxlojhl.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcnodsp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2tjufwjea.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrqrpem.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgoesayd.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hlipfhcw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2iigemvzr.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lorpmccd.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvhawyw.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjemvpa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wgibqdxy.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2oauwreer.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2mabddjoy.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwtrnok.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnwiqvq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmedlvr.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdeiznk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqeqgmgm.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgzvhgj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2cstwztyx.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2oopvuyrb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhuhfie.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2slnruggd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2gkabxqiu.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqbkvwg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nybpzgcg.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvwritb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2alvkbtne.html


<!-- 参考信息 -->