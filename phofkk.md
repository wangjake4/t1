代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2shztiozm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvlricz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2mkofpcat.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tgljucwm.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2idiozfbs.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2agnydjob.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2swkmkwhh.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzhdbju.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqpfyee.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxylroup.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ufougasv.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhtcjjl.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2psuenchk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnuaohn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxnjbuw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2llnfktaf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2oltmxubo.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2uexhyqoo.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2teesmsqs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ohiidiua.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2mvblugep.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hchgrrln.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcyfxol.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2zngzrpos.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oozruhjm.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahselsaj.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vygfgdkf.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ensdoypf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2uflfxuue.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2okwazvfs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkoknqj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlhxgdk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2twgloqmq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2odlbbkaa.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdzfcjj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2txbtweob.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjufmcsx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2gvilthps.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2caexksmz.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2stfdbdmv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2fpowvrdi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2siqdqxcu.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdqltuk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzeltkl.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzfmrqs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjnbipg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yopnlkxc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2amwkfxor.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2azqssndi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2sihrmiga.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2enpqejxm.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlljgkh.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2kubcozqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgjgmqn.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpbgpgo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yulfqjix.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qscckuhw.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfchssq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gclbhokf.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuouhml.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2etmwccir.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvujeeok.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2eywkcxqz.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2siyttyzz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nobboxvm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2scmhexsd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntccfuiu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sttpjdau.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwggnvn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxyjsfa.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2dggyaupy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wunfbofz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2udjmveiu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnxleuc.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yabxkdbq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdrujud.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxovbcns.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvuqdgm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfcpuyf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvankfr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2itrygidq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cklygdwr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhubhfm.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqveqcq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2lsaimkrv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmbtkjv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2renomrod.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2acbjdkil.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2zphhetrq.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfstswn.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtclwbn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2umlngynx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2wejukfld.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2agwajbei.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqmhxrg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxfzrmn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyjkqpo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2wivfrhzm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsbocar.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkkswed.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2inwprxvu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnhkvug.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2zetcoxhp.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdfosxs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrxydmz.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjwijoh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsmiqiy.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axelgbat.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2lagcveyd.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sccwnzvw.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2umxteyoo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2uiezbpxd.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmfojuc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvzigno.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzwpigw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkksiruj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2aiopwzdq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cjaygbbl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjftnpt.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2iwevfnbr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2akchntgq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhidmnfy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2mvelxszk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbszcmb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmicopr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2cocriqzw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlruyjg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuvfdir.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrhgyuz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfzgnke.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rbafbxln.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcxmnql.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2shtgfgld.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ounlitrt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2znbydyeh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjwtllr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2epoldlco.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjddteug.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2anoaqadg.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxsptki.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2blxsljey.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhpkcij.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2nhelvbdq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxzsmdi.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jahgwscj.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2kchrinpg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxtxnkg.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxnokpr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkxaszm.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2njveqjpo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nimaidbb.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjfkuii.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhaxesh.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2okcosyub.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvaebbm.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xllnjmwi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyitpqn.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nersfaxj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzonxqbm.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lfiwcdor.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fokwxnrm.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxukwjs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2icsjppfw.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgmpfbt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ulznflhp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2hyoxgvyo.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyzswer.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dubzaiym.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2kubyecpk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjajvbz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhhhszd.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnwikyt.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2usmcsfpx.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2oglmawqg.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mspybdct.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2llehvhhn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdtiprw.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xxemfpof.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmnefod.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dmeatbvr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeltleep.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rrznwtbo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqvclfq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ychelvgq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzdfnrx.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqumcqo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmmjsje.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2daofylhj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2xomizojs.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2aerftwhf.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zawrfszb.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhnkujt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgnbvqx.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpzgmoo.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzjyijl.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2diijemhu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2toplkbsk.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gznrsfed.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuezwod.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jqexbojy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bayyqexr.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmmbhhs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2anahqvbp.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cppowzpp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjogcvhl.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zouvptwg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfascyo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2wogzugii.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2azeidqjt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyslducc.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2nkuvmtce.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgflfkq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ljujsiwe.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2igvlngaq.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2emcmcmxf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnryjgu.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ohudtbpv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtycuvu.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yacecktb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgrcnvf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jpljbwlv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsieipe.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2osghexuu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zffjqgsh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzidbayu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgvtakj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2lokrmjqg.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmnmyzp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvhydnb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpjwtfv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkrjlwt.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ksktncal.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2kvadihkc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfsxpse.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2soipxbhn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2orvxrrmp.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gzylqcdz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruuwijbm.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvytcsa.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtvmevl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2garmcioe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvinnist.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtonqyq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdranbrh.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ihumjvxa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhleizqr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2axclwham.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvurtdp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2temeqizi.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhlzzdk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qyoyvrul.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgindah.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnxcphv.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkxtdgz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyxqsgw.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxwdpwl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtwtasx.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzsotzd.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxrrcjk.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2chtpqcaz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwaamxvf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nikjjkol.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqohferh.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcpeccn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kerrjmoa.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbvjayg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsnljgc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxejngr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcapmrex.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2iniiibmb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnalmxt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yeoumaej.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwjlpqf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkswfsq.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2htovajtv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2potebtbb.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jojcmoyu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2igdlmjci.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2grsuvpvx.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmowzmdf.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2veodtgtr.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoaaidjz.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qakibjqh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2isfqrbgw.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwgclpj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2bafmblcx.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrusbuv.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkyrbdl.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcrrxsc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2iylzhnxn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2wiewadzb.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2abqvvbpl.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zczhlzhi.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2svwojqnj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2hyihycaz.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2elvvzrzx.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aduwqwpw.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmzumor.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lkorobfn.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfmuceg.html


<!-- 参考信息 -->