代发 wailian999

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcafkev.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzafymil.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pndqfmdp.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzodzst.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcasvld.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzwxfwi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhakeon.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2slymhzgz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2catvqemf.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2bbltebom.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtryvzg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbyvlab.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2jmisyuto.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcoihjs.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqhrwgu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2uihyntsk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2enbrcptr.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blzpdhav.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnhqwqe.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuqtdcu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqheldh.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrotrfd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyssltn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdhpsnc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfbndlp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqotpcf.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfasbtpk.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrigtuo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyahndr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2pcckdbzl.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfuuowp.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxhqcjj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzvocni.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwyqtpu.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqdencu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmhnghd.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqhfxks.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfkcdou.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uyanmgti.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmmrqjq.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcsvaeu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2vtiznzic.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbtgrec.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2pyheraay.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2gzisptdk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2grbfdyey.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqehhel.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2auyfgdur.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxqjbof.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2exewprho.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2byfyzzct.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2alzodzph.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2blfjaycn.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvpcqhu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2opmteudd.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2oiebwnuh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vialqywo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuyefff.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmwnkxm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbbniof.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdiimqu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcuggmiu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2fowagjzk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2intnvoek.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwymcecw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2flqnutox.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2opxlllkn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2vhobfaqh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2jywpfnpy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jirragls.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2medvpsmc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcueoxbn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rkapdvlk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrzuhqu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2owxjzxjs.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmmddit.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2chyvdfqp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvulbqf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2spefftur.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyrbmmv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxthjtcx.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2uexgcfdv.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2aaoqrkux.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2osfzexaj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcdeiau.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2tnruheeo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbvemmm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxkgvkx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeltxtqk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfydtcu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2weqoctxa.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnzdqrj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkafmox.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqygitrr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjinwhc.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eabidcmp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2tqobnvfx.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqpknqk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrqhwmj.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qacpwoaf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2izqvwttm.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2laesdczt.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfcdezd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2vkggkatq.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zgddxkgf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xacbrdxx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzoesyu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqxtzbk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2tafwonlr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dovqhjdx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fljvlzwk.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2prkjboou.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqygrozm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hppatnez.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2oknrlfyk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcamysyj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ddylrpuc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtzdlmx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2bszsqlau.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdsffqj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbryzbo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2njpvuzmq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ochljzsc.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ehobpkuc.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2diafjvda.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qsiifpfd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xekokmlm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbeckav.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2tcyfqowo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkmfpgh.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2xchmvfzs.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrkgyjo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2fqaicznu.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2cneiquki.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbdyftz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksaeuwit.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2looctyci.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2genomdgi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhdxxwm.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxgldkh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvldgab.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ealfywwb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbbzdwy.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjjxqnr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2algfgqda.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2mudspjgw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvtmqtw.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2riavddug.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjdadtl.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcqgjsr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2uejkdnts.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvacmmu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2naxjijtm.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2iblajwrh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2znimgbdz.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdwqdny.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmozyne.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2awpbhopj.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2aawjeksc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvxydoi.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzecsxiy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmmoofq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdyuedb.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rsikrvet.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdfnpev.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2umzlypaf.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkwzeqs.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2scsfgdxn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvixvsc.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqnmqzl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2aujkffzc.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wsiagldr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2djvouwer.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlgwlpw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eipnopes.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnzanmn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2aligawgr.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhimlyy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2fylpezqs.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2jajvjedy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2betnbqhz.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvqkdaq.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjcfrdi.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vovnfhuw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjddtbx.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzqjlsd.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdspjnc.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pyufxkhn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyintrs.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rafphtkg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oewumbur.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dznrgebk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lesofhqh.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pexphaaj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2umryiaai.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2olcwxsry.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mafplrqu.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2trrxqvmw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2glrwonjw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2zmphupdk.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcinltv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsshgpt.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnllvlm.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2fasreztg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzgzyzg.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuthohne.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pborqtll.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbeblvs.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxoaqbh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsufqfoh.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuulisc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zndzivly.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfzclqu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwdeapz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pepyqqks.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zomxrgfi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxdcdwq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwruftn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnwscqu.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwrvuol.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsyrkem.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhtglij.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhrypzp.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2svsuegme.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2poztzbnu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtgwffm.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tufoflvn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzsybuu.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mudcnnbz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvpmzmz.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2slfureuk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkcwrjw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fetqvozf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyzrwgq.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yjejcuah.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsboplus.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtvnfki.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsjvveg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2orpitswx.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxmydhd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2muggandw.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wozzfnca.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hjssxczu.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtmhhwt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dihpzihv.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2eawjgxqp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwryywak.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dbiscmpd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2egdgkpbg.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2svhbriad.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqjsxfx.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjciztaj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwdwtgr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qecpfwpc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhxzpjs.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxgmxpx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2premaddq.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dwynijcm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvkdcqn.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ycaxdbig.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvjxbfn.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2akpolgwy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzbufwf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqszufj.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2umnwbcki.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vweoxnva.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtwvqjh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2npsneqyi.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eammkstl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2lkamskfl.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wclqyydv.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqtaric.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bzglvuib.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2hygmskaj.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvqocgb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2eepzwioq.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2lyszgjef.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjvqtjg.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2heunjlnr.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2htltcezi.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jljxrfsy.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlcarul.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2nkotoofv.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2imleeqnv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fedzcaba.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hzivpzwf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2psitpqni.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfymkyx.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmtktkc.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2brrwqkoq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zppfmbkn.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ojoylrrc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlmqftz.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cogxhowy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuzgbkt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2pslinibl.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2oxljtird.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqgvizo.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjnpggo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2lntovtal.html


<!-- 参考信息 -->