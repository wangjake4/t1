代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2lbssqujo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjywhkn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nwefpwba.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmdhcww.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2eupgcada.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvwhtnu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fipnpofy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yyimddvj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pkopfrtp.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfgrazu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dntdpbqt.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jammxotn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2lyaozyke.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2enecbfdg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcrpojv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwwxgzf.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2swpgxwww.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkijyyeg.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkctixe.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2pdalrajm.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mxeuvcxl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkcizas.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2swkrvhqs.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfmqwqa.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wlopycxv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmfdhfv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmfulzd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnnjaoa.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2rskbxxmx.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2avkgqfow.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2imdladgn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2bminqyvr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtkyctv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2iyykznha.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gykgltkd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmjiiwf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vobgqoiu.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvdstwi.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nssgroqo.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrxzvig.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2qfruanyr.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lawnwmjw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2maglxyjf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrwnbza.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2sjoelpbk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnmmirr.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjduehlt.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjnxpxs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yztesfat.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjvzbtz.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcsofuf.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jblnsxzn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2sylwizdl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2krhjvqgp.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuawrsvn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvttjtv.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pybztpxj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2eesbzlqz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bakmossc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhfxbau.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwjdvin.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2gnunwiwl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwshckj.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2meeozbea.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2yskvrzmo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzugxvx.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2swnlakbh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lylrzlxp.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsmoxdj.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxylgxp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqxxkxc.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcotefq.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2entgjgtw.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2azlkvios.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdedxvl.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmzzgap.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqalzllt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkqyqhj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcllyft.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jokafzws.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsbuuun.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2swyjzzpl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2crnbgxga.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2txlndawb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyagtvpu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsyxheo.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ulaukare.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyioych.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqydszqi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jupshmts.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjriqro.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbakqmtx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2twzkuclt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvubwfqx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbmuiwc.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgopmly.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2xloinqvd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2swgrdhsb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2azfqfjdm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2qkepwpgg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrwavcv.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydynoyws.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpwatny.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hmeiqldp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ookwwula.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rswzeosu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtjilhr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2swewkvuo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsirqotg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2sjogmtks.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oieadhwu.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqyxyib.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjxyeql.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2yelpchbo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2baevvsed.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oeapehqg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2mospgiay.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jehnubdm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2abmxiyum.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrtiayi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnabtovd.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nijneoej.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2tumotdsu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvvnkvv.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzarjfz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2myhjmstq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rymvdnnb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxeuxryf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2dprhqyzx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhagepu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2krmsdiff.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2thdgmprc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbsjxno.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jepypixt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2obhlvuea.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqfvwmh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2tpradrbr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2yoayfjym.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2otqzgelp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2pvceqzug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqpppev.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgneboe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2azobirhh.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhgjtvz.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2avummzxn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2cbphmhnz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2abpgniku.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2iwecudby.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2bphbzppf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2onyvytiy.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdtihnp.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2apznsudv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2fqaxgcoc.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnxesef.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ifntqoyz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfryjer.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2udltdgbo.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkerzql.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrpmphb.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nasebebz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vilajiuz.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2uoiyqmhr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sidiompw.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2acartucg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcekqshv.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdcovvp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkalwhj.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxtmcru.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2eiclidgv.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2huugixxh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2aibawrvu.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mveyjnxb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2atqzieew.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvklgxk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvdhsdi.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrznwle.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2hkscsfvz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ephumuoy.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvkukby.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2htxldtgo.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtretgz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ykziebxz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2miupczsu.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wrepwmpf.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2azuahswn.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2guwiiacu.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2evcqwczt.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpvycsl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhausyx.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkpsavz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvvfklr.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2whuhlqgx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzeqyen.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xpseoumv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2escqbrxd.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2odqkobjr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcarxfvc.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2igfuycmj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuifzrg.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxtapuy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxbikyt.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2nftxuefv.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tumoarzu.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfoqhmo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2palqrjcg.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wzufhbmz.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2djqgrccb.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2txcsnnwb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekevmsou.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlmjnsp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyzpawf.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsbtgdr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlctnfx.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fqoitrjm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwedbmf.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2towkedsx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jspeuypp.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lwiaavef.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvkiksw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ggscdtuq.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mloocthe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfidhgv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ylliikxs.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2xznuocoa.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvlvzgp.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqruhlz.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ysllivgt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuqudqr.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwnufaz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sepgnpzv.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2invdkopi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2apfzeedo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2anopgihc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueesduuw.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgggxwmq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2eatbflhh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qydvxwod.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvcnonv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzetiwa.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmueqni.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2grmlkphd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2zpymrqlz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oirpzsxc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qwycfxvy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2kvuwawfn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2comafzwg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhnrjir.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfxeowy.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wmanlyda.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcmgnuv.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pobkzium.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2igrbqogu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhozbpg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2iejgltup.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnggcdt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnuybkm.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzgpybu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2wunauepd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycllszuc.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2svhtkenz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlesekp.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2goruxayo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvyuhbt.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2orjapooz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zarqjyfp.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2gymsvdpq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rujbbdsh.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgodmaz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kicntfvj.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvthkxv.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlphuovc.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2okphdsbw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2socpwyyl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpdgdon.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpqopps.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xggrtmzh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbnaabv.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2avdljuyj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjaxtup.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2oqoazrwy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pperhnhc.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fthjqbjv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2uqaiyxsr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkxcncj.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpscdhs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxeikhj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2muhytxrz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qloslnye.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rfavssmw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyvtdco.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2befuttvi.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsmgymz.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xpoaanwg.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxghaqq.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iajonedx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkqqpwq.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpaqueh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpqauev.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqzmods.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tobemexw.html


<!-- 参考信息 -->