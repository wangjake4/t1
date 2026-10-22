代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jehrxvwx.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsthjkx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jikvewld.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxyvyqs.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmzfigf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpiqdxu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2toplyyko.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2twcnqxpc.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyerdbg.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqnbtkz.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2kablrtur.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzpykld.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfjmyjq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2itecyhpc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2aafknaju.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqlkvii.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uznmgxzc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eanepzwk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2vahcmouo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnasbjw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjuvmdz.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2eenphltd.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tkooilcg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2abuxpzhm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2emzulxmu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2nekrtdel.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlembsqp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2tifvpzgg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2apwmtkvq.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkwndhu.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2aibjkiab.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsyoxvl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2oealpfrd.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zedopemx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2naqqzuqz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2atglfvrs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dyudmnsh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2rdatzxcz.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tckzsfin.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxoimee.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2seutiojz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrhobln.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nallhmgs.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrkuwlx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrkhsxn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvwihqo.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2cicoakdr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fddtlyii.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gwobamad.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2etmzmjpd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdbznvx.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dtheswpm.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2oojnenob.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2frzeugcs.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2natcrdyb.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2scugizpf.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuyjmtj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjgepgc.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2trzffmnd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqnqdib.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rysapckj.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2qpakzjqv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhmjxdk.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2crwrjuvg.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsozpxp.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lcoaygmp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lvoivbaw.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfoejpu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwiiythh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2eqccyamc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyyhafm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hovgojoz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ybftlhje.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2bowlphtu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcayhcou.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cytacsej.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bixwnyvh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2bysbecjb.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzctrmn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwkhswl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvxqzth.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcmabbq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuwacki.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2offnimzc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vbybveea.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2axosteot.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2htgjfpot.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mevztwha.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2yttgsjhn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xnclqive.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlrickm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2afjuzshi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyywmjb.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbjqicf.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkmxnxr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2htnhkrkh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2khwhtepo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2sjidqqmb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2xgruerow.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2zplmwjlt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lijwaaep.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2touzqhay.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlacduai.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2gfeqpcau.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2uadgdnuc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuldbya.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2zonsqdbr.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wddervki.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2kfphgqkl.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2llnhxbcq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oeydbyxs.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmmtyso.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2udcuagsq.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzndxkso.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2bscusepv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvsntkl.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbmmzju.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjkrayf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2luttzswo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbvfgus.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkbbbug.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbrlhfv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2spllctxt.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwfobal.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2dibyazpm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqdphkp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2znidwqgn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpepzhux.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2otoxzmuo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfiqhus.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpmpbxd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2dsudtfxs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2odjsnsvn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwagyave.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdqkuyt.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2thfibyiq.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcvvguh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vaewdsid.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2favkncxh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2xduyorxz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2bipidubf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdeljjr.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ptocgfdm.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnckyhr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2aezmepgf.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2inpjfzud.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnaepfc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2njlgrtqk.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mulbzchr.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvjhcna.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhspalfi.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xntltwqh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2isynxqlf.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2yejcagat.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2loirhhvn.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2vbverzfw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2popfiydr.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2wddmuedt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpccszel.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdtgmlc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tguaoiqd.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqwaain.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2oupfvtce.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fffuwnbg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2exwdensa.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2eimamptw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzdijno.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ghieajni.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2texqxvox.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xifukoeb.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ulurnhto.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2onpouqjp.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuqwpaw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2igknopdy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfyrscd.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2skxypclr.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqoutai.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhndksp.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2srptixks.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhxmmqb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqvivrj.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2asbndwmr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2gspuchuq.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdhhoyw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmbyayi.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cftqofsd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2covsufkr.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2irwymnwx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2irupqfts.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqgdyfd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhctqmr.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2nhthovac.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwaeviq.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lprmwops.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfauhgd.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcusmme.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2vldezzrs.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2phliimaa.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2javsabna.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhqpbqv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2evfoaxyd.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rmoapxbb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrsgzqr.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvycvqr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hieeudsd.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxktjgi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2axatzqdo.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2afoanzye.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwbxswy.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgxvrum.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyegnza.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzkhxds.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkvzusm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsenrmyl.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhzroei.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2szojdhgx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2cggjigyy.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwqswzi.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvdqrwa.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2benpzrwx.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fsivrfoe.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvszdmfn.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iunbanob.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuddvnw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2knoxmnki.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcxohcm.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxodkdj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsehgkw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qssxunss.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2smpqaypa.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2azljexmq.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxoypxr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qaehadrw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjzrave.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2elhnfqts.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yzssyzfd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2miyjmgwp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2okavtysg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mxeojpwl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgdwdot.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwpouqu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2jltamntx.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gegggfqp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ackjzlqf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xbefmszm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwyemzd.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oppogmjf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdackaa.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mazocpln.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuncwng.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2medloxus.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zavktrez.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzqietn.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgviwpj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2shhixrvh.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpkhsyn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvyheah.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2kyujepob.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjorkqd.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rfktmsgy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzhtpkl.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxlzlob.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2qylgjkru.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwgkycr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjgxjrw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbzldyk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2omsitoxy.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ezszsiyv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkdqghb.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbehboy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsswkwj.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkfayuh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfimyly.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vikfvraj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2aftpprea.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrqagzw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ysovqedg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2grniexbx.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2amyqnshj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2onsgxalm.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vidhotkp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfnncjm.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjypdai.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2orbtqhhe.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzffgbi.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssarxmbj.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yylmudld.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrwegnn.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxoiapl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2hilvmgbc.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2knqlhamk.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2obkpxuzy.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fadfxkik.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwtwfpz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2znyndlnq.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxtsbpz.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjfjbpt.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2psotjyrf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2wskjnpfw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qiaeaqwi.html


<!-- 参考信息 -->