代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpogwga.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2mymbpkgf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzuyfzf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ruuqqwyn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2edakeqma.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbershja.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfwgswa.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmvdrvg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itrzhftw.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2brxyeecs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yksmohvh.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2asfzepda.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsevwmn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsbhosl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2beahksvi.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvwqnwj.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfextpdu.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2sambgxhi.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2khjaiuos.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2obqjyfsa.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxmqzxw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bznqqqmy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bmogigll.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnjexuc.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yskgfqcu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcwouuv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2hobqclio.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2cfywzman.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2biquttao.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2papjamwy.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2weqdlpwg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzggoml.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcgszck.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfqipaj.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxhjsyu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2teymjxkc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwoegueo.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nappeyro.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2yjluwser.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2psglzzts.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrrkssk.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lspkwtyo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkykzrkr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmhpcnv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2twkhviem.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjufbij.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2daxcwfgk.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnnjzdg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzpwhyf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ydeqsnxu.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhjdtcc.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdjbjqk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2sycgibnc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2exrchdmj.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2rngcqjeu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjumyorn.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtkwofd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxtymui.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfbvrca.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpgxfna.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2herzinua.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2phynkqvu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2adlbzqej.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2mxotdxpu.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2gvprbckg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfsgwhw.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cyavbwzi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wpverkmn.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdwzrna.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2gxryfhfn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2buacavtt.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtouher.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbtlyfg.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2oindqofb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yboevpom.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbdidcn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qylciyno.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzwodgw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgqutrk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2osdmdprc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2eokcbvwo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmutrog.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhqfvlh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rkccxuew.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnapjtiv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2brlxplrg.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpparjq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmiuknn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuxdfoc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvrjxpq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2icdaoqcp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwzwgxu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2glkyvizl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2webbhicp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdzvamv.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnuexlq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ityzxdcx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdofobk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvzjual.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2akwycfud.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2setnrhap.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2xztrtvhj.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2euoeiapt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tjblcvfs.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2insurcvx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbquowa.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwggwwv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2lanfjyls.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gumupomc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2spmkdrjs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhntgrd.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbifuor.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2rebobdol.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2awozxkrp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpwyfey.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxjtzqc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqhdnto.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tconqclg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iktbexev.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2riwaundd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2adkwkkwu.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xivmbcwx.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnytwlc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpsdjkf.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrstbvv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2quaecdcd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzkvkai.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqqkmtg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2klasenuh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2smzdlzmr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cijnokwp.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2onokbkom.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rurxmugp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmaiwvpl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkkvhlx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwzvpop.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2pcycxgtz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrhnbfi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjzwptp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2knoeowzr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ackwfyre.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgoydfau.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxojrfo.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2msfrciti.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2hefkvddh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfqzklb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2shewvema.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpawwbg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdfusmd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxcaooa.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcexchg.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2xinkbrsb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2usxjkjiy.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2pobiagov.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2sszgifvk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2wipkwlbw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2matwnykj.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2kolrslxz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahptahqk.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqdwftu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuduzvlp.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2alvjddaz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgsrkaw.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbgdwmq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlwcyeg.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2tjomteni.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uewepmkh.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qyebtzar.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrorpih.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrhtfve.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nikhwurt.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2csjtxhst.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2visboqiw.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjsnvfm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ravsqimf.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2rehxezdm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfseeal.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkrrwii.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2duoewvul.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcfgtvr.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwqjlvl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhgybpn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcnmffg.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfiuauv.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkokndbu.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ocshfoko.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqpbpmu.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmrexol.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjzncrh.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlovegs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2sqslmpln.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcdxhjr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2goukhwbo.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jucjzkop.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxktddz.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjudedl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtujtlll.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkveepr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2omoiacob.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2keibkydn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2evlwqmgi.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjbviip.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcvqxcy.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nbffwxyn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hivwzjpx.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfyylui.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqkzvzp.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrawbgq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zewtlbja.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgjrlkt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2trzjclci.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2uoczzkpg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlodjrop.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hedqtqyc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvuwsufr.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjqwwrj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2petlucbu.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2edryemkn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbzmtvp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmegvvc.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pydysuqe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjzopdk.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2xutgcmdi.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2obobrtas.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxskvpx.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2inlamchb.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2izisjgrh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfuumayg.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ruuxdxde.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dggmkguu.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kbclmrth.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sseypxov.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjloyrs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwrlqwj.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjmbzyo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2nnldadku.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrmbyyz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2skqjozhf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqukncnu.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eaonstue.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkwyqze.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgypbhm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwifcxtx.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bylvpiai.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrjmkil.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2frojgpnp.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2khopaylz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2jovyynce.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ppryizjg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrprhlsy.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkwvhif.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbidubq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzsjave.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbgdjya.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlvbvey.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2qofvldcy.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgbckan.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjygavfd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbypscia.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2uavvoaln.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzozvqf.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2obqseosy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmigisu.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsgmjhm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvpvjev.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmqewed.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jecwuohj.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpcnwez.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2psrzkqmf.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkcjgva.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjanhlgo.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2sejpskjk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmiswemm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2diljeyof.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwoazuy.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzeudby.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgixvxv.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxyugck.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oobumzmn.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2xezgblog.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2enowkysm.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fyecjinb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2imuxhsgo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cysiisgp.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2awmiyowz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjknfjyx.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rumeikne.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxiwwupf.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxkelqg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqesuee.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzgvrik.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzupmkjq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wleucewo.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2sasrypqb.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2usfhmlgc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgoyeiy.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2nodfwyrg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2afdllnhz.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2xisjcvan.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqpsibm.html


<!-- 参考信息 -->