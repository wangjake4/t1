代发 wailian999

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2usziggfh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dedywuqu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2blvadmes.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bztidyqq.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhzygzy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oexgqxqj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2rqegtsuz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwwpney.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2mrodiqis.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzwnbzc.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyxmgeb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2twtccito.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtyguxy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhxviar.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxjlcnx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzeuhamh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrtueep.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyufrof.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdnipom.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvyoeaq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjyfqiw.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2taqtwfbg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wllorlhv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2bdozugmb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpqjmwg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2savwlghf.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyzmgov.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2trqrvewn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdwaplg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxlpork.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdtyjxn.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhseolsw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcwbbfe.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgatzsm.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbrijvk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsmzozp.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcezwqx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ziljacgq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pdblgzpc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vaugbqpr.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2pvoryfol.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkuoibx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnhmvqh.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdiskrg.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2cycatadf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbsfrib.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvrexan.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkievci.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xarrshnh.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2avwjctxx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzhuwem.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgoavtuz.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufysfccj.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hinfxbss.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sxznfiug.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ghymczpf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtqsuwg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhodhyp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2pedoukrr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eedjnabz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfhbtvq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhohvttt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaouqoqn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ziigwdws.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2twqxhnsw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2adugtmuw.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgejevc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwukrex.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpckppvu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2aocpzitd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzznxcwk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggityazk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2esmphtjg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yniudvec.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2efbawyyn.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfrnafr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfvface.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2uixwzfxq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vybraxyx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2gfaaatwl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfprqce.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtcmqct.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2pjejfdhj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hohhzidb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfkflla.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2upaztzez.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmczyjs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2zftjbapx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lemozjal.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2fghsmjna.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmjjzbf.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjkotxt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2nlucgext.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkvuind.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2togamtnk.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwxhrvs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2pxaeixey.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xoacxksa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clyvpeam.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wreramws.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2xthsshlx.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwnldcw.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2tpoaxqxl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrbpiok.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjtjgks.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xofucwph.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrtrhav.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nadeaaeg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbxypfl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvzsqlm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2oechiniq.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2kiamtexj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsjpycc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sklmanex.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2igsuvdsq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtlbmpw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqezhmu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfuhjqi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2pncaqfdm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2cejcddav.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yowsvwli.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2opwjffiq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrvglzf.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzbbeff.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2xkyuulth.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzyntmj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbltpzr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwtlqbf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgxwthb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2libudyie.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2vesoacrp.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2brovyjpq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeppgxc.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rnarmdbf.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2poitqnqk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2jivyudws.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyiksrj.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2whxvcnyz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtftzbn.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nfekasry.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzunogx.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqaerhs.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lraadlkd.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqdyete.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2uowjbqgo.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2qdonabsg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjecfjfd.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ardfnolt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ompzlmmc.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kutnvfln.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgeorqj.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2rptfhyij.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zveqjavh.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqxzigb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2suyziiqa.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2eajjkaxx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhbszlh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2njvrhuhr.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxgppfh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qctsrpsb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2iweciqal.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhznewn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnihxhz.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfybqib.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgsnpgu.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmrukwg.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtlvehc.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjhtpsi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxbzcco.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hssvewmf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrpalie.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ygofgpte.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxiwkcs.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkyicyo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbyzvck.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtkquhr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkasstux.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cwombfkw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdwfcni.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2fvifnjrk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2scpfovxi.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hwniljyh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fckvmzrs.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dksgzhlo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrufxtb.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2czxqrbby.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsohlqb.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdsgeth.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iymrevlq.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlvsmce.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvoxjns.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2syguixxx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlxburt.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyauzto.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfcfzpg.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2viclantp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxagkvpn.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2afttyxue.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtweryqq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2cshwlpdw.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyqpukg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2puefpvap.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2viwobijh.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpgwvcp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2vbffgwdk.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lksyfcll.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2flrryguq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxqnxuk.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gutavzdm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zljoburf.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jxabifze.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvklamo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2klkcpoey.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtwllla.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2eoabagsu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2waexihhb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqyvnbt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqqovne.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsfmbxw.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ehghesuo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qykwlsjp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgxrgep.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zizehbek.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmmpxqx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbsvhwh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2txhidlwb.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmaonnq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2zduztsil.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2milzsklj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2egjejklm.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2paddotki.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2obqonhit.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2umycyhnj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkkqpde.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwnpyyw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2tijqecaq.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbfsttv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujeuklpy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwqqnse.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ffeodlqu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qneajrlh.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xetrszop.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbfjmdc.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjkqasp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2huanfivd.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmivneq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntheopfh.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtkphoi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyhpqyl.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2mpowgitr.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2udiinekc.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vymedhxf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhnkpqf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjljhae.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2okppguac.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2okurbuty.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbslnldq.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmclyky.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjmwdwd.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdtbnln.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqsvpyg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxpmkid.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2rqenmepm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oprixrhh.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2htmvvimp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlllprbz.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2dthxwwvq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jevwcysk.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2egrwikjf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2mskkefqo.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pwybnazw.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfqqvhi.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tcessinm.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2meaklfzt.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhcbmnv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qobogamb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2dcztyugj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2qktjscuz.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2pzegrmnj.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgolxam.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uycxfhnb.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2yonowrha.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2bjiwlmnl.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgcwtdw.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfggugqm.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qcduexqu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpopizd.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2aglrudwc.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxboajvu.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2vcczvplp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2htyyvrhe.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2igetfwam.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtyqgxj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnirsqz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2etqxaqij.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2lliziswg.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bozgbsmj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvblapz.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxflugy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjhzicw.html


<!-- 参考信息 -->