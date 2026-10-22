代发 wailian999

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kekcmzwf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2azuqwdzt.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iighcrcd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxwwaea.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2iupuyznu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2tueffuuu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvwgvkk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pezhoiam.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnvzfhj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbppodzr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxensyep.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cobbdczu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vckgbgfs.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2uzerajmr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2shtwhubp.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2swukmhnl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfzumwg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rgiobbwk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2pugtdvfk.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rgupfmca.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zieeunrr.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbttksrb.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2npfirsps.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnuresj.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2znhxqkho.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsttqxc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qrheccfs.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xaazcpej.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hwviymgp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvtvoif.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2vagbaqep.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpmtmea.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdtwilh.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbjskmc.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqpjkbc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2djbmhrfj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2mrscfaox.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2obiayxxu.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqracju.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcswchy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwvgpuz.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckanmfqa.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfiuqfd.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2qibjihpf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnyquip.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtookpwl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkglhrti.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2acbkavmi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2meqstlyb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2szqueqba.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrzytmt.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwoeuad.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2idmduoes.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpfnxku.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoycsicz.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hutbgjhl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmujyjvn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnydasqw.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdmtfry.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wngtkvbo.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2oefamyyy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2sviwamis.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcjlpfm.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2cbevaigq.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2htduudpg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2obnriijd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkawbep.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgbblsq.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2avnvhsvw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzhisag.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qkejtcir.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2odoaxhob.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqdicum.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrwujaj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ctymowlr.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjufekif.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mthoggzw.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwgrvzl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcqtxsy.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2syvxxsnk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dungytde.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2spjcrpsv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpimgadw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2atxoueso.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmpcblq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2bswxhesl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxieitpv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2niueyxux.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2svkvbmbp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgvnnas.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yegcczha.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2flkxzknc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2xflbcztp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2osyizvhq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnysbapx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnpvrrn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbtiuir.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgujrhv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wlycxngs.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2emabtggp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhjwjmc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2loswnhze.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bpspkyth.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnbroso.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2fiovrnle.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbkjohj.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qxauinxg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzrnshf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2oizkcesx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2khtnpwdv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfczwdp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyouous.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrcxjss.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2sfykjdjx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2abpqvtrs.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2toxmvryj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmbgzxp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2igemywuz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpmvzcs.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tcducukp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwuwhae.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uthwyash.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nijnqcsu.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2geqozipr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrejzaj.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzjxazc.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xviebsct.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2emelhamm.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbbauis.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iibepfsw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgvjaub.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2thelghdh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2hdypoisv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2msanjngf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2htbihypn.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2oproypov.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gerfmdco.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2whprtuhm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2pdaxavgc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2brjbgpfd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjuwtgb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2mocblddj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpaabwfa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2pihbhxgm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ibravfse.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxkutna.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2swnxqutu.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbxxfhh.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2mxumqirx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wqoulptx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ekamkvbp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2hkigutpo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2livcmxdh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhtkigg.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyekyft.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2twhzdwjf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwmknan.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzckkna.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2idfaczqc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsactnqm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvmcxtj.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2iikezalv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyabmxb.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcdpcrb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwelrqe.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2vmaafvba.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdcvpde.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmcinej.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmuprsw.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2chgqfzse.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkreiiq.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxanufw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgwahcd.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfzcnjz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzadmhh.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2teelajbx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bujfbzlt.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2nrviyvvm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2yizgnrlb.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjhirsv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2yduumtra.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2bguuptoi.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ttotpgvp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvhoznx.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjixazhs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqbcpmy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2iphgvypl.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2flwasxhs.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmcbonv.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrgbkds.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lymbficj.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwhgfgo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwaapnp.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xeypsous.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrowydp.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2obeedgih.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2holarifp.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yulnopkg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtlfhkn.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2psfwvnrc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2achkqmme.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdyfudc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqvseao.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtwwrty.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzknnekq.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gmadfxgu.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhinonq.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbeozry.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ereehfvd.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfafailx.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdxgtyj.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pzisgzmi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sssxbsni.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kzejuxqa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzkpjpr.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zmytvajt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2trwwvhds.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmtitkw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmtpfbz.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqcmoni.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcyphom.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lbftyuoh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpreduxd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ocntolxu.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kiifjsmh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofiflwkx.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2lrupsuby.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2alnxulng.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfeldyn.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmsopfr.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsiedri.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtnkngs.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmjxldr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wegkbvgz.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2raeitqce.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2knnfegbv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2enhrpimf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2blgnkgxs.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2eeoyszkn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2amzcbbqw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbkilbi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2glfymaqw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2weyjtejx.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjegrun.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2edaqkryg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2zekyrbyi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwfzuaq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsksgzo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvwcdbe.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2huzlyoqf.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2snevdhlh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvboyxda.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kodvongu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkcqdup.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iumcthlm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqimtrzn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2okakdsmw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2doepsluk.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcyyidf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyktpsqa.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fduaicgv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqakihgn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkedaoq.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2uitjnwfq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdunkuv.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nkibdstn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqyrrjl.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkyeplp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvoudxug.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ynonkjfz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkptkcm.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqjdkwx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyrnkeh.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2yaoclmle.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2undphczv.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2uegyqfix.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxqexno.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2uueanqan.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuphjpoi.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkxojjt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnzcten.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhcyglc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2izvsluxn.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgwwmwy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2upwjqgja.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2aebouzgn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwzjytg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvvmrir.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnblcfm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpmvchs.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsjpeik.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2uubsnekb.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2afvzsojz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qavwxnfc.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpmnrkk.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwgjsyc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2aeavvyly.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2tagftnma.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2whwloqbs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqazfawk.html


<!-- 参考信息 -->