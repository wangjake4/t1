代发 wailian999

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mxedsuab.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhymrnn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwqhken.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2pazqckfo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2knypebkl.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2apwfhwnm.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2blpgtfml.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2fqktiets.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2iltaqyey.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ynogoweg.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvgzqem.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnqewdo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmizldw.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlvxvwh.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkgjpfk.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbxdpmg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2rapkpfzo.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2goeplpep.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nytuyucl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2hvabxvqh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2erjowhrb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgnkxfm.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwyiqos.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqxdrtn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2krekexgj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdrpqpz.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2esjjqfyi.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdhfrws.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrgypkc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxmncck.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozztojjq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiermufv.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgkkoqg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2atmvmyte.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpzamun.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqmsfvu.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2zknjuewk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2tplmqprf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2njejsate.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2gemhtpqq.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2chkkbeou.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hiondomw.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzbulkm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjrdxgn.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhfjozx.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2xhiqjdmh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mvraalva.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfcyild.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2olyrebqw.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqyeyfp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfgbylu.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnifwuq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjnazdc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2zedimjgf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2utfasqab.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsqcnkk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwgycks.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgnpfpk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpykxqid.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kxywkteq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjwhuqj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnixxar.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2urqxtvza.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2punigiiy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjdareu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2obufoxgu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcjrkif.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhrrluo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgsqzdr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmxnigh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vclpycul.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzordkd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxebfko.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmljafy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2iymjrfcx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgcnhph.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtdlylw.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmalxrab.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jpspgslo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkvppol.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2cquttbwr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnfxaig.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2zofsxhxi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrnhlcg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yemdvfpu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ceifmajr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zogyybzz.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkuotwy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2cqufxndm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkewcrvf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2mqimkhpr.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dupmokye.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2oplstiya.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzdvysu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2srriindi.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2edutxzsi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwphzbg.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dabuagds.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2yccdpjgt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2juipvqnu.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfrhzhf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtbqurc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhgbxga.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnegjtxf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2nvedjqsz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgmxibw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxgasup.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2exxpajby.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqqjfck.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsitylzu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2swbxbyev.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzuvpbmj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzrlsdj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2lawlwybd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2benwnamr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfxcmmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbpbsnm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhihumfv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jybntkxh.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjfnijs.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2lnctxkci.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjfvcys.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmauwxe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqellrq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqypucr.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2lphsycze.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2wldelqmr.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2kakjxpwt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2llvrkqoh.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2gqidxhfh.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwnqpxa.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfizacck.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbatbzaw.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhhsujh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dexfadzo.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fifxincc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2efenchyy.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcefzan.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtxywzh.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2eepjmgzc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfznrlj.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2apoojtgs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwelrqm.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sntednjz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2upvswouv.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tryalklp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qenohfpi.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xulbhjxo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2faoflijy.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2xewoaavj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2chqueesy.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2quareyen.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2xckknbcj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2regkhwtr.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2xkibjdwf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkfwotb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhqoshz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdgzfyg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwdvppf.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdixrqq.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2osfvyoev.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2sokkekfc.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgeklmj.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mgazjdyl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2edictald.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2thmpdenk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ucabiyld.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lycgnufs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrkrkvn.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjvjfyb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ficxjzop.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxggbjz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztridkkh.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcrjnku.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvfrute.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2okkmzrfa.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxynoghy.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwaqvon.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziizzvok.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rmalbahh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmlpsmx.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2yavihmbn.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sczblghj.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxyhnct.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2niswllwo.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2crsjlldr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2klfmzkem.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjknajn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdygrhrt.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlhqpwr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqwhhtc.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2krnutnht.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtwrukf.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iotwmvse.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqevwih.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbecevd.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bawjflkk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2xypklzmh.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjxepfc.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcxsabh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2htmdkuwv.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aczrfwld.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmiwrhi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojiracon.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlxkfkh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2puolzdli.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdsiqwb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2esmbxxna.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtfovzr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnuetvrz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwiwlzqt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2bfiaeeeg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyemeonh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsjmfmp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdtcllw.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aseohror.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ujudhfke.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2wreeavyc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxijcgs.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkinied.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2tazuwbir.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuxgpev.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2atazghsc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyewstvm.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpbjpfn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfoqaywh.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2izhimaxc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpitpyf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uchgfffj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qidcusfb.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnziayz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyoacugw.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2snzptgdt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2csgklyix.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwwcelv.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyliawe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfiioiza.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2onldwgfg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qrivpyzo.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmpqvao.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2miyotvrt.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzjziqb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fanoenfc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qjayczng.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpiyrai.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhbhtlc.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqoayzw.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqakxoyj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2saznkdme.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxtspbq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2doeccpev.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2owyvusmc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzgjtta.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2glmmtdjs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpjueiw.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvirfxu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjepgfap.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tolsoebl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqehmtk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhdndic.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2pztezplj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzxxffz.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rhiunhxz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyrucys.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdzzxny.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjvxfaw.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxpfycp.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2taffqbig.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwrygkr.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2sblqpsdo.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2olahlyvg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2joavagsr.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2pohapdds.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxnernv.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2kppinczq.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cccucpsq.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbokcdsc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2odgoydof.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2uydbykmz.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pkaykzfp.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2brnrgfom.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzvpkrf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2emezplds.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2enevhflt.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoijyscy.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsyjdsi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qasmbzyp.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2otfcfwnn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2halicnto.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyaxqys.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxfgroz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2zuphexhq.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2idnxflyl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2znghjcqk.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2aeryvsih.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2drvceccq.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvkyngq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2gncatyei.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zjoquymf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpesysb.html


<!-- 参考信息 -->