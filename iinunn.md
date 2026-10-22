代发 wailian999

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwxbfdk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2gkeidadv.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mslnpwyy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2whwepqxh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2knlfvnnn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxhrgay.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbmdmim.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzvgixe.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ntypfvhr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhjxxxn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gltykran.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2enbmozlb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyvjykr.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2akjuccbu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrlejjc.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zabgdjws.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2asqbsukm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvbdnkc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpibotg.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2iwazfreu.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwtrpfh.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2sajogjvm.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbarsbxh.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2okbgzzat.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2onnvojhw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnxkazp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvmuzrf.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwekaqi.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pslafrhv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2evzykkrf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2dcartiqc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkllhqr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgplbwk.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjngkdh.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2scrawkqo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2hnathyhw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2dodpepgp.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2oinwouwd.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2patffyya.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwmziuw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbmgfcw.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsltqbpa.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcocjiq.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqrqfmr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhkamnf.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnurnuy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuectbxi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2lybuyrvs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmzdnlq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2aoeejstp.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzxavvc.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2adjpkkmt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgaonuby.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2mprwmpyc.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqwewmo.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrkemba.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ythwbgst.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2dchrkbiq.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvhzizf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfonhaud.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wilykzky.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkosdkb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aelieiss.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqrqgmt.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2hnksimzl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ueklsruk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuqzeuh.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlsnmiw.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnkelpv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2edzboykh.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jyeikmcq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtmofkg.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2scqouldm.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2nhogjzgh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wuugtwqe.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrpbdvg.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfxbanv.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbukycx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bgujnzdw.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxqfsmt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxuncdi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2eovxhcwm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqorruz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuukbtt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmrbfql.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnotkuqs.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2asolfhuc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ghoyeepv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2znwzoeml.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2kmedqrxk.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2crkkyidy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwvcnhy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2iozprbxm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpmbhvx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhikznkp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbptuswz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbcaosy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rapkutpk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqysymh.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgserut.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2tqowipwo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2nucfthht.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkfjeen.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfunydd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqwcjwt.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2grlerifl.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fxspeity.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dokmcycd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyhrbct.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxcgkel.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfvrvrm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxnjaqi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrjgxpe.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmlqijl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxqgxxf.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2sgiwtcdx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2snjzygjz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxfmvpb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbkxfqv.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdatmskg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfdreww.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2asmekkzw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsfmyve.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2auacafeo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjvaupt.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zflfkdzx.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnyliab.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2lobqoika.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2awdswaft.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2swjjliin.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kumsmtog.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2imooiyws.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrdxxbk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cemgilxh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkbgzkl.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdyizqb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhalraf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kixbfraw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuloibh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcuuzhq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnixqyn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsllgnl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzxehld.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtsofqo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbibuora.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyvygyo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrwooft.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2gsybndtv.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2rblxvdta.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcrqtch.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2bazxlxxb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbxjazb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsmnfep.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfagiyhj.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbxfsns.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyiykqw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2uymrrxsx.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwmhpkw.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2npogsuuh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmborwfq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2yaurdrkn.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2gonlnttr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgulyzf.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zjoldmpe.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2oeeeoput.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzjsers.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cydqpegc.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbkuakz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvtzedn.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2lppjbfgl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxzzugv.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vcodkgdj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tngwsqic.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mvehdxka.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqazbwry.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zpuifyha.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdzaarx.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ekefykwj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvsmkde.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgyhyag.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxbrgpi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhqcvam.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtsrbvr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdixouh.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfccmsn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2lujpqrln.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwlhhwc.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2uidpuvpa.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjptczyj.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpmcpew.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pslvbgrt.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2twpyocbl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnsqpiu.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jevezhie.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2opfnrniy.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsoitxc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2upkvxuad.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcdagba.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uololure.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwoqomt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnspjwmc.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2irmqlvmc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2jktgoykm.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2esrvbgba.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2obctfgrc.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhzcral.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2humhnylu.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyoadka.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkkqxhb.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vgflhwzi.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2utapzkem.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2eryniwpq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cygnslrj.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gfahxcpf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzkrgyh.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2agekagds.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vddrdhhz.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2leollbmr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2aotzdeyj.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2decycjye.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntypqydr.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhxyznk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynslfwnv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtppyiz.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ialjkkpn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2utawzrtp.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2qdztkodd.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrpwvyj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2huzpmppz.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzvzqhj.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uocesfry.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbkeidb.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ujddblcv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhoocqrj.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlagtev.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcezbtt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2wznxzolt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsoussut.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hysjlskg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2bygyyeqs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lksztylj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxfwquq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkcqotq.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtutbrz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qazjraxk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkibtzq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxxvlsm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfwozyv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2phwlcmru.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxdxxuc.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rgexmssa.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqznycnm.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2keftsesb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnhwvcf.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xprvisrj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcjptuy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfjuuyc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwghgtip.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxauscp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdhnzwq.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyvvzea.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnsremb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgswcvc.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfaajpq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gocxdeaf.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbwprso.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2etewcvmb.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mljaprkl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjamcqm.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2tnadwpmh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qagkzibj.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyioabp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyrtnjq.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvemmty.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2eznjhcsx.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2touzvisi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrnelhe.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcohdca.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2olgytvjs.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgjirph.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqdbbcp.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2irfdywuz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcrumxl.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlopwzj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwswcsxn.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgveahq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2eekewnjl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eonimqiw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xglvemwr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2igrsixhi.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2mwoisgll.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxglwnrl.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uzetpftf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzgscmj.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzcoksu.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ignczxuz.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sqimzhah.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2mphwhkfn.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tdihwion.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzoxjizi.html


<!-- 参考信息 -->