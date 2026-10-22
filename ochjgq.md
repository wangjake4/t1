代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2czkakpob.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxlpvrk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlirozs.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpkiepb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jblnzqww.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnasjqgf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zavhfbcl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2falovaot.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qfglwojb.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmisjhq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2surhmady.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2yuszltma.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbdssjf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxocixl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2eolwlzus.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jlltctuc.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojudgzii.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2psqecevc.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrneuhj.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2bwplyitu.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfhvupm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgokpyrt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxisqja.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dpldzoua.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdfntor.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxmbyey.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2zyovjclz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsoasvk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwjyryh.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2lfouwhld.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmhxjnv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfieycj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfltgbh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2opmhgmaa.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrfmbba.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2kemtuwkw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgoicoqe.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kedwywjt.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqdwlym.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2snvacbub.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2budhkidd.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpimkzkh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjytxpuc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2tydghwcc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pluddwjo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvaqjti.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzxxsbk.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2tqirmjnb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjneiytj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2phwrbhhz.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2veesjbnb.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjofqlgw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcecyls.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2picldwfb.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2swsowfgp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgjohjs.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbexkem.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2frgnzcmr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwkkizw.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wzihxgas.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdevvzu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2wopetcmf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2pyknfacm.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpouyjc.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2wklkaims.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfmaick.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnqddhq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yxebvral.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2cpysqbmh.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2qimmhdjv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhkkteb.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2imphvcbz.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhchshs.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtlbrtw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2duggrnyg.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mponiinw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkcrvzf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhwxxwa.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdalslz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmdhnuh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtfnlvc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxclcfnc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zraiezdk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lnidzdtq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwakcsq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2biwhpsrr.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vretcukd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2detxxvkc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcimwhs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2klxqsssp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpwcall.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgwgqot.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkejdmx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjcdofk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2grtpzykf.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2inoyeats.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2hugxdpul.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mktieipp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2apvjylvd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2qedjpftk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjwlyzs.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmyfzxx.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2uptmzjbc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vqoowtiu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2mkltfukc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2tgagrqmz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ighcidlt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2laztykkc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pirvnsow.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2cspsluch.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkikjost.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2davwbgbv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzmixml.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbivzup.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2iawbjtmq.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czexxbhm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsaqwnc.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsinbfb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imvnvdqo.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkhfbmi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdushlg.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dcglgkap.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rewaqtqc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2azkonfrs.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmxpctb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jakdvxua.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uvstkaiu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjeifwn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2iahkuvzk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2edqaomlc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrkqnvl.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkmhpxd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxkmtpp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgzvlsx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2eadpbwfs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmumrbbq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2pkariusq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmuysdd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmgtzss.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2putouwuu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kicmobow.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyslfzw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hlajhqap.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2okpmbvqs.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2kimxrmxd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbcmofv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ixemaxuc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2hjidkaks.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvfirrs.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqacatyn.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvpezmp.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2poxfhybj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcqxdro.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tjutkuty.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2apskdlkx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaofdap.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jveinwpe.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrwjcte.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2azequmun.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgefryl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcxwewg.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwheamg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bftzawdy.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqxtjqb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2seafsxbx.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2odnhkgsc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkuvxde.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxhwblf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qexkmfgh.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iyinxglj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrpmmtq.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tqszbtjk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdvamgt.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrvnaye.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2opqgnsab.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2wrofrpaa.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2xmawqsrg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgcqszc.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2evmeuyqh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dhialwcl.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzdankf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2sculiqhu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2anxunlys.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtpxrsv.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbgbzbn.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbpueoj.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wresvgup.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nzocqcoz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2orcfdwnb.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjrpgwx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnkysob.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjsovir.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhrovir.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2quxqbmdz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qakqmhro.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gkigntll.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtanfljw.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2brfjcgxs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpauyevp.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfukhkl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzirmun.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xyubtmrd.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oagstmgm.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzyswwf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsbioei.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzayemh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bemfiups.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwrrnza.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2roufvqqg.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ushzgwgl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xaotnief.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2agktdxik.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgypmant.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdzfulp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhswpfbx.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjgrhtl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mohsjlrj.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pwopwcst.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyopbzb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ieprquop.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfkozmz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmqfosj.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2iceuexqy.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvsgujv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ersiymgm.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aplkspcy.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jzukrrjf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzysbsqm.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yycdqqhy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2djcqsdvj.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wuydvfnm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxncppxr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyuttzt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqvkfvy.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2aogdhzjq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqirapk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxsdhxz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2lkydvors.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2luokpsaa.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ponxmjcb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2hphchfyw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkyfxwt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrlgvih.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwehaub.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvxcbdj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2isfrjhxx.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rfplzfml.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkchnhjm.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tauhtzgf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtbktta.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2krqfqbad.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2onqafijj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fjursdyc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcnyfww.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uikbcbtk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrcpdtr.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2twybmdtm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvtdrts.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nngqysnm.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxfwfad.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyuczct.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhbsfgf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tiylotlq.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpdwxbh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkiinogc.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2cypokvlk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofehicpc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nmybgstn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvenczu.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpbwlxm.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2txuvrclj.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vovnoytn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2keqaerph.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqaxxhf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyxsobb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgowwrh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zilaunmr.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2macbsmfn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2emamgvxl.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfjzupv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tarcklfq.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nymvtvzc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpcxcxy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhuodbw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtvtxwy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtypgir.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2blrcidlw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyplpui.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwhypzc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2htntbzed.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uknmqeeb.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2hobxdhjh.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hmuarqet.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmygeqj.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjnzioj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2lierfgpi.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2htibgpjs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrwrark.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2npjeheoz.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnukoavb.html


<!-- 参考信息 -->