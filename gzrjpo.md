代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkppryiv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hezhzwqs.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwjzqyv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2limafxux.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmllupfk.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmenfkci.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpdoexa.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2zhoxpchh.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpeihkz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yircerlg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jczorlqv.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzmztzi.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2atewzycr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nshjrkdy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmnumid.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2iyilrzet.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2wofdjtsv.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ymixuvrb.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrpydtj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsnqqmr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwkgqmk.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzlysfz.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmqziyl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2szhpkmxw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaeuqxoj.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbonerd.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlfxxkw.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuexfyj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdesifa.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2micjasfs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpinrscb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpwtslq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbqvdqo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2krrrotos.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2edzbfsva.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2uuapqjvr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpetifd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2cfievqfe.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmvjaun.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcecmmq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsswmfk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2txgtwugi.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqxgkwk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouspgfum.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2olbdvgbg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2jisapolc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvudmmy.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyvnxsj.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwsyghl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2kpazxrtc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2amzgybqx.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2zndczkqg.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2oqytqufp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqpbzmz.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzdtaoz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2naxywohd.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2dowqoafm.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2hwksgjjl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gbciqkkm.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynebbtew.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmwsbiq.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gizlrxoo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2njqnoein.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xocaxjby.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkneeeh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2omugdwlq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2lycllbws.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdohdyt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2alhzzdwe.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2nygcazmi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzfwxul.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkyumul.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrnuouh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtkhqzv.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hcncdghs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2cumwkoys.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjuyepq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hggeglqm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfieevwc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzylngbs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2llabydym.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kobaeqbo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dxucpoef.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fsimjiue.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzigngo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwizado.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rwulnjys.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhvytlh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2shksifzf.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhisbfl.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxwkjtv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmkrfak.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzevtoa.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ketsgkdf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkdjmxf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2zxievuui.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzrmjaa.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2eojkvjbs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjckafh.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxdtqux.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2hypumtqr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvajrsmy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2pbibmnmd.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdefeov.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ehncbvob.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxebcnlw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2obhazgwg.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2quyktvuc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgvhufj.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnihhhu.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcrwtab.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxwmfyd.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bwckjhaj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwvfiav.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pilbzyoz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubitbcux.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjsaeky.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2llapxauz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jmalzqns.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrnrile.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlhffab.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2edkpijpt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2sumlbkys.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2liskavwd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2buiavkha.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2lxecfbux.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhxpkpl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqejudr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfbsicp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpoxyki.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kiprujkb.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgdqbeb.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpvtykp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2iwviipsw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2aabnpvtp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2wrifaokk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2pegclbds.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2eucinsrs.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2fpacaxml.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2qcicjboo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlisaif.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2spiokzyu.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxtnktz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2razkkfao.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2uycmckyi.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2anqguxoy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzohqck.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjbvqnw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2swspbuxo.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcvgyrf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjklaggt.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2debozxxc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjdlkvo.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhlgbya.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2agpsbqkr.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qqujicpu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2sngkrsza.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpoflkc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2afayyddf.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwaojir.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xjamdpgj.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkulwxu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2niurbnam.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcznnfb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2shvwakmv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvuyyao.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsymnjb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlyxiqd.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrfvfkj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgeprez.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xslisros.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2yiayvqot.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzepivnx.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hxratwxp.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdowmrdn.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjfboxe.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqzehjf.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pscjfwbo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2eekapgdn.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrzhaub.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2hujgknyo.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ublukeky.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2idnotejp.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2umjxdgss.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmqsdxx.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aigaxsna.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkrhbxg.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfxemwq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2fptyfyop.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pekzdndo.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovckvmkb.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcnlkww.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2lonjkjgv.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpcuuqx.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iulhrfwr.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkuovzq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgrxgkt.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjossdf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxjbeib.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qaoouxsg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pegrvqqj.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2porrlxmm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2idrksfqx.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2erdgnmxy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyfeszx.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvchmcw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vphqtmvu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrnqhyv.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgpxdng.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwfikyv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2txstzcoz.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2oekkbkug.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlhplpe.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrgwcru.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qsetaftx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtljgsna.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gltvrzqe.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcmltte.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2raaiqzdk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpxhgnf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtbdicn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohddxgsh.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxzkpdb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbjhbgi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvpkpba.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2iklqvvcw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlxxdpz.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gheukfny.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2jwawqsqu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqycqgo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvervme.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbzmjrd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjimasd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrekbwfx.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqqphfq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiipxgwn.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrpogzc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsykhmf.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dkerueue.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2goadmbxv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmdnolg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngndtfik.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbnafjq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vehkgjie.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qqavauxf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2obyaxgvd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfnjdhl.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmsirle.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2itkhzfei.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpqdeqo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2lasegkkt.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uitepzvl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdarvuyn.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2istbicbn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmftbwn.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxlohui.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xsomkhmi.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2yxksymsd.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpufrxdb.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzjcspq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxminuf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2srphysmz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggisltot.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qmauftit.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qggdpuwy.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyoqoup.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsxdcnx.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nihbltse.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwepnten.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fdaxqyxm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdwdwhy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhbblvo.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpdiara.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2alihdeyi.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrldpqq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzaubmq.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pbghbfew.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2naxllrrg.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uzawyrbw.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcowbpa.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpupzih.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2zydzpabv.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2svjpnuzq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhjvkie.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwdpuix.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcejxtl.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2xkovofad.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2swonvdow.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkoomdj.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtjvmqj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ogokonsx.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fftgdleq.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrkyjhq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2wpifiabq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2jvloiehl.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjykpwt.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtvajuo.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxzxbdz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgnbnvz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhxgszn.html


<!-- 参考信息 -->