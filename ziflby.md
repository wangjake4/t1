代发 wailian999

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pcstyewq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxobdkpl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tenllnfe.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2khcvyflb.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fsayxfgv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fionucwx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpudkns.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdghuzx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2fmomazwb.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkkazrz.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqtorzw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhsegoz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2iiuxbfow.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2fphonwam.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhiuzcog.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2dyaequmi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrbmabx.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgilqmsx.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2znqpovrg.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2whbwxnxy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxehqfh.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgdxfec.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2muxgazdn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgcjyvo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2efpgdgcp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvqrrzc.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuagipq.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ggoltydc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpchusjf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2dduculni.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mftogoue.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lquorohq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzvoilv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrozngo.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbpufue.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmuksttg.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ptopkusd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2nozrkkzj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhegdep.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2nssejrdy.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xxseavhw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2sdizuqox.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxfywov.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2orexlwgb.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ssuhuarz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tylqqlgt.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cylfuqqd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhiehng.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2nqywxnok.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2cimdwizm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbdlbpg.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2amebrfmr.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqcofpr.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2twdncdhw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2arysgqbi.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rhivbjsc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqcfnxx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2nmglujpk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjxajml.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsasmdu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2eboursmr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfitpll.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2kayskcxp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xtityfom.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbdkuur.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkcjubg.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yakiazhz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2zcudaagl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2izgbrrps.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjweawh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmfxjpk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjkgfdu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxuqxff.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqhzrba.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvjxpky.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2niekzszb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2wzovnjgu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2odcncolh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2clizbuqn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2pbndfzin.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2wetgqafs.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqpokry.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsssced.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhmxrtm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrvbrji.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pocthnha.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2khsembxv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2beaanhqf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fghdzxbc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2gwksyjhq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrehdwwc.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2kijzqcvk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2qoptusgb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qyedervi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2slsggjmm.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqxpzse.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2squxazom.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvznzkqv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvngiyh.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dizxdroy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhaefqlz.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwftnxd.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2eddtfwmy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2bphsbrot.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yaojzdnd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlzayfa.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lugzfprw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcqcaeq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrveadx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zixvnloz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhcvvfq.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2nemrnjvl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcbfdvi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvmojkj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2hedutxnr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uipdkjxy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwhtfih.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcsxzna.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbrbxmk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2smwcushh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbsfqxk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2avvforrs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvpahfn.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjzulzp.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2zhscaihm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2crbjoxbs.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2hhycysdz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbcimdk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjojvwl.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuncpghn.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2guhvrpkj.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvokdcl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkpugeb.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfehjqo.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwgleop.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsmbsms.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vadmtjmc.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2tminmrpe.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cojydmsn.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2axqaxoxz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2anzdhgim.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpdnxns.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2azefnqll.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwhhfax.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsnxsij.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwtuaei.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzvvvwx.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjzamym.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyeumulx.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rernhydb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wukrvuke.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2iwifynyi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vudzvwbw.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnmthtc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2weicmywl.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsywdci.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2uepvcoeu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlrfqqq.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqcpnff.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fgyzrxph.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlmwngy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ozijvneq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwkzanz.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsbakmm.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgmaxbz.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qoctovlg.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjovqtjl.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlmxnzv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcsegwv.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2riokedll.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2xhimjvta.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2djvczrln.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvegsrzf.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tblxnkwn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2owesstjl.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjdvcxm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfswtcg.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2erfumbvi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pregtces.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlpajeb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbumath.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxpqunb.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcjwfsx.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2afebebvy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2twdctmmh.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lmohrtls.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tanigpej.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zgohvxco.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmplnwt.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2smwyuklj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtwegga.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjiipeu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdykboy.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2elkdykxs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vujkowsy.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qaphpixn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkebbvu.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kdguntat.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfaxvmb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2koncotqx.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2epurechm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2eilvubdz.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2rirfljzx.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnrhahc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2qompdmhw.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfrleal.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zogpoldg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnmajqk.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlyfvcx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtkrvit.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dypesbsd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgabywx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpldzvia.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2plhmiyad.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwmfsew.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2wntuerno.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmcykzm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2oodyzumj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2upszxxks.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhadecb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdnqapy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2wuofepei.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxgwnmr.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qquajtbh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqxvkrp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfztqel.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hekifaxs.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2oaatmhln.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsvdryk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ninhjoyg.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fnadaldi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyaueiy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rccogkne.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfodawpw.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2usezxbyx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vowwbvfk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iiabijbw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2flzktglu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwddlicm.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgznsnr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2abbrquai.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxkclxr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ydujvfox.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrcmzta.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2frdxxagv.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2hfglucyd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bllgnnxc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vxieeqbs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrlvfjs.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2cotqhwfn.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2fosqntdt.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzwffjx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nggnmpst.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvrvgym.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cddmwpon.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkztrpl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxsxaty.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yvavubdx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nybsevnl.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjkcsff.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfovolif.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vrosqxns.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ksphotpq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpsswam.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmdzuju.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffahlovl.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2iubghcki.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoascvga.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qofhfqhz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2tvggrzve.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bxeiyjjr.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqsuwjx.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhhfdxx.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbefisk.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwhqmus.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2llvnfhqb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmlapif.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2oayiiknz.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqkhybb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2efoexqmw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oultocsm.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgyaijm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2uuajixlf.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwymbcb.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzeinvyk.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2bqprcoif.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxvfezt.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2meogkghw.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmhlpzb.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2maopsmyb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgczyzo.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxxpcah.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2eauzvwqs.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2umjoytez.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kltcxjzc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2qsoocjbg.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpspdyc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtgbbxn.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2gavslwcl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2jglbwstb.html


<!-- 参考信息 -->