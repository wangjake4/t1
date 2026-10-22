代发 wailian999

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dsauyuqq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmjpnbo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgteipg.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhrvria.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gohyeutl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2iofxjewv.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2drcmluss.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgptfpzz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2bghiuvnm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2woieqzfg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2clsqozyj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mhacejlt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sfiervic.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwojcdq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2waqltfev.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2raecoqwv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtceihh.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2rkihlqle.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yhimzvky.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxijcvg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfliapgi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrsrkzt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2yngqaqry.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2szedmiuy.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2crukuylx.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2buvsekua.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcutuda.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ksaubddo.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkcphwt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kncqmvep.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2eguamhlp.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwqfhcb.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2eapdohfq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2relscfno.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjhjbki.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuzxvia.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ewztwtoe.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2syfvbwvp.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtclxnr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdujpys.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwzabjn.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlebztw.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhemqqur.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2wixzbqdw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2llvhfcgb.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dekqsxmu.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxurzwb.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzrvhne.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2lagileyu.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rngefjqu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzopshsd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2umutwqao.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2iksryspi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqlblzg.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvygzmw.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2aggnhtyc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsidbbws.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdkzdmq.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaowpdju.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2skokeqgi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjoynjp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2qquiamny.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygomhcuk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzxrndm.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pedjivzl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwmbrov.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2doetmros.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfjrlvd.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrzyqrr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2obkzllhg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2umxxgyjq.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2yejsyzzg.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2edbgeptw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zohmbcca.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxawnxde.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dqggfosp.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnizsmu.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkncpqb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvuctpz.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2moztlesy.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcpnhvx.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2viybxqxc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqrcnfz.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzjoqyf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcwhrbq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2rrthbfxa.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhimvlz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2peffltzw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxmladc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2eriilteq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2xktnkakj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtmmvik.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfueech.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyeyuzw.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzzpvjk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2prmktyqo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2haowzwvc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uewyidtq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2igriskod.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdljsedc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2moiaajvu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiywdrel.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2luhbjeyd.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyhwteu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2qavfclaz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwefwcu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mimjgjvi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2omthcifw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwikcypf.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuoywsws.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vxakswpi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2csqzppqb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsyswss.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zesvtfyc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2tgumksel.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2shwexcyh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfvvykz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2vmruytwo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqphonyk.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfylauq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgrrydx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2huroeqmv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2elppiumn.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxpsmee.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2eldfcumj.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aylunkbx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2otarthvl.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbevhdym.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2srvnzvrt.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwhgchj.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuqfvuk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpkxbcf.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fygloerk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuapksl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zqimaduf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sakjqvit.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2wngstmah.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyiaytk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2kweclufh.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2viglzxfh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdyyigk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2arzgmdbt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrjiltv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wstublmn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2rieykqzm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnneuqi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrslmar.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2kabbmrsf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzonfcf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqipdxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mktmjdfa.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2vupudiph.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdbyxuk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxeqdyz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kehztofs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2owhrlphj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpnqjai.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2flzwsrao.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2rchfzggs.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2skifqlvw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqhvdvp.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2peezxbxk.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2szymbgdn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqbbwdr.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzeirzd.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsmovxi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2aivujyne.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkzwucq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jthgbixx.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2wszqjytf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kekasklo.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbvleeq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2fghsexfx.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxvpyph.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmoelyth.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwzchbh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ridefrmv.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2trqivyit.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzsedbm.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2dstjdtiw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2smtbyilm.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqhucpa.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2coieysyo.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvndtnk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtqcqkr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmoudvd.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjuakmw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2etwgdatt.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhvdlju.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbcillu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2faqnwufb.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wfugbeau.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwwxcea.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmnyluo.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbagtps.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsxxnoz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jumuxjey.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mfakvbdj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnmddkr.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jzloqzdb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2zliyjwxv.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfwgiha.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oovcrtyh.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sybkqrbl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2plmmtjtw.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwnsoxj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2maqlfvpc.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcnenlb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2efxfnzfd.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hibqtamb.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnsgiii.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgxbgix.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdjpqyt.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2objivgaw.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgpsuve.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyxfwwb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzntpml.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqzrecr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qaayijgj.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2piauijbx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtmhlav.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fszvxwso.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2usqwubdy.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvrzcak.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbhphkw.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iykmdnzy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgjxgsq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2xneoxjek.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rmazqmwv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwtkcst.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2aizlvxbc.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbafbtb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvgldsr.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkyidkkt.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nymkbbzg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkqlwvk.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfidjjw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpldwkg.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2flnvanpq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2plzinkqe.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2mihoabmk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2denbwhll.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjknvme.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwxfwty.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqakqaix.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2suacdybs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtnxucf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvcdcvr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2uoflyiok.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2aylpzqqw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgmnyga.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2akktxwxu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuxtivv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuubpwoa.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnfgmos.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifarzbro.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ukndkdtz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtgpfcg.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tggqditm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcuadto.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pnphetbw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsacejp.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lpngvlsv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2pooyrglr.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvdyrmq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2noirlbdt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkupdzz.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2skwhuzwi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2knbrvitc.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrpigtu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtgdyrd.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2utxnwsxp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoakkdfe.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtshfxu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2owqpifjk.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wutdbgrh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2blbzfkfn.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkidlkk.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgdjwzu.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdkysgp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgaxgemx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvchzcq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxonciw.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzexnxg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxpgogh.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnjmsua.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wveavwlx.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyojdvw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdydwbv.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bjatqdzx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2onxqoxek.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbghzrs.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxvnrce.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ownonjcw.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfkvuwl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2quixmupj.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbleuft.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyczfai.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqtymfk.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2evjooxbi.html


<!-- 参考信息 -->