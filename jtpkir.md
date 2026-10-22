代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhdrahi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cxltqzhq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2kitoaigl.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxubbdf.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjqzfft.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcjiuei.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2duamsahz.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2niextxtw.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lenysmpr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmojuawi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wbquylsf.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mudcogxe.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ucllwoie.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbiabdp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmrpway.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2gdidpnzd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsskwmk.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkplmvn.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfluggb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2bchmvngs.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2oflcnncx.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmievhn.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrdzwti.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbmseek.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zowevzck.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhyndgv.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tsogiaqx.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjrzyjd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2oaaybkyh.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpiatepa.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzplscup.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2sdilnxmv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgjbqih.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2actevvrh.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcsmwdg.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvskaro.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lttrzzej.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsxmpxq.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmjoozz.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzdziib.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtpnyfb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrulanp.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2efakncor.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2omtmufqt.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrnkfpj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvhlrsf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2acqpnxnw.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2rajosuxy.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpuvpek.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfhxvwi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzpltqy.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2qgorbslg.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2uelwiswy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlgrqtp.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2utnzoelj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxnrlas.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzhxmqb.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqbkvvv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmictrd.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdimicdb.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsaxkyy.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdmcmin.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwvnvbd.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxjykgx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hofvhuhm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjjydkq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjuqzas.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2volnupzd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwttjzk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfqkhfy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeiqlizs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xngjlvop.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cupphmvf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpojfyd.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyatbpn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsbciuc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2odubkgvk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpybgkl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgbietp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2biqkpkfs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ibftchpv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2semzvbye.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvgjvyu.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fchckegu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2okiasuux.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qronkcti.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcfzpbd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2exduugqg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2vidkvujm.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpccscxj.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zrytkjtf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2noslmtxr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2vysqodor.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2aeejnbcp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2maiciqzk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2hycomubq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzztsldv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbpzweo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2obitzvfb.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2dfoykdfz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2bksuaccu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbxicee.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2fljptxcf.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czphswta.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ymukbqek.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gacnbzws.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzdjsrw.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hraauzlk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2lanqvxko.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyovfvg.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfsejpa.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2npjugecm.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhcrqos.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2waeiforn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxrlveo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlermot.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2linowbza.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjcsggc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgchbki.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2sacowmrc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdqsspa.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2keehfely.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrmtqow.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuolfovj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2okshpxhj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2sokmhiwz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsilbjk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ibghgaif.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iptcqglu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdagvxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cmddihhx.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rtktnueu.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2waxwnzws.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2urwpvygg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2avpkcahk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2cugaqooo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2fawulocj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2slldhjnf.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdhggko.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2gyimfkoa.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdiqdob.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2befhmpuk.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2igmdlxqn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbeqctqp.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzdtwfh.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcumhqy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2finqwwjj.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrpeccd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzismidl.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2yofboxcq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2faepmxcz.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2micwxcte.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyyxldee.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2aeebyrnx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbfeqyg.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2trehvwrz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hiskzvat.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2azkhkknq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gechuryf.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lzyomkcu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvrahis.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrhugvn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gjoghgmr.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2urrxxaap.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjmnlvj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2hrguahuc.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbbmeio.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2btkunurv.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhuxlhy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsasevw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjnixte.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wnprfmwz.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbkwthg.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnokqvo.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhldpnak.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtyzneq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2buenotiq.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrbypqj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtpdtzz.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sopkefvd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2brqrwdpz.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bqujtgdb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtolsviq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtbfuqx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xypjgsvl.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rsagbqwr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhvsdoq.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2onsbtcxk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2servdoia.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpgluwg.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfietnc.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ogejebca.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2fxemmlnb.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgellcw.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrrpdfi.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2iznaazjc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qojhuuxh.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdygglh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2edvalzxi.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjyvtfb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qitndvre.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfcesyk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvhxisq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqsyzki.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgcsmwe.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jsezydxb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qahlroyt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2caofiaez.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfdsqsj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwuxlyy.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2nsosotvi.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2oagipuox.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2unzkmuih.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2blfwabfm.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrtkiat.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2khcwjhiq.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxjwssc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxalgggp.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2frefbgan.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjycmmxt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2shigkkej.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwmupuo.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjzxjqz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2svcqipuo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceylmabm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2nviasgkk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwivwttm.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkcoayf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxarnrx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2unvcdciw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2svjkrtjt.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2smtqxdbl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xazvgrqo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2akdnckmg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrvwpql.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnyqtfh.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdybvvl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkyzecyg.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iohlceit.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnismbn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjfyzru.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbvvbjl.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uonsihsn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkitsgzj.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2osaakttz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2biypoprl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbrljqd.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbjghrl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnekoben.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2aubvedsz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkgafqh.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjqgzhu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxxelnt.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcwmfns.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvnraam.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfxgpji.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2aeoumszd.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2cygokcif.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjtdzzf.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2cccbobdo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfnnnbf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bxuusukx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2stzhtceg.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnirzuk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbinzktt.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cvyuhibq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2orylzikb.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2jxiayucf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxbrcmu.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2geidvzfc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2vavwiiml.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpicxsec.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxtlpvn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdcntop.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtqnosi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqawhqu.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvhwqwc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyyozps.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgtdpwy.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmetiiq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2esrbwopz.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqautzx.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnmypfx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2puhpeupw.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnexucc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2rybvqekf.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzumwre.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuqobwt.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdllcrg.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2agknlwhq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2svgiujum.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtvwktr.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfopvaad.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrntmze.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyqselo.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkzoezj.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyezmgpn.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2fowwhujs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjvjiog.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuctcsa.html


<!-- 参考信息 -->