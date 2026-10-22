代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gjehdjgd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcgbmkp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeprlcdh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxkrzqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfltcrx.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2hswuehkl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbifhin.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2skvgbfid.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvbbuxl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kyspiufw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2yabmoijq.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzpushr.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xoolslnn.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxifiimv.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhaeorbg.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2sskdtcuy.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqqoeoh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyyzrzc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2srqbbnji.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yphoxhhe.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqgiegm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyojrkt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2lolmeefi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2bricdlqt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpvzmza.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhulhyp.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwklkua.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2abcjtdhg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjftzda.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqmqtqm.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxkabwy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2xoacopiw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuyxlhf.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfbhhtq.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2stgfesjr.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2hphzqqhd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2jmceeyxs.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvredpa.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfqpekp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfexdbm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2norhmxmu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2vyymopad.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2islmjcuc.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2easzxhjv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2eozbkhzu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2etporsdb.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcmfkdw.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzdvkpv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtnqvcb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwuduqj.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2mojqvnca.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lijehzyk.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqzzuhx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2exjwevpb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdkikts.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2hqehhwcc.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2eqepxdfs.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ggywszbf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2pjszfdtr.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnhvavi.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2inqhzlgg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfbgeyh.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgepytu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zebxomcd.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvblfms.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2utcedjlc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtaikaq.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2szqhioat.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvwdwwb.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrdcymy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfiluna.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2igispiyf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2oaebapec.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2bofxfmij.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2tprzmmda.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovasaejk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqhyonv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjnipkx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2larrxvbs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsjdzyr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlssywwz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjzphrh.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2permwqoo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2qecvkkzu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdakfij.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxeacfxm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpstntvn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2slviimhd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tniqtdst.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rojvtvtf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpndkje.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwhrpcx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2udiqtpoe.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fujkmgxv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnkltfw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wscaujwy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2omlfvxri.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfrfcuf.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwhgmcs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2exgumuuj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2tljdrwzq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2askkoyav.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2behtrqfe.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqubpiv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiupymyd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgwnhnp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2drnzgtmm.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnzuyyq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwciite.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqpekbu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfsjgrx.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkoqnov.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2haalzuco.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlsfeou.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chznhkik.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwvywsw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrkrftp.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsauedw.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsireej.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2fddumqtj.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjxjdtb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvzunim.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ushvasgx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsaiptw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvaynjn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mdorpixf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwyanwy.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdzyepq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tofiukbi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2adnxwqvt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyjmoha.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ychdalsa.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgtxddv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrnmllh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2baaylxzv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2trhyxvcl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxojzqw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzvurbw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnpycbk.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ioomadhx.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkzlevq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nomrokdj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwcswos.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2roslputy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2tcybvinl.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrxccgu.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2shtnqkcz.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2snjhgukk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2lbugrilg.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlxlkpj.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvwagen.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyaedhem.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2plularzy.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjzorss.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cppljzfm.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xrizaxjx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2izayfdwl.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2mnifzyou.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eijlbuej.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2lseyahiw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjivwluw.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfvznsz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyafejo.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuglxlw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwealxe.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjydxkc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xntyrroj.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gdckrjbc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2uaukvcqb.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2eznlxscu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxwnjov.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2mexogiap.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2beekdrtg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2qksvvfjn.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2okieplcx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlkfbwp.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2nivbvykc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2joicgegd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpuiqfl.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ffizkcjc.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2inchlvbe.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdqncal.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvsifdl.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqnlyig.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmxctsj.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2twpwchix.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpisxbp.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xfowxghi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2orsexezi.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcauivu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ooerdxug.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tflexwav.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtszkco.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdqnjcm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2imyyttjr.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2fasizzod.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlyloss.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxfvxqw.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2noaworau.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyydbkn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzxygpt.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxnwjfc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zavlbtmp.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2iondrweq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cduwnfmb.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hpacbbrg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqugapba.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2iwacoijf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2esdodsiw.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxomhff.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2orwcbjhy.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2femvoeae.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkzzuyx.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxgdigw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwehfgyq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnorooi.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2oylpiozy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2nluhovfk.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcutisf.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2twpzypqd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpvvoly.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdlnxso.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdolyvb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oreqodre.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyusvow.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jschscak.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2msrtjxxy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2onughxmz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwrtfju.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkqvstk.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kcaqwjtf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2euntlrpc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wybfsnsu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpywxhji.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmtmxqh.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2owhzozxb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2nwynaxkr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2iwizrzsr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2juypaveq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2anszbtil.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2uvagcrqy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yptbevwl.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfpjwkx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2dscwzsxo.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2asxvynib.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxjchjk.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmubmsp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mabcbvwg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpahfcr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkoiusw.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpidvrb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdgynqf.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kmoixcyy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvxnpwr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjokibsc.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lorksahg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2skgjvycd.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fewxanyv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqswudz.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcdtoel.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqaruhm.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqcjovx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fysaazak.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2guyjtclp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bunvtkba.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2lnedprkt.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2uccwniyw.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqfhzmg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvrrzcm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dlexzttw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wirpuved.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nainbvjv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2killxjoy.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gylwcaqg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2whsfgwpz.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlmgowd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bawguwld.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2svgmhriy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzyomun.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjoydui.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuqzeex.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kypmxugy.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2szxptsgt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2niylbhwh.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xemgnqif.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2boniisjt.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtppktg.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtistik.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2clozjfyn.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgltbhp.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2demgfqbv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwasflco.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2abtdtjuk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxexivem.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2vydyvhnn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2femcvnoi.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmllclt.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvfunka.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2gztmgiox.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbvopzw.html


<!-- 参考信息 -->