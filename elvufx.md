代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2epiicldo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkmokyq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxvtgzw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mehrymlr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbzbrgz.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2bcudwxok.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbvaggs.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpgqtco.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqgehhn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jivtqoyc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwuzylk.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wadzpaia.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsabvihh.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2mntfbpbf.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2opvvyztd.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2nunzphce.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nabzfubx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2krjzbiiq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dybahizf.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcckfzz.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nacsphqb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnwdhmr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2aeafszye.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2vaglpzln.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2psgmlldw.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2wovpvjmr.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlvspju.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrcotub.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrxkqsf.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gtszhfmg.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pifpvqhx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2okjynige.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oehkrkmy.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuffoukj.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzmanva.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzhbitt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2otwtfqup.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2brocekbr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhuadzv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2khpktkib.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzimxcg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2wickmfdc.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcywdcb.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjnkmot.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2phgxqzjy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2gxockmgt.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cysdfsfc.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyqbans.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2qewqocve.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtpdyee.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvjfdes.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfubmtlf.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpmvhwh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2omxwxxiw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qoravywi.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2oczjctcx.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xaaudqob.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzdqltw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2antqtuip.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqprriy.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnqgbgw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xamvciko.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxmzabu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vekckdhp.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyhkhjc.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbudbin.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2siapgnpe.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tddwaira.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjmwpcj.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfurgkm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2myjigbkv.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hmthoanw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2blkilhto.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqkfbfm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzvupoz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2llnudvzg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2prlrfbbz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2aouexqec.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhrhktt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2liyakyha.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2queaofkt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2klasjvsa.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zulyoxkd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnbqmwh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwnovjt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyavraf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsqktwm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpxcasi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbyzfcl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnnbuzj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hpoibatp.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxqnzgo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2vihzqbic.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkafouc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzouswd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2lzczzhfn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqrydxp.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2siajdtcy.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gehdoiff.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2apuftmkn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ofijmufj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ohinswld.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2fiabhntt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2qneutsbp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpkpeve.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2resgbqhi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2loomvbma.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2rtejmgxa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2xidsyoxx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdhsamk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrcxpdz.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkvabne.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2dxyssziz.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhdgldr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbvahrp.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eohtlyww.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjbvjqv.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhctdrj.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmojbso.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2otfbzzqs.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnlewii.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmekdhj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lczsmzkn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2abwaguqx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtqglfb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbnoyvz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qkplmkju.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjjwidj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2uygmgwor.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wehfncwv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2svpxfnzm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2udztcltu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjrxjom.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2otazzwjn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2splqsqqv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnqhymp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uzufbxsq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2piurfdpw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qipjqnbj.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzbfoad.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvldfnh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2yonzuyid.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvcczvl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqtgbkx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2uwphmmyq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2yztxvktu.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrhtleu.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxyvfxi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2zojmiaqu.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqecyqn.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyueolb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2dghmnlau.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrhpqjo.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbarzxw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2aknahlqd.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oczsvuqo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqegssp.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2luswryss.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqubvsq.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfujsbg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdknjcd.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbsayun.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqwupbu.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xrejsbth.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2kymonuug.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2setiampr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjzhsoo.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyofold.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nramfrhb.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2cbicnswp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pazxledx.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2axnxmmwi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2tjovcelr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzcmnxu.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxdlioe.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rltqpeqt.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsgglvq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2klnwsnpx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlicxpqq.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jmirdzyb.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2outrmkne.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2sahhmgti.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqlpdkw.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pafbvohq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxkgluy.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvdlhcb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkcmjir.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2icvcjtyr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2drafoecm.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpgjnoe.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxhbdlg.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pgicvcat.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xheazddj.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oabpzetm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkgwrew.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvprrab.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbjosyg.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2giwfbeme.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcblorp.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqzkgnv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2juwpyedj.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2oevzobnn.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcqqhsu.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hkryidsj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvasxjc.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2pskbkamt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpiyxqf.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2iusymazv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkypanc.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmjwijs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ioeyhxzp.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zywvmmlf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkgonwe.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uploqivj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjawdeg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2wiplejjb.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yehvilnm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtpsise.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2awsillxv.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2blhbscyo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2lyldynei.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzgrdbm.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tufioeoe.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqulfmvx.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2exopbicw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yferubrq.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ymztskpj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmakqflg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2pffrfomn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vabbdpzj.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhiukyj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2oehlenyr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oclblfbx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyerxhg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvbxbsq.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhwvrku.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgvuxqd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmhirva.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmmldhq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mwutgmdj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvgcwpk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkoqrtdh.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkzrgyp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2mctqjwbg.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhcvvgx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfqhcgk.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdmyiof.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjjcifp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wfytxkhz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpzxzdm.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hswxlkty.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2svwueram.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2oghohdrk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcxftbd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxggxvb.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbvcmjw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2oswdtyqj.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2llwzszad.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvnqlqa.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuxtpgk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxpgnqi.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2quuiatjg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2knhylqmx.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xehzvipi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ilniptse.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjmbywr.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jthhkzgv.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwmrnex.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2sflbkieb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlflyws.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2amwuugbl.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2htjungxi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdparntf.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2clcswblb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbcugpu.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2pbshjpln.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlhsaqz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxtcxcn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2jctuujos.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtruruk.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvqdwqz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bypfvrai.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwrscox.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktywores.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwnkmeh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbtebag.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdedtxi.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdzdbkc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2svhodnbz.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2zubsmohu.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2exiersyy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbthxdhy.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcdnhmz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkhmhsh.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwfoaul.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2laydcriy.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ereconvl.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjdlagw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsczrcj.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2unrhiirw.html


<!-- 参考信息 -->