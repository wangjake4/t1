代发 wailian999

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpvnuap.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2srltjfpb.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mcglmmtr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2rcscvqqf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwyjkcw.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2acpirilz.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtrdcbk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrcqppr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgcczuh.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyipgzix.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjjahay.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvvkdgp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2jienwomz.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjnbmgh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjanuozs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtaqucc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ogttmffi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2woruppzl.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xayngvgq.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwmfflw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkhcjrs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhdluiq.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyapuofb.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uftpjrgl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvjhbsz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxyrkzm.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqlnblp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlwfefi.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xocgogdi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2opkzmsbt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2knicxblt.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2fenenaiq.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2droinceg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2grmbwwwb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkvjatn.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2nljupgyp.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2eowztrkb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xcokierp.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2scyuswki.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oskjstxj.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2slptinlr.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2wpeknepl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2nyeccrtg.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2euoxoeao.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfhdafk.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpausfq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkszybx.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvsprle.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qexnguop.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2yubgbjrf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgeshrhz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2okwwdxxt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdqsuzt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2cehgwfbc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbbbinl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2msdqbmxt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmniaxl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpdwvbz.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpcwrqm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnuugvk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjimzxme.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmafasn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2meulilmm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2unugyjdr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2yeeabtfj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjecpoh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pilvaqix.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2flgvdafm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2lncrdcob.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmrxsij.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyeogbs.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwnhduh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdrelqo.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzqtlgd.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpiiluu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmsaxwf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkkyjrq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qulftzpg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2qcggwnof.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqjqsxq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjzezyv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhhhlix.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxydzqgh.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrazwkv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxjhiyf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqioiaeo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfgrlol.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rykyesbj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ouccetmu.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucoqtcxo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcatyvr.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kuaddtvb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2iukbqngy.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaqubob.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lrltbruk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2xiugevxd.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2certfgcn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2duzhahsa.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjrujil.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlporfu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2wezzdkhc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbvbakr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfzdftv.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2eqshwjot.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcrtayc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyquvewt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2gbouoxdj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2soaetbvl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2zuoopcoo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhhdoev.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvqxueu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeobtbm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ltiywypl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2loflhnla.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2llagztwn.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2yerfkgub.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ktovpjhd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjniobe.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2dzilmwpg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbxizhi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbbspim.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmyreaw.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzhfyiv.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuozcdt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfzfjaf.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tnosinxr.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2xprybzul.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjhvxgs.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2elixlclv.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ddiykeoc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2youmbotc.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2djwzxdhj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpogmfl.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyhwxgd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyleomh.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvucpln.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqcixxf.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2obucrfcc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhzxccn.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqinfoc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2eglikwiu.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2krjmmmyx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxpvojd.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjvgtsi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzchkye.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsxajkc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqelonm.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2bgivwnty.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2afjvuvfr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2stlreyct.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdvmipr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gworyvhz.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2soazqxla.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmpfxzy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpucxigb.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpnkpnq.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxcnpvy.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lhscjaby.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rakdnidh.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtxmfrv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxewbucg.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zoleefns.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2lojetbot.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbskvvt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgcniba.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxtadlt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzvbwcw.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2doeujrkb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlakstx.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhjggvx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2bayxlccb.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxspbnt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2zufilvig.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcmilvi.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yewhuhne.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2amfdlfpq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2grrgbtmm.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2unlvzlgv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jaytazbx.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kezozpwz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdslrzqh.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xelribky.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwcfvmz.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lknahfue.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcelkxgb.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmrhpjs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2plfabaxl.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzlxdat.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbqsvac.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmxlumc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmyujln.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcgaaed.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdregxn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qihymskc.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2sliafyal.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2snskabnh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2nurtgwij.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvmvgbt.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oeiuhzdm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddttkkis.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hugdtcxb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzaazwff.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qldpiign.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kseywepq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkeeucw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aypjggef.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwejweek.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdsnoxv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwsnkig.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxpqcsd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqadksu.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2umfyfxbw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmjajpb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2qkosentp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykejodqd.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kceuvqtu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgcfeia.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2njdomoha.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbxirdb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2gamdbaxf.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qmminlrw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxztpof.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bfypplcc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnagvvt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrvfwka.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnxtint.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnqsjfy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkymsstn.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsxjnnn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbitzdf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbluusz.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gaakwywn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdemzzwc.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zuttigvc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2uzehgent.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gopylpls.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvgkvco.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2vbywnhvf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmwzkrv.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrvpleb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqskoio.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2klelojik.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgozzryu.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwfbrvk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2otpgldrr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrfivqr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrozbaq.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vufdktwj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmegius.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2myytsijx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2swbzmkvp.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmfdthf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnufsjcw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2omyscasg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyeetnj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2borimdch.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2reshmzsl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvxhgdb.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfwvqtn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqgarbz.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbiwycu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2xgiuyoog.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2msqbagdf.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkovsvig.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpehixn.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2agnmophr.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2geaxmvyz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2gidpanzx.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2wchiacli.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2chqkvvbp.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnkgcpn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2faidyhsr.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlspkpd.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkkrwfl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2dkiagxbx.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2shmqgzgp.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjypbir.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qhretxfp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvvuyqx.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zdugwyba.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpsjvpr.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2iauatipk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqfmerw.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwkkuyw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfnpdkh.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqbiaqn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2opwhpfhm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjhuaeb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkygeka.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnchyvt.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ilubqvyb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnhxtiz.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfltamd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbnefrk.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2prprnvri.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2gfunpvck.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2giqnxyhi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2savcqsra.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kelicdza.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oumilybz.html


<!-- 参考信息 -->