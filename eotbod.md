代发 wailian999

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzlqtkg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2evbqbxcv.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cpktzttw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqpbdod.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2fwptlgxo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2oycutiah.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2awgynshu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2egaponrc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpjctpn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjidkyqh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmokjkdf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wedhzqua.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hakzsuwc.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2kobaszln.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2syidismx.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2pevfxkuj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbaktdwz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lsiobyhc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2gxknprxy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2kclezuva.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2levxetnm.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdbhqwr.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdbquph.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2enmjdpiu.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2duvoqlod.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2khldeiai.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2isfzdlel.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqmbzkw.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2czvrohcu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oglqpsbm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpwxqeg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvdolxy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrunkqh.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ddalsgfa.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjzebmb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjtgmyh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ynznprno.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmykdmf.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sptfrzyc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2yquycyio.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzxaipd.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeocaybs.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyviwuv.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2cspkzjrn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2odbtksxq.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxstzdj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqhguhw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyvbcyb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2djmweanr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2oetfdkli.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yscovzwh.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2gipypmcn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2npyzkpki.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2vismqkag.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfuctbxi.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2slxeeasq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtihrmc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbdljye.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpotefdq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2plrvmull.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjiirce.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2renithcv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxilpji.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2iikberrj.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvnggyr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkcxhyp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmzmphz.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpvqwpn.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdnrxoh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgawsqk.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgyyjdh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdhxazf.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsnzdyu.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2lccxsvel.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2chiozvmr.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2luqslgxh.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpovkpa.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tizevvip.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmeliyu.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpmllez.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2looceurn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2lfruyxyd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2irtjrguh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wynwozxw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhwnfqo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyjtoav.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcviabx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2afxvflts.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybloewoz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ergjcuod.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nvseghqp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfhzvzz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgsabcn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsrsjyu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhexosmq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wolslvpb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2obwscdwd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2elswryrw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ephryyxc.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rgohfpkr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2grfbcpzm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wkaqjliy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqmycsg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2xftrnlgk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ummwvsxw.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhixepoz.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqddtqw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqmufdt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhhdsra.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfymawg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2bbklldnk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuejpmm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zacgttmg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2trdrrevw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvrdsti.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2wlniugvr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2yiouenpo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2prfemgpv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2etojlfww.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2furdbujx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2tuiexrqi.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lncljtzw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpneroyj.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szsjjort.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsbofhd.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2obgwnivo.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqdjarx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcieuoe.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2flukmvrb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lljmucmq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qsuggpuf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mettsqqu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2xehnixek.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kirovbef.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbpahzv.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjxxxxo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmvtpug.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtpqren.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2xpugedyx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebflmxdc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjwnbia.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyrpqyr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvljrik.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2izgssmqp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbdvuyb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxepiyau.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjezhik.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2umuhsxxh.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2dyatjctp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xtewujsz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwyiljs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2glbbrpki.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtfimbq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwjujyd.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2bekkkbnr.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ishkszrg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kipixsrw.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2pifwwrwi.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2fulzwqzg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmonpmhd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfllcfyg.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2qdttwolh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hytgmgvs.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvycigq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqzfilz.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2wserdmkl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfnjazx.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2wutvinia.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrenzay.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwaeizf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrhtyhc.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2flnatnfm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwpzbtv.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyaokcb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrnnezf.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2adllehdy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmshojc.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsawpwa.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnvmnot.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2deaorwoh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2apxlwpyt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2uacaptuc.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqiwear.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2plelacyf.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2vblpiivo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnxhfsc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbaxlgxe.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhldwio.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvigprxy.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpfotar.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ormnjdur.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbqtgtx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrscufil.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrtajul.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqarzfd.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yucgdnww.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnebapx.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fztacytw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxxbvhc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjywvtl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhxhfnm.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2graphkxf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwvezzi.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqizeuz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2leoyjsuf.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lnncxrap.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnimsva.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2huflzkae.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbahgem.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cceujsin.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzdladm.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqloomrn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mffkrtnm.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2famjdnri.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfiqzbb.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxrnker.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2okoslztz.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zmiklnje.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyqwcvi.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2epbdkzpc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lswktpar.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzzpndz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxprpvm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2prxcetzk.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2emjmuiag.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyybesc.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2jydrybzl.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkoxdej.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2bnietajb.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbblzsh.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cvexdwmv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2srbfhzqx.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwlazeb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lortduca.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdsidkm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpkkphz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppaguubo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2snqqpxdk.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qyiuqcid.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2auvscybk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bytfajbw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikuixtru.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhibyyn.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2unxsuqkp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwjlrxo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2oamjukwo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzlvroj.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2adygoikr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgwkwln.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbivjtg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kystflxc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsipkjq.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oscmzxmu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbywidya.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqvipra.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzbmgkg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxegppv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlmztar.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2putaixbv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2xavrrecw.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kejldasg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2matmgobu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kedayesp.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tchkkucg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaaklmtz.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wtziblyu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhjbkhj.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2adwulpum.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2obdctukn.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2rltguwug.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkocuewc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbhcfwb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vgiiqnpi.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2hemizfja.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbeethjr.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jcokoszv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2elsjkupz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nehzeobt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2sncldwws.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlrrtpo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvyvhrz.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqdlxiy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvtyfgp.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2fygvmkpw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrdiuor.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvlrjsd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzidlym.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pagtgbrw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxtwnra.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbadpei.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2hqskztpd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2btfvtdtz.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrzywcn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjsabpm.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvyfbrk.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsriult.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hiifxknv.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2hotcikne.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkbrsvk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlgxwaf.html


<!-- 参考信息 -->