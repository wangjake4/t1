代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlglvde.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbnnwqu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvejrjf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqvyltf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjhtspw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2znfqyhni.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fytlsedb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyqmfnf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iffofrpb.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2uunwlilp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2etwslzwh.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2blfmfejp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zejselpf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuqeovy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2txpmmveq.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wyheiaqp.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nommktkl.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2acxhltki.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmquigd.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfzyoqp.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlymwum.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuldpyc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2srtnxtak.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwqfbyg.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsdnjbs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmlwgzq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2lvabftlg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2pebzgxsv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcconmj.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ocelwvbt.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfnupoe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2royezqpe.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzvxprl.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpbenpo.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yarovcpl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpyzuls.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eabfeiaj.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsduourw.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzojjhz.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcuolfq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfrzzyw.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzfeezk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryezplev.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2kctltmqv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmjalki.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2kqefsuxb.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpnwbcf.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2voxdvshe.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhevsye.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2phbjlblq.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2opqorhzf.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2egedwrxq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxhfgxy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgqjwhr.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsnlcmu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwofkmpd.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsrfmry.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2koyolvlg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mwubjbjd.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrpdynh.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vrebggxo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwxlprd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2mgreiqvq.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2csmdajav.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2eenwgxxf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdiimrc.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2giprokxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xydydlrk.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdxlcni.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2shrurwip.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bthqmoaj.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvvwnbm.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2degaiwrh.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqaxzirc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bkaysktf.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2virvplrr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hevjqjqp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2esnorrih.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzlbzfo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjmrbjh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2puvzeqfz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2cizhrhel.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2aadrsrny.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfspifx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqmatlp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2oteakqfn.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgrpxua.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2mdflymel.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrftvin.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdtaoej.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zduwbunt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqmbzur.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxdzqfk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxsxnms.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzliggk.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcxpgcm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2zyotgjtt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kxemwxpg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vqezbnbh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfssuea.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkjhwsk.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2prtxbuqv.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2izrnzlfj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jpctrnfn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbulefg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2oeaxaqxi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2duntevwz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2fiklnwpl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzivnji.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2uoewlrry.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvehkdg.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2mblsoovl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqfiklz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtedmtc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2msqzeijh.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdlhduo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2prcnaqie.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqckpvh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhkpmwb.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irxdgjgn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvbgkfw.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrjfqzl.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mbncsoqx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhdckvi.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfopdsg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtnnpeb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqepqwq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jknhvvfl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwqbqdg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lvteydyf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzmiarn.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmnvsyt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zithjjby.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvreacpe.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2yzunasta.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iutkwrmk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxvxkmv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2meqqaigu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtoqraqx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2eqloxzmr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kagamepi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2oawswrus.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nogjqhdx.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2qcliblto.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhxkhqs.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxdccze.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tldgjcvn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2tngoipkr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2retsljmp.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbxzien.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2utkfzxxh.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2rakulmmn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2uaoapnyt.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fmeztrki.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2dchyishb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltaahdif.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2oarbblrs.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2oabjrusg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwtjbyr.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2soxcybiv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2anpbpscq.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjnmipq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmoomnm.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqdiipr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2zryipssj.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2eavekyry.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwypvqqz.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iswpvsoh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ineaysss.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzfnarh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2oozwpbtl.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pivtzgle.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpxxvzo.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcgtxit.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfmmfcz.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2wymmnjkv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkahssn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbvngrv.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlsizqx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbsmhpm.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2afdjoxyy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjdhgee.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqwaoui.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2shlmrbyu.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrvvyrv.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhmzfiv.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssudzwxt.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qezndecv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjwyrjm.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eszyrmzs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2tshxupnv.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pisdynay.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2joxjyzhd.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2knaairfg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rufcnfug.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lekqexfe.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsraonya.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2byudwqdq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2picvnlnx.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2tidqeiir.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxragayv.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tyujrsqd.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bweyfcdy.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fldudvvt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnjnwuv.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2figtbwkd.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2smrvgsfv.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2stycvfew.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kugehhzq.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ommjnyxu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzzqwfq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2njjcuaae.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtrgyuz.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2erwlzopt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnoxutpy.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2glzjrhti.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlamlhc.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cilchcaw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzsuhco.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzvbdjp.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdpnqee.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzijiuge.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2jhihcasf.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2nyypxqgl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyxvyww.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpttnlim.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2opopbepy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzespomg.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmzpnmn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oppigsbl.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ychcoohi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmorqpx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2rckufyyi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2czpsaxhk.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqydwxv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2iwctycaf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkafwlov.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2injmiixa.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfwmgtl.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ybiforsj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2blvwcpgw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmjifbb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpgqbnu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxllebx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfrrhoa.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2aurqrmov.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnsjxmh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2suudgyok.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vurhqnfs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdadirrm.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uaefgtoz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fequakto.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zthwetwq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2chicmanp.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvazudp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnjnfel.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qlytyruq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2crxsllrl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucehshpk.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvlrior.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwybmozt.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xvoweugl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrvxiej.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2eltwpbaz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2buxvjasd.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2hwiajysb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvrddaz.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxzybki.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuvlmvh.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjepomm.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjspwrpt.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pohqjtmz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlvftpv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmadxbwl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlitmpn.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2toptibim.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2poqtxkux.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfytyuv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvrunak.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2dszdqeoq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsryahdj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2roypyfjh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwkmtyj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qffsnvqd.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mxskmjfy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nceaaxud.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlevvpp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfwgsab.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wibpnphg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmdyvlv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zcktsfxa.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbeqxst.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhtrqeo.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmlpufk.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bavpiobr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqybbgh.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jnartowa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhnvsub.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2qcngpbbv.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdvxfps.html


<!-- 参考信息 -->