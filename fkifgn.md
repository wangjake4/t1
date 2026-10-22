代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpuqstd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2reflhrnr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2oiilutww.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlnezjx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2annpskly.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dylflatg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzneqfoc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qovjkwxz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvdivfn.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmpntnn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpprjfh.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkgvnzp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkvhnpz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gwimucie.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnfadtj.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlsfkse.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfckbeo.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2gocebaka.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqwgysd.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2bstwlbfx.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mmeqdixf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2etfuqmwv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcjerpt.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjnkqeo.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmibszb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2edslchvx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ecesrpih.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvoaxsl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2sadropkj.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvdsypc.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2usquemqt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbzbstp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxdzqnh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmgwbau.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vplrielo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2utrizcup.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ychkxbso.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jchpfmzg.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkuydre.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2tudlnvdq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2cifacyto.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdqvbkz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaixuzsp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnwnrao.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mwusjrgr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcctvam.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2chquawun.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2snewyyos.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcjwerk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2hirttage.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhzgyxb.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbrssod.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzqhrng.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibetglrd.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxersnhr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwceykui.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbekzoz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsanxqq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrtruxs.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2gckbcgmj.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2subhzxev.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxbzlma.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdaxzcr.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjsplcl.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwqkwzj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mhoblmah.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ootyejpe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gglfqcpo.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzrcbfm.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2wierplhw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwqewys.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwnollk.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytojdlhf.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlhxkvh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwdrgus.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2iijylcat.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2femsrbfs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvgkgra.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqxnhfb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvbgnfu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2eaeehbxx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwicnoji.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbphaelr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjcfhcc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzpdyiv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjcmsdi.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkcfmsq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2wegfjrwl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyembyzk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqptdfs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2npxqbiyc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2atuwwtwn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwsqlzs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfojcsgb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ueisysby.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2imhpsjht.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtjrndz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xueshbkd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrgmwtc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2iegdzrma.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcqyfvf.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2bowgjcxz.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2goakzsxz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fexbpazb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2rmveogle.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwhdbtr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhhjaka.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2muphhble.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtwgmuj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzqgeva.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2flkqxhde.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2olaneimk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2opswdfwa.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlizcir.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrptmro.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ookuwjyf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnbeoax.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2otarzbsz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qojshcpk.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcegyma.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqpsysh.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pvciqmze.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvvjrpo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhcegaz.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpelyga.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjcwyso.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxjiuvm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqjvhjl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgrhtyw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2llhwvcny.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqfoinx.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmvkdtc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2melwtwcw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uthggpis.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2imzdwhyy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfhyszl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xotagkol.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpqshhs.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrcvboa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2quccuplm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoudvhk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2subdcugg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2edsbgufb.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2vpejmdkw.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxsdkry.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2gykzxqyi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xthbxweh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxujtba.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvmamsc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2uluqjumh.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrnzqxa.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnrwmit.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdarxad.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmgvpag.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtmltrx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2uclnihod.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmjxmud.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2niefoomn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mubezimu.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2znsueidk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpjalni.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2rczywhlf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfdysvt.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrwjxrr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbabkxi.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2lusmcvkl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2deelinpq.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwexyjb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhgcwsk.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfdakql.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbcsfyd.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzqxved.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyvmxzv.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2pentcqbc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcyrtok.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkxmobv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwobofy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2hphdtfnj.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2hwoofbzi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzjjvxd.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2juglyams.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2rglmigen.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkebybff.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2busjofoz.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqsqreb.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jnappopw.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjntzhu.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfxbmqm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfnwovl.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zljggvra.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjpdvtp.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2felurpyu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcimlxnf.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qosajslp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sluokaul.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xfiumwuk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgiypmtz.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iuoeasnf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2plbdgxbn.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2vkukhllx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqaszdz.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gygtjnmw.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcizvwey.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tqduwgst.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hiptunbl.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgcfmcx.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnynoae.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2sakagmlh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rorfkmcr.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxuwgtc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nctyfeyi.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqadegn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zggmvviz.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvogpzv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2slvyjqcw.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyucslq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2znuphspj.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvohiwv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwoenge.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzunplg.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bfccybji.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2txnpdznf.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2snzwvmgb.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2veqzxinw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2apjliqij.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpiiwpj.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkybfxb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vngtubgb.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2owrpfubt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfpajtb.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kxaxhcdj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfkogxu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2dyazofbv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmncilp.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2flxcbkuf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqweubw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fngrobdb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfkrtnu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkhfsqi.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkhlthr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsmlrbj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2nugzgwsw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2suichueb.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lxspwrik.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2iaayupxs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoykufrg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhfdvzu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjimftz.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ruullnzs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkiiiri.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eddjlboa.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfizgxn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vuaqqphr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyeuccgq.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yudelklu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrimusv.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwcvdzx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2lizdeggv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2elmxxmid.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2viuhyzab.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dujsvvbm.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyhhcyg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vliyyrxd.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjksmrw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2frkwxgll.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2lltjshbn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2frzacsad.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2osmocqtr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yhiqdiho.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhrxfhn.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzsusxw.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgjwkmd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrywxkq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2izyeqqjj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdtpozq.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2twkmepza.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2axsmhkzs.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2twmqfskd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsoxpxqi.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrtfblc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2usgahmxz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrbrbpn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvwbdpq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gidpodnk.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gcubomyu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtwdsff.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyshphl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2okaeogbm.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eebsyfnp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfxqwcd.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dddelzxt.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyglgbkg.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaipuzt.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqukipxb.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2riuldkzz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbuchev.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2trgylkhs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgtgdak.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvfelvj.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocawhlcf.html


<!-- 参考信息 -->