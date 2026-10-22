代发 wailian999

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fyigjewe.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwyxqme.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rlclzaxs.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2khvnlaiu.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bimufgxu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqrftiy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2njyngubp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2poelzmli.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2iymhgpth.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2qakclzbe.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rthnydkd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2igsdqmjg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2badswdmi.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlkpgdz.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmkzwhl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdunbyqp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjwqroq.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2promyqdb.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcouhuj.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfoeuzym.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmnnxak.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfwzcgc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddulsolh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqnpzsf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2smbxnhae.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzdvzob.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2najrtpdu.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpjkrhj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgtlrrz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgylhhs.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhlxres.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2svullnam.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2aoewratr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2lppxiqsb.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtaajash.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2abmkyqav.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2apdvzxwb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2wplymwao.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ffttqsqn.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2jvykthbi.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2jujpxonn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2rdizomiv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwueaho.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxtmjfi.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbbqjdt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qihvmdip.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qzntpcod.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdekuxe.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbazftt.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2fozagwqj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ocntpjnc.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuqydlc.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dskdtnky.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uydlymiu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgztfvl.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvuylwk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlweladd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmtoukf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrgcwmh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tposbrjw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2armpxikn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2lloavcok.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkdmcao.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjvadss.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbxpzxg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2yypwamus.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtffxua.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjtjoll.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiytbiak.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqqosio.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppogyudr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2takkjgnr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2gckvgbfb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2elweujpc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdjhbfv.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2glixybtg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2tdiernlg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2bagyzpbn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2oucgpuga.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqjqyuf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpurwciz.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2adcujtci.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnjozjo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbnajwk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2lacixdsf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjojufy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2efwfcrwh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcgiqxn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qalwjpjd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcswnls.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hktdpsns.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpqumfj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2skonzftg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qmozeeze.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2hpezejdr.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhhiwwk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2vocqoqtg.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvcidrj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ntghuhee.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebulcjkc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkwsgqk.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgqifqm.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnexbjg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2abemtyrz.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2egdvpaye.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ardpoghu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsvwcvc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lssfzdnk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxzxflw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2czqkxsci.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2acvwpryb.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhdgzuu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqoppho.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpkwdjm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2byvckbxz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzflghq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlqglwe.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2sihghgvl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2qygxeoiv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2mppkzhwl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rddvwuno.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqejynqc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbwcmnk.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2hjztvqsm.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2osbvtlft.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrryirx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2cjppmnbv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqiyhrq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2qbscpurj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2pygxnrja.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkbsdsd.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrodvwj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qxujwsmv.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2noxkolmt.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2qwijhxnt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfuccux.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2clusslrd.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2orfvwgtr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtyxxij.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2axowrqmw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2glpxjoic.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2hhexpxtz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhvzbfs.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2mplsrmjo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcdgkhh.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcotadg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjovyuuq.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqwfmdg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2onyivsip.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsrgozl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2btrcrtvg.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2uzboruwa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zmeppmiy.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2uscmoysh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmpszdp.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbgcfdu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2oisnwbgu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2obdkeyfh.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlcegfb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pfirvvgh.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2clbuzqta.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdpxftx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrekhdjk.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ydugiron.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sunnqkzk.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bcysyhch.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2whdwqqbv.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2trlinprx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbcmcob.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ggspcpmc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpwjjhm.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjsvujn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2segummjp.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvvgrgr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2riyeavts.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zaikmsgz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfhprfl.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvzlxrm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2zstvizph.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnrdsly.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxioxaz.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmavydi.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iimgdkdq.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2notxxnrh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2isamxlpu.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2esxhnwhc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmuwsxv.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ylajmxhs.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jouqceif.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vzaywcrl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ashtdveq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxbnkbl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpfenfi.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pedzcsqm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wicywwpb.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgvthrc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kphgdocx.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uaoveerc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fehytafi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2vhimpbjj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ascqloxw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvrjqgk.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2sohfozen.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2revtqkgs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2xyykrmgj.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqsfrft.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtmqiiy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgfadgs.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjnxdrq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2apujuzst.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pncbocht.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aimsiuro.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgctubt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yaygvjxr.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjyyrwi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2qznqtcrv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyzvkip.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsutvmh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnwjyth.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxgqpqa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2dtessfpa.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2sszekpoq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmauskh.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kgovztnu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2slhmajuz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycaskvfv.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2movvsont.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2oifjehti.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vifjciwz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgdxtam.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcaugdb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zojgusho.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwbtkdc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2htabrpch.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjaimha.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrxnczo.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cofuttiy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueoywncs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xofquskk.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cmucqqay.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvccuit.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjmcivy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnekeuk.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwvumfd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnshdadw.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtnmhmw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrwtdij.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2akzircse.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2uvosqdvo.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2oytnysct.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhntclbz.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghygznlh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvwbaro.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcuheuq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2umrbadks.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ujigzhnz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fscikuzf.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2llxavkng.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ongskvlc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdsnrgy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2njamliyc.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtsvywr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbjimpl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqexjcxf.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cndjlbbz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2buvhuxkr.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2xydfebjn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqfvbqa.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfjzcaq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2rijjlyiz.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2elfpibku.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbjhjvr.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqdlinv.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzkiuuy.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2icepclnj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfcshwg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2iyazrsok.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcylkan.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2xivogtzb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mozyvssd.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtongirf.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2wberidss.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpiifuw.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyugqrk.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxlpmyf.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrqaqxe.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvmxzin.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tndkfhxk.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2euworxke.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkwfrjc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyrzeld.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsimfff.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtopdwl.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2omgxncbc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2znhsokaw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2rokqiinp.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjcdtrn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlduthb.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnncxol.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkedlqm.html


<!-- 参考信息 -->