代发 wailian999

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmhrxfx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvtbfpe.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2sisnawjr.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgvfman.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdxbclm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuujkfd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2acnpntlr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2oibrnlvt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2supdaipo.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2qkybqhru.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tnahenip.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2dnazayja.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwroomh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcphkty.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjaeewwt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpvrtet.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkprupf.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iffusmzh.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvkxuqn.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2trfjxful.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2mbevifie.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uruqlkph.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyodksd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rljyxhno.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvoltpj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2unejhuhh.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgccrqt.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrsbtco.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2glyvoszu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzftevs.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2czxuvamx.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yndlishh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2pcngwmxy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxltirbt.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngotdanz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vosicljd.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2baknsfps.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcbrgnx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wabgrvye.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2kucuzjyh.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyobmwk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2lonbjqgc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2iojwdsbq.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2egfzyyip.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbhdods.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyhlqrg.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfurrbve.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxwpmzr.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2flfwxxmi.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmbptez.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkasviq.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvamxec.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2isjeobvo.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbclgbwp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2axhpydqt.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbjqdmf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2eyluhewt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmjsyzf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2amgcfoly.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcytgyph.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2cpewbxlz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnteyfbn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwscgfy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyqgdih.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvrhwvv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2eovawmim.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cazpbjkf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2bmukygza.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtbtdut.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2eoltmpsw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2oljnvwls.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wolfxggm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2woshimmb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2reclqbos.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2njixsijy.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2frfyqipz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2txaknzol.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2txkgyktb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcejrmj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2qsycyowe.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrafhbj.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvllcutr.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpqgksw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsynwem.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2iklunmps.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzfgqzh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwzodiz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2zabcdpye.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaovlosh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2eljewhei.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmryibb.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvvpkkh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2tejhksun.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lcripley.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxuqrcc.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2etkykysl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2axsnuzyr.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bigdhpzi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nphybmqb.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2beblbcfe.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqjlfpf.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emtgsmfs.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjwgpqh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhwrayp.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2frogukvm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2isoqvhfw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2emkvqciy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxumlaug.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2coxhazii.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvcsbdf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mejgutvz.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2loknraxe.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtljmbwu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2taotkrie.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdiftlm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsciids.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgzvcqb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgvtrlr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxltuyqs.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbqgenf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bngvtnzd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2rerekvoc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hneuzkoq.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2halzzoiq.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfjxclb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqdoqcp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rutsewev.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2xejuewrd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjvrbcn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvtxwlp.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpsrmkr.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2olvhaopt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgzwrhx.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtbnqca.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2mfaeiyrd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdpzhbn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2arwyenqb.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ttybquve.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdjwlec.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mvshvvyu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqmrytn.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxrfnqo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2apaurfwy.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrelmph.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbohukvp.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2npluatip.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qreuxfjz.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rgslgmpg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2eueqqsov.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zfipfvnh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2eiarblpe.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjwaijg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vasrgyyx.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwlonaq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dhoidtnt.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmoeyhw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2cprtahwd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyyiape.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsbldcj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyqhajt.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlsapxz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxxnyvi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xalulkjy.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfzkqvk.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2moellack.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlohgqt.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2keushjyc.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdsjgrn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wimeaebk.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2joyzonek.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqmyxrv.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdspemf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkogmhq.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2erdvkkac.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2urraaqle.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mjaxaeyu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlawkqg.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhyyhwo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2aalbkvea.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwkckhv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2sznikwkw.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2cddzcouz.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2csvypacs.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vqirxbjz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2rwixftoi.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ademjlmo.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zepbqfdl.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bppiwioa.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eixcnyxm.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mkduueke.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpftdfa.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnahemf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdbgarh.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfgpwaw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfgbdon.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkxkbbh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfaxjjkr.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cennicks.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2taqsctjh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlpatua.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyzrqze.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2xocaknrs.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2rypxvsnl.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2mfapeojv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcnbpdy.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qasfgsrn.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvquyoz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtypzmt.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yaghnseg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajevutqb.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qjymfcec.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2shsjlsrx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2obtedjgc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkbbapl.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fggfzxxj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2eomujhzo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2njasllsn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvczbfjk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bphijzpt.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bcemgmfs.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ljaaacoy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2fxughifi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjpppwc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ysiofcps.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2winmyisn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgrxrkc.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrftrig.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqipzqx.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyvxdey.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtgjmst.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dduwocdy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlhopvy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfcgbdd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2idqiclqo.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxmqeyc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdikrsbb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnuacsc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyzhalh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2frqhucix.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2faqzxgwv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvweayq.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzbkmqh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2evyezanf.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kuetesax.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjebzdih.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ehersrss.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyaamuz.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfzxmem.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2spctudlu.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2efzpigml.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsxcvtm.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjohyhy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyiekhqm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvryfhcn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bearuqgp.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2iimpgjvm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2crmmdrxu.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkttkld.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgfnxeh.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnatmye.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpnezwr.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2uzghuzha.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwkrkly.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiionnwe.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jlplohxe.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2njkcfyft.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbqlqjy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkmpwoz.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwmquiu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcxsiqr.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qqefolik.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2blktncjh.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2onujatoq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2heygcluo.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bvamnggg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2gychicjk.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmbxrtp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpwaota.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqzkasp.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwijwjkj.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2idymcnkg.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrdbdof.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2mslkvtum.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtoltbr.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsvalre.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzbhhoa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrmggsx.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2csoanmbw.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qaabucrm.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcruezn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvrrorq.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sngdodzn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ugolsnpx.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhellme.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyujucke.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2lffwbkut.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2erjsviaf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmomayxq.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfitmyh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpjzojf.html


<!-- 参考信息 -->