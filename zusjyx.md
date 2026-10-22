代发 wailian999

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2rizwaxov.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2fbaqfqoa.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmblpxw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2julnerdy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2lycqrhnq.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxuyzpa.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcmaiha.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrasdgi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2irglkmcp.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2euafjnqf.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdougdf.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccejnlic.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbszfph.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjaaiktf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnzmqvz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2oymmbpme.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvchgel.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgtlelj.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rktbpftx.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2tupnhuih.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjeocjr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuhghaz.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjgzxje.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsbucuv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzeqtmty.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpnosfi.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuqtsrb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2niwbedqi.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbyoubr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2wprwkdsn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpxukce.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2hekedoee.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxwybao.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2spvwghum.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2oopykoyi.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2piwrhezn.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2shxafprp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkeynot.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2osruyldq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2akhnxndx.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2izevxfrl.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2xybwdlwr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2shfmumme.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2idhvgvho.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlqpwgq.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtsralt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2khvjseub.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pawpbnwj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2agrkmqls.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwulpzr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhevflxi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzotzbz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrscswv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2zimjiwua.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnmvfio.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxmbvgs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaoguibs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvspelj.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xadyebfl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnzjrls.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrxzevs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtfrrfp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2srrkeswl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfgleto.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vqidmnrl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcjmmio.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2riuvhzas.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2puylxtnx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2xshvzbrg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dbshibts.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2njxklshy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2tqoyjmca.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxzlyys.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2otgkixut.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrkspux.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fffpdnzp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsdmuwu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cutfuhkc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2taouhiln.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2bhulwxxt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfcixqr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjypzrd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrovzvdc.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzkxjwv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2snltxmvu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsgozcs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxckwgw.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkncdvm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhojrqd.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdfpdsh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivttbnfd.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbauzcm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmdbofg.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zguolrmu.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dlajrejt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcwlegf.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iuaxayyu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mvefvfgk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlnubrf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bubylyyg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2zdegouxk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdtaiov.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzwzanx.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpatnyg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmblkclg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvojvyqt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtcrsil.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnsbkbf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2lmoeuwoc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2geeakmmq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbdyptr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2sjiwxbxv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrmpkdv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2igfawxil.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqtclfk.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2uggthllp.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2tocdzyva.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2funxogcv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lxukpkom.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeguqvl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzrorzu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2watjpzcy.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvgklhf.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfjwavt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2fkprgvsl.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqwdabk.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2toobeopu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2lthwsthx.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfamxrv.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2xpiwffil.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjznhkxx.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvtbgzv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2oeehxtuk.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2htajrrbc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxuelpu.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2osdacebx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmxsdvy.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnomyfo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbspahkd.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sovonxyi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxohbgd.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fucuuiot.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2oraqkosy.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ufraqjgw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ifaapkvz.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjoxhcv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2faarmjxh.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2cskssdws.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2hafsewhw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2pthspdjk.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2vehdunfd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kzufhvti.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2uebsyplw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkzijzg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2egunnezt.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dhacrqzr.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqalhcqj.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2uautwoch.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjspsis.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbwtocj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgenztst.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rdobjwmz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2vdguxjwt.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvaznxo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgzvuyi.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sweoinqa.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yctbfriu.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rbclawhd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fziwioeu.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2soarftbc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrfnbmw.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtbdokv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmlcyxg.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mcanunde.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfdzmam.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2snlqqwne.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmxseqb.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmcsjan.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sberjirn.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2paynhtfu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvoxaigu.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gymtnxrs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2towjncwf.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2szmaienq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgpqvrc.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2meuvomqp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdnvlry.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qppiihcs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtzwoeg.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxpkiaz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqufqqjc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2yakwbeqz.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2eguoakiq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwtzziy.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2clysixdw.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlpryip.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2cspdmaga.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2htveykwg.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hzommtbi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzevzey.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdxmwcw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2idxypuss.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xvckeebv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgetblfg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqidmwad.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqvggdc.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2psaygskb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2xjocmazn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwbqgof.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2auknctkn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvwdsaa.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nzioodqf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2uoogurpr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2znsowehn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fblkzjgq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2neiywjzf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2abjmxgtj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2sedeozgs.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbfavgy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2elrhuorz.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2skgfthna.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuderbe.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sojeacjq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqhmlom.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2itwyltic.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2whttavsy.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ekiavcwv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfoyecn.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmtapxn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2vknzobse.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpkshkr.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzrhddh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrmrpub.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2elkaumho.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfjdetw.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcjrjvv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eulhjaty.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmchjqq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdwemec.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2twgebdmn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2golnzgwv.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2erbtiezp.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2mthvvecs.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlhqgpx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bparoowr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjscgsuw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrbgisg.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwxsklt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkppoqv.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wryzfatj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fibqppqt.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmiqvzh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxrdkqe.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jfoesjfj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2evijdndt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2urbwkxre.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmnqeyg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ornwopzs.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsaixip.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2skfbadas.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnvsnvu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2vvougszn.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlcopfn.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuoblog.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2exzhevep.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2jixyrbxk.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jklnydpk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2urcukflx.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2caaxnfad.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgzjlxv.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2erizakkl.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfguyph.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltipqqyz.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmoactg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnhchre.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2jydjybud.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2owusyfih.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvveczr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgzwqnm.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2czgximiy.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ollarozw.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2aaeqvylo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jhspxiij.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2llirwxva.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2gurdfyjp.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnczabr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvnmgzi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2spfcrgww.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gwoasmrk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2eypzdqqz.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmnrxzy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfjlggi.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2djdekhoy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2amjbzolx.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rrluwhai.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgvcchw.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2iafmhbpp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2weydxdap.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdlsrrc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxqpoen.html


<!-- 参考信息 -->