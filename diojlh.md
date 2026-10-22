代发 wailian999

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxyentb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xduvkelf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcegldo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjpynsz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2miqsxjdc.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2adikhjbn.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sfexbinj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjjbjri.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyrslya.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2aktoapkv.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqtqxdm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2bilakyrh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zehmdxsa.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krggqiik.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxvyfpu.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2svygyrcr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqujjpk.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuvaadj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmjfznp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfmtwpu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhflyzs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbuezel.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfreuix.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2rglkyekl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfosbjk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2xilbcmkt.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvssxat.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkheniu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2caicubgx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyhruqq.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2udxrpixl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbfqapf.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqtbuat.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjvmxcs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmlrtfw.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkdatqg.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vluycfuu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlktzmt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2oomzgonj.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2sternidz.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsyrbih.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gotidzmb.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjbmtku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zehawyyd.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fyervcop.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2gexaxjsl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pifludzg.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzjgycb.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2acrqeqci.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwdftyv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmxzukr.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgzbgrg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhjxkxt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyyahnz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrwwimx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2txywmgpy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvgsymn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2smnzrhkg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2krfsyffi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwjvtll.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2waelungy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2heqdhaxj.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2odypanrb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ahaxtuqf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlggllm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fyujgcru.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqzhwzq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvopzot.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2galjcapi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2oywbmjza.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkljsqx.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bunfhqas.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcsbuit.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lksrqpbs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbrqpai.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhrpicy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrgmuka.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehuwiftz.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlotiye.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrrokvr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbeyiup.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zinfwdvi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2btgbaxqa.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2iwifaqet.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vytrxhxu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2zvluqwtr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kitdpqfq.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2dgauagiq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2sibwnjth.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvxohpd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkqopux.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pocsafom.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgmmxvz.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebihsoey.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyaimoj.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxfhkae.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2thguepme.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nnivzyef.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dczmadlv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvecimm.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2meqjnuhe.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iydljsdg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xwoflcvh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyepezkw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgfsghv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvextvv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzgeqht.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2qftxcrna.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbhlspy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zszzvfnk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyzedli.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2llivgshs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2aupiapuf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2snfwnwjj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgwjtda.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqqxzpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcteoqk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfjfyyo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcfkhrs.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnaugip.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2eijzzzcx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2sntcajln.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtgcdga.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2lamhmpyg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvrsdyo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsloxsq.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2hczkppef.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2zjaymzsz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2urbfpyfx.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2eizubbms.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2prerhcof.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqofqkn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpbfkdr.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2rsenmhfz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiykjbqb.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxblegx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvmvnrt.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2texptyev.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbfbkzs.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2jllgoulj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzkwvbe.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2hlaqavhw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnyougu.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsuxlck.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfrvcvj.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2prillidv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsblupe.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjdonei.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xjroared.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2oiutmhtp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2odpzjwby.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzboorg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2laciuika.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmsrwow.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2xqaeouzf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pspxayvp.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbedjkq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjqtnsm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkplhhvc.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xnokfmzp.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhszrmus.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvdbfys.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbzuhix.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnyvjqv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqecqjjk.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqyctai.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhihnoe.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbisgsh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2cimaarhm.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hssdkzey.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2urvvnytf.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gkarhija.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2llnzuqin.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yjiacsxx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhftcfep.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqdsitc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2cimrxrgp.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhrpsyp.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eltlvbuh.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2licnkllq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2xshhadpv.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xldntrwg.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2okegqtpr.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2oorbmxrd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2orxvwini.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dxagrobt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqodkdkn.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjobcpg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgyhtasj.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lclyvvbv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhlbkft.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjidowv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sigydztj.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wowetarn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tszozbrc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzcpyke.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqugdxb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpievmps.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2lpprbadu.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2muiqpsfh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2upoucchp.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dunncsxa.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtnmpoe.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlexhsi.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oedjkeyz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xeflymba.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdpjnem.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zchneuof.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2qobrnaus.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bastbkcb.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdxtkxj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwymkzf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvglbvh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2avscsigt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnafpceb.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2knysoufc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2xnitcvtr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrzicxu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwlrgau.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvibzka.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqisxzw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsvsyjy.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlzcvtk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxcvipb.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzmizyk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhapglb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfcvbrb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmptcyff.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2itompteu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzypryi.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2epkgpgdx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpubwksl.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyzsdrf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgylulzn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmihhvis.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmngzpe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvwzjih.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nwprchwp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrofdhx.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpuxgtp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipimlkvl.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2azskboex.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvijfqf.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrkrvge.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tqivssns.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wntrvwfb.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2uutgwfnq.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2doiobsmw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihaukozd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttglnldy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnlmioy.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtiosbt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2riqrouuu.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xusperma.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aketrmko.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqijglx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqudilqe.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvhsvbn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyyuvsx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcfeevb.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hgissmkk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwxdnsz.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwscgel.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2exirmlmd.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfjvdhb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbczqpy.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcofxoh.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2piblltac.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2umsnflff.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2epowyyne.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyjprao.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmnupua.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2psypocea.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvunebe.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhgfmhg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnysrwgt.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbwmasu.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdmmgfz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2yomppkho.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfyoief.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tynbqbkc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhwgmla.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2pqoribvz.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlttsds.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2enrslusy.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2yqebbduu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjojypd.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzwfkbq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2raicwstg.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfqtutz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkoexwx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ziajromw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zysepwrj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2quagaeqs.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmebvjt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2khuqwnlh.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxdxtbc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2jgojbddr.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fmioqlwr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xaskppqn.html


<!-- 参考信息 -->