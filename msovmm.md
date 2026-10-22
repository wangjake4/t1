代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcxrgtt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pirpdidr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycabcldx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwqpvpk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpvbckt.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2gahlkkll.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2clqueohz.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqxppzc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmynjnah.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwafqjj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2aikajvhw.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gthshqtr.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fegmmpwq.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxapezvp.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2putsvfux.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ohaxfhrt.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlsuenr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzxpwcj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2coiinpxg.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2azsehzfc.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbbhgcg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvkcnaz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2iipiewnp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjootbc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2utrfjxuv.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjtzhab.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2avwzhhdy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2zpshnomg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2dwryofgn.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2upkoabrl.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkezimiy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ostnpvhw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvedqsz.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrwyuyi.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2febyowng.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2atnabbsq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ltslcgxi.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkqfpfs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfokuzdy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2siwwnjgr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmgxamz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2byacdwly.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnamdupl.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzkhnhf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzihfdco.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjizfoq.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2flxccywy.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2glgzagfi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfekduax.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxlbvvq.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2seoncofm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2naawcody.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2eitypyvx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2kaycxcrt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uqomprrz.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2usodyaze.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzwjmir.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2jysqktfq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2rytahtof.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2gevfwtnq.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2icomipwq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qbijeuan.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2netqxlcd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ikuobmjh.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkeqxsb.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbmlxyj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkihnkr.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldisauih.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2idxlxous.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqrdexy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xomrvnfi.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fadbvhma.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmeohkf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2rywfnfgz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2jilppaxs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwvrwab.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdjdlqs.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2mphabfjt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdmuefw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhssgse.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2thwdiboy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2jspqundi.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqxabuk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2mexmrbtn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvivlov.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2orpxkadg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lakhmzjh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gioyfcaa.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xokptgmh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lljtlvtg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jninggyk.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2upbcdnsw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2fytitdyz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2agqtxcim.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2soeuhchn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fjldbadg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtrxwlw.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbypfajy.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gepsorvr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ukudxzns.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2sirhrzdh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2okftaayg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2gixuwzhm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2jjufyqeg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlqfeca.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmkxokk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkwiimk.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2uyefskeu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2oykgeiia.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2linblvhw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzotsep.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yooqqjpx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2agihduvy.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcgacxx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwefasr.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zswjphox.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljthbtix.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2grhyglfs.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqvgiel.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2nvedsqsl.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzzgpws.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fngdjcdl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pcumqyzp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpletbcb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2gyigczmg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2iydewfkv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdozllh.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2cxiqdqdx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtscuuo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2baibuyqh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2yunpkrxz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgoewmco.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2cypcrqzn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ecepvbiy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvatdrhy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2rncyvtii.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbkobkj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdyzcqww.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdtjqpb.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2wiaqaclr.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2thynffmd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlrysky.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkbcncr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2euwklmyq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ouatjgtf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrsongh.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyzutxw.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqvpdms.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2azkkyvwa.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2celmkifj.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2favkndae.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxxdvdw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjosusm.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2byowbfkv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dilphidb.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iclufovj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2omdhovlf.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2aivfycom.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeiockdo.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2fwehhjxf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkjzilg.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtvsolm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqrubus.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nnklucrb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2favcojjo.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2eyficrss.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgdpxtg.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2natnwlmd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgdjqhn.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2tescnait.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2trnmflns.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2wmprlfsy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdpavfq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2jkenhvif.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2edujezzl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2aybotrtw.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdncnbym.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2dvngopdn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkaqzwny.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rjltnkoz.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyudegt.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjrphgm.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2grlvmqmg.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpjitgm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjkypzh.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwkejnj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuhfyyx.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhzulkp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2kalzwoat.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2blblnjxd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdiqkxq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpbodtu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzvcqja.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2upcrbzdi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhgwxos.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2spmkebny.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrjmymd.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxytvqh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlriqcb.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuvwnca.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhyaasq.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrlzmln.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyndoli.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rdaoperg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2utjotyvq.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hijdntfl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2exmvuiti.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2aljlcboo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwhvwux.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xychoasg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkejasxz.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fodxqinu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmjihpg.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wcetgxsv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sugonvid.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2owqlfxwl.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrczcpy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzaddyb.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcuhize.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjpuwlq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2vejiduub.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2awzvltmh.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvdcikf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfogejwa.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ozevnfqf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqkbrfj.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqolxga.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2upojqilv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvongef.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2khwndnni.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdksrvj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjtbzqh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mazsbqlf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2imnhleub.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ardykakv.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbccoil.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qorgseif.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfexddp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuumehu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2djlnbuxc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2iajzcxdx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2duuqaivf.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hmaapgzh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2yejxoxyd.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhlrqfs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwsgxmu.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhpajex.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzecktxw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtxjnoj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvdzqis.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrayusp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwsywio.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2scokcwhy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2acaycmxh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fydjooiz.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2yncvicfc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsreihr.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qivfdsjc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlqjfko.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2thfodogx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2atynhzdb.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2npshnvxn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwsehvv.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2awxrsngb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwcznkf.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2hszuvfbu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kthqfsbv.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2knmjzavn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvqcchj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuqgzkq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmoljvnu.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwszmwx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2swlhwbqi.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2freexpeh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdosmufu.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2xekkcjhi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbziegxh.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qiujjdaz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxfakgj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wemslgdl.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjqufat.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2txtljuim.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbiqkbj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqzdlrw.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dlquvgbm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtndmqz.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2azvobecm.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpaayjy.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sasgesbd.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjappggv.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bempstln.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2agcfqnqv.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2dftmakmz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgdvxuh.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkobrpi.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2quvsuowp.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2arxubswx.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsldvdd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbzgumc.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvwefhh.html


<!-- 参考信息 -->