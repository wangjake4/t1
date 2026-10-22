代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wijnfgyd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsdqylz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbwscas.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkxigpg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsnuxfv.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjcayqd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ycioknkj.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2cdosfftm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqczdzo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aepojusd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2riforqcm.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvyexsj.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozidyukd.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2eufvlkal.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpuoryh.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtrpbxe.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cidfrwuu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tleqtdtj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gnaqfxsg.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2clgwdwxr.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwxafkn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgwqhno.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2cotnjvbb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyxlbes.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfrmyod.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2moinzsil.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bxobwnac.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2csenfmyl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2iybvedtd.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbtqzff.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgirrxr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2shxhywoq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkvkovm.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrwpnax.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2orgajqlr.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2endxtwdi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxhwbbo.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqpywlm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iewehmpi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqtyuyf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vftavnre.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2smevtmov.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfuqhfip.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgprntj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwsjdoa.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkazmjg.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2beuyfzxd.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdagekd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejybpwsl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynttjrna.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2efqmhcai.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrssppy.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvnetpc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfstcpzt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vllhgzip.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbtejnl.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwmnpve.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2vchusthm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2fuocvgfg.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpoklxx.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrzoron.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sxiczrwl.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhymqby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmosfcb.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rryghwmu.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2erttbqde.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhhhbal.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgufvvy.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrksiwd.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2skgwninq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlmxdri.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhxpdoq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrzuyjm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2yoavbpuy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxnlxqz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrulzin.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2zppkzwef.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrhmmyc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2dczepgan.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzbhtjq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwzyffu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmnwpux.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgobtoj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvpyxrk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsvkmhw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhenaae.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2efepwfxb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2whebxldy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ulorudpn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2doonuurs.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rxutefpt.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqguawm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfwscwg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmzwsnh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2kagkqogi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlswedt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgohmvt.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrspjcoe.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmuevvv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfojcte.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2xxztxzje.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxhewzc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcsqzld.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlrbuyh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2poblrlvv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhjvpmh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jakiursh.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2coaijhko.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2hnycujvw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2veheicpt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ryeslfcd.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtjnnes.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2dkganfhh.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlesese.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzjiskm.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfwoplw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyixiyqj.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwcfcjj.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqezaxx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfloupc.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qakjkeoj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hsucvumk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mppyxhaw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdotimaa.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2achxrdjb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qqidediw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhrjddu.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnetfip.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqryvah.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzicvpla.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2oszplbdn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooigxdcd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ergqages.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2edgjgghr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2nyytsanj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsutusp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2buucrbfq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwahcak.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnrmcqu.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2snsejtzg.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2hsojfthf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qksbkbik.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmzmyqp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2doyzkmiq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwwflub.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjkqmmz.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxqeadr.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrrjxnv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcebevl.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgdpszj.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgramll.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdnbmkg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvgrhfm.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2lzphoacs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvabcmb.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmzglkv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuzjogh.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvfptec.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjrrkqz.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2xanxqxwc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2aprbcfti.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkjmzmw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkrdoda.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zlraeflh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bheebnes.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmuotce.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiekidrt.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrxsprw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdsivqz.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2uijavgjz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqzdyel.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2yftyeoqa.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjujbab.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2snjtlnud.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbbsald.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsevich.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtthlcw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqjcmbi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekssbtzo.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkqojef.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2htxqcfbe.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjfjjzh.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcqwhnc.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2llnzjywk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmknmtw.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zywvnhej.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbfqlwj.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcaxbbg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2modvrhfr.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2elugcfwh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcfgcrj.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qrormlsz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dujlovsj.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2obwgfpfy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2tanqwuoq.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2hptnugrg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqvszol.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2chzyfasc.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqhkwbe.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxoowrl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbqnctw.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhxgckh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kscwoned.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsatmje.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2amulyarb.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2axszxhrx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhcgdvw.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2oseddpas.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzgzahr.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2inpncyrp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiduxtbn.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjvpxah.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxkpgjm.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2spbwwiyu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzssomm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2jukfnbnf.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkxsbnn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgotrgb.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpzgrzh.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2zmteiups.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2boapgiul.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2otiezxbq.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hirymobd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrpkogh.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkhgzog.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhtmkrg.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rnobyosz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeabyaxi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtdlshy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbytfttj.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyjzudm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbzjjpm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eruspjoy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdbfhok.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2odaawuhx.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyvmilc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ocokksdd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgkvgil.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqavmkt.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hsizfzni.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzktwkq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmsnfoz.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2amvixmag.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrpcnsf.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pdykydhb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzenhobm.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxwniqn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvnfnfk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqsiora.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2svjhwinj.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iefgkttl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxetxwv.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlrbthh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnonzit.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjjbzbh.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2buyalrjf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkfzlqs.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ylagfvcx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2pddtenqd.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xshhfqtl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfjbjsm.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2neqdvwth.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkqfnfs.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2thguetza.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2enyjkaen.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsxavpo.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2rouampqt.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfcxwci.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijowgwnv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuubrxb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfwpewx.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2eiaffuvu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2alwgoavc.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2obqpijuu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvvpglk.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2bemfxwex.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwavgek.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bpoicprx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2azfthutt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoyfkfo.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmohzcj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxaqoxnu.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2pggcbkln.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kflvrram.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bytakryw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmvciwa.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2heipkeuh.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2oktkbyta.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcplxmq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihaqerda.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnkhojm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyblgzcc.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2dsggzteo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsscsrng.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdiqcuw.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iitallgl.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sozlzgar.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvzsoft.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzhnchc.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfmubik.html


<!-- 参考信息 -->