代发 wailian999

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gpaqnkje.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kehovfkd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lynnvdta.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxlcsch.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2skojbtdu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yngcvzdf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsqhfug.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlqtpbs.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2uryytimu.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyhembz.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2btciwkpg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdjnwon.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnychyz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwrhgvq.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkybflr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdylpxdz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsxgnod.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okqqfhon.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqpoueo.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2tldsolzm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2oqicgbbu.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmwvvae.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mubmmzmk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpniuur.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2oldujdpu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2nadkgkxh.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhtsxyq.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcswnby.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2orfvesqd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdeztlp.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cubupfvj.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnxifed.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrajllh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmkhbdz.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2trlfiniu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpvmiyz.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2blshlyfj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2raguunll.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pkimheff.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxxcsqn.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2onkilsvl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2twugvymk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzaaefc.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqdpxaw.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtmfoks.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2odansqtu.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjgrofk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuqhnda.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vchfnbnt.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2oluxhncf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2aapbjsra.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdckrve.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqqnrun.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2thafjalg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sgplmtlx.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2taotrrmc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpaxumfx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnyidgv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2dticyakl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2knpgxsqn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlquyda.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2cweomban.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpmswvp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pegetvxp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsatiljg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjmhgah.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyasuss.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2dolzblmt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2gykksbms.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsuuovzw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzahcfdd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwquarco.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbpvmfw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfxgldq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ahajiask.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrugzth.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfmkzks.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vdimrhvd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2easdabye.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwfavxm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtnhtkm.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqanyoaq.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wydlbymi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hbomihti.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkrqick.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwbsavx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsirqbu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnyabjf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eohcyyfq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2cniuydbu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeegyvwo.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2uuededoo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2luuyxyiy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqyflui.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2blgvkrrf.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyaaytx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2nsegwdlc.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyivddm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2etecwgbo.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyeirss.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpelasdp.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uggbppqf.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnycudm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2lngenivi.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kosgiwvz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjtrfxy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnutoae.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjmcgxz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2fvexzmdg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgbqvzh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuqfrgf.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqyqfqv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdwvwlu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwefmvrw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2otkkceje.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkynzqn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwpwhil.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2agsqkgkx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdptxhgk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbrymtf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcyamua.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlvgnih.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bexpigjz.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2mljmllyg.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtfliqy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2gqffhgpx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmjxmgu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2prnpbysr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrttmmm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuqusrk.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbsokpd.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxiynav.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuzflex.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqlicwg.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwhgjns.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzurfvn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2irwpapqi.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2kttbyfjm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zupwuhmw.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qslfgatm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqahvbln.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpxisay.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsopyei.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmgjitx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhnvvff.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2wiifhaoi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zemwkomv.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2halgzbrg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjjwwdu.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zddjanzc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bioiocjf.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2whjlplcq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrjnvad.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuylthy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwqdwwk.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2cryeindz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2bprgloqj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2cirlqpwi.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2naozoivt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgaafah.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxcpqcv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfvpedi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzolfso.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lxklcncl.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2usaqpoak.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrgmist.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2omjgvzfs.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2abhifqkt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2syhzkmnx.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2obhmmfjv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmbjmed.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ychylucw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwlwnme.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wngfwrfa.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2upwogmov.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbcbirg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lctmikef.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwsjfwf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2znjnqfqn.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2gffkjmql.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2urfoipia.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gytvurgy.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2drbwkojb.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkciulq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwvdsya.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfacugl.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjixcmy.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hsuwgocn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjkzeyg.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpdhtuk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2avzrpmcd.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xadvxkyr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvovpwhb.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rnaiwwva.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lymulwqx.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2liapxctc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsrjqkm.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hndzqjtg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrmpyaz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2zmuhhbuf.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpfkerk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfspcbwy.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxajirn.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlsmwwa.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqjysgq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxitncug.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aomtaqbu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2spqjpyxt.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pklawnjq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjrbreg.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvnbpkn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oewfuwcr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2xifajhyq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpkxliu.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtbkutn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbrllra.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnjocey.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2yheijjej.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgovfcy.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xufvpwgu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qwprfmct.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2odgydftt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nopikbvu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvkztfb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpdvpmf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjfuzgp.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zppivmvr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxfmpdp.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvachov.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhdjtno.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmgaggv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxriohe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzbsera.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2eaycdjke.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsflumk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2irccozly.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2azzrkmsl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrwpnoj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2uctbizul.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2oufyufgt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2eljfkkii.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2amosbdtj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhoyrxw.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hmujqitm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdjhxjy.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhnifkj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvefubqk.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzvhpst.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xeyhxmjc.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2biuilfgn.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2qserdhoc.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2chjlzreg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrhqulq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2svfzztvb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpyxeli.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2inydimok.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2acmrawhs.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzsfllr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2edusyoah.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2jhljxbzo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkaoskl.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pdppgciu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqutfuu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjkmqzt.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2umedevxd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jirwhivs.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2acyatfbo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjhbllx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgfmcxz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2vmozbams.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rtidvkkg.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2danxgwju.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqqsydd.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2yeoijioz.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdpmkil.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmuksffq.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ophekqyq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdlxcnl.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlhumhn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxjcqmy.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgmcvkq.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2alawmisq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2oilfyfij.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2kiabvlvu.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2leivrjal.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qicdmpoz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2npdrsyto.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxmzgit.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kupylnen.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdeegje.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2altqcunh.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2flfypyjn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxpczdq.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqwdxwh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yupmfezn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2jaeqtdeo.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qextdxmz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuakrfkg.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlwpqyf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2dfohagpn.html


<!-- 参考信息 -->