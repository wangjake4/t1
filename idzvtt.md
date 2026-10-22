代发 wailian999

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwhmbjf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkhzyay.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2bygbwfff.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2jtezxagy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2yypidzxa.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2iskeeelv.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iynplbmh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjezyvh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2wawybxtr.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jubwlgbl.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjemahze.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvewtrb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2trzizrzm.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njbgyokd.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkbuvvw.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwwuwoz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2poisjxfq.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pohyvpzb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzazneq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2fxslcjdo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvgdyxi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2hagdmgsc.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cumqewfy.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyfzmpr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2idvlzwaq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyiscbb.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2loizbmbr.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qehvckhl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmcgcfy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhjqvgi.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hinjhbxj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hliupeae.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bttkwkyf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2nejtaorb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlryxlw.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgvmhhj.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuzlepa.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2haeqgwyx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2tcaiikmq.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzlgjcr.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2jaaqtrbn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzsifal.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvkzmib.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2azeofdqy.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fckqnubm.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2daybgxqi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tyctppqr.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwwevzu.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wslvegwk.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxeaoiym.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmaclfe.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjvanpc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbfrypu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuptmeb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2enxflsgg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2owmjpfpm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2fimfekka.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjotwho.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsisirts.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvdiwib.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihownpaj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2iqypojqf.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lkevfrvg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ueyyodqm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2apmvtlpw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2igydxqbm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2agsxeajc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmeeicb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtqryot.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2opfosovd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vvooqqzp.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2emwohoon.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzpgqve.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnlwtqo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfygfpv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfzkbmx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2fahpdotf.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2fovyfili.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzhnudr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dkspxkmr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2tuiugvxr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwxkxor.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2azxartmf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwvgdoj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjivzgf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2dncilgiz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpglrtl.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2jojabrac.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwgzoau.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2stqsjeyd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2inwwxcmr.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2egsaqlzw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2fvoetjpw.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2unhqalvl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdvtkin.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmevhbn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmadwddq.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgsbgfb.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wvirwytq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkdsmdi.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhogujv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bygfnpko.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qureokkd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2soohjbcx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2sycmghia.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrvsbpn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgyykmx.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvbigei.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zazuidkh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulteamgo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfjtksu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xidajjam.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwauxzg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtnvrks.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzozuvhj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlsdurn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcykkpk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctulhzgd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrzxprk.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyliecz.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2qgalumuw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqoawrj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kotiipkz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrujjbs.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2diizkqwp.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dazvmshj.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2apdauxpj.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2mxudojbz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpfpfvt.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2thccpxvq.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhscmjx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2vilfbpln.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtbhxoz.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjnmecv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtgngvt.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zmydimnr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrsqcii.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ayoukgix.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhynlba.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsysqtv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqpbgqf.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2vleholtt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2itopqkts.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmjepwx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmflgtqe.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtipjwy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgphczz.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xwumyuow.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2blonepzm.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2egbkvjmb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjowyvx.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxwpxui.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwzuykq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcmklco.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvoivml.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bnerngig.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2zoeuweun.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqbeyeq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2bykxldwb.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2mivlahwe.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2szgmwwmj.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjiquvf.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qycevaiu.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2reetyavh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxboafm.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkafyzx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfoadgd.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzcvoah.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2qftcmiws.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nggxavhs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2svzbdhjo.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfhmxan.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnebdkcu.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wydscylp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2dosrdfin.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtwjhcs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2wekgtrkm.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2darhqdxc.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkcvtat.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2akjlzcaw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfaydqe.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvrfcjm.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2psakodyu.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnmhqfz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjoxjgka.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2sagimyro.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmiodrhk.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqpreqi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgutaagv.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyjzzjm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycofelie.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgofgoe.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvpsvab.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2whnamdhb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vetezqiw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2akwkyxry.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzivlzd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvmjbkd.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2msjhzdvb.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjtihkg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmkotce.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2clatbsol.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnslesh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbsptuq.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqbnzmn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyxqjrl.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfyksgp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kezdrvkn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2brikijxc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpnvcgp.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2clxbtfhm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2panwtmlr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhswmcax.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnonkor.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqgmqfb.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2acoldddp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrsrgmi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxdwefk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkiudgm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzodtby.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhnpxff.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztghccvy.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2shvmshgq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2emxfmxpg.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjfbyor.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtmzrwj.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qcilooxo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tauejxuy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmxuvbp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2eneykdhl.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqjzhdr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjsudsv.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqmzeyf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdajuntp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrfsetp.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2khnzkphz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmfvnxy.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zucxqlqo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfzyamm.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rirwdjcq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hoeqehdw.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfdwyeg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyssrrq.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdjotap.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmmktid.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2vafaplty.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2tarpxbrf.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyklzkt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwvnctf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbtqbth.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2peqzwkjr.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvofecj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpggeokv.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aweawzbo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqjkbfc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfiseqc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbxujqk.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2irtxyfni.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmltevz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dijsbuyl.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wnaipgvt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtykidz.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxrexxr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdrdflz.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxsgiyq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnvjgih.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqzgesp.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2zozekrjg.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nwytbblh.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhbnfbr.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zavchwln.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2shxtmzum.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnseshl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2uroprpsk.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2jojlmmab.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugatxwny.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsopmcoc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdhwlpf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2azeykstm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2uctvcbzz.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2heuhfyqa.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtlmnam.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2adfunmqu.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqgvonw.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wacjehex.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ednmyfji.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrpzcns.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnitsiu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyyeocl.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkuwoql.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhqgwup.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjwhpff.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2grdswuvd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfghobna.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2rexydszz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhmlpyh.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfolyli.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2tgirlhez.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2asetzbvx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ieytogkj.html


<!-- 参考信息 -->