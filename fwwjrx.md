代发 wailian999

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2oedfnhex.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlhntmp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkznzom.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbpelxk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2aononcrg.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2pllgeshq.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kxezeqar.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrawkux.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2eabzlkmb.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkehldd.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrgojws.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2aoytukum.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsddfheh.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opfcocrk.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnatwbq.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmedygr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2cunoiddw.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlwlbvz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iumxbuay.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlysief.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mglgemqi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2sleiwhor.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuckcmn.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2vniwqwzj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2byhrjybb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfjanjt.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cutpgdnj.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhyegyab.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2svxegtpi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqsauor.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2axisomzw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcshvok.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbhxgvp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2namldaem.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyaaytm.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxpycdk.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrsbqpg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxoyeec.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwcjpqp.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2todeyodi.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqabbjb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tymavlhh.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkdxvcg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkivsblj.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdbhgmo.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyrrpnp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2capqpffg.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xupieuxz.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyiiudo.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkqiptm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2opsmvrhh.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xblsczfb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cuznzlbo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2vwypzcep.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2phozmfmh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2flwlqzsv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ungjbqzp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2qucgcnbz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzjjkxd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fygiaqww.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqryrugz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhyckcy.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpsripr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2yvymuyab.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjolldlg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtdfvkz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvutmhp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhhypsh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bmifftqf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjlehan.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lombvzmd.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2elcmxsav.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwjouvu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2flpkldfm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtqpdct.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2icvmqrgb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2abjexryc.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtpqdgs.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmozlgg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqhmkxi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ysblucwt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2yhubojvq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2etynwkop.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeeycbd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjukrcbk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtxothg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iubybihz.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2eolrorzo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ldponumv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmbunab.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2chqrmlpk.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxegtudx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2oqteoywe.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jduyvdnx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rodmpbvb.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjqwlex.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyvvhed.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrgzrso.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2stycyoad.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2cllukgyl.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yocpcjsd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2byqfswrk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxutadn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfnthgx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjegyuy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ohosohco.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nutaxoxs.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ducpfuqt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdborzwv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcujzvun.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2taujsqbe.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dywgmbke.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgmlaxh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwmjghw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjjqwnj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhvosmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxdcole.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2scnpfope.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fplhmbey.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2saodjhgz.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2aegquobk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2eybqtmys.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2attpqbuh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2phwvtjnz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnvrfpl.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xoskhktv.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyrkpgm.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2lqteherq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjykrey.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2syovhpgs.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2gkuilrgm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2npoobjis.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jesabxdt.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2zyeryduk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kydmsjyd.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqbkqrz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvscjmc.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2zemldrdm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtukfrmk.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2towdratd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2umygiyuw.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2dieuznvm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbrjwxo.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hwulmrkv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqshwmsk.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfegapb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyoutbn.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2whapeosf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2epuzxrwi.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2noejmsvp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsqtyxq.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfepqdl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ihofjgso.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2anqhvfdq.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2wtshctmx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwptivi.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbswgogq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2wedzunwa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2avvsdmwf.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrmmbph.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgiknhr.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqozlla.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtuuioyf.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2muxuplsc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oahqjozt.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2devifoyr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwaqskk.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eccnpmva.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdguzii.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ebuxuoxx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrbdhli.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dtaspmta.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2giqxggnd.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yerdgnmt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxyxmkd.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxxjscd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2reihreub.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvmmxiq.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2flisnxzj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nfatnkrv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcjxzzt.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hsuuhmbi.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2syihydbp.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcqujtx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkxywdu.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ntatirqj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjirnyq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2krhrroct.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hakvufve.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlqzypr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfnvych.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xmghhpnp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfbvghu.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lthnkdle.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwqqoyb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2xubvlgfk.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gixdpyim.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxzkgai.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2gdaacvrc.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2awwftgha.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2xfophpkz.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcybdfsz.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mdyrjtai.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2imxduiyj.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fkocvezc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkudazym.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfrlyst.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjusfzq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsniqxi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2waniqrij.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vceqhmqx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxbqyyi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncakhzfz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjrzami.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2siclpxuq.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnsafoj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnwgmrl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjilsbn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gssyqzps.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2latxvcej.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2uleophhv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrjekdf.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nygkflcn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgbagnq.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfqzatg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgoxksk.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eykyuxyu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwpcjky.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvtdjdy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkskyfr.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkyocat.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyksjigb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2meobemle.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecniipsp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2txesnwdh.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2jfaphlfg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzigtxh.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjfezxn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2swirzket.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2twouoglt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yslvxfrc.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2mqksuqqz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxewkvzn.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2doeotxsn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ztodwvum.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkpdkul.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqphapyu.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2shwnjoso.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2uukgxgiv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2atgambnx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnljexoq.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqlnhyp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkydhut.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrdvdqk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnngppkh.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxhnijg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lskifxsb.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqsnnzl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2tubqtfri.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mujiqfyr.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjposdx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvyykbu.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2nowstwnu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwgudiz.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lytrkccx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkyggpp.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzpymzu.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpkztlt.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdbnfez.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2covnvvei.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tamgkpsa.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxjxyri.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2pttcfjvy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsfkdsp.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2wezognfx.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqjbidy.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieviclxl.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpukofp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2pyctxpfm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmyunat.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcrfabc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2roqarfbh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxqdbnc.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tmworejr.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpohwmf.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcthbrl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gtloxjlq.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxcpmap.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2fwoeuqqy.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkaqefp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqmtdll.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2mgljnxnt.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrdyoru.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyczloe.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2eqajbudy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvjxcal.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhdwjry.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2qntncooc.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ghklypmm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qymsthjy.html


<!-- 参考信息 -->