代发 wailian999

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrqppic.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2czqionhu.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxuatjq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2jzytmivj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2jaeozipn.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2smqcfmnm.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpexrsay.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkbporm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjbnmvq.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpetczf.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2elbcoiof.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2umibyzoz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuecayu.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2drqvevue.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wggrraue.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmiqasn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fftwslih.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2tazeoxac.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcpnmbe.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2uwihxnen.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtapodas.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqxqudz.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxxlnuk.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhamytr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuuftvd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdpeavk.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2metbivwt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oypokskh.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nqczmrhy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcmnmec.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqjxdoq.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxvfzaa.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtosnvt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2jpslrdlb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2lemzlhgq.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ivudkyab.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2aotpcvms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkmeqjt.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zsprmwwq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eofjuysb.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2syflopqz.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2pxaxpqlb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2btaoxewt.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qujvfixw.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrrcmvp.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yeusuvgr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjsyfjo.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmdggks.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivecropx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2hhoqlioh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtfbohi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxagnxhk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2azdhorjs.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2aiiobidu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2scxdopjb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2afqfojcm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpoxactc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqykskl.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zofsppul.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2saxlmfpf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2prwaldaf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnytebc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdckceo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyerlpqh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzjujqo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsjvfdn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nitshtpc.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxxrgmh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2omwvtnkr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2quxfxaiy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zaknrwri.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2otfjzimq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwqjeoy.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjhivwq.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2comwrbjy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2aguwstma.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2pesggpra.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsqfrqn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmyhcjo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcnklgi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2waxvbuff.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2wakpxubd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjijebe.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyrrxzi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2mszqyrlu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gldgypbg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjtlhoe.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsunrbn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcejtki.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wpaupcbi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2phatuysw.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxcbres.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffafdkgp.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjowcmcq.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hfoswlam.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2mobzlfmr.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2chfrybvl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wjskfhpc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxtbwkj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wezpjaap.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtfpxco.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcbolsp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqsqncf.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2oogtaucm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2aclinbjt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdzuwci.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2fptyznup.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfbagrv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2cssirraf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnynanx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuboare.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2srelpcev.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uilpdfmo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2qplmsejs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uyubirnk.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2utmbquqr.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdvayda.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmftthn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2prfbvpdy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2tejspizk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdxjnxc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkykohjy.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2oolirqdd.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhmjkok.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xigndile.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zzskodum.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhhgkhi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzgkucz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzprfua.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqrefce.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvygroto.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oiigomrn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2egardzed.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmojoiq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzybwlkg.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2fvitpbxn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxfsqtl.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2zecmehey.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrphfjaf.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpumhvq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcnzpha.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2evftsddc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lttdefsk.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fdikcyhf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtsvepu.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyznrhl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrbwkcf.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2nutpjvbv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdxdrjh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuxnxqq.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2giuqclrv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vlstdfub.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhilhjj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgobaik.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpotjfjb.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzhizmm.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hegathqi.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgifwqb.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdhwumj.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2viacbwzs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zatrjkpx.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tilqycob.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjnyqfn.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgafmpg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtluwwl.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2udhizdko.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfnbflx.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2afrjcgds.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwezmxjj.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vylcxwja.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjmcign.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2xgssmbmf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2adreoltk.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjqucdv.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhifnrru.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqtdwpd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2vypjwrbo.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jeokxlfy.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnsqymb.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjztrnu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcagwpe.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuslyph.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vajotpek.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdmsxyc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2glyyzwrr.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcnvwmv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2urjakwzb.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qbknkjpu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2grgmhkmp.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvzziye.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpjwgpg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkikzna.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ookleizq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygivjoej.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2xeupxpql.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2smvzsbhq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzlojei.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdwavxe.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vljwqmnn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlolxaf.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gayebsst.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nksflzag.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rhefdajp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbrzjyw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2nswftfne.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlltjprn.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2igchdfag.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2lacfhwxf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnaspob.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuoioof.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxegyetn.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkuehnq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2griinulv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2egjsgjgc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqtgwzm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgsfraw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpbwlmj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2epzdfisx.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyenlsh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ithnxeny.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2esjyytqr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdljbrqm.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdurcdv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2aanoapvf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2etvbrima.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnxakfi.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2grnjthmi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvwdzjt.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbpnmov.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2kettxixk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdkbegt.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdcyiyn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2emnkwshh.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xomlqcji.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qssqzojt.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2burchvew.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzslqio.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2npvjohjl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rngeppca.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2luzijtcy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2slfgmqzk.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2mmixcngj.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2bacorjlt.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2upejzawu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgdlwjt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nskvigkq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlkwqde.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfuesby.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsgbcbb.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2itoxzauc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2axngrdwd.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2fztitbmg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2exfnfcrk.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qttxbcab.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzsjkqv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqnnfzq.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2klvedqaf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpekcdvt.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrnrwgc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmhldgr.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2svksgkgd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgllzga.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvqatdm.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxycqit.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vewzocch.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2aluipduq.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2psxaltlq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqbtzbl.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2iejfimxl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2moxbsdrn.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2nvngpoqb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlwjnum.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmiigmuv.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsslibq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2wumcehno.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcqzllo.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgyydyk.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hmugxgwa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjqiqzp.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpedarc.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2koojlydj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2uauzojnv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzjadhr.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjmbpvb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjcpdzm.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfobkhm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvztgbv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2fblgplac.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2toiufhor.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2efzbbvwj.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2hklulgpg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2znmpkpqk.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgdftco.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2aegltoqw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2erftrcik.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgqaaxy.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtjpudw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2onxojpry.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aybnbmsg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fceviswz.html


<!-- 参考信息 -->