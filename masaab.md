代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hpuuxdwh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2opziqsjm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2emchqvid.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2avrqxrse.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mfngbqzq.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2kogejvua.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyqigcn.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2hltvhgym.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxeopxe.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kditeqmo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfokkjx.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2twksmtfg.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2imlkuwsq.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2cilpyghr.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2xckrelvm.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2tbexulab.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqoffvj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzalcvlu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpodcqh.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2txruxbhn.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdhznnt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pinledcs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2vstpldwq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2llrzujyi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2wwansyig.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdictzo.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfdxitx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2rarqaece.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2gduatkbc.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkvlfgf.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnazxzl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcbnstc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uctkcfgr.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qngobqqt.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bidujqnz.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2drbumgph.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2azdrjqen.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkdxits.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmaenuz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2uplplvxp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2otrataob.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2xenpaoki.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipucvigf.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2irltcjvz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjegqtd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2mokabcbm.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2udyezprx.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2anrgnmig.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzxgrhs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2yowwzysf.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpnlczn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpuffrzs.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsqityr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrllebr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2farhkwqw.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzaoqvy.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ertqxtba.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwmudzh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfaqtoa.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjuxsdz.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqhflpe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2csvwfjse.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ekucsypn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkhxpxu.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmzwepj.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkjddka.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2axfrhzwr.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2puedvbjy.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqroyhhn.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ithnbdzc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2urvndtni.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgiqnvo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvhtgfk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2venyjnug.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2etoizvss.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtullylh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2kusvfzfo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmvoeba.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2titmhbyu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kixethfn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvhkypb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbszomr.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlfwwqu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2mihcotyw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2zteibywd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbznzmho.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxettshv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwtpqhd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjeaimr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2veosqpzl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cogqgmbt.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yzndypnp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvsvasu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrvyuzy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2hcasaqke.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuejeyy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2fknmfpni.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2bygkknft.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2loxgdqwe.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2utfbgnup.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqyztqs.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2urkmfqmj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaseevm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2dtljrzkr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnrhhju.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyldgza.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyapcdm.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbfiekt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2kmthyqwj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2yglroael.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2pydhthyz.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cywtbcfr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtjbghk.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgejqrk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2obhjcbdw.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hskmdseh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2batfxrsk.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtloleu.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2huxdcclw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxfaxch.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfarhmu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxqhfrr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qmajoqvz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdmjfgf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2fyslwbpk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vtarbpgg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zmephnpu.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdvxdfh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2biqtzfnf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zihuxhrx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnrdhzl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qflzyomn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwijctf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqheyne.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2awezjljf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2yiozfjdt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ladzlmuy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2tngpzmdv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzsifus.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgromhb.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2bshgfvbw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpmnrzc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2drfkqdfe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdzqhyz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgapaak.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyuabfk.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnutylw.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2nafluxni.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jvanpuvu.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfusykm.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2flkthfif.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrsnhvh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkyqqdu.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpvxtal.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qabkbyfm.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2urjaapgx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bulwjxnq.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfjkimz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2txjteowg.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfwqnih.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2leiancfu.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2rywnojdx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fggmywnt.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2coisliqp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2pffcxjaj.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfigztm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuorgfyo.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gorvjgry.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2carvkorn.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcnzhfc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfrzsoy.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2btfluzuo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2sjytaemd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlwyddp.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbriebn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gprfibqu.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfghtaza.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdhnvww.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyndfdwj.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwvpmah.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhelpcu.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2aghfwawp.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2papwjulm.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2injkxrup.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2labuqhlo.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgdvldy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2mwavarzs.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mzitmkwj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgttftnv.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2njpdwudz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2izjjnvcq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvcysvd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbbydeg.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iazlhhae.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvxwutn.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnhhvmm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjinwpzc.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2doavinoo.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2elekneeg.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2iggqhvdz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2xsplbctz.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlgwcjh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpmyakv.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2sonkazxe.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yngqmdcs.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvvhmxl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyoczmnc.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jnusvlzn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gepxliaj.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ittuwhpo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vplbibec.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2shvzomui.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2piryqaaz.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmczgdz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxbdfdf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2elgfugnv.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdianeh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxucdxse.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjgyhjp.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2upvopjbb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfpesrb.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxkfjmo.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sofzfqmb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2depupuhm.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pugglvtd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuinfve.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxvedtg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2walaimza.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwcbyzx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdjluok.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjplyvdq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2kivjymlw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bataibds.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2uatgnvtm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzhsyyz.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rcghxitx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2koaaubhx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjphmnh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2byoksmmb.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2efqdeefs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuyyrbl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2abzolwsh.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtscscc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmosevau.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfdgdqr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfpztjm.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvuisxr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdcwyut.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmpadlb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2npymcuyl.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2perslkwm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwieqagd.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nobcckzo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjziptc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2sctiupjt.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2imyvnhrs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2drzkbyqj.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rbawkdzf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ebififif.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wemumgty.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2swiymwuo.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2maftiygj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjybbqrt.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2htprxche.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvltfzr.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2npzwisqo.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzudnwo.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnpnfug.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjrxvoy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjogqobj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkcqugp.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcljzvn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2npjxotzd.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2syztcmqc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2flekljvy.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmcfxsr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnyvczs.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hydvblcs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2qprbbtex.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrltlcw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzkehic.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtzmuxj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhvlxhf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdocanc.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdauxib.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2griifabn.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpyvthn.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqkknec.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bwicuvzd.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyrcwzu.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvyvkhu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2phvwsbcq.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqfjdwp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgsmfgf.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2chzjeisi.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yggfhqzn.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2irgasdwd.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2tjocxqal.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqktkbr.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkxyvph.html


<!-- 参考信息 -->