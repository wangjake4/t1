代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jonqpjry.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pdboctcp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2gghjzsbs.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2asckpfjj.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2etwpkmkf.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2xthvpvam.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2flswuatq.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2aemceukb.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2sujbjphy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhnmnwl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbdfkse.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqmphst.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2oprhigjp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nexobtqd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbxkpgy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ujelzqlr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqooozt.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcparcr.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjrtbht.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2rljysdkw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2sswemitv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jitisejq.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lttevkws.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhwznuv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuizfync.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmffodq.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tymisuug.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdmofwy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxgmmlo.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yobsjsjh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlouqew.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcosvnn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2upggtxyd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2oczpbbzh.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjrorgb.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhrtubf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjlxdws.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwutqle.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2flofsvdi.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhbrlpo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2qimqpshu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhecldmt.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2adaogfgi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqhcrcx.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnupqcr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqmsqop.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qwulvdjn.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqpoenw.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2pnokcyac.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyvayev.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxpohfb.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmxtrkq.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2tggtuhmu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ogigioiu.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rovezsnd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iiftfjtc.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtlfpwr.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2slnvcqhn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rqaeagyx.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuqreyk.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2odtbnzro.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyybgby.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxrhuau.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcrcvil.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2irsyecpz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2qufbxwhb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2raspmtyj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyrlcsh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2mfggospi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2hugkrdfx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqdtzsv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvvqzmv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooksvjmf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2fzajcabz.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gmiuceiu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcflljz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2innpwmiv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xiivaiug.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmltywa.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nadimgia.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ueglddat.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmmfmnd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vggxbyhz.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgrgouc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrxioty.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2daxvpeho.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxgwizt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2qifslsso.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfmrknl.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcozcyy.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2uczstdof.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nznrnxny.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkpoarq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wblhrfit.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2owxbiexi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcwmnnb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jspavjld.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2igofcxke.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2smbcsepk.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2dqecfutz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2fflqpmwj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjzpoyg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrrjerq.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wxipbetg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqwtyzd.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oryqpcef.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szyvxecd.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhynjfp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2vseljztl.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utdicyls.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2utvfqwnl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvfzgsw.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2msvjxdmz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gqeduumh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbrvxyi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2imycizct.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2cupkdujk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2plpfwoae.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fztbehif.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfbwuvj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzorvugf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpbylhc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2srvkzohf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyoeucly.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpijvax.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpcckkh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvinmdk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2czpwittp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uihroqhf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzcxahi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fklqccbx.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgdijkw.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrbvxmf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpvflqw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2upipckwt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwhcrfr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2qsencemq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2bngrbxzv.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjfvyrz.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2jdepbflm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtwqrmh.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuoudhb.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvrevdg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgefwvr.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvvzvro.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2gneybqie.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtkqmmn.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zseoagtm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpueoqg.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2nvewnmkb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayedzyzq.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrvzyaa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2vineqqzo.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2gocmedef.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqbnpsj.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ypubzfwa.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2saolanto.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gapqsjcd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjjtbqu.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2enhatheo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqaxyqe.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2yufiorof.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2poopqngm.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzeavuo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2boppvdho.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2eittesbt.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2uygxdcij.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpvjfyq.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2aaluqvww.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2agvzaqbd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmwnavf.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vobodvcz.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyutpyza.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2aemndweb.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpumyjy.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2klpivvlg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hscekvpo.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ncozbvru.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2rfiottqq.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkbukpv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgyavulu.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2oevonxqb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjeystex.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hjehmtyy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2leszckfk.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcbdezd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwxtiwu.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtjlkpx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyfkaqd.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjomdti.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuohlvg.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ympgrvxx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjajvec.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2iakwagcw.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jetrpyni.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsgajuy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2thtmijmk.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvvocvf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayssywmk.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqhqroa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2shjolmiq.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bierzfjm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2enwgfhpe.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gruvmoki.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwbxsiu.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rjncfaej.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmewunk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2pssdxrqc.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jisuvegs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkcfuqv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvyucln.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlctnyz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2inmaqvru.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2itydjupu.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2shszkrqh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxidlawc.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xmafxksk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceeelmza.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oehsiqqn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2opxqctdf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2chfdpaoe.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnyopih.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2inyydznh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqsnwvx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyicqvvq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2jazlvntb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2wroltmbb.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqdqqle.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2kedgbbby.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2pbctxnwy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrvbicg.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2slfjgzsr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgorwou.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxuwcvu.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uhngshbe.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttstkpax.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dhauvgvs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhvkiez.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdoujzr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2chzbmdfb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wnorehzf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgsqaku.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhrkyyf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihevxtlb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwduoim.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcskycik.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhnrtnl.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kriobfyb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpynhvn.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pofzlwhc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wgldpbxa.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bdueldxx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xooyltav.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpvlxne.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqjjsol.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxftqcf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbjyfpo.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2rliggztu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2tengxpyr.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrmmmuj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vouvajtp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdexdmt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlztqpbw.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhallse.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2putieebx.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xosozvkz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwiiwziw.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbvczme.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhoxifw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwefpha.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvmjlxi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgibpwix.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhygjqx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2axiydjeb.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2owctobqy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvbsqsf.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2edzdhplh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrvgoch.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kcssyrvg.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2czdsdodv.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtydudp.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtbinxy.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aeysvsxj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvzqhqq.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsjsvht.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdhipuf.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2cercsski.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sczhxnew.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaeavrwc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ulllaqot.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2yldwhwlg.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ggecmmtp.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxqaflj.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxapxby.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfbolsq.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqylidv.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2utkbfppk.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2efdsctjm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uaoiofxc.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpmrxag.html


<!-- 参考信息 -->