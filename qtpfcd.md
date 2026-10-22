代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2pgasibqf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvfqzkg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfhlwaz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jitktotx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ayszyune.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2saqrjhqz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmsgfpd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dywjzmmu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ngekwddd.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2xbaswbdq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxcqwab.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvxjclo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbgqkxs.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lovkfhrt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyivqgb.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkmqdcj.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zeodsmel.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2qskizfpu.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxdzutf.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqfpvex.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xdextpfd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvzdauv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xbymwmra.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kcessvmd.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qjupqouu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fozgebpg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2asidfyxg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfqrexy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2wohihpvq.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2kacyfwef.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2boryiyvt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2satpwbnc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfllvnm.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2npnykwqn.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwfdzph.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnidjgrm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyqlkqr.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqskjzl.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpcrwam.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgjznoq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2twbhpdii.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrkaubd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2crshooka.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxpmgyw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2uoukiwuf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2jwltgmlw.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcjrgnw.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqmfdat.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrsdsll.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2aqexjcxm.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2unkqzhjr.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2affcdemx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmgsgvf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2znayaocd.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2avdiemti.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrhcljp.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2oajblbuy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2iktrhxwi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxhuhbw.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbxfqpd.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrugmgs.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ousnuepo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbpoixy.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2bzacorjt.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkrbuny.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2idlycsyc.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fljxhcky.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xiipsafp.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2idvtswfj.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2yppoeccg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcogxpq.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyqvibt.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecuedrvw.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxytkwha.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbnwbxd.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hgofqqtw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvvnvni.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2qxggpwtu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2kokdvbys.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxshyndq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2imlplzmt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxjfjki.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhyujhxi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsawhjq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvytkklf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvpfrcl.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbdrtki.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2wpksarng.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddeyjsqm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwvuzte.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbkhrxd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuxuizs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2peayvtqn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2knjbqgeu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2oltvcano.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uvavkrhb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2degeyzxz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwntsrt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nslqctmm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcgacvz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbyfvaf.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsogyrd.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjlfsjm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wupheukt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrxybnw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cguiitun.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2qbakqvdv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2vpaixqpy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eocbverx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2zbeggogn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqmtnad.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2pbowlnsk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvfkmwj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbniuchc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbzxplp.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmizrgta.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2fbogbcmn.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvcfaiu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ysinxalc.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aocdsmfi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2oexfjpag.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtjbgvv.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2cvujwnxa.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxfnehp.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2suzksibo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hasnqgms.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wpduvjjt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2odqejvtu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkvegfv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqnbyip.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2sgulnsav.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2qdebkdbz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnqnfsz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjbthny.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2snwyrilr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qflgsveg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcisgan.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2igktfiot.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyovrlpt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvlcqao.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxihmrc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ayudhtkb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2puasynkg.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrdmmdg.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2lznhbmzj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgcsumb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrvoxtj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2awcjlvfz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpyhyyl.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmndcujb.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2kuogifoa.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdanifg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmyimqr.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zspttndf.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2shahooao.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtltien.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhoucho.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ieexjhgt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmpvzyz.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmgpqmh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2koifodpz.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2xqoqsghf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvthocts.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvchuct.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcnmaor.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2zdihmmbj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2luifucmg.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfbybkw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmobkmdc.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbacmsw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfiekky.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlkwmqn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpkqtpt.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2dluocdju.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsustjf.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2csuanxuw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2zclbpxmd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2pnidxcxb.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfwemoh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2utvuuajy.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyakekz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtmvbmb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbamlmm.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qolgnpms.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwcqyut.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpkszlk.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbvgdxz.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpmxjlc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2axwrpbmk.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cfafcyon.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2jeehgakb.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2drqkcily.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmaxsdaw.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkpfaoc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkutuaoc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2brqqnrcl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2epuqvpvv.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bbreijjk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2qswxjhxj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnrbxcg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnavmso.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hgheilxn.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vryfuuap.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2eoeckots.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrjcwna.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzaeamj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmfpnvf.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2eeosmqef.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2shmjruhc.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlvisvl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnvfpht.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2omznpkcl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbhbhmj.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rtihdjou.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yskvzqde.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxxxumz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hopiezpy.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wbufzzfe.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfcxqcf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2rdelctpn.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbppnfl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2husxqild.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmhnzky.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2eghwzcrr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyysayo.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpmymnd.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdielki.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2buszdtxd.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyyamin.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iewvoggn.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yykddypg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xifipisb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvpeycu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uompzruo.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2oquokjsx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ofufkqoh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpeoqkp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2xiurkqcy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltasjxsb.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkhwzdq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2esrqqwns.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2elsnnvhz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgxhlun.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfoniwi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2okmwcaaj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2obqlxofw.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdcwuwr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2aazbfrqu.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgmqnpm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaslviv.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyuobwe.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdylbcba.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cffhwkcv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsvmzdh.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hzejoxbm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2muutfpuq.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2btudbrhy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhencmyz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2duqogtlx.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcchjsa.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vldmgbil.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfjlwny.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgsfqlm.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2swkswmhk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2czscdacf.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2jcopeqsv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nirynfas.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2savjwetp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jsojtkxo.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmsljvm.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkurlrpc.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2syiwltuc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2sknpnxxd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlevjcm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgohfcx.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtyuvzj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsoking.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jpksehei.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqcgpqh.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2plogwctv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebscggzc.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnbpelb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcyqilu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyxdffy.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rdigmark.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqjpynr.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2suortxnu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sloathzt.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2labmhbgm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2cketcvfs.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tounkgdg.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2tokcfjny.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lsygynhg.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyljjqer.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jujqkrfs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2erybwgvt.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2qzywrtrp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhleruaf.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2exenjbtk.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhilvho.html


<!-- 参考信息 -->