代发 wailian999

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eujveawb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tokjgnos.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2htezlybl.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2odoqqeid.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvvorpi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2pxiefpyz.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sfagmqmq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpalofjy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsqnfli.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2iroxdsnt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvexmsp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxfxwde.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfnbqty.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmtixhw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhyrywq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbrncdc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrikpyw.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2makzqsls.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tempwupk.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2eigsuila.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2owwqolop.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwjdikk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2rvffosfk.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2thrqajfw.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dncqtrfn.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2blocjcqq.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2yccxdfws.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2thurbofy.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wpeddobk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nynyheyq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ydeafwqw.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmzmirz.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qlorviup.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzwgpjm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2roejennn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2zubzgulj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2nesaqpqw.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2czqsuecn.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmiuntr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrmdfll.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2vnftphgy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtfcyml.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxuiuwv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcyflht.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbldccpv.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpteecpk.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlzmjky.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajifqhtc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdyscly.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwackwkv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yelvfrxn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2raktpwvs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2uctiknqn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2zieibggu.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cphzvuee.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2aczxkfxk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2barcfimh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqtewqc.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2axwaksob.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkoxfsc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2blzfckxu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdecobe.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmotrhdx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kozccjmp.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2smgkrour.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2nujrxmap.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxrkxpo.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvzxmvm.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2rvplthrj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2yalfjiun.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2xljlhivx.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2onuyeqrr.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2arcpkqfc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2enmidgtg.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2enppcqzd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2osvssmhq.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvmakgb.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxvogfs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkreuew.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2twfnswre.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcglcgv.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxclaqz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbngzhs.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yfaxbwgj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyixukh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwrrgmy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkoozefb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2curkuexy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2pukyijzk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2amsqxfmg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2nobsfpbm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvsdftu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cueftzhv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ftaacnue.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bglvbqhw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjarxvd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcsjxnq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zagoajgd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqefrhpn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgrrlfe.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2asffexub.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjaxaxgm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsspaeo.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtiscwf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2plmglpji.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzqnfjk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhdcikl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtlmcrk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmtnwfv.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkpxhny.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcyidwn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2guynhnxa.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2cazyvdjb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgpjuro.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2bqneykia.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdlklnp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hckiisxg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2tjolfjfp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rokgzwvj.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxvhaoc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2njqbgyde.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryorvjon.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnhcajb.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yokxyyas.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2hdexidhx.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gykigzba.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lajyzmnd.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vyblxsqf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2heovrweh.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2twjuhqao.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gewdfkaq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnjjmbn.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ueozleyn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fuptsiru.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cboxvtro.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcnztin.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjujnud.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fypsjvdj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2arvxepof.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2fdblgvhx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffllntfa.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhmgley.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2bnweoabi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftiilahi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvjwtmv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2epwchkid.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2cghsuhho.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2drxonpss.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ejphdnhj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2mryrfeoa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bugxtgby.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlcqtsr.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2agfeopex.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjlggcg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2hexlkcpz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ioybyerr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2nitamwlw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsauwkuf.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2nswscosn.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmghiuz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tteoypim.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2olypjqee.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmyljsm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwntxbry.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgerreh.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2uingxlyu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jitxsdpg.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mzflnivk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhzbtcx.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxishnj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwislxy.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2brpuwdwu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtvpmul.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmbnwkp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpsswyl.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxcuews.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2koiihrhj.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqatgfa.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2eeujmxop.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2jkedqgob.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jacjzvji.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2jyeambqq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gfinjluj.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2bufhyqxa.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2janhbscc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2eahrclgm.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2sphelqqc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzrfmen.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2fawnejqr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyslqhz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcpdqzh.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvltltn.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vibspeqb.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrewcro.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xchoklou.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xematzpe.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2skwhhmpm.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpwcpzn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2djjxvglu.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zeogkqwn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2syonirhg.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2guruvtcp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrcvrwe.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ykduuqgc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfiadtzr.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsuqcuc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwxkbyy.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxwjjlx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2noeqlrtt.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wuraodhh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zeeiuqyu.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsagtzg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2uelxujaa.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2awfglvgq.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vamxbegi.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqcfsqy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvauuio.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfgdebm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzqfihz.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2atesxobn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pshuitzd.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmqumuj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rehhmhje.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvhzepo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwgrghr.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvvxtca.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bluoieiy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2eoizzhqs.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvyjgea.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbttwtn.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgveybv.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ywozexnz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnbzdhh.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhicravh.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2powoggwg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzuadbs.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bkeuravx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iodgmwas.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kyoyjvlx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkepqdfb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jiltxrjx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uunusezt.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrtfkhx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2karxdedy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2drnipcuh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2zeasswjt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbyzjzq.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmqfept.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2inpkalcj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2isewtrzl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnkpzrt.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bramynxk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfndxbe.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvegpze.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbdzhxf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqdjgjw.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qzasuipd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmrjjdj.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2usbrhwdh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pthatxvb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfwfhjp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2aswwoadu.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iidbrqzv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhymagag.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2znjfjgub.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2tngcoiro.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2iygkehyk.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2luvltrkp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2quntxpnb.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxtmfko.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ksonsoff.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvwkbku.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmxizjf.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzossts.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkfpfic.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfropaa.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2enmcrlsw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2dyazthhw.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmmqxaa.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcimacua.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvapykbk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjdbjtx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkixwoy.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkljogd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrfgwae.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bepfpmou.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyfirew.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxxhdmv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iktdhafz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cmiqvxwx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2plclhyiq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffblcyzz.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qarciowd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2knyowkih.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2gylrmsbn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2icybkwkv.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxrprhq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2lncbbzeq.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlcdwri.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2euvgdnhn.html


<!-- 参考信息 -->