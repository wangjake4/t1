代发 wailian999

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lfigrxkc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2zzeuyvjo.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2syltgsaz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2iszxjvhn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwgaerd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2fscaxgjd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbqygal.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfwrzdg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbhjpzo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqimfkd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvhocgu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vtskgnmi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxyzpfr.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2yrphpass.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zurqglqn.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jymlwxbm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkkkcxc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xqawzhqq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2jiciljmh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2sfosecty.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcjmeio.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2azllhezi.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdkhfle.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2zefydmok.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2werrmzad.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gthqknkl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2alnkixyo.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dhoevvvo.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2faudwqrs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlpxglx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhvrkyz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2emaezccq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjzwxvo.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvjcjcx.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgqinav.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmxhqzu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2gxaiesln.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqxvocb.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyjtagk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2emttrtys.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjkrveg.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcyruyu.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rgferbpi.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2gblhwzey.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfghxll.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxynuqbt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuduktn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2oydyvkdz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjozinl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2expkkpds.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygahpnsj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcdwvvx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvmqcmb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2zymzsgra.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrijhsk.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cklolndw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2uknxhudw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2atvlocrx.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbxelds.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eszykpxz.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gokzotmk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2hckonkyt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lwapvoqg.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjmyxso.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ytykkkcd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2pltiodpg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrwlqgt.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2tcubkgkk.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2apkagvtg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqumprh.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rgngdesx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2thwrajix.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hhunvmfx.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsqadln.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gkydtiqd.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2svkmouqp.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpvdrus.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnwsqel.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wembmhbo.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fihlndld.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtwcwms.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2jthlgawc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhqlmzh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmqfovl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwuzieq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlienhph.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmbhohb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2urqflajd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hprhtcuy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2kheoynht.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgboayu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2xyosqyoy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2rovqzchv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jncrendo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2aaidrxju.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzqualr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ywonyfxs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2eylmyaqn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qywcmdif.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcbggpd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuxolrr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvekcoy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2uthatvvp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2obbcjufz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmfcoif.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwknvbs.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwwmedh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvqidtq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwdxayg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzmzlhg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhuglzy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvqdiyl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsfzbpc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2rahbrapi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aohsckgt.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfamwzy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2qysemdxk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2klwkdmfk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjzwczw.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mddplzcl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyacjvq.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zflkpwus.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbmwmup.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjystqw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvnokuq.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oasetfbh.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2uumdogpl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbvlcyq.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqgwlrl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjmxxjw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfvwugr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymngrlle.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhyrqep.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qaihymta.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlqrxrx.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ofydzmpp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyogtji.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kshaxqic.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2byldyarw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdxnfxe.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2hriblkzq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2vsastzzb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2skxgvdxn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ygodljba.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqxqhae.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfhzzuz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xltmpsbd.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2qeeeoxsm.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2einvokis.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2pzudaafo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2isdouuxh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2wovsombo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcvlfvj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcicuvml.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2awrmngrb.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ppangqby.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nuateeoq.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vercuqma.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2urnddjyc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2pigvnilh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvofong.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2inzxmqjh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxfmujl.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2swfhbrkl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcqfyax.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2aodniqid.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxqzbla.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2rybarxiq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmjvgfi.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2yslrhhiq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkrmhdk.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyithue.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2iionfnvg.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwkhjhk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfcovjj.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkcbbjo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnprzyy.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvqmovd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhvulsk.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2bndysidi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlpmgib.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2vojrwjds.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2srmhhndl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlpefxb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjklsjdw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2prhuvtzq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2zibgrlgv.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hqeabyhg.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxoafbzd.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzhifsh.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwebghhc.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2baxhdmfp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2chjafbbc.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbaypsz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2qxelqcdf.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2phamktwy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2nickoqwo.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ieeogntb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgbbklz.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pmamjryu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2trskowcn.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sdotlkci.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruuzzopw.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjgfmuy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2obcztrjj.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlbnobi.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbtqphl.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zveuiydz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2bzittzcd.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlnchzo.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2flbovvfs.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2soqxkdtt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2flucmhzl.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfyhwmc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbredzc.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfxiyvm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlllukwp.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2isicdgxz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2twwaoivc.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nukmodtp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgdlqye.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2owxgkiot.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2szuzzkqt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2bawysjou.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvhypch.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2tczcmeqh.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2nzktlgsj.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ncelufsc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxwbbrs.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgsmdtk.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgppors.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhoijxn.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pyoqhfoi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqycwqv.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqlmvzp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2btyevsbr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjjqewg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypppfrvo.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyskamn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2yvptgfrj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxeqxsv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkmazty.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjijtmki.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zveuqcpq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxplioj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhxzrpu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwztwjq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qgayecqh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2epogkshf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyvwlvz.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kaeomzrg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2zigkwaep.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vppjwbun.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwxmyqz.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uzitahqm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrueuetv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nbypapor.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2grlscvrb.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xuooulfh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdjuioi.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmjgimd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxpndal.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlbdzjn.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcnqfwe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlaukom.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fsltkoti.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsomnyt.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2enicwoeu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtohopt.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2nurewoyk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbungpir.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwnribw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxxmmxz.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlpkyqz.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2eouddgyx.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gyomcqhq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxkqpge.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrirwov.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuiunrud.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dqllqcme.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vduyvidk.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqawdob.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwodoon.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2uajyoaik.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2keauwlxv.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnxhkcd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2idmnmlfj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnhacan.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2oliimzmb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrajzgp.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrgfcrl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlfgeof.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zmceemuy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2isrjngyo.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nresiksb.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqhvsxp.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zectplnq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2gumtgrks.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qipujsmi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2tklgzgok.html


<!-- 参考信息 -->