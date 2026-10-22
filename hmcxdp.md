代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2guxsclif.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2chapjxwx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrjhrse.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bomzqqxp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ntotzjsv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzzllqh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctsjycth.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzoemyq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjitond.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2uwymcech.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmximdjx.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzhuuyb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmtiils.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwgmelc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2oyaugzoi.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbpjqgc.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwmxqlw.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2fycpbiae.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnknjcj.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpspyxq.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkkejzm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkxucut.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fozhjcnk.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lguvioak.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkbtayz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2iugljdiv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2breacztc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdjnwkr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsdqsdg.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2iemwoisv.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxjfzfv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkikfcf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2nvomeles.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbmlbtl.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxpbwsx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfxmnrd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxiddlbj.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igsugoly.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzuauzt.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2utjbsbul.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2izkaksqh.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvpzzks.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrecnva.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2naohvava.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2oedmadfh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2khqzptce.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkubokha.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2zttindxn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzldxhv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2isgxjmpu.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gebnxggh.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2icyxjncg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2oripgriy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2uldedory.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2yespfhom.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2urcywxtr.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbzilxl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpglueqb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pufzgtxf.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2eopxiegk.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuogiuo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzgpfgh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2unninvwr.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvlldyg.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2wnigxghm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tapiftgf.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hiylsyas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrsfqzl.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwuwrzs.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrplutv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ebaysxvg.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqgajwa.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckoakooy.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2njuprser.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxffilw.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yuankjwu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2onrqlmrd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjdrxtt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcsfidb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cefzeduy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2recpdajp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihioatbi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgonatu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2clailjla.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwkqqgi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtdsadg.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aoouorkp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2iaugloud.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2flplwvyi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qotmhenx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxczqyg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2msmgnmyj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rrosnsvu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2keumaxcj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bdenlkox.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2doemwrch.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2lawmceuf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fejmbowr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjaajly.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vjymhyhy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpduean.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjfxffh.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xypcifmy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dewilpqt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2bmusnxkb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2llfjqqzo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzymujf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjchimz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhswvqpx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2enoqrfsa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgolbodk.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2zreslcyl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmegiue.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zimcwclx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2egteurba.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrbhbvg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmovtcn.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdzmmzi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yblnotwo.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mquzshno.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2akxxsspj.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dopywtuv.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvtpuwt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvqfqfx.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xzeijnff.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hancfrpw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvvhhla.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqougqcn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvbkvqf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nivukzoj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2anmunrhh.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2flgfmzcw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qguoneie.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxjziad.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2htipduxd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvrgzzw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrptzol.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvubzae.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyunptmb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwhrlmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjrkert.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2camdgbhk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsmwnox.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2wjiygnss.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjrdnuv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2btwxrcrk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzxbkah.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2bavqhnns.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2yipytsyb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgaabdp.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2paerhosj.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ekafknxl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2uggbtzdd.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkcfxue.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2kkctymkh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2frcvcmav.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqiaqfxg.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcvsltl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjjlhcs.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdwgaej.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsphmsc.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzxumhu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mamlqwdw.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2csooxslz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwbeoxr.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfxdzto.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlclujiu.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yiodzybw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsbcvpt.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwxmzvx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjeraepp.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmiquww.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2roprzjon.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2vdftosco.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhhhhtd.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyvcrht.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2rhewepio.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2khnqpytl.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2shimmwfy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwqjsit.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzfvoey.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqjtdgk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxkxqrd.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2actccpnl.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxighofo.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2sijsehgf.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmykswt.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2somwdqjr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyhmgvu.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2olfnsqyu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpohogz.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhpjshc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcrvwwn.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbacylu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkkvrvx.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2byhdkvch.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkrnrdc.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fumbpkzi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2gieitxkx.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjmykmt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxdvnsu.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyxebps.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvucqqxx.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2frggwtva.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2zayazklv.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gffvigwj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyonewrt.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtayntu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfaifyyy.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wkveceua.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2djdmilvp.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbyrinz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgimttg.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwtxhrk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwhkabf.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwuxhpg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrdqyuo.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzhqebb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2edqwisok.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2exirfyxe.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cbazulby.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qafwtvfv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcicbwj.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzlpjzj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlpaprw.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsaiirn.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rfaiovvn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2evrnjwsd.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2brlonncy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvghnzcl.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2umwntsll.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fogjaggx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfzxpnx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuhxjhr.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyncaja.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfersxv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhuaftp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxejijjx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwjxspq.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjglula.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtqmkue.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjlmshy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2narylzze.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vixegqon.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfewpnt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybylcetn.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbarpzy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2anojtwot.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjscvio.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsgjdzr.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpxlgfc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2aemlcjuy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpnrvzx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmdyenp.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bdouiwgw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwytamtd.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qumqrtzh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyextnnm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2asdekftl.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbpzjez.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvoepxml.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvijbuw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2lazeiiqj.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2badgwjcq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqhupub.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2thahuwro.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2idwtmyea.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqazwux.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzkjppd.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmbeuqa.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpfrtut.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2llvcycfz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2iylryxke.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmjuocz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kknfznyl.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrdzkqs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnsuczw.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2twsvdjnb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpwsmnm.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2orrmyshm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lreopgbv.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vhiqvpqq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2fblhnuax.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrorivj.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nydxmyfi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjavobzr.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2gdoofnkd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmaoeufx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cgudfohd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2efjvgfuk.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qayeamud.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcssztin.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2acslyhbw.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgesxrcr.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkbylpy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdccjnsg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2btszeita.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2odiisqfs.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ltohessy.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxaispas.html


<!-- 参考信息 -->