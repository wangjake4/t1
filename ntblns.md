代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2givqumdx.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjphyxa.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2hazwefyd.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2abkitigp.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rxswvkng.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkcjgpv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxgwqlf.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uiweumti.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2miiztjau.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmniaqu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2djxzheed.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjqlrwl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2cogcdvbw.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdmxsik.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpfbdng.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrdifpz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2vveylagz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ilauzgek.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpdnoff.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2tsimqjnt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2utaacagh.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqiusus.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzvffuy.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2wyeuqoyl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpyeeqt.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfhtzgk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2elrfqrhp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdathzp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcpmzcl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdoeiig.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2myeqmkdl.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2urcinwtx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyuwnxd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcmnnjy.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcapcxxy.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmsgdyq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnteucur.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzoeonp.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2wohwgjgp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2flassymt.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtobmze.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2jnklwpef.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dpivtnih.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2gnffqmst.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2mftrlmce.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwtkwot.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2wydgnxlt.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqkbwxd.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2svcffybx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2echgbmuy.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tiekqehc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgmqhsf.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuebimp.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzdkzcf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2unjblyji.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrtxkrh.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrzdkym.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wehynsty.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdjnfsd.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jrapbkqa.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxuqgck.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjqorwb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2kutzddnz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcczesg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbvsrlo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvbsgii.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2syuutpwc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mnprytcr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnchealw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2hqinlbav.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrjtjjv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqupyxki.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmfnwke.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2aebyuler.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwxqxyi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhccctxm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvvrtdz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2agjnrqmc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbvsovr.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pvruqzbl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxgneek.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgkynfg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmiyoja.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmagndi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2eswyhhkq.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2cllihiij.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnlumqx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxrlgeo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnetjvy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqlkcvz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbbyhlh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2unjchfgc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhninqdu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrditye.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dryzwolp.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2qdznhmjf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2hobmmxil.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuaczup.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhjnibg.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzsabcr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtoqcdk.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xoadygaf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrzquhe.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dsaxywvj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgpmmxe.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhaxivb.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ypeymvpk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2diuylrdr.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxmcocf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kaeysqoy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qploliji.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2flueiing.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhignrh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpgigvg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvdkpld.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgccmqi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2owwmugyf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsyfzyf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcohlon.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcfxanv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdmmtvj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2beomepmj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxcyboa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2tjewecxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxfwmyr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2evfngoxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjdqthn.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2enhwkdro.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlqizwf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ovknmtzh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2irvfylur.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjolyaj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2jteeyhvb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnorfpo.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtmgyaz.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2nhblmhdv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2fuidtpnc.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxdqmdo.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxeyzjw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxhbknx.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyptdkzt.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcvjdap.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsbzhmw.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtsyjwr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxosxld.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2tboygsuv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwcorsw.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmctqfp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2shtqzzhk.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqpzppy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2unsjcutk.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfkkjvb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2chwwyhlm.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuphver.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2phrxvzuu.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bumvxlsn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ybenmofd.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2zriinsyy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kumaebox.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcwpigi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2onhvmuls.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwjxvpg.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkbusky.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzatynl.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxizcyns.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjbqqoj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzshndn.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wczzsjod.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmxcrmr.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxfwrnv.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgmvcyy.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhtzzwz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeakbdnh.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhslnek.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnrlhtq.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2efkuklck.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxipfan.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2exyuwhnj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkrqcaj.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gcblyxlv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjxoinp.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qgphcimm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdztqim.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2rikbaxdj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2gucuvimx.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2cadmigef.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdcqpfl.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmtqyni.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2mdiexgou.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzfftaw.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2thnifcku.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlkvzba.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqxdafs.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcnuafo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckumffya.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnkieuh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fswfwxuh.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnkzbra.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvovria.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dtaxrycd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iurmpbtr.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxqxvln.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuwtrbp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2twjteuzc.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjtuzpq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2oizohtlx.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwivpyx.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2kayflsae.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxqiqqp.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aapmffkx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nxczsbjf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaglexcr.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kkymadaz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbsqfzp.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzesxvl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2buptsjrs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpvcwyv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvrzjfb.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvslwzjf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdjynqk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlnwwqn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhrydmc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tazrwgfa.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmmfomj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2eafqrvmw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxklebo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvklgww.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgkkwei.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ppijemyg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkssdufn.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mexhjhhh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfsbrrp.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2degdikbr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ieemnjzx.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2juaosnxq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2iljiwthq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wolidttl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwapowd.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2neikhzxc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfoujjuu.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rmaxhilj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbndiqd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2oefbdosk.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ttepgecf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dswmkuob.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2frbcbkav.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2upgvgndu.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2olusuhiz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bckwbldz.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2xnflotaa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfkjnxe.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfqmkte.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2djddldbt.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2esokuken.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsmpmmc.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzwmnvj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2omfqbdgm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtrlsbv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lioeonhh.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kswoheag.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nttylkfe.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fxykdceb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2scvmoqzk.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2vodvgaex.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2azhgwmcu.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2njgbdmaj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjxyefj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoracidq.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qenaxhad.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlknacb.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2oydserqk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtelzab.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2luidhnij.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkoqghe.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lqynkcez.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2iglnltnc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdibjbq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkykxpr.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqhwvwa.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxmltkw.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsqolej.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbwcikz.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjbieof.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehuokdjy.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aswfqgxg.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2huksenrf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2lqggbyhb.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2girvxbey.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sujlxdjh.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2swzikltn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrkgkmc.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfveznm.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgselqw.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ctocjvcn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2efmzszez.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdoorcc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2glxoprlk.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wexvbdyx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzchmwi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2bmszdrjj.html


<!-- 参考信息 -->