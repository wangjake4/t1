代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qysfxoas.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2tthgnbmx.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmdhbxf.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2grbpwbwf.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qatfwqcw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjicfove.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgqdulk.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yczkbsqp.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2umdcdpaz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtivfjhf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsqrxas.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrygqry.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2lvuckash.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsanmod.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxyqked.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwgfiow.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsrszad.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxqakzz.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afxztaqg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdefxudp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuehskxk.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpfjijo.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2snibfjvp.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2qncaguva.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2meboneom.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvvcsfs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkasscv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2eybeswgt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ooayckul.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2tchlpjxr.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2potuiqsa.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2obpycpfn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dufjdipv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ujaipxnv.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzkaqgx.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjiizwoo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfwyrsz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2eboosoks.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhjnsiv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxvijbl.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tulvpmil.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmajnuwj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ixftuerq.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2sagwhonh.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2edkwemdk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhuhegs.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjzmkxq.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2syeyjmja.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdvakwv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsablck.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uujpkson.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjqiiby.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2aobebnkw.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2oxavunbj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rtidcptl.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkaindwg.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pijetiwy.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrchrotc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uujdzszg.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwuosuw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhbdvch.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpfsvcd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2atwrmwhp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2reyitsjp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2wcttgvkd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqaqkkcn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2uazavpss.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbxyszb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2biexbzlh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2hggroxlh.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgfwxzp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2xypdinzg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2panucrzn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyzsqkz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnqozmi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmszduyl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvbxgmm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2plwysjwn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bolmkkqu.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwbmlvw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2plznlakr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyztatq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtklljt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2oytwxxyi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpbnfks.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2juvkvydl.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2nhebmvee.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xebtmlrn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2cakavwfg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlypxbd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2hokyfuzv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2fvshxzip.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlsmmxt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2hoawwrcm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2anpxcaia.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2uppgtqmw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsfmgfd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2icvhzjad.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbvhnkg.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wisguesl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtvktpu.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lplewwej.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agbnbefp.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuncpdr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdfadcy.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmqpbda.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxcxddf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2cerozwdu.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ljexzfha.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxftvno.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2igewrxvp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rafzpkuj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2eronoctv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oyonozqh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjctqrq.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2zbktfoyw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2edrfunid.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqwlnfq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2olgqoiai.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2olughbum.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxdybpa.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgiycrp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxayngwr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyyqneq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrquzmh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2tifujqzc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuilqlw.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyfblkd.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmkfrsv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2toxejmte.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrpyovp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2gswcxmga.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2eyshiahn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2aazyiyib.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqufubg.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2hqysexmn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkboyvl.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvizafg.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlpldkk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcqqwxk.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2bytvkseq.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpqvqgn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvwlqij.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qtefyycd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmptrpc.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2eaofxihc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2thtvhrxf.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2umnsjpco.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2depiogwa.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2vrevzppy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rchewpog.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfplguc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwuhgkh.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhtvxkk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2msrtblcz.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqesedp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2uzczswda.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2phdynzfg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkckrce.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpctgiu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2mnepqmdl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbprkzz.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2efgqgrvs.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lfiwiosu.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2yioodgew.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdhwzoh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vamwgvaz.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2enunsmfq.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvixwqdl.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhctmuw.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhviwnmx.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lwicnejz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqezvos.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcehxtn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ouopsebo.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlxyxjc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlgfxaj.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2iptnlkqm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyhrzyj.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvcxyle.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2etahpsox.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dceuftpy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyycpuh.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2umpiicoc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqobuzg.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ziktvejn.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdehthy.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnjoqfb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzcpmsn.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyvlhrf.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrauqqj.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2eiusrrxe.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2muyudvyi.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqplnkc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrrvkup.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzertgb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qovoxohc.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuodzqb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkgyoez.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnexhmc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmlfnhc.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkieomw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnbpbof.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfusdvt.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vffjnlje.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2wykijfea.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2luwrywzk.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkghxka.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2dtatnwgz.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbesreeu.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkiyriu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dksfjsgw.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fqedxiyw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhhetzb.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aotvnrrw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbqihmk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdbxuzc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lffmccay.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbtkinn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsvqvpa.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mshmhbrw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcovoha.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2iylydwhv.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2smhcadgs.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsnfznk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgnostn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxkgvfe.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lbeirarl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2dvemmdcf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvtawtn.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtsqgby.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdazmjii.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2urlnwjgw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkhioah.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yywvhwgb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hljlhvhy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2abhuyfgq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwnhfda.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdirfwo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfcbrrz.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ivauwllz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgydjckt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnjwgqg.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bgglmyzn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgnggwq.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgulxti.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bkocxqtp.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hshmuouz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsgwfdz.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2emeoysep.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvjcfgf.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsqujrt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hawxomqe.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2iesqptkb.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzypydiu.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2loegrijj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzrpgss.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnyygnt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2chfywfnf.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wbeoiegj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnfahtn.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oavsxkpi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2stivxfcs.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuyhppk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcrxoko.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzkwwui.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2gefgjcmp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcoaoom.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dlaynopb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzftxha.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjevclf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpsftzn.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fzearxdc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2yustcwtc.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2coxscyua.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnnuvzl.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nghngsdr.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahscrlkf.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrjbwit.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwnhxqg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbxmmpk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrbmyip.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlezkoi.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zejdzsyf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyukydmg.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ryepxlup.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxortsg.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hplguhbq.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjwxbky.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkzvtzm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkdsgez.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qpeaprtx.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zophpydt.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2dstesrru.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyfytth.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ydviainl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuzqggc.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fbksxmhz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2elbxjnof.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnsbqmo.html


<!-- 参考信息 -->