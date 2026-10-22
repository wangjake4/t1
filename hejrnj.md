代发 wailian999

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xugovfbc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnkzozn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2zkoqfrrt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2fltzluef.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcvpjqk.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2cagfopcv.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2anvvxffp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2dvouhoxa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfhwqor.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbsqvus.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqyaxrz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2atzwqsjl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2znsuygeq.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgysdpix.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bgedrhdr.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2lworfaxi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ckiquerz.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlgeawg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzdhcwu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgukqyc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2akcthlcp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2iynlmeyj.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fanrecxv.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2wjiesnkt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmvrrdf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2acntimpy.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfdcfqb.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rodgzqvq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ueyionxk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpaehycd.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcraisnv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsonizxe.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qnozypxm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2xloaszng.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvwefri.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmxjdmi.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vanfvbhq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2jdndwbxh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyjorne.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2qemqpvmy.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2yngavhqz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvtfvyc.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2anzccwpt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlpmseu.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmfubkz.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2dscrqpqz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kmipabtv.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2suqntfbz.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjdclfh.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2omloauja.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uwovwyyj.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lfseabsq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgaxkrgz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2zailoykh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2mohnezfz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbkdqpt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2blexgyup.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzqpxzd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2yecsgrsp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2paquktmx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2znxmuxis.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2cyiosred.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gstierdu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2oscmpxcn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2yujizdin.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqtkpcx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bffvnqdp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tanluyey.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdgvdwi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfcipjz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2unfuhtkq.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ashsrqev.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2aolggxbn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxjaway.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2yamszykg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bopsoaqz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnioeba.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2uckmcung.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2azcusyzm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqvtmqc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2yetsjetk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2btlrsxnk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbwyfyi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrlbftg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2euwuvufw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpmnblg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zigarhxr.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2eelrrmzk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2jdipbran.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jaoitbtb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbhugtg.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2djpntcnl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqlowai.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvgrmjs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpkguqk.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ijncnunf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2occqfqnc.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwqazuk.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfoutvk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2bprpuexe.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2auddappm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2elbmjqld.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sudfphup.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yihtcxtr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2iaelcxre.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2minpainc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lefkkoym.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzrjovr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2eetduqda.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdolump.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2yobrzwhi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxpgemw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkjkqry.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxbgebx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgziafe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqpnitd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yljdlomw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2zusgkrbd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2utuglkuy.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2yybccizb.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2zfldccgp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2dbejvzdx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2yigsjwlm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkeyfem.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvzysia.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjamkwyc.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2jccrqaoh.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2hjplbasx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcueeon.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2eohvbfpv.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2fhniznpi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyarnole.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2yshgfkiv.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ilktygty.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2apdqbegm.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yepymmhy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2waxpznov.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkggpox.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnzbtfc.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2lcasmzyd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2huejftly.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2aufkddjb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbggmvtj.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbisieg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2esbaeofi.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zmphcjwy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhqykwm.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2itjmpkpa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzamaoh.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfoctyq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2csaozdqc.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvdsaks.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2urbicaee.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkmyish.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbzeivr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbmqihw.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2djkakfid.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ljeszrzu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rriqbwaq.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvgcmhe.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2grnnuiqx.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjhbrvo.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrebpjlu.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zderexum.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhgnujs.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpxrbtk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2zqeenpcu.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2avshxkaw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvmulzd.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzjwkth.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pukocayk.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrikpso.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2betbtgqc.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2thdcuutg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2skmilgmw.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2moqrwakw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqoqliy.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2aazcrodc.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhmzuss.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zbeswiks.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2lldcsypb.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvejmer.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wezhtcer.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2duuworie.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2floiwwcq.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fawvirrb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qysghgsv.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwgvxyh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkowjmwu.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuxmfkj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkoouux.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cupfhtac.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuejbzt.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpzhbpm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrzlrtv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2cerlrlra.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvjkbex.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnuxqaap.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2odgowjxl.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2giexkqcz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2pxupbrow.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2almwszgs.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhkauzb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmtfmey.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfblnpy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbvtckr.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvxbdzy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcarmfs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2aljrnulx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnwggdc.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbntlfv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwkzjza.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrahssc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpmengj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwwwkmq.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwjcgbm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhejljz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2trpoltki.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2blitazhe.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnvfyvt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2belmbiqg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhesyfod.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wabxzitr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmembtge.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tykxjaio.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2niycrqza.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iklugfps.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2snajfufk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdmezdz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mspovfcl.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pgloamoh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2zczlayre.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yyugtppk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywothycc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcyiqxe.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhadomf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhsrmog.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2puwqknqp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhmwpgm.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqoapur.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmtwiqi.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpfspql.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzailhdh.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2shcnrivq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hbihdydh.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2kmknadhl.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jadfpkoc.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdysefh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnmqyea.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnxpjsa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2blppwwbm.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxxqpcq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpfgjco.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsmqwxd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2okvhzvok.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ewheunfe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2itwdhvon.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mddluyxp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2uahbhcae.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqfrilk.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2acbtpzee.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuabcruo.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2dygtendl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwawczkw.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dieuospz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2unbobfif.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsceoje.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrkolip.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlclcpm.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvbpeoc.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wjubwlwo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2erffkpea.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2awxbjcuz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2mafmlqds.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpvigjf.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhypvmx.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgleeari.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rovbznbp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jzaadtwd.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2updbbojk.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmuybif.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrucgxz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrxidau.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2axybslzk.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzewnmd.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsijtps.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtbwrax.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqonlic.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdkvgwj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdujiga.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcwaxpo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2idboizpn.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fddaaean.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2exvlnpqi.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2obxhuboh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2azkripih.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ksesoerz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdeauzu.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fufajapo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrlkgdl.html


<!-- 参考信息 -->