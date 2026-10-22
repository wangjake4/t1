代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqnlpyx.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2detcpkcp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhohcys.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2kibynfat.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cotkwzkb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqdcxbn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2inffgwdm.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqclwzm.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2knlsdnsx.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdexgwzp.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmjgnps.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2jffwmqbl.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvhrxjb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgodydzo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcgxhvl.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxmxnzx.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yiobmjrw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngeoigyt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2higgylrg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2hsazjydr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxpjugg.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2hhysywba.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bjahrqoj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2goldzmqv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2wuajwcys.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrlrndv.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtvynrj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsffknf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrbuxch.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gctppeqs.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zedpvcxr.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyvsnxp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpwfcod.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfgeosj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewipxzwn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2fstyouou.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvbadrc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpgryca.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhphxgog.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2jkaaxccd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctoztleu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2hkemybec.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmitdyim.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoeanobx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2unwzukyy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvfrlmu.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ordvitay.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcoczyg.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gddarbpj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvfkjsh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2npsqwlly.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbjarvp.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2nznntnsw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2fqirocvi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2hyejvyzj.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkajxwd.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbtfmco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmgbuoq.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tuywtdeh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kovhulox.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ankyrofi.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2hluvpjfd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdqrpbj.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgysczc.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wobusazx.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2enqqiuvr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfxdygv.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2auomlojq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkznmwoe.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2taoeqymv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2vznumieb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybauxxyi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2jqacuznu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihivosdi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhnjoek.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vikeblqu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2inclfiha.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfqrruz.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxkquet.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2humzklhg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmugfjpx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzqdkqg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2boaeaset.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2twyemfve.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhxdupl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nurktuat.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mstliouv.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmduals.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfhwakl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwuqhye.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbddbjn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2otmidgxv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqhvaqp.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdqlsmx.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfhutho.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hxicntax.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2dftqmljd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfhpqwk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2wquhuxdw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2egpqjhoy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgeocus.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbxoqyr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqiwlcq.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnlxqmi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2thwpmyky.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmspdxd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfavutk.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkjtsuk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyzoabq.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfzqyjl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkyvdpq.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rnajecpd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaiteede.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qptxstmy.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdctphj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyeuofz.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gqttcdfo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2awhsvwkd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsolyrn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgxjutp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2eysspkos.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zmghivaq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2swivybvu.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2jaaqdxuf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gynmwfvi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2djuievxm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2tptzuvwe.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqcrejq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkcszuw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoxuogv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2bruokdzp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcqbhlu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bevxubxi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2xczozers.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hxiqomep.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvsozcd.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmyofzw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jnoedhqr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2pluwrnbv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2nihohgwl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2hueiojra.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktontjaq.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdngllf.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzwtfre.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2esrxryqb.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvybbme.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxfaddc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgugyvlw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vogojecy.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2dobjyrcc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruprnapd.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2beloqyvc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxwdpmb.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2jaclicsw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbkmnze.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhkxakl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlpouhd.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnrcldo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkenpas.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fymirofr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvugvada.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzivavg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwokedhv.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvoxjea.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ihofzpii.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2qijzrauu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qdepgopf.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqiknxc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsgttfw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpydqon.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlzyoqz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2aifqsfmh.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2yreaclje.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2vywbxxro.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2sylioxco.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2pamjcwyg.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlveazy.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2frhjlqgf.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpffafep.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hccrcphd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqfhmqd.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnatzsc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjifljs.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2huapssoy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2vehfknjf.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ryynvvyv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2amwomjkt.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vsoqwrif.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnciwpij.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qubahiti.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcbqzxj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2fnetuqnl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2yylggnjr.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdpffpc.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2slmkcsaa.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2enqgojzx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbqmgun.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2njjlxvjt.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqjyzzj.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjvsxjp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdwjlsv.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vumjczyb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fropnjol.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ltehlfid.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftguoiqc.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2azvugwca.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rombkras.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2isavpsnh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqnghza.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pcouxive.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sahvfbyg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxqddcv.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2keuelent.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsonfzfx.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgsxypm.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbxgeyo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzenumk.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcydsvse.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkioeht.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yygckjhq.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqrqwji.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rerkudvs.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvttstw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qosqedka.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2fegztbco.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmrkoon.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wejiiwvp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpyajpw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2avyuukuy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2mcswdbdt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytipvsbj.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pneymuhx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2zogniokj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhdmysp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ommlfcgb.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dajgpyjd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ggplqtqr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcatqcke.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgnvpzl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwftawqd.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2skmmnkez.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnjsjbw.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgaymjq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeoqfjg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2chvnhtoa.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2labakfcw.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnsmqll.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmeaqbg.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkbeymn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2piflqler.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyuexaa.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwaxofp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuwzebd.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjfuyvp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jpetcvxq.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zibsttxk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhibdces.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2wozquvil.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmainfw.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpyraix.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhdfmqu.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwjbzbt.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbaoniw.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qspbpsap.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2agpvlldr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxsqvwa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbierplk.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2urergqua.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqcqtap.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzaxbam.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqhzcgc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ginnflef.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2najfyuxi.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kslczfgv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcwfckw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsplhty.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kapfysqv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iywuxncv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2giqhxsuq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqydawqj.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hasgdqed.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2tmguxqoh.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnnownu.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2npvdwrav.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwfshnq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2bijyoopw.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2frrryrhk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfohotbe.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2azjlnfbp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrgclpo.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbhqmtp.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyiqywkg.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2htjzmoxl.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2wunounyp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xgamnndk.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2igtigmjk.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxtdpaw.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrhoakw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpqhswi.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wptatlyt.html


<!-- 参考信息 -->