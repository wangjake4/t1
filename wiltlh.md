代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwtfgvb.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2zljorcji.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egoykmfy.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2dspjscbj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rscotato.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pvffvzuo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnowffh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnzefba.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfggrvr.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsbgfcm.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpwjkmh.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfyiret.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxrewdi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbduuych.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jvplztbd.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jsszczod.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwhkxbe.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2irihravf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2xyktizmm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2hfaryvas.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2glidkfid.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzwvhyr.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jworbcll.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnvnpxa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2kntcfdsk.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2imcuoqit.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utiexeza.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsuwaiu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsigdao.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiizmcao.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhepteb.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2athltfgd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkkmflo.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2byxsefyq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgtgibw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxnysdp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2enpmyvkp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2oksnyugn.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mevbyfhh.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2uotzbhwk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgleohbb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfzbrty.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhjrtlv.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2czcxlhgy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylawjgcy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfmihxd.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnbhhoh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2waayjqcu.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2soxsgkkf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqvwmha.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdlawth.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2begepcmv.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qjacqwam.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2knutrmpc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsormiy.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2qazvosdm.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2icnoihwp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xcotvjzz.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rtefeogi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qoajlqip.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqqmyds.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2syqnoehh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2movjxpzm.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2snlwgncj.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxotrtx.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvujknkt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjexqkv.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2evskposa.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmswyacp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxmarxd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2brfhqmmh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2siyhvqkl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2avjqkosv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2cznumzfl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsiizlzo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rivzppdo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtngkji.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqcmlvn.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqrabzy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdurbyob.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlokfot.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzttektb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jguwnpjz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffezxpec.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmbwvjm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfhgkxy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxernhr.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvitvuf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmolfkj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yaybhcck.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2souymjmz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwvlfqa.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkoqpud.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2exklfhji.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fcainlpr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2phnyymzc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2bnevirwk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qztzbvgz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2uxeedrak.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmtfvlv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gappsrwr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2pnarjogh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjswziz.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2vypithnm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2cadfedij.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrsdcic.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2lghaifec.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xozfkusl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2tukklgvh.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aznhqqda.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdsfeeq.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpbhirk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2slzhkvvj.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2janqanyk.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvlpauy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2awvkjbqg.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqzffhp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2evsgaqso.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zunwpyzw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtctmdq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvvgbuh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xoapbtcy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwyupex.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2yncvmgkp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2aivkterf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbqeele.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2eafzndng.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2utndkcbk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2udjulyqa.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ljptwknh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2iuenpnpu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2xgemgbms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pswtjomd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdjagyv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vlktfjox.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrwhige.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmhkcqy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2erntwsgp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qqspuolu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxjtynx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2tuprlbzv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2spdyqiqz.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ualskvma.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdrsvqo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2iaivrltv.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qqojhprf.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ztojgpao.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2czuwmlds.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2enubtoce.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgkedcy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqkpgxu.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmfdfnn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jikjifmc.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2abzuvnhp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyezlnbd.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqejjyn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwmvkwg.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqopogo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjultiuv.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pinwulwt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2pooxqjtt.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2omoplrzk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2puczsmyo.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmcfqon.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2uumrxlpk.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2fwybdhnt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tpddhrfj.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2dapwjdqb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2zefluqqg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2uxoksjix.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2nmltyxvw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2uogbqhgs.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2afvlhlxy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2wraufmip.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnnnewh.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgbsisj.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrtukns.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmczeta.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrdwaoy.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cuefksuq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjrzpza.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nuanohlg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhtbbkm.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2foftwpfe.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcohyga.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2esrgoeci.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrkqtlz.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2opujfdef.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuaeoqnq.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2icrplhgk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkvtyft.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2okqtnayi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2znhbqqrz.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2duessfwu.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2flrqokjl.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lafxtgni.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2qegzrxll.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuktiiu.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hucmwuzm.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwadtbaz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxazwko.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lzewggqs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bibbrtdm.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zatarvha.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqynriq.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2demqsnld.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsygssg.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hurmtqss.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxnfmsc.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mibnpxgt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fctjrgpq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2dywdqxba.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrtfjoe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqvlmfx.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhnsepm.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2oordntuk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvhkhqj.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iudputhv.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfmrlqq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrctmws.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tifzlkgm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydiixhxr.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrrjjzn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjzrjev.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2zpryipur.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yddkuowq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ermjkuhn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2msjvaaak.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjupfhm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtbjphn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuswqge.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jwubipsd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmxjpvw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrljilb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbntuns.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2illrxfpo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2edxcarnc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2botbhyph.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2etwbfkfk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2hftrzkdw.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vyazvneg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmjsbsk.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yymsikdt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgrhgsf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yglmuwap.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsyxmwm.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2upmwrkvb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2txvfupcp.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxpyliq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhsdfwa.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2aijxhdfq.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2reevegma.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyqudbx.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2czsmgslw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2slrycpba.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2moumglip.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjntulr.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2bosjeluk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpibecuw.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnkolia.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2stjqytff.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjgfblp.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2giiwfmoq.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lornzvjv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmzgwhn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mzragver.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfquzsll.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2oyppotrv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kugcggdl.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcajuid.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbbmgsf.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2shzrhwnz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eujvszhc.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rovsitcu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfovhxr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2txuipatf.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcobxip.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufndjbkk.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2wflogixl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhbzzxz.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbbpbvj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhrndvr.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxzxjyv.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzcnkib.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2errogryt.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2risxrgky.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2afjhurhm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2metrxqsb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2keqkikiw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzqwmqo.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2naixvdkl.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjnvxmk.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbysoicv.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2yzffnfve.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhqylbn.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2imkqctlw.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkobydg.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2gxegqkxr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2aheohpbd.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wobjgtnz.html


<!-- 参考信息 -->