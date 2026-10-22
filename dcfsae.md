代发 wailian999

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vphupkqb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmmfsnj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyatpex.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfivwfb.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uyluhtgj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvyczjk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2noyaeikg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2bpedpdmb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2qivdkmrf.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjyhjrh.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrgmdlb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2yisdxpcd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2llexpvjx.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjatysv.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbqvcyu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2trqcfrok.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqcmbau.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcojyqp.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqjxxkr.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbppfjc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ercdcivs.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzaveur.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqvwvqr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnmxcce.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2igbvlczj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2wyypwygn.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2baoxnblv.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2bcewhmbc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2njakhixn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2qftfppxg.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfceoole.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2znqcxlzd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzwhpeg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrpgtiw.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2swphruna.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rapqkudn.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxqlhgl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2lugkfqug.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxzclfy.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xfshqfmj.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpuphtu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2buzlndpi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbxfruo.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2iivxzeur.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2uczorype.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stlktqtw.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkcwumh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2podkxmmw.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zednmiif.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjtbmnu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ijffikqn.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qphzpggs.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwaiimhq.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwhbhgl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vkepxcjb.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxmjivb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnenlgfo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2htitbwwb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2slucmhcn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcguewaf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2azchhicb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2nodrywed.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2czlaoitj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmxnwhn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tslkfeyh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2cdisfcgt.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlxmvem.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqmnvfz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlijnwa.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2clfrmxym.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqypxci.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kumjfudj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzbcswy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mctlqxxf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pahrylzv.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtziikn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2gqevqysl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2aijzqtfw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsgycyr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcjildz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmgpjlv.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjhwesq.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqyaezb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbmpbom.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2saaydlmv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2evnmegtk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2mklkyngs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2hidtgohp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sikfxlmb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpcfyld.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xomapbsl.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2xepxijho.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2jkeiexiy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcztwqjf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2iazxfqzy.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fblijlfv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlxtrmw.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzchpxn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dbguxmxn.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oztnbgrs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2owirowrh.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfggtag.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbjdlbm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2rigepbbl.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqspbpa.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbkpwbl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwqavrd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmvrlgb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzivfcn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vghhhzxh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2czudniwo.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2vthidquh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpuerlk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyiveagr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2xonbjnmk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnplqxnk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpewrit.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqzjuaz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxgetfo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2oaglkwnq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdtmcjg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2vznisqsi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xupnkkmr.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2spqajgat.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2lsohcshu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bgomhgpz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2iukhjllb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ugincisu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlviuzs.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzojgmcm.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2jruafvzo.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2gefgewwy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2eaamsozx.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlntdel.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2merjfaya.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcytinzc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zytltfad.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqbabav.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvboeyja.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqseyxo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsiayij.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2xikklydr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkrivia.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvhalav.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmlykcf.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmdjqqg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxsyduz.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2elrqvviq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzspuxg.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2leoktoke.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkwjwxj.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlqjgon.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjnqvti.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpaeyjb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmtomzi.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2neldcevi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgjhfpo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2mgigemqf.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ellwommv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2oqudbcuq.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2emwjwymo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2oriieclv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2cugqgfvh.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbwwxid.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhymnll.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwhevyr.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjupixz.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fuiwclha.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpacfnpm.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzbhoch.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqpzvyv.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhtsgih.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuthmdq.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpswjnk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvsceuv.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vcibvtqg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cixhmdcn.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gaaxrbqp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2iikzhvkw.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvfybfq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqfyvdm.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxzxlul.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2drytzlcj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2doscqbdx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2nxeavmeh.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2neoujlpp.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xeghhjpd.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wydywyyy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrxihbs.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnvgeqd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyciqmfk.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyuwxkf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnlqvup.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfpcwrg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2krsmvsxp.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdgnnzs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2scskenab.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpxcvca.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbthwqd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2hixubzdk.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nwddrfwe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqghqmrl.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdkqatj.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2livubbix.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2cefhvtkk.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wccygrgd.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2erqtjgyh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zedvfnkh.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgvtrza.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdqfiok.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2omndrxom.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyysdzf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykeodeyn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvputuz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqbrsdh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2aeiaoewu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjluuin.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2daaeitee.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzuypjm.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2edqfrrxs.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2bshezdzx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2eulyhehx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzuwzrp.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxnwbja.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjzoljc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlfidtf.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vjclczzw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2bixhfgqs.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mirmzxln.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsljgeqf.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tennufvs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwsenna.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhtdble.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lclmxuen.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqhwgxb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxugoyk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2utbhvscb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2khgqrmrm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpwpavj.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lopdtuet.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyjzqnx.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kawfqirk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2okmsoqcv.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rjafvolb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qafyraec.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2zpebmjre.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnzuawg.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcxelwu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlnraiy.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2yffriceg.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2bacbhbxl.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdttfri.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2numfuycc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxnfubi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2arcdhdts.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nxakijpp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kueeqmqn.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2faklsjrv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrckkkxc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2rjybzwky.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2berexwyc.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dbujibbn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpvnwij.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjcxrpk.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2uibbvhla.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmtuiji.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2tenepfki.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohebrugu.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvxrqwj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2jukckohg.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2npetuddr.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvsgzkf.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tntzxbhn.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xahtnsvs.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsborll.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlzpvrc.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvfuiqa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2wotkxnue.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhhozgo.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnvxrjx.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmhkicg.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqlgydc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2rcicfnks.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqgkydt.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdsamsz.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvsgzir.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2dunvmxdh.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hjymliet.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iefqqbgw.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvwaufw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmtowqx.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2prcrpskr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgptlqi.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jnapxlrs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqgjlmc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgvrquw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nymrfinx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhtypqt.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsdepqd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuppwlh.html


<!-- 参考信息 -->