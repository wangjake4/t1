代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2thtbmyyb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vubbidfa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgbirup.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2occskeuk.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukexafwz.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcmwdqe.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2llnbakyn.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2upxlbvhv.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyytpnn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvflqrtq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pydluzfo.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bkicthaj.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fyizgisx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsxkxel.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqjgnrr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcstxhv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2wsytbjyb.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2felrewvh.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfoycib.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnueiad.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdkjxkq.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2zidlycmi.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkbdmxe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2pygsnmmq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzaeernp.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfufcbe.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2squzbntq.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwvikvp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjwddui.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgmmqof.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnbatvn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzkefxn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzstgnt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2thssmgob.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrqavzw.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2lhporquk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqbqyyv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2khznblux.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqncxlwy.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvwzitg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqmxqcg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkikuihx.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkuwxlw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrhvleg.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwlqluw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2jirwsjut.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fdckmlry.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2iccfgwzn.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfyrwiv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2cztbrjie.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2qwahbomb.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2dceqqkoi.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzzwjcs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhjxdds.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlckitk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nvefexog.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbnvfvh.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmungbu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dzicbguq.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmhoolw.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjrsbwx.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uoncqwpx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2aeiodivt.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfmwoue.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2auzmrihb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2omwduhui.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfzncof.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2srielbzs.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2aoazvyyd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmftehna.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2xatsojqy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2urwlmhyv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgneirr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgsjpsi.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmzsags.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqcjzhg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmwjcck.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2katumdui.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvhavxj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2argylhif.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2giyeulmo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gduvjkfu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmqkvei.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wywzgemp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ircfgghp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2cgiuofze.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2czmukvsi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzimisn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2vouifkiz.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2siujkrlh.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ardzaauk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhuodtc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlrdady.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjqzktg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2chvxwtzv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhjyuhu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vihwbmym.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ykphhlel.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnfipor.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjpxnow.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlrynqe.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qckwyekr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2qtilroso.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmwplaq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhadrdb.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhkgzlk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfpzgiu.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwtlncx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2joirwwzt.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2thafidlk.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2jndacbld.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2kujoeuif.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqqaigs.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqrstcp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yawovezd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwzgyfn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmmjmai.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jmabcvnw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlllkrl.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ctetfsjw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwrmmms.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xydnywjw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2cacgqjdl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhrxblf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpwwoum.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfmtzzv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2yavwvkmt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbmswof.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vmckrcrw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2udvcvmhw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2whwwvzbs.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2kyirermi.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2pfeaokfr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjqbgkl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2aprcczbj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2zscajtvt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvhnwmu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjeiqga.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzgvvfb.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhqbwzz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdrhfmx.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ioalxtlj.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2yakwshjn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzbcsza.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozulhmrz.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbjhtxa.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrpobso.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqquqiu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ravswajo.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxweblz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbmkora.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlniuga.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2vabcqovg.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgwfieo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecativid.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2khijvlco.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2rojilvsv.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgvxkal.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpykrpmc.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ublpwfsq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2iapbpsno.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ukiyhwmp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxmhzfz.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2esqdzzii.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvvkbkz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2cyihybed.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2oeavhxzc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbnbouc.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsjqpyn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxrprsq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwiqddvj.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2aomqhvie.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxdmces.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2uycumoix.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iakimtmf.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mfllsefs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dclnppzg.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iepqimfz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2iegbnlux.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfxkdzc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhjsemy.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2knluksev.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bizlrolx.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sntoroma.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2owctzxmx.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgudrtj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2flxqqywh.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2girpvsib.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2uigtbweh.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdsoyha.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vicjcrdv.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rxphqdtf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtrdeeg.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rsenidvr.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kozbwidv.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqytvxhw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgxnksa.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2otsxdcbo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbttkbbc.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzthamw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsurjov.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzyzpaq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2stpezjys.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xjeonwbr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2icuntpbm.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lwydkxlg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhabvraa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2uetygvvn.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wafplmuf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvtceij.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2pchpanqd.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2tqodwqke.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2louytkxg.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbbzjzg.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjbvimb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwywcbgz.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2glljbsfw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcjhghx.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mgonnznf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyywwjzd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdoqamsf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvydgfcv.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2klilctak.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2irgbwjxj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfskkvta.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wfragyib.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmhrmlm.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbxwyks.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2umfwzdmn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2dablbwgw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvxpzcx.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lophazoi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2lqadcizk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuvgwrb.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmtqeoq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnomzsuv.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpwovmc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvdbfjg.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhgjlso.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzrcslf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkxubyc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrkykvh.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zidjxtkr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyttfjnx.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtdewyf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2vagjjlwf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hebvojej.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2efiggvad.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2navfnpbd.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uayalhcp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vilacily.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxrtucs.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqalcwqq.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2amtxfvhe.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjgzwry.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2accbxutt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2intkzhas.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcvcbrb.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjmlghy.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvxehvr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrtjowk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbnaruy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbvmmyf.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzwvwzk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2soglzfdd.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhbtdls.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eajvdxaa.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsqlnur.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2msrqcjwv.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqwvqgh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbuidlm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdsckgv.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmzkhie.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzqawis.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwmpooh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqejvif.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnfceai.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2mileprqh.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ryttklmi.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbustli.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xwodgzah.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2rikwwayx.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zigotbqv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2updpczba.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2hsenusch.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuhswby.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqihagd.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkebljqr.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkqfydo.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2udfhgggl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmmorpq.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhotygj.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgwbzbc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnlmdce.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2lomtwenv.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tojmljlk.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqmippq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2owhpqpsi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2enxcnnmb.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kdefhvgy.html


<!-- 参考信息 -->