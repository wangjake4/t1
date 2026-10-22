代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zftohstf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbyeuxx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oahioxtp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvapkii.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2snmuwreu.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2udegopgo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wivbiixt.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuxcyhb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxloywe.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dkizujbx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgvvxob.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dokbnlrg.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2lldqbhsv.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2stbkflwe.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2qabvqpbq.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtxuwuw.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfflwrl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2brbqzqvv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fsigjybk.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpwwzxi.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vjusatlx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rchtemmb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2uhuquinl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdvyjln.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2uranoyzt.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdxorhg.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsfmcub.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2qykeffiw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhlsgvb.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjbzoyr.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvomjnfb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2egwohpmh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmqfnrd.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiogwcmo.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cxubepwq.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkrccqy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2tstjosrg.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyypdcol.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2stgkgyjv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnbxiym.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbqazpy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2knbdtywg.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxnivhf.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsbgppz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xklhkamu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvddcbf.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2flzntdcg.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzniflqc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2pslgoesj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwbvzuc.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqnpliq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2djjibtub.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wopejldz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyawtzx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cificwan.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaejlnf.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2lnodjokf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnrargc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2nedgozjq.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2aklzbprx.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxltobc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhssevh.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzpmpau.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uauupysb.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xdruaslf.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxtywcy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wjahybzc.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2foplflig.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwawbff.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmvoyqf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzllixr.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ajoqkrrv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgfackd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2yudwveto.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgcpgjo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gazqvbbk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2pohjndha.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2znjnrkre.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2iauvtxba.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2igaakksh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhiapbhn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ildejheg.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxrxzno.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2khdanlwy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfikolq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkumpivd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlnumpa.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqewiks.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2osgepcpv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwdggug.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jozerzpk.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2skzjjijp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2zupqahkb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqokguu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2okwcfupj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzieqsg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2rikmjksi.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2skpuords.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jyivrrrm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jyffqqlt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdjtfdy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gkufriun.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrsxhux.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqbjyns.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zugtfngx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlkqagu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2elpdfspy.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2dtngqjtq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2yokusrok.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2crtexlhy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjnuvqc.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyrxcuc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrnkklw.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2huswpzun.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2maatdabd.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2intybmly.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2csfdjmtf.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrpjteg.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hsszotjq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2vndjcnod.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgrmkln.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuphwyv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lczlcokx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gugcmczs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtvjjch.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2apydnhjt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2avkbksgo.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkjxwoq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfntqgx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qympwmlr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlhtslp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qedpbszg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjuasrg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2mpctyjqe.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2hoiyqgoa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2lcyyecdt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2awunrojy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2vclwfdck.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxfueod.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2prhpbbrn.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrlolyv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ymepjdgx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfpbuxo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2zavvlgfj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2swfstmyz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbiqsdk.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmgtoxq.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgkhogs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kuygacnb.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpflhwk.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuqnpev.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcgvzda.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2awdumtye.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwzelsk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydoepdan.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vetrocnb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvecwfxe.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2lngniskt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpjtnem.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkahmua.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhgdjli.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2hspdkbkh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvojmop.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdxoano.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbvmcqz.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvtqyus.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2peccgqiv.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhfopui.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2claixthw.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmzxrce.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2idgagwka.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2elmfskbf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzktnay.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2udlgfftn.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvdcvif.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnsjcfc.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvioqcsp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbyllex.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfkpdtl.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jlotqafj.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdadxag.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2piuomssc.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqzefpj.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tedmymqs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwukqvtu.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yomfojfd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkyumsd.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cuscasmy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnogzrvm.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2suchiszr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hivnnyhc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvakocu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2evxbyqst.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gdskdhuw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkypmcw.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ejittogm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2kahgazhv.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2stnntosx.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sifdylpr.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ompjlshs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2rinkyoxp.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyxmtxd.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2poscgvcj.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ujohpvai.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hydnkuwy.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2luyqfptf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhdiphj.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yqknadpv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zukcwfde.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2uxajdroq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lijtsbvb.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpgzbdc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2msnqfqdy.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2putejabo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqguwev.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2kweiqtwf.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgmmvma.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxdtmqx.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ofisbxff.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2pinzzqff.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2erzwkjmi.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbxqbbj.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xgevsqlo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2srawfrxb.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ylahctcr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2diiurvku.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqiqivg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtikbnrs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2iseflxeg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2llngpxfs.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2uydfgviq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2yxoqcisn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tufjyyha.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmykakb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2meffstvt.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ciijhndz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2snmoxnqj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xszpcokq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2axqkxtph.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2diozmmjk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsooemq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgexiagl.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eodytgck.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmkhyul.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhxxcvk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkorspa.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2npyhybns.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vetskkxu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zmipbflf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqllcutg.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zyaqnrpc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2zinovtra.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xmejocnl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfpeqfs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbvrxyd.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2aibmvvpo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmjbrwt.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2smsghsyn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsigbiw.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vzexwmzt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfxpkdo.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2fryxwbas.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqmcdcp.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hosklhjb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsaatzy.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2pxawtauy.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdzdlpp.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbqioyi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2znnbpohv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgtyzzr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajphgshz.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2maqaoiyj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdonotrk.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2avpzgfku.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvlfmpx.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrvkniv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2awalzotz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2eaerqsij.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2vdipvuwp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zneufzni.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2pyciuvse.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkalvscd.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2sklpxado.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgezburj.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhphvls.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2simmbvwc.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnbpriu.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqdxjyo.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrwytkx.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqsmece.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2asyhwzeq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2szrsflag.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2gchslwzn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrojnghl.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2mqytcytd.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdrpzrm.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkyxvaa.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2atjjrmxo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwicoax.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjhjaiz.html


<!-- 参考信息 -->