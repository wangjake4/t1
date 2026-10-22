代发 wailian999

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2odwaqack.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbktebsm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mzoeeawc.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbnhedc.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2facppjyc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkozcqlw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvnyuhf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrlqhee.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2afqlzuwi.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2tklzbpgj.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrvpzsx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgreyno.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2bdktnhki.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ybebuhsq.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqinasx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbemcgk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbddiifz.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjjfhvw.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrefsyz.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2insmuleg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2zspiayyc.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tumsddbv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyboldf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rngiwhsa.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwtdpru.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrnjxjb.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvdcqek.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqyompz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgnwweg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdkwyhv.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcyjybb.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfgxdtp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyltujw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpscyyu.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2grusjder.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2riaodvwq.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qeoyqobz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2egaqmcsu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eazpvcpc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ioixqfdu.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkuncxw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcnaujx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyynlzy.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2rshylnav.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgxnzkz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2txjyirdy.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qxakcscd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2teyqlahf.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qglthpge.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2jzswooqk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvdxcat.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qecvokdn.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zljyblgm.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjabskj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhdjvtg.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjnmzhq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjnhxdw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2aciruoiu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsizunp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnsiyzn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2pjautyks.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2dodkouzp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnjoqmn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjfhxfs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xidzfghx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2hlucxlzt.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjqqdwq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2uaivjzup.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2vywdcdfb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxcsczk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnhkaiy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2joqxhvaz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwayixv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fumzwtbf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2yuurfajc.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwsycsr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpzbxbh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2igdlmqlk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsmdphk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2kufxdswl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2omzrfknm.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpacyae.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrglijo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ekftffmc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2aircdqwq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwfpdql.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmrvzqs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ohosvifh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2suqfjyga.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2egxfndoc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjonqow.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2wpeqfxtj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjretfz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhooqnt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2tllczntq.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrljoae.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnsqzjd.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2owdyhahq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlkyzkm.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgjwepd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2udddgpoj.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfglalx.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2iessoywt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2phkhyoyq.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jegtpkzh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgudgcv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2usjoxprd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfxbnth.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2adpxjsfg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmxobho.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fghisqhy.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2zevzpkdo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgcxfly.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkorlqp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2eeklwtqo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzydvkwm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2risphcww.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2xuksjgrd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2atmfqkid.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsuttqc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdlbigs.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqmtcnu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yankbgwl.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2tczcrjkt.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ttufblzt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmplves.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmdrunr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ndijmcmu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbceoja.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2upvbokcy.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2urxlghhw.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2joavdmsx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvphbpt.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxmnczw.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2fdubnarr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbxrjwa.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmnwuho.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvacaah.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpncvlau.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzxgusd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2icdmvmjg.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2njtgumli.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnjfheg.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmnslld.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouknjzmt.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2xykuvhop.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hljfqirm.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2eyewqpzt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gollnmdg.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2azwtheix.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2egmcqtaf.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmgemfc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2axdkjzlh.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzpdqpm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2aptxfdcu.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2hknskzbe.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgzkiya.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ftixaqdz.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwtuslp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsattkp.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2shnkgjra.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrarekj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnakmnwf.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gpifaioq.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmxtfzp.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhsbybb.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2riymxvfo.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zikcdtcw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrkuwjq.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uddfxjip.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2suffarkv.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2njpiaqxu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhajajeo.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2obfftuzd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkohlenl.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjjneav.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2whiocurm.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2voekaimg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqaqulcm.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2drvgjtru.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnfshze.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2nwphldvu.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrbovxy.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfpudjj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsfpslo.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2safmffwi.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2goqrdmtx.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qywantvu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyybhjt.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhsdjgb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2njrjpqbh.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2olgcwvlv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvzllwh.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqnbozx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqabwfqp.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtbtewv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtqjsny.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzmkfuc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2llldulvn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ukppuuab.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvuulcp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2msdabpqx.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwmcrnx.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2apttqljs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2jildrzkp.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2izaiblyc.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rmumpysl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqkriul.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmnexxi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkykfss.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2amihjmha.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwiafdk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2saccoqvh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2serwlget.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2oulxrazw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2enpqbclj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhslyfq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2datuycmz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhazcfnf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdbouox.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwlzucw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhijbkg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqjvtjs.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vheopwss.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2vtygyseb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uagvajvz.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xgivoynf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2neewloox.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyrdzat.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgivntd.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzivtxx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhnqitt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlchwvu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsymdcg.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxanzbr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrwdhhd.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2labqdegf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2txwimhzl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdmtzhj.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2iuffnkyk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzqhvdp.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbxvtvb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2azqzzufu.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwpioja.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqvvcgo.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2jhshseln.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2prlnmxqi.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvghrcd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrcpzrg.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2yoezzyzs.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2lorgoudv.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kszjacbi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygijpjqp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjdzste.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwewetp.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2caeyigsx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2teknjajg.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkojnph.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qucxasoi.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpuvsbf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdgfixl.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlntctn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgmbgln.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxzgren.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wapomshe.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2efywamzs.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2mtekjvmz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbeyfpyw.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nipjtyqj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2exnyyidy.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvdpqjk.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2njpptpey.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2swvsbxrr.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsofwhyt.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgzkgai.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbmhfrs.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2nnffclvg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2edwkbesa.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgcikyw.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqugtpf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dstjqxyv.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rodmwdpj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2sotggulw.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wqciobmz.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjltsfhc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2cllzjimz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvhgjhn.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lpccexyg.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2febiffle.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjiyrjy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyzsere.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlmstmi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2evzsxnfb.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rsexgzxw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpdnymi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwobgxa.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ielgpugn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhepkkh.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuzggol.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlxiafx.html


<!-- 参考信息 -->