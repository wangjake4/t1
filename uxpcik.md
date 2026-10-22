代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yiywqqzu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2aktewxnk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2elgtmhos.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2etevjwqs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rswnijzk.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrrngtb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzrpadg.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzapaap.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwdnwdv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2urbxbmvx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwnivbh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2luulwomp.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqlbqwg.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbndmjq.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffguesyt.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhqabss.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vppkeenw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsnsvbj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzhzojd.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vutxctfj.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvhlvtj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwtvlpf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2crkcwzks.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2cesmrkve.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbqisir.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwnobyj.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gxoypsmo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2cendptgs.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2jlouhljm.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qubbvgpa.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjszigz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2jzniwqwx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrurpcyx.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grhvodma.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2chopwomy.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcjoqrt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgzxmjj.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdyomsb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwurfcme.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrdnlfr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ifumsprb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2uxunplvm.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrybfty.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxusqiw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvbekis.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2jposkoug.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjmcxnc.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmttipa.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2exerkyof.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnmubyi.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2zojctjix.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtchdak.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2solucehr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2afdiwlwa.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2snthkvhm.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ngexqxbv.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2fcukurxl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrwzsgo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2exridurm.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxffscc.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2elodlpfa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zdssljfj.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcwlpwl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmjxygh.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqkblio.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2mremzxlp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmnqehc.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2umbwjnde.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbbhwuk.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqstaar.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuedhrp.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2daedwrwv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2shgxbmmx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2iauyoujs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwltkwzc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpicfdga.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhvuipn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvfpbob.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2acowcfgo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdiowbf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdetgow.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvxaxdk.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjvhilm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuzrivf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmzmugc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qyicujoi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2seanhvew.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgenybkq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfggqrm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwvwgst.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pegnzxjk.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2baqqysnj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2giqcayax.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dlivaqwp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2buvkfzpy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcgqspo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjepyvk.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfltnxww.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2atmhasoy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hooohspk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2txsnhnan.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsnbrxa.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2fkehnoqg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvthubf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhuopoy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwowbmv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwomkbnf.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2serracoc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmjqhde.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2aovlcgge.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ucddvaut.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bctnuhfi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ldehjzqn.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfecgfif.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szfnpixd.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2esgsesuk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwxhkyl.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iggwrizd.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2oldgwnen.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2cezqdowa.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2inkioyvc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ciblvbpx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2axpwcxlb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikuiwxyj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2crjbbyxj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnwjfbu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2eowezhag.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbtdnne.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2urgaxlqt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2akhgrfsc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhflylj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gupvrblq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrskfnt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2inohbjje.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbyhefk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2nolmgmyl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bedgigev.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2oftgffcb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdknmmj.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2kygjfixk.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2kumwdcji.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2mypkntgj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnhehqd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwtreyp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkujbup.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnqxokf.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ksecmnbu.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ojomusgt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqqjdfe.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnoamiq.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuebgmh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2azjnymoh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2phmhzjyd.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrxaffh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijaznycr.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fofbzkob.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2noklvill.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfayzlf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuemxea.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvdrray.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzlfnrm.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2znpjwpcd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfbybri.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmbndad.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2yytoiwpw.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvydfdq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuhsnrx.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wgahrngz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcmnvjx.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2tevfvsvc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rqruopcx.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2hhptpgdi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdoilyg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2wslemlbm.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2empfnicg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhxftva.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdygctjt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2zinsbmrl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxukrhiq.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vhshljbr.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lthvmpoq.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vtuehnmp.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pknnpdbu.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rakfryta.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2brsqrqkl.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2acgxphls.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyxwajl.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2twhegohy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvwgemd.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nthcvvhn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqngywhm.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2drarhgmr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcygiepf.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmoynhr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdvjieg.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2frtrxptv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpaaekp.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kzopglgi.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlaltpd.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhxqdnh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2quxmrxll.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2sizdnsmp.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhlcptn.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmkrvab.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gctzpafm.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfrvjqz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpioqod.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcnybxo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oergtcfn.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bzottapt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqljtowg.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nskfvsen.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtodidsy.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uueyzqxg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2iihqqzbf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2uaewjbog.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmnraii.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2witatxew.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrehxlp.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2atbsipok.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzavraz.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2usnquacr.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgdoeqq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2esljxznf.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2poltzgxs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyjongd.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rbssgrnb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2shrcfayt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2trtwtrsd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmoubnl.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfeastj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2cxosswwe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwgvlvg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwwkthz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyltddwu.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlfkrvj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcrdymi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzynbar.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlanstk.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnfpmnp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdpsgjy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zljwvpdf.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kidwwrgm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpygenwa.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkudlol.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2sekksbhr.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2obcsqcmo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pawwosbs.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2obfprqks.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2oirowvbt.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xszaypbn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmrpruz.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfspunh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2egikelfh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2coeqvryv.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqdsiiz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyezpxl.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhjqgbw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrotgyz.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ducuolsx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxyimgx.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2glhaqajq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rljfxoxz.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbcdgma.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2liwctptb.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2tssqrxbc.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsklssh.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcpqcmq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nffbumni.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrvzqjb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsoyive.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2axthouic.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyrivnv.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2liczlwbq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfewbsm.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2voftwlfj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzjpqxp.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzvypth.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2bxoeknhm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjtzgeq.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qkskogmg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pelelelb.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbagwad.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhbojsx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpfotfz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxtyzqq.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrytupd.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxyxncx.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tyssvfev.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzomivn.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcuilgb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkannojp.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2hvupviek.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhnpupk.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ncceyqoc.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2henshctt.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwybktz.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2hwszbvxj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2msrbddey.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xluhzwwq.html


<!-- 参考信息 -->