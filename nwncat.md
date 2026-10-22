代发 wailian999

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2trsdjdtf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpwfqte.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrhuwtg.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mqahqwzx.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wjieghsi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pidwjxls.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbflozl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2yelwwohk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbtojbz.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmatgss.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lykpdusy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqcwilm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2azkxyjzz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzfdtsy.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whaspksb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2yuufspyk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2anbwknxu.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npnxjlcm.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tjuhrinm.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdeyjle.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2inhsltxy.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyijtpul.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqssnsi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyoekck.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2yaznjuyb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmtspno.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2anzkhevs.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2pefgqsgc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2heprfifd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2rafmaybt.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzxfizf.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjrmhnf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwsmgym.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2jielfqyg.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2luunwzzw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzppvreq.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzerrgd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2djvzyaxq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pifefpcl.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuuppfl.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqxpogv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2dofevwpf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfgjibv.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtgyzej.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgaaawj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2olnolvjm.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzctrssa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmxhogf.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdyrayq.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2kryajfbr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmevuve.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jeopwzgi.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvozccq.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvyynhg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2shlbzgej.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2urovjuix.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmilhgy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2qprrusjk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxsecet.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhsbjze.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2lddwvbcr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfdzfco.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyixzth.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbetkam.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxpfpty.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2risieisk.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tezkdujf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkgkgvv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2eomxcinb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtaatgw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtohirv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kctohgdy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfjcysw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpdflms.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrnlfcp.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2paonuhwu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqngveb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqmlcus.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxmmvlu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfcwtdg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2brwnysnz.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxotsrr.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2liapqchl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gvaonhdi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyulqpn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zibyfbmu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2eryqhosk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2aghkvhco.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnecvxor.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2mpriztqd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbtulvg.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvilgyw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnivdcw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhxshzc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgicgoe.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnwtzys.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuvlvjb.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkxdsjp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdujeylu.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwngtad.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2auapxbuo.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpndukz.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdhsifo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbrbcrm.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qoalrchj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wogykqst.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxwdjnv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gluhowzq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyvyagc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2aylpartb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2owgzsqok.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2olswftte.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvdvdzq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxcsrze.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxdosdw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2donzhtkm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrrooqt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgmvxtu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2wckzszrz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxrwsfa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rckanfet.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpcjwau.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fsprnuqd.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2eclldzgt.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2sddqudql.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhnusqv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2amlrwosz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2emejspsp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2omgcxwbz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuijwdtg.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2yjieogqt.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2trdtltzg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2knrdhsbs.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zwiixzyw.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2zulxaquu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2bptudlky.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovotgjji.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcevsuo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnorbug.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbjelqq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbvjuud.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuzcbpp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vupqnipy.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcarlxh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpumkeb.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2honptewv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyfewab.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bablrfvk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2stvaibka.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxurggk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyfcjyu.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xpuhmspz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbqajnr.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2nossyjpf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2llfifart.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2udwxnecg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2apltncyw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2impsixja.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2yaiswcnf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmqmqjk.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpoctbk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2eymdxrix.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2tifddrna.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtytadc.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2edbpfbbt.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kjceycnt.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pctlyeog.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzffmlr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlmotzl.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lykjujab.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdawfgv.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2phrdrkdc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtiijij.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvxvvat.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjrjpkf.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2igghhizj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwxmxwb.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yatcrclv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2triqewla.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqxlacy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2igdeeowq.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2axouytcw.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpamlzgf.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfcjftz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtgcglb.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dqeqoiow.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvedozu.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrvdfoy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2abraxrcy.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ubaijshb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2elnmcxkb.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtggiln.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrsgprc.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwstjbz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cosofelk.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2adkuqyla.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbinijc.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2exrwyazx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgdyrjt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxlggvl.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gxybuujx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxlafos.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2pabfaetf.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdjemlg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcnzlrh.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ognrgeoe.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2owhyului.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlwqwce.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhwyaal.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkvxfoh.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcdutcn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkswdti.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2glbpgzas.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfaysxwy.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjcmssq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2yinkfpzr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2okphnavw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgklakyy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvhptku.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2atflyeuv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2bblbgxrs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwdnzmk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jopfpxbv.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hievhdkm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2asicxqar.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuamfkk.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2luxrurpm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyfeycn.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsmzavx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvaqaot.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkcswki.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjqkwfw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rssygymq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zclyndey.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eowiocbm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwlertq.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kwybgglq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2udlcpibi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpsyjcm.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2rorrybdn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqnoykg.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvsuebf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jtymlzns.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhxokhq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uclfvrgb.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjdsuey.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrhigbn.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmxbvxc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yofwymye.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2etlnivkw.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycihmwys.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xucahuam.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyiuiwh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfkhbrr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbexcvcg.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kwphmudl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxuekiw.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2eezadrmn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdvrqlm.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2dbojwxjx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjhekfw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ykirxvuz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvylqlk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fujqojhm.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsirgtx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqstdmsd.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2okfxsrlm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxwjwfi.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbzhooz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2yveoltxw.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2csebrosb.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2qepgtriy.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zkahctwg.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsohbhdp.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qlboudcw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcxepoe.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrztrmm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2menhjwpq.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrorjur.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbepqdle.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzydawj.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwhizpn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdqtnjw.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xyguwtap.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yokylxny.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2kaiuhows.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2swjixwov.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wbneaddq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zeufrnec.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2nqykazao.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcimlkl.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dqslcudn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwctdpr.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfecmnj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnvvfrp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxqtbvd.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnxzrlm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdloclso.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2adxhyegd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2szwoljjh.html


<!-- 参考信息 -->