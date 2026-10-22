代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgtayba.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlxjyus.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhquyjt.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rjskbdjz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2temjiudk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2colcjumc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfxdjqd.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxcvnxi.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2azhyyorf.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbkyfpe.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyualrq.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2cviqhmlf.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yjedvdcv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hemdgcst.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hivpxnjc.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bztenmxt.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rsecraya.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzanozp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2obvhywav.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ofplgttl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgmaxlj.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2obhigwhk.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwleqzh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2kqeaucxp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2inhagfnv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtqyboo.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khgohxvd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2aevhshkn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fekhlfem.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptethgmf.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lbprhvrc.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2uivnybtm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2byjortas.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2meimhqhl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdigwto.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zomwiddf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2swzylcur.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvcqtmy.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbwnooe.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2mamlchjc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2avbobwsg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2aubzrnlm.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxblbnj.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2aurmmkyk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2idzqlpms.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2brofkgik.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbeejqx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmbhzou.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2exzpqaql.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2qobvxlnt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uukudlhf.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xxskrspi.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhxkzpy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgyzxpi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2yccggyjv.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ilotfxjs.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ullzllkm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kydsxidn.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvkveve.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kbavzddx.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcrasfs.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmnxhyd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2udsyvkwz.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvddcnsf.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2athigjdb.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfebqzbt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnebvqx.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2isbgrkcu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxtrcdx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgvoyoc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2vogaasuy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmroqaf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyhufza.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywopctfv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzdgggm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2exxluasq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2deznrbtc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxzqsie.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oligcpsr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxgoodi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuaaivb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2duybzaaa.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqwqwcs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2svegtnvw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjthdpw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvgbnma.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkruxuy.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mdokgmsj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbrvktd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wmupafce.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2txupbcax.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fckzpylb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2fysdoasg.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2kspqrzdx.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkpqlgj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpqlunv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2dazyiesz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdxqdtl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnaevpo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbagkpb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzfhpvl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqqtfje.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oztuysur.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwxzswy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2kvccyequ.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfbiggd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2eybehbzd.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjrgmdd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2tngffrcb.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvyynpn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kikvykzv.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uzewlson.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhclsnr.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzyhbqf.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hvesgqxm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2kidozhok.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wytktclx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gffyzlof.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pvoslilk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qburyxzs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcsijnn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzclyyz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zepudqly.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhjiidk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2dimbksov.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtovsgb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2lttztgxe.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bijaohbi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2byqlqyjg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdzyppi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2eaioiljg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2zolafhew.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yatzsvvt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2nonhkwsb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xpndtdxg.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzvlqnf.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxmpywd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzcawqr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2htyzurnp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2efmwqqpx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2zeeyffug.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wptvxkiz.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2jtofastt.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2goxgqlsu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2omlthqrl.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jndkqfep.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzoudse.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2monhdmie.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2odoswtgq.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcgqqgx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaejnybs.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zftigniw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kenukuzd.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsietbt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2poryhnno.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbhuauv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2emzhfcws.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2lflkvear.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqyvidl.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2myraxdki.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucirxyhi.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsqnfgw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzewpuhf.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2unjsfruu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2aebmzmzy.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvwyxtq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fwaxroba.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqzjdtj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdhidfi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqgquwl.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2sugfgcwu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2snduckne.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2xrroktwg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ojercuyq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvibzhd.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2anctefbr.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvwjdhc.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wflwecyr.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhskqxv.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2soyaxoqd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmalsps.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oidanozt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2idohxutw.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2olyfwcud.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgxklxi.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpgqfvw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qiumvbhr.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mkodzedc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvurdloa.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mmumbajs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2zessokmo.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrplefr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqceaokq.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2axqcvbsq.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2egnpbqmq.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2efzengcv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2qombahqk.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2uxthromd.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lipxqtya.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkqbfsn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbyfksw.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2usikwvdd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aihuczew.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rozajxiv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnsvfiz.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvadsjk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gutxzbfx.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdcqbhe.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifviifin.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2txpfuamw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2viczdcru.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2noiermcv.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxqjsum.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2sudsufdd.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2woputwvj.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvjtwnl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2gboqokda.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gorxbild.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgggsvt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybazdfdh.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwkqmpg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rikrsswi.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pigcubae.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2otqnwmgj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwtmvoj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjaakvud.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wghdeasy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjhhfdg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdvzbhu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjmcijk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqowkjxt.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2glzvdgzn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxmmqrx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgknaqs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qybnxlfo.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnydzax.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtaqify.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2szeumugk.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwpnbes.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnwlnuc.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2epvdxvxh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2guscvqnx.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cajrjgft.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxcppux.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cvikdboz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2afohtlhl.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrcdvra.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2zheynjet.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxzpmbn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkerlpxp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2waxyavzq.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kamtmsgx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnawrhei.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2oeywfoab.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2djwvijvl.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvzfzwn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2skrlltns.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2lfedgwzo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyshhuuo.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ivznjhko.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2lrurrteo.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2grxxllsw.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpknhnv.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2stcqvkia.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2onubqtrk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmadeuje.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtctlou.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tnoayfqx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcesofe.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tviekvep.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwymrbp.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2jrolteqq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehijicvj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyaonpn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsbpbhk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kaeahmyw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfzglbj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnajsqy.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2odwybvur.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhoucqe.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmxiate.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2zlduhzrz.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnnbrqx.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbofsssb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxklzvt.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrykugh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcewsrp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbljesvb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzpfece.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2mykfbixl.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ygawckpz.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2djrzybpw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzndnhlx.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvsakhq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2auvivdrb.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyjehfy.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wayajnsy.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbhgmva.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2vehiwuni.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvykeag.html


<!-- 参考信息 -->