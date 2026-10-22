代发 wailian999

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yiavgapf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bbntixve.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjfxbvq.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jozeampa.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qanbfdko.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2dhemkfem.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdyqwxm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2twggbmxh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcnekla.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2npqqcapc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2samuuwnq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwoefmx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2efhefwxf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zojwzven.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfoydle.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhltxjv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvfacog.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzxskvr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kynjashp.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlgiurq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2clgbabjl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjjrixg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmoutax.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wxellyka.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2stnvgnzi.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2lholweow.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2fypqnwvr.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxkvmjn.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtishqm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2shovrgml.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrzccpr.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxfniez.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ausphoql.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpxxqgu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrwgwty.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpadknm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnoqlxc.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2txedwcun.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2shwffzry.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2tndiueah.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2qypzfamb.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lytirqfj.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sovzdndy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ieiruvuj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2itghngtp.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thgqjrdb.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2haknuarx.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvfykod.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2eirsbgjj.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuflryl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lksirmlj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2thxyzutf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2gwphibkh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ckztbdbb.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxezxgib.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2motgdgcn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulblaegc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2kurwuvnh.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbnrxxv.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdvkulh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2qiuavgio.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2lrazzehn.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2xunppdyf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwxbymu.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvziqgq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2xojypovn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2perzfokb.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2maqsnfqp.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnimdgd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2shdenohe.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2dwesafsh.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2qugbsmjp.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2erpsxfdq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wdiavsjq.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jedwheqm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2elaezqon.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jelrgpmq.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvitwvs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qalsirra.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbkxozh.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2cafdsdjs.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sttypjcz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjpgvln.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2acnrlcxi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvyohvx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlmexdq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2aufpkbpn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxiavmhi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2gkipwbht.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2dujywmef.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnlbbgz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxawgqc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbvyjfh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2itdzutag.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ubeioeen.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2xlusyrbu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmmcawa.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhumohdg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmhecdy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2evpixzko.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtfloub.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwiqbmds.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhaxlbj.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gsttmaqu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmnqxbk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2crifnzgr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jtovraqd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyzbnah.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnjlwsv.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2nftfhcpi.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2msxhnzai.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ztelqnwa.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjmfupa.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wpiieqcy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlqqjqs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2lklreoor.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxieyfov.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2bciwybwh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eieiesvf.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxkgyvb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdbdsiu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fafchmse.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ncreywwe.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cgiqeyrp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2lznkfkoy.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mawpcqqm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rasvchbl.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrazvill.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbczhgvp.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oteitooy.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrczlir.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvvkcpn.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwdhthh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vitzyvct.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2edxljgan.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdskrzn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2hwarmjzj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzmdpse.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwqbkza.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2xbobdfnd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdutwoew.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybreytll.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2icxuqyyc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqwdgvs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvdmqvj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzubtsp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2lptxatul.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnfqnvh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cynvyaok.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmlsnwr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvoikup.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhnunlz.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvgjlah.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2avmdjhuv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjjeqgj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2kclilocz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2veowvlho.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyukrsom.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2aouoyjfl.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2fittrshx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgigbjs.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfwtait.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmkzdrc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2llwxxaxe.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcihwrah.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2sachxcwd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2igjyfohu.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuhnrem.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2quokezbo.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2vqovixjy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdllhwli.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2wmimhpru.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbwyqus.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjxlcpj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2okqhmzex.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pirhnwfn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtaqnuhu.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhpdfvm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2iudyhttm.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkoultz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlhhwcq.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrkgbvu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnduxcw.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpltujb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2jntnqqki.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjgliao.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2useoiwpq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2umbtupms.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2rcudtwjz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyacxpv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwbklae.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2iltkqczh.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwsqiys.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kajcavkx.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgijxvl.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uaudryxi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxlpuix.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuokyiv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ucluswbt.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2evvpwaux.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2riwlzuju.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwangeo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzdmcqq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkvsggu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zowtmtpx.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rdghjioz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pasnxzjz.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2aruyxgyo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaccinjj.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jqffnhje.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bogsbnxu.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2uqljxakw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwixaal.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2diwhjbwn.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrqohxq.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2isgnvpgs.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpiyyrb.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdukjki.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iamxwwgo.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jckwwbxs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyckflyb.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcmsroo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2uancrqbt.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2expiwxqk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mswbjkvo.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsmjiqz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmftabpd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2hulwgzww.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mriihypl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrvqelg.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2twuqqhll.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2vdidwnjn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwemogi.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hizwhqaw.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhvjdtv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyewdqhz.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwdbddo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffstscea.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xhihxqjv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrpjios.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgspdqcl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2enebbnhd.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2delrrcvu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2raivgkxa.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmsstdv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbjynnw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2cepcdxmu.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zalnbjzc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhivjzb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2kaurgowk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjersqeb.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hckpwmln.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqnpmwa.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yisjagvp.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2facjapby.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgddoegl.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qjetpbqz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtkmxaw.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rafgpvcb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpbwdmt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqkprzu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2eilgzsfg.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxdsfuj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2veazzkwo.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hiemkjzm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2slhuakck.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rusomgut.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuzsxmh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2davyjhdm.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxkwkir.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfhzgma.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvprkvf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrhuqcu.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2npqvrdhw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqijyupq.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rztebjvo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mercbill.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnjxsan.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkgspmi.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2yoakhhdt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrocptt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcsokvq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjmdccx.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmgjvvn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2asdyunan.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfexaok.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvpuooi.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nirfejno.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpdalwk.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2blvikvfw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkoalyp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2opftrquu.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbqaimr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2laqnlutl.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxrijaj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lupccxgo.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwidbcq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2njkslftk.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fttfiqwf.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvylwmps.html


<!-- 参考信息 -->