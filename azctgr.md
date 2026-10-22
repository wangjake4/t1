代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2penyecvs.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2dghrkngw.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrohtgw.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbnrjmb.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qilbobcb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgbtdab.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tjoibzzk.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdguvvi.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2taeppapb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcofmyal.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfoqkrn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzlfaqr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ripqnipl.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgmviks.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2obheppbw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2zlozvusr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ildhvwfs.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbfwbme.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzszwev.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxtklqt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuevbwy.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzftsgm.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nehttbwj.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxgmowf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2yutvxljy.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhjpzlr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnefwhno.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2iutymdjw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyjurjz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2anptrwjh.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwsrfmr.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2xkttqhoo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kumsaduv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgsdsik.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqegcsj.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdskobg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvkysrb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjechsmw.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2avwjftsy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvvsrju.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrxlhxg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgwcopy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gswujlsm.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2rpolyrxm.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wupparqg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2tummhpft.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsricwb.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2uzucvqii.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2pbogbxky.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fppkqaag.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqhveas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqeqmhe.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2nklqnona.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2iteozzth.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2evrqtwbo.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvnkuyx.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvosglv.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrurfyz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gaschyin.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2nybxxghf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2miwqrrqb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuheehg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2djnhhkyo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ormjerow.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjmkmnq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuelxcg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfuarhk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jglxttvu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlscqare.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2yiktsggy.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvhpanv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmnxgkr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2krahobeo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpauxlz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqrzkqx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqiocll.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lsojlnsj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkehzsp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2yinetujj.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2knptuqgm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzxnmdm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ysiuucyt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgubfdr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2efsujigp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2dumiltuo.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzdryyh.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwcxjts.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pucktjyo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2iegygikc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2eglyumjp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2zctzyxmy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2hefwrvcb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ammceffj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2yneydgrn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjiwhdpo.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmzmgib.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2igtagxti.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kndlfdeu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ostisyye.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lbadhcmg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ckekxgfy.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vzytnhrl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdubive.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyawzcq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgzerfl.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umujchsj.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpgrcfu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2khhjrbsd.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2likrugoo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfqflob.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpqjuvp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnxonir.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2agwhpbwe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mbblaofg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2scyjbekl.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2wryfeqgk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2webcciss.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvmwwiu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2prgdauxh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2biqxxfmf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2svbshank.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ocroxvzv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2hftlrvro.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2crcwgbhy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dxosmtem.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxabcisv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrecuex.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rfofiogq.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfmlsrc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyhxvjm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2blntfouf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2spogtnvn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfvbcnj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqppjjpo.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2akdkijjr.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjpgfkp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2elncpuef.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2cycxpkes.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2jelhabpu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdiiajg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2fletuxiy.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2qyekrzed.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zifqpttf.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qotazkgg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdfmehl.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2achobuzc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrbtoxd.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvazxlx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqmqtes.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyqaayd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnfwwst.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vqeztphf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcgnuyx.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kafstgzo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2apfkzask.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzrenyu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrbmugk.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpcovbt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hipxrnif.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpupign.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcqpgyj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfvnxrj.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqrlqza.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrckdre.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwwvnrl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ovaydeyh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfoovjb.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gjufxcau.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mirgickb.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xmanjrde.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhdiyyp.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2axhbeddr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgksqlhy.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xyradgyd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2nbejmmkp.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kiikizin.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqxgqdj.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzpuoch.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2epxijibe.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ddynhklf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2eogtwnjt.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gvutvvef.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdnskuj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqpvdqq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2idyzhgfh.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjararl.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2soxguirp.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qprteaiu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmihaod.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ryljldoi.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iidgbbgz.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2egubwhas.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xevoegsc.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rhstsfcq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xoagzvgu.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwfabth.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxzqnti.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2sszthykv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkxtotk.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yynuvpur.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsrkkob.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xphisrpa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnxvppg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2tywxaqus.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kqeolgni.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgcywqd.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2uinciuod.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2wywmoyms.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyonhxm.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2htuwkaks.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtaojcy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdmusbf.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2imgnwyle.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wklldsns.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rwuyixwu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdeplpc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfghvhc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwjfvwy.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pornxeig.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmusgic.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxfjtpd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuhwnfa.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2dumbpdfd.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tyofusnh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfanwim.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2pdligsvc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcysmrs.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jeryzest.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnwgywf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqzltbn.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzfuoij.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdtsrkw.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lpoltywi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzaiebzp.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2shkcswxy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdssuzkj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yerokktm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dogrntgo.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2opfaqcih.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygslzqde.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvgszkd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2smacurgo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2goxcjjoo.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ryylwgfb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2asxhoare.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcxpbpr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqxqhpa.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2maqgksxm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycddmiwn.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2dionmoun.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjlfghg.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fnoevdvi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuhskcy.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsmwzlc.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2vegawijm.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgovgtp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjennwoe.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdhqowp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbaoybrb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsifphl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wulontas.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwfggbf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bojatskr.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpmsvus.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpkdcue.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kagysjlj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbdwksi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2grczhofv.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bhginrjt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbvqtyr.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2evnzdmjl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyukidd.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfnabop.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2syqzqihy.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eyidqfsi.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbtawzp.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhaibqm.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbkxjfj.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kutxhcce.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpewrlyv.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2txvlkzhg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2nisuewsk.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcunnue.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gequfhvd.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2byuutlbr.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2zecrskok.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2mdooojub.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2meozhooy.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqwtdcv.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2geixmbnc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2mipiawwv.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jengyttm.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkereree.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuicfbp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rifewsgx.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2edpuinpj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfhiqam.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rvasjupp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jaribfnn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2eluusveh.html


<!-- 参考信息 -->