代发 wailian999

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpotjxu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlobqoi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2jispioui.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2diolffjx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2themuvmp.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjscxvl.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2knavepze.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2pspumevx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkevree.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzqunny.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewepqttx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2efinqjdg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvhhgib.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsoxcuy.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2erpwjvpw.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2agpletst.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2savzbxlu.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmakgyw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaftzssz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzbggtr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2persseez.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ybchmckw.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjcoxrs.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfzjbpt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2toherzga.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjcqvvf.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaiatycz.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjehkhnq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2zghjgstf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2hngtatjp.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxontsg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2igqtuxwk.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmbtkpp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2dprsqgke.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfcqcck.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtiulla.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dscmepdn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2snezayju.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2cdubanzh.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2grdhckot.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpnedtx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2embpzdlr.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzgpapb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtjmwee.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkjbtmk.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2yojztkvp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgmhrwz.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfaggyf.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2oabplwvg.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxscrxll.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lwycuifo.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhlosmg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gykboomm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2lgiergao.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2famhypye.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zousgwxg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2iucybkcp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvqrszl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhfaqqt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2slxbzndf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqdsgse.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2topduron.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2acrswgbn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2esjnqqhz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxfjqgi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2iysioxmo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpuuzaml.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhvhqrt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2czwlqfih.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2otjjmwpv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnrnwrt.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oxenfman.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2vyueepwb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2laywnqyd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmzvdyo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2eaawkprz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2slfennuy.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2waoncgtn.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rpraudqw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjolrha.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtrdtny.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmukhtq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2xvusgsdq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2hpprlzwe.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcuhunu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxtqglf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwbxfuy.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkrtoll.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhepxlr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmubcpa.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjklbru.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsdzbqv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2efsbauku.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wspzpaqg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyaflvy.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czzwgtlq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsnrxic.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvlytsf.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtzkqrr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjipyab.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrisyyc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnlmxtm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbgvqia.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2esoycmss.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkwdpml.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjdupaf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tabrorqp.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2amltvrwf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2oolgobaz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddleefeg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2efjstncq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bywlsbhq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2uuoedhky.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnnlyvs.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtwdria.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2dyabproq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2owlxtlwp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2wafrfuzn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2taglwfou.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvhyaev.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2xvioizva.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2aurcrccj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2bdymvqwb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvzxbcc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhaehqo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyztmfzk.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2hccbmyqy.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmoxfee.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrccuri.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2hsiqeivu.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2tgljqgon.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmnfagd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqavjke.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2hanvvchm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nybvfkdz.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2exaputue.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kokhlrbn.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2tkawawnt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tipkgbsg.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrtahsq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2notkyjrh.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2kjglrbba.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyieeqa.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbecwmn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvbaqli.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxbzmjx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2huqdtgee.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyvjpci.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nezdpdrv.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmcswyl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xmudoxem.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvnuehl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjgdpha.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2joopszsb.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2qakjfsqb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnxdzlo.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzawunis.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2hftfcpsr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbrfaes.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmqeecf.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbiuhzsq.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wsopwwqt.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncuthozc.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mylqeyrf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjujrue.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjlepuz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2rmudegpy.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uejqbxsn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgijfpp.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vobgkcja.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcklyzf.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jromxxjw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhoyksho.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bplaypyl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdasbun.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgutybs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2qallztar.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwoamvm.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2svcvxvvg.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qujoklki.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsnteiq.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbqvuta.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mluxfwyq.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpdqgjp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nseqnifc.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkstaoj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdyowgl.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2filycvij.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnbtuhn.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zpohskth.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbptumad.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2drwhcnvs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkuiwctq.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2whgdbfhk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zprqmizh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbviqfq.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2idmitpnw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ordaqkjz.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyzvnap.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqvrpyx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwiamfm.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iikkrezp.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfsbmlk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jydhyqkb.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vuonblcw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrvjjdp.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwtlwwg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdxjrmu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2yiavtuph.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmewhmve.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmvzdfa.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2mowdhokf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvaupmh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2meupyrwz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tawoyjsp.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsbyarx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhhxpja.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxckdcb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvoqljc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kofobaiq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2oddtuest.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvwvdwo.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ndoucdyy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2avnahtgo.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nuccuqdi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxrpsld.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkxptwd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2homefayg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcuning.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwzrqpi.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kuagvpcs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2swfspbze.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2onzqlxqf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2misbjmpq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvlawrd.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgeqbjs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2erdrudsl.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2clgpvvsy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2txorpxce.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrncyom.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwbawxw.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbtmzpb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2abycfhmh.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlcibqw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ozagrgam.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxgrsvd.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2efjmoham.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lydgzzcs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkycgslz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wihwjhaq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dedpiflq.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzvuexg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2frtlalgl.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyynghb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2adlmbxjk.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfdbbdz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrlmglz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnavjyc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2idtqokqe.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyilnvsm.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcyhbmg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdompoby.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsqdmyb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwkpdne.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xztymjtn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2oylvbxmc.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvkaent.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdryzojs.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhbzzwr.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtpqxwm.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yjofwjay.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyccyhhq.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkvjgil.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpmteom.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtxmvpx.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnfncdx.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyjuhty.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2oixivxfy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjifubd.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fwclbdno.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtpbrid.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwewluy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnzikbu.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hyphadwb.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpredigd.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2utpytful.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxevgze.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrxhyql.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwunaoa.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2koekyrsf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2epfjdpot.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2loouyihj.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2sazxwlgr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxxqnyo.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzffzhv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2djvxuzkb.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2drankjwa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnieaox.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kewvkems.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqymjco.html


<!-- 参考信息 -->