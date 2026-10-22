代发 wailian999

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbkdjam.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2zhklzbjc.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2khejbqyg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqqxvuz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbixyty.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfgqsve.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2keztabmm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tmaquoce.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzwbngj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2exesknzv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gftokxtw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnzorro.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lscjjgyr.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnyxjgk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cnomyjnf.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2obqehmeb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsgwrsz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2taakppdo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnxifxj.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ewheuodd.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2owekvnns.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzptessc.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2udeqvkxg.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ybiaapba.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pavrtkkq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2svjgnciv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvuxdfc.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lsuupmgi.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2andmhuew.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtpiwzr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwncqwl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwfmgxv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ewismfki.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdkgxjj.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkkwchk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuimrtj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2zsccibah.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlnlkem.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmmwolq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtnwjxd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfennzc.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmimxnwn.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2euonhylj.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrjbqkg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2pahogfuj.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjoxsdu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwfxdug.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrkbugp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnjdozz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcbmofa.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgxzpfj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwbzlja.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjqqmqu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2lenlvamb.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfvzmjw.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2termynhb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdcmjks.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2cyayubeh.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2abenykiw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfumflm.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xilcfxzz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqeierj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpmkvsz.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2emboujcg.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzpmdog.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvmssik.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqykwgz.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2okjplopd.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2rhihhjzp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2audzszeq.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wshfbsyn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bwunbakj.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfbfadx.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgsrkgx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2evxdjhsj.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2eytjormz.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwmlwrh.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzuchoa.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2smvgnewg.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2siwfqlnk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2baipdcxr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxcbjfd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbcrdbn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwwokqv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2seiukkvf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgsbbfp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbichhz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyzejee.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtayutug.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqhbmlz.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2slvnsvvl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2nafaqyvy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2evgnvuqm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rutntqfh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2omevehsp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxpvaqh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2squmjvpn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gugfvpll.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhavkxv.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2arrxkrgd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvmvvck.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnjuekf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2krebdtdt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfqhmel.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2fghtescj.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgeahbzo.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2sbafajtt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfqimgd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2xraeafdn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qhajzrsc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqevmbx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2iekpvwuw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpeciuk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2fiprbnqk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uckeupfm.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2uamnxasa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqicvof.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qttbpysz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2rwajwsmt.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrtgnud.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwfsmqh.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2owabbcav.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkkrepu.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2esgtqphk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqpkyun.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtjoeov.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlmqerc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2hikyocve.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fetpqezc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2howczjnh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hkicuytx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2spuccaxl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2rmheovhj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmsfirm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2goqmohcd.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2pidmavxh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqrihst.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2twebyzqt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgpzzgk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nggnopom.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xozrsjvc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2soxgqcfc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkexvsu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2xyneaqzm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dzndbqch.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgqrvmf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmxtnap.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2cuiyxwyy.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2nlutgdlz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2pleaoqax.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2wthqgois.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbkwpkj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2flcvsmts.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgofxvh.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbemtbi.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2hedsbcmm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2gguarjri.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2wicccydb.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2zooyewjp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2fggoahgo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmectep.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxhshwb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzrepyx.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ogiheeet.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhxcsru.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2gckizurm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqcfhft.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcsmqow.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ourjzjou.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2heqgxmxi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrxaygt.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2shluqvkf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2noqsdybo.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2efizkejn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wydepmis.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2epyrmgqx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnmvdrk.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2llqypyrq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2riwehlih.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2yigazxyz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vxubbxxx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsizdxh.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2iizdgski.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rochpujz.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2udetmsqr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgxrldc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyunhpmd.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwmrnho.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrnjerc.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vpetgrzi.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fugacblx.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tfltyclh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpguqgp.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzwrmpc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2amizcban.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdggzao.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqrzqqz.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbcixnz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfajdic.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbwdwgu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbeiwirb.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2opjsbdzv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2euriclxo.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2zfotwyje.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqavima.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vroisgve.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2teuxapxf.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsknlbo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjtjypm.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bocyasty.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdsbuhp.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqlxknn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdwxnra.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlvglig.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnltzzn.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzokhpp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfeedhvv.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ngafyxgz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tysypfzy.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tcisuodp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uskmukho.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrudbxc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cghzzqvj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpmntrc.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjjcbrz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrbntoz.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2uopenqii.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2bleypkhb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdegyrm.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wviyaemk.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iezmoukq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhaypnb.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kabhpbvs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnmosnd.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bcoyaanv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlrcbkq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwmrdmp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xthrtufj.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2alcvgaeg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxhgnja.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpziuljd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wmngfacw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzapmfpv.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjjzxym.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfrnzit.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlyhgts.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2znbdzkef.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cshqgzsd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2iuixipgz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2iazmislr.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuimrmo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzgnmjl.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2crpjhpiv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ultpjhrb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uadnqzid.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2oazcbpip.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhaohnj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2laskihhi.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjapkin.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2shsklilf.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2znxzhcld.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxqqnww.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtyznnk.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfgeqmk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aymsihxt.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnmhpry.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vchrztjy.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qsemgzle.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2smmnupdn.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2kiovbevb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kautazen.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmberfl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qaezqcbh.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwtzkoh.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmaiwnh.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmzpqzc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2uubwlsdz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2iloywfmb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2avbaxsne.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkxidjw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oicodthf.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmqjdpy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpaxxpso.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nuaoizxb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzprxfgf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxczfud.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhsgbzk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkoctfbg.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzmsedi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2akuquwkt.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2laernaog.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfrzkxl.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcfyqjv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2gekeimiq.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dczhmfwz.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwdqwti.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2aglqpgcx.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2yaixkmpp.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcgzcqz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhtrlyj.html


<!-- 参考信息 -->