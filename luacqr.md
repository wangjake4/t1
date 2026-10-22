代发 wailian999

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2irtymbio.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuiojyz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2orlzlpsc.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxzxhoz.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2costaspy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2uppikzys.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqykach.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xfihhqlb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyhxcic.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqsrnoy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bnekprzm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rztrjhkb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nizygnvh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsoocje.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wncbwgao.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjvlzip.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2glucccum.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2pkebstyp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhmhawm.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ywevabko.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2evlxoqdp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zjexjjue.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2mvprmfhj.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxnryeg.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyglkvh.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvpjlbb.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmpvvhl.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2cnspfsvv.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2douriyuf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcajptyn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2voigymlk.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2piogevkb.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gukyaerq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmejotz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuncpmc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdzecrz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2olzkomte.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2gapzzgaw.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dfclyqis.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ztogfadc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmmjjqy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjldtqw.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtquezb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2twnqimqx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tugwybpp.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zceigzsv.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fxamnfjl.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2swkaxtph.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2eumtydnq.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpaixzju.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqfagpz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ovroteqg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhieucd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ymriwpjs.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzjvgsc.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2egxkndss.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaphtidk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2veamxbkr.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtlmjcp.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlhcanp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2beyihapi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbakxrac.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvtvnar.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ildbktgc.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2swjzleuf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2simiiytt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2orbcxxrl.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbquyma.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvogfft.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2xkaglylv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2qzekdxqf.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsxtapb.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2txussikv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhzqjlw.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qivdohya.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2asyfxizk.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2tpiegsaj.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2gbebcmpo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxtqcbf.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqlskzm.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfmspeh.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywryzels.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkhxlxd.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fesetqap.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2haxkgeol.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgywqsx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwjppvd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2huaicxvk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2qasiicub.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2oguwropa.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2rancpmil.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bvljoten.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxgbkgz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzecouf.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ujassgla.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqmschh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqvalsd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlfmjci.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2znpmfkxx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxaozwr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzjdywg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2npwfxmcn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2utemergb.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlwexul.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2fosfvefx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hagejlqg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nugqppte.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2iyypaadc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzogqji.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpjtzhd.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ysuhdnyv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bgelsyic.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrftpjh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2yevtqezx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2detnrqhk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2quwiwggk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2otsqbhcx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2uiixjsgq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmgqpma.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqobckt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2gsiltcsy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxfjyvd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2onodqxlz.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzflatt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2abezyryc.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kksziohr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjeljfhp.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvveipzx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfslcyk.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhlgyul.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ngeqrwym.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2qopzrwhc.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uixcrhfl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2txmszivq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2daimlwnm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncslbpue.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2hhigbiuo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfdbhsd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2engpllad.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2clncnwdd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kexyusbq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgzoirt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2bpezegub.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnowzys.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdxsutk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkzggqu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtqdqdt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzrufih.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fclhrdhu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2afaovgqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jllnsyie.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrefflh.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtirlcx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jizzinda.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcgcsxh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2vimqdamt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkrirhn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcblbyrg.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmalesu.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsnuahp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjzsbfb.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qbeyqavc.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2trlpdfhv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqurvion.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2czhfamgk.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2elhmcohs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtibxzp.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fenyjymg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvwjxqq.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2hoichymb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejibzqra.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbbueiu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxvhrbx.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2habwnhui.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcabrbnm.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nuasqsfd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpkvgnr.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvupshm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpkhhev.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2brlvrcnc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnwimjp.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqakjps.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrgbvga.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2shevrpar.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2rkecrgdr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcfbhak.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2xndfesoj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xtybbvrw.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2lohkyqjj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2hynzpnaz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2cykfoqrz.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwnioww.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2opvmdpbt.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hltxdcfk.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2svsxonbr.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bbitljtz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kipdpiom.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2clmnwwrz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2itumowtn.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2futqpobj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2olqjhaid.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlnqmcz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vknasoxx.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mherqhpw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfimhyur.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyqpbsi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2wswrayjr.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlsknma.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2bujemmbj.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2uinnrijh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvvzdal.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hyekgvnl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2olqzljiy.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbljsjr.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbgmsbq.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwztmesu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgpdtgn.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqvqmdc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vttgqhsz.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zohaxygf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcscoqjb.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pimjdsgu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2txvwvhkr.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tplyerfk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvwvgmf.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmfowjc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bapktwpg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbprxzo.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvbvhms.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlsozmk.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzjoels.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrvwsfm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2deelnelm.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaiyxqip.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dejtxsyy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxiorwzt.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yusxbuxn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pioqlxxc.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xxquiyux.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuonmwp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzqmpci.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrpwlqf.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2cadvifyr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2isxvbxzh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbokqfwq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqtrtfs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2trgexwsf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmwzaqw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfdlznl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xwykokoi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwwzply.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmynemz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhmlkia.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndazbgqo.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kejreozb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2bziwletg.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmbxmko.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxtegea.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsjhffz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfntwqnj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gfplexww.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtefose.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xucuxyjw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2eybtcoao.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2olphhjoo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ourxngag.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyaiazp.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkruwhp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2keabmhcb.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqxjavb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbfglbn.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jibqjvbu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2apnizuzj.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2lukszqfl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2usedeqeh.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dguyvdkg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyyzmgp.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmyzoph.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2hoswcfbx.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2uguocois.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiydgevn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmesvrsd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkslmuw.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2aivagcpd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkykkqfo.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fafxlxcc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfxbcxi.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxonapj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjqhsjk.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcmqftv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2axlmacia.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2psvqktys.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2iijfavke.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvmmcbt.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvwqrku.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdticzfb.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxxkcoy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwgrakh.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hpplwkev.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2whykjuhm.html


<!-- 参考信息 -->